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

1. [女子请屠夫杀年猪惨遭其儿子杀害 (A woman asked a butcher to kill a New Year pig but was killed by her son)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%AF%B7%E5%B1%A0%E5%A4%AB%E6%9D%80%E5%B9%B4%E7%8C%AA%E6%83%A8%E9%81%AD%E5%85%B6%E5%84%BF%E5%AD%90%E6%9D%80%E5%AE%B3%23) `1.1M 🔥` `NEW`
1. [张凌赫解锁华帝人生净界](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%A7%A3%E9%94%81%E5%8D%8E%E5%B8%9D%E4%BA%BA%E7%94%9F%E5%87%80%E7%95%8C%23) `362.2K 🔥` `NEW`
1. [逐玉 庆功宴](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%BA%86%E5%8A%9F%E5%AE%B4%23) `362.1K 🔥` `NEW`
1. [THE9在安崎微博团建](https://s.weibo.com/weibo?q=%23THE9%E5%9C%A8%E5%AE%89%E5%B4%8E%E5%BE%AE%E5%8D%9A%E5%9B%A2%E5%BB%BA%23) `359.9K 🔥` `NEW`
1. [蔡徐坤直播](https://s.weibo.com/weibo?q=%23%E8%94%A1%E5%BE%90%E5%9D%A4%E7%9B%B4%E6%92%AD%23) `349.6K 🔥` `NEW`
1. [虞书欣梦回凌妙妙](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%A2%A6%E5%9B%9E%E5%87%8C%E5%A6%99%E5%A6%99%23) `312.3K 🔥` `NEW`
1. [今年蚊子可能迎来史诗级加强](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E8%9A%8A%E5%AD%90%E5%8F%AF%E8%83%BD%E8%BF%8E%E6%9D%A5%E5%8F%B2%E8%AF%97%E7%BA%A7%E5%8A%A0%E5%BC%BA%23) `218.7K 🔥` `NEW`
1. [西班牙25岁女孩被性侵多次后申请安乐死](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E7%8F%AD%E7%89%9925%E5%B2%81%E5%A5%B3%E5%AD%A9%E8%A2%AB%E6%80%A7%E4%BE%B5%E5%A4%9A%E6%AC%A1%E5%90%8E%E7%94%B3%E8%AF%B7%E5%AE%89%E4%B9%90%E6%AD%BB%23) `150.7K 🔥` `NEW`
1. [做饭好吃的底层逻辑](https://s.weibo.com/weibo?q=%23%E5%81%9A%E9%A5%AD%E5%A5%BD%E5%90%83%E7%9A%84%E5%BA%95%E5%B1%82%E9%80%BB%E8%BE%91%23) `146.6K 🔥` `NEW`
1. [是你的孩子吗你就背](https://s.weibo.com/weibo?q=%23%E6%98%AF%E4%BD%A0%E7%9A%84%E5%AD%A9%E5%AD%90%E5%90%97%E4%BD%A0%E5%B0%B1%E8%83%8C%23) `141.6K 🔥` `NEW`
1. [张杰鸟巢演唱会 (Zhang Jie Bird's Nest Concert)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E9%B8%9F%E5%B7%A2%E6%BC%94%E5%94%B1%E4%BC%9A%23) `108.7K 🔥` `NEW`
1. [张凌赫涨粉量](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%B6%A8%E7%B2%89%E9%87%8F%23) `106.1K 🔥` `NEW`
1. [错撩漫画](https://s.weibo.com/weibo?q=%23%E9%94%99%E6%92%A9%E6%BC%AB%E7%94%BB%23) `103.3K 🔥` `NEW`
1. [张极直播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9E%81%E7%9B%B4%E6%92%AD%23) `96.8K 🔥` `NEW`
1. [大学生表白被拒后怒砸食堂咖啡店](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F%E8%A1%A8%E7%99%BD%E8%A2%AB%E6%8B%92%E5%90%8E%E6%80%92%E7%A0%B8%E9%A3%9F%E5%A0%82%E5%92%96%E5%95%A1%E5%BA%97%23) `90.6K 🔥` `NEW`
1. [伊朗革命卫队称霍尔木兹海峡关闭](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E7%A7%B0%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%85%B3%E9%97%AD%23) `410.7K 🔥` `+80%`
1. [中国博士后遭美方约谈盘问后自杀 (Chinese postdoctoral fellow committed suicide after being interviewed and questioned by the US)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%8D%9A%E5%A3%AB%E5%90%8E%E9%81%AD%E7%BE%8E%E6%96%B9%E7%BA%A6%E8%B0%88%E7%9B%98%E9%97%AE%E5%90%8E%E8%87%AA%E6%9D%80%23) `381.6K 🔥` `+37%`
1. [大部分人觉得旅游累的原因](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E9%83%A8%E5%88%86%E4%BA%BA%E8%A7%89%E5%BE%97%E6%97%85%E6%B8%B8%E7%B4%AF%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `363.1K 🔥` `+278%`
1. [TES欢迎JackeyLove归来](https://s.weibo.com/weibo?q=%23TES%E6%AC%A2%E8%BF%8EJackeyLove%E5%BD%92%E6%9D%A5%23) `359.4K 🔥` `+269%`
1. [王一博微博改名](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%BE%AE%E5%8D%9A%E6%94%B9%E5%90%8D%23) `357.6K 🔥` `+98%`
1. [疑似商K工作人员回应](https://s.weibo.com/weibo?q=%23%E7%96%91%E4%BC%BC%E5%95%86K%E5%B7%A5%E4%BD%9C%E4%BA%BA%E5%91%98%E5%9B%9E%E5%BA%94%23) `356.6K 🔥` `+103%`
1. [保留奔跑吧艺人剩菜店家道歉 (Store owner apologizes for retaining Running Bar artist's leftovers)](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E7%95%99%E5%A5%94%E8%B7%91%E5%90%A7%E8%89%BA%E4%BA%BA%E5%89%A9%E8%8F%9C%E5%BA%97%E5%AE%B6%E9%81%93%E6%AD%89%23) `356.0K 🔥` `+57%`
1. [刘昊然 商K](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%98%8A%E7%84%B6%20%E5%95%86K%23) `355.3K 🔥` `+111%`
1. [王橹杰换头像](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%8D%A2%E5%A4%B4%E5%83%8F%23) `353.2K 🔥` `+119%`
1. [中方回应美称中企向伊军提供芯片](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%BE%8E%E7%A7%B0%E4%B8%AD%E4%BC%81%E5%90%91%E4%BC%8A%E5%86%9B%E6%8F%90%E4%BE%9B%E8%8A%AF%E7%89%87%23) `352.6K 🔥` `+69%`
1. [深蓝董事长拆解行驶50万公里电驱](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E8%93%9D%E8%91%A3%E4%BA%8B%E9%95%BF%E6%8B%86%E8%A7%A3%E8%A1%8C%E9%A9%B650%E4%B8%87%E5%85%AC%E9%87%8C%E7%94%B5%E9%A9%B1%23) `351.0K 🔥` `+79%`
1. [王一博乐华续约](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E4%B9%90%E5%8D%8E%E7%BB%AD%E7%BA%A6%23) `350.0K 🔥` `+158%`
1. [4500元冲锋衣被湿巾擦坏仅赔278元 (A 4,500 yuan jacket was damaged by a wet wipe and only 278 yuan was paid.)](https://s.weibo.com/weibo?q=%234500%E5%85%83%E5%86%B2%E9%94%8B%E8%A1%A3%E8%A2%AB%E6%B9%BF%E5%B7%BE%E6%93%A6%E5%9D%8F%E4%BB%85%E8%B5%94278%E5%85%83%23) `347.9K 🔥` `+104%`
1. [黄灿灿浪姐连麦杨紫 (Huang Cancanlang's sister Lianmai Yangzi)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E7%81%BF%E7%81%BF%E6%B5%AA%E5%A7%90%E8%BF%9E%E9%BA%A6%E6%9D%A8%E7%B4%AB%23) `347.5K 🔥` `+50%`
1. [女子手指截肢放肚里养1个月变小肉球](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%89%8B%E6%8C%87%E6%88%AA%E8%82%A2%E6%94%BE%E8%82%9A%E9%87%8C%E5%85%BB1%E4%B8%AA%E6%9C%88%E5%8F%98%E5%B0%8F%E8%82%89%E7%90%83%23) `224.2K 🔥` `+29%`
1. [UNIQ组合已解散](https://s.weibo.com/weibo?q=%23UNIQ%E7%BB%84%E5%90%88%E5%B7%B2%E8%A7%A3%E6%95%A3%23) `223.6K 🔥` `+119%`
1. [尚界Z7随行美容舱 (Shangjie Z7 accompanying beauty cabin)](https://s.weibo.com/weibo?q=%23%E5%B0%9A%E7%95%8CZ7%E9%9A%8F%E8%A1%8C%E7%BE%8E%E5%AE%B9%E8%88%B1%23) `189.4K 🔥` `+39%`
1. [王源新纹身](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BA%90%E6%96%B0%E7%BA%B9%E8%BA%AB%23) `180.8K 🔥` `+48%`
1. [刘昊然方发律师声明](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%98%8A%E7%84%B6%E6%96%B9%E5%8F%91%E5%BE%8B%E5%B8%88%E5%A3%B0%E6%98%8E%23) `145.7K 🔥` `+49%`
1. [陈思罕新头像 (Chen Sihan's new avatar)](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%80%9D%E7%BD%95%E6%96%B0%E5%A4%B4%E5%83%8F%23) `140.5K 🔥` `+35%`
1. [海南自贸港封关运作100天 (Hainan Free Trade Port closed for 100 days)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8D%97%E8%87%AA%E8%B4%B8%E6%B8%AF%E5%B0%81%E5%85%B3%E8%BF%90%E4%BD%9C100%E5%A4%A9%23) `600.3K 🔥`
1. [乘风2026官宣阵容 (Chengfeng 2026 official lineup announced)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%AE%98%E5%AE%A3%E9%98%B5%E5%AE%B9%23) `217.3K 🔥`
1. [奉劝大家还是尽量多存钱](https://s.weibo.com/weibo?q=%23%E5%A5%89%E5%8A%9D%E5%A4%A7%E5%AE%B6%E8%BF%98%E6%98%AF%E5%B0%BD%E9%87%8F%E5%A4%9A%E5%AD%98%E9%92%B1%23) `153.5K 🔥`
1. [迪丽热巴提灯走机场 (Dilireba walks through the airport holding a lantern)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%8F%90%E7%81%AF%E8%B5%B0%E6%9C%BA%E5%9C%BA%23) `149.7K 🔥`
1. [郭麒麟对接回应KTV传闻](https://s.weibo.com/weibo?q=%23%E9%83%AD%E9%BA%92%E9%BA%9F%E5%AF%B9%E6%8E%A5%E5%9B%9E%E5%BA%94KTV%E4%BC%A0%E9%97%BB%23) `106.0K 🔥`
1. [乘风2026师姐帮帮唱 (Chengfeng 2026 senior sister helps sing)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%B8%88%E5%A7%90%E5%B8%AE%E5%B8%AE%E5%94%B1%23) `102.2K 🔥`
1. [乘风2026定档 (Chengfeng 2026 scheduled)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%AE%9A%E6%A1%A3%23) `90.7K 🔥`
1. [职称评审将迎重大调整](https://s.weibo.com/weibo?q=%23%E8%81%8C%E7%A7%B0%E8%AF%84%E5%AE%A1%E5%B0%86%E8%BF%8E%E9%87%8D%E5%A4%A7%E8%B0%83%E6%95%B4%23) `757.9K 🔥` `-28%`
1. [国足赢了世界杯球队](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E8%B6%B3%E8%B5%A2%E4%BA%86%E4%B8%96%E7%95%8C%E6%9D%AF%E7%90%83%E9%98%9F%23) `361.5K 🔥` `-53%`
1. [郭永航被查](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%B0%B8%E8%88%AA%E8%A2%AB%E6%9F%A5%23) `151.2K 🔥` `-38%`
1. [乘风2026](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%23) `147.5K 🔥` `-36%`
1. [花少8在约宋威龙张凌赫](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%B0%918%E5%9C%A8%E7%BA%A6%E5%AE%8B%E5%A8%81%E9%BE%99%E5%BC%A0%E5%87%8C%E8%B5%AB%23) `145.7K 🔥` `-21%`
1. [起底日本撞人族](https://s.weibo.com/weibo?q=%23%E8%B5%B7%E5%BA%95%E6%97%A5%E6%9C%AC%E6%92%9E%E4%BA%BA%E6%97%8F%23) `106.2K 🔥` `-42%`
1. [熬夜的人要多吃一类食物](https://s.weibo.com/weibo?q=%23%E7%86%AC%E5%A4%9C%E7%9A%84%E4%BA%BA%E8%A6%81%E5%A4%9A%E5%90%83%E4%B8%80%E7%B1%BB%E9%A3%9F%E7%89%A9%23) `94.3K 🔥` `-29%`
1. [法院通报副院长与原告同吃同拜佛 (The court informed that the vice-president and the plaintiff ate and worshiped together)](https://s.weibo.com/weibo?q=%23%E6%B3%95%E9%99%A2%E9%80%9A%E6%8A%A5%E5%89%AF%E9%99%A2%E9%95%BF%E4%B8%8E%E5%8E%9F%E5%91%8A%E5%90%8C%E5%90%83%E5%90%8C%E6%8B%9C%E4%BD%9B%23) `86.8K 🔥` `-57%`

Updated at 2026-03-27 20:03:56

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
