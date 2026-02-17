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

1. [镖人 真的好看 (The escort is really good-looking)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E7%9C%9F%E7%9A%84%E5%A5%BD%E7%9C%8B%23) `688.6K 🔥` `NEW`
1. [沙溢给白鹿发了多少压岁钱](https://s.weibo.com/weibo?q=%23%E6%B2%99%E6%BA%A2%E7%BB%99%E7%99%BD%E9%B9%BF%E5%8F%91%E4%BA%86%E5%A4%9A%E5%B0%91%E5%8E%8B%E5%B2%81%E9%92%B1%23) `548.8K 🔥` `NEW`
1. [广州烟花](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E5%B7%9E%E7%83%9F%E8%8A%B1%23) `248.7K 🔥` `NEW`
1. [千万别贪便宜买监控](https://s.weibo.com/weibo?q=%23%E5%8D%83%E4%B8%87%E5%88%AB%E8%B4%AA%E4%BE%BF%E5%AE%9C%E4%B9%B0%E7%9B%91%E6%8E%A7%23) `177.8K 🔥` `NEW`
1. [小芒崩了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E8%8A%92%E5%B4%A9%E4%BA%86%23) `177.5K 🔥` `NEW`
1. [千问说牛马的马是白龙马](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E8%AF%B4%E7%89%9B%E9%A9%AC%E7%9A%84%E9%A9%AC%E6%98%AF%E7%99%BD%E9%BE%99%E9%A9%AC%23) `177.5K 🔥` `NEW`
1. [B站春晚](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E6%98%A5%E6%99%9A%23) `177.4K 🔥` `NEW`
1. [刘少昂换四叶草挂件](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82%E6%8D%A2%E5%9B%9B%E5%8F%B6%E8%8D%89%E6%8C%82%E4%BB%B6%23) `177.1K 🔥` `NEW`
1. [春晚期间豆包AI互动达19亿次](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%9C%9F%E9%97%B4%E8%B1%86%E5%8C%85AI%E4%BA%92%E5%8A%A8%E8%BE%BE19%E4%BA%BF%E6%AC%A1%23) `177.0K 🔥` `NEW`
1. [英国男子打砸香港机场自助机器](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E7%94%B7%E5%AD%90%E6%89%93%E7%A0%B8%E9%A6%99%E6%B8%AF%E6%9C%BA%E5%9C%BA%E8%87%AA%E5%8A%A9%E6%9C%BA%E5%99%A8%23) `176.6K 🔥` `NEW`
1. [三文鱼其实是海底大肥猪 (Salmon is actually a big fat pig on the bottom of the sea)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%96%87%E9%B1%BC%E5%85%B6%E5%AE%9E%E6%98%AF%E6%B5%B7%E5%BA%95%E5%A4%A7%E8%82%A5%E7%8C%AA%23) `176.3K 🔥` `NEW`
1. [母女过年炸丸子变大型翻车现场](https://s.weibo.com/weibo?q=%23%E6%AF%8D%E5%A5%B3%E8%BF%87%E5%B9%B4%E7%82%B8%E4%B8%B8%E5%AD%90%E5%8F%98%E5%A4%A7%E5%9E%8B%E7%BF%BB%E8%BD%A6%E7%8E%B0%E5%9C%BA%23) `176.1K 🔥` `NEW`
1. [穆祉丞高会 落叶归根](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%E9%AB%98%E4%BC%9A%20%E8%90%BD%E5%8F%B6%E5%BD%92%E6%A0%B9%23) `176.0K 🔥` `NEW`
1. [金价银价直线跳水](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E9%93%B6%E4%BB%B7%E7%9B%B4%E7%BA%BF%E8%B7%B3%E6%B0%B4%23) `175.9K 🔥` `NEW`
1. [冯巩 我想死你们了](https://s.weibo.com/weibo?q=%23%E5%86%AF%E5%B7%A9%20%E6%88%91%E6%83%B3%E6%AD%BB%E4%BD%A0%E4%BB%AC%E4%BA%86%23) `175.8K 🔥` `NEW`
1. [岳云鹏一个人上春山](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E4%BA%91%E9%B9%8F%E4%B8%80%E4%B8%AA%E4%BA%BA%E4%B8%8A%E6%98%A5%E5%B1%B1%23) `175.7K 🔥` `NEW`
1. [演员过硬了才敢怼脸拍](https://s.weibo.com/weibo?q=%23%E6%BC%94%E5%91%98%E8%BF%87%E7%A1%AC%E4%BA%86%E6%89%8D%E6%95%A2%E6%80%BC%E8%84%B8%E6%8B%8D%23) `175.6K 🔥` `NEW`
1. [容易内耗的人有3个优点](https://s.weibo.com/weibo?q=%23%E5%AE%B9%E6%98%93%E5%86%85%E8%80%97%E7%9A%84%E4%BA%BA%E6%9C%893%E4%B8%AA%E4%BC%98%E7%82%B9%23) `175.5K 🔥` `NEW`
1. [谷爱凌说这是4年以来第一次赛大跳台](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%AF%B4%E8%BF%99%E6%98%AF4%E5%B9%B4%E4%BB%A5%E6%9D%A5%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%B5%9B%E5%A4%A7%E8%B7%B3%E5%8F%B0%23) `142.5K 🔥` `NEW`
1. [杨博文抽签抽到王橹杰叫早穆祉丞](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%8D%9A%E6%96%87%E6%8A%BD%E7%AD%BE%E6%8A%BD%E5%88%B0%E7%8E%8B%E6%A9%B9%E6%9D%B0%E5%8F%AB%E6%97%A9%E7%A9%86%E7%A5%89%E4%B8%9E%23) `142.1K 🔥` `NEW`
1. [再上门喂两次猫咪都成肌肉猫了 (After two more visits to feed the cat, he became a muscular cat.)](https://s.weibo.com/weibo?q=%23%E5%86%8D%E4%B8%8A%E9%97%A8%E5%96%82%E4%B8%A4%E6%AC%A1%E7%8C%AB%E5%92%AA%E9%83%BD%E6%88%90%E8%82%8C%E8%82%89%E7%8C%AB%E4%BA%86%23) `138.2K 🔥` `NEW`
1. [时代少年团红包分组](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E7%BA%A2%E5%8C%85%E5%88%86%E7%BB%84%23) `131.5K 🔥` `NEW`
1. [卫视春晚节目单](https://s.weibo.com/weibo?q=%23%E5%8D%AB%E8%A7%86%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `131.4K 🔥` `NEW`
1. [单依纯 我表示理解](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BE%9D%E7%BA%AF%20%E6%88%91%E8%A1%A8%E7%A4%BA%E7%90%86%E8%A7%A3%23) `129.6K 🔥` `NEW`
1. [北京台春晚](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%23) `1.2M 🔥` `+98%`
1. [全国初二回娘家的女婿belike](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E5%88%9D%E4%BA%8C%E5%9B%9E%E5%A8%98%E5%AE%B6%E7%9A%84%E5%A5%B3%E5%A9%BFbelike%23) `875.3K 🔥` `+460%`
1. [骏马贺新春电子贺卡 (Horse Happy New Year e-card)](https://s.weibo.com/weibo?q=%23%E9%AA%8F%E9%A9%AC%E8%B4%BA%E6%96%B0%E6%98%A5%E7%94%B5%E5%AD%90%E8%B4%BA%E5%8D%A1%23) `784.1K 🔥` `+29%`
1. [金典新春海报真绝了](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%85%B8%E6%96%B0%E6%98%A5%E6%B5%B7%E6%8A%A5%E7%9C%9F%E7%BB%9D%E4%BA%86%23) `779.6K 🔥` `+131%`
1. [时代少年团红包](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E7%BA%A2%E5%8C%85%23) `776.9K 🔥` `+257%`
1. [很火但难吃的小吃](https://s.weibo.com/weibo?q=%23%E5%BE%88%E7%81%AB%E4%BD%86%E9%9A%BE%E5%90%83%E7%9A%84%E5%B0%8F%E5%90%83%23) `721.5K 🔥` `+195%`
1. [集千问超级免单卡最后一天](https://s.weibo.com/weibo?q=%23%E9%9B%86%E5%8D%83%E9%97%AE%E8%B6%85%E7%BA%A7%E5%85%8D%E5%8D%95%E5%8D%A1%E6%9C%80%E5%90%8E%E4%B8%80%E5%A4%A9%23) `669.0K 🔥` `+38%`
1. [王菲春晚原唱是李雪琴北大闺蜜 (Faye Wong's original singer for the Spring Festival Gala is Li Xueqin, her best friend from Peking University)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E6%98%A5%E6%99%9A%E5%8E%9F%E5%94%B1%E6%98%AF%E6%9D%8E%E9%9B%AA%E7%90%B4%E5%8C%97%E5%A4%A7%E9%97%BA%E8%9C%9C%23) `177.7K 🔥` `+47%`
1. [老君山惊现灵气护罩](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%90%9B%E5%B1%B1%E6%83%8A%E7%8E%B0%E7%81%B5%E6%B0%94%E6%8A%A4%E7%BD%A9%23) `178.0K 🔥`
1. [北京台春晚节目单](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `176.4K 🔥`
1. [不是年味淡了而是轮到我们做主了](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%98%AF%E5%B9%B4%E5%91%B3%E6%B7%A1%E4%BA%86%E8%80%8C%E6%98%AF%E8%BD%AE%E5%88%B0%E6%88%91%E4%BB%AC%E5%81%9A%E4%B8%BB%E4%BA%86%23) `176.3K 🔥`
1. [TF家族族综 (TF family comprehensive)](https://s.weibo.com/weibo?q=%23TF%E5%AE%B6%E6%97%8F%E6%97%8F%E7%BB%BC%23) `142.3K 🔥`
1. [小酒窝和朵朵拜年合照](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%85%92%E7%AA%9D%E5%92%8C%E6%9C%B5%E6%9C%B5%E6%8B%9C%E5%B9%B4%E5%90%88%E7%85%A7%23) `135.8K 🔥`
1. [谷爱凌U型场地数据近乎完美 (Gu Ailing’s U-shaped field data is almost perfect)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E5%9E%8B%E5%9C%BA%E5%9C%B0%E6%95%B0%E6%8D%AE%E8%BF%91%E4%B9%8E%E5%AE%8C%E7%BE%8E%23) `177.9K 🔥` `-83%`
1. [爸妈来后冰箱都变老了 (The refrigerator has become old since my parents came here.)](https://s.weibo.com/weibo?q=%23%E7%88%B8%E5%A6%88%E6%9D%A5%E5%90%8E%E5%86%B0%E7%AE%B1%E9%83%BD%E5%8F%98%E8%80%81%E4%BA%86%23) `177.3K 🔥` `-32%`
1. [13个00后发小给彼此父母磕头拜年](https://s.weibo.com/weibo?q=%2313%E4%B8%AA00%E5%90%8E%E5%8F%91%E5%B0%8F%E7%BB%99%E5%BD%BC%E6%AD%A4%E7%88%B6%E6%AF%8D%E7%A3%95%E5%A4%B4%E6%8B%9C%E5%B9%B4%23) `177.2K 🔥` `-70%`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `176.9K 🔥` `-27%`
1. [飞驰人生3票房](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E7%A5%A8%E6%88%BF%23) `176.8K 🔥` `-31%`
1. [杨幂朱一龙吻戏 (Yang Mi and Zhu Yilong kiss scene)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9C%B1%E4%B8%80%E9%BE%99%E5%90%BB%E6%88%8F%23) `176.7K 🔥` `-28%`
1. [王楚然一脸懵不像演的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E4%B8%80%E8%84%B8%E6%87%B5%E4%B8%8D%E5%83%8F%E6%BC%94%E7%9A%84%23) `176.5K 🔥` `-71%`
1. [镖人 武侠群像](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E6%AD%A6%E4%BE%A0%E7%BE%A4%E5%83%8F%23) `176.0K 🔥` `-32%`
1. [镖人 排片 (Escort movie schedule)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E6%8E%92%E7%89%87%23) `175.5K 🔥` `-28%`
1. [红包 (Red envelope)](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E5%8C%85%23) `164.1K 🔥` `-21%`
1. [Kimi估值超100亿美元](https://s.weibo.com/weibo?q=%23Kimi%E4%BC%B0%E5%80%BC%E8%B6%85100%E4%BA%BF%E7%BE%8E%E5%85%83%23) `144.4K 🔥` `-41%`
1. [大年初一不煮饭 (No cooking on New Year’s Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E4%B8%8D%E7%85%AE%E9%A5%AD%23) `132.4K 🔥` `-78%`
1. [大年初一机票价格腰斩 (Air ticket prices halved on New Year's Day)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E6%9C%BA%E7%A5%A8%E4%BB%B7%E6%A0%BC%E8%85%B0%E6%96%A9%23) `129.8K 🔥` `-83%`
1. [23个小辈拜年舅舅给每人发100元红包](https://s.weibo.com/weibo?q=%2323%E4%B8%AA%E5%B0%8F%E8%BE%88%E6%8B%9C%E5%B9%B4%E8%88%85%E8%88%85%E7%BB%99%E6%AF%8F%E4%BA%BA%E5%8F%91100%E5%85%83%E7%BA%A2%E5%8C%85%23) `127.6K 🔥` `-45%`

Updated at 2026-02-17 21:25:02

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
