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

1. [晚5秒要付1700高速费当事人发声 (The person who is late for 5 seconds has to pay 1700 highway toll speaks out)](https://s.weibo.com/weibo?q=%23%E6%99%9A5%E7%A7%92%E8%A6%81%E4%BB%981700%E9%AB%98%E9%80%9F%E8%B4%B9%E5%BD%93%E4%BA%8B%E4%BA%BA%E5%8F%91%E5%A3%B0%23) `1.1M 🔥` `NEW`
1. [特朗普试戴冬奥金牌不还](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%AF%95%E6%88%B4%E5%86%AC%E5%A5%A5%E9%87%91%E7%89%8C%E4%B8%8D%E8%BF%98%23) `313.3K 🔥` `NEW`
1. [尘白禁区](https://s.weibo.com/weibo?q=%23%E5%B0%98%E7%99%BD%E7%A6%81%E5%8C%BA%23) `175.4K 🔥` `NEW`
1. [张靓颖给张天爱接机做饭](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9D%93%E9%A2%96%E7%BB%99%E5%BC%A0%E5%A4%A9%E7%88%B1%E6%8E%A5%E6%9C%BA%E5%81%9A%E9%A5%AD%23) `172.4K 🔥` `NEW`
1. [俄乌冲突](https://s.weibo.com/weibo?q=%23%E4%BF%84%E4%B9%8C%E5%86%B2%E7%AA%81%23) `170.0K 🔥` `NEW`
1. [美籍快艇闯入古巴领海并开火](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E7%B1%8D%E5%BF%AB%E8%89%87%E9%97%AF%E5%85%A5%E5%8F%A4%E5%B7%B4%E9%A2%86%E6%B5%B7%E5%B9%B6%E5%BC%80%E7%81%AB%23) `165.8K 🔥` `NEW`
1. [教师离世未火化遗孀无法领取补贴](https://s.weibo.com/weibo?q=%23%E6%95%99%E5%B8%88%E7%A6%BB%E4%B8%96%E6%9C%AA%E7%81%AB%E5%8C%96%E9%81%97%E5%AD%80%E6%97%A0%E6%B3%95%E9%A2%86%E5%8F%96%E8%A1%A5%E8%B4%B4%23) `147.8K 🔥` `NEW`
1. [周杰伦田馥甄曾一起去英国游学](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E7%94%B0%E9%A6%A5%E7%94%84%E6%9B%BE%E4%B8%80%E8%B5%B7%E5%8E%BB%E8%8B%B1%E5%9B%BD%E6%B8%B8%E5%AD%A6%23) `147.2K 🔥` `NEW`
1. [脸上有5种表现说明气血不足](https://s.weibo.com/weibo?q=%23%E8%84%B8%E4%B8%8A%E6%9C%895%E7%A7%8D%E8%A1%A8%E7%8E%B0%E8%AF%B4%E6%98%8E%E6%B0%94%E8%A1%80%E4%B8%8D%E8%B6%B3%23) `145.6K 🔥` `NEW`
1. [泽连斯基称4年战争让他没了朋友](https://s.weibo.com/weibo?q=%23%E6%B3%BD%E8%BF%9E%E6%96%AF%E5%9F%BA%E7%A7%B04%E5%B9%B4%E6%88%98%E4%BA%89%E8%AE%A9%E4%BB%96%E6%B2%A1%E4%BA%86%E6%9C%8B%E5%8F%8B%23) `145.1K 🔥` `NEW`
1. [奶茶店为啥不卖热水 (Why don’t milk tea shops sell hot water?)](https://s.weibo.com/weibo?q=%23%E5%A5%B6%E8%8C%B6%E5%BA%97%E4%B8%BA%E5%95%A5%E4%B8%8D%E5%8D%96%E7%83%AD%E6%B0%B4%23) `127.3K 🔥` `NEW`
1. [美国AI攻击中国AI模型是给谁做了广告](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BDAI%E6%94%BB%E5%87%BB%E4%B8%AD%E5%9B%BDAI%E6%A8%A1%E5%9E%8B%E6%98%AF%E7%BB%99%E8%B0%81%E5%81%9A%E4%BA%86%E5%B9%BF%E5%91%8A%23) `112.6K 🔥` `NEW`
1. [宋雨琦为张真源工作人员点40杯奶茶](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E4%B8%BA%E5%BC%A0%E7%9C%9F%E6%BA%90%E5%B7%A5%E4%BD%9C%E4%BA%BA%E5%91%98%E7%82%B940%E6%9D%AF%E5%A5%B6%E8%8C%B6%23) `94.1K 🔥` `NEW`
1. [三角洲](https://s.weibo.com/weibo?q=%23%E4%B8%89%E8%A7%92%E6%B4%B2%23) `79.2K 🔥` `NEW`
1. [盲盒不支持七天无理由退换合法吗](https://s.weibo.com/weibo?q=%23%E7%9B%B2%E7%9B%92%E4%B8%8D%E6%94%AF%E6%8C%81%E4%B8%83%E5%A4%A9%E6%97%A0%E7%90%86%E7%94%B1%E9%80%80%E6%8D%A2%E5%90%88%E6%B3%95%E5%90%97%23) `76.0K 🔥` `NEW`
1. [英伟达四季度营收681亿美元](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E4%BC%9F%E8%BE%BE%E5%9B%9B%E5%AD%A3%E5%BA%A6%E8%90%A5%E6%94%B6681%E4%BA%BF%E7%BE%8E%E5%85%83%23) `75.8K 🔥` `NEW`
1. [欧冠16强出炉](https://s.weibo.com/weibo?q=%23%E6%AC%A7%E5%86%A016%E5%BC%BA%E5%87%BA%E7%82%89%23) `74.2K 🔥` `NEW`
1. [中方严厉驳斥日本等国家不实言论](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E4%B8%A5%E5%8E%89%E9%A9%B3%E6%96%A5%E6%97%A5%E6%9C%AC%E7%AD%89%E5%9B%BD%E5%AE%B6%E4%B8%8D%E5%AE%9E%E8%A8%80%E8%AE%BA%23) `73.0K 🔥` `NEW`
1. [米兰偶遇杨幂探店](https://s.weibo.com/weibo?q=%23%E7%B1%B3%E5%85%B0%E5%81%B6%E9%81%87%E6%9D%A8%E5%B9%82%E6%8E%A2%E5%BA%97%23) `72.0K 🔥` `NEW`
1. [短剧从哪找来这么像的三张脸](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E4%BB%8E%E5%93%AA%E6%89%BE%E6%9D%A5%E8%BF%99%E4%B9%88%E5%83%8F%E7%9A%84%E4%B8%89%E5%BC%A0%E8%84%B8%23) `405.3K 🔥` `+42%`
1. [获退18万彩礼女婿经济状况堪忧 (The financial situation of the son-in-law who received 180,000 yuan in betrothal gifts is worrying)](https://s.weibo.com/weibo?q=%23%E8%8E%B7%E9%80%8018%E4%B8%87%E5%BD%A9%E7%A4%BC%E5%A5%B3%E5%A9%BF%E7%BB%8F%E6%B5%8E%E7%8A%B6%E5%86%B5%E5%A0%AA%E5%BF%A7%23) `217.0K 🔥` `+86%`
1. [女子5.5克黄金戒指换新只剩下2克 (Women's 5.5g gold ring was replaced with a new one, only 2g left)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%905.5%E5%85%8B%E9%BB%84%E9%87%91%E6%88%92%E6%8C%87%E6%8D%A2%E6%96%B0%E5%8F%AA%E5%89%A9%E4%B8%8B2%E5%85%8B%23) `216.5K 🔥` `+70%`
1. [考研 (Postgraduate entrance examination)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%23) `178.4K 🔥` `+112%`
1. [财不入急门也不入脏门 (Wealth does not enter the urgent door, nor does it enter the dirty door.)](https://s.weibo.com/weibo?q=%23%E8%B4%A2%E4%B8%8D%E5%85%A5%E6%80%A5%E9%97%A8%E4%B9%9F%E4%B8%8D%E5%85%A5%E8%84%8F%E9%97%A8%23) `177.2K 🔥` `+95%`
1. [魅族 (Meizu)](https://s.weibo.com/weibo?q=%23%E9%AD%85%E6%97%8F%23) `159.2K 🔥` `+50%`
1. [王天辰郭晓婷床戏](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%E9%83%AD%E6%99%93%E5%A9%B7%E5%BA%8A%E6%88%8F%23) `148.0K 🔥` `+40%`
1. [向华强拒绝和向佑见面](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%8D%8E%E5%BC%BA%E6%8B%92%E7%BB%9D%E5%92%8C%E5%90%91%E4%BD%91%E8%A7%81%E9%9D%A2%23) `147.3K 🔥` `+98%`
1. [谷爱凌回怼美副总统](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%9B%9E%E6%80%BC%E7%BE%8E%E5%89%AF%E6%80%BB%E7%BB%9F%23) `146.8K 🔥` `+100%`
1. [向太拉黑小儿子向佑 (Xiang Tai blackmails his youngest son Xiang You)](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%A4%AA%E6%8B%89%E9%BB%91%E5%B0%8F%E5%84%BF%E5%AD%90%E5%90%91%E4%BD%91%23) `146.3K 🔥` `+98%`
1. [一家4口上山妻子死亡失联时神情恐惧](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B64%E5%8F%A3%E4%B8%8A%E5%B1%B1%E5%A6%BB%E5%AD%90%E6%AD%BB%E4%BA%A1%E5%A4%B1%E8%81%94%E6%97%B6%E7%A5%9E%E6%83%85%E6%81%90%E6%83%A7%23) `146.1K 🔥` `+102%`
1. [贵阳一公园两座雕塑被指不雅](https://s.weibo.com/weibo?q=%23%E8%B4%B5%E9%98%B3%E4%B8%80%E5%85%AC%E5%9B%AD%E4%B8%A4%E5%BA%A7%E9%9B%95%E5%A1%91%E8%A2%AB%E6%8C%87%E4%B8%8D%E9%9B%85%23) `145.2K 🔥` `+95%`
1. [广东英德1岁多走失男童已离世 (A 1-year-old boy who was missing in Yingde, Guangdong has passed away)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E8%8B%B1%E5%BE%B71%E5%B2%81%E5%A4%9A%E8%B5%B0%E5%A4%B1%E7%94%B7%E7%AB%A5%E5%B7%B2%E7%A6%BB%E4%B8%96%23) `139.5K 🔥` `+32%`
1. [女子疑丈夫出轨闺蜜花9千雇人追踪](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%96%91%E4%B8%88%E5%A4%AB%E5%87%BA%E8%BD%A8%E9%97%BA%E8%9C%9C%E8%8A%B19%E5%8D%83%E9%9B%87%E4%BA%BA%E8%BF%BD%E8%B8%AA%23) `138.0K 🔥` `+110%`
1. [田柾国直播](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9F%BE%E5%9B%BD%E7%9B%B4%E6%92%AD%23) `121.8K 🔥` `+90%`
1. [中国最适合夫妻养老退休的城市 (The most suitable cities for couples to retire in China)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%9C%80%E9%80%82%E5%90%88%E5%A4%AB%E5%A6%BB%E5%85%BB%E8%80%81%E9%80%80%E4%BC%91%E7%9A%84%E5%9F%8E%E5%B8%82%23) `109.5K 🔥` `+167%`
1. [放过小说妹 (Let go of the novel girl)](https://s.weibo.com/weibo?q=%23%E6%94%BE%E8%BF%87%E5%B0%8F%E8%AF%B4%E5%A6%B9%23) `105.3K 🔥` `+47%`
1. [金价高的已经推出红绳戒指了 (Gold prices are high and red string rings have been launched)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E9%AB%98%E7%9A%84%E5%B7%B2%E7%BB%8F%E6%8E%A8%E5%87%BA%E7%BA%A2%E7%BB%B3%E6%88%92%E6%8C%87%E4%BA%86%23) `88.4K 🔥` `+127%`
1. [白鹿忘记自己会说韩语了 (Bailu forgot that he could speak Korean)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%BF%98%E8%AE%B0%E8%87%AA%E5%B7%B1%E4%BC%9A%E8%AF%B4%E9%9F%A9%E8%AF%AD%E4%BA%86%23) `87.3K 🔥` `+34%`
1. [女大学生坐硬座31小时返校心脏骤停 (Female college student suffers cardiac arrest after returning to school after sitting on hard seat for 31 hours)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%A4%A7%E5%AD%A6%E7%94%9F%E5%9D%90%E7%A1%AC%E5%BA%A731%E5%B0%8F%E6%97%B6%E8%BF%94%E6%A0%A1%E5%BF%83%E8%84%8F%E9%AA%A4%E5%81%9C%23) `801.8K 🔥`
1. [米兰冬奥风雪18天 (18 days of snow at Milan Winter Olympics)](https://s.weibo.com/weibo?q=%23%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E9%A3%8E%E9%9B%AA18%E5%A4%A9%23) `645.1K 🔥`
1. [女子心跳骤停因美甲无法探测血氧值 (Woman's heart stopped and her blood oxygen level couldn't be detected due to manicure)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%BF%83%E8%B7%B3%E9%AA%A4%E5%81%9C%E5%9B%A0%E7%BE%8E%E7%94%B2%E6%97%A0%E6%B3%95%E6%8E%A2%E6%B5%8B%E8%A1%80%E6%B0%A7%E5%80%BC%23) `242.2K 🔥`
1. [乌士兵被迫肢解战友遗体](https://s.weibo.com/weibo?q=%23%E4%B9%8C%E5%A3%AB%E5%85%B5%E8%A2%AB%E8%BF%AB%E8%82%A2%E8%A7%A3%E6%88%98%E5%8F%8B%E9%81%97%E4%BD%93%23) `153.2K 🔥`
1. [刘晓庆短剧吻戏](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%86%E7%9F%AD%E5%89%A7%E5%90%BB%E6%88%8F%23) `121.5K 🔥`
1. [iPhone可添加门禁卡可写入加密 (iPhone can add access control card and write encryption)](https://s.weibo.com/weibo?q=%23iPhone%E5%8F%AF%E6%B7%BB%E5%8A%A0%E9%97%A8%E7%A6%81%E5%8D%A1%E5%8F%AF%E5%86%99%E5%85%A5%E5%8A%A0%E5%AF%86%23) `119.2K 🔥`
1. [墨宝非宝宣布离婚 (Mo Bao Fei Bao announces divorce)](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E5%AE%9D%E9%9D%9E%E5%AE%9D%E5%AE%A3%E5%B8%83%E7%A6%BB%E5%A9%9A%23) `81.4K 🔥`
1. [继父亲吻女孩事件最新进展 (The latest developments in the incident of stepfather kissing girl)](https://s.weibo.com/weibo?q=%23%E7%BB%A7%E7%88%B6%E4%BA%B2%E5%90%BB%E5%A5%B3%E5%AD%A9%E4%BA%8B%E4%BB%B6%E6%9C%80%E6%96%B0%E8%BF%9B%E5%B1%95%23) `77.6K 🔥`
1. [靠爱不能维持一辈子的婚姻 (Love cannot sustain a lifelong marriage)](https://s.weibo.com/weibo?q=%23%E9%9D%A0%E7%88%B1%E4%B8%8D%E8%83%BD%E7%BB%B4%E6%8C%81%E4%B8%80%E8%BE%88%E5%AD%90%E7%9A%84%E5%A9%9A%E5%A7%BB%23) `72.6K 🔥`
1. [试管婴儿出生右脚缺4趾产检未发现 (Four toes on the right foot of a baby born from IVF were not found during prenatal examination)](https://s.weibo.com/weibo?q=%23%E8%AF%95%E7%AE%A1%E5%A9%B4%E5%84%BF%E5%87%BA%E7%94%9F%E5%8F%B3%E8%84%9A%E7%BC%BA4%E8%B6%BE%E4%BA%A7%E6%A3%80%E6%9C%AA%E5%8F%91%E7%8E%B0%23) `384.0K 🔥` `-60%`
1. [刘少昂女友发文](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82%E5%A5%B3%E5%8F%8B%E5%8F%91%E6%96%87%23) `82.5K 🔥` `-22%`

Updated at 2026-02-26 08:53:47

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
