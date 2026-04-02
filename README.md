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

1. [张雪想卖陈光标赠送豪车给嫣然捐款 (Zhang Xue wants to sell Chen Guangbiao and give a luxury car to Yanran to donate money.)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E6%83%B3%E5%8D%96%E9%99%88%E5%85%89%E6%A0%87%E8%B5%A0%E9%80%81%E8%B1%AA%E8%BD%A6%E7%BB%99%E5%AB%A3%E7%84%B6%E6%8D%90%E6%AC%BE%23) `844.2K 🔥` `NEW`
1. [天宫画展再上新](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E5%AE%AB%E7%94%BB%E5%B1%95%E5%86%8D%E4%B8%8A%E6%96%B0%23) `663.4K 🔥` `NEW`
1. [特朗普话音刚落伊朗导弹袭向以色列](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%AF%9D%E9%9F%B3%E5%88%9A%E8%90%BD%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `649.1K 🔥` `NEW`
1. [宝珠](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E7%8F%A0%23) `302.8K 🔥` `NEW`
1. [乘风2026乘风送考人](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E4%B9%98%E9%A3%8E%E9%80%81%E8%80%83%E4%BA%BA%23) `286.9K 🔥` `NEW`
1. [主播陆续回应优思益售后](https://s.weibo.com/weibo?q=%23%E4%B8%BB%E6%92%AD%E9%99%86%E7%BB%AD%E5%9B%9E%E5%BA%94%E4%BC%98%E6%80%9D%E7%9B%8A%E5%94%AE%E5%90%8E%23) `254.9K 🔥` `NEW`
1. [有线耳机被淘汰10年翻红 销量暴涨](https://s.weibo.com/weibo?q=%23%E6%9C%89%E7%BA%BF%E8%80%B3%E6%9C%BA%E8%A2%AB%E6%B7%98%E6%B1%B010%E5%B9%B4%E7%BF%BB%E7%BA%A2%20%E9%94%80%E9%87%8F%E6%9A%B4%E6%B6%A8%23) `237.2K 🔥` `NEW`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `234.8K 🔥` `NEW`
1. [李若彤发布致歉声明](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8B%A5%E5%BD%A4%E5%8F%91%E5%B8%83%E8%87%B4%E6%AD%89%E5%A3%B0%E6%98%8E%23) `232.4K 🔥` `NEW`
1. [何穗带娃看小动物](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%A9%97%E5%B8%A6%E5%A8%83%E7%9C%8B%E5%B0%8F%E5%8A%A8%E7%89%A9%23) `216.4K 🔥` `NEW`
1. [疯狂动物城2预约人数近千万 (Zootopia 2 has nearly 10 million reservations)](https://s.weibo.com/weibo?q=%23%E7%96%AF%E7%8B%82%E5%8A%A8%E7%89%A9%E5%9F%8E2%E9%A2%84%E7%BA%A6%E4%BA%BA%E6%95%B0%E8%BF%91%E5%8D%83%E4%B8%87%23) `185.1K 🔥` `NEW`
1. [美军向中东增派18架A10攻击机](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E5%90%91%E4%B8%AD%E4%B8%9C%E5%A2%9E%E6%B4%BE18%E6%9E%B6A10%E6%94%BB%E5%87%BB%E6%9C%BA%23) `176.2K 🔥` `NEW`
1. [曝短剧男顶忘本](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%9F%AD%E5%89%A7%E7%94%B7%E9%A1%B6%E5%BF%98%E6%9C%AC%23) `175.6K 🔥` `NEW`
1. [王菲俞飞鸿聚餐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E4%BF%9E%E9%A3%9E%E9%B8%BF%E8%81%9A%E9%A4%90%23) `174.2K 🔥` `NEW`
1. [老爸收入不敌女儿卖拼豆直呼崩溃](https://s.weibo.com/weibo?q=%23%E8%80%81%E7%88%B8%E6%94%B6%E5%85%A5%E4%B8%8D%E6%95%8C%E5%A5%B3%E5%84%BF%E5%8D%96%E6%8B%BC%E8%B1%86%E7%9B%B4%E5%91%BC%E5%B4%A9%E6%BA%83%23) `172.1K 🔥` `NEW`
1. [乘风2026](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%23) `171.3K 🔥` `NEW`
1. [4个炒菜习惯或让致癌物翻倍](https://s.weibo.com/weibo?q=%234%E4%B8%AA%E7%82%92%E8%8F%9C%E4%B9%A0%E6%83%AF%E6%88%96%E8%AE%A9%E8%87%B4%E7%99%8C%E7%89%A9%E7%BF%BB%E5%80%8D%23) `160.2K 🔥` `NEW`
1. [赵一鸣零食店回应不给学生发薪](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%80%E9%B8%A3%E9%9B%B6%E9%A3%9F%E5%BA%97%E5%9B%9E%E5%BA%94%E4%B8%8D%E7%BB%99%E5%AD%A6%E7%94%9F%E5%8F%91%E8%96%AA%23) `158.8K 🔥` `NEW`
1. [怪不得上大学老了这么多](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E4%B8%8A%E5%A4%A7%E5%AD%A6%E8%80%81%E4%BA%86%E8%BF%99%E4%B9%88%E5%A4%9A%23) `142.6K 🔥` `NEW`
1. [幼儿园小朋友裹被子开溜被老师抓包](https://s.weibo.com/weibo?q=%23%E5%B9%BC%E5%84%BF%E5%9B%AD%E5%B0%8F%E6%9C%8B%E5%8F%8B%E8%A3%B9%E8%A2%AB%E5%AD%90%E5%BC%80%E6%BA%9C%E8%A2%AB%E8%80%81%E5%B8%88%E6%8A%93%E5%8C%85%23) `141.5K 🔥` `NEW`
1. [侮辱赵丽颖的汪诚公开道歉 (Wang Cheng publicly apologized for insulting Zhao Liying)](https://s.weibo.com/weibo?q=%23%E4%BE%AE%E8%BE%B1%E8%B5%B5%E4%B8%BD%E9%A2%96%E7%9A%84%E6%B1%AA%E8%AF%9A%E5%85%AC%E5%BC%80%E9%81%93%E6%AD%89%23) `134.3K 🔥` `NEW`
1. [多位明星发布优思益事件处理说明](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E4%BD%8D%E6%98%8E%E6%98%9F%E5%8F%91%E5%B8%83%E4%BC%98%E6%80%9D%E7%9B%8A%E4%BA%8B%E4%BB%B6%E5%A4%84%E7%90%86%E8%AF%B4%E6%98%8E%23) `133.9K 🔥` `NEW`
1. [伊朗动用超100枚重型导弹](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8A%A8%E7%94%A8%E8%B6%85100%E6%9E%9A%E9%87%8D%E5%9E%8B%E5%AF%BC%E5%BC%B9%23) `130.0K 🔥` `NEW`
1. [女子深夜搭网约车遭摸腿性骚扰](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%B7%B1%E5%A4%9C%E6%90%AD%E7%BD%91%E7%BA%A6%E8%BD%A6%E9%81%AD%E6%91%B8%E8%85%BF%E6%80%A7%E9%AA%9A%E6%89%B0%23) `123.3K 🔥` `NEW`
1. [广东人的清明假期又要泡汤了](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E4%BA%BA%E7%9A%84%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E5%8F%88%E8%A6%81%E6%B3%A1%E6%B1%A4%E4%BA%86%23) `118.9K 🔥` `NEW`
1. [原来i人看e人是这种感觉](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5i%E4%BA%BA%E7%9C%8Be%E4%BA%BA%E6%98%AF%E8%BF%99%E7%A7%8D%E6%84%9F%E8%A7%89%23) `116.7K 🔥` `NEW`
1. [当我以为熬到5点没有影响](https://s.weibo.com/weibo?q=%23%E5%BD%93%E6%88%91%E4%BB%A5%E4%B8%BA%E7%86%AC%E5%88%B05%E7%82%B9%E6%B2%A1%E6%9C%89%E5%BD%B1%E5%93%8D%23) `114.8K 🔥` `NEW`
1. [夫妻出卖5名亲生子女被判刑](https://s.weibo.com/weibo?q=%23%E5%A4%AB%E5%A6%BB%E5%87%BA%E5%8D%965%E5%90%8D%E4%BA%B2%E7%94%9F%E5%AD%90%E5%A5%B3%E8%A2%AB%E5%88%A4%E5%88%91%23) `112.5K 🔥` `NEW`
1. [武大靖回复张雪](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E5%A4%A7%E9%9D%96%E5%9B%9E%E5%A4%8D%E5%BC%A0%E9%9B%AA%23) `111.6K 🔥` `NEW`
1. [Knight谈369发文暂别赛场](https://s.weibo.com/weibo?q=%23Knight%E8%B0%88369%E5%8F%91%E6%96%87%E6%9A%82%E5%88%AB%E8%B5%9B%E5%9C%BA%23) `109.0K 🔥` `NEW`
1. [当我想谈恋爱时 (when i want to fall in love)](https://s.weibo.com/weibo?q=%23%E5%BD%93%E6%88%91%E6%83%B3%E8%B0%88%E6%81%8B%E7%88%B1%E6%97%B6%23) `103.9K 🔥` `NEW`
1. [张凌赫新华社讲述星星的孩子](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%96%B0%E5%8D%8E%E7%A4%BE%E8%AE%B2%E8%BF%B0%E6%98%9F%E6%98%9F%E7%9A%84%E5%AD%A9%E5%AD%90%23) `99.8K 🔥` `NEW`
1. [4岁女孩买汉堡遭女子踢踹母亲发声](https://s.weibo.com/weibo?q=%234%E5%B2%81%E5%A5%B3%E5%AD%A9%E4%B9%B0%E6%B1%89%E5%A0%A1%E9%81%AD%E5%A5%B3%E5%AD%90%E8%B8%A2%E8%B8%B9%E6%AF%8D%E4%BA%B2%E5%8F%91%E5%A3%B0%23) `97.8K 🔥` `NEW`
1. [加油站开业请模特穿紧身短裙搞促销](https://s.weibo.com/weibo?q=%23%E5%8A%A0%E6%B2%B9%E7%AB%99%E5%BC%80%E4%B8%9A%E8%AF%B7%E6%A8%A1%E7%89%B9%E7%A9%BF%E7%B4%A7%E8%BA%AB%E7%9F%AD%E8%A3%99%E6%90%9E%E4%BF%83%E9%94%80%23) `96.9K 🔥` `NEW`
1. [王源演唱会天津站官宣](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BA%90%E6%BC%94%E5%94%B1%E4%BC%9A%E5%A4%A9%E6%B4%A5%E7%AB%99%E5%AE%98%E5%AE%A3%23) `92.0K 🔥` `NEW`
1. [易烊千玺素颜皮肤](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E7%B4%A0%E9%A2%9C%E7%9A%AE%E8%82%A4%23) `88.4K 🔥` `NEW`
1. [教体局回应小学要求早上6点40到校](https://s.weibo.com/weibo?q=%23%E6%95%99%E4%BD%93%E5%B1%80%E5%9B%9E%E5%BA%94%E5%B0%8F%E5%AD%A6%E8%A6%81%E6%B1%82%E6%97%A9%E4%B8%8A6%E7%82%B940%E5%88%B0%E6%A0%A1%23) `87.2K 🔥` `NEW`
1. [严屹宽称妆造张凌赫的决策权有限](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%E7%A7%B0%E5%A6%86%E9%80%A0%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9A%84%E5%86%B3%E7%AD%96%E6%9D%83%E6%9C%89%E9%99%90%23) `86.9K 🔥` `NEW`
1. [日本终于露出獠牙](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%BB%88%E4%BA%8E%E9%9C%B2%E5%87%BA%E7%8D%A0%E7%89%99%23) `1.1M 🔥` `+163%`
1. [美国TikTok禁令演不下去了吗](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BDTikTok%E7%A6%81%E4%BB%A4%E6%BC%94%E4%B8%8D%E4%B8%8B%E5%8E%BB%E4%BA%86%E5%90%97%23) `226.8K 🔥` `+84%`
1. [杨紫 没人通知我啊 (Yang Zi, no one informed me)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%20%E6%B2%A1%E4%BA%BA%E9%80%9A%E7%9F%A5%E6%88%91%E5%95%8A%23) `228.3K 🔥`
1. [张雪机车夺冠含金量](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E5%A4%BA%E5%86%A0%E5%90%AB%E9%87%91%E9%87%8F%23) `193.0K 🔥`
1. [保时捷女销售再夺一季度销冠](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E6%97%B6%E6%8D%B7%E5%A5%B3%E9%94%80%E5%94%AE%E5%86%8D%E5%A4%BA%E4%B8%80%E5%AD%A3%E5%BA%A6%E9%94%80%E5%86%A0%23) `177.3K 🔥`
1. [美国50多年来首次载人飞向月球](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD50%E5%A4%9A%E5%B9%B4%E6%9D%A5%E9%A6%96%E6%AC%A1%E8%BD%BD%E4%BA%BA%E9%A3%9E%E5%90%91%E6%9C%88%E7%90%83%23) `105.0K 🔥`
1. [收到了去世好友的微信回复](https://s.weibo.com/weibo?q=%23%E6%94%B6%E5%88%B0%E4%BA%86%E5%8E%BB%E4%B8%96%E5%A5%BD%E5%8F%8B%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%9B%9E%E5%A4%8D%23) `299.6K 🔥` `-61%`
1. [清明假期首选神州租车 (Car rental in China is the first choice during the Qingming Festival)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E9%A6%96%E9%80%89%E7%A5%9E%E5%B7%9E%E7%A7%9F%E8%BD%A6%23) `289.0K 🔥` `-41%`
1. [伊朗总统致美国人民公开信](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E8%87%B4%E7%BE%8E%E5%9B%BD%E4%BA%BA%E6%B0%91%E5%85%AC%E5%BC%80%E4%BF%A1%23) `255.8K 🔥` `-67%`
1. [王者荣耀无双](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%80%85%E8%8D%A3%E8%80%80%E6%97%A0%E5%8F%8C%23) `178.6K 🔥` `-47%`
1. [白日提灯热度](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E7%83%AD%E5%BA%A6%23) `112.0K 🔥` `-55%`
1. [与辉同行卖优思益销售额超千万 (Selling Yousiyi with Hui Peer, sales exceeding 10 million)](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E8%BE%89%E5%90%8C%E8%A1%8C%E5%8D%96%E4%BC%98%E6%80%9D%E7%9B%8A%E9%94%80%E5%94%AE%E9%A2%9D%E8%B6%85%E5%8D%83%E4%B8%87%23) `110.2K 🔥` `-87%`

Updated at 2026-04-02 11:50:42

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
