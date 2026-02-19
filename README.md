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

1. [中国冰壶男队4比6不敌德国队 (The Chinese men's curling team lost to the German team 4-6)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%86%B0%E5%A3%B6%E7%94%B7%E9%98%9F4%E6%AF%946%E4%B8%8D%E6%95%8C%E5%BE%B7%E5%9B%BD%E9%98%9F%23) `158.0K 🔥` `NEW`
1. [王安宇你玩狼人杀不是这样的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E4%BD%A0%E7%8E%A9%E7%8B%BC%E4%BA%BA%E6%9D%80%E4%B8%8D%E6%98%AF%E8%BF%99%E6%A0%B7%E7%9A%84%23) `139.5K 🔥` `NEW`
1. [网剧双轨](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%89%A7%E5%8F%8C%E8%BD%A8%23) `133.0K 🔥` `NEW`
1. [亲信透露尹锡悦为护妻铤而走险](https://s.weibo.com/weibo?q=%23%E4%BA%B2%E4%BF%A1%E9%80%8F%E9%9C%B2%E5%B0%B9%E9%94%A1%E6%82%A6%E4%B8%BA%E6%8A%A4%E5%A6%BB%E9%93%A4%E8%80%8C%E8%B5%B0%E9%99%A9%23) `120.1K 🔥` `NEW`
1. [海南偶遇吴谨言洪尧吃饭](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8D%97%E5%81%B6%E9%81%87%E5%90%B4%E8%B0%A8%E8%A8%80%E6%B4%AA%E5%B0%A7%E5%90%83%E9%A5%AD%23) `111.3K 🔥` `NEW`
1. [自取其辱九件套](https://s.weibo.com/weibo?q=%23%E8%87%AA%E5%8F%96%E5%85%B6%E8%BE%B1%E4%B9%9D%E4%BB%B6%E5%A5%97%23) `106.9K 🔥` `NEW`
1. [黄宗泽6岁已经是潮男](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AE%97%E6%B3%BD6%E5%B2%81%E5%B7%B2%E7%BB%8F%E6%98%AF%E6%BD%AE%E7%94%B7%23) `105.3K 🔥` `NEW`
1. [于适那么帅 吴京在后面像个帆布袋](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E9%80%82%E9%82%A3%E4%B9%88%E5%B8%85%20%E5%90%B4%E4%BA%AC%E5%9C%A8%E5%90%8E%E9%9D%A2%E5%83%8F%E4%B8%AA%E5%B8%86%E5%B8%83%E8%A2%8B%23) `100.6K 🔥` `NEW`
1. [谷爱凌U池的权威我后知后觉](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E6%B1%A0%E7%9A%84%E6%9D%83%E5%A8%81%E6%88%91%E5%90%8E%E7%9F%A5%E5%90%8E%E8%A7%89%23) `91.1K 🔥` `NEW`
1. [我们的少年时代2](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%23) `85.0K 🔥` `NEW`
1. [苏翊鸣谷爱凌小时候训练日常 (Su Yi Minggu Ailing’s daily training when she was a child)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E8%B0%B7%E7%88%B1%E5%87%8C%E5%B0%8F%E6%97%B6%E5%80%99%E8%AE%AD%E7%BB%83%E6%97%A5%E5%B8%B8%23) `76.6K 🔥` `NEW`
1. [学生回应哈工大为留校生发压岁钱](https://s.weibo.com/weibo?q=%23%E5%AD%A6%E7%94%9F%E5%9B%9E%E5%BA%94%E5%93%88%E5%B7%A5%E5%A4%A7%E4%B8%BA%E7%95%99%E6%A0%A1%E7%94%9F%E5%8F%91%E5%8E%8B%E5%B2%81%E9%92%B1%23) `70.7K 🔥` `NEW`
1. [2026春节档票房超30亿](https://s.weibo.com/weibo?q=%232026%E6%98%A5%E8%8A%82%E6%A1%A3%E7%A5%A8%E6%88%BF%E8%B6%8530%E4%BA%BF%23) `59.3K 🔥` `NEW`
1. [尹锡悦被判无期徒刑 (Yin Xiyue was sentenced to life imprisonment)](https://s.weibo.com/weibo?q=%23%E5%B0%B9%E9%94%A1%E6%82%A6%E8%A2%AB%E5%88%A4%E6%97%A0%E6%9C%9F%E5%BE%92%E5%88%91%23) `464.1K 🔥` `+49%`
1. [冬奥版美强惨出现了](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E7%89%88%E7%BE%8E%E5%BC%BA%E6%83%A8%E5%87%BA%E7%8E%B0%E4%BA%86%23) `414.9K 🔥` `+243%`
1. [首档中老年恋综成了4对](https://s.weibo.com/weibo?q=%23%E9%A6%96%E6%A1%A3%E4%B8%AD%E8%80%81%E5%B9%B4%E6%81%8B%E7%BB%BC%E6%88%90%E4%BA%864%E5%AF%B9%23) `410.6K 🔥` `+97%`
1. [王兴兴独家揭秘春晚机器人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%85%B4%E5%85%B4%E7%8B%AC%E5%AE%B6%E6%8F%AD%E7%A7%98%E6%98%A5%E6%99%9A%E6%9C%BA%E5%99%A8%E4%BA%BA%23) `286.9K 🔥` `+33%`
1. [吴京 朕们和我从来没有嫌隙](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E6%9C%95%E4%BB%AC%E5%92%8C%E6%88%91%E4%BB%8E%E6%9D%A5%E6%B2%A1%E6%9C%89%E5%AB%8C%E9%9A%99%23) `263.3K 🔥` `+282%`
1. [希林娜依高7米变色长裙唱浮光](https://s.weibo.com/weibo?q=%23%E5%B8%8C%E6%9E%97%E5%A8%9C%E4%BE%9D%E9%AB%987%E7%B1%B3%E5%8F%98%E8%89%B2%E9%95%BF%E8%A3%99%E5%94%B1%E6%B5%AE%E5%85%89%23) `160.3K 🔥` `+32%`
1. [英国前王子安德鲁被捕 (Former British Prince Andrew arrested)](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E5%89%8D%E7%8E%8B%E5%AD%90%E5%AE%89%E5%BE%B7%E9%B2%81%E8%A2%AB%E6%8D%95%23) `1.1M 🔥`
1. [苏翊鸣 为了露表手忙脚乱](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%20%E4%B8%BA%E4%BA%86%E9%9C%B2%E8%A1%A8%E6%89%8B%E5%BF%99%E8%84%9A%E4%B9%B1%23) `797.6K 🔥`
1. [春节不归人坚守汇成动人团圆 (People who have not returned during the Spring Festival stick to each other and form a touching reunion)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E4%B8%8D%E5%BD%92%E4%BA%BA%E5%9D%9A%E5%AE%88%E6%B1%87%E6%88%90%E5%8A%A8%E4%BA%BA%E5%9B%A2%E5%9C%86%23) `617.9K 🔥`
1. [鲍鱼壳 除蟑螂 (Abalone shell to remove cockroaches)](https://s.weibo.com/weibo?q=%23%E9%B2%8D%E9%B1%BC%E5%A3%B3%20%E9%99%A4%E8%9F%91%E8%9E%82%23) `164.7K 🔥`
1. [高层看烟花有多吓人 (How scary is it to watch fireworks from high-rise buildings?)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B1%82%E7%9C%8B%E7%83%9F%E8%8A%B1%E6%9C%89%E5%A4%9A%E5%90%93%E4%BA%BA%23) `152.9K 🔥`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `146.9K 🔥`
1. [刘德华解冻失败 (Andy Lau failed to unfreeze)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BE%B7%E5%8D%8E%E8%A7%A3%E5%86%BB%E5%A4%B1%E8%B4%A5%23) `113.8K 🔥`
1. [2名初中生扶摔倒女子遭索赔22万 (Two junior high school students helped a woman who fell down and were compensated for NT$220,000)](https://s.weibo.com/weibo?q=%232%E5%90%8D%E5%88%9D%E4%B8%AD%E7%94%9F%E6%89%B6%E6%91%94%E5%80%92%E5%A5%B3%E5%AD%90%E9%81%AD%E7%B4%A2%E8%B5%9422%E4%B8%87%23) `112.6K 🔥`
1. [白鹿韩国](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E9%9F%A9%E5%9B%BD%23) `110.4K 🔥`
1. [爸爸除夕独自吃饺子女儿看监控哭了](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E9%99%A4%E5%A4%95%E7%8B%AC%E8%87%AA%E5%90%83%E9%A5%BA%E5%AD%90%E5%A5%B3%E5%84%BF%E7%9C%8B%E7%9B%91%E6%8E%A7%E5%93%AD%E4%BA%86%23) `108.4K 🔥`
1. [王嘉尔纠正阿玛尼官方](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%98%89%E5%B0%94%E7%BA%A0%E6%AD%A3%E9%98%BF%E7%8E%9B%E5%B0%BC%E5%AE%98%E6%96%B9%23) `105.5K 🔥`
1. [镖人票房破3亿 (The box office of Daredevil exceeded 300 million)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E7%A0%B43%E4%BA%BF%23) `103.5K 🔥`
1. [飞驰人生](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F%23) `100.7K 🔥`
1. [中国短道速滑还有一个项目可冲金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E8%BF%98%E6%9C%89%E4%B8%80%E4%B8%AA%E9%A1%B9%E7%9B%AE%E5%8F%AF%E5%86%B2%E9%87%91%23) `100.6K 🔥`
1. [昀牵孟绕](https://s.weibo.com/weibo?q=%23%E6%98%80%E7%89%B5%E5%AD%9F%E7%BB%95%23) `78.6K 🔥`
1. [Doinb转型DOTA2选手 (Doinb transforms into a DOTA2 player)](https://s.weibo.com/weibo?q=%23Doinb%E8%BD%AC%E5%9E%8BDOTA2%E9%80%89%E6%89%8B%23) `77.6K 🔥`
1. [白鹿用韩语和韩国粉丝聊天](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E7%94%A8%E9%9F%A9%E8%AF%AD%E5%92%8C%E9%9F%A9%E5%9B%BD%E7%B2%89%E4%B8%9D%E8%81%8A%E5%A4%A9%23) `71.6K 🔥`
1. [以防你没见过小鸟摇屁股](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E9%98%B2%E4%BD%A0%E6%B2%A1%E8%A7%81%E8%BF%87%E5%B0%8F%E9%B8%9F%E6%91%87%E5%B1%81%E8%82%A1%23) `60.1K 🔥`
1. [过年 二手烟](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%20%E4%BA%8C%E6%89%8B%E7%83%9F%23) `140.5K 🔥` `-43%`
1. [玩手机是一件很私人的事情 (Playing with a mobile phone is a very personal thing)](https://s.weibo.com/weibo?q=%23%E7%8E%A9%E6%89%8B%E6%9C%BA%E6%98%AF%E4%B8%80%E4%BB%B6%E5%BE%88%E7%A7%81%E4%BA%BA%E7%9A%84%E4%BA%8B%E6%83%85%23) `129.9K 🔥` `-22%`
1. [尹锡悦听宣判后叹气面色凝重](https://s.weibo.com/weibo?q=%23%E5%B0%B9%E9%94%A1%E6%82%A6%E5%90%AC%E5%AE%A3%E5%88%A4%E5%90%8E%E5%8F%B9%E6%B0%94%E9%9D%A2%E8%89%B2%E5%87%9D%E9%87%8D%23) `128.4K 🔥` `-48%`
1. [我将学会谷爱凌这个大笑方式 (I will learn Gu Ailing’s way of laughing)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%B0%86%E5%AD%A6%E4%BC%9A%E8%B0%B7%E7%88%B1%E5%87%8C%E8%BF%99%E4%B8%AA%E5%A4%A7%E7%AC%91%E6%96%B9%E5%BC%8F%23) `124.2K 🔥` `-23%`
1. [双轨还有售后](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E8%BD%A8%E8%BF%98%E6%9C%89%E5%94%AE%E5%90%8E%23) `114.4K 🔥` `-26%`
1. [疯狂星期四调休](https://s.weibo.com/weibo?q=%23%E7%96%AF%E7%8B%82%E6%98%9F%E6%9C%9F%E5%9B%9B%E8%B0%83%E4%BC%91%23) `104.2K 🔥` `-33%`
1. [韩延哽咽谈星河入梦排片](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%BB%B6%E5%93%BD%E5%92%BD%E8%B0%88%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%E6%8E%92%E7%89%87%23) `99.0K 🔥` `-26%`
1. [左奇函外拍 (Zuo Qihan's outdoor shooting)](https://s.weibo.com/weibo?q=%23%E5%B7%A6%E5%A5%87%E5%87%BD%E5%A4%96%E6%8B%8D%23) `88.0K 🔥` `-23%`
1. [金价迎来新一轮大涨](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E8%BF%8E%E6%9D%A5%E6%96%B0%E4%B8%80%E8%BD%AE%E5%A4%A7%E6%B6%A8%23) `80.5K 🔥` `-29%`
1. [阿沁自曝和刘阳分开后谈过两段感情](https://s.weibo.com/weibo?q=%23%E9%98%BF%E6%B2%81%E8%87%AA%E6%9B%9D%E5%92%8C%E5%88%98%E9%98%B3%E5%88%86%E5%BC%80%E5%90%8E%E8%B0%88%E8%BF%87%E4%B8%A4%E6%AE%B5%E6%84%9F%E6%83%85%23) `79.6K 🔥` `-31%`
1. [旺旺雪饼vs仙贝](https://s.weibo.com/weibo?q=%23%E6%97%BA%E6%97%BA%E9%9B%AA%E9%A5%BCvs%E4%BB%99%E8%B4%9D%23) `72.3K 🔥` `-51%`
1. [镖人有望保三争二](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E6%9C%89%E6%9C%9B%E4%BF%9D%E4%B8%89%E4%BA%89%E4%BA%8C%23) `64.7K 🔥` `-25%`
1. [面包界需要一个蜜雪冰城 (The bakery industry needs a Michelle Ice City)](https://s.weibo.com/weibo?q=%23%E9%9D%A2%E5%8C%85%E7%95%8C%E9%9C%80%E8%A6%81%E4%B8%80%E4%B8%AA%E8%9C%9C%E9%9B%AA%E5%86%B0%E5%9F%8E%23) `61.5K 🔥` `-23%`
1. [关晓彤滑雪摔屁墩儿](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E6%BB%91%E9%9B%AA%E6%91%94%E5%B1%81%E5%A2%A9%E5%84%BF%23) `60.2K 🔥` `-49%`

Updated at 2026-02-19 19:48:32

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
