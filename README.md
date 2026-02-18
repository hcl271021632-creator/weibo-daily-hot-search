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

1. [高市早苗再当选日本首相 (Sanae Takaichi re-elected as Prime Minister of Japan)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%86%8D%E5%BD%93%E9%80%89%E6%97%A5%E6%9C%AC%E9%A6%96%E7%9B%B8%23) `1.2M 🔥` `NEW`
1. [大年初二回门日](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%8C%E5%9B%9E%E9%97%A8%E6%97%A5%23) `677.3K 🔥` `NEW`
1. [诗幂](https://s.weibo.com/weibo?q=%23%E8%AF%97%E5%B9%82%23) `195.2K 🔥` `NEW`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `194.8K 🔥` `NEW`
1. [刘诗诗给杨幂拿话筒](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%AF%97%E8%AF%97%E7%BB%99%E6%9D%A8%E5%B9%82%E6%8B%BF%E8%AF%9D%E7%AD%92%23) `194.7K 🔥` `NEW`
1. [在宁波马力全开过大年](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%AE%81%E6%B3%A2%E9%A9%AC%E5%8A%9B%E5%85%A8%E5%BC%80%E8%BF%87%E5%A4%A7%E5%B9%B4%23) `186.1K 🔥` `NEW`
1. [军事AI新视野](https://s.weibo.com/weibo?q=%23%E5%86%9B%E4%BA%8BAI%E6%96%B0%E8%A7%86%E9%87%8E%23) `175.7K 🔥` `NEW`
1. [电影星河入梦](https://s.weibo.com/weibo?q=%23%E7%94%B5%E5%BD%B1%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%23) `147.6K 🔥` `NEW`
1. [你家姑爷今天贡献了什么名场面](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%AE%B6%E5%A7%91%E7%88%B7%E4%BB%8A%E5%A4%A9%E8%B4%A1%E7%8C%AE%E4%BA%86%E4%BB%80%E4%B9%88%E5%90%8D%E5%9C%BA%E9%9D%A2%23) `120.3K 🔥` `NEW`
1. [徐梦桃第5次出战冬奥会](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E7%AC%AC5%E6%AC%A1%E5%87%BA%E6%88%98%E5%86%AC%E5%A5%A5%E4%BC%9A%23) `120.0K 🔥` `NEW`
1. [妈妈炸丸子翻车立刻去姥姥家求助 (Mom's croquettes overturned and she immediately went to her grandma's house for help.)](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E7%82%B8%E4%B8%B8%E5%AD%90%E7%BF%BB%E8%BD%A6%E7%AB%8B%E5%88%BB%E5%8E%BB%E5%A7%A5%E5%A7%A5%E5%AE%B6%E6%B1%82%E5%8A%A9%23) `91.3K 🔥` `NEW`
1. [林孝埈刘少昂决赛前瞻](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E5%88%98%E5%B0%91%E6%98%82%E5%86%B3%E8%B5%9B%E5%89%8D%E7%9E%BB%23) `89.4K 🔥` `NEW`
1. [大侦探没侦探助理了](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BE%A6%E6%8E%A2%E6%B2%A1%E4%BE%A6%E6%8E%A2%E5%8A%A9%E7%90%86%E4%BA%86%23) `82.7K 🔥` `NEW`
1. [金饰价跌到1509元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E8%B7%8C%E5%88%B01509%E5%85%83%23) `70.9K 🔥` `NEW`
1. [短道速滑局面像8年前平昌](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%E5%B1%80%E9%9D%A2%E5%83%8F8%E5%B9%B4%E5%89%8D%E5%B9%B3%E6%98%8C%23) `69.6K 🔥` `NEW`
1. [时代少年团周边](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E5%91%A8%E8%BE%B9%23) `69.6K 🔥` `NEW`
1. [刘耀文 雷佳音是坏人不跟他讲话](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%80%80%E6%96%87%20%E9%9B%B7%E4%BD%B3%E9%9F%B3%E6%98%AF%E5%9D%8F%E4%BA%BA%E4%B8%8D%E8%B7%9F%E4%BB%96%E8%AE%B2%E8%AF%9D%23) `68.2K 🔥` `NEW`
1. [时代峰峻高会崩了](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E9%AB%98%E4%BC%9A%E5%B4%A9%E4%BA%86%23) `67.5K 🔥` `NEW`
1. [中国速滑队出场镜头太夯了](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%80%9F%E6%BB%91%E9%98%9F%E5%87%BA%E5%9C%BA%E9%95%9C%E5%A4%B4%E5%A4%AA%E5%A4%AF%E4%BA%86%23) `65.4K 🔥` `NEW`
1. [蔡卓妍晒英皇艺人拜年大合照](https://s.weibo.com/weibo?q=%23%E8%94%A1%E5%8D%93%E5%A6%8D%E6%99%92%E8%8B%B1%E7%9A%87%E8%89%BA%E4%BA%BA%E6%8B%9C%E5%B9%B4%E5%A4%A7%E5%90%88%E7%85%A7%23) `62.2K 🔥` `NEW`
1. [孩子存1000比你存20万利息高 (If your child saves 1,000, the interest will be higher than if you save 200,000.)](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E5%AD%981000%E6%AF%94%E4%BD%A0%E5%AD%9820%E4%B8%87%E5%88%A9%E6%81%AF%E9%AB%98%23) `857.6K 🔥` `+1044%`
1. [奥迪抽奖送车除夕福利返场 (Audi returns with lucky draw and car giveaway on New Year’s Eve)](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E8%BF%AA%E6%8A%BD%E5%A5%96%E9%80%81%E8%BD%A6%E9%99%A4%E5%A4%95%E7%A6%8F%E5%88%A9%E8%BF%94%E5%9C%BA%23) `653.8K 🔥` `+161%`
1. [龙洋主持完春晚哭了 (Long Yang cried after hosting the Spring Festival Gala)](https://s.weibo.com/weibo?q=%23%E9%BE%99%E6%B4%8B%E4%B8%BB%E6%8C%81%E5%AE%8C%E6%98%A5%E6%99%9A%E5%93%AD%E4%BA%86%23) `520.5K 🔥` `+79%`
1. [惊蛰无声豆瓣开分6.3](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%E8%B1%86%E7%93%A3%E5%BC%80%E5%88%866.3%23) `236.2K 🔥` `+129%`
1. [宋小宝 掉微博热搜池里了救救我](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%B0%8F%E5%AE%9D%20%E6%8E%89%E5%BE%AE%E5%8D%9A%E7%83%AD%E6%90%9C%E6%B1%A0%E9%87%8C%E4%BA%86%E6%95%91%E6%95%91%E6%88%91%23) `199.9K 🔥` `+42%`
1. [谷爱凌 顶级alpha](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%20%E9%A1%B6%E7%BA%A7alpha%23) `195.3K 🔥` `+39%`
1. [马凡舒回应春晚发型争议 (Ma Fanshu responds to Spring Festival Gala hairstyle controversy)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%87%A1%E8%88%92%E5%9B%9E%E5%BA%94%E6%98%A5%E6%99%9A%E5%8F%91%E5%9E%8B%E4%BA%89%E8%AE%AE%23) `195.0K 🔥` `+79%`
1. [高市早苗内阁集体辞职 (Takaichi Sanae cabinet resigns en masse)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%86%85%E9%98%81%E9%9B%86%E4%BD%93%E8%BE%9E%E8%81%8C%23) `180.3K 🔥` `+28%`
1. [娜然与霍家父子同游意大利 (Naran traveled to Italy with the Huo family and his son)](https://s.weibo.com/weibo?q=%23%E5%A8%9C%E7%84%B6%E4%B8%8E%E9%9C%8D%E5%AE%B6%E7%88%B6%E5%AD%90%E5%90%8C%E6%B8%B8%E6%84%8F%E5%A4%A7%E5%88%A9%23) `174.0K 🔥` `+53%`
1. [今年过年没人催婚了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E8%BF%87%E5%B9%B4%E6%B2%A1%E4%BA%BA%E5%82%AC%E5%A9%9A%E4%BA%86%23) `170.8K 🔥` `+54%`
1. [月嫂回应为入狱雇主无偿带娃](https://s.weibo.com/weibo?q=%23%E6%9C%88%E5%AB%82%E5%9B%9E%E5%BA%94%E4%B8%BA%E5%85%A5%E7%8B%B1%E9%9B%87%E4%B8%BB%E6%97%A0%E5%81%BF%E5%B8%A6%E5%A8%83%23) `166.9K 🔥` `+76%`
1. [洗衣机竟用错了那么多年](https://s.weibo.com/weibo?q=%23%E6%B4%97%E8%A1%A3%E6%9C%BA%E7%AB%9F%E7%94%A8%E9%94%99%E4%BA%86%E9%82%A3%E4%B9%88%E5%A4%9A%E5%B9%B4%23) `128.0K 🔥` `+23%`
1. [刘宇宁说大家进了春晚休息间鸦雀无声](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E8%AF%B4%E5%A4%A7%E5%AE%B6%E8%BF%9B%E4%BA%86%E6%98%A5%E6%99%9A%E4%BC%91%E6%81%AF%E9%97%B4%E9%B8%A6%E9%9B%80%E6%97%A0%E5%A3%B0%23) `121.3K 🔥` `+33%`
1. [网民造谣非洲猪瘟在本地传播被罚](https://s.weibo.com/weibo?q=%23%E7%BD%91%E6%B0%91%E9%80%A0%E8%B0%A3%E9%9D%9E%E6%B4%B2%E7%8C%AA%E7%98%9F%E5%9C%A8%E6%9C%AC%E5%9C%B0%E4%BC%A0%E6%92%AD%E8%A2%AB%E7%BD%9A%23) `201.6K 🔥`
1. [豆包打麻将](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E6%89%93%E9%BA%BB%E5%B0%86%23) `194.8K 🔥`
1. [刘浩存 你就是有天赋 (Liu Haocun, you just have talent)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%20%E4%BD%A0%E5%B0%B1%E6%98%AF%E6%9C%89%E5%A4%A9%E8%B5%8B%23) `119.9K 🔥`
1. [大侦探11开播](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BE%A6%E6%8E%A211%E5%BC%80%E6%92%AD%23) `90.6K 🔥`
1. [王楚然出圈镜头](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E5%87%BA%E5%9C%88%E9%95%9C%E5%A4%B4%23) `90.2K 🔥`
1. [成何体统](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%23) `75.5K 🔥`
1. [第一次见古装剧男主叫女主紫啧](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%A7%81%E5%8F%A4%E8%A3%85%E5%89%A7%E7%94%B7%E4%B8%BB%E5%8F%AB%E5%A5%B3%E4%B8%BB%E7%B4%AB%E5%95%A7%23) `70.9K 🔥`
1. [大年初二不午睡](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%8C%E4%B8%8D%E5%8D%88%E7%9D%A1%23) `201.7K 🔥` `-82%`
1. [飞驰人生3票房或超50亿](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E7%A5%A8%E6%88%BF%E6%88%96%E8%B6%8550%E4%BA%BF%23) `199.7K 🔥` `-36%`
1. [过年不要一直穿睡衣](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E4%B8%8D%E8%A6%81%E4%B8%80%E7%9B%B4%E7%A9%BF%E7%9D%A1%E8%A1%A3%23) `195.3K 🔥` `-32%`
1. [女生半年卖出800多只点翠大蟑螂](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E5%8D%8A%E5%B9%B4%E5%8D%96%E5%87%BA800%E5%A4%9A%E5%8F%AA%E7%82%B9%E7%BF%A0%E5%A4%A7%E8%9F%91%E8%9E%82%23) `191.6K 🔥` `-37%`
1. [听说全国女婿到丈母娘家都这样 (I heard that this happens all over the country when a son-in-law goes to his mother-in-law’s house.)](https://s.weibo.com/weibo?q=%23%E5%90%AC%E8%AF%B4%E5%85%A8%E5%9B%BD%E5%A5%B3%E5%A9%BF%E5%88%B0%E4%B8%88%E6%AF%8D%E5%A8%98%E5%AE%B6%E9%83%BD%E8%BF%99%E6%A0%B7%23) `188.9K 🔥` `-76%`
1. [成何体统大结局](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%E5%A4%A7%E7%BB%93%E5%B1%80%23) `163.9K 🔥` `-37%`
1. [沈腾看似鼓掌实则扔橘子皮 (Shen Teng seemed to be applauding, but actually he was throwing orange peels)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E7%9C%8B%E4%BC%BC%E9%BC%93%E6%8E%8C%E5%AE%9E%E5%88%99%E6%89%94%E6%A9%98%E5%AD%90%E7%9A%AE%23) `105.3K 🔥` `-25%`
1. [特斯拉宣布首辆Cybercab下线](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%96%AF%E6%8B%89%E5%AE%A3%E5%B8%83%E9%A6%96%E8%BE%86Cybercab%E4%B8%8B%E7%BA%BF%23) `67.6K 🔥` `-26%`
1. [王一博易烊千玺春晚穿搭上榜最佳](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E6%98%A5%E6%99%9A%E7%A9%BF%E6%90%AD%E4%B8%8A%E6%A6%9C%E6%9C%80%E4%BD%B3%23) `67.0K 🔥` `-34%`
1. [菲律宾海警在南海投放不明物体](https://s.weibo.com/weibo?q=%23%E8%8F%B2%E5%BE%8B%E5%AE%BE%E6%B5%B7%E8%AD%A6%E5%9C%A8%E5%8D%97%E6%B5%B7%E6%8A%95%E6%94%BE%E4%B8%8D%E6%98%8E%E7%89%A9%E4%BD%93%23) `63.7K 🔥` `-45%`
1. [国外长大的中国娃回老家过年反应亮了](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%A4%96%E9%95%BF%E5%A4%A7%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%A8%83%E5%9B%9E%E8%80%81%E5%AE%B6%E8%BF%87%E5%B9%B4%E5%8F%8D%E5%BA%94%E4%BA%AE%E4%BA%86%23) `62.4K 🔥` `-46%`

Updated at 2026-02-18 15:29:39

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
