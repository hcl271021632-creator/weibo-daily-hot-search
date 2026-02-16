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

1. [王菲接了李谷一的班 (Faye Wong took over Li Guyi's class)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E6%8E%A5%E4%BA%86%E6%9D%8E%E8%B0%B7%E4%B8%80%E7%9A%84%E7%8F%AD%23) `7.0M 🔥` `NEW`
1. [魔术 比小品好笑](https://s.weibo.com/weibo?q=%23%E9%AD%94%E6%9C%AF%20%E6%AF%94%E5%B0%8F%E5%93%81%E5%A5%BD%E7%AC%91%23) `5.4M 🔥` `NEW`
1. [春晚 台湾回家](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%20%E5%8F%B0%E6%B9%BE%E5%9B%9E%E5%AE%B6%23) `2.7M 🔥` `NEW`
1. [王菲 真妈妈来了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%20%E7%9C%9F%E5%A6%88%E5%A6%88%E6%9D%A5%E4%BA%86%23) `2.3M 🔥` `NEW`
1. [豆包红包](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E7%BA%A2%E5%8C%85%23) `2.2M 🔥` `NEW`
1. [白鹿 陈哲远951](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%20%E9%99%88%E5%93%B2%E8%BF%9C951%23) `1.8M 🔥` `NEW`
1. [邓超 魔丸变灵珠](https://s.weibo.com/weibo?q=%23%E9%82%93%E8%B6%85%20%E9%AD%94%E4%B8%B8%E5%8F%98%E7%81%B5%E7%8F%A0%23) `1.6M 🔥` `NEW`
1. [邓超不当显眼包了我不习惯](https://s.weibo.com/weibo?q=%23%E9%82%93%E8%B6%85%E4%B8%8D%E5%BD%93%E6%98%BE%E7%9C%BC%E5%8C%85%E4%BA%86%E6%88%91%E4%B8%8D%E4%B9%A0%E6%83%AF%23) `1.3M 🔥` `NEW`
1. [春晚导演 米莱狄](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%AF%BC%E6%BC%94%20%E7%B1%B3%E8%8E%B1%E7%8B%84%23) `1.2M 🔥` `NEW`
1. [2162227](https://s.weibo.com/weibo?q=%232162227%23) `1.1M 🔥` `NEW`
1. [春晚小品这个帅哥是谁 (Who is this handsome guy in the Spring Festival Gala skit?)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%B0%8F%E5%93%81%E8%BF%99%E4%B8%AA%E5%B8%85%E5%93%A5%E6%98%AF%E8%B0%81%23) `881.4K 🔥` `NEW`
1. [春晚进步最快的是蔡明的孙子](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%BF%9B%E6%AD%A5%E6%9C%80%E5%BF%AB%E7%9A%84%E6%98%AF%E8%94%A1%E6%98%8E%E7%9A%84%E5%AD%99%E5%AD%90%23) `726.5K 🔥` `NEW`
1. [撒贝宁 你有八十了吗](https://s.weibo.com/weibo?q=%23%E6%92%92%E8%B4%9D%E5%AE%81%20%E4%BD%A0%E6%9C%89%E5%85%AB%E5%8D%81%E4%BA%86%E5%90%97%23) `652.8K 🔥` `NEW`
1. [梁家辉唱跳 虐待老人](https://s.weibo.com/weibo?q=%23%E6%A2%81%E5%AE%B6%E8%BE%89%E5%94%B1%E8%B7%B3%20%E8%99%90%E5%BE%85%E8%80%81%E4%BA%BA%23) `576.9K 🔥` `NEW`
1. [哈尔滨分会场 全场最佳](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%B0%94%E6%BB%A8%E5%88%86%E4%BC%9A%E5%9C%BA%20%E5%85%A8%E5%9C%BA%E6%9C%80%E4%BD%B3%23) `549.2K 🔥` `NEW`
1. [宋佳喊小孩](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BD%B3%E5%96%8A%E5%B0%8F%E5%AD%A9%23) `543.1K 🔥` `NEW`
1. [谷爱凌大年初一凌晨争金](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E5%87%8C%E6%99%A8%E4%BA%89%E9%87%91%23) `536.5K 🔥` `NEW`
1. [追觅全场景生态亮相春晚](https://s.weibo.com/weibo?q=%23%E8%BF%BD%E8%A7%85%E5%85%A8%E5%9C%BA%E6%99%AF%E7%94%9F%E6%80%81%E4%BA%AE%E7%9B%B8%E6%98%A5%E6%99%9A%23) `5.3M 🔥` `+111%`
1. [豆包抽奖](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E6%8A%BD%E5%A5%96%23) `2.3M 🔥` `+189%`
1. [短道速滑 (short track speed skating)](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `2.2M 🔥` `+186%`
1. [宇树科技股票](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E7%A7%91%E6%8A%80%E8%82%A1%E7%A5%A8%23) `2.2M 🔥` `+186%`
1. [元宝 (Yuanbao)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%9D%23) `2.2M 🔥` `+183%`
1. [新年祝福语 (New Year's greetings)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%B9%B4%E7%A5%9D%E7%A6%8F%E8%AF%AD%23) `2.2M 🔥` `+182%`
1. [春晚的阿福就是蚂蚁阿福](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E7%9A%84%E9%98%BF%E7%A6%8F%E5%B0%B1%E6%98%AF%E8%9A%82%E8%9A%81%E9%98%BF%E7%A6%8F%23) `2.1M 🔥` `+181%`
1. [陈哲远 你的运气额度省下来了](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%20%E4%BD%A0%E7%9A%84%E8%BF%90%E6%B0%94%E9%A2%9D%E5%BA%A6%E7%9C%81%E4%B8%8B%E6%9D%A5%E4%BA%86%23) `2.1M 🔥` `+186%`
1. [春晚同款被追觅包圆了](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%90%8C%E6%AC%BE%E8%A2%AB%E8%BF%BD%E8%A7%85%E5%8C%85%E5%9C%86%E4%BA%86%23) `2.1M 🔥` `+220%`
1. [压岁钱](https://s.weibo.com/weibo?q=%23%E5%8E%8B%E5%B2%81%E9%92%B1%23) `2.0M 🔥` `+166%`
1. [冬奥短道速滑男子500米预赛](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E7%94%B7%E5%AD%90500%E7%B1%B3%E9%A2%84%E8%B5%9B%23) `1.9M 🔥` `+162%`
1. [艾特千问陪看春晚太多梗](https://s.weibo.com/weibo?q=%23%E8%89%BE%E7%89%B9%E5%8D%83%E9%97%AE%E9%99%AA%E7%9C%8B%E6%98%A5%E6%99%9A%E5%A4%AA%E5%A4%9A%E6%A2%97%23) `1.9M 🔥` `+272%`
1. [支付宝口令红包](https://s.weibo.com/weibo?q=%23%E6%94%AF%E4%BB%98%E5%AE%9D%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `1.2M 🔥` `+67%`
1. [烟花](https://s.weibo.com/weibo?q=%23%E7%83%9F%E8%8A%B1%23) `1.2M 🔥` `+64%`
1. [春晚贺花神用的是豆包Seedance](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%B4%BA%E8%8A%B1%E7%A5%9E%E7%94%A8%E7%9A%84%E6%98%AF%E8%B1%86%E5%8C%85Seedance%23) `1.1M 🔥` `+129%`
1. [年夜饭 (New Year's Eve dinner)](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `1.1M 🔥` `+57%`
1. [张钧甯春晚口红色号 (Janine Chang Spring Festival Gala lipstick number)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%92%A7%E7%94%AF%E6%98%A5%E6%99%9A%E5%8F%A3%E7%BA%A2%E8%89%B2%E5%8F%B7%23) `1.1M 🔥` `+98%`
1. [春晚 (Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%23) `6.0M 🔥`
1. [春晚分会场上大分](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%88%86%E4%BC%9A%E5%9C%BA%E4%B8%8A%E5%A4%A7%E5%88%86%23) `4.7M 🔥`
1. [我的马年抓马之旅 (My trip to catch horses in the Year of the Horse)](https://s.weibo.com/weibo?q=%23%E6%88%91%E7%9A%84%E9%A9%AC%E5%B9%B4%E6%8A%93%E9%A9%AC%E4%B9%8B%E6%97%85%23) `3.2M 🔥`
1. [张凌赫发了好多红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%8F%91%E4%BA%86%E5%A5%BD%E5%A4%9A%E7%BA%A2%E5%8C%85%23) `790.2K 🔥`
1. [大年初一不洗头不煮饭 (Don’t wash your hair or cook on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E6%B4%97%E5%A4%B4%E4%B8%8D%E7%85%AE%E9%A5%AD%23) `775.5K 🔥`
1. [李昀锐内娱舒肤佳](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E5%86%85%E5%A8%B1%E8%88%92%E8%82%A4%E4%BD%B3%23) `761.6K 🔥`
1. [曾舜晞钻粉 人均200](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E9%92%BB%E7%B2%89%20%E4%BA%BA%E5%9D%87200%23) `657.2K 🔥`
1. [迪丽热巴 朵莉亚新皮肤 (Dilireba Dolia new skin)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%20%E6%9C%B5%E8%8E%89%E4%BA%9A%E6%96%B0%E7%9A%AE%E8%82%A4%23) `652.7K 🔥`
1. [易烊千玺压得住场](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%8E%8B%E5%BE%97%E4%BD%8F%E5%9C%BA%23) `611.5K 🔥`
1. [张杰魏晨相视一笑](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E9%AD%8F%E6%99%A8%E7%9B%B8%E8%A7%86%E4%B8%80%E7%AC%91%23) `553.3K 🔥`
1. [谁把撒贝宁做成老鼠干了](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%8A%8A%E6%92%92%E8%B4%9D%E5%AE%81%E5%81%9A%E6%88%90%E8%80%81%E9%BC%A0%E5%B9%B2%E4%BA%86%23) `551.3K 🔥`
1. [中国短道队男子5000米无缘决赛](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%AD%E9%81%93%E9%98%9F%E7%94%B7%E5%AD%905000%E7%B1%B3%E6%97%A0%E7%BC%98%E5%86%B3%E8%B5%9B%23) `544.0K 🔥`
1. [林孝埈500米顺利晋级](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88500%E7%B1%B3%E9%A1%BA%E5%88%A9%E6%99%8B%E7%BA%A7%23) `534.4K 🔥`
1. [谁给迪丽热巴化的妆 (Who put makeup on Dilireba?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E7%BB%99%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%8C%96%E7%9A%84%E5%A6%86%23) `10.2M 🔥` `-34%`
1. [机器人全面入侵春晚 (Robots fully invade the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%85%A8%E9%9D%A2%E5%85%A5%E4%BE%B5%E6%98%A5%E6%99%9A%23) `3.2M 🔥` `-55%`
1. [王一博郭富城炸场 (Wang Yibo Aaron Kwok bombing site)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E9%83%AD%E5%AF%8C%E5%9F%8E%E7%82%B8%E5%9C%BA%23) `1.3M 🔥` `-66%`
1. [秦岚李沁王楚然美成啥了](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%B2%9A%E6%9D%8E%E6%B2%81%E7%8E%8B%E6%A5%9A%E7%84%B6%E7%BE%8E%E6%88%90%E5%95%A5%E4%BA%86%23) `1.1M 🔥` `-65%`
1. [李健开净化了](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%81%A5%E5%BC%80%E5%87%80%E5%8C%96%E4%BA%86%23) `772.2K 🔥` `-76%`

Updated at 2026-02-16 23:00:09

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
