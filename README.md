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

1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `1.0M 🔥` `NEW`
1. [北斗导航机器挖坑在沙漠5秒种1棵树](https://s.weibo.com/weibo?q=%23%E5%8C%97%E6%96%97%E5%AF%BC%E8%88%AA%E6%9C%BA%E5%99%A8%E6%8C%96%E5%9D%91%E5%9C%A8%E6%B2%99%E6%BC%A05%E7%A7%92%E7%A7%8D1%E6%A3%B5%E6%A0%91%23) `593.2K 🔥` `NEW`
1. [伊朗为拉里贾尼举行葬礼](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%BA%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%E4%B8%BE%E8%A1%8C%E8%91%AC%E7%A4%BC%23) `588.1K 🔥` `NEW`
1. [张凌赫田曦薇被cue经纪人梗的反应](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E8%A2%ABcue%E7%BB%8F%E7%BA%AA%E4%BA%BA%E6%A2%97%E7%9A%84%E5%8F%8D%E5%BA%94%23) `586.6K 🔥` `NEW`
1. [698元海蓝之谜只有瓶子是真的](https://s.weibo.com/weibo?q=%23698%E5%85%83%E6%B5%B7%E8%93%9D%E4%B9%8B%E8%B0%9C%E5%8F%AA%E6%9C%89%E7%93%B6%E5%AD%90%E6%98%AF%E7%9C%9F%E7%9A%84%23) `584.9K 🔥` `NEW`
1. [周启豪获世乒赛参赛名额](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%90%AF%E8%B1%AA%E8%8E%B7%E4%B8%96%E4%B9%92%E8%B5%9B%E5%8F%82%E8%B5%9B%E5%90%8D%E9%A2%9D%23) `583.2K 🔥` `NEW`
1. [早期田曦薇 真人bjd](https://s.weibo.com/weibo?q=%23%E6%97%A9%E6%9C%9F%E7%94%B0%E6%9B%A6%E8%96%87%20%E7%9C%9F%E4%BA%BAbjd%23) `579.1K 🔥` `NEW`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `343.1K 🔥` `NEW`
1. [杨威回应杨阳洋成绩不好去香港读书](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%A8%81%E5%9B%9E%E5%BA%94%E6%9D%A8%E9%98%B3%E6%B4%8B%E6%88%90%E7%BB%A9%E4%B8%8D%E5%A5%BD%E5%8E%BB%E9%A6%99%E6%B8%AF%E8%AF%BB%E4%B9%A6%23) `320.1K 🔥` `NEW`
1. [文科生的春天](https://s.weibo.com/weibo?q=%23%E6%96%87%E7%A7%91%E7%94%9F%E7%9A%84%E6%98%A5%E5%A4%A9%23) `272.4K 🔥` `NEW`
1. [奇瑞要做真正的新能源车 (Chery wants to make a real new energy vehicle)](https://s.weibo.com/weibo?q=%23%E5%A5%87%E7%91%9E%E8%A6%81%E5%81%9A%E7%9C%9F%E6%AD%A3%E7%9A%84%E6%96%B0%E8%83%BD%E6%BA%90%E8%BD%A6%23) `208.0K 🔥` `NEW`
1. [精神病男子杀人4年后被认定0危险](https://s.weibo.com/weibo?q=%23%E7%B2%BE%E7%A5%9E%E7%97%85%E7%94%B7%E5%AD%90%E6%9D%80%E4%BA%BA4%E5%B9%B4%E5%90%8E%E8%A2%AB%E8%AE%A4%E5%AE%9A0%E5%8D%B1%E9%99%A9%23) `205.7K 🔥` `NEW`
1. [网友抵制AI演员](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E6%8A%B5%E5%88%B6AI%E6%BC%94%E5%91%98%23) `202.3K 🔥` `NEW`
1. [美联储](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%81%94%E5%82%A8%23) `193.0K 🔥` `NEW`
1. [4月1日医保新规落地](https://s.weibo.com/weibo?q=%234%E6%9C%881%E6%97%A5%E5%8C%BB%E4%BF%9D%E6%96%B0%E8%A7%84%E8%90%BD%E5%9C%B0%23) `149.8K 🔥` `NEW`
1. [逐玉预告](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E9%A2%84%E5%91%8A%23) `133.6K 🔥` `NEW`
1. [什么工作不会被AI替代](https://s.weibo.com/weibo?q=%23%E4%BB%80%E4%B9%88%E5%B7%A5%E4%BD%9C%E4%B8%8D%E4%BC%9A%E8%A2%ABAI%E6%9B%BF%E4%BB%A3%23) `125.4K 🔥` `NEW`
1. [美国特教女老师1天5次性侵男童](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E7%89%B9%E6%95%99%E5%A5%B3%E8%80%81%E5%B8%881%E5%A4%A95%E6%AC%A1%E6%80%A7%E4%BE%B5%E7%94%B7%E7%AB%A5%23) `120.1K 🔥` `NEW`
1. [金银油集体跳水](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%93%B6%E6%B2%B9%E9%9B%86%E4%BD%93%E8%B7%B3%E6%B0%B4%23) `106.0K 🔥` `NEW`
1. [白玉兰官宣6月26日颁奖](https://s.weibo.com/weibo?q=%23%E7%99%BD%E7%8E%89%E5%85%B0%E5%AE%98%E5%AE%A36%E6%9C%8826%E6%97%A5%E9%A2%81%E5%A5%96%23) `99.2K 🔥` `NEW`
1. [时代少年团演唱会 南沙 (Times Youth League Concert Nansha)](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E6%BC%94%E5%94%B1%E4%BC%9A%20%E5%8D%97%E6%B2%99%23) `98.2K 🔥` `NEW`
1. [国内金饰克价连跌](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%86%85%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E8%BF%9E%E8%B7%8C%23) `97.0K 🔥` `NEW`
1. [檀健次 你们当没看到](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%20%E4%BD%A0%E4%BB%AC%E5%BD%93%E6%B2%A1%E7%9C%8B%E5%88%B0%23) `96.8K 🔥` `NEW`
1. [联合国回应拉里贾尼遇害](https://s.weibo.com/weibo?q=%23%E8%81%94%E5%90%88%E5%9B%BD%E5%9B%9E%E5%BA%94%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%E9%81%87%E5%AE%B3%23) `91.7K 🔥` `NEW`
1. [邓凯 你第一](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%20%E4%BD%A0%E7%AC%AC%E4%B8%80%23) `91.3K 🔥` `NEW`
1. [vivo手机涨价](https://s.weibo.com/weibo?q=%23vivo%E6%89%8B%E6%9C%BA%E6%B6%A8%E4%BB%B7%23) `89.6K 🔥` `NEW`
1. [王一博春晚伴舞老师分享趣事](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%98%A5%E6%99%9A%E4%BC%B4%E8%88%9E%E8%80%81%E5%B8%88%E5%88%86%E4%BA%AB%E8%B6%A3%E4%BA%8B%23) `89.5K 🔥` `NEW`
1. [赵丽颖短发齐刘海造型](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E7%9F%AD%E5%8F%91%E9%BD%90%E5%88%98%E6%B5%B7%E9%80%A0%E5%9E%8B%23) `89.5K 🔥` `NEW`
1. [腾讯营收首超7000亿](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E8%90%A5%E6%94%B6%E9%A6%96%E8%B6%857000%E4%BA%BF%23) `89.4K 🔥` `NEW`
1. [雷军感谢同行鼓励](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E6%84%9F%E8%B0%A2%E5%90%8C%E8%A1%8C%E9%BC%93%E5%8A%B1%23) `89.4K 🔥` `NEW`
1. [宁娘 皇后 (Ning Niang Queen)](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%A8%98%20%E7%9A%87%E5%90%8E%23) `592.2K 🔥` `+666%`
1. [黄金怎么不涨反跌 (Why does gold fall instead of rising?)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E6%80%8E%E4%B9%88%E4%B8%8D%E6%B6%A8%E5%8F%8D%E8%B7%8C%23) `590.7K 🔥` `+244%`
1. [倪妮拥抱曼妮芬 (Ni Ni hugs Manifen)](https://s.weibo.com/weibo?q=%23%E5%80%AA%E5%A6%AE%E6%8B%A5%E6%8A%B1%E6%9B%BC%E5%A6%AE%E8%8A%AC%23) `586.8K 🔥` `+209%`
1. [建议年轻人少去公园容易伤自尊 (It is recommended that young people go to the park less often because it may hurt their self-esteem.)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%B0%91%E5%8E%BB%E5%85%AC%E5%9B%AD%E5%AE%B9%E6%98%93%E4%BC%A4%E8%87%AA%E5%B0%8A%23) `582.6K 🔥` `+60%`
1. [徐若晗 挂脸](https://s.weibo.com/weibo?q=%23%E5%BE%90%E8%8B%A5%E6%99%97%20%E6%8C%82%E8%84%B8%23) `579.4K 🔥` `+236%`
1. [赵丽颖直播](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E7%9B%B4%E6%92%AD%23) `335.0K 🔥` `+95%`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `289.7K 🔥` `+129%`
1. [耀客AI演员 赵今麦翟子路](https://s.weibo.com/weibo?q=%23%E8%80%80%E5%AE%A2AI%E6%BC%94%E5%91%98%20%E8%B5%B5%E4%BB%8A%E9%BA%A6%E7%BF%9F%E5%AD%90%E8%B7%AF%23) `214.7K 🔥` `+25%`
1. [中国学生开始卷海外考公了 (Chinese students begin to take public exams overseas)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%AD%A6%E7%94%9F%E5%BC%80%E5%A7%8B%E5%8D%B7%E6%B5%B7%E5%A4%96%E8%80%83%E5%85%AC%E4%BA%86%23) `739.2K 🔥`
1. [客服笑了半个小时决定去仓库打人](https://s.weibo.com/weibo?q=%23%E5%AE%A2%E6%9C%8D%E7%AC%91%E4%BA%86%E5%8D%8A%E4%B8%AA%E5%B0%8F%E6%97%B6%E5%86%B3%E5%AE%9A%E5%8E%BB%E4%BB%93%E5%BA%93%E6%89%93%E4%BA%BA%23) `205.7K 🔥`
1. [3岁女童被虐死前零下20多度遭脱衣](https://s.weibo.com/weibo?q=%233%E5%B2%81%E5%A5%B3%E7%AB%A5%E8%A2%AB%E8%99%90%E6%AD%BB%E5%89%8D%E9%9B%B6%E4%B8%8B20%E5%A4%9A%E5%BA%A6%E9%81%AD%E8%84%B1%E8%A1%A3%23) `177.1K 🔥`
1. [樊长玉谢征 好孕赘婿 (Fan Changyu, Xie Zheng, pregnant son-in-law)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E8%B0%A2%E5%BE%81%20%E5%A5%BD%E5%AD%95%E8%B5%98%E5%A9%BF%23) `141.6K 🔥` `-56%`
1. [福建一鸭子活吞41只小鸡](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%BB%BA%E4%B8%80%E9%B8%AD%E5%AD%90%E6%B4%BB%E5%90%9E41%E5%8F%AA%E5%B0%8F%E9%B8%A1%23) `135.1K 🔥` `-21%`
1. [容易让人长胖的睡前习惯](https://s.weibo.com/weibo?q=%23%E5%AE%B9%E6%98%93%E8%AE%A9%E4%BA%BA%E9%95%BF%E8%83%96%E7%9A%84%E7%9D%A1%E5%89%8D%E4%B9%A0%E6%83%AF%23) `127.3K 🔥` `-26%`
1. [张凌赫 我和他都没演过长风渡](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E6%88%91%E5%92%8C%E4%BB%96%E9%83%BD%E6%B2%A1%E6%BC%94%E8%BF%87%E9%95%BF%E9%A3%8E%E6%B8%A1%23) `120.2K 🔥` `-30%`
1. [爸爸买下校景房儿子上学仅需两分钟 (Dad bought a house with a school view so his son can go to school in just two minutes)](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E4%B9%B0%E4%B8%8B%E6%A0%A1%E6%99%AF%E6%88%BF%E5%84%BF%E5%AD%90%E4%B8%8A%E5%AD%A6%E4%BB%85%E9%9C%80%E4%B8%A4%E5%88%86%E9%92%9F%23) `113.2K 🔥` `-34%`
1. [小米新SU7](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%96%B0SU7%23) `96.8K 🔥` `-91%`
1. [正午阳光要扶持新人了](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E5%8D%88%E9%98%B3%E5%85%89%E8%A6%81%E6%89%B6%E6%8C%81%E6%96%B0%E4%BA%BA%E4%BA%86%23) `96.8K 🔥` `-71%`
1. [蜘蛛侠4预告](https://s.weibo.com/weibo?q=%23%E8%9C%98%E8%9B%9B%E4%BE%A04%E9%A2%84%E5%91%8A%23) `89.6K 🔥` `-73%`
1. [以色列刺杀伊朗情报部长 (Israel assassinates Iranian intelligence minister)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%88%BA%E6%9D%80%E4%BC%8A%E6%9C%97%E6%83%85%E6%8A%A5%E9%83%A8%E9%95%BF%23) `89.3K 🔥` `-73%`
1. [TF四代已实名](https://s.weibo.com/weibo?q=%23TF%E5%9B%9B%E4%BB%A3%E5%B7%B2%E5%AE%9E%E5%90%8D%23) `89.2K 🔥` `-41%`

Updated at 2026-03-18 21:46:18

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
