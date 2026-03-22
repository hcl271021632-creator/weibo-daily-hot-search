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

1. [女子久坐便血半年后确诊癌症晚期 (Woman diagnosed with terminal cancer six months after sitting for long periods of time and having bloody stools)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B9%85%E5%9D%90%E4%BE%BF%E8%A1%80%E5%8D%8A%E5%B9%B4%E5%90%8E%E7%A1%AE%E8%AF%8A%E7%99%8C%E7%97%87%E6%99%9A%E6%9C%9F%23) `208.0K 🔥` `NEW`
1. [猥亵15岁少女民警曾对自己行为极力否认](https://s.weibo.com/weibo?q=%23%E7%8C%A5%E4%BA%B515%E5%B2%81%E5%B0%91%E5%A5%B3%E6%B0%91%E8%AD%A6%E6%9B%BE%E5%AF%B9%E8%87%AA%E5%B7%B1%E8%A1%8C%E4%B8%BA%E6%9E%81%E5%8A%9B%E5%90%A6%E8%AE%A4%23) `165.0K 🔥` `NEW`
1. [贾斯汀比伯Usher派对打架](https://s.weibo.com/weibo?q=%23%E8%B4%BE%E6%96%AF%E6%B1%80%E6%AF%94%E4%BC%AFUsher%E6%B4%BE%E5%AF%B9%E6%89%93%E6%9E%B6%23) `144.5K 🔥` `NEW`
1. [李嘉格没有不爱帅哥的义务](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E5%98%89%E6%A0%BC%E6%B2%A1%E6%9C%89%E4%B8%8D%E7%88%B1%E5%B8%85%E5%93%A5%E7%9A%84%E4%B9%89%E5%8A%A1%23) `77.8K 🔥` `NEW`
1. [虞书欣杀青给粉丝鞠躬](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E6%9D%80%E9%9D%92%E7%BB%99%E7%B2%89%E4%B8%9D%E9%9E%A0%E8%BA%AC%23) `75.6K 🔥` `NEW`
1. [Xteam晋级深渊九全球总决赛](https://s.weibo.com/weibo?q=%23Xteam%E6%99%8B%E7%BA%A7%E6%B7%B1%E6%B8%8A%E4%B9%9D%E5%85%A8%E7%90%83%E6%80%BB%E5%86%B3%E8%B5%9B%23) `72.5K 🔥` `NEW`
1. [雨梦好牛](https://s.weibo.com/weibo?q=%23%E9%9B%A8%E6%A2%A6%E5%A5%BD%E7%89%9B%23) `69.3K 🔥` `NEW`
1. [雷军回应新su7销量](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%9B%9E%E5%BA%94%E6%96%B0su7%E9%94%80%E9%87%8F%23) `65.7K 🔥` `NEW`
1. [吐槽用水测评卫生巾](https://s.weibo.com/weibo?q=%23%E5%90%90%E6%A7%BD%E7%94%A8%E6%B0%B4%E6%B5%8B%E8%AF%84%E5%8D%AB%E7%94%9F%E5%B7%BE%23) `64.6K 🔥` `NEW`
1. [新SU7北京开到上海仅充1次电](https://s.weibo.com/weibo?q=%23%E6%96%B0SU7%E5%8C%97%E4%BA%AC%E5%BC%80%E5%88%B0%E4%B8%8A%E6%B5%B7%E4%BB%85%E5%85%851%E6%AC%A1%E7%94%B5%23) `63.8K 🔥` `NEW`
1. [这么多年误会执子之手了 (After so many years of misunderstanding, we have held hands.)](https://s.weibo.com/weibo?q=%23%E8%BF%99%E4%B9%88%E5%A4%9A%E5%B9%B4%E8%AF%AF%E4%BC%9A%E6%89%A7%E5%AD%90%E4%B9%8B%E6%89%8B%E4%BA%86%23) `62.2K 🔥` `NEW`
1. [报喜不报忧的本质](https://s.weibo.com/weibo?q=%23%E6%8A%A5%E5%96%9C%E4%B8%8D%E6%8A%A5%E5%BF%A7%E7%9A%84%E6%9C%AC%E8%B4%A8%23) `59.3K 🔥` `NEW`
1. [詹姆斯超20项纪录历史第一](https://s.weibo.com/weibo?q=%23%E8%A9%B9%E5%A7%86%E6%96%AF%E8%B6%8520%E9%A1%B9%E7%BA%AA%E5%BD%95%E5%8E%86%E5%8F%B2%E7%AC%AC%E4%B8%80%23) `53.3K 🔥` `NEW`
1. [你好1983 女频爽剧](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%A5%BD1983%20%E5%A5%B3%E9%A2%91%E7%88%BD%E5%89%A7%23) `52.2K 🔥` `NEW`
1. [华中师大放话想把冠军留在武汉](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E4%B8%AD%E5%B8%88%E5%A4%A7%E6%94%BE%E8%AF%9D%E6%83%B3%E6%8A%8A%E5%86%A0%E5%86%9B%E7%95%99%E5%9C%A8%E6%AD%A6%E6%B1%89%23) `51.7K 🔥` `NEW`
1. [外媒曝多艘美军舰增援中东](https://s.weibo.com/weibo?q=%23%E5%A4%96%E5%AA%92%E6%9B%9D%E5%A4%9A%E8%89%98%E7%BE%8E%E5%86%9B%E8%88%B0%E5%A2%9E%E6%8F%B4%E4%B8%AD%E4%B8%9C%23) `51.2K 🔥` `NEW`
1. [月鳞绮纪](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%23) `766.5K 🔥` `+390%`
1. [辛芷蕾 多邻国](https://s.weibo.com/weibo?q=%23%E8%BE%9B%E8%8A%B7%E8%95%BE%20%E5%A4%9A%E9%82%BB%E5%9B%BD%23) `208.8K 🔥` `+168%`
1. [壁上观](https://s.weibo.com/weibo?q=%23%E5%A3%81%E4%B8%8A%E8%A7%82%23) `207.6K 🔥` `+130%`
1. [沙特谴责伊朗](https://s.weibo.com/weibo?q=%23%E6%B2%99%E7%89%B9%E8%B0%B4%E8%B4%A3%E4%BC%8A%E6%9C%97%23) `206.9K 🔥` `+26%`
1. [多校试点班主任退群 (Pilot class teachers in many schools withdraw from the group)](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E6%A0%A1%E8%AF%95%E7%82%B9%E7%8F%AD%E4%B8%BB%E4%BB%BB%E9%80%80%E7%BE%A4%23) `1.1M 🔥`
1. [中国变压器在国外一器难求 (Chinese transformers are hard to find abroad)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%8F%98%E5%8E%8B%E5%99%A8%E5%9C%A8%E5%9B%BD%E5%A4%96%E4%B8%80%E5%99%A8%E9%9A%BE%E6%B1%82%23) `638.9K 🔥`
1. [鸡鸣寺樱花](https://s.weibo.com/weibo?q=%23%E9%B8%A1%E9%B8%A3%E5%AF%BA%E6%A8%B1%E8%8A%B1%23) `213.7K 🔥`
1. [逐玉反盗版声明 (Zhuyu Anti-Piracy Statement)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%8F%8D%E7%9B%97%E7%89%88%E5%A3%B0%E6%98%8E%23) `213.5K 🔥`
1. [小猫嫌弃自己脚臭](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E5%AB%8C%E5%BC%83%E8%87%AA%E5%B7%B1%E8%84%9A%E8%87%AD%23) `212.4K 🔥`
1. [以色列拦截伊朗导弹失败瞬间](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E6%8B%A6%E6%88%AA%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%A4%B1%E8%B4%A5%E7%9E%AC%E9%97%B4%23) `211.4K 🔥`
1. [梅姨在广州三元里落网为不实消息](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%9C%A8%E5%B9%BF%E5%B7%9E%E4%B8%89%E5%85%83%E9%87%8C%E8%90%BD%E7%BD%91%E4%B8%BA%E4%B8%8D%E5%AE%9E%E6%B6%88%E6%81%AF%23) `211.1K 🔥`
1. [徐若晗桃花坞第一大漏勺](https://s.weibo.com/weibo?q=%23%E5%BE%90%E8%8B%A5%E6%99%97%E6%A1%83%E8%8A%B1%E5%9D%9E%E7%AC%AC%E4%B8%80%E5%A4%A7%E6%BC%8F%E5%8B%BA%23) `209.7K 🔥`
1. [陈赫张子萱带女儿做客王祖蓝家](https://s.weibo.com/weibo?q=%23%E9%99%88%E8%B5%AB%E5%BC%A0%E5%AD%90%E8%90%B1%E5%B8%A6%E5%A5%B3%E5%84%BF%E5%81%9A%E5%AE%A2%E7%8E%8B%E7%A5%96%E8%93%9D%E5%AE%B6%23) `206.5K 🔥`
1. [国内油价将迎5连涨 (Domestic oil prices will rise for five consecutive years)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%86%85%E6%B2%B9%E4%BB%B7%E5%B0%86%E8%BF%8E5%E8%BF%9E%E6%B6%A8%23) `191.1K 🔥`
1. [英国男星死在普吉岛排水沟 (British actor dies in Phuket drain)](https://s.weibo.com/weibo?q=%23%E8%8B%B1%E5%9B%BD%E7%94%B7%E6%98%9F%E6%AD%BB%E5%9C%A8%E6%99%AE%E5%90%89%E5%B2%9B%E6%8E%92%E6%B0%B4%E6%B2%9F%23) `143.0K 🔥`
1. [含娃量最高的小长假要来了](https://s.weibo.com/weibo?q=%23%E5%90%AB%E5%A8%83%E9%87%8F%E6%9C%80%E9%AB%98%E7%9A%84%E5%B0%8F%E9%95%BF%E5%81%87%E8%A6%81%E6%9D%A5%E4%BA%86%23) `105.6K 🔥`
1. [王鸥 何九华](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B8%A5%20%E4%BD%95%E4%B9%9D%E5%8D%8E%23) `102.7K 🔥`
1. [高以翔前女友BeIIa官宣怀孕](https://s.weibo.com/weibo?q=%23%E9%AB%98%E4%BB%A5%E7%BF%94%E5%89%8D%E5%A5%B3%E5%8F%8BBeIIa%E5%AE%98%E5%AE%A3%E6%80%80%E5%AD%95%23) `100.5K 🔥`
1. [刚洗完澡别在浴室吹头发 (Don’t dry your hair in the bathroom right after you take a shower)](https://s.weibo.com/weibo?q=%23%E5%88%9A%E6%B4%97%E5%AE%8C%E6%BE%A1%E5%88%AB%E5%9C%A8%E6%B5%B4%E5%AE%A4%E5%90%B9%E5%A4%B4%E5%8F%91%23) `97.7K 🔥`
1. [半小时取鱼刺7小时修路震惊老外](https://s.weibo.com/weibo?q=%23%E5%8D%8A%E5%B0%8F%E6%97%B6%E5%8F%96%E9%B1%BC%E5%88%BA7%E5%B0%8F%E6%97%B6%E4%BF%AE%E8%B7%AF%E9%9C%87%E6%83%8A%E8%80%81%E5%A4%96%23) `85.7K 🔥`
1. [AI演员签约官宣](https://s.weibo.com/weibo?q=%23AI%E6%BC%94%E5%91%98%E7%AD%BE%E7%BA%A6%E5%AE%98%E5%AE%A3%23) `83.9K 🔥`
1. [逐玉的兵 不贪盗版](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%9A%84%E5%85%B5%20%E4%B8%8D%E8%B4%AA%E7%9B%97%E7%89%88%23) `67.5K 🔥`
1. [伊朗称只对敌人关闭霍尔木兹海峡 (Iran says it will only close Strait of Hormuz to enemies)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%8F%AA%E5%AF%B9%E6%95%8C%E4%BA%BA%E5%85%B3%E9%97%AD%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `61.4K 🔥`
1. [一诺职业病](https://s.weibo.com/weibo?q=%23%E4%B8%80%E8%AF%BA%E8%81%8C%E4%B8%9A%E7%97%85%23) `60.8K 🔥`
1. [鞠婧祎月鳞绮纪预约近200万](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%E9%A2%84%E7%BA%A6%E8%BF%91200%E4%B8%87%23) `60.3K 🔥`
1. [警方通报男子窜至某小区抢劫致1死 (The police reported that a man ran into a community and robbed one person to death.)](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E9%80%9A%E6%8A%A5%E7%94%B7%E5%AD%90%E7%AA%9C%E8%87%B3%E6%9F%90%E5%B0%8F%E5%8C%BA%E6%8A%A2%E5%8A%AB%E8%87%B41%E6%AD%BB%23) `255.0K 🔥` `-68%`
1. [陈慧敏怀孕了](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%85%A7%E6%95%8F%E6%80%80%E5%AD%95%E4%BA%86%23) `93.2K 🔥` `-22%`
1. [网友给逐玉的建议](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E7%BB%99%E9%80%90%E7%8E%89%E7%9A%84%E5%BB%BA%E8%AE%AE%23) `90.2K 🔥` `-44%`
1. [上班自备厕纸](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%AD%E8%87%AA%E5%A4%87%E5%8E%95%E7%BA%B8%23) `86.5K 🔥` `-38%`
1. [葛夕回怼复合要求](https://s.weibo.com/weibo?q=%23%E8%91%9B%E5%A4%95%E5%9B%9E%E6%80%BC%E5%A4%8D%E5%90%88%E8%A6%81%E6%B1%82%23) `86.2K 🔥` `-35%`
1. [广东横琴发布警情通报 (Guangdong Hengqin issues police advisory)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E6%A8%AA%E7%90%B4%E5%8F%91%E5%B8%83%E8%AD%A6%E6%83%85%E9%80%9A%E6%8A%A5%23) `80.7K 🔥` `-37%`
1. [瞿颖西班牙 王俊凯新加坡 (Qu Ying Spain Wang Junkai Singapore)](https://s.weibo.com/weibo?q=%23%E7%9E%BF%E9%A2%96%E8%A5%BF%E7%8F%AD%E7%89%99%20%E7%8E%8B%E4%BF%8A%E5%87%AF%E6%96%B0%E5%8A%A0%E5%9D%A1%23) `71.2K 🔥` `-40%`
1. [大熊猫摔到地上有多Q弹](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E7%86%8A%E7%8C%AB%E6%91%94%E5%88%B0%E5%9C%B0%E4%B8%8A%E6%9C%89%E5%A4%9AQ%E5%BC%B9%23) `57.4K 🔥` `-23%`
1. [希林娜依高伯克利七年没毕业](https://s.weibo.com/weibo?q=%23%E5%B8%8C%E6%9E%97%E5%A8%9C%E4%BE%9D%E9%AB%98%E4%BC%AF%E5%85%8B%E5%88%A9%E4%B8%83%E5%B9%B4%E6%B2%A1%E6%AF%95%E4%B8%9A%23) `52.1K 🔥` `-36%`

Updated at 2026-03-22 16:54:21

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
