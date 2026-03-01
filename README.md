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

1. [有人凌晨蹲点退税退了3万多 (Someone stayed early in the morning to get a tax refund and got a refund of more than 30,000 yuan)](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%BA%BA%E5%87%8C%E6%99%A8%E8%B9%B2%E7%82%B9%E9%80%80%E7%A8%8E%E9%80%80%E4%BA%863%E4%B8%87%E5%A4%9A%23) `1.7M 🔥` `NEW`
1. [我国综合国力再上新台阶](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E7%BB%BC%E5%90%88%E5%9B%BD%E5%8A%9B%E5%86%8D%E4%B8%8A%E6%96%B0%E5%8F%B0%E9%98%B6%23) `1.4M 🔥` `NEW`
1. [撞人族已成为日本全国性问题](https://s.weibo.com/weibo?q=%23%E6%92%9E%E4%BA%BA%E6%97%8F%E5%B7%B2%E6%88%90%E4%B8%BA%E6%97%A5%E6%9C%AC%E5%85%A8%E5%9B%BD%E6%80%A7%E9%97%AE%E9%A2%98%23) `847.0K 🔥` `NEW`
1. [郑州中牟自建房倒塌多人被埋系谣言](https://s.weibo.com/weibo?q=%23%E9%83%91%E5%B7%9E%E4%B8%AD%E7%89%9F%E8%87%AA%E5%BB%BA%E6%88%BF%E5%80%92%E5%A1%8C%E5%A4%9A%E4%BA%BA%E8%A2%AB%E5%9F%8B%E7%B3%BB%E8%B0%A3%E8%A8%80%23) `327.8K 🔥` `NEW`
1. [李健巡演官宣](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%81%A5%E5%B7%A1%E6%BC%94%E5%AE%98%E5%AE%A3%23) `323.4K 🔥` `NEW`
1. [哈梅内伊遗体已被找到](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E9%81%97%E4%BD%93%E5%B7%B2%E8%A2%AB%E6%89%BE%E5%88%B0%23) `308.7K 🔥` `NEW`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `306.2K 🔥` `NEW`
1. [迪拜机场被炸滞留中国旅客发声](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E6%8B%9C%E6%9C%BA%E5%9C%BA%E8%A2%AB%E7%82%B8%E6%BB%9E%E7%95%99%E4%B8%AD%E5%9B%BD%E6%97%85%E5%AE%A2%E5%8F%91%E5%A3%B0%23) `300.0K 🔥` `NEW`
1. [委内瑞拉](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%23) `292.7K 🔥` `NEW`
1. [曝哈梅内伊已任命继任者](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E5%B7%B2%E4%BB%BB%E5%91%BD%E7%BB%A7%E4%BB%BB%E8%80%85%23) `289.5K 🔥` `NEW`
1. [迪丽热巴3月份行程图 (Dilireba’s itinerary in March)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B43%E6%9C%88%E4%BB%BD%E8%A1%8C%E7%A8%8B%E5%9B%BE%23) `285.0K 🔥` `NEW`
1. [伊朗反政府人士推倒哈梅内伊雕像](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%8D%E6%94%BF%E5%BA%9C%E4%BA%BA%E5%A3%AB%E6%8E%A8%E5%80%92%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E9%9B%95%E5%83%8F%23) `279.7K 🔥` `NEW`
1. [七种退税方式](https://s.weibo.com/weibo?q=%23%E4%B8%83%E7%A7%8D%E9%80%80%E7%A8%8E%E6%96%B9%E5%BC%8F%23) `238.3K 🔥` `NEW`
1. [伊朗3场世界杯小组赛都在美国球场踢](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%973%E5%9C%BA%E4%B8%96%E7%95%8C%E6%9D%AF%E5%B0%8F%E7%BB%84%E8%B5%9B%E9%83%BD%E5%9C%A8%E7%BE%8E%E5%9B%BD%E7%90%83%E5%9C%BA%E8%B8%A2%23) `218.5K 🔥` `NEW`
1. [伊朗若退出世界杯谁能替代](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%8B%A5%E9%80%80%E5%87%BA%E4%B8%96%E7%95%8C%E6%9D%AF%E8%B0%81%E8%83%BD%E6%9B%BF%E4%BB%A3%23) `216.9K 🔥` `NEW`
1. [你是张栋梁那他是谁](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E6%98%AF%E5%BC%A0%E6%A0%8B%E6%A2%81%E9%82%A3%E4%BB%96%E6%98%AF%E8%B0%81%23) `212.2K 🔥` `NEW`
1. [伊朗称将抵抗到最后一滴血](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%B0%86%E6%8A%B5%E6%8A%97%E5%88%B0%E6%9C%80%E5%90%8E%E4%B8%80%E6%BB%B4%E8%A1%80%23) `210.8K 🔥` `NEW`
1. [迪丽热巴第一语言不是汉语](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%AC%AC%E4%B8%80%E8%AF%AD%E8%A8%80%E4%B8%8D%E6%98%AF%E6%B1%89%E8%AF%AD%23) `206.9K 🔥` `NEW`
1. [伊朗称将开启最猛烈进攻](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%B0%86%E5%BC%80%E5%90%AF%E6%9C%80%E7%8C%9B%E7%83%88%E8%BF%9B%E6%94%BB%23) `201.0K 🔥` `NEW`
1. [方大同拍摄的时候没有封路](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%A4%A7%E5%90%8C%E6%8B%8D%E6%91%84%E7%9A%84%E6%97%B6%E5%80%99%E6%B2%A1%E6%9C%89%E5%B0%81%E8%B7%AF%23) `192.0K 🔥` `NEW`
1. [伊朗总统等将领导国家 (The president of Iran and others will lead the country)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E7%AD%89%E5%B0%86%E9%A2%86%E5%AF%BC%E5%9B%BD%E5%AE%B6%23) `191.9K 🔥` `NEW`
1. [哈梅内伊遇害细节公开](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E9%81%87%E5%AE%B3%E7%BB%86%E8%8A%82%E5%85%AC%E5%BC%80%23) `155.7K 🔥` `NEW`
1. [家属单位楼里藏了个别墅](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E5%B1%9E%E5%8D%95%E4%BD%8D%E6%A5%BC%E9%87%8C%E8%97%8F%E4%BA%86%E4%B8%AA%E5%88%AB%E5%A2%85%23) `134.2K 🔥` `NEW`
1. [中方说谈判之际美以袭击令人震惊](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E8%AF%B4%E8%B0%88%E5%88%A4%E4%B9%8B%E9%99%85%E7%BE%8E%E4%BB%A5%E8%A2%AD%E5%87%BB%E4%BB%A4%E4%BA%BA%E9%9C%87%E6%83%8A%23) `130.5K 🔥` `NEW`
1. [A股行情](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E8%A1%8C%E6%83%85%23) `114.2K 🔥` `NEW`
1. [美军公布对伊朗行动视频](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E5%85%AC%E5%B8%83%E5%AF%B9%E4%BC%8A%E6%9C%97%E8%A1%8C%E5%8A%A8%E8%A7%86%E9%A2%91%23) `113.6K 🔥` `NEW`
1. [天官赐福全新动画内容](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E5%AE%98%E8%B5%90%E7%A6%8F%E5%85%A8%E6%96%B0%E5%8A%A8%E7%94%BB%E5%86%85%E5%AE%B9%23) `109.6K 🔥` `NEW`
1. [哈梅内伊曾挺过入狱暗杀制裁等危机](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E6%9B%BE%E6%8C%BA%E8%BF%87%E5%85%A5%E7%8B%B1%E6%9A%97%E6%9D%80%E5%88%B6%E8%A3%81%E7%AD%89%E5%8D%B1%E6%9C%BA%23) `109.5K 🔥` `NEW`
1. [老一辈助眠就是没轻没重](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%B8%80%E8%BE%88%E5%8A%A9%E7%9C%A0%E5%B0%B1%E6%98%AF%E6%B2%A1%E8%BD%BB%E6%B2%A1%E9%87%8D%23) `107.7K 🔥` `NEW`
1. [超过25岁就不适合劝分了](https://s.weibo.com/weibo?q=%23%E8%B6%85%E8%BF%8725%E5%B2%81%E5%B0%B1%E4%B8%8D%E9%80%82%E5%90%88%E5%8A%9D%E5%88%86%E4%BA%86%23) `100.7K 🔥` `NEW`
1. [一直以为小猫在踹自己 (I always thought the kitten was kicking me)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%9B%B4%E4%BB%A5%E4%B8%BA%E5%B0%8F%E7%8C%AB%E5%9C%A8%E8%B8%B9%E8%87%AA%E5%B7%B1%23) `90.4K 🔥` `NEW`
1. [提醒在伊朗中国公民尽快撤离](https://s.weibo.com/weibo?q=%23%E6%8F%90%E9%86%92%E5%9C%A8%E4%BC%8A%E6%9C%97%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E5%B0%BD%E5%BF%AB%E6%92%A4%E7%A6%BB%23) `90.4K 🔥` `NEW`
1. [桃黑黑秒下播](https://s.weibo.com/weibo?q=%23%E6%A1%83%E9%BB%91%E9%BB%91%E7%A7%92%E4%B8%8B%E6%92%AD%23) `316.8K 🔥` `+58%`
1. [哈梅内伊遇害 (Khamenei killed)](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E9%81%87%E5%AE%B3%23) `8.4M 🔥` `-56%`
1. [哈梅内伊的女儿女婿等遇难](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E7%9A%84%E5%A5%B3%E5%84%BF%E5%A5%B3%E5%A9%BF%E7%AD%89%E9%81%87%E9%9A%BE%23) `712.4K 🔥` `-76%`
1. [油价或出现历史性飙升 (Oil prices may see historic surge)](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E6%88%96%E5%87%BA%E7%8E%B0%E5%8E%86%E5%8F%B2%E6%80%A7%E9%A3%99%E5%8D%87%23) `331.5K 🔥` `-47%`
1. [伊朗政府宣布40天全国哀悼](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%94%BF%E5%BA%9C%E5%AE%A3%E5%B8%8340%E5%A4%A9%E5%85%A8%E5%9B%BD%E5%93%80%E6%82%BC%23) `327.0K 🔥` `-55%`
1. [国防部回应美方指责中方](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%98%B2%E9%83%A8%E5%9B%9E%E5%BA%94%E7%BE%8E%E6%96%B9%E6%8C%87%E8%B4%A3%E4%B8%AD%E6%96%B9%23) `320.4K 🔥` `-57%`
1. [椰树 追求胸大是让婴儿有奶吃 (Coconut tree pursues big breasts so that the baby can have milk to drink)](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E6%A0%91%20%E8%BF%BD%E6%B1%82%E8%83%B8%E5%A4%A7%E6%98%AF%E8%AE%A9%E5%A9%B4%E5%84%BF%E6%9C%89%E5%A5%B6%E5%90%83%23) `297.5K 🔥` `-51%`
1. [杨紫爱自己少吃多睡戒色 (Yang Zi loves herself to eat less, sleep more and reboot)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%88%B1%E8%87%AA%E5%B7%B1%E5%B0%91%E5%90%83%E5%A4%9A%E7%9D%A1%E6%88%92%E8%89%B2%23) `276.8K 🔥` `-32%`
1. [伊朗遭袭小学超150人死亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%81%AD%E8%A2%AD%E5%B0%8F%E5%AD%A6%E8%B6%85150%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `234.8K 🔥` `-61%`
1. [中方呼吁军事行动立即停止](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%91%BC%E5%90%81%E5%86%9B%E4%BA%8B%E8%A1%8C%E5%8A%A8%E7%AB%8B%E5%8D%B3%E5%81%9C%E6%AD%A2%23) `191.8K 🔥` `-95%`
1. [这样的房子才配收我的房租](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%A0%B7%E7%9A%84%E6%88%BF%E5%AD%90%E6%89%8D%E9%85%8D%E6%94%B6%E6%88%91%E7%9A%84%E6%88%BF%E7%A7%9F%23) `191.6K 🔥` `-43%`
1. [迪拜帆船酒店在袭击中起火](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E6%8B%9C%E5%B8%86%E8%88%B9%E9%85%92%E5%BA%97%E5%9C%A8%E8%A2%AD%E5%87%BB%E4%B8%AD%E8%B5%B7%E7%81%AB%23) `177.9K 🔥` `-74%`
1. [婴儿肚皮开裂多器官裸露环绕在外 (The baby's belly is cracked and many organs are exposed)](https://s.weibo.com/weibo?q=%23%E5%A9%B4%E5%84%BF%E8%82%9A%E7%9A%AE%E5%BC%80%E8%A3%82%E5%A4%9A%E5%99%A8%E5%AE%98%E8%A3%B8%E9%9C%B2%E7%8E%AF%E7%BB%95%E5%9C%A8%E5%A4%96%23) `161.6K 🔥` `-48%`
1. [伊朗遭袭小学课本上沾着鲜血](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%81%AD%E8%A2%AD%E5%B0%8F%E5%AD%A6%E8%AF%BE%E6%9C%AC%E4%B8%8A%E6%B2%BE%E7%9D%80%E9%B2%9C%E8%A1%80%23) `142.5K 🔥` `-61%`
1. [退税 (tax refund)](https://s.weibo.com/weibo?q=%23%E9%80%80%E7%A8%8E%23) `128.7K 🔥` `-61%`
1. [美以袭击致伊朗201人死747人伤](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E8%A2%AD%E5%87%BB%E8%87%B4%E4%BC%8A%E6%9C%97201%E4%BA%BA%E6%AD%BB747%E4%BA%BA%E4%BC%A4%23) `128.3K 🔥` `-79%`
1. [伊朗拥有中东最大弹道导弹库存 (Iran has the largest ballistic missile inventory in the Middle East)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8B%A5%E6%9C%89%E4%B8%AD%E4%B8%9C%E6%9C%80%E5%A4%A7%E5%BC%B9%E9%81%93%E5%AF%BC%E5%BC%B9%E5%BA%93%E5%AD%98%23) `104.5K 🔥` `-65%`
1. [王安宇 季总点天灯吗](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%20%E5%AD%A3%E6%80%BB%E7%82%B9%E5%A4%A9%E7%81%AF%E5%90%97%23) `92.1K 🔥` `-43%`

Updated at 2026-03-01 12:34:24

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
