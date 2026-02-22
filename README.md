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

1. [大年初六迎来春节假期返程高峰 (The sixth day of the Lunar New Year ushered in the peak return period during the Spring Festival holiday)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E5%85%AD%E8%BF%8E%E6%9D%A5%E6%98%A5%E8%8A%82%E5%81%87%E6%9C%9F%E8%BF%94%E7%A8%8B%E9%AB%98%E5%B3%B0%23) `1.2M 🔥` `NEW`
1. [太原出现疫情系谣言](https://s.weibo.com/weibo?q=%23%E5%A4%AA%E5%8E%9F%E5%87%BA%E7%8E%B0%E7%96%AB%E6%83%85%E7%B3%BB%E8%B0%A3%E8%A8%80%23) `502.1K 🔥` `NEW`
1. [谷爱凌 九亿少女的梦](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%20%E4%B9%9D%E4%BA%BF%E5%B0%91%E5%A5%B3%E7%9A%84%E6%A2%A6%23) `443.6K 🔥` `NEW`
1. [谷爱凌唱国歌](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%94%B1%E5%9B%BD%E6%AD%8C%23) `418.3K 🔥` `NEW`
1. [谷爱凌金色蝴蝶结](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E9%87%91%E8%89%B2%E8%9D%B4%E8%9D%B6%E7%BB%93%23) `347.1K 🔥` `NEW`
1. [熊孩扔螺帽游客排队2小时无缘见花花](https://s.weibo.com/weibo?q=%23%E7%86%8A%E5%AD%A9%E6%89%94%E8%9E%BA%E5%B8%BD%E6%B8%B8%E5%AE%A2%E6%8E%92%E9%98%9F2%E5%B0%8F%E6%97%B6%E6%97%A0%E7%BC%98%E8%A7%81%E8%8A%B1%E8%8A%B1%23) `241.1K 🔥` `NEW`
1. [短道速滑](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E9%81%93%E9%80%9F%E6%BB%91%23) `240.2K 🔥` `NEW`
1. [五代物料](https://s.weibo.com/weibo?q=%23%E4%BA%94%E4%BB%A3%E7%89%A9%E6%96%99%23) `180.5K 🔥` `NEW`
1. [央视女解说看谷爱凌夺冠哽咽了](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E5%A5%B3%E8%A7%A3%E8%AF%B4%E7%9C%8B%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A4%BA%E5%86%A0%E5%93%BD%E5%92%BD%E4%BA%86%23) `130.9K 🔥` `NEW`
1. [DK让二追二T1](https://s.weibo.com/weibo?q=%23DK%E8%AE%A9%E4%BA%8C%E8%BF%BD%E4%BA%8CT1%23) `128.1K 🔥` `NEW`
1. [深圳高二数学偏才直通博士 (Shenzhen High School Mathematics Talents Directly Lead to PhD)](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E9%AB%98%E4%BA%8C%E6%95%B0%E5%AD%A6%E5%81%8F%E6%89%8D%E7%9B%B4%E9%80%9A%E5%8D%9A%E5%A3%AB%23) `91.6K 🔥` `NEW`
1. [拍照脸歪嘴斜大小脸是骨头长歪了](https://s.weibo.com/weibo?q=%23%E6%8B%8D%E7%85%A7%E8%84%B8%E6%AD%AA%E5%98%B4%E6%96%9C%E5%A4%A7%E5%B0%8F%E8%84%B8%E6%98%AF%E9%AA%A8%E5%A4%B4%E9%95%BF%E6%AD%AA%E4%BA%86%23) `83.9K 🔥` `NEW`
1. [日本一寺庙举行裸祭上万名男性参加](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E4%B8%80%E5%AF%BA%E5%BA%99%E4%B8%BE%E8%A1%8C%E8%A3%B8%E7%A5%AD%E4%B8%8A%E4%B8%87%E5%90%8D%E7%94%B7%E6%80%A7%E5%8F%82%E5%8A%A0%23) `82.4K 🔥` `NEW`
1. [秦始皇开公交车上还有李白对诗](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%A7%8B%E7%9A%87%E5%BC%80%E5%85%AC%E4%BA%A4%E8%BD%A6%E4%B8%8A%E8%BF%98%E6%9C%89%E6%9D%8E%E7%99%BD%E5%AF%B9%E8%AF%97%23) `75.6K 🔥` `NEW`
1. [小孩哥祝舅妈年年有男朋友笑翻全家](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A9%E5%93%A5%E7%A5%9D%E8%88%85%E5%A6%88%E5%B9%B4%E5%B9%B4%E6%9C%89%E7%94%B7%E6%9C%8B%E5%8F%8B%E7%AC%91%E7%BF%BB%E5%85%A8%E5%AE%B6%23) `75.0K 🔥` `NEW`
1. [网友给财政部留言求财运](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E7%BB%99%E8%B4%A2%E6%94%BF%E9%83%A8%E7%95%99%E8%A8%80%E6%B1%82%E8%B4%A2%E8%BF%90%23) `74.3K 🔥` `NEW`
1. [谷爱凌追平王濛冬奥奖牌纪录 (Gu Ailing equals Wang Meng’s Winter Olympic medal record)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E8%BF%BD%E5%B9%B3%E7%8E%8B%E6%BF%9B%E5%86%AC%E5%A5%A5%E5%A5%96%E7%89%8C%E7%BA%AA%E5%BD%95%23) `1.5M 🔥` `+180%`
1. [谷爱凌一战刷爆多项纪录](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E4%B8%80%E6%88%98%E5%88%B7%E7%88%86%E5%A4%9A%E9%A1%B9%E7%BA%AA%E5%BD%95%23) `507.2K 🔥` `+87%`
1. [孟子义李昀锐 四搭](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%20%E5%9B%9B%E6%90%AD%23) `408.1K 🔥` `+88%`
1. [孙耀威当年真没骗人简直是仙女下凡](https://s.weibo.com/weibo?q=%23%E5%AD%99%E8%80%80%E5%A8%81%E5%BD%93%E5%B9%B4%E7%9C%9F%E6%B2%A1%E9%AA%97%E4%BA%BA%E7%AE%80%E7%9B%B4%E6%98%AF%E4%BB%99%E5%A5%B3%E4%B8%8B%E5%87%A1%23) `340.3K 🔥` `+101%`
1. [李峋的vlog全是公主 (Li Xun’s vlogs are all about princesses)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%B3%8B%E7%9A%84vlog%E5%85%A8%E6%98%AF%E5%85%AC%E4%B8%BB%23) `279.2K 🔥` `+30%`
1. [果然爱情公寓不是拍给当时的我们看的](https://s.weibo.com/weibo?q=%23%E6%9E%9C%E7%84%B6%E7%88%B1%E6%83%85%E5%85%AC%E5%AF%93%E4%B8%8D%E6%98%AF%E6%8B%8D%E7%BB%99%E5%BD%93%E6%97%B6%E7%9A%84%E6%88%91%E4%BB%AC%E7%9C%8B%E7%9A%84%23) `388.0K 🔥`
1. [极客湾 下架 (Geek Bay removed from shelves)](https://s.weibo.com/weibo?q=%23%E6%9E%81%E5%AE%A2%E6%B9%BE%20%E4%B8%8B%E6%9E%B6%23) `366.9K 🔥`
1. [谷爱凌李方慧 慧当凌绝顶](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%9D%8E%E6%96%B9%E6%85%A7%20%E6%85%A7%E5%BD%93%E5%87%8C%E7%BB%9D%E9%A1%B6%23) `264.4K 🔥`
1. [淀粉肠进入瑜伽裤时代 (Starch intestine enters the era of yoga pants)](https://s.weibo.com/weibo?q=%23%E6%B7%80%E7%B2%89%E8%82%A0%E8%BF%9B%E5%85%A5%E7%91%9C%E4%BC%BD%E8%A3%A4%E6%97%B6%E4%BB%A3%23) `236.4K 🔥`
1. [厚本 长剧](https://s.weibo.com/weibo?q=%23%E5%8E%9A%E6%9C%AC%20%E9%95%BF%E5%89%A7%23) `230.7K 🔥`
1. [杨幂演技](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E6%BC%94%E6%8A%80%23) `213.1K 🔥`
1. [远嫁姐姐回家 47岁弟弟激动得像孩子](https://s.weibo.com/weibo?q=%23%E8%BF%9C%E5%AB%81%E5%A7%90%E5%A7%90%E5%9B%9E%E5%AE%B6%2047%E5%B2%81%E5%BC%9F%E5%BC%9F%E6%BF%80%E5%8A%A8%E5%BE%97%E5%83%8F%E5%AD%A9%E5%AD%90%23) `194.3K 🔥`
1. [徐梦桃父亲在线催生 (Xu Mengtao’s father gave birth online)](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E7%88%B6%E4%BA%B2%E5%9C%A8%E7%BA%BF%E5%82%AC%E7%94%9F%23) `182.7K 🔥`
1. [大年初五8岁男童虎跳峡坠崖遇难 (An 8-year-old boy died after falling off a cliff in Tiger Leaping Gorge on the fifth day of the Lunar New Year)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%B9%B4%E5%88%9D%E4%BA%948%E5%B2%81%E7%94%B7%E7%AB%A5%E8%99%8E%E8%B7%B3%E5%B3%A1%E5%9D%A0%E5%B4%96%E9%81%87%E9%9A%BE%23) `181.9K 🔥`
1. [男女性吸引通常两三年就会变淡](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%A5%B3%E6%80%A7%E5%90%B8%E5%BC%95%E9%80%9A%E5%B8%B8%E4%B8%A4%E4%B8%89%E5%B9%B4%E5%B0%B1%E4%BC%9A%E5%8F%98%E6%B7%A1%23) `121.9K 🔥`
1. [不要在吃喝方面拿捏人](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%A6%81%E5%9C%A8%E5%90%83%E5%96%9D%E6%96%B9%E9%9D%A2%E6%8B%BF%E6%8D%8F%E4%BA%BA%23) `118.2K 🔥`
1. [谷爱凌金牌 (Gu Ailing gold medal)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E9%87%91%E7%89%8C%23) `6.7M 🔥` `-44%`
1. [中国队5金4银6铜收官 (The Chinese team finished with 5 golds, 4 silvers and 6 bronzes)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%98%9F5%E9%87%914%E9%93%B66%E9%93%9C%E6%94%B6%E5%AE%98%23) `811.9K 🔥` `-49%`
1. [谷爱凌第三滑94.75分 (Gu Ailing skated third with 94.75 points)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E7%AC%AC%E4%B8%89%E6%BB%9194.75%E5%88%86%23) `756.5K 🔥` `-72%`
1. [李方慧银牌](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%96%B9%E6%85%A7%E9%93%B6%E7%89%8C%23) `492.7K 🔥` `-65%`
1. [女子U型场地决赛 (Women's halfpipe final)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90U%E5%9E%8B%E5%9C%BA%E5%9C%B0%E5%86%B3%E8%B5%9B%23) `484.5K 🔥` `-59%`
1. [韩国队抗议米兰冬奥至少4次印错国旗 (The South Korean team protested at least 4 times the wrong flag was printed at the Milan Winter Olympics)](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E9%98%9F%E6%8A%97%E8%AE%AE%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E8%87%B3%E5%B0%914%E6%AC%A1%E5%8D%B0%E9%94%99%E5%9B%BD%E6%97%97%23) `244.5K 🔥` `-49%`
1. [奖牌榜](https://s.weibo.com/weibo?q=%23%E5%A5%96%E7%89%8C%E6%A6%9C%23) `243.1K 🔥` `-53%`
1. [谷爱凌 大心脏](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%20%E5%A4%A7%E5%BF%83%E8%84%8F%23) `185.7K 🔥` `-43%`
1. [谷爱凌李方慧拥抱 (Hug by Gu Ailing and Li Fanghui)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E6%9D%8E%E6%96%B9%E6%85%A7%E6%8B%A5%E6%8A%B1%23) `142.2K 🔥` `-76%`
1. [唐宫奇案大结局 (The finale of The Strange Case of Tang Palace)](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%AE%AB%E5%A5%87%E6%A1%88%E5%A4%A7%E7%BB%93%E5%B1%80%23) `134.9K 🔥` `-38%`
1. [曝票房15亿是镖人的回本线 (It is revealed that the box office of 1.5 billion is the return line for escorts)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%A5%A8%E6%88%BF15%E4%BA%BF%E6%98%AF%E9%95%96%E4%BA%BA%E7%9A%84%E5%9B%9E%E6%9C%AC%E7%BA%BF%23) `128.2K 🔥` `-27%`
1. [仙逆](https://s.weibo.com/weibo?q=%23%E4%BB%99%E9%80%86%23) `117.1K 🔥` `-21%`
1. [李方慧第三滑93.00分](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%96%B9%E6%85%A7%E7%AC%AC%E4%B8%89%E6%BB%9193.00%E5%88%86%23) `109.3K 🔥` `-54%`
1. [谷爱凌空中姿态太美了](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E7%A9%BA%E4%B8%AD%E5%A7%BF%E6%80%81%E5%A4%AA%E7%BE%8E%E4%BA%86%23) `105.6K 🔥` `-49%`
1. [孟子义沈妙路透 (Mencius Shen Miao Reuters)](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%B2%88%E5%A6%99%E8%B7%AF%E9%80%8F%23) `104.3K 🔥` `-22%`
1. [杨幂说白帆插足别人婚姻是错误的](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%B9%82%E8%AF%B4%E7%99%BD%E5%B8%86%E6%8F%92%E8%B6%B3%E5%88%AB%E4%BA%BA%E5%A9%9A%E5%A7%BB%E6%98%AF%E9%94%99%E8%AF%AF%E7%9A%84%23) `86.4K 🔥` `-23%`
1. [输液过敏死亡独生女父母有残疾](https://s.weibo.com/weibo?q=%23%E8%BE%93%E6%B6%B2%E8%BF%87%E6%95%8F%E6%AD%BB%E4%BA%A1%E7%8B%AC%E7%94%9F%E5%A5%B3%E7%88%B6%E6%AF%8D%E6%9C%89%E6%AE%8B%E7%96%BE%23) `80.9K 🔥` `-36%`
1. [小猫一头扎进大猫怀里](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E4%B8%80%E5%A4%B4%E6%89%8E%E8%BF%9B%E5%A4%A7%E7%8C%AB%E6%80%80%E9%87%8C%23) `77.2K 🔥` `-31%`
1. [徐梦桃说太嘚瑟了结果金牌被刮花](https://s.weibo.com/weibo?q=%23%E5%BE%90%E6%A2%A6%E6%A1%83%E8%AF%B4%E5%A4%AA%E5%98%9A%E7%91%9F%E4%BA%86%E7%BB%93%E6%9E%9C%E9%87%91%E7%89%8C%E8%A2%AB%E5%88%AE%E8%8A%B1%23) `75.8K 🔥` `-53%`

Updated at 2026-02-22 20:22:44

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
