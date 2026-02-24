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

1. [金所泫宋江二搭 (Kim So Hyun and Song Jiang Erdu)](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%89%80%E6%B3%AB%E5%AE%8B%E6%B1%9F%E4%BA%8C%E6%90%AD%23) `240.5K 🔥` `NEW`
1. [卢昱晓回复外婆去世的粉丝](https://s.weibo.com/weibo?q=%23%E5%8D%A2%E6%98%B1%E6%99%93%E5%9B%9E%E5%A4%8D%E5%A4%96%E5%A9%86%E5%8E%BB%E4%B8%96%E7%9A%84%E7%B2%89%E4%B8%9D%23) `213.0K 🔥` `NEW`
1. [开了个公众号和父母进行魔法对轰](https://s.weibo.com/weibo?q=%23%E5%BC%80%E4%BA%86%E4%B8%AA%E5%85%AC%E4%BC%97%E5%8F%B7%E5%92%8C%E7%88%B6%E6%AF%8D%E8%BF%9B%E8%A1%8C%E9%AD%94%E6%B3%95%E5%AF%B9%E8%BD%B0%23) `210.5K 🔥` `NEW`
1. [一栗小莎子第三次化疗](https://s.weibo.com/weibo?q=%23%E4%B8%80%E6%A0%97%E5%B0%8F%E8%8E%8E%E5%AD%90%E7%AC%AC%E4%B8%89%E6%AC%A1%E5%8C%96%E7%96%97%23) `210.2K 🔥` `NEW`
1. [张元英solo成绩](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%85%83%E8%8B%B1solo%E6%88%90%E7%BB%A9%23) `208.9K 🔥` `NEW`
1. [湖南湘阴一男子放烟花时炸膛致身亡](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E6%B9%98%E9%98%B4%E4%B8%80%E7%94%B7%E5%AD%90%E6%94%BE%E7%83%9F%E8%8A%B1%E6%97%B6%E7%82%B8%E8%86%9B%E8%87%B4%E8%BA%AB%E4%BA%A1%23) `207.2K 🔥` `NEW`
1. [平顶山被打女孩轻伤二级](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E9%A1%B6%E5%B1%B1%E8%A2%AB%E6%89%93%E5%A5%B3%E5%AD%A9%E8%BD%BB%E4%BC%A4%E4%BA%8C%E7%BA%A7%23) `184.8K 🔥` `NEW`
1. [专家称AI时代文科比理科吃香](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E7%A7%B0AI%E6%97%B6%E4%BB%A3%E6%96%87%E7%A7%91%E6%AF%94%E7%90%86%E7%A7%91%E5%90%83%E9%A6%99%23) `179.9K 🔥` `NEW`
1. [李现和杨紫父母穿同款外套](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%8E%B0%E5%92%8C%E6%9D%A8%E7%B4%AB%E7%88%B6%E6%AF%8D%E7%A9%BF%E5%90%8C%E6%AC%BE%E5%A4%96%E5%A5%97%23) `179.8K 🔥` `NEW`
1. [金银价格大涨原因](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%93%B6%E4%BB%B7%E6%A0%BC%E5%A4%A7%E6%B6%A8%E5%8E%9F%E5%9B%A0%23) `160.6K 🔥` `NEW`
1. [迅猛龙考研估分190考出来223 (The Velociraptor postgraduate entrance examination score was estimated to be 190 and the score was 223)](https://s.weibo.com/weibo?q=%23%E8%BF%85%E7%8C%9B%E9%BE%99%E8%80%83%E7%A0%94%E4%BC%B0%E5%88%86190%E8%80%83%E5%87%BA%E6%9D%A5223%23) `154.6K 🔥` `NEW`
1. [边伯贤 SM](https://s.weibo.com/weibo?q=%23%E8%BE%B9%E4%BC%AF%E8%B4%A4%20SM%23) `150.4K 🔥` `NEW`
1. [墨西哥特种部队与毒枭火拼](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A5%E7%89%B9%E7%A7%8D%E9%83%A8%E9%98%9F%E4%B8%8E%E6%AF%92%E6%9E%AD%E7%81%AB%E6%8B%BC%23) `129.0K 🔥` `NEW`
1. [志胜跟大哥十指紧扣](https://s.weibo.com/weibo?q=%23%E5%BF%97%E8%83%9C%E8%B7%9F%E5%A4%A7%E5%93%A5%E5%8D%81%E6%8C%87%E7%B4%A7%E6%89%A3%23) `117.8K 🔥` `NEW`
1. [吵了一年要辞职 初八文案是开工大吉](https://s.weibo.com/weibo?q=%23%E5%90%B5%E4%BA%86%E4%B8%80%E5%B9%B4%E8%A6%81%E8%BE%9E%E8%81%8C%20%E5%88%9D%E5%85%AB%E6%96%87%E6%A1%88%E6%98%AF%E5%BC%80%E5%B7%A5%E5%A4%A7%E5%90%89%23) `111.3K 🔥` `NEW`
1. [深圳一企业开工给员工发百元利是](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E4%B8%80%E4%BC%81%E4%B8%9A%E5%BC%80%E5%B7%A5%E7%BB%99%E5%91%98%E5%B7%A5%E5%8F%91%E7%99%BE%E5%85%83%E5%88%A9%E6%98%AF%23) `103.8K 🔥` `NEW`
1. [王一博还演过红孩儿](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%BF%98%E6%BC%94%E8%BF%87%E7%BA%A2%E5%AD%A9%E5%84%BF%23) `99.9K 🔥` `NEW`
1. [朱一龙演我打到臭车](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E4%B8%80%E9%BE%99%E6%BC%94%E6%88%91%E6%89%93%E5%88%B0%E8%87%AD%E8%BD%A6%23) `98.2K 🔥` `NEW`
1. [二十多年烤全羊老板谈行业乱象](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E5%8D%81%E5%A4%9A%E5%B9%B4%E7%83%A4%E5%85%A8%E7%BE%8A%E8%80%81%E6%9D%BF%E8%B0%88%E8%A1%8C%E4%B8%9A%E4%B9%B1%E8%B1%A1%23) `96.6K 🔥` `NEW`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `89.4K 🔥` `NEW`
1. [长和反对巴拿马政府强行接管 (CK Hutchison opposes the forced takeover by the Panamanian government)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E5%92%8C%E5%8F%8D%E5%AF%B9%E5%B7%B4%E6%8B%BF%E9%A9%AC%E6%94%BF%E5%BA%9C%E5%BC%BA%E8%A1%8C%E6%8E%A5%E7%AE%A1%23) `80.9K 🔥` `NEW`
1. [王俊凯海边花絮](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E6%B5%B7%E8%BE%B9%E8%8A%B1%E7%B5%AE%23) `80.5K 🔥` `NEW`
1. [宝马因需求不足放弃7系L3辅助驾驶](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E9%A9%AC%E5%9B%A0%E9%9C%80%E6%B1%82%E4%B8%8D%E8%B6%B3%E6%94%BE%E5%BC%837%E7%B3%BBL3%E8%BE%85%E5%8A%A9%E9%A9%BE%E9%A9%B6%23) `76.7K 🔥` `NEW`
1. [考研出分时间 (Postgraduate entrance examination score time)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E5%87%BA%E5%88%86%E6%97%B6%E9%97%B4%23) `1.1M 🔥` `+40%`
1. [妈妈回应瑶一瑶表演时不开心](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9B%9E%E5%BA%94%E7%91%B6%E4%B8%80%E7%91%B6%E8%A1%A8%E6%BC%94%E6%97%B6%E4%B8%8D%E5%BC%80%E5%BF%83%23) `212.1K 🔥` `+25%`
1. [考研](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%23) `133.6K 🔥` `+21%`
1. [特朗普称不知道还能活多久](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E4%B8%8D%E7%9F%A5%E9%81%93%E8%BF%98%E8%83%BD%E6%B4%BB%E5%A4%9A%E4%B9%85%23) `119.8K 🔥` `+25%`
1. [米兰冬奥超越胜负的动人瞬间 (Moving moments beyond victory and defeat at the Milan Winter Olympics)](https://s.weibo.com/weibo?q=%23%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E8%B6%85%E8%B6%8A%E8%83%9C%E8%B4%9F%E7%9A%84%E5%8A%A8%E4%BA%BA%E7%9E%AC%E9%97%B4%23) `637.9K 🔥`
1. [女生失联后用牛粪保温在牛棚被找到](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E5%A4%B1%E8%81%94%E5%90%8E%E7%94%A8%E7%89%9B%E7%B2%AA%E4%BF%9D%E6%B8%A9%E5%9C%A8%E7%89%9B%E6%A3%9A%E8%A2%AB%E6%89%BE%E5%88%B0%23) `462.1K 🔥`
1. [考研查分 (Postgraduate entrance examination score check)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E6%9F%A5%E5%88%86%23) `317.1K 🔥`
1. [开工第一天 请假](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%20%E8%AF%B7%E5%81%87%23) `305.7K 🔥`
1. [灵隐寺惊现110万家厂商祈福](https://s.weibo.com/weibo?q=%23%E7%81%B5%E9%9A%90%E5%AF%BA%E6%83%8A%E7%8E%B0110%E4%B8%87%E5%AE%B6%E5%8E%82%E5%95%86%E7%A5%88%E7%A6%8F%23) `290.4K 🔥`
1. [iPhone18 折叠](https://s.weibo.com/weibo?q=%23iPhone18%20%E6%8A%98%E5%8F%A0%23) `214.5K 🔥`
1. [日本 (Japan)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%23) `207.2K 🔥`
1. [iPhone18Pro新配色目标一眼最新款 (iPhone 18 Pro new color target at a glance the latest model)](https://s.weibo.com/weibo?q=%23iPhone18Pro%E6%96%B0%E9%85%8D%E8%89%B2%E7%9B%AE%E6%A0%87%E4%B8%80%E7%9C%BC%E6%9C%80%E6%96%B0%E6%AC%BE%23) `172.5K 🔥`
1. [假如你从初八开始找工作](https://s.weibo.com/weibo?q=%23%E5%81%87%E5%A6%82%E4%BD%A0%E4%BB%8E%E5%88%9D%E5%85%AB%E5%BC%80%E5%A7%8B%E6%89%BE%E5%B7%A5%E4%BD%9C%23) `127.3K 🔥`
1. [研招网](https://s.weibo.com/weibo?q=%23%E7%A0%94%E6%8B%9B%E7%BD%91%23) `125.1K 🔥`
1. [开工第一件事调整工位风水](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E4%BB%B6%E4%BA%8B%E8%B0%83%E6%95%B4%E5%B7%A5%E4%BD%8D%E9%A3%8E%E6%B0%B4%23) `95.2K 🔥`
1. [高速免费最后1分钟实拍 (High speed free last minute real shot)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%85%8D%E8%B4%B9%E6%9C%80%E5%90%8E1%E5%88%86%E9%92%9F%E5%AE%9E%E6%8B%8D%23) `95.1K 🔥`
1. [12306半夜候补成功1700元车票作废 (12306 Successful waiting list in the middle of the night, ticket worth 1,700 yuan is invalid)](https://s.weibo.com/weibo?q=%2312306%E5%8D%8A%E5%A4%9C%E5%80%99%E8%A1%A5%E6%88%90%E5%8A%9F1700%E5%85%83%E8%BD%A6%E7%A5%A8%E4%BD%9C%E5%BA%9F%23) `817.5K 🔥` `-26%`
1. [官方通报36斤羊烤完仅剩6.9斤](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A536%E6%96%A4%E7%BE%8A%E7%83%A4%E5%AE%8C%E4%BB%85%E5%89%A96.9%E6%96%A4%23) `215.9K 🔥` `-45%`
1. [芒果搞钱综艺要来了](https://s.weibo.com/weibo?q=%23%E8%8A%92%E6%9E%9C%E6%90%9E%E9%92%B1%E7%BB%BC%E8%89%BA%E8%A6%81%E6%9D%A5%E4%BA%86%23) `215.2K 🔥` `-27%`
1. [50岁的陈坤24岁的张康乐](https://s.weibo.com/weibo?q=%2350%E5%B2%81%E7%9A%84%E9%99%88%E5%9D%A424%E5%B2%81%E7%9A%84%E5%BC%A0%E5%BA%B7%E4%B9%90%23) `176.7K 🔥` `-26%`
1. [看演唱会旁边坐的白鹿](https://s.weibo.com/weibo?q=%23%E7%9C%8B%E6%BC%94%E5%94%B1%E4%BC%9A%E6%97%81%E8%BE%B9%E5%9D%90%E7%9A%84%E7%99%BD%E9%B9%BF%23) `163.1K 🔥` `-29%`
1. [这些证书可抵个税](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%BA%9B%E8%AF%81%E4%B9%A6%E5%8F%AF%E6%8A%B5%E4%B8%AA%E7%A8%8E%23) `144.2K 🔥` `-33%`
1. [章若楠王安宇排名不分先后 (Zhang Ruonan and Wang Anyu are ranked in no particular order)](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E8%8B%A5%E6%A5%A0%E7%8E%8B%E5%AE%89%E5%AE%87%E6%8E%92%E5%90%8D%E4%B8%8D%E5%88%86%E5%85%88%E5%90%8E%23) `116.6K 🔥` `-25%`
1. [这胡同别让王一博看见了](https://s.weibo.com/weibo?q=%23%E8%BF%99%E8%83%A1%E5%90%8C%E5%88%AB%E8%AE%A9%E7%8E%8B%E4%B8%80%E5%8D%9A%E7%9C%8B%E8%A7%81%E4%BA%86%23) `99.9K 🔥` `-54%`
1. [丁程鑫严浩翔比24 (Ding Chengxin Yan Hao Xiangbi 24)](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E4%B8%A5%E6%B5%A9%E7%BF%94%E6%AF%9424%23) `87.2K 🔥` `-44%`
1. [生命树豆瓣分数涨至8.3](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%E8%B1%86%E7%93%A3%E5%88%86%E6%95%B0%E6%B6%A8%E8%87%B38.3%23) `77.4K 🔥` `-21%`
1. [郑钦文取关里巴教练](https://s.weibo.com/weibo?q=%23%E9%83%91%E9%92%A6%E6%96%87%E5%8F%96%E5%85%B3%E9%87%8C%E5%B7%B4%E6%95%99%E7%BB%83%23) `76.7K 🔥` `-43%`

Updated at 2026-02-24 15:01:05

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
