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

1. [专家建议放宽公积金提取限制 (Experts recommend relaxing provident fund withdrawal restrictions)](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E5%BB%BA%E8%AE%AE%E6%94%BE%E5%AE%BD%E5%85%AC%E7%A7%AF%E9%87%91%E6%8F%90%E5%8F%96%E9%99%90%E5%88%B6%23) `1.0M 🔥` `NEW`
1. [闲鱼和金靖都别唱了让我来拍](https://s.weibo.com/weibo?q=%23%E9%97%B2%E9%B1%BC%E5%92%8C%E9%87%91%E9%9D%96%E9%83%BD%E5%88%AB%E5%94%B1%E4%BA%86%E8%AE%A9%E6%88%91%E6%9D%A5%E6%8B%8D%23) `557.2K 🔥` `NEW`
1. [生态环境部部长现场拿出一枚芯片](https://s.weibo.com/weibo?q=%23%E7%94%9F%E6%80%81%E7%8E%AF%E5%A2%83%E9%83%A8%E9%83%A8%E9%95%BF%E7%8E%B0%E5%9C%BA%E6%8B%BF%E5%87%BA%E4%B8%80%E6%9E%9A%E8%8A%AF%E7%89%87%23) `513.6K 🔥` `NEW`
1. [女子腰臀部疼了8年终于找到元凶](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%85%B0%E8%87%80%E9%83%A8%E7%96%BC%E4%BA%868%E5%B9%B4%E7%BB%88%E4%BA%8E%E6%89%BE%E5%88%B0%E5%85%83%E5%87%B6%23) `474.6K 🔥` `NEW`
1. [AG对战DYG](https://s.weibo.com/weibo?q=%23AG%E5%AF%B9%E6%88%98DYG%23) `474.2K 🔥` `NEW`
1. [台湾地震](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E5%9C%B0%E9%9C%87%23) `305.0K 🔥` `NEW`
1. [乃万演唱会取消](https://s.weibo.com/weibo?q=%23%E4%B9%83%E4%B8%87%E6%BC%94%E5%94%B1%E4%BC%9A%E5%8F%96%E6%B6%88%23) `225.4K 🔥` `NEW`
1. [王楚钦vs弗朗西斯卡](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E5%BC%97%E6%9C%97%E8%A5%BF%E6%96%AF%E5%8D%A1%23) `207.1K 🔥` `NEW`
1. [李维嘉或将你好星期六常驻](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BB%B4%E5%98%89%E6%88%96%E5%B0%86%E4%BD%A0%E5%A5%BD%E6%98%9F%E6%9C%9F%E5%85%AD%E5%B8%B8%E9%A9%BB%23) `196.4K 🔥` `NEW`
1. [20岁小伙泡沫尿1年多不重视致透析](https://s.weibo.com/weibo?q=%2320%E5%B2%81%E5%B0%8F%E4%BC%99%E6%B3%A1%E6%B2%AB%E5%B0%BF1%E5%B9%B4%E5%A4%9A%E4%B8%8D%E9%87%8D%E8%A7%86%E8%87%B4%E9%80%8F%E6%9E%90%23) `196.1K 🔥` `NEW`
1. [伊朗最高领袖即将发表首份声明 (Iran's supreme leader is about to issue his first statement)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E5%8D%B3%E5%B0%86%E5%8F%91%E8%A1%A8%E9%A6%96%E4%BB%BD%E5%A3%B0%E6%98%8E%23) `195.9K 🔥` `NEW`
1. [衣服洗不干净的原因找到了](https://s.weibo.com/weibo?q=%23%E8%A1%A3%E6%9C%8D%E6%B4%97%E4%B8%8D%E5%B9%B2%E5%87%80%E7%9A%84%E5%8E%9F%E5%9B%A0%E6%89%BE%E5%88%B0%E4%BA%86%23) `195.3K 🔥` `NEW`
1. [张凌赫没牵上然后垂下的手](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%B2%A1%E7%89%B5%E4%B8%8A%E7%84%B6%E5%90%8E%E5%9E%82%E4%B8%8B%E7%9A%84%E6%89%8B%23) `195.2K 🔥` `NEW`
1. [逐玉神级镜头加一](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%A5%9E%E7%BA%A7%E9%95%9C%E5%A4%B4%E5%8A%A0%E4%B8%80%23) `194.8K 🔥` `NEW`
1. [女子花10多元为姥姥爆改钻石拐杖](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%8A%B110%E5%A4%9A%E5%85%83%E4%B8%BA%E5%A7%A5%E5%A7%A5%E7%88%86%E6%94%B9%E9%92%BB%E7%9F%B3%E6%8B%90%E6%9D%96%23) `193.9K 🔥` `NEW`
1. [飞机上到处求摸摸的社交悍匪小狗](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E6%9C%BA%E4%B8%8A%E5%88%B0%E5%A4%84%E6%B1%82%E6%91%B8%E6%91%B8%E7%9A%84%E7%A4%BE%E4%BA%A4%E6%82%8D%E5%8C%AA%E5%B0%8F%E7%8B%97%23) `193.6K 🔥` `NEW`
1. [伊朗要求美以赔偿](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A6%81%E6%B1%82%E7%BE%8E%E4%BB%A5%E8%B5%94%E5%81%BF%23) `193.2K 🔥` `NEW`
1. [种地吧4](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A74%23) `193.0K 🔥` `NEW`
1. [温瑞博掀翻世界第二](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9A%E6%8E%80%E7%BF%BB%E4%B8%96%E7%95%8C%E7%AC%AC%E4%BA%8C%23) `192.5K 🔥` `NEW`
1. [什么样的三文鱼能生吃](https://s.weibo.com/weibo?q=%23%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%E4%B8%89%E6%96%87%E9%B1%BC%E8%83%BD%E7%94%9F%E5%90%83%23) `192.2K 🔥` `NEW`
1. [伊朗最高领袖公开声明 (Public statement by Iran's supreme leader)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E5%85%AC%E5%BC%80%E5%A3%B0%E6%98%8E%23) `192.2K 🔥` `NEW`
1. [中国女篮不敌比利时女篮](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E7%AF%AE%E4%B8%8D%E6%95%8C%E6%AF%94%E5%88%A9%E6%97%B6%E5%A5%B3%E7%AF%AE%23) `192.0K 🔥` `NEW`
1. [中方回应特朗普计划访华 (China responds to Trump's planned visit to China)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E8%AE%A1%E5%88%92%E8%AE%BF%E5%8D%8E%23) `758.4K 🔥` `+83%`
1. [伊朗空军指挥官遭袭身亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A9%BA%E5%86%9B%E6%8C%87%E6%8C%A5%E5%AE%98%E9%81%AD%E8%A2%AD%E8%BA%AB%E4%BA%A1%23) `528.5K 🔥` `+30%`
1. [中国女篮vs比利时女篮](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E7%AF%AEvs%E6%AF%94%E5%88%A9%E6%97%B6%E5%A5%B3%E7%AF%AE%23) `522.7K 🔥` `+27%`
1. [我国人均有100棵树](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E4%BA%BA%E5%9D%87%E6%9C%89100%E6%A3%B5%E6%A0%91%23) `505.0K 🔥` `+40%`
1. [两会期间单位食堂少了个碗](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%E6%9C%9F%E9%97%B4%E5%8D%95%E4%BD%8D%E9%A3%9F%E5%A0%82%E5%B0%91%E4%BA%86%E4%B8%AA%E7%A2%97%23) `485.9K 🔥` `+39%`
1. [伊朗自曝研究美军20年](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%87%AA%E6%9B%9D%E7%A0%94%E7%A9%B6%E7%BE%8E%E5%86%9B20%E5%B9%B4%23) `194.1K 🔥` `+112%`
1. [鞠婧祎彝族服饰造型](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E5%BD%9D%E6%97%8F%E6%9C%8D%E9%A5%B0%E9%80%A0%E5%9E%8B%23) `194.0K 🔥` `+67%`
1. [追觅汽车价格](https://s.weibo.com/weibo?q=%23%E8%BF%BD%E8%A7%85%E6%B1%BD%E8%BD%A6%E4%BB%B7%E6%A0%BC%23) `193.8K 🔥` `+80%`
1. [保时捷车主回应车窗被砸取AED救人](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E6%97%B6%E6%8D%B7%E8%BD%A6%E4%B8%BB%E5%9B%9E%E5%BA%94%E8%BD%A6%E7%AA%97%E8%A2%AB%E7%A0%B8%E5%8F%96AED%E6%95%91%E4%BA%BA%23) `193.5K 🔥` `+51%`
1. [爆剧 养老剧 (Explosive Drama Elder Care Drama)](https://s.weibo.com/weibo?q=%23%E7%88%86%E5%89%A7%20%E5%85%BB%E8%80%81%E5%89%A7%23) `193.3K 🔥` `+109%`
1. [逐玉 弃养一头牛 (Zhuyu abandoned a cow)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%BC%83%E5%85%BB%E4%B8%80%E5%A4%B4%E7%89%9B%23) `192.8K 🔥` `+82%`
1. [逐玉网友有偿求经纪人接吻直拍](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%BD%91%E5%8F%8B%E6%9C%89%E5%81%BF%E6%B1%82%E7%BB%8F%E7%BA%AA%E4%BA%BA%E6%8E%A5%E5%90%BB%E7%9B%B4%E6%8B%8D%23) `192.4K 🔥` `+96%`
1. [中国109项硬核项目来了 (China’s 109 hard-core projects are here)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD109%E9%A1%B9%E7%A1%AC%E6%A0%B8%E9%A1%B9%E7%9B%AE%E6%9D%A5%E4%BA%86%23) `560.9K 🔥`
1. [董明珠的Ai全家桶亮相AWE (Dong Mingzhu’s Ai family bucket debuts in AWE)](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%98%8E%E7%8F%A0%E7%9A%84Ai%E5%85%A8%E5%AE%B6%E6%A1%B6%E4%BA%AE%E7%9B%B8AWE%23) `524.0K 🔥`
1. [西安不倒翁小姐姐宣布离职 (The roly-poly girl from Xi'an announced her resignation)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%AE%89%E4%B8%8D%E5%80%92%E7%BF%81%E5%B0%8F%E5%A7%90%E5%A7%90%E5%AE%A3%E5%B8%83%E7%A6%BB%E8%81%8C%23) `383.9K 🔥`
1. [金正恩和女儿体验手枪射击](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E5%92%8C%E5%A5%B3%E5%84%BF%E4%BD%93%E9%AA%8C%E6%89%8B%E6%9E%AA%E5%B0%84%E5%87%BB%23) `246.9K 🔥`
1. [微信3大新功能 (3 new features of WeChat)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A13%E5%A4%A7%E6%96%B0%E5%8A%9F%E8%83%BD%23) `196.4K 🔥`
1. [男子误吞12厘米筷子忍了8年才取出 (Man accidentally swallowed 12cm chopsticks and endured it for 8 years before taking them out)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%AF%AF%E5%90%9E12%E5%8E%98%E7%B1%B3%E7%AD%B7%E5%AD%90%E5%BF%8D%E4%BA%868%E5%B9%B4%E6%89%8D%E5%8F%96%E5%87%BA%23) `195.8K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `195.6K 🔥`
1. [美国海军已逃离伊朗周边海域](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%B5%B7%E5%86%9B%E5%B7%B2%E9%80%83%E7%A6%BB%E4%BC%8A%E6%9C%97%E5%91%A8%E8%BE%B9%E6%B5%B7%E5%9F%9F%23) `195.0K 🔥`
1. [大学生4个馒头卖了30000元](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F4%E4%B8%AA%E9%A6%92%E5%A4%B4%E5%8D%96%E4%BA%8630000%E5%85%83%23) `194.6K 🔥`
1. [樊长玉 腮红](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%20%E8%85%AE%E7%BA%A2%23) `194.3K 🔥`
1. [伊朗称袭击了美国油轮 (Iran says it attacked US oil tanker)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E8%A2%AD%E5%87%BB%E4%BA%86%E7%BE%8E%E5%9B%BD%E6%B2%B9%E8%BD%AE%23) `192.9K 🔥`
1. [司法部将在全国统一推行扫码入企 (The Ministry of Justice will uniformly implement scanning codes to enter enterprises nationwide)](https://s.weibo.com/weibo?q=%23%E5%8F%B8%E6%B3%95%E9%83%A8%E5%B0%86%E5%9C%A8%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%A1%8C%E6%89%AB%E7%A0%81%E5%85%A5%E4%BC%81%23) `554.2K 🔥` `-26%`
1. [十四届全国人大四次会议闭幕会 (Closing Session of the Fourth Session of the 14th National People's Congress)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E9%97%AD%E5%B9%95%E4%BC%9A%23) `540.9K 🔥` `-46%`
1. [天塌了山姆的三文鱼原来不能生吃](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E5%A1%8C%E4%BA%86%E5%B1%B1%E5%A7%86%E7%9A%84%E4%B8%89%E6%96%87%E9%B1%BC%E5%8E%9F%E6%9D%A5%E4%B8%8D%E8%83%BD%E7%94%9F%E5%90%83%23) `233.0K 🔥` `-22%`
1. [谢征强吻樊长玉](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E5%BC%BA%E5%90%BB%E6%A8%8A%E9%95%BF%E7%8E%89%23) `196.2K 🔥` `-38%`
1. [白鹿把孩子塞到王鹤棣怀里](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E6%8A%8A%E5%AD%A9%E5%AD%90%E5%A1%9E%E5%88%B0%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%80%80%E9%87%8C%23) `195.6K 🔥` `-22%`
1. [ITZY召回打歌 (ITZY recalls playing songs)](https://s.weibo.com/weibo?q=%23ITZY%E5%8F%AC%E5%9B%9E%E6%89%93%E6%AD%8C%23) `194.5K 🔥` `-28%`

Updated at 2026-03-12 21:43:12

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
