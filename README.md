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

1. [公积金提取 (Provident fund withdrawal)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E7%A7%AF%E9%87%91%E6%8F%90%E5%8F%96%23) `563.2K 🔥` `NEW`
1. [Gemini五连绝世](https://s.weibo.com/weibo?q=%23Gemini%E4%BA%94%E8%BF%9E%E7%BB%9D%E4%B8%96%23) `559.0K 🔥` `NEW`
1. [JDG战胜KSG](https://s.weibo.com/weibo?q=%23JDG%E6%88%98%E8%83%9CKSG%23) `446.0K 🔥` `NEW`
1. [为农民哽咽发声代表接到多部委电话](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E5%86%9C%E6%B0%91%E5%93%BD%E5%92%BD%E5%8F%91%E5%A3%B0%E4%BB%A3%E8%A1%A8%E6%8E%A5%E5%88%B0%E5%A4%9A%E9%83%A8%E5%A7%94%E7%94%B5%E8%AF%9D%23) `376.4K 🔥` `NEW`
1. [建议建设大学版网络理政平台](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%BB%BA%E8%AE%BE%E5%A4%A7%E5%AD%A6%E7%89%88%E7%BD%91%E7%BB%9C%E7%90%86%E6%94%BF%E5%B9%B3%E5%8F%B0%23) `160.7K 🔥` `NEW`
1. [精灵黄lululemon发圈被炒到999元](https://s.weibo.com/weibo?q=%23%E7%B2%BE%E7%81%B5%E9%BB%84lululemon%E5%8F%91%E5%9C%88%E8%A2%AB%E7%82%92%E5%88%B0999%E5%85%83%23) `129.6K 🔥` `NEW`
1. [宁德时代创始人曾毓群个人分红81亿](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BE%B7%E6%97%B6%E4%BB%A3%E5%88%9B%E5%A7%8B%E4%BA%BA%E6%9B%BE%E6%AF%93%E7%BE%A4%E4%B8%AA%E4%BA%BA%E5%88%86%E7%BA%A281%E4%BA%BF%23) `118.6K 🔥` `NEW`
1. [别再对孩子说想开点了](https://s.weibo.com/weibo?q=%23%E5%88%AB%E5%86%8D%E5%AF%B9%E5%AD%A9%E5%AD%90%E8%AF%B4%E6%83%B3%E5%BC%80%E7%82%B9%E4%BA%86%23) `87.1K 🔥` `NEW`
1. [中国女篮vs马里女篮](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E7%AF%AEvs%E9%A9%AC%E9%87%8C%E5%A5%B3%E7%AF%AE%23) `87.0K 🔥` `NEW`
1. [日本部署远程导弹彻底撕下伪装](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E9%83%A8%E7%BD%B2%E8%BF%9C%E7%A8%8B%E5%AF%BC%E5%BC%B9%E5%BD%BB%E5%BA%95%E6%92%95%E4%B8%8B%E4%BC%AA%E8%A3%85%23) `86.9K 🔥` `NEW`
1. [上过班的才知道这有多幸福 (Only those who have worked know how happy this is)](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E8%BF%87%E7%8F%AD%E7%9A%84%E6%89%8D%E7%9F%A5%E9%81%93%E8%BF%99%E6%9C%89%E5%A4%9A%E5%B9%B8%E7%A6%8F%23) `86.3K 🔥` `NEW`
1. [张凌赫自己给自己加词](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%87%AA%E5%B7%B1%E7%BB%99%E8%87%AA%E5%B7%B1%E5%8A%A0%E8%AF%8D%23) `85.9K 🔥` `NEW`
1. [冯天薇说孙颖莎第一次就把自己赢了](https://s.weibo.com/weibo?q=%23%E5%86%AF%E5%A4%A9%E8%96%87%E8%AF%B4%E5%AD%99%E9%A2%96%E8%8E%8E%E7%AC%AC%E4%B8%80%E6%AC%A1%E5%B0%B1%E6%8A%8A%E8%87%AA%E5%B7%B1%E8%B5%A2%E4%BA%86%23) `85.7K 🔥` `NEW`
1. [无畏张飞八战八胜](https://s.weibo.com/weibo?q=%23%E6%97%A0%E7%95%8F%E5%BC%A0%E9%A3%9E%E5%85%AB%E6%88%98%E5%85%AB%E8%83%9C%23) `84.8K 🔥` `NEW`
1. [曝有国产手机大厂合作豆包AI手机](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%9C%89%E5%9B%BD%E4%BA%A7%E6%89%8B%E6%9C%BA%E5%A4%A7%E5%8E%82%E5%90%88%E4%BD%9C%E8%B1%86%E5%8C%85AI%E6%89%8B%E6%9C%BA%23) `84.5K 🔥` `NEW`
1. [委员回应年轻人天天熬夜行不行](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E5%9B%9E%E5%BA%94%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%A4%A9%E5%A4%A9%E7%86%AC%E5%A4%9C%E8%A1%8C%E4%B8%8D%E8%A1%8C%23) `1.0M 🔥` `+88%`
1. [吴昕在大侦探爆哭](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E5%9C%A8%E5%A4%A7%E4%BE%A6%E6%8E%A2%E7%88%86%E5%93%AD%23) `332.4K 🔥` `+122%`
1. [你更愿意喝9.9元还是30元的咖啡](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E6%9B%B4%E6%84%BF%E6%84%8F%E5%96%9D9.9%E5%85%83%E8%BF%98%E6%98%AF30%E5%85%83%E7%9A%84%E5%92%96%E5%95%A1%23) `153.5K 🔥` `+38%`
1. [前2月外贸交出提气答卷 (Foreign trade in the first two months handed over answers to improve the situation)](https://s.weibo.com/weibo?q=%23%E5%89%8D2%E6%9C%88%E5%A4%96%E8%B4%B8%E4%BA%A4%E5%87%BA%E6%8F%90%E6%B0%94%E7%AD%94%E5%8D%B7%23) `581.8K 🔥`
1. [全球最平整折叠屏OPPOFindN6 (OPPO Find N6, the world’s flattest folding screen)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E6%9C%80%E5%B9%B3%E6%95%B4%E6%8A%98%E5%8F%A0%E5%B1%8FOPPOFindN6%23) `580.9K 🔥`
1. [伊朗对美以发动38波攻击 (Iran launches 38 waves of attacks on the United States and Israel)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%B9%E7%BE%8E%E4%BB%A5%E5%8F%91%E5%8A%A838%E6%B3%A2%E6%94%BB%E5%87%BB%23) `464.7K 🔥`
1. [代表揣着的红色笔记本里记了啥](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E6%8F%A3%E7%9D%80%E7%9A%84%E7%BA%A2%E8%89%B2%E7%AC%94%E8%AE%B0%E6%9C%AC%E9%87%8C%E8%AE%B0%E4%BA%86%E5%95%A5%23) `409.0K 🔥`
1. [双人餐是需要两份主食饮料的](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E4%BA%BA%E9%A4%90%E6%98%AF%E9%9C%80%E8%A6%81%E4%B8%A4%E4%BB%BD%E4%B8%BB%E9%A3%9F%E9%A5%AE%E6%96%99%E7%9A%84%23) `224.1K 🔥`
1. [剑来 (The sword comes)](https://s.weibo.com/weibo?q=%23%E5%89%91%E6%9D%A5%23) `161.1K 🔥`
1. [日本大阪一马路长出15米高巨型水管](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%A4%A7%E9%98%AA%E4%B8%80%E9%A9%AC%E8%B7%AF%E9%95%BF%E5%87%BA15%E7%B1%B3%E9%AB%98%E5%B7%A8%E5%9E%8B%E6%B0%B4%E7%AE%A1%23) `125.3K 🔥`
1. [我们的少年时代2开通官微 (Our Boyhood 2 launches official WeChat account)](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%E5%BC%80%E9%80%9A%E5%AE%98%E5%BE%AE%23) `123.5K 🔥`
1. [梁朝伟走势](https://s.weibo.com/weibo?q=%23%E6%A2%81%E6%9C%9D%E4%BC%9F%E8%B5%B0%E5%8A%BF%23) `121.9K 🔥`
1. [黄金涨价劝退不了消费者 (Gold price increase cannot dissuade consumers)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E6%B6%A8%E4%BB%B7%E5%8A%9D%E9%80%80%E4%B8%8D%E4%BA%86%E6%B6%88%E8%B4%B9%E8%80%85%23) `121.4K 🔥`
1. [逐玉 说闲话](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E8%AF%B4%E9%97%B2%E8%AF%9D%23) `97.1K 🔥`
1. [国防部回应日本部署远程导弹 (Ministry of National Defense responds to Japan's deployment of long-range missiles)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%98%B2%E9%83%A8%E5%9B%9E%E5%BA%94%E6%97%A5%E6%9C%AC%E9%83%A8%E7%BD%B2%E8%BF%9C%E7%A8%8B%E5%AF%BC%E5%BC%B9%23) `754.1K 🔥` `-26%`
1. [银行员工抢救23万元火烧币](https://s.weibo.com/weibo?q=%23%E9%93%B6%E8%A1%8C%E5%91%98%E5%B7%A5%E6%8A%A2%E6%95%9123%E4%B8%87%E5%85%83%E7%81%AB%E7%83%A7%E5%B8%81%23) `419.7K 🔥` `-27%`
1. [逐玉追剧团](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%BF%BD%E5%89%A7%E5%9B%A2%23) `344.9K 🔥` `-29%`
1. [MiuMiu](https://s.weibo.com/weibo?q=%23MiuMiu%23) `270.6K 🔥` `-40%`
1. [逐玉 头纱](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%A4%B4%E7%BA%B1%23) `256.5K 🔥` `-44%`
1. [慕慕昭昭大婚](https://s.weibo.com/weibo?q=%23%E6%85%95%E6%85%95%E6%98%AD%E6%98%AD%E5%A4%A7%E5%A9%9A%23) `253.4K 🔥` `-36%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `204.5K 🔥` `-54%`
1. [JDG对战KSG](https://s.weibo.com/weibo?q=%23JDG%E5%AF%B9%E6%88%98KSG%23) `178.7K 🔥` `-36%`
1. [公积金改革大潮真的来了 (The tide of provident fund reform is really coming)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E7%A7%AF%E9%87%91%E6%94%B9%E9%9D%A9%E5%A4%A7%E6%BD%AE%E7%9C%9F%E7%9A%84%E6%9D%A5%E4%BA%86%23) `158.5K 🔥` `-26%`
1. [不二之臣 (The best minister)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BA%8C%E4%B9%8B%E8%87%A3%23) `156.8K 🔥` `-26%`
1. [建议允许60岁以上农民工继续务工](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%85%81%E8%AE%B860%E5%B2%81%E4%BB%A5%E4%B8%8A%E5%86%9C%E6%B0%91%E5%B7%A5%E7%BB%A7%E7%BB%AD%E5%8A%A1%E5%B7%A5%23) `155.1K 🔥` `-62%`
1. [取微信名要慎重 (Be careful when choosing a WeChat name)](https://s.weibo.com/weibo?q=%23%E5%8F%96%E5%BE%AE%E4%BF%A1%E5%90%8D%E8%A6%81%E6%85%8E%E9%87%8D%23) `152.5K 🔥` `-27%`
1. [入职大疆1个月被发了5次钱](https://s.weibo.com/weibo?q=%23%E5%85%A5%E8%81%8C%E5%A4%A7%E7%96%861%E4%B8%AA%E6%9C%88%E8%A2%AB%E5%8F%91%E4%BA%865%E6%AC%A1%E9%92%B1%23) `128.9K 🔥` `-23%`
1. [伊朗总统之子称最高领袖平安](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E4%B9%8B%E5%AD%90%E7%A7%B0%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E5%B9%B3%E5%AE%89%23) `128.4K 🔥` `-72%`
1. [蔡猛说王曼昱后续或将暂停比赛](https://s.weibo.com/weibo?q=%23%E8%94%A1%E7%8C%9B%E8%AF%B4%E7%8E%8B%E6%9B%BC%E6%98%B1%E5%90%8E%E7%BB%AD%E6%88%96%E5%B0%86%E6%9A%82%E5%81%9C%E6%AF%94%E8%B5%9B%23) `101.8K 🔥` `-57%`
1. [华师大回应师范本科不再输出教师](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E5%B8%88%E5%A4%A7%E5%9B%9E%E5%BA%94%E5%B8%88%E8%8C%83%E6%9C%AC%E7%A7%91%E4%B8%8D%E5%86%8D%E8%BE%93%E5%87%BA%E6%95%99%E5%B8%88%23) `96.2K 🔥` `-87%`
1. [80元Lululemon发圈卖断货](https://s.weibo.com/weibo?q=%2380%E5%85%83Lululemon%E5%8F%91%E5%9C%88%E5%8D%96%E6%96%AD%E8%B4%A7%23) `92.7K 🔥` `-48%`
1. [中餐厅10网传阵容](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E9%A4%90%E5%8E%8510%E7%BD%91%E4%BC%A0%E9%98%B5%E5%AE%B9%23) `86.7K 🔥` `-26%`
1. [七部云合破40%的剧](https://s.weibo.com/weibo?q=%23%E4%B8%83%E9%83%A8%E4%BA%91%E5%90%88%E7%A0%B440%25%E7%9A%84%E5%89%A7%23) `86.2K 🔥` `-32%`
1. [种地吧4种地日记](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A74%E7%A7%8D%E5%9C%B0%E6%97%A5%E8%AE%B0%23) `85.3K 🔥` `-84%`
1. [金价杀疯了山东直接去地下2700米挖 (The price of gold is so crazy that Shandong went directly to dig 2,700 meters underground.)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%9D%80%E7%96%AF%E4%BA%86%E5%B1%B1%E4%B8%9C%E7%9B%B4%E6%8E%A5%E5%8E%BB%E5%9C%B0%E4%B8%8B2700%E7%B1%B3%E6%8C%96%23) `85.2K 🔥` `-27%`
1. [AG 首发](https://s.weibo.com/weibo?q=%23AG%20%E9%A6%96%E5%8F%91%23) `84.7K 🔥` `-24%`

Updated at 2026-03-11 20:35:37

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
