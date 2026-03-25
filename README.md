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

1. [女儿殿下 夯 (Her Royal Highness Daughter)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%84%BF%E6%AE%BF%E4%B8%8B%20%E5%A4%AF%23) `1.1M 🔥` `NEW`
1. [过度自律](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%BA%A6%E8%87%AA%E5%BE%8B%23) `774.7K 🔥` `NEW`
1. [张雪峰团队老师整夜未眠](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%9B%A2%E9%98%9F%E8%80%81%E5%B8%88%E6%95%B4%E5%A4%9C%E6%9C%AA%E7%9C%A0%23) `604.0K 🔥` `NEW`
1. [央视新闻发了逐玉](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB%E5%8F%91%E4%BA%86%E9%80%90%E7%8E%89%23) `600.7K 🔥` `NEW`
1. [张雪峰微博曾5次提及猝死](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%BE%AE%E5%8D%9A%E6%9B%BE5%E6%AC%A1%E6%8F%90%E5%8F%8A%E7%8C%9D%E6%AD%BB%23) `595.7K 🔥` `NEW`
1. [相当于老鼠开了一家粮仓了](https://s.weibo.com/weibo?q=%23%E7%9B%B8%E5%BD%93%E4%BA%8E%E8%80%81%E9%BC%A0%E5%BC%80%E4%BA%86%E4%B8%80%E5%AE%B6%E7%B2%AE%E4%BB%93%E4%BA%86%23) `588.6K 🔥` `NEW`
1. [大冰感谢张雪峰对小朋友的帮助](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%86%B0%E6%84%9F%E8%B0%A2%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%AF%B9%E5%B0%8F%E6%9C%8B%E5%8F%8B%E7%9A%84%E5%B8%AE%E5%8A%A9%23) `585.1K 🔥` `NEW`
1. [心源性猝死与跑步有什么关系](https://s.weibo.com/weibo?q=%23%E5%BF%83%E6%BA%90%E6%80%A7%E7%8C%9D%E6%AD%BB%E4%B8%8E%E8%B7%91%E6%AD%A5%E6%9C%89%E4%BB%80%E4%B9%88%E5%85%B3%E7%B3%BB%23) `447.7K 🔥` `NEW`
1. [向太说人一定要学会避谶](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%A4%AA%E8%AF%B4%E4%BA%BA%E4%B8%80%E5%AE%9A%E8%A6%81%E5%AD%A6%E4%BC%9A%E9%81%BF%E8%B0%B6%23) `387.7K 🔥` `NEW`
1. [员工称救心丸不会因张雪峰事件涨价](https://s.weibo.com/weibo?q=%23%E5%91%98%E5%B7%A5%E7%A7%B0%E6%95%91%E5%BF%83%E4%B8%B8%E4%B8%8D%E4%BC%9A%E5%9B%A0%E5%BC%A0%E9%9B%AA%E5%B3%B0%E4%BA%8B%E4%BB%B6%E6%B6%A8%E4%BB%B7%23) `357.6K 🔥` `NEW`
1. [范丞丞轻氧感穿搭 (Fan Chengcheng’s light oxygen style outfit)](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E8%BD%BB%E6%B0%A7%E6%84%9F%E7%A9%BF%E6%90%AD%23) `322.5K 🔥` `NEW`
1. [张雪峰曾给焦虑买房的员工借100万](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%9B%BE%E7%BB%99%E7%84%A6%E8%99%91%E4%B9%B0%E6%88%BF%E7%9A%84%E5%91%98%E5%B7%A5%E5%80%9F100%E4%B8%87%23) `319.0K 🔥` `NEW`
1. [山姆饼干配料表和实物不一致被立案](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E9%A5%BC%E5%B9%B2%E9%85%8D%E6%96%99%E8%A1%A8%E5%92%8C%E5%AE%9E%E7%89%A9%E4%B8%8D%E4%B8%80%E8%87%B4%E8%A2%AB%E7%AB%8B%E6%A1%88%23) `277.1K 🔥` `NEW`
1. [张雪峰骑小电驴上下班](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E9%AA%91%E5%B0%8F%E7%94%B5%E9%A9%B4%E4%B8%8A%E4%B8%8B%E7%8F%AD%23) `239.0K 🔥` `NEW`
1. [偶遇毛阿敏 问问当年房车细节](https://s.weibo.com/weibo?q=%23%E5%81%B6%E9%81%87%E6%AF%9B%E9%98%BF%E6%95%8F%20%E9%97%AE%E9%97%AE%E5%BD%93%E5%B9%B4%E6%88%BF%E8%BD%A6%E7%BB%86%E8%8A%82%23) `192.0K 🔥` `NEW`
1. [随元青竟然欺负洪世贤艾莉儿子](https://s.weibo.com/weibo?q=%23%E9%9A%8F%E5%85%83%E9%9D%92%E7%AB%9F%E7%84%B6%E6%AC%BA%E8%B4%9F%E6%B4%AA%E4%B8%96%E8%B4%A4%E8%89%BE%E8%8E%89%E5%84%BF%E5%AD%90%23) `177.9K 🔥` `NEW`
1. [为什么会有人嘴唇发紫](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E6%9C%89%E4%BA%BA%E5%98%B4%E5%94%87%E5%8F%91%E7%B4%AB%23) `169.6K 🔥` `NEW`
1. [奔跑吧](https://s.weibo.com/weibo?q=%23%E5%A5%94%E8%B7%91%E5%90%A7%23) `162.0K 🔥` `NEW`
1. [何润东 项羽杀秦军情况说明](https://s.weibo.com/weibo?q=%23%E4%BD%95%E6%B6%A6%E4%B8%9C%20%E9%A1%B9%E7%BE%BD%E6%9D%80%E7%A7%A6%E5%86%9B%E6%83%85%E5%86%B5%E8%AF%B4%E6%98%8E%23) `160.0K 🔥` `NEW`
1. [日本警方将对我使馆24小时警戒](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E8%AD%A6%E6%96%B9%E5%B0%86%E5%AF%B9%E6%88%91%E4%BD%BF%E9%A6%8624%E5%B0%8F%E6%97%B6%E8%AD%A6%E6%88%92%23) `151.6K 🔥` `NEW`
1. [张雪峰公司3年参保人数涨超10倍 (The number of insured persons in Zhang Xuefeng's company has increased more than 10 times in the past three years)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%85%AC%E5%8F%B83%E5%B9%B4%E5%8F%82%E4%BF%9D%E4%BA%BA%E6%95%B0%E6%B6%A8%E8%B6%8510%E5%80%8D%23) `145.4K 🔥` `NEW`
1. [硝酸甘油 速效救心丸](https://s.weibo.com/weibo?q=%23%E7%A1%9D%E9%85%B8%E7%94%98%E6%B2%B9%20%E9%80%9F%E6%95%88%E6%95%91%E5%BF%83%E4%B8%B8%23) `140.9K 🔥` `NEW`
1. [董洁回应没有做烤瓷牙](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%B4%81%E5%9B%9E%E5%BA%94%E6%B2%A1%E6%9C%89%E5%81%9A%E7%83%A4%E7%93%B7%E7%89%99%23) `129.6K 🔥` `NEW`
1. [黄金连续突破](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E8%BF%9E%E7%BB%AD%E7%AA%81%E7%A0%B4%23) `123.4K 🔥` `NEW`
1. [伊朗发起第80波打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC80%E6%B3%A2%E6%89%93%E5%87%BB%23) `122.2K 🔥` `NEW`
1. [五角大楼和记者杠上了](https://s.weibo.com/weibo?q=%23%E4%BA%94%E8%A7%92%E5%A4%A7%E6%A5%BC%E5%92%8C%E8%AE%B0%E8%80%85%E6%9D%A0%E4%B8%8A%E4%BA%86%23) `117.1K 🔥` `NEW`
1. [黄金回涨原因](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E5%9B%9E%E6%B6%A8%E5%8E%9F%E5%9B%A0%23) `114.6K 🔥` `NEW`
1. [三甲医生回应为什么会有人嘴唇发紫](https://s.weibo.com/weibo?q=%23%E4%B8%89%E7%94%B2%E5%8C%BB%E7%94%9F%E5%9B%9E%E5%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E6%9C%89%E4%BA%BA%E5%98%B4%E5%94%87%E5%8F%91%E7%B4%AB%23) `109.6K 🔥` `NEW`
1. [光与夜之恋](https://s.weibo.com/weibo?q=%23%E5%85%89%E4%B8%8E%E5%A4%9C%E4%B9%8B%E6%81%8B%23) `108.3K 🔥` `NEW`
1. [林允生理性演技](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%85%81%E7%94%9F%E7%90%86%E6%80%A7%E6%BC%94%E6%8A%80%23) `108.2K 🔥` `NEW`
1. [马丽沈腾脸型叠一起成吴京了 (Ma Li and Shen Teng's face look like Wu Jing when combined)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E4%B8%BD%E6%B2%88%E8%85%BE%E8%84%B8%E5%9E%8B%E5%8F%A0%E4%B8%80%E8%B5%B7%E6%88%90%E5%90%B4%E4%BA%AC%E4%BA%86%23) `97.7K 🔥` `NEW`
1. [经常投喂的流浪猫把家养仓鼠吃掉了](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E5%B8%B8%E6%8A%95%E5%96%82%E7%9A%84%E6%B5%81%E6%B5%AA%E7%8C%AB%E6%8A%8A%E5%AE%B6%E5%85%BB%E4%BB%93%E9%BC%A0%E5%90%83%E6%8E%89%E4%BA%86%23) `93.2K 🔥` `NEW`
1. [旧手机回收价暴涨五六倍](https://s.weibo.com/weibo?q=%23%E6%97%A7%E6%89%8B%E6%9C%BA%E5%9B%9E%E6%94%B6%E4%BB%B7%E6%9A%B4%E6%B6%A8%E4%BA%94%E5%85%AD%E5%80%8D%23) `611.6K 🔥` `+133%`
1. [周杰伦 歌词](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%20%E6%AD%8C%E8%AF%8D%23) `607.5K 🔥` `+121%`
1. [奇瑞风云之夜T9L正式预售 (Chery Fengyun Night T9L officially pre-sold)](https://s.weibo.com/weibo?q=%23%E5%A5%87%E7%91%9E%E9%A3%8E%E4%BA%91%E4%B9%8B%E5%A4%9CT9L%E6%AD%A3%E5%BC%8F%E9%A2%84%E5%94%AE%23) `603.7K 🔥` `+233%`
1. [周杰伦新歌从夯到拉排名 (Jay Chou's new songs ranked from popular to popular)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E6%AD%8C%E4%BB%8E%E5%A4%AF%E5%88%B0%E6%8B%89%E6%8E%92%E5%90%8D%23) `525.4K 🔥` `+103%`
1. [一笑随歌](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%AC%91%E9%9A%8F%E6%AD%8C%23) `399.3K 🔥` `+370%`
1. [速效救心丸搜索同比增30倍](https://s.weibo.com/weibo?q=%23%E9%80%9F%E6%95%88%E6%95%91%E5%BF%83%E4%B8%B8%E6%90%9C%E7%B4%A2%E5%90%8C%E6%AF%94%E5%A2%9E30%E5%80%8D%23) `116.7K 🔥` `+23%`
1. [这就是中国AI产业链的硬核实力](https://s.weibo.com/weibo?q=%23%E8%BF%99%E5%B0%B1%E6%98%AF%E4%B8%AD%E5%9B%BDAI%E4%BA%A7%E4%B8%9A%E9%93%BE%E7%9A%84%E7%A1%AC%E6%A0%B8%E5%AE%9E%E5%8A%9B%23) `611.9K 🔥`
1. [颜如晶一年减重2.9斤](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%A6%82%E6%99%B6%E4%B8%80%E5%B9%B4%E5%87%8F%E9%87%8D2.9%E6%96%A4%23) `263.7K 🔥`
1. [霍启刚自曝为追求郭晶晶费尽心思](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%90%AF%E5%88%9A%E8%87%AA%E6%9B%9D%E4%B8%BA%E8%BF%BD%E6%B1%82%E9%83%AD%E6%99%B6%E6%99%B6%E8%B4%B9%E5%B0%BD%E5%BF%83%E6%80%9D%23) `203.5K 🔥`
1. [嘴唇发紫 心脏不好](https://s.weibo.com/weibo?q=%23%E5%98%B4%E5%94%87%E5%8F%91%E7%B4%AB%20%E5%BF%83%E8%84%8F%E4%B8%8D%E5%A5%BD%23) `592.2K 🔥` `-47%`
1. [浪姐7阵容 (Lang Jie 7 lineup)](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%907%E9%98%B5%E5%AE%B9%23) `587.8K 🔥` `-28%`
1. [安睡裤什么时候变成这样了 (When did Anpai pants become like this?)](https://s.weibo.com/weibo?q=%23%E5%AE%89%E7%9D%A1%E8%A3%A4%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%8F%98%E6%88%90%E8%BF%99%E6%A0%B7%E4%BA%86%23) `190.4K 🔥` `-24%`
1. [美国与伊朗和谈方案曝光](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%8E%E4%BC%8A%E6%9C%97%E5%92%8C%E8%B0%88%E6%96%B9%E6%A1%88%E6%9B%9D%E5%85%89%23) `179.1K 🔥` `-36%`
1. [日本对现役军人冲击中国使馆冷处理](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%AF%B9%E7%8E%B0%E5%BD%B9%E5%86%9B%E4%BA%BA%E5%86%B2%E5%87%BB%E4%B8%AD%E5%9B%BD%E4%BD%BF%E9%A6%86%E5%86%B7%E5%A4%84%E7%90%86%23) `150.0K 🔥` `-39%`
1. [郝蕾说不想再见纪凌尘了](https://s.weibo.com/weibo?q=%23%E9%83%9D%E8%95%BE%E8%AF%B4%E4%B8%8D%E6%83%B3%E5%86%8D%E8%A7%81%E7%BA%AA%E5%87%8C%E5%B0%98%E4%BA%86%23) `148.8K 🔥` `-42%`
1. [王俊凯 浪姐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%20%E6%B5%AA%E5%A7%90%23) `123.4K 🔥` `-27%`
1. [夏之光主演](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E4%B9%8B%E5%85%89%E4%B8%BB%E6%BC%94%23) `91.1K 🔥` `-44%`
1. [白日提灯OST官宣](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AFOST%E5%AE%98%E5%AE%A3%23) `86.6K 🔥` `-69%`
1. [三甲医生提醒吃面后运动严重会休克](https://s.weibo.com/weibo?q=%23%E4%B8%89%E7%94%B2%E5%8C%BB%E7%94%9F%E6%8F%90%E9%86%92%E5%90%83%E9%9D%A2%E5%90%8E%E8%BF%90%E5%8A%A8%E4%B8%A5%E9%87%8D%E4%BC%9A%E4%BC%91%E5%85%8B%23) `86.2K 🔥` `-24%`

Updated at 2026-03-25 13:15:06

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
