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

1. [豆瓣称无法承受异常订单巨额损失 (Douban says it cannot bear huge losses from abnormal orders)](https://s.weibo.com/weibo?q=%23%E8%B1%86%E7%93%A3%E7%A7%B0%E6%97%A0%E6%B3%95%E6%89%BF%E5%8F%97%E5%BC%82%E5%B8%B8%E8%AE%A2%E5%8D%95%E5%B7%A8%E9%A2%9D%E6%8D%9F%E5%A4%B1%23) `979.3K 🔥` `NEW`
1. [海澜之家被暂停全军采购资格](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E6%BE%9C%E4%B9%8B%E5%AE%B6%E8%A2%AB%E6%9A%82%E5%81%9C%E5%85%A8%E5%86%9B%E9%87%87%E8%B4%AD%E8%B5%84%E6%A0%BC%23) `597.9K 🔥` `NEW`
1. [爱与不爱真的很明显](https://s.weibo.com/weibo?q=%23%E7%88%B1%E4%B8%8E%E4%B8%8D%E7%88%B1%E7%9C%9F%E7%9A%84%E5%BE%88%E6%98%8E%E6%98%BE%23) `272.5K 🔥` `NEW`
1. [俄罗斯](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%23) `184.5K 🔥` `NEW`
1. [湖南卫视元宵喜乐会节目单](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E5%8D%AB%E8%A7%86%E5%85%83%E5%AE%B5%E5%96%9C%E4%B9%90%E4%BC%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `184.4K 🔥` `NEW`
1. [LV羽绒服穿3小时掉色女子发声](https://s.weibo.com/weibo?q=%23LV%E7%BE%BD%E7%BB%92%E6%9C%8D%E7%A9%BF3%E5%B0%8F%E6%97%B6%E6%8E%89%E8%89%B2%E5%A5%B3%E5%AD%90%E5%8F%91%E5%A3%B0%23) `183.6K 🔥` `NEW`
1. [陈浩民夫妇滞留阿联酋](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%B5%A9%E6%B0%91%E5%A4%AB%E5%A6%87%E6%BB%9E%E7%95%99%E9%98%BF%E8%81%94%E9%85%8B%23) `182.6K 🔥` `NEW`
1. [周杰伦成都被称为史上最离谱演唱会](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%88%90%E9%83%BD%E8%A2%AB%E7%A7%B0%E4%B8%BA%E5%8F%B2%E4%B8%8A%E6%9C%80%E7%A6%BB%E8%B0%B1%E6%BC%94%E5%94%B1%E4%BC%9A%23) `180.5K 🔥` `NEW`
1. [小鹏智驾负责人称拉开差距的时刻到了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%B9%8F%E6%99%BA%E9%A9%BE%E8%B4%9F%E8%B4%A3%E4%BA%BA%E7%A7%B0%E6%8B%89%E5%BC%80%E5%B7%AE%E8%B7%9D%E7%9A%84%E6%97%B6%E5%88%BB%E5%88%B0%E4%BA%86%23) `180.0K 🔥` `NEW`
1. [王安宇顶奢官宣待遇](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E9%A1%B6%E5%A5%A2%E5%AE%98%E5%AE%A3%E5%BE%85%E9%81%87%23) `179.4K 🔥` `NEW`
1. [伊朗击落美军F15战机现场视频 (Live video of Iran shooting down US F15 fighter jet)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%87%BB%E8%90%BD%E7%BE%8E%E5%86%9BF15%E6%88%98%E6%9C%BA%E7%8E%B0%E5%9C%BA%E8%A7%86%E9%A2%91%23) `173.1K 🔥` `NEW`
1. [DuaLipa朴彩英合照](https://s.weibo.com/weibo?q=%23DuaLipa%E6%9C%B4%E5%BD%A9%E8%8B%B1%E5%90%88%E7%85%A7%23) `165.3K 🔥` `NEW`
1. [刘文祥店主喊话感谢紫薯精](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E5%BA%97%E4%B8%BB%E5%96%8A%E8%AF%9D%E6%84%9F%E8%B0%A2%E7%B4%AB%E8%96%AF%E7%B2%BE%23) `161.9K 🔥` `NEW`
1. [李茂称将跨边境去阿曼](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8C%82%E7%A7%B0%E5%B0%86%E8%B7%A8%E8%BE%B9%E5%A2%83%E5%8E%BB%E9%98%BF%E6%9B%BC%23) `159.3K 🔥` `NEW`
1. [建议大型犬出门叼个篮子](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%A4%A7%E5%9E%8B%E7%8A%AC%E5%87%BA%E9%97%A8%E5%8F%BC%E4%B8%AA%E7%AF%AE%E5%AD%90%23) `159.2K 🔥` `NEW`
1. [莫斯科遭炸弹袭击](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%96%AF%E7%A7%91%E9%81%AD%E7%82%B8%E5%BC%B9%E8%A2%AD%E5%87%BB%23) `1.5M 🔥` `+793%`
1. [刘文祥麻辣烫](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%23) `822.1K 🔥` `+22%`
1. [年轻人的第一台轿跑可以更新了 (Young people’s first coupe can be updated)](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E8%BD%BB%E4%BA%BA%E7%9A%84%E7%AC%AC%E4%B8%80%E5%8F%B0%E8%BD%BF%E8%B7%91%E5%8F%AF%E4%BB%A5%E6%9B%B4%E6%96%B0%E4%BA%86%23) `642.8K 🔥` `+202%`
1. [20后都避开网红名了吗](https://s.weibo.com/weibo?q=%2320%E5%90%8E%E9%83%BD%E9%81%BF%E5%BC%80%E7%BD%91%E7%BA%A2%E5%90%8D%E4%BA%86%E5%90%97%23) `578.6K 🔥` `+307%`
1. [陈昊宇剧宣 低头](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%98%8A%E5%AE%87%E5%89%A7%E5%AE%A3%20%E4%BD%8E%E5%A4%B4%23) `440.6K 🔥` `+176%`
1. [日本遭遇霍尔木兹休克](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E9%81%AD%E9%81%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E4%BC%91%E5%85%8B%23) `372.1K 🔥` `+158%`
1. [伊朗发动第10波攻势 (Iran launches 10th wave of offensive)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E5%8A%A8%E7%AC%AC10%E6%B3%A2%E6%94%BB%E5%8A%BF%23) `352.7K 🔥` `+56%`
1. [日本动漫巨头封口性侵受害者](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%8A%A8%E6%BC%AB%E5%B7%A8%E5%A4%B4%E5%B0%81%E5%8F%A3%E6%80%A7%E4%BE%B5%E5%8F%97%E5%AE%B3%E8%80%85%23) `226.9K 🔥` `+26%`
1. [十四届全国人大四次会议发布会](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E5%8F%91%E5%B8%83%E4%BC%9A%23) `1.1M 🔥`
1. [多架美军战机坠毁](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%9E%B6%E7%BE%8E%E5%86%9B%E6%88%98%E6%9C%BA%E5%9D%A0%E6%AF%81%23) `921.1K 🔥`
1. [命运真的会提醒你适合走哪条路](https://s.weibo.com/weibo?q=%23%E5%91%BD%E8%BF%90%E7%9C%9F%E7%9A%84%E4%BC%9A%E6%8F%90%E9%86%92%E4%BD%A0%E9%80%82%E5%90%88%E8%B5%B0%E5%93%AA%E6%9D%A1%E8%B7%AF%23) `230.2K 🔥`
1. [中方回应是否会对伊朗提供军事支持](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E6%98%AF%E5%90%A6%E4%BC%9A%E5%AF%B9%E4%BC%8A%E6%9C%97%E6%8F%90%E4%BE%9B%E5%86%9B%E4%BA%8B%E6%94%AF%E6%8C%81%23) `228.5K 🔥`
1. [伊朗前总统内贾德亲信称其平安](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%89%8D%E6%80%BB%E7%BB%9F%E5%86%85%E8%B4%BE%E5%BE%B7%E4%BA%B2%E4%BF%A1%E7%A7%B0%E5%85%B6%E5%B9%B3%E5%AE%89%23) `221.4K 🔥`
1. [李雨桐喊话薛之谦 (Li Yutong shouts to Joker Xue)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%9B%A8%E6%A1%90%E5%96%8A%E8%AF%9D%E8%96%9B%E4%B9%8B%E8%B0%A6%23) `183.9K 🔥`
1. [李茂报平安 (Li Mao reported safety)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8C%82%E6%8A%A5%E5%B9%B3%E5%AE%89%23) `182.3K 🔥`
1. [李雨桐说被薛之谦威胁](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%9B%A8%E6%A1%90%E8%AF%B4%E8%A2%AB%E8%96%9B%E4%B9%8B%E8%B0%A6%E5%A8%81%E8%83%81%23) `180.8K 🔥`
1. [坐在医院等结果突然被塞手里一个小孩 (Sitting in the hospital waiting for the result, a child was suddenly thrust into my hand.)](https://s.weibo.com/weibo?q=%23%E5%9D%90%E5%9C%A8%E5%8C%BB%E9%99%A2%E7%AD%89%E7%BB%93%E6%9E%9C%E7%AA%81%E7%84%B6%E8%A2%AB%E5%A1%9E%E6%89%8B%E9%87%8C%E4%B8%80%E4%B8%AA%E5%B0%8F%E5%AD%A9%23) `170.2K 🔥`
1. [对洗澡的开发还是太少了](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E6%B4%97%E6%BE%A1%E7%9A%84%E5%BC%80%E5%8F%91%E8%BF%98%E6%98%AF%E5%A4%AA%E5%B0%91%E4%BA%86%23) `159.1K 🔥`
1. [男子烧烤店就餐发现茶壶内发霉 (Man found mold inside teapot while dining at barbecue restaurant)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%83%A7%E7%83%A4%E5%BA%97%E5%B0%B1%E9%A4%90%E5%8F%91%E7%8E%B0%E8%8C%B6%E5%A3%B6%E5%86%85%E5%8F%91%E9%9C%89%23) `158.7K 🔥`
1. [伊朗一名中国公民遇难 (A Chinese citizen was killed in Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%90%8D%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E9%81%87%E9%9A%BE%23) `2.4M 🔥` `-66%`
1. [中方回应伊朗关闭霍尔木兹海峡](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E4%BC%8A%E6%9C%97%E5%85%B3%E9%97%AD%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `265.9K 🔥` `-23%`
1. [猫 你怎么不等我死了才回来 (Cat, why didn’t you wait until I was dead before you came back?)](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E4%BD%A0%E6%80%8E%E4%B9%88%E4%B8%8D%E7%AD%89%E6%88%91%E6%AD%BB%E4%BA%86%E6%89%8D%E5%9B%9E%E6%9D%A5%23) `193.8K 🔥` `-48%`
1. [短剧 变天 (Short drama: Change of weather)](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%20%E5%8F%98%E5%A4%A9%23) `183.5K 🔥` `-87%`
1. [蓝莓剥皮](https://s.weibo.com/weibo?q=%23%E8%93%9D%E8%8E%93%E5%89%A5%E7%9A%AE%23) `183.1K 🔥` `-50%`
1. [中国游客迪拜遇机场停运进退两难 (Chinese tourists face dilemma in Dubai due to airport shutdown)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E8%BF%AA%E6%8B%9C%E9%81%87%E6%9C%BA%E5%9C%BA%E5%81%9C%E8%BF%90%E8%BF%9B%E9%80%80%E4%B8%A4%E9%9A%BE%23) `182.2K 🔥` `-43%`
1. [刘文祥 紫薯精](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%20%E7%B4%AB%E8%96%AF%E7%B2%BE%23) `181.9K 🔥` `-48%`
1. [卢昱晓短发](https://s.weibo.com/weibo?q=%23%E5%8D%A2%E6%98%B1%E6%99%93%E7%9F%AD%E5%8F%91%23) `181.5K 🔥` `-46%`
1. [男子6元买彩票留店里竟然中了707万 (A man bought a lottery ticket for 6 yuan and left it at the store, but he won 7.07 million)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%906%E5%85%83%E4%B9%B0%E5%BD%A9%E7%A5%A8%E7%95%99%E5%BA%97%E9%87%8C%E7%AB%9F%E7%84%B6%E4%B8%AD%E4%BA%86707%E4%B8%87%23) `181.1K 🔥` `-50%`
1. [英国派出战机](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E6%B4%BE%E5%87%BA%E6%88%98%E6%9C%BA%23) `180.1K 🔥` `-21%`
1. [吴宣仪 剩下的交给时间和报应](https://s.weibo.com/weibo?q=%23%E5%90%B4%E5%AE%A3%E4%BB%AA%20%E5%89%A9%E4%B8%8B%E7%9A%84%E4%BA%A4%E7%BB%99%E6%97%B6%E9%97%B4%E5%92%8C%E6%8A%A5%E5%BA%94%23) `179.3K 🔥` `-44%`
1. [毛晓彤去了坦桑尼亚看狮子](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%99%93%E5%BD%A4%E5%8E%BB%E4%BA%86%E5%9D%A6%E6%A1%91%E5%B0%BC%E4%BA%9A%E7%9C%8B%E7%8B%AE%E5%AD%90%23) `169.4K 🔥` `-30%`
1. [赵樱子直播关掉美颜](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E6%A8%B1%E5%AD%90%E7%9B%B4%E6%92%AD%E5%85%B3%E6%8E%89%E7%BE%8E%E9%A2%9C%23) `159.3K 🔥` `-52%`
1. [丁禹兮宋祖儿 司宫令](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A6%B9%E5%85%AE%E5%AE%8B%E7%A5%96%E5%84%BF%20%E5%8F%B8%E5%AE%AB%E4%BB%A4%23) `159.2K 🔥` `-56%`
1. [女装牛仔裤也没有放过王楚然 (Women’s jeans didn’t let Wang Churan go either)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E8%A3%85%E7%89%9B%E4%BB%94%E8%A3%A4%E4%B9%9F%E6%B2%A1%E6%9C%89%E6%94%BE%E8%BF%87%E7%8E%8B%E6%A5%9A%E7%84%B6%23) `159.0K 🔥` `-49%`
1. [网红辛巴在美国被网友偶遇](https://s.weibo.com/weibo?q=%23%E7%BD%91%E7%BA%A2%E8%BE%9B%E5%B7%B4%E5%9C%A8%E7%BE%8E%E5%9B%BD%E8%A2%AB%E7%BD%91%E5%8F%8B%E5%81%B6%E9%81%87%23) `158.9K 🔥` `-29%`
1. [海口市监局回应椰树低俗广告 (Haikou Municipal Supervision Bureau responds to vulgar coconut tree advertisement)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8F%A3%E5%B8%82%E7%9B%91%E5%B1%80%E5%9B%9E%E5%BA%94%E6%A4%B0%E6%A0%91%E4%BD%8E%E4%BF%97%E5%B9%BF%E5%91%8A%23) `158.9K 🔥` `-23%`

Updated at 2026-03-02 18:02:41

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
