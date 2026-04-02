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

1. [谢娜一直不停地拉着袁咏仪说话 (Xie Na kept pulling Anita Yuen to talk)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E4%B8%80%E7%9B%B4%E4%B8%8D%E5%81%9C%E5%9C%B0%E6%8B%89%E7%9D%80%E8%A2%81%E5%92%8F%E4%BB%AA%E8%AF%B4%E8%AF%9D%23) `704.8K 🔥` `NEW`
1. [曾沛慈好高](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E6%B2%9B%E6%85%88%E5%A5%BD%E9%AB%98%23) `679.8K 🔥` `NEW`
1. [SNH48的粤剧DNA动了](https://s.weibo.com/weibo?q=%23SNH48%E7%9A%84%E7%B2%A4%E5%89%A7DNA%E5%8A%A8%E4%BA%86%23) `677.7K 🔥` `NEW`
1. [白鹿素颜做饭自拍](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E7%B4%A0%E9%A2%9C%E5%81%9A%E9%A5%AD%E8%87%AA%E6%8B%8D%23) `542.8K 🔥` `NEW`
1. [金价持续大蹦极](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%8C%81%E7%BB%AD%E5%A4%A7%E8%B9%A6%E6%9E%81%23) `236.4K 🔥` `NEW`
1. [齐思钧唱够爱吓曾沛慈一跳](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%80%9D%E9%92%A7%E5%94%B1%E5%A4%9F%E7%88%B1%E5%90%93%E6%9B%BE%E6%B2%9B%E6%85%88%E4%B8%80%E8%B7%B3%23) `226.1K 🔥` `NEW`
1. [邓凯要还车贷交社保把自己说生气了](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E8%A6%81%E8%BF%98%E8%BD%A6%E8%B4%B7%E4%BA%A4%E7%A4%BE%E4%BF%9D%E6%8A%8A%E8%87%AA%E5%B7%B1%E8%AF%B4%E7%94%9F%E6%B0%94%E4%BA%86%23) `220.2K 🔥` `NEW`
1. [师父发现张雪没赛车天赋让他造车](https://s.weibo.com/weibo?q=%23%E5%B8%88%E7%88%B6%E5%8F%91%E7%8E%B0%E5%BC%A0%E9%9B%AA%E6%B2%A1%E8%B5%9B%E8%BD%A6%E5%A4%A9%E8%B5%8B%E8%AE%A9%E4%BB%96%E9%80%A0%E8%BD%A6%23) `220.1K 🔥` `NEW`
1. [张凌赫后面还有两部待播将军剧](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%90%8E%E9%9D%A2%E8%BF%98%E6%9C%89%E4%B8%A4%E9%83%A8%E5%BE%85%E6%92%AD%E5%B0%86%E5%86%9B%E5%89%A7%23) `212.4K 🔥` `NEW`
1. [失眠花6000买进口药吃出违禁成分](https://s.weibo.com/weibo?q=%23%E5%A4%B1%E7%9C%A0%E8%8A%B16000%E4%B9%B0%E8%BF%9B%E5%8F%A3%E8%8D%AF%E5%90%83%E5%87%BA%E8%BF%9D%E7%A6%81%E6%88%90%E5%88%86%23) `202.3K 🔥` `NEW`
1. [为什么很难吃到小时候的老派水果了 (Why is it so hard to eat the old-school fruits from my childhood?)](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E5%BE%88%E9%9A%BE%E5%90%83%E5%88%B0%E5%B0%8F%E6%97%B6%E5%80%99%E7%9A%84%E8%80%81%E6%B4%BE%E6%B0%B4%E6%9E%9C%E4%BA%86%23) `151.3K 🔥` `NEW`
1. [范玮琪对王俊凯说你也唱过我的歌](https://s.weibo.com/weibo?q=%23%E8%8C%83%E7%8E%AE%E7%90%AA%E5%AF%B9%E7%8E%8B%E4%BF%8A%E5%87%AF%E8%AF%B4%E4%BD%A0%E4%B9%9F%E5%94%B1%E8%BF%87%E6%88%91%E7%9A%84%E6%AD%8C%23) `150.1K 🔥` `NEW`
1. [张雪称卖陈光标劳斯莱斯捐款天使嫣然](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E7%A7%B0%E5%8D%96%E9%99%88%E5%85%89%E6%A0%87%E5%8A%B3%E6%96%AF%E8%8E%B1%E6%96%AF%E6%8D%90%E6%AC%BE%E5%A4%A9%E4%BD%BF%E5%AB%A3%E7%84%B6%23) `127.6K 🔥` `NEW`
1. [唐艺昕陶昕然 宝娟我的嗓子](https://s.weibo.com/weibo?q=%23%E5%94%90%E8%89%BA%E6%98%95%E9%99%B6%E6%98%95%E7%84%B6%20%E5%AE%9D%E5%A8%9F%E6%88%91%E7%9A%84%E5%97%93%E5%AD%90%23) `122.9K 🔥` `NEW`
1. [DYG纪录片](https://s.weibo.com/weibo?q=%23DYG%E7%BA%AA%E5%BD%95%E7%89%87%23) `122.8K 🔥` `NEW`
1. [王安宇 宽肩窄腰](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%20%E5%AE%BD%E8%82%A9%E7%AA%84%E8%85%B0%23) `119.8K 🔥` `NEW`
1. [李若彤与辉同行等要为优思益担责吗](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8B%A5%E5%BD%A4%E4%B8%8E%E8%BE%89%E5%90%8C%E8%A1%8C%E7%AD%89%E8%A6%81%E4%B8%BA%E4%BC%98%E6%80%9D%E7%9B%8A%E6%8B%85%E8%B4%A3%E5%90%97%23) `117.6K 🔥` `NEW`
1. [张雪债务刚还清](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%80%BA%E5%8A%A1%E5%88%9A%E8%BF%98%E6%B8%85%23) `116.8K 🔥` `NEW`
1. [浪姐初见面万千惠第一个出场](https://s.weibo.com/weibo?q=%23%E6%B5%AA%E5%A7%90%E5%88%9D%E8%A7%81%E9%9D%A2%E4%B8%87%E5%8D%83%E6%83%A0%E7%AC%AC%E4%B8%80%E4%B8%AA%E5%87%BA%E5%9C%BA%23) `116.0K 🔥` `NEW`
1. [向鱼哭了](https://s.weibo.com/weibo?q=%23%E5%90%91%E9%B1%BC%E5%93%AD%E4%BA%86%23) `114.0K 🔥` `NEW`
1. [DYG止步春季赛六强 (DYG stopped in the top six of the Spring Split)](https://s.weibo.com/weibo?q=%23DYG%E6%AD%A2%E6%AD%A5%E6%98%A5%E5%AD%A3%E8%B5%9B%E5%85%AD%E5%BC%BA%23) `111.5K 🔥` `NEW`
1. [王濛 浪姐直播太磨叽了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%20%E6%B5%AA%E5%A7%90%E7%9B%B4%E6%92%AD%E5%A4%AA%E7%A3%A8%E5%8F%BD%E4%BA%86%23) `1.5M 🔥` `+1442%`
1. [佛山鸡煲太火爆老板开小号黑自己](https://s.weibo.com/weibo?q=%23%E4%BD%9B%E5%B1%B1%E9%B8%A1%E7%85%B2%E5%A4%AA%E7%81%AB%E7%88%86%E8%80%81%E6%9D%BF%E5%BC%80%E5%B0%8F%E5%8F%B7%E9%BB%91%E8%87%AA%E5%B7%B1%23) `926.8K 🔥` `+703%`
1. [卫龙全球品牌代言人时代少年团 (Weilong Global Brand Spokesperson Times Youth League)](https://s.weibo.com/weibo?q=%23%E5%8D%AB%E9%BE%99%E5%85%A8%E7%90%83%E5%93%81%E7%89%8C%E4%BB%A3%E8%A8%80%E4%BA%BA%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%23) `705.4K 🔥` `+73%`
1. [美国头大了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%A4%B4%E5%A4%A7%E4%BA%86%23) `695.9K 🔥` `+468%`
1. [三部门约谈抖音淘天小红书 (Three departments interviewed Douyin, Taotian and Xiaohongshu)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E9%83%A8%E9%97%A8%E7%BA%A6%E8%B0%88%E6%8A%96%E9%9F%B3%E6%B7%98%E5%A4%A9%E5%B0%8F%E7%BA%A2%E4%B9%A6%23) `643.5K 🔥` `+145%`
1. [博主嘴唇发紫粉丝隔空诊出心脏病](https://s.weibo.com/weibo?q=%23%E5%8D%9A%E4%B8%BB%E5%98%B4%E5%94%87%E5%8F%91%E7%B4%AB%E7%B2%89%E4%B8%9D%E9%9A%94%E7%A9%BA%E8%AF%8A%E5%87%BA%E5%BF%83%E8%84%8F%E7%97%85%23) `630.8K 🔥` `+379%`
1. [迪丽热巴 古偶](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%20%E5%8F%A4%E5%81%B6%23) `615.0K 🔥` `+101%`
1. [iPhone18Pro模具偷跑](https://s.weibo.com/weibo?q=%23iPhone18Pro%E6%A8%A1%E5%85%B7%E5%81%B7%E8%B7%91%23) `598.3K 🔥` `+208%`
1. [王俊凯送考徐洁儿](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E9%80%81%E8%80%83%E5%BE%90%E6%B4%81%E5%84%BF%23) `568.0K 🔥` `+130%`
1. [伊朗袭击美军隐秘据点致37人死亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%E9%9A%90%E7%A7%98%E6%8D%AE%E7%82%B9%E8%87%B437%E4%BA%BA%E6%AD%BB%E4%BA%A1%23) `523.5K 🔥` `+114%`
1. [伊朗航空航天部队司令巡视地下导弹基地](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%88%AA%E7%A9%BA%E8%88%AA%E5%A4%A9%E9%83%A8%E9%98%9F%E5%8F%B8%E4%BB%A4%E5%B7%A1%E8%A7%86%E5%9C%B0%E4%B8%8B%E5%AF%BC%E5%BC%B9%E5%9F%BA%E5%9C%B0%23) `511.6K 🔥` `+96%`
1. [谢娜控场能力 (Xie Na's field control ability)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E6%8E%A7%E5%9C%BA%E8%83%BD%E5%8A%9B%23) `491.9K 🔥` `+102%`
1. [老式水果为什么消失了](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%BC%8F%E6%B0%B4%E6%9E%9C%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B6%88%E5%A4%B1%E4%BA%86%23) `459.2K 🔥` `+313%`
1. [孙颖莎2比7落后完成逆转](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E2%E6%AF%947%E8%90%BD%E5%90%8E%E5%AE%8C%E6%88%90%E9%80%86%E8%BD%AC%23) `454.1K 🔥` `+76%`
1. [张元英下巴](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%85%83%E8%8B%B1%E4%B8%8B%E5%B7%B4%23) `452.2K 🔥` `+246%`
1. [夏克立回应再婚生女](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E5%85%8B%E7%AB%8B%E5%9B%9E%E5%BA%94%E5%86%8D%E5%A9%9A%E7%94%9F%E5%A5%B3%23) `220.1K 🔥` `+69%`
1. [李荣浩方否认恋人抄袭 (Li Ronghao denies plagiarism by his lover)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8D%A3%E6%B5%A9%E6%96%B9%E5%90%A6%E8%AE%A4%E6%81%8B%E4%BA%BA%E6%8A%84%E8%A2%AD%23) `200.5K 🔥` `+53%`
1. [女子20万买170g金条藏豆瓣酱里 (Woman buys 170g gold bars for RMB 200,000 and hides them in Doubanjiang)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%9020%E4%B8%87%E4%B9%B0170g%E9%87%91%E6%9D%A1%E8%97%8F%E8%B1%86%E7%93%A3%E9%85%B1%E9%87%8C%23) `121.2K 🔥` `+56%`
1. [以色列遭到开战以来最大规模导弹袭击](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E9%81%AD%E5%88%B0%E5%BC%80%E6%88%98%E4%BB%A5%E6%9D%A5%E6%9C%80%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%23) `120.2K 🔥` `+21%`
1. [你好1983结局](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD1983%E7%BB%93%E5%B1%80%23) `113.7K 🔥` `+29%`
1. [被时代淘汰的水果](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E6%97%B6%E4%BB%A3%E6%B7%98%E6%B1%B0%E7%9A%84%E6%B0%B4%E6%9E%9C%23) `110.8K 🔥` `+30%`
1. [多城实施住房公积金新政](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9F%8E%E5%AE%9E%E6%96%BD%E4%BD%8F%E6%88%BF%E5%85%AC%E7%A7%AF%E9%87%91%E6%96%B0%E6%94%BF%23) `709.2K 🔥`
1. [与辉同行致歉](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E8%BE%89%E5%90%8C%E8%A1%8C%E8%87%B4%E6%AD%89%23) `667.9K 🔥`
1. [优思益 (Yousiyi)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `651.7K 🔥`
1. [张天爱变样了 (Zhang Tianai has changed)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%A4%A9%E7%88%B1%E5%8F%98%E6%A0%B7%E4%BA%86%23) `619.8K 🔥`
1. [陈妍希方致歉](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A6%8D%E5%B8%8C%E6%96%B9%E8%87%B4%E6%AD%89%23) `137.7K 🔥`
1. [阿瑟不卖的时候反耳嗑到了](https://s.weibo.com/weibo?q=%23%E9%98%BF%E7%91%9F%E4%B8%8D%E5%8D%96%E7%9A%84%E6%97%B6%E5%80%99%E5%8F%8D%E8%80%B3%E5%97%91%E5%88%B0%E4%BA%86%23) `118.6K 🔥`
1. [乘风直播时长 (Chengfeng live broadcast duration)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E%E7%9B%B4%E6%92%AD%E6%97%B6%E9%95%BF%23) `115.0K 🔥`
1. [发明这个咖啡喝法的简直是天才](https://s.weibo.com/weibo?q=%23%E5%8F%91%E6%98%8E%E8%BF%99%E4%B8%AA%E5%92%96%E5%95%A1%E5%96%9D%E6%B3%95%E7%9A%84%E7%AE%80%E7%9B%B4%E6%98%AF%E5%A4%A9%E6%89%8D%23) `112.4K 🔥`
1. [乘风直播节奏好慢 (Chengfeng live broadcast is so slow)](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E%E7%9B%B4%E6%92%AD%E8%8A%82%E5%A5%8F%E5%A5%BD%E6%85%A2%23) `348.9K 🔥` `-69%`
1. [刘亦菲几乎没有法令纹](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E5%87%A0%E4%B9%8E%E6%B2%A1%E6%9C%89%E6%B3%95%E4%BB%A4%E7%BA%B9%23) `153.3K 🔥` `-34%`

Updated at 2026-04-02 22:42:54

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
