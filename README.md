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

1. [温瑞博vs莫雷加德 (Wenrebo vs Moregard)](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9Avs%E8%8E%AB%E9%9B%B7%E5%8A%A0%E5%BE%B7%23) `414.8K 🔥` `NEW`
1. [红旗HS6 PHEV致敬中国健儿](https://s.weibo.com/weibo?q=%23%E7%BA%A2%E6%97%97HS6%20PHEV%E8%87%B4%E6%95%AC%E4%B8%AD%E5%9B%BD%E5%81%A5%E5%84%BF%23) `389.9K 🔥` `NEW`
1. [两会期间单位食堂少了个碗](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%E6%9C%9F%E9%97%B4%E5%8D%95%E4%BD%8D%E9%A3%9F%E5%A0%82%E5%B0%91%E4%BA%86%E4%B8%AA%E7%A2%97%23) `337.8K 🔥` `NEW`
1. [ITZY召回打歌](https://s.weibo.com/weibo?q=%23ITZY%E5%8F%AC%E5%9B%9E%E6%89%93%E6%AD%8C%23) `180.3K 🔥` `NEW`
1. [温瑞博3比1莫雷加德](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9A3%E6%AF%941%E8%8E%AB%E9%9B%B7%E5%8A%A0%E5%BE%B7%23) `131.6K 🔥` `NEW`
1. [樊长玉 腮红](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%20%E8%85%AE%E7%BA%A2%23) `114.4K 🔥` `NEW`
1. [谢征切大号](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E5%88%87%E5%A4%A7%E5%8F%B7%23) `88.9K 🔥` `NEW`
1. [温瑞博晋级重庆赛八强](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9A%E6%99%8B%E7%BA%A7%E9%87%8D%E5%BA%86%E8%B5%9B%E5%85%AB%E5%BC%BA%23) `86.8K 🔥` `NEW`
1. [网友提名金鹰奖名单](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E6%8F%90%E5%90%8D%E9%87%91%E9%B9%B0%E5%A5%96%E5%90%8D%E5%8D%95%23) `82.5K 🔥` `NEW`
1. [追觅汽车价格](https://s.weibo.com/weibo?q=%23%E8%BF%BD%E8%A7%85%E6%B1%BD%E8%BD%A6%E4%BB%B7%E6%A0%BC%23) `72.7K 🔥` `NEW`
1. [在海上生活的狗狗吵架还得游泳 (Dogs living in the sea argue and have to swim)](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E6%B5%B7%E4%B8%8A%E7%94%9F%E6%B4%BB%E7%9A%84%E7%8B%97%E7%8B%97%E5%90%B5%E6%9E%B6%E8%BF%98%E5%BE%97%E6%B8%B8%E6%B3%B3%23) `72.0K 🔥` `NEW`
1. [周云杰说ai对每个人都是机会](https://s.weibo.com/weibo?q=%23%E5%91%A8%E4%BA%91%E6%9D%B0%E8%AF%B4ai%E5%AF%B9%E6%AF%8F%E4%B8%AA%E4%BA%BA%E9%83%BD%E6%98%AF%E6%9C%BA%E4%BC%9A%23) `71.7K 🔥` `NEW`
1. [伊朗空军指挥官遭袭身亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A9%BA%E5%86%9B%E6%8C%87%E6%8C%A5%E5%AE%98%E9%81%AD%E8%A2%AD%E8%BA%AB%E4%BA%A1%23) `393.8K 🔥` `+48%`
1. [NBA常规赛](https://s.weibo.com/weibo?q=%23NBA%E5%B8%B8%E8%A7%84%E8%B5%9B%23) `387.4K 🔥` `+23%`
1. [谢征强吻樊长玉](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E5%BC%BA%E5%90%BB%E6%A8%8A%E9%95%BF%E7%8E%89%23) `303.6K 🔥` `+80%`
1. [白鹿把孩子塞到王鹤棣怀里](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E6%8A%8A%E5%AD%A9%E5%AD%90%E5%A1%9E%E5%88%B0%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%80%80%E9%87%8C%23) `272.7K 🔥` `+161%`
1. [伊朗称袭击了美国油轮](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E8%A2%AD%E5%87%BB%E4%BA%86%E7%BE%8E%E5%9B%BD%E6%B2%B9%E8%BD%AE%23) `150.2K 🔥` `+77%`
1. [十四届全国人大四次会议闭幕会](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E9%97%AD%E5%B9%95%E4%BC%9A%23) `1.0M 🔥`
1. [司法部将在全国统一推行扫码入企 (The Ministry of Justice will uniformly implement scanning codes to enter enterprises nationwide)](https://s.weibo.com/weibo?q=%23%E5%8F%B8%E6%B3%95%E9%83%A8%E5%B0%86%E5%9C%A8%E5%85%A8%E5%9B%BD%E7%BB%9F%E4%B8%80%E6%8E%A8%E8%A1%8C%E6%89%AB%E7%A0%81%E5%85%A5%E4%BC%81%23) `717.6K 🔥`
1. [中国109项硬核项目来了 (China’s 109 hard-core projects are here)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD109%E9%A1%B9%E7%A1%AC%E6%A0%B8%E9%A1%B9%E7%9B%AE%E6%9D%A5%E4%BA%86%23) `558.0K 🔥`
1. [中方回应特朗普计划访华 (China responds to Trump's planned visit to China)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E8%AE%A1%E5%88%92%E8%AE%BF%E5%8D%8E%23) `441.0K 🔥`
1. [表决通过生态环境法典](https://s.weibo.com/weibo?q=%23%E8%A1%A8%E5%86%B3%E9%80%9A%E8%BF%87%E7%94%9F%E6%80%81%E7%8E%AF%E5%A2%83%E6%B3%95%E5%85%B8%23) `366.4K 🔥`
1. [我国人均有100棵树](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E4%BA%BA%E5%9D%87%E6%9C%89100%E6%A3%B5%E6%A0%91%23) `346.0K 🔥`
1. [西安不倒翁小姐姐宣布离职 (The roly-poly girl from Xi'an announced her resignation)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%AE%89%E4%B8%8D%E5%80%92%E7%BF%81%E5%B0%8F%E5%A7%90%E5%A7%90%E5%AE%A3%E5%B8%83%E7%A6%BB%E8%81%8C%23) `324.2K 🔥`
1. [天塌了山姆的三文鱼原来不能生吃](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E5%A1%8C%E4%BA%86%E5%B1%B1%E5%A7%86%E7%9A%84%E4%B8%89%E6%96%87%E9%B1%BC%E5%8E%9F%E6%9D%A5%E4%B8%8D%E8%83%BD%E7%94%9F%E5%90%83%23) `280.0K 🔥`
1. [微信3大新功能 (3 new features of WeChat)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A13%E5%A4%A7%E6%96%B0%E5%8A%9F%E8%83%BD%23) `207.7K 🔥`
1. [大学生4个馒头卖了30000元](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F4%E4%B8%AA%E9%A6%92%E5%A4%B4%E5%8D%96%E4%BA%8630000%E5%85%83%23) `195.0K 🔥`
1. [网传琅琊榜3吴磊换张凌赫](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E7%90%85%E7%90%8A%E6%A6%9C3%E5%90%B4%E7%A3%8A%E6%8D%A2%E5%BC%A0%E5%87%8C%E8%B5%AB%23) `152.6K 🔥`
1. [男子误吞12厘米筷子忍了8年才取出 (Man accidentally swallowed 12cm chopsticks and endured it for 8 years before taking them out)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%AF%AF%E5%90%9E12%E5%8E%98%E7%B1%B3%E7%AD%B7%E5%AD%90%E5%BF%8D%E4%BA%868%E5%B9%B4%E6%89%8D%E5%8F%96%E5%87%BA%23) `152.1K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `151.2K 🔥`
1. [保时捷车主回应车窗被砸取AED救人](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E6%97%B6%E6%8D%B7%E8%BD%A6%E4%B8%BB%E5%9B%9E%E5%BA%94%E8%BD%A6%E7%AA%97%E8%A2%AB%E7%A0%B8%E5%8F%96AED%E6%95%91%E4%BA%BA%23) `140.9K 🔥`
1. [逐玉超过赘婿](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%B6%85%E8%BF%87%E8%B5%98%E5%A9%BF%23) `127.6K 🔥`
1. [鞠婧祎彝族服饰造型](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E5%BD%9D%E6%97%8F%E6%9C%8D%E9%A5%B0%E9%80%A0%E5%9E%8B%23) `126.7K 🔥`
1. [AI演员都出片场花絮了 (AI actors have all appeared on the set.)](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%E9%83%BD%E5%87%BA%E7%89%87%E5%9C%BA%E8%8A%B1%E7%B5%AE%E4%BA%86%23) `105.3K 🔥`
1. [伊朗自曝研究美军20年](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%87%AA%E6%9B%9D%E7%A0%94%E7%A9%B6%E7%BE%8E%E5%86%9B20%E5%B9%B4%23) `98.6K 🔥`
1. [吃全麦面包减肥的人天塌了](https://s.weibo.com/weibo?q=%23%E5%90%83%E5%85%A8%E9%BA%A6%E9%9D%A2%E5%8C%85%E5%87%8F%E8%82%A5%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `95.9K 🔥`
1. [杨幂把海洋穿身上了 (Yang Mi wears the ocean on her body)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%8A%8A%E6%B5%B7%E6%B4%8B%E7%A9%BF%E8%BA%AB%E4%B8%8A%E4%BA%86%23) `85.5K 🔥`
1. [伊朗用最强导弹专打以色列 (Iran uses its most powerful missiles to attack Israel)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%94%A8%E6%9C%80%E5%BC%BA%E5%AF%BC%E5%BC%B9%E4%B8%93%E6%89%93%E4%BB%A5%E8%89%B2%E5%88%97%23) `81.3K 🔥`
1. [易梦体质](https://s.weibo.com/weibo?q=%23%E6%98%93%E6%A2%A6%E4%BD%93%E8%B4%A8%23) `80.0K 🔥`
1. [镖人 第二部](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E7%AC%AC%E4%BA%8C%E9%83%A8%23) `78.1K 🔥`
1. [腾讯视频 无添加不兑水](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91%20%E6%97%A0%E6%B7%BB%E5%8A%A0%E4%B8%8D%E5%85%91%E6%B0%B4%23) `77.7K 🔥`
1. [猫 我刚刚是不是太凶了](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E6%88%91%E5%88%9A%E5%88%9A%E6%98%AF%E4%B8%8D%E6%98%AF%E5%A4%AA%E5%87%B6%E4%BA%86%23) `71.4K 🔥`
1. [美国海军已逃离伊朗周边海域](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%B5%B7%E5%86%9B%E5%B7%B2%E9%80%83%E7%A6%BB%E4%BC%8A%E6%9C%97%E5%91%A8%E8%BE%B9%E6%B5%B7%E5%9F%9F%23) `268.6K 🔥` `-26%`
1. [种地吧直播 (Farm Bar live broadcast)](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%E7%9B%B4%E6%92%AD%23) `193.5K 🔥` `-46%`
1. [吴艳妮决赛退赛](https://s.weibo.com/weibo?q=%23%E5%90%B4%E8%89%B3%E5%A6%AE%E5%86%B3%E8%B5%9B%E9%80%80%E8%B5%9B%23) `152.7K 🔥` `-28%`
1. [本田突发暴雷](https://s.weibo.com/weibo?q=%23%E6%9C%AC%E7%94%B0%E7%AA%81%E5%8F%91%E6%9A%B4%E9%9B%B7%23) `118.0K 🔥` `-36%`
1. [朝九晚五其实是朝七晚六](https://s.weibo.com/weibo?q=%23%E6%9C%9D%E4%B9%9D%E6%99%9A%E4%BA%94%E5%85%B6%E5%AE%9E%E6%98%AF%E6%9C%9D%E4%B8%83%E6%99%9A%E5%85%AD%23) `103.3K 🔥` `-64%`
1. [爆剧 养老剧 (Explosive Drama Elder Care Drama)](https://s.weibo.com/weibo?q=%23%E7%88%86%E5%89%A7%20%E5%85%BB%E8%80%81%E5%89%A7%23) `84.5K 🔥` `-49%`
1. [两个无印良品共存易让人误购](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%B8%AA%E6%97%A0%E5%8D%B0%E8%89%AF%E5%93%81%E5%85%B1%E5%AD%98%E6%98%93%E8%AE%A9%E4%BA%BA%E8%AF%AF%E8%B4%AD%23) `75.4K 🔥` `-55%`
1. [最强alpha齐聚阿迪达斯 (The strongest alphas gather in Adidas)](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BC%BAalpha%E9%BD%90%E8%81%9A%E9%98%BF%E8%BF%AA%E8%BE%BE%E6%96%AF%23) `72.2K 🔥` `-41%`

Updated at 2026-03-12 19:48:14

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
