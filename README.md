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

1. [武契奇证实购买中国超音速导弹 (Vucic confirms purchase of Chinese supersonic missiles)](https://s.weibo.com/weibo?q=%23%E6%AD%A6%E5%A5%91%E5%A5%87%E8%AF%81%E5%AE%9E%E8%B4%AD%E4%B9%B0%E4%B8%AD%E5%9B%BD%E8%B6%85%E9%9F%B3%E9%80%9F%E5%AF%BC%E5%BC%B9%23) `445.0K 🔥` `NEW`
1. [iCARV27全能上市16.98万起](https://s.weibo.com/weibo?q=%23iCARV27%E5%85%A8%E8%83%BD%E4%B8%8A%E5%B8%8216.98%E4%B8%87%E8%B5%B7%23) `355.3K 🔥` `NEW`
1. [豹豹原来是汗脚](https://s.weibo.com/weibo?q=%23%E8%B1%B9%E8%B1%B9%E5%8E%9F%E6%9D%A5%E6%98%AF%E6%B1%97%E8%84%9A%23) `144.5K 🔥` `NEW`
1. [省考行测](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%E8%A1%8C%E6%B5%8B%23) `112.7K 🔥` `NEW`
1. [多方回应除尘魔盒不吸尘](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%96%B9%E5%9B%9E%E5%BA%94%E9%99%A4%E5%B0%98%E9%AD%94%E7%9B%92%E4%B8%8D%E5%90%B8%E5%B0%98%23) `112.4K 🔥` `NEW`
1. [王冕官宣生子](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%86%95%E5%AE%98%E5%AE%A3%E7%94%9F%E5%AD%90%23) `111.9K 🔥` `NEW`
1. [美国急于退场以色列还想硬刚](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%80%A5%E4%BA%8E%E9%80%80%E5%9C%BA%E4%BB%A5%E8%89%B2%E5%88%97%E8%BF%98%E6%83%B3%E7%A1%AC%E5%88%9A%23) `111.4K 🔥` `NEW`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `110.5K 🔥` `NEW`
1. [起底3C认证充电宝造假产业链](https://s.weibo.com/weibo?q=%23%E8%B5%B7%E5%BA%953C%E8%AE%A4%E8%AF%81%E5%85%85%E7%94%B5%E5%AE%9D%E9%80%A0%E5%81%87%E4%BA%A7%E4%B8%9A%E9%93%BE%23) `110.1K 🔥` `NEW`
1. [被丢弃厕所女婴含泪抱住妈妈](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E4%B8%A2%E5%BC%83%E5%8E%95%E6%89%80%E5%A5%B3%E5%A9%B4%E5%90%AB%E6%B3%AA%E6%8A%B1%E4%BD%8F%E5%A6%88%E5%A6%88%23) `104.8K 🔥` `NEW`
1. [林孝埈为安东内利颁小轮胎 (Lin Xiaojun awarded Antonelli a small tire)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%AD%9D%E5%9F%88%E4%B8%BA%E5%AE%89%E4%B8%9C%E5%86%85%E5%88%A9%E9%A2%81%E5%B0%8F%E8%BD%AE%E8%83%8E%23) `85.7K 🔥` `NEW`
1. [产品宣称每克添加750亿活菌实测2.2万](https://s.weibo.com/weibo?q=%23%E4%BA%A7%E5%93%81%E5%AE%A3%E7%A7%B0%E6%AF%8F%E5%85%8B%E6%B7%BB%E5%8A%A0750%E4%BA%BF%E6%B4%BB%E8%8F%8C%E5%AE%9E%E6%B5%8B2.2%E4%B8%87%23) `85.6K 🔥` `NEW`
1. [16岁少年未管所遭同监区3人殴打致死](https://s.weibo.com/weibo?q=%2316%E5%B2%81%E5%B0%91%E5%B9%B4%E6%9C%AA%E7%AE%A1%E6%89%80%E9%81%AD%E5%90%8C%E7%9B%91%E5%8C%BA3%E4%BA%BA%E6%AE%B4%E6%89%93%E8%87%B4%E6%AD%BB%23) `85.4K 🔥` `NEW`
1. [1800元买猫传腹特效药竟是假兽药](https://s.weibo.com/weibo?q=%231800%E5%85%83%E4%B9%B0%E7%8C%AB%E4%BC%A0%E8%85%B9%E7%89%B9%E6%95%88%E8%8D%AF%E7%AB%9F%E6%98%AF%E5%81%87%E5%85%BD%E8%8D%AF%23) `85.4K 🔥` `NEW`
1. [点外卖的那批人开始做辅食了](https://s.weibo.com/weibo?q=%23%E7%82%B9%E5%A4%96%E5%8D%96%E7%9A%84%E9%82%A3%E6%89%B9%E4%BA%BA%E5%BC%80%E5%A7%8B%E5%81%9A%E8%BE%85%E9%A3%9F%E4%BA%86%23) `84.9K 🔥` `NEW`
1. [多款被曝工业用酶婴幼儿产品下架](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%AC%BE%E8%A2%AB%E6%9B%9D%E5%B7%A5%E4%B8%9A%E7%94%A8%E9%85%B6%E5%A9%B4%E5%B9%BC%E5%84%BF%E4%BA%A7%E5%93%81%E4%B8%8B%E6%9E%B6%23) `84.8K 🔥` `NEW`
1. [LGD零封晋级六强](https://s.weibo.com/weibo?q=%23LGD%E9%9B%B6%E5%B0%81%E6%99%8B%E7%BA%A7%E5%85%AD%E5%BC%BA%23) `84.6K 🔥` `NEW`
1. [这洗脚水是非喝不可吗](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%B4%97%E8%84%9A%E6%B0%B4%E6%98%AF%E9%9D%9E%E5%96%9D%E4%B8%8D%E5%8F%AF%E5%90%97%23) `84.6K 🔥` `NEW`
1. [女孩长期便血以为是痔疮结果是癌症](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E9%95%BF%E6%9C%9F%E4%BE%BF%E8%A1%80%E4%BB%A5%E4%B8%BA%E6%98%AF%E7%97%94%E7%96%AE%E7%BB%93%E6%9E%9C%E6%98%AF%E7%99%8C%E7%97%87%23) `539.8K 🔥` `+137%`
1. [生菜是最伟大的蔬菜](https://s.weibo.com/weibo?q=%23%E7%94%9F%E8%8F%9C%E6%98%AF%E6%9C%80%E4%BC%9F%E5%A4%A7%E7%9A%84%E8%94%AC%E8%8F%9C%23) `392.0K 🔥` `+37%`
1. [谢征收到了和离书 (Xie Zheng received the He Li Shu)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%94%B6%E5%88%B0%E4%BA%86%E5%92%8C%E7%A6%BB%E4%B9%A6%23) `140.0K 🔥` `+34%`
1. [边工作边考研的人 (People who take postgraduate entrance exams while working)](https://s.weibo.com/weibo?q=%23%E8%BE%B9%E5%B7%A5%E4%BD%9C%E8%BE%B9%E8%80%83%E7%A0%94%E7%9A%84%E4%BA%BA%23) `84.4K 🔥` `+25%`
1. [央视315晚会点了4个领域 (CCTV 315 Party highlighted 4 areas)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86315%E6%99%9A%E4%BC%9A%E7%82%B9%E4%BA%864%E4%B8%AA%E9%A2%86%E5%9F%9F%23) `1.1M 🔥`
1. [申论大作文 (Essay on essay)](https://s.weibo.com/weibo?q=%23%E7%94%B3%E8%AE%BA%E5%A4%A7%E4%BD%9C%E6%96%87%23) `795.5K 🔥`
1. [十五五规划纲要解读来了](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92%E7%BA%B2%E8%A6%81%E8%A7%A3%E8%AF%BB%E6%9D%A5%E4%BA%86%23) `598.3K 🔥`
1. [315调查眼镜到底有多暴利 (315 investigates how profitable glasses are)](https://s.weibo.com/weibo?q=%23315%E8%B0%83%E6%9F%A5%E7%9C%BC%E9%95%9C%E5%88%B0%E5%BA%95%E6%9C%89%E5%A4%9A%E6%9A%B4%E5%88%A9%23) `217.1K 🔥`
1. [云南花香蓝莓 (Yunnan floral blueberry)](https://s.weibo.com/weibo?q=%23%E4%BA%91%E5%8D%97%E8%8A%B1%E9%A6%99%E8%93%9D%E8%8E%93%23) `189.2K 🔥`
1. [霍尔木兹封锁日本最先扛不住了 (Japan was the first to be unable to handle the Hormuz blockade.)](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E5%B0%81%E9%94%81%E6%97%A5%E6%9C%AC%E6%9C%80%E5%85%88%E6%89%9B%E4%B8%8D%E4%BD%8F%E4%BA%86%23) `178.2K 🔥`
1. [Tiffany三里屯开幕](https://s.weibo.com/weibo?q=%23Tiffany%E4%B8%89%E9%87%8C%E5%B1%AF%E5%BC%80%E5%B9%95%23) `162.8K 🔥`
1. [王鹤棣新歌歌词 (Wang Hedi's new song lyrics)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%96%B0%E6%AD%8C%E6%AD%8C%E8%AF%8D%23) `162.7K 🔥`
1. [逐玉 肛泰别闹了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E8%82%9B%E6%B3%B0%E5%88%AB%E9%97%B9%E4%BA%86%23) `111.8K 🔥`
1. [陆仙人回应整容](https://s.weibo.com/weibo?q=%23%E9%99%86%E4%BB%99%E4%BA%BA%E5%9B%9E%E5%BA%94%E6%95%B4%E5%AE%B9%23) `110.7K 🔥`
1. [谢征没有言正帅 谁上班谁知道 (Xie Zheng didn’t say he was handsome. Who knows who is working?)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%B2%A1%E6%9C%89%E8%A8%80%E6%AD%A3%E5%B8%85%20%E8%B0%81%E4%B8%8A%E7%8F%AD%E8%B0%81%E7%9F%A5%E9%81%93%23) `109.7K 🔥`
1. [小红帽下楼](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%BA%A2%E5%B8%BD%E4%B8%8B%E6%A5%BC%23) `107.6K 🔥`
1. [120斤减肥减到160斤](https://s.weibo.com/weibo?q=%23120%E6%96%A4%E5%87%8F%E8%82%A5%E5%87%8F%E5%88%B0160%E6%96%A4%23) `92.5K 🔥`
1. [关晓彤程潇F1观赛造型](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E7%A8%8B%E6%BD%87F1%E8%A7%82%E8%B5%9B%E9%80%A0%E5%9E%8B%23) `90.2K 🔥`
1. [外卖到了白鹿就这样跑步迎接](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%8D%96%E5%88%B0%E4%BA%86%E7%99%BD%E9%B9%BF%E5%B0%B1%E8%BF%99%E6%A0%B7%E8%B7%91%E6%AD%A5%E8%BF%8E%E6%8E%A5%23) `87.8K 🔥`
1. [孙颖莎2比4蒯曼 (Sun Yingsha 2 to 4 Kuaiman)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E2%E6%AF%944%E8%92%AF%E6%9B%BC%23) `87.1K 🔥`
1. [央视主持人怎么也开始拍短剧了 (Why did the CCTV host start filming short dramas?)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E4%B8%BB%E6%8C%81%E4%BA%BA%E6%80%8E%E4%B9%88%E4%B9%9F%E5%BC%80%E5%A7%8B%E6%8B%8D%E7%9F%AD%E5%89%A7%E4%BA%86%23) `86.8K 🔥`
1. [金玟庭跳了姐姐真漂亮](https://s.weibo.com/weibo?q=%23%E9%87%91%E7%8E%9F%E5%BA%AD%E8%B7%B3%E4%BA%86%E5%A7%90%E5%A7%90%E7%9C%9F%E6%BC%82%E4%BA%AE%23) `85.3K 🔥`
1. [马思纯发文 (Ma Sichun posted a message)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%80%9D%E7%BA%AF%E5%8F%91%E6%96%87%23) `85.2K 🔥`
1. [生理性讨厌是藏不住的](https://s.weibo.com/weibo?q=%23%E7%94%9F%E7%90%86%E6%80%A7%E8%AE%A8%E5%8E%8C%E6%98%AF%E8%97%8F%E4%B8%8D%E4%BD%8F%E7%9A%84%23) `85.1K 🔥`
1. [瞿颖自曝不需要赚那么多钱](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%87%AA%E6%9B%9D%E4%B8%8D%E9%9C%80%E8%A6%81%E8%B5%9A%E9%82%A3%E4%B9%88%E5%A4%9A%E9%92%B1%23) `85.0K 🔥`
1. [狼队对战DYG](https://s.weibo.com/weibo?q=%23%E7%8B%BC%E9%98%9F%E5%AF%B9%E6%88%98DYG%23) `84.7K 🔥`
1. [AI时代青少年该掌握哪些能力](https://s.weibo.com/weibo?q=%23AI%E6%97%B6%E4%BB%A3%E9%9D%92%E5%B0%91%E5%B9%B4%E8%AF%A5%E6%8E%8C%E6%8F%A1%E5%93%AA%E4%BA%9B%E8%83%BD%E5%8A%9B%23) `180.7K 🔥` `-21%`
1. [建议慈善教育分层推进](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%85%88%E5%96%84%E6%95%99%E8%82%B2%E5%88%86%E5%B1%82%E6%8E%A8%E8%BF%9B%23) `178.5K 🔥` `-22%`
1. [省考申论 (Provincial Examination Application Essay)](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%E7%94%B3%E8%AE%BA%23) `177.2K 🔥` `-39%`
1. [冰箱贴一直不挪会伤害冰箱](https://s.weibo.com/weibo?q=%23%E5%86%B0%E7%AE%B1%E8%B4%B4%E4%B8%80%E7%9B%B4%E4%B8%8D%E6%8C%AA%E4%BC%9A%E4%BC%A4%E5%AE%B3%E5%86%B0%E7%AE%B1%23) `166.2K 🔥` `-27%`
1. [河南申论](https://s.weibo.com/weibo?q=%23%E6%B2%B3%E5%8D%97%E7%94%B3%E8%AE%BA%23) `115.5K 🔥` `-40%`
1. [省考](https://s.weibo.com/weibo?q=%23%E7%9C%81%E8%80%83%23) `109.3K 🔥` `-48%`
1. [老凤祥40克旧黄金置换后仅剩17克 (Lao Fengxiang’s 40 grams of old gold was replaced with only 17 grams left)](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%87%A4%E7%A5%A540%E5%85%8B%E6%97%A7%E9%BB%84%E9%87%91%E7%BD%AE%E6%8D%A2%E5%90%8E%E4%BB%85%E5%89%A917%E5%85%8B%23) `85.7K 🔥` `-34%`

Updated at 2026-03-14 18:48:59

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
