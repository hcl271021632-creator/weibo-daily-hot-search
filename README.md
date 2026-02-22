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

1. [官方通报网传妈祖巡游换童事件 (Official news website reports that Mazu parades to change children)](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%E7%BD%91%E4%BC%A0%E5%A6%88%E7%A5%96%E5%B7%A1%E6%B8%B8%E6%8D%A2%E7%AB%A5%E4%BA%8B%E4%BB%B6%23) `7.6M 🔥` `NEW`
1. [贾玲剧组 女演员可以坐箱子](https://s.weibo.com/weibo?q=%23%E8%B4%BE%E7%8E%B2%E5%89%A7%E7%BB%84%20%E5%A5%B3%E6%BC%94%E5%91%98%E5%8F%AF%E4%BB%A5%E5%9D%90%E7%AE%B1%E5%AD%90%23) `232.6K 🔥` `NEW`
1. [父亲遇3岁儿子坠楼下意识伸手接](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E9%81%873%E5%B2%81%E5%84%BF%E5%AD%90%E5%9D%A0%E6%A5%BC%E4%B8%8B%E6%84%8F%E8%AF%86%E4%BC%B8%E6%89%8B%E6%8E%A5%23) `213.0K 🔥` `NEW`
1. [还原妈祖巡游换童争议全过程](https://s.weibo.com/weibo?q=%23%E8%BF%98%E5%8E%9F%E5%A6%88%E7%A5%96%E5%B7%A1%E6%B8%B8%E6%8D%A2%E7%AB%A5%E4%BA%89%E8%AE%AE%E5%85%A8%E8%BF%87%E7%A8%8B%23) `209.8K 🔥` `NEW`
1. [骏良](https://s.weibo.com/weibo?q=%23%E9%AA%8F%E8%89%AF%23) `191.8K 🔥` `NEW`
1. [谷爱凌戴上3枚奖牌](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%88%B4%E4%B8%8A3%E6%9E%9A%E5%A5%96%E7%89%8C%23) `182.2K 🔥` `NEW`
1. [王楚钦vs卢伟](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6vs%E5%8D%A2%E4%BC%9F%23) `160.8K 🔥` `NEW`
1. [王楚钦3比0卢伟](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A63%E6%AF%940%E5%8D%A2%E4%BC%9F%23) `121.6K 🔥` `NEW`
1. [妈祖巡游事件当事2人均为女孩](https://s.weibo.com/weibo?q=%23%E5%A6%88%E7%A5%96%E5%B7%A1%E6%B8%B8%E4%BA%8B%E4%BB%B6%E5%BD%93%E4%BA%8B2%E4%BA%BA%E5%9D%87%E4%B8%BA%E5%A5%B3%E5%AD%A9%23) `117.3K 🔥` `NEW`
1. [任子威谈到李琰教练哭了](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E5%AD%90%E5%A8%81%E8%B0%88%E5%88%B0%E6%9D%8E%E7%90%B0%E6%95%99%E7%BB%83%E5%93%AD%E4%BA%86%23) `111.3K 🔥` `NEW`
1. [央视解说谷爱凌比赛爆金句 (CCTV’s commentaries on Gu Ailing’s famous quotes during the competition)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E8%A7%A3%E8%AF%B4%E8%B0%B7%E7%88%B1%E5%87%8C%E6%AF%94%E8%B5%9B%E7%88%86%E9%87%91%E5%8F%A5%23) `109.4K 🔥` `NEW`
1. [赫伊森](https://s.weibo.com/weibo?q=%23%E8%B5%AB%E4%BC%8A%E6%A3%AE%23) `108.8K 🔥` `NEW`
1. [大学生唯一拒绝的红包](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F%E5%94%AF%E4%B8%80%E6%8B%92%E7%BB%9D%E7%9A%84%E7%BA%A2%E5%8C%85%23) `103.9K 🔥` `NEW`
1. [李方慧2个倒滑900是独一份的](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%96%B9%E6%85%A72%E4%B8%AA%E5%80%92%E6%BB%91900%E6%98%AF%E7%8B%AC%E4%B8%80%E4%BB%BD%E7%9A%84%23) `99.6K 🔥` `NEW`
1. [骏良前妻](https://s.weibo.com/weibo?q=%23%E9%AA%8F%E8%89%AF%E5%89%8D%E5%A6%BB%23) `93.5K 🔥` `NEW`
1. [2026新春走基层 (2026 New Year Goes to the Grassroots)](https://s.weibo.com/weibo?q=%232026%E6%96%B0%E6%98%A5%E8%B5%B0%E5%9F%BA%E5%B1%82%23) `1.2M 🔥` `+65%`
1. [皇家马德里道歉](https://s.weibo.com/weibo?q=%23%E7%9A%87%E5%AE%B6%E9%A9%AC%E5%BE%B7%E9%87%8C%E9%81%93%E6%AD%89%23) `171.7K 🔥` `+70%`
1. [谷爱凌金牌 (Gu Ailing gold medal)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E9%87%91%E7%89%8C%23) `1.6M 🔥`
1. [虞书欣何与 神仙肉](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%BD%95%E4%B8%8E%20%E7%A5%9E%E4%BB%99%E8%82%89%23) `554.7K 🔥`
1. [谷爱凌第三滑94.75分 (Gu Ailing skated third with 94.75 points)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E7%AC%AC%E4%B8%89%E6%BB%9194.75%E5%88%86%23) `505.5K 🔥`
1. [王濛祝贺谷爱凌李方慧](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E7%A5%9D%E8%B4%BA%E8%B0%B7%E7%88%B1%E5%87%8C%E6%9D%8E%E6%96%B9%E6%85%A7%23) `367.0K 🔥`
1. [女子U型场地决赛 (Women's halfpipe final)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90U%E5%9E%8B%E5%9C%BA%E5%9C%B0%E5%86%B3%E8%B5%9B%23) `365.7K 🔥`
1. [张凌赫 刺棠](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E5%88%BA%E6%A3%A0%23) `349.1K 🔥`
1. [白鹿这眼线是自己画的吧](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E8%BF%99%E7%9C%BC%E7%BA%BF%E6%98%AF%E8%87%AA%E5%B7%B1%E7%94%BB%E7%9A%84%E5%90%A7%23) `271.4K 🔥`
1. [谷爱凌U池卫冕成功 (Gu Ailing successfully defended her title in U Pool)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E6%B1%A0%E5%8D%AB%E5%86%95%E6%88%90%E5%8A%9F%23) `271.1K 🔥`
1. [王楚钦比赛](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E6%AF%94%E8%B5%9B%23) `240.7K 🔥`
1. [拾石村小妈祖巡游终于有翻译版本了](https://s.weibo.com/weibo?q=%23%E6%8B%BE%E7%9F%B3%E6%9D%91%E5%B0%8F%E5%A6%88%E7%A5%96%E5%B7%A1%E6%B8%B8%E7%BB%88%E4%BA%8E%E6%9C%89%E7%BF%BB%E8%AF%91%E7%89%88%E6%9C%AC%E4%BA%86%23) `238.5K 🔥`
1. [64岁演员江华暴瘦引网友担忧](https://s.weibo.com/weibo?q=%2364%E5%B2%81%E6%BC%94%E5%91%98%E6%B1%9F%E5%8D%8E%E6%9A%B4%E7%98%A6%E5%BC%95%E7%BD%91%E5%8F%8B%E6%8B%85%E5%BF%A7%23) `226.6K 🔥`
1. [大年初五8岁男童虎跳峡坠崖遇难 (An 8-year-old boy died after falling off a cliff in Tiger Leaping Gorge on the fifth day of the Lunar New Year)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%948%E5%B2%81%E7%94%B7%E7%AB%A5%E8%99%8E%E8%B7%B3%E5%B3%A1%E5%9D%A0%E5%B4%96%E9%81%87%E9%9A%BE%23) `209.8K 🔥`
1. [日本一寺庙举行裸祭上万名男性参加](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E4%B8%80%E5%AF%BA%E5%BA%99%E4%B8%BE%E8%A1%8C%E8%A3%B8%E7%A5%AD%E4%B8%8A%E4%B8%87%E5%90%8D%E7%94%B7%E6%80%A7%E5%8F%82%E5%8A%A0%23) `193.4K 🔥`
1. [贝加尔湖溺亡中国游客遗体全部打捞上岸 (All bodies of Chinese tourists who drowned in Lake Baikal were recovered)](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E6%BA%BA%E4%BA%A1%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E9%81%97%E4%BD%93%E5%85%A8%E9%83%A8%E6%89%93%E6%8D%9E%E4%B8%8A%E5%B2%B8%23) `161.7K 🔥`
1. [北京市委市政府贺电](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%B8%82%E5%A7%94%E5%B8%82%E6%94%BF%E5%BA%9C%E8%B4%BA%E7%94%B5%23) `155.2K 🔥`
1. [李方慧回应银牌](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%96%B9%E6%85%A7%E5%9B%9E%E5%BA%94%E9%93%B6%E7%89%8C%23) `138.2K 🔥`
1. [仙逆 (Immortal Ni)](https://s.weibo.com/weibo?q=%23%E4%BB%99%E9%80%86%23) `102.8K 🔥`
1. [谷爱凌唱国歌](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%94%B1%E5%9B%BD%E6%AD%8C%23) `373.0K 🔥` `-38%`
1. [人生去留 (Stay or go in life)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%94%9F%E5%8E%BB%E7%95%99%23) `367.4K 🔥` `-51%`
1. [谷爱凌追平王濛冬奥奖牌纪录 (Gu Ailing equals Wang Meng’s Winter Olympic medal record)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%BF%BD%E5%B9%B3%E7%8E%8B%E6%BF%9B%E5%86%AC%E5%A5%A5%E5%A5%96%E7%89%8C%E7%BA%AA%E5%BD%95%23) `271.5K 🔥` `-70%`
1. [孟子义李昀锐 四搭](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%20%E5%9B%9B%E6%90%AD%23) `271.5K 🔥` `-30%`
1. [中国队5金4银6铜收官 (The Chinese team finished with 5 golds, 4 silvers and 6 bronzes)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F5%E9%87%914%E9%93%B66%E9%93%9C%E6%94%B6%E5%AE%98%23) `270.8K 🔥` `-34%`
1. [谷爱凌 九亿少女的梦](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%20%E4%B9%9D%E4%BA%BF%E5%B0%91%E5%A5%B3%E7%9A%84%E6%A2%A6%23) `209.6K 🔥` `-52%`
1. [DK战胜T1 (DK defeated T1)](https://s.weibo.com/weibo?q=%23DK%E6%88%98%E8%83%9CT1%23) `188.1K 🔥` `-52%`
1. [谷爱凌金色蝴蝶结](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E9%87%91%E8%89%B2%E8%9D%B4%E8%9D%B6%E7%BB%93%23) `178.7K 🔥` `-35%`
1. [果然爱情公寓不是拍给当时的我们看的](https://s.weibo.com/weibo?q=%23%E6%9E%9C%E7%84%B6%E7%88%B1%E6%83%85%E5%85%AC%E5%AF%93%E4%B8%8D%E6%98%AF%E6%8B%8D%E7%BB%99%E5%BD%93%E6%97%B6%E7%9A%84%E6%88%91%E4%BB%AC%E7%9C%8B%E7%9A%84%23) `151.6K 🔥` `-32%`
1. [孙耀威当年真没骗人简直是仙女下凡](https://s.weibo.com/weibo?q=%23%E5%AD%99%E8%80%80%E5%A8%81%E5%BD%93%E5%B9%B4%E7%9C%9F%E6%B2%A1%E9%AA%97%E4%BA%BA%E7%AE%80%E7%9B%B4%E6%98%AF%E4%BB%99%E5%A5%B3%E4%B8%8B%E5%87%A1%23) `138.2K 🔥` `-34%`
1. [李峋的vlog全是公主 (Li Xun’s vlogs are all about princesses)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%B3%8B%E7%9A%84vlog%E5%85%A8%E6%98%AF%E5%85%AC%E4%B8%BB%23) `115.5K 🔥` `-22%`
1. [淀粉肠进入瑜伽裤时代 (Starch intestine enters the era of yoga pants)](https://s.weibo.com/weibo?q=%23%E6%B7%80%E7%B2%89%E8%82%A0%E8%BF%9B%E5%85%A5%E7%91%9C%E4%BC%BD%E8%A3%A4%E6%97%B6%E4%BB%A3%23) `106.2K 🔥` `-26%`
1. [韩国队抗议米兰冬奥至少4次印错国旗 (The South Korean team protested at least 4 times the wrong flag was printed at the Milan Winter Olympics)](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E9%98%9F%E6%8A%97%E8%AE%AE%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E8%87%B3%E5%B0%914%E6%AC%A1%E5%8D%B0%E9%94%99%E5%9B%BD%E6%97%97%23) `95.5K 🔥` `-28%`
1. [杨幂演技](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%BC%94%E6%8A%80%23) `94.9K 🔥` `-24%`
1. [DK让二追三T1](https://s.weibo.com/weibo?q=%23DK%E8%AE%A9%E4%BA%8C%E8%BF%BD%E4%B8%89T1%23) `89.8K 🔥` `-40%`
1. [侯明昊直播](https://s.weibo.com/weibo?q=%23%E4%BE%AF%E6%98%8E%E6%98%8A%E7%9B%B4%E6%92%AD%23) `89.2K 🔥` `-29%`
1. [短道速滑](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `87.3K 🔥` `-64%`

Updated at 2026-02-22 21:58:12

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
