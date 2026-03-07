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

1. [漂亮过节用美团医美 (Be beautiful during the holidays with Meituan Medical Beauty)](https://s.weibo.com/weibo?q=%23%E6%BC%82%E4%BA%AE%E8%BF%87%E8%8A%82%E7%94%A8%E7%BE%8E%E5%9B%A2%E5%8C%BB%E7%BE%8E%23) `600.1K 🔥` `NEW`
1. [已有3300万家庭领到育儿补贴](https://s.weibo.com/weibo?q=%23%E5%B7%B2%E6%9C%893300%E4%B8%87%E5%AE%B6%E5%BA%AD%E9%A2%86%E5%88%B0%E8%82%B2%E5%84%BF%E8%A1%A5%E8%B4%B4%23) `181.3K 🔥` `NEW`
1. [下面用的已经是苹果二十几了](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E9%9D%A2%E7%94%A8%E7%9A%84%E5%B7%B2%E7%BB%8F%E6%98%AF%E8%8B%B9%E6%9E%9C%E4%BA%8C%E5%8D%81%E5%87%A0%E4%BA%86%23) `178.9K 🔥` `NEW`
1. [感受到了明星化妆师的权威](https://s.weibo.com/weibo?q=%23%E6%84%9F%E5%8F%97%E5%88%B0%E4%BA%86%E6%98%8E%E6%98%9F%E5%8C%96%E5%A6%86%E5%B8%88%E7%9A%84%E6%9D%83%E5%A8%81%23) `176.1K 🔥` `NEW`
1. [宝格丽 刘亦菲在哪儿我在哪儿](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E6%A0%BC%E4%B8%BD%20%E5%88%98%E4%BA%A6%E8%8F%B2%E5%9C%A8%E5%93%AA%E5%84%BF%E6%88%91%E5%9C%A8%E5%93%AA%E5%84%BF%23) `148.8K 🔥` `NEW`
1. [刘亦菲8秒换胎](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B28%E7%A7%92%E6%8D%A2%E8%83%8E%23) `147.8K 🔥` `NEW`
1. [杨瀚森21分9篮板](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%80%9A%E6%A3%AE21%E5%88%869%E7%AF%AE%E6%9D%BF%23) `146.8K 🔥` `NEW`
1. [维斯塔潘撞墙](https://s.weibo.com/weibo?q=%23%E7%BB%B4%E6%96%AF%E5%A1%94%E6%BD%98%E6%92%9E%E5%A2%99%23) `135.3K 🔥` `NEW`
1. [白鹿回应和跑男团关系](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%9B%9E%E5%BA%94%E5%92%8C%E8%B7%91%E7%94%B7%E5%9B%A2%E5%85%B3%E7%B3%BB%23) `116.4K 🔥` `NEW`
1. [路虎揽胜回应魏建军道歉](https://s.weibo.com/weibo?q=%23%E8%B7%AF%E8%99%8E%E6%8F%BD%E8%83%9C%E5%9B%9E%E5%BA%94%E9%AD%8F%E5%BB%BA%E5%86%9B%E9%81%93%E6%AD%89%23) `115.5K 🔥` `NEW`
1. [ZOO对战北京WBG (ZOO vs. Beijing WBG)](https://s.weibo.com/weibo?q=%23ZOO%E5%AF%B9%E6%88%98%E5%8C%97%E4%BA%ACWBG%23) `100.2K 🔥` `NEW`
1. [逐玉1集初遇4集大婚5集床戏](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%891%E9%9B%86%E5%88%9D%E9%81%874%E9%9B%86%E5%A4%A7%E5%A9%9A5%E9%9B%86%E5%BA%8A%E6%88%8F%23) `93.7K 🔥` `NEW`
1. [男队依然需要樊振东这样的定海神针](https://s.weibo.com/weibo?q=%23%E7%94%B7%E9%98%9F%E4%BE%9D%E7%84%B6%E9%9C%80%E8%A6%81%E6%A8%8A%E6%8C%AF%E4%B8%9C%E8%BF%99%E6%A0%B7%E7%9A%84%E5%AE%9A%E6%B5%B7%E7%A5%9E%E9%92%88%23) `90.1K 🔥` `NEW`
1. [伊朗7小时5轮导弹射向以色列](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%977%E5%B0%8F%E6%97%B65%E8%BD%AE%E5%AF%BC%E5%BC%B9%E5%B0%84%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `84.8K 🔥` `NEW`
1. [F1直播](https://s.weibo.com/weibo?q=%23F1%E7%9B%B4%E6%92%AD%23) `75.9K 🔥` `NEW`
1. [40年前的丧假制度该更新了 (The 40-year-old bereavement leave system needs to be updated)](https://s.weibo.com/weibo?q=%2340%E5%B9%B4%E5%89%8D%E7%9A%84%E4%B8%A7%E5%81%87%E5%88%B6%E5%BA%A6%E8%AF%A5%E6%9B%B4%E6%96%B0%E4%BA%86%23) `1.1M 🔥` `+41%`
1. [建议像治理黄色网站治理网盘浏览器](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%83%8F%E6%B2%BB%E7%90%86%E9%BB%84%E8%89%B2%E7%BD%91%E7%AB%99%E6%B2%BB%E7%90%86%E7%BD%91%E7%9B%98%E6%B5%8F%E8%A7%88%E5%99%A8%23) `180.4K 🔥` `+28%`
1. [因为9岁侄子的一句话哭了40分钟](https://s.weibo.com/weibo?q=%23%E5%9B%A0%E4%B8%BA9%E5%B2%81%E4%BE%84%E5%AD%90%E7%9A%84%E4%B8%80%E5%8F%A5%E8%AF%9D%E5%93%AD%E4%BA%8640%E5%88%86%E9%92%9F%23) `171.5K 🔥` `+39%`
1. [两口子是在工地认识的吗](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E5%8F%A3%E5%AD%90%E6%98%AF%E5%9C%A8%E5%B7%A5%E5%9C%B0%E8%AE%A4%E8%AF%86%E7%9A%84%E5%90%97%23) `114.5K 🔥` `+32%`
1. [十五五109项重大工程项目思维导图](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94109%E9%A1%B9%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%E9%A1%B9%E7%9B%AE%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE%23) `610.6K 🔥`
1. [90后单亲妈妈摆地摊起家年赚上千万 (A single mother born in the 1990s started a street stall and earned tens of millions a year)](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E5%8D%95%E4%BA%B2%E5%A6%88%E5%A6%88%E6%91%86%E5%9C%B0%E6%91%8A%E8%B5%B7%E5%AE%B6%E5%B9%B4%E8%B5%9A%E4%B8%8A%E5%8D%83%E4%B8%87%23) `348.6K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `178.1K 🔥`
1. [林书豪张嘴闭嘴都是钱 (Jeremy Lin opens and shuts his mouth, it’s money)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%B9%A6%E8%B1%AA%E5%BC%A0%E5%98%B4%E9%97%AD%E5%98%B4%E9%83%BD%E6%98%AF%E9%92%B1%23) `165.9K 🔥`
1. [白鹿因为当模特患上风湿病](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%9B%A0%E4%B8%BA%E5%BD%93%E6%A8%A1%E7%89%B9%E6%82%A3%E4%B8%8A%E9%A3%8E%E6%B9%BF%E7%97%85%23) `163.2K 🔥`
1. [4岁女儿被诊断为男孩需选性别做手术](https://s.weibo.com/weibo?q=%234%E5%B2%81%E5%A5%B3%E5%84%BF%E8%A2%AB%E8%AF%8A%E6%96%AD%E4%B8%BA%E7%94%B7%E5%AD%A9%E9%9C%80%E9%80%89%E6%80%A7%E5%88%AB%E5%81%9A%E6%89%8B%E6%9C%AF%23) `130.6K 🔥`
1. [王楚然偏偏你最争气](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E5%81%8F%E5%81%8F%E4%BD%A0%E6%9C%80%E4%BA%89%E6%B0%94%23) `110.6K 🔥`
1. [未来五年哪些工作更吃香](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A5%E4%BA%94%E5%B9%B4%E5%93%AA%E4%BA%9B%E5%B7%A5%E4%BD%9C%E6%9B%B4%E5%90%83%E9%A6%99%23) `98.9K 🔥`
1. [Jennie出发Chanel大秀](https://s.weibo.com/weibo?q=%23Jennie%E5%87%BA%E5%8F%91Chanel%E5%A4%A7%E7%A7%80%23) `98.3K 🔥`
1. [教资 (teaching resources)](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%23) `762.4K 🔥` `-29%`
1. [张凌赫感谢惠英红推荐逐玉](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%84%9F%E8%B0%A2%E6%83%A0%E8%8B%B1%E7%BA%A2%E6%8E%A8%E8%8D%90%E9%80%90%E7%8E%89%23) `247.3K 🔥` `-32%`
1. [不会化妆的女生建议反复观看](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BC%9A%E5%8C%96%E5%A6%86%E7%9A%84%E5%A5%B3%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%8F%8D%E5%A4%8D%E8%A7%82%E7%9C%8B%23) `230.8K 🔥` `-27%`
1. [刘敏涛倒第二遍水这段真绷不住了 (Liu Mintao couldn't hold himself any longer when he poured the water for the second time.)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%95%8F%E6%B6%9B%E5%80%92%E7%AC%AC%E4%BA%8C%E9%81%8D%E6%B0%B4%E8%BF%99%E6%AE%B5%E7%9C%9F%E7%BB%B7%E4%B8%8D%E4%BD%8F%E4%BA%86%23) `187.2K 🔥` `-44%`
1. [成年男性腰围控制90cm以内女性85以内](https://s.weibo.com/weibo?q=%23%E6%88%90%E5%B9%B4%E7%94%B7%E6%80%A7%E8%85%B0%E5%9B%B4%E6%8E%A7%E5%88%B690cm%E4%BB%A5%E5%86%85%E5%A5%B3%E6%80%A785%E4%BB%A5%E5%86%85%23) `182.0K 🔥` `-28%`
1. [报告里这些民生举措触手可及](https://s.weibo.com/weibo?q=%23%E6%8A%A5%E5%91%8A%E9%87%8C%E8%BF%99%E4%BA%9B%E6%B0%91%E7%94%9F%E4%B8%BE%E6%8E%AA%E8%A7%A6%E6%89%8B%E5%8F%AF%E5%8F%8A%23) `181.7K 🔥` `-28%`
1. [美第三个航母打击群或将部署至中东 (The third US aircraft carrier strike group may be deployed to the Middle East)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E7%AC%AC%E4%B8%89%E4%B8%AA%E8%88%AA%E6%AF%8D%E6%89%93%E5%87%BB%E7%BE%A4%E6%88%96%E5%B0%86%E9%83%A8%E7%BD%B2%E8%87%B3%E4%B8%AD%E4%B8%9C%23) `179.8K 🔥` `-28%`
1. [麦当劳CEO再被网友扒出假吃](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E5%86%8D%E8%A2%AB%E7%BD%91%E5%8F%8B%E6%89%92%E5%87%BA%E5%81%87%E5%90%83%23) `177.5K 🔥` `-29%`
1. [张凌赫手戳田曦薇梨涡](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%89%8B%E6%88%B3%E7%94%B0%E6%9B%A6%E8%96%87%E6%A2%A8%E6%B6%A1%23) `177.2K 🔥` `-29%`
1. [花儿与少年8 (Flowers and Boys 8)](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%84%BF%E4%B8%8E%E5%B0%91%E5%B9%B48%23) `176.1K 🔥` `-30%`
1. [你弟什么身份居然还有门卫](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%BC%9F%E4%BB%80%E4%B9%88%E8%BA%AB%E4%BB%BD%E5%B1%85%E7%84%B6%E8%BF%98%E6%9C%89%E9%97%A8%E5%8D%AB%23) `150.4K 🔥` `-38%`
1. [惠英红也在看逐玉](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%E4%B9%9F%E5%9C%A8%E7%9C%8B%E9%80%90%E7%8E%89%23) `143.6K 🔥` `-43%`
1. [王一博周围全是LV集团高层](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%91%A8%E5%9B%B4%E5%85%A8%E6%98%AFLV%E9%9B%86%E5%9B%A2%E9%AB%98%E5%B1%82%23) `129.2K 🔥` `-31%`
1. [霍尔木兹海峡船只遭袭致4死3重伤](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E8%88%B9%E5%8F%AA%E9%81%AD%E8%A2%AD%E8%87%B44%E6%AD%BB3%E9%87%8D%E4%BC%A4%23) `127.7K 🔥` `-41%`
1. [俄方警告芬兰](https://s.weibo.com/weibo?q=%23%E4%BF%84%E6%96%B9%E8%AD%A6%E5%91%8A%E8%8A%AC%E5%85%B0%23) `111.6K 🔥` `-40%`
1. [女子热水泡脚3个月皮肤变色洗不掉](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%83%AD%E6%B0%B4%E6%B3%A1%E8%84%9A3%E4%B8%AA%E6%9C%88%E7%9A%AE%E8%82%A4%E5%8F%98%E8%89%B2%E6%B4%97%E4%B8%8D%E6%8E%89%23) `106.6K 🔥` `-32%`
1. [所有省份已推行课间15分钟](https://s.weibo.com/weibo?q=%23%E6%89%80%E6%9C%89%E7%9C%81%E4%BB%BD%E5%B7%B2%E6%8E%A8%E8%A1%8C%E8%AF%BE%E9%97%B415%E5%88%86%E9%92%9F%23) `91.2K 🔥` `-64%`
1. [岳雨婷G社出图 (Pictured by Yue Yuting's G agency)](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7G%E7%A4%BE%E5%87%BA%E5%9B%BE%23) `91.1K 🔥` `-43%`
1. [王小亿你演短剧的时候不是这样的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%B0%8F%E4%BA%BF%E4%BD%A0%E6%BC%94%E7%9F%AD%E5%89%A7%E7%9A%84%E6%97%B6%E5%80%99%E4%B8%8D%E6%98%AF%E8%BF%99%E6%A0%B7%E7%9A%84%23) `90.5K 🔥` `-42%`
1. [以军被指击中伊朗直升机涂鸦](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E8%A2%AB%E6%8C%87%E5%87%BB%E4%B8%AD%E4%BC%8A%E6%9C%97%E7%9B%B4%E5%8D%87%E6%9C%BA%E6%B6%82%E9%B8%A6%23) `90.3K 🔥` `-21%`
1. [张凯丽谈20天婚假公司只批3天](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%AF%E4%B8%BD%E8%B0%8820%E5%A4%A9%E5%A9%9A%E5%81%87%E5%85%AC%E5%8F%B8%E5%8F%AA%E6%89%B93%E5%A4%A9%23) `88.9K 🔥` `-54%`
1. [教资作文 (Teaching resources composition)](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E4%BD%9C%E6%96%87%23) `83.4K 🔥` `-32%`
1. [德黑兰发生巨大爆炸 (Huge explosion hits Tehran)](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E9%BB%91%E5%85%B0%E5%8F%91%E7%94%9F%E5%B7%A8%E5%A4%A7%E7%88%86%E7%82%B8%23) `81.3K 🔥` `-44%`

Updated at 2026-03-07 13:52:22

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
