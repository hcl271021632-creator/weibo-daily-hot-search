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

1. [人生去留 (Stay or go in life)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%94%9F%E5%8E%BB%E7%95%99%23) `199.9K 🔥` `NEW`
1. [谷爱凌第一滑失误](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E7%AC%AC%E4%B8%80%E6%BB%91%E5%A4%B1%E8%AF%AF%23) `177.2K 🔥` `NEW`
1. [钓帝安大爷走得突然儿子没听上遗言](https://s.weibo.com/weibo?q=%23%E9%92%93%E5%B8%9D%E5%AE%89%E5%A4%A7%E7%88%B7%E8%B5%B0%E5%BE%97%E7%AA%81%E7%84%B6%E5%84%BF%E5%AD%90%E6%B2%A1%E5%90%AC%E4%B8%8A%E9%81%97%E8%A8%80%23) `110.8K 🔥` `NEW`
1. [韩国队抗议米兰冬奥至少4次印错国旗](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E9%98%9F%E6%8A%97%E8%AE%AE%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E8%87%B3%E5%B0%914%E6%AC%A1%E5%8D%B0%E9%94%99%E5%9B%BD%E6%97%97%23) `99.4K 🔥` `NEW`
1. [王鹤棣问敏感有鹿晗纯享版吗](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E9%97%AE%E6%95%8F%E6%84%9F%E6%9C%89%E9%B9%BF%E6%99%97%E7%BA%AF%E4%BA%AB%E7%89%88%E5%90%97%23) `90.0K 🔥` `NEW`
1. [生命树一部剧带火一座城](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%E4%B8%80%E9%83%A8%E5%89%A7%E5%B8%A6%E7%81%AB%E4%B8%80%E5%BA%A7%E5%9F%8E%23) `83.2K 🔥` `NEW`
1. [我国成年人超重肥胖率已超过50%](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E6%88%90%E5%B9%B4%E4%BA%BA%E8%B6%85%E9%87%8D%E8%82%A5%E8%83%96%E7%8E%87%E5%B7%B2%E8%B6%85%E8%BF%8750%25%23) `79.0K 🔥` `NEW`
1. [昆明海埂大坝游客比海鸥多](https://s.weibo.com/weibo?q=%23%E6%98%86%E6%98%8E%E6%B5%B7%E5%9F%82%E5%A4%A7%E5%9D%9D%E6%B8%B8%E5%AE%A2%E6%AF%94%E6%B5%B7%E9%B8%A5%E5%A4%9A%23) `78.9K 🔥` `NEW`
1. [医生眼中不靠谱的避孕方式](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E7%9C%BC%E4%B8%AD%E4%B8%8D%E9%9D%A0%E8%B0%B1%E7%9A%84%E9%81%BF%E5%AD%95%E6%96%B9%E5%BC%8F%23) `78.9K 🔥` `NEW`
1. [可恶的年兽竟敢冒充外孙女](https://s.weibo.com/weibo?q=%23%E5%8F%AF%E6%81%B6%E7%9A%84%E5%B9%B4%E5%85%BD%E7%AB%9F%E6%95%A2%E5%86%92%E5%85%85%E5%A4%96%E5%AD%99%E5%A5%B3%23) `74.6K 🔥` `NEW`
1. [OpenAI预计2030年收入破2800亿美元 (OpenAI expects revenue to top $280 billion in 2030)](https://s.weibo.com/weibo?q=%23OpenAI%E9%A2%84%E8%AE%A12030%E5%B9%B4%E6%94%B6%E5%85%A5%E7%A0%B42800%E4%BA%BF%E7%BE%8E%E5%85%83%23) `71.0K 🔥` `NEW`
1. [吃饭是一件很私密的事情](https://s.weibo.com/weibo?q=%23%E5%90%83%E9%A5%AD%E6%98%AF%E4%B8%80%E4%BB%B6%E5%BE%88%E7%A7%81%E5%AF%86%E7%9A%84%E4%BA%8B%E6%83%85%23) `69.5K 🔥` `NEW`
1. [女子U型场地决赛 (Women's halfpipe final)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90U%E5%9E%8B%E5%9C%BA%E5%9C%B0%E5%86%B3%E8%B5%9B%23) `1.2M 🔥` `+60%`
1. [台湾男子在缅甸妙瓦底被殴打拔指甲](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E7%94%B7%E5%AD%90%E5%9C%A8%E7%BC%85%E7%94%B8%E5%A6%99%E7%93%A6%E5%BA%95%E8%A2%AB%E6%AE%B4%E6%89%93%E6%8B%94%E6%8C%87%E7%94%B2%23) `159.4K 🔥` `+44%`
1. [福州偶遇陈赫张子萱](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%B7%9E%E5%81%B6%E9%81%87%E9%99%88%E8%B5%AB%E5%BC%A0%E5%AD%90%E8%90%B1%23) `110.4K 🔥` `+50%`
1. [曝票房15亿是镖人的回本线 (It is revealed that the box office of 1.5 billion is the return line for escorts)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%A5%A8%E6%88%BF15%E4%BA%BF%E6%98%AF%E9%95%96%E4%BA%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E7%BA%BF%23) `883.7K 🔥`
1. [热气腾腾的中国年 (Steamy Chinese New Year)](https://s.weibo.com/weibo?q=%23%E7%83%AD%E6%B0%94%E8%85%BE%E8%85%BE%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%B9%B4%23) `669.8K 🔥`
1. [杨幂演技](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%BC%94%E6%8A%80%23) `298.9K 🔥`
1. [不要在吃喝方面拿捏人](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%A6%81%E5%9C%A8%E5%90%83%E5%96%9D%E6%96%B9%E9%9D%A2%E6%8B%BF%E6%8D%8F%E4%BA%BA%23) `193.1K 🔥`
1. [虹猫蓝兔七侠传回来了](https://s.weibo.com/weibo?q=%23%E8%99%B9%E7%8C%AB%E8%93%9D%E5%85%94%E4%B8%83%E4%BE%A0%E4%BC%A0%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `181.6K 🔥`
1. [王婆说媒炫富男子实际年龄40岁](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A9%86%E8%AF%B4%E5%AA%92%E7%82%AB%E5%AF%8C%E7%94%B7%E5%AD%90%E5%AE%9E%E9%99%85%E5%B9%B4%E9%BE%8440%E5%B2%81%23) `172.7K 🔥`
1. [彩民随手扔掉千万彩票2天才发现](https://s.weibo.com/weibo?q=%23%E5%BD%A9%E6%B0%91%E9%9A%8F%E6%89%8B%E6%89%94%E6%8E%89%E5%8D%83%E4%B8%87%E5%BD%A9%E7%A5%A82%E5%A4%A9%E6%89%8D%E5%8F%91%E7%8E%B0%23) `170.3K 🔥`
1. [月薪多少才愿意过这样的人生](https://s.weibo.com/weibo?q=%23%E6%9C%88%E8%96%AA%E5%A4%9A%E5%B0%91%E6%89%8D%E6%84%BF%E6%84%8F%E8%BF%87%E8%BF%99%E6%A0%B7%E7%9A%84%E4%BA%BA%E7%94%9F%23) `162.4K 🔥`
1. [初六把我回收了吧 (Did you recycle me on the sixth day of the Lunar New Year?)](https://s.weibo.com/weibo?q=%23%E5%88%9D%E5%85%AD%E6%8A%8A%E6%88%91%E5%9B%9E%E6%94%B6%E4%BA%86%E5%90%A7%23) `150.9K 🔥`
1. [输液过敏死亡独生女父母有残疾](https://s.weibo.com/weibo?q=%23%E8%BE%93%E6%B6%B2%E8%BF%87%E6%95%8F%E6%AD%BB%E4%BA%A1%E7%8B%AC%E7%94%9F%E5%A5%B3%E7%88%B6%E6%AF%8D%E6%9C%89%E6%AE%8B%E7%96%BE%23) `139.7K 🔥`
1. [飞驰人生3豆瓣评分降至7.4](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E8%B1%86%E7%93%A3%E8%AF%84%E5%88%86%E9%99%8D%E8%87%B37.4%23) `135.0K 🔥`
1. [官方回应连云港一公职人员炫富 (Official response to a public official in Lianyungang showing off his wealth)](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E5%9B%9E%E5%BA%94%E8%BF%9E%E4%BA%91%E6%B8%AF%E4%B8%80%E5%85%AC%E8%81%8C%E4%BA%BA%E5%91%98%E7%82%AB%E5%AF%8C%23) `112.5K 🔥`
1. [孟子义李昀锐 四搭](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%20%E5%9B%9B%E6%90%AD%23) `110.7K 🔥`
1. [大年初五8岁男童虎跳峡坠崖遇难 (An 8-year-old boy died after falling off a cliff in Tiger Leaping Gorge on the fifth day of the Lunar New Year)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%948%E5%B2%81%E7%94%B7%E7%AB%A5%E8%99%8E%E8%B7%B3%E5%B3%A1%E5%9D%A0%E5%B4%96%E9%81%87%E9%9A%BE%23) `110.5K 🔥`
1. [沈妙原型 王艳 (Shen Miao Prototype Wang Yan)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E5%A6%99%E5%8E%9F%E5%9E%8B%20%E7%8E%8B%E8%89%B3%23) `110.3K 🔥`
1. [舅舅兑1元零钱给每个外甥发500](https://s.weibo.com/weibo?q=%23%E8%88%85%E8%88%85%E5%85%911%E5%85%83%E9%9B%B6%E9%92%B1%E7%BB%99%E6%AF%8F%E4%B8%AA%E5%A4%96%E7%94%A5%E5%8F%91500%23) `110.2K 🔥`
1. [张凯毅生娃](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%AF%E6%AF%85%E7%94%9F%E5%A8%83%23) `110.0K 🔥`
1. [申有娜零食很忙采购中](https://s.weibo.com/weibo?q=%23%E7%94%B3%E6%9C%89%E5%A8%9C%E9%9B%B6%E9%A3%9F%E5%BE%88%E5%BF%99%E9%87%87%E8%B4%AD%E4%B8%AD%23) `109.9K 🔥`
1. [在家喝杯咖啡都被教育](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%AE%B6%E5%96%9D%E6%9D%AF%E5%92%96%E5%95%A1%E9%83%BD%E8%A2%AB%E6%95%99%E8%82%B2%23) `109.8K 🔥`
1. [星河入梦上映6天票房仅破7000万](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%E4%B8%8A%E6%98%A06%E5%A4%A9%E7%A5%A8%E6%88%BF%E4%BB%85%E7%A0%B47000%E4%B8%87%23) `104.4K 🔥`
1. [厚本进组不让江山 (Joining the group with thick capital and refusing to give up power)](https://s.weibo.com/weibo?q=%23%E5%8E%9A%E6%9C%AC%E8%BF%9B%E7%BB%84%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%23) `92.1K 🔥`
1. [徐梦桃说太嘚瑟了结果金牌被刮花](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E8%AF%B4%E5%A4%AA%E5%98%9A%E7%91%9F%E4%BA%86%E7%BB%93%E6%9E%9C%E9%87%91%E7%89%8C%E8%A2%AB%E5%88%AE%E8%8A%B1%23) `85.8K 🔥`
1. [雷军假期滑了6天雪 (Lei Jun skied for 6 days during the holiday)](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%81%87%E6%9C%9F%E6%BB%91%E4%BA%866%E5%A4%A9%E9%9B%AA%23) `85.1K 🔥`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `84.7K 🔥`
1. [伊朗 (Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `84.3K 🔥`
1. [徐明浩韩语说出中国春节](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%98%8E%E6%B5%A9%E9%9F%A9%E8%AF%AD%E8%AF%B4%E5%87%BA%E4%B8%AD%E5%9B%BD%E6%98%A5%E8%8A%82%23) `80.2K 🔥`
1. [高速堵车 (Highway traffic jam)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%A0%B5%E8%BD%A6%23) `76.9K 🔥`
1. [朴志训吃苹果减肥瘦了30斤](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E5%BF%97%E8%AE%AD%E5%90%83%E8%8B%B9%E6%9E%9C%E5%87%8F%E8%82%A5%E7%98%A6%E4%BA%8630%E6%96%A4%23) `74.4K 🔥`
1. [飞驰人生](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F%23) `73.4K 🔥`
1. [大理初四订房订到医院 (Book a room at the hospital on the fourth day of the Lunar New Year in Dali)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%90%86%E5%88%9D%E5%9B%9B%E8%AE%A2%E6%88%BF%E8%AE%A2%E5%88%B0%E5%8C%BB%E9%99%A2%23) `210.5K 🔥` `-28%`
1. [淀粉肠进入瑜伽裤时代 (Starch intestine enters the era of yoga pants)](https://s.weibo.com/weibo?q=%23%E6%B7%80%E7%B2%89%E8%82%A0%E8%BF%9B%E5%85%A5%E7%91%9C%E4%BC%BD%E8%A3%A4%E6%97%B6%E4%BB%A3%23) `203.4K 🔥` `-28%`
1. [孟子义沈妙路透 (Mencius Shen Miao Reuters)](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%B2%88%E5%A6%99%E8%B7%AF%E9%80%8F%23) `199.7K 🔥` `-26%`
1. [谷爱凌决赛正常进行 (Gu Ailing’s final proceeds as normal)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%86%B3%E8%B5%9B%E6%AD%A3%E5%B8%B8%E8%BF%9B%E8%A1%8C%23) `110.8K 🔥` `-52%`
1. [若决赛取消谷爱凌将无缘奖牌 (If the final is canceled, Gu Ailing will miss the medal)](https://s.weibo.com/weibo?q=%23%E8%8B%A5%E5%86%B3%E8%B5%9B%E5%8F%96%E6%B6%88%E8%B0%B7%E7%88%B1%E5%87%8C%E5%B0%86%E6%97%A0%E7%BC%98%E5%A5%96%E7%89%8C%23) `77.6K 🔥` `-30%`
1. [熊孩子扔螺帽致大熊猫馆紧急收园](https://s.weibo.com/weibo?q=%23%E7%86%8A%E5%AD%A9%E5%AD%90%E6%89%94%E8%9E%BA%E5%B8%BD%E8%87%B4%E5%A4%A7%E7%86%8A%E7%8C%AB%E9%A6%86%E7%B4%A7%E6%80%A5%E6%94%B6%E5%9B%AD%23) `74.1K 🔥` `-33%`
1. [邢菲录个节目看清人间冷暖](https://s.weibo.com/weibo?q=%23%E9%82%A2%E8%8F%B2%E5%BD%95%E4%B8%AA%E8%8A%82%E7%9B%AE%E7%9C%8B%E6%B8%85%E4%BA%BA%E9%97%B4%E5%86%B7%E6%9A%96%23) `72.0K 🔥` `-35%`

Updated at 2026-02-22 18:12:11

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
