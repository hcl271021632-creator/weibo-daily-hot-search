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

1. [2026春节消费马力全开 (2026 Spring Festival consumption power is on full swing)](https://s.weibo.com/weibo?q=%232026%E6%98%A5%E8%8A%82%E6%B6%88%E8%B4%B9%E9%A9%AC%E5%8A%9B%E5%85%A8%E5%BC%80%23) `598.5K 🔥` `NEW`
1. [和汪苏泷上淘宝闪购喝开工第一杯](https://s.weibo.com/weibo?q=%23%E5%92%8C%E6%B1%AA%E8%8B%8F%E6%B3%B7%E4%B8%8A%E6%B7%98%E5%AE%9D%E9%97%AA%E8%B4%AD%E5%96%9D%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E6%9D%AF%23) `558.9K 🔥` `NEW`
1. [阿瑟 为艺术献身](https://s.weibo.com/weibo?q=%23%E9%98%BF%E7%91%9F%20%E4%B8%BA%E8%89%BA%E6%9C%AF%E7%8C%AE%E8%BA%AB%23) `252.6K 🔥` `NEW`
1. [TCG战胜LGDNBW](https://s.weibo.com/weibo?q=%23TCG%E6%88%98%E8%83%9CLGDNBW%23) `174.9K 🔥` `NEW`
1. [第四次工业革命](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E5%9B%9B%E6%AC%A1%E5%B7%A5%E4%B8%9A%E9%9D%A9%E5%91%BD%23) `139.5K 🔥` `NEW`
1. [二手CCD价格暴涨](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E6%89%8BCCD%E4%BB%B7%E6%A0%BC%E6%9A%B4%E6%B6%A8%23) `109.6K 🔥` `NEW`
1. [开工第一天被通知放假10天](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%E8%A2%AB%E9%80%9A%E7%9F%A5%E6%94%BE%E5%81%8710%E5%A4%A9%23) `87.2K 🔥` `NEW`
1. [ally自曝是王安宇梦女](https://s.weibo.com/weibo?q=%23ally%E8%87%AA%E6%9B%9D%E6%98%AF%E7%8E%8B%E5%AE%89%E5%AE%87%E6%A2%A6%E5%A5%B3%23) `86.7K 🔥` `NEW`
1. [Melody道歉](https://s.weibo.com/weibo?q=%23Melody%E9%81%93%E6%AD%89%23) `84.9K 🔥` `NEW`
1. [TF家族高会背景](https://s.weibo.com/weibo?q=%23TF%E5%AE%B6%E6%97%8F%E9%AB%98%E4%BC%9A%E8%83%8C%E6%99%AF%23) `83.2K 🔥` `NEW`
1. [iPhone17ProMax国内激活销量破千万 (Domestic activation sales of iPhone 17 Pro Max exceed 10 million)](https://s.weibo.com/weibo?q=%23iPhone17ProMax%E5%9B%BD%E5%86%85%E6%BF%80%E6%B4%BB%E9%94%80%E9%87%8F%E7%A0%B4%E5%8D%83%E4%B8%87%23) `81.9K 🔥` `NEW`
1. [宋雨琦拆了假发](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E6%8B%86%E4%BA%86%E5%81%87%E5%8F%91%23) `81.3K 🔥` `NEW`
1. [我应该是神 无本相](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%BA%94%E8%AF%A5%E6%98%AF%E7%A5%9E%20%E6%97%A0%E6%9C%AC%E7%9B%B8%23) `80.0K 🔥` `NEW`
1. [大疆起诉美联邦通信委员会](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%96%86%E8%B5%B7%E8%AF%89%E7%BE%8E%E8%81%94%E9%82%A6%E9%80%9A%E4%BF%A1%E5%A7%94%E5%91%98%E4%BC%9A%23) `79.6K 🔥` `NEW`
1. [家务机器人](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E5%8A%A1%E6%9C%BA%E5%99%A8%E4%BA%BA%23) `78.2K 🔥` `NEW`
1. [音乐摇摆鹅走红有人一万元求购被拒](https://s.weibo.com/weibo?q=%23%E9%9F%B3%E4%B9%90%E6%91%87%E6%91%86%E9%B9%85%E8%B5%B0%E7%BA%A2%E6%9C%89%E4%BA%BA%E4%B8%80%E4%B8%87%E5%85%83%E6%B1%82%E8%B4%AD%E8%A2%AB%E6%8B%92%23) `74.9K 🔥` `NEW`
1. [平顶山被打15岁女孩伤情鉴定](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E9%A1%B6%E5%B1%B1%E8%A2%AB%E6%89%9315%E5%B2%81%E5%A5%B3%E5%AD%A9%E4%BC%A4%E6%83%85%E9%89%B4%E5%AE%9A%23) `74.3K 🔥` `NEW`
1. [重拾小时候的兴趣](https://s.weibo.com/weibo?q=%23%E9%87%8D%E6%8B%BE%E5%B0%8F%E6%97%B6%E5%80%99%E7%9A%84%E5%85%B4%E8%B6%A3%23) `73.6K 🔥` `NEW`
1. [春节国内游总花费超8千亿](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E5%9B%BD%E5%86%85%E6%B8%B8%E6%80%BB%E8%8A%B1%E8%B4%B9%E8%B6%858%E5%8D%83%E4%BA%BF%23) `72.3K 🔥` `NEW`
1. [中方再对日本精准锁喉](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%86%8D%E5%AF%B9%E6%97%A5%E6%9C%AC%E7%B2%BE%E5%87%86%E9%94%81%E5%96%89%23) `71.3K 🔥` `NEW`
1. [德约ins转发了一段谷爱凌的采访 (Djokovic reposted an interview with Gu Ailing on Instagram)](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E7%BA%A6ins%E8%BD%AC%E5%8F%91%E4%BA%86%E4%B8%80%E6%AE%B5%E8%B0%B7%E7%88%B1%E5%87%8C%E7%9A%84%E9%87%87%E8%AE%BF%23) `71.2K 🔥` `NEW`
1. [国粤无双 宋亚轩](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E7%B2%A4%E6%97%A0%E5%8F%8C%20%E5%AE%8B%E4%BA%9A%E8%BD%A9%23) `70.5K 🔥` `NEW`
1. [王楚钦送你个6](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E9%80%81%E4%BD%A0%E4%B8%AA6%23) `68.3K 🔥` `NEW`
1. [多款相机价格暴涨近10倍](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%AC%BE%E7%9B%B8%E6%9C%BA%E4%BB%B7%E6%A0%BC%E6%9A%B4%E6%B6%A8%E8%BF%9110%E5%80%8D%23) `1.1M 🔥` `+667%`
1. [墨西哥毒枭残忍罪行被曝光](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A5%E6%AF%92%E6%9E%AD%E6%AE%8B%E5%BF%8D%E7%BD%AA%E8%A1%8C%E8%A2%AB%E6%9B%9D%E5%85%89%23) `260.8K 🔥` `+143%`
1. [男子误喝过期牛奶暴瘦53斤](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%AF%AF%E5%96%9D%E8%BF%87%E6%9C%9F%E7%89%9B%E5%A5%B6%E6%9A%B4%E7%98%A653%E6%96%A4%23) `197.4K 🔥`
1. [衣服的成本价在水洗标上](https://s.weibo.com/weibo?q=%23%E8%A1%A3%E6%9C%8D%E7%9A%84%E6%88%90%E6%9C%AC%E4%BB%B7%E5%9C%A8%E6%B0%B4%E6%B4%97%E6%A0%87%E4%B8%8A%23) `136.2K 🔥`
1. [12306候补半夜成功车票作废谁担责](https://s.weibo.com/weibo?q=%2312306%E5%80%99%E8%A1%A5%E5%8D%8A%E5%A4%9C%E6%88%90%E5%8A%9F%E8%BD%A6%E7%A5%A8%E4%BD%9C%E5%BA%9F%E8%B0%81%E6%8B%85%E8%B4%A3%23) `121.8K 🔥`
1. [一个烟花烧掉80万](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%B8%AA%E7%83%9F%E8%8A%B1%E7%83%A7%E6%8E%8980%E4%B8%87%23) `105.9K 🔥`
1. [湖南湘阴一男子放烟花时炸膛致身亡 (A man in Xiangyin, Hunan died after his chest exploded while setting off fireworks.)](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E6%B9%98%E9%98%B4%E4%B8%80%E7%94%B7%E5%AD%90%E6%94%BE%E7%83%9F%E8%8A%B1%E6%97%B6%E7%82%B8%E8%86%9B%E8%87%B4%E8%BA%AB%E4%BA%A1%23) `94.1K 🔥`
1. [飞驰人生原型](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F%E5%8E%9F%E5%9E%8B%23) `87.5K 🔥`
1. [史上最高分小品少爷和我 (The highest-scoring skit in history: The Young Master and Me)](https://s.weibo.com/weibo?q=%23%E5%8F%B2%E4%B8%8A%E6%9C%80%E9%AB%98%E5%88%86%E5%B0%8F%E5%93%81%E5%B0%91%E7%88%B7%E5%92%8C%E6%88%91%23) `86.0K 🔥`
1. [小车23点59分59秒下高速收费员狂喜 (The car got off the expressway at 23:59:59 and the toll collector was ecstatic)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E8%BD%A623%E7%82%B959%E5%88%8659%E7%A7%92%E4%B8%8B%E9%AB%98%E9%80%9F%E6%94%B6%E8%B4%B9%E5%91%98%E7%8B%82%E5%96%9C%23) `788.2K 🔥` `-28%`
1. [正月剃头死舅舅的真相来了](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E6%9C%88%E5%89%83%E5%A4%B4%E6%AD%BB%E8%88%85%E8%88%85%E7%9A%84%E7%9C%9F%E7%9B%B8%E6%9D%A5%E4%BA%86%23) `267.9K 🔥` `-67%`
1. [王楚然丞磊 京洛再无佳人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E4%B8%9E%E7%A3%8A%20%E4%BA%AC%E6%B4%9B%E5%86%8D%E6%97%A0%E4%BD%B3%E4%BA%BA%23) `214.6K 🔥` `-21%`
1. [微信新功能面对面传照片](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E6%96%B0%E5%8A%9F%E8%83%BD%E9%9D%A2%E5%AF%B9%E9%9D%A2%E4%BC%A0%E7%85%A7%E7%89%87%23) `141.7K 🔥` `-30%`
1. [草莓360元一斤公司参保人数为0 (Strawberries cost 360 yuan per pound. The number of insured persons in the company is 0)](https://s.weibo.com/weibo?q=%23%E8%8D%89%E8%8E%93360%E5%85%83%E4%B8%80%E6%96%A4%E5%85%AC%E5%8F%B8%E5%8F%82%E4%BF%9D%E4%BA%BA%E6%95%B0%E4%B8%BA0%23) `141.6K 🔥` `-61%`
1. [考研查分能不能给个确切的时间](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E6%9F%A5%E5%88%86%E8%83%BD%E4%B8%8D%E8%83%BD%E7%BB%99%E4%B8%AA%E7%A1%AE%E5%88%87%E7%9A%84%E6%97%B6%E9%97%B4%23) `107.4K 🔥` `-35%`
1. [镖人 删减](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E5%88%A0%E5%87%8F%23) `89.2K 🔥` `-35%`
1. [新娘爸爸婚礼现场退还18.8万彩礼](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%A8%98%E7%88%B8%E7%88%B8%E5%A9%9A%E7%A4%BC%E7%8E%B0%E5%9C%BA%E9%80%80%E8%BF%9818.8%E4%B8%87%E5%BD%A9%E7%A4%BC%23) `85.5K 🔥` `-30%`
1. [白鹿宋雨琦背后抱](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%AE%8B%E9%9B%A8%E7%90%A6%E8%83%8C%E5%90%8E%E6%8A%B1%23) `83.9K 🔥` `-31%`
1. [突然理解了爱坐公交车的人 (Suddenly I understand people who love taking the bus)](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E7%90%86%E8%A7%A3%E4%BA%86%E7%88%B1%E5%9D%90%E5%85%AC%E4%BA%A4%E8%BD%A6%E7%9A%84%E4%BA%BA%23) `83.6K 🔥` `-30%`
1. [新年BBA车价大降](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%B9%B4BBA%E8%BD%A6%E4%BB%B7%E5%A4%A7%E9%99%8D%23) `81.4K 🔥` `-49%`
1. [吴昕谈在快本时人气低](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%B0%88%E5%9C%A8%E5%BF%AB%E6%9C%AC%E6%97%B6%E4%BA%BA%E6%B0%94%E4%BD%8E%23) `80.3K 🔥` `-35%`
1. [任敏 比例 (Ren Min ratio)](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E6%95%8F%20%E6%AF%94%E4%BE%8B%23) `79.0K 🔥` `-36%`
1. [张杰谢娜一起滑雪 (Zhang Jie and Xie Na ski together)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E8%B0%A2%E5%A8%9C%E4%B8%80%E8%B5%B7%E6%BB%91%E9%9B%AA%23) `78.5K 🔥` `-35%`
1. [李现和杨紫父母穿同款外套](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%8E%B0%E5%92%8C%E6%9D%A8%E7%B4%AB%E7%88%B6%E6%AF%8D%E7%A9%BF%E5%90%8C%E6%AC%BE%E5%A4%96%E5%A5%97%23) `77.5K 🔥` `-34%`
1. [沈腾马丽这种鞋也要穿同款吗](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E9%A9%AC%E4%B8%BD%E8%BF%99%E7%A7%8D%E9%9E%8B%E4%B9%9F%E8%A6%81%E7%A9%BF%E5%90%8C%E6%AC%BE%E5%90%97%23) `74.7K 🔥` `-37%`
1. [不让江山 (Do not give way to the country)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%23) `72.0K 🔥` `-35%`
1. [卢昱晓回复外婆去世的粉丝 (Lu Yuxiao replies to fans whose grandmother passed away)](https://s.weibo.com/weibo?q=%23%E5%8D%A2%E6%98%B1%E6%99%93%E5%9B%9E%E5%A4%8D%E5%A4%96%E5%A9%86%E5%8E%BB%E4%B8%96%E7%9A%84%E7%B2%89%E4%B8%9D%23) `70.6K 🔥` `-21%`

Updated at 2026-02-24 19:50:03

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
