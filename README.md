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

1. [伊朗一小学遭袭51人死60人伤 (Attack on primary school in Iran kills 51 people and injures 60 others)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%B0%8F%E5%AD%A6%E9%81%AD%E8%A2%AD51%E4%BA%BA%E6%AD%BB60%E4%BA%BA%E4%BC%A4%23) `915.7K 🔥` `NEW`
1. [TOP专辑秒切](https://s.weibo.com/weibo?q=%23TOP%E4%B8%93%E8%BE%91%E7%A7%92%E5%88%87%23) `524.5K 🔥` `NEW`
1. [年后复工就看笑街回血](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%90%8E%E5%A4%8D%E5%B7%A5%E5%B0%B1%E7%9C%8B%E7%AC%91%E8%A1%97%E5%9B%9E%E8%A1%80%23) `468.0K 🔥` `NEW`
1. [陈飞宇孙千换了情头](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E5%AD%99%E5%8D%83%E6%8D%A2%E4%BA%86%E6%83%85%E5%A4%B4%23) `264.3K 🔥` `NEW`
1. [伊朗摧毁美军雷达](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%91%A7%E6%AF%81%E7%BE%8E%E5%86%9B%E9%9B%B7%E8%BE%BE%23) `263.7K 🔥` `NEW`
1. [胡塞武装将恢复袭击以色列](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%A1%9E%E6%AD%A6%E8%A3%85%E5%B0%86%E6%81%A2%E5%A4%8D%E8%A2%AD%E5%87%BB%E4%BB%A5%E8%89%B2%E5%88%97%23) `263.6K 🔥` `NEW`
1. [老铺黄金46.9万元金如意售空](https://s.weibo.com/weibo?q=%23%E8%80%81%E9%93%BA%E9%BB%84%E9%87%9146.9%E4%B8%87%E5%85%83%E9%87%91%E5%A6%82%E6%84%8F%E5%94%AE%E7%A9%BA%23) `245.5K 🔥` `NEW`
1. [谷爱凌苏翊鸣徐梦桃王心迪合照](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%BE%90%E6%A2%A6%E6%A1%83%E7%8E%8B%E5%BF%83%E8%BF%AA%E5%90%88%E7%85%A7%23) `245.3K 🔥` `NEW`
1. [伊朗导弹袭击4处美军基地](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB4%E5%A4%84%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%23) `240.7K 🔥` `NEW`
1. [朱志鑫娃娃款售罄](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E5%A8%83%E5%A8%83%E6%AC%BE%E5%94%AE%E7%BD%84%23) `239.2K 🔥` `NEW`
1. [杨紫董竹君造型直播 (Yang Zi and Dong Zhujun styling live broadcast)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E8%91%A3%E7%AB%B9%E5%90%9B%E9%80%A0%E5%9E%8B%E7%9B%B4%E6%92%AD%23) `231.3K 🔥` `NEW`
1. [Prada全平台认领杨幂](https://s.weibo.com/weibo?q=%23Prada%E5%85%A8%E5%B9%B3%E5%8F%B0%E8%AE%A4%E9%A2%86%E6%9D%A8%E5%B9%82%23) `206.8K 🔥` `NEW`
1. [MCN与反诈老陈解约](https://s.weibo.com/weibo?q=%23MCN%E4%B8%8E%E5%8F%8D%E8%AF%88%E8%80%81%E9%99%88%E8%A7%A3%E7%BA%A6%23) `177.3K 🔥` `NEW`
1. [男朋友送的草莓蛋糕第一次见](https://s.weibo.com/weibo?q=%23%E7%94%B7%E6%9C%8B%E5%8F%8B%E9%80%81%E7%9A%84%E8%8D%89%E8%8E%93%E8%9B%8B%E7%B3%95%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%A7%81%23) `176.9K 🔥` `NEW`
1. [阿联酋拦截伊朗导弹1人死亡](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%81%94%E9%85%8B%E6%8B%A6%E6%88%AA%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B91%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `175.4K 🔥` `NEW`
1. [谷爱凌观战中国女排](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%A7%82%E6%88%98%E4%B8%AD%E5%9B%BD%E5%A5%B3%E6%8E%92%23) `167.7K 🔥` `NEW`
1. [多家公司暂停石油通过霍尔木兹海峡](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%AE%B6%E5%85%AC%E5%8F%B8%E6%9A%82%E5%81%9C%E7%9F%B3%E6%B2%B9%E9%80%9A%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `163.4K 🔥` `NEW`
1. [展轩直播](https://s.weibo.com/weibo?q=%23%E5%B1%95%E8%BD%A9%E7%9B%B4%E6%92%AD%23) `163.1K 🔥` `NEW`
1. [你好星期六](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD%E6%98%9F%E6%9C%9F%E5%85%AD%23) `151.3K 🔥` `NEW`
1. [斗破苍穹](https://s.weibo.com/weibo?q=%23%E6%96%97%E7%A0%B4%E8%8B%8D%E7%A9%B9%23) `148.2K 🔥` `NEW`
1. [阿联酋迪拜响起爆炸声 (Explosions ring out in Dubai, United Arab Emirates)](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%81%94%E9%85%8B%E8%BF%AA%E6%8B%9C%E5%93%8D%E8%B5%B7%E7%88%86%E7%82%B8%E5%A3%B0%23) `140.1K 🔥` `NEW`
1. [巴林美军基地现状](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E6%9E%97%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%E7%8E%B0%E7%8A%B6%23) `133.6K 🔥` `NEW`
1. [默茨从中国回去不满每周四天工作制](https://s.weibo.com/weibo?q=%23%E9%BB%98%E8%8C%A8%E4%BB%8E%E4%B8%AD%E5%9B%BD%E5%9B%9E%E5%8E%BB%E4%B8%8D%E6%BB%A1%E6%AF%8F%E5%91%A8%E5%9B%9B%E5%A4%A9%E5%B7%A5%E4%BD%9C%E5%88%B6%23) `123.9K 🔥` `NEW`
1. [华润集团副总经理韩嵩主动投案](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E6%B6%A6%E9%9B%86%E5%9B%A2%E5%89%AF%E6%80%BB%E7%BB%8F%E7%90%86%E9%9F%A9%E5%B5%A9%E4%B8%BB%E5%8A%A8%E6%8A%95%E6%A1%88%23) `102.2K 🔥` `NEW`
1. [中东战争形态发生根本转变](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%B8%9C%E6%88%98%E4%BA%89%E5%BD%A2%E6%80%81%E5%8F%91%E7%94%9F%E6%A0%B9%E6%9C%AC%E8%BD%AC%E5%8F%98%23) `101.8K 🔥` `NEW`
1. [孙颖莎vs早田希娜](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E6%97%A9%E7%94%B0%E5%B8%8C%E5%A8%9C%23) `355.6K 🔥` `+265%`
1. [公认是烂片你却很喜欢的电影](https://s.weibo.com/weibo?q=%23%E5%85%AC%E8%AE%A4%E6%98%AF%E7%83%82%E7%89%87%E4%BD%A0%E5%8D%B4%E5%BE%88%E5%96%9C%E6%AC%A2%E7%9A%84%E7%94%B5%E5%BD%B1%23) `264.2K 🔥` `+164%`
1. [伊朗的导弹雨正在路上 (Iran's missile rain is on its way)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%9A%84%E5%AF%BC%E5%BC%B9%E9%9B%A8%E6%AD%A3%E5%9C%A8%E8%B7%AF%E4%B8%8A%23) `263.9K 🔥` `+80%`
1. [伊朗总统之子发声](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E4%B9%8B%E5%AD%90%E5%8F%91%E5%A3%B0%23) `190.5K 🔥` `+30%`
1. [以色列宣布袭击伊朗 (Israel announces attack on Iran)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%23) `5.5M 🔥`
1. [山姆520元巧克力降到99元 (Sam’s 520 yuan chocolate reduced to 99 yuan)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86520%E5%85%83%E5%B7%A7%E5%85%8B%E5%8A%9B%E9%99%8D%E5%88%B099%E5%85%83%23) `1.3M 🔥`
1. [2025我国完成92次宇航发射 (my country completed 92 space launches in 2025)](https://s.weibo.com/weibo?q=%232025%E6%88%91%E5%9B%BD%E5%AE%8C%E6%88%9092%E6%AC%A1%E5%AE%87%E8%88%AA%E5%8F%91%E5%B0%84%23) `1.1M 🔥`
1. [突然对1g黄金没概念了](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E5%AF%B91g%E9%BB%84%E9%87%91%E6%B2%A1%E6%A6%82%E5%BF%B5%E4%BA%86%23) `211.8K 🔥`
1. [买3条金项链一夜赚超2.3万元](https://s.weibo.com/weibo?q=%23%E4%B9%B03%E6%9D%A1%E9%87%91%E9%A1%B9%E9%93%BE%E4%B8%80%E5%A4%9C%E8%B5%9A%E8%B6%852.3%E4%B8%87%E5%85%83%23) `169.5K 🔥`
1. [纯真年代的爱情 (Love in the Age of Innocence)](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `134.2K 🔥`
1. [我家那小子 (That boy of mine)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%23) `128.0K 🔥`
1. [新锐王牌问界M6七色亮相 (New Ace Wenjie M6 unveiled in seven colors)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E9%94%90%E7%8E%8B%E7%89%8C%E9%97%AE%E7%95%8CM6%E4%B8%83%E8%89%B2%E4%BA%AE%E7%9B%B8%23) `1.0M 🔥` `-28%`
1. [伊朗正在打击美国军事基地 (Iran is attacking US military bases)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%9C%A8%E6%89%93%E5%87%BB%E7%BE%8E%E5%9B%BD%E5%86%9B%E4%BA%8B%E5%9F%BA%E5%9C%B0%23) `500.5K 🔥` `-45%`
1. [美颜突然关掉吓得人一哆嗦](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E9%A2%9C%E7%AA%81%E7%84%B6%E5%85%B3%E6%8E%89%E5%90%93%E5%BE%97%E4%BA%BA%E4%B8%80%E5%93%86%E5%97%A6%23) `458.9K 🔥` `-28%`
1. [椰树广告 擦边](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E6%A0%91%E5%B9%BF%E5%91%8A%20%E6%93%A6%E8%BE%B9%23) `264.2K 🔥` `-57%`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `263.8K 🔥` `-52%`
1. [伊朗启动大规模军事行动 (Iran launches large-scale military operation)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%AF%E5%8A%A8%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%86%9B%E4%BA%8B%E8%A1%8C%E5%8A%A8%23) `258.6K 🔥` `-58%`
1. [大熊猫半半香果离世](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%86%8A%E7%8C%AB%E5%8D%8A%E5%8D%8A%E9%A6%99%E6%9E%9C%E7%A6%BB%E4%B8%96%23) `247.9K 🔥` `-62%`
1. [伊朗军方称总司令身体健康 (Iran's military says commander-in-chief is in good health)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%9B%E6%96%B9%E7%A7%B0%E6%80%BB%E5%8F%B8%E4%BB%A4%E8%BA%AB%E4%BD%93%E5%81%A5%E5%BA%B7%23) `245.1K 🔥` `-41%`
1. [TOP专辑 (TOP album)](https://s.weibo.com/weibo?q=%23TOP%E4%B8%93%E8%BE%91%23) `199.2K 🔥` `-35%`
1. [李治廷 十日终焉 (Li Zhiting The End of Ten Days)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%B2%BB%E5%BB%B7%20%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%23) `187.9K 🔥` `-51%`
1. [小米YU9 (Xiaomi YU9)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3YU9%23) `172.0K 🔥` `-73%`
1. [网传跑男铁了心要国民cp](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E8%B7%91%E7%94%B7%E9%93%81%E4%BA%86%E5%BF%83%E8%A6%81%E5%9B%BD%E6%B0%91cp%23) `167.7K 🔥` `-42%`
1. [伊朗袭击科威特美军基地 (Iran attacks US military base in Kuwait)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%E7%A7%91%E5%A8%81%E7%89%B9%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%23) `121.1K 🔥` `-68%`
1. [一点点 植脂末](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%20%E6%A4%8D%E8%84%82%E6%9C%AB%23) `99.7K 🔥` `-84%`
1. [Angelababy紫瞳 (Angelababy purple pupil)](https://s.weibo.com/weibo?q=%23Angelababy%E7%B4%AB%E7%9E%B3%23) `98.5K 🔥` `-48%`

Updated at 2026-02-28 21:03:55

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
