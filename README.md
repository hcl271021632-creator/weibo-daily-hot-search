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

1. [亲爱的客栈慢综白月光回宫 (Dear Inn slowly returns to the palace in white moonlight)](https://s.weibo.com/weibo?q=%23%E4%BA%B2%E7%88%B1%E7%9A%84%E5%AE%A2%E6%A0%88%E6%85%A2%E7%BB%BC%E7%99%BD%E6%9C%88%E5%85%89%E5%9B%9E%E5%AE%AB%23) `246.2K 🔥` `NEW`
1. [无限期退出娱乐圈除非有商务](https://s.weibo.com/weibo?q=%23%E6%97%A0%E9%99%90%E6%9C%9F%E9%80%80%E5%87%BA%E5%A8%B1%E4%B9%90%E5%9C%88%E9%99%A4%E9%9D%9E%E6%9C%89%E5%95%86%E5%8A%A1%23) `230.6K 🔥` `NEW`
1. [负责林孝埈的韩国籍康复教练被解雇](https://s.weibo.com/weibo?q=%23%E8%B4%9F%E8%B4%A3%E6%9E%97%E5%AD%9D%E5%9F%88%E7%9A%84%E9%9F%A9%E5%9B%BD%E7%B1%8D%E5%BA%B7%E5%A4%8D%E6%95%99%E7%BB%83%E8%A2%AB%E8%A7%A3%E9%9B%87%23) `219.4K 🔥` `NEW`
1. [BLG战胜WBG](https://s.weibo.com/weibo?q=%23BLG%E6%88%98%E8%83%9CWBG%23) `218.6K 🔥` `NEW`
1. [郑业成演技](https://s.weibo.com/weibo?q=%23%E9%83%91%E4%B8%9A%E6%88%90%E6%BC%94%E6%8A%80%23) `172.4K 🔥` `NEW`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `115.8K 🔥` `NEW`
1. [孙颖莎3比1石洵瑶](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E3%E6%AF%941%E7%9F%B3%E6%B4%B5%E7%91%B6%23) `111.1K 🔥` `NEW`
1. [种地吧](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `106.4K 🔥` `NEW`
1. [桃黑黑迟到](https://s.weibo.com/weibo?q=%23%E6%A1%83%E9%BB%91%E9%BB%91%E8%BF%9F%E5%88%B0%23) `102.8K 🔥` `NEW`
1. [RW 选错英雄](https://s.weibo.com/weibo?q=%23RW%20%E9%80%89%E9%94%99%E8%8B%B1%E9%9B%84%23) `93.3K 🔥` `NEW`
1. [马桶才需要一直冲 (The toilet needs to be flushed all the time)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%A1%B6%E6%89%8D%E9%9C%80%E8%A6%81%E4%B8%80%E7%9B%B4%E5%86%B2%23) `90.1K 🔥` `NEW`
1. [美团外卖送开工好礼](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%A2%E5%A4%96%E5%8D%96%E9%80%81%E5%BC%80%E5%B7%A5%E5%A5%BD%E7%A4%BC%23) `487.9K 🔥` `+30%`
1. [一点点资助男孩长期班级前三](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E9%95%BF%E6%9C%9F%E7%8F%AD%E7%BA%A7%E5%89%8D%E4%B8%89%23) `459.2K 🔥` `+55%`
1. [林俊杰回复张凌赫](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E5%9B%9E%E5%A4%8D%E5%BC%A0%E5%87%8C%E8%B5%AB%23) `235.9K 🔥` `+111%`
1. [王皓开玩笑说王楚钦的签名我哪会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%9A%93%E5%BC%80%E7%8E%A9%E7%AC%91%E8%AF%B4%E7%8E%8B%E6%A5%9A%E9%92%A6%E7%9A%84%E7%AD%BE%E5%90%8D%E6%88%91%E5%93%AA%E4%BC%9A%23) `230.4K 🔥` `+24%`
1. [AG对战RW](https://s.weibo.com/weibo?q=%23AG%E5%AF%B9%E6%88%98RW%23) `150.8K 🔥` `+58%`
1. [提醒在伊朗的中国公民尽快撤离 (Chinese citizens in Iran are reminded to evacuate as soon as possible)](https://s.weibo.com/weibo?q=%23%E6%8F%90%E9%86%92%E5%9C%A8%E4%BC%8A%E6%9C%97%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E5%B0%BD%E5%BF%AB%E6%92%A4%E7%A6%BB%23) `1.2M 🔥`
1. [草莓价格跌至1元一斤 (Strawberry price drops to 1 yuan per pound)](https://s.weibo.com/weibo?q=%23%E8%8D%89%E8%8E%93%E4%BB%B7%E6%A0%BC%E8%B7%8C%E8%87%B31%E5%85%83%E4%B8%80%E6%96%A4%23) `863.9K 🔥`
1. [数读春节消费市场年味十足 (Digital reading of the Spring Festival consumer market is full of new year flavor)](https://s.weibo.com/weibo?q=%23%E6%95%B0%E8%AF%BB%E6%98%A5%E8%8A%82%E6%B6%88%E8%B4%B9%E5%B8%82%E5%9C%BA%E5%B9%B4%E5%91%B3%E5%8D%81%E8%B6%B3%23) `663.9K 🔥`
1. [退房的时候前台拿了个徐福记的糖纸](https://s.weibo.com/weibo?q=%23%E9%80%80%E6%88%BF%E7%9A%84%E6%97%B6%E5%80%99%E5%89%8D%E5%8F%B0%E6%8B%BF%E4%BA%86%E4%B8%AA%E5%BE%90%E7%A6%8F%E8%AE%B0%E7%9A%84%E7%B3%96%E7%BA%B8%23) `247.3K 🔥`
1. [白敬亭章若楠 二搭 (Bai Jingting, Zhang Ruonan, Er Da)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E7%AB%A0%E8%8B%A5%E6%A5%A0%20%E4%BA%8C%E6%90%AD%23) `239.2K 🔥`
1. [欧冠抽签](https://s.weibo.com/weibo?q=%23%E6%AC%A7%E5%86%A0%E6%8A%BD%E7%AD%BE%23) `230.8K 🔥`
1. [杨洋不让江山造型路透](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E9%80%A0%E5%9E%8B%E8%B7%AF%E9%80%8F%23) `230.3K 🔥`
1. [德国总理在杭州吃了西湖醋鱼东坡肉](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E5%9B%BD%E6%80%BB%E7%90%86%E5%9C%A8%E6%9D%AD%E5%B7%9E%E5%90%83%E4%BA%86%E8%A5%BF%E6%B9%96%E9%86%8B%E9%B1%BC%E4%B8%9C%E5%9D%A1%E8%82%89%23) `230.3K 🔥`
1. [下一个是谁 啊吗粽 (Who is next? Zong)](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%98%AF%E8%B0%81%20%E5%95%8A%E5%90%97%E7%B2%BD%23) `227.9K 🔥`
1. [FIBA国际篮联向中国男篮致歉](https://s.weibo.com/weibo?q=%23FIBA%E5%9B%BD%E9%99%85%E7%AF%AE%E8%81%94%E5%90%91%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE%E8%87%B4%E6%AD%89%23) `207.3K 🔥`
1. [不建议在朋友圈展示技能 (It is not recommended to show skills in the circle of friends)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%BB%BA%E8%AE%AE%E5%9C%A8%E6%9C%8B%E5%8F%8B%E5%9C%88%E5%B1%95%E7%A4%BA%E6%8A%80%E8%83%BD%23) `201.1K 🔥`
1. [杨洋的手好肿](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E7%9A%84%E6%89%8B%E5%A5%BD%E8%82%BF%23) `168.5K 🔥`
1. [李胜利的狱友repo (Li Shengli’s inmate repo)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%83%9C%E5%88%A9%E7%9A%84%E7%8B%B1%E5%8F%8Brepo%23) `150.7K 🔥`
1. [养过小孩的才知道他有多会教](https://s.weibo.com/weibo?q=%23%E5%85%BB%E8%BF%87%E5%B0%8F%E5%AD%A9%E7%9A%84%E6%89%8D%E7%9F%A5%E9%81%93%E4%BB%96%E6%9C%89%E5%A4%9A%E4%BC%9A%E6%95%99%23) `125.6K 🔥`
1. [杨幂主动问碳酸需不需要合照](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E4%B8%BB%E5%8A%A8%E9%97%AE%E7%A2%B3%E9%85%B8%E9%9C%80%E4%B8%8D%E9%9C%80%E8%A6%81%E5%90%88%E7%85%A7%23) `125.6K 🔥`
1. [李胜利唯独管GD直接叫GD](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%83%9C%E5%88%A9%E5%94%AF%E7%8B%AC%E7%AE%A1GD%E7%9B%B4%E6%8E%A5%E5%8F%ABGD%23) `125.4K 🔥`
1. [BLACKPINK回归 敷衍](https://s.weibo.com/weibo?q=%23BLACKPINK%E5%9B%9E%E5%BD%92%20%E6%95%B7%E8%A1%8D%23) `125.1K 🔥`
1. [于正新剧宣传博被说低俗](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E6%AD%A3%E6%96%B0%E5%89%A7%E5%AE%A3%E4%BC%A0%E5%8D%9A%E8%A2%AB%E8%AF%B4%E4%BD%8E%E4%BF%97%23) `122.1K 🔥`
1. [美国建议美国公民尽快离开以色列 (US advises US citizens to leave Israel as soon as possible)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%BB%BA%E8%AE%AE%E7%BE%8E%E5%9B%BD%E5%85%AC%E6%B0%91%E5%B0%BD%E5%BF%AB%E7%A6%BB%E5%BC%80%E4%BB%A5%E8%89%B2%E5%88%97%23) `116.4K 🔥`
1. [镖人破十亿刀马谛听番外](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A0%B4%E5%8D%81%E4%BA%BF%E5%88%80%E9%A9%AC%E8%B0%9B%E5%90%AC%E7%95%AA%E5%A4%96%23) `114.2K 🔥`
1. [朱志鑫直播](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E7%9B%B4%E6%92%AD%23) `110.9K 🔥`
1. [海外曝光小米神秘新车 (Xiaomi’s mysterious new car exposed overseas)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%A4%96%E6%9B%9D%E5%85%89%E5%B0%8F%E7%B1%B3%E7%A5%9E%E7%A7%98%E6%96%B0%E8%BD%A6%23) `109.1K 🔥`
1. [刘雯开场走秀气场全开](https://s.weibo.com/weibo?q=%23%E5%88%98%E9%9B%AF%E5%BC%80%E5%9C%BA%E8%B5%B0%E7%A7%80%E6%B0%94%E5%9C%BA%E5%85%A8%E5%BC%80%23) `107.6K 🔥`
1. [见春天 陈飞宇王影璐 (See Spring Chen Feiyu Wang Yinglu)](https://s.weibo.com/weibo?q=%23%E8%A7%81%E6%98%A5%E5%A4%A9%20%E9%99%88%E9%A3%9E%E5%AE%87%E7%8E%8B%E5%BD%B1%E7%92%90%23) `102.8K 🔥`
1. [宋威龙都不一定生得出这么像的](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%A8%81%E9%BE%99%E9%83%BD%E4%B8%8D%E4%B8%80%E5%AE%9A%E7%94%9F%E5%BE%97%E5%87%BA%E8%BF%99%E4%B9%88%E5%83%8F%E7%9A%84%23) `102.8K 🔥`
1. [左航直播](https://s.weibo.com/weibo?q=%23%E5%B7%A6%E8%88%AA%E7%9B%B4%E6%92%AD%23) `98.7K 🔥`
1. [大二男生攒4万为爷奶请戏班报恩](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BA%8C%E7%94%B7%E7%94%9F%E6%94%924%E4%B8%87%E4%B8%BA%E7%88%B7%E5%A5%B6%E8%AF%B7%E6%88%8F%E7%8F%AD%E6%8A%A5%E6%81%A9%23) `91.6K 🔥`
1. [妈妈在女儿婚礼上美出圈](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9C%A8%E5%A5%B3%E5%84%BF%E5%A9%9A%E7%A4%BC%E4%B8%8A%E7%BE%8E%E5%87%BA%E5%9C%88%23) `259.6K 🔥` `-21%`
1. [下一个是谁 (who is next)](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%98%AF%E8%B0%81%23) `230.7K 🔥` `-22%`
1. [现在就出发4 (Let's go now 4)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%23) `150.7K 🔥` `-25%`
1. [孙颖莎vs石洵瑶 (Sun Yingsha vs Shi Xunyao)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E7%9F%B3%E6%B4%B5%E7%91%B6%23) `150.2K 🔥` `-36%`
1. [向华强 向佐不能搞老三老四](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%8D%8E%E5%BC%BA%20%E5%90%91%E4%BD%90%E4%B8%8D%E8%83%BD%E6%90%9E%E8%80%81%E4%B8%89%E8%80%81%E5%9B%9B%23) `138.2K 🔥` `-25%`
1. [X电竞打WBG (X E-sports playing WBG)](https://s.weibo.com/weibo?q=%23X%E7%94%B5%E7%AB%9E%E6%89%93WBG%23) `125.2K 🔥` `-32%`
1. [腾讯感谢爱奇艺宣传逐玉](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E6%84%9F%E8%B0%A2%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A3%E4%BC%A0%E9%80%90%E7%8E%89%23) `114.0K 🔥` `-43%`
1. [WBG对战BLG](https://s.weibo.com/weibo?q=%23WBG%E5%AF%B9%E6%88%98BLG%23) `102.9K 🔥` `-30%`

Updated at 2026-02-27 20:01:01

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
