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

1. [21岁女生头晕以为没睡好查出脑梗 (A 21-year-old girl felt dizzy and thought she hadn’t slept well and was diagnosed with cerebral infarction)](https://s.weibo.com/weibo?q=%2321%E5%B2%81%E5%A5%B3%E7%94%9F%E5%A4%B4%E6%99%95%E4%BB%A5%E4%B8%BA%E6%B2%A1%E7%9D%A1%E5%A5%BD%E6%9F%A5%E5%87%BA%E8%84%91%E6%A2%97%23) `918.0K 🔥` `NEW`
1. [提醒在伊朗的中国公民尽快撤离](https://s.weibo.com/weibo?q=%23%E6%8F%90%E9%86%92%E5%9C%A8%E4%BC%8A%E6%9C%97%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E5%B0%BD%E5%BF%AB%E6%92%A4%E7%A6%BB%23) `665.8K 🔥` `NEW`
1. [关注2026全国两会](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%B3%A82026%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%23) `506.9K 🔥` `NEW`
1. [反诈老陈因多次违规被罚](https://s.weibo.com/weibo?q=%23%E5%8F%8D%E8%AF%88%E8%80%81%E9%99%88%E5%9B%A0%E5%A4%9A%E6%AC%A1%E8%BF%9D%E8%A7%84%E8%A2%AB%E7%BD%9A%23) `371.1K 🔥` `NEW`
1. [虎跳峡男游客疑因洗杯落水失联](https://s.weibo.com/weibo?q=%23%E8%99%8E%E8%B7%B3%E5%B3%A1%E7%94%B7%E6%B8%B8%E5%AE%A2%E7%96%91%E5%9B%A0%E6%B4%97%E6%9D%AF%E8%90%BD%E6%B0%B4%E5%A4%B1%E8%81%94%23) `190.6K 🔥` `NEW`
1. [当妈妈把欧洲特产蒸了后](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%A6%88%E5%A6%88%E6%8A%8A%E6%AC%A7%E6%B4%B2%E7%89%B9%E4%BA%A7%E8%92%B8%E4%BA%86%E5%90%8E%23) `189.3K 🔥` `NEW`
1. [徐福记回应米兰小伙求代购酥心糖](https://s.weibo.com/weibo?q=%23%E5%BE%90%E7%A6%8F%E8%AE%B0%E5%9B%9E%E5%BA%94%E7%B1%B3%E5%85%B0%E5%B0%8F%E4%BC%99%E6%B1%82%E4%BB%A3%E8%B4%AD%E9%85%A5%E5%BF%83%E7%B3%96%23) `167.5K 🔥` `NEW`
1. [美国双航母已就位](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%8F%8C%E8%88%AA%E6%AF%8D%E5%B7%B2%E5%B0%B1%E4%BD%8D%23) `167.3K 🔥` `NEW`
1. [伊军方将对美侵略予以毁灭性回应](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E5%86%9B%E6%96%B9%E5%B0%86%E5%AF%B9%E7%BE%8E%E4%BE%B5%E7%95%A5%E4%BA%88%E4%BB%A5%E6%AF%81%E7%81%AD%E6%80%A7%E5%9B%9E%E5%BA%94%23) `156.2K 🔥` `NEW`
1. [Gucci直播](https://s.weibo.com/weibo?q=%23Gucci%E7%9B%B4%E6%92%AD%23) `156.0K 🔥` `NEW`
1. [美国 伊朗 (United States Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%20%E4%BC%8A%E6%9C%97%23) `155.4K 🔥` `NEW`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `155.2K 🔥` `NEW`
1. [杨幂谷爱凌合照 好娇啊小幂](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%B0%B7%E7%88%B1%E5%87%8C%E5%90%88%E7%85%A7%20%E5%A5%BD%E5%A8%87%E5%95%8A%E5%B0%8F%E5%B9%82%23) `155.0K 🔥` `NEW`
1. [奥黛丽厚本正完骨变薄本了](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E9%BB%9B%E4%B8%BD%E5%8E%9A%E6%9C%AC%E6%AD%A3%E5%AE%8C%E9%AA%A8%E5%8F%98%E8%96%84%E6%9C%AC%E4%BA%86%23) `154.3K 🔥` `NEW`
1. [高市早苗反对女天皇](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%8F%8D%E5%AF%B9%E5%A5%B3%E5%A4%A9%E7%9A%87%23) `153.9K 🔥` `NEW`
1. [刘雯好性感](https://s.weibo.com/weibo?q=%23%E5%88%98%E9%9B%AF%E5%A5%BD%E6%80%A7%E6%84%9F%23) `153.6K 🔥` `NEW`
1. [杨洋发文回应不让江山争议](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E4%BA%89%E8%AE%AE%23) `153.3K 🔥` `NEW`
1. [政府借厕所遭辱骂男子要求公开道歉](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%BA%9C%E5%80%9F%E5%8E%95%E6%89%80%E9%81%AD%E8%BE%B1%E9%AA%82%E7%94%B7%E5%AD%90%E8%A6%81%E6%B1%82%E5%85%AC%E5%BC%80%E9%81%93%E6%AD%89%23) `153.1K 🔥` `NEW`
1. [曝敖瑞鹏合约到期不续](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%95%96%E7%91%9E%E9%B9%8F%E5%90%88%E7%BA%A6%E5%88%B0%E6%9C%9F%E4%B8%8D%E7%BB%AD%23) `150.7K 🔥` `NEW`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `148.4K 🔥` `NEW`
1. [吴世勋发合照 (Wu Shixun posted a group photo)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%B8%96%E5%8B%8B%E5%8F%91%E5%90%88%E7%85%A7%23) `146.9K 🔥` `NEW`
1. [柳智敏 我喜欢漂亮女人](https://s.weibo.com/weibo?q=%23%E6%9F%B3%E6%99%BA%E6%95%8F%20%E6%88%91%E5%96%9C%E6%AC%A2%E6%BC%82%E4%BA%AE%E5%A5%B3%E4%BA%BA%23) `146.1K 🔥` `NEW`
1. [有美国入侵伊拉克时的味道了](https://s.weibo.com/weibo?q=%23%E6%9C%89%E7%BE%8E%E5%9B%BD%E5%85%A5%E4%BE%B5%E4%BC%8A%E6%8B%89%E5%85%8B%E6%97%B6%E7%9A%84%E5%91%B3%E9%81%93%E4%BA%86%23) `144.7K 🔥` `NEW`
1. [王橹杰路透](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E8%B7%AF%E9%80%8F%23) `141.3K 🔥` `NEW`
1. [以色列](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%23) `125.9K 🔥` `NEW`
1. [姐姐姐夫戏份](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%E6%88%8F%E4%BB%BD%23) `120.2K 🔥` `NEW`
1. [无限期退出娱乐圈除非有商务](https://s.weibo.com/weibo?q=%23%E6%97%A0%E9%99%90%E6%9C%9F%E9%80%80%E5%87%BA%E5%A8%B1%E4%B9%90%E5%9C%88%E9%99%A4%E9%9D%9E%E6%9C%89%E5%95%86%E5%8A%A1%23) `109.4K 🔥` `NEW`
1. [草莓价格跌至1元一斤](https://s.weibo.com/weibo?q=%23%E8%8D%89%E8%8E%93%E4%BB%B7%E6%A0%BC%E8%B7%8C%E8%87%B31%E5%85%83%E4%B8%80%E6%96%A4%23) `100.7K 🔥` `NEW`
1. [张凌赫对着爱奇艺贴脸开大](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%AF%B9%E7%9D%80%E7%88%B1%E5%A5%87%E8%89%BA%E8%B4%B4%E8%84%B8%E5%BC%80%E5%A4%A7%23) `99.2K 🔥` `NEW`
1. [种地吧](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `97.0K 🔥` `NEW`
1. [Prada晚宴上的谷爱凌 (Gu Ailing at Prada dinner)](https://s.weibo.com/weibo?q=%23Prada%E6%99%9A%E5%AE%B4%E4%B8%8A%E7%9A%84%E8%B0%B7%E7%88%B1%E5%87%8C%23) `92.4K 🔥` `NEW`
1. [下一个是谁](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%98%AF%E8%B0%81%23) `90.1K 🔥` `NEW`
1. [宁艺卓美趋第一](https://s.weibo.com/weibo?q=%23%E5%AE%81%E8%89%BA%E5%8D%93%E7%BE%8E%E8%B6%8B%E7%AC%AC%E4%B8%80%23) `87.7K 🔥` `NEW`
1. [代孕子女落户争议](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E5%AD%95%E5%AD%90%E5%A5%B3%E8%90%BD%E6%88%B7%E4%BA%89%E8%AE%AE%23) `85.9K 🔥` `NEW`
1. [中国驻以色列使馆紧急通知](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%A9%BB%E4%BB%A5%E8%89%B2%E5%88%97%E4%BD%BF%E9%A6%86%E7%B4%A7%E6%80%A5%E9%80%9A%E7%9F%A5%23) `83.1K 🔥` `NEW`
1. [刘雯高开叉亮片裙](https://s.weibo.com/weibo?q=%23%E5%88%98%E9%9B%AF%E9%AB%98%E5%BC%80%E5%8F%89%E4%BA%AE%E7%89%87%E8%A3%99%23) `81.4K 🔥` `NEW`
1. [梦溪选错英雄](https://s.weibo.com/weibo?q=%23%E6%A2%A6%E6%BA%AA%E9%80%89%E9%94%99%E8%8B%B1%E9%9B%84%23) `79.5K 🔥` `NEW`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `79.3K 🔥` `NEW`
1. [退房的时候前台拿了个徐福记的糖纸](https://s.weibo.com/weibo?q=%23%E9%80%80%E6%88%BF%E7%9A%84%E6%97%B6%E5%80%99%E5%89%8D%E5%8F%B0%E6%8B%BF%E4%BA%86%E4%B8%AA%E5%BE%90%E7%A6%8F%E8%AE%B0%E7%9A%84%E7%B3%96%E7%BA%B8%23) `77.4K 🔥` `NEW`
1. [美伊对峙](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BC%8A%E5%AF%B9%E5%B3%99%23) `77.0K 🔥` `NEW`
1. [苏新皓突袭直播 (Su Xinhao's surprise live broadcast)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E6%96%B0%E7%9A%93%E7%AA%81%E8%A2%AD%E7%9B%B4%E6%92%AD%23) `72.5K 🔥` `NEW`
1. [小徐已成立公司](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%BE%90%E5%B7%B2%E6%88%90%E7%AB%8B%E5%85%AC%E5%8F%B8%23) `71.3K 🔥` `NEW`
1. [去年59元买的内存卡今年卖197元](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E5%B9%B459%E5%85%83%E4%B9%B0%E7%9A%84%E5%86%85%E5%AD%98%E5%8D%A1%E4%BB%8A%E5%B9%B4%E5%8D%96197%E5%85%83%23) `68.6K 🔥` `NEW`
1. [张极直播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9E%81%E7%9B%B4%E6%92%AD%23) `67.2K 🔥` `NEW`
1. [杨洋的手好肿](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E7%9A%84%E6%89%8B%E5%A5%BD%E8%82%BF%23) `67.2K 🔥` `NEW`
1. [育儿嫂看护时刷视频致婴儿病亡](https://s.weibo.com/weibo?q=%23%E8%82%B2%E5%84%BF%E5%AB%82%E7%9C%8B%E6%8A%A4%E6%97%B6%E5%88%B7%E8%A7%86%E9%A2%91%E8%87%B4%E5%A9%B4%E5%84%BF%E7%97%85%E4%BA%A1%23) `67.1K 🔥` `NEW`
1. [白敬亭章若楠 二搭](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E7%AB%A0%E8%8B%A5%E6%A5%A0%20%E4%BA%8C%E6%90%AD%23) `66.1K 🔥` `NEW`
1. [宝可梦风与波](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E5%8F%AF%E6%A2%A6%E9%A3%8E%E4%B8%8E%E6%B3%A2%23) `64.0K 🔥` `NEW`

Updated at 2026-02-28 00:22:51

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
