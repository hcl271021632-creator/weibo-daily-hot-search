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

1. [一点点资助男孩被曝戴千元手表 (Little by little boy was exposed wearing a thousand-yuan watch)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E8%A2%AB%E6%9B%9D%E6%88%B4%E5%8D%83%E5%85%83%E6%89%8B%E8%A1%A8%23) `1.1M 🔥` `NEW`
1. [非遗鱼灯看古村里的中国年](https://s.weibo.com/weibo?q=%23%E9%9D%9E%E9%81%97%E9%B1%BC%E7%81%AF%E7%9C%8B%E5%8F%A4%E6%9D%91%E9%87%8C%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%B9%B4%23) `638.6K 🔥` `NEW`
1. [美好家打造指南](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%A5%BD%E5%AE%B6%E6%89%93%E9%80%A0%E6%8C%87%E5%8D%97%23) `466.8K 🔥` `NEW`
1. [逐玉请来了林俊杰唱OST](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%AF%B7%E6%9D%A5%E4%BA%86%E6%9E%97%E4%BF%8A%E6%9D%B0%E5%94%B1OST%23) `330.6K 🔥` `NEW`
1. [意外继承了前任同事留下的100块](https://s.weibo.com/weibo?q=%23%E6%84%8F%E5%A4%96%E7%BB%A7%E6%89%BF%E4%BA%86%E5%89%8D%E4%BB%BB%E5%90%8C%E4%BA%8B%E7%95%99%E4%B8%8B%E7%9A%84100%E5%9D%97%23) `323.7K 🔥` `NEW`
1. [千元lululemon外套仅穿一次就起球](https://s.weibo.com/weibo?q=%23%E5%8D%83%E5%85%83lululemon%E5%A4%96%E5%A5%97%E4%BB%85%E7%A9%BF%E4%B8%80%E6%AC%A1%E5%B0%B1%E8%B5%B7%E7%90%83%23) `275.7K 🔥` `NEW`
1. [手机 涨价](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%20%E6%B6%A8%E4%BB%B7%23) `212.3K 🔥` `NEW`
1. [杨幂米兰allblack看秀](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E7%B1%B3%E5%85%B0allblack%E7%9C%8B%E7%A7%80%23) `210.6K 🔥` `NEW`
1. [曝迪丽热巴与嘉行合约到期](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%B8%8E%E5%98%89%E8%A1%8C%E5%90%88%E7%BA%A6%E5%88%B0%E6%9C%9F%23) `151.0K 🔥` `NEW`
1. [郭富城三岁的时候岳父出生了](https://s.weibo.com/weibo?q=%23%E9%83%AD%E5%AF%8C%E5%9F%8E%E4%B8%89%E5%B2%81%E7%9A%84%E6%97%B6%E5%80%99%E5%B2%B3%E7%88%B6%E5%87%BA%E7%94%9F%E4%BA%86%23) `141.6K 🔥` `NEW`
1. [Prada大秀 (Prada show)](https://s.weibo.com/weibo?q=%23Prada%E5%A4%A7%E7%A7%80%23) `130.1K 🔥` `NEW`
1. [镖人 删减的打戏](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E5%88%A0%E5%87%8F%E7%9A%84%E6%89%93%E6%88%8F%23) `129.6K 🔥` `NEW`
1. [王劲松怒斥被AI盗用](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B2%E6%9D%BE%E6%80%92%E6%96%A5%E8%A2%ABAI%E7%9B%97%E7%94%A8%23) `129.0K 🔥` `NEW`
1. [原来补气血有个最佳顺序](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%A1%A5%E6%B0%94%E8%A1%80%E6%9C%89%E4%B8%AA%E6%9C%80%E4%BD%B3%E9%A1%BA%E5%BA%8F%23) `122.2K 🔥` `NEW`
1. [新一轮美伊谈判举行](https://s.weibo.com/weibo?q=%23%E6%96%B0%E4%B8%80%E8%BD%AE%E7%BE%8E%E4%BC%8A%E8%B0%88%E5%88%A4%E4%B8%BE%E8%A1%8C%23) `118.3K 🔥` `NEW`
1. [印度一18岁新娘在婚礼上遭枪击](https://s.weibo.com/weibo?q=%23%E5%8D%B0%E5%BA%A6%E4%B8%8018%E5%B2%81%E6%96%B0%E5%A8%98%E5%9C%A8%E5%A9%9A%E7%A4%BC%E4%B8%8A%E9%81%AD%E6%9E%AA%E5%87%BB%23) `118.3K 🔥` `NEW`
1. [给患癌去世女友筹钱男生讲述经过](https://s.weibo.com/weibo?q=%23%E7%BB%99%E6%82%A3%E7%99%8C%E5%8E%BB%E4%B8%96%E5%A5%B3%E5%8F%8B%E7%AD%B9%E9%92%B1%E7%94%B7%E7%94%9F%E8%AE%B2%E8%BF%B0%E7%BB%8F%E8%BF%87%23) `118.3K 🔥` `NEW`
1. [小米高管称手机成本已成鬼故事](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E9%AB%98%E7%AE%A1%E7%A7%B0%E6%89%8B%E6%9C%BA%E6%88%90%E6%9C%AC%E5%B7%B2%E6%88%90%E9%AC%BC%E6%95%85%E4%BA%8B%23) `118.3K 🔥` `NEW`
1. [任素汐演了9集身后已空无一人](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E7%B4%A0%E6%B1%90%E6%BC%94%E4%BA%869%E9%9B%86%E8%BA%AB%E5%90%8E%E5%B7%B2%E7%A9%BA%E6%97%A0%E4%B8%80%E4%BA%BA%23) `117.8K 🔥` `NEW`
1. [120未及时搬抬老人被判赔17万](https://s.weibo.com/weibo?q=%23120%E6%9C%AA%E5%8F%8A%E6%97%B6%E6%90%AC%E6%8A%AC%E8%80%81%E4%BA%BA%E8%A2%AB%E5%88%A4%E8%B5%9417%E4%B8%87%23) `108.5K 🔥` `NEW`
1. [理发师以打薄为由偷刮孕妇长发卖钱 (Barber shaves pregnant woman's long hair for money on the pretext of thinning it)](https://s.weibo.com/weibo?q=%23%E7%90%86%E5%8F%91%E5%B8%88%E4%BB%A5%E6%89%93%E8%96%84%E4%B8%BA%E7%94%B1%E5%81%B7%E5%88%AE%E5%AD%95%E5%A6%87%E9%95%BF%E5%8F%91%E5%8D%96%E9%92%B1%23) `107.2K 🔥` `NEW`
1. [林俊杰作曲方文山作词](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E4%BD%9C%E6%9B%B2%E6%96%B9%E6%96%87%E5%B1%B1%E4%BD%9C%E8%AF%8D%23) `106.9K 🔥` `NEW`
1. [给患癌女友筹钱男生称自己尽力了](https://s.weibo.com/weibo?q=%23%E7%BB%99%E6%82%A3%E7%99%8C%E5%A5%B3%E5%8F%8B%E7%AD%B9%E9%92%B1%E7%94%B7%E7%94%9F%E7%A7%B0%E8%87%AA%E5%B7%B1%E5%B0%BD%E5%8A%9B%E4%BA%86%23) `106.2K 🔥` `NEW`
1. [这桌子下一届学生不得疯抢](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%A1%8C%E5%AD%90%E4%B8%8B%E4%B8%80%E5%B1%8A%E5%AD%A6%E7%94%9F%E4%B8%8D%E5%BE%97%E7%96%AF%E6%8A%A2%23) `100.3K 🔥` `NEW`
1. [35岁男子胸痛扛了几天不幸离世](https://s.weibo.com/weibo?q=%2335%E5%B2%81%E7%94%B7%E5%AD%90%E8%83%B8%E7%97%9B%E6%89%9B%E4%BA%86%E5%87%A0%E5%A4%A9%E4%B8%8D%E5%B9%B8%E7%A6%BB%E4%B8%96%23) `99.8K 🔥` `NEW`
1. [去掉身上的弱者气息](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E6%8E%89%E8%BA%AB%E4%B8%8A%E7%9A%84%E5%BC%B1%E8%80%85%E6%B0%94%E6%81%AF%23) `97.5K 🔥` `NEW`
1. [造谣王橹杰私联或被罚款拘留](https://s.weibo.com/weibo?q=%23%E9%80%A0%E8%B0%A3%E7%8E%8B%E6%A9%B9%E6%9D%B0%E7%A7%81%E8%81%94%E6%88%96%E8%A2%AB%E7%BD%9A%E6%AC%BE%E6%8B%98%E7%95%99%23) `96.0K 🔥` `NEW`
1. [面条 熟了我自己会说OK](https://s.weibo.com/weibo?q=%23%E9%9D%A2%E6%9D%A1%20%E7%86%9F%E4%BA%86%E6%88%91%E8%87%AA%E5%B7%B1%E4%BC%9A%E8%AF%B4OK%23) `95.8K 🔥` `NEW`
1. [过了年再找工作更容易吗](https://s.weibo.com/weibo?q=%23%E8%BF%87%E4%BA%86%E5%B9%B4%E5%86%8D%E6%89%BE%E5%B7%A5%E4%BD%9C%E6%9B%B4%E5%AE%B9%E6%98%93%E5%90%97%23) `92.3K 🔥` `NEW`
1. [杨幂这是在米兰还是在湖南](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%BF%99%E6%98%AF%E5%9C%A8%E7%B1%B3%E5%85%B0%E8%BF%98%E6%98%AF%E5%9C%A8%E6%B9%96%E5%8D%97%23) `90.7K 🔥` `NEW`
1. [欠款1000万亿当事人这次真要逾期了 (The party who owes 1000 trillion yuan is really going to be overdue this time)](https://s.weibo.com/weibo?q=%23%E6%AC%A0%E6%AC%BE1000%E4%B8%87%E4%BA%BF%E5%BD%93%E4%BA%8B%E4%BA%BA%E8%BF%99%E6%AC%A1%E7%9C%9F%E8%A6%81%E9%80%BE%E6%9C%9F%E4%BA%86%23) `822.0K 🔥` `+256%`
1. [向佑不满遗产分配直喊不公平](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%91%E4%B8%8D%E6%BB%A1%E9%81%97%E4%BA%A7%E5%88%86%E9%85%8D%E7%9B%B4%E5%96%8A%E4%B8%8D%E5%85%AC%E5%B9%B3%23) `212.0K 🔥` `+45%`
1. [坐顺风车排泄后失联男子被封号](https://s.weibo.com/weibo?q=%23%E5%9D%90%E9%A1%BA%E9%A3%8E%E8%BD%A6%E6%8E%92%E6%B3%84%E5%90%8E%E5%A4%B1%E8%81%94%E7%94%B7%E5%AD%90%E8%A2%AB%E5%B0%81%E5%8F%B7%23) `211.7K 🔥` `+45%`
1. [男演员点赞和刘晓庆搭戏是工伤](https://s.weibo.com/weibo?q=%23%E7%94%B7%E6%BC%94%E5%91%98%E7%82%B9%E8%B5%9E%E5%92%8C%E5%88%98%E6%99%93%E5%BA%86%E6%90%AD%E6%88%8F%E6%98%AF%E5%B7%A5%E4%BC%A4%23) `210.2K 🔥` `+44%`
1. [杨洋对接回应复工](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%AF%B9%E6%8E%A5%E5%9B%9E%E5%BA%94%E5%A4%8D%E5%B7%A5%23) `209.3K 🔥` `+44%`
1. [小猫守家26天在主人床上拉满便便](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E5%AE%88%E5%AE%B626%E5%A4%A9%E5%9C%A8%E4%B8%BB%E4%BA%BA%E5%BA%8A%E4%B8%8A%E6%8B%89%E6%BB%A1%E4%BE%BF%E4%BE%BF%23) `208.8K 🔥` `+43%`
1. [周杰伦结婚田馥甄有了讽刺的情书](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E7%BB%93%E5%A9%9A%E7%94%B0%E9%A6%A5%E7%94%84%E6%9C%89%E4%BA%86%E8%AE%BD%E5%88%BA%E7%9A%84%E6%83%85%E4%B9%A6%23) `129.8K 🔥`
1. [一点点](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%23) `129.1K 🔥`
1. [安卓机皇三星S26上手体验](https://s.weibo.com/weibo?q=%23%E5%AE%89%E5%8D%93%E6%9C%BA%E7%9A%87%E4%B8%89%E6%98%9FS26%E4%B8%8A%E6%89%8B%E4%BD%93%E9%AA%8C%23) `125.0K 🔥`
1. [陈飞宇叫孙千洗衣粉儿 (Chen Feiyu calls Sun Qian washing powder)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E5%8F%AB%E5%AD%99%E5%8D%83%E6%B4%97%E8%A1%A3%E7%B2%89%E5%84%BF%23) `97.5K 🔥`
1. [微信能看图片使用次数了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%83%BD%E7%9C%8B%E5%9B%BE%E7%89%87%E4%BD%BF%E7%94%A8%E6%AC%A1%E6%95%B0%E4%BA%86%23) `347.4K 🔥` `-69%`
1. [唐国强也去演短剧了 (Tang Guoqiang also went to perform a short play)](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%9B%BD%E5%BC%BA%E4%B9%9F%E5%8E%BB%E6%BC%94%E7%9F%AD%E5%89%A7%E4%BA%86%23) `261.7K 🔥` `-40%`
1. [男子节后返家价值几万乌龟全被煮](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%8A%82%E5%90%8E%E8%BF%94%E5%AE%B6%E4%BB%B7%E5%80%BC%E5%87%A0%E4%B8%87%E4%B9%8C%E9%BE%9F%E5%85%A8%E8%A2%AB%E7%85%AE%23) `218.6K 🔥` `-72%`
1. [美国从陈志案获利150亿美元 (The United States gained US$15 billion from the Chen Zhi case)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%BB%8E%E9%99%88%E5%BF%97%E6%A1%88%E8%8E%B7%E5%88%A9150%E4%BA%BF%E7%BE%8E%E5%85%83%23) `209.6K 🔥` `-68%`
1. [王安宇推了半天凶手是自己 (Wang Anyu pushed for a long time that he was the murderer.)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E6%8E%A8%E4%BA%86%E5%8D%8A%E5%A4%A9%E5%87%B6%E6%89%8B%E6%98%AF%E8%87%AA%E5%B7%B1%23) `178.4K 🔥` `-44%`
1. [医生建议做美甲至少保留一个原甲](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%81%9A%E7%BE%8E%E7%94%B2%E8%87%B3%E5%B0%91%E4%BF%9D%E7%95%99%E4%B8%80%E4%B8%AA%E5%8E%9F%E7%94%B2%23) `161.8K 🔥` `-22%`
1. [男子中669万刷朋友圈查彩票才发现 (A man won 6.69 million and found out after checking the lottery through Moments)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E4%B8%AD669%E4%B8%87%E5%88%B7%E6%9C%8B%E5%8F%8B%E5%9C%88%E6%9F%A5%E5%BD%A9%E7%A5%A8%E6%89%8D%E5%8F%91%E7%8E%B0%23) `128.8K 🔥` `-63%`
1. [男子地铁猥亵女子称像年轻时的妻子](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%9C%B0%E9%93%81%E7%8C%A5%E4%BA%B5%E5%A5%B3%E5%AD%90%E7%A7%B0%E5%83%8F%E5%B9%B4%E8%BD%BB%E6%97%B6%E7%9A%84%E5%A6%BB%E5%AD%90%23) `108.8K 🔥` `-25%`
1. [周涛也开始拍短剧了 (Zhou Tao also started filming short plays)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B6%9B%E4%B9%9F%E5%BC%80%E5%A7%8B%E6%8B%8D%E7%9F%AD%E5%89%A7%E4%BA%86%23) `108.3K 🔥` `-26%`
1. [男子将博士学位证折成元宝烧给爷爷](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%B0%86%E5%8D%9A%E5%A3%AB%E5%AD%A6%E4%BD%8D%E8%AF%81%E6%8A%98%E6%88%90%E5%85%83%E5%AE%9D%E7%83%A7%E7%BB%99%E7%88%B7%E7%88%B7%23) `106.2K 🔥` `-24%`
1. [爱泼斯坦案曝光霍金与比基尼女子合影 (Epstein case exposes Hawking posing with bikini woman)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%B3%BC%E6%96%AF%E5%9D%A6%E6%A1%88%E6%9B%9D%E5%85%89%E9%9C%8D%E9%87%91%E4%B8%8E%E6%AF%94%E5%9F%BA%E5%B0%BC%E5%A5%B3%E5%AD%90%E5%90%88%E5%BD%B1%23) `101.7K 🔥` `-28%`

Updated at 2026-02-26 17:02:01

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
