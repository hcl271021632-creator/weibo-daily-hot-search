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

1. [尚界Z7双箭齐发 (Shangjie Z7 shoots both arrows together)](https://s.weibo.com/weibo?q=%23%E5%B0%9A%E7%95%8CZ7%E5%8F%8C%E7%AE%AD%E9%BD%90%E5%8F%91%23) `584.5K 🔥` `NEW`
1. [普京说考虑主动给欧洲断气](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E8%AF%B4%E8%80%83%E8%99%91%E4%B8%BB%E5%8A%A8%E7%BB%99%E6%AC%A7%E6%B4%B2%E6%96%AD%E6%B0%94%23) `578.2K 🔥` `NEW`
1. [第一场代表通道采访](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E5%9C%BA%E4%BB%A3%E8%A1%A8%E9%80%9A%E9%81%93%E9%87%87%E8%AE%BF%23) `285.1K 🔥` `NEW`
1. [曝十日终焉主演王天辰](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E4%B8%BB%E6%BC%94%E7%8E%8B%E5%A4%A9%E8%BE%B0%23) `282.7K 🔥` `NEW`
1. [没见过气血虚成这样的](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E8%A7%81%E8%BF%87%E6%B0%94%E8%A1%80%E8%99%9A%E6%88%90%E8%BF%99%E6%A0%B7%E7%9A%84%23) `281.7K 🔥` `NEW`
1. [冯琳王德发分手](https://s.weibo.com/weibo?q=%23%E5%86%AF%E7%90%B3%E7%8E%8B%E5%BE%B7%E5%8F%91%E5%88%86%E6%89%8B%23) `198.3K 🔥` `NEW`
1. [伊朗表示无意与美谈判](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A1%A8%E7%A4%BA%E6%97%A0%E6%84%8F%E4%B8%8E%E7%BE%8E%E8%B0%88%E5%88%A4%23) `197.1K 🔥` `NEW`
1. [中国芯片让区块链性能提升50倍](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E8%8A%AF%E7%89%87%E8%AE%A9%E5%8C%BA%E5%9D%97%E9%93%BE%E6%80%A7%E8%83%BD%E6%8F%90%E5%8D%8750%E5%80%8D%23) `195.6K 🔥` `NEW`
1. [汪涵读省委书记亲笔信](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E6%B6%B5%E8%AF%BB%E7%9C%81%E5%A7%94%E4%B9%A6%E8%AE%B0%E4%BA%B2%E7%AC%94%E4%BF%A1%23) `183.8K 🔥` `NEW`
1. [羽毛球降价原因](https://s.weibo.com/weibo?q=%23%E7%BE%BD%E6%AF%9B%E7%90%83%E9%99%8D%E4%BB%B7%E5%8E%9F%E5%9B%A0%23) `172.7K 🔥` `NEW`
1. [新疆地震 (Xinjiang earthquake)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E7%96%86%E5%9C%B0%E9%9C%87%23) `128.0K 🔥` `NEW`
1. [瞿桦的初恋](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E6%A1%A6%E7%9A%84%E5%88%9D%E6%81%8B%23) `113.2K 🔥` `NEW`
1. [姐姐姐夫的结局](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%E7%9A%84%E7%BB%93%E5%B1%80%23) `106.2K 🔥` `NEW`
1. [曝十日终焉领衔主演艾米](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E9%A2%86%E8%A1%94%E4%B8%BB%E6%BC%94%E8%89%BE%E7%B1%B3%23) `80.7K 🔥` `NEW`
1. [王者全体女英雄限免来了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%80%85%E5%85%A8%E4%BD%93%E5%A5%B3%E8%8B%B1%E9%9B%84%E9%99%90%E5%85%8D%E6%9D%A5%E4%BA%86%23) `79.7K 🔥` `NEW`
1. [不拥抱AI的人会被社会淘汰](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%8B%A5%E6%8A%B1AI%E7%9A%84%E4%BA%BA%E4%BC%9A%E8%A2%AB%E7%A4%BE%E4%BC%9A%E6%B7%98%E6%B1%B0%23) `78.1K 🔥` `NEW`
1. [人大代表反问微短剧爽完之后呢 (The National People's Congress representative asked what will happen after the mini-short play is over?)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E5%8F%8D%E9%97%AE%E5%BE%AE%E7%9F%AD%E5%89%A7%E7%88%BD%E5%AE%8C%E4%B9%8B%E5%90%8E%E5%91%A2%23) `1.1M 🔥` `+63%`
1. [物业费越来越难收](https://s.weibo.com/weibo?q=%23%E7%89%A9%E4%B8%9A%E8%B4%B9%E8%B6%8A%E6%9D%A5%E8%B6%8A%E9%9A%BE%E6%94%B6%23) `792.2K 🔥` `+252%`
1. [伊朗袭击以国防部大楼](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%E4%BB%A5%E5%9B%BD%E9%98%B2%E9%83%A8%E5%A4%A7%E6%A5%BC%23) `518.2K 🔥` `+241%`
1. [什么水果一听就很东北](https://s.weibo.com/weibo?q=%23%E4%BB%80%E4%B9%88%E6%B0%B4%E6%9E%9C%E4%B8%80%E5%90%AC%E5%B0%B1%E5%BE%88%E4%B8%9C%E5%8C%97%23) `358.6K 🔥` `+483%`
1. [代表谈吴克群帮农民卖3万斤菜](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%B0%88%E5%90%B4%E5%85%8B%E7%BE%A4%E5%B8%AE%E5%86%9C%E6%B0%91%E5%8D%963%E4%B8%87%E6%96%A4%E8%8F%9C%23) `280.7K 🔥` `+68%`
1. [叶璇说拍短剧老爽了 (Michelle Ye said that filming short dramas is always a pleasure)](https://s.weibo.com/weibo?q=%23%E5%8F%B6%E7%92%87%E8%AF%B4%E6%8B%8D%E7%9F%AD%E5%89%A7%E8%80%81%E7%88%BD%E4%BA%86%23) `280.7K 🔥` `+24%`
1. [惊蛰](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%23) `272.1K 🔥` `+43%`
1. [中国游客在日本目睹老太被壮汉撞飞](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E5%9C%A8%E6%97%A5%E6%9C%AC%E7%9B%AE%E7%9D%B9%E8%80%81%E5%A4%AA%E8%A2%AB%E5%A3%AE%E6%B1%89%E6%92%9E%E9%A3%9E%23) `248.4K 🔥` `+65%`
1. [最长学期后迎来史上最短学期 (The longest semester is followed by the shortest semester in history)](https://s.weibo.com/weibo?q=%23%E6%9C%80%E9%95%BF%E5%AD%A6%E6%9C%9F%E5%90%8E%E8%BF%8E%E6%9D%A5%E5%8F%B2%E4%B8%8A%E6%9C%80%E7%9F%AD%E5%AD%A6%E6%9C%9F%23) `240.1K 🔥` `+38%`
1. [迪丽热巴报平安](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%8A%A5%E5%B9%B3%E5%AE%89%23) `226.0K 🔥` `+46%`
1. [沙特阿美避开霍尔木兹海峡运原油 (Saudi Aramco avoids Strait of Hormuz to ship crude oil)](https://s.weibo.com/weibo?q=%23%E6%B2%99%E7%89%B9%E9%98%BF%E7%BE%8E%E9%81%BF%E5%BC%80%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E8%BF%90%E5%8E%9F%E6%B2%B9%23) `224.1K 🔥` `+57%`
1. [微信转账1万没写借条同学不还钱了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%BD%AC%E8%B4%A61%E4%B8%87%E6%B2%A1%E5%86%99%E5%80%9F%E6%9D%A1%E5%90%8C%E5%AD%A6%E4%B8%8D%E8%BF%98%E9%92%B1%E4%BA%86%23) `195.3K 🔥` `+40%`
1. [齐思钧吕严同一个初中同一个高中](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%80%9D%E9%92%A7%E5%90%95%E4%B8%A5%E5%90%8C%E4%B8%80%E4%B8%AA%E5%88%9D%E4%B8%AD%E5%90%8C%E4%B8%80%E4%B8%AA%E9%AB%98%E4%B8%AD%23) `194.2K 🔥` `+111%`
1. [纯真年代 真替身 (The Age of Innocence, True Substitute)](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%20%E7%9C%9F%E6%9B%BF%E8%BA%AB%23) `190.2K 🔥` `+66%`
1. [伊朗玫瑰宫遭袭前后对比 (Comparison before and after the attack on Iran’s Rose Palace)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%8E%AB%E7%91%B0%E5%AE%AB%E9%81%AD%E8%A2%AD%E5%89%8D%E5%90%8E%E5%AF%B9%E6%AF%94%23) `171.4K 🔥` `+33%`
1. [美国为何非要搞垮伊朗 (Why does the United States insist on destroying Iran?)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%BA%E4%BD%95%E9%9D%9E%E8%A6%81%E6%90%9E%E5%9E%AE%E4%BC%8A%E6%9C%97%23) `154.7K 🔥` `+41%`
1. [车停半个月被老鼠囤了20斤粮食 (The car was parked for half a month and rats hoarded 20 kilograms of grain.)](https://s.weibo.com/weibo?q=%23%E8%BD%A6%E5%81%9C%E5%8D%8A%E4%B8%AA%E6%9C%88%E8%A2%AB%E8%80%81%E9%BC%A0%E5%9B%A4%E4%BA%8620%E6%96%A4%E7%B2%AE%E9%A3%9F%23) `151.4K 🔥` `+55%`
1. [刘国梁建议加强挫折教育](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%9B%BD%E6%A2%81%E5%BB%BA%E8%AE%AE%E5%8A%A0%E5%BC%BA%E6%8C%AB%E6%8A%98%E6%95%99%E8%82%B2%23) `133.7K 🔥` `+55%`
1. [十日终焉 (End of ten days)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%23) `121.5K 🔥` `+21%`
1. [苹果新品 (Apple new products)](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%96%B0%E5%93%81%23) `109.3K 🔥` `+106%`
1. [iPhone17e上手](https://s.weibo.com/weibo?q=%23iPhone17e%E4%B8%8A%E6%89%8B%23) `100.8K 🔥` `+87%`
1. [易烊千玺告眼镜公司侵权索赔50.5万 (Yi Yang Qianxi sues an eyewear company for infringement of RMB 505,000)](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%91%8A%E7%9C%BC%E9%95%9C%E5%85%AC%E5%8F%B8%E4%BE%B5%E6%9D%83%E7%B4%A2%E8%B5%9450.5%E4%B8%87%23) `86.7K 🔥` `+24%`
1. [在中国式现代化新征程上策马奔腾 (Galloping forward on the new journey of Chinese-style modernization)](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%BC%8F%E7%8E%B0%E4%BB%A3%E5%8C%96%E6%96%B0%E5%BE%81%E7%A8%8B%E4%B8%8A%E7%AD%96%E9%A9%AC%E5%A5%94%E8%85%BE%23) `635.3K 🔥`
1. [3月5日两会日程 (Agenda for the two sessions on March 5)](https://s.weibo.com/weibo?q=%233%E6%9C%885%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%23) `527.7K 🔥`
1. [中东局势彻底失控](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%B8%9C%E5%B1%80%E5%8A%BF%E5%BD%BB%E5%BA%95%E5%A4%B1%E6%8E%A7%23) `283.4K 🔥`
1. [王鹤棣紫衣少年谢景行 (Wang Hedi, the boy in purple, Xie Jingxing)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E7%B4%AB%E8%A1%A3%E5%B0%91%E5%B9%B4%E8%B0%A2%E6%99%AF%E8%A1%8C%23) `230.1K 🔥`
1. [社保迎来第六险](https://s.weibo.com/weibo?q=%23%E7%A4%BE%E4%BF%9D%E8%BF%8E%E6%9D%A5%E7%AC%AC%E5%85%AD%E9%99%A9%23) `199.0K 🔥`
1. [苹果发布会 (Apple conference)](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E5%8F%91%E5%B8%83%E4%BC%9A%23) `160.4K 🔥`
1. [流动草莓摊因网友评价太好吃火了 (The mobile strawberry stand became popular because netizens commented that it was so delicious.)](https://s.weibo.com/weibo?q=%23%E6%B5%81%E5%8A%A8%E8%8D%89%E8%8E%93%E6%91%8A%E5%9B%A0%E7%BD%91%E5%8F%8B%E8%AF%84%E4%BB%B7%E5%A4%AA%E5%A5%BD%E5%90%83%E7%81%AB%E4%BA%86%23) `130.5K 🔥`
1. [韩蛇蝎美人被确认为反社会人格 (Korean femme fatale confirmed to be anti-social personality)](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E8%9B%87%E8%9D%8E%E7%BE%8E%E4%BA%BA%E8%A2%AB%E7%A1%AE%E8%AE%A4%E4%B8%BA%E5%8F%8D%E7%A4%BE%E4%BC%9A%E4%BA%BA%E6%A0%BC%23) `98.7K 🔥`
1. [谈到美国电网中国白发院士笑了 (Chinese white-haired academician laughed when talking about the U.S. power grid)](https://s.weibo.com/weibo?q=%23%E8%B0%88%E5%88%B0%E7%BE%8E%E5%9B%BD%E7%94%B5%E7%BD%91%E4%B8%AD%E5%9B%BD%E7%99%BD%E5%8F%91%E9%99%A2%E5%A3%AB%E7%AC%91%E4%BA%86%23) `90.2K 🔥`
1. [20岁小伙长期戴骨传导耳机致聋 (20-year-old boy suffers from deafness after wearing bone conduction headphones for a long time)](https://s.weibo.com/weibo?q=%2320%E5%B2%81%E5%B0%8F%E4%BC%99%E9%95%BF%E6%9C%9F%E6%88%B4%E9%AA%A8%E4%BC%A0%E5%AF%BC%E8%80%B3%E6%9C%BA%E8%87%B4%E8%81%8B%23) `484.4K 🔥` `-24%`
1. [我使馆提醒近期避免前往日本 (The embassy reminds you to avoid traveling to Japan in the near future)](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BD%BF%E9%A6%86%E6%8F%90%E9%86%92%E8%BF%91%E6%9C%9F%E9%81%BF%E5%85%8D%E5%89%8D%E5%BE%80%E6%97%A5%E6%9C%AC%23) `285.3K 🔥` `-70%`
1. [女子花20万住酒店3年遭员工吐槽](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%8A%B120%E4%B8%87%E4%BD%8F%E9%85%92%E5%BA%973%E5%B9%B4%E9%81%AD%E5%91%98%E5%B7%A5%E5%90%90%E6%A7%BD%23) `283.8K 🔥` `-54%`
1. [伊朗沉没军舰已找到80具遗体](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%B2%89%E6%B2%A1%E5%86%9B%E8%88%B0%E5%B7%B2%E6%89%BE%E5%88%B080%E5%85%B7%E9%81%97%E4%BD%93%23) `198.7K 🔥` `-68%`

Updated at 2026-03-05 08:56:23

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
