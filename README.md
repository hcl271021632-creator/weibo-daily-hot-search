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

1. [千问 (Qianwen)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%97%AE%23) `1.1M 🔥` `NEW`
1. [村口小卖部里的全国人大代表](https://s.weibo.com/weibo?q=%23%E6%9D%91%E5%8F%A3%E5%B0%8F%E5%8D%96%E9%83%A8%E9%87%8C%E7%9A%84%E5%85%A8%E5%9B%BD%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%23) `259.2K 🔥` `NEW`
1. [政府工作报告中的民生热词](https://s.weibo.com/weibo?q=%23%E6%94%BF%E5%BA%9C%E5%B7%A5%E4%BD%9C%E6%8A%A5%E5%91%8A%E4%B8%AD%E7%9A%84%E6%B0%91%E7%94%9F%E7%83%AD%E8%AF%8D%23) `258.5K 🔥` `NEW`
1. [白敬亭又来找心动的offer了](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E5%8F%88%E6%9D%A5%E6%89%BE%E5%BF%83%E5%8A%A8%E7%9A%84offer%E4%BA%86%23) `171.1K 🔥` `NEW`
1. [男子吃火锅花113元发票抽奖中了10万](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%90%83%E7%81%AB%E9%94%85%E8%8A%B1113%E5%85%83%E5%8F%91%E7%A5%A8%E6%8A%BD%E5%A5%96%E4%B8%AD%E4%BA%8610%E4%B8%87%23) `166.5K 🔥` `NEW`
1. [得闲谨制最终票房4.12亿](https://s.weibo.com/weibo?q=%23%E5%BE%97%E9%97%B2%E8%B0%A8%E5%88%B6%E6%9C%80%E7%BB%88%E7%A5%A8%E6%88%BF4.12%E4%BA%BF%23) `133.4K 🔥` `NEW`
1. [张维伊救的不是董璇是房主任](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E7%BB%B4%E4%BC%8A%E6%95%91%E7%9A%84%E4%B8%8D%E6%98%AF%E8%91%A3%E7%92%87%E6%98%AF%E6%88%BF%E4%B8%BB%E4%BB%BB%23) `83.2K 🔥` `NEW`
1. [朱桢悼念嫩娘](https://s.weibo.com/weibo?q=%23%E6%9C%B1%E6%A1%A2%E6%82%BC%E5%BF%B5%E5%AB%A9%E5%A8%98%23) `80.2K 🔥` `NEW`
1. [妈妈给一年级萌娃的每页书角贴透明胶](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E7%BB%99%E4%B8%80%E5%B9%B4%E7%BA%A7%E8%90%8C%E5%A8%83%E7%9A%84%E6%AF%8F%E9%A1%B5%E4%B9%A6%E8%A7%92%E8%B4%B4%E9%80%8F%E6%98%8E%E8%83%B6%23) `66.0K 🔥` `NEW`
1. [十日终焉](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%23) `65.2K 🔥` `NEW`
1. [戚薇王鸥你俩一起过刚刚好 (Qi Wei, Wang Ou, it’s just right for you two to spend time together)](https://s.weibo.com/weibo?q=%23%E6%88%9A%E8%96%87%E7%8E%8B%E9%B8%A5%E4%BD%A0%E4%BF%A9%E4%B8%80%E8%B5%B7%E8%BF%87%E5%88%9A%E5%88%9A%E5%A5%BD%23) `63.9K 🔥` `NEW`
1. [逐玉 智能倍速看剧](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E6%99%BA%E8%83%BD%E5%80%8D%E9%80%9F%E7%9C%8B%E5%89%A7%23) `258.3K 🔥` `+214%`
1. [十年前卖衣服方式](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%B9%B4%E5%89%8D%E5%8D%96%E8%A1%A3%E6%9C%8D%E6%96%B9%E5%BC%8F%23) `242.7K 🔥` `+73%`
1. [不要热水洗头时梳头发](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%A6%81%E7%83%AD%E6%B0%B4%E6%B4%97%E5%A4%B4%E6%97%B6%E6%A2%B3%E5%A4%B4%E5%8F%91%23) `210.6K 🔥` `+59%`
1. [田曦薇能演杀猪女李雪琴早有预言](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E8%83%BD%E6%BC%94%E6%9D%80%E7%8C%AA%E5%A5%B3%E6%9D%8E%E9%9B%AA%E7%90%B4%E6%97%A9%E6%9C%89%E9%A2%84%E8%A8%80%23) `111.8K 🔥` `+25%`
1. [十五五规划109项重大工程项目一览](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E8%A7%84%E5%88%92109%E9%A1%B9%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%E9%A1%B9%E7%9B%AE%E4%B8%80%E8%A7%88%23) `642.3K 🔥`
1. [伊朗军队誓为遭击沉军舰复仇](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%9B%E9%98%9F%E8%AA%93%E4%B8%BA%E9%81%AD%E5%87%BB%E6%B2%89%E5%86%9B%E8%88%B0%E5%A4%8D%E4%BB%87%23) `286.8K 🔥`
1. [外国朋友以为中国也是一人一道菜](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%9B%BD%E6%9C%8B%E5%8F%8B%E4%BB%A5%E4%B8%BA%E4%B8%AD%E5%9B%BD%E4%B9%9F%E6%98%AF%E4%B8%80%E4%BA%BA%E4%B8%80%E9%81%93%E8%8F%9C%23) `268.6K 🔥`
1. [死了么APP创始人被原公司劝离职](https://s.weibo.com/weibo?q=%23%E6%AD%BB%E4%BA%86%E4%B9%88APP%E5%88%9B%E5%A7%8B%E4%BA%BA%E8%A2%AB%E5%8E%9F%E5%85%AC%E5%8F%B8%E5%8A%9D%E7%A6%BB%E8%81%8C%23) `257.2K 🔥`
1. [女子产后21天突发大出血晕倒车库](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%BA%A7%E5%90%8E21%E5%A4%A9%E7%AA%81%E5%8F%91%E5%A4%A7%E5%87%BA%E8%A1%80%E6%99%95%E5%80%92%E8%BD%A6%E5%BA%93%23) `252.2K 🔥`
1. [老舅妈嫩娘去世 (My old aunt and young lady passed away)](https://s.weibo.com/weibo?q=%23%E8%80%81%E8%88%85%E5%A6%88%E5%AB%A9%E5%A8%98%E5%8E%BB%E4%B8%96%23) `248.3K 🔥`
1. [曝现在就出发4金晨被替换了 (It is revealed that Jin Chen has been replaced in Let’s Go Now 4)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%B0%E5%9C%A8%E5%B0%B1%E5%87%BA%E5%8F%914%E9%87%91%E6%99%A8%E8%A2%AB%E6%9B%BF%E6%8D%A2%E4%BA%86%23) `180.8K 🔥`
1. [舒适正当夏 (Comfortable in summer)](https://s.weibo.com/weibo?q=%23%E8%88%92%E9%80%82%E6%AD%A3%E5%BD%93%E5%A4%8F%23) `168.7K 🔥`
1. [谭松韵新剧气血十足老辈子来的](https://s.weibo.com/weibo?q=%23%E8%B0%AD%E6%9D%BE%E9%9F%B5%E6%96%B0%E5%89%A7%E6%B0%94%E8%A1%80%E5%8D%81%E8%B6%B3%E8%80%81%E8%BE%88%E5%AD%90%E6%9D%A5%E7%9A%84%23) `153.9K 🔥`
1. [伊朗向美以发动第20波袭击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%91%E7%BE%8E%E4%BB%A5%E5%8F%91%E5%8A%A8%E7%AC%AC20%E6%B3%A2%E8%A2%AD%E5%87%BB%23) `129.6K 🔥`
1. [重案六组 (Serious Case Group Six)](https://s.weibo.com/weibo?q=%23%E9%87%8D%E6%A1%88%E5%85%AD%E7%BB%84%23) `127.5K 🔥`
1. [刘昊然宋祖儿 你透过我的眼睛在看谁](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%98%8A%E7%84%B6%E5%AE%8B%E7%A5%96%E5%84%BF%20%E4%BD%A0%E9%80%8F%E8%BF%87%E6%88%91%E7%9A%84%E7%9C%BC%E7%9D%9B%E5%9C%A8%E7%9C%8B%E8%B0%81%23) `125.0K 🔥`
1. [知道会动的冰箱贴受众是谁了](https://s.weibo.com/weibo?q=%23%E7%9F%A5%E9%81%93%E4%BC%9A%E5%8A%A8%E7%9A%84%E5%86%B0%E7%AE%B1%E8%B4%B4%E5%8F%97%E4%BC%97%E6%98%AF%E8%B0%81%E4%BA%86%23) `123.5K 🔥`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `123.4K 🔥`
1. [王安宇巴黎时装周出图](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E5%87%BA%E5%9B%BE%23) `112.0K 🔥`
1. [凤舞九天](https://s.weibo.com/weibo?q=%23%E5%87%A4%E8%88%9E%E4%B9%9D%E5%A4%A9%23) `109.1K 🔥`
1. [二十多年内娱只有这一个拿得出手的女警](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E5%8D%81%E5%A4%9A%E5%B9%B4%E5%86%85%E5%A8%B1%E5%8F%AA%E6%9C%89%E8%BF%99%E4%B8%80%E4%B8%AA%E6%8B%BF%E5%BE%97%E5%87%BA%E6%89%8B%E7%9A%84%E5%A5%B3%E8%AD%A6%23) `108.4K 🔥`
1. [詹姆斯生涯进球数历史第一](https://s.weibo.com/weibo?q=%23%E8%A9%B9%E5%A7%86%E6%96%AF%E7%94%9F%E6%B6%AF%E8%BF%9B%E7%90%83%E6%95%B0%E5%8E%86%E5%8F%B2%E7%AC%AC%E4%B8%80%23) `87.5K 🔥`
1. [据报初步评估显示美军袭击伊朗学校 (Preliminary assessment reportedly shows U.S. forces attacking Iranian schools)](https://s.weibo.com/weibo?q=%23%E6%8D%AE%E6%8A%A5%E5%88%9D%E6%AD%A5%E8%AF%84%E4%BC%B0%E6%98%BE%E7%A4%BA%E7%BE%8E%E5%86%9B%E8%A2%AD%E5%87%BB%E4%BC%8A%E6%9C%97%E5%AD%A6%E6%A0%A1%23) `82.5K 🔥`
1. [多地官宣春假清明连休6天 (Officials in many places announced that the Spring Festival will be closed for 6 consecutive days during Qingming Festival)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E5%AE%98%E5%AE%A3%E6%98%A5%E5%81%87%E6%B8%85%E6%98%8E%E8%BF%9E%E4%BC%916%E5%A4%A9%23) `766.6K 🔥` `-29%`
1. [比亚迪闪充5分好9分饱3分寒 (BYD flash charge: 5 points good, 9 points full, 3 points cold)](https://s.weibo.com/weibo?q=%23%E6%AF%94%E4%BA%9A%E8%BF%AA%E9%97%AA%E5%85%855%E5%88%86%E5%A5%BD9%E5%88%86%E9%A5%B13%E5%88%86%E5%AF%92%23) `424.5K 🔥` `-44%`
1. [被骂了千年的小动物们该翻身了 (It’s time for the little animals who have been scolded for thousands of years to turn around.)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E9%AA%82%E4%BA%86%E5%8D%83%E5%B9%B4%E7%9A%84%E5%B0%8F%E5%8A%A8%E7%89%A9%E4%BB%AC%E8%AF%A5%E7%BF%BB%E8%BA%AB%E4%BA%86%23) `307.2K 🔥` `-60%`
1. [霸王茶姬免单 (Overlord Cha Ji free order)](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%85%8D%E5%8D%95%23) `293.0K 🔥` `-23%`
1. [柳州辟谣本地女子出轨同事感染HIV](https://s.weibo.com/weibo?q=%23%E6%9F%B3%E5%B7%9E%E8%BE%9F%E8%B0%A3%E6%9C%AC%E5%9C%B0%E5%A5%B3%E5%AD%90%E5%87%BA%E8%BD%A8%E5%90%8C%E4%BA%8B%E6%84%9F%E6%9F%93HIV%23) `276.5K 🔥` `-55%`
1. [伊朗外长拒绝与美国谈判](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%96%E9%95%BF%E6%8B%92%E7%BB%9D%E4%B8%8E%E7%BE%8E%E5%9B%BD%E8%B0%88%E5%88%A4%23) `181.9K 🔥` `-30%`
1. [委内瑞拉决定同美国恢复外交关系](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E5%86%B3%E5%AE%9A%E5%90%8C%E7%BE%8E%E5%9B%BD%E6%81%A2%E5%A4%8D%E5%A4%96%E4%BA%A4%E5%85%B3%E7%B3%BB%23) `160.4K 🔥` `-29%`
1. [美国24州联合起诉特朗普政府](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD24%E5%B7%9E%E8%81%94%E5%90%88%E8%B5%B7%E8%AF%89%E7%89%B9%E6%9C%97%E6%99%AE%E6%94%BF%E5%BA%9C%23) `114.3K 🔥` `-42%`
1. [你的肉松肉紧](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E7%9A%84%E8%82%89%E6%9D%BE%E8%82%89%E7%B4%A7%23) `109.2K 🔥` `-33%`
1. [女生800元买猫被传染全身长猫藓](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F800%E5%85%83%E4%B9%B0%E7%8C%AB%E8%A2%AB%E4%BC%A0%E6%9F%93%E5%85%A8%E8%BA%AB%E9%95%BF%E7%8C%AB%E8%97%93%23) `86.5K 🔥` `-39%`
1. [建议别让家长替学校站岗](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%88%AB%E8%AE%A9%E5%AE%B6%E9%95%BF%E6%9B%BF%E5%AD%A6%E6%A0%A1%E7%AB%99%E5%B2%97%23) `82.4K 🔥` `-71%`
1. [刘国梁高度肯定樊振东](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%9B%BD%E6%A2%81%E9%AB%98%E5%BA%A6%E8%82%AF%E5%AE%9A%E6%A8%8A%E6%8C%AF%E4%B8%9C%23) `80.9K 🔥` `-57%`
1. [十日终焉纯大男主群像](https://s.weibo.com/weibo?q=%23%E5%8D%81%E6%97%A5%E7%BB%88%E7%84%89%E7%BA%AF%E5%A4%A7%E7%94%B7%E4%B8%BB%E7%BE%A4%E5%83%8F%23) `80.6K 🔥` `-31%`
1. [建议三年级前学生课间延长至30分钟 (It is recommended that the recess for students before third grade be extended to 30 minutes)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E4%B8%89%E5%B9%B4%E7%BA%A7%E5%89%8D%E5%AD%A6%E7%94%9F%E8%AF%BE%E9%97%B4%E5%BB%B6%E9%95%BF%E8%87%B330%E5%88%86%E9%92%9F%23) `80.3K 🔥` `-32%`
1. [原来四个小时能干这么多事](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%9B%9B%E4%B8%AA%E5%B0%8F%E6%97%B6%E8%83%BD%E5%B9%B2%E8%BF%99%E4%B9%88%E5%A4%9A%E4%BA%8B%23) `71.6K 🔥` `-21%`
1. [逐玉追剧日历](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%BF%BD%E5%89%A7%E6%97%A5%E5%8E%86%23) `69.9K 🔥` `-28%`
1. [原神](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E7%A5%9E%23) `68.1K 🔥` `-46%`

Updated at 2026-03-06 14:08:02

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
