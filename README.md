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

1. [王曼昱vs申裕斌 (Wang Manyu vs. Shin Yubin)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1vs%E7%94%B3%E8%A3%95%E6%96%8C%23) `240.9K 🔥` `NEW`
1. [出门和不出门过的两种人生](https://s.weibo.com/weibo?q=%23%E5%87%BA%E9%97%A8%E5%92%8C%E4%B8%8D%E5%87%BA%E9%97%A8%E8%BF%87%E7%9A%84%E4%B8%A4%E7%A7%8D%E4%BA%BA%E7%94%9F%23) `239.9K 🔥` `NEW`
1. [创造营2026女生季](https://s.weibo.com/weibo?q=%23%E5%88%9B%E9%80%A0%E8%90%A52026%E5%A5%B3%E7%94%9F%E5%AD%A3%23) `192.9K 🔥` `NEW`
1. [王曼昱黄牌](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E9%BB%84%E7%89%8C%23) `186.4K 🔥` `NEW`
1. [胡一菲诺澜在短国相遇了](https://s.weibo.com/weibo?q=%23%E8%83%A1%E4%B8%80%E8%8F%B2%E8%AF%BA%E6%BE%9C%E5%9C%A8%E7%9F%AD%E5%9B%BD%E7%9B%B8%E9%81%87%E4%BA%86%23) `177.0K 🔥` `NEW`
1. [王一博饼干在韩国火了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E9%A5%BC%E5%B9%B2%E5%9C%A8%E9%9F%A9%E5%9B%BD%E7%81%AB%E4%BA%86%23) `173.7K 🔥` `NEW`
1. [金价波动](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%B3%A2%E5%8A%A8%23) `170.5K 🔥` `NEW`
1. [文淇一种很新的生命力穿搭](https://s.weibo.com/weibo?q=%23%E6%96%87%E6%B7%87%E4%B8%80%E7%A7%8D%E5%BE%88%E6%96%B0%E7%9A%84%E7%94%9F%E5%91%BD%E5%8A%9B%E7%A9%BF%E6%90%AD%23) `151.7K 🔥` `NEW`
1. [王艺迪3比1伊藤美诚](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%89%BA%E8%BF%AA3%E6%AF%941%E4%BC%8A%E8%97%A4%E7%BE%8E%E8%AF%9A%23) `151.0K 🔥` `NEW`
1. [郭富城一家去景区只用买一张票](https://s.weibo.com/weibo?q=%23%E9%83%AD%E5%AF%8C%E5%9F%8E%E4%B8%80%E5%AE%B6%E5%8E%BB%E6%99%AF%E5%8C%BA%E5%8F%AA%E7%94%A8%E4%B9%B0%E4%B8%80%E5%BC%A0%E7%A5%A8%23) `144.2K 🔥` `NEW`
1. [王橹杰手捧红玫瑰 (Wang Lujie holds red roses in hand)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%89%8B%E6%8D%A7%E7%BA%A2%E7%8E%AB%E7%91%B0%23) `139.3K 🔥` `NEW`
1. [G社拍的汪顺](https://s.weibo.com/weibo?q=%23G%E7%A4%BE%E6%8B%8D%E7%9A%84%E6%B1%AA%E9%A1%BA%23) `137.3K 🔥` `NEW`
1. [谷爱凌嘴里咬的到底是个啥](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%98%B4%E9%87%8C%E5%92%AC%E7%9A%84%E5%88%B0%E5%BA%95%E6%98%AF%E4%B8%AA%E5%95%A5%23) `122.9K 🔥` `NEW`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `119.1K 🔥` `NEW`
1. [登陆少年米兰直播](https://s.weibo.com/weibo?q=%23%E7%99%BB%E9%99%86%E5%B0%91%E5%B9%B4%E7%B1%B3%E5%85%B0%E7%9B%B4%E6%92%AD%23) `118.1K 🔥` `NEW`
1. [上海一彩民一口气中5注一等奖](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E4%B8%80%E5%BD%A9%E6%B0%91%E4%B8%80%E5%8F%A3%E6%B0%94%E4%B8%AD5%E6%B3%A8%E4%B8%80%E7%AD%89%E5%A5%96%23) `117.3K 🔥` `NEW`
1. [男子在汉堡店吃出疑似钢针异物](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%9C%A8%E6%B1%89%E5%A0%A1%E5%BA%97%E5%90%83%E5%87%BA%E7%96%91%E4%BC%BC%E9%92%A2%E9%92%88%E5%BC%82%E7%89%A9%23) `116.8K 🔥` `NEW`
1. [王楚钦vs林德](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E6%9E%97%E5%BE%B7%23) `114.1K 🔥` `NEW`
1. [刘宇宁角色热度破亿](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E8%A7%92%E8%89%B2%E7%83%AD%E5%BA%A6%E7%A0%B4%E4%BA%BF%23) `101.7K 🔥` `NEW`
1. [手机集体涨价的原因](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E9%9B%86%E4%BD%93%E6%B6%A8%E4%BB%B7%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `98.9K 🔥` `NEW`
1. [发1.8亿年终奖公司开工3天爆单 (Company that issued 180 million year-end bonus received huge orders within 3 days of starting work)](https://s.weibo.com/weibo?q=%23%E5%8F%911.8%E4%BA%BF%E5%B9%B4%E7%BB%88%E5%A5%96%E5%85%AC%E5%8F%B8%E5%BC%80%E5%B7%A53%E5%A4%A9%E7%88%86%E5%8D%95%23) `830.2K 🔥` `+293%`
1. [手机 涨价](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%20%E6%B6%A8%E4%BB%B7%23) `1.2M 🔥`
1. [银发经济市场规模有望达30万亿元 (The size of the silver economy market is expected to reach 30 trillion yuan)](https://s.weibo.com/weibo?q=%23%E9%93%B6%E5%8F%91%E7%BB%8F%E6%B5%8E%E5%B8%82%E5%9C%BA%E8%A7%84%E6%A8%A1%E6%9C%89%E6%9C%9B%E8%BE%BE30%E4%B8%87%E4%BA%BF%E5%85%83%23) `678.3K 🔥`
1. [美好家打造指南](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%A5%BD%E5%AE%B6%E6%89%93%E9%80%A0%E6%8C%87%E5%8D%97%23) `422.2K 🔥`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `192.3K 🔥`
1. [一点点资助男孩公益活动引争议](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E5%85%AC%E7%9B%8A%E6%B4%BB%E5%8A%A8%E5%BC%95%E4%BA%89%E8%AE%AE%23) `174.7K 🔥`
1. [坐顺风车排泄后失联男子被封号](https://s.weibo.com/weibo?q=%23%E5%9D%90%E9%A1%BA%E9%A3%8E%E8%BD%A6%E6%8E%92%E6%B3%84%E5%90%8E%E5%A4%B1%E8%81%94%E7%94%B7%E5%AD%90%E8%A2%AB%E5%B0%81%E5%8F%B7%23) `166.6K 🔥`
1. [Prada外网只认领了柳智敏](https://s.weibo.com/weibo?q=%23Prada%E5%A4%96%E7%BD%91%E5%8F%AA%E8%AE%A4%E9%A2%86%E4%BA%86%E6%9F%B3%E6%99%BA%E6%95%8F%23) `147.3K 🔥`
1. [迪丽热巴已成立个人独资工作室 (Dilireba has established a sole proprietorship studio)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%B7%B2%E6%88%90%E7%AB%8B%E4%B8%AA%E4%BA%BA%E7%8B%AC%E8%B5%84%E5%B7%A5%E4%BD%9C%E5%AE%A4%23) `140.1K 🔥`
1. [JDG对战AL](https://s.weibo.com/weibo?q=%23JDG%E5%AF%B9%E6%88%98AL%23) `139.5K 🔥`
1. [刘亦菲最接近本人的一张图 (Liu Yifei’s closest picture to herself)](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E6%9C%80%E6%8E%A5%E8%BF%91%E6%9C%AC%E4%BA%BA%E7%9A%84%E4%B8%80%E5%BC%A0%E5%9B%BE%23) `139.3K 🔥`
1. [向佑不满遗产分配直喊不公平](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%91%E4%B8%8D%E6%BB%A1%E9%81%97%E4%BA%A7%E5%88%86%E9%85%8D%E7%9B%B4%E5%96%8A%E4%B8%8D%E5%85%AC%E5%B9%B3%23) `121.6K 🔥`
1. [霍金遗属发声 (Hawking's family speaks out)](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E9%87%91%E9%81%97%E5%B1%9E%E5%8F%91%E5%A3%B0%23) `120.4K 🔥`
1. [郭富城三岁的时候岳父出生了](https://s.weibo.com/weibo?q=%23%E9%83%AD%E5%AF%8C%E5%9F%8E%E4%B8%89%E5%B2%81%E7%9A%84%E6%97%B6%E5%80%99%E5%B2%B3%E7%88%B6%E5%87%BA%E7%94%9F%E4%BA%86%23) `119.7K 🔥`
1. [女教师因调皮男生怕开学暴瘦10多斤 (Female teacher lost more than 10 pounds because naughty boys were afraid of starting school)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E6%95%99%E5%B8%88%E5%9B%A0%E8%B0%83%E7%9A%AE%E7%94%B7%E7%94%9F%E6%80%95%E5%BC%80%E5%AD%A6%E6%9A%B4%E7%98%A610%E5%A4%9A%E6%96%A4%23) `118.7K 🔥`
1. [曝迪丽热巴与嘉行合约到期 (It is revealed that Dilireba’s contract with Jiaxing has expired)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%B8%8E%E5%98%89%E8%A1%8C%E5%90%88%E7%BA%A6%E5%88%B0%E6%9C%9F%23) `114.8K 🔥`
1. [小S曾说田馥甄周杰伦不可能在一起](https://s.weibo.com/weibo?q=%23%E5%B0%8FS%E6%9B%BE%E8%AF%B4%E7%94%B0%E9%A6%A5%E7%94%84%E5%91%A8%E6%9D%B0%E4%BC%A6%E4%B8%8D%E5%8F%AF%E8%83%BD%E5%9C%A8%E4%B8%80%E8%B5%B7%23) `109.8K 🔥`
1. [日本网民称日本确实存在撞人族](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%BD%91%E6%B0%91%E7%A7%B0%E6%97%A5%E6%9C%AC%E7%A1%AE%E5%AE%9E%E5%AD%98%E5%9C%A8%E6%92%9E%E4%BA%BA%E6%97%8F%23) `244.2K 🔥` `-71%`
1. [上海迪士尼10岁生日](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E8%BF%AA%E5%A3%AB%E5%B0%BC10%E5%B2%81%E7%94%9F%E6%97%A5%23) `227.1K 🔥` `-32%`
1. [一点点资助男孩被曝戴千元手表 (Little by little boy was exposed wearing a thousand-yuan watch)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E8%A2%AB%E6%9B%9D%E6%88%B4%E5%8D%83%E5%85%83%E6%89%8B%E8%A1%A8%23) `223.7K 🔥` `-30%`
1. [欠款1000万亿当事人这次真要逾期了 (The party who owes 1000 trillion yuan is really going to be overdue this time)](https://s.weibo.com/weibo?q=%23%E6%AC%A0%E6%AC%BE1000%E4%B8%87%E4%BA%BF%E5%BD%93%E4%BA%8B%E4%BA%BA%E8%BF%99%E6%AC%A1%E7%9C%9F%E8%A6%81%E9%80%BE%E6%9C%9F%E4%BA%86%23) `195.7K 🔥` `-30%`
1. [镖人 一代大蠕](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E4%B8%80%E4%BB%A3%E5%A4%A7%E8%A0%95%23) `192.9K 🔥` `-29%`
1. [爱泼斯坦私密储物柜曝光](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%B3%BC%E6%96%AF%E5%9D%A6%E7%A7%81%E5%AF%86%E5%82%A8%E7%89%A9%E6%9F%9C%E6%9B%9D%E5%85%89%23) `154.0K 🔥` `-33%`
1. [中国邮政回应已叫停相关线下活动 (China Post responded that it has suspended relevant offline activities.)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%82%AE%E6%94%BF%E5%9B%9E%E5%BA%94%E5%B7%B2%E5%8F%AB%E5%81%9C%E7%9B%B8%E5%85%B3%E7%BA%BF%E4%B8%8B%E6%B4%BB%E5%8A%A8%23) `145.2K 🔥` `-64%`
1. [日本把宇树机器人改成僧侣](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%8A%8A%E5%AE%87%E6%A0%91%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%94%B9%E6%88%90%E5%83%A7%E4%BE%A3%23) `123.0K 🔥` `-36%`
1. [中国男篮vs日本男篮](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AEvs%E6%97%A5%E6%9C%AC%E7%94%B7%E7%AF%AE%23) `122.1K 🔥` `-50%`
1. [薛之谦开票](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E5%BC%80%E7%A5%A8%23) `121.2K 🔥` `-57%`
1. [林俊杰作曲方文山作词](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E4%BD%9C%E6%9B%B2%E6%96%B9%E6%96%87%E5%B1%B1%E4%BD%9C%E8%AF%8D%23) `115.9K 🔥` `-41%`
1. [160万江景房被父母堆成废品站 (The 1.6 million river view house was piled into a scrapyard by parents)](https://s.weibo.com/weibo?q=%23160%E4%B8%87%E6%B1%9F%E6%99%AF%E6%88%BF%E8%A2%AB%E7%88%B6%E6%AF%8D%E5%A0%86%E6%88%90%E5%BA%9F%E5%93%81%E7%AB%99%23) `102.7K 🔥` `-61%`
1. [杨幂米兰allblack看秀 (Yang Mi Milan allblack watch show)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E7%B1%B3%E5%85%B0allblack%E7%9C%8B%E7%A7%80%23) `101.9K 🔥` `-21%`
1. [女孩给妈妈买金手链反被指责爆哭](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E7%BB%99%E5%A6%88%E5%A6%88%E4%B9%B0%E9%87%91%E6%89%8B%E9%93%BE%E5%8F%8D%E8%A2%AB%E6%8C%87%E8%B4%A3%E7%88%86%E5%93%AD%23) `99.1K 🔥` `-22%`

Updated at 2026-02-26 19:50:48

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
