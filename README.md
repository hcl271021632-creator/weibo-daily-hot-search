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

1. [两会 (two sessions)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `1.1M 🔥` `NEW`
1. [霸王茶姬口令](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `376.4K 🔥` `NEW`
1. [雷军2026两会准备5份建议](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B2026%E4%B8%A4%E4%BC%9A%E5%87%86%E5%A4%875%E4%BB%BD%E5%BB%BA%E8%AE%AE%23) `368.0K 🔥` `NEW`
1. [建议高速年度3000公里免费](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%AB%98%E9%80%9F%E5%B9%B4%E5%BA%A63000%E5%85%AC%E9%87%8C%E5%85%8D%E8%B4%B9%23) `359.7K 🔥` `NEW`
1. [EDG张钊](https://s.weibo.com/weibo?q=%23EDG%E5%BC%A0%E9%92%8A%23) `343.6K 🔥` `NEW`
1. [大妈攒金34年戴百克黄金逛珠宝城](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%A6%88%E6%94%92%E9%87%9134%E5%B9%B4%E6%88%B4%E7%99%BE%E5%85%8B%E9%BB%84%E9%87%91%E9%80%9B%E7%8F%A0%E5%AE%9D%E5%9F%8E%23) `315.4K 🔥` `NEW`
1. [法国派出航母](https://s.weibo.com/weibo?q=%23%E6%B3%95%E5%9B%BD%E6%B4%BE%E5%87%BA%E8%88%AA%E6%AF%8D%23) `308.9K 🔥` `NEW`
1. [全红婵在村里聚完餐骑车离开](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E5%9C%A8%E6%9D%91%E9%87%8C%E8%81%9A%E5%AE%8C%E9%A4%90%E9%AA%91%E8%BD%A6%E7%A6%BB%E5%BC%80%23) `301.1K 🔥` `NEW`
1. [何与刘些宁同款汤圆](https://s.weibo.com/weibo?q=%23%E4%BD%95%E4%B8%8E%E5%88%98%E4%BA%9B%E5%AE%81%E5%90%8C%E6%AC%BE%E6%B1%A4%E5%9C%86%23) `261.3K 🔥` `NEW`
1. [新款仰望U7首搭第二代刀片电池](https://s.weibo.com/weibo?q=%23%E6%96%B0%E6%AC%BE%E4%BB%B0%E6%9C%9BU7%E9%A6%96%E6%90%AD%E7%AC%AC%E4%BA%8C%E4%BB%A3%E5%88%80%E7%89%87%E7%94%B5%E6%B1%A0%23) `258.1K 🔥` `NEW`
1. [油价 (oil price)](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%23) `255.3K 🔥` `NEW`
1. [姐姐姐夫终于说开了](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%E7%BB%88%E4%BA%8E%E8%AF%B4%E5%BC%80%E4%BA%86%23) `250.8K 🔥` `NEW`
1. [男性感染HPV有哪些健康风险](https://s.weibo.com/weibo?q=%23%E7%94%B7%E6%80%A7%E6%84%9F%E6%9F%93HPV%E6%9C%89%E5%93%AA%E4%BA%9B%E5%81%A5%E5%BA%B7%E9%A3%8E%E9%99%A9%23) `236.1K 🔥` `NEW`
1. [黄金白银再直线拉升](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E5%86%8D%E7%9B%B4%E7%BA%BF%E6%8B%89%E5%8D%87%23) `233.0K 🔥` `NEW`
1. [伊朗遇难学生一个个墓穴让人心碎](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%81%87%E9%9A%BE%E5%AD%A6%E7%94%9F%E4%B8%80%E4%B8%AA%E4%B8%AA%E5%A2%93%E7%A9%B4%E8%AE%A9%E4%BA%BA%E5%BF%83%E7%A2%8E%23) `232.9K 🔥` `NEW`
1. [中国石油跌停](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E8%B7%8C%E5%81%9C%23) `232.8K 🔥` `NEW`
1. [霍尔木兹海峡十多艘油轮被炮弹击中](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%8D%81%E5%A4%9A%E8%89%98%E6%B2%B9%E8%BD%AE%E8%A2%AB%E7%82%AE%E5%BC%B9%E5%87%BB%E4%B8%AD%23) `231.7K 🔥` `NEW`
1. [阿里Qwen负责人宣布离开](https://s.weibo.com/weibo?q=%23%E9%98%BF%E9%87%8CQwen%E8%B4%9F%E8%B4%A3%E4%BA%BA%E5%AE%A3%E5%B8%83%E7%A6%BB%E5%BC%80%23) `220.5K 🔥` `NEW`
1. [贫血女子经期一次性拔6颗牙](https://s.weibo.com/weibo?q=%23%E8%B4%AB%E8%A1%80%E5%A5%B3%E5%AD%90%E7%BB%8F%E6%9C%9F%E4%B8%80%E6%AC%A1%E6%80%A7%E6%8B%946%E9%A2%97%E7%89%99%23) `184.4K 🔥` `NEW`
1. [汪东城方严正声明](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E4%B8%9C%E5%9F%8E%E6%96%B9%E4%B8%A5%E6%AD%A3%E5%A3%B0%E6%98%8E%23) `142.5K 🔥` `NEW`
1. [西班牙回应特朗普贸易威胁 (Spain responds to Trump trade threats)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E7%8F%AD%E7%89%99%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E8%B4%B8%E6%98%93%E5%A8%81%E8%83%81%23) `132.0K 🔥` `NEW`
1. [石油](https://s.weibo.com/weibo?q=%23%E7%9F%B3%E6%B2%B9%23) `130.8K 🔥` `NEW`
1. [IF椰子水股价连续大跌](https://s.weibo.com/weibo?q=%23IF%E6%A4%B0%E5%AD%90%E6%B0%B4%E8%82%A1%E4%BB%B7%E8%BF%9E%E7%BB%AD%E5%A4%A7%E8%B7%8C%23) `130.2K 🔥` `NEW`
1. [美假谈判真备战声誉扫地](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%81%87%E8%B0%88%E5%88%A4%E7%9C%9F%E5%A4%87%E6%88%98%E5%A3%B0%E8%AA%89%E6%89%AB%E5%9C%B0%23) `121.1K 🔥` `NEW`
1. [这些生活习惯可能给HPV可乘之机](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%BA%9B%E7%94%9F%E6%B4%BB%E4%B9%A0%E6%83%AF%E5%8F%AF%E8%83%BD%E7%BB%99HPV%E5%8F%AF%E4%B9%98%E4%B9%8B%E6%9C%BA%23) `121.1K 🔥` `NEW`
1. [伊媒称哈梅内伊之子被选为新任最高领袖](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E5%AA%92%E7%A7%B0%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E4%B9%8B%E5%AD%90%E8%A2%AB%E9%80%89%E4%B8%BA%E6%96%B0%E4%BB%BB%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%23) `120.5K 🔥` `NEW`
1. [谷爱凌法国晒照](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%B3%95%E5%9B%BD%E6%99%92%E7%85%A7%23) `120.4K 🔥` `NEW`
1. [腰果圣杯](https://s.weibo.com/weibo?q=%23%E8%85%B0%E6%9E%9C%E5%9C%A3%E6%9D%AF%23) `119.9K 🔥` `NEW`
1. [穆祉丞怼眼自拍](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%E6%80%BC%E7%9C%BC%E8%87%AA%E6%8B%8D%23) `119.6K 🔥` `NEW`
1. [苹果上调MacBookAir和Pro售价](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E4%B8%8A%E8%B0%83MacBookAir%E5%92%8CPro%E5%94%AE%E4%BB%B7%23) `119.2K 🔥` `NEW`
1. [刘耀文张真源卡点祝福宋亚轩 (Liu Yaowen and Zhang Zhenyuan congratulated Song Yaxuan)](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%80%80%E6%96%87%E5%BC%A0%E7%9C%9F%E6%BA%90%E5%8D%A1%E7%82%B9%E7%A5%9D%E7%A6%8F%E5%AE%8B%E4%BA%9A%E8%BD%A9%23) `119.1K 🔥` `NEW`
1. [BIGBANG今年将世巡](https://s.weibo.com/weibo?q=%23BIGBANG%E4%BB%8A%E5%B9%B4%E5%B0%86%E4%B8%96%E5%B7%A1%23) `119.0K 🔥` `NEW`
1. [康康赛后采访](https://s.weibo.com/weibo?q=%23%E5%BA%B7%E5%BA%B7%E8%B5%9B%E5%90%8E%E9%87%87%E8%AE%BF%23) `118.7K 🔥` `NEW`
1. [张小满严晓丹结局](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%B0%8F%E6%BB%A1%E4%B8%A5%E6%99%93%E4%B8%B9%E7%BB%93%E5%B1%80%23) `118.4K 🔥` `NEW`
1. [罗德里戈无缘世界杯](https://s.weibo.com/weibo?q=%23%E7%BD%97%E5%BE%B7%E9%87%8C%E6%88%88%E6%97%A0%E7%BC%98%E4%B8%96%E7%95%8C%E6%9D%AF%23) `118.3K 🔥` `NEW`
1. [中国石油发布公告 (PetroChina releases announcement)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E5%8F%91%E5%B8%83%E5%85%AC%E5%91%8A%23) `775.7K 🔥` `+48%`
1. [身体少抵抗 节后减重轻松达 (The body has less resistance and can easily lose weight after the holidays)](https://s.weibo.com/weibo?q=%23%E8%BA%AB%E4%BD%93%E5%B0%91%E6%8A%B5%E6%8A%97%20%E8%8A%82%E5%90%8E%E5%87%8F%E9%87%8D%E8%BD%BB%E6%9D%BE%E8%BE%BE%23) `356.1K 🔥` `+231%`
1. [2026全国两会这些看点值得关注](https://s.weibo.com/weibo?q=%232026%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%E8%BF%99%E4%BA%9B%E7%9C%8B%E7%82%B9%E5%80%BC%E5%BE%97%E5%85%B3%E6%B3%A8%23) `588.2K 🔥`
1. [12306回应乘客在高铁上用排插 (12306 responded to passengers using power strips on high-speed trains)](https://s.weibo.com/weibo?q=%2312306%E5%9B%9E%E5%BA%94%E4%B9%98%E5%AE%A2%E5%9C%A8%E9%AB%98%E9%93%81%E4%B8%8A%E7%94%A8%E6%8E%92%E6%8F%92%23) `355.6K 🔥` `-52%`
1. [人大代表建议元宵节重阳节放假](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E5%BB%BA%E8%AE%AE%E5%85%83%E5%AE%B5%E8%8A%82%E9%87%8D%E9%98%B3%E8%8A%82%E6%94%BE%E5%81%87%23) `337.0K 🔥` `-36%`
1. [王毅要求以方确保中国人员机构安全 (Wang Yi requires Israel to ensure the safety of Chinese personnel and institutions)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%AF%85%E8%A6%81%E6%B1%82%E4%BB%A5%E6%96%B9%E7%A1%AE%E4%BF%9D%E4%B8%AD%E5%9B%BD%E4%BA%BA%E5%91%98%E6%9C%BA%E6%9E%84%E5%AE%89%E5%85%A8%23) `332.9K 🔥` `-35%`
1. [伊朗导弹击中美第五舰队总部瞬间](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%87%BB%E4%B8%AD%E7%BE%8E%E7%AC%AC%E4%BA%94%E8%88%B0%E9%98%9F%E6%80%BB%E9%83%A8%E7%9E%AC%E9%97%B4%23) `324.2K 🔥` `-38%`
1. [山姆1.38公斤冰块卖37.9元](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%861.38%E5%85%AC%E6%96%A4%E5%86%B0%E5%9D%97%E5%8D%9637.9%E5%85%83%23) `132.3K 🔥` `-75%`
1. [EDG](https://s.weibo.com/weibo?q=%23EDG%23) `120.8K 🔥` `-77%`
1. [伦敦机场18小时未进食求助女子发声 (Woman at London Airport asks for help after not eating for 18 hours)](https://s.weibo.com/weibo?q=%23%E4%BC%A6%E6%95%A6%E6%9C%BA%E5%9C%BA18%E5%B0%8F%E6%97%B6%E6%9C%AA%E8%BF%9B%E9%A3%9F%E6%B1%82%E5%8A%A9%E5%A5%B3%E5%AD%90%E5%8F%91%E5%A3%B0%23) `120.7K 🔥` `-77%`
1. [赵今麦吃了好多汤圆 (Zhao Jinmai ate a lot of glutinous rice balls)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%BB%8A%E9%BA%A6%E5%90%83%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%A4%E5%9C%86%23) `120.2K 🔥` `-77%`
1. [麦当劳CEO试吃自家汉堡 (McDonald's CEO tastes his own burger)](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E8%AF%95%E5%90%83%E8%87%AA%E5%AE%B6%E6%B1%89%E5%A0%A1%23) `120.0K 🔥` `-76%`
1. [妻子要离婚丈夫要求返还10万元彩礼 (Wife wants divorce, husband demands return of 100,000 yuan gift)](https://s.weibo.com/weibo?q=%23%E5%A6%BB%E5%AD%90%E8%A6%81%E7%A6%BB%E5%A9%9A%E4%B8%88%E5%A4%AB%E8%A6%81%E6%B1%82%E8%BF%94%E8%BF%9810%E4%B8%87%E5%85%83%E5%BD%A9%E7%A4%BC%23) `119.7K 🔥` `-77%`
1. [金智秀 迪奥公主 (Kim Ji Soo Princess Dior)](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%99%BA%E7%A7%80%20%E8%BF%AA%E5%A5%A5%E5%85%AC%E4%B8%BB%23) `119.4K 🔥` `-77%`
1. [中国驻迪拜总领馆发布特别提醒 (The Chinese Consulate General in Dubai issues a special reminder)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%A9%BB%E8%BF%AA%E6%8B%9C%E6%80%BB%E9%A2%86%E9%A6%86%E5%8F%91%E5%B8%83%E7%89%B9%E5%88%AB%E6%8F%90%E9%86%92%23) `118.6K 🔥` `-89%`

Updated at 2026-03-04 10:45:16

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
