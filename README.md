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

1. [央视315晚会点了4个领域 (CCTV 315 Party highlighted 4 areas)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86315%E6%99%9A%E4%BC%9A%E7%82%B9%E4%BA%864%E4%B8%AA%E9%A2%86%E5%9F%9F%23) `817.0K 🔥` `NEW`
1. [50秒解码美丽中国](https://s.weibo.com/weibo?q=%2350%E7%A7%92%E8%A7%A3%E7%A0%81%E7%BE%8E%E4%B8%BD%E4%B8%AD%E5%9B%BD%23) `617.7K 🔥` `NEW`
1. [韩军称朝鲜发射10余枚弹道导弹](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%86%9B%E7%A7%B0%E6%9C%9D%E9%B2%9C%E5%8F%91%E5%B0%8410%E4%BD%99%E6%9E%9A%E5%BC%B9%E9%81%93%E5%AF%BC%E5%BC%B9%23) `434.4K 🔥` `NEW`
1. [张远远行巡回演唱会](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%BF%9C%E8%BF%9C%E8%A1%8C%E5%B7%A1%E5%9B%9E%E6%BC%94%E5%94%B1%E4%BC%9A%23) `366.1K 🔥` `NEW`
1. [中国女足直通巴西世界杯](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B3%E7%9B%B4%E9%80%9A%E5%B7%B4%E8%A5%BF%E4%B8%96%E7%95%8C%E6%9D%AF%23) `173.1K 🔥` `NEW`
1. [老凤祥40克旧黄金置换后仅剩17克](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%87%A4%E7%A5%A540%E5%85%8B%E6%97%A7%E9%BB%84%E9%87%91%E7%BD%AE%E6%8D%A2%E5%90%8E%E4%BB%85%E5%89%A917%E5%85%8B%23) `164.6K 🔥` `NEW`
1. [饭馆用的塑封碗筷脏到你想吐](https://s.weibo.com/weibo?q=%23%E9%A5%AD%E9%A6%86%E7%94%A8%E7%9A%84%E5%A1%91%E5%B0%81%E7%A2%97%E7%AD%B7%E8%84%8F%E5%88%B0%E4%BD%A0%E6%83%B3%E5%90%90%23) `164.5K 🔥` `NEW`
1. [格力高管被Tim追着提问](https://s.weibo.com/weibo?q=%23%E6%A0%BC%E5%8A%9B%E9%AB%98%E7%AE%A1%E8%A2%ABTim%E8%BF%BD%E7%9D%80%E6%8F%90%E9%97%AE%23) `140.8K 🔥` `NEW`
1. [男子买皮卡收到超大老头乐愁坏妻子](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E4%B9%B0%E7%9A%AE%E5%8D%A1%E6%94%B6%E5%88%B0%E8%B6%85%E5%A4%A7%E8%80%81%E5%A4%B4%E4%B9%90%E6%84%81%E5%9D%8F%E5%A6%BB%E5%AD%90%23) `139.0K 🔥` `NEW`
1. [5988买培训课承诺月入900变8元](https://s.weibo.com/weibo?q=%235988%E4%B9%B0%E5%9F%B9%E8%AE%AD%E8%AF%BE%E6%89%BF%E8%AF%BA%E6%9C%88%E5%85%A5900%E5%8F%988%E5%85%83%23) `138.3K 🔥` `NEW`
1. [孙颖莎反手发球首秀 (Sun Yingsha's backhand serve makes her debut)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E5%8F%8D%E6%89%8B%E5%8F%91%E7%90%83%E9%A6%96%E7%A7%80%23) `131.8K 🔥` `NEW`
1. [生理性讨厌是藏不住的](https://s.weibo.com/weibo?q=%23%E7%94%9F%E7%90%86%E6%80%A7%E8%AE%A8%E5%8E%8C%E6%98%AF%E8%97%8F%E4%B8%8D%E4%BD%8F%E7%9A%84%23) `123.0K 🔥` `NEW`
1. [终于不用手洗内裤袜子了](https://s.weibo.com/weibo?q=%23%E7%BB%88%E4%BA%8E%E4%B8%8D%E7%94%A8%E6%89%8B%E6%B4%97%E5%86%85%E8%A3%A4%E8%A2%9C%E5%AD%90%E4%BA%86%23) `116.2K 🔥` `NEW`
1. [瞿颖自曝不需要赚那么多钱](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%87%AA%E6%9B%9D%E4%B8%8D%E9%9C%80%E8%A6%81%E8%B5%9A%E9%82%A3%E4%B9%88%E5%A4%9A%E9%92%B1%23) `106.3K 🔥` `NEW`
1. [发现了让小猫多喝水的方法](https://s.weibo.com/weibo?q=%23%E5%8F%91%E7%8E%B0%E4%BA%86%E8%AE%A9%E5%B0%8F%E7%8C%AB%E5%A4%9A%E5%96%9D%E6%B0%B4%E7%9A%84%E6%96%B9%E6%B3%95%23) `104.1K 🔥` `NEW`
1. [孙颖莎在加油鼓励声中退场](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E5%9C%A8%E5%8A%A0%E6%B2%B9%E9%BC%93%E5%8A%B1%E5%A3%B0%E4%B8%AD%E9%80%80%E5%9C%BA%23) `93.1K 🔥` `NEW`
1. [陈楚生你浪费我的半小时拿什么赔我](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%A5%9A%E7%94%9F%E4%BD%A0%E6%B5%AA%E8%B4%B9%E6%88%91%E7%9A%84%E5%8D%8A%E5%B0%8F%E6%97%B6%E6%8B%BF%E4%BB%80%E4%B9%88%E8%B5%94%E6%88%91%23) `85.4K 🔥` `NEW`
1. [增甜油柑销往外地商家坦言本地不吃](https://s.weibo.com/weibo?q=%23%E5%A2%9E%E7%94%9C%E6%B2%B9%E6%9F%91%E9%94%80%E5%BE%80%E5%A4%96%E5%9C%B0%E5%95%86%E5%AE%B6%E5%9D%A6%E8%A8%80%E6%9C%AC%E5%9C%B0%E4%B8%8D%E5%90%83%23) `83.9K 🔥` `NEW`
1. [中国女足2比0中国台北队](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B32%E6%AF%940%E4%B8%AD%E5%9B%BD%E5%8F%B0%E5%8C%97%E9%98%9F%23) `79.9K 🔥` `NEW`
1. [无畏苏烈王来了](https://s.weibo.com/weibo?q=%23%E6%97%A0%E7%95%8F%E8%8B%8F%E7%83%88%E7%8E%8B%E6%9D%A5%E4%BA%86%23) `79.5K 🔥` `NEW`
1. [我看推理小说 等着侦探说答案 (I read mystery novels and wait for the detective to tell me the answer.)](https://s.weibo.com/weibo?q=%23%E6%88%91%E7%9C%8B%E6%8E%A8%E7%90%86%E5%B0%8F%E8%AF%B4%20%E7%AD%89%E7%9D%80%E4%BE%A6%E6%8E%A2%E8%AF%B4%E7%AD%94%E6%A1%88%23) `74.7K 🔥` `NEW`
1. [云南花香蓝莓 (Yunnan floral blueberry)](https://s.weibo.com/weibo?q=%23%E4%BA%91%E5%8D%97%E8%8A%B1%E9%A6%99%E8%93%9D%E8%8E%93%23) `490.9K 🔥` `+51%`
1. [爸爸给被丢弃厕所女儿准备金手镯](https://s.weibo.com/weibo?q=%23%E7%88%B8%E7%88%B8%E7%BB%99%E8%A2%AB%E4%B8%A2%E5%BC%83%E5%8E%95%E6%89%80%E5%A5%B3%E5%84%BF%E5%87%86%E5%A4%87%E9%87%91%E6%89%8B%E9%95%AF%23) `390.8K 🔥` `+140%`
1. [关晓彤程潇F1观赛造型](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E7%A8%8B%E6%BD%87F1%E8%A7%82%E8%B5%9B%E9%80%A0%E5%9E%8B%23) `136.5K 🔥` `+21%`
1. [WB对战JDG (WB vs. JDG)](https://s.weibo.com/weibo?q=%23WB%E5%AF%B9%E6%88%98JDG%23) `106.8K 🔥` `+59%`
1. [315调查眼镜到底有多暴利 (315 investigates how profitable glasses are)](https://s.weibo.com/weibo?q=%23315%E8%B0%83%E6%9F%A5%E7%9C%BC%E9%95%9C%E5%88%B0%E5%BA%95%E6%9C%89%E5%A4%9A%E6%9A%B4%E5%88%A9%23) `1.1M 🔥`
1. [王鹤棣新歌歌词 (Wang Hedi's new song lyrics)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%96%B0%E6%AD%8C%E6%AD%8C%E8%AF%8D%23) `305.5K 🔥`
1. [霍尔木兹封锁日本最先扛不住了 (Japan was the first to be unable to handle the Hormuz blockade.)](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E5%B0%81%E9%94%81%E6%97%A5%E6%9C%AC%E6%9C%80%E5%85%88%E6%89%9B%E4%B8%8D%E4%BD%8F%E4%BA%86%23) `163.4K 🔥`
1. [马思纯发文](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%80%9D%E7%BA%AF%E5%8F%91%E6%96%87%23) `162.4K 🔥`
1. [富二代为情人落户雇人假结婚](https://s.weibo.com/weibo?q=%23%E5%AF%8C%E4%BA%8C%E4%BB%A3%E4%B8%BA%E6%83%85%E4%BA%BA%E8%90%BD%E6%88%B7%E9%9B%87%E4%BA%BA%E5%81%87%E7%BB%93%E5%A9%9A%23) `161.4K 🔥`
1. [王一博给品牌发title (Wang Yibo sends a title to the brand)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E7%BB%99%E5%93%81%E7%89%8C%E5%8F%91title%23) `154.5K 🔥`
1. [田曦薇张凌赫经纪人依旧纯恨中 (Tian Xiwei, Zhang Linghe’s manager is still in pure hatred)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%BB%8F%E7%BA%AA%E4%BA%BA%E4%BE%9D%E6%97%A7%E7%BA%AF%E6%81%A8%E4%B8%AD%23) `141.1K 🔥`
1. [谢征没有言正帅 谁上班谁知道](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%B2%A1%E6%9C%89%E8%A8%80%E6%AD%A3%E5%B8%85%20%E8%B0%81%E4%B8%8A%E7%8F%AD%E8%B0%81%E7%9F%A5%E9%81%93%23) `136.8K 🔥`
1. [外卖到了白鹿就这样跑步迎接](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%8D%96%E5%88%B0%E4%BA%86%E7%99%BD%E9%B9%BF%E5%B0%B1%E8%BF%99%E6%A0%B7%E8%B7%91%E6%AD%A5%E8%BF%8E%E6%8E%A5%23) `98.9K 🔥`
1. [15岁男孩嘴歪发现智齿长到眼窝里](https://s.weibo.com/weibo?q=%2315%E5%B2%81%E7%94%B7%E5%AD%A9%E5%98%B4%E6%AD%AA%E5%8F%91%E7%8E%B0%E6%99%BA%E9%BD%BF%E9%95%BF%E5%88%B0%E7%9C%BC%E7%AA%9D%E9%87%8C%23) `98.8K 🔥`
1. [中国女足1比0中国台北](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E8%B6%B31%E6%AF%940%E4%B8%AD%E5%9B%BD%E5%8F%B0%E5%8C%97%23) `95.4K 🔥`
1. [林依晨谈做脑部手术经历](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BE%9D%E6%99%A8%E8%B0%88%E5%81%9A%E8%84%91%E9%83%A8%E6%89%8B%E6%9C%AF%E7%BB%8F%E5%8E%86%23) `91.6K 🔥`
1. [孔雪儿 只想演强制爱 (Kong Seol just wants to play forced love)](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%20%E5%8F%AA%E6%83%B3%E6%BC%94%E5%BC%BA%E5%88%B6%E7%88%B1%23) `81.8K 🔥`
1. [省考](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%23) `79.9K 🔥`
1. [第31届白玉兰奖 (The 31st Magnolia Award)](https://s.weibo.com/weibo?q=%23%E7%AC%AC31%E5%B1%8A%E7%99%BD%E7%8E%89%E5%85%B0%E5%A5%96%23) `79.2K 🔥`
1. [原神](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E7%A5%9E%23) `75.7K 🔥`
1. [谢征收到了和离书 (Xie Zheng received the He Li Shu)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%94%B6%E5%88%B0%E4%BA%86%E5%92%8C%E7%A6%BB%E4%B9%A6%23) `161.0K 🔥` `-27%`
1. [美国凭啥从委内瑞拉搬走1亿美元黄金](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%87%AD%E5%95%A5%E4%BB%8E%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E6%90%AC%E8%B5%B01%E4%BA%BF%E7%BE%8E%E5%85%83%E9%BB%84%E9%87%91%23) `157.5K 🔥` `-27%`
1. [蒯曼回应4比2孙颖莎](https://s.weibo.com/weibo?q=%23%E8%92%AF%E6%9B%BC%E5%9B%9E%E5%BA%944%E6%AF%942%E5%AD%99%E9%A2%96%E8%8E%8E%23) `130.8K 🔥` `-32%`
1. [上海F1偶遇关晓彤](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7F1%E5%81%B6%E9%81%87%E5%85%B3%E6%99%93%E5%BD%A4%23) `115.8K 🔥` `-27%`
1. [孙颖莎2比4蒯曼](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E2%E6%AF%944%E8%92%AF%E6%9B%BC%23) `113.9K 🔥` `-86%`
1. [怪不得有人做饭这么好吃](https://s.weibo.com/weibo?q=%23%E6%80%AA%E4%B8%8D%E5%BE%97%E6%9C%89%E4%BA%BA%E5%81%9A%E9%A5%AD%E8%BF%99%E4%B9%88%E5%A5%BD%E5%90%83%23) `108.9K 🔥` `-31%`
1. [赵丽颖已经三提白玉兰了](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%B8%BD%E9%A2%96%E5%B7%B2%E7%BB%8F%E4%B8%89%E6%8F%90%E7%99%BD%E7%8E%89%E5%85%B0%E4%BA%86%23) `102.7K 🔥` `-37%`
1. [25岁硕士曝光剧本直播间被死亡威胁](https://s.weibo.com/weibo?q=%2325%E5%B2%81%E7%A1%95%E5%A3%AB%E6%9B%9D%E5%85%89%E5%89%A7%E6%9C%AC%E7%9B%B4%E6%92%AD%E9%97%B4%E8%A2%AB%E6%AD%BB%E4%BA%A1%E5%A8%81%E8%83%81%23) `82.6K 🔥` `-27%`
1. [女足 (women's football)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E8%B6%B3%23) `82.2K 🔥` `-47%`
1. [清明节放假安排来了 (Tomb Sweeping Day holiday arrangements are here)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E8%8A%82%E6%94%BE%E5%81%87%E5%AE%89%E6%8E%92%E6%9D%A5%E4%BA%86%23) `76.9K 🔥` `-31%`

Updated at 2026-03-14 16:37:38

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
