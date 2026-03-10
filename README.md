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

1. [建议高速每年1000元免费额度 (It is recommended that free highway quota of 1,000 yuan per year)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%AB%98%E9%80%9F%E6%AF%8F%E5%B9%B41000%E5%85%83%E5%85%8D%E8%B4%B9%E9%A2%9D%E5%BA%A6%23) `777.8K 🔥` `NEW`
1. [快乐出发 全新QQ3正式预售](https://s.weibo.com/weibo?q=%23%E5%BF%AB%E4%B9%90%E5%87%BA%E5%8F%91%20%E5%85%A8%E6%96%B0QQ3%E6%AD%A3%E5%BC%8F%E9%A2%84%E5%94%AE%23) `619.9K 🔥` `NEW`
1. [我要回伊朗我要保卫我的国家](https://s.weibo.com/weibo?q=%23%E6%88%91%E8%A6%81%E5%9B%9E%E4%BC%8A%E6%9C%97%E6%88%91%E8%A6%81%E4%BF%9D%E5%8D%AB%E6%88%91%E7%9A%84%E5%9B%BD%E5%AE%B6%23) `619.4K 🔥` `NEW`
1. [伊朗高官6种语言发帖](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%AB%98%E5%AE%986%E7%A7%8D%E8%AF%AD%E8%A8%80%E5%8F%91%E5%B8%96%23) `616.4K 🔥` `NEW`
1. [周杰伦新专辑时间](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%E6%97%B6%E9%97%B4%23) `601.0K 🔥` `NEW`
1. [陈昊宇新剧给自己生了个弟弟](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%98%8A%E5%AE%87%E6%96%B0%E5%89%A7%E7%BB%99%E8%87%AA%E5%B7%B1%E7%94%9F%E4%BA%86%E4%B8%AA%E5%BC%9F%E5%BC%9F%23) `597.8K 🔥` `NEW`
1. [地球或将迎超级厄尔尼诺现象](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E7%90%83%E6%88%96%E5%B0%86%E8%BF%8E%E8%B6%85%E7%BA%A7%E5%8E%84%E5%B0%94%E5%B0%BC%E8%AF%BA%E7%8E%B0%E8%B1%A1%23) `592.7K 🔥` `NEW`
1. [崔然竣 光头强](https://s.weibo.com/weibo?q=%23%E5%B4%94%E7%84%B6%E7%AB%A3%20%E5%85%89%E5%A4%B4%E5%BC%BA%23) `538.4K 🔥` `NEW`
1. [你好星期六删除张凌赫争议片段](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD%E6%98%9F%E6%9C%9F%E5%85%AD%E5%88%A0%E9%99%A4%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%BA%89%E8%AE%AE%E7%89%87%E6%AE%B5%23) `538.0K 🔥` `NEW`
1. [周翊然和偶像乐扣比赛](https://s.weibo.com/weibo?q=%23%E5%91%A8%E7%BF%8A%E7%84%B6%E5%92%8C%E5%81%B6%E5%83%8F%E4%B9%90%E6%89%A3%E6%AF%94%E8%B5%9B%23) `537.3K 🔥` `NEW`
1. [批发商回应4.5元的1米大肉串卖20元 (The wholesaler responded that a 1-meter-large meat skewer sold for NT$20 for NT$4.50.)](https://s.weibo.com/weibo?q=%23%E6%89%B9%E5%8F%91%E5%95%86%E5%9B%9E%E5%BA%944.5%E5%85%83%E7%9A%841%E7%B1%B3%E5%A4%A7%E8%82%89%E4%B8%B2%E5%8D%9620%E5%85%83%23) `536.3K 🔥` `NEW`
1. [狗狗的失望都写在尾巴上了](https://s.weibo.com/weibo?q=%23%E7%8B%97%E7%8B%97%E7%9A%84%E5%A4%B1%E6%9C%9B%E9%83%BD%E5%86%99%E5%9C%A8%E5%B0%BE%E5%B7%B4%E4%B8%8A%E4%BA%86%23) `535.6K 🔥` `NEW`
1. [孙颖莎打破圈层跨越国际](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E6%89%93%E7%A0%B4%E5%9C%88%E5%B1%82%E8%B7%A8%E8%B6%8A%E5%9B%BD%E9%99%85%23) `534.4K 🔥` `NEW`
1. [孙颖莎王楚钦公式照](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%85%AC%E5%BC%8F%E7%85%A7%23) `534.1K 🔥` `NEW`
1. [哈哈哈哈哈6](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%93%88%E5%93%88%E5%93%88%E5%93%886%23) `533.7K 🔥` `NEW`
1. [去机场不该比坐飞机时间还长](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E6%9C%BA%E5%9C%BA%E4%B8%8D%E8%AF%A5%E6%AF%94%E5%9D%90%E9%A3%9E%E6%9C%BA%E6%97%B6%E9%97%B4%E8%BF%98%E9%95%BF%23) `1.1M 🔥` `+49%`
1. [杨迪回复穆祉丞](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%BF%AA%E5%9B%9E%E5%A4%8D%E7%A9%86%E7%A5%89%E4%B8%9E%23) `604.0K 🔥` `+62%`
1. [伊朗驻华大使谈霍尔木兹海峡通行](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A9%BB%E5%8D%8E%E5%A4%A7%E4%BD%BF%E8%B0%88%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E9%80%9A%E8%A1%8C%23) `594.4K 🔥` `+59%`
1. [突然一下就不焦虑了](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E4%B8%80%E4%B8%8B%E5%B0%B1%E4%B8%8D%E7%84%A6%E8%99%91%E4%BA%86%23) `560.7K 🔥` `+49%`
1. [婆婆进卧室不敲门儿媳崩溃哭诉](https://s.weibo.com/weibo?q=%23%E5%A9%86%E5%A9%86%E8%BF%9B%E5%8D%A7%E5%AE%A4%E4%B8%8D%E6%95%B2%E9%97%A8%E5%84%BF%E5%AA%B3%E5%B4%A9%E6%BA%83%E5%93%AD%E8%AF%89%23) `538.1K 🔥` `+43%`
1. [原来这些爆火的文案都是王源写的 (It turns out that these popular copywritings were all written by Wang Yuan)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E4%BA%9B%E7%88%86%E7%81%AB%E7%9A%84%E6%96%87%E6%A1%88%E9%83%BD%E6%98%AF%E7%8E%8B%E6%BA%90%E5%86%99%E7%9A%84%23) `537.7K 🔥` `+43%`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `536.7K 🔥` `+43%`
1. [刘亦菲ins更新看秀照 (Liu Yifei’s ins updates, see show photos)](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2ins%E6%9B%B4%E6%96%B0%E7%9C%8B%E7%A7%80%E7%85%A7%23) `536.6K 🔥` `+44%`
1. [鹿晗喝霸王茶姬](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E5%96%9D%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%23) `536.0K 🔥` `+43%`
1. [苏新皓跳第三个吻痕](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E6%96%B0%E7%9A%93%E8%B7%B3%E7%AC%AC%E4%B8%89%E4%B8%AA%E5%90%BB%E7%97%95%23) `535.9K 🔥` `+43%`
1. [甜茶买了孙颖莎海报](https://s.weibo.com/weibo?q=%23%E7%94%9C%E8%8C%B6%E4%B9%B0%E4%BA%86%E5%AD%99%E9%A2%96%E8%8E%8E%E6%B5%B7%E6%8A%A5%23) `535.4K 🔥` `+45%`
1. [ZB1解散 (ZB1 disbanded)](https://s.weibo.com/weibo?q=%23ZB1%E8%A7%A3%E6%95%A3%23) `535.4K 🔥` `+44%`
1. [MiuMiu直播 (MiuMiu live broadcast)](https://s.weibo.com/weibo?q=%23MiuMiu%E7%9B%B4%E6%92%AD%23) `535.1K 🔥` `+44%`
1. [未婚夫去世了该不该赡养对方父母 (If my fiancé dies, should I support his parents?)](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E5%A9%9A%E5%A4%AB%E5%8E%BB%E4%B8%96%E4%BA%86%E8%AF%A5%E4%B8%8D%E8%AF%A5%E8%B5%A1%E5%85%BB%E5%AF%B9%E6%96%B9%E7%88%B6%E6%AF%8D%23) `534.9K 🔥` `+44%`
1. [刘亦菲看秀造型](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E7%9C%8B%E7%A7%80%E9%80%A0%E5%9E%8B%23) `534.6K 🔥` `+43%`
1. [孔雪儿演技](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E6%BC%94%E6%8A%80%23) `534.2K 🔥` `+43%`
1. [李羲承有点像我离职的lastday](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BE%B2%E6%89%BF%E6%9C%89%E7%82%B9%E5%83%8F%E6%88%91%E7%A6%BB%E8%81%8C%E7%9A%84lastday%23) `533.9K 🔥` `+45%`
1. [周雨推测王曼昱爆冷输球原因 (Zhou Yu speculates on the reason for Wang Manyu’s upset loss)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E9%9B%A8%E6%8E%A8%E6%B5%8B%E7%8E%8B%E6%9B%BC%E6%98%B1%E7%88%86%E5%86%B7%E8%BE%93%E7%90%83%E5%8E%9F%E5%9B%A0%23) `533.4K 🔥` `+44%`
1. [张凌赫道歉 (Zhang Linghe apologizes)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E9%81%93%E6%AD%89%23) `7.1M 🔥`
1. [中国两会将为全球创造更多机遇](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E5%B0%86%E4%B8%BA%E5%85%A8%E7%90%83%E5%88%9B%E9%80%A0%E6%9B%B4%E5%A4%9A%E6%9C%BA%E9%81%87%23) `625.4K 🔥`
1. [MiuMiu巴黎时装秀](https://s.weibo.com/weibo?q=%23MiuMiu%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E7%A7%80%23) `624.6K 🔥`
1. [杨舒予担任中国女篮队长](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%88%92%E4%BA%88%E6%8B%85%E4%BB%BB%E4%B8%AD%E5%9B%BD%E5%A5%B3%E7%AF%AE%E9%98%9F%E9%95%BF%23) `624.3K 🔥`
1. [中国队金牌榜奖牌榜都是第一 (The Chinese team ranks first in the gold medal list and the medal list.)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E9%87%91%E7%89%8C%E6%A6%9C%E5%A5%96%E7%89%8C%E6%A6%9C%E9%83%BD%E6%98%AF%E7%AC%AC%E4%B8%80%23) `623.4K 🔥`
1. [院士说文科生绝不会被AI替代](https://s.weibo.com/weibo?q=%23%E9%99%A2%E5%A3%AB%E8%AF%B4%E6%96%87%E7%A7%91%E7%94%9F%E7%BB%9D%E4%B8%8D%E4%BC%9A%E8%A2%ABAI%E6%9B%BF%E4%BB%A3%23) `614.1K 🔥`
1. [建议向新婚夫妇发放住房补贴](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%90%91%E6%96%B0%E5%A9%9A%E5%A4%AB%E5%A6%87%E5%8F%91%E6%94%BE%E4%BD%8F%E6%88%BF%E8%A1%A5%E8%B4%B4%23) `611.8K 🔥`
1. [伊朗提出停火条件 (Iran proposes ceasefire conditions)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8F%90%E5%87%BA%E5%81%9C%E7%81%AB%E6%9D%A1%E4%BB%B6%23) `609.9K 🔥`
1. [逐玉 女主职业自卑](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%A5%B3%E4%B8%BB%E8%81%8C%E4%B8%9A%E8%87%AA%E5%8D%91%23) `607.9K 🔥`
1. [在医院生个孩子只花了2块5 (Giving birth to a baby in the hospital only cost 2.5 yuan)](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%8C%BB%E9%99%A2%E7%94%9F%E4%B8%AA%E5%AD%A9%E5%AD%90%E5%8F%AA%E8%8A%B1%E4%BA%862%E5%9D%975%23) `604.4K 🔥`
1. [村民20元买彩票中100万](https://s.weibo.com/weibo?q=%23%E6%9D%91%E6%B0%9120%E5%85%83%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD100%E4%B8%87%23) `598.5K 🔥`
1. [李羲承退队 (Li Xicheng quits the team)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BE%B2%E6%89%BF%E9%80%80%E9%98%9F%23) `590.4K 🔥`
1. [JYP考公上岸了](https://s.weibo.com/weibo?q=%23JYP%E8%80%83%E5%85%AC%E4%B8%8A%E5%B2%B8%E4%BA%86%23) `538.5K 🔥`
1. [把果蝇的大脑复制到电脑](https://s.weibo.com/weibo?q=%23%E6%8A%8A%E6%9E%9C%E8%9D%87%E7%9A%84%E5%A4%A7%E8%84%91%E5%A4%8D%E5%88%B6%E5%88%B0%E7%94%B5%E8%84%91%23) `537.6K 🔥`
1. [杨紫紫色高定](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%B4%AB%E8%89%B2%E9%AB%98%E5%AE%9A%23) `537.1K 🔥`
1. [22个月大宝宝在院子里慵懒躺倒晒太阳](https://s.weibo.com/weibo?q=%2322%E4%B8%AA%E6%9C%88%E5%A4%A7%E5%AE%9D%E5%AE%9D%E5%9C%A8%E9%99%A2%E5%AD%90%E9%87%8C%E6%85%B5%E6%87%92%E8%BA%BA%E5%80%92%E6%99%92%E5%A4%AA%E9%98%B3%23) `537.0K 🔥`
1. [2026年安排国防支出1.94万亿元](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E5%AE%89%E6%8E%92%E5%9B%BD%E9%98%B2%E6%94%AF%E5%87%BA1.94%E4%B8%87%E4%BA%BF%E5%85%83%23) `620.1K 🔥` `-39%`
1. [国乒人才梯队建设怎么样 (How about the construction of the national table tennis talent echelon?)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%B9%92%E4%BA%BA%E6%89%8D%E6%A2%AF%E9%98%9F%E5%BB%BA%E8%AE%BE%E6%80%8E%E4%B9%88%E6%A0%B7%23) `533.3K 🔥` `-22%`

Updated at 2026-03-10 23:11:50

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
