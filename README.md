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

1. [王楚钦鹰眼挑战失败 (Wang Chuqin’s Eagle Eye challenge failed)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E9%B9%B0%E7%9C%BC%E6%8C%91%E6%88%98%E5%A4%B1%E8%B4%A5%23) `770.1K 🔥` `NEW`
1. [IVL开年欧气抽卡必中](https://s.weibo.com/weibo?q=%23IVL%E5%BC%80%E5%B9%B4%E6%AC%A7%E6%B0%94%E6%8A%BD%E5%8D%A1%E5%BF%85%E4%B8%AD%23) `461.4K 🔥` `NEW`
1. [杨幂演历史剧](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%BC%94%E5%8E%86%E5%8F%B2%E5%89%A7%23) `208.9K 🔥` `NEW`
1. [不让江山作者取关剧组](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E4%BD%9C%E8%80%85%E5%8F%96%E5%85%B3%E5%89%A7%E7%BB%84%23) `207.6K 🔥` `NEW`
1. [林枫松陈稳直播](https://s.weibo.com/weibo?q=%23%E6%9E%97%E6%9E%AB%E6%9D%BE%E9%99%88%E7%A8%B3%E7%9B%B4%E6%92%AD%23) `192.4K 🔥` `NEW`
1. [平台回应夫妻春节送外卖1个月赚4万](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E5%8F%B0%E5%9B%9E%E5%BA%94%E5%A4%AB%E5%A6%BB%E6%98%A5%E8%8A%82%E9%80%81%E5%A4%96%E5%8D%961%E4%B8%AA%E6%9C%88%E8%B5%9A4%E4%B8%87%23) `143.3K 🔥` `NEW`
1. [王心迪徐梦桃恋爱过程](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%BF%83%E8%BF%AA%E5%BE%90%E6%A2%A6%E6%A1%83%E6%81%8B%E7%88%B1%E8%BF%87%E7%A8%8B%23) `114.7K 🔥` `NEW`
1. [谷爱凌妈妈谷燕的人生轨迹](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A6%88%E5%A6%88%E8%B0%B7%E7%87%95%E7%9A%84%E4%BA%BA%E7%94%9F%E8%BD%A8%E8%BF%B9%23) `93.4K 🔥` `NEW`
1. [不内耗的人脑子里是这样想的](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%86%85%E8%80%97%E7%9A%84%E4%BA%BA%E8%84%91%E5%AD%90%E9%87%8C%E6%98%AF%E8%BF%99%E6%A0%B7%E6%83%B3%E7%9A%84%23) `91.6K 🔥` `NEW`
1. [将门独后](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `91.0K 🔥` `NEW`
1. [陈飞宇演技 (Chen Feiyu's acting skills)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E6%BC%94%E6%8A%80%23) `86.1K 🔥` `NEW`
1. [李方慧说谷爱凌太强了](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%96%B9%E6%85%A7%E8%AF%B4%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A4%AA%E5%BC%BA%E4%BA%86%23) `76.3K 🔥` `NEW`
1. [春节互联网公司烧钱80亿发红包](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E4%BA%92%E8%81%94%E7%BD%91%E5%85%AC%E5%8F%B8%E7%83%A7%E9%92%B180%E4%BA%BF%E5%8F%91%E7%BA%A2%E5%8C%85%23) `75.0K 🔥` `NEW`
1. [韩国新冠疫苗被爆含真菌毛发](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E6%96%B0%E5%86%A0%E7%96%AB%E8%8B%97%E8%A2%AB%E7%88%86%E5%90%AB%E7%9C%9F%E8%8F%8C%E6%AF%9B%E5%8F%91%23) `73.2K 🔥` `NEW`
1. [瑶一瑶小肉包近30天掉粉4万](https://s.weibo.com/weibo?q=%23%E7%91%B6%E4%B8%80%E7%91%B6%E5%B0%8F%E8%82%89%E5%8C%85%E8%BF%9130%E5%A4%A9%E6%8E%89%E7%B2%894%E4%B8%87%23) `69.7K 🔥` `NEW`
1. [牛奶灌溉草莓卖出360元天价](https://s.weibo.com/weibo?q=%23%E7%89%9B%E5%A5%B6%E7%81%8C%E6%BA%89%E8%8D%89%E8%8E%93%E5%8D%96%E5%87%BA360%E5%85%83%E5%A4%A9%E4%BB%B7%23) `68.9K 🔥` `NEW`
1. [西安一市民除夕夜被AI给骂了](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%AE%89%E4%B8%80%E5%B8%82%E6%B0%91%E9%99%A4%E5%A4%95%E5%A4%9C%E8%A2%ABAI%E7%BB%99%E9%AA%82%E4%BA%86%23) `66.5K 🔥` `NEW`
1. [地球超新鲜2](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E7%90%83%E8%B6%85%E6%96%B0%E9%B2%9C2%23) `1.1M 🔥` `+333%`
1. [高速堵车大哥在路边架锅卖炒粉](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%A0%B5%E8%BD%A6%E5%A4%A7%E5%93%A5%E5%9C%A8%E8%B7%AF%E8%BE%B9%E6%9E%B6%E9%94%85%E5%8D%96%E7%82%92%E7%B2%89%23) `353.6K 🔥` `+78%`
1. [丁程鑫生日星愿约定](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E7%94%9F%E6%97%A5%E6%98%9F%E6%84%BF%E7%BA%A6%E5%AE%9A%23) `259.5K 🔥` `+35%`
1. [江西一家人自驾返程出车祸1死4伤 (A family in Jiangxi was involved in a car accident while driving back home, killing 1 and injuring 4)](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E8%A5%BF%E4%B8%80%E5%AE%B6%E4%BA%BA%E8%87%AA%E9%A9%BE%E8%BF%94%E7%A8%8B%E5%87%BA%E8%BD%A6%E7%A5%B81%E6%AD%BB4%E4%BC%A4%23) `207.3K 🔥` `+113%`
1. [女儿照顾大小便失禁的妈妈整整三年](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%84%BF%E7%85%A7%E9%A1%BE%E5%A4%A7%E5%B0%8F%E4%BE%BF%E5%A4%B1%E7%A6%81%E7%9A%84%E5%A6%88%E5%A6%88%E6%95%B4%E6%95%B4%E4%B8%89%E5%B9%B4%23) `151.8K 🔥` `+26%`
1. [经常熬夜是在挑战甲状腺极限](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E5%B8%B8%E7%86%AC%E5%A4%9C%E6%98%AF%E5%9C%A8%E6%8C%91%E6%88%98%E7%94%B2%E7%8A%B6%E8%85%BA%E6%9E%81%E9%99%90%23) `126.9K 🔥` `+34%`
1. [2026年新春走基层 (Go to the grassroots level in the New Year of 2026)](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E6%96%B0%E6%98%A5%E8%B5%B0%E5%9F%BA%E5%B1%82%23) `630.1K 🔥`
1. [剑来 魔改 (Jian Lai Mo Gai)](https://s.weibo.com/weibo?q=%23%E5%89%91%E6%9D%A5%20%E9%AD%94%E6%94%B9%23) `308.7K 🔥`
1. [正月剃头死舅舅的真相来了](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E6%9C%88%E5%89%83%E5%A4%B4%E6%AD%BB%E8%88%85%E8%88%85%E7%9A%84%E7%9C%9F%E7%9B%B8%E6%9D%A5%E4%BA%86%23) `209.5K 🔥`
1. [开工第一天被通知放假10天 (On the first day of work, I was informed of a 10-day holiday.)](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%E8%A2%AB%E9%80%9A%E7%9F%A5%E6%94%BE%E5%81%8710%E5%A4%A9%23) `209.1K 🔥`
1. [吴昕自曝录制快本三四个月还是想走](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%87%AA%E6%9B%9D%E5%BD%95%E5%88%B6%E5%BF%AB%E6%9C%AC%E4%B8%89%E5%9B%9B%E4%B8%AA%E6%9C%88%E8%BF%98%E6%98%AF%E6%83%B3%E8%B5%B0%23) `208.6K 🔥`
1. [被炸身亡男子从哪里买的烟花](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%82%B8%E8%BA%AB%E4%BA%A1%E7%94%B7%E5%AD%90%E4%BB%8E%E5%93%AA%E9%87%8C%E4%B9%B0%E7%9A%84%E7%83%9F%E8%8A%B1%23) `208.2K 🔥`
1. [丁程鑫直播](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E7%9B%B4%E6%92%AD%23) `204.6K 🔥`
1. [93岁老人去世将千万财产赠邻居](https://s.weibo.com/weibo?q=%2393%E5%B2%81%E8%80%81%E4%BA%BA%E5%8E%BB%E4%B8%96%E5%B0%86%E5%8D%83%E4%B8%87%E8%B4%A2%E4%BA%A7%E8%B5%A0%E9%82%BB%E5%B1%85%23) `194.3K 🔥`
1. [刘强东宣布进军游艇行业 (Liu Qiangdong announces his entry into the yacht industry)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BC%BA%E4%B8%9C%E5%AE%A3%E5%B8%83%E8%BF%9B%E5%86%9B%E6%B8%B8%E8%89%87%E8%A1%8C%E4%B8%9A%23) `180.7K 🔥`
1. [俄乌冲突](https://s.weibo.com/weibo?q=%23%E4%BF%84%E4%B9%8C%E5%86%B2%E7%AA%81%23) `160.6K 🔥`
1. [杨洋的不让江山妆造](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E7%9A%84%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%A6%86%E9%80%A0%23) `156.0K 🔥`
1. [张元英ins更新 (Zhang Yuanying ins update)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%85%83%E8%8B%B1ins%E6%9B%B4%E6%96%B0%23) `108.4K 🔥`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `97.2K 🔥`
1. [墨西哥毒枭残忍罪行被曝光 (Brutal crimes of Mexican drug lords exposed)](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A5%E6%AF%92%E6%9E%AD%E6%AE%8B%E5%BF%8D%E7%BD%AA%E8%A1%8C%E8%A2%AB%E6%9B%9D%E5%85%89%23) `74.9K 🔥`
1. [Prada出发图](https://s.weibo.com/weibo?q=%23Prada%E5%87%BA%E5%8F%91%E5%9B%BE%23) `343.1K 🔥` `-41%`
1. [谷爱凌U槽卫冕英媒质疑打分](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E6%A7%BD%E5%8D%AB%E5%86%95%E8%8B%B1%E5%AA%92%E8%B4%A8%E7%96%91%E6%89%93%E5%88%86%23) `252.2K 🔥` `-68%`
1. [纯真年代的爱情 男二女二戏份](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%20%E7%94%B7%E4%BA%8C%E5%A5%B3%E4%BA%8C%E6%88%8F%E4%BB%BD%23) `131.6K 🔥` `-52%`
1. [小车23点59分59秒下高速收费员狂喜 (The car got off the expressway at 23:59:59 and the toll collector was ecstatic)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E8%BD%A623%E7%82%B959%E5%88%8659%E7%A7%92%E4%B8%8B%E9%AB%98%E9%80%9F%E6%94%B6%E8%B4%B9%E5%91%98%E7%8B%82%E5%96%9C%23) `97.3K 🔥` `-22%`
1. [丁程鑫不叫兄弟叫宝贝](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E4%B8%8D%E5%8F%AB%E5%85%84%E5%BC%9F%E5%8F%AB%E5%AE%9D%E8%B4%9D%23) `93.6K 🔥` `-33%`
1. [白鹿宋雨琦背后抱](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%AE%8B%E9%9B%A8%E7%90%A6%E8%83%8C%E5%90%8E%E6%8A%B1%23) `93.1K 🔥` `-38%`
1. [穆祉丞发的是什么](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%E5%8F%91%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%23) `89.5K 🔥` `-46%`
1. [宇树发布四足机器人As2](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E5%8F%91%E5%B8%83%E5%9B%9B%E8%B6%B3%E6%9C%BA%E5%99%A8%E4%BA%BAAs2%23) `86.4K 🔥` `-43%`
1. [苏翊鸣居然演过韩庚爷爷](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%B1%85%E7%84%B6%E6%BC%94%E8%BF%87%E9%9F%A9%E5%BA%9A%E7%88%B7%E7%88%B7%23) `84.6K 🔥` `-49%`
1. [镖人电影宇宙来了 (The Daredevil Cinematic Universe is coming)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%94%B5%E5%BD%B1%E5%AE%87%E5%AE%99%E6%9D%A5%E4%BA%86%23) `75.0K 🔥` `-35%`
1. [中方回应特朗普3月31日将访问中国](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE3%E6%9C%8831%E6%97%A5%E5%B0%86%E8%AE%BF%E9%97%AE%E4%B8%AD%E5%9B%BD%23) `67.6K 🔥` `-45%`
1. [男子误喝过期牛奶暴瘦53斤 (Man lost 53 pounds by accidentally drinking expired milk)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%AF%AF%E5%96%9D%E8%BF%87%E6%9C%9F%E7%89%9B%E5%A5%B6%E6%9A%B4%E7%98%A653%E6%96%A4%23) `67.3K 🔥` `-57%`
1. [史上最高分小品少爷和我 (The highest-scoring skit in history: The Young Master and Me)](https://s.weibo.com/weibo?q=%23%E5%8F%B2%E4%B8%8A%E6%9C%80%E9%AB%98%E5%88%86%E5%B0%8F%E5%93%81%E5%B0%91%E7%88%B7%E5%92%8C%E6%88%91%23) `66.5K 🔥` `-46%`

Updated at 2026-02-24 23:46:47

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
