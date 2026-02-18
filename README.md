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

1. [复旦大学教授讲自己儿子是学渣怎么办 (What should I do if a professor at Fudan University says his son is a scumbag?)](https://s.weibo.com/weibo?q=%23%E5%A4%8D%E6%97%A6%E5%A4%A7%E5%AD%A6%E6%95%99%E6%8E%88%E8%AE%B2%E8%87%AA%E5%B7%B1%E5%84%BF%E5%AD%90%E6%98%AF%E5%AD%A6%E6%B8%A3%E6%80%8E%E4%B9%88%E5%8A%9E%23) `118.9K 🔥` `NEW`
1. [徐梦桃回应是否参加下届冬奥会](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E5%9B%9E%E5%BA%94%E6%98%AF%E5%90%A6%E5%8F%82%E5%8A%A0%E4%B8%8B%E5%B1%8A%E5%86%AC%E5%A5%A5%E4%BC%9A%23) `84.6K 🔥` `NEW`
1. [苏翊鸣和亚军季军角落等分好搞笑](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%92%8C%E4%BA%9A%E5%86%9B%E5%AD%A3%E5%86%9B%E8%A7%92%E8%90%BD%E7%AD%89%E5%88%86%E5%A5%BD%E6%90%9E%E7%AC%91%23) `55.8K 🔥` `NEW`
1. [5种高危剩菜宁可倒掉也不能吃](https://s.weibo.com/weibo?q=%235%E7%A7%8D%E9%AB%98%E5%8D%B1%E5%89%A9%E8%8F%9C%E5%AE%81%E5%8F%AF%E5%80%92%E6%8E%89%E4%B9%9F%E4%B8%8D%E8%83%BD%E5%90%83%23) `55.2K 🔥` `NEW`
1. [爱泼斯坦通过伦敦机场贩运女性](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%B3%BC%E6%96%AF%E5%9D%A6%E9%80%9A%E8%BF%87%E4%BC%A6%E6%95%A6%E6%9C%BA%E5%9C%BA%E8%B4%A9%E8%BF%90%E5%A5%B3%E6%80%A7%23) `54.1K 🔥` `NEW`
1. [朱一龙回应家里刘诗诗外面杨幂](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E4%B8%80%E9%BE%99%E5%9B%9E%E5%BA%94%E5%AE%B6%E9%87%8C%E5%88%98%E8%AF%97%E8%AF%97%E5%A4%96%E9%9D%A2%E6%9D%A8%E5%B9%82%23) `52.3K 🔥` `NEW`
1. [湖北宜城一爆竹店爆炸附近居民发声](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8C%97%E5%AE%9C%E5%9F%8E%E4%B8%80%E7%88%86%E7%AB%B9%E5%BA%97%E7%88%86%E7%82%B8%E9%99%84%E8%BF%91%E5%B1%85%E6%B0%91%E5%8F%91%E5%A3%B0%23) `52.0K 🔥` `NEW`
1. [刘宇宁展示最满意的身体部位](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%B1%95%E7%A4%BA%E6%9C%80%E6%BB%A1%E6%84%8F%E7%9A%84%E8%BA%AB%E4%BD%93%E9%83%A8%E4%BD%8D%23) `49.1K 🔥` `NEW`
1. [今年的假放了但没完全放](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E7%9A%84%E5%81%87%E6%94%BE%E4%BA%86%E4%BD%86%E6%B2%A1%E5%AE%8C%E5%85%A8%E6%94%BE%23) `42.0K 🔥` `NEW`
1. [林孝埈 遗憾](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%20%E9%81%97%E6%86%BE%23) `952.2K 🔥` `+29%`
1. [刘少昂摔了 (Liu Shaoang fell)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82%E6%91%94%E4%BA%86%23) `706.1K 🔥` `+28%`
1. [00后新兵有啥心愿 (What are the wishes of the new recruits born in 2000?)](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E6%96%B0%E5%85%B5%E6%9C%89%E5%95%A5%E5%BF%83%E6%84%BF%23) `535.8K 🔥` `+22%`
1. [初三一定记得睡懒觉 (Be sure to sleep in in the third grade of junior high school)](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B8%89%E4%B8%80%E5%AE%9A%E8%AE%B0%E5%BE%97%E7%9D%A1%E6%87%92%E8%A7%89%23) `179.6K 🔥` `+22%`
1. [外网如何评价春晚机器人 (How do external networks evaluate Spring Festival Gala robots?)](https://s.weibo.com/weibo?q=%23%E5%A4%96%E7%BD%91%E5%A6%82%E4%BD%95%E8%AF%84%E4%BB%B7%E6%98%A5%E6%99%9A%E6%9C%BA%E5%99%A8%E4%BA%BA%23) `169.3K 🔥` `+35%`
1. [林孝埈无缘500米半决赛 (Lin Xiaojuan missed the 500m semifinals)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E6%97%A0%E7%BC%98500%E7%B1%B3%E5%8D%8A%E5%86%B3%E8%B5%9B%23) `147.5K 🔥` `+22%`
1. [飞驰人生3杀疯了](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E6%9D%80%E7%96%AF%E4%BA%86%23) `134.8K 🔥` `+35%`
1. [中国奖牌榜反超韩国](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%96%E7%89%8C%E6%A6%9C%E5%8F%8D%E8%B6%85%E9%9F%A9%E5%9B%BD%23) `120.1K 🔥` `+27%`
1. [镖人 对吴京黑转BLACKPINK (The escort turned to BLACKPINK on Wu Jinghei)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E5%AF%B9%E5%90%B4%E4%BA%AC%E9%BB%91%E8%BD%ACBLACKPINK%23) `118.6K 🔥` `+22%`
1. [太奶奶实在是上边没人了](https://s.weibo.com/weibo?q=%23%E5%A4%AA%E5%A5%B6%E5%A5%B6%E5%AE%9E%E5%9C%A8%E6%98%AF%E4%B8%8A%E8%BE%B9%E6%B2%A1%E4%BA%BA%E4%BA%86%23) `115.7K 🔥` `+47%`
1. [年入35万扛楼小伙回应买车质疑](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%85%A535%E4%B8%87%E6%89%9B%E6%A5%BC%E5%B0%8F%E4%BC%99%E5%9B%9E%E5%BA%94%E4%B9%B0%E8%BD%A6%E8%B4%A8%E7%96%91%23) `105.8K 🔥` `+36%`
1. [朱易发合影祝贺苏翊鸣 (Zhu Yifa took a group photo to congratulate Su Yiming)](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E6%98%93%E5%8F%91%E5%90%88%E5%BD%B1%E7%A5%9D%E8%B4%BA%E8%8B%8F%E7%BF%8A%E9%B8%A3%23) `82.5K 🔥` `+27%`
1. [杨幂刘诗诗时隔16年同框宣发 (Yang Mi and Liu Shishi announced in the same frame after 16 years)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E5%88%98%E8%AF%97%E8%AF%97%E6%97%B6%E9%9A%9416%E5%B9%B4%E5%90%8C%E6%A1%86%E5%AE%A3%E5%8F%91%23) `63.3K 🔥` `+41%`
1. [5个月宝宝抬头巧变磕头喜提红包 (5-month-old baby cleverly kowtows when he raises his head and gives a red envelope)](https://s.weibo.com/weibo?q=%235%E4%B8%AA%E6%9C%88%E5%AE%9D%E5%AE%9D%E6%8A%AC%E5%A4%B4%E5%B7%A7%E5%8F%98%E7%A3%95%E5%A4%B4%E5%96%9C%E6%8F%90%E7%BA%A2%E5%8C%85%23) `53.8K 🔥` `+49%`
1. [苏翊鸣金牌](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E9%87%91%E7%89%8C%23) `52.0K 🔥` `+33%`
1. [任子威说刘少昂倾斜角度太大了](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E5%AD%90%E5%A8%81%E8%AF%B4%E5%88%98%E5%B0%91%E6%98%82%E5%80%BE%E6%96%9C%E8%A7%92%E5%BA%A6%E5%A4%AA%E5%A4%A7%E4%BA%86%23) `51.8K 🔥` `+35%`
1. [任子威说500米名单太恐怖](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E5%AD%90%E5%A8%81%E8%AF%B4500%E7%B1%B3%E5%90%8D%E5%8D%95%E5%A4%AA%E6%81%90%E6%80%96%23) `48.5K 🔥` `+26%`
1. [台湾女子被臭豆腐店熏到焦虑拔头发](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E5%A5%B3%E5%AD%90%E8%A2%AB%E8%87%AD%E8%B1%86%E8%85%90%E5%BA%97%E7%86%8F%E5%88%B0%E7%84%A6%E8%99%91%E6%8B%94%E5%A4%B4%E5%8F%91%23) `47.9K 🔥` `+36%`
1. [教练说苏翊鸣米兰夺金前不能谈恋爱 (The coach said that Su Yiming cannot fall in love before winning the gold medal in Milan)](https://s.weibo.com/weibo?q=%23%E6%95%99%E7%BB%83%E8%AF%B4%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%B1%B3%E5%85%B0%E5%A4%BA%E9%87%91%E5%89%8D%E4%B8%8D%E8%83%BD%E8%B0%88%E6%81%8B%E7%88%B1%23) `42.6K 🔥` `+23%`
1. [星河入梦](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%23) `42.1K 🔥` `+21%`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `42.0K 🔥` `+21%`
1. [朱易 苏翊鸣 (Zhu Yi Su Yiming)](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E6%98%93%20%E8%8B%8F%E7%BF%8A%E9%B8%A3%23) `42.0K 🔥` `+21%`
1. [徐梦桃说没法冷静 (Xu Mengtao said she couldn’t calm down)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E8%AF%B4%E6%B2%A1%E6%B3%95%E5%86%B7%E9%9D%99%23) `42.0K 🔥` `+21%`
1. [冬奥短道速滑男子500米 (Winter Olympics short track speed skating men's 500 meters)](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E7%94%B7%E5%AD%90500%E7%B1%B3%23) `42.0K 🔥` `+22%`
1. [中国队米兰冬奥首金](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E9%A6%96%E9%87%91%23) `42.0K 🔥` `+21%`
1. [苏翊鸣甜蜜回复朱易 (Su Yiming sweetly replied to Zhu Yi)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%94%9C%E8%9C%9C%E5%9B%9E%E5%A4%8D%E6%9C%B1%E6%98%93%23) `370.4K 🔥`
1. [浪姐首位冬奥会卫冕冠军](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E9%A6%96%E4%BD%8D%E5%86%AC%E5%A5%A5%E4%BC%9A%E5%8D%AB%E5%86%95%E5%86%A0%E5%86%9B%23) `188.2K 🔥`
1. [徐梦桃金牌 (Xu Mengtao gold medal)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E9%87%91%E7%89%8C%23) `92.4K 🔥`
1. [徐梦桃 文能浪姐唱跳武能冬奥夺冠 (Sister Xu Mengtao and Wen Nenglang sing and dance to win the Winter Olympics)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%20%E6%96%87%E8%83%BD%E6%B5%AA%E5%A7%90%E5%94%B1%E8%B7%B3%E6%AD%A6%E8%83%BD%E5%86%AC%E5%A5%A5%E5%A4%BA%E5%86%A0%23) `75.4K 🔥`
1. [韩国短道女子3000米接力夺金](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E7%9F%AD%E9%81%93%E5%A5%B3%E5%AD%903000%E7%B1%B3%E6%8E%A5%E5%8A%9B%E5%A4%BA%E9%87%91%23) `56.7K 🔥`
1. [半藏森林转型](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E8%97%8F%E6%A3%AE%E6%9E%97%E8%BD%AC%E5%9E%8B%23) `56.3K 🔥`
1. [酷滕 双取 (Ku Teng double take)](https://s.weibo.com/weibo?q=%23%E9%85%B7%E6%BB%95%20%E5%8F%8C%E5%8F%96%23) `56.2K 🔥`
1. [中国香港居民在北海道遇袭 (Hong Kong residents attacked in Hokkaido)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%A6%99%E6%B8%AF%E5%B1%85%E6%B0%91%E5%9C%A8%E5%8C%97%E6%B5%B7%E9%81%93%E9%81%87%E8%A2%AD%23) `54.7K 🔥`
1. [苏翊鸣祝贺徐梦桃](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%A5%9D%E8%B4%BA%E5%BE%90%E6%A2%A6%E6%A1%83%23) `53.6K 🔥`
1. [苏翊鸣赛前1小时才决定动作方案 (Su Yiming decided on his action plan only 1 hour before the game.)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E8%B5%9B%E5%89%8D1%E5%B0%8F%E6%97%B6%E6%89%8D%E5%86%B3%E5%AE%9A%E5%8A%A8%E4%BD%9C%E6%96%B9%E6%A1%88%23) `49.3K 🔥`
1. [大年初三 (The third day of the Lunar New Year)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%89%23) `46.8K 🔥`
1. [杜博伊斯500米金牌](https://s.weibo.com/weibo?q=%23%E6%9D%9C%E5%8D%9A%E4%BC%8A%E6%96%AF500%E7%B1%B3%E9%87%91%E7%89%8C%23) `46.0K 🔥`
1. [日本挖到含稀土泥浆的真相来了 (Here’s the truth about mud containing rare earths dug up in Japan)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%8C%96%E5%88%B0%E5%90%AB%E7%A8%80%E5%9C%9F%E6%B3%A5%E6%B5%86%E7%9A%84%E7%9C%9F%E7%9B%B8%E6%9D%A5%E4%BA%86%23) `44.8K 🔥`
1. [谁把郭富城鞋踩掉了 (Who stepped on Aaron Kwok's shoes?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%8A%8A%E9%83%AD%E5%AF%8C%E5%9F%8E%E9%9E%8B%E8%B8%A9%E6%8E%89%E4%BA%86%23) `43.8K 🔥`
1. [短道速滑](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `42.1K 🔥`
1. [曝邓超怒怼项目方维护孙俪 (Exposed: Deng Chao angrily criticized the project side for defending Sun Li)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E9%82%93%E8%B6%85%E6%80%92%E6%80%BC%E9%A1%B9%E7%9B%AE%E6%96%B9%E7%BB%B4%E6%8A%A4%E5%AD%99%E4%BF%AA%23) `42.0K 🔥`

Updated at 2026-02-19 07:49:26

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
