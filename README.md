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

1. [我国自研新一代超大型油船交付 (my country's self-developed new generation of very large oil tanker delivered)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E8%87%AA%E7%A0%94%E6%96%B0%E4%B8%80%E4%BB%A3%E8%B6%85%E5%A4%A7%E5%9E%8B%E6%B2%B9%E8%88%B9%E4%BA%A4%E4%BB%98%23) `602.9K 🔥` `NEW`
1. [日方回应自卫队人员强闯我大使馆](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%96%B9%E5%9B%9E%E5%BA%94%E8%87%AA%E5%8D%AB%E9%98%9F%E4%BA%BA%E5%91%98%E5%BC%BA%E9%97%AF%E6%88%91%E5%A4%A7%E4%BD%BF%E9%A6%86%23) `255.6K 🔥` `NEW`
1. [江山大同](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E5%B1%B1%E5%A4%A7%E5%90%8C%23) `209.9K 🔥` `NEW`
1. [市监局回应专柜买4个LV包为假货](https://s.weibo.com/weibo?q=%23%E5%B8%82%E7%9B%91%E5%B1%80%E5%9B%9E%E5%BA%94%E4%B8%93%E6%9F%9C%E4%B9%B04%E4%B8%AALV%E5%8C%85%E4%B8%BA%E5%81%87%E8%B4%A7%23) `179.4K 🔥` `NEW`
1. [气得想把刘敏涛的痣抠下来](https://s.weibo.com/weibo?q=%23%E6%B0%94%E5%BE%97%E6%83%B3%E6%8A%8A%E5%88%98%E6%95%8F%E6%B6%9B%E7%9A%84%E7%97%A3%E6%8A%A0%E4%B8%8B%E6%9D%A5%23) `179.1K 🔥` `NEW`
1. [身体有这6种表现最好别运动](https://s.weibo.com/weibo?q=%23%E8%BA%AB%E4%BD%93%E6%9C%89%E8%BF%996%E7%A7%8D%E8%A1%A8%E7%8E%B0%E6%9C%80%E5%A5%BD%E5%88%AB%E8%BF%90%E5%8A%A8%23) `178.5K 🔥` `NEW`
1. [曝张雪峰立过遗嘱了](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%BC%A0%E9%9B%AA%E5%B3%B0%E7%AB%8B%E8%BF%87%E9%81%97%E5%98%B1%E4%BA%86%23) `177.3K 🔥` `NEW`
1. [何润东近7日涨粉25.6万](https://s.weibo.com/weibo?q=%23%E4%BD%95%E6%B6%A6%E4%B8%9C%E8%BF%917%E6%97%A5%E6%B6%A8%E7%B2%8925.6%E4%B8%87%23) `175.8K 🔥` `NEW`
1. [张雪峰微博里的捐款回执](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%BE%AE%E5%8D%9A%E9%87%8C%E7%9A%84%E6%8D%90%E6%AC%BE%E5%9B%9E%E6%89%A7%23) `173.2K 🔥` `NEW`
1. [知名经济学家巴曙松被办案机关带走](https://s.weibo.com/weibo?q=%23%E7%9F%A5%E5%90%8D%E7%BB%8F%E6%B5%8E%E5%AD%A6%E5%AE%B6%E5%B7%B4%E6%9B%99%E6%9D%BE%E8%A2%AB%E5%8A%9E%E6%A1%88%E6%9C%BA%E5%85%B3%E5%B8%A6%E8%B5%B0%23) `172.8K 🔥` `NEW`
1. [专家说黄金正重演08年剧本 (Experts say gold is repeating 2008 script)](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E8%AF%B4%E9%BB%84%E9%87%91%E6%AD%A3%E9%87%8D%E6%BC%9408%E5%B9%B4%E5%89%A7%E6%9C%AC%23) `172.3K 🔥` `NEW`
1. [何润东16年异地恋每年见面不到俩月](https://s.weibo.com/weibo?q=%23%E4%BD%95%E6%B6%A6%E4%B8%9C16%E5%B9%B4%E5%BC%82%E5%9C%B0%E6%81%8B%E6%AF%8F%E5%B9%B4%E8%A7%81%E9%9D%A2%E4%B8%8D%E5%88%B0%E4%BF%A9%E6%9C%88%23) `171.3K 🔥` `NEW`
1. [张雪峰曾说公司永远储备半年工资](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%9B%BE%E8%AF%B4%E5%85%AC%E5%8F%B8%E6%B0%B8%E8%BF%9C%E5%82%A8%E5%A4%87%E5%8D%8A%E5%B9%B4%E5%B7%A5%E8%B5%84%23) `164.1K 🔥` `NEW`
1. [国产激光武器真实打击画面](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E6%BF%80%E5%85%89%E6%AD%A6%E5%99%A8%E7%9C%9F%E5%AE%9E%E6%89%93%E5%87%BB%E7%94%BB%E9%9D%A2%23) `133.5K 🔥` `NEW`
1. [U23国足2比2泰国U23](https://s.weibo.com/weibo?q=%23U23%E5%9B%BD%E8%B6%B32%E6%AF%942%E6%B3%B0%E5%9B%BDU23%23) `127.6K 🔥` `NEW`
1. [金饰克价又暴涨](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E5%8F%88%E6%9A%B4%E6%B6%A8%23) `117.2K 🔥` `NEW`
1. [张凌赫剧组碎片](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%89%A7%E7%BB%84%E7%A2%8E%E7%89%87%23) `112.9K 🔥` `NEW`
1. [Uzi自曝与iG管理层沟通](https://s.weibo.com/weibo?q=%23Uzi%E8%87%AA%E6%9B%9D%E4%B8%8EiG%E7%AE%A1%E7%90%86%E5%B1%82%E6%B2%9F%E9%80%9A%23) `104.1K 🔥` `NEW`
1. [耳垂出现折痕建议及时检查心脏](https://s.weibo.com/weibo?q=%23%E8%80%B3%E5%9E%82%E5%87%BA%E7%8E%B0%E6%8A%98%E7%97%95%E5%BB%BA%E8%AE%AE%E5%8F%8A%E6%97%B6%E6%A3%80%E6%9F%A5%E5%BF%83%E8%84%8F%23) `101.5K 🔥` `NEW`
1. [张凌赫中学时期贴吧发言](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%B8%AD%E5%AD%A6%E6%97%B6%E6%9C%9F%E8%B4%B4%E5%90%A7%E5%8F%91%E8%A8%80%23) `99.4K 🔥` `NEW`
1. [白宇新剧被剧组边缘化 (Bai Yu's new drama is marginalized by the crew)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%87%E6%96%B0%E5%89%A7%E8%A2%AB%E5%89%A7%E7%BB%84%E8%BE%B9%E7%BC%98%E5%8C%96%23) `98.6K 🔥` `NEW`
1. [中方回应巴基斯坦愿成美伊调解方](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E5%B7%B4%E5%9F%BA%E6%96%AF%E5%9D%A6%E6%84%BF%E6%88%90%E7%BE%8E%E4%BC%8A%E8%B0%83%E8%A7%A3%E6%96%B9%23) `97.1K 🔥` `NEW`
1. [男子陪家人看病被医生发现猝死先兆](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%99%AA%E5%AE%B6%E4%BA%BA%E7%9C%8B%E7%97%85%E8%A2%AB%E5%8C%BB%E7%94%9F%E5%8F%91%E7%8E%B0%E7%8C%9D%E6%AD%BB%E5%85%88%E5%85%86%23) `94.5K 🔥` `NEW`
1. [张峻豪不敢给刘宇宁发消息](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%B3%BB%E8%B1%AA%E4%B8%8D%E6%95%A2%E7%BB%99%E5%88%98%E5%AE%87%E5%AE%81%E5%8F%91%E6%B6%88%E6%81%AF%23) `92.5K 🔥` `NEW`
1. [上海警方通报女子出差遭领导猥亵](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E5%A5%B3%E5%AD%90%E5%87%BA%E5%B7%AE%E9%81%AD%E9%A2%86%E5%AF%BC%E7%8C%A5%E4%BA%B5%23) `91.4K 🔥` `NEW`
1. [陈哲远一笑随歌播后半年逆袭](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%E4%B8%80%E7%AC%91%E9%9A%8F%E6%AD%8C%E6%92%AD%E5%90%8E%E5%8D%8A%E5%B9%B4%E9%80%86%E8%A2%AD%23) `86.9K 🔥` `NEW`
1. [第一次知道玻璃厂不能停电](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E7%9F%A5%E9%81%93%E7%8E%BB%E7%92%83%E5%8E%82%E4%B8%8D%E8%83%BD%E5%81%9C%E7%94%B5%23) `1.1M 🔥` `+383%`
1. [心源性猝死发生时的唯一急救手段](https://s.weibo.com/weibo?q=%23%E5%BF%83%E6%BA%90%E6%80%A7%E7%8C%9D%E6%AD%BB%E5%8F%91%E7%94%9F%E6%97%B6%E7%9A%84%E5%94%AF%E4%B8%80%E6%80%A5%E6%95%91%E6%89%8B%E6%AE%B5%23) `780.8K 🔥` `+701%`
1. [王俊凯专辑概念预告 (Wang Junkai album concept trailer)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E4%B8%93%E8%BE%91%E6%A6%82%E5%BF%B5%E9%A2%84%E5%91%8A%23) `175.2K 🔥` `+25%`
1. [董洁王橹杰演母子](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%B4%81%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%BC%94%E6%AF%8D%E5%AD%90%23) `174.1K 🔥` `+80%`
1. [小猫不洗头为什么脑袋不臭](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E4%B8%8D%E6%B4%97%E5%A4%B4%E4%B8%BA%E4%BB%80%E4%B9%88%E8%84%91%E8%A2%8B%E4%B8%8D%E8%87%AD%23) `177.8K 🔥`
1. [速效救心丸最好不要贴身携带 (It is best not to carry Suxiao Jiuxin Pills with you personally)](https://s.weibo.com/weibo?q=%23%E9%80%9F%E6%95%88%E6%95%91%E5%BF%83%E4%B8%B8%E6%9C%80%E5%A5%BD%E4%B8%8D%E8%A6%81%E8%B4%B4%E8%BA%AB%E6%90%BA%E5%B8%A6%23) `176.8K 🔥`
1. [于东来因对下属发脾气赔40多万](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E4%B8%9C%E6%9D%A5%E5%9B%A0%E5%AF%B9%E4%B8%8B%E5%B1%9E%E5%8F%91%E8%84%BE%E6%B0%94%E8%B5%9440%E5%A4%9A%E4%B8%87%23) `176.4K 🔥`
1. [32岁产妇羊水栓塞成植物人 (32-year-old mother suffers amniotic fluid embolism and becomes vegetative)](https://s.weibo.com/weibo?q=%2332%E5%B2%81%E4%BA%A7%E5%A6%87%E7%BE%8A%E6%B0%B4%E6%A0%93%E5%A1%9E%E6%88%90%E6%A4%8D%E7%89%A9%E4%BA%BA%23) `173.4K 🔥`
1. [晋江 花了好多钱](https://s.weibo.com/weibo?q=%23%E6%99%8B%E6%B1%9F%20%E8%8A%B1%E4%BA%86%E5%A5%BD%E5%A4%9A%E9%92%B1%23) `171.2K 🔥`
1. [于东来宣布每人退3000元 (Yu Donglai announced a refund of 3,000 yuan per person)](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E4%B8%9C%E6%9D%A5%E5%AE%A3%E5%B8%83%E6%AF%8F%E4%BA%BA%E9%80%803000%E5%85%83%23) `164.7K 🔥`
1. [50岁女子同房后出血查出晚期宫颈癌](https://s.weibo.com/weibo?q=%2350%E5%B2%81%E5%A5%B3%E5%AD%90%E5%90%8C%E6%88%BF%E5%90%8E%E5%87%BA%E8%A1%80%E6%9F%A5%E5%87%BA%E6%99%9A%E6%9C%9F%E5%AE%AB%E9%A2%88%E7%99%8C%23) `158.1K 🔥`
1. [原来迪丽热巴的20岁也难熬](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%9A%8420%E5%B2%81%E4%B9%9F%E9%9A%BE%E7%86%AC%23) `153.7K 🔥`
1. [耳帝评价周杰伦新专辑](https://s.weibo.com/weibo?q=%23%E8%80%B3%E5%B8%9D%E8%AF%84%E4%BB%B7%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%23) `143.5K 🔥`
1. [如何改善慢性炎症](https://s.weibo.com/weibo?q=%23%E5%A6%82%E4%BD%95%E6%94%B9%E5%96%84%E6%85%A2%E6%80%A7%E7%82%8E%E7%97%87%23) `118.8K 🔥`
1. [古偶粉底液将军101](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E5%81%B6%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B101%23) `117.0K 🔥`
1. [刘亦菲车内大片](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E8%BD%A6%E5%86%85%E5%A4%A7%E7%89%87%23) `103.0K 🔥`
1. [我和Angelababy居然是同一个物种](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%92%8CAngelababy%E5%B1%85%E7%84%B6%E6%98%AF%E5%90%8C%E4%B8%80%E4%B8%AA%E7%89%A9%E7%A7%8D%23) `86.8K 🔥`
1. [896线版智界R7发布即交付 (The 896-line version of Zhijie R7 will be delivered as soon as it is released)](https://s.weibo.com/weibo?q=%23896%E7%BA%BF%E7%89%88%E6%99%BA%E7%95%8CR7%E5%8F%91%E5%B8%83%E5%8D%B3%E4%BA%A4%E4%BB%98%23) `255.6K 🔥` `-61%`
1. [逐玉 删减](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%88%A0%E5%87%8F%23) `195.9K 🔥` `-24%`
1. [以纯品牌代言人范丞丞 (Yichun brand spokesperson Fan Chengcheng)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E7%BA%AF%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%E8%8C%83%E4%B8%9E%E4%B8%9E%23) `181.9K 🔥` `-59%`
1. [台湾赌王身中29枪死亡5枪爆头 (Taiwan gambling king was shot 29 times and died, with 5 shots in the head)](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E8%B5%8C%E7%8E%8B%E8%BA%AB%E4%B8%AD29%E6%9E%AA%E6%AD%BB%E4%BA%A15%E6%9E%AA%E7%88%86%E5%A4%B4%23) `174.9K 🔥` `-58%`
1. [薛之谦演唱会 视角](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E6%BC%94%E5%94%B1%E4%BC%9A%20%E8%A7%86%E8%A7%92%23) `102.3K 🔥` `-63%`
1. [奔跑吧14定档 (Running Bar 14 scheduled release)](https://s.weibo.com/weibo?q=%23%E5%A5%94%E8%B7%91%E5%90%A714%E5%AE%9A%E6%A1%A3%23) `90.8K 🔥` `-29%`
1. [40岁以上常熬夜体检加做一项 (People over 40 years old who often stay up late need to do an additional physical examination)](https://s.weibo.com/weibo?q=%2340%E5%B2%81%E4%BB%A5%E4%B8%8A%E5%B8%B8%E7%86%AC%E5%A4%9C%E4%BD%93%E6%A3%80%E5%8A%A0%E5%81%9A%E4%B8%80%E9%A1%B9%23) `87.8K 🔥` `-91%`
1. [出差猥亵女下属研究所所长被刑拘](https://s.weibo.com/weibo?q=%23%E5%87%BA%E5%B7%AE%E7%8C%A5%E4%BA%B5%E5%A5%B3%E4%B8%8B%E5%B1%9E%E7%A0%94%E7%A9%B6%E6%89%80%E6%89%80%E9%95%BF%E8%A2%AB%E5%88%91%E6%8B%98%23) `77.3K 🔥` `-69%`
1. [偶遇纪凌尘 看来综艺里不是演的 (I met Ji Lingchen by chance. It seems that he didn’t act in a variety show.)](https://s.weibo.com/weibo?q=%23%E5%81%B6%E9%81%87%E7%BA%AA%E5%87%8C%E5%B0%98%20%E7%9C%8B%E6%9D%A5%E7%BB%BC%E8%89%BA%E9%87%8C%E4%B8%8D%E6%98%AF%E6%BC%94%E7%9A%84%23) `76.8K 🔥` `-54%`

Updated at 2026-03-25 22:37:07

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
