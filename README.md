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

1. [中国男篮战胜日本男篮 (Chinese men's basketball team defeats Japanese men's basketball team)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE%E6%88%98%E8%83%9C%E6%97%A5%E6%9C%AC%E7%94%B7%E7%AF%AE%23) `1.2M 🔥` `NEW`
1. [日本 主场哨](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%20%E4%B8%BB%E5%9C%BA%E5%93%A8%23) `551.8K 🔥` `NEW`
1. [兔闪闪直播间](https://s.weibo.com/weibo?q=%23%E5%85%94%E9%97%AA%E9%97%AA%E7%9B%B4%E6%92%AD%E9%97%B4%23) `275.2K 🔥` `NEW`
1. [试管婴儿右足畸形官方将通报](https://s.weibo.com/weibo?q=%23%E8%AF%95%E7%AE%A1%E5%A9%B4%E5%84%BF%E5%8F%B3%E8%B6%B3%E7%95%B8%E5%BD%A2%E5%AE%98%E6%96%B9%E5%B0%86%E9%80%9A%E6%8A%A5%23) `214.5K 🔥` `NEW`
1. [赵继伟太牛了](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E7%BB%A7%E4%BC%9F%E5%A4%AA%E7%89%9B%E4%BA%86%23) `177.9K 🔥` `NEW`
1. [中国男篮反超日本](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE%E5%8F%8D%E8%B6%85%E6%97%A5%E6%9C%AC%23) `168.5K 🔥` `NEW`
1. [虞书欣红衣主母跳惊鸿一面](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E7%BA%A2%E8%A1%A3%E4%B8%BB%E6%AF%8D%E8%B7%B3%E6%83%8A%E9%B8%BF%E4%B8%80%E9%9D%A2%23) `162.2K 🔥` `NEW`
1. [郭晓婷亲孙千](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%93%E5%A9%B7%E4%BA%B2%E5%AD%99%E5%8D%83%23) `155.6K 🔥` `NEW`
1. [免去王祥喜应急管理部部长职务](https://s.weibo.com/weibo?q=%23%E5%85%8D%E5%8E%BB%E7%8E%8B%E7%A5%A5%E5%96%9C%E5%BA%94%E6%80%A5%E7%AE%A1%E7%90%86%E9%83%A8%E9%83%A8%E9%95%BF%E8%81%8C%E5%8A%A1%23) `149.5K 🔥` `NEW`
1. [文章上了澳门语文教材是什么体验](https://s.weibo.com/weibo?q=%23%E6%96%87%E7%AB%A0%E4%B8%8A%E4%BA%86%E6%BE%B3%E9%97%A8%E8%AF%AD%E6%96%87%E6%95%99%E6%9D%90%E6%98%AF%E4%BB%80%E4%B9%88%E4%BD%93%E9%AA%8C%23) `149.2K 🔥` `NEW`
1. [赖伟明被揩油 (Lai Weiming was taken advantage of)](https://s.weibo.com/weibo?q=%23%E8%B5%96%E4%BC%9F%E6%98%8E%E8%A2%AB%E6%8F%A9%E6%B2%B9%23) `144.5K 🔥` `NEW`
1. [王曼昱19比21申裕斌](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B119%E6%AF%9421%E7%94%B3%E8%A3%95%E6%96%8C%23) `136.7K 🔥` `NEW`
1. [彩礼归女方父母还是女方自己](https://s.weibo.com/weibo?q=%23%E5%BD%A9%E7%A4%BC%E5%BD%92%E5%A5%B3%E6%96%B9%E7%88%B6%E6%AF%8D%E8%BF%98%E6%98%AF%E5%A5%B3%E6%96%B9%E8%87%AA%E5%B7%B1%23) `134.8K 🔥` `NEW`
1. [霍启刚今年两会拟提8项建议](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%90%AF%E5%88%9A%E4%BB%8A%E5%B9%B4%E4%B8%A4%E4%BC%9A%E6%8B%9F%E6%8F%908%E9%A1%B9%E5%BB%BA%E8%AE%AE%23) `129.3K 🔥` `NEW`
1. [官方回应一点点资助男孩戴千元手表](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E5%9B%9E%E5%BA%94%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E6%88%B4%E5%8D%83%E5%85%83%E6%89%8B%E8%A1%A8%23) `125.1K 🔥` `NEW`
1. [王天辰 春节档最忙演员](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%20%E6%98%A5%E8%8A%82%E6%A1%A3%E6%9C%80%E5%BF%99%E6%BC%94%E5%91%98%23) `124.6K 🔥` `NEW`
1. [真正的喜欢是藏不住的爱意](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%AD%A3%E7%9A%84%E5%96%9C%E6%AC%A2%E6%98%AF%E8%97%8F%E4%B8%8D%E4%BD%8F%E7%9A%84%E7%88%B1%E6%84%8F%23) `113.0K 🔥` `NEW`
1. [赵继伟弹无虚发](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E7%BB%A7%E4%BC%9F%E5%BC%B9%E6%97%A0%E8%99%9A%E5%8F%91%23) `109.3K 🔥` `NEW`
1. [胡一菲诺澜在短国相遇了](https://s.weibo.com/weibo?q=%23%E8%83%A1%E4%B8%80%E8%8F%B2%E8%AF%BA%E6%BE%9C%E5%9C%A8%E7%9F%AD%E5%9B%BD%E7%9B%B8%E9%81%87%E4%BA%86%23) `805.0K 🔥` `+355%`
1. [上海迪士尼10岁生日](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E8%BF%AA%E5%A3%AB%E5%B0%BC10%E5%B2%81%E7%94%9F%E6%97%A5%23) `405.7K 🔥` `+79%`
1. [王曼昱黄牌 (Wang Manyu yellow card)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E9%BB%84%E7%89%8C%23) `403.1K 🔥` `+116%`
1. [中国男篮vs日本男篮](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AEvs%E6%97%A5%E6%9C%AC%E7%94%B7%E7%AF%AE%23) `331.4K 🔥` `+171%`
1. [出门和不出门过的两种人生](https://s.weibo.com/weibo?q=%23%E5%87%BA%E9%97%A8%E5%92%8C%E4%B8%8D%E5%87%BA%E9%97%A8%E8%BF%87%E7%9A%84%E4%B8%A4%E7%A7%8D%E4%BA%BA%E7%94%9F%23) `304.2K 🔥` `+27%`
1. [王一博饼干在韩国火了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E9%A5%BC%E5%B9%B2%E5%9C%A8%E9%9F%A9%E5%9B%BD%E7%81%AB%E4%BA%86%23) `279.1K 🔥` `+61%`
1. [G社拍的汪顺](https://s.weibo.com/weibo?q=%23G%E7%A4%BE%E6%8B%8D%E7%9A%84%E6%B1%AA%E9%A1%BA%23) `270.4K 🔥` `+97%`
1. [向佑不满遗产分配直喊不公平](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%91%E4%B8%8D%E6%BB%A1%E9%81%97%E4%BA%A7%E5%88%86%E9%85%8D%E7%9B%B4%E5%96%8A%E4%B8%8D%E5%85%AC%E5%B9%B3%23) `269.8K 🔥` `+122%`
1. [王橹杰手捧红玫瑰 (Wang Lujie holds red roses in hand)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%89%8B%E6%8D%A7%E7%BA%A2%E7%8E%AB%E7%91%B0%23) `266.3K 🔥` `+91%`
1. [刘亦菲最接近本人的一张图 (Liu Yifei’s closest picture to herself)](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E6%9C%80%E6%8E%A5%E8%BF%91%E6%9C%AC%E4%BA%BA%E7%9A%84%E4%B8%80%E5%BC%A0%E5%9B%BE%23) `219.5K 🔥` `+58%`
1. [王楚钦vs林德](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E6%9E%97%E5%BE%B7%23) `178.0K 🔥` `+56%`
1. [中国邮政回应已叫停相关线下活动 (China Post responded that it has suspended relevant offline activities.)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%82%AE%E6%94%BF%E5%9B%9E%E5%BA%94%E5%B7%B2%E5%8F%AB%E5%81%9C%E7%9B%B8%E5%85%B3%E7%BA%BF%E4%B8%8B%E6%B4%BB%E5%8A%A8%23) `175.8K 🔥` `+21%`
1. [曝迪丽热巴与嘉行合约到期 (It is revealed that Dilireba’s contract with Jiaxing has expired)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%B8%8E%E5%98%89%E8%A1%8C%E5%90%88%E7%BA%A6%E5%88%B0%E6%9C%9F%23) `169.9K 🔥` `+48%`
1. [霍金遗属发声 (Hawking's family speaks out)](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E9%87%91%E9%81%97%E5%B1%9E%E5%8F%91%E5%A3%B0%23) `168.2K 🔥` `+40%`
1. [薛之谦开票](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E5%BC%80%E7%A5%A8%23) `147.2K 🔥` `+22%`
1. [杨幂米兰allblack看秀 (Yang Mi Milan allblack watch show)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E7%B1%B3%E5%85%B0allblack%E7%9C%8B%E7%A7%80%23) `135.6K 🔥` `+33%`
1. [手机 涨价](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%20%E6%B6%A8%E4%BB%B7%23) `1.1M 🔥`
1. [银发经济市场规模有望达30万亿元 (The size of the silver economy market is expected to reach 30 trillion yuan)](https://s.weibo.com/weibo?q=%23%E9%93%B6%E5%8F%91%E7%BB%8F%E6%B5%8E%E5%B8%82%E5%9C%BA%E8%A7%84%E6%A8%A1%E6%9C%89%E6%9C%9B%E8%BE%BE30%E4%B8%87%E4%BA%BF%E5%85%83%23) `808.9K 🔥`
1. [日本网民称日本确实存在撞人族](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%BD%91%E6%B0%91%E7%A7%B0%E6%97%A5%E6%9C%AC%E7%A1%AE%E5%AE%9E%E5%AD%98%E5%9C%A8%E6%92%9E%E4%BA%BA%E6%97%8F%23) `281.3K 🔥`
1. [伊朗 (Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `222.6K 🔥`
1. [创造营2026女生季](https://s.weibo.com/weibo?q=%23%E5%88%9B%E9%80%A0%E8%90%A52026%E5%A5%B3%E7%94%9F%E5%AD%A3%23) `176.3K 🔥`
1. [郭富城一家去景区只用买一张票](https://s.weibo.com/weibo?q=%23%E9%83%AD%E5%AF%8C%E5%9F%8E%E4%B8%80%E5%AE%B6%E5%8E%BB%E6%99%AF%E5%8C%BA%E5%8F%AA%E7%94%A8%E4%B9%B0%E4%B8%80%E5%BC%A0%E7%A5%A8%23) `168.7K 🔥`
1. [日本把宇树机器人改成僧侣](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%8A%8A%E5%AE%87%E6%A0%91%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%94%B9%E6%88%90%E5%83%A7%E4%BE%A3%23) `135.9K 🔥`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `135.7K 🔥`
1. [迪丽热巴已成立个人独资工作室 (Dilireba has established a sole proprietorship studio)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%B7%B2%E6%88%90%E7%AB%8B%E4%B8%AA%E4%BA%BA%E7%8B%AC%E8%B5%84%E5%B7%A5%E4%BD%9C%E5%AE%A4%23) `117.2K 🔥`
1. [小S曾说田馥甄周杰伦不可能在一起](https://s.weibo.com/weibo?q=%23%E5%B0%8FS%E6%9B%BE%E8%AF%B4%E7%94%B0%E9%A6%A5%E7%94%84%E5%91%A8%E6%9D%B0%E4%BC%A6%E4%B8%8D%E5%8F%AF%E8%83%BD%E5%9C%A8%E4%B8%80%E8%B5%B7%23) `105.2K 🔥`
1. [发1.8亿年终奖公司开工3天爆单 (Company that issued 180 million year-end bonus received huge orders within 3 days of starting work)](https://s.weibo.com/weibo?q=%23%E5%8F%911.8%E4%BA%BF%E5%B9%B4%E7%BB%88%E5%A5%96%E5%85%AC%E5%8F%B8%E5%BC%80%E5%B7%A53%E5%A4%A9%E7%88%86%E5%8D%95%23) `415.6K 🔥` `-50%`
1. [一点点资助男孩被曝戴千元手表 (Little by little boy was exposed wearing a thousand-yuan watch)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E8%A2%AB%E6%9B%9D%E6%88%B4%E5%8D%83%E5%85%83%E6%89%8B%E8%A1%A8%23) `164.7K 🔥` `-26%`
1. [王曼昱vs申裕斌 (Wang Manyu vs. Shin Yubin)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1vs%E7%94%B3%E8%A3%95%E6%96%8C%23) `135.4K 🔥` `-44%`
1. [镖人 一代大蠕](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E4%B8%80%E4%BB%A3%E5%A4%A7%E8%A0%95%23) `135.3K 🔥` `-30%`
1. [欠款1000万亿当事人这次真要逾期了 (The party who owes 1000 trillion yuan is really going to be overdue this time)](https://s.weibo.com/weibo?q=%23%E6%AC%A0%E6%AC%BE1000%E4%B8%87%E4%BA%BF%E5%BD%93%E4%BA%8B%E4%BA%BA%E8%BF%99%E6%AC%A1%E7%9C%9F%E8%A6%81%E9%80%BE%E6%9C%9F%E4%BA%86%23) `134.5K 🔥` `-31%`
1. [金价波动](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%B3%A2%E5%8A%A8%23) `114.4K 🔥` `-33%`
1. [一点点资助男孩公益活动引争议](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E5%85%AC%E7%9B%8A%E6%B4%BB%E5%8A%A8%E5%BC%95%E4%BA%89%E8%AE%AE%23) `108.9K 🔥` `-38%`

Updated at 2026-02-26 20:38:31

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
