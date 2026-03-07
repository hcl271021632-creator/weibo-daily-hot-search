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

1. [全国两会正在关注 (The National Two Sessions are paying attention to)](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E4%B8%A4%E4%BC%9A%E6%AD%A3%E5%9C%A8%E5%85%B3%E6%B3%A8%23) `336.1K 🔥` `NEW`
1. [教资科三](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E7%A7%91%E4%B8%89%23) `191.9K 🔥` `NEW`
1. [在QQ也可以用OpenClaw了](https://s.weibo.com/weibo?q=%23%E5%9C%A8QQ%E4%B9%9F%E5%8F%AF%E4%BB%A5%E7%94%A8OpenClaw%E4%BA%86%23) `187.5K 🔥` `NEW`
1. [揽胜回应魏建军道歉](https://s.weibo.com/weibo?q=%23%E6%8F%BD%E8%83%9C%E5%9B%9E%E5%BA%94%E9%AD%8F%E5%BB%BA%E5%86%9B%E9%81%93%E6%AD%89%23) `94.6K 🔥` `NEW`
1. [逐玉 田耕纪](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20%E7%94%B0%E8%80%95%E7%BA%AA%23) `94.6K 🔥` `NEW`
1. [王鹤棣牵白鹿手](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E7%89%B5%E7%99%BD%E9%B9%BF%E6%89%8B%23) `94.4K 🔥` `NEW`
1. [李亮辟谣红果缩减真人短剧投入](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E4%BA%AE%E8%BE%9F%E8%B0%A3%E7%BA%A2%E6%9E%9C%E7%BC%A9%E5%87%8F%E7%9C%9F%E4%BA%BA%E7%9F%AD%E5%89%A7%E6%8A%95%E5%85%A5%23) `94.2K 🔥` `NEW`
1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `94.1K 🔥` `NEW`
1. [医生建议女性量力而行](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%A5%B3%E6%80%A7%E9%87%8F%E5%8A%9B%E8%80%8C%E8%A1%8C%23) `1.1M 🔥` `+39%`
1. [海洋闪充678 告别等待即刻出发 (Ocean Flash Charge 678 Say goodbye to waiting and set off immediately)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E6%B4%8B%E9%97%AA%E5%85%85678%20%E5%91%8A%E5%88%AB%E7%AD%89%E5%BE%85%E5%8D%B3%E5%88%BB%E5%87%BA%E5%8F%91%23) `592.1K 🔥` `+47%`
1. [我国义务教育达高收入国家平均水平](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E4%B9%89%E5%8A%A1%E6%95%99%E8%82%B2%E8%BE%BE%E9%AB%98%E6%94%B6%E5%85%A5%E5%9B%BD%E5%AE%B6%E5%B9%B3%E5%9D%87%E6%B0%B4%E5%B9%B3%23) `616.5K 🔥`
1. [鲁豫吃了多少盐才能讲出这些话 (How much salt did Lu Yu eat to say these words?)](https://s.weibo.com/weibo?q=%23%E9%B2%81%E8%B1%AB%E5%90%83%E4%BA%86%E5%A4%9A%E5%B0%91%E7%9B%90%E6%89%8D%E8%83%BD%E8%AE%B2%E5%87%BA%E8%BF%99%E4%BA%9B%E8%AF%9D%23) `591.8K 🔥`
1. [孩子一出生就自带口粮自带工资 (As soon as a child is born, he brings his own food and salary.)](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E4%B8%80%E5%87%BA%E7%94%9F%E5%B0%B1%E8%87%AA%E5%B8%A6%E5%8F%A3%E7%B2%AE%E8%87%AA%E5%B8%A6%E5%B7%A5%E8%B5%84%23) `753.7K 🔥` `-29%`
1. [雷军说未来每周或仅需工作3天](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E8%AF%B4%E6%9C%AA%E6%9D%A5%E6%AF%8F%E5%91%A8%E6%88%96%E4%BB%85%E9%9C%80%E5%B7%A5%E4%BD%9C3%E5%A4%A9%23) `393.9K 🔥` `-35%`
1. [孔雪儿将门独后首套造型](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E5%B0%86%E9%97%A8%E7%8B%AC%E5%90%8E%E9%A6%96%E5%A5%97%E9%80%A0%E5%9E%8B%23) `376.4K 🔥` `-37%`
1. [伊朗不许美以相关船只通过霍尔木兹 (Iran blocks US-Israeli ships from passing through Hormuz)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8D%E8%AE%B8%E7%BE%8E%E4%BB%A5%E7%9B%B8%E5%85%B3%E8%88%B9%E5%8F%AA%E9%80%9A%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%23) `309.1K 🔥` `-49%`
1. [留个学被老师科普了三天中国](https://s.weibo.com/weibo?q=%23%E7%95%99%E4%B8%AA%E5%AD%A6%E8%A2%AB%E8%80%81%E5%B8%88%E7%A7%91%E6%99%AE%E4%BA%86%E4%B8%89%E5%A4%A9%E4%B8%AD%E5%9B%BD%23) `192.0K 🔥` `-68%`
1. [WBG对战JDG](https://s.weibo.com/weibo?q=%23WBG%E5%AF%B9%E6%88%98JDG%23) `191.1K 🔥` `-67%`
1. [伊朗总统称不再首先攻击邻国](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E7%A7%B0%E4%B8%8D%E5%86%8D%E9%A6%96%E5%85%88%E6%94%BB%E5%87%BB%E9%82%BB%E5%9B%BD%23) `190.3K 🔥` `-68%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `189.5K 🔥` `-68%`
1. [花少神一季鬼一季的定律 (The law of Hua Shao Shen and ghosts)](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%B0%91%E7%A5%9E%E4%B8%80%E5%AD%A3%E9%AC%BC%E4%B8%80%E5%AD%A3%E7%9A%84%E5%AE%9A%E5%BE%8B%23) `189.0K 🔥` `-68%`
1. [建议像治理黄色网站治理网盘浏览器 (It is recommended to manage pornographic websites and manage the network disk browser)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%83%8F%E6%B2%BB%E7%90%86%E9%BB%84%E8%89%B2%E7%BD%91%E7%AB%99%E6%B2%BB%E7%90%86%E7%BD%91%E7%9B%98%E6%B5%8F%E8%A7%88%E5%99%A8%23) `188.5K 🔥` `-68%`
1. [十个勤天到底有多少个群](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%B8%AA%E5%8B%A4%E5%A4%A9%E5%88%B0%E5%BA%95%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E7%BE%A4%23) `187.2K 🔥` `-69%`
1. [浙产减重药一个疗程平均能瘦15%](https://s.weibo.com/weibo?q=%23%E6%B5%99%E4%BA%A7%E5%87%8F%E9%87%8D%E8%8D%AF%E4%B8%80%E4%B8%AA%E7%96%97%E7%A8%8B%E5%B9%B3%E5%9D%87%E8%83%BD%E7%98%A615%25%23) `186.1K 🔥` `-68%`
1. [教资科二 (Teaching Resources Section 2)](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%E7%A7%91%E4%BA%8C%23) `185.5K 🔥` `-68%`
1. [伊朗霍尔木兹甘省发生4.3级地震 (A 4.3-magnitude earthquake hits Iran's Hormozgan province)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E7%94%98%E7%9C%81%E5%8F%91%E7%94%9F4.3%E7%BA%A7%E5%9C%B0%E9%9C%87%23) `184.7K 🔥` `-69%`
1. [何广智 名侦探学院是什么单位](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%B9%BF%E6%99%BA%20%E5%90%8D%E4%BE%A6%E6%8E%A2%E5%AD%A6%E9%99%A2%E6%98%AF%E4%BB%80%E4%B9%88%E5%8D%95%E4%BD%8D%23) `184.5K 🔥` `-69%`
1. [王安宇裴秀智孙千同框 (Wang Anyu, Pei Xiuzhi and Sun Qian are in the same frame)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E8%A3%B4%E7%A7%80%E6%99%BA%E5%AD%99%E5%8D%83%E5%90%8C%E6%A1%86%23) `183.8K 🔥` `-69%`
1. [中国的身份证果然高级 (China’s ID card is really advanced)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9A%84%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%9E%9C%E7%84%B6%E9%AB%98%E7%BA%A7%23) `182.9K 🔥` `-69%`
1. [伊朗宣布关闭股市](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%A3%E5%B8%83%E5%85%B3%E9%97%AD%E8%82%A1%E5%B8%82%23) `182.7K 🔥` `-69%`
1. [王一博拒绝不了攀岩绳](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%8B%92%E7%BB%9D%E4%B8%8D%E4%BA%86%E6%94%80%E5%B2%A9%E7%BB%B3%23) `166.0K 🔥` `-72%`
1. [白鹿因为当模特患上风湿病 (Bailu suffered from rheumatism because of his work as a model)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%9B%A0%E4%B8%BA%E5%BD%93%E6%A8%A1%E7%89%B9%E6%82%A3%E4%B8%8A%E9%A3%8E%E6%B9%BF%E7%97%85%23) `141.9K 🔥` `-76%`
1. [伊朗7小时5轮导弹射向以色列 (Iran fired five rounds of missiles at Israel in 7 hours)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%977%E5%B0%8F%E6%97%B65%E8%BD%AE%E5%AF%BC%E5%BC%B9%E5%B0%84%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `128.9K 🔥` `-78%`
1. [短剧霸总一件衣服12人穿](https://s.weibo.com/weibo?q=%23%E7%9F%AD%E5%89%A7%E9%9C%B8%E6%80%BB%E4%B8%80%E4%BB%B6%E8%A1%A3%E6%9C%8D12%E4%BA%BA%E7%A9%BF%23) `125.1K 🔥` `-78%`
1. [曝花少8拟邀宁艺卓刘浩存](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%8A%B1%E5%B0%918%E6%8B%9F%E9%82%80%E5%AE%81%E8%89%BA%E5%8D%93%E5%88%98%E6%B5%A9%E5%AD%98%23) `105.9K 🔥` `-82%`
1. [迪拜国际机场紧急疏散旅客](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E6%8B%9C%E5%9B%BD%E9%99%85%E6%9C%BA%E5%9C%BA%E7%B4%A7%E6%80%A5%E7%96%8F%E6%95%A3%E6%97%85%E5%AE%A2%23) `97.5K 🔥` `-83%`
1. [没有女生能拒绝这么暖心的地铁标语](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E6%9C%89%E5%A5%B3%E7%94%9F%E8%83%BD%E6%8B%92%E7%BB%9D%E8%BF%99%E4%B9%88%E6%9A%96%E5%BF%83%E7%9A%84%E5%9C%B0%E9%93%81%E6%A0%87%E8%AF%AD%23) `96.1K 🔥` `-83%`
1. [陈小春再也没让应采儿上这种节目](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%B0%8F%E6%98%A5%E5%86%8D%E4%B9%9F%E6%B2%A1%E8%AE%A9%E5%BA%94%E9%87%87%E5%84%BF%E4%B8%8A%E8%BF%99%E7%A7%8D%E8%8A%82%E7%9B%AE%23) `96.1K 🔥` `-83%`
1. [袁姗姗第一章异国千金](https://s.weibo.com/weibo?q=%23%E8%A2%81%E5%A7%97%E5%A7%97%E7%AC%AC%E4%B8%80%E7%AB%A0%E5%BC%82%E5%9B%BD%E5%8D%83%E9%87%91%23) `95.8K 🔥` `-84%`
1. [JackeyLove的号是买的](https://s.weibo.com/weibo?q=%23JackeyLove%E7%9A%84%E5%8F%B7%E6%98%AF%E4%B9%B0%E7%9A%84%23) `94.7K 🔥` `-84%`
1. [逐玉首日云合 (Clouds converge on the first day of chasing jade)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E9%A6%96%E6%97%A5%E4%BA%91%E5%90%88%23) `94.7K 🔥` `-84%`
1. [90后单亲妈妈摆地摊起家年赚上千万 (A single mother born in the 1990s started a street stall and earned tens of millions a year)](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E5%8D%95%E4%BA%B2%E5%A6%88%E5%A6%88%E6%91%86%E5%9C%B0%E6%91%8A%E8%B5%B7%E5%AE%B6%E5%B9%B4%E8%B5%9A%E4%B8%8A%E5%8D%83%E4%B8%87%23) `94.6K 🔥` `-84%`
1. [拿得出手却带不出门的徒弟](https://s.weibo.com/weibo?q=%23%E6%8B%BF%E5%BE%97%E5%87%BA%E6%89%8B%E5%8D%B4%E5%B8%A6%E4%B8%8D%E5%87%BA%E9%97%A8%E7%9A%84%E5%BE%92%E5%BC%9F%23) `94.6K 🔥` `-84%`
1. [刘亦菲8秒换胎 (Liu Yifei changes tires in 8 seconds)](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B28%E7%A7%92%E6%8D%A2%E8%83%8E%23) `94.5K 🔥` `-84%`
1. [谁敢信这是20块的猫啊 (Who can believe that this is a 20 yuan cat?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%95%A2%E4%BF%A1%E8%BF%99%E6%98%AF20%E5%9D%97%E7%9A%84%E7%8C%AB%E5%95%8A%23) `94.5K 🔥` `-84%`
1. [麦当劳CEO再被网友扒出假吃](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E5%86%8D%E8%A2%AB%E7%BD%91%E5%8F%8B%E6%89%92%E5%87%BA%E5%81%87%E5%90%83%23) `94.4K 🔥` `-84%`
1. [伊朗称尚未大规模使用新型武器](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%B0%9A%E6%9C%AA%E5%A4%A7%E8%A7%84%E6%A8%A1%E4%BD%BF%E7%94%A8%E6%96%B0%E5%9E%8B%E6%AD%A6%E5%99%A8%23) `94.3K 🔥` `-84%`
1. [猫像喝醉了被鸭子带回家 (The cat looks like it was brought home by a duck when it was drunk)](https://s.weibo.com/weibo?q=%23%E7%8C%AB%E5%83%8F%E5%96%9D%E9%86%89%E4%BA%86%E8%A2%AB%E9%B8%AD%E5%AD%90%E5%B8%A6%E5%9B%9E%E5%AE%B6%23) `94.3K 🔥` `-83%`
1. [教资](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%B5%84%23) `94.3K 🔥` `-84%`
1. [何炅把张远远行看成张远远](https://s.weibo.com/weibo?q=%23%E4%BD%95%E7%82%85%E6%8A%8A%E5%BC%A0%E8%BF%9C%E8%BF%9C%E8%A1%8C%E7%9C%8B%E6%88%90%E5%BC%A0%E8%BF%9C%E8%BF%9C%23) `94.2K 🔥` `-84%`
1. [父亲回应9岁女儿埃及骑马霸气维权](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E5%9B%9E%E5%BA%949%E5%B2%81%E5%A5%B3%E5%84%BF%E5%9F%83%E5%8F%8A%E9%AA%91%E9%A9%AC%E9%9C%B8%E6%B0%94%E7%BB%B4%E6%9D%83%23) `94.2K 🔥` `-84%`
1. [吃自助烤肉时的几类人 (Several types of people eating buffet barbecue)](https://s.weibo.com/weibo?q=%23%E5%90%83%E8%87%AA%E5%8A%A9%E7%83%A4%E8%82%89%E6%97%B6%E7%9A%84%E5%87%A0%E7%B1%BB%E4%BA%BA%23) `94.1K 🔥` `-84%`

Updated at 2026-03-07 18:52:02

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
