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

1. [解读国家账本看数字背后 (Interpret the national account books and see behind the numbers)](https://s.weibo.com/weibo?q=%23%E8%A7%A3%E8%AF%BB%E5%9B%BD%E5%AE%B6%E8%B4%A6%E6%9C%AC%E7%9C%8B%E6%95%B0%E5%AD%97%E8%83%8C%E5%90%8E%23) `590.4K 🔥` `NEW`
1. [炸伊朗小学导弹零件MadeinUSA](https://s.weibo.com/weibo?q=%23%E7%82%B8%E4%BC%8A%E6%9C%97%E5%B0%8F%E5%AD%A6%E5%AF%BC%E5%BC%B9%E9%9B%B6%E4%BB%B6MadeinUSA%23) `588.0K 🔥` `NEW`
1. [建议未来五年逐步取消公摊面积](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E6%9C%AA%E6%9D%A5%E4%BA%94%E5%B9%B4%E9%80%90%E6%AD%A5%E5%8F%96%E6%B6%88%E5%85%AC%E6%91%8A%E9%9D%A2%E7%A7%AF%23) `586.7K 🔥` `NEW`
1. [村书记带了一堆柠檬上两会](https://s.weibo.com/weibo?q=%23%E6%9D%91%E4%B9%A6%E8%AE%B0%E5%B8%A6%E4%BA%86%E4%B8%80%E5%A0%86%E6%9F%A0%E6%AA%AC%E4%B8%8A%E4%B8%A4%E4%BC%9A%23) `585.2K 🔥` `NEW`
1. [委员谈员工不敢休年假怎么办](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E8%B0%88%E5%91%98%E5%B7%A5%E4%B8%8D%E6%95%A2%E4%BC%91%E5%B9%B4%E5%81%87%E6%80%8E%E4%B9%88%E5%8A%9E%23) `584.8K 🔥` `NEW`
1. [逐玉爱奇艺破万](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E7%88%B1%E5%A5%87%E8%89%BA%E7%A0%B4%E4%B8%87%23) `583.6K 🔥` `NEW`
1. [这才是普通身材的普通人穿搭](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%89%8D%E6%98%AF%E6%99%AE%E9%80%9A%E8%BA%AB%E6%9D%90%E7%9A%84%E6%99%AE%E9%80%9A%E4%BA%BA%E7%A9%BF%E6%90%AD%23) `583.4K 🔥` `NEW`
1. [田曦薇背后抱量张凌赫腰围](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E8%83%8C%E5%90%8E%E6%8A%B1%E9%87%8F%E5%BC%A0%E5%87%8C%E8%B5%AB%E8%85%B0%E5%9B%B4%23) `531.0K 🔥` `NEW`
1. [乘风2026将全程直播](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%B0%86%E5%85%A8%E7%A8%8B%E7%9B%B4%E6%92%AD%23) `280.9K 🔥` `NEW`
1. [西班牙降级与以色列外交关系](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E7%8F%AD%E7%89%99%E9%99%8D%E7%BA%A7%E4%B8%8E%E4%BB%A5%E8%89%B2%E5%88%97%E5%A4%96%E4%BA%A4%E5%85%B3%E7%B3%BB%23) `163.5K 🔥` `NEW`
1. [伊朗称不再局限于对等反击 (Iran says it is no longer limited to reciprocal counterattacks)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E4%B8%8D%E5%86%8D%E5%B1%80%E9%99%90%E4%BA%8E%E5%AF%B9%E7%AD%89%E5%8F%8D%E5%87%BB%23) `157.4K 🔥` `NEW`
1. [曝AL签下Bigwei](https://s.weibo.com/weibo?q=%23%E6%9B%9DAL%E7%AD%BE%E4%B8%8BBigwei%23) `149.0K 🔥` `NEW`
1. [WB对战狼队](https://s.weibo.com/weibo?q=%23WB%E5%AF%B9%E6%88%98%E7%8B%BC%E9%98%9F%23) `148.2K 🔥` `NEW`
1. [田曦薇 我图你好看啊](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%20%E6%88%91%E5%9B%BE%E4%BD%A0%E5%A5%BD%E7%9C%8B%E5%95%8A%23) `144.1K 🔥` `NEW`
1. [3名美国富豪强奸性侵60名女性](https://s.weibo.com/weibo?q=%233%E5%90%8D%E7%BE%8E%E5%9B%BD%E5%AF%8C%E8%B1%AA%E5%BC%BA%E5%A5%B8%E6%80%A7%E4%BE%B560%E5%90%8D%E5%A5%B3%E6%80%A7%23) `129.4K 🔥` `NEW`
1. [TVB演员江华化身景区打工皇帝](https://s.weibo.com/weibo?q=%23TVB%E6%BC%94%E5%91%98%E6%B1%9F%E5%8D%8E%E5%8C%96%E8%BA%AB%E6%99%AF%E5%8C%BA%E6%89%93%E5%B7%A5%E7%9A%87%E5%B8%9D%23) `112.3K 🔥` `NEW`
1. [伊朗多弹头导弹袭击美军基地](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%A4%9A%E5%BC%B9%E5%A4%B4%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%23) `110.0K 🔥` `NEW`
1. [随元青 辣条音](https://s.weibo.com/weibo?q=%23%E9%9A%8F%E5%85%83%E9%9D%92%20%E8%BE%A3%E6%9D%A1%E9%9F%B3%23) `103.9K 🔥` `NEW`
1. [白敬亭拍长风渡留下的疤](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E6%8B%8D%E9%95%BF%E9%A3%8E%E6%B8%A1%E7%95%99%E4%B8%8B%E7%9A%84%E7%96%A4%23) `102.8K 🔥` `NEW`
1. [伊朗发起第39波打击](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8F%91%E8%B5%B7%E7%AC%AC39%E6%B3%A2%E6%89%93%E5%87%BB%23) `96.9K 🔥` `NEW`
1. [李月汝21分11篮板 (Li Yueru had 21 points and 11 rebounds)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%9C%88%E6%B1%9D21%E5%88%8611%E7%AF%AE%E6%9D%BF%23) `96.9K 🔥` `NEW`
1. [逐玉断层领跑](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E6%96%AD%E5%B1%82%E9%A2%86%E8%B7%91%23) `95.8K 🔥` `NEW`
1. [中国博主拍下打击电诈后的柬埔寨](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%8D%9A%E4%B8%BB%E6%8B%8D%E4%B8%8B%E6%89%93%E5%87%BB%E7%94%B5%E8%AF%88%E5%90%8E%E7%9A%84%E6%9F%AC%E5%9F%94%E5%AF%A8%23) `91.2K 🔥` `NEW`
1. [博主称阿德巴约83分是对科比的羞辱](https://s.weibo.com/weibo?q=%23%E5%8D%9A%E4%B8%BB%E7%A7%B0%E9%98%BF%E5%BE%B7%E5%B7%B4%E7%BA%A683%E5%88%86%E6%98%AF%E5%AF%B9%E7%A7%91%E6%AF%94%E7%9A%84%E7%BE%9E%E8%BE%B1%23) `89.9K 🔥` `NEW`
1. [三星首款防窥屏手机 (Samsung’s first phone with privacy screen)](https://s.weibo.com/weibo?q=%23%E4%B8%89%E6%98%9F%E9%A6%96%E6%AC%BE%E9%98%B2%E7%AA%A5%E5%B1%8F%E6%89%8B%E6%9C%BA%23) `589.9K 🔥` `+47%`
1. [精灵黄lululemon发圈被炒到999元](https://s.weibo.com/weibo?q=%23%E7%B2%BE%E7%81%B5%E9%BB%84lululemon%E5%8F%91%E5%9C%88%E8%A2%AB%E7%82%92%E5%88%B0999%E5%85%83%23) `588.8K 🔥` `+354%`
1. [宁德时代创始人曾毓群个人分红81亿](https://s.weibo.com/weibo?q=%23%E5%AE%81%E5%BE%B7%E6%97%B6%E4%BB%A3%E5%88%9B%E5%A7%8B%E4%BA%BA%E6%9B%BE%E6%AF%93%E7%BE%A4%E4%B8%AA%E4%BA%BA%E5%88%86%E7%BA%A281%E4%BA%BF%23) `587.7K 🔥` `+395%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `413.1K 🔥` `+102%`
1. [公积金改革大潮真的来了 (The tide of provident fund reform is really coming)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E7%A7%AF%E9%87%91%E6%94%B9%E9%9D%A9%E5%A4%A7%E6%BD%AE%E7%9C%9F%E7%9A%84%E6%9D%A5%E4%BA%86%23) `206.2K 🔥` `+30%`
1. [上过班的才知道这有多幸福 (Only those who have worked know how happy this is)](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E8%BF%87%E7%8F%AD%E7%9A%84%E6%89%8D%E7%9F%A5%E9%81%93%E8%BF%99%E6%9C%89%E5%A4%9A%E5%B9%B8%E7%A6%8F%23) `126.2K 🔥` `+46%`
1. [委员回应年轻人天天熬夜行不行](https://s.weibo.com/weibo?q=%23%E5%A7%94%E5%91%98%E5%9B%9E%E5%BA%94%E5%B9%B4%E8%BD%BB%E4%BA%BA%E5%A4%A9%E5%A4%A9%E7%86%AC%E5%A4%9C%E8%A1%8C%E4%B8%8D%E8%A1%8C%23) `1.0M 🔥`
1. [国防部回应日本部署远程导弹 (Ministry of National Defense responds to Japan's deployment of long-range missiles)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%98%B2%E9%83%A8%E5%9B%9E%E5%BA%94%E6%97%A5%E6%9C%AC%E9%83%A8%E7%BD%B2%E8%BF%9C%E7%A8%8B%E5%AF%BC%E5%BC%B9%23) `765.4K 🔥`
1. [公积金提取 (Provident fund withdrawal)](https://s.weibo.com/weibo?q=%23%E5%85%AC%E7%A7%AF%E9%87%91%E6%8F%90%E5%8F%96%23) `589.6K 🔥`
1. [为农民哽咽发声代表接到多部委电话](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E5%86%9C%E6%B0%91%E5%93%BD%E5%92%BD%E5%8F%91%E5%A3%B0%E4%BB%A3%E8%A1%A8%E6%8E%A5%E5%88%B0%E5%A4%9A%E9%83%A8%E5%A7%94%E7%94%B5%E8%AF%9D%23) `435.6K 🔥`
1. [MiuMiu](https://s.weibo.com/weibo?q=%23MiuMiu%23) `303.2K 🔥`
1. [逐玉 头纱](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%A4%B4%E7%BA%B1%23) `302.6K 🔥`
1. [建议允许60岁以上农民工继续务工 (It is recommended that migrant workers over 60 years old be allowed to continue working)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%85%81%E8%AE%B860%E5%B2%81%E4%BB%A5%E4%B8%8A%E5%86%9C%E6%B0%91%E5%B7%A5%E7%BB%A7%E7%BB%AD%E5%8A%A1%E5%B7%A5%23) `159.7K 🔥`
1. [我们的少年时代2开通官微 (Our Boyhood 2 launches official WeChat account)](https://s.weibo.com/weibo?q=%23%E6%88%91%E4%BB%AC%E7%9A%84%E5%B0%91%E5%B9%B4%E6%97%B6%E4%BB%A32%E5%BC%80%E9%80%9A%E5%AE%98%E5%BE%AE%23) `116.5K 🔥`
1. [中国女篮vs马里女篮](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E5%A5%B3%E7%AF%AEvs%E9%A9%AC%E9%87%8C%E5%A5%B3%E7%AF%AE%23) `96.5K 🔥`
1. [伊朗对美以发动38波攻击 (Iran launches 38 waves of attacks on the United States and Israel)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%B9%E7%BE%8E%E4%BB%A5%E5%8F%91%E5%8A%A838%E6%B3%A2%E6%94%BB%E5%87%BB%23) `217.6K 🔥` `-53%`
1. [Gemini五连绝世](https://s.weibo.com/weibo?q=%23Gemini%E4%BA%94%E8%BF%9E%E7%BB%9D%E4%B8%96%23) `210.4K 🔥` `-62%`
1. [逐玉追剧团](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%BF%BD%E5%89%A7%E5%9B%A2%23) `177.7K 🔥` `-48%`
1. [吴昕在大侦探爆哭](https://s.weibo.com/weibo?q=%23%E5%90%B4%E6%98%95%E5%9C%A8%E5%A4%A7%E4%BE%A6%E6%8E%A2%E7%88%86%E5%93%AD%23) `167.4K 🔥` `-50%`
1. [慕慕昭昭大婚](https://s.weibo.com/weibo?q=%23%E6%85%95%E6%85%95%E6%98%AD%E6%98%AD%E5%A4%A7%E5%A9%9A%23) `131.1K 🔥` `-48%`
1. [不二之臣 (The best minister)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BA%8C%E4%B9%8B%E8%87%A3%23) `122.2K 🔥` `-22%`
1. [取微信名要慎重 (Be careful when choosing a WeChat name)](https://s.weibo.com/weibo?q=%23%E5%8F%96%E5%BE%AE%E4%BF%A1%E5%90%8D%E8%A6%81%E6%85%8E%E9%87%8D%23) `117.0K 🔥` `-23%`
1. [你更愿意喝9.9元还是30元的咖啡](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E6%9B%B4%E6%84%BF%E6%84%8F%E5%96%9D9.9%E5%85%83%E8%BF%98%E6%98%AF30%E5%85%83%E7%9A%84%E5%92%96%E5%95%A1%23) `115.9K 🔥` `-24%`
1. [双人餐是需要两份主食饮料的](https://s.weibo.com/weibo?q=%23%E5%8F%8C%E4%BA%BA%E9%A4%90%E6%98%AF%E9%9C%80%E8%A6%81%E4%B8%A4%E4%BB%BD%E4%B8%BB%E9%A3%9F%E9%A5%AE%E6%96%99%E7%9A%84%23) `105.6K 🔥` `-53%`
1. [入职大疆1个月被发了5次钱](https://s.weibo.com/weibo?q=%23%E5%85%A5%E8%81%8C%E5%A4%A7%E7%96%861%E4%B8%AA%E6%9C%88%E8%A2%AB%E5%8F%91%E4%BA%865%E6%AC%A1%E9%92%B1%23) `97.0K 🔥` `-25%`
1. [梁朝伟走势](https://s.weibo.com/weibo?q=%23%E6%A2%81%E6%9C%9D%E4%BC%9F%E8%B5%B0%E5%8A%BF%23) `90.5K 🔥` `-26%`
1. [日本大阪一马路长出15米高巨型水管 (A 15-meter-tall giant water pipe grows on a road in Osaka, Japan)](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E5%A4%A7%E9%98%AA%E4%B8%80%E9%A9%AC%E8%B7%AF%E9%95%BF%E5%87%BA15%E7%B1%B3%E9%AB%98%E5%B7%A8%E5%9E%8B%E6%B0%B4%E7%AE%A1%23) `85.5K 🔥` `-32%`

Updated at 2026-03-11 21:50:13

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
