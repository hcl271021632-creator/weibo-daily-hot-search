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

1. [女子U型场地决赛 (Women's halfpipe final)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90U%E5%9E%8B%E5%9C%BA%E5%9C%B0%E5%86%B3%E8%B5%9B%23) `760.3K 🔥` `NEW`
1. [台湾男子在缅甸妙瓦底被殴打拔指甲](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E7%94%B7%E5%AD%90%E5%9C%A8%E7%BC%85%E7%94%B8%E5%A6%99%E7%93%A6%E5%BA%95%E8%A2%AB%E6%AE%B4%E6%89%93%E6%8B%94%E6%8C%87%E7%94%B2%23) `110.3K 🔥` `NEW`
1. [孟子义李昀锐 四搭](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%20%E5%9B%9B%E6%90%AD%23) `110.3K 🔥` `NEW`
1. [舅舅兑1元零钱给每个外甥发500](https://s.weibo.com/weibo?q=%23%E8%88%85%E8%88%85%E5%85%911%E5%85%83%E9%9B%B6%E9%92%B1%E7%BB%99%E6%AF%8F%E4%B8%AA%E5%A4%96%E7%94%A5%E5%8F%91500%23) `110.3K 🔥` `NEW`
1. [徐梦桃说太嘚瑟了结果金牌被刮花](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E8%AF%B4%E5%A4%AA%E5%98%9A%E7%91%9F%E4%BA%86%E7%BB%93%E6%9E%9C%E9%87%91%E7%89%8C%E8%A2%AB%E5%88%AE%E8%8A%B1%23) `87.8K 🔥` `NEW`
1. [惊蛰无声](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `83.6K 🔥` `NEW`
1. [福州偶遇陈赫张子萱](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%B7%9E%E5%81%B6%E9%81%87%E9%99%88%E8%B5%AB%E5%BC%A0%E5%AD%90%E8%90%B1%23) `73.8K 🔥` `NEW`
1. [复工状态](https://s.weibo.com/weibo?q=%23%E5%A4%8D%E5%B7%A5%E7%8A%B6%E6%80%81%23) `70.4K 🔥` `NEW`
1. [飞驰人生](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F%23) `67.4K 🔥` `NEW`
1. [徐梦桃回应团体丢金](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E5%9B%9E%E5%BA%94%E5%9B%A2%E4%BD%93%E4%B8%A2%E9%87%91%23) `64.7K 🔥` `NEW`
1. [曝票房15亿是镖人的回本线 (It is revealed that the box office of 1.5 billion is the return line for escorts)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%A5%A8%E6%88%BF15%E4%BA%BF%E6%98%AF%E9%95%96%E4%BA%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E7%BA%BF%23) `1.1M 🔥` `+38%`
1. [孟子义沈妙路透 (Mencius Shen Miao Reuters)](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%B2%88%E5%A6%99%E8%B7%AF%E9%80%8F%23) `269.3K 🔥` `+104%`
1. [不要在吃喝方面拿捏人](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%A6%81%E5%9C%A8%E5%90%83%E5%96%9D%E6%96%B9%E9%9D%A2%E6%8B%BF%E6%8D%8F%E4%BA%BA%23) `228.2K 🔥` `+190%`
1. [王婆说媒炫富男子实际年龄40岁](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A9%86%E8%AF%B4%E5%AA%92%E7%82%AB%E5%AF%8C%E7%94%B7%E5%AD%90%E5%AE%9E%E9%99%85%E5%B9%B4%E9%BE%8440%E5%B2%81%23) `170.0K 🔥` `+42%`
1. [邢菲录个节目看清人间冷暖](https://s.weibo.com/weibo?q=%23%E9%82%A2%E8%8F%B2%E5%BD%95%E4%B8%AA%E8%8A%82%E7%9B%AE%E7%9C%8B%E6%B8%85%E4%BA%BA%E9%97%B4%E5%86%B7%E6%9A%96%23) `110.3K 🔥` `+40%`
1. [热气腾腾的中国年 (Steamy Chinese New Year)](https://s.weibo.com/weibo?q=%23%E7%83%AD%E6%B0%94%E8%85%BE%E8%85%BE%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%B9%B4%23) `601.3K 🔥`
1. [杨幂演技](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%BC%94%E6%8A%80%23) `363.6K 🔥`
1. [保鲜膜裹食物加热会致癌系谣言](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E9%B2%9C%E8%86%9C%E8%A3%B9%E9%A3%9F%E7%89%A9%E5%8A%A0%E7%83%AD%E4%BC%9A%E8%87%B4%E7%99%8C%E7%B3%BB%E8%B0%A3%E8%A8%80%23) `278.5K 🔥`
1. [谷爱凌决赛正常进行 (Gu Ailing’s final proceeds as normal)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%86%B3%E8%B5%9B%E6%AD%A3%E5%B8%B8%E8%BF%9B%E8%A1%8C%23) `228.9K 🔥`
1. [虹猫蓝兔七侠传回来了](https://s.weibo.com/weibo?q=%23%E8%99%B9%E7%8C%AB%E8%93%9D%E5%85%94%E4%B8%83%E4%BE%A0%E4%BC%A0%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `199.1K 🔥`
1. [彩民随手扔掉千万彩票2天才发现](https://s.weibo.com/weibo?q=%23%E5%BD%A9%E6%B0%91%E9%9A%8F%E6%89%8B%E6%89%94%E6%8E%89%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A82%E5%A4%A9%E6%89%8D%E5%8F%91%E7%8E%B0%23) `192.3K 🔥`
1. [月薪多少才愿意过这样的人生](https://s.weibo.com/weibo?q=%23%E6%9C%88%E8%96%AA%E5%A4%9A%E5%B0%91%E6%89%8D%E6%84%BF%E6%84%8F%E8%BF%87%E8%BF%99%E6%A0%B7%E7%9A%84%E4%BA%BA%E7%94%9F%23) `178.5K 🔥`
1. [输液过敏死亡独生女父母有残疾](https://s.weibo.com/weibo?q=%23%E8%BE%93%E6%B6%B2%E8%BF%87%E6%95%8F%E6%AD%BB%E4%BA%A1%E7%8B%AC%E7%94%9F%E5%A5%B3%E7%88%B6%E6%AF%8D%E6%9C%89%E6%AE%8B%E7%96%BE%23) `154.4K 🔥`
1. [官方回应连云港一公职人员炫富 (Official response to a public official in Lianyungang showing off his wealth)](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E5%9B%9E%E5%BA%94%E8%BF%9E%E4%BA%91%E6%B8%AF%E4%B8%80%E5%85%AC%E8%81%8C%E4%BA%BA%E5%91%98%E7%82%AB%E5%AF%8C%23) `140.5K 🔥`
1. [飞驰人生3豆瓣评分降至7.4](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E8%B1%86%E7%93%A3%E8%AF%84%E5%88%86%E9%99%8D%E8%87%B37.4%23) `135.1K 🔥`
1. [厚本进组不让江山 (Joining the group with thick capital and refusing to give up power)](https://s.weibo.com/weibo?q=%23%E5%8E%9A%E6%9C%AC%E8%BF%9B%E7%BB%84%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%23) `110.3K 🔥`
1. [熊孩子扔螺帽致大熊猫馆紧急收园](https://s.weibo.com/weibo?q=%23%E7%86%8A%E5%AD%A9%E5%AD%90%E6%89%94%E8%9E%BA%E5%B8%BD%E8%87%B4%E5%A4%A7%E7%86%8A%E7%8C%AB%E9%A6%86%E7%B4%A7%E6%80%A5%E6%94%B6%E5%9B%AD%23) `110.3K 🔥`
1. [U池决赛现场天公作美](https://s.weibo.com/weibo?q=%23U%E6%B1%A0%E5%86%B3%E8%B5%9B%E7%8E%B0%E5%9C%BA%E5%A4%A9%E5%85%AC%E4%BD%9C%E7%BE%8E%23) `110.3K 🔥`
1. [在家喝杯咖啡都被教育](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%AE%B6%E5%96%9D%E6%9D%AF%E5%92%96%E5%95%A1%E9%83%BD%E8%A2%AB%E6%95%99%E8%82%B2%23) `110.3K 🔥`
1. [星河入梦上映6天票房仅破7000万](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%E4%B8%8A%E6%98%A06%E5%A4%A9%E7%A5%A8%E6%88%BF%E4%BB%85%E7%A0%B47000%E4%B8%87%23) `110.3K 🔥`
1. [申有娜零食很忙采购中](https://s.weibo.com/weibo?q=%23%E7%94%B3%E6%9C%89%E5%A8%9C%E9%9B%B6%E9%A3%9F%E5%BE%88%E5%BF%99%E9%87%87%E8%B4%AD%E4%B8%AD%23) `110.3K 🔥`
1. [伊朗 (Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `90.9K 🔥`
1. [高速堵车 (Highway traffic jam)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%A0%B5%E8%BD%A6%23) `89.2K 🔥`
1. [运动一定要30分钟以上才能减肥吗](https://s.weibo.com/weibo?q=%23%E8%BF%90%E5%8A%A8%E4%B8%80%E5%AE%9A%E8%A6%8130%E5%88%86%E9%92%9F%E4%BB%A5%E4%B8%8A%E6%89%8D%E8%83%BD%E5%87%8F%E8%82%A5%E5%90%97%23) `83.6K 🔥`
1. [曝iPhoneFold与18Pro7月量产](https://s.weibo.com/weibo?q=%23%E6%9B%9DiPhoneFold%E4%B8%8E18Pro7%E6%9C%88%E9%87%8F%E4%BA%A7%23) `77.9K 🔥`
1. [齐思钧回应分手 (Qi Sijun responded to the breakup)](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%80%9D%E9%92%A7%E5%9B%9E%E5%BA%94%E5%88%86%E6%89%8B%23) `67.8K 🔥`
1. [大理初四订房订到医院 (Book a room at the hospital on the fourth day of the Lunar New Year in Dali)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%90%86%E5%88%9D%E5%9B%9B%E8%AE%A2%E6%88%BF%E8%AE%A2%E5%88%B0%E5%8C%BB%E9%99%A2%23) `290.7K 🔥` `-73%`
1. [淀粉肠进入瑜伽裤时代 (Starch intestine enters the era of yoga pants)](https://s.weibo.com/weibo?q=%23%E6%B7%80%E7%B2%89%E8%82%A0%E8%BF%9B%E5%85%A5%E7%91%9C%E4%BC%BD%E8%A3%A4%E6%97%B6%E4%BB%A3%23) `283.7K 🔥` `-58%`
1. [初六把我回收了吧](https://s.weibo.com/weibo?q=%23%E5%88%9D%E5%85%AD%E6%8A%8A%E6%88%91%E5%9B%9E%E6%94%B6%E4%BA%86%E5%90%A7%23) `141.6K 🔥` `-34%`
1. [大年初五8岁男童虎跳峡坠崖遇难 (An 8-year-old boy died after falling off a cliff in Tiger Leaping Gorge on the fifth day of the Lunar New Year)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%948%E5%B2%81%E7%94%B7%E7%AB%A5%E8%99%8E%E8%B7%B3%E5%B3%A1%E5%9D%A0%E5%B4%96%E9%81%87%E9%9A%BE%23) `110.3K 🔥` `-33%`
1. [沈妙原型 王艳 (Shen Miao Prototype Wang Yan)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E5%A6%99%E5%8E%9F%E5%9E%8B%20%E7%8E%8B%E8%89%B3%23) `110.3K 🔥` `-33%`
1. [张凯毅生娃](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%AF%E6%AF%85%E7%94%9F%E5%A8%83%23) `110.3K 🔥` `-33%`
1. [若决赛取消谷爱凌将无缘奖牌 (If the final is canceled, Gu Ailing will miss the medal)](https://s.weibo.com/weibo?q=%23%E8%8B%A5%E5%86%B3%E8%B5%9B%E5%8F%96%E6%B6%88%E8%B0%B7%E7%88%B1%E5%87%8C%E5%B0%86%E6%97%A0%E7%BC%98%E5%A5%96%E7%89%8C%23) `110.3K 🔥` `-25%`
1. [宋雨琦差点漏接韩国音著协电话](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E5%B7%AE%E7%82%B9%E6%BC%8F%E6%8E%A5%E9%9F%A9%E5%9B%BD%E9%9F%B3%E8%91%97%E5%8D%8F%E7%94%B5%E8%AF%9D%23) `110.3K 🔥` `-33%`
1. [雷军假期滑了6天雪 (Lei Jun skied for 6 days during the holiday)](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%81%87%E6%9C%9F%E6%BB%91%E4%BA%866%E5%A4%A9%E9%9B%AA%23) `96.0K 🔥` `-42%`
1. [徐明浩韩语说出中国春节](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%98%8E%E6%B5%A9%E9%9F%A9%E8%AF%AD%E8%AF%B4%E5%87%BA%E4%B8%AD%E5%9B%BD%E6%98%A5%E8%8A%82%23) `94.8K 🔥` `-42%`
1. [朴志训吃苹果减肥瘦了30斤](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E5%BF%97%E8%AE%AD%E5%90%83%E8%8B%B9%E6%9E%9C%E5%87%8F%E8%82%A5%E7%98%A6%E4%BA%8630%E6%96%A4%23) `92.9K 🔥` `-40%`
1. [湖南6名牺牲消防员名字公布 (Names of 6 firefighters who died in Hunan announced)](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%976%E5%90%8D%E7%89%BA%E7%89%B2%E6%B6%88%E9%98%B2%E5%91%98%E5%90%8D%E5%AD%97%E5%85%AC%E5%B8%83%23) `88.1K 🔥` `-47%`
1. [刘耀文唱了鹿晗黄子韬的敏感](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%80%80%E6%96%87%E5%94%B1%E4%BA%86%E9%B9%BF%E6%99%97%E9%BB%84%E5%AD%90%E9%9F%AC%E7%9A%84%E6%95%8F%E6%84%9F%23) `80.4K 🔥` `-28%`
1. [陆虎15分钟卖出一套房 (Land Rover sells a house in 15 minutes)](https://s.weibo.com/weibo?q=%23%E9%99%86%E8%99%8E15%E5%88%86%E9%92%9F%E5%8D%96%E5%87%BA%E4%B8%80%E5%A5%97%E6%88%BF%23) `73.3K 🔥` `-56%`
1. [美国11岁男孩被没收游戏机爆头养父](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD11%E5%B2%81%E7%94%B7%E5%AD%A9%E8%A2%AB%E6%B2%A1%E6%94%B6%E6%B8%B8%E6%88%8F%E6%9C%BA%E7%88%86%E5%A4%B4%E5%85%BB%E7%88%B6%23) `63.4K 🔥` `-24%`

Updated at 2026-02-22 17:49:03

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
