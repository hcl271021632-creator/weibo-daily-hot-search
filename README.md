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

1. [华策声明 (Huace Statement)](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E7%AD%96%E5%A3%B0%E6%98%8E%23) `758.8K 🔥` `NEW`
1. [试管婴儿出生右脚缺4趾产检未发现](https://s.weibo.com/weibo?q=%23%E8%AF%95%E7%AE%A1%E5%A9%B4%E5%84%BF%E5%87%BA%E7%94%9F%E5%8F%B3%E8%84%9A%E7%BC%BA4%E8%B6%BE%E4%BA%A7%E6%A3%80%E6%9C%AA%E5%8F%91%E7%8E%B0%23) `481.1K 🔥` `NEW`
1. [刘少昂女友发文](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82%E5%A5%B3%E5%8F%8B%E5%8F%91%E6%96%87%23) `216.4K 🔥` `NEW`
1. [向华强说遗产都交给郭碧婷来管](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%8D%8E%E5%BC%BA%E8%AF%B4%E9%81%97%E4%BA%A7%E9%83%BD%E4%BA%A4%E7%BB%99%E9%83%AD%E7%A2%A7%E5%A9%B7%E6%9D%A5%E7%AE%A1%23) `214.0K 🔥` `NEW`
1. [Maria回归FENDI首秀](https://s.weibo.com/weibo?q=%23Maria%E5%9B%9E%E5%BD%92FENDI%E9%A6%96%E7%A7%80%23) `183.6K 🔥` `NEW`
1. [女大学生坐硬座31小时返校心脏骤停](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%A4%A7%E5%AD%A6%E7%94%9F%E5%9D%90%E7%A1%AC%E5%BA%A731%E5%B0%8F%E6%97%B6%E8%BF%94%E6%A0%A1%E5%BF%83%E8%84%8F%E9%AA%A4%E5%81%9C%23) `173.6K 🔥` `NEW`
1. [谷爱凌回怼美副总统](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%9B%9E%E6%80%BC%E7%BE%8E%E5%89%AF%E6%80%BB%E7%BB%9F%23) `170.4K 🔥` `NEW`
1. [中国最适合夫妻养老退休的城市](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%9C%80%E9%80%82%E5%90%88%E5%A4%AB%E5%A6%BB%E5%85%BB%E8%80%81%E9%80%80%E4%BC%91%E7%9A%84%E5%9F%8E%E5%B8%82%23) `161.0K 🔥` `NEW`
1. [放过小说妹](https://s.weibo.com/weibo?q=%23%E6%94%BE%E8%BF%87%E5%B0%8F%E8%AF%B4%E5%A6%B9%23) `131.3K 🔥` `NEW`
1. [终于知道小说里的男女主长啥样了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E5%B0%8F%E8%AF%B4%E9%87%8C%E7%9A%84%E7%94%B7%E5%A5%B3%E4%B8%BB%E9%95%BF%E5%95%A5%E6%A0%B7%E4%BA%86%23) `104.4K 🔥` `NEW`
1. [继父亲吻女孩事件最新进展 (The latest developments in the incident of stepfather kissing girl)](https://s.weibo.com/weibo?q=%23%E7%BB%A7%E7%88%B6%E4%BA%B2%E5%90%BB%E5%A5%B3%E5%AD%A9%E4%BA%8B%E4%BB%B6%E6%9C%80%E6%96%B0%E8%BF%9B%E5%B1%95%23) `102.7K 🔥` `NEW`
1. [Kep1er献唱哪吒2](https://s.weibo.com/weibo?q=%23Kep1er%E7%8C%AE%E5%94%B1%E5%93%AA%E5%90%922%23) `102.3K 🔥` `NEW`
1. [菠菜最好吃的做法](https://s.weibo.com/weibo?q=%23%E8%8F%A0%E8%8F%9C%E6%9C%80%E5%A5%BD%E5%90%83%E7%9A%84%E5%81%9A%E6%B3%95%23) `99.8K 🔥` `NEW`
1. [胖东来针织衫只赚1块1](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E9%92%88%E7%BB%87%E8%A1%AB%E5%8F%AA%E8%B5%9A1%E5%9D%971%23) `98.1K 🔥` `NEW`
1. [乌士兵被迫肢解战友遗体](https://s.weibo.com/weibo?q=%23%E4%B9%8C%E5%A3%AB%E5%85%B5%E8%A2%AB%E8%BF%AB%E8%82%A2%E8%A7%A3%E6%88%98%E5%8F%8B%E9%81%97%E4%BD%93%23) `98.0K 🔥` `NEW`
1. [郭晓婷王天辰 单开一部](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%93%E5%A9%B7%E7%8E%8B%E5%A4%A9%E8%BE%B0%20%E5%8D%95%E5%BC%80%E4%B8%80%E9%83%A8%23) `98.0K 🔥` `NEW`
1. [张杰发未成年人保护法](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E5%8F%91%E6%9C%AA%E6%88%90%E5%B9%B4%E4%BA%BA%E4%BF%9D%E6%8A%A4%E6%B3%95%23) `97.5K 🔥` `NEW`
1. [广东英德1岁多走失男童已离世](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E8%8B%B1%E5%BE%B71%E5%B2%81%E5%A4%9A%E8%B5%B0%E5%A4%B1%E7%94%B7%E7%AB%A5%E5%B7%B2%E7%A6%BB%E4%B8%96%23) `95.0K 🔥` `NEW`
1. [丞磊发了九宫格双人照](https://s.weibo.com/weibo?q=%23%E4%B8%9E%E7%A3%8A%E5%8F%91%E4%BA%86%E4%B9%9D%E5%AE%AB%E6%A0%BC%E5%8F%8C%E4%BA%BA%E7%85%A7%23) `93.7K 🔥` `NEW`
1. [宋雨琦看秀造型](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E7%9C%8B%E7%A7%80%E9%80%A0%E5%9E%8B%23) `87.5K 🔥` `NEW`
1. [唐嫣无袖西装 (Tang Yan sleeveless suit)](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%AB%A3%E6%97%A0%E8%A2%96%E8%A5%BF%E8%A3%85%23) `86.0K 🔥` `NEW`
1. [夫妻晚5秒错过免费高速付1700余元](https://s.weibo.com/weibo?q=%23%E5%A4%AB%E5%A6%BB%E6%99%9A5%E7%A7%92%E9%94%99%E8%BF%87%E5%85%8D%E8%B4%B9%E9%AB%98%E9%80%9F%E4%BB%981700%E4%BD%99%E5%85%83%23) `1.1M 🔥` `+431%`
1. [女子5.5克黄金戒指换新只剩下2克](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%905.5%E5%85%8B%E9%BB%84%E9%87%91%E6%88%92%E6%8C%87%E6%8D%A2%E6%96%B0%E5%8F%AA%E5%89%A9%E4%B8%8B2%E5%85%8B%23) `259.8K 🔥` `+40%`
1. [FENDI大秀明星阵容](https://s.weibo.com/weibo?q=%23FENDI%E5%A4%A7%E7%A7%80%E6%98%8E%E6%98%9F%E9%98%B5%E5%AE%B9%23) `170.7K 🔥` `+81%`
1. [春节假期多项数据创历史新高](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E5%81%87%E6%9C%9F%E5%A4%9A%E9%A1%B9%E6%95%B0%E6%8D%AE%E5%88%9B%E5%8E%86%E5%8F%B2%E6%96%B0%E9%AB%98%23) `630.8K 🔥`
1. [金价高的已经推出红绳戒指了](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E9%AB%98%E7%9A%84%E5%B7%B2%E7%BB%8F%E6%8E%A8%E5%87%BA%E7%BA%A2%E7%BB%B3%E6%88%92%E6%8C%87%E4%BA%86%23) `329.5K 🔥`
1. [代露娃 短剧](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E9%9C%B2%E5%A8%83%20%E7%9F%AD%E5%89%A7%23) `321.0K 🔥`
1. [王天辰郭晓婷床戏](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%E9%83%AD%E6%99%93%E5%A9%B7%E5%BA%8A%E6%88%8F%23) `225.3K 🔥`
1. [王橹杰壁纸 (Wang Lujie wallpaper)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E5%A3%81%E7%BA%B8%23) `218.6K 🔥`
1. [刘晓庆短剧吻戏](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%86%E7%9F%AD%E5%89%A7%E5%90%BB%E6%88%8F%23) `207.6K 🔥`
1. [iPhone可添加门禁卡可写入加密](https://s.weibo.com/weibo?q=%23iPhone%E5%8F%AF%E6%B7%BB%E5%8A%A0%E9%97%A8%E7%A6%81%E5%8D%A1%E5%8F%AF%E5%86%99%E5%85%A5%E5%8A%A0%E5%AF%86%23) `203.8K 🔥`
1. [考研 (Postgraduate entrance examination)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%23) `203.0K 🔥`
1. [女子疑丈夫出轨闺蜜花9千雇人追踪](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%96%91%E4%B8%88%E5%A4%AB%E5%87%BA%E8%BD%A8%E9%97%BA%E8%9C%9C%E8%8A%B19%E5%8D%83%E9%9B%87%E4%BA%BA%E8%BF%BD%E8%B8%AA%23) `169.9K 🔥`
1. [墨宝非宝宣布离婚](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E5%AE%9D%E9%9D%9E%E5%AE%9D%E5%AE%A3%E5%B8%83%E7%A6%BB%E5%A9%9A%23) `168.1K 🔥`
1. [一家4口上山妻子死亡失联时神情恐惧 (Family of 4 looked frightened when wife died and lost contact while going up mountain)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B64%E5%8F%A3%E4%B8%8A%E5%B1%B1%E5%A6%BB%E5%AD%90%E6%AD%BB%E4%BA%A1%E5%A4%B1%E8%81%94%E6%97%B6%E7%A5%9E%E6%83%85%E6%81%90%E6%83%A7%23) `165.5K 🔥`
1. [杨洋不让江山复工 (Yang Yang won’t let Jiangshan resume work)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%A4%8D%E5%B7%A5%23) `160.1K 🔥`
1. [虞书欣云初暗夜奔跑](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%BA%91%E5%88%9D%E6%9A%97%E5%A4%9C%E5%A5%94%E8%B7%91%23) `81.9K 🔥`
1. [女子心跳骤停因美甲无法探测血氧值 (Woman's heart stopped and her blood oxygen level couldn't be detected due to manicure)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%BF%83%E8%B7%B3%E9%AA%A4%E5%81%9C%E5%9B%A0%E7%BE%8E%E7%94%B2%E6%97%A0%E6%B3%95%E6%8E%A2%E6%B5%8B%E8%A1%80%E6%B0%A7%E5%80%BC%23) `390.8K 🔥` `-51%`
1. [尘白禁区 中国邮政](https://s.weibo.com/weibo?q=%23%E5%B0%98%E7%99%BD%E7%A6%81%E5%8C%BA%20%E4%B8%AD%E5%9B%BD%E9%82%AE%E6%94%BF%23) `242.4K 🔥` `-24%`
1. [魅族 (Meizu)](https://s.weibo.com/weibo?q=%23%E9%AD%85%E6%97%8F%23) `225.7K 🔥` `-37%`
1. [白鹿忘记自己会说韩语了](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%BF%98%E8%AE%B0%E8%87%AA%E5%B7%B1%E4%BC%9A%E8%AF%B4%E9%9F%A9%E8%AF%AD%E4%BA%86%23) `164.2K 🔥` `-24%`
1. [拍谢娜双胞胎儿女的狗仔涉嫌违法](https://s.weibo.com/weibo?q=%23%E6%8B%8D%E8%B0%A2%E5%A8%9C%E5%8F%8C%E8%83%9E%E8%83%8E%E5%84%BF%E5%A5%B3%E7%9A%84%E7%8B%97%E4%BB%94%E6%B6%89%E5%AB%8C%E8%BF%9D%E6%B3%95%23) `145.5K 🔥` `-30%`
1. [孙颖莎黄牌 (Sun Yingsha yellow card)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E9%BB%84%E7%89%8C%23) `132.7K 🔥` `-59%`
1. [福建喊话回归台湾回复收到](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%BB%BA%E5%96%8A%E8%AF%9D%E5%9B%9E%E5%BD%92%E5%8F%B0%E6%B9%BE%E5%9B%9E%E5%A4%8D%E6%94%B6%E5%88%B0%23) `131.9K 🔥` `-40%`
1. [魅族手机3月正式退市](https://s.weibo.com/weibo?q=%23%E9%AD%85%E6%97%8F%E6%89%8B%E6%9C%BA3%E6%9C%88%E6%AD%A3%E5%BC%8F%E9%80%80%E5%B8%82%23) `106.9K 🔥` `-21%`
1. [张杰声援谢娜](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E5%A3%B0%E6%8F%B4%E8%B0%A2%E5%A8%9C%23) `106.0K 🔥` `-46%`
1. [偏偏宠爱女主 (I just love the heroine)](https://s.weibo.com/weibo?q=%23%E5%81%8F%E5%81%8F%E5%AE%A0%E7%88%B1%E5%A5%B3%E4%B8%BB%23) `103.3K 🔥` `-48%`
1. [陶喆最终五站官宣 (Tao Zhe’s final five stops are officially announced)](https://s.weibo.com/weibo?q=%23%E9%99%B6%E5%96%86%E6%9C%80%E7%BB%88%E4%BA%94%E7%AB%99%E5%AE%98%E5%AE%A3%23) `93.5K 🔥` `-26%`
1. [谷爱凌晒照纪念奶奶](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%99%92%E7%85%A7%E7%BA%AA%E5%BF%B5%E5%A5%B6%E5%A5%B6%23) `87.5K 🔥` `-26%`
1. [靠爱不能维持一辈子的婚姻](https://s.weibo.com/weibo?q=%23%E9%9D%A0%E7%88%B1%E4%B8%8D%E8%83%BD%E7%BB%B4%E6%8C%81%E4%B8%80%E8%BE%88%E5%AD%90%E7%9A%84%E5%A9%9A%E5%A7%BB%23) `86.3K 🔥` `-39%`

Updated at 2026-02-25 23:39:31

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
