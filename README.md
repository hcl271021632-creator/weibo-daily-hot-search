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

1. [安崎求职浪姐真的成功了 (An Qi’s job search for Sister Lang was really successful)](https://s.weibo.com/weibo?q=%23%E5%AE%89%E5%B4%8E%E6%B1%82%E8%81%8C%E6%B5%AA%E5%A7%90%E7%9C%9F%E7%9A%84%E6%88%90%E5%8A%9F%E4%BA%86%23) `627.3K 🔥` `NEW`
1. [锋芒上新全新以赴](https://s.weibo.com/weibo?q=%23%E9%94%8B%E8%8A%92%E4%B8%8A%E6%96%B0%E5%85%A8%E6%96%B0%E4%BB%A5%E8%B5%B4%23) `564.2K 🔥` `NEW`
1. [张凌赫田曦薇挑衅经纪人](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%8C%91%E8%A1%85%E7%BB%8F%E7%BA%AA%E4%BA%BA%23) `555.6K 🔥` `NEW`
1. [代表呼吁关注通信骚扰再抬头](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%91%BC%E5%90%81%E5%85%B3%E6%B3%A8%E9%80%9A%E4%BF%A1%E9%AA%9A%E6%89%B0%E5%86%8D%E6%8A%AC%E5%A4%B4%23) `536.3K 🔥` `NEW`
1. [刘国梁卸任世界乒联董事会主席](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%9B%BD%E6%A2%81%E5%8D%B8%E4%BB%BB%E4%B8%96%E7%95%8C%E4%B9%92%E8%81%94%E8%91%A3%E4%BA%8B%E4%BC%9A%E4%B8%BB%E5%B8%AD%23) `493.8K 🔥` `NEW`
1. [47岁男子1000元彩礼娶82岁老人](https://s.weibo.com/weibo?q=%2347%E5%B2%81%E7%94%B7%E5%AD%901000%E5%85%83%E5%BD%A9%E7%A4%BC%E5%A8%B682%E5%B2%81%E8%80%81%E4%BA%BA%23) `287.4K 🔥` `NEW`
1. [北京WBG对战ACT](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%ACWBG%E5%AF%B9%E6%88%98ACT%23) `193.1K 🔥` `NEW`
1. [中方支持伊朗人民渡过难关](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E6%94%AF%E6%8C%81%E4%BC%8A%E6%9C%97%E4%BA%BA%E6%B0%91%E6%B8%A1%E8%BF%87%E9%9A%BE%E5%85%B3%23) `192.1K 🔥` `NEW`
1. [女生照片遭一键脱衣发至色情网](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E7%85%A7%E7%89%87%E9%81%AD%E4%B8%80%E9%94%AE%E8%84%B1%E8%A1%A3%E5%8F%91%E8%87%B3%E8%89%B2%E6%83%85%E7%BD%91%23) `128.5K 🔥` `NEW`
1. [张杰鸟巢舞台概念图](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E9%B8%9F%E5%B7%A2%E8%88%9E%E5%8F%B0%E6%A6%82%E5%BF%B5%E5%9B%BE%23) `104.5K 🔥` `NEW`
1. [中方向伊朗遇难学生家长援助20万美元 (China provides $200,000 in aid to parents of Iranian students killed)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%90%91%E4%BC%8A%E6%9C%97%E9%81%87%E9%9A%BE%E5%AD%A6%E7%94%9F%E5%AE%B6%E9%95%BF%E6%8F%B4%E5%8A%A920%E4%B8%87%E7%BE%8E%E5%85%83%23) `103.5K 🔥` `NEW`
1. [花1.5万就能用修正商标卖自家产品](https://s.weibo.com/weibo?q=%23%E8%8A%B11.5%E4%B8%87%E5%B0%B1%E8%83%BD%E7%94%A8%E4%BF%AE%E6%AD%A3%E5%95%86%E6%A0%87%E5%8D%96%E8%87%AA%E5%AE%B6%E4%BA%A7%E5%93%81%23) `92.8K 🔥` `NEW`
1. [美国中期选举开战](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%AD%E6%9C%9F%E9%80%89%E4%B8%BE%E5%BC%80%E6%88%98%23) `91.5K 🔥` `NEW`
1. [五粮液变五稂液](https://s.weibo.com/weibo?q=%23%E4%BA%94%E7%B2%AE%E6%B6%B2%E5%8F%98%E4%BA%94%E7%A8%82%E6%B6%B2%23) `85.5K 🔥` `NEW`
1. [辞职把自己感动哭了](https://s.weibo.com/weibo?q=%23%E8%BE%9E%E8%81%8C%E6%8A%8A%E8%87%AA%E5%B7%B1%E6%84%9F%E5%8A%A8%E5%93%AD%E4%BA%86%23) `81.7K 🔥` `NEW`
1. [漳州市市监局介入核实问题冻干草莓](https://s.weibo.com/weibo?q=%23%E6%BC%B3%E5%B7%9E%E5%B8%82%E5%B8%82%E7%9B%91%E5%B1%80%E4%BB%8B%E5%85%A5%E6%A0%B8%E5%AE%9E%E9%97%AE%E9%A2%98%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%23) `80.8K 🔥` `NEW`
1. [国漫男主单刀抢亲夯爆了](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E6%BC%AB%E7%94%B7%E4%B8%BB%E5%8D%95%E5%88%80%E6%8A%A2%E4%BA%B2%E5%A4%AF%E7%88%86%E4%BA%86%23) `77.0K 🔥` `NEW`
1. [第五人格COA9](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%BA%94%E4%BA%BA%E6%A0%BCCOA9%23) `76.3K 🔥` `NEW`
1. [90后成30万级汽车消费主力](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E6%88%9030%E4%B8%87%E7%BA%A7%E6%B1%BD%E8%BD%A6%E6%B6%88%E8%B4%B9%E4%B8%BB%E5%8A%9B%23) `75.4K 🔥` `NEW`
1. [冻干草莓 农药](https://s.weibo.com/weibo?q=%23%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%20%E5%86%9C%E8%8D%AF%23) `600.1K 🔥` `+68%`
1. [中俄安理会硬刚美国 (China-Russia Security Council toughens the United States)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BF%84%E5%AE%89%E7%90%86%E4%BC%9A%E7%A1%AC%E5%88%9A%E7%BE%8E%E5%9B%BD%23) `570.4K 🔥` `+96%`
1. [世界从中国两会看到新机遇 (The world sees new opportunities from China’s Two Sessions)](https://s.weibo.com/weibo?q=%23%E4%B8%96%E7%95%8C%E4%BB%8E%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E7%9C%8B%E5%88%B0%E6%96%B0%E6%9C%BA%E9%81%87%23) `469.8K 🔥` `+68%`
1. [长期用小拇指托手机的后果 (The consequences of holding your phone with your little finger for a long time)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E7%94%A8%E5%B0%8F%E6%8B%87%E6%8C%87%E6%89%98%E6%89%8B%E6%9C%BA%E7%9A%84%E5%90%8E%E6%9E%9C%23) `466.2K 🔥` `+97%`
1. [卜凡 sk团播](https://s.weibo.com/weibo?q=%23%E5%8D%9C%E5%87%A1%20sk%E5%9B%A2%E6%92%AD%23) `425.6K 🔥` `+241%`
1. [别让你的微信隐私在裸奔 (Don’t let your WeChat privacy slip away naked)](https://s.weibo.com/weibo?q=%23%E5%88%AB%E8%AE%A9%E4%BD%A0%E7%9A%84%E5%BE%AE%E4%BF%A1%E9%9A%90%E7%A7%81%E5%9C%A8%E8%A3%B8%E5%A5%94%23) `390.7K 🔥` `+36%`
1. [绩效 反人类](https://s.weibo.com/weibo?q=%23%E7%BB%A9%E6%95%88%20%E5%8F%8D%E4%BA%BA%E7%B1%BB%23) `367.3K 🔥` `+38%`
1. [严屹宽 双男主](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%20%E5%8F%8C%E7%94%B7%E4%B8%BB%23) `348.6K 🔥` `+28%`
1. [女子把过期牛奶给狗喝致其死亡](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%8A%8A%E8%BF%87%E6%9C%9F%E7%89%9B%E5%A5%B6%E7%BB%99%E7%8B%97%E5%96%9D%E8%87%B4%E5%85%B6%E6%AD%BB%E4%BA%A1%23) `191.1K 🔥` `+41%`
1. [韩佳人化中国网红妆](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E4%BD%B3%E4%BA%BA%E5%8C%96%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BA%A2%E5%A6%86%23) `174.3K 🔥` `+101%`
1. [伊朗被曝研究开辟新战场](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AB%E6%9B%9D%E7%A0%94%E7%A9%B6%E5%BC%80%E8%BE%9F%E6%96%B0%E6%88%98%E5%9C%BA%23) `91.3K 🔥` `+29%`
1. [微信 朋友圈编辑 (WeChat Moments Editor)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%20%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%BC%96%E8%BE%91%23) `1.1M 🔥`
1. [国产手机涨价2000元 (Domestic mobile phone prices increase by 2,000 yuan)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E6%89%8B%E6%9C%BA%E6%B6%A8%E4%BB%B72000%E5%85%83%23) `775.2K 🔥`
1. [十五五新程上我们有底气有动力 (We have the confidence and motivation to embark on the new journey of the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E6%96%B0%E7%A8%8B%E4%B8%8A%E6%88%91%E4%BB%AC%E6%9C%89%E5%BA%95%E6%B0%94%E6%9C%89%E5%8A%A8%E5%8A%9B%23) `630.8K 🔥`
1. [儿子遗体在泰医院失踪中国父亲报警](https://s.weibo.com/weibo?q=%23%E5%84%BF%E5%AD%90%E9%81%97%E4%BD%93%E5%9C%A8%E6%B3%B0%E5%8C%BB%E9%99%A2%E5%A4%B1%E8%B8%AA%E4%B8%AD%E5%9B%BD%E7%88%B6%E4%BA%B2%E6%8A%A5%E8%AD%A6%23) `199.0K 🔥`
1. [痞幼做医美了](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%81%9A%E5%8C%BB%E7%BE%8E%E4%BA%86%23) `191.9K 🔥`
1. [汪铎看出祝绪丹挂脸了](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E9%93%8E%E7%9C%8B%E5%87%BA%E7%A5%9D%E7%BB%AA%E4%B8%B9%E6%8C%82%E8%84%B8%E4%BA%86%23) `80.9K 🔥`
1. [王鹤润 王玉雯 (Wang Herun Wang Yuwen)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%B6%A6%20%E7%8E%8B%E7%8E%89%E9%9B%AF%23) `80.2K 🔥`
1. [女孩吃酸奶勺子卡牙里凌晨就医](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E5%90%83%E9%85%B8%E5%A5%B6%E5%8B%BA%E5%AD%90%E5%8D%A1%E7%89%99%E9%87%8C%E5%87%8C%E6%99%A8%E5%B0%B1%E5%8C%BB%23) `78.3K 🔥`
1. [缺觉等于全身发炎](https://s.weibo.com/weibo?q=%23%E7%BC%BA%E8%A7%89%E7%AD%89%E4%BA%8E%E5%85%A8%E8%BA%AB%E5%8F%91%E7%82%8E%23) `77.4K 🔥`
1. [广电总局将公布演员番位规则 (The State Administration of Radio, Film and Television will announce the cast rules for actors)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E7%94%B5%E6%80%BB%E5%B1%80%E5%B0%86%E5%85%AC%E5%B8%83%E6%BC%94%E5%91%98%E7%95%AA%E4%BD%8D%E8%A7%84%E5%88%99%23) `199.5K 🔥` `-22%`
1. [澳洲遇难男子遗体回家费用犯愁](https://s.weibo.com/weibo?q=%23%E6%BE%B3%E6%B4%B2%E9%81%87%E9%9A%BE%E7%94%B7%E5%AD%90%E9%81%97%E4%BD%93%E5%9B%9E%E5%AE%B6%E8%B4%B9%E7%94%A8%E7%8A%AF%E6%84%81%23) `152.0K 🔥` `-43%`
1. [沈月说不能留白鹿一个人](https://s.weibo.com/weibo?q=%23%E6%B2%88%E6%9C%88%E8%AF%B4%E4%B8%8D%E8%83%BD%E7%95%99%E7%99%BD%E9%B9%BF%E4%B8%80%E4%B8%AA%E4%BA%BA%23) `126.8K 🔥` `-60%`
1. [伊朗称对林肯号航母发动袭击 (Iran says attack on USS Lincoln aircraft carrier)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%AF%B9%E6%9E%97%E8%82%AF%E5%8F%B7%E8%88%AA%E6%AF%8D%E5%8F%91%E5%8A%A8%E8%A2%AD%E5%87%BB%23) `125.9K 🔥` `-46%`
1. [谁敢相信这是九年前的张凌赫](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%95%A2%E7%9B%B8%E4%BF%A1%E8%BF%99%E6%98%AF%E4%B9%9D%E5%B9%B4%E5%89%8D%E7%9A%84%E5%BC%A0%E5%87%8C%E8%B5%AB%23) `97.4K 🔥` `-35%`
1. [周星驰打劫孙燕姿抢演唱会门票](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%98%9F%E9%A9%B0%E6%89%93%E5%8A%AB%E5%AD%99%E7%87%95%E5%A7%BF%E6%8A%A2%E6%BC%94%E5%94%B1%E4%BC%9A%E9%97%A8%E7%A5%A8%23) `90.3K 🔥` `-26%`
1. [多款100%椰子水被曝兑水加糖](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%AC%BE100%25%E6%A4%B0%E5%AD%90%E6%B0%B4%E8%A2%AB%E6%9B%9D%E5%85%91%E6%B0%B4%E5%8A%A0%E7%B3%96%23) `82.4K 🔥` `-71%`
1. [头部演员片酬将发生结构性改变](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E9%83%A8%E6%BC%94%E5%91%98%E7%89%87%E9%85%AC%E5%B0%86%E5%8F%91%E7%94%9F%E7%BB%93%E6%9E%84%E6%80%A7%E6%94%B9%E5%8F%98%23) `82.3K 🔥` `-62%`
1. [00后女生运营体温计网店月销超10万](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E5%A5%B3%E7%94%9F%E8%BF%90%E8%90%A5%E4%BD%93%E6%B8%A9%E8%AE%A1%E7%BD%91%E5%BA%97%E6%9C%88%E9%94%80%E8%B6%8510%E4%B8%87%23) `80.7K 🔥` `-47%`
1. [81岁爷爷误食了我的火鸡面 (81-year-old grandpa accidentally ate my turkey noodles)](https://s.weibo.com/weibo?q=%2381%E5%B2%81%E7%88%B7%E7%88%B7%E8%AF%AF%E9%A3%9F%E4%BA%86%E6%88%91%E7%9A%84%E7%81%AB%E9%B8%A1%E9%9D%A2%23) `79.6K 🔥` `-59%`
1. [不想看AI演戏](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%83%B3%E7%9C%8BAI%E6%BC%94%E6%88%8F%23) `77.9K 🔥` `-70%`
1. [温瑞博vs邱党](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9Avs%E9%82%B1%E5%85%9A%23) `76.2K 🔥` `-21%`

Updated at 2026-03-13 16:55:40

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
