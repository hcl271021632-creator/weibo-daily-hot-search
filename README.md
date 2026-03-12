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

1. [建议让全年无休的照护者能喘口气 (Recommendations to give year-round caregivers a breather)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E8%AE%A9%E5%85%A8%E5%B9%B4%E6%97%A0%E4%BC%91%E7%9A%84%E7%85%A7%E6%8A%A4%E8%80%85%E8%83%BD%E5%96%98%E5%8F%A3%E6%B0%94%23) `1.1M 🔥` `NEW`
1. [长生钟意回归首发](https://s.weibo.com/weibo?q=%23%E9%95%BF%E7%94%9F%E9%92%9F%E6%84%8F%E5%9B%9E%E5%BD%92%E9%A6%96%E5%8F%91%23) `591.7K 🔥` `NEW`
1. [伊朗港口若遭袭将打击地区所有港口](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%B8%AF%E5%8F%A3%E8%8B%A5%E9%81%AD%E8%A2%AD%E5%B0%86%E6%89%93%E5%87%BB%E5%9C%B0%E5%8C%BA%E6%89%80%E6%9C%89%E6%B8%AF%E5%8F%A3%23) `572.4K 🔥` `NEW`
1. [董明珠的Ai全家桶亮相AWE](https://s.weibo.com/weibo?q=%23%E8%91%A3%E6%98%8E%E7%8F%A0%E7%9A%84Ai%E5%85%A8%E5%AE%B6%E6%A1%B6%E4%BA%AE%E7%9B%B8AWE%23) `557.3K 🔥` `NEW`
1. [多位人大代表呼吁提高农民养老金](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E4%BD%8D%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E5%91%BC%E5%90%81%E6%8F%90%E9%AB%98%E5%86%9C%E6%B0%91%E5%85%BB%E8%80%81%E9%87%91%23) `540.9K 🔥` `NEW`
1. [80元Lululemon发圈火爆是因为天热](https://s.weibo.com/weibo?q=%2380%E5%85%83Lululemon%E5%8F%91%E5%9C%88%E7%81%AB%E7%88%86%E6%98%AF%E5%9B%A0%E4%B8%BA%E5%A4%A9%E7%83%AD%23) `520.9K 🔥` `NEW`
1. [姜贞羽无限超越班路透](https://s.weibo.com/weibo?q=%23%E5%A7%9C%E8%B4%9E%E7%BE%BD%E6%97%A0%E9%99%90%E8%B6%85%E8%B6%8A%E7%8F%AD%E8%B7%AF%E9%80%8F%23) `504.8K 🔥` `NEW`
1. [苹果最贵手机要来了](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%9C%80%E8%B4%B5%E6%89%8B%E6%9C%BA%E8%A6%81%E6%9D%A5%E4%BA%86%23) `501.4K 🔥` `NEW`
1. [田曦薇第一位双平台破万女演员](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E7%AC%AC%E4%B8%80%E4%BD%8D%E5%8F%8C%E5%B9%B3%E5%8F%B0%E7%A0%B4%E4%B8%87%E5%A5%B3%E6%BC%94%E5%91%98%23) `474.0K 🔥` `NEW`
1. [代表说农民交的公粮就等于交了社保](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%86%9C%E6%B0%91%E4%BA%A4%E7%9A%84%E5%85%AC%E7%B2%AE%E5%B0%B1%E7%AD%89%E4%BA%8E%E4%BA%A4%E4%BA%86%E7%A4%BE%E4%BF%9D%23) `404.8K 🔥` `NEW`
1. [景区买个水果捞没想到切完多了 (I bought some fruit in the scenic spot, but I didn’t expect that it would be too much to cut.)](https://s.weibo.com/weibo?q=%23%E6%99%AF%E5%8C%BA%E4%B9%B0%E4%B8%AA%E6%B0%B4%E6%9E%9C%E6%8D%9E%E6%B2%A1%E6%83%B3%E5%88%B0%E5%88%87%E5%AE%8C%E5%A4%9A%E4%BA%86%23) `381.4K 🔥` `NEW`
1. [狗 人我讨厌坐飞机](https://s.weibo.com/weibo?q=%23%E7%8B%97%20%E4%BA%BA%E6%88%91%E8%AE%A8%E5%8E%8C%E5%9D%90%E9%A3%9E%E6%9C%BA%23) `317.6K 🔥` `NEW`
1. [伊总统提出结束战争3大必要条件](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%80%BB%E7%BB%9F%E6%8F%90%E5%87%BA%E7%BB%93%E6%9D%9F%E6%88%98%E4%BA%893%E5%A4%A7%E5%BF%85%E8%A6%81%E6%9D%A1%E4%BB%B6%23) `317.6K 🔥` `NEW`
1. [同工不同酬的劳务派遣制度该废止了](https://s.weibo.com/weibo?q=%23%E5%90%8C%E5%B7%A5%E4%B8%8D%E5%90%8C%E9%85%AC%E7%9A%84%E5%8A%B3%E5%8A%A1%E6%B4%BE%E9%81%A3%E5%88%B6%E5%BA%A6%E8%AF%A5%E5%BA%9F%E6%AD%A2%E4%BA%86%23) `317.3K 🔥` `NEW`
1. [鹿晗新商务](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E6%96%B0%E5%95%86%E5%8A%A1%23) `316.7K 🔥` `NEW`
1. [伴娘回应婚礼偶遇吴彦祖代旭井胧](https://s.weibo.com/weibo?q=%23%E4%BC%B4%E5%A8%98%E5%9B%9E%E5%BA%94%E5%A9%9A%E7%A4%BC%E5%81%B6%E9%81%87%E5%90%B4%E5%BD%A6%E7%A5%96%E4%BB%A3%E6%97%AD%E4%BA%95%E8%83%A7%23) `316.6K 🔥` `NEW`
1. [我国灵活就业人员超2.4亿](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E7%81%B5%E6%B4%BB%E5%B0%B1%E4%B8%9A%E4%BA%BA%E5%91%98%E8%B6%852.4%E4%BA%BF%23) `316.5K 🔥` `NEW`
1. [张凌赫回应逐玉双平台破万](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%9B%9E%E5%BA%94%E9%80%90%E7%8E%89%E5%8F%8C%E5%B9%B3%E5%8F%B0%E7%A0%B4%E4%B8%87%23) `316.0K 🔥` `NEW`
1. [东北阿姨坐5小时高铁后把座椅全立直](https://s.weibo.com/weibo?q=%23%E4%B8%9C%E5%8C%97%E9%98%BF%E5%A7%A8%E5%9D%905%E5%B0%8F%E6%97%B6%E9%AB%98%E9%93%81%E5%90%8E%E6%8A%8A%E5%BA%A7%E6%A4%85%E5%85%A8%E7%AB%8B%E7%9B%B4%23) `315.1K 🔥` `NEW`
1. [23岁牛散5000万买股浮盈超4100万](https://s.weibo.com/weibo?q=%2323%E5%B2%81%E7%89%9B%E6%95%A35000%E4%B8%87%E4%B9%B0%E8%82%A1%E6%B5%AE%E7%9B%88%E8%B6%854100%E4%B8%87%23) `313.9K 🔥` `NEW`
1. [章子怡求剧本 (Zhang Ziyi asks for script)](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E5%AD%90%E6%80%A1%E6%B1%82%E5%89%A7%E6%9C%AC%23) `313.7K 🔥` `NEW`
1. [KPL](https://s.weibo.com/weibo?q=%23KPL%23) `313.3K 🔥` `NEW`
1. [伊朗与黎巴嫩真主党联合作战](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8E%E9%BB%8E%E5%B7%B4%E5%AB%A9%E7%9C%9F%E4%B8%BB%E5%85%9A%E8%81%94%E5%90%88%E4%BD%9C%E6%88%98%23) `311.6K 🔥` `NEW`
1. [刘亦菲早春穿搭](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E6%97%A9%E6%98%A5%E7%A9%BF%E6%90%AD%23) `311.0K 🔥` `NEW`
1. [影视聚焦 逐玉](https://s.weibo.com/weibo?q=%23%E5%BD%B1%E8%A7%86%E8%81%9A%E7%84%A6%20%E9%80%90%E7%8E%89%23) `310.5K 🔥` `NEW`
1. [伊朗以色列德黑兰上空持续交战](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BB%A5%E8%89%B2%E5%88%97%E5%BE%B7%E9%BB%91%E5%85%B0%E4%B8%8A%E7%A9%BA%E6%8C%81%E7%BB%AD%E4%BA%A4%E6%88%98%23) `309.7K 🔥` `NEW`
1. [朴综星疑似回应李羲承退团](https://s.weibo.com/weibo?q=%23%E6%9C%B4%E7%BB%BC%E6%98%9F%E7%96%91%E4%BC%BC%E5%9B%9E%E5%BA%94%E6%9D%8E%E7%BE%B2%E6%89%BF%E9%80%80%E5%9B%A2%23) `309.1K 🔥` `NEW`
1. [黄油年糕在韩国流行](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%B2%B9%E5%B9%B4%E7%B3%95%E5%9C%A8%E9%9F%A9%E5%9B%BD%E6%B5%81%E8%A1%8C%23) `308.5K 🔥` `NEW`
1. [穆祉丞官宣加入周五晚高疯](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%E5%AE%98%E5%AE%A3%E5%8A%A0%E5%85%A5%E5%91%A8%E4%BA%94%E6%99%9A%E9%AB%98%E7%96%AF%23) `308.0K 🔥` `NEW`
1. [美国将释放1.72亿桶战略石油储备](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%B0%86%E9%87%8A%E6%94%BE1.72%E4%BA%BF%E6%A1%B6%E6%88%98%E7%95%A5%E7%9F%B3%E6%B2%B9%E5%82%A8%E5%A4%87%23) `307.6K 🔥` `NEW`
1. [植树节 (Arbor Day)](https://s.weibo.com/weibo?q=%23%E6%A4%8D%E6%A0%91%E8%8A%82%23) `305.1K 🔥` `NEW`
1. [王一博还配了bgm](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%BF%98%E9%85%8D%E4%BA%86bgm%23) `304.6K 🔥` `NEW`
1. [Lululemon客服回应80元发圈售罄](https://s.weibo.com/weibo?q=%23Lululemon%E5%AE%A2%E6%9C%8D%E5%9B%9E%E5%BA%9480%E5%85%83%E5%8F%91%E5%9C%88%E5%94%AE%E7%BD%84%23) `304.0K 🔥` `NEW`
1. [联系导师的第一句话就写错了](https://s.weibo.com/weibo?q=%23%E8%81%94%E7%B3%BB%E5%AF%BC%E5%B8%88%E7%9A%84%E7%AC%AC%E4%B8%80%E5%8F%A5%E8%AF%9D%E5%B0%B1%E5%86%99%E9%94%99%E4%BA%86%23) `303.6K 🔥` `NEW`
1. [雷军回应小米手机龙虾](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%9B%9E%E5%BA%94%E5%B0%8F%E7%B1%B3%E6%89%8B%E6%9C%BA%E9%BE%99%E8%99%BE%23) `303.2K 🔥` `NEW`
1. [巴黎圣日耳曼5比2切尔西](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E9%BB%8E%E5%9C%A3%E6%97%A5%E8%80%B3%E6%9B%BC5%E6%AF%942%E5%88%87%E5%B0%94%E8%A5%BF%23) `302.7K 🔥` `NEW`
1. [建议年假天数按工龄递增 (It is recommended that the number of annual leave days increases according to seniority)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B9%B4%E5%81%87%E5%A4%A9%E6%95%B0%E6%8C%89%E5%B7%A5%E9%BE%84%E9%80%92%E5%A2%9E%23) `768.3K 🔥` `+430%`
1. [公积金提取 (Provident fund withdrawal)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E7%A7%AF%E9%87%91%E6%8F%90%E5%8F%96%23) `317.1K 🔥` `+209%`
1. [3名美国富豪强奸性侵60名女性 (3 wealthy Americans raped and sexually assaulted 60 women)](https://s.weibo.com/weibo?q=%233%E5%90%8D%E7%BE%8E%E5%9B%BD%E5%AF%8C%E8%B1%AA%E5%BC%BA%E5%A5%B8%E6%80%A7%E4%BE%B560%E5%90%8D%E5%A5%B3%E6%80%A7%23) `316.9K 🔥` `+132%`
1. [曝李鹤来退出SMTR25](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%9D%8E%E9%B9%A4%E6%9D%A5%E9%80%80%E5%87%BASMTR25%23) `312.7K 🔥` `+155%`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `312.0K 🔥` `+206%`
1. [公积金改革大潮真的来了 (The tide of provident fund reform is really coming)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E7%A7%AF%E9%87%91%E6%94%B9%E9%9D%A9%E5%A4%A7%E6%BD%AE%E7%9C%9F%E7%9A%84%E6%9D%A5%E4%BA%86%23) `306.8K 🔥` `+135%`
1. [逐玉双平台破万 (Zhuyu double platform breaks 10,000)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8C%E5%B9%B3%E5%8F%B0%E7%A0%B4%E4%B8%87%23) `301.8K 🔥` `+148%`
1. [解读国家账本看数字背后 (Interpret the national account books and see behind the numbers)](https://s.weibo.com/weibo?q=%23%E8%A7%A3%E8%AF%BB%E5%9B%BD%E5%AE%B6%E8%B4%A6%E6%9C%AC%E7%9C%8B%E6%95%B0%E5%AD%97%E8%83%8C%E5%90%8E%23) `610.4K 🔥`
1. [王濛拟被破格晋升 (Wang Meng is scheduled to be promoted under unusual circumstances)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%E6%8B%9F%E8%A2%AB%E7%A0%B4%E6%A0%BC%E6%99%8B%E5%8D%87%23) `604.4K 🔥`
1. [3月12日两会日程 (Agenda for the two sessions on March 12)](https://s.weibo.com/weibo?q=%233%E6%9C%8812%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%23) `552.8K 🔥`
1. [1斤赘肉换1斤牛肉已超千人报名 (Over a thousand people have signed up to exchange 1 pound of fat for 1 pound of beef)](https://s.weibo.com/weibo?q=%231%E6%96%A4%E8%B5%98%E8%82%89%E6%8D%A21%E6%96%A4%E7%89%9B%E8%82%89%E5%B7%B2%E8%B6%85%E5%8D%83%E4%BA%BA%E6%8A%A5%E5%90%8D%23) `314.8K 🔥`
1. [分析称美国可能真的有点撑不住了](https://s.weibo.com/weibo?q=%23%E5%88%86%E6%9E%90%E7%A7%B0%E7%BE%8E%E5%9B%BD%E5%8F%AF%E8%83%BD%E7%9C%9F%E7%9A%84%E6%9C%89%E7%82%B9%E6%92%91%E4%B8%8D%E4%BD%8F%E4%BA%86%23) `306.3K 🔥`
1. [张凌赫田曦薇头纱照](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E5%A4%B4%E7%BA%B1%E7%85%A7%23) `317.5K 🔥` `-39%`
1. [骄阳似我 (The sun is like me)](https://s.weibo.com/weibo?q=%23%E9%AA%84%E9%98%B3%E4%BC%BC%E6%88%91%23) `317.2K 🔥` `-38%`
1. [塞尔维亚战机挂中国导弹亮相 (Serbian fighter jets unveiled with Chinese missiles)](https://s.weibo.com/weibo?q=%23%E5%A1%9E%E5%B0%94%E7%BB%B4%E4%BA%9A%E6%88%98%E6%9C%BA%E6%8C%82%E4%B8%AD%E5%9B%BD%E5%AF%BC%E5%BC%B9%E4%BA%AE%E7%9B%B8%23) `305.7K 🔥` `-71%`

Updated at 2026-03-12 10:51:02

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
