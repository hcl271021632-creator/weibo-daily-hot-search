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

1. [2026探月任务清单刷新了 (The 2026 lunar exploration task list has been refreshed)](https://s.weibo.com/weibo?q=%232026%E6%8E%A2%E6%9C%88%E4%BB%BB%E5%8A%A1%E6%B8%85%E5%8D%95%E5%88%B7%E6%96%B0%E4%BA%86%23) `680.9K 🔥` `NEW`
1. [Gucci直播](https://s.weibo.com/weibo?q=%23Gucci%E7%9B%B4%E6%92%AD%23) `629.4K 🔥` `NEW`
1. [00后员工年薪80万是老板的6倍](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E5%91%98%E5%B7%A5%E5%B9%B4%E8%96%AA80%E4%B8%87%E6%98%AF%E8%80%81%E6%9D%BF%E7%9A%846%E5%80%8D%23) `379.7K 🔥` `NEW`
1. [FENDI2026秋冬时装秀](https://s.weibo.com/weibo?q=%23FENDI2026%E7%A7%8B%E5%86%AC%E6%97%B6%E8%A3%85%E7%A7%80%23) `351.1K 🔥` `NEW`
1. [男子高速路上发现62具宠物尸体](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%AB%98%E9%80%9F%E8%B7%AF%E4%B8%8A%E5%8F%91%E7%8E%B062%E5%85%B7%E5%AE%A0%E7%89%A9%E5%B0%B8%E4%BD%93%23) `332.3K 🔥` `NEW`
1. [一天100个电话见证海南自贸港热度](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%A4%A9100%E4%B8%AA%E7%94%B5%E8%AF%9D%E8%A7%81%E8%AF%81%E6%B5%B7%E5%8D%97%E8%87%AA%E8%B4%B8%E6%B8%AF%E7%83%AD%E5%BA%A6%23) `258.0K 🔥` `NEW`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `257.9K 🔥` `NEW`
1. [杨洋发文回应不让江山争议](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E4%BA%89%E8%AE%AE%23) `257.5K 🔥` `NEW`
1. [以色列](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%23) `256.6K 🔥` `NEW`
1. [代孕子女落户争议](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E5%AD%95%E5%AD%90%E5%A5%B3%E8%90%BD%E6%88%B7%E4%BA%89%E8%AE%AE%23) `255.8K 🔥` `NEW`
1. [宁艺卓美趋第一 (Ning Yi Zhuo’s Beauty Trend is No. 1)](https://s.weibo.com/weibo?q=%23%E5%AE%81%E8%89%BA%E5%8D%93%E7%BE%8E%E8%B6%8B%E7%AC%AC%E4%B8%80%23) `255.4K 🔥` `NEW`
1. [梦溪选错英雄](https://s.weibo.com/weibo?q=%23%E6%A2%A6%E6%BA%AA%E9%80%89%E9%94%99%E8%8B%B1%E9%9B%84%23) `185.7K 🔥` `NEW`
1. [于适吃盖浇饭庆祝镖人破10亿](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E9%80%82%E5%90%83%E7%9B%96%E6%B5%87%E9%A5%AD%E5%BA%86%E7%A5%9D%E9%95%96%E4%BA%BA%E7%A0%B410%E4%BA%BF%23) `184.9K 🔥` `NEW`
1. [张本智和2比3弗朗西斯卡](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9C%AC%E6%99%BA%E5%92%8C2%E6%AF%943%E5%BC%97%E6%9C%97%E8%A5%BF%E6%96%AF%E5%8D%A1%23) `183.0K 🔥` `NEW`
1. [米哈游公布猝死员工生前工作轨迹](https://s.weibo.com/weibo?q=%23%E7%B1%B3%E5%93%88%E6%B8%B8%E5%85%AC%E5%B8%83%E7%8C%9D%E6%AD%BB%E5%91%98%E5%B7%A5%E7%94%9F%E5%89%8D%E5%B7%A5%E4%BD%9C%E8%BD%A8%E8%BF%B9%23) `169.5K 🔥` `NEW`
1. [Prada晚宴上的谷爱凌](https://s.weibo.com/weibo?q=%23Prada%E6%99%9A%E5%AE%B4%E4%B8%8A%E7%9A%84%E8%B0%B7%E7%88%B1%E5%87%8C%23) `162.3K 🔥` `NEW`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `156.4K 🔥` `NEW`
1. [宁艺卓蛇纹皮衣](https://s.weibo.com/weibo?q=%23%E5%AE%81%E8%89%BA%E5%8D%93%E8%9B%87%E7%BA%B9%E7%9A%AE%E8%A1%A3%23) `155.4K 🔥` `NEW`
1. [官方通报母子坠入水坑溺亡](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%E6%AF%8D%E5%AD%90%E5%9D%A0%E5%85%A5%E6%B0%B4%E5%9D%91%E6%BA%BA%E4%BA%A1%23) `148.7K 🔥` `NEW`
1. [六旬老太用花洒灌肠通便直肠破裂](https://s.weibo.com/weibo?q=%23%E5%85%AD%E6%97%AC%E8%80%81%E5%A4%AA%E7%94%A8%E8%8A%B1%E6%B4%92%E7%81%8C%E8%82%A0%E9%80%9A%E4%BE%BF%E7%9B%B4%E8%82%A0%E7%A0%B4%E8%A3%82%23) `140.0K 🔥` `NEW`
1. [双高胎直播 (Double high tire live broadcast)](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E9%AB%98%E8%83%8E%E7%9B%B4%E6%92%AD%23) `132.9K 🔥` `NEW`
1. [汪苏泷演唱会](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E6%BC%94%E5%94%B1%E4%BC%9A%23) `130.7K 🔥` `NEW`
1. [黄景瑜抓内鬼王天辰扫雷](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E6%8A%93%E5%86%85%E9%AC%BC%E7%8E%8B%E5%A4%A9%E8%BE%B0%E6%89%AB%E9%9B%B7%23) `106.9K 🔥` `NEW`
1. [雷军再强调辅助驾驶无法代替人类](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%86%8D%E5%BC%BA%E8%B0%83%E8%BE%85%E5%8A%A9%E9%A9%BE%E9%A9%B6%E6%97%A0%E6%B3%95%E4%BB%A3%E6%9B%BF%E4%BA%BA%E7%B1%BB%23) `101.4K 🔥` `NEW`
1. [中国地图软件在外网火了](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%9C%B0%E5%9B%BE%E8%BD%AF%E4%BB%B6%E5%9C%A8%E5%A4%96%E7%BD%91%E7%81%AB%E4%BA%86%23) `99.5K 🔥` `NEW`
1. [李昀锐周翊然新剧演父子](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E5%91%A8%E7%BF%8A%E7%84%B6%E6%96%B0%E5%89%A7%E6%BC%94%E7%88%B6%E5%AD%90%23) `99.3K 🔥` `NEW`
1. [白宇前女友说终于有了很骄傲的感觉](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%87%E5%89%8D%E5%A5%B3%E5%8F%8B%E8%AF%B4%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%86%E5%BE%88%E9%AA%84%E5%82%B2%E7%9A%84%E6%84%9F%E8%A7%89%23) `98.8K 🔥` `NEW`
1. [弟弟凭一双手死死拦住迎亲队伍](https://s.weibo.com/weibo?q=%23%E5%BC%9F%E5%BC%9F%E5%87%AD%E4%B8%80%E5%8F%8C%E6%89%8B%E6%AD%BB%E6%AD%BB%E6%8B%A6%E4%BD%8F%E8%BF%8E%E4%BA%B2%E9%98%9F%E4%BC%8D%23) `92.7K 🔥` `NEW`
1. [美团外卖送开工好礼](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%A2%E5%A4%96%E5%8D%96%E9%80%81%E5%BC%80%E5%B7%A5%E5%A5%BD%E7%A4%BC%23) `636.7K 🔥` `+30%`
1. [RW 选错英雄](https://s.weibo.com/weibo?q=%23RW%20%E9%80%89%E9%94%99%E8%8B%B1%E9%9B%84%23) `356.7K 🔥` `+282%`
1. [退房的时候前台拿了个徐福记的糖纸 (When checking out, the front desk took a candy wrapper from Hsu Fu Chi.)](https://s.weibo.com/weibo?q=%23%E9%80%80%E6%88%BF%E7%9A%84%E6%97%B6%E5%80%99%E5%89%8D%E5%8F%B0%E6%8B%BF%E4%BA%86%E4%B8%AA%E5%BE%90%E7%A6%8F%E8%AE%B0%E7%9A%84%E7%B3%96%E7%BA%B8%23) `309.1K 🔥` `+25%`
1. [杨洋的手好肿](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E7%9A%84%E6%89%8B%E5%A5%BD%E8%82%BF%23) `255.0K 🔥` `+51%`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `254.9K 🔥` `+120%`
1. [种地吧](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `179.7K 🔥` `+69%`
1. [提醒在伊朗的中国公民尽快撤离 (Chinese citizens in Iran are reminded to evacuate as soon as possible)](https://s.weibo.com/weibo?q=%23%E6%8F%90%E9%86%92%E5%9C%A8%E4%BC%8A%E6%9C%97%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E5%B0%BD%E5%BF%AB%E6%92%A4%E7%A6%BB%23) `1.2M 🔥`
1. [草莓价格跌至1元一斤 (Strawberry price drops to 1 yuan per pound)](https://s.weibo.com/weibo?q=%23%E8%8D%89%E8%8E%93%E4%BB%B7%E6%A0%BC%E8%B7%8C%E8%87%B31%E5%85%83%E4%B8%80%E6%96%A4%23) `837.5K 🔥`
1. [林俊杰回复张凌赫](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E5%9B%9E%E5%A4%8D%E5%BC%A0%E5%87%8C%E8%B5%AB%23) `273.2K 🔥`
1. [白敬亭章若楠 二搭 (Bai Jingting, Zhang Ruonan, Er Da)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E7%AB%A0%E8%8B%A5%E6%A5%A0%20%E4%BA%8C%E6%90%AD%23) `258.5K 🔥`
1. [无限期退出娱乐圈除非有商务](https://s.weibo.com/weibo?q=%23%E6%97%A0%E9%99%90%E6%9C%9F%E9%80%80%E5%87%BA%E5%A8%B1%E4%B9%90%E5%9C%88%E9%99%A4%E9%9D%9E%E6%9C%89%E5%95%86%E5%8A%A1%23) `256.9K 🔥`
1. [李胜利的狱友repo (Li Shengli’s inmate repo)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%83%9C%E5%88%A9%E7%9A%84%E7%8B%B1%E5%8F%8Brepo%23) `170.4K 🔥`
1. [养过小孩的才知道他有多会教](https://s.weibo.com/weibo?q=%23%E5%85%BB%E8%BF%87%E5%B0%8F%E5%AD%A9%E7%9A%84%E6%89%8D%E7%9F%A5%E9%81%93%E4%BB%96%E6%9C%89%E5%A4%9A%E4%BC%9A%E6%95%99%23) `125.8K 🔥`
1. [朱志鑫直播](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E7%9B%B4%E6%92%AD%23) `119.7K 🔥`
1. [见春天 陈飞宇王影璐 (See Spring Chen Feiyu Wang Yinglu)](https://s.weibo.com/weibo?q=%23%E8%A7%81%E6%98%A5%E5%A4%A9%20%E9%99%88%E9%A3%9E%E5%AE%87%E7%8E%8B%E5%BD%B1%E7%92%90%23) `101.2K 🔥`
1. [李胜利唯独管GD直接叫GD](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%83%9C%E5%88%A9%E5%94%AF%E7%8B%AC%E7%AE%A1GD%E7%9B%B4%E6%8E%A5%E5%8F%ABGD%23) `100.2K 🔥`
1. [妈妈在女儿婚礼上美出圈](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9C%A8%E5%A5%B3%E5%84%BF%E5%A9%9A%E7%A4%BC%E4%B8%8A%E7%BE%8E%E5%87%BA%E5%9C%88%23) `166.3K 🔥` `-36%`
1. [下一个是谁 (who is next)](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%98%AF%E8%B0%81%23) `121.4K 🔥` `-47%`
1. [不建议在朋友圈展示技能 (It is not recommended to show skills in the circle of friends)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%BB%BA%E8%AE%AE%E5%9C%A8%E6%9C%8B%E5%8F%8B%E5%9C%88%E5%B1%95%E7%A4%BA%E6%8A%80%E8%83%BD%23) `101.3K 🔥` `-50%`
1. [王皓开玩笑说王楚钦的签名我哪会 (Wang Hao joked that I can’t write Wang Chuqin’s signature.)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%9A%93%E5%BC%80%E7%8E%A9%E7%AC%91%E8%AF%B4%E7%8E%8B%E6%A5%9A%E9%92%A6%E7%9A%84%E7%AD%BE%E5%90%8D%E6%88%91%E5%93%AA%E4%BC%9A%23) `98.3K 🔥` `-57%`
1. [现在就出发4 (Let's go now 4)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%23) `98.3K 🔥` `-35%`
1. [BLACKPINK回归 敷衍](https://s.weibo.com/weibo?q=%23BLACKPINK%E5%9B%9E%E5%BD%92%20%E6%95%B7%E8%A1%8D%23) `90.6K 🔥` `-28%`

Updated at 2026-02-27 21:20:11

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
