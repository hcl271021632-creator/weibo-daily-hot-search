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

1. [接李琰事业运 (Receive Li Yan’s career fortune)](https://s.weibo.com/weibo?q=%23%E6%8E%A5%E6%9D%8E%E7%90%B0%E4%BA%8B%E4%B8%9A%E8%BF%90%23) `175.5K 🔥` `NEW`
1. [宁忠岩说滑疯了](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E8%AF%B4%E6%BB%91%E7%96%AF%E4%BA%86%23) `94.9K 🔥` `NEW`
1. [宁忠岩没吹牛](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E6%B2%A1%E5%90%B9%E7%89%9B%23) `45.0K 🔥` `NEW`
1. [没有杨紫这条线就没有生命树](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E6%9C%89%E6%9D%A8%E7%B4%AB%E8%BF%99%E6%9D%A1%E7%BA%BF%E5%B0%B1%E6%B2%A1%E6%9C%89%E7%94%9F%E5%91%BD%E6%A0%91%23) `37.6K 🔥` `NEW`
1. [大量美军海空力量在中东地区集结](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E9%87%8F%E7%BE%8E%E5%86%9B%E6%B5%B7%E7%A9%BA%E5%8A%9B%E9%87%8F%E5%9C%A8%E4%B8%AD%E4%B8%9C%E5%9C%B0%E5%8C%BA%E9%9B%86%E7%BB%93%23) `34.7K 🔥` `NEW`
1. [奇迹男孩宁忠岩](https://s.weibo.com/weibo?q=%23%E5%A5%87%E8%BF%B9%E7%94%B7%E5%AD%A9%E5%AE%81%E5%BF%A0%E5%B2%A9%23) `29.0K 🔥` `NEW`
1. [镖人细节](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%BB%86%E8%8A%82%23) `28.4K 🔥` `NEW`
1. [宁忠岩身披国旗哭了](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E8%BA%AB%E6%8A%AB%E5%9B%BD%E6%97%97%E5%93%AD%E4%BA%86%23) `26.7K 🔥` `NEW`
1. [宁忠岩创造历史](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E5%88%9B%E9%80%A0%E5%8E%86%E5%8F%B2%23) `25.9K 🔥` `NEW`
1. [觉得自己闯祸的可以看看美国四人雪车](https://s.weibo.com/weibo?q=%23%E8%A7%89%E5%BE%97%E8%87%AA%E5%B7%B1%E9%97%AF%E7%A5%B8%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%9C%8B%E7%9C%8B%E7%BE%8E%E5%9B%BD%E5%9B%9B%E4%BA%BA%E9%9B%AA%E8%BD%A6%23) `92.6K 🔥` `+84%`
1. [宁忠岩 圆月弯刀斩落紫微星 (Ning Zhongyan's full moon scimitar cuts off the purple star)](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%20%E5%9C%86%E6%9C%88%E5%BC%AF%E5%88%80%E6%96%A9%E8%90%BD%E7%B4%AB%E5%BE%AE%E6%98%9F%23) `251.7K 🔥`
1. [宁忠岩李琰拥抱](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E6%9D%8E%E7%90%B0%E6%8B%A5%E6%8A%B1%23) `129.4K 🔥`
1. [宁忠岩金牌 (Ning Zhongyan gold medal)](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E9%87%91%E7%89%8C%23) `1.2M 🔥` `-63%`
1. [他们在天山脚下脚踏冰河巡边](https://s.weibo.com/weibo?q=%23%E4%BB%96%E4%BB%AC%E5%9C%A8%E5%A4%A9%E5%B1%B1%E8%84%9A%E4%B8%8B%E8%84%9A%E8%B8%8F%E5%86%B0%E6%B2%B3%E5%B7%A1%E8%BE%B9%23) `210.3K 🔥` `-62%`
1. [宁忠岩打破奥运纪录](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E6%89%93%E7%A0%B4%E5%A5%A5%E8%BF%90%E7%BA%AA%E5%BD%95%23) `177.0K 🔥` `-81%`
1. [谢景行 (Xie Jingxing)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E6%99%AF%E8%A1%8C%23) `147.2K 🔥` `-58%`
1. [宁忠岩飞起来了](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E9%A3%9E%E8%B5%B7%E6%9D%A5%E4%BA%86%23) `97.0K 🔥` `-42%`
1. [刘德华解冻失败 (Andy Lau failed to unfreeze)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BE%B7%E5%8D%8E%E8%A7%A3%E5%86%BB%E5%A4%B1%E8%B4%A5%23) `89.2K 🔥` `-26%`
1. [美军力量被曝正快速集结](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E5%8A%9B%E9%87%8F%E8%A2%AB%E6%9B%9D%E6%AD%A3%E5%BF%AB%E9%80%9F%E9%9B%86%E7%BB%93%23) `79.9K 🔥` `-58%`
1. [王鹤棣孟子义 将门独后](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AD%9F%E5%AD%90%E4%B9%89%20%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `72.7K 🔥` `-33%`
1. [酷滕 雷淞然](https://s.weibo.com/weibo?q=%23%E9%85%B7%E6%BB%95%20%E9%9B%B7%E6%B7%9E%E7%84%B6%23) `66.2K 🔥` `-39%`
1. [于奥点赞](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E5%A5%A5%E7%82%B9%E8%B5%9E%23) `62.9K 🔥` `-47%`
1. [中国队米兰冬奥第3金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E7%AC%AC3%E9%87%91%23) `60.2K 🔥` `-61%`
1. [人的心气是能重新养回来的 (A person's heart energy can be restored again)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%9A%84%E5%BF%83%E6%B0%94%E6%98%AF%E8%83%BD%E9%87%8D%E6%96%B0%E5%85%BB%E5%9B%9E%E6%9D%A5%E7%9A%84%23) `60.1K 🔥` `-50%`
1. [镖人票房逆跌](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E9%80%86%E8%B7%8C%23) `54.4K 🔥` `-26%`
1. [谭凯回应没戏拍回青岛开饺子店 (Tan Kai responded that he had no chance to film and returned to Qingdao to open a dumpling shop)](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E5%87%AF%E5%9B%9E%E5%BA%94%E6%B2%A1%E6%88%8F%E6%8B%8D%E5%9B%9E%E9%9D%92%E5%B2%9B%E5%BC%80%E9%A5%BA%E5%AD%90%E5%BA%97%23) `52.7K 🔥` `-54%`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `46.8K 🔥` `-32%`
1. [浙江一地即日起禁售烟花爆竹](https://s.weibo.com/weibo?q=%23%E6%B5%99%E6%B1%9F%E4%B8%80%E5%9C%B0%E5%8D%B3%E6%97%A5%E8%B5%B7%E7%A6%81%E5%94%AE%E7%83%9F%E8%8A%B1%E7%88%86%E7%AB%B9%23) `44.3K 🔥` `-62%`
1. [杨幂开车都能出神图](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E5%BC%80%E8%BD%A6%E9%83%BD%E8%83%BD%E5%87%BA%E7%A5%9E%E5%9B%BE%23) `43.4K 🔥` `-36%`
1. [妈妈让上交2万压岁钱孩子不干了](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E8%AE%A9%E4%B8%8A%E4%BA%A42%E4%B8%87%E5%8E%8B%E5%B2%81%E9%92%B1%E5%AD%A9%E5%AD%90%E4%B8%8D%E5%B9%B2%E4%BA%86%23) `42.7K 🔥` `-26%`
1. [穆祉丞 没人打扰的感觉太爽了](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%20%E6%B2%A1%E4%BA%BA%E6%89%93%E6%89%B0%E7%9A%84%E6%84%9F%E8%A7%89%E5%A4%AA%E7%88%BD%E4%BA%86%23) `39.5K 🔥` `-49%`
1. [电影镖人口碑](https://s.weibo.com/weibo?q=%23%E7%94%B5%E5%BD%B1%E9%95%96%E4%BA%BA%E5%8F%A3%E7%A2%91%23) `37.7K 🔥` `-29%`
1. [大年初四](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E5%9B%9B%23) `37.2K 🔥` `-45%`
1. [郭晶晶霍启刚做马蹄糕拜年](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%B6%E6%99%B6%E9%9C%8D%E5%90%AF%E5%88%9A%E5%81%9A%E9%A9%AC%E8%B9%84%E7%B3%95%E6%8B%9C%E5%B9%B4%23) `35.7K 🔥` `-53%`
1. [将门独后官宣节奏 (The official announcement of the rhythm of being the only queen in the general family)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%AE%98%E5%AE%A3%E8%8A%82%E5%A5%8F%23) `35.6K 🔥` `-39%`
1. [特朗普称对台军售要跟中国商量 (Trump says arms sales to Taiwan must be discussed with China)](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E5%AF%B9%E5%8F%B0%E5%86%9B%E5%94%AE%E8%A6%81%E8%B7%9F%E4%B8%AD%E5%9B%BD%E5%95%86%E9%87%8F%23) `33.0K 🔥` `-53%`
1. [白鹿代露娃二搭疯批对疯批](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E4%BB%A3%E9%9C%B2%E5%A8%83%E4%BA%8C%E6%90%AD%E7%96%AF%E6%89%B9%E5%AF%B9%E7%96%AF%E6%89%B9%23) `33.0K 🔥` `-58%`
1. [网剧双轨](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%89%A7%E5%8F%8C%E8%BD%A8%23) `32.5K 🔥` `-46%`
1. [范丞丞主演电影票房破70亿](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E4%B8%BB%E6%BC%94%E7%94%B5%E5%BD%B1%E7%A5%A8%E6%88%BF%E7%A0%B470%E4%BA%BF%23) `31.0K 🔥` `-41%`
1. [苏翊鸣采访时徐梦桃打来电话](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E9%87%87%E8%AE%BF%E6%97%B6%E5%BE%90%E6%A2%A6%E6%A1%83%E6%89%93%E6%9D%A5%E7%94%B5%E8%AF%9D%23) `30.0K 🔥` `-49%`
1. [形象的演示了什么叫命里有财](https://s.weibo.com/weibo?q=%23%E5%BD%A2%E8%B1%A1%E7%9A%84%E6%BC%94%E7%A4%BA%E4%BA%86%E4%BB%80%E4%B9%88%E5%8F%AB%E5%91%BD%E9%87%8C%E6%9C%89%E8%B4%A2%23) `28.3K 🔥` `-52%`
1. [陈丽君 现代女演员里少见的英姿勃发 (Chen Lijun is a rare and heroic figure among modern actresses)](https://s.weibo.com/weibo?q=%23%E9%99%88%E4%B8%BD%E5%90%9B%20%E7%8E%B0%E4%BB%A3%E5%A5%B3%E6%BC%94%E5%91%98%E9%87%8C%E5%B0%91%E8%A7%81%E7%9A%84%E8%8B%B1%E5%A7%BF%E5%8B%83%E5%8F%91%23) `27.4K 🔥` `-63%`
1. [王橹杰抽抽乐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%8A%BD%E6%8A%BD%E4%B9%90%23) `25.9K 🔥` `-36%`
1. [王菲为什么选中你我经历的一刻 (Why did Faye Wong choose you? The moment I experienced)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E4%B8%BA%E4%BB%80%E4%B9%88%E9%80%89%E4%B8%AD%E4%BD%A0%E6%88%91%E7%BB%8F%E5%8E%86%E7%9A%84%E4%B8%80%E5%88%BB%23) `25.9K 🔥` `-47%`
1. [属相不是从立春开始算 (Zodiac signs are not calculated from the beginning of spring)](https://s.weibo.com/weibo?q=%23%E5%B1%9E%E7%9B%B8%E4%B8%8D%E6%98%AF%E4%BB%8E%E7%AB%8B%E6%98%A5%E5%BC%80%E5%A7%8B%E7%AE%97%23) `25.5K 🔥` `-44%`
1. [苏翊鸣的第二枚奥运金牌](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%9A%84%E7%AC%AC%E4%BA%8C%E6%9E%9A%E5%A5%A5%E8%BF%90%E9%87%91%E7%89%8C%23) `25.0K 🔥` `-66%`
1. [英国前王子安德鲁被捕 (Former British Prince Andrew arrested)](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E5%89%8D%E7%8E%8B%E5%AD%90%E5%AE%89%E5%BE%B7%E9%B2%81%E8%A2%AB%E6%8D%95%23) `24.9K 🔥` `-60%`
1. [Deepseek神回复](https://s.weibo.com/weibo?q=%23Deepseek%E7%A5%9E%E5%9B%9E%E5%A4%8D%23) `24.6K 🔥` `-75%`
1. [生命树](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%23) `24.6K 🔥` `-46%`
1. [美国若武力介入台湾代价巨大 (If the United States intervenes in Taiwan with force, the cost will be huge)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E8%8B%A5%E6%AD%A6%E5%8A%9B%E4%BB%8B%E5%85%A5%E5%8F%B0%E6%B9%BE%E4%BB%A3%E4%BB%B7%E5%B7%A8%E5%A4%A7%23) `23.3K 🔥` `-81%`

Updated at 2026-02-20 02:31:03

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
