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

1. [小米新SU7官宣舒淇苏炳添代言 (Xiaomi’s new SU7 officially announced that Shu Qi and Su Bingtian will be the endorsers)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%96%B0SU7%E5%AE%98%E5%AE%A3%E8%88%92%E6%B7%87%E8%8B%8F%E7%82%B3%E6%B7%BB%E4%BB%A3%E8%A8%80%23) `493.0K 🔥` `NEW`
1. [章子怡穿的比红毯还红](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%E7%A9%BF%E7%9A%84%E6%AF%94%E7%BA%A2%E6%AF%AF%E8%BF%98%E7%BA%A2%23) `244.2K 🔥` `NEW`
1. [神州山海 此生必驾](https://s.weibo.com/weibo?q=%23%E7%A5%9E%E5%B7%9E%E5%B1%B1%E6%B5%B7%20%E6%AD%A4%E7%94%9F%E5%BF%85%E9%A9%BE%23) `238.9K 🔥` `NEW`
1. [打工人姿势病](https://s.weibo.com/weibo?q=%23%E6%89%93%E5%B7%A5%E4%BA%BA%E5%A7%BF%E5%8A%BF%E7%97%85%23) `237.7K 🔥` `NEW`
1. [Able战队夺冠](https://s.weibo.com/weibo?q=%23Able%E6%88%98%E9%98%9F%E5%A4%BA%E5%86%A0%23) `236.5K 🔥` `NEW`
1. [外网也意识到韩国偷文化了](https://s.weibo.com/weibo?q=%23%E5%A4%96%E7%BD%91%E4%B9%9F%E6%84%8F%E8%AF%86%E5%88%B0%E9%9F%A9%E5%9B%BD%E5%81%B7%E6%96%87%E5%8C%96%E4%BA%86%23) `235.0K 🔥` `NEW`
1. [医院招聘法务硕士编外博士编内](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E9%99%A2%E6%8B%9B%E8%81%98%E6%B3%95%E5%8A%A1%E7%A1%95%E5%A3%AB%E7%BC%96%E5%A4%96%E5%8D%9A%E5%A3%AB%E7%BC%96%E5%86%85%23) `115.1K 🔥` `NEW`
1. [迪丽热巴迪奥活动直拍](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E8%BF%AA%E5%A5%A5%E6%B4%BB%E5%8A%A8%E7%9B%B4%E6%8B%8D%23) `114.4K 🔥` `NEW`
1. [暗访调查考公协议班](https://s.weibo.com/weibo?q=%23%E6%9A%97%E8%AE%BF%E8%B0%83%E6%9F%A5%E8%80%83%E5%85%AC%E5%8D%8F%E8%AE%AE%E7%8F%AD%23) `95.7K 🔥` `NEW`
1. [张凌赫田曦薇hi6拍立得](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87hi6%E6%8B%8D%E7%AB%8B%E5%BE%97%23) `93.6K 🔥` `NEW`
1. [班上一个唐氏综合症的孩子写的 (Written by a child with Down syndrome in the class)](https://s.weibo.com/weibo?q=%23%E7%8F%AD%E4%B8%8A%E4%B8%80%E4%B8%AA%E5%94%90%E6%B0%8F%E7%BB%BC%E5%90%88%E7%97%87%E7%9A%84%E5%AD%A9%E5%AD%90%E5%86%99%E7%9A%84%23) `93.6K 🔥` `NEW`
1. [女子办离婚被问你要离哪一段](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%8A%9E%E7%A6%BB%E5%A9%9A%E8%A2%AB%E9%97%AE%E4%BD%A0%E8%A6%81%E7%A6%BB%E5%93%AA%E4%B8%80%E6%AE%B5%23) `93.5K 🔥` `NEW`
1. [周深胸前是什么](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B1%E8%83%B8%E5%89%8D%E6%98%AF%E4%BB%80%E4%B9%88%23) `77.7K 🔥` `NEW`
1. [商户送的锦旗被扔在政务中心门口](https://s.weibo.com/weibo?q=%23%E5%95%86%E6%88%B7%E9%80%81%E7%9A%84%E9%94%A6%E6%97%97%E8%A2%AB%E6%89%94%E5%9C%A8%E6%94%BF%E5%8A%A1%E4%B8%AD%E5%BF%83%E9%97%A8%E5%8F%A3%23) `77.7K 🔥` `NEW`
1. [日媒评高市早苗访美](https://s.weibo.com/weibo?q=%23%E6%97%A5%E5%AA%92%E8%AF%84%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E8%AE%BF%E7%BE%8E%23) `72.5K 🔥` `NEW`
1. [CMG中国电影盛典](https://s.weibo.com/weibo?q=%23CMG%E4%B8%AD%E5%9B%BD%E7%94%B5%E5%BD%B1%E7%9B%9B%E5%85%B8%23) `71.6K 🔥` `NEW`
1. [白日提灯双端预约破400万](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E5%8F%8C%E7%AB%AF%E9%A2%84%E7%BA%A6%E7%A0%B4400%E4%B8%87%23) `63.9K 🔥` `NEW`
1. [濮院高定时尚周](https://s.weibo.com/weibo?q=%23%E6%BF%AE%E9%99%A2%E9%AB%98%E5%AE%9A%E6%97%B6%E5%B0%9A%E5%91%A8%23) `62.7K 🔥` `NEW`
1. [释永信涉嫌4项罪名 (Shi Yongxin is suspected of 4 crimes)](https://s.weibo.com/weibo?q=%23%E9%87%8A%E6%B0%B8%E4%BF%A1%E6%B6%89%E5%AB%8C4%E9%A1%B9%E7%BD%AA%E5%90%8D%23) `1.0M 🔥` `+35%`
1. [奥恰洛夫说樊振东不参加世乒赛 (Ocharov said Fan Zhendong will not participate in the World Table Tennis Championships)](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E6%81%B0%E6%B4%9B%E5%A4%AB%E8%AF%B4%E6%A8%8A%E6%8C%AF%E4%B8%9C%E4%B8%8D%E5%8F%82%E5%8A%A0%E4%B8%96%E4%B9%92%E8%B5%9B%23) `311.5K 🔥` `+33%`
1. [女子买8套老破小月收租2.1万 (A woman bought 8 old and dilapidated apartments and collected rent of 21,000 yuan a month)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%B08%E5%A5%97%E8%80%81%E7%A0%B4%E5%B0%8F%E6%9C%88%E6%94%B6%E7%A7%9F2.1%E4%B8%87%23) `254.4K 🔥` `+25%`
1. [薛之谦广州演唱会](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E5%B9%BF%E5%B7%9E%E6%BC%94%E5%94%B1%E4%BC%9A%23) `238.9K 🔥` `+83%`
1. [伊朗伊斯兰革命卫队发言人身亡 (Spokesperson of Iran’s Islamic Revolutionary Guard Corps dies)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BC%8A%E6%96%AF%E5%85%B0%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E5%8F%91%E8%A8%80%E4%BA%BA%E8%BA%AB%E4%BA%A1%23) `238.0K 🔥` `+42%`
1. [樊长玉草莓印](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E8%8D%89%E8%8E%93%E5%8D%B0%23) `234.0K 🔥` `+53%`
1. [对一块钱的概念越来越模糊 (The concept of a dollar is becoming increasingly vague)](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E4%B8%80%E5%9D%97%E9%92%B1%E7%9A%84%E6%A6%82%E5%BF%B5%E8%B6%8A%E6%9D%A5%E8%B6%8A%E6%A8%A1%E7%B3%8A%23) `232.6K 🔥` `+48%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `225.2K 🔥` `+21%`
1. [双休但不是休周末的工作](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E4%BC%91%E4%BD%86%E4%B8%8D%E6%98%AF%E4%BC%91%E5%91%A8%E6%9C%AB%E7%9A%84%E5%B7%A5%E4%BD%9C%23) `193.1K 🔥` `+22%`
1. [二月二最硬核龙抬头 (The most hard-core dragon raises its head on February 2nd)](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E6%9C%88%E4%BA%8C%E6%9C%80%E7%A1%AC%E6%A0%B8%E9%BE%99%E6%8A%AC%E5%A4%B4%23) `567.1K 🔥`
1. [刘轩丞新剧镜头被删 (Scenes from Liu Xuancheng's new drama deleted)](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%BD%A9%E4%B8%9E%E6%96%B0%E5%89%A7%E9%95%9C%E5%A4%B4%E8%A2%AB%E5%88%A0%23) `233.1K 🔥`
1. [张子枫 希腊神女](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%AD%90%E6%9E%AB%20%E5%B8%8C%E8%85%8A%E7%A5%9E%E5%A5%B3%23) `168.5K 🔥`
1. [铁路通报女子月经弄脏卧铺事件](https://s.weibo.com/weibo?q=%23%E9%93%81%E8%B7%AF%E9%80%9A%E6%8A%A5%E5%A5%B3%E5%AD%90%E6%9C%88%E7%BB%8F%E5%BC%84%E8%84%8F%E5%8D%A7%E9%93%BA%E4%BA%8B%E4%BB%B6%23) `166.8K 🔥`
1. [一种很新的减肥方法](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%A7%8D%E5%BE%88%E6%96%B0%E7%9A%84%E5%87%8F%E8%82%A5%E6%96%B9%E6%B3%95%23) `131.8K 🔥`
1. [孟佳开撕品牌方](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E4%BD%B3%E5%BC%80%E6%92%95%E5%93%81%E7%89%8C%E6%96%B9%23) `112.2K 🔥`
1. [伊朗称渴望实战中给美军舰沉重一击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E6%B8%B4%E6%9C%9B%E5%AE%9E%E6%88%98%E4%B8%AD%E7%BB%99%E7%BE%8E%E5%86%9B%E8%88%B0%E6%B2%89%E9%87%8D%E4%B8%80%E5%87%BB%23) `109.2K 🔥`
1. [张凌赫工作室 拍出了张凌赫的死角](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%B7%A5%E4%BD%9C%E5%AE%A4%20%E6%8B%8D%E5%87%BA%E4%BA%86%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9A%84%E6%AD%BB%E8%A7%92%23) `106.6K 🔥`
1. [吾恩 肠梗阻](https://s.weibo.com/weibo?q=%23%E5%90%BE%E6%81%A9%20%E8%82%A0%E6%A2%97%E9%98%BB%23) `101.3K 🔥`
1. [孟佳品牌方 盖娅传说 (Mengjia brand side The Legend of Gaia)](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E4%BD%B3%E5%93%81%E7%89%8C%E6%96%B9%20%E7%9B%96%E5%A8%85%E4%BC%A0%E8%AF%B4%23) `95.6K 🔥`
1. [张桂源上网才知道自己成田赫之子了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%A1%82%E6%BA%90%E4%B8%8A%E7%BD%91%E6%89%8D%E7%9F%A5%E9%81%93%E8%87%AA%E5%B7%B1%E6%88%90%E7%94%B0%E8%B5%AB%E4%B9%8B%E5%AD%90%E4%BA%86%23) `95.3K 🔥`
1. [曝王一博乐华续约 (It is revealed that Wang Yibo Lehua renewed his contract)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%8B%E4%B8%80%E5%8D%9A%E4%B9%90%E5%8D%8E%E7%BB%AD%E7%BA%A6%23) `93.5K 🔥`
1. [李维嘉崩溃大哭到无法主持](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BB%B4%E5%98%89%E5%B4%A9%E6%BA%83%E5%A4%A7%E5%93%AD%E5%88%B0%E6%97%A0%E6%B3%95%E4%B8%BB%E6%8C%81%23) `77.7K 🔥`
1. [前员工爆料海底捞高层点炮制度 (A former employee revealed the high-level shooting system of Haidilao)](https://s.weibo.com/weibo?q=%23%E5%89%8D%E5%91%98%E5%B7%A5%E7%88%86%E6%96%99%E6%B5%B7%E5%BA%95%E6%8D%9E%E9%AB%98%E5%B1%82%E7%82%B9%E7%82%AE%E5%88%B6%E5%BA%A6%23) `771.9K 🔥` `-27%`
1. [妈妈瞒着病重女儿偷偷看最后一眼 (Mother secretly takes one last look at seriously ill daughter without telling her)](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E7%9E%92%E7%9D%80%E7%97%85%E9%87%8D%E5%A5%B3%E5%84%BF%E5%81%B7%E5%81%B7%E7%9C%8B%E6%9C%80%E5%90%8E%E4%B8%80%E7%9C%BC%23) `93.7K 🔥` `-22%`
1. [新任印度驻华大使取了个中国名字](https://s.weibo.com/weibo?q=%23%E6%96%B0%E4%BB%BB%E5%8D%B0%E5%BA%A6%E9%A9%BB%E5%8D%8E%E5%A4%A7%E4%BD%BF%E5%8F%96%E4%BA%86%E4%B8%AA%E4%B8%AD%E5%9B%BD%E5%90%8D%E5%AD%97%23) `93.7K 🔥` `-41%`
1. [迪丽热巴红衣女鬼塑](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%BA%A2%E8%A1%A3%E5%A5%B3%E9%AC%BC%E5%A1%91%23) `84.9K 🔥` `-30%`
1. [全球航运又一大动脉拉响警报](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E8%88%AA%E8%BF%90%E5%8F%88%E4%B8%80%E5%A4%A7%E5%8A%A8%E8%84%89%E6%8B%89%E5%93%8D%E8%AD%A6%E6%8A%A5%23) `82.4K 🔥` `-36%`
1. [怪不得爸妈要各一间卧室](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E7%88%B8%E5%A6%88%E8%A6%81%E5%90%84%E4%B8%80%E9%97%B4%E5%8D%A7%E5%AE%A4%23) `79.4K 🔥` `-46%`
1. [金价还要跌多久](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E8%BF%98%E8%A6%81%E8%B7%8C%E5%A4%9A%E4%B9%85%23) `78.3K 🔥` `-32%`
1. [曝AI短剧使用杨紫的脸](https://s.weibo.com/weibo?q=%23%E6%9B%9DAI%E7%9F%AD%E5%89%A7%E4%BD%BF%E7%94%A8%E6%9D%A8%E7%B4%AB%E7%9A%84%E8%84%B8%23) `77.1K 🔥` `-23%`
1. [重庆市长胡衡华被查 (Chongqing Mayor Hu Henghua was investigated)](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E5%B8%82%E9%95%BF%E8%83%A1%E8%A1%A1%E5%8D%8E%E8%A2%AB%E6%9F%A5%23) `70.1K 🔥` `-36%`
1. [网易严选 玩梗 (NetEase carefully selected jokes)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E6%98%93%E4%B8%A5%E9%80%89%20%E7%8E%A9%E6%A2%97%23) `64.8K 🔥` `-32%`
1. [特朗普全程高能高市被晾一边](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E5%85%A8%E7%A8%8B%E9%AB%98%E8%83%BD%E9%AB%98%E5%B8%82%E8%A2%AB%E6%99%BE%E4%B8%80%E8%BE%B9%23) `62.8K 🔥` `-36%`
1. [发型易容术 (Hair transformation)](https://s.weibo.com/weibo?q=%23%E5%8F%91%E5%9E%8B%E6%98%93%E5%AE%B9%E6%9C%AF%23) `62.5K 🔥` `-50%`

Updated at 2026-03-20 19:45:24

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
