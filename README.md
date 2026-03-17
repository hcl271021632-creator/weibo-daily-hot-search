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

1. [50多斤巨莽现身安溪一工地 (A giant man weighing more than 50 kilograms appeared at a construction site in Anxi)](https://s.weibo.com/weibo?q=%2350%E5%A4%9A%E6%96%A4%E5%B7%A8%E8%8E%BD%E7%8E%B0%E8%BA%AB%E5%AE%89%E6%BA%AA%E4%B8%80%E5%B7%A5%E5%9C%B0%23) `232.0K 🔥` `NEW`
1. [以军认为成功暗杀拉里贾尼](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E8%AE%A4%E4%B8%BA%E6%88%90%E5%8A%9F%E6%9A%97%E6%9D%80%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%23) `229.1K 🔥` `NEW`
1. [逐步推行免费学前教育](https://s.weibo.com/weibo?q=%23%E9%80%90%E6%AD%A5%E6%8E%A8%E8%A1%8C%E5%85%8D%E8%B4%B9%E5%AD%A6%E5%89%8D%E6%95%99%E8%82%B2%23) `224.1K 🔥` `NEW`
1. [两个女孩之间闹掰的原因](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%B8%AA%E5%A5%B3%E5%AD%A9%E4%B9%8B%E9%97%B4%E9%97%B9%E6%8E%B0%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `219.6K 🔥` `NEW`
1. [七万元买QQ到底贵不贵](https://s.weibo.com/weibo?q=%23%E4%B8%83%E4%B8%87%E5%85%83%E4%B9%B0QQ%E5%88%B0%E5%BA%95%E8%B4%B5%E4%B8%8D%E8%B4%B5%23) `119.3K 🔥` `NEW`
1. [正式确诊为番茄](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E5%BC%8F%E7%A1%AE%E8%AF%8A%E4%B8%BA%E7%95%AA%E8%8C%84%23) `110.5K 🔥` `NEW`
1. [张凌赫也抠手](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%B9%9F%E6%8A%A0%E6%89%8B%23) `100.5K 🔥` `NEW`
1. [以色列刺杀拉里贾尼](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%88%BA%E6%9D%80%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%23) `99.9K 🔥` `NEW`
1. [宝宝巴士被罚30万元](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E5%AE%9D%E5%B7%B4%E5%A3%AB%E8%A2%AB%E7%BD%9A30%E4%B8%87%E5%85%83%23) `99.5K 🔥` `NEW`
1. [宋家三胞胎14岁身高](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%AE%B6%E4%B8%89%E8%83%9E%E8%83%8E14%E5%B2%81%E8%BA%AB%E9%AB%98%23) `99.1K 🔥` `NEW`
1. [省考考生被指P高14分误导竞争者 (Provincial exam candidates were accused of misleading competitors by scoring 14 points higher than P)](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%E8%80%83%E7%94%9F%E8%A2%AB%E6%8C%87P%E9%AB%9814%E5%88%86%E8%AF%AF%E5%AF%BC%E7%AB%9E%E4%BA%89%E8%80%85%23) `98.5K 🔥` `NEW`
1. [伊朗这次不想忍了](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%BF%99%E6%AC%A1%E4%B8%8D%E6%83%B3%E5%BF%8D%E4%BA%86%23) `97.9K 🔥` `NEW`
1. [银行金条越来越难买了](https://s.weibo.com/weibo?q=%23%E9%93%B6%E8%A1%8C%E9%87%91%E6%9D%A1%E8%B6%8A%E6%9D%A5%E8%B6%8A%E9%9A%BE%E4%B9%B0%E4%BA%86%23) `94.4K 🔥` `NEW`
1. [苏翊鸣经常教拉塞尔滑雪](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E7%BB%8F%E5%B8%B8%E6%95%99%E6%8B%89%E5%A1%9E%E5%B0%94%E6%BB%91%E9%9B%AA%23) `90.9K 🔥` `NEW`
1. [外交部回应特朗普访华时间](https://s.weibo.com/weibo?q=%23%E5%A4%96%E4%BA%A4%E9%83%A8%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E8%AE%BF%E5%8D%8E%E6%97%B6%E9%97%B4%23) `88.6K 🔥` `NEW`
1. [人生有三样东西最重要](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%94%9F%E6%9C%89%E4%B8%89%E6%A0%B7%E4%B8%9C%E8%A5%BF%E6%9C%80%E9%87%8D%E8%A6%81%23) `72.7K 🔥` `NEW`
1. [王橹杰 男神蜕变之路](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%20%E7%94%B7%E7%A5%9E%E8%9C%95%E5%8F%98%E4%B9%8B%E8%B7%AF%23) `68.5K 🔥` `NEW`
1. [林沐然艾米等比例长大](https://s.weibo.com/weibo?q=%23%E6%9E%97%E6%B2%90%E7%84%B6%E8%89%BE%E7%B1%B3%E7%AD%89%E6%AF%94%E4%BE%8B%E9%95%BF%E5%A4%A7%23) `67.6K 🔥` `NEW`
1. [图书馆就应该建在商场里](https://s.weibo.com/weibo?q=%23%E5%9B%BE%E4%B9%A6%E9%A6%86%E5%B0%B1%E5%BA%94%E8%AF%A5%E5%BB%BA%E5%9C%A8%E5%95%86%E5%9C%BA%E9%87%8C%23) `66.9K 🔥` `NEW`
1. [王子文带儿子聚餐](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AD%90%E6%96%87%E5%B8%A6%E5%84%BF%E5%AD%90%E8%81%9A%E9%A4%90%23) `66.3K 🔥` `NEW`
1. [iOS26无缘最强Siri (iOS26 misses the most powerful Siri)](https://s.weibo.com/weibo?q=%23iOS26%E6%97%A0%E7%BC%98%E6%9C%80%E5%BC%BASiri%23) `66.2K 🔥` `NEW`
1. [杨洋雨霖铃巨幅海报](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E9%9B%A8%E9%9C%96%E9%93%83%E5%B7%A8%E5%B9%85%E6%B5%B7%E6%8A%A5%23) `66.0K 🔥` `NEW`
1. [这才是我梦想中的厨房水池](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%89%8D%E6%98%AF%E6%88%91%E6%A2%A6%E6%83%B3%E4%B8%AD%E7%9A%84%E5%8E%A8%E6%88%BF%E6%B0%B4%E6%B1%A0%23) `62.4K 🔥` `NEW`
1. [美方澄清特朗普威胁推迟访华](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E6%96%B9%E6%BE%84%E6%B8%85%E7%89%B9%E6%9C%97%E6%99%AE%E5%A8%81%E8%83%81%E6%8E%A8%E8%BF%9F%E8%AE%BF%E5%8D%8E%23) `60.9K 🔥` `NEW`
1. [AI大厂月薪3万疯抢文科生](https://s.weibo.com/weibo?q=%23AI%E5%A4%A7%E5%8E%82%E6%9C%88%E8%96%AA3%E4%B8%87%E7%96%AF%E6%8A%A2%E6%96%87%E7%A7%91%E7%94%9F%23) `1.1M 🔥` `+147%`
1. [满13周岁女孩免费接种HPV](https://s.weibo.com/weibo?q=%23%E6%BB%A113%E5%91%A8%E5%B2%81%E5%A5%B3%E5%AD%A9%E5%85%8D%E8%B4%B9%E6%8E%A5%E7%A7%8DHPV%23) `784.2K 🔥` `+825%`
1. [周杰伦说今晚0点准备](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E8%AF%B4%E4%BB%8A%E6%99%9A0%E7%82%B9%E5%87%86%E5%A4%87%23) `231.8K 🔥` `+35%`
1. [原来这就是小鸟胃啊](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E5%B0%B1%E6%98%AF%E5%B0%8F%E9%B8%9F%E8%83%83%E5%95%8A%23) `227.0K 🔥` `+88%`
1. [小巷人家2 范丞丞卢昱晓](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%B7%B7%E4%BA%BA%E5%AE%B62%20%E8%8C%83%E4%B8%9E%E4%B8%9E%E5%8D%A2%E6%98%B1%E6%99%93%23) `226.1K 🔥` `+155%`
1. [神21乘组圆满完成第二次出舱活动](https://s.weibo.com/weibo?q=%23%E7%A5%9E21%E4%B9%98%E7%BB%84%E5%9C%86%E6%BB%A1%E5%AE%8C%E6%88%90%E7%AC%AC%E4%BA%8C%E6%AC%A1%E5%87%BA%E8%88%B1%E6%B4%BB%E5%8A%A8%23) `629.2K 🔥`
1. [深圳卫健委抽烟这块越骂越勇 (The Shenzhen Health Commission becomes more aggressive when it comes to scolding people about smoking.)](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E5%8D%AB%E5%81%A5%E5%A7%94%E6%8A%BD%E7%83%9F%E8%BF%99%E5%9D%97%E8%B6%8A%E9%AA%82%E8%B6%8A%E5%8B%87%23) `165.6K 🔥`
1. [JackeyLove谈BLG战胜BFX](https://s.weibo.com/weibo?q=%23JackeyLove%E8%B0%88BLG%E6%88%98%E8%83%9CBFX%23) `79.3K 🔥`
1. [山姆三文鱼遵循的是非即食国标](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E4%B8%89%E6%96%87%E9%B1%BC%E9%81%B5%E5%BE%AA%E7%9A%84%E6%98%AF%E9%9D%9E%E5%8D%B3%E9%A3%9F%E5%9B%BD%E6%A0%87%23) `60.8K 🔥`
1. [舒淇喊你一块喝好茶](https://s.weibo.com/weibo?q=%23%E8%88%92%E6%B7%87%E5%96%8A%E4%BD%A0%E4%B8%80%E5%9D%97%E5%96%9D%E5%A5%BD%E8%8C%B6%23) `283.6K 🔥` `-41%`
1. [小巷人家2官宣 (Alley People 2 Official Announcement)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%B7%B7%E4%BA%BA%E5%AE%B62%E5%AE%98%E5%AE%A3%23) `221.7K 🔥` `-81%`
1. [中方向伊朗提供人道主义援助](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%90%91%E4%BC%8A%E6%9C%97%E6%8F%90%E4%BE%9B%E4%BA%BA%E9%81%93%E4%B8%BB%E4%B9%89%E6%8F%B4%E5%8A%A9%23) `221.1K 🔥` `-21%`
1. [正午阳光又要拍宅斗了](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E5%8D%88%E9%98%B3%E5%85%89%E5%8F%88%E8%A6%81%E6%8B%8D%E5%AE%85%E6%96%97%E4%BA%86%23) `214.8K 🔥` `-28%`
1. [赵丽颖于适 浮华之上 (Zhao Liying is suitable for the glitz and glamor)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E4%BA%8E%E9%80%82%20%E6%B5%AE%E5%8D%8E%E4%B9%8B%E4%B8%8A%23) `199.0K 🔥` `-28%`
1. [A股行情](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E8%A1%8C%E6%83%85%23) `133.5K 🔥` `-50%`
1. [小巷人家第二部 (Alley People Part 2)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%B7%B7%E4%BA%BA%E5%AE%B6%E7%AC%AC%E4%BA%8C%E9%83%A8%23) `127.0K 🔥` `-69%`
1. [刘昊然 周冬雨](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%98%8A%E7%84%B6%20%E5%91%A8%E5%86%AC%E9%9B%A8%23) `100.3K 🔥` `-42%`
1. [金价大跌黄金9点开卖9点01分售罄](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%A4%A7%E8%B7%8C%E9%BB%84%E9%87%919%E7%82%B9%E5%BC%80%E5%8D%969%E7%82%B901%E5%88%86%E5%94%AE%E7%BD%84%23) `99.6K 🔥` `-42%`
1. [伊朗警告日本 (Iran warns Japan)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%AD%A6%E5%91%8A%E6%97%A5%E6%9C%AC%23) `98.7K 🔥` `-61%`
1. [金价下跌却买不进](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E4%B8%8B%E8%B7%8C%E5%8D%B4%E4%B9%B0%E4%B8%8D%E8%BF%9B%23) `98.3K 🔥` `-65%`
1. [曝小巷人家2剧情 (Exposing the plot of Alley People 2)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%B0%8F%E5%B7%B7%E4%BA%BA%E5%AE%B62%E5%89%A7%E6%83%85%23) `97.8K 🔥` `-39%`
1. [高中生斑马线过马路被撞飞身亡](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%B8%AD%E7%94%9F%E6%96%91%E9%A9%AC%E7%BA%BF%E8%BF%87%E9%A9%AC%E8%B7%AF%E8%A2%AB%E6%92%9E%E9%A3%9E%E8%BA%AB%E4%BA%A1%23) `96.7K 🔥` `-52%`
1. [豆包给周也指导的穿搭](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E7%BB%99%E5%91%A8%E4%B9%9F%E6%8C%87%E5%AF%BC%E7%9A%84%E7%A9%BF%E6%90%AD%23) `78.1K 🔥` `-65%`
1. [ELLE四月刊张凌赫封面预告](https://s.weibo.com/weibo?q=%23ELLE%E5%9B%9B%E6%9C%88%E5%88%8A%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%B0%81%E9%9D%A2%E9%A2%84%E5%91%8A%23) `74.9K 🔥` `-36%`
1. [正午阳光2026片单](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E5%8D%88%E9%98%B3%E5%85%892026%E7%89%87%E5%8D%95%23) `66.5K 🔥` `-62%`
1. [男子买18元彩票中1734万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E4%B9%B018%E5%85%83%E5%BD%A9%E7%A5%A8%E4%B8%AD1734%E4%B8%87%23) `66.1K 🔥` `-39%`
1. [易烊千玺网站歌曲投票 (Yi Yang Qianxi website song voting)](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E7%BD%91%E7%AB%99%E6%AD%8C%E6%9B%B2%E6%8A%95%E7%A5%A8%23) `65.5K 🔥` `-29%`

Updated at 2026-03-17 17:08:40

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
