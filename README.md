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

1. [2026年新春走基层 (Go to the grassroots level in the New Year of 2026)](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E6%96%B0%E6%98%A5%E8%B5%B0%E5%9F%BA%E5%B1%82%23) `620.7K 🔥` `NEW`
1. [Prada出发图](https://s.weibo.com/weibo?q=%23Prada%E5%87%BA%E5%8F%91%E5%9B%BE%23) `617.2K 🔥` `NEW`
1. [丁程鑫生日星愿约定](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E7%94%9F%E6%97%A5%E6%98%9F%E6%84%BF%E7%BA%A6%E5%AE%9A%23) `192.6K 🔥` `NEW`
1. [纯真年代的爱情 男二女二戏份](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%20%E7%94%B7%E4%BA%8C%E5%A5%B3%E4%BA%8C%E6%88%8F%E4%BB%BD%23) `164.2K 🔥` `NEW`
1. [谷爱凌U槽卫冕英媒质疑打分](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E6%A7%BD%E5%8D%AB%E5%86%95%E8%8B%B1%E5%AA%92%E8%B4%A8%E7%96%91%E6%89%93%E5%88%86%23) `159.4K 🔥` `NEW`
1. [吴昕自曝录制快本三四个月还是想走](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%87%AA%E6%9B%9D%E5%BD%95%E5%88%B6%E5%BF%AB%E6%9C%AC%E4%B8%89%E5%9B%9B%E4%B8%AA%E6%9C%88%E8%BF%98%E6%98%AF%E6%83%B3%E8%B5%B0%23) `159.1K 🔥` `NEW`
1. [刘强东宣布进军游艇行业](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BC%BA%E4%B8%9C%E5%AE%A3%E5%B8%83%E8%BF%9B%E5%86%9B%E6%B8%B8%E8%89%87%E8%A1%8C%E4%B8%9A%23) `158.8K 🔥` `NEW`
1. [穆祉丞发的是什么](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%E5%8F%91%E7%9A%84%E6%98%AF%E4%BB%80%E4%B9%88%23) `158.1K 🔥` `NEW`
1. [独来独往的女人没有一个是孬种](https://s.weibo.com/weibo?q=%23%E7%8B%AC%E6%9D%A5%E7%8B%AC%E5%BE%80%E7%9A%84%E5%A5%B3%E4%BA%BA%E6%B2%A1%E6%9C%89%E4%B8%80%E4%B8%AA%E6%98%AF%E5%AD%AC%E7%A7%8D%23) `156.5K 🔥` `NEW`
1. [中国为何此时对日本军工亮剑](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%B8%BA%E4%BD%95%E6%AD%A4%E6%97%B6%E5%AF%B9%E6%97%A5%E6%9C%AC%E5%86%9B%E5%B7%A5%E4%BA%AE%E5%89%91%23) `155.6K 🔥` `NEW`
1. [李嘉格男友晒照 (Li Jiage's boyfriend posts photos)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%98%89%E6%A0%BC%E7%94%B7%E5%8F%8B%E6%99%92%E7%85%A7%23) `152.3K 🔥` `NEW`
1. [鞠婧祎跳了没有明天](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E8%B7%B3%E4%BA%86%E6%B2%A1%E6%9C%89%E6%98%8E%E5%A4%A9%23) `115.2K 🔥` `NEW`
1. [被炸身亡男子从哪里买的烟花](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%82%B8%E8%BA%AB%E4%BA%A1%E7%94%B7%E5%AD%90%E4%BB%8E%E5%93%AA%E9%87%8C%E4%B9%B0%E7%9A%84%E7%83%9F%E8%8A%B1%23) `111.3K 🔥` `NEW`
1. [章子怡 游过海岸一百米](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%20%E6%B8%B8%E8%BF%87%E6%B5%B7%E5%B2%B8%E4%B8%80%E7%99%BE%E7%B1%B3%23) `111.2K 🔥` `NEW`
1. [湖南元宵阵容夯爆了](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E5%85%83%E5%AE%B5%E9%98%B5%E5%AE%B9%E5%A4%AF%E7%88%86%E4%BA%86%23) `107.1K 🔥` `NEW`
1. [今晚夜空有个大写D](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E6%99%9A%E5%A4%9C%E7%A9%BA%E6%9C%89%E4%B8%AA%E5%A4%A7%E5%86%99D%23) `106.7K 🔥` `NEW`
1. [MOMO好辣](https://s.weibo.com/weibo?q=%23MOMO%E5%A5%BD%E8%BE%A3%23) `106.7K 🔥` `NEW`
1. [地球超新鲜2](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E7%90%83%E8%B6%85%E6%96%B0%E9%B2%9C2%23) `102.4K 🔥` `NEW`
1. [AL战胜WE](https://s.weibo.com/weibo?q=%23AL%E6%88%98%E8%83%9CWE%23) `100.9K 🔥` `NEW`
1. [全网最早预定羊年除夕宴的人出现](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BD%91%E6%9C%80%E6%97%A9%E9%A2%84%E5%AE%9A%E7%BE%8A%E5%B9%B4%E9%99%A4%E5%A4%95%E5%AE%B4%E7%9A%84%E4%BA%BA%E5%87%BA%E7%8E%B0%23) `99.5K 🔥` `NEW`
1. [万妮达过年胖了八斤多 (Wan Nida gained over eight pounds during the Chinese New Year)](https://s.weibo.com/weibo?q=%23%E4%B8%87%E5%A6%AE%E8%BE%BE%E8%BF%87%E5%B9%B4%E8%83%96%E4%BA%86%E5%85%AB%E6%96%A4%E5%A4%9A%23) `98.5K 🔥` `NEW`
1. [中方回应特朗普3月31日将访问中国](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE3%E6%9C%8831%E6%97%A5%E5%B0%86%E8%AE%BF%E9%97%AE%E4%B8%AD%E5%9B%BD%23) `84.0K 🔥` `NEW`
1. [王楚钦老把人往地上打](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%80%81%E6%8A%8A%E4%BA%BA%E5%BE%80%E5%9C%B0%E4%B8%8A%E6%89%93%23) `80.2K 🔥` `NEW`
1. [吴昕谈在快本时人气低](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%B0%88%E5%9C%A8%E5%BF%AB%E6%9C%AC%E6%97%B6%E4%BA%BA%E6%B0%94%E4%BD%8E%23) `75.4K 🔥` `NEW`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `73.2K 🔥` `NEW`
1. [情绪成熟的人通常有9个特点](https://s.weibo.com/weibo?q=%23%E6%83%85%E7%BB%AA%E6%88%90%E7%86%9F%E7%9A%84%E4%BA%BA%E9%80%9A%E5%B8%B8%E6%9C%899%E4%B8%AA%E7%89%B9%E7%82%B9%23) `72.3K 🔥` `NEW`
1. [AL对战WE](https://s.weibo.com/weibo?q=%23AL%E5%AF%B9%E6%88%98WE%23) `68.6K 🔥` `NEW`
1. [高速免费有司机超5秒付1384元](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%85%8D%E8%B4%B9%E6%9C%89%E5%8F%B8%E6%9C%BA%E8%B6%855%E7%A7%92%E4%BB%981384%E5%85%83%23) `68.4K 🔥` `NEW`
1. [多款相机价格暴涨近10倍](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%AC%BE%E7%9B%B8%E6%9C%BA%E4%BB%B7%E6%A0%BC%E6%9A%B4%E6%B6%A8%E8%BF%9110%E5%80%8D%23) `1.1M 🔥`
1. [正月剃头死舅舅的真相来了](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E6%9C%88%E5%89%83%E5%A4%B4%E6%AD%BB%E8%88%85%E8%88%85%E7%9A%84%E7%9C%9F%E7%9B%B8%E6%9D%A5%E4%BA%86%23) `783.7K 🔥`
1. [开工新头好全都上淘宝 (It’s a good idea to start a new business and go to Taobao)](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E6%96%B0%E5%A4%B4%E5%A5%BD%E5%85%A8%E9%83%BD%E4%B8%8A%E6%B7%98%E5%AE%9D%23) `619.6K 🔥`
1. [男子误喝过期牛奶暴瘦53斤 (Man lost 53 pounds by accidentally drinking expired milk)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%AF%AF%E5%96%9D%E8%BF%87%E6%9C%9F%E7%89%9B%E5%A5%B6%E6%9A%B4%E7%98%A653%E6%96%A4%23) `223.1K 🔥`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `205.0K 🔥`
1. [小车23点59分59秒下高速收费员狂喜 (The car got off the expressway at 23:59:59 and the toll collector was ecstatic)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E8%BD%A623%E7%82%B959%E5%88%8659%E7%A7%92%E4%B8%8B%E9%AB%98%E9%80%9F%E6%94%B6%E8%B4%B9%E5%91%98%E7%8B%82%E5%96%9C%23) `190.7K 🔥`
1. [开工第一天被通知放假10天](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%E8%A2%AB%E9%80%9A%E7%9F%A5%E6%94%BE%E5%81%8710%E5%A4%A9%23) `159.4K 🔥`
1. [苏翊鸣居然演过韩庚爷爷](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%B1%85%E7%84%B6%E6%BC%94%E8%BF%87%E9%9F%A9%E5%BA%9A%E7%88%B7%E7%88%B7%23) `158.3K 🔥`
1. [93岁老人去世将千万财产赠邻居](https://s.weibo.com/weibo?q=%2393%E5%B2%81%E8%80%81%E4%BA%BA%E5%8E%BB%E4%B8%96%E5%B0%86%E5%8D%83%E4%B8%87%E8%B4%A2%E4%BA%A7%E8%B5%A0%E9%82%BB%E5%B1%85%23) `157.7K 🔥`
1. [丁程鑫直播](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E7%9B%B4%E6%92%AD%23) `157.1K 🔥`
1. [俄乌冲突](https://s.weibo.com/weibo?q=%23%E4%BF%84%E4%B9%8C%E5%86%B2%E7%AA%81%23) `156.8K 🔥`
1. [白鹿宋雨琦背后抱](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%AE%8B%E9%9B%A8%E7%90%A6%E8%83%8C%E5%90%8E%E6%8A%B1%23) `156.0K 🔥`
1. [史上最高分小品少爷和我 (The highest-scoring skit in history: The Young Master and Me)](https://s.weibo.com/weibo?q=%23%E5%8F%B2%E4%B8%8A%E6%9C%80%E9%AB%98%E5%88%86%E5%B0%8F%E5%93%81%E5%B0%91%E7%88%B7%E5%92%8C%E6%88%91%23) `146.3K 🔥`
1. [瑶一瑶小肉包近30天掉粉4万](https://s.weibo.com/weibo?q=%23%E7%91%B6%E4%B8%80%E7%91%B6%E5%B0%8F%E8%82%89%E5%8C%85%E8%BF%9130%E5%A4%A9%E6%8E%89%E7%B2%894%E4%B8%87%23) `110.8K 🔥`
1. [新娘爸爸婚礼现场退还18.8万彩礼](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%A8%98%E7%88%B8%E7%88%B8%E5%A9%9A%E7%A4%BC%E7%8E%B0%E5%9C%BA%E9%80%80%E8%BF%9818.8%E4%B8%87%E5%BD%A9%E7%A4%BC%23) `109.4K 🔥`
1. [国投白银LOF自掏腰包补偿 (SDIC Silver LOF pays out of pocket for compensation)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E6%8A%95%E7%99%BD%E9%93%B6LOF%E8%87%AA%E6%8E%8F%E8%85%B0%E5%8C%85%E8%A1%A5%E5%81%BF%23) `71.4K 🔥`
1. [王楚钦vs户上隼辅 (Wang Chuqin vs Togami Hayabusa)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E6%88%B7%E4%B8%8A%E9%9A%BC%E8%BE%85%23) `155.4K 🔥` `-37%`
1. [墨西哥毒枭残忍罪行被曝光](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A5%E6%AF%92%E6%9E%AD%E6%AE%8B%E5%BF%8D%E7%BD%AA%E8%A1%8C%E8%A2%AB%E6%9B%9D%E5%85%89%23) `119.9K 🔥` `-41%`
1. [王楚然丞磊 京洛再无佳人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E4%B8%9E%E7%A3%8A%20%E4%BA%AC%E6%B4%9B%E5%86%8D%E6%97%A0%E4%BD%B3%E4%BA%BA%23) `116.0K 🔥` `-22%`
1. [Melody道歉](https://s.weibo.com/weibo?q=%23Melody%E9%81%93%E6%AD%89%23) `92.4K 🔥` `-40%`
1. [TF家族高会背景](https://s.weibo.com/weibo?q=%23TF%E5%AE%B6%E6%97%8F%E9%AB%98%E4%BC%9A%E8%83%8C%E6%99%AF%23) `81.5K 🔥` `-46%`
1. [衣服的成本价在水洗标上 (The cost price of the clothes is listed on the washing label)](https://s.weibo.com/weibo?q=%23%E8%A1%A3%E6%9C%8D%E7%9A%84%E6%88%90%E6%9C%AC%E4%BB%B7%E5%9C%A8%E6%B0%B4%E6%B4%97%E6%A0%87%E4%B8%8A%23) `73.0K 🔥` `-31%`
1. [程潇素颜皮肤状态](https://s.weibo.com/weibo?q=%23%E7%A8%8B%E6%BD%87%E7%B4%A0%E9%A2%9C%E7%9A%AE%E8%82%A4%E7%8A%B6%E6%80%81%23) `71.1K 🔥` `-23%`

Updated at 2026-02-24 21:55:08

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
