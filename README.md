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

1. [6G网要来了 (6G network is coming)](https://s.weibo.com/weibo?q=%236G%E7%BD%91%E8%A6%81%E6%9D%A5%E4%BA%86%23) `1.1M 🔥` `NEW`
1. [物业管理改服务住建部采纳了](https://s.weibo.com/weibo?q=%23%E7%89%A9%E4%B8%9A%E7%AE%A1%E7%90%86%E6%94%B9%E6%9C%8D%E5%8A%A1%E4%BD%8F%E5%BB%BA%E9%83%A8%E9%87%87%E7%BA%B3%E4%BA%86%23) `813.4K 🔥` `NEW`
1. [正在解决地外星球长期生存问题](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E5%9C%A8%E8%A7%A3%E5%86%B3%E5%9C%B0%E5%A4%96%E6%98%9F%E7%90%83%E9%95%BF%E6%9C%9F%E7%94%9F%E5%AD%98%E9%97%AE%E9%A2%98%23) `171.3K 🔥` `NEW`
1. [伊朗称驱逐美以大使可过霍尔木兹](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E9%A9%B1%E9%80%90%E7%BE%8E%E4%BB%A5%E5%A4%A7%E4%BD%BF%E5%8F%AF%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%23) `164.2K 🔥` `NEW`
1. [全红婵新身份曝光](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E6%96%B0%E8%BA%AB%E4%BB%BD%E6%9B%9D%E5%85%89%23) `164.0K 🔥` `NEW`
1. [司宫令](https://s.weibo.com/weibo?q=%23%E5%8F%B8%E5%AE%AB%E4%BB%A4%23) `162.5K 🔥` `NEW`
1. [历届SMG视后](https://s.weibo.com/weibo?q=%23%E5%8E%86%E5%B1%8ASMG%E8%A7%86%E5%90%8E%23) `152.1K 🔥` `NEW`
1. [起飞就是战斗起飞定传胜利消息](https://s.weibo.com/weibo?q=%23%E8%B5%B7%E9%A3%9E%E5%B0%B1%E6%98%AF%E6%88%98%E6%96%97%E8%B5%B7%E9%A3%9E%E5%AE%9A%E4%BC%A0%E8%83%9C%E5%88%A9%E6%B6%88%E6%81%AF%23) `151.2K 🔥` `NEW`
1. [建议餐馆标明预制菜让顾客自己选](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%A4%90%E9%A6%86%E6%A0%87%E6%98%8E%E9%A2%84%E5%88%B6%E8%8F%9C%E8%AE%A9%E9%A1%BE%E5%AE%A2%E8%87%AA%E5%B7%B1%E9%80%89%23) `149.8K 🔥` `NEW`
1. [美媒称这场战争打不起了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AA%92%E7%A7%B0%E8%BF%99%E5%9C%BA%E6%88%98%E4%BA%89%E6%89%93%E4%B8%8D%E8%B5%B7%E4%BA%86%23) `147.7K 🔥` `NEW`
1. [霸王茶姬口令答案 (Overlord Cha Ji password answer)](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%E7%AD%94%E6%A1%88%23) `145.0K 🔥` `NEW`
1. [亚历山大绝杀掘金](https://s.weibo.com/weibo?q=%23%E4%BA%9A%E5%8E%86%E5%B1%B1%E5%A4%A7%E7%BB%9D%E6%9D%80%E6%8E%98%E9%87%91%23) `119.1K 🔥` `NEW`
1. [胖东来八成员工月收入9000元](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E5%85%AB%E6%88%90%E5%91%98%E5%B7%A5%E6%9C%88%E6%94%B6%E5%85%A59000%E5%85%83%23) `119.1K 🔥` `NEW`
1. [伊朗放弃猛打猛冲](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%94%BE%E5%BC%83%E7%8C%9B%E6%89%93%E7%8C%9B%E5%86%B2%23) `119.0K 🔥` `NEW`
1. [刘亦菲LV大秀造型图](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2LV%E5%A4%A7%E7%A7%80%E9%80%A0%E5%9E%8B%E5%9B%BE%23) `118.9K 🔥` `NEW`
1. [性格有5个特点的人更容易长寿](https://s.weibo.com/weibo?q=%23%E6%80%A7%E6%A0%BC%E6%9C%895%E4%B8%AA%E7%89%B9%E7%82%B9%E7%9A%84%E4%BA%BA%E6%9B%B4%E5%AE%B9%E6%98%93%E9%95%BF%E5%AF%BF%23) `118.9K 🔥` `NEW`
1. [泽连斯基称已有11国向乌克兰求助](https://s.weibo.com/weibo?q=%23%E6%B3%BD%E8%BF%9E%E6%96%AF%E5%9F%BA%E7%A7%B0%E5%B7%B2%E6%9C%8911%E5%9B%BD%E5%90%91%E4%B9%8C%E5%85%8B%E5%85%B0%E6%B1%82%E5%8A%A9%23) `118.8K 🔥` `NEW`
1. [劳动者退休后养老待遇应是平等的](https://s.weibo.com/weibo?q=%23%E5%8A%B3%E5%8A%A8%E8%80%85%E9%80%80%E4%BC%91%E5%90%8E%E5%85%BB%E8%80%81%E5%BE%85%E9%81%87%E5%BA%94%E6%98%AF%E5%B9%B3%E7%AD%89%E7%9A%84%23) `115.5K 🔥` `NEW`
1. [王一博谷爱凌张钧甯合影](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%B0%B7%E7%88%B1%E5%87%8C%E5%BC%A0%E9%92%A7%E7%94%AF%E5%90%88%E5%BD%B1%23) `115.1K 🔥` `NEW`
1. [胖东来室外保洁月薪近万元](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E5%AE%A4%E5%A4%96%E4%BF%9D%E6%B4%81%E6%9C%88%E8%96%AA%E8%BF%91%E4%B8%87%E5%85%83%23) `105.5K 🔥` `NEW`
1. [伊朗提出过霍尔木兹海峡条件 (Iran raises conditions over Strait of Hormuz)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8F%90%E5%87%BA%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E6%9D%A1%E4%BB%B6%23) `104.2K 🔥` `NEW`
1. [司机大山里突然停机拨打119求冲话费](https://s.weibo.com/weibo?q=%23%E5%8F%B8%E6%9C%BA%E5%A4%A7%E5%B1%B1%E9%87%8C%E7%AA%81%E7%84%B6%E5%81%9C%E6%9C%BA%E6%8B%A8%E6%89%93119%E6%B1%82%E5%86%B2%E8%AF%9D%E8%B4%B9%23) `95.7K 🔥` `NEW`
1. [明日方舟](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%97%A5%E6%96%B9%E8%88%9F%23) `90.0K 🔥` `NEW`
1. [妈妈回应女儿用烧火棍在灶台作画](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%84%BF%E7%94%A8%E7%83%A7%E7%81%AB%E6%A3%8D%E5%9C%A8%E7%81%B6%E5%8F%B0%E4%BD%9C%E7%94%BB%23) `83.8K 🔥` `NEW`
1. [OpenClaw火了龙虾养了也要防](https://s.weibo.com/weibo?q=%23OpenClaw%E7%81%AB%E4%BA%86%E9%BE%99%E8%99%BE%E5%85%BB%E4%BA%86%E4%B9%9F%E8%A6%81%E9%98%B2%23) `78.5K 🔥` `NEW`
1. [建议促消费先要加工资](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%BF%83%E6%B6%88%E8%B4%B9%E5%85%88%E8%A6%81%E5%8A%A0%E5%B7%A5%E8%B5%84%23) `76.9K 🔥` `NEW`
1. [周冠宇紫薯精](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%A0%E5%AE%87%E7%B4%AB%E8%96%AF%E7%B2%BE%23) `76.2K 🔥` `NEW`
1. [宁德时代日赚近2亿](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BE%B7%E6%97%B6%E4%BB%A3%E6%97%A5%E8%B5%9A%E8%BF%912%E4%BA%BF%23) `76.1K 🔥` `NEW`
1. [掘金vs雷霆](https://s.weibo.com/weibo?q=%23%E6%8E%98%E9%87%91vs%E9%9B%B7%E9%9C%86%23) `75.8K 🔥` `NEW`
1. [刘亦菲ins更新巴黎照](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2ins%E6%9B%B4%E6%96%B0%E5%B7%B4%E9%BB%8E%E7%85%A7%23) `75.8K 🔥` `NEW`
1. [谢征强吻长玉后的台词 (Xie Zheng’s lines after he kissed Chang Yu forcefully)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E5%BC%BA%E5%90%BB%E9%95%BF%E7%8E%89%E5%90%8E%E7%9A%84%E5%8F%B0%E8%AF%8D%23) `123.8K 🔥` `+98%`
1. [2026这些区域将迎发展 (These areas will welcome development in 2026)](https://s.weibo.com/weibo?q=%232026%E8%BF%99%E4%BA%9B%E5%8C%BA%E5%9F%9F%E5%B0%86%E8%BF%8E%E5%8F%91%E5%B1%95%23) `629.6K 🔥`
1. [第一批养虾人已经失眠了](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%89%B9%E5%85%BB%E8%99%BE%E4%BA%BA%E5%B7%B2%E7%BB%8F%E5%A4%B1%E7%9C%A0%E4%BA%86%23) `105.4K 🔥`
1. [鸡鸣寺消息树今年失约](https://s.weibo.com/weibo?q=%23%E9%B8%A1%E9%B8%A3%E5%AF%BA%E6%B6%88%E6%81%AF%E6%A0%91%E4%BB%8A%E5%B9%B4%E5%A4%B1%E7%BA%A6%23) `78.2K 🔥`
1. [伊朗发起第32波打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC32%E6%B3%A2%E6%89%93%E5%87%BB%23) `76.1K 🔥`
1. [逐玉热度 (The popularity of chasing jade)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%83%AD%E5%BA%A6%23) `75.7K 🔥`
1. [哥伦比亚女子滑滑梯猛烈撞墙后身亡 (Colombian woman dies after hitting wall on slide)](https://s.weibo.com/weibo?q=%23%E5%93%A5%E4%BC%A6%E6%AF%94%E4%BA%9A%E5%A5%B3%E5%AD%90%E6%BB%91%E6%BB%91%E6%A2%AF%E7%8C%9B%E7%83%88%E6%92%9E%E5%A2%99%E5%90%8E%E8%BA%AB%E4%BA%A1%23) `75.7K 🔥`
1. [未来5年中国要建设的重大工程](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A55%E5%B9%B4%E4%B8%AD%E5%9B%BD%E8%A6%81%E5%BB%BA%E8%AE%BE%E7%9A%84%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%23) `165.4K 🔥` `-67%`
1. [孙俪SMG视后](https://s.weibo.com/weibo?q=%23%E5%AD%99%E4%BF%AASMG%E8%A7%86%E5%90%8E%23) `144.2K 🔥` `-24%`
1. [胖东来12名店长共分2.4亿资产利润 (Fat Donglai’s 12 store managers shared a total of 240 million in asset profits)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A512%E5%90%8D%E5%BA%97%E9%95%BF%E5%85%B1%E5%88%862.4%E4%BA%BF%E8%B5%84%E4%BA%A7%E5%88%A9%E6%B6%A6%23) `125.7K 🔥` `-36%`
1. [91岁女儿受委屈向113岁妈妈哭诉 (91-year-old daughter cries to her 113-year-old mother after being wronged)](https://s.weibo.com/weibo?q=%2391%E5%B2%81%E5%A5%B3%E5%84%BF%E5%8F%97%E5%A7%94%E5%B1%88%E5%90%91113%E5%B2%81%E5%A6%88%E5%A6%88%E5%93%AD%E8%AF%89%23) `119.1K 🔥` `-34%`
1. [医生提醒不要模仿Ella真空腹 (Doctor reminds not to imitate Ella’s vacuum abdomen)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E6%8F%90%E9%86%92%E4%B8%8D%E8%A6%81%E6%A8%A1%E4%BB%BFElla%E7%9C%9F%E7%A9%BA%E8%85%B9%23) `118.9K 🔥` `-32%`
1. [历届SMG视帝 (Previous SMG TV Emperors)](https://s.weibo.com/weibo?q=%23%E5%8E%86%E5%B1%8ASMG%E8%A7%86%E5%B8%9D%23) `118.9K 🔥` `-77%`
1. [10日两会日程预告 (Preview of the schedule of the two sessions on the 10th)](https://s.weibo.com/weibo?q=%2310%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%E9%A2%84%E5%91%8A%23) `106.4K 🔥` `-86%`
1. [1亿美元委内瑞拉黄金运抵美国](https://s.weibo.com/weibo?q=%231%E4%BA%BF%E7%BE%8E%E5%85%83%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E9%BB%84%E9%87%91%E8%BF%90%E6%8A%B5%E7%BE%8E%E5%9B%BD%23) `100.7K 🔥` `-62%`
1. [卢昱晓走红毯忘记把暖宝宝拿下来了 (Lu Yuxiao forgot to take off the warm baby while walking on the red carpet)](https://s.weibo.com/weibo?q=%23%E5%8D%A2%E6%98%B1%E6%99%93%E8%B5%B0%E7%BA%A2%E6%AF%AF%E5%BF%98%E8%AE%B0%E6%8A%8A%E6%9A%96%E5%AE%9D%E5%AE%9D%E6%8B%BF%E4%B8%8B%E6%9D%A5%E4%BA%86%23) `93.6K 🔥` `-37%`
1. [6个月宝宝吃辅食被香得一激灵](https://s.weibo.com/weibo?q=%236%E4%B8%AA%E6%9C%88%E5%AE%9D%E5%AE%9D%E5%90%83%E8%BE%85%E9%A3%9F%E8%A2%AB%E9%A6%99%E5%BE%97%E4%B8%80%E6%BF%80%E7%81%B5%23) `76.0K 🔥` `-30%`
1. [普京特朗普再通话](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E7%89%B9%E6%9C%97%E6%99%AE%E5%86%8D%E9%80%9A%E8%AF%9D%23) `76.0K 🔥` `-80%`
1. [13岁中国小孩哥夺得世界街舞冠军 (13-year-old Chinese kid wins world hip-hop dance championship)](https://s.weibo.com/weibo?q=%2313%E5%B2%81%E4%B8%AD%E5%9B%BD%E5%B0%8F%E5%AD%A9%E5%93%A5%E5%A4%BA%E5%BE%97%E4%B8%96%E7%95%8C%E8%A1%97%E8%88%9E%E5%86%A0%E5%86%9B%23) `75.9K 🔥` `-93%`

Updated at 2026-03-10 10:46:20

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
