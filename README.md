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

1. [视频速览十五五20项主要指标 (Video quick overview of 20 major indicators of the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E8%A7%86%E9%A2%91%E9%80%9F%E8%A7%88%E5%8D%81%E4%BA%94%E4%BA%9420%E9%A1%B9%E4%B8%BB%E8%A6%81%E6%8C%87%E6%A0%87%23) `605.1K 🔥` `NEW`
1. [开学容错率最高的三个决定](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%AD%A6%E5%AE%B9%E9%94%99%E7%8E%87%E6%9C%80%E9%AB%98%E7%9A%84%E4%B8%89%E4%B8%AA%E5%86%B3%E5%AE%9A%23) `603.8K 🔥` `NEW`
1. [央行今年将降准降息](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A1%8C%E4%BB%8A%E5%B9%B4%E5%B0%86%E9%99%8D%E5%87%86%E9%99%8D%E6%81%AF%23) `603.8K 🔥` `NEW`
1. [耿爽履新中国人民外交学会副会长](https://s.weibo.com/weibo?q=%23%E8%80%BF%E7%88%BD%E5%B1%A5%E6%96%B0%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B0%91%E5%A4%96%E4%BA%A4%E5%AD%A6%E4%BC%9A%E5%89%AF%E4%BC%9A%E9%95%BF%23) `603.0K 🔥` `NEW`
1. [看完英超看中超](https://s.weibo.com/weibo?q=%23%E7%9C%8B%E5%AE%8C%E8%8B%B1%E8%B6%85%E7%9C%8B%E4%B8%AD%E8%B6%85%23) `600.2K 🔥` `NEW`
1. [建议老年人转账设24小时冷静期](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E8%80%81%E5%B9%B4%E4%BA%BA%E8%BD%AC%E8%B4%A6%E8%AE%BE24%E5%B0%8F%E6%97%B6%E5%86%B7%E9%9D%99%E6%9C%9F%23) `599.1K 🔥` `NEW`
1. [这位人大代表坚守乡村小学40年](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%BD%8D%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E5%9D%9A%E5%AE%88%E4%B9%A1%E6%9D%91%E5%B0%8F%E5%AD%A640%E5%B9%B4%23) `597.0K 🔥` `NEW`
1. [TES上报Naiyou不正当行为](https://s.weibo.com/weibo?q=%23TES%E4%B8%8A%E6%8A%A5Naiyou%E4%B8%8D%E6%AD%A3%E5%BD%93%E8%A1%8C%E4%B8%BA%23) `593.4K 🔥` `NEW`
1. [369 小丑了](https://s.weibo.com/weibo?q=%23369%20%E5%B0%8F%E4%B8%91%E4%BA%86%23) `592.8K 🔥` `NEW`
1. [钎九不清冰合照](https://s.weibo.com/weibo?q=%23%E9%92%8E%E4%B9%9D%E4%B8%8D%E6%B8%85%E5%86%B0%E5%90%88%E7%85%A7%23) `335.8K 🔥` `NEW`
1. [代表说宠物相关法律迟早会出台 (Representatives say pet-related laws will be introduced sooner or later)](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%AE%A0%E7%89%A9%E7%9B%B8%E5%85%B3%E6%B3%95%E5%BE%8B%E8%BF%9F%E6%97%A9%E4%BC%9A%E5%87%BA%E5%8F%B0%23) `287.1K 🔥` `NEW`
1. [董璇张维伊婚礼策划倒闭了](https://s.weibo.com/weibo?q=%23%E8%91%A3%E7%92%87%E5%BC%A0%E7%BB%B4%E4%BC%8A%E5%A9%9A%E7%A4%BC%E7%AD%96%E5%88%92%E5%80%92%E9%97%AD%E4%BA%86%23) `286.6K 🔥` `NEW`
1. [Naiyou疑似假赛](https://s.weibo.com/weibo?q=%23Naiyou%E7%96%91%E4%BC%BC%E5%81%87%E8%B5%9B%23) `220.7K 🔥` `NEW`
1. [腾讯工程师在楼下免费安装OpenClaw](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E5%B7%A5%E7%A8%8B%E5%B8%88%E5%9C%A8%E6%A5%BC%E4%B8%8B%E5%85%8D%E8%B4%B9%E5%AE%89%E8%A3%85OpenClaw%23) `166.1K 🔥` `NEW`
1. [伊朗一儿童游乐场遭袭](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%80%E5%84%BF%E7%AB%A5%E6%B8%B8%E4%B9%90%E5%9C%BA%E9%81%AD%E8%A2%AD%23) `147.2K 🔥` `NEW`
1. [妇女节 放假](https://s.weibo.com/weibo?q=%23%E5%A6%87%E5%A5%B3%E8%8A%82%20%E6%94%BE%E5%81%87%23) `143.7K 🔥` `NEW`
1. [白鹿跳水了](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E8%B7%B3%E6%B0%B4%E4%BA%86%23) `132.6K 🔥` `NEW`
1. [逐玉 顶级待遇](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E9%A1%B6%E7%BA%A7%E5%BE%85%E9%81%87%23) `132.1K 🔥` `NEW`
1. [PDRN为什么叫液体黄金](https://s.weibo.com/weibo?q=%23PDRN%E4%B8%BA%E4%BB%80%E4%B9%88%E5%8F%AB%E6%B6%B2%E4%BD%93%E9%BB%84%E9%87%91%23) `119.0K 🔥` `NEW`
1. [千问妇女节活动](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%A6%87%E5%A5%B3%E8%8A%82%E6%B4%BB%E5%8A%A8%23) `601.3K 🔥` `+28%`
1. [AI相关产业规模将超10万亿元 (AI-related industry scale will exceed 10 trillion yuan)](https://s.weibo.com/weibo?q=%23AI%E7%9B%B8%E5%85%B3%E4%BA%A7%E4%B8%9A%E8%A7%84%E6%A8%A1%E5%B0%86%E8%B6%8510%E4%B8%87%E4%BA%BF%E5%85%83%23) `598.5K 🔥` `+26%`
1. [预计今年GDP增量超6万亿元 (GDP growth this year is expected to exceed 6 trillion yuan)](https://s.weibo.com/weibo?q=%23%E9%A2%84%E8%AE%A1%E4%BB%8A%E5%B9%B4GDP%E5%A2%9E%E9%87%8F%E8%B6%856%E4%B8%87%E4%BA%BF%E5%85%83%23) `595.0K 🔥` `+26%`
1. [伊朗称击中美国林肯号航母](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%87%BB%E4%B8%AD%E7%BE%8E%E5%9B%BD%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%23) `589.0K 🔥` `+45%`
1. [多地官宣春假清明连休6天 (Officials in many places announced that the Spring Festival will be closed for 6 consecutive days during Qingming Festival)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E5%AE%98%E5%AE%A3%E6%98%A5%E5%81%87%E6%B8%85%E6%98%8E%E8%BF%9E%E4%BC%916%E5%A4%A9%23) `587.1K 🔥` `+22%`
1. [董璇吐槽张维伊](https://s.weibo.com/weibo?q=%23%E8%91%A3%E7%92%87%E5%90%90%E6%A7%BD%E5%BC%A0%E7%BB%B4%E4%BC%8A%23) `586.7K 🔥` `+21%`
1. [天猫一场直播汇集百款AI新品](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E7%8C%AB%E4%B8%80%E5%9C%BA%E7%9B%B4%E6%92%AD%E6%B1%87%E9%9B%86%E7%99%BE%E6%AC%BEAI%E6%96%B0%E5%93%81%23) `305.3K 🔥` `+57%`
1. [小鹏G6超级增程六项全能一步到位](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%B9%8FG6%E8%B6%85%E7%BA%A7%E5%A2%9E%E7%A8%8B%E5%85%AD%E9%A1%B9%E5%85%A8%E8%83%BD%E4%B8%80%E6%AD%A5%E5%88%B0%E4%BD%8D%23) `262.2K 🔥` `+50%`
1. [破5亿播放AI短剧成本仅3000](https://s.weibo.com/weibo?q=%23%E7%A0%B45%E4%BA%BF%E6%92%AD%E6%94%BEAI%E7%9F%AD%E5%89%A7%E6%88%90%E6%9C%AC%E4%BB%853000%23) `247.6K 🔥` `+27%`
1. [第五人格](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%BA%94%E4%BA%BA%E6%A0%BC%23) `232.3K 🔥` `+172%`
1. [教练笑了半小时才决定教普拉提](https://s.weibo.com/weibo?q=%23%E6%95%99%E7%BB%83%E7%AC%91%E4%BA%86%E5%8D%8A%E5%B0%8F%E6%97%B6%E6%89%8D%E5%86%B3%E5%AE%9A%E6%95%99%E6%99%AE%E6%8B%89%E6%8F%90%23) `151.8K 🔥` `+74%`
1. [只有白鹿一个人自恋](https://s.weibo.com/weibo?q=%23%E5%8F%AA%E6%9C%89%E7%99%BD%E9%B9%BF%E4%B8%80%E4%B8%AA%E4%BA%BA%E8%87%AA%E6%81%8B%23) `119.4K 🔥` `+31%`
1. [曝周翊然竞争十日终焉被pass](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%91%A8%E7%BF%8A%E7%84%B6%E7%AB%9E%E4%BA%89%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E8%A2%ABpass%23) `118.9K 🔥` `+36%`
1. [经济主题记者会 (Economic press conference)](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E6%B5%8E%E4%B8%BB%E9%A2%98%E8%AE%B0%E8%80%85%E4%BC%9A%23) `1.0M 🔥`
1. [青海省委书记看生命树落泪 (Secretary of Qinghai Provincial Party Committee sheds tears when looking at the Tree of Life)](https://s.weibo.com/weibo?q=%23%E9%9D%92%E6%B5%B7%E7%9C%81%E5%A7%94%E4%B9%A6%E8%AE%B0%E7%9C%8B%E7%94%9F%E5%91%BD%E6%A0%91%E8%90%BD%E6%B3%AA%23) `717.0K 🔥`
1. [千问宣布妇女节再次请客 (Qianwen announces another treat for Women’s Day)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%AE%A3%E5%B8%83%E5%A6%87%E5%A5%B3%E8%8A%82%E5%86%8D%E6%AC%A1%E8%AF%B7%E5%AE%A2%23) `443.6K 🔥`
1. [孩子大了后要帮孩子完成社会化](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E5%A4%A7%E4%BA%86%E5%90%8E%E8%A6%81%E5%B8%AE%E5%AD%A9%E5%AD%90%E5%AE%8C%E6%88%90%E7%A4%BE%E4%BC%9A%E5%8C%96%23) `282.2K 🔥`
1. [领克900大五座官宣亮相](https://s.weibo.com/weibo?q=%23%E9%A2%86%E5%85%8B900%E5%A4%A7%E4%BA%94%E5%BA%A7%E5%AE%98%E5%AE%A3%E4%BA%AE%E7%9B%B8%23) `178.0K 🔥`
1. [女子产后21天突发大出血晕倒车库](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%BA%A7%E5%90%8E21%E5%A4%A9%E7%AA%81%E5%8F%91%E5%A4%A7%E5%87%BA%E8%A1%80%E6%99%95%E5%80%92%E8%BD%A6%E5%BA%93%23) `177.6K 🔥`
1. [本想全国唯一却因太生僻改名](https://s.weibo.com/weibo?q=%23%E6%9C%AC%E6%83%B3%E5%85%A8%E5%9B%BD%E5%94%AF%E4%B8%80%E5%8D%B4%E5%9B%A0%E5%A4%AA%E7%94%9F%E5%83%BB%E6%94%B9%E5%90%8D%23) `113.4K 🔥`
1. [逐玉集均](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E9%9B%86%E5%9D%87%23) `107.3K 🔥`
1. [千问 (Qianwen)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%23) `285.6K 🔥` `-40%`
1. [小米发布国内第一个手机版龙虾 (Xiaomi releases China’s first mobile version of Lobster)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E5%8F%91%E5%B8%83%E5%9B%BD%E5%86%85%E7%AC%AC%E4%B8%80%E4%B8%AA%E6%89%8B%E6%9C%BA%E7%89%88%E9%BE%99%E8%99%BE%23) `216.6K 🔥` `-27%`
1. [印度对美国炸船行为保持沉默](https://s.weibo.com/weibo?q=%23%E5%8D%B0%E5%BA%A6%E5%AF%B9%E7%BE%8E%E5%9B%BD%E7%82%B8%E8%88%B9%E8%A1%8C%E4%B8%BA%E4%BF%9D%E6%8C%81%E6%B2%89%E9%BB%98%23) `193.3K 🔥` `-23%`
1. [建议在全国推行低彩礼](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%9C%A8%E5%85%A8%E5%9B%BD%E6%8E%A8%E8%A1%8C%E4%BD%8E%E5%BD%A9%E7%A4%BC%23) `129.2K 🔥` `-73%`
1. [娜扎我互联网的好闺蜜](https://s.weibo.com/weibo?q=%23%E5%A8%9C%E6%89%8E%E6%88%91%E4%BA%92%E8%81%94%E7%BD%91%E7%9A%84%E5%A5%BD%E9%97%BA%E8%9C%9C%23) `123.3K 🔥` `-29%`
1. [Kep1er徐永恩退团](https://s.weibo.com/weibo?q=%23Kep1er%E5%BE%90%E6%B0%B8%E6%81%A9%E9%80%80%E5%9B%A2%23) `111.6K 🔥` `-42%`
1. [刘国梁回应樊振东一出一回 (Liu Guoliang responded to Fan Zhendong every time he came out)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%9B%BD%E6%A2%81%E5%9B%9E%E5%BA%94%E6%A8%8A%E6%8C%AF%E4%B8%9C%E4%B8%80%E5%87%BA%E4%B8%80%E5%9B%9E%23) `109.6K 🔥` `-40%`
1. [不要热水洗头时梳头发](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%A6%81%E7%83%AD%E6%B0%B4%E6%B4%97%E5%A4%B4%E6%97%B6%E6%A2%B3%E5%A4%B4%E5%8F%91%23) `109.3K 🔥` `-36%`
1. [避免女性在生育与事业间被迫二选一](https://s.weibo.com/weibo?q=%23%E9%81%BF%E5%85%8D%E5%A5%B3%E6%80%A7%E5%9C%A8%E7%94%9F%E8%82%B2%E4%B8%8E%E4%BA%8B%E4%B8%9A%E9%97%B4%E8%A2%AB%E8%BF%AB%E4%BA%8C%E9%80%89%E4%B8%80%23) `104.2K 🔥` `-47%`
1. [猫 哥你别吃了我害怕 (Cat, brother, don’t eat it, I’m afraid)](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E5%93%A5%E4%BD%A0%E5%88%AB%E5%90%83%E4%BA%86%E6%88%91%E5%AE%B3%E6%80%95%23) `101.8K 🔥` `-22%`
1. [季洁扮演者王茜回应重案六组翻拍 (Wang Qian, who plays Ji Jie, responds to the remake of Serious Case Six)](https://s.weibo.com/weibo?q=%23%E5%AD%A3%E6%B4%81%E6%89%AE%E6%BC%94%E8%80%85%E7%8E%8B%E8%8C%9C%E5%9B%9E%E5%BA%94%E9%87%8D%E6%A1%88%E5%85%AD%E7%BB%84%E7%BF%BB%E6%8B%8D%23) `101.6K 🔥` `-43%`

Updated at 2026-03-06 17:04:44

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
