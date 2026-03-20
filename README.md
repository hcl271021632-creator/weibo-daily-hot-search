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

1. [你是迟来的欢喜定档 (You are the belated happy date)](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E6%98%AF%E8%BF%9F%E6%9D%A5%E7%9A%84%E6%AC%A2%E5%96%9C%E5%AE%9A%E6%A1%A3%23) `1.1M 🔥` `NEW`
1. [中国科学家培育出长寿水稻](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%A7%91%E5%AD%A6%E5%AE%B6%E5%9F%B9%E8%82%B2%E5%87%BA%E9%95%BF%E5%AF%BF%E6%B0%B4%E7%A8%BB%23) `642.6K 🔥` `NEW`
1. [和淘宝闪购明星天团抢春季新品](https://s.weibo.com/weibo?q=%23%E5%92%8C%E6%B7%98%E5%AE%9D%E9%97%AA%E8%B4%AD%E6%98%8E%E6%98%9F%E5%A4%A9%E5%9B%A2%E6%8A%A2%E6%98%A5%E5%AD%A3%E6%96%B0%E5%93%81%23) `484.0K 🔥` `NEW`
1. [A股第8只千元股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E7%AC%AC8%E5%8F%AA%E5%8D%83%E5%85%83%E8%82%A1%23) `270.6K 🔥` `NEW`
1. [喜欢吃蓝莓和炒饭的都沉默了](https://s.weibo.com/weibo?q=%23%E5%96%9C%E6%AC%A2%E5%90%83%E8%93%9D%E8%8E%93%E5%92%8C%E7%82%92%E9%A5%AD%E7%9A%84%E9%83%BD%E6%B2%89%E9%BB%98%E4%BA%86%23) `269.6K 🔥` `NEW`
1. [你好春天](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD%E6%98%A5%E5%A4%A9%23) `269.5K 🔥` `NEW`
1. [重庆民政局回应领导家属被举报](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E6%B0%91%E6%94%BF%E5%B1%80%E5%9B%9E%E5%BA%94%E9%A2%86%E5%AF%BC%E5%AE%B6%E5%B1%9E%E8%A2%AB%E4%B8%BE%E6%8A%A5%23) `267.1K 🔥` `NEW`
1. [女子举报退休领导母亲名下巨额财产](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B8%BE%E6%8A%A5%E9%80%80%E4%BC%91%E9%A2%86%E5%AF%BC%E6%AF%8D%E4%BA%B2%E5%90%8D%E4%B8%8B%E5%B7%A8%E9%A2%9D%E8%B4%A2%E4%BA%A7%23) `266.6K 🔥` `NEW`
1. [BTS回归](https://s.weibo.com/weibo?q=%23BTS%E5%9B%9E%E5%BD%92%23) `266.0K 🔥` `NEW`
1. [迪丽热巴新经纪人郝阿三上岗了](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%96%B0%E7%BB%8F%E7%BA%AA%E4%BA%BA%E9%83%9D%E9%98%BF%E4%B8%89%E4%B8%8A%E5%B2%97%E4%BA%86%23) `265.3K 🔥` `NEW`
1. [言承旭提词器 (Yan Chengxu teleprompter)](https://s.weibo.com/weibo?q=%23%E8%A8%80%E6%89%BF%E6%97%AD%E6%8F%90%E8%AF%8D%E5%99%A8%23) `264.1K 🔥` `NEW`
1. [青岛让善意成为流动的光](https://s.weibo.com/weibo?q=%23%E9%9D%92%E5%B2%9B%E8%AE%A9%E5%96%84%E6%84%8F%E6%88%90%E4%B8%BA%E6%B5%81%E5%8A%A8%E7%9A%84%E5%85%89%23) `263.6K 🔥` `NEW`
1. [女子花3万作法挽回男友被大师拉黑](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%8A%B13%E4%B8%87%E4%BD%9C%E6%B3%95%E6%8C%BD%E5%9B%9E%E7%94%B7%E5%8F%8B%E8%A2%AB%E5%A4%A7%E5%B8%88%E6%8B%89%E9%BB%91%23) `263.2K 🔥` `NEW`
1. [葛夕被留几手气哭了](https://s.weibo.com/weibo?q=%23%E8%91%9B%E5%A4%95%E8%A2%AB%E7%95%99%E5%87%A0%E6%89%8B%E6%B0%94%E5%93%AD%E4%BA%86%23) `262.4K 🔥` `NEW`
1. [美军或夺岛迫伊朗开放霍尔木兹海峡](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E6%88%96%E5%A4%BA%E5%B2%9B%E8%BF%AB%E4%BC%8A%E6%9C%97%E5%BC%80%E6%94%BE%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `261.4K 🔥` `NEW`
1. [大学生AI换脸盗刷他人银行卡获刑](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9FAI%E6%8D%A2%E8%84%B8%E7%9B%97%E5%88%B7%E4%BB%96%E4%BA%BA%E9%93%B6%E8%A1%8C%E5%8D%A1%E8%8E%B7%E5%88%91%23) `261.1K 🔥` `NEW`
1. [单依纯 维密](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BE%9D%E7%BA%AF%20%E7%BB%B4%E5%AF%86%23) `259.8K 🔥` `NEW`
1. [仨外甥正月不剪头拉横幅要红包](https://s.weibo.com/weibo?q=%23%E4%BB%A8%E5%A4%96%E7%94%A5%E6%AD%A3%E6%9C%88%E4%B8%8D%E5%89%AA%E5%A4%B4%E6%8B%89%E6%A8%AA%E5%B9%85%E8%A6%81%E7%BA%A2%E5%8C%85%23) `258.9K 🔥` `NEW`
1. [魏哲鸣今日定档两部剧](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E5%93%B2%E9%B8%A3%E4%BB%8A%E6%97%A5%E5%AE%9A%E6%A1%A3%E4%B8%A4%E9%83%A8%E5%89%A7%23) `236.7K 🔥` `NEW`
1. [女子每月痛经超20天求医生切子宫](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%AF%8F%E6%9C%88%E7%97%9B%E7%BB%8F%E8%B6%8520%E5%A4%A9%E6%B1%82%E5%8C%BB%E7%94%9F%E5%88%87%E5%AD%90%E5%AE%AB%23) `236.3K 🔥` `NEW`
1. [檀健次 HooHoo的火热日常 (Tan Kenji HooHoo’s hot daily routine)](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%20HooHoo%E7%9A%84%E7%81%AB%E7%83%AD%E6%97%A5%E5%B8%B8%23) `138.9K 🔥` `NEW`
1. [手胖的人解释不清了](https://s.weibo.com/weibo?q=%23%E6%89%8B%E8%83%96%E7%9A%84%E4%BA%BA%E8%A7%A3%E9%87%8A%E4%B8%8D%E6%B8%85%E4%BA%86%23) `129.3K 🔥` `NEW`
1. [迪丽热巴魏哲鸣对峙戏](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%AD%8F%E5%93%B2%E9%B8%A3%E5%AF%B9%E5%B3%99%E6%88%8F%23) `121.0K 🔥` `NEW`
1. [吉利全地形硬核SUV命名官宣](https://s.weibo.com/weibo?q=%23%E5%90%89%E5%88%A9%E5%85%A8%E5%9C%B0%E5%BD%A2%E7%A1%AC%E6%A0%B8SUV%E5%91%BD%E5%90%8D%E5%AE%98%E5%AE%A3%23) `116.0K 🔥` `NEW`
1. [方圆自曝舍不得花钱](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%9C%86%E8%87%AA%E6%9B%9D%E8%88%8D%E4%B8%8D%E5%BE%97%E8%8A%B1%E9%92%B1%23) `115.6K 🔥` `NEW`
1. [1岁幼儿睡前发现蜱虫钻进头皮在吸血](https://s.weibo.com/weibo?q=%231%E5%B2%81%E5%B9%BC%E5%84%BF%E7%9D%A1%E5%89%8D%E5%8F%91%E7%8E%B0%E8%9C%B1%E8%99%AB%E9%92%BB%E8%BF%9B%E5%A4%B4%E7%9A%AE%E5%9C%A8%E5%90%B8%E8%A1%80%23) `99.1K 🔥` `NEW`
1. [吃到了独来独往的红利](https://s.weibo.com/weibo?q=%23%E5%90%83%E5%88%B0%E4%BA%86%E7%8B%AC%E6%9D%A5%E7%8B%AC%E5%BE%80%E7%9A%84%E7%BA%A2%E5%88%A9%23) `94.1K 🔥` `NEW`
1. [高卿尘说早就开始攒金](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%8D%BF%E5%B0%98%E8%AF%B4%E6%97%A9%E5%B0%B1%E5%BC%80%E5%A7%8B%E6%94%92%E9%87%91%23) `89.4K 🔥` `NEW`
1. [普京单膝跪地为残奥会冠军佩戴奖章](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E5%8D%95%E8%86%9D%E8%B7%AA%E5%9C%B0%E4%B8%BA%E6%AE%8B%E5%A5%A5%E4%BC%9A%E5%86%A0%E5%86%9B%E4%BD%A9%E6%88%B4%E5%A5%96%E7%AB%A0%23) `88.7K 🔥` `NEW`
1. [道路运输从业人员年龄放宽至63周岁](https://s.weibo.com/weibo?q=%23%E9%81%93%E8%B7%AF%E8%BF%90%E8%BE%93%E4%BB%8E%E4%B8%9A%E4%BA%BA%E5%91%98%E5%B9%B4%E9%BE%84%E6%94%BE%E5%AE%BD%E8%87%B363%E5%91%A8%E5%B2%81%23) `88.5K 🔥` `NEW`
1. [曝马斯克拟采购200亿中国光伏设备 (It is revealed that Musk plans to purchase 20 billion Chinese photovoltaic equipment)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E9%A9%AC%E6%96%AF%E5%85%8B%E6%8B%9F%E9%87%87%E8%B4%AD200%E4%BA%BF%E4%B8%AD%E5%9B%BD%E5%85%89%E4%BC%8F%E8%AE%BE%E5%A4%87%23) `87.5K 🔥` `NEW`
1. [在网吧看结构力学](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E7%BD%91%E5%90%A7%E7%9C%8B%E7%BB%93%E6%9E%84%E5%8A%9B%E5%AD%A6%23) `77.6K 🔥` `NEW`
1. [高市早苗微表情](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%BE%AE%E8%A1%A8%E6%83%85%23) `77.4K 🔥` `NEW`
1. [文班亚马绝杀太阳](https://s.weibo.com/weibo?q=%23%E6%96%87%E7%8F%AD%E4%BA%9A%E9%A9%AC%E7%BB%9D%E6%9D%80%E5%A4%AA%E9%98%B3%23) `77.2K 🔥` `NEW`
1. [伊朗外长谈伊高官频频遭暗杀](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E8%B0%88%E4%BC%8A%E9%AB%98%E5%AE%98%E9%A2%91%E9%A2%91%E9%81%AD%E6%9A%97%E6%9D%80%23) `73.1K 🔥` `NEW`
1. [南昌舰以一敌二逼退外舰细节公布](https://s.weibo.com/weibo?q=%23%E5%8D%97%E6%98%8C%E8%88%B0%E4%BB%A5%E4%B8%80%E6%95%8C%E4%BA%8C%E9%80%BC%E9%80%80%E5%A4%96%E8%88%B0%E7%BB%86%E8%8A%82%E5%85%AC%E5%B8%83%23) `784.6K 🔥` `+177%`
1. [伊朗导弹击中以色列海法炼油厂 (Iranian missile hits Israeli oil refinery in Haifa)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%87%BB%E4%B8%AD%E4%BB%A5%E8%89%B2%E5%88%97%E6%B5%B7%E6%B3%95%E7%82%BC%E6%B2%B9%E5%8E%82%23) `269.4K 🔥` `+48%`
1. [东契奇60分](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E5%A5%91%E5%A5%8760%E5%88%86%23) `268.0K 🔥` `+254%`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `260.5K 🔥` `+43%`
1. [孟羽童再上初入职场和董明珠说了](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E7%BE%BD%E7%AB%A5%E5%86%8D%E4%B8%8A%E5%88%9D%E5%85%A5%E8%81%8C%E5%9C%BA%E5%92%8C%E8%91%A3%E6%98%8E%E7%8F%A0%E8%AF%B4%E4%BA%86%23) `258.8K 🔥` `+42%`
1. [原著谢征和长玉提了分手 (In the original work, Xie Zheng and Chang Yu broke up)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E8%91%97%E8%B0%A2%E5%BE%81%E5%92%8C%E9%95%BF%E7%8E%89%E6%8F%90%E4%BA%86%E5%88%86%E6%89%8B%23) `209.8K 🔥`
1. [女子罕见双子宫双阴道10年3次剖宫产](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%BD%95%E8%A7%81%E5%8F%8C%E5%AD%90%E5%AE%AB%E5%8F%8C%E9%98%B4%E9%81%9310%E5%B9%B43%E6%AC%A1%E5%89%96%E5%AE%AB%E4%BA%A7%23) `160.5K 🔥`
1. [白日提灯定档 (Daytime lantern scheduled)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E5%AE%9A%E6%A1%A3%23) `290.2K 🔥` `-75%`
1. [32G内存涨了约3000元 (32G memory has increased by about 3,000 yuan)](https://s.weibo.com/weibo?q=%2332G%E5%86%85%E5%AD%98%E6%B6%A8%E4%BA%86%E7%BA%A63000%E5%85%83%23) `268.8K 🔥` `-68%`
1. [小猴子石山玩耍不慎坠落身亡](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%B4%E5%AD%90%E7%9F%B3%E5%B1%B1%E7%8E%A9%E8%80%8D%E4%B8%8D%E6%85%8E%E5%9D%A0%E8%90%BD%E8%BA%AB%E4%BA%A1%23) `264.8K 🔥` `-38%`
1. [巴西女子嫁给布娃娃还连生4子](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E8%A5%BF%E5%A5%B3%E5%AD%90%E5%AB%81%E7%BB%99%E5%B8%83%E5%A8%83%E5%A8%83%E8%BF%98%E8%BF%9E%E7%94%9F4%E5%AD%90%23) `126.5K 🔥` `-30%`
1. [武大靖自曝退役后现状](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E5%A4%A7%E9%9D%96%E8%87%AA%E6%9B%9D%E9%80%80%E5%BD%B9%E5%90%8E%E7%8E%B0%E7%8A%B6%23) `121.5K 🔥` `-33%`
1. [6国声明拟保障霍尔木兹海峡安全](https://s.weibo.com/weibo?q=%236%E5%9B%BD%E5%A3%B0%E6%98%8E%E6%8B%9F%E4%BF%9D%E9%9A%9C%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%AE%89%E5%85%A8%23) `88.4K 🔥` `-56%`
1. [泡过胖东来馒头的水清澈见底](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E8%BF%87%E8%83%96%E4%B8%9C%E6%9D%A5%E9%A6%92%E5%A4%B4%E7%9A%84%E6%B0%B4%E6%B8%85%E6%BE%88%E8%A7%81%E5%BA%95%23) `85.2K 🔥` `-53%`
1. [金价暴跌真凶](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%9A%B4%E8%B7%8C%E7%9C%9F%E5%87%B6%23) `79.3K 🔥` `-52%`
1. [热巴好汹涌的爱意](https://s.weibo.com/weibo?q=%23%E7%83%AD%E5%B7%B4%E5%A5%BD%E6%B1%B9%E6%B6%8C%E7%9A%84%E7%88%B1%E6%84%8F%23) `76.1K 🔥` `-58%`
1. [李卿饭撒 没轻没重](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%8D%BF%E9%A5%AD%E6%92%92%20%E6%B2%A1%E8%BD%BB%E6%B2%A1%E9%87%8D%23) `74.4K 🔥` `-59%`

Updated at 2026-03-20 12:28:41

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
