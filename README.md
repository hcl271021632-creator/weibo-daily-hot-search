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

1. [浪姐7阵容 (Lang Jie 7 lineup)](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%907%E9%98%B5%E5%AE%B9%23) `811.5K 🔥` `NEW`
1. [这就是中国AI产业链的硬核实力](https://s.weibo.com/weibo?q=%23%E8%BF%99%E5%B0%B1%E6%98%AF%E4%B8%AD%E5%9B%BDAI%E4%BA%A7%E4%B8%9A%E9%93%BE%E7%9A%84%E7%A1%AC%E6%A0%B8%E5%AE%9E%E5%8A%9B%23) `661.4K 🔥` `NEW`
1. [896线版智界R7发布即交付](https://s.weibo.com/weibo?q=%23896%E7%BA%BF%E7%89%88%E6%99%BA%E7%95%8CR7%E5%8F%91%E5%B8%83%E5%8D%B3%E4%BA%A4%E4%BB%98%23) `649.7K 🔥` `NEW`
1. [白日提灯OST官宣](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AFOST%E5%AE%98%E5%AE%A3%23) `283.8K 🔥` `NEW`
1. [朱伟知道张雪峰去世后哭了](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E4%BC%9F%E7%9F%A5%E9%81%93%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%8E%BB%E4%B8%96%E5%90%8E%E5%93%AD%E4%BA%86%23) `281.3K 🔥` `NEW`
1. [郑州大学发博悼念张雪峰](https://s.weibo.com/weibo?q=%23%E9%83%91%E5%B7%9E%E5%A4%A7%E5%AD%A6%E5%8F%91%E5%8D%9A%E6%82%BC%E5%BF%B5%E5%BC%A0%E9%9B%AA%E5%B3%B0%23) `277.9K 🔥` `NEW`
1. [周杰伦 歌词](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%20%E6%AD%8C%E8%AF%8D%23) `275.1K 🔥` `NEW`
1. [张雪峰公司注册多枚女儿姓名商标](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%85%AC%E5%8F%B8%E6%B3%A8%E5%86%8C%E5%A4%9A%E6%9E%9A%E5%A5%B3%E5%84%BF%E5%A7%93%E5%90%8D%E5%95%86%E6%A0%87%23) `262.0K 🔥` `NEW`
1. [颜如晶一年减重2.9斤](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%A6%82%E6%99%B6%E4%B8%80%E5%B9%B4%E5%87%8F%E9%87%8D2.9%E6%96%A4%23) `260.3K 🔥` `NEW`
1. [张雪峰曾说名下连块砖都没有](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%9B%BE%E8%AF%B4%E5%90%8D%E4%B8%8B%E8%BF%9E%E5%9D%97%E7%A0%96%E9%83%BD%E6%B2%A1%E6%9C%89%23) `258.8K 🔥` `NEW`
1. [周杰伦新歌从夯到拉排名 (Jay Chou's new songs ranked from popular to popular)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E6%AD%8C%E4%BB%8E%E5%A4%AF%E5%88%B0%E6%8B%89%E6%8E%92%E5%90%8D%23) `258.4K 🔥` `NEW`
1. [郝蕾说不想再见纪凌尘了](https://s.weibo.com/weibo?q=%23%E9%83%9D%E8%95%BE%E8%AF%B4%E4%B8%8D%E6%83%B3%E5%86%8D%E8%A7%81%E7%BA%AA%E5%87%8C%E5%B0%98%E4%BA%86%23) `257.0K 🔥` `NEW`
1. [张雪峰捐款千万资助贫困学生](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%8D%90%E6%AC%BE%E5%8D%83%E4%B8%87%E8%B5%84%E5%8A%A9%E8%B4%AB%E5%9B%B0%E5%AD%A6%E7%94%9F%23) `255.5K 🔥` `NEW`
1. [恋与深空](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%23) `254.3K 🔥` `NEW`
1. [郑州大学校友会悼念张雪峰](https://s.weibo.com/weibo?q=%23%E9%83%91%E5%B7%9E%E5%A4%A7%E5%AD%A6%E6%A0%A1%E5%8F%8B%E4%BC%9A%E6%82%BC%E5%BF%B5%E5%BC%A0%E9%9B%AA%E5%B3%B0%23) `252.9K 🔥` `NEW`
1. [心源性猝死救心丸无效](https://s.weibo.com/weibo?q=%23%E5%BF%83%E6%BA%90%E6%80%A7%E7%8C%9D%E6%AD%BB%E6%95%91%E5%BF%83%E4%B8%B8%E6%97%A0%E6%95%88%23) `252.4K 🔥` `NEW`
1. [内鬼受贿两千万公司损失一个亿](https://s.weibo.com/weibo?q=%23%E5%86%85%E9%AC%BC%E5%8F%97%E8%B4%BF%E4%B8%A4%E5%8D%83%E4%B8%87%E5%85%AC%E5%8F%B8%E6%8D%9F%E5%A4%B1%E4%B8%80%E4%B8%AA%E4%BA%BF%23) `250.4K 🔥` `NEW`
1. [安睡裤什么时候变成这样了](https://s.weibo.com/weibo?q=%23%E5%AE%89%E7%9D%A1%E8%A3%A4%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%8F%98%E6%88%90%E8%BF%99%E6%A0%B7%E4%BA%86%23) `250.3K 🔥` `NEW`
1. [张宇 雪峰一路走好](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%AE%87%20%E9%9B%AA%E5%B3%B0%E4%B8%80%E8%B7%AF%E8%B5%B0%E5%A5%BD%23) `249.7K 🔥` `NEW`
1. [日本对现役军人冲击中国使馆冷处理](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%AF%B9%E7%8E%B0%E5%BD%B9%E5%86%9B%E4%BA%BA%E5%86%B2%E5%87%BB%E4%B8%AD%E5%9B%BD%E4%BD%BF%E9%A6%86%E5%86%B7%E5%A4%84%E7%90%86%23) `246.7K 🔥` `NEW`
1. [中园石化加油站被立案调查 (Zhongyuan Petrochemical Gas Station is under investigation)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%AD%E7%9F%B3%E5%8C%96%E5%8A%A0%E6%B2%B9%E7%AB%99%E8%A2%AB%E7%AB%8B%E6%A1%88%E8%B0%83%E6%9F%A5%23) `205.9K 🔥` `NEW`
1. [霍启刚自曝为追求郭晶晶费尽心思](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%90%AF%E5%88%9A%E8%87%AA%E6%9B%9D%E4%B8%BA%E8%BF%BD%E6%B1%82%E9%83%AD%E6%99%B6%E6%99%B6%E8%B4%B9%E5%B0%BD%E5%BF%83%E6%80%9D%23) `190.3K 🔥` `NEW`
1. [逐玉创网飞国产剧新纪录](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%88%9B%E7%BD%91%E9%A3%9E%E5%9B%BD%E4%BA%A7%E5%89%A7%E6%96%B0%E7%BA%AA%E5%BD%95%23) `169.2K 🔥` `NEW`
1. [王俊凯 浪姐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%20%E6%B5%AA%E5%A7%90%23) `169.0K 🔥` `NEW`
1. [崩坏星穹铁道](https://s.weibo.com/weibo?q=%23%E5%B4%A9%E5%9D%8F%E6%98%9F%E7%A9%B9%E9%93%81%E9%81%93%23) `165.9K 🔥` `NEW`
1. [夏之光主演](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E4%B9%8B%E5%85%89%E4%B8%BB%E6%BC%94%23) `163.8K 🔥` `NEW`
1. [金泰亨田柾国swim军装cha](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%B3%B0%E4%BA%A8%E7%94%B0%E6%9F%BE%E5%9B%BDswim%E5%86%9B%E8%A3%85cha%23) `162.8K 🔥` `NEW`
1. [夏以昼新PV](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E4%BB%A5%E6%98%BC%E6%96%B0PV%23) `141.3K 🔥` `NEW`
1. [跑步究竟预防心梗还是引发心梗](https://s.weibo.com/weibo?q=%23%E8%B7%91%E6%AD%A5%E7%A9%B6%E7%AB%9F%E9%A2%84%E9%98%B2%E5%BF%83%E6%A2%97%E8%BF%98%E6%98%AF%E5%BC%95%E5%8F%91%E5%BF%83%E6%A2%97%23) `139.5K 🔥` `NEW`
1. [熬夜时心脏为何突然咯噔一下](https://s.weibo.com/weibo?q=%23%E7%86%AC%E5%A4%9C%E6%97%B6%E5%BF%83%E8%84%8F%E4%B8%BA%E4%BD%95%E7%AA%81%E7%84%B6%E5%92%AF%E5%99%94%E4%B8%80%E4%B8%8B%23) `127.8K 🔥` `NEW`
1. [剧版哈利波特预告片 (Trailer for the TV series Harry Potter)](https://s.weibo.com/weibo?q=%23%E5%89%A7%E7%89%88%E5%93%88%E5%88%A9%E6%B3%A2%E7%89%B9%E9%A2%84%E5%91%8A%E7%89%87%23) `125.7K 🔥` `NEW`
1. [理解为什么大家爱饭后散步了](https://s.weibo.com/weibo?q=%23%E7%90%86%E8%A7%A3%E4%B8%BA%E4%BB%80%E4%B9%88%E5%A4%A7%E5%AE%B6%E7%88%B1%E9%A5%AD%E5%90%8E%E6%95%A3%E6%AD%A5%E4%BA%86%23) `122.8K 🔥` `NEW`
1. [闯我大使馆的日本不法之徒身份曝光](https://s.weibo.com/weibo?q=%23%E9%97%AF%E6%88%91%E5%A4%A7%E4%BD%BF%E9%A6%86%E7%9A%84%E6%97%A5%E6%9C%AC%E4%B8%8D%E6%B3%95%E4%B9%8B%E5%BE%92%E8%BA%AB%E4%BB%BD%E6%9B%9D%E5%85%89%23) `122.4K 🔥` `NEW`
1. [三甲医生提醒吃面后运动严重会休克](https://s.weibo.com/weibo?q=%23%E4%B8%89%E7%94%B2%E5%8C%BB%E7%94%9F%E6%8F%90%E9%86%92%E5%90%83%E9%9D%A2%E5%90%8E%E8%BF%90%E5%8A%A8%E4%B8%A5%E9%87%8D%E4%BC%9A%E4%BC%91%E5%85%8B%23) `113.9K 🔥` `NEW`
1. [金价将继续推升](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%B0%86%E7%BB%A7%E7%BB%AD%E6%8E%A8%E5%8D%87%23) `98.4K 🔥` `NEW`
1. [张雪峰曾回应新闻学争议](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%9B%BE%E5%9B%9E%E5%BA%94%E6%96%B0%E9%97%BB%E5%AD%A6%E4%BA%89%E8%AE%AE%23) `96.3K 🔥` `NEW`
1. [金饰价格一夜大涨63元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E6%A0%BC%E4%B8%80%E5%A4%9C%E5%A4%A7%E6%B6%A863%E5%85%83%23) `95.5K 🔥` `NEW`
1. [速效救心丸搜索同比增30倍](https://s.weibo.com/weibo?q=%23%E9%80%9F%E6%95%88%E6%95%91%E5%BF%83%E4%B8%B8%E6%90%9C%E7%B4%A2%E5%90%8C%E6%AF%94%E5%A2%9E30%E5%80%8D%23) `95.0K 🔥` `NEW`
1. [夏以昼冥罗之主](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E4%BB%A5%E6%98%BC%E5%86%A5%E7%BD%97%E4%B9%8B%E4%B8%BB%23) `95.0K 🔥` `NEW`
1. [黄金是不是调整结束了](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E6%98%AF%E4%B8%8D%E6%98%AF%E8%B0%83%E6%95%B4%E7%BB%93%E6%9D%9F%E4%BA%86%23) `92.4K 🔥` `NEW`
1. [14岁男孩把干冰放冰箱半夜爆炸 (14-year-old boy put dry ice in the refrigerator and it exploded in the middle of the night)](https://s.weibo.com/weibo?q=%2314%E5%B2%81%E7%94%B7%E5%AD%A9%E6%8A%8A%E5%B9%B2%E5%86%B0%E6%94%BE%E5%86%B0%E7%AE%B1%E5%8D%8A%E5%A4%9C%E7%88%86%E7%82%B8%23) `92.3K 🔥` `NEW`
1. [樊振东空降迈阿密](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E7%A9%BA%E9%99%8D%E8%BF%88%E9%98%BF%E5%AF%86%23) `89.9K 🔥` `NEW`
1. [一笑随歌](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%AC%91%E9%9A%8F%E6%AD%8C%23) `85.0K 🔥` `NEW`
1. [姆巴佩膝伤遭皇马误诊](https://s.weibo.com/weibo?q=%23%E5%A7%86%E5%B7%B4%E4%BD%A9%E8%86%9D%E4%BC%A4%E9%81%AD%E7%9A%87%E9%A9%AC%E8%AF%AF%E8%AF%8A%23) `81.5K 🔥` `NEW`
1. [嘴唇发紫 心脏不好](https://s.weibo.com/weibo?q=%23%E5%98%B4%E5%94%87%E5%8F%91%E7%B4%AB%20%E5%BF%83%E8%84%8F%E4%B8%8D%E5%A5%BD%23) `1.1M 🔥` `+294%`
1. [避谶](https://s.weibo.com/weibo?q=%23%E9%81%BF%E8%B0%B6%23) `649.7K 🔥` `+160%`
1. [旧手机回收价暴涨五六倍](https://s.weibo.com/weibo?q=%23%E6%97%A7%E6%89%8B%E6%9C%BA%E5%9B%9E%E6%94%B6%E4%BB%B7%E6%9A%B4%E6%B6%A8%E4%BA%94%E5%85%AD%E5%80%8D%23) `262.2K 🔥` `+60%`
1. [美国与伊朗和谈方案曝光](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%8E%E4%BC%8A%E6%9C%97%E5%92%8C%E8%B0%88%E6%96%B9%E6%A1%88%E6%9B%9D%E5%85%89%23) `278.9K 🔥`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `193.0K 🔥`
1. [刘亦菲 宝格丽女王](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%20%E5%AE%9D%E6%A0%BC%E4%B8%BD%E5%A5%B3%E7%8E%8B%23) `94.4K 🔥` `-37%`
1. [拿错狗的饭盒去上班 (Taking the wrong dog’s lunchbox to work)](https://s.weibo.com/weibo?q=%23%E6%8B%BF%E9%94%99%E7%8B%97%E7%9A%84%E9%A5%AD%E7%9B%92%E5%8E%BB%E4%B8%8A%E7%8F%AD%23) `89.1K 🔥` `-38%`

Updated at 2026-03-25 11:42:09

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
