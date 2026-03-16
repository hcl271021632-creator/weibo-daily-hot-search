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

1. [樊振东下赛季加盟杜塞尔多夫 (Fan Zhendong joins Dusseldorf next season)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E4%B8%8B%E8%B5%9B%E5%AD%A3%E5%8A%A0%E7%9B%9F%E6%9D%9C%E5%A1%9E%E5%B0%94%E5%A4%9A%E5%A4%AB%23) `1.1M 🔥` `NEW`
1. [樊振东将离开萨尔队](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%B0%86%E7%A6%BB%E5%BC%80%E8%90%A8%E5%B0%94%E9%98%9F%23) `558.8K 🔥` `NEW`
1. [发现虾腿有肉以后](https://s.weibo.com/weibo?q=%23%E5%8F%91%E7%8E%B0%E8%99%BE%E8%85%BF%E6%9C%89%E8%82%89%E4%BB%A5%E5%90%8E%23) `552.6K 🔥` `NEW`
1. [中美双方就特朗普总统访华事保持着沟通](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E7%BE%8E%E5%8F%8C%E6%96%B9%E5%B0%B1%E7%89%B9%E6%9C%97%E6%99%AE%E6%80%BB%E7%BB%9F%E8%AE%BF%E5%8D%8E%E4%BA%8B%E4%BF%9D%E6%8C%81%E7%9D%80%E6%B2%9F%E9%80%9A%23) `352.7K 🔥` `NEW`
1. [坠江研究生曾因试图跳楼被送精神病科](https://s.weibo.com/weibo?q=%23%E5%9D%A0%E6%B1%9F%E7%A0%94%E7%A9%B6%E7%94%9F%E6%9B%BE%E5%9B%A0%E8%AF%95%E5%9B%BE%E8%B7%B3%E6%A5%BC%E8%A2%AB%E9%80%81%E7%B2%BE%E7%A5%9E%E7%97%85%E7%A7%91%23) `352.0K 🔥` `NEW`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `349.9K 🔥` `NEW`
1. [不然官宣恋情](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E7%84%B6%E5%AE%98%E5%AE%A3%E6%81%8B%E6%83%85%23) `323.6K 🔥` `NEW`
1. [樊振东回应转会](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%9B%9E%E5%BA%94%E8%BD%AC%E4%BC%9A%23) `312.6K 🔥` `NEW`
1. [315塌房全总结](https://s.weibo.com/weibo?q=%23315%E5%A1%8C%E6%88%BF%E5%85%A8%E6%80%BB%E7%BB%93%23) `305.3K 🔥` `NEW`
1. [事业单位招人岗位在海拔3614米山顶](https://s.weibo.com/weibo?q=%23%E4%BA%8B%E4%B8%9A%E5%8D%95%E4%BD%8D%E6%8B%9B%E4%BA%BA%E5%B2%97%E4%BD%8D%E5%9C%A8%E6%B5%B7%E6%8B%943614%E7%B1%B3%E5%B1%B1%E9%A1%B6%23) `287.6K 🔥` `NEW`
1. [女子借5万还不上履约做对方女友 (A woman borrowed 50,000 yuan but still failed to fulfill the contract to become his girlfriend)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%80%9F5%E4%B8%87%E8%BF%98%E4%B8%8D%E4%B8%8A%E5%B1%A5%E7%BA%A6%E5%81%9A%E5%AF%B9%E6%96%B9%E5%A5%B3%E5%8F%8B%23) `271.7K 🔥` `NEW`
1. [孙燕姿胖了](https://s.weibo.com/weibo?q=%23%E5%AD%99%E7%87%95%E5%A7%BF%E8%83%96%E4%BA%86%23) `269.9K 🔥` `NEW`
1. [范丞丞开始减肥第一天](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E5%BC%80%E5%A7%8B%E5%87%8F%E8%82%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%23) `234.8K 🔥` `NEW`
1. [痞幼自曝彩礼只要10万](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E8%87%AA%E6%9B%9D%E5%BD%A9%E7%A4%BC%E5%8F%AA%E8%A6%8110%E4%B8%87%23) `152.5K 🔥` `NEW`
1. [男子喝咖啡后头晕送检查出伟哥成分](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%96%9D%E5%92%96%E5%95%A1%E5%90%8E%E5%A4%B4%E6%99%95%E9%80%81%E6%A3%80%E6%9F%A5%E5%87%BA%E4%BC%9F%E5%93%A5%E6%88%90%E5%88%86%23) `132.2K 🔥` `NEW`
1. [香港西贡码头惊现身绑砖头浮尸](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E8%A5%BF%E8%B4%A1%E7%A0%81%E5%A4%B4%E6%83%8A%E7%8E%B0%E8%BA%AB%E7%BB%91%E7%A0%96%E5%A4%B4%E6%B5%AE%E5%B0%B8%23) `100.5K 🔥` `NEW`
1. [何小鹏直播第二代VLA推送](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%B0%8F%E9%B9%8F%E7%9B%B4%E6%92%AD%E7%AC%AC%E4%BA%8C%E4%BB%A3VLA%E6%8E%A8%E9%80%81%23) `88.5K 🔥` `NEW`
1. [樊振东与波尔的约定实现了](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E4%B8%8E%E6%B3%A2%E5%B0%94%E7%9A%84%E7%BA%A6%E5%AE%9A%E5%AE%9E%E7%8E%B0%E4%BA%86%23) `87.0K 🔥` `NEW`
1. [幼儿园孩子该不该活在楚门的世界里](https://s.weibo.com/weibo?q=%23%E5%B9%BC%E5%84%BF%E5%9B%AD%E5%AD%A9%E5%AD%90%E8%AF%A5%E4%B8%8D%E8%AF%A5%E6%B4%BB%E5%9C%A8%E6%A5%9A%E9%97%A8%E7%9A%84%E4%B8%96%E7%95%8C%E9%87%8C%23) `86.2K 🔥` `NEW`
1. [王一栩虞书欣 三搭](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E6%A0%A9%E8%99%9E%E4%B9%A6%E6%AC%A3%20%E4%B8%89%E6%90%AD%23) `83.0K 🔥` `NEW`
1. [啃雕胡萝卜女孩称曾因牙齿自卑 (Girl who gnawed carved carrots said she had low self-esteem because of her teeth)](https://s.weibo.com/weibo?q=%23%E5%95%83%E9%9B%95%E8%83%A1%E8%90%9D%E5%8D%9C%E5%A5%B3%E5%AD%A9%E7%A7%B0%E6%9B%BE%E5%9B%A0%E7%89%99%E9%BD%BF%E8%87%AA%E5%8D%91%23) `81.9K 🔥` `NEW`
1. [黄子韬疑似回应被经纪人背刺](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E9%9F%AC%E7%96%91%E4%BC%BC%E5%9B%9E%E5%BA%94%E8%A2%AB%E7%BB%8F%E7%BA%AA%E4%BA%BA%E8%83%8C%E5%88%BA%23) `73.0K 🔥` `NEW`
1. [鸿蒙智行 小米](https://s.weibo.com/weibo?q=%23%E9%B8%BF%E8%92%99%E6%99%BA%E8%A1%8C%20%E5%B0%8F%E7%B1%B3%23) `576.9K 🔥` `+138%`
1. [爱吃薯片的人天塌了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E8%96%AF%E7%89%87%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `558.4K 🔥` `+209%`
1. [教体局通报女孩遭殴打不予立案原因](https://s.weibo.com/weibo?q=%23%E6%95%99%E4%BD%93%E5%B1%80%E9%80%9A%E6%8A%A5%E5%A5%B3%E5%AD%A9%E9%81%AD%E6%AE%B4%E6%89%93%E4%B8%8D%E4%BA%88%E7%AB%8B%E6%A1%88%E5%8E%9F%E5%9B%A0%23) `459.9K 🔥` `+260%`
1. [F1海外账号发合影把吴艳妮裁掉 (F1 overseas account posted a group photo and cut Wu Yanni off)](https://s.weibo.com/weibo?q=%23F1%E6%B5%B7%E5%A4%96%E8%B4%A6%E5%8F%B7%E5%8F%91%E5%90%88%E5%BD%B1%E6%8A%8A%E5%90%B4%E8%89%B3%E5%A6%AE%E8%A3%81%E6%8E%89%23) `377.0K 🔥` `+113%`
1. [张凌赫田曦薇浴池戏](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%B5%B4%E6%B1%A0%E6%88%8F%23) `315.8K 🔥` `+156%`
1. [中方回应特朗普呼吁多国派军舰护航](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E5%91%BC%E5%90%81%E5%A4%9A%E5%9B%BD%E6%B4%BE%E5%86%9B%E8%88%B0%E6%8A%A4%E8%88%AA%23) `310.0K 🔥` `+103%`
1. [埃文凯尔官宣定居中国 (Evan Kyle officially announced to settle in China)](https://s.weibo.com/weibo?q=%23%E5%9F%83%E6%96%87%E5%87%AF%E5%B0%94%E5%AE%98%E5%AE%A3%E5%AE%9A%E5%B1%85%E4%B8%AD%E5%9B%BD%23) `300.0K 🔥` `+82%`
1. [逐玉 编剧浪费演员颜值](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%BC%96%E5%89%A7%E6%B5%AA%E8%B4%B9%E6%BC%94%E5%91%98%E9%A2%9C%E5%80%BC%23) `295.0K 🔥` `+95%`
1. [鹿晗 关晓彤](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `282.5K 🔥` `+122%`
1. [王一栩 虞书欣演过最好的都是我给的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E6%A0%A9%20%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%BC%94%E8%BF%87%E6%9C%80%E5%A5%BD%E7%9A%84%E9%83%BD%E6%98%AF%E6%88%91%E7%BB%99%E7%9A%84%23) `282.3K 🔥` `+122%`
1. [周冬雨 刘昊然 (Zhou Dongyu Liu Haoran)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%AC%E9%9B%A8%20%E5%88%98%E6%98%8A%E7%84%B6%23) `219.4K 🔥` `+72%`
1. [26岁患癌女子冒生命危险坚持备孕 (26-year-old cancer-stricken woman risks her life to prepare for pregnancy)](https://s.weibo.com/weibo?q=%2326%E5%B2%81%E6%82%A3%E7%99%8C%E5%A5%B3%E5%AD%90%E5%86%92%E7%94%9F%E5%91%BD%E5%8D%B1%E9%99%A9%E5%9D%9A%E6%8C%81%E5%A4%87%E5%AD%95%23) `187.9K 🔥` `+48%`
1. [李诞说现在失业的人可能是一件好事](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%AF%9E%E8%AF%B4%E7%8E%B0%E5%9C%A8%E5%A4%B1%E4%B8%9A%E7%9A%84%E4%BA%BA%E5%8F%AF%E8%83%BD%E6%98%AF%E4%B8%80%E4%BB%B6%E5%A5%BD%E4%BA%8B%23) `165.9K 🔥` `+31%`
1. [涉事机器人高举双手被警方押走](https://s.weibo.com/weibo?q=%23%E6%B6%89%E4%BA%8B%E6%9C%BA%E5%99%A8%E4%BA%BA%E9%AB%98%E4%B8%BE%E5%8F%8C%E6%89%8B%E8%A2%AB%E8%AD%A6%E6%96%B9%E6%8A%BC%E8%B5%B0%23) `93.6K 🔥` `+34%`
1. [以为是火腿肠其实是炸药 (I thought it was ham sausage but it was actually explosives)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%98%AF%E7%81%AB%E8%85%BF%E8%82%A0%E5%85%B6%E5%AE%9E%E6%98%AF%E7%82%B8%E8%8D%AF%23) `799.3K 🔥`
1. [2026年以旧换新数据亮眼](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E4%BB%A5%E6%97%A7%E6%8D%A2%E6%96%B0%E6%95%B0%E6%8D%AE%E4%BA%AE%E7%9C%BC%23) `634.0K 🔥`
1. [张檬想给孩子喂母乳到2岁](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%AA%AC%E6%83%B3%E7%BB%99%E5%AD%A9%E5%AD%90%E5%96%82%E6%AF%8D%E4%B9%B3%E5%88%B02%E5%B2%81%23) `127.1K 🔥`
1. [向太给郭碧婷买了4块地 (Xiangtai bought 4 pieces of land for Guo Biting)](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%A4%AA%E7%BB%99%E9%83%AD%E7%A2%A7%E5%A9%B7%E4%B9%B0%E4%BA%864%E5%9D%97%E5%9C%B0%23) `92.9K 🔥`
1. [吴敬平说樊振东娘家人来了](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%95%AC%E5%B9%B3%E8%AF%B4%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%A8%98%E5%AE%B6%E4%BA%BA%E6%9D%A5%E4%BA%86%23) `83.5K 🔥`
1. [王橹杰语音](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E8%AF%AD%E9%9F%B3%23) `80.9K 🔥`
1. [刘文祥致歉 (Liu Wenxiang apologizes)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E8%87%B4%E6%AD%89%23) `251.8K 🔥` `-76%`
1. [深圳卫健委又发力了 (Shenzhen Health Commission has made another effort)](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E5%8D%AB%E5%81%A5%E5%A7%94%E5%8F%88%E5%8F%91%E5%8A%9B%E4%BA%86%23) `105.3K 🔥` `-31%`
1. [刘宇宁回应黄子韬道歉](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%9B%9E%E5%BA%94%E9%BB%84%E5%AD%90%E9%9F%AC%E9%81%93%E6%AD%89%23) `99.0K 🔥` `-22%`
1. [经纪人回应瞿颖翻红](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E7%BA%AA%E4%BA%BA%E5%9B%9E%E5%BA%94%E7%9E%BF%E9%A2%96%E7%BF%BB%E7%BA%A2%23) `85.9K 🔥` `-25%`
1. [78岁老人离世天空群鹤盘旋半小时](https://s.weibo.com/weibo?q=%2378%E5%B2%81%E8%80%81%E4%BA%BA%E7%A6%BB%E4%B8%96%E5%A4%A9%E7%A9%BA%E7%BE%A4%E9%B9%A4%E7%9B%98%E6%97%8B%E5%8D%8A%E5%B0%8F%E6%97%B6%23) `79.0K 🔥` `-33%`
1. [老人被烫伤酒店怒吼家属你没责任吗 (An old man was burned and the hotel yelled at his family. Are you not responsible?)](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%BA%BA%E8%A2%AB%E7%83%AB%E4%BC%A4%E9%85%92%E5%BA%97%E6%80%92%E5%90%BC%E5%AE%B6%E5%B1%9E%E4%BD%A0%E6%B2%A1%E8%B4%A3%E4%BB%BB%E5%90%97%23) `74.1K 🔥` `-33%`
1. [宋雨琦 内娱星二代孩子王](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%20%E5%86%85%E5%A8%B1%E6%98%9F%E4%BA%8C%E4%BB%A3%E5%AD%A9%E5%AD%90%E7%8E%8B%23) `73.3K 🔥` `-37%`
1. [爱穿带帽卫衣的那批人被年龄攻击了 (Those who like to wear hooded sweatshirts are attacked by age)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E7%A9%BF%E5%B8%A6%E5%B8%BD%E5%8D%AB%E8%A1%A3%E7%9A%84%E9%82%A3%E6%89%B9%E4%BA%BA%E8%A2%AB%E5%B9%B4%E9%BE%84%E6%94%BB%E5%87%BB%E4%BA%86%23) `72.9K 🔥` `-48%`

Updated at 2026-03-16 19:14:11

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
