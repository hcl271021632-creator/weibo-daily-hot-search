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

1. [美团外卖送开工好礼 (Meituan’s takeaway delivery starts with gifts)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%A2%E5%A4%96%E5%8D%96%E9%80%81%E5%BC%80%E5%B7%A5%E5%A5%BD%E7%A4%BC%23) `467.8K 🔥` `NEW`
1. [杨紫允许自己绕个弯](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E5%85%81%E8%AE%B8%E8%87%AA%E5%B7%B1%E7%BB%95%E4%B8%AA%E5%BC%AF%23) `234.9K 🔥` `NEW`
1. [欠款1000万亿当事人这次真要逾期了](https://s.weibo.com/weibo?q=%23%E6%AC%A0%E6%AC%BE1000%E4%B8%87%E4%BA%BF%E5%BD%93%E4%BA%8B%E4%BA%BA%E8%BF%99%E6%AC%A1%E7%9C%9F%E8%A6%81%E9%80%BE%E6%9C%9F%E4%BA%86%23) `230.8K 🔥` `NEW`
1. [一点点](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%23) `146.1K 🔥` `NEW`
1. [杨洋对接回应复工](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%AF%B9%E6%8E%A5%E5%9B%9E%E5%BA%94%E5%A4%8D%E5%B7%A5%23) `145.7K 🔥` `NEW`
1. [安卓机皇三星S26上手体验](https://s.weibo.com/weibo?q=%23%E5%AE%89%E5%8D%93%E6%9C%BA%E7%9A%87%E4%B8%89%E6%98%9FS26%E4%B8%8A%E6%89%8B%E4%BD%93%E9%AA%8C%23) `145.4K 🔥` `NEW`
1. [王子文我在现偶圈等了你三年](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AD%90%E6%96%87%E6%88%91%E5%9C%A8%E7%8E%B0%E5%81%B6%E5%9C%88%E7%AD%89%E4%BA%86%E4%BD%A0%E4%B8%89%E5%B9%B4%23) `139.8K 🔥` `NEW`
1. [男子将博士学位证折成元宝烧给爷爷](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%B0%86%E5%8D%9A%E5%A3%AB%E5%AD%A6%E4%BD%8D%E8%AF%81%E6%8A%98%E6%88%90%E5%85%83%E5%AE%9D%E7%83%A7%E7%BB%99%E7%88%B7%E7%88%B7%23) `138.8K 🔥` `NEW`
1. [新员工上班带水杯的含义](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%91%98%E5%B7%A5%E4%B8%8A%E7%8F%AD%E5%B8%A6%E6%B0%B4%E6%9D%AF%E7%9A%84%E5%90%AB%E4%B9%89%23) `101.0K 🔥` `NEW`
1. [A股行情](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E8%A1%8C%E6%83%85%23) `100.5K 🔥` `NEW`
1. [陈飞宇叫孙千洗衣粉儿 (Chen Feiyu calls Sun Qian washing powder)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E5%8F%AB%E5%AD%99%E5%8D%83%E6%B4%97%E8%A1%A3%E7%B2%89%E5%84%BF%23) `100.2K 🔥` `NEW`
1. [瞿桦强吻方穆静](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E6%A1%A6%E5%BC%BA%E5%90%BB%E6%96%B9%E7%A9%86%E9%9D%99%23) `93.1K 🔥` `NEW`
1. [希望老丈人退彩礼不再成为新闻](https://s.weibo.com/weibo?q=%23%E5%B8%8C%E6%9C%9B%E8%80%81%E4%B8%88%E4%BA%BA%E9%80%80%E5%BD%A9%E7%A4%BC%E4%B8%8D%E5%86%8D%E6%88%90%E4%B8%BA%E6%96%B0%E9%97%BB%23) `90.7K 🔥` `NEW`
1. [三亚毁约民宿被罚35万](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E6%AF%81%E7%BA%A6%E6%B0%91%E5%AE%BF%E8%A2%AB%E7%BD%9A35%E4%B8%87%23) `88.8K 🔥` `NEW`
1. [宋雨琦说喜欢白鹿李佩仪妆造](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E8%AF%B4%E5%96%9C%E6%AC%A2%E7%99%BD%E9%B9%BF%E6%9D%8E%E4%BD%A9%E4%BB%AA%E5%A6%86%E9%80%A0%23) `86.6K 🔥` `NEW`
1. [韩国女生第一次来中国买彩妆](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E5%A5%B3%E7%94%9F%E7%AC%AC%E4%B8%80%E6%AC%A1%E6%9D%A5%E4%B8%AD%E5%9B%BD%E4%B9%B0%E5%BD%A9%E5%A6%86%23) `81.7K 🔥` `NEW`
1. [在卧室装出了三室一厅](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%8D%A7%E5%AE%A4%E8%A3%85%E5%87%BA%E4%BA%86%E4%B8%89%E5%AE%A4%E4%B8%80%E5%8E%85%23) `78.4K 🔥` `NEW`
1. [可灵AI力压众多海外模型登顶全球第一](https://s.weibo.com/weibo?q=%23%E5%8F%AF%E7%81%B5AI%E5%8A%9B%E5%8E%8B%E4%BC%97%E5%A4%9A%E6%B5%B7%E5%A4%96%E6%A8%A1%E5%9E%8B%E7%99%BB%E9%A1%B6%E5%85%A8%E7%90%83%E7%AC%AC%E4%B8%80%23) `74.8K 🔥` `NEW`
1. [男子节后返家价值几万乌龟全被煮](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%8A%82%E5%90%8E%E8%BF%94%E5%AE%B6%E4%BB%B7%E5%80%BC%E5%87%A0%E4%B8%87%E4%B9%8C%E9%BE%9F%E5%85%A8%E8%A2%AB%E7%85%AE%23) `785.8K 🔥` `+42%`
1. [唐国强也去演短剧了](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%9B%BD%E5%BC%BA%E4%B9%9F%E5%8E%BB%E6%BC%94%E7%9F%AD%E5%89%A7%E4%BA%86%23) `438.5K 🔥` `+165%`
1. [王安宇推了半天凶手是自己 (Wang Anyu pushed for a long time that he was the murderer.)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E6%8E%A8%E4%BA%86%E5%8D%8A%E5%A4%A9%E5%87%B6%E6%89%8B%E6%98%AF%E8%87%AA%E5%B7%B1%23) `319.0K 🔥` `+61%`
1. [坐顺风车排泄后失联男子被封号](https://s.weibo.com/weibo?q=%23%E5%9D%90%E9%A1%BA%E9%A3%8E%E8%BD%A6%E6%8E%92%E6%B3%84%E5%90%8E%E5%A4%B1%E8%81%94%E7%94%B7%E5%AD%90%E8%A2%AB%E5%B0%81%E5%8F%B7%23) `145.6K 🔥` `+59%`
1. [微信能看图片使用次数了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%83%BD%E7%9C%8B%E5%9B%BE%E7%89%87%E4%BD%BF%E7%94%A8%E6%AC%A1%E6%95%B0%E4%BA%86%23) `1.1M 🔥`
1. [美国从陈志案获利150亿美元 (The United States gained US$15 billion from the Chen Zhi case)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%BB%8E%E9%99%88%E5%BF%97%E6%A1%88%E8%8E%B7%E5%88%A9150%E4%BA%BF%E7%BE%8E%E5%85%83%23) `647.7K 🔥`
1. [医生建议做美甲至少保留一个原甲](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%81%9A%E7%BE%8E%E7%94%B2%E8%87%B3%E5%B0%91%E4%BF%9D%E7%95%99%E4%B8%80%E4%B8%AA%E5%8E%9F%E7%94%B2%23) `208.5K 🔥`
1. [周涛也开始拍短剧了 (Zhou Tao also started filming short plays)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B6%9B%E4%B9%9F%E5%BC%80%E5%A7%8B%E6%8B%8D%E7%9F%AD%E5%89%A7%E4%BA%86%23) `145.4K 🔥`
1. [时代峰峻否认王橹杰私联](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E5%90%A6%E8%AE%A4%E7%8E%8B%E6%A9%B9%E6%9D%B0%E7%A7%81%E8%81%94%23) `114.6K 🔥`
1. [猫 待会去了姥姥家使劲哭](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E5%BE%85%E4%BC%9A%E5%8E%BB%E4%BA%86%E5%A7%A5%E5%A7%A5%E5%AE%B6%E4%BD%BF%E5%8A%B2%E5%93%AD%23) `110.1K 🔥`
1. [2026考研查分时间](https://s.weibo.com/weibo?q=%232026%E8%80%83%E7%A0%94%E6%9F%A5%E5%88%86%E6%97%B6%E9%97%B4%23) `110.0K 🔥`
1. [张本美和鹰眼挑战失败](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9C%AC%E7%BE%8E%E5%92%8C%E9%B9%B0%E7%9C%BC%E6%8C%91%E6%88%98%E5%A4%B1%E8%B4%A5%23) `94.5K 🔥`
1. [杨幂柳智敏Prada撞衫 (Yang Mi and Liu Zhimin in Prada shirt)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9F%B3%E6%99%BA%E6%95%8FPrada%E6%92%9E%E8%A1%AB%23) `93.0K 🔥`
1. [夜王票房破亿](https://s.weibo.com/weibo?q=%23%E5%A4%9C%E7%8E%8B%E7%A5%A8%E6%88%BF%E7%A0%B4%E4%BA%BF%23) `82.4K 🔥`
1. [120抵达后40分钟拒抬老人致死](https://s.weibo.com/weibo?q=%23120%E6%8A%B5%E8%BE%BE%E5%90%8E40%E5%88%86%E9%92%9F%E6%8B%92%E6%8A%AC%E8%80%81%E4%BA%BA%E8%87%B4%E6%AD%BB%23) `79.5K 🔥`
1. [男子中669万刷朋友圈查彩票才发现 (A man won 6.69 million and found out after checking the lottery through Moments)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E4%B8%AD669%E4%B8%87%E5%88%B7%E6%9C%8B%E5%8F%8B%E5%9C%88%E6%9F%A5%E5%BD%A9%E7%A5%A8%E6%89%8D%E5%8F%91%E7%8E%B0%23) `350.3K 🔥` `-58%`
1. [金正恩称韩国是彻底的敌国](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E7%A7%B0%E9%9F%A9%E5%9B%BD%E6%98%AF%E5%BD%BB%E5%BA%95%E7%9A%84%E6%95%8C%E5%9B%BD%23) `233.2K 🔥` `-62%`
1. [董宇辉休了工作以来最长春节假](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AE%87%E8%BE%89%E4%BC%91%E4%BA%86%E5%B7%A5%E4%BD%9C%E4%BB%A5%E6%9D%A5%E6%9C%80%E9%95%BF%E6%98%A5%E8%8A%82%E5%81%87%23) `146.1K 🔥` `-73%`
1. [向佑不满遗产分配直喊不公平](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%91%E4%B8%8D%E6%BB%A1%E9%81%97%E4%BA%A7%E5%88%86%E9%85%8D%E7%9B%B4%E5%96%8A%E4%B8%8D%E5%85%AC%E5%B9%B3%23) `146.0K 🔥` `-73%`
1. [男子地铁猥亵女子称像年轻时的妻子](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%9C%B0%E9%93%81%E7%8C%A5%E4%BA%B5%E5%A5%B3%E5%AD%90%E7%A7%B0%E5%83%8F%E5%B9%B4%E8%BD%BB%E6%97%B6%E7%9A%84%E5%A6%BB%E5%AD%90%23) `145.8K 🔥` `-39%`
1. [男演员点赞和刘晓庆搭戏是工伤](https://s.weibo.com/weibo?q=%23%E7%94%B7%E6%BC%94%E5%91%98%E7%82%B9%E8%B5%9E%E5%92%8C%E5%88%98%E6%99%93%E5%BA%86%E6%90%AD%E6%88%8F%E6%98%AF%E5%B7%A5%E4%BC%A4%23) `145.8K 🔥` `-73%`
1. [小猫守家26天在主人床上拉满便便](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E5%AE%88%E5%AE%B626%E5%A4%A9%E5%9C%A8%E4%B8%BB%E4%BA%BA%E5%BA%8A%E4%B8%8A%E6%8B%89%E6%BB%A1%E4%BE%BF%E4%BE%BF%23) `145.6K 🔥` `-25%`
1. [关晓彤这段戏我比男主更先爱上女主](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E8%BF%99%E6%AE%B5%E6%88%8F%E6%88%91%E6%AF%94%E7%94%B7%E4%B8%BB%E6%9B%B4%E5%85%88%E7%88%B1%E4%B8%8A%E5%A5%B3%E4%B8%BB%23) `145.5K 🔥` `-76%`
1. [周杰伦结婚田馥甄有了讽刺的情书](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E7%BB%93%E5%A9%9A%E7%94%B0%E9%A6%A5%E7%94%84%E6%9C%89%E4%BA%86%E8%AE%BD%E5%88%BA%E7%9A%84%E6%83%85%E4%B9%A6%23) `145.3K 🔥` `-25%`
1. [刘晓庆75岁再演少女](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%8675%E5%B2%81%E5%86%8D%E6%BC%94%E5%B0%91%E5%A5%B3%23) `145.0K 🔥` `-75%`
1. [女子嘴角起泡未重视竟脑死亡 (Woman's mouth blistered but she didn't pay attention and ended up brain dead)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%98%B4%E8%A7%92%E8%B5%B7%E6%B3%A1%E6%9C%AA%E9%87%8D%E8%A7%86%E7%AB%9F%E8%84%91%E6%AD%BB%E4%BA%A1%23) `144.5K 🔥` `-74%`
1. [爱泼斯坦案曝光霍金与比基尼女子合影 (Epstein case exposes Hawking posing with bikini woman)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%B3%BC%E6%96%AF%E5%9D%A6%E6%A1%88%E6%9B%9D%E5%85%89%E9%9C%8D%E9%87%91%E4%B8%8E%E6%AF%94%E5%9F%BA%E5%B0%BC%E5%A5%B3%E5%AD%90%E5%90%88%E5%BD%B1%23) `141.9K 🔥` `-50%`
1. [鹿哈说没有鹿晗就没有自己的今天](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E8%AF%B4%E6%B2%A1%E6%9C%89%E9%B9%BF%E6%99%97%E5%B0%B1%E6%B2%A1%E6%9C%89%E8%87%AA%E5%B7%B1%E7%9A%84%E4%BB%8A%E5%A4%A9%23) `110.0K 🔥` `-60%`
1. [花10万做折角腰整形醒来浑身血水](https://s.weibo.com/weibo?q=%23%E8%8A%B110%E4%B8%87%E5%81%9A%E6%8A%98%E8%A7%92%E8%85%B0%E6%95%B4%E5%BD%A2%E9%86%92%E6%9D%A5%E6%B5%91%E8%BA%AB%E8%A1%80%E6%B0%B4%23) `97.8K 🔥` `-83%`
1. [考研成绩 (Postgraduate entrance examination results)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E6%88%90%E7%BB%A9%23) `88.8K 🔥` `-54%`
1. [神童与父母断绝联系](https://s.weibo.com/weibo?q=%23%E7%A5%9E%E7%AB%A5%E4%B8%8E%E7%88%B6%E6%AF%8D%E6%96%AD%E7%BB%9D%E8%81%94%E7%B3%BB%23) `88.0K 🔥` `-53%`
1. [垃圾桶内有小孩父亲称不要救他](https://s.weibo.com/weibo?q=%23%E5%9E%83%E5%9C%BE%E6%A1%B6%E5%86%85%E6%9C%89%E5%B0%8F%E5%AD%A9%E7%88%B6%E4%BA%B2%E7%A7%B0%E4%B8%8D%E8%A6%81%E6%95%91%E4%BB%96%23) `86.3K 🔥` `-32%`
1. [三星发布会现场直击](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%98%9F%E5%8F%91%E5%B8%83%E4%BC%9A%E7%8E%B0%E5%9C%BA%E7%9B%B4%E5%87%BB%23) `82.0K 🔥` `-58%`

Updated at 2026-02-26 16:02:35

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
