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

1. [谢景行 (Xie Jingxing)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E6%99%AF%E8%A1%8C%23) `252.4K 🔥` `NEW`
1. [穆祉丞 没人打扰的感觉太爽了](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%20%E6%B2%A1%E4%BA%BA%E6%89%93%E6%89%B0%E7%9A%84%E6%84%9F%E8%A7%89%E5%A4%AA%E7%88%BD%E4%BA%86%23) `216.9K 🔥` `NEW`
1. [吴京聊王嘉尔镖人主题曲创作](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%E8%81%8A%E7%8E%8B%E5%98%89%E5%B0%94%E9%95%96%E4%BA%BA%E4%B8%BB%E9%A2%98%E6%9B%B2%E5%88%9B%E4%BD%9C%23) `197.9K 🔥` `NEW`
1. [妈妈让上交2万压岁钱孩子不干了](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E8%AE%A9%E4%B8%8A%E4%BA%A42%E4%B8%87%E5%8E%8B%E5%B2%81%E9%92%B1%E5%AD%A9%E5%AD%90%E4%B8%8D%E5%B9%B2%E4%BA%86%23) `184.9K 🔥` `NEW`
1. [中国智能机器人持续惊艳全球](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%99%BA%E8%83%BD%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%8C%81%E7%BB%AD%E6%83%8A%E8%89%B3%E5%85%A8%E7%90%83%23) `153.3K 🔥` `NEW`
1. [29岁男子日夜颠倒狂吃碳水ICU过年](https://s.weibo.com/weibo?q=%2329%E5%B2%81%E7%94%B7%E5%AD%90%E6%97%A5%E5%A4%9C%E9%A2%A0%E5%80%92%E7%8B%82%E5%90%83%E7%A2%B3%E6%B0%B4ICU%E8%BF%87%E5%B9%B4%23) `108.2K 🔥` `NEW`
1. [老家短短2天热闹却是一整年盼头](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%AE%B6%E7%9F%AD%E7%9F%AD2%E5%A4%A9%E7%83%AD%E9%97%B9%E5%8D%B4%E6%98%AF%E4%B8%80%E6%95%B4%E5%B9%B4%E7%9B%BC%E5%A4%B4%23) `105.6K 🔥` `NEW`
1. [沈腾主演电影票房已超384亿](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E4%B8%BB%E6%BC%94%E7%94%B5%E5%BD%B1%E7%A5%A8%E6%88%BF%E5%B7%B2%E8%B6%85384%E4%BA%BF%23) `105.5K 🔥` `NEW`
1. [形象的演示了什么叫命里有财](https://s.weibo.com/weibo?q=%23%E5%BD%A2%E8%B1%A1%E7%9A%84%E6%BC%94%E7%A4%BA%E4%BA%86%E4%BB%80%E4%B9%88%E5%8F%AB%E5%91%BD%E9%87%8C%E6%9C%89%E8%B4%A2%23) `103.5K 🔥` `NEW`
1. [明确提出谈恋爱吧才算谈恋爱](https://s.weibo.com/weibo?q=%23%E6%98%8E%E7%A1%AE%E6%8F%90%E5%87%BA%E8%B0%88%E6%81%8B%E7%88%B1%E5%90%A7%E6%89%8D%E7%AE%97%E8%B0%88%E6%81%8B%E7%88%B1%23) `102.5K 🔥` `NEW`
1. [苏翊鸣的第二枚奥运金牌 (Su Yiming’s second Olympic gold medal)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%9A%84%E7%AC%AC%E4%BA%8C%E6%9E%9A%E5%A5%A5%E8%BF%90%E9%87%91%E7%89%8C%23) `73.7K 🔥` `NEW`
1. [李云霄在自己单位楼上路演](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BA%91%E9%9C%84%E5%9C%A8%E8%87%AA%E5%B7%B1%E5%8D%95%E4%BD%8D%E6%A5%BC%E4%B8%8A%E8%B7%AF%E6%BC%94%23) `67.2K 🔥` `NEW`
1. [苏翊鸣采访时徐梦桃打来电话](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E9%87%87%E8%AE%BF%E6%97%B6%E5%BE%90%E6%A2%A6%E6%A1%83%E6%89%93%E6%9D%A5%E7%94%B5%E8%AF%9D%23) `64.8K 🔥` `NEW`
1. [Deepseek神回复](https://s.weibo.com/weibo?q=%23Deepseek%E7%A5%9E%E5%9B%9E%E5%A4%8D%23) `1.1M 🔥` `+624%`
1. [飞驰人生3后劲好大 (Flying Life 3 has great stamina)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E5%90%8E%E5%8A%B2%E5%A5%BD%E5%A4%A7%23) `261.0K 🔥` `+43%`
1. [王菲为什么选中你我经历的一刻](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E4%B8%BA%E4%BB%80%E4%B9%88%E9%80%89%E4%B8%AD%E4%BD%A0%E6%88%91%E7%BB%8F%E5%8E%86%E7%9A%84%E4%B8%80%E5%88%BB%23) `241.0K 🔥` `+108%`
1. [属相不是从立春开始算](https://s.weibo.com/weibo?q=%23%E5%B1%9E%E7%9B%B8%E4%B8%8D%E6%98%AF%E4%BB%8E%E7%AB%8B%E6%98%A5%E5%BC%80%E5%A7%8B%E7%AE%97%23) `229.0K 🔥` `+56%`
1. [刘德华解冻失败 (Andy Lau failed to unfreeze)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%BE%B7%E5%8D%8E%E8%A7%A3%E5%86%BB%E5%A4%B1%E8%B4%A5%23) `227.3K 🔥` `+32%`
1. [高层看烟花有多吓人 (How scary is it to watch fireworks from high-rise buildings?)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B1%82%E7%9C%8B%E7%83%9F%E8%8A%B1%E6%9C%89%E5%A4%9A%E5%90%93%E4%BA%BA%23) `212.9K 🔥` `+24%`
1. [酷滕 雷淞然](https://s.weibo.com/weibo?q=%23%E9%85%B7%E6%BB%95%20%E9%9B%B7%E6%B7%9E%E7%84%B6%23) `207.5K 🔥` `+21%`
1. [他们在天山脚下脚踏冰河巡边 (They patrolled the glacier at the foot of the Tianshan Mountains)](https://s.weibo.com/weibo?q=%23%E4%BB%96%E4%BB%AC%E5%9C%A8%E5%A4%A9%E5%B1%B1%E8%84%9A%E4%B8%8B%E8%84%9A%E8%B8%8F%E5%86%B0%E6%B2%B3%E5%B7%A1%E8%BE%B9%23) `613.0K 🔥`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `190.7K 🔥`
1. [100多元订房酒店嫌价低不让入住](https://s.weibo.com/weibo?q=%23100%E5%A4%9A%E5%85%83%E8%AE%A2%E6%88%BF%E9%85%92%E5%BA%97%E5%AB%8C%E4%BB%B7%E4%BD%8E%E4%B8%8D%E8%AE%A9%E5%85%A5%E4%BD%8F%23) `187.8K 🔥`
1. [网剧双轨](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%89%A7%E5%8F%8C%E8%BD%A8%23) `142.4K 🔥`
1. [山东晚高峰视频在推特火了 (Shandong evening rush hour video goes viral on Twitter)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E4%B8%9C%E6%99%9A%E9%AB%98%E5%B3%B0%E8%A7%86%E9%A2%91%E5%9C%A8%E6%8E%A8%E7%89%B9%E7%81%AB%E4%BA%86%23) `118.3K 🔥`
1. [王一博表演现场版震感好爽](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%A1%A8%E6%BC%94%E7%8E%B0%E5%9C%BA%E7%89%88%E9%9C%87%E6%84%9F%E5%A5%BD%E7%88%BD%23) `99.0K 🔥`
1. [北京大学陈江教授讲AI (Professor Chen Jiang from Peking University lectures on AI)](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%A4%A7%E5%AD%A6%E9%99%88%E6%B1%9F%E6%95%99%E6%8E%88%E8%AE%B2AI%23) `97.1K 🔥`
1. [科学解释不了只有爱能解释](https://s.weibo.com/weibo?q=%23%E7%A7%91%E5%AD%A6%E8%A7%A3%E9%87%8A%E4%B8%8D%E4%BA%86%E5%8F%AA%E6%9C%89%E7%88%B1%E8%83%BD%E8%A7%A3%E9%87%8A%23) `93.0K 🔥`
1. [杨幂朱一龙吻戏](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9C%B1%E4%B8%80%E9%BE%99%E5%90%BB%E6%88%8F%23) `71.3K 🔥`
1. [引导型恋人笑得好崩溃](https://s.weibo.com/weibo?q=%23%E5%BC%95%E5%AF%BC%E5%9E%8B%E6%81%8B%E4%BA%BA%E7%AC%91%E5%BE%97%E5%A5%BD%E5%B4%A9%E6%BA%83%23) `71.1K 🔥`
1. [将门独后官宣节奏 (The official announcement of the rhythm of being the only queen in the general family)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%AE%98%E5%AE%A3%E8%8A%82%E5%A5%8F%23) `775.5K 🔥` `-29%`
1. [王鹤棣孟子义 将门独后](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AD%9F%E5%AD%90%E4%B9%89%20%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `357.6K 🔥` `-21%`
1. [美国若武力介入台湾代价巨大](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E8%8B%A5%E6%AD%A6%E5%8A%9B%E4%BB%8B%E5%85%A5%E5%8F%B0%E6%B9%BE%E4%BB%A3%E4%BB%B7%E5%B7%A8%E5%A4%A7%23) `274.3K 🔥` `-31%`
1. [湖南新化6名消防员因公牺牲](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E6%96%B0%E5%8C%966%E5%90%8D%E6%B6%88%E9%98%B2%E5%91%98%E5%9B%A0%E5%85%AC%E7%89%BA%E7%89%B2%23) `263.4K 🔥` `-34%`
1. [人的心气是能重新养回来的](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%9A%84%E5%BF%83%E6%B0%94%E6%98%AF%E8%83%BD%E9%87%8D%E6%96%B0%E5%85%BB%E5%9B%9E%E6%9D%A5%E7%9A%84%23) `230.7K 🔥` `-41%`
1. [苏翊鸣因北京冬奥会放弃当演员](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%9B%A0%E5%8C%97%E4%BA%AC%E5%86%AC%E5%A5%A5%E4%BC%9A%E6%94%BE%E5%BC%83%E5%BD%93%E6%BC%94%E5%91%98%23) `159.5K 🔥` `-80%`
1. [镖人票房逆跌 (The box office of Daredevil fell sharply)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E9%80%86%E8%B7%8C%23) `148.2K 🔥` `-57%`
1. [2名初中生扶摔倒女子遭索赔22万 (Two junior high school students helped a woman who fell down and were compensated for NT$220,000)](https://s.weibo.com/weibo?q=%232%E5%90%8D%E5%88%9D%E4%B8%AD%E7%94%9F%E6%89%B6%E6%91%94%E5%80%92%E5%A5%B3%E5%AD%90%E9%81%AD%E7%B4%A2%E8%B5%9422%E4%B8%87%23) `131.0K 🔥` `-31%`
1. [杨幂开车都能出神图 (Yang Mi can be enchanted when driving)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E5%BC%80%E8%BD%A6%E9%83%BD%E8%83%BD%E5%87%BA%E7%A5%9E%E5%9B%BE%23) `127.9K 🔥` `-62%`
1. [白鹿韩国](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E9%9F%A9%E5%9B%BD%23) `122.2K 🔥` `-29%`
1. [爸爸除夕独自吃饺子女儿看监控哭了 (Dad eats dumplings alone on New Year’s Eve and daughter cries while watching CCTV)](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E9%99%A4%E5%A4%95%E7%8B%AC%E8%87%AA%E5%90%83%E9%A5%BA%E5%AD%90%E5%A5%B3%E5%84%BF%E7%9C%8B%E7%9B%91%E6%8E%A7%E5%93%AD%E4%BA%86%23) `104.4K 🔥` `-26%`
1. [白鹿代露娃二搭疯批对疯批 (Shirokadai Luwa's second match is crazy about crazy criticism.)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E4%BB%A3%E9%9C%B2%E5%A8%83%E4%BA%8C%E6%90%AD%E7%96%AF%E6%89%B9%E5%AF%B9%E7%96%AF%E6%89%B9%23) `102.0K 🔥` `-29%`
1. [英国前王子安德鲁被捕 (Former British Prince Andrew arrested)](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E5%89%8D%E7%8E%8B%E5%AD%90%E5%AE%89%E5%BE%B7%E9%B2%81%E8%A2%AB%E6%8D%95%23) `101.9K 🔥` `-41%`
1. [自取其辱九件套](https://s.weibo.com/weibo?q=%23%E8%87%AA%E5%8F%96%E5%85%B6%E8%BE%B1%E4%B9%9D%E4%BB%B6%E5%A5%97%23) `95.6K 🔥` `-44%`
1. [王橹杰抽抽乐 (Wang Lujie has fun)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%8A%BD%E6%8A%BD%E4%B9%90%23) `90.0K 🔥` `-44%`
1. [生命树](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%23) `85.2K 🔥` `-21%`
1. [觉得自己闯祸的可以看看美国四人雪车](https://s.weibo.com/weibo?q=%23%E8%A7%89%E5%BE%97%E8%87%AA%E5%B7%B1%E9%97%AF%E7%A5%B8%E7%9A%84%E5%8F%AF%E4%BB%A5%E7%9C%8B%E7%9C%8B%E7%BE%8E%E5%9B%BD%E5%9B%9B%E4%BA%BA%E9%9B%AA%E8%BD%A6%23) `77.2K 🔥` `-45%`
1. [沈腾回应马丽单飞](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E5%9B%9E%E5%BA%94%E9%A9%AC%E4%B8%BD%E5%8D%95%E9%A3%9E%23) `74.6K 🔥` `-33%`
1. [我们的少年时代2 (Our Boyhood 2)](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%23) `67.2K 🔥` `-26%`
1. [烟花爆竹该禁吗](https://s.weibo.com/weibo?q=%23%E7%83%9F%E8%8A%B1%E7%88%86%E7%AB%B9%E8%AF%A5%E7%A6%81%E5%90%97%23) `65.6K 🔥` `-62%`
1. [美一高校兄弟会诡异入会仪式曝光](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%B8%80%E9%AB%98%E6%A0%A1%E5%85%84%E5%BC%9F%E4%BC%9A%E8%AF%A1%E5%BC%82%E5%85%A5%E4%BC%9A%E4%BB%AA%E5%BC%8F%E6%9B%9D%E5%85%89%23) `62.6K 🔥` `-57%`

Updated at 2026-02-19 23:33:30

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
