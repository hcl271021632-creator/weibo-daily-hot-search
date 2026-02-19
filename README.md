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

1. [苏翊鸣中日美关系最好的一集 (The best episode of Su Yiming's China-Japan-US relations)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E4%B8%AD%E6%97%A5%E7%BE%8E%E5%85%B3%E7%B3%BB%E6%9C%80%E5%A5%BD%E7%9A%84%E4%B8%80%E9%9B%86%23) `671.6K 🔥` `NEW`
1. [徐梦桃冠军时刻不止赛场](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E5%86%A0%E5%86%9B%E6%97%B6%E5%88%BB%E4%B8%8D%E6%AD%A2%E8%B5%9B%E5%9C%BA%23) `141.9K 🔥` `NEW`
1. [8岁小姨给晚辈发红包](https://s.weibo.com/weibo?q=%238%E5%B2%81%E5%B0%8F%E5%A7%A8%E7%BB%99%E6%99%9A%E8%BE%88%E5%8F%91%E7%BA%A2%E5%8C%85%23) `122.5K 🔥` `NEW`
1. [上海网红蛋糕店被拍到发霉草莓](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E7%BD%91%E7%BA%A2%E8%9B%8B%E7%B3%95%E5%BA%97%E8%A2%AB%E6%8B%8D%E5%88%B0%E5%8F%91%E9%9C%89%E8%8D%89%E8%8E%93%23) `97.6K 🔥` `NEW`
1. [大年初三睡睡睡](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%89%E7%9D%A1%E7%9D%A1%E7%9D%A1%23) `97.4K 🔥` `NEW`
1. [感谢日韩媒体的这一口奶](https://s.weibo.com/weibo?q=%23%E6%84%9F%E8%B0%A2%E6%97%A5%E9%9F%A9%E5%AA%92%E4%BD%93%E7%9A%84%E8%BF%99%E4%B8%80%E5%8F%A3%E5%A5%B6%23) `88.8K 🔥` `NEW`
1. [初五起冷空气来袭](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%BA%94%E8%B5%B7%E5%86%B7%E7%A9%BA%E6%B0%94%E6%9D%A5%E8%A2%AD%23) `87.8K 🔥` `NEW`
1. [镖人票房趋势](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E8%B6%8B%E5%8A%BF%23) `80.9K 🔥` `NEW`
1. [大年初三有什么讲究](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%89%E6%9C%89%E4%BB%80%E4%B9%88%E8%AE%B2%E7%A9%B6%23) `80.6K 🔥` `NEW`
1. [欧文赛季报销](https://s.weibo.com/weibo?q=%23%E6%AC%A7%E6%96%87%E8%B5%9B%E5%AD%A3%E6%8A%A5%E9%94%80%23) `78.6K 🔥` `NEW`
1. [安藤樱韩孝周金高银合照 (A group photo of Ando Sakura, Han Hyo-joo, Kim and Go-eun)](https://s.weibo.com/weibo?q=%23%E5%AE%89%E8%97%A4%E6%A8%B1%E9%9F%A9%E5%AD%9D%E5%91%A8%E9%87%91%E9%AB%98%E9%93%B6%E5%90%88%E7%85%A7%23) `77.4K 🔥` `NEW`
1. [狗狗烤火时把头靠在主人的腿上](https://s.weibo.com/weibo?q=%23%E7%8B%97%E7%8B%97%E7%83%A4%E7%81%AB%E6%97%B6%E6%8A%8A%E5%A4%B4%E9%9D%A0%E5%9C%A8%E4%B8%BB%E4%BA%BA%E7%9A%84%E8%85%BF%E4%B8%8A%23) `74.0K 🔥` `NEW`
1. [王鹤棣最后这个笑看的人头皮发麻](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%9C%80%E5%90%8E%E8%BF%99%E4%B8%AA%E7%AC%91%E7%9C%8B%E7%9A%84%E4%BA%BA%E5%A4%B4%E7%9A%AE%E5%8F%91%E9%BA%BB%23) `70.5K 🔥` `NEW`
1. [票房](https://s.weibo.com/weibo?q=%23%E7%A5%A8%E6%88%BF%23) `69.7K 🔥` `NEW`
1. [中日美三选手紧张等分好好笑](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%97%A5%E7%BE%8E%E4%B8%89%E9%80%89%E6%89%8B%E7%B4%A7%E5%BC%A0%E7%AD%89%E5%88%86%E5%A5%BD%E5%A5%BD%E7%AC%91%23) `65.3K 🔥` `NEW`
1. [徐梦桃感觉自己从从容容游刃有余](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E6%84%9F%E8%A7%89%E8%87%AA%E5%B7%B1%E4%BB%8E%E4%BB%8E%E5%AE%B9%E5%AE%B9%E6%B8%B8%E5%88%83%E6%9C%89%E4%BD%99%23) `61.3K 🔥` `NEW`
1. [徐梦桃荣耀时刻历史突破](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E8%8D%A3%E8%80%80%E6%97%B6%E5%88%BB%E5%8E%86%E5%8F%B2%E7%AA%81%E7%A0%B4%23) `59.6K 🔥` `NEW`
1. [深圳蝴蝶兰从250喊至120元成交](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E8%9D%B4%E8%9D%B6%E5%85%B0%E4%BB%8E250%E5%96%8A%E8%87%B3120%E5%85%83%E6%88%90%E4%BA%A4%23) `59.1K 🔥` `NEW`
1. [徐梦桃说35岁依然有无限可能](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E8%AF%B435%E5%B2%81%E4%BE%9D%E7%84%B6%E6%9C%89%E6%97%A0%E9%99%90%E5%8F%AF%E8%83%BD%23) `57.7K 🔥` `NEW`
1. [多方回应饭馆被熊锤门](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%96%B9%E5%9B%9E%E5%BA%94%E9%A5%AD%E9%A6%86%E8%A2%AB%E7%86%8A%E9%94%A4%E9%97%A8%23) `57.0K 🔥` `NEW`
1. [远离内耗的3个小方法 (3 small ways to stay away from internal friction)](https://s.weibo.com/weibo?q=%23%E8%BF%9C%E7%A6%BB%E5%86%85%E8%80%97%E7%9A%843%E4%B8%AA%E5%B0%8F%E6%96%B9%E6%B3%95%23) `56.5K 🔥` `NEW`
1. [浪姐首位冬奥会卫冕冠军](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E9%A6%96%E4%BD%8D%E5%86%AC%E5%A5%A5%E4%BC%9A%E5%8D%AB%E5%86%95%E5%86%A0%E5%86%9B%23) `1.1M 🔥` `+459%`
1. [今年的假放了但没完全放](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E7%9A%84%E5%81%87%E6%94%BE%E4%BA%86%E4%BD%86%E6%B2%A1%E5%AE%8C%E5%85%A8%E6%94%BE%23) `782.0K 🔥` `+1761%`
1. [00后新兵有啥心愿 (What are the wishes of the new recruits born in 2000?)](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E6%96%B0%E5%85%B5%E6%9C%89%E5%95%A5%E5%BF%83%E6%84%BF%23) `716.1K 🔥` `+34%`
1. [苏翊鸣甜蜜回复朱易 (Su Yiming sweetly replied to Zhu Yi)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%94%9C%E8%9C%9C%E5%9B%9E%E5%A4%8D%E6%9C%B1%E6%98%93%23) `682.7K 🔥` `+84%`
1. [初三一定记得睡懒觉 (Be sure to sleep in in the third grade of junior high school)](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%89%E4%B8%80%E5%AE%9A%E8%AE%B0%E5%BE%97%E7%9D%A1%E6%87%92%E8%A7%89%23) `660.9K 🔥` `+268%`
1. [朱一龙回应家里刘诗诗外面杨幂](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E4%B8%80%E9%BE%99%E5%9B%9E%E5%BA%94%E5%AE%B6%E9%87%8C%E5%88%98%E8%AF%97%E8%AF%97%E5%A4%96%E9%9D%A2%E6%9D%A8%E5%B9%82%23) `214.6K 🔥` `+311%`
1. [飞驰人生3杀疯了](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E6%9D%80%E7%96%AF%E4%BA%86%23) `191.6K 🔥` `+42%`
1. [年入35万扛楼小伙回应买车质疑](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%85%A535%E4%B8%87%E6%89%9B%E6%A5%BC%E5%B0%8F%E4%BC%99%E5%9B%9E%E5%BA%94%E4%B9%B0%E8%BD%A6%E8%B4%A8%E7%96%91%23) `141.9K 🔥` `+34%`
1. [徐梦桃回应是否参加下届冬奥会](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E5%9B%9E%E5%BA%94%E6%98%AF%E5%90%A6%E5%8F%82%E5%8A%A0%E4%B8%8B%E5%B1%8A%E5%86%AC%E5%A5%A5%E4%BC%9A%23) `141.9K 🔥` `+68%`
1. [刘宇宁展示最满意的身体部位](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%B1%95%E7%A4%BA%E6%9C%80%E6%BB%A1%E6%84%8F%E7%9A%84%E8%BA%AB%E4%BD%93%E9%83%A8%E4%BD%8D%23) `132.1K 🔥` `+169%`
1. [半藏森林转型](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E8%97%8F%E6%A3%AE%E6%9E%97%E8%BD%AC%E5%9E%8B%23) `98.3K 🔥` `+75%`
1. [酷滕 双取 (Ku Teng double take)](https://s.weibo.com/weibo?q=%23%E9%85%B7%E6%BB%95%20%E5%8F%8C%E5%8F%96%23) `98.0K 🔥` `+74%`
1. [苏翊鸣和亚军季军角落等分好搞笑](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%92%8C%E4%BA%9A%E5%86%9B%E5%AD%A3%E5%86%9B%E8%A7%92%E8%90%BD%E7%AD%89%E5%88%86%E5%A5%BD%E6%90%9E%E7%AC%91%23) `97.5K 🔥` `+75%`
1. [5个月宝宝抬头巧变磕头喜提红包 (5-month-old baby cleverly kowtows when he raises his head and gives a red envelope)](https://s.weibo.com/weibo?q=%235%E4%B8%AA%E6%9C%88%E5%AE%9D%E5%AE%9D%E6%8A%AC%E5%A4%B4%E5%B7%A7%E5%8F%98%E7%A3%95%E5%A4%B4%E5%96%9C%E6%8F%90%E7%BA%A2%E5%8C%85%23) `97.4K 🔥` `+81%`
1. [5种高危剩菜宁可倒掉也不能吃 (5 high-risk leftovers that you would rather throw away than eat)](https://s.weibo.com/weibo?q=%235%E7%A7%8D%E9%AB%98%E5%8D%B1%E5%89%A9%E8%8F%9C%E5%AE%81%E5%8F%AF%E5%80%92%E6%8E%89%E4%B9%9F%E4%B8%8D%E8%83%BD%E5%90%83%23) `97.3K 🔥` `+76%`
1. [爱泼斯坦通过伦敦机场贩运女性](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%B3%BC%E6%96%AF%E5%9D%A6%E9%80%9A%E8%BF%87%E4%BC%A6%E6%95%A6%E6%9C%BA%E5%9C%BA%E8%B4%A9%E8%BF%90%E5%A5%B3%E6%80%A7%23) `87.7K 🔥` `+62%`
1. [中国香港居民在北海道遇袭 (Hong Kong residents attacked in Hokkaido)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%A6%99%E6%B8%AF%E5%B1%85%E6%B0%91%E5%9C%A8%E5%8C%97%E6%B5%B7%E9%81%93%E9%81%87%E8%A2%AD%23) `71.9K 🔥` `+31%`
1. [苏翊鸣赛前1小时才决定动作方案 (Su Yiming decided on his action plan only 1 hour before the game.)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E8%B5%9B%E5%89%8D1%E5%B0%8F%E6%97%B6%E6%89%8D%E5%86%B3%E5%AE%9A%E5%8A%A8%E4%BD%9C%E6%96%B9%E6%A1%88%23) `65.2K 🔥` `+32%`
1. [短道速滑](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `59.8K 🔥` `+42%`
1. [林孝埈无缘500米半决赛 (Lin Xiaojuan missed the 500m semifinals)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E6%97%A0%E7%BC%98500%E7%B1%B3%E5%8D%8A%E5%86%B3%E8%B5%9B%23) `174.4K 🔥`
1. [外网如何评价春晚机器人 (How do external networks evaluate Spring Festival Gala robots?)](https://s.weibo.com/weibo?q=%23%E5%A4%96%E7%BD%91%E5%A6%82%E4%BD%95%E8%AF%84%E4%BB%B7%E6%98%A5%E6%99%9A%E6%9C%BA%E5%99%A8%E4%BA%BA%23) `142.0K 🔥`
1. [复旦大学教授讲自己儿子是学渣怎么办 (What should I do if a professor at Fudan University says his son is a scumbag?)](https://s.weibo.com/weibo?q=%23%E5%A4%8D%E6%97%A6%E5%A4%A7%E5%AD%A6%E6%95%99%E6%8E%88%E8%AE%B2%E8%87%AA%E5%B7%B1%E5%84%BF%E5%AD%90%E6%98%AF%E5%AD%A6%E6%B8%A3%E6%80%8E%E4%B9%88%E5%8A%9E%23) `142.0K 🔥`
1. [镖人 对吴京黑转BLACKPINK (The escort turned to BLACKPINK on Wu Jinghei)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E5%AF%B9%E5%90%B4%E4%BA%AC%E9%BB%91%E8%BD%ACBLACKPINK%23) `142.0K 🔥`
1. [中国奖牌榜反超韩国](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%96%E7%89%8C%E6%A6%9C%E5%8F%8D%E8%B6%85%E9%9F%A9%E5%9B%BD%23) `101.1K 🔥`
1. [朱易发合影祝贺苏翊鸣 (Zhu Yifa took a group photo to congratulate Su Yiming)](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E6%98%93%E5%8F%91%E5%90%88%E5%BD%B1%E7%A5%9D%E8%B4%BA%E8%8B%8F%E7%BF%8A%E9%B8%A3%23) `99.3K 🔥`
1. [徐梦桃金牌 (Xu Mengtao gold medal)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E9%87%91%E7%89%8C%23) `76.0K 🔥`
1. [林孝埈 遗憾](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%20%E9%81%97%E6%86%BE%23) `98.9K 🔥` `-90%`
1. [刘少昂摔了 (Liu Shaoang fell)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82%E6%91%94%E4%BA%86%23) `97.5K 🔥` `-86%`
1. [太奶奶实在是上边没人了](https://s.weibo.com/weibo?q=%23%E5%A4%AA%E5%A5%B6%E5%A5%B6%E5%AE%9E%E5%9C%A8%E6%98%AF%E4%B8%8A%E8%BE%B9%E6%B2%A1%E4%BA%BA%E4%BA%86%23) `79.5K 🔥` `-31%`

Updated at 2026-02-19 08:58:17

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
