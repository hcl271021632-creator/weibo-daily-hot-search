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

1. [涉企网络辟谣专区今天上线 (A special area to refute corporate rumors online today)](https://s.weibo.com/weibo?q=%23%E6%B6%89%E4%BC%81%E7%BD%91%E7%BB%9C%E8%BE%9F%E8%B0%A3%E4%B8%93%E5%8C%BA%E4%BB%8A%E5%A4%A9%E4%B8%8A%E7%BA%BF%23) `380.7K 🔥` `NEW`
1. [北京WBG对战FPX.ZQ](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%ACWBG%E5%AF%B9%E6%88%98FPX.ZQ%23) `235.6K 🔥` `NEW`
1. [逐玉开始单更了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%80%E5%A7%8B%E5%8D%95%E6%9B%B4%E4%BA%86%23) `204.6K 🔥` `NEW`
1. [中美经贸磋商在巴黎举行](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E7%BE%8E%E7%BB%8F%E8%B4%B8%E7%A3%8B%E5%95%86%E5%9C%A8%E5%B7%B4%E9%BB%8E%E4%B8%BE%E8%A1%8C%23) `153.5K 🔥` `NEW`
1. [315记者为拍证据曾勇闯杀人蜂区](https://s.weibo.com/weibo?q=%23315%E8%AE%B0%E8%80%85%E4%B8%BA%E6%8B%8D%E8%AF%81%E6%8D%AE%E6%9B%BE%E5%8B%87%E9%97%AF%E6%9D%80%E4%BA%BA%E8%9C%82%E5%8C%BA%23) `152.8K 🔥` `NEW`
1. [李煜东故事会](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%85%9C%E4%B8%9C%E6%95%85%E4%BA%8B%E4%BC%9A%23) `146.3K 🔥` `NEW`
1. [三平台破万的六位演员](https://s.weibo.com/weibo?q=%23%E4%B8%89%E5%B9%B3%E5%8F%B0%E7%A0%B4%E4%B8%87%E7%9A%84%E5%85%AD%E4%BD%8D%E6%BC%94%E5%91%98%23) `141.4K 🔥` `NEW`
1. [林丹回应不让儿子学羽毛球](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%B8%B9%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E5%84%BF%E5%AD%90%E5%AD%A6%E7%BE%BD%E6%AF%9B%E7%90%83%23) `133.4K 🔥` `NEW`
1. [王橹杰的语音](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E7%9A%84%E8%AF%AD%E9%9F%B3%23) `131.6K 🔥` `NEW`
1. [国色天香 何晟铭](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E8%89%B2%E5%A4%A9%E9%A6%99%20%E4%BD%95%E6%99%9F%E9%93%AD%23) `127.7K 🔥` `NEW`
1. [余承恩妈妈感谢夏之光 (Yu Chengen’s mother thanks Xia Zhiguang)](https://s.weibo.com/weibo?q=%23%E4%BD%99%E6%89%BF%E6%81%A9%E5%A6%88%E5%A6%88%E6%84%9F%E8%B0%A2%E5%A4%8F%E4%B9%8B%E5%85%89%23) `125.8K 🔥` `NEW`
1. [伊朗称要打到美以投降受到惩罚](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E8%A6%81%E6%89%93%E5%88%B0%E7%BE%8E%E4%BB%A5%E6%8A%95%E9%99%8D%E5%8F%97%E5%88%B0%E6%83%A9%E7%BD%9A%23) `119.5K 🔥` `NEW`
1. [孔雪儿邓凯 接三搭](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E9%82%93%E5%87%AF%20%E6%8E%A5%E4%B8%89%E6%90%AD%23) `116.8K 🔥` `NEW`
1. [部分商家被315晚会曝光后屡教不改](https://s.weibo.com/weibo?q=%23%E9%83%A8%E5%88%86%E5%95%86%E5%AE%B6%E8%A2%AB315%E6%99%9A%E4%BC%9A%E6%9B%9D%E5%85%89%E5%90%8E%E5%B1%A1%E6%95%99%E4%B8%8D%E6%94%B9%23) `109.6K 🔥` `NEW`
1. [奔驰EQC车主称花50万买了个老头乐](https://s.weibo.com/weibo?q=%23%E5%A5%94%E9%A9%B0EQC%E8%BD%A6%E4%B8%BB%E7%A7%B0%E8%8A%B150%E4%B8%87%E4%B9%B0%E4%BA%86%E4%B8%AA%E8%80%81%E5%A4%B4%E4%B9%90%23) `105.8K 🔥` `NEW`
1. [F1现场好多明星](https://s.weibo.com/weibo?q=%23F1%E7%8E%B0%E5%9C%BA%E5%A5%BD%E5%A4%9A%E6%98%8E%E6%98%9F%23) `97.8K 🔥` `NEW`
1. [王鹤棣把白鹿宋茜沈月都回答了一遍](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%8A%8A%E7%99%BD%E9%B9%BF%E5%AE%8B%E8%8C%9C%E6%B2%88%E6%9C%88%E9%83%BD%E5%9B%9E%E7%AD%94%E4%BA%86%E4%B8%80%E9%81%8D%23) `96.6K 🔥` `NEW`
1. [刘文祥](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%23) `96.3K 🔥` `NEW`
1. [315](https://s.weibo.com/weibo?q=%23315%23) `912.2K 🔥` `+161%`
1. [紫薯精天塌了 (Purple Sweet Potato Essence The sky is falling)](https://s.weibo.com/weibo?q=%23%E7%B4%AB%E8%96%AF%E7%B2%BE%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `617.2K 🔥` `+513%`
1. [胖东来要求博主删除视频](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E8%A6%81%E6%B1%82%E5%8D%9A%E4%B8%BB%E5%88%A0%E9%99%A4%E8%A7%86%E9%A2%91%23) `407.5K 🔥` `+83%`
1. [逐玉云合破50%](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%91%E5%90%88%E7%A0%B450%25%23) `351.8K 🔥` `+140%`
1. [江西九江发生岩降事故 3人死亡 (Three people died in a rockfall accident in Jiujiang, Jiangxi)](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E8%A5%BF%E4%B9%9D%E6%B1%9F%E5%8F%91%E7%94%9F%E5%B2%A9%E9%99%8D%E4%BA%8B%E6%95%85%203%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `312.9K 🔥` `+40%`
1. [怪不得印度工业发达原来都是0成本](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E5%8D%B0%E5%BA%A6%E5%B7%A5%E4%B8%9A%E5%8F%91%E8%BE%BE%E5%8E%9F%E6%9D%A5%E9%83%BD%E6%98%AF0%E6%88%90%E6%9C%AC%23) `289.8K 🔥` `+29%`
1. [鹿哈或需赔偿消费者26.9亿元 (Luha may have to compensate consumers 2.69 billion yuan)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E6%88%96%E9%9C%80%E8%B5%94%E5%81%BF%E6%B6%88%E8%B4%B9%E8%80%8526.9%E4%BA%BF%E5%85%83%23) `1.6M 🔥`
1. [十五五这四类人群直接受益 (These four groups of people will directly benefit from the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%BF%99%E5%9B%9B%E7%B1%BB%E4%BA%BA%E7%BE%A4%E7%9B%B4%E6%8E%A5%E5%8F%97%E7%9B%8A%23) `755.0K 🔥`
1. [张凌赫田曦薇没有杀青合照](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%B2%A1%E6%9C%89%E6%9D%80%E9%9D%92%E5%90%88%E7%85%A7%23) `309.2K 🔥`
1. [温瑞博4比2张本智和](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9A4%E6%AF%942%E5%BC%A0%E6%9C%AC%E6%99%BA%E5%92%8C%23) `203.5K 🔥`
1. [央视315晚会点名食品安全领域](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86315%E6%99%9A%E4%BC%9A%E7%82%B9%E5%90%8D%E9%A3%9F%E5%93%81%E5%AE%89%E5%85%A8%E9%A2%86%E5%9F%9F%23) `167.6K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `149.2K 🔥`
1. [央视调查某茶饮品牌遭恶意抹黑始末](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E8%B0%83%E6%9F%A5%E6%9F%90%E8%8C%B6%E9%A5%AE%E5%93%81%E7%89%8C%E9%81%AD%E6%81%B6%E6%84%8F%E6%8A%B9%E9%BB%91%E5%A7%8B%E6%9C%AB%23) `142.1K 🔥`
1. [郝熠然 今晚见一面吧](https://s.weibo.com/weibo?q=%23%E9%83%9D%E7%86%A0%E7%84%B6%20%E4%BB%8A%E6%99%9A%E8%A7%81%E4%B8%80%E9%9D%A2%E5%90%A7%23) `141.5K 🔥`
1. [安东内利哭了](https://s.weibo.com/weibo?q=%23%E5%AE%89%E4%B8%9C%E5%86%85%E5%88%A9%E5%93%AD%E4%BA%86%23) `102.1K 🔥`
1. [李煜东发文 (Li Yudong posted a message)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%85%9C%E4%B8%9C%E5%8F%91%E6%96%87%23) `101.2K 🔥`
1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `384.2K 🔥` `-28%`
1. [刘文祥刚爆火就塌房 (Liu Wenxiang's house collapsed just after the fire broke out)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E5%88%9A%E7%88%86%E7%81%AB%E5%B0%B1%E5%A1%8C%E6%88%BF%23) `298.2K 🔥` `-68%`
1. [七种千万不能吃的食物 (Seven foods you must not eat)](https://s.weibo.com/weibo?q=%23%E4%B8%83%E7%A7%8D%E5%8D%83%E4%B8%87%E4%B8%8D%E8%83%BD%E5%90%83%E7%9A%84%E9%A3%9F%E7%89%A9%23) `282.6K 🔥` `-23%`
1. [维斯塔潘退赛](https://s.weibo.com/weibo?q=%23%E7%BB%B4%E6%96%AF%E5%A1%94%E6%BD%98%E9%80%80%E8%B5%9B%23) `233.5K 🔥` `-53%`
1. [法拉利内斗](https://s.weibo.com/weibo?q=%23%E6%B3%95%E6%8B%89%E5%88%A9%E5%86%85%E6%96%97%23) `153.6K 🔥` `-31%`
1. [成毅 年龄 (Cheng Yi age)](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%20%E5%B9%B4%E9%BE%84%23) `152.4K 🔥` `-32%`
1. [何晟铭因不愿演男主和于正冷战 (He Shengming had a cold war with Yu Zheng because he didn't want to play the male lead.)](https://s.weibo.com/weibo?q=%23%E4%BD%95%E6%99%9F%E9%93%AD%E5%9B%A0%E4%B8%8D%E6%84%BF%E6%BC%94%E7%94%B7%E4%B8%BB%E5%92%8C%E4%BA%8E%E6%AD%A3%E5%86%B7%E6%88%98%23) `152.1K 🔥` `-32%`
1. [美宜佳致歉](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AE%9C%E4%BD%B3%E8%87%B4%E6%AD%89%23) `151.9K 🔥` `-45%`
1. [泡椒凤爪的泡椒竟是印上去的 (The pickled peppers in the pickled pepper chicken feet are actually printed on them.)](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E6%A4%92%E5%87%A4%E7%88%AA%E7%9A%84%E6%B3%A1%E6%A4%92%E7%AB%9F%E6%98%AF%E5%8D%B0%E4%B8%8A%E5%8E%BB%E7%9A%84%23) `140.5K 🔥` `-36%`
1. [鹿哈 凌达乐 (Lu Ha Ling Dale)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%20%E5%87%8C%E8%BE%BE%E4%B9%90%23) `136.9K 🔥` `-39%`
1. [眼镜镜片标价799元进价仅15元](https://s.weibo.com/weibo?q=%23%E7%9C%BC%E9%95%9C%E9%95%9C%E7%89%87%E6%A0%87%E4%BB%B7799%E5%85%83%E8%BF%9B%E4%BB%B7%E4%BB%8515%E5%85%83%23) `127.9K 🔥` `-41%`
1. [保证前额叶健康太重要了](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E8%AF%81%E5%89%8D%E9%A2%9D%E5%8F%B6%E5%81%A5%E5%BA%B7%E5%A4%AA%E9%87%8D%E8%A6%81%E4%BA%86%23) `123.6K 🔥` `-34%`
1. [伊朗用涂鸦骗导弹轰炸](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%94%A8%E6%B6%82%E9%B8%A6%E9%AA%97%E5%AF%BC%E5%BC%B9%E8%BD%B0%E7%82%B8%23) `116.5K 🔥` `-21%`
1. [自闭症女孩玩游戏半年充45万](https://s.weibo.com/weibo?q=%23%E8%87%AA%E9%97%AD%E7%97%87%E5%A5%B3%E5%AD%A9%E7%8E%A9%E6%B8%B8%E6%88%8F%E5%8D%8A%E5%B9%B4%E5%85%8545%E4%B8%87%23) `108.9K 🔥` `-51%`
1. [短视频平台直播间的暗藏色情交易](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E8%A7%86%E9%A2%91%E5%B9%B3%E5%8F%B0%E7%9B%B4%E6%92%AD%E9%97%B4%E7%9A%84%E6%9A%97%E8%97%8F%E8%89%B2%E6%83%85%E4%BA%A4%E6%98%93%23) `105.0K 🔥` `-52%`
1. [安东内利夺F1中国站冠军](https://s.weibo.com/weibo?q=%23%E5%AE%89%E4%B8%9C%E5%86%85%E5%88%A9%E5%A4%BAF1%E4%B8%AD%E5%9B%BD%E7%AB%99%E5%86%A0%E5%86%9B%23) `102.3K 🔥` `-33%`
1. [25岁儿子毕业不工作急哭父亲 (The 25-year-old son is crying because he has no job after graduation.)](https://s.weibo.com/weibo?q=%2325%E5%B2%81%E5%84%BF%E5%AD%90%E6%AF%95%E4%B8%9A%E4%B8%8D%E5%B7%A5%E4%BD%9C%E6%80%A5%E5%93%AD%E7%88%B6%E4%BA%B2%23) `98.9K 🔥` `-27%`

Updated at 2026-03-15 17:48:34

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
