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

1. [10日两会日程预告 (Preview of the schedule of the two sessions on the 10th)](https://s.weibo.com/weibo?q=%2310%E6%97%A5%E4%B8%A4%E4%BC%9A%E6%97%A5%E7%A8%8B%E9%A2%84%E5%91%8A%23) `746.3K 🔥` `NEW`
1. [未来5年中国要建设的重大工程](https://s.weibo.com/weibo?q=%23%E6%9C%AA%E6%9D%A55%E5%B9%B4%E4%B8%AD%E5%9B%BD%E8%A6%81%E5%BB%BA%E8%AE%BE%E7%9A%84%E9%87%8D%E5%A4%A7%E5%B7%A5%E7%A8%8B%23) `506.5K 🔥` `NEW`
1. [伊朗称24小时内摧毁4部萨德雷达](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B024%E5%B0%8F%E6%97%B6%E5%86%85%E6%91%A7%E6%AF%814%E9%83%A8%E8%90%A8%E5%BE%B7%E9%9B%B7%E8%BE%BE%23) `100.8K 🔥` `NEW`
1. [鸡鸣寺消息树今年失约](https://s.weibo.com/weibo?q=%23%E9%B8%A1%E9%B8%A3%E5%AF%BA%E6%B6%88%E6%81%AF%E6%A0%91%E4%BB%8A%E5%B9%B4%E5%A4%B1%E7%BA%A6%23) `83.4K 🔥` `NEW`
1. [藏海传横扫SMG](https://s.weibo.com/weibo?q=%23%E8%97%8F%E6%B5%B7%E4%BC%A0%E6%A8%AA%E6%89%ABSMG%23) `68.1K 🔥` `NEW`
1. [谢征强吻长玉后的台词](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E5%BC%BA%E5%90%BB%E9%95%BF%E7%8E%89%E5%90%8E%E7%9A%84%E5%8F%B0%E8%AF%8D%23) `62.4K 🔥` `NEW`
1. [历届SMG视帝 (Previous SMG TV Emperors)](https://s.weibo.com/weibo?q=%23%E5%8E%86%E5%B1%8ASMG%E8%A7%86%E5%B8%9D%23) `507.3K 🔥` `+559%`
1. [BeADreamer新濠天地品牌新章 (BeADreamer City of Dreams brand new chapter)](https://s.weibo.com/weibo?q=%23BeADreamer%E6%96%B0%E6%BF%A0%E5%A4%A9%E5%9C%B0%E5%93%81%E7%89%8C%E6%96%B0%E7%AB%A0%23) `491.6K 🔥` `+222%`
1. [教师法](https://s.weibo.com/weibo?q=%23%E6%95%99%E5%B8%88%E6%B3%95%23) `429.3K 🔥` `+248%`
1. [委员谈如何提高居民财产收入](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E8%B0%88%E5%A6%82%E4%BD%95%E6%8F%90%E9%AB%98%E5%B1%85%E6%B0%91%E8%B4%A2%E4%BA%A7%E6%94%B6%E5%85%A5%23) `409.3K 🔥` `+23%`
1. [普京特朗普再通话](https://s.weibo.com/weibo?q=%23%E6%99%AE%E4%BA%AC%E7%89%B9%E6%9C%97%E6%99%AE%E5%86%8D%E9%80%9A%E8%AF%9D%23) `378.9K 🔥` `+223%`
1. [在韩剧里看中国人演中国人](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E9%9F%A9%E5%89%A7%E9%87%8C%E7%9C%8B%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%BC%94%E4%B8%AD%E5%9B%BD%E4%BA%BA%23) `322.6K 🔥` `+30%`
1. [千万不要在洗澡时做人脸认证 (Never do face authentication while taking a shower)](https://s.weibo.com/weibo?q=%23%E5%8D%83%E4%B8%87%E4%B8%8D%E8%A6%81%E5%9C%A8%E6%B4%97%E6%BE%A1%E6%97%B6%E5%81%9A%E4%BA%BA%E8%84%B8%E8%AE%A4%E8%AF%81%23) `185.1K 🔥` `+38%`
1. [91岁女儿受委屈向113岁妈妈哭诉 (91-year-old daughter cries to her 113-year-old mother after being wronged)](https://s.weibo.com/weibo?q=%2391%E5%B2%81%E5%A5%B3%E5%84%BF%E5%8F%97%E5%A7%94%E5%B1%88%E5%90%91113%E5%B2%81%E5%A6%88%E5%A6%88%E5%93%AD%E8%AF%89%23) `179.7K 🔥` `+42%`
1. [医生提醒不要模仿Ella真空腹 (Doctor reminds not to imitate Ella’s vacuum abdomen)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E6%8F%90%E9%86%92%E4%B8%8D%E8%A6%81%E6%A8%A1%E4%BB%BFElla%E7%9C%9F%E7%A9%BA%E8%85%B9%23) `173.9K 🔥` `+43%`
1. [张艺兴处于术后康复阶段 (Zhang Yixing is in the recovery stage after surgery)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%89%BA%E5%85%B4%E5%A4%84%E4%BA%8E%E6%9C%AF%E5%90%8E%E5%BA%B7%E5%A4%8D%E9%98%B6%E6%AE%B5%23) `160.9K 🔥` `+34%`
1. [伊朗新领袖释放强硬信号](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%96%B0%E9%A2%86%E8%A2%96%E9%87%8A%E6%94%BE%E5%BC%BA%E7%A1%AC%E4%BF%A1%E5%8F%B7%23) `159.1K 🔥` `+44%`
1. [小孩打针视频外网播放破两千万](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A9%E6%89%93%E9%92%88%E8%A7%86%E9%A2%91%E5%A4%96%E7%BD%91%E6%92%AD%E6%94%BE%E7%A0%B4%E4%B8%A4%E5%8D%83%E4%B8%87%23) `154.4K 🔥` `+34%`
1. [卢昱晓走红毯忘记把暖宝宝拿下来了 (Lu Yuxiao forgot to take off the warm baby while walking on the red carpet)](https://s.weibo.com/weibo?q=%23%E5%8D%A2%E6%98%B1%E6%99%93%E8%B5%B0%E7%BA%A2%E6%AF%AF%E5%BF%98%E8%AE%B0%E6%8A%8A%E6%9A%96%E5%AE%9D%E5%AE%9D%E6%8B%BF%E4%B8%8B%E6%9D%A5%E4%BA%86%23) `147.6K 🔥` `+37%`
1. [宇宙闪烁请注意](https://s.weibo.com/weibo?q=%23%E5%AE%87%E5%AE%99%E9%97%AA%E7%83%81%E8%AF%B7%E6%B3%A8%E6%84%8F%23) `130.9K 🔥` `+129%`
1. [第一批养虾人已经失眠了](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%89%B9%E5%85%BB%E8%99%BE%E4%BA%BA%E5%B7%B2%E7%BB%8F%E5%A4%B1%E7%9C%A0%E4%BA%86%23) `106.0K 🔥` `+34%`
1. [韩国很火的狗布奇诺](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E5%BE%88%E7%81%AB%E7%9A%84%E7%8B%97%E5%B8%83%E5%A5%87%E8%AF%BA%23) `94.5K 🔥` `+51%`
1. [香奈儿大秀](https://s.weibo.com/weibo?q=%23%E9%A6%99%E5%A5%88%E5%84%BF%E5%A4%A7%E7%A7%80%23) `87.8K 🔥` `+31%`
1. [13岁中国小孩哥夺得世界街舞冠军 (13-year-old Chinese kid wins world hip-hop dance championship)](https://s.weibo.com/weibo?q=%2313%E5%B2%81%E4%B8%AD%E5%9B%BD%E5%B0%8F%E5%AD%A9%E5%93%A5%E5%A4%BA%E5%BE%97%E4%B8%96%E7%95%8C%E8%A1%97%E8%88%9E%E5%86%A0%E5%86%9B%23) `1.0M 🔥`
1. [2026这些区域将迎发展 (These areas will welcome development in 2026)](https://s.weibo.com/weibo?q=%232026%E8%BF%99%E4%BA%9B%E5%8C%BA%E5%9F%9F%E5%B0%86%E8%BF%8E%E5%8F%91%E5%B1%95%23) `567.0K 🔥`
1. [美军精锐部队突然异动 (The elite U.S. troops suddenly moved)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E7%B2%BE%E9%94%90%E9%83%A8%E9%98%9F%E7%AA%81%E7%84%B6%E5%BC%82%E5%8A%A8%23) `505.8K 🔥`
1. [巴黎时装周 (paris fashion week)](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%23) `487.3K 🔥`
1. [华裔选手称谷爱凌有权代表中国出战 (Chinese players say Gu Ailing has the right to represent China)](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E8%A3%94%E9%80%89%E6%89%8B%E7%A7%B0%E8%B0%B7%E7%88%B1%E5%87%8C%E6%9C%89%E6%9D%83%E4%BB%A3%E8%A1%A8%E4%B8%AD%E5%9B%BD%E5%87%BA%E6%88%98%23) `463.5K 🔥`
1. [1亿美元委内瑞拉黄金运抵美国](https://s.weibo.com/weibo?q=%231%E4%BA%BF%E7%BE%8E%E5%85%83%E5%A7%94%E5%86%85%E7%91%9E%E6%8B%89%E9%BB%84%E9%87%91%E8%BF%90%E6%8A%B5%E7%BE%8E%E5%9B%BD%23) `265.6K 🔥`
1. [胖东来12名店长共分2.4亿资产利润 (Fat Donglai’s 12 store managers shared a total of 240 million in asset profits)](https://s.weibo.com/weibo?q=%23%E8%83%96%E4%B8%9C%E6%9D%A512%E5%90%8D%E5%BA%97%E9%95%BF%E5%85%B1%E5%88%862.4%E4%BA%BF%E8%B5%84%E4%BA%A7%E5%88%A9%E6%B6%A6%23) `195.7K 🔥`
1. [孙俪SMG视后](https://s.weibo.com/weibo?q=%23%E5%AD%99%E4%BF%AASMG%E8%A7%86%E5%90%8E%23) `188.5K 🔥`
1. [伊朗警告油价或超200美元 (Iran warns oil prices may exceed $200)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%AD%A6%E5%91%8A%E6%B2%B9%E4%BB%B7%E6%88%96%E8%B6%85200%E7%BE%8E%E5%85%83%23) `126.0K 🔥`
1. [6个月宝宝吃辅食被香得一激灵](https://s.weibo.com/weibo?q=%236%E4%B8%AA%E6%9C%88%E5%AE%9D%E5%AE%9D%E5%90%83%E8%BE%85%E9%A3%9F%E8%A2%AB%E9%A6%99%E5%BE%97%E4%B8%80%E6%BF%80%E7%81%B5%23) `108.2K 🔥`
1. [国家队教练教你快速瘦肚子的方法 (The national team coach teaches you how to lose weight quickly)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E5%AE%B6%E9%98%9F%E6%95%99%E7%BB%83%E6%95%99%E4%BD%A0%E5%BF%AB%E9%80%9F%E7%98%A6%E8%82%9A%E5%AD%90%E7%9A%84%E6%96%B9%E6%B3%95%23) `101.1K 🔥`
1. [伊朗发起第32波打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC32%E6%B3%A2%E6%89%93%E5%87%BB%23) `91.5K 🔥`
1. [王一博出席香奈儿秀场](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%87%BA%E5%B8%AD%E9%A6%99%E5%A5%88%E5%84%BF%E7%A7%80%E5%9C%BA%23) `80.8K 🔥`
1. [油价将上调加油站员工发声 (Gas prices will rise, gas station employees speak out)](https://s.weibo.com/weibo?q=%23%E6%B2%B9%E4%BB%B7%E5%B0%86%E4%B8%8A%E8%B0%83%E5%8A%A0%E6%B2%B9%E7%AB%99%E5%91%98%E5%B7%A5%E5%8F%91%E5%A3%B0%23) `75.4K 🔥`
1. [日本或陷入无油可用困境 (Japan may be in trouble with no oil available)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E6%88%96%E9%99%B7%E5%85%A5%E6%97%A0%E6%B2%B9%E5%8F%AF%E7%94%A8%E5%9B%B0%E5%A2%83%23) `71.3K 🔥`
1. [张艺兴工作室声明 (Statement from Zhang Yixing Studio)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%89%BA%E5%85%B4%E5%B7%A5%E4%BD%9C%E5%AE%A4%E5%A3%B0%E6%98%8E%23) `70.8K 🔥`
1. [哥伦比亚女子滑滑梯猛烈撞墙后身亡 (Colombian woman dies after hitting wall on slide)](https://s.weibo.com/weibo?q=%23%E5%93%A5%E4%BC%A6%E6%AF%94%E4%BA%9A%E5%A5%B3%E5%AD%90%E6%BB%91%E6%BB%91%E6%A2%AF%E7%8C%9B%E7%83%88%E6%92%9E%E5%A2%99%E5%90%8E%E8%BA%AB%E4%BA%A1%23) `68.9K 🔥`
1. [杨超越 中国有自己的张元英 (Yang Chaoyue China has its own Zhang Yuanying)](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E8%B6%85%E8%B6%8A%20%E4%B8%AD%E5%9B%BD%E6%9C%89%E8%87%AA%E5%B7%B1%E7%9A%84%E5%BC%A0%E5%85%83%E8%8B%B1%23) `65.1K 🔥`
1. [华裔花滑选手称批评谷爱凌的人虚伪](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E8%A3%94%E8%8A%B1%E6%BB%91%E9%80%89%E6%89%8B%E7%A7%B0%E6%89%B9%E8%AF%84%E8%B0%B7%E7%88%B1%E5%87%8C%E7%9A%84%E4%BA%BA%E8%99%9A%E4%BC%AA%23) `63.0K 🔥`
1. [代表建议升级育儿补贴](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%BB%BA%E8%AE%AE%E5%8D%87%E7%BA%A7%E8%82%B2%E5%84%BF%E8%A1%A5%E8%B4%B4%23) `58.1K 🔥`
1. [白鹿别把白敬亭扇感冒了 (Bai Lu, don’t fan Bai Jingting to catch a cold.)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%88%AB%E6%8A%8A%E7%99%BD%E6%95%AC%E4%BA%AD%E6%89%87%E6%84%9F%E5%86%92%E4%BA%86%23) `57.4K 🔥`
1. [镖人](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `245.8K 🔥` `-33%`
1. [农业农村部部长建议大家少吃点油 (The Minister of Agriculture and Rural Affairs advises everyone to eat less oil)](https://s.weibo.com/weibo?q=%23%E5%86%9C%E4%B8%9A%E5%86%9C%E6%9D%91%E9%83%A8%E9%83%A8%E9%95%BF%E5%BB%BA%E8%AE%AE%E5%A4%A7%E5%AE%B6%E5%B0%91%E5%90%83%E7%82%B9%E6%B2%B9%23) `166.0K 🔥` `-75%`
1. [伊朗重型导弹打击美以目标 (Iran's heavy missile strikes US and Israeli targets)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%87%8D%E5%9E%8B%E5%AF%BC%E5%BC%B9%E6%89%93%E5%87%BB%E7%BE%8E%E4%BB%A5%E7%9B%AE%E6%A0%87%23) `153.6K 🔥` `-30%`
1. [最高法成绩单新亮点 (New Highlights of the Supreme Court’s Report Card)](https://s.weibo.com/weibo?q=%23%E6%9C%80%E9%AB%98%E6%B3%95%E6%88%90%E7%BB%A9%E5%8D%95%E6%96%B0%E4%BA%AE%E7%82%B9%23) `85.3K 🔥` `-82%`
1. [逐玉热度 (The popularity of chasing jade)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%83%AD%E5%BA%A6%23) `81.5K 🔥` `-28%`

Updated at 2026-03-10 08:00:05

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
