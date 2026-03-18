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

1. [刘文祥麻辣烫店员徒手拌麻酱 (Liu Wenxiang Malatang clerk mixes sesame paste with his bare hands)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E5%BA%97%E5%91%98%E5%BE%92%E6%89%8B%E6%8B%8C%E9%BA%BB%E9%85%B1%23) `877.7K 🔥` `NEW`
1. [春暖花开各地文旅持续升温](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%9A%96%E8%8A%B1%E5%BC%80%E5%90%84%E5%9C%B0%E6%96%87%E6%97%85%E6%8C%81%E7%BB%AD%E5%8D%87%E6%B8%A9%23) `651.1K 🔥` `NEW`
1. [樊长玉谢征 好孕赘婿](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E8%B0%A2%E5%BE%81%20%E5%A5%BD%E5%AD%95%E8%B5%98%E5%A9%BF%23) `515.0K 🔥` `NEW`
1. [买到1箱有针眼水男子称已立案](https://s.weibo.com/weibo?q=%23%E4%B9%B0%E5%88%B01%E7%AE%B1%E6%9C%89%E9%92%88%E7%9C%BC%E6%B0%B4%E7%94%B7%E5%AD%90%E7%A7%B0%E5%B7%B2%E7%AB%8B%E6%A1%88%23) `256.0K 🔥` `NEW`
1. [鹅鸭杀新角色超能力者](https://s.weibo.com/weibo?q=%23%E9%B9%85%E9%B8%AD%E6%9D%80%E6%96%B0%E8%A7%92%E8%89%B2%E8%B6%85%E8%83%BD%E5%8A%9B%E8%80%85%23) `255.4K 🔥` `NEW`
1. [不是私生 是公立医院出生](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E6%98%AF%E7%A7%81%E7%94%9F%20%E6%98%AF%E5%85%AC%E7%AB%8B%E5%8C%BB%E9%99%A2%E5%87%BA%E7%94%9F%23) `254.9K 🔥` `NEW`
1. [网传落生去世](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E8%90%BD%E7%94%9F%E5%8E%BB%E4%B8%96%23) `253.8K 🔥` `NEW`
1. [今天才知道TFBOYS全称](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E6%89%8D%E7%9F%A5%E9%81%93TFBOYS%E5%85%A8%E7%A7%B0%23) `253.6K 🔥` `NEW`
1. [高市早苗回应不谴责美以言论被批](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%B0%B4%E8%B4%A3%E7%BE%8E%E4%BB%A5%E8%A8%80%E8%AE%BA%E8%A2%AB%E6%89%B9%23) `253.0K 🔥` `NEW`
1. [英皇还债 惠英红唱跳画全面发展](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E7%9A%87%E8%BF%98%E5%80%BA%20%E6%83%A0%E8%8B%B1%E7%BA%A2%E5%94%B1%E8%B7%B3%E7%94%BB%E5%85%A8%E9%9D%A2%E5%8F%91%E5%B1%95%23) `252.2K 🔥` `NEW`
1. [王祖贤医美 (Wang Zuxian Medical Beauty)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E7%A5%96%E8%B4%A4%E5%8C%BB%E7%BE%8E%23) `251.8K 🔥` `NEW`
1. [倪妮的新松弛感](https://s.weibo.com/weibo?q=%23%E5%80%AA%E5%A6%AE%E7%9A%84%E6%96%B0%E6%9D%BE%E5%BC%9B%E6%84%9F%23) `251.7K 🔥` `NEW`
1. [列车服务应满足卫生巾这一女性刚需](https://s.weibo.com/weibo?q=%23%E5%88%97%E8%BD%A6%E6%9C%8D%E5%8A%A1%E5%BA%94%E6%BB%A1%E8%B6%B3%E5%8D%AB%E7%94%9F%E5%B7%BE%E8%BF%99%E4%B8%80%E5%A5%B3%E6%80%A7%E5%88%9A%E9%9C%80%23) `251.6K 🔥` `NEW`
1. [姚晨 侯雯元](https://s.weibo.com/weibo?q=%23%E5%A7%9A%E6%99%A8%20%E4%BE%AF%E9%9B%AF%E5%85%83%23) `251.5K 🔥` `NEW`
1. [曝胡歌给初恋的手写信](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%83%A1%E6%AD%8C%E7%BB%99%E5%88%9D%E6%81%8B%E7%9A%84%E6%89%8B%E5%86%99%E4%BF%A1%23) `251.5K 🔥` `NEW`
1. [惠英红 备战歌手战长沙](https://s.weibo.com/weibo?q=%23%E6%83%A0%E8%8B%B1%E7%BA%A2%20%E5%A4%87%E6%88%98%E6%AD%8C%E6%89%8B%E6%88%98%E9%95%BF%E6%B2%99%23) `235.6K 🔥` `NEW`
1. [改善胰岛素抵抗的关键](https://s.weibo.com/weibo?q=%23%E6%94%B9%E5%96%84%E8%83%B0%E5%B2%9B%E7%B4%A0%E6%8A%B5%E6%8A%97%E7%9A%84%E5%85%B3%E9%94%AE%23) `178.4K 🔥` `NEW`
1. [吉利发布舱驾融合关键成果](https://s.weibo.com/weibo?q=%23%E5%90%89%E5%88%A9%E5%8F%91%E5%B8%83%E8%88%B1%E9%A9%BE%E8%9E%8D%E5%90%88%E5%85%B3%E9%94%AE%E6%88%90%E6%9E%9C%23) `177.5K 🔥` `NEW`
1. [何穗孕中期吃一顿饭胖三斤](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%A9%97%E5%AD%95%E4%B8%AD%E6%9C%9F%E5%90%83%E4%B8%80%E9%A1%BF%E9%A5%AD%E8%83%96%E4%B8%89%E6%96%A4%23) `171.6K 🔥` `NEW`
1. [油价或重回9元时代](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E6%88%96%E9%87%8D%E5%9B%9E9%E5%85%83%E6%97%B6%E4%BB%A3%23) `166.4K 🔥` `NEW`
1. [赵丽颖请选择你的修仙搭子 (Zhao Liying, please choose your partner for cultivating immortality)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E8%AF%B7%E9%80%89%E6%8B%A9%E4%BD%A0%E7%9A%84%E4%BF%AE%E4%BB%99%E6%90%AD%E5%AD%90%23) `165.3K 🔥` `NEW`
1. [微信折叠发图](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E6%8A%98%E5%8F%A0%E5%8F%91%E5%9B%BE%23) `153.1K 🔥` `NEW`
1. [流浪猫30天偷了1800只手套](https://s.weibo.com/weibo?q=%23%E6%B5%81%E6%B5%AA%E7%8C%AB30%E5%A4%A9%E5%81%B7%E4%BA%861800%E5%8F%AA%E6%89%8B%E5%A5%97%23) `125.7K 🔥` `NEW`
1. [邓凯不愧是语文130的大厨](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E4%B8%8D%E6%84%A7%E6%98%AF%E8%AF%AD%E6%96%87130%E7%9A%84%E5%A4%A7%E5%8E%A8%23) `125.2K 🔥` `NEW`
1. [黄子韬让刘耀文别乱说话](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E9%9F%AC%E8%AE%A9%E5%88%98%E8%80%80%E6%96%87%E5%88%AB%E4%B9%B1%E8%AF%B4%E8%AF%9D%23) `124.3K 🔥` `NEW`
1. [做核磁共振被遗忘6小时会经历什么](https://s.weibo.com/weibo?q=%23%E5%81%9A%E6%A0%B8%E7%A3%81%E5%85%B1%E6%8C%AF%E8%A2%AB%E9%81%97%E5%BF%986%E5%B0%8F%E6%97%B6%E4%BC%9A%E7%BB%8F%E5%8E%86%E4%BB%80%E4%B9%88%23) `124.0K 🔥` `NEW`
1. [曾被封杀的李一舟又开始卖AI课了](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%A2%AB%E5%B0%81%E6%9D%80%E7%9A%84%E6%9D%8E%E4%B8%80%E8%88%9F%E5%8F%88%E5%BC%80%E5%A7%8B%E5%8D%96AI%E8%AF%BE%E4%BA%86%23) `123.5K 🔥` `NEW`
1. [凌潇肃侯雯元 莞莞类卿](https://s.weibo.com/weibo?q=%23%E5%87%8C%E6%BD%87%E8%82%83%E4%BE%AF%E9%9B%AF%E5%85%83%20%E8%8E%9E%E8%8E%9E%E7%B1%BB%E5%8D%BF%23) `122.6K 🔥` `NEW`
1. [男孩被塞后备箱生父拒绝道歉赔偿](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E8%A2%AB%E5%A1%9E%E5%90%8E%E5%A4%87%E7%AE%B1%E7%94%9F%E7%88%B6%E6%8B%92%E7%BB%9D%E9%81%93%E6%AD%89%E8%B5%94%E5%81%BF%23) `122.0K 🔥` `NEW`
1. [瞿颖胡兵回应为什么没在一起](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%83%A1%E5%85%B5%E5%9B%9E%E5%BA%94%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B2%A1%E5%9C%A8%E4%B8%80%E8%B5%B7%23) `117.7K 🔥` `NEW`
1. [把装满牛奶的杯子倒着放 (Put the cup filled with milk upside down)](https://s.weibo.com/weibo?q=%23%E6%8A%8A%E8%A3%85%E6%BB%A1%E7%89%9B%E5%A5%B6%E7%9A%84%E6%9D%AF%E5%AD%90%E5%80%92%E7%9D%80%E6%94%BE%23) `116.2K 🔥` `NEW`
1. [陈法拉 好莱坞](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%B3%95%E6%8B%89%20%E5%A5%BD%E8%8E%B1%E5%9D%9E%23) `115.4K 🔥` `NEW`
1. [杨幂 想把祖国各种地方都走一走](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%20%E6%83%B3%E6%8A%8A%E7%A5%96%E5%9B%BD%E5%90%84%E7%A7%8D%E5%9C%B0%E6%96%B9%E9%83%BD%E8%B5%B0%E4%B8%80%E8%B5%B0%23) `97.8K 🔥` `NEW`
1. [林高远骑士精神](https://s.weibo.com/weibo?q=%23%E6%9E%97%E9%AB%98%E8%BF%9C%E9%AA%91%E5%A3%AB%E7%B2%BE%E7%A5%9E%23) `95.8K 🔥` `NEW`
1. [内蒙古一洗浴店涉卖淫嫖娼2人被抓](https://s.weibo.com/weibo?q=%23%E5%86%85%E8%92%99%E5%8F%A4%E4%B8%80%E6%B4%97%E6%B5%B4%E5%BA%97%E6%B6%89%E5%8D%96%E6%B7%AB%E5%AB%96%E5%A8%BC2%E4%BA%BA%E8%A2%AB%E6%8A%93%23) `92.3K 🔥` `NEW`
1. [钉钉发布企业级AI工作平台悟空](https://s.weibo.com/weibo?q=%23%E9%92%89%E9%92%89%E5%8F%91%E5%B8%83%E4%BC%81%E4%B8%9A%E7%BA%A7AI%E5%B7%A5%E4%BD%9C%E5%B9%B3%E5%8F%B0%E6%82%9F%E7%A9%BA%23) `564.0K 🔥` `+41%`
1. [女子投保两年半后确诊患癌遭拒赔 (Woman was diagnosed with cancer two and a half years after taking out insurance but was denied compensation)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%8A%95%E4%BF%9D%E4%B8%A4%E5%B9%B4%E5%8D%8A%E5%90%8E%E7%A1%AE%E8%AF%8A%E6%82%A3%E7%99%8C%E9%81%AD%E6%8B%92%E8%B5%94%23) `258.3K 🔥` `+160%`
1. [奇瑞犀牛电池360度安全防护](https://s.weibo.com/weibo?q=%23%E5%A5%87%E7%91%9E%E7%8A%80%E7%89%9B%E7%94%B5%E6%B1%A0360%E5%BA%A6%E5%AE%89%E5%85%A8%E9%98%B2%E6%8A%A4%23) `257.4K 🔥` `+32%`
1. [小米超强钢获得国家级科技一等奖](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E8%B6%85%E5%BC%BA%E9%92%A2%E8%8E%B7%E5%BE%97%E5%9B%BD%E5%AE%B6%E7%BA%A7%E7%A7%91%E6%8A%80%E4%B8%80%E7%AD%89%E5%A5%96%23) `257.4K 🔥` `+114%`
1. [iPhone18将首次启用三星相机](https://s.weibo.com/weibo?q=%23iPhone18%E5%B0%86%E9%A6%96%E6%AC%A1%E5%90%AF%E7%94%A8%E4%B8%89%E6%98%9F%E7%9B%B8%E6%9C%BA%23) `251.8K 🔥` `+65%`
1. [瞿颖回应已婚](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E5%9B%9E%E5%BA%94%E5%B7%B2%E5%A9%9A%23) `251.4K 🔥` `+65%`
1. [曝小S哭着去陈建州范玮琪家 (It was revealed that Little S went to Chen Jianzhou and Weiqi Fan’s house in tears)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%B0%8FS%E5%93%AD%E7%9D%80%E5%8E%BB%E9%99%88%E5%BB%BA%E5%B7%9E%E8%8C%83%E7%8E%AE%E7%90%AA%E5%AE%B6%23) `175.7K 🔥` `+34%`
1. [美军称用多枚5000磅钻地弹打击伊朗 (US military says it used multiple 5,000-pound ground-penetrating bombs to hit Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E7%A7%B0%E7%94%A8%E5%A4%9A%E6%9E%9A5000%E7%A3%85%E9%92%BB%E5%9C%B0%E5%BC%B9%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%23) `169.1K 🔥` `+43%`
1. [小S街头大哭](https://s.weibo.com/weibo?q=%23%E5%B0%8FS%E8%A1%97%E5%A4%B4%E5%A4%A7%E5%93%AD%23) `159.9K 🔥` `+31%`
1. [男二以下 AI演员 (AI actors below male 2)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E4%BA%8C%E4%BB%A5%E4%B8%8B%20AI%E6%BC%94%E5%91%98%23) `1.2M 🔥`
1. [伊朗总统誓言要为拉里贾尼复仇](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E8%AA%93%E8%A8%80%E8%A6%81%E4%B8%BA%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%E5%A4%8D%E4%BB%87%23) `258.0K 🔥`
1. [周杰伦新歌预告 (Jay Chou's new song preview)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E6%AD%8C%E9%A2%84%E5%91%8A%23) `147.6K 🔥`
1. [章昊 新男团](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E6%98%8A%20%E6%96%B0%E7%94%B7%E5%9B%A2%23) `143.7K 🔥`
1. [微信能折叠发图了](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%83%BD%E6%8A%98%E5%8F%A0%E5%8F%91%E5%9B%BE%E4%BA%86%23) `256.5K 🔥` `-71%`
1. [毛宁向世界分享中国学生午睡神器](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E5%AE%81%E5%90%91%E4%B8%96%E7%95%8C%E5%88%86%E4%BA%AB%E4%B8%AD%E5%9B%BD%E5%AD%A6%E7%94%9F%E5%8D%88%E7%9D%A1%E7%A5%9E%E5%99%A8%23) `251.7K 🔥` `-21%`
1. [谢征吻完眼里不是欲望是恐慌](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E5%90%BB%E5%AE%8C%E7%9C%BC%E9%87%8C%E4%B8%8D%E6%98%AF%E6%AC%B2%E6%9C%9B%E6%98%AF%E6%81%90%E6%85%8C%23) `121.8K 🔥` `-51%`
1. [利他性表达](https://s.weibo.com/weibo?q=%23%E5%88%A9%E4%BB%96%E6%80%A7%E8%A1%A8%E8%BE%BE%23) `90.7K 🔥` `-41%`

Updated at 2026-03-18 13:10:23

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
