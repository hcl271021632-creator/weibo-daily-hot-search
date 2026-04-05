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

1. [莫氏鸡煲老板儿子发声 (The son of the owner of Mo’s Chicken Pot speaks out)](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%B0%8F%E9%B8%A1%E7%85%B2%E8%80%81%E6%9D%BF%E5%84%BF%E5%AD%90%E5%8F%91%E5%A3%B0%23) `750.5K 🔥` `NEW`
1. [李小冉老辈子的颜值不是说说的](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%B0%8F%E5%86%89%E8%80%81%E8%BE%88%E5%AD%90%E7%9A%84%E9%A2%9C%E5%80%BC%E4%B8%8D%E6%98%AF%E8%AF%B4%E8%AF%B4%E7%9A%84%23) `348.5K 🔥` `NEW`
1. [张雪妻子晒儿子练车视频](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%A6%BB%E5%AD%90%E6%99%92%E5%84%BF%E5%AD%90%E7%BB%83%E8%BD%A6%E8%A7%86%E9%A2%91%23) `213.4K 🔥` `NEW`
1. [周杰伦演唱会大屏上的昆凌](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%BC%94%E5%94%B1%E4%BC%9A%E5%A4%A7%E5%B1%8F%E4%B8%8A%E7%9A%84%E6%98%86%E5%87%8C%23) `163.5K 🔥` `NEW`
1. [曝cream不想和Tian打比赛](https://s.weibo.com/weibo?q=%23%E6%9B%9Dcream%E4%B8%8D%E6%83%B3%E5%92%8CTian%E6%89%93%E6%AF%94%E8%B5%9B%23) `161.1K 🔥` `NEW`
1. [董宇辉遭遇回旋镖](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AE%87%E8%BE%89%E9%81%AD%E9%81%87%E5%9B%9E%E6%97%8B%E9%95%96%23) `159.2K 🔥` `NEW`
1. [重庆官方通报飞行器坠落事故](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%E9%A3%9E%E8%A1%8C%E5%99%A8%E5%9D%A0%E8%90%BD%E4%BA%8B%E6%95%85%23) `147.9K 🔥` `NEW`
1. [以色列将打击伊朗的摇钱树](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%B0%86%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%E7%9A%84%E6%91%87%E9%92%B1%E6%A0%91%23) `146.9K 🔥` `NEW`
1. [男子钓7条鱼获利50元被判刑](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%92%937%E6%9D%A1%E9%B1%BC%E8%8E%B7%E5%88%A950%E5%85%83%E8%A2%AB%E5%88%A4%E5%88%91%23) `127.8K 🔥` `NEW`
1. [清明节](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E8%8A%82%23) `106.5K 🔥` `NEW`
1. [为什么人到中年要坚持运动 (Why people should continue to exercise in middle age)](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BA%BA%E5%88%B0%E4%B8%AD%E5%B9%B4%E8%A6%81%E5%9D%9A%E6%8C%81%E8%BF%90%E5%8A%A8%23) `103.5K 🔥` `NEW`
1. [老虎卖萌吐舌头被同事呲牙教育](https://s.weibo.com/weibo?q=%23%E8%80%81%E8%99%8E%E5%8D%96%E8%90%8C%E5%90%90%E8%88%8C%E5%A4%B4%E8%A2%AB%E5%90%8C%E4%BA%8B%E5%91%B2%E7%89%99%E6%95%99%E8%82%B2%23) `103.3K 🔥` `NEW`
1. [乘风Queen前三](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8EQueen%E5%89%8D%E4%B8%89%23) `93.8K 🔥` `NEW`
1. [伊朗称将全面控制领空](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%B0%86%E5%85%A8%E9%9D%A2%E6%8E%A7%E5%88%B6%E9%A2%86%E7%A9%BA%23) `92.4K 🔥` `NEW`
1. [伊拒绝特朗普48小时通牒](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%8B%92%E7%BB%9D%E7%89%B9%E6%9C%97%E6%99%AE48%E5%B0%8F%E6%97%B6%E9%80%9A%E7%89%92%23) `74.4K 🔥` `NEW`
1. [易烊千玺AI侵权维权](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BAAI%E4%BE%B5%E6%9D%83%E7%BB%B4%E6%9D%83%23) `70.6K 🔥` `NEW`
1. [女子清明前发现姥爷坟头被平](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%B8%85%E6%98%8E%E5%89%8D%E5%8F%91%E7%8E%B0%E5%A7%A5%E7%88%B7%E5%9D%9F%E5%A4%B4%E8%A2%AB%E5%B9%B3%23) `68.8K 🔥` `NEW`
1. [张雪没拿补贴却拿冠军](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E6%B2%A1%E6%8B%BF%E8%A1%A5%E8%B4%B4%E5%8D%B4%E6%8B%BF%E5%86%A0%E5%86%9B%23) `68.5K 🔥` `NEW`
1. [金价3月累计下跌15%](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B73%E6%9C%88%E7%B4%AF%E8%AE%A1%E4%B8%8B%E8%B7%8C15%25%23) `65.7K 🔥` `NEW`
1. [巴萨2比1逆转十人马竞](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E8%90%A82%E6%AF%941%E9%80%86%E8%BD%AC%E5%8D%81%E4%BA%BA%E9%A9%AC%E7%AB%9E%23) `65.1K 🔥` `NEW`
1. [瑞幸回应徐州一门店被嘲像公厕 (Luckin responded to a store in Xuzhou that was ridiculed like a public toilet)](https://s.weibo.com/weibo?q=%23%E7%91%9E%E5%B9%B8%E5%9B%9E%E5%BA%94%E5%BE%90%E5%B7%9E%E4%B8%80%E9%97%A8%E5%BA%97%E8%A2%AB%E5%98%B2%E5%83%8F%E5%85%AC%E5%8E%95%23) `64.5K 🔥` `NEW`
1. [废品回收站店主回应收到退役歼六](https://s.weibo.com/weibo?q=%23%E5%BA%9F%E5%93%81%E5%9B%9E%E6%94%B6%E7%AB%99%E5%BA%97%E4%B8%BB%E5%9B%9E%E5%BA%94%E6%94%B6%E5%88%B0%E9%80%80%E5%BD%B9%E6%AD%BC%E5%85%AD%23) `64.3K 🔥` `NEW`
1. [美议员说对伊战争像捅了马蜂窝](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%AE%AE%E5%91%98%E8%AF%B4%E5%AF%B9%E4%BC%8A%E6%88%98%E4%BA%89%E5%83%8F%E6%8D%85%E4%BA%86%E9%A9%AC%E8%9C%82%E7%AA%9D%23) `59.4K 🔥` `NEW`
1. [德国针对中餐从业人员恶性案件频发](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E5%9B%BD%E9%92%88%E5%AF%B9%E4%B8%AD%E9%A4%90%E4%BB%8E%E4%B8%9A%E4%BA%BA%E5%91%98%E6%81%B6%E6%80%A7%E6%A1%88%E4%BB%B6%E9%A2%91%E5%8F%91%23) `59.3K 🔥` `NEW`
1. [掘金终结马刺十一连胜](https://s.weibo.com/weibo?q=%23%E6%8E%98%E9%87%91%E7%BB%88%E7%BB%93%E9%A9%AC%E5%88%BA%E5%8D%81%E4%B8%80%E8%BF%9E%E8%83%9C%23) `57.1K 🔥` `NEW`
1. [莫氏鸡煲老板说这种钱赚得不划算](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%B0%8F%E9%B8%A1%E7%85%B2%E8%80%81%E6%9D%BF%E8%AF%B4%E8%BF%99%E7%A7%8D%E9%92%B1%E8%B5%9A%E5%BE%97%E4%B8%8D%E5%88%92%E7%AE%97%23) `52.9K 🔥` `NEW`
1. [浪姐直播谢娜念的感谢词](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E7%9B%B4%E6%92%AD%E8%B0%A2%E5%A8%9C%E5%BF%B5%E7%9A%84%E6%84%9F%E8%B0%A2%E8%AF%8D%23) `52.8K 🔥` `NEW`
1. [多方回应快递沾染血迹被更换包装](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%96%B9%E5%9B%9E%E5%BA%94%E5%BF%AB%E9%80%92%E6%B2%BE%E6%9F%93%E8%A1%80%E8%BF%B9%E8%A2%AB%E6%9B%B4%E6%8D%A2%E5%8C%85%E8%A3%85%23) `1.1M 🔥` `+1130%`
1. [李清明  清明节myday](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%B8%85%E6%98%8E%20%20%E6%B8%85%E6%98%8E%E8%8A%82myday%23) `157.6K 🔥` `+155%`
1. [食客睡车里等全网最不想红鸡煲开门](https://s.weibo.com/weibo?q=%23%E9%A3%9F%E5%AE%A2%E7%9D%A1%E8%BD%A6%E9%87%8C%E7%AD%89%E5%85%A8%E7%BD%91%E6%9C%80%E4%B8%8D%E6%83%B3%E7%BA%A2%E9%B8%A1%E7%85%B2%E5%BC%80%E9%97%A8%23) `151.7K 🔥` `+163%`
1. [文淇第一次做妇科检查的不适感受 (Wen Qi’s discomfort during her first gynecological examination)](https://s.weibo.com/weibo?q=%23%E6%96%87%E6%B7%87%E7%AC%AC%E4%B8%80%E6%AC%A1%E5%81%9A%E5%A6%87%E7%A7%91%E6%A3%80%E6%9F%A5%E7%9A%84%E4%B8%8D%E9%80%82%E6%84%9F%E5%8F%97%23) `150.0K 🔥` `+57%`
1. [叶一茜 05超女的含金量 (Ye Yiqian 05 The gold content of super girl)](https://s.weibo.com/weibo?q=%23%E5%8F%B6%E4%B8%80%E8%8C%9C%2005%E8%B6%85%E5%A5%B3%E7%9A%84%E5%90%AB%E9%87%91%E9%87%8F%23) `132.7K 🔥` `+42%`
1. [张凌赫脱稿演讲六分半的含金量 (The gold content of six and a half minutes of Zhang Linghe’s unscripted speech)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%84%B1%E7%A8%BF%E6%BC%94%E8%AE%B2%E5%85%AD%E5%88%86%E5%8D%8A%E7%9A%84%E5%90%AB%E9%87%91%E9%87%8F%23) `115.9K 🔥` `+25%`
1. [黄晓明晒和儿子春日骑行照 (Huang Xiaoming posted photos of riding with his son in spring)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E6%99%92%E5%92%8C%E5%84%BF%E5%AD%90%E6%98%A5%E6%97%A5%E9%AA%91%E8%A1%8C%E7%85%A7%23) `115.2K 🔥` `+39%`
1. [有些东西你看不见不代表它不存在](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%BA%9B%E4%B8%9C%E8%A5%BF%E4%BD%A0%E7%9C%8B%E4%B8%8D%E8%A7%81%E4%B8%8D%E4%BB%A3%E8%A1%A8%E5%AE%83%E4%B8%8D%E5%AD%98%E5%9C%A8%23) `108.7K 🔥` `+90%`
1. [面部八段锦养出好气色](https://s.weibo.com/weibo?q=%23%E9%9D%A2%E9%83%A8%E5%85%AB%E6%AE%B5%E9%94%A6%E5%85%BB%E5%87%BA%E5%A5%BD%E6%B0%94%E8%89%B2%23) `84.7K 🔥` `+31%`
1. [房主任体重200斤膝盖积液](https://s.weibo.com/weibo?q=%23%E6%88%BF%E4%B8%BB%E4%BB%BB%E4%BD%93%E9%87%8D200%E6%96%A4%E8%86%9D%E7%9B%96%E7%A7%AF%E6%B6%B2%23) `69.2K 🔥` `+51%`
1. [清明假期叠加春假激发经济新活力 (Qingming holiday combined with spring break stimulates new economic vitality)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E5%8F%A0%E5%8A%A0%E6%98%A5%E5%81%87%E6%BF%80%E5%8F%91%E7%BB%8F%E6%B5%8E%E6%96%B0%E6%B4%BB%E5%8A%9B%23) `596.6K 🔥`
1. [伊朗击落2架美战机击中2架黑鹰](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%87%BB%E8%90%BD2%E6%9E%B6%E7%BE%8E%E6%88%98%E6%9C%BA%E5%87%BB%E4%B8%AD2%E6%9E%B6%E9%BB%91%E9%B9%B0%23) `166.0K 🔥`
1. [海关截获18厘米长活体帝王蝎 (Customs intercepts 18cm long live emperor scorpion)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%85%B3%E6%88%AA%E8%8E%B718%E5%8E%98%E7%B1%B3%E9%95%BF%E6%B4%BB%E4%BD%93%E5%B8%9D%E7%8E%8B%E8%9D%8E%23) `113.0K 🔥`
1. [十日终焉作者谈青岛出现血月 (The author of Ten Days End talks about the blood moon in Qingdao)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E4%BD%9C%E8%80%85%E8%B0%88%E9%9D%92%E5%B2%9B%E5%87%BA%E7%8E%B0%E8%A1%80%E6%9C%88%23) `102.6K 🔥`
1. [小伙家住46楼免费看周杰伦演唱会 (This guy lives on the 46th floor and can watch Jay Chou's concert for free)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%AE%B6%E4%BD%8F46%E6%A5%BC%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%BC%94%E5%94%B1%E4%BC%9A%23) `74.4K 🔥`
1. [陈凯琳老公是郑嘉颖](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%87%AF%E7%90%B3%E8%80%81%E5%85%AC%E6%98%AF%E9%83%91%E5%98%89%E9%A2%96%23) `58.5K 🔥`
1. [12306回应男子高铁站抽烟无人管 (12306 responded to man smoking at high-speed rail station without supervision)](https://s.weibo.com/weibo?q=%2312306%E5%9B%9E%E5%BA%94%E7%94%B7%E5%AD%90%E9%AB%98%E9%93%81%E7%AB%99%E6%8A%BD%E7%83%9F%E6%97%A0%E4%BA%BA%E7%AE%A1%23) `55.4K 🔥`
1. [3岁女童被毒蛇咬伤假死3天奇迹生还 (3-year-old girl was bitten by a venomous snake and miraculously survived for 3 days after pretending to be dead)](https://s.weibo.com/weibo?q=%233%E5%B2%81%E5%A5%B3%E7%AB%A5%E8%A2%AB%E6%AF%92%E8%9B%87%E5%92%AC%E4%BC%A4%E5%81%87%E6%AD%BB3%E5%A4%A9%E5%A5%87%E8%BF%B9%E7%94%9F%E8%BF%98%23) `181.2K 🔥` `-74%`
1. [伊朗无人机大规模打击本古里安机场 (Iranian drones carry out massive strike on Ben-Gurion Airport)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%97%A0%E4%BA%BA%E6%9C%BA%E5%A4%A7%E8%A7%84%E6%A8%A1%E6%89%93%E5%87%BB%E6%9C%AC%E5%8F%A4%E9%87%8C%E5%AE%89%E6%9C%BA%E5%9C%BA%23) `167.4K 🔥` `-46%`
1. [乘风Queen (ChengfengQueen)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8EQueen%23) `155.5K 🔥` `-84%`
1. [我国过敏性鼻炎患者数量攀升](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E8%BF%87%E6%95%8F%E6%80%A7%E9%BC%BB%E7%82%8E%E6%82%A3%E8%80%85%E6%95%B0%E9%87%8F%E6%94%80%E5%8D%87%23) `58.3K 🔥` `-24%`
1. [许昕说一直有人希望王楚钦输](https://s.weibo.com/weibo?q=%23%E8%AE%B8%E6%98%95%E8%AF%B4%E4%B8%80%E7%9B%B4%E6%9C%89%E4%BA%BA%E5%B8%8C%E6%9C%9B%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%BE%93%23) `56.4K 🔥` `-42%`
1. [莫氏鸡煲周边商户发声 (Merchants around Mo’s Chicken Pot speak out)](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%B0%8F%E9%B8%A1%E7%85%B2%E5%91%A8%E8%BE%B9%E5%95%86%E6%88%B7%E5%8F%91%E5%A3%B0%23) `55.0K 🔥` `-37%`

Updated at 2026-04-05 09:26:35

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
