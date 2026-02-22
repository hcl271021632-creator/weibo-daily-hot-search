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

1. [谷爱凌U型场地决赛或取消 (Gu Ailing’s U-shaped field final may be cancelled)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8CU%E5%9E%8B%E5%9C%BA%E5%9C%B0%E5%86%B3%E8%B5%9B%E6%88%96%E5%8F%96%E6%B6%88%23) `1.1M 🔥` `NEW`
1. [女生被催婚6岁侄子帮忙反击](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%94%9F%E8%A2%AB%E5%82%AC%E5%A9%9A6%E5%B2%81%E4%BE%84%E5%AD%90%E5%B8%AE%E5%BF%99%E5%8F%8D%E5%87%BB%23) `834.5K 🔥` `NEW`
1. [谢景行原型是胡歌](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E6%99%AF%E8%A1%8C%E5%8E%9F%E5%9E%8B%E6%98%AF%E8%83%A1%E6%AD%8C%23) `550.9K 🔥` `NEW`
1. [沈妙原型 王艳](https://s.weibo.com/weibo?q=%23%E6%B2%88%E5%A6%99%E5%8E%9F%E5%9E%8B%20%E7%8E%8B%E8%89%B3%23) `443.0K 🔥` `NEW`
1. [突然意识到经常习惯性霸凌自己](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E6%84%8F%E8%AF%86%E5%88%B0%E7%BB%8F%E5%B8%B8%E4%B9%A0%E6%83%AF%E6%80%A7%E9%9C%B8%E5%87%8C%E8%87%AA%E5%B7%B1%23) `346.6K 🔥` `NEW`
1. [杨洋周洁琼不让江山开机同框](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%91%A8%E6%B4%81%E7%90%BC%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%BC%80%E6%9C%BA%E5%90%8C%E6%A1%86%23) `338.7K 🔥` `NEW`
1. [75岁钓帝黑大爷去世](https://s.weibo.com/weibo?q=%2375%E5%B2%81%E9%92%93%E5%B8%9D%E9%BB%91%E5%A4%A7%E7%88%B7%E5%8E%BB%E4%B8%96%23) `292.4K 🔥` `NEW`
1. [这才是我想要的将门毒后](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%89%8D%E6%98%AF%E6%88%91%E6%83%B3%E8%A6%81%E7%9A%84%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%23) `226.4K 🔥` `NEW`
1. [撒娇时没控制好力度的小狗](https://s.weibo.com/weibo?q=%23%E6%92%92%E5%A8%87%E6%97%B6%E6%B2%A1%E6%8E%A7%E5%88%B6%E5%A5%BD%E5%8A%9B%E5%BA%A6%E7%9A%84%E5%B0%8F%E7%8B%97%23) `191.4K 🔥` `NEW`
1. [贝加尔湖事故8人身份全部确认](https://s.weibo.com/weibo?q=%23%E8%B4%9D%E5%8A%A0%E5%B0%94%E6%B9%96%E4%BA%8B%E6%95%858%E4%BA%BA%E8%BA%AB%E4%BB%BD%E5%85%A8%E9%83%A8%E7%A1%AE%E8%AE%A4%23) `177.3K 🔥` `NEW`
1. [山西文旅局回应出租打折却要司机贴钱 (Shanxi Culture and Tourism Bureau responded to rental discounts but asked drivers to pay)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E8%A5%BF%E6%96%87%E6%97%85%E5%B1%80%E5%9B%9E%E5%BA%94%E5%87%BA%E7%A7%9F%E6%89%93%E6%8A%98%E5%8D%B4%E8%A6%81%E5%8F%B8%E6%9C%BA%E8%B4%B4%E9%92%B1%23) `162.0K 🔥` `NEW`
1. [王鹤棣宋茜恳求观众多给一些机会](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AE%8B%E8%8C%9C%E6%81%B3%E6%B1%82%E8%A7%82%E4%BC%97%E5%A4%9A%E7%BB%99%E4%B8%80%E4%BA%9B%E6%9C%BA%E4%BC%9A%23) `159.8K 🔥` `NEW`
1. [李昀锐当上宋雨琦站哥了](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%80%E9%94%90%E5%BD%93%E4%B8%8A%E5%AE%8B%E9%9B%A8%E7%90%A6%E7%AB%99%E5%93%A5%E4%BA%86%23) `158.2K 🔥` `NEW`
1. [五台山明火已被扑灭](https://s.weibo.com/weibo?q=%23%E4%BA%94%E5%8F%B0%E5%B1%B1%E6%98%8E%E7%81%AB%E5%B7%B2%E8%A2%AB%E6%89%91%E7%81%AD%23) `152.7K 🔥` `NEW`
1. [若决赛取消谷爱凌将无缘奖牌](https://s.weibo.com/weibo?q=%23%E8%8B%A5%E5%86%B3%E8%B5%9B%E5%8F%96%E6%B6%88%E8%B0%B7%E7%88%B1%E5%87%8C%E5%B0%86%E6%97%A0%E7%BC%98%E5%A5%96%E7%89%8C%23) `125.2K 🔥` `NEW`
1. [单届冬奥会6金](https://s.weibo.com/weibo?q=%23%E5%8D%95%E5%B1%8A%E5%86%AC%E5%A5%A5%E4%BC%9A6%E9%87%91%23) `124.9K 🔥` `NEW`
1. [小伙撞毁刚还清车贷的宝马微笑合影](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E6%92%9E%E6%AF%81%E5%88%9A%E8%BF%98%E6%B8%85%E8%BD%A6%E8%B4%B7%E7%9A%84%E5%AE%9D%E9%A9%AC%E5%BE%AE%E7%AC%91%E5%90%88%E5%BD%B1%23) `124.2K 🔥` `NEW`
1. [小伙刚还清车贷宝马几乎撞报废](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E5%88%9A%E8%BF%98%E6%B8%85%E8%BD%A6%E8%B4%B7%E5%AE%9D%E9%A9%AC%E5%87%A0%E4%B9%8E%E6%92%9E%E6%8A%A5%E5%BA%9F%23) `122.6K 🔥` `NEW`
1. [时代少年团演唱会](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%E6%BC%94%E5%94%B1%E4%BC%9A%23) `121.7K 🔥` `NEW`
1. [镖人口碑升至第一](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E5%8F%A3%E7%A2%91%E5%8D%87%E8%87%B3%E7%AC%AC%E4%B8%80%23) `120.7K 🔥` `NEW`
1. [父亲屋外透气偶遇儿子坠楼接住 (Father accidentally caught his son after he fell from the building outside his house to get some air.)](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E5%B1%8B%E5%A4%96%E9%80%8F%E6%B0%94%E5%81%B6%E9%81%87%E5%84%BF%E5%AD%90%E5%9D%A0%E6%A5%BC%E6%8E%A5%E4%BD%8F%23) `120.1K 🔥` `NEW`
1. [将门毒后用程少商的个人曲](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%E7%94%A8%E7%A8%8B%E5%B0%91%E5%95%86%E7%9A%84%E4%B8%AA%E4%BA%BA%E6%9B%B2%23) `119.3K 🔥` `NEW`
1. [怕朋友过得苦又怕朋友开路虎](https://s.weibo.com/weibo?q=%23%E6%80%95%E6%9C%8B%E5%8F%8B%E8%BF%87%E5%BE%97%E8%8B%A6%E5%8F%88%E6%80%95%E6%9C%8B%E5%8F%8B%E5%BC%80%E8%B7%AF%E8%99%8E%23) `118.2K 🔥` `NEW`
1. [杨洋手部骨折](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E6%89%8B%E9%83%A8%E9%AA%A8%E6%8A%98%23) `106.0K 🔥` `NEW`
1. [初六](https://s.weibo.com/weibo?q=%23%E5%88%9D%E5%85%AD%23) `104.0K 🔥` `NEW`
1. [刘梦章齐思钧交往约6年](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%A2%A6%E7%AB%A0%E9%BD%90%E6%80%9D%E9%92%A7%E4%BA%A4%E5%BE%80%E7%BA%A66%E5%B9%B4%23) `103.8K 🔥` `NEW`
1. [白鹿晒跑男团gidle合照](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E6%99%92%E8%B7%91%E7%94%B7%E5%9B%A2gidle%E5%90%88%E7%85%A7%23) `102.4K 🔥` `NEW`
1. [决赛推迟谷爱凌更新社媒](https://s.weibo.com/weibo?q=%23%E5%86%B3%E8%B5%9B%E6%8E%A8%E8%BF%9F%E8%B0%B7%E7%88%B1%E5%87%8C%E6%9B%B4%E6%96%B0%E7%A4%BE%E5%AA%92%23) `88.0K 🔥` `NEW`
1. [偶遇马嘉祺考驾照](https://s.weibo.com/weibo?q=%23%E5%81%B6%E9%81%87%E9%A9%AC%E5%98%89%E7%A5%BA%E8%80%83%E9%A9%BE%E7%85%A7%23) `86.0K 🔥` `NEW`
1. [小兔洗脸小兔摔倒](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%85%94%E6%B4%97%E8%84%B8%E5%B0%8F%E5%85%94%E6%91%94%E5%80%92%23) `83.8K 🔥` `NEW`
1. [星河入梦票房低迷仅是排片问题吗 (Is the sluggish box office performance of "Stars in the Sky" just a matter of film schedule?)](https://s.weibo.com/weibo?q=%23%E6%98%9F%E6%B2%B3%E5%85%A5%E6%A2%A6%E7%A5%A8%E6%88%BF%E4%BD%8E%E8%BF%B7%E4%BB%85%E6%98%AF%E6%8E%92%E7%89%87%E9%97%AE%E9%A2%98%E5%90%97%23) `83.7K 🔥` `NEW`
1. [杰伦格林双加时绝杀魔术](https://s.weibo.com/weibo?q=%23%E6%9D%B0%E4%BC%A6%E6%A0%BC%E6%9E%97%E5%8F%8C%E5%8A%A0%E6%97%B6%E7%BB%9D%E6%9D%80%E9%AD%94%E6%9C%AF%23) `66.6K 🔥` `NEW`
1. [小城良方](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%9F%8E%E8%89%AF%E6%96%B9%23) `65.9K 🔥` `NEW`
1. [宁忠岩直播晒三枚冬奥奖牌](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E7%9B%B4%E6%92%AD%E6%99%92%E4%B8%89%E6%9E%9A%E5%86%AC%E5%A5%A5%E5%A5%96%E7%89%8C%23) `64.7K 🔥` `NEW`
1. [泰国官方通报清迈72只老虎死亡](https://s.weibo.com/weibo?q=%23%E6%B3%B0%E5%9B%BD%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%E6%B8%85%E8%BF%8872%E5%8F%AA%E8%80%81%E8%99%8E%E6%AD%BB%E4%BA%A1%23) `64.2K 🔥` `NEW`
1. [十年后的恋爱关系](https://s.weibo.com/weibo?q=%23%E5%8D%81%E5%B9%B4%E5%90%8E%E7%9A%84%E6%81%8B%E7%88%B1%E5%85%B3%E7%B3%BB%23) `62.8K 🔥` `NEW`
1. [夜王](https://s.weibo.com/weibo?q=%23%E5%A4%9C%E7%8E%8B%23) `62.6K 🔥` `NEW`
1. [伊能静衣服吊牌没摘](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E8%83%BD%E9%9D%99%E8%A1%A3%E6%9C%8D%E5%90%8A%E7%89%8C%E6%B2%A1%E6%91%98%23) `172.0K 🔥` `+145%`
1. [齐思钧回应分手 (Qi Sijun responded to the breakup)](https://s.weibo.com/weibo?q=%23%E9%BD%90%E6%80%9D%E9%92%A7%E5%9B%9E%E5%BA%94%E5%88%86%E6%89%8B%23) `168.5K 🔥` `+59%`
1. [每天早睡1小时身体就不一样](https://s.weibo.com/weibo?q=%23%E6%AF%8F%E5%A4%A9%E6%97%A9%E7%9D%A11%E5%B0%8F%E6%97%B6%E8%BA%AB%E4%BD%93%E5%B0%B1%E4%B8%8D%E4%B8%80%E6%A0%B7%23) `117.4K 🔥` `+66%`
1. [娱乐圈恋爱就是一个巨大的县城文学](https://s.weibo.com/weibo?q=%23%E5%A8%B1%E4%B9%90%E5%9C%88%E6%81%8B%E7%88%B1%E5%B0%B1%E6%98%AF%E4%B8%80%E4%B8%AA%E5%B7%A8%E5%A4%A7%E7%9A%84%E5%8E%BF%E5%9F%8E%E6%96%87%E5%AD%A6%23) `116.9K 🔥` `+70%`
1. [热气腾腾的中国年 (Steamy Chinese New Year)](https://s.weibo.com/weibo?q=%23%E7%83%AD%E6%B0%94%E8%85%BE%E8%85%BE%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%B9%B4%23) `656.1K 🔥`
1. [将门独后分销红果 (The only queen in the family distributes red fruits)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%88%86%E9%94%80%E7%BA%A2%E6%9E%9C%23) `85.5K 🔥`
1. [苏翊鸣闭幕式旗手 (Su Yiming flag bearer at closing ceremony)](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E9%97%AD%E5%B9%95%E5%BC%8F%E6%97%97%E6%89%8B%23) `68.5K 🔥`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `66.2K 🔥`
1. [今年好几对情侣都分了 (Several couples have broken up this year)](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E5%A5%BD%E5%87%A0%E5%AF%B9%E6%83%85%E4%BE%A3%E9%83%BD%E5%88%86%E4%BA%86%23) `65.0K 🔥`
1. [前方无厕所无烤肠无茶叶蛋 (No toilet ahead, no sausages, no tea eggs)](https://s.weibo.com/weibo?q=%23%E5%89%8D%E6%96%B9%E6%97%A0%E5%8E%95%E6%89%80%E6%97%A0%E7%83%A4%E8%82%A0%E6%97%A0%E8%8C%B6%E5%8F%B6%E8%9B%8B%23) `79.6K 🔥` `-92%`
1. [美高官叫嚣27分钟接战台海 (Senior U.S. officials clamor for war over Taiwan in 27 minutes)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E9%AB%98%E5%AE%98%E5%8F%AB%E5%9A%A327%E5%88%86%E9%92%9F%E6%8E%A5%E6%88%98%E5%8F%B0%E6%B5%B7%23) `65.4K 🔥` `-74%`
1. [结婚五金起步价迈入10万元大关 (The starting price of wedding hardware has reached the 100,000 yuan mark)](https://s.weibo.com/weibo?q=%23%E7%BB%93%E5%A9%9A%E4%BA%94%E9%87%91%E8%B5%B7%E6%AD%A5%E4%BB%B7%E8%BF%88%E5%85%A510%E4%B8%87%E5%85%83%E5%A4%A7%E5%85%B3%23) `64.5K 🔥` `-28%`

Updated at 2026-02-22 11:12:49

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
