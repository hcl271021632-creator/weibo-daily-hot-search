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

1. [草莓价格跌至1元一斤 (Strawberry price drops to 1 yuan per pound)](https://s.weibo.com/weibo?q=%23%E8%8D%89%E8%8E%93%E4%BB%B7%E6%A0%BC%E8%B7%8C%E8%87%B31%E5%85%83%E4%B8%80%E6%96%A4%23) `1.1M 🔥` `NEW`
1. [FIBA国际篮联向中国男篮致歉](https://s.weibo.com/weibo?q=%23FIBA%E5%9B%BD%E9%99%85%E7%AF%AE%E8%81%94%E5%90%91%E4%B8%AD%E5%9B%BD%E7%94%B7%E7%AF%AE%E8%87%B4%E6%AD%89%23) `154.2K 🔥` `NEW`
1. [孙颖莎vs石洵瑶](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E7%9F%B3%E6%B4%B5%E7%91%B6%23) `148.4K 🔥` `NEW`
1. [女子拒同房不离婚为何引争议](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%8B%92%E5%90%8C%E6%88%BF%E4%B8%8D%E7%A6%BB%E5%A9%9A%E4%B8%BA%E4%BD%95%E5%BC%95%E4%BA%89%E8%AE%AE%23) `145.4K 🔥` `NEW`
1. [一点点资助男孩长期班级前三](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E9%95%BF%E6%9C%9F%E7%8F%AD%E7%BA%A7%E5%89%8D%E4%B8%89%23) `142.9K 🔥` `NEW`
1. [朱志鑫直播](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E5%BF%97%E9%91%AB%E7%9B%B4%E6%92%AD%23) `139.8K 🔥` `NEW`
1. [左航直播](https://s.weibo.com/weibo?q=%23%E5%B7%A6%E8%88%AA%E7%9B%B4%E6%92%AD%23) `136.4K 🔥` `NEW`
1. [下一个是谁 啊吗粽](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%98%AF%E8%B0%81%20%E5%95%8A%E5%90%97%E7%B2%BD%23) `132.2K 🔥` `NEW`
1. [中方回应巴拿马港口问题](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E5%B7%B4%E6%8B%BF%E9%A9%AC%E6%B8%AF%E5%8F%A3%E9%97%AE%E9%A2%98%23) `127.5K 🔥` `NEW`
1. [杨洋不让江山造型路透](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E9%80%A0%E5%9E%8B%E8%B7%AF%E9%80%8F%23) `127.4K 🔥` `NEW`
1. [X电竞打WBG (X E-sports playing WBG)](https://s.weibo.com/weibo?q=%23X%E7%94%B5%E7%AB%9E%E6%89%93WBG%23) `119.7K 🔥` `NEW`
1. [宋威龙都不一定生得出这么像的](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%A8%81%E9%BE%99%E9%83%BD%E4%B8%8D%E4%B8%80%E5%AE%9A%E7%94%9F%E5%BE%97%E5%87%BA%E8%BF%99%E4%B9%88%E5%83%8F%E7%9A%84%23) `112.2K 🔥` `NEW`
1. [杨幂主动问碳酸需不需要合照](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E4%B8%BB%E5%8A%A8%E9%97%AE%E7%A2%B3%E9%85%B8%E9%9C%80%E4%B8%8D%E9%9C%80%E8%A6%81%E5%90%88%E7%85%A7%23) `109.4K 🔥` `NEW`
1. [养过小孩的才知道他有多会教](https://s.weibo.com/weibo?q=%23%E5%85%BB%E8%BF%87%E5%B0%8F%E5%AD%A9%E7%9A%84%E6%89%8D%E7%9F%A5%E9%81%93%E4%BB%96%E6%9C%89%E5%A4%9A%E4%BC%9A%E6%95%99%23) `108.8K 🔥` `NEW`
1. [COA9抽签仪式](https://s.weibo.com/weibo?q=%23COA9%E6%8A%BD%E7%AD%BE%E4%BB%AA%E5%BC%8F%23) `94.7K 🔥` `NEW`
1. [教练说谢娜要是从小练滑雪能拿金牌](https://s.weibo.com/weibo?q=%23%E6%95%99%E7%BB%83%E8%AF%B4%E8%B0%A2%E5%A8%9C%E8%A6%81%E6%98%AF%E4%BB%8E%E5%B0%8F%E7%BB%83%E6%BB%91%E9%9B%AA%E8%83%BD%E6%8B%BF%E9%87%91%E7%89%8C%23) `92.5K 🔥` `NEW`
1. [一锅馒头死一个是为什么](https://s.weibo.com/weibo?q=%23%E4%B8%80%E9%94%85%E9%A6%92%E5%A4%B4%E6%AD%BB%E4%B8%80%E4%B8%AA%E6%98%AF%E4%B8%BA%E4%BB%80%E4%B9%88%23) `90.8K 🔥` `NEW`
1. [下一个是谁 (who is next)](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%98%AF%E8%B0%81%23) `452.9K 🔥` `+402%`
1. [退房的时候前台拿了个徐福记的糖纸](https://s.weibo.com/weibo?q=%23%E9%80%80%E6%88%BF%E7%9A%84%E6%97%B6%E5%80%99%E5%89%8D%E5%8F%B0%E6%8B%BF%E4%BA%86%E4%B8%AA%E5%BE%90%E7%A6%8F%E8%AE%B0%E7%9A%84%E7%B3%96%E7%BA%B8%23) `427.4K 🔥` `+309%`
1. [德国总理在杭州吃了西湖醋鱼东坡肉](https://s.weibo.com/weibo?q=%23%E5%BE%B7%E5%9B%BD%E6%80%BB%E7%90%86%E5%9C%A8%E6%9D%AD%E5%B7%9E%E5%90%83%E4%BA%86%E8%A5%BF%E6%B9%96%E9%86%8B%E9%B1%BC%E4%B8%9C%E5%9D%A1%E8%82%89%23) `276.0K 🔥` `+161%`
1. [张凌赫感谢林俊杰](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%84%9F%E8%B0%A2%E6%9E%97%E4%BF%8A%E6%9D%B0%23) `145.9K 🔥` `+66%`
1. [你的刷牙时间可能一直是错的 (You may have been brushing your teeth at the wrong time all along)](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E7%9A%84%E5%88%B7%E7%89%99%E6%97%B6%E9%97%B4%E5%8F%AF%E8%83%BD%E4%B8%80%E7%9B%B4%E6%98%AF%E9%94%99%E7%9A%84%23) `140.5K 🔥` `+62%`
1. [于正新剧宣传博被说低俗](https://s.weibo.com/weibo?q=%23%E4%BA%8E%E6%AD%A3%E6%96%B0%E5%89%A7%E5%AE%A3%E4%BC%A0%E5%8D%9A%E8%A2%AB%E8%AF%B4%E4%BD%8E%E4%BF%97%23) `139.1K 🔥` `+24%`
1. [AG对战RW](https://s.weibo.com/weibo?q=%23AG%E5%AF%B9%E6%88%98RW%23) `138.9K 🔥` `+22%`
1. [被男方指婚后拒绝同房女方发声](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%94%B7%E6%96%B9%E6%8C%87%E5%A9%9A%E5%90%8E%E6%8B%92%E7%BB%9D%E5%90%8C%E6%88%BF%E5%A5%B3%E6%96%B9%E5%8F%91%E5%A3%B0%23) `128.4K 🔥` `+51%`
1. [白宇前女友说终于有了很骄傲的感觉](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%87%E5%89%8D%E5%A5%B3%E5%8F%8B%E8%AF%B4%E7%BB%88%E4%BA%8E%E6%9C%89%E4%BA%86%E5%BE%88%E9%AA%84%E5%82%B2%E7%9A%84%E6%84%9F%E8%A7%89%23) `116.1K 🔥` `+31%`
1. [妈妈在女儿婚礼上美出圈](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9C%A8%E5%A5%B3%E5%84%BF%E5%A9%9A%E7%A4%BC%E4%B8%8A%E7%BE%8E%E5%87%BA%E5%9C%88%23) `789.8K 🔥`
1. [数读春节消费市场年味十足 (Digital reading of the Spring Festival consumer market is full of new year flavor)](https://s.weibo.com/weibo?q=%23%E6%95%B0%E8%AF%BB%E6%98%A5%E8%8A%82%E6%B6%88%E8%B4%B9%E5%B8%82%E5%9C%BA%E5%B9%B4%E5%91%B3%E5%8D%81%E8%B6%B3%23) `615.4K 🔥`
1. [三星S26 (Samsung S26)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%98%9FS26%23) `607.2K 🔥`
1. [白敬亭章若楠 二搭 (Bai Jingting, Zhang Ruonan, Er Da)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E7%AB%A0%E8%8B%A5%E6%A5%A0%20%E4%BA%8C%E6%90%AD%23) `552.6K 🔥`
1. [MBTI人格更新啦](https://s.weibo.com/weibo?q=%23MBTI%E4%BA%BA%E6%A0%BC%E6%9B%B4%E6%96%B0%E5%95%A6%23) `357.3K 🔥`
1. [女孩遭猥亵爷爷维权被要求别声张 (A girl was molested and her grandfather defended her rights and was asked not to speak out)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E9%81%AD%E7%8C%A5%E4%BA%B5%E7%88%B7%E7%88%B7%E7%BB%B4%E6%9D%83%E8%A2%AB%E8%A6%81%E6%B1%82%E5%88%AB%E5%A3%B0%E5%BC%A0%23) `152.6K 🔥`
1. [镖人破十亿刀马谛听番外](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A0%B4%E5%8D%81%E4%BA%BF%E5%88%80%E9%A9%AC%E8%B0%9B%E5%90%AC%E7%95%AA%E5%A4%96%23) `147.5K 🔥`
1. [头像洁癖](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E5%83%8F%E6%B4%81%E7%99%96%23) `144.5K 🔥`
1. [女子婚内出轨同居犯重婚罪获刑](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%A9%9A%E5%86%85%E5%87%BA%E8%BD%A8%E5%90%8C%E5%B1%85%E7%8A%AF%E9%87%8D%E5%A9%9A%E7%BD%AA%E8%8E%B7%E5%88%91%23) `143.3K 🔥`
1. [李胜利的狱友repo (Li Shengli’s inmate repo)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%83%9C%E5%88%A9%E7%9A%84%E7%8B%B1%E5%8F%8Brepo%23) `142.5K 🔥`
1. [向华强 向佐不能搞老三老四](https://s.weibo.com/weibo?q=%23%E5%90%91%E5%8D%8E%E5%BC%BA%20%E5%90%91%E4%BD%90%E4%B8%8D%E8%83%BD%E6%90%9E%E8%80%81%E4%B8%89%E8%80%81%E5%9B%9B%23) `141.4K 🔥`
1. [见春天 陈飞宇王影璐 (See Spring Chen Feiyu Wang Yinglu)](https://s.weibo.com/weibo?q=%23%E8%A7%81%E6%98%A5%E5%A4%A9%20%E9%99%88%E9%A3%9E%E5%AE%87%E7%8E%8B%E5%BD%B1%E7%92%90%23) `131.3K 🔥`
1. [小徐六级277分](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%BE%90%E5%85%AD%E7%BA%A7277%E5%88%86%23) `124.6K 🔥`
1. [李亚鹏官宣与哥哥和解](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BA%9A%E9%B9%8F%E5%AE%98%E5%AE%A3%E4%B8%8E%E5%93%A5%E5%93%A5%E5%92%8C%E8%A7%A3%23) `108.6K 🔥`
1. [Tiffany卞耀汉结婚](https://s.weibo.com/weibo?q=%23Tiffany%E5%8D%9E%E8%80%80%E6%B1%89%E7%BB%93%E5%A9%9A%23) `108.4K 🔥`
1. [白鹿抢孩子咯](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E6%8A%A2%E5%AD%A9%E5%AD%90%E5%92%AF%23) `94.6K 🔥`
1. [姜妍常驻现在就出发](https://s.weibo.com/weibo?q=%23%E5%A7%9C%E5%A6%8D%E5%B8%B8%E9%A9%BB%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%91%23) `94.0K 🔥`
1. [魅族](https://s.weibo.com/weibo?q=%23%E9%AD%85%E6%97%8F%23) `93.0K 🔥`
1. [王天辰 孩子太多了养不起 (Wang Tianchen has too many children to raise.)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%A4%A9%E8%BE%B0%20%E5%AD%A9%E5%AD%90%E5%A4%AA%E5%A4%9A%E4%BA%86%E5%85%BB%E4%B8%8D%E8%B5%B7%23) `92.9K 🔥`
1. [腾讯感谢爱奇艺宣传逐玉](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E6%84%9F%E8%B0%A2%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A3%E4%BC%A0%E9%80%90%E7%8E%89%23) `340.8K 🔥` `-69%`
1. [新娘出嫁徒手拔光碎发](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%A8%98%E5%87%BA%E5%AB%81%E5%BE%92%E6%89%8B%E6%8B%94%E5%85%89%E7%A2%8E%E5%8F%91%23) `158.2K 🔥` `-55%`
1. [现在就出发4 (Let's go now 4)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%23) `148.0K 🔥` `-54%`
1. [不建议在朋友圈展示技能 (It is not recommended to show skills in the circle of friends)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%BB%BA%E8%AE%AE%E5%9C%A8%E6%9C%8B%E5%8F%8B%E5%9C%88%E5%B1%95%E7%A4%BA%E6%8A%80%E8%83%BD%23) `146.7K 🔥` `-37%`
1. [超短学期](https://s.weibo.com/weibo?q=%23%E8%B6%85%E7%9F%AD%E5%AD%A6%E6%9C%9F%23) `132.8K 🔥` `-25%`
1. [43岁也能考编了 (I can take the exam at 43 years old)](https://s.weibo.com/weibo?q=%2343%E5%B2%81%E4%B9%9F%E8%83%BD%E8%80%83%E7%BC%96%E4%BA%86%23) `126.9K 🔥` `-46%`

Updated at 2026-02-27 18:58:27

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
