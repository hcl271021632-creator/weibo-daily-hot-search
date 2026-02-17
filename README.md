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

1. [沈腾说错词自责打了半宿掼蛋 (Shen Teng blamed himself for saying the wrong word and beat him half a night)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E8%AF%B4%E9%94%99%E8%AF%8D%E8%87%AA%E8%B4%A3%E6%89%93%E4%BA%86%E5%8D%8A%E5%AE%BF%E6%8E%BC%E8%9B%8B%23) `646.0K 🔥` `NEW`
1. [俄罗斯民众冒雪看春晚](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%E6%B0%91%E4%BC%97%E5%86%92%E9%9B%AA%E7%9C%8B%E6%98%A5%E6%99%9A%23) `438.4K 🔥` `NEW`
1. [家里最没用的把最受宠的吵醒了](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%87%8C%E6%9C%80%E6%B2%A1%E7%94%A8%E7%9A%84%E6%8A%8A%E6%9C%80%E5%8F%97%E5%AE%A0%E7%9A%84%E5%90%B5%E9%86%92%E4%BA%86%23) `340.8K 🔥` `NEW`
1. [迪奥红运开年](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E5%A5%A5%E7%BA%A2%E8%BF%90%E5%BC%80%E5%B9%B4%23) `221.0K 🔥` `NEW`
1. [大年初一机票价格腰斩](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E6%9C%BA%E7%A5%A8%E4%BB%B7%E6%A0%BC%E8%85%B0%E6%96%A9%23) `186.7K 🔥` `NEW`
1. [易烊千玺这个角色和以前很不一样](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E8%BF%99%E4%B8%AA%E8%A7%92%E8%89%B2%E5%92%8C%E4%BB%A5%E5%89%8D%E5%BE%88%E4%B8%8D%E4%B8%80%E6%A0%B7%23) `172.1K 🔥` `NEW`
1. [爸妈来后冰箱都变老了](https://s.weibo.com/weibo?q=%23%E7%88%B8%E5%A6%88%E6%9D%A5%E5%90%8E%E5%86%B0%E7%AE%B1%E9%83%BD%E5%8F%98%E8%80%81%E4%BA%86%23) `163.7K 🔥` `NEW`
1. [王一博攀岩拜年](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%94%80%E5%B2%A9%E6%8B%9C%E5%B9%B4%23) `159.3K 🔥` `NEW`
1. [丁禹兮cos白龙马](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A6%B9%E5%85%AEcos%E7%99%BD%E9%BE%99%E9%A9%AC%23) `151.9K 🔥` `NEW`
1. [家里的猫会开门把大家全救了](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%87%8C%E7%9A%84%E7%8C%AB%E4%BC%9A%E5%BC%80%E9%97%A8%E6%8A%8A%E5%A4%A7%E5%AE%B6%E5%85%A8%E6%95%91%E4%BA%86%23) `151.8K 🔥` `NEW`
1. [全家晒千问战绩 (The whole family shares their achievements in Qianwen)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%AE%B6%E6%99%92%E5%8D%83%E9%97%AE%E6%88%98%E7%BB%A9%23) `146.4K 🔥` `NEW`
1. [春晚这么多演员都穿了宋锦](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%BF%99%E4%B9%88%E5%A4%9A%E6%BC%94%E5%91%98%E9%83%BD%E7%A9%BF%E4%BA%86%E5%AE%8B%E9%94%A6%23) `143.1K 🔥` `NEW`
1. [俄罗斯圣彼得堡点亮中国红](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%E5%9C%A3%E5%BD%BC%E5%BE%97%E5%A0%A1%E7%82%B9%E4%BA%AE%E4%B8%AD%E5%9B%BD%E7%BA%A2%23) `139.0K 🔥` `NEW`
1. [刘宇宁 包宿哥](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%20%E5%8C%85%E5%AE%BF%E5%93%A5%23) `126.3K 🔥` `NEW`
1. [给爸妈换头我是认真的](https://s.weibo.com/weibo?q=%23%E7%BB%99%E7%88%B8%E5%A6%88%E6%8D%A2%E5%A4%B4%E6%88%91%E6%98%AF%E8%AE%A4%E7%9C%9F%E7%9A%84%23) `122.7K 🔥` `NEW`
1. [王玉雯合照堪称小型春晚聚会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%8E%89%E9%9B%AF%E5%90%88%E7%85%A7%E5%A0%AA%E7%A7%B0%E5%B0%8F%E5%9E%8B%E6%98%A5%E6%99%9A%E8%81%9A%E4%BC%9A%23) `122.3K 🔥` `NEW`
1. [镖人的排片](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%9A%84%E6%8E%92%E7%89%87%23) `98.2K 🔥` `NEW`
1. [李昀锐扛住了春晚镜头1分钟](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E6%89%9B%E4%BD%8F%E4%BA%86%E6%98%A5%E6%99%9A%E9%95%9C%E5%A4%B41%E5%88%86%E9%92%9F%23) `338.6K 🔥` `+121%`
1. [猫 死腿快跑啊](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E6%AD%BB%E8%85%BF%E5%BF%AB%E8%B7%91%E5%95%8A%23) `332.4K 🔥` `+46%`
1. [春晚机器人都在用火山引擎](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%9C%BA%E5%99%A8%E4%BA%BA%E9%83%BD%E5%9C%A8%E7%94%A8%E7%81%AB%E5%B1%B1%E5%BC%95%E6%93%8E%23) `170.3K 🔥` `+51%`
1. [星河入梦 黑马 (Starry River Dreaming Dark Horse)](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%20%E9%BB%91%E9%A9%AC%23) `1.1M 🔥`
1. [大年初一不能做哪些事 (What not to do on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E8%83%BD%E5%81%9A%E5%93%AA%E4%BA%9B%E4%BA%8B%23) `847.2K 🔥`
1. [春晚首启中国式智能科技新篇章 (Spring Festival Gala opens a new chapter in Chinese-style smart technology)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E9%A6%96%E5%90%AF%E4%B8%AD%E5%9B%BD%E5%BC%8F%E6%99%BA%E8%83%BD%E7%A7%91%E6%8A%80%E6%96%B0%E7%AF%87%E7%AB%A0%23) `654.1K 🔥`
1. [总台使用Mate80竖屏直播春晚 (The main station uses Mate80 vertical screen to live broadcast the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%80%BB%E5%8F%B0%E4%BD%BF%E7%94%A8Mate80%E7%AB%96%E5%B1%8F%E7%9B%B4%E6%92%AD%E6%98%A5%E6%99%9A%23) `651.4K 🔥`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `341.1K 🔥`
1. [宇树今年目标出货量1至2万台](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E4%BB%8A%E5%B9%B4%E7%9B%AE%E6%A0%87%E5%87%BA%E8%B4%A7%E9%87%8F1%E8%87%B32%E4%B8%87%E5%8F%B0%23) `339.4K 🔥`
1. [王菲连续两年带火小众耳环](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E8%BF%9E%E7%BB%AD%E4%B8%A4%E5%B9%B4%E5%B8%A6%E7%81%AB%E5%B0%8F%E4%BC%97%E8%80%B3%E7%8E%AF%23) `338.8K 🔥`
1. [飞驰人生3 (Flying Life 3)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%23) `332.1K 🔥`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `218.9K 🔥`
1. [春晚小品讽刺拉满尺度不小](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%B0%8F%E5%93%81%E8%AE%BD%E5%88%BA%E6%8B%89%E6%BB%A1%E5%B0%BA%E5%BA%A6%E4%B8%8D%E5%B0%8F%23) `217.6K 🔥`
1. [飞驰人生3口碑两极分化](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E5%8F%A3%E7%A2%91%E4%B8%A4%E6%9E%81%E5%88%86%E5%8C%96%23) `188.5K 🔥`
1. [千问没有免单卡也能天天减免 (Qianwen can get daily deductions even if you don’t have a free card.)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E6%B2%A1%E6%9C%89%E5%85%8D%E5%8D%95%E5%8D%A1%E4%B9%9F%E8%83%BD%E5%A4%A9%E5%A4%A9%E5%87%8F%E5%85%8D%23) `159.3K 🔥`
1. [马宝宝出生](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%AE%9D%E5%AE%9D%E5%87%BA%E7%94%9F%23) `107.7K 🔥`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `106.0K 🔥`
1. [央妈不会找王一博赔地板吧](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E5%A6%88%E4%B8%8D%E4%BC%9A%E6%89%BE%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%B5%94%E5%9C%B0%E6%9D%BF%E5%90%A7%23) `352.7K 🔥` `-29%`
1. [惊蛰无声大年初一好戏开场 (Jingzhe's silent New Year's Day drama begins)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E5%A5%BD%E6%88%8F%E5%BC%80%E5%9C%BA%23) `346.5K 🔥` `-40%`
1. [男生回应春节上门喂猫爆赚16万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E7%94%9F%E5%9B%9E%E5%BA%94%E6%98%A5%E8%8A%82%E4%B8%8A%E9%97%A8%E5%96%82%E7%8C%AB%E7%88%86%E8%B5%9A16%E4%B8%87%23) `340.3K 🔥` `-37%`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `237.3K 🔥` `-33%`
1. [开始吃剩菜](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E5%90%83%E5%89%A9%E8%8F%9C%23) `228.9K 🔥` `-42%`
1. [过年当天的你和妈妈 (You and your mother on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%BD%93%E5%A4%A9%E7%9A%84%E4%BD%A0%E5%92%8C%E5%A6%88%E5%A6%88%23) `224.2K 🔥` `-33%`
1. [国防部发文时刻准备着](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%98%B2%E9%83%A8%E5%8F%91%E6%96%87%E6%97%B6%E5%88%BB%E5%87%86%E5%A4%87%E7%9D%80%23) `222.2K 🔥` `-21%`
1. [时代少年团红包](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E7%BA%A2%E5%8C%85%23) `221.5K 🔥` `-21%`
1. [王楚然春晚20秒破2亿](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E6%98%A5%E6%99%9A20%E7%A7%92%E7%A0%B42%E4%BA%BF%23) `219.6K 🔥` `-67%`
1. [北京台春晚官宣节目单 (Beijing TV Spring Festival Gala official program announcement)](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%E5%AE%98%E5%AE%A3%E8%8A%82%E7%9B%AE%E5%8D%95%23) `217.9K 🔥` `-22%`
1. [10万元现金被娃当垃圾扔掉](https://s.weibo.com/weibo?q=%2310%E4%B8%87%E5%85%83%E7%8E%B0%E9%87%91%E8%A2%AB%E5%A8%83%E5%BD%93%E5%9E%83%E5%9C%BE%E6%89%94%E6%8E%89%23) `192.6K 🔥` `-31%`
1. [iPhone18ProMax或无重大更新](https://s.weibo.com/weibo?q=%23iPhone18ProMax%E6%88%96%E6%97%A0%E9%87%8D%E5%A4%A7%E6%9B%B4%E6%96%B0%23) `178.5K 🔥` `-22%`
1. [准爸爸拿B超单替宝宝给爷奶拜年 (The father-to-be takes the B-ultrasound scan to wish the grandma New Year’s greetings for the baby)](https://s.weibo.com/weibo?q=%23%E5%87%86%E7%88%B8%E7%88%B8%E6%8B%BFB%E8%B6%85%E5%8D%95%E6%9B%BF%E5%AE%9D%E5%AE%9D%E7%BB%99%E7%88%B7%E5%A5%B6%E6%8B%9C%E5%B9%B4%23) `159.3K 🔥` `-60%`
1. [汪苏泷 我在春晚闯祸 (Wang Sulong I got into trouble at the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%20%E6%88%91%E5%9C%A8%E6%98%A5%E6%99%9A%E9%97%AF%E7%A5%B8%23) `159.3K 🔥` `-43%`
1. [范丞丞贴脸开大沈腾忘词](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E8%B4%B4%E8%84%B8%E5%BC%80%E5%A4%A7%E6%B2%88%E8%85%BE%E5%BF%98%E8%AF%8D%23) `138.8K 🔥` `-24%`
1. [蔡磊一家三口除夕送祝福](https://s.weibo.com/weibo?q=%23%E8%94%A1%E7%A3%8A%E4%B8%80%E5%AE%B6%E4%B8%89%E5%8F%A3%E9%99%A4%E5%A4%95%E9%80%81%E7%A5%9D%E7%A6%8F%23) `124.1K 🔥` `-56%`
1. [迪丽热巴红裙摇曳](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%BA%A2%E8%A3%99%E6%91%87%E6%9B%B3%23) `120.8K 🔥` `-27%`
1. [ELLE主编朋友圈](https://s.weibo.com/weibo?q=%23ELLE%E4%B8%BB%E7%BC%96%E6%9C%8B%E5%8F%8B%E5%9C%88%23) `97.9K 🔥` `-42%`

Updated at 2026-02-17 16:28:04

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
