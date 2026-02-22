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

1. [淀粉肠进入瑜伽裤时代 (Starch intestine enters the era of yoga pants)](https://s.weibo.com/weibo?q=%23%E6%B7%80%E7%B2%89%E8%82%A0%E8%BF%9B%E5%85%A5%E7%91%9C%E4%BC%BD%E8%A3%A4%E6%97%B6%E4%BB%A3%23) `591.0K 🔥` `NEW`
1. [雷军假期滑了6天雪](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%81%87%E6%9C%9F%E6%BB%91%E4%BA%866%E5%A4%A9%E9%9B%AA%23) `318.1K 🔥` `NEW`
1. [谷爱凌压轴之战延期又延期](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%8E%8B%E8%BD%B4%E4%B9%8B%E6%88%98%E5%BB%B6%E6%9C%9F%E5%8F%88%E5%BB%B6%E6%9C%9F%23) `297.8K 🔥` `NEW`
1. [宋雨琦差点漏接韩国音著协电话](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E5%B7%AE%E7%82%B9%E6%BC%8F%E6%8E%A5%E9%9F%A9%E5%9B%BD%E9%9F%B3%E8%91%97%E5%8D%8F%E7%94%B5%E8%AF%9D%23) `216.9K 🔥` `NEW`
1. [长大后全球物价下降100倍](https://s.weibo.com/weibo?q=%23%E9%95%BF%E5%A4%A7%E5%90%8E%E5%85%A8%E7%90%83%E7%89%A9%E4%BB%B7%E4%B8%8B%E9%99%8D100%E5%80%8D%23) `193.8K 🔥` `NEW`
1. [钓帝黑大爷从生病到去世仅5天](https://s.weibo.com/weibo?q=%23%E9%92%93%E5%B8%9D%E9%BB%91%E5%A4%A7%E7%88%B7%E4%BB%8E%E7%94%9F%E7%97%85%E5%88%B0%E5%8E%BB%E4%B8%96%E4%BB%855%E5%A4%A9%23) `138.4K 🔥` `NEW`
1. [唐宫奇案道歉名单](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%AE%AB%E5%A5%87%E6%A1%88%E9%81%93%E6%AD%89%E5%90%8D%E5%8D%95%23) `135.9K 🔥` `NEW`
1. [徐梦桃父亲回应女儿女婿齐夺冠](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E7%88%B6%E4%BA%B2%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%84%BF%E5%A5%B3%E5%A9%BF%E9%BD%90%E5%A4%BA%E5%86%A0%23) `109.0K 🔥` `NEW`
1. [星河入梦主创哽咽求排片](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%E4%B8%BB%E5%88%9B%E5%93%BD%E5%92%BD%E6%B1%82%E6%8E%92%E7%89%87%23) `97.8K 🔥` `NEW`
1. [北京奥运会的金镶玉奖牌有多权威](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%A5%A5%E8%BF%90%E4%BC%9A%E7%9A%84%E9%87%91%E9%95%B6%E7%8E%89%E5%A5%96%E7%89%8C%E6%9C%89%E5%A4%9A%E6%9D%83%E5%A8%81%23) `97.6K 🔥` `NEW`
1. [鲍鱼价格被中国打下来了 (Abalone prices have been driven down by China)](https://s.weibo.com/weibo?q=%23%E9%B2%8D%E9%B1%BC%E4%BB%B7%E6%A0%BC%E8%A2%AB%E4%B8%AD%E5%9B%BD%E6%89%93%E4%B8%8B%E6%9D%A5%E4%BA%86%23) `87.1K 🔥` `NEW`
1. [空气炸锅烤奶茶](https://s.weibo.com/weibo?q=%23%E7%A9%BA%E6%B0%94%E7%82%B8%E9%94%85%E7%83%A4%E5%A5%B6%E8%8C%B6%23) `69.8K 🔥` `NEW`
1. [李柯以称不认为自己是短剧一姐](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%9F%AF%E4%BB%A5%E7%A7%B0%E4%B8%8D%E8%AE%A4%E4%B8%BA%E8%87%AA%E5%B7%B1%E6%98%AF%E7%9F%AD%E5%89%A7%E4%B8%80%E5%A7%90%23) `69.2K 🔥` `NEW`
1. [和十年闺蜜断交后对友谊的思考](https://s.weibo.com/weibo?q=%23%E5%92%8C%E5%8D%81%E5%B9%B4%E9%97%BA%E8%9C%9C%E6%96%AD%E4%BA%A4%E5%90%8E%E5%AF%B9%E5%8F%8B%E8%B0%8A%E7%9A%84%E6%80%9D%E8%80%83%23) `65.5K 🔥` `NEW`
1. [萨摩耶从白面馒头逐渐化为狗形](https://s.weibo.com/weibo?q=%23%E8%90%A8%E6%91%A9%E8%80%B6%E4%BB%8E%E7%99%BD%E9%9D%A2%E9%A6%92%E5%A4%B4%E9%80%90%E6%B8%90%E5%8C%96%E4%B8%BA%E7%8B%97%E5%BD%A2%23) `65.5K 🔥` `NEW`
1. [高端的食材只需要换个名字](https://s.weibo.com/weibo?q=%23%E9%AB%98%E7%AB%AF%E7%9A%84%E9%A3%9F%E6%9D%90%E5%8F%AA%E9%9C%80%E8%A6%81%E6%8D%A2%E4%B8%AA%E5%90%8D%E5%AD%97%23) `63.2K 🔥` `NEW`
1. [回家过年不能呆久了](https://s.weibo.com/weibo?q=%23%E5%9B%9E%E5%AE%B6%E8%BF%87%E5%B9%B4%E4%B8%8D%E8%83%BD%E5%91%86%E4%B9%85%E4%BA%86%23) `62.7K 🔥` `NEW`
1. [若决赛取消谷爱凌将无缘奖牌 (If the final is canceled, Gu Ailing will miss the medal)](https://s.weibo.com/weibo?q=%23%E8%8B%A5%E5%86%B3%E8%B5%9B%E5%8F%96%E6%B6%88%E8%B0%B7%E7%88%B1%E5%87%8C%E5%B0%86%E6%97%A0%E7%BC%98%E5%A5%96%E7%89%8C%23) `1.1M 🔥` `+38%`
1. [陆虎15分钟卖出一套房 (Land Rover sells a house in 15 minutes)](https://s.weibo.com/weibo?q=%23%E9%99%86%E8%99%8E15%E5%88%86%E9%92%9F%E5%8D%96%E5%87%BA%E4%B8%80%E5%A5%97%E6%88%BF%23) `455.1K 🔥` `+102%`
1. [水煮肉片吃出纸店家回怼你咋呼啥](https://s.weibo.com/weibo?q=%23%E6%B0%B4%E7%85%AE%E8%82%89%E7%89%87%E5%90%83%E5%87%BA%E7%BA%B8%E5%BA%97%E5%AE%B6%E5%9B%9E%E6%80%BC%E4%BD%A0%E5%92%8B%E5%91%BC%E5%95%A5%23) `221.6K 🔥` `+45%`
1. [张凯毅生娃](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%AF%E6%AF%85%E7%94%9F%E5%A8%83%23) `220.9K 🔥` `+29%`
1. [特朗普开始报复了 (Trump is taking revenge)](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E5%BC%80%E5%A7%8B%E6%8A%A5%E5%A4%8D%E4%BA%86%23) `161.0K 🔥` `+22%`
1. [哈尔滨冰雪大世界退票后下届免费看](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%B0%94%E6%BB%A8%E5%86%B0%E9%9B%AA%E5%A4%A7%E4%B8%96%E7%95%8C%E9%80%80%E7%A5%A8%E5%90%8E%E4%B8%8B%E5%B1%8A%E5%85%8D%E8%B4%B9%E7%9C%8B%23) `135.9K 🔥` `+33%`
1. [官方通报男孩景区游玩时突发坠崖 (Officials reported that a boy suddenly fell off a cliff while visiting a scenic spot.)](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%E7%94%B7%E5%AD%A9%E6%99%AF%E5%8C%BA%E6%B8%B8%E7%8E%A9%E6%97%B6%E7%AA%81%E5%8F%91%E5%9D%A0%E5%B4%96%23) `117.3K 🔥` `+61%`
1. [春运前20天预计流动量超50亿人次 (The number of people traveling during the first 20 days of Spring Festival travel is expected to exceed 5 billion)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%BF%90%E5%89%8D20%E5%A4%A9%E9%A2%84%E8%AE%A1%E6%B5%81%E5%8A%A8%E9%87%8F%E8%B6%8550%E4%BA%BF%E4%BA%BA%E6%AC%A1%23) `633.8K 🔥`
1. [高速堵车](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%A0%B5%E8%BD%A6%23) `236.1K 🔥`
1. [姥姥说上次吃还是在旧社会](https://s.weibo.com/weibo?q=%23%E5%A7%A5%E5%A7%A5%E8%AF%B4%E4%B8%8A%E6%AC%A1%E5%90%83%E8%BF%98%E6%98%AF%E5%9C%A8%E6%97%A7%E7%A4%BE%E4%BC%9A%23) `226.2K 🔥`
1. [美国11岁男孩被没收游戏机爆头养父](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD11%E5%B2%81%E7%94%B7%E5%AD%A9%E8%A2%AB%E6%B2%A1%E6%94%B6%E6%B8%B8%E6%88%8F%E6%9C%BA%E7%88%86%E5%A4%B4%E5%85%BB%E7%88%B6%23) `216.7K 🔥`
1. [杨洋手部骨折](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E6%89%8B%E9%83%A8%E9%AA%A8%E6%8A%98%23) `172.4K 🔥`
1. [齐思钧回应分手 (Qi Sijun responded to the breakup)](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%80%9D%E9%92%A7%E5%9B%9E%E5%BA%94%E5%88%86%E6%89%8B%23) `169.4K 🔥`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `146.6K 🔥`
1. [将门毒后用程少商的个人曲](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%E7%94%A8%E7%A8%8B%E5%B0%91%E5%95%86%E7%9A%84%E4%B8%AA%E4%BA%BA%E6%9B%B2%23) `111.9K 🔥`
1. [小伙刚还清车贷宝马几乎撞报废 (The guy just paid off his car loan and his BMW was almost totaled)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%88%9A%E8%BF%98%E6%B8%85%E8%BD%A6%E8%B4%B7%E5%AE%9D%E9%A9%AC%E5%87%A0%E4%B9%8E%E6%92%9E%E6%8A%A5%E5%BA%9F%23) `74.5K 🔥`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `66.4K 🔥`
1. [原来小狗也有门禁啊](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%B0%8F%E7%8B%97%E4%B9%9F%E6%9C%89%E9%97%A8%E7%A6%81%E5%95%8A%23) `63.1K 🔥`
1. [沈妙原型 王艳](https://s.weibo.com/weibo?q=%23%E6%B2%88%E5%A6%99%E5%8E%9F%E5%9E%8B%20%E7%8E%8B%E8%89%B3%23) `757.0K 🔥` `-31%`
1. [厚本进组不让江山](https://s.weibo.com/weibo?q=%23%E5%8E%9A%E6%9C%AC%E8%BF%9B%E7%BB%84%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%23) `204.7K 🔥` `-55%`
1. [林孝埈再次道歉 (Lin Xiaojuan apologizes again)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E5%86%8D%E6%AC%A1%E9%81%93%E6%AD%89%23) `144.3K 🔥` `-40%`
1. [陈飞宇孙千新剧首播口碑](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E5%AD%99%E5%8D%83%E6%96%B0%E5%89%A7%E9%A6%96%E6%92%AD%E5%8F%A3%E7%A2%91%23) `132.6K 🔥` `-26%`
1. [杨洋回应骨折](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%9B%9E%E5%BA%94%E9%AA%A8%E6%8A%98%23) `99.0K 🔥` `-24%`
1. [我家那小子开播](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%E5%BC%80%E6%92%AD%23) `98.3K 🔥` `-23%`
1. [泰国官方通报清迈72只老虎死亡](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%E6%B8%85%E8%BF%8872%E5%8F%AA%E8%80%81%E8%99%8E%E6%AD%BB%E4%BA%A1%23) `98.1K 🔥` `-48%`
1. [家里有三个女儿出门有多难](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%87%8C%E6%9C%89%E4%B8%89%E4%B8%AA%E5%A5%B3%E5%84%BF%E5%87%BA%E9%97%A8%E6%9C%89%E5%A4%9A%E9%9A%BE%23) `95.8K 🔥` `-24%`
1. [王鹤棣宋茜恳求观众多给一些机会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AE%8B%E8%8C%9C%E6%81%B3%E6%B1%82%E8%A7%82%E4%BC%97%E5%A4%9A%E7%BB%99%E4%B8%80%E4%BA%9B%E6%9C%BA%E4%BC%9A%23) `91.9K 🔥` `-30%`
1. [镖人口碑升至第一](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E5%8F%A3%E7%A2%91%E5%8D%87%E8%87%B3%E7%AC%AC%E4%B8%80%23) `88.8K 🔥` `-34%`
1. [带半瓶茅台乘火车被拦欲当场喝完](https://s.weibo.com/weibo?q=%23%E5%B8%A6%E5%8D%8A%E7%93%B6%E8%8C%85%E5%8F%B0%E4%B9%98%E7%81%AB%E8%BD%A6%E8%A2%AB%E6%8B%A6%E6%AC%B2%E5%BD%93%E5%9C%BA%E5%96%9D%E5%AE%8C%23) `79.5K 🔥` `-38%`
1. [香港宏福苑7座受灾楼宇将拆除](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E5%AE%8F%E7%A6%8F%E8%8B%917%E5%BA%A7%E5%8F%97%E7%81%BE%E6%A5%BC%E5%AE%87%E5%B0%86%E6%8B%86%E9%99%A4%23) `74.9K 🔥` `-71%`
1. [徐梦桃的金牌有划痕了 (Xu Mengtao’s gold medal is scratched)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E7%9A%84%E9%87%91%E7%89%8C%E6%9C%89%E5%88%92%E7%97%95%E4%BA%86%23) `74.7K 🔥` `-23%`
1. [飞驰人生3票房20亿彩蛋 (Flying Life 3 has a box office of 2 billion easter eggs)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E7%A5%A8%E6%88%BF20%E4%BA%BF%E5%BD%A9%E8%9B%8B%23) `70.2K 🔥` `-30%`
1. [突然意识到经常习惯性霸凌自己](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E6%84%8F%E8%AF%86%E5%88%B0%E7%BB%8F%E5%B8%B8%E4%B9%A0%E6%83%AF%E6%80%A7%E9%9C%B8%E5%87%8C%E8%87%AA%E5%B7%B1%23) `66.7K 🔥` `-56%`

Updated at 2026-02-22 15:00:59

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
