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

1. [时装周限定惊喜抽卡 (Fashion week limited surprise card draw)](https://s.weibo.com/weibo?q=%23%E6%97%B6%E8%A3%85%E5%91%A8%E9%99%90%E5%AE%9A%E6%83%8A%E5%96%9C%E6%8A%BD%E5%8D%A1%23) `636.8K 🔥` `NEW`
1. [央视曝光活鱼麻醉剂滥用乱象](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%9B%9D%E5%85%89%E6%B4%BB%E9%B1%BC%E9%BA%BB%E9%86%89%E5%89%82%E6%BB%A5%E7%94%A8%E4%B9%B1%E8%B1%A1%23) `230.7K 🔥` `NEW`
1. [李帝努 电子烟](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%B8%9D%E5%8A%AA%20%E7%94%B5%E5%AD%90%E7%83%9F%23) `222.2K 🔥` `NEW`
1. [王鹤棣影视飓风雅迪](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%BD%B1%E8%A7%86%E9%A3%93%E9%A3%8E%E9%9B%85%E8%BF%AA%23) `211.7K 🔥` `NEW`
1. [工业酒精麻醉鱼流入市场](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%B8%9A%E9%85%92%E7%B2%BE%E9%BA%BB%E9%86%89%E9%B1%BC%E6%B5%81%E5%85%A5%E5%B8%82%E5%9C%BA%23) `207.8K 🔥` `NEW`
1. [长期运动可以解决生活中很多问题](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E8%BF%90%E5%8A%A8%E5%8F%AF%E4%BB%A5%E8%A7%A3%E5%86%B3%E7%94%9F%E6%B4%BB%E4%B8%AD%E5%BE%88%E5%A4%9A%E9%97%AE%E9%A2%98%23) `202.5K 🔥` `NEW`
1. [太湖湾音乐节](https://s.weibo.com/weibo?q=%23%E5%A4%AA%E6%B9%96%E6%B9%BE%E9%9F%B3%E4%B9%90%E8%8A%82%23) `135.5K 🔥` `NEW`
1. [薛之谦演唱会](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E6%BC%94%E5%94%B1%E4%BC%9A%23) `130.0K 🔥` `NEW`
1. [白宇演技](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%87%E6%BC%94%E6%8A%80%23) `126.7K 🔥` `NEW`
1. [逐玉热度超过苍兰诀](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%83%AD%E5%BA%A6%E8%B6%85%E8%BF%87%E8%8B%8D%E5%85%B0%E8%AF%80%23) `125.4K 🔥` `NEW`
1. [伊朗发起第74波打击 (Iran launches 74th wave of strikes)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC74%E6%B3%A2%E6%89%93%E5%87%BB%23) `106.5K 🔥` `NEW`
1. [曝伊朗导弹射程可覆盖欧洲多国首都](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%B0%84%E7%A8%8B%E5%8F%AF%E8%A6%86%E7%9B%96%E6%AC%A7%E6%B4%B2%E5%A4%9A%E5%9B%BD%E9%A6%96%E9%83%BD%23) `104.9K 🔥` `NEW`
1. [张真源 青岛](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%9C%9F%E6%BA%90%20%E9%9D%92%E5%B2%9B%23) `104.8K 🔥` `NEW`
1. [二十多岁她们确诊卵巢早衰之后](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E5%8D%81%E5%A4%9A%E5%B2%81%E5%A5%B9%E4%BB%AC%E7%A1%AE%E8%AF%8A%E5%8D%B5%E5%B7%A2%E6%97%A9%E8%A1%B0%E4%B9%8B%E5%90%8E%23) `101.2K 🔥` `NEW`
1. [穆祉丞 太湖湾音乐节](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%20%E5%A4%AA%E6%B9%96%E6%B9%BE%E9%9F%B3%E4%B9%90%E8%8A%82%23) `100.6K 🔥` `NEW`
1. [新郎新娘办结婚证遇惊喜尾号](https://s.weibo.com/weibo?q=%23%E6%96%B0%E9%83%8E%E6%96%B0%E5%A8%98%E5%8A%9E%E7%BB%93%E5%A9%9A%E8%AF%81%E9%81%87%E6%83%8A%E5%96%9C%E5%B0%BE%E5%8F%B7%23) `97.2K 🔥` `NEW`
1. [中国石化2025净利润下降36.8%](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E5%8C%962025%E5%87%80%E5%88%A9%E6%B6%A6%E4%B8%8B%E9%99%8D36.8%25%23) `94.7K 🔥` `NEW`
1. [中国石化提示提前错峰加油](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E5%8C%96%E6%8F%90%E7%A4%BA%E6%8F%90%E5%89%8D%E9%94%99%E5%B3%B0%E5%8A%A0%E6%B2%B9%23) `1.2M 🔥` `+577%`
1. [苍兰诀](https://s.weibo.com/weibo?q=%23%E8%8B%8D%E5%85%B0%E8%AF%80%23) `600.0K 🔥` `+374%`
1. [G2对战BLG](https://s.weibo.com/weibo?q=%23G2%E5%AF%B9%E6%88%98BLG%23) `364.7K 🔥` `+190%`
1. [逐玉直播 (Zhuyu live broadcast)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%9B%B4%E6%92%AD%23) `343.9K 🔥` `+60%`
1. [伊朗媒体称伊官员提出停战六项条件](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AA%92%E4%BD%93%E7%A7%B0%E4%BC%8A%E5%AE%98%E5%91%98%E6%8F%90%E5%87%BA%E5%81%9C%E6%88%98%E5%85%AD%E9%A1%B9%E6%9D%A1%E4%BB%B6%23) `312.4K 🔥` `+48%`
1. [金价上演断崖式下跌](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E4%B8%8A%E6%BC%94%E6%96%AD%E5%B4%96%E5%BC%8F%E4%B8%8B%E8%B7%8C%23) `223.5K 🔥` `+21%`
1. [内娱男流量五官大赏](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A8%B1%E7%94%B7%E6%B5%81%E9%87%8F%E4%BA%94%E5%AE%98%E5%A4%A7%E8%B5%8F%23) `218.1K 🔥` `+45%`
1. [减内脏脂肪最有效的方法 (The most effective way to reduce visceral fat)](https://s.weibo.com/weibo?q=%23%E5%87%8F%E5%86%85%E8%84%8F%E8%84%82%E8%82%AA%E6%9C%80%E6%9C%89%E6%95%88%E7%9A%84%E6%96%B9%E6%B3%95%23) `214.7K 🔥` `+24%`
1. [王鸥 何九华](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B8%A5%20%E4%BD%95%E4%B9%9D%E5%8D%8E%23) `206.4K 🔥` `+54%`
1. [茂茂你终于结婚生子了](https://s.weibo.com/weibo?q=%23%E8%8C%82%E8%8C%82%E4%BD%A0%E7%BB%88%E4%BA%8E%E7%BB%93%E5%A9%9A%E7%94%9F%E5%AD%90%E4%BA%86%23) `204.2K 🔥` `+36%`
1. [高以翔前女友BeIIa官宣怀孕 (Godfrey Gao’s ex-girlfriend BeIIa officially announces pregnancy)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%BB%A5%E7%BF%94%E5%89%8D%E5%A5%B3%E5%8F%8BBeIIa%E5%AE%98%E5%AE%A3%E6%80%80%E5%AD%95%23) `202.0K 🔥` `+55%`
1. [范世錡直播 (Fan Shiqi live broadcast)](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%96%E9%8C%A1%E7%9B%B4%E6%92%AD%23) `169.3K 🔥` `+34%`
1. [9组数据见证大国治水生动画卷 (9 sets of data testify to the animation volume of aquatic governance in a great country)](https://s.weibo.com/weibo?q=%239%E7%BB%84%E6%95%B0%E6%8D%AE%E8%A7%81%E8%AF%81%E5%A4%A7%E5%9B%BD%E6%B2%BB%E6%B0%B4%E7%94%9F%E5%8A%A8%E7%94%BB%E5%8D%B7%23) `675.1K 🔥`
1. [张凌赫的撕拉片又被热议了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9A%84%E6%92%95%E6%8B%89%E7%89%87%E5%8F%88%E8%A2%AB%E7%83%AD%E8%AE%AE%E4%BA%86%23) `228.5K 🔥`
1. [张靓颖回应do脸翻车](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9D%93%E9%A2%96%E5%9B%9E%E5%BA%94do%E8%84%B8%E7%BF%BB%E8%BD%A6%23) `226.0K 🔥`
1. [香港发生亿元黄金劫案 (Billion dollar gold robbery in Hong Kong)](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E5%8F%91%E7%94%9F%E4%BA%BF%E5%85%83%E9%BB%84%E9%87%91%E5%8A%AB%E6%A1%88%23) `216.3K 🔥`
1. [迪士尼平替把多少县城父母骗惨了](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E5%A3%AB%E5%B0%BC%E5%B9%B3%E6%9B%BF%E6%8A%8A%E5%A4%9A%E5%B0%91%E5%8E%BF%E5%9F%8E%E7%88%B6%E6%AF%8D%E9%AA%97%E6%83%A8%E4%BA%86%23) `209.4K 🔥`
1. [迪丽热巴直播](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%9B%B4%E6%92%AD%23) `200.5K 🔥`
1. [伊朗导弹在以本土砸出直径10米深坑 (Iranian missile creates a 10-meter-diameter crater in Israel)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%9C%A8%E4%BB%A5%E6%9C%AC%E5%9C%9F%E7%A0%B8%E5%87%BA%E7%9B%B4%E5%BE%8410%E7%B1%B3%E6%B7%B1%E5%9D%91%23) `192.5K 🔥`
1. [辛芷蕾 多邻国 (Xin Zhilei Duolingo)](https://s.weibo.com/weibo?q=%23%E8%BE%9B%E8%8A%B7%E8%95%BE%20%E5%A4%9A%E9%82%BB%E5%9B%BD%23) `192.0K 🔥`
1. [齐旻从未想过杀掉母妃 (Qi Min never thought of killing his mother and concubine)](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%97%BB%E4%BB%8E%E6%9C%AA%E6%83%B3%E8%BF%87%E6%9D%80%E6%8E%89%E6%AF%8D%E5%A6%83%23) `141.7K 🔥`
1. [23岁女子刚结婚一年就闭经](https://s.weibo.com/weibo?q=%2323%E5%B2%81%E5%A5%B3%E5%AD%90%E5%88%9A%E7%BB%93%E5%A9%9A%E4%B8%80%E5%B9%B4%E5%B0%B1%E9%97%AD%E7%BB%8F%23) `132.9K 🔥`
1. [汪顺亚军](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E9%A1%BA%E4%BA%9A%E5%86%9B%23) `129.4K 🔥`
1. [女子久坐便血半年后确诊癌症晚期 (Woman diagnosed with terminal cancer six months after sitting for long periods of time and having bloody stools)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%85%E5%9D%90%E4%BE%BF%E8%A1%80%E5%8D%8A%E5%B9%B4%E5%90%8E%E7%A1%AE%E8%AF%8A%E7%99%8C%E7%97%87%E6%99%9A%E6%9C%9F%23) `108.1K 🔥`
1. [方可能不能不遮热巴的太阳穴](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%8F%AF%E8%83%BD%E4%B8%8D%E8%83%BD%E4%B8%8D%E9%81%AE%E7%83%AD%E5%B7%B4%E7%9A%84%E5%A4%AA%E9%98%B3%E7%A9%B4%23) `104.8K 🔥`
1. [武汉女孩8天胖8斤喊话顺德道歉](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E6%B1%89%E5%A5%B3%E5%AD%A98%E5%A4%A9%E8%83%968%E6%96%A4%E5%96%8A%E8%AF%9D%E9%A1%BA%E5%BE%B7%E9%81%93%E6%AD%89%23) `104.6K 🔥`
1. [刚洗完澡别在浴室吹头发 (Don’t dry your hair in the bathroom right after you take a shower)](https://s.weibo.com/weibo?q=%23%E5%88%9A%E6%B4%97%E5%AE%8C%E6%BE%A1%E5%88%AB%E5%9C%A8%E6%B5%B4%E5%AE%A4%E5%90%B9%E5%A4%B4%E5%8F%91%23) `99.3K 🔥`
1. [月鳞绮纪](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%23) `94.4K 🔥`
1. [章若楠 无以言表好好演戏](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E8%8B%A5%E6%A5%A0%20%E6%97%A0%E4%BB%A5%E8%A8%80%E8%A1%A8%E5%A5%BD%E5%A5%BD%E6%BC%94%E6%88%8F%23) `92.8K 🔥`
1. [爱吃荔枝的人今年天塌了 (People who love lychees are in trouble this year)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E8%8D%94%E6%9E%9D%E7%9A%84%E4%BA%BA%E4%BB%8A%E5%B9%B4%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `842.2K 🔥` `-21%`
1. [周也 毛利兰](https://s.weibo.com/weibo?q=%23%E5%91%A8%E4%B9%9F%20%E6%AF%9B%E5%88%A9%E5%85%B0%23) `353.3K 🔥` `-26%`
1. [双汇王中王火腿肠被曝吃出两根钢钉 (Shuanghui King of Kings ham sausage was exposed to have eaten two steel nails)](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E6%B1%87%E7%8E%8B%E4%B8%AD%E7%8E%8B%E7%81%AB%E8%85%BF%E8%82%A0%E8%A2%AB%E6%9B%9D%E5%90%83%E5%87%BA%E4%B8%A4%E6%A0%B9%E9%92%A2%E9%92%89%23) `231.1K 🔥` `-69%`
1. [烤肠界的四大顶流](https://s.weibo.com/weibo?q=%23%E7%83%A4%E8%82%A0%E7%95%8C%E7%9A%84%E5%9B%9B%E5%A4%A7%E9%A1%B6%E6%B5%81%23) `143.7K 🔥` `-26%`
1. [逐玉反盗版声明 (Zhuyu Anti-Piracy Statement)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8D%E7%9B%97%E7%89%88%E5%A3%B0%E6%98%8E%23) `131.6K 🔥` `-36%`

Updated at 2026-03-22 22:02:05

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
