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

1. [小米17Ultra徕卡版黑银色开售 (Xiaomi Mi 17 Ultra Leica Edition black and silver now on sale)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B317Ultra%E5%BE%95%E5%8D%A1%E7%89%88%E9%BB%91%E9%93%B6%E8%89%B2%E5%BC%80%E5%94%AE%23) `602.3K 🔥` `NEW`
1. [王曼昱0比3大藤沙月](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B10%E6%AF%943%E5%A4%A7%E8%97%A4%E6%B2%99%E6%9C%88%23) `583.2K 🔥` `NEW`
1. [王曼昱爆冷](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E7%88%86%E5%86%B7%23) `476.1K 🔥` `NEW`
1. [美军急调韩国萨德系统部署中东](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E6%80%A5%E8%B0%83%E9%9F%A9%E5%9B%BD%E8%90%A8%E5%BE%B7%E7%B3%BB%E7%BB%9F%E9%83%A8%E7%BD%B2%E4%B8%AD%E4%B8%9C%23) `475.7K 🔥` `NEW`
1. [张凌赫赛车风OOTD](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%B5%9B%E8%BD%A6%E9%A3%8EOOTD%23) `475.7K 🔥` `NEW`
1. [白日提灯](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `475.3K 🔥` `NEW`
1. [姑姑你明天没法上学了](https://s.weibo.com/weibo?q=%23%E5%A7%91%E5%A7%91%E4%BD%A0%E6%98%8E%E5%A4%A9%E6%B2%A1%E6%B3%95%E4%B8%8A%E5%AD%A6%E4%BA%86%23) `358.9K 🔥` `NEW`
1. [物业到底是来管理还是服务我们的](https://s.weibo.com/weibo?q=%23%E7%89%A9%E4%B8%9A%E5%88%B0%E5%BA%95%E6%98%AF%E6%9D%A5%E7%AE%A1%E7%90%86%E8%BF%98%E6%98%AF%E6%9C%8D%E5%8A%A1%E6%88%91%E4%BB%AC%E7%9A%84%23) `342.5K 🔥` `NEW`
1. [中传回应砍掉16个专业](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BC%A0%E5%9B%9E%E5%BA%94%E7%A0%8D%E6%8E%8916%E4%B8%AA%E4%B8%93%E4%B8%9A%23) `342.3K 🔥` `NEW`
1. [终于有人把化橘红说清楚了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%8A%8A%E5%8C%96%E6%A9%98%E7%BA%A2%E8%AF%B4%E6%B8%85%E6%A5%9A%E4%BA%86%23) `342.0K 🔥` `NEW`
1. [孔雪儿逐玉带球跑 (Kong Xueer Zhuyu runs with the ball)](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E9%80%90%E7%8E%89%E5%B8%A6%E7%90%83%E8%B7%91%23) `341.9K 🔥` `NEW`
1. [王曼昱止步重庆冠军赛首轮](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E6%AD%A2%E6%AD%A5%E9%87%8D%E5%BA%86%E5%86%A0%E5%86%9B%E8%B5%9B%E9%A6%96%E8%BD%AE%23) `341.4K 🔥` `NEW`
1. [德黑兰降黑雨](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E9%BB%91%E5%85%B0%E9%99%8D%E9%BB%91%E9%9B%A8%23) `341.2K 🔥` `NEW`
1. [董晴一部一个有效出演](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%99%B4%E4%B8%80%E9%83%A8%E4%B8%80%E4%B8%AA%E6%9C%89%E6%95%88%E5%87%BA%E6%BC%94%23) `340.9K 🔥` `NEW`
1. [安卓涨价你会考虑买iPhone吗](https://s.weibo.com/weibo?q=%23%E5%AE%89%E5%8D%93%E6%B6%A8%E4%BB%B7%E4%BD%A0%E4%BC%9A%E8%80%83%E8%99%91%E4%B9%B0iPhone%E5%90%97%23) `340.9K 🔥` `NEW`
1. [田嘉瑞大男主](https://s.weibo.com/weibo?q=%23%E7%94%B0%E5%98%89%E7%91%9E%E5%A4%A7%E7%94%B7%E4%B8%BB%23) `340.8K 🔥` `NEW`
1. [董明珠说奋斗不等于要加班](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%98%8E%E7%8F%A0%E8%AF%B4%E5%A5%8B%E6%96%97%E4%B8%8D%E7%AD%89%E4%BA%8E%E8%A6%81%E5%8A%A0%E7%8F%AD%23) `340.7K 🔥` `NEW`
1. [生命树](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%23) `340.3K 🔥` `NEW`
1. [从煎鸡蛋到麻辣香锅](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E7%85%8E%E9%B8%A1%E8%9B%8B%E5%88%B0%E9%BA%BB%E8%BE%A3%E9%A6%99%E9%94%85%23) `340.2K 🔥` `NEW`
1. [韩国人夸起易烊千玺发了狠忘了情](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E4%BA%BA%E5%A4%B8%E8%B5%B7%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%8F%91%E4%BA%86%E7%8B%A0%E5%BF%98%E4%BA%86%E6%83%85%23) `340.1K 🔥` `NEW`
1. [原来这就是小说里的强者气息 (It turns out that this is the aura of the strong man in the novel)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E5%B0%B1%E6%98%AF%E5%B0%8F%E8%AF%B4%E9%87%8C%E7%9A%84%E5%BC%BA%E8%80%85%E6%B0%94%E6%81%AF%23) `340.0K 🔥` `NEW`
1. [王曼昱vs大藤沙月](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1vs%E5%A4%A7%E8%97%A4%E6%B2%99%E6%9C%88%23) `339.9K 🔥` `NEW`
1. [代表说儿子告诉他千万不要爹味太浓](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%84%BF%E5%AD%90%E5%91%8A%E8%AF%89%E4%BB%96%E5%8D%83%E4%B8%87%E4%B8%8D%E8%A6%81%E7%88%B9%E5%91%B3%E5%A4%AA%E6%B5%93%23) `1.0M 🔥` `+32%`
1. [6G网要来了 (6G network is coming)](https://s.weibo.com/weibo?q=%236G%E7%BD%91%E8%A6%81%E6%9D%A5%E4%BA%86%23) `760.5K 🔥` `-27%`
1. [两会声音传递法治力度民生温度 (The voices of the two sessions convey the strength of the rule of law and the warmth of people’s livelihood)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%E5%A3%B0%E9%9F%B3%E4%BC%A0%E9%80%92%E6%B3%95%E6%B2%BB%E5%8A%9B%E5%BA%A6%E6%B0%91%E7%94%9F%E6%B8%A9%E5%BA%A6%23) `607.0K 🔥` `-38%`
1. [2026白玉兰预测 (2026 Magnolia Forecast)](https://s.weibo.com/weibo?q=%232026%E7%99%BD%E7%8E%89%E5%85%B0%E9%A2%84%E6%B5%8B%23) `474.9K 🔥` `-41%`
1. [制造业升级的超级红包来了](https://s.weibo.com/weibo?q=%23%E5%88%B6%E9%80%A0%E4%B8%9A%E5%8D%87%E7%BA%A7%E7%9A%84%E8%B6%85%E7%BA%A7%E7%BA%A2%E5%8C%85%E6%9D%A5%E4%BA%86%23) `474.3K 🔥` `-40%`
1. [建议小学三年级前课间半小时 (It is recommended that half an hour be allowed in the recess before the third grade of primary school)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%8F%E5%AD%A6%E4%B8%89%E5%B9%B4%E7%BA%A7%E5%89%8D%E8%AF%BE%E9%97%B4%E5%8D%8A%E5%B0%8F%E6%97%B6%23) `474.0K 🔥` `-54%`
1. [张凌赫回应天涯四美已合作两美](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%9B%9E%E5%BA%94%E5%A4%A9%E6%B6%AF%E5%9B%9B%E7%BE%8E%E5%B7%B2%E5%90%88%E4%BD%9C%E4%B8%A4%E7%BE%8E%23) `473.2K 🔥` `-40%`
1. [美国开始甩锅了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%BC%80%E5%A7%8B%E7%94%A9%E9%94%85%E4%BA%86%23) `473.0K 🔥` `-40%`
1. [普京提建议后特朗普称很快停火](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E6%8F%90%E5%BB%BA%E8%AE%AE%E5%90%8E%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E5%BE%88%E5%BF%AB%E5%81%9C%E7%81%AB%23) `344.3K 🔥` `-56%`
1. [香蕉有可能会灭绝](https://s.weibo.com/weibo?q=%23%E9%A6%99%E8%95%89%E6%9C%89%E5%8F%AF%E8%83%BD%E4%BC%9A%E7%81%AD%E7%BB%9D%23) `342.7K 🔥` `-57%`
1. [手机市场将迎来全面涨价 (The mobile phone market will usher in comprehensive price increases)](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E5%B8%82%E5%9C%BA%E5%B0%86%E8%BF%8E%E6%9D%A5%E5%85%A8%E9%9D%A2%E6%B6%A8%E4%BB%B7%23) `342.7K 🔥` `-57%`
1. [OPPO涨价](https://s.weibo.com/weibo?q=%23OPPO%E6%B6%A8%E4%BB%B7%23) `342.5K 🔥` `-57%`
1. [Ella送别袁惟仁哭到抽搐](https://s.weibo.com/weibo?q=%23Ella%E9%80%81%E5%88%AB%E8%A2%81%E6%83%9F%E4%BB%81%E5%93%AD%E5%88%B0%E6%8A%BD%E6%90%90%23) `342.3K 🔥` `-57%`
1. [第一次见反向装修的 (This is the first time I’ve seen reverse decoration.)](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%A7%81%E5%8F%8D%E5%90%91%E8%A3%85%E4%BF%AE%E7%9A%84%23) `342.2K 🔥` `-57%`
1. [张凌赫像是在横店待疯了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%83%8F%E6%98%AF%E5%9C%A8%E6%A8%AA%E5%BA%97%E5%BE%85%E7%96%AF%E4%BA%86%23) `342.1K 🔥` `-57%`
1. [青3创4门面同框今夕是何年](https://s.weibo.com/weibo?q=%23%E9%9D%923%E5%88%9B4%E9%97%A8%E9%9D%A2%E5%90%8C%E6%A1%86%E4%BB%8A%E5%A4%95%E6%98%AF%E4%BD%95%E5%B9%B4%23) `341.9K 🔥` `-57%`
1. [美方称不会让印度胜过美国](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E6%96%B9%E7%A7%B0%E4%B8%8D%E4%BC%9A%E8%AE%A9%E5%8D%B0%E5%BA%A6%E8%83%9C%E8%BF%87%E7%BE%8E%E5%9B%BD%23) `341.8K 🔥` `-57%`
1. [一个小朋友学过台阶的视频火了](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%B8%AA%E5%B0%8F%E6%9C%8B%E5%8F%8B%E5%AD%A6%E8%BF%87%E5%8F%B0%E9%98%B6%E7%9A%84%E8%A7%86%E9%A2%91%E7%81%AB%E4%BA%86%23) `341.7K 🔥` `-57%`
1. [经纪公司否认张娜拉去世](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E7%BA%AA%E5%85%AC%E5%8F%B8%E5%90%A6%E8%AE%A4%E5%BC%A0%E5%A8%9C%E6%8B%89%E5%8E%BB%E4%B8%96%23) `341.6K 🔥` `-56%`
1. [美媒称这场战争打不起了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AA%92%E7%A7%B0%E8%BF%99%E5%9C%BA%E6%88%98%E4%BA%89%E6%89%93%E4%B8%8D%E8%B5%B7%E4%BA%86%23) `341.6K 🔥` `-57%`
1. [李诞称有人用AI龙虾约女主播饭](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%AF%9E%E7%A7%B0%E6%9C%89%E4%BA%BA%E7%94%A8AI%E9%BE%99%E8%99%BE%E7%BA%A6%E5%A5%B3%E4%B8%BB%E6%92%AD%E9%A5%AD%23) `341.5K 🔥` `-56%`
1. [数字生命](https://s.weibo.com/weibo?q=%23%E6%95%B0%E5%AD%97%E7%94%9F%E5%91%BD%23) `341.3K 🔥` `-56%`
1. [别再吃高油高盐的食物了](https://s.weibo.com/weibo?q=%23%E5%88%AB%E5%86%8D%E5%90%83%E9%AB%98%E6%B2%B9%E9%AB%98%E7%9B%90%E7%9A%84%E9%A3%9F%E7%89%A9%E4%BA%86%23) `341.2K 🔥` `-57%`
1. [医生提醒不要模仿Ella真空腹 (Doctor reminds not to imitate Ella’s vacuum abdomen)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E6%8F%90%E9%86%92%E4%B8%8D%E8%A6%81%E6%A8%A1%E4%BB%BFElla%E7%9C%9F%E7%A9%BA%E8%85%B9%23) `341.0K 🔥` `-57%`
1. [腾讯版小龙虾致歉信 (Tencent version of crayfish apology letter)](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E7%89%88%E5%B0%8F%E9%BE%99%E8%99%BE%E8%87%B4%E6%AD%89%E4%BF%A1%23) `340.6K 🔥` `-57%`
1. [火鸡面冰淇淋 (turkey noodle ice cream)](https://s.weibo.com/weibo?q=%23%E7%81%AB%E9%B8%A1%E9%9D%A2%E5%86%B0%E6%B7%87%E6%B7%8B%23) `340.6K 🔥` `-57%`
1. [男子养双头龟喂食时2个头还争食](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%85%BB%E5%8F%8C%E5%A4%B4%E9%BE%9F%E5%96%82%E9%A3%9F%E6%97%B62%E4%B8%AA%E5%A4%B4%E8%BF%98%E4%BA%89%E9%A3%9F%23) `340.5K 🔥` `-57%`
1. [樊长玉得知谢征是武安侯](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E5%BE%97%E7%9F%A5%E8%B0%A2%E5%BE%81%E6%98%AF%E6%AD%A6%E5%AE%89%E4%BE%AF%23) `340.4K 🔥` `-57%`
1. [袁惟仁告别式 (Yuan Weiren's farewell ceremony)](https://s.weibo.com/weibo?q=%23%E8%A2%81%E6%83%9F%E4%BB%81%E5%91%8A%E5%88%AB%E5%BC%8F%23) `340.1K 🔥` `-57%`

Updated at 2026-03-10 15:07:22

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
