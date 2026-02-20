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

1. [7名中国游客沉入贝加尔湖溺亡 (7 Chinese tourists sink into Lake Baikal and drown)](https://s.weibo.com/weibo?q=%237%E5%90%8D%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E6%B2%89%E5%85%A5%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E6%BA%BA%E4%BA%A1%23) `2.0M 🔥` `NEW`
1. [全世界为什么只有中国人吃炒菜](https://s.weibo.com/weibo?q=%23%E5%85%A8%E4%B8%96%E7%95%8C%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%AA%E6%9C%89%E4%B8%AD%E5%9B%BD%E4%BA%BA%E5%90%83%E7%82%92%E8%8F%9C%23) `220.3K 🔥` `NEW`
1. [为什么美人计使用率如此之高](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E7%BE%8E%E4%BA%BA%E8%AE%A1%E4%BD%BF%E7%94%A8%E7%8E%87%E5%A6%82%E6%AD%A4%E4%B9%8B%E9%AB%98%23) `208.8K 🔥` `NEW`
1. [所有东西都必须支付两次](https://s.weibo.com/weibo?q=%23%E6%89%80%E6%9C%89%E4%B8%9C%E8%A5%BF%E9%83%BD%E5%BF%85%E9%A1%BB%E6%94%AF%E4%BB%98%E4%B8%A4%E6%AC%A1%23) `205.7K 🔥` `NEW`
1. [火锅店春节4天赚33.9万全给员工](https://s.weibo.com/weibo?q=%23%E7%81%AB%E9%94%85%E5%BA%97%E6%98%A5%E8%8A%824%E5%A4%A9%E8%B5%9A33.9%E4%B8%87%E5%85%A8%E7%BB%99%E5%91%98%E5%B7%A5%23) `124.1K 🔥` `NEW`
1. [日本货船游船相撞多人死伤](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E8%B4%A7%E8%88%B9%E6%B8%B8%E8%88%B9%E7%9B%B8%E6%92%9E%E5%A4%9A%E4%BA%BA%E6%AD%BB%E4%BC%A4%23) `123.8K 🔥` `NEW`
1. [虞书欣何与双人拍立得](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%BD%95%E4%B8%8E%E5%8F%8C%E4%BA%BA%E6%8B%8D%E7%AB%8B%E5%BE%97%23) `121.1K 🔥` `NEW`
1. [拾石村暗箱操作到妈祖头上了](https://s.weibo.com/weibo?q=%23%E6%8B%BE%E7%9F%B3%E6%9D%91%E6%9A%97%E7%AE%B1%E6%93%8D%E4%BD%9C%E5%88%B0%E5%A6%88%E7%A5%96%E5%A4%B4%E4%B8%8A%E4%BA%86%23) `109.5K 🔥` `NEW`
1. [易烊千玺是有点演技症在身上](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E6%98%AF%E6%9C%89%E7%82%B9%E6%BC%94%E6%8A%80%E7%97%87%E5%9C%A8%E8%BA%AB%E4%B8%8A%23) `102.7K 🔥` `NEW`
1. [宋威龙你顶着这张脸四肢爬行啊](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%A8%81%E9%BE%99%E4%BD%A0%E9%A1%B6%E7%9D%80%E8%BF%99%E5%BC%A0%E8%84%B8%E5%9B%9B%E8%82%A2%E7%88%AC%E8%A1%8C%E5%95%8A%23) `98.6K 🔥` `NEW`
1. [大年初五有啥习俗 (What are the customs on the fifth day of the Lunar New Year?)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%94%E6%9C%89%E5%95%A5%E4%B9%A0%E4%BF%97%23) `97.7K 🔥` `NEW`
1. [酒店咖啡机洗内裤](https://s.weibo.com/weibo?q=%23%E9%85%92%E5%BA%97%E5%92%96%E5%95%A1%E6%9C%BA%E6%B4%97%E5%86%85%E8%A3%A4%23) `94.7K 🔥` `NEW`
1. [人人人人人天坛人人人人人](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E4%BA%BA%E4%BA%BA%E4%BA%BA%E4%BA%BA%E5%A4%A9%E5%9D%9B%E4%BA%BA%E4%BA%BA%E4%BA%BA%E4%BA%BA%E4%BA%BA%23) `94.1K 🔥` `NEW`
1. [韩国向日本提出强烈抗议](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E5%90%91%E6%97%A5%E6%9C%AC%E6%8F%90%E5%87%BA%E5%BC%BA%E7%83%88%E6%8A%97%E8%AE%AE%23) `86.9K 🔥` `NEW`
1. [李天马第二跳127.50分](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%A4%A9%E9%A9%AC%E7%AC%AC%E4%BA%8C%E8%B7%B3127.50%E5%88%86%23) `80.3K 🔥` `NEW`
1. [贝加尔湖一个月内2起涉中安全事故](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E4%B8%80%E4%B8%AA%E6%9C%88%E5%86%852%E8%B5%B7%E6%B6%89%E4%B8%AD%E5%AE%89%E5%85%A8%E4%BA%8B%E6%95%85%23) `75.5K 🔥` `NEW`
1. [贝加尔湖 冰面行驶](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%20%E5%86%B0%E9%9D%A2%E8%A1%8C%E9%A9%B6%23) `71.6K 🔥` `NEW`
1. [将门独后 天崩开局 (The only queen in the sect will start with Heavenly Collapse)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%20%E5%A4%A9%E5%B4%A9%E5%BC%80%E5%B1%80%23) `948.9K 🔥` `+73%`
1. [每一位中国冰雪健儿都闪闪发光 (Every Chinese ice and snow athlete shines brightly)](https://s.weibo.com/weibo?q=%23%E6%AF%8F%E4%B8%80%E4%BD%8D%E4%B8%AD%E5%9B%BD%E5%86%B0%E9%9B%AA%E5%81%A5%E5%84%BF%E9%83%BD%E9%97%AA%E9%97%AA%E5%8F%91%E5%85%89%23) `790.0K 🔥` `+27%`
1. [杨幂带火吊带条纹长裙](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E5%B8%A6%E7%81%AB%E5%90%8A%E5%B8%A6%E6%9D%A1%E7%BA%B9%E9%95%BF%E8%A3%99%23) `227.1K 🔥` `+67%`
1. [陈雪凝回应在婚礼上唱歌](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%9B%AA%E5%87%9D%E5%9B%9E%E5%BA%94%E5%9C%A8%E5%A9%9A%E7%A4%BC%E4%B8%8A%E5%94%B1%E6%AD%8C%23) `166.3K 🔥` `+25%`
1. [王鹤棣观众盘 (Wang Hedi audience plate)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E8%A7%82%E4%BC%97%E7%9B%98%23) `165.6K 🔥` `+24%`
1. [第一集就看到黄景瑜腹肌 (In the first episode, we saw Huang Jingyu’s abdominal muscles)](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E9%9B%86%E5%B0%B1%E7%9C%8B%E5%88%B0%E9%BB%84%E6%99%AF%E7%91%9C%E8%85%B9%E8%82%8C%23) `121.6K 🔥` `+40%`
1. [妈祖换人 (Mazu substitution)](https://s.weibo.com/weibo?q=%23%E5%A6%88%E7%A5%96%E6%8D%A2%E4%BA%BA%23) `7.4M 🔥`
1. [镖人票房排名第二](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E6%8E%92%E5%90%8D%E7%AC%AC%E4%BA%8C%23) `323.3K 🔥`
1. [TF四代五练结束了 (TF fourth generation and fifth training is over)](https://s.weibo.com/weibo?q=%23TF%E5%9B%9B%E4%BB%A3%E4%BA%94%E7%BB%83%E7%BB%93%E6%9D%9F%E4%BA%86%23) `145.8K 🔥`
1. [广东地震 (Guangdong earthquake)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E5%9C%B0%E9%9C%87%23) `127.2K 🔥`
1. [日本冰壶美女撞脸孙燕姿 (Japanese curling beauty bumps into Stefanie Sun)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%86%B0%E5%A3%B6%E7%BE%8E%E5%A5%B3%E6%92%9E%E8%84%B8%E5%AD%99%E7%87%95%E5%A7%BF%23) `126.8K 🔥`
1. [男子用AI鉴定玉石8个月收入上百万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%94%A8AI%E9%89%B4%E5%AE%9A%E7%8E%89%E7%9F%B38%E4%B8%AA%E6%9C%88%E6%94%B6%E5%85%A5%E4%B8%8A%E7%99%BE%E4%B8%87%23) `125.0K 🔥`
1. [初中生扶人被索赔22万摔倒老人发声](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%AD%E7%94%9F%E6%89%B6%E4%BA%BA%E8%A2%AB%E7%B4%A2%E8%B5%9422%E4%B8%87%E6%91%94%E5%80%92%E8%80%81%E4%BA%BA%E5%8F%91%E5%A3%B0%23) `123.3K 🔥`
1. [吴佳尼自曝离婚原因 (Wu Jiani reveals the reason for divorce)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%B3%E5%B0%BC%E8%87%AA%E6%9B%9D%E7%A6%BB%E5%A9%9A%E5%8E%9F%E5%9B%A0%23) `122.7K 🔥`
1. [女子在洗浴中心浴池门口被人录像](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%9C%A8%E6%B4%97%E6%B5%B4%E4%B8%AD%E5%BF%83%E6%B5%B4%E6%B1%A0%E9%97%A8%E5%8F%A3%E8%A2%AB%E4%BA%BA%E5%BD%95%E5%83%8F%23) `122.0K 🔥`
1. [确实型人格](https://s.weibo.com/weibo?q=%23%E7%A1%AE%E5%AE%9E%E5%9E%8B%E4%BA%BA%E6%A0%BC%23) `118.3K 🔥`
1. [张函瑞抽抽乐](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%BD%E7%91%9E%E6%8A%BD%E6%8A%BD%E4%B9%90%23) `114.2K 🔥`
1. [特朗普赞中国仪仗队](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%B5%9E%E4%B8%AD%E5%9B%BD%E4%BB%AA%E4%BB%97%E9%98%9F%23) `105.4K 🔥`
1. [情绪稳定的一家人有多重要](https://s.weibo.com/weibo?q=%23%E6%83%85%E7%BB%AA%E7%A8%B3%E5%AE%9A%E7%9A%84%E4%B8%80%E5%AE%B6%E4%BA%BA%E6%9C%89%E5%A4%9A%E9%87%8D%E8%A6%81%23) `97.8K 🔥`
1. [惊蛰无声](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `88.3K 🔥`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `83.6K 🔥`
1. [胡先煦cos胡先煦](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%85%88%E7%85%A6cos%E8%83%A1%E5%85%88%E7%85%A6%23) `79.1K 🔥`
1. [王腾回应换iPhone17 (Wang Teng responded to switching to iPhone 17)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%85%BE%E5%9B%9E%E5%BA%94%E6%8D%A2iPhone17%23) `75.4K 🔥`
1. [一载有8人汽车在贝加尔湖沉没 (Car with 8 people on board sinks in Lake Baikal)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%BD%BD%E6%9C%898%E4%BA%BA%E6%B1%BD%E8%BD%A6%E5%9C%A8%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E6%B2%89%E6%B2%A1%23) `365.4K 🔥` `-66%`
1. [谷爱凌赌上职业生涯的一跳](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%B5%8C%E4%B8%8A%E8%81%8C%E4%B8%9A%E7%94%9F%E6%B6%AF%E7%9A%84%E4%B8%80%E8%B7%B3%23) `197.3K 🔥` `-75%`
1. [贝加尔湖](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%23) `175.0K 🔥` `-68%`
1. [妈祖 掷圣杯](https://s.weibo.com/weibo?q=%23%E5%A6%88%E7%A5%96%20%E6%8E%B7%E5%9C%A3%E6%9D%AF%23) `166.1K 🔥` `-70%`
1. [吴京 我的夫人姓谢 (Wu Jing My wife’s surname is Xie)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E6%88%91%E7%9A%84%E5%A4%AB%E4%BA%BA%E5%A7%93%E8%B0%A2%23) `100.4K 🔥` `-24%`
1. [女子买20元奶茶中奖黄金约25000元](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%B020%E5%85%83%E5%A5%B6%E8%8C%B6%E4%B8%AD%E5%A5%96%E9%BB%84%E9%87%91%E7%BA%A625000%E5%85%83%23) `98.9K 🔥` `-27%`
1. [将门毒后书粉](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%E4%B9%A6%E7%B2%89%23) `91.4K 🔥` `-32%`
1. [曝网红鹿哈师徒恋](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%BD%91%E7%BA%A2%E9%B9%BF%E5%93%88%E5%B8%88%E5%BE%92%E6%81%8B%23) `83.2K 🔥` `-33%`
1. [星期五练习生 (Friday trainee)](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%9C%9F%E4%BA%94%E7%BB%83%E4%B9%A0%E7%94%9F%23) `77.2K 🔥` `-43%`
1. [香港63岁男子为救猫坠亡](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF63%E5%B2%81%E7%94%B7%E5%AD%90%E4%B8%BA%E6%95%91%E7%8C%AB%E5%9D%A0%E4%BA%A1%23) `75.9K 🔥` `-21%`

Updated at 2026-02-20 20:25:15

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
