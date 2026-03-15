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

1. [微博315 (Weibo 315)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E5%8D%9A315%23) `557.6K 🔥` `NEW`
1. [315 没有红名单](https://s.weibo.com/weibo?q=%23315%20%E6%B2%A1%E6%9C%89%E7%BA%A2%E5%90%8D%E5%8D%95%23) `176.4K 🔥` `NEW`
1. [成都通报漂白鸡爪](https://s.weibo.com/weibo?q=%23%E6%88%90%E9%83%BD%E9%80%9A%E6%8A%A5%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%23) `174.7K 🔥` `NEW`
1. [315曝光的鸡爪公司股东也在看晚会](https://s.weibo.com/weibo?q=%23315%E6%9B%9D%E5%85%89%E7%9A%84%E9%B8%A1%E7%88%AA%E5%85%AC%E5%8F%B8%E8%82%A1%E4%B8%9C%E4%B9%9F%E5%9C%A8%E7%9C%8B%E6%99%9A%E4%BC%9A%23) `174.5K 🔥` `NEW`
1. [刘文祥这泼天的富贵你都没接住](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E8%BF%99%E6%B3%BC%E5%A4%A9%E7%9A%84%E5%AF%8C%E8%B4%B5%E4%BD%A0%E9%83%BD%E6%B2%A1%E6%8E%A5%E4%BD%8F%23) `174.1K 🔥` `NEW`
1. [中国仙侠剧凡人修仙传火爆全球](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BB%99%E4%BE%A0%E5%89%A7%E5%87%A1%E4%BA%BA%E4%BF%AE%E4%BB%99%E4%BC%A0%E7%81%AB%E7%88%86%E5%85%A8%E7%90%83%23) `141.6K 🔥` `NEW`
1. [给AI投毒已成产业链](https://s.weibo.com/weibo?q=%23%E7%BB%99AI%E6%8A%95%E6%AF%92%E5%B7%B2%E6%88%90%E4%BA%A7%E4%B8%9A%E9%93%BE%23) `114.2K 🔥` `NEW`
1. [田曦薇芭比脸金刚身](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E8%8A%AD%E6%AF%94%E8%84%B8%E9%87%91%E5%88%9A%E8%BA%AB%23) `99.6K 🔥` `NEW`
1. [315点名漂白鸡爪为比比赞供应商](https://s.weibo.com/weibo?q=%23315%E7%82%B9%E5%90%8D%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%E4%B8%BA%E6%AF%94%E6%AF%94%E8%B5%9E%E4%BE%9B%E5%BA%94%E5%95%86%23) `99.1K 🔥` `NEW`
1. [F勒布伦冠军](https://s.weibo.com/weibo?q=%23F%E5%8B%92%E5%B8%83%E4%BC%A6%E5%86%A0%E5%86%9B%23) `98.0K 🔥` `NEW`
1. [315晚会曝光AI大模型被投毒 (The 315 party revealed that a large AI model was poisoned)](https://s.weibo.com/weibo?q=%23315%E6%99%9A%E4%BC%9A%E6%9B%9D%E5%85%89AI%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%A2%AB%E6%8A%95%E6%AF%92%23) `84.4K 🔥` `NEW`
1. [曼联vs阿斯顿维拉](https://s.weibo.com/weibo?q=%23%E6%9B%BC%E8%81%94vs%E9%98%BF%E6%96%AF%E9%A1%BF%E7%BB%B4%E6%8B%89%23) `81.8K 🔥` `NEW`
1. [椰子水 兑水加糖 (Coconut water mixed with water and sugar)](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E5%AD%90%E6%B0%B4%20%E5%85%91%E6%B0%B4%E5%8A%A0%E7%B3%96%23) `1.9M 🔥` `+293%`
1. [西梅汁](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E6%A2%85%E6%B1%81%23) `649.6K 🔥` `+389%`
1. [孔雪儿邓凯 等风热吻你](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E9%82%93%E5%87%AF%20%E7%AD%89%E9%A3%8E%E7%83%AD%E5%90%BB%E4%BD%A0%23) `528.2K 🔥` `+182%`
1. [海霸王](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E9%9C%B8%E7%8E%8B%23) `175.0K 🔥` `+25%`
1. [李宇春吴青峰都哭了](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%AE%87%E6%98%A5%E5%90%B4%E9%9D%92%E5%B3%B0%E9%83%BD%E5%93%AD%E4%BA%86%23) `162.7K 🔥` `+55%`
1. [网警提醒看不见的虚假更要防](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%AD%A6%E6%8F%90%E9%86%92%E7%9C%8B%E4%B8%8D%E8%A7%81%E7%9A%84%E8%99%9A%E5%81%87%E6%9B%B4%E8%A6%81%E9%98%B2%23) `1.6M 🔥`
1. [周小闹回应刘文祥塌房 (Zhou Xiaonao responded to Liu Wenxiang’s house collapse)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%B0%8F%E9%97%B9%E5%9B%9E%E5%BA%94%E5%88%98%E6%96%87%E7%A5%A5%E5%A1%8C%E6%88%BF%23) `574.9K 🔥`
1. [医用级卫生巾](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%A8%E7%BA%A7%E5%8D%AB%E7%94%9F%E5%B7%BE%23) `452.4K 🔥`
1. [网红西梅汁实则暗藏强效泻药 (Internet celebrity prune juice actually contains a powerful laxative)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E7%BA%A2%E8%A5%BF%E6%A2%85%E6%B1%81%E5%AE%9E%E5%88%99%E6%9A%97%E8%97%8F%E5%BC%BA%E6%95%88%E6%B3%BB%E8%8D%AF%23) `155.1K 🔥`
1. [谢征什么叫我们没在一起过 (Xie Zheng, what do you mean we have never been together?)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E4%BB%80%E4%B9%88%E5%8F%AB%E6%88%91%E4%BB%AC%E6%B2%A1%E5%9C%A8%E4%B8%80%E8%B5%B7%E8%BF%87%23) `108.4K 🔥`
1. [成毅正月里真不剪头发](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%E6%AD%A3%E6%9C%88%E9%87%8C%E7%9C%9F%E4%B8%8D%E5%89%AA%E5%A4%B4%E5%8F%91%23) `92.2K 🔥`
1. [315名单 (315 list)](https://s.weibo.com/weibo?q=%23315%E5%90%8D%E5%8D%95%23) `10.1M 🔥` `-24%`
1. [有友鸡爪](https://s.weibo.com/weibo?q=%23%E6%9C%89%E5%8F%8B%E9%B8%A1%E7%88%AA%23) `743.5K 🔥` `-69%`
1. [原来电商图是这样生成的 (It turns out that this is how the e-commerce diagram is generated)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E7%94%B5%E5%95%86%E5%9B%BE%E6%98%AF%E8%BF%99%E6%A0%B7%E7%94%9F%E6%88%90%E7%9A%84%23) `177.2K 🔥` `-58%`
1. [未来5年民生保障再加力 (More efforts will be made to ensure people’s livelihood in the next five years)](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A55%E5%B9%B4%E6%B0%91%E7%94%9F%E4%BF%9D%E9%9A%9C%E5%86%8D%E5%8A%A0%E5%8A%9B%23) `177.0K 🔥` `-55%`
1. [315之夜某市监局大楼空无一人](https://s.weibo.com/weibo?q=%23315%E4%B9%8B%E5%A4%9C%E6%9F%90%E5%B8%82%E7%9B%91%E5%B1%80%E5%A4%A7%E6%A5%BC%E7%A9%BA%E6%97%A0%E4%B8%80%E4%BA%BA%23) `176.7K 🔥` `-53%`
1. [315晚会 (315 party)](https://s.weibo.com/weibo?q=%23315%E6%99%9A%E4%BC%9A%23) `176.5K 🔥` `-85%`
1. [吴佳妮自曝婚内没收入很没尊严](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%B3%E5%A6%AE%E8%87%AA%E6%9B%9D%E5%A9%9A%E5%86%85%E6%B2%A1%E6%94%B6%E5%85%A5%E5%BE%88%E6%B2%A1%E5%B0%8A%E4%B8%A5%23) `176.0K 🔥` `-52%`
1. [紫薯精天塌了 (Purple Sweet Potato Essence The sky is falling)](https://s.weibo.com/weibo?q=%23%E7%B4%AB%E8%96%AF%E7%B2%BE%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `175.7K 🔥` `-50%`
1. [院人喜人看黄子弘凡演唱会](https://s.weibo.com/weibo?q=%23%E9%99%A2%E4%BA%BA%E5%96%9C%E4%BA%BA%E7%9C%8B%E9%BB%84%E5%AD%90%E5%BC%98%E5%87%A1%E6%BC%94%E5%94%B1%E4%BC%9A%23) `175.5K 🔥` `-37%`
1. [配眼镜 暴利 (Glasses, huge profits)](https://s.weibo.com/weibo?q=%23%E9%85%8D%E7%9C%BC%E9%95%9C%20%E6%9A%B4%E5%88%A9%23) `175.4K 🔥` `-55%`
1. [乖媳妇鸡爪 (Good Wife Chicken Feet)](https://s.weibo.com/weibo?q=%23%E4%B9%96%E5%AA%B3%E5%A6%87%E9%B8%A1%E7%88%AA%23) `174.0K 🔥` `-30%`
1. [给AI投毒](https://s.weibo.com/weibo?q=%23%E7%BB%99AI%E6%8A%95%E6%AF%92%23) `173.6K 🔥` `-71%`
1. [爱吃毛肚的人天塌了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E6%AF%9B%E8%82%9A%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `168.5K 🔥` `-41%`
1. [医美骗局](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%BE%8E%E9%AA%97%E5%B1%80%23) `149.6K 🔥` `-29%`
1. [老师标配的小蜜蜂该用还是该禁 (Should the teacher’s standard bee be used or banned?)](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%B8%88%E6%A0%87%E9%85%8D%E7%9A%84%E5%B0%8F%E8%9C%9C%E8%9C%82%E8%AF%A5%E7%94%A8%E8%BF%98%E6%98%AF%E8%AF%A5%E7%A6%81%23) `145.9K 🔥` `-33%`
1. [315曝光名单梳理](https://s.weibo.com/weibo?q=%23315%E6%9B%9D%E5%85%89%E5%90%8D%E5%8D%95%E6%A2%B3%E7%90%86%23) `143.9K 🔥` `-22%`
1. [双氧水鸡爪 (Hydrogen peroxide chicken feet)](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E6%B0%A7%E6%B0%B4%E9%B8%A1%E7%88%AA%23) `136.6K 🔥` `-52%`
1. [民警抓捕逃犯时牺牲2嫌犯畏罪自杀](https://s.weibo.com/weibo?q=%23%E6%B0%91%E8%AD%A6%E6%8A%93%E6%8D%95%E9%80%83%E7%8A%AF%E6%97%B6%E7%89%BA%E7%89%B22%E5%AB%8C%E7%8A%AF%E7%95%8F%E7%BD%AA%E8%87%AA%E6%9D%80%23) `136.4K 🔥` `-26%`
1. [315记者为暗访一个月抽血十几次 (315 reporter draws blood more than ten times a month for undercover investigation)](https://s.weibo.com/weibo?q=%23315%E8%AE%B0%E8%80%85%E4%B8%BA%E6%9A%97%E8%AE%BF%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8A%BD%E8%A1%80%E5%8D%81%E5%87%A0%E6%AC%A1%23) `128.3K 🔥` `-31%`
1. [樊长玉知道谢征的身份了 (Fan Changyu knows Xie Zheng’s identity)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E7%9F%A5%E9%81%93%E8%B0%A2%E5%BE%81%E7%9A%84%E8%BA%AB%E4%BB%BD%E4%BA%86%23) `124.2K 🔥` `-30%`
1. [等风热吻你看到了网友的呼吁](https://s.weibo.com/weibo?q=%23%E7%AD%89%E9%A3%8E%E7%83%AD%E5%90%BB%E4%BD%A0%E7%9C%8B%E5%88%B0%E4%BA%86%E7%BD%91%E5%8F%8B%E7%9A%84%E5%91%BC%E5%90%81%23) `122.8K 🔥` `-31%`
1. [刘宇宁在最猛的年纪又野又欲 (Liu Yuning was wild and lustful at his most ferocious age)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%9C%A8%E6%9C%80%E7%8C%9B%E7%9A%84%E5%B9%B4%E7%BA%AA%E5%8F%88%E9%87%8E%E5%8F%88%E6%AC%B2%23) `113.1K 🔥` `-40%`
1. [胖东来要求博主删除视频 (Fat Donglai asked the blogger to delete the video)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E8%A6%81%E6%B1%82%E5%8D%9A%E4%B8%BB%E5%88%A0%E9%99%A4%E8%A7%86%E9%A2%91%23) `99.6K 🔥` `-30%`
1. [外泌体 (exosomes)](https://s.weibo.com/weibo?q=%23%E5%A4%96%E6%B3%8C%E4%BD%93%23) `92.8K 🔥` `-49%`
1. [315](https://s.weibo.com/weibo?q=%23315%23) `91.3K 🔥` `-33%`
1. [陈梦看F1晒照](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%A2%A6%E7%9C%8BF1%E6%99%92%E7%85%A7%23) `86.3K 🔥` `-33%`

Updated at 2026-03-15 23:39:23

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
