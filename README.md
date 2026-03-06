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

1. [十五五规划新指标新看点 (New indicators and new highlights of the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E6%96%B0%E6%8C%87%E6%A0%87%E6%96%B0%E7%9C%8B%E7%82%B9%23) `644.6K 🔥` `NEW`
1. [六大未来产业有哪些](https://s.weibo.com/weibo?q=%23%E5%85%AD%E5%A4%A7%E6%9C%AA%E6%9D%A5%E4%BA%A7%E4%B8%9A%E6%9C%89%E5%93%AA%E4%BA%9B%23) `629.6K 🔥` `NEW`
1. [医生辟谣3个减肥谣言](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E8%BE%9F%E8%B0%A33%E4%B8%AA%E5%87%8F%E8%82%A5%E8%B0%A3%E8%A8%80%23) `590.8K 🔥` `NEW`
1. [委员称培训隐形变异侵蚀教育公平](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E7%A7%B0%E5%9F%B9%E8%AE%AD%E9%9A%90%E5%BD%A2%E5%8F%98%E5%BC%82%E4%BE%B5%E8%9A%80%E6%95%99%E8%82%B2%E5%85%AC%E5%B9%B3%23) `542.7K 🔥` `NEW`
1. [伊朗打击伊拉克库尔德地区](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%89%93%E5%87%BB%E4%BC%8A%E6%8B%89%E5%85%8B%E5%BA%93%E5%B0%94%E5%BE%B7%E5%9C%B0%E5%8C%BA%23) `528.1K 🔥` `NEW`
1. [逐玉腾讯爱奇艺热度差距](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%85%BE%E8%AE%AF%E7%88%B1%E5%A5%87%E8%89%BA%E7%83%AD%E5%BA%A6%E5%B7%AE%E8%B7%9D%23) `465.4K 🔥` `NEW`
1. [逐玉假洞房比真的还涩](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%81%87%E6%B4%9E%E6%88%BF%E6%AF%94%E7%9C%9F%E7%9A%84%E8%BF%98%E6%B6%A9%23) `238.9K 🔥` `NEW`
1. [张予曦毕雯珺 综艺](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BA%88%E6%9B%A6%E6%AF%95%E9%9B%AF%E7%8F%BA%20%E7%BB%BC%E8%89%BA%23) `221.2K 🔥` `NEW`
1. [代表说70岁以上老人真干不动农活了](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B470%E5%B2%81%E4%BB%A5%E4%B8%8A%E8%80%81%E4%BA%BA%E7%9C%9F%E5%B9%B2%E4%B8%8D%E5%8A%A8%E5%86%9C%E6%B4%BB%E4%BA%86%23) `180.2K 🔥` `NEW`
1. [林俊杰空降逐玉直播间](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E7%A9%BA%E9%99%8D%E9%80%90%E7%8E%89%E7%9B%B4%E6%92%AD%E9%97%B4%23) `180.1K 🔥` `NEW`
1. [逐玉 曾庆杰 (Zhuyu Zeng Qingjie)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E6%9B%BE%E5%BA%86%E6%9D%B0%23) `144.1K 🔥` `NEW`
1. [周云杰出道的感觉又回来了](https://s.weibo.com/weibo?q=%23%E5%91%A8%E4%BA%91%E6%9D%B0%E5%87%BA%E9%81%93%E7%9A%84%E6%84%9F%E8%A7%89%E5%8F%88%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `119.5K 🔥` `NEW`
1. [魏建军就海报抄袭道歉](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E5%BB%BA%E5%86%9B%E5%B0%B1%E6%B5%B7%E6%8A%A5%E6%8A%84%E8%A2%AD%E9%81%93%E6%AD%89%23) `101.3K 🔥` `NEW`
1. [请全球通缉发明这个水枪的天才](https://s.weibo.com/weibo?q=%23%E8%AF%B7%E5%85%A8%E7%90%83%E9%80%9A%E7%BC%89%E5%8F%91%E6%98%8E%E8%BF%99%E4%B8%AA%E6%B0%B4%E6%9E%AA%E7%9A%84%E5%A4%A9%E6%89%8D%23) `93.9K 🔥` `NEW`
1. [建议减轻教师非教育教学负担](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%87%8F%E8%BD%BB%E6%95%99%E5%B8%88%E9%9D%9E%E6%95%99%E8%82%B2%E6%95%99%E5%AD%A6%E8%B4%9F%E6%8B%85%23) `88.2K 🔥` `NEW`
1. [OpenClaw爆火](https://s.weibo.com/weibo?q=%23OpenClaw%E7%88%86%E7%81%AB%23) `85.8K 🔥` `NEW`
1. [建议家长放弃竞争式教育观念](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%AE%B6%E9%95%BF%E6%94%BE%E5%BC%83%E7%AB%9E%E4%BA%89%E5%BC%8F%E6%95%99%E8%82%B2%E8%A7%82%E5%BF%B5%23) `85.2K 🔥` `NEW`
1. [黄景瑜孙千 明川有知夏](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E5%AD%99%E5%8D%83%20%E6%98%8E%E5%B7%9D%E6%9C%89%E7%9F%A5%E5%A4%8F%23) `83.9K 🔥` `NEW`
1. [委员说去机场比坐飞机时间还长](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E8%AF%B4%E5%8E%BB%E6%9C%BA%E5%9C%BA%E6%AF%94%E5%9D%90%E9%A3%9E%E6%9C%BA%E6%97%B6%E9%97%B4%E8%BF%98%E9%95%BF%23) `71.4K 🔥` `NEW`
1. [生命树](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%23) `1.1M 🔥` `+1097%`
1. [比亚迪闪充5分好9分饱3分寒 (BYD flash charge: 5 points good, 9 points full, 3 points cold)](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%E9%97%AA%E5%85%855%E5%88%86%E5%A5%BD9%E5%88%86%E9%A5%B13%E5%88%86%E5%AF%92%23) `640.1K 🔥` `+68%`
1. [广西壮族自治区党委书记陈刚亮家丑 (Chen Gangliang, Secretary of the Party Committee of Guangxi Zhuang Autonomous Region, has a family scandal)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E8%A5%BF%E5%A3%AE%E6%97%8F%E8%87%AA%E6%B2%BB%E5%8C%BA%E5%85%9A%E5%A7%94%E4%B9%A6%E8%AE%B0%E9%99%88%E5%88%9A%E4%BA%AE%E5%AE%B6%E4%B8%91%23) `637.7K 🔥` `+378%`
1. [伊朗导弹袭击以色列最大机场 (Iranian missile attacks Israel's largest airport)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%E4%BB%A5%E8%89%B2%E5%88%97%E6%9C%80%E5%A4%A7%E6%9C%BA%E5%9C%BA%23) `613.4K 🔥` `+22%`
1. [破5亿播放AI短剧成本仅3000](https://s.weibo.com/weibo?q=%23%E7%A0%B45%E4%BA%BF%E6%92%AD%E6%94%BEAI%E7%9F%AD%E5%89%A7%E6%88%90%E6%9C%AC%E4%BB%853000%23) `586.5K 🔥` `+152%`
1. [千问妇女节活动](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%A6%87%E5%A5%B3%E8%8A%82%E6%B4%BB%E5%8A%A8%23) `578.3K 🔥` `+205%`
1. [预计今年GDP增量超6万亿元 (GDP growth this year is expected to exceed 6 trillion yuan)](https://s.weibo.com/weibo?q=%23%E9%A2%84%E8%AE%A1%E4%BB%8A%E5%B9%B4GDP%E5%A2%9E%E9%87%8F%E8%B6%856%E4%B8%87%E4%BA%BF%E5%85%83%23) `562.3K 🔥` `+40%`
1. [TES上报Naiyou不正当行为 (TES reports Naiyou’s improper behavior)](https://s.weibo.com/weibo?q=%23TES%E4%B8%8A%E6%8A%A5Naiyou%E4%B8%8D%E6%AD%A3%E5%BD%93%E8%A1%8C%E4%B8%BA%23) `277.5K 🔥` `+49%`
1. [逐玉开播 (Zhuyu starts broadcasting)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%80%E6%92%AD%23) `265.6K 🔥` `+45%`
1. [369 小丑了](https://s.weibo.com/weibo?q=%23369%20%E5%B0%8F%E4%B8%91%E4%BA%86%23) `245.5K 🔥` `+31%`
1. [女子翻老盒子内藏十几张清朝地契](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%BF%BB%E8%80%81%E7%9B%92%E5%AD%90%E5%86%85%E8%97%8F%E5%8D%81%E5%87%A0%E5%BC%A0%E6%B8%85%E6%9C%9D%E5%9C%B0%E5%A5%91%23) `179.7K 🔥` `+52%`
1. [白鹿跳水了 (The white deer dives)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E8%B7%B3%E6%B0%B4%E4%BA%86%23) `118.1K 🔥` `+30%`
1. [第五人格](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%BA%94%E4%BA%BA%E6%A0%BC%23) `182.2K 🔥`
1. [女子常熬夜上班压力大查出3种癌](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%B8%B8%E7%86%AC%E5%A4%9C%E4%B8%8A%E7%8F%AD%E5%8E%8B%E5%8A%9B%E5%A4%A7%E6%9F%A5%E5%87%BA3%E7%A7%8D%E7%99%8C%23) `155.0K 🔥`
1. [唐家三少口碑因晋江女频翻盘 (The reputation of the third young master of the Tang family has been reversed due to Jinjiang female pornographic videos)](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%AE%B6%E4%B8%89%E5%B0%91%E5%8F%A3%E7%A2%91%E5%9B%A0%E6%99%8B%E6%B1%9F%E5%A5%B3%E9%A2%91%E7%BF%BB%E7%9B%98%23) `103.4K 🔥`
1. [美以袭击已致1332名伊朗人死亡 (US-Israeli strikes kill 1,332 Iranians)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E8%A2%AD%E5%87%BB%E5%B7%B2%E8%87%B41332%E5%90%8D%E4%BC%8A%E6%9C%97%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `99.7K 🔥`
1. [妇女节 放假](https://s.weibo.com/weibo?q=%23%E5%A6%87%E5%A5%B3%E8%8A%82%20%E6%94%BE%E5%81%87%23) `782.5K 🔥` `-26%`
1. [逐玉热度](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%83%AD%E5%BA%A6%23) `528.7K 🔥` `-46%`
1. [滨寿司员工餐 (Hamazushi staff meal)](https://s.weibo.com/weibo?q=%23%E6%BB%A8%E5%AF%BF%E5%8F%B8%E5%91%98%E5%B7%A5%E9%A4%90%23) `142.5K 🔥` `-21%`
1. [双一流高校本科扩招10万人以上](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E4%B8%80%E6%B5%81%E9%AB%98%E6%A0%A1%E6%9C%AC%E7%A7%91%E6%89%A9%E6%8B%9B10%E4%B8%87%E4%BA%BA%E4%BB%A5%E4%B8%8A%23) `127.9K 🔥` `-88%`
1. [剩半截身体的鱼经主人照顾奇迹康复 (The fish with half of its body miraculously recovered after being cared for by its owner)](https://s.weibo.com/weibo?q=%23%E5%89%A9%E5%8D%8A%E6%88%AA%E8%BA%AB%E4%BD%93%E7%9A%84%E9%B1%BC%E7%BB%8F%E4%B8%BB%E4%BA%BA%E7%85%A7%E9%A1%BE%E5%A5%87%E8%BF%B9%E5%BA%B7%E5%A4%8D%23) `123.0K 🔥` `-25%`
1. [罗意威大秀](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%84%8F%E5%A8%81%E5%A4%A7%E7%A7%80%23) `116.6K 🔥` `-36%`
1. [伊朗一儿童游乐场遭袭 (A children's playground in Iran was attacked)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%84%BF%E7%AB%A5%E6%B8%B8%E4%B9%90%E5%9C%BA%E9%81%AD%E8%A2%AD%23) `114.2K 🔥` `-35%`
1. [专家建议女性尽早做生育力评估](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E5%BB%BA%E8%AE%AE%E5%A5%B3%E6%80%A7%E5%B0%BD%E6%97%A9%E5%81%9A%E7%94%9F%E8%82%B2%E5%8A%9B%E8%AF%84%E4%BC%B0%23) `107.2K 🔥` `-37%`
1. [女子频繁迟到做事拖沓被确诊ADHD](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E9%A2%91%E7%B9%81%E8%BF%9F%E5%88%B0%E5%81%9A%E4%BA%8B%E6%8B%96%E6%B2%93%E8%A2%AB%E7%A1%AE%E8%AF%8AADHD%23) `83.2K 🔥` `-39%`
1. [金智秀新剧开播 (Kim Ji Soo’s new drama starts airing)](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%99%BA%E7%A7%80%E6%96%B0%E5%89%A7%E5%BC%80%E6%92%AD%23) `83.1K 🔥` `-25%`
1. [建议艾滋感染者1个月内告知配偶](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E8%89%BE%E6%BB%8B%E6%84%9F%E6%9F%93%E8%80%851%E4%B8%AA%E6%9C%88%E5%86%85%E5%91%8A%E7%9F%A5%E9%85%8D%E5%81%B6%23) `82.5K 🔥` `-52%`
1. [董璇张维伊婚礼策划倒闭了 (Dong Xuan and Zhang Weiyi’s wedding planning went bankrupt)](https://s.weibo.com/weibo?q=%23%E8%91%A3%E7%92%87%E5%BC%A0%E7%BB%B4%E4%BC%8A%E5%A9%9A%E7%A4%BC%E7%AD%96%E5%88%92%E5%80%92%E9%97%AD%E4%BA%86%23) `78.0K 🔥` `-53%`
1. [王楚钦孙颖莎缺席WTT太原挑战赛](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%AD%99%E9%A2%96%E8%8E%8E%E7%BC%BA%E5%B8%ADWTT%E5%A4%AA%E5%8E%9F%E6%8C%91%E6%88%98%E8%B5%9B%23) `72.9K 🔥` `-93%`
1. [钎九不清冰合照](https://s.weibo.com/weibo?q=%23%E9%92%8E%E4%B9%9D%E4%B8%8D%E6%B8%85%E5%86%B0%E5%90%88%E7%85%A7%23) `72.0K 🔥` `-30%`
1. [王一博巴黎时装周大片](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E5%A4%A7%E7%89%87%23) `69.6K 🔥` `-57%`
1. [喜人真的升咖了](https://s.weibo.com/weibo?q=%23%E5%96%9C%E4%BA%BA%E7%9C%9F%E7%9A%84%E5%8D%87%E5%92%96%E4%BA%86%23) `68.7K 🔥` `-45%`

Updated at 2026-03-06 21:17:17

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
