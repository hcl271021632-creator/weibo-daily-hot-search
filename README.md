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

1. [姚晨曹郁官宣离婚 (Yao Chen and Cao Yu officially announced their divorce)](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E6%99%A8%E6%9B%B9%E9%83%81%E5%AE%98%E5%AE%A3%E7%A6%BB%E5%A9%9A%23) `12.8M 🔥` `NEW`
1. [鸿蒙智行 小米](https://s.weibo.com/weibo?q=%23%E9%B8%BF%E8%92%99%E6%99%BA%E8%A1%8C%20%E5%B0%8F%E7%B1%B3%23) `321.0K 🔥` `NEW`
1. [爱上逐玉是我的宿命](https://s.weibo.com/weibo?q=%23%E7%88%B1%E4%B8%8A%E9%80%90%E7%8E%89%E6%98%AF%E6%88%91%E7%9A%84%E5%AE%BF%E5%91%BD%23) `221.9K 🔥` `NEW`
1. [360元雅诗兰黛口红只有外壳没膏体](https://s.weibo.com/weibo?q=%23360%E5%85%83%E9%9B%85%E8%AF%97%E5%85%B0%E9%BB%9B%E5%8F%A3%E7%BA%A2%E5%8F%AA%E6%9C%89%E5%A4%96%E5%A3%B3%E6%B2%A1%E8%86%8F%E4%BD%93%23) `199.1K 🔥` `NEW`
1. [逐玉 编剧浪费演员颜值](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%BC%96%E5%89%A7%E6%B5%AA%E8%B4%B9%E6%BC%94%E5%91%98%E9%A2%9C%E5%80%BC%23) `198.2K 🔥` `NEW`
1. [深圳卫健委又发力了](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E5%8D%AB%E5%81%A5%E5%A7%94%E5%8F%88%E5%8F%91%E5%8A%9B%E4%BA%86%23) `198.0K 🔥` `NEW`
1. [机皇EA211黄金增程步入增程3.0](https://s.weibo.com/weibo?q=%23%E6%9C%BA%E7%9A%87EA211%E9%BB%84%E9%87%91%E5%A2%9E%E7%A8%8B%E6%AD%A5%E5%85%A5%E5%A2%9E%E7%A8%8B3.0%23) `186.5K 🔥` `NEW`
1. [性格内向的人看起来更显小](https://s.weibo.com/weibo?q=%23%E6%80%A7%E6%A0%BC%E5%86%85%E5%90%91%E7%9A%84%E4%BA%BA%E7%9C%8B%E8%B5%B7%E6%9D%A5%E6%9B%B4%E6%98%BE%E5%B0%8F%23) `174.1K 🔥` `NEW`
1. [ILLIT新专logo被质疑抄袭BLACKPINK](https://s.weibo.com/weibo?q=%23ILLIT%E6%96%B0%E4%B8%93logo%E8%A2%AB%E8%B4%A8%E7%96%91%E6%8A%84%E8%A2%ADBLACKPINK%23) `148.7K 🔥` `NEW`
1. [坠江研究生离世前上完最后一个夜班](https://s.weibo.com/weibo?q=%23%E5%9D%A0%E6%B1%9F%E7%A0%94%E7%A9%B6%E7%94%9F%E7%A6%BB%E4%B8%96%E5%89%8D%E4%B8%8A%E5%AE%8C%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E5%A4%9C%E7%8F%AD%23) `147.5K 🔥` `NEW`
1. [郭碧婷把向太给的钱都存给孩子了 (Guo Biting saved all the money given by Mrs. Xiang to her children)](https://s.weibo.com/weibo?q=%23%E9%83%AD%E7%A2%A7%E5%A9%B7%E6%8A%8A%E5%90%91%E5%A4%AA%E7%BB%99%E7%9A%84%E9%92%B1%E9%83%BD%E5%AD%98%E7%BB%99%E5%AD%A9%E5%AD%90%E4%BA%86%23) `146.8K 🔥` `NEW`
1. [司宫令正式官宣](https://s.weibo.com/weibo?q=%23%E5%8F%B8%E5%AE%AB%E4%BB%A4%E6%AD%A3%E5%BC%8F%E5%AE%98%E5%AE%A3%23) `141.8K 🔥` `NEW`
1. [奥斯卡最佳男主穿新中式领奖](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E6%96%AF%E5%8D%A1%E6%9C%80%E4%BD%B3%E7%94%B7%E4%B8%BB%E7%A9%BF%E6%96%B0%E4%B8%AD%E5%BC%8F%E9%A2%86%E5%A5%96%23) `140.6K 🔥` `NEW`
1. [建议papi酱多请上个世纪的艺人](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AEpapi%E9%85%B1%E5%A4%9A%E8%AF%B7%E4%B8%8A%E4%B8%AA%E4%B8%96%E7%BA%AA%E7%9A%84%E8%89%BA%E4%BA%BA%23) `140.3K 🔥` `NEW`
1. [杨幂保存了关雪穿的旗袍](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E4%BF%9D%E5%AD%98%E4%BA%86%E5%85%B3%E9%9B%AA%E7%A9%BF%E7%9A%84%E6%97%97%E8%A2%8D%23) `133.0K 🔥` `NEW`
1. [时代峰峻养的孩子从不缺教养](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E5%85%BB%E7%9A%84%E5%AD%A9%E5%AD%90%E4%BB%8E%E4%B8%8D%E7%BC%BA%E6%95%99%E5%85%BB%23) `132.9K 🔥` `NEW`
1. [315的价值应当是365](https://s.weibo.com/weibo?q=%23315%E7%9A%84%E4%BB%B7%E5%80%BC%E5%BA%94%E5%BD%93%E6%98%AF365%23) `132.9K 🔥` `NEW`
1. [何炅杨蓉是十指紧扣的关系](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%82%85%E6%9D%A8%E8%93%89%E6%98%AF%E5%8D%81%E6%8C%87%E7%B4%A7%E6%89%A3%E7%9A%84%E5%85%B3%E7%B3%BB%23) `132.9K 🔥` `NEW`
1. [爱穿带帽卫衣的那批人被年龄攻击了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E7%A9%BF%E5%B8%A6%E5%B8%BD%E5%8D%AB%E8%A1%A3%E7%9A%84%E9%82%A3%E6%89%B9%E4%BA%BA%E8%A2%AB%E5%B9%B4%E9%BE%84%E6%94%BB%E5%87%BB%E4%BA%86%23) `114.5K 🔥` `NEW`
1. [王橹杰男鬼人格溢出](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E7%94%B7%E9%AC%BC%E4%BA%BA%E6%A0%BC%E6%BA%A2%E5%87%BA%23) `110.4K 🔥` `NEW`
1. [我最近找工作的心态变化 (My recent change in mentality when looking for a job)](https://s.weibo.com/weibo?q=%23%E6%88%91%E6%9C%80%E8%BF%91%E6%89%BE%E5%B7%A5%E4%BD%9C%E7%9A%84%E5%BF%83%E6%80%81%E5%8F%98%E5%8C%96%23) `106.2K 🔥` `NEW`
1. [胖东来鸡蛋](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E9%B8%A1%E8%9B%8B%23) `97.5K 🔥` `NEW`
1. [布洛芬很着急为您服务 (Ibuprofen is anxious to serve you)](https://s.weibo.com/weibo?q=%23%E5%B8%83%E6%B4%9B%E8%8A%AC%E5%BE%88%E7%9D%80%E6%80%A5%E4%B8%BA%E6%82%A8%E6%9C%8D%E5%8A%A1%23) `229.8K 🔥` `+141%`
1. [芒果一口气宣了20场音乐节](https://s.weibo.com/weibo?q=%23%E8%8A%92%E6%9E%9C%E4%B8%80%E5%8F%A3%E6%B0%94%E5%AE%A3%E4%BA%8620%E5%9C%BA%E9%9F%B3%E4%B9%90%E8%8A%82%23) `199.3K 🔥` `+48%`
1. [邓凯妈妈 有那么帅吗](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E5%A6%88%E5%A6%88%20%E6%9C%89%E9%82%A3%E4%B9%88%E5%B8%85%E5%90%97%23) `198.0K 🔥` `+48%`
1. [埃文凯尔官宣定居中国 (Evan Kyle officially announced to settle in China)](https://s.weibo.com/weibo?q=%23%E5%9F%83%E6%96%87%E5%87%AF%E5%B0%94%E5%AE%98%E5%AE%A3%E5%AE%9A%E5%B1%85%E4%B8%AD%E5%9B%BD%23) `1.1M 🔥`
1. [315曝光名单 (315 exposure list)](https://s.weibo.com/weibo?q=%23315%E6%9B%9D%E5%85%89%E5%90%8D%E5%8D%95%23) `769.6K 🔥`
1. [致敬每一份不屈的热爱](https://s.weibo.com/weibo?q=%23%E8%87%B4%E6%95%AC%E6%AF%8F%E4%B8%80%E4%BB%BD%E4%B8%8D%E5%B1%88%E7%9A%84%E7%83%AD%E7%88%B1%23) `618.4K 🔥`
1. [伊朗称440公斤60%丰度浓缩铀被埋](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0440%E5%85%AC%E6%96%A460%25%E4%B8%B0%E5%BA%A6%E6%B5%93%E7%BC%A9%E9%93%80%E8%A2%AB%E5%9F%8B%23) `199.4K 🔥`
1. [山姆等多品牌回应双氧水漂白鸡爪](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E7%AD%89%E5%A4%9A%E5%93%81%E7%89%8C%E5%9B%9E%E5%BA%94%E5%8F%8C%E6%B0%A7%E6%B0%B4%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%23) `198.9K 🔥`
1. [经纪人回应瞿颖翻红](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E7%BA%AA%E4%BA%BA%E5%9B%9E%E5%BA%94%E7%9E%BF%E9%A2%96%E7%BF%BB%E7%BA%A2%23) `198.4K 🔥`
1. [小狗舔人被说主人情绪失控 (Puppy licks people and its owner is said to have lost control of his emotions)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E8%88%94%E4%BA%BA%E8%A2%AB%E8%AF%B4%E4%B8%BB%E4%BA%BA%E6%83%85%E7%BB%AA%E5%A4%B1%E6%8E%A7%23) `197.8K 🔥`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `197.7K 🔥`
1. [脑梗最快急救方法](https://s.weibo.com/weibo?q=%23%E8%84%91%E6%A2%97%E6%9C%80%E5%BF%AB%E6%80%A5%E6%95%91%E6%96%B9%E6%B3%95%23) `176.6K 🔥`
1. [周冬雨 刘昊然 (Zhou Dongyu Liu Haoran)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%AC%E9%9B%A8%20%E5%88%98%E6%98%8A%E7%84%B6%23) `176.3K 🔥`
1. [鹿晗 关晓彤](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `175.7K 🔥`
1. [李诞说现在失业的人可能是一件好事](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%AF%9E%E8%AF%B4%E7%8E%B0%E5%9C%A8%E5%A4%B1%E4%B8%9A%E7%9A%84%E4%BA%BA%E5%8F%AF%E8%83%BD%E6%98%AF%E4%B8%80%E4%BB%B6%E5%A5%BD%E4%BA%8B%23) `173.6K 🔥`
1. [都美竹被判向朱姐道歉](https://s.weibo.com/weibo?q=%23%E9%83%BD%E7%BE%8E%E7%AB%B9%E8%A2%AB%E5%88%A4%E5%90%91%E6%9C%B1%E5%A7%90%E9%81%93%E6%AD%89%23) `173.1K 🔥`
1. [卧底卧成二把手的记者315又立功 (The reporter who went undercover and became the second-in-command in 315 made another meritorious service)](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%95%E5%8D%A7%E6%88%90%E4%BA%8C%E6%8A%8A%E6%89%8B%E7%9A%84%E8%AE%B0%E8%80%85315%E5%8F%88%E7%AB%8B%E5%8A%9F%23) `168.6K 🔥`
1. [刘宇宁回应黄子韬道歉](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%9B%9E%E5%BA%94%E9%BB%84%E5%AD%90%E9%9F%AC%E9%81%93%E6%AD%89%23) `167.4K 🔥`
1. [章子怡的买股运](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%E7%9A%84%E4%B9%B0%E8%82%A1%E8%BF%90%23) `160.5K 🔥`
1. [终于有人把带孩子的累说清楚了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%8A%8A%E5%B8%A6%E5%AD%A9%E5%AD%90%E7%9A%84%E7%B4%AF%E8%AF%B4%E6%B8%85%E6%A5%9A%E4%BA%86%23) `154.5K 🔥`
1. [瞿颖 翻红](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%20%E7%BF%BB%E7%BA%A2%23) `150.2K 🔥`
1. [霍尔木兹海峡首次没有船只通航](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E9%A6%96%E6%AC%A1%E6%B2%A1%E6%9C%89%E8%88%B9%E5%8F%AA%E9%80%9A%E8%88%AA%23) `140.7K 🔥`
1. [什么和离书分明是录取通知书](https://s.weibo.com/weibo?q=%23%E4%BB%80%E4%B9%88%E5%92%8C%E7%A6%BB%E4%B9%A6%E5%88%86%E6%98%8E%E6%98%AF%E5%BD%95%E5%8F%96%E9%80%9A%E7%9F%A5%E4%B9%A6%23) `107.4K 🔥`
1. [卧底老K收入暴涨315总导演1天1电话 (Undercover old K’s income skyrocketed 315. The chief director made one call a day)](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%95%E8%80%81K%E6%94%B6%E5%85%A5%E6%9A%B4%E6%B6%A8315%E6%80%BB%E5%AF%BC%E6%BC%941%E5%A4%A91%E7%94%B5%E8%AF%9D%23) `230.8K 🔥` `-28%`
1. [湘雅医院失联学生确认坠江身亡 (Missing student from Xiangya Hospital confirmed to have fallen into river and died)](https://s.weibo.com/weibo?q=%23%E6%B9%98%E9%9B%85%E5%8C%BB%E9%99%A2%E5%A4%B1%E8%81%94%E5%AD%A6%E7%94%9F%E7%A1%AE%E8%AE%A4%E5%9D%A0%E6%B1%9F%E8%BA%AB%E4%BA%A1%23) `198.5K 🔥` `-38%`
1. [宋智雅因三星Galaxy言论被骂](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E6%99%BA%E9%9B%85%E5%9B%A0%E4%B8%89%E6%98%9FGalaxy%E8%A8%80%E8%AE%BA%E8%A2%AB%E9%AA%82%23) `110.1K 🔥` `-38%`
1. [vivo宣布涨价](https://s.weibo.com/weibo?q=%23vivo%E5%AE%A3%E5%B8%83%E6%B6%A8%E4%BB%B7%23) `108.2K 🔥` `-40%`

Updated at 2026-03-16 16:08:03

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
