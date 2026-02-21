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

1. [镖人 第二部 (The Escort Part 2)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E7%AC%AC%E4%BA%8C%E9%83%A8%23) `836.0K 🔥` `NEW`
1. [闪耀赛场的中国红是最深情的告白](https://s.weibo.com/weibo?q=%23%E9%97%AA%E8%80%80%E8%B5%9B%E5%9C%BA%E7%9A%84%E4%B8%AD%E5%9B%BD%E7%BA%A2%E6%98%AF%E6%9C%80%E6%B7%B1%E6%83%85%E7%9A%84%E5%91%8A%E7%99%BD%23) `640.8K 🔥` `NEW`
1. [初一到初五我的精神状态](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%80%E5%88%B0%E5%88%9D%E4%BA%94%E6%88%91%E7%9A%84%E7%B2%BE%E7%A5%9E%E7%8A%B6%E6%80%81%23) `181.2K 🔥` `NEW`
1. [大学生过年在家的多重身份](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F%E8%BF%87%E5%B9%B4%E5%9C%A8%E5%AE%B6%E7%9A%84%E5%A4%9A%E9%87%8D%E8%BA%AB%E4%BB%BD%23) `80.1K 🔥` `NEW`
1. [沙尘暴](https://s.weibo.com/weibo?q=%23%E6%B2%99%E5%B0%98%E6%9A%B4%23) `71.1K 🔥` `NEW`
1. [高市早苗求和被俄罗斯泼冷水](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E6%B1%82%E5%92%8C%E8%A2%AB%E4%BF%84%E7%BD%97%E6%96%AF%E6%B3%BC%E5%86%B7%E6%B0%B4%23) `64.4K 🔥` `NEW`
1. [掘金54分大胜开拓者](https://s.weibo.com/weibo?q=%23%E6%8E%98%E9%87%9154%E5%88%86%E5%A4%A7%E8%83%9C%E5%BC%80%E6%8B%93%E8%80%85%23) `62.7K 🔥` `NEW`
1. [任嘉伦进化成了日更博主](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E5%98%89%E4%BC%A6%E8%BF%9B%E5%8C%96%E6%88%90%E4%BA%86%E6%97%A5%E6%9B%B4%E5%8D%9A%E4%B8%BB%23) `60.2K 🔥` `NEW`
1. [王心迪叫老婆桃桃姐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%BF%83%E8%BF%AA%E5%8F%AB%E8%80%81%E5%A9%86%E6%A1%83%E6%A1%83%E5%A7%90%23) `58.9K 🔥` `NEW`
1. [三个黄景瑜都吻上来了](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%B8%AA%E9%BB%84%E6%99%AF%E7%91%9C%E9%83%BD%E5%90%BB%E4%B8%8A%E6%9D%A5%E4%BA%86%23) `56.5K 🔥` `NEW`
1. [我的道德和笑点在打架 (My morals and my sense of humor are fighting)](https://s.weibo.com/weibo?q=%23%E6%88%91%E7%9A%84%E9%81%93%E5%BE%B7%E5%92%8C%E7%AC%91%E7%82%B9%E5%9C%A8%E6%89%93%E6%9E%B6%23) `56.1K 🔥` `NEW`
1. [王濛批评短道合理吗](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E6%89%B9%E8%AF%84%E7%9F%AD%E9%81%93%E5%90%88%E7%90%86%E5%90%97%23) `181.0K 🔥` `+90%`
1. [金价 (gold price)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `180.8K 🔥` `+72%`
1. [致7人溺亡的贝加尔湖旅游16888元起](https://s.weibo.com/weibo?q=%23%E8%87%B47%E4%BA%BA%E6%BA%BA%E4%BA%A1%E7%9A%84%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E6%97%85%E6%B8%B816888%E5%85%83%E8%B5%B7%23) `180.8K 🔥` `+72%`
1. [那艺娜劣迹艺人 (Na Yina's evil artist)](https://s.weibo.com/weibo?q=%23%E9%82%A3%E8%89%BA%E5%A8%9C%E5%8A%A3%E8%BF%B9%E8%89%BA%E4%BA%BA%23) `180.6K 🔥` `+73%`
1. [过年发大财 (Make a fortune during the new year)](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%8F%91%E5%A4%A7%E8%B4%A2%23) `180.5K 🔥` `+72%`
1. [苹果史上首款折叠屏手机](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E5%8F%B2%E4%B8%8A%E9%A6%96%E6%AC%BE%E6%8A%98%E5%8F%A0%E5%B1%8F%E6%89%8B%E6%9C%BA%23) `180.3K 🔥` `+73%`
1. [刘耀文自曝时代峰峻选助理内幕](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%80%80%E6%96%87%E8%87%AA%E6%9B%9D%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E9%80%89%E5%8A%A9%E7%90%86%E5%86%85%E5%B9%95%23) `180.3K 🔥` `+81%`
1. [孟子义沈妙](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%B2%88%E5%A6%99%23) `180.2K 🔥` `+75%`
1. [郭晶晶聊带娃读书叹气](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%B6%E6%99%B6%E8%81%8A%E5%B8%A6%E5%A8%83%E8%AF%BB%E4%B9%A6%E5%8F%B9%E6%B0%94%23) `180.1K 🔥` `+80%`
1. [谷爱凌出战冲金](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%87%BA%E6%88%98%E5%86%B2%E9%87%91%23) `177.8K 🔥` `+39%`
1. [韩维辰硬刚wk1](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E7%BB%B4%E8%BE%B0%E7%A1%AC%E5%88%9Awk1%23) `177.8K 🔥` `+76%`
1. [沈腾这下不怕票房被黄渤超过了](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E8%BF%99%E4%B8%8B%E4%B8%8D%E6%80%95%E7%A5%A8%E6%88%BF%E8%A2%AB%E9%BB%84%E6%B8%A4%E8%B6%85%E8%BF%87%E4%BA%86%23) `177.8K 🔥` `+88%`
1. [这2种饮料混着喝或永久损伤大脑 (Mixing these two drinks could permanently damage your brain)](https://s.weibo.com/weibo?q=%23%E8%BF%992%E7%A7%8D%E9%A5%AE%E6%96%99%E6%B7%B7%E7%9D%80%E5%96%9D%E6%88%96%E6%B0%B8%E4%B9%85%E6%8D%9F%E4%BC%A4%E5%A4%A7%E8%84%91%23) `142.4K 🔥` `+46%`
1. [姚晨丢掉妈妈过期药品被骂了3天 (Yao Chen was scolded for 3 days for throwing away his mother's expired medicines)](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E6%99%A8%E4%B8%A2%E6%8E%89%E5%A6%88%E5%A6%88%E8%BF%87%E6%9C%9F%E8%8D%AF%E5%93%81%E8%A2%AB%E9%AA%82%E4%BA%863%E5%A4%A9%23) `136.4K 🔥` `+38%`
1. [警方通报平顶山打人事件 (Police report on beating incident in Pingdingshan)](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E5%B9%B3%E9%A1%B6%E5%B1%B1%E6%89%93%E4%BA%BA%E4%BA%8B%E4%BB%B6%23) `1.2M 🔥`
1. [黄晓明回应在澳门输掉十几亿 (Huang Xiaoming responded to losing more than one billion in Macau)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E5%9B%9E%E5%BA%94%E5%9C%A8%E6%BE%B3%E9%97%A8%E8%BE%93%E6%8E%89%E5%8D%81%E5%87%A0%E4%BA%BF%23) `540.3K 🔥`
1. [弟弟没钱但有的是力气和手段](https://s.weibo.com/weibo?q=%23%E5%BC%9F%E5%BC%9F%E6%B2%A1%E9%92%B1%E4%BD%86%E6%9C%89%E7%9A%84%E6%98%AF%E5%8A%9B%E6%B0%94%E5%92%8C%E6%89%8B%E6%AE%B5%23) `181.4K 🔥`
1. [终于有人懂牛奶包装设计师了 (Finally someone understands milk packaging designers)](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%87%82%E7%89%9B%E5%A5%B6%E5%8C%85%E8%A3%85%E8%AE%BE%E8%AE%A1%E5%B8%88%E4%BA%86%23) `181.1K 🔥`
1. [迎财神 (Welcome the God of Wealth)](https://s.weibo.com/weibo?q=%23%E8%BF%8E%E8%B4%A2%E7%A5%9E%23) `104.3K 🔥`
1. [阿勒泰 刘耀文宋亚轩](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%8B%92%E6%B3%B0%20%E5%88%98%E8%80%80%E6%96%87%E5%AE%8B%E4%BA%9A%E8%BD%A9%23) `103.3K 🔥`
1. [初中女生若未满16岁骑电动车属违规](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%AD%E5%A5%B3%E7%94%9F%E8%8B%A5%E6%9C%AA%E6%BB%A116%E5%B2%81%E9%AA%91%E7%94%B5%E5%8A%A8%E8%BD%A6%E5%B1%9E%E8%BF%9D%E8%A7%84%23) `101.7K 🔥`
1. [不让江山女主 (The heroine who won’t let the country go)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%A5%B3%E4%B8%BB%23) `87.3K 🔥`
1. [上海财神庙一炉子被烧起火](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E8%B4%A2%E7%A5%9E%E5%BA%99%E4%B8%80%E7%82%89%E5%AD%90%E8%A2%AB%E7%83%A7%E8%B5%B7%E7%81%AB%23) `85.1K 🔥`
1. [三亚返程机票逼近万元](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E8%BF%94%E7%A8%8B%E6%9C%BA%E7%A5%A8%E9%80%BC%E8%BF%91%E4%B8%87%E5%85%83%23) `83.3K 🔥`
1. [不让江山官宣杨洋 (Don’t let Jiangshan officials announce Yang Yang)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%AE%98%E5%AE%A3%E6%9D%A8%E6%B4%8B%23) `74.3K 🔥`
1. [泡泡玛特创始人送小酒窝盲盒](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E6%B3%A1%E7%8E%9B%E7%89%B9%E5%88%9B%E5%A7%8B%E4%BA%BA%E9%80%81%E5%B0%8F%E9%85%92%E7%AA%9D%E7%9B%B2%E7%9B%92%23) `73.3K 🔥`
1. [侯明昊初五上早班困成啥了](https://s.weibo.com/weibo?q=%23%E4%BE%AF%E6%98%8E%E6%98%8A%E5%88%9D%E4%BA%94%E4%B8%8A%E6%97%A9%E7%8F%AD%E5%9B%B0%E6%88%90%E5%95%A5%E4%BA%86%23) `72.6K 🔥`
1. [花10块钱买的齐天大圣烟花](https://s.weibo.com/weibo?q=%23%E8%8A%B110%E5%9D%97%E9%92%B1%E4%B9%B0%E7%9A%84%E9%BD%90%E5%A4%A9%E5%A4%A7%E5%9C%A3%E7%83%9F%E8%8A%B1%23) `70.2K 🔥`
1. [身体里的湿气到底是什么 (What exactly is moisture in the body?)](https://s.weibo.com/weibo?q=%23%E8%BA%AB%E4%BD%93%E9%87%8C%E7%9A%84%E6%B9%BF%E6%B0%94%E5%88%B0%E5%BA%95%E6%98%AF%E4%BB%80%E4%B9%88%23) `64.6K 🔥`
1. [鹿晗四巡纪录片](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E5%9B%9B%E5%B7%A1%E7%BA%AA%E5%BD%95%E7%89%87%23) `57.0K 🔥`
1. [王濛说签生死状复出 (Wang Meng said he would sign a life and death certificate to come back)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E8%AF%B4%E7%AD%BE%E7%94%9F%E6%AD%BB%E7%8A%B6%E5%A4%8D%E5%87%BA%23) `219.7K 🔥` `-75%`
1. [刘涛演妈祖 三次圣杯 (Liu Tao plays Mazu in Three Holy Grails)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B6%9B%E6%BC%94%E5%A6%88%E7%A5%96%20%E4%B8%89%E6%AC%A1%E5%9C%A3%E6%9D%AF%23) `200.8K 🔥` `-59%`
1. [苏翊鸣下个周期最大目标法国冬奥 (Su Yiming’s biggest goal in the next cycle is the French Winter Olympics)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E4%B8%8B%E4%B8%AA%E5%91%A8%E6%9C%9F%E6%9C%80%E5%A4%A7%E7%9B%AE%E6%A0%87%E6%B3%95%E5%9B%BD%E5%86%AC%E5%A5%A5%23) `181.4K 🔥` `-64%`
1. [关晓彤我长大了不能被骗了](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E6%88%91%E9%95%BF%E5%A4%A7%E4%BA%86%E4%B8%8D%E8%83%BD%E8%A2%AB%E9%AA%97%E4%BA%86%23) `62.9K 🔥` `-24%`
1. [家属称平顶山被打女孩处半昏迷 (Family members said the girl who was beaten in Pingdingshan was semi-conscious)](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E5%B1%9E%E7%A7%B0%E5%B9%B3%E9%A1%B6%E5%B1%B1%E8%A2%AB%E6%89%93%E5%A5%B3%E5%AD%A9%E5%A4%84%E5%8D%8A%E6%98%8F%E8%BF%B7%23) `62.9K 🔥` `-40%`
1. [圣杯八次不中概率](https://s.weibo.com/weibo?q=%23%E5%9C%A3%E6%9D%AF%E5%85%AB%E6%AC%A1%E4%B8%8D%E4%B8%AD%E6%A6%82%E7%8E%87%23) `62.9K 🔥` `-40%`
1. [赵美延全额现金购入龙山公寓](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E7%BE%8E%E5%BB%B6%E5%85%A8%E9%A2%9D%E7%8E%B0%E9%87%91%E8%B4%AD%E5%85%A5%E9%BE%99%E5%B1%B1%E5%85%AC%E5%AF%93%23) `61.8K 🔥` `-22%`
1. [初五的财神有多忙](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%BA%94%E7%9A%84%E8%B4%A2%E7%A5%9E%E6%9C%89%E5%A4%9A%E5%BF%99%23) `58.1K 🔥` `-37%`

Updated at 2026-02-21 15:56:35

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
