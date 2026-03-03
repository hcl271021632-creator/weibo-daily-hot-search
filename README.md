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

1. [谢娜喊话薛之谦 (Xie Na shouts to Joker Xue)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E5%96%8A%E8%AF%9D%E8%96%9B%E4%B9%8B%E8%B0%A6%23) `13.0M 🔥` `NEW`
1. [红果停了很多项目](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E6%9E%9C%E5%81%9C%E4%BA%86%E5%BE%88%E5%A4%9A%E9%A1%B9%E7%9B%AE%23) `853.1K 🔥` `NEW`
1. [骏马闹元宵贺卡](https://s.weibo.com/weibo?q=%23%E9%AA%8F%E9%A9%AC%E9%97%B9%E5%85%83%E5%AE%B5%E8%B4%BA%E5%8D%A1%23) `646.1K 🔥` `NEW`
1. [伊朗发起第13轮攻击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC13%E8%BD%AE%E6%94%BB%E5%87%BB%23) `359.7K 🔥` `NEW`
1. [当地通报母亲去世后被结婚](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%9C%B0%E9%80%9A%E6%8A%A5%E6%AF%8D%E4%BA%B2%E5%8E%BB%E4%B8%96%E5%90%8E%E8%A2%AB%E7%BB%93%E5%A9%9A%23) `358.5K 🔥` `NEW`
1. [火车硬座惊现上下铺](https://s.weibo.com/weibo?q=%23%E7%81%AB%E8%BD%A6%E7%A1%AC%E5%BA%A7%E6%83%8A%E7%8E%B0%E4%B8%8A%E4%B8%8B%E9%93%BA%23) `304.4K 🔥` `NEW`
1. [女子蹭完WiFi借钱被拒掀翻店家桌子](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%B9%AD%E5%AE%8CWiFi%E5%80%9F%E9%92%B1%E8%A2%AB%E6%8B%92%E6%8E%80%E7%BF%BB%E5%BA%97%E5%AE%B6%E6%A1%8C%E5%AD%90%23) `179.9K 🔥` `NEW`
1. [巴黎时装周](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%23) `179.7K 🔥` `NEW`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `173.9K 🔥` `NEW`
1. [杨幂说女孩子要多吃berry](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%AF%B4%E5%A5%B3%E5%AD%A9%E5%AD%90%E8%A6%81%E5%A4%9A%E5%90%83berry%23) `171.8K 🔥` `NEW`
1. [戒糖加跳绳5个月威力有多大 (How powerful is quitting sugar and skipping rope for 5 months?)](https://s.weibo.com/weibo?q=%23%E6%88%92%E7%B3%96%E5%8A%A0%E8%B7%B3%E7%BB%B35%E4%B8%AA%E6%9C%88%E5%A8%81%E5%8A%9B%E6%9C%89%E5%A4%9A%E5%A4%A7%23) `169.3K 🔥` `NEW`
1. [伊朗一医院遭袭后画面](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%8C%BB%E9%99%A2%E9%81%AD%E8%A2%AD%E5%90%8E%E7%94%BB%E9%9D%A2%23) `167.7K 🔥` `NEW`
1. [保镖对IU和曹承衍的表情差异](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E9%95%96%E5%AF%B9IU%E5%92%8C%E6%9B%B9%E6%89%BF%E8%A1%8D%E7%9A%84%E8%A1%A8%E6%83%85%E5%B7%AE%E5%BC%82%23) `161.4K 🔥` `NEW`
1. [以色列空袭黎巴嫩52死154伤](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E7%A9%BA%E8%A2%AD%E9%BB%8E%E5%B7%B4%E5%AB%A952%E6%AD%BB154%E4%BC%A4%23) `161.4K 🔥` `NEW`
1. [美国驻沙特大使馆遭袭起火](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E9%A9%BB%E6%B2%99%E7%89%B9%E5%A4%A7%E4%BD%BF%E9%A6%86%E9%81%AD%E8%A2%AD%E8%B5%B7%E7%81%AB%23) `161.3K 🔥` `NEW`
1. [霸王茶姬答案](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E7%AD%94%E6%A1%88%23) `161.3K 🔥` `NEW`
1. [iPhone最便宜新机来了](https://s.weibo.com/weibo?q=%23iPhone%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%96%B0%E6%9C%BA%E6%9D%A5%E4%BA%86%23) `161.3K 🔥` `NEW`
1. [以伊代表在联合国隔空交锋](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%BC%8A%E4%BB%A3%E8%A1%A8%E5%9C%A8%E8%81%94%E5%90%88%E5%9B%BD%E9%9A%94%E7%A9%BA%E4%BA%A4%E9%94%8B%23) `161.3K 🔥` `NEW`
1. [汤圆](https://s.weibo.com/weibo?q=%23%E6%B1%A4%E5%9C%86%23) `161.2K 🔥` `NEW`
1. [两会](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `161.2K 🔥` `NEW`
1. [王天辰被叫姐夫后暗爽 (Wang Tianchen felt happy after being called brother-in-law)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%E8%A2%AB%E5%8F%AB%E5%A7%90%E5%A4%AB%E5%90%8E%E6%9A%97%E7%88%BD%23) `161.1K 🔥` `NEW`
1. [领克汽车 美食免单卡](https://s.weibo.com/weibo?q=%23%E9%A2%86%E5%85%8B%E6%B1%BD%E8%BD%A6%20%E7%BE%8E%E9%A3%9F%E5%85%8D%E5%8D%95%E5%8D%A1%23) `161.0K 🔥` `NEW`
1. [曝库里和追梦计划全力招募詹姆斯](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%BA%93%E9%87%8C%E5%92%8C%E8%BF%BD%E6%A2%A6%E8%AE%A1%E5%88%92%E5%85%A8%E5%8A%9B%E6%8B%9B%E5%8B%9F%E8%A9%B9%E5%A7%86%E6%96%AF%23) `160.9K 🔥` `NEW`
1. [2026世界杯倒计时100天](https://s.weibo.com/weibo?q=%232026%E4%B8%96%E7%95%8C%E6%9D%AF%E5%80%92%E8%AE%A1%E6%97%B6100%E5%A4%A9%23) `160.9K 🔥` `NEW`
1. [当老外被中国人邀请吃饭](https://s.weibo.com/weibo?q=%23%E5%BD%93%E8%80%81%E5%A4%96%E8%A2%AB%E4%B8%AD%E5%9B%BD%E4%BA%BA%E9%82%80%E8%AF%B7%E5%90%83%E9%A5%AD%23) `160.8K 🔥` `NEW`
1. [拼豆人有自己的大疆](https://s.weibo.com/weibo?q=%23%E6%8B%BC%E8%B1%86%E4%BA%BA%E6%9C%89%E8%87%AA%E5%B7%B1%E7%9A%84%E5%A4%A7%E7%96%86%23) `160.8K 🔥` `NEW`
1. [王楚钦观赏鲨鱼](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%A7%82%E8%B5%8F%E9%B2%A8%E9%B1%BC%23) `160.8K 🔥` `NEW`
1. [尚公主](https://s.weibo.com/weibo?q=%23%E5%B0%9A%E5%85%AC%E4%B8%BB%23) `160.7K 🔥` `NEW`
1. [月全食](https://s.weibo.com/weibo?q=%23%E6%9C%88%E5%85%A8%E9%A3%9F%23) `160.6K 🔥` `NEW`
1. [苹果推出大量粉色配件](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%8E%A8%E5%87%BA%E5%A4%A7%E9%87%8F%E7%B2%89%E8%89%B2%E9%85%8D%E4%BB%B6%23) `160.6K 🔥` `NEW`
1. [恋与深空发文致歉 (Love and Deep Space issued an apology)](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%E5%8F%91%E6%96%87%E8%87%B4%E6%AD%89%23) `160.6K 🔥` `NEW`
1. [18名美军士兵在对伊行动中受重伤](https://s.weibo.com/weibo?q=%2318%E5%90%8D%E7%BE%8E%E5%86%9B%E5%A3%AB%E5%85%B5%E5%9C%A8%E5%AF%B9%E4%BC%8A%E8%A1%8C%E5%8A%A8%E4%B8%AD%E5%8F%97%E9%87%8D%E4%BC%A4%23) `160.5K 🔥` `NEW`
1. [刘宇宁宋雨琦合作新歌](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%AE%8B%E9%9B%A8%E7%90%A6%E5%90%88%E4%BD%9C%E6%96%B0%E6%AD%8C%23) `160.5K 🔥` `NEW`
1. [年轻人有自己的汤圆吃法](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E8%BD%BB%E4%BA%BA%E6%9C%89%E8%87%AA%E5%B7%B1%E7%9A%84%E6%B1%A4%E5%9C%86%E5%90%83%E6%B3%95%23) `160.4K 🔥` `NEW`
1. [江苏卫视元宵晚会节目单](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E8%8B%8F%E5%8D%AB%E8%A7%86%E5%85%83%E5%AE%B5%E6%99%9A%E4%BC%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `160.4K 🔥` `NEW`
1. [杨幂5分半米兰vlog](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%825%E5%88%86%E5%8D%8A%E7%B1%B3%E5%85%B0vlog%23) `160.4K 🔥` `NEW`
1. [越来越多国家被卷入中东冲突](https://s.weibo.com/weibo?q=%23%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%A4%9A%E5%9B%BD%E5%AE%B6%E8%A2%AB%E5%8D%B7%E5%85%A5%E4%B8%AD%E4%B8%9C%E5%86%B2%E7%AA%81%23) `1.1M 🔥` `+937%`
1. [移步巴塞看中国 (Move to Barcelona and see China)](https://s.weibo.com/weibo?q=%23%E7%A7%BB%E6%AD%A5%E5%B7%B4%E5%A1%9E%E7%9C%8B%E4%B8%AD%E5%9B%BD%23) `462.8K 🔥` `+56%`
1. [种地吧 (Farm it)](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `262.3K 🔥` `+163%`
1. [黄金白银双双快速跳水](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E5%8F%8C%E5%8F%8C%E5%BF%AB%E9%80%9F%E8%B7%B3%E6%B0%B4%23) `161.2K 🔥` `+36%`
1. [30多岁男子总觉脚冷险遭截肢](https://s.weibo.com/weibo?q=%2330%E5%A4%9A%E5%B2%81%E7%94%B7%E5%AD%90%E6%80%BB%E8%A7%89%E8%84%9A%E5%86%B7%E9%99%A9%E9%81%AD%E6%88%AA%E8%82%A2%23) `161.0K 🔥` `+78%`
1. [冯琳一巴掌费霆更是一巴掌](https://s.weibo.com/weibo?q=%23%E5%86%AF%E7%90%B3%E4%B8%80%E5%B7%B4%E6%8E%8C%E8%B4%B9%E9%9C%86%E6%9B%B4%E6%98%AF%E4%B8%80%E5%B7%B4%E6%8E%8C%23) `161.0K 🔥` `+80%`
1. [弦子报平安 (Xianzi reports peace)](https://s.weibo.com/weibo?q=%23%E5%BC%A6%E5%AD%90%E6%8A%A5%E5%B9%B3%E5%AE%89%23) `160.9K 🔥` `+38%`
1. [终于懂什么叫社交圣母症了 (I finally understand what Social Mary Syndrome is.)](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%87%82%E4%BB%80%E4%B9%88%E5%8F%AB%E7%A4%BE%E4%BA%A4%E5%9C%A3%E6%AF%8D%E7%97%87%E4%BA%86%23) `160.9K 🔥` `+92%`
1. [全国中小学新学期迎来多项新变化 (The new semester for primary and secondary schools across the country has ushered in many new changes)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E4%B8%AD%E5%B0%8F%E5%AD%A6%E6%96%B0%E5%AD%A6%E6%9C%9F%E8%BF%8E%E6%9D%A5%E5%A4%9A%E9%A1%B9%E6%96%B0%E5%8F%98%E5%8C%96%23) `160.4K 🔥` `+29%`
1. [iPhone17e浅粉色 (iPhone17e light pink)](https://s.weibo.com/weibo?q=%23iPhone17e%E6%B5%85%E7%B2%89%E8%89%B2%23) `161.4K 🔥`
1. [元宵节 (Lantern Festival)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E8%8A%82%23) `346.9K 🔥` `-57%`
1. [伊朗首都5地几乎同时爆炸 (Explosions occurred in five places in the Iranian capital almost simultaneously)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD5%E5%9C%B0%E5%87%A0%E4%B9%8E%E5%90%8C%E6%97%B6%E7%88%86%E7%82%B8%23) `161.1K 🔥` `-74%`
1. [女子带1米长巨大豆荚坐飞机引围观](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%B8%A61%E7%B1%B3%E9%95%BF%E5%B7%A8%E5%A4%A7%E8%B1%86%E8%8D%9A%E5%9D%90%E9%A3%9E%E6%9C%BA%E5%BC%95%E5%9B%B4%E8%A7%82%23) `160.7K 🔥` `-30%`

Updated at 2026-03-03 10:52:56

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
