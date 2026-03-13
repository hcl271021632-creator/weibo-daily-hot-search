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

1. [广电总局将公布演员番位规则 (The State Administration of Radio, Film and Television will announce the cast rules for actors)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E7%94%B5%E6%80%BB%E5%B1%80%E5%B0%86%E5%85%AC%E5%B8%83%E6%BC%94%E5%91%98%E7%95%AA%E4%BD%8D%E8%A7%84%E5%88%99%23) `858.2K 🔥` `NEW`
1. [关于香蕉的三大谣言](https://s.weibo.com/weibo?q=%23%E5%85%B3%E4%BA%8E%E9%A6%99%E8%95%89%E7%9A%84%E4%B8%89%E5%A4%A7%E8%B0%A3%E8%A8%80%23) `373.2K 🔥` `NEW`
1. [这球也就是孙颖莎能打出来](https://s.weibo.com/weibo?q=%23%E8%BF%99%E7%90%83%E4%B9%9F%E5%B0%B1%E6%98%AF%E5%AD%99%E9%A2%96%E8%8E%8E%E8%83%BD%E6%89%93%E5%87%BA%E6%9D%A5%23) `372.9K 🔥` `NEW`
1. [去年315被点名的企业怎么样了](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E5%B9%B4315%E8%A2%AB%E7%82%B9%E5%90%8D%E7%9A%84%E4%BC%81%E4%B8%9A%E6%80%8E%E4%B9%88%E6%A0%B7%E4%BA%86%23) `372.2K 🔥` `NEW`
1. [张踩铃跨年看到张杰谢娜就换台了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%B8%A9%E9%93%83%E8%B7%A8%E5%B9%B4%E7%9C%8B%E5%88%B0%E5%BC%A0%E6%9D%B0%E8%B0%A2%E5%A8%9C%E5%B0%B1%E6%8D%A2%E5%8F%B0%E4%BA%86%23) `369.6K 🔥` `NEW`
1. [黄晓明要小海绵10年后接班](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E8%A6%81%E5%B0%8F%E6%B5%B7%E7%BB%B510%E5%B9%B4%E5%90%8E%E6%8E%A5%E7%8F%AD%23) `369.5K 🔥` `NEW`
1. [不想看AI演戏](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%83%B3%E7%9C%8BAI%E6%BC%94%E6%88%8F%23) `358.9K 🔥` `NEW`
1. [严屹宽 双男主](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%20%E5%8F%8C%E7%94%B7%E4%B8%BB%23) `352.3K 🔥` `NEW`
1. [头部演员片酬将发生结构性改变](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E9%83%A8%E6%BC%94%E5%91%98%E7%89%87%E9%85%AC%E5%B0%86%E5%8F%91%E7%94%9F%E7%BB%93%E6%9E%84%E6%80%A7%E6%94%B9%E5%8F%98%23) `343.8K 🔥` `NEW`
1. [魏大勋吐槽周冬雨穿得像自己奶奶](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E5%A4%A7%E5%8B%8B%E5%90%90%E6%A7%BD%E5%91%A8%E5%86%AC%E9%9B%A8%E7%A9%BF%E5%BE%97%E5%83%8F%E8%87%AA%E5%B7%B1%E5%A5%B6%E5%A5%B6%23) `324.2K 🔥` `NEW`
1. [襁褓女婴被领养到荷兰28年今日回国 (The infant girl was adopted to the Netherlands and returned to the country today after 28 years.)](https://s.weibo.com/weibo?q=%23%E8%A5%81%E8%A4%93%E5%A5%B3%E5%A9%B4%E8%A2%AB%E9%A2%86%E5%85%BB%E5%88%B0%E8%8D%B7%E5%85%B028%E5%B9%B4%E4%BB%8A%E6%97%A5%E5%9B%9E%E5%9B%BD%23) `310.1K 🔥` `NEW`
1. [金银直播间宣称真材实料却卖白菜价](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%93%B6%E7%9B%B4%E6%92%AD%E9%97%B4%E5%AE%A3%E7%A7%B0%E7%9C%9F%E6%9D%90%E5%AE%9E%E6%96%99%E5%8D%B4%E5%8D%96%E7%99%BD%E8%8F%9C%E4%BB%B7%23) `272.1K 🔥` `NEW`
1. [痞幼做医美了](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%81%9A%E5%8C%BB%E7%BE%8E%E4%BA%86%23) `240.4K 🔥` `NEW`
1. [这个春天再出发](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B8%AA%E6%98%A5%E5%A4%A9%E5%86%8D%E5%87%BA%E5%8F%91%23) `219.1K 🔥` `NEW`
1. [澳洲遇难男子遗体回家费用犯愁](https://s.weibo.com/weibo?q=%23%E6%BE%B3%E6%B4%B2%E9%81%87%E9%9A%BE%E7%94%B7%E5%AD%90%E9%81%97%E4%BD%93%E5%9B%9E%E5%AE%B6%E8%B4%B9%E7%94%A8%E7%8A%AF%E6%84%81%23) `179.6K 🔥` `NEW`
1. [赵钰琪七七进组但愿人长久](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E9%92%B0%E7%90%AA%E4%B8%83%E4%B8%83%E8%BF%9B%E7%BB%84%E4%BD%86%E6%84%BF%E4%BA%BA%E9%95%BF%E4%B9%85%23) `175.2K 🔥` `NEW`
1. [00后女生运营体温计网店月销超10万](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E5%A5%B3%E7%94%9F%E8%BF%90%E8%90%A5%E4%BD%93%E6%B8%A9%E8%AE%A1%E7%BD%91%E5%BA%97%E6%9C%88%E9%94%80%E8%B6%8510%E4%B8%87%23) `152.5K 🔥` `NEW`
1. [日本高官承认出轨但拒绝辞职](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E9%AB%98%E5%AE%98%E6%89%BF%E8%AE%A4%E5%87%BA%E8%BD%A8%E4%BD%86%E6%8B%92%E7%BB%9D%E8%BE%9E%E8%81%8C%23) `147.3K 🔥` `NEW`
1. [2026年春季全国中小学消防安全公开课](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E6%98%A5%E5%AD%A3%E5%85%A8%E5%9B%BD%E4%B8%AD%E5%B0%8F%E5%AD%A6%E6%B6%88%E9%98%B2%E5%AE%89%E5%85%A8%E5%85%AC%E5%BC%80%E8%AF%BE%23) `146.9K 🔥` `NEW`
1. [绩效 反人类](https://s.weibo.com/weibo?q=%23%E7%BB%A9%E6%95%88%20%E5%8F%8D%E4%BA%BA%E7%B1%BB%23) `120.5K 🔥` `NEW`
1. [F1冲刺排位赛 (F1 sprint qualifying)](https://s.weibo.com/weibo?q=%23F1%E5%86%B2%E5%88%BA%E6%8E%92%E4%BD%8D%E8%B5%9B%23) `108.0K 🔥` `NEW`
1. [沈月说不能留白鹿一个人](https://s.weibo.com/weibo?q=%23%E6%B2%88%E6%9C%88%E8%AF%B4%E4%B8%8D%E8%83%BD%E7%95%99%E7%99%BD%E9%B9%BF%E4%B8%80%E4%B8%AA%E4%BA%BA%23) `107.6K 🔥` `NEW`
1. [汪铎看出祝绪丹挂脸了](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E9%93%8E%E7%9C%8B%E5%87%BA%E7%A5%9D%E7%BB%AA%E4%B8%B9%E6%8C%82%E8%84%B8%E4%BA%86%23) `103.7K 🔥` `NEW`
1. [张拿铁差点被取名战狼2](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%8B%BF%E9%93%81%E5%B7%AE%E7%82%B9%E8%A2%AB%E5%8F%96%E5%90%8D%E6%88%98%E7%8B%BC2%23) `103.6K 🔥` `NEW`
1. [中产小孩降级去泰国插班](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BA%A7%E5%B0%8F%E5%AD%A9%E9%99%8D%E7%BA%A7%E5%8E%BB%E6%B3%B0%E5%9B%BD%E6%8F%92%E7%8F%AD%23) `102.8K 🔥` `NEW`
1. [男子向12315投诉遭接线员吐槽恶心](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%90%9112315%E6%8A%95%E8%AF%89%E9%81%AD%E6%8E%A5%E7%BA%BF%E5%91%98%E5%90%90%E6%A7%BD%E6%81%B6%E5%BF%83%23) `102.6K 🔥` `NEW`
1. [209元买梭子蟹百来块买绑绳](https://s.weibo.com/weibo?q=%23209%E5%85%83%E4%B9%B0%E6%A2%AD%E5%AD%90%E8%9F%B9%E7%99%BE%E6%9D%A5%E5%9D%97%E4%B9%B0%E7%BB%91%E7%BB%B3%23) `102.1K 🔥` `NEW`
1. [干净自己 埋汰别人](https://s.weibo.com/weibo?q=%23%E5%B9%B2%E5%87%80%E8%87%AA%E5%B7%B1%20%E5%9F%8B%E6%B1%B0%E5%88%AB%E4%BA%BA%23) `97.8K 🔥` `NEW`
1. [微信公关总监曾回应朋友圈编辑功能](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E5%85%AC%E5%85%B3%E6%80%BB%E7%9B%91%E6%9B%BE%E5%9B%9E%E5%BA%94%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%BC%96%E8%BE%91%E5%8A%9F%E8%83%BD%23) `86.7K 🔥` `NEW`
1. [马思纯一演戏面相都变了](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%80%9D%E7%BA%AF%E4%B8%80%E6%BC%94%E6%88%8F%E9%9D%A2%E7%9B%B8%E9%83%BD%E5%8F%98%E4%BA%86%23) `83.8K 🔥` `NEW`
1. [小猫相亲选了个秃头 (The kitten chose a bald guy on a blind date)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E7%9B%B8%E4%BA%B2%E9%80%89%E4%BA%86%E4%B8%AA%E7%A7%83%E5%A4%B4%23) `83.8K 🔥` `NEW`
1. [微信 朋友圈编辑 (WeChat Moments Editor)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%20%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%BC%96%E8%BE%91%23) `1.2M 🔥` `+36%`
1. [冻干草莓 农药](https://s.weibo.com/weibo?q=%23%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%20%E5%86%9C%E8%8D%AF%23) `399.7K 🔥` `+459%`
1. [中俄安理会硬刚美国](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BF%84%E5%AE%89%E7%90%86%E4%BC%9A%E7%A1%AC%E5%88%9A%E7%BE%8E%E5%9B%BD%23) `373.5K 🔥` `+79%`
1. [政协委员说国家统一才有安定未来](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%8D%8F%E5%A7%94%E5%91%98%E8%AF%B4%E5%9B%BD%E5%AE%B6%E7%BB%9F%E4%B8%80%E6%89%8D%E6%9C%89%E5%AE%89%E5%AE%9A%E6%9C%AA%E6%9D%A5%23) `371.8K 🔥` `+101%`
1. [世界从中国两会看到新机遇 (The world sees new opportunities from China’s Two Sessions)](https://s.weibo.com/weibo?q=%23%E4%B8%96%E7%95%8C%E4%BB%8E%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E7%9C%8B%E5%88%B0%E6%96%B0%E6%9C%BA%E9%81%87%23) `370.9K 🔥` `+103%`
1. [伊朗称对林肯号航母发动袭击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%AF%B9%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%E5%8F%91%E5%8A%A8%E8%A2%AD%E5%87%BB%23) `326.0K 🔥` `+132%`
1. [81岁爷爷误食了我的火鸡面](https://s.weibo.com/weibo?q=%2381%E5%B2%81%E7%88%B7%E7%88%B7%E8%AF%AF%E9%A3%9F%E4%BA%86%E6%88%91%E7%9A%84%E7%81%AB%E9%B8%A1%E9%9D%A2%23) `322.2K 🔥` `+301%`
1. [十五五新程上我们有底气有动力 (We have the confidence and motivation to embark on the new journey of the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E6%96%B0%E7%A8%8B%E4%B8%8A%E6%88%91%E4%BB%AC%E6%9C%89%E5%BA%95%E6%B0%94%E6%9C%89%E5%8A%A8%E5%8A%9B%23) `660.0K 🔥`
1. [谁敢相信这是九年前的张凌赫](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%95%A2%E7%9B%B8%E4%BF%A1%E8%BF%99%E6%98%AF%E4%B9%9D%E5%B9%B4%E5%89%8D%E7%9A%84%E5%BC%A0%E5%87%8C%E8%B5%AB%23) `207.0K 🔥`
1. [别让你的微信隐私在裸奔 (Don’t let your WeChat privacy slip away naked)](https://s.weibo.com/weibo?q=%23%E5%88%AB%E8%AE%A9%E4%BD%A0%E7%9A%84%E5%BE%AE%E4%BF%A1%E9%9A%90%E7%A7%81%E5%9C%A8%E8%A3%B8%E5%A5%94%23) `186.2K 🔥`
1. [王鹤润 王玉雯](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%B6%A6%20%E7%8E%8B%E7%8E%89%E9%9B%AF%23) `136.1K 🔥`
1. [谭松韵长文回应王劲松](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E9%95%BF%E6%96%87%E5%9B%9E%E5%BA%94%E7%8E%8B%E5%8A%B2%E6%9D%BE%23) `125.7K 🔥`
1. [国产手机涨价2000元 (Domestic mobile phone prices increase by 2,000 yuan)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E6%89%8B%E6%9C%BA%E6%B6%A8%E4%BB%B72000%E5%85%83%23) `492.5K 🔥` `-57%`
1. [多款100%椰子水被曝兑水加糖](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%AC%BE100%25%E6%A4%B0%E5%AD%90%E6%B0%B4%E8%A2%AB%E6%9B%9D%E5%85%91%E6%B0%B4%E5%8A%A0%E7%B3%96%23) `117.4K 🔥` `-44%`
1. [豆包 消极怠工 (Beanbao, passive and slow at work)](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%20%E6%B6%88%E6%9E%81%E6%80%A0%E5%B7%A5%23) `101.8K 🔥` `-44%`
1. [中腰部演员将被AI替代](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E8%85%B0%E9%83%A8%E6%BC%94%E5%91%98%E5%B0%86%E8%A2%ABAI%E6%9B%BF%E4%BB%A3%23) `99.2K 🔥` `-45%`
1. [为什么现在冰箱门越来越多了](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E7%8E%B0%E5%9C%A8%E5%86%B0%E7%AE%B1%E9%97%A8%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%A4%9A%E4%BA%86%23) `92.8K 🔥` `-54%`
1. [老人拒透露500枚金币下落被关十年 (An old man was imprisoned for ten years for refusing to disclose the whereabouts of 500 gold coins)](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%BA%BA%E6%8B%92%E9%80%8F%E9%9C%B2500%E6%9E%9A%E9%87%91%E5%B8%81%E4%B8%8B%E8%90%BD%E8%A2%AB%E5%85%B3%E5%8D%81%E5%B9%B4%23) `88.6K 🔥` `-39%`
1. [gse 抢日乙鸡蛋](https://s.weibo.com/weibo?q=%23gse%20%E6%8A%A2%E6%97%A5%E4%B9%99%E9%B8%A1%E8%9B%8B%23) `88.0K 🔥` `-37%`
1. [孙颖莎vs迪亚兹](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E8%BF%AA%E4%BA%9A%E5%85%B9%23) `85.4K 🔥` `-54%`

Updated at 2026-03-13 15:29:47

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
