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

1. [舅舅送外甥女30斤银砖当压岁钱 (Uncle gives niece 30 kilograms of silver bricks as lucky money)](https://s.weibo.com/weibo?q=%23%E8%88%85%E8%88%85%E9%80%81%E5%A4%96%E7%94%A5%E5%A5%B330%E6%96%A4%E9%93%B6%E7%A0%96%E5%BD%93%E5%8E%8B%E5%B2%81%E9%92%B1%23) `1.1M 🔥` `NEW`
1. [镖人阿育娅 换人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E9%98%BF%E8%82%B2%E5%A8%85%20%E6%8D%A2%E4%BA%BA%23) `831.0K 🔥` `NEW`
1. [多地气温断崖式下跌](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E6%B0%94%E6%B8%A9%E6%96%AD%E5%B4%96%E5%BC%8F%E4%B8%8B%E8%B7%8C%23) `650.7K 🔥` `NEW`
1. [官方辟谣过年了轨道交通都跑熄火了](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E8%BE%9F%E8%B0%A3%E8%BF%87%E5%B9%B4%E4%BA%86%E8%BD%A8%E9%81%93%E4%BA%A4%E9%80%9A%E9%83%BD%E8%B7%91%E7%86%84%E7%81%AB%E4%BA%86%23) `273.4K 🔥` `NEW`
1. [黄晓明曝艺人红毯上假摔](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E6%9B%9D%E8%89%BA%E4%BA%BA%E7%BA%A2%E6%AF%AF%E4%B8%8A%E5%81%87%E6%91%94%23) `128.3K 🔥` `NEW`
1. [北京沙尘暴](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E6%B2%99%E5%B0%98%E6%9A%B4%23) `125.8K 🔥` `NEW`
1. [00后月租200住养老院2年](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E6%9C%88%E7%A7%9F200%E4%BD%8F%E5%85%BB%E8%80%81%E9%99%A22%E5%B9%B4%23) `125.4K 🔥` `NEW`
1. [意大利中国博士生已失联一个月](https://s.weibo.com/weibo?q=%23%E6%84%8F%E5%A4%A7%E5%88%A9%E4%B8%AD%E5%9B%BD%E5%8D%9A%E5%A3%AB%E7%94%9F%E5%B7%B2%E5%A4%B1%E8%81%94%E4%B8%80%E4%B8%AA%E6%9C%88%23) `121.9K 🔥` `NEW`
1. [飞驰人生3路演现场乐事多](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E8%B7%AF%E6%BC%94%E7%8E%B0%E5%9C%BA%E4%B9%90%E4%BA%8B%E5%A4%9A%23) `119.9K 🔥` `NEW`
1. [回村后用的都是名牌货](https://s.weibo.com/weibo?q=%23%E5%9B%9E%E6%9D%91%E5%90%8E%E7%94%A8%E7%9A%84%E9%83%BD%E6%98%AF%E5%90%8D%E7%89%8C%E8%B4%A7%23) `118.3K 🔥` `NEW`
1. [一栗莎子过年在医院治疗 (Yili Shazi is treated in the hospital during the Chinese New Year)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E6%A0%97%E8%8E%8E%E5%AD%90%E8%BF%87%E5%B9%B4%E5%9C%A8%E5%8C%BB%E9%99%A2%E6%B2%BB%E7%96%97%23) `75.2K 🔥` `NEW`
1. [爸爸做年夜饭每个摆盘都出乎意料](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E5%81%9A%E5%B9%B4%E5%A4%9C%E9%A5%AD%E6%AF%8F%E4%B8%AA%E6%91%86%E7%9B%98%E9%83%BD%E5%87%BA%E4%B9%8E%E6%84%8F%E6%96%99%23) `72.9K 🔥` `NEW`
1. [一代人有一代人的财神](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%BB%A3%E4%BA%BA%E6%9C%89%E4%B8%80%E4%BB%A3%E4%BA%BA%E7%9A%84%E8%B4%A2%E7%A5%9E%23) `70.2K 🔥` `NEW`
1. [张柏芝让员工带薪休假一个月](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9F%8F%E8%8A%9D%E8%AE%A9%E5%91%98%E5%B7%A5%E5%B8%A6%E8%96%AA%E4%BC%91%E5%81%87%E4%B8%80%E4%B8%AA%E6%9C%88%23) `69.6K 🔥` `NEW`
1. [陈飞宇减肥的证据被我找到了](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E5%87%8F%E8%82%A5%E7%9A%84%E8%AF%81%E6%8D%AE%E8%A2%AB%E6%88%91%E6%89%BE%E5%88%B0%E4%BA%86%23) `64.2K 🔥` `NEW`
1. [教练辟谣不让苏翊鸣谈恋爱](https://s.weibo.com/weibo?q=%23%E6%95%99%E7%BB%83%E8%BE%9F%E8%B0%A3%E4%B8%8D%E8%AE%A9%E8%8B%8F%E7%BF%8A%E9%B8%A3%E8%B0%88%E6%81%8B%E7%88%B1%23) `63.5K 🔥` `NEW`
1. [OpenAI下调算力支出目标至6000亿美元](https://s.weibo.com/weibo?q=%23OpenAI%E4%B8%8B%E8%B0%83%E7%AE%97%E5%8A%9B%E6%94%AF%E5%87%BA%E7%9B%AE%E6%A0%87%E8%87%B36000%E4%BA%BF%E7%BE%8E%E5%85%83%23) `63.1K 🔥` `NEW`
1. [不让江山](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%23) `63.0K 🔥` `NEW`
1. [春节档第11部长剧开播了](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E6%A1%A3%E7%AC%AC11%E9%83%A8%E9%95%BF%E5%89%A7%E5%BC%80%E6%92%AD%E4%BA%86%23) `63.0K 🔥` `NEW`
1. [中国队剑指双金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E5%89%91%E6%8C%87%E5%8F%8C%E9%87%91%23) `63.0K 🔥` `NEW`
1. [沙尘暴 (sandstorm)](https://s.weibo.com/weibo?q=%23%E6%B2%99%E5%B0%98%E6%9A%B4%23) `274.7K 🔥` `+286%`
1. [刘涛演妈祖 三次圣杯 (Liu Tao plays Mazu in Three Holy Grails)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B6%9B%E6%BC%94%E5%A6%88%E7%A5%96%20%E4%B8%89%E6%AC%A1%E5%9C%A3%E6%9D%AF%23) `274.6K 🔥` `+37%`
1. [初一到初五我的精神状态](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%80%E5%88%B0%E5%88%9D%E4%BA%94%E6%88%91%E7%9A%84%E7%B2%BE%E7%A5%9E%E7%8A%B6%E6%80%81%23) `271.3K 🔥` `+50%`
1. [三亚返程机票逼近万元](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E8%BF%94%E7%A8%8B%E6%9C%BA%E7%A5%A8%E9%80%BC%E8%BF%91%E4%B8%87%E5%85%83%23) `119.0K 🔥` `+43%`
1. [京东健康祝天下父母身体健康 (JD Health wishes parents all over the world good health)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E5%81%A5%E5%BA%B7%E7%A5%9D%E5%A4%A9%E4%B8%8B%E7%88%B6%E6%AF%8D%E8%BA%AB%E4%BD%93%E5%81%A5%E5%BA%B7%23) `634.4K 🔥`
1. [黄晓明回应在澳门输掉十几亿 (Huang Xiaoming responded to losing more than one billion in Macau)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E5%9B%9E%E5%BA%94%E5%9C%A8%E6%BE%B3%E9%97%A8%E8%BE%93%E6%8E%89%E5%8D%81%E5%87%A0%E4%BA%BF%23) `548.7K 🔥`
1. [这2种饮料混着喝或永久损伤大脑 (Mixing these two drinks could permanently damage your brain)](https://s.weibo.com/weibo?q=%23%E8%BF%992%E7%A7%8D%E9%A5%AE%E6%96%99%E6%B7%B7%E7%9D%80%E5%96%9D%E6%88%96%E6%B0%B8%E4%B9%85%E6%8D%9F%E4%BC%A4%E5%A4%A7%E8%84%91%23) `123.6K 🔥`
1. [初中女生若未满16岁骑电动车属违规](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%AD%E5%A5%B3%E7%94%9F%E8%8B%A5%E6%9C%AA%E6%BB%A116%E5%B2%81%E9%AA%91%E7%94%B5%E5%8A%A8%E8%BD%A6%E5%B1%9E%E8%BF%9D%E8%A7%84%23) `121.0K 🔥`
1. [阿勒泰 刘耀文宋亚轩](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%8B%92%E6%B3%B0%20%E5%88%98%E8%80%80%E6%96%87%E5%AE%8B%E4%BA%9A%E8%BD%A9%23) `118.9K 🔥`
1. [花10块钱买的齐天大圣烟花](https://s.weibo.com/weibo?q=%23%E8%8A%B110%E5%9D%97%E9%92%B1%E4%B9%B0%E7%9A%84%E9%BD%90%E5%A4%A9%E5%A4%A7%E5%9C%A3%E7%83%9F%E8%8A%B1%23) `73.5K 🔥`
1. [侯明昊初五上早班困成啥了](https://s.weibo.com/weibo?q=%23%E4%BE%AF%E6%98%8E%E6%98%8A%E5%88%9D%E4%BA%94%E4%B8%8A%E6%97%A9%E7%8F%AD%E5%9B%B0%E6%88%90%E5%95%A5%E4%BA%86%23) `63.1K 🔥`
1. [三个黄景瑜都吻上来了](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%B8%AA%E9%BB%84%E6%99%AF%E7%91%9C%E9%83%BD%E5%90%BB%E4%B8%8A%E6%9D%A5%E4%BA%86%23) `63.1K 🔥`
1. [镖人 第二部 (The Escort Part 2)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E7%AC%AC%E4%BA%8C%E9%83%A8%23) `273.3K 🔥` `-67%`
1. [王濛说签生死状复出 (Wang Meng said he would sign a life and death certificate to come back)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E8%AF%B4%E7%AD%BE%E7%94%9F%E6%AD%BB%E7%8A%B6%E5%A4%8D%E5%87%BA%23) `143.2K 🔥` `-35%`
1. [弟弟没钱但有的是力气和手段](https://s.weibo.com/weibo?q=%23%E5%BC%9F%E5%BC%9F%E6%B2%A1%E9%92%B1%E4%BD%86%E6%9C%89%E7%9A%84%E6%98%AF%E5%8A%9B%E6%B0%94%E5%92%8C%E6%89%8B%E6%AE%B5%23) `131.1K 🔥` `-28%`
1. [警方通报平顶山打人事件 (Police report on beating incident in Pingdingshan)](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E5%B9%B3%E9%A1%B6%E5%B1%B1%E6%89%93%E4%BA%BA%E4%BA%8B%E4%BB%B6%23) `130.6K 🔥` `-89%`
1. [王濛批评短道合理吗](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E6%89%B9%E8%AF%84%E7%9F%AD%E9%81%93%E5%90%88%E7%90%86%E5%90%97%23) `129.9K 🔥` `-28%`
1. [金价 (gold price)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `129.7K 🔥` `-28%`
1. [致7人溺亡的贝加尔湖旅游16888元起 (Lake Baikal tour that caused 7 drownings starts at 16,888 yuan)](https://s.weibo.com/weibo?q=%23%E8%87%B47%E4%BA%BA%E6%BA%BA%E4%BA%A1%E7%9A%84%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E6%97%85%E6%B8%B816888%E5%85%83%E8%B5%B7%23) `128.9K 🔥` `-29%`
1. [那艺娜劣迹艺人 (Na Yina's evil artist)](https://s.weibo.com/weibo?q=%23%E9%82%A3%E8%89%BA%E5%A8%9C%E5%8A%A3%E8%BF%B9%E8%89%BA%E4%BA%BA%23) `127.8K 🔥` `-29%`
1. [苹果史上首款折叠屏手机](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E5%8F%B2%E4%B8%8A%E9%A6%96%E6%AC%BE%E6%8A%98%E5%8F%A0%E5%B1%8F%E6%89%8B%E6%9C%BA%23) `127.3K 🔥` `-29%`
1. [沈腾这下不怕票房被黄渤超过了](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E8%BF%99%E4%B8%8B%E4%B8%8D%E6%80%95%E7%A5%A8%E6%88%BF%E8%A2%AB%E9%BB%84%E6%B8%A4%E8%B6%85%E8%BF%87%E4%BA%86%23) `126.5K 🔥` `-29%`
1. [刘耀文自曝时代峰峻选助理内幕](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%80%80%E6%96%87%E8%87%AA%E6%9B%9D%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E9%80%89%E5%8A%A9%E7%90%86%E5%86%85%E5%B9%95%23) `124.0K 🔥` `-31%`
1. [韩维辰硬刚wk1](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E7%BB%B4%E8%BE%B0%E7%A1%AC%E5%88%9Awk1%23) `122.4K 🔥` `-31%`
1. [孟子义沈妙](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%B2%88%E5%A6%99%23) `122.4K 🔥` `-32%`
1. [苏翊鸣下个周期最大目标法国冬奥 (Su Yiming’s biggest goal in the next cycle is the French Winter Olympics)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E4%B8%8B%E4%B8%AA%E5%91%A8%E6%9C%9F%E6%9C%80%E5%A4%A7%E7%9B%AE%E6%A0%87%E6%B3%95%E5%9B%BD%E5%86%AC%E5%A5%A5%23) `121.7K 🔥` `-33%`
1. [谷爱凌出战冲金](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%87%BA%E6%88%98%E5%86%B2%E9%87%91%23) `120.4K 🔥` `-32%`
1. [郭晶晶聊带娃读书叹气](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%B6%E6%99%B6%E8%81%8A%E5%B8%A6%E5%A8%83%E8%AF%BB%E4%B9%A6%E5%8F%B9%E6%B0%94%23) `113.5K 🔥` `-37%`
1. [姚晨丢掉妈妈过期药品被骂了3天 (Yao Chen was scolded for 3 days for throwing away his mother's expired medicines)](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E6%99%A8%E4%B8%A2%E6%8E%89%E5%A6%88%E5%A6%88%E8%BF%87%E6%9C%9F%E8%8D%AF%E5%93%81%E8%A2%AB%E9%AA%82%E4%BA%863%E5%A4%A9%23) `105.6K 🔥` `-23%`
1. [终于有人懂牛奶包装设计师了 (Finally someone understands milk packaging designers)](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%87%82%E7%89%9B%E5%A5%B6%E5%8C%85%E8%A3%85%E8%AE%BE%E8%AE%A1%E5%B8%88%E4%BA%86%23) `75.1K 🔥` `-59%`
1. [迎财神 (Welcome the God of Wealth)](https://s.weibo.com/weibo?q=%23%E8%BF%8E%E8%B4%A2%E7%A5%9E%23) `74.5K 🔥` `-29%`

Updated at 2026-02-21 16:37:44

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
