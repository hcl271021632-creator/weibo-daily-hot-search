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

1. [田曦薇张凌赫 二搭 (Tian Xiwei Zhang Linghe second partner)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E4%BA%8C%E6%90%AD%23) `601.3K 🔥` `NEW`
1. [谢征樊长玉被窝戏删掉了](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E8%A2%AB%E7%AA%9D%E6%88%8F%E5%88%A0%E6%8E%89%E4%BA%86%23) `595.1K 🔥` `NEW`
1. [谢征樊长玉生了两个孩子](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E7%94%9F%E4%BA%86%E4%B8%A4%E4%B8%AA%E5%AD%A9%E5%AD%90%23) `590.0K 🔥` `NEW`
1. [晋江文学城涉多起名誉权纠纷](https://s.weibo.com/weibo?q=%23%E6%99%8B%E6%B1%9F%E6%96%87%E5%AD%A6%E5%9F%8E%E6%B6%89%E5%A4%9A%E8%B5%B7%E5%90%8D%E8%AA%89%E6%9D%83%E7%BA%A0%E7%BA%B7%23) `583.3K 🔥` `NEW`
1. [叶璇聊张雪峰去世](https://s.weibo.com/weibo?q=%23%E5%8F%B6%E7%92%87%E8%81%8A%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%8E%BB%E4%B8%96%23) `582.7K 🔥` `NEW`
1. [林俊杰称自己生命的沙漏加速了](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E7%A7%B0%E8%87%AA%E5%B7%B1%E7%94%9F%E5%91%BD%E7%9A%84%E6%B2%99%E6%BC%8F%E5%8A%A0%E9%80%9F%E4%BA%86%23) `395.6K 🔥` `NEW`
1. [印度石油储备只够9.5天](https://s.weibo.com/weibo?q=%23%E5%8D%B0%E5%BA%A6%E7%9F%B3%E6%B2%B9%E5%82%A8%E5%A4%87%E5%8F%AA%E5%A4%9F9.5%E5%A4%A9%23) `186.2K 🔥` `NEW`
1. [美团第四季度净亏损150.8亿](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%A2%E7%AC%AC%E5%9B%9B%E5%AD%A3%E5%BA%A6%E5%87%80%E4%BA%8F%E6%8D%9F150.8%E4%BA%BF%23) `177.7K 🔥` `NEW`
1. [两艘055型驱逐舰将提升打击台独能力](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E8%89%98055%E5%9E%8B%E9%A9%B1%E9%80%90%E8%88%B0%E5%B0%86%E6%8F%90%E5%8D%87%E6%89%93%E5%87%BB%E5%8F%B0%E7%8B%AC%E8%83%BD%E5%8A%9B%23) `173.5K 🔥` `NEW`
1. [旧金山灭门案凶宅竟成抢手货](https://s.weibo.com/weibo?q=%23%E6%97%A7%E9%87%91%E5%B1%B1%E7%81%AD%E9%97%A8%E6%A1%88%E5%87%B6%E5%AE%85%E7%AB%9F%E6%88%90%E6%8A%A2%E6%89%8B%E8%B4%A7%23) `151.1K 🔥` `NEW`
1. [表白被拒坚信是欲擒故纵确诊桃花癫 (Confession rejected, convinced that he was playing hard to get and diagnosed with epilepsy)](https://s.weibo.com/weibo?q=%23%E8%A1%A8%E7%99%BD%E8%A2%AB%E6%8B%92%E5%9D%9A%E4%BF%A1%E6%98%AF%E6%AC%B2%E6%93%92%E6%95%85%E7%BA%B5%E7%A1%AE%E8%AF%8A%E6%A1%83%E8%8A%B1%E7%99%AB%23) `141.2K 🔥` `NEW`
1. [因抢玩具殴打2岁女童女子被行拘](https://s.weibo.com/weibo?q=%23%E5%9B%A0%E6%8A%A2%E7%8E%A9%E5%85%B7%E6%AE%B4%E6%89%932%E5%B2%81%E5%A5%B3%E7%AB%A5%E5%A5%B3%E5%AD%90%E8%A2%AB%E8%A1%8C%E6%8B%98%23) `137.1K 🔥` `NEW`
1. [韩国女子怒抢中国游客手机](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E5%A5%B3%E5%AD%90%E6%80%92%E6%8A%A2%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E6%89%8B%E6%9C%BA%23) `131.7K 🔥` `NEW`
1. [张凌赫田曦薇吻戏不用调](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E5%90%BB%E6%88%8F%E4%B8%8D%E7%94%A8%E8%B0%83%23) `77.5K 🔥` `NEW`
1. [银价跌爆了](https://s.weibo.com/weibo?q=%23%E9%93%B6%E4%BB%B7%E8%B7%8C%E7%88%86%E4%BA%86%23) `77.0K 🔥` `NEW`
1. [颜如晶曾找过25个教练减重均失败](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%A6%82%E6%99%B6%E6%9B%BE%E6%89%BE%E8%BF%8725%E4%B8%AA%E6%95%99%E7%BB%83%E5%87%8F%E9%87%8D%E5%9D%87%E5%A4%B1%E8%B4%A5%23) `77.0K 🔥` `NEW`
1. [伦敦世乒赛国乒选拔赛](https://s.weibo.com/weibo?q=%23%E4%BC%A6%E6%95%A6%E4%B8%96%E4%B9%92%E8%B5%9B%E5%9B%BD%E4%B9%92%E9%80%89%E6%8B%94%E8%B5%9B%23) `71.1K 🔥` `NEW`
1. [狗狗看到刀后忽然忙了起来](https://s.weibo.com/weibo?q=%23%E7%8B%97%E7%8B%97%E7%9C%8B%E5%88%B0%E5%88%80%E5%90%8E%E5%BF%BD%E7%84%B6%E5%BF%99%E4%BA%86%E8%B5%B7%E6%9D%A5%23) `70.3K 🔥` `NEW`
1. [晋江把发票设为屏蔽词](https://s.weibo.com/weibo?q=%23%E6%99%8B%E6%B1%9F%E6%8A%8A%E5%8F%91%E7%A5%A8%E8%AE%BE%E4%B8%BA%E5%B1%8F%E8%94%BD%E8%AF%8D%23) `66.3K 🔥` `NEW`
1. [中国无人飞枪曝光](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%97%A0%E4%BA%BA%E9%A3%9E%E6%9E%AA%E6%9B%9D%E5%85%89%23) `598.1K 🔥` `+150%`
1. [伊朗伊斯兰革命卫队海军指挥官身亡 (Iran's Islamic Revolutionary Guard Corps naval commander dies)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BC%8A%E6%96%AF%E5%85%B0%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E6%B5%B7%E5%86%9B%E6%8C%87%E6%8C%A5%E5%AE%98%E8%BA%AB%E4%BA%A1%23) `591.4K 🔥` `+147%`
1. [以后将只在周二网购](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%90%8E%E5%B0%86%E5%8F%AA%E5%9C%A8%E5%91%A8%E4%BA%8C%E7%BD%91%E8%B4%AD%23) `586.6K 🔥` `+146%`
1. [佛山电翰自曝收入 (Foshan Dianhan reveals his income)](https://s.weibo.com/weibo?q=%23%E4%BD%9B%E5%B1%B1%E7%94%B5%E7%BF%B0%E8%87%AA%E6%9B%9D%E6%94%B6%E5%85%A5%23) `229.5K 🔥` `+87%`
1. [留几手发文暗讽被全网炮轰](https://s.weibo.com/weibo?q=%23%E7%95%99%E5%87%A0%E6%89%8B%E5%8F%91%E6%96%87%E6%9A%97%E8%AE%BD%E8%A2%AB%E5%85%A8%E7%BD%91%E7%82%AE%E8%BD%B0%23) `180.5K 🔥` `+51%`
1. [郭敬明需要避谶](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%95%AC%E6%98%8E%E9%9C%80%E8%A6%81%E9%81%BF%E8%B0%B6%23) `171.2K 🔥` `+41%`
1. [我们一直把苹果放反了](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E4%B8%80%E7%9B%B4%E6%8A%8A%E8%8B%B9%E6%9E%9C%E6%94%BE%E5%8F%8D%E4%BA%86%23) `161.4K 🔥` `+34%`
1. [王一博 乐华](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%20%E4%B9%90%E5%8D%8E%23) `154.7K 🔥` `+31%`
1. [卧床35年女子顺利产下健康宝宝](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%8A35%E5%B9%B4%E5%A5%B3%E5%AD%90%E9%A1%BA%E5%88%A9%E4%BA%A7%E4%B8%8B%E5%81%A5%E5%BA%B7%E5%AE%9D%E5%AE%9D%23) `152.8K 🔥` `+23%`
1. [华晨宇排队吃烤鱼](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E6%99%A8%E5%AE%87%E6%8E%92%E9%98%9F%E5%90%83%E7%83%A4%E9%B1%BC%23) `119.0K 🔥` `+21%`
1. [早期心血管病可能反映在脸上 (Early cardiovascular disease may be reflected on the face)](https://s.weibo.com/weibo?q=%23%E6%97%A9%E6%9C%9F%E5%BF%83%E8%A1%80%E7%AE%A1%E7%97%85%E5%8F%AF%E8%83%BD%E5%8F%8D%E6%98%A0%E5%9C%A8%E8%84%B8%E4%B8%8A%23) `1.0M 🔥`
1. [内存条降价 (Memory module price reduction)](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%AD%98%E6%9D%A1%E9%99%8D%E4%BB%B7%23) `731.6K 🔥`
1. [七彩云南万千气象](https://s.weibo.com/weibo?q=%23%E4%B8%83%E5%BD%A9%E4%BA%91%E5%8D%97%E4%B8%87%E5%8D%83%E6%B0%94%E8%B1%A1%23) `602.1K 🔥`
1. [43岁不健身和61岁健身的区别](https://s.weibo.com/weibo?q=%2343%E5%B2%81%E4%B8%8D%E5%81%A5%E8%BA%AB%E5%92%8C61%E5%B2%81%E5%81%A5%E8%BA%AB%E7%9A%84%E5%8C%BA%E5%88%AB%23) `257.0K 🔥`
1. [逐玉大结局 (Chasing Jade Finale)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%A4%A7%E7%BB%93%E5%B1%80%23) `251.3K 🔥`
1. [女子买24元卤菜顺走40块钱大肠头](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%B024%E5%85%83%E5%8D%A4%E8%8F%9C%E9%A1%BA%E8%B5%B040%E5%9D%97%E9%92%B1%E5%A4%A7%E8%82%A0%E5%A4%B4%23) `126.6K 🔥`
1. [2026最吸金的星座](https://s.weibo.com/weibo?q=%232026%E6%9C%80%E5%90%B8%E9%87%91%E7%9A%84%E6%98%9F%E5%BA%A7%23) `117.1K 🔥`
1. [鹿晗校草时期 现实版流星花园](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E6%A0%A1%E8%8D%89%E6%97%B6%E6%9C%9F%20%E7%8E%B0%E5%AE%9E%E7%89%88%E6%B5%81%E6%98%9F%E8%8A%B1%E5%9B%AD%23) `75.9K 🔥`
1. [原来半大小子吃穷老子是真的](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%8D%8A%E5%A4%A7%E5%B0%8F%E5%AD%90%E5%90%83%E7%A9%B7%E8%80%81%E5%AD%90%E6%98%AF%E7%9C%9F%E7%9A%84%23) `67.3K 🔥`
1. [恋与深空短信](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%E7%9F%AD%E4%BF%A1%23) `178.5K 🔥` `-25%`
1. [董子健 我以前也是东北女婿](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AD%90%E5%81%A5%20%E6%88%91%E4%BB%A5%E5%89%8D%E4%B9%9F%E6%98%AF%E4%B8%9C%E5%8C%97%E5%A5%B3%E5%A9%BF%23) `171.9K 🔥` `-28%`
1. [孟子义腰比名牌细](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E8%85%B0%E6%AF%94%E5%90%8D%E7%89%8C%E7%BB%86%23) `152.6K 🔥` `-36%`
1. [王俊凯 演唱会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%20%E6%BC%94%E5%94%B1%E4%BC%9A%23) `105.0K 🔥` `-39%`
1. [张远真去做了魏哲鸣的嘉宾](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%BF%9C%E7%9C%9F%E5%8E%BB%E5%81%9A%E4%BA%86%E9%AD%8F%E5%93%B2%E9%B8%A3%E7%9A%84%E5%98%89%E5%AE%BE%23) `85.3K 🔥` `-30%`
1. [中方回应是否禁止Manus两高管离境 (China responds to whether to ban two Manus executives from leaving the country)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E6%98%AF%E5%90%A6%E7%A6%81%E6%AD%A2Manus%E4%B8%A4%E9%AB%98%E7%AE%A1%E7%A6%BB%E5%A2%83%23) `78.4K 🔥` `-63%`
1. [小猫一气之下怒吃了两口冻干 (The kitten ate two bites of freeze-dried food in anger.)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E4%B8%80%E6%B0%94%E4%B9%8B%E4%B8%8B%E6%80%92%E5%90%83%E4%BA%86%E4%B8%A4%E5%8F%A3%E5%86%BB%E5%B9%B2%23) `78.0K 🔥` `-33%`
1. [王俊凯卡点521](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E5%8D%A1%E7%82%B9521%23) `77.4K 🔥` `-33%`
1. [孟子义差点上到李昀锐车上 (Meng Ziyi almost got on Li Yunrui’s car)](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E5%B7%AE%E7%82%B9%E4%B8%8A%E5%88%B0%E6%9D%8E%E6%98%80%E9%94%90%E8%BD%A6%E4%B8%8A%23) `70.9K 🔥` `-70%`
1. [黄晓明回应没考上博士](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E5%9B%9E%E5%BA%94%E6%B2%A1%E8%80%83%E4%B8%8A%E5%8D%9A%E5%A3%AB%23) `68.0K 🔥` `-42%`
1. [心疼清融](https://s.weibo.com/weibo?q=%23%E5%BF%83%E7%96%BC%E6%B8%85%E8%9E%8D%23) `64.7K 🔥` `-49%`

Updated at 2026-03-26 20:38:08

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
