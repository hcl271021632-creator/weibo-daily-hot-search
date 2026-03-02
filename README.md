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

1. [伊朗导弹突破以色列防御系统 (Iranian missile breaks through Israeli defense system)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E7%AA%81%E7%A0%B4%E4%BB%A5%E8%89%B2%E5%88%97%E9%98%B2%E5%BE%A1%E7%B3%BB%E7%BB%9F%23) `1.9M 🔥` `NEW`
1. [电影难看20分钟内可退款40%](https://s.weibo.com/weibo?q=%23%E7%94%B5%E5%BD%B1%E9%9A%BE%E7%9C%8B20%E5%88%86%E9%92%9F%E5%86%85%E5%8F%AF%E9%80%80%E6%AC%BE40%25%23) `978.7K 🔥` `NEW`
1. [从一无所有到再造山河](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E4%B8%80%E6%97%A0%E6%89%80%E6%9C%89%E5%88%B0%E5%86%8D%E9%80%A0%E5%B1%B1%E6%B2%B3%23) `764.8K 🔥` `NEW`
1. [豆瓣200减200](https://s.weibo.com/weibo?q=%23%E8%B1%86%E7%93%A3200%E5%87%8F200%23) `375.6K 🔥` `NEW`
1. [学历自卑](https://s.weibo.com/weibo?q=%23%E5%AD%A6%E5%8E%86%E8%87%AA%E5%8D%91%23) `373.1K 🔥` `NEW`
1. [32岁男子首次带女友回家30人迎接](https://s.weibo.com/weibo?q=%2332%E5%B2%81%E7%94%B7%E5%AD%90%E9%A6%96%E6%AC%A1%E5%B8%A6%E5%A5%B3%E5%8F%8B%E5%9B%9E%E5%AE%B630%E4%BA%BA%E8%BF%8E%E6%8E%A5%23) `372.0K 🔥` `NEW`
1. [湖南卫视元宵晚会因暴雪暂停彩排](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8D%97%E5%8D%AB%E8%A7%86%E5%85%83%E5%AE%B5%E6%99%9A%E4%BC%9A%E5%9B%A0%E6%9A%B4%E9%9B%AA%E6%9A%82%E5%81%9C%E5%BD%A9%E6%8E%92%23) `368.2K 🔥` `NEW`
1. [伊朗前总统内贾德亲信称其平安](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%89%8D%E6%80%BB%E7%BB%9F%E5%86%85%E8%B4%BE%E5%BE%B7%E4%BA%B2%E4%BF%A1%E7%A7%B0%E5%85%B6%E5%B9%B3%E5%AE%89%23) `365.7K 🔥` `NEW`
1. [王楚钦过不了安检瞬间红温](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%BF%87%E4%B8%8D%E4%BA%86%E5%AE%89%E6%A3%80%E7%9E%AC%E9%97%B4%E7%BA%A2%E6%B8%A9%23) `363.5K 🔥` `NEW`
1. [向太怒批你凭什么喷王菲](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%A4%AA%E6%80%92%E6%89%B9%E4%BD%A0%E5%87%AD%E4%BB%80%E4%B9%88%E5%96%B7%E7%8E%8B%E8%8F%B2%23) `358.6K 🔥` `NEW`
1. [迪丽热巴闪耀巴黎 (Dilireba shines in Paris)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%97%AA%E8%80%80%E5%B7%B4%E9%BB%8E%23) `274.4K 🔥` `NEW`
1. [麦吉丽小银管褪红修护超顶](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%90%89%E4%B8%BD%E5%B0%8F%E9%93%B6%E7%AE%A1%E8%A4%AA%E7%BA%A2%E4%BF%AE%E6%8A%A4%E8%B6%85%E9%A1%B6%23) `273.7K 🔥` `NEW`
1. [李雨桐喊话薛之谦](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%9B%A8%E6%A1%90%E5%96%8A%E8%AF%9D%E8%96%9B%E4%B9%8B%E8%B0%A6%23) `270.5K 🔥` `NEW`
1. [英国允许美使用英方基地打击伊朗](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E5%85%81%E8%AE%B8%E7%BE%8E%E4%BD%BF%E7%94%A8%E8%8B%B1%E6%96%B9%E5%9F%BA%E5%9C%B0%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%23) `269.3K 🔥` `NEW`
1. [原来不止我一个人这样洗澡](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E4%B8%8D%E6%AD%A2%E6%88%91%E4%B8%80%E4%B8%AA%E4%BA%BA%E8%BF%99%E6%A0%B7%E6%B4%97%E6%BE%A1%23) `262.4K 🔥` `NEW`
1. [李雨桐说被薛之谦威胁](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%9B%A8%E6%A1%90%E8%AF%B4%E8%A2%AB%E8%96%9B%E4%B9%8B%E8%B0%A6%E5%A8%81%E8%83%81%23) `260.3K 🔥` `NEW`
1. [年轻人如何远离胃癌](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%A6%82%E4%BD%95%E8%BF%9C%E7%A6%BB%E8%83%83%E7%99%8C%23) `256.0K 🔥` `NEW`
1. [梅西梅开二度](https://s.weibo.com/weibo?q=%23%E6%A2%85%E8%A5%BF%E6%A2%85%E5%BC%80%E4%BA%8C%E5%BA%A6%23) `255.6K 🔥` `NEW`
1. [美以不可能打了伊朗就一走了之](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E4%B8%8D%E5%8F%AF%E8%83%BD%E6%89%93%E4%BA%86%E4%BC%8A%E6%9C%97%E5%B0%B1%E4%B8%80%E8%B5%B0%E4%BA%86%E4%B9%8B%23) `255.4K 🔥` `NEW`
1. [李昀锐还记得自己姓李不姓林吗](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E8%BF%98%E8%AE%B0%E5%BE%97%E8%87%AA%E5%B7%B1%E5%A7%93%E6%9D%8E%E4%B8%8D%E5%A7%93%E6%9E%97%E5%90%97%23) `255.3K 🔥` `NEW`
1. [佟丽娅给小酒窝发压岁钱 (Tong Liya gives new year's money to Xiao Dimple)](https://s.weibo.com/weibo?q=%23%E4%BD%9F%E4%B8%BD%E5%A8%85%E7%BB%99%E5%B0%8F%E9%85%92%E7%AA%9D%E5%8F%91%E5%8E%8B%E5%B2%81%E9%92%B1%23) `242.5K 🔥` `NEW`
1. [王楚然老钱风](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E8%80%81%E9%92%B1%E9%A3%8E%23) `230.0K 🔥` `NEW`
1. [黎巴嫩向以色列发射火箭弹](https://s.weibo.com/weibo?q=%23%E9%BB%8E%E5%B7%B4%E5%AB%A9%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%E5%8F%91%E5%B0%84%E7%81%AB%E7%AE%AD%E5%BC%B9%23) `182.0K 🔥` `NEW`
1. [孙颖莎对王楚钦说你拍你拍](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E5%AF%B9%E7%8E%8B%E6%A5%9A%E9%92%A6%E8%AF%B4%E4%BD%A0%E6%8B%8D%E4%BD%A0%E6%8B%8D%23) `181.3K 🔥` `NEW`
1. [白宫下令暂缓推进对台军售](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%AB%E4%B8%8B%E4%BB%A4%E6%9A%82%E7%BC%93%E6%8E%A8%E8%BF%9B%E5%AF%B9%E5%8F%B0%E5%86%9B%E5%94%AE%23) `181.3K 🔥` `NEW`
1. [当你发现奶茶袋可以防油溅](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BD%A0%E5%8F%91%E7%8E%B0%E5%A5%B6%E8%8C%B6%E8%A2%8B%E5%8F%AF%E4%BB%A5%E9%98%B2%E6%B2%B9%E6%BA%85%23) `181.2K 🔥` `NEW`
1. [秦岚拍延禧攻略大哭戏引发咽炎](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%B2%9A%E6%8B%8D%E5%BB%B6%E7%A6%A7%E6%94%BB%E7%95%A5%E5%A4%A7%E5%93%AD%E6%88%8F%E5%BC%95%E5%8F%91%E5%92%BD%E7%82%8E%23) `159.4K 🔥` `NEW`
1. [库明加隔扣杨瀚森](https://s.weibo.com/weibo?q=%23%E5%BA%93%E6%98%8E%E5%8A%A0%E9%9A%94%E6%89%A3%E6%9D%A8%E7%80%9A%E6%A3%AE%23) `150.3K 🔥` `NEW`
1. [幸福的秘诀 关闭朋友圈](https://s.weibo.com/weibo?q=%23%E5%B9%B8%E7%A6%8F%E7%9A%84%E7%A7%98%E8%AF%80%20%E5%85%B3%E9%97%AD%E6%9C%8B%E5%8F%8B%E5%9C%88%23) `147.2K 🔥` `NEW`
1. [18名中国公民顺利撤离伊朗](https://s.weibo.com/weibo?q=%2318%E5%90%8D%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E9%A1%BA%E5%88%A9%E6%92%A4%E7%A6%BB%E4%BC%8A%E6%9C%97%23) `375.3K 🔥` `+263%`
1. [年轻人的第一台轿跑可以更新了 (Young people’s first coupe can be updated)](https://s.weibo.com/weibo?q=%23%E5%B9%B4%E8%BD%BB%E4%BA%BA%E7%9A%84%E7%AC%AC%E4%B8%80%E5%8F%B0%E8%BD%BF%E8%B7%91%E5%8F%AF%E4%BB%A5%E6%9B%B4%E6%96%B0%E4%BA%86%23) `372.2K 🔥` `+48%`
1. [陈若琳手下又有王牌选手了 (Chen Ruolin has another ace player under her belt)](https://s.weibo.com/weibo?q=%23%E9%99%88%E8%8B%A5%E7%90%B3%E6%89%8B%E4%B8%8B%E5%8F%88%E6%9C%89%E7%8E%8B%E7%89%8C%E9%80%89%E6%89%8B%E4%BA%86%23) `369.7K 🔥` `+158%`
1. [孟子义自曝两年最长只休了2天](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E8%87%AA%E6%9B%9D%E4%B8%A4%E5%B9%B4%E6%9C%80%E9%95%BF%E5%8F%AA%E4%BC%91%E4%BA%862%E5%A4%A9%23) `360.3K 🔥` `+32%`
1. [霍尔木兹海峡两侧船只集体趴窝](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E4%B8%A4%E4%BE%A7%E8%88%B9%E5%8F%AA%E9%9B%86%E4%BD%93%E8%B6%B4%E7%AA%9D%23) `359.3K 🔥` `+97%`
1. [英法德或对伊朗采取防御行动 (Britain, France and Germany may take defensive action against Iran)](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E6%B3%95%E5%BE%B7%E6%88%96%E5%AF%B9%E4%BC%8A%E6%9C%97%E9%87%87%E5%8F%96%E9%98%B2%E5%BE%A1%E8%A1%8C%E5%8A%A8%23) `266.5K 🔥` `+47%`
1. [金饰克价涨到1642元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E6%B6%A8%E5%88%B01642%E5%85%83%23) `256.0K 🔥` `+49%`
1. [中国游客迪拜遇机场停运进退两难](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E8%BF%AA%E6%8B%9C%E9%81%87%E6%9C%BA%E5%9C%BA%E5%81%9C%E8%BF%90%E8%BF%9B%E9%80%80%E4%B8%A4%E9%9A%BE%23) `245.6K 🔥` `+194%`
1. [霸王茶姬口令](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `367.1K 🔥`
1. [广式离职申请书](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E5%BC%8F%E7%A6%BB%E8%81%8C%E7%94%B3%E8%AF%B7%E4%B9%A6%23) `295.3K 🔥`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `293.1K 🔥`
1. [赞达亚荷兰弟已经结婚](https://s.weibo.com/weibo?q=%23%E8%B5%9E%E8%BE%BE%E4%BA%9A%E8%8D%B7%E5%85%B0%E5%BC%9F%E5%B7%B2%E7%BB%8F%E7%BB%93%E5%A9%9A%23) `267.2K 🔥`
1. [亲母女嫁给了亲父子](https://s.weibo.com/weibo?q=%23%E4%BA%B2%E6%AF%8D%E5%A5%B3%E5%AB%81%E7%BB%99%E4%BA%86%E4%BA%B2%E7%88%B6%E5%AD%90%23) `255.8K 🔥`
1. [演员逼真到根本看不出来是AI (The actors are so lifelike that you can’t even tell they are AI)](https://s.weibo.com/weibo?q=%23%E6%BC%94%E5%91%98%E9%80%BC%E7%9C%9F%E5%88%B0%E6%A0%B9%E6%9C%AC%E7%9C%8B%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%98%AFAI%23) `254.0K 🔥`
1. [偶遇李昀锐还合照了 (I met Li Yunrui by chance and took a photo together.)](https://s.weibo.com/weibo?q=%23%E5%81%B6%E9%81%87%E6%9D%8E%E6%98%80%E9%94%90%E8%BF%98%E5%90%88%E7%85%A7%E4%BA%86%23) `152.5K 🔥`
1. [以军超100架战机空袭伊朗 (More than 100 Israeli fighter jets launch air strikes on Iran)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E8%B6%85100%E6%9E%B6%E6%88%98%E6%9C%BA%E7%A9%BA%E8%A2%AD%E4%BC%8A%E6%9C%97%23) `362.6K 🔥` `-69%`
1. [宋威龙误入直播间 (Song Weilong accidentally entered the live broadcast room)](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%A8%81%E9%BE%99%E8%AF%AF%E5%85%A5%E7%9B%B4%E6%92%AD%E9%97%B4%23) `181.6K 🔥` `-33%`
1. [俄罗斯在中东的布局被美国搅乱了 (Russia's layout in the Middle East has been disrupted by the United States)](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%E5%9C%A8%E4%B8%AD%E4%B8%9C%E7%9A%84%E5%B8%83%E5%B1%80%E8%A2%AB%E7%BE%8E%E5%9B%BD%E6%90%85%E4%B9%B1%E4%BA%86%23) `171.6K 🔥` `-37%`
1. [椰子水](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E5%AD%90%E6%B0%B4%23) `171.4K 🔥` `-43%`
1. [首都机场工作人员穿上汉服 (Capital Airport staff wear Hanfu)](https://s.weibo.com/weibo?q=%23%E9%A6%96%E9%83%BD%E6%9C%BA%E5%9C%BA%E5%B7%A5%E4%BD%9C%E4%BA%BA%E5%91%98%E7%A9%BF%E4%B8%8A%E6%B1%89%E6%9C%8D%23) `165.8K 🔥` `-39%`
1. [北京协和医院提出的科学减重方法](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8D%8F%E5%92%8C%E5%8C%BB%E9%99%A2%E6%8F%90%E5%87%BA%E7%9A%84%E7%A7%91%E5%AD%A6%E5%87%8F%E9%87%8D%E6%96%B9%E6%B3%95%23) `158.2K 🔥` `-42%`
1. [阿富汗使用重型武器打击巴基斯坦](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%AF%8C%E6%B1%97%E4%BD%BF%E7%94%A8%E9%87%8D%E5%9E%8B%E6%AD%A6%E5%99%A8%E6%89%93%E5%87%BB%E5%B7%B4%E5%9F%BA%E6%96%AF%E5%9D%A6%23) `156.1K 🔥` `-42%`

Updated at 2026-03-02 12:30:12

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
