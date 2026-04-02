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

1. [京东加投百亿换新补贴 (JD.com invests tens of billions more in replacement subsidy)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E5%8A%A0%E6%8A%95%E7%99%BE%E4%BA%BF%E6%8D%A2%E6%96%B0%E8%A1%A5%E8%B4%B4%23) `590.6K 🔥` `NEW`
1. [张雪](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%23) `349.9K 🔥` `NEW`
1. [优思益营销策划公司被立案调查](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E8%90%A5%E9%94%80%E7%AD%96%E5%88%92%E5%85%AC%E5%8F%B8%E8%A2%AB%E7%AB%8B%E6%A1%88%E8%B0%83%E6%9F%A5%23) `314.6K 🔥` `NEW`
1. [陈光标回应张雪要卖车](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%85%89%E6%A0%87%E5%9B%9E%E5%BA%94%E5%BC%A0%E9%9B%AA%E8%A6%81%E5%8D%96%E8%BD%A6%23) `290.5K 🔥` `NEW`
1. [乘风一口气官宣34位送考人](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E%E4%B8%80%E5%8F%A3%E6%B0%94%E5%AE%98%E5%AE%A334%E4%BD%8D%E9%80%81%E8%80%83%E4%BA%BA%23) `286.2K 🔥` `NEW`
1. [金价瀑布式下跌](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E7%80%91%E5%B8%83%E5%BC%8F%E4%B8%8B%E8%B7%8C%23) `267.4K 🔥` `NEW`
1. [董宇辉曾说产品上播10天前有人试吃](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AE%87%E8%BE%89%E6%9B%BE%E8%AF%B4%E4%BA%A7%E5%93%81%E4%B8%8A%E6%92%AD10%E5%A4%A9%E5%89%8D%E6%9C%89%E4%BA%BA%E8%AF%95%E5%90%83%23) `225.1K 🔥` `NEW`
1. [胡彦斌连夜关闭了人脸支付](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%BD%A6%E6%96%8C%E8%BF%9E%E5%A4%9C%E5%85%B3%E9%97%AD%E4%BA%86%E4%BA%BA%E8%84%B8%E6%94%AF%E4%BB%98%23) `200.2K 🔥` `NEW`
1. [领克900大五座万物皆可装](https://s.weibo.com/weibo?q=%23%E9%A2%86%E5%85%8B900%E5%A4%A7%E4%BA%94%E5%BA%A7%E4%B8%87%E7%89%A9%E7%9A%86%E5%8F%AF%E8%A3%85%23) `194.1K 🔥` `NEW`
1. [田曦薇骨相清冷美](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E9%AA%A8%E7%9B%B8%E6%B8%85%E5%86%B7%E7%BE%8E%23) `193.8K 🔥` `NEW`
1. [梅姨曾多次催人贩子拐孩子 (Aunt Mei repeatedly urged traffickers to abduct children)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E6%9B%BE%E5%A4%9A%E6%AC%A1%E5%82%AC%E4%BA%BA%E8%B4%A9%E5%AD%90%E6%8B%90%E5%AD%A9%E5%AD%90%23) `193.6K 🔥` `NEW`
1. [张柏芝晒二儿子打球正脸](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9F%8F%E8%8A%9D%E6%99%92%E4%BA%8C%E5%84%BF%E5%AD%90%E6%89%93%E7%90%83%E6%AD%A3%E8%84%B8%23) `193.3K 🔥` `NEW`
1. [男孩捡50g金条咬了一口竟是真的](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E6%8D%A150g%E9%87%91%E6%9D%A1%E5%92%AC%E4%BA%86%E4%B8%80%E5%8F%A3%E7%AB%9F%E6%98%AF%E7%9C%9F%E7%9A%84%23) `192.8K 🔥` `NEW`
1. [华为旗舰标准智界V9不计成本投入](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%B8%BA%E6%97%97%E8%88%B0%E6%A0%87%E5%87%86%E6%99%BA%E7%95%8CV9%E4%B8%8D%E8%AE%A1%E6%88%90%E6%9C%AC%E6%8A%95%E5%85%A5%23) `192.5K 🔥` `NEW`
1. [汪苏泷郑州演唱会抢票](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E9%83%91%E5%B7%9E%E6%BC%94%E5%94%B1%E4%BC%9A%E6%8A%A2%E7%A5%A8%23) `186.0K 🔥` `NEW`
1. [张雪机车商标被恶意抢注](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E5%95%86%E6%A0%87%E8%A2%AB%E6%81%B6%E6%84%8F%E6%8A%A2%E6%B3%A8%23) `155.4K 🔥` `NEW`
1. [银行回应老人存10万变7万](https://s.weibo.com/weibo?q=%23%E9%93%B6%E8%A1%8C%E5%9B%9E%E5%BA%94%E8%80%81%E4%BA%BA%E5%AD%9810%E4%B8%87%E5%8F%987%E4%B8%87%23) `147.3K 🔥` `NEW`
1. [今麦郎手打擦边20年不能停产就完了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E9%BA%A6%E9%83%8E%E6%89%8B%E6%89%93%E6%93%A6%E8%BE%B920%E5%B9%B4%E4%B8%8D%E8%83%BD%E5%81%9C%E4%BA%A7%E5%B0%B1%E5%AE%8C%E4%BA%86%23) `143.1K 🔥` `NEW`
1. [王曼昱vs伊藤美诚](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1vs%E4%BC%8A%E8%97%A4%E7%BE%8E%E8%AF%9A%23) `135.0K 🔥` `NEW`
1. [正义女神](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E4%B9%89%E5%A5%B3%E7%A5%9E%23) `128.6K 🔥` `NEW`
1. [三亚一海滩露出尖锐钢筋 (Sharp steel bars exposed on a beach in Sanya)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E4%B8%80%E6%B5%B7%E6%BB%A9%E9%9C%B2%E5%87%BA%E5%B0%96%E9%94%90%E9%92%A2%E7%AD%8B%23) `127.5K 🔥` `NEW`
1. [刘晓艳网课现场没有学生一个人聊嗨了](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E8%89%B3%E7%BD%91%E8%AF%BE%E7%8E%B0%E5%9C%BA%E6%B2%A1%E6%9C%89%E5%AD%A6%E7%94%9F%E4%B8%80%E4%B8%AA%E4%BA%BA%E8%81%8A%E5%97%A8%E4%BA%86%23) `126.1K 🔥` `NEW`
1. [女入殓师三十年只为女性料理白事](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%85%A5%E6%AE%93%E5%B8%88%E4%B8%89%E5%8D%81%E5%B9%B4%E5%8F%AA%E4%B8%BA%E5%A5%B3%E6%80%A7%E6%96%99%E7%90%86%E7%99%BD%E4%BA%8B%23) `121.6K 🔥` `NEW`
1. [鞋子太臭真的会燃起来](https://s.weibo.com/weibo?q=%23%E9%9E%8B%E5%AD%90%E5%A4%AA%E8%87%AD%E7%9C%9F%E7%9A%84%E4%BC%9A%E7%87%83%E8%B5%B7%E6%9D%A5%23) `121.0K 🔥` `NEW`
1. [智界CEO官宣](https://s.weibo.com/weibo?q=%23%E6%99%BA%E7%95%8CCEO%E5%AE%98%E5%AE%A3%23) `120.5K 🔥` `NEW`
1. [说唱歌手JCole加盟CBA](https://s.weibo.com/weibo?q=%23%E8%AF%B4%E5%94%B1%E6%AD%8C%E6%89%8BJCole%E5%8A%A0%E7%9B%9FCBA%23) `117.8K 🔥` `NEW`
1. [小区花20万加装电梯只通向其中一层](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%8C%BA%E8%8A%B120%E4%B8%87%E5%8A%A0%E8%A3%85%E7%94%B5%E6%A2%AF%E5%8F%AA%E9%80%9A%E5%90%91%E5%85%B6%E4%B8%AD%E4%B8%80%E5%B1%82%23) `107.9K 🔥` `NEW`
1. [为上香港幼儿园13名家长入狱](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%B8%8A%E9%A6%99%E6%B8%AF%E5%B9%BC%E5%84%BF%E5%9B%AD13%E5%90%8D%E5%AE%B6%E9%95%BF%E5%85%A5%E7%8B%B1%23) `106.9K 🔥` `NEW`
1. [电子爸妈因亲生女儿出镜被拉黑](https://s.weibo.com/weibo?q=%23%E7%94%B5%E5%AD%90%E7%88%B8%E5%A6%88%E5%9B%A0%E4%BA%B2%E7%94%9F%E5%A5%B3%E5%84%BF%E5%87%BA%E9%95%9C%E8%A2%AB%E6%8B%89%E9%BB%91%23) `106.8K 🔥` `NEW`
1. [尹锡悦看守所内吸金12亿韩元](https://s.weibo.com/weibo?q=%23%E5%B0%B9%E9%94%A1%E6%82%A6%E7%9C%8B%E5%AE%88%E6%89%80%E5%86%85%E5%90%B8%E9%87%9112%E4%BA%BF%E9%9F%A9%E5%85%83%23) `106.8K 🔥` `NEW`
1. [优思益 (Yousiyi)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `1.1M 🔥` `+947%`
1. [怪不得上大学老了这么多 (No wonder I’ve aged so much since I went to college.)](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E4%B8%8A%E5%A4%A7%E5%AD%A6%E8%80%81%E4%BA%86%E8%BF%99%E4%B9%88%E5%A4%9A%23) `304.7K 🔥` `+114%`
1. [张雪机车夺冠含金量](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E5%A4%BA%E5%86%A0%E5%90%AB%E9%87%91%E9%87%8F%23) `285.4K 🔥` `+48%`
1. [多位明星发布优思益事件处理说明](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E4%BD%8D%E6%98%8E%E6%98%9F%E5%8F%91%E5%B8%83%E4%BC%98%E6%80%9D%E7%9B%8A%E4%BA%8B%E4%BB%B6%E5%A4%84%E7%90%86%E8%AF%B4%E6%98%8E%23) `194.4K 🔥` `+45%`
1. [严屹宽称妆造张凌赫的决策权有限](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%E7%A7%B0%E5%A6%86%E9%80%A0%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9A%84%E5%86%B3%E7%AD%96%E6%9D%83%E6%9C%89%E9%99%90%23) `116.0K 🔥` `+33%`
1. [天宫画展再上新](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E5%AE%AB%E7%94%BB%E5%B1%95%E5%86%8D%E4%B8%8A%E6%96%B0%23) `675.1K 🔥`
1. [李若彤发布致歉声明](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8B%A5%E5%BD%A4%E5%8F%91%E5%B8%83%E8%87%B4%E6%AD%89%E5%A3%B0%E6%98%8E%23) `275.5K 🔥`
1. [杨紫 没人通知我啊 (Yang Zi, no one informed me)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%20%E6%B2%A1%E4%BA%BA%E9%80%9A%E7%9F%A5%E6%88%91%E5%95%8A%23) `265.0K 🔥`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `192.3K 🔥`
1. [曝短剧男顶忘本](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%9F%AD%E5%89%A7%E7%94%B7%E9%A1%B6%E5%BF%98%E6%9C%AC%23) `187.9K 🔥`
1. [日本终于露出獠牙](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%BB%88%E4%BA%8E%E9%9C%B2%E5%87%BA%E7%8D%A0%E7%89%99%23) `804.1K 🔥` `-29%`
1. [特朗普话音刚落伊朗导弹袭向以色列](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%AF%9D%E9%9F%B3%E5%88%9A%E8%90%BD%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `294.1K 🔥` `-55%`
1. [主播陆续回应优思益售后 (Anchors responded to Yousiyi after-sales service one after another)](https://s.weibo.com/weibo?q=%23%E4%B8%BB%E6%92%AD%E9%99%86%E7%BB%AD%E5%9B%9E%E5%BA%94%E4%BC%98%E6%80%9D%E7%9B%8A%E5%94%AE%E5%90%8E%23) `162.9K 🔥` `-36%`
1. [收到了去世好友的微信回复](https://s.weibo.com/weibo?q=%23%E6%94%B6%E5%88%B0%E4%BA%86%E5%8E%BB%E4%B8%96%E5%A5%BD%E5%8F%8B%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%9B%9E%E5%A4%8D%23) `160.8K 🔥` `-46%`
1. [老爸收入不敌女儿卖拼豆直呼崩溃](https://s.weibo.com/weibo?q=%23%E8%80%81%E7%88%B8%E6%94%B6%E5%85%A5%E4%B8%8D%E6%95%8C%E5%A5%B3%E5%84%BF%E5%8D%96%E6%8B%BC%E8%B1%86%E7%9B%B4%E5%91%BC%E5%B4%A9%E6%BA%83%23) `127.8K 🔥` `-26%`
1. [王菲俞飞鸿聚餐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E4%BF%9E%E9%A3%9E%E9%B8%BF%E8%81%9A%E9%A4%90%23) `113.1K 🔥` `-35%`
1. [乘风2026](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%23) `107.9K 🔥` `-37%`
1. [疯狂动物城2预约人数近千万 (Zootopia 2 has nearly 10 million reservations)](https://s.weibo.com/weibo?q=%23%E7%96%AF%E7%8B%82%E5%8A%A8%E7%89%A9%E5%9F%8E2%E9%A2%84%E7%BA%A6%E4%BA%BA%E6%95%B0%E8%BF%91%E5%8D%83%E4%B8%87%23) `99.9K 🔥` `-46%`
1. [4个炒菜习惯或让致癌物翻倍](https://s.weibo.com/weibo?q=%234%E4%B8%AA%E7%82%92%E8%8F%9C%E4%B9%A0%E6%83%AF%E6%88%96%E8%AE%A9%E8%87%B4%E7%99%8C%E7%89%A9%E7%BF%BB%E5%80%8D%23) `96.9K 🔥` `-40%`

Updated at 2026-04-02 13:26:47

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
