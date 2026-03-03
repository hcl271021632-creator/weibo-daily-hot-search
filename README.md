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

1. [周柯宇又要用礼物狙击谁 (Who is Zhou Keyu going to snipe with gifts?)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9F%AF%E5%AE%87%E5%8F%88%E8%A6%81%E7%94%A8%E7%A4%BC%E7%89%A9%E7%8B%99%E5%87%BB%E8%B0%81%23) `509.2K 🔥` `NEW`
1. [iPhone17只用一个月橙色变粉色](https://s.weibo.com/weibo?q=%23iPhone17%E5%8F%AA%E7%94%A8%E4%B8%80%E4%B8%AA%E6%9C%88%E6%A9%99%E8%89%B2%E5%8F%98%E7%B2%89%E8%89%B2%23) `432.2K 🔥` `NEW`
1. [AI先锋天团亮相MWC](https://s.weibo.com/weibo?q=%23AI%E5%85%88%E9%94%8B%E5%A4%A9%E5%9B%A2%E4%BA%AE%E7%9B%B8MWC%23) `362.7K 🔥` `NEW`
1. [地铁上最夯的位置](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E9%93%81%E4%B8%8A%E6%9C%80%E5%A4%AF%E7%9A%84%E4%BD%8D%E7%BD%AE%23) `201.9K 🔥` `NEW`
1. [胡彦斌只一味吃汤圆](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%BD%A6%E6%96%8C%E5%8F%AA%E4%B8%80%E5%91%B3%E5%90%83%E6%B1%A4%E5%9C%86%23) `201.9K 🔥` `NEW`
1. [无情报证明伊朗计划先袭击美军](https://s.weibo.com/weibo?q=%23%E6%97%A0%E6%83%85%E6%8A%A5%E8%AF%81%E6%98%8E%E4%BC%8A%E6%9C%97%E8%AE%A1%E5%88%92%E5%85%88%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%23) `201.9K 🔥` `NEW`
1. [朴信惠被曝涉嫌逃税](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E4%BF%A1%E6%83%A0%E8%A2%AB%E6%9B%9D%E6%B6%89%E5%AB%8C%E9%80%83%E7%A8%8E%23) `201.7K 🔥` `NEW`
1. [人大代表关注农村大龄青年结婚难](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E5%85%B3%E6%B3%A8%E5%86%9C%E6%9D%91%E5%A4%A7%E9%BE%84%E9%9D%92%E5%B9%B4%E7%BB%93%E5%A9%9A%E9%9A%BE%23) `201.4K 🔥` `NEW`
1. [孟子义李昀锐跳overdrive](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E8%B7%B3overdrive%23) `201.4K 🔥` `NEW`
1. [台湾热议台胞证能救命](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E7%83%AD%E8%AE%AE%E5%8F%B0%E8%83%9E%E8%AF%81%E8%83%BD%E6%95%91%E5%91%BD%23) `201.1K 🔥` `NEW`
1. [建议加强落实双休制度 (It is recommended to strengthen the implementation of the weekend system)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%8A%A0%E5%BC%BA%E8%90%BD%E5%AE%9E%E5%8F%8C%E4%BC%91%E5%88%B6%E5%BA%A6%23) `200.9K 🔥` `NEW`
1. [不足5%的女性能在晚10点前入睡](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%B6%B35%25%E7%9A%84%E5%A5%B3%E6%80%A7%E8%83%BD%E5%9C%A8%E6%99%9A10%E7%82%B9%E5%89%8D%E5%85%A5%E7%9D%A1%23) `200.8K 🔥` `NEW`
1. [自己一个人打麻将](https://s.weibo.com/weibo?q=%23%E8%87%AA%E5%B7%B1%E4%B8%80%E4%B8%AA%E4%BA%BA%E6%89%93%E9%BA%BB%E5%B0%86%23) `200.7K 🔥` `NEW`
1. [张凌赫曾经在我的雅思机构当助教](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%9B%BE%E7%BB%8F%E5%9C%A8%E6%88%91%E7%9A%84%E9%9B%85%E6%80%9D%E6%9C%BA%E6%9E%84%E5%BD%93%E5%8A%A9%E6%95%99%23) `200.6K 🔥` `NEW`
1. [小狗有种英式老管家的从容感](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E6%9C%89%E7%A7%8D%E8%8B%B1%E5%BC%8F%E8%80%81%E7%AE%A1%E5%AE%B6%E7%9A%84%E4%BB%8E%E5%AE%B9%E6%84%9F%23) `200.5K 🔥` `NEW`
1. [齐司礼新卡](https://s.weibo.com/weibo?q=%23%E9%BD%90%E5%8F%B8%E7%A4%BC%E6%96%B0%E5%8D%A1%23) `200.4K 🔥` `NEW`
1. [赵丽颖工作室灯谜](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E5%B7%A5%E4%BD%9C%E5%AE%A4%E7%81%AF%E8%B0%9C%23) `200.3K 🔥` `NEW`
1. [在摸狗的时候突然停下](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E6%91%B8%E7%8B%97%E7%9A%84%E6%97%B6%E5%80%99%E7%AA%81%E7%84%B6%E5%81%9C%E4%B8%8B%23) `200.2K 🔥` `NEW`
1. [周柯宇霸总男大秒切换](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9F%AF%E5%AE%87%E9%9C%B8%E6%80%BB%E7%94%B7%E5%A4%A7%E7%A7%92%E5%88%87%E6%8D%A2%23) `200.2K 🔥` `NEW`
1. [油价调整](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E8%B0%83%E6%95%B4%23) `821.1K 🔥` `+142%`
1. [伊朗发布袭击美军基地画面 (Iran releases footage of attack on US military base)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E5%B8%83%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%E7%94%BB%E9%9D%A2%23) `481.3K 🔥` `+42%`
1. [越来越多国家被卷入中东冲突](https://s.weibo.com/weibo?q=%23%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%A4%9A%E5%9B%BD%E5%AE%B6%E8%A2%AB%E5%8D%B7%E5%85%A5%E4%B8%AD%E4%B8%9C%E5%86%B2%E7%AA%81%23) `1.1M 🔥`
1. [多方回应女子去世后被嫁弟弟](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%96%B9%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%AD%90%E5%8E%BB%E4%B8%96%E5%90%8E%E8%A2%AB%E5%AB%81%E5%BC%9F%E5%BC%9F%23) `287.4K 🔥`
1. [谢娜喊话薛之谦 (Xie Na shouts to Joker Xue)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E5%96%8A%E8%AF%9D%E8%96%9B%E4%B9%8B%E8%B0%A6%23) `8.2M 🔥` `-25%`
1. [90秒看懂全国两会重要知识点](https://s.weibo.com/weibo?q=%2390%E7%A7%92%E7%9C%8B%E6%87%82%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%E9%87%8D%E8%A6%81%E7%9F%A5%E8%AF%86%E7%82%B9%23) `628.3K 🔥` `-21%`
1. [刘文祥麻辣烫暂停新合作](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E6%9A%82%E5%81%9C%E6%96%B0%E5%90%88%E4%BD%9C%23) `471.0K 🔥` `-41%`
1. [男子下高速显示费用8万多震惊收费员](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E4%B8%8B%E9%AB%98%E9%80%9F%E6%98%BE%E7%A4%BA%E8%B4%B9%E7%94%A88%E4%B8%87%E5%A4%9A%E9%9C%87%E6%83%8A%E6%94%B6%E8%B4%B9%E5%91%98%23) `252.3K 🔥` `-29%`
1. [种地吧4开工直播 (Farming Bar 4 starts live broadcast)](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A74%E5%BC%80%E5%B7%A5%E7%9B%B4%E6%92%AD%23) `232.8K 🔥` `-71%`
1. [倪萍怒怼李诚儒](https://s.weibo.com/weibo?q=%23%E5%80%AA%E8%90%8D%E6%80%92%E6%80%BC%E6%9D%8E%E8%AF%9A%E5%84%92%23) `208.0K 🔥` `-39%`
1. [郑恺回村也不能撕baby](https://s.weibo.com/weibo?q=%23%E9%83%91%E6%81%BA%E5%9B%9E%E6%9D%91%E4%B9%9F%E4%B8%8D%E8%83%BD%E6%92%95baby%23) `201.9K 🔥` `-40%`
1. [杨幂说自己有老人味](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%AF%B4%E8%87%AA%E5%B7%B1%E6%9C%89%E8%80%81%E4%BA%BA%E5%91%B3%23) `201.8K 🔥` `-40%`
1. [红果停了很多项目](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E6%9E%9C%E5%81%9C%E4%BA%86%E5%BE%88%E5%A4%9A%E9%A1%B9%E7%9B%AE%23) `201.8K 🔥` `-52%`
1. [苏炳添QQ意外曝光 (Su Bingtian QQ accidentally exposed)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%82%B3%E6%B7%BBQQ%E6%84%8F%E5%A4%96%E6%9B%9D%E5%85%89%23) `201.7K 🔥` `-41%`
1. [谭松韵董晴 真闺蜜二搭 (Tan Songyun and Dong Qing, the second pair of true besties)](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E8%91%A3%E6%99%B4%20%E7%9C%9F%E9%97%BA%E8%9C%9C%E4%BA%8C%E6%90%AD%23) `201.6K 🔥` `-41%`
1. [元宵节 (Lantern Festival)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E8%8A%82%23) `201.6K 🔥` `-41%`
1. [伊朗发起第13轮攻击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC13%E8%BD%AE%E6%94%BB%E5%87%BB%23) `201.5K 🔥` `-50%`
1. [有人考公雇人大量虚假报名吓走对手](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%BA%BA%E8%80%83%E5%85%AC%E9%9B%87%E4%BA%BA%E5%A4%A7%E9%87%8F%E8%99%9A%E5%81%87%E6%8A%A5%E5%90%8D%E5%90%93%E8%B5%B0%E5%AF%B9%E6%89%8B%23) `201.4K 🔥` `-41%`
1. [中方强烈谴责一切攻击儿童行为](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%BC%BA%E7%83%88%E8%B0%B4%E8%B4%A3%E4%B8%80%E5%88%87%E6%94%BB%E5%87%BB%E5%84%BF%E7%AB%A5%E8%A1%8C%E4%B8%BA%23) `201.3K 🔥` `-41%`
1. [戒糖加跳绳5个月威力有多大 (How powerful is quitting sugar and skipping rope for 5 months?)](https://s.weibo.com/weibo?q=%23%E6%88%92%E7%B3%96%E5%8A%A0%E8%B7%B3%E7%BB%B35%E4%B8%AA%E6%9C%88%E5%A8%81%E5%8A%9B%E6%9C%89%E5%A4%9A%E5%A4%A7%23) `201.3K 🔥` `-41%`
1. [光与夜之恋 (Love of light and night)](https://s.weibo.com/weibo?q=%23%E5%85%89%E4%B8%8E%E5%A4%9C%E4%B9%8B%E6%81%8B%23) `201.2K 🔥` `-41%`
1. [Angelababy生图有多权威](https://s.weibo.com/weibo?q=%23Angelababy%E7%94%9F%E5%9B%BE%E6%9C%89%E5%A4%9A%E6%9D%83%E5%A8%81%23) `201.2K 🔥` `-41%`
1. [凤凰传奇抢票](https://s.weibo.com/weibo?q=%23%E5%87%A4%E5%87%B0%E4%BC%A0%E5%A5%87%E6%8A%A2%E7%A5%A8%23) `201.1K 🔥` `-41%`
1. [小猫竟然真会用给它缝的枕头](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E7%AB%9F%E7%84%B6%E7%9C%9F%E4%BC%9A%E7%94%A8%E7%BB%99%E5%AE%83%E7%BC%9D%E7%9A%84%E6%9E%95%E5%A4%B4%23) `201.0K 🔥` `-41%`
1. [不要和扫兴的人一起去吃自助餐](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%A6%81%E5%92%8C%E6%89%AB%E5%85%B4%E7%9A%84%E4%BA%BA%E4%B8%80%E8%B5%B7%E5%8E%BB%E5%90%83%E8%87%AA%E5%8A%A9%E9%A4%90%23) `201.0K 🔥` `-41%`
1. [带火刘文祥的紫薯精30天涨粉421万](https://s.weibo.com/weibo?q=%23%E5%B8%A6%E7%81%AB%E5%88%98%E6%96%87%E7%A5%A5%E7%9A%84%E7%B4%AB%E8%96%AF%E7%B2%BE30%E5%A4%A9%E6%B6%A8%E7%B2%89421%E4%B8%87%23) `201.0K 🔥` `-41%`
1. [汤圆](https://s.weibo.com/weibo?q=%23%E6%B1%A4%E5%9C%86%23) `200.9K 🔥` `-41%`
1. [白日提灯 (day lantern)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `200.7K 🔥` `-41%`
1. [A股 (A shares)](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `200.7K 🔥` `-41%`
1. [迪丽热巴陈飞宇元宵营业](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%99%88%E9%A3%9E%E5%AE%87%E5%85%83%E5%AE%B5%E8%90%A5%E4%B8%9A%23) `200.6K 🔥` `-41%`
1. [种地吧 (Farm it)](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `200.4K 🔥` `-41%`
1. [檀健次卢昱晓双人cha](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%E5%8D%A2%E6%98%B1%E6%99%93%E5%8F%8C%E4%BA%BAcha%23) `200.3K 🔥` `-41%`

Updated at 2026-03-03 13:38:24

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
