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

1. [谁给迪丽热巴化的妆 (Who put makeup on Dilireba?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E7%BB%99%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%8C%96%E7%9A%84%E5%A6%86%23) `15.5M 🔥` `NEW`
1. [春晚分会场上大分](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%88%86%E4%BC%9A%E5%9C%BA%E4%B8%8A%E5%A4%A7%E5%88%86%23) `4.6M 🔥` `NEW`
1. [李健开净化了](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%81%A5%E5%BC%80%E5%87%80%E5%8C%96%E4%BA%86%23) `3.2M 🔥` `NEW`
1. [豆包抽奖](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E6%8A%BD%E5%A5%96%23) `786.3K 🔥` `NEW`
1. [宇树科技股票](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E7%A7%91%E6%8A%80%E8%82%A1%E7%A5%A8%23) `774.8K 🔥` `NEW`
1. [元宝](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%9D%23) `768.4K 🔥` `NEW`
1. [春晚的阿福就是蚂蚁阿福](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E7%9A%84%E9%98%BF%E7%A6%8F%E5%B0%B1%E6%98%AF%E8%9A%82%E8%9A%81%E9%98%BF%E7%A6%8F%23) `753.2K 🔥` `NEW`
1. [陈哲远 你的运气额度省下来了](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%20%E4%BD%A0%E7%9A%84%E8%BF%90%E6%B0%94%E9%A2%9D%E5%BA%A6%E7%9C%81%E4%B8%8B%E6%9D%A5%E4%BA%86%23) `737.0K 🔥` `NEW`
1. [春晚的底气是豆包大模型](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E7%9A%84%E5%BA%95%E6%B0%94%E6%98%AF%E8%B1%86%E5%8C%85%E5%A4%A7%E6%A8%A1%E5%9E%8B%23) `726.0K 🔥` `NEW`
1. [李昀锐内娱舒肤佳](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E5%86%85%E5%A8%B1%E8%88%92%E8%82%A4%E4%BD%B3%23) `714.1K 🔥` `NEW`
1. [迪丽热巴 朵莉亚新皮肤 (Dilireba Dolia new skin)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%20%E6%9C%B5%E8%8E%89%E4%BA%9A%E6%96%B0%E7%9A%AE%E8%82%A4%23) `712.1K 🔥` `NEW`
1. [支付宝口令红包](https://s.weibo.com/weibo?q=%23%E6%94%AF%E4%BB%98%E5%AE%9D%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `699.5K 🔥` `NEW`
1. [我在春晚刷短视频](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9C%A8%E6%98%A5%E6%99%9A%E5%88%B7%E7%9F%AD%E8%A7%86%E9%A2%91%23) `698.8K 🔥` `NEW`
1. [曾舜晞钻粉 人均200](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E9%92%BB%E7%B2%89%20%E4%BA%BA%E5%9D%87200%23) `695.0K 🔥` `NEW`
1. [追觅全生态春晚C位出场](https://s.weibo.com/weibo?q=%23%E8%BF%BD%E8%A7%85%E5%85%A8%E7%94%9F%E6%80%81%E6%98%A5%E6%99%9AC%E4%BD%8D%E5%87%BA%E5%9C%BA%23) `692.9K 🔥` `NEW`
1. [谁把撒贝宁做成老鼠干了](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%8A%8A%E6%92%92%E8%B4%9D%E5%AE%81%E5%81%9A%E6%88%90%E8%80%81%E9%BC%A0%E5%B9%B2%E4%BA%86%23) `686.3K 🔥` `NEW`
1. [还得是周深](https://s.weibo.com/weibo?q=%23%E8%BF%98%E5%BE%97%E6%98%AF%E5%91%A8%E6%B7%B1%23) `666.7K 🔥` `NEW`
1. [春晚同款被追觅包圆了](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%90%8C%E6%AC%BE%E8%A2%AB%E8%BF%BD%E8%A7%85%E5%8C%85%E5%9C%86%E4%BA%86%23) `651.7K 🔥` `NEW`
1. [B站弹幕](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E5%BC%B9%E5%B9%95%23) `648.9K 🔥` `NEW`
1. [张杰魏晨相视一笑](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E9%AD%8F%E6%99%A8%E7%9B%B8%E8%A7%86%E4%B8%80%E7%AC%91%23) `579.8K 🔥` `NEW`
1. [张钧甯春晚口红色号 (Janine Chang Spring Festival Gala lipstick number)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%92%A7%E7%94%AF%E6%98%A5%E6%99%9A%E5%8F%A3%E7%BA%A2%E8%89%B2%E5%8F%B7%23) `537.3K 🔥` `NEW`
1. [春晚汉族小朋友穿了汉服](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%B1%89%E6%97%8F%E5%B0%8F%E6%9C%8B%E5%8F%8B%E7%A9%BF%E4%BA%86%E6%B1%89%E6%9C%8D%23) `517.1K 🔥` `NEW`
1. [宜宾分会场 真不错](https://s.weibo.com/weibo?q=%23%E5%AE%9C%E5%AE%BE%E5%88%86%E4%BC%9A%E5%9C%BA%20%E7%9C%9F%E4%B8%8D%E9%94%99%23) `507.5K 🔥` `NEW`
1. [艾特千问陪看春晚太多梗](https://s.weibo.com/weibo?q=%23%E8%89%BE%E7%89%B9%E5%8D%83%E9%97%AE%E9%99%AA%E7%9C%8B%E6%98%A5%E6%99%9A%E5%A4%AA%E5%A4%9A%E6%A2%97%23) `502.1K 🔥` `NEW`
1. [王楚然春晚第二套](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E6%98%A5%E6%99%9A%E7%AC%AC%E4%BA%8C%E5%A5%97%23) `498.2K 🔥` `NEW`
1. [春晚贺花神用的是豆包Seedance](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%B4%BA%E8%8A%B1%E7%A5%9E%E7%94%A8%E7%9A%84%E6%98%AF%E8%B1%86%E5%8C%85Seedance%23) `487.8K 🔥` `NEW`
1. [易烊千玺春晚限定笑容](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E6%98%A5%E6%99%9A%E9%99%90%E5%AE%9A%E7%AC%91%E5%AE%B9%23) `485.6K 🔥` `NEW`
1. [王亚飞给热巴化的人鱼姬妆](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BA%9A%E9%A3%9E%E7%BB%99%E7%83%AD%E5%B7%B4%E5%8C%96%E7%9A%84%E4%BA%BA%E9%B1%BC%E5%A7%AC%E5%A6%86%23) `454.9K 🔥` `NEW`
1. [二舅来了一朵](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E8%88%85%E6%9D%A5%E4%BA%86%E4%B8%80%E6%9C%B5%23) `453.3K 🔥` `NEW`
1. [林孝埈500米顺利晋级](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88500%E7%B1%B3%E9%A1%BA%E5%88%A9%E6%99%8B%E7%BA%A7%23) `453.1K 🔥` `NEW`
1. [献给汽修工人李尚国 (Dedicated to auto repairman Li Shangguo)](https://s.weibo.com/weibo?q=%23%E7%8C%AE%E7%BB%99%E6%B1%BD%E4%BF%AE%E5%B7%A5%E4%BA%BA%E6%9D%8E%E5%B0%9A%E5%9B%BD%23) `6.5M 🔥` `+131%`
1. [我的马年抓马之旅 (My trip to catch horses in the Year of the Horse)](https://s.weibo.com/weibo?q=%23%E6%88%91%E7%9A%84%E9%A9%AC%E5%B9%B4%E6%8A%93%E9%A9%AC%E4%B9%8B%E6%97%85%23) `3.2M 🔥` `+92%`
1. [机器人全面入侵春晚 (Robots fully invade the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%85%A8%E9%9D%A2%E5%85%A5%E4%BE%B5%E6%98%A5%E6%99%9A%23) `7.1M 🔥` `-59%`
1. [春晚 (Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%23) `6.9M 🔥` `-70%`
1. [王一博郭富城炸场](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E9%83%AD%E5%AF%8C%E5%9F%8E%E7%82%B8%E5%9C%BA%23) `3.8M 🔥` `-39%`
1. [秦岚李沁王楚然美成啥了](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%B2%9A%E6%9D%8E%E6%B2%81%E7%8E%8B%E6%A5%9A%E7%84%B6%E7%BE%8E%E6%88%90%E5%95%A5%E4%BA%86%23) `3.1M 🔥` `-26%`
1. [明星红包](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%98%9F%E7%BA%A2%E5%8C%85%23) `2.1M 🔥` `-86%`
1. [短道速滑 (short track speed skating)](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `783.8K 🔥` `-84%`
1. [新年祝福语 (New Year's greetings)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%B9%B4%E7%A5%9D%E7%A6%8F%E8%AF%AD%23) `762.1K 🔥` `-84%`
1. [压岁钱](https://s.weibo.com/weibo?q=%23%E5%8E%8B%E5%B2%81%E9%92%B1%23) `757.2K 🔥` `-81%`
1. [春晚节目单 (Spring Festival Gala Program)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `748.6K 🔥` `-94%`
1. [张凌赫发了好多红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%8F%91%E4%BA%86%E5%A5%BD%E5%A4%9A%E7%BA%A2%E5%8C%85%23) `739.1K 🔥` `-69%`
1. [冬奥短道速滑男子500米预赛](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E7%94%B7%E5%AD%90500%E7%B1%B3%E9%A2%84%E8%B5%9B%23) `724.4K 🔥` `-39%`
1. [易烊千玺压得住场](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%8E%8B%E5%BE%97%E4%BD%8F%E5%9C%BA%23) `707.1K 🔥` `-88%`
1. [烟花](https://s.weibo.com/weibo?q=%23%E7%83%9F%E8%8A%B1%23) `701.2K 🔥` `-78%`
1. [年夜饭](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `691.1K 🔥` `-61%`
1. [大年初一不洗头不煮饭 (Don’t wash your hair or cook on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E6%B4%97%E5%A4%B4%E4%B8%8D%E7%85%AE%E9%A5%AD%23) `690.5K 🔥` `-56%`
1. [十二花神 好看](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%8C%E8%8A%B1%E7%A5%9E%20%E5%A5%BD%E7%9C%8B%23) `686.4K 🔥` `-46%`
1. [中国短道队男子5000米无缘决赛](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%AD%E9%81%93%E9%98%9F%E7%94%B7%E5%AD%905000%E7%B1%B3%E6%97%A0%E7%BC%98%E5%86%B3%E8%B5%9B%23) `656.8K 🔥` `-61%`
1. [撒贝宁依旧蜡笔小新眉毛](https://s.weibo.com/weibo?q=%23%E6%92%92%E8%B4%9D%E5%AE%81%E4%BE%9D%E6%97%A7%E8%9C%A1%E7%AC%94%E5%B0%8F%E6%96%B0%E7%9C%89%E6%AF%9B%23) `498.3K 🔥` `-83%`
1. [春晚后台直播](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%90%8E%E5%8F%B0%E7%9B%B4%E6%92%AD%23) `494.9K 🔥` `-71%`
1. [机器人武术 宇树无敌](https://s.weibo.com/weibo?q=%23%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%AD%A6%E6%9C%AF%20%E5%AE%87%E6%A0%91%E6%97%A0%E6%95%8C%23) `457.6K 🔥` `-90%`

Updated at 2026-02-16 22:08:19

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
