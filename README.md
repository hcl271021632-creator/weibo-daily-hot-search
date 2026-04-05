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

1. [浪姐今日直播暂停 (Sister Lang’s live broadcast is suspended today)](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E4%BB%8A%E6%97%A5%E7%9B%B4%E6%92%AD%E6%9A%82%E5%81%9C%23) `1.1M 🔥` `NEW`
1. [张雪回应一个子儿没有言论](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%9B%9E%E5%BA%94%E4%B8%80%E4%B8%AA%E5%AD%90%E5%84%BF%E6%B2%A1%E6%9C%89%E8%A8%80%E8%AE%BA%23) `790.3K 🔥` `NEW`
1. [清明假期新业态解锁新体验](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E6%96%B0%E4%B8%9A%E6%80%81%E8%A7%A3%E9%94%81%E6%96%B0%E4%BD%93%E9%AA%8C%23) `639.9K 🔥` `NEW`
1. [张月曾沛慈 评级人数](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9C%88%E6%9B%BE%E6%B2%9B%E6%85%88%20%E8%AF%84%E7%BA%A7%E4%BA%BA%E6%95%B0%23) `281.5K 🔥` `NEW`
1. [王曼昱vs申裕斌](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1vs%E7%94%B3%E8%A3%95%E6%96%8C%23) `237.4K 🔥` `NEW`
1. [原来软柿子在人群里这么明显](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BD%AF%E6%9F%BF%E5%AD%90%E5%9C%A8%E4%BA%BA%E7%BE%A4%E9%87%8C%E8%BF%99%E4%B9%88%E6%98%8E%E6%98%BE%23) `236.1K 🔥` `NEW`
1. [美5名顶尖科学家离奇失踪或死亡](https://s.weibo.com/weibo?q=%23%E7%BE%8E5%E5%90%8D%E9%A1%B6%E5%B0%96%E7%A7%91%E5%AD%A6%E5%AE%B6%E7%A6%BB%E5%A5%87%E5%A4%B1%E8%B8%AA%E6%88%96%E6%AD%BB%E4%BA%A1%23) `235.8K 🔥` `NEW`
1. [孙颖莎vs温特](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E6%B8%A9%E7%89%B9%23) `233.8K 🔥` `NEW`
1. [黄婷婷没去浪姐去了演综](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%A9%B7%E5%A9%B7%E6%B2%A1%E5%8E%BB%E6%B5%AA%E5%A7%90%E5%8E%BB%E4%BA%86%E6%BC%94%E7%BB%BC%23) `215.0K 🔥` `NEW`
1. [男子拿祖宗骨灰坛回家进门就打碎了](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E6%8B%BF%E7%A5%96%E5%AE%97%E9%AA%A8%E7%81%B0%E5%9D%9B%E5%9B%9E%E5%AE%B6%E8%BF%9B%E9%97%A8%E5%B0%B1%E6%89%93%E7%A2%8E%E4%BA%86%23) `184.3K 🔥` `NEW`
1. [美国前参议员表示特朗普已经住院 (Former US senator says Trump has been hospitalized)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%89%8D%E5%8F%82%E8%AE%AE%E5%91%98%E8%A1%A8%E7%A4%BA%E7%89%B9%E6%9C%97%E6%99%AE%E5%B7%B2%E7%BB%8F%E4%BD%8F%E9%99%A2%23) `179.5K 🔥` `NEW`
1. [何炅没开口维嘉就哭了](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%82%85%E6%B2%A1%E5%BC%80%E5%8F%A3%E7%BB%B4%E5%98%89%E5%B0%B1%E5%93%AD%E4%BA%86%23) `176.7K 🔥` `NEW`
1. [嘴甜羞耻症](https://s.weibo.com/weibo?q=%23%E5%98%B4%E7%94%9C%E7%BE%9E%E8%80%BB%E7%97%87%23) `172.6K 🔥` `NEW`
1. [伊媒称美军试图炸死在伊失联飞行员](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E5%AA%92%E7%A7%B0%E7%BE%8E%E5%86%9B%E8%AF%95%E5%9B%BE%E7%82%B8%E6%AD%BB%E5%9C%A8%E4%BC%8A%E5%A4%B1%E8%81%94%E9%A3%9E%E8%A1%8C%E5%91%98%23) `167.3K 🔥` `NEW`
1. [网友爸爸曾在昆明石林偶遇张国荣](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E7%88%B8%E7%88%B8%E6%9B%BE%E5%9C%A8%E6%98%86%E6%98%8E%E7%9F%B3%E6%9E%97%E5%81%B6%E9%81%87%E5%BC%A0%E5%9B%BD%E8%8D%A3%23) `167.1K 🔥` `NEW`
1. [特朗普一直呆在白宫](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E4%B8%80%E7%9B%B4%E5%91%86%E5%9C%A8%E7%99%BD%E5%AE%AB%23) `157.3K 🔥` `NEW`
1. [谢娜的话筒一直是在冲着李小冉的](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E7%9A%84%E8%AF%9D%E7%AD%92%E4%B8%80%E7%9B%B4%E6%98%AF%E5%9C%A8%E5%86%B2%E7%9D%80%E6%9D%8E%E5%B0%8F%E5%86%89%E7%9A%84%23) `156.4K 🔥` `NEW`
1. [黄金大买家狂抛](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E5%A4%A7%E4%B9%B0%E5%AE%B6%E7%8B%82%E6%8A%9B%23) `149.9K 🔥` `NEW`
1. [乘风2026](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%23) `143.0K 🔥` `NEW`
1. [孙颖莎4比0温特](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E4%E6%AF%940%E6%B8%A9%E7%89%B9%23) `140.5K 🔥` `NEW`
1. [黄磊二女儿长得好像黄磊 (Huang Lei’s second daughter looks like Huang Lei)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E7%A3%8A%E4%BA%8C%E5%A5%B3%E5%84%BF%E9%95%BF%E5%BE%97%E5%A5%BD%E5%83%8F%E9%BB%84%E7%A3%8A%23) `140.0K 🔥` `NEW`
1. [李小冉曾自曝给谢娜收拾脱的脏衣服](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%B0%8F%E5%86%89%E6%9B%BE%E8%87%AA%E6%9B%9D%E7%BB%99%E8%B0%A2%E5%A8%9C%E6%94%B6%E6%8B%BE%E8%84%B1%E7%9A%84%E8%84%8F%E8%A1%A3%E6%9C%8D%23) `139.5K 🔥` `NEW`
1. [吴京点赞吐槽浪姐博文](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%E7%82%B9%E8%B5%9E%E5%90%90%E6%A7%BD%E6%B5%AA%E5%A7%90%E5%8D%9A%E6%96%87%23) `138.2K 🔥` `NEW`
1. [飞机 烟灰缸](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E6%9C%BA%20%E7%83%9F%E7%81%B0%E7%BC%B8%23) `138.1K 🔥` `NEW`
1. [文章马伊琍女儿小名叫文爱马](https://s.weibo.com/weibo?q=%23%E6%96%87%E7%AB%A0%E9%A9%AC%E4%BC%8A%E7%90%8D%E5%A5%B3%E5%84%BF%E5%B0%8F%E5%90%8D%E5%8F%AB%E6%96%87%E7%88%B1%E9%A9%AC%23) `136.7K 🔥` `NEW`
1. [以色列被曝正等待美国开绿灯](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E8%A2%AB%E6%9B%9D%E6%AD%A3%E7%AD%89%E5%BE%85%E7%BE%8E%E5%9B%BD%E5%BC%80%E7%BB%BF%E7%81%AF%23) `136.5K 🔥` `NEW`
1. [女孩2岁确诊孤独症父母花100万求医](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A92%E5%B2%81%E7%A1%AE%E8%AF%8A%E5%AD%A4%E7%8B%AC%E7%97%87%E7%88%B6%E6%AF%8D%E8%8A%B1100%E4%B8%87%E6%B1%82%E5%8C%BB%23) `134.9K 🔥` `NEW`
1. [中国电车全球爆火](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%94%B5%E8%BD%A6%E5%85%A8%E7%90%83%E7%88%86%E7%81%AB%23) `109.0K 🔥` `NEW`
1. [男子被毒蛇咬200多次产生抗体](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%A2%AB%E6%AF%92%E8%9B%87%E5%92%AC200%E5%A4%9A%E6%AC%A1%E4%BA%A7%E7%94%9F%E6%8A%97%E4%BD%93%23) `103.8K 🔥` `NEW`
1. [手机壳比手机还贵](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E5%A3%B3%E6%AF%94%E6%89%8B%E6%9C%BA%E8%BF%98%E8%B4%B5%23) `92.9K 🔥` `NEW`
1. [伊朗籍男子在日本被殴打致死 (Iranian man beaten to death in Japan)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%B1%8D%E7%94%B7%E5%AD%90%E5%9C%A8%E6%97%A5%E6%9C%AC%E8%A2%AB%E6%AE%B4%E6%89%93%E8%87%B4%E6%AD%BB%23) `92.8K 🔥` `NEW`
1. [年轻人扫墓成瘾为地偶应援](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E8%BD%BB%E4%BA%BA%E6%89%AB%E5%A2%93%E6%88%90%E7%98%BE%E4%B8%BA%E5%9C%B0%E5%81%B6%E5%BA%94%E6%8F%B4%23) `91.5K 🔥` `NEW`
1. [月鳞绮纪角色热度均破亿](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E8%A7%92%E8%89%B2%E7%83%AD%E5%BA%A6%E5%9D%87%E7%A0%B4%E4%BA%BF%23) `89.8K 🔥` `NEW`
1. [27岁女博士暂停学业开女工维修公司](https://s.weibo.com/weibo?q=%2327%E5%B2%81%E5%A5%B3%E5%8D%9A%E5%A3%AB%E6%9A%82%E5%81%9C%E5%AD%A6%E4%B8%9A%E5%BC%80%E5%A5%B3%E5%B7%A5%E7%BB%B4%E4%BF%AE%E5%85%AC%E5%8F%B8%23) `88.6K 🔥` `NEW`
1. [疯狂动物城2原设定有狐兔鼻尖糖](https://s.weibo.com/weibo?q=%23%E7%96%AF%E7%8B%82%E5%8A%A8%E7%89%A9%E5%9F%8E2%E5%8E%9F%E8%AE%BE%E5%AE%9A%E6%9C%89%E7%8B%90%E5%85%94%E9%BC%BB%E5%B0%96%E7%B3%96%23) `87.7K 🔥` `NEW`
1. [莫氏鸡煲店家人均痛苦面具](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%B0%8F%E9%B8%A1%E7%85%B2%E5%BA%97%E5%AE%B6%E4%BA%BA%E5%9D%87%E7%97%9B%E8%8B%A6%E9%9D%A2%E5%85%B7%23) `86.6K 🔥` `NEW`
1. [全红婵快乐成长吧](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E5%BF%AB%E4%B9%90%E6%88%90%E9%95%BF%E5%90%A7%23) `85.9K 🔥` `NEW`
1. [孙颖莎零封对手](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E9%9B%B6%E5%B0%81%E5%AF%B9%E6%89%8B%23) `83.9K 🔥` `NEW`
1. [侯英超夸孙颖莎战术](https://s.weibo.com/weibo?q=%23%E4%BE%AF%E8%8B%B1%E8%B6%85%E5%A4%B8%E5%AD%99%E9%A2%96%E8%8E%8E%E6%88%98%E6%9C%AF%23) `83.1K 🔥` `NEW`
1. [张月妆造](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9C%88%E5%A6%86%E9%80%A0%23) `81.5K 🔥` `NEW`
1. [土耳其狂抛黄金原因 (Why Türkiye is selling gold so much)](https://s.weibo.com/weibo?q=%23%E5%9C%9F%E8%80%B3%E5%85%B6%E7%8B%82%E6%8A%9B%E9%BB%84%E9%87%91%E5%8E%9F%E5%9B%A0%23) `80.9K 🔥` `NEW`
1. [美议员称公开外星人简报会让国家混乱](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%AE%AE%E5%91%98%E7%A7%B0%E5%85%AC%E5%BC%80%E5%A4%96%E6%98%9F%E4%BA%BA%E7%AE%80%E6%8A%A5%E4%BC%9A%E8%AE%A9%E5%9B%BD%E5%AE%B6%E6%B7%B7%E4%B9%B1%23) `74.6K 🔥` `NEW`
1. [刘雨鑫探店莫氏鸡煲视频点赞超130万](https://s.weibo.com/weibo?q=%23%E5%88%98%E9%9B%A8%E9%91%AB%E6%8E%A2%E5%BA%97%E8%8E%AB%E6%B0%8F%E9%B8%A1%E7%85%B2%E8%A7%86%E9%A2%91%E7%82%B9%E8%B5%9E%E8%B6%85130%E4%B8%87%23) `72.9K 🔥` `NEW`
1. [侯英超夸孙颖莎夸到没词儿](https://s.weibo.com/weibo?q=%23%E4%BE%AF%E8%8B%B1%E8%B6%85%E5%A4%B8%E5%AD%99%E9%A2%96%E8%8E%8E%E5%A4%B8%E5%88%B0%E6%B2%A1%E8%AF%8D%E5%84%BF%23) `70.1K 🔥` `NEW`
1. [迪丽热巴陈飞宇白日提灯热度涨幅](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%99%88%E9%A3%9E%E5%AE%87%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E7%83%AD%E5%BA%A6%E6%B6%A8%E5%B9%85%23) `69.6K 🔥` `NEW`
1. [伊朗外长称从未拒绝前往伊斯兰堡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E7%A7%B0%E4%BB%8E%E6%9C%AA%E6%8B%92%E7%BB%9D%E5%89%8D%E5%BE%80%E4%BC%8A%E6%96%AF%E5%85%B0%E5%A0%A1%23) `68.6K 🔥` `NEW`
1. [孙颖莎谈对阵温特战术](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E8%B0%88%E5%AF%B9%E9%98%B5%E6%B8%A9%E7%89%B9%E6%88%98%E6%9C%AF%23) `68.3K 🔥` `NEW`
1. [毛新宇携家人到杨开慧烈士陵园祭扫](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%96%B0%E5%AE%87%E6%90%BA%E5%AE%B6%E4%BA%BA%E5%88%B0%E6%9D%A8%E5%BC%80%E6%85%A7%E7%83%88%E5%A3%AB%E9%99%B5%E5%9B%AD%E7%A5%AD%E6%89%AB%23) `67.3K 🔥` `NEW`
1. [清明节](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E8%8A%82%23) `71.0K 🔥` `-33%`
1. [男子钓7条鱼获利50元被判刑](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%92%937%E6%9D%A1%E9%B1%BC%E8%8E%B7%E5%88%A950%E5%85%83%E8%A2%AB%E5%88%A4%E5%88%91%23) `68.5K 🔥` `-46%`

Updated at 2026-04-05 12:20:06

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
