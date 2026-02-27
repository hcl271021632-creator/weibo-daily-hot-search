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

1. [未开封杨枝甘露8天后爆炸 (Unopened poplar nectar exploded after 8 days)](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E5%BC%80%E5%B0%81%E6%9D%A8%E6%9E%9D%E7%94%98%E9%9C%B28%E5%A4%A9%E5%90%8E%E7%88%86%E7%82%B8%23) `809.5K 🔥` `NEW`
1. [新娘出嫁徒手拔光碎发](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%A8%98%E5%87%BA%E5%AB%81%E5%BE%92%E6%89%8B%E6%8B%94%E5%85%89%E7%A2%8E%E5%8F%91%23) `621.0K 🔥` `NEW`
1. [腾讯感谢爱奇艺宣传逐玉](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E6%84%9F%E8%B0%A2%E7%88%B1%E5%A5%87%E8%89%BA%E5%AE%A3%E4%BC%A0%E9%80%90%E7%8E%89%23) `282.3K 🔥` `NEW`
1. [女子婚内出轨同居犯重婚罪获刑](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%A9%9A%E5%86%85%E5%87%BA%E8%BD%A8%E5%90%8C%E5%B1%85%E7%8A%AF%E9%87%8D%E5%A9%9A%E7%BD%AA%E8%8E%B7%E5%88%91%23) `240.0K 🔥` `NEW`
1. [P图的时候忘记P的是实况](https://s.weibo.com/weibo?q=%23P%E5%9B%BE%E7%9A%84%E6%97%B6%E5%80%99%E5%BF%98%E8%AE%B0P%E7%9A%84%E6%98%AF%E5%AE%9E%E5%86%B5%23) `238.8K 🔥` `NEW`
1. [为给43岁哥哥求姻缘发动全家砍树](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E7%BB%9943%E5%B2%81%E5%93%A5%E5%93%A5%E6%B1%82%E5%A7%BB%E7%BC%98%E5%8F%91%E5%8A%A8%E5%85%A8%E5%AE%B6%E7%A0%8D%E6%A0%91%23) `238.6K 🔥` `NEW`
1. [一点点资助男孩手表系亲戚凑钱购买](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%82%B9%E7%82%B9%E8%B5%84%E5%8A%A9%E7%94%B7%E5%AD%A9%E6%89%8B%E8%A1%A8%E7%B3%BB%E4%BA%B2%E6%88%9A%E5%87%91%E9%92%B1%E8%B4%AD%E4%B9%B0%23) `238.5K 🔥` `NEW`
1. [李亚鹏官宣与哥哥和解](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BA%9A%E9%B9%8F%E5%AE%98%E5%AE%A3%E4%B8%8E%E5%93%A5%E5%93%A5%E5%92%8C%E8%A7%A3%23) `236.6K 🔥` `NEW`
1. [米哈游内部发文回应员工意外离世](https://s.weibo.com/weibo?q=%23%E7%B1%B3%E5%93%88%E6%B8%B8%E5%86%85%E9%83%A8%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%E5%91%98%E5%B7%A5%E6%84%8F%E5%A4%96%E7%A6%BB%E4%B8%96%23) `191.4K 🔥` `NEW`
1. [白敬亭章若楠 二搭](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E7%AB%A0%E8%8B%A5%E6%A5%A0%20%E4%BA%8C%E6%90%AD%23) `191.1K 🔥` `NEW`
1. [杨幂唐嫣看秀生图 (Yang Mi and Tang Yan look at Xiu Sheng pictures)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E5%94%90%E5%AB%A3%E7%9C%8B%E7%A7%80%E7%94%9F%E5%9B%BE%23) `184.5K 🔥` `NEW`
1. [AI短剧已经丝滑到这种程度了](https://s.weibo.com/weibo?q=%23AI%E7%9F%AD%E5%89%A7%E5%B7%B2%E7%BB%8F%E4%B8%9D%E6%BB%91%E5%88%B0%E8%BF%99%E7%A7%8D%E7%A8%8B%E5%BA%A6%E4%BA%86%23) `166.2K 🔥` `NEW`
1. [内娱男艺人要下海开酒吧了](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A8%B1%E7%94%B7%E8%89%BA%E4%BA%BA%E8%A6%81%E4%B8%8B%E6%B5%B7%E5%BC%80%E9%85%92%E5%90%A7%E4%BA%86%23) `148.2K 🔥` `NEW`
1. [赵晴好灵](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E6%99%B4%E5%A5%BD%E7%81%B5%23) `141.6K 🔥` `NEW`
1. [男子高铁抽烟还把脚放窗上](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E9%AB%98%E9%93%81%E6%8A%BD%E7%83%9F%E8%BF%98%E6%8A%8A%E8%84%9A%E6%94%BE%E7%AA%97%E4%B8%8A%23) `128.7K 🔥` `NEW`
1. [豆包严正声明](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%E4%B8%A5%E6%AD%A3%E5%A3%B0%E6%98%8E%23) `118.9K 🔥` `NEW`
1. [这么多年带出去玩的内衣都错付了](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B9%88%E5%A4%9A%E5%B9%B4%E5%B8%A6%E5%87%BA%E5%8E%BB%E7%8E%A9%E7%9A%84%E5%86%85%E8%A1%A3%E9%83%BD%E9%94%99%E4%BB%98%E4%BA%86%23) `106.3K 🔥` `NEW`
1. [尹净汉在香港](https://s.weibo.com/weibo?q=%23%E5%B0%B9%E5%87%80%E6%B1%89%E5%9C%A8%E9%A6%99%E6%B8%AF%23) `103.4K 🔥` `NEW`
1. [全红婵秀街舞回应被网友攻击](https://s.weibo.com/weibo?q=%23%E5%85%A8%E7%BA%A2%E5%A9%B5%E7%A7%80%E8%A1%97%E8%88%9E%E5%9B%9E%E5%BA%94%E8%A2%AB%E7%BD%91%E5%8F%8B%E6%94%BB%E5%87%BB%23) `101.3K 🔥` `NEW`
1. [真正的门当户对](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%AD%A3%E7%9A%84%E9%97%A8%E5%BD%93%E6%88%B7%E5%AF%B9%23) `78.8K 🔥` `NEW`
1. [43岁也能考编了 (I can take the exam at 43 years old)](https://s.weibo.com/weibo?q=%2343%E5%B2%81%E4%B9%9F%E8%83%BD%E8%80%83%E7%BC%96%E4%BA%86%23) `579.1K 🔥` `+482%`
1. [头像洁癖](https://s.weibo.com/weibo?q=%23%E5%A4%B4%E5%83%8F%E6%B4%81%E7%99%96%23) `530.5K 🔥` `+201%`
1. [魅族](https://s.weibo.com/weibo?q=%23%E9%AD%85%E6%97%8F%23) `240.8K 🔥` `+53%`
1. [见春天 陈飞宇王影璐](https://s.weibo.com/weibo?q=%23%E8%A7%81%E6%98%A5%E5%A4%A9%20%E9%99%88%E9%A3%9E%E5%AE%87%E7%8E%8B%E5%BD%B1%E7%92%90%23) `239.5K 🔥` `+132%`
1. [杨幂登陆少年组合Prada大秀同框](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E7%99%BB%E9%99%86%E5%B0%91%E5%B9%B4%E7%BB%84%E5%90%88Prada%E5%A4%A7%E7%A7%80%E5%90%8C%E6%A1%86%23) `238.7K 🔥` `+28%`
1. [Tiffany卞耀汉结婚](https://s.weibo.com/weibo?q=%23Tiffany%E5%8D%9E%E8%80%80%E6%B1%89%E7%BB%93%E5%A9%9A%23) `238.1K 🔥` `+32%`
1. [今天的饺子是王一博擀的皮](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%A4%A9%E7%9A%84%E9%A5%BA%E5%AD%90%E6%98%AF%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%93%80%E7%9A%84%E7%9A%AE%23) `226.2K 🔥` `+31%`
1. [台独刘世芳亲属在大陆投资谋利](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E7%8B%AC%E5%88%98%E4%B8%96%E8%8A%B3%E4%BA%B2%E5%B1%9E%E5%9C%A8%E5%A4%A7%E9%99%86%E6%8A%95%E8%B5%84%E8%B0%8B%E5%88%A9%23) `190.6K 🔥` `+64%`
1. [现在就出发4 (Let's go now 4)](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%23) `1.1M 🔥`
1. [美国发动网攻侵占全球虚拟资产](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%8F%91%E5%8A%A8%E7%BD%91%E6%94%BB%E4%BE%B5%E5%8D%A0%E5%85%A8%E7%90%83%E8%99%9A%E6%8B%9F%E8%B5%84%E4%BA%A7%23) `631.0K 🔥`
1. [虞书欣父亲借贷案三大焦点 (Three major focuses of Yu Shuxin’s father’s loan case)](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E7%88%B6%E4%BA%B2%E5%80%9F%E8%B4%B7%E6%A1%88%E4%B8%89%E5%A4%A7%E7%84%A6%E7%82%B9%23) `240.2K 🔥`
1. [小徐六级277分](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%BE%90%E5%85%AD%E7%BA%A7277%E5%88%86%23) `239.3K 🔥`
1. [伊能静 真的别再雌竞了 (Yi Nengjing, really stop competing with females.)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E8%83%BD%E9%9D%99%20%E7%9C%9F%E7%9A%84%E5%88%AB%E5%86%8D%E9%9B%8C%E7%AB%9E%E4%BA%86%23) `238.3K 🔥`
1. [白宇和前女友分手原因](https://s.weibo.com/weibo?q=%23%E7%99%BD%E5%AE%87%E5%92%8C%E5%89%8D%E5%A5%B3%E5%8F%8B%E5%88%86%E6%89%8B%E5%8E%9F%E5%9B%A0%23) `191.3K 🔥`
1. [尘白禁区联动取消 (Linkage cancellation of Chenbai restricted area)](https://s.weibo.com/weibo?q=%23%E5%B0%98%E7%99%BD%E7%A6%81%E5%8C%BA%E8%81%94%E5%8A%A8%E5%8F%96%E6%B6%88%23) `190.7K 🔥`
1. [刘晓艳现身小徐直播间](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E8%89%B3%E7%8E%B0%E8%BA%AB%E5%B0%8F%E5%BE%90%E7%9B%B4%E6%92%AD%E9%97%B4%23) `190.5K 🔥`
1. [少女时代第一个结婚的人](https://s.weibo.com/weibo?q=%23%E5%B0%91%E5%A5%B3%E6%97%B6%E4%BB%A3%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%BB%93%E5%A9%9A%E7%9A%84%E4%BA%BA%23) `111.3K 🔥`
1. [意大利小偷把肾结石误认黄金偷走 (Italian thief mistook kidney stone for gold and stole it)](https://s.weibo.com/weibo?q=%23%E6%84%8F%E5%A4%A7%E5%88%A9%E5%B0%8F%E5%81%B7%E6%8A%8A%E8%82%BE%E7%BB%93%E7%9F%B3%E8%AF%AF%E8%AE%A4%E9%BB%84%E9%87%91%E5%81%B7%E8%B5%B0%23) `426.0K 🔥` `-50%`
1. [姜妍常驻现在就出发](https://s.weibo.com/weibo?q=%23%E5%A7%9C%E5%A6%8D%E5%B8%B8%E9%A9%BB%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%91%23) `334.7K 🔥` `-39%`
1. [替父请假2小时致其被开除女子发声](https://s.weibo.com/weibo?q=%23%E6%9B%BF%E7%88%B6%E8%AF%B7%E5%81%872%E5%B0%8F%E6%97%B6%E8%87%B4%E5%85%B6%E8%A2%AB%E5%BC%80%E9%99%A4%E5%A5%B3%E5%AD%90%E5%8F%91%E5%A3%B0%23) `238.7K 🔥` `-57%`
1. [不建议在朋友圈展示技能](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%BB%BA%E8%AE%AE%E5%9C%A8%E6%9C%8B%E5%8F%8B%E5%9C%88%E5%B1%95%E7%A4%BA%E6%8A%80%E8%83%BD%23) `238.1K 🔥` `-39%`
1. [Cat退役发长文](https://s.weibo.com/weibo?q=%23Cat%E9%80%80%E5%BD%B9%E5%8F%91%E9%95%BF%E6%96%87%23) `168.2K 🔥` `-36%`
1. [彪马店员说买不起别试](https://s.weibo.com/weibo?q=%23%E5%BD%AA%E9%A9%AC%E5%BA%97%E5%91%98%E8%AF%B4%E4%B9%B0%E4%B8%8D%E8%B5%B7%E5%88%AB%E8%AF%95%23) `136.5K 🔥` `-59%`
1. [姐姐姐夫](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%23) `135.5K 🔥` `-29%`
1. [丈夫准备给诞下5胞胎老婆送黄金 (Husband plans to give gold to wife who gave birth to quintuplets)](https://s.weibo.com/weibo?q=%23%E4%B8%88%E5%A4%AB%E5%87%86%E5%A4%87%E7%BB%99%E8%AF%9E%E4%B8%8B5%E8%83%9E%E8%83%8E%E8%80%81%E5%A9%86%E9%80%81%E9%BB%84%E9%87%91%23) `133.0K 🔥` `-43%`
1. [比尔盖茨被曝是裸体夜店常客 (Bill Gates revealed to be a nude nightclub regular)](https://s.weibo.com/weibo?q=%23%E6%AF%94%E5%B0%94%E7%9B%96%E8%8C%A8%E8%A2%AB%E6%9B%9D%E6%98%AF%E8%A3%B8%E4%BD%93%E5%A4%9C%E5%BA%97%E5%B8%B8%E5%AE%A2%23) `126.1K 🔥` `-29%`
1. [千元机或将消失](https://s.weibo.com/weibo?q=%23%E5%8D%83%E5%85%83%E6%9C%BA%E6%88%96%E5%B0%86%E6%B6%88%E5%A4%B1%23) `90.1K 🔥` `-56%`
1. [山西卫健委已严肃约谈市急救中心](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E8%A5%BF%E5%8D%AB%E5%81%A5%E5%A7%94%E5%B7%B2%E4%B8%A5%E8%82%83%E7%BA%A6%E8%B0%88%E5%B8%82%E6%80%A5%E6%95%91%E4%B8%AD%E5%BF%83%23) `79.6K 🔥` `-51%`
1. [高叶宋妍霏回应臭脸 (Gao Ye and Song Yanfei responded with a bad face)](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%8F%B6%E5%AE%8B%E5%A6%8D%E9%9C%8F%E5%9B%9E%E5%BA%94%E8%87%AD%E8%84%B8%23) `78.6K 🔥` `-45%`

Updated at 2026-02-27 16:47:16

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
