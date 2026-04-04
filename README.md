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

1. [美军2架黑鹰直升机被伊朗击中 (Two U.S. Black Hawk helicopters were shot down by Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B2%E6%9E%B6%E9%BB%91%E9%B9%B0%E7%9B%B4%E5%8D%87%E6%9C%BA%E8%A2%AB%E4%BC%8A%E6%9C%97%E5%87%BB%E4%B8%AD%23) `572.3K 🔥` `NEW`
1. [金典和浪姐分手了](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%85%B8%E5%92%8C%E6%B5%AA%E5%A7%90%E5%88%86%E6%89%8B%E4%BA%86%23) `558.3K 🔥` `NEW`
1. [阚清子说很感谢倪萍](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E8%AF%B4%E5%BE%88%E6%84%9F%E8%B0%A2%E5%80%AA%E8%90%8D%23) `536.0K 🔥` `NEW`
1. [带师生徒步祭英烈校领导步数76000](https://s.weibo.com/weibo?q=%23%E5%B8%A6%E5%B8%88%E7%94%9F%E5%BE%92%E6%AD%A5%E7%A5%AD%E8%8B%B1%E7%83%88%E6%A0%A1%E9%A2%86%E5%AF%BC%E6%AD%A5%E6%95%B076000%23) `515.4K 🔥` `NEW`
1. [齐思钧在谢娜旁边承担了何炅功能](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%80%9D%E9%92%A7%E5%9C%A8%E8%B0%A2%E5%A8%9C%E6%97%81%E8%BE%B9%E6%89%BF%E6%8B%85%E4%BA%86%E4%BD%95%E7%82%85%E5%8A%9F%E8%83%BD%23) `490.5K 🔥` `NEW`
1. [何宣林是北影表演系班主任](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%AE%A3%E6%9E%97%E6%98%AF%E5%8C%97%E5%BD%B1%E8%A1%A8%E6%BC%94%E7%B3%BB%E7%8F%AD%E4%B8%BB%E4%BB%BB%23) `226.6K 🔥` `NEW`
1. [美国教师为性侵学生与其母亲交往](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%95%99%E5%B8%88%E4%B8%BA%E6%80%A7%E4%BE%B5%E5%AD%A6%E7%94%9F%E4%B8%8E%E5%85%B6%E6%AF%8D%E4%BA%B2%E4%BA%A4%E5%BE%80%23) `196.0K 🔥` `NEW`
1. [海南一沙滩现巨型搁浅皇带鱼](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E5%8D%97%E4%B8%80%E6%B2%99%E6%BB%A9%E7%8E%B0%E5%B7%A8%E5%9E%8B%E6%90%81%E6%B5%85%E7%9A%87%E5%B8%A6%E9%B1%BC%23) `179.6K 🔥` `NEW`
1. [范闲 你也给祺贵人打电话吗](https://s.weibo.com/weibo?q=%23%E8%8C%83%E9%97%B2%20%E4%BD%A0%E4%B9%9F%E7%BB%99%E7%A5%BA%E8%B4%B5%E4%BA%BA%E6%89%93%E7%94%B5%E8%AF%9D%E5%90%97%23) `138.4K 🔥` `NEW`
1. [李煜东高会](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%85%9C%E4%B8%9C%E9%AB%98%E4%BC%9A%23) `135.2K 🔥` `NEW`
1. [冰箱里的冻肉超过这个时间直接扔 (If the frozen meat in the refrigerator exceeds this time, throw it away directly)](https://s.weibo.com/weibo?q=%23%E5%86%B0%E7%AE%B1%E9%87%8C%E7%9A%84%E5%86%BB%E8%82%89%E8%B6%85%E8%BF%87%E8%BF%99%E4%B8%AA%E6%97%B6%E9%97%B4%E7%9B%B4%E6%8E%A5%E6%89%94%23) `132.5K 🔥` `NEW`
1. [塞车把周杰伦女儿急坏了](https://s.weibo.com/weibo?q=%23%E5%A1%9E%E8%BD%A6%E6%8A%8A%E5%91%A8%E6%9D%B0%E4%BC%A6%E5%A5%B3%E5%84%BF%E6%80%A5%E5%9D%8F%E4%BA%86%23) `130.0K 🔥` `NEW`
1. [东契奇无限期休战](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E5%A5%91%E5%A5%87%E6%97%A0%E9%99%90%E6%9C%9F%E4%BC%91%E6%88%98%23) `126.9K 🔥` `NEW`
1. [特朗普非常生气](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E9%9D%9E%E5%B8%B8%E7%94%9F%E6%B0%94%23) `120.6K 🔥` `NEW`
1. [孙俪新剧就这样官宣了](https://s.weibo.com/weibo?q=%23%E5%AD%99%E4%BF%AA%E6%96%B0%E5%89%A7%E5%B0%B1%E8%BF%99%E6%A0%B7%E5%AE%98%E5%AE%A3%E4%BA%86%23) `119.2K 🔥` `NEW`
1. [伊媒称美提议停火48小时](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E5%AA%92%E7%A7%B0%E7%BE%8E%E6%8F%90%E8%AE%AE%E5%81%9C%E7%81%AB48%E5%B0%8F%E6%97%B6%23) `113.0K 🔥` `NEW`
1. [张凌赫是在致敬罗晋给唐嫣拿糖吗](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%98%AF%E5%9C%A8%E8%87%B4%E6%95%AC%E7%BD%97%E6%99%8B%E7%BB%99%E5%94%90%E5%AB%A3%E6%8B%BF%E7%B3%96%E5%90%97%23) `112.4K 🔥` `NEW`
1. [清明前一天出发的大聪明堵在高速上](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%89%8D%E4%B8%80%E5%A4%A9%E5%87%BA%E5%8F%91%E7%9A%84%E5%A4%A7%E8%81%AA%E6%98%8E%E5%A0%B5%E5%9C%A8%E9%AB%98%E9%80%9F%E4%B8%8A%23) `112.2K 🔥` `NEW`
1. [40岁男子AI成瘾无法接受版本更新](https://s.weibo.com/weibo?q=%2340%E5%B2%81%E7%94%B7%E5%AD%90AI%E6%88%90%E7%98%BE%E6%97%A0%E6%B3%95%E6%8E%A5%E5%8F%97%E7%89%88%E6%9C%AC%E6%9B%B4%E6%96%B0%23) `112.0K 🔥` `NEW`
1. [市委书记随行学生徒步祭英烈](https://s.weibo.com/weibo?q=%23%E5%B8%82%E5%A7%94%E4%B9%A6%E8%AE%B0%E9%9A%8F%E8%A1%8C%E5%AD%A6%E7%94%9F%E5%BE%92%E6%AD%A5%E7%A5%AD%E8%8B%B1%E7%83%88%23) `111.9K 🔥` `NEW`
1. [东契奇将申请破例参与奖项评选 (Doncic will apply for an exception to participate in the award selection)](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E5%A5%91%E5%A5%87%E5%B0%86%E7%94%B3%E8%AF%B7%E7%A0%B4%E4%BE%8B%E5%8F%82%E4%B8%8E%E5%A5%96%E9%A1%B9%E8%AF%84%E9%80%89%23) `111.7K 🔥` `NEW`
1. [在北京赶飞机不用提前两小时傻等了](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%8C%97%E4%BA%AC%E8%B5%B6%E9%A3%9E%E6%9C%BA%E4%B8%8D%E7%94%A8%E6%8F%90%E5%89%8D%E4%B8%A4%E5%B0%8F%E6%97%B6%E5%82%BB%E7%AD%89%E4%BA%86%23) `111.5K 🔥` `NEW`
1. [洛阳牡丹花太美了](https://s.weibo.com/weibo?q=%23%E6%B4%9B%E9%98%B3%E7%89%A1%E4%B8%B9%E8%8A%B1%E5%A4%AA%E7%BE%8E%E4%BA%86%23) `111.4K 🔥` `NEW`
1. [伊朗称12小时击落两架美军战机](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B012%E5%B0%8F%E6%97%B6%E5%87%BB%E8%90%BD%E4%B8%A4%E6%9E%B6%E7%BE%8E%E5%86%9B%E6%88%98%E6%9C%BA%23) `111.1K 🔥` `NEW`
1. [最强大脑13双脑王](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BC%BA%E5%A4%A7%E8%84%9113%E5%8F%8C%E8%84%91%E7%8E%8B%23) `111.0K 🔥` `NEW`
1. [好多人装修没有去家务化的意识](https://s.weibo.com/weibo?q=%23%E5%A5%BD%E5%A4%9A%E4%BA%BA%E8%A3%85%E4%BF%AE%E6%B2%A1%E6%9C%89%E5%8E%BB%E5%AE%B6%E5%8A%A1%E5%8C%96%E7%9A%84%E6%84%8F%E8%AF%86%23) `518.9K 🔥` `+68%`
1. [王楚钦直言0比2落后真没机会 (Wang Chuqin bluntly said that he really had no chance after falling behind 0-2.)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E7%9B%B4%E8%A8%800%E6%AF%942%E8%90%BD%E5%90%8E%E7%9C%9F%E6%B2%A1%E6%9C%BA%E4%BC%9A%23) `466.0K 🔥` `+253%`
1. [唐艺昕因皮肤原因4年未拍戏 (Tang Yixin stopped filming for 4 years due to skin reasons)](https://s.weibo.com/weibo?q=%23%E5%94%90%E8%89%BA%E6%98%95%E5%9B%A0%E7%9A%AE%E8%82%A4%E5%8E%9F%E5%9B%A04%E5%B9%B4%E6%9C%AA%E6%8B%8D%E6%88%8F%23) `463.7K 🔥` `+251%`
1. [伊朗被曝实施打了就跑战术](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AB%E6%9B%9D%E5%AE%9E%E6%96%BD%E6%89%93%E4%BA%86%E5%B0%B1%E8%B7%91%E6%88%98%E6%9C%AF%23) `168.4K 🔥` `+34%`
1. [谁来救救代斯 (Who will save Dais?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%9D%A5%E6%95%91%E6%95%91%E4%BB%A3%E6%96%AF%23) `112.2K 🔥` `+71%`
1. [何宣林 黑马](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%AE%A3%E6%9E%97%20%E9%BB%91%E9%A9%AC%23) `111.8K 🔥` `+22%`
1. [发现小猫长牙齿之后天天都要看](https://s.weibo.com/weibo?q=%23%E5%8F%91%E7%8E%B0%E5%B0%8F%E7%8C%AB%E9%95%BF%E7%89%99%E9%BD%BF%E4%B9%8B%E5%90%8E%E5%A4%A9%E5%A4%A9%E9%83%BD%E8%A6%81%E7%9C%8B%23) `111.6K 🔥` `+43%`
1. [张凌赫早期颜值](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%97%A9%E6%9C%9F%E9%A2%9C%E5%80%BC%23) `111.2K 🔥` `+129%`
1. [马兴瑞涉嫌严重违纪违法 (Ma Xingrui is suspected of serious violations of discipline and law)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%85%B4%E7%91%9E%E6%B6%89%E5%AB%8C%E4%B8%A5%E9%87%8D%E8%BF%9D%E7%BA%AA%E8%BF%9D%E6%B3%95%23) `111.0K 🔥` `+68%`
1. [女演员三平台破万剧盘点 (List of actresses who have broken through 10,000 dramas on three platforms)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E6%BC%94%E5%91%98%E4%B8%89%E5%B9%B3%E5%8F%B0%E7%A0%B4%E4%B8%87%E5%89%A7%E7%9B%98%E7%82%B9%23) `110.9K 🔥` `+95%`
1. [与辉同行宣布全额退款 (Hehui Peer announces full refund)](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E8%BE%89%E5%90%8C%E8%A1%8C%E5%AE%A3%E5%B8%83%E5%85%A8%E9%A2%9D%E9%80%80%E6%AC%BE%23) `1.0M 🔥`
1. [优思益称无力售后 (Yousiyi says it is unable to provide after-sales service)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E7%A7%B0%E6%97%A0%E5%8A%9B%E5%94%AE%E5%90%8E%23) `742.0K 🔥`
1. [赏花踏青特色主题专列来了 (Special themed train for flower viewing and outing is here)](https://s.weibo.com/weibo?q=%23%E8%B5%8F%E8%8A%B1%E8%B8%8F%E9%9D%92%E7%89%B9%E8%89%B2%E4%B8%BB%E9%A2%98%E4%B8%93%E5%88%97%E6%9D%A5%E4%BA%86%23) `588.8K 🔥`
1. [浪姐排名 (Sister Lang ranking)](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E6%8E%92%E5%90%8D%23) `154.8K 🔥`
1. [张若昀发唐艺昕直拍 (Zhang Ruoyun sends Tang Yixin to shoot directly)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%8B%A5%E6%98%80%E5%8F%91%E5%94%90%E8%89%BA%E6%98%95%E7%9B%B4%E6%8B%8D%23) `133.6K 🔥`
1. [黄灿灿表情](https://s.weibo.com/weibo?q=%23%E9%BB%84%E7%81%BF%E7%81%BF%E8%A1%A8%E6%83%85%23) `124.3K 🔥`
1. [有结节的人要在春天做4件事](https://s.weibo.com/weibo?q=%23%E6%9C%89%E7%BB%93%E8%8A%82%E7%9A%84%E4%BA%BA%E8%A6%81%E5%9C%A8%E6%98%A5%E5%A4%A9%E5%81%9A4%E4%BB%B6%E4%BA%8B%23) `112.4K 🔥`
1. [三甲医院医生建议重病有三不治](https://s.weibo.com/weibo?q=%23%E4%B8%89%E7%94%B2%E5%8C%BB%E9%99%A2%E5%8C%BB%E7%94%9F%E5%BB%BA%E8%AE%AE%E9%87%8D%E7%97%85%E6%9C%89%E4%B8%89%E4%B8%8D%E6%B2%BB%23) `112.0K 🔥`
1. [浪姐改赛制](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E6%94%B9%E8%B5%9B%E5%88%B6%23) `111.3K 🔥`
1. [男子拔掉祖坟旁槟榔苗被判刑 (Man sentenced for pulling out betel nut seedlings near ancestral grave)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E6%8B%94%E6%8E%89%E7%A5%96%E5%9D%9F%E6%97%81%E6%A7%9F%E6%A6%94%E8%8B%97%E8%A2%AB%E5%88%A4%E5%88%91%23) `231.9K 🔥` `-58%`
1. [工信部紧急提醒苹果用户](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%BF%A1%E9%83%A8%E7%B4%A7%E6%80%A5%E6%8F%90%E9%86%92%E8%8B%B9%E6%9E%9C%E7%94%A8%E6%88%B7%23) `136.2K 🔥` `-41%`
1. [倪萍真的给人看力竭了](https://s.weibo.com/weibo?q=%23%E5%80%AA%E8%90%8D%E7%9C%9F%E7%9A%84%E7%BB%99%E4%BA%BA%E7%9C%8B%E5%8A%9B%E7%AB%AD%E4%BA%86%23) `128.6K 🔥` `-74%`
1. [章小蕙让阚清子放下过去 (Zhang Xiaohui asked Kan Qingzi to let go of the past)](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%B0%8F%E8%95%99%E8%AE%A9%E9%98%9A%E6%B8%85%E5%AD%90%E6%94%BE%E4%B8%8B%E8%BF%87%E5%8E%BB%23) `121.9K 🔥` `-67%`
1. [女生午睡5小时被领导警告发视频哭诉 (A girl was warned by her boss after taking a 5-hour nap and posted a video crying.)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E5%8D%88%E7%9D%A15%E5%B0%8F%E6%97%B6%E8%A2%AB%E9%A2%86%E5%AF%BC%E8%AD%A6%E5%91%8A%E5%8F%91%E8%A7%86%E9%A2%91%E5%93%AD%E8%AF%89%23) `113.0K 🔥` `-49%`

Updated at 2026-04-04 10:37:13

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
