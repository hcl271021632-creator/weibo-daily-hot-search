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

1. [长护险减轻群众负担超千亿元 (Long-term care insurance reduces the burden on the public by more than 100 billion yuan)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%8A%A4%E9%99%A9%E5%87%8F%E8%BD%BB%E7%BE%A4%E4%BC%97%E8%B4%9F%E6%8B%85%E8%B6%85%E5%8D%83%E4%BA%BF%E5%85%83%23) `627.3K 🔥` `NEW`
1. [白敬亭郑合惠子互动](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E9%83%91%E5%90%88%E6%83%A0%E5%AD%90%E4%BA%92%E5%8A%A8%23) `413.7K 🔥` `NEW`
1. [伊朗导弹2小时内4次密集砸向以本土](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B92%E5%B0%8F%E6%97%B6%E5%86%854%E6%AC%A1%E5%AF%86%E9%9B%86%E7%A0%B8%E5%90%91%E4%BB%A5%E6%9C%AC%E5%9C%9F%23) `346.2K 🔥` `NEW`
1. [张凌赫宋祖儿 刺棠](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%AE%8B%E7%A5%96%E5%84%BF%20%E5%88%BA%E6%A3%A0%23) `341.5K 🔥` `NEW`
1. [罗永浩深度对话杨笠](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%B0%B8%E6%B5%A9%E6%B7%B1%E5%BA%A6%E5%AF%B9%E8%AF%9D%E6%9D%A8%E7%AC%A0%23) `340.9K 🔥` `NEW`
1. [逐玉 he](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20he%23) `339.9K 🔥` `NEW`
1. [孙颖莎最心酸的一场比赛](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E6%9C%80%E5%BF%83%E9%85%B8%E7%9A%84%E4%B8%80%E5%9C%BA%E6%AF%94%E8%B5%9B%23) `337.4K 🔥` `NEW`
1. [罗技侮辱消费者](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%8A%80%E4%BE%AE%E8%BE%B1%E6%B6%88%E8%B4%B9%E8%80%85%23) `335.9K 🔥` `NEW`
1. [梁祯元 李羲承](https://s.weibo.com/weibo?q=%23%E6%A2%81%E7%A5%AF%E5%85%83%20%E6%9D%8E%E7%BE%B2%E6%89%BF%23) `333.5K 🔥` `NEW`
1. [罗技 像狗一样跑过来](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%8A%80%20%E5%83%8F%E7%8B%97%E4%B8%80%E6%A0%B7%E8%B7%91%E8%BF%87%E6%9D%A5%23) `265.5K 🔥` `NEW`
1. [千问和机器人整上人情世故了 (Qianwen and the robot have become sociable.)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%92%8C%E6%9C%BA%E5%99%A8%E4%BA%BA%E6%95%B4%E4%B8%8A%E4%BA%BA%E6%83%85%E4%B8%96%E6%95%85%E4%BA%86%23) `264.7K 🔥` `NEW`
1. [标配1500TOPS金标大众太顶了](https://s.weibo.com/weibo?q=%23%E6%A0%87%E9%85%8D1500TOPS%E9%87%91%E6%A0%87%E5%A4%A7%E4%BC%97%E5%A4%AA%E9%A1%B6%E4%BA%86%23) `235.9K 🔥` `NEW`
1. [陈都灵聊宠物出行太共情了](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%83%BD%E7%81%B5%E8%81%8A%E5%AE%A0%E7%89%A9%E5%87%BA%E8%A1%8C%E5%A4%AA%E5%85%B1%E6%83%85%E4%BA%86%23) `224.4K 🔥` `NEW`
1. [宋Ultra全系标配闪充15.19万起](https://s.weibo.com/weibo?q=%23%E5%AE%8BUltra%E5%85%A8%E7%B3%BB%E6%A0%87%E9%85%8D%E9%97%AA%E5%85%8515.19%E4%B8%87%E8%B5%B7%23) `124.2K 🔥` `NEW`
1. [美方被曝正酝酿对伊朗最后一击](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E6%96%B9%E8%A2%AB%E6%9B%9D%E6%AD%A3%E9%85%9D%E9%85%BF%E5%AF%B9%E4%BC%8A%E6%9C%97%E6%9C%80%E5%90%8E%E4%B8%80%E5%87%BB%23) `122.2K 🔥` `NEW`
1. [白鹿陈哲远合拍](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E9%99%88%E5%93%B2%E8%BF%9C%E5%90%88%E6%8B%8D%23) `115.4K 🔥` `NEW`
1. [这些情况是心脏在报警](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%BA%9B%E6%83%85%E5%86%B5%E6%98%AF%E5%BF%83%E8%84%8F%E5%9C%A8%E6%8A%A5%E8%AD%A6%23) `96.4K 🔥` `NEW`
1. [日网痛批日本小学午餐](https://s.weibo.com/weibo?q=%23%E6%97%A5%E7%BD%91%E7%97%9B%E6%89%B9%E6%97%A5%E6%9C%AC%E5%B0%8F%E5%AD%A6%E5%8D%88%E9%A4%90%23) `96.1K 🔥` `NEW`
1. [Tian回归TES](https://s.weibo.com/weibo?q=%23Tian%E5%9B%9E%E5%BD%92TES%23) `93.7K 🔥` `NEW`
1. [蔡康永问马龙观众特别漂亮会紧张吗](https://s.weibo.com/weibo?q=%23%E8%94%A1%E5%BA%B7%E6%B0%B8%E9%97%AE%E9%A9%AC%E9%BE%99%E8%A7%82%E4%BC%97%E7%89%B9%E5%88%AB%E6%BC%82%E4%BA%AE%E4%BC%9A%E7%B4%A7%E5%BC%A0%E5%90%97%23) `92.1K 🔥` `NEW`
1. [全球石油储备仅够3至4个月 (Global oil reserves are only enough for 3 to 4 months)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E7%9F%B3%E6%B2%B9%E5%82%A8%E5%A4%87%E4%BB%85%E5%A4%9F3%E8%87%B34%E4%B8%AA%E6%9C%88%23) `89.2K 🔥` `NEW`
1. [谢征樊长玉马车吻](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E9%A9%AC%E8%BD%A6%E5%90%BB%23) `89.1K 🔥` `NEW`
1. [金价为何急涨急跌](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E4%B8%BA%E4%BD%95%E6%80%A5%E6%B6%A8%E6%80%A5%E8%B7%8C%23) `88.4K 🔥` `NEW`
1. [女子未婚先孕生完孩子被男友拉黑](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%9C%AA%E5%A9%9A%E5%85%88%E5%AD%95%E7%94%9F%E5%AE%8C%E5%AD%A9%E5%AD%90%E8%A2%AB%E7%94%B7%E5%8F%8B%E6%8B%89%E9%BB%91%23) `84.0K 🔥` `NEW`
1. [宋亚轩说马嘉祺有老人味](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BA%9A%E8%BD%A9%E8%AF%B4%E9%A9%AC%E5%98%89%E7%A5%BA%E6%9C%89%E8%80%81%E4%BA%BA%E5%91%B3%23) `79.9K 🔥` `NEW`
1. [甲醇价格暴涨原因](https://s.weibo.com/weibo?q=%23%E7%94%B2%E9%86%87%E4%BB%B7%E6%A0%BC%E6%9A%B4%E6%B6%A8%E5%8E%9F%E5%9B%A0%23) `73.4K 🔥` `NEW`
1. [迪拜楼市遭重挫](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E6%8B%9C%E6%A5%BC%E5%B8%82%E9%81%AD%E9%87%8D%E6%8C%AB%23) `68.3K 🔥` `NEW`
1. [微博文化交流之夜澳门站开票 (Weibo Cultural Exchange Night Macau Station Ticket Opening)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E5%8D%9A%E6%96%87%E5%8C%96%E4%BA%A4%E6%B5%81%E4%B9%8B%E5%A4%9C%E6%BE%B3%E9%97%A8%E7%AB%99%E5%BC%80%E7%A5%A8%23) `484.2K 🔥` `+25%`
1. [因抢玩具殴打2岁女童女子被行拘](https://s.weibo.com/weibo?q=%23%E5%9B%A0%E6%8A%A2%E7%8E%A9%E5%85%B7%E6%AE%B4%E6%89%932%E5%B2%81%E5%A5%B3%E7%AB%A5%E5%A5%B3%E5%AD%90%E8%A2%AB%E8%A1%8C%E6%8B%98%23) `340.3K 🔥` `+148%`
1. [卧床35年女子顺利产下健康宝宝](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%8A35%E5%B9%B4%E5%A5%B3%E5%AD%90%E9%A1%BA%E5%88%A9%E4%BA%A7%E4%B8%8B%E5%81%A5%E5%BA%B7%E5%AE%9D%E5%AE%9D%23) `193.8K 🔥` `+27%`
1. [早期心血管病可能反映在脸上 (Early cardiovascular disease may be reflected on the face)](https://s.weibo.com/weibo?q=%23%E6%97%A9%E6%9C%9F%E5%BF%83%E8%A1%80%E7%AE%A1%E7%97%85%E5%8F%AF%E8%83%BD%E5%8F%8D%E6%98%A0%E5%9C%A8%E8%84%B8%E4%B8%8A%23) `1.0M 🔥`
1. [内存条降价 (Memory module price reduction)](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%AD%98%E6%9D%A1%E9%99%8D%E4%BB%B7%23) `763.5K 🔥`
1. [留几手发文暗讽被全网炮轰](https://s.weibo.com/weibo?q=%23%E7%95%99%E5%87%A0%E6%89%8B%E5%8F%91%E6%96%87%E6%9A%97%E8%AE%BD%E8%A2%AB%E5%85%A8%E7%BD%91%E7%82%AE%E8%BD%B0%23) `190.4K 🔥`
1. [女子买24元卤菜顺走40块钱大肠头 (Woman buys braised vegetables for 24 yuan and walks away with large intestines for 40 yuan)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%B024%E5%85%83%E5%8D%A4%E8%8F%9C%E9%A1%BA%E8%B5%B040%E5%9D%97%E9%92%B1%E5%A4%A7%E8%82%A0%E5%A4%B4%23) `135.5K 🔥`
1. [王一博 乐华](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%20%E4%B9%90%E5%8D%8E%23) `134.5K 🔥`
1. [韩国女子怒抢中国游客手机](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E5%A5%B3%E5%AD%90%E6%80%92%E6%8A%A2%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E6%89%8B%E6%9C%BA%23) `121.6K 🔥`
1. [2026最吸金的星座](https://s.weibo.com/weibo?q=%232026%E6%9C%80%E5%90%B8%E9%87%91%E7%9A%84%E6%98%9F%E5%BA%A7%23) `102.6K 🔥`
1. [王俊凯 演唱会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%20%E6%BC%94%E5%94%B1%E4%BC%9A%23) `100.4K 🔥`
1. [颜如晶曾找过25个教练减重均失败](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%A6%82%E6%99%B6%E6%9B%BE%E6%89%BE%E8%BF%8725%E4%B8%AA%E6%95%99%E7%BB%83%E5%87%8F%E9%87%8D%E5%9D%87%E5%A4%B1%E8%B4%A5%23) `86.1K 🔥`
1. [王俊凯卡点521](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E5%8D%A1%E7%82%B9521%23) `77.0K 🔥`
1. [黄晓明回应没考上博士](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E5%9B%9E%E5%BA%94%E6%B2%A1%E8%80%83%E4%B8%8A%E5%8D%9A%E5%A3%AB%23) `73.2K 🔥`
1. [中国无人飞枪曝光](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%97%A0%E4%BA%BA%E9%A3%9E%E6%9E%AA%E6%9B%9D%E5%85%89%23) `338.4K 🔥` `-43%`
1. [谢征樊长玉被窝戏删掉了](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E8%A2%AB%E7%AA%9D%E6%88%8F%E5%88%A0%E6%8E%89%E4%BA%86%23) `333.6K 🔥` `-44%`
1. [林俊杰称自己生命的沙漏加速了 (JJ Lin said the hourglass of his life has accelerated)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E7%A7%B0%E8%87%AA%E5%B7%B1%E7%94%9F%E5%91%BD%E7%9A%84%E6%B2%99%E6%BC%8F%E5%8A%A0%E9%80%9F%E4%BA%86%23) `201.0K 🔥` `-49%`
1. [43岁不健身和61岁健身的区别](https://s.weibo.com/weibo?q=%2343%E5%B2%81%E4%B8%8D%E5%81%A5%E8%BA%AB%E5%92%8C61%E5%B2%81%E5%81%A5%E8%BA%AB%E7%9A%84%E5%8C%BA%E5%88%AB%23) `199.6K 🔥` `-22%`
1. [田曦薇张凌赫 二搭 (Tian Xiwei Zhang Linghe second partner)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E4%BA%8C%E6%90%AD%23) `193.1K 🔥` `-68%`
1. [逐玉大结局 (Chasing Jade Finale)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%A4%A7%E7%BB%93%E5%B1%80%23) `130.7K 🔥` `-48%`
1. [我们一直把苹果放反了](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E4%B8%80%E7%9B%B4%E6%8A%8A%E8%8B%B9%E6%9E%9C%E6%94%BE%E5%8F%8D%E4%BA%86%23) `102.5K 🔥` `-37%`
1. [孟子义腰比名牌细](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E8%85%B0%E6%AF%94%E5%90%8D%E7%89%8C%E7%BB%86%23) `99.9K 🔥` `-35%`
1. [谢征樊长玉生了两个孩子](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E7%94%9F%E4%BA%86%E4%B8%A4%E4%B8%AA%E5%AD%A9%E5%AD%90%23) `89.8K 🔥` `-85%`
1. [董子健 我以前也是东北女婿](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AD%90%E5%81%A5%20%E6%88%91%E4%BB%A5%E5%89%8D%E4%B9%9F%E6%98%AF%E4%B8%9C%E5%8C%97%E5%A5%B3%E5%A9%BF%23) `85.8K 🔥` `-50%`
1. [郭敬明需要避谶](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%95%AC%E6%98%8E%E9%9C%80%E8%A6%81%E9%81%BF%E8%B0%B6%23) `69.5K 🔥` `-59%`

Updated at 2026-03-26 22:11:34

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
