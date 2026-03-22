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

1. [顾客吃牛蛙天花板上掉出一条人腿 (A human leg fell out of the ceiling after a customer ate bullfrog)](https://s.weibo.com/weibo?q=%23%E9%A1%BE%E5%AE%A2%E5%90%83%E7%89%9B%E8%9B%99%E5%A4%A9%E8%8A%B1%E6%9D%BF%E4%B8%8A%E6%8E%89%E5%87%BA%E4%B8%80%E6%9D%A1%E4%BA%BA%E8%85%BF%23) `472.1K 🔥` `NEW`
1. [靳磊任深圳市委书记](https://s.weibo.com/weibo?q=%23%E9%9D%B3%E7%A3%8A%E4%BB%BB%E6%B7%B1%E5%9C%B3%E5%B8%82%E5%A7%94%E4%B9%A6%E8%AE%B0%23) `233.3K 🔥` `NEW`
1. [校长回应江浙沪没有夜生活](https://s.weibo.com/weibo?q=%23%E6%A0%A1%E9%95%BF%E5%9B%9E%E5%BA%94%E6%B1%9F%E6%B5%99%E6%B2%AA%E6%B2%A1%E6%9C%89%E5%A4%9C%E7%94%9F%E6%B4%BB%23) `191.0K 🔥` `NEW`
1. [一诺加盟我家那小子](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%AF%BA%E5%8A%A0%E7%9B%9F%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%23) `172.0K 🔥` `NEW`
1. [梅姨难抓或是因为长相太普通](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E9%9A%BE%E6%8A%93%E6%88%96%E6%98%AF%E5%9B%A0%E4%B8%BA%E9%95%BF%E7%9B%B8%E5%A4%AA%E6%99%AE%E9%80%9A%23) `130.4K 🔥` `NEW`
1. [陈慧敏怀孕了](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%85%A7%E6%95%8F%E6%80%80%E5%AD%95%E4%BA%86%23) `130.1K 🔥` `NEW`
1. [桃花坞](https://s.weibo.com/weibo?q=%23%E6%A1%83%E8%8A%B1%E5%9D%9E%23) `103.5K 🔥` `NEW`
1. [我家那小子](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%23) `80.6K 🔥` `NEW`
1. [男子连续工作16小时后宿舍猝死](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%BF%9E%E7%BB%AD%E5%B7%A5%E4%BD%9C16%E5%B0%8F%E6%97%B6%E5%90%8E%E5%AE%BF%E8%88%8D%E7%8C%9D%E6%AD%BB%23) `78.1K 🔥` `NEW`
1. [雷霆奇才爆发大规模群殴](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E9%9C%86%E5%A5%87%E6%89%8D%E7%88%86%E5%8F%91%E5%A4%A7%E8%A7%84%E6%A8%A1%E7%BE%A4%E6%AE%B4%23) `74.8K 🔥` `NEW`
1. [84消毒液用错可能致罕见病 (84 Incorrect use of disinfectant may cause rare diseases)](https://s.weibo.com/weibo?q=%2384%E6%B6%88%E6%AF%92%E6%B6%B2%E7%94%A8%E9%94%99%E5%8F%AF%E8%83%BD%E8%87%B4%E7%BD%95%E8%A7%81%E7%97%85%23) `73.9K 🔥` `NEW`
1. [伊朗再发警告](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%8D%E5%8F%91%E8%AD%A6%E5%91%8A%23) `65.4K 🔥` `NEW`
1. [周深唱白日提灯ost](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B1%E5%94%B1%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AFost%23) `61.2K 🔥` `NEW`
1. [背书背的是孔子的聊天记录](https://s.weibo.com/weibo?q=%23%E8%83%8C%E4%B9%A6%E8%83%8C%E7%9A%84%E6%98%AF%E5%AD%94%E5%AD%90%E7%9A%84%E8%81%8A%E5%A4%A9%E8%AE%B0%E5%BD%95%23) `59.8K 🔥` `NEW`
1. [高以翔前女友BeIIa官宣怀孕](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%BB%A5%E7%BF%94%E5%89%8D%E5%A5%B3%E5%8F%8BBeIIa%E5%AE%98%E5%AE%A3%E6%80%80%E5%AD%95%23) `55.2K 🔥` `NEW`
1. [冬去春来今日开播](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%8E%BB%E6%98%A5%E6%9D%A5%E4%BB%8A%E6%97%A5%E5%BC%80%E6%92%AD%23) `55.0K 🔥` `NEW`
1. [梅姨在广州三元里落网为不实消息](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%9C%A8%E5%B9%BF%E5%B7%9E%E4%B8%89%E5%85%83%E9%87%8C%E8%90%BD%E7%BD%91%E4%B8%BA%E4%B8%8D%E5%AE%9E%E6%B6%88%E6%81%AF%23) `1.1M 🔥` `+591%`
1. [半小时取鱼刺7小时修路震惊老外](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E5%B0%8F%E6%97%B6%E5%8F%96%E9%B1%BC%E5%88%BA7%E5%B0%8F%E6%97%B6%E4%BF%AE%E8%B7%AF%E9%9C%87%E6%83%8A%E8%80%81%E5%A4%96%23) `767.6K 🔥` `+471%`
1. [网警破获网络开盒案守护网络空间安全](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%AD%A6%E7%A0%B4%E8%8E%B7%E7%BD%91%E7%BB%9C%E5%BC%80%E7%9B%92%E6%A1%88%E5%AE%88%E6%8A%A4%E7%BD%91%E7%BB%9C%E7%A9%BA%E9%97%B4%E5%AE%89%E5%85%A8%23) `714.5K 🔥` `+21%`
1. [魏家凉皮汉堡](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E5%AE%B6%E5%87%89%E7%9A%AE%E6%B1%89%E5%A0%A1%23) `700.2K 🔥` `+309%`
1. [逐玉反盗版声明 (Zhuyu Anti-Piracy Statement)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8D%E7%9B%97%E7%89%88%E5%A3%B0%E6%98%8E%23) `398.5K 🔥` `+53%`
1. [千问崩了](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%B4%A9%E4%BA%86%23) `257.3K 🔥` `+163%`
1. [逐玉男配林沐然涨粉101万](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%94%B7%E9%85%8D%E6%9E%97%E6%B2%90%E7%84%B6%E6%B6%A8%E7%B2%89101%E4%B8%87%23) `206.6K 🔥` `+54%`
1. [AI演员签约官宣](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%E7%AD%BE%E7%BA%A6%E5%AE%98%E5%AE%A3%23) `204.0K 🔥` `+35%`
1. [陈飞宇迪丽热巴5年前拍的杂志 (Magazines photographed by Chen Feiyu and Di Lieba 5 years ago)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B45%E5%B9%B4%E5%89%8D%E6%8B%8D%E7%9A%84%E6%9D%82%E5%BF%97%23) `198.0K 🔥` `+42%`
1. [张佳宁说单眼皮因拍戏变不回来了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BD%B3%E5%AE%81%E8%AF%B4%E5%8D%95%E7%9C%BC%E7%9A%AE%E5%9B%A0%E6%8B%8D%E6%88%8F%E5%8F%98%E4%B8%8D%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `184.5K 🔥` `+28%`
1. [逐玉的兵 不贪盗版](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%9A%84%E5%85%B5%20%E4%B8%8D%E8%B4%AA%E7%9B%97%E7%89%88%23) `175.5K 🔥` `+23%`
1. [最快女护士张水华丽水马拉松夺冠](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BF%AB%E5%A5%B3%E6%8A%A4%E5%A3%AB%E5%BC%A0%E6%B0%B4%E5%8D%8E%E4%B8%BD%E6%B0%B4%E9%A9%AC%E6%8B%89%E6%9D%BE%E5%A4%BA%E5%86%A0%23) `166.7K 🔥` `+21%`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `129.6K 🔥`
1. [梅姨假装答应同居老人领证后失联](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%81%87%E8%A3%85%E7%AD%94%E5%BA%94%E5%90%8C%E5%B1%85%E8%80%81%E4%BA%BA%E9%A2%86%E8%AF%81%E5%90%8E%E5%A4%B1%E8%81%94%23) `128.6K 🔥`
1. [逐玉 盗版没弹幕快乐少一半](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%9B%97%E7%89%88%E6%B2%A1%E5%BC%B9%E5%B9%95%E5%BF%AB%E4%B9%90%E5%B0%91%E4%B8%80%E5%8D%8A%23) `118.5K 🔥`
1. [新疆一处沙漠惊现沙尘豹 (Sand leopard suddenly appears in Xinjiang desert)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E7%96%86%E4%B8%80%E5%A4%84%E6%B2%99%E6%BC%A0%E6%83%8A%E7%8E%B0%E6%B2%99%E5%B0%98%E8%B1%B9%23) `76.6K 🔥`
1. [伊朗官宣导弹工业将获满分 (Iran officially announces missile industry will receive full marks)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%98%E5%AE%A3%E5%AF%BC%E5%BC%B9%E5%B7%A5%E4%B8%9A%E5%B0%86%E8%8E%B7%E6%BB%A1%E5%88%86%23) `74.4K 🔥`
1. [重庆大学电镜中心耗资1.2亿元建成](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E5%A4%A7%E5%AD%A6%E7%94%B5%E9%95%9C%E4%B8%AD%E5%BF%83%E8%80%97%E8%B5%841.2%E4%BA%BF%E5%85%83%E5%BB%BA%E6%88%90%23) `69.5K 🔥`
1. [希林娜依高伯克利七年没毕业](https://s.weibo.com/weibo?q=%23%E5%B8%8C%E6%9E%97%E5%A8%9C%E4%BE%9D%E9%AB%98%E4%BC%AF%E5%85%8B%E5%88%A9%E4%B8%83%E5%B9%B4%E6%B2%A1%E6%AF%95%E4%B8%9A%23) `260.4K 🔥` `-52%`
1. [梅姨](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%23) `199.1K 🔥` `-25%`
1. [1200多家饭店拍黄瓜被举报 (More than 1,200 restaurants were reported for taking pictures of cucumbers)](https://s.weibo.com/weibo?q=%231200%E5%A4%9A%E5%AE%B6%E9%A5%AD%E5%BA%97%E6%8B%8D%E9%BB%84%E7%93%9C%E8%A2%AB%E4%B8%BE%E6%8A%A5%23) `174.3K 🔥` `-84%`
1. [伊朗回应特朗普袭击电厂威胁](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E8%A2%AD%E5%87%BB%E7%94%B5%E5%8E%82%E5%A8%81%E8%83%81%23) `86.2K 🔥` `-45%`
1. [逐玉亲到腿软的路透要播了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%B2%E5%88%B0%E8%85%BF%E8%BD%AF%E7%9A%84%E8%B7%AF%E9%80%8F%E8%A6%81%E6%92%AD%E4%BA%86%23) `85.4K 🔥` `-39%`
1. [虞书欣云初令杀青上班路透](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%BA%91%E5%88%9D%E4%BB%A4%E6%9D%80%E9%9D%92%E4%B8%8A%E7%8F%AD%E8%B7%AF%E9%80%8F%23) `84.2K 🔥` `-30%`
1. [山东事业编](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E4%B8%9C%E4%BA%8B%E4%B8%9A%E7%BC%96%23) `82.0K 🔥` `-39%`
1. [逐玉 超点](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E8%B6%85%E7%82%B9%23) `81.5K 🔥` `-51%`
1. [警方介入女子追打2岁宝宝](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E4%BB%8B%E5%85%A5%E5%A5%B3%E5%AD%90%E8%BF%BD%E6%89%932%E5%B2%81%E5%AE%9D%E5%AE%9D%23) `76.9K 🔥` `-43%`
1. [曝迪丽热巴团队重整 (Dilireba’s team reorganization revealed)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%9B%A2%E9%98%9F%E9%87%8D%E6%95%B4%23) `63.2K 🔥` `-53%`
1. [刘宇宁直播麻药劲还没过](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E7%9B%B4%E6%92%AD%E9%BA%BB%E8%8D%AF%E5%8A%B2%E8%BF%98%E6%B2%A1%E8%BF%87%23) `63.1K 🔥` `-34%`
1. [梅姨到哪也不出示身份证 (Aunt Mei never shows her ID card wherever she goes.)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%88%B0%E5%93%AA%E4%B9%9F%E4%B8%8D%E5%87%BA%E7%A4%BA%E8%BA%AB%E4%BB%BD%E8%AF%81%23) `61.2K 🔥` `-92%`
1. [美学者称伊朗战事对中国经济影响有限](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AD%A6%E8%80%85%E7%A7%B0%E4%BC%8A%E6%9C%97%E6%88%98%E4%BA%8B%E5%AF%B9%E4%B8%AD%E5%9B%BD%E7%BB%8F%E6%B5%8E%E5%BD%B1%E5%93%8D%E6%9C%89%E9%99%90%23) `60.4K 🔥` `-21%`
1. [小米SU7Pro一充跑通京沪](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3SU7Pro%E4%B8%80%E5%85%85%E8%B7%91%E9%80%9A%E4%BA%AC%E6%B2%AA%23) `56.9K 🔥` `-59%`
1. [男子醉酒摸女孩胸部被高中生制服 (Drunk man touched girl's breast and was restrained by high school student)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%86%89%E9%85%92%E6%91%B8%E5%A5%B3%E5%AD%A9%E8%83%B8%E9%83%A8%E8%A2%AB%E9%AB%98%E4%B8%AD%E7%94%9F%E5%88%B6%E6%9C%8D%23) `56.3K 🔥` `-26%`
1. [香港大劫案5人落网73公斤黄金找回](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E5%A4%A7%E5%8A%AB%E6%A1%885%E4%BA%BA%E8%90%BD%E7%BD%9173%E5%85%AC%E6%96%A4%E9%BB%84%E9%87%91%E6%89%BE%E5%9B%9E%23) `55.3K 🔥` `-21%`

Updated at 2026-03-22 14:03:49

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
