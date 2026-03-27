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

1. [寿司郎 SIM卡 (Sushilang SIM card)](https://s.weibo.com/weibo?q=%23%E5%AF%BF%E5%8F%B8%E9%83%8E%20SIM%E5%8D%A1%23) `1.1M 🔥` `NEW`
1. [大圣崛起定档](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%9C%A3%E5%B4%9B%E8%B5%B7%E5%AE%9A%E6%A1%A3%23) `796.5K 🔥` `NEW`
1. [日本东京发生命案](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E4%B8%9C%E4%BA%AC%E5%8F%91%E7%94%9F%E5%91%BD%E6%A1%88%23) `346.1K 🔥` `NEW`
1. [王源官宣巡演](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BA%90%E5%AE%98%E5%AE%A3%E5%B7%A1%E6%BC%94%23) `327.5K 🔥` `NEW`
1. [为什么房间里那么多灰尘毛](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%BF%E9%97%B4%E9%87%8C%E9%82%A3%E4%B9%88%E5%A4%9A%E7%81%B0%E5%B0%98%E6%AF%9B%23) `271.3K 🔥` `NEW`
1. [一条vlog回顾3月](https://s.weibo.com/weibo?q=%23%E4%B8%80%E6%9D%A1vlog%E5%9B%9E%E9%A1%BE3%E6%9C%88%23) `226.6K 🔥` `NEW`
1. [郴州13名公职人员被处理](https://s.weibo.com/weibo?q=%23%E9%83%B4%E5%B7%9E13%E5%90%8D%E5%85%AC%E8%81%8C%E4%BA%BA%E5%91%98%E8%A2%AB%E5%A4%84%E7%90%86%23) `195.5K 🔥` `NEW`
1. [李昀锐孟子义她在闹他在笑](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E5%AD%9F%E5%AD%90%E4%B9%89%E5%A5%B9%E5%9C%A8%E9%97%B9%E4%BB%96%E5%9C%A8%E7%AC%91%23) `192.7K 🔥` `NEW`
1. [教育部发布20条严禁清单](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%82%B2%E9%83%A8%E5%8F%91%E5%B8%8320%E6%9D%A1%E4%B8%A5%E7%A6%81%E6%B8%85%E5%8D%95%23) `180.9K 🔥` `NEW`
1. [地坛公园不再允许用明星姓名认领树](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E5%9D%9B%E5%85%AC%E5%9B%AD%E4%B8%8D%E5%86%8D%E5%85%81%E8%AE%B8%E7%94%A8%E6%98%8E%E6%98%9F%E5%A7%93%E5%90%8D%E8%AE%A4%E9%A2%86%E6%A0%91%23) `175.9K 🔥` `NEW`
1. [沈南 谢谢你为寒门学子打造梯子 (Shen Nan, thank you for building a ladder for disadvantaged students.)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E5%8D%97%20%E8%B0%A2%E8%B0%A2%E4%BD%A0%E4%B8%BA%E5%AF%92%E9%97%A8%E5%AD%A6%E5%AD%90%E6%89%93%E9%80%A0%E6%A2%AF%E5%AD%90%23) `174.2K 🔥` `NEW`
1. [女子怀疑丈夫出轨扒货车车尾跟踪](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%80%80%E7%96%91%E4%B8%88%E5%A4%AB%E5%87%BA%E8%BD%A8%E6%89%92%E8%B4%A7%E8%BD%A6%E8%BD%A6%E5%B0%BE%E8%B7%9F%E8%B8%AA%23) `171.6K 🔥` `NEW`
1. [持刀闯馆事件日方休想蒙混过关](https://s.weibo.com/weibo?q=%23%E6%8C%81%E5%88%80%E9%97%AF%E9%A6%86%E4%BA%8B%E4%BB%B6%E6%97%A5%E6%96%B9%E4%BC%91%E6%83%B3%E8%92%99%E6%B7%B7%E8%BF%87%E5%85%B3%23) `170.7K 🔥` `NEW`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `168.9K 🔥` `NEW`
1. [蒙牛 孙颖莎](https://s.weibo.com/weibo?q=%23%E8%92%99%E7%89%9B%20%E5%AD%99%E9%A2%96%E8%8E%8E%23) `168.3K 🔥` `NEW`
1. [鹿晗片场状态比鲜啤还鲜活](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E7%89%87%E5%9C%BA%E7%8A%B6%E6%80%81%E6%AF%94%E9%B2%9C%E5%95%A4%E8%BF%98%E9%B2%9C%E6%B4%BB%23) `166.4K 🔥` `NEW`
1. [林俊杰合照没有七七](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E5%90%88%E7%85%A7%E6%B2%A1%E6%9C%89%E4%B8%83%E4%B8%83%23) `162.5K 🔥` `NEW`
1. [粉底液将军为何会激起群嘲](https://s.weibo.com/weibo?q=%23%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B%E4%B8%BA%E4%BD%95%E4%BC%9A%E6%BF%80%E8%B5%B7%E7%BE%A4%E5%98%B2%23) `160.1K 🔥` `NEW`
1. [27岁200斤女子每天奶茶外卖患心梗](https://s.weibo.com/weibo?q=%2327%E5%B2%81200%E6%96%A4%E5%A5%B3%E5%AD%90%E6%AF%8F%E5%A4%A9%E5%A5%B6%E8%8C%B6%E5%A4%96%E5%8D%96%E6%82%A3%E5%BF%83%E6%A2%97%23) `159.4K 🔥` `NEW`
1. [与众08遥遥领先](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E4%BC%9708%E9%81%A5%E9%81%A5%E9%A2%86%E5%85%88%23) `158.3K 🔥` `NEW`
1. [奔跑吧14首录合照各有各的活 (The 14 recorded photos of Run Bar each have their own activities)](https://s.weibo.com/weibo?q=%23%E5%A5%94%E8%B7%91%E5%90%A714%E9%A6%96%E5%BD%95%E5%90%88%E7%85%A7%E5%90%84%E6%9C%89%E5%90%84%E7%9A%84%E6%B4%BB%23) `157.2K 🔥` `NEW`
1. [淄博烧烤退烧之后](https://s.weibo.com/weibo?q=%23%E6%B7%84%E5%8D%9A%E7%83%A7%E7%83%A4%E9%80%80%E7%83%A7%E4%B9%8B%E5%90%8E%23) `156.6K 🔥` `NEW`
1. [以军大规模空袭德黑兰](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E5%A4%A7%E8%A7%84%E6%A8%A1%E7%A9%BA%E8%A2%AD%E5%BE%B7%E9%BB%91%E5%85%B0%23) `134.7K 🔥` `NEW`
1. [章子怡李安再合作](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%E6%9D%8E%E5%AE%89%E5%86%8D%E5%90%88%E4%BD%9C%23) `133.2K 🔥` `NEW`
1. [梅姨打牌经常拿出几千上万现金显摆](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E6%89%93%E7%89%8C%E7%BB%8F%E5%B8%B8%E6%8B%BF%E5%87%BA%E5%87%A0%E5%8D%83%E4%B8%8A%E4%B8%87%E7%8E%B0%E9%87%91%E6%98%BE%E6%91%86%23) `132.6K 🔥` `NEW`
1. [老人突发心梗30分钟教科书式自救](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%BA%BA%E7%AA%81%E5%8F%91%E5%BF%83%E6%A2%9730%E5%88%86%E9%92%9F%E6%95%99%E7%A7%91%E4%B9%A6%E5%BC%8F%E8%87%AA%E6%95%91%23) `112.9K 🔥` `NEW`
1. [无限超越班4阵容](https://s.weibo.com/weibo?q=%23%E6%97%A0%E9%99%90%E8%B6%85%E8%B6%8A%E7%8F%AD4%E9%98%B5%E5%AE%B9%23) `112.4K 🔥` `NEW`
1. [大侦探](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BE%A6%E6%8E%A2%23) `108.8K 🔥` `NEW`
1. [燕子也是一代不如一代了](https://s.weibo.com/weibo?q=%23%E7%87%95%E5%AD%90%E4%B9%9F%E6%98%AF%E4%B8%80%E4%BB%A3%E4%B8%8D%E5%A6%82%E4%B8%80%E4%BB%A3%E4%BA%86%23) `102.4K 🔥` `NEW`
1. [霉霉状态梦回2016](https://s.weibo.com/weibo?q=%23%E9%9C%89%E9%9C%89%E7%8A%B6%E6%80%81%E6%A2%A6%E5%9B%9E2016%23) `101.9K 🔥` `NEW`
1. [一声老婆45岁离异女打赏男主播61万 (Yiyi’s wife, a 45-year-old divorced woman, rewards a male anchor with RMB 610,000)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%A3%B0%E8%80%81%E5%A9%8645%E5%B2%81%E7%A6%BB%E5%BC%82%E5%A5%B3%E6%89%93%E8%B5%8F%E7%94%B7%E4%B8%BB%E6%92%AD61%E4%B8%87%23) `100.7K 🔥` `NEW`
1. [每月一杯奶茶钱换来晚年托底](https://s.weibo.com/weibo?q=%23%E6%AF%8F%E6%9C%88%E4%B8%80%E6%9D%AF%E5%A5%B6%E8%8C%B6%E9%92%B1%E6%8D%A2%E6%9D%A5%E6%99%9A%E5%B9%B4%E6%89%98%E5%BA%95%23) `100.4K 🔥` `NEW`
1. [06出生的人都已经上恋综了](https://s.weibo.com/weibo?q=%2306%E5%87%BA%E7%94%9F%E7%9A%84%E4%BA%BA%E9%83%BD%E5%B7%B2%E7%BB%8F%E4%B8%8A%E6%81%8B%E7%BB%BC%E4%BA%86%23) `100.3K 🔥` `NEW`
1. [发现爸妈是标准的老实人](https://s.weibo.com/weibo?q=%23%E5%8F%91%E7%8E%B0%E7%88%B8%E5%A6%88%E6%98%AF%E6%A0%87%E5%87%86%E7%9A%84%E8%80%81%E5%AE%9E%E4%BA%BA%23) `96.8K 🔥` `NEW`
1. [小小年纪就懂怎么把生意做黄了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%B0%8F%E5%B9%B4%E7%BA%AA%E5%B0%B1%E6%87%82%E6%80%8E%E4%B9%88%E6%8A%8A%E7%94%9F%E6%84%8F%E5%81%9A%E9%BB%84%E4%BA%86%23) `92.8K 🔥` `NEW`
1. [金正恩现场试用卢卡申科所赠步枪](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E7%8E%B0%E5%9C%BA%E8%AF%95%E7%94%A8%E5%8D%A2%E5%8D%A1%E7%94%B3%E7%A7%91%E6%89%80%E8%B5%A0%E6%AD%A5%E6%9E%AA%23) `91.1K 🔥` `NEW`
1. [A股华电辽能涨停](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E5%8D%8E%E7%94%B5%E8%BE%BD%E8%83%BD%E6%B6%A8%E5%81%9C%23) `90.9K 🔥` `NEW`
1. [张真源又在孟子义李昀锐中间](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%9C%9F%E6%BA%90%E5%8F%88%E5%9C%A8%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E4%B8%AD%E9%97%B4%23) `85.4K 🔥` `NEW`
1. [车主违停被贴不干胶直呼方式太粗暴](https://s.weibo.com/weibo?q=%23%E8%BD%A6%E4%B8%BB%E8%BF%9D%E5%81%9C%E8%A2%AB%E8%B4%B4%E4%B8%8D%E5%B9%B2%E8%83%B6%E7%9B%B4%E5%91%BC%E6%96%B9%E5%BC%8F%E5%A4%AA%E7%B2%97%E6%9A%B4%23) `81.4K 🔥` `NEW`
1. [父亲背着千金拖着犬子过斑马线](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E8%83%8C%E7%9D%80%E5%8D%83%E9%87%91%E6%8B%96%E7%9D%80%E7%8A%AC%E5%AD%90%E8%BF%87%E6%96%91%E9%A9%AC%E7%BA%BF%23) `80.6K 🔥` `NEW`
1. [ROG发布新视频内涵罗技 (ROG releases new video connotation Logitech)](https://s.weibo.com/weibo?q=%23ROG%E5%8F%91%E5%B8%83%E6%96%B0%E8%A7%86%E9%A2%91%E5%86%85%E6%B6%B5%E7%BD%97%E6%8A%80%23) `80.2K 🔥` `NEW`
1. [2026中国网络媒体论坛 (2026 China Online Media Forum)](https://s.weibo.com/weibo?q=%232026%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BB%9C%E5%AA%92%E4%BD%93%E8%AE%BA%E5%9D%9B%23) `625.8K 🔥`
1. [没认出来这是王子异](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E8%AE%A4%E5%87%BA%E6%9D%A5%E8%BF%99%E6%98%AF%E7%8E%8B%E5%AD%90%E5%BC%82%23) `165.3K 🔥`
1. [国产伟哥2025年少卖近800万片](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E4%BC%9F%E5%93%A52025%E5%B9%B4%E5%B0%91%E5%8D%96%E8%BF%91800%E4%B8%87%E7%89%87%23) `163.0K 🔥`
1. [全国猪价已跌破5元](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E7%8C%AA%E4%BB%B7%E5%B7%B2%E8%B7%8C%E7%A0%B45%E5%85%83%23) `134.5K 🔥`
1. [伊朗正式回应美国15点停火协议](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%BC%8F%E5%9B%9E%E5%BA%94%E7%BE%8E%E5%9B%BD15%E7%82%B9%E5%81%9C%E7%81%AB%E5%8D%8F%E8%AE%AE%23) `177.1K 🔥` `-68%`
1. [罗技就侮辱性广告致歉 (Logitech apologizes for insulting ad)](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%8A%80%E5%B0%B1%E4%BE%AE%E8%BE%B1%E6%80%A7%E5%B9%BF%E5%91%8A%E8%87%B4%E6%AD%89%23) `173.5K 🔥` `-85%`
1. [央视新闻夸了张凌赫雉鸡翎造型 (CCTV News praised Zhang Linghe’s pheasant feather appearance)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB%E5%A4%B8%E4%BA%86%E5%BC%A0%E5%87%8C%E8%B5%AB%E9%9B%89%E9%B8%A1%E7%BF%8E%E9%80%A0%E5%9E%8B%23) `157.9K 🔥` `-60%`
1. [白鹿录完跑男状态](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%BD%95%E5%AE%8C%E8%B7%91%E7%94%B7%E7%8A%B6%E6%80%81%23) `114.2K 🔥` `-35%`
1. [人民的名义演员被诉休庭未宣判](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E6%B0%91%E7%9A%84%E5%90%8D%E4%B9%89%E6%BC%94%E5%91%98%E8%A2%AB%E8%AF%89%E4%BC%91%E5%BA%AD%E6%9C%AA%E5%AE%A3%E5%88%A4%23) `113.9K 🔥` `-39%`
1. [南方将有暴雨大暴雨](https://s.weibo.com/weibo?q=%23%E5%8D%97%E6%96%B9%E5%B0%86%E6%9C%89%E6%9A%B4%E9%9B%A8%E5%A4%A7%E6%9A%B4%E9%9B%A8%23) `88.9K 🔥` `-37%`

Updated at 2026-03-27 11:55:13

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
