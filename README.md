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

1. [张雪说被资本搞懵了 (Zhang Xue said she was confused by capital.)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E8%AF%B4%E8%A2%AB%E8%B5%84%E6%9C%AC%E6%90%9E%E6%87%B5%E4%BA%86%23) `804.7K 🔥` `NEW`
1. [美国一婴儿光天化日在街头被枪杀](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%B8%80%E5%A9%B4%E5%84%BF%E5%85%89%E5%A4%A9%E5%8C%96%E6%97%A5%E5%9C%A8%E8%A1%97%E5%A4%B4%E8%A2%AB%E6%9E%AA%E6%9D%80%23) `226.8K 🔥` `NEW`
1. [金价](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%23) `219.9K 🔥` `NEW`
1. [Wayward曝369休息原因](https://s.weibo.com/weibo?q=%23Wayward%E6%9B%9D369%E4%BC%91%E6%81%AF%E5%8E%9F%E5%9B%A0%23) `165.8K 🔥` `NEW`
1. [这个代言是时团自己谈下来的吧](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B8%AA%E4%BB%A3%E8%A8%80%E6%98%AF%E6%97%B6%E5%9B%A2%E8%87%AA%E5%B7%B1%E8%B0%88%E4%B8%8B%E6%9D%A5%E7%9A%84%E5%90%A7%23) `162.4K 🔥` `NEW`
1. [刘亦菲老钱风大片](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E8%80%81%E9%92%B1%E9%A3%8E%E5%A4%A7%E7%89%87%23) `161.4K 🔥` `NEW`
1. [吴佩孚公馆转卖背后的隐秘交易](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%A9%E5%AD%9A%E5%85%AC%E9%A6%86%E8%BD%AC%E5%8D%96%E8%83%8C%E5%90%8E%E7%9A%84%E9%9A%90%E7%A7%98%E4%BA%A4%E6%98%93%23) `145.7K 🔥` `NEW`
1. [严屹宽曝张凌赫挨鞭子真打了108次](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%E6%9B%9D%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%8C%A8%E9%9E%AD%E5%AD%90%E7%9C%9F%E6%89%93%E4%BA%86108%E6%AC%A1%23) `143.1K 🔥` `NEW`
1. [法国车手34岁夺冠感谢张雪机车圆梦](https://s.weibo.com/weibo?q=%23%E6%B3%95%E5%9B%BD%E8%BD%A6%E6%89%8B34%E5%B2%81%E5%A4%BA%E5%86%A0%E6%84%9F%E8%B0%A2%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E5%9C%86%E6%A2%A6%23) `132.9K 🔥` `NEW`
1. [阿花花酱 优思益](https://s.weibo.com/weibo?q=%23%E9%98%BF%E8%8A%B1%E8%8A%B1%E9%85%B1%20%E4%BC%98%E6%80%9D%E7%9B%8A%23) `132.5K 🔥` `NEW`
1. [当我凌晨5点去健身 (When I go to the gym at 5 a.m.)](https://s.weibo.com/weibo?q=%23%E5%BD%93%E6%88%91%E5%87%8C%E6%99%A85%E7%82%B9%E5%8E%BB%E5%81%A5%E8%BA%AB%23) `118.0K 🔥` `NEW`
1. [教师被AI造谣猥亵入狱10年](https://s.weibo.com/weibo?q=%23%E6%95%99%E5%B8%88%E8%A2%ABAI%E9%80%A0%E8%B0%A3%E7%8C%A5%E4%BA%B5%E5%85%A5%E7%8B%B110%E5%B9%B4%23) `113.6K 🔥` `NEW`
1. [临终老人怕拖累子女恳求医生想早走](https://s.weibo.com/weibo?q=%23%E4%B8%B4%E7%BB%88%E8%80%81%E4%BA%BA%E6%80%95%E6%8B%96%E7%B4%AF%E5%AD%90%E5%A5%B3%E6%81%B3%E6%B1%82%E5%8C%BB%E7%94%9F%E6%83%B3%E6%97%A9%E8%B5%B0%23) `107.4K 🔥` `NEW`
1. [多位明星曾直播卖优思益](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E4%BD%8D%E6%98%8E%E6%98%9F%E6%9B%BE%E7%9B%B4%E6%92%AD%E5%8D%96%E4%BC%98%E6%80%9D%E7%9B%8A%23) `105.2K 🔥` `NEW`
1. [许昕说国家队大门永远给所有人打开](https://s.weibo.com/weibo?q=%23%E8%AE%B8%E6%98%95%E8%AF%B4%E5%9B%BD%E5%AE%B6%E9%98%9F%E5%A4%A7%E9%97%A8%E6%B0%B8%E8%BF%9C%E7%BB%99%E6%89%80%E6%9C%89%E4%BA%BA%E6%89%93%E5%BC%80%23) `94.8K 🔥` `NEW`
1. [黄杨钿甜新剧被鞭刑梦回小楚乔](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%9D%A8%E9%92%BF%E7%94%9C%E6%96%B0%E5%89%A7%E8%A2%AB%E9%9E%AD%E5%88%91%E6%A2%A6%E5%9B%9E%E5%B0%8F%E6%A5%9A%E4%B9%94%23) `93.4K 🔥` `NEW`
1. [接变成气血很足月经规律的女人](https://s.weibo.com/weibo?q=%23%E6%8E%A5%E5%8F%98%E6%88%90%E6%B0%94%E8%A1%80%E5%BE%88%E8%B6%B3%E6%9C%88%E7%BB%8F%E8%A7%84%E5%BE%8B%E7%9A%84%E5%A5%B3%E4%BA%BA%23) `91.2K 🔥` `NEW`
1. [撸了一只认错人的猫](https://s.weibo.com/weibo?q=%23%E6%92%B8%E4%BA%86%E4%B8%80%E5%8F%AA%E8%AE%A4%E9%94%99%E4%BA%BA%E7%9A%84%E7%8C%AB%23) `87.0K 🔥` `NEW`
1. [全球资产再度巨震](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%90%83%E8%B5%84%E4%BA%A7%E5%86%8D%E5%BA%A6%E5%B7%A8%E9%9C%87%23) `81.4K 🔥` `NEW`
1. [乘风2026舞台总监张铃](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E8%88%9E%E5%8F%B0%E6%80%BB%E7%9B%91%E5%BC%A0%E9%93%83%23) `79.5K 🔥` `NEW`
1. [多家银行4月1日起下调存款利率 (Many banks will lower deposit interest rates starting from April 1)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%AE%B6%E9%93%B6%E8%A1%8C4%E6%9C%881%E6%97%A5%E8%B5%B7%E4%B8%8B%E8%B0%83%E5%AD%98%E6%AC%BE%E5%88%A9%E7%8E%87%23) `76.2K 🔥` `NEW`
1. [赖伟明宝珠首个大男主](https://s.weibo.com/weibo?q=%23%E8%B5%96%E4%BC%9F%E6%98%8E%E5%AE%9D%E7%8F%A0%E9%A6%96%E4%B8%AA%E5%A4%A7%E7%94%B7%E4%B8%BB%23) `72.3K 🔥` `NEW`
1. [上班有三到](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%AD%E6%9C%89%E4%B8%89%E5%88%B0%23) `71.5K 🔥` `NEW`
1. [浙江用9000万元换来10多亿](https://s.weibo.com/weibo?q=%23%E6%B5%99%E6%B1%9F%E7%94%A89000%E4%B8%87%E5%85%83%E6%8D%A2%E6%9D%A510%E5%A4%9A%E4%BA%BF%23) `69.4K 🔥` `NEW`
1. [LPL守护星星行动](https://s.weibo.com/weibo?q=%23LPL%E5%AE%88%E6%8A%A4%E6%98%9F%E6%98%9F%E8%A1%8C%E5%8A%A8%23) `69.2K 🔥` `NEW`
1. [刘晓艳网课现场没有学生一个人聊嗨了](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E8%89%B3%E7%BD%91%E8%AF%BE%E7%8E%B0%E5%9C%BA%E6%B2%A1%E6%9C%89%E5%AD%A6%E7%94%9F%E4%B8%80%E4%B8%AA%E4%BA%BA%E8%81%8A%E5%97%A8%E4%BA%86%23) `606.4K 🔥` `+381%`
1. [银行回应老人存10万变7万](https://s.weibo.com/weibo?q=%23%E9%93%B6%E8%A1%8C%E5%9B%9E%E5%BA%94%E8%80%81%E4%BA%BA%E5%AD%9810%E4%B8%87%E5%8F%987%E4%B8%87%23) `224.1K 🔥` `+52%`
1. [优思益 (Yousiyi)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `1.1M 🔥`
1. [天宫画展再上新](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E5%AE%AB%E7%94%BB%E5%B1%95%E5%86%8D%E4%B8%8A%E6%96%B0%23) `650.9K 🔥`
1. [张雪](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%23) `418.8K 🔥`
1. [清明假期首选神州租车 (Car rental in China is the first choice during the Qingming Festival)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E9%A6%96%E9%80%89%E7%A5%9E%E5%B7%9E%E7%A7%9F%E8%BD%A6%23) `242.6K 🔥`
1. [乘风一口气官宣34位送考人](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E%E4%B8%80%E5%8F%A3%E6%B0%94%E5%AE%98%E5%AE%A334%E4%BD%8D%E9%80%81%E8%80%83%E4%BA%BA%23) `238.8K 🔥`
1. [胡彦斌连夜关闭了人脸支付 (Hu Yanbin shut down face payment overnight)](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%BD%A6%E6%96%8C%E8%BF%9E%E5%A4%9C%E5%85%B3%E9%97%AD%E4%BA%86%E4%BA%BA%E8%84%B8%E6%94%AF%E4%BB%98%23) `211.6K 🔥`
1. [董宇辉曾说产品上播10天前有人试吃](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AE%87%E8%BE%89%E6%9B%BE%E8%AF%B4%E4%BA%A7%E5%93%81%E4%B8%8A%E6%92%AD10%E5%A4%A9%E5%89%8D%E6%9C%89%E4%BA%BA%E8%AF%95%E5%90%83%23) `198.4K 🔥`
1. [乘风2026](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%23) `87.4K 🔥`
1. [优思益营销策划公司被立案调查](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E8%90%A5%E9%94%80%E7%AD%96%E5%88%92%E5%85%AC%E5%8F%B8%E8%A2%AB%E7%AB%8B%E6%A1%88%E8%B0%83%E6%9F%A5%23) `228.4K 🔥` `-27%`
1. [李若彤发布致歉声明](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E8%8B%A5%E5%BD%A4%E5%8F%91%E5%B8%83%E8%87%B4%E6%AD%89%E5%A3%B0%E6%98%8E%23) `205.0K 🔥` `-26%`
1. [特朗普话音刚落伊朗导弹袭向以色列](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%AF%9D%E9%9F%B3%E5%88%9A%E8%90%BD%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `197.1K 🔥` `-33%`
1. [日本终于露出獠牙](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%BB%88%E4%BA%8E%E9%9C%B2%E5%87%BA%E7%8D%A0%E7%89%99%23) `149.8K 🔥` `-81%`
1. [男孩捡50g金条咬了一口竟是真的](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%A9%E6%8D%A150g%E9%87%91%E6%9D%A1%E5%92%AC%E4%BA%86%E4%B8%80%E5%8F%A3%E7%AB%9F%E6%98%AF%E7%9C%9F%E7%9A%84%23) `145.2K 🔥` `-25%`
1. [杨紫 没人通知我啊 (Yang Zi, no one informed me)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%20%E6%B2%A1%E4%BA%BA%E9%80%9A%E7%9F%A5%E6%88%91%E5%95%8A%23) `144.9K 🔥` `-45%`
1. [主播陆续回应优思益售后 (Anchors responded to Yousiyi after-sales service one after another)](https://s.weibo.com/weibo?q=%23%E4%B8%BB%E6%92%AD%E9%99%86%E7%BB%AD%E5%9B%9E%E5%BA%94%E4%BC%98%E6%80%9D%E7%9B%8A%E5%94%AE%E5%90%8E%23) `128.3K 🔥` `-21%`
1. [怪不得上大学老了这么多 (No wonder I’ve aged so much since I went to college.)](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E4%B8%8A%E5%A4%A7%E5%AD%A6%E8%80%81%E4%BA%86%E8%BF%99%E4%B9%88%E5%A4%9A%23) `109.0K 🔥` `-64%`
1. [今麦郎手打擦边20年不能停产就完了](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E9%BA%A6%E9%83%8E%E6%89%8B%E6%89%93%E6%93%A6%E8%BE%B920%E5%B9%B4%E4%B8%8D%E8%83%BD%E5%81%9C%E4%BA%A7%E5%B0%B1%E5%AE%8C%E4%BA%86%23) `108.4K 🔥` `-24%`
1. [张柏芝晒二儿子打球正脸](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9F%8F%E8%8A%9D%E6%99%92%E4%BA%8C%E5%84%BF%E5%AD%90%E6%89%93%E7%90%83%E6%AD%A3%E8%84%B8%23) `98.6K 🔥` `-49%`
1. [说唱歌手JCole加盟CBA (Rapper JCole joins CBA)](https://s.weibo.com/weibo?q=%23%E8%AF%B4%E5%94%B1%E6%AD%8C%E6%89%8BJCole%E5%8A%A0%E7%9B%9FCBA%23) `76.3K 🔥` `-35%`
1. [尹锡悦看守所内吸金12亿韩元](https://s.weibo.com/weibo?q=%23%E5%B0%B9%E9%94%A1%E6%82%A6%E7%9C%8B%E5%AE%88%E6%89%80%E5%86%85%E5%90%B8%E9%87%9112%E4%BA%BF%E9%9F%A9%E5%85%83%23) `73.5K 🔥` `-31%`
1. [老爸收入不敌女儿卖拼豆直呼崩溃](https://s.weibo.com/weibo?q=%23%E8%80%81%E7%88%B8%E6%94%B6%E5%85%A5%E4%B8%8D%E6%95%8C%E5%A5%B3%E5%84%BF%E5%8D%96%E6%8B%BC%E8%B1%86%E7%9B%B4%E5%91%BC%E5%B4%A9%E6%BA%83%23) `70.2K 🔥` `-45%`
1. [正义女神](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E4%B9%89%E5%A5%B3%E7%A5%9E%23) `68.9K 🔥` `-46%`

Updated at 2026-04-02 14:50:17

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
