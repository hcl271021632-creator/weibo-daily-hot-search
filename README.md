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

1. [韩3名高空被烧死人员均为外包工 (The three people who were burned to death at high altitude in South Korea were all outsourced workers)](https://s.weibo.com/weibo?q=%23%E9%9F%A93%E5%90%8D%E9%AB%98%E7%A9%BA%E8%A2%AB%E7%83%A7%E6%AD%BB%E4%BA%BA%E5%91%98%E5%9D%87%E4%B8%BA%E5%A4%96%E5%8C%85%E5%B7%A5%23) `757.6K 🔥` `NEW`
1. [张凌赫知道热巴白宇退出开推的反应](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9F%A5%E9%81%93%E7%83%AD%E5%B7%B4%E7%99%BD%E5%AE%87%E9%80%80%E5%87%BA%E5%BC%80%E6%8E%A8%E7%9A%84%E5%8F%8D%E5%BA%94%23) `584.5K 🔥` `NEW`
1. [第一次看懂中文是因为看懂了英文](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E7%9C%8B%E6%87%82%E4%B8%AD%E6%96%87%E6%98%AF%E5%9B%A0%E4%B8%BA%E7%9C%8B%E6%87%82%E4%BA%86%E8%8B%B1%E6%96%87%23) `578.6K 🔥` `NEW`
1. [官方辟谣瑞安塘下4人集体跳河](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E8%BE%9F%E8%B0%A3%E7%91%9E%E5%AE%89%E5%A1%98%E4%B8%8B4%E4%BA%BA%E9%9B%86%E4%BD%93%E8%B7%B3%E6%B2%B3%23) `575.8K 🔥` `NEW`
1. [周杰伦太阳之子MV](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E5%A4%AA%E9%98%B3%E4%B9%8B%E5%AD%90MV%23) `572.6K 🔥` `NEW`
1. [地铁吐血女孩前男友去年因病离世](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E9%93%81%E5%90%90%E8%A1%80%E5%A5%B3%E5%AD%A9%E5%89%8D%E7%94%B7%E5%8F%8B%E5%8E%BB%E5%B9%B4%E5%9B%A0%E7%97%85%E7%A6%BB%E4%B8%96%23) `556.5K 🔥` `NEW`
1. [刘亦菲金智媛生图](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E9%87%91%E6%99%BA%E5%AA%9B%E7%94%9F%E5%9B%BE%23) `519.3K 🔥` `NEW`
1. [入室抢婴主犯听到死缓当庭开骂](https://s.weibo.com/weibo?q=%23%E5%85%A5%E5%AE%A4%E6%8A%A2%E5%A9%B4%E4%B8%BB%E7%8A%AF%E5%90%AC%E5%88%B0%E6%AD%BB%E7%BC%93%E5%BD%93%E5%BA%AD%E5%BC%80%E9%AA%82%23) `421.2K 🔥` `NEW`
1. [穆迪膝盖变形](https://s.weibo.com/weibo?q=%23%E7%A9%86%E8%BF%AA%E8%86%9D%E7%9B%96%E5%8F%98%E5%BD%A2%23) `214.2K 🔥` `NEW`
1. [14岁少年遭虐待离世伤痕遍布全身](https://s.weibo.com/weibo?q=%2314%E5%B2%81%E5%B0%91%E5%B9%B4%E9%81%AD%E8%99%90%E5%BE%85%E7%A6%BB%E4%B8%96%E4%BC%A4%E7%97%95%E9%81%8D%E5%B8%83%E5%85%A8%E8%BA%AB%23) `211.4K 🔥` `NEW`
1. [一吃自助就忍不住拿便宜货 (As soon as I eat at the buffet, I can’t help but grab the bargains)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%90%83%E8%87%AA%E5%8A%A9%E5%B0%B1%E5%BF%8D%E4%B8%8D%E4%BD%8F%E6%8B%BF%E4%BE%BF%E5%AE%9C%E8%B4%A7%23) `175.0K 🔥` `NEW`
1. [70元米妮蒸包系三个无馅白面馒头](https://s.weibo.com/weibo?q=%2370%E5%85%83%E7%B1%B3%E5%A6%AE%E8%92%B8%E5%8C%85%E7%B3%BB%E4%B8%89%E4%B8%AA%E6%97%A0%E9%A6%85%E7%99%BD%E9%9D%A2%E9%A6%92%E5%A4%B4%23) `172.7K 🔥` `NEW`
1. [金正恩正式将韩国定义为头号敌国](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E6%AD%A3%E5%BC%8F%E5%B0%86%E9%9F%A9%E5%9B%BD%E5%AE%9A%E4%B9%89%E4%B8%BA%E5%A4%B4%E5%8F%B7%E6%95%8C%E5%9B%BD%23) `172.6K 🔥` `NEW`
1. [贵州溶洞发现地下反向森林](https://s.weibo.com/weibo?q=%23%E8%B4%B5%E5%B7%9E%E6%BA%B6%E6%B4%9E%E5%8F%91%E7%8E%B0%E5%9C%B0%E4%B8%8B%E5%8F%8D%E5%90%91%E6%A3%AE%E6%9E%97%23) `155.6K 🔥` `NEW`
1. [100克金条吃顿饭工夫便宜3000元](https://s.weibo.com/weibo?q=%23100%E5%85%8B%E9%87%91%E6%9D%A1%E5%90%83%E9%A1%BF%E9%A5%AD%E5%B7%A5%E5%A4%AB%E4%BE%BF%E5%AE%9C3000%E5%85%83%23) `142.4K 🔥` `NEW`
1. [邓超碰上了最懂自己的节目组](https://s.weibo.com/weibo?q=%23%E9%82%93%E8%B6%85%E7%A2%B0%E4%B8%8A%E4%BA%86%E6%9C%80%E6%87%82%E8%87%AA%E5%B7%B1%E7%9A%84%E8%8A%82%E7%9B%AE%E7%BB%84%23) `133.0K 🔥` `NEW`
1. [被吸管杯背刺了](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E5%90%B8%E7%AE%A1%E6%9D%AF%E8%83%8C%E5%88%BA%E4%BA%86%23) `118.1K 🔥` `NEW`
1. [中园石化碰瓷中国石化](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%AD%E7%9F%B3%E5%8C%96%E7%A2%B0%E7%93%B7%E4%B8%AD%E5%9B%BD%E7%9F%B3%E5%8C%96%23) `114.1K 🔥` `NEW`
1. [丁程鑫比周柯宇大](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E6%AF%94%E5%91%A8%E6%9F%AF%E5%AE%87%E5%A4%A7%23) `114.0K 🔥` `NEW`
1. [烘焙店一次性手套包装被指像避孕套](https://s.weibo.com/weibo?q=%23%E7%83%98%E7%84%99%E5%BA%97%E4%B8%80%E6%AC%A1%E6%80%A7%E6%89%8B%E5%A5%97%E5%8C%85%E8%A3%85%E8%A2%AB%E6%8C%87%E5%83%8F%E9%81%BF%E5%AD%95%E5%A5%97%23) `114.0K 🔥` `NEW`
1. [惠英红 66岁正是晚上最热闹的时候 (Hui Yinghong 66 years old is the busiest time at night)](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%2066%E5%B2%81%E6%AD%A3%E6%98%AF%E6%99%9A%E4%B8%8A%E6%9C%80%E7%83%AD%E9%97%B9%E7%9A%84%E6%97%B6%E5%80%99%23) `113.3K 🔥` `NEW`
1. [少年被虐致死家族群里都是伤痕照片](https://s.weibo.com/weibo?q=%23%E5%B0%91%E5%B9%B4%E8%A2%AB%E8%99%90%E8%87%B4%E6%AD%BB%E5%AE%B6%E6%97%8F%E7%BE%A4%E9%87%8C%E9%83%BD%E6%98%AF%E4%BC%A4%E7%97%95%E7%85%A7%E7%89%87%23) `108.8K 🔥` `NEW`
1. [孕期接触杀菌剂影响持续20代](https://s.weibo.com/weibo?q=%23%E5%AD%95%E6%9C%9F%E6%8E%A5%E8%A7%A6%E6%9D%80%E8%8F%8C%E5%89%82%E5%BD%B1%E5%93%8D%E6%8C%81%E7%BB%AD20%E4%BB%A3%23) `95.9K 🔥` `NEW`
1. [咪想要 咪得到](https://s.weibo.com/weibo?q=%23%E5%92%AA%E6%83%B3%E8%A6%81%20%E5%92%AA%E5%BE%97%E5%88%B0%23) `89.1K 🔥` `NEW`
1. [买黄金赚的钱全吐出来了](https://s.weibo.com/weibo?q=%23%E4%B9%B0%E9%BB%84%E9%87%91%E8%B5%9A%E7%9A%84%E9%92%B1%E5%85%A8%E5%90%90%E5%87%BA%E6%9D%A5%E4%BA%86%23) `86.8K 🔥` `NEW`
1. [曝詹姆斯下赛季愿降薪留队](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%A9%B9%E5%A7%86%E6%96%AF%E4%B8%8B%E8%B5%9B%E5%AD%A3%E6%84%BF%E9%99%8D%E8%96%AA%E7%95%99%E9%98%9F%23) `85.3K 🔥` `NEW`
1. [其实你根本不喜欢玩手机](https://s.weibo.com/weibo?q=%23%E5%85%B6%E5%AE%9E%E4%BD%A0%E6%A0%B9%E6%9C%AC%E4%B8%8D%E5%96%9C%E6%AC%A2%E7%8E%A9%E6%89%8B%E6%9C%BA%23) `84.8K 🔥` `NEW`
1. [Fly登场KPL九周年](https://s.weibo.com/weibo?q=%23Fly%E7%99%BB%E5%9C%BAKPL%E4%B9%9D%E5%91%A8%E5%B9%B4%23) `80.0K 🔥` `NEW`
1. [等鲁豫姜思达](https://s.weibo.com/weibo?q=%23%E7%AD%89%E9%B2%81%E8%B1%AB%E5%A7%9C%E6%80%9D%E8%BE%BE%23) `78.9K 🔥` `NEW`
1. [老板回应一千多万预算请员工父母旅游](https://s.weibo.com/weibo?q=%23%E8%80%81%E6%9D%BF%E5%9B%9E%E5%BA%94%E4%B8%80%E5%8D%83%E5%A4%9A%E4%B8%87%E9%A2%84%E7%AE%97%E8%AF%B7%E5%91%98%E5%B7%A5%E7%88%B6%E6%AF%8D%E6%97%85%E6%B8%B8%23) `77.7K 🔥` `NEW`
1. [美国得州炼油厂发生爆炸 (Explosion occurs at Texas refinery)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%BE%97%E5%B7%9E%E7%82%BC%E6%B2%B9%E5%8E%82%E5%8F%91%E7%94%9F%E7%88%86%E7%82%B8%23) `1.0M 🔥` `+184%`
1. [享界896线激光雷达首测 (Xiangjie 896-line lidar first test)](https://s.weibo.com/weibo?q=%23%E4%BA%AB%E7%95%8C896%E7%BA%BF%E6%BF%80%E5%85%89%E9%9B%B7%E8%BE%BE%E9%A6%96%E6%B5%8B%23) `586.9K 🔥` `+608%`
1. [真正的麻辣香锅已经非常罕见了 (Real spicy hotpot is very rare)](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%AD%A3%E7%9A%84%E9%BA%BB%E8%BE%A3%E9%A6%99%E9%94%85%E5%B7%B2%E7%BB%8F%E9%9D%9E%E5%B8%B8%E7%BD%95%E8%A7%81%E4%BA%86%23) `583.4K 🔥` `+83%`
1. [伊朗公布袭击美军基地前后对比照](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%85%AC%E5%B8%83%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%E5%89%8D%E5%90%8E%E5%AF%B9%E6%AF%94%E7%85%A7%23) `563.7K 🔥` `+205%`
1. [海马体为出片要求穿长裙致孕妇摔倒 (Hippocampus required a pregnant woman to wear a long skirt for a film, causing her to fall)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E9%A9%AC%E4%BD%93%E4%B8%BA%E5%87%BA%E7%89%87%E8%A6%81%E6%B1%82%E7%A9%BF%E9%95%BF%E8%A3%99%E8%87%B4%E5%AD%95%E5%A6%87%E6%91%94%E5%80%92%23) `559.8K 🔥` `+142%`
1. [美团删照片](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%A2%E5%88%A0%E7%85%A7%E7%89%87%23) `440.6K 🔥` `+139%`
1. [iPhone史上最大规模产品革新来了](https://s.weibo.com/weibo?q=%23iPhone%E5%8F%B2%E4%B8%8A%E6%9C%80%E5%A4%A7%E8%A7%84%E6%A8%A1%E4%BA%A7%E5%93%81%E9%9D%A9%E6%96%B0%E6%9D%A5%E4%BA%86%23) `238.0K 🔥` `+30%`
1. [稳定发展是中国人民的坚实底气](https://s.weibo.com/weibo?q=%23%E7%A8%B3%E5%AE%9A%E5%8F%91%E5%B1%95%E6%98%AF%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B0%91%E7%9A%84%E5%9D%9A%E5%AE%9E%E5%BA%95%E6%B0%94%23) `588.4K 🔥`
1. [张凌赫为什么被称为粉底液将军](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A2%AB%E7%A7%B0%E4%B8%BA%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B%23) `171.7K 🔥`
1. [热巴给开推团准备了新疆特产](https://s.weibo.com/weibo?q=%23%E7%83%AD%E5%B7%B4%E7%BB%99%E5%BC%80%E6%8E%A8%E5%9B%A2%E5%87%86%E5%A4%87%E4%BA%86%E6%96%B0%E7%96%86%E7%89%B9%E4%BA%A7%23) `146.8K 🔥`
1. [王俊凯要唱新歌无人乐园](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E8%A6%81%E5%94%B1%E6%96%B0%E6%AD%8C%E6%97%A0%E4%BA%BA%E4%B9%90%E5%9B%AD%23) `146.8K 🔥`
1. [QQ音乐超级巅峰之夜曲目](https://s.weibo.com/weibo?q=%23QQ%E9%9F%B3%E4%B9%90%E8%B6%85%E7%BA%A7%E5%B7%85%E5%B3%B0%E4%B9%8B%E5%A4%9C%E6%9B%B2%E7%9B%AE%23) `109.1K 🔥`
1. [谢征樊长玉圆房吻来了](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E5%9C%86%E6%88%BF%E5%90%BB%E6%9D%A5%E4%BA%86%23) `90.0K 🔥`
1. [开始推理吧直播 (Start reasoning live)](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E6%8E%A8%E7%90%86%E5%90%A7%E7%9B%B4%E6%92%AD%23) `567.2K 🔥` `-31%`
1. [浅浅为俞宝儿改名齐煜](https://s.weibo.com/weibo?q=%23%E6%B5%85%E6%B5%85%E4%B8%BA%E4%BF%9E%E5%AE%9D%E5%84%BF%E6%94%B9%E5%90%8D%E9%BD%90%E7%85%9C%23) `181.8K 🔥` `-41%`
1. [单休一天出了一趟国](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BC%91%E4%B8%80%E5%A4%A9%E5%87%BA%E4%BA%86%E4%B8%80%E8%B6%9F%E5%9B%BD%23) `163.8K 🔥` `-45%`
1. [刘亦菲安妮海瑟薇互相搂腰](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E5%AE%89%E5%A6%AE%E6%B5%B7%E7%91%9F%E8%96%87%E4%BA%92%E7%9B%B8%E6%90%82%E8%85%B0%23) `105.2K 🔥` `-42%`
1. [张楚寒邓凯吻戏](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%A5%9A%E5%AF%92%E9%82%93%E5%87%AF%E5%90%BB%E6%88%8F%23) `97.2K 🔥` `-64%`
1. [赖清德宣布将重启核电厂](https://s.weibo.com/weibo?q=%23%E8%B5%96%E6%B8%85%E5%BE%B7%E5%AE%A3%E5%B8%83%E5%B0%86%E9%87%8D%E5%90%AF%E6%A0%B8%E7%94%B5%E5%8E%82%23) `89.3K 🔥` `-28%`
1. [金正恩称朝鲜将继续巩固拥核国家地位](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E7%A7%B0%E6%9C%9D%E9%B2%9C%E5%B0%86%E7%BB%A7%E7%BB%AD%E5%B7%A9%E5%9B%BA%E6%8B%A5%E6%A0%B8%E5%9B%BD%E5%AE%B6%E5%9C%B0%E4%BD%8D%23) `81.6K 🔥` `-32%`
1. [一个预防胃癌最简单的方法](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%B8%AA%E9%A2%84%E9%98%B2%E8%83%83%E7%99%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95%23) `79.3K 🔥` `-38%`
1. [中东已经够乱了](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%B8%9C%E5%B7%B2%E7%BB%8F%E5%A4%9F%E4%B9%B1%E4%BA%86%23) `78.5K 🔥` `-41%`

Updated at 2026-03-24 13:15:19

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
