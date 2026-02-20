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

1. [王心迪金牌 (Wang Xindi gold medal)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%BF%83%E8%BF%AA%E9%87%91%E7%89%8C%23) `9.4M 🔥` `NEW`
1. [王心迪徐梦桃 金牌夫妻](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%BF%83%E8%BF%AA%E5%BE%90%E6%A2%A6%E6%A1%83%20%E9%87%91%E7%89%8C%E5%A4%AB%E5%A6%BB%23) `3.5M 🔥` `NEW`
1. [中国非遗给你亿点点震撼](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%9D%9E%E9%81%97%E7%BB%99%E4%BD%A0%E4%BA%BF%E7%82%B9%E7%82%B9%E9%9C%87%E6%92%BC%23) `1.5M 🔥` `NEW`
1. [王心迪132.60分](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%BF%83%E8%BF%AA132.60%E5%88%86%23) `508.2K 🔥` `NEW`
1. [奖牌榜](https://s.weibo.com/weibo?q=%23%E5%A5%96%E7%89%8C%E6%A6%9C%23) `468.7K 🔥` `NEW`
1. [李天马铜牌](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%A4%A9%E9%A9%AC%E9%93%9C%E7%89%8C%23) `394.6K 🔥` `NEW`
1. [齐广璞第六](https://s.weibo.com/weibo?q=%23%E9%BD%90%E5%B9%BF%E7%92%9E%E7%AC%AC%E5%85%AD%23) `316.4K 🔥` `NEW`
1. [将门独后](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `254.7K 🔥` `NEW`
1. [目击者还原车辆坠贝加尔湖经过](https://s.weibo.com/weibo?q=%23%E7%9B%AE%E5%87%BB%E8%80%85%E8%BF%98%E5%8E%9F%E8%BD%A6%E8%BE%86%E5%9D%A0%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E7%BB%8F%E8%BF%87%23) `187.3K 🔥` `NEW`
1. [中国队米兰第4金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E7%B1%B3%E5%85%B0%E7%AC%AC4%E9%87%91%23) `160.9K 🔥` `NEW`
1. [将门独后全阵容官宣 (Official announcement of the entire lineup)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%85%A8%E9%98%B5%E5%AE%B9%E5%AE%98%E5%AE%A3%23) `138.1K 🔥` `NEW`
1. [中国队不到30小时连夺3金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E4%B8%8D%E5%88%B030%E5%B0%8F%E6%97%B6%E8%BF%9E%E5%A4%BA3%E9%87%91%23) `115.4K 🔥` `NEW`
1. [中国队提前锁定奖牌](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E6%8F%90%E5%89%8D%E9%94%81%E5%AE%9A%E5%A5%96%E7%89%8C%23) `112.9K 🔥` `NEW`
1. [最强大脑变大型分手现场](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BC%BA%E5%A4%A7%E8%84%91%E5%8F%98%E5%A4%A7%E5%9E%8B%E5%88%86%E6%89%8B%E7%8E%B0%E5%9C%BA%23) `108.8K 🔥` `NEW`
1. [杨幂无意中摔出来意外的感觉](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%97%A0%E6%84%8F%E4%B8%AD%E6%91%94%E5%87%BA%E6%9D%A5%E6%84%8F%E5%A4%96%E7%9A%84%E6%84%9F%E8%A7%89%23) `100.3K 🔥` `NEW`
1. [镖人总成本](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E6%80%BB%E6%88%90%E6%9C%AC%23) `98.0K 🔥` `NEW`
1. [商场里的书店到底是靠啥赚钱的](https://s.weibo.com/weibo?q=%23%E5%95%86%E5%9C%BA%E9%87%8C%E7%9A%84%E4%B9%A6%E5%BA%97%E5%88%B0%E5%BA%95%E6%98%AF%E9%9D%A0%E5%95%A5%E8%B5%9A%E9%92%B1%E7%9A%84%23) `96.5K 🔥` `NEW`
1. [九尾这摄影技术有感觉吗](https://s.weibo.com/weibo?q=%23%E4%B9%9D%E5%B0%BE%E8%BF%99%E6%91%84%E5%BD%B1%E6%8A%80%E6%9C%AF%E6%9C%89%E6%84%9F%E8%A7%89%E5%90%97%23) `87.5K 🔥` `NEW`
1. [冬奥会赛程](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E4%BC%9A%E8%B5%9B%E7%A8%8B%23) `87.3K 🔥` `NEW`
1. [年糕这样吃比薯片还香](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E7%B3%95%E8%BF%99%E6%A0%B7%E5%90%83%E6%AF%94%E8%96%AF%E7%89%87%E8%BF%98%E9%A6%99%23) `85.8K 🔥` `NEW`
1. [香港长江和记最新发声 (The latest statement from Cheung Kong Hutchison Hong Kong)](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E9%95%BF%E6%B1%9F%E5%92%8C%E8%AE%B0%E6%9C%80%E6%96%B0%E5%8F%91%E5%A3%B0%23) `82.2K 🔥` `NEW`
1. [妈祖女孩被换神轿抬不动请回](https://s.weibo.com/weibo?q=%23%E5%A6%88%E7%A5%96%E5%A5%B3%E5%AD%A9%E8%A2%AB%E6%8D%A2%E7%A5%9E%E8%BD%BF%E6%8A%AC%E4%B8%8D%E5%8A%A8%E8%AF%B7%E5%9B%9E%23) `1.3M 🔥` `+176%`
1. [贝加尔湖事件疑因司机强闯冰裂缝](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E4%BA%8B%E4%BB%B6%E7%96%91%E5%9B%A0%E5%8F%B8%E6%9C%BA%E5%BC%BA%E9%97%AF%E5%86%B0%E8%A3%82%E7%BC%9D%23) `392.0K 🔥` `+116%`
1. [吴京 绿卡最严厉的父亲](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E7%BB%BF%E5%8D%A1%E6%9C%80%E4%B8%A5%E5%8E%89%E7%9A%84%E7%88%B6%E4%BA%B2%23) `382.0K 🔥` `+268%`
1. [张子墨长文](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%AD%90%E5%A2%A8%E9%95%BF%E6%96%87%23) `363.2K 🔥` `+127%`
1. [女子发现网购大衣出现手写名字 (Woman discovers handwritten name on coat she purchased online)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%8F%91%E7%8E%B0%E7%BD%91%E8%B4%AD%E5%A4%A7%E8%A1%A3%E5%87%BA%E7%8E%B0%E6%89%8B%E5%86%99%E5%90%8D%E5%AD%97%23) `243.3K 🔥` `+87%`
1. [沈月 角色不要上升本人](https://s.weibo.com/weibo?q=%23%E6%B2%88%E6%9C%88%20%E8%A7%92%E8%89%B2%E4%B8%8D%E8%A6%81%E4%B8%8A%E5%8D%87%E6%9C%AC%E4%BA%BA%23) `222.0K 🔥` `+56%`
1. [陈奕迅女儿被曝新恋情](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A5%95%E8%BF%85%E5%A5%B3%E5%84%BF%E8%A2%AB%E6%9B%9D%E6%96%B0%E6%81%8B%E6%83%85%23) `184.5K 🔥` `+48%`
1. [庄家终于有自己的宋莹了](https://s.weibo.com/weibo?q=%23%E5%BA%84%E5%AE%B6%E7%BB%88%E4%BA%8E%E6%9C%89%E8%87%AA%E5%B7%B1%E7%9A%84%E5%AE%8B%E8%8E%B9%E4%BA%86%23) `172.1K 🔥` `+46%`
1. [谷爱凌赌上职业生涯的一跳](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%B5%8C%E4%B8%8A%E8%81%8C%E4%B8%9A%E7%94%9F%E6%B6%AF%E7%9A%84%E4%B8%80%E8%B7%B3%23) `100.6K 🔥` `+32%`
1. [自由式滑雪男子空中技巧决赛 (Freestyle Skiing Men's Aerials Final)](https://s.weibo.com/weibo?q=%23%E8%87%AA%E7%94%B1%E5%BC%8F%E6%BB%91%E9%9B%AA%E7%94%B7%E5%AD%90%E7%A9%BA%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%86%B3%E8%B5%9B%23) `768.6K 🔥`
1. [将门毒后不是大ip是巨ip](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%E4%B8%8D%E6%98%AF%E5%A4%A7ip%E6%98%AF%E5%B7%A8ip%23) `532.3K 🔥`
1. [杨幂带火吊带条纹长裙 (Yang Mi's striped long skirt with fire straps)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E5%B8%A6%E7%81%AB%E5%90%8A%E5%B8%A6%E6%9D%A1%E7%BA%B9%E9%95%BF%E8%A3%99%23) `115.1K 🔥`
1. [李佩仪萧怀瑾分手](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BD%A9%E4%BB%AA%E8%90%A7%E6%80%80%E7%91%BE%E5%88%86%E6%89%8B%23) `114.6K 🔥`
1. [酒店咖啡机洗内裤](https://s.weibo.com/weibo?q=%23%E9%85%92%E5%BA%97%E5%92%96%E5%95%A1%E6%9C%BA%E6%B4%97%E5%86%85%E8%A3%A4%23) `112.9K 🔥`
1. [吴京争取拍镖人第二部](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%E4%BA%89%E5%8F%96%E6%8B%8D%E9%95%96%E4%BA%BA%E7%AC%AC%E4%BA%8C%E9%83%A8%23) `111.4K 🔥`
1. [吴佳尼自曝离婚原因 (Wu Jiani reveals the reason for divorce)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%B3%E5%B0%BC%E8%87%AA%E6%9B%9D%E7%A6%BB%E5%A9%9A%E5%8E%9F%E5%9B%A0%23) `105.5K 🔥`
1. [最强大脑](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BC%BA%E5%A4%A7%E8%84%91%23) `103.0K 🔥`
1. [易烊千玺是有点演技症在身上](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E6%98%AF%E6%9C%89%E7%82%B9%E6%BC%94%E6%8A%80%E7%97%87%E5%9C%A8%E8%BA%AB%E4%B8%8A%23) `94.7K 🔥`
1. [TF四代五练结束了 (TF fourth generation and fifth training is over)](https://s.weibo.com/weibo?q=%23TF%E5%9B%9B%E4%BB%A3%E4%BA%94%E7%BB%83%E7%BB%93%E6%9D%9F%E4%BA%86%23) `84.0K 🔥`
1. [齐广璞决赛第一跳121.68分 (Qi Guangpu’s first jump in the final was 121.68 points)](https://s.weibo.com/weibo?q=%23%E9%BD%90%E5%B9%BF%E7%92%9E%E5%86%B3%E8%B5%9B%E7%AC%AC%E4%B8%80%E8%B7%B3121.68%E5%88%86%23) `82.9K 🔥`
1. [将门独后 天崩开局 (The only queen in the sect will start with Heavenly Collapse)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%20%E5%A4%A9%E5%B4%A9%E5%BC%80%E5%B1%80%23) `714.9K 🔥` `-38%`
1. [短剧上星 不匹配电视](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E4%B8%8A%E6%98%9F%20%E4%B8%8D%E5%8C%B9%E9%85%8D%E7%94%B5%E8%A7%86%23) `257.2K 🔥` `-26%`
1. [火锅店春节4天赚33.9万全给员工](https://s.weibo.com/weibo?q=%23%E7%81%AB%E9%94%85%E5%BA%97%E6%98%A5%E8%8A%824%E5%A4%A9%E8%B5%9A33.9%E4%B8%87%E5%85%A8%E7%BB%99%E5%91%98%E5%B7%A5%23) `191.3K 🔥` `-57%`
1. [全世界为什么只有中国人吃炒菜](https://s.weibo.com/weibo?q=%23%E5%85%A8%E4%B8%96%E7%95%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%AA%E6%9C%89%E4%B8%AD%E5%9B%BD%E4%BA%BA%E5%90%83%E7%82%92%E8%8F%9C%23) `180.9K 🔥` `-28%`
1. [为什么美人计使用率如此之高](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E7%BE%8E%E4%BA%BA%E8%AE%A1%E4%BD%BF%E7%94%A8%E7%8E%87%E5%A6%82%E6%AD%A4%E4%B9%8B%E9%AB%98%23) `157.0K 🔥` `-37%`
1. [广东地震 (Guangdong earthquake)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E5%9C%B0%E9%9C%87%23) `107.1K 🔥` `-45%`
1. [镖人票房排名第二 (The Bodyguard ranks second at the box office)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E6%8E%92%E5%90%8D%E7%AC%AC%E4%BA%8C%23) `100.6K 🔥` `-24%`
1. [情绪稳定的一家人有多重要](https://s.weibo.com/weibo?q=%23%E6%83%85%E7%BB%AA%E7%A8%B3%E5%AE%9A%E7%9A%84%E4%B8%80%E5%AE%B6%E4%BA%BA%E6%9C%89%E5%A4%9A%E9%87%8D%E8%A6%81%23) `93.7K 🔥` `-28%`
1. [宋威龙你顶着这张脸四肢爬行啊](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%A8%81%E9%BE%99%E4%BD%A0%E9%A1%B6%E7%9D%80%E8%BF%99%E5%BC%A0%E8%84%B8%E5%9B%9B%E8%82%A2%E7%88%AC%E8%A1%8C%E5%95%8A%23) `84.0K 🔥` `-21%`

Updated at 2026-02-20 22:26:16

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
