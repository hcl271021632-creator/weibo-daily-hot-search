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

1. [马丽单飞了 沈腾怎么办 (Ma Li flies solo, what should Shen Teng do?)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E4%B8%BD%E5%8D%95%E9%A3%9E%E4%BA%86%20%E6%B2%88%E8%85%BE%E6%80%8E%E4%B9%88%E5%8A%9E%23) `7.7M 🔥` `NEW`
1. [过年好](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%A5%BD%23) `5.0M 🔥` `NEW`
1. [过年反催婚的小连招](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%8F%8D%E5%82%AC%E5%A9%9A%E7%9A%84%E5%B0%8F%E8%BF%9E%E6%8B%9B%23) `2.8M 🔥` `NEW`
1. [沈腾马丽 嗑晕了](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E9%A9%AC%E4%B8%BD%20%E5%97%91%E6%99%95%E4%BA%86%23) `2.5M 🔥` `NEW`
1. [刘浩存 北舞严选](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%20%E5%8C%97%E8%88%9E%E4%B8%A5%E9%80%89%23) `1.5M 🔥` `NEW`
1. [千问上抢的红包比广东人包的多](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E4%B8%8A%E6%8A%A2%E7%9A%84%E7%BA%A2%E5%8C%85%E6%AF%94%E5%B9%BF%E4%B8%9C%E4%BA%BA%E5%8C%85%E7%9A%84%E5%A4%9A%23) `1.4M 🔥` `NEW`
1. [李一桐红包](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%B8%80%E6%A1%90%E7%BA%A2%E5%8C%85%23) `1.4M 🔥` `NEW`
1. [魏晨站山顶](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E6%99%A8%E7%AB%99%E5%B1%B1%E9%A1%B6%23) `918.7K 🔥` `NEW`
1. [这届春晚大家都在找豆包帮忙](https://s.weibo.com/weibo?q=%23%E8%BF%99%E5%B1%8A%E6%98%A5%E6%99%9A%E5%A4%A7%E5%AE%B6%E9%83%BD%E5%9C%A8%E6%89%BE%E8%B1%86%E5%8C%85%E5%B8%AE%E5%BF%99%23) `862.1K 🔥` `NEW`
1. [任素汐毛不易神仙组合](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E7%B4%A0%E6%B1%90%E6%AF%9B%E4%B8%8D%E6%98%93%E7%A5%9E%E4%BB%99%E7%BB%84%E5%90%88%23) `845.8K 🔥` `NEW`
1. [蚂蚁阿福上春晚了 (Ant Ah Fu went to the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E8%9A%82%E8%9A%81%E9%98%BF%E7%A6%8F%E4%B8%8A%E6%98%A5%E6%99%9A%E4%BA%86%23) `818.3K 🔥` `NEW`
1. [张万森 下机器人了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%B8%87%E6%A3%AE%20%E4%B8%8B%E6%9C%BA%E5%99%A8%E4%BA%BA%E4%BA%86%23) `813.7K 🔥` `NEW`
1. [在春晚看见义乌的世界情](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E6%98%A5%E6%99%9A%E7%9C%8B%E8%A7%81%E4%B9%89%E4%B9%8C%E7%9A%84%E4%B8%96%E7%95%8C%E6%83%85%23) `750.4K 🔥` `NEW`
1. [邓超妈妈](https://s.weibo.com/weibo?q=%23%E9%82%93%E8%B6%85%E5%A6%88%E5%A6%88%23) `717.9K 🔥` `NEW`
1. [马年春晚华为出镜率](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%B9%B4%E6%98%A5%E6%99%9A%E5%8D%8E%E4%B8%BA%E5%87%BA%E9%95%9C%E7%8E%87%23) `534.9K 🔥` `NEW`
1. [撒贝宁领嗑沈马](https://s.weibo.com/weibo?q=%23%E6%92%92%E8%B4%9D%E5%AE%81%E9%A2%86%E5%97%91%E6%B2%88%E9%A9%AC%23) `534.2K 🔥` `NEW`
1. [合肥分会场](https://s.weibo.com/weibo?q=%23%E5%90%88%E8%82%A5%E5%88%86%E4%BC%9A%E5%9C%BA%23) `525.1K 🔥` `NEW`
1. [汪苏泷的发型师是谁](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E7%9A%84%E5%8F%91%E5%9E%8B%E5%B8%88%E6%98%AF%E8%B0%81%23) `454.9K 🔥` `NEW`
1. [孙千红裙芭蕾](https://s.weibo.com/weibo?q=%23%E5%AD%99%E5%8D%83%E7%BA%A2%E8%A3%99%E8%8A%AD%E8%95%BE%23) `418.4K 🔥` `NEW`
1. [春晚后台直播](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%90%8E%E5%8F%B0%E7%9B%B4%E6%92%AD%23) `388.2K 🔥` `NEW`
1. [中国冰壶男队除夕夜收获首胜 (China's men's curling team gets first win on New Year's Eve)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%86%B0%E5%A3%B6%E7%94%B7%E9%98%9F%E9%99%A4%E5%A4%95%E5%A4%9C%E6%94%B6%E8%8E%B7%E9%A6%96%E8%83%9C%23) `377.5K 🔥` `NEW`
1. [张凌赫发了好多红包](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%8F%91%E4%BA%86%E5%A5%BD%E5%A4%9A%E7%BA%A2%E5%8C%85%23) `998.9K 🔥` `+26%`
1. [春晚 (Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%23) `5.0M 🔥`
1. [春晚导演 米莱狄](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%AF%BC%E6%BC%94%20%E7%B1%B3%E8%8E%B1%E7%8B%84%23) `1.2M 🔥`
1. [秦岚李沁王楚然美成啥了](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%B2%9A%E6%9D%8E%E6%B2%81%E7%8E%8B%E6%A5%9A%E7%84%B6%E7%BE%8E%E6%88%90%E5%95%A5%E4%BA%86%23) `987.5K 🔥`
1. [大年初一不洗头不煮饭 (Don’t wash your hair or cook on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E6%B4%97%E5%A4%B4%E4%B8%8D%E7%85%AE%E9%A5%AD%23) `826.9K 🔥`
1. [易烊千玺压得住场](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%8E%8B%E5%BE%97%E4%BD%8F%E5%9C%BA%23) `536.7K 🔥`
1. [哈尔滨分会场 全场最佳](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%B0%94%E6%BB%A8%E5%88%86%E4%BC%9A%E5%9C%BA%20%E5%85%A8%E5%9C%BA%E6%9C%80%E4%BD%B3%23) `438.8K 🔥`
1. [谁给迪丽热巴化的妆 (Who put makeup on Dilireba?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E7%BB%99%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%8C%96%E7%9A%84%E5%A6%86%23) `5.0M 🔥` `-51%`
1. [迪奥开运红 (Dior Lucky Red)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E5%A5%A5%E5%BC%80%E8%BF%90%E7%BA%A2%23) `4.2M 🔥` `-60%`
1. [春晚分会场上大分](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%88%86%E4%BC%9A%E5%9C%BA%E4%B8%8A%E5%A4%A7%E5%88%86%23) `3.3M 🔥` `-31%`
1. [王菲接了李谷一的班 (Faye Wong took over Li Guyi's class)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E6%8E%A5%E4%BA%86%E6%9D%8E%E8%B0%B7%E4%B8%80%E7%9A%84%E7%8F%AD%23) `2.8M 🔥` `-60%`
1. [魔术 比小品好笑](https://s.weibo.com/weibo?q=%23%E9%AD%94%E6%9C%AF%20%E6%AF%94%E5%B0%8F%E5%93%81%E5%A5%BD%E7%AC%91%23) `1.9M 🔥` `-65%`
1. [豆包红包](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E7%BA%A2%E5%8C%85%23) `1.7M 🔥` `-22%`
1. [短道速滑 (short track speed skating)](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `1.7M 🔥` `-26%`
1. [春晚 台湾回家](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%20%E5%8F%B0%E6%B9%BE%E5%9B%9E%E5%AE%B6%23) `1.7M 🔥` `-39%`
1. [宇树科技股票 (Yushu Technology Stock)](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E7%A7%91%E6%8A%80%E8%82%A1%E7%A5%A8%23) `1.4M 🔥` `-36%`
1. [新年祝福语 (New Year's greetings)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%B9%B4%E7%A5%9D%E7%A6%8F%E8%AF%AD%23) `1.4M 🔥` `-35%`
1. [陈哲远 你的运气额度省下来了](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%20%E4%BD%A0%E7%9A%84%E8%BF%90%E6%B0%94%E9%A2%9D%E5%BA%A6%E7%9C%81%E4%B8%8B%E6%9D%A5%E4%BA%86%23) `1.1M 🔥` `-48%`
1. [压岁钱](https://s.weibo.com/weibo?q=%23%E5%8E%8B%E5%B2%81%E9%92%B1%23) `992.5K 🔥` `-51%`
1. [王一博郭富城炸场 (Wang Yibo Aaron Kwok bombing site)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E9%83%AD%E5%AF%8C%E5%9F%8E%E7%82%B8%E5%9C%BA%23) `895.6K 🔥` `-31%`
1. [烟花](https://s.weibo.com/weibo?q=%23%E7%83%9F%E8%8A%B1%23) `885.6K 🔥` `-23%`
1. [支付宝口令红包](https://s.weibo.com/weibo?q=%23%E6%94%AF%E4%BB%98%E5%AE%9D%E5%8F%A3%E4%BB%A4%E7%BA%A2%E5%8C%85%23) `881.6K 🔥` `-25%`
1. [豆包抽奖](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E6%8A%BD%E5%A5%96%23) `858.4K 🔥` `-62%`
1. [邓超 魔丸变灵珠](https://s.weibo.com/weibo?q=%23%E9%82%93%E8%B6%85%20%E9%AD%94%E4%B8%B8%E5%8F%98%E7%81%B5%E7%8F%A0%23) `774.9K 🔥` `-51%`
1. [白鹿 陈哲远951](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%20%E9%99%88%E5%93%B2%E8%BF%9C951%23) `731.5K 🔥` `-60%`
1. [元宝 (Yuanbao)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%9D%23) `718.1K 🔥` `-67%`
1. [春晚同款被追觅包圆了](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%90%8C%E6%AC%BE%E8%A2%AB%E8%BF%BD%E8%A7%85%E5%8C%85%E5%9C%86%E4%BA%86%23) `576.1K 🔥` `-72%`
1. [年夜饭 (New Year's Eve dinner)](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%A4%9C%E9%A5%AD%23) `534.2K 🔥` `-51%`
1. [曾舜晞钻粉 人均200](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E9%92%BB%E7%B2%89%20%E4%BA%BA%E5%9D%87200%23) `481.1K 🔥` `-27%`
1. [李健开净化了 (Li Jiankai purified)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%81%A5%E5%BC%80%E5%87%80%E5%8C%96%E4%BA%86%23) `452.3K 🔥` `-41%`
1. [谷爱凌大年初一凌晨争金](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E5%87%8C%E6%99%A8%E4%BA%89%E9%87%91%23) `386.9K 🔥` `-28%`

Updated at 2026-02-16 23:52:50

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
