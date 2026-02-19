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

1. [韩媒赛前嘲讽中国队0金被打脸 (Korean media ridiculed the Chinese team before the game and was slapped in the face for 0 gold medals)](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%AA%92%E8%B5%9B%E5%89%8D%E5%98%B2%E8%AE%BD%E4%B8%AD%E5%9B%BD%E9%98%9F0%E9%87%91%E8%A2%AB%E6%89%93%E8%84%B8%23) `1.1M 🔥` `NEW`
1. [尹锡悦今天或被判死刑](https://s.weibo.com/weibo?q=%23%E5%B0%B9%E9%94%A1%E6%82%A6%E4%BB%8A%E5%A4%A9%E6%88%96%E8%A2%AB%E5%88%A4%E6%AD%BB%E5%88%91%23) `769.7K 🔥` `NEW`
1. [从小逛到大的庙会](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E5%B0%8F%E9%80%9B%E5%88%B0%E5%A4%A7%E7%9A%84%E5%BA%99%E4%BC%9A%23) `637.1K 🔥` `NEW`
1. [蒙牛贺中国队夺金](https://s.weibo.com/weibo?q=%23%E8%92%99%E7%89%9B%E8%B4%BA%E4%B8%AD%E5%9B%BD%E9%98%9F%E5%A4%BA%E9%87%91%23) `492.3K 🔥` `NEW`
1. [今年调休变少了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E8%B0%83%E4%BC%91%E5%8F%98%E5%B0%91%E4%BA%86%23) `292.4K 🔥` `NEW`
1. [桃黑黑 大白菜](https://s.weibo.com/weibo?q=%23%E6%A1%83%E9%BB%91%E9%BB%91%20%E5%A4%A7%E7%99%BD%E8%8F%9C%23) `251.8K 🔥` `NEW`
1. [过年剩下的红包不要扔](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E5%89%A9%E4%B8%8B%E7%9A%84%E7%BA%A2%E5%8C%85%E4%B8%8D%E8%A6%81%E6%89%94%23) `243.4K 🔥` `NEW`
1. [林孝埈已为中国短道燃尽所有](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E5%B7%B2%E4%B8%BA%E4%B8%AD%E5%9B%BD%E7%9F%AD%E9%81%93%E7%87%83%E5%B0%BD%E6%89%80%E6%9C%89%23) `217.3K 🔥` `NEW`
1. [宜城烟花爆燃事故应急处置情况通报](https://s.weibo.com/weibo?q=%23%E5%AE%9C%E5%9F%8E%E7%83%9F%E8%8A%B1%E7%88%86%E7%87%83%E4%BA%8B%E6%95%85%E5%BA%94%E6%80%A5%E5%A4%84%E7%BD%AE%E6%83%85%E5%86%B5%E9%80%9A%E6%8A%A5%23) `211.2K 🔥` `NEW`
1. [罗布泊里的铁路驿站](https://s.weibo.com/weibo?q=%23%E7%BD%97%E5%B8%83%E6%B3%8A%E9%87%8C%E7%9A%84%E9%93%81%E8%B7%AF%E9%A9%BF%E7%AB%99%23) `200.7K 🔥` `NEW`
1. [热水器出现明火女子被吓懵 (Woman was frightened when open flame appeared in water heater)](https://s.weibo.com/weibo?q=%23%E7%83%AD%E6%B0%B4%E5%99%A8%E5%87%BA%E7%8E%B0%E6%98%8E%E7%81%AB%E5%A5%B3%E5%AD%90%E8%A2%AB%E5%90%93%E6%87%B5%23) `192.2K 🔥` `NEW`
1. [每天这4个小时最好在睡眠中度过](https://s.weibo.com/weibo?q=%23%E6%AF%8F%E5%A4%A9%E8%BF%994%E4%B8%AA%E5%B0%8F%E6%97%B6%E6%9C%80%E5%A5%BD%E5%9C%A8%E7%9D%A1%E7%9C%A0%E4%B8%AD%E5%BA%A6%E8%BF%87%23) `180.0K 🔥` `NEW`
1. [拍了三个月得闲谨制妈妈却没认出自己](https://s.weibo.com/weibo?q=%23%E6%8B%8D%E4%BA%86%E4%B8%89%E4%B8%AA%E6%9C%88%E5%BE%97%E9%97%B2%E8%B0%A8%E5%88%B6%E5%A6%88%E5%A6%88%E5%8D%B4%E6%B2%A1%E8%AE%A4%E5%87%BA%E8%87%AA%E5%B7%B1%23) `175.3K 🔥` `NEW`
1. [朱志鑫伦敦](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E4%BC%A6%E6%95%A6%23) `139.7K 🔥` `NEW`
1. [沙溢飞驰3犯的坏白展堂全责](https://s.weibo.com/weibo?q=%23%E6%B2%99%E6%BA%A2%E9%A3%9E%E9%A9%B03%E7%8A%AF%E7%9A%84%E5%9D%8F%E7%99%BD%E5%B1%95%E5%A0%82%E5%85%A8%E8%B4%A3%23) `121.3K 🔥` `NEW`
1. [女婿连续2年告状今年坐在丈人腿上](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%A9%BF%E8%BF%9E%E7%BB%AD2%E5%B9%B4%E5%91%8A%E7%8A%B6%E4%BB%8A%E5%B9%B4%E5%9D%90%E5%9C%A8%E4%B8%88%E4%BA%BA%E8%85%BF%E4%B8%8A%23) `120.3K 🔥` `NEW`
1. [宜城烟花爆竹爆燃5名未成年人遇难](https://s.weibo.com/weibo?q=%23%E5%AE%9C%E5%9F%8E%E7%83%9F%E8%8A%B1%E7%88%86%E7%AB%B9%E7%88%86%E7%87%835%E5%90%8D%E6%9C%AA%E6%88%90%E5%B9%B4%E4%BA%BA%E9%81%87%E9%9A%BE%23) `119.9K 🔥` `NEW`
1. [谷爱凌U池技巧预赛首位出场](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E6%B1%A0%E6%8A%80%E5%B7%A7%E9%A2%84%E8%B5%9B%E9%A6%96%E4%BD%8D%E5%87%BA%E5%9C%BA%23) `119.1K 🔥` `NEW`
1. [iPhone17e或将今日发布](https://s.weibo.com/weibo?q=%23iPhone17e%E6%88%96%E5%B0%86%E4%BB%8A%E6%97%A5%E5%8F%91%E5%B8%83%23) `118.5K 🔥` `NEW`
1. [谷爱凌这串笑声嘲讽拉满](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%BF%99%E4%B8%B2%E7%AC%91%E5%A3%B0%E5%98%B2%E8%AE%BD%E6%8B%89%E6%BB%A1%23) `117.8K 🔥` `NEW`
1. [张艺谋谈如何在垃圾桶捡手机 (Zhang Yimou talks about how to pick up mobile phones in the trash can)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%89%BA%E8%B0%8B%E8%B0%88%E5%A6%82%E4%BD%95%E5%9C%A8%E5%9E%83%E5%9C%BE%E6%A1%B6%E6%8D%A1%E6%89%8B%E6%9C%BA%23) `110.1K 🔥` `NEW`
1. [一下子分不清是谁在过年了](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%B8%8B%E5%AD%90%E5%88%86%E4%B8%8D%E6%B8%85%E6%98%AF%E8%B0%81%E5%9C%A8%E8%BF%87%E5%B9%B4%E4%BA%86%23) `108.2K 🔥` `NEW`
1. [冬季干敏皮护肤搭子](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%AD%A3%E5%B9%B2%E6%95%8F%E7%9A%AE%E6%8A%A4%E8%82%A4%E6%90%AD%E5%AD%90%23) `108.2K 🔥` `NEW`
1. [当化妆师回村后发现每个人的美](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%8C%96%E5%A6%86%E5%B8%88%E5%9B%9E%E6%9D%91%E5%90%8E%E5%8F%91%E7%8E%B0%E6%AF%8F%E4%B8%AA%E4%BA%BA%E7%9A%84%E7%BE%8E%23) `102.3K 🔥` `NEW`
1. [春节档佳片云集总有一款适合你](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E6%A1%A3%E4%BD%B3%E7%89%87%E4%BA%91%E9%9B%86%E6%80%BB%E6%9C%89%E4%B8%80%E6%AC%BE%E9%80%82%E5%90%88%E4%BD%A0%23) `99.5K 🔥` `NEW`
1. [曝侯明昊美妆营业额一小时600万](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E4%BE%AF%E6%98%8E%E6%98%8A%E7%BE%8E%E5%A6%86%E8%90%A5%E4%B8%9A%E9%A2%9D%E4%B8%80%E5%B0%8F%E6%97%B6600%E4%B8%87%23) `99.5K 🔥` `NEW`
1. [大侦探](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BE%A6%E6%8E%A2%23) `97.8K 🔥` `NEW`
1. [徐梦桃母校发喜报](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E6%AF%8D%E6%A0%A1%E5%8F%91%E5%96%9C%E6%8A%A5%23) `82.3K 🔥` `NEW`
1. [喜剧就要和家人一起看](https://s.weibo.com/weibo?q=%23%E5%96%9C%E5%89%A7%E5%B0%B1%E8%A6%81%E5%92%8C%E5%AE%B6%E4%BA%BA%E4%B8%80%E8%B5%B7%E7%9C%8B%23) `79.9K 🔥` `NEW`
1. [感觉有1亿人在汕头看烟花](https://s.weibo.com/weibo?q=%23%E6%84%9F%E8%A7%89%E6%9C%891%E4%BA%BF%E4%BA%BA%E5%9C%A8%E6%B1%95%E5%A4%B4%E7%9C%8B%E7%83%9F%E8%8A%B1%23) `79.9K 🔥` `NEW`
1. [王一博春晚高清大图 (Wang Yibo Spring Festival Gala HD large picture)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%98%A5%E6%99%9A%E9%AB%98%E6%B8%85%E5%A4%A7%E5%9B%BE%23) `78.5K 🔥` `NEW`
1. [苏翊鸣将备战下一届冬奥](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%B0%86%E5%A4%87%E6%88%98%E4%B8%8B%E4%B8%80%E5%B1%8A%E5%86%AC%E5%A5%A5%23) `77.1K 🔥` `NEW`
1. [马嘉祺珠海](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%98%89%E7%A5%BA%E7%8F%A0%E6%B5%B7%23) `73.5K 🔥` `NEW`
1. [惊蛰无声致敬隐姓埋名的他们](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%E8%87%B4%E6%95%AC%E9%9A%90%E5%A7%93%E5%9F%8B%E5%90%8D%E7%9A%84%E4%BB%96%E4%BB%AC%23) `72.4K 🔥` `NEW`
1. [林孝埈竞技状态令人遗憾](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E7%AB%9E%E6%8A%80%E7%8A%B6%E6%80%81%E4%BB%A4%E4%BA%BA%E9%81%97%E6%86%BE%23) `71.3K 🔥` `NEW`
1. [成毅8部剧全网曝光均破百亿](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%858%E9%83%A8%E5%89%A7%E5%85%A8%E7%BD%91%E6%9B%9D%E5%85%89%E5%9D%87%E7%A0%B4%E7%99%BE%E4%BA%BF%23) `60.7K 🔥` `NEW`
1. [飞驰人生3后劲好大 (Flying Life 3 has great stamina)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E5%90%8E%E5%8A%B2%E5%A5%BD%E5%A4%A7%23) `267.4K 🔥` `+87%`
1. [酷滕 双取 (Ku Teng double take)](https://s.weibo.com/weibo?q=%23%E9%85%B7%E6%BB%95%20%E5%8F%8C%E5%8F%96%23) `120.2K 🔥` `+23%`
1. [镖人票房趋势](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E8%B6%8B%E5%8A%BF%23) `108.2K 🔥` `+34%`
1. [镖人 对吴京黑转BLACKPINK (The escort turned to BLACKPINK on Wu Jinghei)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E5%AF%B9%E5%90%B4%E4%BA%AC%E9%BB%91%E8%BD%ACBLACKPINK%23) `160.1K 🔥`
1. [8岁小姨给晚辈发红包](https://s.weibo.com/weibo?q=%238%E5%B2%81%E5%B0%8F%E5%A7%A8%E7%BB%99%E6%99%9A%E8%BE%88%E5%8F%91%E7%BA%A2%E5%8C%85%23) `142.2K 🔥`
1. [大年初三睡睡睡](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%89%E7%9D%A1%E7%9D%A1%E7%9D%A1%23) `110.7K 🔥`
1. [半藏森林转型](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E8%97%8F%E6%A3%AE%E6%9E%97%E8%BD%AC%E5%9E%8B%23) `100.1K 🔥`
1. [刘少昂摔了 (Liu Shaoang fell)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82%E6%91%94%E4%BA%86%23) `79.6K 🔥`
1. [苏翊鸣甜蜜回复朱易 (Su Yiming sweetly replied to Zhu Yi)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%94%9C%E8%9C%9C%E5%9B%9E%E5%A4%8D%E6%9C%B1%E6%98%93%23) `282.8K 🔥` `-59%`
1. [初三一定记得睡懒觉 (Be sure to sleep in in the third grade of junior high school)](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%89%E4%B8%80%E5%AE%9A%E8%AE%B0%E5%BE%97%E7%9D%A1%E6%87%92%E8%A7%89%23) `271.0K 🔥` `-59%`
1. [苏翊鸣中日美关系最好的一集 (The best episode of Su Yiming's China-Japan-US relations)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E4%B8%AD%E6%97%A5%E7%BE%8E%E5%85%B3%E7%B3%BB%E6%9C%80%E5%A5%BD%E7%9A%84%E4%B8%80%E9%9B%86%23) `254.7K 🔥` `-62%`
1. [浪姐首位冬奥会卫冕冠军 (Sister Lang is the first defending Winter Olympics champion)](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E9%A6%96%E4%BD%8D%E5%86%AC%E5%A5%A5%E4%BC%9A%E5%8D%AB%E5%86%95%E5%86%A0%E5%86%9B%23) `177.3K 🔥` `-83%`
1. [朱一龙回应家里刘诗诗外面杨幂](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E4%B8%80%E9%BE%99%E5%9B%9E%E5%BA%94%E5%AE%B6%E9%87%8C%E5%88%98%E8%AF%97%E8%AF%97%E5%A4%96%E9%9D%A2%E6%9D%A8%E5%B9%82%23) `79.9K 🔥` `-63%`
1. [复旦大学教授讲自己儿子是学渣怎么办 (What should I do if a professor at Fudan University says his son is a scumbag?)](https://s.weibo.com/weibo?q=%23%E5%A4%8D%E6%97%A6%E5%A4%A7%E5%AD%A6%E6%95%99%E6%8E%88%E8%AE%B2%E8%87%AA%E5%B7%B1%E5%84%BF%E5%AD%90%E6%98%AF%E5%AD%A6%E6%B8%A3%E6%80%8E%E4%B9%88%E5%8A%9E%23) `79.9K 🔥` `-44%`
1. [林孝埈 遗憾](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%20%E9%81%97%E6%86%BE%23) `67.6K 🔥` `-32%`
1. [林孝埈无缘500米半决赛 (Lin Xiaojuan missed the 500m semifinals)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E6%97%A0%E7%BC%98500%E7%B1%B3%E5%8D%8A%E5%86%B3%E8%B5%9B%23) `63.5K 🔥` `-64%`

Updated at 2026-02-19 11:42:10

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
