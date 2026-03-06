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

1. [被医生咆哮塞200元母亲婉拒捐款 (The mother who was yelled at by the doctor and stuffed her with NT$200 declined the donation.)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E5%8C%BB%E7%94%9F%E5%92%86%E5%93%AE%E5%A1%9E200%E5%85%83%E6%AF%8D%E4%BA%B2%E5%A9%89%E6%8B%92%E6%8D%90%E6%AC%BE%23) `1.1M 🔥` `NEW`
1. [利率下调房贷省出110万元](https://s.weibo.com/weibo?q=%23%E5%88%A9%E7%8E%87%E4%B8%8B%E8%B0%83%E6%88%BF%E8%B4%B7%E7%9C%81%E5%87%BA110%E4%B8%87%E5%85%83%23) `782.5K 🔥` `NEW`
1. [建议取消学术不端人员教职或学位](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%8F%96%E6%B6%88%E5%AD%A6%E6%9C%AF%E4%B8%8D%E7%AB%AF%E4%BA%BA%E5%91%98%E6%95%99%E8%81%8C%E6%88%96%E5%AD%A6%E4%BD%8D%23) `629.5K 🔥` `NEW`
1. [霸王茶姬免单](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%85%8D%E5%8D%95%23) `628.2K 🔥` `NEW`
1. [伊朗外长拒绝与美国谈判](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E6%8B%92%E7%BB%9D%E4%B8%8E%E7%BE%8E%E5%9B%BD%E8%B0%88%E5%88%A4%23) `625.8K 🔥` `NEW`
1. [戴电子手表人的统一奇怪动作](https://s.weibo.com/weibo?q=%23%E6%88%B4%E7%94%B5%E5%AD%90%E6%89%8B%E8%A1%A8%E4%BA%BA%E7%9A%84%E7%BB%9F%E4%B8%80%E5%A5%87%E6%80%AA%E5%8A%A8%E4%BD%9C%23) `617.1K 🔥` `NEW`
1. [凤舞九天](https://s.weibo.com/weibo?q=%23%E5%87%A4%E8%88%9E%E4%B9%9D%E5%A4%A9%23) `432.9K 🔥` `NEW`
1. [委内瑞拉决定同美国恢复外交关系](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E5%86%B3%E5%AE%9A%E5%90%8C%E7%BE%8E%E5%9B%BD%E6%81%A2%E5%A4%8D%E5%A4%96%E4%BA%A4%E5%85%B3%E7%B3%BB%23) `358.2K 🔥` `NEW`
1. [日本再次向海洋排放核污染水](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%86%8D%E6%AC%A1%E5%90%91%E6%B5%B7%E6%B4%8B%E6%8E%92%E6%94%BE%E6%A0%B8%E6%B1%A1%E6%9F%93%E6%B0%B4%23) `354.1K 🔥` `NEW`
1. [特朗普在白宫接见梅西](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E5%9C%A8%E7%99%BD%E5%AE%AB%E6%8E%A5%E8%A7%81%E6%A2%85%E8%A5%BF%23) `329.3K 🔥` `NEW`
1. [重案六组 (Serious Case Group Six)](https://s.weibo.com/weibo?q=%23%E9%87%8D%E6%A1%88%E5%85%AD%E7%BB%84%23) `310.2K 🔥` `NEW`
1. [伊朗称美军林肯号航母被击中后撤](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E7%BE%8E%E5%86%9B%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%E8%A2%AB%E5%87%BB%E4%B8%AD%E5%90%8E%E6%92%A4%23) `285.1K 🔥` `NEW`
1. [代表建议提升环卫工人待遇](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%BB%BA%E8%AE%AE%E6%8F%90%E5%8D%87%E7%8E%AF%E5%8D%AB%E5%B7%A5%E4%BA%BA%E5%BE%85%E9%81%87%23) `239.3K 🔥` `NEW`
1. [人类进化没放弃头发是有原因的](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%B1%BB%E8%BF%9B%E5%8C%96%E6%B2%A1%E6%94%BE%E5%BC%83%E5%A4%B4%E5%8F%91%E6%98%AF%E6%9C%89%E5%8E%9F%E5%9B%A0%E7%9A%84%23) `238.6K 🔥` `NEW`
1. [10万亿存量公积金如何盘活](https://s.weibo.com/weibo?q=%2310%E4%B8%87%E4%BA%BF%E5%AD%98%E9%87%8F%E5%85%AC%E7%A7%AF%E9%87%91%E5%A6%82%E4%BD%95%E7%9B%98%E6%B4%BB%23) `232.8K 🔥` `NEW`
1. [D级SUV的顶级掌控感](https://s.weibo.com/weibo?q=%23D%E7%BA%A7SUV%E7%9A%84%E9%A1%B6%E7%BA%A7%E6%8E%8C%E6%8E%A7%E6%84%9F%23) `214.0K 🔥` `NEW`
1. [妈妈回应女儿长得像星星人](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%84%BF%E9%95%BF%E5%BE%97%E5%83%8F%E6%98%9F%E6%98%9F%E4%BA%BA%23) `206.3K 🔥` `NEW`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `201.5K 🔥` `NEW`
1. [李昀锐刘些宁归良辰今日开机](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E5%88%98%E4%BA%9B%E5%AE%81%E5%BD%92%E8%89%AF%E8%BE%B0%E4%BB%8A%E6%97%A5%E5%BC%80%E6%9C%BA%23) `157.8K 🔥` `NEW`
1. [伊朗称已准备好应对美军地面入侵](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%B7%B2%E5%87%86%E5%A4%87%E5%A5%BD%E5%BA%94%E5%AF%B9%E7%BE%8E%E5%86%9B%E5%9C%B0%E9%9D%A2%E5%85%A5%E4%BE%B5%23) `150.6K 🔥` `NEW`
1. [王楚钦与小海螺 (Wang Chuqin and the little conch)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E4%B8%8E%E5%B0%8F%E6%B5%B7%E8%9E%BA%23) `145.0K 🔥` `NEW`
1. [两会](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `128.3K 🔥` `NEW`
1. [向涵之看秀造型](https://s.weibo.com/weibo?q=%23%E5%90%91%E6%B6%B5%E4%B9%8B%E7%9C%8B%E7%A7%80%E9%80%A0%E5%9E%8B%23) `127.5K 🔥` `NEW`
1. [折叠屏最好的屏幕长什么样](https://s.weibo.com/weibo?q=%23%E6%8A%98%E5%8F%A0%E5%B1%8F%E6%9C%80%E5%A5%BD%E7%9A%84%E5%B1%8F%E5%B9%95%E9%95%BF%E4%BB%80%E4%B9%88%E6%A0%B7%23) `123.3K 🔥` `NEW`
1. [中方吊唁哈梅内伊遇难](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%90%8A%E5%94%81%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E9%81%87%E9%9A%BE%23) `123.0K 🔥` `NEW`
1. [外婆以为这样就是在送礼物了](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%A9%86%E4%BB%A5%E4%B8%BA%E8%BF%99%E6%A0%B7%E5%B0%B1%E6%98%AF%E5%9C%A8%E9%80%81%E7%A4%BC%E7%89%A9%E4%BA%86%23) `121.8K 🔥` `NEW`
1. [辛芷蕾巴黎时装周新造型](https://s.weibo.com/weibo?q=%23%E8%BE%9B%E8%8A%B7%E8%95%BE%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E6%96%B0%E9%80%A0%E5%9E%8B%23) `120.5K 🔥` `NEW`
1. [猫咪外出归来回家发现天塌了](https://s.weibo.com/weibo?q=%23%E7%8C%AB%E5%92%AA%E5%A4%96%E5%87%BA%E5%BD%92%E6%9D%A5%E5%9B%9E%E5%AE%B6%E5%8F%91%E7%8E%B0%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `110.6K 🔥` `NEW`
1. [委员谈年轻人不愿意体检](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E8%B0%88%E5%B9%B4%E8%BD%BB%E4%BA%BA%E4%B8%8D%E6%84%BF%E6%84%8F%E4%BD%93%E6%A3%80%23) `107.0K 🔥` `NEW`
1. [十日终焉](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%23) `104.9K 🔥` `NEW`
1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `95.0K 🔥` `NEW`
1. [樊振东又添新荣誉](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%8F%88%E6%B7%BB%E6%96%B0%E8%8D%A3%E8%AA%89%23) `82.0K 🔥` `NEW`
1. [当事人回应每月买黄金已赚50万](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BA%8B%E4%BA%BA%E5%9B%9E%E5%BA%94%E6%AF%8F%E6%9C%88%E4%B9%B0%E9%BB%84%E9%87%91%E5%B7%B2%E8%B5%9A50%E4%B8%87%23) `81.1K 🔥` `NEW`
1. [逐玉开播](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%80%E6%92%AD%23) `76.5K 🔥` `NEW`
1. [杨超越出发巴黎时装周机场路透](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%B6%85%E8%B6%8A%E5%87%BA%E5%8F%91%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E6%9C%BA%E5%9C%BA%E8%B7%AF%E9%80%8F%23) `76.0K 🔥` `NEW`
1. [人际交往里最让人反感的行为](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E9%99%85%E4%BA%A4%E5%BE%80%E9%87%8C%E6%9C%80%E8%AE%A9%E4%BA%BA%E5%8F%8D%E6%84%9F%E7%9A%84%E8%A1%8C%E4%B8%BA%23) `75.6K 🔥` `NEW`
1. [逐玉云包场好多cp](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%91%E5%8C%85%E5%9C%BA%E5%A5%BD%E5%A4%9Acp%23) `75.4K 🔥` `NEW`
1. [全新腾势Z9GT上市价26.98万元起 (The new Denza Z9GT is launched with a starting price of 269,800 yuan)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E6%96%B0%E8%85%BE%E5%8A%BFZ9GT%E4%B8%8A%E5%B8%82%E4%BB%B726.98%E4%B8%87%E5%85%83%E8%B5%B7%23) `639.3K 🔥` `+1280%`
1. [首台ID.ERA 9X投产上新](https://s.weibo.com/weibo?q=%23%E9%A6%96%E5%8F%B0ID.ERA%209X%E6%8A%95%E4%BA%A7%E4%B8%8A%E6%96%B0%23) `619.4K 🔥` `+196%`
1. [曝现在就出发4金晨被替换了 (It is revealed that Jin Chen has been replaced in Let’s Go Now 4)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%E9%87%91%E6%99%A8%E8%A2%AB%E6%9B%BF%E6%8D%A2%E4%BA%86%23) `239.2K 🔥` `+159%`
1. [陈哲远 再不救教资要融化了 (Chen Zheyuan If we don’t save the teaching resources, they will be melted down.)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%20%E5%86%8D%E4%B8%8D%E6%95%91%E6%95%99%E8%B5%84%E8%A6%81%E8%9E%8D%E5%8C%96%E4%BA%86%23) `98.5K 🔥` `+30%`
1. [中国将在哪些方向发力](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%B0%86%E5%9C%A8%E5%93%AA%E4%BA%9B%E6%96%B9%E5%90%91%E5%8F%91%E5%8A%9B%23) `644.6K 🔥`
1. [伊朗称其无人机袭击林肯号航母](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%85%B6%E6%97%A0%E4%BA%BA%E6%9C%BA%E8%A2%AD%E5%87%BB%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%23) `137.8K 🔥`
1. [如萍你真是在哪都不会说话 (Ruping, you really can’t speak anywhere.)](https://s.weibo.com/weibo?q=%23%E5%A6%82%E8%90%8D%E4%BD%A0%E7%9C%9F%E6%98%AF%E5%9C%A8%E5%93%AA%E9%83%BD%E4%B8%8D%E4%BC%9A%E8%AF%B4%E8%AF%9D%23) `75.5K 🔥`
1. [曝现在就出发4沈腾白敬亭带队](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%E6%B2%88%E8%85%BE%E7%99%BD%E6%95%AC%E4%BA%AD%E5%B8%A6%E9%98%9F%23) `291.5K 🔥` `-60%`
1. [春假清明连休6天家长称很无奈 (Parents said they were helpless after taking six consecutive days off during the Qingming Festival during the spring break.)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%81%87%E6%B8%85%E6%98%8E%E8%BF%9E%E4%BC%916%E5%A4%A9%E5%AE%B6%E9%95%BF%E7%A7%B0%E5%BE%88%E6%97%A0%E5%A5%88%23) `222.6K 🔥` `-70%`
1. [美国国土安全部部长被解职](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%9B%BD%E5%9C%9F%E5%AE%89%E5%85%A8%E9%83%A8%E9%83%A8%E9%95%BF%E8%A2%AB%E8%A7%A3%E8%81%8C%23) `155.8K 🔥` `-75%`
1. [17岁男生发现新物种筷子蛇登上SCI (A 17-year-old boy discovered a new species of chopstick snake and boarded the SCI)](https://s.weibo.com/weibo?q=%2317%E5%B2%81%E7%94%B7%E7%94%9F%E5%8F%91%E7%8E%B0%E6%96%B0%E7%89%A9%E7%A7%8D%E7%AD%B7%E5%AD%90%E8%9B%87%E7%99%BB%E4%B8%8ASCI%23) `119.1K 🔥` `-27%`
1. [高速收费员因帅得人山人海火了](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E6%94%B6%E8%B4%B9%E5%91%98%E5%9B%A0%E5%B8%85%E5%BE%97%E4%BA%BA%E5%B1%B1%E4%BA%BA%E6%B5%B7%E7%81%AB%E4%BA%86%23) `99.9K 🔥` `-38%`
1. [香港没有调休](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E6%B2%A1%E6%9C%89%E8%B0%83%E4%BC%91%23) `98.7K 🔥` `-91%`
1. [33岁女子长相幼态常被认为是小学生](https://s.weibo.com/weibo?q=%2333%E5%B2%81%E5%A5%B3%E5%AD%90%E9%95%BF%E7%9B%B8%E5%B9%BC%E6%80%81%E5%B8%B8%E8%A2%AB%E8%AE%A4%E4%B8%BA%E6%98%AF%E5%B0%8F%E5%AD%A6%E7%94%9F%23) `94.2K 🔥` `-41%`
1. [归良辰](https://s.weibo.com/weibo?q=%23%E5%BD%92%E8%89%AF%E8%BE%B0%23) `85.9K 🔥` `-25%`

Updated at 2026-03-06 10:49:38

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
