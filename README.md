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

1. [建议小学三年级前课间半小时 (It is recommended that half an hour be allowed in the recess before the third grade of primary school)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%B0%8F%E5%AD%A6%E4%B8%89%E5%B9%B4%E7%BA%A7%E5%89%8D%E8%AF%BE%E9%97%B4%E5%8D%8A%E5%B0%8F%E6%97%B6%23) `781.7K 🔥` `NEW`
1. [两会声音传递法治力度民生温度](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BC%9A%E5%A3%B0%E9%9F%B3%E4%BC%A0%E9%80%92%E6%B3%95%E6%B2%BB%E5%8A%9B%E5%BA%A6%E6%B0%91%E7%94%9F%E6%B8%A9%E5%BA%A6%23) `629.6K 🔥` `NEW`
1. [OPPO涨价](https://s.weibo.com/weibo?q=%23OPPO%E6%B6%A8%E4%BB%B7%23) `618.6K 🔥` `NEW`
1. [樊长玉得知谢征是武安侯](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E5%BE%97%E7%9F%A5%E8%B0%A2%E5%BE%81%E6%98%AF%E6%AD%A6%E5%AE%89%E4%BE%AF%23) `391.6K 🔥` `NEW`
1. [手机市场将迎来全面涨价](https://s.weibo.com/weibo?q=%23%E6%89%8B%E6%9C%BA%E5%B8%82%E5%9C%BA%E5%B0%86%E8%BF%8E%E6%9D%A5%E5%85%A8%E9%9D%A2%E6%B6%A8%E4%BB%B7%23) `390.3K 🔥` `NEW`
1. [代表说儿子告诉他千万不要爹味太浓](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E8%AF%B4%E5%84%BF%E5%AD%90%E5%91%8A%E8%AF%89%E4%BB%96%E5%8D%83%E4%B8%87%E4%B8%8D%E8%A6%81%E7%88%B9%E5%91%B3%E5%A4%AA%E6%B5%93%23) `389.9K 🔥` `NEW`
1. [制造业升级的超级红包来了](https://s.weibo.com/weibo?q=%23%E5%88%B6%E9%80%A0%E4%B8%9A%E5%8D%87%E7%BA%A7%E7%9A%84%E8%B6%85%E7%BA%A7%E7%BA%A2%E5%8C%85%E6%9D%A5%E4%BA%86%23) `388.4K 🔥` `NEW`
1. [五月天演唱会取消24号场次](https://s.weibo.com/weibo?q=%23%E4%BA%94%E6%9C%88%E5%A4%A9%E6%BC%94%E5%94%B1%E4%BC%9A%E5%8F%96%E6%B6%8824%E5%8F%B7%E5%9C%BA%E6%AC%A1%23) `386.3K 🔥` `NEW`
1. [香蕉有可能会灭绝](https://s.weibo.com/weibo?q=%23%E9%A6%99%E8%95%89%E6%9C%89%E5%8F%AF%E8%83%BD%E4%BC%9A%E7%81%AD%E7%BB%9D%23) `385.9K 🔥` `NEW`
1. [爱奇艺逐玉标题00后写的吧](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%A5%87%E8%89%BA%E9%80%90%E7%8E%89%E6%A0%87%E9%A2%9800%E5%90%8E%E5%86%99%E7%9A%84%E5%90%A7%23) `381.9K 🔥` `NEW`
1. [周深 合同签了吗 (Zhou Shen, has the contract been signed?)](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B7%B1%20%E5%90%88%E5%90%8C%E7%AD%BE%E4%BA%86%E5%90%97%23) `380.5K 🔥` `NEW`
1. [火鸡面冰淇淋](https://s.weibo.com/weibo?q=%23%E7%81%AB%E9%B8%A1%E9%9D%A2%E5%86%B0%E6%B7%87%E6%B7%8B%23) `377.0K 🔥` `NEW`
1. [谁上班不想来包薯片](https://s.weibo.com/weibo?q=%23%E8%B0%81%E4%B8%8A%E7%8F%AD%E4%B8%8D%E6%83%B3%E6%9D%A5%E5%8C%85%E8%96%AF%E7%89%87%23) `372.9K 🔥` `NEW`
1. [代表呼吁提高中低收入人群育儿补贴](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%91%BC%E5%90%81%E6%8F%90%E9%AB%98%E4%B8%AD%E4%BD%8E%E6%94%B6%E5%85%A5%E4%BA%BA%E7%BE%A4%E8%82%B2%E5%84%BF%E8%A1%A5%E8%B4%B4%23) `369.1K 🔥` `NEW`
1. [逐玉原来谢征亲回去了](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8E%9F%E6%9D%A5%E8%B0%A2%E5%BE%81%E4%BA%B2%E5%9B%9E%E5%8E%BB%E4%BA%86%23) `366.3K 🔥` `NEW`
1. [Ella送别袁惟仁哭到抽搐](https://s.weibo.com/weibo?q=%23Ella%E9%80%81%E5%88%AB%E8%A2%81%E6%83%9F%E4%BB%81%E5%93%AD%E5%88%B0%E6%8A%BD%E6%90%90%23) `362.2K 🔥` `NEW`
1. [美国开始甩锅了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%BC%80%E5%A7%8B%E7%94%A9%E9%94%85%E4%BA%86%23) `359.5K 🔥` `NEW`
1. [经纪公司否认张娜拉去世](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E7%BA%AA%E5%85%AC%E5%8F%B8%E5%90%A6%E8%AE%A4%E5%BC%A0%E5%A8%9C%E6%8B%89%E5%8E%BB%E4%B8%96%23) `358.9K 🔥` `NEW`
1. [别再吃高油高盐的食物了](https://s.weibo.com/weibo?q=%23%E5%88%AB%E5%86%8D%E5%90%83%E9%AB%98%E6%B2%B9%E9%AB%98%E7%9B%90%E7%9A%84%E9%A3%9F%E7%89%A9%E4%BA%86%23) `358.8K 🔥` `NEW`
1. [涉密人员被开除主动投靠间谍机关](https://s.weibo.com/weibo?q=%23%E6%B6%89%E5%AF%86%E4%BA%BA%E5%91%98%E8%A2%AB%E5%BC%80%E9%99%A4%E4%B8%BB%E5%8A%A8%E6%8A%95%E9%9D%A0%E9%97%B4%E8%B0%8D%E6%9C%BA%E5%85%B3%23) `358.5K 🔥` `NEW`
1. [袁惟仁告别式 (Yuan Weiren's farewell ceremony)](https://s.weibo.com/weibo?q=%23%E8%A2%81%E6%83%9F%E4%BB%81%E5%91%8A%E5%88%AB%E5%BC%8F%23) `358.4K 🔥` `NEW`
1. [20头整容骆驼参加选美被抓包](https://s.weibo.com/weibo?q=%2320%E5%A4%B4%E6%95%B4%E5%AE%B9%E9%AA%86%E9%A9%BC%E5%8F%82%E5%8A%A0%E9%80%89%E7%BE%8E%E8%A2%AB%E6%8A%93%E5%8C%85%23) `358.4K 🔥` `NEW`
1. [腾讯版小龙虾致歉信](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E7%89%88%E5%B0%8F%E9%BE%99%E8%99%BE%E8%87%B4%E6%AD%89%E4%BF%A1%23) `358.1K 🔥` `NEW`
1. [男子养双头龟喂食时2个头还争食](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%85%BB%E5%8F%8C%E5%A4%B4%E9%BE%9F%E5%96%82%E9%A3%9F%E6%97%B62%E4%B8%AA%E5%A4%B4%E8%BF%98%E4%BA%89%E9%A3%9F%23) `358.0K 🔥` `NEW`
1. [王一博巴黎大秀第三套](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%B7%B4%E9%BB%8E%E5%A4%A7%E7%A7%80%E7%AC%AC%E4%B8%89%E5%A5%97%23) `357.8K 🔥` `NEW`
1. [林书豪说蒲熠星长得好漂亮](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%B9%A6%E8%B1%AA%E8%AF%B4%E8%92%B2%E7%86%A0%E6%98%9F%E9%95%BF%E5%BE%97%E5%A5%BD%E6%BC%82%E4%BA%AE%23) `357.7K 🔥` `NEW`
1. [315消费段位大比拼](https://s.weibo.com/weibo?q=%23315%E6%B6%88%E8%B4%B9%E6%AE%B5%E4%BD%8D%E5%A4%A7%E6%AF%94%E6%8B%BC%23) `357.6K 🔥` `NEW`
1. [美官员称都是以色列干的](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AE%98%E5%91%98%E7%A7%B0%E9%83%BD%E6%98%AF%E4%BB%A5%E8%89%B2%E5%88%97%E5%B9%B2%E7%9A%84%23) `357.6K 🔥` `NEW`
1. [宋雨琦客串韩剧](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E9%9B%A8%E7%90%A6%E5%AE%A2%E4%B8%B2%E9%9F%A9%E5%89%A7%23) `357.4K 🔥` `NEW`
1. [谭松韵新剧唱歌跑调](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E6%96%B0%E5%89%A7%E5%94%B1%E6%AD%8C%E8%B7%91%E8%B0%83%23) `357.3K 🔥` `NEW`
1. [养龙虾是风口还是大坑 (Is lobster farming an outlet or a pitfall?)](https://s.weibo.com/weibo?q=%23%E5%85%BB%E9%BE%99%E8%99%BE%E6%98%AF%E9%A3%8E%E5%8F%A3%E8%BF%98%E6%98%AF%E5%A4%A7%E5%9D%91%23) `356.9K 🔥` `NEW`
1. [正在解决地外星球长期生存问题](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E5%9C%A8%E8%A7%A3%E5%86%B3%E5%9C%B0%E5%A4%96%E6%98%9F%E7%90%83%E9%95%BF%E6%9C%9F%E7%94%9F%E5%AD%98%E9%97%AE%E9%A2%98%23) `619.2K 🔥` `+261%`
1. [快乐出发 全新QQ3正式预售 (Happy departure, the new QQ3 is officially on pre-sale)](https://s.weibo.com/weibo?q=%23%E5%BF%AB%E4%B9%90%E5%87%BA%E5%8F%91%20%E5%85%A8%E6%96%B0QQ3%E6%AD%A3%E5%BC%8F%E9%A2%84%E5%94%AE%23) `391.4K 🔥` `+53%`
1. [美媒称这场战争打不起了](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%AA%92%E7%A7%B0%E8%BF%99%E5%9C%BA%E6%88%98%E4%BA%89%E6%89%93%E4%B8%8D%E8%B5%B7%E4%BA%86%23) `383.5K 🔥` `+160%`
1. [伊朗称驱逐美以大使可过霍尔木兹](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E9%A9%B1%E9%80%90%E7%BE%8E%E4%BB%A5%E5%A4%A7%E4%BD%BF%E5%8F%AF%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%23) `381.8K 🔥` `+133%`
1. [未来5年中国要建设的重大工程](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A55%E5%B9%B4%E4%B8%AD%E5%9B%BD%E8%A6%81%E5%BB%BA%E8%AE%BE%E7%9A%84%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%23) `369.9K 🔥` `+124%`
1. [伊朗放弃猛打猛冲](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%94%BE%E5%BC%83%E7%8C%9B%E6%89%93%E7%8C%9B%E5%86%B2%23) `358.9K 🔥` `+202%`
1. [医生提醒不要模仿Ella真空腹 (Doctor reminds not to imitate Ella’s vacuum abdomen)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E6%8F%90%E9%86%92%E4%B8%8D%E8%A6%81%E6%A8%A1%E4%BB%BFElla%E7%9C%9F%E7%A9%BA%E8%85%B9%23) `358.7K 🔥` `+202%`
1. [性格有5个特点的人更容易长寿](https://s.weibo.com/weibo?q=%23%E6%80%A7%E6%A0%BC%E6%9C%895%E4%B8%AA%E7%89%B9%E7%82%B9%E7%9A%84%E4%BA%BA%E6%9B%B4%E5%AE%B9%E6%98%93%E9%95%BF%E5%AF%BF%23) `358.3K 🔥` `+201%`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `358.2K 🔥` `+46%`
1. [刘亦菲LV大秀造型图](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2LV%E5%A4%A7%E7%A7%80%E9%80%A0%E5%9E%8B%E5%9B%BE%23) `357.9K 🔥` `+201%`
1. [泽连斯基称已有11国向乌克兰求助](https://s.weibo.com/weibo?q=%23%E6%B3%BD%E8%BF%9E%E6%96%AF%E5%9F%BA%E7%A7%B0%E5%B7%B2%E6%9C%8911%E5%9B%BD%E5%90%91%E4%B9%8C%E5%85%8B%E5%85%B0%E6%B1%82%E5%8A%A9%23) `357.8K 🔥` `+201%`
1. [胖东来八成员工月收入9000元 (Eighty percent of employees at Fat Dong Lai earn 9,000 yuan a month)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A5%E5%85%AB%E6%88%90%E5%91%98%E5%B7%A5%E6%9C%88%E6%94%B6%E5%85%A59000%E5%85%83%23) `357.2K 🔥` `+200%`
1. [王一博谷爱凌张钧甯合影](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E8%B0%B7%E7%88%B1%E5%87%8C%E5%BC%A0%E9%92%A7%E7%94%AF%E5%90%88%E5%BD%B1%23) `357.2K 🔥` `+210%`
1. [亚历山大绝杀掘金](https://s.weibo.com/weibo?q=%23%E4%BA%9A%E5%8E%86%E5%B1%B1%E5%A4%A7%E7%BB%9D%E6%9D%80%E6%8E%98%E9%87%91%23) `357.0K 🔥` `+200%`
1. [妈妈回应女儿用烧火棍在灶台作画](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%84%BF%E7%94%A8%E7%83%A7%E7%81%AB%E6%A3%8D%E5%9C%A8%E7%81%B6%E5%8F%B0%E4%BD%9C%E7%94%BB%23) `356.9K 🔥` `+326%`
1. [伊朗提出过霍尔木兹海峡条件 (Iran raises conditions over Strait of Hormuz)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%8F%90%E5%87%BA%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E6%9D%A1%E4%BB%B6%23) `356.8K 🔥` `+242%`
1. [6G网要来了 (6G network is coming)](https://s.weibo.com/weibo?q=%236G%E7%BD%91%E8%A6%81%E6%9D%A5%E4%BA%86%23) `1.1M 🔥`
1. [物业管理改服务住建部采纳了](https://s.weibo.com/weibo?q=%23%E7%89%A9%E4%B8%9A%E7%AE%A1%E7%90%86%E6%94%B9%E6%9C%8D%E5%8A%A1%E4%BD%8F%E5%BB%BA%E9%83%A8%E9%87%87%E7%BA%B3%E4%BA%86%23) `375.5K 🔥` `-54%`

Updated at 2026-03-10 12:24:54

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
