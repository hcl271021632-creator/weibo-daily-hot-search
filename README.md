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

1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `1.1M 🔥` `NEW`
1. [妇女节快乐](https://s.weibo.com/weibo?q=%23%E5%A6%87%E5%A5%B3%E8%8A%82%E5%BF%AB%E4%B9%90%23) `334.4K 🔥` `NEW`
1. [花少神一季鬼一季的定律](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%B0%91%E7%A5%9E%E4%B8%80%E5%AD%A3%E9%AC%BC%E4%B8%80%E5%AD%A3%E7%9A%84%E5%AE%9A%E5%BE%8B%23) `214.2K 🔥` `NEW`
1. [雷军说未来每周或仅需工作3天](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E8%AF%B4%E6%9C%AA%E6%9D%A5%E6%AF%8F%E5%91%A8%E6%88%96%E4%BB%85%E9%9C%80%E5%B7%A5%E4%BD%9C3%E5%A4%A9%23) `211.6K 🔥` `NEW`
1. [霍启刚建议中小学开冰雪课](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%90%AF%E5%88%9A%E5%BB%BA%E8%AE%AE%E4%B8%AD%E5%B0%8F%E5%AD%A6%E5%BC%80%E5%86%B0%E9%9B%AA%E8%AF%BE%23) `162.6K 🔥` `NEW`
1. [身份证上这些彩蛋你看到了吗](https://s.weibo.com/weibo?q=%23%E8%BA%AB%E4%BB%BD%E8%AF%81%E4%B8%8A%E8%BF%99%E4%BA%9B%E5%BD%A9%E8%9B%8B%E4%BD%A0%E7%9C%8B%E5%88%B0%E4%BA%86%E5%90%97%23) `108.7K 🔥` `NEW`
1. [逐玉有条通天路你走不走](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E6%9C%89%E6%9D%A1%E9%80%9A%E5%A4%A9%E8%B7%AF%E4%BD%A0%E8%B5%B0%E4%B8%8D%E8%B5%B0%23) `96.6K 🔥` `NEW`
1. [Faker直播犯困](https://s.weibo.com/weibo?q=%23Faker%E7%9B%B4%E6%92%AD%E7%8A%AF%E5%9B%B0%23) `93.5K 🔥` `NEW`
1. [黄晓明 圈外交心的朋友比圈内的多](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%20%E5%9C%88%E5%A4%96%E4%BA%A4%E5%BF%83%E7%9A%84%E6%9C%8B%E5%8F%8B%E6%AF%94%E5%9C%88%E5%86%85%E7%9A%84%E5%A4%9A%23) `90.7K 🔥` `NEW`
1. [狄龙涉嫌酒驾被捕现场视频曝光](https://s.weibo.com/weibo?q=%23%E7%8B%84%E9%BE%99%E6%B6%89%E5%AB%8C%E9%85%92%E9%A9%BE%E8%A2%AB%E6%8D%95%E7%8E%B0%E5%9C%BA%E8%A7%86%E9%A2%91%E6%9B%9D%E5%85%89%23) `88.4K 🔥` `NEW`
1. [JackeyLove职业生涯最夯的一次闪现 (The most powerful flash of JackeyLove's career)](https://s.weibo.com/weibo?q=%23JackeyLove%E8%81%8C%E4%B8%9A%E7%94%9F%E6%B6%AF%E6%9C%80%E5%A4%AF%E7%9A%84%E4%B8%80%E6%AC%A1%E9%97%AA%E7%8E%B0%23) `78.8K 🔥` `NEW`
1. [谭维维陈卓璇养成系具象化](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E7%BB%B4%E7%BB%B4%E9%99%88%E5%8D%93%E7%92%87%E5%85%BB%E6%88%90%E7%B3%BB%E5%85%B7%E8%B1%A1%E5%8C%96%23) `70.6K 🔥` `NEW`
1. [教资作文](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E4%BD%9C%E6%96%87%23) `69.4K 🔥` `NEW`
1. [这大尾巴谁不想摸](https://s.weibo.com/weibo?q=%23%E8%BF%99%E5%A4%A7%E5%B0%BE%E5%B7%B4%E8%B0%81%E4%B8%8D%E6%83%B3%E6%91%B8%23) `69.0K 🔥` `NEW`
1. [老年人追星的痛](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%B9%B4%E4%BA%BA%E8%BF%BD%E6%98%9F%E7%9A%84%E7%97%9B%23) `109.2K 🔥` `+41%`
1. [十五五109项重大工程项目思维导图](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94109%E9%A1%B9%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%E9%A1%B9%E7%9B%AE%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE%23) `615.6K 🔥`
1. [漂亮过节用美团医美 (Be beautiful during the holidays with Meituan Medical Beauty)](https://s.weibo.com/weibo?q=%23%E6%BC%82%E4%BA%AE%E8%BF%87%E8%8A%82%E7%94%A8%E7%BE%8E%E5%9B%A2%E5%8C%BB%E7%BE%8E%23) `607.5K 🔥`
1. [王传君恶剪了所有人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BC%A0%E5%90%9B%E6%81%B6%E5%89%AA%E4%BA%86%E6%89%80%E6%9C%89%E4%BA%BA%23) `412.7K 🔥`
1. [麦当劳CEO再被网友扒出假吃](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E5%86%8D%E8%A2%AB%E7%BD%91%E5%8F%8B%E6%89%92%E5%87%BA%E5%81%87%E5%90%83%23) `208.6K 🔥`
1. [不会化妆的女生建议反复观看](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BC%9A%E5%8C%96%E5%A6%86%E7%9A%84%E5%A5%B3%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%8F%8D%E5%A4%8D%E8%A7%82%E7%9C%8B%23) `201.5K 🔥`
1. [张凌赫感谢惠英红推荐逐玉](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%84%9F%E8%B0%A2%E6%83%A0%E8%8B%B1%E7%BA%A2%E6%8E%A8%E8%8D%90%E9%80%90%E7%8E%89%23) `178.3K 🔥`
1. [两口子是在工地认识的吗 (Did the couple meet at the construction site?)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E5%8F%A3%E5%AD%90%E6%98%AF%E5%9C%A8%E5%B7%A5%E5%9C%B0%E8%AE%A4%E8%AF%86%E7%9A%84%E5%90%97%23) `166.7K 🔥`
1. [刘亦菲8秒换胎](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B28%E7%A7%92%E6%8D%A2%E8%83%8E%23) `162.0K 🔥`
1. [宝格丽 刘亦菲在哪儿我在哪儿 (Bulgari Where is Liu Yifei, where am I?)](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E6%A0%BC%E4%B8%BD%20%E5%88%98%E4%BA%A6%E8%8F%B2%E5%9C%A8%E5%93%AA%E5%84%BF%E6%88%91%E5%9C%A8%E5%93%AA%E5%84%BF%23) `161.9K 🔥`
1. [教资 (teaching resources)](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%23) `159.2K 🔥`
1. [白鹿回应和跑男团关系](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%9B%9E%E5%BA%94%E5%92%8C%E8%B7%91%E7%94%B7%E5%9B%A2%E5%85%B3%E7%B3%BB%23) `108.9K 🔥`
1. [惠英红也在看逐玉](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%E4%B9%9F%E5%9C%A8%E7%9C%8B%E9%80%90%E7%8E%89%23) `108.6K 🔥`
1. [王一博周围全是LV集团高层](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%91%A8%E5%9B%B4%E5%85%A8%E6%98%AFLV%E9%9B%86%E5%9B%A2%E9%AB%98%E5%B1%82%23) `91.8K 🔥`
1. [张凯丽谈20天婚假公司只批3天 (Zhang Kaili talks about 20 days of wedding leave, the company only approves 3 days)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%AF%E4%B8%BD%E8%B0%8820%E5%A4%A9%E5%A9%9A%E5%81%87%E5%85%AC%E5%8F%B8%E5%8F%AA%E6%89%B93%E5%A4%A9%23) `81.4K 🔥`
1. [女子热水泡脚3个月皮肤变色洗不掉](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%83%AD%E6%B0%B4%E6%B3%A1%E8%84%9A3%E4%B8%AA%E6%9C%88%E7%9A%AE%E8%82%A4%E5%8F%98%E8%89%B2%E6%B4%97%E4%B8%8D%E6%8E%89%23) `80.8K 🔥`
1. [未来五年哪些工作更吃香](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A5%E4%BA%94%E5%B9%B4%E5%93%AA%E4%BA%9B%E5%B7%A5%E4%BD%9C%E6%9B%B4%E5%90%83%E9%A6%99%23) `70.0K 🔥`
1. [40年前的丧假制度该更新了 (The 40-year-old bereavement leave system needs to be updated)](https://s.weibo.com/weibo?q=%2340%E5%B9%B4%E5%89%8D%E7%9A%84%E4%B8%A7%E5%81%87%E5%88%B6%E5%BA%A6%E8%AF%A5%E6%9B%B4%E6%96%B0%E4%BA%86%23) `816.2K 🔥` `-23%`
1. [第2场委员通道](https://s.weibo.com/weibo?q=%23%E7%AC%AC2%E5%9C%BA%E5%A7%94%E5%91%98%E9%80%9A%E9%81%93%23) `342.5K 🔥` `-33%`
1. [伊朗7小时5轮导弹射向以色列](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%977%E5%B0%8F%E6%97%B65%E8%BD%AE%E5%AF%BC%E5%BC%B9%E5%B0%84%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `337.9K 🔥` `-34%`
1. [路虎揽胜回应魏建军道歉](https://s.weibo.com/weibo?q=%23%E8%B7%AF%E8%99%8E%E6%8F%BD%E8%83%9C%E5%9B%9E%E5%BA%94%E9%AD%8F%E5%BB%BA%E5%86%9B%E9%81%93%E6%AD%89%23) `305.4K 🔥` `-61%`
1. [90后单亲妈妈摆地摊起家年赚上千万 (A single mother born in the 1990s started a street stall and earned tens of millions a year)](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E5%8D%95%E4%BA%B2%E5%A6%88%E5%A6%88%E6%91%86%E5%9C%B0%E6%91%8A%E8%B5%B7%E5%AE%B6%E5%B9%B4%E8%B5%9A%E4%B8%8A%E5%8D%83%E4%B8%87%23) `217.8K 🔥` `-57%`
1. [报告里这些民生举措触手可及 (These livelihood measures in the report are within reach)](https://s.weibo.com/weibo?q=%23%E6%8A%A5%E5%91%8A%E9%87%8C%E8%BF%99%E4%BA%9B%E6%B0%91%E7%94%9F%E4%B8%BE%E6%8E%AA%E8%A7%A6%E6%89%8B%E5%8F%AF%E5%8F%8A%23) `216.8K 🔥` `-57%`
1. [5500多所医疗机构设健康体重管理门诊](https://s.weibo.com/weibo?q=%235500%E5%A4%9A%E6%89%80%E5%8C%BB%E7%96%97%E6%9C%BA%E6%9E%84%E8%AE%BE%E5%81%A5%E5%BA%B7%E4%BD%93%E9%87%8D%E7%AE%A1%E7%90%86%E9%97%A8%E8%AF%8A%23) `216.1K 🔥` `-57%`
1. [建议像治理黄色网站治理网盘浏览器](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%83%8F%E6%B2%BB%E7%90%86%E9%BB%84%E8%89%B2%E7%BD%91%E7%AB%99%E6%B2%BB%E7%90%86%E7%BD%91%E7%9B%98%E6%B5%8F%E8%A7%88%E5%99%A8%23) `213.2K 🔥` `-57%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `210.1K 🔥` `-31%`
1. [下面用的已经是苹果二十几了](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E9%9D%A2%E7%94%A8%E7%9A%84%E5%B7%B2%E7%BB%8F%E6%98%AF%E8%8B%B9%E6%9E%9C%E4%BA%8C%E5%8D%81%E5%87%A0%E4%BA%86%23) `209.1K 🔥` `-32%`
1. [白鹿因为当模特患上风湿病](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%9B%A0%E4%B8%BA%E5%BD%93%E6%A8%A1%E7%89%B9%E6%82%A3%E4%B8%8A%E9%A3%8E%E6%B9%BF%E7%97%85%23) `143.9K 🔥` `-21%`
1. [感受到了明星化妆师的权威](https://s.weibo.com/weibo?q=%23%E6%84%9F%E5%8F%97%E5%88%B0%E4%BA%86%E6%98%8E%E6%98%9F%E5%8C%96%E5%A6%86%E5%B8%88%E7%9A%84%E6%9D%83%E5%A8%81%23) `126.9K 🔥` `-34%`
1. [美第三个航母打击群或将部署至中东 (The third US aircraft carrier strike group may be deployed to the Middle East)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E7%AC%AC%E4%B8%89%E4%B8%AA%E8%88%AA%E6%AF%8D%E6%89%93%E5%87%BB%E7%BE%A4%E6%88%96%E5%B0%86%E9%83%A8%E7%BD%B2%E8%87%B3%E4%B8%AD%E4%B8%9C%23) `118.4K 🔥` `-43%`
1. [爱慕店长竟然是柯爱林](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%85%95%E5%BA%97%E9%95%BF%E7%AB%9F%E7%84%B6%E6%98%AF%E6%9F%AF%E7%88%B1%E6%9E%97%23) `109.0K 🔥` `-42%`
1. [千问女孩吃上刘文祥了](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%A5%B3%E5%AD%A9%E5%90%83%E4%B8%8A%E5%88%98%E6%96%87%E7%A5%A5%E4%BA%86%23) `108.6K 🔥` `-48%`
1. [4岁女儿被诊断为男孩需选性别做手术](https://s.weibo.com/weibo?q=%234%E5%B2%81%E5%A5%B3%E5%84%BF%E8%A2%AB%E8%AF%8A%E6%96%AD%E4%B8%BA%E7%94%B7%E5%AD%A9%E9%9C%80%E9%80%89%E6%80%A7%E5%88%AB%E5%81%9A%E6%89%8B%E6%9C%AF%23) `98.7K 🔥` `-24%`
1. [花儿与少年8 (Flowers and Boys 8)](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%84%BF%E4%B8%8E%E5%B0%91%E5%B9%B48%23) `84.0K 🔥` `-35%`
1. [张凌赫手戳田曦薇梨涡 (Zhang Linghe pokes Tian Xiwei's pear vortex with his hand)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%89%8B%E6%88%B3%E7%94%B0%E6%9B%A6%E8%96%87%E6%A2%A8%E6%B6%A1%23) `76.9K 🔥` `-36%`
1. [霍尔木兹海峡船只遭袭致4死3重伤](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E8%88%B9%E5%8F%AA%E9%81%AD%E8%A2%AD%E8%87%B44%E6%AD%BB3%E9%87%8D%E4%BC%A4%23) `70.7K 🔥` `-28%`
1. [谁给李昀锐开机现场放毒了](https://s.weibo.com/weibo?q=%23%E8%B0%81%E7%BB%99%E6%9D%8E%E6%98%80%E9%94%90%E5%BC%80%E6%9C%BA%E7%8E%B0%E5%9C%BA%E6%94%BE%E6%AF%92%E4%BA%86%23) `68.3K 🔥` `-25%`
1. [俄方警告芬兰 (Russia warns Finland)](https://s.weibo.com/weibo?q=%23%E4%BF%84%E6%96%B9%E8%AD%A6%E5%91%8A%E8%8A%AC%E5%85%B0%23) `68.0K 🔥` `-22%`

Updated at 2026-03-07 15:05:56

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
