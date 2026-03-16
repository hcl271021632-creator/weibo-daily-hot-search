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

1. [胖东来 打假人 (Fat Donglai fights the fake people)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%20%E6%89%93%E5%81%87%E4%BA%BA%23) `1.1M 🔥` `NEW`
1. [一男女在公众场合实施不雅行为被抓](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%94%B7%E5%A5%B3%E5%9C%A8%E5%85%AC%E4%BC%97%E5%9C%BA%E5%90%88%E5%AE%9E%E6%96%BD%E4%B8%8D%E9%9B%85%E8%A1%8C%E4%B8%BA%E8%A2%AB%E6%8A%93%23) `642.5K 🔥` `NEW`
1. [张凌赫 导演你管管她](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E5%AF%BC%E6%BC%94%E4%BD%A0%E7%AE%A1%E7%AE%A1%E5%A5%B9%23) `642.0K 🔥` `NEW`
1. [42岁女子从不抽烟确诊肺癌晚期](https://s.weibo.com/weibo?q=%2342%E5%B2%81%E5%A5%B3%E5%AD%90%E4%BB%8E%E4%B8%8D%E6%8A%BD%E7%83%9F%E7%A1%AE%E8%AF%8A%E8%82%BA%E7%99%8C%E6%99%9A%E6%9C%9F%23) `627.4K 🔥` `NEW`
1. [因为瞿颖盒马的菠菜都标上英文了](https://s.weibo.com/weibo?q=%23%E5%9B%A0%E4%B8%BA%E7%9E%BF%E9%A2%96%E7%9B%92%E9%A9%AC%E7%9A%84%E8%8F%A0%E8%8F%9C%E9%83%BD%E6%A0%87%E4%B8%8A%E8%8B%B1%E6%96%87%E4%BA%86%23) `333.7K 🔥` `NEW`
1. [18岁女孩腹中肿块里还有24颗牙齿](https://s.weibo.com/weibo?q=%2318%E5%B2%81%E5%A5%B3%E5%AD%A9%E8%85%B9%E4%B8%AD%E8%82%BF%E5%9D%97%E9%87%8C%E8%BF%98%E6%9C%8924%E9%A2%97%E7%89%99%E9%BD%BF%23) `313.1K 🔥` `NEW`
1. [瞿颖好大的雨啊](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E5%A5%BD%E5%A4%A7%E7%9A%84%E9%9B%A8%E5%95%8A%23) `190.4K 🔥` `NEW`
1. [20城都在追的春日减重新姿势](https://s.weibo.com/weibo?q=%2320%E5%9F%8E%E9%83%BD%E5%9C%A8%E8%BF%BD%E7%9A%84%E6%98%A5%E6%97%A5%E5%87%8F%E9%87%8D%E6%96%B0%E5%A7%BF%E5%8A%BF%23) `176.8K 🔥` `NEW`
1. [伊朗成功执行第55轮打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%88%90%E5%8A%9F%E6%89%A7%E8%A1%8C%E7%AC%AC55%E8%BD%AE%E6%89%93%E5%87%BB%23) `168.8K 🔥` `NEW`
1. [长沙警方通报一起寻衅滋事案](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%B2%99%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E4%B8%80%E8%B5%B7%E5%AF%BB%E8%A1%85%E6%BB%8B%E4%BA%8B%E6%A1%88%23) `121.0K 🔥` `NEW`
1. [伊朗称逮捕500名间谍 (Iran says it has arrested 500 spies)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E9%80%AE%E6%8D%95500%E5%90%8D%E9%97%B4%E8%B0%8D%23) `108.1K 🔥` `NEW`
1. [极氪8X售价](https://s.weibo.com/weibo?q=%23%E6%9E%81%E6%B0%AA8X%E5%94%AE%E4%BB%B7%23) `105.0K 🔥` `NEW`
1. [吴敬平回应樊振东转会](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%95%AC%E5%B9%B3%E5%9B%9E%E5%BA%94%E6%A8%8A%E6%8C%AF%E4%B8%9C%E8%BD%AC%E4%BC%9A%23) `98.7K 🔥` `NEW`
1. [中国援助伊朗人道主义物资完成交接](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%8F%B4%E5%8A%A9%E4%BC%8A%E6%9C%97%E4%BA%BA%E9%81%93%E4%B8%BB%E4%B9%89%E7%89%A9%E8%B5%84%E5%AE%8C%E6%88%90%E4%BA%A4%E6%8E%A5%23) `93.3K 🔥` `NEW`
1. [女子买12克乐事薯片打开仅一片](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%B012%E5%85%8B%E4%B9%90%E4%BA%8B%E8%96%AF%E7%89%87%E6%89%93%E5%BC%80%E4%BB%85%E4%B8%80%E7%89%87%23) `90.0K 🔥` `NEW`
1. [21万买新车提车一个月锈迹斑斑](https://s.weibo.com/weibo?q=%2321%E4%B8%87%E4%B9%B0%E6%96%B0%E8%BD%A6%E6%8F%90%E8%BD%A6%E4%B8%80%E4%B8%AA%E6%9C%88%E9%94%88%E8%BF%B9%E6%96%91%E6%96%91%23) `82.7K 🔥` `NEW`
1. [2岁娃被忘车内反锁1小时](https://s.weibo.com/weibo?q=%232%E5%B2%81%E5%A8%83%E8%A2%AB%E5%BF%98%E8%BD%A6%E5%86%85%E5%8F%8D%E9%94%811%E5%B0%8F%E6%97%B6%23) `81.6K 🔥` `NEW`
1. [重庆万州马拉松冠军冲线被拦截](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E4%B8%87%E5%B7%9E%E9%A9%AC%E6%8B%89%E6%9D%BE%E5%86%A0%E5%86%9B%E5%86%B2%E7%BA%BF%E8%A2%AB%E6%8B%A6%E6%88%AA%23) `79.5K 🔥` `NEW`
1. [夏以昼 新日卡](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E4%BB%A5%E6%98%BC%20%E6%96%B0%E6%97%A5%E5%8D%A1%23) `78.3K 🔥` `NEW`
1. [AirPodsMax2发布](https://s.weibo.com/weibo?q=%23AirPodsMax2%E5%8F%91%E5%B8%83%23) `77.7K 🔥` `NEW`
1. [瑞幸的钱被外卖偷了 (Luckin’s money was stolen by takeaway)](https://s.weibo.com/weibo?q=%23%E7%91%9E%E5%B9%B8%E7%9A%84%E9%92%B1%E8%A2%AB%E5%A4%96%E5%8D%96%E5%81%B7%E4%BA%86%23) `75.9K 🔥` `NEW`
1. [KPL老乡杯](https://s.weibo.com/weibo?q=%23KPL%E8%80%81%E4%B9%A1%E6%9D%AF%23) `75.5K 🔥` `NEW`
1. [8年是二手新能源车流通斩杀线](https://s.weibo.com/weibo?q=%238%E5%B9%B4%E6%98%AF%E4%BA%8C%E6%89%8B%E6%96%B0%E8%83%BD%E6%BA%90%E8%BD%A6%E6%B5%81%E9%80%9A%E6%96%A9%E6%9D%80%E7%BA%BF%23) `74.9K 🔥` `NEW`
1. [爱吃薯片的人天塌了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E8%96%AF%E7%89%87%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `642.0K 🔥` `+135%`
1. [樊振东回应转会](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%9B%9E%E5%BA%94%E8%BD%AC%E4%BC%9A%23) `529.8K 🔥` `+96%`
1. [恋与深空 偷跑](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%20%E5%81%B7%E8%B7%91%23) `491.2K 🔥` `+439%`
1. [手机电脑迎来涨价潮](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E7%94%B5%E8%84%91%E8%BF%8E%E6%9D%A5%E6%B6%A8%E4%BB%B7%E6%BD%AE%23) `416.9K 🔥` `+151%`
1. [刚起床的素颜张柏芝](https://s.weibo.com/weibo?q=%23%E5%88%9A%E8%B5%B7%E5%BA%8A%E7%9A%84%E7%B4%A0%E9%A2%9C%E5%BC%A0%E6%9F%8F%E8%8A%9D%23) `302.3K 🔥` `+216%`
1. [孔雪儿伟大的爱豆时期](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E4%BC%9F%E5%A4%A7%E7%9A%84%E7%88%B1%E8%B1%86%E6%97%B6%E6%9C%9F%23) `189.3K 🔥` `+21%`
1. [事业单位招人岗位在海拔3614米山顶](https://s.weibo.com/weibo?q=%23%E4%BA%8B%E4%B8%9A%E5%8D%95%E4%BD%8D%E6%8B%9B%E4%BA%BA%E5%B2%97%E4%BD%8D%E5%9C%A8%E6%B5%B7%E6%8B%943614%E7%B1%B3%E5%B1%B1%E9%A1%B6%23) `801.4K 🔥`
1. [2026年以旧换新数据亮眼 (Trade-in data for 2026 is eye-catching)](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E4%BB%A5%E6%97%A7%E6%8D%A2%E6%96%B0%E6%95%B0%E6%8D%AE%E4%BA%AE%E7%9C%BC%23) `642.6K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `277.3K 🔥`
1. [女子借5万还不上履约做对方女友 (A woman borrowed 50,000 yuan but still failed to fulfill the contract to become his girlfriend)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%80%9F5%E4%B8%87%E8%BF%98%E4%B8%8D%E4%B8%8A%E5%B1%A5%E7%BA%A6%E5%81%9A%E5%AF%B9%E6%96%B9%E5%A5%B3%E5%8F%8B%23) `182.2K 🔥`
1. [周冬雨 刘昊然 (Zhou Dongyu Liu Haoran)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%AC%E9%9B%A8%20%E5%88%98%E6%98%8A%E7%84%B6%23) `175.2K 🔥`
1. [鹿晗 关晓彤](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `170.9K 🔥`
1. [孙燕姿胖了](https://s.weibo.com/weibo?q=%23%E5%AD%99%E7%87%95%E5%A7%BF%E8%83%96%E4%BA%86%23) `168.4K 🔥`
1. [黄亦玫你又去找庄国栋了吗](https://s.weibo.com/weibo?q=%23%E9%BB%84%E4%BA%A6%E7%8E%AB%E4%BD%A0%E5%8F%88%E5%8E%BB%E6%89%BE%E5%BA%84%E5%9B%BD%E6%A0%8B%E4%BA%86%E5%90%97%23) `87.2K 🔥`
1. [发现虾腿有肉以后](https://s.weibo.com/weibo?q=%23%E5%8F%91%E7%8E%B0%E8%99%BE%E8%85%BF%E6%9C%89%E8%82%89%E4%BB%A5%E5%90%8E%23) `190.7K 🔥` `-30%`
1. [315塌房全总结](https://s.weibo.com/weibo?q=%23315%E5%A1%8C%E6%88%BF%E5%85%A8%E6%80%BB%E7%BB%93%23) `177.5K 🔥` `-34%`
1. [张凌赫田曦薇浴池戏](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%B5%B4%E6%B1%A0%E6%88%8F%23) `132.9K 🔥` `-23%`
1. [樊振东下赛季加盟杜塞尔多夫 (Fan Zhendong joins Dusseldorf next season)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E4%B8%8B%E8%B5%9B%E5%AD%A3%E5%8A%A0%E7%9B%9F%E6%9D%9C%E5%A1%9E%E5%B0%94%E5%A4%9A%E5%A4%AB%23) `112.3K 🔥` `-89%`
1. [教体局通报女孩遭殴打不予立案原因](https://s.weibo.com/weibo?q=%23%E6%95%99%E4%BD%93%E5%B1%80%E9%80%9A%E6%8A%A5%E5%A5%B3%E5%AD%A9%E9%81%AD%E6%AE%B4%E6%89%93%E4%B8%8D%E4%BA%88%E7%AB%8B%E6%A1%88%E5%8E%9F%E5%9B%A0%23) `112.0K 🔥` `-58%`
1. [范丞丞开始减肥第一天 (Fan Chengcheng’s first day of losing weight)](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E5%BC%80%E5%A7%8B%E5%87%8F%E8%82%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%23) `110.0K 🔥` `-32%`
1. [长玉说和离 谢征吐血](https://s.weibo.com/weibo?q=%23%E9%95%BF%E7%8E%89%E8%AF%B4%E5%92%8C%E7%A6%BB%20%E8%B0%A2%E5%BE%81%E5%90%90%E8%A1%80%23) `106.5K 🔥` `-60%`
1. [李诞说现在失业的人可能是一件好事 (Li Dan said that people who are unemployed now may be a good thing)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%AF%9E%E8%AF%B4%E7%8E%B0%E5%9C%A8%E5%A4%B1%E4%B8%9A%E7%9A%84%E4%BA%BA%E5%8F%AF%E8%83%BD%E6%98%AF%E4%B8%80%E4%BB%B6%E5%A5%BD%E4%BA%8B%23) `85.1K 🔥` `-46%`
1. [26岁患癌女子冒生命危险坚持备孕 (26-year-old cancer-stricken woman risks her life to prepare for pregnancy)](https://s.weibo.com/weibo?q=%2326%E5%B2%81%E6%82%A3%E7%99%8C%E5%A5%B3%E5%AD%90%E5%86%92%E7%94%9F%E5%91%BD%E5%8D%B1%E9%99%A9%E5%9D%9A%E6%8C%81%E5%A4%87%E5%AD%95%23) `83.4K 🔥` `-47%`
1. [王一栩 虞书欣演过最好的都是我给的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E6%A0%A9%20%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%BC%94%E8%BF%87%E6%9C%80%E5%A5%BD%E7%9A%84%E9%83%BD%E6%98%AF%E6%88%91%E7%BB%99%E7%9A%84%23) `80.6K 🔥` `-49%`
1. [鸿蒙智行 小米](https://s.weibo.com/weibo?q=%23%E9%B8%BF%E8%92%99%E6%99%BA%E8%A1%8C%20%E5%B0%8F%E7%B1%B3%23) `75.3K 🔥` `-72%`
1. [中方回应特朗普呼吁多国派军舰护航](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E5%91%BC%E5%90%81%E5%A4%9A%E5%9B%BD%E6%B4%BE%E5%86%9B%E8%88%B0%E6%8A%A4%E8%88%AA%23) `72.6K 🔥` `-58%`
1. [李门槛 齐本宫](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%97%A8%E6%A7%9B%20%E9%BD%90%E6%9C%AC%E5%AE%AB%23) `72.5K 🔥` `-22%`

Updated at 2026-03-16 21:48:36

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
