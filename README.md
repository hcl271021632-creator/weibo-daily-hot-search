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

1. [北京首位马宝宝取名初一 (Beijing's first baby horse named Junior One)](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E9%A6%96%E4%BD%8D%E9%A9%AC%E5%AE%9D%E5%AE%9D%E5%8F%96%E5%90%8D%E5%88%9D%E4%B8%80%23) `1.1M 🔥` `NEW`
1. [祖国大江南北子弟兵声声祝福](https://s.weibo.com/weibo?q=%23%E7%A5%96%E5%9B%BD%E5%A4%A7%E6%B1%9F%E5%8D%97%E5%8C%97%E5%AD%90%E5%BC%9F%E5%85%B5%E5%A3%B0%E5%A3%B0%E7%A5%9D%E7%A6%8F%23) `644.3K 🔥` `NEW`
1. [首秀封神魔法原子智造未来](https://s.weibo.com/weibo?q=%23%E9%A6%96%E7%A7%80%E5%B0%81%E7%A5%9E%E9%AD%94%E6%B3%95%E5%8E%9F%E5%AD%90%E6%99%BA%E9%80%A0%E6%9C%AA%E6%9D%A5%23) `609.7K 🔥` `NEW`
1. [范丞丞这个笑太漂亮了](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E8%BF%99%E4%B8%AA%E7%AC%91%E5%A4%AA%E6%BC%82%E4%BA%AE%E4%BA%86%23) `607.6K 🔥` `NEW`
1. [春晚AI率比我论文高](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9AAI%E7%8E%87%E6%AF%94%E6%88%91%E8%AE%BA%E6%96%87%E9%AB%98%23) `599.3K 🔥` `NEW`
1. [李健怎么看叙利亚局势](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%81%A5%E6%80%8E%E4%B9%88%E7%9C%8B%E5%8F%99%E5%88%A9%E4%BA%9A%E5%B1%80%E5%8A%BF%23) `569.7K 🔥` `NEW`
1. [猫 虾的味道咪知道](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E8%99%BE%E7%9A%84%E5%91%B3%E9%81%93%E5%92%AA%E7%9F%A5%E9%81%93%23) `415.6K 🔥` `NEW`
1. [准爸爸拿B超单替宝宝给爷奶拜年](https://s.weibo.com/weibo?q=%23%E5%87%86%E7%88%B8%E7%88%B8%E6%8B%BFB%E8%B6%85%E5%8D%95%E6%9B%BF%E5%AE%9D%E5%AE%9D%E7%BB%99%E7%88%B7%E5%A5%B6%E6%8B%9C%E5%B9%B4%23) `352.3K 🔥` `NEW`
1. [想学张钧甯春晚妆容](https://s.weibo.com/weibo?q=%23%E6%83%B3%E5%AD%A6%E5%BC%A0%E9%92%A7%E7%94%AF%E6%98%A5%E6%99%9A%E5%A6%86%E5%AE%B9%23) `337.2K 🔥` `NEW`
1. [美国日本春节想针对台海搞事](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%97%A5%E6%9C%AC%E6%98%A5%E8%8A%82%E6%83%B3%E9%92%88%E5%AF%B9%E5%8F%B0%E6%B5%B7%E6%90%9E%E4%BA%8B%23) `330.7K 🔥` `NEW`
1. [王楚然春晚登场涨粉超65万 (Wang Churan's Spring Festival Gala appearance gained over 650,000 followers)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E6%98%A5%E6%99%9A%E7%99%BB%E5%9C%BA%E6%B6%A8%E7%B2%89%E8%B6%8565%E4%B8%87%23) `324.8K 🔥` `NEW`
1. [年夜饭上抽中年度猎装轿跑引爆全网](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%E4%B8%8A%E6%8A%BD%E4%B8%AD%E5%B9%B4%E5%BA%A6%E7%8C%8E%E8%A3%85%E8%BD%BF%E8%B7%91%E5%BC%95%E7%88%86%E5%85%A8%E7%BD%91%23) `311.5K 🔥` `NEW`
1. [宇树今年目标出货量1至2万台](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E4%BB%8A%E5%B9%B4%E7%9B%AE%E6%A0%87%E5%87%BA%E8%B4%A7%E9%87%8F1%E8%87%B32%E4%B8%87%E5%8F%B0%23) `304.5K 🔥` `NEW`
1. [谷爱凌转身就有妈妈在场边](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%BD%AC%E8%BA%AB%E5%B0%B1%E6%9C%89%E5%A6%88%E5%A6%88%E5%9C%A8%E5%9C%BA%E8%BE%B9%23) `263.1K 🔥` `NEW`
1. [上咪咕为徐梦桃加油](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E5%92%AA%E5%92%95%E4%B8%BA%E5%BE%90%E6%A2%A6%E6%A1%83%E5%8A%A0%E6%B2%B9%23) `256.7K 🔥` `NEW`
1. [ELLE主编朋友圈](https://s.weibo.com/weibo?q=%23ELLE%E4%B8%BB%E7%BC%96%E6%9C%8B%E5%8F%8B%E5%9C%88%23) `229.1K 🔥` `NEW`
1. [40岁朱洁静抗癌归来状态](https://s.weibo.com/weibo?q=%2340%E5%B2%81%E6%9C%B1%E6%B4%81%E9%9D%99%E6%8A%97%E7%99%8C%E5%BD%92%E6%9D%A5%E7%8A%B6%E6%80%81%23) `216.3K 🔥` `NEW`
1. [喵娲娲红包返场](https://s.weibo.com/weibo?q=%23%E5%96%B5%E5%A8%B2%E5%A8%B2%E7%BA%A2%E5%8C%85%E8%BF%94%E5%9C%BA%23) `214.3K 🔥` `NEW`
1. [交卷的时候才看见学霸的题](https://s.weibo.com/weibo?q=%23%E4%BA%A4%E5%8D%B7%E7%9A%84%E6%97%B6%E5%80%99%E6%89%8D%E7%9C%8B%E8%A7%81%E5%AD%A6%E9%9C%B8%E7%9A%84%E9%A2%98%23) `181.0K 🔥` `NEW`
1. [张小斐 你的菜正在吃菜](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%B0%8F%E6%96%90%20%E4%BD%A0%E7%9A%84%E8%8F%9C%E6%AD%A3%E5%9C%A8%E5%90%83%E8%8F%9C%23) `177.9K 🔥` `NEW`
1. [李昀锐演上白鹿助理了 (Li Yunrui plays Bailu's assistant)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E6%BC%94%E4%B8%8A%E7%99%BD%E9%B9%BF%E5%8A%A9%E7%90%86%E4%BA%86%23) `177.7K 🔥` `NEW`
1. [星河入梦](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%23) `162.7K 🔥` `NEW`
1. [陈丽君 镖人](https://s.weibo.com/weibo?q=%23%E9%99%88%E4%B8%BD%E5%90%9B%20%E9%95%96%E4%BA%BA%23) `157.2K 🔥` `NEW`
1. [原来打工人才是年兽](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E6%89%93%E5%B7%A5%E4%BA%BA%E6%89%8D%E6%98%AF%E5%B9%B4%E5%85%BD%23) `150.8K 🔥` `NEW`
1. [吃个三室一厅](https://s.weibo.com/weibo?q=%23%E5%90%83%E4%B8%AA%E4%B8%89%E5%AE%A4%E4%B8%80%E5%8E%85%23) `140.3K 🔥` `NEW`
1. [中国速滑男团冲击新历史](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%80%9F%E6%BB%91%E7%94%B7%E5%9B%A2%E5%86%B2%E5%87%BB%E6%96%B0%E5%8E%86%E5%8F%B2%23) `138.7K 🔥` `NEW`
1. [郭文韬红包](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%96%87%E9%9F%AC%E7%BA%A2%E5%8C%85%23) `138.6K 🔥` `NEW`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `775.8K 🔥` `+216%`
1. [与捷途共赴新年第一缕曙光 (Celebrate the first light of the new year with Jietu)](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E6%8D%B7%E9%80%94%E5%85%B1%E8%B5%B4%E6%96%B0%E5%B9%B4%E7%AC%AC%E4%B8%80%E7%BC%95%E6%9B%99%E5%85%89%23) `642.7K 🔥` `+30%`
1. [央妈不会找王一博赔地板吧](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E5%A6%88%E4%B8%8D%E4%BC%9A%E6%89%BE%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%B5%94%E5%9C%B0%E6%9D%BF%E5%90%A7%23) `642.2K 🔥` `+159%`
1. [谷爱凌大跳台银牌 (Gu Ailing silver medal in big platform)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A4%A7%E8%B7%B3%E5%8F%B0%E9%93%B6%E7%89%8C%23) `626.1K 🔥` `+111%`
1. [男生回应春节上门喂猫爆赚16万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E7%94%9F%E5%9B%9E%E5%BA%94%E6%98%A5%E8%8A%82%E4%B8%8A%E9%97%A8%E5%96%82%E7%8C%AB%E7%88%86%E8%B5%9A16%E4%B8%87%23) `593.4K 🔥` `+139%`
1. [很好的人都是淡淡的 (Very good people are indifferent)](https://s.weibo.com/weibo?q=%23%E5%BE%88%E5%A5%BD%E7%9A%84%E4%BA%BA%E9%83%BD%E6%98%AF%E6%B7%A1%E6%B7%A1%E7%9A%84%23) `581.8K 🔥` `+134%`
1. [春晚总导演回应机器人浓度高](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%80%BB%E5%AF%BC%E6%BC%94%E5%9B%9E%E5%BA%94%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%B5%93%E5%BA%A6%E9%AB%98%23) `578.7K 🔥` `+94%`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `353.9K 🔥` `+48%`
1. [惊蛰无声](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `352.3K 🔥` `+44%`
1. [大年初一记得别扫地别泼水](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E8%AE%B0%E5%BE%97%E5%88%AB%E6%89%AB%E5%9C%B0%E5%88%AB%E6%B3%BC%E6%B0%B4%23) `350.6K 🔥` `+44%`
1. [北京台春晚官宣节目单](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%E5%AE%98%E5%AE%A3%E8%8A%82%E7%9B%AE%E5%8D%95%23) `285.5K 🔥` `+23%`
1. [飞驰人生3](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%23) `213.4K 🔥` `+71%`
1. [林孝埈500米突出重围](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88500%E7%B1%B3%E7%AA%81%E5%87%BA%E9%87%8D%E5%9B%B4%23) `164.2K 🔥` `+35%`
1. [马宝宝出生](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%AE%9D%E5%AE%9D%E5%87%BA%E7%94%9F%23) `352.4K 🔥`
1. [春晚 (Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%23) `294.3K 🔥`
1. [钟意](https://s.weibo.com/weibo?q=%23%E9%92%9F%E6%84%8F%23) `274.2K 🔥`
1. [春晚拍出了王楚然的人生镜头 (The Spring Festival Gala captured footage of Wang Churan’s life)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%8B%8D%E5%87%BA%E4%BA%86%E7%8E%8B%E6%A5%9A%E7%84%B6%E7%9A%84%E4%BA%BA%E7%94%9F%E9%95%9C%E5%A4%B4%23) `240.5K 🔥`
1. [沈腾说错词白鹿宋威龙憋笑](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E8%AF%B4%E9%94%99%E8%AF%8D%E7%99%BD%E9%B9%BF%E5%AE%8B%E5%A8%81%E9%BE%99%E6%86%8B%E7%AC%91%23) `222.0K 🔥`
1. [宇树科技股票 (Yushu Technology Stock)](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E7%A7%91%E6%8A%80%E8%82%A1%E7%A5%A8%23) `213.6K 🔥`
1. [春节档](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E6%A1%A3%23) `196.6K 🔥`
1. [大年初一 (New Year's Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%23) `179.1K 🔥`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `619.8K 🔥` `-44%`
1. [王一博郭富城 坚持手搓](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E9%83%AD%E5%AF%8C%E5%9F%8E%20%E5%9D%9A%E6%8C%81%E6%89%8B%E6%90%93%23) `297.0K 🔥` `-49%`
1. [谁给迪丽热巴化的妆 (Who put makeup on Dilireba?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E7%BB%99%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%8C%96%E7%9A%84%E5%A6%86%23) `148.0K 🔥` `-39%`
1. [窦靖童 挖嘞个亲娘](https://s.weibo.com/weibo?q=%23%E7%AA%A6%E9%9D%96%E7%AB%A5%20%E6%8C%96%E5%98%9E%E4%B8%AA%E4%BA%B2%E5%A8%98%23) `142.2K 🔥` `-42%`

Updated at 2026-02-17 12:50:24

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
