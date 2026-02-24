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

1. [谷爱凌或考虑进入其他行业 (Gu Ailing may consider entering other industries)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%88%96%E8%80%83%E8%99%91%E8%BF%9B%E5%85%A5%E5%85%B6%E4%BB%96%E8%A1%8C%E4%B8%9A%23) `318.1K 🔥` `NEW`
1. [开工大吉](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E5%A4%A7%E5%90%89%23) `145.4K 🔥` `NEW`
1. [A股马年开市](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E9%A9%AC%E5%B9%B4%E5%BC%80%E5%B8%82%23) `86.7K 🔥` `NEW`
1. [墨西哥27名安全人员死亡](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A527%E5%90%8D%E5%AE%89%E5%85%A8%E4%BA%BA%E5%91%98%E6%AD%BB%E4%BA%A1%23) `83.0K 🔥` `NEW`
1. [突然理解第三次分配的重要性](https://s.weibo.com/weibo?q=%23%E7%AA%81%E7%84%B6%E7%90%86%E8%A7%A3%E7%AC%AC%E4%B8%89%E6%AC%A1%E5%88%86%E9%85%8D%E7%9A%84%E9%87%8D%E8%A6%81%E6%80%A7%23) `74.2K 🔥` `NEW`
1. [国产人形机器人企业排名](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%BA%A7%E4%BA%BA%E5%BD%A2%E6%9C%BA%E5%99%A8%E4%BA%BA%E4%BC%81%E4%B8%9A%E6%8E%92%E5%90%8D%23) `64.1K 🔥` `NEW`
1. [宋亚轩晒照祝丁程鑫程鑫如意](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BA%9A%E8%BD%A9%E6%99%92%E7%85%A7%E7%A5%9D%E4%B8%81%E7%A8%8B%E9%91%AB%E7%A8%8B%E9%91%AB%E5%A6%82%E6%84%8F%23) `62.2K 🔥` `NEW`
1. [美考虑初步打击伊朗](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%80%83%E8%99%91%E5%88%9D%E6%AD%A5%E6%89%93%E5%87%BB%E4%BC%8A%E6%9C%97%23) `60.7K 🔥` `NEW`
1. [捡到了两只一模一样的小狗](https://s.weibo.com/weibo?q=%23%E6%8D%A1%E5%88%B0%E4%BA%86%E4%B8%A4%E5%8F%AA%E4%B8%80%E6%A8%A1%E4%B8%80%E6%A0%B7%E7%9A%84%E5%B0%8F%E7%8B%97%23) `60.6K 🔥` `NEW`
1. [陈凯文 双眼皮](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%87%AF%E6%96%87%20%E5%8F%8C%E7%9C%BC%E7%9A%AE%23) `49.4K 🔥` `NEW`
1. [曼联战胜埃弗顿 (Manchester United beat Everton)](https://s.weibo.com/weibo?q=%23%E6%9B%BC%E8%81%94%E6%88%98%E8%83%9C%E5%9F%83%E5%BC%97%E9%A1%BF%23) `44.3K 🔥` `NEW`
1. [夜王 尺度 (night king scale)](https://s.weibo.com/weibo?q=%23%E5%A4%9C%E7%8E%8B%20%E5%B0%BA%E5%BA%A6%23) `335.6K 🔥` `+25%`
1. [考研出分时间 (Postgraduate entrance examination score time)](https://s.weibo.com/weibo?q=%23%E8%80%83%E7%A0%94%E5%87%BA%E5%88%86%E6%97%B6%E9%97%B4%23) `298.4K 🔥` `+139%`
1. [高速堵车大聪明选择下国道绕行](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%A0%B5%E8%BD%A6%E5%A4%A7%E8%81%AA%E6%98%8E%E9%80%89%E6%8B%A9%E4%B8%8B%E5%9B%BD%E9%81%93%E7%BB%95%E8%A1%8C%23) `222.1K 🔥` `+215%`
1. [高速](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%23) `210.6K 🔥` `+347%`
1. [伊朗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%23) `209.3K 🔥` `+89%`
1. [吴佳尼自曝订婚后才知马景涛年龄](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%B3%E5%B0%BC%E8%87%AA%E6%9B%9D%E8%AE%A2%E5%A9%9A%E5%90%8E%E6%89%8D%E7%9F%A5%E9%A9%AC%E6%99%AF%E6%B6%9B%E5%B9%B4%E9%BE%84%23) `207.5K 🔥` `+91%`
1. [刘耀文 (Liu Yaowen)](https://s.weibo.com/weibo?q=%23%E5%88%98%E8%80%80%E6%96%87%23) `153.0K 🔥` `+42%`
1. [史上最贵iPhone要来了 (The most expensive iPhone in history is coming)](https://s.weibo.com/weibo?q=%23%E5%8F%B2%E4%B8%8A%E6%9C%80%E8%B4%B5iPhone%E8%A6%81%E6%9D%A5%E4%BA%86%23) `153.0K 🔥` `+43%`
1. [西湖里捞起财物累计价值超600万 (The cumulative value of property found in West Lake exceeds 6 million)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E6%B9%96%E9%87%8C%E6%8D%9E%E8%B5%B7%E8%B4%A2%E7%89%A9%E7%B4%AF%E8%AE%A1%E4%BB%B7%E5%80%BC%E8%B6%85600%E4%B8%87%23) `137.1K 🔥` `+31%`
1. [免费时段即将结束仍在高速怎么办 (What should I do if the free period is about to end and I’m still on the expressway?)](https://s.weibo.com/weibo?q=%23%E5%85%8D%E8%B4%B9%E6%97%B6%E6%AE%B5%E5%8D%B3%E5%B0%86%E7%BB%93%E6%9D%9F%E4%BB%8D%E5%9C%A8%E9%AB%98%E9%80%9F%E6%80%8E%E4%B9%88%E5%8A%9E%23) `110.8K 🔥` `+58%`
1. [宋亚轩 (Song Yaxuan)](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E4%BA%9A%E8%BD%A9%23) `110.7K 🔥` `+57%`
1. [鞠婧祎珍珠腰链](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E7%8F%8D%E7%8F%A0%E8%85%B0%E9%93%BE%23) `110.5K 🔥` `+57%`
1. [黄景瑜回复贾乃亮](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%AF%E7%91%9C%E5%9B%9E%E5%A4%8D%E8%B4%BE%E4%B9%83%E4%BA%AE%23) `105.0K 🔥` `+70%`
1. [方家翊自曝和家人划清界限](https://s.weibo.com/weibo?q=%23%E6%96%B9%E5%AE%B6%E7%BF%8A%E8%87%AA%E6%9B%9D%E5%92%8C%E5%AE%B6%E4%BA%BA%E5%88%92%E6%B8%85%E7%95%8C%E9%99%90%23) `102.0K 🔥` `+33%`
1. [镖人票房](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%23) `86.6K 🔥` `+21%`
1. [能谈到结婚的伴侣是什么样的 (What does it look like to have a partner who can talk about marriage?)](https://s.weibo.com/weibo?q=%23%E8%83%BD%E8%B0%88%E5%88%B0%E7%BB%93%E5%A9%9A%E7%9A%84%E4%BC%B4%E4%BE%A3%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%23) `84.8K 🔥` `+21%`
1. [BLACKPINK新歌GOmv预告](https://s.weibo.com/weibo?q=%23BLACKPINK%E6%96%B0%E6%AD%8CGOmv%E9%A2%84%E5%91%8A%23) `75.1K 🔥` `+30%`
1. [电视台通报游客采访口音质疑 (The TV station reports that tourists are questioning their accent during interviews)](https://s.weibo.com/weibo?q=%23%E7%94%B5%E8%A7%86%E5%8F%B0%E9%80%9A%E6%8A%A5%E6%B8%B8%E5%AE%A2%E9%87%87%E8%AE%BF%E5%8F%A3%E9%9F%B3%E8%B4%A8%E7%96%91%23) `54.2K 🔥` `+28%`
1. [瘦了后出片像呼吸一样简单 (After losing weight, making movies is as easy as breathing)](https://s.weibo.com/weibo?q=%23%E7%98%A6%E4%BA%86%E5%90%8E%E5%87%BA%E7%89%87%E5%83%8F%E5%91%BC%E5%90%B8%E4%B8%80%E6%A0%B7%E7%AE%80%E5%8D%95%23) `53.0K 🔥` `+21%`
1. [夜王 (night king)](https://s.weibo.com/weibo?q=%23%E5%A4%9C%E7%8E%8B%23) `51.8K 🔥` `+21%`
1. [误转69万公款对方拒绝退款 (The other party refused to refund 690,000 public funds mistakenly)](https://s.weibo.com/weibo?q=%23%E8%AF%AF%E8%BD%AC69%E4%B8%87%E5%85%AC%E6%AC%BE%E5%AF%B9%E6%96%B9%E6%8B%92%E7%BB%9D%E9%80%80%E6%AC%BE%23) `1.1M 🔥`
1. [墨西哥毒枭身亡事件华人发声 (Chinese speak out on Mexican drug lord's death)](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A5%E6%AF%92%E6%9E%AD%E8%BA%AB%E4%BA%A1%E4%BA%8B%E4%BB%B6%E5%8D%8E%E4%BA%BA%E5%8F%91%E5%A3%B0%23) `789.4K 🔥`
1. [在全党开展树立和践行正确政绩观学习教育](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E5%85%A8%E5%85%9A%E5%BC%80%E5%B1%95%E6%A0%91%E7%AB%8B%E5%92%8C%E8%B7%B5%E8%A1%8C%E6%AD%A3%E7%A1%AE%E6%94%BF%E7%BB%A9%E8%A7%82%E5%AD%A6%E4%B9%A0%E6%95%99%E8%82%B2%23) `627.6K 🔥`
1. [上班 (work)](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%AD%23) `251.9K 🔥`
1. [原来全麻手术不是睡着了 (It turns out that I didn’t fall asleep during the general anesthesia surgery.)](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%85%A8%E9%BA%BB%E6%89%8B%E6%9C%AF%E4%B8%8D%E6%98%AF%E7%9D%A1%E7%9D%80%E4%BA%86%23) `221.5K 🔥`
1. [徐梦桃拆台说并不享受做家务](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E6%8B%86%E5%8F%B0%E8%AF%B4%E5%B9%B6%E4%B8%8D%E4%BA%AB%E5%8F%97%E5%81%9A%E5%AE%B6%E5%8A%A1%23) `146.3K 🔥`
1. [孙颖莎7比11帕拉南 (Sun Yingsha 7 to 11 Paranan)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E7%E6%AF%9411%E5%B8%95%E6%8B%89%E5%8D%97%23) `128.4K 🔥`
1. [丁程鑫 (Ding Chengxin)](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%23) `122.3K 🔥`
1. [不让江山剧组声明 (Don't let Jiangshan crew make a statement)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%89%A7%E7%BB%84%E5%A3%B0%E6%98%8E%23) `119.6K 🔥`
1. [夫妻春节不回家送外卖1个月赚4万 (Couple makes 40,000 yuan in one month by delivering food without going home during Spring Festival)](https://s.weibo.com/weibo?q=%23%E5%A4%AB%E5%A6%BB%E6%98%A5%E8%8A%82%E4%B8%8D%E5%9B%9E%E5%AE%B6%E9%80%81%E5%A4%96%E5%8D%961%E4%B8%AA%E6%9C%88%E8%B5%9A4%E4%B8%87%23) `110.4K 🔥`
1. [鸟中刘亦菲也扛不了后置镜头怼脸拍 (Even Liu Yifei, the best among birds, can’t bear the rear camera and slaps her in the face)](https://s.weibo.com/weibo?q=%23%E9%B8%9F%E4%B8%AD%E5%88%98%E4%BA%A6%E8%8F%B2%E4%B9%9F%E6%89%9B%E4%B8%8D%E4%BA%86%E5%90%8E%E7%BD%AE%E9%95%9C%E5%A4%B4%E6%80%BC%E8%84%B8%E6%8B%8D%23) `83.2K 🔥`
1. [人民日报专访教练李琰 (People's Daily interviews coach Li Yan)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E6%B0%91%E6%97%A5%E6%8A%A5%E4%B8%93%E8%AE%BF%E6%95%99%E7%BB%83%E6%9D%8E%E7%90%B0%23) `68.0K 🔥`
1. [刘宇宁新剧教科书级暧昧避嫌](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E6%96%B0%E5%89%A7%E6%95%99%E7%A7%91%E4%B9%A6%E7%BA%A7%E6%9A%A7%E6%98%A7%E9%81%BF%E5%AB%8C%23) `61.2K 🔥`
1. [三亚偶遇章子怡一家 (Encountering Zhang Ziyi’s family in Sanya)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E5%81%B6%E9%81%87%E7%AB%A0%E5%AD%90%E6%80%A1%E4%B8%80%E5%AE%B6%23) `54.6K 🔥`
1. [女子情绪失控欲跳桥丈夫狂奔阻拦 (A woman loses control and wants to jump off a bridge, but her husband rushes to stop her)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%83%85%E7%BB%AA%E5%A4%B1%E6%8E%A7%E6%AC%B2%E8%B7%B3%E6%A1%A5%E4%B8%88%E5%A4%AB%E7%8B%82%E5%A5%94%E9%98%BB%E6%8B%A6%23) `54.3K 🔥`
1. [没想到卫生间也能跳大跳台 (I didn’t expect that the bathroom could also be used for jumping on the big platform.)](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E6%83%B3%E5%88%B0%E5%8D%AB%E7%94%9F%E9%97%B4%E4%B9%9F%E8%83%BD%E8%B7%B3%E5%A4%A7%E8%B7%B3%E5%8F%B0%23) `54.2K 🔥`
1. [歌手徐浩宣布干团播](https://s.weibo.com/weibo?q=%23%E6%AD%8C%E6%89%8B%E5%BE%90%E6%B5%A9%E5%AE%A3%E5%B8%83%E5%B9%B2%E5%9B%A2%E6%92%AD%23) `49.8K 🔥`
1. [孩子把摔炮当糖果入口后爆炸 (Child eats cannon after eating it as candy)](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E6%8A%8A%E6%91%94%E7%82%AE%E5%BD%93%E7%B3%96%E6%9E%9C%E5%85%A5%E5%8F%A3%E5%90%8E%E7%88%86%E7%82%B8%23) `49.4K 🔥`
1. [时代少年团](https://s.weibo.com/weibo?q=%23%E6%97%B6%E4%BB%A3%E5%B0%91%E5%B9%B4%E5%9B%A2%23) `48.6K 🔥`

Updated at 2026-02-24 08:02:01

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
