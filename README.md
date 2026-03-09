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

1. [十四届全国人大四次会议二次全体会议 (Second Plenary Session of the Fourth Session of the 14th National People's Congress)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E4%BA%8C%E6%AC%A1%E5%85%A8%E4%BD%93%E4%BC%9A%E8%AE%AE%23) `1.0M 🔥` `NEW`
1. [胖东来每年利润50%发奖金](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E6%AF%8F%E5%B9%B4%E5%88%A9%E6%B6%A650%25%E5%8F%91%E5%A5%96%E9%87%91%23) `414.8K 🔥` `NEW`
1. [伊朗确认军舰遭美军击沉致104人死亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A1%AE%E8%AE%A4%E5%86%9B%E8%88%B0%E9%81%AD%E7%BE%8E%E5%86%9B%E5%87%BB%E6%B2%89%E8%87%B4104%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `289.2K 🔥` `NEW`
1. [官方辟谣霍山存在600公斤储量砂金矿](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E8%BE%9F%E8%B0%A3%E9%9C%8D%E5%B1%B1%E5%AD%98%E5%9C%A8600%E5%85%AC%E6%96%A4%E5%82%A8%E9%87%8F%E7%A0%82%E9%87%91%E7%9F%BF%23) `288.2K 🔥` `NEW`
1. [建议将8小时工作制缩短为7小时](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%868%E5%B0%8F%E6%97%B6%E5%B7%A5%E4%BD%9C%E5%88%B6%E7%BC%A9%E7%9F%AD%E4%B8%BA7%E5%B0%8F%E6%97%B6%23) `287.9K 🔥` `NEW`
1. [孔雪儿 真天使投资人](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%20%E7%9C%9F%E5%A4%A9%E4%BD%BF%E6%8A%95%E8%B5%84%E4%BA%BA%23) `285.9K 🔥` `NEW`
1. [桃黑黑开奖](https://s.weibo.com/weibo?q=%23%E6%A1%83%E9%BB%91%E9%BB%91%E5%BC%80%E5%A5%96%23) `284.2K 🔥` `NEW`
1. [985父母的清醒反思](https://s.weibo.com/weibo?q=%23985%E7%88%B6%E6%AF%8D%E7%9A%84%E6%B8%85%E9%86%92%E5%8F%8D%E6%80%9D%23) `280.3K 🔥` `NEW`
1. [地狱级饮食后身体的变化](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E7%8B%B1%E7%BA%A7%E9%A5%AE%E9%A3%9F%E5%90%8E%E8%BA%AB%E4%BD%93%E7%9A%84%E5%8F%98%E5%8C%96%23) `251.6K 🔥` `NEW`
1. [今年修改教师法](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E4%BF%AE%E6%94%B9%E6%95%99%E5%B8%88%E6%B3%95%23) `225.3K 🔥` `NEW`
1. [王鹤棣孟子义将门独后首个同框路透 (Wang Hedi and Meng Ziyi are the first to share the same frame with Reuters)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AD%9F%E5%AD%90%E4%B9%89%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E9%A6%96%E4%B8%AA%E5%90%8C%E6%A1%86%E8%B7%AF%E9%80%8F%23) `205.2K 🔥` `NEW`
1. [刘美贤3次力挺谷爱凌](https://s.weibo.com/weibo?q=%23%E5%88%98%E7%BE%8E%E8%B4%A43%E6%AC%A1%E5%8A%9B%E6%8C%BA%E8%B0%B7%E7%88%B1%E5%87%8C%23) `204.8K 🔥` `NEW`
1. [云南的紫外线我给到夯](https://s.weibo.com/weibo?q=%23%E4%BA%91%E5%8D%97%E7%9A%84%E7%B4%AB%E5%A4%96%E7%BA%BF%E6%88%91%E7%BB%99%E5%88%B0%E5%A4%AF%23) `199.8K 🔥` `NEW`
1. [今年制定国有资产法](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E5%88%B6%E5%AE%9A%E5%9B%BD%E6%9C%89%E8%B5%84%E4%BA%A7%E6%B3%95%23) `193.4K 🔥` `NEW`
1. [五角大楼承认伊无人机破坏力超预期](https://s.weibo.com/weibo?q=%23%E4%BA%94%E8%A7%92%E5%A4%A7%E6%A5%BC%E6%89%BF%E8%AE%A4%E4%BC%8A%E6%97%A0%E4%BA%BA%E6%9C%BA%E7%A0%B4%E5%9D%8F%E5%8A%9B%E8%B6%85%E9%A2%84%E6%9C%9F%23) `182.0K 🔥` `NEW`
1. [父亲回应9岁女孩埃及霸气维权](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E5%9B%9E%E5%BA%949%E5%B2%81%E5%A5%B3%E5%AD%A9%E5%9F%83%E5%8F%8A%E9%9C%B8%E6%B0%94%E7%BB%B4%E6%9D%83%23) `123.4K 🔥` `NEW`
1. [伊朗储油设施遭袭19小时后天空浓烟](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%82%A8%E6%B2%B9%E8%AE%BE%E6%96%BD%E9%81%AD%E8%A2%AD19%E5%B0%8F%E6%97%B6%E5%90%8E%E5%A4%A9%E7%A9%BA%E6%B5%93%E7%83%9F%23) `123.2K 🔥` `NEW`
1. [谷爱凌妇女节晒和妈妈合影](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A6%87%E5%A5%B3%E8%8A%82%E6%99%92%E5%92%8C%E5%A6%88%E5%A6%88%E5%90%88%E5%BD%B1%23) `120.9K 🔥` `NEW`
1. [iPhoneUltra起售价或超万元](https://s.weibo.com/weibo?q=%23iPhoneUltra%E8%B5%B7%E5%94%AE%E4%BB%B7%E6%88%96%E8%B6%85%E4%B8%87%E5%85%83%23) `118.1K 🔥` `NEW`
1. [岳雨婷口碑反转](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E5%8F%A3%E7%A2%91%E5%8F%8D%E8%BD%AC%23) `105.7K 🔥` `NEW`
1. [原来这就是醍醐灌顶的感觉 (It turns out that this is the feeling of enlightenment)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E5%B0%B1%E6%98%AF%E9%86%8D%E9%86%90%E7%81%8C%E9%A1%B6%E7%9A%84%E6%84%9F%E8%A7%89%23) `90.1K 🔥` `NEW`
1. [美军称已有7名士兵阵亡](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E7%A7%B0%E5%B7%B2%E6%9C%897%E5%90%8D%E5%A3%AB%E5%85%B5%E9%98%B5%E4%BA%A1%23) `85.7K 🔥` `NEW`
1. [伊朗革命卫队支持新任最高领袖](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E6%94%AF%E6%8C%81%E6%96%B0%E4%BB%BB%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%23) `73.1K 🔥` `NEW`
1. [企业拒收留学生背后的考量](https://s.weibo.com/weibo?q=%23%E4%BC%81%E4%B8%9A%E6%8B%92%E6%94%B6%E7%95%99%E5%AD%A6%E7%94%9F%E8%83%8C%E5%90%8E%E7%9A%84%E8%80%83%E9%87%8F%23) `70.3K 🔥` `NEW`
1. [父亲回应儿子为逃打被困塔吊6小时](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E5%9B%9E%E5%BA%94%E5%84%BF%E5%AD%90%E4%B8%BA%E9%80%83%E6%89%93%E8%A2%AB%E5%9B%B0%E5%A1%94%E5%90%8A6%E5%B0%8F%E6%97%B6%23) `68.5K 🔥` `NEW`
1. [王祉怡全英夺冠后说我不出操了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%A5%89%E6%80%A1%E5%85%A8%E8%8B%B1%E5%A4%BA%E5%86%A0%E5%90%8E%E8%AF%B4%E6%88%91%E4%B8%8D%E5%87%BA%E6%93%8D%E4%BA%86%23) `57.8K 🔥` `NEW`
1. [徐志胜回应黄子韬徐艺洋吵架](https://s.weibo.com/weibo?q=%23%E5%BE%90%E5%BF%97%E8%83%9C%E5%9B%9E%E5%BA%94%E9%BB%84%E5%AD%90%E9%9F%AC%E5%BE%90%E8%89%BA%E6%B4%8B%E5%90%B5%E6%9E%B6%23) `56.8K 🔥` `NEW`
1. [最高法工作报告抢先看](https://s.weibo.com/weibo?q=%23%E6%9C%80%E9%AB%98%E6%B3%95%E5%B7%A5%E4%BD%9C%E6%8A%A5%E5%91%8A%E6%8A%A2%E5%85%88%E7%9C%8B%23) `56.7K 🔥` `NEW`
1. [AG世界赛首胜](https://s.weibo.com/weibo?q=%23AG%E4%B8%96%E7%95%8C%E8%B5%9B%E9%A6%96%E8%83%9C%23) `56.7K 🔥` `NEW`
1. [中国式现代化圈粉全球 (Chinese-style modernization attracts global fans)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%BC%8F%E7%8E%B0%E4%BB%A3%E5%8C%96%E5%9C%88%E7%B2%89%E5%85%A8%E7%90%83%23) `285.2K 🔥` `+33%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `197.7K 🔥` `+36%`
1. [27岁女子挤痘痘后确诊2型糖尿病 (27-year-old woman diagnosed with type 2 diabetes after popping acne)](https://s.weibo.com/weibo?q=%2327%E5%B2%81%E5%A5%B3%E5%AD%90%E6%8C%A4%E7%97%98%E7%97%98%E5%90%8E%E7%A1%AE%E8%AF%8A2%E5%9E%8B%E7%B3%96%E5%B0%BF%E7%97%85%23) `123.1K 🔥` `+30%`
1. [从海底1万米到距地球4300万公里 (From 10,000 meters under the sea to 43 million kilometers from the earth)](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E6%B5%B7%E5%BA%951%E4%B8%87%E7%B1%B3%E5%88%B0%E8%B7%9D%E5%9C%B0%E7%90%834300%E4%B8%87%E5%85%AC%E9%87%8C%23) `583.3K 🔥`
1. [逐玉因平台缺爆款被迫爆 (Zhuyu was forced to go viral due to lack of popular items on the platform)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%9B%A0%E5%B9%B3%E5%8F%B0%E7%BC%BA%E7%88%86%E6%AC%BE%E8%A2%AB%E8%BF%AB%E7%88%86%23) `191.2K 🔥`
1. [逐玉 出圈梗 (Zhuyu out of the circle stalks)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%87%BA%E5%9C%88%E6%A2%97%23) `177.4K 🔥`
1. [恋综史上最明艳的出场 (The brightest appearance in the history of romance dramas)](https://s.weibo.com/weibo?q=%23%E6%81%8B%E7%BB%BC%E5%8F%B2%E4%B8%8A%E6%9C%80%E6%98%8E%E8%89%B3%E7%9A%84%E5%87%BA%E5%9C%BA%23) `93.7K 🔥`
1. [王一博 巴黎也有回南天 (Wang Yibo Paris also returns to Nantian)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%20%E5%B7%B4%E9%BB%8E%E4%B9%9F%E6%9C%89%E5%9B%9E%E5%8D%97%E5%A4%A9%23) `78.5K 🔥`
1. [汪苏泷演唱会 (Wang Sulong concert)](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E6%BC%94%E5%94%B1%E4%BC%9A%23) `65.8K 🔥`
1. [Bin不知道BFX从哪冒出来](https://s.weibo.com/weibo?q=%23Bin%E4%B8%8D%E7%9F%A5%E9%81%93BFX%E4%BB%8E%E5%93%AA%E5%86%92%E5%87%BA%E6%9D%A5%23) `61.9K 🔥`
1. [湖南卫视妇女节视频设计好天才啊 (Hunan Satellite TV’s Women’s Day video design is so genius)](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E5%8D%AB%E8%A7%86%E5%A6%87%E5%A5%B3%E8%8A%82%E8%A7%86%E9%A2%91%E8%AE%BE%E8%AE%A1%E5%A5%BD%E5%A4%A9%E6%89%8D%E5%95%8A%23) `61.6K 🔥`
1. [王毅向日本发出灵魂4问 (Wang Yi sends 4 soul questions to Japan)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%AF%85%E5%90%91%E6%97%A5%E6%9C%AC%E5%8F%91%E5%87%BA%E7%81%B5%E9%AD%824%E9%97%AE%23) `730.3K 🔥` `-26%`
1. [中传砍掉翻译摄影等16个专业 (CCTV cuts 16 majors including translation and photography)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BC%A0%E7%A0%8D%E6%8E%89%E7%BF%BB%E8%AF%91%E6%91%84%E5%BD%B1%E7%AD%8916%E4%B8%AA%E4%B8%93%E4%B8%9A%23) `289.3K 🔥` `-43%`
1. [哈梅内伊之子接任最高领袖 (Khamenei's son takes over as supreme leader)](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E4%B9%8B%E5%AD%90%E6%8E%A5%E4%BB%BB%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%23) `281.8K 🔥` `-49%`
1. [多家黄金品牌宣布调价 (Many gold brands announce price adjustments)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%AE%B6%E9%BB%84%E9%87%91%E5%93%81%E7%89%8C%E5%AE%A3%E5%B8%83%E8%B0%83%E4%BB%B7%23) `280.5K 🔥` `-50%`
1. [狂飙 (hurricane)](https://s.weibo.com/weibo?q=%23%E7%8B%82%E9%A3%99%23) `184.6K 🔥` `-68%`
1. [武大食堂4元熬夜水日销百斤 (Wuhan University cafeteria sells 100 kilograms of water for staying up late for 4 yuan a day)](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E5%A4%A7%E9%A3%9F%E5%A0%824%E5%85%83%E7%86%AC%E5%A4%9C%E6%B0%B4%E6%97%A5%E9%94%80%E7%99%BE%E6%96%A4%23) `113.4K 🔥` `-51%`
1. [两艘万吨大驱亮相 (Two 10,000-ton cruise ships unveiled)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E8%89%98%E4%B8%87%E5%90%A8%E5%A4%A7%E9%A9%B1%E4%BA%AE%E7%9B%B8%23) `79.9K 🔥` `-89%`
1. [玫瑰丛生](https://s.weibo.com/weibo?q=%23%E7%8E%AB%E7%91%B0%E4%B8%9B%E7%94%9F%23) `74.2K 🔥` `-63%`
1. [AI对老师的影响 (The impact of AI on teachers)](https://s.weibo.com/weibo?q=%23AI%E5%AF%B9%E8%80%81%E5%B8%88%E7%9A%84%E5%BD%B1%E5%93%8D%23) `61.0K 🔥` `-34%`
1. [美军战斗力成谜 (U.S. military’s combat effectiveness remains a mystery)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E6%88%98%E6%96%97%E5%8A%9B%E6%88%90%E8%B0%9C%23) `59.1K 🔥` `-37%`

Updated at 2026-03-09 09:58:59

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
