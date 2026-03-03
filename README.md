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

1. [369为TES野辅发声 (369 speaks for TES Nosuke)](https://s.weibo.com/weibo?q=%23369%E4%B8%BATES%E9%87%8E%E8%BE%85%E5%8F%91%E5%A3%B0%23) `840.4K 🔥` `NEW`
1. [伊朗女足拒唱国歌](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A5%B3%E8%B6%B3%E6%8B%92%E5%94%B1%E5%9B%BD%E6%AD%8C%23) `467.9K 🔥` `NEW`
1. [我拍了拍月亮](https://s.weibo.com/weibo?q=%23%E6%88%91%E6%8B%8D%E4%BA%86%E6%8B%8D%E6%9C%88%E4%BA%AE%23) `461.8K 🔥` `NEW`
1. [建议多举措斩断不良网络热梗传播](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%A4%9A%E4%B8%BE%E6%8E%AA%E6%96%A9%E6%96%AD%E4%B8%8D%E8%89%AF%E7%BD%91%E7%BB%9C%E7%83%AD%E6%A2%97%E4%BC%A0%E6%92%AD%23) `413.2K 🔥` `NEW`
1. [品牌方回应迪丽热巴缺席](https://s.weibo.com/weibo?q=%23%E5%93%81%E7%89%8C%E6%96%B9%E5%9B%9E%E5%BA%94%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%BC%BA%E5%B8%AD%23) `397.8K 🔥` `NEW`
1. [李兰迪汤圆全洒了](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%85%B0%E8%BF%AA%E6%B1%A4%E5%9C%86%E5%85%A8%E6%B4%92%E4%BA%86%23) `248.1K 🔥` `NEW`
1. [下次元宵月全食要等到2072年](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E6%AC%A1%E5%85%83%E5%AE%B5%E6%9C%88%E5%85%A8%E9%A3%9F%E8%A6%81%E7%AD%89%E5%88%B02072%E5%B9%B4%23) `248.0K 🔥` `NEW`
1. [惠英红 你真的太狠了](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%20%E4%BD%A0%E7%9C%9F%E7%9A%84%E5%A4%AA%E7%8B%A0%E4%BA%86%23) `247.8K 🔥` `NEW`
1. [AI短剧 恐怖谷效应](https://s.weibo.com/weibo?q=%23AI%E7%9F%AD%E5%89%A7%20%E6%81%90%E6%80%96%E8%B0%B7%E6%95%88%E5%BA%94%23) `247.7K 🔥` `NEW`
1. [臭脚丫味把小猫逼疯](https://s.weibo.com/weibo?q=%23%E8%87%AD%E8%84%9A%E4%B8%AB%E5%91%B3%E6%8A%8A%E5%B0%8F%E7%8C%AB%E9%80%BC%E7%96%AF%23) `247.2K 🔥` `NEW`
1. [刘文祥 每家店味道不一样 (Liu Wenxiang Every store has a different taste)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%20%E6%AF%8F%E5%AE%B6%E5%BA%97%E5%91%B3%E9%81%93%E4%B8%8D%E4%B8%80%E6%A0%B7%23) `247.0K 🔥` `NEW`
1. [Bin拍校园写真了](https://s.weibo.com/weibo?q=%23Bin%E6%8B%8D%E6%A0%A1%E5%9B%AD%E5%86%99%E7%9C%9F%E4%BA%86%23) `246.8K 🔥` `NEW`
1. [纯真年代改了方穆静妈妈人设](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E6%94%B9%E4%BA%86%E6%96%B9%E7%A9%86%E9%9D%99%E5%A6%88%E5%A6%88%E4%BA%BA%E8%AE%BE%23) `246.7K 🔥` `NEW`
1. [AL对战iG](https://s.weibo.com/weibo?q=%23AL%E5%AF%B9%E6%88%98iG%23) `246.6K 🔥` `NEW`
1. [月全食 (total lunar eclipse)](https://s.weibo.com/weibo?q=%23%E6%9C%88%E5%85%A8%E9%A3%9F%23) `1.7M 🔥` `+55%`
1. [全国政协十四届四次会议新闻发布会 (Press Conference of the Fourth Session of the 14th CPPCC National Committee)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E6%94%BF%E5%8D%8F%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E6%96%B0%E9%97%BB%E5%8F%91%E5%B8%83%E4%BC%9A%23) `874.4K 🔥` `+40%`
1. [地平线HSD方盒子智驾新标杆 (Horizon HSD square box new benchmark for smart driving)](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E5%B9%B3%E7%BA%BFHSD%E6%96%B9%E7%9B%92%E5%AD%90%E6%99%BA%E9%A9%BE%E6%96%B0%E6%A0%87%E6%9D%86%23) `873.7K 🔥` `+40%`
1. [王安宇CELINE品牌大使](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87CELINE%E5%93%81%E7%89%8C%E5%A4%A7%E4%BD%BF%23) `514.5K 🔥` `+37%`
1. [刘文祥头像](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E5%A4%B4%E5%83%8F%23) `514.3K 🔥` `+65%`
1. [世界油阀关闭](https://s.weibo.com/weibo?q=%23%E4%B8%96%E7%95%8C%E6%B2%B9%E9%98%80%E5%85%B3%E9%97%AD%23) `508.4K 🔥` `+51%`
1. [元宵晚会节目单](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E6%99%9A%E4%BC%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `503.7K 🔥` `+61%`
1. [舅舅去世舅妈向正月理发外甥索赔百万](https://s.weibo.com/weibo?q=%23%E8%88%85%E8%88%85%E5%8E%BB%E4%B8%96%E8%88%85%E5%A6%88%E5%90%91%E6%AD%A3%E6%9C%88%E7%90%86%E5%8F%91%E5%A4%96%E7%94%A5%E7%B4%A2%E8%B5%94%E7%99%BE%E4%B8%87%23) `487.0K 🔥` `+57%`
1. [油价或涨超70% (Oil prices may rise by more than 70%)](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E6%88%96%E6%B6%A8%E8%B6%8570%25%23) `477.4K 🔥` `+54%`
1. [伊朗纳坦兹核设施遭破坏](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%BA%B3%E5%9D%A6%E5%85%B9%E6%A0%B8%E8%AE%BE%E6%96%BD%E9%81%AD%E7%A0%B4%E5%9D%8F%23) `455.2K 🔥` `+48%`
1. [刘文祥麻辣烫暂停新合作 (Liu Wenxiang Malatang suspends new cooperation)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E6%9A%82%E5%81%9C%E6%96%B0%E5%90%88%E4%BD%9C%23) `445.4K 🔥` `+43%`
1. [小满春春在一起了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E6%BB%A1%E6%98%A5%E6%98%A5%E5%9C%A8%E4%B8%80%E8%B5%B7%E4%BA%86%23) `438.9K 🔥` `+52%`
1. [建议A股延至下午4点闭市](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AEA%E8%82%A1%E5%BB%B6%E8%87%B3%E4%B8%8B%E5%8D%884%E7%82%B9%E9%97%AD%E5%B8%82%23) `423.0K 🔥` `+40%`
1. [汤圆 (sweet dumpling)](https://s.weibo.com/weibo?q=%23%E6%B1%A4%E5%9C%86%23) `421.3K 🔥` `+45%`
1. [迪奥官宣王楚然](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E5%A5%A5%E5%AE%98%E5%AE%A3%E7%8E%8B%E6%A5%9A%E7%84%B6%23) `403.8K 🔥` `+35%`
1. [深圳租金涨了](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E7%A7%9F%E9%87%91%E6%B6%A8%E4%BA%86%23) `923.3K 🔥`
1. [建议禁止16岁以下使用社媒 (It is recommended that users under the age of 16 are prohibited from using social media)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%A6%81%E6%AD%A216%E5%B2%81%E4%BB%A5%E4%B8%8B%E4%BD%BF%E7%94%A8%E7%A4%BE%E5%AA%92%23) `574.9K 🔥`
1. [伊朗称向美航母发射4枚巡航导弹 (Iran says it fired 4 cruise missiles at US aircraft carrier)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%90%91%E7%BE%8E%E8%88%AA%E6%AF%8D%E5%8F%91%E5%B0%844%E6%9E%9A%E5%B7%A1%E8%88%AA%E5%AF%BC%E5%BC%B9%23) `522.9K 🔥`
1. [元宵节 (Lantern Festival)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E8%8A%82%23) `494.2K 🔥`
1. [黄金白银断崖式下跌 (Gold and silver plummet)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E6%96%AD%E5%B4%96%E5%BC%8F%E4%B8%8B%E8%B7%8C%23) `361.3K 🔥`
1. [穆祉丞王橹杰跨代隐藏卡](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%E7%8E%8B%E6%A9%B9%E6%9D%B0%E8%B7%A8%E4%BB%A3%E9%9A%90%E8%97%8F%E5%8D%A1%23) `331.6K 🔥`
1. [痞幼直播关美颜](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E7%9B%B4%E6%92%AD%E5%85%B3%E7%BE%8E%E9%A2%9C%23) `248.6K 🔥`
1. [以军称打击伊朗总统府](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E7%A7%B0%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E5%BA%9C%23) `248.5K 🔥`
1. [谢霆锋 叫王菲才理人 (Nicholas Tse calls Faye Wong the wise man)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E9%9C%86%E9%94%8B%20%E5%8F%AB%E7%8E%8B%E8%8F%B2%E6%89%8D%E7%90%86%E4%BA%BA%23) `248.5K 🔥`
1. [短剧女主 时尚资源](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E5%A5%B3%E4%B8%BB%20%E6%97%B6%E5%B0%9A%E8%B5%84%E6%BA%90%23) `248.4K 🔥`
1. [樊振东退世排那天照常训练](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E9%80%80%E4%B8%96%E6%8E%92%E9%82%A3%E5%A4%A9%E7%85%A7%E5%B8%B8%E8%AE%AD%E7%BB%83%23) `248.3K 🔥`
1. [2009与2025麦当劳对比 (Comparison of McDonald's in 2009 and 2025)](https://s.weibo.com/weibo?q=%232009%E4%B8%8E2025%E9%BA%A6%E5%BD%93%E5%8A%B3%E5%AF%B9%E6%AF%94%23) `248.2K 🔥`
1. [曝张元英签售一直玩手机 (It is revealed that Zhang Yuanying has been playing with her mobile phone while signing a book)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%BC%A0%E5%85%83%E8%8B%B1%E7%AD%BE%E5%94%AE%E4%B8%80%E7%9B%B4%E7%8E%A9%E6%89%8B%E6%9C%BA%23) `248.2K 🔥`
1. [伊朗称击中了美空军基地大楼 (Iran says it hit US Air Force base building)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%87%BB%E4%B8%AD%E4%BA%86%E7%BE%8E%E7%A9%BA%E5%86%9B%E5%9F%BA%E5%9C%B0%E5%A4%A7%E6%A5%BC%23) `247.9K 🔥`
1. [建议提升教师待遇保障水平](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%8F%90%E5%8D%87%E6%95%99%E5%B8%88%E5%BE%85%E9%81%87%E4%BF%9D%E9%9A%9C%E6%B0%B4%E5%B9%B3%23) `247.7K 🔥`
1. [元宵节赏月全食太浪漫了](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E8%8A%82%E8%B5%8F%E6%9C%88%E5%85%A8%E9%A3%9F%E5%A4%AA%E6%B5%AA%E6%BC%AB%E4%BA%86%23) `247.6K 🔥`
1. [以为是正缘来了没想到是血缘](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%98%AF%E6%AD%A3%E7%BC%98%E6%9D%A5%E4%BA%86%E6%B2%A1%E6%83%B3%E5%88%B0%E6%98%AF%E8%A1%80%E7%BC%98%23) `247.4K 🔥`
1. [烟台一只狗被困井下约3年获救](https://s.weibo.com/weibo?q=%23%E7%83%9F%E5%8F%B0%E4%B8%80%E5%8F%AA%E7%8B%97%E8%A2%AB%E5%9B%B0%E4%BA%95%E4%B8%8B%E7%BA%A63%E5%B9%B4%E8%8E%B7%E6%95%91%23) `247.3K 🔥`
1. [泰星MAi自曝脸部花费几百万 (Thai star MAi revealed that he spent millions on his face)](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E6%98%9FMAi%E8%87%AA%E6%9B%9D%E8%84%B8%E9%83%A8%E8%8A%B1%E8%B4%B9%E5%87%A0%E7%99%BE%E4%B8%87%23) `247.3K 🔥`
1. [短剧演员就业寒冬 (Short drama actors face employment crisis)](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E6%BC%94%E5%91%98%E5%B0%B1%E4%B8%9A%E5%AF%92%E5%86%AC%23) `247.2K 🔥`
1. [油价调整](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E8%B0%83%E6%95%B4%23) `247.0K 🔥`
1. [王一博巴黎时装周行程](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E8%A1%8C%E7%A8%8B%23) `246.8K 🔥`
1. [丈夫回应月子期赶走母亲](https://s.weibo.com/weibo?q=%23%E4%B8%88%E5%A4%AB%E5%9B%9E%E5%BA%94%E6%9C%88%E5%AD%90%E6%9C%9F%E8%B5%B6%E8%B5%B0%E6%AF%8D%E4%BA%B2%23) `246.6K 🔥`

Updated at 2026-03-03 19:19:07

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
