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

1. [iPhone4回收价暴涨80倍 (iPhone 4 recycling price skyrockets 80 times)](https://s.weibo.com/weibo?q=%23iPhone4%E5%9B%9E%E6%94%B6%E4%BB%B7%E6%9A%B4%E6%B6%A880%E5%80%8D%23) `1.1M 🔥` `NEW`
1. [七彩云南万千气象](https://s.weibo.com/weibo?q=%23%E4%B8%83%E5%BD%A9%E4%BA%91%E5%8D%97%E4%B8%87%E5%8D%83%E6%B0%94%E8%B1%A1%23) `628.9K 🔥` `NEW`
1. [伊朗伊斯兰革命卫队海军指挥官身亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BC%8A%E6%96%AF%E5%85%B0%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E6%B5%B7%E5%86%9B%E6%8C%87%E6%8C%A5%E5%AE%98%E8%BA%AB%E4%BA%A1%23) `269.5K 🔥` `NEW`
1. [我们一直把苹果放反了](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E4%B8%80%E7%9B%B4%E6%8A%8A%E8%8B%B9%E6%9E%9C%E6%94%BE%E5%8F%8D%E4%BA%86%23) `248.7K 🔥` `NEW`
1. [晋江发情况说明](https://s.weibo.com/weibo?q=%23%E6%99%8B%E6%B1%9F%E5%8F%91%E6%83%85%E5%86%B5%E8%AF%B4%E6%98%8E%23) `223.3K 🔥` `NEW`
1. [助理曾因担心张雪峰准备买AED](https://s.weibo.com/weibo?q=%23%E5%8A%A9%E7%90%86%E6%9B%BE%E5%9B%A0%E6%8B%85%E5%BF%83%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%87%86%E5%A4%87%E4%B9%B0AED%23) `179.6K 🔥` `NEW`
1. [妈妈重回案发现场洗刷儿子血迹](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E9%87%8D%E5%9B%9E%E6%A1%88%E5%8F%91%E7%8E%B0%E5%9C%BA%E6%B4%97%E5%88%B7%E5%84%BF%E5%AD%90%E8%A1%80%E8%BF%B9%23) `176.4K 🔥` `NEW`
1. [拼多多新拼姆一期150亿品牌自营](https://s.weibo.com/weibo?q=%23%E6%8B%BC%E5%A4%9A%E5%A4%9A%E6%96%B0%E6%8B%BC%E5%A7%86%E4%B8%80%E6%9C%9F150%E4%BA%BF%E5%93%81%E7%89%8C%E8%87%AA%E8%90%A5%23) `171.1K 🔥` `NEW`
1. [以色列担心特朗普突然停战](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E6%8B%85%E5%BF%83%E7%89%B9%E6%9C%97%E6%99%AE%E7%AA%81%E7%84%B6%E5%81%9C%E6%88%98%23) `139.5K 🔥` `NEW`
1. [留几手发文暗讽被全网炮轰](https://s.weibo.com/weibo?q=%23%E7%95%99%E5%87%A0%E6%89%8B%E5%8F%91%E6%96%87%E6%9A%97%E8%AE%BD%E8%A2%AB%E5%85%A8%E7%BD%91%E7%82%AE%E8%BD%B0%23) `131.5K 🔥` `NEW`
1. [雪山救狐狸创作者最初只为卖酱板鸭 (The creator of "Save the Fox in Snow Mountain" initially only wanted to sell salted duck)](https://s.weibo.com/weibo?q=%23%E9%9B%AA%E5%B1%B1%E6%95%91%E7%8B%90%E7%8B%B8%E5%88%9B%E4%BD%9C%E8%80%85%E6%9C%80%E5%88%9D%E5%8F%AA%E4%B8%BA%E5%8D%96%E9%85%B1%E6%9D%BF%E9%B8%AD%23) `121.6K 🔥` `NEW`
1. [只有GEN认为T1夺冠](https://s.weibo.com/weibo?q=%23%E5%8F%AA%E6%9C%89GEN%E8%AE%A4%E4%B8%BAT1%E5%A4%BA%E5%86%A0%23) `120.6K 🔥` `NEW`
1. [杨超越主演陈思诚新片](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%B6%85%E8%B6%8A%E4%B8%BB%E6%BC%94%E9%99%88%E6%80%9D%E8%AF%9A%E6%96%B0%E7%89%87%23) `118.7K 🔥` `NEW`
1. [男子为表忠心将房产99%份额转妻子](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E4%B8%BA%E8%A1%A8%E5%BF%A0%E5%BF%83%E5%B0%86%E6%88%BF%E4%BA%A799%25%E4%BB%BD%E9%A2%9D%E8%BD%AC%E5%A6%BB%E5%AD%90%23) `115.4K 🔥` `NEW`
1. [朴敏英瘦成这样](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E6%95%8F%E8%8B%B1%E7%98%A6%E6%88%90%E8%BF%99%E6%A0%B7%23) `111.4K 🔥` `NEW`
1. [陈思罕又被星探看上了](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%80%9D%E7%BD%95%E5%8F%88%E8%A2%AB%E6%98%9F%E6%8E%A2%E7%9C%8B%E4%B8%8A%E4%BA%86%23) `97.3K 🔥` `NEW`
1. [伊称已击中202架美以军机](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E7%A7%B0%E5%B7%B2%E5%87%BB%E4%B8%AD202%E6%9E%B6%E7%BE%8E%E4%BB%A5%E5%86%9B%E6%9C%BA%23) `97.2K 🔥` `NEW`
1. [陈飞宇热巴白日提灯两集短剧](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E7%83%AD%E5%B7%B4%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E4%B8%A4%E9%9B%86%E7%9F%AD%E5%89%A7%23) `96.4K 🔥` `NEW`
1. [笔记本电脑销量暴跌40%](https://s.weibo.com/weibo?q=%23%E7%AC%94%E8%AE%B0%E6%9C%AC%E7%94%B5%E8%84%91%E9%94%80%E9%87%8F%E6%9A%B4%E8%B7%8C40%25%23) `87.6K 🔥` `NEW`
1. [伊朗对美以发动82波打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%B9%E7%BE%8E%E4%BB%A5%E5%8F%91%E5%8A%A882%E6%B3%A2%E6%89%93%E5%87%BB%23) `86.5K 🔥` `NEW`
1. [共和国3天痛失3位院士 (The Republic lost 3 academicians in 3 days)](https://s.weibo.com/weibo?q=%23%E5%85%B1%E5%92%8C%E5%9B%BD3%E5%A4%A9%E7%97%9B%E5%A4%B13%E4%BD%8D%E9%99%A2%E5%A3%AB%23) `803.8K 🔥` `+426%`
1. [王俊凯 演唱会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%20%E6%BC%94%E5%94%B1%E4%BC%9A%23) `347.8K 🔥` `+213%`
1. [孟子义差点上到李昀锐车上](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E5%B7%AE%E7%82%B9%E4%B8%8A%E5%88%B0%E6%9D%8E%E6%98%80%E9%94%90%E8%BD%A6%E4%B8%8A%23) `269.0K 🔥` `+220%`
1. [董子健 我以前也是东北女婿](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AD%90%E5%81%A5%20%E6%88%91%E4%BB%A5%E5%89%8D%E4%B9%9F%E6%98%AF%E4%B8%9C%E5%8C%97%E5%A5%B3%E5%A9%BF%23) `174.2K 🔥` `+24%`
1. [外甥方称刘晓庆撕裂亲情](https://s.weibo.com/weibo?q=%23%E5%A4%96%E7%94%A5%E6%96%B9%E7%A7%B0%E5%88%98%E6%99%93%E5%BA%86%E6%92%95%E8%A3%82%E4%BA%B2%E6%83%85%23) `121.3K 🔥` `+25%`
1. [刘佳梁聊天记录](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BD%B3%E6%A2%81%E8%81%8A%E5%A4%A9%E8%AE%B0%E5%BD%95%23) `120.1K 🔥` `+23%`
1. [中方回应特朗普称5月中旬访华 (China responds to Trump's announcement of visiting China in mid-May)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B05%E6%9C%88%E4%B8%AD%E6%97%AC%E8%AE%BF%E5%8D%8E%23) `170.4K 🔥`
1. [卧床35年女子顺利产下健康宝宝](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%8A35%E5%B9%B4%E5%A5%B3%E5%AD%90%E9%A1%BA%E5%88%A9%E4%BA%A7%E4%B8%8B%E5%81%A5%E5%BA%B7%E5%AE%9D%E5%AE%9D%23) `135.6K 🔥`
1. [张凌赫小学奥数班毕业照](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%B0%8F%E5%AD%A6%E5%A5%A5%E6%95%B0%E7%8F%AD%E6%AF%95%E4%B8%9A%E7%85%A7%23) `110.3K 🔥`
1. [春日限定美好家 (Spring limited beautiful home)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%97%A5%E9%99%90%E5%AE%9A%E7%BE%8E%E5%A5%BD%E5%AE%B6%23) `260.9K 🔥` `-76%`
1. [救命神器AED使用率不足0.1%](https://s.weibo.com/weibo?q=%23%E6%95%91%E5%91%BD%E7%A5%9E%E5%99%A8AED%E4%BD%BF%E7%94%A8%E7%8E%87%E4%B8%8D%E8%B6%B30.1%25%23) `187.9K 🔥` `-83%`
1. [早期心血管病可能反映在脸上](https://s.weibo.com/weibo?q=%23%E6%97%A9%E6%9C%9F%E5%BF%83%E8%A1%80%E7%AE%A1%E7%97%85%E5%8F%AF%E8%83%BD%E5%8F%8D%E6%98%A0%E5%9C%A8%E8%84%B8%E4%B8%8A%23) `183.1K 🔥` `-83%`
1. [张雪峰曾为多睡一会儿住酒店 (Zhang Xuefeng once stayed in a hotel to sleep a little longer)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%9B%BE%E4%B8%BA%E5%A4%9A%E7%9D%A1%E4%B8%80%E4%BC%9A%E5%84%BF%E4%BD%8F%E9%85%92%E5%BA%97%23) `182.5K 🔥` `-83%`
1. [孟子义腰比名牌细](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E8%85%B0%E6%AF%94%E5%90%8D%E7%89%8C%E7%BB%86%23) `181.0K 🔥` `-77%`
1. [镜头霸凌](https://s.weibo.com/weibo?q=%23%E9%95%9C%E5%A4%B4%E9%9C%B8%E5%87%8C%23) `178.6K 🔥` `-77%`
1. [以后将只在周二网购](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%90%8E%E5%B0%86%E5%8F%AA%E5%9C%A8%E5%91%A8%E4%BA%8C%E7%BD%91%E8%B4%AD%23) `175.2K 🔥` `-51%`
1. [郭敬明需要避谶](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%95%AC%E6%98%8E%E9%9C%80%E8%A6%81%E9%81%BF%E8%B0%B6%23) `138.4K 🔥` `-85%`
1. [王一博 乐华](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%20%E4%B9%90%E5%8D%8E%23) `138.3K 🔥` `-27%`
1. [阚清子和老公一同现身机场 (Kan Qingzi and her husband appeared at the airport together)](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E5%92%8C%E8%80%81%E5%85%AC%E4%B8%80%E5%90%8C%E7%8E%B0%E8%BA%AB%E6%9C%BA%E5%9C%BA%23) `131.2K 🔥` `-57%`
1. [家长违停孩子开门杀撞人后逃逸](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%95%BF%E8%BF%9D%E5%81%9C%E5%AD%A9%E5%AD%90%E5%BC%80%E9%97%A8%E6%9D%80%E6%92%9E%E4%BA%BA%E5%90%8E%E9%80%83%E9%80%B8%23) `126.2K 🔥` `-88%`
1. [鹿晗校草时期 现实版流星花园](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E6%A0%A1%E8%8D%89%E6%97%B6%E6%9C%9F%20%E7%8E%B0%E5%AE%9E%E7%89%88%E6%B5%81%E6%98%9F%E8%8A%B1%E5%9B%AD%23) `126.2K 🔥` `-42%`
1. [张凌赫 张家玮](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E5%BC%A0%E5%AE%B6%E7%8E%AE%23) `125.7K 🔥` `-50%`
1. [微信聊天为什么会出现对方正在输入](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%81%8A%E5%A4%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E5%87%BA%E7%8E%B0%E5%AF%B9%E6%96%B9%E6%AD%A3%E5%9C%A8%E8%BE%93%E5%85%A5%23) `114.5K 🔥` `-89%`
1. [气血不足的人干不了这活 (People with insufficient blood cannot do this job)](https://s.weibo.com/weibo?q=%23%E6%B0%94%E8%A1%80%E4%B8%8D%E8%B6%B3%E7%9A%84%E4%BA%BA%E5%B9%B2%E4%B8%8D%E4%BA%86%E8%BF%99%E6%B4%BB%23) `101.9K 🔥` `-62%`
1. [情侣间转账6万因多音字闹上法庭 (Couple who transferred RMB 60,000 to each other went to court over polyphonic characters)](https://s.weibo.com/weibo?q=%23%E6%83%85%E4%BE%A3%E9%97%B4%E8%BD%AC%E8%B4%A66%E4%B8%87%E5%9B%A0%E5%A4%9A%E9%9F%B3%E5%AD%97%E9%97%B9%E4%B8%8A%E6%B3%95%E5%BA%AD%23) `97.2K 🔥` `-64%`
1. [杨笠辟谣不结婚不生小孩](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%AC%A0%E8%BE%9F%E8%B0%A3%E4%B8%8D%E7%BB%93%E5%A9%9A%E4%B8%8D%E7%94%9F%E5%B0%8F%E5%AD%A9%23) `94.7K 🔥` `-33%`
1. [张雪峰追悼会将于周六举行 (Zhang Xuefeng's memorial service will be held on Saturday)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E8%BF%BD%E6%82%BC%E4%BC%9A%E5%B0%86%E4%BA%8E%E5%91%A8%E5%85%AD%E4%B8%BE%E8%A1%8C%23) `94.1K 🔥` `-32%`
1. [张雪峰最后一个视频还在吃外卖](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E8%A7%86%E9%A2%91%E8%BF%98%E5%9C%A8%E5%90%83%E5%A4%96%E5%8D%96%23) `93.9K 🔥` `-77%`
1. [能做夫妻是有点玄学在身上的 (Being a couple is a bit mysterious.)](https://s.weibo.com/weibo?q=%23%E8%83%BD%E5%81%9A%E5%A4%AB%E5%A6%BB%E6%98%AF%E6%9C%89%E7%82%B9%E7%8E%84%E5%AD%A6%E5%9C%A8%E8%BA%AB%E4%B8%8A%E7%9A%84%23) `93.0K 🔥` `-51%`
1. [内塔尼亚胡妻子为成年儿子诉苦遭批 (Netanyahu's wife criticized for complaining about adult son)](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A1%94%E5%B0%BC%E4%BA%9A%E8%83%A1%E5%A6%BB%E5%AD%90%E4%B8%BA%E6%88%90%E5%B9%B4%E5%84%BF%E5%AD%90%E8%AF%89%E8%8B%A6%E9%81%AD%E6%89%B9%23) `90.2K 🔥` `-92%`
1. [柯文哲被判17年 (Ke Wenzhe was sentenced to 17 years)](https://s.weibo.com/weibo?q=%23%E6%9F%AF%E6%96%87%E5%93%B2%E8%A2%AB%E5%88%A417%E5%B9%B4%23) `86.0K 🔥` `-92%`

Updated at 2026-03-26 17:42:35

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
