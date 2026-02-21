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

1. [不让江山女主 (The heroine who won’t let the country go)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%A5%B3%E4%B8%BB%23) `775.3K 🔥` `NEW`
1. [谷爱凌出战冲金](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%87%BA%E6%88%98%E5%86%B2%E9%87%91%23) `211.3K 🔥` `NEW`
1. [黄晓明回应在澳门输掉十几亿](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E5%9B%9E%E5%BA%94%E5%9C%A8%E6%BE%B3%E9%97%A8%E8%BE%93%E6%8E%89%E5%8D%81%E5%87%A0%E4%BA%BF%23) `159.3K 🔥` `NEW`
1. [韩维辰硬刚wk1](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E7%BB%B4%E8%BE%B0%E7%A1%AC%E5%88%9Awk1%23) `151.0K 🔥` `NEW`
1. [院士回忆靠算盘计算尺击落美战机](https://s.weibo.com/weibo?q=%23%E9%99%A2%E5%A3%AB%E5%9B%9E%E5%BF%86%E9%9D%A0%E7%AE%97%E7%9B%98%E8%AE%A1%E7%AE%97%E5%B0%BA%E5%87%BB%E8%90%BD%E7%BE%8E%E6%88%98%E6%9C%BA%23) `139.8K 🔥` `NEW`
1. [金饰价涨到1598元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E6%B6%A8%E5%88%B01598%E5%85%83%23) `138.0K 🔥` `NEW`
1. [这2种饮料混着喝或永久损伤大脑](https://s.weibo.com/weibo?q=%23%E8%BF%992%E7%A7%8D%E9%A5%AE%E6%96%99%E6%B7%B7%E7%9D%80%E5%96%9D%E6%88%96%E6%B0%B8%E4%B9%85%E6%8D%9F%E4%BC%A4%E5%A4%A7%E8%84%91%23) `136.2K 🔥` `NEW`
1. [贝加尔湖事故有很多中国人参与救援](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E4%BA%8B%E6%95%85%E6%9C%89%E5%BE%88%E5%A4%9A%E4%B8%AD%E5%9B%BD%E4%BA%BA%E5%8F%82%E4%B8%8E%E6%95%91%E6%8F%B4%23) `133.5K 🔥` `NEW`
1. [徐梦桃爱拍照全米兰都知道了](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E7%88%B1%E6%8B%8D%E7%85%A7%E5%85%A8%E7%B1%B3%E5%85%B0%E9%83%BD%E7%9F%A5%E9%81%93%E4%BA%86%23) `130.7K 🔥` `NEW`
1. [沈腾有望成首位主演票房破400亿演员](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E6%9C%89%E6%9C%9B%E6%88%90%E9%A6%96%E4%BD%8D%E4%B8%BB%E6%BC%94%E7%A5%A8%E6%88%BF%E7%A0%B4400%E4%BA%BF%E6%BC%94%E5%91%98%23) `125.2K 🔥` `NEW`
1. [终于有人懂牛奶包装设计师了 (Finally someone understands milk packaging designers)](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%87%82%E7%89%9B%E5%A5%B6%E5%8C%85%E8%A3%85%E8%AE%BE%E8%AE%A1%E5%B8%88%E4%BA%86%23) `106.9K 🔥` `NEW`
1. [林孝埈采访](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E9%87%87%E8%AE%BF%23) `101.7K 🔥` `NEW`
1. [王牌对王牌](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%89%8C%E5%AF%B9%E7%8E%8B%E7%89%8C%23) `98.4K 🔥` `NEW`
1. [过年减肥规则怪谈](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%87%8F%E8%82%A5%E8%A7%84%E5%88%99%E6%80%AA%E8%B0%88%23) `94.2K 🔥` `NEW`
1. [建议纳入北影教材](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%BA%B3%E5%85%A5%E5%8C%97%E5%BD%B1%E6%95%99%E6%9D%90%23) `91.6K 🔥` `NEW`
1. [花市一夜变整洁见证广东速度](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%B8%82%E4%B8%80%E5%A4%9C%E5%8F%98%E6%95%B4%E6%B4%81%E8%A7%81%E8%AF%81%E5%B9%BF%E4%B8%9C%E9%80%9F%E5%BA%A6%23) `89.8K 🔥` `NEW`
1. [83岁外婆用竹扫帚给孙女洗车](https://s.weibo.com/weibo?q=%2383%E5%B2%81%E5%A4%96%E5%A9%86%E7%94%A8%E7%AB%B9%E6%89%AB%E5%B8%9A%E7%BB%99%E5%AD%99%E5%A5%B3%E6%B4%97%E8%BD%A6%23) `89.4K 🔥` `NEW`
1. [迎财神图片](https://s.weibo.com/weibo?q=%23%E8%BF%8E%E8%B4%A2%E7%A5%9E%E5%9B%BE%E7%89%87%23) `89.2K 🔥` `NEW`
1. [苹果史上首款折叠屏手机](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E5%8F%B2%E4%B8%8A%E9%A6%96%E6%AC%BE%E6%8A%98%E5%8F%A0%E5%B1%8F%E6%89%8B%E6%9C%BA%23) `87.6K 🔥` `NEW`
1. [打开朋友圈以为到了天庭](https://s.weibo.com/weibo?q=%23%E6%89%93%E5%BC%80%E6%9C%8B%E5%8F%8B%E5%9C%88%E4%BB%A5%E4%B8%BA%E5%88%B0%E4%BA%86%E5%A4%A9%E5%BA%AD%23) `82.5K 🔥` `NEW`
1. [现在的碰碰车都发展成这样了 (Nowadays bumper cars have developed like this)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E7%9A%84%E7%A2%B0%E7%A2%B0%E8%BD%A6%E9%83%BD%E5%8F%91%E5%B1%95%E6%88%90%E8%BF%99%E6%A0%B7%E4%BA%86%23) `81.2K 🔥` `NEW`
1. [上班上出了结婚的感觉](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%AD%E4%B8%8A%E5%87%BA%E4%BA%86%E7%BB%93%E5%A9%9A%E7%9A%84%E6%84%9F%E8%A7%89%23) `72.7K 🔥` `NEW`
1. [慈母多败咪 (A loving mother often fails)](https://s.weibo.com/weibo?q=%23%E6%85%88%E6%AF%8D%E5%A4%9A%E8%B4%A5%E5%92%AA%23) `224.1K 🔥` `+167%`
1. [古言三巨头](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E8%A8%80%E4%B8%89%E5%B7%A8%E5%A4%B4%23) `163.0K 🔥` `+63%`
1. [特朗普访华时间](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%AE%BF%E5%8D%8E%E6%97%B6%E9%97%B4%23) `161.0K 🔥` `+28%`
1. [姚晨丢掉妈妈过期药品被骂了3天](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E6%99%A8%E4%B8%A2%E6%8E%89%E5%A6%88%E5%A6%88%E8%BF%87%E6%9C%9F%E8%8D%AF%E5%93%81%E8%A2%AB%E9%AA%82%E4%BA%863%E5%A4%A9%23) `156.9K 🔥` `+26%`
1. [泡泡玛特创始人送小酒窝盲盒](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E6%B3%A1%E7%8E%9B%E7%89%B9%E5%88%9B%E5%A7%8B%E4%BA%BA%E9%80%81%E5%B0%8F%E9%85%92%E7%AA%9D%E7%9B%B2%E7%9B%92%23) `153.2K 🔥` `+23%`
1. [关晓彤我长大了不能被骗了](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E6%88%91%E9%95%BF%E5%A4%A7%E4%BA%86%E4%B8%8D%E8%83%BD%E8%A2%AB%E9%AA%97%E4%BA%86%23) `147.9K 🔥` `+48%`
1. [王濛说签生死状复出 (Wang Meng said he would sign a life and death certificate to come back)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E8%AF%B4%E7%AD%BE%E7%94%9F%E6%AD%BB%E7%8A%B6%E5%A4%8D%E5%87%BA%23) `1.1M 🔥`
1. [马年春节新三样 (Three new things for the Spring Festival in the Year of the Horse)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%B9%B4%E6%98%A5%E8%8A%82%E6%96%B0%E4%B8%89%E6%A0%B7%23) `617.5K 🔥`
1. [刘涛演妈祖 三次圣杯](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B6%9B%E6%BC%94%E5%A6%88%E7%A5%96%20%E4%B8%89%E6%AC%A1%E5%9C%A3%E6%9D%AF%23) `444.9K 🔥`
1. [那艺娜劣迹艺人 (Na Yina's evil artist)](https://s.weibo.com/weibo?q=%23%E9%82%A3%E8%89%BA%E5%A8%9C%E5%8A%A3%E8%BF%B9%E8%89%BA%E4%BA%BA%23) `224.2K 🔥`
1. [王濛别嗦了蜜了换衣服去比赛](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E5%88%AB%E5%97%A6%E4%BA%86%E8%9C%9C%E4%BA%86%E6%8D%A2%E8%A1%A3%E6%9C%8D%E5%8E%BB%E6%AF%94%E8%B5%9B%23) `222.3K 🔥`
1. [一觉醒来特朗普改新打法了](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%A7%89%E9%86%92%E6%9D%A5%E7%89%B9%E6%9C%97%E6%99%AE%E6%94%B9%E6%96%B0%E6%89%93%E6%B3%95%E4%BA%86%23) `144.3K 🔥`
1. [医院回应女子死亡系自身过敏 (The hospital responded that the woman's death was caused by allergic reactions)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E9%99%A2%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%AD%90%E6%AD%BB%E4%BA%A1%E7%B3%BB%E8%87%AA%E8%BA%AB%E8%BF%87%E6%95%8F%23) `142.4K 🔥`
1. [姐姐回应22岁小伙烫大波浪被质疑](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%9B%9E%E5%BA%9422%E5%B2%81%E5%B0%8F%E4%BC%99%E7%83%AB%E5%A4%A7%E6%B3%A2%E6%B5%AA%E8%A2%AB%E8%B4%A8%E7%96%91%23) `140.7K 🔥`
1. [阿勒泰 刘耀文宋亚轩](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%8B%92%E6%B3%B0%20%E5%88%98%E8%80%80%E6%96%87%E5%AE%8B%E4%BA%9A%E8%BD%A9%23) `139.5K 🔥`
1. [曝那艺娜偷税漏税](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E9%82%A3%E8%89%BA%E5%A8%9C%E5%81%B7%E7%A8%8E%E6%BC%8F%E7%A8%8E%23) `137.6K 🔥`
1. [牢A解释中国人游泳夺冠美国人破防](https://s.weibo.com/weibo?q=%23%E7%89%A2A%E8%A7%A3%E9%87%8A%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B8%B8%E6%B3%B3%E5%A4%BA%E5%86%A0%E7%BE%8E%E5%9B%BD%E4%BA%BA%E7%A0%B4%E9%98%B2%23) `135.4K 🔥`
1. [方大同才二十三MV](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%A4%A7%E5%90%8C%E6%89%8D%E4%BA%8C%E5%8D%81%E4%B8%89MV%23) `134.4K 🔥`
1. [正月初五接财神 (Receive the God of Wealth on the fifth day of the first lunar month)](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E6%9C%88%E5%88%9D%E4%BA%94%E6%8E%A5%E8%B4%A2%E7%A5%9E%23) `109.0K 🔥`
1. [不让江山官宣杨洋 (Don’t let Jiangshan officials announce Yang Yang)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%AE%98%E5%AE%A3%E6%9D%A8%E6%B4%8B%23) `104.6K 🔥`
1. [金度勋疑似骚扰女艺人](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%BA%A6%E5%8B%8B%E7%96%91%E4%BC%BC%E9%AA%9A%E6%89%B0%E5%A5%B3%E8%89%BA%E4%BA%BA%23) `87.9K 🔥`
1. [人形机器人](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%BD%A2%E6%9C%BA%E5%99%A8%E4%BA%BA%23) `75.9K 🔥`
1. [不让江山 (Don't give way to the country)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%23) `73.3K 🔥`
1. [迎财神 (Welcome the God of Wealth)](https://s.weibo.com/weibo?q=%23%E8%BF%8E%E8%B4%A2%E7%A5%9E%23) `225.9K 🔥` `-72%`
1. [王濛现场观赛生气了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E7%8E%B0%E5%9C%BA%E8%A7%82%E8%B5%9B%E7%94%9F%E6%B0%94%E4%BA%86%23) `101.2K 🔥` `-44%`
1. [中韩体坛最唯美的爱情](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E9%9F%A9%E4%BD%93%E5%9D%9B%E6%9C%80%E5%94%AF%E7%BE%8E%E7%9A%84%E7%88%B1%E6%83%85%23) `100.0K 🔥` `-45%`
1. [齐天大圣烟花 (Monkey King Fireworks)](https://s.weibo.com/weibo?q=%23%E9%BD%90%E5%A4%A9%E5%A4%A7%E5%9C%A3%E7%83%9F%E8%8A%B1%23) `78.2K 🔥` `-22%`
1. [苏翊鸣回复徐梦桃小鸣酱随500](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%9B%9E%E5%A4%8D%E5%BE%90%E6%A2%A6%E6%A1%83%E5%B0%8F%E9%B8%A3%E9%85%B1%E9%9A%8F500%23) `76.8K 🔥` `-37%`

Updated at 2026-02-21 13:15:26

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
