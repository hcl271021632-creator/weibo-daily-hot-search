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

1. [孙颖莎vs蒯曼 (Sun Yingsha vs Kuaiman)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E8%92%AF%E6%9B%BC%23) `311.4K 🔥` `NEW`
1. [直击鸟中大熊猫青头潜鸭野化放飞](https://s.weibo.com/weibo?q=%23%E7%9B%B4%E5%87%BB%E9%B8%9F%E4%B8%AD%E5%A4%A7%E7%86%8A%E7%8C%AB%E9%9D%92%E5%A4%B4%E6%BD%9C%E9%B8%AD%E9%87%8E%E5%8C%96%E6%94%BE%E9%A3%9E%23) `166.5K 🔥` `NEW`
1. [离职守恒定律](https://s.weibo.com/weibo?q=%23%E7%A6%BB%E8%81%8C%E5%AE%88%E6%81%92%E5%AE%9A%E5%BE%8B%23) `162.4K 🔥` `NEW`
1. [泰国女星近乎昏迷时遭救护员性侵](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E5%A5%B3%E6%98%9F%E8%BF%91%E4%B9%8E%E6%98%8F%E8%BF%B7%E6%97%B6%E9%81%AD%E6%95%91%E6%8A%A4%E5%91%98%E6%80%A7%E4%BE%B5%23) `159.6K 🔥` `NEW`
1. [乘风2026立意片来了](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E7%AB%8B%E6%84%8F%E7%89%87%E6%9D%A5%E4%BA%86%23) `156.7K 🔥` `NEW`
1. [以色列遭到开战以来最大规模导弹袭击](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E9%81%AD%E5%88%B0%E5%BC%80%E6%88%98%E4%BB%A5%E6%9D%A5%E6%9C%80%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%23) `126.3K 🔥` `NEW`
1. [毛晓彤花神妆](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%99%93%E5%BD%A4%E8%8A%B1%E7%A5%9E%E5%A6%86%23) `111.4K 🔥` `NEW`
1. [古巨基二胎儿子正面照公开](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E5%B7%A8%E5%9F%BA%E4%BA%8C%E8%83%8E%E5%84%BF%E5%AD%90%E6%AD%A3%E9%9D%A2%E7%85%A7%E5%85%AC%E5%BC%80%23) `107.1K 🔥` `NEW`
1. [林依晨43岁状态](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BE%9D%E6%99%A843%E5%B2%81%E7%8A%B6%E6%80%81%23) `106.1K 🔥` `NEW`
1. [高圆圆赵又廷女儿长这么大了](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%9C%86%E5%9C%86%E8%B5%B5%E5%8F%88%E5%BB%B7%E5%A5%B3%E5%84%BF%E9%95%BF%E8%BF%99%E4%B9%88%E5%A4%A7%E4%BA%86%23) `104.8K 🔥` `NEW`
1. [白日提灯 (day lantern)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `104.3K 🔥` `NEW`
1. [TOP全员感冒](https://s.weibo.com/weibo?q=%23TOP%E5%85%A8%E5%91%98%E6%84%9F%E5%86%92%23) `101.4K 🔥` `NEW`
1. [孙颖莎蒯曼争八强](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E8%92%AF%E6%9B%BC%E4%BA%89%E5%85%AB%E5%BC%BA%23) `99.8K 🔥` `NEW`
1. [你好1983结局](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD1983%E7%BB%93%E5%B1%80%23) `98.6K 🔥` `NEW`
1. [孙颖莎11比4蒯曼](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E11%E6%AF%944%E8%92%AF%E6%9B%BC%23) `98.3K 🔥` `NEW`
1. [性侵泰国女星嫌疑人已承认指控](https://s.weibo.com/weibo?q=%23%E6%80%A7%E4%BE%B5%E6%B3%B0%E5%9B%BD%E5%A5%B3%E6%98%9F%E5%AB%8C%E7%96%91%E4%BA%BA%E5%B7%B2%E6%89%BF%E8%AE%A4%E6%8C%87%E6%8E%A7%23) `77.4K 🔥` `NEW`
1. [现货黄金](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E8%B4%A7%E9%BB%84%E9%87%91%23) `76.8K 🔥` `NEW`
1. [深圳高铁站台禁烟](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E9%AB%98%E9%93%81%E7%AB%99%E5%8F%B0%E7%A6%81%E7%83%9F%23) `72.7K 🔥` `NEW`
1. [张俪回应二搭迪丽热巴](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BF%AA%E5%9B%9E%E5%BA%94%E4%BA%8C%E6%90%AD%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%23) `71.9K 🔥` `NEW`
1. [14岁男孩与猫狗同吃同睡双眼险失明](https://s.weibo.com/weibo?q=%2314%E5%B2%81%E7%94%B7%E5%AD%A9%E4%B8%8E%E7%8C%AB%E7%8B%97%E5%90%8C%E5%90%83%E5%90%8C%E7%9D%A1%E5%8F%8C%E7%9C%BC%E9%99%A9%E5%A4%B1%E6%98%8E%23) `71.0K 🔥` `NEW`
1. [张雪谈夺冠那一刻 (Zhang Xue talks about the moment she won the championship)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E8%B0%88%E5%A4%BA%E5%86%A0%E9%82%A3%E4%B8%80%E5%88%BB%23) `66.9K 🔥` `NEW`
1. [智界CEO谈亏本卖车](https://s.weibo.com/weibo?q=%23%E6%99%BA%E7%95%8CCEO%E8%B0%88%E4%BA%8F%E6%9C%AC%E5%8D%96%E8%BD%A6%23) `65.3K 🔥` `NEW`
1. [NS零封DK](https://s.weibo.com/weibo?q=%23NS%E9%9B%B6%E5%B0%81DK%23) `64.4K 🔥` `NEW`
1. [带货优思益明星或担连带责任](https://s.weibo.com/weibo?q=%23%E5%B8%A6%E8%B4%A7%E4%BC%98%E6%80%9D%E7%9B%8A%E6%98%8E%E6%98%9F%E6%88%96%E6%8B%85%E8%BF%9E%E5%B8%A6%E8%B4%A3%E4%BB%BB%23) `63.0K 🔥` `NEW`
1. [印度65岁大象死亡生前被涂粉色颜料 (65-year-old elephant in India was painted pink before death)](https://s.weibo.com/weibo?q=%23%E5%8D%B0%E5%BA%A665%E5%B2%81%E5%A4%A7%E8%B1%A1%E6%AD%BB%E4%BA%A1%E7%94%9F%E5%89%8D%E8%A2%AB%E6%B6%82%E7%B2%89%E8%89%B2%E9%A2%9C%E6%96%99%23) `1.1M 🔥` `+1149%`
1. [已吃两瓶优思益消费者发声](https://s.weibo.com/weibo?q=%23%E5%B7%B2%E5%90%83%E4%B8%A4%E7%93%B6%E4%BC%98%E6%80%9D%E7%9B%8A%E6%B6%88%E8%B4%B9%E8%80%85%E5%8F%91%E5%A3%B0%23) `775.0K 🔥` `+279%`
1. [三年后狗近视得找不到饭盆](https://s.weibo.com/weibo?q=%23%E4%B8%89%E5%B9%B4%E5%90%8E%E7%8B%97%E8%BF%91%E8%A7%86%E5%BE%97%E6%89%BE%E4%B8%8D%E5%88%B0%E9%A5%AD%E7%9B%86%23) `238.1K 🔥` `+179%`
1. [乘风2026](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%23) `167.8K 🔥` `+87%`
1. [董宇辉称商品上架前会完成相关检测](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AE%87%E8%BE%89%E7%A7%B0%E5%95%86%E5%93%81%E4%B8%8A%E6%9E%B6%E5%89%8D%E4%BC%9A%E5%AE%8C%E6%88%90%E7%9B%B8%E5%85%B3%E6%A3%80%E6%B5%8B%23) `102.3K 🔥` `+58%`
1. [又是赏花好时节 (It’s a good time to enjoy flowers again)](https://s.weibo.com/weibo?q=%23%E5%8F%88%E6%98%AF%E8%B5%8F%E8%8A%B1%E5%A5%BD%E6%97%B6%E8%8A%82%23) `649.7K 🔥`
1. [华为畅享90满电奔赴 (Huawei Enjoys 90% Charge on the Road)](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%B8%BA%E7%95%85%E4%BA%AB90%E6%BB%A1%E7%94%B5%E5%A5%94%E8%B5%B4%23) `646.3K 🔥`
1. [被时代淘汰的水果](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E6%97%B6%E4%BB%A3%E6%B7%98%E6%B1%B0%E7%9A%84%E6%B0%B4%E6%9E%9C%23) `276.4K 🔥`
1. [清明假期首选神州租车 (Car rental in China is the first choice during the Qingming Festival)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E9%A6%96%E9%80%89%E7%A5%9E%E5%B7%9E%E7%A7%9F%E8%BD%A6%23) `257.9K 🔥`
1. [优思益 (Yousiyi)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `254.1K 🔥`
1. [张杰回应张凌赫送花篮](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E5%9B%9E%E5%BA%94%E5%BC%A0%E5%87%8C%E8%B5%AB%E9%80%81%E8%8A%B1%E7%AF%AE%23) `157.0K 🔥`
1. [男孩捡50g金条咬了一口竟是真的 (The boy picked up a 50g gold bar and took a bite, it turned out to be real)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E6%8D%A150g%E9%87%91%E6%9D%A1%E5%92%AC%E4%BA%86%E4%B8%80%E5%8F%A3%E7%AB%9F%E6%98%AF%E7%9C%9F%E7%9A%84%23) `145.3K 🔥`
1. [男子趁妻子去厕所上台相亲](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%B6%81%E5%A6%BB%E5%AD%90%E5%8E%BB%E5%8E%95%E6%89%80%E4%B8%8A%E5%8F%B0%E7%9B%B8%E4%BA%B2%23) `105.5K 🔥`
1. [曾舜晞工作室致歉](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E5%B7%A5%E4%BD%9C%E5%AE%A4%E8%87%B4%E6%AD%89%23) `101.5K 🔥`
1. [李若彤发布致歉声明](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8B%A5%E5%BD%A4%E5%8F%91%E5%B8%83%E8%87%B4%E6%AD%89%E5%A3%B0%E6%98%8E%23) `99.7K 🔥`
1. [同事离职显得我很命苦](https://s.weibo.com/weibo?q=%23%E5%90%8C%E4%BA%8B%E7%A6%BB%E8%81%8C%E6%98%BE%E5%BE%97%E6%88%91%E5%BE%88%E5%91%BD%E8%8B%A6%23) `97.1K 🔥`
1. [伊朗公布最新战果](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%85%AC%E5%B8%83%E6%9C%80%E6%96%B0%E6%88%98%E6%9E%9C%23) `97.1K 🔥`
1. [优思益总销量与辉同行占了近40%](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E6%80%BB%E9%94%80%E9%87%8F%E4%B8%8E%E8%BE%89%E5%90%8C%E8%A1%8C%E5%8D%A0%E4%BA%86%E8%BF%9140%25%23) `72.7K 🔥`
1. [应激性开花](https://s.weibo.com/weibo?q=%23%E5%BA%94%E6%BF%80%E6%80%A7%E5%BC%80%E8%8A%B1%23) `71.0K 🔥`
1. [阿花花酱 优思益 (Ahuahuajiang Yousiyi)](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%8A%B1%E8%8A%B1%E9%85%B1%20%E4%BC%98%E6%80%9D%E7%9B%8A%23) `63.0K 🔥`
1. [女子104000元买80g金条店员报警](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90104000%E5%85%83%E4%B9%B080g%E9%87%91%E6%9D%A1%E5%BA%97%E5%91%98%E6%8A%A5%E8%AD%A6%23) `290.3K 🔥` `-73%`
1. [李荣浩方否认恋人抄袭 (Li Ronghao denies plagiarism by his lover)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8D%A3%E6%B5%A9%E6%96%B9%E5%90%A6%E8%AE%A4%E6%81%8B%E4%BA%BA%E6%8A%84%E8%A2%AD%23) `164.4K 🔥` `-69%`
1. [美国一婴儿光天化日在街头被枪杀 (A baby was shot dead on the street in broad daylight in the United States)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%80%E5%A9%B4%E5%84%BF%E5%85%89%E5%A4%A9%E5%8C%96%E6%97%A5%E5%9C%A8%E8%A1%97%E5%A4%B4%E8%A2%AB%E6%9E%AA%E6%9D%80%23) `107.2K 🔥` `-25%`
1. [警方通报司机猥亵后排女乘客](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E5%8F%B8%E6%9C%BA%E7%8C%A5%E4%BA%B5%E5%90%8E%E6%8E%92%E5%A5%B3%E4%B9%98%E5%AE%A2%23) `92.1K 🔥` `-66%`
1. [张雪机车夺冠车手发声 (Zhang Xue’s motorcycle winning driver speaks out)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E5%A4%BA%E5%86%A0%E8%BD%A6%E6%89%8B%E5%8F%91%E5%A3%B0%23) `92.1K 🔥` `-88%`
1. [火旺 宋威龙 (Huo Wang Song Weilong)](https://s.weibo.com/weibo?q=%23%E7%81%AB%E6%97%BA%20%E5%AE%8B%E5%A8%81%E9%BE%99%23) `85.5K 🔥` `-42%`
1. [优思益营销策划公司被立案调查 (Yousiyi Marketing Planning Company was placed under investigation)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E8%90%A5%E9%94%80%E7%AD%96%E5%88%92%E5%85%AC%E5%8F%B8%E8%A2%AB%E7%AB%8B%E6%A1%88%E8%B0%83%E6%9F%A5%23) `74.3K 🔥` `-43%`
1. [伊朗拒绝谈判的真实底牌](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8B%92%E7%BB%9D%E8%B0%88%E5%88%A4%E7%9A%84%E7%9C%9F%E5%AE%9E%E5%BA%95%E7%89%8C%23) `69.5K 🔥` `-22%`

Updated at 2026-04-02 19:09:33

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
