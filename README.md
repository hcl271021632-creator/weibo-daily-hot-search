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

1. [歌手2026拟邀 (Singer 2026 to be invited)](https://s.weibo.com/weibo?q=%23%E6%AD%8C%E6%89%8B2026%E6%8B%9F%E9%82%80%23) `1.1M 🔥` `NEW`
1. [男子因虚荣心冒充消防员多店检查](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%9B%A0%E8%99%9A%E8%8D%A3%E5%BF%83%E5%86%92%E5%85%85%E6%B6%88%E9%98%B2%E5%91%98%E5%A4%9A%E5%BA%97%E6%A3%80%E6%9F%A5%23) `845.1K 🔥` `NEW`
1. [周也演技](https://s.weibo.com/weibo?q=%23%E5%91%A8%E4%B9%9F%E6%BC%94%E6%8A%80%23) `377.2K 🔥` `NEW`
1. [妻子肺癌晚期求丈夫送至安宁病房](https://s.weibo.com/weibo?q=%23%E5%A6%BB%E5%AD%90%E8%82%BA%E7%99%8C%E6%99%9A%E6%9C%9F%E6%B1%82%E4%B8%88%E5%A4%AB%E9%80%81%E8%87%B3%E5%AE%89%E5%AE%81%E7%97%85%E6%88%BF%23) `312.3K 🔥` `NEW`
1. [美将只剩一艘航母用于对伊朗袭击](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%B0%86%E5%8F%AA%E5%89%A9%E4%B8%80%E8%89%98%E8%88%AA%E6%AF%8D%E7%94%A8%E4%BA%8E%E5%AF%B9%E4%BC%8A%E6%9C%97%E8%A2%AD%E5%87%BB%23) `289.4K 🔥` `NEW`
1. [樊长玉没让谢征牵手](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E6%B2%A1%E8%AE%A9%E8%B0%A2%E5%BE%81%E7%89%B5%E6%89%8B%23) `287.0K 🔥` `NEW`
1. [4S店称吃饭超260次客户已报警](https://s.weibo.com/weibo?q=%234S%E5%BA%97%E7%A7%B0%E5%90%83%E9%A5%AD%E8%B6%85260%E6%AC%A1%E5%AE%A2%E6%88%B7%E5%B7%B2%E6%8A%A5%E8%AD%A6%23) `274.8K 🔥` `NEW`
1. [银行金条1克难求](https://s.weibo.com/weibo?q=%23%E9%93%B6%E8%A1%8C%E9%87%91%E6%9D%A11%E5%85%8B%E9%9A%BE%E6%B1%82%23) `202.6K 🔥` `NEW`
1. [THEBOYZ解约](https://s.weibo.com/weibo?q=%23THEBOYZ%E8%A7%A3%E7%BA%A6%23) `201.4K 🔥` `NEW`
1. [AI演员 假人感](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%20%E5%81%87%E4%BA%BA%E6%84%9F%23) `197.1K 🔥` `NEW`
1. [沙县鸡腿饭中国宝宝的减脂餐 (Shaxian Chicken Leg Rice, a fat-reducing meal for Chinese babies)](https://s.weibo.com/weibo?q=%23%E6%B2%99%E5%8E%BF%E9%B8%A1%E8%85%BF%E9%A5%AD%E4%B8%AD%E5%9B%BD%E5%AE%9D%E5%AE%9D%E7%9A%84%E5%87%8F%E8%84%82%E9%A4%90%23) `192.1K 🔥` `NEW`
1. [小米汽车 舒淇](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%B1%BD%E8%BD%A6%20%E8%88%92%E6%B7%87%23) `189.8K 🔥` `NEW`
1. [春分拍到的治愈瞬间](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%88%86%E6%8B%8D%E5%88%B0%E7%9A%84%E6%B2%BB%E6%84%88%E7%9E%AC%E9%97%B4%23) `185.9K 🔥` `NEW`
1. [张凌赫杂志](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%9D%82%E5%BF%97%23) `185.9K 🔥` `NEW`
1. [印度一家人将老人装进麻袋寄快递](https://s.weibo.com/weibo?q=%23%E5%8D%B0%E5%BA%A6%E4%B8%80%E5%AE%B6%E4%BA%BA%E5%B0%86%E8%80%81%E4%BA%BA%E8%A3%85%E8%BF%9B%E9%BA%BB%E8%A2%8B%E5%AF%84%E5%BF%AB%E9%80%92%23) `185.5K 🔥` `NEW`
1. [爱心面馆获众人接力](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%BF%83%E9%9D%A2%E9%A6%86%E8%8E%B7%E4%BC%97%E4%BA%BA%E6%8E%A5%E5%8A%9B%23) `183.2K 🔥` `NEW`
1. [胖东来参访费2万不满意可全额退款](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E5%8F%82%E8%AE%BF%E8%B4%B92%E4%B8%87%E4%B8%8D%E6%BB%A1%E6%84%8F%E5%8F%AF%E5%85%A8%E9%A2%9D%E9%80%80%E6%AC%BE%23) `182.9K 🔥` `NEW`
1. [携密件回家遭亲属偷拍发往境外](https://s.weibo.com/weibo?q=%23%E6%90%BA%E5%AF%86%E4%BB%B6%E5%9B%9E%E5%AE%B6%E9%81%AD%E4%BA%B2%E5%B1%9E%E5%81%B7%E6%8B%8D%E5%8F%91%E5%BE%80%E5%A2%83%E5%A4%96%23) `182.7K 🔥` `NEW`
1. [小酒窝不想看妈妈在剧里被打](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E9%85%92%E7%AA%9D%E4%B8%8D%E6%83%B3%E7%9C%8B%E5%A6%88%E5%A6%88%E5%9C%A8%E5%89%A7%E9%87%8C%E8%A2%AB%E6%89%93%23) `182.7K 🔥` `NEW`
1. [伊朗发起报复行动](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E6%8A%A5%E5%A4%8D%E8%A1%8C%E5%8A%A8%23) `165.9K 🔥` `NEW`
1. [如果一个人长期不工作 (If a person does not work for a long time)](https://s.weibo.com/weibo?q=%23%E5%A6%82%E6%9E%9C%E4%B8%80%E4%B8%AA%E4%BA%BA%E9%95%BF%E6%9C%9F%E4%B8%8D%E5%B7%A5%E4%BD%9C%23) `139.1K 🔥` `NEW`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `138.4K 🔥` `NEW`
1. [71岁老人花200万买基金亏了85万](https://s.weibo.com/weibo?q=%2371%E5%B2%81%E8%80%81%E4%BA%BA%E8%8A%B1200%E4%B8%87%E4%B9%B0%E5%9F%BA%E9%87%91%E4%BA%8F%E4%BA%8685%E4%B8%87%23) `126.5K 🔥` `NEW`
1. [曝带货女明星学佛人设是炒作](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%B8%A6%E8%B4%A7%E5%A5%B3%E6%98%8E%E6%98%9F%E5%AD%A6%E4%BD%9B%E4%BA%BA%E8%AE%BE%E6%98%AF%E7%82%92%E4%BD%9C%23) `122.9K 🔥` `NEW`
1. [戴军曝潜水时曾被拔呼吸器威胁](https://s.weibo.com/weibo?q=%23%E6%88%B4%E5%86%9B%E6%9B%9D%E6%BD%9C%E6%B0%B4%E6%97%B6%E6%9B%BE%E8%A2%AB%E6%8B%94%E5%91%BC%E5%90%B8%E5%99%A8%E5%A8%81%E8%83%81%23) `107.9K 🔥` `NEW`
1. [伊朗大规模打击与美国相关石油设施](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%A7%E8%A7%84%E6%A8%A1%E6%89%93%E5%87%BB%E4%B8%8E%E7%BE%8E%E5%9B%BD%E7%9B%B8%E5%85%B3%E7%9F%B3%E6%B2%B9%E8%AE%BE%E6%96%BD%23) `106.9K 🔥` `NEW`
1. [现货黄金白银翻红](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E8%B4%A7%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E7%BF%BB%E7%BA%A2%23) `106.8K 🔥` `NEW`
1. [美国以色列有分歧了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E4%BB%A5%E8%89%B2%E5%88%97%E6%9C%89%E5%88%86%E6%AD%A7%E4%BA%86%23) `95.8K 🔥` `NEW`
1. [谢征的毕业论文](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E7%9A%84%E6%AF%95%E4%B8%9A%E8%AE%BA%E6%96%87%23) `93.8K 🔥` `NEW`
1. [孙颖莎一回头何卓佳也在拍](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E4%B8%80%E5%9B%9E%E5%A4%B4%E4%BD%95%E5%8D%93%E4%BD%B3%E4%B9%9F%E5%9C%A8%E6%8B%8D%23) `90.5K 🔥` `NEW`
1. [马斯克点赞深圳小孩哥 (Musk likes Shenzhen kid brother)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%96%AF%E5%85%8B%E7%82%B9%E8%B5%9E%E6%B7%B1%E5%9C%B3%E5%B0%8F%E5%AD%A9%E5%93%A5%23) `89.0K 🔥` `NEW`
1. [徐若晗明媚](https://s.weibo.com/weibo?q=%23%E5%BE%90%E8%8B%A5%E6%99%97%E6%98%8E%E5%AA%9A%23) `85.5K 🔥` `NEW`
1. [女子体检医院出具三份不同CT报告](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%BD%93%E6%A3%80%E5%8C%BB%E9%99%A2%E5%87%BA%E5%85%B7%E4%B8%89%E4%BB%BD%E4%B8%8D%E5%90%8CCT%E6%8A%A5%E5%91%8A%23) `85.1K 🔥` `NEW`
1. [跑腿师傅爬着进门怕弄脏地板](https://s.weibo.com/weibo?q=%23%E8%B7%91%E8%85%BF%E5%B8%88%E5%82%85%E7%88%AC%E7%9D%80%E8%BF%9B%E9%97%A8%E6%80%95%E5%BC%84%E8%84%8F%E5%9C%B0%E6%9D%BF%23) `83.5K 🔥` `NEW`
1. [小米大模型](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E5%A4%A7%E6%A8%A1%E5%9E%8B%23) `80.7K 🔥` `NEW`
1. [高市早苗开启任后首次访美](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%BC%80%E5%90%AF%E4%BB%BB%E5%90%8E%E9%A6%96%E6%AC%A1%E8%AE%BF%E7%BE%8E%23) `79.4K 🔥` `NEW`
1. [多家银行金条断货](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%AE%B6%E9%93%B6%E8%A1%8C%E9%87%91%E6%9D%A1%E6%96%AD%E8%B4%A7%23) `77.0K 🔥` `NEW`
1. [湖人vs火箭](https://s.weibo.com/weibo?q=%23%E6%B9%96%E4%BA%BAvs%E7%81%AB%E7%AE%AD%23) `75.2K 🔥` `NEW`
1. [2026年中国游泳公开赛](https://s.weibo.com/weibo?q=%232026%E5%B9%B4%E4%B8%AD%E5%9B%BD%E6%B8%B8%E6%B3%B3%E5%85%AC%E5%BC%80%E8%B5%9B%23) `74.5K 🔥` `NEW`
1. [AI演员开通账号](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%E5%BC%80%E9%80%9A%E8%B4%A6%E5%8F%B7%23) `72.4K 🔥` `NEW`
1. [油价上涨对哪种材质衣服影响最大 (Which material for clothing will be most affected by rising oil prices?)](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E4%B8%8A%E6%B6%A8%E5%AF%B9%E5%93%AA%E7%A7%8D%E6%9D%90%E8%B4%A8%E8%A1%A3%E6%9C%8D%E5%BD%B1%E5%93%8D%E6%9C%80%E5%A4%A7%23) `70.7K 🔥` `NEW`
1. [新一批重大外资项目要来了 (A new batch of major foreign investment projects are coming)](https://s.weibo.com/weibo?q=%23%E6%96%B0%E4%B8%80%E6%89%B9%E9%87%8D%E5%A4%A7%E5%A4%96%E8%B5%84%E9%A1%B9%E7%9B%AE%E8%A6%81%E6%9D%A5%E4%BA%86%23) `644.0K 🔥`
1. [和热巴共享甄稀美妙时刻 (Share precious and wonderful moments with Reba)](https://s.weibo.com/weibo?q=%23%E5%92%8C%E7%83%AD%E5%B7%B4%E5%85%B1%E4%BA%AB%E7%94%84%E7%A8%80%E7%BE%8E%E5%A6%99%E6%97%B6%E5%88%BB%23) `638.6K 🔥`
1. [赵丽颖被主持人骗到的反应 (Zhao Liying's reaction to being deceived by the host)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E8%A2%AB%E4%B8%BB%E6%8C%81%E4%BA%BA%E9%AA%97%E5%88%B0%E7%9A%84%E5%8F%8D%E5%BA%94%23) `106.5K 🔥`
1. [当老公得知宝宝鞋子的价格 (When the husband learned the price of the baby’s shoes)](https://s.weibo.com/weibo?q=%23%E5%BD%93%E8%80%81%E5%85%AC%E5%BE%97%E7%9F%A5%E5%AE%9D%E5%AE%9D%E9%9E%8B%E5%AD%90%E7%9A%84%E4%BB%B7%E6%A0%BC%23) `100.5K 🔥`
1. [胖东来小方糖戒指重新上架3天售罄](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E5%B0%8F%E6%96%B9%E7%B3%96%E6%88%92%E6%8C%87%E9%87%8D%E6%96%B0%E4%B8%8A%E6%9E%B63%E5%A4%A9%E5%94%AE%E7%BD%84%23) `208.6K 🔥` `-80%`
1. [刘冲和迪丽热巴聚餐](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%86%B2%E5%92%8C%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E8%81%9A%E9%A4%90%23) `164.4K 🔥` `-35%`
1. [男子遭路虎1分钟恶意别停8次后追尾 (Man was rear-ended by Land Rover after it maliciously stopped 8 times in 1 minute)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%81%AD%E8%B7%AF%E8%99%8E1%E5%88%86%E9%92%9F%E6%81%B6%E6%84%8F%E5%88%AB%E5%81%9C8%E6%AC%A1%E5%90%8E%E8%BF%BD%E5%B0%BE%23) `107.7K 🔥` `-58%`
1. [男子输液头孢7年第一次过敏休克 (Man suffered from anaphylactic shock for the first time in 7 years after receiving cephalosporin infusion)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%BE%93%E6%B6%B2%E5%A4%B4%E5%AD%A27%E5%B9%B4%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%BF%87%E6%95%8F%E4%BC%91%E5%85%8B%23) `83.0K 🔥` `-45%`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `79.9K 🔥` `-56%`
1. [张予曦毕雯珺 河清海晏](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BA%88%E6%9B%A6%E6%AF%95%E9%9B%AF%E7%8F%BA%20%E6%B2%B3%E6%B8%85%E6%B5%B7%E6%99%8F%23) `76.5K 🔥` `-70%`

Updated at 2026-03-19 11:15:16

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
