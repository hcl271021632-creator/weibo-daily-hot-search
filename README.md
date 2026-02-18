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

1. [过年上淘宝闪购抢电影奶茶免单 (Go to Taobao flash sale to grab movie milk tea for free during Chinese New Year)](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E4%B8%8A%E6%B7%98%E5%AE%9D%E9%97%AA%E8%B4%AD%E6%8A%A2%E7%94%B5%E5%BD%B1%E5%A5%B6%E8%8C%B6%E5%85%8D%E5%8D%95%23) `632.6K 🔥` `NEW`
1. [河北医保局辟谣可领500元分娩补贴](https://s.weibo.com/weibo?q=%23%E6%B2%B3%E5%8C%97%E5%8C%BB%E4%BF%9D%E5%B1%80%E8%BE%9F%E8%B0%A3%E5%8F%AF%E9%A2%86500%E5%85%83%E5%88%86%E5%A8%A9%E8%A1%A5%E8%B4%B4%23) `219.2K 🔥` `NEW`
1. [贡菜是莴笋](https://s.weibo.com/weibo?q=%23%E8%B4%A1%E8%8F%9C%E6%98%AF%E8%8E%B4%E7%AC%8B%23) `213.0K 🔥` `NEW`
1. [王橹杰娃娃](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E5%A8%83%E5%A8%83%23) `124.2K 🔥` `NEW`
1. [印一大学被曝买宇树机器狗冒充自研](https://s.weibo.com/weibo?q=%23%E5%8D%B0%E4%B8%80%E5%A4%A7%E5%AD%A6%E8%A2%AB%E6%9B%9D%E4%B9%B0%E5%AE%87%E6%A0%91%E6%9C%BA%E5%99%A8%E7%8B%97%E5%86%92%E5%85%85%E8%87%AA%E7%A0%94%23) `110.0K 🔥` `NEW`
1. [打麻将输7万4名牌友全获刑](https://s.weibo.com/weibo?q=%23%E6%89%93%E9%BA%BB%E5%B0%86%E8%BE%937%E4%B8%874%E5%90%8D%E7%89%8C%E5%8F%8B%E5%85%A8%E8%8E%B7%E5%88%91%23) `103.6K 🔥` `NEW`
1. [我和papi酱的愿望是一样的](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%92%8Cpapi%E9%85%B1%E7%9A%84%E6%84%BF%E6%9C%9B%E6%98%AF%E4%B8%80%E6%A0%B7%E7%9A%84%23) `103.2K 🔥` `NEW`
1. [航司回应新年伊始机票价腰斩](https://s.weibo.com/weibo?q=%23%E8%88%AA%E5%8F%B8%E5%9B%9E%E5%BA%94%E6%96%B0%E5%B9%B4%E4%BC%8A%E5%A7%8B%E6%9C%BA%E7%A5%A8%E4%BB%B7%E8%85%B0%E6%96%A9%23) `102.9K 🔥` `NEW`
1. [TF四代娃娃](https://s.weibo.com/weibo?q=%23TF%E5%9B%9B%E4%BB%A3%E5%A8%83%E5%A8%83%23) `102.3K 🔥` `NEW`
1. [特朗普公开警告](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E5%85%AC%E5%BC%80%E8%AD%A6%E5%91%8A%23) `100.7K 🔥` `NEW`
1. [易烊千玺嗓子哑因过于疲惫 (Yi Yang Qianxi’s voice became hoarse due to exhaustion)](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%97%93%E5%AD%90%E5%93%91%E5%9B%A0%E8%BF%87%E4%BA%8E%E7%96%B2%E6%83%AB%23) `100.1K 🔥` `NEW`
1. [爸爸做山海经年夜饭女儿一口吃不下](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E5%81%9A%E5%B1%B1%E6%B5%B7%E7%BB%8F%E5%B9%B4%E5%A4%9C%E9%A5%AD%E5%A5%B3%E5%84%BF%E4%B8%80%E5%8F%A3%E5%90%83%E4%B8%8D%E4%B8%8B%23) `99.9K 🔥` `NEW`
1. [朕与吴京何时有过嫌隙](https://s.weibo.com/weibo?q=%23%E6%9C%95%E4%B8%8E%E5%90%B4%E4%BA%AC%E4%BD%95%E6%97%B6%E6%9C%89%E8%BF%87%E5%AB%8C%E9%9A%99%23) `99.2K 🔥` `NEW`
1. [杨幂 好有说服力的女特务](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%20%E5%A5%BD%E6%9C%89%E8%AF%B4%E6%9C%8D%E5%8A%9B%E7%9A%84%E5%A5%B3%E7%89%B9%E5%8A%A1%23) `98.4K 🔥` `NEW`
1. [看小说时莫名其妙的生理反应](https://s.weibo.com/weibo?q=%23%E7%9C%8B%E5%B0%8F%E8%AF%B4%E6%97%B6%E8%8E%AB%E5%90%8D%E5%85%B6%E5%A6%99%E7%9A%84%E7%94%9F%E7%90%86%E5%8F%8D%E5%BA%94%23) `97.7K 🔥` `NEW`
1. [刘诗诗回应每场戏都在流泪](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%AF%97%E8%AF%97%E5%9B%9E%E5%BA%94%E6%AF%8F%E5%9C%BA%E6%88%8F%E9%83%BD%E5%9C%A8%E6%B5%81%E6%B3%AA%23) `97.6K 🔥` `NEW`
1. [有王安宇这样的老公你几点回家](https://s.weibo.com/weibo?q=%23%E6%9C%89%E7%8E%8B%E5%AE%89%E5%AE%87%E8%BF%99%E6%A0%B7%E7%9A%84%E8%80%81%E5%85%AC%E4%BD%A0%E5%87%A0%E7%82%B9%E5%9B%9E%E5%AE%B6%23) `96.8K 🔥` `NEW`
1. [25岁女生在景区扮财神爷走红](https://s.weibo.com/weibo?q=%2325%E5%B2%81%E5%A5%B3%E7%94%9F%E5%9C%A8%E6%99%AF%E5%8C%BA%E6%89%AE%E8%B4%A2%E7%A5%9E%E7%88%B7%E8%B5%B0%E7%BA%A2%23) `91.0K 🔥` `NEW`
1. [曝男艺人商业变现能力更强](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%94%B7%E8%89%BA%E4%BA%BA%E5%95%86%E4%B8%9A%E5%8F%98%E7%8E%B0%E8%83%BD%E5%8A%9B%E6%9B%B4%E5%BC%BA%23) `83.4K 🔥` `NEW`
1. [大扫除最忙的是小猫咪](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E6%89%AB%E9%99%A4%E6%9C%80%E5%BF%99%E7%9A%84%E6%98%AF%E5%B0%8F%E7%8C%AB%E5%92%AA%23) `72.9K 🔥` `NEW`
1. [诗幂 (poetry power)](https://s.weibo.com/weibo?q=%23%E8%AF%97%E5%B9%82%23) `1.1M 🔥` `+470%`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `235.1K 🔥` `+21%`
1. [时代峰峻高会崩了](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E9%AB%98%E4%BC%9A%E5%B4%A9%E4%BA%86%23) `150.2K 🔥` `+123%`
1. [短道速滑局面像8年前平昌](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E5%B1%80%E9%9D%A2%E5%83%8F8%E5%B9%B4%E5%89%8D%E5%B9%B3%E6%98%8C%23) `105.2K 🔥` `+51%`
1. [成何体统](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%23) `95.3K 🔥` `+26%`
1. [孩子存1000比你存20万利息高 (If your child saves 1,000, the interest will be higher than if you save 200,000.)](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E5%AD%981000%E6%AF%94%E4%BD%A0%E5%AD%9820%E4%B8%87%E5%88%A9%E6%81%AF%E9%AB%98%23) `786.2K 🔥`
1. [大年初二回门日](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%8C%E5%9B%9E%E9%97%A8%E6%97%A5%23) `636.0K 🔥`
1. [龙洋主持完春晚哭了 (Long Yang cried after hosting the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E9%BE%99%E6%B4%8B%E4%B8%BB%E6%8C%81%E5%AE%8C%E6%98%A5%E6%99%9A%E5%93%AD%E4%BA%86%23) `436.7K 🔥`
1. [刘诗诗给杨幂拿话筒](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%AF%97%E8%AF%97%E7%BB%99%E6%9D%A8%E5%B9%82%E6%8B%BF%E8%AF%9D%E7%AD%92%23) `207.1K 🔥`
1. [过年不要一直穿睡衣](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E4%B8%8D%E8%A6%81%E4%B8%80%E7%9B%B4%E7%A9%BF%E7%9D%A1%E8%A1%A3%23) `195.5K 🔥`
1. [大年初二不午睡](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%8C%E4%B8%8D%E5%8D%88%E7%9D%A1%23) `162.8K 🔥`
1. [林孝埈刘少昂决赛前瞻](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E5%88%98%E5%B0%91%E6%98%82%E5%86%B3%E8%B5%9B%E5%89%8D%E7%9E%BB%23) `95.4K 🔥`
1. [妈妈炸丸子翻车立刻去姥姥家求助 (Mom's croquettes overturned and she immediately went to her grandma's house for help.)](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E7%82%B8%E4%B8%B8%E5%AD%90%E7%BF%BB%E8%BD%A6%E7%AB%8B%E5%88%BB%E5%8E%BB%E5%A7%A5%E5%A7%A5%E5%AE%B6%E6%B1%82%E5%8A%A9%23) `74.0K 🔥`
1. [高市早苗再当选日本首相 (Sanae Takaichi re-elected as Prime Minister of Japan)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%86%8D%E5%BD%93%E9%80%89%E6%97%A5%E6%9C%AC%E9%A6%96%E7%9B%B8%23) `524.0K 🔥` `-56%`
1. [飞驰人生3票房或超50亿 (The box office of Flying Life 3 may exceed 5 billion)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E7%A5%A8%E6%88%BF%E6%88%96%E8%B6%8550%E4%BA%BF%23) `156.6K 🔥` `-22%`
1. [听说全国女婿到丈母娘家都这样 (I heard that this happens all over the country when a son-in-law goes to his mother-in-law’s house.)](https://s.weibo.com/weibo?q=%23%E5%90%AC%E8%AF%B4%E5%85%A8%E5%9B%BD%E5%A5%B3%E5%A9%BF%E5%88%B0%E4%B8%88%E6%AF%8D%E5%A8%98%E5%AE%B6%E9%83%BD%E8%BF%99%E6%A0%B7%23) `128.8K 🔥` `-32%`
1. [马凡舒回应春晚发型争议 (Ma Fanshu responds to Spring Festival Gala hairstyle controversy)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%87%A1%E8%88%92%E5%9B%9E%E5%BA%94%E6%98%A5%E6%99%9A%E5%8F%91%E5%9E%8B%E4%BA%89%E8%AE%AE%23) `119.5K 🔥` `-39%`
1. [谷爱凌 顶级alpha](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%20%E9%A1%B6%E7%BA%A7alpha%23) `105.3K 🔥` `-46%`
1. [宋小宝 掉微博热搜池里了救救我](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%B0%8F%E5%AE%9D%20%E6%8E%89%E5%BE%AE%E5%8D%9A%E7%83%AD%E6%90%9C%E6%B1%A0%E9%87%8C%E4%BA%86%E6%95%91%E6%95%91%E6%88%91%23) `104.9K 🔥` `-48%`
1. [在宁波马力全开过大年](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%AE%81%E6%B3%A2%E9%A9%AC%E5%8A%9B%E5%85%A8%E5%BC%80%E8%BF%87%E5%A4%A7%E5%B9%B4%23) `104.6K 🔥` `-44%`
1. [娜然与霍家父子同游意大利 (Naran traveled to Italy with the Huo family and his son)](https://s.weibo.com/weibo?q=%23%E5%A8%9C%E7%84%B6%E4%B8%8E%E9%9C%8D%E5%AE%B6%E7%88%B6%E5%AD%90%E5%90%8C%E6%B8%B8%E6%84%8F%E5%A4%A7%E5%88%A9%23) `104.2K 🔥` `-40%`
1. [豆包打麻将](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E6%89%93%E9%BA%BB%E5%B0%86%23) `103.4K 🔥` `-47%`
1. [今年过年没人催婚了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E8%BF%87%E5%B9%B4%E6%B2%A1%E4%BA%BA%E5%82%AC%E5%A9%9A%E4%BA%86%23) `102.3K 🔥` `-40%`
1. [惊蛰无声豆瓣开分6.3](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%E8%B1%86%E7%93%A3%E5%BC%80%E5%88%866.3%23) `101.9K 🔥` `-57%`
1. [月嫂回应为入狱雇主无偿带娃](https://s.weibo.com/weibo?q=%23%E6%9C%88%E5%AB%82%E5%9B%9E%E5%BA%94%E4%B8%BA%E5%85%A5%E7%8B%B1%E9%9B%87%E4%B8%BB%E6%97%A0%E5%81%BF%E5%B8%A6%E5%A8%83%23) `101.4K 🔥` `-39%`
1. [电影星河入梦](https://s.weibo.com/weibo?q=%23%E7%94%B5%E5%BD%B1%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%23) `101.1K 🔥` `-31%`
1. [成何体统大结局](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%E5%A4%A7%E7%BB%93%E5%B1%80%23) `100.5K 🔥` `-39%`
1. [女生半年卖出800多只点翠大蟑螂 (A girl sold more than 800 large cockroaches in half a year)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E5%8D%8A%E5%B9%B4%E5%8D%96%E5%87%BA800%E5%A4%9A%E5%8F%AA%E7%82%B9%E7%BF%A0%E5%A4%A7%E8%9F%91%E8%9E%82%23) `99.4K 🔥` `-48%`
1. [刘宇宁说大家进了春晚休息间鸦雀无声](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E8%AF%B4%E5%A4%A7%E5%AE%B6%E8%BF%9B%E4%BA%86%E6%98%A5%E6%99%9A%E4%BC%91%E6%81%AF%E9%97%B4%E9%B8%A6%E9%9B%80%E6%97%A0%E5%A3%B0%23) `91.9K 🔥` `-24%`
1. [刘浩存 你就是有天赋 (Liu Haocun, you just have talent)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%20%E4%BD%A0%E5%B0%B1%E6%98%AF%E6%9C%89%E5%A4%A9%E8%B5%8B%23) `90.7K 🔥` `-24%`
1. [你家姑爷今天贡献了什么名场面](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%AE%B6%E5%A7%91%E7%88%B7%E4%BB%8A%E5%A4%A9%E8%B4%A1%E7%8C%AE%E4%BA%86%E4%BB%80%E4%B9%88%E5%90%8D%E5%9C%BA%E9%9D%A2%23) `73.0K 🔥` `-39%`

Updated at 2026-02-18 16:05:21

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
