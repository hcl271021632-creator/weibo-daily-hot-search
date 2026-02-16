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

1. [春晚 (Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%23) `7.9M 🔥` `NEW`
1. [中国短道队男子5000米无缘决赛](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%AD%E9%81%93%E9%98%9F%E7%94%B7%E5%AD%905000%E7%B1%B3%E6%97%A0%E7%BC%98%E5%86%B3%E8%B5%9B%23) `822.5K 🔥` `NEW`
1. [春晚后台直播](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%90%8E%E5%8F%B0%E7%9B%B4%E6%92%AD%23) `602.4K 🔥` `NEW`
1. [2026年为啥晚春节](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E4%B8%BA%E5%95%A5%E6%99%9A%E6%98%A5%E8%8A%82%23) `571.6K 🔥` `NEW`
1. [周深第三次春晚独唱](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B1%E7%AC%AC%E4%B8%89%E6%AC%A1%E6%98%A5%E6%99%9A%E7%8B%AC%E5%94%B1%23) `560.7K 🔥` `NEW`
1. [短道速滑男子5000米接力](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E7%94%B7%E5%AD%905000%E7%B1%B3%E6%8E%A5%E5%8A%9B%23) `262.3K 🔥` `NEW`
1. [刘瀚彬蓄力团体追逐半决赛](https://s.weibo.com/weibo?q=%23%E5%88%98%E7%80%9A%E5%BD%AC%E8%93%84%E5%8A%9B%E5%9B%A2%E4%BD%93%E8%BF%BD%E9%80%90%E5%8D%8A%E5%86%B3%E8%B5%9B%23) `260.6K 🔥` `NEW`
1. [田曦薇好萌](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%A5%BD%E8%90%8C%23) `253.4K 🔥` `NEW`
1. [陈哲远红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%E7%BA%A2%E5%8C%85%23) `232.2K 🔥` `NEW`
1. [丁程鑫年会发了66666](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E5%B9%B4%E4%BC%9A%E5%8F%91%E4%BA%8666666%23) `220.6K 🔥` `NEW`
1. [谁懂啊春晚骐骥竟然不是马 (Who knew that Qi Ji in the Spring Festival Gala was not a horse?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%87%82%E5%95%8A%E6%98%A5%E6%99%9A%E9%AA%90%E9%AA%A5%E7%AB%9F%E7%84%B6%E4%B8%8D%E6%98%AF%E9%A9%AC%23) `207.4K 🔥` `NEW`
1. [张凌赫发了好多红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%8F%91%E4%BA%86%E5%A5%BD%E5%A4%9A%E7%BA%A2%E5%8C%85%23) `207.2K 🔥` `NEW`
1. [九尾家的年夜饭](https://s.weibo.com/weibo?q=%23%E4%B9%9D%E5%B0%BE%E5%AE%B6%E7%9A%84%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `206.7K 🔥` `NEW`
1. [王俊凯 大师炫技之作](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%20%E5%A4%A7%E5%B8%88%E7%82%AB%E6%8A%80%E4%B9%8B%E4%BD%9C%23) `206.7K 🔥` `NEW`
1. [时代峰峻年会](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E5%B9%B4%E4%BC%9A%23) `206.2K 🔥` `NEW`
1. [王鹤棣红包](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E7%BA%A2%E5%8C%85%23) `205.0K 🔥` `NEW`
1. [奥巴马改口了](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E5%B7%B4%E9%A9%AC%E6%94%B9%E5%8F%A3%E4%BA%86%23) `203.1K 🔥` `NEW`
1. [宋威龙红包](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%A8%81%E9%BE%99%E7%BA%A2%E5%8C%85%23) `179.5K 🔥` `NEW`
1. [年夜饭文案](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%E6%96%87%E6%A1%88%23) `176.0K 🔥` `NEW`
1. [鹤壁网民发布盖印钞厂谣言被处罚](https://s.weibo.com/weibo?q=%23%E9%B9%A4%E5%A3%81%E7%BD%91%E6%B0%91%E5%8F%91%E5%B8%83%E7%9B%96%E5%8D%B0%E9%92%9E%E5%8E%82%E8%B0%A3%E8%A8%80%E8%A2%AB%E5%A4%84%E7%BD%9A%23) `3.7M 🔥` `+431%`
1. [献给汽修工人李尚国 (Dedicated to auto repairman Li Shangguo)](https://s.weibo.com/weibo?q=%23%E7%8C%AE%E7%BB%99%E6%B1%BD%E4%BF%AE%E5%B7%A5%E4%BA%BA%E6%9D%8E%E5%B0%9A%E5%9B%BD%23) `2.8M 🔥` `+29%`
1. [易烊千玺邀你上千问领红包](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E9%82%80%E4%BD%A0%E4%B8%8A%E5%8D%83%E9%97%AE%E9%A2%86%E7%BA%A2%E5%8C%85%23) `370.4K 🔥` `+30%`
1. [千问红包 (Qianwen red envelope)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E7%BA%A2%E5%8C%85%23) `369.1K 🔥` `+22%`
1. [张碧晨晚饭后还有红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%A2%A7%E6%99%A8%E6%99%9A%E9%A5%AD%E5%90%8E%E8%BF%98%E6%9C%89%E7%BA%A2%E5%8C%85%23) `256.3K 🔥` `+38%`
1. [新年祝福语](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%B9%B4%E7%A5%9D%E7%A6%8F%E8%AF%AD%23) `251.3K 🔥` `+46%`
1. [春晚节目单 (Spring Festival Gala Program)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `8.3M 🔥`
1. [年夜饭](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `875.3K 🔥`
1. [短道速滑 (short track speed skating)](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `680.5K 🔥`
1. [迪丽热巴人鱼公主](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%BA%BA%E9%B1%BC%E5%85%AC%E4%B8%BB%23) `570.2K 🔥`
1. [冬奥短道速滑男子500米预赛](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E7%94%B7%E5%AD%90500%E7%B1%B3%E9%A2%84%E8%B5%9B%23) `465.5K 🔥`
1. [陈楚生 我们春天见](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%A5%9A%E7%94%9F%20%E6%88%91%E4%BB%AC%E6%98%A5%E5%A4%A9%E8%A7%81%23) `207.5K 🔥`
1. [孟子义 先发美图再发红包](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%20%E5%85%88%E5%8F%91%E7%BE%8E%E5%9B%BE%E5%86%8D%E5%8F%91%E7%BA%A2%E5%8C%85%23) `206.3K 🔥`
1. [林孝埈500米顺利晋级](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88500%E7%B1%B3%E9%A1%BA%E5%88%A9%E6%99%8B%E7%BA%A7%23) `206.3K 🔥`
1. [王一博出图 (Photo by Wang Yibo)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%87%BA%E5%9B%BE%23) `206.0K 🔥`
1. [千问能不能帮我自动抢红包](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E8%83%BD%E4%B8%8D%E8%83%BD%E5%B8%AE%E6%88%91%E8%87%AA%E5%8A%A8%E6%8A%A2%E7%BA%A2%E5%8C%85%23) `205.7K 🔥`
1. [成毅的年夜饭 (Cheng Yi’s New Year’s Eve dinner)](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%E7%9A%84%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `202.3K 🔥`
1. [春晚时间](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%97%B6%E9%97%B4%23) `200.6K 🔥`
1. [浙江压岁钱 (Zhejiang lucky money)](https://s.weibo.com/weibo?q=%23%E6%B5%99%E6%B1%9F%E5%8E%8B%E5%B2%81%E9%92%B1%23) `199.3K 🔥`
1. [李一桐定时红包](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%B8%80%E6%A1%90%E5%AE%9A%E6%97%B6%E7%BA%A2%E5%8C%85%23) `190.5K 🔥`
1. [除夕 (Lunar New Year's eve)](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%23) `169.5K 🔥`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `17.0M 🔥` `-44%`
1. [白鹿红包预告 (White Deer Red Envelope Preview)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E7%BA%A2%E5%8C%85%E9%A2%84%E5%91%8A%23) `5.4M 🔥` `-58%`
1. [除夕祝你万事胜意](https://s.weibo.com/weibo?q=%23%E9%99%A4%E5%A4%95%E7%A5%9D%E4%BD%A0%E4%B8%87%E4%BA%8B%E8%83%9C%E6%84%8F%23) `3.2M 🔥` `-23%`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `597.4K 🔥` `-40%`
1. [敖瑞鹏发红包还有前菜 (Ao Ruipeng gave out red envelopes and appetizers)](https://s.weibo.com/weibo?q=%23%E6%95%96%E7%91%9E%E9%B9%8F%E5%8F%91%E7%BA%A2%E5%8C%85%E8%BF%98%E6%9C%89%E5%89%8D%E8%8F%9C%23) `455.5K 🔥` `-49%`
1. [红包分组 (Red envelope grouping)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%E5%88%86%E7%BB%84%23) `321.3K 🔥` `-39%`
1. [孙龙500米pen](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%BE%99500%E7%B1%B3pen%23) `207.7K 🔥` `-33%`
1. [陈哲远 15万红包](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%2015%E4%B8%87%E7%BA%A2%E5%8C%85%23) `207.0K 🔥` `-33%`
1. [时代少年团楼晚特别栏目](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E6%A5%BC%E6%99%9A%E7%89%B9%E5%88%AB%E6%A0%8F%E7%9B%AE%23) `185.6K 🔥` `-36%`
1. [刘少昂500米晋级 (Liu Shaoang advances in 500m)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82500%E7%B1%B3%E6%99%8B%E7%BA%A7%23) `180.0K 🔥` `-28%`
1. [TOP红包](https://s.weibo.com/weibo?q=%23TOP%E7%BA%A2%E5%8C%85%23) `178.8K 🔥` `-25%`

Updated at 2026-02-16 19:53:41

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
