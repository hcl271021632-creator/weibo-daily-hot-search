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

1. [霍尔木兹封锁日本最先扛不住了 (Japan was the first to be unable to handle the Hormuz blockade.)](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E5%B0%81%E9%94%81%E6%97%A5%E6%9C%AC%E6%9C%80%E5%85%88%E6%89%9B%E4%B8%8D%E4%BD%8F%E4%BA%86%23) `162.6K 🔥` `NEW`
1. [富二代为情人落户雇人假结婚](https://s.weibo.com/weibo?q=%23%E5%AF%8C%E4%BA%8C%E4%BB%A3%E4%B8%BA%E6%83%85%E4%BA%BA%E8%90%BD%E6%88%B7%E9%9B%87%E4%BA%BA%E5%81%87%E7%BB%93%E5%A9%9A%23) `158.9K 🔥` `NEW`
1. [中国女足1比0中国台北](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B31%E6%AF%940%E4%B8%AD%E5%9B%BD%E5%8F%B0%E5%8C%97%23) `113.0K 🔥` `NEW`
1. [如何把一家人情绪价值都拉满](https://s.weibo.com/weibo?q=%23%E5%A6%82%E4%BD%95%E6%8A%8A%E4%B8%80%E5%AE%B6%E4%BA%BA%E6%83%85%E7%BB%AA%E4%BB%B7%E5%80%BC%E9%83%BD%E6%8B%89%E6%BB%A1%23) `91.2K 🔥` `NEW`
1. [哪个天才发明的减肥群](https://s.weibo.com/weibo?q=%23%E5%93%AA%E4%B8%AA%E5%A4%A9%E6%89%8D%E5%8F%91%E6%98%8E%E7%9A%84%E5%87%8F%E8%82%A5%E7%BE%A4%23) `75.4K 🔥` `NEW`
1. [大张伟在音乐剧被人喊闭嘴](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%BC%A0%E4%BC%9F%E5%9C%A8%E9%9F%B3%E4%B9%90%E5%89%A7%E8%A2%AB%E4%BA%BA%E5%96%8A%E9%97%AD%E5%98%B4%23) `75.2K 🔥` `NEW`
1. [两会结束国务院立刻行动](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%E7%BB%93%E6%9D%9F%E5%9B%BD%E5%8A%A1%E9%99%A2%E7%AB%8B%E5%88%BB%E8%A1%8C%E5%8A%A8%23) `67.8K 🔥` `NEW`
1. [鹿晗LP专辑水敏纸封面好浪漫](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97LP%E4%B8%93%E8%BE%91%E6%B0%B4%E6%95%8F%E7%BA%B8%E5%B0%81%E9%9D%A2%E5%A5%BD%E6%B5%AA%E6%BC%AB%23) `65.5K 🔥` `NEW`
1. [你的磁场很好天生就是富婆命](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E7%9A%84%E7%A3%81%E5%9C%BA%E5%BE%88%E5%A5%BD%E5%A4%A9%E7%94%9F%E5%B0%B1%E6%98%AF%E5%AF%8C%E5%A9%86%E5%91%BD%23) `64.0K 🔥` `NEW`
1. [鞠婧祎杂志开售](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E6%9D%82%E5%BF%97%E5%BC%80%E5%94%AE%23) `62.6K 🔥` `NEW`
1. [王鹤棣新歌歌词 (Wang Hedi's new song lyrics)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%96%B0%E6%AD%8C%E6%AD%8C%E8%AF%8D%23) `366.5K 🔥` `+22%`
1. [云南花香蓝莓 (Yunnan floral blueberry)](https://s.weibo.com/weibo?q=%23%E4%BA%91%E5%8D%97%E8%8A%B1%E9%A6%99%E8%93%9D%E8%8E%93%23) `326.1K 🔥` `+183%`
1. [美国凭啥从委内瑞拉搬走1亿美元黄金](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%87%AD%E5%95%A5%E4%BB%8E%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E6%90%AC%E8%B5%B01%E4%BA%BF%E7%BE%8E%E5%85%83%E9%BB%84%E9%87%91%23) `214.9K 🔥` `+38%`
1. [马思纯发文](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%80%9D%E7%BA%AF%E5%8F%91%E6%96%87%23) `161.5K 🔥` `+52%`
1. [女足](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E8%B6%B3%23) `156.2K 🔥` `+26%`
1. [关晓彤程潇F1观赛造型](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E7%A8%8B%E6%BD%87F1%E8%A7%82%E8%B5%9B%E9%80%A0%E5%9E%8B%23) `112.8K 🔥` `+49%`
1. [315调查眼镜到底有多暴利 (315 investigates how profitable glasses are)](https://s.weibo.com/weibo?q=%23315%E8%B0%83%E6%9F%A5%E7%9C%BC%E9%95%9C%E5%88%B0%E5%BA%95%E6%9C%89%E5%A4%9A%E6%9A%B4%E5%88%A9%23) `1.1M 🔥`
1. [孙颖莎2比4蒯曼](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E2%E6%AF%944%E8%92%AF%E6%9B%BC%23) `812.4K 🔥`
1. [十五五规划纲要全文](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E7%BA%B2%E8%A6%81%E5%85%A8%E6%96%87%23) `614.8K 🔥`
1. [国家摄影队独有的两会时间](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%AE%B6%E6%91%84%E5%BD%B1%E9%98%9F%E7%8B%AC%E6%9C%89%E7%9A%84%E4%B8%A4%E4%BC%9A%E6%97%B6%E9%97%B4%23) `345.5K 🔥`
1. [赵丽颖已经三提白玉兰了](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E5%B7%B2%E7%BB%8F%E4%B8%89%E6%8F%90%E7%99%BD%E7%8E%89%E5%85%B0%E4%BA%86%23) `163.5K 🔥`
1. [上海F1偶遇关晓彤](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7F1%E5%81%B6%E9%81%87%E5%85%B3%E6%99%93%E5%BD%A4%23) `157.9K 🔥`
1. [王一博给品牌发title (Wang Yibo sends a title to the brand)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E7%BB%99%E5%93%81%E7%89%8C%E5%8F%91title%23) `143.9K 🔥`
1. [中国女足vs中国台北女足](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B3vs%E4%B8%AD%E5%9B%BD%E5%8F%B0%E5%8C%97%E5%A5%B3%E8%B6%B3%23) `139.8K 🔥`
1. [25岁硕士曝光剧本直播间被死亡威胁](https://s.weibo.com/weibo?q=%2325%E5%B2%81%E7%A1%95%E5%A3%AB%E6%9B%9D%E5%85%89%E5%89%A7%E6%9C%AC%E7%9B%B4%E6%92%AD%E9%97%B4%E8%A2%AB%E6%AD%BB%E4%BA%A1%E5%A8%81%E8%83%81%23) `113.6K 🔥`
1. [清明节放假安排来了 (Tomb Sweeping Day holiday arrangements are here)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E8%8A%82%E6%94%BE%E5%81%87%E5%AE%89%E6%8E%92%E6%9D%A5%E4%BA%86%23) `111.6K 🔥`
1. [逛华为展看鸿蒙车](https://s.weibo.com/weibo?q=%23%E9%80%9B%E5%8D%8E%E4%B8%BA%E5%B1%95%E7%9C%8B%E9%B8%BF%E8%92%99%E8%BD%A6%23) `105.1K 🔥`
1. [孔雪儿 只想演强制爱](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%20%E5%8F%AA%E6%83%B3%E6%BC%94%E5%BC%BA%E5%88%B6%E7%88%B1%23) `96.6K 🔥`
1. [第31届白玉兰奖 (The 31st Magnolia Award)](https://s.weibo.com/weibo?q=%23%E7%AC%AC31%E5%B1%8A%E7%99%BD%E7%8E%89%E5%85%B0%E5%A5%96%23) `91.8K 🔥`
1. [外卖到了白鹿就这样跑步迎接](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%8D%96%E5%88%B0%E4%BA%86%E7%99%BD%E9%B9%BF%E5%B0%B1%E8%BF%99%E6%A0%B7%E8%B7%91%E6%AD%A5%E8%BF%8E%E6%8E%A5%23) `90.2K 🔥`
1. [省考](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%23) `77.5K 🔥`
1. [唐嫣刺绣吊带裙](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%AB%A3%E5%88%BA%E7%BB%A3%E5%90%8A%E5%B8%A6%E8%A3%99%23) `75.3K 🔥`
1. [15岁男孩智齿长到眼窝里妈妈发声](https://s.weibo.com/weibo?q=%2315%E5%B2%81%E7%94%B7%E5%AD%A9%E6%99%BA%E9%BD%BF%E9%95%BF%E5%88%B0%E7%9C%BC%E7%AA%9D%E9%87%8C%E5%A6%88%E5%A6%88%E5%8F%91%E5%A3%B0%23) `75.1K 🔥`
1. [原神](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E7%A5%9E%23) `71.8K 🔥`
1. [杨幂赵丽颖 白玉兰 (Yang Mi, Zhao Liying, Magnolia)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%B5%B5%E4%B8%BD%E9%A2%96%20%E7%99%BD%E7%8E%89%E5%85%B0%23) `71.3K 🔥`
1. [谢征收到了和离书 (Xie Zheng received the He Li Shu)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%94%B6%E5%88%B0%E4%BA%86%E5%92%8C%E7%A6%BB%E4%B9%A6%23) `220.4K 🔥` `-25%`
1. [蒯曼回应4比2孙颖莎](https://s.weibo.com/weibo?q=%23%E8%92%AF%E6%9B%BC%E5%9B%9E%E5%BA%944%E6%AF%942%E5%AD%99%E9%A2%96%E8%8E%8E%23) `193.3K 🔥` `-35%`
1. [爸爸给被丢弃厕所女儿准备金手镯](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E7%BB%99%E8%A2%AB%E4%B8%A2%E5%BC%83%E5%8E%95%E6%89%80%E5%A5%B3%E5%84%BF%E5%87%86%E5%A4%87%E9%87%91%E6%89%8B%E9%95%AF%23) `162.7K 🔥` `-39%`
1. [田曦薇张凌赫经纪人依旧纯恨中 (Tian Xiwei, Zhang Linghe’s manager is still in pure hatred)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%BB%8F%E7%BA%AA%E4%BA%BA%E4%BE%9D%E6%97%A7%E7%BA%AF%E6%81%A8%E4%B8%AD%23) `160.0K 🔥` `-39%`
1. [怪不得有人做饭这么好吃](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E6%9C%89%E4%BA%BA%E5%81%9A%E9%A5%AD%E8%BF%99%E4%B9%88%E5%A5%BD%E5%90%83%23) `157.8K 🔥` `-26%`
1. [谢征没有言正帅 谁上班谁知道](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%B2%A1%E6%9C%89%E8%A8%80%E6%AD%A3%E5%B8%85%20%E8%B0%81%E4%B8%8A%E7%8F%AD%E8%B0%81%E7%9F%A5%E9%81%93%23) `141.9K 🔥` `-54%`
1. [15岁男孩嘴歪发现智齿长到眼窝里](https://s.weibo.com/weibo?q=%2315%E5%B2%81%E7%94%B7%E5%AD%A9%E5%98%B4%E6%AD%AA%E5%8F%91%E7%8E%B0%E6%99%BA%E9%BD%BF%E9%95%BF%E5%88%B0%E7%9C%BC%E7%AA%9D%E9%87%8C%23) `114.5K 🔥` `-21%`
1. [林依晨谈做脑部手术经历](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BE%9D%E6%99%A8%E8%B0%88%E5%81%9A%E8%84%91%E9%83%A8%E6%89%8B%E6%9C%AF%E7%BB%8F%E5%8E%86%23) `112.8K 🔥` `-31%`
1. [打赏女主播167万发现已婚起诉退款](https://s.weibo.com/weibo?q=%23%E6%89%93%E8%B5%8F%E5%A5%B3%E4%B8%BB%E6%92%AD167%E4%B8%87%E5%8F%91%E7%8E%B0%E5%B7%B2%E5%A9%9A%E8%B5%B7%E8%AF%89%E9%80%80%E6%AC%BE%23) `100.2K 🔥` `-27%`
1. [伊能静秦昊秀恩爱不管孙杨死活](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E8%83%BD%E9%9D%99%E7%A7%A6%E6%98%8A%E7%A7%80%E6%81%A9%E7%88%B1%E4%B8%8D%E7%AE%A1%E5%AD%99%E6%9D%A8%E6%AD%BB%E6%B4%BB%23) `91.2K 🔥` `-30%`
1. [苏醒为胡辣汤事件道歉](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E9%86%92%E4%B8%BA%E8%83%A1%E8%BE%A3%E6%B1%A4%E4%BA%8B%E4%BB%B6%E9%81%93%E6%AD%89%23) `76.5K 🔥` `-41%`
1. [王鹤润王玉雯 反转 (Wang Herun Wang Yuwen reverse)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%B6%A6%E7%8E%8B%E7%8E%89%E9%9B%AF%20%E5%8F%8D%E8%BD%AC%23) `76.1K 🔥` `-48%`
1. [官方通报12345投诉被泄露个人信息](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A512345%E6%8A%95%E8%AF%89%E8%A2%AB%E6%B3%84%E9%9C%B2%E4%B8%AA%E4%BA%BA%E4%BF%A1%E6%81%AF%23) `67.1K 🔥` `-29%`
1. [WB对战JDG (WB vs. JDG)](https://s.weibo.com/weibo?q=%23WB%E5%AF%B9%E6%88%98JDG%23) `67.1K 🔥` `-55%`
1. [工资都没群聊多](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E8%B5%84%E9%83%BD%E6%B2%A1%E7%BE%A4%E8%81%8A%E5%A4%9A%23) `61.6K 🔥` `-24%`

Updated at 2026-03-14 15:55:11

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
