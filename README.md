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

1. [奥迪破马年吉尼斯世界纪录 (Audi breaks Guinness world record in Year of the Horse)](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E8%BF%AA%E7%A0%B4%E9%A9%AC%E5%B9%B4%E5%90%89%E5%B0%BC%E6%96%AF%E4%B8%96%E7%95%8C%E7%BA%AA%E5%BD%95%23) `521.8K 🔥` `NEW`
1. [全国政协十四届四次会议开幕](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E6%94%BF%E5%8D%8F%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E5%BC%80%E5%B9%95%23) `304.6K 🔥` `NEW`
1. [伊朗飞乌鲁木齐视频刷屏后被打假](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A3%9E%E4%B9%8C%E9%B2%81%E6%9C%A8%E9%BD%90%E8%A7%86%E9%A2%91%E5%88%B7%E5%B1%8F%E5%90%8E%E8%A2%AB%E6%89%93%E5%81%87%23) `287.0K 🔥` `NEW`
1. [阿里高层出面挽留林俊旸](https://s.weibo.com/weibo?q=%23%E9%98%BF%E9%87%8C%E9%AB%98%E5%B1%82%E5%87%BA%E9%9D%A2%E6%8C%BD%E7%95%99%E6%9E%97%E4%BF%8A%E6%97%B8%23) `251.1K 🔥` `NEW`
1. [李幼斌 法拉利老了会变成意大利炮](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%B9%BC%E6%96%8C%20%E6%B3%95%E6%8B%89%E5%88%A9%E8%80%81%E4%BA%86%E4%BC%9A%E5%8F%98%E6%88%90%E6%84%8F%E5%A4%A7%E5%88%A9%E7%82%AE%23) `191.1K 🔥` `NEW`
1. [情久对战JDG](https://s.weibo.com/weibo?q=%23%E6%83%85%E4%B9%85%E5%AF%B9%E6%88%98JDG%23) `125.8K 🔥` `NEW`
1. [林诗栋重庆冠军赛退赛](https://s.weibo.com/weibo?q=%23%E6%9E%97%E8%AF%97%E6%A0%8B%E9%87%8D%E5%BA%86%E5%86%A0%E5%86%9B%E8%B5%9B%E9%80%80%E8%B5%9B%23) `123.3K 🔥` `NEW`
1. [鸿蒙智行发布会](https://s.weibo.com/weibo?q=%23%E9%B8%BF%E8%92%99%E6%99%BA%E8%A1%8C%E5%8F%91%E5%B8%83%E4%BC%9A%23) `117.7K 🔥` `NEW`
1. [我国今年将大力提振消费](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E4%BB%8A%E5%B9%B4%E5%B0%86%E5%A4%A7%E5%8A%9B%E6%8F%90%E6%8C%AF%E6%B6%88%E8%B4%B9%23) `117.4K 🔥` `NEW`
1. [萨巴伦卡订婚](https://s.weibo.com/weibo?q=%23%E8%90%A8%E5%B7%B4%E4%BC%A6%E5%8D%A1%E8%AE%A2%E5%A9%9A%23) `104.6K 🔥` `NEW`
1. [惠英红 最灵验的庙宇是我的血肉 (Hui Yinghong The most effective temple is my flesh and blood)](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%20%E6%9C%80%E7%81%B5%E9%AA%8C%E7%9A%84%E5%BA%99%E5%AE%87%E6%98%AF%E6%88%91%E7%9A%84%E8%A1%80%E8%82%89%23) `93.7K 🔥` `NEW`
1. [古偶有被造谣当场反击的女主了](https://s.weibo.com/weibo?q=%23%E5%8F%A4%E5%81%B6%E6%9C%89%E8%A2%AB%E9%80%A0%E8%B0%A3%E5%BD%93%E5%9C%BA%E5%8F%8D%E5%87%BB%E7%9A%84%E5%A5%B3%E4%B8%BB%E4%BA%86%23) `93.0K 🔥` `NEW`
1. [一眼看出不经常加班的公司](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%9C%BC%E7%9C%8B%E5%87%BA%E4%B8%8D%E7%BB%8F%E5%B8%B8%E5%8A%A0%E7%8F%AD%E7%9A%84%E5%85%AC%E5%8F%B8%23) `88.0K 🔥` `NEW`
1. [你有点不新鲜了](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E6%9C%89%E7%82%B9%E4%B8%8D%E6%96%B0%E9%B2%9C%E4%BA%86%23) `86.3K 🔥` `NEW`
1. [中国石油跌停](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E8%B7%8C%E5%81%9C%23) `85.7K 🔥` `NEW`
1. [镖人 历史上最后的纯手工武侠](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20%E5%8E%86%E5%8F%B2%E4%B8%8A%E6%9C%80%E5%90%8E%E7%9A%84%E7%BA%AF%E6%89%8B%E5%B7%A5%E6%AD%A6%E4%BE%A0%23) `80.0K 🔥` `NEW`
1. [建议提高个税起征点至8000或1万](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%8F%90%E9%AB%98%E4%B8%AA%E7%A8%8E%E8%B5%B7%E5%BE%81%E7%82%B9%E8%87%B38000%E6%88%961%E4%B8%87%23) `280.2K 🔥` `+101%`
1. [建议高考英语降为100分](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E9%AB%98%E8%80%83%E8%8B%B1%E8%AF%AD%E9%99%8D%E4%B8%BA100%E5%88%86%23) `263.2K 🔥` `+83%`
1. [李乃文 去法国排什么队](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%B9%83%E6%96%87%20%E5%8E%BB%E6%B3%95%E5%9B%BD%E6%8E%92%E4%BB%80%E4%B9%88%E9%98%9F%23) `186.4K 🔥` `+54%`
1. [建议居民身份证去地址化 (It is recommended that resident ID cards be de-addressed)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B1%85%E6%B0%91%E8%BA%AB%E4%BB%BD%E8%AF%81%E5%8E%BB%E5%9C%B0%E5%9D%80%E5%8C%96%23) `1.1M 🔥`
1. [建议彩礼金额不超过6万元 (It is recommended that the amount of the betrothal gift should not exceed 60,000 yuan)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%BD%A9%E7%A4%BC%E9%87%91%E9%A2%9D%E4%B8%8D%E8%B6%85%E8%BF%876%E4%B8%87%E5%85%83%23) `790.9K 🔥`
1. [2026两会日程预告 (2026 Two Sessions Schedule Preview)](https://s.weibo.com/weibo?q=%232026%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%E9%A2%84%E5%91%8A%23) `666.7K 🔥`
1. [一菲和诺澜在短剧二搭了](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%8F%B2%E5%92%8C%E8%AF%BA%E6%BE%9C%E5%9C%A8%E7%9F%AD%E5%89%A7%E4%BA%8C%E6%90%AD%E4%BA%86%23) `292.4K 🔥`
1. [中东局势彻底失控 (The situation in the Middle East is completely out of control)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%B8%9C%E5%B1%80%E5%8A%BF%E5%BD%BB%E5%BA%95%E5%A4%B1%E6%8E%A7%23) `287.6K 🔥`
1. [大学生返校统一姿势 (College students return to school in unified posture)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%AD%A6%E7%94%9F%E8%BF%94%E6%A0%A1%E7%BB%9F%E4%B8%80%E5%A7%BF%E5%8A%BF%23) `284.1K 🔥`
1. [烤肉店辣椒水是干嘛的](https://s.weibo.com/weibo?q=%23%E7%83%A4%E8%82%89%E5%BA%97%E8%BE%A3%E6%A4%92%E6%B0%B4%E6%98%AF%E5%B9%B2%E5%98%9B%E7%9A%84%23) `257.4K 🔥`
1. [王天辰 就是很想亲](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%20%E5%B0%B1%E6%98%AF%E5%BE%88%E6%83%B3%E4%BA%B2%23) `235.4K 🔥`
1. [伊拉克被美以当成打伊朗的免费跳板](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%8B%89%E5%85%8B%E8%A2%AB%E7%BE%8E%E4%BB%A5%E5%BD%93%E6%88%90%E6%89%93%E4%BC%8A%E6%9C%97%E7%9A%84%E5%85%8D%E8%B4%B9%E8%B7%B3%E6%9D%BF%23) `226.5K 🔥`
1. [这竟然是甄嬛传里的温宜公主](https://s.weibo.com/weibo?q=%23%E8%BF%99%E7%AB%9F%E7%84%B6%E6%98%AF%E7%94%84%E5%AC%9B%E4%BC%A0%E9%87%8C%E7%9A%84%E6%B8%A9%E5%AE%9C%E5%85%AC%E4%B8%BB%23) `225.1K 🔥`
1. [徐璐自曝做了牙贴片](https://s.weibo.com/weibo?q=%23%E5%BE%90%E7%92%90%E8%87%AA%E6%9B%9D%E5%81%9A%E4%BA%86%E7%89%99%E8%B4%B4%E7%89%87%23) `204.9K 🔥`
1. [肛门周围长东西一定是痔疮吗 (Is the growth around the anus definitely hemorrhoids?)](https://s.weibo.com/weibo?q=%23%E8%82%9B%E9%97%A8%E5%91%A8%E5%9B%B4%E9%95%BF%E4%B8%9C%E8%A5%BF%E4%B8%80%E5%AE%9A%E6%98%AF%E7%97%94%E7%96%AE%E5%90%97%23) `134.4K 🔥`
1. [伊朗宣布击中美军驱逐舰补给舰](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%A3%E5%B8%83%E5%87%BB%E4%B8%AD%E7%BE%8E%E5%86%9B%E9%A9%B1%E9%80%90%E8%88%B0%E8%A1%A5%E7%BB%99%E8%88%B0%23) `133.2K 🔥`
1. [十四届全国人大四次会议议程 (Agenda for the Fourth Session of the 14th National People's Congress)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E8%AE%AE%E7%A8%8B%23) `97.2K 🔥`
1. [恋与深空 (Love and deep space)](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%23) `96.8K 🔥`
1. [杨幂汤圆头像](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%B1%A4%E5%9C%86%E5%A4%B4%E5%83%8F%23) `91.0K 🔥`
1. [相亲市场还是太权威了](https://s.weibo.com/weibo?q=%23%E7%9B%B8%E4%BA%B2%E5%B8%82%E5%9C%BA%E8%BF%98%E6%98%AF%E5%A4%AA%E6%9D%83%E5%A8%81%E4%BA%86%23) `87.2K 🔥`
1. [胖东来1月为2员工发放1.5万委屈奖](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A51%E6%9C%88%E4%B8%BA2%E5%91%98%E5%B7%A5%E5%8F%91%E6%94%BE1.5%E4%B8%87%E5%A7%94%E5%B1%88%E5%A5%96%23) `83.0K 🔥`
1. [建议将农村养老金提升至500元每人每月 (It is recommended to increase rural pensions to 500 yuan per person per month)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%86%E5%86%9C%E6%9D%91%E5%85%BB%E8%80%81%E9%87%91%E6%8F%90%E5%8D%87%E8%87%B3500%E5%85%83%E6%AF%8F%E4%BA%BA%E6%AF%8F%E6%9C%88%23) `192.0K 🔥` `-35%`
1. [两会 (two sessions)](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%23) `183.5K 🔥` `-26%`
1. [全球股市全线暴跌](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E8%82%A1%E5%B8%82%E5%85%A8%E7%BA%BF%E6%9A%B4%E8%B7%8C%23) `179.7K 🔥` `-27%`
1. [美军公布最新伤亡情况](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E5%85%AC%E5%B8%83%E6%9C%80%E6%96%B0%E4%BC%A4%E4%BA%A1%E6%83%85%E5%86%B5%23) `155.8K 🔥` `-24%`
1. [雨天午睡很舒服就要小心了](https://s.weibo.com/weibo?q=%23%E9%9B%A8%E5%A4%A9%E5%8D%88%E7%9D%A1%E5%BE%88%E8%88%92%E6%9C%8D%E5%B0%B1%E8%A6%81%E5%B0%8F%E5%BF%83%E4%BA%86%23) `144.7K 🔥` `-32%`
1. [伊朗首都全天遭轮番打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%85%A8%E5%A4%A9%E9%81%AD%E8%BD%AE%E7%95%AA%E6%89%93%E5%87%BB%23) `144.3K 🔥` `-41%`
1. [霍尔木兹海峡十多艘油轮被炮弹击中](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E5%8D%81%E5%A4%9A%E8%89%98%E6%B2%B9%E8%BD%AE%E8%A2%AB%E7%82%AE%E5%BC%B9%E5%87%BB%E4%B8%AD%23) `125.0K 🔥` `-22%`
1. [十四届全国人大四次会议发布会](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%9B%9B%E5%B1%8A%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E5%9B%9B%E6%AC%A1%E4%BC%9A%E8%AE%AE%E5%8F%91%E5%B8%83%E4%BC%9A%23) `109.4K 🔥` `-23%`
1. [没有性生活也会感染HPV吗 (Can you get HPV even if you don’t have sex?)](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E6%9C%89%E6%80%A7%E7%94%9F%E6%B4%BB%E4%B9%9F%E4%BC%9A%E6%84%9F%E6%9F%93HPV%E5%90%97%23) `104.2K 🔥` `-25%`
1. [飞驰人生3暂列全球票房年榜第一](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E6%9A%82%E5%88%97%E5%85%A8%E7%90%83%E7%A5%A8%E6%88%BF%E5%B9%B4%E6%A6%9C%E7%AC%AC%E4%B8%80%23) `103.0K 🔥` `-58%`
1. [赖伟明学范丞丞的手势舞 照抄广告](https://s.weibo.com/weibo?q=%23%E8%B5%96%E4%BC%9F%E6%98%8E%E5%AD%A6%E8%8C%83%E4%B8%9E%E4%B8%9E%E7%9A%84%E6%89%8B%E5%8A%BF%E8%88%9E%20%E7%85%A7%E6%8A%84%E5%B9%BF%E5%91%8A%23) `95.8K 🔥` `-27%`
1. [复旦大学生活码 复活码](https://s.weibo.com/weibo?q=%23%E5%A4%8D%E6%97%A6%E5%A4%A7%E5%AD%A6%E7%94%9F%E6%B4%BB%E7%A0%81%20%E5%A4%8D%E6%B4%BB%E7%A0%81%23) `95.5K 🔥` `-61%`
1. [第一场委员通道 (The first committee member channel)](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E5%9C%BA%E5%A7%94%E5%91%98%E9%80%9A%E9%81%93%23) `93.0K 🔥` `-29%`
1. [王楚钦许昕互动 (Wang Chuqin and Xu Xin interaction)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%AE%B8%E6%98%95%E4%BA%92%E5%8A%A8%23) `85.3K 🔥` `-37%`
1. [建议建立母亲养老金制度](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%BB%BA%E7%AB%8B%E6%AF%8D%E4%BA%B2%E5%85%BB%E8%80%81%E9%87%91%E5%88%B6%E5%BA%A6%23) `78.3K 🔥` `-62%`

Updated at 2026-03-04 15:49:56

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
