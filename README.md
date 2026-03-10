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

1. [张凌赫道歉 (Zhang Linghe apologizes)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E9%81%93%E6%AD%89%23) `8.5M 🔥` `NEW`
1. [中国两会将为全球创造更多机遇](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E5%B0%86%E4%B8%BA%E5%85%A8%E7%90%83%E5%88%9B%E9%80%A0%E6%9B%B4%E5%A4%9A%E6%9C%BA%E9%81%87%23) `598.8K 🔥` `NEW`
1. [MiuMiu巴黎时装秀](https://s.weibo.com/weibo?q=%23MiuMiu%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E7%A7%80%23) `597.5K 🔥` `NEW`
1. [中国队金牌榜奖牌榜都是第一](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E9%87%91%E7%89%8C%E6%A6%9C%E5%A5%96%E7%89%8C%E6%A6%9C%E9%83%BD%E6%98%AF%E7%AC%AC%E4%B8%80%23) `597.0K 🔥` `NEW`
1. [建议向新婚夫妇发放住房补贴](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%90%91%E6%96%B0%E5%A9%9A%E5%A4%AB%E5%A6%87%E5%8F%91%E6%94%BE%E4%BD%8F%E6%88%BF%E8%A1%A5%E8%B4%B4%23) `596.2K 🔥` `NEW`
1. [张凌赫赛车风OOTD](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%B5%9B%E8%BD%A6%E9%A3%8EOOTD%23) `593.4K 🔥` `NEW`
1. [国家互联网应急中心提示龙虾风险](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%AE%B6%E4%BA%92%E8%81%94%E7%BD%91%E5%BA%94%E6%80%A5%E4%B8%AD%E5%BF%83%E6%8F%90%E7%A4%BA%E9%BE%99%E8%99%BE%E9%A3%8E%E9%99%A9%23) `588.6K 🔥` `NEW`
1. [外媒记者期待与中国共享发展新机遇](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%AA%92%E8%AE%B0%E8%80%85%E6%9C%9F%E5%BE%85%E4%B8%8E%E4%B8%AD%E5%9B%BD%E5%85%B1%E4%BA%AB%E5%8F%91%E5%B1%95%E6%96%B0%E6%9C%BA%E9%81%87%23) `585.8K 🔥` `NEW`
1. [安全养龙虾要注意这6点](https://s.weibo.com/weibo?q=%23%E5%AE%89%E5%85%A8%E5%85%BB%E9%BE%99%E8%99%BE%E8%A6%81%E6%B3%A8%E6%84%8F%E8%BF%996%E7%82%B9%23) `583.5K 🔥` `NEW`
1. [逐玉 女主职业自卑](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%A5%B3%E4%B8%BB%E8%81%8C%E4%B8%9A%E8%87%AA%E5%8D%91%23) `579.7K 🔥` `NEW`
1. [第一批养虾人已经开始卸载了 (The first batch of shrimp farmers have begun to unload)](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%89%B9%E5%85%BB%E8%99%BE%E4%BA%BA%E5%B7%B2%E7%BB%8F%E5%BC%80%E5%A7%8B%E5%8D%B8%E8%BD%BD%E4%BA%86%23) `577.1K 🔥` `NEW`
1. [逐玉云合](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%91%E5%90%88%23) `571.0K 🔥` `NEW`
1. [把果蝇的大脑复制到电脑](https://s.weibo.com/weibo?q=%23%E6%8A%8A%E6%9E%9C%E8%9D%87%E7%9A%84%E5%A4%A7%E8%84%91%E5%A4%8D%E5%88%B6%E5%88%B0%E7%94%B5%E8%84%91%23) `568.1K 🔥` `NEW`
1. [荣耀MagicV6太能整活了](https://s.weibo.com/weibo?q=%23%E8%8D%A3%E8%80%80MagicV6%E5%A4%AA%E8%83%BD%E6%95%B4%E6%B4%BB%E4%BA%86%23) `565.3K 🔥` `NEW`
1. [镖人 惠英红挟持戏份删减](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E6%83%A0%E8%8B%B1%E7%BA%A2%E6%8C%9F%E6%8C%81%E6%88%8F%E4%BB%BD%E5%88%A0%E5%87%8F%23) `562.9K 🔥` `NEW`
1. [LV秋冬女装秀](https://s.weibo.com/weibo?q=%23LV%E7%A7%8B%E5%86%AC%E5%A5%B3%E8%A3%85%E7%A7%80%23) `553.6K 🔥` `NEW`
1. [代表称农民工怕社保断缴白花钱](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E7%A7%B0%E5%86%9C%E6%B0%91%E5%B7%A5%E6%80%95%E7%A4%BE%E4%BF%9D%E6%96%AD%E7%BC%B4%E7%99%BD%E8%8A%B1%E9%92%B1%23) `549.0K 🔥` `NEW`
1. [中朝国际旅客列车将双向开行](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%9C%9D%E5%9B%BD%E9%99%85%E6%97%85%E5%AE%A2%E5%88%97%E8%BD%A6%E5%B0%86%E5%8F%8C%E5%90%91%E5%BC%80%E8%A1%8C%23) `546.6K 🔥` `NEW`
1. [突然一下就不焦虑了](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E4%B8%80%E4%B8%8B%E5%B0%B1%E4%B8%8D%E7%84%A6%E8%99%91%E4%BA%86%23) `531.2K 🔥` `NEW`
1. [原来厉害的人面试这么溜啊](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%8E%89%E5%AE%B3%E7%9A%84%E4%BA%BA%E9%9D%A2%E8%AF%95%E8%BF%99%E4%B9%88%E6%BA%9C%E5%95%8A%23) `524.9K 🔥` `NEW`
1. [原来这些爆火的文案都是王源写的 (It turns out that these popular copywritings were all written by Wang Yuan)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E4%BA%9B%E7%88%86%E7%81%AB%E7%9A%84%E6%96%87%E6%A1%88%E9%83%BD%E6%98%AF%E7%8E%8B%E6%BA%90%E5%86%99%E7%9A%84%23) `521.7K 🔥` `NEW`
1. [鹿晗喝霸王茶姬](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E5%96%9D%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%23) `519.4K 🔥` `NEW`
1. [林高远也加入网球大军](https://s.weibo.com/weibo?q=%23%E6%9E%97%E9%AB%98%E8%BF%9C%E4%B9%9F%E5%8A%A0%E5%85%A5%E7%BD%91%E7%90%83%E5%A4%A7%E5%86%9B%23) `517.3K 🔥` `NEW`
1. [起底团油直播间加油券套路](https://s.weibo.com/weibo?q=%23%E8%B5%B7%E5%BA%95%E5%9B%A2%E6%B2%B9%E7%9B%B4%E6%92%AD%E9%97%B4%E5%8A%A0%E6%B2%B9%E5%88%B8%E5%A5%97%E8%B7%AF%23) `515.9K 🔥` `NEW`
1. [伊朗驻华大使谈霍尔木兹海峡通行](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A9%BB%E5%8D%8E%E5%A4%A7%E4%BD%BF%E8%B0%88%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E9%80%9A%E8%A1%8C%23) `508.8K 🔥` `NEW`
1. [杨紫周翊然活动同台](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E5%91%A8%E7%BF%8A%E7%84%B6%E6%B4%BB%E5%8A%A8%E5%90%8C%E5%8F%B0%23) `505.0K 🔥` `NEW`
1. [blackpink的周冠宇](https://s.weibo.com/weibo?q=%23blackpink%E7%9A%84%E5%91%A8%E5%86%A0%E5%AE%87%23) `504.0K 🔥` `NEW`
1. [村民20元买彩票中100万](https://s.weibo.com/weibo?q=%23%E6%9D%91%E6%B0%9120%E5%85%83%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD100%E4%B8%87%23) `502.1K 🔥` `NEW`
1. [22个月大宝宝在院子里慵懒躺倒晒太阳](https://s.weibo.com/weibo?q=%2322%E4%B8%AA%E6%9C%88%E5%A4%A7%E5%AE%9D%E5%AE%9D%E5%9C%A8%E9%99%A2%E5%AD%90%E9%87%8C%E6%85%B5%E6%87%92%E8%BA%BA%E5%80%92%E6%99%92%E5%A4%AA%E9%98%B3%23) `499.5K 🔥` `NEW`
1. [孔雪儿演技](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E6%BC%94%E6%8A%80%23) `496.4K 🔥` `NEW`
1. [国乒人才梯队建设怎么样 (How about the construction of the national table tennis talent echelon?)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%B9%92%E4%BA%BA%E6%89%8D%E6%A2%AF%E9%98%9F%E5%BB%BA%E8%AE%BE%E6%80%8E%E4%B9%88%E6%A0%B7%23) `484.9K 🔥` `NEW`
1. [2026年安排国防支出1.94万亿元](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E5%AE%89%E6%8E%92%E5%9B%BD%E9%98%B2%E6%94%AF%E5%87%BA1.94%E4%B8%87%E4%BA%BF%E5%85%83%23) `1.0M 🔥`
1. [宋平同志遗体在京火化 (Comrade Song Ping's body was cremated in Beijing)](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%B9%B3%E5%90%8C%E5%BF%97%E9%81%97%E4%BD%93%E5%9C%A8%E4%BA%AC%E7%81%AB%E5%8C%96%23) `719.1K 🔥`
1. [福建舰入列就形成了战斗力](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%BB%BA%E8%88%B0%E5%85%A5%E5%88%97%E5%B0%B1%E5%BD%A2%E6%88%90%E4%BA%86%E6%88%98%E6%96%97%E5%8A%9B%23) `593.8K 🔥`
1. [52条中日航线2月取消全部航班 (All 52 China-Japan routes canceled flights in February)](https://s.weibo.com/weibo?q=%2352%E6%9D%A1%E4%B8%AD%E6%97%A5%E8%88%AA%E7%BA%BF2%E6%9C%88%E5%8F%96%E6%B6%88%E5%85%A8%E9%83%A8%E8%88%AA%E7%8F%AD%23) `591.2K 🔥`
1. [伊朗提出停火条件 (Iran proposes ceasefire conditions)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8F%90%E5%87%BA%E5%81%9C%E7%81%AB%E6%9D%A1%E4%BB%B6%23) `581.2K 🔥`
1. [未婚夫去世了该不该赡养对方父母](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E5%A9%9A%E5%A4%AB%E5%8E%BB%E4%B8%96%E4%BA%86%E8%AF%A5%E4%B8%8D%E8%AF%A5%E8%B5%A1%E5%85%BB%E5%AF%B9%E6%96%B9%E7%88%B6%E6%AF%8D%23) `574.1K 🔥`
1. [在医院生个孩子只花了2块5 (Giving birth to a baby in the hospital only cost 2.5 yuan)](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%8C%BB%E9%99%A2%E7%94%9F%E4%B8%AA%E5%AD%A9%E5%AD%90%E5%8F%AA%E8%8A%B1%E4%BA%862%E5%9D%975%23) `566.5K 🔥`
1. [婆婆进卧室不敲门儿媳崩溃哭诉](https://s.weibo.com/weibo?q=%23%E5%A9%86%E5%A9%86%E8%BF%9B%E5%8D%A7%E5%AE%A4%E4%B8%8D%E6%95%B2%E9%97%A8%E5%84%BF%E5%AA%B3%E5%B4%A9%E6%BA%83%E5%93%AD%E8%AF%89%23) `555.1K 🔥`
1. [BeADreamer](https://s.weibo.com/weibo?q=%23BeADreamer%23) `551.1K 🔥`
1. [杨紫紫色高定](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%B4%AB%E8%89%B2%E9%AB%98%E5%AE%9A%23) `544.1K 🔥`
1. [JYP考公上岸了](https://s.weibo.com/weibo?q=%23JYP%E8%80%83%E5%85%AC%E4%B8%8A%E5%B2%B8%E4%BA%86%23) `543.4K 🔥`
1. [中方回应北京至平壤列车恢复运行](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E5%8C%97%E4%BA%AC%E8%87%B3%E5%B9%B3%E5%A3%A4%E5%88%97%E8%BD%A6%E6%81%A2%E5%A4%8D%E8%BF%90%E8%A1%8C%23) `575.8K 🔥` `-21%`
1. [甜茶买了孙颖莎海报](https://s.weibo.com/weibo?q=%23%E7%94%9C%E8%8C%B6%E4%B9%B0%E4%BA%86%E5%AD%99%E9%A2%96%E8%8E%8E%E6%B5%B7%E6%8A%A5%23) `557.4K 🔥` `-21%`
1. [李羲承退队 (Li Xicheng quits the team)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BE%B2%E6%89%BF%E9%80%80%E9%98%9F%23) `527.7K 🔥` `-21%`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `526.6K 🔥` `-21%`
1. [刘亦菲看秀造型](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E7%9C%8B%E7%A7%80%E9%80%A0%E5%9E%8B%23) `511.5K 🔥` `-23%`
1. [倪虹洁走完红毯天塌了](https://s.weibo.com/weibo?q=%23%E5%80%AA%E8%99%B9%E6%B4%81%E8%B5%B0%E5%AE%8C%E7%BA%A2%E6%AF%AF%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `509.1K 🔥` `-23%`
1. [ZB1解散 (ZB1 disbanded)](https://s.weibo.com/weibo?q=%23ZB1%E8%A7%A3%E6%95%A3%23) `494.4K 🔥` `-26%`
1. [黄金不再保值了吗](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E4%B8%8D%E5%86%8D%E4%BF%9D%E5%80%BC%E4%BA%86%E5%90%97%23) `491.8K 🔥` `-27%`
1. [李羲承有点像我离职的lastday](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BE%B2%E6%89%BF%E6%9C%89%E7%82%B9%E5%83%8F%E6%88%91%E7%A6%BB%E8%81%8C%E7%9A%84lastday%23) `488.6K 🔥` `-26%`
1. [JYP从JYP辞职了 (JYP resigned from JYP)](https://s.weibo.com/weibo?q=%23JYP%E4%BB%8EJYP%E8%BE%9E%E8%81%8C%E4%BA%86%23) `486.0K 🔥` `-27%`

Updated at 2026-03-10 21:24:10

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
