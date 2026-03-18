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

1. [产品背后 (Behind the product)](https://s.weibo.com/weibo?q=%23%E4%BA%A7%E5%93%81%E8%83%8C%E5%90%8E%23) `172.7K 🔥` `NEW`
1. [陶太傅掉马](https://s.weibo.com/weibo?q=%23%E9%99%B6%E5%A4%AA%E5%82%85%E6%8E%89%E9%A9%AC%23) `171.2K 🔥` `NEW`
1. [丞磊郭宇欣扇巴掌路透](https://s.weibo.com/weibo?q=%23%E4%B8%9E%E7%A3%8A%E9%83%AD%E5%AE%87%E6%AC%A3%E6%89%87%E5%B7%B4%E6%8E%8C%E8%B7%AF%E9%80%8F%23) `168.7K 🔥` `NEW`
1. [21岁女孩被亲妈饿到30公斤虐死](https://s.weibo.com/weibo?q=%2321%E5%B2%81%E5%A5%B3%E5%AD%A9%E8%A2%AB%E4%BA%B2%E5%A6%88%E9%A5%BF%E5%88%B030%E5%85%AC%E6%96%A4%E8%99%90%E6%AD%BB%23) `164.4K 🔥` `NEW`
1. [日本女孩发布新干线化妆视频被辱骂](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%A5%B3%E5%AD%A9%E5%8F%91%E5%B8%83%E6%96%B0%E5%B9%B2%E7%BA%BF%E5%8C%96%E5%A6%86%E8%A7%86%E9%A2%91%E8%A2%AB%E8%BE%B1%E9%AA%82%23) `160.9K 🔥` `NEW`
1. [游戏AI化驱动腾讯游戏业绩增长](https://s.weibo.com/weibo?q=%23%E6%B8%B8%E6%88%8FAI%E5%8C%96%E9%A9%B1%E5%8A%A8%E8%85%BE%E8%AE%AF%E6%B8%B8%E6%88%8F%E4%B8%9A%E7%BB%A9%E5%A2%9E%E9%95%BF%23) `157.8K 🔥` `NEW`
1. [张维伊喊袁姗姗嫂子](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%BB%B4%E4%BC%8A%E5%96%8A%E8%A2%81%E5%A7%97%E5%A7%97%E5%AB%82%E5%AD%90%23) `154.1K 🔥` `NEW`
1. [女性承担无偿家务是男性的两到三倍](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E6%80%A7%E6%89%BF%E6%8B%85%E6%97%A0%E5%81%BF%E5%AE%B6%E5%8A%A1%E6%98%AF%E7%94%B7%E6%80%A7%E7%9A%84%E4%B8%A4%E5%88%B0%E4%B8%89%E5%80%8D%23) `152.8K 🔥` `NEW`
1. [容易让人长胖的睡前习惯](https://s.weibo.com/weibo?q=%23%E5%AE%B9%E6%98%93%E8%AE%A9%E4%BA%BA%E9%95%BF%E8%83%96%E7%9A%84%E7%9D%A1%E5%89%8D%E4%B9%A0%E6%83%AF%23) `152.2K 🔥` `NEW`
1. [TF四代已实名](https://s.weibo.com/weibo?q=%23TF%E5%9B%9B%E4%BB%A3%E5%B7%B2%E5%AE%9E%E5%90%8D%23) `151.7K 🔥` `NEW`
1. [泰国国王和王后驾驶飞机抵达老挝 (Thailand's King and Queen fly to Laos)](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E5%9B%BD%E7%8E%8B%E5%92%8C%E7%8E%8B%E5%90%8E%E9%A9%BE%E9%A9%B6%E9%A3%9E%E6%9C%BA%E6%8A%B5%E8%BE%BE%E8%80%81%E6%8C%9D%23) `143.5K 🔥` `NEW`
1. [客服笑了半个小时决定去仓库打人](https://s.weibo.com/weibo?q=%23%E5%AE%A2%E6%9C%8D%E7%AC%91%E4%BA%86%E5%8D%8A%E4%B8%AA%E5%B0%8F%E6%97%B6%E5%86%B3%E5%AE%9A%E5%8E%BB%E4%BB%93%E5%BA%93%E6%89%93%E4%BA%BA%23) `143.4K 🔥` `NEW`
1. [腾讯人均年薪成本112.8万](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%9D%87%E5%B9%B4%E8%96%AA%E6%88%90%E6%9C%AC112.8%E4%B8%87%23) `132.3K 🔥` `NEW`
1. [狼队对战KSG](https://s.weibo.com/weibo?q=%23%E7%8B%BC%E9%98%9F%E5%AF%B9%E6%88%98KSG%23) `103.4K 🔥` `NEW`
1. [何穗分享孕期不长胖的方法](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%A9%97%E5%88%86%E4%BA%AB%E5%AD%95%E6%9C%9F%E4%B8%8D%E9%95%BF%E8%83%96%E7%9A%84%E6%96%B9%E6%B3%95%23) `102.8K 🔥` `NEW`
1. [董璇怕小酒窝到青春期不理她](https://s.weibo.com/weibo?q=%23%E8%91%A3%E7%92%87%E6%80%95%E5%B0%8F%E9%85%92%E7%AA%9D%E5%88%B0%E9%9D%92%E6%98%A5%E6%9C%9F%E4%B8%8D%E7%90%86%E5%A5%B9%23) `97.9K 🔥` `NEW`
1. [以色列防长称伊朗情报部长已死](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E9%98%B2%E9%95%BF%E7%A7%B0%E4%BC%8A%E6%9C%97%E6%83%85%E6%8A%A5%E9%83%A8%E9%95%BF%E5%B7%B2%E6%AD%BB%23) `97.1K 🔥` `NEW`
1. [赵丽颖直播](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E7%9B%B4%E6%92%AD%23) `95.4K 🔥` `NEW`
1. [网易否认外包裁员](https://s.weibo.com/weibo?q=%23%E7%BD%91%E6%98%93%E5%90%A6%E8%AE%A4%E5%A4%96%E5%8C%85%E8%A3%81%E5%91%98%23) `81.6K 🔥` `NEW`
1. [专家称以后或不止冲锋衣涨价](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E7%A7%B0%E4%BB%A5%E5%90%8E%E6%88%96%E4%B8%8D%E6%AD%A2%E5%86%B2%E9%94%8B%E8%A1%A3%E6%B6%A8%E4%BB%B7%23) `72.9K 🔥` `NEW`
1. [鱼塘主坚持2年用辣椒喂鱼 (Fish pond owner insists on feeding fish with chili pepper for 2 years)](https://s.weibo.com/weibo?q=%23%E9%B1%BC%E5%A1%98%E4%B8%BB%E5%9D%9A%E6%8C%812%E5%B9%B4%E7%94%A8%E8%BE%A3%E6%A4%92%E5%96%82%E9%B1%BC%23) `801.8K 🔥` `+266%`
1. [薛之谦演唱会](https://s.weibo.com/weibo?q=%23%E8%96%9B%E4%B9%8B%E8%B0%A6%E6%BC%94%E5%94%B1%E4%BC%9A%23) `173.0K 🔥` `+73%`
1. [耀客AI演员 赵今麦翟子路](https://s.weibo.com/weibo?q=%23%E8%80%80%E5%AE%A2AI%E6%BC%94%E5%91%98%20%E8%B5%B5%E4%BB%8A%E9%BA%A6%E7%BF%9F%E5%AD%90%E8%B7%AF%23) `156.4K 🔥` `+97%`
1. [国台办回应台湾面临断油断气危险](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%8F%B0%E5%8A%9E%E5%9B%9E%E5%BA%94%E5%8F%B0%E6%B9%BE%E9%9D%A2%E4%B8%B4%E6%96%AD%E6%B2%B9%E6%96%AD%E6%B0%94%E5%8D%B1%E9%99%A9%23) `99.8K 🔥` `+32%`
1. [小米新SU7](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%96%B0SU7%23) `1.1M 🔥`
1. [中国人4900年前造出水坝群](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BA%BA4900%E5%B9%B4%E5%89%8D%E9%80%A0%E5%87%BA%E6%B0%B4%E5%9D%9D%E7%BE%A4%23) `596.3K 🔥`
1. [雷军点赞小米车主助人善举](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E7%82%B9%E8%B5%9E%E5%B0%8F%E7%B1%B3%E8%BD%A6%E4%B8%BB%E5%8A%A9%E4%BA%BA%E5%96%84%E4%B8%BE%23) `153.7K 🔥`
1. [迪丽热巴代言甄稀冰淇淋](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%BB%A3%E8%A8%80%E7%94%84%E7%A8%80%E5%86%B0%E6%B7%87%E6%B7%8B%23) `140.9K 🔥`
1. [半个娱乐圈的人都抱过林沐然](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E4%B8%AA%E5%A8%B1%E4%B9%90%E5%9C%88%E7%9A%84%E4%BA%BA%E9%83%BD%E6%8A%B1%E8%BF%87%E6%9E%97%E6%B2%90%E7%84%B6%23) `120.0K 🔥`
1. [小S街头大哭](https://s.weibo.com/weibo?q=%23%E5%B0%8FS%E8%A1%97%E5%A4%B4%E5%A4%A7%E5%93%AD%23) `79.7K 🔥`
1. [中国学生开始卷海外考公了 (Chinese students begin to take public exams overseas)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%AD%A6%E7%94%9F%E5%BC%80%E5%A7%8B%E5%8D%B7%E6%B5%B7%E5%A4%96%E8%80%83%E5%85%AC%E4%BA%86%23) `176.1K 🔥` `-21%`
1. [腾讯发布2025年财报 (Tencent releases 2025 financial report)](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E5%8F%91%E5%B8%832025%E5%B9%B4%E8%B4%A2%E6%8A%A5%23) `175.2K 🔥` `-77%`
1. [以色列刺杀伊朗情报部长 (Israel assassinates Iranian intelligence minister)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%88%BA%E6%9D%80%E4%BC%8A%E6%9C%97%E6%83%85%E6%8A%A5%E9%83%A8%E9%95%BF%23) `170.5K 🔥` `-22%`
1. [建议年轻人少去公园容易伤自尊 (It is recommended that young people go to the park less often because it may hurt their self-esteem.)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%B0%91%E5%8E%BB%E5%85%AC%E5%9B%AD%E5%AE%B9%E6%98%93%E4%BC%A4%E8%87%AA%E5%B0%8A%23) `166.2K 🔥` `-24%`
1. [樊长玉谢征 好孕赘婿 (Fan Changyu, Xie Zheng, pregnant son-in-law)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E8%B0%A2%E5%BE%81%20%E5%A5%BD%E5%AD%95%E8%B5%98%E5%A9%BF%23) `163.0K 🔥` `-24%`
1. [果然人老了干什么都心酸 (Sure enough, when you are old, you will feel sad no matter what you do.)](https://s.weibo.com/weibo?q=%23%E6%9E%9C%E7%84%B6%E4%BA%BA%E8%80%81%E4%BA%86%E5%B9%B2%E4%BB%80%E4%B9%88%E9%83%BD%E5%BF%83%E9%85%B8%23) `161.0K 🔥` `-24%`
1. [拉里贾尼被斩首细节披露](https://s.weibo.com/weibo?q=%23%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%E8%A2%AB%E6%96%A9%E9%A6%96%E7%BB%86%E8%8A%82%E6%8A%AB%E9%9C%B2%23) `160.5K 🔥` `-22%`
1. [5岁孩子狂赚20亿短剧人设引争议](https://s.weibo.com/weibo?q=%235%E5%B2%81%E5%AD%A9%E5%AD%90%E7%8B%82%E8%B5%9A20%E4%BA%BF%E7%9F%AD%E5%89%A7%E4%BA%BA%E8%AE%BE%E5%BC%95%E4%BA%89%E8%AE%AE%23) `159.7K 🔥` `-25%`
1. [油价涨了冲锋衣可能更贵](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E6%B6%A8%E4%BA%86%E5%86%B2%E9%94%8B%E8%A1%A3%E5%8F%AF%E8%83%BD%E6%9B%B4%E8%B4%B5%23) `159.3K 🔥` `-26%`
1. [离职要走发现同事在窗口举牌](https://s.weibo.com/weibo?q=%23%E7%A6%BB%E8%81%8C%E8%A6%81%E8%B5%B0%E5%8F%91%E7%8E%B0%E5%90%8C%E4%BA%8B%E5%9C%A8%E7%AA%97%E5%8F%A3%E4%B8%BE%E7%89%8C%23) `158.3K 🔥` `-24%`
1. [百花杀](https://s.weibo.com/weibo?q=%23%E7%99%BE%E8%8A%B1%E6%9D%80%23) `157.4K 🔥` `-25%`
1. [烧饭阿姨把三文鱼煮了](https://s.weibo.com/weibo?q=%23%E7%83%A7%E9%A5%AD%E9%98%BF%E5%A7%A8%E6%8A%8A%E4%B8%89%E6%96%87%E9%B1%BC%E7%85%AE%E4%BA%86%23) `156.1K 🔥` `-30%`
1. [张凌赫 我和他都没演过长风渡](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E6%88%91%E5%92%8C%E4%BB%96%E9%83%BD%E6%B2%A1%E6%BC%94%E8%BF%87%E9%95%BF%E9%A3%8E%E6%B8%A1%23) `154.8K 🔥` `-67%`
1. [福建一鸭子活吞41只小鸡](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%BB%BA%E4%B8%80%E9%B8%AD%E5%AD%90%E6%B4%BB%E5%90%9E41%E5%8F%AA%E5%B0%8F%E9%B8%A1%23) `151.3K 🔥` `-25%`
1. [文身店免费给65岁以上老人文身](https://s.weibo.com/weibo?q=%23%E6%96%87%E8%BA%AB%E5%BA%97%E5%85%8D%E8%B4%B9%E7%BB%9965%E5%B2%81%E4%BB%A5%E4%B8%8A%E8%80%81%E4%BA%BA%E6%96%87%E8%BA%AB%23) `103.2K 🔥` `-51%`
1. [耀客一直在等孟子义 (Yaoke has been waiting for Meng Ziyi)](https://s.weibo.com/weibo?q=%23%E8%80%80%E5%AE%A2%E4%B8%80%E7%9B%B4%E5%9C%A8%E7%AD%89%E5%AD%9F%E5%AD%90%E4%B9%89%23) `100.9K 🔥` `-51%`
1. [网传落生去世 (Internet rumors about death)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E4%BC%A0%E8%90%BD%E7%94%9F%E5%8E%BB%E4%B8%96%23) `99.5K 🔥` `-48%`
1. [我家楼下有鹿晗 (There is Luhan downstairs in my house)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%AE%B6%E6%A5%BC%E4%B8%8B%E6%9C%89%E9%B9%BF%E6%99%97%23) `84.6K 🔥` `-58%`
1. [钮钴禄Jennie](https://s.weibo.com/weibo?q=%23%E9%92%AE%E9%92%B4%E7%A6%84Jennie%23) `80.3K 🔥` `-60%`
1. [伊朗革命卫队报复行动升级 (Iran's Revolutionary Guards escalate retaliatory actions)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%E5%8D%87%E7%BA%A7%23) `73.6K 🔥` `-34%`
1. [全球机票将涨价](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E6%9C%BA%E7%A5%A8%E5%B0%86%E6%B6%A8%E4%BB%B7%23) `72.8K 🔥` `-32%`

Updated at 2026-03-18 19:09:46

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
