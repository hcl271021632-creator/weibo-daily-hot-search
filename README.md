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

1. [315晚会 (315 party)](https://s.weibo.com/weibo?q=%23315%E6%99%9A%E4%BC%9A%23) `1.6M 🔥` `NEW`
1. [电视剧品质盛典夯爆了](https://s.weibo.com/weibo?q=%23%E7%94%B5%E8%A7%86%E5%89%A7%E5%93%81%E8%B4%A8%E7%9B%9B%E5%85%B8%E5%A4%AF%E7%88%86%E4%BA%86%23) `570.5K 🔥` `NEW`
1. [蒯曼亚军](https://s.weibo.com/weibo?q=%23%E8%92%AF%E6%9B%BC%E4%BA%9A%E5%86%9B%23) `159.3K 🔥` `NEW`
1. [315记者为暗访一个月抽血十几次](https://s.weibo.com/weibo?q=%23315%E8%AE%B0%E8%80%85%E4%B8%BA%E6%9A%97%E8%AE%BF%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8A%BD%E8%A1%80%E5%8D%81%E5%87%A0%E6%AC%A1%23) `133.0K 🔥` `NEW`
1. [蒯曼3比4张本美和](https://s.weibo.com/weibo?q=%23%E8%92%AF%E6%9B%BC3%E6%AF%944%E5%BC%A0%E6%9C%AC%E7%BE%8E%E5%92%8C%23) `130.9K 🔥` `NEW`
1. [ZB1解散演唱会](https://s.weibo.com/weibo?q=%23ZB1%E8%A7%A3%E6%95%A3%E6%BC%94%E5%94%B1%E4%BC%9A%23) `119.3K 🔥` `NEW`
1. [广东查获美宜佳非法卷烟近140万支](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E6%9F%A5%E8%8E%B7%E7%BE%8E%E5%AE%9C%E4%BD%B3%E9%9D%9E%E6%B3%95%E5%8D%B7%E7%83%9F%E8%BF%91140%E4%B8%87%E6%94%AF%23) `98.7K 🔥` `NEW`
1. [周小闹回应刘文祥塌房 (Zhou Xiaonao responded to Liu Wenxiang’s house collapse)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%B0%8F%E9%97%B9%E5%9B%9E%E5%BA%94%E5%88%98%E6%96%87%E7%A5%A5%E5%A1%8C%E6%88%BF%23) `1.7M 🔥` `+192%`
1. [十五五这四类人群直接受益 (These four groups of people will directly benefit from the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%BF%99%E5%9B%9B%E7%B1%BB%E4%BA%BA%E7%BE%A4%E7%9B%B4%E6%8E%A5%E5%8F%97%E7%9B%8A%23) `1.5M 🔥` `+109%`
1. [美团外卖周末半价吃大餐 (Meituan Takeaway offers half-price meals on weekends)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%A2%E5%A4%96%E5%8D%96%E5%91%A8%E6%9C%AB%E5%8D%8A%E4%BB%B7%E5%90%83%E5%A4%A7%E9%A4%90%23) `1.5M 🔥` `+98%`
1. [蒯曼vs张本美和](https://s.weibo.com/weibo?q=%23%E8%92%AF%E6%9B%BCvs%E5%BC%A0%E6%9C%AC%E7%BE%8E%E5%92%8C%23) `756.0K 🔥` `+91%`
1. [315像是来审判我的](https://s.weibo.com/weibo?q=%23315%E5%83%8F%E6%98%AF%E6%9D%A5%E5%AE%A1%E5%88%A4%E6%88%91%E7%9A%84%23) `479.2K 🔥` `+191%`
1. [孙颖莎示意观众小声些](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E7%A4%BA%E6%84%8F%E8%A7%82%E4%BC%97%E5%B0%8F%E5%A3%B0%E4%BA%9B%23) `346.6K 🔥` `+75%`
1. [樊长玉知道谢征的身份了 (Fan Changyu knows Xie Zheng’s identity)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E7%9F%A5%E9%81%93%E8%B0%A2%E5%BE%81%E7%9A%84%E8%BA%AB%E4%BB%BD%E4%BA%86%23) `276.6K 🔥` `+120%`
1. [山姆有机冻干草莓已下架](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E6%9C%89%E6%9C%BA%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%E5%B7%B2%E4%B8%8B%E6%9E%B6%23) `274.6K 🔥` `+83%`
1. [以为是分手结果是索命](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%98%AF%E5%88%86%E6%89%8B%E7%BB%93%E6%9E%9C%E6%98%AF%E7%B4%A2%E5%91%BD%23) `138.9K 🔥` `+36%`
1. [孙颖莎观赛](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E8%A7%82%E8%B5%9B%23) `119.2K 🔥` `+29%`
1. [315](https://s.weibo.com/weibo?q=%23315%23) `1.4M 🔥`
1. [配眼镜 暴利 (Glasses, huge profits)](https://s.weibo.com/weibo?q=%23%E9%85%8D%E7%9C%BC%E9%95%9C%20%E6%9A%B4%E5%88%A9%23) `1.1M 🔥`
1. [刘文祥 纯素菜](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%20%E7%BA%AF%E7%B4%A0%E8%8F%9C%23) `384.8K 🔥`
1. [央视315晚会点名食品安全领域](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86315%E6%99%9A%E4%BC%9A%E7%82%B9%E5%90%8D%E9%A3%9F%E5%93%81%E5%AE%89%E5%85%A8%E9%A2%86%E5%9F%9F%23) `286.8K 🔥`
1. [为什么大学里的男生比例越来越少 (Why are there fewer and fewer men in college?)](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E5%A4%A7%E5%AD%A6%E9%87%8C%E7%9A%84%E7%94%B7%E7%94%9F%E6%AF%94%E4%BE%8B%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%B0%91%23) `263.7K 🔥`
1. [孙颖莎观战女单决赛](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E8%A7%82%E6%88%98%E5%A5%B3%E5%8D%95%E5%86%B3%E8%B5%9B%23) `224.9K 🔥`
1. [黄天鹅鸡蛋检出人工色素](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%A4%A9%E9%B9%85%E9%B8%A1%E8%9B%8B%E6%A3%80%E5%87%BA%E4%BA%BA%E5%B7%A5%E8%89%B2%E7%B4%A0%23) `195.7K 🔥`
1. [315记者为拍证据曾勇闯杀人蜂区](https://s.weibo.com/weibo?q=%23315%E8%AE%B0%E8%80%85%E4%B8%BA%E6%8B%8D%E8%AF%81%E6%8D%AE%E6%9B%BE%E5%8B%87%E9%97%AF%E6%9D%80%E4%BA%BA%E8%9C%82%E5%8C%BA%23) `191.6K 🔥`
1. [男制作人用吉赛尔未公开照片当头像](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%88%B6%E4%BD%9C%E4%BA%BA%E7%94%A8%E5%90%89%E8%B5%9B%E5%B0%94%E6%9C%AA%E5%85%AC%E5%BC%80%E7%85%A7%E7%89%87%E5%BD%93%E5%A4%B4%E5%83%8F%23) `156.9K 🔥`
1. [成毅 年龄 (Cheng Yi age)](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%20%E5%B9%B4%E9%BE%84%23) `156.9K 🔥`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `151.5K 🔥`
1. [蓝盈莹一出手就是浪姐水准 (Lan Yingying is at the level of Sister Lang as soon as she makes a move)](https://s.weibo.com/weibo?q=%23%E8%93%9D%E7%9B%88%E8%8E%B9%E4%B8%80%E5%87%BA%E6%89%8B%E5%B0%B1%E6%98%AF%E6%B5%AA%E5%A7%90%E6%B0%B4%E5%87%86%23) `147.2K 🔥`
1. [黄天鹅](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%A4%A9%E9%B9%85%23) `142.3K 🔥`
1. [逐玉开始单更了 (Zhuyu has started to update orders)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%80%E5%A7%8B%E5%8D%95%E6%9B%B4%E4%BA%86%23) `140.3K 🔥`
1. [刘文祥麻辣烫多处不合规](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E5%A4%9A%E5%A4%84%E4%B8%8D%E5%90%88%E8%A7%84%23) `131.4K 🔥`
1. [鹿哈曾自曝带货7个月赚了3500万](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E6%9B%BE%E8%87%AA%E6%9B%9D%E5%B8%A6%E8%B4%A77%E4%B8%AA%E6%9C%88%E8%B5%9A%E4%BA%863500%E4%B8%87%23) `130.4K 🔥`
1. [郝熠然直播](https://s.weibo.com/weibo?q=%23%E9%83%9D%E7%86%A0%E7%84%B6%E7%9B%B4%E6%92%AD%23) `126.3K 🔥`
1. [国色天香 何晟铭](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E8%89%B2%E5%A4%A9%E9%A6%99%20%E4%BD%95%E6%99%9F%E9%93%AD%23) `124.5K 🔥`
1. [9岁男孩17楼坠亡生母质疑死因不明](https://s.weibo.com/weibo?q=%239%E5%B2%81%E7%94%B7%E5%AD%A917%E6%A5%BC%E5%9D%A0%E4%BA%A1%E7%94%9F%E6%AF%8D%E8%B4%A8%E7%96%91%E6%AD%BB%E5%9B%A0%E4%B8%8D%E6%98%8E%23) `120.4K 🔥`
1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `120.3K 🔥`
1. [315押题大会](https://s.weibo.com/weibo?q=%23315%E6%8A%BC%E9%A2%98%E5%A4%A7%E4%BC%9A%23) `110.1K 🔥`
1. [张凌赫田曦薇没有杀青合照](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%B2%A1%E6%9C%89%E6%9D%80%E9%9D%92%E5%90%88%E7%85%A7%23) `108.4K 🔥`
1. [电视剧品质盛典 (TV Series Quality Ceremony)](https://s.weibo.com/weibo?q=%23%E7%94%B5%E8%A7%86%E5%89%A7%E5%93%81%E8%B4%A8%E7%9B%9B%E5%85%B8%23) `106.0K 🔥`
1. [仙逆](https://s.weibo.com/weibo?q=%23%E4%BB%99%E9%80%86%23) `105.7K 🔥`
1. [逐玉云合破50%](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%91%E5%90%88%E7%A0%B450%25%23) `105.7K 🔥`
1. [李煜东发文 (Li Yudong posted a message)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%85%9C%E4%B8%9C%E5%8F%91%E6%96%87%23) `102.3K 🔥`
1. [少吃水果就少生病吗](https://s.weibo.com/weibo?q=%23%E5%B0%91%E5%90%83%E6%B0%B4%E6%9E%9C%E5%B0%B1%E5%B0%91%E7%94%9F%E7%97%85%E5%90%97%23) `99.1K 🔥`
1. [女童穿新鞋3天后高低腿被客服嘲讽](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%AB%A5%E7%A9%BF%E6%96%B0%E9%9E%8B3%E5%A4%A9%E5%90%8E%E9%AB%98%E4%BD%8E%E8%85%BF%E8%A2%AB%E5%AE%A2%E6%9C%8D%E5%98%B2%E8%AE%BD%23) `98.3K 🔥`
1. [刘文祥刚爆火就塌房 (Liu Wenxiang's house collapsed just after the fire broke out)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E5%88%9A%E7%88%86%E7%81%AB%E5%B0%B1%E5%A1%8C%E6%88%BF%23) `88.1K 🔥`
1. [胖东来要求博主删除视频 (Fat Donglai asked the blogger to delete the video)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E8%A6%81%E6%B1%82%E5%8D%9A%E4%B8%BB%E5%88%A0%E9%99%A4%E8%A7%86%E9%A2%91%23) `428.4K 🔥` `-22%`
1. [紫薯精天塌了 (Purple Sweet Potato Essence The sky is falling)](https://s.weibo.com/weibo?q=%23%E7%B4%AB%E8%96%AF%E7%B2%BE%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `320.8K 🔥` `-51%`
1. [专家建议工作日缩至4天](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E5%BB%BA%E8%AE%AE%E5%B7%A5%E4%BD%9C%E6%97%A5%E7%BC%A9%E8%87%B34%E5%A4%A9%23) `157.0K 🔥` `-31%`
1. [iPhone长焦 出片](https://s.weibo.com/weibo?q=%23iPhone%E9%95%BF%E7%84%A6%20%E5%87%BA%E7%89%87%23) `156.6K 🔥` `-26%`
1. [林丹回应不让儿子学羽毛球](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%B8%B9%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E5%84%BF%E5%AD%90%E5%AD%A6%E7%BE%BD%E6%AF%9B%E7%90%83%23) `115.4K 🔥` `-24%`
1. [F1现场好多明星 (There are many stars in F1 scene)](https://s.weibo.com/weibo?q=%23F1%E7%8E%B0%E5%9C%BA%E5%A5%BD%E5%A4%9A%E6%98%8E%E6%98%9F%23) `101.1K 🔥` `-28%`

Updated at 2026-03-15 20:00:03

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
