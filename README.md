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

1. [认识的哥哥 (Brother I know)](https://s.weibo.com/weibo?q=%23%E8%AE%A4%E8%AF%86%E7%9A%84%E5%93%A5%E5%93%A5%23) `117.2K 🔥` `NEW`
1. [Knight巴西服改名Tian](https://s.weibo.com/weibo?q=%23Knight%E5%B7%B4%E8%A5%BF%E6%9C%8D%E6%94%B9%E5%90%8DTian%23) `117.0K 🔥` `NEW`
1. [我家那小子](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%AE%B6%E9%82%A3%E5%B0%8F%E5%AD%90%23) `116.5K 🔥` `NEW`
1. [女子捐赠4万多毫升母乳给医院](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E6%8D%90%E8%B5%A04%E4%B8%87%E5%A4%9A%E6%AF%AB%E5%8D%87%E6%AF%8D%E4%B9%B3%E7%BB%99%E5%8C%BB%E9%99%A2%23) `776.9K 🔥` `+242%`
1. [文淇路演亲了粉丝](https://s.weibo.com/weibo?q=%23%E6%96%87%E6%B7%87%E8%B7%AF%E6%BC%94%E4%BA%B2%E4%BA%86%E7%B2%89%E4%B8%9D%23) `282.0K 🔥` `+103%`
1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `173.5K 🔥` `+44%`
1. [女孩长期便血以为是痔疮结果是癌症 (Girl's long-term blood in stool thought it was hemorrhoids but turned out to be cancer)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%A9%E9%95%BF%E6%9C%9F%E4%BE%BF%E8%A1%80%E4%BB%A5%E4%B8%BA%E6%98%AF%E7%97%94%E7%96%AE%E7%BB%93%E6%9E%9C%E6%98%AF%E7%99%8C%E7%97%87%23) `157.0K 🔥` `+41%`
1. [原来这就叫感官过载呀](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E8%BF%99%E5%B0%B1%E5%8F%AB%E6%84%9F%E5%AE%98%E8%BF%87%E8%BD%BD%E5%91%80%23) `156.2K 🔥` `+79%`
1. [内娱明星在Tiffany晚宴团建](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A8%B1%E6%98%8E%E6%98%9F%E5%9C%A8Tiffany%E6%99%9A%E5%AE%B4%E5%9B%A2%E5%BB%BA%23) `153.3K 🔥` `+37%`
1. [爱奇艺海外播放量前十作品 (iQIYI’s top ten most played overseas works)](https://s.weibo.com/weibo?q=%23%E7%88%B1%E5%A5%87%E8%89%BA%E6%B5%B7%E5%A4%96%E6%92%AD%E6%94%BE%E9%87%8F%E5%89%8D%E5%8D%81%E4%BD%9C%E5%93%81%23) `152.7K 🔥` `+37%`
1. [女子翻丈夫手机发现其出轨几十人](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%BF%BB%E4%B8%88%E5%A4%AB%E6%89%8B%E6%9C%BA%E5%8F%91%E7%8E%B0%E5%85%B6%E5%87%BA%E8%BD%A8%E5%87%A0%E5%8D%81%E4%BA%BA%23) `152.0K 🔥` `+39%`
1. [著名哲学家哈贝马斯去世 (Famous philosopher Habermas dies)](https://s.weibo.com/weibo?q=%23%E8%91%97%E5%90%8D%E5%93%B2%E5%AD%A6%E5%AE%B6%E5%93%88%E8%B4%9D%E9%A9%AC%E6%96%AF%E5%8E%BB%E4%B8%96%23) `151.2K 🔥` `+45%`
1. [成毅撤诉](https://s.weibo.com/weibo?q=%23%E6%88%90%E6%AF%85%E6%92%A4%E8%AF%89%23) `150.8K 🔥` `+38%`
1. [王冕官宣生子 (Wang Miangguan announces the birth of a son)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%86%95%E5%AE%98%E5%AE%A3%E7%94%9F%E5%AD%90%23) `149.8K 🔥` `+35%`
1. [伊朗宣布导弹命中率提升了一倍](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%A3%E5%B8%83%E5%AF%BC%E5%BC%B9%E5%91%BD%E4%B8%AD%E7%8E%87%E6%8F%90%E5%8D%87%E4%BA%86%E4%B8%80%E5%80%8D%23) `149.2K 🔥` `+61%`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `149.0K 🔥` `+38%`
1. [唐嫣张若昀主持 (Tang Yan hosted by Zhang Ruoyun)](https://s.weibo.com/weibo?q=%23%E5%94%90%E5%AB%A3%E5%BC%A0%E8%8B%A5%E6%98%80%E4%B8%BB%E6%8C%81%23) `148.3K 🔥` `+45%`
1. [袋鼠妈妈被曝虚假宣传孕妇适用](https://s.weibo.com/weibo?q=%23%E8%A2%8B%E9%BC%A0%E5%A6%88%E5%A6%88%E8%A2%AB%E6%9B%9D%E8%99%9A%E5%81%87%E5%AE%A3%E4%BC%A0%E5%AD%95%E5%A6%87%E9%80%82%E7%94%A8%23) `134.3K 🔥` `+57%`
1. [李宇春张靓颖周笔畅该来的都没来](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%AE%87%E6%98%A5%E5%BC%A0%E9%9D%93%E9%A2%96%E5%91%A8%E7%AC%94%E7%95%85%E8%AF%A5%E6%9D%A5%E7%9A%84%E9%83%BD%E6%B2%A1%E6%9D%A5%23) `124.6K 🔥` `+27%`
1. [春晚与周深同台女孩靠输血维持生命](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E4%B8%8E%E5%91%A8%E6%B7%B1%E5%90%8C%E5%8F%B0%E5%A5%B3%E5%AD%A9%E9%9D%A0%E8%BE%93%E8%A1%80%E7%BB%B4%E6%8C%81%E7%94%9F%E5%91%BD%23) `121.2K 🔥` `+31%`
1. [广东315晚会](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C315%E6%99%9A%E4%BC%9A%23) `119.0K 🔥` `+45%`
1. [金道勋ana互动](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%81%93%E5%8B%8Bana%E4%BA%92%E5%8A%A8%23) `118.5K 🔥` `+33%`
1. [柯淳人帅心善买了残疾人的水果](https://s.weibo.com/weibo?q=%23%E6%9F%AF%E6%B7%B3%E4%BA%BA%E5%B8%85%E5%BF%83%E5%96%84%E4%B9%B0%E4%BA%86%E6%AE%8B%E7%96%BE%E4%BA%BA%E7%9A%84%E6%B0%B4%E6%9E%9C%23) `118.4K 🔥` `+30%`
1. [孔雪儿邓凯浴池戏 (Kong Xueer and Deng Kai bath scene)](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E9%82%93%E5%87%AF%E6%B5%B4%E6%B1%A0%E6%88%8F%23) `118.1K 🔥` `+34%`
1. [伊朗称袭击美军中东三大军事基地](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%E4%B8%AD%E4%B8%9C%E4%B8%89%E5%A4%A7%E5%86%9B%E4%BA%8B%E5%9F%BA%E5%9C%B0%23) `117.9K 🔥` `+47%`
1. [夏之光出道两年每月只有三千元](https://s.weibo.com/weibo?q=%23%E5%A4%8F%E4%B9%8B%E5%85%89%E5%87%BA%E9%81%93%E4%B8%A4%E5%B9%B4%E6%AF%8F%E6%9C%88%E5%8F%AA%E6%9C%89%E4%B8%89%E5%8D%83%E5%85%83%23) `117.7K 🔥` `+40%`
1. [TOP直播 (TOP live broadcast)](https://s.weibo.com/weibo?q=%23TOP%E7%9B%B4%E6%92%AD%23) `117.6K 🔥` `+50%`
1. [刘文祥麻辣烫回应鸭肉当猪肉牛肉卖 (Liu Wenxiang Malatang responded by selling duck meat as pork and beef)](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%96%87%E7%A5%A5%E9%BA%BB%E8%BE%A3%E7%83%AB%E5%9B%9E%E5%BA%94%E9%B8%AD%E8%82%89%E5%BD%93%E7%8C%AA%E8%82%89%E7%89%9B%E8%82%89%E5%8D%96%23) `117.5K 🔥` `+30%`
1. [林依晨称因熬夜和压力患脑部囊肿](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BE%9D%E6%99%A8%E7%A7%B0%E5%9B%A0%E7%86%AC%E5%A4%9C%E5%92%8C%E5%8E%8B%E5%8A%9B%E6%82%A3%E8%84%91%E9%83%A8%E5%9B%8A%E8%82%BF%23) `117.3K 🔥` `+36%`
1. [黄子弘凡鸟巢上座率 (Huang Zihongfan Bird's Nest attendance rate)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E5%BC%98%E5%87%A1%E9%B8%9F%E5%B7%A2%E4%B8%8A%E5%BA%A7%E7%8E%87%23) `117.0K 🔥` `+39%`
1. [谢征越骗越多](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E8%B6%8A%E9%AA%97%E8%B6%8A%E5%A4%9A%23) `116.8K 🔥` `+43%`
1. [松岛辉空仰天大笑庆祝胜利](https://s.weibo.com/weibo?q=%23%E6%9D%BE%E5%B2%9B%E8%BE%89%E7%A9%BA%E4%BB%B0%E5%A4%A9%E5%A4%A7%E7%AC%91%E5%BA%86%E7%A5%9D%E8%83%9C%E5%88%A9%23) `116.6K 🔥` `+46%`
1. [一栗小莎子近况](https://s.weibo.com/weibo?q=%23%E4%B8%80%E6%A0%97%E5%B0%8F%E8%8E%8E%E5%AD%90%E8%BF%91%E5%86%B5%23) `116.4K 🔥` `+46%`
1. [杨舒予飞身拥抱杨力维 (Yang Shuyu flew to hug Yang Liwei)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%88%92%E4%BA%88%E9%A3%9E%E8%BA%AB%E6%8B%A5%E6%8A%B1%E6%9D%A8%E5%8A%9B%E7%BB%B4%23) `116.2K 🔥` `+51%`
1. [暗访10家便利店10家都卖假烟](https://s.weibo.com/weibo?q=%23%E6%9A%97%E8%AE%BF10%E5%AE%B6%E4%BE%BF%E5%88%A9%E5%BA%9710%E5%AE%B6%E9%83%BD%E5%8D%96%E5%81%87%E7%83%9F%23) `1.1M 🔥`
1. [十五五民生红包](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E6%B0%91%E7%94%9F%E7%BA%A2%E5%8C%85%23) `627.1K 🔥`
1. [余承东小尼点亮华为生活全景图 (Yu Chengdong and Xiaoni light up Huawei’s life panorama)](https://s.weibo.com/weibo?q=%23%E4%BD%99%E6%89%BF%E4%B8%9C%E5%B0%8F%E5%B0%BC%E7%82%B9%E4%BA%AE%E5%8D%8E%E4%B8%BA%E7%94%9F%E6%B4%BB%E5%85%A8%E6%99%AF%E5%9B%BE%23) `416.6K 🔥`
1. [吉利银河迈入长续航时代 (Geely Galaxy enters the era of long battery life)](https://s.weibo.com/weibo?q=%23%E5%90%89%E5%88%A9%E9%93%B6%E6%B2%B3%E8%BF%88%E5%85%A5%E9%95%BF%E7%BB%AD%E8%88%AA%E6%97%B6%E4%BB%A3%23) `225.2K 🔥`
1. [第一次被一个柜子惊艳到](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%A2%AB%E4%B8%80%E4%B8%AA%E6%9F%9C%E5%AD%90%E6%83%8A%E8%89%B3%E5%88%B0%23) `175.3K 🔥`
1. [KSG战胜AG (KSG defeated AG)](https://s.weibo.com/weibo?q=%23KSG%E6%88%98%E8%83%9CAG%23) `169.7K 🔥`
1. [人民大会堂的同款老式热水瓶已停产](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E6%B0%91%E5%A4%A7%E4%BC%9A%E5%A0%82%E7%9A%84%E5%90%8C%E6%AC%BE%E8%80%81%E5%BC%8F%E7%83%AD%E6%B0%B4%E7%93%B6%E5%B7%B2%E5%81%9C%E4%BA%A7%23) `168.8K 🔥`
1. [王楚钦差点吐了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%B7%AE%E7%82%B9%E5%90%90%E4%BA%86%23) `165.4K 🔥`
1. [中国34岁女子在泰国被抛尸水沟 (34-year-old Chinese woman dumped in ditch in Thailand)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD34%E5%B2%81%E5%A5%B3%E5%AD%90%E5%9C%A8%E6%B3%B0%E5%9B%BD%E8%A2%AB%E6%8A%9B%E5%B0%B8%E6%B0%B4%E6%B2%9F%23) `162.5K 🔥`
1. [王楚钦2比4松岛辉空 (Wang Chuqin 2 to 4 Matsushima Terukong)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A62%E6%AF%944%E6%9D%BE%E5%B2%9B%E8%BE%89%E7%A9%BA%23) `157.5K 🔥`
1. [两人敲晕老年犬丢垃圾桶致死被罚款](https://s.weibo.com/weibo?q=%23%E4%B8%A4%E4%BA%BA%E6%95%B2%E6%99%95%E8%80%81%E5%B9%B4%E7%8A%AC%E4%B8%A2%E5%9E%83%E5%9C%BE%E6%A1%B6%E8%87%B4%E6%AD%BB%E8%A2%AB%E7%BD%9A%E6%AC%BE%23) `157.3K 🔥`
1. [韩综男主持当众殴打女主持 (Korean TV show male host assaults female host in public)](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E7%BB%BC%E7%94%B7%E4%B8%BB%E6%8C%81%E5%BD%93%E4%BC%97%E6%AE%B4%E6%89%93%E5%A5%B3%E4%B8%BB%E6%8C%81%23) `155.3K 🔥`
1. [逐玉热度超过宁安如梦](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%83%AD%E5%BA%A6%E8%B6%85%E8%BF%87%E5%AE%81%E5%AE%89%E5%A6%82%E6%A2%A6%23) `155.1K 🔥`
1. [日本考虑购买俄罗斯石油](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E8%80%83%E8%99%91%E8%B4%AD%E4%B9%B0%E4%BF%84%E7%BD%97%E6%96%AF%E7%9F%B3%E6%B2%B9%23) `154.2K 🔥`
1. [AG对战KSG (AG vs. KSG)](https://s.weibo.com/weibo?q=%23AG%E5%AF%B9%E6%88%98KSG%23) `118.3K 🔥`
1. [胡先煦看了黄子弘凡演唱会](https://s.weibo.com/weibo?q=%23%E8%83%A1%E5%85%88%E7%85%A6%E7%9C%8B%E4%BA%86%E9%BB%84%E5%AD%90%E5%BC%98%E5%87%A1%E6%BC%94%E5%94%B1%E4%BC%9A%23) `118.1K 🔥`
1. [谢征试探长玉](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E8%AF%95%E6%8E%A2%E9%95%BF%E7%8E%89%23) `262.4K 🔥` `-39%`
1. [央视315晚会点了4个领域 (CCTV 315 Party highlighted 4 areas)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86315%E6%99%9A%E4%BC%9A%E7%82%B9%E4%BA%864%E4%B8%AA%E9%A2%86%E5%9F%9F%23) `251.0K 🔥` `-69%`

Updated at 2026-03-14 23:54:18

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
