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

1. [我们的少年时代2 (Our Boyhood 2)](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%23) `993.3K 🔥` `NEW`
1. [十五五规划纲要全文](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E7%BA%B2%E8%A6%81%E5%85%A8%E6%96%87%23) `766.5K 🔥` `NEW`
1. [马思纯生日 闲鱼](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%80%9D%E7%BA%AF%E7%94%9F%E6%97%A5%20%E9%97%B2%E9%B1%BC%23) `553.4K 🔥` `NEW`
1. [第31届白玉兰奖](https://s.weibo.com/weibo?q=%23%E7%AC%AC31%E5%B1%8A%E7%99%BD%E7%8E%89%E5%85%B0%E5%A5%96%23) `411.4K 🔥` `NEW`
1. [河南省考](https://s.weibo.com/weibo?q=%23%E6%B2%B3%E5%8D%97%E7%9C%81%E8%80%83%23) `337.5K 🔥` `NEW`
1. [人大代表支招小单方治大病](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E6%94%AF%E6%8B%9B%E5%B0%8F%E5%8D%95%E6%96%B9%E6%B2%BB%E5%A4%A7%E7%97%85%23) `308.4K 🔥` `NEW`
1. [2026入坑F1刚刚好](https://s.weibo.com/weibo?q=%232026%E5%85%A5%E5%9D%91F1%E5%88%9A%E5%88%9A%E5%A5%BD%23) `308.2K 🔥` `NEW`
1. [十五五这四类人群直接受益](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%BF%99%E5%9B%9B%E7%B1%BB%E4%BA%BA%E7%BE%A4%E7%9B%B4%E6%8E%A5%E5%8F%97%E7%9B%8A%23) `293.0K 🔥` `NEW`
1. [人民大会堂的热水瓶用了30年](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E6%B0%91%E5%A4%A7%E4%BC%9A%E5%A0%82%E7%9A%84%E7%83%AD%E6%B0%B4%E7%93%B6%E7%94%A8%E4%BA%8630%E5%B9%B4%23) `291.7K 🔥` `NEW`
1. [成为中国人何以海外出圈](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%B8%BA%E4%B8%AD%E5%9B%BD%E4%BA%BA%E4%BD%95%E4%BB%A5%E6%B5%B7%E5%A4%96%E5%87%BA%E5%9C%88%23) `288.8K 🔥` `NEW`
1. [田曦薇张凌赫经纪人依旧纯恨中 (Tian Xiwei, Zhang Linghe’s manager is still in pure hatred)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%BB%8F%E7%BA%AA%E4%BA%BA%E4%BE%9D%E6%97%A7%E7%BA%AF%E6%81%A8%E4%B8%AD%23) `287.4K 🔥` `NEW`
1. [男子狂扇自己称后悔花10万再婚](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%8B%82%E6%89%87%E8%87%AA%E5%B7%B1%E7%A7%B0%E5%90%8E%E6%82%94%E8%8A%B110%E4%B8%87%E5%86%8D%E5%A9%9A%23) `285.0K 🔥` `NEW`
1. [鞠婧祎杂志开售](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E6%9D%82%E5%BF%97%E5%BC%80%E5%94%AE%23) `281.1K 🔥` `NEW`
1. [严屹宽 别让老霸总演这些](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%20%E5%88%AB%E8%AE%A9%E8%80%81%E9%9C%B8%E6%80%BB%E6%BC%94%E8%BF%99%E4%BA%9B%23) `279.1K 🔥` `NEW`
1. [女孩用胡萝卜啃出70cm高黄鹤楼](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E7%94%A8%E8%83%A1%E8%90%9D%E5%8D%9C%E5%95%83%E5%87%BA70cm%E9%AB%98%E9%BB%84%E9%B9%A4%E6%A5%BC%23) `238.2K 🔥` `NEW`
1. [行测](https://s.weibo.com/weibo?q=%23%E8%A1%8C%E6%B5%8B%23) `231.2K 🔥` `NEW`
1. [毛林林感谢田曦薇](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%9E%97%E6%9E%97%E6%84%9F%E8%B0%A2%E7%94%B0%E6%9B%A6%E8%96%87%23) `217.4K 🔥` `NEW`
1. [海尔AI科技真的懂生活](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%B0%94AI%E7%A7%91%E6%8A%80%E7%9C%9F%E7%9A%84%E6%87%82%E7%94%9F%E6%B4%BB%23) `215.4K 🔥` `NEW`
1. [省考图推](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%E5%9B%BE%E6%8E%A8%23) `215.3K 🔥` `NEW`
1. [原来被老天爷追着喂饭是这样](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%A2%AB%E8%80%81%E5%A4%A9%E7%88%B7%E8%BF%BD%E7%9D%80%E5%96%82%E9%A5%AD%E6%98%AF%E8%BF%99%E6%A0%B7%23) `184.2K 🔥` `NEW`
1. [妻子的浪漫旅行8路透 (Wife’s Romantic Travel 8 Reuters)](https://s.weibo.com/weibo?q=%23%E5%A6%BB%E5%AD%90%E7%9A%84%E6%B5%AA%E6%BC%AB%E6%97%85%E8%A1%8C8%E8%B7%AF%E9%80%8F%23) `174.0K 🔥` `NEW`
1. [我们的少年时代2官宣](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%E5%AE%98%E5%AE%A3%23) `169.7K 🔥` `NEW`
1. [湖北省考](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8C%97%E7%9C%81%E8%80%83%23) `160.8K 🔥` `NEW`
1. [热销榜首的工学椅被指填充黑心棉](https://s.weibo.com/weibo?q=%23%E7%83%AD%E9%94%80%E6%A6%9C%E9%A6%96%E7%9A%84%E5%B7%A5%E5%AD%A6%E6%A4%85%E8%A2%AB%E6%8C%87%E5%A1%AB%E5%85%85%E9%BB%91%E5%BF%83%E6%A3%89%23) `158.8K 🔥` `NEW`
1. [把本侯的女儿毫发无伤地带回来](https://s.weibo.com/weibo?q=%23%E6%8A%8A%E6%9C%AC%E4%BE%AF%E7%9A%84%E5%A5%B3%E5%84%BF%E6%AF%AB%E5%8F%91%E6%97%A0%E4%BC%A4%E5%9C%B0%E5%B8%A6%E5%9B%9E%E6%9D%A5%23) `158.8K 🔥` `NEW`
1. [直播间卖200元抗癌药实为糖果](https://s.weibo.com/weibo?q=%23%E7%9B%B4%E6%92%AD%E9%97%B4%E5%8D%96200%E5%85%83%E6%8A%97%E7%99%8C%E8%8D%AF%E5%AE%9E%E4%B8%BA%E7%B3%96%E6%9E%9C%23) `157.6K 🔥` `NEW`
1. [王橹杰逆光海报](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E9%80%86%E5%85%89%E6%B5%B7%E6%8A%A5%23) `157.2K 🔥` `NEW`
1. [腾讯2026年8部头部大剧](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF2026%E5%B9%B48%E9%83%A8%E5%A4%B4%E9%83%A8%E5%A4%A7%E5%89%A7%23) `150.8K 🔥` `NEW`
1. [贵州茅台](https://s.weibo.com/weibo?q=%23%E8%B4%B5%E5%B7%9E%E8%8C%85%E5%8F%B0%23) `146.4K 🔥` `NEW`
1. [吉林省考](https://s.weibo.com/weibo?q=%23%E5%90%89%E6%9E%97%E7%9C%81%E8%80%83%23) `140.0K 🔥` `NEW`
1. [岳雨婷万渣朝凰定妆照 (Yue Yuting's Wanzha Chaohuang makeup photos)](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E4%B8%87%E6%B8%A3%E6%9C%9D%E5%87%B0%E5%AE%9A%E5%A6%86%E7%85%A7%23) `126.5K 🔥` `NEW`
1. [ELLE四月刊鞠婧祎封面](https://s.weibo.com/weibo?q=%23ELLE%E5%9B%9B%E6%9C%88%E5%88%8A%E9%9E%A0%E5%A9%A7%E7%A5%8E%E5%B0%81%E9%9D%A2%23) `123.2K 🔥` `NEW`
1. [被丢弃厕所女婴生母感谢养母](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E4%B8%A2%E5%BC%83%E5%8E%95%E6%89%80%E5%A5%B3%E5%A9%B4%E7%94%9F%E6%AF%8D%E6%84%9F%E8%B0%A2%E5%85%BB%E6%AF%8D%23) `94.8K 🔥` `NEW`
1. [3米就放电伤人电杆标语引质疑](https://s.weibo.com/weibo?q=%233%E7%B1%B3%E5%B0%B1%E6%94%BE%E7%94%B5%E4%BC%A4%E4%BA%BA%E7%94%B5%E6%9D%86%E6%A0%87%E8%AF%AD%E5%BC%95%E8%B4%A8%E7%96%91%23) `94.1K 🔥` `NEW`
1. [近半老年人在租房时被拒绝](https://s.weibo.com/weibo?q=%23%E8%BF%91%E5%8D%8A%E8%80%81%E5%B9%B4%E4%BA%BA%E5%9C%A8%E7%A7%9F%E6%88%BF%E6%97%B6%E8%A2%AB%E6%8B%92%E7%BB%9D%23) `93.7K 🔥` `NEW`
1. [有一种浪漫叫玉兰花开了](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%B8%80%E7%A7%8D%E6%B5%AA%E6%BC%AB%E5%8F%AB%E7%8E%89%E5%85%B0%E8%8A%B1%E5%BC%80%E4%BA%86%23) `92.3K 🔥` `NEW`
1. [随元青结局](https://s.weibo.com/weibo?q=%23%E9%9A%8F%E5%85%83%E9%9D%92%E7%BB%93%E5%B1%80%23) `85.7K 🔥` `NEW`
1. [我们的少年时代2符动青春海报](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%E7%AC%A6%E5%8A%A8%E9%9D%92%E6%98%A5%E6%B5%B7%E6%8A%A5%23) `82.9K 🔥` `NEW`
1. [公务员招录持续向应届生和基层倾斜](https://s.weibo.com/weibo?q=%23%E5%85%AC%E5%8A%A1%E5%91%98%E6%8B%9B%E5%BD%95%E6%8C%81%E7%BB%AD%E5%90%91%E5%BA%94%E5%B1%8A%E7%94%9F%E5%92%8C%E5%9F%BA%E5%B1%82%E5%80%BE%E6%96%9C%23) `79.9K 🔥` `NEW`
1. [陈楚生也沉迷短剧无法自拔](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%A5%9A%E7%94%9F%E4%B9%9F%E6%B2%89%E8%BF%B7%E7%9F%AD%E5%89%A7%E6%97%A0%E6%B3%95%E8%87%AA%E6%8B%94%23) `79.3K 🔥` `NEW`
1. [被丢弃厕所女婴母亲愧疚没保护好女儿 (Mother of baby girl abandoned in toilet feels guilty for failing to protect her daughter)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E4%B8%A2%E5%BC%83%E5%8E%95%E6%89%80%E5%A5%B3%E5%A9%B4%E6%AF%8D%E4%BA%B2%E6%84%A7%E7%96%9A%E6%B2%A1%E4%BF%9D%E6%8A%A4%E5%A5%BD%E5%A5%B3%E5%84%BF%23) `78.7K 🔥` `NEW`
1. [省考](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%23) `2.1M 🔥` `+99%`
1. [呼啸山庄尺度好大 (Wuthering Heights is so big)](https://s.weibo.com/weibo?q=%23%E5%91%BC%E5%95%B8%E5%B1%B1%E5%BA%84%E5%B0%BA%E5%BA%A6%E5%A5%BD%E5%A4%A7%23) `210.8K 🔥` `+77%`
1. [张凌赫特别适合在很狼狈的时候爱人 (Zhang Linghe is especially suitable for loving someone when they are in a very embarrassing situation)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%89%B9%E5%88%AB%E9%80%82%E5%90%88%E5%9C%A8%E5%BE%88%E7%8B%BC%E7%8B%88%E7%9A%84%E6%97%B6%E5%80%99%E7%88%B1%E4%BA%BA%23) `93.4K 🔥` `+114%`
1. [伊朗30枚超重导弹袭击以色列 (Iran attacks Israel with 30 super-heavy missiles)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%9730%E6%9E%9A%E8%B6%85%E9%87%8D%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%E4%BB%A5%E8%89%B2%E5%88%97%23) `301.7K 🔥`
1. [伊朗向以色列发动最猛烈空袭](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%E5%8F%91%E5%8A%A8%E6%9C%80%E7%8C%9B%E7%83%88%E7%A9%BA%E8%A2%AD%23) `121.4K 🔥`
1. [4种睡眠异常提示肾出问题](https://s.weibo.com/weibo?q=%234%E7%A7%8D%E7%9D%A1%E7%9C%A0%E5%BC%82%E5%B8%B8%E6%8F%90%E7%A4%BA%E8%82%BE%E5%87%BA%E9%97%AE%E9%A2%98%23) `111.5K 🔥`
1. [九尾 这导播是真恶心](https://s.weibo.com/weibo?q=%23%E4%B9%9D%E5%B0%BE%20%E8%BF%99%E5%AF%BC%E6%92%AD%E6%98%AF%E7%9C%9F%E6%81%B6%E5%BF%83%23) `79.5K 🔥`
1. [国家网络安全通报中心通报OpenClaw风险 (National Cybersecurity Notification Center notifies OpenClaw risks)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%AE%B6%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8%E9%80%9A%E6%8A%A5%E4%B8%AD%E5%BF%83%E9%80%9A%E6%8A%A5OpenClaw%E9%A3%8E%E9%99%A9%23) `266.7K 🔥` `-57%`
1. [弟弟的脐带血15年后救了哥哥](https://s.weibo.com/weibo?q=%23%E5%BC%9F%E5%BC%9F%E7%9A%84%E8%84%90%E5%B8%A6%E8%A1%8015%E5%B9%B4%E5%90%8E%E6%95%91%E4%BA%86%E5%93%A5%E5%93%A5%23) `257.7K 🔥` `-56%`
1. [杨幂赵丽颖 白玉兰 (Yang Mi, Zhao Liying, Magnolia)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%B5%B5%E4%B8%BD%E9%A2%96%20%E7%99%BD%E7%8E%89%E5%85%B0%23) `215.4K 🔥` `-60%`
1. [男子维权被12315工作人员嘲讽 (A man’s rights defense was ridiculed by 12315 staff)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%BB%B4%E6%9D%83%E8%A2%AB12315%E5%B7%A5%E4%BD%9C%E4%BA%BA%E5%91%98%E5%98%B2%E8%AE%BD%23) `105.5K 🔥` `-46%`

Updated at 2026-03-14 11:24:29

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
