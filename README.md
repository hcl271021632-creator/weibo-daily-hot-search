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

1. [以为是火腿肠其实是炸药 (I thought it was ham sausage but it was actually explosives)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%98%AF%E7%81%AB%E8%85%BF%E8%82%A0%E5%85%B6%E5%AE%9E%E6%98%AF%E7%82%B8%E8%8D%AF%23) `767.8K 🔥` `NEW`
1. [今日辟谣](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E6%97%A5%E8%BE%9F%E8%B0%A3%23) `177.2K 🔥` `NEW`
1. [商户说你把我曝光了我咋做人](https://s.weibo.com/weibo?q=%23%E5%95%86%E6%88%B7%E8%AF%B4%E4%BD%A0%E6%8A%8A%E6%88%91%E6%9B%9D%E5%85%89%E4%BA%86%E6%88%91%E5%92%8B%E5%81%9A%E4%BA%BA%23) `153.9K 🔥` `NEW`
1. [一代人有一代人的下班仪式感](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%BB%A3%E4%BA%BA%E6%9C%89%E4%B8%80%E4%BB%A3%E4%BA%BA%E7%9A%84%E4%B8%8B%E7%8F%AD%E4%BB%AA%E5%BC%8F%E6%84%9F%23) `149.7K 🔥` `NEW`
1. [大众9X首发MomentaR7世界模型](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BC%979X%E9%A6%96%E5%8F%91MomentaR7%E4%B8%96%E7%95%8C%E6%A8%A1%E5%9E%8B%23) `130.1K 🔥` `NEW`
1. [教体局通报女孩遭殴打不予立案原因](https://s.weibo.com/weibo?q=%23%E6%95%99%E4%BD%93%E5%B1%80%E9%80%9A%E6%8A%A5%E5%A5%B3%E5%AD%A9%E9%81%AD%E6%AE%B4%E6%89%93%E4%B8%8D%E4%BA%88%E7%AB%8B%E6%A1%88%E5%8E%9F%E5%9B%A0%23) `127.6K 🔥` `NEW`
1. [王一栩 虞书欣演过最好的都是我给的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E6%A0%A9%20%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%BC%94%E8%BF%87%E6%9C%80%E5%A5%BD%E7%9A%84%E9%83%BD%E6%98%AF%E6%88%91%E7%BB%99%E7%9A%84%23) `127.0K 🔥` `NEW`
1. [张檬想给孩子喂母乳到2岁](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%AA%AC%E6%83%B3%E7%BB%99%E5%AD%A9%E5%AD%90%E5%96%82%E6%AF%8D%E4%B9%B3%E5%88%B02%E5%B2%81%23) `126.9K 🔥` `NEW`
1. [张凌赫田曦薇浴池戏](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%B5%B4%E6%B1%A0%E6%88%8F%23) `123.3K 🔥` `NEW`
1. [老人被烫伤酒店怒吼家属你没责任吗](https://s.weibo.com/weibo?q=%23%E8%80%81%E4%BA%BA%E8%A2%AB%E7%83%AB%E4%BC%A4%E9%85%92%E5%BA%97%E6%80%92%E5%90%BC%E5%AE%B6%E5%B1%9E%E4%BD%A0%E6%B2%A1%E8%B4%A3%E4%BB%BB%E5%90%97%23) `111.1K 🔥` `NEW`
1. [向太给郭碧婷买了4块地 (Xiangtai bought 4 pieces of land for Guo Biting)](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%A4%AA%E7%BB%99%E9%83%AD%E7%A2%A7%E5%A9%B7%E4%B9%B0%E4%BA%864%E5%9D%97%E5%9C%B0%23) `92.1K 🔥` `NEW`
1. [教委回应学校被曝规定上厕所不许带纸](https://s.weibo.com/weibo?q=%23%E6%95%99%E5%A7%94%E5%9B%9E%E5%BA%94%E5%AD%A6%E6%A0%A1%E8%A2%AB%E6%9B%9D%E8%A7%84%E5%AE%9A%E4%B8%8A%E5%8E%95%E6%89%80%E4%B8%8D%E8%AE%B8%E5%B8%A6%E7%BA%B8%23) `88.4K 🔥` `NEW`
1. [男子离世前夜再婚妻子转走60万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E7%A6%BB%E4%B8%96%E5%89%8D%E5%A4%9C%E5%86%8D%E5%A9%9A%E5%A6%BB%E5%AD%90%E8%BD%AC%E8%B5%B060%E4%B8%87%23) `88.1K 🔥` `NEW`
1. [吴敬平说樊振东娘家人来了](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%95%AC%E5%B9%B3%E8%AF%B4%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%A8%98%E5%AE%B6%E4%BA%BA%E6%9D%A5%E4%BA%86%23) `87.9K 🔥` `NEW`
1. [外国人赶飞机迟到工作人员一路带跑](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%9B%BD%E4%BA%BA%E8%B5%B6%E9%A3%9E%E6%9C%BA%E8%BF%9F%E5%88%B0%E5%B7%A5%E4%BD%9C%E4%BA%BA%E5%91%98%E4%B8%80%E8%B7%AF%E5%B8%A6%E8%B7%91%23) `82.7K 🔥` `NEW`
1. [王橹杰语音](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E8%AF%AD%E9%9F%B3%23) `81.0K 🔥` `NEW`
1. [田曦薇哭戏](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%93%AD%E6%88%8F%23) `81.0K 🔥` `NEW`
1. [下午茶吃出了大米饭的感觉](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E5%8D%88%E8%8C%B6%E5%90%83%E5%87%BA%E4%BA%86%E5%A4%A7%E7%B1%B3%E9%A5%AD%E7%9A%84%E6%84%9F%E8%A7%89%23) `80.7K 🔥` `NEW`
1. [涉事机器人高举双手被警方押走](https://s.weibo.com/weibo?q=%23%E6%B6%89%E4%BA%8B%E6%9C%BA%E5%99%A8%E4%BA%BA%E9%AB%98%E4%B8%BE%E5%8F%8C%E6%89%8B%E8%A2%AB%E8%AD%A6%E6%96%B9%E6%8A%BC%E8%B5%B0%23) `69.9K 🔥` `NEW`
1. [京东服装真5折又又又来了 (Jingdong clothing is really 50% off again)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E6%9C%8D%E8%A3%85%E7%9C%9F5%E6%8A%98%E5%8F%88%E5%8F%88%E5%8F%88%E6%9D%A5%E4%BA%86%23) `242.7K 🔥` `+52%`
1. [爱吃薯片的人天塌了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E8%96%AF%E7%89%87%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `180.7K 🔥` `+74%`
1. [F1海外账号发合影把吴艳妮裁掉 (F1 overseas account posted a group photo and cut Wu Yanni off)](https://s.weibo.com/weibo?q=%23F1%E6%B5%B7%E5%A4%96%E8%B4%A6%E5%8F%B7%E5%8F%91%E5%90%88%E5%BD%B1%E6%8A%8A%E5%90%B4%E8%89%B3%E5%A6%AE%E8%A3%81%E6%8E%89%23) `176.7K 🔥` `+59%`
1. [胡兵要去papi节目了](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%85%B5%E8%A6%81%E5%8E%BBpapi%E8%8A%82%E7%9B%AE%E4%BA%86%23) `109.2K 🔥` `+22%`
1. [刘文祥致歉 (Liu Wenxiang apologizes)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E8%87%B4%E6%AD%89%23) `1.1M 🔥`
1. [2026年以旧换新数据亮眼](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E4%BB%A5%E6%97%A7%E6%8D%A2%E6%96%B0%E6%95%B0%E6%8D%AE%E4%BA%AE%E7%9C%BC%23) `606.3K 🔥`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `129.8K 🔥`
1. [嫩牛五方桌 (Tender beef five-square table)](https://s.weibo.com/weibo?q=%23%E5%AB%A9%E7%89%9B%E4%BA%94%E6%96%B9%E6%A1%8C%23) `127.7K 🔥`
1. [鹿晗 关晓彤](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `127.4K 🔥`
1. [周冬雨 刘昊然 (Zhou Dongyu Liu Haoran)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%AC%E9%9B%A8%20%E5%88%98%E6%98%8A%E7%84%B6%23) `127.3K 🔥`
1. [李诞说现在失业的人可能是一件好事](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%AF%9E%E8%AF%B4%E7%8E%B0%E5%9C%A8%E5%A4%B1%E4%B8%9A%E7%9A%84%E4%BA%BA%E5%8F%AF%E8%83%BD%E6%98%AF%E4%B8%80%E4%BB%B6%E5%A5%BD%E4%BA%8B%23) `126.6K 🔥`
1. [林永健儿子与苏翊鸣合照](https://s.weibo.com/weibo?q=%23%E6%9E%97%E6%B0%B8%E5%81%A5%E5%84%BF%E5%AD%90%E4%B8%8E%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%90%88%E7%85%A7%23) `126.5K 🔥`
1. [刘宇宁回应黄子韬道歉](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E5%9B%9E%E5%BA%94%E9%BB%84%E5%AD%90%E9%9F%AC%E9%81%93%E6%AD%89%23) `126.2K 🔥`
1. [章子怡的买股运](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%E7%9A%84%E4%B9%B0%E8%82%A1%E8%BF%90%23) `99.6K 🔥`
1. [鸿蒙智行 小米](https://s.weibo.com/weibo?q=%23%E9%B8%BF%E8%92%99%E6%99%BA%E8%A1%8C%20%E5%B0%8F%E7%B1%B3%23) `242.7K 🔥` `-28%`
1. [315曝光名单 (315 exposure list)](https://s.weibo.com/weibo?q=%23315%E6%9B%9D%E5%85%89%E5%90%8D%E5%8D%95%23) `189.6K 🔥` `-75%`
1. [埃文凯尔官宣定居中国 (Evan Kyle officially announced to settle in China)](https://s.weibo.com/weibo?q=%23%E5%9F%83%E6%96%87%E5%87%AF%E5%B0%94%E5%AE%98%E5%AE%A3%E5%AE%9A%E5%B1%85%E4%B8%AD%E5%9B%BD%23) `164.7K 🔥` `-38%`
1. [卧底老K收入暴涨315总导演1天1电话 (Undercover old K’s income skyrocketed 315. The chief director made one call a day)](https://s.weibo.com/weibo?q=%23%E5%8D%A7%E5%BA%95%E8%80%81K%E6%94%B6%E5%85%A5%E6%9A%B4%E6%B6%A8315%E6%80%BB%E5%AF%BC%E6%BC%941%E5%A4%A91%E7%94%B5%E8%AF%9D%23) `154.5K 🔥` `-44%`
1. [深圳卫健委又发力了 (Shenzhen Health Commission has made another effort)](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E5%8D%AB%E5%81%A5%E5%A7%94%E5%8F%88%E5%8F%91%E5%8A%9B%E4%BA%86%23) `152.7K 🔥` `-25%`
1. [中方回应特朗普呼吁多国派军舰护航](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E5%91%BC%E5%90%81%E5%A4%9A%E5%9B%BD%E6%B4%BE%E5%86%9B%E8%88%B0%E6%8A%A4%E8%88%AA%23) `152.6K 🔥` `-24%`
1. [逐玉 编剧浪费演员颜值](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%BC%96%E5%89%A7%E6%B5%AA%E8%B4%B9%E6%BC%94%E5%91%98%E9%A2%9C%E5%80%BC%23) `151.5K 🔥` `-27%`
1. [脱刘文祥](https://s.weibo.com/weibo?q=%23%E8%84%B1%E5%88%98%E6%96%87%E7%A5%A5%23) `150.8K 🔥` `-26%`
1. [爱穿带帽卫衣的那批人被年龄攻击了 (Those who like to wear hooded sweatshirts are attacked by age)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E7%A9%BF%E5%B8%A6%E5%B8%BD%E5%8D%AB%E8%A1%A3%E7%9A%84%E9%82%A3%E6%89%B9%E4%BA%BA%E8%A2%AB%E5%B9%B4%E9%BE%84%E6%94%BB%E5%87%BB%E4%BA%86%23) `141.1K 🔥` `-35%`
1. [26岁患癌女子冒生命危险坚持备孕](https://s.weibo.com/weibo?q=%2326%E5%B2%81%E6%82%A3%E7%99%8C%E5%A5%B3%E5%AD%90%E5%86%92%E7%94%9F%E5%91%BD%E5%8D%B1%E9%99%A9%E5%9D%9A%E6%8C%81%E5%A4%87%E5%AD%95%23) `127.2K 🔥` `-39%`
1. [伊朗称440公斤60%丰度浓缩铀被埋](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0440%E5%85%AC%E6%96%A460%25%E4%B8%B0%E5%BA%A6%E6%B5%93%E7%BC%A9%E9%93%80%E8%A2%AB%E5%9F%8B%23) `126.7K 🔥` `-41%`
1. [小狗舔人被说主人情绪失控 (Puppy licks people and its owner is said to have lost control of his emotions)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E8%88%94%E4%BA%BA%E8%A2%AB%E8%AF%B4%E4%B8%BB%E4%BA%BA%E6%83%85%E7%BB%AA%E5%A4%B1%E6%8E%A7%23) `126.3K 🔥` `-22%`
1. [78岁老人离世天空群鹤盘旋半小时](https://s.weibo.com/weibo?q=%2378%E5%B2%81%E8%80%81%E4%BA%BA%E7%A6%BB%E4%B8%96%E5%A4%A9%E7%A9%BA%E7%BE%A4%E9%B9%A4%E7%9B%98%E6%97%8B%E5%8D%8A%E5%B0%8F%E6%97%B6%23) `118.2K 🔥` `-21%`
1. [宋雨琦 内娱星二代孩子王](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%20%E5%86%85%E5%A8%B1%E6%98%9F%E4%BA%8C%E4%BB%A3%E5%AD%A9%E5%AD%90%E7%8E%8B%23) `116.9K 🔥` `-28%`
1. [经纪人回应瞿颖翻红](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E7%BA%AA%E4%BA%BA%E5%9B%9E%E5%BA%94%E7%9E%BF%E9%A2%96%E7%BF%BB%E7%BA%A2%23) `114.0K 🔥` `-43%`
1. [性格内向的人看起来更显小](https://s.weibo.com/weibo?q=%23%E6%80%A7%E6%A0%BC%E5%86%85%E5%90%91%E7%9A%84%E4%BA%BA%E7%9C%8B%E8%B5%B7%E6%9D%A5%E6%9B%B4%E6%98%BE%E5%B0%8F%23) `80.5K 🔥` `-33%`
1. [奥斯卡最佳男主穿新中式领奖 (Oscar Best Actor wears new Chinese style to receive award)](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E6%96%AF%E5%8D%A1%E6%9C%80%E4%BD%B3%E7%94%B7%E4%B8%BB%E7%A9%BF%E6%96%B0%E4%B8%AD%E5%BC%8F%E9%A2%86%E5%A5%96%23) `74.5K 🔥` `-26%`
1. [邓凯妈妈 有那么帅吗](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E5%A6%88%E5%A6%88%20%E6%9C%89%E9%82%A3%E4%B9%88%E5%B8%85%E5%90%97%23) `74.3K 🔥` `-32%`
1. [司宫令正式官宣 (Official announcement of the Palace Order)](https://s.weibo.com/weibo?q=%23%E5%8F%B8%E5%AE%AB%E4%BB%A4%E6%AD%A3%E5%BC%8F%E5%AE%98%E5%AE%A3%23) `68.2K 🔥` `-42%`

Updated at 2026-03-16 18:16:41

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
