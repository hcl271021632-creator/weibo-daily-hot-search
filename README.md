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

1. [315晚会后台探秘 (315 party backstage exploration)](https://s.weibo.com/weibo?q=%23315%E6%99%9A%E4%BC%9A%E5%90%8E%E5%8F%B0%E6%8E%A2%E7%A7%98%23) `196.1K 🔥` `NEW`
1. [刘文祥麻辣烫多处不合规](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E5%A4%9A%E5%A4%84%E4%B8%8D%E5%90%88%E8%A7%84%23) `184.9K 🔥` `NEW`
1. [网红法式鹅肝竟检出鸡源性成分](https://s.weibo.com/weibo?q=%23%E7%BD%91%E7%BA%A2%E6%B3%95%E5%BC%8F%E9%B9%85%E8%82%9D%E7%AB%9F%E6%A3%80%E5%87%BA%E9%B8%A1%E6%BA%90%E6%80%A7%E6%88%90%E5%88%86%23) `168.8K 🔥` `NEW`
1. [女童穿新鞋3天后高低腿被客服嘲讽](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%AB%A5%E7%A9%BF%E6%96%B0%E9%9E%8B3%E5%A4%A9%E5%90%8E%E9%AB%98%E4%BD%8E%E8%85%BF%E8%A2%AB%E5%AE%A2%E6%9C%8D%E5%98%B2%E8%AE%BD%23) `122.1K 🔥` `NEW`
1. [不喜欢可能认识的人](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%96%9C%E6%AC%A2%E5%8F%AF%E8%83%BD%E8%AE%A4%E8%AF%86%E7%9A%84%E4%BA%BA%23) `110.6K 🔥` `NEW`
1. [怪不得今年陆虎蒋敦豪没上春晚](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E4%BB%8A%E5%B9%B4%E9%99%86%E8%99%8E%E8%92%8B%E6%95%A6%E8%B1%AA%E6%B2%A1%E4%B8%8A%E6%98%A5%E6%99%9A%23) `110.4K 🔥` `NEW`
1. [黄晓明问邵子恒是在讲赵丽颖的剧吗](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E9%97%AE%E9%82%B5%E5%AD%90%E6%81%92%E6%98%AF%E5%9C%A8%E8%AE%B2%E8%B5%B5%E4%B8%BD%E9%A2%96%E7%9A%84%E5%89%A7%E5%90%97%23) `106.4K 🔥` `NEW`
1. [痞幼带保洁阿姨去三亚度假](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%B8%A6%E4%BF%9D%E6%B4%81%E9%98%BF%E5%A7%A8%E5%8E%BB%E4%B8%89%E4%BA%9A%E5%BA%A6%E5%81%87%23) `103.8K 🔥` `NEW`
1. [邓超等到孙俪出来才上车](https://s.weibo.com/weibo?q=%23%E9%82%93%E8%B6%85%E7%AD%89%E5%88%B0%E5%AD%99%E4%BF%AA%E5%87%BA%E6%9D%A5%E6%89%8D%E4%B8%8A%E8%BD%A6%23) `91.7K 🔥` `NEW`
1. [第五人格COA9预选赛](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%BA%94%E4%BA%BA%E6%A0%BCCOA9%E9%A2%84%E9%80%89%E8%B5%9B%23) `87.2K 🔥` `NEW`
1. [暗访保税仓发货背后造假黑产 (Undercover visits to bonded warehouses to uncover counterfeit goods behind shipments)](https://s.weibo.com/weibo?q=%23%E6%9A%97%E8%AE%BF%E4%BF%9D%E7%A8%8E%E4%BB%93%E5%8F%91%E8%B4%A7%E8%83%8C%E5%90%8E%E9%80%A0%E5%81%87%E9%BB%91%E4%BA%A7%23) `83.6K 🔥` `NEW`
1. [淘宝闪购把F1速度带出赛道 (Taobao flash sales take F1 speed off the track)](https://s.weibo.com/weibo?q=%23%E6%B7%98%E5%AE%9D%E9%97%AA%E8%B4%AD%E6%8A%8AF1%E9%80%9F%E5%BA%A6%E5%B8%A6%E5%87%BA%E8%B5%9B%E9%81%93%23) `688.1K 🔥` `+51%`
1. [315记者为拍证据曾勇闯杀人蜂区](https://s.weibo.com/weibo?q=%23315%E8%AE%B0%E8%80%85%E4%B8%BA%E6%8B%8D%E8%AF%81%E6%8D%AE%E6%9B%BE%E5%8B%87%E9%97%AF%E6%9D%80%E4%BA%BA%E8%9C%82%E5%8C%BA%23) `310.7K 🔥` `+33%`
1. [为什么大学里的男生比例越来越少](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E5%A4%A7%E5%AD%A6%E9%87%8C%E7%9A%84%E7%94%B7%E7%94%9F%E6%AF%94%E4%BE%8B%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%B0%91%23) `136.1K 🔥` `+26%`
1. [鹿哈或需赔偿消费者26.9亿元 (Luha may have to compensate consumers 2.69 billion yuan)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E6%88%96%E9%9C%80%E8%B5%94%E5%81%BF%E6%B6%88%E8%B4%B9%E8%80%8526.9%E4%BA%BF%E5%85%83%23) `1.2M 🔥`
1. [315](https://s.weibo.com/weibo?q=%23315%23) `945.1K 🔥`
1. [十五五这四类人群直接受益 (These four groups of people will directly benefit from the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%BF%99%E5%9B%9B%E7%B1%BB%E4%BA%BA%E7%BE%A4%E7%9B%B4%E6%8E%A5%E5%8F%97%E7%9B%8A%23) `702.8K 🔥`
1. [紫薯精天塌了 (Purple Sweet Potato Essence The sky is falling)](https://s.weibo.com/weibo?q=%23%E7%B4%AB%E8%96%AF%E7%B2%BE%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `687.8K 🔥`
1. [胖东来要求博主删除视频 (Fat Donglai asked the blogger to delete the video)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E8%A6%81%E6%B1%82%E5%8D%9A%E4%B8%BB%E5%88%A0%E9%99%A4%E8%A7%86%E9%A2%91%23) `529.8K 🔥`
1. [F1现场好多明星](https://s.weibo.com/weibo?q=%23F1%E7%8E%B0%E5%9C%BA%E5%A5%BD%E5%A4%9A%E6%98%8E%E6%98%9F%23) `190.7K 🔥`
1. [林丹回应不让儿子学羽毛球](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%B8%B9%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E5%84%BF%E5%AD%90%E5%AD%A6%E7%BE%BD%E6%AF%9B%E7%90%83%23) `188.5K 🔥`
1. [iPhone长焦 出片](https://s.weibo.com/weibo?q=%23iPhone%E9%95%BF%E7%84%A6%20%E5%87%BA%E7%89%87%23) `136.4K 🔥`
1. [郝熠然直播](https://s.weibo.com/weibo?q=%23%E9%83%9D%E7%86%A0%E7%84%B6%E7%9B%B4%E6%92%AD%23) `136.2K 🔥`
1. [成毅 年龄 (Cheng Yi age)](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%20%E5%B9%B4%E9%BE%84%23) `133.6K 🔥`
1. [小英整牙](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E8%8B%B1%E6%95%B4%E7%89%99%23) `131.8K 🔥`
1. [伊朗称要打到美以投降受到惩罚](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E8%A6%81%E6%89%93%E5%88%B0%E7%BE%8E%E4%BB%A5%E6%8A%95%E9%99%8D%E5%8F%97%E5%88%B0%E6%83%A9%E7%BD%9A%23) `129.4K 🔥`
1. [男制作人用吉赛尔未公开照片当头像](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%88%B6%E4%BD%9C%E4%BA%BA%E7%94%A8%E5%90%89%E8%B5%9B%E5%B0%94%E6%9C%AA%E5%85%AC%E5%BC%80%E7%85%A7%E7%89%87%E5%BD%93%E5%A4%B4%E5%83%8F%23) `129.4K 🔥`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `129.4K 🔥`
1. [三平台破万的六位演员](https://s.weibo.com/weibo?q=%23%E4%B8%89%E5%B9%B3%E5%8F%B0%E7%A0%B4%E4%B8%87%E7%9A%84%E5%85%AD%E4%BD%8D%E6%BC%94%E5%91%98%23) `124.9K 🔥`
1. [央视调查某茶饮品牌遭恶意抹黑始末](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E8%B0%83%E6%9F%A5%E6%9F%90%E8%8C%B6%E9%A5%AE%E5%93%81%E7%89%8C%E9%81%AD%E6%81%B6%E6%84%8F%E6%8A%B9%E9%BB%91%E5%A7%8B%E6%9C%AB%23) `124.0K 🔥`
1. [以前扮丑是真的扮丑](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%89%8D%E6%89%AE%E4%B8%91%E6%98%AF%E7%9C%9F%E7%9A%84%E6%89%AE%E4%B8%91%23) `120.8K 🔥`
1. [王橹杰的语音](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E7%9A%84%E8%AF%AD%E9%9F%B3%23) `111.4K 🔥`
1. [去年最狠的十个消费陷阱](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E5%B9%B4%E6%9C%80%E7%8B%A0%E7%9A%84%E5%8D%81%E4%B8%AA%E6%B6%88%E8%B4%B9%E9%99%B7%E9%98%B1%23) `105.9K 🔥`
1. [美宜佳致歉](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AE%9C%E4%BD%B3%E8%87%B4%E6%AD%89%23) `98.2K 🔥`
1. [鹿哈 凌达乐 (Lu Ha Ling Dale)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%20%E5%87%8C%E8%BE%BE%E4%B9%90%23) `83.9K 🔥`
1. [国色天香 何晟铭](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E8%89%B2%E5%A4%A9%E9%A6%99%20%E4%BD%95%E6%99%9F%E9%93%AD%23) `268.3K 🔥` `-26%`
1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `196.9K 🔥` `-22%`
1. [中美大模型谁找工作更厉害](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E7%BE%8E%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%B0%81%E6%89%BE%E5%B7%A5%E4%BD%9C%E6%9B%B4%E5%8E%89%E5%AE%B3%23) `193.7K 🔥` `-21%`
1. [逐玉开始单更了 (Zhuyu has started to update orders)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%80%E5%A7%8B%E5%8D%95%E6%9B%B4%E4%BA%86%23) `185.3K 🔥` `-44%`
1. [黑工厂制假天麻现场触目惊心 (The scene of counterfeit Gastrodia elata produced in a black factory is shocking)](https://s.weibo.com/weibo?q=%23%E9%BB%91%E5%B7%A5%E5%8E%82%E5%88%B6%E5%81%87%E5%A4%A9%E9%BA%BB%E7%8E%B0%E5%9C%BA%E8%A7%A6%E7%9B%AE%E6%83%8A%E5%BF%83%23) `182.3K 🔥` `-27%`
1. [江西九江发生岩降事故 3人死亡 (Three people died in a rockfall accident in Jiujiang, Jiangxi)](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E8%A5%BF%E4%B9%9D%E6%B1%9F%E5%8F%91%E7%94%9F%E5%B2%A9%E9%99%8D%E4%BA%8B%E6%95%85%203%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `180.6K 🔥` `-25%`
1. [七种千万不能吃的食物 (Seven foods you must not eat)](https://s.weibo.com/weibo?q=%23%E4%B8%83%E7%A7%8D%E5%8D%83%E4%B8%87%E4%B8%8D%E8%83%BD%E5%90%83%E7%9A%84%E9%A3%9F%E7%89%A9%23) `143.8K 🔥` `-37%`
1. [逐玉云合破50%](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%91%E5%90%88%E7%A0%B450%25%23) `136.3K 🔥` `-43%`
1. [北京WBG对战FPX.ZQ](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%ACWBG%E5%AF%B9%E6%88%98FPX.ZQ%23) `129.3K 🔥` `-45%`
1. [张凌赫田曦薇没有杀青合照](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%B2%A1%E6%9C%89%E6%9D%80%E9%9D%92%E5%90%88%E7%85%A7%23) `115.1K 🔥` `-34%`
1. [央视315晚会点名食品安全领域](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86315%E6%99%9A%E4%BC%9A%E7%82%B9%E5%90%8D%E9%A3%9F%E5%93%81%E5%AE%89%E5%85%A8%E9%A2%86%E5%9F%9F%23) `113.2K 🔥` `-21%`
1. [刘文祥刚爆火就塌房 (Liu Wenxiang's house collapsed just after the fire broke out)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E5%88%9A%E7%88%86%E7%81%AB%E5%B0%B1%E5%A1%8C%E6%88%BF%23) `110.2K 🔥` `-36%`
1. [温瑞博4比2张本智和](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9A4%E6%AF%942%E5%BC%A0%E6%9C%AC%E6%99%BA%E5%92%8C%23) `105.5K 🔥` `-36%`
1. [怪不得印度工业发达原来都是0成本 (No wonder India’s developed industry turns out to be zero cost)](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E5%8D%B0%E5%BA%A6%E5%B7%A5%E4%B8%9A%E5%8F%91%E8%BE%BE%E5%8E%9F%E6%9D%A5%E9%83%BD%E6%98%AF0%E6%88%90%E6%9C%AC%23) `100.3K 🔥` `-54%`
1. [保证前额叶健康太重要了](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E8%AF%81%E5%89%8D%E9%A2%9D%E5%8F%B6%E5%81%A5%E5%BA%B7%E5%A4%AA%E9%87%8D%E8%A6%81%E4%BA%86%23) `97.3K 🔥` `-21%`
1. [孔雪儿邓凯 接三搭](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E9%82%93%E5%87%AF%20%E6%8E%A5%E4%B8%89%E6%90%AD%23) `82.1K 🔥` `-23%`

Updated at 2026-03-15 18:52:27

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
