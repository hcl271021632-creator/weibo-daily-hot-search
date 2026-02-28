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

1. [伊朗一小学遭袭40人死48人伤 (Attack on primary school in Iran kills 40, injures 48)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%B0%8F%E5%AD%A6%E9%81%AD%E8%A2%AD40%E4%BA%BA%E6%AD%BB48%E4%BA%BA%E4%BC%A4%23) `639.1K 🔥` `NEW`
1. [花海教练](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E6%B5%B7%E6%95%99%E7%BB%83%23) `129.2K 🔥` `NEW`
1. [小米YU7GT无伪装车谍照曝光](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3YU7GT%E6%97%A0%E4%BC%AA%E8%A3%85%E8%BD%A6%E8%B0%8D%E7%85%A7%E6%9B%9D%E5%85%89%23) `123.9K 🔥` `NEW`
1. [女孩天生爱笑被确诊为天使综合征](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E5%A4%A9%E7%94%9F%E7%88%B1%E7%AC%91%E8%A2%AB%E7%A1%AE%E8%AF%8A%E4%B8%BA%E5%A4%A9%E4%BD%BF%E7%BB%BC%E5%90%88%E5%BE%81%23) `121.3K 🔥` `NEW`
1. [无畏赵怀真辅助](https://s.weibo.com/weibo?q=%23%E6%97%A0%E7%95%8F%E8%B5%B5%E6%80%80%E7%9C%9F%E8%BE%85%E5%8A%A9%23) `118.8K 🔥` `NEW`
1. [伊朗公告发5点提醒](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%85%AC%E5%91%8A%E5%8F%915%E7%82%B9%E6%8F%90%E9%86%92%23) `115.4K 🔥` `NEW`
1. [桃黑黑 男神大赛别投我了](https://s.weibo.com/weibo?q=%23%E6%A1%83%E9%BB%91%E9%BB%91%20%E7%94%B7%E7%A5%9E%E5%A4%A7%E8%B5%9B%E5%88%AB%E6%8A%95%E6%88%91%E4%BA%86%23) `107.9K 🔥` `NEW`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `106.0K 🔥` `NEW`
1. [杭州两家动物园闭馆整改](https://s.weibo.com/weibo?q=%23%E6%9D%AD%E5%B7%9E%E4%B8%A4%E5%AE%B6%E5%8A%A8%E7%89%A9%E5%9B%AD%E9%97%AD%E9%A6%86%E6%95%B4%E6%94%B9%23) `101.4K 🔥` `NEW`
1. [TOP专辑 (TOP album)](https://s.weibo.com/weibo?q=%23TOP%E4%B8%93%E8%BE%91%23) `226.9K 🔥` `+49%`
1. [买3条金项链一夜赚超2.3万元](https://s.weibo.com/weibo?q=%23%E4%B9%B03%E6%9D%A1%E9%87%91%E9%A1%B9%E9%93%BE%E4%B8%80%E5%A4%9C%E8%B5%9A%E8%B6%852.3%E4%B8%87%E5%85%83%23) `156.2K 🔥` `+28%`
1. [王楚钦好好好我不挑战了 (Wang Chuqin, okay, okay, I won’t challenge you anymore)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%A5%BD%E5%A5%BD%E5%A5%BD%E6%88%91%E4%B8%8D%E6%8C%91%E6%88%98%E4%BA%86%23) `156.1K 🔥` `+31%`
1. [以色列宣布袭击伊朗 (Israel announces attack on Iran)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%AE%A3%E5%B8%83%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%23) `5.8M 🔥`
1. [山姆520元巧克力降到99元 (Sam’s 520 yuan chocolate reduced to 99 yuan)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86520%E5%85%83%E5%B7%A7%E5%85%8B%E5%8A%9B%E9%99%8D%E5%88%B099%E5%85%83%23) `1.4M 🔥`
1. [2025我国完成92次宇航发射 (my country completed 92 space launches in 2025)](https://s.weibo.com/weibo?q=%232025%E6%88%91%E5%9B%BD%E5%AE%8C%E6%88%9092%E6%AC%A1%E5%AE%87%E8%88%AA%E5%8F%91%E5%B0%84%23) `1.1M 🔥`
1. [伊朗正在打击美国军事基地 (Iran is attacking US military bases)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%9C%A8%E6%89%93%E5%87%BB%E7%BE%8E%E5%9B%BD%E5%86%9B%E4%BA%8B%E5%9F%BA%E5%9C%B0%23) `1.1M 🔥`
1. [大熊猫半半香果离世](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%86%8A%E7%8C%AB%E5%8D%8A%E5%8D%8A%E9%A6%99%E6%9E%9C%E7%A6%BB%E4%B8%96%23) `539.3K 🔥`
1. [赵露思自由点全球品牌代言人 (Zhao Lusi Freepoint Global Brand Spokesperson)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E9%9C%B2%E6%80%9D%E8%87%AA%E7%94%B1%E7%82%B9%E5%85%A8%E7%90%83%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `534.9K 🔥`
1. [伊朗启动大规模军事行动 (Iran launches large-scale military operation)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%AF%E5%8A%A8%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%86%9B%E4%BA%8B%E8%A1%8C%E5%8A%A8%23) `534.8K 🔥`
1. [美颜突然关掉吓得人一哆嗦](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E9%A2%9C%E7%AA%81%E7%84%B6%E5%85%B3%E6%8E%89%E5%90%93%E5%BE%97%E4%BA%BA%E4%B8%80%E5%93%86%E5%97%A6%23) `534.4K 🔥`
1. [陈熠4比0陈幸同 (Chen Yi 4 to 0 Chen Xingtong)](https://s.weibo.com/weibo?q=%23%E9%99%88%E7%86%A04%E6%AF%940%E9%99%88%E5%B9%B8%E5%90%8C%23) `529.2K 🔥`
1. [何凯文英语分数](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%87%AF%E6%96%87%E8%8B%B1%E8%AF%AD%E5%88%86%E6%95%B0%23) `527.8K 🔥`
1. [椰树广告 擦边](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E6%A0%91%E5%B9%BF%E5%91%8A%20%E6%93%A6%E8%BE%B9%23) `525.0K 🔥`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `522.3K 🔥`
1. [伊朗军方称总司令身体健康 (Iran's military says commander-in-chief is in good health)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%9B%E6%96%B9%E7%A7%B0%E6%80%BB%E5%8F%B8%E4%BB%A4%E8%BA%AB%E4%BD%93%E5%81%A5%E5%BA%B7%23) `472.2K 🔥`
1. [李治廷 十日终焉 (Li Zhiting The End of Ten Days)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%B2%BB%E5%BB%B7%20%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%23) `458.7K 🔥`
1. [伊朗袭击科威特美军基地 (Iran attacks US military base in Kuwait)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%E7%A7%91%E5%A8%81%E7%89%B9%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%23) `337.2K 🔥`
1. [前额叶损伤](https://s.weibo.com/weibo?q=%23%E5%89%8D%E9%A2%9D%E5%8F%B6%E6%8D%9F%E4%BC%A4%23) `303.6K 🔥`
1. [突然对1g黄金没概念了](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E5%AF%B91g%E9%BB%84%E9%87%91%E6%B2%A1%E6%A6%82%E5%BF%B5%E4%BA%86%23) `270.3K 🔥`
1. [伊朗一学校5名学生遇袭身亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%AD%A6%E6%A0%A15%E5%90%8D%E5%AD%A6%E7%94%9F%E9%81%87%E8%A2%AD%E8%BA%AB%E4%BA%A1%23) `232.7K 🔥`
1. [网传跑男铁了心要国民cp](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E8%B7%91%E7%94%B7%E9%93%81%E4%BA%86%E5%BF%83%E8%A6%81%E5%9B%BD%E6%B0%91cp%23) `227.1K 🔥`
1. [小米YU9 (Xiaomi YU9)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3YU9%23) `173.0K 🔥`
1. [Angelababy紫瞳 (Angelababy purple pupil)](https://s.weibo.com/weibo?q=%23Angelababy%E7%B4%AB%E7%9E%B3%23) `172.2K 🔥`
1. [伊朗又一轮导弹射向以色列 (Iran fires another round of missiles at Israel)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%88%E4%B8%80%E8%BD%AE%E5%AF%BC%E5%BC%B9%E5%B0%84%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `167.0K 🔥`
1. [曝迪丽热巴签约天伊娱乐 (It is revealed that Dilireba signed a contract with Tianyi Entertainment)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%AD%BE%E7%BA%A6%E5%A4%A9%E4%BC%8A%E5%A8%B1%E4%B9%90%23) `156.5K 🔥`
1. [伊朗正准备毁灭性报复行动 (Iran is preparing devastating retaliation)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%87%86%E5%A4%87%E6%AF%81%E7%81%AD%E6%80%A7%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%23) `144.4K 🔥`
1. [我家那小子](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%23) `142.2K 🔥`
1. [秀禾服 婚服营销](https://s.weibo.com/weibo?q=%23%E7%A7%80%E7%A6%BE%E6%9C%8D%20%E5%A9%9A%E6%9C%8D%E8%90%A5%E9%94%80%23) `137.6K 🔥`
1. [孟子义李昀锐综艺 (Meng Ziyi and Li Yunrui variety show)](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E7%BB%BC%E8%89%BA%23) `135.4K 🔥`
1. [德国总理从中国回去后急了 (The German Chancellor became anxious after returning from China)](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E5%9B%BD%E6%80%BB%E7%90%86%E4%BB%8E%E4%B8%AD%E5%9B%BD%E5%9B%9E%E5%8E%BB%E5%90%8E%E6%80%A5%E4%BA%86%23) `134.3K 🔥`
1. [杨博文抽抽乐](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%8D%9A%E6%96%87%E6%8A%BD%E6%8A%BD%E4%B9%90%23) `128.4K 🔥`
1. [AI种地已经发展成这样了](https://s.weibo.com/weibo?q=%23AI%E7%A7%8D%E5%9C%B0%E5%B7%B2%E7%BB%8F%E5%8F%91%E5%B1%95%E6%88%90%E8%BF%99%E6%A0%B7%E4%BA%86%23) `111.9K 🔥`
1. [范丞丞方说不认识没交集 (Fan Chengcheng said he didn’t know each other or had any interactions with him.)](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E6%96%B9%E8%AF%B4%E4%B8%8D%E8%AE%A4%E8%AF%86%E6%B2%A1%E4%BA%A4%E9%9B%86%23) `108.7K 🔥`
1. [TF家族全员运动会 澳门 (TF Family Sports Meet Macau)](https://s.weibo.com/weibo?q=%23TF%E5%AE%B6%E6%97%8F%E5%85%A8%E5%91%98%E8%BF%90%E5%8A%A8%E4%BC%9A%20%E6%BE%B3%E9%97%A8%23) `106.2K 🔥`
1. [王健林已卖掉80多座万达广场](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%81%A5%E6%9E%97%E5%B7%B2%E5%8D%96%E6%8E%8980%E5%A4%9A%E5%BA%A7%E4%B8%87%E8%BE%BE%E5%B9%BF%E5%9C%BA%23) `103.4K 🔥`
1. [Demna开启Gucci全新时代 (Demna opens a new era for Gucci)](https://s.weibo.com/weibo?q=%23Demna%E5%BC%80%E5%90%AFGucci%E5%85%A8%E6%96%B0%E6%97%B6%E4%BB%A3%23) `234.5K 🔥` `-22%`
1. [一点点 植脂末](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%20%E6%A4%8D%E8%84%82%E6%9C%AB%23) `227.2K 🔥` `-26%`
1. [赛琳娜力挺老公 (Selena supports her husband)](https://s.weibo.com/weibo?q=%23%E8%B5%9B%E7%90%B3%E5%A8%9C%E5%8A%9B%E6%8C%BA%E8%80%81%E5%85%AC%23) `170.9K 🔥` `-24%`
1. [TOP和谷爱凌合照](https://s.weibo.com/weibo?q=%23TOP%E5%92%8C%E8%B0%B7%E7%88%B1%E5%87%8C%E5%90%88%E7%85%A7%23) `166.1K 🔥` `-24%`
1. [曝初瑞雪怀孕](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%88%9D%E7%91%9E%E9%9B%AA%E6%80%80%E5%AD%95%23) `156.0K 🔥` `-34%`
1. [美国太空部队前往伊朗行动](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%A4%AA%E7%A9%BA%E9%83%A8%E9%98%9F%E5%89%8D%E5%BE%80%E4%BC%8A%E6%9C%97%E8%A1%8C%E5%8A%A8%23) `119.3K 🔥` `-58%`

Updated at 2026-02-28 19:48:43

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
