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

1. [40岁以上常熬夜体检加做一项 (People over 40 years old who often stay up late need to do an additional physical examination)](https://s.weibo.com/weibo?q=%2340%E5%B2%81%E4%BB%A5%E4%B8%8A%E5%B8%B8%E7%86%AC%E5%A4%9C%E4%BD%93%E6%A3%80%E5%8A%A0%E5%81%9A%E4%B8%80%E9%A1%B9%23) `1.0M 🔥` `NEW`
1. [薛之谦演唱会 视角](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E6%BC%94%E5%94%B1%E4%BC%9A%20%E8%A7%86%E8%A7%92%23) `275.7K 🔥` `NEW`
1. [中国国际时装周](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%9B%BD%E9%99%85%E6%97%B6%E8%A3%85%E5%91%A8%23) `256.1K 🔥` `NEW`
1. [出差猥亵女下属研究所所长被刑拘](https://s.weibo.com/weibo?q=%23%E5%87%BA%E5%B7%AE%E7%8C%A5%E4%BA%B5%E5%A5%B3%E4%B8%8B%E5%B1%9E%E7%A0%94%E7%A9%B6%E6%89%80%E6%89%80%E9%95%BF%E8%A2%AB%E5%88%91%E6%8B%98%23) `251.3K 🔥` `NEW`
1. [第一次知道玻璃厂不能停电](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E7%9F%A5%E9%81%93%E7%8E%BB%E7%92%83%E5%8E%82%E4%B8%8D%E8%83%BD%E5%81%9C%E7%94%B5%23) `222.7K 🔥` `NEW`
1. [于东来因对下属发脾气赔40多万](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E4%B8%9C%E6%9D%A5%E5%9B%A0%E5%AF%B9%E4%B8%8B%E5%B1%9E%E5%8F%91%E8%84%BE%E6%B0%94%E8%B5%9440%E5%A4%9A%E4%B8%87%23) `195.7K 🔥` `NEW`
1. [速效救心丸最好不要贴身携带](https://s.weibo.com/weibo?q=%23%E9%80%9F%E6%95%88%E6%95%91%E5%BF%83%E4%B8%B8%E6%9C%80%E5%A5%BD%E4%B8%8D%E8%A6%81%E8%B4%B4%E8%BA%AB%E6%90%BA%E5%B8%A6%23) `195.6K 🔥` `NEW`
1. [刘晓庆亲妹妹一家希望她没有后代](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%86%E4%BA%B2%E5%A6%B9%E5%A6%B9%E4%B8%80%E5%AE%B6%E5%B8%8C%E6%9C%9B%E5%A5%B9%E6%B2%A1%E6%9C%89%E5%90%8E%E4%BB%A3%23) `175.3K 🔥` `NEW`
1. [无畏任豪双A合拍](https://s.weibo.com/weibo?q=%23%E6%97%A0%E7%95%8F%E4%BB%BB%E8%B1%AA%E5%8F%8CA%E5%90%88%E6%8B%8D%23) `170.9K 🔥` `NEW`
1. [金正恩给普京回电](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E7%BB%99%E6%99%AE%E4%BA%AC%E5%9B%9E%E7%94%B5%23) `167.3K 🔥` `NEW`
1. [偶遇纪凌尘 看来综艺里不是演的 (I met Ji Lingchen by chance. It seems that he didn’t act in a variety show.)](https://s.weibo.com/weibo?q=%23%E5%81%B6%E9%81%87%E7%BA%AA%E5%87%8C%E5%B0%98%20%E7%9C%8B%E6%9D%A5%E7%BB%BC%E8%89%BA%E9%87%8C%E4%B8%8D%E6%98%AF%E6%BC%94%E7%9A%84%23) `165.9K 🔥` `NEW`
1. [陈奕恒 身材和脸各长各的](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A5%95%E6%81%92%20%E8%BA%AB%E6%9D%90%E5%92%8C%E8%84%B8%E5%90%84%E9%95%BF%E5%90%84%E7%9A%84%23) `137.2K 🔥` `NEW`
1. [黄多多 完美继承爸妈优点](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%A4%9A%E5%A4%9A%20%E5%AE%8C%E7%BE%8E%E7%BB%A7%E6%89%BF%E7%88%B8%E5%A6%88%E4%BC%98%E7%82%B9%23) `132.9K 🔥` `NEW`
1. [如何改善慢性炎症](https://s.weibo.com/weibo?q=%23%E5%A6%82%E4%BD%95%E6%94%B9%E5%96%84%E6%85%A2%E6%80%A7%E7%82%8E%E7%97%87%23) `129.5K 🔥` `NEW`
1. [刘亦菲车内大片](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E8%BD%A6%E5%86%85%E5%A4%A7%E7%89%87%23) `129.5K 🔥` `NEW`
1. [建议心血管不好的人改一下运动时间](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%BF%83%E8%A1%80%E7%AE%A1%E4%B8%8D%E5%A5%BD%E7%9A%84%E4%BA%BA%E6%94%B9%E4%B8%80%E4%B8%8B%E8%BF%90%E5%8A%A8%E6%97%B6%E9%97%B4%23) `101.7K 🔥` `NEW`
1. [我和Angelababy居然是同一个物种](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%92%8CAngelababy%E5%B1%85%E7%84%B6%E6%98%AF%E5%90%8C%E4%B8%80%E4%B8%AA%E7%89%A9%E7%A7%8D%23) `97.6K 🔥` `NEW`
1. [心源性猝死发生时的唯一急救手段](https://s.weibo.com/weibo?q=%23%E5%BF%83%E6%BA%90%E6%80%A7%E7%8C%9D%E6%AD%BB%E5%8F%91%E7%94%9F%E6%97%B6%E7%9A%84%E5%94%AF%E4%B8%80%E6%80%A5%E6%95%91%E6%89%8B%E6%AE%B5%23) `97.5K 🔥` `NEW`
1. [董洁王橹杰演母子](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%B4%81%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%BC%94%E6%AF%8D%E5%AD%90%23) `96.6K 🔥` `NEW`
1. [金灿荣称张雪峰为社会做了不少好事](https://s.weibo.com/weibo?q=%23%E9%87%91%E7%81%BF%E8%8D%A3%E7%A7%B0%E5%BC%A0%E9%9B%AA%E5%B3%B0%E4%B8%BA%E7%A4%BE%E4%BC%9A%E5%81%9A%E4%BA%86%E4%B8%8D%E5%B0%91%E5%A5%BD%E4%BA%8B%23) `95.1K 🔥` `NEW`
1. [张婧仪 顶奢脸 (Zhang Jingyi has a luxurious face)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%A9%A7%E4%BB%AA%20%E9%A1%B6%E5%A5%A2%E8%84%B8%23) `82.9K 🔥` `NEW`
1. [向鹏赢得男队第二次选拔赛冠军](https://s.weibo.com/weibo?q=%23%E5%90%91%E9%B9%8F%E8%B5%A2%E5%BE%97%E7%94%B7%E9%98%9F%E7%AC%AC%E4%BA%8C%E6%AC%A1%E9%80%89%E6%8B%94%E8%B5%9B%E5%86%A0%E5%86%9B%23) `82.2K 🔥` `NEW`
1. [任敏回复罗伯特](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E6%95%8F%E5%9B%9E%E5%A4%8D%E7%BD%97%E4%BC%AF%E7%89%B9%23) `78.0K 🔥` `NEW`
1. [刘晓庆再发文辟谣去世](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%86%E5%86%8D%E5%8F%91%E6%96%87%E8%BE%9F%E8%B0%A3%E5%8E%BB%E4%B8%96%23) `77.8K 🔥` `NEW`
1. [男孩在废品站9元捡漏平衡车](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E5%9C%A8%E5%BA%9F%E5%93%81%E7%AB%999%E5%85%83%E6%8D%A1%E6%BC%8F%E5%B9%B3%E8%A1%A1%E8%BD%A6%23) `76.8K 🔥` `NEW`
1. [雷军一句话卖出一辆车](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E4%B8%80%E5%8F%A5%E8%AF%9D%E5%8D%96%E5%87%BA%E4%B8%80%E8%BE%86%E8%BD%A6%23) `75.8K 🔥` `NEW`
1. [TF一代出道时五代陆续出生](https://s.weibo.com/weibo?q=%23TF%E4%B8%80%E4%BB%A3%E5%87%BA%E9%81%93%E6%97%B6%E4%BA%94%E4%BB%A3%E9%99%86%E7%BB%AD%E5%87%BA%E7%94%9F%23) `73.4K 🔥` `NEW`
1. [李昀锐出发录跑男](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E5%87%BA%E5%8F%91%E5%BD%95%E8%B7%91%E7%94%B7%23) `72.5K 🔥` `NEW`
1. [特朗普的威胁七成落空了](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%9A%84%E5%A8%81%E8%83%81%E4%B8%83%E6%88%90%E8%90%BD%E7%A9%BA%E4%BA%86%23) `72.4K 🔥` `NEW`
1. [孔雪儿回应为俞宝儿挡刀](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E5%9B%9E%E5%BA%94%E4%B8%BA%E4%BF%9E%E5%AE%9D%E5%84%BF%E6%8C%A1%E5%88%80%23) `71.4K 🔥` `NEW`
1. [U23国足 泰国 (U23 National Football Team Thailand)](https://s.weibo.com/weibo?q=%23U23%E5%9B%BD%E8%B6%B3%20%E6%B3%B0%E5%9B%BD%23) `64.9K 🔥` `NEW`
1. [统一后台湾民众可以自驾直达北京](https://s.weibo.com/weibo?q=%23%E7%BB%9F%E4%B8%80%E5%90%8E%E5%8F%B0%E6%B9%BE%E6%B0%91%E4%BC%97%E5%8F%AF%E4%BB%A5%E8%87%AA%E9%A9%BE%E7%9B%B4%E8%BE%BE%E5%8C%97%E4%BA%AC%23) `764.7K 🔥` `+25%`
1. [七彩云南万千气象 (Colorful weather in Yunnan)](https://s.weibo.com/weibo?q=%23%E4%B8%83%E5%BD%A9%E4%BA%91%E5%8D%97%E4%B8%87%E5%8D%83%E6%B0%94%E8%B1%A1%23) `585.8K 🔥`
1. [华境S遭高速侧碰后坠落高坡 (Huajing S was hit by a high-speed side collision and then fell down a high slope.)](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E5%A2%83S%E9%81%AD%E9%AB%98%E9%80%9F%E4%BE%A7%E7%A2%B0%E5%90%8E%E5%9D%A0%E8%90%BD%E9%AB%98%E5%9D%A1%23) `426.3K 🔥`
1. [奔跑吧14定档 (Running Bar 14 scheduled release)](https://s.weibo.com/weibo?q=%23%E5%A5%94%E8%B7%91%E5%90%A714%E5%AE%9A%E6%A1%A3%23) `128.7K 🔥`
1. [台湾赌王身中29枪死亡5枪爆头 (Taiwan gambling king was shot 29 times and died, with 5 shots in the head)](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E8%B5%8C%E7%8E%8B%E8%BA%AB%E4%B8%AD29%E6%9E%AA%E6%AD%BB%E4%BA%A15%E6%9E%AA%E7%88%86%E5%A4%B4%23) `419.6K 🔥` `-32%`
1. [逐玉 删减](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%88%A0%E5%87%8F%23) `257.6K 🔥` `-58%`
1. [小猫不洗头为什么脑袋不臭](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E4%B8%8D%E6%B4%97%E5%A4%B4%E4%B8%BA%E4%BB%80%E4%B9%88%E8%84%91%E8%A2%8B%E4%B8%8D%E8%87%AD%23) `200.9K 🔥` `-62%`
1. [32岁产妇羊水栓塞成植物人 (32-year-old mother suffers amniotic fluid embolism and becomes vegetative)](https://s.weibo.com/weibo?q=%2332%E5%B2%81%E4%BA%A7%E5%A6%87%E7%BE%8A%E6%B0%B4%E6%A0%93%E5%A1%9E%E6%88%90%E6%A4%8D%E7%89%A9%E4%BA%BA%23) `190.6K 🔥` `-83%`
1. [于东来宣布每人退3000元 (Yu Donglai announced a refund of 3,000 yuan per person)](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E4%B8%9C%E6%9D%A5%E5%AE%A3%E5%B8%83%E6%AF%8F%E4%BA%BA%E9%80%803000%E5%85%83%23) `186.0K 🔥` `-68%`
1. [耳帝评价周杰伦新专辑](https://s.weibo.com/weibo?q=%23%E8%80%B3%E5%B8%9D%E8%AF%84%E4%BB%B7%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%23) `180.0K 🔥` `-68%`
1. [晋江 花了好多钱](https://s.weibo.com/weibo?q=%23%E6%99%8B%E6%B1%9F%20%E8%8A%B1%E4%BA%86%E5%A5%BD%E5%A4%9A%E9%92%B1%23) `179.1K 🔥` `-68%`
1. [原来迪丽热巴的20岁也难熬](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%9A%8420%E5%B2%81%E4%B9%9F%E9%9A%BE%E7%86%AC%23) `175.9K 🔥` `-47%`
1. [张晋曾因突发心脏病血管堵塞近80%](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%99%8B%E6%9B%BE%E5%9B%A0%E7%AA%81%E5%8F%91%E5%BF%83%E8%84%8F%E7%97%85%E8%A1%80%E7%AE%A1%E5%A0%B5%E5%A1%9E%E8%BF%9180%25%23) `170.4K 🔥` `-66%`
1. [王俊凯专辑概念预告 (Wang Junkai album concept trailer)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E4%B8%93%E8%BE%91%E6%A6%82%E5%BF%B5%E9%A2%84%E5%91%8A%23) `140.5K 🔥` `-75%`
1. [50岁女子同房后出血查出晚期宫颈癌](https://s.weibo.com/weibo?q=%2350%E5%B2%81%E5%A5%B3%E5%AD%90%E5%90%8C%E6%88%BF%E5%90%8E%E5%87%BA%E8%A1%80%E6%9F%A5%E5%87%BA%E6%99%9A%E6%9C%9F%E5%AE%AB%E9%A2%88%E7%99%8C%23) `137.6K 🔥` `-75%`
1. [张雪峰对女儿未来的规划与期盼 (Zhang Xuefeng’s plans and expectations for her daughter’s future)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%AF%B9%E5%A5%B3%E5%84%BF%E6%9C%AA%E6%9D%A5%E7%9A%84%E8%A7%84%E5%88%92%E4%B8%8E%E6%9C%9F%E7%9B%BC%23) `97.6K 🔥` `-83%`
1. [古偶粉底液将军101](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E5%81%B6%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B101%23) `97.6K 🔥` `-39%`
1. [周杰伦新专辑 二胎刚好三胎就烦了 (Jay Chou's new album: The second child just happens to be the third child and I'm tired of it)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%20%E4%BA%8C%E8%83%8E%E5%88%9A%E5%A5%BD%E4%B8%89%E8%83%8E%E5%B0%B1%E7%83%A6%E4%BA%86%23) `93.0K 🔥` `-30%`
1. [线下追星 拼床](https://s.weibo.com/weibo?q=%23%E7%BA%BF%E4%B8%8B%E8%BF%BD%E6%98%9F%20%E6%8B%BC%E5%BA%8A%23) `72.4K 🔥` `-36%`
1. [金价突然飙升 (Gold price surges suddenly)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E7%AA%81%E7%84%B6%E9%A3%99%E5%8D%87%23) `72.0K 🔥` `-39%`

Updated at 2026-03-25 21:09:02

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
