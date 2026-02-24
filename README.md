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

1. [12306半夜候补成功1700元车票作废 (12306 Successful waiting list in the middle of the night, ticket worth 1,700 yuan is invalid)](https://s.weibo.com/weibo?q=%2312306%E5%8D%8A%E5%A4%9C%E5%80%99%E8%A1%A5%E6%88%90%E5%8A%9F1700%E5%85%83%E8%BD%A6%E7%A5%A8%E4%BD%9C%E5%BA%9F%23) `1.6M 🔥` `NEW`
1. [灵隐寺惊现110万家厂商祈福](https://s.weibo.com/weibo?q=%23%E7%81%B5%E9%9A%90%E5%AF%BA%E6%83%8A%E7%8E%B0110%E4%B8%87%E5%AE%B6%E5%8E%82%E5%95%86%E7%A5%88%E7%A6%8F%23) `723.2K 🔥` `NEW`
1. [高速免费最后1分钟实拍](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%85%8D%E8%B4%B9%E6%9C%80%E5%90%8E1%E5%88%86%E9%92%9F%E5%AE%9E%E6%8B%8D%23) `628.3K 🔥` `NEW`
1. [妈祖被换女孩三天涨粉几十万](https://s.weibo.com/weibo?q=%23%E5%A6%88%E7%A5%96%E8%A2%AB%E6%8D%A2%E5%A5%B3%E5%AD%A9%E4%B8%89%E5%A4%A9%E6%B6%A8%E7%B2%89%E5%87%A0%E5%8D%81%E4%B8%87%23) `609.4K 🔥` `NEW`
1. [考研查分](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E6%9F%A5%E5%88%86%23) `478.3K 🔥` `NEW`
1. [飞驰人生3春节档冠军](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E6%98%A5%E8%8A%82%E6%A1%A3%E5%86%A0%E5%86%9B%23) `415.4K 🔥` `NEW`
1. [研招网](https://s.weibo.com/weibo?q=%23%E7%A0%94%E6%8B%9B%E7%BD%91%23) `353.5K 🔥` `NEW`
1. [车主卡点下高速失败缴费400元](https://s.weibo.com/weibo?q=%23%E8%BD%A6%E4%B8%BB%E5%8D%A1%E7%82%B9%E4%B8%8B%E9%AB%98%E9%80%9F%E5%A4%B1%E8%B4%A5%E7%BC%B4%E8%B4%B9400%E5%85%83%23) `340.2K 🔥` `NEW`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `331.3K 🔥` `NEW`
1. [秋雅别打电话了 我怕夏洛误会](https://s.weibo.com/weibo?q=%23%E7%A7%8B%E9%9B%85%E5%88%AB%E6%89%93%E7%94%B5%E8%AF%9D%E4%BA%86%20%E6%88%91%E6%80%95%E5%A4%8F%E6%B4%9B%E8%AF%AF%E4%BC%9A%23) `327.5K 🔥` `NEW`
1. [多地考研今日出分 (Scores for postgraduate entrance exams in many places are released today)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E8%80%83%E7%A0%94%E4%BB%8A%E6%97%A5%E5%87%BA%E5%88%86%23) `305.3K 🔥` `NEW`
1. [iPhone18Pro小批量试产](https://s.weibo.com/weibo?q=%23iPhone18Pro%E5%B0%8F%E6%89%B9%E9%87%8F%E8%AF%95%E4%BA%A7%23) `287.3K 🔥` `NEW`
1. [韩寒透露飞驰人生4](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%AF%92%E9%80%8F%E9%9C%B2%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F4%23) `235.0K 🔥` `NEW`
1. [考研](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%23) `224.4K 🔥` `NEW`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `206.2K 🔥` `NEW`
1. [曝百妖谱主演阵容](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%99%BE%E5%A6%96%E8%B0%B1%E4%B8%BB%E6%BC%94%E9%98%B5%E5%AE%B9%23) `204.3K 🔥` `NEW`
1. [12306回应半夜候补成功无法退款](https://s.weibo.com/weibo?q=%2312306%E5%9B%9E%E5%BA%94%E5%8D%8A%E5%A4%9C%E5%80%99%E8%A1%A5%E6%88%90%E5%8A%9F%E6%97%A0%E6%B3%95%E9%80%80%E6%AC%BE%23) `195.2K 🔥` `NEW`
1. [不发朋友圈的人是什么性格](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%8F%91%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%9A%84%E4%BA%BA%E6%98%AF%E4%BB%80%E4%B9%88%E6%80%A7%E6%A0%BC%23) `195.1K 🔥` `NEW`
1. [代旭劝学](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E6%97%AD%E5%8A%9D%E5%AD%A6%23) `189.4K 🔥` `NEW`
1. [iPhone18Pro灵动岛缩小35%](https://s.weibo.com/weibo?q=%23iPhone18Pro%E7%81%B5%E5%8A%A8%E5%B2%9B%E7%BC%A9%E5%B0%8F35%25%23) `160.4K 🔥` `NEW`
1. [iPhone18Pro新配色目标一眼最新款 (iPhone 18 Pro new color target at a glance the latest model)](https://s.weibo.com/weibo?q=%23iPhone18Pro%E6%96%B0%E9%85%8D%E8%89%B2%E7%9B%AE%E6%A0%87%E4%B8%80%E7%9C%BC%E6%9C%80%E6%96%B0%E6%AC%BE%23) `150.3K 🔥` `NEW`
1. [杨洋方安抚粉丝](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E6%96%B9%E5%AE%89%E6%8A%9A%E7%B2%89%E4%B8%9D%23) `140.9K 🔥` `NEW`
1. [雷军亲自发开工红包](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E4%BA%B2%E8%87%AA%E5%8F%91%E5%BC%80%E5%B7%A5%E7%BA%A2%E5%8C%85%23) `140.2K 🔥` `NEW`
1. [石雷鹏 今天大概率出不了分](https://s.weibo.com/weibo?q=%23%E7%9F%B3%E9%9B%B7%E9%B9%8F%20%E4%BB%8A%E5%A4%A9%E5%A4%A7%E6%A6%82%E7%8E%87%E5%87%BA%E4%B8%8D%E4%BA%86%E5%88%86%23) `139.1K 🔥` `NEW`
1. [少女9300元贱卖妈妈13万奢侈品](https://s.weibo.com/weibo?q=%23%E5%B0%91%E5%A5%B39300%E5%85%83%E8%B4%B1%E5%8D%96%E5%A6%88%E5%A6%8813%E4%B8%87%E5%A5%A2%E4%BE%88%E5%93%81%23) `137.1K 🔥` `NEW`
1. [谷爱凌我有个想法但我不敢说](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%88%91%E6%9C%89%E4%B8%AA%E6%83%B3%E6%B3%95%E4%BD%86%E6%88%91%E4%B8%8D%E6%95%A2%E8%AF%B4%23) `127.1K 🔥` `NEW`
1. [为什么狗狗睡着后会有一股小狗味](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E7%8B%97%E7%8B%97%E7%9D%A1%E7%9D%80%E5%90%8E%E4%BC%9A%E6%9C%89%E4%B8%80%E8%82%A1%E5%B0%8F%E7%8B%97%E5%91%B3%23) `121.8K 🔥` `NEW`
1. [小米马年开工两件大事](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E9%A9%AC%E5%B9%B4%E5%BC%80%E5%B7%A5%E4%B8%A4%E4%BB%B6%E5%A4%A7%E4%BA%8B%23) `119.7K 🔥` `NEW`
1. [开工第一天别超负荷工作](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%E5%88%AB%E8%B6%85%E8%B4%9F%E8%8D%B7%E5%B7%A5%E4%BD%9C%23) `119.6K 🔥` `NEW`
1. [谷爱凌在斯坦福选修量子物理哲学](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%9C%A8%E6%96%AF%E5%9D%A6%E7%A6%8F%E9%80%89%E4%BF%AE%E9%87%8F%E5%AD%90%E7%89%A9%E7%90%86%E5%93%B2%E5%AD%A6%23) `119.4K 🔥` `NEW`
1. [孙千这段早播二十年能救不少人 (Sun Qian's episode could have saved many people if it had been broadcast twenty years earlier.)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E5%8D%83%E8%BF%99%E6%AE%B5%E6%97%A9%E6%92%AD%E4%BA%8C%E5%8D%81%E5%B9%B4%E8%83%BD%E6%95%91%E4%B8%8D%E5%B0%91%E4%BA%BA%23) `117.6K 🔥` `NEW`
1. [马嘉祺晒开工红包](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%98%89%E7%A5%BA%E6%99%92%E5%BC%80%E5%B7%A5%E7%BA%A2%E5%8C%85%23) `116.2K 🔥` `NEW`
1. [谷爱凌斯坦福大学宿舍曾被闯入](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%96%AF%E5%9D%A6%E7%A6%8F%E5%A4%A7%E5%AD%A6%E5%AE%BF%E8%88%8D%E6%9B%BE%E8%A2%AB%E9%97%AF%E5%85%A5%23) `113.7K 🔥` `NEW`
1. [谢霆锋张婧仪 用花无缺打开镖人](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E9%9C%86%E9%94%8B%E5%BC%A0%E5%A9%A7%E4%BB%AA%20%E7%94%A8%E8%8A%B1%E6%97%A0%E7%BC%BA%E6%89%93%E5%BC%80%E9%95%96%E4%BA%BA%23) `113.0K 🔥` `NEW`
1. [距离下个假期还有40天](https://s.weibo.com/weibo?q=%23%E8%B7%9D%E7%A6%BB%E4%B8%8B%E4%B8%AA%E5%81%87%E6%9C%9F%E8%BF%98%E6%9C%8940%E5%A4%A9%23) `97.6K 🔥` `NEW`
1. [星河入梦 0爱情](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%200%E7%88%B1%E6%83%85%23) `96.1K 🔥` `NEW`
1. [想把你和时间藏起来官宣](https://s.weibo.com/weibo?q=%23%E6%83%B3%E6%8A%8A%E4%BD%A0%E5%92%8C%E6%97%B6%E9%97%B4%E8%97%8F%E8%B5%B7%E6%9D%A5%E5%AE%98%E5%AE%A3%23) `95.5K 🔥` `NEW`
1. [三星全球首发防窥屏](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%98%9F%E5%85%A8%E7%90%83%E9%A6%96%E5%8F%91%E9%98%B2%E7%AA%A5%E5%B1%8F%23) `94.3K 🔥` `NEW`
1. [周也张婧仪宋威龙张凌赫 莞莞类卿](https://s.weibo.com/weibo?q=%23%E5%91%A8%E4%B9%9F%E5%BC%A0%E5%A9%A7%E4%BB%AA%E5%AE%8B%E5%A8%81%E9%BE%99%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E8%8E%9E%E8%8E%9E%E7%B1%BB%E5%8D%BF%23) `93.6K 🔥` `NEW`
1. [差点问陈坤要联系方式了](https://s.weibo.com/weibo?q=%23%E5%B7%AE%E7%82%B9%E9%97%AE%E9%99%88%E5%9D%A4%E8%A6%81%E8%81%94%E7%B3%BB%E6%96%B9%E5%BC%8F%E4%BA%86%23) `91.4K 🔥` `NEW`
1. [从中医角度谈月经推迟 (Discussing delayed menstruation from the perspective of traditional Chinese medicine)](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E4%B8%AD%E5%8C%BB%E8%A7%92%E5%BA%A6%E8%B0%88%E6%9C%88%E7%BB%8F%E6%8E%A8%E8%BF%9F%23) `91.2K 🔥` `NEW`
1. [夜王 删镜头](https://s.weibo.com/weibo?q=%23%E5%A4%9C%E7%8E%8B%20%E5%88%A0%E9%95%9C%E5%A4%B4%23) `91.2K 🔥` `NEW`
1. [爬山到最后的统一姿势](https://s.weibo.com/weibo?q=%23%E7%88%AC%E5%B1%B1%E5%88%B0%E6%9C%80%E5%90%8E%E7%9A%84%E7%BB%9F%E4%B8%80%E5%A7%BF%E5%8A%BF%23) `85.6K 🔥` `NEW`
1. [考研出分时间 (Postgraduate entrance examination score time)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E5%87%BA%E5%88%86%E6%97%B6%E9%97%B4%23) `1.5M 🔥` `+390%`
1. [在全党开展树立和践行正确政绩观学习教育](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%85%A8%E5%85%9A%E5%BC%80%E5%B1%95%E6%A0%91%E7%AB%8B%E5%92%8C%E8%B7%B5%E8%A1%8C%E6%AD%A3%E7%A1%AE%E6%94%BF%E7%BB%A9%E8%A7%82%E5%AD%A6%E4%B9%A0%E6%95%99%E8%82%B2%23) `880.5K 🔥` `+40%`
1. [开工大吉](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E5%A4%A7%E5%90%89%23) `199.0K 🔥` `+37%`
1. [陈凯文 双眼皮](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%87%AF%E6%96%87%20%E5%8F%8C%E7%9C%BC%E7%9A%AE%23) `102.0K 🔥` `+106%`
1. [宋亚轩晒照祝丁程鑫程鑫如意](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BA%9A%E8%BD%A9%E6%99%92%E7%85%A7%E7%A5%9D%E4%B8%81%E7%A8%8B%E9%91%AB%E7%A8%8B%E9%91%AB%E5%A6%82%E6%84%8F%23) `89.9K 🔥` `+44%`
1. [夜王 尺度 (night king scale)](https://s.weibo.com/weibo?q=%23%E5%A4%9C%E7%8E%8B%20%E5%B0%BA%E5%BA%A6%23) `181.5K 🔥` `-46%`
1. [误转69万公款对方拒绝退款 (The other party refused to refund 690,000 public funds mistakenly)](https://s.weibo.com/weibo?q=%23%E8%AF%AF%E8%BD%AC69%E4%B8%87%E5%85%AC%E6%AC%BE%E5%AF%B9%E6%96%B9%E6%8B%92%E7%BB%9D%E9%80%80%E6%AC%BE%23) `171.3K 🔥` `-85%`

Updated at 2026-02-24 10:54:58

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
