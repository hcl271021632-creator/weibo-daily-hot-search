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

1. [2026两会日程预告 (2026 Two Sessions Schedule Preview)](https://s.weibo.com/weibo?q=%232026%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%E9%A2%84%E5%91%8A%23) `740.3K 🔥` `NEW`
1. [美国与委内瑞拉同意恢复外交关系](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%8E%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E5%90%8C%E6%84%8F%E6%81%A2%E5%A4%8D%E5%A4%96%E4%BA%A4%E5%85%B3%E7%B3%BB%23) `724.7K 🔥` `NEW`
1. [美国国土安全部部长被解职](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%9B%BD%E5%9C%9F%E5%AE%89%E5%85%A8%E9%83%A8%E9%83%A8%E9%95%BF%E8%A2%AB%E8%A7%A3%E8%81%8C%23) `633.7K 🔥` `NEW`
1. [俱乐部通报郭艾伦伤情](https://s.weibo.com/weibo?q=%23%E4%BF%B1%E4%B9%90%E9%83%A8%E9%80%9A%E6%8A%A5%E9%83%AD%E8%89%BE%E4%BC%A6%E4%BC%A4%E6%83%85%23) `592.3K 🔥` `NEW`
1. [霍启刚建议香港深化爱国主义教育](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%90%AF%E5%88%9A%E5%BB%BA%E8%AE%AE%E9%A6%99%E6%B8%AF%E6%B7%B1%E5%8C%96%E7%88%B1%E5%9B%BD%E4%B8%BB%E4%B9%89%E6%95%99%E8%82%B2%23) `587.3K 🔥` `NEW`
1. [建议取消私家车年审制度](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%8F%96%E6%B6%88%E7%A7%81%E5%AE%B6%E8%BD%A6%E5%B9%B4%E5%AE%A1%E5%88%B6%E5%BA%A6%23) `174.6K 🔥` `NEW`
1. [伊朗启动第21轮反击行动](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%AF%E5%8A%A8%E7%AC%AC21%E8%BD%AE%E5%8F%8D%E5%87%BB%E8%A1%8C%E5%8A%A8%23) `160.1K 🔥` `NEW`
1. [伊朗称持续打击中东多国美军目标](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%8C%81%E7%BB%AD%E6%89%93%E5%87%BB%E4%B8%AD%E4%B8%9C%E5%A4%9A%E5%9B%BD%E7%BE%8E%E5%86%9B%E7%9B%AE%E6%A0%87%23) `158.8K 🔥` `NEW`
1. [女子一年半攒2000克黄金挣50万](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B8%80%E5%B9%B4%E5%8D%8A%E6%94%922000%E5%85%8B%E9%BB%84%E9%87%91%E6%8C%A350%E4%B8%87%23) `135.9K 🔥` `NEW`
1. [如萍你真是在哪都不会说话](https://s.weibo.com/weibo?q=%23%E5%A6%82%E8%90%8D%E4%BD%A0%E7%9C%9F%E6%98%AF%E5%9C%A8%E5%93%AA%E9%83%BD%E4%B8%8D%E4%BC%9A%E8%AF%B4%E8%AF%9D%23) `94.7K 🔥` `NEW`
1. [曝现在就出发4金晨被替换了 (It is revealed that Jin Chen has been replaced in Let’s Go Now 4)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%E9%87%91%E6%99%A8%E8%A2%AB%E6%9B%BF%E6%8D%A2%E4%BA%86%23) `92.3K 🔥` `NEW`
1. [耐杀王塔图姆要回来了](https://s.weibo.com/weibo?q=%23%E8%80%90%E6%9D%80%E7%8E%8B%E5%A1%94%E5%9B%BE%E5%A7%86%E8%A6%81%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `61.8K 🔥` `NEW`
1. [香港没有调休](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E6%B2%A1%E6%9C%89%E8%B0%83%E4%BC%91%23) `1.1M 🔥` `+33%`
1. [建议短视频凌晨1点至5点深夜静默](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%9F%AD%E8%A7%86%E9%A2%91%E5%87%8C%E6%99%A81%E7%82%B9%E8%87%B35%E7%82%B9%E6%B7%B1%E5%A4%9C%E9%9D%99%E9%BB%98%23) `760.4K 🔥` `+30%`
1. [中国将在哪些方向发力](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%B0%86%E5%9C%A8%E5%93%AA%E4%BA%9B%E6%96%B9%E5%90%91%E5%8F%91%E5%8A%9B%23) `759.2K 🔥` `+65%`
1. [比亚迪闪充5分好9分饱3分寒 (BYD flash charge: 5 points good, 9 points full, 3 points cold)](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%E9%97%AA%E5%85%855%E5%88%86%E5%A5%BD9%E5%88%86%E9%A5%B13%E5%88%86%E5%AF%92%23) `752.9K 🔥` `+419%`
1. [春假清明连休6天家长称很无奈 (Parents said they were helpless after taking six consecutive days off during the Qingming Festival during the spring break.)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%81%87%E6%B8%85%E6%98%8E%E8%BF%9E%E4%BC%916%E5%A4%A9%E5%AE%B6%E9%95%BF%E7%A7%B0%E5%BE%88%E6%97%A0%E5%A5%88%23) `749.5K 🔥` `+79%`
1. [曝现在就出发4沈腾白敬亭带队](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%E6%B2%88%E8%85%BE%E7%99%BD%E6%95%AC%E4%BA%AD%E5%B8%A6%E9%98%9F%23) `725.7K 🔥` `+150%`
1. [伊朗称成功突破以色列七层防御 (Iran says it successfully penetrated seven layers of Israeli defenses)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%88%90%E5%8A%9F%E7%AA%81%E7%A0%B4%E4%BB%A5%E8%89%B2%E5%88%97%E4%B8%83%E5%B1%82%E9%98%B2%E5%BE%A1%23) `586.1K 🔥` `+190%`
1. [曝姜妍补位现在就出发4](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%A7%9C%E5%A6%8D%E8%A1%A5%E4%BD%8D%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%23) `312.0K 🔥` `+239%`
1. [伊朗发射带1吨重弹头导弹打以色列](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E5%B0%84%E5%B8%A61%E5%90%A8%E9%87%8D%E5%BC%B9%E5%A4%B4%E5%AF%BC%E5%BC%B9%E6%89%93%E4%BB%A5%E8%89%B2%E5%88%97%23) `300.2K 🔥` `+222%`
1. [武林外传小米演员已经坚持施粥5年](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E6%9E%97%E5%A4%96%E4%BC%A0%E5%B0%8F%E7%B1%B3%E6%BC%94%E5%91%98%E5%B7%B2%E7%BB%8F%E5%9D%9A%E6%8C%81%E6%96%BD%E7%B2%A55%E5%B9%B4%23) `281.3K 🔥` `+204%`
1. [两女子相隔7公里长得一模一样](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E5%A5%B3%E5%AD%90%E7%9B%B8%E9%9A%947%E5%85%AC%E9%87%8C%E9%95%BF%E5%BE%97%E4%B8%80%E6%A8%A1%E4%B8%80%E6%A0%B7%23) `221.2K 🔥` `+138%`
1. [坐飞机时发现邻座是只耶耶 (When I was on a plane, I noticed that the seat next to me was a guy.)](https://s.weibo.com/weibo?q=%23%E5%9D%90%E9%A3%9E%E6%9C%BA%E6%97%B6%E5%8F%91%E7%8E%B0%E9%82%BB%E5%BA%A7%E6%98%AF%E5%8F%AA%E8%80%B6%E8%80%B6%23) `190.6K 🔥` `+106%`
1. [八爪鱼钻车内失踪3天车主崩溃求助 (Octopus drill has been missing from the car for 3 days. The car owner collapsed and asked for help.)](https://s.weibo.com/weibo?q=%23%E5%85%AB%E7%88%AA%E9%B1%BC%E9%92%BB%E8%BD%A6%E5%86%85%E5%A4%B1%E8%B8%AA3%E5%A4%A9%E8%BD%A6%E4%B8%BB%E5%B4%A9%E6%BA%83%E6%B1%82%E5%8A%A9%23) `166.7K 🔥` `+79%`
1. [00后高速收费员回应撞脸多个明星 (The post-00s expressway toll collector’s response hit many celebrities in the face)](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E9%AB%98%E9%80%9F%E6%94%B6%E8%B4%B9%E5%91%98%E5%9B%9E%E5%BA%94%E6%92%9E%E8%84%B8%E5%A4%9A%E4%B8%AA%E6%98%8E%E6%98%9F%23) `165.6K 🔥` `+79%`
1. [建议最低法定年假从5天提高到10天 (It is recommended that the minimum statutory annual leave be increased from 5 days to 10 days)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%9C%80%E4%BD%8E%E6%B3%95%E5%AE%9A%E5%B9%B4%E5%81%87%E4%BB%8E5%E5%A4%A9%E6%8F%90%E9%AB%98%E5%88%B010%E5%A4%A9%23) `164.7K 🔥` `+62%`
1. [伊朗称其无人机袭击林肯号航母](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%85%B6%E6%97%A0%E4%BA%BA%E6%9C%BA%E8%A2%AD%E5%87%BB%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%23) `164.1K 🔥` `+83%`
1. [17岁男生发现新物种筷子蛇登上SCI (A 17-year-old boy discovered a new species of chopstick snake and boarded the SCI)](https://s.weibo.com/weibo?q=%2317%E5%B2%81%E7%94%B7%E7%94%9F%E5%8F%91%E7%8E%B0%E6%96%B0%E7%89%A9%E7%A7%8D%E7%AD%B7%E5%AD%90%E8%9B%87%E7%99%BB%E4%B8%8ASCI%23) `162.3K 🔥` `+77%`
1. [高速收费员因帅得人山人海火了](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E6%94%B6%E8%B4%B9%E5%91%98%E5%9B%A0%E5%B8%85%E5%BE%97%E4%BA%BA%E5%B1%B1%E4%BA%BA%E6%B5%B7%E7%81%AB%E4%BA%86%23) `161.9K 🔥` `+78%`
1. [33岁女子长相幼态常被认为是小学生](https://s.weibo.com/weibo?q=%2333%E5%B2%81%E5%A5%B3%E5%AD%90%E9%95%BF%E7%9B%B8%E5%B9%BC%E6%80%81%E5%B8%B8%E8%A2%AB%E8%AE%A4%E4%B8%BA%E6%98%AF%E5%B0%8F%E5%AD%A6%E7%94%9F%23) `158.9K 🔥` `+76%`
1. [王楚然 女人中的女人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%20%E5%A5%B3%E4%BA%BA%E4%B8%AD%E7%9A%84%E5%A5%B3%E4%BA%BA%23) `147.3K 🔥` `+65%`
1. [成毅太子长琴cut](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%E5%A4%AA%E5%AD%90%E9%95%BF%E7%90%B4cut%23) `112.3K 🔥` `+22%`
1. [叶璇都演婆婆了刘晓庆还在演少女 (Michelle Ye already plays the mother-in-law, and Liu Xiaoqing still plays the girl)](https://s.weibo.com/weibo?q=%23%E5%8F%B6%E7%92%87%E9%83%BD%E6%BC%94%E5%A9%86%E5%A9%86%E4%BA%86%E5%88%98%E6%99%93%E5%BA%86%E8%BF%98%E5%9C%A8%E6%BC%94%E5%B0%91%E5%A5%B3%23) `109.8K 🔥` `+24%`
1. [6天长假成都飞三亚机票量激增](https://s.weibo.com/weibo?q=%236%E5%A4%A9%E9%95%BF%E5%81%87%E6%88%90%E9%83%BD%E9%A3%9E%E4%B8%89%E4%BA%9A%E6%9C%BA%E7%A5%A8%E9%87%8F%E6%BF%80%E5%A2%9E%23) `97.9K 🔥` `+38%`
1. [陈哲远 再不救教资要融化了 (Chen Zheyuan If we don’t save the teaching resources, they will be melted down.)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%20%E5%86%8D%E4%B8%8D%E6%95%91%E6%95%99%E8%B5%84%E8%A6%81%E8%9E%8D%E5%8C%96%E4%BA%86%23) `76.0K 🔥` `+31%`
1. [艺考严选 宫里又来新人了](https://s.weibo.com/weibo?q=%23%E8%89%BA%E8%80%83%E4%B8%A5%E9%80%89%20%E5%AE%AB%E9%87%8C%E5%8F%88%E6%9D%A5%E6%96%B0%E4%BA%BA%E4%BA%86%23) `68.4K 🔥` `+41%`
1. [女子收到刮刮乐生日花束刮出80万元](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%94%B6%E5%88%B0%E5%88%AE%E5%88%AE%E4%B9%90%E7%94%9F%E6%97%A5%E8%8A%B1%E6%9D%9F%E5%88%AE%E5%87%BA80%E4%B8%87%E5%85%83%23) `64.9K 🔥` `+23%`
1. [建议不调休的代表被记者围住了](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%8D%E8%B0%83%E4%BC%91%E7%9A%84%E4%BB%A3%E8%A1%A8%E8%A2%AB%E8%AE%B0%E8%80%85%E5%9B%B4%E4%BD%8F%E4%BA%86%23) `82.0K 🔥`
1. [徐浩 团播 (Xu Hao group broadcast)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%B5%A9%20%E5%9B%A2%E6%92%AD%23) `74.3K 🔥`
1. [伊朗每天都向以色列发射导弹 (Iran fires missiles at Israel every day)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AF%8F%E5%A4%A9%E9%83%BD%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%E5%8F%91%E5%B0%84%E5%AF%BC%E5%BC%B9%23) `67.9K 🔥`
1. [真正长大了好像就是这样 (It seems like this when you really grow up)](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%AD%A3%E9%95%BF%E5%A4%A7%E4%BA%86%E5%A5%BD%E5%83%8F%E5%B0%B1%E6%98%AF%E8%BF%99%E6%A0%B7%23) `65.4K 🔥`
1. [伊朗反击进入新阶段 (Iran's counterattack enters new stage)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%8D%E5%87%BB%E8%BF%9B%E5%85%A5%E6%96%B0%E9%98%B6%E6%AE%B5%23) `65.4K 🔥`
1. [池昌旭 韩国酵母免疫者 (Ji Chang Wook Korean Yeast Immunologist)](https://s.weibo.com/weibo?q=%23%E6%B1%A0%E6%98%8C%E6%97%AD%20%E9%9F%A9%E5%9B%BD%E9%85%B5%E6%AF%8D%E5%85%8D%E7%96%AB%E8%80%85%23) `64.1K 🔥`
1. [攻玉](https://s.weibo.com/weibo?q=%23%E6%94%BB%E7%8E%89%23) `58.6K 🔥`
1. [比亚迪全球首创闪充桩来了](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%E5%85%A8%E7%90%83%E9%A6%96%E5%88%9B%E9%97%AA%E5%85%85%E6%A1%A9%E6%9D%A5%E4%BA%86%23) `58.6K 🔥`
1. [代表说农民每月200元养老金太亏了 (Representatives say farmers’ monthly pension of 200 yuan is too much of a loss)](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%86%9C%E6%B0%91%E6%AF%8F%E6%9C%88200%E5%85%83%E5%85%BB%E8%80%81%E9%87%91%E5%A4%AA%E4%BA%8F%E4%BA%86%23) `69.0K 🔥` `-25%`
1. [十日终焉角色设定](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E8%A7%92%E8%89%B2%E8%AE%BE%E5%AE%9A%23) `68.5K 🔥` `-39%`
1. [现在就出发4 (Let's go now 4)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%23) `58.6K 🔥` `-26%`
1. [伊朗报复美以 (Iran retaliates against US and Israel)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8A%A5%E5%A4%8D%E7%BE%8E%E4%BB%A5%23) `58.6K 🔥` `-34%`

Updated at 2026-03-06 08:05:09

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
