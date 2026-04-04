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

1. [王曼昱vs桥本帆乃香 (Wang Manyu vs Hashimoto Honoka)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1vs%E6%A1%A5%E6%9C%AC%E5%B8%86%E4%B9%83%E9%A6%99%23) `1.1M 🔥` `NEW`
1. [张慧雯整个大E人](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%85%A7%E9%9B%AF%E6%95%B4%E4%B8%AA%E5%A4%A7E%E4%BA%BA%23) `807.8K 🔥` `NEW`
1. [张月505票](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9C%88505%E7%A5%A8%23) `459.5K 🔥` `NEW`
1. [徐梦洁没选安崎](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%B4%81%E6%B2%A1%E9%80%89%E5%AE%89%E5%B4%8E%23) `250.5K 🔥` `NEW`
1. [男子骑车途中电池爆燃妻子全身烧伤](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%AA%91%E8%BD%A6%E9%80%94%E4%B8%AD%E7%94%B5%E6%B1%A0%E7%88%86%E7%87%83%E5%A6%BB%E5%AD%90%E5%85%A8%E8%BA%AB%E7%83%A7%E4%BC%A4%23) `196.2K 🔥` `NEW`
1. [徐梦洁 不太好听](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%B4%81%20%E4%B8%8D%E5%A4%AA%E5%A5%BD%E5%90%AC%23) `195.4K 🔥` `NEW`
1. [萧蔷 上古神登](https://s.weibo.com/weibo?q=%23%E8%90%A7%E8%94%B7%20%E4%B8%8A%E5%8F%A4%E7%A5%9E%E7%99%BB%23) `194.7K 🔥` `NEW`
1. [浪姐第二场和第一场不是一个节目](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E7%AC%AC%E4%BA%8C%E5%9C%BA%E5%92%8C%E7%AC%AC%E4%B8%80%E5%9C%BA%E4%B8%8D%E6%98%AF%E4%B8%80%E4%B8%AA%E8%8A%82%E7%9B%AE%23) `192.0K 🔥` `NEW`
1. [周杰伦被粉丝说演唱会划水一小时](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E8%A2%AB%E7%B2%89%E4%B8%9D%E8%AF%B4%E6%BC%94%E5%94%B1%E4%BC%9A%E5%88%92%E6%B0%B4%E4%B8%80%E5%B0%8F%E6%97%B6%23) `190.0K 🔥` `NEW`
1. [清明假期叠加春假激发经济新活力](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E5%8F%A0%E5%8A%A0%E6%98%A5%E5%81%87%E6%BF%80%E5%8F%91%E7%BB%8F%E6%B5%8E%E6%96%B0%E6%B4%BB%E5%8A%9B%23) `185.5K 🔥` `NEW`
1. [萧蔷 不一定要逐玉但要逐梦 (Xiao Qiang, you don’t have to chase jade, but you have to chase dreams)](https://s.weibo.com/weibo?q=%23%E8%90%A7%E8%94%B7%20%E4%B8%8D%E4%B8%80%E5%AE%9A%E8%A6%81%E9%80%90%E7%8E%89%E4%BD%86%E8%A6%81%E9%80%90%E6%A2%A6%23) `182.2K 🔥` `NEW`
1. [陈凯琳 完全芭比来的](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%87%AF%E7%90%B3%20%E5%AE%8C%E5%85%A8%E8%8A%AD%E6%AF%94%E6%9D%A5%E7%9A%84%23) `181.1K 🔥` `NEW`
1. [王皓快哭了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%9A%93%E5%BF%AB%E5%93%AD%E4%BA%86%23) `180.0K 🔥` `NEW`
1. [张凌赫脱稿演讲六分半的含金量](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%84%B1%E7%A8%BF%E6%BC%94%E8%AE%B2%E5%85%AD%E5%88%86%E5%8D%8A%E7%9A%84%E5%90%AB%E9%87%91%E9%87%8F%23) `179.9K 🔥` `NEW`
1. [WB止步季后赛四强](https://s.weibo.com/weibo?q=%23WB%E6%AD%A2%E6%AD%A5%E5%AD%A3%E5%90%8E%E8%B5%9B%E5%9B%9B%E5%BC%BA%23) `172.4K 🔥` `NEW`
1. [王皓疯狂庆祝](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%9A%93%E7%96%AF%E7%8B%82%E5%BA%86%E7%A5%9D%23) `154.1K 🔥` `NEW`
1. [伊朗称击中美军黑鹰直升机](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%87%BB%E4%B8%AD%E7%BE%8E%E5%86%9B%E9%BB%91%E9%B9%B0%E7%9B%B4%E5%8D%87%E6%9C%BA%23) `138.9K 🔥` `NEW`
1. [芒果去买够爱版权吧](https://s.weibo.com/weibo?q=%23%E8%8A%92%E6%9E%9C%E5%8E%BB%E4%B9%B0%E5%A4%9F%E7%88%B1%E7%89%88%E6%9D%83%E5%90%A7%23) `129.4K 🔥` `NEW`
1. [王曼昱13比11桥本帆乃香](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B113%E6%AF%9411%E6%A1%A5%E6%9C%AC%E5%B8%86%E4%B9%83%E9%A6%99%23) `126.0K 🔥` `NEW`
1. [谢娜要开演唱会了吗](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E8%A6%81%E5%BC%80%E6%BC%94%E5%94%B1%E4%BC%9A%E4%BA%86%E5%90%97%23) `125.7K 🔥` `NEW`
1. [王曼昱11比8桥本帆乃香 (Wang Manyu 11 to 8 Hashimoto Honoka)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B111%E6%AF%948%E6%A1%A5%E6%9C%AC%E5%B8%86%E4%B9%83%E9%A6%99%23) `119.1K 🔥` `NEW`
1. [中国散户3月以来净买入1.25万亿](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%95%A3%E6%88%B73%E6%9C%88%E4%BB%A5%E6%9D%A5%E5%87%80%E4%B9%B0%E5%85%A51.25%E4%B8%87%E4%BA%BF%23) `108.1K 🔥` `NEW`
1. [我欲乘风](https://s.weibo.com/weibo?q=%23%E6%88%91%E6%AC%B2%E4%B9%98%E9%A3%8E%23) `104.7K 🔥` `NEW`
1. [我国过敏性鼻炎患者数量攀升](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E8%BF%87%E6%95%8F%E6%80%A7%E9%BC%BB%E7%82%8E%E6%82%A3%E8%80%85%E6%95%B0%E9%87%8F%E6%94%80%E5%8D%87%23) `103.6K 🔥` `NEW`
1. [王楚钦大心脏](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%A4%A7%E5%BF%83%E8%84%8F%23) `103.3K 🔥` `NEW`
1. [莫氏鸡煲周边商户发声](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%B0%8F%E9%B8%A1%E7%85%B2%E5%91%A8%E8%BE%B9%E5%95%86%E6%88%B7%E5%8F%91%E5%A3%B0%23) `254.0K 🔥` `+122%`
1. [王楚钦撕掉肌贴](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E6%92%95%E6%8E%89%E8%82%8C%E8%B4%B4%23) `243.9K 🔥` `+39%`
1. [曝熊黛林做全职妈妈后被老公嫌弃](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%86%8A%E9%BB%9B%E6%9E%97%E5%81%9A%E5%85%A8%E8%81%8C%E5%A6%88%E5%A6%88%E5%90%8E%E8%A2%AB%E8%80%81%E5%85%AC%E5%AB%8C%E5%BC%83%23) `187.2K 🔥` `+35%`
1. [WB对战KSG (WB vs. KSG)](https://s.weibo.com/weibo?q=%23WB%E5%AF%B9%E6%88%98KSG%23) `184.0K 🔥` `+100%`
1. [致敬缅怀奋进 (Pay tribute and remember Endeavor)](https://s.weibo.com/weibo?q=%23%E8%87%B4%E6%95%AC%E7%BC%85%E6%80%80%E5%A5%8B%E8%BF%9B%23) `663.8K 🔥`
1. [酒店员工提醒小孩别玩门家长报警](https://s.weibo.com/weibo?q=%23%E9%85%92%E5%BA%97%E5%91%98%E5%B7%A5%E6%8F%90%E9%86%92%E5%B0%8F%E5%AD%A9%E5%88%AB%E7%8E%A9%E9%97%A8%E5%AE%B6%E9%95%BF%E6%8A%A5%E8%AD%A6%23) `196.9K 🔥`
1. [中俄法反对武力打通霍尔木兹海峡](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BF%84%E6%B3%95%E5%8F%8D%E5%AF%B9%E6%AD%A6%E5%8A%9B%E6%89%93%E9%80%9A%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `194.2K 🔥`
1. [伊朗驻华大使馆发布战果 (The Iranian Embassy in China released the results of the battle)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A9%BB%E5%8D%8E%E5%A4%A7%E4%BD%BF%E9%A6%86%E5%8F%91%E5%B8%83%E6%88%98%E6%9E%9C%23) `187.9K 🔥`
1. [瞿颖 我上个世纪还是顶流的时候 (Qu Ying, when I was at the top in the last century)](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%20%E6%88%91%E4%B8%8A%E4%B8%AA%E4%B8%96%E7%BA%AA%E8%BF%98%E6%98%AF%E9%A1%B6%E6%B5%81%E7%9A%84%E6%97%B6%E5%80%99%23) `167.3K 🔥`
1. [田曦薇嫁金钗杀青](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%AB%81%E9%87%91%E9%92%97%E6%9D%80%E9%9D%92%23) `160.6K 🔥`
1. [虞书欣签售妆是一枝南南画的](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E7%AD%BE%E5%94%AE%E5%A6%86%E6%98%AF%E4%B8%80%E6%9E%9D%E5%8D%97%E5%8D%97%E7%94%BB%E7%9A%84%23) `153.2K 🔥`
1. [淡淡不愧是舞台总监](https://s.weibo.com/weibo?q=%23%E6%B7%A1%E6%B7%A1%E4%B8%8D%E6%84%A7%E6%98%AF%E8%88%9E%E5%8F%B0%E6%80%BB%E7%9B%91%23) `134.8K 🔥`
1. [虞书欣晒签售会plog (Yu Shuxin posted the log of the book signing event)](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%99%92%E7%AD%BE%E5%94%AE%E4%BC%9Aplog%23) `125.8K 🔥`
1. [嫁金钗](https://s.weibo.com/weibo?q=%23%E5%AB%81%E9%87%91%E9%92%97%23) `118.6K 🔥`
1. [鞠婧祎露芜衣夕阳下跳舞](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E9%9C%B2%E8%8A%9C%E8%A1%A3%E5%A4%95%E9%98%B3%E4%B8%8B%E8%B7%B3%E8%88%9E%23) `103.4K 🔥`
1. [无人继承的巨额遗产或在拖垮日本](https://s.weibo.com/weibo?q=%23%E6%97%A0%E4%BA%BA%E7%BB%A7%E6%89%BF%E7%9A%84%E5%B7%A8%E9%A2%9D%E9%81%97%E4%BA%A7%E6%88%96%E5%9C%A8%E6%8B%96%E5%9E%AE%E6%97%A5%E6%9C%AC%23) `103.4K 🔥`
1. [红果多部短剧AI角色撞脸易烊千玺 (The AI ​​characters in Hongguo's many short dramas collide with Yi Yang Qianxi's face)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E6%9E%9C%E5%A4%9A%E9%83%A8%E7%9F%AD%E5%89%A7AI%E8%A7%92%E8%89%B2%E6%92%9E%E8%84%B8%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%23) `103.3K 🔥`
1. [陈幸同0比11申裕斌 (Chen Xingtong 0-11 Shen Yubin)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%B9%B8%E5%90%8C0%E6%AF%9411%E7%94%B3%E8%A3%95%E6%96%8C%23) `196.9K 🔥` `-41%`
1. [王楚钦晋级四强](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E6%99%8B%E7%BA%A7%E5%9B%9B%E5%BC%BA%23) `183.7K 🔥` `-56%`
1. [王楚钦vs约奇克](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E7%BA%A6%E5%A5%87%E5%85%8B%23) `108.4K 🔥` `-88%`
1. [进价15元镜片竟卖799元](https://s.weibo.com/weibo?q=%23%E8%BF%9B%E4%BB%B715%E5%85%83%E9%95%9C%E7%89%87%E7%AB%9F%E5%8D%96799%E5%85%83%23) `104.8K 🔥` `-31%`
1. [徐洁儿张月原地成团 (Xu Jieer and Zhang Yue formed a group on the spot)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%B4%81%E5%84%BF%E5%BC%A0%E6%9C%88%E5%8E%9F%E5%9C%B0%E6%88%90%E5%9B%A2%23) `104.3K 🔥` `-51%`
1. [淡淡舞台 完全女团](https://s.weibo.com/weibo?q=%23%E6%B7%A1%E6%B7%A1%E8%88%9E%E5%8F%B0%20%E5%AE%8C%E5%85%A8%E5%A5%B3%E5%9B%A2%23) `104.1K 🔥` `-48%`
1. [瞿颖太好笑了](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E5%A4%AA%E5%A5%BD%E7%AC%91%E4%BA%86%23) `103.8K 🔥` `-34%`
1. [广东仅珠海仍全域禁止电动自行车 (Only Zhuhai in Guangdong still bans electric bicycles)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E4%BB%85%E7%8F%A0%E6%B5%B7%E4%BB%8D%E5%85%A8%E5%9F%9F%E7%A6%81%E6%AD%A2%E7%94%B5%E5%8A%A8%E8%87%AA%E8%A1%8C%E8%BD%A6%23) `103.3K 🔥` `-25%`

Updated at 2026-04-04 21:56:33

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
