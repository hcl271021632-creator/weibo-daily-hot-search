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

1. [中国石油发布公告 (PetroChina releases announcement)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9F%B3%E6%B2%B9%E5%8F%91%E5%B8%83%E5%85%AC%E5%91%8A%23) `520.0K 🔥` `NEW`
1. [伊朗导弹击中美第五舰队总部瞬间](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B9%E5%87%BB%E4%B8%AD%E7%BE%8E%E7%AC%AC%E4%BA%94%E8%88%B0%E9%98%9F%E6%80%BB%E9%83%A8%E7%9E%AC%E9%97%B4%23) `518.5K 🔥` `NEW`
1. [EDG](https://s.weibo.com/weibo?q=%23EDG%23) `518.2K 🔥` `NEW`
1. [伊朗宣称重创美军](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%A3%E7%A7%B0%E9%87%8D%E5%88%9B%E7%BE%8E%E5%86%9B%23) `517.9K 🔥` `NEW`
1. [美股](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E8%82%A1%23) `517.3K 🔥` `NEW`
1. [狼队2比1利物浦](https://s.weibo.com/weibo?q=%23%E7%8B%BC%E9%98%9F2%E6%AF%941%E5%88%A9%E7%89%A9%E6%B5%A6%23) `517.1K 🔥` `NEW`
1. [全国两会](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%23) `517.1K 🔥` `NEW`
1. [苹果新显示器定价](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E6%96%B0%E6%98%BE%E7%A4%BA%E5%99%A8%E5%AE%9A%E4%BB%B7%23) `516.4K 🔥` `NEW`
1. [巴萨3比0马竞](https://s.weibo.com/weibo?q=%23%E5%B7%B4%E8%90%A83%E6%AF%940%E9%A9%AC%E7%AB%9E%23) `516.1K 🔥` `NEW`
1. [狼队vs利物浦](https://s.weibo.com/weibo?q=%23%E7%8B%BC%E9%98%9Fvs%E5%88%A9%E7%89%A9%E6%B5%A6%23) `515.9K 🔥` `NEW`
1. [G2大师赛战胜XLG (G2 Masters defeated XLG)](https://s.weibo.com/weibo?q=%23G2%E5%A4%A7%E5%B8%88%E8%B5%9B%E6%88%98%E8%83%9CXLG%23) `515.7K 🔥` `NEW`
1. [中国驻迪拜总领馆发布特别提醒 (The Chinese Consulate General in Dubai issues a special reminder)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E9%A9%BB%E8%BF%AA%E6%8B%9C%E6%80%BB%E9%A2%86%E9%A6%86%E5%8F%91%E5%B8%83%E7%89%B9%E5%88%AB%E6%8F%90%E9%86%92%23) `892.9K 🔥` `+149%`
1. [2026全国两会这些看点值得关注](https://s.weibo.com/weibo?q=%232026%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%E8%BF%99%E4%BA%9B%E7%9C%8B%E7%82%B9%E5%80%BC%E5%BE%97%E5%85%B3%E6%B3%A8%23) `520.2K 🔥` `+44%`
1. [跟刘宇宁来京东38节领五色花 (Follow Liu Yuning to JD.com’s 38th Festival to receive colorful flowers)](https://s.weibo.com/weibo?q=%23%E8%B7%9F%E5%88%98%E5%AE%87%E5%AE%81%E6%9D%A5%E4%BA%AC%E4%B8%9C38%E8%8A%82%E9%A2%86%E4%BA%94%E8%89%B2%E8%8A%B1%23) `520.2K 🔥` `+49%`
1. [金价银价断崖式跳水 (Gold and silver prices plummet)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E9%93%B6%E4%BB%B7%E6%96%AD%E5%B4%96%E5%BC%8F%E8%B7%B3%E6%B0%B4%23) `520.1K 🔥` `+45%`
1. [美以伊最新局势 (The latest situation between the United States, Israel and Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E4%BC%8A%E6%9C%80%E6%96%B0%E5%B1%80%E5%8A%BF%23) `520.0K 🔥` `+47%`
1. [世界油阀关闭](https://s.weibo.com/weibo?q=%23%E4%B8%96%E7%95%8C%E6%B2%B9%E9%98%80%E5%85%B3%E9%97%AD%23) `519.8K 🔥` `+48%`
1. [纯真年代的爱情 (Love in the Age of Innocence)](https://s.weibo.com/weibo?q=%23%E7%BA%AF%E7%9C%9F%E5%B9%B4%E4%BB%A3%E7%9A%84%E7%88%B1%E6%83%85%23) `519.7K 🔥` `+48%`
1. [人大代表建议元宵节重阳节放假](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E5%BB%BA%E8%AE%AE%E5%85%83%E5%AE%B5%E8%8A%82%E9%87%8D%E9%98%B3%E8%8A%82%E6%94%BE%E5%81%87%23) `519.6K 🔥` `+58%`
1. [刘宇宁魏晨 舞台走位](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E9%AD%8F%E6%99%A8%20%E8%88%9E%E5%8F%B0%E8%B5%B0%E4%BD%8D%23) `519.5K 🔥` `+49%`
1. [单亲爸爸打铁花成网红中毒离世 (Single father who worked as an ironworker and became an internet celebrity died of poisoning)](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BA%B2%E7%88%B8%E7%88%B8%E6%89%93%E9%93%81%E8%8A%B1%E6%88%90%E7%BD%91%E7%BA%A2%E4%B8%AD%E6%AF%92%E7%A6%BB%E4%B8%96%23) `519.4K 🔥` `+51%`
1. [伊朗最高领袖选举机构办公楼遭袭 (The office building of Iran’s supreme leader’s electoral body was attacked)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E9%80%89%E4%B8%BE%E6%9C%BA%E6%9E%84%E5%8A%9E%E5%85%AC%E6%A5%BC%E9%81%AD%E8%A2%AD%23) `519.3K 🔥` `+50%`
1. [住酒店三年还被员工蛐蛐 (I stayed in a hotel for three years and was cricketed by employees)](https://s.weibo.com/weibo?q=%23%E4%BD%8F%E9%85%92%E5%BA%97%E4%B8%89%E5%B9%B4%E8%BF%98%E8%A2%AB%E5%91%98%E5%B7%A5%E8%9B%90%E8%9B%90%23) `519.3K 🔥` `+52%`
1. [伦敦机场18小时未进食求助女子发声](https://s.weibo.com/weibo?q=%23%E4%BC%A6%E6%95%A6%E6%9C%BA%E5%9C%BA18%E5%B0%8F%E6%97%B6%E6%9C%AA%E8%BF%9B%E9%A3%9F%E6%B1%82%E5%8A%A9%E5%A5%B3%E5%AD%90%E5%8F%91%E5%A3%B0%23) `519.1K 🔥` `+51%`
1. [山姆1.38公斤冰块卖37.9元](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E5%A7%861.38%E5%85%AC%E6%96%A4%E5%86%B0%E5%9D%97%E5%8D%9637.9%E5%85%83%23) `519.0K 🔥` `+54%`
1. [妻子要离婚丈夫要求返还10万元彩礼 (Wife wants divorce, husband demands return of 100,000 yuan gift)](https://s.weibo.com/weibo?q=%23%E5%A6%BB%E5%AD%90%E8%A6%81%E7%A6%BB%E5%A9%9A%E4%B8%88%E5%A4%AB%E8%A6%81%E6%B1%82%E8%BF%94%E8%BF%9810%E4%B8%87%E5%85%83%E5%BD%A9%E7%A4%BC%23) `519.0K 🔥` `+55%`
1. [迪奥官宣王楚然 (Dior officially announces Wang Churan)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E5%A5%A5%E5%AE%98%E5%AE%A3%E7%8E%8B%E6%A5%9A%E7%84%B6%23) `518.9K 🔥` `+56%`
1. [DIOR大秀 (DIOR show)](https://s.weibo.com/weibo?q=%23DIOR%E5%A4%A7%E7%A7%80%23) `518.8K 🔥` `+47%`
1. [痞幼直播关美颜](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E7%9B%B4%E6%92%AD%E5%85%B3%E7%BE%8E%E9%A2%9C%23) `518.7K 🔥` `+53%`
1. [赵今麦吃了好多汤圆 (Zhao Jinmai ate a lot of glutinous rice balls)](https://s.weibo.com/weibo?q=%23%E8%B5%B5%E4%BB%8A%E9%BA%A6%E5%90%83%E4%BA%86%E5%A5%BD%E5%A4%9A%E6%B1%A4%E5%9C%86%23) `518.4K 🔥` `+59%`
1. [伊朗南部阿巴斯港等地遭密集空袭 (Bandar Abbas Port and other places in southern Iran come under intensive air strikes)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%8D%97%E9%83%A8%E9%98%BF%E5%B7%B4%E6%96%AF%E6%B8%AF%E7%AD%89%E5%9C%B0%E9%81%AD%E5%AF%86%E9%9B%86%E7%A9%BA%E8%A2%AD%23) `518.3K 🔥` `+59%`
1. [王毅和以色列外长通电话 (Wang Yi had a phone call with the Israeli Foreign Minister)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%AF%85%E5%92%8C%E4%BB%A5%E8%89%B2%E5%88%97%E5%A4%96%E9%95%BF%E9%80%9A%E7%94%B5%E8%AF%9D%23) `518.1K 🔥` `+60%`
1. [金智秀 迪奥公主 (Kim Ji Soo Princess Dior)](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%99%BA%E7%A7%80%20%E8%BF%AA%E5%A5%A5%E5%85%AC%E4%B8%BB%23) `518.0K 🔥` `+69%`
1. [龙洋眼妆](https://s.weibo.com/weibo?q=%23%E9%BE%99%E6%B4%8B%E7%9C%BC%E5%A6%86%23) `517.8K 🔥` `+64%`
1. [41岁打铁花网红一氧化碳中毒去世 (41-year-old blacksmith internet celebrity died of carbon monoxide poisoning)](https://s.weibo.com/weibo?q=%2341%E5%B2%81%E6%89%93%E9%93%81%E8%8A%B1%E7%BD%91%E7%BA%A2%E4%B8%80%E6%B0%A7%E5%8C%96%E7%A2%B3%E4%B8%AD%E6%AF%92%E5%8E%BB%E4%B8%96%23) `517.7K 🔥` `+68%`
1. [以为李柯以是跨界结果是老本行](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E6%9D%8E%E6%9F%AF%E4%BB%A5%E6%98%AF%E8%B7%A8%E7%95%8C%E7%BB%93%E6%9E%9C%E6%98%AF%E8%80%81%E6%9C%AC%E8%A1%8C%23) `517.6K 🔥` `+61%`
1. [法德联合声明 (Franco-German Joint Statement)](https://s.weibo.com/weibo?q=%23%E6%B3%95%E5%BE%B7%E8%81%94%E5%90%88%E5%A3%B0%E6%98%8E%23) `517.5K 🔥` `+67%`
1. [王毅要求以方确保中国人员机构安全 (Wang Yi requires Israel to ensure the safety of Chinese personnel and institutions)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%AF%85%E8%A6%81%E6%B1%82%E4%BB%A5%E6%96%B9%E7%A1%AE%E4%BF%9D%E4%B8%AD%E5%9B%BD%E4%BA%BA%E5%91%98%E6%9C%BA%E6%9E%84%E5%AE%89%E5%85%A8%23) `517.4K 🔥` `+67%`
1. [罗云熙壁上观舞美](https://s.weibo.com/weibo?q=%23%E7%BD%97%E4%BA%91%E7%86%99%E5%A3%81%E4%B8%8A%E8%A7%82%E8%88%9E%E7%BE%8E%23) `517.2K 🔥` `+56%`
1. [金鹤龙把王菊化成刘亦菲了](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%B9%A4%E9%BE%99%E6%8A%8A%E7%8E%8B%E8%8F%8A%E5%8C%96%E6%88%90%E5%88%98%E4%BA%A6%E8%8F%B2%E4%BA%86%23) `516.9K 🔥` `+62%`
1. [金饰克价突破1660元 (Price of gold jewelry exceeds 1,660 yuan per gram)](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E7%AA%81%E7%A0%B41660%E5%85%83%23) `516.9K 🔥` `+67%`
1. [伊朗称向美航母发射4枚巡航导弹 (Iran says it fired 4 cruise missiles at US aircraft carrier)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%90%91%E7%BE%8E%E8%88%AA%E6%AF%8D%E5%8F%91%E5%B0%844%E6%9E%9A%E5%B7%A1%E8%88%AA%E5%AF%BC%E5%BC%B9%23) `516.7K 🔥` `+62%`
1. [元宵晚会四美 (Four Beauties of the Lantern Festival Party)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E6%99%9A%E4%BC%9A%E5%9B%9B%E7%BE%8E%23) `516.6K 🔥` `+64%`
1. [中方呼吁立即停止军事行动](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%91%BC%E5%90%81%E7%AB%8B%E5%8D%B3%E5%81%9C%E6%AD%A2%E5%86%9B%E4%BA%8B%E8%A1%8C%E5%8A%A8%23) `516.6K 🔥` `+67%`
1. [月全食 (total lunar eclipse)](https://s.weibo.com/weibo?q=%23%E6%9C%88%E5%85%A8%E9%A3%9F%23) `516.5K 🔥` `+65%`
1. [麦当劳CEO试吃自家汉堡 (McDonald's CEO tastes his own burger)](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E8%AF%95%E5%90%83%E8%87%AA%E5%AE%B6%E6%B1%89%E5%A0%A1%23) `516.3K 🔥` `+68%`
1. [华晨宇好稳 (Hua Chenyu is so stable)](https://s.weibo.com/weibo?q=%23%E5%8D%8E%E6%99%A8%E5%AE%87%E5%A5%BD%E7%A8%B3%23) `516.2K 🔥` `+67%`
1. [檀健次好可爱的汤圆](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%E5%A5%BD%E5%8F%AF%E7%88%B1%E7%9A%84%E6%B1%A4%E5%9C%86%23) `515.9K 🔥` `+68%`
1. [王橹杰新的一年祝你永远闪耀](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A9%B9%E6%9D%B0%E6%96%B0%E7%9A%84%E4%B8%80%E5%B9%B4%E7%A5%9D%E4%BD%A0%E6%B0%B8%E8%BF%9C%E9%97%AA%E8%80%80%23) `515.8K 🔥` `+69%`
1. [12306回应乘客在高铁上用排插 (12306 responded to passengers using power strips on high-speed trains)](https://s.weibo.com/weibo?q=%2312306%E5%9B%9E%E5%BA%94%E4%B9%98%E5%AE%A2%E5%9C%A8%E9%AB%98%E9%93%81%E4%B8%8A%E7%94%A8%E6%8E%92%E6%8F%92%23) `665.7K 🔥`
1. [元宵晚会 好看 (Lantern Festival party is beautiful)](https://s.weibo.com/weibo?q=%23%E5%85%83%E5%AE%B5%E6%99%9A%E4%BC%9A%20%E5%A5%BD%E7%9C%8B%23) `518.6K 🔥`

Updated at 2026-03-04 07:37:59

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
