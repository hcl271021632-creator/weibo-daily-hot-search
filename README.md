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

1. [伊朗一名中国公民遇难 (A Chinese citizen was killed in Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%90%8D%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E9%81%87%E9%9A%BE%23) `1.8M 🔥` `NEW`
1. [颜宁等9人全国三八红旗手标兵](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%AE%81%E7%AD%899%E4%BA%BA%E5%85%A8%E5%9B%BD%E4%B8%89%E5%85%AB%E7%BA%A2%E6%97%97%E6%89%8B%E6%A0%87%E5%85%B5%23) `166.1K 🔥` `NEW`
1. [王鹤棣女友视角视频是白鹿拍的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%A5%B3%E5%8F%8B%E8%A7%86%E8%A7%92%E8%A7%86%E9%A2%91%E6%98%AF%E7%99%BD%E9%B9%BF%E6%8B%8D%E7%9A%84%23) `162.0K 🔥` `NEW`
1. [伊朗前总统内贾德亲信称其平安](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%89%8D%E6%80%BB%E7%BB%9F%E5%86%85%E8%B4%BE%E5%BE%B7%E4%BA%B2%E4%BF%A1%E7%A7%B0%E5%85%B6%E5%B9%B3%E5%AE%89%23) `144.7K 🔥` `NEW`
1. [投资贱金属](https://s.weibo.com/weibo?q=%23%E6%8A%95%E8%B5%84%E8%B4%B1%E9%87%91%E5%B1%9E%23) `124.6K 🔥` `NEW`
1. [全世界指责你 我带你吃刘文祥](https://s.weibo.com/weibo?q=%23%E5%85%A8%E4%B8%96%E7%95%8C%E6%8C%87%E8%B4%A3%E4%BD%A0%20%E6%88%91%E5%B8%A6%E4%BD%A0%E5%90%83%E5%88%98%E6%96%87%E7%A5%A5%23) `117.1K 🔥` `NEW`
1. [油价大涨对生活有哪些影响](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E5%A4%A7%E6%B6%A8%E5%AF%B9%E7%94%9F%E6%B4%BB%E6%9C%89%E5%93%AA%E4%BA%9B%E5%BD%B1%E5%93%8D%23) `105.7K 🔥` `NEW`
1. [泰国实施石油出口禁令](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E5%AE%9E%E6%96%BD%E7%9F%B3%E6%B2%B9%E5%87%BA%E5%8F%A3%E7%A6%81%E4%BB%A4%23) `102.0K 🔥` `NEW`
1. [刘宇宁满36减18](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E6%BB%A136%E5%87%8F18%23) `92.0K 🔥` `NEW`
1. [三桶油历史首次收盘集体涨停](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%A1%B6%E6%B2%B9%E5%8E%86%E5%8F%B2%E9%A6%96%E6%AC%A1%E6%94%B6%E7%9B%98%E9%9B%86%E4%BD%93%E6%B6%A8%E5%81%9C%23) `91.0K 🔥` `NEW`
1. [刘文祥 点单攻略 (Liu Wenxiang Ordering Guide)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%20%E7%82%B9%E5%8D%95%E6%94%BB%E7%95%A5%23) `86.0K 🔥` `NEW`
1. [3000多中国公民自伊朗撤离](https://s.weibo.com/weibo?q=%233000%E5%A4%9A%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E8%87%AA%E4%BC%8A%E6%9C%97%E6%92%A4%E7%A6%BB%23) `83.9K 🔥` `NEW`
1. [崩坏星穹铁道](https://s.weibo.com/weibo?q=%23%E5%B4%A9%E5%9D%8F%E6%98%9F%E7%A9%B9%E9%93%81%E9%81%93%23) `81.3K 🔥` `NEW`
1. [当代教师开学现状](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BB%A3%E6%95%99%E5%B8%88%E5%BC%80%E5%AD%A6%E7%8E%B0%E7%8A%B6%23) `81.3K 🔥` `NEW`
1. [男子6元买彩票留店里竟然中了707万 (A man bought a lottery ticket for 6 yuan and left it at the store, but he won 7.07 million)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%906%E5%85%83%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%95%99%E5%BA%97%E9%87%8C%E7%AB%9F%E7%84%B6%E4%B8%AD%E4%BA%86707%E4%B8%87%23) `921.6K 🔥` `+166%`
1. [刘宇宁喊你上闲鱼赚一笔 (Liu Yuning asked you to go to Xianyu and make a fortune)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%96%8A%E4%BD%A0%E4%B8%8A%E9%97%B2%E9%B1%BC%E8%B5%9A%E4%B8%80%E7%AC%94%23) `701.5K 🔥` `+210%`
1. [宝妈抱5月大婴儿扶梯上被玩具车撞倒](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E5%A6%88%E6%8A%B15%E6%9C%88%E5%A4%A7%E5%A9%B4%E5%84%BF%E6%89%B6%E6%A2%AF%E4%B8%8A%E8%A2%AB%E7%8E%A9%E5%85%B7%E8%BD%A6%E6%92%9E%E5%80%92%23) `340.4K 🔥` `+164%`
1. [豆瓣发致歉信](https://s.weibo.com/weibo?q=%23%E8%B1%86%E7%93%A3%E5%8F%91%E8%87%B4%E6%AD%89%E4%BF%A1%23) `338.4K 🔥` `+35%`
1. [当你发现奶茶袋可以防油溅](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BD%A0%E5%8F%91%E7%8E%B0%E5%A5%B6%E8%8C%B6%E8%A2%8B%E5%8F%AF%E4%BB%A5%E9%98%B2%E6%B2%B9%E6%BA%85%23) `334.5K 🔥` `+36%`
1. [男子烧烤店就餐发现茶壶内发霉](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%83%A7%E7%83%A4%E5%BA%97%E5%B0%B1%E9%A4%90%E5%8F%91%E7%8E%B0%E8%8C%B6%E5%A3%B6%E5%86%85%E5%8F%91%E9%9C%89%23) `333.4K 🔥` `+48%`
1. [刘文祥 紫薯精](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%20%E7%B4%AB%E8%96%AF%E7%B2%BE%23) `331.8K 🔥` `+38%`
1. [伊朗的致命隐患是内奸](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%9A%84%E8%87%B4%E5%91%BD%E9%9A%90%E6%82%A3%E6%98%AF%E5%86%85%E5%A5%B8%23) `328.3K 🔥` `+40%`
1. [女装牛仔裤也没有放过王楚然 (Women’s jeans didn’t let Wang Churan go either)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E8%A3%85%E7%89%9B%E4%BB%94%E8%A3%A4%E4%B9%9F%E6%B2%A1%E6%9C%89%E6%94%BE%E8%BF%87%E7%8E%8B%E6%A5%9A%E7%84%B6%23) `326.4K 🔥` `+38%`
1. [迅猛龙自曝直播影响学业了 (Velociraptor revealed that live streaming affects his studies)](https://s.weibo.com/weibo?q=%23%E8%BF%85%E7%8C%9B%E9%BE%99%E8%87%AA%E6%9B%9D%E7%9B%B4%E6%92%AD%E5%BD%B1%E5%93%8D%E5%AD%A6%E4%B8%9A%E4%BA%86%23) `326.2K 🔥` `+104%`
1. [中国游客迪拜遇机场停运进退两难 (Chinese tourists face dilemma in Dubai due to airport shutdown)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E8%BF%AA%E6%8B%9C%E9%81%87%E6%9C%BA%E5%9C%BA%E5%81%9C%E8%BF%90%E8%BF%9B%E9%80%80%E4%B8%A4%E9%9A%BE%23) `188.9K 🔥` `+90%`
1. [猫 你怎么不等我死了才回来](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E4%BD%A0%E6%80%8E%E4%B9%88%E4%B8%8D%E7%AD%89%E6%88%91%E6%AD%BB%E4%BA%86%E6%89%8D%E5%9B%9E%E6%9D%A5%23) `178.8K 🔥` `+26%`
1. [蓝莓剥皮](https://s.weibo.com/weibo?q=%23%E8%93%9D%E8%8E%93%E5%89%A5%E7%9A%AE%23) `145.9K 🔥` `+29%`
1. [骏马闹元宵贺卡](https://s.weibo.com/weibo?q=%23%E9%AA%8F%E9%A9%AC%E9%97%B9%E5%85%83%E5%AE%B5%E8%B4%BA%E5%8D%A1%23) `722.3K 🔥`
1. [白宫下令暂缓推进对台军售](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%AB%E4%B8%8B%E4%BB%A4%E6%9A%82%E7%BC%93%E6%8E%A8%E8%BF%9B%E5%AF%B9%E5%8F%B0%E5%86%9B%E5%94%AE%23) `338.0K 🔥`
1. [迪丽热巴扛起裙摆就走了](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%89%9B%E8%B5%B7%E8%A3%99%E6%91%86%E5%B0%B1%E8%B5%B0%E4%BA%86%23) `219.6K 🔥`
1. [李昀锐还记得自己姓李不姓林吗](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E8%BF%98%E8%AE%B0%E5%BE%97%E8%87%AA%E5%B7%B1%E5%A7%93%E6%9D%8E%E4%B8%8D%E5%A7%93%E6%9E%97%E5%90%97%23) `177.2K 🔥`
1. [小鹏第二代VLA妈妈都爱开的国民智驾 (Xiaopeng’s second-generation VLA is a national smart car that mothers love to drive.)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%B9%8F%E7%AC%AC%E4%BA%8C%E4%BB%A3VLA%E5%A6%88%E5%A6%88%E9%83%BD%E7%88%B1%E5%BC%80%E7%9A%84%E5%9B%BD%E6%B0%91%E6%99%BA%E9%A9%BE%23) `163.5K 🔥`
1. [真的没人管管江西小炒吗 (Is it true that no one cares about Jiangxi Xiao Chao?)](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E7%9A%84%E6%B2%A1%E4%BA%BA%E7%AE%A1%E7%AE%A1%E6%B1%9F%E8%A5%BF%E5%B0%8F%E7%82%92%E5%90%97%23) `150.6K 🔥`
1. [吴京 战狼不干这个](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E6%88%98%E7%8B%BC%E4%B8%8D%E5%B9%B2%E8%BF%99%E4%B8%AA%23) `129.0K 🔥`
1. [新鸳鸯蝴蝶梦在外网火爆了 (The new "Mandarin Duck and Butterfly Dream" is popular on the Internet)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E9%B8%B3%E9%B8%AF%E8%9D%B4%E8%9D%B6%E6%A2%A6%E5%9C%A8%E5%A4%96%E7%BD%91%E7%81%AB%E7%88%86%E4%BA%86%23) `114.8K 🔥`
1. [林一 国产马丁](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%B8%80%20%E5%9B%BD%E4%BA%A7%E9%A9%AC%E4%B8%81%23) `105.8K 🔥`
1. [王楚然出个国怎么美成这样](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E5%87%BA%E4%B8%AA%E5%9B%BD%E6%80%8E%E4%B9%88%E7%BE%8E%E6%88%90%E8%BF%99%E6%A0%B7%23) `105.4K 🔥`
1. [迪丽热巴闪耀巴黎 (Dilireba shines in Paris)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%97%AA%E8%80%80%E5%B7%B4%E9%BB%8E%23) `99.2K 🔥`
1. [朋友圈置顶分享胶卷 (Pin the film to the top of your circle of friends to share it)](https://s.weibo.com/weibo?q=%23%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%BD%AE%E9%A1%B6%E5%88%86%E4%BA%AB%E8%83%B6%E5%8D%B7%23) `91.4K 🔥`
1. [王楚钦过不了安检瞬间红温 (Wang Chuqin suddenly became red when he couldn't pass the security check.)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%BF%87%E4%B8%8D%E4%BA%86%E5%AE%89%E6%A3%80%E7%9E%AC%E9%97%B4%E7%BA%A2%E6%B8%A9%23) `84.5K 🔥`
1. [伊朗导弹突破以色列防御系统 (Iranian missile breaks through Israeli defense system)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E7%AA%81%E7%A0%B4%E4%BB%A5%E8%89%B2%E5%88%97%E9%98%B2%E5%BE%A1%E7%B3%BB%E7%BB%9F%23) `661.1K 🔥` `-41%`
1. [海口市监局回应椰树低俗广告](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8F%A3%E5%B8%82%E7%9B%91%E5%B1%80%E5%9B%9E%E5%BA%94%E6%A4%B0%E6%A0%91%E4%BD%8E%E4%BF%97%E5%B9%BF%E5%91%8A%23) `342.2K 🔥` `-58%`
1. [家属否认内贾德死亡 (Family denies Ahmadinejad's death)](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E5%B1%9E%E5%90%A6%E8%AE%A4%E5%86%85%E8%B4%BE%E5%BE%B7%E6%AD%BB%E4%BA%A1%23) `241.5K 🔥` `-34%`
1. [李雨桐喊话薛之谦 (Li Yutong shouts to Joker Xue)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%9B%A8%E6%A1%90%E5%96%8A%E8%AF%9D%E8%96%9B%E4%B9%8B%E8%B0%A6%23) `164.3K 🔥` `-25%`
1. [以色列袭击黎巴嫩致31人死](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E8%A2%AD%E5%87%BB%E9%BB%8E%E5%B7%B4%E5%AB%A9%E8%87%B431%E4%BA%BA%E6%AD%BB%23) `158.4K 🔥` `-27%`
1. [李雨桐说被薛之谦威胁](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%9B%A8%E6%A1%90%E8%AF%B4%E8%A2%AB%E8%96%9B%E4%B9%8B%E8%B0%A6%E5%A8%81%E8%83%81%23) `150.0K 🔥` `-22%`
1. [刘文祥麻辣烫](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%23) `131.0K 🔥` `-80%`
1. [坐在医院等结果突然被塞手里一个小孩](https://s.weibo.com/weibo?q=%23%E5%9D%90%E5%9C%A8%E5%8C%BB%E9%99%A2%E7%AD%89%E7%BB%93%E6%9E%9C%E7%AA%81%E7%84%B6%E8%A2%AB%E5%A1%9E%E6%89%8B%E9%87%8C%E4%B8%80%E4%B8%AA%E5%B0%8F%E5%AD%A9%23) `124.8K 🔥` `-22%`
1. [建议全民发放500元通用消费券](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%85%A8%E6%B0%91%E5%8F%91%E6%94%BE500%E5%85%83%E9%80%9A%E7%94%A8%E6%B6%88%E8%B4%B9%E5%88%B8%23) `108.3K 🔥` `-51%`
1. [孙千的cp玄学又显灵了](https://s.weibo.com/weibo?q=%23%E5%AD%99%E5%8D%83%E7%9A%84cp%E7%8E%84%E5%AD%A6%E5%8F%88%E6%98%BE%E7%81%B5%E4%BA%86%23) `106.0K 🔥` `-54%`
1. [中国石油封涨停创近11年新高](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E5%B0%81%E6%B6%A8%E5%81%9C%E5%88%9B%E8%BF%9111%E5%B9%B4%E6%96%B0%E9%AB%98%23) `101.8K 🔥` `-36%`

Updated at 2026-03-02 16:06:29

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
