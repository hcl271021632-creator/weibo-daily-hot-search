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

1. [普高扩招是否意味高中将纳入义务教育 (Does the expansion of general high school enrollment mean that high schools will be included in compulsory education?)](https://s.weibo.com/weibo?q=%23%E6%99%AE%E9%AB%98%E6%89%A9%E6%8B%9B%E6%98%AF%E5%90%A6%E6%84%8F%E5%91%B3%E9%AB%98%E4%B8%AD%E5%B0%86%E7%BA%B3%E5%85%A5%E4%B9%89%E5%8A%A1%E6%95%99%E8%82%B2%23) `213.3K 🔥` `NEW`
1. [医生建议女性量力而行](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%A5%B3%E6%80%A7%E9%87%8F%E5%8A%9B%E8%80%8C%E8%A1%8C%23) `177.9K 🔥` `NEW`
1. [鲁豫吃了多少盐才能讲出这些话](https://s.weibo.com/weibo?q=%23%E9%B2%81%E8%B1%AB%E5%90%83%E4%BA%86%E5%A4%9A%E5%B0%91%E7%9B%90%E6%89%8D%E8%83%BD%E8%AE%B2%E5%87%BA%E8%BF%99%E4%BA%9B%E8%AF%9D%23) `177.8K 🔥` `NEW`
1. [十个勤天到底有多少个群](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%B8%AA%E5%8B%A4%E5%A4%A9%E5%88%B0%E5%BA%95%E6%9C%89%E5%A4%9A%E5%B0%91%E4%B8%AA%E7%BE%A4%23) `177.7K 🔥` `NEW`
1. [伊朗宣布关闭股市](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AE%A3%E5%B8%83%E5%85%B3%E9%97%AD%E8%82%A1%E5%B8%82%23) `177.3K 🔥` `NEW`
1. [袁姗姗第一章异国千金](https://s.weibo.com/weibo?q=%23%E8%A2%81%E5%A7%97%E5%A7%97%E7%AC%AC%E4%B8%80%E7%AB%A0%E5%BC%82%E5%9B%BD%E5%8D%83%E9%87%91%23) `177.1K 🔥` `NEW`
1. [王安宇裴秀智孙千同框](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E5%AE%89%E5%AE%87%E8%A3%B4%E7%A7%80%E6%99%BA%E5%AD%99%E5%8D%83%E5%90%8C%E6%A1%86%23) `166.8K 🔥` `NEW`
1. [伊朗总统向邻国表示歉意](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E5%90%91%E9%82%BB%E5%9B%BD%E8%A1%A8%E7%A4%BA%E6%AD%89%E6%84%8F%23) `166.7K 🔥` `NEW`
1. [留个学被老师科普了三天中国](https://s.weibo.com/weibo?q=%23%E7%95%99%E4%B8%AA%E5%AD%A6%E8%A2%AB%E8%80%81%E5%B8%88%E7%A7%91%E6%99%AE%E4%BA%86%E4%B8%89%E5%A4%A9%E4%B8%AD%E5%9B%BD%23) `166.5K 🔥` `NEW`
1. [曝花少8拟邀宁艺卓刘浩存](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%8A%B1%E5%B0%918%E6%8B%9F%E9%82%80%E5%AE%81%E8%89%BA%E5%8D%93%E5%88%98%E6%B5%A9%E5%AD%98%23) `166.0K 🔥` `NEW`
1. [谁敢信这是20块的猫啊 (Who can believe that this is a 20 yuan cat?)](https://s.weibo.com/weibo?q=%23%E8%B0%81%E6%95%A2%E4%BF%A1%E8%BF%99%E6%98%AF20%E5%9D%97%E7%9A%84%E7%8C%AB%E5%95%8A%23) `165.9K 🔥` `NEW`
1. [几十年前给小猫拍了很多照片](https://s.weibo.com/weibo?q=%23%E5%87%A0%E5%8D%81%E5%B9%B4%E5%89%8D%E7%BB%99%E5%B0%8F%E7%8C%AB%E6%8B%8D%E4%BA%86%E5%BE%88%E5%A4%9A%E7%85%A7%E7%89%87%23) `165.6K 🔥` `NEW`
1. [WBG对战JDG](https://s.weibo.com/weibo?q=%23WBG%E5%AF%B9%E6%88%98JDG%23) `165.2K 🔥` `NEW`
1. [秦岚在花少头发都没油成这样 (Qin Lan’s hair is not even oily like this in Hua Shao)](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%B2%9A%E5%9C%A8%E8%8A%B1%E5%B0%91%E5%A4%B4%E5%8F%91%E9%83%BD%E6%B2%A1%E6%B2%B9%E6%88%90%E8%BF%99%E6%A0%B7%23) `477.9K 🔥` `+129%`
1. [何广智 名侦探学院是什么单位](https://s.weibo.com/weibo?q=%23%E4%BD%95%E5%B9%BF%E6%99%BA%20%E5%90%8D%E4%BE%A6%E6%8E%A2%E5%AD%A6%E9%99%A2%E6%98%AF%E4%BB%80%E4%B9%88%E5%8D%95%E4%BD%8D%23) `215.5K 🔥` `+100%`
1. [拿得出手却带不出门的徒弟](https://s.weibo.com/weibo?q=%23%E6%8B%BF%E5%BE%97%E5%87%BA%E6%89%8B%E5%8D%B4%E5%B8%A6%E4%B8%8D%E5%87%BA%E9%97%A8%E7%9A%84%E5%BE%92%E5%BC%9F%23) `215.1K 🔥` `+146%`
1. [不会化妆的女生建议反复观看 (Girls who don’t know how to wear makeup are recommended to watch it again and again)](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E4%BC%9A%E5%8C%96%E5%A6%86%E7%9A%84%E5%A5%B3%E7%94%9F%E5%BB%BA%E8%AE%AE%E5%8F%8D%E5%A4%8D%E8%A7%82%E7%9C%8B%23) `214.2K 🔥` `+49%`
1. [迪拜国际机场紧急疏散旅客](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E6%8B%9C%E5%9B%BD%E9%99%85%E6%9C%BA%E5%9C%BA%E7%B4%A7%E6%80%A5%E7%96%8F%E6%95%A3%E6%97%85%E5%AE%A2%23) `212.1K 🔥` `+89%`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `211.0K 🔥` `+65%`
1. [花少神一季鬼一季的定律 (The law of Hua Shao Shen and ghosts)](https://s.weibo.com/weibo?q=%23%E8%8A%B1%E5%B0%91%E7%A5%9E%E4%B8%80%E5%AD%A3%E9%AC%BC%E4%B8%80%E5%AD%A3%E7%9A%84%E5%AE%9A%E5%BE%8B%23) `210.7K 🔥` `+60%`
1. [建议像治理黄色网站治理网盘浏览器](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%83%8F%E6%B2%BB%E7%90%86%E9%BB%84%E8%89%B2%E7%BD%91%E7%AB%99%E6%B2%BB%E7%90%86%E7%BD%91%E7%9B%98%E6%B5%8F%E8%A7%88%E5%99%A8%23) `178.0K 🔥` `+40%`
1. [麦当劳CEO再被网友扒出假吃](https://s.weibo.com/weibo?q=%23%E9%BA%A6%E5%BD%93%E5%8A%B3CEO%E5%86%8D%E8%A2%AB%E7%BD%91%E5%8F%8B%E6%89%92%E5%87%BA%E5%81%87%E5%90%83%23) `177.8K 🔥` `+43%`
1. [90后单亲妈妈摆地摊起家年赚上千万 (A single mother born in the 1990s started a street stall and earned tens of millions a year)](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E5%8D%95%E4%BA%B2%E5%A6%88%E5%A6%88%E6%91%86%E5%9C%B0%E6%91%8A%E8%B5%B7%E5%AE%B6%E5%B9%B4%E8%B5%9A%E4%B8%8A%E5%8D%83%E4%B8%87%23) `177.5K 🔥` `+61%`
1. [伊朗霍尔木兹甘省发生4.3级地震](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E7%94%98%E7%9C%81%E5%8F%91%E7%94%9F4.3%E7%BA%A7%E5%9C%B0%E9%9C%87%23) `177.5K 🔥` `+47%`
1. [中国的身份证果然高级 (China’s ID card is really advanced)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E5%9B%BD%E7%9A%84%E8%BA%AB%E4%BB%BD%E8%AF%81%E6%9E%9C%E7%84%B6%E9%AB%98%E7%BA%A7%23) `177.2K 🔥` `+52%`
1. [伊朗不许美以相关船只通过霍尔木兹 (Iran blocks US-Israeli ships from passing through Hormuz)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E4%B8%8D%E8%AE%B8%E7%BE%8E%E4%BB%A5%E7%9B%B8%E5%85%B3%E8%88%B9%E5%8F%AA%E9%80%9A%E8%BF%87%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%23) `177.2K 🔥` `+37%`
1. [伊朗7小时5轮导弹射向以色列 (Iran fired five rounds of missiles at Israel in 7 hours)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%977%E5%B0%8F%E6%97%B65%E8%BD%AE%E5%AF%BC%E5%BC%B9%E5%B0%84%E5%90%91%E4%BB%A5%E8%89%B2%E5%88%97%23) `174.4K 🔥` `+52%`
1. [白鹿因为当模特患上风湿病 (Bailu suffered from rheumatism because of his work as a model)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%9B%A0%E4%B8%BA%E5%BD%93%E6%A8%A1%E7%89%B9%E6%82%A3%E4%B8%8A%E9%A3%8E%E6%B9%BF%E7%97%85%23) `166.7K 🔥` `+47%`
1. [人社部部长回应AI抢饭碗言论 (Minister of Human Resources and Social Security responds to comments about AI stealing jobs)](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E7%A4%BE%E9%83%A8%E9%83%A8%E9%95%BF%E5%9B%9E%E5%BA%94AI%E6%8A%A2%E9%A5%AD%E7%A2%97%E8%A8%80%E8%AE%BA%23) `166.6K 🔥` `+132%`
1. [刘亦菲8秒换胎](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B28%E7%A7%92%E6%8D%A2%E8%83%8E%23) `166.5K 🔥` `+48%`
1. [伊朗称尚未大规模使用新型武器](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E5%B0%9A%E6%9C%AA%E5%A4%A7%E8%A7%84%E6%A8%A1%E4%BD%BF%E7%94%A8%E6%96%B0%E5%9E%8B%E6%AD%A6%E5%99%A8%23) `166.4K 🔥` `+66%`
1. [路虎揽胜回应魏建军道歉](https://s.weibo.com/weibo?q=%23%E8%B7%AF%E8%99%8E%E6%8F%BD%E8%83%9C%E5%9B%9E%E5%BA%94%E9%AD%8F%E5%BB%BA%E5%86%9B%E9%81%93%E6%AD%89%23) `166.4K 🔥` `+59%`
1. [吃自助烤肉时的几类人 (Several types of people eating buffet barbecue)](https://s.weibo.com/weibo?q=%23%E5%90%83%E8%87%AA%E5%8A%A9%E7%83%A4%E8%82%89%E6%97%B6%E7%9A%84%E5%87%A0%E7%B1%BB%E4%BA%BA%23) `166.3K 🔥` `+141%`
1. [王传君恶剪了所有人](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BC%A0%E5%90%9B%E6%81%B6%E5%89%AA%E4%BA%86%E6%89%80%E6%9C%89%E4%BA%BA%23) `166.2K 🔥` `+50%`
1. [省长说抢不到苏超的票找副省长](https://s.weibo.com/weibo?q=%23%E7%9C%81%E9%95%BF%E8%AF%B4%E6%8A%A2%E4%B8%8D%E5%88%B0%E8%8B%8F%E8%B6%85%E7%9A%84%E7%A5%A8%E6%89%BE%E5%89%AF%E7%9C%81%E9%95%BF%23) `166.1K 🔥` `+111%`
1. [秦岚事事有回应](https://s.weibo.com/weibo?q=%23%E7%A7%A6%E5%B2%9A%E4%BA%8B%E4%BA%8B%E6%9C%89%E5%9B%9E%E5%BA%94%23) `165.9K 🔥` `+110%`
1. [白鹿回应和跑男团关系](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%9B%9E%E5%BA%94%E5%92%8C%E8%B7%91%E7%94%B7%E5%9B%A2%E5%85%B3%E7%B3%BB%23) `165.8K 🔥` `+105%`
1. [工作脑vs事业脑](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%BD%9C%E8%84%91vs%E4%BA%8B%E4%B8%9A%E8%84%91%23) `165.7K 🔥` `+25%`
1. [香飘飘投入1000万用于女性经期关爱](https://s.weibo.com/weibo?q=%23%E9%A6%99%E9%A3%98%E9%A3%98%E6%8A%95%E5%85%A51000%E4%B8%87%E7%94%A8%E4%BA%8E%E5%A5%B3%E6%80%A7%E7%BB%8F%E6%9C%9F%E5%85%B3%E7%88%B1%23) `165.6K 🔥` `+40%`
1. [镖人大沙暴是实拍八级大风 (The big sandstorm in Escort is a real-life 8-level wind)](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E5%A4%A7%E6%B2%99%E6%9A%B4%E6%98%AF%E5%AE%9E%E6%8B%8D%E5%85%AB%E7%BA%A7%E5%A4%A7%E9%A3%8E%23) `165.5K 🔥` `+90%`
1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `165.4K 🔥` `+39%`
1. [JackeyLove回应退役 (JackeyLove responds to retirement)](https://s.weibo.com/weibo?q=%23JackeyLove%E5%9B%9E%E5%BA%94%E9%80%80%E5%BD%B9%23) `165.3K 🔥` `+112%`
1. [霍启刚建议降低中等收入群体税率 (Huo Qigang proposes lowering tax rates for middle-income groups)](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%90%AF%E5%88%9A%E5%BB%BA%E8%AE%AE%E9%99%8D%E4%BD%8E%E4%B8%AD%E7%AD%89%E6%94%B6%E5%85%A5%E7%BE%A4%E4%BD%93%E7%A8%8E%E7%8E%87%23) `165.3K 🔥` `+55%`
1. [金饰克价涨到1607元 (Gold jewelry price rises to 1,607 yuan per gram)](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E5%85%8B%E4%BB%B7%E6%B6%A8%E5%88%B01607%E5%85%83%23) `165.3K 🔥` `+89%`
1. [孩子一出生就自带口粮自带工资](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E4%B8%80%E5%87%BA%E7%94%9F%E5%B0%B1%E8%87%AA%E5%B8%A6%E5%8F%A3%E7%B2%AE%E8%87%AA%E5%B8%A6%E5%B7%A5%E8%B5%84%23) `1.1M 🔥`
1. [雷军说未来每周或仅需工作3天](https://s.weibo.com/weibo?q=%23%E9%9B%B7%E5%86%9B%E8%AF%B4%E6%9C%AA%E6%9D%A5%E6%AF%8F%E5%91%A8%E6%88%96%E4%BB%85%E9%9C%80%E5%B7%A5%E4%BD%9C3%E5%A4%A9%23) `766.9K 🔥`
1. [我国义务教育达高收入国家平均水平](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E4%B9%89%E5%8A%A1%E6%95%99%E8%82%B2%E8%BE%BE%E9%AB%98%E6%94%B6%E5%85%A5%E5%9B%BD%E5%AE%B6%E5%B9%B3%E5%9D%87%E6%B0%B4%E5%B9%B3%23) `607.7K 🔥`
1. [漂亮过节用美团医美 (Be beautiful during the holidays with Meituan Medical Beauty)](https://s.weibo.com/weibo?q=%23%E6%BC%82%E4%BA%AE%E8%BF%87%E8%8A%82%E7%94%A8%E7%BE%8E%E5%9B%A2%E5%8C%BB%E7%BE%8E%23) `602.5K 🔥`
1. [逐玉首日云合](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E9%A6%96%E6%97%A5%E4%BA%91%E5%90%88%23) `217.0K 🔥`
1. [伊朗总统称不再首先攻击邻国](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E7%A7%B0%E4%B8%8D%E5%86%8D%E9%A6%96%E5%85%88%E6%94%BB%E5%87%BB%E9%82%BB%E5%9B%BD%23) `216.3K 🔥`
1. [40年前的丧假制度该更新了 (The 40-year-old bereavement leave system needs to be updated)](https://s.weibo.com/weibo?q=%2340%E5%B9%B4%E5%89%8D%E7%9A%84%E4%B8%A7%E5%81%87%E5%88%B6%E5%BA%A6%E8%AF%A5%E6%9B%B4%E6%96%B0%E4%BA%86%23) `166.1K 🔥`

Updated at 2026-03-07 17:39:01

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
