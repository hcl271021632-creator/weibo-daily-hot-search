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

1. [政协会议闭幕 (CPPCC meeting closes)](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%8D%8F%E4%BC%9A%E8%AE%AE%E9%97%AD%E5%B9%95%23) `1.0M 🔥` `NEW`
1. [工作不满10年休5天年假规则该调整](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%BD%9C%E4%B8%8D%E6%BB%A110%E5%B9%B4%E4%BC%915%E5%A4%A9%E5%B9%B4%E5%81%87%E8%A7%84%E5%88%99%E8%AF%A5%E8%B0%83%E6%95%B4%23) `994.5K 🔥` `NEW`
1. [闲鱼空间体火了](https://s.weibo.com/weibo?q=%23%E9%97%B2%E9%B1%BC%E7%A9%BA%E9%97%B4%E4%BD%93%E7%81%AB%E4%BA%86%23) `949.2K 🔥` `NEW`
1. [阿德巴约83分](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A683%E5%88%86%23) `934.8K 🔥` `NEW`
1. [等我小了我也要这么晒太阳](https://s.weibo.com/weibo?q=%23%E7%AD%89%E6%88%91%E5%B0%8F%E4%BA%86%E6%88%91%E4%B9%9F%E8%A6%81%E8%BF%99%E4%B9%88%E6%99%92%E5%A4%AA%E9%98%B3%23) `914.5K 🔥` `NEW`
1. [阿德巴约现役得分王](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A6%E7%8E%B0%E5%BD%B9%E5%BE%97%E5%88%86%E7%8E%8B%23) `554.9K 🔥` `NEW`
1. [政协会议圆满完成各项议程](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%8D%8F%E4%BC%9A%E8%AE%AE%E5%9C%86%E6%BB%A1%E5%AE%8C%E6%88%90%E5%90%84%E9%A1%B9%E8%AE%AE%E7%A8%8B%23) `212.0K 🔥` `NEW`
1. [逐玉原著的女主](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8E%9F%E8%91%97%E7%9A%84%E5%A5%B3%E4%B8%BB%23) `202.8K 🔥` `NEW`
1. [美国要求以色列勿袭伊朗能源设施](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E8%A6%81%E6%B1%82%E4%BB%A5%E8%89%B2%E5%88%97%E5%8B%BF%E8%A2%AD%E4%BC%8A%E6%9C%97%E8%83%BD%E6%BA%90%E8%AE%BE%E6%96%BD%23) `194.9K 🔥` `NEW`
1. [王励勤称正在与樊振东沟通](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B1%E5%8B%A4%E7%A7%B0%E6%AD%A3%E5%9C%A8%E4%B8%8E%E6%A8%8A%E6%8C%AF%E4%B8%9C%E6%B2%9F%E9%80%9A%23) `163.0K 🔥` `NEW`
1. [哈哈哈哈哈6铁三角回归 (Hahahahaha 6 iron triangle returns)](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%93%88%E5%93%88%E5%93%88%E5%93%886%E9%93%81%E4%B8%89%E8%A7%92%E5%9B%9E%E5%BD%92%23) `159.8K 🔥` `NEW`
1. [阿德巴约单节31分](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A6%E5%8D%95%E8%8A%8231%E5%88%86%23) `139.4K 🔥` `NEW`
1. [相差十岁的兄妹一天没见就紧紧相拥](https://s.weibo.com/weibo?q=%23%E7%9B%B8%E5%B7%AE%E5%8D%81%E5%B2%81%E7%9A%84%E5%85%84%E5%A6%B9%E4%B8%80%E5%A4%A9%E6%B2%A1%E8%A7%81%E5%B0%B1%E7%B4%A7%E7%B4%A7%E7%9B%B8%E6%8B%A5%23) `106.2K 🔥` `NEW`
1. [刘冲选的刘浩存李庚希封面图](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%86%B2%E9%80%89%E7%9A%84%E5%88%98%E6%B5%A9%E5%AD%98%E6%9D%8E%E5%BA%9A%E5%B8%8C%E5%B0%81%E9%9D%A2%E5%9B%BE%23) `106.0K 🔥` `NEW`
1. [敖瑞鹏不二之臣婚礼路透](https://s.weibo.com/weibo?q=%23%E6%95%96%E7%91%9E%E9%B9%8F%E4%B8%8D%E4%BA%8C%E4%B9%8B%E8%87%A3%E5%A9%9A%E7%A4%BC%E8%B7%AF%E9%80%8F%23) `103.7K 🔥` `NEW`
1. [伊朗发起第37波打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC37%E6%B3%A2%E6%89%93%E5%87%BB%23) `102.6K 🔥` `NEW`
1. [刘亦菲行走的玫瑰花](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E8%A1%8C%E8%B5%B0%E7%9A%84%E7%8E%AB%E7%91%B0%E8%8A%B1%23) `102.0K 🔥` `NEW`
1. [成员回应李羲承退队](https://s.weibo.com/weibo?q=%23%E6%88%90%E5%91%98%E5%9B%9E%E5%BA%94%E6%9D%8E%E7%BE%B2%E6%89%BF%E9%80%80%E9%98%9F%23) `101.2K 🔥` `NEW`
1. [NBA](https://s.weibo.com/weibo?q=%23NBA%23) `101.1K 🔥` `NEW`
1. [伊朗逮捕10名伊斯兰革命卫队成员](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%80%AE%E6%8D%9510%E5%90%8D%E4%BC%8A%E6%96%AF%E5%85%B0%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E6%88%90%E5%91%98%23) `101.0K 🔥` `NEW`
1. [广西一山洞内景似世外桃源 (The interior of a cave in Guangxi looks like a paradise)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E8%A5%BF%E4%B8%80%E5%B1%B1%E6%B4%9E%E5%86%85%E6%99%AF%E4%BC%BC%E4%B8%96%E5%A4%96%E6%A1%83%E6%BA%90%23) `100.9K 🔥` `NEW`
1. [两会](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `100.8K 🔥` `NEW`
1. [周杰伦将举行发片记者会](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E5%B0%86%E4%B8%BE%E8%A1%8C%E5%8F%91%E7%89%87%E8%AE%B0%E8%80%85%E4%BC%9A%23) `100.8K 🔥` `NEW`
1. [姐姐是大将军姐夫是摄政王](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E6%98%AF%E5%A4%A7%E5%B0%86%E5%86%9B%E5%A7%90%E5%A4%AB%E6%98%AF%E6%91%84%E6%94%BF%E7%8E%8B%23) `100.6K 🔥` `NEW`
1. [衣食住行就是人的气运](https://s.weibo.com/weibo?q=%23%E8%A1%A3%E9%A3%9F%E4%BD%8F%E8%A1%8C%E5%B0%B1%E6%98%AF%E4%BA%BA%E7%9A%84%E6%B0%94%E8%BF%90%23) `100.6K 🔥` `NEW`
1. [孔雪儿俞浅浅含泪发脾气](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E4%BF%9E%E6%B5%85%E6%B5%85%E5%90%AB%E6%B3%AA%E5%8F%91%E8%84%BE%E6%B0%94%23) `100.5K 🔥` `NEW`
1. [车还能用电池先老了](https://s.weibo.com/weibo?q=%23%E8%BD%A6%E8%BF%98%E8%83%BD%E7%94%A8%E7%94%B5%E6%B1%A0%E5%85%88%E8%80%81%E4%BA%86%23) `100.5K 🔥` `NEW`
1. [国际油价经历过山车行情](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%99%85%E6%B2%B9%E4%BB%B7%E7%BB%8F%E5%8E%86%E8%BF%87%E5%B1%B1%E8%BD%A6%E8%A1%8C%E6%83%85%23) `100.4K 🔥` `NEW`
1. [奇才vs热火](https://s.weibo.com/weibo?q=%23%E5%A5%87%E6%89%8Dvs%E7%83%AD%E7%81%AB%23) `100.3K 🔥` `NEW`
1. [逐玉原著vs剧版](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8E%9F%E8%91%97vs%E5%89%A7%E7%89%88%23) `100.3K 🔥` `NEW`
1. [杨扬谈中国短道冬奥成绩 (Yang Yang talks about China’s short track Winter Olympics results)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%89%AC%E8%B0%88%E4%B8%AD%E5%9B%BD%E7%9F%AD%E9%81%93%E5%86%AC%E5%A5%A5%E6%88%90%E7%BB%A9%23) `100.1K 🔥` `NEW`
1. [董明珠说年轻人有压力是好事](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%98%8E%E7%8F%A0%E8%AF%B4%E5%B9%B4%E8%BD%BB%E4%BA%BA%E6%9C%89%E5%8E%8B%E5%8A%9B%E6%98%AF%E5%A5%BD%E4%BA%8B%23) `100.0K 🔥` `NEW`
1. [魏晨一句话陈哲远天塌了](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E6%99%A8%E4%B8%80%E5%8F%A5%E8%AF%9D%E9%99%88%E5%93%B2%E8%BF%9C%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `99.9K 🔥` `NEW`
1. [中国两会将为全球创造更多机遇 (China’s Two Sessions will create more opportunities for the world)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E5%B0%86%E4%B8%BA%E5%85%A8%E7%90%83%E5%88%9B%E9%80%A0%E6%9B%B4%E5%A4%9A%E6%9C%BA%E9%81%87%23) `955.1K 🔥` `+73%`
1. [伊朗下起毒雨](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8B%E8%B5%B7%E6%AF%92%E9%9B%A8%23) `903.1K 🔥` `+378%`
1. [3月11日两会日程](https://s.weibo.com/weibo?q=%233%E6%9C%8811%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%23) `667.4K 🔥` `+189%`
1. [22个月大宝宝在院子里慵懒躺倒晒太阳 (The 22-month-old baby lay lazily in the yard and basked in the sun)](https://s.weibo.com/weibo?q=%2322%E4%B8%AA%E6%9C%88%E5%A4%A7%E5%AE%9D%E5%AE%9D%E5%9C%A8%E9%99%A2%E5%AD%90%E9%87%8C%E6%85%B5%E6%87%92%E8%BA%BA%E5%80%92%E6%99%92%E5%A4%AA%E9%98%B3%23) `100.1K 🔥` `+43%`
1. [苹果最便宜手机来了](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E6%9D%A5%E4%BA%86%23) `184.0K 🔥`
1. [豆包限制AI成毅 (Doubao limits AI into Yi)](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E9%99%90%E5%88%B6AI%E6%88%90%E6%AF%85%23) `172.5K 🔥`
1. [日本是一个老龄化很严重的国家](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%98%AF%E4%B8%80%E4%B8%AA%E8%80%81%E9%BE%84%E5%8C%96%E5%BE%88%E4%B8%A5%E9%87%8D%E7%9A%84%E5%9B%BD%E5%AE%B6%23) `167.8K 🔥`
1. [老夫妻双双129岁相恋100年引质疑 (An old couple, both 129 years old, have been in love for 100 years, raising questions)](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%A4%AB%E5%A6%BB%E5%8F%8C%E5%8F%8C129%E5%B2%81%E7%9B%B8%E6%81%8B100%E5%B9%B4%E5%BC%95%E8%B4%A8%E7%96%91%23) `159.2K 🔥`
1. [美国被曝考虑派兵夺取伊朗哈尔克岛](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E8%A2%AB%E6%9B%9D%E8%80%83%E8%99%91%E6%B4%BE%E5%85%B5%E5%A4%BA%E5%8F%96%E4%BC%8A%E6%9C%97%E5%93%88%E5%B0%94%E5%85%8B%E5%B2%9B%23) `101.3K 🔥`
1. [去机场不该比坐飞机时间还长 (Getting to the airport shouldn't take longer than flying)](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E6%9C%BA%E5%9C%BA%E4%B8%8D%E8%AF%A5%E6%AF%94%E5%9D%90%E9%A3%9E%E6%9C%BA%E6%97%B6%E9%97%B4%E8%BF%98%E9%95%BF%23) `213.8K 🔥` `-71%`
1. [王励勤希望樊振东能代表国家征战](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B1%E5%8B%A4%E5%B8%8C%E6%9C%9B%E6%A8%8A%E6%8C%AF%E4%B8%9C%E8%83%BD%E4%BB%A3%E8%A1%A8%E5%9B%BD%E5%AE%B6%E5%BE%81%E6%88%98%23) `106.9K 🔥` `-37%`
1. [伊朗逮捕81名内鬼](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%80%AE%E6%8D%9581%E5%90%8D%E5%86%85%E9%AC%BC%23) `104.2K 🔥` `-28%`
1. [伊朗提出停火条件 (Iran proposes ceasefire conditions)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8F%90%E5%87%BA%E5%81%9C%E7%81%AB%E6%9D%A1%E4%BB%B6%23) `101.1K 🔥` `-46%`
1. [地球或将迎超级厄尔尼诺现象 (The Earth may be facing a super El Niño phenomenon)](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E7%90%83%E6%88%96%E5%B0%86%E8%BF%8E%E8%B6%85%E7%BA%A7%E5%8E%84%E5%B0%94%E5%B0%BC%E8%AF%BA%E7%8E%B0%E8%B1%A1%23) `101.0K 🔥` `-46%`
1. [对台绝不承诺放弃使用武力 (We will never commit to giving up the use of force against Taiwan)](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E5%8F%B0%E7%BB%9D%E4%B8%8D%E6%89%BF%E8%AF%BA%E6%94%BE%E5%BC%83%E4%BD%BF%E7%94%A8%E6%AD%A6%E5%8A%9B%23) `100.7K 🔥` `-60%`
1. [业内人士谈小米汽车被销售嘲讽](https://s.weibo.com/weibo?q=%23%E4%B8%9A%E5%86%85%E4%BA%BA%E5%A3%AB%E8%B0%88%E5%B0%8F%E7%B1%B3%E6%B1%BD%E8%BD%A6%E8%A2%AB%E9%94%80%E5%94%AE%E5%98%B2%E8%AE%BD%23) `100.2K 🔥` `-46%`
1. [建议不允许青少年用AI做作业 (It is recommended that teenagers not be allowed to use AI to do homework)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%8D%E5%85%81%E8%AE%B8%E9%9D%92%E5%B0%91%E5%B9%B4%E7%94%A8AI%E5%81%9A%E4%BD%9C%E4%B8%9A%23) `100.2K 🔥` `-47%`

Updated at 2026-03-11 10:45:59

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
