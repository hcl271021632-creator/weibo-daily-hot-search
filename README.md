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

1. [徐梦桃金牌 (Xu Mengtao gold medal)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E9%87%91%E7%89%8C%23) `11.1M 🔥` `NEW`
1. [2026春节消费市场红火开场](https://s.weibo.com/weibo?q=%232026%E6%98%A5%E8%8A%82%E6%B6%88%E8%B4%B9%E5%B8%82%E5%9C%BA%E7%BA%A2%E7%81%AB%E5%BC%80%E5%9C%BA%23) `1.7M 🔥` `NEW`
1. [中国队第二金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E7%AC%AC%E4%BA%8C%E9%87%91%23) `1.0M 🔥` `NEW`
1. [初三一定记得睡懒觉](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%89%E4%B8%80%E5%AE%9A%E8%AE%B0%E5%BE%97%E7%9D%A1%E6%87%92%E8%A7%89%23) `958.4K 🔥` `NEW`
1. [众星祝贺苏翊鸣](https://s.weibo.com/weibo?q=%23%E4%BC%97%E6%98%9F%E7%A5%9D%E8%B4%BA%E8%8B%8F%E7%BF%8A%E9%B8%A3%23) `601.3K 🔥` `NEW`
1. [苏翊鸣教练双膝跪地](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E6%95%99%E7%BB%83%E5%8F%8C%E8%86%9D%E8%B7%AA%E5%9C%B0%23) `481.4K 🔥` `NEW`
1. [商洛地震](https://s.weibo.com/weibo?q=%23%E5%95%86%E6%B4%9B%E5%9C%B0%E9%9C%87%23) `458.3K 🔥` `NEW`
1. [苏翊鸣边唱国歌边哭](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E8%BE%B9%E5%94%B1%E5%9B%BD%E6%AD%8C%E8%BE%B9%E5%93%AD%23) `391.3K 🔥` `NEW`
1. [邵琪铜牌](https://s.weibo.com/weibo?q=%23%E9%82%B5%E7%90%AA%E9%93%9C%E7%89%8C%23) `333.9K 🔥` `NEW`
1. [谁把郭富城鞋踩掉了](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%8A%8A%E9%83%AD%E5%AF%8C%E5%9F%8E%E9%9E%8B%E8%B8%A9%E6%8E%89%E4%BA%86%23) `333.7K 🔥` `NEW`
1. [假期打麻将打到肢体抽搐口吐白沫 (Playing mahjong during vacation, my limbs twitched and I foamed at the mouth.)](https://s.weibo.com/weibo?q=%23%E5%81%87%E6%9C%9F%E6%89%93%E9%BA%BB%E5%B0%86%E6%89%93%E5%88%B0%E8%82%A2%E4%BD%93%E6%8A%BD%E6%90%90%E5%8F%A3%E5%90%90%E7%99%BD%E6%B2%AB%23) `330.1K 🔥` `NEW`
1. [8岁小姨给晚辈发红包亲属发声](https://s.weibo.com/weibo?q=%238%E5%B2%81%E5%B0%8F%E5%A7%A8%E7%BB%99%E6%99%9A%E8%BE%88%E5%8F%91%E7%BA%A2%E5%8C%85%E4%BA%B2%E5%B1%9E%E5%8F%91%E5%A3%B0%23) `328.3K 🔥` `NEW`
1. [海口至上海机票高达11560元](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8F%A3%E8%87%B3%E4%B8%8A%E6%B5%B7%E6%9C%BA%E7%A5%A8%E9%AB%98%E8%BE%BE11560%E5%85%83%23) `327.6K 🔥` `NEW`
1. [祝贺老将徐梦桃](https://s.weibo.com/weibo?q=%23%E7%A5%9D%E8%B4%BA%E8%80%81%E5%B0%86%E5%BE%90%E6%A2%A6%E6%A1%83%23) `323.1K 🔥` `NEW`
1. [小猫以为人也是怀孕两个月就生](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E4%BB%A5%E4%B8%BA%E4%BA%BA%E4%B9%9F%E6%98%AF%E6%80%80%E5%AD%95%E4%B8%A4%E4%B8%AA%E6%9C%88%E5%B0%B1%E7%94%9F%23) `229.8K 🔥` `NEW`
1. [盼盼在手冠军我有](https://s.weibo.com/weibo?q=%23%E7%9B%BC%E7%9B%BC%E5%9C%A8%E6%89%8B%E5%86%A0%E5%86%9B%E6%88%91%E6%9C%89%23) `211.4K 🔥` `NEW`
1. [苏翊鸣第三跳 裁判压分](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%AC%AC%E4%B8%89%E8%B7%B3%20%E8%A3%81%E5%88%A4%E5%8E%8B%E5%88%86%23) `211.0K 🔥` `NEW`
1. [李现祝贺苏翊鸣](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%8E%B0%E7%A5%9D%E8%B4%BA%E8%8B%8F%E7%BF%8A%E9%B8%A3%23) `205.7K 🔥` `NEW`
1. [孔凡钰 可惜](https://s.weibo.com/weibo?q=%23%E5%AD%94%E5%87%A1%E9%92%B0%20%E5%8F%AF%E6%83%9C%23) `196.0K 🔥` `NEW`
1. [冬奥会奖牌榜](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E4%BC%9A%E5%A5%96%E7%89%8C%E6%A6%9C%23) `180.3K 🔥` `NEW`
1. [汕头烟花 (Shantou Fireworks)](https://s.weibo.com/weibo?q=%23%E6%B1%95%E5%A4%B4%E7%83%9F%E8%8A%B1%23) `170.4K 🔥` `NEW`
1. [徐梦桃大喊我怎么跳这么漂亮](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E5%A4%A7%E5%96%8A%E6%88%91%E6%80%8E%E4%B9%88%E8%B7%B3%E8%BF%99%E4%B9%88%E6%BC%82%E4%BA%AE%23) `167.7K 🔥` `NEW`
1. [2026势头最猛的星座](https://s.weibo.com/weibo?q=%232026%E5%8A%BF%E5%A4%B4%E6%9C%80%E7%8C%9B%E7%9A%84%E6%98%9F%E5%BA%A7%23) `158.5K 🔥` `NEW`
1. [台湾女子被臭豆腐店熏到焦虑拔头发](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E5%A5%B3%E5%AD%90%E8%A2%AB%E8%87%AD%E8%B1%86%E8%85%90%E5%BA%97%E7%86%8F%E5%88%B0%E7%84%A6%E8%99%91%E6%8B%94%E5%A4%B4%E5%8F%91%23) `149.1K 🔥` `NEW`
1. [中国香港居民在北海道遇袭](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%A6%99%E6%B8%AF%E5%B1%85%E6%B0%91%E5%9C%A8%E5%8C%97%E6%B5%B7%E9%81%93%E9%81%87%E8%A2%AD%23) `146.3K 🔥` `NEW`
1. [孔凡钰113.33分](https://s.weibo.com/weibo?q=%23%E5%AD%94%E5%87%A1%E9%92%B0113.33%E5%88%86%23) `141.9K 🔥` `NEW`
1. [澳男子摸鱼找工作遭解雇获赔15万元](https://s.weibo.com/weibo?q=%23%E6%BE%B3%E7%94%B7%E5%AD%90%E6%91%B8%E9%B1%BC%E6%89%BE%E5%B7%A5%E4%BD%9C%E9%81%AD%E8%A7%A3%E9%9B%87%E8%8E%B7%E8%B5%9415%E4%B8%87%E5%85%83%23) `141.7K 🔥` `NEW`
1. [张虹为苏翊鸣颁奖](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%99%B9%E4%B8%BA%E8%8B%8F%E7%BF%8A%E9%B8%A3%E9%A2%81%E5%A5%96%23) `140.0K 🔥` `NEW`
1. [妈妈为苏翊鸣擦眼泪](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E4%B8%BA%E8%8B%8F%E7%BF%8A%E9%B8%A3%E6%93%A6%E7%9C%BC%E6%B3%AA%23) `137.2K 🔥` `NEW`
1. [镖人惠英红没打戏好可惜](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E6%83%A0%E8%8B%B1%E7%BA%A2%E6%B2%A1%E6%89%93%E6%88%8F%E5%A5%BD%E5%8F%AF%E6%83%9C%23) `136.0K 🔥` `NEW`
1. [看熊出没孩子开心家长放心 (Watching bears come and go, children are happy, parents are reassured)](https://s.weibo.com/weibo?q=%23%E7%9C%8B%E7%86%8A%E5%87%BA%E6%B2%A1%E5%AD%A9%E5%AD%90%E5%BC%80%E5%BF%83%E5%AE%B6%E9%95%BF%E6%94%BE%E5%BF%83%23) `850.1K 🔥` `+141%`
1. [自由式滑雪女子空中技巧决赛 (Freestyle Skiing Women's Aerials Final)](https://s.weibo.com/weibo?q=%23%E8%87%AA%E7%94%B1%E5%BC%8F%E6%BB%91%E9%9B%AA%E5%A5%B3%E5%AD%90%E7%A9%BA%E4%B8%AD%E6%8A%80%E5%B7%A7%E5%86%B3%E8%B5%9B%23) `649.3K 🔥` `+45%`
1. [曝邓超怒怼项目方维护孙俪](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E9%82%93%E8%B6%85%E6%80%92%E6%80%BC%E9%A1%B9%E7%9B%AE%E6%96%B9%E7%BB%B4%E6%8A%A4%E5%AD%99%E4%BF%AA%23) `433.8K 🔥` `+37%`
1. [苏翊鸣成中国单板滑雪首位双金王](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E6%88%90%E4%B8%AD%E5%9B%BD%E5%8D%95%E6%9D%BF%E6%BB%91%E9%9B%AA%E9%A6%96%E4%BD%8D%E5%8F%8C%E9%87%91%E7%8E%8B%23) `410.7K 🔥` `+61%`
1. [李健 媚眼抛给瞎子看](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%81%A5%20%E5%AA%9A%E7%9C%BC%E6%8A%9B%E7%BB%99%E7%9E%8E%E5%AD%90%E7%9C%8B%23) `274.0K 🔥` `+98%`
1. [谷爱凌 顶级狩猎者的眼神](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%20%E9%A1%B6%E7%BA%A7%E7%8B%A9%E7%8C%8E%E8%80%85%E7%9A%84%E7%9C%BC%E7%A5%9E%23) `327.6K 🔥`
1. [冬奥会直播](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E4%BC%9A%E7%9B%B4%E6%92%AD%23) `230.2K 🔥`
1. [徐梦桃说需要继续保持专注](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E8%AF%B4%E9%9C%80%E8%A6%81%E7%BB%A7%E7%BB%AD%E4%BF%9D%E6%8C%81%E4%B8%93%E6%B3%A8%23) `191.4K 🔥`
1. [网红阿沁直播首次谈前任刘阳](https://s.weibo.com/weibo?q=%23%E7%BD%91%E7%BA%A2%E9%98%BF%E6%B2%81%E7%9B%B4%E6%92%AD%E9%A6%96%E6%AC%A1%E8%B0%88%E5%89%8D%E4%BB%BB%E5%88%98%E9%98%B3%23) `179.9K 🔥`
1. [惠英红 姐别累着但也别闲着](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%20%E5%A7%90%E5%88%AB%E7%B4%AF%E7%9D%80%E4%BD%86%E4%B9%9F%E5%88%AB%E9%97%B2%E7%9D%80%23) `166.8K 🔥`
1. [镖人 武侠不死](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E6%AD%A6%E4%BE%A0%E4%B8%8D%E6%AD%BB%23) `141.7K 🔥`
1. [白鹿 大大方方的满分女 (Bailu, a generous and generous girl)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%20%E5%A4%A7%E5%A4%A7%E6%96%B9%E6%96%B9%E7%9A%84%E6%BB%A1%E5%88%86%E5%A5%B3%23) `139.2K 🔥`
1. [苏翊鸣金牌 (Su Yiming gold medal)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E9%87%91%E7%89%8C%23) `2.2M 🔥` `-65%`
1. [中国队米兰冬奥首金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E9%A6%96%E9%87%91%23) `1.1M 🔥` `-82%`
1. [苏翊鸣单板滑雪坡障技巧决赛 (Su Yiming Snowboard Slopestyle Finals)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%8D%95%E6%9D%BF%E6%BB%91%E9%9B%AA%E5%9D%A1%E9%9A%9C%E6%8A%80%E5%B7%A7%E5%86%B3%E8%B5%9B%23) `737.3K 🔥` `-91%`
1. [CCTV6 三女休夫](https://s.weibo.com/weibo?q=%23CCTV6%20%E4%B8%89%E5%A5%B3%E4%BC%91%E5%A4%AB%23) `214.5K 🔥` `-53%`
1. [龙洋主持完春晚哭了 (Long Yang cried after hosting the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E9%BE%99%E6%B4%8B%E4%B8%BB%E6%8C%81%E5%AE%8C%E6%98%A5%E6%99%9A%E5%93%AD%E4%BA%86%23) `193.2K 🔥` `-43%`
1. [日本挖到含稀土泥浆的真相来了 (Here’s the truth about mud containing rare earths dug up in Japan)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%8C%96%E5%88%B0%E5%90%AB%E7%A8%80%E5%9C%9F%E6%B3%A5%E6%B5%86%E7%9A%84%E7%9C%9F%E7%9B%B8%E6%9D%A5%E4%BA%86%23) `163.7K 🔥` `-39%`
1. [云旗郝熠然滑雪](https://s.weibo.com/weibo?q=%23%E4%BA%91%E6%97%97%E9%83%9D%E7%86%A0%E7%84%B6%E6%BB%91%E9%9B%AA%23) `146.0K 🔥` `-30%`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `144.4K 🔥` `-38%`
1. [朱志鑫 墨尔本](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%20%E5%A2%A8%E5%B0%94%E6%9C%AC%23) `141.7K 🔥` `-32%`

Updated at 2026-02-18 21:50:17

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
