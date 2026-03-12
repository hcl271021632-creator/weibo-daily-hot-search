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

1. [代表刚回屋建议就收到回复 (The representative received a reply as soon as he returned to the house to advise.)](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%88%9A%E5%9B%9E%E5%B1%8B%E5%BB%BA%E8%AE%AE%E5%B0%B1%E6%94%B6%E5%88%B0%E5%9B%9E%E5%A4%8D%23) `1.0M 🔥` `NEW`
1. [建议70岁以上农民养老金提至500](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE70%E5%B2%81%E4%BB%A5%E4%B8%8A%E5%86%9C%E6%B0%91%E5%85%BB%E8%80%81%E9%87%91%E6%8F%90%E8%87%B3500%23) `728.7K 🔥` `NEW`
1. [微信语音视频来电能忽略了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%AF%AD%E9%9F%B3%E8%A7%86%E9%A2%91%E6%9D%A5%E7%94%B5%E8%83%BD%E5%BF%BD%E7%95%A5%E4%BA%86%23) `262.4K 🔥` `NEW`
1. [杨瀚森G联赛比赛直播](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%80%9A%E6%A3%AEG%E8%81%94%E8%B5%9B%E6%AF%94%E8%B5%9B%E7%9B%B4%E6%92%AD%23) `256.7K 🔥` `NEW`
1. [安理会决议要求伊朗停止打海湾国家](https://s.weibo.com/weibo?q=%23%E5%AE%89%E7%90%86%E4%BC%9A%E5%86%B3%E8%AE%AE%E8%A6%81%E6%B1%82%E4%BC%8A%E6%9C%97%E5%81%9C%E6%AD%A2%E6%89%93%E6%B5%B7%E6%B9%BE%E5%9B%BD%E5%AE%B6%23) `254.4K 🔥` `NEW`
1. [好喝到王安宇还想再再再来一瓶](https://s.weibo.com/weibo?q=%23%E5%A5%BD%E5%96%9D%E5%88%B0%E7%8E%8B%E5%AE%89%E5%AE%87%E8%BF%98%E6%83%B3%E5%86%8D%E5%86%8D%E5%86%8D%E6%9D%A5%E4%B8%80%E7%93%B6%23) `254.3K 🔥` `NEW`
1. [建议提高待遇激励医学生扎根基层](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%8F%90%E9%AB%98%E5%BE%85%E9%81%87%E6%BF%80%E5%8A%B1%E5%8C%BB%E5%AD%A6%E7%94%9F%E6%89%8E%E6%A0%B9%E5%9F%BA%E5%B1%82%23) `253.5K 🔥` `NEW`
1. [在春天里奔赴新征程](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E6%98%A5%E5%A4%A9%E9%87%8C%E5%A5%94%E8%B5%B4%E6%96%B0%E5%BE%81%E7%A8%8B%23) `252.1K 🔥` `NEW`
1. [美国伊朗冲突](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%BC%8A%E6%9C%97%E5%86%B2%E7%AA%81%23) `248.9K 🔥` `NEW`
1. [逐玉破万 经纪人亲一个](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%A0%B4%E4%B8%87%20%E7%BB%8F%E7%BA%AA%E4%BA%BA%E4%BA%B2%E4%B8%80%E4%B8%AA%23) `248.1K 🔥` `NEW`
1. [汪苏泷明日世界MV (Wang Sulong Tomorrow's World MV)](https://s.weibo.com/weibo?q=%23%E6%B1%AA%E8%8B%8F%E6%B3%B7%E6%98%8E%E6%97%A5%E4%B8%96%E7%95%8CMV%23) `247.6K 🔥` `NEW`
1. [腾讯视频修改逐玉战报](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91%E4%BF%AE%E6%94%B9%E9%80%90%E7%8E%89%E6%88%98%E6%8A%A5%23) `242.6K 🔥` `NEW`
1. [张凌赫看了好几次田曦薇的手](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9C%8B%E4%BA%86%E5%A5%BD%E5%87%A0%E6%AC%A1%E7%94%B0%E6%9B%A6%E8%96%87%E7%9A%84%E6%89%8B%23) `240.9K 🔥` `NEW`
1. [腾讯视频版头有9部爆剧](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E8%A7%86%E9%A2%91%E7%89%88%E5%A4%B4%E6%9C%899%E9%83%A8%E7%88%86%E5%89%A7%23) `183.0K 🔥` `NEW`
1. [意识到同事不傻只是在逃避工作](https://s.weibo.com/weibo?q=%23%E6%84%8F%E8%AF%86%E5%88%B0%E5%90%8C%E4%BA%8B%E4%B8%8D%E5%82%BB%E5%8F%AA%E6%98%AF%E5%9C%A8%E9%80%83%E9%81%BF%E5%B7%A5%E4%BD%9C%23) `181.8K 🔥` `NEW`
1. [宋雨琦于谦不新鲜才怪](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E4%BA%8E%E8%B0%A6%E4%B8%8D%E6%96%B0%E9%B2%9C%E6%89%8D%E6%80%AA%23) `180.1K 🔥` `NEW`
1. [国有房东开始降租](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E6%9C%89%E6%88%BF%E4%B8%9C%E5%BC%80%E5%A7%8B%E9%99%8D%E7%A7%9F%23) `179.0K 🔥` `NEW`
1. [随手拍的照片帮我赚一年生活费](https://s.weibo.com/weibo?q=%23%E9%9A%8F%E6%89%8B%E6%8B%8D%E7%9A%84%E7%85%A7%E7%89%87%E5%B8%AE%E6%88%91%E8%B5%9A%E4%B8%80%E5%B9%B4%E7%94%9F%E6%B4%BB%E8%B4%B9%23) `175.4K 🔥` `NEW`
1. [多邻国绿鸟 离职](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E9%82%BB%E5%9B%BD%E7%BB%BF%E9%B8%9F%20%E7%A6%BB%E8%81%8C%23) `154.0K 🔥` `NEW`
1. [逐玉女二 穿越](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%A5%B3%E4%BA%8C%20%E7%A9%BF%E8%B6%8A%23) `135.8K 🔥` `NEW`
1. [一胎双胞胎女儿二胎双胞胎儿子 (One birth of twin girls and two births of twin sons.)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%83%8E%E5%8F%8C%E8%83%9E%E8%83%8E%E5%A5%B3%E5%84%BF%E4%BA%8C%E8%83%8E%E5%8F%8C%E8%83%9E%E8%83%8E%E5%84%BF%E5%AD%90%23) `132.8K 🔥` `NEW`
1. [辛辛苦苦考了一份辛辛苦苦的工作](https://s.weibo.com/weibo?q=%23%E8%BE%9B%E8%BE%9B%E8%8B%A6%E8%8B%A6%E8%80%83%E4%BA%86%E4%B8%80%E4%BB%BD%E8%BE%9B%E8%BE%9B%E8%8B%A6%E8%8B%A6%E7%9A%84%E5%B7%A5%E4%BD%9C%23) `131.4K 🔥` `NEW`
1. [爆剧标准](https://s.weibo.com/weibo?q=%23%E7%88%86%E5%89%A7%E6%A0%87%E5%87%86%23) `124.3K 🔥` `NEW`
1. [原来给肉去腥这么简单](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E7%BB%99%E8%82%89%E5%8E%BB%E8%85%A5%E8%BF%99%E4%B9%88%E7%AE%80%E5%8D%95%23) `121.0K 🔥` `NEW`
1. [纯真年代的爱情](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `120.3K 🔥` `NEW`
1. [杨瀚森G联赛半场8中8](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%80%9A%E6%A3%AEG%E8%81%94%E8%B5%9B%E5%8D%8A%E5%9C%BA8%E4%B8%AD8%23) `118.5K 🔥` `NEW`
1. [双胞胎老了后](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E8%83%9E%E8%83%8E%E8%80%81%E4%BA%86%E5%90%8E%23) `115.6K 🔥` `NEW`
1. [两个吃货分手后be like](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%B8%AA%E5%90%83%E8%B4%A7%E5%88%86%E6%89%8B%E5%90%8Ebe%20like%23) `109.8K 🔥` `NEW`
1. [代表称老师的职责不该向家长转移](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E7%A7%B0%E8%80%81%E5%B8%88%E7%9A%84%E8%81%8C%E8%B4%A3%E4%B8%8D%E8%AF%A5%E5%90%91%E5%AE%B6%E9%95%BF%E8%BD%AC%E7%A7%BB%23) `107.5K 🔥` `NEW`
1. [甜茶坐地铁通勤也一身班味](https://s.weibo.com/weibo?q=%23%E7%94%9C%E8%8C%B6%E5%9D%90%E5%9C%B0%E9%93%81%E9%80%9A%E5%8B%A4%E4%B9%9F%E4%B8%80%E8%BA%AB%E7%8F%AD%E5%91%B3%23) `107.5K 🔥` `NEW`
1. [游客夜爬华山偶遇神兽 (Tourists climb Mount Huashan at night and encounter mythical beasts)](https://s.weibo.com/weibo?q=%23%E6%B8%B8%E5%AE%A2%E5%A4%9C%E7%88%AC%E5%8D%8E%E5%B1%B1%E5%81%B6%E9%81%87%E7%A5%9E%E5%85%BD%23) `93.8K 🔥` `NEW`
1. [逐玉 业内](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E4%B8%9A%E5%86%85%23) `91.7K 🔥` `NEW`
1. [曝光暴利毒护垫](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%85%89%E6%9A%B4%E5%88%A9%E6%AF%92%E6%8A%A4%E5%9E%AB%23) `87.3K 🔥` `NEW`
1. [3月12日两会日程 (Agenda for the two sessions on March 12)](https://s.weibo.com/weibo?q=%233%E6%9C%8812%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%23) `599.4K 🔥`
1. [闲鱼和金靖都别唱了让我来拍 (Xianyu and Jin Jing, please stop singing and let me take the photos.)](https://s.weibo.com/weibo?q=%23%E9%97%B2%E9%B1%BC%E5%92%8C%E9%87%91%E9%9D%96%E9%83%BD%E5%88%AB%E5%94%B1%E4%BA%86%E8%AE%A9%E6%88%91%E6%9D%A5%E6%8B%8D%23) `410.7K 🔥`
1. [王濛拟被破格晋升 (Wang Meng is scheduled to be promoted under unusual circumstances)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E6%8B%9F%E8%A2%AB%E7%A0%B4%E6%A0%BC%E6%99%8B%E5%8D%87%23) `253.0K 🔥` `-58%`
1. [建议让全年无休的照护者能喘口气 (Recommendations to give year-round caregivers a breather)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E8%AE%A9%E5%85%A8%E5%B9%B4%E6%97%A0%E4%BC%91%E7%9A%84%E7%85%A7%E6%8A%A4%E8%80%85%E8%83%BD%E5%96%98%E5%8F%A3%E6%B0%94%23) `250.0K 🔥` `-77%`
1. [苹果最贵手机要来了](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%9C%80%E8%B4%B5%E6%89%8B%E6%9C%BA%E8%A6%81%E6%9D%A5%E4%BA%86%23) `246.7K 🔥` `-51%`
1. [景区买个水果捞没想到切完多了 (I bought some fruit in the scenic spot, but I didn’t expect that it would be too much to cut.)](https://s.weibo.com/weibo?q=%23%E6%99%AF%E5%8C%BA%E4%B9%B0%E4%B8%AA%E6%B0%B4%E6%9E%9C%E6%8D%9E%E6%B2%A1%E6%83%B3%E5%88%B0%E5%88%87%E5%AE%8C%E5%A4%9A%E4%BA%86%23) `207.5K 🔥` `-46%`
1. [章子怡求剧本 (Zhang Ziyi asks for script)](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%E6%B1%82%E5%89%A7%E6%9C%AC%23) `205.7K 🔥` `-34%`
1. [伊朗港口若遭袭将打击地区所有港口](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%B8%AF%E5%8F%A3%E8%8B%A5%E9%81%AD%E8%A2%AD%E5%B0%86%E6%89%93%E5%87%BB%E5%9C%B0%E5%8C%BA%E6%89%80%E6%9C%89%E6%B8%AF%E5%8F%A3%23) `182.8K 🔥` `-68%`
1. [3名美国富豪强奸性侵60名女性 (3 wealthy Americans raped and sexually assaulted 60 women)](https://s.weibo.com/weibo?q=%233%E5%90%8D%E7%BE%8E%E5%9B%BD%E5%AF%8C%E8%B1%AA%E5%BC%BA%E5%A5%B8%E6%80%A7%E4%BE%B560%E5%90%8D%E5%A5%B3%E6%80%A7%23) `178.0K 🔥` `-44%`
1. [张凌赫田曦薇头纱照](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E5%A4%B4%E7%BA%B1%E7%85%A7%23) `177.0K 🔥` `-44%`
1. [鹿晗新商务](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E6%96%B0%E5%95%86%E5%8A%A1%23) `176.2K 🔥` `-44%`
1. [代表说农民交的公粮就等于交了社保](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%86%9C%E6%B0%91%E4%BA%A4%E7%9A%84%E5%85%AC%E7%B2%AE%E5%B0%B1%E7%AD%89%E4%BA%8E%E4%BA%A4%E4%BA%86%E7%A4%BE%E4%BF%9D%23) `170.0K 🔥` `-58%`
1. [伊总统提出结束战争3大必要条件](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%80%BB%E7%BB%9F%E6%8F%90%E5%87%BA%E7%BB%93%E6%9D%9F%E6%88%98%E4%BA%893%E5%A4%A7%E5%BF%85%E8%A6%81%E6%9D%A1%E4%BB%B6%23) `152.9K 🔥` `-52%`
1. [东北阿姨坐5小时高铁后把座椅全立直](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E5%8C%97%E9%98%BF%E5%A7%A8%E5%9D%905%E5%B0%8F%E6%97%B6%E9%AB%98%E9%93%81%E5%90%8E%E6%8A%8A%E5%BA%A7%E6%A4%85%E5%85%A8%E7%AB%8B%E7%9B%B4%23) `139.0K 🔥` `-56%`
1. [我国灵活就业人员超2.4亿 (my country’s flexible employment population exceeds 240 million)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E7%81%B5%E6%B4%BB%E5%B0%B1%E4%B8%9A%E4%BA%BA%E5%91%98%E8%B6%852.4%E4%BA%BF%23) `133.4K 🔥` `-58%`
1. [狗 人我讨厌坐飞机](https://s.weibo.com/weibo?q=%23%E7%8B%97%20%E4%BA%BA%E6%88%91%E8%AE%A8%E5%8E%8C%E5%9D%90%E9%A3%9E%E6%9C%BA%23) `119.2K 🔥` `-62%`
1. [骄阳似我 (The sun is like me)](https://s.weibo.com/weibo?q=%23%E9%AA%84%E9%98%B3%E4%BC%BC%E6%88%91%23) `111.3K 🔥` `-65%`
1. [23岁牛散5000万买股浮盈超4100万](https://s.weibo.com/weibo?q=%2323%E5%B2%81%E7%89%9B%E6%95%A35000%E4%B8%87%E4%B9%B0%E8%82%A1%E6%B5%AE%E7%9B%88%E8%B6%854100%E4%B8%87%23) `90.6K 🔥` `-71%`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `89.1K 🔥` `-71%`

Updated at 2026-03-12 12:29:55

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
