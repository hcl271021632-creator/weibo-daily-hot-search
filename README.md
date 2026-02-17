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

1. [大年初一不能做哪些事 (What not to do on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E8%83%BD%E5%81%9A%E5%93%AA%E4%BA%9B%E4%BA%8B%23) `873.9K 🔥` `NEW`
1. [春晚首启中国式智能科技新篇章](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E9%A6%96%E5%90%AF%E4%B8%AD%E5%9B%BD%E5%BC%8F%E6%99%BA%E8%83%BD%E7%A7%91%E6%8A%80%E6%96%B0%E7%AF%87%E7%AB%A0%23) `699.5K 🔥` `NEW`
1. [王楚然春晚20秒破2亿](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E6%98%A5%E6%99%9A20%E7%A7%92%E7%A0%B42%E4%BA%BF%23) `667.7K 🔥` `NEW`
1. [时代少年团红包](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E7%BA%A2%E5%8C%85%23) `280.5K 🔥` `NEW`
1. [春晚小品讽刺拉满尺度不小](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%B0%8F%E5%93%81%E8%AE%BD%E5%88%BA%E6%8B%89%E6%BB%A1%E5%B0%BA%E5%BA%A6%E4%B8%8D%E5%B0%8F%23) `270.1K 🔥` `NEW`
1. [猫 死腿快跑啊](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E6%AD%BB%E8%85%BF%E5%BF%AB%E8%B7%91%E5%95%8A%23) `227.6K 🔥` `NEW`
1. [范丞丞贴脸开大沈腾忘词](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E8%B4%B4%E8%84%B8%E5%BC%80%E5%A4%A7%E6%B2%88%E8%85%BE%E5%BF%98%E8%AF%8D%23) `181.6K 🔥` `NEW`
1. [飞驰人生3口碑两极分化](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E5%8F%A3%E7%A2%91%E4%B8%A4%E6%9E%81%E5%88%86%E5%8C%96%23) `159.5K 🔥` `NEW`
1. [李昀锐扛住了春晚镜头1分钟](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E6%89%9B%E4%BD%8F%E4%BA%86%E6%98%A5%E6%99%9A%E9%95%9C%E5%A4%B41%E5%88%86%E9%92%9F%23) `152.9K 🔥` `NEW`
1. [反应慢的人其实是脑子转太快了](https://s.weibo.com/weibo?q=%23%E5%8F%8D%E5%BA%94%E6%85%A2%E7%9A%84%E4%BA%BA%E5%85%B6%E5%AE%9E%E6%98%AF%E8%84%91%E5%AD%90%E8%BD%AC%E5%A4%AA%E5%BF%AB%E4%BA%86%23) `114.3K 🔥` `NEW`
1. [小伙开车1.6万公里从巴黎回山东过年 (A young man drove 16,000 kilometers from Paris back to Shandong for the New Year)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%BC%80%E8%BD%A61.6%E4%B8%87%E5%85%AC%E9%87%8C%E4%BB%8E%E5%B7%B4%E9%BB%8E%E5%9B%9E%E5%B1%B1%E4%B8%9C%E8%BF%87%E5%B9%B4%23) `113.5K 🔥` `NEW`
1. [春晚机器人都在用火山引擎](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%9C%BA%E5%99%A8%E4%BA%BA%E9%83%BD%E5%9C%A8%E7%94%A8%E7%81%AB%E5%B1%B1%E5%BC%95%E6%93%8E%23) `113.0K 🔥` `NEW`
1. [田曦薇特写美我一大跳](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E7%89%B9%E5%86%99%E7%BE%8E%E6%88%91%E4%B8%80%E5%A4%A7%E8%B7%B3%23) `111.2K 🔥` `NEW`
1. [春晚拍出了王楚然的人生镜头](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%8B%8D%E5%87%BA%E4%BA%86%E7%8E%8B%E6%A5%9A%E7%84%B6%E7%9A%84%E4%BA%BA%E7%94%9F%E9%95%9C%E5%A4%B4%23) `83.8K 🔥` `NEW`
1. [在2009年一个普通的周末醒来](https://s.weibo.com/weibo?q=%23%E5%9C%A82009%E5%B9%B4%E4%B8%80%E4%B8%AA%E6%99%AE%E9%80%9A%E7%9A%84%E5%91%A8%E6%9C%AB%E9%86%92%E6%9D%A5%23) `83.7K 🔥` `NEW`
1. [你弟自恋程度恐怕在我之上](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%BC%9F%E8%87%AA%E6%81%8B%E7%A8%8B%E5%BA%A6%E6%81%90%E6%80%95%E5%9C%A8%E6%88%91%E4%B9%8B%E4%B8%8A%23) `83.6K 🔥` `NEW`
1. [星河入梦 黑马 (Starry River Dreaming Dark Horse)](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%20%E9%BB%91%E9%A9%AC%23) `1.2M 🔥` `+567%`
1. [集千问超级免单卡最后一天](https://s.weibo.com/weibo?q=%23%E9%9B%86%E5%8D%83%E9%97%AE%E8%B6%85%E7%BA%A7%E5%85%8D%E5%8D%95%E5%8D%A1%E6%9C%80%E5%90%8E%E4%B8%80%E5%A4%A9%23) `485.6K 🔥` `+93%`
1. [过年当天的你和妈妈](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%BD%93%E5%A4%A9%E7%9A%84%E4%BD%A0%E5%92%8C%E5%A6%88%E5%A6%88%23) `332.9K 🔥` `+87%`
1. [与捷途共赴新年第一缕曙光 (Celebrate the first light of the new year with Jietu)](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E6%8D%B7%E9%80%94%E5%85%B1%E8%B5%B4%E6%96%B0%E5%B9%B4%E7%AC%AC%E4%B8%80%E7%BC%95%E6%9B%99%E5%85%89%23) `674.1K 🔥`
1. [男生回应春节上门喂猫爆赚16万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E7%94%9F%E5%9B%9E%E5%BA%94%E6%98%A5%E8%8A%82%E4%B8%8A%E9%97%A8%E5%96%82%E7%8C%AB%E7%88%86%E8%B5%9A16%E4%B8%87%23) `543.7K 🔥`
1. [央妈不会找王一博赔地板吧](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E5%A6%88%E4%B8%8D%E4%BC%9A%E6%89%BE%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%B5%94%E5%9C%B0%E6%9D%BF%E5%90%A7%23) `496.0K 🔥`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `421.8K 🔥`
1. [飞驰人生3 (Flying Life 3)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%23) `323.7K 🔥`
1. [蔡磊一家三口除夕送祝福](https://s.weibo.com/weibo?q=%23%E8%94%A1%E7%A3%8A%E4%B8%80%E5%AE%B6%E4%B8%89%E5%8F%A3%E9%99%A4%E5%A4%95%E9%80%81%E7%A5%9D%E7%A6%8F%23) `280.2K 🔥`
1. [10万元现金被娃当垃圾扔掉](https://s.weibo.com/weibo?q=%2310%E4%B8%87%E5%85%83%E7%8E%B0%E9%87%91%E8%A2%AB%E5%A8%83%E5%BD%93%E5%9E%83%E5%9C%BE%E6%89%94%E6%8E%89%23) `279.5K 🔥`
1. [iPhone18ProMax或无重大更新](https://s.weibo.com/weibo?q=%23iPhone18ProMax%E6%88%96%E6%97%A0%E9%87%8D%E5%A4%A7%E6%9B%B4%E6%96%B0%23) `228.5K 🔥`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `227.5K 🔥`
1. [迪丽热巴红裙摇曳](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%BA%A2%E8%A3%99%E6%91%87%E6%9B%B3%23) `166.3K 🔥`
1. [星河入梦](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%23) `129.0K 🔥`
1. [开始吃剩菜](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E5%90%83%E5%89%A9%E8%8F%9C%23) `396.2K 🔥` `-21%`
1. [准爸爸拿B超单替宝宝给爷奶拜年 (The father-to-be takes the B-ultrasound scan to wish the grandma New Year’s greetings for the baby)](https://s.weibo.com/weibo?q=%23%E5%87%86%E7%88%B8%E7%88%B8%E6%8B%BFB%E8%B6%85%E5%8D%95%E6%9B%BF%E5%AE%9D%E5%AE%9D%E7%BB%99%E7%88%B7%E5%A5%B6%E6%8B%9C%E5%B9%B4%23) `394.4K 🔥` `-50%`
1. [宇树今年目标出货量1至2万台](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E4%BB%8A%E5%B9%B4%E7%9B%AE%E6%A0%87%E5%87%BA%E8%B4%A7%E9%87%8F1%E8%87%B32%E4%B8%87%E5%8F%B0%23) `394.1K 🔥` `-33%`
1. [王菲连续两年带火小众耳环](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E8%BF%9E%E7%BB%AD%E4%B8%A4%E5%B9%B4%E5%B8%A6%E7%81%AB%E5%B0%8F%E4%BC%97%E8%80%B3%E7%8E%AF%23) `393.9K 🔥` `-32%`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `355.2K 🔥` `-41%`
1. [国防部发文时刻准备着](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%98%B2%E9%83%A8%E5%8F%91%E6%96%87%E6%97%B6%E5%88%BB%E5%87%86%E5%A4%87%E7%9D%80%23) `280.4K 🔥` `-26%`
1. [北京台春晚官宣节目单 (Beijing TV Spring Festival Gala official program announcement)](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%E5%AE%98%E5%AE%A3%E8%8A%82%E7%9B%AE%E5%8D%95%23) `280.4K 🔥` `-54%`
1. [交卷的时候才看见学霸的题](https://s.weibo.com/weibo?q=%23%E4%BA%A4%E5%8D%B7%E7%9A%84%E6%97%B6%E5%80%99%E6%89%8D%E7%9C%8B%E8%A7%81%E5%AD%A6%E9%9C%B8%E7%9A%84%E9%A2%98%23) `280.3K 🔥` `-44%`
1. [小猫和主人都占到了对方的便宜 (Both kitten and owner take advantage of each other)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E5%92%8C%E4%B8%BB%E4%BA%BA%E9%83%BD%E5%8D%A0%E5%88%B0%E4%BA%86%E5%AF%B9%E6%96%B9%E7%9A%84%E4%BE%BF%E5%AE%9C%23) `280.3K 🔥` `-24%`
1. [汪苏泷 我在春晚闯祸 (Wang Sulong I got into trouble at the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%20%E6%88%91%E5%9C%A8%E6%98%A5%E6%99%9A%E9%97%AF%E7%A5%B8%23) `280.2K 🔥` `-44%`
1. [票房 (box office)](https://s.weibo.com/weibo?q=%23%E7%A5%A8%E6%88%BF%23) `236.5K 🔥` `-78%`
1. [年度女演员荣誉提名](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%BA%A6%E5%A5%B3%E6%BC%94%E5%91%98%E8%8D%A3%E8%AA%89%E6%8F%90%E5%90%8D%23) `168.5K 🔥` `-39%`
1. [ELLE主编朋友圈](https://s.weibo.com/weibo?q=%23ELLE%E4%B8%BB%E7%BC%96%E6%9C%8B%E5%8F%8B%E5%9C%88%23) `167.3K 🔥` `-45%`
1. [千问没有免单卡也能天天减免 (Qianwen can get daily deductions even if you don’t have a free card.)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E6%B2%A1%E6%9C%89%E5%85%8D%E5%8D%95%E5%8D%A1%E4%B9%9F%E8%83%BD%E5%A4%A9%E5%A4%A9%E5%87%8F%E5%85%8D%23) `153.8K 🔥` `-42%`
1. [王一博 工作留痕](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%20%E5%B7%A5%E4%BD%9C%E7%95%99%E7%97%95%23) `136.0K 🔥` `-57%`
1. [马宝宝出生](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%AE%9D%E5%AE%9D%E5%87%BA%E7%94%9F%23) `129.5K 🔥` `-65%`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `128.4K 🔥` `-58%`
1. [范丞丞这个笑太漂亮了](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E8%BF%99%E4%B8%AA%E7%AC%91%E5%A4%AA%E6%BC%82%E4%BA%AE%E4%BA%86%23) `113.0K 🔥` `-58%`
1. [钟意](https://s.weibo.com/weibo?q=%23%E9%92%9F%E6%84%8F%23) `111.5K 🔥` `-55%`
1. [檀健次红包](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%E7%BA%A2%E5%8C%85%23) `96.7K 🔥` `-66%`
1. [烟花菜 (Fireworks dish)](https://s.weibo.com/weibo?q=%23%E7%83%9F%E8%8A%B1%E8%8F%9C%23) `86.6K 🔥` `-44%`
1. [美国日本春节想针对台海搞事](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%97%A5%E6%9C%AC%E6%98%A5%E8%8A%82%E6%83%B3%E9%92%88%E5%AF%B9%E5%8F%B0%E6%B5%B7%E6%90%9E%E4%BA%8B%23) `83.7K 🔥` `-77%`

Updated at 2026-02-17 15:40:45

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
