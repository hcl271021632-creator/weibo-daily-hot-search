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

1. [骏马贺新春电子贺卡 (Horse Happy New Year e-card)](https://s.weibo.com/weibo?q=%23%E9%AA%8F%E9%A9%AC%E8%B4%BA%E6%96%B0%E6%98%A5%E7%94%B5%E5%AD%90%E8%B4%BA%E5%8D%A1%23) `608.6K 🔥` `NEW`
1. [北京台春晚](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%23) `599.5K 🔥` `NEW`
1. [江苏卫视春晚](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E8%8B%8F%E5%8D%AB%E8%A7%86%E6%98%A5%E6%99%9A%23) `245.7K 🔥` `NEW`
1. [很火但难吃的小吃](https://s.weibo.com/weibo?q=%23%E5%BE%88%E7%81%AB%E4%BD%86%E9%9A%BE%E5%90%83%E7%9A%84%E5%B0%8F%E5%90%83%23) `244.7K 🔥` `NEW`
1. [多地居民家中开启彩灯PK](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E5%B1%85%E6%B0%91%E5%AE%B6%E4%B8%AD%E5%BC%80%E5%90%AF%E5%BD%A9%E7%81%AFPK%23) `242.5K 🔥` `NEW`
1. [不是年味淡了而是轮到我们做主了](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%98%AF%E5%B9%B4%E5%91%B3%E6%B7%A1%E4%BA%86%E8%80%8C%E6%98%AF%E8%BD%AE%E5%88%B0%E6%88%91%E4%BB%AC%E5%81%9A%E4%B8%BB%E4%BA%86%23) `217.8K 🔥` `NEW`
1. [北京台春晚节目单](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `167.8K 🔥` `NEW`
1. [全国初二回娘家的女婿belike](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E5%88%9D%E4%BA%8C%E5%9B%9E%E5%A8%98%E5%AE%B6%E7%9A%84%E5%A5%B3%E5%A9%BFbelike%23) `156.4K 🔥` `NEW`
1. [小酒窝和朵朵拜年合照](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%85%92%E7%AA%9D%E5%92%8C%E6%9C%B5%E6%9C%B5%E6%8B%9C%E5%B9%B4%E5%90%88%E7%85%A7%23) `154.8K 🔥` `NEW`
1. [浙江卫视春晚](https://s.weibo.com/weibo?q=%23%E6%B5%99%E6%B1%9F%E5%8D%AB%E8%A7%86%E6%98%A5%E6%99%9A%23) `139.4K 🔥` `NEW`
1. [TF家族族综 (TF family comprehensive)](https://s.weibo.com/weibo?q=%23TF%E5%AE%B6%E6%97%8F%E6%97%8F%E7%BB%BC%23) `135.3K 🔥` `NEW`
1. [王菲春晚原唱是李雪琴北大闺蜜](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E6%98%A5%E6%99%9A%E5%8E%9F%E5%94%B1%E6%98%AF%E6%9D%8E%E9%9B%AA%E7%90%B4%E5%8C%97%E5%A4%A7%E9%97%BA%E8%9C%9C%23) `120.9K 🔥` `NEW`
1. [东北嫡长闺具象化了](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E5%8C%97%E5%AB%A1%E9%95%BF%E9%97%BA%E5%85%B7%E8%B1%A1%E5%8C%96%E4%BA%86%23) `113.1K 🔥` `NEW`
1. [东方卫视春晚](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E6%96%B9%E5%8D%AB%E8%A7%86%E6%98%A5%E6%99%9A%23) `107.1K 🔥` `NEW`
1. [网友AI创作特朗普异国版走红](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8BAI%E5%88%9B%E4%BD%9C%E7%89%B9%E6%9C%97%E6%99%AE%E5%BC%82%E5%9B%BD%E7%89%88%E8%B5%B0%E7%BA%A2%23) `103.4K 🔥` `NEW`
1. [谷爱凌U型场地数据近乎完美 (Gu Ailing’s U-shaped field data is almost perfect)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E5%9E%8B%E5%9C%BA%E5%9C%B0%E6%95%B0%E6%8D%AE%E8%BF%91%E4%B9%8E%E5%AE%8C%E7%BE%8E%23) `1.0M 🔥` `+38%`
1. [大年初一机票价格腰斩 (Air ticket prices halved on New Year's Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E6%9C%BA%E7%A5%A8%E4%BB%B7%E6%A0%BC%E8%85%B0%E6%96%A9%23) `757.1K 🔥` `+321%`
1. [大年初一不煮饭 (No cooking on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E7%85%AE%E9%A5%AD%23) `600.6K 🔥` `+247%`
1. [13个00后发小给彼此父母磕头拜年](https://s.weibo.com/weibo?q=%2313%E4%B8%AA00%E5%90%8E%E5%8F%91%E5%B0%8F%E7%BB%99%E5%BD%BC%E6%AD%A4%E7%88%B6%E6%AF%8D%E7%A3%95%E5%A4%B4%E6%8B%9C%E5%B9%B4%23) `599.6K 🔥` `+411%`
1. [看飞驰人生接美的好风 (Watch the beautiful scenery of flying life)](https://s.weibo.com/weibo?q=%23%E7%9C%8B%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F%E6%8E%A5%E7%BE%8E%E7%9A%84%E5%A5%BD%E9%A3%8E%23) `599.4K 🔥` `+101%`
1. [王楚然一脸懵不像演的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E4%B8%80%E8%84%B8%E6%87%B5%E4%B8%8D%E5%83%8F%E6%BC%94%E7%9A%84%23) `599.4K 🔥` `+248%`
1. [爸妈来后冰箱都变老了 (The refrigerator has become old since my parents came here.)](https://s.weibo.com/weibo?q=%23%E7%88%B8%E5%A6%88%E6%9D%A5%E5%90%8E%E5%86%B0%E7%AE%B1%E9%83%BD%E5%8F%98%E8%80%81%E4%BA%86%23) `260.8K 🔥` `+53%`
1. [飞驰人生3票房](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E7%A5%A8%E6%88%BF%23) `257.7K 🔥` `+49%`
1. [镖人 武侠群像](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E6%AD%A6%E4%BE%A0%E7%BE%A4%E5%83%8F%23) `256.9K 🔥` `+52%`
1. [Kimi估值超100亿美元](https://s.weibo.com/weibo?q=%23Kimi%E4%BC%B0%E5%80%BC%E8%B6%85100%E4%BA%BF%E7%BE%8E%E5%85%83%23) `245.8K 🔥` `+47%`
1. [杨幂朱一龙吻戏 (Yang Mi and Zhu Yilong kiss scene)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9C%B1%E4%B8%80%E9%BE%99%E5%90%BB%E6%88%8F%23) `245.2K 🔥` `+46%`
1. [千问江浙沪春晚给你发红包](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E6%B1%9F%E6%B5%99%E6%B2%AA%E6%98%A5%E6%99%9A%E7%BB%99%E4%BD%A0%E5%8F%91%E7%BA%A2%E5%8C%85%23) `244.5K 🔥` `+47%`
1. [镖人 排片](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E6%8E%92%E7%89%87%23) `244.1K 🔥` `+95%`
1. [俄罗斯民众冒雪看春晚](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%E6%B0%91%E4%BC%97%E5%86%92%E9%9B%AA%E7%9C%8B%E6%98%A5%E6%99%9A%23) `243.7K 🔥` `+84%`
1. [大年初一不能做哪些事 (What not to do on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E8%83%BD%E5%81%9A%E5%93%AA%E4%BA%9B%E4%BA%8B%23) `242.9K 🔥` `+47%`
1. [开始吃剩菜](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E5%90%83%E5%89%A9%E8%8F%9C%23) `242.8K 🔥` `+47%`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `241.7K 🔥` `+43%`
1. [惊蛰无声票房](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%E7%A5%A8%E6%88%BF%23) `241.3K 🔥` `+42%`
1. [星河入梦 黑马 (Starry River Dreaming Dark Horse)](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%20%E9%BB%91%E9%A9%AC%23) `241.3K 🔥` `+44%`
1. [迪丽热巴穿红色太惊艳 (Dilireba looks so stunning in red)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%A9%BF%E7%BA%A2%E8%89%B2%E5%A4%AA%E6%83%8A%E8%89%B3%23) `226.9K 🔥` `+39%`
1. [时代少年团红包](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E7%BA%A2%E5%8C%85%23) `217.8K 🔥` `+95%`
1. [砂糖橘这样摆太有年味了 (The sugar oranges displayed like this look so festive.)](https://s.weibo.com/weibo?q=%23%E7%A0%82%E7%B3%96%E6%A9%98%E8%BF%99%E6%A0%B7%E6%91%86%E5%A4%AA%E6%9C%89%E5%B9%B4%E5%91%B3%E4%BA%86%23) `217.6K 🔥` `+37%`
1. [徐梦桃齐广璞今日出战](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E9%BD%90%E5%B9%BF%E7%92%9E%E4%BB%8A%E6%97%A5%E5%87%BA%E6%88%98%23) `217.4K 🔥` `+110%`
1. [千问带着杨丽萍万马奔腾出海了](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%B8%A6%E7%9D%80%E6%9D%A8%E4%B8%BD%E8%90%8D%E4%B8%87%E9%A9%AC%E5%A5%94%E8%85%BE%E5%87%BA%E6%B5%B7%E4%BA%86%23) `217.3K 🔥` `+37%`
1. [中国冰壶男队8比5美国队 (Chinese men's curling team 8-5 US team)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%86%B0%E5%A3%B6%E7%94%B7%E9%98%9F8%E6%AF%945%E7%BE%8E%E5%9B%BD%E9%98%9F%23) `217.2K 🔥` `+32%`
1. [老君山惊现灵气护罩](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%90%9B%E5%B1%B1%E6%83%8A%E7%8E%B0%E7%81%B5%E6%B0%94%E6%8A%A4%E7%BD%A9%23) `217.1K 🔥` `+74%`
1. [36岁为什么还来主持人大赛 为今天](https://s.weibo.com/weibo?q=%2336%E5%B2%81%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BF%98%E6%9D%A5%E4%B8%BB%E6%8C%81%E4%BA%BA%E5%A4%A7%E8%B5%9B%20%E4%B8%BA%E4%BB%8A%E5%A4%A9%23) `217.0K 🔥` `+31%`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `208.4K 🔥` `+32%`
1. [押中春晚魔术博主称对不起邓男子](https://s.weibo.com/weibo?q=%23%E6%8A%BC%E4%B8%AD%E6%98%A5%E6%99%9A%E9%AD%94%E6%9C%AF%E5%8D%9A%E4%B8%BB%E7%A7%B0%E5%AF%B9%E4%B8%8D%E8%B5%B7%E9%82%93%E7%94%B7%E5%AD%90%23) `182.9K 🔥`
1. [王楚然春晚20秒破2亿](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E6%98%A5%E6%99%9A20%E7%A7%92%E7%A0%B42%E4%BA%BF%23) `176.0K 🔥`
1. [刘浩存拜年](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%E6%8B%9C%E5%B9%B4%23) `150.6K 🔥`
1. [13个发小初一登门给彼此父母磕头拜年 (13 primary school students came to kowtow to each other’s parents to pay New Year greetings)](https://s.weibo.com/weibo?q=%2313%E4%B8%AA%E5%8F%91%E5%B0%8F%E5%88%9D%E4%B8%80%E7%99%BB%E9%97%A8%E7%BB%99%E5%BD%BC%E6%AD%A4%E7%88%B6%E6%AF%8D%E7%A3%95%E5%A4%B4%E6%8B%9C%E5%B9%B4%23) `150.1K 🔥`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `150.0K 🔥`
1. [冬奥女选手庆祝举动或赚百万美元](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E5%A5%B3%E9%80%89%E6%89%8B%E5%BA%86%E7%A5%9D%E4%B8%BE%E5%8A%A8%E6%88%96%E8%B5%9A%E7%99%BE%E4%B8%87%E7%BE%8E%E5%85%83%23) `136.9K 🔥`
1. [23个小辈拜年舅舅给每人发100元红包](https://s.weibo.com/weibo?q=%2323%E4%B8%AA%E5%B0%8F%E8%BE%88%E6%8B%9C%E5%B9%B4%E8%88%85%E8%88%85%E7%BB%99%E6%AF%8F%E4%BA%BA%E5%8F%91100%E5%85%83%E7%BA%A2%E5%8C%85%23) `230.5K 🔥` `-78%`
1. [央妈不会找王一博赔地板吧](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E5%A6%88%E4%B8%8D%E4%BC%9A%E6%89%BE%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%B5%94%E5%9C%B0%E6%9D%BF%E5%90%A7%23) `111.8K 🔥` `-30%`

Updated at 2026-02-17 19:59:45

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
