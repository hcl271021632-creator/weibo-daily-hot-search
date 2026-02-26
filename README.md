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

1. [网传浪姐7参赛名单 (The list of contestants for Sister Lang 7 is reported online)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E6%B5%AA%E5%A7%907%E5%8F%82%E8%B5%9B%E5%90%8D%E5%8D%95%23) `187.1K 🔥` `NEW`
1. [15后娃开始整顿亲戚](https://s.weibo.com/weibo?q=%2315%E5%90%8E%E5%A8%83%E5%BC%80%E5%A7%8B%E6%95%B4%E9%A1%BF%E4%BA%B2%E6%88%9A%23) `129.5K 🔥` `NEW`
1. [比尔盖茨出轨女性身份曝光](https://s.weibo.com/weibo?q=%23%E6%AF%94%E5%B0%94%E7%9B%96%E8%8C%A8%E5%87%BA%E8%BD%A8%E5%A5%B3%E6%80%A7%E8%BA%AB%E4%BB%BD%E6%9B%9D%E5%85%89%23) `125.2K 🔥` `NEW`
1. [免去王祥喜应急管理部部长职务](https://s.weibo.com/weibo?q=%23%E5%85%8D%E5%8E%BB%E7%8E%8B%E7%A5%A5%E5%96%9C%E5%BA%94%E6%80%A5%E7%AE%A1%E7%90%86%E9%83%A8%E9%83%A8%E9%95%BF%E8%81%8C%E5%8A%A1%23) `114.3K 🔥` `NEW`
1. [老外以为一个姓张的人研究遍及各学科](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%A4%96%E4%BB%A5%E4%B8%BA%E4%B8%80%E4%B8%AA%E5%A7%93%E5%BC%A0%E7%9A%84%E4%BA%BA%E7%A0%94%E7%A9%B6%E9%81%8D%E5%8F%8A%E5%90%84%E5%AD%A6%E7%A7%91%23) `114.2K 🔥` `NEW`
1. [申裕斌赛后飙中文太累了](https://s.weibo.com/weibo?q=%23%E7%94%B3%E8%A3%95%E6%96%8C%E8%B5%9B%E5%90%8E%E9%A3%99%E4%B8%AD%E6%96%87%E5%A4%AA%E7%B4%AF%E4%BA%86%23) `103.4K 🔥` `NEW`
1. [汽车充完电未及时挪车被收438元](https://s.weibo.com/weibo?q=%23%E6%B1%BD%E8%BD%A6%E5%85%85%E5%AE%8C%E7%94%B5%E6%9C%AA%E5%8F%8A%E6%97%B6%E6%8C%AA%E8%BD%A6%E8%A2%AB%E6%94%B6438%E5%85%83%23) `103.3K 🔥` `NEW`
1. [张艺兴小张入职第一天](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%89%BA%E5%85%B4%E5%B0%8F%E5%BC%A0%E5%85%A5%E8%81%8C%E7%AC%AC%E4%B8%80%E5%A4%A9%23) `103.2K 🔥` `NEW`
1. [整治幽灵外卖新规发布](https://s.weibo.com/weibo?q=%23%E6%95%B4%E6%B2%BB%E5%B9%BD%E7%81%B5%E5%A4%96%E5%8D%96%E6%96%B0%E8%A7%84%E5%8F%91%E5%B8%83%23) `103.1K 🔥` `NEW`
1. [尘白禁区 中国邮政](https://s.weibo.com/weibo?q=%23%E5%B0%98%E7%99%BD%E7%A6%81%E5%8C%BA%20%E4%B8%AD%E5%9B%BD%E9%82%AE%E6%94%BF%23) `100.6K 🔥` `NEW`
1. [陌生网友帮新娘堵门被邀坐主桌 (Strange netizen helped the bride block the door and was invited to sit at the main table)](https://s.weibo.com/weibo?q=%23%E9%99%8C%E7%94%9F%E7%BD%91%E5%8F%8B%E5%B8%AE%E6%96%B0%E5%A8%98%E5%A0%B5%E9%97%A8%E8%A2%AB%E9%82%80%E5%9D%90%E4%B8%BB%E6%A1%8C%23) `99.0K 🔥` `NEW`
1. [陈妍希说英语](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A6%8D%E5%B8%8C%E8%AF%B4%E8%8B%B1%E8%AF%AD%23) `95.2K 🔥` `NEW`
1. [有人早上6点去寿司郎排队](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%BA%BA%E6%97%A9%E4%B8%8A6%E7%82%B9%E5%8E%BB%E5%AF%BF%E5%8F%B8%E9%83%8E%E6%8E%92%E9%98%9F%23) `78.1K 🔥` `NEW`
1. [KSG战胜DYG](https://s.weibo.com/weibo?q=%23KSG%E6%88%98%E8%83%9CDYG%23) `74.6K 🔥` `NEW`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `74.4K 🔥` `NEW`
1. [男子谎称走亲戚欲把7岁儿子留老家](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%B0%8E%E7%A7%B0%E8%B5%B0%E4%BA%B2%E6%88%9A%E6%AC%B2%E6%8A%8A7%E5%B2%81%E5%84%BF%E5%AD%90%E7%95%99%E8%80%81%E5%AE%B6%23) `433.7K 🔥` `+295%`
1. [苹果新品来了](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%96%B0%E5%93%81%E6%9D%A5%E4%BA%86%23) `430.5K 🔥` `+61%`
1. [王楚钦1比7落后逆转 (Wang Chuqin came back from behind 1-7)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A61%E6%AF%947%E8%90%BD%E5%90%8E%E9%80%86%E8%BD%AC%23) `279.9K 🔥` `+85%`
1. [Cat毕业典礼](https://s.weibo.com/weibo?q=%23Cat%E6%AF%95%E4%B8%9A%E5%85%B8%E7%A4%BC%23) `199.1K 🔥` `+63%`
1. [24岁女生成功诞下1男4女5胞胎 (24-year-old girl successfully gave birth to quintuplets, 1 boy, 4 girls)](https://s.weibo.com/weibo?q=%2324%E5%B2%81%E5%A5%B3%E7%94%9F%E6%88%90%E5%8A%9F%E8%AF%9E%E4%B8%8B1%E7%94%B74%E5%A5%B35%E8%83%9E%E8%83%8E%23) `1.2M 🔥`
1. [手机 涨价](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%20%E6%B6%A8%E4%BB%B7%23) `871.1K 🔥`
1. [迪丽热巴 瓦猫 (dilireba watt cat)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%20%E7%93%A6%E7%8C%AB%23) `599.1K 🔥`
1. [上海迪士尼10岁生日](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E8%BF%AA%E5%A3%AB%E5%B0%BC10%E5%B2%81%E7%94%9F%E6%97%A5%23) `353.0K 🔥`
1. [中方回应金正恩对韩表态 (China responds to Kim Jong-un’s stance on South Korea)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E9%87%91%E6%AD%A3%E6%81%A9%E5%AF%B9%E9%9F%A9%E8%A1%A8%E6%80%81%23) `235.8K 🔥`
1. [冬奥花滑冠军刘美贤遭俄罗斯粉丝吐槽](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E8%8A%B1%E6%BB%91%E5%86%A0%E5%86%9B%E5%88%98%E7%BE%8E%E8%B4%A4%E9%81%AD%E4%BF%84%E7%BD%97%E6%96%AF%E7%B2%89%E4%B8%9D%E5%90%90%E6%A7%BD%23) `229.7K 🔥`
1. [Prada认领杨幂](https://s.weibo.com/weibo?q=%23Prada%E8%AE%A4%E9%A2%86%E6%9D%A8%E5%B9%82%23) `227.6K 🔥`
1. [向佑不满遗产分配直喊不公平 (Xiang You is dissatisfied with the inheritance distribution and calls it unfair)](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%91%E4%B8%8D%E6%BB%A1%E9%81%97%E4%BA%A7%E5%88%86%E9%85%8D%E7%9B%B4%E5%96%8A%E4%B8%8D%E5%85%AC%E5%B9%B3%23) `227.4K 🔥`
1. [胡一菲诺澜在短国相遇了](https://s.weibo.com/weibo?q=%23%E8%83%A1%E4%B8%80%E8%8F%B2%E8%AF%BA%E6%BE%9C%E5%9C%A8%E7%9F%AD%E5%9B%BD%E7%9B%B8%E9%81%87%E4%BA%86%23) `195.0K 🔥`
1. [虞书欣红衣主母跳惊鸿一面](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E7%BA%A2%E8%A1%A3%E4%B8%BB%E6%AF%8D%E8%B7%B3%E6%83%8A%E9%B8%BF%E4%B8%80%E9%9D%A2%23) `126.4K 🔥`
1. [王天辰 上桌](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%20%E4%B8%8A%E6%A1%8C%23) `120.0K 🔥`
1. [孙燕姿新歌飞瀑而下](https://s.weibo.com/weibo?q=%23%E5%AD%99%E7%87%95%E5%A7%BF%E6%96%B0%E6%AD%8C%E9%A3%9E%E7%80%91%E8%80%8C%E4%B8%8B%23) `92.8K 🔥`
1. [一趟列车24站解锁200多家景区 (One train unlocks more than 200 scenic spots at 24 stops)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%B6%9F%E5%88%97%E8%BD%A624%E7%AB%99%E8%A7%A3%E9%94%81200%E5%A4%9A%E5%AE%B6%E6%99%AF%E5%8C%BA%23) `652.4K 🔥` `-36%`
1. [尘白禁区发文回应](https://s.weibo.com/weibo?q=%23%E5%B0%98%E7%99%BD%E7%A6%81%E5%8C%BA%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%23) `332.4K 🔥` `-30%`
1. [日本物价居然到这种程度了](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%89%A9%E4%BB%B7%E5%B1%85%E7%84%B6%E5%88%B0%E8%BF%99%E7%A7%8D%E7%A8%8B%E5%BA%A6%E4%BA%86%23) `234.7K 🔥` `-30%`
1. [香港突发山火](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E7%AA%81%E5%8F%91%E5%B1%B1%E7%81%AB%23) `231.9K 🔥` `-80%`
1. [文章上了澳门语文教材是什么体验 (What is it like to have an article published in the Macao Chinese language textbook?)](https://s.weibo.com/weibo?q=%23%E6%96%87%E7%AB%A0%E4%B8%8A%E4%BA%86%E6%BE%B3%E9%97%A8%E8%AF%AD%E6%96%87%E6%95%99%E6%9D%90%E6%98%AF%E4%BB%80%E4%B9%88%E4%BD%93%E9%AA%8C%23) `132.3K 🔥` `-45%`
1. [杨幂怼脸镜头好美](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%80%BC%E8%84%B8%E9%95%9C%E5%A4%B4%E5%A5%BD%E7%BE%8E%23) `132.3K 🔥` `-36%`
1. [中国邮政回应已叫停相关线下活动 (China Post responded that it has suspended relevant offline activities.)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%82%AE%E6%94%BF%E5%9B%9E%E5%BA%94%E5%B7%B2%E5%8F%AB%E5%81%9C%E7%9B%B8%E5%85%B3%E7%BA%BF%E4%B8%8B%E6%B4%BB%E5%8A%A8%23) `129.4K 🔥` `-28%`
1. [橹穆双人舞台官摄破2711万](https://s.weibo.com/weibo?q=%23%E6%A9%B9%E7%A9%86%E5%8F%8C%E4%BA%BA%E8%88%9E%E5%8F%B0%E5%AE%98%E6%91%84%E7%A0%B42711%E4%B8%87%23) `127.6K 🔥` `-38%`
1. [嘉人单发苏新皓](https://s.weibo.com/weibo?q=%23%E5%98%89%E4%BA%BA%E5%8D%95%E5%8F%91%E8%8B%8F%E6%96%B0%E7%9A%93%23) `121.9K 🔥` `-27%`
1. [JDG战胜AL](https://s.weibo.com/weibo?q=%23JDG%E6%88%98%E8%83%9CAL%23) `114.9K 🔥` `-44%`
1. [创造营2026女生季](https://s.weibo.com/weibo?q=%23%E5%88%9B%E9%80%A0%E8%90%A52026%E5%A5%B3%E7%94%9F%E5%AD%A3%23) `114.8K 🔥` `-37%`
1. [王橹杰手捧红玫瑰 (Wang Lujie holds red roses in hand)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%89%8B%E6%8D%A7%E7%BA%A2%E7%8E%AB%E7%91%B0%23) `114.7K 🔥` `-23%`
1. [郭富城一家去景区只用买一张票](https://s.weibo.com/weibo?q=%23%E9%83%AD%E5%AF%8C%E5%9F%8E%E4%B8%80%E5%AE%B6%E5%8E%BB%E6%99%AF%E5%8C%BA%E5%8F%AA%E7%94%A8%E4%B9%B0%E4%B8%80%E5%BC%A0%E7%A5%A8%23) `114.0K 🔥` `-31%`
1. [中国男篮战胜日本男篮 (Chinese men's basketball team defeats Japanese men's basketball team)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE%E6%88%98%E8%83%9C%E6%97%A5%E6%9C%AC%E7%94%B7%E7%AF%AE%23) `113.9K 🔥` `-45%`
1. [兔闪闪道歉](https://s.weibo.com/weibo?q=%23%E5%85%94%E9%97%AA%E9%97%AA%E9%81%93%E6%AD%89%23) `103.1K 🔥` `-43%`
1. [领克致歉语音误关大灯](https://s.weibo.com/weibo?q=%23%E9%A2%86%E5%85%8B%E8%87%B4%E6%AD%89%E8%AF%AD%E9%9F%B3%E8%AF%AF%E5%85%B3%E5%A4%A7%E7%81%AF%23) `99.0K 🔥` `-24%`
1. [发1.8亿年终奖公司开工3天爆单 (Company that issued 180 million year-end bonus received huge orders within 3 days of starting work)](https://s.weibo.com/weibo?q=%23%E5%8F%911.8%E4%BA%BF%E5%B9%B4%E7%BB%88%E5%A5%96%E5%85%AC%E5%8F%B8%E5%BC%80%E5%B7%A53%E5%A4%A9%E7%88%86%E5%8D%95%23) `89.6K 🔥` `-34%`
1. [曝迪丽热巴与嘉行合约到期 (It is revealed that Dilireba’s contract with Jiaxing has expired)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%B8%8E%E5%98%89%E8%A1%8C%E5%90%88%E7%BA%A6%E5%88%B0%E6%9C%9F%23) `85.9K 🔥` `-37%`
1. [Prada直播](https://s.weibo.com/weibo?q=%23Prada%E7%9B%B4%E6%92%AD%23) `77.4K 🔥` `-47%`

Updated at 2026-02-26 23:51:49

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
