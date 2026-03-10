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

1. [李羲承退队 (Li Xicheng quits the team)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BE%B2%E6%89%BF%E9%80%80%E9%98%9F%23) `14.8M 🔥` `NEW`
1. [手机集体涨价原因](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E9%9B%86%E4%BD%93%E6%B6%A8%E4%BB%B7%E5%8E%9F%E5%9B%A0%23) `468.1K 🔥` `NEW`
1. [伊朗提出停火条件](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8F%90%E5%87%BA%E5%81%9C%E7%81%AB%E6%9D%A1%E4%BB%B6%23) `425.9K 🔥` `NEW`
1. [长宁是未来皇后](https://s.weibo.com/weibo?q=%23%E9%95%BF%E5%AE%81%E6%98%AF%E6%9C%AA%E6%9D%A5%E7%9A%87%E5%90%8E%23) `418.5K 🔥` `NEW`
1. [汪苏泷新专辑明日世界](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E6%96%B0%E4%B8%93%E8%BE%91%E6%98%8E%E6%97%A5%E4%B8%96%E7%95%8C%23) `414.5K 🔥` `NEW`
1. [黄金不再保值了吗](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E4%B8%8D%E5%86%8D%E4%BF%9D%E5%80%BC%E4%BA%86%E5%90%97%23) `410.6K 🔥` `NEW`
1. [给男朋友用特效化妆](https://s.weibo.com/weibo?q=%23%E7%BB%99%E7%94%B7%E6%9C%8B%E5%8F%8B%E7%94%A8%E7%89%B9%E6%95%88%E5%8C%96%E5%A6%86%23) `403.1K 🔥` `NEW`
1. [JYP从JYP辞职了](https://s.weibo.com/weibo?q=%23JYP%E4%BB%8EJYP%E8%BE%9E%E8%81%8C%E4%BA%86%23) `401.6K 🔥` `NEW`
1. [ZB1解散](https://s.weibo.com/weibo?q=%23ZB1%E8%A7%A3%E6%95%A3%23) `400.6K 🔥` `NEW`
1. [50岁大姐睡觉时粉碎性骨折](https://s.weibo.com/weibo?q=%2350%E5%B2%81%E5%A4%A7%E5%A7%90%E7%9D%A1%E8%A7%89%E6%97%B6%E7%B2%89%E7%A2%8E%E6%80%A7%E9%AA%A8%E6%8A%98%23) `398.0K 🔥` `NEW`
1. [李羲承 ENHYPEN (Li Xicheng ENHYPEN)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BE%B2%E6%89%BF%20ENHYPEN%23) `396.1K 🔥` `NEW`
1. [150层酥皮连切30多刀雕出松鼠](https://s.weibo.com/weibo?q=%23150%E5%B1%82%E9%85%A5%E7%9A%AE%E8%BF%9E%E5%88%8730%E5%A4%9A%E5%88%80%E9%9B%95%E5%87%BA%E6%9D%BE%E9%BC%A0%23) `394.1K 🔥` `NEW`
1. [七人男团魔咒](https://s.weibo.com/weibo?q=%23%E4%B8%83%E4%BA%BA%E7%94%B7%E5%9B%A2%E9%AD%94%E5%92%92%23) `393.5K 🔥` `NEW`
1. [朴振英 JYP](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E6%8C%AF%E8%8B%B1%20JYP%23) `382.0K 🔥` `NEW`
1. [大藤沙月回应首胜王曼昱](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E8%97%A4%E6%B2%99%E6%9C%88%E5%9B%9E%E5%BA%94%E9%A6%96%E8%83%9C%E7%8E%8B%E6%9B%BC%E6%98%B1%23) `381.8K 🔥` `NEW`
1. [王曼昱爆冷后摇头](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E7%88%86%E5%86%B7%E5%90%8E%E6%91%87%E5%A4%B4%23) `380.3K 🔥` `NEW`
1. [过于强调第一学历歪曲人才评价标准](https://s.weibo.com/weibo?q=%23%E8%BF%87%E4%BA%8E%E5%BC%BA%E8%B0%83%E7%AC%AC%E4%B8%80%E5%AD%A6%E5%8E%86%E6%AD%AA%E6%9B%B2%E4%BA%BA%E6%89%8D%E8%AF%84%E4%BB%B7%E6%A0%87%E5%87%86%23) `379.9K 🔥` `NEW`
1. [ENHYPEN将以六人组活动](https://s.weibo.com/weibo?q=%23ENHYPEN%E5%B0%86%E4%BB%A5%E5%85%AD%E4%BA%BA%E7%BB%84%E6%B4%BB%E5%8A%A8%23) `378.6K 🔥` `NEW`
1. [张钧甯谷爱凌王一博互让C位](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%92%A7%E7%94%AF%E8%B0%B7%E7%88%B1%E5%87%8C%E7%8E%8B%E4%B8%80%E5%8D%9A%E4%BA%92%E8%AE%A9C%E4%BD%8D%23) `378.2K 🔥` `NEW`
1. [逐玉一个担心得要命一个只想亲亲](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%B8%80%E4%B8%AA%E6%8B%85%E5%BF%83%E5%BE%97%E8%A6%81%E5%91%BD%E4%B8%80%E4%B8%AA%E5%8F%AA%E6%83%B3%E4%BA%B2%E4%BA%B2%23) `377.6K 🔥` `NEW`
1. [袁惟仁丧葬费用均由圈内好友支付 (Yuan Weiren’s funeral expenses were paid by friends in the circle)](https://s.weibo.com/weibo?q=%23%E8%A2%81%E6%83%9F%E4%BB%81%E4%B8%A7%E8%91%AC%E8%B4%B9%E7%94%A8%E5%9D%87%E7%94%B1%E5%9C%88%E5%86%85%E5%A5%BD%E5%8F%8B%E6%94%AF%E4%BB%98%23) `376.6K 🔥` `NEW`
1. [我国约2.2亿人听力有问题](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E7%BA%A62.2%E4%BA%BF%E4%BA%BA%E5%90%AC%E5%8A%9B%E6%9C%89%E9%97%AE%E9%A2%98%23) `374.7K 🔥` `NEW`
1. [国家开始挂念你的腰围了](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%AE%B6%E5%BC%80%E5%A7%8B%E6%8C%82%E5%BF%B5%E4%BD%A0%E7%9A%84%E8%85%B0%E5%9B%B4%E4%BA%86%23) `372.4K 🔥` `NEW`
1. [6G网要来了 (6G network is coming)](https://s.weibo.com/weibo?q=%236G%E7%BD%91%E8%A6%81%E6%9D%A5%E4%BA%86%23) `1.0M 🔥` `+35%`
1. [建议小学三年级前课间半小时 (It is recommended that half an hour be allowed in the recess before the third grade of primary school)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%8F%E5%AD%A6%E4%B8%89%E5%B9%B4%E7%BA%A7%E5%89%8D%E8%AF%BE%E9%97%B4%E5%8D%8A%E5%B0%8F%E6%97%B6%23) `716.6K 🔥` `+51%`
1. [德黑兰降黑雨](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E9%BB%91%E5%85%B0%E9%99%8D%E9%BB%91%E9%9B%A8%23) `470.7K 🔥` `+38%`
1. [董晴一部一个有效出演](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%99%B4%E4%B8%80%E9%83%A8%E4%B8%80%E4%B8%AA%E6%9C%89%E6%95%88%E5%87%BA%E6%BC%94%23) `461.5K 🔥` `+35%`
1. [生命树](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%23) `447.1K 🔥` `+31%`
1. [香蕉有可能会灭绝](https://s.weibo.com/weibo?q=%23%E9%A6%99%E8%95%89%E6%9C%89%E5%8F%AF%E8%83%BD%E4%BC%9A%E7%81%AD%E7%BB%9D%23) `424.5K 🔥` `+24%`
1. [中传回应砍掉16个专业](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BC%A0%E5%9B%9E%E5%BA%94%E7%A0%8D%E6%8E%8916%E4%B8%AA%E4%B8%93%E4%B8%9A%23) `422.2K 🔥` `+23%`
1. [两会声音传递法治力度民生温度 (The voices of the two sessions convey the strength of the rule of law and the warmth of people’s livelihood)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%E5%A3%B0%E9%9F%B3%E4%BC%A0%E9%80%92%E6%B3%95%E6%B2%BB%E5%8A%9B%E5%BA%A6%E6%B0%91%E7%94%9F%E6%B8%A9%E5%BA%A6%23) `592.6K 🔥`
1. [王曼昱0比3大藤沙月](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B10%E6%AF%943%E5%A4%A7%E8%97%A4%E6%B2%99%E6%9C%88%23) `483.2K 🔥`
1. [王曼昱爆冷](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E7%88%86%E5%86%B7%23) `474.7K 🔥`
1. [张凌赫赛车风OOTD (Zhang Linghe racing style OOTD)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%B5%9B%E8%BD%A6%E9%A3%8EOOTD%23) `470.3K 🔥`
1. [制造业升级的超级红包来了](https://s.weibo.com/weibo?q=%23%E5%88%B6%E9%80%A0%E4%B8%9A%E5%8D%87%E7%BA%A7%E7%9A%84%E8%B6%85%E7%BA%A7%E7%BA%A2%E5%8C%85%E6%9D%A5%E4%BA%86%23) `457.8K 🔥`
1. [美国开始甩锅了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%BC%80%E5%A7%8B%E7%94%A9%E9%94%85%E4%BA%86%23) `439.7K 🔥`
1. [张凌赫回应天涯四美已合作两美](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%9B%9E%E5%BA%94%E5%A4%A9%E6%B6%AF%E5%9B%9B%E7%BE%8E%E5%B7%B2%E5%90%88%E4%BD%9C%E4%B8%A4%E7%BE%8E%23) `439.3K 🔥`
1. [姑姑你明天没法上学了](https://s.weibo.com/weibo?q=%23%E5%A7%91%E5%A7%91%E4%BD%A0%E6%98%8E%E5%A4%A9%E6%B2%A1%E6%B3%95%E4%B8%8A%E5%AD%A6%E4%BA%86%23) `420.6K 🔥`
1. [美军急调韩国萨德系统部署中东](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E6%80%A5%E8%B0%83%E9%9F%A9%E5%9B%BD%E8%90%A8%E5%BE%B7%E7%B3%BB%E7%BB%9F%E9%83%A8%E7%BD%B2%E4%B8%AD%E4%B8%9C%23) `415.6K 🔥`
1. [OPPO涨价](https://s.weibo.com/weibo?q=%23OPPO%E6%B6%A8%E4%BB%B7%23) `405.4K 🔥`
1. [白日提灯](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `381.1K 🔥`
1. [Ella送别袁惟仁哭到抽搐](https://s.weibo.com/weibo?q=%23Ella%E9%80%81%E5%88%AB%E8%A2%81%E6%83%9F%E4%BB%81%E5%93%AD%E5%88%B0%E6%8A%BD%E6%90%90%23) `379.2K 🔥`
1. [终于有人把化橘红说清楚了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%8A%8A%E5%8C%96%E6%A9%98%E7%BA%A2%E8%AF%B4%E6%B8%85%E6%A5%9A%E4%BA%86%23) `377.4K 🔥`
1. [张凌赫像是在横店待疯了 (Zhang Linghe seems to have gone crazy staying in Hengdian)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%83%8F%E6%98%AF%E5%9C%A8%E6%A8%AA%E5%BA%97%E5%BE%85%E7%96%AF%E4%BA%86%23) `375.2K 🔥`
1. [青3创4门面同框今夕是何年](https://s.weibo.com/weibo?q=%23%E9%9D%923%E5%88%9B4%E9%97%A8%E9%9D%A2%E5%90%8C%E6%A1%86%E4%BB%8A%E5%A4%95%E6%98%AF%E4%BD%95%E5%B9%B4%23) `374.2K 🔥`
1. [手机市场将迎来全面涨价 (The mobile phone market will usher in comprehensive price increases)](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E5%B8%82%E5%9C%BA%E5%B0%86%E8%BF%8E%E6%9D%A5%E5%85%A8%E9%9D%A2%E6%B6%A8%E4%BB%B7%23) `373.6K 🔥`
1. [田嘉瑞大男主](https://s.weibo.com/weibo?q=%23%E7%94%B0%E5%98%89%E7%91%9E%E5%A4%A7%E7%94%B7%E4%B8%BB%23) `372.9K 🔥`
1. [经纪公司否认张娜拉去世](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E7%BA%AA%E5%85%AC%E5%8F%B8%E5%90%A6%E8%AE%A4%E5%BC%A0%E5%A8%9C%E6%8B%89%E5%8E%BB%E4%B8%96%23) `372.3K 🔥`
1. [代表说儿子告诉他千万不要爹味太浓](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%84%BF%E5%AD%90%E5%91%8A%E8%AF%89%E4%BB%96%E5%8D%83%E4%B8%87%E4%B8%8D%E8%A6%81%E7%88%B9%E5%91%B3%E5%A4%AA%E6%B5%93%23) `407.4K 🔥` `-61%`
1. [2026白玉兰预测 (2026 Magnolia Forecast)](https://s.weibo.com/weibo?q=%232026%E7%99%BD%E7%8E%89%E5%85%B0%E9%A2%84%E6%B5%8B%23) `375.9K 🔥` `-21%`

Updated at 2026-03-10 15:53:21

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
