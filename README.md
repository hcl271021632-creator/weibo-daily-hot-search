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

1. [建议禁止性侵未成年罪犯进入幼儿园 (It is recommended that juvenile sexual offenders be prohibited from entering kindergartens)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%A6%81%E6%AD%A2%E6%80%A7%E4%BE%B5%E6%9C%AA%E6%88%90%E5%B9%B4%E7%BD%AA%E7%8A%AF%E8%BF%9B%E5%85%A5%E5%B9%BC%E5%84%BF%E5%9B%AD%23) `1.1M 🔥` `NEW`
1. [今年经济增长目标4.5%至5%](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E7%BB%8F%E6%B5%8E%E5%A2%9E%E9%95%BF%E7%9B%AE%E6%A0%874.5%25%E8%87%B35%25%23) `801.1K 🔥` `NEW`
1. [2025年主要目标任务顺利完成](https://s.weibo.com/weibo?q=%232025%E5%B9%B4%E4%B8%BB%E8%A6%81%E7%9B%AE%E6%A0%87%E4%BB%BB%E5%8A%A1%E9%A1%BA%E5%88%A9%E5%AE%8C%E6%88%90%23) `643.7K 🔥` `NEW`
1. [现在发动机还重要吗](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E5%8F%91%E5%8A%A8%E6%9C%BA%E8%BF%98%E9%87%8D%E8%A6%81%E5%90%97%23) `623.5K 🔥` `NEW`
1. [推进祖国统一](https://s.weibo.com/weibo?q=%23%E6%8E%A8%E8%BF%9B%E7%A5%96%E5%9B%BD%E7%BB%9F%E4%B8%80%23) `499.6K 🔥` `NEW`
1. [第一场部长通道](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E5%9C%BA%E9%83%A8%E9%95%BF%E9%80%9A%E9%81%93%23) `454.3K 🔥` `NEW`
1. [杨紫草本初色全球品牌代言人](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E8%8D%89%E6%9C%AC%E5%88%9D%E8%89%B2%E5%85%A8%E7%90%83%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `432.6K 🔥` `NEW`
1. [2026政府工作报告](https://s.weibo.com/weibo?q=%232026%E6%94%BF%E5%BA%9C%E5%B7%A5%E4%BD%9C%E6%8A%A5%E5%91%8A%23) `416.5K 🔥` `NEW`
1. [居民基础养老金月再提20元](https://s.weibo.com/weibo?q=%23%E5%B1%85%E6%B0%91%E5%9F%BA%E7%A1%80%E5%85%BB%E8%80%81%E9%87%91%E6%9C%88%E5%86%8D%E6%8F%9020%E5%85%83%23) `253.8K 🔥` `NEW`
1. [九组数据感受胜利收官壮阔历程](https://s.weibo.com/weibo?q=%23%E4%B9%9D%E7%BB%84%E6%95%B0%E6%8D%AE%E6%84%9F%E5%8F%97%E8%83%9C%E5%88%A9%E6%94%B6%E5%AE%98%E5%A3%AE%E9%98%94%E5%8E%86%E7%A8%8B%23) `252.7K 🔥` `NEW`
1. [霸王茶姬口令 (Overlord Cha Ji password)](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `250.7K 🔥` `NEW`
1. [伊朗总统强调尊重邻国主权](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E5%BC%BA%E8%B0%83%E5%B0%8A%E9%87%8D%E9%82%BB%E5%9B%BD%E4%B8%BB%E6%9D%83%23) `247.6K 🔥` `NEW`
1. [离职排队都排到7月份了](https://s.weibo.com/weibo?q=%23%E7%A6%BB%E8%81%8C%E6%8E%92%E9%98%9F%E9%83%BD%E6%8E%92%E5%88%B07%E6%9C%88%E4%BB%BD%E4%BA%86%23) `245.0K 🔥` `NEW`
1. [电影我的妈耶定档](https://s.weibo.com/weibo?q=%23%E7%94%B5%E5%BD%B1%E6%88%91%E7%9A%84%E5%A6%88%E8%80%B6%E5%AE%9A%E6%A1%A3%23) `239.4K 🔥` `NEW`
1. [千问AI眼镜MWC全球重磅首发](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AEAI%E7%9C%BC%E9%95%9CMWC%E5%85%A8%E7%90%83%E9%87%8D%E7%A3%85%E9%A6%96%E5%8F%91%23) `226.0K 🔥` `NEW`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `197.6K 🔥` `NEW`
1. [李娜姜山认定的家用SUV](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%A8%9C%E5%A7%9C%E5%B1%B1%E8%AE%A4%E5%AE%9A%E7%9A%84%E5%AE%B6%E7%94%A8SUV%23) `193.7K 🔥` `NEW`
1. [启动新一轮双一流建设](https://s.weibo.com/weibo?q=%23%E5%90%AF%E5%8A%A8%E6%96%B0%E4%B8%80%E8%BD%AE%E5%8F%8C%E4%B8%80%E6%B5%81%E5%BB%BA%E8%AE%BE%23) `192.0K 🔥` `NEW`
1. [极简版政府工作报告](https://s.weibo.com/weibo?q=%23%E6%9E%81%E7%AE%80%E7%89%88%E6%94%BF%E5%BA%9C%E5%B7%A5%E4%BD%9C%E6%8A%A5%E5%91%8A%23) `185.7K 🔥` `NEW`
1. [政府工作报告](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%BA%9C%E5%B7%A5%E4%BD%9C%E6%8A%A5%E5%91%8A%23) `183.5K 🔥` `NEW`
1. [原著里方穆静是妍妍的偶像 (In the original work, Fang Mujing is Yanyan’s idol)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E8%91%97%E9%87%8C%E6%96%B9%E7%A9%86%E9%9D%99%E6%98%AF%E5%A6%8D%E5%A6%8D%E7%9A%84%E5%81%B6%E5%83%8F%23) `176.8K 🔥` `NEW`
1. [女子毕业时120斤工作后胖到200斤](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%AF%95%E4%B8%9A%E6%97%B6120%E6%96%A4%E5%B7%A5%E4%BD%9C%E5%90%8E%E8%83%96%E5%88%B0200%E6%96%A4%23) `172.8K 🔥` `NEW`
1. [喊卡了姐夫还来个额头吻](https://s.weibo.com/weibo?q=%23%E5%96%8A%E5%8D%A1%E4%BA%86%E5%A7%90%E5%A4%AB%E8%BF%98%E6%9D%A5%E4%B8%AA%E9%A2%9D%E5%A4%B4%E5%90%BB%23) `170.5K 🔥` `NEW`
1. [我国经济顶压前行展现强大韧性](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E7%BB%8F%E6%B5%8E%E9%A1%B6%E5%8E%8B%E5%89%8D%E8%A1%8C%E5%B1%95%E7%8E%B0%E5%BC%BA%E5%A4%A7%E9%9F%A7%E6%80%A7%23) `150.6K 🔥` `NEW`
1. [狗狗追车几公里上车后生下狗宝宝](https://s.weibo.com/weibo?q=%23%E7%8B%97%E7%8B%97%E8%BF%BD%E8%BD%A6%E5%87%A0%E5%85%AC%E9%87%8C%E4%B8%8A%E8%BD%A6%E5%90%8E%E7%94%9F%E4%B8%8B%E7%8B%97%E5%AE%9D%E5%AE%9D%23) `150.0K 🔥` `NEW`
1. [十四届全国人大四次会议开幕会](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E5%BC%80%E5%B9%95%E4%BC%9A%23) `150.0K 🔥` `NEW`
1. [南方绿化带是要考研吗](https://s.weibo.com/weibo?q=%23%E5%8D%97%E6%96%B9%E7%BB%BF%E5%8C%96%E5%B8%A6%E6%98%AF%E8%A6%81%E8%80%83%E7%A0%94%E5%90%97%23) `113.4K 🔥` `NEW`
1. [雷军回应小米手机是否涨价](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%9B%9E%E5%BA%94%E5%B0%8F%E7%B1%B3%E6%89%8B%E6%9C%BA%E6%98%AF%E5%90%A6%E6%B6%A8%E4%BB%B7%23) `109.0K 🔥` `NEW`
1. [培育发展脑机接口等未来产业](https://s.weibo.com/weibo?q=%23%E5%9F%B9%E8%82%B2%E5%8F%91%E5%B1%95%E8%84%91%E6%9C%BA%E6%8E%A5%E5%8F%A3%E7%AD%89%E6%9C%AA%E6%9D%A5%E4%BA%A7%E4%B8%9A%23) `108.0K 🔥` `NEW`
1. [岳雨婷时装周出片质量](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E6%97%B6%E8%A3%85%E5%91%A8%E5%87%BA%E7%89%87%E8%B4%A8%E9%87%8F%23) `107.3K 🔥` `NEW`
1. [加强初婚初育住房保障 (Strengthen housing security for first marriages and first children)](https://s.weibo.com/weibo?q=%23%E5%8A%A0%E5%BC%BA%E5%88%9D%E5%A9%9A%E5%88%9D%E8%82%B2%E4%BD%8F%E6%88%BF%E4%BF%9D%E9%9A%9C%23) `105.9K 🔥` `NEW`
1. [周杰伦或将本月发新专辑](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%88%96%E5%B0%86%E6%9C%AC%E6%9C%88%E5%8F%91%E6%96%B0%E4%B8%93%E8%BE%91%23) `96.7K 🔥` `NEW`
1. [2026KPL春季赛第三轮赛程](https://s.weibo.com/weibo?q=%232026KPL%E6%98%A5%E5%AD%A3%E8%B5%9B%E7%AC%AC%E4%B8%89%E8%BD%AE%E8%B5%9B%E7%A8%8B%23) `95.4K 🔥` `NEW`
1. [上班vlog到底是谁在拍](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%ADvlog%E5%88%B0%E5%BA%95%E6%98%AF%E8%B0%81%E5%9C%A8%E6%8B%8D%23) `94.5K 🔥` `NEW`
1. [落实职工带薪错峰休假制度](https://s.weibo.com/weibo?q=%23%E8%90%BD%E5%AE%9E%E8%81%8C%E5%B7%A5%E5%B8%A6%E8%96%AA%E9%94%99%E5%B3%B0%E4%BC%91%E5%81%87%E5%88%B6%E5%BA%A6%23) `87.9K 🔥` `NEW`
1. [i人出门就小猫这样](https://s.weibo.com/weibo?q=%23i%E4%BA%BA%E5%87%BA%E9%97%A8%E5%B0%B1%E5%B0%8F%E7%8C%AB%E8%BF%99%E6%A0%B7%23) `87.8K 🔥` `NEW`
1. [居民医保人均补助标准提高24元](https://s.weibo.com/weibo?q=%23%E5%B1%85%E6%B0%91%E5%8C%BB%E4%BF%9D%E4%BA%BA%E5%9D%87%E8%A1%A5%E5%8A%A9%E6%A0%87%E5%87%86%E6%8F%90%E9%AB%9824%E5%85%83%23) `87.8K 🔥` `NEW`
1. [医院回应63岁高龄孕妇产女](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E9%99%A2%E5%9B%9E%E5%BA%9463%E5%B2%81%E9%AB%98%E9%BE%84%E5%AD%95%E5%A6%87%E4%BA%A7%E5%A5%B3%23) `87.8K 🔥` `NEW`
1. [曝十日终焉领衔主演艾米](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E9%A2%86%E8%A1%94%E4%B8%BB%E6%BC%94%E8%89%BE%E7%B1%B3%23) `136.3K 🔥` `+69%`
1. [伊朗袭击以国防部大楼](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%E4%BB%A5%E5%9B%BD%E9%98%B2%E9%83%A8%E5%A4%A7%E6%A5%BC%23) `453.9K 🔥`
1. [没见过气血虚成这样的 (I have never seen such a person with Qi and blood deficiency.)](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E8%A7%81%E8%BF%87%E6%B0%94%E8%A1%80%E8%99%9A%E6%88%90%E8%BF%99%E6%A0%B7%E7%9A%84%23) `240.9K 🔥`
1. [苹果新品 (Apple new products)](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%96%B0%E5%93%81%23) `93.7K 🔥`
1. [普京说考虑主动给欧洲断气](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E8%AF%B4%E8%80%83%E8%99%91%E4%B8%BB%E5%8A%A8%E7%BB%99%E6%AC%A7%E6%B4%B2%E6%96%AD%E6%B0%94%23) `214.2K 🔥` `-63%`
1. [迪丽热巴报平安](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%8A%A5%E5%B9%B3%E5%AE%89%23) `178.3K 🔥` `-21%`
1. [物业费越来越难收](https://s.weibo.com/weibo?q=%23%E7%89%A9%E4%B8%9A%E8%B4%B9%E8%B6%8A%E6%9D%A5%E8%B6%8A%E9%9A%BE%E6%94%B6%23) `169.9K 🔥` `-79%`
1. [曝十日终焉主演王天辰](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E4%B8%BB%E6%BC%94%E7%8E%8B%E5%A4%A9%E8%BE%B0%23) `148.5K 🔥` `-47%`
1. [惊蛰](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%23) `140.2K 🔥` `-48%`
1. [什么水果一听就很东北](https://s.weibo.com/weibo?q=%23%E4%BB%80%E4%B9%88%E6%B0%B4%E6%9E%9C%E4%B8%80%E5%90%AC%E5%B0%B1%E5%BE%88%E4%B8%9C%E5%8C%97%23) `119.5K 🔥` `-67%`
1. [第一场代表通道采访](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E5%9C%BA%E4%BB%A3%E8%A1%A8%E9%80%9A%E9%81%93%E9%87%87%E8%AE%BF%23) `116.5K 🔥` `-59%`
1. [伊朗沉没军舰已找到80具遗体](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%B2%89%E6%B2%A1%E5%86%9B%E8%88%B0%E5%B7%B2%E6%89%BE%E5%88%B080%E5%85%B7%E9%81%97%E4%BD%93%23) `91.7K 🔥` `-54%`
1. [微信转账1万没写借条同学不还钱了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%BD%AC%E8%B4%A61%E4%B8%87%E6%B2%A1%E5%86%99%E5%80%9F%E6%9D%A1%E5%90%8C%E5%AD%A6%E4%B8%8D%E8%BF%98%E9%92%B1%E4%BA%86%23) `89.5K 🔥` `-54%`
1. [在中国式现代化新征程上策马奔腾 (Galloping forward on the new journey of Chinese-style modernization)](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E4%B8%AD%E5%9B%BD%E5%BC%8F%E7%8E%B0%E4%BB%A3%E5%8C%96%E6%96%B0%E5%BE%81%E7%A8%8B%E4%B8%8A%E7%AD%96%E9%A9%AC%E5%A5%94%E8%85%BE%23) `87.8K 🔥` `-86%`

Updated at 2026-03-05 11:30:31

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
