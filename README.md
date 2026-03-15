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

1. [刘文祥店员说20元1斤能是纯牛肉吗 (Liu Wenxiang, the clerk said, can 20 yuan per pound be pure beef?)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E5%BA%97%E5%91%98%E8%AF%B420%E5%85%831%E6%96%A4%E8%83%BD%E6%98%AF%E7%BA%AF%E7%89%9B%E8%82%89%E5%90%97%23) `812.0K 🔥` `NEW`
1. [F1取消四月全部赛事](https://s.weibo.com/weibo?q=%23F1%E5%8F%96%E6%B6%88%E5%9B%9B%E6%9C%88%E5%85%A8%E9%83%A8%E8%B5%9B%E4%BA%8B%23) `317.3K 🔥` `NEW`
1. [把家租给短剧剧组吧](https://s.weibo.com/weibo?q=%23%E6%8A%8A%E5%AE%B6%E7%A7%9F%E7%BB%99%E7%9F%AD%E5%89%A7%E5%89%A7%E7%BB%84%E5%90%A7%23) `286.5K 🔥` `NEW`
1. [章子怡 医美](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%20%E5%8C%BB%E7%BE%8E%23) `284.9K 🔥` `NEW`
1. [孔雪儿好有版权意识](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E5%A5%BD%E6%9C%89%E7%89%88%E6%9D%83%E6%84%8F%E8%AF%86%23) `272.6K 🔥` `NEW`
1. [伊朗用涂鸦骗导弹轰炸](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%94%A8%E6%B6%82%E9%B8%A6%E9%AA%97%E5%AF%BC%E5%BC%B9%E8%BD%B0%E7%82%B8%23) `269.2K 🔥` `NEW`
1. [王橹杰自拍九宫格](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E8%87%AA%E6%8B%8D%E4%B9%9D%E5%AE%AB%E6%A0%BC%23) `265.8K 🔥` `NEW`
1. [温瑞博vs张本智和](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9Avs%E5%BC%A0%E6%9C%AC%E6%99%BA%E5%92%8C%23) `236.9K 🔥` `NEW`
1. [AMG带你追F1](https://s.weibo.com/weibo?q=%23AMG%E5%B8%A6%E4%BD%A0%E8%BF%BDF1%23) `236.7K 🔥` `NEW`
1. [谁在给F1加满能量](https://s.weibo.com/weibo?q=%23%E8%B0%81%E5%9C%A8%E7%BB%99F1%E5%8A%A0%E6%BB%A1%E8%83%BD%E9%87%8F%23) `236.6K 🔥` `NEW`
1. [国产剧月经戏终于不尴尬了 (Menstruation scenes in domestic dramas are finally no longer embarrassing)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E5%89%A7%E6%9C%88%E7%BB%8F%E6%88%8F%E7%BB%88%E4%BA%8E%E4%B8%8D%E5%B0%B4%E5%B0%AC%E4%BA%86%23) `236.6K 🔥` `NEW`
1. [保证前额叶健康太重要了](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E8%AF%81%E5%89%8D%E9%A2%9D%E5%8F%B6%E5%81%A5%E5%BA%B7%E5%A4%AA%E9%87%8D%E8%A6%81%E4%BA%86%23) `201.1K 🔥` `NEW`
1. [金道勋 ana](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%81%93%E5%8B%8B%20ana%23) `201.0K 🔥` `NEW`
1. [李煜东发文](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%85%9C%E4%B8%9C%E5%8F%91%E6%96%87%23) `159.8K 🔥` `NEW`
1. [老虎纠正游客发音竟然害羞了](https://s.weibo.com/weibo?q=%23%E8%80%81%E8%99%8E%E7%BA%A0%E6%AD%A3%E6%B8%B8%E5%AE%A2%E5%8F%91%E9%9F%B3%E7%AB%9F%E7%84%B6%E5%AE%B3%E7%BE%9E%E4%BA%86%23) `154.3K 🔥` `NEW`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `153.7K 🔥` `NEW`
1. [库里回复庞博](https://s.weibo.com/weibo?q=%23%E5%BA%93%E9%87%8C%E5%9B%9E%E5%A4%8D%E5%BA%9E%E5%8D%9A%23) `127.5K 🔥` `NEW`
1. [亿级APP存在大量儿童软色情内容](https://s.weibo.com/weibo?q=%23%E4%BA%BF%E7%BA%A7APP%E5%AD%98%E5%9C%A8%E5%A4%A7%E9%87%8F%E5%84%BF%E7%AB%A5%E8%BD%AF%E8%89%B2%E6%83%85%E5%86%85%E5%AE%B9%23) `126.8K 🔥` `NEW`
1. [汪苏泷直播](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E7%9B%B4%E6%92%AD%23) `126.3K 🔥` `NEW`
1. [5岁金毛长期寄养宠夕夕发病身亡](https://s.weibo.com/weibo?q=%235%E5%B2%81%E9%87%91%E6%AF%9B%E9%95%BF%E6%9C%9F%E5%AF%84%E5%85%BB%E5%AE%A0%E5%A4%95%E5%A4%95%E5%8F%91%E7%97%85%E8%BA%AB%E4%BA%A1%23) `119.2K 🔥` `NEW`
1. [交友APP色情聊天收割中老年男性 (Dating APP sex chat harvests middle-aged and elderly men)](https://s.weibo.com/weibo?q=%23%E4%BA%A4%E5%8F%8BAPP%E8%89%B2%E6%83%85%E8%81%8A%E5%A4%A9%E6%94%B6%E5%89%B2%E4%B8%AD%E8%80%81%E5%B9%B4%E7%94%B7%E6%80%A7%23) `114.1K 🔥` `NEW`
1. [博主用饲料标准测评胖东来鸡蛋](https://s.weibo.com/weibo?q=%23%E5%8D%9A%E4%B8%BB%E7%94%A8%E9%A5%B2%E6%96%99%E6%A0%87%E5%87%86%E6%B5%8B%E8%AF%84%E8%83%96%E4%B8%9C%E6%9D%A5%E9%B8%A1%E8%9B%8B%23) `102.3K 🔥` `NEW`
1. [李昀锐F1赛车服造型](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90F1%E8%B5%9B%E8%BD%A6%E6%9C%8D%E9%80%A0%E5%9E%8B%23) `102.3K 🔥` `NEW`
1. [鹿哈带货牛肚直接扔地上冷却](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E5%B8%A6%E8%B4%A7%E7%89%9B%E8%82%9A%E7%9B%B4%E6%8E%A5%E6%89%94%E5%9C%B0%E4%B8%8A%E5%86%B7%E5%8D%B4%23) `99.4K 🔥` `NEW`
1. [F勒布伦4比3松岛辉空](https://s.weibo.com/weibo?q=%23F%E5%8B%92%E5%B8%83%E4%BC%A64%E6%AF%943%E6%9D%BE%E5%B2%9B%E8%BE%89%E7%A9%BA%23) `94.8K 🔥` `NEW`
1. [懒人真的很适合去过极简生活](https://s.weibo.com/weibo?q=%23%E6%87%92%E4%BA%BA%E7%9C%9F%E7%9A%84%E5%BE%88%E9%80%82%E5%90%88%E5%8E%BB%E8%BF%87%E6%9E%81%E7%AE%80%E7%94%9F%E6%B4%BB%23) `91.4K 🔥` `NEW`
1. [王鹤棣把白鹿宋茜沈月都回答了一遍](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%8A%8A%E7%99%BD%E9%B9%BF%E5%AE%8B%E8%8C%9C%E6%B2%88%E6%9C%88%E9%83%BD%E5%9B%9E%E7%AD%94%E4%BA%86%E4%B8%80%E9%81%8D%23) `82.7K 🔥` `NEW`
1. [当代年轻人最拿手的两道菜](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BB%A3%E5%B9%B4%E8%BD%BB%E4%BA%BA%E6%9C%80%E6%8B%BF%E6%89%8B%E7%9A%84%E4%B8%A4%E9%81%93%E8%8F%9C%23) `79.5K 🔥` `NEW`
1. [柴犬把边牧当成了自己的狗窝](https://s.weibo.com/weibo?q=%23%E6%9F%B4%E7%8A%AC%E6%8A%8A%E8%BE%B9%E7%89%A7%E5%BD%93%E6%88%90%E4%BA%86%E8%87%AA%E5%B7%B1%E7%9A%84%E7%8B%97%E7%AA%9D%23) `79.4K 🔥` `NEW`
1. [淘宝闪购把F1速度带出赛道 (Taobao flash sales take F1 speed off the track)](https://s.weibo.com/weibo?q=%23%E6%B7%98%E5%AE%9D%E9%97%AA%E8%B4%AD%E6%8A%8AF1%E9%80%9F%E5%BA%A6%E5%B8%A6%E5%87%BA%E8%B5%9B%E9%81%93%23) `455.9K 🔥` `+40%`
1. [央视调查某茶饮品牌遭恶意抹黑始末](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E8%B0%83%E6%9F%A5%E6%9F%90%E8%8C%B6%E9%A5%AE%E5%93%81%E7%89%8C%E9%81%AD%E6%81%B6%E6%84%8F%E6%8A%B9%E9%BB%91%E5%A7%8B%E6%9C%AB%23) `451.5K 🔥` `+342%`
1. [泡椒凤爪的泡椒竟是印上去的 (The pickled peppers in the pickled pepper chicken feet are actually printed on them.)](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E6%A4%92%E5%87%A4%E7%88%AA%E7%9A%84%E6%B3%A1%E6%A4%92%E7%AB%9F%E6%98%AF%E5%8D%B0%E4%B8%8A%E5%8E%BB%E7%9A%84%23) `337.7K 🔥` `+105%`
1. [专家建议工作日缩至4天](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E5%BB%BA%E8%AE%AE%E5%B7%A5%E4%BD%9C%E6%97%A5%E7%BC%A9%E8%87%B34%E5%A4%A9%23) `293.2K 🔥` `+73%`
1. [成毅 年龄](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%20%E5%B9%B4%E9%BE%84%23) `286.0K 🔥` `+74%`
1. [她俩从连体婴到形同陌路](https://s.weibo.com/weibo?q=%23%E5%A5%B9%E4%BF%A9%E4%BB%8E%E8%BF%9E%E4%BD%93%E5%A9%B4%E5%88%B0%E5%BD%A2%E5%90%8C%E9%99%8C%E8%B7%AF%23) `270.1K 🔥` `+66%`
1. [梁婷 成毅报户口的时候报大一岁](https://s.weibo.com/weibo?q=%23%E6%A2%81%E5%A9%B7%20%E6%88%90%E6%AF%85%E6%8A%A5%E6%88%B7%E5%8F%A3%E7%9A%84%E6%97%B6%E5%80%99%E6%8A%A5%E5%A4%A7%E4%B8%80%E5%B2%81%23) `267.4K 🔥` `+72%`
1. [泰国遇害中国女子丈夫发声](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E9%81%87%E5%AE%B3%E4%B8%AD%E5%9B%BD%E5%A5%B3%E5%AD%90%E4%B8%88%E5%A4%AB%E5%8F%91%E5%A3%B0%23) `245.5K 🔥` `+50%`
1. [方圆自曝不火了就去国外读书](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%9C%86%E8%87%AA%E6%9B%9D%E4%B8%8D%E7%81%AB%E4%BA%86%E5%B0%B1%E5%8E%BB%E5%9B%BD%E5%A4%96%E8%AF%BB%E4%B9%A6%23) `237.2K 🔥` `+70%`
1. [网友卢浮宫偶遇素颜刘亦菲](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E5%8D%A2%E6%B5%AE%E5%AE%AB%E5%81%B6%E9%81%87%E7%B4%A0%E9%A2%9C%E5%88%98%E4%BA%A6%E8%8F%B2%23) `237.2K 🔥` `+45%`
1. [花少 花儿与中老年](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%B0%91%20%E8%8A%B1%E5%84%BF%E4%B8%8E%E4%B8%AD%E8%80%81%E5%B9%B4%23) `207.2K 🔥` `+54%`
1. [315](https://s.weibo.com/weibo?q=%23315%23) `1.1M 🔥`
1. [未来5年民生保障再加力](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A55%E5%B9%B4%E6%B0%91%E7%94%9F%E4%BF%9D%E9%9A%9C%E5%86%8D%E5%8A%A0%E5%8A%9B%23) `674.9K 🔥`
1. [谢征掉马被打看的好爽 (It feels so good to see Xie Zheng fall off his horse and get beaten)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%8E%89%E9%A9%AC%E8%A2%AB%E6%89%93%E7%9C%8B%E7%9A%84%E5%A5%BD%E7%88%BD%23) `125.6K 🔥`
1. [刘文祥 (Liu Wenxiang)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%23) `370.8K 🔥` `-57%`
1. [25岁儿子毕业不工作急哭父亲 (The 25-year-old son is crying because he has no job after graduation.)](https://s.weibo.com/weibo?q=%2325%E5%B2%81%E5%84%BF%E5%AD%90%E6%AF%95%E4%B8%9A%E4%B8%8D%E5%B7%A5%E4%BD%9C%E6%80%A5%E5%93%AD%E7%88%B6%E4%BA%B2%23) `329.3K 🔥` `-45%`
1. [100万装出了10万的装修效果](https://s.weibo.com/weibo?q=%23100%E4%B8%87%E8%A3%85%E5%87%BA%E4%BA%8610%E4%B8%87%E7%9A%84%E8%A3%85%E4%BF%AE%E6%95%88%E6%9E%9C%23) `274.0K 🔥` `-26%`
1. [高质量睡眠对人的改变](https://s.weibo.com/weibo?q=%23%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9D%A1%E7%9C%A0%E5%AF%B9%E4%BA%BA%E7%9A%84%E6%94%B9%E5%8F%98%23) `114.0K 🔥` `-51%`
1. [中国爸爸带娃视频在推特上火了](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%88%B8%E7%88%B8%E5%B8%A6%E5%A8%83%E8%A7%86%E9%A2%91%E5%9C%A8%E6%8E%A8%E7%89%B9%E4%B8%8A%E7%81%AB%E4%BA%86%23) `104.5K 🔥` `-23%`
1. [谢娜晒老家学校旁边的面](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E6%99%92%E8%80%81%E5%AE%B6%E5%AD%A6%E6%A0%A1%E6%97%81%E8%BE%B9%E7%9A%84%E9%9D%A2%23) `103.8K 🔥` `-33%`
1. [网红锅巴厂原料和鞋垫一起烤](https://s.weibo.com/weibo?q=%23%E7%BD%91%E7%BA%A2%E9%94%85%E5%B7%B4%E5%8E%82%E5%8E%9F%E6%96%99%E5%92%8C%E9%9E%8B%E5%9E%AB%E4%B8%80%E8%B5%B7%E7%83%A4%23) `88.9K 🔥` `-77%`
1. [古巴](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E5%B7%B4%23) `75.2K 🔥` `-31%`

Updated at 2026-03-15 14:08:36

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
