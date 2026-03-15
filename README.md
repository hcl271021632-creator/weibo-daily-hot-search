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

1. [私域营销5倍暴利围猎老人 (Private domain marketing 5 times huge profits to hunt the elderly)](https://s.weibo.com/weibo?q=%23%E7%A7%81%E5%9F%9F%E8%90%A5%E9%94%805%E5%80%8D%E6%9A%B4%E5%88%A9%E5%9B%B4%E7%8C%8E%E8%80%81%E4%BA%BA%23) `496.2K 🔥` `NEW`
1. [重庆市监局通报漂白鸡爪](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E5%B8%82%E7%9B%91%E5%B1%80%E9%80%9A%E6%8A%A5%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%23) `250.2K 🔥` `NEW`
1. [等风热吻你看到了网友的呼吁](https://s.weibo.com/weibo?q=%23%E7%AD%89%E9%A3%8E%E7%83%AD%E5%90%BB%E4%BD%A0%E7%9C%8B%E5%88%B0%E4%BA%86%E7%BD%91%E5%8F%8B%E7%9A%84%E5%91%BC%E5%90%81%23) `203.7K 🔥` `NEW`
1. [内科医师一上网成了眼科专家](https://s.weibo.com/weibo?q=%23%E5%86%85%E7%A7%91%E5%8C%BB%E5%B8%88%E4%B8%80%E4%B8%8A%E7%BD%91%E6%88%90%E4%BA%86%E7%9C%BC%E7%A7%91%E4%B8%93%E5%AE%B6%23) `203.4K 🔥` `NEW`
1. [民警抓捕逃犯时牺牲2嫌犯畏罪自杀](https://s.weibo.com/weibo?q=%23%E6%B0%91%E8%AD%A6%E6%8A%93%E6%8D%95%E9%80%83%E7%8A%AF%E6%97%B6%E7%89%BA%E7%89%B22%E5%AB%8C%E7%8A%AF%E7%95%8F%E7%BD%AA%E8%87%AA%E6%9D%80%23) `168.2K 🔥` `NEW`
1. [黄子弘凡直播](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E5%BC%98%E5%87%A1%E7%9B%B4%E6%92%AD%23) `159.8K 🔥` `NEW`
1. [医用级卫生巾](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%A8%E7%BA%A7%E5%8D%AB%E7%94%9F%E5%B7%BE%23) `157.6K 🔥` `NEW`
1. [刘宇宁杭州演唱会](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E6%9D%AD%E5%B7%9E%E6%BC%94%E5%94%B1%E4%BC%9A%23) `149.8K 🔥` `NEW`
1. [云南三角梅开成了五彩花瀑](https://s.weibo.com/weibo?q=%23%E4%BA%91%E5%8D%97%E4%B8%89%E8%A7%92%E6%A2%85%E5%BC%80%E6%88%90%E4%BA%86%E4%BA%94%E5%BD%A9%E8%8A%B1%E7%80%91%23) `108.8K 🔥` `NEW`
1. [田曦薇逐玉戏份](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E9%80%90%E7%8E%89%E6%88%8F%E4%BB%BD%23) `107.8K 🔥` `NEW`
1. [ZB1一个一个退场 (ZB1 exits one by one)](https://s.weibo.com/weibo?q=%23ZB1%E4%B8%80%E4%B8%AA%E4%B8%80%E4%B8%AA%E9%80%80%E5%9C%BA%23) `107.7K 🔥` `NEW`
1. [邱贻可找孙颖莎聊天](https://s.weibo.com/weibo?q=%23%E9%82%B1%E8%B4%BB%E5%8F%AF%E6%89%BE%E5%AD%99%E9%A2%96%E8%8E%8E%E8%81%8A%E5%A4%A9%23) `105.2K 🔥` `NEW`
1. [LGD第四周周冠军](https://s.weibo.com/weibo?q=%23LGD%E7%AC%AC%E5%9B%9B%E5%91%A8%E5%91%A8%E5%86%A0%E5%86%9B%23) `103.1K 🔥` `NEW`
1. [315名单 (315 list)](https://s.weibo.com/weibo?q=%23315%E5%90%8D%E5%8D%95%23) `10.5M 🔥` `+136%`
1. [京东邀你抵制假测评 举报领黄金 (JD.com invites you to boycott fake reviews, report them and get gold)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E9%82%80%E4%BD%A0%E6%8A%B5%E5%88%B6%E5%81%87%E6%B5%8B%E8%AF%84%20%E4%B8%BE%E6%8A%A5%E9%A2%86%E9%BB%84%E9%87%91%23) `1.7M 🔥` `+151%`
1. [有友鸡爪](https://s.weibo.com/weibo?q=%23%E6%9C%89%E5%8F%8B%E9%B8%A1%E7%88%AA%23) `1.4M 🔥` `+115%`
1. [原来电商图是这样生成的](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E7%94%B5%E5%95%86%E5%9B%BE%E6%98%AF%E8%BF%99%E6%A0%B7%E7%94%9F%E6%88%90%E7%9A%84%23) `498.4K 🔥` `+101%`
1. [刘宇宁在最猛的年纪又野又欲](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%9C%A8%E6%9C%80%E7%8C%9B%E7%9A%84%E5%B9%B4%E7%BA%AA%E5%8F%88%E9%87%8E%E5%8F%88%E6%AC%B2%23) `199.7K 🔥` `+57%`
1. [网警提醒看不见的虚假更要防](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%AD%A6%E6%8F%90%E9%86%92%E7%9C%8B%E4%B8%8D%E8%A7%81%E7%9A%84%E8%99%9A%E5%81%87%E6%9B%B4%E8%A6%81%E9%98%B2%23) `1.8M 🔥`
1. [配眼镜 暴利 (Glasses, huge profits)](https://s.weibo.com/weibo?q=%23%E9%85%8D%E7%9C%BC%E9%95%9C%20%E6%9A%B4%E5%88%A9%23) `366.4K 🔥`
1. [樊长玉知道谢征的身份了 (Fan Changyu knows Xie Zheng’s identity)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E7%9F%A5%E9%81%93%E8%B0%A2%E5%BE%81%E7%9A%84%E8%BA%AB%E4%BB%BD%E4%BA%86%23) `203.4K 🔥`
1. [9岁男孩17楼坠亡生母质疑死因不明](https://s.weibo.com/weibo?q=%239%E5%B2%81%E7%94%B7%E5%AD%A917%E6%A5%BC%E5%9D%A0%E4%BA%A1%E7%94%9F%E6%AF%8D%E8%B4%A8%E7%96%91%E6%AD%BB%E5%9B%A0%E4%B8%8D%E6%98%8E%23) `121.8K 🔥`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `121.2K 🔥`
1. [樊振东vs沃尔瑟](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9Cvs%E6%B2%83%E5%B0%94%E7%91%9F%23) `107.7K 🔥`
1. [315晚会 (315 party)](https://s.weibo.com/weibo?q=%23315%E6%99%9A%E4%BC%9A%23) `2.2M 🔥` `-77%`
1. [给AI投毒](https://s.weibo.com/weibo?q=%23%E7%BB%99AI%E6%8A%95%E6%AF%92%23) `1.3M 🔥` `-27%`
1. [周小闹回应刘文祥塌房 (Zhou Xiaonao responded to Liu Wenxiang’s house collapse)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%B0%8F%E9%97%B9%E5%9B%9E%E5%BA%94%E5%88%98%E6%96%87%E7%A5%A5%E5%A1%8C%E6%88%BF%23) `809.3K 🔥` `-29%`
1. [双氧水鸡爪 (Hydrogen peroxide chicken feet)](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E6%B0%A7%E6%B0%B4%E9%B8%A1%E7%88%AA%23) `507.4K 🔥` `-68%`
1. [未来5年民生保障再加力 (More efforts will be made to ensure people’s livelihood in the next five years)](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A55%E5%B9%B4%E6%B0%91%E7%94%9F%E4%BF%9D%E9%9A%9C%E5%86%8D%E5%8A%A0%E5%8A%9B%23) `496.1K 🔥` `-26%`
1. [吴佳妮自曝婚内没收入很没尊严](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%B3%E5%A6%AE%E8%87%AA%E6%9B%9D%E5%A9%9A%E5%86%85%E6%B2%A1%E6%94%B6%E5%85%A5%E5%BE%88%E6%B2%A1%E5%B0%8A%E4%B8%A5%23) `495.9K 🔥` `-42%`
1. [爱吃毛肚的人天塌了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E6%AF%9B%E8%82%9A%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `467.1K 🔥` `-59%`
1. [紫薯精天塌了 (Purple Sweet Potato Essence The sky is falling)](https://s.weibo.com/weibo?q=%23%E7%B4%AB%E8%96%AF%E7%B2%BE%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `426.5K 🔥` `-45%`
1. [医美骗局](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%BE%8E%E9%AA%97%E5%B1%80%23) `393.3K 🔥` `-41%`
1. [乖媳妇鸡爪 (Good Wife Chicken Feet)](https://s.weibo.com/weibo?q=%23%E4%B9%96%E5%AA%B3%E5%A6%87%E9%B8%A1%E7%88%AA%23) `308.4K 🔥` `-39%`
1. [315记者为暗访一个月抽血十几次 (315 reporter draws blood more than ten times a month for undercover investigation)](https://s.weibo.com/weibo?q=%23315%E8%AE%B0%E8%80%85%E4%B8%BA%E6%9A%97%E8%AE%BF%E4%B8%80%E4%B8%AA%E6%9C%88%E6%8A%BD%E8%A1%80%E5%8D%81%E5%87%A0%E6%AC%A1%23) `280.6K 🔥` `-48%`
1. [网红西梅汁实则暗藏强效泻药](https://s.weibo.com/weibo?q=%23%E7%BD%91%E7%BA%A2%E8%A5%BF%E6%A2%85%E6%B1%81%E5%AE%9E%E5%88%99%E6%9A%97%E8%97%8F%E5%BC%BA%E6%95%88%E6%B3%BB%E8%8D%AF%23) `257.7K 🔥` `-42%`
1. [老师标配的小蜜蜂该用还是该禁](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%B8%88%E6%A0%87%E9%85%8D%E7%9A%84%E5%B0%8F%E8%9C%9C%E8%9C%82%E8%AF%A5%E7%94%A8%E8%BF%98%E6%98%AF%E8%AF%A5%E7%A6%81%23) `249.6K 🔥` `-23%`
1. [多品牌回应鸡爪安全](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%93%81%E7%89%8C%E5%9B%9E%E5%BA%94%E9%B8%A1%E7%88%AA%E5%AE%89%E5%85%A8%23) `200.6K 🔥` `-59%`
1. [315](https://s.weibo.com/weibo?q=%23315%23) `194.7K 🔥` `-44%`
1. [外泌体 (exosomes)](https://s.weibo.com/weibo?q=%23%E5%A4%96%E6%B3%8C%E4%BD%93%23) `186.9K 🔥` `-36%`
1. [哈啰电动车超速](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%95%B0%E7%94%B5%E5%8A%A8%E8%BD%A6%E8%B6%85%E9%80%9F%23) `180.6K 🔥` `-63%`
1. [刘文祥麻辣烫多处不合规](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E5%A4%9A%E5%A4%84%E4%B8%8D%E5%90%88%E8%A7%84%23) `169.1K 🔥` `-28%`
1. [胖东来要求博主删除视频 (Fat Donglai asked the blogger to delete the video)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E8%A6%81%E6%B1%82%E5%8D%9A%E4%B8%BB%E5%88%A0%E9%99%A4%E8%A7%86%E9%A2%91%23) `165.4K 🔥` `-24%`
1. [刘文祥 纯素菜](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%20%E7%BA%AF%E7%B4%A0%E8%8F%9C%23) `141.1K 🔥` `-35%`
1. [温瑞博亚军 (Wen Ruibo runner-up)](https://s.weibo.com/weibo?q=%23%E6%B8%A9%E7%91%9E%E5%8D%9A%E4%BA%9A%E5%86%9B%23) `135.1K 🔥` `-86%`
1. [黄天鹅](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%A4%A9%E9%B9%85%23) `132.5K 🔥` `-27%`
1. [为什么大学里的男生比例越来越少 (Why are there fewer and fewer men in college?)](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E5%A4%A7%E5%AD%A6%E9%87%8C%E7%9A%84%E7%94%B7%E7%94%9F%E6%AF%94%E4%BE%8B%E8%B6%8A%E6%9D%A5%E8%B6%8A%E5%B0%91%23) `128.5K 🔥` `-26%`
1. [王楚钦噘嘴鼓掌](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%99%98%E5%98%B4%E9%BC%93%E6%8E%8C%23) `118.2K 🔥` `-39%`
1. [315晚会曝光AI大模型被投毒](https://s.weibo.com/weibo?q=%23315%E6%99%9A%E4%BC%9A%E6%9B%9D%E5%85%89AI%E5%A4%A7%E6%A8%A1%E5%9E%8B%E8%A2%AB%E6%8A%95%E6%AF%92%23) `113.6K 🔥` `-87%`
1. [黄子弘凡新歌](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E5%BC%98%E5%87%A1%E6%96%B0%E6%AD%8C%23) `110.1K 🔥` `-36%`

Updated at 2026-03-15 22:37:43

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
