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

1. [警方通报男子窜至某小区抢劫致1死 (The police reported that a man ran into a community and robbed one person to death.)](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E7%94%B7%E5%AD%90%E7%AA%9C%E8%87%B3%E6%9F%90%E5%B0%8F%E5%8C%BA%E6%8A%A2%E5%8A%AB%E8%87%B41%E6%AD%BB%23) `1.1M 🔥` `NEW`
1. [周冬雨素颜录节目](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%AC%E9%9B%A8%E7%B4%A0%E9%A2%9C%E5%BD%95%E8%8A%82%E7%9B%AE%23) `247.4K 🔥` `NEW`
1. [以色列拦截伊朗导弹失败瞬间](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E6%8B%A6%E6%88%AA%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%A4%B1%E8%B4%A5%E7%9E%AC%E9%97%B4%23) `244.6K 🔥` `NEW`
1. [小猫不敢再随便熬夜了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E4%B8%8D%E6%95%A2%E5%86%8D%E9%9A%8F%E4%BE%BF%E7%86%AC%E5%A4%9C%E4%BA%86%23) `239.5K 🔥` `NEW`
1. [网友给逐玉的建议](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E7%BB%99%E9%80%90%E7%8E%89%E7%9A%84%E5%BB%BA%E8%AE%AE%23) `212.3K 🔥` `NEW`
1. [瞿颖西班牙 王俊凯新加坡](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%A5%BF%E7%8F%AD%E7%89%99%20%E7%8E%8B%E4%BF%8A%E5%87%AF%E6%96%B0%E5%8A%A0%E5%9D%A1%23) `177.0K 🔥` `NEW`
1. [上班自备厕纸](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%AD%E8%87%AA%E5%A4%87%E5%8E%95%E7%BA%B8%23) `147.5K 🔥` `NEW`
1. [英国男星死在普吉岛排水沟](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E7%94%B7%E6%98%9F%E6%AD%BB%E5%9C%A8%E6%99%AE%E5%90%89%E5%B2%9B%E6%8E%92%E6%B0%B4%E6%B2%9F%23) `146.2K 🔥` `NEW`
1. [钟丽缇女儿考拉争议](https://s.weibo.com/weibo?q=%23%E9%92%9F%E4%B8%BD%E7%BC%87%E5%A5%B3%E5%84%BF%E8%80%83%E6%8B%89%E4%BA%89%E8%AE%AE%23) `106.9K 🔥` `NEW`
1. [齐旻 烂人真心](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%97%BB%20%E7%83%82%E4%BA%BA%E7%9C%9F%E5%BF%83%23) `106.8K 🔥` `NEW`
1. [牛马面包 (cow horse bread)](https://s.weibo.com/weibo?q=%23%E7%89%9B%E9%A9%AC%E9%9D%A2%E5%8C%85%23) `106.8K 🔥` `NEW`
1. [鞠婧祎月鳞绮纪预约近200万](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E9%A2%84%E7%BA%A6%E8%BF%91200%E4%B8%87%23) `100.5K 🔥` `NEW`
1. [袁娅维威神V给内娱舞台上强度了](https://s.weibo.com/weibo?q=%23%E8%A2%81%E5%A8%85%E7%BB%B4%E5%A8%81%E7%A5%9EV%E7%BB%99%E5%86%85%E5%A8%B1%E8%88%9E%E5%8F%B0%E4%B8%8A%E5%BC%BA%E5%BA%A6%E4%BA%86%23) `87.0K 🔥` `NEW`
1. [广东横琴发布警情通报](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E6%A8%AA%E7%90%B4%E5%8F%91%E5%B8%83%E8%AD%A6%E6%83%85%E9%80%9A%E6%8A%A5%23) `87.0K 🔥` `NEW`
1. [去春游的人已经出片了](https://s.weibo.com/weibo?q=%23%E5%8E%BB%E6%98%A5%E6%B8%B8%E7%9A%84%E4%BA%BA%E5%B7%B2%E7%BB%8F%E5%87%BA%E7%89%87%E4%BA%86%23) `78.0K 🔥` `NEW`
1. [伊朗说允许非敌方船只通过霍尔木兹](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%AF%B4%E5%85%81%E8%AE%B8%E9%9D%9E%E6%95%8C%E6%96%B9%E8%88%B9%E5%8F%AA%E9%80%9A%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%23) `72.3K 🔥` `NEW`
1. [想要一份工作的年轻癌症患者](https://s.weibo.com/weibo?q=%23%E6%83%B3%E8%A6%81%E4%B8%80%E4%BB%BD%E5%B7%A5%E4%BD%9C%E7%9A%84%E5%B9%B4%E8%BD%BB%E7%99%8C%E7%97%87%E6%82%A3%E8%80%85%23) `69.6K 🔥` `NEW`
1. [碧血蝉全阵容官宣](https://s.weibo.com/weibo?q=%23%E7%A2%A7%E8%A1%80%E8%9D%89%E5%85%A8%E9%98%B5%E5%AE%B9%E5%AE%98%E5%AE%A3%23) `69.6K 🔥` `NEW`
1. [苦练书法多年终于有回报了](https://s.weibo.com/weibo?q=%23%E8%8B%A6%E7%BB%83%E4%B9%A6%E6%B3%95%E5%A4%9A%E5%B9%B4%E7%BB%88%E4%BA%8E%E6%9C%89%E5%9B%9E%E6%8A%A5%E4%BA%86%23) `62.5K 🔥` `NEW`
1. [大熊猫摔到地上有多Q弹](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%86%8A%E7%8C%AB%E6%91%94%E5%88%B0%E5%9C%B0%E4%B8%8A%E6%9C%89%E5%A4%9AQ%E5%BC%B9%23) `62.4K 🔥` `NEW`
1. [孟凡利 (Meng Fanli)](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%87%A1%E5%88%A9%23) `62.3K 🔥` `NEW`
1. [丈夫家暴后第一时间改银行卡密码](https://s.weibo.com/weibo?q=%23%E4%B8%88%E5%A4%AB%E5%AE%B6%E6%9A%B4%E5%90%8E%E7%AC%AC%E4%B8%80%E6%97%B6%E9%97%B4%E6%94%B9%E9%93%B6%E8%A1%8C%E5%8D%A1%E5%AF%86%E7%A0%81%23) `58.2K 🔥` `NEW`
1. [名侦探学院](https://s.weibo.com/weibo?q=%23%E5%90%8D%E4%BE%A6%E6%8E%A2%E5%AD%A6%E9%99%A2%23) `55.2K 🔥` `NEW`
1. [没有勾心斗角的工作](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E6%9C%89%E5%8B%BE%E5%BF%83%E6%96%97%E8%A7%92%E7%9A%84%E5%B7%A5%E4%BD%9C%23) `55.0K 🔥` `NEW`
1. [梅姨为何难抓](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E4%B8%BA%E4%BD%95%E9%9A%BE%E6%8A%93%23) `54.9K 🔥` `NEW`
1. [校长回应江浙沪没有夜生活](https://s.weibo.com/weibo?q=%23%E6%A0%A1%E9%95%BF%E5%9B%9E%E5%BA%94%E6%B1%9F%E6%B5%99%E6%B2%AA%E6%B2%A1%E6%9C%89%E5%A4%9C%E7%94%9F%E6%B4%BB%23) `234.0K 🔥` `+23%`
1. [高以翔前女友BeIIa官宣怀孕](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%BB%A5%E7%BF%94%E5%89%8D%E5%A5%B3%E5%8F%8BBeIIa%E5%AE%98%E5%AE%A3%E6%80%80%E5%AD%95%23) `107.0K 🔥` `+94%`
1. [网警破获网络开盒案守护网络空间安全](https://s.weibo.com/weibo?q=%23%E7%BD%91%E8%AD%A6%E7%A0%B4%E8%8E%B7%E7%BD%91%E7%BB%9C%E5%BC%80%E7%9B%92%E6%A1%88%E5%AE%88%E6%8A%A4%E7%BD%91%E7%BB%9C%E7%A9%BA%E9%97%B4%E5%AE%89%E5%85%A8%23) `617.9K 🔥`
1. [顾客吃牛蛙天花板上掉出一条人腿 (A human leg fell out of the ceiling after a customer ate bullfrog)](https://s.weibo.com/weibo?q=%23%E9%A1%BE%E5%AE%A2%E5%90%83%E7%89%9B%E8%9B%99%E5%A4%A9%E8%8A%B1%E6%9D%BF%E4%B8%8A%E6%8E%89%E5%87%BA%E4%B8%80%E6%9D%A1%E4%BA%BA%E8%85%BF%23) `379.4K 🔥`
1. [千问崩了](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%E5%B4%A9%E4%BA%86%23) `226.9K 🔥`
1. [AI演员签约官宣](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%E7%AD%BE%E7%BA%A6%E5%AE%98%E5%AE%A3%23) `210.9K 🔥`
1. [金价 (gold price)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `106.9K 🔥`
1. [陈慧敏怀孕了](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%85%A7%E6%95%8F%E6%80%80%E5%AD%95%E4%BA%86%23) `106.9K 🔥`
1. [逐玉亲到腿软的路透要播了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E4%BA%B2%E5%88%B0%E8%85%BF%E8%BD%AF%E7%9A%84%E8%B7%AF%E9%80%8F%E8%A6%81%E6%92%AD%E4%BA%86%23) `72.2K 🔥`
1. [警方介入女子追打2岁宝宝](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E4%BB%8B%E5%85%A5%E5%A5%B3%E5%AD%90%E8%BF%BD%E6%89%932%E5%B2%81%E5%AE%9D%E5%AE%9D%23) `69.6K 🔥`
1. [虞书欣云初令杀青上班路透](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E4%BA%91%E5%88%9D%E4%BB%A4%E6%9D%80%E9%9D%92%E4%B8%8A%E7%8F%AD%E8%B7%AF%E9%80%8F%23) `67.0K 🔥`
1. [梅姨在广州三元里落网为不实消息](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%9C%A8%E5%B9%BF%E5%B7%9E%E4%B8%89%E5%85%83%E9%87%8C%E8%90%BD%E7%BD%91%E4%B8%BA%E4%B8%8D%E5%AE%9E%E6%B6%88%E6%81%AF%23) `756.6K 🔥` `-29%`
1. [逐玉反盗版声明 (Zhuyu Anti-Piracy Statement)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8D%E7%9B%97%E7%89%88%E5%A3%B0%E6%98%8E%23) `245.9K 🔥` `-38%`
1. [魏家凉皮汉堡](https://s.weibo.com/weibo?q=%23%E9%AD%8F%E5%AE%B6%E5%87%89%E7%9A%AE%E6%B1%89%E5%A0%A1%23) `218.2K 🔥` `-69%`
1. [半小时取鱼刺7小时修路震惊老外](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E5%B0%8F%E6%97%B6%E5%8F%96%E9%B1%BC%E5%88%BA7%E5%B0%8F%E6%97%B6%E4%BF%AE%E8%B7%AF%E9%9C%87%E6%83%8A%E8%80%81%E5%A4%96%23) `177.7K 🔥` `-77%`
1. [希林娜依高伯克利七年没毕业](https://s.weibo.com/weibo?q=%23%E5%B8%8C%E6%9E%97%E5%A8%9C%E4%BE%9D%E9%AB%98%E4%BC%AF%E5%85%8B%E5%88%A9%E4%B8%83%E5%B9%B4%E6%B2%A1%E6%AF%95%E4%B8%9A%23) `172.0K 🔥` `-34%`
1. [逐玉的兵 不贪盗版](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%9A%84%E5%85%B5%20%E4%B8%8D%E8%B4%AA%E7%9B%97%E7%89%88%23) `127.4K 🔥` `-27%`
1. [靳磊任深圳市委书记 (Jin Lei appointed as Shenzhen Municipal Party Committee Secretary)](https://s.weibo.com/weibo?q=%23%E9%9D%B3%E7%A3%8A%E4%BB%BB%E6%B7%B1%E5%9C%B3%E5%B8%82%E5%A7%94%E4%B9%A6%E8%AE%B0%23) `107.0K 🔥` `-54%`
1. [张佳宁说单眼皮因拍戏变不回来了](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BD%B3%E5%AE%81%E8%AF%B4%E5%8D%95%E7%9C%BC%E7%9A%AE%E5%9B%A0%E6%8B%8D%E6%88%8F%E5%8F%98%E4%B8%8D%E5%9B%9E%E6%9D%A5%E4%BA%86%23) `106.8K 🔥` `-42%`
1. [1200多家饭店拍黄瓜被举报 (More than 1,200 restaurants were reported for taking pictures of cucumbers)](https://s.weibo.com/weibo?q=%231200%E5%A4%9A%E5%AE%B6%E9%A5%AD%E5%BA%97%E6%8B%8D%E9%BB%84%E7%93%9C%E8%A2%AB%E4%B8%BE%E6%8A%A5%23) `88.2K 🔥` `-49%`
1. [逐玉男配林沐然涨粉101万](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%94%B7%E9%85%8D%E6%9E%97%E6%B2%90%E7%84%B6%E6%B6%A8%E7%B2%89101%E4%B8%87%23) `86.7K 🔥` `-58%`
1. [陈飞宇迪丽热巴5年前拍的杂志 (Magazines photographed by Chen Feiyu and Di Lieba 5 years ago)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B45%E5%B9%B4%E5%89%8D%E6%8B%8D%E7%9A%84%E6%9D%82%E5%BF%97%23) `83.6K 🔥` `-58%`
1. [一诺加盟我家那小子](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%AF%BA%E5%8A%A0%E7%9B%9F%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%23) `74.1K 🔥` `-57%`
1. [逐玉 盗版没弹幕快乐少一半](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%9B%97%E7%89%88%E6%B2%A1%E5%BC%B9%E5%B9%95%E5%BF%AB%E4%B9%90%E5%B0%91%E4%B8%80%E5%8D%8A%23) `72.4K 🔥` `-39%`
1. [梅姨假装答应同居老人领证后失联](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%81%87%E8%A3%85%E7%AD%94%E5%BA%94%E5%90%8C%E5%B1%85%E8%80%81%E4%BA%BA%E9%A2%86%E8%AF%81%E5%90%8E%E5%A4%B1%E8%81%94%23) `63.4K 🔥` `-51%`

Updated at 2026-03-22 15:05:06

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
