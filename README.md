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

1. [鹿哈或需赔偿消费者26.9亿元 (Luha may have to compensate consumers 2.69 billion yuan)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E6%88%96%E9%9C%80%E8%B5%94%E5%81%BF%E6%B6%88%E8%B4%B9%E8%80%8526.9%E4%BA%BF%E5%85%83%23) `1.4M 🔥` `NEW`
1. [十五五规划里的新提法](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E9%87%8C%E7%9A%84%E6%96%B0%E6%8F%90%E6%B3%95%23) `874.4K 🔥` `NEW`
1. [温瑞博4比2张本智和](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9A4%E6%AF%942%E5%BC%A0%E6%9C%AC%E6%99%BA%E5%92%8C%23) `458.8K 🔥` `NEW`
1. [律师帮帮团](https://s.weibo.com/weibo?q=%23%E5%BE%8B%E5%B8%88%E5%B8%AE%E5%B8%AE%E5%9B%A2%23) `317.0K 🔥` `NEW`
1. [夏之光 我的家庭没有能力兜底](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E4%B9%8B%E5%85%89%20%E6%88%91%E7%9A%84%E5%AE%B6%E5%BA%AD%E6%B2%A1%E6%9C%89%E8%83%BD%E5%8A%9B%E5%85%9C%E5%BA%95%23) `315.7K 🔥` `NEW`
1. [F1正赛](https://s.weibo.com/weibo?q=%23F1%E6%AD%A3%E8%B5%9B%23) `295.2K 🔥` `NEW`
1. [冻干草莓](https://s.weibo.com/weibo?q=%23%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%23) `226.3K 🔥` `NEW`
1. [眼镜镜片标价799元进价仅15元](https://s.weibo.com/weibo?q=%23%E7%9C%BC%E9%95%9C%E9%95%9C%E7%89%87%E6%A0%87%E4%BB%B7799%E5%85%83%E8%BF%9B%E4%BB%B7%E4%BB%8515%E5%85%83%23) `193.3K 🔥` `NEW`
1. [谭松韵别试探了有市场](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E5%88%AB%E8%AF%95%E6%8E%A2%E4%BA%86%E6%9C%89%E5%B8%82%E5%9C%BA%23) `161.6K 🔥` `NEW`
1. [考研初试成绩权重不低于50%](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E5%88%9D%E8%AF%95%E6%88%90%E7%BB%A9%E6%9D%83%E9%87%8D%E4%B8%8D%E4%BD%8E%E4%BA%8E50%25%23) `115.9K 🔥` `NEW`
1. [张凌赫吃了田曦薇给的青提 (Zhang Linghe ate the green tea given by Tian Xiwei)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%90%83%E4%BA%86%E7%94%B0%E6%9B%A6%E8%96%87%E7%BB%99%E7%9A%84%E9%9D%92%E6%8F%90%23) `115.7K 🔥` `NEW`
1. [虞书欣拍上云初令短剧了](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%8B%8D%E4%B8%8A%E4%BA%91%E5%88%9D%E4%BB%A4%E7%9F%AD%E5%89%A7%E4%BA%86%23) `104.4K 🔥` `NEW`
1. [书源摔倒](https://s.weibo.com/weibo?q=%23%E4%B9%A6%E6%BA%90%E6%91%94%E5%80%92%23) `103.4K 🔥` `NEW`
1. [李兰迪林沐然十年前的合照](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%85%B0%E8%BF%AA%E6%9E%97%E6%B2%90%E7%84%B6%E5%8D%81%E5%B9%B4%E5%89%8D%E7%9A%84%E5%90%88%E7%85%A7%23) `103.2K 🔥` `NEW`
1. [王励勤观战温瑞博](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%8A%B1%E5%8B%A4%E8%A7%82%E6%88%98%E6%B8%A9%E7%91%9E%E5%8D%9A%23) `77.9K 🔥` `NEW`
1. [315不是一天的事](https://s.weibo.com/weibo?q=%23315%E4%B8%8D%E6%98%AF%E4%B8%80%E5%A4%A9%E7%9A%84%E4%BA%8B%23) `67.5K 🔥` `NEW`
1. [温瑞博vs张本智和](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9Avs%E5%BC%A0%E6%9C%AC%E6%99%BA%E5%92%8C%23) `928.2K 🔥` `+292%`
1. [保证前额叶健康太重要了](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E8%AF%81%E5%89%8D%E9%A2%9D%E5%8F%B6%E5%81%A5%E5%BA%B7%E5%A4%AA%E9%87%8D%E8%A6%81%E4%BA%86%23) `297.1K 🔥` `+48%`
1. [亿级APP存在大量儿童软色情内容](https://s.weibo.com/weibo?q=%23%E4%BA%BF%E7%BA%A7APP%E5%AD%98%E5%9C%A8%E5%A4%A7%E9%87%8F%E5%84%BF%E7%AB%A5%E8%BD%AF%E8%89%B2%E6%83%85%E5%86%85%E5%AE%B9%23) `154.4K 🔥` `+22%`
1. [专家建议工作日缩至4天](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E5%BB%BA%E8%AE%AE%E5%B7%A5%E4%BD%9C%E6%97%A5%E7%BC%A9%E8%87%B34%E5%A4%A9%23) `296.0K 🔥`
1. [章子怡 医美 (Zhang Ziyi Medical Beauty)](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%20%E5%8C%BB%E7%BE%8E%23) `292.3K 🔥`
1. [成毅 年龄](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%20%E5%B9%B4%E9%BE%84%23) `291.6K 🔥`
1. [伊朗用涂鸦骗导弹轰炸](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%94%A8%E6%B6%82%E9%B8%A6%E9%AA%97%E5%AF%BC%E5%BC%B9%E8%BD%B0%E7%82%B8%23) `290.3K 🔥`
1. [孔雪儿好有版权意识](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E5%A5%BD%E6%9C%89%E7%89%88%E6%9D%83%E6%84%8F%E8%AF%86%23) `241.3K 🔥`
1. [梁婷 成毅报户口的时候报大一岁](https://s.weibo.com/weibo?q=%23%E6%A2%81%E5%A9%B7%20%E6%88%90%E6%AF%85%E6%8A%A5%E6%88%B7%E5%8F%A3%E7%9A%84%E6%97%B6%E5%80%99%E6%8A%A5%E5%A4%A7%E4%B8%80%E5%B2%81%23) `221.0K 🔥`
1. [AMG带你追F1](https://s.weibo.com/weibo?q=%23AMG%E5%B8%A6%E4%BD%A0%E8%BF%BDF1%23) `207.8K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `125.0K 🔥`
1. [李昀锐F1赛车服造型](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90F1%E8%B5%9B%E8%BD%A6%E6%9C%8D%E9%80%A0%E5%9E%8B%23) `86.6K 🔥`
1. [F勒布伦4比3松岛辉空](https://s.weibo.com/weibo?q=%23F%E5%8B%92%E5%B8%83%E4%BC%A64%E6%AF%943%E6%9D%BE%E5%B2%9B%E8%BE%89%E7%A9%BA%23) `80.4K 🔥`
1. [王鹤棣把白鹿宋茜沈月都回答了一遍](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%8A%8A%E7%99%BD%E9%B9%BF%E5%AE%8B%E8%8C%9C%E6%B2%88%E6%9C%88%E9%83%BD%E5%9B%9E%E7%AD%94%E4%BA%86%E4%B8%80%E9%81%8D%23) `74.1K 🔥`
1. [古巴 (cuba)](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E5%B7%B4%23) `66.9K 🔥`
1. [315](https://s.weibo.com/weibo?q=%23315%23) `862.6K 🔥` `-24%`
1. [刘文祥店员说20元1斤能是纯牛肉吗 (Liu Wenxiang, the clerk said, can 20 yuan per pound be pure beef?)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E5%BA%97%E5%91%98%E8%AF%B420%E5%85%831%E6%96%A4%E8%83%BD%E6%98%AF%E7%BA%AF%E7%89%9B%E8%82%89%E5%90%97%23) `377.5K 🔥` `-54%`
1. [央视调查某茶饮品牌遭恶意抹黑始末](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E8%B0%83%E6%9F%A5%E6%9F%90%E8%8C%B6%E9%A5%AE%E5%93%81%E7%89%8C%E9%81%AD%E6%81%B6%E6%84%8F%E6%8A%B9%E9%BB%91%E5%A7%8B%E6%9C%AB%23) `224.5K 🔥` `-50%`
1. [泡椒凤爪的泡椒竟是印上去的 (The pickled peppers in the pickled pepper chicken feet are actually printed on them.)](https://s.weibo.com/weibo?q=%23%E6%B3%A1%E6%A4%92%E5%87%A4%E7%88%AA%E7%9A%84%E6%B3%A1%E6%A4%92%E7%AB%9F%E6%98%AF%E5%8D%B0%E4%B8%8A%E5%8E%BB%E7%9A%84%23) `216.5K 🔥` `-36%`
1. [刘文祥 (Liu Wenxiang)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%23) `215.4K 🔥` `-42%`
1. [25岁儿子毕业不工作急哭父亲 (The 25-year-old son is crying because he has no job after graduation.)](https://s.weibo.com/weibo?q=%2325%E5%B2%81%E5%84%BF%E5%AD%90%E6%AF%95%E4%B8%9A%E4%B8%8D%E5%B7%A5%E4%BD%9C%E6%80%A5%E5%93%AD%E7%88%B6%E4%BA%B2%23) `204.9K 🔥` `-38%`
1. [F1取消四月全部赛事](https://s.weibo.com/weibo?q=%23F1%E5%8F%96%E6%B6%88%E5%9B%9B%E6%9C%88%E5%85%A8%E9%83%A8%E8%B5%9B%E4%BA%8B%23) `201.9K 🔥` `-36%`
1. [100万装出了10万的装修效果](https://s.weibo.com/weibo?q=%23100%E4%B8%87%E8%A3%85%E5%87%BA%E4%BA%8610%E4%B8%87%E7%9A%84%E8%A3%85%E4%BF%AE%E6%95%88%E6%9E%9C%23) `141.0K 🔥` `-49%`
1. [金道勋 ana](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%81%93%E5%8B%8B%20ana%23) `132.6K 🔥` `-34%`
1. [泰国遇害中国女子丈夫发声](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E9%81%87%E5%AE%B3%E4%B8%AD%E5%9B%BD%E5%A5%B3%E5%AD%90%E4%B8%88%E5%A4%AB%E5%8F%91%E5%A3%B0%23) `123.0K 🔥` `-50%`
1. [网友卢浮宫偶遇素颜刘亦菲](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E5%8D%A2%E6%B5%AE%E5%AE%AB%E5%81%B6%E9%81%87%E7%B4%A0%E9%A2%9C%E5%88%98%E4%BA%A6%E8%8F%B2%23) `121.5K 🔥` `-49%`
1. [国产剧月经戏终于不尴尬了 (Menstruation scenes in domestic dramas are finally no longer embarrassing)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E5%89%A7%E6%9C%88%E7%BB%8F%E6%88%8F%E7%BB%88%E4%BA%8E%E4%B8%8D%E5%B0%B4%E5%B0%AC%E4%BA%86%23) `116.5K 🔥` `-51%`
1. [王橹杰自拍九宫格](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E8%87%AA%E6%8B%8D%E4%B9%9D%E5%AE%AB%E6%A0%BC%23) `99.3K 🔥` `-63%`
1. [5岁金毛长期寄养宠夕夕发病身亡](https://s.weibo.com/weibo?q=%235%E5%B2%81%E9%87%91%E6%AF%9B%E9%95%BF%E6%9C%9F%E5%AF%84%E5%85%BB%E5%AE%A0%E5%A4%95%E5%A4%95%E5%8F%91%E7%97%85%E8%BA%AB%E4%BA%A1%23) `91.3K 🔥` `-23%`
1. [她俩从连体婴到形同陌路](https://s.weibo.com/weibo?q=%23%E5%A5%B9%E4%BF%A9%E4%BB%8E%E8%BF%9E%E4%BD%93%E5%A9%B4%E5%88%B0%E5%BD%A2%E5%90%8C%E9%99%8C%E8%B7%AF%23) `89.4K 🔥` `-67%`
1. [把家租给短剧剧组吧 (Rent your home to a skit crew)](https://s.weibo.com/weibo?q=%23%E6%8A%8A%E5%AE%B6%E7%A7%9F%E7%BB%99%E7%9F%AD%E5%89%A7%E5%89%A7%E7%BB%84%E5%90%A7%23) `82.5K 🔥` `-71%`
1. [方圆自曝不火了就去国外读书](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%9C%86%E8%87%AA%E6%9B%9D%E4%B8%8D%E7%81%AB%E4%BA%86%E5%B0%B1%E5%8E%BB%E5%9B%BD%E5%A4%96%E8%AF%BB%E4%B9%A6%23) `82.1K 🔥` `-65%`
1. [李煜东发文](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%85%9C%E4%B8%9C%E5%8F%91%E6%96%87%23) `81.4K 🔥` `-49%`
1. [交友APP色情聊天收割中老年男性 (Dating APP sex chat harvests middle-aged and elderly men)](https://s.weibo.com/weibo?q=%23%E4%BA%A4%E5%8F%8BAPP%E8%89%B2%E6%83%85%E8%81%8A%E5%A4%A9%E6%94%B6%E5%89%B2%E4%B8%AD%E8%80%81%E5%B9%B4%E7%94%B7%E6%80%A7%23) `75.8K 🔥` `-34%`
1. [库里回复庞博](https://s.weibo.com/weibo?q=%23%E5%BA%93%E9%87%8C%E5%9B%9E%E5%A4%8D%E5%BA%9E%E5%8D%9A%23) `67.5K 🔥` `-47%`

Updated at 2026-03-15 15:13:00

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
