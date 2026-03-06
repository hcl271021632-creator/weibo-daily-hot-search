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

1. [开工就点拼好饭 (Just order a meal when you start working)](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E5%B0%B1%E7%82%B9%E6%8B%BC%E5%A5%BD%E9%A5%AD%23) `470.7K 🔥` `NEW`
1. [代表建议将心理筛查纳入中小学体检](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%BB%BA%E8%AE%AE%E5%B0%86%E5%BF%83%E7%90%86%E7%AD%9B%E6%9F%A5%E7%BA%B3%E5%85%A5%E4%B8%AD%E5%B0%8F%E5%AD%A6%E4%BD%93%E6%A3%80%23) `462.6K 🔥` `NEW`
1. [罗意威2026秋冬时装秀](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%84%8F%E5%A8%812026%E7%A7%8B%E5%86%AC%E6%97%B6%E8%A3%85%E7%A7%80%23) `336.1K 🔥` `NEW`
1. [外国朋友以为中国也是一人一道菜](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%9B%BD%E6%9C%8B%E5%8F%8B%E4%BB%A5%E4%B8%BA%E4%B8%AD%E5%9B%BD%E4%B9%9F%E6%98%AF%E4%B8%80%E4%BA%BA%E4%B8%80%E9%81%93%E8%8F%9C%23) `304.4K 🔥` `NEW`
1. [建议将免费教育年限扩至15年](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%86%E5%85%8D%E8%B4%B9%E6%95%99%E8%82%B2%E5%B9%B4%E9%99%90%E6%89%A9%E8%87%B315%E5%B9%B4%23) `298.1K 🔥` `NEW`
1. [建议对主动涨薪企业给予补贴](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%AF%B9%E4%B8%BB%E5%8A%A8%E6%B6%A8%E8%96%AA%E4%BC%81%E4%B8%9A%E7%BB%99%E4%BA%88%E8%A1%A5%E8%B4%B4%23) `293.3K 🔥` `NEW`
1. [建议别让家长替学校站岗](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%88%AB%E8%AE%A9%E5%AE%B6%E9%95%BF%E6%9B%BF%E5%AD%A6%E6%A0%A1%E7%AB%99%E5%B2%97%23) `282.1K 🔥` `NEW`
1. [死了么APP创始人被原公司劝离职](https://s.weibo.com/weibo?q=%23%E6%AD%BB%E4%BA%86%E4%B9%88APP%E5%88%9B%E5%A7%8B%E4%BA%BA%E8%A2%AB%E5%8E%9F%E5%85%AC%E5%8F%B8%E5%8A%9D%E7%A6%BB%E8%81%8C%23) `266.8K 🔥` `NEW`
1. [女子产后21天突发大出血晕倒车库](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%BA%A7%E5%90%8E21%E5%A4%A9%E7%AA%81%E5%8F%91%E5%A4%A7%E5%87%BA%E8%A1%80%E6%99%95%E5%80%92%E8%BD%A6%E5%BA%93%23) `237.3K 🔥` `NEW`
1. [舒适正当夏](https://s.weibo.com/weibo?q=%23%E8%88%92%E9%80%82%E6%AD%A3%E5%BD%93%E5%A4%8F%23) `200.6K 🔥` `NEW`
1. [代表建议罚没款应先赔股民 (The representative suggested that fines and forfeitures should be paid to shareholders first)](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%BB%BA%E8%AE%AE%E7%BD%9A%E6%B2%A1%E6%AC%BE%E5%BA%94%E5%85%88%E8%B5%94%E8%82%A1%E6%B0%91%23) `192.5K 🔥` `NEW`
1. [知道会动的冰箱贴受众是谁了](https://s.weibo.com/weibo?q=%23%E7%9F%A5%E9%81%93%E4%BC%9A%E5%8A%A8%E7%9A%84%E5%86%B0%E7%AE%B1%E8%B4%B4%E5%8F%97%E4%BC%97%E6%98%AF%E8%B0%81%E4%BA%86%23) `152.9K 🔥` `NEW`
1. [刘昊然宋祖儿 你透过我的眼睛在看谁](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%98%8A%E7%84%B6%E5%AE%8B%E7%A5%96%E5%84%BF%20%E4%BD%A0%E9%80%8F%E8%BF%87%E6%88%91%E7%9A%84%E7%9C%BC%E7%9D%9B%E5%9C%A8%E7%9C%8B%E8%B0%81%23) `143.1K 🔥` `NEW`
1. [十年前卖衣服方式](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%B9%B4%E5%89%8D%E5%8D%96%E8%A1%A3%E6%9C%8D%E6%96%B9%E5%BC%8F%23) `140.5K 🔥` `NEW`
1. [王安宇巴黎时装周出图](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E5%87%BA%E5%9B%BE%23) `139.3K 🔥` `NEW`
1. [不要热水洗头时梳头发](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%A6%81%E7%83%AD%E6%B0%B4%E6%B4%97%E5%A4%B4%E6%97%B6%E6%A2%B3%E5%A4%B4%E5%8F%91%23) `132.5K 🔥` `NEW`
1. [二十多年内娱只有这一个拿得出手的女警](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E5%8D%81%E5%A4%9A%E5%B9%B4%E5%86%85%E5%A8%B1%E5%8F%AA%E6%9C%89%E8%BF%99%E4%B8%80%E4%B8%AA%E6%8B%BF%E5%BE%97%E5%87%BA%E6%89%8B%E7%9A%84%E5%A5%B3%E8%AD%A6%23) `129.9K 🔥` `NEW`
1. [原神](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E7%A5%9E%23) `125.1K 🔥` `NEW`
1. [伊朗向美以发动第20波袭击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%91%E7%BE%8E%E4%BB%A5%E5%8F%91%E5%8A%A8%E7%AC%AC20%E6%B3%A2%E8%A2%AD%E5%87%BB%23) `124.7K 🔥` `NEW`
1. [建议三年级前学生课间延长至30分钟](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%89%E5%B9%B4%E7%BA%A7%E5%89%8D%E5%AD%A6%E7%94%9F%E8%AF%BE%E9%97%B4%E5%BB%B6%E9%95%BF%E8%87%B330%E5%88%86%E9%92%9F%23) `118.2K 🔥` `NEW`
1. [据报初步评估显示美军袭击伊朗学校 (Preliminary assessment reportedly shows U.S. forces attacking Iranian schools)](https://s.weibo.com/weibo?q=%23%E6%8D%AE%E6%8A%A5%E5%88%9D%E6%AD%A5%E8%AF%84%E4%BC%B0%E6%98%BE%E7%A4%BA%E7%BE%8E%E5%86%9B%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E5%AD%A6%E6%A0%A1%23) `101.6K 🔥` `NEW`
1. [詹姆斯生涯进球数历史第一](https://s.weibo.com/weibo?q=%23%E8%A9%B9%E5%A7%86%E6%96%AF%E7%94%9F%E6%B6%AF%E8%BF%9B%E7%90%83%E6%95%B0%E5%8E%86%E5%8F%B2%E7%AC%AC%E4%B8%80%23) `93.3K 🔥` `NEW`
1. [原来四个小时能干这么多事](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%9B%9B%E4%B8%AA%E5%B0%8F%E6%97%B6%E8%83%BD%E5%B9%B2%E8%BF%99%E4%B9%88%E5%A4%9A%E4%BA%8B%23) `90.8K 🔥` `NEW`
1. [田曦薇能演杀猪女李雪琴早有预言](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E8%83%BD%E6%BC%94%E6%9D%80%E7%8C%AA%E5%A5%B3%E6%9D%8E%E9%9B%AA%E7%90%B4%E6%97%A9%E6%9C%89%E9%A2%84%E8%A8%80%23) `89.1K 🔥` `NEW`
1. [逐玉 智能倍速看剧](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E6%99%BA%E8%83%BD%E5%80%8D%E9%80%9F%E7%9C%8B%E5%89%A7%23) `82.4K 🔥` `NEW`
1. [谭松韵新剧气血十足老辈子来的](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E6%96%B0%E5%89%A7%E6%B0%94%E8%A1%80%E5%8D%81%E8%B6%B3%E8%80%81%E8%BE%88%E5%AD%90%E6%9D%A5%E7%9A%84%23) `191.2K 🔥` `+86%`
1. [多地官宣春假清明连休6天 (Officials in many places announced that the Spring Festival will be closed for 6 consecutive days during Qingming Festival)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E5%AE%98%E5%AE%A3%E6%98%A5%E5%81%87%E6%B8%85%E6%98%8E%E8%BF%9E%E4%BC%916%E5%A4%A9%23) `1.1M 🔥`
1. [伊朗军队誓为遭击沉军舰复仇](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%9B%E9%98%9F%E8%AA%93%E4%B8%BA%E9%81%AD%E5%87%BB%E6%B2%89%E5%86%9B%E8%88%B0%E5%A4%8D%E4%BB%87%23) `353.9K 🔥`
1. [刘国梁高度肯定樊振东](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%9B%BD%E6%A2%81%E9%AB%98%E5%BA%A6%E8%82%AF%E5%AE%9A%E6%A8%8A%E6%8C%AF%E4%B8%9C%23) `188.6K 🔥`
1. [被骂了千年的小动物们该翻身了](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E9%AA%82%E4%BA%86%E5%8D%83%E5%B9%B4%E7%9A%84%E5%B0%8F%E5%8A%A8%E7%89%A9%E4%BB%AC%E8%AF%A5%E7%BF%BB%E8%BA%AB%E4%BA%86%23) `766.5K 🔥` `-25%`
1. [十五五规划109项重大工程项目一览](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92109%E9%A1%B9%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%E9%A1%B9%E7%9B%AE%E4%B8%80%E8%A7%88%23) `598.2K 🔥` `-38%`
1. [霸王茶姬免单 (Overlord Cha Ji free order)](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%85%8D%E5%8D%95%23) `381.7K 🔥` `-59%`
1. [伊朗外长拒绝与美国谈判](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E6%8B%92%E7%BB%9D%E4%B8%8E%E7%BE%8E%E5%9B%BD%E8%B0%88%E5%88%A4%23) `259.0K 🔥` `-54%`
1. [老舅妈嫩娘去世 (My old aunt and young lady passed away)](https://s.weibo.com/weibo?q=%23%E8%80%81%E8%88%85%E5%A6%88%E5%AB%A9%E5%A8%98%E5%8E%BB%E4%B8%96%23) `249.1K 🔥` `-50%`
1. [委内瑞拉决定同美国恢复外交关系](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E5%86%B3%E5%AE%9A%E5%90%8C%E7%BE%8E%E5%9B%BD%E6%81%A2%E5%A4%8D%E5%A4%96%E4%BA%A4%E5%85%B3%E7%B3%BB%23) `226.3K 🔥` `-63%`
1. [曝现在就出发4金晨被替换了 (It is revealed that Jin Chen has been replaced in Let’s Go Now 4)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%E9%87%91%E6%99%A8%E8%A2%AB%E6%9B%BF%E6%8D%A2%E4%BA%86%23) `223.3K 🔥` `-38%`
1. [美国24州联合起诉特朗普政府](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD24%E5%B7%9E%E8%81%94%E5%90%88%E8%B5%B7%E8%AF%89%E7%89%B9%E6%9C%97%E6%99%AE%E6%94%BF%E5%BA%9C%23) `196.1K 🔥` `-68%`
1. [蔡徐坤阳光感好绝](https://s.weibo.com/weibo?q=%23%E8%94%A1%E5%BE%90%E5%9D%A4%E9%98%B3%E5%85%89%E6%84%9F%E5%A5%BD%E7%BB%9D%23) `191.3K 🔥` `-37%`
1. [你的肉松肉紧](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E7%9A%84%E8%82%89%E6%9D%BE%E8%82%89%E7%B4%A7%23) `162.1K 🔥` `-74%`
1. [重案六组 (Serious Case Group Six)](https://s.weibo.com/weibo?q=%23%E9%87%8D%E6%A1%88%E5%85%AD%E7%BB%84%23) `146.5K 🔥` `-69%`
1. [女生800元买猫被传染全身长猫藓](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F800%E5%85%83%E4%B9%B0%E7%8C%AB%E8%A2%AB%E4%BC%A0%E6%9F%93%E5%85%A8%E8%BA%AB%E9%95%BF%E7%8C%AB%E8%97%93%23) `142.2K 🔥` `-62%`
1. [刘亦菲夏日松弛感拉满](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E5%A4%8F%E6%97%A5%E6%9D%BE%E5%BC%9B%E6%84%9F%E6%8B%89%E6%BB%A1%23) `142.1K 🔥` `-56%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `142.1K 🔥` `-53%`
1. [惠英红 叫声妈咪保你在香港风生水起](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%20%E5%8F%AB%E5%A3%B0%E5%A6%88%E5%92%AA%E4%BF%9D%E4%BD%A0%E5%9C%A8%E9%A6%99%E6%B8%AF%E9%A3%8E%E7%94%9F%E6%B0%B4%E8%B5%B7%23) `136.8K 🔥` `-58%`
1. [龚俊陆小凤造型 (Gong Jun and Lu Xiaofeng's style)](https://s.weibo.com/weibo?q=%23%E9%BE%9A%E4%BF%8A%E9%99%86%E5%B0%8F%E5%87%A4%E9%80%A0%E5%9E%8B%23) `132.1K 🔥` `-61%`
1. [十日终焉纯大男主群像](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E7%BA%AF%E5%A4%A7%E7%94%B7%E4%B8%BB%E7%BE%A4%E5%83%8F%23) `116.3K 🔥` `-27%`
1. [凤舞九天](https://s.weibo.com/weibo?q=%23%E5%87%A4%E8%88%9E%E4%B9%9D%E5%A4%A9%23) `112.0K 🔥` `-52%`
1. [逐玉追剧日历](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%BF%BD%E5%89%A7%E6%97%A5%E5%8E%86%23) `96.6K 🔥` `-33%`
1. [军费增长7%专家解读](https://s.weibo.com/weibo?q=%23%E5%86%9B%E8%B4%B9%E5%A2%9E%E9%95%BF7%25%E4%B8%93%E5%AE%B6%E8%A7%A3%E8%AF%BB%23) `88.6K 🔥` `-86%`
1. [今年首个官宣涨价的车企 (The first car company to officially announce a price increase this year)](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E9%A6%96%E4%B8%AA%E5%AE%98%E5%AE%A3%E6%B6%A8%E4%BB%B7%E7%9A%84%E8%BD%A6%E4%BC%81%23) `86.5K 🔥` `-70%`
1. [伊朗称美军林肯号航母被击中后撤](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E7%BE%8E%E5%86%9B%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%E8%A2%AB%E5%87%BB%E4%B8%AD%E5%90%8E%E6%92%A4%23) `82.6K 🔥` `-48%`

Updated at 2026-03-06 13:31:44

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
