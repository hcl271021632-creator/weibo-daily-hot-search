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

1. [AI写作48小时生成500万字长篇小说 (AI writing generates a 5 million word novel in 48 hours)](https://s.weibo.com/weibo?q=%23AI%E5%86%99%E4%BD%9C48%E5%B0%8F%E6%97%B6%E7%94%9F%E6%88%90500%E4%B8%87%E5%AD%97%E9%95%BF%E7%AF%87%E5%B0%8F%E8%AF%B4%23) `526.6K 🔥` `NEW`
1. [外国游客到中国根本买不够](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%9B%BD%E6%B8%B8%E5%AE%A2%E5%88%B0%E4%B8%AD%E5%9B%BD%E6%A0%B9%E6%9C%AC%E4%B9%B0%E4%B8%8D%E5%A4%9F%23) `516.1K 🔥` `NEW`
1. [千万不能让小孩知道牙线还能这样玩](https://s.weibo.com/weibo?q=%23%E5%8D%83%E4%B8%87%E4%B8%8D%E8%83%BD%E8%AE%A9%E5%B0%8F%E5%AD%A9%E7%9F%A5%E9%81%93%E7%89%99%E7%BA%BF%E8%BF%98%E8%83%BD%E8%BF%99%E6%A0%B7%E7%8E%A9%23) `443.9K 🔥` `NEW`
1. [麦当劳CEO被质疑多次假吃吐掉汉堡](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E8%A2%AB%E8%B4%A8%E7%96%91%E5%A4%9A%E6%AC%A1%E5%81%87%E5%90%83%E5%90%90%E6%8E%89%E6%B1%89%E5%A0%A1%23) `442.1K 🔥` `NEW`
1. [不二之臣](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BA%8C%E4%B9%8B%E8%87%A3%23) `440.8K 🔥` `NEW`
1. [中国奶茶在莫斯科走红](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B6%E8%8C%B6%E5%9C%A8%E8%8E%AB%E6%96%AF%E7%A7%91%E8%B5%B0%E7%BA%A2%23) `438.7K 🔥` `NEW`
1. [伊朗称以色列试图构建人盾](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E4%BB%A5%E8%89%B2%E5%88%97%E8%AF%95%E5%9B%BE%E6%9E%84%E5%BB%BA%E4%BA%BA%E7%9B%BE%23) `438.2K 🔥` `NEW`
1. [岳雨婷ES看秀造型](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7ES%E7%9C%8B%E7%A7%80%E9%80%A0%E5%9E%8B%23) `436.1K 🔥` `NEW`
1. [伊朗大规模无人机攻击美以](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%A7%E8%A7%84%E6%A8%A1%E6%97%A0%E4%BA%BA%E6%9C%BA%E6%94%BB%E5%87%BB%E7%BE%8E%E4%BB%A5%23) `435.7K 🔥` `NEW`
1. [十日终焉](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%23) `432.5K 🔥` `NEW`
1. [女儿通过银行考试后父亲的反应 (Father's reaction after daughter passes bank exam)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%84%BF%E9%80%9A%E8%BF%87%E9%93%B6%E8%A1%8C%E8%80%83%E8%AF%95%E5%90%8E%E7%88%B6%E4%BA%B2%E7%9A%84%E5%8F%8D%E5%BA%94%23) `431.2K 🔥` `NEW`
1. [适女化的四分离卫生间](https://s.weibo.com/weibo?q=%23%E9%80%82%E5%A5%B3%E5%8C%96%E7%9A%84%E5%9B%9B%E5%88%86%E7%A6%BB%E5%8D%AB%E7%94%9F%E9%97%B4%23) `430.6K 🔥` `NEW`
1. [去动物园竟被猴子投喂苹果](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E5%8A%A8%E7%89%A9%E5%9B%AD%E7%AB%9F%E8%A2%AB%E7%8C%B4%E5%AD%90%E6%8A%95%E5%96%82%E8%8B%B9%E6%9E%9C%23) `429.8K 🔥` `NEW`
1. [猫咪还没断奶就上岗了](https://s.weibo.com/weibo?q=%23%E7%8C%AB%E5%92%AA%E8%BF%98%E6%B2%A1%E6%96%AD%E5%A5%B6%E5%B0%B1%E4%B8%8A%E5%B2%97%E4%BA%86%23) `427.9K 🔥` `NEW`
1. [岳雨婷事业心](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E4%BA%8B%E4%B8%9A%E5%BF%83%23) `427.6K 🔥` `NEW`
1. [伊朗称打击超200处美以目标](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%89%93%E5%87%BB%E8%B6%85200%E5%A4%84%E7%BE%8E%E4%BB%A5%E7%9B%AE%E6%A0%87%23) `426.8K 🔥` `NEW`
1. [多家银行投资金条已售罄](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%AE%B6%E9%93%B6%E8%A1%8C%E6%8A%95%E8%B5%84%E9%87%91%E6%9D%A1%E5%B7%B2%E5%94%AE%E7%BD%84%23) `424.8K 🔥` `NEW`
1. [委员谈劳务派遣制度被滥用](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E8%B0%88%E5%8A%B3%E5%8A%A1%E6%B4%BE%E9%81%A3%E5%88%B6%E5%BA%A6%E8%A2%AB%E6%BB%A5%E7%94%A8%23) `422.4K 🔥` `NEW`
1. [陈飞宇杨超越大秀同框](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E6%9D%A8%E8%B6%85%E8%B6%8A%E5%A4%A7%E7%A7%80%E5%90%8C%E6%A1%86%23) `421.6K 🔥` `NEW`
1. [上热下寒脾胃虚的天菜萝卜汤](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%83%AD%E4%B8%8B%E5%AF%92%E8%84%BE%E8%83%83%E8%99%9A%E7%9A%84%E5%A4%A9%E8%8F%9C%E8%90%9D%E5%8D%9C%E6%B1%A4%23) `421.1K 🔥` `NEW`
1. [腾讯视频发了张凌赫田曦薇吻戏 (Tencent Video released Zhang Linghe and Tian Xiwei kissing scene)](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91%E5%8F%91%E4%BA%86%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E5%90%BB%E6%88%8F%23) `419.3K 🔥` `NEW`
1. [妇女节 (women's day)](https://s.weibo.com/weibo?q=%23%E5%A6%87%E5%A5%B3%E8%8A%82%23) `1.0M 🔥` `+47%`
1. [爸妈收个礼物全村都知道了](https://s.weibo.com/weibo?q=%23%E7%88%B8%E5%A6%88%E6%94%B6%E4%B8%AA%E7%A4%BC%E7%89%A9%E5%85%A8%E6%9D%91%E9%83%BD%E7%9F%A5%E9%81%93%E4%BA%86%23) `731.9K 🔥` `+536%`
1. [你好星期六 (hello saturday)](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD%E6%98%9F%E6%9C%9F%E5%85%AD%23) `577.0K 🔥` `+159%`
1. [美袭击伊朗海水淡化厂](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E6%B5%B7%E6%B0%B4%E6%B7%A1%E5%8C%96%E5%8E%82%23) `547.5K 🔥` `+376%`
1. [3月8日两会日程](https://s.weibo.com/weibo?q=%233%E6%9C%888%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%23) `488.6K 🔥` `+325%`
1. [驻华记者称中国早已成自己第二故乡](https://s.weibo.com/weibo?q=%23%E9%A9%BB%E5%8D%8E%E8%AE%B0%E8%80%85%E7%A7%B0%E4%B8%AD%E5%9B%BD%E6%97%A9%E5%B7%B2%E6%88%90%E8%87%AA%E5%B7%B1%E7%AC%AC%E4%BA%8C%E6%95%85%E4%B9%A1%23) `471.0K 🔥` `+999%`
1. [伊朗65所学校遭袭 (65 schools attacked in Iran)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%9765%E6%89%80%E5%AD%A6%E6%A0%A1%E9%81%AD%E8%A2%AD%23) `456.1K 🔥` `+299%`
1. [多地学校早读取消了](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E5%AD%A6%E6%A0%A1%E6%97%A9%E8%AF%BB%E5%8F%96%E6%B6%88%E4%BA%86%23) `443.4K 🔥` `+373%`
1. [对张凌赫田曦薇身高差有了实感 (I have a real understanding of the height difference between Zhang Ling, He and Tian Xiwei)](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E8%BA%AB%E9%AB%98%E5%B7%AE%E6%9C%89%E4%BA%86%E5%AE%9E%E6%84%9F%23) `443.2K 🔥` `+288%`
1. [张凌赫谢征外甥随舅舅](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%B0%A2%E5%BE%81%E5%A4%96%E7%94%A5%E9%9A%8F%E8%88%85%E8%88%85%23) `441.4K 🔥` `+356%`
1. [百岁老人每日黄酒猪蹄50年不去医院](https://s.weibo.com/weibo?q=%23%E7%99%BE%E5%B2%81%E8%80%81%E4%BA%BA%E6%AF%8F%E6%97%A5%E9%BB%84%E9%85%92%E7%8C%AA%E8%B9%8450%E5%B9%B4%E4%B8%8D%E5%8E%BB%E5%8C%BB%E9%99%A2%23) `440.1K 🔥` `+772%`
1. [手机放大身份证竟藏微缩字母 (Mobile phone enlarges ID card to hide micro letters)](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E6%94%BE%E5%A4%A7%E8%BA%AB%E4%BB%BD%E8%AF%81%E7%AB%9F%E8%97%8F%E5%BE%AE%E7%BC%A9%E5%AD%97%E6%AF%8D%23) `439.8K 🔥` `+282%`
1. [杨超越巴黎世家全球首穿](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%B6%85%E8%B6%8A%E5%B7%B4%E9%BB%8E%E4%B8%96%E5%AE%B6%E5%85%A8%E7%90%83%E9%A6%96%E7%A9%BF%23) `437.9K 🔥` `+638%`
1. [伊朗外长称美袭击海水淡化厂是犯罪](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E7%A7%B0%E7%BE%8E%E8%A2%AD%E5%87%BB%E6%B5%B7%E6%B0%B4%E6%B7%A1%E5%8C%96%E5%8E%82%E6%98%AF%E7%8A%AF%E7%BD%AA%23) `436.7K 🔥` `+634%`
1. [郑钦文vs鲁季奇 (Zheng Qinwen vs Lujic)](https://s.weibo.com/weibo?q=%23%E9%83%91%E9%92%A6%E6%96%87vs%E9%B2%81%E5%AD%A3%E5%A5%87%23) `434.6K 🔥` `+278%`
1. [金价剧烈波动大家开始观望 (Gold prices fluctuate violently and everyone begins to wait and see)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%89%A7%E7%83%88%E6%B3%A2%E5%8A%A8%E5%A4%A7%E5%AE%B6%E5%BC%80%E5%A7%8B%E8%A7%82%E6%9C%9B%23) `433.8K 🔥` `+634%`
1. [奥巴马说在当前的美国很难怀抱希望 (Obama says it's hard to have hope in America right now)](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E5%B7%B4%E9%A9%AC%E8%AF%B4%E5%9C%A8%E5%BD%93%E5%89%8D%E7%9A%84%E7%BE%8E%E5%9B%BD%E5%BE%88%E9%9A%BE%E6%80%80%E6%8A%B1%E5%B8%8C%E6%9C%9B%23) `432.9K 🔥` `+281%`
1. [伊朗今天或选出最高领袖 (Iran may elect supreme leader today)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BB%8A%E5%A4%A9%E6%88%96%E9%80%89%E5%87%BA%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%23) `430.4K 🔥` `+673%`
1. [美对伊朗动武每日开支明细](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AF%B9%E4%BC%8A%E6%9C%97%E5%8A%A8%E6%AD%A6%E6%AF%8F%E6%97%A5%E5%BC%80%E6%94%AF%E6%98%8E%E7%BB%86%23) `428.7K 🔥` `+850%`
1. [逐玉热度 (The popularity of chasing jade)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%83%AD%E5%BA%A6%23) `426.2K 🔥` `+676%`
1. [59瓶汇源果汁起拍价109元 (The starting price for 59 bottles of Huiyuan juice is 109 yuan)](https://s.weibo.com/weibo?q=%2359%E7%93%B6%E6%B1%87%E6%BA%90%E6%9E%9C%E6%B1%81%E8%B5%B7%E6%8B%8D%E4%BB%B7109%E5%85%83%23) `425.4K 🔥` `+626%`
1. [谭松韵演技](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E6%BC%94%E6%8A%80%23) `424.1K 🔥` `+812%`
1. [人大代表推荐化橘红纳入国礼 (Deputies to the National People's Congress recommend incorporating orange into national gifts)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E6%8E%A8%E8%8D%90%E5%8C%96%E6%A9%98%E7%BA%A2%E7%BA%B3%E5%85%A5%E5%9B%BD%E7%A4%BC%23) `423.3K 🔥` `+793%`
1. [家长称8天假期打印了60多页作业 (Parents said they printed more than 60 pages of homework during the eight-day holiday)](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%95%BF%E7%A7%B08%E5%A4%A9%E5%81%87%E6%9C%9F%E6%89%93%E5%8D%B0%E4%BA%8660%E5%A4%9A%E9%A1%B5%E4%BD%9C%E4%B8%9A%23) `422.8K 🔥` `+620%`
1. [3人48小时做出5亿播放量AI短剧 (3 people created an AI short drama with 500 million views in 48 hours)](https://s.weibo.com/weibo?q=%233%E4%BA%BA48%E5%B0%8F%E6%97%B6%E5%81%9A%E5%87%BA5%E4%BA%BF%E6%92%AD%E6%94%BE%E9%87%8FAI%E7%9F%AD%E5%89%A7%23) `419.9K 🔥` `+618%`
1. [女孩贪玩忘事成绩下滑查出罕见病 (A girl was found to have a rare disease because she was too playful and forgot about things, her grades dropped.)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E8%B4%AA%E7%8E%A9%E5%BF%98%E4%BA%8B%E6%88%90%E7%BB%A9%E4%B8%8B%E6%BB%91%E6%9F%A5%E5%87%BA%E7%BD%95%E8%A7%81%E7%97%85%23) `418.7K 🔥` `+386%`
1. [两会学习笔记 (Two sessions study notes)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0%23) `589.1K 🔥`
1. [公务员养上政务龙虾了 (Civil servants are raising government lobsters)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E5%8A%A1%E5%91%98%E5%85%BB%E4%B8%8A%E6%94%BF%E5%8A%A1%E9%BE%99%E8%99%BE%E4%BA%86%23) `563.4K 🔥` `-42%`

Updated at 2026-03-08 09:09:09

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
