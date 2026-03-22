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

1. [爱吃荔枝的人今年天塌了 (People who love lychees are in trouble this year)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E8%8D%94%E6%9E%9D%E7%9A%84%E4%BA%BA%E4%BB%8A%E5%B9%B4%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `818.8K 🔥` `NEW`
1. [乘客去世英航班带着遗体飞完全程](https://s.weibo.com/weibo?q=%23%E4%B9%98%E5%AE%A2%E5%8E%BB%E4%B8%96%E8%8B%B1%E8%88%AA%E7%8F%AD%E5%B8%A6%E7%9D%80%E9%81%97%E4%BD%93%E9%A3%9E%E5%AE%8C%E5%85%A8%E7%A8%8B%23) `364.4K 🔥` `NEW`
1. [17岁女孩一睡10天被叫醒就打人](https://s.weibo.com/weibo?q=%2317%E5%B2%81%E5%A5%B3%E5%AD%A9%E4%B8%80%E7%9D%A110%E5%A4%A9%E8%A2%AB%E5%8F%AB%E9%86%92%E5%B0%B1%E6%89%93%E4%BA%BA%23) `347.9K 🔥` `NEW`
1. [爬山就得穿鲜艳的衣服](https://s.weibo.com/weibo?q=%23%E7%88%AC%E5%B1%B1%E5%B0%B1%E5%BE%97%E7%A9%BF%E9%B2%9C%E8%89%B3%E7%9A%84%E8%A1%A3%E6%9C%8D%23) `282.5K 🔥` `NEW`
1. [你好星期六下周嘉宾阵容预告](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD%E6%98%9F%E6%9C%9F%E5%85%AD%E4%B8%8B%E5%91%A8%E5%98%89%E5%AE%BE%E9%98%B5%E5%AE%B9%E9%A2%84%E5%91%8A%23) `162.5K 🔥` `NEW`
1. [油价飙升加油站变大型停车场](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E9%A3%99%E5%8D%87%E5%8A%A0%E6%B2%B9%E7%AB%99%E5%8F%98%E5%A4%A7%E5%9E%8B%E5%81%9C%E8%BD%A6%E5%9C%BA%23) `147.4K 🔥` `NEW`
1. [油价](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%23) `142.8K 🔥` `NEW`
1. [女生遭民警猥亵父亲刚开始以为是胡说](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E9%81%AD%E6%B0%91%E8%AD%A6%E7%8C%A5%E4%BA%B5%E7%88%B6%E4%BA%B2%E5%88%9A%E5%BC%80%E5%A7%8B%E4%BB%A5%E4%B8%BA%E6%98%AF%E8%83%A1%E8%AF%B4%23) `129.7K 🔥` `NEW`
1. [F35被击中关键原因是异常低空飞行](https://s.weibo.com/weibo?q=%23F35%E8%A2%AB%E5%87%BB%E4%B8%AD%E5%85%B3%E9%94%AE%E5%8E%9F%E5%9B%A0%E6%98%AF%E5%BC%82%E5%B8%B8%E4%BD%8E%E7%A9%BA%E9%A3%9E%E8%A1%8C%23) `113.8K 🔥` `NEW`
1. [专家称梅姨可能觉得自己在做善事](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E7%A7%B0%E6%A2%85%E5%A7%A8%E5%8F%AF%E8%83%BD%E8%A7%89%E5%BE%97%E8%87%AA%E5%B7%B1%E5%9C%A8%E5%81%9A%E5%96%84%E4%BA%8B%23) `113.0K 🔥` `NEW`
1. [孙颖莎不信邪喊再来一次 (Sun Yingsha didn’t believe it and shouted to do it again)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E4%B8%8D%E4%BF%A1%E9%82%AA%E5%96%8A%E5%86%8D%E6%9D%A5%E4%B8%80%E6%AC%A1%23) `103.9K 🔥` `NEW`
1. [张凌赫演技 颜值外的破局](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%BC%94%E6%8A%80%20%E9%A2%9C%E5%80%BC%E5%A4%96%E7%9A%84%E7%A0%B4%E5%B1%80%23) `99.2K 🔥` `NEW`
1. [本轮金价暴跌原因](https://s.weibo.com/weibo?q=%23%E6%9C%AC%E8%BD%AE%E9%87%91%E4%BB%B7%E6%9A%B4%E8%B7%8C%E5%8E%9F%E5%9B%A0%23) `97.5K 🔥` `NEW`
1. [羽毛球降价原因找到了](https://s.weibo.com/weibo?q=%23%E7%BE%BD%E6%AF%9B%E7%90%83%E9%99%8D%E4%BB%B7%E5%8E%9F%E5%9B%A0%E6%89%BE%E5%88%B0%E4%BA%86%23) `88.5K 🔥` `NEW`
1. [机场怎么不开个洗头发的店](https://s.weibo.com/weibo?q=%23%E6%9C%BA%E5%9C%BA%E6%80%8E%E4%B9%88%E4%B8%8D%E5%BC%80%E4%B8%AA%E6%B4%97%E5%A4%B4%E5%8F%91%E7%9A%84%E5%BA%97%23) `87.9K 🔥` `NEW`
1. [耙耙柑你牛](https://s.weibo.com/weibo?q=%23%E8%80%99%E8%80%99%E6%9F%91%E4%BD%A0%E7%89%9B%23) `85.2K 🔥` `NEW`
1. [金饰销售火爆](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E9%94%80%E5%94%AE%E7%81%AB%E7%88%86%23) `82.7K 🔥` `NEW`
1. [孔雪儿进行曲cha](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E8%BF%9B%E8%A1%8C%E6%9B%B2cha%23) `81.8K 🔥` `NEW`
1. [金价八连跌消费者还是不敢买](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%85%AB%E8%BF%9E%E8%B7%8C%E6%B6%88%E8%B4%B9%E8%80%85%E8%BF%98%E6%98%AF%E4%B8%8D%E6%95%A2%E4%B9%B0%23) `76.1K 🔥` `NEW`
1. [Ruler向队友道歉](https://s.weibo.com/weibo?q=%23Ruler%E5%90%91%E9%98%9F%E5%8F%8B%E9%81%93%E6%AD%89%23) `75.4K 🔥` `NEW`
1. [霸王茶姬口令 (Overlord Cha Ji password)](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `73.7K 🔥` `NEW`
1. [苏州文旅电竞联动给到夯](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E5%B7%9E%E6%96%87%E6%97%85%E7%94%B5%E7%AB%9E%E8%81%94%E5%8A%A8%E7%BB%99%E5%88%B0%E5%A4%AF%23) `64.1K 🔥` `NEW`
1. [江波龙实控人姐弟身家暴涨超400亿](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E6%B3%A2%E9%BE%99%E5%AE%9E%E6%8E%A7%E4%BA%BA%E5%A7%90%E5%BC%9F%E8%BA%AB%E5%AE%B6%E6%9A%B4%E6%B6%A8%E8%B6%85400%E4%BA%BF%23) `60.2K 🔥` `NEW`
1. [杨蓉把何炅整脸红了](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%93%89%E6%8A%8A%E4%BD%95%E7%82%85%E6%95%B4%E8%84%B8%E7%BA%A2%E4%BA%86%23) `59.8K 🔥` `NEW`
1. [樊长玉 贺将军](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%20%E8%B4%BA%E5%B0%86%E5%86%9B%23) `58.7K 🔥` `NEW`
1. [月鳞绮纪](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%23) `1.1M 🔥` `+43%`
1. [尊界S800携手海南高尔夫精英赛](https://s.weibo.com/weibo?q=%23%E5%B0%8A%E7%95%8CS800%E6%90%BA%E6%89%8B%E6%B5%B7%E5%8D%97%E9%AB%98%E5%B0%94%E5%A4%AB%E7%B2%BE%E8%8B%B1%E8%B5%9B%23) `369.6K 🔥` `+50%`
1. [逐玉反盗版声明 (Zhuyu Anti-Piracy Statement)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8D%E7%9B%97%E7%89%88%E5%A3%B0%E6%98%8E%23) `300.2K 🔥` `+41%`
1. [一诺职业病](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%AF%BA%E8%81%8C%E4%B8%9A%E7%97%85%23) `77.9K 🔥` `+28%`
1. [中国变压器在国外一器难求 (Chinese transformers are hard to find abroad)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%8F%98%E5%8E%8B%E5%99%A8%E5%9C%A8%E5%9B%BD%E5%A4%96%E4%B8%80%E5%99%A8%E9%9A%BE%E6%B1%82%23) `621.8K 🔥`
1. [王鸥 何九华](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B8%A5%20%E4%BD%95%E4%B9%9D%E5%8D%8E%23) `110.0K 🔥`
1. [高以翔前女友BeIIa官宣怀孕](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%BB%A5%E7%BF%94%E5%89%8D%E5%A5%B3%E5%8F%8BBeIIa%E5%AE%98%E5%AE%A3%E6%80%80%E5%AD%95%23) `109.7K 🔥`
1. [刚洗完澡别在浴室吹头发 (Don’t dry your hair in the bathroom right after you take a shower)](https://s.weibo.com/weibo?q=%23%E5%88%9A%E6%B4%97%E5%AE%8C%E6%BE%A1%E5%88%AB%E5%9C%A8%E6%B5%B4%E5%AE%A4%E5%90%B9%E5%A4%B4%E5%8F%91%23) `109.4K 🔥`
1. [陈慧敏怀孕了 (Chen Huimin is pregnant)](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%85%A7%E6%95%8F%E6%80%80%E5%AD%95%E4%BA%86%23) `109.2K 🔥`
1. [虞书欣杀青给粉丝鞠躬](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%9D%80%E9%9D%92%E7%BB%99%E7%B2%89%E4%B8%9D%E9%9E%A0%E8%BA%AC%23) `63.4K 🔥`
1. [多校试点班主任退群 (Pilot class teachers in many schools withdraw from the group)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%A0%A1%E8%AF%95%E7%82%B9%E7%8F%AD%E4%B8%BB%E4%BB%BB%E9%80%80%E7%BE%A4%23) `237.5K 🔥` `-78%`
1. [女子久坐便血半年后确诊癌症晚期 (Woman diagnosed with terminal cancer six months after sitting for long periods of time and having bloody stools)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%85%E5%9D%90%E4%BE%BF%E8%A1%80%E5%8D%8A%E5%B9%B4%E5%90%8E%E7%A1%AE%E8%AF%8A%E7%99%8C%E7%97%87%E6%99%9A%E6%9C%9F%23) `140.3K 🔥` `-33%`
1. [小猫嫌弃自己脚臭](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E5%AB%8C%E5%BC%83%E8%87%AA%E5%B7%B1%E8%84%9A%E8%87%AD%23) `131.7K 🔥` `-38%`
1. [以色列拦截伊朗导弹失败瞬间](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E6%8B%A6%E6%88%AA%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%A4%B1%E8%B4%A5%E7%9E%AC%E9%97%B4%23) `126.3K 🔥` `-40%`
1. [徐若晗桃花坞第一大漏勺](https://s.weibo.com/weibo?q=%23%E5%BE%90%E8%8B%A5%E6%99%97%E6%A1%83%E8%8A%B1%E5%9D%9E%E7%AC%AC%E4%B8%80%E5%A4%A7%E6%BC%8F%E5%8B%BA%23) `114.2K 🔥` `-46%`
1. [猥亵15岁少女民警曾对自己行为极力否认](https://s.weibo.com/weibo?q=%23%E7%8C%A5%E4%BA%B515%E5%B2%81%E5%B0%91%E5%A5%B3%E6%B0%91%E8%AD%A6%E6%9B%BE%E5%AF%B9%E8%87%AA%E5%B7%B1%E8%A1%8C%E4%B8%BA%E6%9E%81%E5%8A%9B%E5%90%A6%E8%AE%A4%23) `110.3K 🔥` `-33%`
1. [鸡鸣寺樱花](https://s.weibo.com/weibo?q=%23%E9%B8%A1%E9%B8%A3%E5%AF%BA%E6%A8%B1%E8%8A%B1%23) `110.3K 🔥` `-48%`
1. [辛芷蕾 多邻国](https://s.weibo.com/weibo?q=%23%E8%BE%9B%E8%8A%B7%E8%95%BE%20%E5%A4%9A%E9%82%BB%E5%9B%BD%23) `110.1K 🔥` `-47%`
1. [警方通报男子窜至某小区抢劫致1死 (The police reported that a man ran into a community and robbed one person to death.)](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E7%94%B7%E5%AD%90%E7%AA%9C%E8%87%B3%E6%9F%90%E5%B0%8F%E5%8C%BA%E6%8A%A2%E5%8A%AB%E8%87%B41%E6%AD%BB%23) `109.9K 🔥` `-57%`
1. [贾斯汀比伯Usher派对打架](https://s.weibo.com/weibo?q=%23%E8%B4%BE%E6%96%AF%E6%B1%80%E6%AF%94%E4%BC%AFUsher%E6%B4%BE%E5%AF%B9%E6%89%93%E6%9E%B6%23) `109.5K 🔥` `-24%`
1. [陈赫张子萱带女儿做客王祖蓝家](https://s.weibo.com/weibo?q=%23%E9%99%88%E8%B5%AB%E5%BC%A0%E5%AD%90%E8%90%B1%E5%B8%A6%E5%A5%B3%E5%84%BF%E5%81%9A%E5%AE%A2%E7%8E%8B%E7%A5%96%E8%93%9D%E5%AE%B6%23) `109.1K 🔥` `-47%`
1. [壁上观 (View from the wall)](https://s.weibo.com/weibo?q=%23%E5%A3%81%E4%B8%8A%E8%A7%82%23) `87.8K 🔥` `-58%`
1. [沙特谴责伊朗](https://s.weibo.com/weibo?q=%23%E6%B2%99%E7%89%B9%E8%B0%B4%E8%B4%A3%E4%BC%8A%E6%9C%97%23) `81.4K 🔥` `-61%`
1. [梅姨在广州三元里落网为不实消息](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%9C%A8%E5%B9%BF%E5%B7%9E%E4%B8%89%E5%85%83%E9%87%8C%E8%90%BD%E7%BD%91%E4%B8%BA%E4%B8%8D%E5%AE%9E%E6%B6%88%E6%81%AF%23) `80.2K 🔥` `-62%`
1. [英国男星死在普吉岛排水沟 (British actor dies in Phuket drain)](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E7%94%B7%E6%98%9F%E6%AD%BB%E5%9C%A8%E6%99%AE%E5%90%89%E5%B2%9B%E6%8E%92%E6%B0%B4%E6%B2%9F%23) `66.0K 🔥` `-54%`
1. [网友给逐玉的建议](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E7%BB%99%E9%80%90%E7%8E%89%E7%9A%84%E5%BB%BA%E8%AE%AE%23) `63.5K 🔥` `-30%`

Updated at 2026-03-22 17:57:37

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
