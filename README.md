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

1. [司法部将在全国统一推行扫码入企 (The Ministry of Justice will uniformly implement scanning codes to enter enterprises nationwide)](https://s.weibo.com/weibo?q=%23%E5%8F%B8%E6%B3%95%E9%83%A8%E5%B0%86%E5%9C%A8%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%A1%8C%E6%89%AB%E7%A0%81%E5%85%A5%E4%BC%81%23) `565.7K 🔥` `NEW`
1. [微信3大新功能](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A13%E5%A4%A7%E6%96%B0%E5%8A%9F%E8%83%BD%23) `506.1K 🔥` `NEW`
1. [本田突发暴雷](https://s.weibo.com/weibo?q=%23%E6%9C%AC%E7%94%B0%E7%AA%81%E5%8F%91%E6%9A%B4%E9%9B%B7%23) `504.2K 🔥` `NEW`
1. [男子误吞12厘米筷子忍了8年才取出](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%AF%AF%E5%90%9E12%E5%8E%98%E7%B1%B3%E7%AD%B7%E5%AD%90%E5%BF%8D%E4%BA%868%E5%B9%B4%E6%89%8D%E5%8F%96%E5%87%BA%23) `503.1K 🔥` `NEW`
1. [通过政府立法解决内卷式竞争](https://s.weibo.com/weibo?q=%23%E9%80%9A%E8%BF%87%E6%94%BF%E5%BA%9C%E7%AB%8B%E6%B3%95%E8%A7%A3%E5%86%B3%E5%86%85%E5%8D%B7%E5%BC%8F%E7%AB%9E%E4%BA%89%23) `501.4K 🔥` `NEW`
1. [今年加快研究人工智能立法](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E5%8A%A0%E5%BF%AB%E7%A0%94%E7%A9%B6%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%AB%8B%E6%B3%95%23) `499.7K 🔥` `NEW`
1. [保时捷车主回应车窗被砸取AED救人](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E6%97%B6%E6%8D%B7%E8%BD%A6%E4%B8%BB%E5%9B%9E%E5%BA%94%E8%BD%A6%E7%AA%97%E8%A2%AB%E7%A0%B8%E5%8F%96AED%E6%95%91%E4%BA%BA%23) `498.7K 🔥` `NEW`
1. [乐华 中韩男团](https://s.weibo.com/weibo?q=%23%E4%B9%90%E5%8D%8E%20%E4%B8%AD%E9%9F%A9%E7%94%B7%E5%9B%A2%23) `497.1K 🔥` `NEW`
1. [全红婵白衬衫配裙子发辫精致](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E7%99%BD%E8%A1%AC%E8%A1%AB%E9%85%8D%E8%A3%99%E5%AD%90%E5%8F%91%E8%BE%AB%E7%B2%BE%E8%87%B4%23) `497.0K 🔥` `NEW`
1. [张翅直播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%BF%85%E7%9B%B4%E6%92%AD%23) `496.0K 🔥` `NEW`
1. [董卿何赛飞 初见她漫步溪桥下 (Dong Qing and He Saifei first saw her walking under the creek bridge)](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%8D%BF%E4%BD%95%E8%B5%9B%E9%A3%9E%20%E5%88%9D%E8%A7%81%E5%A5%B9%E6%BC%AB%E6%AD%A5%E6%BA%AA%E6%A1%A5%E4%B8%8B%23) `495.9K 🔥` `NEW`
1. [孙颖莎不听不听和尚念经](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E4%B8%8D%E5%90%AC%E4%B8%8D%E5%90%AC%E5%92%8C%E5%B0%9A%E5%BF%B5%E7%BB%8F%23) `495.3K 🔥` `NEW`
1. [孙颖莎完赛又去加练了](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E5%AE%8C%E8%B5%9B%E5%8F%88%E5%8E%BB%E5%8A%A0%E7%BB%83%E4%BA%86%23) `494.5K 🔥` `NEW`
1. [推进不动产登记跨省通办](https://s.weibo.com/weibo?q=%23%E6%8E%A8%E8%BF%9B%E4%B8%8D%E5%8A%A8%E4%BA%A7%E7%99%BB%E8%AE%B0%E8%B7%A8%E7%9C%81%E9%80%9A%E5%8A%9E%23) `494.3K 🔥` `NEW`
1. [为何很多肾病发现就是晚期](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BD%95%E5%BE%88%E5%A4%9A%E8%82%BE%E7%97%85%E5%8F%91%E7%8E%B0%E5%B0%B1%E6%98%AF%E6%99%9A%E6%9C%9F%23) `492.9K 🔥` `NEW`
1. [伊朗调整战略](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%B0%83%E6%95%B4%E6%88%98%E7%95%A5%23) `492.3K 🔥` `NEW`
1. [当小狗察觉到人类生气后](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%B0%8F%E7%8B%97%E5%AF%9F%E8%A7%89%E5%88%B0%E4%BA%BA%E7%B1%BB%E7%94%9F%E6%B0%94%E5%90%8E%23) `489.0K 🔥` `NEW`
1. [建议禁止流量月底清零](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%A6%81%E6%AD%A2%E6%B5%81%E9%87%8F%E6%9C%88%E5%BA%95%E6%B8%85%E9%9B%B6%23) `735.1K 🔥` `+49%`
1. [伊朗用最强导弹专打以色列](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%94%A8%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%BC%B9%E4%B8%93%E6%89%93%E4%BB%A5%E8%89%B2%E5%88%97%23) `584.1K 🔥` `+152%`
1. [揭秘周冠宇3D新战术 (Revealing Zhou Guanyu’s new 3D tactics)](https://s.weibo.com/weibo?q=%23%E6%8F%AD%E7%A7%98%E5%91%A8%E5%86%A0%E5%AE%873D%E6%96%B0%E6%88%98%E6%9C%AF%23) `580.1K 🔥` `+49%`
1. [易梦体质](https://s.weibo.com/weibo?q=%23%E6%98%93%E6%A2%A6%E4%BD%93%E8%B4%A8%23) `555.2K 🔥` `+138%`
1. [爆剧 养老剧 (Explosive Drama Elder Care Drama)](https://s.weibo.com/weibo?q=%23%E7%88%86%E5%89%A7%20%E5%85%BB%E8%80%81%E5%89%A7%23) `552.1K 🔥` `+459%`
1. [张凌赫被田曦薇摸耳朵的反应](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%A2%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%91%B8%E8%80%B3%E6%9C%B5%E7%9A%84%E5%8F%8D%E5%BA%94%23) `505.9K 🔥` `+84%`
1. [辛辛苦苦考了一份辛辛苦苦的工作 (After working hard, I got a hard-working job.)](https://s.weibo.com/weibo?q=%23%E8%BE%9B%E8%BE%9B%E8%8B%A6%E8%8B%A6%E8%80%83%E4%BA%86%E4%B8%80%E4%BB%BD%E8%BE%9B%E8%BE%9B%E8%8B%A6%E8%8B%A6%E7%9A%84%E5%B7%A5%E4%BD%9C%23) `504.7K 🔥` `+89%`
1. [浪姐7 (Lang Jie 7)](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%907%23) `503.9K 🔥` `+121%`
1. [杨幂把海洋穿身上了](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%8A%8A%E6%B5%B7%E6%B4%8B%E7%A9%BF%E8%BA%AB%E4%B8%8A%E4%BA%86%23) `502.7K 🔥` `+126%`
1. [改剧本 加流量演员](https://s.weibo.com/weibo?q=%23%E6%94%B9%E5%89%A7%E6%9C%AC%20%E5%8A%A0%E6%B5%81%E9%87%8F%E6%BC%94%E5%91%98%23) `502.2K 🔥` `+154%`
1. [吃全麦面包减肥的人天塌了](https://s.weibo.com/weibo?q=%23%E5%90%83%E5%85%A8%E9%BA%A6%E9%9D%A2%E5%8C%85%E5%87%8F%E8%82%A5%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `501.7K 🔥` `+132%`
1. [腾讯视频修改逐玉战报 (Tencent Video Modifies Zhuyu Battle Report)](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91%E4%BF%AE%E6%94%B9%E9%80%90%E7%8E%89%E6%88%98%E6%8A%A5%23) `500.9K 🔥` `+190%`
1. [儿媳一怀孕婆婆立马报班学月嫂](https://s.weibo.com/weibo?q=%23%E5%84%BF%E5%AA%B3%E4%B8%80%E6%80%80%E5%AD%95%E5%A9%86%E5%A9%86%E7%AB%8B%E9%A9%AC%E6%8A%A5%E7%8F%AD%E5%AD%A6%E6%9C%88%E5%AB%82%23) `500.2K 🔥` `+188%`
1. [张凌赫王玉雯 刺棠](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%8E%8B%E7%8E%89%E9%9B%AF%20%E5%88%BA%E6%A3%A0%23) `499.2K 🔥` `+128%`
1. [微信视频通话终于有锁定功能了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%A7%86%E9%A2%91%E9%80%9A%E8%AF%9D%E7%BB%88%E4%BA%8E%E6%9C%89%E9%94%81%E5%AE%9A%E5%8A%9F%E8%83%BD%E4%BA%86%23) `498.4K 🔥` `+267%`
1. [逐玉 业内](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E4%B8%9A%E5%86%85%23) `497.7K 🔥` `+215%`
1. [熊 这辈子吃的最贵的苹果](https://s.weibo.com/weibo?q=%23%E7%86%8A%20%E8%BF%99%E8%BE%88%E5%AD%90%E5%90%83%E7%9A%84%E6%9C%80%E8%B4%B5%E7%9A%84%E8%8B%B9%E6%9E%9C%23) `493.6K 🔥` `+89%`
1. [王濛官宣参加浪姐7 (Wang Meng officially announced to participate in Sister Lang 7)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E5%AE%98%E5%AE%A3%E5%8F%82%E5%8A%A0%E6%B5%AA%E5%A7%907%23) `493.2K 🔥` `+156%`
1. [王天辰回应生李昀锐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%E5%9B%9E%E5%BA%94%E7%94%9F%E6%9D%8E%E6%98%80%E9%94%90%23) `491.8K 🔥` `+307%`
1. [姐妹俩互用化妆品双双查出肾病 (Two sisters were diagnosed with kidney disease after using cosmetics on each other)](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A6%B9%E4%BF%A9%E4%BA%92%E7%94%A8%E5%8C%96%E5%A6%86%E5%93%81%E5%8F%8C%E5%8F%8C%E6%9F%A5%E5%87%BA%E8%82%BE%E7%97%85%23) `490.7K 🔥` `+388%`
1. [BFX下路回应Bin](https://s.weibo.com/weibo?q=%23BFX%E4%B8%8B%E8%B7%AF%E5%9B%9E%E5%BA%94Bin%23) `490.3K 🔥` `+477%`
1. [逐玉破万 经纪人亲一个](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%A0%B4%E4%B8%87%20%E7%BB%8F%E7%BA%AA%E4%BA%BA%E4%BA%B2%E4%B8%80%E4%B8%AA%23) `489.9K 🔥` `+353%`
1. [十四届全国人大四次会议闭幕会](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E9%97%AD%E5%B9%95%E4%BC%9A%23) `1.0M 🔥`
1. [3月12日两会日程 (Agenda for the two sessions on March 12)](https://s.weibo.com/weibo?q=%233%E6%9C%8812%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%23) `597.3K 🔥`
1. [首批能活到1000岁的人或已出生](https://s.weibo.com/weibo?q=%23%E9%A6%96%E6%89%B9%E8%83%BD%E6%B4%BB%E5%88%B01000%E5%B2%81%E7%9A%84%E4%BA%BA%E6%88%96%E5%B7%B2%E5%87%BA%E7%94%9F%23) `592.1K 🔥`
1. [第3场部长通道 (Session 3 Ministerial Channel)](https://s.weibo.com/weibo?q=%23%E7%AC%AC3%E5%9C%BA%E9%83%A8%E9%95%BF%E9%80%9A%E9%81%93%23) `591.5K 🔥`
1. [镖人 第二部](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E7%AC%AC%E4%BA%8C%E9%83%A8%23) `577.8K 🔥`
1. [表决通过政府工作报告](https://s.weibo.com/weibo?q=%23%E8%A1%A8%E5%86%B3%E9%80%9A%E8%BF%87%E6%94%BF%E5%BA%9C%E5%B7%A5%E4%BD%9C%E6%8A%A5%E5%91%8A%23) `560.8K 🔥`
1. [十五五规划纲要表决通过](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E7%BA%B2%E8%A6%81%E8%A1%A8%E5%86%B3%E9%80%9A%E8%BF%87%23) `544.5K 🔥`
1. [大学生4个馒头卖了30000元](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F4%E4%B8%AA%E9%A6%92%E5%A4%B4%E5%8D%96%E4%BA%8630000%E5%85%83%23) `506.5K 🔥`
1. [多邻国绿鸟 离职 (Duolingo Green Bird resigned)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E9%82%BB%E5%9B%BD%E7%BB%BF%E9%B8%9F%20%E7%A6%BB%E8%81%8C%23) `505.5K 🔥`
1. [安理会决议要求伊朗停止打海湾国家 (Security Council resolution calls on Iran to stop attacking Gulf countries)](https://s.weibo.com/weibo?q=%23%E5%AE%89%E7%90%86%E4%BC%9A%E5%86%B3%E8%AE%AE%E8%A6%81%E6%B1%82%E4%BC%8A%E6%9C%97%E5%81%9C%E6%AD%A2%E6%89%93%E6%B5%B7%E6%B9%BE%E5%9B%BD%E5%AE%B6%23) `491.0K 🔥`
1. [女孩回老家把祖屋改造成雨林民宿](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E5%9B%9E%E8%80%81%E5%AE%B6%E6%8A%8A%E7%A5%96%E5%B1%8B%E6%94%B9%E9%80%A0%E6%88%90%E9%9B%A8%E6%9E%97%E6%B0%91%E5%AE%BF%23) `573.2K 🔥` `-22%`

Updated at 2026-03-12 16:59:20

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
