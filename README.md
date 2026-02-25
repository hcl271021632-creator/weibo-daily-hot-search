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

1. [大爷欲购200万元黄金店员报警 (The uncle wanted to buy 2 million yuan in gold. The clerk called the police)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%88%B7%E6%AC%B2%E8%B4%AD200%E4%B8%87%E5%85%83%E9%BB%84%E9%87%91%E5%BA%97%E5%91%98%E6%8A%A5%E8%AD%A6%23) `1.1M 🔥` `NEW`
1. [春节国内出游5.96亿人次](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E5%9B%BD%E5%86%85%E5%87%BA%E6%B8%B85.96%E4%BA%BF%E4%BA%BA%E6%AC%A1%23) `602.3K 🔥` `NEW`
1. [没人比周柯宇更懂礼物](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E4%BA%BA%E6%AF%94%E5%91%A8%E6%9F%AF%E5%AE%87%E6%9B%B4%E6%87%82%E7%A4%BC%E7%89%A9%23) `560.6K 🔥` `NEW`
1. [告白官宣王星越和邓恩熙](https://s.weibo.com/weibo?q=%23%E5%91%8A%E7%99%BD%E5%AE%98%E5%AE%A3%E7%8E%8B%E6%98%9F%E8%B6%8A%E5%92%8C%E9%82%93%E6%81%A9%E7%86%99%23) `556.5K 🔥` `NEW`
1. [四六级查分时间](https://s.weibo.com/weibo?q=%23%E5%9B%9B%E5%85%AD%E7%BA%A7%E6%9F%A5%E5%88%86%E6%97%B6%E9%97%B4%23) `289.6K 🔥` `NEW`
1. [为什么谷爱凌比赛前要放两撮头发](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E8%B0%B7%E7%88%B1%E5%87%8C%E6%AF%94%E8%B5%9B%E5%89%8D%E8%A6%81%E6%94%BE%E4%B8%A4%E6%92%AE%E5%A4%B4%E5%8F%91%23) `278.6K 🔥` `NEW`
1. [教育局回应教师报考其他单位遭开除](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%82%B2%E5%B1%80%E5%9B%9E%E5%BA%94%E6%95%99%E5%B8%88%E6%8A%A5%E8%80%83%E5%85%B6%E4%BB%96%E5%8D%95%E4%BD%8D%E9%81%AD%E5%BC%80%E9%99%A4%23) `252.1K 🔥` `NEW`
1. [雷军鹅鸭杀互动](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E9%B9%85%E9%B8%AD%E6%9D%80%E4%BA%92%E5%8A%A8%23) `233.5K 🔥` `NEW`
1. [默茨抵达北京开始访华](https://s.weibo.com/weibo?q=%23%E9%BB%98%E8%8C%A8%E6%8A%B5%E8%BE%BE%E5%8C%97%E4%BA%AC%E5%BC%80%E5%A7%8B%E8%AE%BF%E5%8D%8E%23) `232.7K 🔥` `NEW`
1. [刘强东已接到5条大型游艇订单](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BC%BA%E4%B8%9C%E5%B7%B2%E6%8E%A5%E5%88%B05%E6%9D%A1%E5%A4%A7%E5%9E%8B%E6%B8%B8%E8%89%87%E8%AE%A2%E5%8D%95%23) `232.0K 🔥` `NEW`
1. [伊能静尝试生酮饮食半年瘦到86斤 (Yi Nengjing tried the ketogenic diet for half a year and lost weight to 86 pounds)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E8%83%BD%E9%9D%99%E5%B0%9D%E8%AF%95%E7%94%9F%E9%85%AE%E9%A5%AE%E9%A3%9F%E5%8D%8A%E5%B9%B4%E7%98%A6%E5%88%B086%E6%96%A4%23) `231.7K 🔥` `NEW`
1. [时代峰峻高会否认时代少年团单飞](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E9%AB%98%E4%BC%9A%E5%90%A6%E8%AE%A4%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E5%8D%95%E9%A3%9E%23) `231.0K 🔥` `NEW`
1. [继父曾发布女童穿短裙高跟鞋视频](https://s.weibo.com/weibo?q=%23%E7%BB%A7%E7%88%B6%E6%9B%BE%E5%8F%91%E5%B8%83%E5%A5%B3%E7%AB%A5%E7%A9%BF%E7%9F%AD%E8%A3%99%E9%AB%98%E8%B7%9F%E9%9E%8B%E8%A7%86%E9%A2%91%23) `230.1K 🔥` `NEW`
1. [生酮饮食是个啥](https://s.weibo.com/weibo?q=%23%E7%94%9F%E9%85%AE%E9%A5%AE%E9%A3%9F%E6%98%AF%E4%B8%AA%E5%95%A5%23) `229.1K 🔥` `NEW`
1. [台北餐厅冷库女尸案](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E5%8C%97%E9%A4%90%E5%8E%85%E5%86%B7%E5%BA%93%E5%A5%B3%E5%B0%B8%E6%A1%88%23) `226.9K 🔥` `NEW`
1. [宁艺卓出发Gucci大秀](https://s.weibo.com/weibo?q=%23%E5%AE%81%E8%89%BA%E5%8D%93%E5%87%BA%E5%8F%91Gucci%E5%A4%A7%E7%A7%80%23) `225.5K 🔥` `NEW`
1. [长剧出现了马年第1匹口碑黑马](https://s.weibo.com/weibo?q=%23%E9%95%BF%E5%89%A7%E5%87%BA%E7%8E%B0%E4%BA%86%E9%A9%AC%E5%B9%B4%E7%AC%AC1%E5%8C%B9%E5%8F%A3%E7%A2%91%E9%BB%91%E9%A9%AC%23) `221.7K 🔥` `NEW`
1. [女子不会做饭用泡面招待亲戚](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B8%8D%E4%BC%9A%E5%81%9A%E9%A5%AD%E7%94%A8%E6%B3%A1%E9%9D%A2%E6%8B%9B%E5%BE%85%E4%BA%B2%E6%88%9A%23) `211.9K 🔥` `NEW`
1. [王楚然丞磊伟大的杀青梗](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E4%B8%9E%E7%A3%8A%E4%BC%9F%E5%A4%A7%E7%9A%84%E6%9D%80%E9%9D%92%E6%A2%97%23) `190.8K 🔥` `NEW`
1. [殴打少女夫妻事前曾错打3名路人](https://s.weibo.com/weibo?q=%23%E6%AE%B4%E6%89%93%E5%B0%91%E5%A5%B3%E5%A4%AB%E5%A6%BB%E4%BA%8B%E5%89%8D%E6%9B%BE%E9%94%99%E6%89%933%E5%90%8D%E8%B7%AF%E4%BA%BA%23) `184.2K 🔥` `NEW`
1. [刘强东一艘游艇卖6000万欧元 (Liu Qiangdong sold a yacht for 60 million euros)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BC%BA%E4%B8%9C%E4%B8%80%E8%89%98%E6%B8%B8%E8%89%87%E5%8D%966000%E4%B8%87%E6%AC%A7%E5%85%83%23) `180.6K 🔥` `NEW`
1. [挂提亲横幅自驾932公里男子发声](https://s.weibo.com/weibo?q=%23%E6%8C%82%E6%8F%90%E4%BA%B2%E6%A8%AA%E5%B9%85%E8%87%AA%E9%A9%BE932%E5%85%AC%E9%87%8C%E7%94%B7%E5%AD%90%E5%8F%91%E5%A3%B0%23) `180.0K 🔥` `NEW`
1. [游客在三亚沙滩写不想上班](https://s.weibo.com/weibo?q=%23%E6%B8%B8%E5%AE%A2%E5%9C%A8%E4%B8%89%E4%BA%9A%E6%B2%99%E6%BB%A9%E5%86%99%E4%B8%8D%E6%83%B3%E4%B8%8A%E7%8F%AD%23) `179.5K 🔥` `NEW`
1. [王楚钦回应鹰眼挑战失败](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%9B%9E%E5%BA%94%E9%B9%B0%E7%9C%BC%E6%8C%91%E6%88%98%E5%A4%B1%E8%B4%A5%23) `165.5K 🔥` `NEW`
1. [金店店员称结婚不要强追五金](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%BA%97%E5%BA%97%E5%91%98%E7%A7%B0%E7%BB%93%E5%A9%9A%E4%B8%8D%E8%A6%81%E5%BC%BA%E8%BF%BD%E4%BA%94%E9%87%91%23) `152.6K 🔥` `NEW`
1. [交警回应女子随手拍举报20多辆车](https://s.weibo.com/weibo?q=%23%E4%BA%A4%E8%AD%A6%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%AD%90%E9%9A%8F%E6%89%8B%E6%8B%8D%E4%B8%BE%E6%8A%A520%E5%A4%9A%E8%BE%86%E8%BD%A6%23) `145.8K 🔥` `NEW`
1. [爱你开播一周年](https://s.weibo.com/weibo?q=%23%E7%88%B1%E4%BD%A0%E5%BC%80%E6%92%AD%E4%B8%80%E5%91%A8%E5%B9%B4%23) `139.8K 🔥` `NEW`
1. [海南涌现大量1折机票](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8D%97%E6%B6%8C%E7%8E%B0%E5%A4%A7%E9%87%8F1%E6%8A%98%E6%9C%BA%E7%A5%A8%23) `132.2K 🔥` `NEW`
1. [杨洋多部待播剧](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%A4%9A%E9%83%A8%E5%BE%85%E6%92%AD%E5%89%A7%23) `130.1K 🔥` `NEW`
1. [夫妻过年后回家发现家门大敞](https://s.weibo.com/weibo?q=%23%E5%A4%AB%E5%A6%BB%E8%BF%87%E5%B9%B4%E5%90%8E%E5%9B%9E%E5%AE%B6%E5%8F%91%E7%8E%B0%E5%AE%B6%E9%97%A8%E5%A4%A7%E6%95%9E%23) `128.9K 🔥` `NEW`
1. [春节自驾35人大家庭计划夏天游新疆 (A self-driving family of 35 people plans to travel to Xinjiang during the Spring Festival in the summer)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E8%87%AA%E9%A9%BE35%E4%BA%BA%E5%A4%A7%E5%AE%B6%E5%BA%AD%E8%AE%A1%E5%88%92%E5%A4%8F%E5%A4%A9%E6%B8%B8%E6%96%B0%E7%96%86%23) `126.0K 🔥` `NEW`
1. [继父亲吻女童时母亲就在现场](https://s.weibo.com/weibo?q=%23%E7%BB%A7%E7%88%B6%E4%BA%B2%E5%90%BB%E5%A5%B3%E7%AB%A5%E6%97%B6%E6%AF%8D%E4%BA%B2%E5%B0%B1%E5%9C%A8%E7%8E%B0%E5%9C%BA%23) `126.0K 🔥` `NEW`
1. [TVB演员游飚去世](https://s.weibo.com/weibo?q=%23TVB%E6%BC%94%E5%91%98%E6%B8%B8%E9%A3%9A%E5%8E%BB%E4%B8%96%23) `124.9K 🔥` `NEW`
1. [谷爱凌的金色蝴蝶结是即兴系的](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E7%9A%84%E9%87%91%E8%89%B2%E8%9D%B4%E8%9D%B6%E7%BB%93%E6%98%AF%E5%8D%B3%E5%85%B4%E7%B3%BB%E7%9A%84%23) `115.4K 🔥` `NEW`
1. [新版傲慢与偏见预告](https://s.weibo.com/weibo?q=%23%E6%96%B0%E7%89%88%E5%82%B2%E6%85%A2%E4%B8%8E%E5%81%8F%E8%A7%81%E9%A2%84%E5%91%8A%23) `112.5K 🔥` `NEW`
1. [我们的少年时代2开机日](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%E5%BC%80%E6%9C%BA%E6%97%A5%23) `111.1K 🔥` `NEW`
1. [樊振东孙颖莎釜山团体世乒赛MVP回顾](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%AD%99%E9%A2%96%E8%8E%8E%E9%87%9C%E5%B1%B1%E5%9B%A2%E4%BD%93%E4%B8%96%E4%B9%92%E8%B5%9BMVP%E5%9B%9E%E9%A1%BE%23) `103.8K 🔥` `NEW`
1. [曝杨洋手里不缺剧本](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%9D%A8%E6%B4%8B%E6%89%8B%E9%87%8C%E4%B8%8D%E7%BC%BA%E5%89%A7%E6%9C%AC%23) `103.4K 🔥` `NEW`
1. [我们的少年时代2](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%23) `99.2K 🔥` `NEW`
1. [吴昕自曝录制快本三四个月还是想走 (Wu Xin reveals that she still wants to leave after three or four months of recording the album)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%87%AA%E6%9B%9D%E5%BD%95%E5%88%B6%E5%BF%AB%E6%9C%AC%E4%B8%89%E5%9B%9B%E4%B8%AA%E6%9C%88%E8%BF%98%E6%98%AF%E6%83%B3%E8%B5%B0%23) `228.1K 🔥` `+22%`
1. [iPhone18Pro深红色](https://s.weibo.com/weibo?q=%23iPhone18Pro%E6%B7%B1%E7%BA%A2%E8%89%B2%23) `225.7K 🔥` `+96%`
1. [碧血蝉 (green blood cicada)](https://s.weibo.com/weibo?q=%23%E7%A2%A7%E8%A1%80%E8%9D%89%23) `151.4K 🔥` `+56%`
1. [宝马7系降价约27万 (BMW 7 Series price cut by about 270,000)](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E9%A9%AC7%E7%B3%BB%E9%99%8D%E4%BB%B7%E7%BA%A627%E4%B8%87%23) `775.2K 🔥`
1. [平顶山再通报打人事件](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E9%A1%B6%E5%B1%B1%E5%86%8D%E9%80%9A%E6%8A%A5%E6%89%93%E4%BA%BA%E4%BA%8B%E4%BB%B6%23) `274.1K 🔥` `-76%`
1. [女子在加油站人肉插队躺后车引擎盖](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%9C%A8%E5%8A%A0%E6%B2%B9%E7%AB%99%E4%BA%BA%E8%82%89%E6%8F%92%E9%98%9F%E8%BA%BA%E5%90%8E%E8%BD%A6%E5%BC%95%E6%93%8E%E7%9B%96%23) `208.4K 🔥` `-55%`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `171.4K 🔥` `-54%`
1. [女子返程堵车偶遇10年未见初恋](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%BF%94%E7%A8%8B%E5%A0%B5%E8%BD%A6%E5%81%B6%E9%81%8710%E5%B9%B4%E6%9C%AA%E8%A7%81%E5%88%9D%E6%81%8B%23) `146.1K 🔥` `-70%`
1. [米兰偶遇杨幂逛店](https://s.weibo.com/weibo?q=%23%E7%B1%B3%E5%85%B0%E5%81%B6%E9%81%87%E6%9D%A8%E5%B9%82%E9%80%9B%E5%BA%97%23) `135.4K 🔥` `-22%`
1. [王楚钦鹰眼挑战失败 (Wang Chuqin’s Eagle Eye challenge failed)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E9%B9%B0%E7%9C%BC%E6%8C%91%E6%88%98%E5%A4%B1%E8%B4%A5%23) `124.9K 🔥` `-41%`
1. [月经一定程度上能反映气血状况](https://s.weibo.com/weibo?q=%23%E6%9C%88%E7%BB%8F%E4%B8%80%E5%AE%9A%E7%A8%8B%E5%BA%A6%E4%B8%8A%E8%83%BD%E5%8F%8D%E6%98%A0%E6%B0%94%E8%A1%80%E7%8A%B6%E5%86%B5%23) `121.7K 🔥` `-32%`

Updated at 2026-02-25 11:46:16

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
