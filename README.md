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

1. [邓凯新剧又是强制爱 (Deng Kai’s new drama is about forced love again)](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E6%96%B0%E5%89%A7%E5%8F%88%E6%98%AF%E5%BC%BA%E5%88%B6%E7%88%B1%23) `231.4K 🔥` `NEW`
1. [张凌赫田曦薇 我爱上了弟弟的妻子](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%20%E6%88%91%E7%88%B1%E4%B8%8A%E4%BA%86%E5%BC%9F%E5%BC%9F%E7%9A%84%E5%A6%BB%E5%AD%90%23) `225.4K 🔥` `NEW`
1. [宫脇咲良取关张元英](https://s.weibo.com/weibo?q=%23%E5%AE%AB%E8%84%87%E5%92%B2%E8%89%AF%E5%8F%96%E5%85%B3%E5%BC%A0%E5%85%83%E8%8B%B1%23) `165.1K 🔥` `NEW`
1. [美股](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%82%A1%23) `163.9K 🔥` `NEW`
1. [陈锦鸿把自闭症儿子养成青年钢琴家](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%94%A6%E9%B8%BF%E6%8A%8A%E8%87%AA%E9%97%AD%E7%97%87%E5%84%BF%E5%AD%90%E5%85%BB%E6%88%90%E9%9D%92%E5%B9%B4%E9%92%A2%E7%90%B4%E5%AE%B6%23) `161.3K 🔥` `NEW`
1. [齐俞 齐煜](https://s.weibo.com/weibo?q=%23%E9%BD%90%E4%BF%9E%20%E9%BD%90%E7%85%9C%23) `153.1K 🔥` `NEW`
1. [周杰伦新专辑太阳之子](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%E5%A4%AA%E9%98%B3%E4%B9%8B%E5%AD%90%23) `139.4K 🔥` `NEW`
1. [美伊就中东敌对行动解决方案进行对话](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BC%8A%E5%B0%B1%E4%B8%AD%E4%B8%9C%E6%95%8C%E5%AF%B9%E8%A1%8C%E5%8A%A8%E8%A7%A3%E5%86%B3%E6%96%B9%E6%A1%88%E8%BF%9B%E8%A1%8C%E5%AF%B9%E8%AF%9D%23) `138.7K 🔥` `NEW`
1. [朝鲜称与日本没什么可谈的](https://s.weibo.com/weibo?q=%23%E6%9C%9D%E9%B2%9C%E7%A7%B0%E4%B8%8E%E6%97%A5%E6%9C%AC%E6%B2%A1%E4%BB%80%E4%B9%88%E5%8F%AF%E8%B0%88%E7%9A%84%23) `113.3K 🔥` `NEW`
1. [夏晓兰 春梦](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E6%99%93%E5%85%B0%20%E6%98%A5%E6%A2%A6%23) `106.5K 🔥` `NEW`
1. [萧蔷曾多次婉拒浪姐邀约 (Xiao Qiang declined Sister Lang’s invitation many times)](https://s.weibo.com/weibo?q=%23%E8%90%A7%E8%94%B7%E6%9B%BE%E5%A4%9A%E6%AC%A1%E5%A9%89%E6%8B%92%E6%B5%AA%E5%A7%90%E9%82%80%E7%BA%A6%23) `92.4K 🔥` `NEW`
1. [逐玉这下是真捅破窗户纸了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%BF%99%E4%B8%8B%E6%98%AF%E7%9C%9F%E6%8D%85%E7%A0%B4%E7%AA%97%E6%88%B7%E7%BA%B8%E4%BA%86%23) `87.9K 🔥` `NEW`
1. [AI写歌走红程序员9个月赚20万](https://s.weibo.com/weibo?q=%23AI%E5%86%99%E6%AD%8C%E8%B5%B0%E7%BA%A2%E7%A8%8B%E5%BA%8F%E5%91%989%E4%B8%AA%E6%9C%88%E8%B5%9A20%E4%B8%87%23) `84.5K 🔥` `NEW`
1. [金与正说不想看到日本首相来平壤](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%B8%8E%E6%AD%A3%E8%AF%B4%E4%B8%8D%E6%83%B3%E7%9C%8B%E5%88%B0%E6%97%A5%E6%9C%AC%E9%A6%96%E7%9B%B8%E6%9D%A5%E5%B9%B3%E5%A3%A4%23) `83.8K 🔥` `NEW`
1. [14位美企高管来访商务部排排坐](https://s.weibo.com/weibo?q=%2314%E4%BD%8D%E7%BE%8E%E4%BC%81%E9%AB%98%E7%AE%A1%E6%9D%A5%E8%AE%BF%E5%95%86%E5%8A%A1%E9%83%A8%E6%8E%92%E6%8E%92%E5%9D%90%23) `83.6K 🔥` `NEW`
1. [美军福特号航母撤至希腊](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E7%A6%8F%E7%89%B9%E5%8F%B7%E8%88%AA%E6%AF%8D%E6%92%A4%E8%87%B3%E5%B8%8C%E8%85%8A%23) `83.5K 🔥` `NEW`
1. [女子用剪刀八达岭长城上刻字](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%94%A8%E5%89%AA%E5%88%80%E5%85%AB%E8%BE%BE%E5%B2%AD%E9%95%BF%E5%9F%8E%E4%B8%8A%E5%88%BB%E5%AD%97%23) `79.1K 🔥` `NEW`
1. [乱世黄金遭到抛售](https://s.weibo.com/weibo?q=%23%E4%B9%B1%E4%B8%96%E9%BB%84%E9%87%91%E9%81%AD%E5%88%B0%E6%8A%9B%E5%94%AE%23) `76.4K 🔥` `NEW`
1. [黄金跌近400美元](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E8%B7%8C%E8%BF%91400%E7%BE%8E%E5%85%83%23) `73.8K 🔥` `NEW`
1. [辽宁男篮vs同曦男篮](https://s.weibo.com/weibo?q=%23%E8%BE%BD%E5%AE%81%E7%94%B7%E7%AF%AEvs%E5%90%8C%E6%9B%A6%E7%94%B7%E7%AF%AE%23) `70.8K 🔥` `NEW`
1. [对国内成品油价格采取临时调控 (Adopt temporary controls on domestic refined oil prices)](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E5%9B%BD%E5%86%85%E6%88%90%E5%93%81%E6%B2%B9%E4%BB%B7%E6%A0%BC%E9%87%87%E5%8F%96%E4%B8%B4%E6%97%B6%E8%B0%83%E6%8E%A7%23) `1.1M 🔥` `+38%`
1. [开始推理吧4 (Let’s start reasoning 4)](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E6%8E%A8%E7%90%86%E5%90%A74%23) `767.1K 🔥` `+387%`
1. [伊朗称特朗普推迟袭击表态为心理战](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E7%89%B9%E6%9C%97%E6%99%AE%E6%8E%A8%E8%BF%9F%E8%A2%AD%E5%87%BB%E8%A1%A8%E6%80%81%E4%B8%BA%E5%BF%83%E7%90%86%E6%88%98%23) `227.4K 🔥` `+71%`
1. [以前看小说vs现在看小说](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%89%8D%E7%9C%8B%E5%B0%8F%E8%AF%B4vs%E7%8E%B0%E5%9C%A8%E7%9C%8B%E5%B0%8F%E8%AF%B4%23) `223.2K 🔥` `+68%`
1. [大学是离异性最远的阶段](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E6%98%AF%E7%A6%BB%E5%BC%82%E6%80%A7%E6%9C%80%E8%BF%9C%E7%9A%84%E9%98%B6%E6%AE%B5%23) `166.3K 🔥` `+153%`
1. [20岁女生长期开灯睡觉胖到200斤](https://s.weibo.com/weibo?q=%2320%E5%B2%81%E5%A5%B3%E7%94%9F%E9%95%BF%E6%9C%9F%E5%BC%80%E7%81%AF%E7%9D%A1%E8%A7%89%E8%83%96%E5%88%B0200%E6%96%A4%23) `153.9K 🔥` `+69%`
1. [梦想的接力最燃 (The relay of dreams is the most burning)](https://s.weibo.com/weibo?q=%23%E6%A2%A6%E6%83%B3%E7%9A%84%E6%8E%A5%E5%8A%9B%E6%9C%80%E7%87%83%23) `626.1K 🔥`
1. [国乒公布伦敦世乒赛初步参赛名单](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%B9%92%E5%85%AC%E5%B8%83%E4%BC%A6%E6%95%A6%E4%B8%96%E4%B9%92%E8%B5%9B%E5%88%9D%E6%AD%A5%E5%8F%82%E8%B5%9B%E5%90%8D%E5%8D%95%23) `232.2K 🔥`
1. [长期不换社交头像的人 (People who don’t change their social avatars for a long time)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E4%B8%8D%E6%8D%A2%E7%A4%BE%E4%BA%A4%E5%A4%B4%E5%83%8F%E7%9A%84%E4%BA%BA%23) `168.2K 🔥`
1. [阚清子晒近照](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E6%99%92%E8%BF%91%E7%85%A7%23) `168.0K 🔥`
1. [男大学生患桃花癫一周挥霍5万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%A4%A7%E5%AD%A6%E7%94%9F%E6%82%A3%E6%A1%83%E8%8A%B1%E7%99%AB%E4%B8%80%E5%91%A8%E6%8C%A5%E9%9C%8D5%E4%B8%87%23) `162.6K 🔥`
1. [上过跑男的团体都解散了](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E8%BF%87%E8%B7%91%E7%94%B7%E7%9A%84%E5%9B%A2%E4%BD%93%E9%83%BD%E8%A7%A3%E6%95%A3%E4%BA%86%23) `159.4K 🔥`
1. [逐玉第二](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%AC%AC%E4%BA%8C%23) `158.1K 🔥`
1. [教授地铁审博士论文视频海外爆火 (Video of professor reviewing doctoral thesis on subway goes viral abroad)](https://s.weibo.com/weibo?q=%23%E6%95%99%E6%8E%88%E5%9C%B0%E9%93%81%E5%AE%A1%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87%E8%A7%86%E9%A2%91%E6%B5%B7%E5%A4%96%E7%88%86%E7%81%AB%23) `157.6K 🔥`
1. [特朗普称美伊已对话 (Trump says U.S.-Iran dialogue has begun)](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E7%BE%8E%E4%BC%8A%E5%B7%B2%E5%AF%B9%E8%AF%9D%23) `156.2K 🔥`
1. [金价创下1983年3月以来最大单周跌幅](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%88%9B%E4%B8%8B1983%E5%B9%B43%E6%9C%88%E4%BB%A5%E6%9D%A5%E6%9C%80%E5%A4%A7%E5%8D%95%E5%91%A8%E8%B7%8C%E5%B9%85%23) `154.5K 🔥`
1. [为什么我们要多吃水果](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%91%E4%BB%AC%E8%A6%81%E5%A4%9A%E5%90%83%E6%B0%B4%E6%9E%9C%23) `139.6K 🔥`
1. [开始推理吧](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E6%8E%A8%E7%90%86%E5%90%A7%23) `120.2K 🔥`
1. [伊朗地下设施堆放一排排导弹 (Rows of missiles stacked in Iran's underground facilities)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%9C%B0%E4%B8%8B%E8%AE%BE%E6%96%BD%E5%A0%86%E6%94%BE%E4%B8%80%E6%8E%92%E6%8E%92%E5%AF%BC%E5%BC%B9%23) `114.3K 🔥`
1. [黄金大跌金店老板慌了](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E5%A4%A7%E8%B7%8C%E9%87%91%E5%BA%97%E8%80%81%E6%9D%BF%E6%85%8C%E4%BA%86%23) `111.3K 🔥`
1. [长期喝桶装水的人天塌了 (People who drink bottled water for a long time are in trouble)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E5%96%9D%E6%A1%B6%E8%A3%85%E6%B0%B4%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `95.0K 🔥`
1. [我洗头后三天的头发蓬松程度](https://s.weibo.com/weibo?q=%23%E6%88%91%E6%B4%97%E5%A4%B4%E5%90%8E%E4%B8%89%E5%A4%A9%E7%9A%84%E5%A4%B4%E5%8F%91%E8%93%AC%E6%9D%BE%E7%A8%8B%E5%BA%A6%23) `87.2K 🔥`
1. [TF五代 拿电话手表聊国际新闻](https://s.weibo.com/weibo?q=%23TF%E4%BA%94%E4%BB%A3%20%E6%8B%BF%E7%94%B5%E8%AF%9D%E6%89%8B%E8%A1%A8%E8%81%8A%E5%9B%BD%E9%99%85%E6%96%B0%E9%97%BB%23) `76.6K 🔥`
1. [一家四口感染HIV妻子小儿子去世](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B6%E5%9B%9B%E5%8F%A3%E6%84%9F%E6%9F%93HIV%E5%A6%BB%E5%AD%90%E5%B0%8F%E5%84%BF%E5%AD%90%E5%8E%BB%E4%B8%96%23) `229.4K 🔥` `-44%`
1. [伊朗否认与美国沟通](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%A6%E8%AE%A4%E4%B8%8E%E7%BE%8E%E5%9B%BD%E6%B2%9F%E9%80%9A%23) `160.9K 🔥` `-25%`
1. [张凌赫出发录开始推理吧](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%87%BA%E5%8F%91%E5%BD%95%E5%BC%80%E5%A7%8B%E6%8E%A8%E7%90%86%E5%90%A7%23) `151.6K 🔥` `-24%`
1. [李卿 内娱金宣虎 (Li Qing Internal Entertainment Kim Sun Ho)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%8D%BF%20%E5%86%85%E5%A8%B1%E9%87%91%E5%AE%A3%E8%99%8E%23) `85.9K 🔥` `-35%`
1. [关晓彤 至今不知道腿长的坏处 (Guan Xiaotong still doesn’t know the disadvantages of long legs)](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%20%E8%87%B3%E4%BB%8A%E4%B8%8D%E7%9F%A5%E9%81%93%E8%85%BF%E9%95%BF%E7%9A%84%E5%9D%8F%E5%A4%84%23) `78.8K 🔥` `-37%`
1. [美股三大股指期货突然拉升](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%82%A1%E4%B8%89%E5%A4%A7%E8%82%A1%E6%8C%87%E6%9C%9F%E8%B4%A7%E7%AA%81%E7%84%B6%E6%8B%89%E5%8D%87%23) `73.3K 🔥` `-48%`
1. [毛晓彤28岁时因为年龄焦虑大哭](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%99%93%E5%BD%A428%E5%B2%81%E6%97%B6%E5%9B%A0%E4%B8%BA%E5%B9%B4%E9%BE%84%E7%84%A6%E8%99%91%E5%A4%A7%E5%93%AD%23) `73.2K 🔥` `-27%`

Updated at 2026-03-23 22:35:44

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
