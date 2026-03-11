# Weibo Signal Tracker

Narrative signal monitoring system that tracks Weibo trending search data with velocity analysis and lifecycle detection.

## Live Demo

**[https://arandomguyhere.github.io/weibo-daily-hot-search](https://arandomguyhere.github.io/weibo-daily-hot-search)**

Browse historical trending data with status badges, velocity indicators, and category filters.

## Features

- **Signal tracking**: Scrapes Weibo trending every 5 minutes, tracks up to 100 topics per day
- **Lifecycle detection**: Each topic tagged as `NEW`, `RISING`, `HOT`, `FALLING`, or `GONE`
- **Velocity analysis**: Percentage change between scrapes shows acceleration/deceleration
- **Suppression detection**: Topics that disappear from the feed are marked as `GONE`
- **English translations**: Auto-translated via Google Translate for non-Chinese readers
- **Dark mode + filters**: Filter by status category, search by Chinese or English text
- **Engagement metrics**: Top topics enriched with likes, comments, and reposts from related posts

## Today's Hot Searches

<!-- BEGIN -->

1. [第3场委员通道 (Game 3 committee member channel)](https://s.weibo.com/weibo?q=%23%E7%AC%AC3%E5%9C%BA%E5%A7%94%E5%91%98%E9%80%9A%E9%81%93%23) `995.2K 🔥` `NEW`
1. [美国被曝考虑派兵夺取伊朗哈尔克岛](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E8%A2%AB%E6%9B%9D%E8%80%83%E8%99%91%E6%B4%BE%E5%85%B5%E5%A4%BA%E5%8F%96%E4%BC%8A%E6%9C%97%E5%93%88%E5%B0%94%E5%85%8B%E5%B2%9B%23) `91.5K 🔥` `NEW`
1. [电锯人将完结](https://s.weibo.com/weibo?q=%23%E7%94%B5%E9%94%AF%E4%BA%BA%E5%B0%86%E5%AE%8C%E7%BB%93%23) `76.4K 🔥` `NEW`
1. [伊朗要给美以一个教训](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A6%81%E7%BB%99%E7%BE%8E%E4%BB%A5%E4%B8%80%E4%B8%AA%E6%95%99%E8%AE%AD%23) `67.5K 🔥` `NEW`
1. [装虾499卸载299](https://s.weibo.com/weibo?q=%23%E8%A3%85%E8%99%BE499%E5%8D%B8%E8%BD%BD299%23) `65.8K 🔥` `NEW`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `320.7K 🔥` `+25%`
1. [对台绝不承诺放弃使用武力 (We will never commit to giving up the use of force against Taiwan)](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E5%8F%B0%E7%BB%9D%E4%B8%8D%E6%89%BF%E8%AF%BA%E6%94%BE%E5%BC%83%E4%BD%BF%E7%94%A8%E6%AD%A6%E5%8A%9B%23) `251.8K 🔥` `+47%`
1. [欧冠 (Champions League)](https://s.weibo.com/weibo?q=%23%E6%AC%A7%E5%86%A0%23) `245.5K 🔥` `+43%`
1. [3月11日两会日程](https://s.weibo.com/weibo?q=%233%E6%9C%8811%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%23) `230.8K 🔥` `+35%`
1. [建议高速每年1000元免费额度](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%AB%98%E9%80%9F%E6%AF%8F%E5%B9%B41000%E5%85%83%E5%85%8D%E8%B4%B9%E9%A2%9D%E5%BA%A6%23) `206.4K 🔥` `+21%`
1. [伊朗下起毒雨](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8B%E8%B5%B7%E6%AF%92%E9%9B%A8%23) `189.0K 🔥` `+42%`
1. [王励勤希望樊振东能代表国家征战](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B1%E5%8B%A4%E5%B8%8C%E6%9C%9B%E6%A8%8A%E6%8C%AF%E4%B8%9C%E8%83%BD%E4%BB%A3%E8%A1%A8%E5%9B%BD%E5%AE%B6%E5%BE%81%E6%88%98%23) `168.7K 🔥` `+106%`
1. [豆包限制AI成毅 (Doubao limits AI into Yi)](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E9%99%90%E5%88%B6AI%E6%88%90%E6%AF%85%23) `147.1K 🔥` `+21%`
1. [杨紫紫色高定 (Yang Zi purple haute couture)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%B4%AB%E8%89%B2%E9%AB%98%E5%AE%9A%23) `106.7K 🔥` `+28%`
1. [雷军新闻联播镜头 (Lei Jun News Network footage)](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E6%96%B0%E9%97%BB%E8%81%94%E6%92%AD%E9%95%9C%E5%A4%B4%23) `91.0K 🔥` `+22%`
1. [中国两会将为全球创造更多机遇 (China’s Two Sessions will create more opportunities for the world)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E5%B0%86%E4%B8%BA%E5%85%A8%E7%90%83%E5%88%9B%E9%80%A0%E6%9B%B4%E5%A4%9A%E6%9C%BA%E9%81%87%23) `552.3K 🔥`
1. [外媒记者期待与中国共享发展新机遇 (Foreign journalists look forward to sharing new development opportunities with China)](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%AA%92%E8%AE%B0%E8%80%85%E6%9C%9F%E5%BE%85%E4%B8%8E%E4%B8%AD%E5%9B%BD%E5%85%B1%E4%BA%AB%E5%8F%91%E5%B1%95%E6%96%B0%E6%9C%BA%E9%81%87%23) `203.4K 🔥`
1. [地球或将迎超级厄尔尼诺现象](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E7%90%83%E6%88%96%E5%B0%86%E8%BF%8E%E8%B6%85%E7%BA%A7%E5%8E%84%E5%B0%94%E5%B0%BC%E8%AF%BA%E7%8E%B0%E8%B1%A1%23) `188.2K 🔥`
1. [伊朗提出停火条件 (Iran proposes ceasefire conditions)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8F%90%E5%87%BA%E5%81%9C%E7%81%AB%E6%9D%A1%E4%BB%B6%23) `187.5K 🔥`
1. [老夫妻双双129岁相恋100年引质疑 (An old couple, both 129 years old, have been in love for 100 years, raising questions)](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%A4%AB%E5%A6%BB%E5%8F%8C%E5%8F%8C129%E5%B2%81%E7%9B%B8%E6%81%8B100%E5%B9%B4%E5%BC%95%E8%B4%A8%E7%96%91%23) `186.3K 🔥`
1. [日本是一个老龄化很严重的国家](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%98%AF%E4%B8%80%E4%B8%AA%E8%80%81%E9%BE%84%E5%8C%96%E5%BE%88%E4%B8%A5%E9%87%8D%E7%9A%84%E5%9B%BD%E5%AE%B6%23) `185.8K 🔥`
1. [业内人士谈小米汽车被销售嘲讽](https://s.weibo.com/weibo?q=%23%E4%B8%9A%E5%86%85%E4%BA%BA%E5%A3%AB%E8%B0%88%E5%B0%8F%E7%B1%B3%E6%B1%BD%E8%BD%A6%E8%A2%AB%E9%94%80%E5%94%AE%E5%98%B2%E8%AE%BD%23) `183.9K 🔥`
1. [苹果最便宜手机来了](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E6%9D%A5%E4%BA%86%23) `183.1K 🔥`
1. [陈昊宇新剧给自己生了个弟弟](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%98%8A%E5%AE%87%E6%96%B0%E5%89%A7%E7%BB%99%E8%87%AA%E5%B7%B1%E7%94%9F%E4%BA%86%E4%B8%AA%E5%BC%9F%E5%BC%9F%23) `182.8K 🔥`
1. [我要回伊朗我要保卫我的国家 (I want to go back to Iran and I want to defend my country)](https://s.weibo.com/weibo?q=%23%E6%88%91%E8%A6%81%E5%9B%9E%E4%BC%8A%E6%9C%97%E6%88%91%E8%A6%81%E4%BF%9D%E5%8D%AB%E6%88%91%E7%9A%84%E5%9B%BD%E5%AE%B6%23) `161.6K 🔥`
1. [伊朗逮捕81名内鬼](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%80%AE%E6%8D%9581%E5%90%8D%E5%86%85%E9%AC%BC%23) `144.8K 🔥`
1. [原来这些爆火的文案都是王源写的 (It turns out that these popular copywritings were all written by Wang Yuan)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E4%BA%9B%E7%88%86%E7%81%AB%E7%9A%84%E6%96%87%E6%A1%88%E9%83%BD%E6%98%AF%E7%8E%8B%E6%BA%90%E5%86%99%E7%9A%84%23) `131.7K 🔥`
1. [婆婆进卧室不敲门儿媳崩溃哭诉 (The mother-in-law entered the bedroom without knocking, and the daughter-in-law broke down and cried.)](https://s.weibo.com/weibo?q=%23%E5%A9%86%E5%A9%86%E8%BF%9B%E5%8D%A7%E5%AE%A4%E4%B8%8D%E6%95%B2%E9%97%A8%E5%84%BF%E5%AA%B3%E5%B4%A9%E6%BA%83%E5%93%AD%E8%AF%89%23) `128.4K 🔥`
1. [刘国梁卸任WTT董事会主席 (Liu Guoliang steps down as chairman of WTT board of directors)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%9B%BD%E6%A2%81%E5%8D%B8%E4%BB%BBWTT%E8%91%A3%E4%BA%8B%E4%BC%9A%E4%B8%BB%E5%B8%AD%23) `118.6K 🔥`
1. [突然一下就不焦虑了](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E4%B8%80%E4%B8%8B%E5%B0%B1%E4%B8%8D%E7%84%A6%E8%99%91%E4%BA%86%23) `110.3K 🔥`
1. [张凌赫道歉 (Zhang Linghe apologizes)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E9%81%93%E6%AD%89%23) `91.4K 🔥`
1. [JYP考公上岸了 (JYP’s public examination is now available)](https://s.weibo.com/weibo?q=%23JYP%E8%80%83%E5%85%AC%E4%B8%8A%E5%B2%B8%E4%BA%86%23) `86.7K 🔥`
1. [杨紫周翊然活动同台](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E5%91%A8%E7%BF%8A%E7%84%B6%E6%B4%BB%E5%8A%A8%E5%90%8C%E5%8F%B0%23) `83.9K 🔥`
1. [你好星期六删除张凌赫争议片段 (Hello Saturday deletes Zhang Linghe controversial clip)](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD%E6%98%9F%E6%9C%9F%E5%85%AD%E5%88%A0%E9%99%A4%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%BA%89%E8%AE%AE%E7%89%87%E6%AE%B5%23) `76.2K 🔥`
1. [刘亦菲ins更新看秀照 (Liu Yifei’s ins updates, see show photos)](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2ins%E6%9B%B4%E6%96%B0%E7%9C%8B%E7%A7%80%E7%85%A7%23) `75.9K 🔥`
1. [小猫捧着耶耶的脸亲了两下](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E6%8D%A7%E7%9D%80%E8%80%B6%E8%80%B6%E7%9A%84%E8%84%B8%E4%BA%B2%E4%BA%86%E4%B8%A4%E4%B8%8B%23) `75.5K 🔥`
1. [亲爱的客栈第二期热度](https://s.weibo.com/weibo?q=%23%E4%BA%B2%E7%88%B1%E7%9A%84%E5%AE%A2%E6%A0%88%E7%AC%AC%E4%BA%8C%E6%9C%9F%E7%83%AD%E5%BA%A6%23) `75.0K 🔥`
1. [批发商回应4.5元的1米大肉串卖20元 (The wholesaler responded that a 1-meter-large meat skewer sold for NT$20 for NT$4.50.)](https://s.weibo.com/weibo?q=%23%E6%89%B9%E5%8F%91%E5%95%86%E5%9B%9E%E5%BA%944.5%E5%85%83%E7%9A%841%E7%B1%B3%E5%A4%A7%E8%82%89%E4%B8%B2%E5%8D%9620%E5%85%83%23) `71.8K 🔥`
1. [22个月大宝宝在院子里慵懒躺倒晒太阳 (The 22-month-old baby lay lazily in the yard and basked in the sun)](https://s.weibo.com/weibo?q=%2322%E4%B8%AA%E6%9C%88%E5%A4%A7%E5%AE%9D%E5%AE%9D%E5%9C%A8%E9%99%A2%E5%AD%90%E9%87%8C%E6%85%B5%E6%87%92%E8%BA%BA%E5%80%92%E6%99%92%E5%A4%AA%E9%98%B3%23) `69.8K 🔥`
1. [李在明回应萨德外调 (Lee Jae-ming responds to THAAD’s external report)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%9C%A8%E6%98%8E%E5%9B%9E%E5%BA%94%E8%90%A8%E5%BE%B7%E5%A4%96%E8%B0%83%23) `64.6K 🔥`
1. [王源是环球人物6年专栏作家 (Wang Yuan has been a columnist for Global People for 6 years)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BA%90%E6%98%AF%E7%8E%AF%E7%90%83%E4%BA%BA%E7%89%A96%E5%B9%B4%E4%B8%93%E6%A0%8F%E4%BD%9C%E5%AE%B6%23) `63.2K 🔥`
1. [哈哈哈哈哈6 (Hahahahaha 6)](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%93%88%E5%93%88%E5%93%88%E5%93%886%23) `62.9K 🔥`
1. [鹿晗喝霸王茶姬 (Lu Han drinks Bawang Cha Ji)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E5%96%9D%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%23) `61.4K 🔥`
1. [AG憾负PRX](https://s.weibo.com/weibo?q=%23AG%E6%86%BE%E8%B4%9FPRX%23) `61.4K 🔥`
1. [去机场不该比坐飞机时间还长 (Getting to the airport shouldn't take longer than flying)](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E6%9C%BA%E5%9C%BA%E4%B8%8D%E8%AF%A5%E6%AF%94%E5%9D%90%E9%A3%9E%E6%9C%BA%E6%97%B6%E9%97%B4%E8%BF%98%E9%95%BF%23) `738.6K 🔥` `-22%`
1. [建议不允许青少年用AI做作业 (It is recommended that teenagers not be allowed to use AI to do homework)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%8D%E5%85%81%E8%AE%B8%E9%9D%92%E5%B0%91%E5%B9%B4%E7%94%A8AI%E5%81%9A%E4%BD%9C%E4%B8%9A%23) `189.3K 🔥` `-73%`
1. [伊朗高官6种语言发帖](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%AB%98%E5%AE%986%E7%A7%8D%E8%AF%AD%E8%A8%80%E5%8F%91%E5%B8%96%23) `61.4K 🔥` `-27%`
1. [中国队金牌榜奖牌榜都是第一](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E9%87%91%E7%89%8C%E6%A6%9C%E5%A5%96%E7%89%8C%E6%A6%9C%E9%83%BD%E6%98%AF%E7%AC%AC%E4%B8%80%23) `55.4K 🔥` `-26%`

Updated at 2026-03-11 08:00:17

<!-- END -->

## Data Reference

### Directory Structure

```
├── raw/                    # Raw JSON data
│   └── YYYY-MM-DD.json     # Daily hot search data
├── index.html              # GitHub Pages frontend
├── mod.ts                  # Scraping script (Deno)
├── bridge.py               # Data bridge to WeiboInsight/MongoDB
└── WeiboInsight/           # Submodule: Playwright-based deep analysis
```

### Data Format

Daily JSON format (`raw/YYYY-MM-DD.json`):

```json
[
  {
    "url": "/weibo?q=%23Topic%23",
    "text": "Topic",
    "textEn": "Topic in English",
    "count": 1234567,
    "firstSeen": "2026-02-07T08:15:00.000Z",
    "peakCount": 1500000,
    "prevCount": 900000,
    "status": "rising",
    "velocity": 37,
    "engagement": { "posts": 15, "likes": 45200, "comments": 3100, "reposts": 8900 }
  }
]
```

| Field | Description |
|-------|-------------|
| `url` | Weibo search link path |
| `text` | Trending topic text (Chinese) |
| `textEn` | English translation (optional) |
| `count` | Heat value from Weibo API |
| `firstSeen` | ISO timestamp when topic first appeared today |
| `peakCount` | Highest count recorded for this topic today |
| `prevCount` | Count from previous scrape cycle |
| `status` | Lifecycle stage: `new`, `rising`, `hot`, `falling`, `gone` |
| `velocity` | Percentage change from previous scrape |
| `engagement` | Post engagement metrics (top 10 topics): posts, likes, comments, reposts |

## Tech Stack

- **Runtime**: [Deno](https://deno.land/)
- **Automation**: GitHub Actions (cron)
- **Frontend**: Vanilla HTML/CSS/JavaScript
- **Hosting**: GitHub Pages

## Local Development

```bash
# Install Deno
curl -fsSL https://deno.land/install.sh | sh

# Run the scraper
deno run --allow-net --allow-read --allow-write --import-map=import_map.json mod.ts
```

## WeiboInsight Integration

This project includes [WeiboInsight](https://github.com/arandomguyhere/WeiboInsight) as a submodule for deep NLP analysis of trending topics.

**What each project does:**
- **weibo-daily-hot-search** — Lightweight Deno scraper that tracks trending topics every 5 min via JSON APIs, with lifecycle/velocity analysis
- **WeiboInsight** — Python/Playwright-based scraper with Scrapy pipelines, MongoDB storage, Jieba segmentation, LDA topic modeling, and K-Means clustering

**How they connect:**
1. This scraper collects trending topics + engagement data every 5 minutes
2. `bridge.py` imports the JSON data into MongoDB with text segmentation
3. WeiboInsight's `analyze_weibo_data.py` runs NLP analysis on the imported data

```bash
# Setup
git submodule update --init
cd WeiboInsight && pip install -r requirements.txt && cd ..
pip install pymongo jieba

# Import data into MongoDB
python bridge.py --all

# Run NLP analysis
cd WeiboInsight/scrapy_project
python analyze_weibo_data.py
```

## Related Projects

- [WeiboInsight](https://github.com/arandomguyhere/WeiboInsight) — Playwright-based Weibo CTI analysis
- [V2EX Daily Hot Topics](https://github.com/boojack/v2ex-daily-hot-topic)
- [jackylee1/weibo-daily-hot-search](https://github.com/jackylee1/weibo-daily-hot-search) — Original project

## License

MIT
