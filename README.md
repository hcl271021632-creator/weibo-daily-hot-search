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

1. [魏牌V9X代言人魏建军首秀直播 (Wei brand V9X spokesperson Wei Jianjun’s first live broadcast)](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E7%89%8CV9X%E4%BB%A3%E8%A8%80%E4%BA%BA%E9%AD%8F%E5%BB%BA%E5%86%9B%E9%A6%96%E7%A7%80%E7%9B%B4%E6%92%AD%23) `567.7K 🔥` `NEW`
1. [何小鹏建议不要一毕业就创业](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%B0%8F%E9%B9%8F%E5%BB%BA%E8%AE%AE%E4%B8%8D%E8%A6%81%E4%B8%80%E6%AF%95%E4%B8%9A%E5%B0%B1%E5%88%9B%E4%B8%9A%23) `461.6K 🔥` `NEW`
1. [宋亚轩直播](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BA%9A%E8%BD%A9%E7%9B%B4%E6%92%AD%23) `461.5K 🔥` `NEW`
1. [一颗粘在厨房两年的QQ糖](https://s.weibo.com/weibo?q=%23%E4%B8%80%E9%A2%97%E7%B2%98%E5%9C%A8%E5%8E%A8%E6%88%BF%E4%B8%A4%E5%B9%B4%E7%9A%84QQ%E7%B3%96%23) `461.1K 🔥` `NEW`
1. [品质盛典后台直播](https://s.weibo.com/weibo?q=%23%E5%93%81%E8%B4%A8%E7%9B%9B%E5%85%B8%E5%90%8E%E5%8F%B0%E7%9B%B4%E6%92%AD%23) `460.9K 🔥` `NEW`
1. [广东名医欧阳卫权去世](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E5%90%8D%E5%8C%BB%E6%AC%A7%E9%98%B3%E5%8D%AB%E6%9D%83%E5%8E%BB%E4%B8%96%23) `460.6K 🔥` `NEW`
1. [青岛女子回应十几万黄金藏冰箱冷冻](https://s.weibo.com/weibo?q=%23%E9%9D%92%E5%B2%9B%E5%A5%B3%E5%AD%90%E5%9B%9E%E5%BA%94%E5%8D%81%E5%87%A0%E4%B8%87%E9%BB%84%E9%87%91%E8%97%8F%E5%86%B0%E7%AE%B1%E5%86%B7%E5%86%BB%23) `460.3K 🔥` `NEW`
1. [普京祝贺伊朗新任最高领袖](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E7%A5%9D%E8%B4%BA%E4%BC%8A%E6%9C%97%E6%96%B0%E4%BB%BB%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%23) `460.0K 🔥` `NEW`
1. [被逐玉拼好婿笑死](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E9%80%90%E7%8E%89%E6%8B%BC%E5%A5%BD%E5%A9%BF%E7%AC%91%E6%AD%BB%23) `459.6K 🔥` `NEW`
1. [电饭锅 我冒饭了](https://s.weibo.com/weibo?q=%23%E7%94%B5%E9%A5%AD%E9%94%85%20%E6%88%91%E5%86%92%E9%A5%AD%E4%BA%86%23) `459.5K 🔥` `NEW`
1. [13岁中国小孩哥夺得世界街舞冠军 (13-year-old Chinese kid wins world hip-hop dance championship)](https://s.weibo.com/weibo?q=%2313%E5%B2%81%E4%B8%AD%E5%9B%BD%E5%B0%8F%E5%AD%A9%E5%93%A5%E5%A4%BA%E5%BE%97%E4%B8%96%E7%95%8C%E8%A1%97%E8%88%9E%E5%86%A0%E5%86%9B%23) `459.4K 🔥` `NEW`
1. [中国女足2比1朝鲜女足 (Chinese women's football team 2-1 North Korea women's football team)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B32%E6%AF%941%E6%9C%9D%E9%B2%9C%E5%A5%B3%E8%B6%B3%23) `1.0M 🔥`
1. [农业农村部部长建议大家少吃点油 (The Minister of Agriculture and Rural Affairs advises everyone to eat less oil)](https://s.weibo.com/weibo?q=%23%E5%86%9C%E4%B8%9A%E5%86%9C%E6%9D%91%E9%83%A8%E9%83%A8%E9%95%BF%E5%BB%BA%E8%AE%AE%E5%A4%A7%E5%AE%B6%E5%B0%91%E5%90%83%E7%82%B9%E6%B2%B9%23) `739.7K 🔥`
1. [听劝淘宝闪购真的合作F1了 (After listening to the advice, Taobao’s flash sale really cooperated with F1)](https://s.weibo.com/weibo?q=%23%E5%90%AC%E5%8A%9D%E6%B7%98%E5%AE%9D%E9%97%AA%E8%B4%AD%E7%9C%9F%E7%9A%84%E5%90%88%E4%BD%9CF1%E4%BA%86%23) `583.7K 🔥`
1. [周深1天官宣8场演唱会](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B11%E5%A4%A9%E5%AE%98%E5%AE%A38%E5%9C%BA%E6%BC%94%E5%94%B1%E4%BC%9A%23) `582.8K 🔥`
1. [日方恣意妄为必将付出代价](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%96%B9%E6%81%A3%E6%84%8F%E5%A6%84%E4%B8%BA%E5%BF%85%E5%B0%86%E4%BB%98%E5%87%BA%E4%BB%A3%E4%BB%B7%23) `554.4K 🔥`
1. [人大报告精华版 (Highlights of the National People's Congress Report)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E6%8A%A5%E5%91%8A%E7%B2%BE%E5%8D%8E%E7%89%88%23) `585.1K 🔥` `-22%`
1. [建议中小学周边禁设台球厅](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%AD%E5%B0%8F%E5%AD%A6%E5%91%A8%E8%BE%B9%E7%A6%81%E8%AE%BE%E5%8F%B0%E7%90%83%E5%8E%85%23) `576.7K 🔥` `-23%`
1. [美被迫中止军事行动的可能性上升](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%A2%AB%E8%BF%AB%E4%B8%AD%E6%AD%A2%E5%86%9B%E4%BA%8B%E8%A1%8C%E5%8A%A8%E7%9A%84%E5%8F%AF%E8%83%BD%E6%80%A7%E4%B8%8A%E5%8D%87%23) `572.9K 🔥` `-23%`
1. [公司辞退闭眼小憩3分钟员工违法 (Company fires employee for taking 3-minute nap with eyes closed, illegal)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E5%8F%B8%E8%BE%9E%E9%80%80%E9%97%AD%E7%9C%BC%E5%B0%8F%E6%86%A93%E5%88%86%E9%92%9F%E5%91%98%E5%B7%A5%E8%BF%9D%E6%B3%95%23) `567.2K 🔥` `-24%`
1. [建议鼓励大学生返乡创业](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%BC%93%E5%8A%B1%E5%A4%A7%E5%AD%A6%E7%94%9F%E8%BF%94%E4%B9%A1%E5%88%9B%E4%B8%9A%23) `564.8K 🔥` `-23%`
1. [电视剧品质盛典 (TV Series Quality Ceremony)](https://s.weibo.com/weibo?q=%23%E7%94%B5%E8%A7%86%E5%89%A7%E5%93%81%E8%B4%A8%E7%9B%9B%E5%85%B8%23) `560.3K 🔥` `-25%`
1. [千万不要在洗澡时做人脸认证](https://s.weibo.com/weibo?q=%23%E5%8D%83%E4%B8%87%E4%B8%8D%E8%A6%81%E5%9C%A8%E6%B4%97%E6%BE%A1%E6%97%B6%E5%81%9A%E4%BA%BA%E8%84%B8%E8%AE%A4%E8%AF%81%23) `542.6K 🔥` `-26%`
1. [重案六组 张一山李沐宸 (Serious Case Group Six Zhang Yishan and Li Muchen)](https://s.weibo.com/weibo?q=%23%E9%87%8D%E6%A1%88%E5%85%AD%E7%BB%84%20%E5%BC%A0%E4%B8%80%E5%B1%B1%E6%9D%8E%E6%B2%90%E5%AE%B8%23) `540.8K 🔥` `-26%`
1. [白鹿别把白敬亭扇感冒了](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%88%AB%E6%8A%8A%E7%99%BD%E6%95%AC%E4%BA%AD%E6%89%87%E6%84%9F%E5%86%92%E4%BA%86%23) `481.5K 🔥` `-33%`
1. [爱玩拼豆的人天塌了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E7%8E%A9%E6%8B%BC%E8%B1%86%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `462.0K 🔥` `-37%`
1. [逐玉 杀人者的噩梦竟然是杀猪](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E6%9D%80%E4%BA%BA%E8%80%85%E7%9A%84%E5%99%A9%E6%A2%A6%E7%AB%9F%E7%84%B6%E6%98%AF%E6%9D%80%E7%8C%AA%23) `462.0K 🔥` `-37%`
1. [长玉大人开恩 谢征都杀喽 (Lord Changyu, please show mercy. Xie Zhengdu will be killed.)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E7%8E%89%E5%A4%A7%E4%BA%BA%E5%BC%80%E6%81%A9%20%E8%B0%A2%E5%BE%81%E9%83%BD%E6%9D%80%E5%96%BD%23) `461.9K 🔥` `-36%`
1. [日本部署远程导弹 (Japan deploys long-range missiles)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E9%83%A8%E7%BD%B2%E8%BF%9C%E7%A8%8B%E5%AF%BC%E5%BC%B9%23) `461.8K 🔥` `-37%`
1. [杨超越 中国有自己的张元英 (Yang Chaoyue China has its own Zhang Yuanying)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%B6%85%E8%B6%8A%20%E4%B8%AD%E5%9B%BD%E6%9C%89%E8%87%AA%E5%B7%B1%E7%9A%84%E5%BC%A0%E5%85%83%E8%8B%B1%23) `461.7K 🔥` `-35%`
1. [TVB女主播靠指纹破37年杀人悬案](https://s.weibo.com/weibo?q=%23TVB%E5%A5%B3%E4%B8%BB%E6%92%AD%E9%9D%A0%E6%8C%87%E7%BA%B9%E7%A0%B437%E5%B9%B4%E6%9D%80%E4%BA%BA%E6%82%AC%E6%A1%88%23) `461.6K 🔥` `-36%`
1. [男子送女友刮刮乐花束刮出80万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%80%81%E5%A5%B3%E5%8F%8B%E5%88%AE%E5%88%AE%E4%B9%90%E8%8A%B1%E6%9D%9F%E5%88%AE%E5%87%BA80%E4%B8%87%23) `461.4K 🔥` `-36%`
1. [逐玉弹幕 恶语伤牛心](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%BC%B9%E5%B9%95%20%E6%81%B6%E8%AF%AD%E4%BC%A4%E7%89%9B%E5%BF%83%23) `461.3K 🔥` `-36%`
1. [李延贺煽动分裂国家破坏国家统一 (Li Yanhe incited secession and undermined national unity)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%BB%B6%E8%B4%BA%E7%85%BD%E5%8A%A8%E5%88%86%E8%A3%82%E5%9B%BD%E5%AE%B6%E7%A0%B4%E5%9D%8F%E5%9B%BD%E5%AE%B6%E7%BB%9F%E4%B8%80%23) `461.1K 🔥` `-35%`
1. [嘉人镜头冲到王一博怀里了](https://s.weibo.com/weibo?q=%23%E5%98%89%E4%BA%BA%E9%95%9C%E5%A4%B4%E5%86%B2%E5%88%B0%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%80%80%E9%87%8C%E4%BA%86%23) `461.1K 🔥` `-36%`
1. [伊朗总统提醒邻国别被美以欺骗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E6%8F%90%E9%86%92%E9%82%BB%E5%9B%BD%E5%88%AB%E8%A2%AB%E7%BE%8E%E4%BB%A5%E6%AC%BA%E9%AA%97%23) `460.9K 🔥` `-36%`
1. [甜茶卖上霉豆腐了](https://s.weibo.com/weibo?q=%23%E7%94%9C%E8%8C%B6%E5%8D%96%E4%B8%8A%E9%9C%89%E8%B1%86%E8%85%90%E4%BA%86%23) `460.8K 🔥` `-36%`
1. [48岁中国女博导在埃及突然去世](https://s.weibo.com/weibo?q=%2348%E5%B2%81%E4%B8%AD%E5%9B%BD%E5%A5%B3%E5%8D%9A%E5%AF%BC%E5%9C%A8%E5%9F%83%E5%8F%8A%E7%AA%81%E7%84%B6%E5%8E%BB%E4%B8%96%23) `460.7K 🔥` `-36%`
1. [镖人 全女版 (Escort all-female version)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E5%85%A8%E5%A5%B3%E7%89%88%23) `460.6K 🔥` `-36%`
1. [美议员称推翻伊朗美国将在中东大赚](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%AE%AE%E5%91%98%E7%A7%B0%E6%8E%A8%E7%BF%BB%E4%BC%8A%E6%9C%97%E7%BE%8E%E5%9B%BD%E5%B0%86%E5%9C%A8%E4%B8%AD%E4%B8%9C%E5%A4%A7%E8%B5%9A%23) `460.5K 🔥` `-36%`
1. [宋雨琦官宣入职乐事](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E5%AE%98%E5%AE%A3%E5%85%A5%E8%81%8C%E4%B9%90%E4%BA%8B%23) `460.4K 🔥` `-37%`
1. [桃黑黑直播 (Taoheihei live broadcast)](https://s.weibo.com/weibo?q=%23%E6%A1%83%E9%BB%91%E9%BB%91%E7%9B%B4%E6%92%AD%23) `460.3K 🔥` `-36%`
1. [趁油价大涨前去加满](https://s.weibo.com/weibo?q=%23%E8%B6%81%E6%B2%B9%E4%BB%B7%E5%A4%A7%E6%B6%A8%E5%89%8D%E5%8E%BB%E5%8A%A0%E6%BB%A1%23) `460.2K 🔥` `-36%`
1. [终于有人把相亲的感受说清楚了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%BA%E6%8A%8A%E7%9B%B8%E4%BA%B2%E7%9A%84%E6%84%9F%E5%8F%97%E8%AF%B4%E6%B8%85%E6%A5%9A%E4%BA%86%23) `460.1K 🔥` `-36%`
1. [镖人升至全球武侠片票房亚军](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E5%8D%87%E8%87%B3%E5%85%A8%E7%90%83%E6%AD%A6%E4%BE%A0%E7%89%87%E7%A5%A8%E6%88%BF%E4%BA%9A%E5%86%9B%23) `459.9K 🔥` `-36%`
1. [白鹿问这是直播么 (Bai Lu asked if this was a live broadcast)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E9%97%AE%E8%BF%99%E6%98%AF%E7%9B%B4%E6%92%AD%E4%B9%88%23) `459.9K 🔥` `-36%`
1. [敬妃带着胧月开网约车](https://s.weibo.com/weibo?q=%23%E6%95%AC%E5%A6%83%E5%B8%A6%E7%9D%80%E8%83%A7%E6%9C%88%E5%BC%80%E7%BD%91%E7%BA%A6%E8%BD%A6%23) `459.8K 🔥` `-35%`
1. [妈妈在被子上缝了一道线](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9C%A8%E8%A2%AB%E5%AD%90%E4%B8%8A%E7%BC%9D%E4%BA%86%E4%B8%80%E9%81%93%E7%BA%BF%23) `459.7K 🔥` `-35%`
1. [孙千发了和王安宇合照 (Sun Qianfa posted a photo with Wang Anyu)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E5%8D%83%E5%8F%91%E4%BA%86%E5%92%8C%E7%8E%8B%E5%AE%89%E5%AE%87%E5%90%88%E7%85%A7%23) `459.6K 🔥` `-36%`
1. [中国女足小组第1](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B3%E5%B0%8F%E7%BB%84%E7%AC%AC1%23) `459.3K 🔥` `-37%`

Updated at 2026-03-09 20:27:25

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
