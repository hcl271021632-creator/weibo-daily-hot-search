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

1. [王濛说签生死状复出 (Wang Meng said he would sign a life and death certificate to come back)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E8%AF%B4%E7%AD%BE%E7%94%9F%E6%AD%BB%E7%8A%B6%E5%A4%8D%E5%87%BA%23) `812.5K 🔥` `NEW`
1. [王濛现场观赛生气了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E7%8E%B0%E5%9C%BA%E8%A7%82%E8%B5%9B%E7%94%9F%E6%B0%94%E4%BA%86%23) `591.0K 🔥` `NEW`
1. [49岁女子为吸粉用AI造谣险情被拘](https://s.weibo.com/weibo?q=%2349%E5%B2%81%E5%A5%B3%E5%AD%90%E4%B8%BA%E5%90%B8%E7%B2%89%E7%94%A8AI%E9%80%A0%E8%B0%A3%E9%99%A9%E6%83%85%E8%A2%AB%E6%8B%98%23) `288.2K 🔥` `NEW`
1. [老一辈起情侣名没轻没重](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%B8%80%E8%BE%88%E8%B5%B7%E6%83%85%E4%BE%A3%E5%90%8D%E6%B2%A1%E8%BD%BB%E6%B2%A1%E9%87%8D%23) `284.5K 🔥` `NEW`
1. [霍启刚还是忍不住秀恩爱](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%90%AF%E5%88%9A%E8%BF%98%E6%98%AF%E5%BF%8D%E4%B8%8D%E4%BD%8F%E7%A7%80%E6%81%A9%E7%88%B1%23) `283.5K 🔥` `NEW`
1. [方大同才二十三MV](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%A4%A7%E5%90%8C%E6%89%8D%E4%BA%8C%E5%8D%81%E4%B8%89MV%23) `263.5K 🔥` `NEW`
1. [一觉醒来特朗普改新打法了](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%A7%89%E9%86%92%E6%9D%A5%E7%89%B9%E6%9C%97%E6%99%AE%E6%94%B9%E6%96%B0%E6%89%93%E6%B3%95%E4%BA%86%23) `258.1K 🔥` `NEW`
1. [贝加尔湖事故](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E4%BA%8B%E6%95%85%23) `250.8K 🔥` `NEW`
1. [苏翊鸣回复徐梦桃小鸣酱随500](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%9B%9E%E5%A4%8D%E5%BE%90%E6%A2%A6%E6%A1%83%E5%B0%8F%E9%B8%A3%E9%85%B1%E9%9A%8F500%23) `232.8K 🔥` `NEW`
1. [林孝埈接受韩媒采访回应无奖牌](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E6%8E%A5%E5%8F%97%E9%9F%A9%E5%AA%92%E9%87%87%E8%AE%BF%E5%9B%9E%E5%BA%94%E6%97%A0%E5%A5%96%E7%89%8C%23) `155.9K 🔥` `NEW`
1. [妈祖被替小女孩回应 (Mazu was answered on behalf of the little girl)](https://s.weibo.com/weibo?q=%23%E5%A6%88%E7%A5%96%E8%A2%AB%E6%9B%BF%E5%B0%8F%E5%A5%B3%E5%AD%A9%E5%9B%9E%E5%BA%94%23) `154.3K 🔥` `NEW`
1. [当我问亲戚们存了多少钱](https://s.weibo.com/weibo?q=%23%E5%BD%93%E6%88%91%E9%97%AE%E4%BA%B2%E6%88%9A%E4%BB%AC%E5%AD%98%E4%BA%86%E5%A4%9A%E5%B0%91%E9%92%B1%23) `151.4K 🔥` `NEW`
1. [黄景瑜演技](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E6%BC%94%E6%8A%80%23) `137.0K 🔥` `NEW`
1. [金度勋疑似骚扰女艺人](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%BA%A6%E5%8B%8B%E7%96%91%E4%BC%BC%E9%AA%9A%E6%89%B0%E5%A5%B3%E8%89%BA%E4%BA%BA%23) `136.9K 🔥` `NEW`
1. [为什么各地初五迎的财神不一样](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E5%90%84%E5%9C%B0%E5%88%9D%E4%BA%94%E8%BF%8E%E7%9A%84%E8%B4%A2%E7%A5%9E%E4%B8%8D%E4%B8%80%E6%A0%B7%23) `135.8K 🔥` `NEW`
1. [郭富城透露方媛和岳父母香港过年](https://s.weibo.com/weibo?q=%23%E9%83%AD%E5%AF%8C%E5%9F%8E%E9%80%8F%E9%9C%B2%E6%96%B9%E5%AA%9B%E5%92%8C%E5%B2%B3%E7%88%B6%E6%AF%8D%E9%A6%99%E6%B8%AF%E8%BF%87%E5%B9%B4%23) `135.7K 🔥` `NEW`
1. [22岁小伙长发大波浪被外甥叫阿姨](https://s.weibo.com/weibo?q=%2322%E5%B2%81%E5%B0%8F%E4%BC%99%E9%95%BF%E5%8F%91%E5%A4%A7%E6%B3%A2%E6%B5%AA%E8%A2%AB%E5%A4%96%E7%94%A5%E5%8F%AB%E9%98%BF%E5%A7%A8%23) `135.5K 🔥` `NEW`
1. [巧克力生煎](https://s.weibo.com/weibo?q=%23%E5%B7%A7%E5%85%8B%E5%8A%9B%E7%94%9F%E7%85%8E%23) `120.6K 🔥` `NEW`
1. [王濛不是说遗憾就是滑得太难看](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E4%B8%8D%E6%98%AF%E8%AF%B4%E9%81%97%E6%86%BE%E5%B0%B1%E6%98%AF%E6%BB%91%E5%BE%97%E5%A4%AA%E9%9A%BE%E7%9C%8B%23) `115.6K 🔥` `NEW`
1. [谷爱凌李方慧等U型场地冲金](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%9D%8E%E6%96%B9%E6%85%A7%E7%AD%89U%E5%9E%8B%E5%9C%BA%E5%9C%B0%E5%86%B2%E9%87%91%23) `107.5K 🔥` `NEW`
1. [孙颖莎红温 (Sun Yingsha Hongwen)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E7%BA%A2%E6%B8%A9%23) `91.9K 🔥` `NEW`
1. [泡泡玛特创始人送小酒窝盲盒](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E6%B3%A1%E7%8E%9B%E7%89%B9%E5%88%9B%E5%A7%8B%E4%BA%BA%E9%80%81%E5%B0%8F%E9%85%92%E7%AA%9D%E7%9B%B2%E7%9B%92%23) `91.8K 🔥` `NEW`
1. [飞驰人生3五天破20亿](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E4%BA%94%E5%A4%A9%E7%A0%B420%E4%BA%BF%23) `90.5K 🔥` `NEW`
1. [中国代表重申日本没资格要求入常](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BB%A3%E8%A1%A8%E9%87%8D%E7%94%B3%E6%97%A5%E6%9C%AC%E6%B2%A1%E8%B5%84%E6%A0%BC%E8%A6%81%E6%B1%82%E5%85%A5%E5%B8%B8%23) `87.3K 🔥` `NEW`
1. [王心迪是哈工大力学专业在读博士生](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%BF%83%E8%BF%AA%E6%98%AF%E5%93%88%E5%B7%A5%E5%A4%A7%E5%8A%9B%E5%AD%A6%E4%B8%93%E4%B8%9A%E5%9C%A8%E8%AF%BB%E5%8D%9A%E5%A3%AB%E7%94%9F%23) `86.3K 🔥` `NEW`
1. [王濛直播](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E7%9B%B4%E6%92%AD%23) `79.4K 🔥` `NEW`
1. [曹颖回应卖房争议](https://s.weibo.com/weibo?q=%23%E6%9B%B9%E9%A2%96%E5%9B%9E%E5%BA%94%E5%8D%96%E6%88%BF%E4%BA%89%E8%AE%AE%23) `74.3K 🔥` `NEW`
1. [俄方公布贝加尔湖救援现场视频](https://s.weibo.com/weibo?q=%23%E4%BF%84%E6%96%B9%E5%85%AC%E5%B8%83%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E6%95%91%E6%8F%B4%E7%8E%B0%E5%9C%BA%E8%A7%86%E9%A2%91%23) `73.2K 🔥` `NEW`
1. [中国队比冠军还快](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E6%AF%94%E5%86%A0%E5%86%9B%E8%BF%98%E5%BF%AB%23) `70.3K 🔥` `NEW`
1. [白宫确认终止部分关税措施](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%AB%E7%A1%AE%E8%AE%A4%E7%BB%88%E6%AD%A2%E9%83%A8%E5%88%86%E5%85%B3%E7%A8%8E%E6%8E%AA%E6%96%BD%23) `69.5K 🔥` `NEW`
1. [浙江人赚钱敏感度有多高 (How sensitive are Zhejiang people to making money?)](https://s.weibo.com/weibo?q=%23%E6%B5%99%E6%B1%9F%E4%BA%BA%E8%B5%9A%E9%92%B1%E6%95%8F%E6%84%9F%E5%BA%A6%E6%9C%89%E5%A4%9A%E9%AB%98%23) `65.1K 🔥` `NEW`
1. [男子称医院未采取急救措施致妻子死亡](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%A7%B0%E5%8C%BB%E9%99%A2%E6%9C%AA%E9%87%87%E5%8F%96%E6%80%A5%E6%95%91%E6%8E%AA%E6%96%BD%E8%87%B4%E5%A6%BB%E5%AD%90%E6%AD%BB%E4%BA%A1%23) `64.3K 🔥` `NEW`
1. [美最大航母进入地中海](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E6%9C%80%E5%A4%A7%E8%88%AA%E6%AF%8D%E8%BF%9B%E5%85%A5%E5%9C%B0%E4%B8%AD%E6%B5%B7%23) `61.2K 🔥` `NEW`
1. [不让江山](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%23) `60.9K 🔥` `NEW`
1. [美最大核动力航母进入地中海](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E6%9C%80%E5%A4%A7%E6%A0%B8%E5%8A%A8%E5%8A%9B%E8%88%AA%E6%AF%8D%E8%BF%9B%E5%85%A5%E5%9C%B0%E4%B8%AD%E6%B5%B7%23) `60.3K 🔥` `NEW`
1. [一家人在武林大会认识的吧](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B6%E4%BA%BA%E5%9C%A8%E6%AD%A6%E6%9E%97%E5%A4%A7%E4%BC%9A%E8%AE%A4%E8%AF%86%E7%9A%84%E5%90%A7%23) `58.4K 🔥` `NEW`
1. [前教练回应王心迪夺金](https://s.weibo.com/weibo?q=%23%E5%89%8D%E6%95%99%E7%BB%83%E5%9B%9E%E5%BA%94%E7%8E%8B%E5%BF%83%E8%BF%AA%E5%A4%BA%E9%87%91%23) `58.0K 🔥` `NEW`
1. [京东健康祝天下父母身体健康 (JD Health wishes parents all over the world good health)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7%E7%A5%9D%E5%A4%A9%E4%B8%8B%E7%88%B6%E6%AF%8D%E8%BA%AB%E4%BD%93%E5%81%A5%E5%BA%B7%23) `653.0K 🔥` `+999%`
1. [那艺娜劣迹艺人 (Na Yina's evil artist)](https://s.weibo.com/weibo?q=%23%E9%82%A3%E8%89%BA%E5%A8%9C%E5%8A%A3%E8%BF%B9%E8%89%BA%E4%BA%BA%23) `645.6K 🔥` `+498%`
1. [正月初五接财神 (Receive the God of Wealth on the fifth day of the first lunar month)](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E6%9C%88%E5%88%9D%E4%BA%94%E6%8E%A5%E8%B4%A2%E7%A5%9E%23) `338.2K 🔥` `+104%`
1. [沈娇娇是个眼圆脸圆的甜妹](https://s.weibo.com/weibo?q=%23%E6%B2%88%E5%A8%87%E5%A8%87%E6%98%AF%E4%B8%AA%E7%9C%BC%E5%9C%86%E8%84%B8%E5%9C%86%E7%9A%84%E7%94%9C%E5%A6%B9%23) `272.9K 🔥` `+24%`
1. [这种致癌物在春节很常见](https://s.weibo.com/weibo?q=%23%E8%BF%99%E7%A7%8D%E8%87%B4%E7%99%8C%E7%89%A9%E5%9C%A8%E6%98%A5%E8%8A%82%E5%BE%88%E5%B8%B8%E8%A7%81%23) `136.3K 🔥` `+27%`
1. [财神壁纸](https://s.weibo.com/weibo?q=%23%E8%B4%A2%E7%A5%9E%E5%A3%81%E7%BA%B8%23) `128.0K 🔥` `+76%`
1. [白鹿孟子义李昀锐拼好剧 又争又抢 (White Deer, Meng Ziyi and Li Yunrui fight for a good drama and fight for it)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E6%8B%BC%E5%A5%BD%E5%89%A7%20%E5%8F%88%E4%BA%89%E5%8F%88%E6%8A%A2%23) `91.8K 🔥` `+78%`
1. [将门独后 (The only one left behind)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `58.5K 🔥` `+28%`
1. [黄金白银飙涨](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E9%A3%99%E6%B6%A8%23) `58.0K 🔥` `+40%`
1. [迎财神 (Welcome the God of Wealth)](https://s.weibo.com/weibo?q=%23%E8%BF%8E%E8%B4%A2%E7%A5%9E%23) `1.1M 🔥`
1. [中国非遗给你亿点点震撼 (China’s intangible cultural heritage will shock you a little bit)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%9D%9E%E9%81%97%E7%BB%99%E4%BD%A0%E4%BA%BF%E7%82%B9%E7%82%B9%E9%9C%87%E6%92%BC%23) `654.4K 🔥`
1. [将门毒后不是大ip是巨ip (After Jiangmen was poisoned, it was not a big IP but a giant IP.)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%E4%B8%8D%E6%98%AF%E5%A4%A7ip%E6%98%AF%E5%B7%A8ip%23) `131.6K 🔥`
1. [五路财神](https://s.weibo.com/weibo?q=%23%E4%BA%94%E8%B7%AF%E8%B4%A2%E7%A5%9E%23) `86.4K 🔥`
1. [金吉莉1500米金牌](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%90%89%E8%8E%891500%E7%B1%B3%E9%87%91%E7%89%8C%23) `96.3K 🔥` `-88%`
1. [将门独后 天崩开局](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%20%E5%A4%A9%E5%B4%A9%E5%BC%80%E5%B1%80%23) `63.6K 🔥` `-41%`

Updated at 2026-02-21 10:40:16

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
