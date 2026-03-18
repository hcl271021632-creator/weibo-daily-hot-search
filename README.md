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

1. [周小闹回应带红刘文祥麻辣烫 (Zhou Xiaonao responded to Liu Wenxiang's spicy hotpot)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%B0%8F%E9%97%B9%E5%9B%9E%E5%BA%94%E5%B8%A6%E7%BA%A2%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%23) `400.3K 🔥` `NEW`
1. [正午阳光要扶持新人了](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E5%8D%88%E9%98%B3%E5%85%89%E8%A6%81%E6%89%B6%E6%8C%81%E6%96%B0%E4%BA%BA%E4%BA%86%23) `328.6K 🔥` `NEW`
1. [蜘蛛侠4预告](https://s.weibo.com/weibo?q=%23%E8%9C%98%E8%9B%9B%E4%BE%A04%E9%A2%84%E5%91%8A%23) `327.7K 🔥` `NEW`
1. [女子称在健身房裸身被男维修工看光](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%A7%B0%E5%9C%A8%E5%81%A5%E8%BA%AB%E6%88%BF%E8%A3%B8%E8%BA%AB%E8%A2%AB%E7%94%B7%E7%BB%B4%E4%BF%AE%E5%B7%A5%E7%9C%8B%E5%85%89%23) `302.0K 🔥` `NEW`
1. [3岁女童被虐死前零下20多度遭脱衣](https://s.weibo.com/weibo?q=%233%E5%B2%81%E5%A5%B3%E7%AB%A5%E8%A2%AB%E8%99%90%E6%AD%BB%E5%89%8D%E9%9B%B6%E4%B8%8B20%E5%A4%9A%E5%BA%A6%E9%81%AD%E8%84%B1%E8%A1%A3%23) `188.8K 🔥` `NEW`
1. [爸爸买下校景房儿子上学仅需两分钟](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E4%B9%B0%E4%B8%8B%E6%A0%A1%E6%99%AF%E6%88%BF%E5%84%BF%E5%AD%90%E4%B8%8A%E5%AD%A6%E4%BB%85%E9%9C%80%E4%B8%A4%E5%88%86%E9%92%9F%23) `172.6K 🔥` `NEW`
1. [小鹏P7这次太全面了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%B9%8FP7%E8%BF%99%E6%AC%A1%E5%A4%AA%E5%85%A8%E9%9D%A2%E4%BA%86%23) `172.5K 🔥` `NEW`
1. [宝诗龙上海旗舰店](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E8%AF%97%E9%BE%99%E4%B8%8A%E6%B5%B7%E6%97%97%E8%88%B0%E5%BA%97%23) `172.4K 🔥` `NEW`
1. [徐若晗 挂脸](https://s.weibo.com/weibo?q=%23%E5%BE%90%E8%8B%A5%E6%99%97%20%E6%8C%82%E8%84%B8%23) `172.3K 🔥` `NEW`
1. [陈妍希说谢谢你一直懂我](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A6%8D%E5%B8%8C%E8%AF%B4%E8%B0%A2%E8%B0%A2%E4%BD%A0%E4%B8%80%E7%9B%B4%E6%87%82%E6%88%91%23) `172.0K 🔥` `NEW`
1. [黄金怎么不涨反跌 (Why does gold fall instead of rising?)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E6%80%8E%E4%B9%88%E4%B8%8D%E6%B6%A8%E5%8F%8D%E8%B7%8C%23) `171.7K 🔥` `NEW`
1. [黄金](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%23) `126.4K 🔥` `NEW`
1. [AI演员 人山人海](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%20%E4%BA%BA%E5%B1%B1%E4%BA%BA%E6%B5%B7%23) `124.9K 🔥` `NEW`
1. [原来你就是武安侯](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E4%BD%A0%E5%B0%B1%E6%98%AF%E6%AD%A6%E5%AE%89%E4%BE%AF%23) `111.0K 🔥` `NEW`
1. [全球多个国家出现麻疹疫情反弹](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E5%A4%9A%E4%B8%AA%E5%9B%BD%E5%AE%B6%E5%87%BA%E7%8E%B0%E9%BA%BB%E7%96%B9%E7%96%AB%E6%83%85%E5%8F%8D%E5%BC%B9%23) `100.1K 🔥` `NEW`
1. [时代峰峻是不是觉得自己很聪明](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E6%98%AF%E4%B8%8D%E6%98%AF%E8%A7%89%E5%BE%97%E8%87%AA%E5%B7%B1%E5%BE%88%E8%81%AA%E6%98%8E%23) `79.7K 🔥` `NEW`
1. [宁娘 皇后](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%A8%98%20%E7%9A%87%E5%90%8E%23) `77.3K 🔥` `NEW`
1. [邓凯原名叫邓尚](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E5%8E%9F%E5%90%8D%E5%8F%AB%E9%82%93%E5%B0%9A%23) `70.8K 🔥` `NEW`
1. [走村串巷偷了8000个手机号](https://s.weibo.com/weibo?q=%23%E8%B5%B0%E6%9D%91%E4%B8%B2%E5%B7%B7%E5%81%B7%E4%BA%868000%E4%B8%AA%E6%89%8B%E6%9C%BA%E5%8F%B7%23) `69.4K 🔥` `NEW`
1. [五十公里桃花坞6](https://s.weibo.com/weibo?q=%23%E4%BA%94%E5%8D%81%E5%85%AC%E9%87%8C%E6%A1%83%E8%8A%B1%E5%9D%9E6%23) `68.5K 🔥` `NEW`
1. [我们英语老师怎么不这么教 (Why don’t our English teachers teach like this?)](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E8%8B%B1%E8%AF%AD%E8%80%81%E5%B8%88%E6%80%8E%E4%B9%88%E4%B8%8D%E8%BF%99%E4%B9%88%E6%95%99%23) `67.7K 🔥` `NEW`
1. [中国学生开始卷海外考公了 (Chinese students begin to take public exams overseas)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%AD%A6%E7%94%9F%E5%BC%80%E5%A7%8B%E5%8D%B7%E6%B5%B7%E5%A4%96%E8%80%83%E5%85%AC%E4%BA%86%23) `760.9K 🔥` `+332%`
1. [建议年轻人少去公园容易伤自尊 (It is recommended that young people go to the park less often because it may hurt their self-esteem.)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%B0%91%E5%8E%BB%E5%85%AC%E5%9B%AD%E5%AE%B9%E6%98%93%E4%BC%A4%E8%87%AA%E5%B0%8A%23) `364.0K 🔥` `+119%`
1. [以色列刺杀伊朗情报部长 (Israel assassinates Iranian intelligence minister)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%88%BA%E6%9D%80%E4%BC%8A%E6%9C%97%E6%83%85%E6%8A%A5%E9%83%A8%E9%95%BF%23) `326.2K 🔥` `+91%`
1. [腾讯人均年薪成本112.8万](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E4%BA%BA%E5%9D%87%E5%B9%B4%E8%96%AA%E6%88%90%E6%9C%AC112.8%E4%B8%87%23) `325.9K 🔥` `+146%`
1. [油价涨了冲锋衣可能更贵](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E6%B6%A8%E4%BA%86%E5%86%B2%E9%94%8B%E8%A1%A3%E5%8F%AF%E8%83%BD%E6%9B%B4%E8%B4%B5%23) `324.6K 🔥` `+104%`
1. [樊长玉谢征 好孕赘婿 (Fan Changyu, Xie Zheng, pregnant son-in-law)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E8%B0%A2%E5%BE%81%20%E5%A5%BD%E5%AD%95%E8%B5%98%E5%A9%BF%23) `323.1K 🔥` `+98%`
1. [泰国国王和王后驾驶飞机抵达老挝 (Thailand's King and Queen fly to Laos)](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E5%9B%BD%E7%8E%8B%E5%92%8C%E7%8E%8B%E5%90%8E%E9%A9%BE%E9%A9%B6%E9%A3%9E%E6%9C%BA%E6%8A%B5%E8%BE%BE%E8%80%81%E6%8C%9D%23) `322.5K 🔥` `+125%`
1. [狼队对战KSG](https://s.weibo.com/weibo?q=%23%E7%8B%BC%E9%98%9F%E5%AF%B9%E6%88%98KSG%23) `172.5K 🔥` `+67%`
1. [赵丽颖直播](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E7%9B%B4%E6%92%AD%23) `172.2K 🔥` `+80%`
1. [小米新SU7](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%96%B0SU7%23) `1.1M 🔥`
1. [中国人4900年前造出水坝群](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E4%BA%BA4900%E5%B9%B4%E5%89%8D%E9%80%A0%E5%87%BA%E6%B0%B4%E5%9D%9D%E7%BE%A4%23) `633.6K 🔥`
1. [陶太傅掉马](https://s.weibo.com/weibo?q=%23%E9%99%B6%E5%A4%AA%E5%82%85%E6%8E%89%E9%A9%AC%23) `172.6K 🔥`
1. [客服笑了半个小时决定去仓库打人](https://s.weibo.com/weibo?q=%23%E5%AE%A2%E6%9C%8D%E7%AC%91%E4%BA%86%E5%8D%8A%E4%B8%AA%E5%B0%8F%E6%97%B6%E5%86%B3%E5%AE%9A%E5%8E%BB%E4%BB%93%E5%BA%93%E6%89%93%E4%BA%BA%23) `172.3K 🔥`
1. [耀客AI演员 赵今麦翟子路](https://s.weibo.com/weibo?q=%23%E8%80%80%E5%AE%A2AI%E6%BC%94%E5%91%98%20%E8%B5%B5%E4%BB%8A%E9%BA%A6%E7%BF%9F%E5%AD%90%E8%B7%AF%23) `172.1K 🔥`
1. [果然人老了干什么都心酸 (Sure enough, when you are old, you will feel sad no matter what you do.)](https://s.weibo.com/weibo?q=%23%E6%9E%9C%E7%84%B6%E4%BA%BA%E8%80%81%E4%BA%86%E5%B9%B2%E4%BB%80%E4%B9%88%E9%83%BD%E5%BF%83%E9%85%B8%23) `171.9K 🔥`
1. [5岁孩子狂赚20亿短剧人设引争议 (5-year-old boy makes 2 billion yuan with short play character, sparks controversy)](https://s.weibo.com/weibo?q=%235%E5%B2%81%E5%AD%A9%E5%AD%90%E7%8B%82%E8%B5%9A20%E4%BA%BF%E7%9F%AD%E5%89%A7%E4%BA%BA%E8%AE%BE%E5%BC%95%E4%BA%89%E8%AE%AE%23) `171.9K 🔥`
1. [张凌赫 我和他都没演过长风渡](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E6%88%91%E5%92%8C%E4%BB%96%E9%83%BD%E6%B2%A1%E6%BC%94%E8%BF%87%E9%95%BF%E9%A3%8E%E6%B8%A1%23) `171.8K 🔥`
1. [福建一鸭子活吞41只小鸡](https://s.weibo.com/weibo?q=%23%E7%A6%8F%E5%BB%BA%E4%B8%80%E9%B8%AD%E5%AD%90%E6%B4%BB%E5%90%9E41%E5%8F%AA%E5%B0%8F%E9%B8%A1%23) `171.6K 🔥`
1. [拉里贾尼被斩首细节披露](https://s.weibo.com/weibo?q=%23%E6%8B%89%E9%87%8C%E8%B4%BE%E5%B0%BC%E8%A2%AB%E6%96%A9%E9%A6%96%E7%BB%86%E8%8A%82%E6%8A%AB%E9%9C%B2%23) `171.6K 🔥`
1. [丞磊郭宇欣扇巴掌路透](https://s.weibo.com/weibo?q=%23%E4%B8%9E%E7%A3%8A%E9%83%AD%E5%AE%87%E6%AC%A3%E6%89%87%E5%B7%B4%E6%8E%8C%E8%B7%AF%E9%80%8F%23) `171.5K 🔥`
1. [烧饭阿姨把三文鱼煮了](https://s.weibo.com/weibo?q=%23%E7%83%A7%E9%A5%AD%E9%98%BF%E5%A7%A8%E6%8A%8A%E4%B8%89%E6%96%87%E9%B1%BC%E7%85%AE%E4%BA%86%23) `171.4K 🔥`
1. [容易让人长胖的睡前习惯](https://s.weibo.com/weibo?q=%23%E5%AE%B9%E6%98%93%E8%AE%A9%E4%BA%BA%E9%95%BF%E8%83%96%E7%9A%84%E7%9D%A1%E5%89%8D%E4%B9%A0%E6%83%AF%23) `171.4K 🔥`
1. [张维伊喊袁姗姗嫂子](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%BB%B4%E4%BC%8A%E5%96%8A%E8%A2%81%E5%A7%97%E5%A7%97%E5%AB%82%E5%AD%90%23) `161.9K 🔥`
1. [TF四代已实名](https://s.weibo.com/weibo?q=%23TF%E5%9B%9B%E4%BB%A3%E5%B7%B2%E5%AE%9E%E5%90%8D%23) `152.5K 🔥`
1. [何穗分享孕期不长胖的方法](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%A9%97%E5%88%86%E4%BA%AB%E5%AD%95%E6%9C%9F%E4%B8%8D%E9%95%BF%E8%83%96%E7%9A%84%E6%96%B9%E6%B3%95%23) `97.2K 🔥`
1. [耀客一直在等孟子义 (Yaoke has been waiting for Meng Ziyi)](https://s.weibo.com/weibo?q=%23%E8%80%80%E5%AE%A2%E4%B8%80%E7%9B%B4%E5%9C%A8%E7%AD%89%E5%AD%9F%E5%AD%90%E4%B9%89%23) `85.4K 🔥`
1. [小S街头大哭 (Little S crying on the street)](https://s.weibo.com/weibo?q=%23%E5%B0%8FS%E8%A1%97%E5%A4%B4%E5%A4%A7%E5%93%AD%23) `69.2K 🔥`
1. [鱼塘主坚持2年用辣椒喂鱼 (Fish pond owner insists on feeding fish with chili pepper for 2 years)](https://s.weibo.com/weibo?q=%23%E9%B1%BC%E5%A1%98%E4%B8%BB%E5%9D%9A%E6%8C%812%E5%B9%B4%E7%94%A8%E8%BE%A3%E6%A4%92%E5%96%82%E9%B1%BC%23) `190.3K 🔥` `-76%`
1. [日本女孩发布新干线化妆视频被辱骂](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%A5%B3%E5%AD%A9%E5%8F%91%E5%B8%83%E6%96%B0%E5%B9%B2%E7%BA%BF%E5%8C%96%E5%A6%86%E8%A7%86%E9%A2%91%E8%A2%AB%E8%BE%B1%E9%AA%82%23) `82.6K 🔥` `-49%`

Updated at 2026-03-18 19:58:35

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
