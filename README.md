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

1. [伊朗革命卫队报复行动升级 (Iran's Revolutionary Guards escalate retaliatory actions)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%E5%8D%87%E7%BA%A7%23) `261.1K 🔥` `NEW`
1. [胡兵家有瞿颖的专属卧室](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%85%B5%E5%AE%B6%E6%9C%89%E7%9E%BF%E9%A2%96%E7%9A%84%E4%B8%93%E5%B1%9E%E5%8D%A7%E5%AE%A4%23) `185.9K 🔥` `NEW`
1. [女子人脸被盗喂给AI做成短剧](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%BA%BA%E8%84%B8%E8%A2%AB%E7%9B%97%E5%96%82%E7%BB%99AI%E5%81%9A%E6%88%90%E7%9F%AD%E5%89%A7%23) `168.2K 🔥` `NEW`
1. [药店藏5元平价药推销50元替代药](https://s.weibo.com/weibo?q=%23%E8%8D%AF%E5%BA%97%E8%97%8F5%E5%85%83%E5%B9%B3%E4%BB%B7%E8%8D%AF%E6%8E%A8%E9%94%8050%E5%85%83%E6%9B%BF%E4%BB%A3%E8%8D%AF%23) `162.7K 🔥` `NEW`
1. [小S街头大哭](https://s.weibo.com/weibo?q=%23%E5%B0%8FS%E8%A1%97%E5%A4%B4%E5%A4%A7%E5%93%AD%23) `155.8K 🔥` `NEW`
1. [凌潇肃侯雯元 莞莞类卿](https://s.weibo.com/weibo?q=%23%E5%87%8C%E6%BD%87%E8%82%83%E4%BE%AF%E9%9B%AF%E5%85%83%20%E8%8E%9E%E8%8E%9E%E7%B1%BB%E5%8D%BF%23) `155.3K 🔥` `NEW`
1. [谈莉娜孕晚期状态](https://s.weibo.com/weibo?q=%23%E8%B0%88%E8%8E%89%E5%A8%9C%E5%AD%95%E6%99%9A%E6%9C%9F%E7%8A%B6%E6%80%81%23) `149.3K 🔥` `NEW`
1. [冰湖重生](https://s.weibo.com/weibo?q=%23%E5%86%B0%E6%B9%96%E9%87%8D%E7%94%9F%23) `117.3K 🔥` `NEW`
1. [拉里贾尼被斩首细节披露](https://s.weibo.com/weibo?q=%23%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%E8%A2%AB%E6%96%A9%E9%A6%96%E7%BB%86%E8%8A%82%E6%8A%AB%E9%9C%B2%23) `115.3K 🔥` `NEW`
1. [油价](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%23) `102.9K 🔥` `NEW`
1. [曝岳雨婷巴黎看秀风波内幕 (The inside story of Yue Yuting’s Paris show scandal revealed)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%B2%B3%E9%9B%A8%E5%A9%B7%E5%B7%B4%E9%BB%8E%E7%9C%8B%E7%A7%80%E9%A3%8E%E6%B3%A2%E5%86%85%E5%B9%95%23) `99.7K 🔥` `NEW`
1. [五千的钢琴课狗学了三千](https://s.weibo.com/weibo?q=%23%E4%BA%94%E5%8D%83%E7%9A%84%E9%92%A2%E7%90%B4%E8%AF%BE%E7%8B%97%E5%AD%A6%E4%BA%86%E4%B8%89%E5%8D%83%23) `99.4K 🔥` `NEW`
1. [网购救命药患者注射后救治无效身亡](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%B4%AD%E6%95%91%E5%91%BD%E8%8D%AF%E6%82%A3%E8%80%85%E6%B3%A8%E5%B0%84%E5%90%8E%E6%95%91%E6%B2%BB%E6%97%A0%E6%95%88%E8%BA%AB%E4%BA%A1%23) `93.5K 🔥` `NEW`
1. [瞿颖回应已婚](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E5%9B%9E%E5%BA%94%E5%B7%B2%E5%A9%9A%23) `93.3K 🔥` `NEW`
1. [小米新SU7](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%96%B0SU7%23) `83.2K 🔥` `NEW`
1. [中方回应特朗普确认推迟访华](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E7%A1%AE%E8%AE%A4%E6%8E%A8%E8%BF%9F%E8%AE%BF%E5%8D%8E%23) `1.1M 🔥` `+823%`
1. [文身店免费给65岁以上老人文身](https://s.weibo.com/weibo?q=%23%E6%96%87%E8%BA%AB%E5%BA%97%E5%85%8D%E8%B4%B9%E7%BB%9965%E5%B2%81%E4%BB%A5%E4%B8%8A%E8%80%81%E4%BA%BA%E6%96%87%E8%BA%AB%23) `361.4K 🔥` `+89%`
1. [百花杀](https://s.weibo.com/weibo?q=%23%E7%99%BE%E8%8A%B1%E6%9D%80%23) `192.7K 🔥` `+34%`
1. [春暖花开各地文旅持续升温](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%9A%96%E8%8A%B1%E5%BC%80%E5%90%84%E5%9C%B0%E6%96%87%E6%97%85%E6%8C%81%E7%BB%AD%E5%8D%87%E6%B8%A9%23) `620.1K 🔥`
1. [鹿晗鲜啤福鹿家品牌全球代言人 (Global spokesperson of Luhan Fresh Beer and Lujia Brand)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E9%B2%9C%E5%95%A4%E7%A6%8F%E9%B9%BF%E5%AE%B6%E5%93%81%E7%89%8C%E5%85%A8%E7%90%83%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `314.7K 🔥`
1. [离职要走发现同事在窗口举牌](https://s.weibo.com/weibo?q=%23%E7%A6%BB%E8%81%8C%E8%A6%81%E8%B5%B0%E5%8F%91%E7%8E%B0%E5%90%8C%E4%BA%8B%E5%9C%A8%E7%AA%97%E5%8F%A3%E4%B8%BE%E7%89%8C%23) `189.8K 🔥`
1. [网传落生去世 (Internet rumors about death)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E8%90%BD%E7%94%9F%E5%8E%BB%E4%B8%96%23) `178.4K 🔥`
1. [一块get舒淇同款清香好茶](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%9D%97get%E8%88%92%E6%B7%87%E5%90%8C%E6%AC%BE%E6%B8%85%E9%A6%99%E5%A5%BD%E8%8C%B6%23) `175.0K 🔥`
1. [岳雨婷爸爸因破产头发全白](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E7%88%B8%E7%88%B8%E5%9B%A0%E7%A0%B4%E4%BA%A7%E5%A4%B4%E5%8F%91%E5%85%A8%E7%99%BD%23) `161.9K 🔥`
1. [高度近视吹瓶子](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%BA%A6%E8%BF%91%E8%A7%86%E5%90%B9%E7%93%B6%E5%AD%90%23) `155.4K 🔥`
1. [周杰伦新专辑太阳之子](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%E8%BE%91%E5%A4%AA%E9%98%B3%E4%B9%8B%E5%AD%90%23) `155.4K 🔥`
1. [奶奶减肥法](https://s.weibo.com/weibo?q=%23%E5%A5%B6%E5%A5%B6%E5%87%8F%E8%82%A5%E6%B3%95%23) `153.9K 🔥`
1. [今天才知道TFBOYS全称](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E6%89%8D%E7%9F%A5%E9%81%93TFBOYS%E5%85%A8%E7%A7%B0%23) `151.6K 🔥`
1. [孔雪儿曾是邓凯的偶像](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E6%9B%BE%E6%98%AF%E9%82%93%E5%87%AF%E7%9A%84%E5%81%B6%E5%83%8F%23) `110.7K 🔥`
1. [桃花坞第六季重庆路透](https://s.weibo.com/weibo?q=%23%E6%A1%83%E8%8A%B1%E5%9D%9E%E7%AC%AC%E5%85%AD%E5%AD%A3%E9%87%8D%E5%BA%86%E8%B7%AF%E9%80%8F%23) `99.3K 🔥`
1. [建议年轻人少去公园容易伤自尊 (It is recommended that young people go to the park less often because it may hurt their self-esteem.)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%B0%91%E5%8E%BB%E5%85%AC%E5%9B%AD%E5%AE%B9%E6%98%93%E4%BC%A4%E8%87%AA%E5%B0%8A%23) `803.7K 🔥` `-27%`
1. [京东大内存手机限时特惠5折抄底 (JD.com offers 50% off on large-memory mobile phones for a limited time)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E5%A4%A7%E5%86%85%E5%AD%98%E6%89%8B%E6%9C%BA%E9%99%90%E6%97%B6%E7%89%B9%E6%83%A05%E6%8A%98%E6%8A%84%E5%BA%95%23) `413.2K 🔥` `-22%`
1. [油价涨了冲锋衣可能更贵](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E6%B6%A8%E4%BA%86%E5%86%B2%E9%94%8B%E8%A1%A3%E5%8F%AF%E8%83%BD%E6%9B%B4%E8%B4%B5%23) `315.1K 🔥` `-37%`
1. [果然人老了干什么都心酸 (Sure enough, when you are old, you will feel sad no matter what you do.)](https://s.weibo.com/weibo?q=%23%E6%9E%9C%E7%84%B6%E4%BA%BA%E8%80%81%E4%BA%86%E5%B9%B2%E4%BB%80%E4%B9%88%E9%83%BD%E5%BF%83%E9%85%B8%23) `314.9K 🔥` `-37%`
1. [男二以下 AI演员 (AI actors below male 2)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E4%BA%8C%E4%BB%A5%E4%B8%8B%20AI%E6%BC%94%E5%91%98%23) `314.2K 🔥` `-59%`
1. [婴儿倒挂近1分钟爸爸全程玩手机](https://s.weibo.com/weibo?q=%23%E5%A9%B4%E5%84%BF%E5%80%92%E6%8C%82%E8%BF%911%E5%88%86%E9%92%9F%E7%88%B8%E7%88%B8%E5%85%A8%E7%A8%8B%E7%8E%A9%E6%89%8B%E6%9C%BA%23) `224.2K 🔥` `-55%`
1. [樊长玉谢征 好孕赘婿](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E8%B0%A2%E5%BE%81%20%E5%A5%BD%E5%AD%95%E8%B5%98%E5%A9%BF%23) `183.4K 🔥` `-36%`
1. [以色列因总理身亡传言连发3天视频](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%9B%A0%E6%80%BB%E7%90%86%E8%BA%AB%E4%BA%A1%E4%BC%A0%E8%A8%80%E8%BF%9E%E5%8F%913%E5%A4%A9%E8%A7%86%E9%A2%91%23) `181.9K 🔥` `-43%`
1. [50岁女职工被强制退休获赔94万 (A 50-year-old female employee was forced to retire and received a compensation of NT$940,000)](https://s.weibo.com/weibo?q=%2350%E5%B2%81%E5%A5%B3%E8%81%8C%E5%B7%A5%E8%A2%AB%E5%BC%BA%E5%88%B6%E9%80%80%E4%BC%91%E8%8E%B7%E8%B5%9494%E4%B8%87%23) `171.9K 🔥` `-31%`
1. [不是私生 是公立医院出生](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%98%AF%E7%A7%81%E7%94%9F%20%E6%98%AF%E5%85%AC%E7%AB%8B%E5%8C%BB%E9%99%A2%E5%87%BA%E7%94%9F%23) `169.8K 🔥` `-21%`
1. [凤梨居然还能这么切](https://s.weibo.com/weibo?q=%23%E5%87%A4%E6%A2%A8%E5%B1%85%E7%84%B6%E8%BF%98%E8%83%BD%E8%BF%99%E4%B9%88%E5%88%87%23) `118.8K 🔥` `-41%`
1. [顾客带狗就餐店主砸碎600套餐具](https://s.weibo.com/weibo?q=%23%E9%A1%BE%E5%AE%A2%E5%B8%A6%E7%8B%97%E5%B0%B1%E9%A4%90%E5%BA%97%E4%B8%BB%E7%A0%B8%E7%A2%8E600%E5%A5%97%E9%A4%90%E5%85%B7%23) `113.3K 🔥` `-48%`
1. [曝酷滕雷淞然闹掰原因](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E9%85%B7%E6%BB%95%E9%9B%B7%E6%B7%9E%E7%84%B6%E9%97%B9%E6%8E%B0%E5%8E%9F%E5%9B%A0%23) `99.5K 🔥` `-43%`
1. [姚晨 侯雯元 (Yao Chen Hou Wenyuan)](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E6%99%A8%20%E4%BE%AF%E9%9B%AF%E5%85%83%23) `93.4K 🔥` `-51%`
1. [曝小S哭着去陈建州范玮琪家 (It was revealed that Little S went to Chen Jianzhou and Weiqi Fan’s house in tears)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%B0%8FS%E5%93%AD%E7%9D%80%E5%8E%BB%E9%99%88%E5%BB%BA%E5%B7%9E%E8%8C%83%E7%8E%AE%E7%90%AA%E5%AE%B6%23) `93.0K 🔥` `-40%`
1. [伊朗对一名间谍执行死刑 (Iran executes spy)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%B9%E4%B8%80%E5%90%8D%E9%97%B4%E8%B0%8D%E6%89%A7%E8%A1%8C%E6%AD%BB%E5%88%91%23) `87.5K 🔥` `-44%`
1. [再邋遢一天明天可以理发了](https://s.weibo.com/weibo?q=%23%E5%86%8D%E9%82%8B%E9%81%A2%E4%B8%80%E5%A4%A9%E6%98%8E%E5%A4%A9%E5%8F%AF%E4%BB%A5%E7%90%86%E5%8F%91%E4%BA%86%23) `86.5K 🔥` `-27%`
1. [TF四代一班认证变成演员 (One of the four generations of TF certified as actors)](https://s.weibo.com/weibo?q=%23TF%E5%9B%9B%E4%BB%A3%E4%B8%80%E7%8F%AD%E8%AE%A4%E8%AF%81%E5%8F%98%E6%88%90%E6%BC%94%E5%91%98%23) `85.5K 🔥` `-27%`
1. [刘文祥麻辣烫店员徒手拌麻酱 (Liu Wenxiang Malatang clerk mixes sesame paste with his bare hands)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E5%BA%97%E5%91%98%E5%BE%92%E6%89%8B%E6%8B%8C%E9%BA%BB%E9%85%B1%23) `84.7K 🔥` `-31%`
1. [何穗孕中期吃一顿饭胖三斤](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%A9%97%E5%AD%95%E4%B8%AD%E6%9C%9F%E5%90%83%E4%B8%80%E9%A1%BF%E9%A5%AD%E8%83%96%E4%B8%89%E6%96%A4%23) `84.4K 🔥` `-39%`
1. [姚晨方否认与侯雯元恋情 (Yao Chenfang denies romance with Hou Wenyuan)](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E6%99%A8%E6%96%B9%E5%90%A6%E8%AE%A4%E4%B8%8E%E4%BE%AF%E9%9B%AF%E5%85%83%E6%81%8B%E6%83%85%23) `84.2K 🔥` `-29%`

Updated at 2026-03-18 16:07:02

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
