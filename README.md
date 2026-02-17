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

1. [浙江新特产 (Zhejiang new specialties)](https://s.weibo.com/weibo?q=%23%E6%B5%99%E6%B1%9F%E6%96%B0%E7%89%B9%E4%BA%A7%23) `741.5K 🔥` `NEW`
1. [西双版纳地震](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%8F%8C%E7%89%88%E7%BA%B3%E5%9C%B0%E9%9C%87%23) `604.0K 🔥` `NEW`
1. [宋小宝 小品翻车](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%B0%8F%E5%AE%9D%20%E5%B0%8F%E5%93%81%E7%BF%BB%E8%BD%A6%23) `538.5K 🔥` `NEW`
1. [B站春晚从夯到夯爆了排名](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E6%98%A5%E6%99%9A%E4%BB%8E%E5%A4%AF%E5%88%B0%E5%A4%AF%E7%88%86%E4%BA%86%E6%8E%92%E5%90%8D%23) `322.1K 🔥` `NEW`
1. [B站小品 笑力竭了](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E5%B0%8F%E5%93%81%20%E7%AC%91%E5%8A%9B%E7%AB%AD%E4%BA%86%23) `230.6K 🔥` `NEW`
1. [今年所有法定假日全与周末重合](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E6%89%80%E6%9C%89%E6%B3%95%E5%AE%9A%E5%81%87%E6%97%A5%E5%85%A8%E4%B8%8E%E5%91%A8%E6%9C%AB%E9%87%8D%E5%90%88%23) `203.4K 🔥` `NEW`
1. [凌晨4点起床吃年夜饭是什么体验](https://s.weibo.com/weibo?q=%23%E5%87%8C%E6%99%A84%E7%82%B9%E8%B5%B7%E5%BA%8A%E5%90%83%E5%B9%B4%E5%A4%9C%E9%A5%AD%E6%98%AF%E4%BB%80%E4%B9%88%E4%BD%93%E9%AA%8C%23) `185.7K 🔥` `NEW`
1. [周深与千问定制马年新歌](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B1%E4%B8%8E%E5%8D%83%E9%97%AE%E5%AE%9A%E5%88%B6%E9%A9%AC%E5%B9%B4%E6%96%B0%E6%AD%8C%23) `183.0K 🔥` `NEW`
1. [初二和初五的财神一样吗](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%BA%8C%E5%92%8C%E5%88%9D%E4%BA%94%E7%9A%84%E8%B4%A2%E7%A5%9E%E4%B8%80%E6%A0%B7%E5%90%97%23) `181.6K 🔥` `NEW`
1. [B站语言类节目 赢麻了](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E8%AF%AD%E8%A8%80%E7%B1%BB%E8%8A%82%E7%9B%AE%20%E8%B5%A2%E9%BA%BB%E4%BA%86%23) `178.5K 🔥` `NEW`
1. [山东一村600多人集体磕头拜年 (More than 600 people in a village in Shandong kowtowed together to pay New Year greetings)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E4%B8%9C%E4%B8%80%E6%9D%91600%E5%A4%9A%E4%BA%BA%E9%9B%86%E4%BD%93%E7%A3%95%E5%A4%B4%E6%8B%9C%E5%B9%B4%23) `175.4K 🔥` `NEW`
1. [易烊千玺台词含金量](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%8F%B0%E8%AF%8D%E5%90%AB%E9%87%91%E9%87%8F%23) `159.9K 🔥` `NEW`
1. [王菲化妆师改口问就是AI](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%8F%B2%E5%8C%96%E5%A6%86%E5%B8%88%E6%94%B9%E5%8F%A3%E9%97%AE%E5%B0%B1%E6%98%AFAI%23) `141.7K 🔥` `NEW`
1. [短剧演员唱歌 大白嗓](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E6%BC%94%E5%91%98%E5%94%B1%E6%AD%8C%20%E5%A4%A7%E7%99%BD%E5%97%93%23) `125.4K 🔥` `NEW`
1. [千问在春晚当起了恋爱军师](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%9C%A8%E6%98%A5%E6%99%9A%E5%BD%93%E8%B5%B7%E4%BA%86%E6%81%8B%E7%88%B1%E5%86%9B%E5%B8%88%23) `123.3K 🔥` `NEW`
1. [百名后辈给104岁老人磕头拜年](https://s.weibo.com/weibo?q=%23%E7%99%BE%E5%90%8D%E5%90%8E%E8%BE%88%E7%BB%99104%E5%B2%81%E8%80%81%E4%BA%BA%E7%A3%95%E5%A4%B4%E6%8B%9C%E5%B9%B4%23) `122.3K 🔥` `NEW`
1. [成何体统](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%23) `112.0K 🔥` `NEW`
1. [全红婵过年也逃不过吃鸡](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E8%BF%87%E5%B9%B4%E4%B9%9F%E9%80%83%E4%B8%8D%E8%BF%87%E5%90%83%E9%B8%A1%23) `110.1K 🔥` `NEW`
1. [谁来给王玉雯递个古装本子](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%9D%A5%E7%BB%99%E7%8E%8B%E7%8E%89%E9%9B%AF%E9%80%92%E4%B8%AA%E5%8F%A4%E8%A3%85%E6%9C%AC%E5%AD%90%23) `104.7K 🔥` `NEW`
1. [苹果推出马年春节壁纸](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%8E%A8%E5%87%BA%E9%A9%AC%E5%B9%B4%E6%98%A5%E8%8A%82%E5%A3%81%E7%BA%B8%23) `103.9K 🔥` `NEW`
1. [中国游客被困俄罗斯极光村超40小时 (Chinese tourists were trapped in Russia's Aurora Village for more than 40 hours)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E8%A2%AB%E5%9B%B0%E4%BF%84%E7%BD%97%E6%96%AF%E6%9E%81%E5%85%89%E6%9D%91%E8%B6%8540%E5%B0%8F%E6%97%B6%23) `103.4K 🔥` `NEW`
1. [镖人 真的好看 (The escort is really good-looking)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E7%9C%9F%E7%9A%84%E5%A5%BD%E7%9C%8B%23) `419.4K 🔥` `+36%`
1. [比艺人还帅的韩国花滑天才](https://s.weibo.com/weibo?q=%23%E6%AF%94%E8%89%BA%E4%BA%BA%E8%BF%98%E5%B8%85%E7%9A%84%E9%9F%A9%E5%9B%BD%E8%8A%B1%E6%BB%91%E5%A4%A9%E6%89%8D%23) `211.9K 🔥` `+23%`
1. [不是年味淡了而是轮到我们做主了](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%98%AF%E5%B9%B4%E5%91%B3%E6%B7%A1%E4%BA%86%E8%80%8C%E6%98%AF%E8%BD%AE%E5%88%B0%E6%88%91%E4%BB%AC%E5%81%9A%E4%B8%BB%E4%BA%86%23) `170.2K 🔥` `+47%`
1. [广州烟花 (Guangzhou fireworks)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E5%B7%9E%E7%83%9F%E8%8A%B1%23) `934.8K 🔥`
1. [问界M9祝您新年手到福来](https://s.weibo.com/weibo?q=%23%E9%97%AE%E7%95%8CM9%E7%A5%9D%E6%82%A8%E6%96%B0%E5%B9%B4%E6%89%8B%E5%88%B0%E7%A6%8F%E6%9D%A5%23) `692.0K 🔥`
1. [埃及土耳其等8国联合声明](https://s.weibo.com/weibo?q=%23%E5%9F%83%E5%8F%8A%E5%9C%9F%E8%80%B3%E5%85%B6%E7%AD%898%E5%9B%BD%E8%81%94%E5%90%88%E5%A3%B0%E6%98%8E%23) `211.2K 🔥`
1. [宋小宝 我上坟都不敢这么烧](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%B0%8F%E5%AE%9D%20%E6%88%91%E4%B8%8A%E5%9D%9F%E9%83%BD%E4%B8%8D%E6%95%A2%E8%BF%99%E4%B9%88%E7%83%A7%23) `206.5K 🔥`
1. [瞿颖胡兵 为啥没在一起](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%83%A1%E5%85%B5%20%E4%B8%BA%E5%95%A5%E6%B2%A1%E5%9C%A8%E4%B8%80%E8%B5%B7%23) `199.0K 🔥`
1. [冬奥会露内衣品牌女选手引来广告商](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E4%BC%9A%E9%9C%B2%E5%86%85%E8%A1%A3%E5%93%81%E7%89%8C%E5%A5%B3%E9%80%89%E6%89%8B%E5%BC%95%E6%9D%A5%E5%B9%BF%E5%91%8A%E5%95%86%23) `196.4K 🔥`
1. [全国初二回娘家的女婿belike](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E5%88%9D%E4%BA%8C%E5%9B%9E%E5%A8%98%E5%AE%B6%E7%9A%84%E5%A5%B3%E5%A9%BFbelike%23) `195.4K 🔥`
1. [千万别贪便宜买监控](https://s.weibo.com/weibo?q=%23%E5%8D%83%E4%B8%87%E5%88%AB%E8%B4%AA%E4%BE%BF%E5%AE%9C%E4%B9%B0%E7%9B%91%E6%8E%A7%23) `186.3K 🔥`
1. [金价 (gold price)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `179.2K 🔥`
1. [飞驰人生](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F%23) `173.2K 🔥`
1. [年度女演员杨幂](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E5%BA%A6%E5%A5%B3%E6%BC%94%E5%91%98%E6%9D%A8%E5%B9%82%23) `171.5K 🔥`
1. [沙溢给白鹿发了多少压岁钱](https://s.weibo.com/weibo?q=%23%E6%B2%99%E6%BA%A2%E7%BB%99%E7%99%BD%E9%B9%BF%E5%8F%91%E4%BA%86%E5%A4%9A%E5%B0%91%E5%8E%8B%E5%B2%81%E9%92%B1%23) `167.1K 🔥`
1. [正确走路姿势是用臀而不是腿](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E7%A1%AE%E8%B5%B0%E8%B7%AF%E5%A7%BF%E5%8A%BF%E6%98%AF%E7%94%A8%E8%87%80%E8%80%8C%E4%B8%8D%E6%98%AF%E8%85%BF%23) `165.2K 🔥`
1. [母女过年炸丸子变大型翻车现场](https://s.weibo.com/weibo?q=%23%E6%AF%8D%E5%A5%B3%E8%BF%87%E5%B9%B4%E7%82%B8%E4%B8%B8%E5%AD%90%E5%8F%98%E5%A4%A7%E5%9E%8B%E7%BF%BB%E8%BD%A6%E7%8E%B0%E5%9C%BA%23) `162.1K 🔥`
1. [飞驰人生3票房 (Flying Life 3 box office)](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E7%A5%A8%E6%88%BF%23) `161.4K 🔥`
1. [金价银价直线跳水](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E9%93%B6%E4%BB%B7%E7%9B%B4%E7%BA%BF%E8%B7%B3%E6%B0%B4%23) `159.9K 🔥`
1. [三文鱼其实是海底大肥猪 (Salmon is actually a big fat pig on the bottom of the sea)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%96%87%E9%B1%BC%E5%85%B6%E5%AE%9E%E6%98%AF%E6%B5%B7%E5%BA%95%E5%A4%A7%E8%82%A5%E7%8C%AA%23) `138.6K 🔥`
1. [小酒窝做管乐的花童了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%85%92%E7%AA%9D%E5%81%9A%E7%AE%A1%E4%B9%90%E7%9A%84%E8%8A%B1%E7%AB%A5%E4%BA%86%23) `121.6K 🔥`
1. [B站春晚 夯 (Station B Spring Festival Gala)](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E6%98%A5%E6%99%9A%20%E5%A4%AF%23) `1.6M 🔥` `-29%`
1. [很火但难吃的小吃](https://s.weibo.com/weibo?q=%23%E5%BE%88%E7%81%AB%E4%BD%86%E9%9A%BE%E5%90%83%E7%9A%84%E5%B0%8F%E5%90%83%23) `232.3K 🔥` `-27%`
1. [北京台春晚](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8F%B0%E6%98%A5%E6%99%9A%23) `161.7K 🔥` `-43%`
1. [镖人 武侠群像 (Bodyguard martial arts group portrait)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E6%AD%A6%E4%BE%A0%E7%BE%A4%E5%83%8F%23) `138.0K 🔥` `-21%`
1. [速度滑冰](https://s.weibo.com/weibo?q=%23%E9%80%9F%E5%BA%A6%E6%BB%91%E5%86%B0%23) `111.2K 🔥` `-47%`
1. [B站春晚](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E6%98%A5%E6%99%9A%23) `110.7K 🔥` `-39%`
1. [杨幂朱一龙吻戏 (Yang Mi and Zhu Yilong kiss scene)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%9C%B1%E4%B8%80%E9%BE%99%E5%90%BB%E6%88%8F%23) `109.9K 🔥` `-37%`
1. [谷爱凌说这是4年以来第一次赛大跳台](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%AF%B4%E8%BF%99%E6%98%AF4%E5%B9%B4%E4%BB%A5%E6%9D%A5%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%B5%9B%E5%A4%A7%E8%B7%B3%E5%8F%B0%23) `104.2K 🔥` `-49%`

Updated at 2026-02-17 23:27:49

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
