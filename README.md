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

1. [建议推行婴幼儿父母弹性上下班 (It is recommended to implement flexible commuting for parents of infants and young children)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%8E%A8%E8%A1%8C%E5%A9%B4%E5%B9%BC%E5%84%BF%E7%88%B6%E6%AF%8D%E5%BC%B9%E6%80%A7%E4%B8%8A%E4%B8%8B%E7%8F%AD%23) `735.2K 🔥` `NEW`
1. [华莱士正式宣布退市](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E8%8E%B1%E5%A3%AB%E6%AD%A3%E5%BC%8F%E5%AE%A3%E5%B8%83%E9%80%80%E5%B8%82%23) `574.3K 🔥` `NEW`
1. [她的盛焰定档](https://s.weibo.com/weibo?q=%23%E5%A5%B9%E7%9A%84%E7%9B%9B%E7%84%B0%E5%AE%9A%E6%A1%A3%23) `468.8K 🔥` `NEW`
1. [建议引入物业公司竞争机制](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%BC%95%E5%85%A5%E7%89%A9%E4%B8%9A%E5%85%AC%E5%8F%B8%E7%AB%9E%E4%BA%89%E6%9C%BA%E5%88%B6%23) `398.2K 🔥` `NEW`
1. [女子将老公送金镯扔地上又响又跳](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%B0%86%E8%80%81%E5%85%AC%E9%80%81%E9%87%91%E9%95%AF%E6%89%94%E5%9C%B0%E4%B8%8A%E5%8F%88%E5%93%8D%E5%8F%88%E8%B7%B3%23) `333.1K 🔥` `NEW`
1. [驻韩美军6部萨德发射车全部运出](https://s.weibo.com/weibo?q=%23%E9%A9%BB%E9%9F%A9%E7%BE%8E%E5%86%9B6%E9%83%A8%E8%90%A8%E5%BE%B7%E5%8F%91%E5%B0%84%E8%BD%A6%E5%85%A8%E9%83%A8%E8%BF%90%E5%87%BA%23) `330.4K 🔥` `NEW`
1. [井胧酒吧开业披哥都来支持了](https://s.weibo.com/weibo?q=%23%E4%BA%95%E8%83%A7%E9%85%92%E5%90%A7%E5%BC%80%E4%B8%9A%E6%8A%AB%E5%93%A5%E9%83%BD%E6%9D%A5%E6%94%AF%E6%8C%81%E4%BA%86%23) `328.8K 🔥` `NEW`
1. [向佐差点踢到主持人的头](https://s.weibo.com/weibo?q=%23%E5%90%91%E4%BD%90%E5%B7%AE%E7%82%B9%E8%B8%A2%E5%88%B0%E4%B8%BB%E6%8C%81%E4%BA%BA%E7%9A%84%E5%A4%B4%23) `307.0K 🔥` `NEW`
1. [詹姆斯回应阿德巴约破纪录](https://s.weibo.com/weibo?q=%23%E8%A9%B9%E5%A7%86%E6%96%AF%E5%9B%9E%E5%BA%94%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A6%E7%A0%B4%E7%BA%AA%E5%BD%95%23) `138.0K 🔥` `NEW`
1. [猫 她用的都是我的动作啊](https://s.weibo.com/weibo?q=%23%E7%8C%AB%20%E5%A5%B9%E7%94%A8%E7%9A%84%E9%83%BD%E6%98%AF%E6%88%91%E7%9A%84%E5%8A%A8%E4%BD%9C%E5%95%8A%23) `133.6K 🔥` `NEW`
1. [逐玉播出实绩 (Zhuyu broadcast performance)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E6%92%AD%E5%87%BA%E5%AE%9E%E7%BB%A9%23) `119.4K 🔥` `NEW`
1. [电脑售价或上涨40%](https://s.weibo.com/weibo?q=%23%E7%94%B5%E8%84%91%E5%94%AE%E4%BB%B7%E6%88%96%E4%B8%8A%E6%B6%A840%25%23) `116.8K 🔥` `NEW`
1. [我以为长大后会自动变成王子文](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%A5%E4%B8%BA%E9%95%BF%E5%A4%A7%E5%90%8E%E4%BC%9A%E8%87%AA%E5%8A%A8%E5%8F%98%E6%88%90%E7%8E%8B%E5%AD%90%E6%96%87%23) `115.1K 🔥` `NEW`
1. [伊朗称正在霍尔木兹海峡等待美海军](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%AD%A3%E5%9C%A8%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E7%AD%89%E5%BE%85%E7%BE%8E%E6%B5%B7%E5%86%9B%23) `114.6K 🔥` `NEW`
1. [杨紫罗马时装周出发图](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%BD%97%E9%A9%AC%E6%97%B6%E8%A3%85%E5%91%A8%E5%87%BA%E5%8F%91%E5%9B%BE%23) `110.8K 🔥` `NEW`
1. [联合国警告以美袭击伊朗后果](https://s.weibo.com/weibo?q=%23%E8%81%94%E5%90%88%E5%9B%BD%E8%AD%A6%E5%91%8A%E4%BB%A5%E7%BE%8E%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E5%90%8E%E6%9E%9C%23) `109.6K 🔥` `NEW`
1. [开30万的车捡3块钱的废品](https://s.weibo.com/weibo?q=%23%E5%BC%8030%E4%B8%87%E7%9A%84%E8%BD%A6%E6%8D%A13%E5%9D%97%E9%92%B1%E7%9A%84%E5%BA%9F%E5%93%81%23) `106.2K 🔥` `NEW`
1. [汾酒回应多名硕士拟录为酿酒工成装工](https://s.weibo.com/weibo?q=%23%E6%B1%BE%E9%85%92%E5%9B%9E%E5%BA%94%E5%A4%9A%E5%90%8D%E7%A1%95%E5%A3%AB%E6%8B%9F%E5%BD%95%E4%B8%BA%E9%85%BF%E9%85%92%E5%B7%A5%E6%88%90%E8%A3%85%E5%B7%A5%23) `99.5K 🔥` `NEW`
1. [宋雨琦打工精神状态绝了](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E6%89%93%E5%B7%A5%E7%B2%BE%E7%A5%9E%E7%8A%B6%E6%80%81%E7%BB%9D%E4%BA%86%23) `95.1K 🔥` `NEW`
1. [家里有三高人群警惕带状疱疹](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%87%8C%E6%9C%89%E4%B8%89%E9%AB%98%E4%BA%BA%E7%BE%A4%E8%AD%A6%E6%83%95%E5%B8%A6%E7%8A%B6%E7%96%B1%E7%96%B9%23) `92.2K 🔥` `NEW`
1. [怪不得小孩总是一哭就找妈妈 (No wonder children always look for their mothers when they cry)](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E5%B0%8F%E5%AD%A9%E6%80%BB%E6%98%AF%E4%B8%80%E5%93%AD%E5%B0%B1%E6%89%BE%E5%A6%88%E5%A6%88%23) `92.0K 🔥` `NEW`
1. [81岁爷爷被火鸡面攻击了](https://s.weibo.com/weibo?q=%2381%E5%B2%81%E7%88%B7%E7%88%B7%E8%A2%AB%E7%81%AB%E9%B8%A1%E9%9D%A2%E6%94%BB%E5%87%BB%E4%BA%86%23) `78.3K 🔥` `NEW`
1. [苏群谈阿德巴约单场83分](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BE%A4%E8%B0%88%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A6%E5%8D%95%E5%9C%BA83%E5%88%86%23) `78.2K 🔥` `NEW`
1. [这三位河南代表的绰号大家都知道](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B8%89%E4%BD%8D%E6%B2%B3%E5%8D%97%E4%BB%A3%E8%A1%A8%E7%9A%84%E7%BB%B0%E5%8F%B7%E5%A4%A7%E5%AE%B6%E9%83%BD%E7%9F%A5%E9%81%93%23) `78.0K 🔥` `NEW`
1. [代拍给林允拍出神图了](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E6%8B%8D%E7%BB%99%E6%9E%97%E5%85%81%E6%8B%8D%E5%87%BA%E7%A5%9E%E5%9B%BE%E4%BA%86%23) `71.8K 🔥` `NEW`
1. [逐玉 赋魅](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E8%B5%8B%E9%AD%85%23) `69.3K 🔥` `NEW`
1. [人类幼崽的手有多小](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%B1%BB%E5%B9%BC%E5%B4%BD%E7%9A%84%E6%89%8B%E6%9C%89%E5%A4%9A%E5%B0%8F%23) `64.4K 🔥` `NEW`
1. [这穿搭在哪都可以原地上班](https://s.weibo.com/weibo?q=%23%E8%BF%99%E7%A9%BF%E6%90%AD%E5%9C%A8%E5%93%AA%E9%83%BD%E5%8F%AF%E4%BB%A5%E5%8E%9F%E5%9C%B0%E4%B8%8A%E7%8F%AD%23) `64.1K 🔥` `NEW`
1. [荷兰菜竟然走出荷兰了](https://s.weibo.com/weibo?q=%23%E8%8D%B7%E5%85%B0%E8%8F%9C%E7%AB%9F%E7%84%B6%E8%B5%B0%E5%87%BA%E8%8D%B7%E5%85%B0%E4%BA%86%23) `63.8K 🔥` `NEW`
1. [曝苹果放弃小折叠iPhone](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%8B%B9%E6%9E%9C%E6%94%BE%E5%BC%83%E5%B0%8F%E6%8A%98%E5%8F%A0iPhone%23) `63.0K 🔥` `NEW`
1. [看完感觉又上了一天班 (After watching it, I feel like I’ve been working for another day)](https://s.weibo.com/weibo?q=%23%E7%9C%8B%E5%AE%8C%E6%84%9F%E8%A7%89%E5%8F%88%E4%B8%8A%E4%BA%86%E4%B8%80%E5%A4%A9%E7%8F%AD%23) `62.0K 🔥` `NEW`
1. [巴黎时装周](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%23) `61.1K 🔥` `NEW`
1. [政协会议圆满完成各项议程](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%8D%8F%E4%BC%9A%E8%AE%AE%E5%9C%86%E6%BB%A1%E5%AE%8C%E6%88%90%E5%90%84%E9%A1%B9%E8%AE%AE%E7%A8%8B%23) `365.9K 🔥` `+73%`
1. [工作不满10年休5天年假规则该调整](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%BD%9C%E4%B8%8D%E6%BB%A110%E5%B9%B4%E4%BC%915%E5%A4%A9%E5%B9%B4%E5%81%87%E8%A7%84%E5%88%99%E8%AF%A5%E8%B0%83%E6%95%B4%23) `1.0M 🔥`
1. [苹果最便宜手机来了](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%9C%80%E4%BE%BF%E5%AE%9C%E6%89%8B%E6%9C%BA%E6%9D%A5%E4%BA%86%23) `175.9K 🔥`
1. [刘冲选的刘浩存李庚希封面图](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%86%B2%E9%80%89%E7%9A%84%E5%88%98%E6%B5%A9%E5%AD%98%E6%9D%8E%E5%BA%9A%E5%B8%8C%E5%B0%81%E9%9D%A2%E5%9B%BE%23) `103.9K 🔥`
1. [伊朗逮捕81名内鬼](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%80%AE%E6%8D%9581%E5%90%8D%E5%86%85%E9%AC%BC%23) `83.1K 🔥`
1. [中国两会将为全球创造更多机遇 (China’s Two Sessions will create more opportunities for the world)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E5%B0%86%E4%B8%BA%E5%85%A8%E7%90%83%E5%88%9B%E9%80%A0%E6%9B%B4%E5%A4%9A%E6%9C%BA%E9%81%87%23) `595.7K 🔥` `-38%`
1. [政协会议闭幕 (CPPCC meeting closes)](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%8D%8F%E4%BC%9A%E8%AE%AE%E9%97%AD%E5%B9%95%23) `539.0K 🔥` `-47%`
1. [伊朗下起毒雨](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8B%E8%B5%B7%E6%AF%92%E9%9B%A8%23) `510.0K 🔥` `-44%`
1. [阿德巴约83分](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A683%E5%88%86%23) `452.6K 🔥` `-52%`
1. [王励勤称正在与樊振东沟通](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B1%E5%8B%A4%E7%A7%B0%E6%AD%A3%E5%9C%A8%E4%B8%8E%E6%A8%8A%E6%8C%AF%E4%B8%9C%E6%B2%9F%E9%80%9A%23) `103.8K 🔥` `-36%`
1. [等我小了我也要这么晒太阳 (When I grow up, I will also bask in the sun like this)](https://s.weibo.com/weibo?q=%23%E7%AD%89%E6%88%91%E5%B0%8F%E4%BA%86%E6%88%91%E4%B9%9F%E8%A6%81%E8%BF%99%E4%B9%88%E6%99%92%E5%A4%AA%E9%98%B3%23) `101.7K 🔥` `-89%`
1. [逐玉原著的女主](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8E%9F%E8%91%97%E7%9A%84%E5%A5%B3%E4%B8%BB%23) `91.6K 🔥` `-55%`
1. [阿德巴约现役得分王](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A6%E7%8E%B0%E5%BD%B9%E5%BE%97%E5%88%86%E7%8E%8B%23) `82.9K 🔥` `-85%`
1. [伊朗发起第37波打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC37%E6%B3%A2%E6%89%93%E5%87%BB%23) `77.9K 🔥` `-24%`
1. [哈哈哈哈哈6铁三角回归 (Hahahahaha 6 iron triangle returns)](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%93%88%E5%93%88%E5%93%88%E5%93%886%E9%93%81%E4%B8%89%E8%A7%92%E5%9B%9E%E5%BD%92%23) `75.2K 🔥` `-53%`
1. [美国要求以色列勿袭伊朗能源设施](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E8%A6%81%E6%B1%82%E4%BB%A5%E8%89%B2%E5%88%97%E5%8B%BF%E8%A2%AD%E4%BC%8A%E6%9C%97%E8%83%BD%E6%BA%90%E8%AE%BE%E6%96%BD%23) `74.4K 🔥` `-62%`
1. [相差十岁的兄妹一天没见就紧紧相拥](https://s.weibo.com/weibo?q=%23%E7%9B%B8%E5%B7%AE%E5%8D%81%E5%B2%81%E7%9A%84%E5%85%84%E5%A6%B9%E4%B8%80%E5%A4%A9%E6%B2%A1%E8%A7%81%E5%B0%B1%E7%B4%A7%E7%B4%A7%E7%9B%B8%E6%8B%A5%23) `73.2K 🔥` `-31%`
1. [日本是一个老龄化很严重的国家](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%98%AF%E4%B8%80%E4%B8%AA%E8%80%81%E9%BE%84%E5%8C%96%E5%BE%88%E4%B8%A5%E9%87%8D%E7%9A%84%E5%9B%BD%E5%AE%B6%23) `60.2K 🔥` `-64%`

Updated at 2026-03-11 12:25:06

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
