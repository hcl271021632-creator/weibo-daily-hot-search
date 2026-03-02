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

1. [以军超100架战机空袭伊朗 (More than 100 Israeli fighter jets launch air strikes on Iran)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E8%B6%85100%E6%9E%B6%E6%88%98%E6%9C%BA%E7%A9%BA%E8%A2%AD%E4%BC%8A%E6%9C%97%23) `1.2M 🔥` `NEW`
1. [豆瓣 薅羊毛](https://s.weibo.com/weibo?q=%23%E8%B1%86%E7%93%A3%20%E8%96%85%E7%BE%8A%E6%AF%9B%23) `845.2K 🔥` `NEW`
1. [骏马闹元宵贺卡](https://s.weibo.com/weibo?q=%23%E9%AA%8F%E9%A9%AC%E9%97%B9%E5%85%83%E5%AE%B5%E8%B4%BA%E5%8D%A1%23) `698.7K 🔥` `NEW`
1. [霸王茶姬口令](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `443.3K 🔥` `NEW`
1. [油价](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%23) `286.7K 🔥` `NEW`
1. [广式离职申请书](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E5%BC%8F%E7%A6%BB%E8%81%8C%E7%94%B3%E8%AF%B7%E4%B9%A6%23) `274.1K 🔥` `NEW`
1. [油价金价大涨](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E9%87%91%E4%BB%B7%E5%A4%A7%E6%B6%A8%23) `273.7K 🔥` `NEW`
1. [以军轰炸黎巴嫩首都](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E5%86%9B%E8%BD%B0%E7%82%B8%E9%BB%8E%E5%B7%B4%E5%AB%A9%E9%A6%96%E9%83%BD%23) `273.6K 🔥` `NEW`
1. [孟子义自曝两年最长只休了2天](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E8%87%AA%E6%9B%9D%E4%B8%A4%E5%B9%B4%E6%9C%80%E9%95%BF%E5%8F%AA%E4%BC%91%E4%BA%862%E5%A4%A9%23) `273.4K 🔥` `NEW`
1. [北京协和医院提出的科学减重方法](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E5%8D%8F%E5%92%8C%E5%8C%BB%E9%99%A2%E6%8F%90%E5%87%BA%E7%9A%84%E7%A7%91%E5%AD%A6%E5%87%8F%E9%87%8D%E6%96%B9%E6%B3%95%23) `273.2K 🔥` `NEW`
1. [首都机场工作人员穿上汉服 (Capital Airport staff wear Hanfu)](https://s.weibo.com/weibo?q=%23%E9%A6%96%E9%83%BD%E6%9C%BA%E5%9C%BA%E5%B7%A5%E4%BD%9C%E4%BA%BA%E5%91%98%E7%A9%BF%E4%B8%8A%E6%B1%89%E6%9C%8D%23) `273.0K 🔥` `NEW`
1. [伊朗会不会变成下个伊拉克](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%BC%9A%E4%B8%8D%E4%BC%9A%E5%8F%98%E6%88%90%E4%B8%8B%E4%B8%AA%E4%BC%8A%E6%8B%89%E5%85%8B%23) `272.7K 🔥` `NEW`
1. [宋威龙误入直播间](https://s.weibo.com/weibo?q=%23%E5%AE%8B%E5%A8%81%E9%BE%99%E8%AF%AF%E5%85%A5%E7%9B%B4%E6%92%AD%E9%97%B4%23) `272.5K 🔥` `NEW`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `272.3K 🔥` `NEW`
1. [赞达亚荷兰弟已经结婚](https://s.weibo.com/weibo?q=%23%E8%B5%9E%E8%BE%BE%E4%BA%9A%E8%8D%B7%E5%85%B0%E5%BC%9F%E5%B7%B2%E7%BB%8F%E7%BB%93%E5%A9%9A%23) `271.6K 🔥` `NEW`
1. [金银涨爆了](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%93%B6%E6%B6%A8%E7%88%86%E4%BA%86%23) `271.5K 🔥` `NEW`
1. [亲母女嫁给了亲父子](https://s.weibo.com/weibo?q=%23%E4%BA%B2%E6%AF%8D%E5%A5%B3%E5%AB%81%E7%BB%99%E4%BA%86%E4%BA%B2%E7%88%B6%E5%AD%90%23) `271.4K 🔥` `NEW`
1. [阿富汗使用重型武器打击巴基斯坦](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%AF%8C%E6%B1%97%E4%BD%BF%E7%94%A8%E9%87%8D%E5%9E%8B%E6%AD%A6%E5%99%A8%E6%89%93%E5%87%BB%E5%B7%B4%E5%9F%BA%E6%96%AF%E5%9D%A6%23) `270.7K 🔥` `NEW`
1. [苏翊鸣北京夺冠后一度空虚](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E5%8C%97%E4%BA%AC%E5%A4%BA%E5%86%A0%E5%90%8E%E4%B8%80%E5%BA%A6%E7%A9%BA%E8%99%9A%23) `188.3K 🔥` `NEW`
1. [霍尔木兹海峡两侧船只集体趴窝](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E4%B8%A4%E4%BE%A7%E8%88%B9%E5%8F%AA%E9%9B%86%E4%BD%93%E8%B6%B4%E7%AA%9D%23) `182.5K 🔥` `NEW`
1. [英法德或对伊朗采取防御行动 (Britain, France and Germany may take defensive action against Iran)](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E6%B3%95%E5%BE%B7%E6%88%96%E5%AF%B9%E4%BC%8A%E6%9C%97%E9%87%87%E5%8F%96%E9%98%B2%E5%BE%A1%E8%A1%8C%E5%8A%A8%23) `180.7K 🔥` `NEW`
1. [金饰克价涨到1642元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E6%B6%A8%E5%88%B01642%E5%85%83%23) `171.3K 🔥` `NEW`
1. [一家6口滞留迪拜老人缺药急需帮助](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B66%E5%8F%A3%E6%BB%9E%E7%95%99%E8%BF%AA%E6%8B%9C%E8%80%81%E4%BA%BA%E7%BC%BA%E8%8D%AF%E6%80%A5%E9%9C%80%E5%B8%AE%E5%8A%A9%23) `167.0K 🔥` `NEW`
1. [美军3死5重伤](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B3%E6%AD%BB5%E9%87%8D%E4%BC%A4%23) `150.4K 🔥` `NEW`
1. [浆果类水果简直是来报恩的](https://s.weibo.com/weibo?q=%23%E6%B5%86%E6%9E%9C%E7%B1%BB%E6%B0%B4%E6%9E%9C%E7%AE%80%E7%9B%B4%E6%98%AF%E6%9D%A5%E6%8A%A5%E6%81%A9%E7%9A%84%23) `149.3K 🔥` `NEW`
1. [陈若琳手下又有王牌选手了](https://s.weibo.com/weibo?q=%23%E9%99%88%E8%8B%A5%E7%90%B3%E6%89%8B%E4%B8%8B%E5%8F%88%E6%9C%89%E7%8E%8B%E7%89%8C%E9%80%89%E6%89%8B%E4%BA%86%23) `143.3K 🔥` `NEW`
1. [伊朗遭袭40小时后情况](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%81%AD%E8%A2%AD40%E5%B0%8F%E6%97%B6%E5%90%8E%E6%83%85%E5%86%B5%23) `142.7K 🔥` `NEW`
1. [姐姐姐夫共创](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%A7%90%E5%A4%AB%E5%85%B1%E5%88%9B%23) `135.0K 🔥` `NEW`
1. [范丞丞自曝体重63公斤](https://s.weibo.com/weibo?q=%23%E8%8C%83%E4%B8%9E%E4%B8%9E%E8%87%AA%E6%9B%9D%E4%BD%93%E9%87%8D63%E5%85%AC%E6%96%A4%23) `130.7K 🔥` `NEW`
1. [elk 十月](https://s.weibo.com/weibo?q=%23elk%20%E5%8D%81%E6%9C%88%23) `129.7K 🔥` `NEW`
1. [偶遇李昀锐还合照了 (I met Li Yunrui by chance and took a photo together.)](https://s.weibo.com/weibo?q=%23%E5%81%B6%E9%81%87%E6%9D%8E%E6%98%80%E9%94%90%E8%BF%98%E5%90%88%E7%85%A7%E4%BA%86%23) `126.6K 🔥` `NEW`
1. [七个月大宝宝主动安慰哭泣的妈妈](https://s.weibo.com/weibo?q=%23%E4%B8%83%E4%B8%AA%E6%9C%88%E5%A4%A7%E5%AE%9D%E5%AE%9D%E4%B8%BB%E5%8A%A8%E5%AE%89%E6%85%B0%E5%93%AD%E6%B3%A3%E7%9A%84%E5%A6%88%E5%A6%88%23) `114.3K 🔥` `NEW`
1. [毕雯珺张淼怡新剧领证路透](https://s.weibo.com/weibo?q=%23%E6%AF%95%E9%9B%AF%E7%8F%BA%E5%BC%A0%E6%B7%BC%E6%80%A1%E6%96%B0%E5%89%A7%E9%A2%86%E8%AF%81%E8%B7%AF%E9%80%8F%23) `110.0K 🔥` `NEW`
1. [18名中国公民顺利撤离伊朗](https://s.weibo.com/weibo?q=%2318%E5%90%8D%E4%B8%AD%E5%9B%BD%E5%85%AC%E6%B0%91%E9%A1%BA%E5%88%A9%E6%92%A4%E7%A6%BB%E4%BC%8A%E6%9C%97%23) `103.3K 🔥` `NEW`
1. [中国游客迪拜遇机场停运进退两难](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E6%B8%B8%E5%AE%A2%E8%BF%AA%E6%8B%9C%E9%81%87%E6%9C%BA%E5%9C%BA%E5%81%9C%E8%BF%90%E8%BF%9B%E9%80%80%E4%B8%A4%E9%9A%BE%23) `83.6K 🔥` `NEW`
1. [王楚钦孙颖莎新加坡城市宣传照](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%AD%99%E9%A2%96%E8%8E%8E%E6%96%B0%E5%8A%A0%E5%9D%A1%E5%9F%8E%E5%B8%82%E5%AE%A3%E4%BC%A0%E7%85%A7%23) `80.4K 🔥` `NEW`
1. [王楚钦冠军城市宣传照](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%86%A0%E5%86%9B%E5%9F%8E%E5%B8%82%E5%AE%A3%E4%BC%A0%E7%85%A7%23) `80.1K 🔥` `NEW`
1. [章若楠同款敏感防御伞 (Zhang Ruonan's same sensitive defense umbrella)](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E8%8B%A5%E6%A5%A0%E5%90%8C%E6%AC%BE%E6%95%8F%E6%84%9F%E9%98%B2%E5%BE%A1%E4%BC%9E%23) `288.6K 🔥` `+500%`
1. [小伙腹痛CT查出肠道卡2把勺子 (Boy with abdominal pain, CT found two spoons stuck in intestine)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E4%BC%99%E8%85%B9%E7%97%9BCT%E6%9F%A5%E5%87%BA%E8%82%A0%E9%81%93%E5%8D%A12%E6%8A%8A%E5%8B%BA%E5%AD%90%23) `274.3K 🔥` `+27%`
1. [英法德三国联合声明](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E6%B3%95%E5%BE%B7%E4%B8%89%E5%9B%BD%E8%81%94%E5%90%88%E5%A3%B0%E6%98%8E%23) `273.9K 🔥` `+44%`
1. [俄罗斯在中东的布局被美国搅乱了 (Russia's layout in the Middle East has been disrupted by the United States)](https://s.weibo.com/weibo?q=%23%E4%BF%84%E7%BD%97%E6%96%AF%E5%9C%A8%E4%B8%AD%E4%B8%9C%E7%9A%84%E5%B8%83%E5%B1%80%E8%A2%AB%E7%BE%8E%E5%9B%BD%E6%90%85%E4%B9%B1%E4%BA%86%23) `272.4K 🔥` `+51%`
1. [以色列陷入多线作战的战争泥潭 (Israel is mired in a multi-front war)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E9%99%B7%E5%85%A5%E5%A4%9A%E7%BA%BF%E4%BD%9C%E6%88%98%E7%9A%84%E6%88%98%E4%BA%89%E6%B3%A5%E6%BD%AD%23) `150.4K 🔥` `+65%`
1. [椰子水](https://s.weibo.com/weibo?q=%23%E6%A4%B0%E5%AD%90%E6%B0%B4%23) `298.5K 🔥`
1. [伊朗革命卫队发起新一轮打击 (Iran's Revolutionary Guard launches new round of strikes)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%9D%A9%E5%91%BD%E5%8D%AB%E9%98%9F%E5%8F%91%E8%B5%B7%E6%96%B0%E4%B8%80%E8%BD%AE%E6%89%93%E5%87%BB%23) `86.6K 🔥`
1. [演员逼真到根本看不出来是AI (The actors are so lifelike that you can’t even tell they are AI)](https://s.weibo.com/weibo?q=%23%E6%BC%94%E5%91%98%E9%80%BC%E7%9C%9F%E5%88%B0%E6%A0%B9%E6%9C%AC%E7%9C%8B%E4%B8%8D%E5%87%BA%E6%9D%A5%E6%98%AFAI%23) `288.6K 🔥` `-72%`
1. [难怪周杰伦再也没来成都开过演唱会](https://s.weibo.com/weibo?q=%23%E9%9A%BE%E6%80%AA%E5%91%A8%E6%9D%B0%E4%BC%A6%E5%86%8D%E4%B9%9F%E6%B2%A1%E6%9D%A5%E6%88%90%E9%83%BD%E5%BC%80%E8%BF%87%E6%BC%94%E5%94%B1%E4%BC%9A%23) `274.4K 🔥` `-50%`
1. [伊朗国家电视台总部遭袭 (Iranian state television headquarters attacked)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%9B%BD%E5%AE%B6%E7%94%B5%E8%A7%86%E5%8F%B0%E6%80%BB%E9%83%A8%E9%81%AD%E8%A2%AD%23) `170.4K 🔥` `-49%`
1. [伊朗前总统内贾德遇袭身亡 (Former Iranian President Mahmoud Ahmadinejad killed in attack)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%89%8D%E6%80%BB%E7%BB%9F%E5%86%85%E8%B4%BE%E5%BE%B7%E9%81%87%E8%A2%AD%E8%BA%AB%E4%BA%A1%23) `165.3K 🔥` `-86%`
1. [当狗咖最后一个顾客离开后 (When the last customer of the dog cafe leaves)](https://s.weibo.com/weibo?q=%23%E5%BD%93%E7%8B%97%E5%92%96%E6%9C%80%E5%90%8E%E4%B8%80%E4%B8%AA%E9%A1%BE%E5%AE%A2%E7%A6%BB%E5%BC%80%E5%90%8E%23) `108.8K 🔥` `-43%`
1. [迪丽热巴化妆王亚飞发型丽杰 (Dilireba's makeup, Wang Yafei's hairstyle, Lijie)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%8C%96%E5%A6%86%E7%8E%8B%E4%BA%9A%E9%A3%9E%E5%8F%91%E5%9E%8B%E4%B8%BD%E6%9D%B0%23) `84.5K 🔥` `-34%`

Updated at 2026-03-02 10:50:00

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
