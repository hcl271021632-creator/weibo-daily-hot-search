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

1. [1200多家饭店拍黄瓜被举报 (More than 1,200 restaurants were reported for taking pictures of cucumbers)](https://s.weibo.com/weibo?q=%231200%E5%A4%9A%E5%AE%B6%E9%A5%AD%E5%BA%97%E6%8B%8D%E9%BB%84%E7%93%9C%E8%A2%AB%E4%B8%BE%E6%8A%A5%23) `1.1M 🔥` `NEW`
1. [网警破获网络开盒案守护网络空间安全](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%AD%A6%E7%A0%B4%E8%8E%B7%E7%BD%91%E7%BB%9C%E5%BC%80%E7%9B%92%E6%A1%88%E5%AE%88%E6%8A%A4%E7%BD%91%E7%BB%9C%E7%A9%BA%E9%97%B4%E5%AE%89%E5%85%A8%23) `590.7K 🔥` `NEW`
1. [希林娜依高伯克利七年没毕业](https://s.weibo.com/weibo?q=%23%E5%B8%8C%E6%9E%97%E5%A8%9C%E4%BE%9D%E9%AB%98%E4%BC%AF%E5%85%8B%E5%88%A9%E4%B8%83%E5%B9%B4%E6%B2%A1%E6%AF%95%E4%B8%9A%23) `537.6K 🔥` `NEW`
1. [梅姨](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%23) `266.0K 🔥` `NEW`
1. [魏家凉皮汉堡](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E5%AE%B6%E5%87%89%E7%9A%AE%E6%B1%89%E5%A0%A1%23) `171.0K 🔥` `NEW`
1. [梅姨在广州三元里落网为不实消息](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%9C%A8%E5%B9%BF%E5%B7%9E%E4%B8%89%E5%85%83%E9%87%8C%E8%90%BD%E7%BD%91%E4%B8%BA%E4%B8%8D%E5%AE%9E%E6%B6%88%E6%81%AF%23) `154.3K 🔥` `NEW`
1. [AI演员签约官宣](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%E7%AD%BE%E7%BA%A6%E5%AE%98%E5%AE%A3%23) `151.5K 🔥` `NEW`
1. [沙特要求伊朗武官24小时内离境](https://s.weibo.com/weibo?q=%23%E6%B2%99%E7%89%B9%E8%A6%81%E6%B1%82%E4%BC%8A%E6%9C%97%E6%AD%A6%E5%AE%9824%E5%B0%8F%E6%97%B6%E5%86%85%E7%A6%BB%E5%A2%83%23) `148.2K 🔥` `NEW`
1. [小米SU7Pro一充跑通京沪](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3SU7Pro%E4%B8%80%E5%85%85%E8%B7%91%E9%80%9A%E4%BA%AC%E6%B2%AA%23) `140.1K 🔥` `NEW`
1. [逐玉亲到腿软的路透要播了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%B2%E5%88%B0%E8%85%BF%E8%BD%AF%E7%9A%84%E8%B7%AF%E9%80%8F%E8%A6%81%E6%92%AD%E4%BA%86%23) `139.7K 🔥` `NEW`
1. [陈飞宇迪丽热巴5年前拍的杂志 (Magazines photographed by Chen Feiyu and Di Lieba 5 years ago)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B45%E5%B9%B4%E5%89%8D%E6%8B%8D%E7%9A%84%E6%9D%82%E5%BF%97%23) `139.2K 🔥` `NEW`
1. [最快女护士张水华丽水马拉松夺冠](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BF%AB%E5%A5%B3%E6%8A%A4%E5%A3%AB%E5%BC%A0%E6%B0%B4%E5%8D%8E%E4%B8%BD%E6%B0%B4%E9%A9%AC%E6%8B%89%E6%9D%BE%E5%A4%BA%E5%86%A0%23) `137.3K 🔥` `NEW`
1. [警方介入女子追打2岁宝宝](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E4%BB%8B%E5%85%A5%E5%A5%B3%E5%AD%90%E8%BF%BD%E6%89%932%E5%B2%81%E5%AE%9D%E5%AE%9D%23) `135.0K 🔥` `NEW`
1. [逐玉男配林沐然涨粉101万](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%94%B7%E9%85%8D%E6%9E%97%E6%B2%90%E7%84%B6%E6%B6%A8%E7%B2%89101%E4%B8%87%23) `134.5K 🔥` `NEW`
1. [半小时取鱼刺7小时修路震惊老外](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E5%B0%8F%E6%97%B6%E5%8F%96%E9%B1%BC%E5%88%BA7%E5%B0%8F%E6%97%B6%E4%BF%AE%E8%B7%AF%E9%9C%87%E6%83%8A%E8%80%81%E5%A4%96%23) `134.5K 🔥` `NEW`
1. [山东事业编](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E4%B8%9C%E4%BA%8B%E4%B8%9A%E7%BC%96%23) `134.2K 🔥` `NEW`
1. [曝迪丽热巴团队重整](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%9B%A2%E9%98%9F%E9%87%8D%E6%95%B4%23) `134.1K 🔥` `NEW`
1. [虞书欣云初令杀青上班路透](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%BA%91%E5%88%9D%E4%BB%A4%E6%9D%80%E9%9D%92%E4%B8%8A%E7%8F%AD%E8%B7%AF%E9%80%8F%23) `120.0K 🔥` `NEW`
1. [深圳垃圾量46年暴涨超3000倍](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E5%9E%83%E5%9C%BE%E9%87%8F46%E5%B9%B4%E6%9A%B4%E6%B6%A8%E8%B6%853000%E5%80%8D%23) `100.9K 🔥` `NEW`
1. [千问崩了](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%B4%A9%E4%BA%86%23) `98.0K 🔥` `NEW`
1. [倪妮20秒无台词眼神戏 (Ni Ni’s 20-second speechless eye scene)](https://s.weibo.com/weibo?q=%23%E5%80%AA%E5%A6%AE20%E7%A7%92%E6%97%A0%E5%8F%B0%E8%AF%8D%E7%9C%BC%E7%A5%9E%E6%88%8F%23) `83.1K 🔥` `NEW`
1. [美学者称伊朗战事对中国经济影响有限](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AD%A6%E8%80%85%E7%A7%B0%E4%BC%8A%E6%9C%97%E6%88%98%E4%BA%8B%E5%AF%B9%E4%B8%AD%E5%9B%BD%E7%BB%8F%E6%B5%8E%E5%BD%B1%E5%93%8D%E6%9C%89%E9%99%90%23) `76.5K 🔥` `NEW`
1. [伊朗官宣导弹工业将获满分](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%98%E5%AE%A3%E5%AF%BC%E5%BC%B9%E5%B7%A5%E4%B8%9A%E5%B0%86%E8%8E%B7%E6%BB%A1%E5%88%86%23) `76.0K 🔥` `NEW`
1. [重庆大学电镜中心耗资1.2亿元建成](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E5%A4%A7%E5%AD%A6%E7%94%B5%E9%95%9C%E4%B8%AD%E5%BF%83%E8%80%97%E8%B5%841.2%E4%BA%BF%E5%85%83%E5%BB%BA%E6%88%90%23) `75.0K 🔥` `NEW`
1. [香港大劫案5人落网73公斤黄金找回](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%8A%AB%E6%A1%885%E4%BA%BA%E8%90%BD%E7%BD%9173%E5%85%AC%E6%96%A4%E9%BB%84%E9%87%91%E6%89%BE%E5%9B%9E%23) `70.3K 🔥` `NEW`
1. [谢霆锋演唱会老辈子疼人没轻没重](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E9%9C%86%E9%94%8B%E6%BC%94%E5%94%B1%E4%BC%9A%E8%80%81%E8%BE%88%E5%AD%90%E7%96%BC%E4%BA%BA%E6%B2%A1%E8%BD%BB%E6%B2%A1%E9%87%8D%23) `68.2K 🔥` `NEW`
1. [家属谈派出所遭猥亵女儿现状](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E5%B1%9E%E8%B0%88%E6%B4%BE%E5%87%BA%E6%89%80%E9%81%AD%E7%8C%A5%E4%BA%B5%E5%A5%B3%E5%84%BF%E7%8E%B0%E7%8A%B6%23) `66.0K 🔥` `NEW`
1. [非油炸 文字游戏](https://s.weibo.com/weibo?q=%23%E9%9D%9E%E6%B2%B9%E7%82%B8%20%E6%96%87%E5%AD%97%E6%B8%B8%E6%88%8F%23) `64.9K 🔥` `NEW`
1. [电竞也有自己的微博King](https://s.weibo.com/weibo?q=%23%E7%94%B5%E7%AB%9E%E4%B9%9F%E6%9C%89%E8%87%AA%E5%B7%B1%E7%9A%84%E5%BE%AE%E5%8D%9AKing%23) `64.1K 🔥` `NEW`
1. [济南一景区多人空地上打滚跪拜](https://s.weibo.com/weibo?q=%23%E6%B5%8E%E5%8D%97%E4%B8%80%E6%99%AF%E5%8C%BA%E5%A4%9A%E4%BA%BA%E7%A9%BA%E5%9C%B0%E4%B8%8A%E6%89%93%E6%BB%9A%E8%B7%AA%E6%8B%9C%23) `64.0K 🔥` `NEW`
1. [火箭绝杀热火 (Rockets beat Heat)](https://s.weibo.com/weibo?q=%23%E7%81%AB%E7%AE%AD%E7%BB%9D%E6%9D%80%E7%83%AD%E7%81%AB%23) `63.0K 🔥` `NEW`
1. [全国多地加油站排长队](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E5%A4%9A%E5%9C%B0%E5%8A%A0%E6%B2%B9%E7%AB%99%E6%8E%92%E9%95%BF%E9%98%9F%23) `62.7K 🔥` `NEW`
1. [不会跳绳的学生遇到了最耐心的老师](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BC%9A%E8%B7%B3%E7%BB%B3%E7%9A%84%E5%AD%A6%E7%94%9F%E9%81%87%E5%88%B0%E4%BA%86%E6%9C%80%E8%80%90%E5%BF%83%E7%9A%84%E8%80%81%E5%B8%88%23) `62.3K 🔥` `NEW`
1. [梅姨到哪也不出示身份证 (Aunt Mei never shows her ID card wherever she goes.)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%88%B0%E5%93%AA%E4%B9%9F%E4%B8%8D%E5%87%BA%E7%A4%BA%E8%BA%AB%E4%BB%BD%E8%AF%81%23) `754.3K 🔥`
1. [逐玉反盗版声明](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8D%E7%9B%97%E7%89%88%E5%A3%B0%E6%98%8E%23) `261.0K 🔥`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `134.9K 🔥`
1. [梅姨假装答应同居老人领证后失联](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%81%87%E8%A3%85%E7%AD%94%E5%BA%94%E5%90%8C%E5%B1%85%E8%80%81%E4%BA%BA%E9%A2%86%E8%AF%81%E5%90%8E%E5%A4%B1%E8%81%94%23) `134.8K 🔥`
1. [逐玉 超点](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E8%B6%85%E7%82%B9%23) `165.0K 🔥` `-32%`
1. [伊朗回应特朗普袭击电厂威胁](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E8%A2%AD%E5%87%BB%E7%94%B5%E5%8E%82%E5%A8%81%E8%83%81%23) `155.3K 🔥` `-33%`
1. [张佳宁说单眼皮因拍戏变不回来了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BD%B3%E5%AE%81%E8%AF%B4%E5%8D%95%E7%9C%BC%E7%9A%AE%E5%9B%A0%E6%8B%8D%E6%88%8F%E5%8F%98%E4%B8%8D%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `144.5K 🔥` `-35%`
1. [逐玉的兵 不贪盗版](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%9A%84%E5%85%B5%20%E4%B8%8D%E8%B4%AA%E7%9B%97%E7%89%88%23) `143.0K 🔥` `-36%`
1. [男子因睡眠呼吸暂停1年撞坏3辆车 (Man crashes 3 cars in 1 year due to sleep apnea)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%9B%A0%E7%9D%A1%E7%9C%A0%E5%91%BC%E5%90%B8%E6%9A%82%E5%81%9C1%E5%B9%B4%E6%92%9E%E5%9D%8F3%E8%BE%86%E8%BD%A6%23) `136.8K 🔥` `-46%`
1. [逐玉 盗版没弹幕快乐少一半](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%9B%97%E7%89%88%E6%B2%A1%E5%BC%B9%E5%B9%95%E5%BF%AB%E4%B9%90%E5%B0%91%E4%B8%80%E5%8D%8A%23) `134.3K 🔥` `-36%`
1. [吃到了上学时独来独往的红利](https://s.weibo.com/weibo?q=%23%E5%90%83%E5%88%B0%E4%BA%86%E4%B8%8A%E5%AD%A6%E6%97%B6%E7%8B%AC%E6%9D%A5%E7%8B%AC%E5%BE%80%E7%9A%84%E7%BA%A2%E5%88%A9%23) `129.0K 🔥` `-38%`
1. [刘宇宁直播麻药劲还没过](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E7%9B%B4%E6%92%AD%E9%BA%BB%E8%8D%AF%E5%8A%B2%E8%BF%98%E6%B2%A1%E8%BF%87%23) `95.5K 🔥` `-55%`
1. [新疆一处沙漠惊现沙尘豹 (Sand leopard suddenly appears in Xinjiang desert)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E7%96%86%E4%B8%80%E5%A4%84%E6%B2%99%E6%BC%A0%E6%83%8A%E7%8E%B0%E6%B2%99%E5%B0%98%E8%B1%B9%23) `88.6K 🔥` `-60%`
1. [水原希子鞋子广告](https://s.weibo.com/weibo?q=%23%E6%B0%B4%E5%8E%9F%E5%B8%8C%E5%AD%90%E9%9E%8B%E5%AD%90%E5%B9%BF%E5%91%8A%23) `77.2K 🔥` `-46%`
1. [男子醉酒摸女孩胸部被高中生制服 (Drunk man touched girl's breast and was restrained by high school student)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%86%89%E9%85%92%E6%91%B8%E5%A5%B3%E5%AD%A9%E8%83%B8%E9%83%A8%E8%A2%AB%E9%AB%98%E4%B8%AD%E7%94%9F%E5%88%B6%E6%9C%8D%23) `76.2K 🔥` `-45%`
1. [在家吃饭可以懒到什么程度](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%AE%B6%E5%90%83%E9%A5%AD%E5%8F%AF%E4%BB%A5%E6%87%92%E5%88%B0%E4%BB%80%E4%B9%88%E7%A8%8B%E5%BA%A6%23) `65.2K 🔥` `-55%`
1. [张元英水手服](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%85%83%E8%8B%B1%E6%B0%B4%E6%89%8B%E6%9C%8D%23) `64.9K 🔥` `-37%`

Updated at 2026-03-22 13:03:22

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
