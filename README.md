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

1. [白日提灯定档 (Daytime lantern scheduled)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E5%AE%9A%E6%A1%A3%23) `1.2M 🔥` `NEW`
1. [32G内存涨了约3000元](https://s.weibo.com/weibo?q=%2332G%E5%86%85%E5%AD%98%E6%B6%A8%E4%BA%86%E7%BA%A63000%E5%85%83%23) `836.0K 🔥` `NEW`
1. [小猴子石山玩耍不慎坠落身亡](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%B4%E5%AD%90%E7%9F%B3%E5%B1%B1%E7%8E%A9%E8%80%8D%E4%B8%8D%E6%85%8E%E5%9D%A0%E8%90%BD%E8%BA%AB%E4%BA%A1%23) `425.0K 🔥` `NEW`
1. [南昌舰以一敌二逼退外舰细节公布](https://s.weibo.com/weibo?q=%23%E5%8D%97%E6%98%8C%E8%88%B0%E4%BB%A5%E4%B8%80%E6%95%8C%E4%BA%8C%E9%80%BC%E9%80%80%E5%A4%96%E8%88%B0%E7%BB%86%E8%8A%82%E5%85%AC%E5%B8%83%23) `283.4K 🔥` `NEW`
1. [二月二龙抬头有啥习俗](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E6%9C%88%E4%BA%8C%E9%BE%99%E6%8A%AC%E5%A4%B4%E6%9C%89%E5%95%A5%E4%B9%A0%E4%BF%97%23) `206.3K 🔥` `NEW`
1. [华为Mate80官宣新版本](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%B8%BAMate80%E5%AE%98%E5%AE%A3%E6%96%B0%E7%89%88%E6%9C%AC%23) `205.2K 🔥` `NEW`
1. [6国声明拟保障霍尔木兹海峡安全](https://s.weibo.com/weibo?q=%236%E5%9B%BD%E5%A3%B0%E6%98%8E%E6%8B%9F%E4%BF%9D%E9%9A%9C%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%AE%89%E5%85%A8%23) `201.9K 🔥` `NEW`
1. [湖人vs热火](https://s.weibo.com/weibo?q=%23%E6%B9%96%E4%BA%BAvs%E7%83%AD%E7%81%AB%23) `182.5K 🔥` `NEW`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `182.5K 🔥` `NEW`
1. [孟羽童再上初入职场和董明珠说了](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E7%BE%BD%E7%AB%A5%E5%86%8D%E4%B8%8A%E5%88%9D%E5%85%A5%E8%81%8C%E5%9C%BA%E5%92%8C%E8%91%A3%E6%98%8E%E7%8F%A0%E8%AF%B4%E4%BA%86%23) `182.3K 🔥` `NEW`
1. [1分钟恶意别车8次是公然行凶 (Badly turning away 8 times in 1 minute is a blatant act of violence)](https://s.weibo.com/weibo?q=%231%E5%88%86%E9%92%9F%E6%81%B6%E6%84%8F%E5%88%AB%E8%BD%A68%E6%AC%A1%E6%98%AF%E5%85%AC%E7%84%B6%E8%A1%8C%E5%87%B6%23) `182.2K 🔥` `NEW`
1. [武大靖自曝退役后现状](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E5%A4%A7%E9%9D%96%E8%87%AA%E6%9B%9D%E9%80%80%E5%BD%B9%E5%90%8E%E7%8E%B0%E7%8A%B6%23) `182.0K 🔥` `NEW`
1. [二月二龙抬头应该吃点啥](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E6%9C%88%E4%BA%8C%E9%BE%99%E6%8A%AC%E5%A4%B4%E5%BA%94%E8%AF%A5%E5%90%83%E7%82%B9%E5%95%A5%23) `181.9K 🔥` `NEW`
1. [热巴好汹涌的爱意](https://s.weibo.com/weibo?q=%23%E7%83%AD%E5%B7%B4%E5%A5%BD%E6%B1%B9%E6%B6%8C%E7%9A%84%E7%88%B1%E6%84%8F%23) `181.7K 🔥` `NEW`
1. [李卿饭撒 没轻没重](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%8D%BF%E9%A5%AD%E6%92%92%20%E6%B2%A1%E8%BD%BB%E6%B2%A1%E9%87%8D%23) `181.7K 🔥` `NEW`
1. [女子罕见双子宫双阴道10年3次剖宫产](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%BD%95%E8%A7%81%E5%8F%8C%E5%AD%90%E5%AE%AB%E5%8F%8C%E9%98%B4%E9%81%9310%E5%B9%B43%E6%AC%A1%E5%89%96%E5%AE%AB%E4%BA%A7%23) `181.3K 🔥` `NEW`
1. [泡过胖东来馒头的水清澈见底](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E8%BF%87%E8%83%96%E4%B8%9C%E6%9D%A5%E9%A6%92%E5%A4%B4%E7%9A%84%E6%B0%B4%E6%B8%85%E6%BE%88%E8%A7%81%E5%BA%95%23) `181.2K 🔥` `NEW`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `181.2K 🔥` `NEW`
1. [金价暴跌真凶](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%9A%B4%E8%B7%8C%E7%9C%9F%E5%87%B6%23) `165.3K 🔥` `NEW`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `161.8K 🔥` `NEW`
1. [泡泡玛特回应7年前买的盲盒才发货 (Bubble Mart responded that the blind box purchased 7 years ago was shipped only)](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E6%B3%A1%E7%8E%9B%E7%89%B9%E5%9B%9E%E5%BA%947%E5%B9%B4%E5%89%8D%E4%B9%B0%E7%9A%84%E7%9B%B2%E7%9B%92%E6%89%8D%E5%8F%91%E8%B4%A7%23) `120.2K 🔥` `NEW`
1. [女孩玩拼豆突然起火秒拔电源插头](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E7%8E%A9%E6%8B%BC%E8%B1%86%E7%AA%81%E7%84%B6%E8%B5%B7%E7%81%AB%E7%A7%92%E6%8B%94%E7%94%B5%E6%BA%90%E6%8F%92%E5%A4%B4%23) `119.9K 🔥` `NEW`
1. [去世演员通过AI重返银幕](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E4%B8%96%E6%BC%94%E5%91%98%E9%80%9A%E8%BF%87AI%E9%87%8D%E8%BF%94%E9%93%B6%E5%B9%95%23) `112.5K 🔥` `NEW`
1. [女生监控里看到外公家暴外婆](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E7%9B%91%E6%8E%A7%E9%87%8C%E7%9C%8B%E5%88%B0%E5%A4%96%E5%85%AC%E5%AE%B6%E6%9A%B4%E5%A4%96%E5%A9%86%23) `108.3K 🔥` `NEW`
1. [张译张小斐担任天坛奖评委](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%AF%91%E5%BC%A0%E5%B0%8F%E6%96%90%E6%8B%85%E4%BB%BB%E5%A4%A9%E5%9D%9B%E5%A5%96%E8%AF%84%E5%A7%94%23) `107.4K 🔥` `NEW`
1. [檀健次晒蛋糕](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%E6%99%92%E8%9B%8B%E7%B3%95%23) `95.4K 🔥` `NEW`
1. [美向中东三国提供165亿美元军售](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%90%91%E4%B8%AD%E4%B8%9C%E4%B8%89%E5%9B%BD%E6%8F%90%E4%BE%9B165%E4%BA%BF%E7%BE%8E%E5%85%83%E5%86%9B%E5%94%AE%23) `86.0K 🔥` `NEW`
1. [瞿颖仁科凭真实赢麻了](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E4%BB%81%E7%A7%91%E5%87%AD%E7%9C%9F%E5%AE%9E%E8%B5%A2%E9%BA%BB%E4%BA%86%23) `79.8K 🔥` `NEW`
1. [青岛这碗面够人回味一辈子](https://s.weibo.com/weibo?q=%23%E9%9D%92%E5%B2%9B%E8%BF%99%E7%A2%97%E9%9D%A2%E5%A4%9F%E4%BA%BA%E5%9B%9E%E5%91%B3%E4%B8%80%E8%BE%88%E5%AD%90%23) `77.2K 🔥` `NEW`
1. [东契奇60分](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E5%A5%91%E5%A5%8760%E5%88%86%23) `75.7K 🔥` `NEW`
1. [坐等BTS回归 (Waiting for BTS to come back)](https://s.weibo.com/weibo?q=%23%E5%9D%90%E7%AD%89BTS%E5%9B%9E%E5%BD%92%23) `69.6K 🔥` `NEW`
1. [油价究竟能涨到多高](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E7%A9%B6%E7%AB%9F%E8%83%BD%E6%B6%A8%E5%88%B0%E5%A4%9A%E9%AB%98%23) `68.4K 🔥` `NEW`
1. [黄金仍有很大下跌空间](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E4%BB%8D%E6%9C%89%E5%BE%88%E5%A4%A7%E4%B8%8B%E8%B7%8C%E7%A9%BA%E9%97%B4%23) `68.3K 🔥` `NEW`
1. [申裕斌甜蜜暴击](https://s.weibo.com/weibo?q=%23%E7%94%B3%E8%A3%95%E6%96%8C%E7%94%9C%E8%9C%9C%E6%9A%B4%E5%87%BB%23) `67.4K 🔥` `NEW`
1. [周杰伦第三支预告上线](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E7%AC%AC%E4%B8%89%E6%94%AF%E9%A2%84%E5%91%8A%E4%B8%8A%E7%BA%BF%23) `64.4K 🔥` `NEW`
1. [武汉樱花](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E6%B1%89%E6%A8%B1%E8%8A%B1%23) `63.9K 🔥` `NEW`
1. [上海迪士尼10岁生日盛大开启 (Shanghai Disney’s 10th birthday kicks off grandly)](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E8%BF%AA%E5%A3%AB%E5%B0%BC10%E5%B2%81%E7%94%9F%E6%97%A5%E7%9B%9B%E5%A4%A7%E5%BC%80%E5%90%AF%23) `206.3K 🔥` `+641%`
1. [原著谢征和长玉提了分手 (In the original work, Xie Zheng and Chang Yu broke up)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E8%91%97%E8%B0%A2%E5%BE%81%E5%92%8C%E9%95%BF%E7%8E%89%E6%8F%90%E4%BA%86%E5%88%86%E6%89%8B%23) `182.1K 🔥` `+43%`
1. [巴西女子嫁给布娃娃还连生4子](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E8%A5%BF%E5%A5%B3%E5%AD%90%E5%AB%81%E7%BB%99%E5%B8%83%E5%A8%83%E5%A8%83%E8%BF%98%E8%BF%9E%E7%94%9F4%E5%AD%90%23) `181.6K 🔥` `+77%`
1. [伊朗导弹击中以色列海法炼油厂 (Iranian missile hits Israeli oil refinery in Haifa)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%87%BB%E4%B8%AD%E4%BB%A5%E8%89%B2%E5%88%97%E6%B5%B7%E6%B3%95%E7%82%BC%E6%B2%B9%E5%8E%82%23) `181.5K 🔥` `+68%`
1. [十五五规划纲要撰写的幕后 (Behind the scenes of writing the outline of the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E7%BA%B2%E8%A6%81%E6%92%B0%E5%86%99%E7%9A%84%E5%B9%95%E5%90%8E%23) `697.9K 🔥`
1. [一觉醒来黄金挂坠亏了2000元](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%A7%89%E9%86%92%E6%9D%A5%E9%BB%84%E9%87%91%E6%8C%82%E5%9D%A0%E4%BA%8F%E4%BA%862000%E5%85%83%23) `91.9K 🔥`
1. [山姆回应三文鱼标注加热却被生食 (Sam responded to salmon being labeled as heated but eaten raw)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E5%9B%9E%E5%BA%94%E4%B8%89%E6%96%87%E9%B1%BC%E6%A0%87%E6%B3%A8%E5%8A%A0%E7%83%AD%E5%8D%B4%E8%A2%AB%E7%94%9F%E9%A3%9F%23) `83.8K 🔥`
1. [7年前买的泡泡玛特盲盒才发货 (The Bubble Mart blind box I bought 7 years ago was just shipped.)](https://s.weibo.com/weibo?q=%237%E5%B9%B4%E5%89%8D%E4%B9%B0%E7%9A%84%E6%B3%A1%E6%B3%A1%E7%8E%9B%E7%89%B9%E7%9B%B2%E7%9B%92%E6%89%8D%E5%8F%91%E8%B4%A7%23) `182.6K 🔥` `-82%`
1. [美国女教师用蛋糕引诱性侵学生](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%A5%B3%E6%95%99%E5%B8%88%E7%94%A8%E8%9B%8B%E7%B3%95%E5%BC%95%E8%AF%B1%E6%80%A7%E4%BE%B5%E5%AD%A6%E7%94%9F%23) `80.0K 🔥` `-26%`
1. [春分 (spring equinox)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%88%86%23) `79.2K 🔥` `-43%`
1. [神秘人花7500元预存500碗面 (A mysterious man spent 7,500 yuan to reserve 500 bowls of noodles)](https://s.weibo.com/weibo?q=%23%E7%A5%9E%E7%A7%98%E4%BA%BA%E8%8A%B17500%E5%85%83%E9%A2%84%E5%AD%98500%E7%A2%97%E9%9D%A2%23) `77.4K 🔥` `-36%`
1. [小米汽车](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%B1%BD%E8%BD%A6%23) `74.6K 🔥` `-41%`
1. [奔跑吧14 (Run 14)](https://s.weibo.com/weibo?q=%23%E5%A5%94%E8%B7%91%E5%90%A714%23) `71.6K 🔥` `-35%`
1. [伊朗称击中美军F35战机 (Iran says it hit US F35 fighter jet)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%87%BB%E4%B8%AD%E7%BE%8E%E5%86%9BF35%E6%88%98%E6%9C%BA%23) `67.1K 🔥` `-47%`

Updated at 2026-03-20 10:49:41

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
