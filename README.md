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

1. [建议整治同一航班同一张票两个价 (It is recommended to correct the two prices for the same ticket on the same flight.)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%95%B4%E6%B2%BB%E5%90%8C%E4%B8%80%E8%88%AA%E7%8F%AD%E5%90%8C%E4%B8%80%E5%BC%A0%E7%A5%A8%E4%B8%A4%E4%B8%AA%E4%BB%B7%23) `332.2K 🔥` `NEW`
1. [白玉兰预测](https://s.weibo.com/weibo?q=%23%E7%99%BD%E7%8E%89%E5%85%B0%E9%A2%84%E6%B5%8B%23) `328.8K 🔥` `NEW`
1. [外甥正月偷偷剪发舅舅气到血压飙升](https://s.weibo.com/weibo?q=%23%E5%A4%96%E7%94%A5%E6%AD%A3%E6%9C%88%E5%81%B7%E5%81%B7%E5%89%AA%E5%8F%91%E8%88%85%E8%88%85%E6%B0%94%E5%88%B0%E8%A1%80%E5%8E%8B%E9%A3%99%E5%8D%87%23) `319.7K 🔥` `NEW`
1. [张凌赫回应颜值出圈](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%9B%9E%E5%BA%94%E9%A2%9C%E5%80%BC%E5%87%BA%E5%9C%88%23) `315.1K 🔥` `NEW`
1. [不带大梁能穿越N39吗](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%B8%A6%E5%A4%A7%E6%A2%81%E8%83%BD%E7%A9%BF%E8%B6%8AN39%E5%90%97%23) `231.6K 🔥` `NEW`
1. [无痛上班模式](https://s.weibo.com/weibo?q=%23%E6%97%A0%E7%97%9B%E4%B8%8A%E7%8F%AD%E6%A8%A1%E5%BC%8F%23) `170.6K 🔥` `NEW`
1. [大学生嘴上说不想开学](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F%E5%98%B4%E4%B8%8A%E8%AF%B4%E4%B8%8D%E6%83%B3%E5%BC%80%E5%AD%A6%23) `145.5K 🔥` `NEW`
1. [刘浩存 还有我的老鼠干](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%20%E8%BF%98%E6%9C%89%E6%88%91%E7%9A%84%E8%80%81%E9%BC%A0%E5%B9%B2%23) `144.7K 🔥` `NEW`
1. [TF后代大战EXO老祖](https://s.weibo.com/weibo?q=%23TF%E5%90%8E%E4%BB%A3%E5%A4%A7%E6%88%98EXO%E8%80%81%E7%A5%96%23) `137.9K 🔥` `NEW`
1. [逐玉 三对CP](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E4%B8%89%E5%AF%B9CP%23) `123.1K 🔥` `NEW`
1. [iPhone18Pro或无屏下FaceID (iPhone 18 Pro or no under-screen FaceID)](https://s.weibo.com/weibo?q=%23iPhone18Pro%E6%88%96%E6%97%A0%E5%B1%8F%E4%B8%8BFaceID%23) `118.6K 🔥` `NEW`
1. [神秘买家超7亿买入4套豪宅](https://s.weibo.com/weibo?q=%23%E7%A5%9E%E7%A7%98%E4%B9%B0%E5%AE%B6%E8%B6%857%E4%BA%BF%E4%B9%B0%E5%85%A54%E5%A5%97%E8%B1%AA%E5%AE%85%23) `112.8K 🔥` `NEW`
1. [建议上夜班前打坐3到5分钟](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%8A%E5%A4%9C%E7%8F%AD%E5%89%8D%E6%89%93%E5%9D%903%E5%88%B05%E5%88%86%E9%92%9F%23) `108.8K 🔥` `NEW`
1. [金店集体涨价](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%BA%97%E9%9B%86%E4%BD%93%E6%B6%A8%E4%BB%B7%23) `97.9K 🔥` `NEW`
1. [刘文祥过完零丁洋得坨](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E8%BF%87%E5%AE%8C%E9%9B%B6%E4%B8%81%E6%B4%8B%E5%BE%97%E5%9D%A8%23) `95.8K 🔥` `NEW`
1. [恋与深空委托 1300一小时](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%E5%A7%94%E6%89%98%201300%E4%B8%80%E5%B0%8F%E6%97%B6%23) `91.7K 🔥` `NEW`
1. [豆包万能P图口令](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E4%B8%87%E8%83%BDP%E5%9B%BE%E5%8F%A3%E4%BB%A4%23) `90.9K 🔥` `NEW`
1. [律师解读平台限制AI成毅](https://s.weibo.com/weibo?q=%23%E5%BE%8B%E5%B8%88%E8%A7%A3%E8%AF%BB%E5%B9%B3%E5%8F%B0%E9%99%90%E5%88%B6AI%E6%88%90%E6%AF%85%23) `85.2K 🔥` `NEW`
1. [DYG 自求多福](https://s.weibo.com/weibo?q=%23DYG%20%E8%87%AA%E6%B1%82%E5%A4%9A%E7%A6%8F%23) `84.0K 🔥` `NEW`
1. [早熟的人通常都晚熟](https://s.weibo.com/weibo?q=%23%E6%97%A9%E7%86%9F%E7%9A%84%E4%BA%BA%E9%80%9A%E5%B8%B8%E9%83%BD%E6%99%9A%E7%86%9F%23) `78.2K 🔥` `NEW`
1. [建议设大龄人才友好岗 (It is recommended to set up posts friendly to older talents)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E8%AE%BE%E5%A4%A7%E9%BE%84%E4%BA%BA%E6%89%8D%E5%8F%8B%E5%A5%BD%E5%B2%97%23) `77.8K 🔥` `NEW`
1. [当你生了一个双鱼座小孩](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BD%A0%E7%94%9F%E4%BA%86%E4%B8%80%E4%B8%AA%E5%8F%8C%E9%B1%BC%E5%BA%A7%E5%B0%8F%E5%AD%A9%23) `76.5K 🔥` `NEW`
1. [伊朗总统之子称最高领袖平安](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E4%B9%8B%E5%AD%90%E7%A7%B0%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E5%B9%B3%E5%AE%89%23) `70.8K 🔥` `NEW`
1. [薛之谦广州场二开](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E5%B9%BF%E5%B7%9E%E5%9C%BA%E4%BA%8C%E5%BC%80%23) `69.4K 🔥` `NEW`
1. [TVB风味古偶白日提灯](https://s.weibo.com/weibo?q=%23TVB%E9%A3%8E%E5%91%B3%E5%8F%A4%E5%81%B6%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `69.3K 🔥` `NEW`
1. [建议允许未休年假两年内结转使用](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%85%81%E8%AE%B8%E6%9C%AA%E4%BC%91%E5%B9%B4%E5%81%87%E4%B8%A4%E5%B9%B4%E5%86%85%E7%BB%93%E8%BD%AC%E4%BD%BF%E7%94%A8%23) `1.1M 🔥` `+1019%`
1. [AG 首发](https://s.weibo.com/weibo?q=%23AG%20%E9%A6%96%E5%8F%91%23) `335.0K 🔥` `+349%`
1. [逐玉孔雪儿邓凯这一对简直仙品](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%AD%94%E9%9B%AA%E5%84%BF%E9%82%93%E5%87%AF%E8%BF%99%E4%B8%80%E5%AF%B9%E7%AE%80%E7%9B%B4%E4%BB%99%E5%93%81%23) `198.9K 🔥` `+44%`
1. [虞书欣一滴泪原始帧](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%B8%80%E6%BB%B4%E6%B3%AA%E5%8E%9F%E5%A7%8B%E5%B8%A7%23) `84.3K 🔥` `+21%`
1. [政协会议圆满完成各项议程](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%8D%8F%E4%BC%9A%E8%AE%AE%E5%9C%86%E6%BB%A1%E5%AE%8C%E6%88%90%E5%90%84%E9%A1%B9%E8%AE%AE%E7%A8%8B%23) `627.6K 🔥`
1. [华莱士正式宣布退市 (Wallace officially announced its delisting)](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E8%8E%B1%E5%A3%AB%E6%AD%A3%E5%BC%8F%E5%AE%A3%E5%B8%83%E9%80%80%E5%B8%82%23) `509.2K 🔥`
1. [伊朗下起毒雨](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8B%E8%B5%B7%E6%AF%92%E9%9B%A8%23) `333.3K 🔥`
1. [十五五蓝图中的职业新图景 (New career prospects in the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%93%9D%E5%9B%BE%E4%B8%AD%E7%9A%84%E8%81%8C%E4%B8%9A%E6%96%B0%E5%9B%BE%E6%99%AF%23) `325.3K 🔥`
1. [建议新增元宵节假日](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%96%B0%E5%A2%9E%E5%85%83%E5%AE%B5%E8%8A%82%E5%81%87%E6%97%A5%23) `322.9K 🔥`
1. [逐玉 赋魅](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E8%B5%8B%E9%AD%85%23) `316.3K 🔥`
1. [女子将老公送金镯扔地上又响又跳](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%B0%86%E8%80%81%E5%85%AC%E9%80%81%E9%87%91%E9%95%AF%E6%89%94%E5%9C%B0%E4%B8%8A%E5%8F%88%E5%93%8D%E5%8F%88%E8%B7%B3%23) `315.5K 🔥`
1. [向佐差点踢到主持人的头](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%90%E5%B7%AE%E7%82%B9%E8%B8%A2%E5%88%B0%E4%B8%BB%E6%8C%81%E4%BA%BA%E7%9A%84%E5%A4%B4%23) `226.0K 🔥`
1. [驻韩美军6部萨德发射车全部运出](https://s.weibo.com/weibo?q=%23%E9%A9%BB%E9%9F%A9%E7%BE%8E%E5%86%9B6%E9%83%A8%E8%90%A8%E5%BE%B7%E5%8F%91%E5%B0%84%E8%BD%A6%E5%85%A8%E9%83%A8%E8%BF%90%E5%87%BA%23) `146.5K 🔥`
1. [要对钱有概念](https://s.weibo.com/weibo?q=%23%E8%A6%81%E5%AF%B9%E9%92%B1%E6%9C%89%E6%A6%82%E5%BF%B5%23) `130.0K 🔥`
1. [工作不满10年休5天年假规则该调整](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%BD%9C%E4%B8%8D%E6%BB%A110%E5%B9%B4%E4%BC%915%E5%A4%A9%E5%B9%B4%E5%81%87%E8%A7%84%E5%88%99%E8%AF%A5%E8%B0%83%E6%95%B4%23) `783.0K 🔥` `-25%`
1. [国际油价历史性暴跌](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%99%85%E6%B2%B9%E4%BB%B7%E5%8E%86%E5%8F%B2%E6%80%A7%E6%9A%B4%E8%B7%8C%23) `255.7K 🔥` `-35%`
1. [王楚钦vs格罗特 (Wang Chuqin vs Grote)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E6%A0%BC%E7%BD%97%E7%89%B9%23) `121.6K 🔥` `-84%`
1. [桃花坞 (Taohuawu)](https://s.weibo.com/weibo?q=%23%E6%A1%83%E8%8A%B1%E5%9D%9E%23) `105.8K 🔥` `-77%`
1. [以为是段子结果真发生了](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%98%AF%E6%AE%B5%E5%AD%90%E7%BB%93%E6%9E%9C%E7%9C%9F%E5%8F%91%E7%94%9F%E4%BA%86%23) `105.0K 🔥` `-25%`
1. [王小亿内场这个美](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%B0%8F%E4%BA%BF%E5%86%85%E5%9C%BA%E8%BF%99%E4%B8%AA%E7%BE%8E%23) `90.4K 🔥` `-44%`
1. [伊朗称正在霍尔木兹海峡等待美海军](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%AD%A3%E5%9C%A8%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E7%AD%89%E5%BE%85%E7%BE%8E%E6%B5%B7%E5%86%9B%23) `76.2K 🔥` `-37%`
1. [两会](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `70.9K 🔥` `-84%`
1. [帅的追你一秒就同意了](https://s.weibo.com/weibo?q=%23%E5%B8%85%E7%9A%84%E8%BF%BD%E4%BD%A0%E4%B8%80%E7%A7%92%E5%B0%B1%E5%90%8C%E6%84%8F%E4%BA%86%23) `69.9K 🔥` `-36%`
1. [美国驻多伦多领馆遭枪击 (U.S. consulate in Toronto attacked)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E9%A9%BB%E5%A4%9A%E4%BC%A6%E5%A4%9A%E9%A2%86%E9%A6%86%E9%81%AD%E6%9E%AA%E5%87%BB%23) `67.1K 🔥` `-84%`

Updated at 2026-03-11 15:28:03

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
