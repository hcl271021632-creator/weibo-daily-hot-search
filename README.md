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

1. [央视公布梅姨案细节 (CCTV releases details of Aunt Mei’s case)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E5%85%AC%E5%B8%83%E6%A2%85%E5%A7%A8%E6%A1%88%E7%BB%86%E8%8A%82%23) `1.1M 🔥` `NEW`
1. [千问上线AI打车](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E4%B8%8A%E7%BA%BFAI%E6%89%93%E8%BD%A6%23) `709.0K 🔥` `NEW`
1. [老中医离世后儿子上交460g罂粟壳](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%B8%AD%E5%8C%BB%E7%A6%BB%E4%B8%96%E5%90%8E%E5%84%BF%E5%AD%90%E4%B8%8A%E4%BA%A4460g%E7%BD%82%E7%B2%9F%E5%A3%B3%23) `707.5K 🔥` `NEW`
1. [日本教授中国旅游后感叹日本变态](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%95%99%E6%8E%88%E4%B8%AD%E5%9B%BD%E6%97%85%E6%B8%B8%E5%90%8E%E6%84%9F%E5%8F%B9%E6%97%A5%E6%9C%AC%E5%8F%98%E6%80%81%23) `698.9K 🔥` `NEW`
1. [托马斯谢尔比来中国啦](https://s.weibo.com/weibo?q=%23%E6%89%98%E9%A9%AC%E6%96%AF%E8%B0%A2%E5%B0%94%E6%AF%94%E6%9D%A5%E4%B8%AD%E5%9B%BD%E5%95%A6%23) `481.1K 🔥` `NEW`
1. [郑合惠子将门毒后妆造](https://s.weibo.com/weibo?q=%23%E9%83%91%E5%90%88%E6%83%A0%E5%AD%90%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%E5%A6%86%E9%80%A0%23) `401.2K 🔥` `NEW`
1. [金价波动](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%B3%A2%E5%8A%A8%23) `342.2K 🔥` `NEW`
1. [网传郭晓婷王天辰合作现偶](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E9%83%AD%E6%99%93%E5%A9%B7%E7%8E%8B%E5%A4%A9%E8%BE%B0%E5%90%88%E4%BD%9C%E7%8E%B0%E5%81%B6%23) `213.7K 🔥` `NEW`
1. [弟弟偷抵32万新车哥哥气炸](https://s.weibo.com/weibo?q=%23%E5%BC%9F%E5%BC%9F%E5%81%B7%E6%8A%B532%E4%B8%87%E6%96%B0%E8%BD%A6%E5%93%A5%E5%93%A5%E6%B0%94%E7%82%B8%23) `203.4K 🔥` `NEW`
1. [黄金猴市来了](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%8C%B4%E5%B8%82%E6%9D%A5%E4%BA%86%23) `152.9K 🔥` `NEW`
1. [2邻居共装9个摄像头互相拍摄 (2 neighbors installed a total of 9 cameras to film each other)](https://s.weibo.com/weibo?q=%232%E9%82%BB%E5%B1%85%E5%85%B1%E8%A3%859%E4%B8%AA%E6%91%84%E5%83%8F%E5%A4%B4%E4%BA%92%E7%9B%B8%E6%8B%8D%E6%91%84%23) `135.3K 🔥` `NEW`
1. [教育局回应毕节学生2死11伤](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%82%B2%E5%B1%80%E5%9B%9E%E5%BA%94%E6%AF%95%E8%8A%82%E5%AD%A6%E7%94%9F2%E6%AD%BB11%E4%BC%A4%23) `133.7K 🔥` `NEW`
1. [金价重回3位数](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E9%87%8D%E5%9B%9E3%E4%BD%8D%E6%95%B0%23) `117.2K 🔥` `NEW`
1. [两只狗吃了一整板布洛芬](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E5%8F%AA%E7%8B%97%E5%90%83%E4%BA%86%E4%B8%80%E6%95%B4%E6%9D%BF%E5%B8%83%E6%B4%9B%E8%8A%AC%23) `110.9K 🔥` `NEW`
1. [在以中国公民摒弃侥幸心理尽快撤离](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E4%BB%A5%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E6%91%92%E5%BC%83%E4%BE%A5%E5%B9%B8%E5%BF%83%E7%90%86%E5%B0%BD%E5%BF%AB%E6%92%A4%E7%A6%BB%23) `106.7K 🔥` `NEW`
1. [伊朗用升级后的作战系统打击美以](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%94%A8%E5%8D%87%E7%BA%A7%E5%90%8E%E7%9A%84%E4%BD%9C%E6%88%98%E7%B3%BB%E7%BB%9F%E6%89%93%E5%87%BB%E7%BE%8E%E4%BB%A5%23) `99.6K 🔥` `NEW`
1. [KPL巅峰对决提速了](https://s.weibo.com/weibo?q=%23KPL%E5%B7%85%E5%B3%B0%E5%AF%B9%E5%86%B3%E6%8F%90%E9%80%9F%E4%BA%86%23) `88.9K 🔥` `NEW`
1. [老太闯入货车盲区被碾压身亡](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%A4%AA%E9%97%AF%E5%85%A5%E8%B4%A7%E8%BD%A6%E7%9B%B2%E5%8C%BA%E8%A2%AB%E7%A2%BE%E5%8E%8B%E8%BA%AB%E4%BA%A1%23) `80.2K 🔥` `NEW`
1. [眉姐姐来卖丑衣服了](https://s.weibo.com/weibo?q=%23%E7%9C%89%E5%A7%90%E5%A7%90%E6%9D%A5%E5%8D%96%E4%B8%91%E8%A1%A3%E6%9C%8D%E4%BA%86%23) `78.6K 🔥` `NEW`
1. [徐若晗去桃花坞养猪了](https://s.weibo.com/weibo?q=%23%E5%BE%90%E8%8B%A5%E6%99%97%E5%8E%BB%E6%A1%83%E8%8A%B1%E5%9D%9E%E5%85%BB%E7%8C%AA%E4%BA%86%23) `76.6K 🔥` `NEW`
1. [315曝光增高骗局涉事公司拟注销 (315 exposed the increase scam and the company involved planned to cancel)](https://s.weibo.com/weibo?q=%23315%E6%9B%9D%E5%85%89%E5%A2%9E%E9%AB%98%E9%AA%97%E5%B1%80%E6%B6%89%E4%BA%8B%E5%85%AC%E5%8F%B8%E6%8B%9F%E6%B3%A8%E9%94%80%23) `76.5K 🔥` `NEW`
1. [逐玉男模团](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%94%B7%E6%A8%A1%E5%9B%A2%23) `76.5K 🔥` `NEW`
1. [孔雪儿说孟子义的萌点是爱吃小零食](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E8%AF%B4%E5%AD%9F%E5%AD%90%E4%B9%89%E7%9A%84%E8%90%8C%E7%82%B9%E6%98%AF%E7%88%B1%E5%90%83%E5%B0%8F%E9%9B%B6%E9%A3%9F%23) `74.2K 🔥` `NEW`
1. [A股半日成交1.46万亿放量155亿](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E5%8D%8A%E6%97%A5%E6%88%90%E4%BA%A41.46%E4%B8%87%E4%BA%BF%E6%94%BE%E9%87%8F155%E4%BA%BF%23) `70.6K 🔥` `NEW`
1. [王安宇杂志开售](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E6%9D%82%E5%BF%97%E5%BC%80%E5%94%AE%23) `69.9K 🔥` `NEW`
1. [梅姨每交易1名儿童拿1000元介绍费 (Aunt Mei gets an introduction fee of 1,000 yuan for every child she trades.)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E6%AF%8F%E4%BA%A4%E6%98%931%E5%90%8D%E5%84%BF%E7%AB%A5%E6%8B%BF1000%E5%85%83%E4%BB%8B%E7%BB%8D%E8%B4%B9%23) `790.7K 🔥` `+263%`
1. [伊朗导弹上写着感谢西班牙首相](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E4%B8%8A%E5%86%99%E7%9D%80%E6%84%9F%E8%B0%A2%E8%A5%BF%E7%8F%AD%E7%89%99%E9%A6%96%E7%9B%B8%23) `695.9K 🔥` `+347%`
1. [熟人羞耻症](https://s.weibo.com/weibo?q=%23%E7%86%9F%E4%BA%BA%E7%BE%9E%E8%80%BB%E7%97%87%23) `472.1K 🔥` `+354%`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `339.0K 🔥` `+165%`
1. [长期喝桶装水的人天塌了](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E5%96%9D%E6%A1%B6%E8%A3%85%E6%B0%B4%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `335.0K 🔥` `+221%`
1. [A股行情](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E8%A1%8C%E6%83%85%23) `333.5K 🔥` `+68%`
1. [何润东演的项羽 (Xiang Yu played by Peter Ho)](https://s.weibo.com/weibo?q=%23%E4%BD%95%E6%B6%A6%E4%B8%9C%E6%BC%94%E7%9A%84%E9%A1%B9%E7%BE%BD%23) `232.3K 🔥` `+46%`
1. [歼10总师不想让国家挨打](https://s.weibo.com/weibo?q=%23%E6%AD%BC10%E6%80%BB%E5%B8%88%E4%B8%8D%E6%83%B3%E8%AE%A9%E5%9B%BD%E5%AE%B6%E6%8C%A8%E6%89%93%23) `716.7K 🔥`
1. [张凌赫喜欢浴池吻 好糟糕的原因](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%96%9C%E6%AC%A2%E6%B5%B4%E6%B1%A0%E5%90%BB%20%E5%A5%BD%E7%B3%9F%E7%B3%95%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `229.8K 🔥`
1. [时代少年团 跑男](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%20%E8%B7%91%E7%94%B7%23) `208.3K 🔥`
1. [32岁孕妈怀孕后容貌变化明显 (32-year-old pregnant mother’s appearance changed significantly after pregnancy)](https://s.weibo.com/weibo?q=%2332%E5%B2%81%E5%AD%95%E5%A6%88%E6%80%80%E5%AD%95%E5%90%8E%E5%AE%B9%E8%B2%8C%E5%8F%98%E5%8C%96%E6%98%8E%E6%98%BE%23) `191.1K 🔥`
1. [女子脖子疼一周确诊胃癌已全身转移](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%84%96%E5%AD%90%E7%96%BC%E4%B8%80%E5%91%A8%E7%A1%AE%E8%AF%8A%E8%83%83%E7%99%8C%E5%B7%B2%E5%85%A8%E8%BA%AB%E8%BD%AC%E7%A7%BB%23) `169.3K 🔥`
1. [张峻豪致敬TFBOYS](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%B3%BB%E8%B1%AA%E8%87%B4%E6%95%ACTFBOYS%23) `160.3K 🔥`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `152.8K 🔥`
1. [股市](https://s.weibo.com/weibo?q=%23%E8%82%A1%E5%B8%82%23) `129.1K 🔥`
1. [田曦薇问张凌赫张哥你这什么妆造 (Tian Xiwei asked Zhang Linghe, Brother Zhang, what kind of makeup do you have?)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E9%97%AE%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%BC%A0%E5%93%A5%E4%BD%A0%E8%BF%99%E4%BB%80%E4%B9%88%E5%A6%86%E9%80%A0%23) `89.0K 🔥`
1. [逐玉豆瓣6.8](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%B1%86%E7%93%A36.8%23) `349.4K 🔥` `-39%`
1. [MBC告B站侵权胜诉](https://s.weibo.com/weibo?q=%23MBC%E5%91%8AB%E7%AB%99%E4%BE%B5%E6%9D%83%E8%83%9C%E8%AF%89%23) `344.1K 🔥` `-41%`
1. [贵州赫章交通事故致学生2死11伤 (Traffic accident in Hezhang, Guizhou kills 2 students and injures 11)](https://s.weibo.com/weibo?q=%23%E8%B4%B5%E5%B7%9E%E8%B5%AB%E7%AB%A0%E4%BA%A4%E9%80%9A%E4%BA%8B%E6%95%85%E8%87%B4%E5%AD%A6%E7%94%9F2%E6%AD%BB11%E4%BC%A4%23) `214.5K 🔥` `-80%`
1. [衣服穿人vs人穿衣服](https://s.weibo.com/weibo?q=%23%E8%A1%A3%E6%9C%8D%E7%A9%BF%E4%BA%BAvs%E4%BA%BA%E7%A9%BF%E8%A1%A3%E6%9C%8D%23) `105.8K 🔥` `-71%`
1. [国内金价跌破1000元 (Domestic gold price falls below 1,000 yuan)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%86%85%E9%87%91%E4%BB%B7%E8%B7%8C%E7%A0%B41000%E5%85%83%23) `97.9K 🔥` `-39%`
1. [郑合惠子在拍戏放弃去hi6女主剧宣](https://s.weibo.com/weibo?q=%23%E9%83%91%E5%90%88%E6%83%A0%E5%AD%90%E5%9C%A8%E6%8B%8D%E6%88%8F%E6%94%BE%E5%BC%83%E5%8E%BBhi6%E5%A5%B3%E4%B8%BB%E5%89%A7%E5%AE%A3%23) `92.8K 🔥` `-50%`
1. [桃花坞上新人了](https://s.weibo.com/weibo?q=%23%E6%A1%83%E8%8A%B1%E5%9D%9E%E4%B8%8A%E6%96%B0%E4%BA%BA%E4%BA%86%23) `85.2K 🔥` `-62%`
1. [美国一次次撒谎全世界买单 (The United States lies again and again and the whole world pays for it)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%80%E6%AC%A1%E6%AC%A1%E6%92%92%E8%B0%8E%E5%85%A8%E4%B8%96%E7%95%8C%E4%B9%B0%E5%8D%95%23) `81.5K 🔥` `-25%`
1. [黄金几乎抹去今年全部涨幅](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E5%87%A0%E4%B9%8E%E6%8A%B9%E5%8E%BB%E4%BB%8A%E5%B9%B4%E5%85%A8%E9%83%A8%E6%B6%A8%E5%B9%85%23) `79.5K 🔥` `-50%`
1. [Bin是世一上](https://s.weibo.com/weibo?q=%23Bin%E6%98%AF%E4%B8%96%E4%B8%80%E4%B8%8A%23) `76.8K 🔥` `-58%`
1. [龚俊新剧体制内女婿](https://s.weibo.com/weibo?q=%23%E9%BE%9A%E4%BF%8A%E6%96%B0%E5%89%A7%E4%BD%93%E5%88%B6%E5%86%85%E5%A5%B3%E5%A9%BF%23) `76.6K 🔥` `-26%`

Updated at 2026-03-23 13:59:31

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
