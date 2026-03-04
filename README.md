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

1. [投号共识 (Voting consensus)](https://s.weibo.com/weibo?q=%23%E6%8A%95%E5%8F%B7%E5%85%B1%E8%AF%86%23) `780.8K 🔥` `NEW`
1. [烤肉店辣椒水是干嘛的](https://s.weibo.com/weibo?q=%23%E7%83%A4%E8%82%89%E5%BA%97%E8%BE%A3%E6%A4%92%E6%B0%B4%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%23) `764.5K 🔥` `NEW`
1. [建议将农村养老金提升至500元每人每月](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%86%E5%86%9C%E6%9D%91%E5%85%BB%E8%80%81%E9%87%91%E6%8F%90%E5%8D%87%E8%87%B3500%E5%85%83%E6%AF%8F%E4%BA%BA%E6%AF%8F%E6%9C%88%23) `757.4K 🔥` `NEW`
1. [阿瑟又白干了](https://s.weibo.com/weibo?q=%23%E9%98%BF%E7%91%9F%E5%8F%88%E7%99%BD%E5%B9%B2%E4%BA%86%23) `236.6K 🔥` `NEW`
1. [方圆鼻子上的疤痕](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%9C%86%E9%BC%BB%E5%AD%90%E4%B8%8A%E7%9A%84%E7%96%A4%E7%97%95%23) `232.4K 🔥` `NEW`
1. [建议高考英语降为100分](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%AB%98%E8%80%83%E8%8B%B1%E8%AF%AD%E9%99%8D%E4%B8%BA100%E5%88%86%23) `224.4K 🔥` `NEW`
1. [全球股市全线暴跌](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E8%82%A1%E5%B8%82%E5%85%A8%E7%BA%BF%E6%9A%B4%E8%B7%8C%23) `224.0K 🔥` `NEW`
1. [这竟然是甄嬛传里的温宜公主](https://s.weibo.com/weibo?q=%23%E8%BF%99%E7%AB%9F%E7%84%B6%E6%98%AF%E7%94%84%E5%AC%9B%E4%BC%A0%E9%87%8C%E7%9A%84%E6%B8%A9%E5%AE%9C%E5%85%AC%E4%B8%BB%23) `195.5K 🔥` `NEW`
1. [美军公布最新伤亡情况](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E5%85%AC%E5%B8%83%E6%9C%80%E6%96%B0%E4%BC%A4%E4%BA%A1%E6%83%85%E5%86%B5%23) `147.9K 🔥` `NEW`
1. [晒出属于你的光](https://s.weibo.com/weibo?q=%23%E6%99%92%E5%87%BA%E5%B1%9E%E4%BA%8E%E4%BD%A0%E7%9A%84%E5%85%89%23) `126.1K 🔥` `NEW`
1. [护肤界黑马PDRN迎来新突破 (PDRN, a dark horse in the skin care industry, ushered in new breakthroughs)](https://s.weibo.com/weibo?q=%23%E6%8A%A4%E8%82%A4%E7%95%8C%E9%BB%91%E9%A9%ACPDRN%E8%BF%8E%E6%9D%A5%E6%96%B0%E7%AA%81%E7%A0%B4%23) `111.8K 🔥` `NEW`
1. [决不允许任何外部势力干涉中国内政](https://s.weibo.com/weibo?q=%23%E5%86%B3%E4%B8%8D%E5%85%81%E8%AE%B8%E4%BB%BB%E4%BD%95%E5%A4%96%E9%83%A8%E5%8A%BF%E5%8A%9B%E5%B9%B2%E6%B6%89%E4%B8%AD%E5%9B%BD%E5%86%85%E6%94%BF%23) `104.8K 🔥` `NEW`
1. [为中美合作开辟更广阔空间](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%B8%AD%E7%BE%8E%E5%90%88%E4%BD%9C%E5%BC%80%E8%BE%9F%E6%9B%B4%E5%B9%BF%E9%98%94%E7%A9%BA%E9%97%B4%23) `104.3K 🔥` `NEW`
1. [建议居民身份证去地址化](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B1%85%E6%B0%91%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%8E%BB%E5%9C%B0%E5%9D%80%E5%8C%96%23) `102.3K 🔥` `NEW`
1. [春天是精神病的高发时期](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%A4%A9%E6%98%AF%E7%B2%BE%E7%A5%9E%E7%97%85%E7%9A%84%E9%AB%98%E5%8F%91%E6%97%B6%E6%9C%9F%23) `100.3K 🔥` `NEW`
1. [一菲和诺澜在短剧二搭了](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%8F%B2%E5%92%8C%E8%AF%BA%E6%BE%9C%E5%9C%A8%E7%9F%AD%E5%89%A7%E4%BA%8C%E6%90%AD%E4%BA%86%23) `93.4K 🔥` `NEW`
1. [鹅鸭杀新角色肉汁小丑](https://s.weibo.com/weibo?q=%23%E9%B9%85%E9%B8%AD%E6%9D%80%E6%96%B0%E8%A7%92%E8%89%B2%E8%82%89%E6%B1%81%E5%B0%8F%E4%B8%91%23) `83.1K 🔥` `NEW`
1. [飞驰人生3暂列全球票房年榜第一](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E6%9A%82%E5%88%97%E5%85%A8%E7%90%83%E7%A5%A8%E6%88%BF%E5%B9%B4%E6%A6%9C%E7%AC%AC%E4%B8%80%23) `814.0K 🔥` `+192%`
1. [跟刘宇宁来京东38节领五色花 (Follow Liu Yuning to JD.com’s 38th Festival to receive colorful flowers)](https://s.weibo.com/weibo?q=%23%E8%B7%9F%E5%88%98%E5%AE%87%E5%AE%81%E6%9D%A5%E4%BA%AC%E4%B8%9C38%E8%8A%82%E9%A2%86%E4%BA%94%E8%89%B2%E8%8A%B1%23) `810.2K 🔥` `+21%`
1. [建议基础教育学制缩短为532](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%9F%BA%E7%A1%80%E6%95%99%E8%82%B2%E5%AD%A6%E5%88%B6%E7%BC%A9%E7%9F%AD%E4%B8%BA532%23) `806.6K 🔥` `+147%`
1. [两会 (two sessions)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `794.2K 🔥` `+385%`
1. [伊朗首都全天遭轮番打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%85%A8%E5%A4%A9%E9%81%AD%E8%BD%AE%E7%95%AA%E6%89%93%E5%87%BB%23) `789.4K 🔥` `+172%`
1. [恋与深空 (Love and deep space)](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%23) `777.2K 🔥` `+367%`
1. [北京下雪 (It's snowing in Beijing)](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E4%B8%8B%E9%9B%AA%23) `773.2K 🔥` `+163%`
1. [岳雨婷 人在巴黎缺席看秀](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%20%E4%BA%BA%E5%9C%A8%E5%B7%B4%E9%BB%8E%E7%BC%BA%E5%B8%AD%E7%9C%8B%E7%A7%80%23) `754.5K 🔥` `+245%`
1. [复旦大学生活码 复活码](https://s.weibo.com/weibo?q=%23%E5%A4%8D%E6%97%A6%E5%A4%A7%E5%AD%A6%E7%94%9F%E6%B4%BB%E7%A0%81%20%E5%A4%8D%E6%B4%BB%E7%A0%81%23) `417.0K 🔥` `+216%`
1. [郭晓婷说王天辰吻戏像牛耕地](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%93%E5%A9%B7%E8%AF%B4%E7%8E%8B%E5%A4%A9%E8%BE%B0%E5%90%BB%E6%88%8F%E5%83%8F%E7%89%9B%E8%80%95%E5%9C%B0%23) `410.4K 🔥` `+89%`
1. [雨天午睡很舒服就要小心了](https://s.weibo.com/weibo?q=%23%E9%9B%A8%E5%A4%A9%E5%8D%88%E7%9D%A1%E5%BE%88%E8%88%92%E6%9C%8D%E5%B0%B1%E8%A6%81%E5%B0%8F%E5%BF%83%E4%BA%86%23) `373.6K 🔥` `+85%`
1. [赖伟明学范丞丞的手势舞 照抄广告](https://s.weibo.com/weibo?q=%23%E8%B5%96%E4%BC%9F%E6%98%8E%E5%AD%A6%E8%8C%83%E4%B8%9E%E4%B8%9E%E7%9A%84%E6%89%8B%E5%8A%BF%E8%88%9E%20%E7%85%A7%E6%8A%84%E5%B9%BF%E5%91%8A%23) `323.6K 🔥` `+52%`
1. [没有性生活也会感染HPV吗](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E6%9C%89%E6%80%A7%E7%94%9F%E6%B4%BB%E4%B9%9F%E4%BC%9A%E6%84%9F%E6%9F%93HPV%E5%90%97%23) `318.3K 🔥` `+90%`
1. [杨幂汤圆头像](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%B1%A4%E5%9C%86%E5%A4%B4%E5%83%8F%23) `300.9K 🔥` `+42%`
1. [淘宝凑齐短剧四小花旦](https://s.weibo.com/weibo?q=%23%E6%B7%98%E5%AE%9D%E5%87%91%E9%BD%90%E7%9F%AD%E5%89%A7%E5%9B%9B%E5%B0%8F%E8%8A%B1%E6%97%A6%23) `259.1K 🔥` `+54%`
1. [肛门周围长东西一定是痔疮吗 (Is the growth around the anus definitely hemorrhoids?)](https://s.weibo.com/weibo?q=%23%E8%82%9B%E9%97%A8%E5%91%A8%E5%9B%B4%E9%95%BF%E4%B8%9C%E8%A5%BF%E4%B8%80%E5%AE%9A%E6%98%AF%E7%97%94%E7%96%AE%E5%90%97%23) `230.8K 🔥` `+50%`
1. [甘肃地震](https://s.weibo.com/weibo?q=%23%E7%94%98%E8%82%83%E5%9C%B0%E9%9C%87%23) `178.4K 🔥` `+57%`
1. [建议彩礼金额不超过6万元 (It is recommended that the amount of the betrothal gift should not exceed 60,000 yuan)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%BD%A9%E7%A4%BC%E9%87%91%E9%A2%9D%E4%B8%8D%E8%B6%85%E8%BF%876%E4%B8%87%E5%85%83%23) `1.1M 🔥`
1. [2026两会日程预告 (2026 Two Sessions Schedule Preview)](https://s.weibo.com/weibo?q=%232026%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%E9%A2%84%E5%91%8A%23) `810.4K 🔥`
1. [伊朗导弹击中美第五舰队总部瞬间](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%87%BB%E4%B8%AD%E7%BE%8E%E7%AC%AC%E4%BA%94%E8%88%B0%E9%98%9F%E6%80%BB%E9%83%A8%E7%9E%AC%E9%97%B4%23) `238.9K 🔥`
1. [霍尔木兹海峡十多艘油轮被炮弹击中](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%8D%81%E5%A4%9A%E8%89%98%E6%B2%B9%E8%BD%AE%E8%A2%AB%E7%82%AE%E5%BC%B9%E5%87%BB%E4%B8%AD%23) `198.7K 🔥`
1. [吃一口饭倒欠200卡路里](https://s.weibo.com/weibo?q=%23%E5%90%83%E4%B8%80%E5%8F%A3%E9%A5%AD%E5%80%92%E6%AC%A0200%E5%8D%A1%E8%B7%AF%E9%87%8C%23) `195.8K 🔥`
1. [伊朗称击毁美军第三套萨德系统](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%87%BB%E6%AF%81%E7%BE%8E%E5%86%9B%E7%AC%AC%E4%B8%89%E5%A5%97%E8%90%A8%E5%BE%B7%E7%B3%BB%E7%BB%9F%23) `151.3K 🔥`
1. [十四届全国人大四次会议议程](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E8%AE%AE%E7%A8%8B%23) `102.4K 🔥`
1. [中国石油跌停](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E8%B7%8C%E5%81%9C%23) `150.8K 🔥` `-24%`
1. [日本撞人族事件多发 (Incidents of collisions with human beings occur frequently in Japan)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%92%9E%E4%BA%BA%E6%97%8F%E4%BA%8B%E4%BB%B6%E5%A4%9A%E5%8F%91%23) `133.0K 🔥` `-37%`
1. [乌克兰愿帮忙拦截伊朗无人机](https://s.weibo.com/weibo?q=%23%E4%B9%8C%E5%85%8B%E5%85%B0%E6%84%BF%E5%B8%AE%E5%BF%99%E6%8B%A6%E6%88%AA%E4%BC%8A%E6%9C%97%E6%97%A0%E4%BA%BA%E6%9C%BA%23) `125.4K 🔥` `-22%`
1. [十四届全国人大四次会议发布会](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E5%8F%91%E5%B8%83%E4%BC%9A%23) `120.6K 🔥` `-45%`
1. [伊朗遇难学生一个个墓穴让人心碎](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%81%87%E9%9A%BE%E5%AD%A6%E7%94%9F%E4%B8%80%E4%B8%AA%E4%B8%AA%E5%A2%93%E7%A9%B4%E8%AE%A9%E4%BA%BA%E5%BF%83%E7%A2%8E%23) `111.5K 🔥` `-28%`
1. [伊朗库姆遭袭 (Attack on Qom, Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%BA%93%E5%A7%86%E9%81%AD%E8%A2%AD%23) `104.6K 🔥` `-36%`
1. [谁家男主一边擦伤一边擦边 (Whose male protagonist wipes his body while getting bruised?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E5%AE%B6%E7%94%B7%E4%B8%BB%E4%B8%80%E8%BE%B9%E6%93%A6%E4%BC%A4%E4%B8%80%E8%BE%B9%E6%93%A6%E8%BE%B9%23) `100.1K 🔥` `-36%`
1. [全红婵在村里聚完餐骑车离开](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E5%9C%A8%E6%9D%91%E9%87%8C%E8%81%9A%E5%AE%8C%E9%A4%90%E9%AA%91%E8%BD%A6%E7%A6%BB%E5%BC%80%23) `98.6K 🔥` `-39%`
1. [金饰克价一夜跌71元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E4%B8%80%E5%A4%9C%E8%B7%8C71%E5%85%83%23) `94.3K 🔥` `-38%`
1. [岳雨婷缺席balmain看秀](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E7%BC%BA%E5%B8%ADbalmain%E7%9C%8B%E7%A7%80%23) `94.0K 🔥` `-48%`

Updated at 2026-03-04 14:06:29

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
