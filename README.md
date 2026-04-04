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

1. [清明假期叠加春假激发经济新活力 (Qingming holiday combined with spring break stimulates new economic vitality)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E5%8F%A0%E5%8A%A0%E6%98%A5%E5%81%87%E6%BF%80%E5%8F%91%E7%BB%8F%E6%B5%8E%E6%96%B0%E6%B4%BB%E5%8A%9B%23) `531.8K 🔥` `NEW`
1. [张雪说logo是淘宝600块做的](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E8%AF%B4logo%E6%98%AF%E6%B7%98%E5%AE%9D600%E5%9D%97%E5%81%9A%E7%9A%84%23) `105.2K 🔥` `NEW`
1. [多方回应快递沾染血迹被更换包装](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%96%B9%E5%9B%9E%E5%BA%94%E5%BF%AB%E9%80%92%E6%B2%BE%E6%9F%93%E8%A1%80%E8%BF%B9%E8%A2%AB%E6%9B%B4%E6%8D%A2%E5%8C%85%E8%A3%85%23) `86.2K 🔥` `NEW`
1. [萧蔷初舞台第一名](https://s.weibo.com/weibo?q=%23%E8%90%A7%E8%94%B7%E5%88%9D%E8%88%9E%E5%8F%B0%E7%AC%AC%E4%B8%80%E5%90%8D%23) `74.3K 🔥` `NEW`
1. [以军空袭伊朗石化设施](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E7%A9%BA%E8%A2%AD%E4%BC%8A%E6%9C%97%E7%9F%B3%E5%8C%96%E8%AE%BE%E6%96%BD%23) `71.7K 🔥` `NEW`
1. [面部八段锦养出好气色](https://s.weibo.com/weibo?q=%23%E9%9D%A2%E9%83%A8%E5%85%AB%E6%AE%B5%E9%94%A6%E5%85%BB%E5%87%BA%E5%A5%BD%E6%B0%94%E8%89%B2%23) `64.6K 🔥` `NEW`
1. [李清明  清明节myday](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%B8%85%E6%98%8E%20%20%E6%B8%85%E6%98%8E%E8%8A%82myday%23) `61.9K 🔥` `NEW`
1. [食客睡车里等全网最不想红鸡煲开门](https://s.weibo.com/weibo?q=%23%E9%A3%9F%E5%AE%A2%E7%9D%A1%E8%BD%A6%E9%87%8C%E7%AD%89%E5%85%A8%E7%BD%91%E6%9C%80%E4%B8%8D%E6%83%B3%E7%BA%A2%E9%B8%A1%E7%85%B2%E5%BC%80%E9%97%A8%23) `57.8K 🔥` `NEW`
1. [有些东西你看不见不代表它不存在](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%BA%9B%E4%B8%9C%E8%A5%BF%E4%BD%A0%E7%9C%8B%E4%B8%8D%E8%A7%81%E4%B8%8D%E4%BB%A3%E8%A1%A8%E5%AE%83%E4%B8%8D%E5%AD%98%E5%9C%A8%23) `57.3K 🔥` `NEW`
1. [南安普顿2比1阿森纳](https://s.weibo.com/weibo?q=%23%E5%8D%97%E5%AE%89%E6%99%AE%E9%A1%BF2%E6%AF%941%E9%98%BF%E6%A3%AE%E7%BA%B3%23) `54.5K 🔥` `NEW`
1. [赵心童10比1希金斯 (Zhao Xintong 10 to 1 Higgins)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E5%BF%83%E7%AB%A510%E6%AF%941%E5%B8%8C%E9%87%91%E6%96%AF%23) `53.9K 🔥` `NEW`
1. [以军大规模打击伊朗基础设施](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E5%A4%A7%E8%A7%84%E6%A8%A1%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%E5%9F%BA%E7%A1%80%E8%AE%BE%E6%96%BD%23) `51.7K 🔥` `NEW`
1. [冯提莫自曝身高体重](https://s.weibo.com/weibo?q=%23%E5%86%AF%E6%8F%90%E8%8E%AB%E8%87%AA%E6%9B%9D%E8%BA%AB%E9%AB%98%E4%BD%93%E9%87%8D%23) `48.4K 🔥` `NEW`
1. [王曼昱谈战胜桥本帆乃香技术细节](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E8%B0%88%E6%88%98%E8%83%9C%E6%A1%A5%E6%9C%AC%E5%B8%86%E4%B9%83%E9%A6%99%E6%8A%80%E6%9C%AF%E7%BB%86%E8%8A%82%23) `47.4K 🔥` `NEW`
1. [房主任体重200斤膝盖积液](https://s.weibo.com/weibo?q=%23%E6%88%BF%E4%B8%BB%E4%BB%BB%E4%BD%93%E9%87%8D200%E6%96%A4%E8%86%9D%E7%9B%96%E7%A7%AF%E6%B6%B2%23) `45.8K 🔥` `NEW`
1. [i狗是e人的玩具](https://s.weibo.com/weibo?q=%23i%E7%8B%97%E6%98%AFe%E4%BA%BA%E7%9A%84%E7%8E%A9%E5%85%B7%23) `39.6K 🔥` `NEW`
1. [乘风Queen (ChengfengQueen)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8EQueen%23) `965.2K 🔥` `+984%`
1. [伊朗击落2架美战机击中2架黑鹰](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%87%BB%E8%90%BD2%E6%9E%B6%E7%BE%8E%E6%88%98%E6%9C%BA%E5%87%BB%E4%B8%AD2%E6%9E%B6%E9%BB%91%E9%B9%B0%23) `182.5K 🔥` `+373%`
1. [莫氏鸡煲周边商户发声 (Merchants around Mo’s Chicken Pot speak out)](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%B0%8F%E9%B8%A1%E7%85%B2%E5%91%A8%E8%BE%B9%E5%95%86%E6%88%B7%E5%8F%91%E5%A3%B0%23) `86.8K 🔥` `+28%`
1. [黄晓明晒和儿子春日骑行照 (Huang Xiaoming posted photos of riding with his son in spring)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E6%99%92%E5%92%8C%E5%84%BF%E5%AD%90%E6%98%A5%E6%97%A5%E9%AA%91%E8%A1%8C%E7%85%A7%23) `82.8K 🔥` `+44%`
1. [我国过敏性鼻炎患者数量攀升](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E8%BF%87%E6%95%8F%E6%80%A7%E9%BC%BB%E7%82%8E%E6%82%A3%E8%80%85%E6%95%B0%E9%87%8F%E6%94%80%E5%8D%87%23) `76.6K 🔥` `+40%`
1. [约奇克说王楚钦赢得实至名归](https://s.weibo.com/weibo?q=%23%E7%BA%A6%E5%A5%87%E5%85%8B%E8%AF%B4%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%B5%A2%E5%BE%97%E5%AE%9E%E8%87%B3%E5%90%8D%E5%BD%92%23) `64.1K 🔥` `+66%`
1. [12306回应男子高铁站抽烟无人管 (12306 responded to man smoking at high-speed rail station without supervision)](https://s.weibo.com/weibo?q=%2312306%E5%9B%9E%E5%BA%94%E7%94%B7%E5%AD%90%E9%AB%98%E9%93%81%E7%AB%99%E6%8A%BD%E7%83%9F%E6%97%A0%E4%BA%BA%E7%AE%A1%23) `57.3K 🔥` `+38%`
1. [徐梦洁 不太好听](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%B4%81%20%E4%B8%8D%E5%A4%AA%E5%A5%BD%E5%90%AC%23) `48.0K 🔥` `+25%`
1. [鞠婧祎这几个小挑眉好灵 (Ju Jingyi is so good at raising eyebrows)](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E8%BF%99%E5%87%A0%E4%B8%AA%E5%B0%8F%E6%8C%91%E7%9C%89%E5%A5%BD%E7%81%B5%23) `47.1K 🔥` `+22%`
1. [3岁女童被毒蛇咬伤假死3天奇迹生还 (3-year-old girl was bitten by a venomous snake and miraculously survived for 3 days after pretending to be dead)](https://s.weibo.com/weibo?q=%233%E5%B2%81%E5%A5%B3%E7%AB%A5%E8%A2%AB%E6%AF%92%E8%9B%87%E5%92%AC%E4%BC%A4%E5%81%87%E6%AD%BB3%E5%A4%A9%E5%A5%87%E8%BF%B9%E7%94%9F%E8%BF%98%23) `684.9K 🔥`
1. [伊朗无人机大规模打击本古里安机场 (Iranian drones carry out massive strike on Ben-Gurion Airport)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%97%A0%E4%BA%BA%E6%9C%BA%E5%A4%A7%E8%A7%84%E6%A8%A1%E6%89%93%E5%87%BB%E6%9C%AC%E5%8F%A4%E9%87%8C%E5%AE%89%E6%9C%BA%E5%9C%BA%23) `310.0K 🔥`
1. [谢娜看到李小冉票数后哭了 (Xie Na cried after seeing Li Xiaoran’s votes)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E7%9C%8B%E5%88%B0%E6%9D%8E%E5%B0%8F%E5%86%89%E7%A5%A8%E6%95%B0%E5%90%8E%E5%93%AD%E4%BA%86%23) `258.5K 🔥`
1. [无人继承的巨额遗产或在拖垮日本 (The huge inheritance that no one inherits may be dragging down Japan)](https://s.weibo.com/weibo?q=%23%E6%97%A0%E4%BA%BA%E7%BB%A7%E6%89%BF%E7%9A%84%E5%B7%A8%E9%A2%9D%E9%81%97%E4%BA%A7%E6%88%96%E5%9C%A8%E6%8B%96%E5%9E%AE%E6%97%A5%E6%9C%AC%23) `127.3K 🔥`
1. [许昕说一直有人希望王楚钦输](https://s.weibo.com/weibo?q=%23%E8%AE%B8%E6%98%95%E8%AF%B4%E4%B8%80%E7%9B%B4%E6%9C%89%E4%BA%BA%E5%B8%8C%E6%9C%9B%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%BE%93%23) `97.0K 🔥`
1. [文淇第一次做妇科检查的不适感受 (Wen Qi’s discomfort during her first gynecological examination)](https://s.weibo.com/weibo?q=%23%E6%96%87%E6%B7%87%E7%AC%AC%E4%B8%80%E6%AC%A1%E5%81%9A%E5%A6%87%E7%A7%91%E6%A3%80%E6%9F%A5%E7%9A%84%E4%B8%8D%E9%80%82%E6%84%9F%E5%8F%97%23) `95.8K 🔥`
1. [海关截获18厘米长活体帝王蝎 (Customs intercepts 18cm long live emperor scorpion)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%85%B3%E6%88%AA%E8%8E%B718%E5%8E%98%E7%B1%B3%E9%95%BF%E6%B4%BB%E4%BD%93%E5%B8%9D%E7%8E%8B%E8%9D%8E%23) `95.1K 🔥`
1. [叶一茜 05超女的含金量](https://s.weibo.com/weibo?q=%23%E5%8F%B6%E4%B8%80%E8%8C%9C%2005%E8%B6%85%E5%A5%B3%E7%9A%84%E5%90%AB%E9%87%91%E9%87%8F%23) `93.5K 🔥`
1. [张凌赫脱稿演讲六分半的含金量 (The gold content of six and a half minutes of Zhang Linghe’s unscripted speech)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%84%B1%E7%A8%BF%E6%BC%94%E8%AE%B2%E5%85%AD%E5%88%86%E5%8D%8A%E7%9A%84%E5%90%AB%E9%87%91%E9%87%8F%23) `92.7K 🔥`
1. [酒店员工提醒小孩别玩门家长报警 (Hotel employee reminds children not to play with door, parents call police)](https://s.weibo.com/weibo?q=%23%E9%85%92%E5%BA%97%E5%91%98%E5%B7%A5%E6%8F%90%E9%86%92%E5%B0%8F%E5%AD%A9%E5%88%AB%E7%8E%A9%E9%97%A8%E5%AE%B6%E9%95%BF%E6%8A%A5%E8%AD%A6%23) `92.3K 🔥`
1. [十日终焉作者谈青岛出现血月 (The author of Ten Days End talks about the blood moon in Qingdao)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E4%BD%9C%E8%80%85%E8%B0%88%E9%9D%92%E5%B2%9B%E5%87%BA%E7%8E%B0%E8%A1%80%E6%9C%88%23) `91.5K 🔥`
1. [小伙家住46楼免费看周杰伦演唱会 (This guy lives on the 46th floor and can watch Jay Chou's concert for free)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%AE%B6%E4%BD%8F46%E6%A5%BC%E5%85%8D%E8%B4%B9%E7%9C%8B%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%BC%94%E5%94%B1%E4%BC%9A%23) `90.5K 🔥`
1. [曝伊朗国产防空武器无法被美锁定 (It is revealed that Iran’s domestically produced air defense weapons cannot be targeted by the United States)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E4%BC%8A%E6%9C%97%E5%9B%BD%E4%BA%A7%E9%98%B2%E7%A9%BA%E6%AD%A6%E5%99%A8%E6%97%A0%E6%B3%95%E8%A2%AB%E7%BE%8E%E9%94%81%E5%AE%9A%23) `57.1K 🔥`
1. [六大行房贷减少7100亿](https://s.weibo.com/weibo?q=%23%E5%85%AD%E5%A4%A7%E8%A1%8C%E6%88%BF%E8%B4%B7%E5%87%8F%E5%B0%917100%E4%BA%BF%23) `52.8K 🔥`
1. [陈凯琳老公是郑嘉颖](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%87%AF%E7%90%B3%E8%80%81%E5%85%AC%E6%98%AF%E9%83%91%E5%98%89%E9%A2%96%23) `52.4K 🔥`
1. [男子骑车途中电池爆燃妻子全身烧伤 (A man's battery exploded while he was riding, and his wife was burned all over her body)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%AA%91%E8%BD%A6%E9%80%94%E4%B8%AD%E7%94%B5%E6%B1%A0%E7%88%86%E7%87%83%E5%A6%BB%E5%AD%90%E5%85%A8%E8%BA%AB%E7%83%A7%E4%BC%A4%23) `50.2K 🔥`
1. [李小冉拉票 老实人豁出去了 (Li Xiaoran canvasses for votes, honest people risk everything)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%B0%8F%E5%86%89%E6%8B%89%E7%A5%A8%20%E8%80%81%E5%AE%9E%E4%BA%BA%E8%B1%81%E5%87%BA%E5%8E%BB%E4%BA%86%23) `45.2K 🔥`
1. [田曦薇嫁金钗杀青 (Tian Xiwei gets married to Jin Chai)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%AB%81%E9%87%91%E9%92%97%E6%9D%80%E9%9D%92%23) `41.3K 🔥`
1. [女子坠崖爱犬独守原地整整7天 (Woman fell off cliff and her dog stayed there alone for 7 days)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%9D%A0%E5%B4%96%E7%88%B1%E7%8A%AC%E7%8B%AC%E5%AE%88%E5%8E%9F%E5%9C%B0%E6%95%B4%E6%95%B47%E5%A4%A9%23) `39.7K 🔥`
1. [桥本帆乃香哭了 (Hashimoto Honoka cried)](https://s.weibo.com/weibo?q=%23%E6%A1%A5%E6%9C%AC%E5%B8%86%E4%B9%83%E9%A6%99%E5%93%AD%E4%BA%86%23) `39.6K 🔥`
1. [嫁金钗 (Marry a golden hairpin)](https://s.weibo.com/weibo?q=%23%E5%AB%81%E9%87%91%E9%92%97%23) `39.6K 🔥`
1. [瞿颖 作为西班牙人 (Qu Ying as a Spaniard)](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%20%E4%BD%9C%E4%B8%BA%E8%A5%BF%E7%8F%AD%E7%89%99%E4%BA%BA%23) `471.2K 🔥` `-42%`
1. [曝熊黛林做全职妈妈后被老公嫌弃](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%86%8A%E9%BB%9B%E6%9E%97%E5%81%9A%E5%85%A8%E8%81%8C%E5%A6%88%E5%A6%88%E5%90%8E%E8%A2%AB%E8%80%81%E5%85%AC%E5%AB%8C%E5%BC%83%23) `96.5K 🔥` `-48%`
1. [伊朗驻华大使馆发布战果 (The Iranian Embassy in China released the results of the battle)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A9%BB%E5%8D%8E%E5%A4%A7%E4%BD%BF%E9%A6%86%E5%8F%91%E5%B8%83%E6%88%98%E6%9E%9C%23) `61.2K 🔥` `-29%`
1. [美军一天2架战机被伊朗击落 (Two U.S. fighter jets were shot down by Iran in one day)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E4%B8%80%E5%A4%A92%E6%9E%B6%E6%88%98%E6%9C%BA%E8%A2%AB%E4%BC%8A%E6%9C%97%E5%87%BB%E8%90%BD%23) `45.7K 🔥` `-49%`

Updated at 2026-04-05 07:51:52

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
