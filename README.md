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

1. [周翊然红包 (Zhou Yiran red envelope)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E7%BF%8A%E7%84%B6%E7%BA%A2%E5%8C%85%23) `8.1M 🔥` `NEW`
1. [茅台迎新年 家国共团圆](https://s.weibo.com/weibo?q=%23%E8%8C%85%E5%8F%B0%E8%BF%8E%E6%96%B0%E5%B9%B4%20%E5%AE%B6%E5%9B%BD%E5%85%B1%E5%9B%A2%E5%9C%86%23) `6.6M 🔥` `NEW`
1. [我的马年抓马之旅](https://s.weibo.com/weibo?q=%23%E6%88%91%E7%9A%84%E9%A9%AC%E5%B9%B4%E6%8A%93%E9%A9%AC%E4%B9%8B%E6%97%85%23) `4.7M 🔥` `NEW`
1. [千问红包](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E7%BA%A2%E5%8C%85%23) `232.4K 🔥` `NEW`
1. [张凌赫 七个红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E4%B8%83%E4%B8%AA%E7%BA%A2%E5%8C%85%23) `195.1K 🔥` `NEW`
1. [深圳除夕当天租男友3000元一天](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E9%99%A4%E5%A4%95%E5%BD%93%E5%A4%A9%E7%A7%9F%E7%94%B7%E5%8F%8B3000%E5%85%83%E4%B8%80%E5%A4%A9%23) `191.4K 🔥` `NEW`
1. [范丞丞红包](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E7%BA%A2%E5%8C%85%23) `186.4K 🔥` `NEW`
1. [老祖宗的强迫症也太优雅了](https://s.weibo.com/weibo?q=%23%E8%80%81%E7%A5%96%E5%AE%97%E7%9A%84%E5%BC%BA%E8%BF%AB%E7%97%87%E4%B9%9F%E5%A4%AA%E4%BC%98%E9%9B%85%E4%BA%86%23) `174.6K 🔥` `NEW`
1. [每个地方都有一道别人不理解的菜](https://s.weibo.com/weibo?q=%23%E6%AF%8F%E4%B8%AA%E5%9C%B0%E6%96%B9%E9%83%BD%E6%9C%89%E4%B8%80%E9%81%93%E5%88%AB%E4%BA%BA%E4%B8%8D%E7%90%86%E8%A7%A3%E7%9A%84%E8%8F%9C%23) `174.1K 🔥` `NEW`
1. [雷军换头像](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E6%8D%A2%E5%A4%B4%E5%83%8F%23) `150.8K 🔥` `NEW`
1. [鹿晗最新素颜照 (Lu Han’s latest photos without makeup)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E6%9C%80%E6%96%B0%E7%B4%A0%E9%A2%9C%E7%85%A7%23) `150.4K 🔥` `NEW`
1. [林孝埈孙龙刘少昂除夕出战](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E5%AD%99%E9%BE%99%E5%88%98%E5%B0%91%E6%98%82%E9%99%A4%E5%A4%95%E5%87%BA%E6%88%98%23) `146.6K 🔥` `NEW`
1. [田曦薇春晚洋娃娃](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E6%98%A5%E6%99%9A%E6%B4%8B%E5%A8%83%E5%A8%83%23) `145.5K 🔥` `NEW`
1. [爷错了 别哭了](https://s.weibo.com/weibo?q=%23%E7%88%B7%E9%94%99%E4%BA%86%20%E5%88%AB%E5%93%AD%E4%BA%86%23) `135.2K 🔥` `NEW`
1. [成龙电话摇来谢霆锋王力宏张杰](https://s.weibo.com/weibo?q=%23%E6%88%90%E9%BE%99%E7%94%B5%E8%AF%9D%E6%91%87%E6%9D%A5%E8%B0%A2%E9%9C%86%E9%94%8B%E7%8E%8B%E5%8A%9B%E5%AE%8F%E5%BC%A0%E6%9D%B0%23) `134.9K 🔥` `NEW`
1. [男子短道速滑500米预赛](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91500%E7%B1%B3%E9%A2%84%E8%B5%9B%23) `128.6K 🔥` `NEW`
1. [吴宣仪已争气争气再争气](https://s.weibo.com/weibo?q=%23%E5%90%B4%E5%AE%A3%E4%BB%AA%E5%B7%B2%E4%BA%89%E6%B0%94%E4%BA%89%E6%B0%94%E5%86%8D%E4%BA%89%E6%B0%94%23) `80.2K 🔥` `NEW`
1. [周深上门拜年送米](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B1%E4%B8%8A%E9%97%A8%E6%8B%9C%E5%B9%B4%E9%80%81%E7%B1%B3%23) `79.4K 🔥` `NEW`
1. [红包雨](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E9%9B%A8%23) `3.8M 🔥` `+1735%`
1. [春晚节目单](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `267.6K 🔥` `+31%`
1. [除夕文案 (New Year's Eve copywriting)](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%E6%96%87%E6%A1%88%23) `193.0K 🔥` `+58%`
1. [白鹿红包没门槛](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E7%BA%A2%E5%8C%85%E6%B2%A1%E9%97%A8%E6%A7%9B%23) `184.0K 🔥` `+51%`
1. [祝绪丹口令红包](https://s.weibo.com/weibo?q=%23%E7%A5%9D%E7%BB%AA%E4%B8%B9%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `183.0K 🔥` `+54%`
1. [陈星旭的红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%98%9F%E6%97%AD%E7%9A%84%E7%BA%A2%E5%8C%85%23) `164.8K 🔥` `+37%`
1. [毛晓彤红包](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%99%93%E5%BD%A4%E7%BA%A2%E5%8C%85%23) `148.6K 🔥` `+23%`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `12.6M 🔥`
1. [话百家姓过中国年](https://s.weibo.com/weibo?q=%23%E8%AF%9D%E7%99%BE%E5%AE%B6%E5%A7%93%E8%BF%87%E4%B8%AD%E5%9B%BD%E5%B9%B4%23) `3.1M 🔥`
1. [今天又要集体洗头了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E5%8F%88%E8%A6%81%E9%9B%86%E4%BD%93%E6%B4%97%E5%A4%B4%E4%BA%86%23) `245.5K 🔥`
1. [除夕 (Lunar New Year's eve)](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%23) `203.5K 🔥`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `202.0K 🔥`
1. [红包分组 (Red envelope grouping)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E5%88%86%E7%BB%84%23) `201.9K 🔥`
1. [年夜饭](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `199.6K 🔥`
1. [春晚大赏](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%A4%A7%E8%B5%8F%23) `198.4K 🔥`
1. [鞠婧祎工作室发图 (Photo posted by Ju Jingyi's studio)](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E5%B7%A5%E4%BD%9C%E5%AE%A4%E5%8F%91%E5%9B%BE%23) `196.3K 🔥`
1. [被王毅痛斥后日本急了](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%8E%8B%E6%AF%85%E7%97%9B%E6%96%A5%E5%90%8E%E6%97%A5%E6%9C%AC%E6%80%A5%E4%BA%86%23) `196.0K 🔥`
1. [等白鹿红包](https://s.weibo.com/weibo?q=%23%E7%AD%89%E7%99%BD%E9%B9%BF%E7%BA%A2%E5%8C%85%23) `193.5K 🔥`
1. [陈哲远 15万红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%2015%E4%B8%87%E7%BA%A2%E5%8C%85%23) `189.8K 🔥`
1. [Angelababy红包金额](https://s.weibo.com/weibo?q=%23Angelababy%E7%BA%A2%E5%8C%85%E9%87%91%E9%A2%9D%23) `189.5K 🔥`
1. [金饰价格涨到1544元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E6%A0%BC%E6%B6%A8%E5%88%B01544%E5%85%83%23) `187.5K 🔥`
1. [和平精英权威皮肤这一块](https://s.weibo.com/weibo?q=%23%E5%92%8C%E5%B9%B3%E7%B2%BE%E8%8B%B1%E6%9D%83%E5%A8%81%E7%9A%AE%E8%82%A4%E8%BF%99%E4%B8%80%E5%9D%97%23) `185.2K 🔥`
1. [明星红包预约](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%E9%A2%84%E7%BA%A6%23) `173.9K 🔥`
1. [朱志鑫红包](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E7%BA%A2%E5%8C%85%23) `135.8K 🔥`
1. [时代少年团马年楼晚节目单](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E9%A9%AC%E5%B9%B4%E6%A5%BC%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `131.2K 🔥`
1. [李亚鹏饮酒后83岁母亲开车接其回家 (Li Yapeng’s 83-year-old mother drove him home after drinking)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BA%9A%E9%B9%8F%E9%A5%AE%E9%85%92%E5%90%8E83%E5%B2%81%E6%AF%8D%E4%BA%B2%E5%BC%80%E8%BD%A6%E6%8E%A5%E5%85%B6%E5%9B%9E%E5%AE%B6%23) `126.7K 🔥`
1. [敖瑞鹏今晚还发红包时间不定](https://s.weibo.com/weibo?q=%23%E6%95%96%E7%91%9E%E9%B9%8F%E4%BB%8A%E6%99%9A%E8%BF%98%E5%8F%91%E7%BA%A2%E5%8C%85%E6%97%B6%E9%97%B4%E4%B8%8D%E5%AE%9A%23) `122.6K 🔥`
1. [鞠婧祎20万红包 (Ju Jingyi’s 200,000 red envelope)](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E20%E4%B8%87%E7%BA%A2%E5%8C%85%23) `5.0M 🔥` `-52%`
1. [口令红包](https://s.weibo.com/weibo?q=%23%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `291.3K 🔥` `-93%`
1. [元宝红包雨](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%9D%E7%BA%A2%E5%8C%85%E9%9B%A8%23) `178.4K 🔥` `-24%`
1. [省服 睡衣](https://s.weibo.com/weibo?q=%23%E7%9C%81%E6%9C%8D%20%E7%9D%A1%E8%A1%A3%23) `83.0K 🔥` `-48%`
1. [小伙带女友回家全家十几人列队欢迎](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%B8%A6%E5%A5%B3%E5%8F%8B%E5%9B%9E%E5%AE%B6%E5%85%A8%E5%AE%B6%E5%8D%81%E5%87%A0%E4%BA%BA%E5%88%97%E9%98%9F%E6%AC%A2%E8%BF%8E%23) `80.9K 🔥` `-54%`
1. [苏新皓红包](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E6%96%B0%E7%9A%93%E7%BA%A2%E5%8C%85%23) `80.7K 🔥` `-32%`
1. [微博抓马](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E5%8D%9A%E6%8A%93%E9%A9%AC%23) `79.7K 🔥` `-22%`

Updated at 2026-02-16 14:16:32

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
