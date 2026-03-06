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

1. [伊朗大使说250年怎能挑衅3000年历史 (Iranian Ambassador said how can 250 years provoke 3,000 years of history?)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%A7%E4%BD%BF%E8%AF%B4250%E5%B9%B4%E6%80%8E%E8%83%BD%E6%8C%91%E8%A1%853000%E5%B9%B4%E5%8E%86%E5%8F%B2%23) `561.8K 🔥` `NEW`
1. [乒协会尊重樊振东意愿全力保障](https://s.weibo.com/weibo?q=%23%E4%B9%92%E5%8D%8F%E4%BC%9A%E5%B0%8A%E9%87%8D%E6%A8%8A%E6%8C%AF%E4%B8%9C%E6%84%8F%E6%84%BF%E5%85%A8%E5%8A%9B%E4%BF%9D%E9%9A%9C%23) `554.4K 🔥` `NEW`
1. [逐玉 任豪](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E4%BB%BB%E8%B1%AA%23) `196.0K 🔥` `NEW`
1. [曾庆杰 升咖](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E5%BA%86%E6%9D%B0%20%E5%8D%87%E5%92%96%23) `176.3K 🔥` `NEW`
1. [伊朗外长说对抗美以已是胜利](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E8%AF%B4%E5%AF%B9%E6%8A%97%E7%BE%8E%E4%BB%A5%E5%B7%B2%E6%98%AF%E8%83%9C%E5%88%A9%23) `156.2K 🔥` `NEW`
1. [4AM单局13淘汰吃鸡](https://s.weibo.com/weibo?q=%234AM%E5%8D%95%E5%B1%8013%E6%B7%98%E6%B1%B0%E5%90%83%E9%B8%A1%23) `129.8K 🔥` `NEW`
1. [花呗等网络消费信贷可享受贴息](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%91%97%E7%AD%89%E7%BD%91%E7%BB%9C%E6%B6%88%E8%B4%B9%E4%BF%A1%E8%B4%B7%E5%8F%AF%E4%BA%AB%E5%8F%97%E8%B4%B4%E6%81%AF%23) `114.1K 🔥` `NEW`
1. [真我](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%88%91%23) `113.2K 🔥` `NEW`
1. [逐玉 猪圈出神图](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%8C%AA%E5%9C%88%E5%87%BA%E7%A5%9E%E5%9B%BE%23) `106.9K 🔥` `NEW`
1. [穆祉丞新歌](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%E6%96%B0%E6%AD%8C%23) `106.0K 🔥` `NEW`
1. [最强大脑 (The most powerful brain)](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BC%BA%E5%A4%A7%E8%84%91%23) `77.9K 🔥` `NEW`
1. [代表说70岁以上老人真干不动农活了](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B470%E5%B2%81%E4%BB%A5%E4%B8%8A%E8%80%81%E4%BA%BA%E7%9C%9F%E5%B9%B2%E4%B8%8D%E5%8A%A8%E5%86%9C%E6%B4%BB%E4%BA%86%23) `1.1M 🔥` `+497%`
1. [曾舜晞浅香品牌代言人 (Zeng Shunxi Qianxiang brand spokesperson)](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E6%B5%85%E9%A6%99%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `581.8K 🔥` `+56%`
1. [张予曦毕雯珺 综艺](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BA%88%E6%9B%A6%E6%AF%95%E9%9B%AF%E7%8F%BA%20%E7%BB%BC%E8%89%BA%23) `391.6K 🔥` `+77%`
1. [请全球通缉发明这个水枪的天才](https://s.weibo.com/weibo?q=%23%E8%AF%B7%E5%85%A8%E7%90%83%E9%80%9A%E7%BC%89%E5%8F%91%E6%98%8E%E8%BF%99%E4%B8%AA%E6%B0%B4%E6%9E%AA%E7%9A%84%E5%A4%A9%E6%89%8D%23) `367.2K 🔥` `+291%`
1. [逐玉开播 (Zhuyu starts broadcasting)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%80%E6%92%AD%23) `367.0K 🔥` `+38%`
1. [魏建军就海报抄袭道歉](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E5%BB%BA%E5%86%9B%E5%B0%B1%E6%B5%B7%E6%8A%A5%E6%8A%84%E8%A2%AD%E9%81%93%E6%AD%89%23) `358.4K 🔥` `+254%`
1. [林俊杰空降逐玉直播间](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E7%A9%BA%E9%99%8D%E9%80%90%E7%8E%89%E7%9B%B4%E6%92%AD%E9%97%B4%23) `355.5K 🔥` `+97%`
1. [周云杰出道的感觉又回来了](https://s.weibo.com/weibo?q=%23%E5%91%A8%E4%BA%91%E6%9D%B0%E5%87%BA%E9%81%93%E7%9A%84%E6%84%9F%E8%A7%89%E5%8F%88%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `155.9K 🔥` `+30%`
1. [黄景瑜孙千 明川有知夏](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E5%AD%99%E5%8D%83%20%E6%98%8E%E5%B7%9D%E6%9C%89%E7%9F%A5%E5%A4%8F%23) `155.7K 🔥` `+86%`
1. [妇女节 放假](https://s.weibo.com/weibo?q=%23%E5%A6%87%E5%A5%B3%E8%8A%82%20%E6%94%BE%E5%81%87%23) `778.4K 🔥`
1. [十五五规划新指标新看点 (New indicators and new highlights of the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E6%96%B0%E6%8C%87%E6%A0%87%E6%96%B0%E7%9C%8B%E7%82%B9%23) `596.0K 🔥`
1. [六大未来产业有哪些](https://s.weibo.com/weibo?q=%23%E5%85%AD%E5%A4%A7%E6%9C%AA%E6%9D%A5%E4%BA%A7%E4%B8%9A%E6%9C%89%E5%93%AA%E4%BA%9B%23) `590.6K 🔥`
1. [伊朗导弹袭击以色列最大机场 (Iranian missile attacks Israel's largest airport)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%E4%BB%A5%E8%89%B2%E5%88%97%E6%9C%80%E5%A4%A7%E6%9C%BA%E5%9C%BA%23) `582.9K 🔥`
1. [破5亿播放AI短剧成本仅3000 (Exceeding 500 million, the cost of playing AI short drama is only 3,000)](https://s.weibo.com/weibo?q=%23%E7%A0%B45%E4%BA%BF%E6%92%AD%E6%94%BEAI%E7%9F%AD%E5%89%A7%E6%88%90%E6%9C%AC%E4%BB%853000%23) `581.2K 🔥`
1. [广西壮族自治区党委书记陈刚亮家丑 (Chen Gangliang, Secretary of the Party Committee of Guangxi Zhuang Autonomous Region, has a family scandal)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E8%A5%BF%E5%A3%AE%E6%97%8F%E8%87%AA%E6%B2%BB%E5%8C%BA%E5%85%9A%E5%A7%94%E4%B9%A6%E8%AE%B0%E9%99%88%E5%88%9A%E4%BA%AE%E5%AE%B6%E4%B8%91%23) `573.4K 🔥`
1. [预计今年GDP增量超6万亿元 (GDP growth this year is expected to exceed 6 trillion yuan)](https://s.weibo.com/weibo?q=%23%E9%A2%84%E8%AE%A1%E4%BB%8A%E5%B9%B4GDP%E5%A2%9E%E9%87%8F%E8%B6%856%E4%B8%87%E4%BA%BF%E5%85%83%23) `567.9K 🔥`
1. [千问妇女节活动](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%A6%87%E5%A5%B3%E8%8A%82%E6%B4%BB%E5%8A%A8%23) `565.1K 🔥`
1. [逐玉热度](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%83%AD%E5%BA%A6%23) `552.5K 🔥`
1. [TES上报Naiyou不正当行为 (TES reports Naiyou’s improper behavior)](https://s.weibo.com/weibo?q=%23TES%E4%B8%8A%E6%8A%A5Naiyou%E4%B8%8D%E6%AD%A3%E5%BD%93%E8%A1%8C%E4%B8%BA%23) `322.9K 🔥`
1. [逐玉假洞房比真的还涩](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%81%87%E6%B4%9E%E6%88%BF%E6%AF%94%E7%9C%9F%E7%9A%84%E8%BF%98%E6%B6%A9%23) `255.3K 🔥`
1. [369 小丑了](https://s.weibo.com/weibo?q=%23369%20%E5%B0%8F%E4%B8%91%E4%BA%86%23) `196.2K 🔥`
1. [第五人格](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%BA%94%E4%BA%BA%E6%A0%BC%23) `150.3K 🔥`
1. [双一流高校本科扩招10万人以上](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E4%B8%80%E6%B5%81%E9%AB%98%E6%A0%A1%E6%9C%AC%E7%A7%91%E6%89%A9%E6%8B%9B10%E4%B8%87%E4%BA%BA%E4%BB%A5%E4%B8%8A%23) `149.4K 🔥`
1. [女子翻老盒子内藏十几张清朝地契](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%BF%BB%E8%80%81%E7%9B%92%E5%AD%90%E5%86%85%E8%97%8F%E5%8D%81%E5%87%A0%E5%BC%A0%E6%B8%85%E6%9C%9D%E5%9C%B0%E5%A5%91%23) `149.2K 🔥`
1. [专家建议女性尽早做生育力评估](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E5%BB%BA%E8%AE%AE%E5%A5%B3%E6%80%A7%E5%B0%BD%E6%97%A9%E5%81%9A%E7%94%9F%E8%82%B2%E5%8A%9B%E8%AF%84%E4%BC%B0%23) `109.0K 🔥`
1. [白鹿跳水了 (The white deer dives)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E8%B7%B3%E6%B0%B4%E4%BA%86%23) `96.8K 🔥`
1. [金智秀新剧开播 (Kim Ji Soo’s new drama starts airing)](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%99%BA%E7%A7%80%E6%96%B0%E5%89%A7%E5%BC%80%E6%92%AD%23) `90.4K 🔥`
1. [女子频繁迟到做事拖沓被确诊ADHD](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E9%A2%91%E7%B9%81%E8%BF%9F%E5%88%B0%E5%81%9A%E4%BA%8B%E6%8B%96%E6%B2%93%E8%A2%AB%E7%A1%AE%E8%AF%8AADHD%23) `82.2K 🔥`
1. [美以袭击已致1332名伊朗人死亡 (US-Israeli strikes kill 1,332 Iranians)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E8%A2%AD%E5%87%BB%E5%B7%B2%E8%87%B41332%E5%90%8D%E4%BC%8A%E6%9C%97%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `79.9K 🔥`
1. [OpenClaw爆火 (OpenClaw goes viral)](https://s.weibo.com/weibo?q=%23OpenClaw%E7%88%86%E7%81%AB%23) `75.4K 🔥`
1. [建议减轻教师非教育教学负担](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%87%8F%E8%BD%BB%E6%95%99%E5%B8%88%E9%9D%9E%E6%95%99%E8%82%B2%E6%95%99%E5%AD%A6%E8%B4%9F%E6%8B%85%23) `75.3K 🔥`
1. [丰田铂智7预售权益价15.68万起 (Toyota Platinum 7 pre-sale price starts from 156,800)](https://s.weibo.com/weibo?q=%23%E4%B8%B0%E7%94%B0%E9%93%82%E6%99%BA7%E9%A2%84%E5%94%AE%E6%9D%83%E7%9B%8A%E4%BB%B715.68%E4%B8%87%E8%B5%B7%23) `595.5K 🔥` `-42%`
1. [生命树](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%23) `593.6K 🔥` `-45%`
1. [逐玉腾讯爱奇艺热度差距](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%85%BE%E8%AE%AF%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E5%BA%A6%E5%B7%AE%E8%B7%9D%23) `317.9K 🔥` `-32%`
1. [伊朗打击伊拉克库尔德地区](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%89%93%E5%87%BB%E4%BC%8A%E6%8B%89%E5%85%8B%E5%BA%93%E5%B0%94%E5%BE%B7%E5%9C%B0%E5%8C%BA%23) `305.1K 🔥` `-42%`
1. [女子常熬夜上班压力大查出3种癌](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%B8%B8%E7%86%AC%E5%A4%9C%E4%B8%8A%E7%8F%AD%E5%8E%8B%E5%8A%9B%E5%A4%A7%E6%9F%A5%E5%87%BA3%E7%A7%8D%E7%99%8C%23) `116.2K 🔥` `-25%`
1. [滨寿司员工餐 (Hamazushi staff meal)](https://s.weibo.com/weibo?q=%23%E6%BB%A8%E5%AF%BF%E5%8F%B8%E5%91%98%E5%B7%A5%E9%A4%90%23) `97.5K 🔥` `-32%`
1. [伊朗一儿童游乐场遭袭 (A children's playground in Iran was attacked)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%84%BF%E7%AB%A5%E6%B8%B8%E4%B9%90%E5%9C%BA%E9%81%AD%E8%A2%AD%23) `88.5K 🔥` `-23%`
1. [剩半截身体的鱼经主人照顾奇迹康复 (The fish with half of its body miraculously recovered after being cared for by its owner)](https://s.weibo.com/weibo?q=%23%E5%89%A9%E5%8D%8A%E6%88%AA%E8%BA%AB%E4%BD%93%E7%9A%84%E9%B1%BC%E7%BB%8F%E4%B8%BB%E4%BA%BA%E7%85%A7%E9%A1%BE%E5%A5%87%E8%BF%B9%E5%BA%B7%E5%A4%8D%23) `79.0K 🔥` `-36%`
1. [罗意威大秀](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%84%8F%E5%A8%81%E5%A4%A7%E7%A7%80%23) `78.4K 🔥` `-33%`

Updated at 2026-03-06 22:04:10

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
