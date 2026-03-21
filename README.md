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

1. [超话同人绘画大赛 (Super Talk Fan Drawing Contest)](https://s.weibo.com/weibo?q=%23%E8%B6%85%E8%AF%9D%E5%90%8C%E4%BA%BA%E7%BB%98%E7%94%BB%E5%A4%A7%E8%B5%9B%23) `489.6K 🔥` `NEW`
1. [身体少抵抗 减重难题轻松答](https://s.weibo.com/weibo?q=%23%E8%BA%AB%E4%BD%93%E5%B0%91%E6%8A%B5%E6%8A%97%20%E5%87%8F%E9%87%8D%E9%9A%BE%E9%A2%98%E8%BD%BB%E6%9D%BE%E7%AD%94%23) `199.2K 🔥` `NEW`
1. [谢征俞宝儿是连襟](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E4%BF%9E%E5%AE%9D%E5%84%BF%E6%98%AF%E8%BF%9E%E8%A5%9F%23) `162.2K 🔥` `NEW`
1. [梅姨同居男友说她不戴首饰](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E7%94%B7%E5%8F%8B%E8%AF%B4%E5%A5%B9%E4%B8%8D%E6%88%B4%E9%A6%96%E9%A5%B0%23) `143.5K 🔥` `NEW`
1. [张凌赫男大自拍](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B7%E5%A4%A7%E8%87%AA%E6%8B%8D%23) `141.9K 🔥` `NEW`
1. [痞幼因网红身份被邻居排挤](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%9B%A0%E7%BD%91%E7%BA%A2%E8%BA%AB%E4%BB%BD%E8%A2%AB%E9%82%BB%E5%B1%85%E6%8E%92%E6%8C%A4%23) `115.9K 🔥` `NEW`
1. [KPL](https://s.weibo.com/weibo?q=%23KPL%23) `81.9K 🔥` `NEW`
1. [以色列刚放完狠话防空警报就响了](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%88%9A%E6%94%BE%E5%AE%8C%E7%8B%A0%E8%AF%9D%E9%98%B2%E7%A9%BA%E8%AD%A6%E6%8A%A5%E5%B0%B1%E5%93%8D%E4%BA%86%23) `75.6K 🔥` `NEW`
1. [梅姨同居男友都看不到她的身份证](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E7%94%B7%E5%8F%8B%E9%83%BD%E7%9C%8B%E4%B8%8D%E5%88%B0%E5%A5%B9%E7%9A%84%E8%BA%AB%E4%BB%BD%E8%AF%81%23) `75.6K 🔥` `NEW`
1. [KSG锁定季后赛胜者组](https://s.weibo.com/weibo?q=%23KSG%E9%94%81%E5%AE%9A%E5%AD%A3%E5%90%8E%E8%B5%9B%E8%83%9C%E8%80%85%E7%BB%84%23) `75.4K 🔥` `NEW`
1. [粉丝误把五月天门票送给韩雨彤 (Fan mistakenly gave Mayday tickets to Han Yutong)](https://s.weibo.com/weibo?q=%23%E7%B2%89%E4%B8%9D%E8%AF%AF%E6%8A%8A%E4%BA%94%E6%9C%88%E5%A4%A9%E9%97%A8%E7%A5%A8%E9%80%81%E7%BB%99%E9%9F%A9%E9%9B%A8%E5%BD%A4%23) `69.4K 🔥` `NEW`
1. [金价大跌后金店生意火爆](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%A4%A7%E8%B7%8C%E5%90%8E%E9%87%91%E5%BA%97%E7%94%9F%E6%84%8F%E7%81%AB%E7%88%86%23) `65.8K 🔥` `NEW`
1. [梅姨与画像相似度不到30%](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E4%B8%8E%E7%94%BB%E5%83%8F%E7%9B%B8%E4%BC%BC%E5%BA%A6%E4%B8%8D%E5%88%B030%25%23) `63.6K 🔥` `NEW`
1. [胡海泉说者来女唱歌不好听](https://s.weibo.com/weibo?q=%23%E8%83%A1%E6%B5%B7%E6%B3%89%E8%AF%B4%E8%80%85%E6%9D%A5%E5%A5%B3%E5%94%B1%E6%AD%8C%E4%B8%8D%E5%A5%BD%E5%90%AC%23) `63.0K 🔥` `NEW`
1. [90后男子为降血糖自制汤药身亡](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E7%94%B7%E5%AD%90%E4%B8%BA%E9%99%8D%E8%A1%80%E7%B3%96%E8%87%AA%E5%88%B6%E6%B1%A4%E8%8D%AF%E8%BA%AB%E4%BA%A1%23) `62.7K 🔥` `NEW`
1. [业内曝男演员比女演员修图难](https://s.weibo.com/weibo?q=%23%E4%B8%9A%E5%86%85%E6%9B%9D%E7%94%B7%E6%BC%94%E5%91%98%E6%AF%94%E5%A5%B3%E6%BC%94%E5%91%98%E4%BF%AE%E5%9B%BE%E9%9A%BE%23) `62.5K 🔥` `NEW`
1. [我们可能高估了老年后的身体状态](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E5%8F%AF%E8%83%BD%E9%AB%98%E4%BC%B0%E4%BA%86%E8%80%81%E5%B9%B4%E5%90%8E%E7%9A%84%E8%BA%AB%E4%BD%93%E7%8A%B6%E6%80%81%23) `61.3K 🔥` `NEW`
1. [归鸾导演在代拍旁边架机位](https://s.weibo.com/weibo?q=%23%E5%BD%92%E9%B8%BE%E5%AF%BC%E6%BC%94%E5%9C%A8%E4%BB%A3%E6%8B%8D%E6%97%81%E8%BE%B9%E6%9E%B6%E6%9C%BA%E4%BD%8D%23) `58.8K 🔥` `NEW`
1. [猫咪意识到抚摸它的不是妈妈](https://s.weibo.com/weibo?q=%23%E7%8C%AB%E5%92%AA%E6%84%8F%E8%AF%86%E5%88%B0%E6%8A%9A%E6%91%B8%E5%AE%83%E7%9A%84%E4%B8%8D%E6%98%AF%E5%A6%88%E5%A6%88%23) `58.2K 🔥` `NEW`
1. [猫猫被自己美了一大跳](https://s.weibo.com/weibo?q=%23%E7%8C%AB%E7%8C%AB%E8%A2%AB%E8%87%AA%E5%B7%B1%E7%BE%8E%E4%BA%86%E4%B8%80%E5%A4%A7%E8%B7%B3%23) `57.9K 🔥` `NEW`
1. [王天辰呲个大牙看郭晓婷笑 (Wang Tianchen showed his big teeth and looked at Guo Xiaoting smiling)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%E5%91%B2%E4%B8%AA%E5%A4%A7%E7%89%99%E7%9C%8B%E9%83%AD%E6%99%93%E5%A9%B7%E7%AC%91%23) `57.0K 🔥` `NEW`
1. [油价调整日历](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E8%B0%83%E6%95%B4%E6%97%A5%E5%8E%86%23) `56.5K 🔥` `NEW`
1. [女子熬夜3个月突然开始对墙讲课](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%86%AC%E5%A4%9C3%E4%B8%AA%E6%9C%88%E7%AA%81%E7%84%B6%E5%BC%80%E5%A7%8B%E5%AF%B9%E5%A2%99%E8%AE%B2%E8%AF%BE%23) `238.4K 🔥` `+87%`
1. [别来工作的地方找我](https://s.weibo.com/weibo?q=%23%E5%88%AB%E6%9D%A5%E5%B7%A5%E4%BD%9C%E7%9A%84%E5%9C%B0%E6%96%B9%E6%89%BE%E6%88%91%23) `196.7K 🔥` `+176%`
1. [迪丽热巴再被叫胖迪很惊讶](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%86%8D%E8%A2%AB%E5%8F%AB%E8%83%96%E8%BF%AA%E5%BE%88%E6%83%8A%E8%AE%B6%23) `156.1K 🔥` `+25%`
1. [曝梁小龙去世两个月没下葬将停棺10年](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%A2%81%E5%B0%8F%E9%BE%99%E5%8E%BB%E4%B8%96%E4%B8%A4%E4%B8%AA%E6%9C%88%E6%B2%A1%E4%B8%8B%E8%91%AC%E5%B0%86%E5%81%9C%E6%A3%BA10%E5%B9%B4%23) `154.8K 🔥` `+23%`
1. [伊朗有意日本船只通行霍尔木兹海峡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%89%E6%84%8F%E6%97%A5%E6%9C%AC%E8%88%B9%E5%8F%AA%E9%80%9A%E8%A1%8C%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `152.9K 🔥` `+26%`
1. [张凌赫田曦薇 所有人都在觊觎我妻子](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%20%E6%89%80%E6%9C%89%E4%BA%BA%E9%83%BD%E5%9C%A8%E8%A7%8A%E8%A7%8E%E6%88%91%E5%A6%BB%E5%AD%90%23) `150.8K 🔥` `+22%`
1. [WB对战KSG](https://s.weibo.com/weibo?q=%23WB%E5%AF%B9%E6%88%98KSG%23) `116.0K 🔥` `+21%`
1. [梅姨长相与公布画像相似度不高](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E9%95%BF%E7%9B%B8%E4%B8%8E%E5%85%AC%E5%B8%83%E7%94%BB%E5%83%8F%E7%9B%B8%E4%BC%BC%E5%BA%A6%E4%B8%8D%E9%AB%98%23) `1.0M 🔥`
1. [白象 土豆泥火鸡面 (White Elephant Mashed Potato Turkey Noodles)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E8%B1%A1%20%E5%9C%9F%E8%B1%86%E6%B3%A5%E7%81%AB%E9%B8%A1%E9%9D%A2%23) `457.9K 🔥`
1. [美军核坟墓辐射量已超切尔诺贝利 (The amount of radiation in the US military's nuclear grave has exceeded that of Chernobyl)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E6%A0%B8%E5%9D%9F%E5%A2%93%E8%BE%90%E5%B0%84%E9%87%8F%E5%B7%B2%E8%B6%85%E5%88%87%E5%B0%94%E8%AF%BA%E8%B4%9D%E5%88%A9%23) `179.4K 🔥`
1. [董事长病逝未成年女儿继承9亿股票](https://s.weibo.com/weibo?q=%23%E8%91%A3%E4%BA%8B%E9%95%BF%E7%97%85%E9%80%9D%E6%9C%AA%E6%88%90%E5%B9%B4%E5%A5%B3%E5%84%BF%E7%BB%A7%E6%89%BF9%E4%BA%BF%E8%82%A1%E7%A5%A8%23) `158.0K 🔥`
1. [谢某某就是梅姨](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E6%9F%90%E6%9F%90%E5%B0%B1%E6%98%AF%E6%A2%85%E5%A7%A8%23) `147.8K 🔥`
1. [网友通过倪妮悄悄话分析出汤唯怀孕了 (Netizens analyzed that Tang Wei was pregnant through Ni Ni’s whispers)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E9%80%9A%E8%BF%87%E5%80%AA%E5%A6%AE%E6%82%84%E6%82%84%E8%AF%9D%E5%88%86%E6%9E%90%E5%87%BA%E6%B1%A4%E5%94%AF%E6%80%80%E5%AD%95%E4%BA%86%23) `146.3K 🔥`
1. [还原梅姨画像神笔警探发声](https://s.weibo.com/weibo?q=%23%E8%BF%98%E5%8E%9F%E6%A2%85%E5%A7%A8%E7%94%BB%E5%83%8F%E7%A5%9E%E7%AC%94%E8%AD%A6%E6%8E%A2%E5%8F%91%E5%A3%B0%23) `140.5K 🔥`
1. [迪丽热巴工作室审美](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%B7%A5%E4%BD%9C%E5%AE%A4%E5%AE%A1%E7%BE%8E%23) `121.3K 🔥`
1. [鹿晗 关晓彤](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `118.9K 🔥`
1. [终于有人吐槽手语舞了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E5%90%90%E6%A7%BD%E6%89%8B%E8%AF%AD%E8%88%9E%E4%BA%86%23) `115.6K 🔥`
1. [徐志胜自曝创业月亏12万](https://s.weibo.com/weibo?q=%23%E5%BE%90%E5%BF%97%E8%83%9C%E8%87%AA%E6%9B%9D%E5%88%9B%E4%B8%9A%E6%9C%88%E4%BA%8F12%E4%B8%87%23) `98.5K 🔥`
1. [原来奚望是故人之女](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%A5%9A%E6%9C%9B%E6%98%AF%E6%95%85%E4%BA%BA%E4%B9%8B%E5%A5%B3%23) `87.7K 🔥`
1. [销售帮客户摇出顶级豹子车牌号](https://s.weibo.com/weibo?q=%23%E9%94%80%E5%94%AE%E5%B8%AE%E5%AE%A2%E6%88%B7%E6%91%87%E5%87%BA%E9%A1%B6%E7%BA%A7%E8%B1%B9%E5%AD%90%E8%BD%A6%E7%89%8C%E5%8F%B7%23) `71.6K 🔥`
1. [余华英 (Yu Huaying)](https://s.weibo.com/weibo?q=%23%E4%BD%99%E5%8D%8E%E8%8B%B1%23) `67.9K 🔥`
1. [高铁卖卫生巾背后看不见的女性需求](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%93%81%E5%8D%96%E5%8D%AB%E7%94%9F%E5%B7%BE%E8%83%8C%E5%90%8E%E7%9C%8B%E4%B8%8D%E8%A7%81%E7%9A%84%E5%A5%B3%E6%80%A7%E9%9C%80%E6%B1%82%23) `60.4K 🔥`
1. [3月婴儿独自在家被子盖脸近2分钟 (A 3-month-old baby’s face was covered with quilt for nearly 2 minutes at home alone)](https://s.weibo.com/weibo?q=%233%E6%9C%88%E5%A9%B4%E5%84%BF%E7%8B%AC%E8%87%AA%E5%9C%A8%E5%AE%B6%E8%A2%AB%E5%AD%90%E7%9B%96%E8%84%B8%E8%BF%912%E5%88%86%E9%92%9F%23) `59.9K 🔥`
1. [梅姨被逮捕 (Aunt May was arrested)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E8%A2%AB%E9%80%AE%E6%8D%95%23) `2.3M 🔥` `-33%`
1. [总会被一棵树的张力震撼到 (I will always be shocked by the tension of a tree)](https://s.weibo.com/weibo?q=%23%E6%80%BB%E4%BC%9A%E8%A2%AB%E4%B8%80%E6%A3%B5%E6%A0%91%E7%9A%84%E5%BC%A0%E5%8A%9B%E9%9C%87%E6%92%BC%E5%88%B0%23) `809.5K 🔥` `-28%`
1. [梅姨男友称与其同居3年没拍照片](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E7%94%B7%E5%8F%8B%E7%A7%B0%E4%B8%8E%E5%85%B6%E5%90%8C%E5%B1%853%E5%B9%B4%E6%B2%A1%E6%8B%8D%E7%85%A7%E7%89%87%23) `404.1K 🔥` `-70%`
1. [女生派出所遭猥亵案家属发声](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E6%B4%BE%E5%87%BA%E6%89%80%E9%81%AD%E7%8C%A5%E4%BA%B5%E6%A1%88%E5%AE%B6%E5%B1%9E%E5%8F%91%E5%A3%B0%23) `84.2K 🔥` `-30%`
1. [男子重病后发现老伴打赏男主播370万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%87%8D%E7%97%85%E5%90%8E%E5%8F%91%E7%8E%B0%E8%80%81%E4%BC%B4%E6%89%93%E8%B5%8F%E7%94%B7%E4%B8%BB%E6%92%AD370%E4%B8%87%23) `75.9K 🔥` `-36%`
1. [倪妮这铁真没白撸](https://s.weibo.com/weibo?q=%23%E5%80%AA%E5%A6%AE%E8%BF%99%E9%93%81%E7%9C%9F%E6%B2%A1%E7%99%BD%E6%92%B8%23) `67.3K 🔥` `-38%`
1. [梅姨2张模拟画像均被指不符](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A82%E5%BC%A0%E6%A8%A1%E6%8B%9F%E7%94%BB%E5%83%8F%E5%9D%87%E8%A2%AB%E6%8C%87%E4%B8%8D%E7%AC%A6%23) `57.8K 🔥` `-51%`

Updated at 2026-03-21 16:40:59

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
