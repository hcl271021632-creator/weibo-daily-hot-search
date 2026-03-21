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

1. [官方辟谣重庆野温泉传播艾滋 (Officials refute rumors that wild hot springs in Chongqing spread AIDS)](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E8%BE%9F%E8%B0%A3%E9%87%8D%E5%BA%86%E9%87%8E%E6%B8%A9%E6%B3%89%E4%BC%A0%E6%92%AD%E8%89%BE%E6%BB%8B%23) `418.4K 🔥` `NEW`
1. [斗破苍穹](https://s.weibo.com/weibo?q=%23%E6%96%97%E7%A0%B4%E8%8B%8D%E7%A9%B9%23) `417.8K 🔥` `NEW`
1. [迪丽热巴好闪好辣](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%A5%BD%E9%97%AA%E5%A5%BD%E8%BE%A3%23) `244.8K 🔥` `NEW`
1. [黄霄雲 莫挨老子](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%9C%84%E9%9B%B2%20%E8%8E%AB%E6%8C%A8%E8%80%81%E5%AD%90%23) `244.2K 🔥` `NEW`
1. [伊朗手中握有真正的筹码](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%89%8B%E4%B8%AD%E6%8F%A1%E6%9C%89%E7%9C%9F%E6%AD%A3%E7%9A%84%E7%AD%B9%E7%A0%81%23) `237.2K 🔥` `NEW`
1. [十年前妈妈自己设计装修的家](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%B9%B4%E5%89%8D%E5%A6%88%E5%A6%88%E8%87%AA%E5%B7%B1%E8%AE%BE%E8%AE%A1%E8%A3%85%E4%BF%AE%E7%9A%84%E5%AE%B6%23) `121.4K 🔥` `NEW`
1. [樊长玉斩杀长信王](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E6%96%A9%E6%9D%80%E9%95%BF%E4%BF%A1%E7%8E%8B%23) `92.5K 🔥` `NEW`
1. [伊朗军方放话全球追猎](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%9B%E6%96%B9%E6%94%BE%E8%AF%9D%E5%85%A8%E7%90%83%E8%BF%BD%E7%8C%8E%23) `92.2K 🔥` `NEW`
1. [云旗走秀造型](https://s.weibo.com/weibo?q=%23%E4%BA%91%E6%97%97%E8%B5%B0%E7%A7%80%E9%80%A0%E5%9E%8B%23) `86.6K 🔥` `NEW`
1. [中国女排超级联赛](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E6%8E%92%E8%B6%85%E7%BA%A7%E8%81%94%E8%B5%9B%23) `71.7K 🔥` `NEW`
1. [季冠霖发文抵制AI (Ji Guanlin issued a letter boycotting AI)](https://s.weibo.com/weibo?q=%23%E5%AD%A3%E5%86%A0%E9%9C%96%E5%8F%91%E6%96%87%E6%8A%B5%E5%88%B6AI%23) `68.3K 🔥` `NEW`
1. [中国新能源汽车再提速](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%96%B0%E8%83%BD%E6%BA%90%E6%B1%BD%E8%BD%A6%E5%86%8D%E6%8F%90%E9%80%9F%23) `68.0K 🔥` `NEW`
1. [防弹少年团新专](https://s.weibo.com/weibo?q=%23%E9%98%B2%E5%BC%B9%E5%B0%91%E5%B9%B4%E5%9B%A2%E6%96%B0%E4%B8%93%23) `67.6K 🔥` `NEW`
1. [伊朗凌晨打击以色列军事设施](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%87%8C%E6%99%A8%E6%89%93%E5%87%BB%E4%BB%A5%E8%89%B2%E5%88%97%E5%86%9B%E4%BA%8B%E8%AE%BE%E6%96%BD%23) `67.2K 🔥` `NEW`
1. [霍尔木兹海峡关闭或长达6个月](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%85%B3%E9%97%AD%E6%88%96%E9%95%BF%E8%BE%BE6%E4%B8%AA%E6%9C%88%23) `418.6K 🔥` `+24%`
1. [软软的水 脆脆的水](https://s.weibo.com/weibo?q=%23%E8%BD%AF%E8%BD%AF%E7%9A%84%E6%B0%B4%20%E8%84%86%E8%84%86%E7%9A%84%E6%B0%B4%23) `418.3K 🔥` `+22%`
1. [美军核坟墓辐射量已超切尔诺贝利 (The amount of radiation in the US military's nuclear grave has exceeded that of Chernobyl)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E6%A0%B8%E5%9D%9F%E5%A2%93%E8%BE%90%E5%B0%84%E9%87%8F%E5%B7%B2%E8%B6%85%E5%88%87%E5%B0%94%E8%AF%BA%E8%B4%9D%E5%88%A9%23) `418.3K 🔥` `+28%`
1. [90后男子为降血糖自制汤药身亡](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E7%94%B7%E5%AD%90%E4%B8%BA%E9%99%8D%E8%A1%80%E7%B3%96%E8%87%AA%E5%88%B6%E6%B1%A4%E8%8D%AF%E8%BA%AB%E4%BA%A1%23) `417.9K 🔥` `+33%`
1. [月经弄脏卧铺当事人详述事件经过](https://s.weibo.com/weibo?q=%23%E6%9C%88%E7%BB%8F%E5%BC%84%E8%84%8F%E5%8D%A7%E9%93%BA%E5%BD%93%E4%BA%8B%E4%BA%BA%E8%AF%A6%E8%BF%B0%E4%BA%8B%E4%BB%B6%E7%BB%8F%E8%BF%87%23) `417.6K 🔥` `+39%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `417.6K 🔥` `+41%`
1. [梅姨拐卖的儿童认亲后将母亲拉黑](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E6%8B%90%E5%8D%96%E7%9A%84%E5%84%BF%E7%AB%A5%E8%AE%A4%E4%BA%B2%E5%90%8E%E5%B0%86%E6%AF%8D%E4%BA%B2%E6%8B%89%E9%BB%91%23) `267.8K 🔥` `+63%`
1. [梅姨长相与公布画像相似度不高 (Aunt Mei’s appearance is not very similar to the published portrait)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E9%95%BF%E7%9B%B8%E4%B8%8E%E5%85%AC%E5%B8%83%E7%94%BB%E5%83%8F%E7%9B%B8%E4%BC%BC%E5%BA%A6%E4%B8%8D%E9%AB%98%23) `255.4K 🔥` `+50%`
1. [金饰价格已下跌超300元 (The price of gold jewelry has dropped by more than 300 yuan)](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E6%A0%BC%E5%B7%B2%E4%B8%8B%E8%B7%8C%E8%B6%85300%E5%85%83%23) `254.6K 🔥` `+42%`
1. [伊朗有意日本船只通行霍尔木兹海峡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%89%E6%84%8F%E6%97%A5%E6%9C%AC%E8%88%B9%E5%8F%AA%E9%80%9A%E8%A1%8C%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `253.9K 🔥` `+37%`
1. [JDG对战DYG](https://s.weibo.com/weibo?q=%23JDG%E5%AF%B9%E6%88%98DYG%23) `252.4K 🔥` `+283%`
1. [鹿晗 关晓彤 (Lu Han Guan Xiaotong)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `252.2K 🔥` `+136%`
1. [曝迪丽热巴新经纪人入职嘉行](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%96%B0%E7%BB%8F%E7%BA%AA%E4%BA%BA%E5%85%A5%E8%81%8C%E5%98%89%E8%A1%8C%23) `250.5K 🔥` `+136%`
1. [白象 土豆泥火鸡面 (White Elephant Mashed Potato Turkey Noodles)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E8%B1%A1%20%E5%9C%9F%E8%B1%86%E6%B3%A5%E7%81%AB%E9%B8%A1%E9%9D%A2%23) `249.4K 🔥` `+138%`
1. [痞幼因网红身份被邻居排挤 (A young boy is ostracized by his neighbors because of his status as an internet celebrity)](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%9B%A0%E7%BD%91%E7%BA%A2%E8%BA%AB%E4%BB%BD%E8%A2%AB%E9%82%BB%E5%B1%85%E6%8E%92%E6%8C%A4%23) `248.9K 🔥` `+139%`
1. [曝梁小龙去世两个月没下葬将停棺10年](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%A2%81%E5%B0%8F%E9%BE%99%E5%8E%BB%E4%B8%96%E4%B8%A4%E4%B8%AA%E6%9C%88%E6%B2%A1%E4%B8%8B%E8%91%AC%E5%B0%86%E5%81%9C%E6%A3%BA10%E5%B9%B4%23) `248.1K 🔥` `+143%`
1. [梅姨落网是申聪的新婚贺礼](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E8%90%BD%E7%BD%91%E6%98%AF%E7%94%B3%E8%81%AA%E7%9A%84%E6%96%B0%E5%A9%9A%E8%B4%BA%E7%A4%BC%23) `245.2K 🔥` `+151%`
1. [张凌赫田曦薇 所有人都在觊觎我妻子](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%20%E6%89%80%E6%9C%89%E4%BA%BA%E9%83%BD%E5%9C%A8%E8%A7%8A%E8%A7%8E%E6%88%91%E5%A6%BB%E5%AD%90%23) `232.3K 🔥` `+124%`
1. [张凌赫男大自拍 (Zhang Linghe male selfie)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B7%E5%A4%A7%E8%87%AA%E6%8B%8D%23) `187.9K 🔥` `+88%`
1. [小黄豆去看蔡徐坤](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%BB%84%E8%B1%86%E5%8E%BB%E7%9C%8B%E8%94%A1%E5%BE%90%E5%9D%A4%23) `101.2K 🔥` `+28%`
1. [杜小华曾跪求梅姨同居者提供线索](https://s.weibo.com/weibo?q=%23%E6%9D%9C%E5%B0%8F%E5%8D%8E%E6%9B%BE%E8%B7%AA%E6%B1%82%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E8%80%85%E6%8F%90%E4%BE%9B%E7%BA%BF%E7%B4%A2%23) `72.2K 🔥` `+21%`
1. [梅姨被逮捕 (Aunt May was arrested)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E8%A2%AB%E9%80%AE%E6%8D%95%23) `1.2M 🔥`
1. [梅姨同居男友都看不到她的身份证](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E7%94%B7%E5%8F%8B%E9%83%BD%E7%9C%8B%E4%B8%8D%E5%88%B0%E5%A5%B9%E7%9A%84%E8%BA%AB%E4%BB%BD%E8%AF%81%23) `864.4K 🔥`
1. [总会被一棵树的张力震撼到 (I will always be shocked by the tension of a tree)](https://s.weibo.com/weibo?q=%23%E6%80%BB%E4%BC%9A%E8%A2%AB%E4%B8%80%E6%A3%B5%E6%A0%91%E7%9A%84%E5%BC%A0%E5%8A%9B%E9%9C%87%E6%92%BC%E5%88%B0%23) `678.5K 🔥`
1. [什么是减压深睡裤 (What are pressure relief pajamas?)](https://s.weibo.com/weibo?q=%23%E4%BB%80%E4%B9%88%E6%98%AF%E5%87%8F%E5%8E%8B%E6%B7%B1%E7%9D%A1%E8%A3%A4%23) `504.5K 🔥`
1. [梅姨同居男友说她不戴首饰 (Aunt Mei’s live-in boyfriend said she doesn’t wear jewelry)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E7%94%B7%E5%8F%8B%E8%AF%B4%E5%A5%B9%E4%B8%8D%E6%88%B4%E9%A6%96%E9%A5%B0%23) `418.8K 🔥`
1. [女子熬夜3个月突然开始对墙讲课 (Woman stayed up late for 3 months and suddenly started lecturing against the wall)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%86%AC%E5%A4%9C3%E4%B8%AA%E6%9C%88%E7%AA%81%E7%84%B6%E5%BC%80%E5%A7%8B%E5%AF%B9%E5%A2%99%E8%AE%B2%E8%AF%BE%23) `418.7K 🔥`
1. [老师为什么能发现家长签名是假的](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E8%83%BD%E5%8F%91%E7%8E%B0%E5%AE%B6%E9%95%BF%E7%AD%BE%E5%90%8D%E6%98%AF%E5%81%87%E7%9A%84%23) `321.0K 🔥`
1. [梅姨曾与60多岁老人同居2年 (Aunt Mei once lived with an old man in his 60s for 2 years)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E6%9B%BE%E4%B8%8E60%E5%A4%9A%E5%B2%81%E8%80%81%E4%BA%BA%E5%90%8C%E5%B1%852%E5%B9%B4%23) `257.5K 🔥`
1. [杨家鑫被梅姨拐走爸爸跳火车身亡](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%AE%B6%E9%91%AB%E8%A2%AB%E6%A2%85%E5%A7%A8%E6%8B%90%E8%B5%B0%E7%88%B8%E7%88%B8%E8%B7%B3%E7%81%AB%E8%BD%A6%E8%BA%AB%E4%BA%A1%23) `256.8K 🔥`
1. [逐玉男配剧播后平均涨粉百万](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%94%B7%E9%85%8D%E5%89%A7%E6%92%AD%E5%90%8E%E5%B9%B3%E5%9D%87%E6%B6%A8%E7%B2%89%E7%99%BE%E4%B8%87%23) `92.1K 🔥`
1. [做饭2小时吃饭10分钟](https://s.weibo.com/weibo?q=%23%E5%81%9A%E9%A5%AD2%E5%B0%8F%E6%97%B6%E5%90%83%E9%A5%AD10%E5%88%86%E9%92%9F%23) `78.9K 🔥`
1. [马嘉祺无框眼镜贵公子 (Ma Jiaqi rimless glasses noble man)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%98%89%E7%A5%BA%E6%97%A0%E6%A1%86%E7%9C%BC%E9%95%9C%E8%B4%B5%E5%85%AC%E5%AD%90%23) `69.6K 🔥`
1. [刘宇宁直播](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E7%9B%B4%E6%92%AD%23) `76.4K 🔥` `-23%`
1. [小学生校门口买小火龙后中毒](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A6%E7%94%9F%E6%A0%A1%E9%97%A8%E5%8F%A3%E4%B9%B0%E5%B0%8F%E7%81%AB%E9%BE%99%E5%90%8E%E4%B8%AD%E6%AF%92%23) `72.8K 🔥` `-29%`
1. [GW对战Xteam](https://s.weibo.com/weibo?q=%23GW%E5%AF%B9%E6%88%98Xteam%23) `70.2K 🔥` `-78%`
1. [梅姨贩卖孩子能力有多强](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E8%B4%A9%E5%8D%96%E5%AD%A9%E5%AD%90%E8%83%BD%E5%8A%9B%E6%9C%89%E5%A4%9A%E5%BC%BA%23) `69.9K 🔥` `-26%`
1. [霸王茶姬口令](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `69.0K 🔥` `-35%`

Updated at 2026-03-21 19:00:05

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
