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

1. [据称伊朗革命卫队总司令和防长身亡 (Iran's Revolutionary Guard Commander-in-Chief and Defense Minister Reportedly Dead)](https://s.weibo.com/weibo?q=%23%E6%8D%AE%E7%A7%B0%E4%BC%8A%E6%9C%97%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E6%80%BB%E5%8F%B8%E4%BB%A4%E5%92%8C%E9%98%B2%E9%95%BF%E8%BA%AB%E4%BA%A1%23) `303.2K 🔥` `NEW`
1. [伊朗宣布战果](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%A3%E5%B8%83%E6%88%98%E6%9E%9C%23) `227.1K 🔥` `NEW`
1. [华人称伊朗断网全靠中国网络联系](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%BA%BA%E7%A7%B0%E4%BC%8A%E6%9C%97%E6%96%AD%E7%BD%91%E5%85%A8%E9%9D%A0%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BB%9C%E8%81%94%E7%B3%BB%23) `218.5K 🔥` `NEW`
1. [伊朗称大量美以导弹坠落境外](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%A4%A7%E9%87%8F%E7%BE%8E%E4%BB%A5%E5%AF%BC%E5%BC%B9%E5%9D%A0%E8%90%BD%E5%A2%83%E5%A4%96%23) `216.7K 🔥` `NEW`
1. [外交部回应美以打击伊朗](https://s.weibo.com/weibo?q=%23%E5%A4%96%E4%BA%A4%E9%83%A8%E5%9B%9E%E5%BA%94%E7%BE%8E%E4%BB%A5%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%23) `213.8K 🔥` `NEW`
1. [WTT](https://s.weibo.com/weibo?q=%23WTT%23) `212.4K 🔥` `NEW`
1. [伊朗致电警告6国别参与](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%87%B4%E7%94%B5%E8%AD%A6%E5%91%8A6%E5%9B%BD%E5%88%AB%E5%8F%82%E4%B8%8E%23) `208.4K 🔥` `NEW`
1. [时光与你都很甜2](https://s.weibo.com/weibo?q=%23%E6%97%B6%E5%85%89%E4%B8%8E%E4%BD%A0%E9%83%BD%E5%BE%88%E7%94%9C2%23) `208.2K 🔥` `NEW`
1. [伊朗反击画面曝光](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%8D%E5%87%BB%E7%94%BB%E9%9D%A2%E6%9B%9D%E5%85%89%23) `165.9K 🔥` `NEW`
1. [这居然是侯明昊的素颜](https://s.weibo.com/weibo?q=%23%E8%BF%99%E5%B1%85%E7%84%B6%E6%98%AF%E4%BE%AF%E6%98%8E%E6%98%8A%E7%9A%84%E7%B4%A0%E9%A2%9C%23) `156.5K 🔥` `NEW`
1. [五粮液回应董事长被查 (Wuliangye responded to the investigation of its chairman)](https://s.weibo.com/weibo?q=%23%E4%BA%94%E7%B2%AE%E6%B6%B2%E5%9B%9E%E5%BA%94%E8%91%A3%E4%BA%8B%E9%95%BF%E8%A2%AB%E6%9F%A5%23) `146.1K 🔥` `NEW`
1. [Uzi杯要来了](https://s.weibo.com/weibo?q=%23Uzi%E6%9D%AF%E8%A6%81%E6%9D%A5%E4%BA%86%23) `144.8K 🔥` `NEW`
1. [伊朗首都加油站排起长龙](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%8A%A0%E6%B2%B9%E7%AB%99%E6%8E%92%E8%B5%B7%E9%95%BF%E9%BE%99%23) `144.3K 🔥` `NEW`
1. [以色列防空掩体内有婴儿在哭](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E9%98%B2%E7%A9%BA%E6%8E%A9%E4%BD%93%E5%86%85%E6%9C%89%E5%A9%B4%E5%84%BF%E5%9C%A8%E5%93%AD%23) `121.5K 🔥` `NEW`
1. [陈垣宇3比4莫雷加德](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%9E%A3%E5%AE%873%E6%AF%944%E8%8E%AB%E9%9B%B7%E5%8A%A0%E5%BE%B7%23) `113.9K 🔥` `NEW`
1. [腰不好的人多去练练臀](https://s.weibo.com/weibo?q=%23%E8%85%B0%E4%B8%8D%E5%A5%BD%E7%9A%84%E4%BA%BA%E5%A4%9A%E5%8E%BB%E7%BB%83%E7%BB%83%E8%87%80%23) `113.3K 🔥` `NEW`
1. [伊朗袭击已致约200名美军伤亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%E5%B7%B2%E8%87%B4%E7%BA%A6200%E5%90%8D%E7%BE%8E%E5%86%9B%E4%BC%A4%E4%BA%A1%23) `1.0M 🔥` `+47%`
1. [镖人票房超越惊蛰无声](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E8%B6%85%E8%B6%8A%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `304.4K 🔥` `+140%`
1. [比尔盖茨出轨对象照片曝光](https://s.weibo.com/weibo?q=%23%E6%AF%94%E5%B0%94%E7%9B%96%E8%8C%A8%E5%87%BA%E8%BD%A8%E5%AF%B9%E8%B1%A1%E7%85%A7%E7%89%87%E6%9B%9D%E5%85%89%23) `228.6K 🔥` `+35%`
1. [五粮液](https://s.weibo.com/weibo?q=%23%E4%BA%94%E7%B2%AE%E6%B6%B2%23) `225.7K 🔥` `+65%`
1. [俄罗斯对美以袭击伊朗表态 (Russia expresses its stance on US-Israeli attack on Iran)](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%E5%AF%B9%E7%BE%8E%E4%BB%A5%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E8%A1%A8%E6%80%81%23) `218.6K 🔥` `+26%`
1. [以色列宣布袭击伊朗 (Israel announces attack on Iran)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%23) `5.5M 🔥`
1. [小米发布会](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E5%8F%91%E5%B8%83%E4%BC%9A%23) `1.4M 🔥`
1. [3月起一批国家标准开始实施 (A number of national standards will be implemented starting from March)](https://s.weibo.com/weibo?q=%233%E6%9C%88%E8%B5%B7%E4%B8%80%E6%89%B9%E5%9B%BD%E5%AE%B6%E6%A0%87%E5%87%86%E5%BC%80%E5%A7%8B%E5%AE%9E%E6%96%BD%23) `1.1M 🔥`
1. [美颜突然关掉吓得人一哆嗦](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E9%A2%9C%E7%AA%81%E7%84%B6%E5%85%B3%E6%8E%89%E5%90%93%E5%BE%97%E4%BA%BA%E4%B8%80%E5%93%86%E5%97%A6%23) `294.7K 🔥`
1. [五粮液董事长曾从钦被查](https://s.weibo.com/weibo?q=%23%E4%BA%94%E7%B2%AE%E6%B6%B2%E8%91%A3%E4%BA%8B%E9%95%BF%E6%9B%BE%E4%BB%8E%E9%92%A6%E8%A2%AB%E6%9F%A5%23) `272.1K 🔥`
1. [山姆520元巧克力降到99元 (Sam’s 520 yuan chocolate reduced to 99 yuan)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86520%E5%85%83%E5%B7%A7%E5%85%8B%E5%8A%9B%E9%99%8D%E5%88%B099%E5%85%83%23) `233.8K 🔥`
1. [杨紫董竹君造型直播 (Yang Zi and Dong Zhujun styling live broadcast)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E8%91%A3%E7%AB%B9%E5%90%9B%E9%80%A0%E5%9E%8B%E7%9B%B4%E6%92%AD%23) `229.6K 🔥`
1. [金价 (gold price)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `228.3K 🔥`
1. [伊朗一小学遭袭51人死60人伤 (Attack on primary school in Iran kills 51 people and injures 60 others)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%B0%8F%E5%AD%A6%E9%81%AD%E8%A2%AD51%E4%BA%BA%E6%AD%BB60%E4%BA%BA%E4%BC%A4%23) `227.9K 🔥`
1. [伊称将使用尖端神秘武器](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E7%A7%B0%E5%B0%86%E4%BD%BF%E7%94%A8%E5%B0%96%E7%AB%AF%E7%A5%9E%E7%A7%98%E6%AD%A6%E5%99%A8%23) `227.4K 🔥`
1. [椰树广告 擦边](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E6%A0%91%E5%B9%BF%E5%91%8A%20%E6%93%A6%E8%BE%B9%23) `226.7K 🔥`
1. [伊朗正在打击美国军事基地 (Iran is attacking US military bases)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%9C%A8%E6%89%93%E5%87%BB%E7%BE%8E%E5%9B%BD%E5%86%9B%E4%BA%8B%E5%9F%BA%E5%9C%B0%23) `226.0K 🔥`
1. [老铺黄金46.9万元金如意售空](https://s.weibo.com/weibo?q=%23%E8%80%81%E9%93%BA%E9%BB%84%E9%87%9146.9%E4%B8%87%E5%85%83%E9%87%91%E5%A6%82%E6%84%8F%E5%94%AE%E7%A9%BA%23) `225.5K 🔥`
1. [郝熠然好会魅](https://s.weibo.com/weibo?q=%23%E9%83%9D%E7%86%A0%E7%84%B6%E5%A5%BD%E4%BC%9A%E9%AD%85%23) `222.9K 🔥`
1. [伊朗与6国外长通话 (Iran held phone calls with foreign ministers of six countries)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8E6%E5%9B%BD%E5%A4%96%E9%95%BF%E9%80%9A%E8%AF%9D%23) `222.7K 🔥`
1. [男朋友送的草莓蛋糕第一次见](https://s.weibo.com/weibo?q=%23%E7%94%B7%E6%9C%8B%E5%8F%8B%E9%80%81%E7%9A%84%E8%8D%89%E8%8E%93%E8%9B%8B%E7%B3%95%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%A7%81%23) `220.5K 🔥`
1. [伊朗启动大规模军事行动 (Iran launches large-scale military operation)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%AF%E5%8A%A8%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%86%9B%E4%BA%8B%E8%A1%8C%E5%8A%A8%23) `218.5K 🔥`
1. [陈飞宇孙千换了情头](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E5%AD%99%E5%8D%83%E6%8D%A2%E4%BA%86%E6%83%85%E5%A4%B4%23) `216.9K 🔥`
1. [伊朗军方称总司令身体健康 (Iran's military says commander-in-chief is in good health)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%9B%E6%96%B9%E7%A7%B0%E6%80%BB%E5%8F%B8%E4%BB%A4%E8%BA%AB%E4%BD%93%E5%81%A5%E5%BA%B7%23) `203.7K 🔥`
1. [突然对1g黄金没概念了 (Suddenly I have no idea about 1g gold)](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E5%AF%B91g%E9%BB%84%E9%87%91%E6%B2%A1%E6%A6%82%E5%BF%B5%E4%BA%86%23) `144.3K 🔥`
1. [阿联酋迪拜响起爆炸声 (Explosions ring out in Dubai, United Arab Emirates)](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%81%94%E9%85%8B%E8%BF%AA%E6%8B%9C%E5%93%8D%E8%B5%B7%E7%88%86%E7%82%B8%E5%A3%B0%23) `142.4K 🔥`
1. [黄金连续上涨7个月了 (Gold has risen for 7 consecutive months)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E8%BF%9E%E7%BB%AD%E4%B8%8A%E6%B6%A87%E4%B8%AA%E6%9C%88%E4%BA%86%23) `139.1K 🔥`
1. [Prada全平台认领杨幂](https://s.weibo.com/weibo?q=%23Prada%E5%85%A8%E5%B9%B3%E5%8F%B0%E8%AE%A4%E9%A2%86%E6%9D%A8%E5%B9%82%23) `131.4K 🔥`
1. [丁禹兮MISTINE全球防晒代言人 (Ding Yuxi MISTINE Global Sunscreen Spokesperson)](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A6%B9%E5%85%AEMISTINE%E5%85%A8%E7%90%83%E9%98%B2%E6%99%92%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `1.0M 🔥` `-36%`
1. [伊朗摧毁美军雷达 (Iran destroys US military radar)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%91%A7%E6%AF%81%E7%BE%8E%E5%86%9B%E9%9B%B7%E8%BE%BE%23) `155.9K 🔥` `-28%`
1. [TOP专辑秒切](https://s.weibo.com/weibo?q=%23TOP%E4%B8%93%E8%BE%91%E7%A7%92%E5%88%87%23) `153.3K 🔥` `-38%`
1. [胡塞武装将恢复袭击以色列](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%A1%9E%E6%AD%A6%E8%A3%85%E5%B0%86%E6%81%A2%E5%A4%8D%E8%A2%AD%E5%87%BB%E4%BB%A5%E8%89%B2%E5%88%97%23) `138.3K 🔥` `-33%`
1. [孙颖莎vs早田希娜](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E6%97%A9%E7%94%B0%E5%B8%8C%E5%A8%9C%23) `112.6K 🔥` `-54%`
1. [胡塞武装导弹射向以色列](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%A1%9E%E6%AD%A6%E8%A3%85%E5%AF%BC%E5%BC%B9%E5%B0%84%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `111.0K 🔥` `-50%`

Updated at 2026-02-28 22:33:19

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
