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

1. [你的公积金悄悄变多了 (Your provident fund has quietly increased)](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E7%9A%84%E5%85%AC%E7%A7%AF%E9%87%91%E6%82%84%E6%82%84%E5%8F%98%E5%A4%9A%E4%BA%86%23) `1.1M 🔥` `NEW`
1. [全新速腾S 7.98万起上市](https://s.weibo.com/weibo?q=%23%E5%85%A8%E6%96%B0%E9%80%9F%E8%85%BES%207.98%E4%B8%87%E8%B5%B7%E4%B8%8A%E5%B8%82%23) `436.4K 🔥` `NEW`
1. [鞠婧祎月鳞绮纪演技](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E6%BC%94%E6%8A%80%23) `265.6K 🔥` `NEW`
1. [芭乐 早知道烂地里了](https://s.weibo.com/weibo?q=%23%E8%8A%AD%E4%B9%90%20%E6%97%A9%E7%9F%A5%E9%81%93%E7%83%82%E5%9C%B0%E9%87%8C%E4%BA%86%23) `254.8K 🔥` `NEW`
1. [王者新赛季竟然可以种田](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%80%85%E6%96%B0%E8%B5%9B%E5%AD%A3%E7%AB%9F%E7%84%B6%E5%8F%AF%E4%BB%A5%E7%A7%8D%E7%94%B0%23) `253.1K 🔥` `NEW`
1. [29岁小伙赶在结婚前立遗嘱](https://s.weibo.com/weibo?q=%2329%E5%B2%81%E5%B0%8F%E4%BC%99%E8%B5%B6%E5%9C%A8%E7%BB%93%E5%A9%9A%E5%89%8D%E7%AB%8B%E9%81%97%E5%98%B1%23) `252.2K 🔥` `NEW`
1. [16G内存降到了700元](https://s.weibo.com/weibo?q=%2316G%E5%86%85%E5%AD%98%E9%99%8D%E5%88%B0%E4%BA%86700%E5%85%83%23) `247.1K 🔥` `NEW`
1. [优思益幕后推手被查](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E5%B9%95%E5%90%8E%E6%8E%A8%E6%89%8B%E8%A2%AB%E6%9F%A5%23) `236.2K 🔥` `NEW`
1. [张雪建议年轻人条件有限就先搞钱](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%BB%BA%E8%AE%AE%E5%B9%B4%E8%BD%BB%E4%BA%BA%E6%9D%A1%E4%BB%B6%E6%9C%89%E9%99%90%E5%B0%B1%E5%85%88%E6%90%9E%E9%92%B1%23) `206.1K 🔥` `NEW`
1. [迪丽热巴这真是妈咪级别的](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E8%BF%99%E7%9C%9F%E6%98%AF%E5%A6%88%E5%92%AA%E7%BA%A7%E5%88%AB%E7%9A%84%23) `173.2K 🔥` `NEW`
1. [青岛一大爷骑电动车进地铁车厢 (A man from Qingdao rides an electric scooter into a subway car)](https://s.weibo.com/weibo?q=%23%E9%9D%92%E5%B2%9B%E4%B8%80%E5%A4%A7%E7%88%B7%E9%AA%91%E7%94%B5%E5%8A%A8%E8%BD%A6%E8%BF%9B%E5%9C%B0%E9%93%81%E8%BD%A6%E5%8E%A2%23) `161.8K 🔥` `NEW`
1. [以后再也不埋怨清明节下雨了](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%90%8E%E5%86%8D%E4%B9%9F%E4%B8%8D%E5%9F%8B%E6%80%A8%E6%B8%85%E6%98%8E%E8%8A%82%E4%B8%8B%E9%9B%A8%E4%BA%86%23) `158.5K 🔥` `NEW`
1. [伊朗不同意停火强调要彻底结束战争](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8D%E5%90%8C%E6%84%8F%E5%81%9C%E7%81%AB%E5%BC%BA%E8%B0%83%E8%A6%81%E5%BD%BB%E5%BA%95%E7%BB%93%E6%9D%9F%E6%88%98%E4%BA%89%23) `157.6K 🔥` `NEW`
1. [金价急跌急涨](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%80%A5%E8%B7%8C%E6%80%A5%E6%B6%A8%23) `154.9K 🔥` `NEW`
1. [Angelababy海边拍摄MV](https://s.weibo.com/weibo?q=%23Angelababy%E6%B5%B7%E8%BE%B9%E6%8B%8D%E6%91%84MV%23) `136.0K 🔥` `NEW`
1. [月鳞绮纪](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%23) `132.6K 🔥` `NEW`
1. [日本男教师因接受性服务时偷拍被解雇](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%94%B7%E6%95%99%E5%B8%88%E5%9B%A0%E6%8E%A5%E5%8F%97%E6%80%A7%E6%9C%8D%E5%8A%A1%E6%97%B6%E5%81%B7%E6%8B%8D%E8%A2%AB%E8%A7%A3%E9%9B%87%23) `129.8K 🔥` `NEW`
1. [怀疑手机坏了都没怀疑林一](https://s.weibo.com/weibo?q=%23%E6%80%80%E7%96%91%E6%89%8B%E6%9C%BA%E5%9D%8F%E4%BA%86%E9%83%BD%E6%B2%A1%E6%80%80%E7%96%91%E6%9E%97%E4%B8%80%23) `119.0K 🔥` `NEW`
1. [三部门对优思益展开调查](https://s.weibo.com/weibo?q=%23%E4%B8%89%E9%83%A8%E9%97%A8%E5%AF%B9%E4%BC%98%E6%80%9D%E7%9B%8A%E5%B1%95%E5%BC%80%E8%B0%83%E6%9F%A5%23) `107.1K 🔥` `NEW`
1. [吉林省考成绩](https://s.weibo.com/weibo?q=%23%E5%90%89%E6%9E%97%E7%9C%81%E8%80%83%E6%88%90%E7%BB%A9%23) `106.6K 🔥` `NEW`
1. [鹿晗说我是邓超我同意五哈不播 (Luhan said I am Deng Chao and I agree that Wuha will not be broadcast)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E8%AF%B4%E6%88%91%E6%98%AF%E9%82%93%E8%B6%85%E6%88%91%E5%90%8C%E6%84%8F%E4%BA%94%E5%93%88%E4%B8%8D%E6%92%AD%23) `105.6K 🔥` `NEW`
1. [白日提灯追剧团](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E8%BF%BD%E5%89%A7%E5%9B%A2%23) `101.1K 🔥` `NEW`
1. [迪丽热巴回复陈飞宇](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%9B%9E%E5%A4%8D%E9%99%88%E9%A3%9E%E5%AE%87%23) `92.4K 🔥` `NEW`
1. [戚薇让刘昊然好好反省](https://s.weibo.com/weibo?q=%23%E6%88%9A%E8%96%87%E8%AE%A9%E5%88%98%E6%98%8A%E7%84%B6%E5%A5%BD%E5%A5%BD%E5%8F%8D%E7%9C%81%23) `89.9K 🔥` `NEW`
1. [曾沛慈 够爱](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E6%B2%9B%E6%85%88%20%E5%A4%9F%E7%88%B1%23) `89.5K 🔥` `NEW`
1. [马思纯咋变东北黎吧啦了](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%80%9D%E7%BA%AF%E5%92%8B%E5%8F%98%E4%B8%9C%E5%8C%97%E9%BB%8E%E5%90%A7%E5%95%A6%E4%BA%86%23) `77.6K 🔥` `NEW`
1. [伊朗精准打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%B2%BE%E5%87%86%E6%89%93%E5%87%BB%23) `77.5K 🔥` `NEW`
1. [甲骨文中国参保人数骤降55%](https://s.weibo.com/weibo?q=%23%E7%94%B2%E9%AA%A8%E6%96%87%E4%B8%AD%E5%9B%BD%E5%8F%82%E4%BF%9D%E4%BA%BA%E6%95%B0%E9%AA%A4%E9%99%8D55%25%23) `74.0K 🔥` `NEW`
1. [日本彻底撕下伪装](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%BD%BB%E5%BA%95%E6%92%95%E4%B8%8B%E4%BC%AA%E8%A3%85%23) `774.3K 🔥` `+277%`
1. [请假在家躺了两天小狗以为我失业了 (I took leave and stayed at home for two days. My puppy thought I was unemployed.)](https://s.weibo.com/weibo?q=%23%E8%AF%B7%E5%81%87%E5%9C%A8%E5%AE%B6%E8%BA%BA%E4%BA%86%E4%B8%A4%E5%A4%A9%E5%B0%8F%E7%8B%97%E4%BB%A5%E4%B8%BA%E6%88%91%E5%A4%B1%E4%B8%9A%E4%BA%86%23) `185.5K 🔥` `+176%`
1. [雄安大脑赋能智慧城市](https://s.weibo.com/weibo?q=%23%E9%9B%84%E5%AE%89%E5%A4%A7%E8%84%91%E8%B5%8B%E8%83%BD%E6%99%BA%E6%85%A7%E5%9F%8E%E5%B8%82%23) `629.0K 🔥`
1. [优思益 (Yousiyi)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `256.3K 🔥`
1. [丝芭起诉月鳞绮纪承制方](https://s.weibo.com/weibo?q=%23%E4%B8%9D%E8%8A%AD%E8%B5%B7%E8%AF%89%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E6%89%BF%E5%88%B6%E6%96%B9%23) `229.5K 🔥`
1. [李荣浩否认抄袭 (Li Ronghao denies plagiarism)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8D%A3%E6%B5%A9%E5%90%A6%E8%AE%A4%E6%8A%84%E8%A2%AD%23) `218.6K 🔥`
1. [警方已约谈太原暴走团负责人](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E5%B7%B2%E7%BA%A6%E8%B0%88%E5%A4%AA%E5%8E%9F%E6%9A%B4%E8%B5%B0%E5%9B%A2%E8%B4%9F%E8%B4%A3%E4%BA%BA%23) `178.8K 🔥`
1. [爸爸举高高孩子180度翻转吓到发烧](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E4%B8%BE%E9%AB%98%E9%AB%98%E5%AD%A9%E5%AD%90180%E5%BA%A6%E7%BF%BB%E8%BD%AC%E5%90%93%E5%88%B0%E5%8F%91%E7%83%A7%23) `103.2K 🔥`
1. [李维嘉不知道遗产传给谁](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BB%B4%E5%98%89%E4%B8%8D%E7%9F%A5%E9%81%93%E9%81%97%E4%BA%A7%E4%BC%A0%E7%BB%99%E8%B0%81%23) `247.4K 🔥` `-29%`
1. [张雪身价上亿还在用两千多块钱坏手机](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E8%BA%AB%E4%BB%B7%E4%B8%8A%E4%BA%BF%E8%BF%98%E5%9C%A8%E7%94%A8%E4%B8%A4%E5%8D%83%E5%A4%9A%E5%9D%97%E9%92%B1%E5%9D%8F%E6%89%8B%E6%9C%BA%23) `211.6K 🔥` `-73%`
1. [甲骨文凌晨6点突发裁员3万人](https://s.weibo.com/weibo?q=%23%E7%94%B2%E9%AA%A8%E6%96%87%E5%87%8C%E6%99%A86%E7%82%B9%E7%AA%81%E5%8F%91%E8%A3%81%E5%91%983%E4%B8%87%E4%BA%BA%23) `181.2K 🔥` `-35%`
1. [央视曝光优思益多平台下架](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%9B%9D%E5%85%89%E4%BC%98%E6%80%9D%E7%9B%8A%E5%A4%9A%E5%B9%B3%E5%8F%B0%E4%B8%8B%E6%9E%B6%23) `180.9K 🔥` `-22%`
1. [月鳞绮纪热度 (Moonscale Qiji popularity)](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E7%83%AD%E5%BA%A6%23) `140.0K 🔥` `-87%`
1. [伊朗愿意结束战争 (Iran is willing to end the war)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%84%BF%E6%84%8F%E7%BB%93%E6%9D%9F%E6%88%98%E4%BA%89%23) `139.8K 🔥` `-32%`
1. [从指甲看主角是真穷](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E6%8C%87%E7%94%B2%E7%9C%8B%E4%B8%BB%E8%A7%92%E6%98%AF%E7%9C%9F%E7%A9%B7%23) `128.1K 🔥` `-37%`
1. [月鳞绮纪开播](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E5%BC%80%E6%92%AD%23) `107.0K 🔥` `-45%`
1. [我坐一天400他躺一天500 (It costs 400 a day for me to sit and 500 a day for me to lie down.)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9D%90%E4%B8%80%E5%A4%A9400%E4%BB%96%E8%BA%BA%E4%B8%80%E5%A4%A9500%23) `106.6K 🔥` `-57%`
1. [张雪 (Zhang Xue)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%23) `102.5K 🔥` `-35%`
1. [销冠澳洲优思益竟是假进口](https://s.weibo.com/weibo?q=%23%E9%94%80%E5%86%A0%E6%BE%B3%E6%B4%B2%E4%BC%98%E6%80%9D%E7%9B%8A%E7%AB%9F%E6%98%AF%E5%81%87%E8%BF%9B%E5%8F%A3%23) `89.5K 🔥` `-38%`
1. [韩国夜店98年前出生顾客禁止入场](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E5%A4%9C%E5%BA%9798%E5%B9%B4%E5%89%8D%E5%87%BA%E7%94%9F%E9%A1%BE%E5%AE%A2%E7%A6%81%E6%AD%A2%E5%85%A5%E5%9C%BA%23) `77.6K 🔥` `-36%`
1. [邓超称4月4日五哈播不了了](https://s.weibo.com/weibo?q=%23%E9%82%93%E8%B6%85%E7%A7%B04%E6%9C%884%E6%97%A5%E4%BA%94%E5%93%88%E6%92%AD%E4%B8%8D%E4%BA%86%E4%BA%86%23) `77.6K 🔥` `-59%`
1. [有线耳机穿搭火了](https://s.weibo.com/weibo?q=%23%E6%9C%89%E7%BA%BF%E8%80%B3%E6%9C%BA%E7%A9%BF%E6%90%AD%E7%81%AB%E4%BA%86%23) `76.6K 🔥` `-50%`
1. [美国男子失踪23年后断腿惊现海滩](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E7%94%B7%E5%AD%90%E5%A4%B1%E8%B8%AA23%E5%B9%B4%E5%90%8E%E6%96%AD%E8%85%BF%E6%83%8A%E7%8E%B0%E6%B5%B7%E6%BB%A9%23) `75.9K 🔥` `-37%`

Updated at 2026-04-01 15:53:50

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
