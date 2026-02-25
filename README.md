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

1. [获退的18万彩礼已所剩无几 (There is not much left of the 180,000 refunded gift.)](https://s.weibo.com/weibo?q=%23%E8%8E%B7%E9%80%80%E7%9A%8418%E4%B8%87%E5%BD%A9%E7%A4%BC%E5%B7%B2%E6%89%80%E5%89%A9%E6%97%A0%E5%87%A0%23) `868.3K 🔥` `NEW`
1. [周杰伦演唱会](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%BC%94%E5%94%B1%E4%BC%9A%23) `555.1K 🔥` `NEW`
1. [关于醋的这些说法是谣言](https://s.weibo.com/weibo?q=%23%E5%85%B3%E4%BA%8E%E9%86%8B%E7%9A%84%E8%BF%99%E4%BA%9B%E8%AF%B4%E6%B3%95%E6%98%AF%E8%B0%A3%E8%A8%80%23) `258.2K 🔥` `NEW`
1. [华策解散电影部门](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E7%AD%96%E8%A7%A3%E6%95%A3%E7%94%B5%E5%BD%B1%E9%83%A8%E9%97%A8%23) `234.5K 🔥` `NEW`
1. [谢娜恳请不要将镜头对准孩子](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E6%81%B3%E8%AF%B7%E4%B8%8D%E8%A6%81%E5%B0%86%E9%95%9C%E5%A4%B4%E5%AF%B9%E5%87%86%E5%AD%A9%E5%AD%90%23) `185.7K 🔥` `NEW`
1. [钱枫近况](https://s.weibo.com/weibo?q=%23%E9%92%B1%E6%9E%AB%E8%BF%91%E5%86%B5%23) `185.4K 🔥` `NEW`
1. [iPhone 自动打电话](https://s.weibo.com/weibo?q=%23iPhone%20%E8%87%AA%E5%8A%A8%E6%89%93%E7%94%B5%E8%AF%9D%23) `185.3K 🔥` `NEW`
1. [杨幂柳智敏撞衫](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9F%B3%E6%99%BA%E6%95%8F%E6%92%9E%E8%A1%AB%23) `184.8K 🔥` `NEW`
1. [曝李佳琦过年给亲戚每人发了500红包](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%9D%8E%E4%BD%B3%E7%90%A6%E8%BF%87%E5%B9%B4%E7%BB%99%E4%BA%B2%E6%88%9A%E6%AF%8F%E4%BA%BA%E5%8F%91%E4%BA%86500%E7%BA%A2%E5%8C%85%23) `184.6K 🔥` `NEW`
1. [曝短剧出现男演员揩油镜头](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%9F%AD%E5%89%A7%E5%87%BA%E7%8E%B0%E7%94%B7%E6%BC%94%E5%91%98%E6%8F%A9%E6%B2%B9%E9%95%9C%E5%A4%B4%23) `183.8K 🔥` `NEW`
1. [闵熙珍放弃255亿韩元赔偿 (Min Hee Jin gives up 25.5 billion won compensation)](https://s.weibo.com/weibo?q=%23%E9%97%B5%E7%86%99%E7%8F%8D%E6%94%BE%E5%BC%83255%E4%BA%BF%E9%9F%A9%E5%85%83%E8%B5%94%E5%81%BF%23) `183.2K 🔥` `NEW`
1. [23岁香港女警在警署身亡](https://s.weibo.com/weibo?q=%2323%E5%B2%81%E9%A6%99%E6%B8%AF%E5%A5%B3%E8%AD%A6%E5%9C%A8%E8%AD%A6%E7%BD%B2%E8%BA%AB%E4%BA%A1%23) `183.2K 🔥` `NEW`
1. [360元1斤的草莓今年已售罄](https://s.weibo.com/weibo?q=%23360%E5%85%831%E6%96%A4%E7%9A%84%E8%8D%89%E8%8E%93%E4%BB%8A%E5%B9%B4%E5%B7%B2%E5%94%AE%E7%BD%84%23) `182.8K 🔥` `NEW`
1. [鹿哈官宣得女](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E5%AE%98%E5%AE%A3%E5%BE%97%E5%A5%B3%23) `182.3K 🔥` `NEW`
1. [韦雪新男友首曝光](https://s.weibo.com/weibo?q=%23%E9%9F%A6%E9%9B%AA%E6%96%B0%E7%94%B7%E5%8F%8B%E9%A6%96%E6%9B%9D%E5%85%89%23) `182.2K 🔥` `NEW`
1. [英国白人女婿吃砂糖橘吃成贵州本地人](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E7%99%BD%E4%BA%BA%E5%A5%B3%E5%A9%BF%E5%90%83%E7%A0%82%E7%B3%96%E6%A9%98%E5%90%83%E6%88%90%E8%B4%B5%E5%B7%9E%E6%9C%AC%E5%9C%B0%E4%BA%BA%23) `126.5K 🔥` `NEW`
1. [真正让大脑逆龄的运动](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%AD%A3%E8%AE%A9%E5%A4%A7%E8%84%91%E9%80%86%E9%BE%84%E7%9A%84%E8%BF%90%E5%8A%A8%23) `126.5K 🔥` `NEW`
1. [如果故人留给你的遗物是一个孩子](https://s.weibo.com/weibo?q=%23%E5%A6%82%E6%9E%9C%E6%95%85%E4%BA%BA%E7%95%99%E7%BB%99%E4%BD%A0%E7%9A%84%E9%81%97%E7%89%A9%E6%98%AF%E4%B8%80%E4%B8%AA%E5%AD%A9%E5%AD%90%23) `126.5K 🔥` `NEW`
1. [白鹿说跟王鹤棣认识五年了](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E8%AF%B4%E8%B7%9F%E7%8E%8B%E9%B9%A4%E6%A3%A3%E8%AE%A4%E8%AF%86%E4%BA%94%E5%B9%B4%E4%BA%86%23) `126.5K 🔥` `NEW`
1. [上海发布楼市沪七条](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E5%8F%91%E5%B8%83%E6%A5%BC%E5%B8%82%E6%B2%AA%E4%B8%83%E6%9D%A1%23) `117.8K 🔥` `NEW`
1. [Supreme棺材 (Supreme coffin)](https://s.weibo.com/weibo?q=%23Supreme%E6%A3%BA%E6%9D%90%23) `98.5K 🔥` `NEW`
1. [花35万买房发现装修完住着陌生人](https://s.weibo.com/weibo?q=%23%E8%8A%B135%E4%B8%87%E4%B9%B0%E6%88%BF%E5%8F%91%E7%8E%B0%E8%A3%85%E4%BF%AE%E5%AE%8C%E4%BD%8F%E7%9D%80%E9%99%8C%E7%94%9F%E4%BA%BA%23) `98.2K 🔥` `NEW`
1. [刘浩存从小就长这样](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%E4%BB%8E%E5%B0%8F%E5%B0%B1%E9%95%BF%E8%BF%99%E6%A0%B7%23) `95.8K 🔥` `NEW`
1. [王橹杰嘴一抿哞一声就背起来了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E5%98%B4%E4%B8%80%E6%8A%BF%E5%93%9E%E4%B8%80%E5%A3%B0%E5%B0%B1%E8%83%8C%E8%B5%B7%E6%9D%A5%E4%BA%86%23) `94.2K 🔥` `NEW`
1. [高市早苗政府再次挑衅](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E6%94%BF%E5%BA%9C%E5%86%8D%E6%AC%A1%E6%8C%91%E8%A1%85%23) `93.8K 🔥` `NEW`
1. [我的朋友圈点赞原则](https://s.weibo.com/weibo?q=%23%E6%88%91%E7%9A%84%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%82%B9%E8%B5%9E%E5%8E%9F%E5%88%99%23) `91.3K 🔥` `NEW`
1. [霍格沃兹来了个东方转校生](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E6%A0%BC%E6%B2%83%E5%85%B9%E6%9D%A5%E4%BA%86%E4%B8%AA%E4%B8%9C%E6%96%B9%E8%BD%AC%E6%A0%A1%E7%94%9F%23) `86.9K 🔥` `NEW`
1. [王楚钦回抛约36度](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%9B%9E%E6%8A%9B%E7%BA%A636%E5%BA%A6%23) `83.7K 🔥` `NEW`
1. [左奇函](https://s.weibo.com/weibo?q=%23%E5%B7%A6%E5%A5%87%E5%87%BD%23) `82.8K 🔥` `NEW`
1. [花二十块钱买了只小狗](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E4%BA%8C%E5%8D%81%E5%9D%97%E9%92%B1%E4%B9%B0%E4%BA%86%E5%8F%AA%E5%B0%8F%E7%8B%97%23) `77.9K 🔥` `NEW`
1. [平顶山打人夫妻或从重处罚 (Pingdingshan beats couple or severely punished)](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E9%A1%B6%E5%B1%B1%E6%89%93%E4%BA%BA%E5%A4%AB%E5%A6%BB%E6%88%96%E4%BB%8E%E9%87%8D%E5%A4%84%E7%BD%9A%23) `75.5K 🔥` `NEW`
1. [中秋请3天假堪比春节](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E7%A7%8B%E8%AF%B73%E5%A4%A9%E5%81%87%E5%A0%AA%E6%AF%94%E6%98%A5%E8%8A%82%23) `1.2M 🔥` `+133%`
1. [爸爸奶奶相继离世网友跟空房子再见 (Dad and grandma passed away one after another, netizens said goodbye to the empty house)](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E5%A5%B6%E5%A5%B6%E7%9B%B8%E7%BB%A7%E7%A6%BB%E4%B8%96%E7%BD%91%E5%8F%8B%E8%B7%9F%E7%A9%BA%E6%88%BF%E5%AD%90%E5%86%8D%E8%A7%81%23) `197.8K 🔥` `+82%`
1. [春节国内出游5.96亿人次](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E5%9B%BD%E5%86%85%E5%87%BA%E6%B8%B85.96%E4%BA%BF%E4%BA%BA%E6%AC%A1%23) `664.8K 🔥`
1. [没人比周柯宇更懂礼物](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E4%BA%BA%E6%AF%94%E5%91%A8%E6%9F%AF%E5%AE%87%E6%9B%B4%E6%87%82%E7%A4%BC%E7%89%A9%23) `565.0K 🔥`
1. [多少滞留三亚的人被自己穷笑了](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%B0%91%E6%BB%9E%E7%95%99%E4%B8%89%E4%BA%9A%E7%9A%84%E4%BA%BA%E8%A2%AB%E8%87%AA%E5%B7%B1%E7%A9%B7%E7%AC%91%E4%BA%86%23) `497.1K 🔥`
1. [难怪考试不让上厕所](https://s.weibo.com/weibo?q=%23%E9%9A%BE%E6%80%AA%E8%80%83%E8%AF%95%E4%B8%8D%E8%AE%A9%E4%B8%8A%E5%8E%95%E6%89%80%23) `252.5K 🔥`
1. [琉球父母被迫杀死孩子后自杀](https://s.weibo.com/weibo?q=%23%E7%90%89%E7%90%83%E7%88%B6%E6%AF%8D%E8%A2%AB%E8%BF%AB%E6%9D%80%E6%AD%BB%E5%AD%A9%E5%AD%90%E5%90%8E%E8%87%AA%E6%9D%80%23) `181.6K 🔥`
1. [谷爱凌回应冬奥神图出圈](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%9B%9E%E5%BA%94%E5%86%AC%E5%A5%A5%E7%A5%9E%E5%9B%BE%E5%87%BA%E5%9C%88%23) `136.9K 🔥`
1. [三亚通报在职教师被开除 (Sanya reports that on-the-job teachers have been fired)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E9%80%9A%E6%8A%A5%E5%9C%A8%E8%81%8C%E6%95%99%E5%B8%88%E8%A2%AB%E5%BC%80%E9%99%A4%23) `259.8K 🔥` `-76%`
1. [14岁谷爱凌在上海街头说这么多老外](https://s.weibo.com/weibo?q=%2314%E5%B2%81%E8%B0%B7%E7%88%B1%E5%87%8C%E5%9C%A8%E4%B8%8A%E6%B5%B7%E8%A1%97%E5%A4%B4%E8%AF%B4%E8%BF%99%E4%B9%88%E5%A4%9A%E8%80%81%E5%A4%96%23) `186.0K 🔥` `-42%`
1. [你打字吧 你字好看](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E6%89%93%E5%AD%97%E5%90%A7%20%E4%BD%A0%E5%AD%97%E5%A5%BD%E7%9C%8B%23) `184.2K 🔥` `-61%`
1. [吴昕自曝录制快本三四个月还是想走 (Wu Xin reveals that she still wants to leave after three or four months of recording the album)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%87%AA%E6%9B%9D%E5%BD%95%E5%88%B6%E5%BF%AB%E6%9C%AC%E4%B8%89%E5%9B%9B%E4%B8%AA%E6%9C%88%E8%BF%98%E6%98%AF%E6%83%B3%E8%B5%B0%23) `181.1K 🔥` `-44%`
1. [刘强东已接到5条大型游艇订单 (Liu Qiangdong has received orders for 5 large yachts)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BC%BA%E4%B8%9C%E5%B7%B2%E6%8E%A5%E5%88%B05%E6%9D%A1%E5%A4%A7%E5%9E%8B%E6%B8%B8%E8%89%87%E8%AE%A2%E5%8D%95%23) `181.1K 🔥` `-44%`
1. [时代峰峻高会否认时代少年团单飞 (Times Fengjun Gao will deny that Times Youth League is going solo)](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E9%AB%98%E4%BC%9A%E5%90%A6%E8%AE%A4%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E5%8D%95%E9%A3%9E%23) `136.8K 🔥` `-58%`
1. [单依纯二巡官宣](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BE%9D%E7%BA%AF%E4%BA%8C%E5%B7%A1%E5%AE%98%E5%AE%A3%23) `130.4K 🔥` `-60%`
1. [王橹杰彩烟应援](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E5%BD%A9%E7%83%9F%E5%BA%94%E6%8F%B4%23) `126.5K 🔥` `-48%`
1. [黄景瑜关晓彤新剧初吻](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E5%85%B3%E6%99%93%E5%BD%A4%E6%96%B0%E5%89%A7%E5%88%9D%E5%90%BB%23) `110.9K 🔥` `-48%`
1. [伊能静尝试生酮饮食半年瘦到86斤 (Yi Nengjing tried the ketogenic diet for half a year and lost weight to 86 pounds)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E8%83%BD%E9%9D%99%E5%B0%9D%E8%AF%95%E7%94%9F%E9%85%AE%E9%A5%AE%E9%A3%9F%E5%8D%8A%E5%B9%B4%E7%98%A6%E5%88%B086%E6%96%A4%23) `99.4K 🔥` `-63%`
1. [校服的裙摆开播](https://s.weibo.com/weibo?q=%23%E6%A0%A1%E6%9C%8D%E7%9A%84%E8%A3%99%E6%91%86%E5%BC%80%E6%92%AD%23) `91.9K 🔥` `-69%`
1. [我们的少年时代2](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%23) `91.8K 🔥` `-52%`

Updated at 2026-02-25 14:35:11

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
