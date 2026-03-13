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

1. [2026金树林绽放之夜入围作品 (2026 Golden Grove Blooming Night Finalist Works)](https://s.weibo.com/weibo?q=%232026%E9%87%91%E6%A0%91%E6%9E%97%E7%BB%BD%E6%94%BE%E4%B9%8B%E5%A4%9C%E5%85%A5%E5%9B%B4%E4%BD%9C%E5%93%81%23) `175.2K 🔥` `NEW`
1. [铁证 孙红雷刘宇宁](https://s.weibo.com/weibo?q=%23%E9%93%81%E8%AF%81%20%E5%AD%99%E7%BA%A2%E9%9B%B7%E5%88%98%E5%AE%87%E5%AE%81%23) `122.9K 🔥` `NEW`
1. [爱奇艺股价](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%A5%87%E8%89%BA%E8%82%A1%E4%BB%B7%23) `117.9K 🔥` `NEW`
1. [全素猫粮是噱头吗](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%B4%A0%E7%8C%AB%E7%B2%AE%E6%98%AF%E5%99%B1%E5%A4%B4%E5%90%97%23) `117.8K 🔥` `NEW`
1. [内娱终于有一部全女悬疑剧了](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A8%B1%E7%BB%88%E4%BA%8E%E6%9C%89%E4%B8%80%E9%83%A8%E5%85%A8%E5%A5%B3%E6%82%AC%E7%96%91%E5%89%A7%E4%BA%86%23) `87.0K 🔥` `NEW`
1. [荷兰回国认亲女子生父回应遗弃女儿](https://s.weibo.com/weibo?q=%23%E8%8D%B7%E5%85%B0%E5%9B%9E%E5%9B%BD%E8%AE%A4%E4%BA%B2%E5%A5%B3%E5%AD%90%E7%94%9F%E7%88%B6%E5%9B%9E%E5%BA%94%E9%81%97%E5%BC%83%E5%A5%B3%E5%84%BF%23) `82.8K 🔥` `NEW`
1. [76年的李维嘉像96年的付豪生的](https://s.weibo.com/weibo?q=%2376%E5%B9%B4%E7%9A%84%E6%9D%8E%E7%BB%B4%E5%98%89%E5%83%8F96%E5%B9%B4%E7%9A%84%E4%BB%98%E8%B1%AA%E7%94%9F%E7%9A%84%23) `76.9K 🔥` `NEW`
1. [多方回应被盗国保琉璃在闲鱼售卖](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%96%B9%E5%9B%9E%E5%BA%94%E8%A2%AB%E7%9B%97%E5%9B%BD%E4%BF%9D%E7%90%89%E7%92%83%E5%9C%A8%E9%97%B2%E9%B1%BC%E5%94%AE%E5%8D%96%23) `75.8K 🔥` `NEW`
1. [中国加入三倍核能宣言](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%8A%A0%E5%85%A5%E4%B8%89%E5%80%8D%E6%A0%B8%E8%83%BD%E5%AE%A3%E8%A8%80%23) `65.7K 🔥` `NEW`
1. [苏醒主持人证的含金量我后知后觉](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E9%86%92%E4%B8%BB%E6%8C%81%E4%BA%BA%E8%AF%81%E7%9A%84%E5%90%AB%E9%87%91%E9%87%8F%E6%88%91%E5%90%8E%E7%9F%A5%E5%90%8E%E8%A7%89%23) `65.4K 🔥` `NEW`
1. [张云龙虞书欣聚餐 (Zhang Yunlong and Yu Shuxin have dinner together)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BA%91%E9%BE%99%E8%99%9E%E4%B9%A6%E6%AC%A3%E8%81%9A%E9%A4%90%23) `64.5K 🔥` `NEW`
1. [火星日落的真实照片](https://s.weibo.com/weibo?q=%23%E7%81%AB%E6%98%9F%E6%97%A5%E8%90%BD%E7%9A%84%E7%9C%9F%E5%AE%9E%E7%85%A7%E7%89%87%23) `64.3K 🔥` `NEW`
1. [新机涨价影响二手手机销量](https://s.weibo.com/weibo?q=%23%E6%96%B0%E6%9C%BA%E6%B6%A8%E4%BB%B7%E5%BD%B1%E5%93%8D%E4%BA%8C%E6%89%8B%E6%89%8B%E6%9C%BA%E9%94%80%E9%87%8F%23) `64.0K 🔥` `NEW`
1. [华为回应15599元折叠屏用3天黑屏](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%B8%BA%E5%9B%9E%E5%BA%9415599%E5%85%83%E6%8A%98%E5%8F%A0%E5%B1%8F%E7%94%A83%E5%A4%A9%E9%BB%91%E5%B1%8F%23) `63.9K 🔥` `NEW`
1. [PEL春季赛第四周周决赛](https://s.weibo.com/weibo?q=%23PEL%E6%98%A5%E5%AD%A3%E8%B5%9B%E7%AC%AC%E5%9B%9B%E5%91%A8%E5%91%A8%E5%86%B3%E8%B5%9B%23) `63.9K 🔥` `NEW`
1. [315还没到椰子水就塌房了](https://s.weibo.com/weibo?q=%23315%E8%BF%98%E6%B2%A1%E5%88%B0%E6%A4%B0%E5%AD%90%E6%B0%B4%E5%B0%B1%E5%A1%8C%E6%88%BF%E4%BA%86%23) `63.9K 🔥` `NEW`
1. [psd 不画绘旅人](https://s.weibo.com/weibo?q=%23psd%20%E4%B8%8D%E7%94%BB%E7%BB%98%E6%97%85%E4%BA%BA%23) `63.9K 🔥` `NEW`
1. [姓丁的有福了 丁永一](https://s.weibo.com/weibo?q=%23%E5%A7%93%E4%B8%81%E7%9A%84%E6%9C%89%E7%A6%8F%E4%BA%86%20%E4%B8%81%E6%B0%B8%E4%B8%80%23) `1.1M 🔥` `+648%`
1. [被盗国保琉璃竟在闲鱼公开售卖](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%9B%97%E5%9B%BD%E4%BF%9D%E7%90%89%E7%92%83%E7%AB%9F%E5%9C%A8%E9%97%B2%E9%B1%BC%E5%85%AC%E5%BC%80%E5%94%AE%E5%8D%96%23) `285.4K 🔥` `+213%`
1. [俞浅浅为什么不认识张凌赫田曦薇](https://s.weibo.com/weibo?q=%23%E4%BF%9E%E6%B5%85%E6%B5%85%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%AE%A4%E8%AF%86%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%23) `176.3K 🔥` `+158%`
1. [爱情公寓是霍建华推荐娄艺潇演的 (Love Apartment was recommended by Huo Jianhua and played by Lou Yixiao)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E6%83%85%E5%85%AC%E5%AF%93%E6%98%AF%E9%9C%8D%E5%BB%BA%E5%8D%8E%E6%8E%A8%E8%8D%90%E5%A8%84%E8%89%BA%E6%BD%87%E6%BC%94%E7%9A%84%23) `117.8K 🔥` `+50%`
1. [绿色低碳发展迈入法典时代 (Green and low-carbon development enters the code era)](https://s.weibo.com/weibo?q=%23%E7%BB%BF%E8%89%B2%E4%BD%8E%E7%A2%B3%E5%8F%91%E5%B1%95%E8%BF%88%E5%85%A5%E6%B3%95%E5%85%B8%E6%97%B6%E4%BB%A3%23) `606.5K 🔥`
1. [研究称第二次怀孕会继续重塑大脑](https://s.weibo.com/weibo?q=%23%E7%A0%94%E7%A9%B6%E7%A7%B0%E7%AC%AC%E4%BA%8C%E6%AC%A1%E6%80%80%E5%AD%95%E4%BC%9A%E7%BB%A7%E7%BB%AD%E9%87%8D%E5%A1%91%E5%A4%A7%E8%84%91%23) `531.3K 🔥`
1. [中方向伊朗遇难学生家长援助20万美元 (China provides $200,000 in aid to parents of Iranian students killed)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%90%91%E4%BC%8A%E6%9C%97%E9%81%87%E9%9A%BE%E5%AD%A6%E7%94%9F%E5%AE%B6%E9%95%BF%E6%8F%B4%E5%8A%A920%E4%B8%87%E7%BE%8E%E5%85%83%23) `173.5K 🔥`
1. [这些两会好声音掷地有声](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%BA%9B%E4%B8%A4%E4%BC%9A%E5%A5%BD%E5%A3%B0%E9%9F%B3%E6%8E%B7%E5%9C%B0%E6%9C%89%E5%A3%B0%23) `163.8K 🔥`
1. [取消家长护学岗让家校关系回归正轨](https://s.weibo.com/weibo?q=%23%E5%8F%96%E6%B6%88%E5%AE%B6%E9%95%BF%E6%8A%A4%E5%AD%A6%E5%B2%97%E8%AE%A9%E5%AE%B6%E6%A0%A1%E5%85%B3%E7%B3%BB%E5%9B%9E%E5%BD%92%E6%AD%A3%E8%BD%A8%23) `154.9K 🔥`
1. [母亲网购中药儿子吃后抽搐昏迷](https://s.weibo.com/weibo?q=%23%E6%AF%8D%E4%BA%B2%E7%BD%91%E8%B4%AD%E4%B8%AD%E8%8D%AF%E5%84%BF%E5%AD%90%E5%90%83%E5%90%8E%E6%8A%BD%E6%90%90%E6%98%8F%E8%BF%B7%23) `153.3K 🔥`
1. [长期用小拇指托手机的后果 (The consequences of holding your phone with your little finger for a long time)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E7%94%A8%E5%B0%8F%E6%8B%87%E6%8C%87%E6%89%98%E6%89%8B%E6%9C%BA%E7%9A%84%E5%90%8E%E6%9E%9C%23) `152.4K 🔥`
1. [严屹宽 双男主 (Yan Yikuan, two male protagonists)](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%20%E5%8F%8C%E7%94%B7%E4%B8%BB%23) `151.0K 🔥`
1. [济州航空空难一年后再现遇难者遗骸](https://s.weibo.com/weibo?q=%23%E6%B5%8E%E5%B7%9E%E8%88%AA%E7%A9%BA%E7%A9%BA%E9%9A%BE%E4%B8%80%E5%B9%B4%E5%90%8E%E5%86%8D%E7%8E%B0%E9%81%87%E9%9A%BE%E8%80%85%E9%81%97%E9%AA%B8%23) `150.4K 🔥`
1. [广电总局将公布演员番位规则 (The State Administration of Radio, Film and Television will announce the cast rules for actors)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E7%94%B5%E6%80%BB%E5%B1%80%E5%B0%86%E5%85%AC%E5%B8%83%E6%BC%94%E5%91%98%E7%95%AA%E4%BD%8D%E8%A7%84%E5%88%99%23) `121.7K 🔥`
1. [儿子遗体在泰医院失踪中国父亲报警](https://s.weibo.com/weibo?q=%23%E5%84%BF%E5%AD%90%E9%81%97%E4%BD%93%E5%9C%A8%E6%B3%B0%E5%8C%BB%E9%99%A2%E5%A4%B1%E8%B8%AA%E4%B8%AD%E5%9B%BD%E7%88%B6%E4%BA%B2%E6%8A%A5%E8%AD%A6%23) `119.6K 🔥`
1. [中俄安理会硬刚美国 (China-Russia Security Council toughens the United States)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BF%84%E5%AE%89%E7%90%86%E4%BC%9A%E7%A1%AC%E5%88%9A%E7%BE%8E%E5%9B%BD%23) `118.9K 🔥`
1. [绩效 反人类](https://s.weibo.com/weibo?q=%23%E7%BB%A9%E6%95%88%20%E5%8F%8D%E4%BA%BA%E7%B1%BB%23) `117.8K 🔥`
1. [女子把过期牛奶给狗喝致其死亡](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%8A%8A%E8%BF%87%E6%9C%9F%E7%89%9B%E5%A5%B6%E7%BB%99%E7%8B%97%E5%96%9D%E8%87%B4%E5%85%B6%E6%AD%BB%E4%BA%A1%23) `117.8K 🔥`
1. [瞿颖能不能去花少](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%83%BD%E4%B8%8D%E8%83%BD%E5%8E%BB%E8%8A%B1%E5%B0%91%23) `91.6K 🔥`
1. [沈月说不能留白鹿一个人 (Shen Yue said Bai Lu could not be left alone)](https://s.weibo.com/weibo?q=%23%E6%B2%88%E6%9C%88%E8%AF%B4%E4%B8%8D%E8%83%BD%E7%95%99%E7%99%BD%E9%B9%BF%E4%B8%80%E4%B8%AA%E4%BA%BA%23) `83.1K 🔥`
1. [韩佳人化中国网红妆](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E4%BD%B3%E4%BA%BA%E5%8C%96%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BA%A2%E5%A6%86%23) `75.7K 🔥`
1. [大冰让做微商的女子讲行业内幕 (Dabing lets a woman doing micro-business tell the inside story of the industry)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%86%B0%E8%AE%A9%E5%81%9A%E5%BE%AE%E5%95%86%E7%9A%84%E5%A5%B3%E5%AD%90%E8%AE%B2%E8%A1%8C%E4%B8%9A%E5%86%85%E5%B9%95%23) `64.3K 🔥`
1. [张杰鸟巢舞台概念图 (Zhang Jie Bird's Nest stage concept map)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E9%B8%9F%E5%B7%A2%E8%88%9E%E5%8F%B0%E6%A6%82%E5%BF%B5%E5%9B%BE%23) `64.0K 🔥`
1. [微信 朋友圈编辑 (WeChat Moments Editor)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%20%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%BC%96%E8%BE%91%23) `803.2K 🔥` `-23%`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `155.9K 🔥` `-79%`
1. [冻干草莓 农药 (freeze-dried strawberries pesticides)](https://s.weibo.com/weibo?q=%23%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%20%E5%86%9C%E8%8D%AF%23) `111.1K 🔥` `-24%`
1. [国产手机涨价2000元 (Domestic mobile phone prices increase by 2,000 yuan)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E6%89%8B%E6%9C%BA%E6%B6%A8%E4%BB%B72000%E5%85%83%23) `99.5K 🔥` `-51%`
1. [痞幼做医美了](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%81%9A%E5%8C%BB%E7%BE%8E%E4%BA%86%23) `93.0K 🔥` `-35%`
1. [手机价格大涨消费者发声](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E4%BB%B7%E6%A0%BC%E5%A4%A7%E6%B6%A8%E6%B6%88%E8%B4%B9%E8%80%85%E5%8F%91%E5%A3%B0%23) `87.8K 🔥` `-41%`
1. [张晚意没到二月二就剪头了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%99%9A%E6%84%8F%E6%B2%A1%E5%88%B0%E4%BA%8C%E6%9C%88%E4%BA%8C%E5%B0%B1%E5%89%AA%E5%A4%B4%E4%BA%86%23) `82.2K 🔥` `-41%`
1. [卜凡 sk团播](https://s.weibo.com/weibo?q=%23%E5%8D%9C%E5%87%A1%20sk%E5%9B%A2%E6%92%AD%23) `76.8K 🔥` `-46%`
1. [安崎求职浪姐真的成功了 (An Qi’s job search for Sister Lang was really successful)](https://s.weibo.com/weibo?q=%23%E5%AE%89%E5%B4%8E%E6%B1%82%E8%81%8C%E6%B5%AA%E5%A7%90%E7%9C%9F%E7%9A%84%E6%88%90%E5%8A%9F%E4%BA%86%23) `71.8K 🔥` `-38%`
1. [头部演员片酬将发生结构性改变 (The salary of leading actors will undergo structural changes)](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E9%83%A8%E6%BC%94%E5%91%98%E7%89%87%E9%85%AC%E5%B0%86%E5%8F%91%E7%94%9F%E7%BB%93%E6%9E%84%E6%80%A7%E6%94%B9%E5%8F%98%23) `64.2K 🔥` `-56%`
1. [女生照片遭一键脱衣发至色情网](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E7%85%A7%E7%89%87%E9%81%AD%E4%B8%80%E9%94%AE%E8%84%B1%E8%A1%A3%E5%8F%91%E8%87%B3%E8%89%B2%E6%83%85%E7%BD%91%23) `64.0K 🔥` `-49%`

Updated at 2026-03-13 19:00:29

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
