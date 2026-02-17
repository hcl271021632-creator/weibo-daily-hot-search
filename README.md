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

1. [转转 对不起大家没钱上春晚 (Zhuanzhuan, I’m sorry that everyone has no money to attend the Spring Festival Gala.)](https://s.weibo.com/weibo?q=%23%E8%BD%AC%E8%BD%AC%20%E5%AF%B9%E4%B8%8D%E8%B5%B7%E5%A4%A7%E5%AE%B6%E6%B2%A1%E9%92%B1%E4%B8%8A%E6%98%A5%E6%99%9A%23) `1.7M 🔥` `NEW`
1. [中国速滑男队再战团体追逐](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%80%9F%E6%BB%91%E7%94%B7%E9%98%9F%E5%86%8D%E6%88%98%E5%9B%A2%E4%BD%93%E8%BF%BD%E9%80%90%23) `177.7K 🔥` `NEW`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `177.4K 🔥` `NEW`
1. [老家的人早就认识阿福了](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%AE%B6%E7%9A%84%E4%BA%BA%E6%97%A9%E5%B0%B1%E8%AE%A4%E8%AF%86%E9%98%BF%E7%A6%8F%E4%BA%86%23) `177.2K 🔥` `NEW`
1. [中国车大年初一勇闯米兰](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E8%BD%A6%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E5%8B%87%E9%97%AF%E7%B1%B3%E5%85%B0%23) `177.0K 🔥` `NEW`
1. [抽中豆包科技大礼的人找到了](https://s.weibo.com/weibo?q=%23%E6%8A%BD%E4%B8%AD%E8%B1%86%E5%8C%85%E7%A7%91%E6%8A%80%E5%A4%A7%E7%A4%BC%E7%9A%84%E4%BA%BA%E6%89%BE%E5%88%B0%E4%BA%86%23) `176.9K 🔥` `NEW`
1. [洪秀柱期盼两岸在丙午马年携手奋进](https://s.weibo.com/weibo?q=%23%E6%B4%AA%E7%A7%80%E6%9F%B1%E6%9C%9F%E7%9B%BC%E4%B8%A4%E5%B2%B8%E5%9C%A8%E4%B8%99%E5%8D%88%E9%A9%AC%E5%B9%B4%E6%90%BA%E6%89%8B%E5%A5%8B%E8%BF%9B%23) `176.7K 🔥` `NEW`
1. [23个小辈拜年舅舅给每人发100元红包](https://s.weibo.com/weibo?q=%2323%E4%B8%AA%E5%B0%8F%E8%BE%88%E6%8B%9C%E5%B9%B4%E8%88%85%E8%88%85%E7%BB%99%E6%AF%8F%E4%BA%BA%E5%8F%91100%E5%85%83%E7%BA%A2%E5%8C%85%23) `176.1K 🔥` `NEW`
1. [夸王建国长得真帅有千问红包](https://s.weibo.com/weibo?q=%23%E5%A4%B8%E7%8E%8B%E5%BB%BA%E5%9B%BD%E9%95%BF%E5%BE%97%E7%9C%9F%E5%B8%85%E6%9C%89%E5%8D%83%E9%97%AE%E7%BA%A2%E5%8C%85%23) `164.8K 🔥` `NEW`
1. [马斯克母亲向中国人民拜年](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%96%AF%E5%85%8B%E6%AF%8D%E4%BA%B2%E5%90%91%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B0%91%E6%8B%9C%E5%B9%B4%23) `164.0K 🔥` `NEW`
1. [迪丽热巴穿红色太惊艳 (Dilireba looks so stunning in red)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%A9%BF%E7%BA%A2%E8%89%B2%E5%A4%AA%E6%83%8A%E8%89%B3%23) `146.9K 🔥` `NEW`
1. [押中春晚魔术博主称对不起邓男子](https://s.weibo.com/weibo?q=%23%E6%8A%BC%E4%B8%AD%E6%98%A5%E6%99%9A%E9%AD%94%E6%9C%AF%E5%8D%9A%E4%B8%BB%E7%A7%B0%E5%AF%B9%E4%B8%8D%E8%B5%B7%E9%82%93%E7%94%B7%E5%AD%90%23) `140.0K 🔥` `NEW`
1. [梁家辉 我也没有工作证](https://s.weibo.com/weibo?q=%23%E6%A2%81%E5%AE%B6%E8%BE%89%20%E6%88%91%E4%B9%9F%E6%B2%A1%E6%9C%89%E5%B7%A5%E4%BD%9C%E8%AF%81%23) `126.1K 🔥` `NEW`
1. [女子喊话亲戚过年串门拿点实惠物品](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%96%8A%E8%AF%9D%E4%BA%B2%E6%88%9A%E8%BF%87%E5%B9%B4%E4%B8%B2%E9%97%A8%E6%8B%BF%E7%82%B9%E5%AE%9E%E6%83%A0%E7%89%A9%E5%93%81%23) `123.9K 🔥` `NEW`
1. [大年初一多地网友集体出门捡柴](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E5%A4%9A%E5%9C%B0%E7%BD%91%E5%8F%8B%E9%9B%86%E4%BD%93%E5%87%BA%E9%97%A8%E6%8D%A1%E6%9F%B4%23) `123.3K 🔥` `NEW`
1. [董璇和张维伊带酒窝在海南过年](https://s.weibo.com/weibo?q=%23%E8%91%A3%E7%92%87%E5%92%8C%E5%BC%A0%E7%BB%B4%E4%BC%8A%E5%B8%A6%E9%85%92%E7%AA%9D%E5%9C%A8%E6%B5%B7%E5%8D%97%E8%BF%87%E5%B9%B4%23) `116.9K 🔥` `NEW`
1. [樊振东送祝福太喜庆了](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E9%80%81%E7%A5%9D%E7%A6%8F%E5%A4%AA%E5%96%9C%E5%BA%86%E4%BA%86%23) `113.6K 🔥` `NEW`
1. [春晚的机器人节目给五竹看哭了](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E7%9A%84%E6%9C%BA%E5%99%A8%E4%BA%BA%E8%8A%82%E7%9B%AE%E7%BB%99%E4%BA%94%E7%AB%B9%E7%9C%8B%E5%93%AD%E4%BA%86%23) `113.3K 🔥` `NEW`
1. [马嘉祺 那天我离大奖就差一个数字](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%98%89%E7%A5%BA%20%E9%82%A3%E5%A4%A9%E6%88%91%E7%A6%BB%E5%A4%A7%E5%A5%96%E5%B0%B1%E5%B7%AE%E4%B8%80%E4%B8%AA%E6%95%B0%E5%AD%97%23) `100.2K 🔥` `NEW`
1. [怎么不找张维伊演机器人蔡明](https://s.weibo.com/weibo?q=%23%E6%80%8E%E4%B9%88%E4%B8%8D%E6%89%BE%E5%BC%A0%E7%BB%B4%E4%BC%8A%E6%BC%94%E6%9C%BA%E5%99%A8%E4%BA%BA%E8%94%A1%E6%98%8E%23) `99.0K 🔥` `NEW`
1. [大年初一不煮饭 (No cooking on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E7%85%AE%E9%A5%AD%23) `900.6K 🔥` `+209%`
1. [王楚然一脸懵不像演的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E4%B8%80%E8%84%B8%E6%87%B5%E4%B8%8D%E5%83%8F%E6%BC%94%E7%9A%84%23) `674.3K 🔥` `+132%`
1. [春节坚守岗位的人 (People who stick to their posts during the Spring Festival)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E5%9D%9A%E5%AE%88%E5%B2%97%E4%BD%8D%E7%9A%84%E4%BA%BA%23) `698.9K 🔥`
1. [问界M9祝您新年手到福来](https://s.weibo.com/weibo?q=%23%E9%97%AE%E7%95%8CM9%E7%A5%9D%E6%82%A8%E6%96%B0%E5%B9%B4%E6%89%8B%E5%88%B0%E7%A6%8F%E6%9D%A5%23) `690.0K 🔥`
1. [36岁为什么还来主持人大赛 为今天](https://s.weibo.com/weibo?q=%2336%E5%B2%81%E4%B8%BA%E4%BB%80%E4%B9%88%E8%BF%98%E6%9D%A5%E4%B8%BB%E6%8C%81%E4%BA%BA%E5%A4%A7%E8%B5%9B%20%E4%B8%BA%E4%BB%8A%E5%A4%A9%23) `176.6K 🔥`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `175.9K 🔥`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `163.3K 🔥`
1. [飞驰人生3 (Flying Life 3)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%23) `122.8K 🔥`
1. [潮汕女孩庄恩琪跳英歌舞超有生命力](https://s.weibo.com/weibo?q=%23%E6%BD%AE%E6%B1%95%E5%A5%B3%E5%AD%A9%E5%BA%84%E6%81%A9%E7%90%AA%E8%B7%B3%E8%8B%B1%E6%AD%8C%E8%88%9E%E8%B6%85%E6%9C%89%E7%94%9F%E5%91%BD%E5%8A%9B%23) `99.0K 🔥`
1. [大年初一机票价格腰斩 (Air ticket prices halved on New Year's Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E6%9C%BA%E7%A5%A8%E4%BB%B7%E6%A0%BC%E8%85%B0%E6%96%A9%23) `178.1K 🔥` `-78%`
1. [飞驰人生3票房](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E7%A5%A8%E6%88%BF%23) `178.0K 🔥` `-37%`
1. [春晚奇妙座驾领克900 (The wonderful car Lynk & Co 900 for the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E5%A5%87%E5%A6%99%E5%BA%A7%E9%A9%BE%E9%A2%86%E5%85%8B900%23) `178.0K 🔥` `-24%`
1. [星河入梦 黑马 (Starry River Dreaming Dark Horse)](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%20%E9%BB%91%E9%A9%AC%23) `177.9K 🔥` `-84%`
1. [爸妈来后冰箱都变老了](https://s.weibo.com/weibo?q=%23%E7%88%B8%E5%A6%88%E6%9D%A5%E5%90%8E%E5%86%B0%E7%AE%B1%E9%83%BD%E5%8F%98%E8%80%81%E4%BA%86%23) `177.8K 🔥` `-39%`
1. [开始吃剩菜](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E5%90%83%E5%89%A9%E8%8F%9C%23) `177.7K 🔥` `-38%`
1. [沈腾说错词自责打了半宿掼蛋 (Shen Teng blamed himself for saying the wrong word and beat him half a night)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E8%AF%B4%E9%94%99%E8%AF%8D%E8%87%AA%E8%B4%A3%E6%89%93%E4%BA%86%E5%8D%8A%E5%AE%BF%E6%8E%BC%E8%9B%8B%23) `177.5K 🔥` `-65%`
1. [杨幂朱一龙吻戏](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9C%B1%E4%B8%80%E9%BE%99%E5%90%BB%E6%88%8F%23) `177.5K 🔥` `-38%`
1. [新加坡反思日本侵略](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%8A%A0%E5%9D%A1%E5%8F%8D%E6%80%9D%E6%97%A5%E6%9C%AC%E4%BE%B5%E7%95%A5%23) `177.3K 🔥` `-38%`
1. [家里最没用的把最受宠的吵醒了 (The most useless one in the family woke up the most favored one)](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%87%8C%E6%9C%80%E6%B2%A1%E7%94%A8%E7%9A%84%E6%8A%8A%E6%9C%80%E5%8F%97%E5%AE%A0%E7%9A%84%E5%90%B5%E9%86%92%E4%BA%86%23) `177.0K 🔥` `-39%`
1. [大年初一不能做哪些事 (What not to do on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E8%83%BD%E5%81%9A%E5%93%AA%E4%BA%9B%E4%BA%8B%23) `176.8K 🔥` `-39%`
1. [央妈不会找王一博赔地板吧](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E5%A6%88%E4%B8%8D%E4%BC%9A%E6%89%BE%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%B5%94%E5%9C%B0%E6%9D%BF%E5%90%A7%23) `176.6K 🔥` `-39%`
1. [砂糖橘这样摆太有年味了 (The sugar oranges displayed like this look so festive.)](https://s.weibo.com/weibo?q=%23%E7%A0%82%E7%B3%96%E6%A9%98%E8%BF%99%E6%A0%B7%E6%91%86%E5%A4%AA%E6%9C%89%E5%B9%B4%E5%91%B3%E4%BA%86%23) `176.4K 🔥` `-38%`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `176.3K 🔥` `-39%`
1. [王楚然春晚20秒破2亿](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E6%98%A5%E6%99%9A20%E7%A7%92%E7%A0%B42%E4%BA%BF%23) `176.3K 🔥` `-29%`
1. [甜馨跟爸爸爷爷奶奶一起过年](https://s.weibo.com/weibo?q=%23%E7%94%9C%E9%A6%A8%E8%B7%9F%E7%88%B8%E7%88%B8%E7%88%B7%E7%88%B7%E5%A5%B6%E5%A5%B6%E4%B8%80%E8%B5%B7%E8%BF%87%E5%B9%B4%23) `176.1K 🔥` `-39%`
1. [俄罗斯民众冒雪看春晚](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%E6%B0%91%E4%BC%97%E5%86%92%E9%9B%AA%E7%9C%8B%E6%98%A5%E6%99%9A%23) `175.9K 🔥` `-39%`
1. [刘亦菲对着狗狗夹飞了](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E5%AF%B9%E7%9D%80%E7%8B%97%E7%8B%97%E5%A4%B9%E9%A3%9E%E4%BA%86%23) `138.0K 🔥` `-33%`
1. [王一博攀岩拜年](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%94%80%E5%B2%A9%E6%8B%9C%E5%B9%B4%23) `137.5K 🔥` `-50%`
1. [千问没有免单卡也能天天减免 (Qianwen can get daily deductions even if you don’t have a free card.)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E6%B2%A1%E6%9C%89%E5%85%8D%E5%8D%95%E5%8D%A1%E4%B9%9F%E8%83%BD%E5%A4%A9%E5%A4%A9%E5%87%8F%E5%85%8D%23) `128.7K 🔥` `-33%`
1. [iPhone18ProMax或无重大更新 (iPhone 18 Pro Max may not have major updates)](https://s.weibo.com/weibo?q=%23iPhone18ProMax%E6%88%96%E6%97%A0%E9%87%8D%E5%A4%A7%E6%9B%B4%E6%96%B0%23) `99.3K 🔥` `-42%`
1. [樊振东与德甲队友过年氛围感](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E4%B8%8E%E5%BE%B7%E7%94%B2%E9%98%9F%E5%8F%8B%E8%BF%87%E5%B9%B4%E6%B0%9B%E5%9B%B4%E6%84%9F%23) `99.0K 🔥` `-52%`
1. [猫 死腿快跑啊](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E6%AD%BB%E8%85%BF%E5%BF%AB%E8%B7%91%E5%95%8A%23) `99.0K 🔥` `-61%`

Updated at 2026-02-17 18:27:09

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
