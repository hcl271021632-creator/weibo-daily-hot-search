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

1. [亲爱的客栈吸睛cp上线 (Dear Inn’s eye-catching CP is online)](https://s.weibo.com/weibo?q=%23%E4%BA%B2%E7%88%B1%E7%9A%84%E5%AE%A2%E6%A0%88%E5%90%B8%E7%9D%9Bcp%E4%B8%8A%E7%BA%BF%23) `179.0K 🔥` `NEW`
1. [谢征求婚](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%B1%82%E5%A9%9A%23) `172.0K 🔥` `NEW`
1. [建议发放历史贡献养老金](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%8F%91%E6%94%BE%E5%8E%86%E5%8F%B2%E8%B4%A1%E7%8C%AE%E5%85%BB%E8%80%81%E9%87%91%23) `161.6K 🔥` `NEW`
1. [手机价格大涨消费者发声](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E4%BB%B7%E6%A0%BC%E5%A4%A7%E6%B6%A8%E6%B6%88%E8%B4%B9%E8%80%85%E5%8F%91%E5%A3%B0%23) `159.3K 🔥` `NEW`
1. [研究称第二次怀孕会继续重塑大脑](https://s.weibo.com/weibo?q=%23%E7%A0%94%E7%A9%B6%E7%A7%B0%E7%AC%AC%E4%BA%8C%E6%AC%A1%E6%80%80%E5%AD%95%E4%BC%9A%E7%BB%A7%E7%BB%AD%E9%87%8D%E5%A1%91%E5%A4%A7%E8%84%91%23) `158.3K 🔥` `NEW`
1. [陈伟霆的老钱风怎么来的](https://s.weibo.com/weibo?q=%23%E9%99%88%E4%BC%9F%E9%9C%86%E7%9A%84%E8%80%81%E9%92%B1%E9%A3%8E%E6%80%8E%E4%B9%88%E6%9D%A5%E7%9A%84%23) `158.3K 🔥` `NEW`
1. [被盗国保琉璃竟在闲鱼公开售卖](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%9B%97%E5%9B%BD%E4%BF%9D%E7%90%89%E7%92%83%E7%AB%9F%E5%9C%A8%E9%97%B2%E9%B1%BC%E5%85%AC%E5%BC%80%E5%94%AE%E5%8D%96%23) `157.7K 🔥` `NEW`
1. [360元故意纹丑眉毛再套路4399元](https://s.weibo.com/weibo?q=%23360%E5%85%83%E6%95%85%E6%84%8F%E7%BA%B9%E4%B8%91%E7%9C%89%E6%AF%9B%E5%86%8D%E5%A5%97%E8%B7%AF4399%E5%85%83%23) `157.6K 🔥` `NEW`
1. [姓丁的有福了 丁永一](https://s.weibo.com/weibo?q=%23%E5%A7%93%E4%B8%81%E7%9A%84%E6%9C%89%E7%A6%8F%E4%BA%86%20%E4%B8%81%E6%B0%B8%E4%B8%80%23) `157.3K 🔥` `NEW`
1. [甲胺磷羊肉面与剧毒农药同名引争议](https://s.weibo.com/weibo?q=%23%E7%94%B2%E8%83%BA%E7%A3%B7%E7%BE%8A%E8%82%89%E9%9D%A2%E4%B8%8E%E5%89%A7%E6%AF%92%E5%86%9C%E8%8D%AF%E5%90%8C%E5%90%8D%E5%BC%95%E4%BA%89%E8%AE%AE%23) `78.4K 🔥` `NEW`
1. [大冰让做微商的女子讲行业内幕 (Dabing lets a woman doing micro-business tell the inside story of the industry)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%86%B0%E8%AE%A9%E5%81%9A%E5%BE%AE%E5%95%86%E7%9A%84%E5%A5%B3%E5%AD%90%E8%AE%B2%E8%A1%8C%E4%B8%9A%E5%86%85%E5%B9%95%23) `78.3K 🔥` `NEW`
1. [女子泰山插队被大妈一棍回击](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%B3%B0%E5%B1%B1%E6%8F%92%E9%98%9F%E8%A2%AB%E5%A4%A7%E5%A6%88%E4%B8%80%E6%A3%8D%E5%9B%9E%E5%87%BB%23) `77.0K 🔥` `NEW`
1. [小时候的愿望水灵灵实现了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E6%97%B6%E5%80%99%E7%9A%84%E6%84%BF%E6%9C%9B%E6%B0%B4%E7%81%B5%E7%81%B5%E5%AE%9E%E7%8E%B0%E4%BA%86%23) `76.7K 🔥` `NEW`
1. [穿普拉达的女王2手提包爆米花桶](https://s.weibo.com/weibo?q=%23%E7%A9%BF%E6%99%AE%E6%8B%89%E8%BE%BE%E7%9A%84%E5%A5%B3%E7%8E%8B2%E6%89%8B%E6%8F%90%E5%8C%85%E7%88%86%E7%B1%B3%E8%8A%B1%E6%A1%B6%23) `76.3K 🔥` `NEW`
1. [阎鹤祥从未否认自己是王一博](https://s.weibo.com/weibo?q=%23%E9%98%8E%E9%B9%A4%E7%A5%A5%E4%BB%8E%E6%9C%AA%E5%90%A6%E8%AE%A4%E8%87%AA%E5%B7%B1%E6%98%AF%E7%8E%8B%E4%B8%80%E5%8D%9A%23) `71.0K 🔥` `NEW`
1. [果然慈母多败咪](https://s.weibo.com/weibo?q=%23%E6%9E%9C%E7%84%B6%E6%85%88%E6%AF%8D%E5%A4%9A%E8%B4%A5%E5%92%AA%23) `70.5K 🔥` `NEW`
1. [缅甸电诈园困住少年威胁10年不放人](https://s.weibo.com/weibo?q=%23%E7%BC%85%E7%94%B8%E7%94%B5%E8%AF%88%E5%9B%AD%E5%9B%B0%E4%BD%8F%E5%B0%91%E5%B9%B4%E5%A8%81%E8%83%8110%E5%B9%B4%E4%B8%8D%E6%94%BE%E4%BA%BA%23) `66.8K 🔥` `NEW`
1. [丁程鑫偷偷回冬天](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E5%81%B7%E5%81%B7%E5%9B%9E%E5%86%AC%E5%A4%A9%23) `65.9K 🔥` `NEW`
1. [psd 不画绘旅人](https://s.weibo.com/weibo?q=%23psd%20%E4%B8%8D%E7%94%BB%E7%BB%98%E6%97%85%E4%BA%BA%23) `65.6K 🔥` `NEW`
1. [三亚偶遇张柏芝](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E5%81%B6%E9%81%87%E5%BC%A0%E6%9F%8F%E8%8A%9D%23) `65.5K 🔥` `NEW`
1. [瞿颖 他以为我命令他说中文 (Qu Ying, he thought I ordered him to speak Chinese)](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%20%E4%BB%96%E4%BB%A5%E4%B8%BA%E6%88%91%E5%91%BD%E4%BB%A4%E4%BB%96%E8%AF%B4%E4%B8%AD%E6%96%87%23) `64.9K 🔥` `NEW`
1. [这个春天再出发](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B8%AA%E6%98%A5%E5%A4%A9%E5%86%8D%E5%87%BA%E5%8F%91%23) `595.3K 🔥` `+172%`
1. [美国中期选举开战](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%AD%E6%9C%9F%E9%80%89%E4%B8%BE%E5%BC%80%E6%88%98%23) `235.8K 🔥` `+158%`
1. [中方向伊朗遇难学生家长援助20万美元 (China provides $200,000 in aid to parents of Iranian students killed)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%90%91%E4%BC%8A%E6%9C%97%E9%81%87%E9%9A%BE%E5%AD%A6%E7%94%9F%E5%AE%B6%E9%95%BF%E6%8F%B4%E5%8A%A920%E4%B8%87%E7%BE%8E%E5%85%83%23) `158.6K 🔥` `+53%`
1. [微信 朋友圈编辑 (WeChat Moments Editor)](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%20%E6%9C%8B%E5%8F%8B%E5%9C%88%E7%BC%96%E8%BE%91%23) `1.1M 🔥`
1. [国产手机涨价2000元 (Domestic mobile phone prices increase by 2,000 yuan)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E6%89%8B%E6%9C%BA%E6%B6%A8%E4%BB%B72000%E5%85%83%23) `766.9K 🔥`
1. [北京WBG对战ACT](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%ACWBG%E5%AF%B9%E6%88%98ACT%23) `158.8K 🔥`
1. [广电总局将公布演员番位规则 (The State Administration of Radio, Film and Television will announce the cast rules for actors)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E7%94%B5%E6%80%BB%E5%B1%80%E5%B0%86%E5%85%AC%E5%B8%83%E6%BC%94%E5%91%98%E7%95%AA%E4%BD%8D%E8%A7%84%E5%88%99%23) `158.7K 🔥`
1. [儿子遗体在泰医院失踪中国父亲报警](https://s.weibo.com/weibo?q=%23%E5%84%BF%E5%AD%90%E9%81%97%E4%BD%93%E5%9C%A8%E6%B3%B0%E5%8C%BB%E9%99%A2%E5%A4%B1%E8%B8%AA%E4%B8%AD%E5%9B%BD%E7%88%B6%E4%BA%B2%E6%8A%A5%E8%AD%A6%23) `158.4K 🔥`
1. [痞幼做医美了](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%81%9A%E5%8C%BB%E7%BE%8E%E4%BA%86%23) `158.2K 🔥`
1. [女子把过期牛奶给狗喝致其死亡](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%8A%8A%E8%BF%87%E6%9C%9F%E7%89%9B%E5%A5%B6%E7%BB%99%E7%8B%97%E5%96%9D%E8%87%B4%E5%85%B6%E6%AD%BB%E4%BA%A1%23) `157.4K 🔥`
1. [韩佳人化中国网红妆](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E4%BD%B3%E4%BA%BA%E5%8C%96%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BA%A2%E5%A6%86%23) `157.4K 🔥`
1. [女生照片遭一键脱衣发至色情网](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E7%85%A7%E7%89%87%E9%81%AD%E4%B8%80%E9%94%AE%E8%84%B1%E8%A1%A3%E5%8F%91%E8%87%B3%E8%89%B2%E6%83%85%E7%BD%91%23) `102.3K 🔥`
1. [漳州市市监局介入核实问题冻干草莓](https://s.weibo.com/weibo?q=%23%E6%BC%B3%E5%B7%9E%E5%B8%82%E5%B8%82%E7%9B%91%E5%B1%80%E4%BB%8B%E5%85%A5%E6%A0%B8%E5%AE%9E%E9%97%AE%E9%A2%98%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%23) `76.2K 🔥`
1. [头部演员片酬将发生结构性改变 (The salary of leading actors will undergo structural changes)](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E9%83%A8%E6%BC%94%E5%91%98%E7%89%87%E9%85%AC%E5%B0%86%E5%8F%91%E7%94%9F%E7%BB%93%E6%9E%84%E6%80%A7%E6%94%B9%E5%8F%98%23) `76.2K 🔥`
1. [王鹤润 王玉雯 (Wang Herun Wang Yuwen)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%B6%A6%20%E7%8E%8B%E7%8E%89%E9%9B%AF%23) `66.0K 🔥`
1. [张凌赫田曦薇挑衅经纪人](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%8C%91%E8%A1%85%E7%BB%8F%E7%BA%AA%E4%BA%BA%23) `302.8K 🔥` `-46%`
1. [冻干草莓 农药](https://s.weibo.com/weibo?q=%23%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%20%E5%86%9C%E8%8D%AF%23) `192.7K 🔥` `-68%`
1. [代表呼吁关注通信骚扰再抬头](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%91%BC%E5%90%81%E5%85%B3%E6%B3%A8%E9%80%9A%E4%BF%A1%E9%AA%9A%E6%89%B0%E5%86%8D%E6%8A%AC%E5%A4%B4%23) `165.5K 🔥` `-69%`
1. [47岁男子1000元彩礼娶82岁老人](https://s.weibo.com/weibo?q=%2347%E5%B2%81%E7%94%B7%E5%AD%901000%E5%85%83%E5%BD%A9%E7%A4%BC%E5%A8%B682%E5%B2%81%E8%80%81%E4%BA%BA%23) `159.2K 🔥` `-45%`
1. [严屹宽 双男主](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%20%E5%8F%8C%E7%94%B7%E4%B8%BB%23) `159.2K 🔥` `-54%`
1. [长期用小拇指托手机的后果 (The consequences of holding your phone with your little finger for a long time)](https://s.weibo.com/weibo?q=%23%E9%95%BF%E6%9C%9F%E7%94%A8%E5%B0%8F%E6%8B%87%E6%8C%87%E6%89%98%E6%89%8B%E6%9C%BA%E7%9A%84%E5%90%8E%E6%9E%9C%23) `158.9K 🔥` `-66%`
1. [中俄安理会硬刚美国 (China-Russia Security Council toughens the United States)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%BF%84%E5%AE%89%E7%90%86%E4%BC%9A%E7%A1%AC%E5%88%9A%E7%BE%8E%E5%9B%BD%23) `158.8K 🔥` `-72%`
1. [绩效 反人类](https://s.weibo.com/weibo?q=%23%E7%BB%A9%E6%95%88%20%E5%8F%8D%E4%BA%BA%E7%B1%BB%23) `158.0K 🔥` `-57%`
1. [卜凡 sk团播](https://s.weibo.com/weibo?q=%23%E5%8D%9C%E5%87%A1%20sk%E5%9B%A2%E6%92%AD%23) `157.9K 🔥` `-63%`
1. [安崎求职浪姐真的成功了 (An Qi’s job search for Sister Lang was really successful)](https://s.weibo.com/weibo?q=%23%E5%AE%89%E5%B4%8E%E6%B1%82%E8%81%8C%E6%B5%AA%E5%A7%90%E7%9C%9F%E7%9A%84%E6%88%90%E5%8A%9F%E4%BA%86%23) `157.8K 🔥` `-75%`
1. [中方支持伊朗人民渡过难关](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E6%94%AF%E6%8C%81%E4%BC%8A%E6%9C%97%E4%BA%BA%E6%B0%91%E6%B8%A1%E8%BF%87%E9%9A%BE%E5%85%B3%23) `121.6K 🔥` `-37%`
1. [刘国梁卸任世界乒联董事会主席](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%9B%BD%E6%A2%81%E5%8D%B8%E4%BB%BB%E4%B8%96%E7%95%8C%E4%B9%92%E8%81%94%E8%91%A3%E4%BA%8B%E4%BC%9A%E4%B8%BB%E5%B8%AD%23) `87.2K 🔥` `-82%`
1. [别让你的微信隐私在裸奔 (Don’t let your WeChat privacy slip away naked)](https://s.weibo.com/weibo?q=%23%E5%88%AB%E8%AE%A9%E4%BD%A0%E7%9A%84%E5%BE%AE%E4%BF%A1%E9%9A%90%E7%A7%81%E5%9C%A8%E8%A3%B8%E5%A5%94%23) `83.7K 🔥` `-79%`
1. [张杰鸟巢舞台概念图 (Zhang Jie Bird's Nest stage concept map)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E9%B8%9F%E5%B7%A2%E8%88%9E%E5%8F%B0%E6%A6%82%E5%BF%B5%E5%9B%BE%23) `81.5K 🔥` `-22%`
1. [沈月说不能留白鹿一个人](https://s.weibo.com/weibo?q=%23%E6%B2%88%E6%9C%88%E8%AF%B4%E4%B8%8D%E8%83%BD%E7%95%99%E7%99%BD%E9%B9%BF%E4%B8%80%E4%B8%AA%E4%BA%BA%23) `77.8K 🔥` `-39%`

Updated at 2026-03-13 17:41:55

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
