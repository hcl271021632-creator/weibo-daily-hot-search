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

1. [2026中国网络媒体论坛 (2026 China Online Media Forum)](https://s.weibo.com/weibo?q=%232026%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BB%9C%E5%AA%92%E4%BD%93%E8%AE%BA%E5%9D%9B%23) `845.9K 🔥` `NEW`
1. [白鹿为乘风姐姐代斯加油](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E4%B8%BA%E4%B9%98%E9%A3%8E%E5%A7%90%E5%A7%90%E4%BB%A3%E6%96%AF%E5%8A%A0%E6%B2%B9%23) `189.9K 🔥` `NEW`
1. [樊振东3比0孟庆宇](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C3%E6%AF%940%E5%AD%9F%E5%BA%86%E5%AE%87%23) `161.6K 🔥` `NEW`
1. [演员李尚宝去世](https://s.weibo.com/weibo?q=%23%E6%BC%94%E5%91%98%E6%9D%8E%E5%B0%9A%E5%AE%9D%E5%8E%BB%E4%B8%96%23) `119.5K 🔥` `NEW`
1. [国际金银急涨](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E9%99%85%E9%87%91%E9%93%B6%E6%80%A5%E6%B6%A8%23) `112.3K 🔥` `NEW`
1. [陶昕然浪姐连线的是孙俪](https://s.weibo.com/weibo?q=%23%E9%99%B6%E6%98%95%E7%84%B6%E6%B5%AA%E5%A7%90%E8%BF%9E%E7%BA%BF%E7%9A%84%E6%98%AF%E5%AD%99%E4%BF%AA%23) `105.7K 🔥` `NEW`
1. [小尼赞助谢娜骑行去鸟巢](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%B0%BC%E8%B5%9E%E5%8A%A9%E8%B0%A2%E5%A8%9C%E9%AA%91%E8%A1%8C%E5%8E%BB%E9%B8%9F%E5%B7%A2%23) `100.2K 🔥` `NEW`
1. [罗技](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%8A%80%23) `96.4K 🔥` `NEW`
1. [乘风2026初舞台就有淘汰](https://s.weibo.com/weibo?q=%23%E4%B9%98%E9%A3%8E2026%E5%88%9D%E8%88%9E%E5%8F%B0%E5%B0%B1%E6%9C%89%E6%B7%98%E6%B1%B0%23) `81.8K 🔥` `NEW`
1. [医院已安抚男医生产检丈夫撞墙孕妇](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E9%99%A2%E5%B7%B2%E5%AE%89%E6%8A%9A%E7%94%B7%E5%8C%BB%E7%94%9F%E4%BA%A7%E6%A3%80%E4%B8%88%E5%A4%AB%E6%92%9E%E5%A2%99%E5%AD%95%E5%A6%87%23) `79.2K 🔥` `NEW`
1. [逐玉吻戏喊cut后两人都很忙 (Both of them were very busy after the Zhuyu kissing scene called for cut)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E5%90%BB%E6%88%8F%E5%96%8Acut%E5%90%8E%E4%B8%A4%E4%BA%BA%E9%83%BD%E5%BE%88%E5%BF%99%23) `68.1K 🔥` `NEW`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `65.3K 🔥` `NEW`
1. [金银油集体飙升](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%93%B6%E6%B2%B9%E9%9B%86%E4%BD%93%E9%A3%99%E5%8D%87%23) `63.5K 🔥` `NEW`
1. [最强大脑国际赛太夯了](https://s.weibo.com/weibo?q=%23%E6%9C%80%E5%BC%BA%E5%A4%A7%E8%84%91%E5%9B%BD%E9%99%85%E8%B5%9B%E5%A4%AA%E5%A4%AF%E4%BA%86%23) `63.5K 🔥` `NEW`
1. [杨紫为黄灿灿乘风2026打call](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E4%B8%BA%E9%BB%84%E7%81%BF%E7%81%BF%E4%B9%98%E9%A3%8E2026%E6%89%93call%23) `63.5K 🔥` `NEW`
1. [李昌钰去世 (Li Changyu passed away)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E6%98%8C%E9%92%B0%E5%8E%BB%E4%B8%96%23) `3.3M 🔥` `+455%`
1. [孩子生病后买彩票中500万妈妈发声 (Mother speaks out after winning $5 million in lottery tickets after her child fell ill)](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E7%94%9F%E7%97%85%E5%90%8E%E4%B9%B0%E5%BD%A9%E7%A5%A8%E4%B8%AD500%E4%B8%87%E5%A6%88%E5%A6%88%E5%8F%91%E5%A3%B0%23) `1.1M 🔥` `+28%`
1. [中巴同意共同推动停火止战恢复和谈](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%B7%B4%E5%90%8C%E6%84%8F%E5%85%B1%E5%90%8C%E6%8E%A8%E5%8A%A8%E5%81%9C%E7%81%AB%E6%AD%A2%E6%88%98%E6%81%A2%E5%A4%8D%E5%92%8C%E8%B0%88%23) `298.1K 🔥` `+443%`
1. [医生辟谣只要少吃就能瘦 (Doctor refutes rumors that you can lose weight by eating less)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E8%BE%9F%E8%B0%A3%E5%8F%AA%E8%A6%81%E5%B0%91%E5%90%83%E5%B0%B1%E8%83%BD%E7%98%A6%23) `199.4K 🔥` `+622%`
1. [竹林四侠彻底be了 (The Four Heroes of the Bamboo Forest are completely bereft)](https://s.weibo.com/weibo?q=%23%E7%AB%B9%E6%9E%97%E5%9B%9B%E4%BE%A0%E5%BD%BB%E5%BA%95be%E4%BA%86%23) `128.1K 🔥` `+51%`
1. [霍尔木兹决战摊牌了 (The showdown begins in Hormuz)](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E5%86%B3%E6%88%98%E6%91%8A%E7%89%8C%E4%BA%86%23) `126.4K 🔥` `+49%`
1. [锤娜丽莎瘦30斤公开减肥原因 (Narissa lost 30 pounds and revealed the reasons for losing weight)](https://s.weibo.com/weibo?q=%23%E9%94%A4%E5%A8%9C%E4%B8%BD%E8%8E%8E%E7%98%A630%E6%96%A4%E5%85%AC%E5%BC%80%E5%87%8F%E8%82%A5%E5%8E%9F%E5%9B%A0%23) `122.9K 🔥` `+45%`
1. [男子借钱凑彩礼结婚后1个月被家暴 (Man borrowed money to collect dowry and was domestically assaulted 1 month after getting married)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%80%9F%E9%92%B1%E5%87%91%E5%BD%A9%E7%A4%BC%E7%BB%93%E5%A9%9A%E5%90%8E1%E4%B8%AA%E6%9C%88%E8%A2%AB%E5%AE%B6%E6%9A%B4%23) `118.7K 🔥` `+41%`
1. [钧正平评粉底液将军](https://s.weibo.com/weibo?q=%23%E9%92%A7%E6%AD%A3%E5%B9%B3%E8%AF%84%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B%23) `115.7K 🔥` `+37%`
1. [阚清子问我这么胖吗 (Kan Qingzi asked me if I was so fat)](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E9%97%AE%E6%88%91%E8%BF%99%E4%B9%88%E8%83%96%E5%90%97%23) `114.0K 🔥` `+35%`
1. [王一博微博改名](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%BE%AE%E5%8D%9A%E6%94%B9%E5%90%8D%23) `112.2K 🔥` `+33%`
1. [西班牙25岁女孩被性侵多次后申请安乐死 (Spanish girl, 25, applies for euthanasia after being sexually assaulted multiple times)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E7%8F%AD%E7%89%9925%E5%B2%81%E5%A5%B3%E5%AD%A9%E8%A2%AB%E6%80%A7%E4%BE%B5%E5%A4%9A%E6%AC%A1%E5%90%8E%E7%94%B3%E8%AF%B7%E5%AE%89%E4%B9%90%E6%AD%BB%23) `112.1K 🔥` `+33%`
1. [曝关晓彤喜提新车 (It is revealed that Guan Xiaotong likes to bring a new car)](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E5%85%B3%E6%99%93%E5%BD%A4%E5%96%9C%E6%8F%90%E6%96%B0%E8%BD%A6%23) `112.1K 🔥` `+33%`
1. [岳云鹏室内抽烟 (Yue Yunpeng smokes indoors)](https://s.weibo.com/weibo?q=%23%E5%B2%B3%E4%BA%91%E9%B9%8F%E5%AE%A4%E5%86%85%E6%8A%BD%E7%83%9F%23) `106.8K 🔥` `+28%`
1. [大部分人觉得旅游累的原因 (The reason why most people feel tired from traveling)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E9%83%A8%E5%88%86%E4%BA%BA%E8%A7%89%E5%BE%97%E6%97%85%E6%B8%B8%E7%B4%AF%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `106.7K 🔥` `+26%`
1. [菲舰不顾中方反复喊话提醒](https://s.weibo.com/weibo?q=%23%E8%8F%B2%E8%88%B0%E4%B8%8D%E9%A1%BE%E4%B8%AD%E6%96%B9%E5%8F%8D%E5%A4%8D%E5%96%8A%E8%AF%9D%E6%8F%90%E9%86%92%23) `286.2K 🔥`
1. [3D还原女子因停车纠纷摔倒身亡 (3D restoration of woman falling and dying due to parking dispute)](https://s.weibo.com/weibo?q=%233D%E8%BF%98%E5%8E%9F%E5%A5%B3%E5%AD%90%E5%9B%A0%E5%81%9C%E8%BD%A6%E7%BA%A0%E7%BA%B7%E6%91%94%E5%80%92%E8%BA%AB%E4%BA%A1%23) `199.7K 🔥`
1. [伊朗无人机群袭以色列最大运输中心](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%97%A0%E4%BA%BA%E6%9C%BA%E7%BE%A4%E8%A2%AD%E4%BB%A5%E8%89%B2%E5%88%97%E6%9C%80%E5%A4%A7%E8%BF%90%E8%BE%93%E4%B8%AD%E5%BF%83%23) `155.1K 🔥`
1. [央视网评罗技侮辱性广告 (CCTV comments on Logitech’s insulting ad)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E7%BD%91%E8%AF%84%E7%BD%97%E6%8A%80%E4%BE%AE%E8%BE%B1%E6%80%A7%E5%B9%BF%E5%91%8A%23) `129.7K 🔥`
1. [雷军壁纸 逆天改命 (Lei Jun wallpaper changes fate against fate)](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E5%A3%81%E7%BA%B8%20%E9%80%86%E5%A4%A9%E6%94%B9%E5%91%BD%23) `85.4K 🔥`
1. [今年蚊子可能迎来史诗级加强 (Mosquitoes may experience an epic strengthening this year)](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E8%9A%8A%E5%AD%90%E5%8F%AF%E8%83%BD%E8%BF%8E%E6%9D%A5%E5%8F%B2%E8%AF%97%E7%BA%A7%E5%8A%A0%E5%BC%BA%23) `81.9K 🔥`
1. [怡宝不好卖了 (Yibao is not easy to sell)](https://s.weibo.com/weibo?q=%23%E6%80%A1%E5%AE%9D%E4%B8%8D%E5%A5%BD%E5%8D%96%E4%BA%86%23) `79.6K 🔥`
1. [世界第一高楼被闪电击中 (The world's tallest building was struck by lightning)](https://s.weibo.com/weibo?q=%23%E4%B8%96%E7%95%8C%E7%AC%AC%E4%B8%80%E9%AB%98%E6%A5%BC%E8%A2%AB%E9%97%AA%E7%94%B5%E5%87%BB%E4%B8%AD%23) `68.3K 🔥`
1. [王一博乐华续约 (Wang Yibo Lehua renews contract)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E4%B9%90%E5%8D%8E%E7%BB%AD%E7%BA%A6%23) `67.8K 🔥`
1. [警方过筛23.7斤血沙破25年前命案](https://s.weibo.com/weibo?q=%23%E8%AD%A6%E6%96%B9%E8%BF%87%E7%AD%9B23.7%E6%96%A4%E8%A1%80%E6%B2%99%E7%A0%B425%E5%B9%B4%E5%89%8D%E5%91%BD%E6%A1%88%23) `65.8K 🔥`
1. [美以空袭伊朗钢铁厂及配套发电厂](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E4%BB%A5%E7%A9%BA%E8%A2%AD%E4%BC%8A%E6%9C%97%E9%92%A2%E9%93%81%E5%8E%82%E5%8F%8A%E9%85%8D%E5%A5%97%E5%8F%91%E7%94%B5%E5%8E%82%23) `63.5K 🔥`
1. [逐玉 庆功宴 (Zhuyu Celebration Banquet)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E5%BA%86%E5%8A%9F%E5%AE%B4%23) `63.5K 🔥`
1. [打学生致面部骨折体育老师已被开除](https://s.weibo.com/weibo?q=%23%E6%89%93%E5%AD%A6%E7%94%9F%E8%87%B4%E9%9D%A2%E9%83%A8%E9%AA%A8%E6%8A%98%E4%BD%93%E8%82%B2%E8%80%81%E5%B8%88%E5%B7%B2%E8%A2%AB%E5%BC%80%E9%99%A4%23) `63.5K 🔥`
1. [张凌赫回复严屹宽 (Zhang Linghe replied to Yan Yikuan)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%9B%9E%E5%A4%8D%E4%B8%A5%E5%B1%B9%E5%AE%BD%23) `63.5K 🔥`
1. [无证医生给骨折老人急救多方发声 (Unlicensed doctors give first aid to elderly people with fractures and speak out)](https://s.weibo.com/weibo?q=%23%E6%97%A0%E8%AF%81%E5%8C%BB%E7%94%9F%E7%BB%99%E9%AA%A8%E6%8A%98%E8%80%81%E4%BA%BA%E6%80%A5%E6%95%91%E5%A4%9A%E6%96%B9%E5%8F%91%E5%A3%B0%23) `63.5K 🔥`
1. [迪丽热巴白日提灯包场6666份](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E5%8C%85%E5%9C%BA6666%E4%BB%BD%23) `63.5K 🔥`
1. [黄子韬因为减肥后脑勺秃了](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E9%9F%AC%E5%9B%A0%E4%B8%BA%E5%87%8F%E8%82%A5%E5%90%8E%E8%84%91%E5%8B%BA%E7%A7%83%E4%BA%86%23) `63.5K 🔥`
1. [奉劝大家还是尽量多存钱](https://s.weibo.com/weibo?q=%23%E5%A5%89%E5%8A%9D%E5%A4%A7%E5%AE%B6%E8%BF%98%E6%98%AF%E5%B0%BD%E9%87%8F%E5%A4%9A%E5%AD%98%E9%92%B1%23) `63.5K 🔥`
1. [为奋进中国打call (Call for Endeavor China)](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E5%A5%8B%E8%BF%9B%E4%B8%AD%E5%9B%BD%E6%89%93call%23) `123.7K 🔥` `-75%`
1. [特朗普揭晓所谓伊朗大礼](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E6%8F%AD%E6%99%93%E6%89%80%E8%B0%93%E4%BC%8A%E6%9C%97%E5%A4%A7%E7%A4%BC%23) `112.0K 🔥` `-31%`
1. [伊朗禁往返敌方盟友港船只通过海峡 (Iran bans ships traveling to and from enemy and ally ports through the strait)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A6%81%E5%BE%80%E8%BF%94%E6%95%8C%E6%96%B9%E7%9B%9F%E5%8F%8B%E6%B8%AF%E8%88%B9%E5%8F%AA%E9%80%9A%E8%BF%87%E6%B5%B7%E5%B3%A1%23) `63.5K 🔥` `-22%`

Updated at 2026-03-28 07:57:45

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
