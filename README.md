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

1. [孙颖莎女单夺冠 (Sun Yingsha wins women's singles championship)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E5%A5%B3%E5%8D%95%E5%A4%BA%E5%86%A0%23) `1.3M 🔥` `NEW`
1. [赵今麦流浪地球3造型](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%BB%8A%E9%BA%A6%E6%B5%81%E6%B5%AA%E5%9C%B0%E7%90%833%E9%80%A0%E5%9E%8B%23) `678.3K 🔥` `NEW`
1. [孙颖莎4比2王曼昱](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E4%E6%AF%942%E7%8E%8B%E6%9B%BC%E6%98%B1%23) `410.1K 🔥` `NEW`
1. [陈思罕 我是一个专业的摄影师](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%80%9D%E7%BD%95%20%E6%88%91%E6%98%AF%E4%B8%80%E4%B8%AA%E4%B8%93%E4%B8%9A%E7%9A%84%E6%91%84%E5%BD%B1%E5%B8%88%23) `241.8K 🔥` `NEW`
1. [秦PLUS官宣7年低息夯爆了](https://s.weibo.com/weibo?q=%23%E7%A7%A6PLUS%E5%AE%98%E5%AE%A37%E5%B9%B4%E4%BD%8E%E6%81%AF%E5%A4%AF%E7%88%86%E4%BA%86%23) `237.1K 🔥` `NEW`
1. [1010元托运柴犬3天没喝一口水死亡](https://s.weibo.com/weibo?q=%231010%E5%85%83%E6%89%98%E8%BF%90%E6%9F%B4%E7%8A%AC3%E5%A4%A9%E6%B2%A1%E5%96%9D%E4%B8%80%E5%8F%A3%E6%B0%B4%E6%AD%BB%E4%BA%A1%23) `236.1K 🔥` `NEW`
1. [一油轮欲通过霍尔木兹海峡被击中](https://s.weibo.com/weibo?q=%23%E4%B8%80%E6%B2%B9%E8%BD%AE%E6%AC%B2%E9%80%9A%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E8%A2%AB%E5%87%BB%E4%B8%AD%23) `234.9K 🔥` `NEW`
1. [迪拜已拦截超百次伊朗炸弹](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E6%8B%9C%E5%B7%B2%E6%8B%A6%E6%88%AA%E8%B6%85%E7%99%BE%E6%AC%A1%E4%BC%8A%E6%9C%97%E7%82%B8%E5%BC%B9%23) `231.6K 🔥` `NEW`
1. [陈思罕镜头里的四代](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%80%9D%E7%BD%95%E9%95%9C%E5%A4%B4%E9%87%8C%E7%9A%84%E5%9B%9B%E4%BB%A3%23) `230.6K 🔥` `NEW`
1. [台胞可持台胞证登记撤离以色列](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E8%83%9E%E5%8F%AF%E6%8C%81%E5%8F%B0%E8%83%9E%E8%AF%81%E7%99%BB%E8%AE%B0%E6%92%A4%E7%A6%BB%E4%BB%A5%E8%89%B2%E5%88%97%23) `218.7K 🔥` `NEW`
1. [AI短剧 (AI skit)](https://s.weibo.com/weibo?q=%23AI%E7%9F%AD%E5%89%A7%23) `181.9K 🔥` `NEW`
1. [曝张元英签售切小屏](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%BC%A0%E5%85%83%E8%8B%B1%E7%AD%BE%E5%94%AE%E5%88%87%E5%B0%8F%E5%B1%8F%23) `176.0K 🔥` `NEW`
1. [张凌赫田曦薇从见面到合作用了386天](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E4%BB%8E%E8%A7%81%E9%9D%A2%E5%88%B0%E5%90%88%E4%BD%9C%E7%94%A8%E4%BA%86386%E5%A4%A9%23) `172.8K 🔥` `NEW`
1. [聚会豪饮2斤白酒23岁小伙喝进ICU](https://s.weibo.com/weibo?q=%23%E8%81%9A%E4%BC%9A%E8%B1%AA%E9%A5%AE2%E6%96%A4%E7%99%BD%E9%85%9223%E5%B2%81%E5%B0%8F%E4%BC%99%E5%96%9D%E8%BF%9BICU%23) `126.2K 🔥` `NEW`
1. [白鹿赵晴偷拍王星越](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E8%B5%B5%E6%99%B4%E5%81%B7%E6%8B%8D%E7%8E%8B%E6%98%9F%E8%B6%8A%23) `124.1K 🔥` `NEW`
1. [中方予以坚决反对和强烈谴责](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E4%BA%88%E4%BB%A5%E5%9D%9A%E5%86%B3%E5%8F%8D%E5%AF%B9%E5%92%8C%E5%BC%BA%E7%83%88%E8%B0%B4%E8%B4%A3%23) `116.2K 🔥` `NEW`
1. [王曼昱获得亚军](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%9B%BC%E6%98%B1%E8%8E%B7%E5%BE%97%E4%BA%9A%E5%86%9B%23) `101.5K 🔥` `NEW`
1. [孙颖莎回应4比2王曼昱](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E5%9B%9E%E5%BA%944%E6%AF%942%E7%8E%8B%E6%9B%BC%E6%98%B1%23) `100.5K 🔥` `NEW`
1. [杨紫上次恋爱已是七年前](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E4%B8%8A%E6%AC%A1%E6%81%8B%E7%88%B1%E5%B7%B2%E6%98%AF%E4%B8%83%E5%B9%B4%E5%89%8D%23) `98.5K 🔥` `NEW`
1. [三甲医生回应秦岚嗓子哑了三年](https://s.weibo.com/weibo?q=%23%E4%B8%89%E7%94%B2%E5%8C%BB%E7%94%9F%E5%9B%9E%E5%BA%94%E7%A7%A6%E5%B2%9A%E5%97%93%E5%AD%90%E5%93%91%E4%BA%86%E4%B8%89%E5%B9%B4%23) `241.0K 🔥` `+22%`
1. [张元英签售态度 (Zhang Yuanying's attitude towards signing sales)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%85%83%E8%8B%B1%E7%AD%BE%E5%94%AE%E6%80%81%E5%BA%A6%23) `237.7K 🔥` `+26%`
1. [黄轩的手 此沙的脚 (Huang Xuan’s hands and this sand’s feet)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E8%BD%A9%E7%9A%84%E6%89%8B%20%E6%AD%A4%E6%B2%99%E7%9A%84%E8%84%9A%23) `233.7K 🔥` `+24%`
1. [宋亚轩海胆头](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BA%9A%E8%BD%A9%E6%B5%B7%E8%83%86%E5%A4%B4%23) `230.4K 🔥` `+25%`
1. [全国政协会议议程来了 (The agenda for the National Committee of the Chinese People's Political Consultative Conference is here)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E6%94%BF%E5%8D%8F%E4%BC%9A%E8%AE%AE%E8%AE%AE%E7%A8%8B%E6%9D%A5%E4%BA%86%23) `694.8K 🔥`
1. [寿星千万种海底捞都宠](https://s.weibo.com/weibo?q=%23%E5%AF%BF%E6%98%9F%E5%8D%83%E4%B8%87%E7%A7%8D%E6%B5%B7%E5%BA%95%E6%8D%9E%E9%83%BD%E5%AE%A0%23) `382.6K 🔥`
1. [中国军号发布视频](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%86%9B%E5%8F%B7%E5%8F%91%E5%B8%83%E8%A7%86%E9%A2%91%23) `328.8K 🔥`
1. [中俄呼吁立即停止战争 (China and Russia call for an immediate end to the war)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BF%84%E5%91%BC%E5%90%81%E7%AB%8B%E5%8D%B3%E5%81%9C%E6%AD%A2%E6%88%98%E4%BA%89%23) `324.7K 🔥`
1. [伊朗总统就哈梅内伊身亡发声明 (Iranian President issues statement on Khamenei's death)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E5%B0%B1%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E8%BA%AB%E4%BA%A1%E5%8F%91%E5%A3%B0%E6%98%8E%23) `242.7K 🔥`
1. [出轨对象得知感染HIV还瞒着自己](https://s.weibo.com/weibo?q=%23%E5%87%BA%E8%BD%A8%E5%AF%B9%E8%B1%A1%E5%BE%97%E7%9F%A5%E6%84%9F%E6%9F%93HIV%E8%BF%98%E7%9E%92%E7%9D%80%E8%87%AA%E5%B7%B1%23) `239.7K 🔥`
1. [黄金暗盘跳水](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E6%9A%97%E7%9B%98%E8%B7%B3%E6%B0%B4%23) `239.6K 🔥`
1. [一家4口爬山祈福妻子坠亡](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B64%E5%8F%A3%E7%88%AC%E5%B1%B1%E7%A5%88%E7%A6%8F%E5%A6%BB%E5%AD%90%E5%9D%A0%E4%BA%A1%23) `238.2K 🔥`
1. [纪凌尘与韩国女友泰国度假](https://s.weibo.com/weibo?q=%23%E7%BA%AA%E5%87%8C%E5%B0%98%E4%B8%8E%E9%9F%A9%E5%9B%BD%E5%A5%B3%E5%8F%8B%E6%B3%B0%E5%9B%BD%E5%BA%A6%E5%81%87%23) `234.5K 🔥`
1. [我在挨骂 稍等呀 (I'm being scolded. Wait a minute.)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9C%A8%E6%8C%A8%E9%AA%82%20%E7%A8%8D%E7%AD%89%E5%91%80%23) `232.8K 🔥`
1. [以军开始打击伊朗首都心脏地带](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E5%BC%80%E5%A7%8B%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%E9%A6%96%E9%83%BD%E5%BF%83%E8%84%8F%E5%9C%B0%E5%B8%A6%23) `230.4K 🔥`
1. [男子酒后和老婆吵架胸口撕裂40厘米 (Man suffered a 40cm tear in his chest after a drunken argument with his wife)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%85%92%E5%90%8E%E5%92%8C%E8%80%81%E5%A9%86%E5%90%B5%E6%9E%B6%E8%83%B8%E5%8F%A3%E6%92%95%E8%A3%8240%E5%8E%98%E7%B1%B3%23) `191.8K 🔥`
1. [杨幂 得罪就得罪吧 (Yang Mi, just offend if you offend me)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%20%E5%BE%97%E7%BD%AA%E5%B0%B1%E5%BE%97%E7%BD%AA%E5%90%A7%23) `182.0K 🔥`
1. [贝因美 大麻二酚](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%9B%A0%E7%BE%8E%20%E5%A4%A7%E9%BA%BB%E4%BA%8C%E9%85%9A%23) `177.8K 🔥`
1. [耙耙柑的本名叫春见 (Raakegan’s real name is Harumi)](https://s.weibo.com/weibo?q=%23%E8%80%99%E8%80%99%E6%9F%91%E7%9A%84%E6%9C%AC%E5%90%8D%E5%8F%AB%E6%98%A5%E8%A7%81%23) `141.7K 🔥`
1. [谷爱凌辛芷蕾 野心是最好的预告 (Gu Ailing Xin Zhilei Ambition is the best trailer)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%BE%9B%E8%8A%B7%E8%95%BE%20%E9%87%8E%E5%BF%83%E6%98%AF%E6%9C%80%E5%A5%BD%E7%9A%84%E9%A2%84%E5%91%8A%23) `116.2K 🔥`
1. [李荣浩 高考界最严厉的父亲 (Li Ronghao, the strictest father in the college entrance examination world)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8D%A3%E6%B5%A9%20%E9%AB%98%E8%80%83%E7%95%8C%E6%9C%80%E4%B8%A5%E5%8E%89%E7%9A%84%E7%88%B6%E4%BA%B2%23) `101.2K 🔥`
1. [小镇唯一外卖员靠跑单月入过万 (The only delivery boy in town earns over 10,000 yuan a month by running orders)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%95%87%E5%94%AF%E4%B8%80%E5%A4%96%E5%8D%96%E5%91%98%E9%9D%A0%E8%B7%91%E5%8D%95%E6%9C%88%E5%85%A5%E8%BF%87%E4%B8%87%23) `98.0K 🔥`
1. [伊朗袭击27个美军基地 (Iran attacks 27 US military bases)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB27%E4%B8%AA%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%23) `850.9K 🔥` `-26%`
1. [孙颖莎vs王曼昱](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E7%8E%8B%E6%9B%BC%E6%98%B1%23) `660.5K 🔥` `-22%`
1. [哈梅内伊遇害 (Khamenei killed)](https://s.weibo.com/weibo?q=%23%E5%93%88%E6%A2%85%E5%86%85%E4%BC%8A%E9%81%87%E5%AE%B3%23) `379.9K 🔥` `-34%`
1. [诞下5胞胎女子说现在没时间买黄金 (Woman who gave birth to quintuplets says she has no time to buy gold now)](https://s.weibo.com/weibo?q=%23%E8%AF%9E%E4%B8%8B5%E8%83%9E%E8%83%8E%E5%A5%B3%E5%AD%90%E8%AF%B4%E7%8E%B0%E5%9C%A8%E6%B2%A1%E6%97%B6%E9%97%B4%E4%B9%B0%E9%BB%84%E9%87%91%23) `243.0K 🔥` `-23%`
1. [王天辰郭晓婷 不舍那你留下来呀](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%E9%83%AD%E6%99%93%E5%A9%B7%20%E4%B8%8D%E8%88%8D%E9%82%A3%E4%BD%A0%E7%95%99%E4%B8%8B%E6%9D%A5%E5%91%80%23) `218.2K 🔥` `-29%`
1. [将门独后王鹤棣路透 (Wang Hedi, the only queen in the general family, Reuters)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E7%8E%8B%E9%B9%A4%E6%A3%A3%E8%B7%AF%E9%80%8F%23) `136.7K 🔥` `-54%`
1. [以军称已向伊朗投掷超1200枚导弹](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E7%A7%B0%E5%B7%B2%E5%90%91%E4%BC%8A%E6%9C%97%E6%8A%95%E6%8E%B7%E8%B6%851200%E6%9E%9A%E5%AF%BC%E5%BC%B9%23) `136.2K 🔥` `-28%`
1. [美以导弹炸到全球人钱包 (US-Israeli missiles hit wallets around the world)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E5%AF%BC%E5%BC%B9%E7%82%B8%E5%88%B0%E5%85%A8%E7%90%83%E4%BA%BA%E9%92%B1%E5%8C%85%23) `128.4K 🔥` `-53%`
1. [中国男篮险胜中国台北男篮 (Chinese men's basketball team narrowly defeated Chinese Taipei men's basketball team)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE%E9%99%A9%E8%83%9C%E4%B8%AD%E5%9B%BD%E5%8F%B0%E5%8C%97%E7%94%B7%E7%AF%AE%23) `118.5K 🔥` `-62%`

Updated at 2026-03-01 20:59:56

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
