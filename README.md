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

1. [伊朗称向美航母发射4枚巡航导弹 (Iran says it fired 4 cruise missiles at US aircraft carrier)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%90%91%E7%BE%8E%E8%88%AA%E6%AF%8D%E5%8F%91%E5%B0%844%E6%9E%9A%E5%B7%A1%E8%88%AA%E5%AF%BC%E5%BC%B9%23) `1.2M 🔥` `NEW`
1. [王玉雯周也在陈星旭胸前喂小羊](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%8E%89%E9%9B%AF%E5%91%A8%E4%B9%9F%E5%9C%A8%E9%99%88%E6%98%9F%E6%97%AD%E8%83%B8%E5%89%8D%E5%96%82%E5%B0%8F%E7%BE%8A%23) `375.8K 🔥` `NEW`
1. [品牌方回应迪丽热巴缺席](https://s.weibo.com/weibo?q=%23%E5%93%81%E7%89%8C%E6%96%B9%E5%9B%9E%E5%BA%94%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%BC%BA%E5%B8%AD%23) `374.3K 🔥` `NEW`
1. [舅舅回应被指觊觎外甥女财产](https://s.weibo.com/weibo?q=%23%E8%88%85%E8%88%85%E5%9B%9E%E5%BA%94%E8%A2%AB%E6%8C%87%E8%A7%8A%E8%A7%8E%E5%A4%96%E7%94%A5%E5%A5%B3%E8%B4%A2%E4%BA%A7%23) `370.4K 🔥` `NEW`
1. [易梦玲工作室回应被质疑压花](https://s.weibo.com/weibo?q=%23%E6%98%93%E6%A2%A6%E7%8E%B2%E5%B7%A5%E4%BD%9C%E5%AE%A4%E5%9B%9E%E5%BA%94%E8%A2%AB%E8%B4%A8%E7%96%91%E5%8E%8B%E8%8A%B1%23) `369.9K 🔥` `NEW`
1. [王一博巴黎时装周行程](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E8%A1%8C%E7%A8%8B%23) `369.3K 🔥` `NEW`
1. [易梦玲回应争议](https://s.weibo.com/weibo?q=%23%E6%98%93%E6%A2%A6%E7%8E%B2%E5%9B%9E%E5%BA%94%E4%BA%89%E8%AE%AE%23) `367.8K 🔥` `NEW`
1. [比亚迪](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%23) `366.4K 🔥` `NEW`
1. [以为是正缘来了没想到是血缘](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%98%AF%E6%AD%A3%E7%BC%98%E6%9D%A5%E4%BA%86%E6%B2%A1%E6%83%B3%E5%88%B0%E6%98%AF%E8%A1%80%E7%BC%98%23) `366.1K 🔥` `NEW`
1. [伊拉克居民捡到完整美国无人机](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%8B%89%E5%85%8B%E5%B1%85%E6%B0%91%E6%8D%A1%E5%88%B0%E5%AE%8C%E6%95%B4%E7%BE%8E%E5%9B%BD%E6%97%A0%E4%BA%BA%E6%9C%BA%23) `365.6K 🔥` `NEW`
1. [女足亚洲杯 (Women's Asian Cup)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E8%B6%B3%E4%BA%9A%E6%B4%B2%E6%9D%AF%23) `364.7K 🔥` `NEW`
1. [建议家暴情形不适用离婚冷静期](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%AE%B6%E6%9A%B4%E6%83%85%E5%BD%A2%E4%B8%8D%E9%80%82%E7%94%A8%E7%A6%BB%E5%A9%9A%E5%86%B7%E9%9D%99%E6%9C%9F%23) `363.7K 🔥` `NEW`
1. [十个勤天应到十人实到十人](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%B8%AA%E5%8B%A4%E5%A4%A9%E5%BA%94%E5%88%B0%E5%8D%81%E4%BA%BA%E5%AE%9E%E5%88%B0%E5%8D%81%E4%BA%BA%23) `363.6K 🔥` `NEW`
1. [代表建议延长A股交易时间](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%BB%BA%E8%AE%AE%E5%BB%B6%E9%95%BFA%E8%82%A1%E4%BA%A4%E6%98%93%E6%97%B6%E9%97%B4%23) `362.7K 🔥` `NEW`
1. [iPhone17e官网对比机型为iPhone11](https://s.weibo.com/weibo?q=%23iPhone17e%E5%AE%98%E7%BD%91%E5%AF%B9%E6%AF%94%E6%9C%BA%E5%9E%8B%E4%B8%BAiPhone11%23) `361.9K 🔥` `NEW`
1. [对方紧急撤回了6只企鹅](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E6%96%B9%E7%B4%A7%E6%80%A5%E6%92%A4%E5%9B%9E%E4%BA%866%E5%8F%AA%E4%BC%81%E9%B9%85%23) `360.9K 🔥` `NEW`
1. [张凌赫别试探了你的设计很有市场](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%88%AB%E8%AF%95%E6%8E%A2%E4%BA%86%E4%BD%A0%E7%9A%84%E8%AE%BE%E8%AE%A1%E5%BE%88%E6%9C%89%E5%B8%82%E5%9C%BA%23) `360.4K 🔥` `NEW`
1. [黄景瑜 咖啡汤圆](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%20%E5%92%96%E5%95%A1%E6%B1%A4%E5%9C%86%23) `359.7K 🔥` `NEW`
1. [把回南天拍得好高级](https://s.weibo.com/weibo?q=%23%E6%8A%8A%E5%9B%9E%E5%8D%97%E5%A4%A9%E6%8B%8D%E5%BE%97%E5%A5%BD%E9%AB%98%E7%BA%A7%23) `359.5K 🔥` `NEW`
1. [长期侧睡的猫猫](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E4%BE%A7%E7%9D%A1%E7%9A%84%E7%8C%AB%E7%8C%AB%23) `358.5K 🔥` `NEW`
1. [全国政协十四届四次会议新闻发布会 (Press Conference of the Fourth Session of the 14th CPPCC National Committee)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E6%94%BF%E5%8D%8F%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E6%96%B0%E9%97%BB%E5%8F%91%E5%B8%83%E4%BC%9A%23) `639.5K 🔥` `+42%`
1. [黄金白银断崖式下跌 (Gold and silver plummet)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E6%96%AD%E5%B4%96%E5%BC%8F%E4%B8%8B%E8%B7%8C%23) `546.9K 🔥` `+112%`
1. [王安宇CELINE品牌大使](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87CELINE%E5%93%81%E7%89%8C%E5%A4%A7%E4%BD%BF%23) `375.8K 🔥` `+38%`
1. [老人抱孙子玩腰间4厘米钢针扎进肚](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%BA%BA%E6%8A%B1%E5%AD%99%E5%AD%90%E7%8E%A9%E8%85%B0%E9%97%B44%E5%8E%98%E7%B1%B3%E9%92%A2%E9%92%88%E6%89%8E%E8%BF%9B%E8%82%9A%23) `373.0K 🔥` `+44%`
1. [以前谈恋爱QQ是要关联的 (In the past, to fall in love on QQ, you had to be connected.)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%89%8D%E8%B0%88%E6%81%8B%E7%88%B1QQ%E6%98%AF%E8%A6%81%E5%85%B3%E8%81%94%E7%9A%84%23) `372.4K 🔥` `+45%`
1. [烟台一只狗被困井下约3年获救](https://s.weibo.com/weibo?q=%23%E7%83%9F%E5%8F%B0%E4%B8%80%E5%8F%AA%E7%8B%97%E8%A2%AB%E5%9B%B0%E4%BA%95%E4%B8%8B%E7%BA%A63%E5%B9%B4%E8%8E%B7%E6%95%91%23) `371.3K 🔥` `+45%`
1. [胡彦斌只一味吃汤圆](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%BD%A6%E6%96%8C%E5%8F%AA%E4%B8%80%E5%91%B3%E5%90%83%E6%B1%A4%E5%9C%86%23) `370.8K 🔥` `+34%`
1. [AI生成 男女身高](https://s.weibo.com/weibo?q=%23AI%E7%94%9F%E6%88%90%20%E7%94%B7%E5%A5%B3%E8%BA%AB%E9%AB%98%23) `369.0K 🔥` `+43%`
1. [台湾热议台胞证能救命](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E7%83%AD%E8%AE%AE%E5%8F%B0%E8%83%9E%E8%AF%81%E8%83%BD%E6%95%91%E5%91%BD%23) `368.4K 🔥` `+43%`
1. [元宵节 (Lantern Festival)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E8%8A%82%23) `367.3K 🔥` `+43%`
1. [元宵晚会节目单](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E6%99%9A%E4%BC%9A%E8%8A%82%E7%9B%AE%E5%8D%95%23) `367.1K 🔥` `+42%`
1. [比亚迪把天门山天梯搬进了厂房](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%E6%8A%8A%E5%A4%A9%E9%97%A8%E5%B1%B1%E5%A4%A9%E6%A2%AF%E6%90%AC%E8%BF%9B%E4%BA%86%E5%8E%82%E6%88%BF%23) `365.9K 🔥` `+43%`
1. [孙俪邓超2026全家福](https://s.weibo.com/weibo?q=%23%E5%AD%99%E4%BF%AA%E9%82%93%E8%B6%852026%E5%85%A8%E5%AE%B6%E7%A6%8F%23) `364.2K 🔥` `+42%`
1. [杨幂说自己有老人味 (Yang Mi says she looks old)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%AF%B4%E8%87%AA%E5%B7%B1%E6%9C%89%E8%80%81%E4%BA%BA%E5%91%B3%23) `363.2K 🔥` `+41%`
1. [无情报证明伊朗计划先袭击美军](https://s.weibo.com/weibo?q=%23%E6%97%A0%E6%83%85%E6%8A%A5%E8%AF%81%E6%98%8E%E4%BC%8A%E6%9C%97%E8%AE%A1%E5%88%92%E5%85%88%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%23) `362.1K 🔥` `+42%`
1. [汤圆](https://s.weibo.com/weibo?q=%23%E6%B1%A4%E5%9C%86%23) `361.5K 🔥` `+41%`
1. [父母不应该与孩子分享的事情belike](https://s.weibo.com/weibo?q=%23%E7%88%B6%E6%AF%8D%E4%B8%8D%E5%BA%94%E8%AF%A5%E4%B8%8E%E5%AD%A9%E5%AD%90%E5%88%86%E4%BA%AB%E7%9A%84%E4%BA%8B%E6%83%85belike%23) `360.9K 🔥` `+41%`
1. [郑恺回村也不能撕baby (Even if Zheng Kai returns to the village, he can’t tear the baby apart)](https://s.weibo.com/weibo?q=%23%E9%83%91%E6%81%BA%E5%9B%9E%E6%9D%91%E4%B9%9F%E4%B8%8D%E8%83%BD%E6%92%95baby%23) `358.9K 🔥` `+40%`
1. [油价调整](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E8%B0%83%E6%95%B4%23) `834.7K 🔥`
1. [地平线HSD方盒子智驾新标杆 (Horizon HSD square box new benchmark for smart driving)](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E5%B9%B3%E7%BA%BFHSD%E6%96%B9%E7%9B%92%E5%AD%90%E6%99%BA%E9%A9%BE%E6%96%B0%E6%A0%87%E6%9D%86%23) `637.7K 🔥`
1. [刘文祥麻辣烫暂停新合作](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E6%9A%82%E5%81%9C%E6%96%B0%E5%90%88%E4%BD%9C%23) `376.0K 🔥`
1. [iPhone17只用一个月橙色变粉色](https://s.weibo.com/weibo?q=%23iPhone17%E5%8F%AA%E7%94%A8%E4%B8%80%E4%B8%AA%E6%9C%88%E6%A9%99%E8%89%B2%E5%8F%98%E7%B2%89%E8%89%B2%23) `375.2K 🔥`
1. [建议禁止16岁以下使用社媒 (It is recommended that users under the age of 16 are prohibited from using social media)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%A6%81%E6%AD%A216%E5%B2%81%E4%BB%A5%E4%B8%8B%E4%BD%BF%E7%94%A8%E7%A4%BE%E5%AA%92%23) `374.7K 🔥`
1. [舅妈冒用去世母亲身份与舅舅结婚](https://s.weibo.com/weibo?q=%23%E8%88%85%E5%A6%88%E5%86%92%E7%94%A8%E5%8E%BB%E4%B8%96%E6%AF%8D%E4%BA%B2%E8%BA%AB%E4%BB%BD%E4%B8%8E%E8%88%85%E8%88%85%E7%BB%93%E5%A9%9A%23) `373.8K 🔥`
1. [迪丽热巴将缺席时装周](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%B0%86%E7%BC%BA%E5%B8%AD%E6%97%B6%E8%A3%85%E5%91%A8%23) `372.1K 🔥`
1. [曝张元英签售一直玩手机 (It is revealed that Zhang Yuanying has been playing with her mobile phone while signing a book)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%BC%A0%E5%85%83%E8%8B%B1%E7%AD%BE%E5%94%AE%E4%B8%80%E7%9B%B4%E7%8E%A9%E6%89%8B%E6%9C%BA%23) `371.8K 🔥`
1. [股市](https://s.weibo.com/weibo?q=%23%E8%82%A1%E5%B8%82%23) `370.1K 🔥`
1. [公务员平替岗挤满没上岸的年轻人 (Civil servants are filling their posts with young people who have not yet landed.)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E5%8A%A1%E5%91%98%E5%B9%B3%E6%9B%BF%E5%B2%97%E6%8C%A4%E6%BB%A1%E6%B2%A1%E4%B8%8A%E5%B2%B8%E7%9A%84%E5%B9%B4%E8%BD%BB%E4%BA%BA%23) `368.7K 🔥`
1. [世界油阀关闭](https://s.weibo.com/weibo?q=%23%E4%B8%96%E7%95%8C%E6%B2%B9%E9%98%80%E5%85%B3%E9%97%AD%23) `539.2K 🔥` `-65%`
1. [越来越多国家被卷入中东冲突 (More and more countries are involved in conflicts in the Middle East)](https://s.weibo.com/weibo?q=%23%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%A4%9A%E5%9B%BD%E5%AE%B6%E8%A2%AB%E5%8D%B7%E5%85%A5%E4%B8%AD%E4%B8%9C%E5%86%B2%E7%AA%81%23) `375.1K 🔥` `-58%`
1. [伊朗称击中了美空军基地大楼 (Iran says it hit US Air Force base building)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%87%BB%E4%B8%AD%E4%BA%86%E7%BE%8E%E7%A9%BA%E5%86%9B%E5%9F%BA%E5%9C%B0%E5%A4%A7%E6%A5%BC%23) `373.4K 🔥` `-24%`

Updated at 2026-03-03 16:57:22

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
