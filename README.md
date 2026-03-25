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

1. [台湾赌王身中29枪死亡5枪爆头 (Taiwan gambling king was shot 29 times and died, with 5 shots in the head)](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E8%B5%8C%E7%8E%8B%E8%BA%AB%E4%B8%AD29%E6%9E%AA%E6%AD%BB%E4%BA%A15%E6%9E%AA%E7%88%86%E5%A4%B4%23) `618.4K 🔥` `NEW`
1. [逐玉 删减](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%88%A0%E5%87%8F%23) `606.1K 🔥` `NEW`
1. [徐涛 研途考研](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%B6%9B%20%E7%A0%94%E9%80%94%E8%80%83%E7%A0%94%23) `603.4K 🔥` `NEW`
1. [福农优品我在家乡等你来](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%86%9C%E4%BC%98%E5%93%81%E6%88%91%E5%9C%A8%E5%AE%B6%E4%B9%A1%E7%AD%89%E4%BD%A0%E6%9D%A5%23) `597.0K 🔥` `NEW`
1. [猝死为啥会盯上年轻人](https://s.weibo.com/weibo?q=%23%E7%8C%9D%E6%AD%BB%E4%B8%BA%E5%95%A5%E4%BC%9A%E7%9B%AF%E4%B8%8A%E5%B9%B4%E8%BD%BB%E4%BA%BA%23) `585.6K 🔥` `NEW`
1. [张雪峰医疗文件疑遭泄露](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%8C%BB%E7%96%97%E6%96%87%E4%BB%B6%E7%96%91%E9%81%AD%E6%B3%84%E9%9C%B2%23) `577.4K 🔥` `NEW`
1. [疑泄露张雪峰医疗文件可判刑七年](https://s.weibo.com/weibo?q=%23%E7%96%91%E6%B3%84%E9%9C%B2%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%8C%BB%E7%96%97%E6%96%87%E4%BB%B6%E5%8F%AF%E5%88%A4%E5%88%91%E4%B8%83%E5%B9%B4%23) `525.9K 🔥` `NEW`
1. [新加坡男生扮成女子行骗被鞭刑](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%8A%A0%E5%9D%A1%E7%94%B7%E7%94%9F%E6%89%AE%E6%88%90%E5%A5%B3%E5%AD%90%E8%A1%8C%E9%AA%97%E8%A2%AB%E9%9E%AD%E5%88%91%23) `510.2K 🔥` `NEW`
1. [Uzi谈LPL退役选手](https://s.weibo.com/weibo?q=%23Uzi%E8%B0%88LPL%E9%80%80%E5%BD%B9%E9%80%89%E6%89%8B%23) `160.2K 🔥` `NEW`
1. [大冰直播悼念张雪峰](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%86%B0%E7%9B%B4%E6%92%AD%E6%82%BC%E5%BF%B5%E5%BC%A0%E9%9B%AA%E5%B3%B0%23) `132.4K 🔥` `NEW`
1. [金价突然飙升 (Gold price surges suddenly)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E7%AA%81%E7%84%B6%E9%A3%99%E5%8D%87%23) `118.0K 🔥` `NEW`
1. [张凌赫透明的前半生](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E9%80%8F%E6%98%8E%E7%9A%84%E5%89%8D%E5%8D%8A%E7%94%9F%23) `112.6K 🔥` `NEW`
1. [11年前在朋友圈见过的素人陈哲远](https://s.weibo.com/weibo?q=%2311%E5%B9%B4%E5%89%8D%E5%9C%A8%E6%9C%8B%E5%8F%8B%E5%9C%88%E8%A7%81%E8%BF%87%E7%9A%84%E7%B4%A0%E4%BA%BA%E9%99%88%E5%93%B2%E8%BF%9C%23) `112.6K 🔥` `NEW`
1. [七成SU7进店客户只看小米](https://s.weibo.com/weibo?q=%23%E4%B8%83%E6%88%90SU7%E8%BF%9B%E5%BA%97%E5%AE%A2%E6%88%B7%E5%8F%AA%E7%9C%8B%E5%B0%8F%E7%B1%B3%23) `88.0K 🔥` `NEW`
1. [32岁产妇羊水栓塞成植物人 (32-year-old mother suffers amniotic fluid embolism and becomes vegetative)](https://s.weibo.com/weibo?q=%2332%E5%B2%81%E4%BA%A7%E5%A6%87%E7%BE%8A%E6%B0%B4%E6%A0%93%E5%A1%9E%E6%88%90%E6%A4%8D%E7%89%A9%E4%BA%BA%23) `1.1M 🔥` `+766%`
1. [医生称运动对血管是直接伤害](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E7%A7%B0%E8%BF%90%E5%8A%A8%E5%AF%B9%E8%A1%80%E7%AE%A1%E6%98%AF%E7%9B%B4%E6%8E%A5%E4%BC%A4%E5%AE%B3%23) `777.6K 🔥` `+401%`
1. [耳帝评价周杰伦新专辑](https://s.weibo.com/weibo?q=%23%E8%80%B3%E5%B8%9D%E8%AF%84%E4%BB%B7%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%23) `570.0K 🔥` `+59%`
1. [张雪峰对女儿未来的规划与期盼 (Zhang Xuefeng’s plans and expectations for her daughter’s future)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%AF%B9%E5%A5%B3%E5%84%BF%E6%9C%AA%E6%9D%A5%E7%9A%84%E8%A7%84%E5%88%92%E4%B8%8E%E6%9C%9F%E7%9B%BC%23) `562.5K 🔥` `+107%`
1. [晋江 花了好多钱](https://s.weibo.com/weibo?q=%23%E6%99%8B%E6%B1%9F%20%E8%8A%B1%E4%BA%86%E5%A5%BD%E5%A4%9A%E9%92%B1%23) `556.7K 🔥` `+127%`
1. [50岁女子同房后出血查出晚期宫颈癌](https://s.weibo.com/weibo?q=%2350%E5%B2%81%E5%A5%B3%E5%AD%90%E5%90%8C%E6%88%BF%E5%90%8E%E5%87%BA%E8%A1%80%E6%9F%A5%E5%87%BA%E6%99%9A%E6%9C%9F%E5%AE%AB%E9%A2%88%E7%99%8C%23) `549.5K 🔥` `+141%`
1. [员工买车买房张雪峰都不缺席](https://s.weibo.com/weibo?q=%23%E5%91%98%E5%B7%A5%E4%B9%B0%E8%BD%A6%E4%B9%B0%E6%88%BF%E5%BC%A0%E9%9B%AA%E5%B3%B0%E9%83%BD%E4%B8%8D%E7%BC%BA%E5%B8%AD%23) `541.6K 🔥` `+325%`
1. [小猫不洗头为什么脑袋不臭](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E4%B8%8D%E6%B4%97%E5%A4%B4%E4%B8%BA%E4%BB%80%E4%B9%88%E8%84%91%E8%A2%8B%E4%B8%8D%E8%87%AD%23) `534.1K 🔥` `+43%`
1. [伊朗称再向美林肯号航母发射导弹 (Iran says it launches another missile at USS Lincoln aircraft carrier)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%86%8D%E5%90%91%E7%BE%8E%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%E5%8F%91%E5%B0%84%E5%AF%BC%E5%BC%B9%23) `522.4K 🔥` `+387%`
1. [造谣刘晓庆去世的是她外甥](https://s.weibo.com/weibo?q=%23%E9%80%A0%E8%B0%A3%E5%88%98%E6%99%93%E5%BA%86%E5%8E%BB%E4%B8%96%E7%9A%84%E6%98%AF%E5%A5%B9%E5%A4%96%E7%94%A5%23) `518.2K 🔥` `+222%`
1. [张晋曾因突发心脏病血管堵塞近80%](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%99%8B%E6%9B%BE%E5%9B%A0%E7%AA%81%E5%8F%91%E5%BF%83%E8%84%8F%E7%97%85%E8%A1%80%E7%AE%A1%E5%A0%B5%E5%A1%9E%E8%BF%9180%25%23) `507.5K 🔥` `+222%`
1. [原来迪丽热巴的20岁也难熬](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%9A%8420%E5%B2%81%E4%B9%9F%E9%9A%BE%E7%86%AC%23) `333.8K 🔥` `+122%`
1. [张雪峰离去并不会终结的喧嚣](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E7%A6%BB%E5%8E%BB%E5%B9%B6%E4%B8%8D%E4%BC%9A%E7%BB%88%E7%BB%93%E7%9A%84%E5%96%A7%E5%9A%A3%23) `160.4K 🔥` `+32%`
1. [9年时间雄安新区长成了啥模样 (What has Xiongan New Area looked like in 9 years?)](https://s.weibo.com/weibo?q=%239%E5%B9%B4%E6%97%B6%E9%97%B4%E9%9B%84%E5%AE%89%E6%96%B0%E5%8C%BA%E9%95%BF%E6%88%90%E4%BA%86%E5%95%A5%E6%A8%A1%E6%A0%B7%23) `621.6K 🔥`
1. [胡歌燕京啤酒全球品牌代言人 (Hu Ge Yanjing Beer Global Brand Spokesperson)](https://s.weibo.com/weibo?q=%23%E8%83%A1%E6%AD%8C%E7%87%95%E4%BA%AC%E5%95%A4%E9%85%92%E5%85%A8%E7%90%83%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `619.3K 🔥`
1. [王俊凯专辑概念预告 (Wang Junkai album concept trailer)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E4%B8%93%E8%BE%91%E6%A6%82%E5%BF%B5%E9%A2%84%E5%91%8A%23) `551.7K 🔥`
1. [古偶粉底液将军101](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E5%81%B6%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B101%23) `160.2K 🔥`
1. [情侣刚把电瓶车停好就出事了](https://s.weibo.com/weibo?q=%23%E6%83%85%E4%BE%A3%E5%88%9A%E6%8A%8A%E7%94%B5%E7%93%B6%E8%BD%A6%E5%81%9C%E5%A5%BD%E5%B0%B1%E5%87%BA%E4%BA%8B%E4%BA%86%23) `133.3K 🔥`
1. [周杰伦新专辑 二胎刚好三胎就烦了](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%20%E4%BA%8C%E8%83%8E%E5%88%9A%E5%A5%BD%E4%B8%89%E8%83%8E%E5%B0%B1%E7%83%A6%E4%BA%86%23) `133.3K 🔥`
1. [线下追星 拼床](https://s.weibo.com/weibo?q=%23%E7%BA%BF%E4%B8%8B%E8%BF%BD%E6%98%9F%20%E6%8B%BC%E5%BA%8A%23) `113.9K 🔥`
1. [蓝莓 寒性 (blueberry cold)](https://s.weibo.com/weibo?q=%23%E8%93%9D%E8%8E%93%20%E5%AF%92%E6%80%A7%23) `107.2K 🔥`
1. [何润东 翻红 (Peter Ho became famous)](https://s.weibo.com/weibo?q=%23%E4%BD%95%E6%B6%A6%E4%B8%9C%20%E7%BF%BB%E7%BA%A2%23) `104.2K 🔥`
1. [统一后台湾民众可以自驾直达北京](https://s.weibo.com/weibo?q=%23%E7%BB%9F%E4%B8%80%E5%90%8E%E5%8F%B0%E6%B9%BE%E6%B0%91%E4%BC%97%E5%8F%AF%E4%BB%A5%E8%87%AA%E9%A9%BE%E7%9B%B4%E8%BE%BE%E5%8C%97%E4%BA%AC%23) `611.6K 🔥` `-25%`
1. [于东来宣布每人退3000元 (Yu Donglai announced a refund of 3,000 yuan per person)](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E4%B8%9C%E6%9D%A5%E5%AE%A3%E5%B8%83%E6%AF%8F%E4%BA%BA%E9%80%803000%E5%85%83%23) `584.7K 🔥` `-50%`
1. [奔跑吧14定档 (Running Bar 14 scheduled release)](https://s.weibo.com/weibo?q=%23%E5%A5%94%E8%B7%91%E5%90%A714%E5%AE%9A%E6%A1%A3%23) `160.1K 🔥` `-34%`
1. [伊朗声明通行霍尔木兹海峡船只条件](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A3%B0%E6%98%8E%E9%80%9A%E8%A1%8C%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E8%88%B9%E5%8F%AA%E6%9D%A1%E4%BB%B6%23) `125.9K 🔥` `-71%`
1. [3个旧手机能换一台iPhone](https://s.weibo.com/weibo?q=%233%E4%B8%AA%E6%97%A7%E6%89%8B%E6%9C%BA%E8%83%BD%E6%8D%A2%E4%B8%80%E5%8F%B0iPhone%23) `113.2K 🔥` `-60%`
1. [四川乐山一公交车车身广告语引争议](https://s.weibo.com/weibo?q=%23%E5%9B%9B%E5%B7%9D%E4%B9%90%E5%B1%B1%E4%B8%80%E5%85%AC%E4%BA%A4%E8%BD%A6%E8%BD%A6%E8%BA%AB%E5%B9%BF%E5%91%8A%E8%AF%AD%E5%BC%95%E4%BA%89%E8%AE%AE%23) `113.2K 🔥` `-79%`
1. [颉斌斌悼念张雪峰](https://s.weibo.com/weibo?q=%23%E9%A2%89%E6%96%8C%E6%96%8C%E6%82%BC%E5%BF%B5%E5%BC%A0%E9%9B%AA%E5%B3%B0%23) `113.0K 🔥` `-56%`
1. [分手退16万彩礼男方嫌少再要16.7万](https://s.weibo.com/weibo?q=%23%E5%88%86%E6%89%8B%E9%80%8016%E4%B8%87%E5%BD%A9%E7%A4%BC%E7%94%B7%E6%96%B9%E5%AB%8C%E5%B0%91%E5%86%8D%E8%A6%8116.7%E4%B8%87%23) `112.8K 🔥` `-41%`
1. [理工男开始靠脸吃饭了](https://s.weibo.com/weibo?q=%23%E7%90%86%E5%B7%A5%E7%94%B7%E5%BC%80%E5%A7%8B%E9%9D%A0%E8%84%B8%E5%90%83%E9%A5%AD%E4%BA%86%23) `112.5K 🔥` `-33%`
1. [越来越多日本女性为供养牛郎跨境卖淫 (More and more Japanese women are engaging in cross-border prostitution to support cowherds)](https://s.weibo.com/weibo?q=%23%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%A4%9A%E6%97%A5%E6%9C%AC%E5%A5%B3%E6%80%A7%E4%B8%BA%E4%BE%9B%E5%85%BB%E7%89%9B%E9%83%8E%E8%B7%A8%E5%A2%83%E5%8D%96%E6%B7%AB%23) `112.5K 🔥` `-25%`
1. [跑男官宣孟子义李昀锐](https://s.weibo.com/weibo?q=%23%E8%B7%91%E7%94%B7%E5%AE%98%E5%AE%A3%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%23) `102.7K 🔥` `-39%`
1. [男孩校园卡有就餐记录惨遭继母殴打](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E6%A0%A1%E5%9B%AD%E5%8D%A1%E6%9C%89%E5%B0%B1%E9%A4%90%E8%AE%B0%E5%BD%95%E6%83%A8%E9%81%AD%E7%BB%A7%E6%AF%8D%E6%AE%B4%E6%89%93%23) `98.4K 🔥` `-23%`
1. [宋亚轩 晒黑了](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BA%9A%E8%BD%A9%20%E6%99%92%E9%BB%91%E4%BA%86%23) `95.5K 🔥` `-21%`
1. [高考钉子户悼念张雪峰 (College entrance examination nail-biter mourns Zhang Xuefeng)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E8%80%83%E9%92%89%E5%AD%90%E6%88%B7%E6%82%BC%E5%BF%B5%E5%BC%A0%E9%9B%AA%E5%B3%B0%23) `91.3K 🔥` `-37%`
1. [展轩发文回应](https://s.weibo.com/weibo?q=%23%E5%B1%95%E8%BD%A9%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%23) `89.8K 🔥` `-30%`

Updated at 2026-03-25 19:54:19

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
