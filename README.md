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

1. [将门独后开机 (Turn on the door alone)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%BC%80%E6%9C%BA%23) `2.2M 🔥` `NEW`
1. [将门独后官宣王鹤棣孟子义](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%AE%98%E5%AE%A3%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AD%9F%E5%AD%90%E4%B9%89%23) `710.5K 🔥` `NEW`
1. [谷爱凌说不是故意吓大家](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%AF%B4%E4%B8%8D%E6%98%AF%E6%95%85%E6%84%8F%E5%90%93%E5%A4%A7%E5%AE%B6%23) `541.2K 🔥` `NEW`
1. [将门毒后](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%23) `464.1K 🔥` `NEW`
1. [大年初四 扔穷](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E5%9B%9B%20%E6%89%94%E7%A9%B7%23) `366.1K 🔥` `NEW`
1. [谷爱凌说我快累死了](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%AF%B4%E6%88%91%E5%BF%AB%E7%B4%AF%E6%AD%BB%E4%BA%86%23) `273.9K 🔥` `NEW`
1. [将门独后造型](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E9%80%A0%E5%9E%8B%23) `257.6K 🔥` `NEW`
1. [吴京 我的夫人姓谢](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E6%88%91%E7%9A%84%E5%A4%AB%E4%BA%BA%E5%A7%93%E8%B0%A2%23) `246.1K 🔥` `NEW`
1. [原来亲戚们都是故意的](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E4%BA%B2%E6%88%9A%E4%BB%AC%E9%83%BD%E6%98%AF%E6%95%85%E6%84%8F%E7%9A%84%23) `236.8K 🔥` `NEW`
1. [顾客称被桔子酒店短信恐吓](https://s.weibo.com/weibo?q=%23%E9%A1%BE%E5%AE%A2%E7%A7%B0%E8%A2%AB%E6%A1%94%E5%AD%90%E9%85%92%E5%BA%97%E7%9F%AD%E4%BF%A1%E6%81%90%E5%90%93%23) `230.6K 🔥` `NEW`
1. [中国队3金3银4铜 (Chinese team 3 golds, 3 silvers and 4 bronzes)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F3%E9%87%913%E9%93%B64%E9%93%9C%23) `220.0K 🔥` `NEW`
1. [恩利庾澄庆拜年](https://s.weibo.com/weibo?q=%23%E6%81%A9%E5%88%A9%E5%BA%BE%E6%BE%84%E5%BA%86%E6%8B%9C%E5%B9%B4%23) `165.8K 🔥` `NEW`
1. [郭晶晶记不清结婚多少年](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%B6%E6%99%B6%E8%AE%B0%E4%B8%8D%E6%B8%85%E7%BB%93%E5%A9%9A%E5%A4%9A%E5%B0%91%E5%B9%B4%23) `148.6K 🔥` `NEW`
1. [谷爱凌为好友受伤而落泪](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E4%B8%BA%E5%A5%BD%E5%8F%8B%E5%8F%97%E4%BC%A4%E8%80%8C%E8%90%BD%E6%B3%AA%23) `127.9K 🔥` `NEW`
1. [特朗普称奥巴马涉外星人言论泄密](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E5%A5%A5%E5%B7%B4%E9%A9%AC%E6%B6%89%E5%A4%96%E6%98%9F%E4%BA%BA%E8%A8%80%E8%AE%BA%E6%B3%84%E5%AF%86%23) `124.9K 🔥` `NEW`
1. [一中国公民在奥克兰街头直播被打](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E5%9C%A8%E5%A5%A5%E5%85%8B%E5%85%B0%E8%A1%97%E5%A4%B4%E7%9B%B4%E6%92%AD%E8%A2%AB%E6%89%93%23) `123.6K 🔥` `NEW`
1. [马丽中国电影票房最高女主](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E4%B8%BD%E4%B8%AD%E5%9B%BD%E7%94%B5%E5%BD%B1%E7%A5%A8%E6%88%BF%E6%9C%80%E9%AB%98%E5%A5%B3%E4%B8%BB%23) `121.0K 🔥` `NEW`
1. [宁忠岩确认夺冠一刻](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E7%A1%AE%E8%AE%A4%E5%A4%BA%E5%86%A0%E4%B8%80%E5%88%BB%23) `120.5K 🔥` `NEW`
1. [镖人 CP佛跳墙](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%20CP%E4%BD%9B%E8%B7%B3%E5%A2%99%23) `116.5K 🔥` `NEW`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `97.8K 🔥` `NEW`
1. [春节机器人卖爆了 (Robots sold out during the Spring Festival)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%8D%96%E7%88%86%E4%BA%86%23) `93.6K 🔥` `NEW`
1. [一家三口返乡途中患病儿子突然离世](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B6%E4%B8%89%E5%8F%A3%E8%BF%94%E4%B9%A1%E9%80%94%E4%B8%AD%E6%82%A3%E7%97%85%E5%84%BF%E5%AD%90%E7%AA%81%E7%84%B6%E7%A6%BB%E4%B8%96%23) `91.4K 🔥` `NEW`
1. [男子自办春晚1天走完17家亲戚](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%87%AA%E5%8A%9E%E6%98%A5%E6%99%9A1%E5%A4%A9%E8%B5%B0%E5%AE%8C17%E5%AE%B6%E4%BA%B2%E6%88%9A%23) `91.2K 🔥` `NEW`
1. [王阳跳屋顶着火身材好曼妙](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%98%B3%E8%B7%B3%E5%B1%8B%E9%A1%B6%E7%9D%80%E7%81%AB%E8%BA%AB%E6%9D%90%E5%A5%BD%E6%9B%BC%E5%A6%99%23) `89.5K 🔥` `NEW`
1. [小狗醒了但是小狗想睡懒觉](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E9%86%92%E4%BA%86%E4%BD%86%E6%98%AF%E5%B0%8F%E7%8B%97%E6%83%B3%E7%9D%A1%E6%87%92%E8%A7%89%23) `89.0K 🔥` `NEW`
1. [女子骑摩托失控坠坡画面火出圈](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E9%AA%91%E6%91%A9%E6%89%98%E5%A4%B1%E6%8E%A7%E5%9D%A0%E5%9D%A1%E7%94%BB%E9%9D%A2%E7%81%AB%E5%87%BA%E5%9C%88%23) `86.0K 🔥` `NEW`
1. [初四全国人民各有各的忙](https://s.weibo.com/weibo?q=%23%E5%88%9D%E5%9B%9B%E5%85%A8%E5%9B%BD%E4%BA%BA%E6%B0%91%E5%90%84%E6%9C%89%E5%90%84%E7%9A%84%E5%BF%99%23) `74.4K 🔥` `NEW`
1. [文俊辉掉头就走](https://s.weibo.com/weibo?q=%23%E6%96%87%E4%BF%8A%E8%BE%89%E6%8E%89%E5%A4%B4%E5%B0%B1%E8%B5%B0%23) `72.3K 🔥` `NEW`
1. [阿育娅 少女的葬礼女王的加冕](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%82%B2%E5%A8%85%20%E5%B0%91%E5%A5%B3%E7%9A%84%E8%91%AC%E7%A4%BC%E5%A5%B3%E7%8E%8B%E7%9A%84%E5%8A%A0%E5%86%95%23) `72.2K 🔥` `NEW`
1. [特朗普将解密外星生命相关文件](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E5%B0%86%E8%A7%A3%E5%AF%86%E5%A4%96%E6%98%9F%E7%94%9F%E5%91%BD%E7%9B%B8%E5%85%B3%E6%96%87%E4%BB%B6%23) `72.1K 🔥` `NEW`
1. [生命树白菊除了杨紫没考虑过别的演员 (I didn't consider any other actors besides Yang Zi for White Juju, the Tree of Life.)](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%E7%99%BD%E8%8F%8A%E9%99%A4%E4%BA%86%E6%9D%A8%E7%B4%AB%E6%B2%A1%E8%80%83%E8%99%91%E8%BF%87%E5%88%AB%E7%9A%84%E6%BC%94%E5%91%98%23) `72.1K 🔥` `NEW`
1. [俄愿用10亿美元冻结资金重建加沙](https://s.weibo.com/weibo?q=%23%E4%BF%84%E6%84%BF%E7%94%A810%E4%BA%BF%E7%BE%8E%E5%85%83%E5%86%BB%E7%BB%93%E8%B5%84%E9%87%91%E9%87%8D%E5%BB%BA%E5%8A%A0%E6%B2%99%23) `69.9K 🔥` `NEW`
1. [刘昊然票房成绩](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%98%8A%E7%84%B6%E7%A5%A8%E6%88%BF%E6%88%90%E7%BB%A9%23) `69.2K 🔥` `NEW`
1. [火箭vs黄蜂](https://s.weibo.com/weibo?q=%23%E7%81%AB%E7%AE%ADvs%E9%BB%84%E8%9C%82%23) `69.1K 🔥` `NEW`
1. [善良的人无法理解坏](https://s.weibo.com/weibo?q=%23%E5%96%84%E8%89%AF%E7%9A%84%E4%BA%BA%E6%97%A0%E6%B3%95%E7%90%86%E8%A7%A3%E5%9D%8F%23) `68.8K 🔥` `NEW`
1. [欧洲代表团只能在酒店等待](https://s.weibo.com/weibo?q=%23%E6%AC%A7%E6%B4%B2%E4%BB%A3%E8%A1%A8%E5%9B%A2%E5%8F%AA%E8%83%BD%E5%9C%A8%E9%85%92%E5%BA%97%E7%AD%89%E5%BE%85%23) `67.2K 🔥` `NEW`
1. [女子回应因骑摩托飞下山坡意外走红](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%9B%9E%E5%BA%94%E5%9B%A0%E9%AA%91%E6%91%A9%E6%89%98%E9%A3%9E%E4%B8%8B%E5%B1%B1%E5%9D%A1%E6%84%8F%E5%A4%96%E8%B5%B0%E7%BA%A2%23) `66.5K 🔥` `NEW`
1. [去男朋友家害怕独处belike](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E7%94%B7%E6%9C%8B%E5%8F%8B%E5%AE%B6%E5%AE%B3%E6%80%95%E7%8B%AC%E5%A4%84belike%23) `66.1K 🔥` `NEW`
1. [中国队升至冬奥奖牌榜第12](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F%E5%8D%87%E8%87%B3%E5%86%AC%E5%A5%A5%E5%A5%96%E7%89%8C%E6%A6%9C%E7%AC%AC12%23) `66.0K 🔥` `NEW`
1. [刘美贤夺冠 (Liu Meixian won the championship)](https://s.weibo.com/weibo?q=%23%E5%88%98%E7%BE%8E%E8%B4%A4%E5%A4%BA%E5%86%A0%23) `960.5K 🔥` `+181%`
1. [他们在天山脚下脚踏冰河巡边 (They patrolled the glacier at the foot of the Tianshan Mountains)](https://s.weibo.com/weibo?q=%23%E4%BB%96%E4%BB%AC%E5%9C%A8%E5%A4%A9%E5%B1%B1%E8%84%9A%E4%B8%8B%E8%84%9A%E8%B8%8F%E5%86%B0%E6%B2%B3%E5%B7%A1%E8%BE%B9%23) `809.8K 🔥` `+24%`
1. [男子放炮摘除眼球称无法面对5个月女儿](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E6%94%BE%E7%82%AE%E6%91%98%E9%99%A4%E7%9C%BC%E7%90%83%E7%A7%B0%E6%97%A0%E6%B3%95%E9%9D%A2%E5%AF%B95%E4%B8%AA%E6%9C%88%E5%A5%B3%E5%84%BF%23) `176.0K 🔥` `+50%`
1. [朱志鑫左航 伯克利 (Zhu Zhixin Zuo Hang Berkeley)](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E5%B7%A6%E8%88%AA%20%E4%BC%AF%E5%85%8B%E5%88%A9%23) `123.8K 🔥` `+168%`
1. [美24岁女子假扮15岁少女诱捕警察](https://s.weibo.com/weibo?q=%23%E7%BE%8E24%E5%B2%81%E5%A5%B3%E5%AD%90%E5%81%87%E6%89%AE15%E5%B2%81%E5%B0%91%E5%A5%B3%E8%AF%B1%E6%8D%95%E8%AD%A6%E5%AF%9F%23) `119.6K 🔥` `+83%`
1. [TOP登陆少年官方后援会道歉 (TOP Login Junior Official Support Club Apologizes)](https://s.weibo.com/weibo?q=%23TOP%E7%99%BB%E9%99%86%E5%B0%91%E5%B9%B4%E5%AE%98%E6%96%B9%E5%90%8E%E6%8F%B4%E4%BC%9A%E9%81%93%E6%AD%89%23) `92.8K 🔥` `+62%`
1. [宁忠岩金牌 (Ning Zhongyan gold medal)](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E9%87%91%E7%89%8C%23) `264.6K 🔥` `-77%`
1. [谢景行 (Xie Jingxing)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E6%99%AF%E8%A1%8C%23) `188.7K 🔥` `-27%`
1. [吴京票房成绩位列第二 (Wu Jing ranks second in box office performance)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%E7%A5%A8%E6%88%BF%E6%88%90%E7%BB%A9%E4%BD%8D%E5%88%97%E7%AC%AC%E4%BA%8C%23) `144.1K 🔥` `-37%`
1. [妈妈让上交2万压岁钱孩子不干了](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E8%AE%A9%E4%B8%8A%E4%BA%A42%E4%B8%87%E5%8E%8B%E5%B2%81%E9%92%B1%E5%AD%A9%E5%AD%90%E4%B8%8D%E5%B9%B2%E4%BA%86%23) `86.6K 🔥` `-21%`
1. [王鹤棣孟子义 将门独后 (Wang Hedi and Meng Ziyi are the only queens in the general family)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AD%9F%E5%AD%90%E4%B9%89%20%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `72.6K 🔥` `-22%`

Updated at 2026-02-20 10:50:01

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
