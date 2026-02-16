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

1. [这张全村福看得人心暖暖 (This portrait of the entire village warms the heart)](https://s.weibo.com/weibo?q=%23%E8%BF%99%E5%BC%A0%E5%85%A8%E6%9D%91%E7%A6%8F%E7%9C%8B%E5%BE%97%E4%BA%BA%E5%BF%83%E6%9A%96%E6%9A%96%23) `3.2M 🔥` `NEW`
1. [大年初一不洗头不煮饭](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E6%B4%97%E5%A4%B4%E4%B8%8D%E7%85%AE%E9%A5%AD%23) `1.4M 🔥` `NEW`
1. [陈都灵红包单包的金额设置好高](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%83%BD%E7%81%B5%E7%BA%A2%E5%8C%85%E5%8D%95%E5%8C%85%E7%9A%84%E9%87%91%E9%A2%9D%E8%AE%BE%E7%BD%AE%E5%A5%BD%E9%AB%98%23) `1.4M 🔥` `NEW`
1. [迪丽热巴人鱼公主](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%BA%BA%E9%B1%BC%E5%85%AC%E4%B8%BB%23) `890.4K 🔥` `NEW`
1. [宇宙级新春祝福上新了](https://s.weibo.com/weibo?q=%23%E5%AE%87%E5%AE%99%E7%BA%A7%E6%96%B0%E6%98%A5%E7%A5%9D%E7%A6%8F%E4%B8%8A%E6%96%B0%E4%BA%86%23) `651.3K 🔥` `NEW`
1. [泰国机场凌晨堵满中国人](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E6%9C%BA%E5%9C%BA%E5%87%8C%E6%99%A8%E5%A0%B5%E6%BB%A1%E4%B8%AD%E5%9B%BD%E4%BA%BA%23) `594.7K 🔥` `NEW`
1. [沈腾马丽没小品](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E9%A9%AC%E4%B8%BD%E6%B2%A1%E5%B0%8F%E5%93%81%23) `589.1K 🔥` `NEW`
1. [王楚然空降](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E7%A9%BA%E9%99%8D%23) `461.4K 🔥` `NEW`
1. [蹲王星越红包](https://s.weibo.com/weibo?q=%23%E8%B9%B2%E7%8E%8B%E6%98%9F%E8%B6%8A%E7%BA%A2%E5%8C%85%23) `418.5K 🔥` `NEW`
1. [谭松韵 年画娃娃](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%20%E5%B9%B4%E7%94%BB%E5%A8%83%E5%A8%83%23) `398.2K 🔥` `NEW`
1. [终于有人把抢红包算法讲明白了 (Finally someone explained the red envelope grabbing algorithm clearly)](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%8A%8A%E6%8A%A2%E7%BA%A2%E5%8C%85%E7%AE%97%E6%B3%95%E8%AE%B2%E6%98%8E%E7%99%BD%E4%BA%86%23) `397.0K 🔥` `NEW`
1. [微博 全世界最有年味的地方](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E5%8D%9A%20%E5%85%A8%E4%B8%96%E7%95%8C%E6%9C%80%E6%9C%89%E5%B9%B4%E5%91%B3%E7%9A%84%E5%9C%B0%E6%96%B9%23) `393.8K 🔥` `NEW`
1. [小偷打开门都以为自己穿越了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%81%B7%E6%89%93%E5%BC%80%E9%97%A8%E9%83%BD%E4%BB%A5%E4%B8%BA%E8%87%AA%E5%B7%B1%E7%A9%BF%E8%B6%8A%E4%BA%86%23) `367.3K 🔥` `NEW`
1. [李沁 没抢到但这张图好美](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%B2%81%20%E6%B2%A1%E6%8A%A2%E5%88%B0%E4%BD%86%E8%BF%99%E5%BC%A0%E5%9B%BE%E5%A5%BD%E7%BE%8E%23) `356.4K 🔥` `NEW`
1. [周翊然小号](https://s.weibo.com/weibo?q=%23%E5%91%A8%E7%BF%8A%E7%84%B6%E5%B0%8F%E5%8F%B7%23) `307.4K 🔥` `NEW`
1. [王橹杰高会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E9%AB%98%E4%BC%9A%23) `242.3K 🔥` `NEW`
1. [无法融入猴群小猴一直抱着玩偶](https://s.weibo.com/weibo?q=%23%E6%97%A0%E6%B3%95%E8%9E%8D%E5%85%A5%E7%8C%B4%E7%BE%A4%E5%B0%8F%E7%8C%B4%E4%B8%80%E7%9B%B4%E6%8A%B1%E7%9D%80%E7%8E%A9%E5%81%B6%23) `239.6K 🔥` `NEW`
1. [孟子义红包](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E7%BA%A2%E5%8C%85%23) `239.0K 🔥` `NEW`
1. [除夕福到团圆到](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%E7%A6%8F%E5%88%B0%E5%9B%A2%E5%9C%86%E5%88%B0%23) `210.0K 🔥` `NEW`
1. [春晚没人愿意和邓超搭档了吗](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%B2%A1%E4%BA%BA%E6%84%BF%E6%84%8F%E5%92%8C%E9%82%93%E8%B6%85%E6%90%AD%E6%A1%A3%E4%BA%86%E5%90%97%23) `201.7K 🔥` `NEW`
1. [短道速滑男子5000米接力 (Short track speed skating men's 5000m relay)](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E7%94%B7%E5%AD%905000%E7%B1%B3%E6%8E%A5%E5%8A%9B%23) `201.5K 🔥` `NEW`
1. [年夜饭](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `3.9M 🔥` `+131%`
1. [用千问给年夜饭加道菜 (Use Qianwen to add another dish to the New Year’s Eve dinner)](https://s.weibo.com/weibo?q=%23%E7%94%A8%E5%8D%83%E9%97%AE%E7%BB%99%E5%B9%B4%E5%A4%9C%E9%A5%AD%E5%8A%A0%E9%81%93%E8%8F%9C%23) `1.8M 🔥` `+732%`
1. [你的骑手正在和外卖箱打架](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E7%9A%84%E9%AA%91%E6%89%8B%E6%AD%A3%E5%9C%A8%E5%92%8C%E5%A4%96%E5%8D%96%E7%AE%B1%E6%89%93%E6%9E%B6%23) `1.4M 🔥` `+713%`
1. [除夕 (Lunar New Year's eve)](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%23) `1.4M 🔥` `+876%`
1. [李一桐定时红包](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%B8%80%E6%A1%90%E5%AE%9A%E6%97%B6%E7%BA%A2%E5%8C%85%23) `1.2M 🔥` `+797%`
1. [口令红包](https://s.weibo.com/weibo?q=%23%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `1.1M 🔥` `+406%`
1. [春晚大赏](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%A4%A7%E8%B5%8F%23) `1.0M 🔥` `+480%`
1. [敖瑞鹏发红包还有前菜 (Ao Ruipeng gave out red envelopes and appetizers)](https://s.weibo.com/weibo?q=%23%E6%95%96%E7%91%9E%E9%B9%8F%E5%8F%91%E7%BA%A2%E5%8C%85%E8%BF%98%E6%9C%89%E5%89%8D%E8%8F%9C%23) `992.8K 🔥` `+648%`
1. [麻将鸡蛋](https://s.weibo.com/weibo?q=%23%E9%BA%BB%E5%B0%86%E9%B8%A1%E8%9B%8B%23) `916.0K 🔥` `+770%`
1. [梁洁红包 (Liang Jie red envelope)](https://s.weibo.com/weibo?q=%23%E6%A2%81%E6%B4%81%E7%BA%A2%E5%8C%85%23) `765.1K 🔥` `+533%`
1. [孙颖莎红包 (Sun Yingsha red envelope)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E7%BA%A2%E5%8C%85%23) `422.9K 🔥` `+106%`
1. [否认南京大屠杀的日本酒店老板死了](https://s.weibo.com/weibo?q=%23%E5%90%A6%E8%AE%A4%E5%8D%97%E4%BA%AC%E5%A4%A7%E5%B1%A0%E6%9D%80%E7%9A%84%E6%97%A5%E6%9C%AC%E9%85%92%E5%BA%97%E8%80%81%E6%9D%BF%E6%AD%BB%E4%BA%86%23) `397.0K 🔥` `+197%`
1. [小孩哥教爷爷抢千问红包](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A9%E5%93%A5%E6%95%99%E7%88%B7%E7%88%B7%E6%8A%A2%E5%8D%83%E9%97%AE%E7%BA%A2%E5%8C%85%23) `397.0K 🔥` `+270%`
1. [孟子义 先发美图再发红包](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%20%E5%85%88%E5%8F%91%E7%BE%8E%E5%9B%BE%E5%86%8D%E5%8F%91%E7%BA%A2%E5%8C%85%23) `397.0K 🔥` `+186%`
1. [年夜饭变身大型千问拉新现场 (New Year’s Eve dinner turns into a large-scale new event)](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%E5%8F%98%E8%BA%AB%E5%A4%A7%E5%9E%8B%E5%8D%83%E9%97%AE%E6%8B%89%E6%96%B0%E7%8E%B0%E5%9C%BA%23) `394.9K 🔥` `+251%`
1. [红包雨](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E9%9B%A8%23) `394.1K 🔥` `+218%`
1. [陈哲远 15万红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%2015%E4%B8%87%E7%BA%A2%E5%8C%85%23) `393.8K 🔥` `+188%`
1. [张凌赫 七个红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E4%B8%83%E4%B8%AA%E7%BA%A2%E5%8C%85%23) `390.9K 🔥` `+190%`
1. [曾舜晞红包](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E7%BA%A2%E5%8C%85%23) `308.6K 🔥` `+95%`
1. [今天又要集体洗头了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E5%8F%88%E8%A6%81%E9%9B%86%E4%BD%93%E6%B4%97%E5%A4%B4%E4%BA%86%23) `307.7K 🔥` `+167%`
1. [春晚3个小品](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A3%E4%B8%AA%E5%B0%8F%E5%93%81%23) `284.0K 🔥` `+74%`
1. [一阳双排](https://s.weibo.com/weibo?q=%23%E4%B8%80%E9%98%B3%E5%8F%8C%E6%8E%92%23) `248.6K 🔥` `+91%`
1. [被王毅痛斥后日本急了 (Japan is anxious after being reprimanded by Wang Yi)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%8E%8B%E6%AF%85%E7%97%9B%E6%96%A5%E5%90%8E%E6%97%A5%E6%9C%AC%E6%80%A5%E4%BA%86%23) `245.0K 🔥` `+161%`
1. [周翊然红包 (Zhou Yiran red envelope)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E7%BF%8A%E7%84%B6%E7%BA%A2%E5%8C%85%23) `241.6K 🔥` `+102%`
1. [春晚没有相声](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%B2%A1%E6%9C%89%E7%9B%B8%E5%A3%B0%23) `227.2K 🔥` `+78%`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `14.4M 🔥`
1. [春晚节目单 (Spring Festival Gala Program)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `5.5M 🔥`
1. [千问红包 (Qianwen red envelope)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E7%BA%A2%E5%8C%85%23) `2.3M 🔥`
1. [红包分组 (Red envelope grouping)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E5%88%86%E7%BB%84%23) `1.9M 🔥`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `1.5M 🔥`
1. [茅台迎新年 家国共团圆](https://s.weibo.com/weibo?q=%23%E8%8C%85%E5%8F%B0%E8%BF%8E%E6%96%B0%E5%B9%B4%20%E5%AE%B6%E5%9B%BD%E5%85%B1%E5%9B%A2%E5%9C%86%23) `4.8M 🔥` `-26%`

Updated at 2026-02-16 17:05:38

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
