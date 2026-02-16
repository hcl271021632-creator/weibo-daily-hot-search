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

1. [鞠婧祎20万红包 (Ju Jingyi’s 200,000 red envelope)](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E20%E4%B8%87%E7%BA%A2%E5%8C%85%23) `10.5M 🔥` `NEW`
1. [口令红包](https://s.weibo.com/weibo?q=%23%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `3.9M 🔥` `NEW`
1. [话百家姓过中国年](https://s.weibo.com/weibo?q=%23%E8%AF%9D%E7%99%BE%E5%AE%B6%E5%A7%93%E8%BF%87%E4%B8%AD%E5%9B%BD%E5%B9%B4%23) `3.1M 🔥` `NEW`
1. [元宝红包雨](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%9D%E7%BA%A2%E5%8C%85%E9%9B%A8%23) `233.7K 🔥` `NEW`
1. [网民编造销冠遭同事下毒被罚](https://s.weibo.com/weibo?q=%23%E7%BD%91%E6%B0%91%E7%BC%96%E9%80%A0%E9%94%80%E5%86%A0%E9%81%AD%E5%90%8C%E4%BA%8B%E4%B8%8B%E6%AF%92%E8%A2%AB%E7%BD%9A%23) `229.3K 🔥` `NEW`
1. [红包雨](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E9%9B%A8%23) `208.7K 🔥` `NEW`
1. [陈哲远 15万红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%2015%E4%B8%87%E7%BA%A2%E5%8C%85%23) `206.3K 🔥` `NEW`
1. [年夜饭](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `198.6K 🔥` `NEW`
1. [蚂蚁阿福16.8红包春节还能领](https://s.weibo.com/weibo?q=%23%E8%9A%82%E8%9A%81%E9%98%BF%E7%A6%8F16.8%E7%BA%A2%E5%8C%85%E6%98%A5%E8%8A%82%E8%BF%98%E8%83%BD%E9%A2%86%23) `192.8K 🔥` `NEW`
1. [被王毅痛斥后日本急了](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%8E%8B%E6%AF%85%E7%97%9B%E6%96%A5%E5%90%8E%E6%97%A5%E6%9C%AC%E6%80%A5%E4%BA%86%23) `186.4K 🔥` `NEW`
1. [千问超级请客卡集卡仅剩一天 (There is only one day left for Qianwen Super Treat Card Collection)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E8%B6%85%E7%BA%A7%E8%AF%B7%E5%AE%A2%E5%8D%A1%E9%9B%86%E5%8D%A1%E4%BB%85%E5%89%A9%E4%B8%80%E5%A4%A9%23) `182.5K 🔥` `NEW`
1. [和平精英权威皮肤这一块](https://s.weibo.com/weibo?q=%23%E5%92%8C%E5%B9%B3%E7%B2%BE%E8%8B%B1%E6%9D%83%E5%A8%81%E7%9A%AE%E8%82%A4%E8%BF%99%E4%B8%80%E5%9D%97%23) `178.1K 🔥` `NEW`
1. [小伙带女友回家全家十几人列队欢迎](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%B8%A6%E5%A5%B3%E5%8F%8B%E5%9B%9E%E5%AE%B6%E5%85%A8%E5%AE%B6%E5%8D%81%E5%87%A0%E4%BA%BA%E5%88%97%E9%98%9F%E6%AC%A2%E8%BF%8E%23) `175.1K 🔥` `NEW`
1. [鞠婧祎工作室发图](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E5%B7%A5%E4%BD%9C%E5%AE%A4%E5%8F%91%E5%9B%BE%23) `171.2K 🔥` `NEW`
1. [Angelababy红包金额](https://s.weibo.com/weibo?q=%23Angelababy%E7%BA%A2%E5%8C%85%E9%87%91%E9%A2%9D%23) `167.4K 🔥` `NEW`
1. [金饰价格涨到1544元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E6%A0%BC%E6%B6%A8%E5%88%B01544%E5%85%83%23) `166.3K 🔥` `NEW`
1. [明星红包预约](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%E9%A2%84%E7%BA%A6%23) `162.4K 🔥` `NEW`
1. [省服 睡衣](https://s.weibo.com/weibo?q=%23%E7%9C%81%E6%9C%8D%20%E7%9D%A1%E8%A1%A3%23) `158.3K 🔥` `NEW`
1. [朱志鑫红包](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E7%BA%A2%E5%8C%85%23) `157.3K 🔥` `NEW`
1. [时代少年团马年楼晚节目单](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E9%A9%AC%E5%B9%B4%E6%A5%BC%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `150.8K 🔥` `NEW`
1. [谷爱凌刘梦婷携手出战决赛 (Gu Ailing and Liu Mengting join hands in the finals)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%88%98%E6%A2%A6%E5%A9%B7%E6%90%BA%E6%89%8B%E5%87%BA%E6%88%98%E5%86%B3%E8%B5%9B%23) `122.1K 🔥` `NEW`
1. [毛晓彤红包](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%99%93%E5%BD%A4%E7%BA%A2%E5%8C%85%23) `121.3K 🔥` `NEW`
1. [敖瑞鹏今晚还发红包时间不定](https://s.weibo.com/weibo?q=%23%E6%95%96%E7%91%9E%E9%B9%8F%E4%BB%8A%E6%99%9A%E8%BF%98%E5%8F%91%E7%BA%A2%E5%8C%85%E6%97%B6%E9%97%B4%E4%B8%8D%E5%AE%9A%23) `119.6K 🔥` `NEW`
1. [微信可以发金色朋友圈](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E5%8F%AF%E4%BB%A5%E5%8F%91%E9%87%91%E8%89%B2%E6%9C%8B%E5%8F%8B%E5%9C%88%23) `118.9K 🔥` `NEW`
1. [苏新皓红包](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E6%96%B0%E7%9A%93%E7%BA%A2%E5%8C%85%23) `118.3K 🔥` `NEW`
1. [过年必备饮品出现了](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%BF%85%E5%A4%87%E9%A5%AE%E5%93%81%E5%87%BA%E7%8E%B0%E4%BA%86%23) `118.2K 🔥` `NEW`
1. [周杰伦新专辑超过12首](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%E8%B6%85%E8%BF%8712%E9%A6%96%23) `118.2K 🔥` `NEW`
1. [抢红包](https://s.weibo.com/weibo?q=%23%E6%8A%A2%E7%BA%A2%E5%8C%85%23) `109.5K 🔥` `NEW`
1. [微博抓马](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E5%8D%9A%E6%8A%93%E9%A9%AC%23) `101.5K 🔥` `NEW`
1. [杨幂贺岁图](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%B4%BA%E5%B2%81%E5%9B%BE%23) `99.2K 🔥` `NEW`
1. [刘涛该叫妈妈还是叫姐姐 (Should Liu Tao be called mother or sister?)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B6%9B%E8%AF%A5%E5%8F%AB%E5%A6%88%E5%A6%88%E8%BF%98%E6%98%AF%E5%8F%AB%E5%A7%90%E5%A7%90%23) `98.8K 🔥` `NEW`
1. [库里将参加2027全明星三分大赛](https://s.weibo.com/weibo?q=%23%E5%BA%93%E9%87%8C%E5%B0%86%E5%8F%82%E5%8A%A02027%E5%85%A8%E6%98%8E%E6%98%9F%E4%B8%89%E5%88%86%E5%A4%A7%E8%B5%9B%23) `98.8K 🔥` `NEW`
1. [图兰朵计划 中介文字游戏](https://s.weibo.com/weibo?q=%23%E5%9B%BE%E5%85%B0%E6%9C%B5%E8%AE%A1%E5%88%92%20%E4%B8%AD%E4%BB%8B%E6%96%87%E5%AD%97%E6%B8%B8%E6%88%8F%23) `98.0K 🔥` `NEW`
1. [原来春联的C位是由横批决定的](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E6%98%A5%E8%81%94%E7%9A%84C%E4%BD%8D%E6%98%AF%E7%94%B1%E6%A8%AA%E6%89%B9%E5%86%B3%E5%AE%9A%E7%9A%84%23) `97.5K 🔥` `NEW`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `14.9M 🔥` `+8047%`
1. [迪奥开运红 (Dior Lucky Red)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E5%A5%A5%E5%BC%80%E8%BF%90%E7%BA%A2%23) `7.1M 🔥` `+2676%`
1. [除夕 (Lunar New Year's eve)](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%23) `221.3K 🔥`
1. [春晚大赏](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%A4%A7%E8%B5%8F%23) `193.9K 🔥`
1. [等白鹿红包](https://s.weibo.com/weibo?q=%23%E7%AD%89%E7%99%BD%E9%B9%BF%E7%BA%A2%E5%8C%85%23) `162.6K 🔥`
1. [白鹿红包没门槛](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E7%BA%A2%E5%8C%85%E6%B2%A1%E9%97%A8%E6%A7%9B%23) `121.7K 🔥`
1. [奥巴马称外星人的确存在 (Obama says aliens do exist)](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E5%B7%B4%E9%A9%AC%E7%A7%B0%E5%A4%96%E6%98%9F%E4%BA%BA%E7%9A%84%E7%A1%AE%E5%AD%98%E5%9C%A8%23) `120.9K 🔥`
1. [李亚鹏饮酒后83岁母亲开车接其回家](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BA%9A%E9%B9%8F%E9%A5%AE%E9%85%92%E5%90%8E83%E5%B2%81%E6%AF%8D%E4%BA%B2%E5%BC%80%E8%BD%A6%E6%8E%A5%E5%85%B6%E5%9B%9E%E5%AE%B6%23) `120.5K 🔥`
1. [陈星旭的红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%98%9F%E6%97%AD%E7%9A%84%E7%BA%A2%E5%8C%85%23) `120.3K 🔥`
1. [几杯辟谣去世 (Died after a few glasses of wine to refute rumors)](https://s.weibo.com/weibo?q=%23%E5%87%A0%E6%9D%AF%E8%BE%9F%E8%B0%A3%E5%8E%BB%E4%B8%96%23) `119.8K 🔥`
1. [祝绪丹口令红包](https://s.weibo.com/weibo?q=%23%E7%A5%9D%E7%BB%AA%E4%B8%B9%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `119.1K 🔥`
1. [楼晚](https://s.weibo.com/weibo?q=%23%E6%A5%BC%E6%99%9A%23) `118.2K 🔥`
1. [红包分组 (Red envelope grouping)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E5%88%86%E7%BB%84%23) `229.3K 🔥` `-91%`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `229.2K 🔥` `-89%`
1. [今天又要集体洗头了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E5%8F%88%E8%A6%81%E9%9B%86%E4%BD%93%E6%B4%97%E5%A4%B4%E4%BA%86%23) `223.2K 🔥` `-60%`
1. [春晚节目单](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `204.8K 🔥` `-91%`
1. [金色朋友圈怎么弄](https://s.weibo.com/weibo?q=%23%E9%87%91%E8%89%B2%E6%9C%8B%E5%8F%8B%E5%9C%88%E6%80%8E%E4%B9%88%E5%BC%84%23) `142.6K 🔥` `-42%`
1. [除夕文案](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%E6%96%87%E6%A1%88%23) `122.4K 🔥` `-39%`

Updated at 2026-02-16 13:13:04

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
