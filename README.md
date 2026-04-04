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

1. [高达赛后发孙颖莎 (Gundam revealed Sun Yingsha after the game)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E8%BE%BE%E8%B5%9B%E5%90%8E%E5%8F%91%E5%AD%99%E9%A2%96%E8%8E%8E%23) `136.4K 🔥` `NEW`
1. [迪丽热巴眼神转换好牛](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%9C%BC%E7%A5%9E%E8%BD%AC%E6%8D%A2%E5%A5%BD%E7%89%9B%23) `136.3K 🔥` `NEW`
1. [新疆一中学走廊秒变健身房](https://s.weibo.com/weibo?q=%23%E6%96%B0%E7%96%86%E4%B8%80%E4%B8%AD%E5%AD%A6%E8%B5%B0%E5%BB%8A%E7%A7%92%E5%8F%98%E5%81%A5%E8%BA%AB%E6%88%BF%23) `96.5K 🔥` `NEW`
1. [冯提莫自曝身高体重](https://s.weibo.com/weibo?q=%23%E5%86%AF%E6%8F%90%E8%8E%AB%E8%87%AA%E6%9B%9D%E8%BA%AB%E9%AB%98%E4%BD%93%E9%87%8D%23) `96.0K 🔥` `NEW`
1. [虞书欣签售妆是一枝南南画的](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E7%AD%BE%E5%94%AE%E5%A6%86%E6%98%AF%E4%B8%80%E6%9E%9D%E5%8D%97%E5%8D%97%E7%94%BB%E7%9A%84%23) `95.4K 🔥` `NEW`
1. [中国人6千年前就用上蒸锅了](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BA%BA6%E5%8D%83%E5%B9%B4%E5%89%8D%E5%B0%B1%E7%94%A8%E4%B8%8A%E8%92%B8%E9%94%85%E4%BA%86%23) `91.7K 🔥` `NEW`
1. [女子减肥过度导致心跳骤停](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%87%8F%E8%82%A5%E8%BF%87%E5%BA%A6%E5%AF%BC%E8%87%B4%E5%BF%83%E8%B7%B3%E9%AA%A4%E5%81%9C%23) `89.0K 🔥` `NEW`
1. [王楚钦11比4约奇克](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A611%E6%AF%944%E7%BA%A6%E5%A5%87%E5%85%8B%23) `86.6K 🔥` `NEW`
1. [多功能智齿](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%8A%9F%E8%83%BD%E6%99%BA%E9%BD%BF%23) `84.6K 🔥` `NEW`
1. [金饰克价一夜又跌11元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E4%B8%80%E5%A4%9C%E5%8F%88%E8%B7%8C11%E5%85%83%23) `78.5K 🔥` `NEW`
1. [小说里一个人单挑整个宗门的大师姐 (In the novel, one person challenges the entire sect’s senior sister)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E8%AF%B4%E9%87%8C%E4%B8%80%E4%B8%AA%E4%BA%BA%E5%8D%95%E6%8C%91%E6%95%B4%E4%B8%AA%E5%AE%97%E9%97%A8%E7%9A%84%E5%A4%A7%E5%B8%88%E5%A7%90%23) `74.4K 🔥` `NEW`
1. [收藏了一堆垃圾之书](https://s.weibo.com/weibo?q=%23%E6%94%B6%E8%97%8F%E4%BA%86%E4%B8%80%E5%A0%86%E5%9E%83%E5%9C%BE%E4%B9%8B%E4%B9%A6%23) `67.8K 🔥` `NEW`
1. [张函瑞粉色卫衣](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%BD%E7%91%9E%E7%B2%89%E8%89%B2%E5%8D%AB%E8%A1%A3%23) `67.5K 🔥` `NEW`
1. [土豆片涮冷面](https://s.weibo.com/weibo?q=%23%E5%9C%9F%E8%B1%86%E7%89%87%E6%B6%AE%E5%86%B7%E9%9D%A2%23) `64.5K 🔥` `NEW`
1. [曼城vs利物浦](https://s.weibo.com/weibo?q=%23%E6%9B%BC%E5%9F%8Evs%E5%88%A9%E7%89%A9%E6%B5%A6%23) `64.4K 🔥` `NEW`
1. [王楚钦vs约奇克](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E7%BA%A6%E5%A5%87%E5%85%8B%23) `1.1M 🔥` `+262%`
1. [乘风初舞台第二场 (The second stage of Chengfengchu stage)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E%E5%88%9D%E8%88%9E%E5%8F%B0%E7%AC%AC%E4%BA%8C%E5%9C%BA%23) `166.2K 🔥` `+65%`
1. [五哈只有一个小时](https://s.weibo.com/weibo?q=%23%E4%BA%94%E5%93%88%E5%8F%AA%E6%9C%89%E4%B8%80%E4%B8%AA%E5%B0%8F%E6%97%B6%23) `144.7K 🔥` `+32%`
1. [AL战胜WBG](https://s.weibo.com/weibo?q=%23AL%E6%88%98%E8%83%9CWBG%23) `135.0K 🔥` `+22%`
1. [泰国女星遭假急救人员侵犯](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E5%A5%B3%E6%98%9F%E9%81%AD%E5%81%87%E6%80%A5%E6%95%91%E4%BA%BA%E5%91%98%E4%BE%B5%E7%8A%AF%23) `129.6K 🔥` `+26%`
1. [文旅共绘诗与远方新画卷 (Culture and tourism jointly paint poems and new pictures of distant places)](https://s.weibo.com/weibo?q=%23%E6%96%87%E6%97%85%E5%85%B1%E7%BB%98%E8%AF%97%E4%B8%8E%E8%BF%9C%E6%96%B9%E6%96%B0%E7%94%BB%E5%8D%B7%23) `642.4K 🔥`
1. [酒店员工提醒小孩别玩门家长报警](https://s.weibo.com/weibo?q=%23%E9%85%92%E5%BA%97%E5%91%98%E5%B7%A5%E6%8F%90%E9%86%92%E5%B0%8F%E5%AD%A9%E5%88%AB%E7%8E%A9%E9%97%A8%E5%AE%B6%E9%95%BF%E6%8A%A5%E8%AD%A6%23) `384.7K 🔥`
1. [广东仅珠海仍全域禁止电动自行车 (Only Zhuhai in Guangdong still bans electric bicycles)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E4%BB%85%E7%8F%A0%E6%B5%B7%E4%BB%8D%E5%85%A8%E5%9F%9F%E7%A6%81%E6%AD%A2%E7%94%B5%E5%8A%A8%E8%87%AA%E8%A1%8C%E8%BD%A6%23) `176.1K 🔥`
1. [何宣林回应是孟子义班主任](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%AE%A3%E6%9E%97%E5%9B%9E%E5%BA%94%E6%98%AF%E5%AD%9F%E5%AD%90%E4%B9%89%E7%8F%AD%E4%B8%BB%E4%BB%BB%23) `126.0K 🔥`
1. [鞠婧祎露芜衣夕阳下跳舞](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E9%9C%B2%E8%8A%9C%E8%A1%A3%E5%A4%95%E9%98%B3%E4%B8%8B%E8%B7%B3%E8%88%9E%23) `122.1K 🔥`
1. [爆火鸡煲店老板称用的冰冻鸡 (The owner of the fried turkey pot shop claims that he uses frozen chicken)](https://s.weibo.com/weibo?q=%23%E7%88%86%E7%81%AB%E9%B8%A1%E7%85%B2%E5%BA%97%E8%80%81%E6%9D%BF%E7%A7%B0%E7%94%A8%E7%9A%84%E5%86%B0%E5%86%BB%E9%B8%A1%23) `96.6K 🔥`
1. [刘琳琳拍的虞书欣](https://s.weibo.com/weibo?q=%23%E5%88%98%E7%90%B3%E7%90%B3%E6%8B%8D%E7%9A%84%E8%99%9E%E4%B9%A6%E6%AC%A3%23) `96.4K 🔥`
1. [红果多部短剧AI角色撞脸易烊千玺 (The AI ​​characters in Hongguo's many short dramas collide with Yi Yang Qianxi's face)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E6%9E%9C%E5%A4%9A%E9%83%A8%E7%9F%AD%E5%89%A7AI%E8%A7%92%E8%89%B2%E6%92%9E%E8%84%B8%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%23) `96.2K 🔥`
1. [无人继承的巨额遗产或在拖垮日本](https://s.weibo.com/weibo?q=%23%E6%97%A0%E4%BA%BA%E7%BB%A7%E6%89%BF%E7%9A%84%E5%B7%A8%E9%A2%9D%E9%81%97%E4%BA%A7%E6%88%96%E5%9C%A8%E6%8B%96%E5%9E%AE%E6%97%A5%E6%9C%AC%23) `96.1K 🔥`
1. [79岁老人花2千多买塑身内衣穿](https://s.weibo.com/weibo?q=%2379%E5%B2%81%E8%80%81%E4%BA%BA%E8%8A%B12%E5%8D%83%E5%A4%9A%E4%B9%B0%E5%A1%91%E8%BA%AB%E5%86%85%E8%A1%A3%E7%A9%BF%23) `94.4K 🔥`
1. [马兴瑞被查新疆表态](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%85%B4%E7%91%9E%E8%A2%AB%E6%9F%A5%E6%96%B0%E7%96%86%E8%A1%A8%E6%80%81%23) `87.7K 🔥`
1. [鹿晗真破音](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E7%9C%9F%E7%A0%B4%E9%9F%B3%23) `85.3K 🔥`
1. [印度女子好心给水喝反遭强奸](https://s.weibo.com/weibo?q=%23%E5%8D%B0%E5%BA%A6%E5%A5%B3%E5%AD%90%E5%A5%BD%E5%BF%83%E7%BB%99%E6%B0%B4%E5%96%9D%E5%8F%8D%E9%81%AD%E5%BC%BA%E5%A5%B8%23) `85.2K 🔥`
1. [WB对战KSG](https://s.weibo.com/weibo?q=%23WB%E5%AF%B9%E6%88%98KSG%23) `80.1K 🔥`
1. [十日终焉 (End of ten days)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%23) `70.5K 🔥`
1. [杨紫看了黄灿灿初舞台 (Yang Zi watched Huang Cancan’s first stage)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%9C%8B%E4%BA%86%E9%BB%84%E7%81%BF%E7%81%BF%E5%88%9D%E8%88%9E%E5%8F%B0%23) `67.7K 🔥`
1. [iG战胜TES](https://s.weibo.com/weibo?q=%23iG%E6%88%98%E8%83%9CTES%23) `66.2K 🔥`
1. [范玮琪希望网友不要被舆论带偏](https://s.weibo.com/weibo?q=%23%E8%8C%83%E7%8E%AE%E7%90%AA%E5%B8%8C%E6%9C%9B%E7%BD%91%E5%8F%8B%E4%B8%8D%E8%A6%81%E8%A2%AB%E8%88%86%E8%AE%BA%E5%B8%A6%E5%81%8F%23) `65.4K 🔥`
1. [刘耀文举宋亚轩路透 (Liu Yaowen selected Song Yaxuan Reuters)](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%80%80%E6%96%87%E4%B8%BE%E5%AE%8B%E4%BA%9A%E8%BD%A9%E8%B7%AF%E9%80%8F%23) `64.8K 🔥`
1. [陈幸同0比11申裕斌 (Chen Xingtong 0-11 Shen Yubin)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%B9%B8%E5%90%8C0%E6%AF%9411%E7%94%B3%E8%A3%95%E6%96%8C%23) `810.2K 🔥` `-27%`
1. [许昕说孙颖莎赢得侥幸](https://s.weibo.com/weibo?q=%23%E8%AE%B8%E6%98%95%E8%AF%B4%E5%AD%99%E9%A2%96%E8%8E%8E%E8%B5%A2%E5%BE%97%E4%BE%A5%E5%B9%B8%23) `133.4K 🔥` `-83%`
1. [伊朗驻华大使馆发布战果 (The Iranian Embassy in China released the results of the battle)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A9%BB%E5%8D%8E%E5%A4%A7%E4%BD%BF%E9%A6%86%E5%8F%91%E5%B8%83%E6%88%98%E6%9E%9C%23) `132.5K 🔥` `-41%`
1. [高铁站禁烟仅1天男子当众吸烟被拍 (Only one day after smoking was banned at a high-speed rail station, a man was photographed smoking in public)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%93%81%E7%AB%99%E7%A6%81%E7%83%9F%E4%BB%851%E5%A4%A9%E7%94%B7%E5%AD%90%E5%BD%93%E4%BC%97%E5%90%B8%E7%83%9F%E8%A2%AB%E6%8B%8D%23) `131.1K 🔥` `-49%`
1. [白日提灯反派骂女主台词](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E5%8F%8D%E6%B4%BE%E9%AA%82%E5%A5%B3%E4%B8%BB%E5%8F%B0%E8%AF%8D%23) `127.8K 🔥` `-38%`
1. [狗 爷爷这么做一定有他的道理](https://s.weibo.com/weibo?q=%23%E7%8B%97%20%E7%88%B7%E7%88%B7%E8%BF%99%E4%B9%88%E5%81%9A%E4%B8%80%E5%AE%9A%E6%9C%89%E4%BB%96%E7%9A%84%E9%81%93%E7%90%86%23) `126.9K 🔥` `-28%`
1. [陈幸同vs申裕斌 (Chen Xingtong vs. Shin Yubin)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%B9%B8%E5%90%8Cvs%E7%94%B3%E8%A3%95%E6%96%8C%23) `96.3K 🔥` `-54%`
1. [赵子琪回应浪姐唯一人脉](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E5%AD%90%E7%90%AA%E5%9B%9E%E5%BA%94%E6%B5%AA%E5%A7%90%E5%94%AF%E4%B8%80%E4%BA%BA%E8%84%89%23) `89.5K 🔥` `-24%`
1. [埃及一航班行李全部丢失](https://s.weibo.com/weibo?q=%23%E5%9F%83%E5%8F%8A%E4%B8%80%E8%88%AA%E7%8F%AD%E8%A1%8C%E6%9D%8E%E5%85%A8%E9%83%A8%E4%B8%A2%E5%A4%B1%23) `79.7K 🔥` `-35%`
1. [逼出最强孙颖莎的高达才18岁 (The Gundam that forced out the strongest Sun Yingsha was only 18 years old)](https://s.weibo.com/weibo?q=%23%E9%80%BC%E5%87%BA%E6%9C%80%E5%BC%BA%E5%AD%99%E9%A2%96%E8%8E%8E%E7%9A%84%E9%AB%98%E8%BE%BE%E6%89%8D18%E5%B2%81%23) `76.9K 🔥` `-29%`
1. [易军怒斥张雪机车被无底线消费](https://s.weibo.com/weibo?q=%23%E6%98%93%E5%86%9B%E6%80%92%E6%96%A5%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E8%A2%AB%E6%97%A0%E5%BA%95%E7%BA%BF%E6%B6%88%E8%B4%B9%23) `65.7K 🔥` `-73%`

Updated at 2026-04-04 19:55:35

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
