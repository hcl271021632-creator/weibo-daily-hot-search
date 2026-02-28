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

1. [2025我国完成92次宇航发射 (my country completed 92 space launches in 2025)](https://s.weibo.com/weibo?q=%232025%E6%88%91%E5%9B%BD%E5%AE%8C%E6%88%9092%E6%AC%A1%E5%AE%87%E8%88%AA%E5%8F%91%E5%B0%84%23) `1.6M 🔥` `NEW`
1. [伊朗反击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%8D%E5%87%BB%23) `1.6M 🔥` `NEW`
1. [美国正从空中和海上打击伊朗](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%AD%A3%E4%BB%8E%E7%A9%BA%E4%B8%AD%E5%92%8C%E6%B5%B7%E4%B8%8A%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%23) `507.7K 🔥` `NEW`
1. [王楚钦看林诗栋比赛摇头叹气](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E7%9C%8B%E6%9E%97%E8%AF%97%E6%A0%8B%E6%AF%94%E8%B5%9B%E6%91%87%E5%A4%B4%E5%8F%B9%E6%B0%94%23) `461.0K 🔥` `NEW`
1. [伊称结局已不再由以色列掌控](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E7%A7%B0%E7%BB%93%E5%B1%80%E5%B7%B2%E4%B8%8D%E5%86%8D%E7%94%B1%E4%BB%A5%E8%89%B2%E5%88%97%E6%8E%8C%E6%8E%A7%23) `426.8K 🔥` `NEW`
1. [小米YU9](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3YU9%23) `266.4K 🔥` `NEW`
1. [王楚钦被裁判整无奈了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%A2%AB%E8%A3%81%E5%88%A4%E6%95%B4%E6%97%A0%E5%A5%88%E4%BA%86%23) `211.3K 🔥` `NEW`
1. [特朗普称要把伊导弹工业夷为平地](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E8%A6%81%E6%8A%8A%E4%BC%8A%E5%AF%BC%E5%BC%B9%E5%B7%A5%E4%B8%9A%E5%A4%B7%E4%B8%BA%E5%B9%B3%E5%9C%B0%23) `199.2K 🔥` `NEW`
1. [特朗普](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%23) `199.1K 🔥` `NEW`
1. [以色列 犹大之盾](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%20%E7%8A%B9%E5%A4%A7%E4%B9%8B%E7%9B%BE%23) `194.2K 🔥` `NEW`
1. [伊朗手机断网 (Iran mobile phone disconnected)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%89%8B%E6%9C%BA%E6%96%AD%E7%BD%91%23) `174.9K 🔥` `NEW`
1. [柳智敏又瘦了](https://s.weibo.com/weibo?q=%23%E6%9F%B3%E6%99%BA%E6%95%8F%E5%8F%88%E7%98%A6%E4%BA%86%23) `173.5K 🔥` `NEW`
1. [张真源哄人这一课已经快博士毕业了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%9C%9F%E6%BA%90%E5%93%84%E4%BA%BA%E8%BF%99%E4%B8%80%E8%AF%BE%E5%B7%B2%E7%BB%8F%E5%BF%AB%E5%8D%9A%E5%A3%AB%E6%AF%95%E4%B8%9A%E4%BA%86%23) `173.2K 🔥` `NEW`
1. [只有女生才懂找到本命bra的爽感](https://s.weibo.com/weibo?q=%23%E5%8F%AA%E6%9C%89%E5%A5%B3%E7%94%9F%E6%89%8D%E6%87%82%E6%89%BE%E5%88%B0%E6%9C%AC%E5%91%BDbra%E7%9A%84%E7%88%BD%E6%84%9F%23) `172.1K 🔥` `NEW`
1. [宁艺卓自曝体重41公斤](https://s.weibo.com/weibo?q=%23%E5%AE%81%E8%89%BA%E5%8D%93%E8%87%AA%E6%9B%9D%E4%BD%93%E9%87%8D41%E5%85%AC%E6%96%A4%23) `164.8K 🔥` `NEW`
1. [王安宇好明显的暗爽](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E5%A5%BD%E6%98%8E%E6%98%BE%E7%9A%84%E6%9A%97%E7%88%BD%23) `152.0K 🔥` `NEW`
1. [伊朗正准备毁灭性报复行动](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%87%86%E5%A4%87%E6%AF%81%E7%81%AD%E6%80%A7%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%23) `1.8M 🔥` `+41%`
1. [丁禹兮MISTINE全球防晒代言人 (Ding Yuxi MISTINE Global Sunscreen Spokesperson)](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A6%B9%E5%85%AEMISTINE%E5%85%A8%E7%90%83%E9%98%B2%E6%99%92%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `1.6M 🔥` `+23%`
1. [以色列监测到伊朗发射导弹](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E7%9B%91%E6%B5%8B%E5%88%B0%E4%BC%8A%E6%9C%97%E5%8F%91%E5%B0%84%E5%AF%BC%E5%BC%B9%23) `596.8K 🔥` `+81%`
1. [王楚钦再次成功挑战鹰眼](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%86%8D%E6%AC%A1%E6%88%90%E5%8A%9F%E6%8C%91%E6%88%98%E9%B9%B0%E7%9C%BC%23) `510.6K 🔥` `+34%`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `504.7K 🔥` `+25%`
1. [以色列伊朗 金价 (Israel Iran Gold Price)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E4%BC%8A%E6%9C%97%20%E9%87%91%E4%BB%B7%23) `500.5K 🔥` `+25%`
1. [九亿少女的梦](https://s.weibo.com/weibo?q=%23%E4%B9%9D%E4%BA%BF%E5%B0%91%E5%A5%B3%E7%9A%84%E6%A2%A6%23) `496.8K 🔥` `+64%`
1. [曝迪丽热巴签约天伊娱乐 (It is revealed that Dilireba signed a contract with Tianyi Entertainment)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%AD%BE%E7%BA%A6%E5%A4%A9%E4%BC%8A%E5%A8%B1%E4%B9%90%23) `493.9K 🔥` `+25%`
1. [头一回见仅付款的](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E4%B8%80%E5%9B%9E%E8%A7%81%E4%BB%85%E4%BB%98%E6%AC%BE%E7%9A%84%23) `398.8K 🔥` `+87%`
1. [特朗普表示将彻底摧毁伊朗海军](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%A1%A8%E7%A4%BA%E5%B0%86%E5%BD%BB%E5%BA%95%E6%91%A7%E6%AF%81%E4%BC%8A%E6%9C%97%E6%B5%B7%E5%86%9B%23) `350.1K 🔥` `+36%`
1. [伊朗首都发生爆炸 (Explosion in Iranian capital)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%8F%91%E7%94%9F%E7%88%86%E7%82%B8%23) `1.0M 🔥`
1. [德国总理从中国回去后急了](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E5%9B%BD%E6%80%BB%E7%90%86%E4%BB%8E%E4%B8%AD%E5%9B%BD%E5%9B%9E%E5%8E%BB%E5%90%8E%E6%80%A5%E4%BA%86%23) `527.2K 🔥`
1. [孟子义李昀锐综艺](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E7%BB%BC%E8%89%BA%23) `516.5K 🔥`
1. [导弹飞越伊拉克画面曝光](https://s.weibo.com/weibo?q=%23%E5%AF%BC%E5%BC%B9%E9%A3%9E%E8%B6%8A%E4%BC%8A%E6%8B%89%E5%85%8B%E7%94%BB%E9%9D%A2%E6%9B%9D%E5%85%89%23) `467.4K 🔥`
1. [一点点回应](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E5%9B%9E%E5%BA%94%23) `453.5K 🔥`
1. [王楚钦vs张禹珍](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E5%BC%A0%E7%A6%B9%E7%8F%8D%23) `442.9K 🔥`
1. [TF家族全员运动会 澳门 (TF Family Sports Meet Macau)](https://s.weibo.com/weibo?q=%23TF%E5%AE%B6%E6%97%8F%E5%85%A8%E5%91%98%E8%BF%90%E5%8A%A8%E4%BC%9A%20%E6%BE%B3%E9%97%A8%23) `424.6K 🔥`
1. [美军航母参与空袭伊朗](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E8%88%AA%E6%AF%8D%E5%8F%82%E4%B8%8E%E7%A9%BA%E8%A2%AD%E4%BC%8A%E6%9C%97%23) `227.7K 🔥`
1. [山姆部分产品大降价 (Some Sam products are greatly reduced in price)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E9%83%A8%E5%88%86%E4%BA%A7%E5%93%81%E5%A4%A7%E9%99%8D%E4%BB%B7%23) `199.4K 🔥`
1. [美国以色列伊朗打仗 (America, Israel, Iran at war)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%BB%A5%E8%89%B2%E5%88%97%E4%BC%8A%E6%9C%97%E6%89%93%E4%BB%97%23) `199.3K 🔥`
1. [热巴 换经纪人](https://s.weibo.com/weibo?q=%23%E7%83%AD%E5%B7%B4%20%E6%8D%A2%E7%BB%8F%E7%BA%AA%E4%BA%BA%23) `198.9K 🔥`
1. [2026考研国家线发布 (2026 Postgraduate Entrance Examination National Line Released)](https://s.weibo.com/weibo?q=%232026%E8%80%83%E7%A0%94%E5%9B%BD%E5%AE%B6%E7%BA%BF%E5%8F%91%E5%B8%83%23) `196.6K 🔥`
1. [人民币涨得太快央行踩刹车 (The yuan rose too fast and the central bank put the brakes on it)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E6%B0%91%E5%B8%81%E6%B6%A8%E5%BE%97%E5%A4%AA%E5%BF%AB%E5%A4%AE%E8%A1%8C%E8%B8%A9%E5%88%B9%E8%BD%A6%23) `173.2K 🔥`
1. [哈梅内伊已转移 (Khamenei has been transferred)](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E5%B7%B2%E8%BD%AC%E7%A7%BB%23) `166.7K 🔥`
1. [以色列宣布全国紧急状态 (Israel declares national emergency)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E5%85%A8%E5%9B%BD%E7%B4%A7%E6%80%A5%E7%8A%B6%E6%80%81%23) `159.2K 🔥`
1. [直播关注伊朗局势](https://s.weibo.com/weibo?q=%23%E7%9B%B4%E6%92%AD%E5%85%B3%E6%B3%A8%E4%BC%8A%E6%9C%97%E5%B1%80%E5%8A%BF%23) `154.0K 🔥`
1. [以色列宣布袭击伊朗](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%23) `3.0M 🔥` `-33%`
1. [美国对伊朗的空袭正在进行中](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%AF%B9%E4%BC%8A%E6%9C%97%E7%9A%84%E7%A9%BA%E8%A2%AD%E6%AD%A3%E5%9C%A8%E8%BF%9B%E8%A1%8C%E4%B8%AD%23) `502.8K 🔥` `-65%`
1. [伊朗总统遭刺杀未遂](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E9%81%AD%E5%88%BA%E6%9D%80%E6%9C%AA%E9%81%82%23) `313.4K 🔥` `-64%`
1. [范丞丞方说不认识没交集](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E6%96%B9%E8%AF%B4%E4%B8%8D%E8%AE%A4%E8%AF%86%E6%B2%A1%E4%BA%A4%E9%9B%86%23) `300.3K 🔥` `-23%`
1. [伊朗总统府遭袭 (Iranian presidential palace attacked)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E5%BA%9C%E9%81%AD%E8%A2%AD%23) `281.5K 🔥` `-25%`
1. [关晓彤漂亮得像洋娃娃一样 (Guan Xiaotong is as beautiful as a doll)](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E6%BC%82%E4%BA%AE%E5%BE%97%E5%83%8F%E6%B4%8B%E5%A8%83%E5%A8%83%E4%B8%80%E6%A0%B7%23) `181.4K 🔥` `-36%`
1. [蔡磊已进入渐冻症疾病的终末期 (Cai Lei has entered the terminal stage of ALS disease)](https://s.weibo.com/weibo?q=%23%E8%94%A1%E7%A3%8A%E5%B7%B2%E8%BF%9B%E5%85%A5%E6%B8%90%E5%86%BB%E7%97%87%E7%96%BE%E7%97%85%E7%9A%84%E7%BB%88%E6%9C%AB%E6%9C%9F%23) `171.3K 🔥` `-55%`
1. [韩国演员林周焕在物流中心搬货](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E6%BC%94%E5%91%98%E6%9E%97%E5%91%A8%E7%84%95%E5%9C%A8%E7%89%A9%E6%B5%81%E4%B8%AD%E5%BF%83%E6%90%AC%E8%B4%A7%23) `169.1K 🔥` `-47%`
1. [Angelababy紫罗兰中式美人](https://s.weibo.com/weibo?q=%23Angelababy%E7%B4%AB%E7%BD%97%E5%85%B0%E4%B8%AD%E5%BC%8F%E7%BE%8E%E4%BA%BA%23) `163.7K 🔥` `-24%`

Updated at 2026-02-28 16:52:52

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
