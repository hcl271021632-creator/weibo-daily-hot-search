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

1. [21岁女生头晕以为没睡好查出脑梗 (A 21-year-old girl felt dizzy and thought she hadn’t slept well and was diagnosed with cerebral infarction)](https://s.weibo.com/weibo?q=%2321%E5%B2%81%E5%A5%B3%E7%94%9F%E5%A4%B4%E6%99%95%E4%BB%A5%E4%B8%BA%E6%B2%A1%E7%9D%A1%E5%A5%BD%E6%9F%A5%E5%87%BA%E8%84%91%E6%A2%97%23) `826.8K 🔥` `NEW`
1. [反诈老陈因多次违规被罚](https://s.weibo.com/weibo?q=%23%E5%8F%8D%E8%AF%88%E8%80%81%E9%99%88%E5%9B%A0%E5%A4%9A%E6%AC%A1%E8%BF%9D%E8%A7%84%E8%A2%AB%E7%BD%9A%23) `203.5K 🔥` `NEW`
1. [杨幂谷爱凌合照 好娇啊小幂](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%B0%B7%E7%88%B1%E5%87%8C%E5%90%88%E7%85%A7%20%E5%A5%BD%E5%A8%87%E5%95%8A%E5%B0%8F%E5%B9%82%23) `163.4K 🔥` `NEW`
1. [徐福记回应米兰小伙求代购酥心糖](https://s.weibo.com/weibo?q=%23%E5%BE%90%E7%A6%8F%E8%AE%B0%E5%9B%9E%E5%BA%94%E7%B1%B3%E5%85%B0%E5%B0%8F%E4%BC%99%E6%B1%82%E4%BB%A3%E8%B4%AD%E9%85%A5%E5%BF%83%E7%B3%96%23) `146.7K 🔥` `NEW`
1. [姐姐姐夫戏份](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%E6%88%8F%E4%BB%BD%23) `126.1K 🔥` `NEW`
1. [高市早苗反对女天皇](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%8F%8D%E5%AF%B9%E5%A5%B3%E5%A4%A9%E7%9A%87%23) `119.0K 🔥` `NEW`
1. [下一个是谁](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%98%AF%E8%B0%81%23) `115.7K 🔥` `NEW`
1. [刘雯高开叉亮片裙](https://s.weibo.com/weibo?q=%23%E5%88%98%E9%9B%AF%E9%AB%98%E5%BC%80%E5%8F%89%E4%BA%AE%E7%89%87%E8%A3%99%23) `104.6K 🔥` `NEW`
1. [去年59元买的内存卡今年卖197元](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E5%B9%B459%E5%85%83%E4%B9%B0%E7%9A%84%E5%86%85%E5%AD%98%E5%8D%A1%E4%BB%8A%E5%B9%B4%E5%8D%96197%E5%85%83%23) `94.4K 🔥` `NEW`
1. [黄金手机贴克价达12666元](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E6%89%8B%E6%9C%BA%E8%B4%B4%E5%85%8B%E4%BB%B7%E8%BE%BE12666%E5%85%83%23) `93.8K 🔥` `NEW`
1. [DYG锁定第三轮S组 (DYG locks Group S in the third round)](https://s.weibo.com/weibo?q=%23DYG%E9%94%81%E5%AE%9A%E7%AC%AC%E4%B8%89%E8%BD%AES%E7%BB%84%23) `87.1K 🔥` `NEW`
1. [4件父母不要和孩子分享的事](https://s.weibo.com/weibo?q=%234%E4%BB%B6%E7%88%B6%E6%AF%8D%E4%B8%8D%E8%A6%81%E5%92%8C%E5%AD%A9%E5%AD%90%E5%88%86%E4%BA%AB%E7%9A%84%E4%BA%8B%23) `85.3K 🔥` `NEW`
1. [政府借厕所遭辱骂男子要求公开道歉](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%BA%9C%E5%80%9F%E5%8E%95%E6%89%80%E9%81%AD%E8%BE%B1%E9%AA%82%E7%94%B7%E5%AD%90%E8%A6%81%E6%B1%82%E5%85%AC%E5%BC%80%E9%81%93%E6%AD%89%23) `257.2K 🔥` `+61%`
1. [当妈妈把欧洲特产蒸了后](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%A6%88%E5%A6%88%E6%8A%8A%E6%AC%A7%E6%B4%B2%E7%89%B9%E4%BA%A7%E8%92%B8%E4%BA%86%E5%90%8E%23) `165.1K 🔥` `+40%`
1. [王橹杰路透](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E8%B7%AF%E9%80%8F%23) `152.2K 🔥` `+49%`
1. [提醒在伊朗的中国公民尽快撤离 (Chinese citizens in Iran are reminded to evacuate as soon as possible)](https://s.weibo.com/weibo?q=%23%E6%8F%90%E9%86%92%E5%9C%A8%E4%BC%8A%E6%9C%97%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E5%B0%BD%E5%BF%AB%E6%92%A4%E7%A6%BB%23) `1.1M 🔥`
1. [关注2026全国两会 (Pay attention to the 2026 National Two Sessions)](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%B3%A82026%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%23) `623.8K 🔥`
1. [三星S26 (Samsung S26)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%98%9FS26%23) `599.1K 🔥`
1. [虎跳峡男游客疑因洗杯落水失联](https://s.weibo.com/weibo?q=%23%E8%99%8E%E8%B7%B3%E5%B3%A1%E7%94%B7%E6%B8%B8%E5%AE%A2%E7%96%91%E5%9B%A0%E6%B4%97%E6%9D%AF%E8%90%BD%E6%B0%B4%E5%A4%B1%E8%81%94%23) `433.5K 🔥`
1. [美国 伊朗](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%20%E4%BC%8A%E6%9C%97%23) `175.0K 🔥`
1. [黄金 (gold)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `174.9K 🔥`
1. [奥黛丽厚本正完骨变薄本了](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E9%BB%9B%E4%B8%BD%E5%8E%9A%E6%9C%AC%E6%AD%A3%E5%AE%8C%E9%AA%A8%E5%8F%98%E8%96%84%E6%9C%AC%E4%BA%86%23) `174.8K 🔥`
1. [Gucci大秀](https://s.weibo.com/weibo?q=%23Gucci%E5%A4%A7%E7%A7%80%23) `174.8K 🔥`
1. [杨洋发文回应不让江山争议](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E4%BA%89%E8%AE%AE%23) `174.7K 🔥`
1. [无限期退出娱乐圈除非有商务 (Retire from the entertainment industry indefinitely unless there is business)](https://s.weibo.com/weibo?q=%23%E6%97%A0%E9%99%90%E6%9C%9F%E9%80%80%E5%87%BA%E5%A8%B1%E4%B9%90%E5%9C%88%E9%99%A4%E9%9D%9E%E6%9C%89%E5%95%86%E5%8A%A1%23) `172.7K 🔥`
1. [柳智敏 我喜欢漂亮女人](https://s.weibo.com/weibo?q=%23%E6%9F%B3%E6%99%BA%E6%95%8F%20%E6%88%91%E5%96%9C%E6%AC%A2%E6%BC%82%E4%BA%AE%E5%A5%B3%E4%BA%BA%23) `169.8K 🔥`
1. [伊朗 (Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `163.8K 🔥`
1. [Prada晚宴上的谷爱凌](https://s.weibo.com/weibo?q=%23Prada%E6%99%9A%E5%AE%B4%E4%B8%8A%E7%9A%84%E8%B0%B7%E7%88%B1%E5%87%8C%23) `162.5K 🔥`
1. [以色列](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%23) `144.2K 🔥`
1. [美伊对峙](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BC%8A%E5%AF%B9%E5%B3%99%23) `128.7K 🔥`
1. [种地吧](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `113.5K 🔥`
1. [美伊战争风险急剧升高](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BC%8A%E6%88%98%E4%BA%89%E9%A3%8E%E9%99%A9%E6%80%A5%E5%89%A7%E5%8D%87%E9%AB%98%23) `104.8K 🔥`
1. [育儿嫂看护时刷视频致婴儿病亡](https://s.weibo.com/weibo?q=%23%E8%82%B2%E5%84%BF%E5%AB%82%E7%9C%8B%E6%8A%A4%E6%97%B6%E5%88%B7%E8%A7%86%E9%A2%91%E8%87%B4%E5%A9%B4%E5%84%BF%E7%97%85%E4%BA%A1%23) `87.3K 🔥`
1. [始祖鸟财报](https://s.weibo.com/weibo?q=%23%E5%A7%8B%E7%A5%96%E9%B8%9F%E8%B4%A2%E6%8A%A5%23) `85.4K 🔥`
1. [美国双航母已就位](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%8F%8C%E8%88%AA%E6%AF%8D%E5%B7%B2%E5%B0%B1%E4%BD%8D%23) `282.9K 🔥` `-66%`
1. [伊军方将对美侵略予以毁灭性回应 (The Iraqi military will respond with a devastating response to the US aggression)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E5%86%9B%E6%96%B9%E5%B0%86%E5%AF%B9%E7%BE%8E%E4%BE%B5%E7%95%A5%E4%BA%88%E4%BB%A5%E6%AF%81%E7%81%AD%E6%80%A7%E5%9B%9E%E5%BA%94%23) `242.3K 🔥` `-30%`
1. [草莓价格跌至1元一斤 (Strawberry price drops to 1 yuan per pound)](https://s.weibo.com/weibo?q=%23%E8%8D%89%E8%8E%93%E4%BB%B7%E6%A0%BC%E8%B7%8C%E8%87%B31%E5%85%83%E4%B8%80%E6%96%A4%23) `175.1K 🔥` `-36%`
1. [Gucci直播](https://s.weibo.com/weibo?q=%23Gucci%E7%9B%B4%E6%92%AD%23) `175.1K 🔥` `-41%`
1. [中国驻以色列使馆紧急通知](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%A9%BB%E4%BB%A5%E8%89%B2%E5%88%97%E4%BD%BF%E9%A6%86%E7%B4%A7%E6%80%A5%E9%80%9A%E7%9F%A5%23) `174.6K 🔥` `-37%`
1. [退房的时候前台拿了个徐福记的糖纸 (When checking out, the front desk took a candy wrapper from Hsu Fu Chi.)](https://s.weibo.com/weibo?q=%23%E9%80%80%E6%88%BF%E7%9A%84%E6%97%B6%E5%80%99%E5%89%8D%E5%8F%B0%E6%8B%BF%E4%BA%86%E4%B8%AA%E5%BE%90%E7%A6%8F%E8%AE%B0%E7%9A%84%E7%B3%96%E7%BA%B8%23) `131.0K 🔥` `-35%`
1. [宁艺卓美趋第一 (Ning Yi Zhuo’s Beauty Trend is No. 1)](https://s.weibo.com/weibo?q=%23%E5%AE%81%E8%89%BA%E5%8D%93%E7%BE%8E%E8%B6%8B%E7%AC%AC%E4%B8%80%23) `122.8K 🔥` `-27%`
1. [宝可梦风与波 (Pokémon Wind and Waves)](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E5%8F%AF%E6%A2%A6%E9%A3%8E%E4%B8%8E%E6%B3%A2%23) `120.1K 🔥` `-41%`
1. [小徐已成立公司](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%BE%90%E5%B7%B2%E6%88%90%E7%AB%8B%E5%85%AC%E5%8F%B8%23) `119.0K 🔥` `-25%`
1. [杨洋的手好肿](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E7%9A%84%E6%89%8B%E5%A5%BD%E8%82%BF%23) `103.1K 🔥` `-23%`
1. [代孕子女落户争议](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E5%AD%95%E5%AD%90%E5%A5%B3%E8%90%BD%E6%88%B7%E4%BA%89%E8%AE%AE%23) `100.2K 🔥` `-37%`
1. [白敬亭章若楠 二搭 (Bai Jingting, Zhang Ruonan, Er Da)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E7%AB%A0%E8%8B%A5%E6%A5%A0%20%E4%BA%8C%E6%90%AD%23) `96.2K 🔥` `-36%`
1. [养过小孩的才知道他有多会教](https://s.weibo.com/weibo?q=%23%E5%85%BB%E8%BF%87%E5%B0%8F%E5%AD%A9%E7%9A%84%E6%89%8D%E7%9F%A5%E9%81%93%E4%BB%96%E6%9C%89%E5%A4%9A%E4%BC%9A%E6%95%99%23) `93.8K 🔥` `-26%`
1. [朴安娜 造型](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E5%AE%89%E5%A8%9C%20%E9%80%A0%E5%9E%8B%23) `88.0K 🔥` `-27%`
1. [张极直播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9E%81%E7%9B%B4%E6%92%AD%23) `85.3K 🔥` `-47%`

Updated at 2026-02-27 23:45:30

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
