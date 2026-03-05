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

1. [徐浩 团播 (Xu Hao group broadcast)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%B5%A9%20%E5%9B%A2%E6%92%AD%23) `99.1K 🔥` `NEW`
1. [17岁男生发现新物种筷子蛇登上SCI (A 17-year-old boy discovered a new species of chopstick snake and boarded the SCI)](https://s.weibo.com/weibo?q=%2317%E5%B2%81%E7%94%B7%E7%94%9F%E5%8F%91%E7%8E%B0%E6%96%B0%E7%89%A9%E7%A7%8D%E7%AD%B7%E5%AD%90%E8%9B%87%E7%99%BB%E4%B8%8ASCI%23) `205.2K 🔥` `+202%`
1. [香港没有调休](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E6%B2%A1%E6%9C%89%E8%B0%83%E4%BC%91%23) `153.5K 🔥` `+225%`
1. [中国将在哪些方向发力](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%B0%86%E5%9C%A8%E5%93%AA%E4%BA%9B%E6%96%B9%E5%90%91%E5%8F%91%E5%8A%9B%23) `121.6K 🔥` `+202%`
1. [春假清明连休6天家长称很无奈 (Parents said they were helpless after taking six consecutive days off during the Qingming Festival during the spring break.)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%81%87%E6%B8%85%E6%98%8E%E8%BF%9E%E4%BC%916%E5%A4%A9%E5%AE%B6%E9%95%BF%E7%A7%B0%E5%BE%88%E6%97%A0%E5%A5%88%23) `120.2K 🔥` `+216%`
1. [建议短视频凌晨1点至5点深夜静默](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%9F%AD%E8%A7%86%E9%A2%91%E5%87%8C%E6%99%A81%E7%82%B9%E8%87%B35%E7%82%B9%E6%B7%B1%E5%A4%9C%E9%9D%99%E9%BB%98%23) `117.3K 🔥` `+259%`
1. [伊朗称成功突破以色列七层防御 (Iran says it successfully penetrated seven layers of Israeli defenses)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%88%90%E5%8A%9F%E7%AA%81%E7%A0%B4%E4%BB%A5%E8%89%B2%E5%88%97%E4%B8%83%E5%B1%82%E9%98%B2%E5%BE%A1%23) `113.9K 🔥` `+250%`
1. [曾舜晞浅香品牌代言人 (Zeng Shunxi Qianxiang brand spokesperson)](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E6%B5%85%E9%A6%99%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `110.8K 🔥` `+243%`
1. [玫瑰丛生](https://s.weibo.com/weibo?q=%23%E7%8E%AB%E7%91%B0%E4%B8%9B%E7%94%9F%23) `109.0K 🔥` `+238%`
1. [建议不调休的代表被记者围住了](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%8D%E8%B0%83%E4%BC%91%E7%9A%84%E4%BB%A3%E8%A1%A8%E8%A2%AB%E8%AE%B0%E8%80%85%E5%9B%B4%E4%BD%8F%E4%BA%86%23) `105.7K 🔥` `+236%`
1. [建议最低法定年假从5天提高到10天](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%9C%80%E4%BD%8E%E6%B3%95%E5%AE%9A%E5%B9%B4%E5%81%87%E4%BB%8E5%E5%A4%A9%E6%8F%90%E9%AB%98%E5%88%B010%E5%A4%A9%23) `103.5K 🔥` `+225%`
1. [郭艾伦受伤](https://s.weibo.com/weibo?q=%23%E9%83%AD%E8%89%BE%E4%BC%A6%E5%8F%97%E4%BC%A4%23) `100.3K 🔥` `+224%`
1. [伊朗发射带1吨重弹头导弹打以色列](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E5%B0%84%E5%B8%A61%E5%90%A8%E9%87%8D%E5%BC%B9%E5%A4%B4%E5%AF%BC%E5%BC%B9%E6%89%93%E4%BB%A5%E8%89%B2%E5%88%97%23) `99.1K 🔥` `+223%`
1. [八爪鱼钻车内失踪3天车主崩溃求助 (Octopus drill has been missing from the car for 3 days. The car owner collapsed and asked for help.)](https://s.weibo.com/weibo?q=%23%E5%85%AB%E7%88%AA%E9%B1%BC%E9%92%BB%E8%BD%A6%E5%86%85%E5%A4%B1%E8%B8%AA3%E5%A4%A9%E8%BD%A6%E4%B8%BB%E5%B4%A9%E6%BA%83%E6%B1%82%E5%8A%A9%23) `98.9K 🔥` `+224%`
1. [两女子相隔7公里长得一模一样](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E5%A5%B3%E5%AD%90%E7%9B%B8%E9%9A%947%E5%85%AC%E9%87%8C%E9%95%BF%E5%BE%97%E4%B8%80%E6%A8%A1%E4%B8%80%E6%A0%B7%23) `98.7K 🔥` `+255%`
1. [坐飞机时发现邻座是只耶耶 (When I was on a plane, I noticed that the seat next to me was a guy.)](https://s.weibo.com/weibo?q=%23%E5%9D%90%E9%A3%9E%E6%9C%BA%E6%97%B6%E5%8F%91%E7%8E%B0%E9%82%BB%E5%BA%A7%E6%98%AF%E5%8F%AA%E8%80%B6%E8%80%B6%23) `98.5K 🔥` `+282%`
1. [成毅太子长琴cut](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%E5%A4%AA%E5%AD%90%E9%95%BF%E7%90%B4cut%23) `98.2K 🔥` `+281%`
1. [代表说农民每月200元养老金太亏了 (Representatives say farmers’ monthly pension of 200 yuan is too much of a loss)](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%86%9C%E6%B0%91%E6%AF%8F%E6%9C%88200%E5%85%83%E5%85%BB%E8%80%81%E9%87%91%E5%A4%AA%E4%BA%8F%E4%BA%86%23) `98.1K 🔥` `+281%`
1. [00后高速收费员回应撞脸多个明星 (The post-00s expressway toll collector’s response hit many celebrities in the face)](https://s.weibo.com/weibo?q=%2300%E5%90%8E%E9%AB%98%E9%80%9F%E6%94%B6%E8%B4%B9%E5%91%98%E5%9B%9E%E5%BA%94%E6%92%9E%E8%84%B8%E5%A4%9A%E4%B8%AA%E6%98%8E%E6%98%9F%23) `97.7K 🔥` `+279%`
1. [高铁一等座4元二等座8元](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%93%81%E4%B8%80%E7%AD%89%E5%BA%A74%E5%85%83%E4%BA%8C%E7%AD%89%E5%BA%A78%E5%85%83%23) `97.6K 🔥` `+279%`
1. [张艺兴直播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%89%BA%E5%85%B4%E7%9B%B4%E6%92%AD%23) `97.4K 🔥` `+332%`
1. [33岁女子长相幼态常被认为是小学生](https://s.weibo.com/weibo?q=%2333%E5%B2%81%E5%A5%B3%E5%AD%90%E9%95%BF%E7%9B%B8%E5%B9%BC%E6%80%81%E5%B8%B8%E8%A2%AB%E8%AE%A4%E4%B8%BA%E6%98%AF%E5%B0%8F%E5%AD%A6%E7%94%9F%23) `97.2K 🔥` `+279%`
1. [王楚然 女人中的女人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%20%E5%A5%B3%E4%BA%BA%E4%B8%AD%E7%9A%84%E5%A5%B3%E4%BA%BA%23) `97.0K 🔥` `+278%`
1. [伊朗报复美以 (Iran retaliates against US and Israel)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8A%A5%E5%A4%8D%E7%BE%8E%E4%BB%A5%23) `96.8K 🔥` `+277%`
1. [艺考严选 宫里又来新人了](https://s.weibo.com/weibo?q=%23%E8%89%BA%E8%80%83%E4%B8%A5%E9%80%89%20%E5%AE%AB%E9%87%8C%E5%8F%88%E6%9D%A5%E6%96%B0%E4%BA%BA%E4%BA%86%23) `96.6K 🔥` `+277%`
1. [郭晓婷评论王天辰 (Guo Xiaoting comments on Wang Tianchen)](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%93%E5%A9%B7%E8%AF%84%E8%AE%BA%E7%8E%8B%E5%A4%A9%E8%BE%B0%23) `96.2K 🔥` `+304%`
1. [美以超7套先进雷达系统被摧毁](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E8%B6%857%E5%A5%97%E5%85%88%E8%BF%9B%E9%9B%B7%E8%BE%BE%E7%B3%BB%E7%BB%9F%E8%A2%AB%E6%91%A7%E6%AF%81%23) `95.9K 🔥` `+319%`
1. [池昌旭 韩国酵母免疫者 (Ji Chang Wook Korean Yeast Immunologist)](https://s.weibo.com/weibo?q=%23%E6%B1%A0%E6%98%8C%E6%97%AD%20%E9%9F%A9%E5%9B%BD%E9%85%B5%E6%AF%8D%E5%85%8D%E7%96%AB%E8%80%85%23) `95.7K 🔥` `+318%`
1. [伊朗反击进入新阶段](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%8D%E5%87%BB%E8%BF%9B%E5%85%A5%E6%96%B0%E9%98%B6%E6%AE%B5%23) `95.6K 🔥` `+319%`
1. [现在就出发4 (Let's go now 4)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%23) `95.4K 🔥` `+318%`
1. [美国老兵高呼没人愿为以色列而战 (US veterans shout no one wants to fight for Israel)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E8%80%81%E5%85%B5%E9%AB%98%E5%91%BC%E6%B2%A1%E4%BA%BA%E6%84%BF%E4%B8%BA%E4%BB%A5%E8%89%B2%E5%88%97%E8%80%8C%E6%88%98%23) `95.1K 🔥` `+318%`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `94.9K 🔥` `+318%`
1. [伊朗每天都向以色列发射导弹](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AF%8F%E5%A4%A9%E9%83%BD%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%E5%8F%91%E5%B0%84%E5%AF%BC%E5%BC%B9%23) `94.7K 🔥` `+316%`
1. [叶璇都演婆婆了刘晓庆还在演少女 (Michelle Ye already plays the mother-in-law, and Liu Xiaoqing still plays the girl)](https://s.weibo.com/weibo?q=%23%E5%8F%B6%E7%92%87%E9%83%BD%E6%BC%94%E5%A9%86%E5%A9%86%E4%BA%86%E5%88%98%E6%99%93%E5%BA%86%E8%BF%98%E5%9C%A8%E6%BC%94%E5%B0%91%E5%A5%B3%23) `94.5K 🔥` `+315%`
1. [伊朗避实就虚打击美军 (Iran avoids truth and uses lies to attack U.S. military)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%81%BF%E5%AE%9E%E5%B0%B1%E8%99%9A%E6%89%93%E5%87%BB%E7%BE%8E%E5%86%9B%23) `94.2K 🔥` `+315%`
1. [真正长大了好像就是这样](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%AD%A3%E9%95%BF%E5%A4%A7%E4%BA%86%E5%A5%BD%E5%83%8F%E5%B0%B1%E6%98%AF%E8%BF%99%E6%A0%B7%23) `94.1K 🔥` `+312%`
1. [王一博巴黎随拍记录](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%B7%B4%E9%BB%8E%E9%9A%8F%E6%8B%8D%E8%AE%B0%E5%BD%95%23) `94.0K 🔥` `+314%`
1. [陈哲远 再不救教资要融化了 (Chen Zheyuan If we don’t save the teaching resources, they will be melted down.)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%20%E5%86%8D%E4%B8%8D%E6%95%91%E6%95%99%E8%B5%84%E8%A6%81%E8%9E%8D%E5%8C%96%E4%BA%86%23) `93.6K 🔥` `+313%`
1. [女子收到刮刮乐生日花束刮出80万元](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%94%B6%E5%88%B0%E5%88%AE%E5%88%AE%E4%B9%90%E7%94%9F%E6%97%A5%E8%8A%B1%E6%9D%9F%E5%88%AE%E5%87%BA80%E4%B8%87%E5%85%83%23) `93.5K 🔥` `+314%`
1. [鹤男](https://s.weibo.com/weibo?q=%23%E9%B9%A4%E7%94%B7%23) `93.2K 🔥` `+262%`
1. [比亚迪全球首创闪充桩来了](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%E5%85%A8%E7%90%83%E9%A6%96%E5%88%9B%E9%97%AA%E5%85%85%E6%A1%A9%E6%9D%A5%E4%BA%86%23) `93.1K 🔥` `+315%`
1. [PEL春季赛](https://s.weibo.com/weibo?q=%23PEL%E6%98%A5%E5%AD%A3%E8%B5%9B%23) `92.9K 🔥` `+316%`
1. [6天长假成都飞三亚机票量激增](https://s.weibo.com/weibo?q=%236%E5%A4%A9%E9%95%BF%E5%81%87%E6%88%90%E9%83%BD%E9%A3%9E%E4%B8%89%E4%BA%9A%E6%9C%BA%E7%A5%A8%E9%87%8F%E6%BF%80%E5%A2%9E%23) `92.7K 🔥` `+311%`
1. [田曦薇转圈出场](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E8%BD%AC%E5%9C%88%E5%87%BA%E5%9C%BA%23) `92.5K 🔥` `+311%`
1. [陈哲远大侦探玩成了密逃 (Detective Chen Zheyuan became a secret escaper)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%E5%A4%A7%E4%BE%A6%E6%8E%A2%E7%8E%A9%E6%88%90%E4%BA%86%E5%AF%86%E9%80%83%23) `92.2K 🔥` `+311%`
1. [归良辰](https://s.weibo.com/weibo?q=%23%E5%BD%92%E8%89%AF%E8%BE%B0%23) `92.0K 🔥` `+307%`
1. [薛之谦万兽之王长沙站开启预售 (Joker Xue, King of Beasts, opens pre-sale in Changsha Station)](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E4%B8%87%E5%85%BD%E4%B9%8B%E7%8E%8B%E9%95%BF%E6%B2%99%E7%AB%99%E5%BC%80%E5%90%AF%E9%A2%84%E5%94%AE%23) `91.9K 🔥` `+257%`
1. [sask mage](https://s.weibo.com/weibo?q=%23sask%20mage%23) `91.7K 🔥` `+308%`
1. [比亚迪闪充零下30度12分钟充饱](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%E9%97%AA%E5%85%85%E9%9B%B6%E4%B8%8B30%E5%BA%A612%E5%88%86%E9%92%9F%E5%85%85%E9%A5%B1%23) `91.5K 🔥` `+306%`
1. [张雨霏鼓励年轻人勇敢试错](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%A8%E9%9C%8F%E9%BC%93%E5%8A%B1%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%8B%87%E6%95%A2%E8%AF%95%E9%94%99%23) `91.2K 🔥` `+308%`

Updated at 2026-03-06 05:45:43

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
