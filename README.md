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

1. [王楚钦vs格罗特 (Wang Chuqin vs Grote)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E6%A0%BC%E7%BD%97%E7%89%B9%23) `770.8K 🔥` `NEW`
1. [王小亿内场这个美](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%B0%8F%E4%BA%BF%E5%86%85%E5%9C%BA%E8%BF%99%E4%B8%AA%E7%BE%8E%23) `162.1K 🔥` `NEW`
1. [逐玉孔雪儿邓凯这一对简直仙品](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%AD%94%E9%9B%AA%E5%84%BF%E9%82%93%E5%87%AF%E8%BF%99%E4%B8%80%E5%AF%B9%E7%AE%80%E7%9B%B4%E4%BB%99%E5%93%81%23) `137.9K 🔥` `NEW`
1. [少点无意义加班很有意义](https://s.weibo.com/weibo?q=%23%E5%B0%91%E7%82%B9%E6%97%A0%E6%84%8F%E4%B9%89%E5%8A%A0%E7%8F%AD%E5%BE%88%E6%9C%89%E6%84%8F%E4%B9%89%23) `103.8K 🔥` `NEW`
1. [建议允许未休年假两年内结转使用](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%85%81%E8%AE%B8%E6%9C%AA%E4%BC%91%E5%B9%B4%E5%81%87%E4%B8%A4%E5%B9%B4%E5%86%85%E7%BB%93%E8%BD%AC%E4%BD%BF%E7%94%A8%23) `99.0K 🔥` `NEW`
1. [湖人战胜森林狼](https://s.weibo.com/weibo?q=%23%E6%B9%96%E4%BA%BA%E6%88%98%E8%83%9C%E6%A3%AE%E6%9E%97%E7%8B%BC%23) `98.4K 🔥` `NEW`
1. [马斯克身价达8390亿美元](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%96%AF%E5%85%8B%E8%BA%AB%E4%BB%B7%E8%BE%BE8390%E4%BA%BF%E7%BE%8E%E5%85%83%23) `81.1K 🔥` `NEW`
1. [统一平台热度标准才能让爆款名副其实](https://s.weibo.com/weibo?q=%23%E7%BB%9F%E4%B8%80%E5%B9%B3%E5%8F%B0%E7%83%AD%E5%BA%A6%E6%A0%87%E5%87%86%E6%89%8D%E8%83%BD%E8%AE%A9%E7%88%86%E6%AC%BE%E5%90%8D%E5%89%AF%E5%85%B6%E5%AE%9E%23) `76.2K 🔥` `NEW`
1. [蔚来ES6五年跑出百万公里](https://s.weibo.com/weibo?q=%23%E8%94%9A%E6%9D%A5ES6%E4%BA%94%E5%B9%B4%E8%B7%91%E5%87%BA%E7%99%BE%E4%B8%87%E5%85%AC%E9%87%8C%23) `74.7K 🔥` `NEW`
1. [AG 首发](https://s.weibo.com/weibo?q=%23AG%20%E9%A6%96%E5%8F%91%23) `74.7K 🔥` `NEW`
1. [猫 我晨练碍着你了 (Cat, my morning exercise is disturbing you.)](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E6%88%91%E6%99%A8%E7%BB%83%E7%A2%8D%E7%9D%80%E4%BD%A0%E4%BA%86%23) `74.2K 🔥` `NEW`
1. [让龙虾知道密码有风险](https://s.weibo.com/weibo?q=%23%E8%AE%A9%E9%BE%99%E8%99%BE%E7%9F%A5%E9%81%93%E5%AF%86%E7%A0%81%E6%9C%89%E9%A3%8E%E9%99%A9%23) `69.9K 🔥` `NEW`
1. [前妻发文告别袁惟仁](https://s.weibo.com/weibo?q=%23%E5%89%8D%E5%A6%BB%E5%8F%91%E6%96%87%E5%91%8A%E5%88%AB%E8%A2%81%E6%83%9F%E4%BB%81%23) `69.7K 🔥` `NEW`
1. [虞书欣一滴泪原始帧](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%B8%80%E6%BB%B4%E6%B3%AA%E5%8E%9F%E5%A7%8B%E5%B8%A7%23) `69.6K 🔥` `NEW`
1. [呼吁合理增加下半年节假日天数](https://s.weibo.com/weibo?q=%23%E5%91%BC%E5%90%81%E5%90%88%E7%90%86%E5%A2%9E%E5%8A%A0%E4%B8%8B%E5%8D%8A%E5%B9%B4%E8%8A%82%E5%81%87%E6%97%A5%E5%A4%A9%E6%95%B0%23) `68.6K 🔥` `NEW`
1. [苹果新品发布会](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%96%B0%E5%93%81%E5%8F%91%E5%B8%83%E4%BC%9A%23) `63.8K 🔥` `NEW`
1. [工作不满10年休5天年假规则该调整](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%BD%9C%E4%B8%8D%E6%BB%A110%E5%B9%B4%E4%BC%915%E5%A4%A9%E5%B9%B4%E5%81%87%E8%A7%84%E5%88%99%E8%AF%A5%E8%B0%83%E6%95%B4%23) `1.0M 🔥` `+38%`
1. [政协会议圆满完成各项议程](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%8D%8F%E4%BC%9A%E8%AE%AE%E5%9C%86%E6%BB%A1%E5%AE%8C%E6%88%90%E5%90%84%E9%A1%B9%E8%AE%AE%E7%A8%8B%23) `608.4K 🔥`
1. [华莱士正式宣布退市](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E8%8E%B1%E5%A3%AB%E6%AD%A3%E5%BC%8F%E5%AE%A3%E5%B8%83%E9%80%80%E5%B8%82%23) `529.7K 🔥`
1. [桃花坞](https://s.weibo.com/weibo?q=%23%E6%A1%83%E8%8A%B1%E5%9D%9E%23) `469.5K 🔥`
1. [美国驻多伦多领馆遭枪击 (U.S. consulate in Toronto attacked)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E9%A9%BB%E5%A4%9A%E4%BC%A6%E5%A4%9A%E9%A2%86%E9%A6%86%E9%81%AD%E6%9E%AA%E5%87%BB%23) `407.8K 🔥`
1. [十五五蓝图中的职业新图景 (New career prospects in the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%93%9D%E5%9B%BE%E4%B8%AD%E7%9A%84%E8%81%8C%E4%B8%9A%E6%96%B0%E5%9B%BE%E6%99%AF%23) `401.9K 🔥`
1. [建议新增元宵节假日](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%96%B0%E5%A2%9E%E5%85%83%E5%AE%B5%E8%8A%82%E5%81%87%E6%97%A5%23) `401.3K 🔥`
1. [逐玉 赋魅](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E8%B5%8B%E9%AD%85%23) `396.1K 🔥`
1. [国际油价历史性暴跌](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%99%85%E6%B2%B9%E4%BB%B7%E5%8E%86%E5%8F%B2%E6%80%A7%E6%9A%B4%E8%B7%8C%23) `395.4K 🔥`
1. [伊朗下起毒雨](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8B%E8%B5%B7%E6%AF%92%E9%9B%A8%23) `410.4K 🔥` `-27%`
1. [建议推行婴幼儿父母弹性上下班 (It is recommended to implement flexible commuting for parents of infants and young children)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%8E%A8%E8%A1%8C%E5%A9%B4%E5%B9%BC%E5%84%BF%E7%88%B6%E6%AF%8D%E5%BC%B9%E6%80%A7%E4%B8%8A%E4%B8%8B%E7%8F%AD%23) `407.1K 🔥` `-60%`
1. [MiuMiu大秀](https://s.weibo.com/weibo?q=%23MiuMiu%E5%A4%A7%E7%A7%80%23) `351.6K 🔥` `-24%`
1. [汾酒回应多名硕士拟录为酿酒工成装工](https://s.weibo.com/weibo?q=%23%E6%B1%BE%E9%85%92%E5%9B%9E%E5%BA%94%E5%A4%9A%E5%90%8D%E7%A1%95%E5%A3%AB%E6%8B%9F%E5%BD%95%E4%B8%BA%E9%85%BF%E9%85%92%E5%B7%A5%E6%88%90%E8%A3%85%E5%B7%A5%23) `338.5K 🔥` `-40%`
1. [女子将老公送金镯扔地上又响又跳](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%B0%86%E8%80%81%E5%85%AC%E9%80%81%E9%87%91%E9%95%AF%E6%89%94%E5%9C%B0%E4%B8%8A%E5%8F%88%E5%93%8D%E5%8F%88%E8%B7%B3%23) `330.0K 🔥` `-29%`
1. [向佐差点踢到主持人的头](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%90%E5%B7%AE%E7%82%B9%E8%B8%A2%E5%88%B0%E4%B8%BB%E6%8C%81%E4%BA%BA%E7%9A%84%E5%A4%B4%23) `255.3K 🔥` `-45%`
1. [驻韩美军6部萨德发射车全部运出](https://s.weibo.com/weibo?q=%23%E9%A9%BB%E9%9F%A9%E7%BE%8E%E5%86%9B6%E9%83%A8%E8%90%A8%E5%BE%B7%E5%8F%91%E5%B0%84%E8%BD%A6%E5%85%A8%E9%83%A8%E8%BF%90%E5%87%BA%23) `162.2K 🔥` `-65%`
1. [王励勤称正在与樊振东沟通 (Wang Liqin said he was communicating with Fan Zhendong)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B1%E5%8B%A4%E7%A7%B0%E6%AD%A3%E5%9C%A8%E4%B8%8E%E6%A8%8A%E6%8C%AF%E4%B8%9C%E6%B2%9F%E9%80%9A%23) `143.0K 🔥` `-69%`
1. [要对钱有概念](https://s.weibo.com/weibo?q=%23%E8%A6%81%E5%AF%B9%E9%92%B1%E6%9C%89%E6%A6%82%E5%BF%B5%23) `140.8K 🔥` `-69%`
1. [以为是段子结果真发生了](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%98%AF%E6%AE%B5%E5%AD%90%E7%BB%93%E6%9E%9C%E7%9C%9F%E5%8F%91%E7%94%9F%E4%BA%86%23) `139.7K 🔥` `-69%`
1. [伊朗称正在霍尔木兹海峡等待美海军](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%AD%A3%E5%9C%A8%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E7%AD%89%E5%BE%85%E7%BE%8E%E6%B5%B7%E5%86%9B%23) `121.5K 🔥` `-73%`
1. [资本重新押注30元咖啡](https://s.weibo.com/weibo?q=%23%E8%B5%84%E6%9C%AC%E9%87%8D%E6%96%B0%E6%8A%BC%E6%B3%A830%E5%85%83%E5%92%96%E5%95%A1%23) `118.3K 🔥` `-74%`
1. [帅的追你一秒就同意了](https://s.weibo.com/weibo?q=%23%E5%B8%85%E7%9A%84%E8%BF%BD%E4%BD%A0%E4%B8%80%E7%A7%92%E5%B0%B1%E5%90%8C%E6%84%8F%E4%BA%86%23) `109.3K 🔥` `-75%`
1. [热水肥皂拖地法](https://s.weibo.com/weibo?q=%23%E7%83%AD%E6%B0%B4%E8%82%A5%E7%9A%82%E6%8B%96%E5%9C%B0%E6%B3%95%23) `100.2K 🔥` `-78%`
1. [苹果最便宜手机来了 (Apple’s cheapest phone is here)](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E6%9D%A5%E4%BA%86%23) `97.3K 🔥` `-79%`
1. [杨紫罗马时装周出发图](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%BD%97%E9%A9%AC%E6%97%B6%E8%A3%85%E5%91%A8%E5%87%BA%E5%8F%91%E5%9B%BE%23) `90.6K 🔥` `-80%`
1. [怪不得小孩总是一哭就找妈妈 (No wonder children always look for their mothers when they cry)](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E5%B0%8F%E5%AD%A9%E6%80%BB%E6%98%AF%E4%B8%80%E5%93%AD%E5%B0%B1%E6%89%BE%E5%A6%88%E5%A6%88%23) `88.6K 🔥` `-80%`
1. [逐玉播出实绩 (Zhuyu broadcast performance)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E6%92%AD%E5%87%BA%E5%AE%9E%E7%BB%A9%23) `80.0K 🔥` `-83%`
1. [社会化能力](https://s.weibo.com/weibo?q=%23%E7%A4%BE%E4%BC%9A%E5%8C%96%E8%83%BD%E5%8A%9B%23) `79.3K 🔥` `-82%`
1. [詹姆斯回应阿德巴约破纪录](https://s.weibo.com/weibo?q=%23%E8%A9%B9%E5%A7%86%E6%96%AF%E5%9B%9E%E5%BA%94%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A6%E7%A0%B4%E7%BA%AA%E5%BD%95%23) `78.0K 🔥` `-86%`
1. [她的盛焰定档 (Her grandeur is set)](https://s.weibo.com/weibo?q=%23%E5%A5%B9%E7%9A%84%E7%9B%9B%E7%84%B0%E5%AE%9A%E6%A1%A3%23) `72.2K 🔥` `-84%`
1. [阿德巴约83分](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A683%E5%88%86%23) `69.9K 🔥` `-84%`
1. [电脑售价或上涨40%](https://s.weibo.com/weibo?q=%23%E7%94%B5%E8%84%91%E5%94%AE%E4%BB%B7%E6%88%96%E4%B8%8A%E6%B6%A840%25%23) `68.7K 🔥` `-85%`
1. [联合国警告以美袭击伊朗后果](https://s.weibo.com/weibo?q=%23%E8%81%94%E5%90%88%E5%9B%BD%E8%AD%A6%E5%91%8A%E4%BB%A5%E7%BE%8E%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E5%90%8E%E6%9E%9C%23) `64.9K 🔥` `-86%`

Updated at 2026-03-11 14:29:19

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
