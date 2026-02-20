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

1. [每一位中国冰雪健儿都闪闪发光 (Every Chinese ice and snow athlete shines brightly)](https://s.weibo.com/weibo?q=%23%E6%AF%8F%E4%B8%80%E4%BD%8D%E4%B8%AD%E5%9B%BD%E5%86%B0%E9%9B%AA%E5%81%A5%E5%84%BF%E9%83%BD%E9%97%AA%E9%97%AA%E5%8F%91%E5%85%89%23) `614.0K 🔥` `NEW`
1. [无接触事故扶老人女生该不该担责](https://s.weibo.com/weibo?q=%23%E6%97%A0%E6%8E%A5%E8%A7%A6%E4%BA%8B%E6%95%85%E6%89%B6%E8%80%81%E4%BA%BA%E5%A5%B3%E7%94%9F%E8%AF%A5%E4%B8%8D%E8%AF%A5%E6%8B%85%E8%B4%A3%23) `302.1K 🔥` `NEW`
1. [王腾回应换iPhone17](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%85%BE%E5%9B%9E%E5%BA%94%E6%8D%A2iPhone17%23) `193.4K 🔥` `NEW`
1. [解放军有效处置美军在黄海活动](https://s.weibo.com/weibo?q=%23%E8%A7%A3%E6%94%BE%E5%86%9B%E6%9C%89%E6%95%88%E5%A4%84%E7%BD%AE%E7%BE%8E%E5%86%9B%E5%9C%A8%E9%BB%84%E6%B5%B7%E6%B4%BB%E5%8A%A8%23) `136.4K 🔥` `NEW`
1. [充电器一拔又是一年](https://s.weibo.com/weibo?q=%23%E5%85%85%E7%94%B5%E5%99%A8%E4%B8%80%E6%8B%94%E5%8F%88%E6%98%AF%E4%B8%80%E5%B9%B4%23) `136.0K 🔥` `NEW`
1. [奶奶养大的孩子看不得祝绪丹这段](https://s.weibo.com/weibo?q=%23%E5%A5%B6%E5%A5%B6%E5%85%BB%E5%A4%A7%E7%9A%84%E5%AD%A9%E5%AD%90%E7%9C%8B%E4%B8%8D%E5%BE%97%E7%A5%9D%E7%BB%AA%E4%B8%B9%E8%BF%99%E6%AE%B5%23) `123.6K 🔥` `NEW`
1. [穆祉丞 海口](https://s.weibo.com/weibo?q=%23%E7%A9%86%E7%A5%89%E4%B8%9E%20%E6%B5%B7%E5%8F%A3%23) `111.4K 🔥` `NEW`
1. [尹锡悦称无法接受被判无期徒刑](https://s.weibo.com/weibo?q=%23%E5%B0%B9%E9%94%A1%E6%82%A6%E7%A7%B0%E6%97%A0%E6%B3%95%E6%8E%A5%E5%8F%97%E8%A2%AB%E5%88%A4%E6%97%A0%E6%9C%9F%E5%BE%92%E5%88%91%23) `101.6K 🔥` `NEW`
1. [张元英ins更新](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%85%83%E8%8B%B1ins%E6%9B%B4%E6%96%B0%23) `91.5K 🔥` `NEW`
1. [剧版镖人](https://s.weibo.com/weibo?q=%23%E5%89%A7%E7%89%88%E9%95%96%E4%BA%BA%23) `91.1K 🔥` `NEW`
1. [香港黄金交易所展出近1吨金条银条 (Hong Kong Gold Exchange displays nearly 1 ton of gold and silver bars)](https://s.weibo.com/weibo?q=%23%E9%A6%99%E6%B8%AF%E9%BB%84%E9%87%91%E4%BA%A4%E6%98%93%E6%89%80%E5%B1%95%E5%87%BA%E8%BF%911%E5%90%A8%E9%87%91%E6%9D%A1%E9%93%B6%E6%9D%A1%23) `78.4K 🔥` `NEW`
1. [陈妍希回应小笼包](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A6%8D%E5%B8%8C%E5%9B%9E%E5%BA%94%E5%B0%8F%E7%AC%BC%E5%8C%85%23) `77.2K 🔥` `NEW`
1. [美国冰壶帅哥做吃播爆红](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%86%B0%E5%A3%B6%E5%B8%85%E5%93%A5%E5%81%9A%E5%90%83%E6%92%AD%E7%88%86%E7%BA%A2%23) `71.6K 🔥` `NEW`
1. [提现膝下黄金](https://s.weibo.com/weibo?q=%23%E6%8F%90%E7%8E%B0%E8%86%9D%E4%B8%8B%E9%BB%84%E9%87%91%23) `67.7K 🔥` `NEW`
1. [容止 谢景行 (Rong Zhi Xie Jingxing)](https://s.weibo.com/weibo?q=%23%E5%AE%B9%E6%AD%A2%20%E8%B0%A2%E6%99%AF%E8%A1%8C%23) `1.1M 🔥` `+27%`
1. [80岁老人把金手镯做成5枚金戒指](https://s.weibo.com/weibo?q=%2380%E5%B2%81%E8%80%81%E4%BA%BA%E6%8A%8A%E9%87%91%E6%89%8B%E9%95%AF%E5%81%9A%E6%88%905%E6%9E%9A%E9%87%91%E6%88%92%E6%8C%87%23) `763.1K 🔥` `+332%`
1. [将门独后官宣王鹤棣孟子义 (The only queen in the general family announced Wang Hedi and Meng Ziyi)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%AE%98%E5%AE%A3%E7%8E%8B%E9%B9%A4%E6%A3%A3%E5%AD%9F%E5%AD%90%E4%B9%89%23) `539.6K 🔥` `+22%`
1. [露上牙说话和露下牙说话的区别](https://s.weibo.com/weibo?q=%23%E9%9C%B2%E4%B8%8A%E7%89%99%E8%AF%B4%E8%AF%9D%E5%92%8C%E9%9C%B2%E4%B8%8B%E7%89%99%E8%AF%B4%E8%AF%9D%E7%9A%84%E5%8C%BA%E5%88%AB%23) `532.6K 🔥` `+75%`
1. [苏翊鸣连考古都是高清的](https://s.weibo.com/weibo?q=%23%E8%8B%8F%E7%BF%8A%E9%B8%A3%E8%BF%9E%E8%80%83%E5%8F%A4%E9%83%BD%E6%98%AF%E9%AB%98%E6%B8%85%E7%9A%84%23) `216.7K 🔥` `+29%`
1. [宁忠岩金牌含金量恐怖如斯](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BF%A0%E5%B2%A9%E9%87%91%E7%89%8C%E5%90%AB%E9%87%91%E9%87%8F%E6%81%90%E6%80%96%E5%A6%82%E6%96%AF%23) `199.7K 🔥` `+69%`
1. [吴京 我的夫人姓谢](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%20%E6%88%91%E7%9A%84%E5%A4%AB%E4%BA%BA%E5%A7%93%E8%B0%A2%23) `354.4K 🔥`
1. [金泰亨指责闵熙珍泄露聊天记录](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%B3%B0%E4%BA%A8%E6%8C%87%E8%B4%A3%E9%97%B5%E7%86%99%E7%8F%8D%E6%B3%84%E9%9C%B2%E8%81%8A%E5%A4%A9%E8%AE%B0%E5%BD%95%23) `180.9K 🔥`
1. [将门独后开机 (Turn on the door alone)](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E5%BC%80%E6%9C%BA%23) `160.7K 🔥`
1. [一家三口返乡途中患病儿子突然离世 (A family of three fell ill and their son died suddenly on their way back home.)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E5%AE%B6%E4%B8%89%E5%8F%A3%E8%BF%94%E4%B9%A1%E9%80%94%E4%B8%AD%E6%82%A3%E7%97%85%E5%84%BF%E5%AD%90%E7%AA%81%E7%84%B6%E7%A6%BB%E4%B8%96%23) `147.2K 🔥`
1. [美国拦截多架俄罗斯军机](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%8B%A6%E6%88%AA%E5%A4%9A%E6%9E%B6%E4%BF%84%E7%BD%97%E6%96%AF%E5%86%9B%E6%9C%BA%23) `98.1K 🔥`
1. [春晚舞台比你想象中要小](https://s.weibo.com/weibo?q=%23%E6%98%A5%E6%99%9A%E8%88%9E%E5%8F%B0%E6%AF%94%E4%BD%A0%E6%83%B3%E8%B1%A1%E4%B8%AD%E8%A6%81%E5%B0%8F%23) `68.8K 🔥`
1. [广东地震 (Guangdong earthquake)](https://s.weibo.com/weibo?q=%23%E5%B9%BF%E4%B8%9C%E5%9C%B0%E9%9C%87%23) `595.8K 🔥` `-48%`
1. [王乐乐官宣恋情](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B9%90%E4%B9%90%E5%AE%98%E5%AE%A3%E6%81%8B%E6%83%85%23) `193.7K 🔥` `-41%`
1. [杨清柠祝福王乐乐](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B8%85%E6%9F%A0%E7%A5%9D%E7%A6%8F%E7%8E%8B%E4%B9%90%E4%B9%90%23) `145.5K 🔥` `-52%`
1. [关晓彤发表情后秒删](https://s.weibo.com/weibo?q=%23%E5%85%B3%E6%99%93%E5%BD%A4%E5%8F%91%E8%A1%A8%E6%83%85%E5%90%8E%E7%A7%92%E5%88%A0%23) `144.1K 🔥` `-55%`
1. [命里有财具象化](https://s.weibo.com/weibo?q=%23%E5%91%BD%E9%87%8C%E6%9C%89%E8%B4%A2%E5%85%B7%E8%B1%A1%E5%8C%96%23) `127.7K 🔥` `-65%`
1. [悉尼偶遇张极张峻豪 (Encountering Zhang Ji and Zhang Junhao in Sydney)](https://s.weibo.com/weibo?q=%23%E6%82%89%E5%B0%BC%E5%81%B6%E9%81%87%E5%BC%A0%E6%9E%81%E5%BC%A0%E5%B3%BB%E8%B1%AA%23) `121.3K 🔥` `-29%`
1. [儿子寒假睡到中午爸爸不许家人打扰](https://s.weibo.com/weibo?q=%23%E5%84%BF%E5%AD%90%E5%AF%92%E5%81%87%E7%9D%A1%E5%88%B0%E4%B8%AD%E5%8D%88%E7%88%B8%E7%88%B8%E4%B8%8D%E8%AE%B8%E5%AE%B6%E4%BA%BA%E6%89%93%E6%89%B0%23) `114.3K 🔥` `-33%`
1. [镖人改编 删吻戏](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E6%94%B9%E7%BC%96%20%E5%88%A0%E5%90%BB%E6%88%8F%23) `106.2K 🔥` `-54%`
1. [陈妍希 勇敢的姐姐先收获李雾](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%A6%8D%E5%B8%8C%20%E5%8B%87%E6%95%A2%E7%9A%84%E5%A7%90%E5%A7%90%E5%85%88%E6%94%B6%E8%8E%B7%E6%9D%8E%E9%9B%BE%23) `101.2K 🔥` `-55%`
1. [镖人 (escort)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%23) `99.8K 🔥` `-30%`
1. [谷爱凌妈妈眼圈哭红了 (Gu Ailing’s mother’s eyes were red from crying)](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%A6%88%E5%A6%88%E7%9C%BC%E5%9C%88%E5%93%AD%E7%BA%A2%E4%BA%86%23) `82.0K 🔥` `-76%`
1. [内蒙古男子因喂流浪猫被杀害](https://s.weibo.com/weibo?q=%23%E5%86%85%E8%92%99%E5%8F%A4%E7%94%B7%E5%AD%90%E5%9B%A0%E5%96%82%E6%B5%81%E6%B5%AA%E7%8C%AB%E8%A2%AB%E6%9D%80%E5%AE%B3%23) `82.0K 🔥` `-78%`
1. [陈平自曝和韦雪前男友做朋友的原因](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%B9%B3%E8%87%AA%E6%9B%9D%E5%92%8C%E9%9F%A6%E9%9B%AA%E5%89%8D%E7%94%B7%E5%8F%8B%E5%81%9A%E6%9C%8B%E5%8F%8B%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `81.8K 🔥` `-38%`
1. [短剧上星](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E4%B8%8A%E6%98%9F%23) `81.7K 🔥` `-51%`
1. [贫穷最可怕的是贫穷的思维基因 (The most terrifying thing about poverty is the poor thinking gene)](https://s.weibo.com/weibo?q=%23%E8%B4%AB%E7%A9%B7%E6%9C%80%E5%8F%AF%E6%80%95%E7%9A%84%E6%98%AF%E8%B4%AB%E7%A9%B7%E7%9A%84%E6%80%9D%E7%BB%B4%E5%9F%BA%E5%9B%A0%23) `81.0K 🔥` `-45%`
1. [将门毒后](https://s.weibo.com/weibo?q=%23%E5%B0%86%E9%97%A8%E6%AF%92%E5%90%8E%23) `80.1K 🔥` `-24%`
1. [新年第一会是AI癫疯大会](https://s.weibo.com/weibo?q=%23%E6%96%B0%E5%B9%B4%E7%AC%AC%E4%B8%80%E4%BC%9A%E6%98%AFAI%E7%99%AB%E7%96%AF%E5%A4%A7%E4%BC%9A%23) `75.2K 🔥` `-28%`
1. [吴京跳刀马 扣了16次扳机 (Wu Jing jumped on the knife horse and pulled the trigger 16 times)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BA%AC%E8%B7%B3%E5%88%80%E9%A9%AC%20%E6%89%A3%E4%BA%8616%E6%AC%A1%E6%89%B3%E6%9C%BA%23) `74.4K 🔥` `-56%`
1. [撒贝宁主持一半找不到龙洋了](https://s.weibo.com/weibo?q=%23%E6%92%92%E8%B4%9D%E5%AE%81%E4%B8%BB%E6%8C%81%E4%B8%80%E5%8D%8A%E6%89%BE%E4%B8%8D%E5%88%B0%E9%BE%99%E6%B4%8B%E4%BA%86%23) `73.1K 🔥` `-39%`
1. [金泰亨说illit像newjeans](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%B3%B0%E4%BA%A8%E8%AF%B4illit%E5%83%8Fnewjeans%23) `71.1K 🔥` `-48%`
1. [深圳震感](https://s.weibo.com/weibo?q=%23%E6%B7%B1%E5%9C%B3%E9%9C%87%E6%84%9F%23) `66.7K 🔥` `-61%`
1. [低山臭水遇知音](https://s.weibo.com/weibo?q=%23%E4%BD%8E%E5%B1%B1%E8%87%AD%E6%B0%B4%E9%81%87%E7%9F%A5%E9%9F%B3%23) `64.6K 🔥` `-26%`
1. [你家是开银行的啊 (Your family runs a bank?)](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%AE%B6%E6%98%AF%E5%BC%80%E9%93%B6%E8%A1%8C%E7%9A%84%E5%95%8A%23) `63.8K 🔥` `-22%`

Updated at 2026-02-20 16:57:57

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
