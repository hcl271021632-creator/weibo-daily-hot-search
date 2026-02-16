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

1. [梁洁红包 (Liang Jie red envelope)](https://s.weibo.com/weibo?q=%23%E6%A2%81%E6%B4%81%E7%BA%A2%E5%8C%85%23) `160.7K 🔥` `NEW`
1. [喵娲娲发30万红包](https://s.weibo.com/weibo?q=%23%E5%96%B5%E5%A8%B2%E5%A8%B2%E5%8F%9130%E4%B8%87%E7%BA%A2%E5%8C%85%23) `137.0K 🔥` `NEW`
1. [孟子义 先发美图再发红包](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%20%E5%85%88%E5%8F%91%E7%BE%8E%E5%9B%BE%E5%86%8D%E5%8F%91%E7%BA%A2%E5%8C%85%23) `135.3K 🔥` `NEW`
1. [遇到不认识的亲戚我就这样](https://s.weibo.com/weibo?q=%23%E9%81%87%E5%88%B0%E4%B8%8D%E8%AE%A4%E8%AF%86%E7%9A%84%E4%BA%B2%E6%88%9A%E6%88%91%E5%B0%B1%E8%BF%99%E6%A0%B7%23) `128.4K 🔥` `NEW`
1. [过年背着妈妈点外卖](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E8%83%8C%E7%9D%80%E5%A6%88%E5%A6%88%E7%82%B9%E5%A4%96%E5%8D%96%23) `128.2K 🔥` `NEW`
1. [以旅行见新年](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E6%97%85%E8%A1%8C%E8%A7%81%E6%96%B0%E5%B9%B4%23) `128.0K 🔥` `NEW`
1. [敖瑞鹏发红包还有前菜](https://s.weibo.com/weibo?q=%23%E6%95%96%E7%91%9E%E9%B9%8F%E5%8F%91%E7%BA%A2%E5%8C%85%E8%BF%98%E6%9C%89%E5%89%8D%E8%8F%9C%23) `127.4K 🔥` `NEW`
1. [否认南京大屠杀的日本酒店老板死了](https://s.weibo.com/weibo?q=%23%E5%90%A6%E8%AE%A4%E5%8D%97%E4%BA%AC%E5%A4%A7%E5%B1%A0%E6%9D%80%E7%9A%84%E6%97%A5%E6%9C%AC%E9%85%92%E5%BA%97%E8%80%81%E6%9D%BF%E6%AD%BB%E4%BA%86%23) `127.2K 🔥` `NEW`
1. [迪丽热巴春晚跳舞](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%98%A5%E6%99%9A%E8%B7%B3%E8%88%9E%23) `125.7K 🔥` `NEW`
1. [今年春晚机器人有好多节目](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E6%98%A5%E6%99%9A%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%9C%89%E5%A5%BD%E5%A4%9A%E8%8A%82%E7%9B%AE%23) `125.6K 🔥` `NEW`
1. [沈腾马丽微电影 (Shen Teng and Ma Li's micro movie)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E9%A9%AC%E4%B8%BD%E5%BE%AE%E7%94%B5%E5%BD%B1%23) `125.0K 🔥` `NEW`
1. [黄景瑜红包](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E7%BA%A2%E5%8C%85%23) `124.7K 🔥` `NEW`
1. [你的骑手正在和外卖箱打架](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E7%9A%84%E9%AA%91%E6%89%8B%E6%AD%A3%E5%9C%A8%E5%92%8C%E5%A4%96%E5%8D%96%E7%AE%B1%E6%89%93%E6%9E%B6%23) `124.5K 🔥` `NEW`
1. [春晚小品](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%B0%8F%E5%93%81%23) `123.5K 🔥` `NEW`
1. [余承恩红包](https://s.weibo.com/weibo?q=%23%E4%BD%99%E6%89%BF%E6%81%A9%E7%BA%A2%E5%8C%85%23) `123.4K 🔥` `NEW`
1. [装修不能相信任何一个师傅](https://s.weibo.com/weibo?q=%23%E8%A3%85%E4%BF%AE%E4%B8%8D%E8%83%BD%E7%9B%B8%E4%BF%A1%E4%BB%BB%E4%BD%95%E4%B8%80%E4%B8%AA%E5%B8%88%E5%82%85%23) `123.2K 🔥` `NEW`
1. [短剧妹和小说妹打入春晚内部](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E5%A6%B9%E5%92%8C%E5%B0%8F%E8%AF%B4%E5%A6%B9%E6%89%93%E5%85%A5%E6%98%A5%E6%99%9A%E5%86%85%E9%83%A8%23) `122.9K 🔥` `NEW`
1. [易烊千玺9登春晚](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA9%E7%99%BB%E6%98%A5%E6%99%9A%23) `122.3K 🔥` `NEW`
1. [麻将鸡蛋](https://s.weibo.com/weibo?q=%23%E9%BA%BB%E5%B0%86%E9%B8%A1%E8%9B%8B%23) `120.6K 🔥` `NEW`
1. [魏晨刘宇宁许我再少年](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E6%99%A8%E5%88%98%E5%AE%87%E5%AE%81%E8%AE%B8%E6%88%91%E5%86%8D%E5%B0%91%E5%B9%B4%23) `111.5K 🔥` `NEW`
1. [孙颖莎祝大家春节快乐 (Sun Yingsha wishes everyone a happy Spring Festival)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E7%A5%9D%E5%A4%A7%E5%AE%B6%E6%98%A5%E8%8A%82%E5%BF%AB%E4%B9%90%23) `110.4K 🔥` `NEW`
1. [秦海璐春晚妆造精致到美甲](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E6%B5%B7%E7%92%90%E6%98%A5%E6%99%9A%E5%A6%86%E9%80%A0%E7%B2%BE%E8%87%B4%E5%88%B0%E7%BE%8E%E7%94%B2%23) `110.1K 🔥` `NEW`
1. [汪苏泷红包](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E7%BA%A2%E5%8C%85%23) `107.1K 🔥` `NEW`
1. [狗狗在主人摸它时会提前把耳朵放下](https://s.weibo.com/weibo?q=%23%E7%8B%97%E7%8B%97%E5%9C%A8%E4%B8%BB%E4%BA%BA%E6%91%B8%E5%AE%83%E6%97%B6%E4%BC%9A%E6%8F%90%E5%89%8D%E6%8A%8A%E8%80%B3%E6%9C%B5%E6%94%BE%E4%B8%8B%23) `107.1K 🔥` `NEW`
1. [春晚节目单](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `6.1M 🔥` `+2161%`
1. [千问红包](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E7%BA%A2%E5%8C%85%23) `2.4M 🔥` `+948%`
1. [支付宝集福红包今晚22点18开奖 (Alipay lucky red envelope lottery draw tonight at 22:18)](https://s.weibo.com/weibo?q=%23%E6%94%AF%E4%BB%98%E5%AE%9D%E9%9B%86%E7%A6%8F%E7%BA%A2%E5%8C%85%E4%BB%8A%E6%99%9A22%E7%82%B918%E5%BC%80%E5%A5%96%23) `2.1M 🔥` `+726%`
1. [爷错了 别哭了](https://s.weibo.com/weibo?q=%23%E7%88%B7%E9%94%99%E4%BA%86%20%E5%88%AB%E5%93%AD%E4%BA%86%23) `184.3K 🔥` `+36%`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `10.3M 🔥`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `214.8K 🔥`
1. [深圳除夕当天租男友3000元一天](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E9%99%A4%E5%A4%95%E5%BD%93%E5%A4%A9%E7%A7%9F%E7%94%B7%E5%8F%8B3000%E5%85%83%E4%B8%80%E5%A4%A9%23) `164.5K 🔥`
1. [红包分组 (Red envelope grouping)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E5%88%86%E7%BB%84%23) `162.4K 🔥`
1. [雷军换头像](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E6%8D%A2%E5%A4%B4%E5%83%8F%23) `126.4K 🔥`
1. [林孝埈孙龙刘少昂除夕出战 (Lin Xiaojuan, Sun Long and Liu Shao'ang play on New Year's Eve)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E5%AD%99%E9%BE%99%E5%88%98%E5%B0%91%E6%98%82%E9%99%A4%E5%A4%95%E5%87%BA%E6%88%98%23) `122.6K 🔥`
1. [田曦薇春晚洋娃娃](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E6%98%A5%E6%99%9A%E6%B4%8B%E5%A8%83%E5%A8%83%23) `122.5K 🔥`
1. [话百家姓过中国年](https://s.weibo.com/weibo?q=%23%E8%AF%9D%E7%99%BE%E5%AE%B6%E5%A7%93%E8%BF%87%E4%B8%AD%E5%9B%BD%E5%B9%B4%23) `1.9M 🔥` `-39%`
1. [口令红包](https://s.weibo.com/weibo?q=%23%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `221.8K 🔥` `-24%`
1. [鞠婧祎20万红包 (Ju Jingyi’s 200,000 red envelope)](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E20%E4%B8%87%E7%BA%A2%E5%8C%85%23) `210.8K 🔥` `-96%`
1. [今天又要集体洗头了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E5%8F%88%E8%A6%81%E9%9B%86%E4%BD%93%E6%B4%97%E5%A4%B4%E4%BA%86%23) `165.6K 🔥` `-33%`
1. [年夜饭](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `158.3K 🔥` `-21%`
1. [除夕 (Lunar New Year's eve)](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%23) `156.7K 🔥` `-23%`
1. [春晚大赏](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%A4%A7%E8%B5%8F%23) `127.7K 🔥` `-36%`
1. [张凌赫 七个红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E4%B8%83%E4%B8%AA%E7%BA%A2%E5%8C%85%23) `127.0K 🔥` `-35%`
1. [周翊然红包 (Zhou Yiran red envelope)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E7%BF%8A%E7%84%B6%E7%BA%A2%E5%8C%85%23) `126.5K 🔥` `-98%`
1. [祝绪丹口令红包](https://s.weibo.com/weibo?q=%23%E7%A5%9D%E7%BB%AA%E4%B8%B9%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `126.4K 🔥` `-31%`
1. [陈哲远 15万红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%2015%E4%B8%87%E7%BA%A2%E5%8C%85%23) `125.9K 🔥` `-34%`
1. [被王毅痛斥后日本急了 (Japan is anxious after being reprimanded by Wang Yi)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%8E%8B%E6%AF%85%E7%97%9B%E6%96%A5%E5%90%8E%E6%97%A5%E6%9C%AC%E6%80%A5%E4%BA%86%23) `125.2K 🔥` `-36%`
1. [等白鹿红包](https://s.weibo.com/weibo?q=%23%E7%AD%89%E7%99%BD%E9%B9%BF%E7%BA%A2%E5%8C%85%23) `124.4K 🔥` `-36%`
1. [Angelababy红包金额](https://s.weibo.com/weibo?q=%23Angelababy%E7%BA%A2%E5%8C%85%E9%87%91%E9%A2%9D%23) `124.1K 🔥` `-34%`
1. [红包雨](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E9%9B%A8%23) `123.9K 🔥` `-97%`
1. [明星红包预约](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%E9%A2%84%E7%BA%A6%23) `120.3K 🔥` `-31%`

Updated at 2026-02-16 15:33:47

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
