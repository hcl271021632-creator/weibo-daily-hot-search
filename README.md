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

1. [达芬奇Live (Leonardo da Vinci Live)](https://s.weibo.com/weibo?q=%23%E8%BE%BE%E8%8A%AC%E5%A5%87Live%23) `1.6M 🔥` `NEW`
1. [美国对伊朗的空袭正在进行中](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%AF%B9%E4%BC%8A%E6%9C%97%E7%9A%84%E7%A9%BA%E8%A2%AD%E6%AD%A3%E5%9C%A8%E8%BF%9B%E8%A1%8C%E4%B8%AD%23) `1.4M 🔥` `NEW`
1. [伊朗总统遭刺杀未遂](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E9%81%AD%E5%88%BA%E6%9D%80%E6%9C%AA%E9%81%82%23) `619.1K 🔥` `NEW`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `317.7K 🔥` `NEW`
1. [伊朗总统府遭袭](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E5%BA%9C%E9%81%AD%E8%A2%AD%23) `311.9K 🔥` `NEW`
1. [王楚钦vs张禹珍](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E5%BC%A0%E7%A6%B9%E7%8F%8D%23) `307.9K 🔥` `NEW`
1. [银行盯上孩子压岁钱](https://s.weibo.com/weibo?q=%23%E9%93%B6%E8%A1%8C%E7%9B%AF%E4%B8%8A%E5%AD%A9%E5%AD%90%E5%8E%8B%E5%B2%81%E9%92%B1%23) `214.5K 🔥` `NEW`
1. [以色列袭击伊朗最新情况](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E6%9C%80%E6%96%B0%E6%83%85%E5%86%B5%23) `210.6K 🔥` `NEW`
1. [韩国演员林周焕在物流中心搬货](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E6%BC%94%E5%91%98%E6%9E%97%E5%91%A8%E7%84%95%E5%9C%A8%E7%89%A9%E6%B5%81%E4%B8%AD%E5%BF%83%E6%90%AC%E8%B4%A7%23) `194.5K 🔥` `NEW`
1. [直播关注伊朗局势](https://s.weibo.com/weibo?q=%23%E7%9B%B4%E6%92%AD%E5%85%B3%E6%B3%A8%E4%BC%8A%E6%9C%97%E5%B1%80%E5%8A%BF%23) `192.1K 🔥` `NEW`
1. [deepseek崩了 (deepseek collapsed)](https://s.weibo.com/weibo?q=%23deepseek%E5%B4%A9%E4%BA%86%23) `191.8K 🔥` `NEW`
1. [对伊袭击是美以共同行动结果](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E4%BC%8A%E8%A2%AD%E5%87%BB%E6%98%AF%E7%BE%8E%E4%BB%A5%E5%85%B1%E5%90%8C%E8%A1%8C%E5%8A%A8%E7%BB%93%E6%9E%9C%23) `181.6K 🔥` `NEW`
1. [孟子义李昀锐综艺](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E7%BB%BC%E8%89%BA%23) `160.7K 🔥` `NEW`
1. [头一回见仅付款的](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E4%B8%80%E5%9B%9E%E8%A7%81%E4%BB%85%E4%BB%98%E6%AC%BE%E7%9A%84%23) `155.0K 🔥` `NEW`
1. [人民币涨得太快央行踩刹车](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E6%B0%91%E5%B8%81%E6%B6%A8%E5%BE%97%E5%A4%AA%E5%BF%AB%E5%A4%AE%E8%A1%8C%E8%B8%A9%E5%88%B9%E8%BD%A6%23) `140.1K 🔥` `NEW`
1. [哈梅内伊已转移](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E5%B7%B2%E8%BD%AC%E7%A7%BB%23) `138.2K 🔥` `NEW`
1. [以色列袭击伊朗现场画面](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E7%8E%B0%E5%9C%BA%E7%94%BB%E9%9D%A2%23) `429.5K 🔥` `+110%`
1. [关晓彤漂亮得像洋娃娃一样](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E6%BC%82%E4%BA%AE%E5%BE%97%E5%83%8F%E6%B4%8B%E5%A8%83%E5%A8%83%E4%B8%80%E6%A0%B7%23) `265.3K 🔥` `+26%`
1. [刘晓艳曾因婆媳关系非常痛苦](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E8%89%B3%E6%9B%BE%E5%9B%A0%E5%A9%86%E5%AA%B3%E5%85%B3%E7%B3%BB%E9%9D%9E%E5%B8%B8%E7%97%9B%E8%8B%A6%23) `177.3K 🔥` `+39%`
1. [以色列宣布袭击伊朗](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%23) `8.5M 🔥`
1. [周鸿祎揭美伪造陈志案证据内幕 (Zhou Hongyi reveals the inside story of the US forgery of Chen Zhi evidence)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E9%B8%BF%E7%A5%8E%E6%8F%AD%E7%BE%8E%E4%BC%AA%E9%80%A0%E9%99%88%E5%BF%97%E6%A1%88%E8%AF%81%E6%8D%AE%E5%86%85%E5%B9%95%23) `1.6M 🔥`
1. [一点点回应](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E5%9B%9E%E5%BA%94%23) `538.0K 🔥`
1. [跑男](https://s.weibo.com/weibo?q=%23%E8%B7%91%E7%94%B7%23) `409.0K 🔥`
1. [曝迪丽热巴签约天伊娱乐 (It is revealed that Dilireba signed a contract with Tianyi Entertainment)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%AD%BE%E7%BA%A6%E5%A4%A9%E4%BC%8A%E5%A8%B1%E4%B9%90%23) `316.9K 🔥`
1. [范丞丞方说不认识没交集](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E6%96%B9%E8%AF%B4%E4%B8%8D%E8%AE%A4%E8%AF%86%E6%B2%A1%E4%BA%A4%E9%9B%86%23) `315.1K 🔥`
1. [以色列对伊朗发动二次袭击](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AF%B9%E4%BC%8A%E6%9C%97%E5%8F%91%E5%8A%A8%E4%BA%8C%E6%AC%A1%E8%A2%AD%E5%87%BB%23) `311.0K 🔥`
1. [向太发向佐向佑儿时视频](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%A4%AA%E5%8F%91%E5%90%91%E4%BD%90%E5%90%91%E4%BD%91%E5%84%BF%E6%97%B6%E8%A7%86%E9%A2%91%23) `310.2K 🔥`
1. [黄子韬因喘不上气暂停节目录制](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E9%9F%AC%E5%9B%A0%E5%96%98%E4%B8%8D%E4%B8%8A%E6%B0%94%E6%9A%82%E5%81%9C%E8%8A%82%E7%9B%AE%E5%BD%95%E5%88%B6%23) `296.1K 🔥`
1. [高速避障能不能猛打方向](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E9%81%BF%E9%9A%9C%E8%83%BD%E4%B8%8D%E8%83%BD%E7%8C%9B%E6%89%93%E6%96%B9%E5%90%91%23) `213.3K 🔥`
1. [婚后拒同房男方讨说法已涉嫌违法 (It is illegal to refuse to have sex with a man after marriage.)](https://s.weibo.com/weibo?q=%23%E5%A9%9A%E5%90%8E%E6%8B%92%E5%90%8C%E6%88%BF%E7%94%B7%E6%96%B9%E8%AE%A8%E8%AF%B4%E6%B3%95%E5%B7%B2%E6%B6%89%E5%AB%8C%E8%BF%9D%E6%B3%95%23) `212.7K 🔥`
1. [女子离家17天马桶狂冲200吨水 (Woman's toilet flushed 200 tons of water 17 days after leaving home)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%A6%BB%E5%AE%B617%E5%A4%A9%E9%A9%AC%E6%A1%B6%E7%8B%82%E5%86%B2200%E5%90%A8%E6%B0%B4%23) `196.8K 🔥`
1. [巴厘岛发现人体肢解遗骸 (Dismembered human remains found in Bali)](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E5%8E%98%E5%B2%9B%E5%8F%91%E7%8E%B0%E4%BA%BA%E4%BD%93%E8%82%A2%E8%A7%A3%E9%81%97%E9%AA%B8%23) `191.6K 🔥`
1. [伊朗同意不拥有可制造核弹的核材料](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%8C%E6%84%8F%E4%B8%8D%E6%8B%A5%E6%9C%89%E5%8F%AF%E5%88%B6%E9%80%A0%E6%A0%B8%E5%BC%B9%E7%9A%84%E6%A0%B8%E6%9D%90%E6%96%99%23) `189.9K 🔥`
1. [Angelababy37岁了 (Angelababy is 37 years old)](https://s.weibo.com/weibo?q=%23Angelababy37%E5%B2%81%E4%BA%86%23) `177.5K 🔥`
1. [周大福镶金发夹卖2080元](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%A4%A7%E7%A6%8F%E9%95%B6%E9%87%91%E5%8F%91%E5%A4%B9%E5%8D%962080%E5%85%83%23) `155.8K 🔥`
1. [王皓解释向鹏为何无缘世界杯 (Wang Hao explains why Xiang Peng missed the World Cup)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%9A%93%E8%A7%A3%E9%87%8A%E5%90%91%E9%B9%8F%E4%B8%BA%E4%BD%95%E6%97%A0%E7%BC%98%E4%B8%96%E7%95%8C%E6%9D%AF%23) `153.4K 🔥`
1. [金饰价涨到1625元 (Gold jewelry price rises to 1,625 yuan)](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E6%B6%A8%E5%88%B01625%E5%85%83%23) `141.5K 🔥`
1. [伊朗首都发生爆炸 (Explosion in Iranian capital)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%8F%91%E7%94%9F%E7%88%86%E7%82%B8%23) `1.9M 🔥` `-43%`
1. [德国总理从中国回去后急了](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E5%9B%BD%E6%80%BB%E7%90%86%E4%BB%8E%E4%B8%AD%E5%9B%BD%E5%9B%9E%E5%8E%BB%E5%90%8E%E6%80%A5%E4%BA%86%23) `553.6K 🔥` `-39%`
1. [谷爱凌机场过安检自带金属buff](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%9C%BA%E5%9C%BA%E8%BF%87%E5%AE%89%E6%A3%80%E8%87%AA%E5%B8%A6%E9%87%91%E5%B1%9Ebuff%23) `318.3K 🔥` `-26%`
1. [蔡磊已进入渐冻症疾病的终末期 (Cai Lei has entered the terminal stage of ALS disease)](https://s.weibo.com/weibo?q=%23%E8%94%A1%E7%A3%8A%E5%B7%B2%E8%BF%9B%E5%85%A5%E6%B8%90%E5%86%BB%E7%97%87%E7%96%BE%E7%97%85%E7%9A%84%E7%BB%88%E6%9C%AB%E6%9C%9F%23) `313.7K 🔥` `-42%`
1. [山姆部分产品大降价 (Some Sam products are greatly reduced in price)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E9%83%A8%E5%88%86%E4%BA%A7%E5%93%81%E5%A4%A7%E9%99%8D%E4%BB%B7%23) `312.9K 🔥` `-39%`
1. [以色列全境响起警报](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%85%A8%E5%A2%83%E5%93%8D%E8%B5%B7%E8%AD%A6%E6%8A%A5%23) `306.0K 🔥` `-53%`
1. [2026考研国家线发布 (2026 Postgraduate Entrance Examination National Line Released)](https://s.weibo.com/weibo?q=%232026%E8%80%83%E7%A0%94%E5%9B%BD%E5%AE%B6%E7%BA%BF%E5%8F%91%E5%B8%83%23) `245.5K 🔥` `-23%`
1. [迪丽热巴现在人还在飞机上](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%8E%B0%E5%9C%A8%E4%BA%BA%E8%BF%98%E5%9C%A8%E9%A3%9E%E6%9C%BA%E4%B8%8A%23) `214.4K 🔥` `-37%`
1. [金贤重回应殴打前女友](https://s.weibo.com/weibo?q=%23%E9%87%91%E8%B4%A4%E9%87%8D%E5%9B%9E%E5%BA%94%E6%AE%B4%E6%89%93%E5%89%8D%E5%A5%B3%E5%8F%8B%23) `196.5K 🔥` `-22%`
1. [花海退役仪式](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E6%B5%B7%E9%80%80%E5%BD%B9%E4%BB%AA%E5%BC%8F%23) `165.2K 🔥` `-38%`
1. [以色列宣布全国紧急状态](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E5%85%A8%E5%9B%BD%E7%B4%A7%E6%80%A5%E7%8A%B6%E6%80%81%23) `162.9K 🔥` `-52%`
1. [考研下岸了 (The postgraduate entrance examination has ended)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E4%B8%8B%E5%B2%B8%E4%BA%86%23) `162.8K 🔥` `-22%`
1. [第一个发现这个机位的是天才 (The first person to discover this location was a genius)](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%8F%91%E7%8E%B0%E8%BF%99%E4%B8%AA%E6%9C%BA%E4%BD%8D%E7%9A%84%E6%98%AF%E5%A4%A9%E6%89%8D%23) `133.8K 🔥` `-32%`
1. [林诗栋2比4F勒布伦](https://s.weibo.com/weibo?q=%23%E6%9E%97%E8%AF%97%E6%A0%8B2%E6%AF%944F%E5%8B%92%E5%B8%83%E4%BC%A6%23) `132.8K 🔥` `-21%`

Updated at 2026-02-28 15:37:15

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
