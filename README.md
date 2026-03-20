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

1. [腾讯包场白日提灯 (Tencent private day lantern)](https://s.weibo.com/weibo?q=%23%E8%85%BE%E8%AE%AF%E5%8C%85%E5%9C%BA%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `214.3K 🔥` `NEW`
1. [市监总局通报漂白鸡爪查处情况](https://s.weibo.com/weibo?q=%23%E5%B8%82%E7%9B%91%E6%80%BB%E5%B1%80%E9%80%9A%E6%8A%A5%E6%BC%82%E7%99%BD%E9%B8%A1%E7%88%AA%E6%9F%A5%E5%A4%84%E6%83%85%E5%86%B5%23) `199.4K 🔥` `NEW`
1. [孟佳 品牌邀请看秀不让进场](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E4%BD%B3%20%E5%93%81%E7%89%8C%E9%82%80%E8%AF%B7%E7%9C%8B%E7%A7%80%E4%B8%8D%E8%AE%A9%E8%BF%9B%E5%9C%BA%23) `198.2K 🔥` `NEW`
1. [张凌赫工作室 拍出了张凌赫的死角](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%B7%A5%E4%BD%9C%E5%AE%A4%20%E6%8B%8D%E5%87%BA%E4%BA%86%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%9A%84%E6%AD%BB%E8%A7%92%23) `197.2K 🔥` `NEW`
1. [高市早苗嘲笑拜登照片](https://s.weibo.com/weibo?q=%23%E9%AB%98%E5%B8%82%E6%97%A9%E8%8B%97%E5%98%B2%E7%AC%91%E6%8B%9C%E7%99%BB%E7%85%A7%E7%89%87%23) `194.2K 🔥` `NEW`
1. [留几手听到葛夕官宣恋情后的反应](https://s.weibo.com/weibo?q=%23%E7%95%99%E5%87%A0%E6%89%8B%E5%90%AC%E5%88%B0%E8%91%9B%E5%A4%95%E5%AE%98%E5%AE%A3%E6%81%8B%E6%83%85%E5%90%8E%E7%9A%84%E5%8F%8D%E5%BA%94%23) `130.0K 🔥` `NEW`
1. [发型易容术](https://s.weibo.com/weibo?q=%23%E5%8F%91%E5%9E%8B%E6%98%93%E5%AE%B9%E6%9C%AF%23) `129.1K 🔥` `NEW`
1. [你好1983](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD1983%23) `127.2K 🔥` `NEW`
1. [奥沙利文单杆153分创纪录](https://s.weibo.com/weibo?q=%23%E5%A5%A5%E6%B2%99%E5%88%A9%E6%96%87%E5%8D%95%E6%9D%86153%E5%88%86%E5%88%9B%E7%BA%AA%E5%BD%95%23) `106.0K 🔥` `NEW`
1. [张俪去首尔做手动超声刀](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E4%BF%AA%E5%8E%BB%E9%A6%96%E5%B0%94%E5%81%9A%E6%89%8B%E5%8A%A8%E8%B6%85%E5%A3%B0%E5%88%80%23) `103.6K 🔥` `NEW`
1. [今年已有4名正部级官员落马 (Four ministerial-level officials have been dismissed this year)](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E5%B7%B2%E6%9C%894%E5%90%8D%E6%AD%A3%E9%83%A8%E7%BA%A7%E5%AE%98%E5%91%98%E8%90%BD%E9%A9%AC%23) `100.1K 🔥` `NEW`
1. [黄金大跌后反弹](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E5%A4%A7%E8%B7%8C%E5%90%8E%E5%8F%8D%E5%BC%B9%23) `93.8K 🔥` `NEW`
1. [你好1983 市长爱上离婚带娃的她](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD1983%20%E5%B8%82%E9%95%BF%E7%88%B1%E4%B8%8A%E7%A6%BB%E5%A9%9A%E5%B8%A6%E5%A8%83%E7%9A%84%E5%A5%B9%23) `93.4K 🔥` `NEW`
1. [华为将成立传媒军团](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%B8%BA%E5%B0%86%E6%88%90%E7%AB%8B%E4%BC%A0%E5%AA%92%E5%86%9B%E5%9B%A2%23) `88.3K 🔥` `NEW`
1. [二月二理发师忙到抬不起头](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E6%9C%88%E4%BA%8C%E7%90%86%E5%8F%91%E5%B8%88%E5%BF%99%E5%88%B0%E6%8A%AC%E4%B8%8D%E8%B5%B7%E5%A4%B4%23) `87.5K 🔥` `NEW`
1. [智己LS8预售发布定档3月26日](https://s.weibo.com/weibo?q=%23%E6%99%BA%E5%B7%B1LS8%E9%A2%84%E5%94%AE%E5%8F%91%E5%B8%83%E5%AE%9A%E6%A1%A33%E6%9C%8826%E6%97%A5%23) `86.9K 🔥` `NEW`
1. [种地吧](https://s.weibo.com/weibo?q=%23%E7%A7%8D%E5%9C%B0%E5%90%A7%23) `86.8K 🔥` `NEW`
1. [吴京 老兵旗袍](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E8%80%81%E5%85%B5%E6%97%97%E8%A2%8D%23) `73.8K 🔥` `NEW`
1. [柠檬鸡爪你害惨我了](https://s.weibo.com/weibo?q=%23%E6%9F%A0%E6%AA%AC%E9%B8%A1%E7%88%AA%E4%BD%A0%E5%AE%B3%E6%83%A8%E6%88%91%E4%BA%86%23) `73.0K 🔥` `NEW`
1. [非油炸不是没有油](https://s.weibo.com/weibo?q=%23%E9%9D%9E%E6%B2%B9%E7%82%B8%E4%B8%8D%E6%98%AF%E6%B2%A1%E6%9C%89%E6%B2%B9%23) `72.7K 🔥` `NEW`
1. [刘浩存CMG盛典造型 (Liu Haocun CMG ceremony style)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98CMG%E7%9B%9B%E5%85%B8%E9%80%A0%E5%9E%8B%23) `70.2K 🔥` `NEW`
1. [金饰克价跌到1445元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E8%B7%8C%E5%88%B01445%E5%85%83%23) `70.0K 🔥` `NEW`
1. [梅花肉苹果煎](https://s.weibo.com/weibo?q=%23%E6%A2%85%E8%8A%B1%E8%82%89%E8%8B%B9%E6%9E%9C%E7%85%8E%23) `69.7K 🔥` `NEW`
1. [女子买8套老破小月收租2.1万 (A woman bought 8 old and dilapidated apartments and collected rent of 21,000 yuan a month)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%B08%E5%A5%97%E8%80%81%E7%A0%B4%E5%B0%8F%E6%9C%88%E6%94%B6%E7%A7%9F2.1%E4%B8%87%23) `743.1K 🔥` `+412%`
1. [33岁抗癌博主阿润离世](https://s.weibo.com/weibo?q=%2333%E5%B2%81%E6%8A%97%E7%99%8C%E5%8D%9A%E4%B8%BB%E9%98%BF%E6%B6%A6%E7%A6%BB%E4%B8%96%23) `204.3K 🔥` `+81%`
1. [伊朗伊斯兰革命卫队发言人身亡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BC%8A%E6%96%AF%E5%85%B0%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E5%8F%91%E8%A8%80%E4%BA%BA%E8%BA%AB%E4%BA%A1%23) `204.0K 🔥` `+25%`
1. [铁路通报女子月经弄脏卧铺事件](https://s.weibo.com/weibo?q=%23%E9%93%81%E8%B7%AF%E9%80%9A%E6%8A%A5%E5%A5%B3%E5%AD%90%E6%9C%88%E7%BB%8F%E5%BC%84%E8%84%8F%E5%8D%A7%E9%93%BA%E4%BA%8B%E4%BB%B6%23) `196.6K 🔥` `+22%`
1. [曝AI短剧使用杨紫的脸](https://s.weibo.com/weibo?q=%23%E6%9B%9DAI%E7%9F%AD%E5%89%A7%E4%BD%BF%E7%94%A8%E6%9D%A8%E7%B4%AB%E7%9A%84%E8%84%B8%23) `195.0K 🔥` `+24%`
1. [曝王一博乐华续约](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E7%8E%8B%E4%B8%80%E5%8D%9A%E4%B9%90%E5%8D%8E%E7%BB%AD%E7%BA%A6%23) `193.7K 🔥` `+22%`
1. [超7成人午睡超过半小时](https://s.weibo.com/weibo?q=%23%E8%B6%857%E6%88%90%E4%BA%BA%E5%8D%88%E7%9D%A1%E8%B6%85%E8%BF%87%E5%8D%8A%E5%B0%8F%E6%97%B6%23) `120.9K 🔥` `+67%`
1. [重庆市长胡衡华被查 (Chongqing Mayor Hu Henghua was investigated)](https://s.weibo.com/weibo?q=%23%E9%87%8D%E5%BA%86%E5%B8%82%E9%95%BF%E8%83%A1%E8%A1%A1%E5%8D%8E%E8%A2%AB%E6%9F%A5%23) `1.1M 🔥`
1. [二月二最硬核龙抬头 (The most hard-core dragon raises its head on February 2nd)](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E6%9C%88%E4%BA%8C%E6%9C%80%E7%A1%AC%E6%A0%B8%E9%BE%99%E6%8A%AC%E5%A4%B4%23) `603.3K 🔥`
1. [最平整折叠屏OPPOFindN6火爆开售 (OPPO Find N6, the flattest folding screen, is now on sale)](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%B9%B3%E6%95%B4%E6%8A%98%E5%8F%A0%E5%B1%8FOPPOFindN6%E7%81%AB%E7%88%86%E5%BC%80%E5%94%AE%23) `568.3K 🔥`
1. [二十四节气紫林寻味](https://s.weibo.com/weibo?q=%23%E4%BA%8C%E5%8D%81%E5%9B%9B%E8%8A%82%E6%B0%94%E7%B4%AB%E6%9E%97%E5%AF%BB%E5%91%B3%23) `203.7K 🔥`
1. [山姆被曝冷鲜猪肉是数月前屠宰的 (Sam’s chilled pork was revealed to have been slaughtered months ago)](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%86%E8%A2%AB%E6%9B%9D%E5%86%B7%E9%B2%9C%E7%8C%AA%E8%82%89%E6%98%AF%E6%95%B0%E6%9C%88%E5%89%8D%E5%B1%A0%E5%AE%B0%E7%9A%84%23) `202.9K 🔥`
1. [马龙车轮战霍启刚郭晶晶 (Ma Long wheel battle with Huo Qigang and Guo Jingjing)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E9%BE%99%E8%BD%A6%E8%BD%AE%E6%88%98%E9%9C%8D%E5%90%AF%E5%88%9A%E9%83%AD%E6%99%B6%E6%99%B6%23) `200.6K 🔥`
1. [女子举报退休领导母亲名下巨额财产](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B8%BE%E6%8A%A5%E9%80%80%E4%BC%91%E9%A2%86%E5%AF%BC%E6%AF%8D%E4%BA%B2%E5%90%8D%E4%B8%8B%E5%B7%A8%E9%A2%9D%E8%B4%A2%E4%BA%A7%23) `151.7K 🔥`
1. [经期3个表现警惕子宫腺肌症](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E6%9C%9F3%E4%B8%AA%E8%A1%A8%E7%8E%B0%E8%AD%A6%E6%83%95%E5%AD%90%E5%AE%AB%E8%85%BA%E8%82%8C%E7%97%87%23) `142.3K 🔥`
1. [单依纯 维密](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BE%9D%E7%BA%AF%20%E7%BB%B4%E5%AF%86%23) `138.7K 🔥`
1. [迪丽热巴红衣女鬼塑](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%BA%A2%E8%A1%A3%E5%A5%B3%E9%AC%BC%E5%A1%91%23) `131.0K 🔥`
1. [手胖的人解释不清了](https://s.weibo.com/weibo?q=%23%E6%89%8B%E8%83%96%E7%9A%84%E4%BA%BA%E8%A7%A3%E9%87%8A%E4%B8%8D%E6%B8%85%E4%BA%86%23) `130.7K 🔥`
1. [李维嘉崩溃大哭到无法主持](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BB%B4%E5%98%89%E5%B4%A9%E6%BA%83%E5%A4%A7%E5%93%AD%E5%88%B0%E6%97%A0%E6%B3%95%E4%B8%BB%E6%8C%81%23) `129.7K 🔥`
1. [42岁婆婆刚给儿子娶完媳妇就怀孕了 (The 42-year-old mother-in-law became pregnant just after marrying her son)](https://s.weibo.com/weibo?q=%2342%E5%B2%81%E5%A9%86%E5%A9%86%E5%88%9A%E7%BB%99%E5%84%BF%E5%AD%90%E5%A8%B6%E5%AE%8C%E5%AA%B3%E5%A6%87%E5%B0%B1%E6%80%80%E5%AD%95%E4%BA%86%23) `128.4K 🔥`
1. [网易严选 玩梗](https://s.weibo.com/weibo?q=%23%E7%BD%91%E6%98%93%E4%B8%A5%E9%80%89%20%E7%8E%A9%E6%A2%97%23) `105.4K 🔥`
1. [男子花350万元抄底7套天津老破小](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%8A%B1350%E4%B8%87%E5%85%83%E6%8A%84%E5%BA%957%E5%A5%97%E5%A4%A9%E6%B4%A5%E8%80%81%E7%A0%B4%E5%B0%8F%23) `201.7K 🔥` `-74%`
1. [瞿颖胡兵李静戴军孙浩团综](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%83%A1%E5%85%B5%E6%9D%8E%E9%9D%99%E6%88%B4%E5%86%9B%E5%AD%99%E6%B5%A9%E5%9B%A2%E7%BB%BC%23) `128.4K 🔥` `-36%`
1. [BTS回归 (BTS returns)](https://s.weibo.com/weibo?q=%23BTS%E5%9B%9E%E5%BD%92%23) `114.7K 🔥` `-31%`
1. [大冰分享自己4个月减50斤的经验](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E5%86%B0%E5%88%86%E4%BA%AB%E8%87%AA%E5%B7%B14%E4%B8%AA%E6%9C%88%E5%87%8F50%E6%96%A4%E7%9A%84%E7%BB%8F%E9%AA%8C%23) `104.4K 🔥` `-31%`
1. [女童术后喷血死亡医院曾被罚20万](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E7%AB%A5%E6%9C%AF%E5%90%8E%E5%96%B7%E8%A1%80%E6%AD%BB%E4%BA%A1%E5%8C%BB%E9%99%A2%E6%9B%BE%E8%A2%AB%E7%BD%9A20%E4%B8%87%23) `98.7K 🔥` `-27%`
1. [夏弃疾拍的热巴陈飞宇 (Reba and Chen Feiyu photographed by Xia Qiji)](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E5%BC%83%E7%96%BE%E6%8B%8D%E7%9A%84%E7%83%AD%E5%B7%B4%E9%99%88%E9%A3%9E%E5%AE%87%23) `90.2K 🔥` `-22%`
1. [迪丽热巴新经纪人郝阿三上岗了 (Dilireba’s new manager Hao Asan has taken up the post)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%96%B0%E7%BB%8F%E7%BA%AA%E4%BA%BA%E9%83%9D%E9%98%BF%E4%B8%89%E4%B8%8A%E5%B2%97%E4%BA%86%23) `83.4K 🔥` `-43%`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `78.0K 🔥` `-43%`

Updated at 2026-03-20 16:57:28

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
