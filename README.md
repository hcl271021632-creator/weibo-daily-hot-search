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

1. [西安大雪 (Heavy snow in Xi'an)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%AE%89%E5%A4%A7%E9%9B%AA%23) `1.1M 🔥` `NEW`
1. [大年初七新的旅程开启](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%83%E6%96%B0%E7%9A%84%E6%97%85%E7%A8%8B%E5%BC%80%E5%90%AF%23) `671.7K 🔥` `NEW`
1. [杨幂 这么来历不明的二维码也要扫吗](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%20%E8%BF%99%E4%B9%88%E6%9D%A5%E5%8E%86%E4%B8%8D%E6%98%8E%E7%9A%84%E4%BA%8C%E7%BB%B4%E7%A0%81%E4%B9%9F%E8%A6%81%E6%89%AB%E5%90%97%23) `665.6K 🔥` `NEW`
1. [史上最贵iPhone要来了](https://s.weibo.com/weibo?q=%23%E5%8F%B2%E4%B8%8A%E6%9C%80%E8%B4%B5iPhone%E8%A6%81%E6%9D%A5%E4%BA%86%23) `544.2K 🔥` `NEW`
1. [父母托关系找的工作应该去吗](https://s.weibo.com/weibo?q=%23%E7%88%B6%E6%AF%8D%E6%89%98%E5%85%B3%E7%B3%BB%E6%89%BE%E7%9A%84%E5%B7%A5%E4%BD%9C%E5%BA%94%E8%AF%A5%E5%8E%BB%E5%90%97%23) `333.5K 🔥` `NEW`
1. [谷爱凌商业价值排冬奥运动员第一](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%95%86%E4%B8%9A%E4%BB%B7%E5%80%BC%E6%8E%92%E5%86%AC%E5%A5%A5%E8%BF%90%E5%8A%A8%E5%91%98%E7%AC%AC%E4%B8%80%23) `295.3K 🔥` `NEW`
1. [大理4公里拖车费1400元](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%90%864%E5%85%AC%E9%87%8C%E6%8B%96%E8%BD%A6%E8%B4%B91400%E5%85%83%23) `260.6K 🔥` `NEW`
1. [尼泊尔巴士坠河致18死20余伤](https://s.weibo.com/weibo?q=%23%E5%B0%BC%E6%B3%8A%E5%B0%94%E5%B7%B4%E5%A3%AB%E5%9D%A0%E6%B2%B3%E8%87%B418%E6%AD%BB20%E4%BD%99%E4%BC%A4%23) `192.1K 🔥` `NEW`
1. [周洁琼不参与I.O.I回归](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B4%81%E7%90%BC%E4%B8%8D%E5%8F%82%E4%B8%8EI.O.I%E5%9B%9E%E5%BD%92%23) `170.3K 🔥` `NEW`
1. [谷爱凌夺冠动作形成完美生物力学闭环](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A4%BA%E5%86%A0%E5%8A%A8%E4%BD%9C%E5%BD%A2%E6%88%90%E5%AE%8C%E7%BE%8E%E7%94%9F%E7%89%A9%E5%8A%9B%E5%AD%A6%E9%97%AD%E7%8E%AF%23) `159.9K 🔥` `NEW`
1. [大侦探 (great detective)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BE%A6%E6%8E%A2%23) `153.0K 🔥` `NEW`
1. [谷爱凌脑回路](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%84%91%E5%9B%9E%E8%B7%AF%23) `141.9K 🔥` `NEW`
1. [第一个吃甘蔗比吃螃蟹更厉害](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%90%83%E7%94%98%E8%94%97%E6%AF%94%E5%90%83%E8%9E%83%E8%9F%B9%E6%9B%B4%E5%8E%89%E5%AE%B3%23) `125.9K 🔥` `NEW`
1. [陈赫给女儿的红包里是试卷](https://s.weibo.com/weibo?q=%23%E9%99%88%E8%B5%AB%E7%BB%99%E5%A5%B3%E5%84%BF%E7%9A%84%E7%BA%A2%E5%8C%85%E9%87%8C%E6%98%AF%E8%AF%95%E5%8D%B7%23) `123.7K 🔥` `NEW`
1. [刘品言抱女儿打牌](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%93%81%E8%A8%80%E6%8A%B1%E5%A5%B3%E5%84%BF%E6%89%93%E7%89%8C%23) `122.3K 🔥` `NEW`
1. [T1让LCK黄牛破防](https://s.weibo.com/weibo?q=%23T1%E8%AE%A9LCK%E9%BB%84%E7%89%9B%E7%A0%B4%E9%98%B2%23) `120.4K 🔥` `NEW`
1. [吕小雨一个月暴瘦20斤](https://s.weibo.com/weibo?q=%23%E5%90%95%E5%B0%8F%E9%9B%A8%E4%B8%80%E4%B8%AA%E6%9C%88%E6%9A%B4%E7%98%A620%E6%96%A4%23) `120.4K 🔥` `NEW`
1. [董璇张维伊带小酒窝抓螃蟹](https://s.weibo.com/weibo?q=%23%E8%91%A3%E7%92%87%E5%BC%A0%E7%BB%B4%E4%BC%8A%E5%B8%A6%E5%B0%8F%E9%85%92%E7%AA%9D%E6%8A%93%E8%9E%83%E8%9F%B9%23) `120.3K 🔥` `NEW`
1. [考研成绩什么时候出](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E6%88%90%E7%BB%A9%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%E5%87%BA%23) `111.7K 🔥` `NEW`
1. [谷爱凌马上牛好灵](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E9%A9%AC%E4%B8%8A%E7%89%9B%E5%A5%BD%E7%81%B5%23) `109.5K 🔥` `NEW`
1. [经常吃太饱身体会发生什么变化 (What will happen to your body if you eat too much often?)](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E5%B8%B8%E5%90%83%E5%A4%AA%E9%A5%B1%E8%BA%AB%E4%BD%93%E4%BC%9A%E5%8F%91%E7%94%9F%E4%BB%80%E4%B9%88%E5%8F%98%E5%8C%96%23) `104.0K 🔥` `NEW`
1. [慕慕昭昭CP](https://s.weibo.com/weibo?q=%23%E6%85%95%E6%85%95%E6%98%AD%E6%98%ADCP%23) `101.6K 🔥` `NEW`
1. [不让江山 男女主没有感情线](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%20%E7%94%B7%E5%A5%B3%E4%B8%BB%E6%B2%A1%E6%9C%89%E6%84%9F%E6%83%85%E7%BA%BF%23) `99.3K 🔥` `NEW`
1. [沈梦辰杜海涛同游德国](https://s.weibo.com/weibo?q=%23%E6%B2%88%E6%A2%A6%E8%BE%B0%E6%9D%9C%E6%B5%B7%E6%B6%9B%E5%90%8C%E6%B8%B8%E5%BE%B7%E5%9B%BD%23) `88.1K 🔥` `NEW`
1. [沈腾飞驰人生3冠军车原型](https://s.weibo.com/weibo?q=%23%E6%B2%88%E8%85%BE%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E5%86%A0%E5%86%9B%E8%BD%A6%E5%8E%9F%E5%9E%8B%23) `88.1K 🔥` `NEW`
1. [上海爸爸说现在不是拼命赚钱的时候](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E7%88%B8%E7%88%B8%E8%AF%B4%E7%8E%B0%E5%9C%A8%E4%B8%8D%E6%98%AF%E6%8B%BC%E5%91%BD%E8%B5%9A%E9%92%B1%E7%9A%84%E6%97%B6%E5%80%99%23) `87.5K 🔥` `NEW`
1. [冬奥运动员收入前五](https://s.weibo.com/weibo?q=%23%E5%86%AC%E5%A5%A5%E8%BF%90%E5%8A%A8%E5%91%98%E6%94%B6%E5%85%A5%E5%89%8D%E4%BA%94%23) `85.0K 🔥` `NEW`
1. [江浙沪接财神接的是GDP吗](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E6%B5%99%E6%B2%AA%E6%8E%A5%E8%B4%A2%E7%A5%9E%E6%8E%A5%E7%9A%84%E6%98%AFGDP%E5%90%97%23) `76.9K 🔥` `NEW`
1. [新疆尉犁5.1级地震](https://s.weibo.com/weibo?q=%23%E6%96%B0%E7%96%86%E5%B0%89%E7%8A%815.1%E7%BA%A7%E5%9C%B0%E9%9C%87%23) `74.5K 🔥` `NEW`
1. [徐梦桃为传好运给王心迪忍着没洗澡](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E4%B8%BA%E4%BC%A0%E5%A5%BD%E8%BF%90%E7%BB%99%E7%8E%8B%E5%BF%83%E8%BF%AA%E5%BF%8D%E7%9D%80%E6%B2%A1%E6%B4%97%E6%BE%A1%23) `69.3K 🔥` `NEW`
1. [谷爱凌说我生而为赢 (Gu Ailing said that I was born to win)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%AF%B4%E6%88%91%E7%94%9F%E8%80%8C%E4%B8%BA%E8%B5%A2%23) `65.9K 🔥` `NEW`
1. [金裕贞短发造型](https://s.weibo.com/weibo?q=%23%E9%87%91%E8%A3%95%E8%B4%9E%E7%9F%AD%E5%8F%91%E9%80%A0%E5%9E%8B%23) `145.7K 🔥` `+113%`
1. [江湖夜雨十年灯 (Rivers and lakes night rain ten years of lanterns)](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E6%B9%96%E5%A4%9C%E9%9B%A8%E5%8D%81%E5%B9%B4%E7%81%AF%23) `112.0K 🔥` `+39%`
1. [谷爱凌晒金牌打脸外媒 (Gu Ailing slapped foreign media in the face after showing off her gold medal)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%99%92%E9%87%91%E7%89%8C%E6%89%93%E8%84%B8%E5%A4%96%E5%AA%92%23) `819.4K 🔥`
1. [四川女婿黄子韬在家也得穿省服](https://s.weibo.com/weibo?q=%23%E5%9B%9B%E5%B7%9D%E5%A5%B3%E5%A9%BF%E9%BB%84%E5%AD%90%E9%9F%AC%E5%9C%A8%E5%AE%B6%E4%B9%9F%E5%BE%97%E7%A9%BF%E7%9C%81%E6%9C%8D%23) `157.2K 🔥`
1. [离婚发现女儿非亲生判还抚养费](https://s.weibo.com/weibo?q=%23%E7%A6%BB%E5%A9%9A%E5%8F%91%E7%8E%B0%E5%A5%B3%E5%84%BF%E9%9D%9E%E4%BA%B2%E7%94%9F%E5%88%A4%E8%BF%98%E6%8A%9A%E5%85%BB%E8%B4%B9%23) `148.8K 🔥`
1. [曝厚本被不让江山除名](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%8E%9A%E6%9C%AC%E8%A2%AB%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E9%99%A4%E5%90%8D%23) `125.3K 🔥`
1. [陈妍希说林心如女儿长的太好看了](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A6%8D%E5%B8%8C%E8%AF%B4%E6%9E%97%E5%BF%83%E5%A6%82%E5%A5%B3%E5%84%BF%E9%95%BF%E7%9A%84%E5%A4%AA%E5%A5%BD%E7%9C%8B%E4%BA%86%23) `125.2K 🔥`
1. [韩媒称韩唯一领先技术被中国反超](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%AA%92%E7%A7%B0%E9%9F%A9%E5%94%AF%E4%B8%80%E9%A2%86%E5%85%88%E6%8A%80%E6%9C%AF%E8%A2%AB%E4%B8%AD%E5%9B%BD%E5%8F%8D%E8%B6%85%23) `113.8K 🔥`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `79.6K 🔥`
1. [陈丽君自曝把命都交代出去](https://s.weibo.com/weibo?q=%23%E9%99%88%E4%B8%BD%E5%90%9B%E8%87%AA%E6%9B%9D%E6%8A%8A%E5%91%BD%E9%83%BD%E4%BA%A4%E4%BB%A3%E5%87%BA%E5%8E%BB%23) `223.7K 🔥` `-31%`
1. [神仙肉](https://s.weibo.com/weibo?q=%23%E7%A5%9E%E4%BB%99%E8%82%89%23) `178.5K 🔥` `-86%`
1. [陈飞宇回应李峋你知道吗](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E5%9B%9E%E5%BA%94%E6%9D%8E%E5%B3%8B%E4%BD%A0%E7%9F%A5%E9%81%93%E5%90%97%23) `145.5K 🔥` `-57%`
1. [徐梦桃夺冠当天收到1600多条信息 (Xu Mengtao received more than 1,600 messages on the day she won the championship)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E5%A4%BA%E5%86%A0%E5%BD%93%E5%A4%A9%E6%94%B6%E5%88%B01600%E5%A4%9A%E6%9D%A1%E4%BF%A1%E6%81%AF%23) `124.7K 🔥` `-55%`
1. [墨西哥毒枭身亡引发报复行动](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A5%E6%AF%92%E6%9E%AD%E8%BA%AB%E4%BA%A1%E5%BC%95%E5%8F%91%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%23) `119.5K 🔥` `-64%`
1. [女子深陷迷你贷400元分36期](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%B7%B1%E9%99%B7%E8%BF%B7%E4%BD%A0%E8%B4%B7400%E5%85%83%E5%88%8636%E6%9C%9F%23) `114.0K 🔥` `-48%`
1. [XG制作人SIMON被捕](https://s.weibo.com/weibo?q=%23XG%E5%88%B6%E4%BD%9C%E4%BA%BASIMON%E8%A2%AB%E6%8D%95%23) `108.0K 🔥` `-40%`
1. [吴京回应镖人票房逆袭](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%E5%9B%9E%E5%BA%94%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%E9%80%86%E8%A2%AD%23) `107.7K 🔥` `-40%`
1. [谷爱凌晒奶奶戴奖牌合照 (Gu Ailing posted a photo of her grandma wearing a medal)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%99%92%E5%A5%B6%E5%A5%B6%E6%88%B4%E5%A5%96%E7%89%8C%E5%90%88%E7%85%A7%23) `88.1K 🔥` `-51%`
1. [越来越高级的智能马桶让人不敢坐](https://s.weibo.com/weibo?q=%23%E8%B6%8A%E6%9D%A5%E8%B6%8A%E9%AB%98%E7%BA%A7%E7%9A%84%E6%99%BA%E8%83%BD%E9%A9%AC%E6%A1%B6%E8%AE%A9%E4%BA%BA%E4%B8%8D%E6%95%A2%E5%9D%90%23) `77.0K 🔥` `-41%`

Updated at 2026-02-23 13:51:39

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
