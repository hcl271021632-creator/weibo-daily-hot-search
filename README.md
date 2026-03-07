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

1. [教资 (teaching resources)](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%23) `752.4K 🔥` `NEW`
1. [十五五109项重大工程项目思维导图](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94109%E9%A1%B9%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%E9%A1%B9%E7%9B%AE%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE%23) `597.6K 🔥` `NEW`
1. [40年前的丧假制度该更新了](https://s.weibo.com/weibo?q=%2340%E5%B9%B4%E5%89%8D%E7%9A%84%E4%B8%A7%E5%81%87%E5%88%B6%E5%BA%A6%E8%AF%A5%E6%9B%B4%E6%96%B0%E4%BA%86%23) `507.9K 🔥` `NEW`
1. [教资作文](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E4%BD%9C%E6%96%87%23) `457.1K 🔥` `NEW`
1. [不会化妆的女生建议反复观看](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BC%9A%E5%8C%96%E5%A6%86%E7%9A%84%E5%A5%B3%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%8F%8D%E5%A4%8D%E8%A7%82%E7%9C%8B%23) `447.7K 🔥` `NEW`
1. [刘敏涛倒第二遍水这段真绷不住了](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%95%8F%E6%B6%9B%E5%80%92%E7%AC%AC%E4%BA%8C%E9%81%8D%E6%B0%B4%E8%BF%99%E6%AE%B5%E7%9C%9F%E7%BB%B7%E4%B8%8D%E4%BD%8F%E4%BA%86%23) `407.7K 🔥` `NEW`
1. [张凌赫感谢惠英红推荐逐玉](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%84%9F%E8%B0%A2%E6%83%A0%E8%8B%B1%E7%BA%A2%E6%8E%A8%E8%8D%90%E9%80%90%E7%8E%89%23) `342.7K 🔥` `NEW`
1. [报告里这些民生举措触手可及](https://s.weibo.com/weibo?q=%23%E6%8A%A5%E5%91%8A%E9%87%8C%E8%BF%99%E4%BA%9B%E6%B0%91%E7%94%9F%E4%B8%BE%E6%8E%AA%E8%A7%A6%E6%89%8B%E5%8F%AF%E5%8F%8A%23) `196.5K 🔥` `NEW`
1. [所有省份已推行课间15分钟](https://s.weibo.com/weibo?q=%23%E6%89%80%E6%9C%89%E7%9C%81%E4%BB%BD%E5%B7%B2%E6%8E%A8%E8%A1%8C%E8%AF%BE%E9%97%B415%E5%88%86%E9%92%9F%23) `191.7K 🔥` `NEW`
1. [麦当劳CEO再被网友扒出假吃](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E5%86%8D%E8%A2%AB%E7%BD%91%E5%8F%8B%E6%89%92%E5%87%BA%E5%81%87%E5%90%83%23) `191.0K 🔥` `NEW`
1. [花儿与少年8 (Flowers and Boys 8)](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%84%BF%E4%B8%8E%E5%B0%91%E5%B9%B48%23) `189.7K 🔥` `NEW`
1. [张凯丽谈20天婚假公司只批3天](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%AF%E4%B8%BD%E8%B0%8820%E5%A4%A9%E5%A9%9A%E5%81%87%E5%85%AC%E5%8F%B8%E5%8F%AA%E6%89%B93%E5%A4%A9%23) `187.8K 🔥` `NEW`
1. [俄方警告芬兰](https://s.weibo.com/weibo?q=%23%E4%BF%84%E6%96%B9%E8%AD%A6%E5%91%8A%E8%8A%AC%E5%85%B0%23) `187.0K 🔥` `NEW`
1. [惠英红也在看逐玉](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%E4%B9%9F%E5%9C%A8%E7%9C%8B%E9%80%90%E7%8E%89%23) `185.1K 🔥` `NEW`
1. [成年男性腰围控制90cm以内女性85以内](https://s.weibo.com/weibo?q=%23%E6%88%90%E5%B9%B4%E7%94%B7%E6%80%A7%E8%85%B0%E5%9B%B4%E6%8E%A7%E5%88%B690cm%E4%BB%A5%E5%86%85%E5%A5%B3%E6%80%A785%E4%BB%A5%E5%86%85%23) `178.8K 🔥` `NEW`
1. [内娱吻戏关系网](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A8%B1%E5%90%BB%E6%88%8F%E5%85%B3%E7%B3%BB%E7%BD%91%23) `178.5K 🔥` `NEW`
1. [教资答案](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E7%AD%94%E6%A1%88%23) `177.8K 🔥` `NEW`
1. [王一博周围全是LV集团高层](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%91%A8%E5%9B%B4%E5%85%A8%E6%98%AFLV%E9%9B%86%E5%9B%A2%E9%AB%98%E5%B1%82%23) `172.5K 🔥` `NEW`
1. [恋与深空](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%23) `155.0K 🔥` `NEW`
1. [好好吃饭的重要性太大了](https://s.weibo.com/weibo?q=%23%E5%A5%BD%E5%A5%BD%E5%90%83%E9%A5%AD%E7%9A%84%E9%87%8D%E8%A6%81%E6%80%A7%E5%A4%AA%E5%A4%A7%E4%BA%86%23) `154.6K 🔥` `NEW`
1. [王劲松刘威演谭松韵的两个爸 (Wang Jinsong and Liu Wei play Tan Songyun’s two fathers)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B2%E6%9D%BE%E5%88%98%E5%A8%81%E6%BC%94%E8%B0%AD%E6%9D%BE%E9%9F%B5%E7%9A%84%E4%B8%A4%E4%B8%AA%E7%88%B8%23) `145.8K 🔥` `NEW`
1. [张凌赫不想在林俊杰面前丢脸](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%B8%8D%E6%83%B3%E5%9C%A8%E6%9E%97%E4%BF%8A%E6%9D%B0%E9%9D%A2%E5%89%8D%E4%B8%A2%E8%84%B8%23) `125.3K 🔥` `NEW`
1. [建议对电影不满意可退票](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%AF%B9%E7%94%B5%E5%BD%B1%E4%B8%8D%E6%BB%A1%E6%84%8F%E5%8F%AF%E9%80%80%E7%A5%A8%23) `118.6K 🔥` `NEW`
1. [教资选择题](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E9%80%89%E6%8B%A9%E9%A2%98%23) `112.1K 🔥` `NEW`
1. [医生回应女子泡脚3个月皮肤变色](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%AD%90%E6%B3%A1%E8%84%9A3%E4%B8%AA%E6%9C%88%E7%9A%AE%E8%82%A4%E5%8F%98%E8%89%B2%23) `108.2K 🔥` `NEW`
1. [教资科一](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E7%A7%91%E4%B8%80%23) `107.1K 🔥` `NEW`
1. [真凶只有一个但嫌犯有八十个](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E5%87%B6%E5%8F%AA%E6%9C%89%E4%B8%80%E4%B8%AA%E4%BD%86%E5%AB%8C%E7%8A%AF%E6%9C%89%E5%85%AB%E5%8D%81%E4%B8%AA%23) `106.8K 🔥` `NEW`
1. [今年38节流行即时送礼](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B438%E8%8A%82%E6%B5%81%E8%A1%8C%E5%8D%B3%E6%97%B6%E9%80%81%E7%A4%BC%23) `96.0K 🔥` `NEW`
1. [养龙虾](https://s.weibo.com/weibo?q=%23%E5%85%BB%E9%BE%99%E8%99%BE%23) `95.7K 🔥` `NEW`
1. [这才是送花界的天花板吧](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%89%8D%E6%98%AF%E9%80%81%E8%8A%B1%E7%95%8C%E7%9A%84%E5%A4%A9%E8%8A%B1%E6%9D%BF%E5%90%A7%23) `95.3K 🔥` `NEW`
1. [小学教资作文 (Elementary school teaching materials composition)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A6%E6%95%99%E8%B5%84%E4%BD%9C%E6%96%87%23) `95.2K 🔥` `NEW`
1. [容易抑郁的同学要揉颊车穴](https://s.weibo.com/weibo?q=%23%E5%AE%B9%E6%98%93%E6%8A%91%E9%83%81%E7%9A%84%E5%90%8C%E5%AD%A6%E8%A6%81%E6%8F%89%E9%A2%8A%E8%BD%A6%E7%A9%B4%23) `93.6K 🔥` `NEW`
1. [以军被指击中伊朗直升机涂鸦](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E8%A2%AB%E6%8C%87%E5%87%BB%E4%B8%AD%E4%BC%8A%E6%9C%97%E7%9B%B4%E5%8D%87%E6%9C%BA%E6%B6%82%E9%B8%A6%23) `87.2K 🔥` `NEW`
1. [雷军推荐XiaomiTag](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E6%8E%A8%E8%8D%90XiaomiTag%23) `85.9K 🔥` `NEW`
1. [大学生开学第一课的正确打开方式](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F%E5%BC%80%E5%AD%A6%E7%AC%AC%E4%B8%80%E8%AF%BE%E7%9A%84%E6%AD%A3%E7%A1%AE%E6%89%93%E5%BC%80%E6%96%B9%E5%BC%8F%23) `83.1K 🔥` `NEW`
1. [女子热水泡脚3个月皮肤变色洗不掉](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%83%AD%E6%B0%B4%E6%B3%A1%E8%84%9A3%E4%B8%AA%E6%9C%88%E7%9A%AE%E8%82%A4%E5%8F%98%E8%89%B2%E6%B4%97%E4%B8%8D%E6%8E%89%23) `180.1K 🔥` `+23%`
1. [民生主题记者会 (People's Livelihood Theme Press Conference)](https://s.weibo.com/weibo?q=%23%E6%B0%91%E7%94%9F%E4%B8%BB%E9%A2%98%E8%AE%B0%E8%80%85%E4%BC%9A%23) `1.0M 🔥`
1. [霍尔木兹海峡船只遭袭致4死3重伤](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E8%88%B9%E5%8F%AA%E9%81%AD%E8%A2%AD%E8%87%B44%E6%AD%BB3%E9%87%8D%E4%BC%A4%23) `188.8K 🔥`
1. [德黑兰发生巨大爆炸 (Huge explosion hits Tehran)](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E9%BB%91%E5%85%B0%E5%8F%91%E7%94%9F%E5%B7%A8%E5%A4%A7%E7%88%86%E7%82%B8%23) `186.3K 🔥`
1. [岳雨婷G社出图](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7G%E7%A4%BE%E5%87%BA%E5%9B%BE%23) `175.3K 🔥`
1. [4岁女儿被诊断为男孩需选性别做手术](https://s.weibo.com/weibo?q=%234%E5%B2%81%E5%A5%B3%E5%84%BF%E8%A2%AB%E8%AF%8A%E6%96%AD%E4%B8%BA%E7%94%B7%E5%AD%A9%E9%9C%80%E9%80%89%E6%80%A7%E5%88%AB%E5%81%9A%E6%89%8B%E6%9C%AF%23) `169.5K 🔥`
1. [易烊千玺网站续费到2035年](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E7%BD%91%E7%AB%99%E7%BB%AD%E8%B4%B9%E5%88%B02035%E5%B9%B4%23) `146.7K 🔥`
1. [白鹿进组要下半年往后了 (Bailu will join the group in the second half of the year)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E8%BF%9B%E7%BB%84%E8%A6%81%E4%B8%8B%E5%8D%8A%E5%B9%B4%E5%BE%80%E5%90%8E%E4%BA%86%23) `120.7K 🔥`
1. [原来这就是录音的意义 (It turns out that this is the meaning of recording)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E5%B0%B1%E6%98%AF%E5%BD%95%E9%9F%B3%E7%9A%84%E6%84%8F%E4%B9%89%23) `106.2K 🔥`
1. [未来五年哪些工作更吃香](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A5%E4%BA%94%E5%B9%B4%E5%93%AA%E4%BA%9B%E5%B7%A5%E4%BD%9C%E6%9B%B4%E5%90%83%E9%A6%99%23) `184.3K 🔥` `-75%`
1. [TESnaiyou 假赛](https://s.weibo.com/weibo?q=%23TESnaiyou%20%E5%81%87%E8%B5%9B%23) `136.8K 🔥` `-36%`
1. [陈飞宇 吃的也不多还是得活着](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%20%E5%90%83%E7%9A%84%E4%B9%9F%E4%B8%8D%E5%A4%9A%E8%BF%98%E6%98%AF%E5%BE%97%E6%B4%BB%E7%9D%80%23) `97.7K 🔥` `-35%`
1. [普京与伊朗总统通电话](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E4%B8%8E%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E9%80%9A%E7%94%B5%E8%AF%9D%23) `95.5K 🔥` `-35%`
1. [林俊杰给田曦薇迷成啥了](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E7%BB%99%E7%94%B0%E6%9B%A6%E8%96%87%E8%BF%B7%E6%88%90%E5%95%A5%E4%BA%86%23) `94.9K 🔥` `-43%`
1. [逐玉爆开 (Zhuyu explodes)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%88%86%E5%BC%80%23) `81.4K 🔥` `-46%`

Updated at 2026-03-07 12:14:10

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
