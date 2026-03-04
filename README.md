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

1. [北京下雪 (It's snowing in Beijing)](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E4%B8%8B%E9%9B%AA%23) `1.1M 🔥` `NEW`
1. [十四届全国人大四次会议发布会](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E5%8F%91%E5%B8%83%E4%BC%9A%23) `825.9K 🔥` `NEW`
1. [90秒看懂议案建议提案如何落地](https://s.weibo.com/weibo?q=%2390%E7%A7%92%E7%9C%8B%E6%87%82%E8%AE%AE%E6%A1%88%E5%BB%BA%E8%AE%AE%E6%8F%90%E6%A1%88%E5%A6%82%E4%BD%95%E8%90%BD%E5%9C%B0%23) `664.2K 🔥` `NEW`
1. [鸿蒙智行技术焕新发布会](https://s.weibo.com/weibo?q=%23%E9%B8%BF%E8%92%99%E6%99%BA%E8%A1%8C%E6%8A%80%E6%9C%AF%E7%84%95%E6%96%B0%E5%8F%91%E5%B8%83%E4%BC%9A%23) `626.7K 🔥` `NEW`
1. [十四届全国人大四次会议议程](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E8%AE%AE%E7%A8%8B%23) `429.5K 🔥` `NEW`
1. [伊朗首都全天遭轮番打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%85%A8%E5%A4%A9%E9%81%AD%E8%BD%AE%E7%95%AA%E6%89%93%E5%87%BB%23) `388.2K 🔥` `NEW`
1. [男生也要预防HPV](https://s.weibo.com/weibo?q=%23%E7%94%B7%E7%94%9F%E4%B9%9F%E8%A6%81%E9%A2%84%E9%98%B2HPV%23) `385.2K 🔥` `NEW`
1. [吃一口饭倒欠200卡路里](https://s.weibo.com/weibo?q=%23%E5%90%83%E4%B8%80%E5%8F%A3%E9%A5%AD%E5%80%92%E6%AC%A0200%E5%8D%A1%E8%B7%AF%E9%87%8C%23) `383.9K 🔥` `NEW`
1. [9图了解政协知识点](https://s.weibo.com/weibo?q=%239%E5%9B%BE%E4%BA%86%E8%A7%A3%E6%94%BF%E5%8D%8F%E7%9F%A5%E8%AF%86%E7%82%B9%23) `373.9K 🔥` `NEW`
1. [直播十四届全国人大四次会议发布会](https://s.weibo.com/weibo?q=%23%E7%9B%B4%E6%92%AD%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E5%8F%91%E5%B8%83%E4%BC%9A%23) `359.9K 🔥` `NEW`
1. [日本撞人族事件多发 (Incidents of collisions with human beings occur frequently in Japan)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%92%9E%E4%BA%BA%E6%97%8F%E4%BA%8B%E4%BB%B6%E5%A4%9A%E5%8F%91%23) `335.0K 🔥` `NEW`
1. [岳雨婷缺席balmain看秀](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E7%BC%BA%E5%B8%ADbalmain%E7%9C%8B%E7%A7%80%23) `332.3K 🔥` `NEW`
1. [锚定奋斗目标汇聚智慧力量](https://s.weibo.com/weibo?q=%23%E9%94%9A%E5%AE%9A%E5%A5%8B%E6%96%97%E7%9B%AE%E6%A0%87%E6%B1%87%E8%81%9A%E6%99%BA%E6%85%A7%E5%8A%9B%E9%87%8F%23) `218.7K 🔥` `NEW`
1. [甜茶首次来华](https://s.weibo.com/weibo?q=%23%E7%94%9C%E8%8C%B6%E9%A6%96%E6%AC%A1%E6%9D%A5%E5%8D%8E%23) `217.0K 🔥` `NEW`
1. [建议严惩性侵未成年人中的熟人作案者](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%A5%E6%83%A9%E6%80%A7%E4%BE%B5%E6%9C%AA%E6%88%90%E5%B9%B4%E4%BA%BA%E4%B8%AD%E7%9A%84%E7%86%9F%E4%BA%BA%E4%BD%9C%E6%A1%88%E8%80%85%23) `214.8K 🔥` `NEW`
1. [金饰克价一夜跌71元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E4%B8%80%E5%A4%9C%E8%B7%8C71%E5%85%83%23) `203.7K 🔥` `NEW`
1. [伊朗称击毁美军第三套萨德系统](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%87%BB%E6%AF%81%E7%BE%8E%E5%86%9B%E7%AC%AC%E4%B8%89%E5%A5%97%E8%90%A8%E5%BE%B7%E7%B3%BB%E7%BB%9F%23) `200.8K 🔥` `NEW`
1. [王楚然花神传到巴黎了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E8%8A%B1%E7%A5%9E%E4%BC%A0%E5%88%B0%E5%B7%B4%E9%BB%8E%E4%BA%86%23) `195.5K 🔥` `NEW`
1. [乌克兰愿帮忙拦截伊朗无人机](https://s.weibo.com/weibo?q=%23%E4%B9%8C%E5%85%8B%E5%85%B0%E6%84%BF%E5%B8%AE%E5%BF%99%E6%8B%A6%E6%88%AA%E4%BC%8A%E6%9C%97%E6%97%A0%E4%BA%BA%E6%9C%BA%23) `186.3K 🔥` `NEW`
1. [赖伟明学范丞丞的手势舞 照抄广告](https://s.weibo.com/weibo?q=%23%E8%B5%96%E4%BC%9F%E6%98%8E%E5%AD%A6%E8%8C%83%E4%B8%9E%E4%B8%9E%E7%9A%84%E6%89%8B%E5%8A%BF%E8%88%9E%20%E7%85%A7%E6%8A%84%E5%B9%BF%E5%91%8A%23) `169.0K 🔥` `NEW`
1. [伊朗库姆遭袭 (Attack on Qom, Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%BA%93%E5%A7%86%E9%81%AD%E8%A2%AD%23) `168.7K 🔥` `NEW`
1. [建议彩礼金额不超过6万元](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%BD%A9%E7%A4%BC%E9%87%91%E9%A2%9D%E4%B8%8D%E8%B6%85%E8%BF%876%E4%B8%87%E5%85%83%23) `163.1K 🔥` `NEW`
1. [朴彩英绿裙看秀](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E5%BD%A9%E8%8B%B1%E7%BB%BF%E8%A3%99%E7%9C%8B%E7%A7%80%23) `159.3K 🔥` `NEW`
1. [建议基础教育学制缩短为532](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%9F%BA%E7%A1%80%E6%95%99%E8%82%B2%E5%AD%A6%E5%88%B6%E7%BC%A9%E7%9F%AD%E4%B8%BA532%23) `157.9K 🔥` `NEW`
1. [粉丝隔着李昀锐聊天](https://s.weibo.com/weibo?q=%23%E7%B2%89%E4%B8%9D%E9%9A%94%E7%9D%80%E6%9D%8E%E6%98%80%E9%94%90%E8%81%8A%E5%A4%A9%23) `153.0K 🔥` `NEW`
1. [薛凯琪发型一半甜妹一半拽姐](https://s.weibo.com/weibo?q=%23%E8%96%9B%E5%87%AF%E7%90%AA%E5%8F%91%E5%9E%8B%E4%B8%80%E5%8D%8A%E7%94%9C%E5%A6%B9%E4%B8%80%E5%8D%8A%E6%8B%BD%E5%A7%90%23) `123.9K 🔥` `NEW`
1. [我使馆提醒防范日本撞人族](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BD%BF%E9%A6%86%E6%8F%90%E9%86%92%E9%98%B2%E8%8C%83%E6%97%A5%E6%9C%AC%E6%92%9E%E4%BA%BA%E6%97%8F%23) `122.4K 🔥` `NEW`
1. [上班的意义具像化了](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%AD%E7%9A%84%E6%84%8F%E4%B9%89%E5%85%B7%E5%83%8F%E5%8C%96%E4%BA%86%23) `121.0K 🔥` `NEW`
1. [王鹤棣镜头快怼到白鹿脸上了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E9%95%9C%E5%A4%B4%E5%BF%AB%E6%80%BC%E5%88%B0%E7%99%BD%E9%B9%BF%E8%84%B8%E4%B8%8A%E4%BA%86%23) `115.9K 🔥` `NEW`
1. [岳雨婷 人在巴黎缺席看秀](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%20%E4%BA%BA%E5%9C%A8%E5%B7%B4%E9%BB%8E%E7%BC%BA%E5%B8%AD%E7%9C%8B%E7%A7%80%23) `115.8K 🔥` `NEW`
1. [王一博粉丝 斗歌 (Wang Yibo fans Dou Ge)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E7%B2%89%E4%B8%9D%20%E6%96%97%E6%AD%8C%23) `109.3K 🔥` `NEW`
1. [这自行车辈分得有多大](https://s.weibo.com/weibo?q=%23%E8%BF%99%E8%87%AA%E8%A1%8C%E8%BD%A6%E8%BE%88%E5%88%86%E5%BE%97%E6%9C%89%E5%A4%9A%E5%A4%A7%23) `108.7K 🔥` `NEW`
1. [郭晓婷说王天辰吻戏像牛耕地](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%93%E5%A9%B7%E8%AF%B4%E7%8E%8B%E5%A4%A9%E8%BE%B0%E5%90%BB%E6%88%8F%E5%83%8F%E7%89%9B%E8%80%95%E5%9C%B0%23) `104.2K 🔥` `NEW`
1. [和平精英](https://s.weibo.com/weibo?q=%23%E5%92%8C%E5%B9%B3%E7%B2%BE%E8%8B%B1%23) `99.4K 🔥` `NEW`
1. [中国石油跌停](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E8%B7%8C%E5%81%9C%23) `336.7K 🔥` `+45%`
1. [伊朗导弹击中美第五舰队总部瞬间](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%87%BB%E4%B8%AD%E7%BE%8E%E7%AC%AC%E4%BA%94%E8%88%B0%E9%98%9F%E6%80%BB%E9%83%A8%E7%9E%AC%E9%97%B4%23) `354.3K 🔥`
1. [全红婵在村里聚完餐骑车离开](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E5%9C%A8%E6%9D%91%E9%87%8C%E8%81%9A%E5%AE%8C%E9%A4%90%E9%AA%91%E8%BD%A6%E7%A6%BB%E5%BC%80%23) `247.5K 🔥`
1. [霍尔木兹海峡十多艘油轮被炮弹击中](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%8D%81%E5%A4%9A%E8%89%98%E6%B2%B9%E8%BD%AE%E8%A2%AB%E7%82%AE%E5%BC%B9%E5%87%BB%E4%B8%AD%23) `207.7K 🔥`
1. [EDG](https://s.weibo.com/weibo?q=%23EDG%23) `109.9K 🔥`
1. [两会 (two sessions)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `392.1K 🔥` `-63%`
1. [中国石油发布公告 (PetroChina releases announcement)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E5%8F%91%E5%B8%83%E5%85%AC%E5%91%8A%23) `377.9K 🔥` `-51%`
1. [霸王茶姬口令](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `232.0K 🔥` `-38%`
1. [法国派出航母 (France dispatches aircraft carrier)](https://s.weibo.com/weibo?q=%23%E6%B3%95%E5%9B%BD%E6%B4%BE%E5%87%BA%E8%88%AA%E6%AF%8D%23) `162.8K 🔥` `-47%`
1. [建议高速年度3000公里免费](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%AB%98%E9%80%9F%E5%B9%B4%E5%BA%A63000%E5%85%AC%E9%87%8C%E5%85%8D%E8%B4%B9%23) `162.1K 🔥` `-55%`
1. [伊朗遇难学生一个个墓穴让人心碎](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%81%87%E9%9A%BE%E5%AD%A6%E7%94%9F%E4%B8%80%E4%B8%AA%E4%B8%AA%E5%A2%93%E7%A9%B4%E8%AE%A9%E4%BA%BA%E5%BF%83%E7%A2%8E%23) `162.0K 🔥` `-30%`
1. [2026全国两会这些看点值得关注](https://s.weibo.com/weibo?q=%232026%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%E8%BF%99%E4%BA%9B%E7%9C%8B%E7%82%B9%E5%80%BC%E5%BE%97%E5%85%B3%E6%B3%A8%23) `160.0K 🔥` `-73%`
1. [黄金白银再直线拉升](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E5%86%8D%E7%9B%B4%E7%BA%BF%E6%8B%89%E5%8D%87%23) `123.9K 🔥` `-47%`
1. [姐姐姐夫终于说开了](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%E7%BB%88%E4%BA%8E%E8%AF%B4%E5%BC%80%E4%BA%86%23) `102.1K 🔥` `-59%`
1. [贫血女子经期一次性拔6颗牙](https://s.weibo.com/weibo?q=%23%E8%B4%AB%E8%A1%80%E5%A5%B3%E5%AD%90%E7%BB%8F%E6%9C%9F%E4%B8%80%E6%AC%A1%E6%80%A7%E6%8B%946%E9%A2%97%E7%89%99%23) `97.3K 🔥` `-47%`
1. [EDG张钊](https://s.weibo.com/weibo?q=%23EDG%E5%BC%A0%E9%92%8A%23) `91.1K 🔥` `-73%`
1. [何与刘些宁同款汤圆](https://s.weibo.com/weibo?q=%23%E4%BD%95%E4%B8%8E%E5%88%98%E4%BA%9B%E5%AE%81%E5%90%8C%E6%AC%BE%E6%B1%A4%E5%9C%86%23) `89.7K 🔥` `-66%`

Updated at 2026-03-04 12:23:12

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
