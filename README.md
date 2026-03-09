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

1. [LOL](https://s.weibo.com/weibo?q=%23LOL%23) `476.8K 🔥` `NEW`
1. [伊朗总统提醒邻国别被美以欺骗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E6%8F%90%E9%86%92%E9%82%BB%E5%9B%BD%E5%88%AB%E8%A2%AB%E7%BE%8E%E4%BB%A5%E6%AC%BA%E9%AA%97%23) `241.2K 🔥` `NEW`
1. [山东多地辟谣小程序可领分娩补贴](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E4%B8%9C%E5%A4%9A%E5%9C%B0%E8%BE%9F%E8%B0%A3%E5%B0%8F%E7%A8%8B%E5%BA%8F%E5%8F%AF%E9%A2%86%E5%88%86%E5%A8%A9%E8%A1%A5%E8%B4%B4%23) `240.6K 🔥` `NEW`
1. [周深官宣2026巡回演唱会](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B1%E5%AE%98%E5%AE%A32026%E5%B7%A1%E5%9B%9E%E6%BC%94%E5%94%B1%E4%BC%9A%23) `226.3K 🔥` `NEW`
1. [杨紫王安宇合作](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%8E%8B%E5%AE%89%E5%AE%87%E5%90%88%E4%BD%9C%23) `221.7K 🔥` `NEW`
1. [赵晴新剧内娱稀有不缺爱女主](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E6%99%B4%E6%96%B0%E5%89%A7%E5%86%85%E5%A8%B1%E7%A8%80%E6%9C%89%E4%B8%8D%E7%BC%BA%E7%88%B1%E5%A5%B3%E4%B8%BB%23) `173.6K 🔥` `NEW`
1. [清华满绩学生路演被评答非所问](https://s.weibo.com/weibo?q=%23%E6%B8%85%E5%8D%8E%E6%BB%A1%E7%BB%A9%E5%AD%A6%E7%94%9F%E8%B7%AF%E6%BC%94%E8%A2%AB%E8%AF%84%E7%AD%94%E9%9D%9E%E6%89%80%E9%97%AE%23) `173.6K 🔥` `NEW`
1. [孙俪ELLE4月刊封面](https://s.weibo.com/weibo?q=%23%E5%AD%99%E4%BF%AAELLE4%E6%9C%88%E5%88%8A%E5%B0%81%E9%9D%A2%23) `173.6K 🔥` `NEW`
1. [伊朗驻华大使回应哈梅内伊之子当选](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A9%BB%E5%8D%8E%E5%A4%A7%E4%BD%BF%E5%9B%9E%E5%BA%94%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E4%B9%8B%E5%AD%90%E5%BD%93%E9%80%89%23) `173.6K 🔥` `NEW`
1. [9旬母亲瘫痪5个子女赡养起争执](https://s.weibo.com/weibo?q=%239%E6%97%AC%E6%AF%8D%E4%BA%B2%E7%98%AB%E7%97%AA5%E4%B8%AA%E5%AD%90%E5%A5%B3%E8%B5%A1%E5%85%BB%E8%B5%B7%E4%BA%89%E6%89%A7%23) `173.6K 🔥` `NEW`
1. [檀健次尖叫之夜后台原声掉落 (Tan Jianci's Screaming Night backstage soundtrack dropped)](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%E5%B0%96%E5%8F%AB%E4%B9%8B%E5%A4%9C%E5%90%8E%E5%8F%B0%E5%8E%9F%E5%A3%B0%E6%8E%89%E8%90%BD%23) `173.6K 🔥` `NEW`
1. [谭松韵红包剧宣](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E7%BA%A2%E5%8C%85%E5%89%A7%E5%AE%A3%23) `173.6K 🔥` `NEW`
1. [白鹿素材够了就收工](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E7%B4%A0%E6%9D%90%E5%A4%9F%E4%BA%86%E5%B0%B1%E6%94%B6%E5%B7%A5%23) `173.6K 🔥` `NEW`
1. [第一次下厨把鸡蛋炒成了炭](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E4%B8%8B%E5%8E%A8%E6%8A%8A%E9%B8%A1%E8%9B%8B%E7%82%92%E6%88%90%E4%BA%86%E7%82%AD%23) `173.5K 🔥` `NEW`
1. [沉迷AI的中年领导](https://s.weibo.com/weibo?q=%23%E6%B2%89%E8%BF%B7AI%E7%9A%84%E4%B8%AD%E5%B9%B4%E9%A2%86%E5%AF%BC%23) `173.5K 🔥` `NEW`
1. [这么小就找到了自己理想型](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B9%88%E5%B0%8F%E5%B0%B1%E6%89%BE%E5%88%B0%E4%BA%86%E8%87%AA%E5%B7%B1%E7%90%86%E6%83%B3%E5%9E%8B%23) `173.5K 🔥` `NEW`
1. [朝鲜女足vs中国女足](https://s.weibo.com/weibo?q=%23%E6%9C%9D%E9%B2%9C%E5%A5%B3%E8%B6%B3vs%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B3%23) `173.5K 🔥` `NEW`
1. [老天爷收拾我的时候力度刚刚好](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%A4%A9%E7%88%B7%E6%94%B6%E6%8B%BE%E6%88%91%E7%9A%84%E6%97%B6%E5%80%99%E5%8A%9B%E5%BA%A6%E5%88%9A%E5%88%9A%E5%A5%BD%23) `173.5K 🔥` `NEW`
1. [玫瑰丛生0热度战报图](https://s.weibo.com/weibo?q=%23%E7%8E%AB%E7%91%B0%E4%B8%9B%E7%94%9F0%E7%83%AD%E5%BA%A6%E6%88%98%E6%8A%A5%E5%9B%BE%23) `218.2K 🔥` `+23%`
1. [西班牙人来中国一周后](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E7%8F%AD%E7%89%99%E4%BA%BA%E6%9D%A5%E4%B8%AD%E5%9B%BD%E4%B8%80%E5%91%A8%E5%90%8E%23) `188.4K 🔥` `+101%`
1. [小狗在街上认出妈妈时的反应 (Puppy's reaction when he recognizes mom on the street)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E5%9C%A8%E8%A1%97%E4%B8%8A%E8%AE%A4%E5%87%BA%E5%A6%88%E5%A6%88%E6%97%B6%E7%9A%84%E5%8F%8D%E5%BA%94%23) `173.6K 🔥` `+43%`
1. [任豪用剑扶田曦薇腰这一下 (Ren Hao used his sword to support Tian Xiwei's waist.)](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E8%B1%AA%E7%94%A8%E5%89%91%E6%89%B6%E7%94%B0%E6%9B%A6%E8%96%87%E8%85%B0%E8%BF%99%E4%B8%80%E4%B8%8B%23) `173.6K 🔥` `+51%`
1. [杭州初二男生贴助长贴一年长高11厘米](https://s.weibo.com/weibo?q=%23%E6%9D%AD%E5%B7%9E%E5%88%9D%E4%BA%8C%E7%94%B7%E7%94%9F%E8%B4%B4%E5%8A%A9%E9%95%BF%E8%B4%B4%E4%B8%80%E5%B9%B4%E9%95%BF%E9%AB%9811%E5%8E%98%E7%B1%B3%23) `173.6K 🔥` `+53%`
1. [4种无效早睡没比熬夜强多少 (4 Ineffective Ways Going to bed early is not much better than staying up late)](https://s.weibo.com/weibo?q=%234%E7%A7%8D%E6%97%A0%E6%95%88%E6%97%A9%E7%9D%A1%E6%B2%A1%E6%AF%94%E7%86%AC%E5%A4%9C%E5%BC%BA%E5%A4%9A%E5%B0%91%23) `173.6K 🔥` `+64%`
1. [黄金品牌涨价50克金手镯贵了5万元](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E5%93%81%E7%89%8C%E6%B6%A8%E4%BB%B750%E5%85%8B%E9%87%91%E6%89%8B%E9%95%AF%E8%B4%B5%E4%BA%865%E4%B8%87%E5%85%83%23) `173.6K 🔥` `+118%`
1. [杨瀚森和队友联手缔造五佳球](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%80%9A%E6%A3%AE%E5%92%8C%E9%98%9F%E5%8F%8B%E8%81%94%E6%89%8B%E7%BC%94%E9%80%A0%E4%BA%94%E4%BD%B3%E7%90%83%23) `173.6K 🔥` `+118%`
1. [哈梅内伊之子接任最高领袖 (Khamenei's son takes over as supreme leader)](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E4%B9%8B%E5%AD%90%E6%8E%A5%E4%BB%BB%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%23) `173.6K 🔥` `+41%`
1. [黄金白银盘中突然跳水](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E7%9B%98%E4%B8%AD%E7%AA%81%E7%84%B6%E8%B7%B3%E6%B0%B4%23) `173.6K 🔥` `+123%`
1. [一诺无偿给JDG复盘教学](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%AF%BA%E6%97%A0%E5%81%BF%E7%BB%99JDG%E5%A4%8D%E7%9B%98%E6%95%99%E5%AD%A6%23) `173.5K 🔥` `+119%`
1. [电视剧品质盛典 (TV Series Quality Ceremony)](https://s.weibo.com/weibo?q=%23%E7%94%B5%E8%A7%86%E5%89%A7%E5%93%81%E8%B4%A8%E7%9B%9B%E5%85%B8%23) `173.5K 🔥` `+132%`
1. [周杰伦温州](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%B8%A9%E5%B7%9E%23) `173.5K 🔥` `+90%`
1. [李延贺煽动分裂国家破坏国家统一](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%BB%B6%E8%B4%BA%E7%85%BD%E5%8A%A8%E5%88%86%E8%A3%82%E5%9B%BD%E5%AE%B6%E7%A0%B4%E5%9D%8F%E5%9B%BD%E5%AE%B6%E7%BB%9F%E4%B8%80%23) `1.1M 🔥`
1. [建议将8小时工作制缩短为7小时](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%868%E5%B0%8F%E6%97%B6%E5%B7%A5%E4%BD%9C%E5%88%B6%E7%BC%A9%E7%9F%AD%E4%B8%BA7%E5%B0%8F%E6%97%B6%23) `776.0K 🔥`
1. [从基层一线走进人民殿堂 (From the grassroots to the People's Hall)](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E5%9F%BA%E5%B1%82%E4%B8%80%E7%BA%BF%E8%B5%B0%E8%BF%9B%E4%BA%BA%E6%B0%91%E6%AE%BF%E5%A0%82%23) `637.5K 🔥`
1. [这不是弃养这是托孤](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B8%8D%E6%98%AF%E5%BC%83%E5%85%BB%E8%BF%99%E6%98%AF%E6%89%98%E5%AD%A4%23) `173.6K 🔥`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `173.6K 🔥`
1. [孙千发了和王安宇合照](https://s.weibo.com/weibo?q=%23%E5%AD%99%E5%8D%83%E5%8F%91%E4%BA%86%E5%92%8C%E7%8E%8B%E5%AE%89%E5%AE%87%E5%90%88%E7%85%A7%23) `173.6K 🔥`
1. [狂飙 (hurricane)](https://s.weibo.com/weibo?q=%23%E7%8B%82%E9%A3%99%23) `173.6K 🔥`
1. [女子称自己有190斤只因脸小没人信](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%A7%B0%E8%87%AA%E5%B7%B1%E6%9C%89190%E6%96%A4%E5%8F%AA%E5%9B%A0%E8%84%B8%E5%B0%8F%E6%B2%A1%E4%BA%BA%E4%BF%A1%23) `173.6K 🔥`
1. [张凌赫人生镜头](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%BA%BA%E7%94%9F%E9%95%9C%E5%A4%B4%23) `173.6K 🔥`
1. [伊朗确认军舰遭美军击沉致104人死亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A1%AE%E8%AE%A4%E5%86%9B%E8%88%B0%E9%81%AD%E7%BE%8E%E5%86%9B%E5%87%BB%E6%B2%89%E8%87%B4104%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `173.6K 🔥`
1. [董晴接档董晴](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%99%B4%E6%8E%A5%E6%A1%A3%E8%91%A3%E6%99%B4%23) `173.5K 🔥`
1. [小哥AI换脸Kpop歌手一夜爆红](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%93%A5AI%E6%8D%A2%E8%84%B8Kpop%E6%AD%8C%E6%89%8B%E4%B8%80%E5%A4%9C%E7%88%86%E7%BA%A2%23) `244.3K 🔥` `-21%`
1. [怪不得古代能一眼认出刺客](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E5%8F%A4%E4%BB%A3%E8%83%BD%E4%B8%80%E7%9C%BC%E8%AE%A4%E5%87%BA%E5%88%BA%E5%AE%A2%23) `235.4K 🔥` `-23%`
1. [白岩松称很多年轻人没时间去爱](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%B2%A9%E6%9D%BE%E7%A7%B0%E5%BE%88%E5%A4%9A%E5%B9%B4%E8%BD%BB%E4%BA%BA%E6%B2%A1%E6%97%B6%E9%97%B4%E5%8E%BB%E7%88%B1%23) `232.4K 🔥` `-23%`
1. [今年修改教师法 (The Teacher Law will be revised this year)](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E4%BF%AE%E6%94%B9%E6%95%99%E5%B8%88%E6%B3%95%23) `228.8K 🔥` `-25%`
1. [胖东来超8成员工拒绝降薪增假 (Over 80% of employees at Fat Dong Lai refused to cut their salary and increase their vacation time)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E8%B6%858%E6%88%90%E5%91%98%E5%B7%A5%E6%8B%92%E7%BB%9D%E9%99%8D%E8%96%AA%E5%A2%9E%E5%81%87%23) `221.0K 🔥` `-27%`
1. [伊朗导弹突防能力拉满](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E7%AA%81%E9%98%B2%E8%83%BD%E5%8A%9B%E6%8B%89%E6%BB%A1%23) `212.0K 🔥` `-30%`
1. [五字概括逐玉剧情 (Five words summarizing the plot of Zhuyu)](https://s.weibo.com/weibo?q=%23%E4%BA%94%E5%AD%97%E6%A6%82%E6%8B%AC%E9%80%90%E7%8E%89%E5%89%A7%E6%83%85%23) `173.6K 🔥` `-21%`
1. [乳腺癌女子从腹部借回一对新乳房](https://s.weibo.com/weibo?q=%23%E4%B9%B3%E8%85%BA%E7%99%8C%E5%A5%B3%E5%AD%90%E4%BB%8E%E8%85%B9%E9%83%A8%E5%80%9F%E5%9B%9E%E4%B8%80%E5%AF%B9%E6%96%B0%E4%B9%B3%E6%88%BF%23) `173.6K 🔥` `-27%`
1. [建议处罚加班严重企业](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%A4%84%E7%BD%9A%E5%8A%A0%E7%8F%AD%E4%B8%A5%E9%87%8D%E4%BC%81%E4%B8%9A%23) `173.6K 🔥` `-43%`

Updated at 2026-03-09 14:41:35

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
