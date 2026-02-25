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

1. [三亚通报在职教师被开除 (Sanya reports that on-the-job teachers have been fired)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E9%80%9A%E6%8A%A5%E5%9C%A8%E8%81%8C%E6%95%99%E5%B8%88%E8%A2%AB%E5%BC%80%E9%99%A4%23) `1.1M 🔥` `NEW`
1. [多少滞留三亚的人被自己穷笑了](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%B0%91%E6%BB%9E%E7%95%99%E4%B8%89%E4%BA%9A%E7%9A%84%E4%BA%BA%E8%A2%AB%E8%87%AA%E5%B7%B1%E7%A9%B7%E7%AC%91%E4%BA%86%23) `558.0K 🔥` `NEW`
1. [中秋请3天假堪比春节](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E7%A7%8B%E8%AF%B73%E5%A4%A9%E5%81%87%E5%A0%AA%E6%AF%94%E6%98%A5%E8%8A%82%23) `498.3K 🔥` `NEW`
1. [你打字吧 你字好看](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E6%89%93%E5%AD%97%E5%90%A7%20%E4%BD%A0%E5%AD%97%E5%A5%BD%E7%9C%8B%23) `472.3K 🔥` `NEW`
1. [考公火爆缩编却开始了](https://s.weibo.com/weibo?q=%23%E8%80%83%E5%85%AC%E7%81%AB%E7%88%86%E7%BC%A9%E7%BC%96%E5%8D%B4%E5%BC%80%E5%A7%8B%E4%BA%86%23) `415.0K 🔥` `NEW`
1. [单依纯二巡官宣](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BE%9D%E7%BA%AF%E4%BA%8C%E5%B7%A1%E5%AE%98%E5%AE%A3%23) `326.0K 🔥` `NEW`
1. [14岁谷爱凌在上海街头说这么多老外](https://s.weibo.com/weibo?q=%2314%E5%B2%81%E8%B0%B7%E7%88%B1%E5%87%8C%E5%9C%A8%E4%B8%8A%E6%B5%B7%E8%A1%97%E5%A4%B4%E8%AF%B4%E8%BF%99%E4%B9%88%E5%A4%9A%E8%80%81%E5%A4%96%23) `323.1K 🔥` `NEW`
1. [难怪考试不让上厕所](https://s.weibo.com/weibo?q=%23%E9%9A%BE%E6%80%AA%E8%80%83%E8%AF%95%E4%B8%8D%E8%AE%A9%E4%B8%8A%E5%8E%95%E6%89%80%23) `304.0K 🔥` `NEW`
1. [校服的裙摆开播](https://s.weibo.com/weibo?q=%23%E6%A0%A1%E6%9C%8D%E7%9A%84%E8%A3%99%E6%91%86%E5%BC%80%E6%92%AD%23) `294.3K 🔥` `NEW`
1. [王橹杰彩烟应援](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E5%BD%A9%E7%83%9F%E5%BA%94%E6%8F%B4%23) `242.7K 🔥` `NEW`
1. [王鹤棣眼神杀 (Wang Hedi’s eyes are killing)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E7%9C%BC%E7%A5%9E%E6%9D%80%23) `223.4K 🔥` `NEW`
1. [琉球父母被迫杀死孩子后自杀](https://s.weibo.com/weibo?q=%23%E7%90%89%E7%90%83%E7%88%B6%E6%AF%8D%E8%A2%AB%E8%BF%AB%E6%9D%80%E6%AD%BB%E5%AD%A9%E5%AD%90%E5%90%8E%E8%87%AA%E6%9D%80%23) `219.0K 🔥` `NEW`
1. [黄景瑜关晓彤新剧初吻](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E5%85%B3%E6%99%93%E5%BD%A4%E6%96%B0%E5%89%A7%E5%88%9D%E5%90%BB%23) `213.7K 🔥` `NEW`
1. [女儿出嫁父亲退回彩礼送上两沓现金](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%84%BF%E5%87%BA%E5%AB%81%E7%88%B6%E4%BA%B2%E9%80%80%E5%9B%9E%E5%BD%A9%E7%A4%BC%E9%80%81%E4%B8%8A%E4%B8%A4%E6%B2%93%E7%8E%B0%E9%87%91%23) `190.9K 🔥` `NEW`
1. [熟人羞耻症](https://s.weibo.com/weibo?q=%23%E7%86%9F%E4%BA%BA%E7%BE%9E%E8%80%BB%E7%97%87%23) `187.2K 🔥` `NEW`
1. [想给老人买杯水辗转多家奶茶店被拒](https://s.weibo.com/weibo?q=%23%E6%83%B3%E7%BB%99%E8%80%81%E4%BA%BA%E4%B9%B0%E6%9D%AF%E6%B0%B4%E8%BE%97%E8%BD%AC%E5%A4%9A%E5%AE%B6%E5%A5%B6%E8%8C%B6%E5%BA%97%E8%A2%AB%E6%8B%92%23) `145.2K 🔥` `NEW`
1. [唐宫结局封神](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%AE%AB%E7%BB%93%E5%B1%80%E5%B0%81%E7%A5%9E%23) `138.8K 🔥` `NEW`
1. [袁一琦居然当了芒果甲方](https://s.weibo.com/weibo?q=%23%E8%A2%81%E4%B8%80%E7%90%A6%E5%B1%85%E7%84%B6%E5%BD%93%E4%BA%86%E8%8A%92%E6%9E%9C%E7%94%B2%E6%96%B9%23) `123.0K 🔥` `NEW`
1. [新郎回应岳父婚礼现场退还18.8万彩礼](https://s.weibo.com/weibo?q=%23%E6%96%B0%E9%83%8E%E5%9B%9E%E5%BA%94%E5%B2%B3%E7%88%B6%E5%A9%9A%E7%A4%BC%E7%8E%B0%E5%9C%BA%E9%80%80%E8%BF%9818.8%E4%B8%87%E5%BD%A9%E7%A4%BC%23) `117.6K 🔥` `NEW`
1. [谷爱凌回应冬奥神图出圈](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%9B%9E%E5%BA%94%E5%86%AC%E5%A5%A5%E7%A5%9E%E5%9B%BE%E5%87%BA%E5%9C%88%23) `116.7K 🔥` `NEW`
1. [爸爸奶奶相继离世网友跟空房子再见 (Dad and grandma passed away one after another, netizens said goodbye to the empty house)](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E5%A5%B6%E5%A5%B6%E7%9B%B8%E7%BB%A7%E7%A6%BB%E4%B8%96%E7%BD%91%E5%8F%8B%E8%B7%9F%E7%A9%BA%E6%88%BF%E5%AD%90%E5%86%8D%E8%A7%81%23) `108.8K 🔥` `NEW`
1. [今天是太阳雨第一阶段杀青](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E6%98%AF%E5%A4%AA%E9%98%B3%E9%9B%A8%E7%AC%AC%E4%B8%80%E9%98%B6%E6%AE%B5%E6%9D%80%E9%9D%92%23) `107.6K 🔥` `NEW`
1. [退彩礼新娘否认自己是恋爱脑](https://s.weibo.com/weibo?q=%23%E9%80%80%E5%BD%A9%E7%A4%BC%E6%96%B0%E5%A8%98%E5%90%A6%E8%AE%A4%E8%87%AA%E5%B7%B1%E6%98%AF%E6%81%8B%E7%88%B1%E8%84%91%23) `107.5K 🔥` `NEW`
1. [张函瑞开机照](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%BD%E7%91%9E%E5%BC%80%E6%9C%BA%E7%85%A7%23) `107.4K 🔥` `NEW`
1. [小S女儿lily回应首次参加大秀](https://s.weibo.com/weibo?q=%23%E5%B0%8FS%E5%A5%B3%E5%84%BFlily%E5%9B%9E%E5%BA%94%E9%A6%96%E6%AC%A1%E5%8F%82%E5%8A%A0%E5%A4%A7%E7%A7%80%23) `91.5K 🔥` `NEW`
1. [张新成一条裤子系了两根皮带](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%96%B0%E6%88%90%E4%B8%80%E6%9D%A1%E8%A3%A4%E5%AD%90%E7%B3%BB%E4%BA%86%E4%B8%A4%E6%A0%B9%E7%9A%AE%E5%B8%A6%23) `87.8K 🔥` `NEW`
1. [国产剧里无色无味但剧毒的老实人](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E5%89%A7%E9%87%8C%E6%97%A0%E8%89%B2%E6%97%A0%E5%91%B3%E4%BD%86%E5%89%A7%E6%AF%92%E7%9A%84%E8%80%81%E5%AE%9E%E4%BA%BA%23) `86.9K 🔥` `NEW`
1. [寒衣店第一次遇到退货](https://s.weibo.com/weibo?q=%23%E5%AF%92%E8%A1%A3%E5%BA%97%E7%AC%AC%E4%B8%80%E6%AC%A1%E9%81%87%E5%88%B0%E9%80%80%E8%B4%A7%23) `85.5K 🔥` `NEW`
1. [贾冰已确诊黄景瑜唯粉](https://s.weibo.com/weibo?q=%23%E8%B4%BE%E5%86%B0%E5%B7%B2%E7%A1%AE%E8%AF%8A%E9%BB%84%E6%99%AF%E7%91%9C%E5%94%AF%E7%B2%89%23) `84.9K 🔥` `NEW`
1. [游客在三亚沙滩写不想上班](https://s.weibo.com/weibo?q=%23%E6%B8%B8%E5%AE%A2%E5%9C%A8%E4%B8%89%E4%BA%9A%E6%B2%99%E6%BB%A9%E5%86%99%E4%B8%8D%E6%83%B3%E4%B8%8A%E7%8F%AD%23) `822.3K 🔥` `+358%`
1. [央视点赞莲花跑车中国智造 (CCTV praises Lotus sports car intelligently made in China)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E7%82%B9%E8%B5%9E%E8%8E%B2%E8%8A%B1%E8%B7%91%E8%BD%A6%E4%B8%AD%E5%9B%BD%E6%99%BA%E9%80%A0%23) `572.1K 🔥` `+161%`
1. [刘强东已接到5条大型游艇订单 (Liu Qiangdong has received orders for 5 large yachts)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BC%BA%E4%B8%9C%E5%B7%B2%E6%8E%A5%E5%88%B05%E6%9D%A1%E5%A4%A7%E5%9E%8B%E6%B8%B8%E8%89%87%E8%AE%A2%E5%8D%95%23) `322.8K 🔥` `+39%`
1. [吴昕自曝录制快本三四个月还是想走 (Wu Xin reveals that she still wants to leave after three or four months of recording the album)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%87%AA%E6%9B%9D%E5%BD%95%E5%88%B6%E5%BF%AB%E6%9C%AC%E4%B8%89%E5%9B%9B%E4%B8%AA%E6%9C%88%E8%BF%98%E6%98%AF%E6%83%B3%E8%B5%B0%23) `322.7K 🔥` `+41%`
1. [时代峰峻高会否认时代少年团单飞](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E9%AB%98%E4%BC%9A%E5%90%A6%E8%AE%A4%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E5%8D%95%E9%A3%9E%23) `322.2K 🔥` `+40%`
1. [交警回应女子随手拍举报20多辆车](https://s.weibo.com/weibo?q=%23%E4%BA%A4%E8%AD%A6%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%AD%90%E9%9A%8F%E6%89%8B%E6%8B%8D%E4%B8%BE%E6%8A%A520%E5%A4%9A%E8%BE%86%E8%BD%A6%23) `256.9K 🔥` `+76%`
1. [继父亲吻女童时母亲就在现场](https://s.weibo.com/weibo?q=%23%E7%BB%A7%E7%88%B6%E4%BA%B2%E5%90%BB%E5%A5%B3%E7%AB%A5%E6%97%B6%E6%AF%8D%E4%BA%B2%E5%B0%B1%E5%9C%A8%E7%8E%B0%E5%9C%BA%23) `218.8K 🔥` `+74%`
1. [我们的少年时代2](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%23) `190.8K 🔥` `+92%`
1. [春节国内出游5.96亿人次](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E5%9B%BD%E5%86%85%E5%87%BA%E6%B8%B85.96%E4%BA%BF%E4%BA%BA%E6%AC%A1%23) `606.6K 🔥`
1. [伊能静尝试生酮饮食半年瘦到86斤 (Yi Nengjing tried the ketogenic diet for half a year and lost weight to 86 pounds)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E8%83%BD%E9%9D%99%E5%B0%9D%E8%AF%95%E7%94%9F%E9%85%AE%E9%A5%AE%E9%A3%9F%E5%8D%8A%E5%B9%B4%E7%98%A6%E5%88%B086%E6%96%A4%23) `269.3K 🔥`
1. [王楚然丞磊伟大的杀青梗](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E4%B8%9E%E7%A3%8A%E4%BC%9F%E5%A4%A7%E7%9A%84%E6%9D%80%E9%9D%92%E6%A2%97%23) `161.4K 🔥`
1. [将门独后 (The only one left behind)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `90.2K 🔥`
1. [告白官宣王星越和邓恩熙](https://s.weibo.com/weibo?q=%23%E5%91%8A%E7%99%BD%E5%AE%98%E5%AE%A3%E7%8E%8B%E6%98%9F%E8%B6%8A%E5%92%8C%E9%82%93%E6%81%A9%E7%86%99%23) `347.2K 🔥` `-38%`
1. [平顶山再通报打人事件](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E9%A1%B6%E5%B1%B1%E5%86%8D%E9%80%9A%E6%8A%A5%E6%89%93%E4%BA%BA%E4%BA%8B%E4%BB%B6%23) `190.4K 🔥` `-31%`
1. [大爷欲购200万元黄金店员报警 (The uncle wanted to buy 2 million yuan in gold. The clerk called the police)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%88%B7%E6%AC%B2%E8%B4%AD200%E4%B8%87%E5%85%83%E9%BB%84%E9%87%91%E5%BA%97%E5%91%98%E6%8A%A5%E8%AD%A6%23) `173.8K 🔥` `-84%`
1. [默茨抵达北京开始访华](https://s.weibo.com/weibo?q=%23%E9%BB%98%E8%8C%A8%E6%8A%B5%E8%BE%BE%E5%8C%97%E4%BA%AC%E5%BC%80%E5%A7%8B%E8%AE%BF%E5%8D%8E%23) `155.3K 🔥` `-33%`
1. [宝马7系降价约27万 (BMW 7 Series price cut by about 270,000)](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E9%A9%AC7%E7%B3%BB%E9%99%8D%E4%BB%B7%E7%BA%A627%E4%B8%87%23) `151.3K 🔥` `-80%`
1. [继父曾发布女童穿短裙高跟鞋视频 (Stepfather once posted a video of a girl wearing a short skirt and high heels)](https://s.weibo.com/weibo?q=%23%E7%BB%A7%E7%88%B6%E6%9B%BE%E5%8F%91%E5%B8%83%E5%A5%B3%E7%AB%A5%E7%A9%BF%E7%9F%AD%E8%A3%99%E9%AB%98%E8%B7%9F%E9%9E%8B%E8%A7%86%E9%A2%91%23) `128.8K 🔥` `-44%`
1. [长剧出现了马年第1匹口碑黑马](https://s.weibo.com/weibo?q=%23%E9%95%BF%E5%89%A7%E5%87%BA%E7%8E%B0%E4%BA%86%E9%A9%AC%E5%B9%B4%E7%AC%AC1%E5%8C%B9%E5%8F%A3%E7%A2%91%E9%BB%91%E9%A9%AC%23) `101.4K 🔥` `-54%`
1. [生酮饮食是个啥](https://s.weibo.com/weibo?q=%23%E7%94%9F%E9%85%AE%E9%A5%AE%E9%A3%9F%E6%98%AF%E4%B8%AA%E5%95%A5%23) `91.9K 🔥` `-60%`
1. [台北餐厅冷库女尸案](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E5%8C%97%E9%A4%90%E5%8E%85%E5%86%B7%E5%BA%93%E5%A5%B3%E5%B0%B8%E6%A1%88%23) `88.3K 🔥` `-61%`

Updated at 2026-02-25 13:15:59

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
