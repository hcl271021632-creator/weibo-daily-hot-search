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

1. [莫斯科遭大量无人机袭击 (Moscow was attacked by a large number of drones)](https://s.weibo.com/weibo?q=%23%E8%8E%AB%E6%96%AF%E7%A7%91%E9%81%AD%E5%A4%A7%E9%87%8F%E6%97%A0%E4%BA%BA%E6%9C%BA%E8%A2%AD%E5%87%BB%23) `1.1M 🔥` `NEW`
1. [仅收280元牙医回应女孩将复查3次](https://s.weibo.com/weibo?q=%23%E4%BB%85%E6%94%B6280%E5%85%83%E7%89%99%E5%8C%BB%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%AD%A9%E5%B0%86%E5%A4%8D%E6%9F%A53%E6%AC%A1%23) `806.5K 🔥` `NEW`
1. [大爷撞法拉利掏163元和4棵菜赔偿](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%88%B7%E6%92%9E%E6%B3%95%E6%8B%89%E5%88%A9%E6%8E%8F163%E5%85%83%E5%92%8C4%E6%A3%B5%E8%8F%9C%E8%B5%94%E5%81%BF%23) `253.3K 🔥` `NEW`
1. [蒋超良被逮捕](https://s.weibo.com/weibo?q=%23%E8%92%8B%E8%B6%85%E8%89%AF%E8%A2%AB%E9%80%AE%E6%8D%95%23) `252.5K 🔥` `NEW`
1. [华为渠道服](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%B8%BA%E6%B8%A0%E9%81%93%E6%9C%8D%23) `218.6K 🔥` `NEW`
1. [恋与深空 无法登陆](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%20%E6%97%A0%E6%B3%95%E7%99%BB%E9%99%86%23) `214.8K 🔥` `NEW`
1. [逐玉 韩国](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E9%9F%A9%E5%9B%BD%23) `204.9K 🔥` `NEW`
1. [高中生斑马线过马路被撞飞身亡](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%B8%AD%E7%94%9F%E6%96%91%E9%A9%AC%E7%BA%BF%E8%BF%87%E9%A9%AC%E8%B7%AF%E8%A2%AB%E6%92%9E%E9%A3%9E%E8%BA%AB%E4%BA%A1%23) `200.8K 🔥` `NEW`
1. [AI 裁员](https://s.weibo.com/weibo?q=%23AI%20%E8%A3%81%E5%91%98%23) `189.9K 🔥` `NEW`
1. [樊长玉听见下聘成亲的反应](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E5%90%AC%E8%A7%81%E4%B8%8B%E8%81%98%E6%88%90%E4%BA%B2%E7%9A%84%E5%8F%8D%E5%BA%94%23) `179.2K 🔥` `NEW`
1. [吴映洁说期待大侦探返场 (Wu Yingjie said she is looking forward to the return of the great detective)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%A0%E6%B4%81%E8%AF%B4%E6%9C%9F%E5%BE%85%E5%A4%A7%E4%BE%A6%E6%8E%A2%E8%BF%94%E5%9C%BA%23) `161.0K 🔥` `NEW`
1. [20岁男子感染HIV后HPV反复发作](https://s.weibo.com/weibo?q=%2320%E5%B2%81%E7%94%B7%E5%AD%90%E6%84%9F%E6%9F%93HIV%E5%90%8EHPV%E5%8F%8D%E5%A4%8D%E5%8F%91%E4%BD%9C%23) `137.7K 🔥` `NEW`
1. [赵本山近况](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E6%9C%AC%E5%B1%B1%E8%BF%91%E5%86%B5%23) `137.1K 🔥` `NEW`
1. [AI 替代岗位](https://s.weibo.com/weibo?q=%23AI%20%E6%9B%BF%E4%BB%A3%E5%B2%97%E4%BD%8D%23) `127.9K 🔥` `NEW`
1. [紫薯精不吃刘文祥改大理寺了](https://s.weibo.com/weibo?q=%23%E7%B4%AB%E8%96%AF%E7%B2%BE%E4%B8%8D%E5%90%83%E5%88%98%E6%96%87%E7%A5%A5%E6%94%B9%E5%A4%A7%E7%90%86%E5%AF%BA%E4%BA%86%23) `127.8K 🔥` `NEW`
1. [朱丹回应被瞿颖说黑](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E4%B8%B9%E5%9B%9E%E5%BA%94%E8%A2%AB%E7%9E%BF%E9%A2%96%E8%AF%B4%E9%BB%91%23) `127.8K 🔥` `NEW`
1. [睡得晚和睡得少哪个更伤身体](https://s.weibo.com/weibo?q=%23%E7%9D%A1%E5%BE%97%E6%99%9A%E5%92%8C%E7%9D%A1%E5%BE%97%E5%B0%91%E5%93%AA%E4%B8%AA%E6%9B%B4%E4%BC%A4%E8%BA%AB%E4%BD%93%23) `127.8K 🔥` `NEW`
1. [小伙卖卤肉饭被同行强行倒菜驱赶](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%8D%96%E5%8D%A4%E8%82%89%E9%A5%AD%E8%A2%AB%E5%90%8C%E8%A1%8C%E5%BC%BA%E8%A1%8C%E5%80%92%E8%8F%9C%E9%A9%B1%E8%B5%B6%23) `127.8K 🔥` `NEW`
1. [AppleWatch国行上线房颤功能](https://s.weibo.com/weibo?q=%23AppleWatch%E5%9B%BD%E8%A1%8C%E4%B8%8A%E7%BA%BF%E6%88%BF%E9%A2%A4%E5%8A%9F%E8%83%BD%23) `122.7K 🔥` `NEW`
1. [重庆马拉松裁判误拦冠军被禁赛1年](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E9%A9%AC%E6%8B%89%E6%9D%BE%E8%A3%81%E5%88%A4%E8%AF%AF%E6%8B%A6%E5%86%A0%E5%86%9B%E8%A2%AB%E7%A6%81%E8%B5%9B1%E5%B9%B4%23) `120.0K 🔥` `NEW`
1. [大理寺米线 泼天的富贵 (Dali Temple Rice Noodles The Wealth of the Sky)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%90%86%E5%AF%BA%E7%B1%B3%E7%BA%BF%20%E6%B3%BC%E5%A4%A9%E7%9A%84%E5%AF%8C%E8%B4%B5%23) `117.0K 🔥` `NEW`
1. [考古的风终于轮到田曦薇了](https://s.weibo.com/weibo?q=%23%E8%80%83%E5%8F%A4%E7%9A%84%E9%A3%8E%E7%BB%88%E4%BA%8E%E8%BD%AE%E5%88%B0%E7%94%B0%E6%9B%A6%E8%96%87%E4%BA%86%23) `113.0K 🔥` `NEW`
1. [洛克王国世界预注册](https://s.weibo.com/weibo?q=%23%E6%B4%9B%E5%85%8B%E7%8E%8B%E5%9B%BD%E4%B8%96%E7%95%8C%E9%A2%84%E6%B3%A8%E5%86%8C%23) `108.1K 🔥` `NEW`
1. [一个34岁研究生上岸后的猝死](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%B8%AA34%E5%B2%81%E7%A0%94%E7%A9%B6%E7%94%9F%E4%B8%8A%E5%B2%B8%E5%90%8E%E7%9A%84%E7%8C%9D%E6%AD%BB%23) `107.9K 🔥` `NEW`
1. [当公交车突然没了台阶](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%85%AC%E4%BA%A4%E8%BD%A6%E7%AA%81%E7%84%B6%E6%B2%A1%E4%BA%86%E5%8F%B0%E9%98%B6%23) `107.5K 🔥` `NEW`
1. [全是不想坐B座的聪明人](https://s.weibo.com/weibo?q=%23%E5%85%A8%E6%98%AF%E4%B8%8D%E6%83%B3%E5%9D%90B%E5%BA%A7%E7%9A%84%E8%81%AA%E6%98%8E%E4%BA%BA%23) `107.3K 🔥` `NEW`
1. [这位美国机械师被中国赠品整红温](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%BD%8D%E7%BE%8E%E5%9B%BD%E6%9C%BA%E6%A2%B0%E5%B8%88%E8%A2%AB%E4%B8%AD%E5%9B%BD%E8%B5%A0%E5%93%81%E6%95%B4%E7%BA%A2%E6%B8%A9%23) `106.6K 🔥` `NEW`
1. [叠纸游戏称封号是华为原因](https://s.weibo.com/weibo?q=%23%E5%8F%A0%E7%BA%B8%E6%B8%B8%E6%88%8F%E7%A7%B0%E5%B0%81%E5%8F%B7%E6%98%AF%E5%8D%8E%E4%B8%BA%E5%8E%9F%E5%9B%A0%23) `106.3K 🔥` `NEW`
1. [三星三折叠将停售](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%98%9F%E4%B8%89%E6%8A%98%E5%8F%A0%E5%B0%86%E5%81%9C%E5%94%AE%23) `106.2K 🔥` `NEW`
1. [金条在唐朝花不出去](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%9D%A1%E5%9C%A8%E5%94%90%E6%9C%9D%E8%8A%B1%E4%B8%8D%E5%87%BA%E5%8E%BB%23) `97.5K 🔥` `NEW`
1. [早睡简直就是人类的无敌作弊器 (Going to bed early is simply an invincible cheating device for humans.)](https://s.weibo.com/weibo?q=%23%E6%97%A9%E7%9D%A1%E7%AE%80%E7%9B%B4%E5%B0%B1%E6%98%AF%E4%BA%BA%E7%B1%BB%E7%9A%84%E6%97%A0%E6%95%8C%E4%BD%9C%E5%BC%8A%E5%99%A8%23) `96.3K 🔥` `NEW`
1. [男子泳池溺亡女儿称10分钟无人救](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E6%B3%B3%E6%B1%A0%E6%BA%BA%E4%BA%A1%E5%A5%B3%E5%84%BF%E7%A7%B010%E5%88%86%E9%92%9F%E6%97%A0%E4%BA%BA%E6%95%91%23) `95.3K 🔥` `NEW`
1. [76岁奶奶送孙子入伍这一幕看泪目了](https://s.weibo.com/weibo?q=%2376%E5%B2%81%E5%A5%B6%E5%A5%B6%E9%80%81%E5%AD%99%E5%AD%90%E5%85%A5%E4%BC%8D%E8%BF%99%E4%B8%80%E5%B9%95%E7%9C%8B%E6%B3%AA%E7%9B%AE%E4%BA%86%23) `92.3K 🔥` `NEW`
1. [单位称已有人致电咨询山顶岗位](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BD%8D%E7%A7%B0%E5%B7%B2%E6%9C%89%E4%BA%BA%E8%87%B4%E7%94%B5%E5%92%A8%E8%AF%A2%E5%B1%B1%E9%A1%B6%E5%B2%97%E4%BD%8D%23) `90.0K 🔥` `NEW`
1. [你好1983今日开播](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD1983%E4%BB%8A%E6%97%A5%E5%BC%80%E6%92%AD%23) `89.9K 🔥` `NEW`
1. [AI焦虑](https://s.weibo.com/weibo?q=%23AI%E7%84%A6%E8%99%91%23) `89.3K 🔥` `NEW`
1. [甜茶的面相变了](https://s.weibo.com/weibo?q=%23%E7%94%9C%E8%8C%B6%E7%9A%84%E9%9D%A2%E7%9B%B8%E5%8F%98%E4%BA%86%23) `88.3K 🔥` `NEW`
1. [双氧水漂白鸡爪名单](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E6%B0%A7%E6%B0%B4%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%E5%90%8D%E5%8D%95%23) `86.7K 🔥` `NEW`
1. [男孩独自照顾婴儿妹妹崩溃大哭](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E7%8B%AC%E8%87%AA%E7%85%A7%E9%A1%BE%E5%A9%B4%E5%84%BF%E5%A6%B9%E5%A6%B9%E5%B4%A9%E6%BA%83%E5%A4%A7%E5%93%AD%23) `84.8K 🔥` `NEW`
1. [邱党直呼樊振东为新同事](https://s.weibo.com/weibo?q=%23%E9%82%B1%E5%85%9A%E7%9B%B4%E5%91%BC%E6%A8%8A%E6%8C%AF%E4%B8%9C%E4%B8%BA%E6%96%B0%E5%90%8C%E4%BA%8B%23) `84.4K 🔥` `NEW`
1. [当风象妈生了个水象闺女 (When an air sign mother gives birth to a water sign girl)](https://s.weibo.com/weibo?q=%23%E5%BD%93%E9%A3%8E%E8%B1%A1%E5%A6%88%E7%94%9F%E4%BA%86%E4%B8%AA%E6%B0%B4%E8%B1%A1%E9%97%BA%E5%A5%B3%23) `83.9K 🔥` `NEW`
1. [90岁老人与妻子告别后几秒钟去世](https://s.weibo.com/weibo?q=%2390%E5%B2%81%E8%80%81%E4%BA%BA%E4%B8%8E%E5%A6%BB%E5%AD%90%E5%91%8A%E5%88%AB%E5%90%8E%E5%87%A0%E7%A7%92%E9%92%9F%E5%8E%BB%E4%B8%96%23) `83.0K 🔥` `NEW`
1. [美军被曝对伊朗退出选项](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E8%A2%AB%E6%9B%9D%E5%AF%B9%E4%BC%8A%E6%9C%97%E9%80%80%E5%87%BA%E9%80%89%E9%A1%B9%23) `240.6K 🔥` `+154%`
1. [美国陷入孤立](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E9%99%B7%E5%85%A5%E5%AD%A4%E7%AB%8B%23) `184.0K 🔥` `+64%`
1. [奋进十五五你会看到这样的中国 (You will see China like this during the 15th Five-Year Plan)](https://s.weibo.com/weibo?q=%23%E5%A5%8B%E8%BF%9B%E5%8D%81%E4%BA%94%E4%BA%94%E4%BD%A0%E4%BC%9A%E7%9C%8B%E5%88%B0%E8%BF%99%E6%A0%B7%E7%9A%84%E4%B8%AD%E5%9B%BD%23) `665.8K 🔥`
1. [爸爸买彩票中748万不告诉孩子](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD748%E4%B8%87%E4%B8%8D%E5%91%8A%E8%AF%89%E5%AD%A9%E5%AD%90%23) `236.6K 🔥` `-62%`
1. [胖东来169元1克拉方糖戒指再上架 (Pang Donglai’s 169 yuan 1 carat sugar cube ring is back on the shelves)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5169%E5%85%831%E5%85%8B%E6%8B%89%E6%96%B9%E7%B3%96%E6%88%92%E6%8C%87%E5%86%8D%E4%B8%8A%E6%9E%B6%23) `223.9K 🔥` `-33%`
1. [入职未满1年怀孕请假被拒获赔10万 (She was compensated NT$100,000 when she was refused leave due to pregnancy less than 1 year after joining the company.)](https://s.weibo.com/weibo?q=%23%E5%85%A5%E8%81%8C%E6%9C%AA%E6%BB%A11%E5%B9%B4%E6%80%80%E5%AD%95%E8%AF%B7%E5%81%87%E8%A2%AB%E6%8B%92%E8%8E%B7%E8%B5%9410%E4%B8%87%23) `192.5K 🔥` `-76%`
1. [邓凯跑了8年龙套](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E8%B7%91%E4%BA%868%E5%B9%B4%E9%BE%99%E5%A5%97%23) `119.7K 🔥` `-43%`
1. [最佳睡眠到底是几个小时 (What are the best hours of sleep?)](https://s.weibo.com/weibo?q=%23%E6%9C%80%E4%BD%B3%E7%9D%A1%E7%9C%A0%E5%88%B0%E5%BA%95%E6%98%AF%E5%87%A0%E4%B8%AA%E5%B0%8F%E6%97%B6%23) `104.5K 🔥` `-91%`

Updated at 2026-03-17 11:42:08

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
