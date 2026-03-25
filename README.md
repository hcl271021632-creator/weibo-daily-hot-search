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

1. [何凯文 我连假装较劲的对象都没了 (He Kaiwen, I don’t even have anyone to pretend to compete with anymore.)](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%87%AF%E6%96%87%20%E6%88%91%E8%BF%9E%E5%81%87%E8%A3%85%E8%BE%83%E5%8A%B2%E7%9A%84%E5%AF%B9%E8%B1%A1%E9%83%BD%E6%B2%A1%E4%BA%86%23) `874.5K 🔥` `NEW`
1. [张雪峰曾含泪说苦和累都是为了家人](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%9B%BE%E5%90%AB%E6%B3%AA%E8%AF%B4%E8%8B%A6%E5%92%8C%E7%B4%AF%E9%83%BD%E6%98%AF%E4%B8%BA%E4%BA%86%E5%AE%B6%E4%BA%BA%23) `225.0K 🔥` `NEW`
1. [以纯品牌代言人范丞丞](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E7%BA%AF%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%E8%8C%83%E4%B8%9E%E4%B8%9E%23) `224.5K 🔥` `NEW`
1. [3个旧手机能换一台iPhone](https://s.weibo.com/weibo?q=%233%E4%B8%AA%E6%97%A7%E6%89%8B%E6%9C%BA%E8%83%BD%E6%8D%A2%E4%B8%80%E5%8F%B0iPhone%23) `223.0K 🔥` `NEW`
1. [小泡芙颜值](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E6%B3%A1%E8%8A%99%E9%A2%9C%E5%80%BC%23) `222.3K 🔥` `NEW`
1. [刘晓庆再发文辟谣去世](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%86%E5%86%8D%E5%8F%91%E6%96%87%E8%BE%9F%E8%B0%A3%E5%8E%BB%E4%B8%96%23) `221.0K 🔥` `NEW`
1. [扎着马步吃麦辣夯爆了](https://s.weibo.com/weibo?q=%23%E6%89%8E%E7%9D%80%E9%A9%AC%E6%AD%A5%E5%90%83%E9%BA%A6%E8%BE%A3%E5%A4%AF%E7%88%86%E4%BA%86%23) `201.8K 🔥` `NEW`
1. [外交部发言人反问](https://s.weibo.com/weibo?q=%23%E5%A4%96%E4%BA%A4%E9%83%A8%E5%8F%91%E8%A8%80%E4%BA%BA%E5%8F%8D%E9%97%AE%23) `184.6K 🔥` `NEW`
1. [油管网红露脸导致事业被毁](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E7%AE%A1%E7%BD%91%E7%BA%A2%E9%9C%B2%E8%84%B8%E5%AF%BC%E8%87%B4%E4%BA%8B%E4%B8%9A%E8%A2%AB%E6%AF%81%23) `136.9K 🔥` `NEW`
1. [逐玉爆火后最大的受害者](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%88%86%E7%81%AB%E5%90%8E%E6%9C%80%E5%A4%A7%E7%9A%84%E5%8F%97%E5%AE%B3%E8%80%85%23) `121.4K 🔥` `NEW`
1. [多位年轻企业家因心梗离世 (Many young entrepreneurs passed away due to heart attack)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E4%BD%8D%E5%B9%B4%E8%BD%BB%E4%BC%81%E4%B8%9A%E5%AE%B6%E5%9B%A0%E5%BF%83%E6%A2%97%E7%A6%BB%E4%B8%96%23) `109.1K 🔥` `NEW`
1. [严浩翔新歌暗黑美学](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E6%B5%A9%E7%BF%94%E6%96%B0%E6%AD%8C%E6%9A%97%E9%BB%91%E7%BE%8E%E5%AD%A6%23) `108.8K 🔥` `NEW`
1. [霍建华当导演](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%BB%BA%E5%8D%8E%E5%BD%93%E5%AF%BC%E6%BC%94%23) `108.1K 🔥` `NEW`
1. [随元青竟然欺负洪世贤艾莉儿子](https://s.weibo.com/weibo?q=%23%E9%9A%8F%E5%85%83%E9%9D%92%E7%AB%9F%E7%84%B6%E6%AC%BA%E8%B4%9F%E6%B4%AA%E4%B8%96%E8%B4%A4%E8%89%BE%E8%8E%89%E5%84%BF%E5%AD%90%23) `106.9K 🔥` `NEW`
1. [被塞后备箱男孩现在很活泼](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E5%A1%9E%E5%90%8E%E5%A4%87%E7%AE%B1%E7%94%B7%E5%AD%A9%E7%8E%B0%E5%9C%A8%E5%BE%88%E6%B4%BB%E6%B3%BC%23) `106.7K 🔥` `NEW`
1. [情侣正亲密被酒店员工开窗最新进展](https://s.weibo.com/weibo?q=%23%E6%83%85%E4%BE%A3%E6%AD%A3%E4%BA%B2%E5%AF%86%E8%A2%AB%E9%85%92%E5%BA%97%E5%91%98%E5%B7%A5%E5%BC%80%E7%AA%97%E6%9C%80%E6%96%B0%E8%BF%9B%E5%B1%95%23) `105.2K 🔥` `NEW`
1. [商场回应专柜买4个LV包为假货](https://s.weibo.com/weibo?q=%23%E5%95%86%E5%9C%BA%E5%9B%9E%E5%BA%94%E4%B8%93%E6%9F%9C%E4%B9%B04%E4%B8%AALV%E5%8C%85%E4%B8%BA%E5%81%87%E8%B4%A7%23) `104.4K 🔥` `NEW`
1. [伊朗喊话美国别把失败说成协议](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%96%8A%E8%AF%9D%E7%BE%8E%E5%9B%BD%E5%88%AB%E6%8A%8A%E5%A4%B1%E8%B4%A5%E8%AF%B4%E6%88%90%E5%8D%8F%E8%AE%AE%23) `93.8K 🔥` `NEW`
1. [迪丽热巴贺思慕特效妆vlog](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E8%B4%BA%E6%80%9D%E6%85%95%E7%89%B9%E6%95%88%E5%A6%86vlog%23) `91.6K 🔥` `NEW`
1. [青菜焦虑症](https://s.weibo.com/weibo?q=%23%E9%9D%92%E8%8F%9C%E7%84%A6%E8%99%91%E7%97%87%23) `82.0K 🔥` `NEW`
1. [徐涛课程取消 (Xu Tao's course canceled)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%B6%9B%E8%AF%BE%E7%A8%8B%E5%8F%96%E6%B6%88%23) `1.5M 🔥` `+160%`
1. [张雪峰离世留下的生意与争议](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E7%A6%BB%E4%B8%96%E7%95%99%E4%B8%8B%E7%9A%84%E7%94%9F%E6%84%8F%E4%B8%8E%E4%BA%89%E8%AE%AE%23) `222.8K 🔥` `+73%`
1. [程潇 布偶猫](https://s.weibo.com/weibo?q=%23%E7%A8%8B%E6%BD%87%20%E5%B8%83%E5%81%B6%E7%8C%AB%23) `220.1K 🔥` `+64%`
1. [美国男子养老院强奸61岁老人被拍下](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E7%94%B7%E5%AD%90%E5%85%BB%E8%80%81%E9%99%A2%E5%BC%BA%E5%A5%B861%E5%B2%81%E8%80%81%E4%BA%BA%E8%A2%AB%E6%8B%8D%E4%B8%8B%23) `182.2K 🔥` `+22%`
1. [9年时间雄安新区长成了啥模样 (What has Xiongan New Area looked like in 9 years?)](https://s.weibo.com/weibo?q=%239%E5%B9%B4%E6%97%B6%E9%97%B4%E9%9B%84%E5%AE%89%E6%96%B0%E5%8C%BA%E9%95%BF%E6%88%90%E4%BA%86%E5%95%A5%E6%A8%A1%E6%A0%B7%23) `734.2K 🔥`
1. [何润东 翻红](https://s.weibo.com/weibo?q=%23%E4%BD%95%E6%B6%A6%E4%B8%9C%20%E7%BF%BB%E7%BA%A2%23) `221.3K 🔥`
1. [心源性猝死急救最忌打车去医院](https://s.weibo.com/weibo?q=%23%E5%BF%83%E6%BA%90%E6%80%A7%E7%8C%9D%E6%AD%BB%E6%80%A5%E6%95%91%E6%9C%80%E5%BF%8C%E6%89%93%E8%BD%A6%E5%8E%BB%E5%8C%BB%E9%99%A2%23) `220.6K 🔥`
1. [李艺彤哭着和粉丝道歉](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%89%BA%E5%BD%A4%E5%93%AD%E7%9D%80%E5%92%8C%E7%B2%89%E4%B8%9D%E9%81%93%E6%AD%89%23) `220.4K 🔥`
1. [遭虐待男童反复说妈妈你能带我走吗](https://s.weibo.com/weibo?q=%23%E9%81%AD%E8%99%90%E5%BE%85%E7%94%B7%E7%AB%A5%E5%8F%8D%E5%A4%8D%E8%AF%B4%E5%A6%88%E5%A6%88%E4%BD%A0%E8%83%BD%E5%B8%A6%E6%88%91%E8%B5%B0%E5%90%97%23) `203.3K 🔥`
1. [线下追星 拼床](https://s.weibo.com/weibo?q=%23%E7%BA%BF%E4%B8%8B%E8%BF%BD%E6%98%9F%20%E6%8B%BC%E5%BA%8A%23) `199.5K 🔥`
1. [越来越多日本女性为供养牛郎跨境卖淫 (More and more Japanese women are engaging in cross-border prostitution to support cowherds)](https://s.weibo.com/weibo?q=%23%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%A4%9A%E6%97%A5%E6%9C%AC%E5%A5%B3%E6%80%A7%E4%B8%BA%E4%BE%9B%E5%85%BB%E7%89%9B%E9%83%8E%E8%B7%A8%E5%A2%83%E5%8D%96%E6%B7%AB%23) `194.0K 🔥`
1. [颜如晶一年减重2.9斤](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%A6%82%E6%99%B6%E4%B8%80%E5%B9%B4%E5%87%8F%E9%87%8D2.9%E6%96%A4%23) `174.6K 🔥`
1. [金智媛宝格丽合照C位 (Kim Ji-won and Bulgari group photo in C position)](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%99%BA%E5%AA%9B%E5%AE%9D%E6%A0%BC%E4%B8%BD%E5%90%88%E7%85%A7C%E4%BD%8D%23) `168.7K 🔥`
1. [张雪峰生前开导抑郁女孩 (Zhang Xuefeng enlightened depressed girls during his lifetime)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E7%94%9F%E5%89%8D%E5%BC%80%E5%AF%BC%E6%8A%91%E9%83%81%E5%A5%B3%E5%AD%A9%23) `126.6K 🔥`
1. [和平统一后大陆可帮台湾建环岛高铁 (After peaceful reunification, the mainland can help Taiwan build a high-speed rail around the island)](https://s.weibo.com/weibo?q=%23%E5%92%8C%E5%B9%B3%E7%BB%9F%E4%B8%80%E5%90%8E%E5%A4%A7%E9%99%86%E5%8F%AF%E5%B8%AE%E5%8F%B0%E6%B9%BE%E5%BB%BA%E7%8E%AF%E5%B2%9B%E9%AB%98%E9%93%81%23) `275.1K 🔥` `-74%`
1. [花27万买摊位老板开业5天快回本一半](https://s.weibo.com/weibo?q=%23%E8%8A%B127%E4%B8%87%E4%B9%B0%E6%91%8A%E4%BD%8D%E8%80%81%E6%9D%BF%E5%BC%80%E4%B8%9A5%E5%A4%A9%E5%BF%AB%E5%9B%9E%E6%9C%AC%E4%B8%80%E5%8D%8A%23) `225.0K 🔥` `-40%`
1. [去动物园一定不要穿水果鞋](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E5%8A%A8%E7%89%A9%E5%9B%AD%E4%B8%80%E5%AE%9A%E4%B8%8D%E8%A6%81%E7%A9%BF%E6%B0%B4%E6%9E%9C%E9%9E%8B%23) `224.4K 🔥` `-23%`
1. [过度自律 (excessive self-discipline)](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%BA%A6%E8%87%AA%E5%BE%8B%23) `223.9K 🔥` `-71%`
1. [央视新闻发了逐玉](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB%E5%8F%91%E4%BA%86%E9%80%90%E7%8E%89%23) `223.5K 🔥` `-23%`
1. [大冰曾劝张雪峰做了好事要往外说](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%86%B0%E6%9B%BE%E5%8A%9D%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%81%9A%E4%BA%86%E5%A5%BD%E4%BA%8B%E8%A6%81%E5%BE%80%E5%A4%96%E8%AF%B4%23) `221.8K 🔥` `-39%`
1. [浪姐7阵容 (Lang Jie 7 lineup)](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%907%E9%98%B5%E5%AE%B9%23) `191.0K 🔥` `-29%`
1. [偶遇孔刘与男子搭肩散步](https://s.weibo.com/weibo?q=%23%E5%81%B6%E9%81%87%E5%AD%94%E5%88%98%E4%B8%8E%E7%94%B7%E5%AD%90%E6%90%AD%E8%82%A9%E6%95%A3%E6%AD%A5%23) `184.2K 🔥` `-32%`
1. [朋友圈跑步打卡](https://s.weibo.com/weibo?q=%23%E6%9C%8B%E5%8F%8B%E5%9C%88%E8%B7%91%E6%AD%A5%E6%89%93%E5%8D%A1%23) `150.7K 🔥` `-44%`
1. [奔跑吧 (run)](https://s.weibo.com/weibo?q=%23%E5%A5%94%E8%B7%91%E5%90%A7%23) `139.0K 🔥` `-39%`
1. [迪丽热巴陈飞宇一个爆炸头一个牛舔头](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%99%88%E9%A3%9E%E5%AE%87%E4%B8%80%E4%B8%AA%E7%88%86%E7%82%B8%E5%A4%B4%E4%B8%80%E4%B8%AA%E7%89%9B%E8%88%94%E5%A4%B4%23) `126.6K 🔥` `-34%`
1. [杨笠说我撑过来了](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%AC%A0%E8%AF%B4%E6%88%91%E6%92%91%E8%BF%87%E6%9D%A5%E4%BA%86%23) `104.4K 🔥` `-24%`
1. [嘴唇发紫 心脏不好 (Purple lips, bad heart)](https://s.weibo.com/weibo?q=%23%E5%98%B4%E5%94%87%E5%8F%91%E7%B4%AB%20%E5%BF%83%E8%84%8F%E4%B8%8D%E5%A5%BD%23) `104.0K 🔥` `-63%`
1. [周杰伦新歌从夯到拉排名 (Jay Chou's new songs ranked from popular to popular)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E6%AD%8C%E4%BB%8E%E5%A4%AF%E5%88%B0%E6%8B%89%E6%8E%92%E5%90%8D%23) `100.0K 🔥` `-32%`
1. [都来向刘晓庆学习就不死](https://s.weibo.com/weibo?q=%23%E9%83%BD%E6%9D%A5%E5%90%91%E5%88%98%E6%99%93%E5%BA%86%E5%AD%A6%E4%B9%A0%E5%B0%B1%E4%B8%8D%E6%AD%BB%23) `87.2K 🔥` `-28%`
1. [A股大反弹能持续多久 (How long can the A-share rebound last?)](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E5%A4%A7%E5%8F%8D%E5%BC%B9%E8%83%BD%E6%8C%81%E7%BB%AD%E5%A4%9A%E4%B9%85%23) `83.9K 🔥` `-38%`

Updated at 2026-03-25 16:08:16

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
