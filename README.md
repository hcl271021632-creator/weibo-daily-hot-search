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

1. [美宜佳被曝光后半小时无一人进店 (No one entered Meiyijia store for half an hour after it was exposed)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AE%9C%E4%BD%B3%E8%A2%AB%E6%9B%9D%E5%85%89%E5%90%8E%E5%8D%8A%E5%B0%8F%E6%97%B6%E6%97%A0%E4%B8%80%E4%BA%BA%E8%BF%9B%E5%BA%97%23) `1.1M 🔥` `NEW`
1. [永辉公开喊话山姆](https://s.weibo.com/weibo?q=%23%E6%B0%B8%E8%BE%89%E5%85%AC%E5%BC%80%E5%96%8A%E8%AF%9D%E5%B1%B1%E5%A7%86%23) `771.5K 🔥` `NEW`
1. [奋进十五五你会看到这样的中国](https://s.weibo.com/weibo?q=%23%E5%A5%8B%E8%BF%9B%E5%8D%81%E4%BA%94%E4%BA%94%E4%BD%A0%E4%BC%9A%E7%9C%8B%E5%88%B0%E8%BF%99%E6%A0%B7%E7%9A%84%E4%B8%AD%E5%9B%BD%23) `632.6K 🔥` `NEW`
1. [小米新SU7发布定档3月19日](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%B1%B3%E6%96%B0SU7%E5%8F%91%E5%B8%83%E5%AE%9A%E6%A1%A33%E6%9C%8819%E6%97%A5%23) `618.2K 🔥` `NEW`
1. [深圳公积金新规4月施行](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E5%85%AC%E7%A7%AF%E9%87%91%E6%96%B0%E8%A7%844%E6%9C%88%E6%96%BD%E8%A1%8C%23) `529.2K 🔥` `NEW`
1. [89岁老人过马路半路变红灯被撞身亡](https://s.weibo.com/weibo?q=%2389%E5%B2%81%E8%80%81%E4%BA%BA%E8%BF%87%E9%A9%AC%E8%B7%AF%E5%8D%8A%E8%B7%AF%E5%8F%98%E7%BA%A2%E7%81%AF%E8%A2%AB%E6%92%9E%E8%BA%AB%E4%BA%A1%23) `485.2K 🔥` `NEW`
1. [胖东来169元1克拉方糖戒指再上架](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5169%E5%85%831%E5%85%8B%E6%8B%89%E6%96%B9%E7%B3%96%E6%88%92%E6%8C%87%E5%86%8D%E4%B8%8A%E6%9E%B6%23) `217.1K 🔥` `NEW`
1. [极氪8X预售37.68万起](https://s.weibo.com/weibo?q=%23%E6%9E%81%E6%B0%AA8X%E9%A2%84%E5%94%AE37.68%E4%B8%87%E8%B5%B7%23) `192.1K 🔥` `NEW`
1. [Ella评论瞿颖](https://s.weibo.com/weibo?q=%23Ella%E8%AF%84%E8%AE%BA%E7%9E%BF%E9%A2%96%23) `191.8K 🔥` `NEW`
1. [入职未满1年怀孕请假被拒获赔10万](https://s.weibo.com/weibo?q=%23%E5%85%A5%E8%81%8C%E6%9C%AA%E6%BB%A11%E5%B9%B4%E6%80%80%E5%AD%95%E8%AF%B7%E5%81%87%E8%A2%AB%E6%8B%92%E8%8E%B7%E8%B5%9410%E4%B8%87%23) `191.2K 🔥` `NEW`
1. [蜀福香厂房标语质量决定幸福 (Slogan of Shufu Xiang Factory: Quality determines happiness)](https://s.weibo.com/weibo?q=%23%E8%9C%80%E7%A6%8F%E9%A6%99%E5%8E%82%E6%88%BF%E6%A0%87%E8%AF%AD%E8%B4%A8%E9%87%8F%E5%86%B3%E5%AE%9A%E5%B9%B8%E7%A6%8F%23) `190.1K 🔥` `NEW`
1. [极氪8X](https://s.weibo.com/weibo?q=%23%E6%9E%81%E6%B0%AA8X%23) `154.3K 🔥` `NEW`
1. [极氪8X预售38分钟破万](https://s.weibo.com/weibo?q=%23%E6%9E%81%E6%B0%AA8X%E9%A2%84%E5%94%AE38%E5%88%86%E9%92%9F%E7%A0%B4%E4%B8%87%23) `119.4K 🔥` `NEW`
1. [钎城官宣老乡杯](https://s.weibo.com/weibo?q=%23%E9%92%8E%E5%9F%8E%E5%AE%98%E5%AE%A3%E8%80%81%E4%B9%A1%E6%9D%AF%23) `117.1K 🔥` `NEW`
1. [T1怎么输的](https://s.weibo.com/weibo?q=%23T1%E6%80%8E%E4%B9%88%E8%BE%93%E7%9A%84%23) `111.3K 🔥` `NEW`
1. [鹿哈毛肚事件获商家退款消费者发声](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E5%93%88%E6%AF%9B%E8%82%9A%E4%BA%8B%E4%BB%B6%E8%8E%B7%E5%95%86%E5%AE%B6%E9%80%80%E6%AC%BE%E6%B6%88%E8%B4%B9%E8%80%85%E5%8F%91%E5%A3%B0%23) `102.5K 🔥` `NEW`
1. [188套餐拍写真结果花了3万](https://s.weibo.com/weibo?q=%23188%E5%A5%97%E9%A4%90%E6%8B%8D%E5%86%99%E7%9C%9F%E7%BB%93%E6%9E%9C%E8%8A%B1%E4%BA%863%E4%B8%87%23) `92.6K 🔥` `NEW`
1. [马斯克5万美金小屋简陋似仓库](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%96%AF%E5%85%8B5%E4%B8%87%E7%BE%8E%E9%87%91%E5%B0%8F%E5%B1%8B%E7%AE%80%E9%99%8B%E4%BC%BC%E4%BB%93%E5%BA%93%23) `89.3K 🔥` `NEW`
1. [男子休15天陪产假遭开除获赔2万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E4%BC%9115%E5%A4%A9%E9%99%AA%E4%BA%A7%E5%81%87%E9%81%AD%E5%BC%80%E9%99%A4%E8%8E%B7%E8%B5%942%E4%B8%87%23) `88.1K 🔥` `NEW`
1. [她的盛焰谁看谁窒息](https://s.weibo.com/weibo?q=%23%E5%A5%B9%E7%9A%84%E7%9B%9B%E7%84%B0%E8%B0%81%E7%9C%8B%E8%B0%81%E7%AA%92%E6%81%AF%23) `87.3K 🔥` `NEW`
1. [任豪跳第三个吻痕 (Ren Hao dances the third hickey)](https://s.weibo.com/weibo?q=%23%E4%BB%BB%E8%B1%AA%E8%B7%B3%E7%AC%AC%E4%B8%89%E4%B8%AA%E5%90%BB%E7%97%95%23) `87.1K 🔥` `NEW`
1. [我国将适度超前推进新基建](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E5%B0%86%E9%80%82%E5%BA%A6%E8%B6%85%E5%89%8D%E6%8E%A8%E8%BF%9B%E6%96%B0%E5%9F%BA%E5%BB%BA%23) `83.3K 🔥` `NEW`
1. [外交部回应中国特使赴阿巴穿梭斡旋](https://s.weibo.com/weibo?q=%23%E5%A4%96%E4%BA%A4%E9%83%A8%E5%9B%9E%E5%BA%94%E4%B8%AD%E5%9B%BD%E7%89%B9%E4%BD%BF%E8%B5%B4%E9%98%BF%E5%B7%B4%E7%A9%BF%E6%A2%AD%E6%96%A1%E6%97%8B%23) `81.7K 🔥` `NEW`
1. [杨紫在秀场交到了新朋友](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E5%9C%A8%E7%A7%80%E5%9C%BA%E4%BA%A4%E5%88%B0%E4%BA%86%E6%96%B0%E6%9C%8B%E5%8F%8B%23) `70.1K 🔥` `NEW`
1. [伊朗成功执行第55轮打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%88%90%E5%8A%9F%E6%89%A7%E8%A1%8C%E7%AC%AC55%E8%BD%AE%E6%89%93%E5%87%BB%23) `232.4K 🔥` `+38%`
1. [2岁娃被忘车内反锁1小时](https://s.weibo.com/weibo?q=%232%E5%B2%81%E5%A8%83%E8%A2%AB%E5%BF%98%E8%BD%A6%E5%86%85%E5%8F%8D%E9%94%811%E5%B0%8F%E6%97%B6%23) `132.2K 🔥` `+62%`
1. [AirPodsMax2发布](https://s.weibo.com/weibo?q=%23AirPodsMax2%E5%8F%91%E5%B8%83%23) `105.0K 🔥` `+35%`
1. [周冬雨 刘昊然 (Zhou Dongyu Liu Haoran)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E5%86%AC%E9%9B%A8%20%E5%88%98%E6%98%8A%E7%84%B6%23) `189.6K 🔥`
1. [孔雪儿伟大的爱豆时期](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E4%BC%9F%E5%A4%A7%E7%9A%84%E7%88%B1%E8%B1%86%E6%97%B6%E6%9C%9F%23) `165.8K 🔥`
1. [315塌房全总结](https://s.weibo.com/weibo?q=%23315%E5%A1%8C%E6%88%BF%E5%85%A8%E6%80%BB%E7%BB%93%23) `147.5K 🔥`
1. [孙燕姿胖了](https://s.weibo.com/weibo?q=%23%E5%AD%99%E7%87%95%E5%A7%BF%E8%83%96%E4%BA%86%23) `136.9K 🔥`
1. [张凌赫田曦薇浴池戏 (Zhang Linghe Tian Xiwei bath scene)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E6%B5%B4%E6%B1%A0%E6%88%8F%23) `114.7K 🔥`
1. [王一栩 虞书欣演过最好的都是我给的](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E6%A0%A9%20%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%BC%94%E8%BF%87%E6%9C%80%E5%A5%BD%E7%9A%84%E9%83%BD%E6%98%AF%E6%88%91%E7%BB%99%E7%9A%84%23) `73.0K 🔥`
1. [事业单位招人岗位在海拔3614米山顶](https://s.weibo.com/weibo?q=%23%E4%BA%8B%E4%B8%9A%E5%8D%95%E4%BD%8D%E6%8B%9B%E4%BA%BA%E5%B2%97%E4%BD%8D%E5%9C%A8%E6%B5%B7%E6%8B%943614%E7%B1%B3%E5%B1%B1%E9%A1%B6%23) `491.9K 🔥` `-39%`
1. [爱吃薯片的人天塌了](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%90%83%E8%96%AF%E7%89%87%E7%9A%84%E4%BA%BA%E5%A4%A9%E5%A1%8C%E4%BA%86%23) `485.0K 🔥` `-24%`
1. [手机电脑迎来涨价潮](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E7%94%B5%E8%84%91%E8%BF%8E%E6%9D%A5%E6%B6%A8%E4%BB%B7%E6%BD%AE%23) `226.4K 🔥` `-46%`
1. [一男女在公众场合实施不雅行为被抓](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%94%B7%E5%A5%B3%E5%9C%A8%E5%85%AC%E4%BC%97%E5%9C%BA%E5%90%88%E5%AE%9E%E6%96%BD%E4%B8%8D%E9%9B%85%E8%A1%8C%E4%B8%BA%E8%A2%AB%E6%8A%93%23) `215.8K 🔥` `-66%`
1. [因为瞿颖盒马的菠菜都标上英文了](https://s.weibo.com/weibo?q=%23%E5%9B%A0%E4%B8%BA%E7%9E%BF%E9%A2%96%E7%9B%92%E9%A9%AC%E7%9A%84%E8%8F%A0%E8%8F%9C%E9%83%BD%E6%A0%87%E4%B8%8A%E8%8B%B1%E6%96%87%E4%BA%86%23) `204.9K 🔥` `-39%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `197.5K 🔥` `-29%`
1. [42岁女子从不抽烟确诊肺癌晚期](https://s.weibo.com/weibo?q=%2342%E5%B2%81%E5%A5%B3%E5%AD%90%E4%BB%8E%E4%B8%8D%E6%8A%BD%E7%83%9F%E7%A1%AE%E8%AF%8A%E8%82%BA%E7%99%8C%E6%99%9A%E6%9C%9F%23) `193.0K 🔥` `-69%`
1. [樊振东回应转会](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E5%9B%9E%E5%BA%94%E8%BD%AC%E4%BC%9A%23) `193.0K 🔥` `-64%`
1. [张凌赫 导演你管管她 (Director Zhang Linghe, please take care of her.)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E5%AF%BC%E6%BC%94%E4%BD%A0%E7%AE%A1%E7%AE%A1%E5%A5%B9%23) `190.5K 🔥` `-70%`
1. [18岁女孩腹中肿块里还有24颗牙齿](https://s.weibo.com/weibo?q=%2318%E5%B2%81%E5%A5%B3%E5%AD%A9%E8%85%B9%E4%B8%AD%E8%82%BF%E5%9D%97%E9%87%8C%E8%BF%98%E6%9C%8924%E9%A2%97%E7%89%99%E9%BD%BF%23) `155.7K 🔥` `-50%`
1. [发现虾腿有肉以后](https://s.weibo.com/weibo?q=%23%E5%8F%91%E7%8E%B0%E8%99%BE%E8%85%BF%E6%9C%89%E8%82%89%E4%BB%A5%E5%90%8E%23) `132.7K 🔥` `-30%`
1. [鹿晗 关晓彤](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `123.2K 🔥` `-28%`
1. [女子借5万还不上履约做对方女友 (A woman borrowed 50,000 yuan but still failed to fulfill the contract to become his girlfriend)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%80%9F5%E4%B8%87%E8%BF%98%E4%B8%8D%E4%B8%8A%E5%B1%A5%E7%BA%A6%E5%81%9A%E5%AF%B9%E6%96%B9%E5%A5%B3%E5%8F%8B%23) `113.5K 🔥` `-38%`
1. [刚起床的素颜张柏芝](https://s.weibo.com/weibo?q=%23%E5%88%9A%E8%B5%B7%E5%BA%8A%E7%9A%84%E7%B4%A0%E9%A2%9C%E5%BC%A0%E6%9F%8F%E8%8A%9D%23) `98.1K 🔥` `-68%`
1. [恋与深空 偷跑](https://s.weibo.com/weibo?q=%23%E6%81%8B%E4%B8%8E%E6%B7%B1%E7%A9%BA%20%E5%81%B7%E8%B7%91%23) `85.6K 🔥` `-83%`
1. [范丞丞开始减肥第一天 (Fan Chengcheng’s first day of losing weight)](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E5%BC%80%E5%A7%8B%E5%87%8F%E8%82%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%23) `84.7K 🔥` `-23%`
1. [伊朗称逮捕500名间谍 (Iran says it has arrested 500 spies)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E9%80%AE%E6%8D%95500%E5%90%8D%E9%97%B4%E8%B0%8D%23) `76.5K 🔥` `-29%`
1. [教体局通报女孩遭殴打不予立案原因](https://s.weibo.com/weibo?q=%23%E6%95%99%E4%BD%93%E5%B1%80%E9%80%9A%E6%8A%A5%E5%A5%B3%E5%AD%A9%E9%81%AD%E6%AE%B4%E6%89%93%E4%B8%8D%E4%BA%88%E7%AB%8B%E6%A1%88%E5%8E%9F%E5%9B%A0%23) `67.3K 🔥` `-40%`

Updated at 2026-03-16 22:51:57

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
