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

1. [江湖夜雨十年灯宿命文学 (Jiang Hu Ye Yu Ten Years Lamp Fate Literature)](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E6%B9%96%E5%A4%9C%E9%9B%A8%E5%8D%81%E5%B9%B4%E7%81%AF%E5%AE%BF%E5%91%BD%E6%96%87%E5%AD%A6%23) `410.7K 🔥` `NEW`
1. [山姆520元巧克力降到99元](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86520%E5%85%83%E5%B7%A7%E5%85%8B%E5%8A%9B%E9%99%8D%E5%88%B099%E5%85%83%23) `335.8K 🔥` `NEW`
1. [突然对1g黄金没概念了](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E5%AF%B91g%E9%BB%84%E9%87%91%E6%B2%A1%E6%A6%82%E5%BF%B5%E4%BA%86%23) `299.7K 🔥` `NEW`
1. [阿联酋传出爆炸声](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%81%94%E9%85%8B%E4%BC%A0%E5%87%BA%E7%88%86%E7%82%B8%E5%A3%B0%23) `291.7K 🔥` `NEW`
1. [伊朗又一轮导弹射向以色列](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%88%E4%B8%80%E8%BD%AE%E5%AF%BC%E5%BC%B9%E5%B0%84%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `275.7K 🔥` `NEW`
1. [我家那小子](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%23) `258.4K 🔥` `NEW`
1. [一点点 植脂末](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%20%E6%A4%8D%E8%84%82%E6%9C%AB%23) `255.7K 🔥` `NEW`
1. [TOP和谷爱凌合照](https://s.weibo.com/weibo?q=%23TOP%E5%92%8C%E8%B0%B7%E7%88%B1%E5%87%8C%E5%90%88%E7%85%A7%23) `232.8K 🔥` `NEW`
1. [第五人格](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%BA%94%E4%BA%BA%E6%A0%BC%23) `224.9K 🔥` `NEW`
1. [伊朗报复行动没有任何红线](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%E6%B2%A1%E6%9C%89%E4%BB%BB%E4%BD%95%E7%BA%A2%E7%BA%BF%23) `220.6K 🔥` `NEW`
1. [嘉行否认迪丽热巴签约天伊娱乐 (Jiaxing denies Dilireba signs contract with Tianyi Entertainment)](https://s.weibo.com/weibo?q=%23%E5%98%89%E8%A1%8C%E5%90%A6%E8%AE%A4%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%AD%BE%E7%BA%A6%E5%A4%A9%E4%BC%8A%E5%A8%B1%E4%B9%90%23) `203.0K 🔥` `NEW`
1. [伊朗第三轮导弹袭击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%AC%AC%E4%B8%89%E8%BD%AE%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%23) `169.5K 🔥` `NEW`
1. [5胞胎妈妈说原打算生一男一女](https://s.weibo.com/weibo?q=%235%E8%83%9E%E8%83%8E%E5%A6%88%E5%A6%88%E8%AF%B4%E5%8E%9F%E6%89%93%E7%AE%97%E7%94%9F%E4%B8%80%E7%94%B7%E4%B8%80%E5%A5%B3%23) `152.0K 🔥` `NEW`
1. [巴林美军基地所在地巨大爆炸声](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E6%9E%97%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%E6%89%80%E5%9C%A8%E5%9C%B0%E5%B7%A8%E5%A4%A7%E7%88%86%E7%82%B8%E5%A3%B0%23) `148.4K 🔥` `NEW`
1. [薛之谦抢票](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E6%8A%A2%E7%A5%A8%23) `148.2K 🔥` `NEW`
1. [阿联酋关闭领空](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%81%94%E9%85%8B%E5%85%B3%E9%97%AD%E9%A2%86%E7%A9%BA%23) `146.7K 🔥` `NEW`
1. [伊朗还能参加美加墨世界杯吗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%BF%98%E8%83%BD%E5%8F%82%E5%8A%A0%E7%BE%8E%E5%8A%A0%E5%A2%A8%E4%B8%96%E7%95%8C%E6%9D%AF%E5%90%97%23) `142.7K 🔥` `NEW`
1. [伊朗陆军总司令身亡 (Iranian army chief dies)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%99%86%E5%86%9B%E6%80%BB%E5%8F%B8%E4%BB%A4%E8%BA%AB%E4%BA%A1%23) `3.3M 🔥` `+85%`
1. [新锐王牌问界M6七色亮相 (New Ace Wenjie M6 unveiled in seven colors)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E9%94%90%E7%8E%8B%E7%89%8C%E9%97%AE%E7%95%8CM6%E4%B8%83%E8%89%B2%E4%BA%AE%E7%9B%B8%23) `1.5M 🔥` `+129%`
1. [王楚钦好好好我不挑战了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%A5%BD%E5%A5%BD%E5%A5%BD%E6%88%91%E4%B8%8D%E6%8C%91%E6%88%98%E4%BA%86%23) `255.0K 🔥` `+38%`
1. [以色列宣布袭击伊朗](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%23) `7.4M 🔥`
1. [2025我国完成92次宇航发射 (my country completed 92 space launches in 2025)](https://s.weibo.com/weibo?q=%232025%E6%88%91%E5%9B%BD%E5%AE%8C%E6%88%9092%E6%AC%A1%E5%AE%87%E8%88%AA%E5%8F%91%E5%B0%84%23) `1.5M 🔥`
1. [德国总理从中国回去后急了 (The German Chancellor became anxious after returning from China)](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E5%9B%BD%E6%80%BB%E7%90%86%E4%BB%8E%E4%B8%AD%E5%9B%BD%E5%9B%9E%E5%8E%BB%E5%90%8E%E6%80%A5%E4%BA%86%23) `405.1K 🔥`
1. [方穆静提离婚](https://s.weibo.com/weibo?q=%23%E6%96%B9%E7%A9%86%E9%9D%99%E6%8F%90%E7%A6%BB%E5%A9%9A%23) `369.6K 🔥`
1. [小米YU9 (Xiaomi YU9)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3YU9%23) `302.2K 🔥`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `302.2K 🔥`
1. [特朗普](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%23) `301.1K 🔥`
1. [孟子义李昀锐综艺](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E7%BB%BC%E8%89%BA%23) `298.1K 🔥`
1. [王皓赛后生气了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%9A%93%E8%B5%9B%E5%90%8E%E7%94%9F%E6%B0%94%E4%BA%86%23) `297.9K 🔥`
1. [特朗普表示将彻底摧毁伊朗海军](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%A1%A8%E7%A4%BA%E5%B0%86%E5%BD%BB%E5%BA%95%E6%91%A7%E6%AF%81%E4%BC%8A%E6%9C%97%E6%B5%B7%E5%86%9B%23) `244.9K 🔥`
1. [范丞丞方说不认识没交集](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E6%96%B9%E8%AF%B4%E4%B8%8D%E8%AE%A4%E8%AF%86%E6%B2%A1%E4%BA%A4%E9%9B%86%23) `210.5K 🔥`
1. [王楚钦被裁判整无奈了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%A2%AB%E8%A3%81%E5%88%A4%E6%95%B4%E6%97%A0%E5%A5%88%E4%BA%86%23) `189.3K 🔥`
1. [伊朗高丰度浓缩铀储藏处首次曝光](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%AB%98%E4%B8%B0%E5%BA%A6%E6%B5%93%E7%BC%A9%E9%93%80%E5%82%A8%E8%97%8F%E5%A4%84%E9%A6%96%E6%AC%A1%E6%9B%9D%E5%85%89%23) `186.2K 🔥`
1. [张真源哄人这一课已经快博士毕业了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%9C%9F%E6%BA%90%E5%93%84%E4%BA%BA%E8%BF%99%E4%B8%80%E8%AF%BE%E5%B7%B2%E7%BB%8F%E5%BF%AB%E5%8D%9A%E5%A3%AB%E6%AF%95%E4%B8%9A%E4%BA%86%23) `159.4K 🔥`
1. [法耶兹性侵案受害者多达154人 (There are 154 victims in Fayyad’s sexual assault case)](https://s.weibo.com/weibo?q=%23%E6%B3%95%E8%80%B6%E5%85%B9%E6%80%A7%E4%BE%B5%E6%A1%88%E5%8F%97%E5%AE%B3%E8%80%85%E5%A4%9A%E8%BE%BE154%E4%BA%BA%23) `152.9K 🔥`
1. [宁艺卓自曝体重41公斤 (Ning Yizhuo reveals his weight is 41 kilograms)](https://s.weibo.com/weibo?q=%23%E5%AE%81%E8%89%BA%E5%8D%93%E8%87%AA%E6%9B%9D%E4%BD%93%E9%87%8D41%E5%85%AC%E6%96%A4%23) `151.5K 🔥`
1. [热巴 换经纪人](https://s.weibo.com/weibo?q=%23%E7%83%AD%E5%B7%B4%20%E6%8D%A2%E7%BB%8F%E7%BA%AA%E4%BA%BA%23) `150.8K 🔥`
1. [伊朗领导人都是打击目标](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A2%86%E5%AF%BC%E4%BA%BA%E9%83%BD%E6%98%AF%E6%89%93%E5%87%BB%E7%9B%AE%E6%A0%87%23) `146.8K 🔥`
1. [伊朗反击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%8D%E5%87%BB%23) `1.4M 🔥` `-23%`
1. [伊朗正准备毁灭性报复行动 (Iran is preparing devastating retaliation)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%87%86%E5%A4%87%E6%AF%81%E7%81%AD%E6%80%A7%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%23) `718.4K 🔥` `-39%`
1. [伊朗首都发生爆炸 (Explosion in Iranian capital)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%8F%91%E7%94%9F%E7%88%86%E7%82%B8%23) `545.8K 🔥` `-30%`
1. [曝迪丽热巴签约天伊娱乐 (It is revealed that Dilireba signed a contract with Tianyi Entertainment)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%AD%BE%E7%BA%A6%E5%A4%A9%E4%BC%8A%E5%A8%B1%E4%B9%90%23) `250.8K 🔥` `-24%`
1. [TF家族全员运动会 澳门 (TF Family Sports Meet Macau)](https://s.weibo.com/weibo?q=%23TF%E5%AE%B6%E6%97%8F%E5%85%A8%E5%91%98%E8%BF%90%E5%8A%A8%E4%BC%9A%20%E6%BE%B3%E9%97%A8%23) `244.7K 🔥` `-23%`
1. [王楚钦看林诗栋比赛摇头叹气](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E7%9C%8B%E6%9E%97%E8%AF%97%E6%A0%8B%E6%AF%94%E8%B5%9B%E6%91%87%E5%A4%B4%E5%8F%B9%E6%B0%94%23) `204.7K 🔥` `-24%`
1. [以色列监测到伊朗发射导弹](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E7%9B%91%E6%B5%8B%E5%88%B0%E4%BC%8A%E6%9C%97%E5%8F%91%E5%B0%84%E5%AF%BC%E5%BC%B9%23) `177.4K 🔥` `-30%`
1. [女子怀疑丈夫出轨闺蜜装定位被发现](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%80%80%E7%96%91%E4%B8%88%E5%A4%AB%E5%87%BA%E8%BD%A8%E9%97%BA%E8%9C%9C%E8%A3%85%E5%AE%9A%E4%BD%8D%E8%A2%AB%E5%8F%91%E7%8E%B0%23) `173.3K 🔥` `-33%`
1. [一点点回应](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E5%9B%9E%E5%BA%94%23) `172.8K 🔥` `-35%`
1. [头一回见仅付款的](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E4%B8%80%E5%9B%9E%E8%A7%81%E4%BB%85%E4%BB%98%E6%AC%BE%E7%9A%84%23) `172.7K 🔥` `-30%`
1. [导弹飞越伊拉克画面曝光](https://s.weibo.com/weibo?q=%23%E5%AF%BC%E5%BC%B9%E9%A3%9E%E8%B6%8A%E4%BC%8A%E6%8B%89%E5%85%8B%E7%94%BB%E9%9D%A2%E6%9B%9D%E5%85%89%23) `170.3K 🔥` `-30%`
1. [美军航母参与空袭伊朗 (US aircraft carrier participates in air strike on Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E8%88%AA%E6%AF%8D%E5%8F%82%E4%B8%8E%E7%A9%BA%E8%A2%AD%E4%BC%8A%E6%9C%97%23) `145.2K 🔥` `-21%`
1. [伊朗总统府遭袭 (Iranian presidential palace attacked)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E5%BA%9C%E9%81%AD%E8%A2%AD%23) `143.0K 🔥` `-22%`
1. [九亿少女的梦](https://s.weibo.com/weibo?q=%23%E4%B9%9D%E4%BA%BF%E5%B0%91%E5%A5%B3%E7%9A%84%E6%A2%A6%23) `138.4K 🔥` `-46%`

Updated at 2026-02-28 17:45:23

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
