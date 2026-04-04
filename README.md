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

1. [凡人修仙传 (A Mortal's Story of Cultivation into Immortality)](https://s.weibo.com/weibo?q=%23%E5%87%A1%E4%BA%BA%E4%BF%AE%E4%BB%99%E4%BC%A0%23) `273.4K 🔥` `NEW`
1. [TXT新专 万妮达](https://s.weibo.com/weibo?q=%23TXT%E6%96%B0%E4%B8%93%20%E4%B8%87%E5%A6%AE%E8%BE%BE%23) `255.7K 🔥` `NEW`
1. [林昀儒4比1张本智和](https://s.weibo.com/weibo?q=%23%E6%9E%97%E6%98%80%E5%84%924%E6%AF%941%E5%BC%A0%E6%9C%AC%E6%99%BA%E5%92%8C%23) `206.3K 🔥` `NEW`
1. [孙颖莎vs高达](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E9%AB%98%E8%BE%BE%23) `204.0K 🔥` `NEW`
1. [李兰迪回应何宣林wink](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%85%B0%E8%BF%AA%E5%9B%9E%E5%BA%94%E4%BD%95%E5%AE%A3%E6%9E%97wink%23) `138.0K 🔥` `NEW`
1. [美军经历开战以来最黑暗24小时](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E7%BB%8F%E5%8E%86%E5%BC%80%E6%88%98%E4%BB%A5%E6%9D%A5%E6%9C%80%E9%BB%91%E6%9A%9724%E5%B0%8F%E6%97%B6%23) `127.1K 🔥` `NEW`
1. [孙颖莎13比11高达](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E13%E6%AF%9411%E9%AB%98%E8%BE%BE%23) `108.1K 🔥` `NEW`
1. [谢霆锋戴与王菲26年前定情手镯](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E9%9C%86%E9%94%8B%E6%88%B4%E4%B8%8E%E7%8E%8B%E8%8F%B226%E5%B9%B4%E5%89%8D%E5%AE%9A%E6%83%85%E6%89%8B%E9%95%AF%23) `105.6K 🔥` `NEW`
1. [天才游戏](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E6%89%8D%E6%B8%B8%E6%88%8F%23) `98.6K 🔥` `NEW`
1. [谢依霖自曝酒后和老公狂恋](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E4%BE%9D%E9%9C%96%E8%87%AA%E6%9B%9D%E9%85%92%E5%90%8E%E5%92%8C%E8%80%81%E5%85%AC%E7%8B%82%E6%81%8B%23) `90.5K 🔥` `NEW`
1. [孙颖莎高达首局爆分 (Sun Yingsha scored a high score in the first game)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E9%AB%98%E8%BE%BE%E9%A6%96%E5%B1%80%E7%88%86%E5%88%86%23) `89.8K 🔥` `NEW`
1. [浪姐改赛制给齐思钧苦得都掐眉头了](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E6%94%B9%E8%B5%9B%E5%88%B6%E7%BB%99%E9%BD%90%E6%80%9D%E9%92%A7%E8%8B%A6%E5%BE%97%E9%83%BD%E6%8E%90%E7%9C%89%E5%A4%B4%E4%BA%86%23) `82.7K 🔥` `NEW`
1. [杨瀚森20分7板2助2帽](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%80%9A%E6%A3%AE20%E5%88%867%E6%9D%BF2%E5%8A%A92%E5%B8%BD%23) `79.7K 🔥` `NEW`
1. [双高胎抢票](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E9%AB%98%E8%83%8E%E6%8A%A2%E7%A5%A8%23) `77.7K 🔥` `NEW`
1. [歌不是谁唱火的谁有版权](https://s.weibo.com/weibo?q=%23%E6%AD%8C%E4%B8%8D%E6%98%AF%E8%B0%81%E5%94%B1%E7%81%AB%E7%9A%84%E8%B0%81%E6%9C%89%E7%89%88%E6%9D%83%23) `71.9K 🔥` `NEW`
1. [养猫的人没有私人空间](https://s.weibo.com/weibo?q=%23%E5%85%BB%E7%8C%AB%E7%9A%84%E4%BA%BA%E6%B2%A1%E6%9C%89%E7%A7%81%E4%BA%BA%E7%A9%BA%E9%97%B4%23) `69.5K 🔥` `NEW`
1. [炒菜放盐时机有多重要](https://s.weibo.com/weibo?q=%23%E7%82%92%E8%8F%9C%E6%94%BE%E7%9B%90%E6%97%B6%E6%9C%BA%E6%9C%89%E5%A4%9A%E9%87%8D%E8%A6%81%23) `69.5K 🔥` `NEW`
1. [俩游客花86元就餐店家嫌消费太少](https://s.weibo.com/weibo?q=%23%E4%BF%A9%E6%B8%B8%E5%AE%A2%E8%8A%B186%E5%85%83%E5%B0%B1%E9%A4%90%E5%BA%97%E5%AE%B6%E5%AB%8C%E6%B6%88%E8%B4%B9%E5%A4%AA%E5%B0%91%23) `56.7K 🔥` `NEW`
1. [我妈以为的早熟vs实际上](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%A6%88%E4%BB%A5%E4%B8%BA%E7%9A%84%E6%97%A9%E7%86%9Fvs%E5%AE%9E%E9%99%85%E4%B8%8A%23) `54.8K 🔥` `NEW`
1. [清明上山扫墓却发现母亲的墓不见了](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E4%B8%8A%E5%B1%B1%E6%89%AB%E5%A2%93%E5%8D%B4%E5%8F%91%E7%8E%B0%E6%AF%8D%E4%BA%B2%E7%9A%84%E5%A2%93%E4%B8%8D%E8%A7%81%E4%BA%86%23) `1.1M 🔥` `+474%`
1. [1层3户只有1家被贴满小广告 (Only one of the three households on the first floor is covered with small advertisements)](https://s.weibo.com/weibo?q=%231%E5%B1%823%E6%88%B7%E5%8F%AA%E6%9C%891%E5%AE%B6%E8%A2%AB%E8%B4%B4%E6%BB%A1%E5%B0%8F%E5%B9%BF%E5%91%8A%23) `798.8K 🔥` `+860%`
1. [原来真有人住的房子这么大](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E7%9C%9F%E6%9C%89%E4%BA%BA%E4%BD%8F%E7%9A%84%E6%88%BF%E5%AD%90%E8%BF%99%E4%B9%88%E5%A4%A7%23) `250.4K 🔥` `+117%`
1. [四月不能叫四月](https://s.weibo.com/weibo?q=%23%E5%9B%9B%E6%9C%88%E4%B8%8D%E8%83%BD%E5%8F%AB%E5%9B%9B%E6%9C%88%23) `116.6K 🔥` `+22%`
1. [属于中国人的清明仪式感](https://s.weibo.com/weibo?q=%23%E5%B1%9E%E4%BA%8E%E4%B8%AD%E5%9B%BD%E4%BA%BA%E7%9A%84%E6%B8%85%E6%98%8E%E4%BB%AA%E5%BC%8F%E6%84%9F%23) `600.3K 🔥`
1. [因为自制力差一下午赚了七千](https://s.weibo.com/weibo?q=%23%E5%9B%A0%E4%B8%BA%E8%87%AA%E5%88%B6%E5%8A%9B%E5%B7%AE%E4%B8%80%E4%B8%8B%E5%8D%88%E8%B5%9A%E4%BA%86%E4%B8%83%E5%8D%83%23) `133.1K 🔥`
1. [王传君给陈赫送的花篮上叫他贤哥](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BC%A0%E5%90%9B%E7%BB%99%E9%99%88%E8%B5%AB%E9%80%81%E7%9A%84%E8%8A%B1%E7%AF%AE%E4%B8%8A%E5%8F%AB%E4%BB%96%E8%B4%A4%E5%93%A5%23) `127.0K 🔥`
1. [唐艺昕因皮肤原因4年未拍戏 (Tang Yixin stopped filming for 4 years due to skin reasons)](https://s.weibo.com/weibo?q=%23%E5%94%90%E8%89%BA%E6%98%95%E5%9B%A0%E7%9A%AE%E8%82%A4%E5%8E%9F%E5%9B%A04%E5%B9%B4%E6%9C%AA%E6%8B%8D%E6%88%8F%23) `119.3K 🔥`
1. [南京被害女大学生父亲现状](https://s.weibo.com/weibo?q=%23%E5%8D%97%E4%BA%AC%E8%A2%AB%E5%AE%B3%E5%A5%B3%E5%A4%A7%E5%AD%A6%E7%94%9F%E7%88%B6%E4%BA%B2%E7%8E%B0%E7%8A%B6%23) `113.9K 🔥`
1. [月鳞绮纪疑似不足1广](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E7%96%91%E4%BC%BC%E4%B8%8D%E8%B6%B31%E5%B9%BF%23) `112.0K 🔥`
1. [何宣林是孟子义的大学班主任](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%AE%A3%E6%9E%97%E6%98%AF%E5%AD%9F%E5%AD%90%E4%B9%89%E7%9A%84%E5%A4%A7%E5%AD%A6%E7%8F%AD%E4%B8%BB%E4%BB%BB%23) `108.6K 🔥`
1. [张若昀发唐艺昕直拍 (Zhang Ruoyun sends Tang Yixin to shoot directly)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%8B%A5%E6%98%80%E5%8F%91%E5%94%90%E8%89%BA%E6%98%95%E7%9B%B4%E6%8B%8D%23) `104.0K 🔥`
1. [午睡时间超1小时死亡风险增加30%](https://s.weibo.com/weibo?q=%23%E5%8D%88%E7%9D%A1%E6%97%B6%E9%97%B4%E8%B6%851%E5%B0%8F%E6%97%B6%E6%AD%BB%E4%BA%A1%E9%A3%8E%E9%99%A9%E5%A2%9E%E5%8A%A030%25%23) `103.4K 🔥`
1. [孔令奇再办婚礼 (Kong Lingqi holds another wedding)](https://s.weibo.com/weibo?q=%23%E5%AD%94%E4%BB%A4%E5%A5%87%E5%86%8D%E5%8A%9E%E5%A9%9A%E7%A4%BC%23) `97.8K 🔥`
1. [94岁爷爷吃饭神似年迈的兔子 (94-year-old grandpa looks like an old rabbit when he eats)](https://s.weibo.com/weibo?q=%2394%E5%B2%81%E7%88%B7%E7%88%B7%E5%90%83%E9%A5%AD%E7%A5%9E%E4%BC%BC%E5%B9%B4%E8%BF%88%E7%9A%84%E5%85%94%E5%AD%90%23) `97.8K 🔥`
1. [女生午睡5小时被领导警告发视频哭诉 (A girl was warned by her boss after taking a 5-hour nap and posted a video crying.)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E5%8D%88%E7%9D%A15%E5%B0%8F%E6%97%B6%E8%A2%AB%E9%A2%86%E5%AF%BC%E8%AD%A6%E5%91%8A%E5%8F%91%E8%A7%86%E9%A2%91%E5%93%AD%E8%AF%89%23) `89.9K 🔥`
1. [美国教师为性侵学生与其母亲交往](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%95%99%E5%B8%88%E4%B8%BA%E6%80%A7%E4%BE%B5%E5%AD%A6%E7%94%9F%E4%B8%8E%E5%85%B6%E6%AF%8D%E4%BA%B2%E4%BA%A4%E5%BE%80%23) `71.5K 🔥`
1. [华裔女子西安刚下飞机就被历史暴击 (A Chinese woman was struck by history as soon as she got off the plane in Xi'an)](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E8%A3%94%E5%A5%B3%E5%AD%90%E8%A5%BF%E5%AE%89%E5%88%9A%E4%B8%8B%E9%A3%9E%E6%9C%BA%E5%B0%B1%E8%A2%AB%E5%8E%86%E5%8F%B2%E6%9A%B4%E5%87%BB%23) `173.4K 🔥` `-83%`
1. [美军2架黑鹰直升机被伊朗击中 (Two U.S. Black Hawk helicopters were shot down by Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B2%E6%9E%B6%E9%BB%91%E9%B9%B0%E7%9B%B4%E5%8D%87%E6%9C%BA%E8%A2%AB%E4%BC%8A%E6%9C%97%E5%87%BB%E4%B8%AD%23) `119.6K 🔥` `-44%`
1. [阿娇首部短剧](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%A8%87%E9%A6%96%E9%83%A8%E7%9F%AD%E5%89%A7%23) `97.1K 🔥` `-57%`
1. [入伍2年返校发现专业没了](https://s.weibo.com/weibo?q=%23%E5%85%A5%E4%BC%8D2%E5%B9%B4%E8%BF%94%E6%A0%A1%E5%8F%91%E7%8E%B0%E4%B8%93%E4%B8%9A%E6%B2%A1%E4%BA%86%23) `95.8K 🔥` `-38%`
1. [阚清子说很感谢倪萍](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E8%AF%B4%E5%BE%88%E6%84%9F%E8%B0%A2%E5%80%AA%E8%90%8D%23) `90.1K 🔥` `-21%`
1. [吴世勋solo单曲MV](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%B8%96%E5%8B%8Bsolo%E5%8D%95%E6%9B%B2MV%23) `86.1K 🔥` `-27%`
1. [优思益](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `84.9K 🔥` `-28%`
1. [钟辰乐泡泡](https://s.weibo.com/weibo?q=%23%E9%92%9F%E8%BE%B0%E4%B9%90%E6%B3%A1%E6%B3%A1%23) `79.2K 🔥` `-27%`
1. [王艺迪0比4温特](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%89%BA%E8%BF%AA0%E6%AF%944%E6%B8%A9%E7%89%B9%23) `75.7K 🔥` `-90%`
1. [19岁少女柬埔寨失联事件迎反转](https://s.weibo.com/weibo?q=%2319%E5%B2%81%E5%B0%91%E5%A5%B3%E6%9F%AC%E5%9F%94%E5%AF%A8%E5%A4%B1%E8%81%94%E4%BA%8B%E4%BB%B6%E8%BF%8E%E5%8F%8D%E8%BD%AC%23) `70.9K 🔥` `-38%`
1. [塞车把周杰伦女儿急坏了 (The traffic jam made Jay Chou's daughter very anxious)](https://s.weibo.com/weibo?q=%23%E5%A1%9E%E8%BD%A6%E6%8A%8A%E5%91%A8%E6%9D%B0%E4%BC%A6%E5%A5%B3%E5%84%BF%E6%80%A5%E5%9D%8F%E4%BA%86%23) `70.7K 🔥` `-38%`
1. [张凌赫是在致敬罗晋给唐嫣拿糖吗](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%98%AF%E5%9C%A8%E8%87%B4%E6%95%AC%E7%BD%97%E6%99%8B%E7%BB%99%E5%94%90%E5%AB%A3%E6%8B%BF%E7%B3%96%E5%90%97%23) `68.4K 🔥` `-24%`
1. [五哈](https://s.weibo.com/weibo?q=%23%E4%BA%94%E5%93%88%23) `63.0K 🔥` `-26%`
1. [终于知道销冠为什么是销冠了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E7%9F%A5%E9%81%93%E9%94%80%E5%86%A0%E4%B8%BA%E4%BB%80%E4%B9%88%E6%98%AF%E9%94%80%E5%86%A0%E4%BA%86%23) `57.6K 🔥` `-72%`

Updated at 2026-04-04 13:42:56

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
