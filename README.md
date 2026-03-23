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

1. [特朗普称推迟5天打击伊朗发电站 (Trump delays strike on Iranian power plants for 5 days)](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E6%8E%A8%E8%BF%9F5%E5%A4%A9%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%E5%8F%91%E7%94%B5%E7%AB%99%23) `288.1K 🔥` `NEW`
1. [男大学生患桃花癫一周挥霍5万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%A4%A7%E5%AD%A6%E7%94%9F%E6%82%A3%E6%A1%83%E8%8A%B1%E7%99%AB%E4%B8%80%E5%91%A8%E6%8C%A5%E9%9C%8D5%E4%B8%87%23) `284.8K 🔥` `NEW`
1. [特朗普称美伊已对话](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E7%A7%B0%E7%BE%8E%E4%BC%8A%E5%B7%B2%E5%AF%B9%E8%AF%9D%23) `162.4K 🔥` `NEW`
1. [诊所帮助摔倒残疾人反遭纠缠威胁](https://s.weibo.com/weibo?q=%23%E8%AF%8A%E6%89%80%E5%B8%AE%E5%8A%A9%E6%91%94%E5%80%92%E6%AE%8B%E7%96%BE%E4%BA%BA%E5%8F%8D%E9%81%AD%E7%BA%A0%E7%BC%A0%E5%A8%81%E8%83%81%23) `142.7K 🔥` `NEW`
1. [毛晓彤28岁时因为年龄焦虑大哭](https://s.weibo.com/weibo?q=%23%E6%AF%9B%E6%99%93%E5%BD%A428%E5%B2%81%E6%97%B6%E5%9B%A0%E4%B8%BA%E5%B9%B4%E9%BE%84%E7%84%A6%E8%99%91%E5%A4%A7%E5%93%AD%23) `120.7K 🔥` `NEW`
1. [伊朗地下设施堆放一排排导弹](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%9C%B0%E4%B8%8B%E8%AE%BE%E6%96%BD%E5%A0%86%E6%94%BE%E4%B8%80%E6%8E%92%E6%8E%92%E5%AF%BC%E5%BC%B9%23) `119.5K 🔥` `NEW`
1. [我洗头后三天的头发蓬松程度](https://s.weibo.com/weibo?q=%23%E6%88%91%E6%B4%97%E5%A4%B4%E5%90%8E%E4%B8%89%E5%A4%A9%E7%9A%84%E5%A4%B4%E5%8F%91%E8%93%AC%E6%9D%BE%E7%A8%8B%E5%BA%A6%23) `115.9K 🔥` `NEW`
1. [为什么我们要多吃水果](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E6%88%91%E4%BB%AC%E8%A6%81%E5%A4%9A%E5%90%83%E6%B0%B4%E6%9E%9C%23) `100.9K 🔥` `NEW`
1. [BLG登顶LOL战力榜](https://s.weibo.com/weibo?q=%23BLG%E7%99%BB%E9%A1%B6LOL%E6%88%98%E5%8A%9B%E6%A6%9C%23) `88.1K 🔥` `NEW`
1. [明日方舟](https://s.weibo.com/weibo?q=%23%E6%98%8E%E6%97%A5%E6%96%B9%E8%88%9F%23) `85.1K 🔥` `NEW`
1. [寿司店后厨老鼠趴在米饭边张望 (A rat in the kitchen of a sushi restaurant lies beside the rice and looks around)](https://s.weibo.com/weibo?q=%23%E5%AF%BF%E5%8F%B8%E5%BA%97%E5%90%8E%E5%8E%A8%E8%80%81%E9%BC%A0%E8%B6%B4%E5%9C%A8%E7%B1%B3%E9%A5%AD%E8%BE%B9%E5%BC%A0%E6%9C%9B%23) `82.5K 🔥` `NEW`
1. [日本街头开韩式麻辣烫](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E8%A1%97%E5%A4%B4%E5%BC%80%E9%9F%A9%E5%BC%8F%E9%BA%BB%E8%BE%A3%E7%83%AB%23) `78.0K 🔥` `NEW`
1. [在刘耀文贺峻霖面前宋亚轩都变成熟了](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%88%98%E8%80%80%E6%96%87%E8%B4%BA%E5%B3%BB%E9%9C%96%E9%9D%A2%E5%89%8D%E5%AE%8B%E4%BA%9A%E8%BD%A9%E9%83%BD%E5%8F%98%E6%88%90%E7%86%9F%E4%BA%86%23) `71.4K 🔥` `NEW`
1. [猫猫笔架](https://s.weibo.com/weibo?q=%23%E7%8C%AB%E7%8C%AB%E7%AC%94%E6%9E%B6%23) `67.9K 🔥` `NEW`
1. [当萨摩耶第一次吃蓝莓](https://s.weibo.com/weibo?q=%23%E5%BD%93%E8%90%A8%E6%91%A9%E8%80%B6%E7%AC%AC%E4%B8%80%E6%AC%A1%E5%90%83%E8%93%9D%E8%8E%93%23) `63.2K 🔥` `NEW`
1. [随元青下线](https://s.weibo.com/weibo?q=%23%E9%9A%8F%E5%85%83%E9%9D%92%E4%B8%8B%E7%BA%BF%23) `60.9K 🔥` `NEW`
1. [种地吧直播预告](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%E7%9B%B4%E6%92%AD%E9%A2%84%E5%91%8A%23) `59.1K 🔥` `NEW`
1. [面试最该问的事](https://s.weibo.com/weibo?q=%23%E9%9D%A2%E8%AF%95%E6%9C%80%E8%AF%A5%E9%97%AE%E7%9A%84%E4%BA%8B%23) `58.5K 🔥` `NEW`
1. [流量退去后的鸡排哥与网红街](https://s.weibo.com/weibo?q=%23%E6%B5%81%E9%87%8F%E9%80%80%E5%8E%BB%E5%90%8E%E7%9A%84%E9%B8%A1%E6%8E%92%E5%93%A5%E4%B8%8E%E7%BD%91%E7%BA%A2%E8%A1%97%23) `1.1M 🔥` `+1369%`
1. [你这个量叫谷饲不叫减脂](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E8%BF%99%E4%B8%AA%E9%87%8F%E5%8F%AB%E8%B0%B7%E9%A5%B2%E4%B8%8D%E5%8F%AB%E5%87%8F%E8%84%82%23) `164.0K 🔥` `+50%`
1. [李卿 内娱金宣虎 (Li Qing Internal Entertainment Kim Sun Ho)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%8D%BF%20%E5%86%85%E5%A8%B1%E9%87%91%E5%AE%A3%E8%99%8E%23) `138.8K 🔥` `+30%`
1. [关晓彤 至今不知道腿长的坏处](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%20%E8%87%B3%E4%BB%8A%E4%B8%8D%E7%9F%A5%E9%81%93%E8%85%BF%E9%95%BF%E7%9A%84%E5%9D%8F%E5%A4%84%23) `137.6K 🔥` `+27%`
1. [黄金大跌金店老板慌了](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E5%A4%A7%E8%B7%8C%E9%87%91%E5%BA%97%E8%80%81%E6%9D%BF%E6%85%8C%E4%BA%86%23) `131.4K 🔥` `+22%`
1. [男子囤33吨石脑油堪比2790斤TNT](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%9B%A433%E5%90%A8%E7%9F%B3%E8%84%91%E6%B2%B9%E5%A0%AA%E6%AF%942790%E6%96%A4TNT%23) `104.3K 🔥` `+40%`
1. [微厘空间02组卫星发射圆满成功](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E5%8E%98%E7%A9%BA%E9%97%B402%E7%BB%84%E5%8D%AB%E6%98%9F%E5%8F%91%E5%B0%84%E5%9C%86%E6%BB%A1%E6%88%90%E5%8A%9F%23) `644.7K 🔥`
1. [千问上线AI打车](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E4%B8%8A%E7%BA%BFAI%E6%89%93%E8%BD%A6%23) `351.2K 🔥`
1. [AI短剧付费后竟然变成PPT (AI short drama turns into PPT after payment)](https://s.weibo.com/weibo?q=%23AI%E7%9F%AD%E5%89%A7%E4%BB%98%E8%B4%B9%E5%90%8E%E7%AB%9F%E7%84%B6%E5%8F%98%E6%88%90PPT%23) `295.3K 🔥`
1. [教授地铁审博士论文视频海外爆火 (Video of professor reviewing doctoral thesis on subway goes viral abroad)](https://s.weibo.com/weibo?q=%23%E6%95%99%E6%8E%88%E5%9C%B0%E9%93%81%E5%AE%A1%E5%8D%9A%E5%A3%AB%E8%AE%BA%E6%96%87%E8%A7%86%E9%A2%91%E6%B5%B7%E5%A4%96%E7%88%86%E7%81%AB%23) `288.2K 🔥`
1. [周大生回应戒指印着周大金](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%A4%A7%E7%94%9F%E5%9B%9E%E5%BA%94%E6%88%92%E6%8C%87%E5%8D%B0%E7%9D%80%E5%91%A8%E5%A4%A7%E9%87%91%23) `146.4K 🔥`
1. [SM运营误发照片 (SM management mistakenly sent photos)](https://s.weibo.com/weibo?q=%23SM%E8%BF%90%E8%90%A5%E8%AF%AF%E5%8F%91%E7%85%A7%E7%89%87%23) `127.5K 🔥`
1. [TF五代 拿电话手表聊国际新闻](https://s.weibo.com/weibo?q=%23TF%E4%BA%94%E4%BB%A3%20%E6%8B%BF%E7%94%B5%E8%AF%9D%E6%89%8B%E8%A1%A8%E8%81%8A%E5%9B%BD%E9%99%85%E6%96%B0%E9%97%BB%23) `109.7K 🔥`
1. [张凌赫壁纸](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%A3%81%E7%BA%B8%23) `91.5K 🔥`
1. [王楚然 全女团队](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%20%E5%85%A8%E5%A5%B3%E5%9B%A2%E9%98%9F%23) `88.3K 🔥`
1. [情侣喝了奶茶却投诉未收到餐 (Couple drank milk tea but complained they didn't receive food)](https://s.weibo.com/weibo?q=%23%E6%83%85%E4%BE%A3%E5%96%9D%E4%BA%86%E5%A5%B6%E8%8C%B6%E5%8D%B4%E6%8A%95%E8%AF%89%E6%9C%AA%E6%94%B6%E5%88%B0%E9%A4%90%23) `61.0K 🔥`
1. [杭州金店老板劝大家别当韭菜](https://s.weibo.com/weibo?q=%23%E6%9D%AD%E5%B7%9E%E9%87%91%E5%BA%97%E8%80%81%E6%9D%BF%E5%8A%9D%E5%A4%A7%E5%AE%B6%E5%88%AB%E5%BD%93%E9%9F%AD%E8%8F%9C%23) `59.7K 🔥`
1. [对国内成品油价格采取临时调控 (Adopt temporary controls on domestic refined oil prices)](https://s.weibo.com/weibo?q=%23%E5%AF%B9%E5%9B%BD%E5%86%85%E6%88%90%E5%93%81%E6%B2%B9%E4%BB%B7%E6%A0%BC%E9%87%87%E5%8F%96%E4%B8%B4%E6%97%B6%E8%B0%83%E6%8E%A7%23) `771.3K 🔥` `-30%`
1. [去年没换手机的人后悔了吗 (Do you regret not changing your mobile phone last year?)](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E5%B9%B4%E6%B2%A1%E6%8D%A2%E6%89%8B%E6%9C%BA%E7%9A%84%E4%BA%BA%E5%90%8E%E6%82%94%E4%BA%86%E5%90%97%23) `197.5K 🔥` `-21%`
1. [长期不换社交头像的人 (People who don’t change their social avatars for a long time)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E4%B8%8D%E6%8D%A2%E7%A4%BE%E4%BA%A4%E5%A4%B4%E5%83%8F%E7%9A%84%E4%BA%BA%23) `166.8K 🔥` `-23%`
1. [逐玉第二](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%AC%AC%E4%BA%8C%23) `160.9K 🔥` `-22%`
1. [种地吧](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `157.7K 🔥` `-49%`
1. [金价创下1983年3月以来最大单周跌幅](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E5%88%9B%E4%B8%8B1983%E5%B9%B43%E6%9C%88%E4%BB%A5%E6%9D%A5%E6%9C%80%E5%A4%A7%E5%8D%95%E5%91%A8%E8%B7%8C%E5%B9%85%23) `157.1K 🔥` `-23%`
1. [开始推理吧](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E6%8E%A8%E7%90%86%E5%90%A7%23) `154.9K 🔥` `-47%`
1. [长期喝桶装水的人天塌了 (People who drink bottled water for a long time are in trouble)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E5%96%9D%E6%A1%B6%E8%A3%85%E6%B0%B4%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `151.8K 🔥` `-21%`
1. [豆瓣评分](https://s.weibo.com/weibo?q=%23%E8%B1%86%E7%93%A3%E8%AF%84%E5%88%86%23) `149.9K 🔥` `-39%`
1. [教师称退群后家长转为点对点私聊 (The teacher said that after leaving the group, parents switched to peer-to-peer private chat)](https://s.weibo.com/weibo?q=%23%E6%95%99%E5%B8%88%E7%A7%B0%E9%80%80%E7%BE%A4%E5%90%8E%E5%AE%B6%E9%95%BF%E8%BD%AC%E4%B8%BA%E7%82%B9%E5%AF%B9%E7%82%B9%E7%A7%81%E8%81%8A%23) `147.4K 🔥` `-81%`
1. [中东战事来到危险临界点](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%B8%9C%E6%88%98%E4%BA%8B%E6%9D%A5%E5%88%B0%E5%8D%B1%E9%99%A9%E4%B8%B4%E7%95%8C%E7%82%B9%23) `114.9K 🔥` `-26%`
1. [河南男孩遭老师要求互打后坠亡后续](https://s.weibo.com/weibo?q=%23%E6%B2%B3%E5%8D%97%E7%94%B7%E5%AD%A9%E9%81%AD%E8%80%81%E5%B8%88%E8%A6%81%E6%B1%82%E4%BA%92%E6%89%93%E5%90%8E%E5%9D%A0%E4%BA%A1%E5%90%8E%E7%BB%AD%23) `85.0K 🔥` `-56%`
1. [陈浚铭再帅十年也才23岁](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%B5%9A%E9%93%AD%E5%86%8D%E5%B8%85%E5%8D%81%E5%B9%B4%E4%B9%9F%E6%89%8D23%E5%B2%81%23) `79.1K 🔥` `-22%`
1. [弟弟偷抵32万新车哥哥气炸 (The younger brother stole a new car worth RMB 320,000, and the older brother was furious.)](https://s.weibo.com/weibo?q=%23%E5%BC%9F%E5%BC%9F%E5%81%B7%E6%8A%B532%E4%B8%87%E6%96%B0%E8%BD%A6%E5%93%A5%E5%93%A5%E6%B0%94%E7%82%B8%23) `61.8K 🔥` `-47%`
1. [2000克黄金一周亏损40万 (2000 grams of gold lost 400,000 in one week)](https://s.weibo.com/weibo?q=%232000%E5%85%8B%E9%BB%84%E9%87%91%E4%B8%80%E5%91%A8%E4%BA%8F%E6%8D%9F40%E4%B8%87%23) `59.6K 🔥` `-43%`
1. [黄金要跌到什么时候](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E8%A6%81%E8%B7%8C%E5%88%B0%E4%BB%80%E4%B9%88%E6%97%B6%E5%80%99%23) `58.1K 🔥` `-34%`

Updated at 2026-03-23 19:56:08

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
