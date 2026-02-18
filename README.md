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

1. [日本要当冤大头了 (Japan is going to be taken advantage of)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E8%A6%81%E5%BD%93%E5%86%A4%E5%A4%A7%E5%A4%B4%E4%BA%86%23) `1.2M 🔥` `NEW`
1. [谷爱凌才是货真价实的夯爆了](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%89%8D%E6%98%AF%E8%B4%A7%E7%9C%9F%E4%BB%B7%E5%AE%9E%E7%9A%84%E5%A4%AF%E7%88%86%E4%BA%86%23) `827.0K 🔥` `NEW`
1. [值得一刷再刷的春晚瞬间](https://s.weibo.com/weibo?q=%23%E5%80%BC%E5%BE%97%E4%B8%80%E5%88%B7%E5%86%8D%E5%88%B7%E7%9A%84%E6%98%A5%E6%99%9A%E7%9E%AC%E9%97%B4%23) `642.0K 🔥` `NEW`
1. [春节AI美食](https://s.weibo.com/weibo?q=%23%E6%98%A5%E8%8A%82AI%E7%BE%8E%E9%A3%9F%23) `581.6K 🔥` `NEW`
1. [丞磊真的读了与妻书](https://s.weibo.com/weibo?q=%23%E4%B8%9E%E7%A3%8A%E7%9C%9F%E7%9A%84%E8%AF%BB%E4%BA%86%E4%B8%8E%E5%A6%BB%E4%B9%A6%23) `563.6K 🔥` `NEW`
1. [谷爱凌 顶级alpha](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%20%E9%A1%B6%E7%BA%A7alpha%23) `250.1K 🔥` `NEW`
1. [大年初二不能做哪些事](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%8C%E4%B8%8D%E8%83%BD%E5%81%9A%E5%93%AA%E4%BA%9B%E4%BA%8B%23) `248.7K 🔥` `NEW`
1. [镖人口碑](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E5%8F%A3%E7%A2%91%23) `247.4K 🔥` `NEW`
1. [回老家后根本没有穿衣焦虑](https://s.weibo.com/weibo?q=%23%E5%9B%9E%E8%80%81%E5%AE%B6%E5%90%8E%E6%A0%B9%E6%9C%AC%E6%B2%A1%E6%9C%89%E7%A9%BF%E8%A1%A3%E7%84%A6%E8%99%91%23) `244.4K 🔥` `NEW`
1. [拉宏桑春晚后台探班 没有一秒不好笑](https://s.weibo.com/weibo?q=%23%E6%8B%89%E5%AE%8F%E6%A1%91%E6%98%A5%E6%99%9A%E5%90%8E%E5%8F%B0%E6%8E%A2%E7%8F%AD%20%E6%B2%A1%E6%9C%89%E4%B8%80%E7%A7%92%E4%B8%8D%E5%A5%BD%E7%AC%91%23) `243.7K 🔥` `NEW`
1. [刘少昂林孝埈携手出战 (Liu Shaoang and Lin Xiaoqi join hands to fight)](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%B0%91%E6%98%82%E6%9E%97%E5%AD%9D%E5%9F%88%E6%90%BA%E6%89%8B%E5%87%BA%E6%88%98%23) `241.0K 🔥` `NEW`
1. [王楚然出圈镜头](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E5%87%BA%E5%9C%88%E9%95%9C%E5%A4%B4%23) `218.9K 🔥` `NEW`
1. [千问让散装苏超具象化了](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E8%AE%A9%E6%95%A3%E8%A3%85%E8%8B%8F%E8%B6%85%E5%85%B7%E8%B1%A1%E5%8C%96%E4%BA%86%23) `185.2K 🔥` `NEW`
1. [有游客大年初一捡漏机票出游](https://s.weibo.com/weibo?q=%23%E6%9C%89%E6%B8%B8%E5%AE%A2%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E6%8D%A1%E6%BC%8F%E6%9C%BA%E7%A5%A8%E5%87%BA%E6%B8%B8%23) `169.4K 🔥` `NEW`
1. [刘诗诗 美人落泪](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%AF%97%E8%AF%97%20%E7%BE%8E%E4%BA%BA%E8%90%BD%E6%B3%AA%23) `169.3K 🔥` `NEW`
1. [谈恋爱要跟有少年气的人谈](https://s.weibo.com/weibo?q=%23%E8%B0%88%E6%81%8B%E7%88%B1%E8%A6%81%E8%B7%9F%E6%9C%89%E5%B0%91%E5%B9%B4%E6%B0%94%E7%9A%84%E4%BA%BA%E8%B0%88%23) `166.0K 🔥` `NEW`
1. [大年初二不午睡](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%8C%E4%B8%8D%E5%8D%88%E7%9D%A1%23) `161.2K 🔥` `NEW`
1. [中国速滑男团0.09秒绝杀](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%80%9F%E6%BB%91%E7%94%B7%E5%9B%A20.09%E7%A7%92%E7%BB%9D%E6%9D%80%23) `159.9K 🔥` `NEW`
1. [女子楼道晾晒16斤咸肉撒手没](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%A5%BC%E9%81%93%E6%99%BE%E6%99%9216%E6%96%A4%E5%92%B8%E8%82%89%E6%92%92%E6%89%8B%E6%B2%A1%23) `149.3K 🔥` `NEW`
1. [小孩哥称在小区搞了2千多红包](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A9%E5%93%A5%E7%A7%B0%E5%9C%A8%E5%B0%8F%E5%8C%BA%E6%90%9E%E4%BA%862%E5%8D%83%E5%A4%9A%E7%BA%A2%E5%8C%85%23) `119.2K 🔥` `NEW`
1. [王楚然美到成何体统 (How beautiful is Wang Churan?)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E7%84%B6%E7%BE%8E%E5%88%B0%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%23) `96.1K 🔥` `NEW`
1. [镖人玉面鬼](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%8E%89%E9%9D%A2%E9%AC%BC%23) `94.9K 🔥` `NEW`
1. [蓝溪镇完结](https://s.weibo.com/weibo?q=%23%E8%93%9D%E6%BA%AA%E9%95%87%E5%AE%8C%E7%BB%93%23) `93.3K 🔥` `NEW`
1. [春晚看迪丽热巴看入迷了](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E7%9C%8B%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%9C%8B%E5%85%A5%E8%BF%B7%E4%BA%86%23) `93.2K 🔥` `NEW`
1. [全家忘带钥匙小猫用5分钟开门](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%AE%B6%E5%BF%98%E5%B8%A6%E9%92%A5%E5%8C%99%E5%B0%8F%E7%8C%AB%E7%94%A85%E5%88%86%E9%92%9F%E5%BC%80%E9%97%A8%23) `83.6K 🔥` `NEW`
1. [刘三瞳回应抄袭](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%B8%89%E7%9E%B3%E5%9B%9E%E5%BA%94%E6%8A%84%E8%A2%AD%23) `83.0K 🔥` `NEW`
1. [央视春晚直播总收视份额创13年来新高](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%98%A5%E6%99%9A%E7%9B%B4%E6%92%AD%E6%80%BB%E6%94%B6%E8%A7%86%E4%BB%BD%E9%A2%9D%E5%88%9B13%E5%B9%B4%E6%9D%A5%E6%96%B0%E9%AB%98%23) `81.4K 🔥` `NEW`
1. [飞驰人生3成大年初一票房冠军](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E6%88%90%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%B8%80%E7%A5%A8%E6%88%BF%E5%86%A0%E5%86%9B%23) `81.2K 🔥` `NEW`
1. [小主人给狗狗拜年曾落水被狗救上岸](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%B8%BB%E4%BA%BA%E7%BB%99%E7%8B%97%E7%8B%97%E6%8B%9C%E5%B9%B4%E6%9B%BE%E8%90%BD%E6%B0%B4%E8%A2%AB%E7%8B%97%E6%95%91%E4%B8%8A%E5%B2%B8%23) `79.9K 🔥` `NEW`
1. [宇树科技CEO回应春晚款机器人](https://s.weibo.com/weibo?q=%23%E5%AE%87%E6%A0%91%E7%A7%91%E6%8A%80CEO%E5%9B%9E%E5%BA%94%E6%98%A5%E6%99%9A%E6%AC%BE%E6%9C%BA%E5%99%A8%E4%BA%BA%23) `79.9K 🔥` `NEW`
1. [哪些菜名提到就馋了 (Which dishes make me hungry just by mentioning them?)](https://s.weibo.com/weibo?q=%23%E5%93%AA%E4%BA%9B%E8%8F%9C%E5%90%8D%E6%8F%90%E5%88%B0%E5%B0%B1%E9%A6%8B%E4%BA%86%23) `78.8K 🔥` `NEW`
1. [陈小春父子三人共用一张脸](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%B0%8F%E6%98%A5%E7%88%B6%E5%AD%90%E4%B8%89%E4%BA%BA%E5%85%B1%E7%94%A8%E4%B8%80%E5%BC%A0%E8%84%B8%23) `78.0K 🔥` `NEW`
1. [过年期间的胃](https://s.weibo.com/weibo?q=%23%E8%BF%87%E5%B9%B4%E6%9C%9F%E9%97%B4%E7%9A%84%E8%83%83%23) `76.5K 🔥` `NEW`
1. [你说这是王安宇路演生图](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E8%AF%B4%E8%BF%99%E6%98%AF%E7%8E%8B%E5%AE%89%E5%AE%87%E8%B7%AF%E6%BC%94%E7%94%9F%E5%9B%BE%23) `73.0K 🔥` `NEW`
1. [王楠任主教练](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%A0%E4%BB%BB%E4%B8%BB%E6%95%99%E7%BB%83%23) `69.6K 🔥` `NEW`
1. [王一博闪耀动起来春晚舞台TOP1](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E9%97%AA%E8%80%80%E5%8A%A8%E8%B5%B7%E6%9D%A5%E6%98%A5%E6%99%9A%E8%88%9E%E5%8F%B0TOP1%23) `68.3K 🔥` `NEW`
1. [老款小孩](https://s.weibo.com/weibo?q=%23%E8%80%81%E6%AC%BE%E5%B0%8F%E5%AD%A9%23) `62.5K 🔥` `NEW`
1. [上门喂猫遇见了社恐猫](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E9%97%A8%E5%96%82%E7%8C%AB%E9%81%87%E8%A7%81%E4%BA%86%E7%A4%BE%E6%81%90%E7%8C%AB%23) `60.9K 🔥` `NEW`
1. [看熊出没孩子开心家长放心 (Watching bears come and go, children are happy, parents are reassured)](https://s.weibo.com/weibo?q=%23%E7%9C%8B%E7%86%8A%E5%87%BA%E6%B2%A1%E5%AD%A9%E5%AD%90%E5%BC%80%E5%BF%83%E5%AE%B6%E9%95%BF%E6%94%BE%E5%BF%83%23) `248.0K 🔥` `+314%`
1. [成何体统](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%23) `113.1K 🔥` `+556%`
1. [春晚总导演说贺花神非常非常难](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E6%80%BB%E5%AF%BC%E6%BC%94%E8%AF%B4%E8%B4%BA%E8%8A%B1%E7%A5%9E%E9%9D%9E%E5%B8%B8%E9%9D%9E%E5%B8%B8%E9%9A%BE%23) `109.5K 🔥` `+33%`
1. [B站语言类节目 赢麻了 (The language program at Station B is a winner)](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E8%AF%AD%E8%A8%80%E7%B1%BB%E8%8A%82%E7%9B%AE%20%E8%B5%A2%E9%BA%BB%E4%BA%86%23) `82.1K 🔥`
1. [父亲去世摆摊卖对联男孩母亲发声 (The mother of a boy selling couplets at a stall after his father passed away speaks out)](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E5%8E%BB%E4%B8%96%E6%91%86%E6%91%8A%E5%8D%96%E5%AF%B9%E8%81%94%E7%94%B7%E5%AD%A9%E6%AF%8D%E4%BA%B2%E5%8F%91%E5%A3%B0%23) `81.6K 🔥`
1. [蔡徐坤迪拜音乐节 (Cai Xukun Dubai Music Festival)](https://s.weibo.com/weibo?q=%23%E8%94%A1%E5%BE%90%E5%9D%A4%E8%BF%AA%E6%8B%9C%E9%9F%B3%E4%B9%90%E8%8A%82%23) `65.2K 🔥`
1. [2026新春走基层](https://s.weibo.com/weibo?q=%232026%E6%96%B0%E6%98%A5%E8%B5%B0%E5%9F%BA%E5%B1%82%23) `247.0K 🔥` `-62%`
1. [高市早苗内阁集体辞职 (Takaichi Sanae cabinet resigns en masse)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%86%85%E9%98%81%E9%9B%86%E4%BD%93%E8%BE%9E%E8%81%8C%23) `242.2K 🔥` `-78%`
1. [B站春晚 夯 (Station B Spring Festival Gala)](https://s.weibo.com/weibo?q=%23B%E7%AB%99%E6%98%A5%E6%99%9A%20%E5%A4%AF%23) `214.1K 🔥` `-74%`
1. [谷爱凌说痛失2块金牌说法太荒谬](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%AF%B4%E7%97%9B%E5%A4%B12%E5%9D%97%E9%87%91%E7%89%8C%E8%AF%B4%E6%B3%95%E5%A4%AA%E8%8D%92%E8%B0%AC%23) `98.8K 🔥` `-56%`
1. [李子柒在春晚后台手搓非遗饰品](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%AD%90%E6%9F%92%E5%9C%A8%E6%98%A5%E6%99%9A%E5%90%8E%E5%8F%B0%E6%89%8B%E6%90%93%E9%9D%9E%E9%81%97%E9%A5%B0%E5%93%81%23) `92.9K 🔥` `-66%`
1. [都穿亮片裙不告诉王玉雯](https://s.weibo.com/weibo?q=%23%E9%83%BD%E7%A9%BF%E4%BA%AE%E7%89%87%E8%A3%99%E4%B8%8D%E5%91%8A%E8%AF%89%E7%8E%8B%E7%8E%89%E9%9B%AF%23) `61.9K 🔥` `-42%`
1. [全妈回应全红婵退役计划 (Quan’s mother responds to Quan Hongchan’s retirement plan)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%A6%88%E5%9B%9E%E5%BA%94%E5%85%A8%E7%BA%A2%E5%A9%B5%E9%80%80%E5%BD%B9%E8%AE%A1%E5%88%92%23) `61.3K 🔥` `-84%`

Updated at 2026-02-18 11:42:15

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
