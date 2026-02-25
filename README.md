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

1. [宝马7系降价约27万 (BMW 7 Series price cut by about 270,000)](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E9%A9%AC7%E7%B3%BB%E9%99%8D%E4%BB%B7%E7%BA%A627%E4%B8%87%23) `832.3K 🔥` `NEW`
1. [刘亦菲晒出光影大片](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E6%99%92%E5%87%BA%E5%85%89%E5%BD%B1%E5%A4%A7%E7%89%87%23) `541.3K 🔥` `NEW`
1. [女子返程堵车偶遇10年未见初恋](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%BF%94%E7%A8%8B%E5%A0%B5%E8%BD%A6%E5%81%B6%E9%81%8710%E5%B9%B4%E6%9C%AA%E8%A7%81%E5%88%9D%E6%81%8B%23) `483.3K 🔥` `NEW`
1. [女子在加油站人肉插队躺后车引擎盖](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%9C%A8%E5%8A%A0%E6%B2%B9%E7%AB%99%E4%BA%BA%E8%82%89%E6%8F%92%E9%98%9F%E8%BA%BA%E5%90%8E%E8%BD%A6%E5%BC%95%E6%93%8E%E7%9B%96%23) `466.8K 🔥` `NEW`
1. [专家在香港发现文物证实夏朝存在](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E5%9C%A8%E9%A6%99%E6%B8%AF%E5%8F%91%E7%8E%B0%E6%96%87%E7%89%A9%E8%AF%81%E5%AE%9E%E5%A4%8F%E6%9C%9D%E5%AD%98%E5%9C%A8%23) `359.2K 🔥` `NEW`
1. [月经一定程度上能反映气血状况](https://s.weibo.com/weibo?q=%23%E6%9C%88%E7%BB%8F%E4%B8%80%E5%AE%9A%E7%A8%8B%E5%BA%A6%E4%B8%8A%E8%83%BD%E5%8F%8D%E6%98%A0%E6%B0%94%E8%A1%80%E7%8A%B6%E5%86%B5%23) `179.9K 🔥` `NEW`
1. [平顶山打人夫妻先后殴打4人](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E9%A1%B6%E5%B1%B1%E6%89%93%E4%BA%BA%E5%A4%AB%E5%A6%BB%E5%85%88%E5%90%8E%E6%AE%B4%E6%89%934%E4%BA%BA%23) `177.3K 🔥` `NEW`
1. [网友偶遇谢霆锋狄波拉逛街](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E5%81%B6%E9%81%87%E8%B0%A2%E9%9C%86%E9%94%8B%E7%8B%84%E6%B3%A2%E6%8B%89%E9%80%9B%E8%A1%97%23) `172.6K 🔥` `NEW`
1. [用4年感受到了命运的推背感](https://s.weibo.com/weibo?q=%23%E7%94%A84%E5%B9%B4%E6%84%9F%E5%8F%97%E5%88%B0%E4%BA%86%E5%91%BD%E8%BF%90%E7%9A%84%E6%8E%A8%E8%83%8C%E6%84%9F%23) `170.6K 🔥` `NEW`
1. [远嫁女子控诉老公陪回娘家待不住](https://s.weibo.com/weibo?q=%23%E8%BF%9C%E5%AB%81%E5%A5%B3%E5%AD%90%E6%8E%A7%E8%AF%89%E8%80%81%E5%85%AC%E9%99%AA%E5%9B%9E%E5%A8%98%E5%AE%B6%E5%BE%85%E4%B8%8D%E4%BD%8F%23) `143.3K 🔥` `NEW`
1. [美军11架F22战机抵达以色列 (11 US F22 fighter jets arrive in Israel)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B11%E6%9E%B6F22%E6%88%98%E6%9C%BA%E6%8A%B5%E8%BE%BE%E4%BB%A5%E8%89%B2%E5%88%97%23) `132.4K 🔥` `NEW`
1. [62岁阿姨返程堵车久坐19小时进ICU](https://s.weibo.com/weibo?q=%2362%E5%B2%81%E9%98%BF%E5%A7%A8%E8%BF%94%E7%A8%8B%E5%A0%B5%E8%BD%A6%E4%B9%85%E5%9D%9019%E5%B0%8F%E6%97%B6%E8%BF%9BICU%23) `130.8K 🔥` `NEW`
1. [一种过期了就不能吃的食物](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%A7%8D%E8%BF%87%E6%9C%9F%E4%BA%86%E5%B0%B1%E4%B8%8D%E8%83%BD%E5%90%83%E7%9A%84%E9%A3%9F%E7%89%A9%23) `114.2K 🔥` `NEW`
1. [碧血蝉](https://s.weibo.com/weibo?q=%23%E7%A2%A7%E8%A1%80%E8%9D%89%23) `96.8K 🔥` `NEW`
1. [小孩骑马受惊爸爸怒扇动物园员工](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A9%E9%AA%91%E9%A9%AC%E5%8F%97%E6%83%8A%E7%88%B8%E7%88%B8%E6%80%92%E6%89%87%E5%8A%A8%E7%89%A9%E5%9B%AD%E5%91%98%E5%B7%A5%23) `85.1K 🔥` `NEW`
1. [正月初九](https://s.weibo.com/weibo?q=%23%E6%AD%A3%E6%9C%88%E5%88%9D%E4%B9%9D%23) `77.1K 🔥` `NEW`
1. [建议这4类人多吃点香菜](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E8%BF%994%E7%B1%BB%E4%BA%BA%E5%A4%9A%E5%90%83%E7%82%B9%E9%A6%99%E8%8F%9C%23) `75.9K 🔥` `NEW`
1. [为什么不能在白纸上签名字](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E4%B8%8D%E8%83%BD%E5%9C%A8%E7%99%BD%E7%BA%B8%E4%B8%8A%E7%AD%BE%E5%90%8D%E5%AD%97%23) `72.5K 🔥` `NEW`
1. [易烊千玺凭演技惊艳韩国人](https://s.weibo.com/weibo?q=%23%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E5%87%AD%E6%BC%94%E6%8A%80%E6%83%8A%E8%89%B3%E9%9F%A9%E5%9B%BD%E4%BA%BA%23) `65.9K 🔥` `NEW`
1. [初九拜天公](https://s.weibo.com/weibo?q=%23%E5%88%9D%E4%B9%9D%E6%8B%9C%E5%A4%A9%E5%85%AC%23) `65.8K 🔥` `NEW`
1. [阿富汗巴基斯坦爆发冲突 (Conflict breaks out in Afghanistan and Pakistan)](https://s.weibo.com/weibo?q=%23%E9%98%BF%E5%AF%8C%E6%B1%97%E5%B7%B4%E5%9F%BA%E6%96%AF%E5%9D%A6%E7%88%86%E5%8F%91%E5%86%B2%E7%AA%81%23) `63.8K 🔥` `NEW`
1. [不内耗的人脑子里是这样想的 (This is what people who are not internally thinking think like this)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E5%86%85%E8%80%97%E7%9A%84%E4%BA%BA%E8%84%91%E5%AD%90%E9%87%8C%E6%98%AF%E8%BF%99%E6%A0%B7%E6%83%B3%E7%9A%84%23) `229.4K 🔥` `+56%`
1. [官方回应继父搂腰亲吻女童](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E5%9B%9E%E5%BA%94%E7%BB%A7%E7%88%B6%E6%90%82%E8%85%B0%E4%BA%B2%E5%90%BB%E5%A5%B3%E7%AB%A5%23) `189.2K 🔥` `+53%`
1. [吴昕自曝录制快本三四个月还是想走 (Wu Xin reveals that she still wants to leave after three or four months of recording the album)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E8%87%AA%E6%9B%9D%E5%BD%95%E5%88%B6%E5%BF%AB%E6%9C%AC%E4%B8%89%E5%9B%9B%E4%B8%AA%E6%9C%88%E8%BF%98%E6%98%AF%E6%83%B3%E8%B5%B0%23) `186.3K 🔥` `+53%`
1. [被继父亲吻女童已被生父接回 (The girl who was kissed by her stepfather has been taken back by her biological father)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%BB%A7%E7%88%B6%E4%BA%B2%E5%90%BB%E5%A5%B3%E7%AB%A5%E5%B7%B2%E8%A2%AB%E7%94%9F%E7%88%B6%E6%8E%A5%E5%9B%9E%23) `183.5K 🔥` `+139%`
1. [米兰偶遇杨幂逛店](https://s.weibo.com/weibo?q=%23%E7%B1%B3%E5%85%B0%E5%81%B6%E9%81%87%E6%9D%A8%E5%B9%82%E9%80%9B%E5%BA%97%23) `174.0K 🔥` `+200%`
1. [Gucci出发图](https://s.weibo.com/weibo?q=%23Gucci%E5%87%BA%E5%8F%91%E5%9B%BE%23) `170.4K 🔥` `+212%`
1. [吴佳尼被认识3天的富二代求婚 (Wu Jiani was proposed to by a rich second generation whom she had known for 3 days)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%B3%E5%B0%BC%E8%A2%AB%E8%AE%A4%E8%AF%863%E5%A4%A9%E7%9A%84%E5%AF%8C%E4%BA%8C%E4%BB%A3%E6%B1%82%E5%A9%9A%23) `141.1K 🔥` `+46%`
1. [iPhone18Pro深红色](https://s.weibo.com/weibo?q=%23iPhone18Pro%E6%B7%B1%E7%BA%A2%E8%89%B2%23) `115.2K 🔥` `+21%`
1. [丁程鑫一个人直播吃蛋糕](https://s.weibo.com/weibo?q=%23%E4%B8%81%E7%A8%8B%E9%91%AB%E4%B8%80%E4%B8%AA%E4%BA%BA%E7%9B%B4%E6%92%AD%E5%90%83%E8%9B%8B%E7%B3%95%23) `106.1K 🔥` `+40%`
1. [经常熬夜是在挑战甲状腺极限 (Staying up late often challenges the limits of your thyroid gland)](https://s.weibo.com/weibo?q=%23%E7%BB%8F%E5%B8%B8%E7%86%AC%E5%A4%9C%E6%98%AF%E5%9C%A8%E6%8C%91%E6%88%98%E7%94%B2%E7%8A%B6%E8%85%BA%E6%9E%81%E9%99%90%23) `93.8K 🔥` `+72%`
1. [欧冠](https://s.weibo.com/weibo?q=%23%E6%AC%A7%E5%86%A0%23) `71.1K 🔥` `+29%`
1. [平顶山再通报打人事件](https://s.weibo.com/weibo?q=%23%E5%B9%B3%E9%A1%B6%E5%B1%B1%E5%86%8D%E9%80%9A%E6%8A%A5%E6%89%93%E4%BA%BA%E4%BA%8B%E4%BB%B6%23) `1.2M 🔥`
1. [九组数据感受万马奔腾的活力春节](https://s.weibo.com/weibo?q=%23%E4%B9%9D%E7%BB%84%E6%95%B0%E6%8D%AE%E6%84%9F%E5%8F%97%E4%B8%87%E9%A9%AC%E5%A5%94%E8%85%BE%E7%9A%84%E6%B4%BB%E5%8A%9B%E6%98%A5%E8%8A%82%23) `690.4K 🔥`
1. [王楚钦鹰眼挑战失败 (Wang Chuqin’s Eagle Eye challenge failed)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E9%B9%B0%E7%9C%BC%E6%8C%91%E6%88%98%E5%A4%B1%E8%B4%A5%23) `213.4K 🔥`
1. [牛奶灌溉草莓卖出360元天价 (Strawberries irrigated with milk sell for a whopping 360 yuan)](https://s.weibo.com/weibo?q=%23%E7%89%9B%E5%A5%B6%E7%81%8C%E6%BA%89%E8%8D%89%E8%8E%93%E5%8D%96%E5%87%BA360%E5%85%83%E5%A4%A9%E4%BB%B7%23) `189.8K 🔥`
1. [江西一家人自驾返程出车祸1死4伤](https://s.weibo.com/weibo?q=%23%E6%B1%9F%E8%A5%BF%E4%B8%80%E5%AE%B6%E4%BA%BA%E8%87%AA%E9%A9%BE%E8%BF%94%E7%A8%8B%E5%87%BA%E8%BD%A6%E7%A5%B81%E6%AD%BB4%E4%BC%A4%23) `134.6K 🔥`
1. [谷爱凌妈妈谷燕的人生轨迹 (The life trajectory of Gu Ailing’s mother Gu Yan)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A6%88%E5%A6%88%E8%B0%B7%E7%87%95%E7%9A%84%E4%BA%BA%E7%94%9F%E8%BD%A8%E8%BF%B9%23) `123.9K 🔥`
1. [掉在床缝里的物品有救了](https://s.weibo.com/weibo?q=%23%E6%8E%89%E5%9C%A8%E5%BA%8A%E7%BC%9D%E9%87%8C%E7%9A%84%E7%89%A9%E5%93%81%E6%9C%89%E6%95%91%E4%BA%86%23) `102.1K 🔥`
1. [西安一市民除夕夜被AI给骂了 (A Xi'an citizen was scolded by AI on New Year's Eve)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%AE%89%E4%B8%80%E5%B8%82%E6%B0%91%E9%99%A4%E5%A4%95%E5%A4%9C%E8%A2%ABAI%E7%BB%99%E9%AA%82%E4%BA%86%23) `101.5K 🔥`
1. [地球超新鲜2 (earth fresh 2)](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E7%90%83%E8%B6%85%E6%96%B0%E9%B2%9C2%23) `95.4K 🔥`
1. [飞驰人生3彩蛋藏太深](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B0%E4%BA%BA%E7%94%9F3%E5%BD%A9%E8%9B%8B%E8%97%8F%E5%A4%AA%E6%B7%B1%23) `89.7K 🔥`
1. [王安宇多给内娱留几个霸总吧](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E5%A4%9A%E7%BB%99%E5%86%85%E5%A8%B1%E7%95%99%E5%87%A0%E4%B8%AA%E9%9C%B8%E6%80%BB%E5%90%A7%23) `86.0K 🔥`
1. [剑来 魔改 (Jian Lai Mo Gai)](https://s.weibo.com/weibo?q=%23%E5%89%91%E6%9D%A5%20%E9%AD%94%E6%94%B9%23) `83.6K 🔥`
1. [开工第一天被通知放假10天](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%B7%A5%E7%AC%AC%E4%B8%80%E5%A4%A9%E8%A2%AB%E9%80%9A%E7%9F%A5%E6%94%BE%E5%81%8710%E5%A4%A9%23) `72.2K 🔥`
1. [杨洋的不让江山妆造 (Yang Yang’s Don’t Let Jiangshan Make Up)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E7%9A%84%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%A6%86%E9%80%A0%23) `70.7K 🔥`
1. [被炸身亡男子从哪里买的烟花 (Where did the man who died in the bombing buy the fireworks?)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E7%82%B8%E8%BA%AB%E4%BA%A1%E7%94%B7%E5%AD%90%E4%BB%8E%E5%93%AA%E9%87%8C%E4%B9%B0%E7%9A%84%E7%83%9F%E8%8A%B1%23) `63.8K 🔥`
1. [惊蛰无声 (Waking of Insects is silent)](https://s.weibo.com/weibo?q=%23%E6%83%8A%E8%9B%B0%E6%97%A0%E5%A3%B0%23) `369.4K 🔥` `-50%`
1. [将门独后](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%23) `104.6K 🔥` `-25%`
1. [俄乌冲突](https://s.weibo.com/weibo?q=%23%E4%BF%84%E4%B9%8C%E5%86%B2%E7%AA%81%23) `74.0K 🔥` `-34%`

Updated at 2026-02-25 09:14:47

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
