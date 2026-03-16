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

1. [卧底卧成二把手的记者315又立功 (The reporter who went undercover and became the second-in-command in 315 made another meritorious service)](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%95%E5%8D%A7%E6%88%90%E4%BA%8C%E6%8A%8A%E6%89%8B%E7%9A%84%E8%AE%B0%E8%80%85315%E5%8F%88%E7%AB%8B%E5%8A%9F%23) `825.8K 🔥` `NEW`
1. [vivo宣布涨价](https://s.weibo.com/weibo?q=%23vivo%E5%AE%A3%E5%B8%83%E6%B6%A8%E4%BB%B7%23) `407.6K 🔥` `NEW`
1. [刘文祥被查紫薯精停更一天](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E8%A2%AB%E6%9F%A5%E7%B4%AB%E8%96%AF%E7%B2%BE%E5%81%9C%E6%9B%B4%E4%B8%80%E5%A4%A9%23) `378.1K 🔥` `NEW`
1. [伊朗称440公斤60%丰度浓缩铀被埋](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0440%E5%85%AC%E6%96%A460%25%E4%B8%B0%E5%BA%A6%E6%B5%93%E7%BC%A9%E9%93%80%E8%A2%AB%E5%9F%8B%23) `332.7K 🔥` `NEW`
1. [男子发现自己长期吃315曝光鸡爪](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%8F%91%E7%8E%B0%E8%87%AA%E5%B7%B1%E9%95%BF%E6%9C%9F%E5%90%83315%E6%9B%9D%E5%85%89%E9%B8%A1%E7%88%AA%23) `263.1K 🔥` `NEW`
1. [刘宇宁回应黄子韬道歉](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%9B%9E%E5%BA%94%E9%BB%84%E5%AD%90%E9%9F%AC%E9%81%93%E6%AD%89%23) `257.8K 🔥` `NEW`
1. [瞿颖 翻红](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%20%E7%BF%BB%E7%BA%A2%23) `254.4K 🔥` `NEW`
1. [315曝光后多地连夜通报](https://s.weibo.com/weibo?q=%23315%E6%9B%9D%E5%85%89%E5%90%8E%E5%A4%9A%E5%9C%B0%E8%BF%9E%E5%A4%9C%E9%80%9A%E6%8A%A5%23) `249.6K 🔥` `NEW`
1. [宋智雅因三星Galaxy言论被骂](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E6%99%BA%E9%9B%85%E5%9B%A0%E4%B8%89%E6%98%9FGalaxy%E8%A8%80%E8%AE%BA%E8%A2%AB%E9%AA%82%23) `242.2K 🔥` `NEW`
1. [姚安娜让我看到传说中的浮光锦了](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E5%AE%89%E5%A8%9C%E8%AE%A9%E6%88%91%E7%9C%8B%E5%88%B0%E4%BC%A0%E8%AF%B4%E4%B8%AD%E7%9A%84%E6%B5%AE%E5%85%89%E9%94%A6%E4%BA%86%23) `241.6K 🔥` `NEW`
1. [小狗舔人被说主人情绪失控 (Puppy licks people and its owner is said to have lost control of his emotions)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E8%88%94%E4%BA%BA%E8%A2%AB%E8%AF%B4%E4%B8%BB%E4%BA%BA%E6%83%85%E7%BB%AA%E5%A4%B1%E6%8E%A7%23) `238.5K 🔥` `NEW`
1. [终于有人把带孩子的累说清楚了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%8A%8A%E5%B8%A6%E5%AD%A9%E5%AD%90%E7%9A%84%E7%B4%AF%E8%AF%B4%E6%B8%85%E6%A5%9A%E4%BA%86%23) `208.8K 🔥` `NEW`
1. [漂白鸡爪涉事公司曾参与制定鸡爪标准](https://s.weibo.com/weibo?q=%23%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%E6%B6%89%E4%BA%8B%E5%85%AC%E5%8F%B8%E6%9B%BE%E5%8F%82%E4%B8%8E%E5%88%B6%E5%AE%9A%E9%B8%A1%E7%88%AA%E6%A0%87%E5%87%86%23) `172.6K 🔥` `NEW`
1. [周冬雨 刘昊然](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%AC%E9%9B%A8%20%E5%88%98%E6%98%8A%E7%84%B6%23) `146.1K 🔥` `NEW`
1. [14岁女儿在校被打智力退至3岁](https://s.weibo.com/weibo?q=%2314%E5%B2%81%E5%A5%B3%E5%84%BF%E5%9C%A8%E6%A0%A1%E8%A2%AB%E6%89%93%E6%99%BA%E5%8A%9B%E9%80%80%E8%87%B33%E5%B2%81%23) `134.9K 🔥` `NEW`
1. [邓凯又在犯姐夫瘾了](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E5%8F%88%E5%9C%A8%E7%8A%AF%E5%A7%90%E5%A4%AB%E7%98%BE%E4%BA%86%23) `132.3K 🔥` `NEW`
1. [卢昱晓被家乡台贴脸开大](https://s.weibo.com/weibo?q=%23%E5%8D%A2%E6%98%B1%E6%99%93%E8%A2%AB%E5%AE%B6%E4%B9%A1%E5%8F%B0%E8%B4%B4%E8%84%B8%E5%BC%80%E5%A4%A7%23) `122.8K 🔥` `NEW`
1. [卧底老K收入暴涨315总导演1天1电话](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%95%E8%80%81K%E6%94%B6%E5%85%A5%E6%9A%B4%E6%B6%A8315%E6%80%BB%E5%AF%BC%E6%BC%941%E5%A4%A91%E7%94%B5%E8%AF%9D%23) `122.8K 🔥` `NEW`
1. [逐玉为何被审判](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%B8%BA%E4%BD%95%E8%A2%AB%E5%AE%A1%E5%88%A4%23) `122.3K 🔥` `NEW`
1. [多国回应特朗普护航要求](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9B%BD%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E6%8A%A4%E8%88%AA%E8%A6%81%E6%B1%82%23) `122.0K 🔥` `NEW`
1. [武契奇称三个邻居准备进攻塞尔维亚 (Vucic says three neighbors are ready to attack Serbia)](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E5%A5%91%E5%A5%87%E7%A7%B0%E4%B8%89%E4%B8%AA%E9%82%BB%E5%B1%85%E5%87%86%E5%A4%87%E8%BF%9B%E6%94%BB%E5%A1%9E%E5%B0%94%E7%BB%B4%E4%BA%9A%23) `121.6K 🔥` `NEW`
1. [原来有天赋的孩子从小就能看出来](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E6%9C%89%E5%A4%A9%E8%B5%8B%E7%9A%84%E5%AD%A9%E5%AD%90%E4%BB%8E%E5%B0%8F%E5%B0%B1%E8%83%BD%E7%9C%8B%E5%87%BA%E6%9D%A5%23) `121.6K 🔥` `NEW`
1. [清融老乡杯江西队队长](https://s.weibo.com/weibo?q=%23%E6%B8%85%E8%9E%8D%E8%80%81%E4%B9%A1%E6%9D%AF%E6%B1%9F%E8%A5%BF%E9%98%9F%E9%98%9F%E9%95%BF%23) `110.3K 🔥` `NEW`
1. [甜茶至尊马蒂9提0中](https://s.weibo.com/weibo?q=%23%E7%94%9C%E8%8C%B6%E8%87%B3%E5%B0%8A%E9%A9%AC%E8%92%829%E6%8F%900%E4%B8%AD%23) `104.1K 🔥` `NEW`
1. [大侦探](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BE%A6%E6%8E%A2%23) `101.2K 🔥` `NEW`
1. [KPL老乡杯来了](https://s.weibo.com/weibo?q=%23KPL%E8%80%81%E4%B9%A1%E6%9D%AF%E6%9D%A5%E4%BA%86%23) `97.8K 🔥` `NEW`
1. [伊能静拥有女儿是太美好的事情](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E8%83%BD%E9%9D%99%E6%8B%A5%E6%9C%89%E5%A5%B3%E5%84%BF%E6%98%AF%E5%A4%AA%E7%BE%8E%E5%A5%BD%E7%9A%84%E4%BA%8B%E6%83%85%23) `95.8K 🔥` `NEW`
1. [油价](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%23) `92.8K 🔥` `NEW`
1. [伊朗亮出2000公里射程战略杀器](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BA%AE%E5%87%BA2000%E5%85%AC%E9%87%8C%E5%B0%84%E7%A8%8B%E6%88%98%E7%95%A5%E6%9D%80%E5%99%A8%23) `92.6K 🔥` `NEW`
1. [老乡杯队长](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%B9%A1%E6%9D%AF%E9%98%9F%E9%95%BF%23) `90.6K 🔥` `NEW`
1. [现货黄金跳水金饰反涨 (Spot gold dives and gold jewelry rebounds)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E8%B4%A7%E9%BB%84%E9%87%91%E8%B7%B3%E6%B0%B4%E9%87%91%E9%A5%B0%E5%8F%8D%E6%B6%A8%23) `86.5K 🔥` `NEW`
1. [中南大学和湖南卫健委成立联合调查组](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%8D%97%E5%A4%A7%E5%AD%A6%E5%92%8C%E6%B9%96%E5%8D%97%E5%8D%AB%E5%81%A5%E5%A7%94%E6%88%90%E7%AB%8B%E8%81%94%E5%90%88%E8%B0%83%E6%9F%A5%E7%BB%84%23) `261.7K 🔥` `+54%`
1. [脑梗最快急救方法](https://s.weibo.com/weibo?q=%23%E8%84%91%E6%A2%97%E6%9C%80%E5%BF%AB%E6%80%A5%E6%95%91%E6%96%B9%E6%B3%95%23) `247.6K 🔥` `+104%`
1. [家有七郎开机](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E6%9C%89%E4%B8%83%E9%83%8E%E5%BC%80%E6%9C%BA%23) `147.0K 🔥` `+81%`
1. [315曝光名单 (315 exposure list)](https://s.weibo.com/weibo?q=%23315%E6%9B%9D%E5%85%89%E5%90%8D%E5%8D%95%23) `1.1M 🔥`
1. [央视新闻实测腾势极寒闪充 (CCTV News measured extreme cold flash charging)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB%E5%AE%9E%E6%B5%8B%E8%85%BE%E5%8A%BF%E6%9E%81%E5%AF%92%E9%97%AA%E5%85%85%23) `350.5K 🔥`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `252.3K 🔥`
1. [鹿晗 关晓彤](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `168.3K 🔥`
1. [奥斯卡](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E6%96%AF%E5%8D%A1%23) `134.8K 🔥`
1. [2026奥斯卡获奖名单 (2026 Oscar winners list)](https://s.weibo.com/weibo?q=%232026%E5%A5%A5%E6%96%AF%E5%8D%A1%E8%8E%B7%E5%A5%96%E5%90%8D%E5%8D%95%23) `134.4K 🔥`
1. [刘宇宁不去鸟巢开演唱会的原因](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E4%B8%8D%E5%8E%BB%E9%B8%9F%E5%B7%A2%E5%BC%80%E6%BC%94%E5%94%B1%E4%BC%9A%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `111.8K 🔥`
1. [致敬每一份不屈的热爱](https://s.weibo.com/weibo?q=%23%E8%87%B4%E6%95%AC%E6%AF%8F%E4%B8%80%E4%BB%BD%E4%B8%8D%E5%B1%88%E7%9A%84%E7%83%AD%E7%88%B1%23) `645.5K 🔥` `-33%`
1. [湘雅医院失联学生确认坠江身亡 (Missing student from Xiangya Hospital confirmed to have fallen into river and died)](https://s.weibo.com/weibo?q=%23%E6%B9%98%E9%9B%85%E5%8C%BB%E9%99%A2%E5%A4%B1%E8%81%94%E5%AD%A6%E7%94%9F%E7%A1%AE%E8%AE%A4%E5%9D%A0%E6%B1%9F%E8%BA%AB%E4%BA%A1%23) `351.0K 🔥` `-78%`
1. [漂白鸡爪企业致歉](https://s.weibo.com/weibo?q=%23%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%E4%BC%81%E4%B8%9A%E8%87%B4%E6%AD%89%23) `270.9K 🔥` `-63%`
1. [湘雅 (Xiangya)](https://s.weibo.com/weibo?q=%23%E6%B9%98%E9%9B%85%23) `150.3K 🔥` `-33%`
1. [内塔尼亚胡发视频自证在世 (Netanyahu posts video to prove he is alive)](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A1%94%E5%B0%BC%E4%BA%9A%E8%83%A1%E5%8F%91%E8%A7%86%E9%A2%91%E8%87%AA%E8%AF%81%E5%9C%A8%E4%B8%96%23) `133.3K 🔥` `-58%`
1. [田曦薇任豪 我欲乘风 (Tian Xiwei Ren Hao I want to ride the wind)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E4%BB%BB%E8%B1%AA%20%E6%88%91%E6%AC%B2%E4%B9%98%E9%A3%8E%23) `109.7K 🔥` `-27%`
1. [大冰教家长应对孩子不自律](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%86%B0%E6%95%99%E5%AE%B6%E9%95%BF%E5%BA%94%E5%AF%B9%E5%AD%A9%E5%AD%90%E4%B8%8D%E8%87%AA%E5%BE%8B%23) `103.8K 🔥` `-71%`
1. [樊长玉因身份悬殊不敢回应](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E5%9B%A0%E8%BA%AB%E4%BB%BD%E6%82%AC%E6%AE%8A%E4%B8%8D%E6%95%A2%E5%9B%9E%E5%BA%94%23) `103.7K 🔥` `-50%`
1. [卖给孩子的可爱卡片竟有上吊暗示](https://s.weibo.com/weibo?q=%23%E5%8D%96%E7%BB%99%E5%AD%A9%E5%AD%90%E7%9A%84%E5%8F%AF%E7%88%B1%E5%8D%A1%E7%89%87%E7%AB%9F%E6%9C%89%E4%B8%8A%E5%90%8A%E6%9A%97%E7%A4%BA%23) `97.8K 🔥` `-81%`
1. [王俊凯 演唱会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%20%E6%BC%94%E5%94%B1%E4%BC%9A%23) `88.3K 🔥` `-36%`

Updated at 2026-03-16 13:29:55

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
