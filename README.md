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

1. [考研查分 (Postgraduate entrance examination score check)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E6%9F%A5%E5%88%86%23) `1.2M 🔥` `NEW`
1. [国家线 砍一刀](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%AE%B6%E7%BA%BF%20%E7%A0%8D%E4%B8%80%E5%88%80%23) `871.1K 🔥` `NEW`
1. [伊朗同意不拥有可制造核弹的核材料](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%8C%E6%84%8F%E4%B8%8D%E6%8B%A5%E6%9C%89%E5%8F%AF%E5%88%B6%E9%80%A0%E6%A0%B8%E5%BC%B9%E7%9A%84%E6%A0%B8%E6%9D%90%E6%96%99%23) `396.1K 🔥` `NEW`
1. [李在明低价卖房](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%9C%A8%E6%98%8E%E4%BD%8E%E4%BB%B7%E5%8D%96%E6%88%BF%23) `226.5K 🔥` `NEW`
1. [女子28元买黄金贴纸折算克价1.4万](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%9028%E5%85%83%E4%B9%B0%E9%BB%84%E9%87%91%E8%B4%B4%E7%BA%B8%E6%8A%98%E7%AE%97%E5%85%8B%E4%BB%B71.4%E4%B8%87%23) `202.6K 🔥` `NEW`
1. [湖南县委书记个人账号变问政现场](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E5%8E%BF%E5%A7%94%E4%B9%A6%E8%AE%B0%E4%B8%AA%E4%BA%BA%E8%B4%A6%E5%8F%B7%E5%8F%98%E9%97%AE%E6%94%BF%E7%8E%B0%E5%9C%BA%23) `186.0K 🔥` `NEW`
1. [玻利维亚军机失事造成至少15人死亡](https://s.weibo.com/weibo?q=%23%E7%8E%BB%E5%88%A9%E7%BB%B4%E4%BA%9A%E5%86%9B%E6%9C%BA%E5%A4%B1%E4%BA%8B%E9%80%A0%E6%88%90%E8%87%B3%E5%B0%9115%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `177.3K 🔥` `NEW`
1. [乐华娱乐声明](https://s.weibo.com/weibo?q=%23%E4%B9%90%E5%8D%8E%E5%A8%B1%E4%B9%90%E5%A3%B0%E6%98%8E%23) `175.4K 🔥` `NEW`
1. [血脂超标的5个常见信号](https://s.weibo.com/weibo?q=%23%E8%A1%80%E8%84%82%E8%B6%85%E6%A0%87%E7%9A%845%E4%B8%AA%E5%B8%B8%E8%A7%81%E4%BF%A1%E5%8F%B7%23) `113.9K 🔥` `NEW`
1. [朝鲜深夜大阅兵](https://s.weibo.com/weibo?q=%23%E6%9C%9D%E9%B2%9C%E6%B7%B1%E5%A4%9C%E5%A4%A7%E9%98%85%E5%85%B5%23) `108.8K 🔥` `NEW`
1. [医生乘机突发不适欲广播寻药遭拒 (Taking advantage of the opportunity, the doctor suddenly felt unwell and attempted to broadcast a request for medicine, but was rejected.)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E4%B9%98%E6%9C%BA%E7%AA%81%E5%8F%91%E4%B8%8D%E9%80%82%E6%AC%B2%E5%B9%BF%E6%92%AD%E5%AF%BB%E8%8D%AF%E9%81%AD%E6%8B%92%23) `103.6K 🔥` `NEW`
1. [50岁女子晒生日照状态惊艳](https://s.weibo.com/weibo?q=%2350%E5%B2%81%E5%A5%B3%E5%AD%90%E6%99%92%E7%94%9F%E6%97%A5%E7%85%A7%E7%8A%B6%E6%80%81%E6%83%8A%E8%89%B3%23) `100.2K 🔥` `NEW`
1. [考研上岸](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E4%B8%8A%E5%B2%B8%23) `98.8K 🔥` `NEW`
1. [真的不建议把肉泡在水里解冻](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E7%9A%84%E4%B8%8D%E5%BB%BA%E8%AE%AE%E6%8A%8A%E8%82%89%E6%B3%A1%E5%9C%A8%E6%B0%B4%E9%87%8C%E8%A7%A3%E5%86%BB%23) `98.7K 🔥` `NEW`
1. [金价波动](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%B3%A2%E5%8A%A8%23) `88.3K 🔥` `NEW`
1. [金正恩向主要领导干部赠送狙击步枪](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E5%90%91%E4%B8%BB%E8%A6%81%E9%A2%86%E5%AF%BC%E5%B9%B2%E9%83%A8%E8%B5%A0%E9%80%81%E7%8B%99%E5%87%BB%E6%AD%A5%E6%9E%AA%23) `87.5K 🔥` `NEW`
1. [有手机店一天卖10多台魅族22](https://s.weibo.com/weibo?q=%23%E6%9C%89%E6%89%8B%E6%9C%BA%E5%BA%97%E4%B8%80%E5%A4%A9%E5%8D%9610%E5%A4%9A%E5%8F%B0%E9%AD%85%E6%97%8F22%23) `86.4K 🔥` `NEW`
1. [张翅直播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%BF%85%E7%9B%B4%E6%92%AD%23) `80.2K 🔥` `NEW`
1. [关注2026全国两会 (Pay attention to the 2026 National Two Sessions)](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%B3%A82026%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%23) `702.4K 🔥` `+24%`
1. [21岁女生头晕以为没睡好查出脑梗 (A 21-year-old girl felt dizzy and thought she hadn’t slept well and was diagnosed with cerebral infarction)](https://s.weibo.com/weibo?q=%2321%E5%B2%81%E5%A5%B3%E7%94%9F%E5%A4%B4%E6%99%95%E4%BB%A5%E4%B8%BA%E6%B2%A1%E7%9D%A1%E5%A5%BD%E6%9F%A5%E5%87%BA%E8%84%91%E6%A2%97%23) `299.7K 🔥` `+46%`
1. [徐福记回应米兰小伙求代购酥心糖](https://s.weibo.com/weibo?q=%23%E5%BE%90%E7%A6%8F%E8%AE%B0%E5%9B%9E%E5%BA%94%E7%B1%B3%E5%85%B0%E5%B0%8F%E4%BC%99%E6%B1%82%E4%BB%A3%E8%B4%AD%E9%85%A5%E5%BF%83%E7%B3%96%23) `211.1K 🔥` `+42%`
1. [反诈老陈因多次违规被罚 (Anti-fraud veteran Chen was fined for multiple violations)](https://s.weibo.com/weibo?q=%23%E5%8F%8D%E8%AF%88%E8%80%81%E9%99%88%E5%9B%A0%E5%A4%9A%E6%AC%A1%E8%BF%9D%E8%A7%84%E8%A2%AB%E7%BD%9A%23) `210.2K 🔥` `+28%`
1. [范丞丞方说不认识没交集](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E6%96%B9%E8%AF%B4%E4%B8%8D%E8%AE%A4%E8%AF%86%E6%B2%A1%E4%BA%A4%E9%9B%86%23) `201.8K 🔥` `+60%`
1. [Angelababy37岁了 (Angelababy is 37 years old)](https://s.weibo.com/weibo?q=%23Angelababy37%E5%B2%81%E4%BA%86%23) `198.7K 🔥` `+76%`
1. [美国 伊朗 (United States Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%20%E4%BC%8A%E6%9C%97%23) `197.2K 🔥` `+54%`
1. [迪丽热巴成立个人工作室](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%88%90%E7%AB%8B%E4%B8%AA%E4%BA%BA%E5%B7%A5%E4%BD%9C%E5%AE%A4%23) `194.8K 🔥` `+58%`
1. [库迪向王一博致歉](https://s.weibo.com/weibo?q=%23%E5%BA%93%E8%BF%AA%E5%90%91%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%87%B4%E6%AD%89%23) `192.0K 🔥` `+63%`
1. [23岁研究生胃癌晚期称作息不规律 (A 23-year-old graduate student with advanced gastric cancer said he had irregular breathing)](https://s.weibo.com/weibo?q=%2323%E5%B2%81%E7%A0%94%E7%A9%B6%E7%94%9F%E8%83%83%E7%99%8C%E6%99%9A%E6%9C%9F%E7%A7%B0%E4%BD%9C%E6%81%AF%E4%B8%8D%E8%A7%84%E5%BE%8B%23) `188.4K 🔥` `+49%`
1. [姐姐姐夫加起来的戏份还没广告长](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%E5%8A%A0%E8%B5%B7%E6%9D%A5%E7%9A%84%E6%88%8F%E4%BB%BD%E8%BF%98%E6%B2%A1%E5%B9%BF%E5%91%8A%E9%95%BF%23) `186.4K 🔥` `+310%`
1. [伊朗 (Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `179.7K 🔥` `+51%`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `176.4K 🔥` `+39%`
1. [全球第一大毒贩被毙引发大规模报复](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E7%AC%AC%E4%B8%80%E5%A4%A7%E6%AF%92%E8%B4%A9%E8%A2%AB%E6%AF%99%E5%BC%95%E5%8F%91%E5%A4%A7%E8%A7%84%E6%A8%A1%E6%8A%A5%E5%A4%8D%23) `176.3K 🔥` `+47%`
1. [昭阳公主造型被指抄袭 (Princess Zhaoyang’s style was accused of plagiarism)](https://s.weibo.com/weibo?q=%23%E6%98%AD%E9%98%B3%E5%85%AC%E4%B8%BB%E9%80%A0%E5%9E%8B%E8%A2%AB%E6%8C%87%E6%8A%84%E8%A2%AD%23) `169.7K 🔥` `+32%`
1. [全红婵直播澄清自己没有不学习](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E7%9B%B4%E6%92%AD%E6%BE%84%E6%B8%85%E8%87%AA%E5%B7%B1%E6%B2%A1%E6%9C%89%E4%B8%8D%E5%AD%A6%E4%B9%A0%23) `162.9K 🔥` `+211%`
1. [杨洋发文回应不让江山争议 (Yang Yang issued an article in response to the controversy about not letting the country go)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E4%BA%89%E8%AE%AE%23) `156.3K 🔥` `+32%`
1. [种地吧 (Farm it)](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `128.6K 🔥` `+128%`
1. [黄金白银又涨爆了 (Gold and silver are soaring again)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E5%8F%88%E6%B6%A8%E7%88%86%E4%BA%86%23) `122.1K 🔥` `+104%`
1. [这些素菜其实都是吸油大户](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%BA%9B%E7%B4%A0%E8%8F%9C%E5%85%B6%E5%AE%9E%E9%83%BD%E6%98%AF%E5%90%B8%E6%B2%B9%E5%A4%A7%E6%88%B7%23) `96.9K 🔥` `+57%`
1. [巴拿马突击搜查中资港口办公室](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E6%8B%BF%E9%A9%AC%E7%AA%81%E5%87%BB%E6%90%9C%E6%9F%A5%E4%B8%AD%E8%B5%84%E6%B8%AF%E5%8F%A3%E5%8A%9E%E5%85%AC%E5%AE%A4%23) `92.0K 🔥` `+26%`
1. [政府借厕所遭辱骂男子要求公开道歉 (Man insulted after using government toilet to demand public apology)](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%BA%9C%E5%80%9F%E5%8E%95%E6%89%80%E9%81%AD%E8%BE%B1%E9%AA%82%E7%94%B7%E5%AD%90%E8%A6%81%E6%B1%82%E5%85%AC%E5%BC%80%E9%81%93%E6%AD%89%23) `136.5K 🔥`
1. [白宇刘萌萌2014年因戏结缘 (Bai Yu and Liu Mengmeng got to know each other through drama in 2014)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%87%E5%88%98%E8%90%8C%E8%90%8C2014%E5%B9%B4%E5%9B%A0%E6%88%8F%E7%BB%93%E7%BC%98%23) `134.5K 🔥`
1. [上一个离开嘉行的是祝绪丹 (The last person to leave Jiaxing was Zhu Xudan)](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E4%B8%80%E4%B8%AA%E7%A6%BB%E5%BC%80%E5%98%89%E8%A1%8C%E7%9A%84%E6%98%AF%E7%A5%9D%E7%BB%AA%E4%B8%B9%23) `120.6K 🔥`
1. [杨幂谷爱凌合照 好娇啊小幂 (A group photo of Yang Mi, Gu Ailing, so cute, Xiaomi)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%B0%B7%E7%88%B1%E5%87%8C%E5%90%88%E7%85%A7%20%E5%A5%BD%E5%A8%87%E5%95%8A%E5%B0%8F%E5%B9%82%23) `117.9K 🔥`
1. [当妈妈把欧洲特产蒸了后 (When my mother steamed European specialties)](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%A6%88%E5%A6%88%E6%8A%8A%E6%AC%A7%E6%B4%B2%E7%89%B9%E4%BA%A7%E8%92%B8%E4%BA%86%E5%90%8E%23) `114.6K 🔥`
1. [全网最黑大熊猫洗白白后什么样](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BD%91%E6%9C%80%E9%BB%91%E5%A4%A7%E7%86%8A%E7%8C%AB%E6%B4%97%E7%99%BD%E7%99%BD%E5%90%8E%E4%BB%80%E4%B9%88%E6%A0%B7%23) `90.3K 🔥`
1. [考研今天出分 (Postgraduate entrance exam scores are out today)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E4%BB%8A%E5%A4%A9%E5%87%BA%E5%88%86%23) `430.6K 🔥` `-56%`
1. [有美国入侵伊拉克时的味道了 (It smells like when the United States invaded Iraq)](https://s.weibo.com/weibo?q=%23%E6%9C%89%E7%BE%8E%E5%9B%BD%E5%85%A5%E4%BE%B5%E4%BC%8A%E6%8B%89%E5%85%8B%E6%97%B6%E7%9A%84%E5%91%B3%E9%81%93%E4%BA%86%23) `116.0K 🔥` `-83%`
1. [高市早苗反对女天皇 (Sanae Takaichi opposes the female emperor)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%8F%8D%E5%AF%B9%E5%A5%B3%E5%A4%A9%E7%9A%87%23) `94.8K 🔥` `-24%`
1. [奥黛丽厚本正完骨变薄本了 (Audrey's thick book is getting thinner)](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E9%BB%9B%E4%B8%BD%E5%8E%9A%E6%9C%AC%E6%AD%A3%E5%AE%8C%E9%AA%A8%E5%8F%98%E8%96%84%E6%9C%AC%E4%BA%86%23) `84.8K 🔥` `-27%`

Updated at 2026-02-28 09:13:37

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
