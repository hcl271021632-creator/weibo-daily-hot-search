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

1. [广西名医黄贵华突发心梗去世 (Guangxi famous doctor Huang Guihua died of sudden myocardial infarction)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E8%A5%BF%E5%90%8D%E5%8C%BB%E9%BB%84%E8%B4%B5%E5%8D%8E%E7%AA%81%E5%8F%91%E5%BF%83%E6%A2%97%E5%8E%BB%E4%B8%96%23) `818.7K 🔥` `NEW`
1. [沧元图川月CP战绩可查](https://s.weibo.com/weibo?q=%23%E6%B2%A7%E5%85%83%E5%9B%BE%E5%B7%9D%E6%9C%88CP%E6%88%98%E7%BB%A9%E5%8F%AF%E6%9F%A5%23) `301.8K 🔥` `NEW`
1. [店家回应留奔跑吧明星剩饭](https://s.weibo.com/weibo?q=%23%E5%BA%97%E5%AE%B6%E5%9B%9E%E5%BA%94%E7%95%99%E5%A5%94%E8%B7%91%E5%90%A7%E6%98%8E%E6%98%9F%E5%89%A9%E9%A5%AD%23) `279.0K 🔥` `NEW`
1. [王濛 浪姐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%20%E6%B5%AA%E5%A7%90%23) `193.9K 🔥` `NEW`
1. [中国博士后遭美方约谈盘问后自杀](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%8D%9A%E5%A3%AB%E5%90%8E%E9%81%AD%E7%BE%8E%E6%96%B9%E7%BA%A6%E8%B0%88%E7%9B%98%E9%97%AE%E5%90%8E%E8%87%AA%E6%9D%80%23) `187.8K 🔥` `NEW`
1. [国足2比0库拉索](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E8%B6%B32%E6%AF%940%E5%BA%93%E6%8B%89%E7%B4%A2%23) `170.4K 🔥` `NEW`
1. [宁波男子网贷60万打赏女主播确诊生病](https://s.weibo.com/weibo?q=%23%E5%AE%81%E6%B3%A2%E7%94%B7%E5%AD%90%E7%BD%91%E8%B4%B760%E4%B8%87%E6%89%93%E8%B5%8F%E5%A5%B3%E4%B8%BB%E6%92%AD%E7%A1%AE%E8%AF%8A%E7%94%9F%E7%97%85%23) `143.6K 🔥` `NEW`
1. [豪华大五座新卷王来了](https://s.weibo.com/weibo?q=%23%E8%B1%AA%E5%8D%8E%E5%A4%A7%E4%BA%94%E5%BA%A7%E6%96%B0%E5%8D%B7%E7%8E%8B%E6%9D%A5%E4%BA%86%23) `136.9K 🔥` `NEW`
1. [文淇都敢演这段戏了](https://s.weibo.com/weibo?q=%23%E6%96%87%E6%B7%87%E9%83%BD%E6%95%A2%E6%BC%94%E8%BF%99%E6%AE%B5%E6%88%8F%E4%BA%86%23) `121.1K 🔥` `NEW`
1. [阚清子说浪姐强度大要养好身体](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E8%AF%B4%E6%B5%AA%E5%A7%90%E5%BC%BA%E5%BA%A6%E5%A4%A7%E8%A6%81%E5%85%BB%E5%A5%BD%E8%BA%AB%E4%BD%93%23) `113.9K 🔥` `NEW`
1. [播剧20天张凌赫涨粉536.7万 (Zhang Linghe gained 5.367 million followers after 20 days of broadcasting the drama)](https://s.weibo.com/weibo?q=%23%E6%92%AD%E5%89%A720%E5%A4%A9%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%B6%A8%E7%B2%89536.7%E4%B8%87%23) `105.3K 🔥` `NEW`
1. [巴西女子杀死性侵女儿男子被判无罪](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E8%A5%BF%E5%A5%B3%E5%AD%90%E6%9D%80%E6%AD%BB%E6%80%A7%E4%BE%B5%E5%A5%B3%E5%84%BF%E7%94%B7%E5%AD%90%E8%A2%AB%E5%88%A4%E6%97%A0%E7%BD%AA%23) `105.3K 🔥` `NEW`
1. [时团要和跑男对抗撕名牌了](https://s.weibo.com/weibo?q=%23%E6%97%B6%E5%9B%A2%E8%A6%81%E5%92%8C%E8%B7%91%E7%94%B7%E5%AF%B9%E6%8A%97%E6%92%95%E5%90%8D%E7%89%8C%E4%BA%86%23) `105.3K 🔥` `NEW`
1. [安陵容祺贵人 浪姐](https://s.weibo.com/weibo?q=%23%E5%AE%89%E9%99%B5%E5%AE%B9%E7%A5%BA%E8%B4%B5%E4%BA%BA%20%E6%B5%AA%E5%A7%90%23) `102.6K 🔥` `NEW`
1. [TES回应Naiyou被终身禁赛](https://s.weibo.com/weibo?q=%23TES%E5%9B%9E%E5%BA%94Naiyou%E8%A2%AB%E7%BB%88%E8%BA%AB%E7%A6%81%E8%B5%9B%23) `87.5K 🔥` `NEW`
1. [日本17岁女高中生偷大米被抓](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC17%E5%B2%81%E5%A5%B3%E9%AB%98%E4%B8%AD%E7%94%9F%E5%81%B7%E5%A4%A7%E7%B1%B3%E8%A2%AB%E6%8A%93%23) `86.4K 🔥` `NEW`
1. [央视曝光职业索赔人造假](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%9B%9D%E5%85%89%E8%81%8C%E4%B8%9A%E7%B4%A2%E8%B5%94%E4%BA%BA%E9%80%A0%E5%81%87%23) `86.0K 🔥` `NEW`
1. [丁程鑫出发录奔跑吧14](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E5%87%BA%E5%8F%91%E5%BD%95%E5%A5%94%E8%B7%91%E5%90%A714%23) `85.9K 🔥` `NEW`
1. [外卖员吐槽收入大不如从前](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%8D%96%E5%91%98%E5%90%90%E6%A7%BD%E6%94%B6%E5%85%A5%E5%A4%A7%E4%B8%8D%E5%A6%82%E4%BB%8E%E5%89%8D%23) `85.2K 🔥` `NEW`
1. [余华把悲伤留给读者自己定居三亚](https://s.weibo.com/weibo?q=%23%E4%BD%99%E5%8D%8E%E6%8A%8A%E6%82%B2%E4%BC%A4%E7%95%99%E7%BB%99%E8%AF%BB%E8%80%85%E8%87%AA%E5%B7%B1%E5%AE%9A%E5%B1%85%E4%B8%89%E4%BA%9A%23) `81.8K 🔥` `NEW`
1. [TES称永不录用杨子健 (TES says it will never hire Yang Zijian)](https://s.weibo.com/weibo?q=%23TES%E7%A7%B0%E6%B0%B8%E4%B8%8D%E5%BD%95%E7%94%A8%E6%9D%A8%E5%AD%90%E5%81%A5%23) `77.8K 🔥` `NEW`
1. [金饰价跌到1364元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E8%B7%8C%E5%88%B01364%E5%85%83%23) `74.7K 🔥` `NEW`
1. [罗技销售额增长主要靠中国市场](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%8A%80%E9%94%80%E5%94%AE%E9%A2%9D%E5%A2%9E%E9%95%BF%E4%B8%BB%E8%A6%81%E9%9D%A0%E4%B8%AD%E5%9B%BD%E5%B8%82%E5%9C%BA%23) `73.6K 🔥` `NEW`
1. [孙颖莎深色OOTD](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E6%B7%B1%E8%89%B2OOTD%23) `72.9K 🔥` `NEW`
1. [汪铎一天不惹祝绪丹就皮痒](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E9%93%8E%E4%B8%80%E5%A4%A9%E4%B8%8D%E6%83%B9%E7%A5%9D%E7%BB%AA%E4%B8%B9%E5%B0%B1%E7%9A%AE%E7%97%92%23) `72.7K 🔥` `NEW`
1. [曾沛慈终于上浪姐了](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E6%B2%9B%E6%85%88%E7%BB%88%E4%BA%8E%E4%B8%8A%E6%B5%AA%E5%A7%90%E4%BA%86%23) `326.0K 🔥` `+63%`
1. [张凌赫回应逐玉大结局](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%9B%9E%E5%BA%94%E9%80%90%E7%8E%89%E5%A4%A7%E7%BB%93%E5%B1%80%23) `324.3K 🔥` `+205%`
1. [多位寻亲家长给梅姨同居者下跪](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E4%BD%8D%E5%AF%BB%E4%BA%B2%E5%AE%B6%E9%95%BF%E7%BB%99%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E8%80%85%E4%B8%8B%E8%B7%AA%23) `294.7K 🔥` `+27%`
1. [熬夜的人要多吃一类食物](https://s.weibo.com/weibo?q=%23%E7%86%AC%E5%A4%9C%E7%9A%84%E4%BA%BA%E8%A6%81%E5%A4%9A%E5%90%83%E4%B8%80%E7%B1%BB%E9%A3%9F%E7%89%A9%23) `198.7K 🔥` `+52%`
1. [刘海宽拒绝吃陈情令老本](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%B7%E5%AE%BD%E6%8B%92%E7%BB%9D%E5%90%83%E9%99%88%E6%83%85%E4%BB%A4%E8%80%81%E6%9C%AC%23) `191.6K 🔥` `+63%`
1. [乘风2026官宣阵容 (Chengfeng 2026 official lineup announced)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%AE%98%E5%AE%A3%E9%98%B5%E5%AE%B9%23) `1.2M 🔥`
1. [海南自贸港封关运作100天 (Hainan Free Trade Port closed for 100 days)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8D%97%E8%87%AA%E8%B4%B8%E6%B8%AF%E5%B0%81%E5%85%B3%E8%BF%90%E4%BD%9C100%E5%A4%A9%23) `649.5K 🔥`
1. [相亲型社交](https://s.weibo.com/weibo?q=%23%E7%9B%B8%E4%BA%B2%E5%9E%8B%E7%A4%BE%E4%BA%A4%23) `298.4K 🔥`
1. [郭麒麟对接回应KTV传闻](https://s.weibo.com/weibo?q=%23%E9%83%AD%E9%BA%92%E9%BA%9F%E5%AF%B9%E6%8E%A5%E5%9B%9E%E5%BA%94KTV%E4%BC%A0%E9%97%BB%23) `203.4K 🔥`
1. [社保基金多次在A股大跌时果断加仓](https://s.weibo.com/weibo?q=%23%E7%A4%BE%E4%BF%9D%E5%9F%BA%E9%87%91%E5%A4%9A%E6%AC%A1%E5%9C%A8A%E8%82%A1%E5%A4%A7%E8%B7%8C%E6%97%B6%E6%9E%9C%E6%96%AD%E5%8A%A0%E4%BB%93%23) `136.3K 🔥`
1. [你们相亲都那么好笑吗](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E4%BB%AC%E7%9B%B8%E4%BA%B2%E9%83%BD%E9%82%A3%E4%B9%88%E5%A5%BD%E7%AC%91%E5%90%97%23) `129.3K 🔥`
1. [遭外机雷达照射歼10C飞行员以牙还牙](https://s.weibo.com/weibo?q=%23%E9%81%AD%E5%A4%96%E6%9C%BA%E9%9B%B7%E8%BE%BE%E7%85%A7%E5%B0%84%E6%AD%BC10C%E9%A3%9E%E8%A1%8C%E5%91%98%E4%BB%A5%E7%89%99%E8%BF%98%E7%89%99%23) `114.8K 🔥`
1. [严浩翔新专概念视频](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E6%B5%A9%E7%BF%94%E6%96%B0%E4%B8%93%E6%A6%82%E5%BF%B5%E8%A7%86%E9%A2%91%23) `105.3K 🔥`
1. [库克公开乔布斯临终遗嘱](https://s.weibo.com/weibo?q=%23%E5%BA%93%E5%85%8B%E5%85%AC%E5%BC%80%E4%B9%94%E5%B8%83%E6%96%AF%E4%B8%B4%E7%BB%88%E9%81%97%E5%98%B1%23) `105.3K 🔥`
1. [Naiyou终身禁赛](https://s.weibo.com/weibo?q=%23Naiyou%E7%BB%88%E8%BA%AB%E7%A6%81%E8%B5%9B%23) `443.5K 🔥` `-38%`
1. [余华定居三亚 (Yu Hua settled in Sanya)](https://s.weibo.com/weibo?q=%23%E4%BD%99%E5%8D%8E%E5%AE%9A%E5%B1%85%E4%B8%89%E4%BA%9A%23) `203.9K 🔥` `-41%`
1. [乘风2026定档 (Chengfeng 2026 scheduled)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%AE%9A%E6%A1%A3%23) `184.1K 🔥` `-64%`
1. [乘风2026师姐帮帮唱](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%B8%88%E5%A7%90%E5%B8%AE%E5%B8%AE%E5%94%B1%23) `159.5K 🔥` `-39%`
1. [孔雪儿壁纸是cortis (Kong Xueer wallpaper is cortis)](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E5%A3%81%E7%BA%B8%E6%98%AFcortis%23) `125.2K 🔥` `-40%`
1. [郭晓婷王天辰杂志 离婚跟拍](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%93%E5%A9%B7%E7%8E%8B%E5%A4%A9%E8%BE%B0%E6%9D%82%E5%BF%97%20%E7%A6%BB%E5%A9%9A%E8%B7%9F%E6%8B%8D%23) `114.7K 🔥` `-44%`
1. [仅退款还得再给你200的程度](https://s.weibo.com/weibo?q=%23%E4%BB%85%E9%80%80%E6%AC%BE%E8%BF%98%E5%BE%97%E5%86%8D%E7%BB%99%E4%BD%A0200%E7%9A%84%E7%A8%8B%E5%BA%A6%23) `105.3K 🔥` `-49%`
1. [国足vs库拉索](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E8%B6%B3vs%E5%BA%93%E6%8B%89%E7%B4%A2%23) `105.3K 🔥` `-87%`
1. [一声老婆45岁离异女打赏男主播61万 (Yiyi’s wife, a 45-year-old divorced woman, rewards a male anchor with RMB 610,000)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%A3%B0%E8%80%81%E5%A9%8645%E5%B2%81%E7%A6%BB%E5%BC%82%E5%A5%B3%E6%89%93%E8%B5%8F%E7%94%B7%E4%B8%BB%E6%92%AD61%E4%B8%87%23) `95.8K 🔥` `-27%`
1. [吴京 水肿](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E6%B0%B4%E8%82%BF%23) `94.7K 🔥` `-27%`
1. [范玮琪这一次乘风破浪](https://s.weibo.com/weibo?q=%23%E8%8C%83%E7%8E%AE%E7%90%AA%E8%BF%99%E4%B8%80%E6%AC%A1%E4%B9%98%E9%A3%8E%E7%A0%B4%E6%B5%AA%23) `94.4K 🔥` `-22%`
1. [粉底液将军为何会激起群嘲](https://s.weibo.com/weibo?q=%23%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B%E4%B8%BA%E4%BD%95%E4%BC%9A%E6%BF%80%E8%B5%B7%E7%BE%A4%E5%98%B2%23) `86.0K 🔥` `-34%`

Updated at 2026-03-27 16:35:37

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
