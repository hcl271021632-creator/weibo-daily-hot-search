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

1. [双汇王中王火腿肠被曝吃出两根钢钉 (Shuanghui King of Kings ham sausage was exposed to have eaten two steel nails)](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E6%B1%87%E7%8E%8B%E4%B8%AD%E7%8E%8B%E7%81%AB%E8%85%BF%E8%82%A0%E8%A2%AB%E6%9B%9D%E5%90%83%E5%87%BA%E4%B8%A4%E6%A0%B9%E9%92%A2%E9%92%89%23) `231.2K 🔥` `NEW`
1. [逐玉直播](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%9B%B4%E6%92%AD%23) `230.5K 🔥` `NEW`
1. [烤肠界的四大顶流](https://s.weibo.com/weibo?q=%23%E7%83%A4%E8%82%A0%E7%95%8C%E7%9A%84%E5%9B%9B%E5%A4%A7%E9%A1%B6%E6%B5%81%23) `228.7K 🔥` `NEW`
1. [皇帝想娶樊长玉](https://s.weibo.com/weibo?q=%23%E7%9A%87%E5%B8%9D%E6%83%B3%E5%A8%B6%E6%A8%8A%E9%95%BF%E7%8E%89%23) `183.9K 🔥` `NEW`
1. [茂茂你终于结婚生子了](https://s.weibo.com/weibo?q=%23%E8%8C%82%E8%8C%82%E4%BD%A0%E7%BB%88%E4%BA%8E%E7%BB%93%E5%A9%9A%E7%94%9F%E5%AD%90%E4%BA%86%23) `154.8K 🔥` `NEW`
1. [冬去春来](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%8E%BB%E6%98%A5%E6%9D%A5%23) `98.5K 🔥` `NEW`
1. [蒯曼锁定伦敦世乒赛参赛资格](https://s.weibo.com/weibo?q=%23%E8%92%AF%E6%9B%BC%E9%94%81%E5%AE%9A%E4%BC%A6%E6%95%A6%E4%B8%96%E4%B9%92%E8%B5%9B%E5%8F%82%E8%B5%9B%E8%B5%84%E6%A0%BC%23) `96.8K 🔥` `NEW`
1. [范世錡直播](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%96%E9%8C%A1%E7%9B%B4%E6%92%AD%23) `88.7K 🔥` `NEW`
1. [专家称黄金被套的投资者确实很多](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E7%A7%B0%E9%BB%84%E9%87%91%E8%A2%AB%E5%A5%97%E7%9A%84%E6%8A%95%E8%B5%84%E8%80%85%E7%A1%AE%E5%AE%9E%E5%BE%88%E5%A4%9A%23) `87.7K 🔥` `NEW`
1. [1983编剧 升咖](https://s.weibo.com/weibo?q=%231983%E7%BC%96%E5%89%A7%20%E5%8D%87%E5%92%96%23) `86.9K 🔥` `NEW`
1. [BLG请神 (BLG please god)](https://s.weibo.com/weibo?q=%23BLG%E8%AF%B7%E7%A5%9E%23) `85.9K 🔥` `NEW`
1. [23岁吴世勋Monster](https://s.weibo.com/weibo?q=%2323%E5%B2%81%E5%90%B4%E4%B8%96%E5%8B%8BMonster%23) `85.0K 🔥` `NEW`
1. [武汉女孩8天胖8斤喊话顺德道歉](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E6%B1%89%E5%A5%B3%E5%AD%A98%E5%A4%A9%E8%83%968%E6%96%A4%E5%96%8A%E8%AF%9D%E9%A1%BA%E5%BE%B7%E9%81%93%E6%AD%89%23) `82.2K 🔥` `NEW`
1. [太古里认领唐嫣](https://s.weibo.com/weibo?q=%23%E5%A4%AA%E5%8F%A4%E9%87%8C%E8%AE%A4%E9%A2%86%E5%94%90%E5%AB%A3%23) `78.7K 🔥` `NEW`
1. [四门全开那一下真没忍住笑](https://s.weibo.com/weibo?q=%23%E5%9B%9B%E9%97%A8%E5%85%A8%E5%BC%80%E9%82%A3%E4%B8%80%E4%B8%8B%E7%9C%9F%E6%B2%A1%E5%BF%8D%E4%BD%8F%E7%AC%91%23) `76.1K 🔥` `NEW`
1. [9岁男孩误会插队被成人推搡受伤](https://s.weibo.com/weibo?q=%239%E5%B2%81%E7%94%B7%E5%AD%A9%E8%AF%AF%E4%BC%9A%E6%8F%92%E9%98%9F%E8%A2%AB%E6%88%90%E4%BA%BA%E6%8E%A8%E6%90%A1%E5%8F%97%E4%BC%A4%23) `75.8K 🔥` `NEW`
1. [丁禹兮直播](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A6%B9%E5%85%AE%E7%9B%B4%E6%92%AD%23) `75.7K 🔥` `NEW`
1. [让小猫乖乖套圈](https://s.weibo.com/weibo?q=%23%E8%AE%A9%E5%B0%8F%E7%8C%AB%E4%B9%96%E4%B9%96%E5%A5%97%E5%9C%88%23) `75.5K 🔥` `NEW`
1. [香港发生亿元黄金劫案 (Billion dollar gold robbery in Hong Kong)](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E5%8F%91%E7%94%9F%E4%BA%BF%E5%85%83%E9%BB%84%E9%87%91%E5%8A%AB%E6%A1%88%23) `1.1M 🔥` `+45%`
1. [张凌赫的撕拉片又被热议了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9A%84%E6%92%95%E6%8B%89%E7%89%87%E5%8F%88%E8%A2%AB%E7%83%AD%E8%AE%AE%E4%BA%86%23) `228.1K 🔥` `+119%`
1. [张靓颖回应do脸翻车](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9D%93%E9%A2%96%E5%9B%9E%E5%BA%94do%E8%84%B8%E7%BF%BB%E8%BD%A6%23) `227.6K 🔥` `+119%`
1. [减内脏脂肪最有效的方法 (The most effective way to reduce visceral fat)](https://s.weibo.com/weibo?q=%23%E5%87%8F%E5%86%85%E8%84%8F%E8%84%82%E8%82%AA%E6%9C%80%E6%9C%89%E6%95%88%E7%9A%84%E6%96%B9%E6%B3%95%23) `227.1K 🔥` `+25%`
1. [迪丽热巴直播](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%9B%B4%E6%92%AD%23) `226.9K 🔥` `+114%`
1. [辛芷蕾 多邻国 (Xin Zhilei Duolingo)](https://s.weibo.com/weibo?q=%23%E8%BE%9B%E8%8A%B7%E8%95%BE%20%E5%A4%9A%E9%82%BB%E5%9B%BD%23) `226.2K 🔥` `+112%`
1. [女子久坐便血半年后确诊癌症晚期 (Woman diagnosed with terminal cancer six months after sitting for long periods of time and having bloody stools)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%85%E5%9D%90%E4%BE%BF%E8%A1%80%E5%8D%8A%E5%B9%B4%E5%90%8E%E7%A1%AE%E8%AF%8A%E7%99%8C%E7%97%87%E6%99%9A%E6%9C%9F%23) `181.6K 🔥` `+51%`
1. [金价上演断崖式下跌](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E4%B8%8A%E6%BC%94%E6%96%AD%E5%B4%96%E5%BC%8F%E4%B8%8B%E8%B7%8C%23) `175.6K 🔥` `+63%`
1. [王鸥 何九华](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B8%A5%20%E4%BD%95%E4%B9%9D%E5%8D%8E%23) `169.7K 🔥` `+62%`
1. [高以翔前女友BeIIa官宣怀孕](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%BB%A5%E7%BF%94%E5%89%8D%E5%A5%B3%E5%8F%8BBeIIa%E5%AE%98%E5%AE%A3%E6%80%80%E5%AD%95%23) `161.8K 🔥` `+72%`
1. [谢征随元青 正版和盗版的区别 (Xie Zheng and Yuan Qing The difference between genuine and pirated copies)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E9%9A%8F%E5%85%83%E9%9D%92%20%E6%AD%A3%E7%89%88%E5%92%8C%E7%9B%97%E7%89%88%E7%9A%84%E5%8C%BA%E5%88%AB%23) `156.2K 🔥` `+27%`
1. [23岁女子刚结婚一年就闭经](https://s.weibo.com/weibo?q=%2323%E5%B2%81%E5%A5%B3%E5%AD%90%E5%88%9A%E7%BB%93%E5%A9%9A%E4%B8%80%E5%B9%B4%E5%B0%B1%E9%97%AD%E7%BB%8F%23) `128.3K 🔥` `+21%`
1. [网警破获网络开盒案守护网络空间安全 (Internet police cracked the case of network box opening to protect the security of cyberspace)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%AD%A6%E7%A0%B4%E8%8E%B7%E7%BD%91%E7%BB%9C%E5%BC%80%E7%9B%92%E6%A1%88%E5%AE%88%E6%8A%A4%E7%BD%91%E7%BB%9C%E7%A9%BA%E9%97%B4%E5%AE%89%E5%85%A8%23) `613.7K 🔥`
1. [伊朗导弹在以本土砸出直径10米深坑](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%9C%A8%E4%BB%A5%E6%9C%AC%E5%9C%9F%E7%A0%B8%E5%87%BA%E7%9B%B4%E5%BE%8410%E7%B1%B3%E6%B7%B1%E5%9D%91%23) `229.7K 🔥`
1. [逐玉学一下想见你是怎么挽救的](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%AD%A6%E4%B8%80%E4%B8%8B%E6%83%B3%E8%A7%81%E4%BD%A0%E6%98%AF%E6%80%8E%E4%B9%88%E6%8C%BD%E6%95%91%E7%9A%84%23) `228.9K 🔥`
1. [金价八连跌消费者还是不敢买 (Gold prices have fallen for eight consecutive years, and consumers are still afraid to buy them)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%85%AB%E8%BF%9E%E8%B7%8C%E6%B6%88%E8%B4%B9%E8%80%85%E8%BF%98%E6%98%AF%E4%B8%8D%E6%95%A2%E4%B9%B0%23) `159.3K 🔥`
1. [78岁女子撞死苹果高管一家被判缓刑](https://s.weibo.com/weibo?q=%2378%E5%B2%81%E5%A5%B3%E5%AD%90%E6%92%9E%E6%AD%BB%E8%8B%B9%E6%9E%9C%E9%AB%98%E7%AE%A1%E4%B8%80%E5%AE%B6%E8%A2%AB%E5%88%A4%E7%BC%93%E5%88%91%23) `100.8K 🔥`
1. [刚洗完澡别在浴室吹头发 (Don’t dry your hair in the bathroom right after you take a shower)](https://s.weibo.com/weibo?q=%23%E5%88%9A%E6%B4%97%E5%AE%8C%E6%BE%A1%E5%88%AB%E5%9C%A8%E6%B5%B4%E5%AE%A4%E5%90%B9%E5%A4%B4%E5%8F%91%23) `93.6K 🔥`
1. [身体状态决定人生走向](https://s.weibo.com/weibo?q=%23%E8%BA%AB%E4%BD%93%E7%8A%B6%E6%80%81%E5%86%B3%E5%AE%9A%E4%BA%BA%E7%94%9F%E8%B5%B0%E5%90%91%23) `89.5K 🔥`
1. [多邻国喊辛芷蕾妈妈 (Duolingo calls Xin Zhilei’s mother)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E9%82%BB%E5%9B%BD%E5%96%8A%E8%BE%9B%E8%8A%B7%E8%95%BE%E5%A6%88%E5%A6%88%23) `82.0K 🔥`
1. [陈慧敏怀孕了](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%85%A7%E6%95%8F%E6%80%80%E5%AD%95%E4%BA%86%23) `79.3K 🔥`
1. [胡楚靓前男友新恋情](https://s.weibo.com/weibo?q=%23%E8%83%A1%E6%A5%9A%E9%9D%93%E5%89%8D%E7%94%B7%E5%8F%8B%E6%96%B0%E6%81%8B%E6%83%85%23) `77.6K 🔥`
1. [排队加油](https://s.weibo.com/weibo?q=%23%E6%8E%92%E9%98%9F%E5%8A%A0%E6%B2%B9%23) `73.8K 🔥`
1. [爱吃荔枝的人今年天塌了 (People who love lychees are in trouble this year)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E8%8D%94%E6%9E%9D%E7%9A%84%E4%BA%BA%E4%BB%8A%E5%B9%B4%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `792.0K 🔥` `-26%`
1. [迪士尼平替把多少县城父母骗惨了](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E5%A3%AB%E5%B0%BC%E5%B9%B3%E6%9B%BF%E6%8A%8A%E5%A4%9A%E5%B0%91%E5%8E%BF%E5%9F%8E%E7%88%B6%E6%AF%8D%E9%AA%97%E6%83%A8%E4%BA%86%23) `240.2K 🔥` `-47%`
1. [逐玉反盗版声明 (Zhuyu Anti-Piracy Statement)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8D%E7%9B%97%E7%89%88%E5%A3%B0%E6%98%8E%23) `229.4K 🔥` `-45%`
1. [专家称梅姨可能觉得自己在做善事](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E7%A7%B0%E6%A2%85%E5%A7%A8%E5%8F%AF%E8%83%BD%E8%A7%89%E5%BE%97%E8%87%AA%E5%B7%B1%E5%9C%A8%E5%81%9A%E5%96%84%E4%BA%8B%23) `225.8K 🔥` `-48%`
1. [耙耙柑你牛 (Rake tangerines, you are awesome)](https://s.weibo.com/weibo?q=%23%E8%80%99%E8%80%99%E6%9F%91%E4%BD%A0%E7%89%9B%23) `225.7K 🔥` `-25%`
1. [月鳞绮纪](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%23) `120.2K 🔥` `-34%`
1. [爬山就得穿鲜艳的衣服 (You have to wear bright clothes when climbing mountains)](https://s.weibo.com/weibo?q=%23%E7%88%AC%E5%B1%B1%E5%B0%B1%E5%BE%97%E7%A9%BF%E9%B2%9C%E8%89%B3%E7%9A%84%E8%A1%A3%E6%9C%8D%23) `107.7K 🔥` `-28%`
1. [女生遭民警猥亵父亲刚开始以为是胡说 (The girl was molested by the police. Her father thought it was nonsense at first.)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E9%81%AD%E6%B0%91%E8%AD%A6%E7%8C%A5%E4%BA%B5%E7%88%B6%E4%BA%B2%E5%88%9A%E5%BC%80%E5%A7%8B%E4%BB%A5%E4%B8%BA%E6%98%AF%E8%83%A1%E8%AF%B4%23) `79.3K 🔥` `-31%`
1. [仙逆 (Immortal Ni)](https://s.weibo.com/weibo?q=%23%E4%BB%99%E9%80%86%23) `73.8K 🔥` `-33%`

Updated at 2026-03-22 20:38:06

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
