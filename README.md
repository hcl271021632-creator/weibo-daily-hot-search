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

1. [冷空气返场厚衣服先别收 (The cold air is back. Don’t put away your thick clothes yet.)](https://s.weibo.com/weibo?q=%23%E5%86%B7%E7%A9%BA%E6%B0%94%E8%BF%94%E5%9C%BA%E5%8E%9A%E8%A1%A3%E6%9C%8D%E5%85%88%E5%88%AB%E6%94%B6%23) `641.1K 🔥` `NEW`
1. [微信能看图片使用次数了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%83%BD%E7%9C%8B%E5%9B%BE%E7%89%87%E4%BD%BF%E7%94%A8%E6%AC%A1%E6%95%B0%E4%BA%86%23) `392.1K 🔥` `NEW`
1. [花10万做折角腰整形醒来浑身血水](https://s.weibo.com/weibo?q=%23%E8%8A%B110%E4%B8%87%E5%81%9A%E6%8A%98%E8%A7%92%E8%85%B0%E6%95%B4%E5%BD%A2%E9%86%92%E6%9D%A5%E6%B5%91%E8%BA%AB%E8%A1%80%E6%B0%B4%23) `369.7K 🔥` `NEW`
1. [董宇辉休了工作以来最长春节假](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AE%87%E8%BE%89%E4%BC%91%E4%BA%86%E5%B7%A5%E4%BD%9C%E4%BB%A5%E6%9D%A5%E6%9C%80%E9%95%BF%E6%98%A5%E8%8A%82%E5%81%87%23) `265.5K 🔥` `NEW`
1. [终于有人知道补枪的重要性了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E7%9F%A5%E9%81%93%E8%A1%A5%E6%9E%AA%E7%9A%84%E9%87%8D%E8%A6%81%E6%80%A7%E4%BA%86%23) `222.7K 🔥` `NEW`
1. [男演员点赞和刘晓庆搭戏是工伤](https://s.weibo.com/weibo?q=%23%E7%94%B7%E6%BC%94%E5%91%98%E7%82%B9%E8%B5%9E%E5%92%8C%E5%88%98%E6%99%93%E5%BA%86%E6%90%AD%E6%88%8F%E6%98%AF%E5%B7%A5%E4%BC%A4%23) `195.0K 🔥` `NEW`
1. [神童与父母断绝联系](https://s.weibo.com/weibo?q=%23%E7%A5%9E%E7%AB%A5%E4%B8%8E%E7%88%B6%E6%AF%8D%E6%96%AD%E7%BB%9D%E8%81%94%E7%B3%BB%23) `194.6K 🔥` `NEW`
1. [永远可以相信杨紫的眼神戏](https://s.weibo.com/weibo?q=%23%E6%B0%B8%E8%BF%9C%E5%8F%AF%E4%BB%A5%E7%9B%B8%E4%BF%A1%E6%9D%A8%E7%B4%AB%E7%9A%84%E7%9C%BC%E7%A5%9E%E6%88%8F%23) `194.1K 🔥` `NEW`
1. [文淇往那一站就有封面感](https://s.weibo.com/weibo?q=%23%E6%96%87%E6%B7%87%E5%BE%80%E9%82%A3%E4%B8%80%E7%AB%99%E5%B0%B1%E6%9C%89%E5%B0%81%E9%9D%A2%E6%84%9F%23) `193.8K 🔥` `NEW`
1. [女子泰国机场1110元金价买了周大福](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%B3%B0%E5%9B%BD%E6%9C%BA%E5%9C%BA1110%E5%85%83%E9%87%91%E4%BB%B7%E4%B9%B0%E4%BA%86%E5%91%A8%E5%A4%A7%E7%A6%8F%23) `193.6K 🔥` `NEW`
1. [乘客车上排泄后失联司机发声 (Driver lost contact after passenger excreted in car and spoke out)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E5%AE%A2%E8%BD%A6%E4%B8%8A%E6%8E%92%E6%B3%84%E5%90%8E%E5%A4%B1%E8%81%94%E5%8F%B8%E6%9C%BA%E5%8F%91%E5%A3%B0%23) `193.2K 🔥` `NEW`
1. [迪丽热巴王楚然 处处为营只为得到你](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%8E%8B%E6%A5%9A%E7%84%B6%20%E5%A4%84%E5%A4%84%E4%B8%BA%E8%90%A5%E5%8F%AA%E4%B8%BA%E5%BE%97%E5%88%B0%E4%BD%A0%23) `193.2K 🔥` `NEW`
1. [2026考研查分时间](https://s.weibo.com/weibo?q=%232026%E8%80%83%E7%A0%94%E6%9F%A5%E5%88%86%E6%97%B6%E9%97%B4%23) `192.1K 🔥` `NEW`
1. [教育局回应5点半读书23点20放学作息表](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%82%B2%E5%B1%80%E5%9B%9E%E5%BA%945%E7%82%B9%E5%8D%8A%E8%AF%BB%E4%B9%A623%E7%82%B920%E6%94%BE%E5%AD%A6%E4%BD%9C%E6%81%AF%E8%A1%A8%23) `191.4K 🔥` `NEW`
1. [李云霄下巴是陈丽君的指纹识别吗](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BA%91%E9%9C%84%E4%B8%8B%E5%B7%B4%E6%98%AF%E9%99%88%E4%B8%BD%E5%90%9B%E7%9A%84%E6%8C%87%E7%BA%B9%E8%AF%86%E5%88%AB%E5%90%97%23) `174.4K 🔥` `NEW`
1. [医生谈美甲对健康的隐患](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E8%B0%88%E7%BE%8E%E7%94%B2%E5%AF%B9%E5%81%A5%E5%BA%B7%E7%9A%84%E9%9A%90%E6%82%A3%23) `157.6K 🔥` `NEW`
1. [田柾国回应抽烟](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9F%BE%E5%9B%BD%E5%9B%9E%E5%BA%94%E6%8A%BD%E7%83%9F%23) `150.0K 🔥` `NEW`
1. [带孩子有多累具像化了](https://s.weibo.com/weibo?q=%23%E5%B8%A6%E5%AD%A9%E5%AD%90%E6%9C%89%E5%A4%9A%E7%B4%AF%E5%85%B7%E5%83%8F%E5%8C%96%E4%BA%86%23) `142.2K 🔥` `NEW`
1. [高铁幼童哭闹男子要求父母带离](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%93%81%E5%B9%BC%E7%AB%A5%E5%93%AD%E9%97%B9%E7%94%B7%E5%AD%90%E8%A6%81%E6%B1%82%E7%88%B6%E6%AF%8D%E5%B8%A6%E7%A6%BB%23) `130.1K 🔥` `NEW`
1. [向佑不满遗产分配直喊不公平](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%91%E4%B8%8D%E6%BB%A1%E9%81%97%E4%BA%A7%E5%88%86%E9%85%8D%E7%9B%B4%E5%96%8A%E4%B8%8D%E5%85%AC%E5%B9%B3%23) `124.1K 🔥` `NEW`
1. [可口可乐vs百事可乐 (Coca-Cola vs Pepsi)](https://s.weibo.com/weibo?q=%23%E5%8F%AF%E5%8F%A3%E5%8F%AF%E4%B9%90vs%E7%99%BE%E4%BA%8B%E5%8F%AF%E4%B9%90%23) `123.2K 🔥` `NEW`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `111.8K 🔥` `NEW`
1. [春日减肥计划该提上日程了](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%97%A5%E5%87%8F%E8%82%A5%E8%AE%A1%E5%88%92%E8%AF%A5%E6%8F%90%E4%B8%8A%E6%97%A5%E7%A8%8B%E4%BA%86%23) `111.0K 🔥` `NEW`
1. [凌晨三点半风把智能锁吹开了](https://s.weibo.com/weibo?q=%23%E5%87%8C%E6%99%A8%E4%B8%89%E7%82%B9%E5%8D%8A%E9%A3%8E%E6%8A%8A%E6%99%BA%E8%83%BD%E9%94%81%E5%90%B9%E5%BC%80%E4%BA%86%23) `110.6K 🔥` `NEW`
1. [刘浩存开工跳蒙古舞](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%E5%BC%80%E5%B7%A5%E8%B7%B3%E8%92%99%E5%8F%A4%E8%88%9E%23) `103.3K 🔥` `NEW`
1. [奶茶杯盖正确用法](https://s.weibo.com/weibo?q=%23%E5%A5%B6%E8%8C%B6%E6%9D%AF%E7%9B%96%E6%AD%A3%E7%A1%AE%E7%94%A8%E6%B3%95%23) `95.5K 🔥` `NEW`
1. [王者达摩新皮肤星君亢金](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%80%85%E8%BE%BE%E6%91%A9%E6%96%B0%E7%9A%AE%E8%82%A4%E6%98%9F%E5%90%9B%E4%BA%A2%E9%87%91%23) `95.1K 🔥` `NEW`
1. [中国公民大阪街头被劫500万日元](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E5%A4%A7%E9%98%AA%E8%A1%97%E5%A4%B4%E8%A2%AB%E5%8A%AB500%E4%B8%87%E6%97%A5%E5%85%83%23) `94.2K 🔥` `NEW`
1. [携程集团总裁范敏辞职](https://s.weibo.com/weibo?q=%23%E6%90%BA%E7%A8%8B%E9%9B%86%E5%9B%A2%E6%80%BB%E8%A3%81%E8%8C%83%E6%95%8F%E8%BE%9E%E8%81%8C%23) `89.8K 🔥` `NEW`
1. [美国全职妈妈想成为中国辣妹](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%85%A8%E8%81%8C%E5%A6%88%E5%A6%88%E6%83%B3%E6%88%90%E4%B8%BA%E4%B8%AD%E5%9B%BD%E8%BE%A3%E5%A6%B9%23) `88.8K 🔥` `NEW`
1. [吴京 领导讲话我施法 (Wu Jing: When the leader speaks, I cast a spell)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E9%A2%86%E5%AF%BC%E8%AE%B2%E8%AF%9D%E6%88%91%E6%96%BD%E6%B3%95%23) `88.6K 🔥` `NEW`
1. [俄乌冲突 (Russia-Ukraine conflict)](https://s.weibo.com/weibo?q=%23%E4%BF%84%E4%B9%8C%E5%86%B2%E7%AA%81%23) `1.1M 🔥` `+35%`
1. [企业招聘限男性限已婚已育](https://s.weibo.com/weibo?q=%23%E4%BC%81%E4%B8%9A%E6%8B%9B%E8%81%98%E9%99%90%E7%94%B7%E6%80%A7%E9%99%90%E5%B7%B2%E5%A9%9A%E5%B7%B2%E8%82%B2%23) `787.8K 🔥` `+509%`
1. [于适瑷尔博士全球品牌代言人 (Dr. Yu Shi Aier Global Brand Spokesperson)](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E9%80%82%E7%91%B7%E5%B0%94%E5%8D%9A%E5%A3%AB%E5%85%A8%E7%90%83%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `502.8K 🔥` `+811%`
1. [刘晓庆75岁再演少女](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%8675%E5%B2%81%E5%86%8D%E6%BC%94%E5%B0%91%E5%A5%B3%23) `489.1K 🔥` `+191%`
1. [女子嘴角起泡未重视竟脑死亡](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%98%B4%E8%A7%92%E8%B5%B7%E6%B3%A1%E6%9C%AA%E9%87%8D%E8%A7%86%E7%AB%9F%E8%84%91%E6%AD%BB%E4%BA%A1%23) `392.0K 🔥` `+102%`
1. [一点点 资助](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%20%E8%B5%84%E5%8A%A9%23) `194.8K 🔥`
1. [时代峰峻否认王橹杰私联](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E5%90%A6%E8%AE%A4%E7%8E%8B%E6%A9%B9%E6%9D%B0%E7%A7%81%E8%81%94%23) `194.7K 🔥`
1. [台湾女孩疑在日本街头被恶意撞倒](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E5%A5%B3%E5%AD%A9%E7%96%91%E5%9C%A8%E6%97%A5%E6%9C%AC%E8%A1%97%E5%A4%B4%E8%A2%AB%E6%81%B6%E6%84%8F%E6%92%9E%E5%80%92%23) `194.3K 🔥`
1. [王骁生理性演技 (Wang Xiao's physiological acting skills)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%AA%81%E7%94%9F%E7%90%86%E6%80%A7%E6%BC%94%E6%8A%80%23) `194.2K 🔥`
1. [周杰伦结婚田馥甄有了讽刺的情书](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E7%BB%93%E5%A9%9A%E7%94%B0%E9%A6%A5%E7%94%84%E6%9C%89%E4%BA%86%E8%AE%BD%E5%88%BA%E7%9A%84%E6%83%85%E4%B9%A6%23) `193.4K 🔥`
1. [杨幂柳智敏Prada撞衫](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9F%B3%E6%99%BA%E6%95%8FPrada%E6%92%9E%E8%A1%AB%23) `163.6K 🔥`
1. [向华强拒绝和向佑见面](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%8D%8E%E5%BC%BA%E6%8B%92%E7%BB%9D%E5%92%8C%E5%90%91%E4%BD%91%E8%A7%81%E9%9D%A2%23) `155.3K 🔥`
1. [中国手机行业将迎来全面涨价 (China’s mobile phone industry will usher in comprehensive price increases)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%89%8B%E6%9C%BA%E8%A1%8C%E4%B8%9A%E5%B0%86%E8%BF%8E%E6%9D%A5%E5%85%A8%E9%9D%A2%E6%B6%A8%E4%BB%B7%23) `195.1K 🔥` `-49%`
1. [考研成绩 (Postgraduate entrance examination results)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E6%88%90%E7%BB%A9%23) `193.9K 🔥` `-82%`
1. [肖秀荣怒斥假消息影响考生心态](https://s.weibo.com/weibo?q=%23%E8%82%96%E7%A7%80%E8%8D%A3%E6%80%92%E6%96%A5%E5%81%87%E6%B6%88%E6%81%AF%E5%BD%B1%E5%93%8D%E8%80%83%E7%94%9F%E5%BF%83%E6%80%81%23) `128.0K 🔥` `-50%`
1. [男子坐顺风车排泄后失联](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%9D%90%E9%A1%BA%E9%A3%8E%E8%BD%A6%E6%8E%92%E6%B3%84%E5%90%8E%E5%A4%B1%E8%81%94%23) `119.2K 🔥` `-26%`
1. [中方投下弃权票是最大的担当](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E6%8A%95%E4%B8%8B%E5%BC%83%E6%9D%83%E7%A5%A8%E6%98%AF%E6%9C%80%E5%A4%A7%E7%9A%84%E6%8B%85%E5%BD%93%23) `115.7K 🔥` `-48%`
1. [谷爱凌再次闪耀米兰时装周](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%86%8D%E6%AC%A1%E9%97%AA%E8%80%80%E7%B1%B3%E5%85%B0%E6%97%B6%E8%A3%85%E5%91%A8%23) `110.5K 🔥` `-36%`
1. [俄罗斯](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%23) `93.4K 🔥` `-53%`

Updated at 2026-02-26 13:09:51

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
