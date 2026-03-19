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

1. [1分钟被路虎别停8次当事人发声 (The person involved was stopped by Land Rover 8 times in 1 minute and spoke out)](https://s.weibo.com/weibo?q=%231%E5%88%86%E9%92%9F%E8%A2%AB%E8%B7%AF%E8%99%8E%E5%88%AB%E5%81%9C8%E6%AC%A1%E5%BD%93%E4%BA%8B%E4%BA%BA%E5%8F%91%E5%A3%B0%23) `257.7K 🔥` `NEW`
1. [亲爱的客栈](https://s.weibo.com/weibo?q=%23%E4%BA%B2%E7%88%B1%E7%9A%84%E5%AE%A2%E6%A0%88%23) `162.7K 🔥` `NEW`
1. [何与薯香鸡排夯爆了](https://s.weibo.com/weibo?q=%23%E4%BD%95%E4%B8%8E%E8%96%AF%E9%A6%99%E9%B8%A1%E6%8E%92%E5%A4%AF%E7%88%86%E4%BA%86%23) `150.5K 🔥` `NEW`
1. [在公司点奶茶差点被劝退了](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%85%AC%E5%8F%B8%E7%82%B9%E5%A5%B6%E8%8C%B6%E5%B7%AE%E7%82%B9%E8%A2%AB%E5%8A%9D%E9%80%80%E4%BA%86%23) `150.3K 🔥` `NEW`
1. [99岁独居老人突然说舍不得死了](https://s.weibo.com/weibo?q=%2399%E5%B2%81%E7%8B%AC%E5%B1%85%E8%80%81%E4%BA%BA%E7%AA%81%E7%84%B6%E8%AF%B4%E8%88%8D%E4%B8%8D%E5%BE%97%E6%AD%BB%E4%BA%86%23) `149.8K 🔥` `NEW`
1. [今天适合把春天装进工位](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E9%80%82%E5%90%88%E6%8A%8A%E6%98%A5%E5%A4%A9%E8%A3%85%E8%BF%9B%E5%B7%A5%E4%BD%8D%23) `148.3K 🔥` `NEW`
1. [迪丽热巴 郝阿三](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%20%E9%83%9D%E9%98%BF%E4%B8%89%23) `140.3K 🔥` `NEW`
1. [AI观众 AI粉丝 AI打分](https://s.weibo.com/weibo?q=%23AI%E8%A7%82%E4%BC%97%20AI%E7%B2%89%E4%B8%9D%20AI%E6%89%93%E5%88%86%23) `132.3K 🔥` `NEW`
1. [市场预期彻底变了](https://s.weibo.com/weibo?q=%23%E5%B8%82%E5%9C%BA%E9%A2%84%E6%9C%9F%E5%BD%BB%E5%BA%95%E5%8F%98%E4%BA%86%23) `95.0K 🔥` `NEW`
1. [银行开始劝退炒金客](https://s.weibo.com/weibo?q=%23%E9%93%B6%E8%A1%8C%E5%BC%80%E5%A7%8B%E5%8A%9D%E9%80%80%E7%82%92%E9%87%91%E5%AE%A2%23) `91.9K 🔥` `NEW`
1. [迪丽热巴新经纪人曾发文怼孙茜 (Dilireba’s new agent once posted a message to criticize Sun Qian)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%96%B0%E7%BB%8F%E7%BA%AA%E4%BA%BA%E6%9B%BE%E5%8F%91%E6%96%87%E6%80%BC%E5%AD%99%E8%8C%9C%23) `89.3K 🔥` `NEW`
1. [到底要睡多久才能不困](https://s.weibo.com/weibo?q=%23%E5%88%B0%E5%BA%95%E8%A6%81%E7%9D%A1%E5%A4%9A%E4%B9%85%E6%89%8D%E8%83%BD%E4%B8%8D%E5%9B%B0%23) `81.2K 🔥` `NEW`
1. [黄金越跌消费者越抢](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E8%B6%8A%E8%B7%8C%E6%B6%88%E8%B4%B9%E8%80%85%E8%B6%8A%E6%8A%A2%23) `79.6K 🔥` `NEW`
1. [生化危机制作人回应隐藏彩蛋](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%8C%96%E5%8D%B1%E6%9C%BA%E5%88%B6%E4%BD%9C%E4%BA%BA%E5%9B%9E%E5%BA%94%E9%9A%90%E8%97%8F%E5%BD%A9%E8%9B%8B%23) `77.5K 🔥` `NEW`
1. [孔雪儿看肌肉秒认田曦薇卢昱晓](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E7%9C%8B%E8%82%8C%E8%82%89%E7%A7%92%E8%AE%A4%E7%94%B0%E6%9B%A6%E8%96%87%E5%8D%A2%E6%98%B1%E6%99%93%23) `73.8K 🔥` `NEW`
1. [奶奶减肥法或致肌肉流失代谢下降](https://s.weibo.com/weibo?q=%23%E5%A5%B6%E5%A5%B6%E5%87%8F%E8%82%A5%E6%B3%95%E6%88%96%E8%87%B4%E8%82%8C%E8%82%89%E6%B5%81%E5%A4%B1%E4%BB%A3%E8%B0%A2%E4%B8%8B%E9%99%8D%23) `66.5K 🔥` `NEW`
1. [男子印尼做团播月入45万美元](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%8D%B0%E5%B0%BC%E5%81%9A%E5%9B%A2%E6%92%AD%E6%9C%88%E5%85%A545%E4%B8%87%E7%BE%8E%E5%85%83%23) `65.2K 🔥` `NEW`
1. [乌克兰暴力征兵画面曝光](https://s.weibo.com/weibo?q=%23%E4%B9%8C%E5%85%8B%E5%85%B0%E6%9A%B4%E5%8A%9B%E5%BE%81%E5%85%B5%E7%94%BB%E9%9D%A2%E6%9B%9D%E5%85%89%23) `1.1M 🔥` `+860%`
1. [蓝莓价格大跳水了 (Blueberry prices plummet)](https://s.weibo.com/weibo?q=%23%E8%93%9D%E8%8E%93%E4%BB%B7%E6%A0%BC%E5%A4%A7%E8%B7%B3%E6%B0%B4%E4%BA%86%23) `797.1K 🔥` `+125%`
1. [男生热水烫开奶茶袋藏天南地图](https://s.weibo.com/weibo?q=%23%E7%94%B7%E7%94%9F%E7%83%AD%E6%B0%B4%E7%83%AB%E5%BC%80%E5%A5%B6%E8%8C%B6%E8%A2%8B%E8%97%8F%E5%A4%A9%E5%8D%97%E5%9C%B0%E5%9B%BE%23) `148.7K 🔥` `+31%`
1. [不运动也能减重的7个方法](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%BF%90%E5%8A%A8%E4%B9%9F%E8%83%BD%E5%87%8F%E9%87%8D%E7%9A%847%E4%B8%AA%E6%96%B9%E6%B3%95%23) `135.0K 🔥` `+83%`
1. [小狗突然关机 (Puppy suddenly shuts down)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E7%AA%81%E7%84%B6%E5%85%B3%E6%9C%BA%23) `98.3K 🔥` `+44%`
1. [中国人种树太硬核](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BA%BA%E7%A7%8D%E6%A0%91%E5%A4%AA%E7%A1%AC%E6%A0%B8%23) `625.0K 🔥`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `140.2K 🔥`
1. [瞿颖与老公未领证未举办婚礼](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E4%B8%8E%E8%80%81%E5%85%AC%E6%9C%AA%E9%A2%86%E8%AF%81%E6%9C%AA%E4%B8%BE%E5%8A%9E%E5%A9%9A%E7%A4%BC%23) `80.2K 🔥`
1. [男孩讲述被生父继母塞后备箱细节](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E8%AE%B2%E8%BF%B0%E8%A2%AB%E7%94%9F%E7%88%B6%E7%BB%A7%E6%AF%8D%E5%A1%9E%E5%90%8E%E5%A4%87%E7%AE%B1%E7%BB%86%E8%8A%82%23) `80.1K 🔥`
1. [买橘朵上拼多多好价不用等 (Buy orange blossoms at a good price on Pinduoduo without having to wait.)](https://s.weibo.com/weibo?q=%23%E4%B9%B0%E6%A9%98%E6%9C%B5%E4%B8%8A%E6%8B%BC%E5%A4%9A%E5%A4%9A%E5%A5%BD%E4%BB%B7%E4%B8%8D%E7%94%A8%E7%AD%89%23) `298.1K 🔥` `-22%`
1. [委内瑞拉击败美国夺冠 全国放假一天 (Venezuela beats the United States to win the championship and the country has a day off)](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E5%87%BB%E8%B4%A5%E7%BE%8E%E5%9B%BD%E5%A4%BA%E5%86%A0%20%E5%85%A8%E5%9B%BD%E6%94%BE%E5%81%87%E4%B8%80%E5%A4%A9%23) `152.1K 🔥` `-55%`
1. [逐玉26集封神](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%8926%E9%9B%86%E5%B0%81%E7%A5%9E%23) `150.2K 🔥` `-46%`
1. [美将只剩一艘航母用于对伊朗袭击](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%B0%86%E5%8F%AA%E5%89%A9%E4%B8%80%E8%89%98%E8%88%AA%E6%AF%8D%E7%94%A8%E4%BA%8E%E5%AF%B9%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%23) `149.5K 🔥` `-46%`
1. [岳雨婷直播美颜掉了](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E9%9B%A8%E5%A9%B7%E7%9B%B4%E6%92%AD%E7%BE%8E%E9%A2%9C%E6%8E%89%E4%BA%86%23) `149.5K 🔥` `-43%`
1. [演唱会恐怖游轮](https://s.weibo.com/weibo?q=%23%E6%BC%94%E5%94%B1%E4%BC%9A%E6%81%90%E6%80%96%E6%B8%B8%E8%BD%AE%23) `149.2K 🔥` `-86%`
1. [任敏10年前考上全球前十表演学校](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E6%95%8F10%E5%B9%B4%E5%89%8D%E8%80%83%E4%B8%8A%E5%85%A8%E7%90%83%E5%89%8D%E5%8D%81%E8%A1%A8%E6%BC%94%E5%AD%A6%E6%A0%A1%23) `148.7K 🔥` `-41%`
1. [张凌赫杂志 (Zhang Linghe Magazine)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%9D%82%E5%BF%97%23) `147.9K 🔥` `-42%`
1. [周杰伦新专 圣诞星](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%96%B0%E4%B8%93%20%E5%9C%A3%E8%AF%9E%E6%98%9F%23) `147.8K 🔥` `-42%`
1. [油价 (oil price)](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%23) `147.4K 🔥` `-41%`
1. [AI演员 粉丝](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%20%E7%B2%89%E4%B8%9D%23) `147.3K 🔥` `-21%`
1. [我把协和大夫的笔顺走了](https://s.weibo.com/weibo?q=%23%E6%88%91%E6%8A%8A%E5%8D%8F%E5%92%8C%E5%A4%A7%E5%A4%AB%E7%9A%84%E7%AC%94%E9%A1%BA%E8%B5%B0%E4%BA%86%23) `144.5K 🔥` `-50%`
1. [原来命运真的有伏笔](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%91%BD%E8%BF%90%E7%9C%9F%E7%9A%84%E6%9C%89%E4%BC%8F%E7%AC%94%23) `132.1K 🔥` `-30%`
1. [赵丽颖喜欢自己的新发型 (Zhao Liying likes her new hairstyle)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E5%96%9C%E6%AC%A2%E8%87%AA%E5%B7%B1%E7%9A%84%E6%96%B0%E5%8F%91%E5%9E%8B%23) `122.7K 🔥` `-50%`
1. [李卿 上桌](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%8D%BF%20%E4%B8%8A%E6%A1%8C%23) `117.1K 🔥` `-59%`
1. [金价下跌也买不到](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E4%B8%8B%E8%B7%8C%E4%B9%9F%E4%B9%B0%E4%B8%8D%E5%88%B0%23) `101.8K 🔥` `-47%`
1. [妻子肺癌晚期求丈夫送至安宁病房 (Wife’s terminal lung cancer begs her husband to send her to hospice ward)](https://s.weibo.com/weibo?q=%23%E5%A6%BB%E5%AD%90%E8%82%BA%E7%99%8C%E6%99%9A%E6%9C%9F%E6%B1%82%E4%B8%88%E5%A4%AB%E9%80%81%E8%87%B3%E5%AE%89%E5%AE%81%E7%97%85%E6%88%BF%23) `100.3K 🔥` `-51%`
1. [北大毕业送外卖男子称自己眼高手低](https://s.weibo.com/weibo?q=%23%E5%8C%97%E5%A4%A7%E6%AF%95%E4%B8%9A%E9%80%81%E5%A4%96%E5%8D%96%E7%94%B7%E5%AD%90%E7%A7%B0%E8%87%AA%E5%B7%B1%E7%9C%BC%E9%AB%98%E6%89%8B%E4%BD%8E%23) `98.8K 🔥` `-61%`
1. [何穗产后掉眉毛睫毛](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%A9%97%E4%BA%A7%E5%90%8E%E6%8E%89%E7%9C%89%E6%AF%9B%E7%9D%AB%E6%AF%9B%23) `91.4K 🔥` `-26%`
1. [贾国龙创办新品牌承接部分西贝员工](https://s.weibo.com/weibo?q=%23%E8%B4%BE%E5%9B%BD%E9%BE%99%E5%88%9B%E5%8A%9E%E6%96%B0%E5%93%81%E7%89%8C%E6%89%BF%E6%8E%A5%E9%83%A8%E5%88%86%E8%A5%BF%E8%B4%9D%E5%91%98%E5%B7%A5%23) `82.7K 🔥` `-25%`
1. [瞿颖胡兵曾相约都单身就生个孩子 (Qu Ying and Hu Bing once agreed to have a baby if they were both single)](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%83%A1%E5%85%B5%E6%9B%BE%E7%9B%B8%E7%BA%A6%E9%83%BD%E5%8D%95%E8%BA%AB%E5%B0%B1%E7%94%9F%E4%B8%AA%E5%AD%A9%E5%AD%90%23) `81.3K 🔥` `-44%`
1. [4S店称吃饭超260次客户已报警 (The 4S store said the customer had called the police after eating more than 260 times.)](https://s.weibo.com/weibo?q=%234S%E5%BA%97%E7%A7%B0%E5%90%83%E9%A5%AD%E8%B6%85260%E6%AC%A1%E5%AE%A2%E6%88%B7%E5%B7%B2%E6%8A%A5%E8%AD%A6%23) `80.5K 🔥` `-70%`
1. [小米汽车 舒淇](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%B1%BD%E8%BD%A6%20%E8%88%92%E6%B7%87%23) `79.1K 🔥` `-26%`
1. [歌手2026拟邀 (Singer 2026 to be invited)](https://s.weibo.com/weibo?q=%23%E6%AD%8C%E6%89%8B2026%E6%8B%9F%E9%82%80%23) `76.4K 🔥` `-54%`
1. [伊朗发起报复行动](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%23) `68.8K 🔥` `-59%`
1. [生父回应将9岁儿子塞进后备箱](https://s.weibo.com/weibo?q=%23%E7%94%9F%E7%88%B6%E5%9B%9E%E5%BA%94%E5%B0%869%E5%B2%81%E5%84%BF%E5%AD%90%E5%A1%9E%E8%BF%9B%E5%90%8E%E5%A4%87%E7%AE%B1%23) `67.1K 🔥` `-42%`

Updated at 2026-03-19 15:14:06

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
