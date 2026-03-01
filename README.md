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

1. [秦岚嗓子哑了三年 (Qin Lan has been hoarse for three years)](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%B2%9A%E5%97%93%E5%AD%90%E5%93%91%E4%BA%86%E4%B8%89%E5%B9%B4%23) `225.4K 🔥` `NEW`
1. [短剧四小花旦同框](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E5%9B%9B%E5%B0%8F%E8%8A%B1%E6%97%A6%E5%90%8C%E6%A1%86%23) `196.7K 🔥` `NEW`
1. [哈梅内伊住所遭袭前后对比景象](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E4%BD%8F%E6%89%80%E9%81%AD%E8%A2%AD%E5%89%8D%E5%90%8E%E5%AF%B9%E6%AF%94%E6%99%AF%E8%B1%A1%23) `187.3K 🔥` `NEW`
1. [王者荣耀 TF四代](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%80%85%E8%8D%A3%E8%80%80%20TF%E5%9B%9B%E4%BB%A3%23) `181.0K 🔥` `NEW`
1. [中东局势解读](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%B8%9C%E5%B1%80%E5%8A%BF%E8%A7%A3%E8%AF%BB%23) `144.4K 🔥` `NEW`
1. [2岁小孩高铁车厢唱歌旅客大打出手](https://s.weibo.com/weibo?q=%232%E5%B2%81%E5%B0%8F%E5%AD%A9%E9%AB%98%E9%93%81%E8%BD%A6%E5%8E%A2%E5%94%B1%E6%AD%8C%E6%97%85%E5%AE%A2%E5%A4%A7%E6%89%93%E5%87%BA%E6%89%8B%23) `126.0K 🔥` `NEW`
1. [全军启用预备役人员证](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%86%9B%E5%90%AF%E7%94%A8%E9%A2%84%E5%A4%87%E5%BD%B9%E4%BA%BA%E5%91%98%E8%AF%81%23) `95.9K 🔥` `NEW`
1. [梁洁郭俊辰国内旅游找了外国导游](https://s.weibo.com/weibo?q=%23%E6%A2%81%E6%B4%81%E9%83%AD%E4%BF%8A%E8%BE%B0%E5%9B%BD%E5%86%85%E6%97%85%E6%B8%B8%E6%89%BE%E4%BA%86%E5%A4%96%E5%9B%BD%E5%AF%BC%E6%B8%B8%23) `95.2K 🔥` `NEW`
1. [官俊臣参加高考成人礼](https://s.weibo.com/weibo?q=%23%E5%AE%98%E4%BF%8A%E8%87%A3%E5%8F%82%E5%8A%A0%E9%AB%98%E8%80%83%E6%88%90%E4%BA%BA%E7%A4%BC%23) `93.9K 🔥` `NEW`
1. [詹姆斯返老还童](https://s.weibo.com/weibo?q=%23%E8%A9%B9%E5%A7%86%E6%96%AF%E8%BF%94%E8%80%81%E8%BF%98%E7%AB%A5%23) `90.9K 🔥` `NEW`
1. [川渝盒饭vs东北盒饭 (Sichuan and Chongqing lunch boxes vs. Northeastern lunch boxes)](https://s.weibo.com/weibo?q=%23%E5%B7%9D%E6%B8%9D%E7%9B%92%E9%A5%ADvs%E4%B8%9C%E5%8C%97%E7%9B%92%E9%A5%AD%23) `90.4K 🔥` `NEW`
1. [到底什么值得我们错过四季](https://s.weibo.com/weibo?q=%23%E5%88%B0%E5%BA%95%E4%BB%80%E4%B9%88%E5%80%BC%E5%BE%97%E6%88%91%E4%BB%AC%E9%94%99%E8%BF%87%E5%9B%9B%E5%AD%A3%23) `85.0K 🔥` `NEW`
1. [当你想体验寄人篱下的感觉时](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BD%A0%E6%83%B3%E4%BD%93%E9%AA%8C%E5%AF%84%E4%BA%BA%E7%AF%B1%E4%B8%8B%E7%9A%84%E6%84%9F%E8%A7%89%E6%97%B6%23) `77.5K 🔥` `NEW`
1. [孙颖莎11比2陈熠](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E11%E6%AF%942%E9%99%88%E7%86%A0%23) `77.5K 🔥` `NEW`
1. [小米17Ultra](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B317Ultra%23) `77.5K 🔥` `NEW`
1. [当你摸狗时它的小心思](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BD%A0%E6%91%B8%E7%8B%97%E6%97%B6%E5%AE%83%E7%9A%84%E5%B0%8F%E5%BF%83%E6%80%9D%23) `77.4K 🔥` `NEW`
1. [伊朗确认继任者后或将扩大反击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A1%AE%E8%AE%A4%E7%BB%A7%E4%BB%BB%E8%80%85%E5%90%8E%E6%88%96%E5%B0%86%E6%89%A9%E5%A4%A7%E5%8F%8D%E5%87%BB%23) `1.4M 🔥` `+1082%`
1. [女子感觉金手镯变轻报警前男友自首](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%84%9F%E8%A7%89%E9%87%91%E6%89%8B%E9%95%AF%E5%8F%98%E8%BD%BB%E6%8A%A5%E8%AD%A6%E5%89%8D%E7%94%B7%E5%8F%8B%E8%87%AA%E9%A6%96%23) `1.0M 🔥` `+389%`
1. [中国人民永远都要保持居安思危的清醒](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B0%91%E6%B0%B8%E8%BF%9C%E9%83%BD%E8%A6%81%E4%BF%9D%E6%8C%81%E5%B1%85%E5%AE%89%E6%80%9D%E5%8D%B1%E7%9A%84%E6%B8%85%E9%86%92%23) `443.3K 🔥` `+123%`
1. [哈梅内伊遇害 (Khamenei killed)](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E9%81%87%E5%AE%B3%23) `5.1M 🔥`
1. [伊朗导弹击中以军总参谋部](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%87%BB%E4%B8%AD%E4%BB%A5%E5%86%9B%E6%80%BB%E5%8F%82%E8%B0%8B%E9%83%A8%23) `421.5K 🔥`
1. [携程回应大马士革到上海机票550万 (Ctrip responds to air tickets from Damascus to Shanghai costing 5.5 million)](https://s.weibo.com/weibo?q=%23%E6%90%BA%E7%A8%8B%E5%9B%9E%E5%BA%94%E5%A4%A7%E9%A9%AC%E5%A3%AB%E9%9D%A9%E5%88%B0%E4%B8%8A%E6%B5%B7%E6%9C%BA%E7%A5%A8550%E4%B8%87%23) `216.0K 🔥`
1. [女童投喂狮子被拖曳涉事动物园停业](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%AB%A5%E6%8A%95%E5%96%82%E7%8B%AE%E5%AD%90%E8%A2%AB%E6%8B%96%E6%9B%B3%E6%B6%89%E4%BA%8B%E5%8A%A8%E7%89%A9%E5%9B%AD%E5%81%9C%E4%B8%9A%23) `117.5K 🔥`
1. [女孩自拍被吐槽长得吓人](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E8%87%AA%E6%8B%8D%E8%A2%AB%E5%90%90%E6%A7%BD%E9%95%BF%E5%BE%97%E5%90%93%E4%BA%BA%23) `98.5K 🔥`
1. [中方呼吁军事行动立即停止](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%91%BC%E5%90%81%E5%86%9B%E4%BA%8B%E8%A1%8C%E5%8A%A8%E7%AB%8B%E5%8D%B3%E5%81%9C%E6%AD%A2%23) `88.1K 🔥`
1. [退税 (tax refund)](https://s.weibo.com/weibo?q=%23%E9%80%80%E7%A8%8E%23) `77.4K 🔥`
1. [王安宇 季总点天灯吗](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%20%E5%AD%A3%E6%80%BB%E7%82%B9%E5%A4%A9%E7%81%AF%E5%90%97%23) `77.3K 🔥`
1. [网警提醒规避考研查分陷阱 (Internet police remind you to avoid the trap of postgraduate entrance examination score checking)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%AD%A6%E6%8F%90%E9%86%92%E8%A7%84%E9%81%BF%E8%80%83%E7%A0%94%E6%9F%A5%E5%88%86%E9%99%B7%E9%98%B1%23) `782.2K 🔥` `-32%`
1. [撞人族已成为日本全国性问题](https://s.weibo.com/weibo?q=%23%E6%92%9E%E4%BA%BA%E6%97%8F%E5%B7%B2%E6%88%90%E4%B8%BA%E6%97%A5%E6%9C%AC%E5%85%A8%E5%9B%BD%E6%80%A7%E9%97%AE%E9%A2%98%23) `320.0K 🔥` `-23%`
1. [有人凌晨蹲点退税退了3万多 (Someone stayed early in the morning to get a tax refund and got a refund of more than 30,000 yuan)](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%BA%BA%E5%87%8C%E6%99%A8%E8%B9%B2%E7%82%B9%E9%80%80%E7%A8%8E%E9%80%80%E4%BA%863%E4%B8%87%E5%A4%9A%23) `308.7K 🔥` `-78%`
1. [家属单位楼里藏了个别墅](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E5%B1%9E%E5%8D%95%E4%BD%8D%E6%A5%BC%E9%87%8C%E8%97%8F%E4%BA%86%E4%B8%AA%E5%88%AB%E5%A2%85%23) `282.7K 🔥` `-30%`
1. [孙颖莎vs陈熠](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E9%99%88%E7%86%A0%23) `229.1K 🔥` `-41%`
1. [杨幂 得罪就得罪吧](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%20%E5%BE%97%E7%BD%AA%E5%B0%B1%E5%BE%97%E7%BD%AA%E5%90%A7%23) `220.5K 🔥` `-34%`
1. [椰树 追求胸大是让婴儿有奶吃 (Coconut tree pursues big breasts so that the baby can have milk to drink)](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E6%A0%91%20%E8%BF%BD%E6%B1%82%E8%83%B8%E5%A4%A7%E6%98%AF%E8%AE%A9%E5%A9%B4%E5%84%BF%E6%9C%89%E5%A5%B6%E5%90%83%23) `206.3K 🔥` `-35%`
1. [反美领袖哈梅内伊的一生](https://s.weibo.com/weibo?q=%23%E5%8F%8D%E7%BE%8E%E9%A2%86%E8%A2%96%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E7%9A%84%E4%B8%80%E7%94%9F%23) `199.4K 🔥` `-31%`
1. [烤香蕉 (Grilled Banana)](https://s.weibo.com/weibo?q=%23%E7%83%A4%E9%A6%99%E8%95%89%23) `180.1K 🔥` `-51%`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `144.4K 🔥` `-28%`
1. [杨紫爱自己少吃多睡戒色 (Yang Zi loves herself to eat less, sleep more and reboot)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%88%B1%E8%87%AA%E5%B7%B1%E5%B0%91%E5%90%83%E5%A4%9A%E7%9D%A1%E6%88%92%E8%89%B2%23) `143.6K 🔥` `-27%`
1. [迪丽热巴3月份行程图 (Dilireba’s itinerary in March)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B43%E6%9C%88%E4%BB%BD%E8%A1%8C%E7%A8%8B%E5%9B%BE%23) `133.2K 🔥` `-42%`
1. [苏新皓抢到TOP专辑了](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E6%96%B0%E7%9A%93%E6%8A%A2%E5%88%B0TOP%E4%B8%93%E8%BE%91%E4%BA%86%23) `113.0K 🔥` `-47%`
1. [EXO参加金俊勉哥哥婚礼](https://s.weibo.com/weibo?q=%23EXO%E5%8F%82%E5%8A%A0%E9%87%91%E4%BF%8A%E5%8B%89%E5%93%A5%E5%93%A5%E5%A9%9A%E7%A4%BC%23) `99.3K 🔥` `-35%`
1. [迪丽热巴第一语言不是汉语](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%AC%AC%E4%B8%80%E8%AF%AD%E8%A8%80%E4%B8%8D%E6%98%AF%E6%B1%89%E8%AF%AD%23) `97.7K 🔥` `-35%`
1. [桃黑黑秒下播](https://s.weibo.com/weibo?q=%23%E6%A1%83%E9%BB%91%E9%BB%91%E7%A7%92%E4%B8%8B%E6%92%AD%23) `93.9K 🔥` `-35%`
1. [李健巡演官宣](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%81%A5%E5%B7%A1%E6%BC%94%E5%AE%98%E5%AE%A3%23) `93.9K 🔥` `-76%`
1. [28岁男子性格淡漠误诊精分治疗2年](https://s.weibo.com/weibo?q=%2328%E5%B2%81%E7%94%B7%E5%AD%90%E6%80%A7%E6%A0%BC%E6%B7%A1%E6%BC%A0%E8%AF%AF%E8%AF%8A%E7%B2%BE%E5%88%86%E6%B2%BB%E7%96%972%E5%B9%B4%23) `93.9K 🔥` `-73%`
1. [婴儿肚皮开裂多器官裸露环绕在外 (The baby's belly is cracked and many organs are exposed)](https://s.weibo.com/weibo?q=%23%E5%A9%B4%E5%84%BF%E8%82%9A%E7%9A%AE%E5%BC%80%E8%A3%82%E5%A4%9A%E5%99%A8%E5%AE%98%E8%A3%B8%E9%9C%B2%E7%8E%AF%E7%BB%95%E5%9C%A8%E5%A4%96%23) `88.2K 🔥` `-25%`
1. [伊朗3场世界杯小组赛都在美国球场踢](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%973%E5%9C%BA%E4%B8%96%E7%95%8C%E6%9D%AF%E5%B0%8F%E7%BB%84%E8%B5%9B%E9%83%BD%E5%9C%A8%E7%BE%8E%E5%9B%BD%E7%90%83%E5%9C%BA%E8%B8%A2%23) `87.9K 🔥` `-45%`
1. [陈妍希状态满40减20 (Michelle Chen gets 20 off if her status reaches 40)](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A6%8D%E5%B8%8C%E7%8A%B6%E6%80%81%E6%BB%A140%E5%87%8F20%23) `83.3K 🔥` `-60%`
1. [超过25岁就不适合劝分了](https://s.weibo.com/weibo?q=%23%E8%B6%85%E8%BF%8725%E5%B2%81%E5%B0%B1%E4%B8%8D%E9%80%82%E5%90%88%E5%8A%9D%E5%88%86%E4%BA%86%23) `77.3K 🔥` `-29%`

Updated at 2026-03-01 14:28:04

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
