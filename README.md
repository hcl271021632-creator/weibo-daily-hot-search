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

1. [小米汽车 (Xiaomi car)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%B1%BD%E8%BD%A6%23) `1.2M 🔥` `NEW`
1. [9.98万起极狐全新阿尔法S5上市](https://s.weibo.com/weibo?q=%239.98%E4%B8%87%E8%B5%B7%E6%9E%81%E7%8B%90%E5%85%A8%E6%96%B0%E9%98%BF%E5%B0%94%E6%B3%95S5%E4%B8%8A%E5%B8%82%23) `577.4K 🔥` `NEW`
1. [DYG确认锁定季后赛败者组](https://s.weibo.com/weibo?q=%23DYG%E7%A1%AE%E8%AE%A4%E9%94%81%E5%AE%9A%E5%AD%A3%E5%90%8E%E8%B5%9B%E8%B4%A5%E8%80%85%E7%BB%84%23) `171.4K 🔥` `NEW`
1. [苏炳添赞新SU7为中国科技骄傲](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%82%B3%E6%B7%BB%E8%B5%9E%E6%96%B0SU7%E4%B8%BA%E4%B8%AD%E5%9B%BD%E7%A7%91%E6%8A%80%E9%AA%84%E5%82%B2%23) `155.6K 🔥` `NEW`
1. [7年前买的泡泡玛特盲盒才发货](https://s.weibo.com/weibo?q=%237%E5%B9%B4%E5%89%8D%E4%B9%B0%E7%9A%84%E6%B3%A1%E6%B3%A1%E7%8E%9B%E7%89%B9%E7%9B%B2%E7%9B%92%E6%89%8D%E5%8F%91%E8%B4%A7%23) `152.7K 🔥` `NEW`
1. [神秘人花7500元预存500碗面](https://s.weibo.com/weibo?q=%23%E7%A5%9E%E7%A7%98%E4%BA%BA%E8%8A%B17500%E5%85%83%E9%A2%84%E5%AD%98500%E7%A2%97%E9%9D%A2%23) `150.6K 🔥` `NEW`
1. [金价跌到看不懂](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E8%B7%8C%E5%88%B0%E7%9C%8B%E4%B8%8D%E6%87%82%23) `126.7K 🔥` `NEW`
1. [舒淇对新SU7卡布里蓝印象最深](https://s.weibo.com/weibo?q=%23%E8%88%92%E6%B7%87%E5%AF%B9%E6%96%B0SU7%E5%8D%A1%E5%B8%83%E9%87%8C%E8%93%9D%E5%8D%B0%E8%B1%A1%E6%9C%80%E6%B7%B1%23) `113.5K 🔥` `NEW`
1. [白银暴跌12%](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%93%B6%E6%9A%B4%E8%B7%8C12%25%23) `87.2K 🔥` `NEW`
1. [青岛爱心面馆重启见证温度](https://s.weibo.com/weibo?q=%23%E9%9D%92%E5%B2%9B%E7%88%B1%E5%BF%83%E9%9D%A2%E9%A6%86%E9%87%8D%E5%90%AF%E8%A7%81%E8%AF%81%E6%B8%A9%E5%BA%A6%23) `85.7K 🔥` `NEW`
1. [金价暴跌抄底7天越买越套 (The gold price plummeted and the bottom was bought for 7 days. The more you bought, the more you bought.)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%9A%B4%E8%B7%8C%E6%8A%84%E5%BA%957%E5%A4%A9%E8%B6%8A%E4%B9%B0%E8%B6%8A%E5%A5%97%23) `85.2K 🔥` `NEW`
1. [逐玉31集经纪人最爱的一集](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%8931%E9%9B%86%E7%BB%8F%E7%BA%AA%E4%BA%BA%E6%9C%80%E7%88%B1%E7%9A%84%E4%B8%80%E9%9B%86%23) `85.2K 🔥` `NEW`
1. [南方医院情况通报](https://s.weibo.com/weibo?q=%23%E5%8D%97%E6%96%B9%E5%8C%BB%E9%99%A2%E6%83%85%E5%86%B5%E9%80%9A%E6%8A%A5%23) `85.2K 🔥` `NEW`
1. [疑似胡歌初恋女友发文](https://s.weibo.com/weibo?q=%23%E7%96%91%E4%BC%BC%E8%83%A1%E6%AD%8C%E5%88%9D%E6%81%8B%E5%A5%B3%E5%8F%8B%E5%8F%91%E6%96%87%23) `85.2K 🔥` `NEW`
1. [意识到4年后30后就出生了](https://s.weibo.com/weibo?q=%23%E6%84%8F%E8%AF%86%E5%88%B04%E5%B9%B4%E5%90%8E30%E5%90%8E%E5%B0%B1%E5%87%BA%E7%94%9F%E4%BA%86%23) `85.1K 🔥` `NEW`
1. [于子迪金牌](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E5%AD%90%E8%BF%AA%E9%87%91%E7%89%8C%23) `85.1K 🔥` `NEW`
1. [胖东来馒头每人限购12个](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E9%A6%92%E5%A4%B4%E6%AF%8F%E4%BA%BA%E9%99%90%E8%B4%AD12%E4%B8%AA%23) `841.5K 🔥` `+396%`
1. [主人回应7只被偷小狗结伴逃回家](https://s.weibo.com/weibo?q=%23%E4%B8%BB%E4%BA%BA%E5%9B%9E%E5%BA%947%E5%8F%AA%E8%A2%AB%E5%81%B7%E5%B0%8F%E7%8B%97%E7%BB%93%E4%BC%B4%E9%80%83%E5%9B%9E%E5%AE%B6%23) `168.6K 🔥` `+51%`
1. [父亲回应儿子北大毕业送外卖](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E5%9B%9E%E5%BA%94%E5%84%BF%E5%AD%90%E5%8C%97%E5%A4%A7%E6%AF%95%E4%B8%9A%E9%80%81%E5%A4%96%E5%8D%96%23) `157.7K 🔥` `+40%`
1. [黄金瀑布式跳水](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%80%91%E5%B8%83%E5%BC%8F%E8%B7%B3%E6%B0%B4%23) `152.1K 🔥` `+61%`
1. [长江上又一座大桥建设新进展 (New progress in the construction of another bridge on the Yangtze River)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%B1%9F%E4%B8%8A%E5%8F%88%E4%B8%80%E5%BA%A7%E5%A4%A7%E6%A1%A5%E5%BB%BA%E8%AE%BE%E6%96%B0%E8%BF%9B%E5%B1%95%23) `648.8K 🔥`
1. [中方对以方说法感到震惊 (China is shocked by Israel’s statement)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%AF%B9%E4%BB%A5%E6%96%B9%E8%AF%B4%E6%B3%95%E6%84%9F%E5%88%B0%E9%9C%87%E6%83%8A%23) `217.4K 🔥`
1. [千问大模型首发搭载智己LS8 (Qianwen large model debuts equipped with Zhiji LS8)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%A4%A7%E6%A8%A1%E5%9E%8B%E9%A6%96%E5%8F%91%E6%90%AD%E8%BD%BD%E6%99%BA%E5%B7%B1LS8%23) `216.7K 🔥`
1. [伊朗外长回应美2000亿美元战争拨款](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E5%9B%9E%E5%BA%94%E7%BE%8E2000%E4%BA%BF%E7%BE%8E%E5%85%83%E6%88%98%E4%BA%89%E6%8B%A8%E6%AC%BE%23) `184.9K 🔥`
1. [雷军称新SU7门把手完全符合新国标](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E7%A7%B0%E6%96%B0SU7%E9%97%A8%E6%8A%8A%E6%89%8B%E5%AE%8C%E5%85%A8%E7%AC%A6%E5%90%88%E6%96%B0%E5%9B%BD%E6%A0%87%23) `172.9K 🔥`
1. [胡先煦秒删博](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%85%88%E7%85%A6%E7%A7%92%E5%88%A0%E5%8D%9A%23) `169.5K 🔥`
1. [王格格 奔跑吧14 (Wang Gege Run 14)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A0%BC%E6%A0%BC%20%E5%A5%94%E8%B7%91%E5%90%A714%23) `164.8K 🔥`
1. [被路虎别停8次男子个人信息疑泄露](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E8%B7%AF%E8%99%8E%E5%88%AB%E5%81%9C8%E6%AC%A1%E7%94%B7%E5%AD%90%E4%B8%AA%E4%BA%BA%E4%BF%A1%E6%81%AF%E7%96%91%E6%B3%84%E9%9C%B2%23) `162.1K 🔥`
1. [鞠婧祎爱吃白开水泡饭](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E7%88%B1%E5%90%83%E7%99%BD%E5%BC%80%E6%B0%B4%E6%B3%A1%E9%A5%AD%23) `159.9K 🔥`
1. [陶晶莹说被张凌赫古装帅得吓到](https://s.weibo.com/weibo?q=%23%E9%99%B6%E6%99%B6%E8%8E%B9%E8%AF%B4%E8%A2%AB%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%8F%A4%E8%A3%85%E5%B8%85%E5%BE%97%E5%90%93%E5%88%B0%23) `158.0K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `157.5K 🔥`
1. [台湾发生双尸案 (Double corpse case in Taiwan)](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E5%8F%91%E7%94%9F%E5%8F%8C%E5%B0%B8%E6%A1%88%23) `154.8K 🔥`
1. [张凌赫直播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9B%B4%E6%92%AD%23) `153.9K 🔥`
1. [网传奔跑吧14常驻嘉宾阵容 (Online news of running bar 14 permanent guest lineup)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E5%A5%94%E8%B7%91%E5%90%A714%E5%B8%B8%E9%A9%BB%E5%98%89%E5%AE%BE%E9%98%B5%E5%AE%B9%23) `149.0K 🔥`
1. [买30克金手镯比1月便宜6000元 (Buying a 30-gram gold bracelet is 6,000 yuan cheaper than in January)](https://s.weibo.com/weibo?q=%23%E4%B9%B030%E5%85%8B%E9%87%91%E6%89%8B%E9%95%AF%E6%AF%941%E6%9C%88%E4%BE%BF%E5%AE%9C6000%E5%85%83%23) `106.9K 🔥`
1. [17岁的Angelababy (17 year old Angelababy)](https://s.weibo.com/weibo?q=%2317%E5%B2%81%E7%9A%84Angelababy%23) `105.3K 🔥`
1. [白日提灯](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `92.3K 🔥`
1. [女婴半岁确诊脊柱裂大排畸报告正常 (Baby girl diagnosed with spina bifida and major deformity report normal at six months old)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%A9%B4%E5%8D%8A%E5%B2%81%E7%A1%AE%E8%AF%8A%E8%84%8A%E6%9F%B1%E8%A3%82%E5%A4%A7%E6%8E%92%E7%95%B8%E6%8A%A5%E5%91%8A%E6%AD%A3%E5%B8%B8%23) `85.2K 🔥`
1. [雷军直播 (Lei Jun live broadcast)](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E7%9B%B4%E6%92%AD%23) `85.1K 🔥`
1. [樊长玉一句侯爷把谢征叫破防了](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E4%B8%80%E5%8F%A5%E4%BE%AF%E7%88%B7%E6%8A%8A%E8%B0%A2%E5%BE%81%E5%8F%AB%E7%A0%B4%E9%98%B2%E4%BA%86%23) `85.1K 🔥`
1. [小米笔记本 (Xiaomi Notebook)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E7%AC%94%E8%AE%B0%E6%9C%AC%23) `272.9K 🔥` `-75%`
1. [小米发布会 (Xiaomi press conference)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E5%8F%91%E5%B8%83%E4%BC%9A%23) `224.0K 🔥` `-72%`
1. [小米新SU7起售价21.99万元](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%96%B0SU7%E8%B5%B7%E5%94%AE%E4%BB%B721.99%E4%B8%87%E5%85%83%23) `208.7K 🔥` `-60%`
1. [谁敢看逐玉接下来的预告](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%95%A2%E7%9C%8B%E9%80%90%E7%8E%89%E6%8E%A5%E4%B8%8B%E6%9D%A5%E7%9A%84%E9%A2%84%E5%91%8A%23) `167.0K 🔥` `-33%`
1. [雷军现身发布会](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E7%8E%B0%E8%BA%AB%E5%8F%91%E5%B8%83%E4%BC%9A%23) `149.6K 🔥` `-21%`
1. [雷军感谢王兴兴给了投资宇树的机会](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E6%84%9F%E8%B0%A2%E7%8E%8B%E5%85%B4%E5%85%B4%E7%BB%99%E4%BA%86%E6%8A%95%E8%B5%84%E5%AE%87%E6%A0%91%E7%9A%84%E6%9C%BA%E4%BC%9A%23) `144.2K 🔥` `-21%`
1. [舒淇代言SU7](https://s.weibo.com/weibo?q=%23%E8%88%92%E6%B7%87%E4%BB%A3%E8%A8%80SU7%23) `121.9K 🔥` `-34%`
1. [金价有望震荡回升](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%9C%89%E6%9C%9B%E9%9C%87%E8%8D%A1%E5%9B%9E%E5%8D%87%23) `94.5K 🔥` `-22%`
1. [逐玉开虐了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%80%E8%99%90%E4%BA%86%23) `91.3K 🔥` `-42%`
1. [3岁男童独自进电梯后坠楼身亡](https://s.weibo.com/weibo?q=%233%E5%B2%81%E7%94%B7%E7%AB%A5%E7%8B%AC%E8%87%AA%E8%BF%9B%E7%94%B5%E6%A2%AF%E5%90%8E%E5%9D%A0%E6%A5%BC%E8%BA%AB%E4%BA%A1%23) `86.3K 🔥` `-51%`
1. [宝诗龙上海全明星阵容 (Boucheron Shanghai All-Star Lineup)](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E8%AF%97%E9%BE%99%E4%B8%8A%E6%B5%B7%E5%85%A8%E6%98%8E%E6%98%9F%E9%98%B5%E5%AE%B9%23) `86.0K 🔥` `-54%`
1. [伊朗要求阿联酋作出赔偿](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A6%81%E6%B1%82%E9%98%BF%E8%81%94%E9%85%8B%E4%BD%9C%E5%87%BA%E8%B5%94%E5%81%BF%23) `85.2K 🔥` `-32%`

Updated at 2026-03-19 22:41:52

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
