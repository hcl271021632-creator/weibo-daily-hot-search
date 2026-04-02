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

1. [父亲车上卖女儿拼豆收入反超车费 (Father's income from selling his daughter's beans in his car exceeds the fare)](https://s.weibo.com/weibo?q=%23%E7%88%B6%E4%BA%B2%E8%BD%A6%E4%B8%8A%E5%8D%96%E5%A5%B3%E5%84%BF%E6%8B%BC%E8%B1%86%E6%94%B6%E5%85%A5%E5%8F%8D%E8%B6%85%E8%BD%A6%E8%B4%B9%23) `1.2M 🔥` `NEW`
1. [3人售卖艺人隐私被采取刑事强制措施](https://s.weibo.com/weibo?q=%233%E4%BA%BA%E5%94%AE%E5%8D%96%E8%89%BA%E4%BA%BA%E9%9A%90%E7%A7%81%E8%A2%AB%E9%87%87%E5%8F%96%E5%88%91%E4%BA%8B%E5%BC%BA%E5%88%B6%E6%8E%AA%E6%96%BD%23) `791.7K 🔥` `NEW`
1. [伊朗总统致美国人民公开信](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%80%BB%E7%BB%9F%E8%87%B4%E7%BE%8E%E5%9B%BD%E4%BA%BA%E6%B0%91%E5%85%AC%E5%BC%80%E4%BF%A1%23) `783.9K 🔥` `NEW`
1. [日本终于露出獠牙](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E7%BB%88%E4%BA%8E%E9%9C%B2%E5%87%BA%E7%8D%A0%E7%89%99%23) `430.9K 🔥` `NEW`
1. [山西一煤业公司冒顶事故4人遇难](https://s.weibo.com/weibo?q=%23%E5%B1%B1%E8%A5%BF%E4%B8%80%E7%85%A4%E4%B8%9A%E5%85%AC%E5%8F%B8%E5%86%92%E9%A1%B6%E4%BA%8B%E6%95%854%E4%BA%BA%E9%81%87%E9%9A%BE%23) `267.5K 🔥` `NEW`
1. [白日提灯热度](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E7%83%AD%E5%BA%A6%23) `251.3K 🔥` `NEW`
1. [张雪机车夺冠含金量](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E5%A4%BA%E5%86%A0%E5%90%AB%E9%87%91%E9%87%8F%23) `176.6K 🔥` `NEW`
1. [张雪与湖南卫视立下新承诺](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E4%B8%8E%E6%B9%96%E5%8D%97%E5%8D%AB%E8%A7%86%E7%AB%8B%E4%B8%8B%E6%96%B0%E6%89%BF%E8%AF%BA%23) `165.9K 🔥` `NEW`
1. [美国执行载人绕月任务火箭发射升空](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E6%89%A7%E8%A1%8C%E8%BD%BD%E4%BA%BA%E7%BB%95%E6%9C%88%E4%BB%BB%E5%8A%A1%E7%81%AB%E7%AE%AD%E5%8F%91%E5%B0%84%E5%8D%87%E7%A9%BA%23) `160.6K 🔥` `NEW`
1. [周杰伦藏了10余年的求婚画面将公开](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E8%97%8F%E4%BA%8610%E4%BD%99%E5%B9%B4%E7%9A%84%E6%B1%82%E5%A9%9A%E7%94%BB%E9%9D%A2%E5%B0%86%E5%85%AC%E5%BC%80%23) `159.8K 🔥` `NEW`
1. [以为能用其实已经过期的东西 (Thinking you can use something that is actually expired)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E4%B8%BA%E8%83%BD%E7%94%A8%E5%85%B6%E5%AE%9E%E5%B7%B2%E7%BB%8F%E8%BF%87%E6%9C%9F%E7%9A%84%E4%B8%9C%E8%A5%BF%23) `126.0K 🔥` `NEW`
1. [美国TikTok禁令演不下去了吗](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BDTikTok%E7%A6%81%E4%BB%A4%E6%BC%94%E4%B8%8D%E4%B8%8B%E5%8E%BB%E4%BA%86%E5%90%97%23) `123.4K 🔥` `NEW`
1. [美国50多年来首次载人飞向月球](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD50%E5%A4%9A%E5%B9%B4%E6%9D%A5%E9%A6%96%E6%AC%A1%E8%BD%BD%E4%BA%BA%E9%A3%9E%E5%90%91%E6%9C%88%E7%90%83%23) `123.2K 🔥` `NEW`
1. [前女友说脆皮三首热单是她写的](https://s.weibo.com/weibo?q=%23%E5%89%8D%E5%A5%B3%E5%8F%8B%E8%AF%B4%E8%84%86%E7%9A%AE%E4%B8%89%E9%A6%96%E7%83%AD%E5%8D%95%E6%98%AF%E5%A5%B9%E5%86%99%E7%9A%84%23) `107.4K 🔥` `NEW`
1. [哈尔滨一商场半开放男童厕所引质疑](https://s.weibo.com/weibo?q=%23%E5%93%88%E5%B0%94%E6%BB%A8%E4%B8%80%E5%95%86%E5%9C%BA%E5%8D%8A%E5%BC%80%E6%94%BE%E7%94%B7%E7%AB%A5%E5%8E%95%E6%89%80%E5%BC%95%E8%B4%A8%E7%96%91%23) `105.4K 🔥` `NEW`
1. [伊朗最高领袖首次讲话](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E9%A6%96%E6%AC%A1%E8%AE%B2%E8%AF%9D%23) `104.5K 🔥` `NEW`
1. [有线耳机穿搭爆火](https://s.weibo.com/weibo?q=%23%E6%9C%89%E7%BA%BF%E8%80%B3%E6%9C%BA%E7%A9%BF%E6%90%AD%E7%88%86%E7%81%AB%23) `102.0K 🔥` `NEW`
1. [工人一次失误竟找回失传800年的技艺](https://s.weibo.com/weibo?q=%23%E5%B7%A5%E4%BA%BA%E4%B8%80%E6%AC%A1%E5%A4%B1%E8%AF%AF%E7%AB%9F%E6%89%BE%E5%9B%9E%E5%A4%B1%E4%BC%A0800%E5%B9%B4%E7%9A%84%E6%8A%80%E8%89%BA%23) `100.4K 🔥` `NEW`
1. [黄金3连涨](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%913%E8%BF%9E%E6%B6%A8%23) `98.9K 🔥` `NEW`
1. [曾舜晞用一整晚磨0.1页剧本](https://s.weibo.com/weibo?q=%23%E6%9B%BE%E8%88%9C%E6%99%9E%E7%94%A8%E4%B8%80%E6%95%B4%E6%99%9A%E7%A3%A80.1%E9%A1%B5%E5%89%A7%E6%9C%AC%23) `98.0K 🔥` `NEW`
1. [4个动作狂瘦小腿 (4 moves to slim down your calves)](https://s.weibo.com/weibo?q=%234%E4%B8%AA%E5%8A%A8%E4%BD%9C%E7%8B%82%E7%98%A6%E5%B0%8F%E8%85%BF%23) `89.5K 🔥` `NEW`
1. [龙门石窟新发现一处石刻金刚经](https://s.weibo.com/weibo?q=%23%E9%BE%99%E9%97%A8%E7%9F%B3%E7%AA%9F%E6%96%B0%E5%8F%91%E7%8E%B0%E4%B8%80%E5%A4%84%E7%9F%B3%E5%88%BB%E9%87%91%E5%88%9A%E7%BB%8F%23) `88.2K 🔥` `NEW`
1. [危险关系](https://s.weibo.com/weibo?q=%23%E5%8D%B1%E9%99%A9%E5%85%B3%E7%B3%BB%23) `86.9K 🔥` `NEW`
1. [弟弟吐槽妈妈偏心哥哥](https://s.weibo.com/weibo?q=%23%E5%BC%9F%E5%BC%9F%E5%90%90%E6%A7%BD%E5%A6%88%E5%A6%88%E5%81%8F%E5%BF%83%E5%93%A5%E5%93%A5%23) `84.2K 🔥` `NEW`
1. [伊朗10分钟5波导弹袭击以色列](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%9710%E5%88%86%E9%92%9F5%E6%B3%A2%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%E4%BB%A5%E8%89%B2%E5%88%97%23) `761.8K 🔥` `+394%`
1. [收到了去世好友的微信回复](https://s.weibo.com/weibo?q=%23%E6%94%B6%E5%88%B0%E4%BA%86%E5%8E%BB%E4%B8%96%E5%A5%BD%E5%8F%8B%E7%9A%84%E5%BE%AE%E4%BF%A1%E5%9B%9E%E5%A4%8D%23) `759.7K 🔥` `+58%`
1. [清明假期首选神州租车 (Car rental in China is the first choice during the Qingming Festival)](https://s.weibo.com/weibo?q=%23%E6%B8%85%E6%98%8E%E5%81%87%E6%9C%9F%E9%A6%96%E9%80%89%E7%A5%9E%E5%B7%9E%E7%A7%9F%E8%BD%A6%23) `486.8K 🔥` `+1429%`
1. [王者荣耀无双](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%80%85%E8%8D%A3%E8%80%80%E6%97%A0%E5%8F%8C%23) `339.5K 🔥` `+383%`
1. [杨紫 没人通知我啊](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%20%E6%B2%A1%E4%BA%BA%E9%80%9A%E7%9F%A5%E6%88%91%E5%95%8A%23) `265.6K 🔥` `+65%`
1. [医生谈全红婵减肥一天只吃一顿饭 (Doctor talks about Quan Hongchan eating only one meal a day to lose weight)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E8%B0%88%E5%85%A8%E7%BA%A2%E5%A9%B5%E5%87%8F%E8%82%A5%E4%B8%80%E5%A4%A9%E5%8F%AA%E5%90%83%E4%B8%80%E9%A1%BF%E9%A5%AD%23) `257.4K 🔥` `+94%`
1. [马立奥有妹妹了 (Mario has a sister)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E7%AB%8B%E5%A5%A5%E6%9C%89%E5%A6%B9%E5%A6%B9%E4%BA%86%23) `223.9K 🔥` `+42%`
1. [甲骨文3万人一觉睡醒工作没了](https://s.weibo.com/weibo?q=%23%E7%94%B2%E9%AA%A8%E6%96%873%E4%B8%87%E4%BA%BA%E4%B8%80%E8%A7%89%E7%9D%A1%E9%86%92%E5%B7%A5%E4%BD%9C%E6%B2%A1%E4%BA%86%23) `210.9K 🔥` `+33%`
1. [保时捷女销售再夺一季度销冠](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E6%97%B6%E6%8D%B7%E5%A5%B3%E9%94%80%E5%94%AE%E5%86%8D%E5%A4%BA%E4%B8%80%E5%AD%A3%E5%BA%A6%E9%94%80%E5%86%A0%23) `168.3K 🔥` `+34%`
1. [为什么木耳不能直接用水泡 (Why can’t fungus be soaked directly in water?)](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E6%9C%A8%E8%80%B3%E4%B8%8D%E8%83%BD%E7%9B%B4%E6%8E%A5%E7%94%A8%E6%B0%B4%E6%B3%A1%23) `165.7K 🔥` `+35%`
1. [很少用top来形容一个土豆 (Top is rarely used to describe a potato.)](https://s.weibo.com/weibo?q=%23%E5%BE%88%E5%B0%91%E7%94%A8top%E6%9D%A5%E5%BD%A2%E5%AE%B9%E4%B8%80%E4%B8%AA%E5%9C%9F%E8%B1%86%23) `135.4K 🔥` `+90%`
1. [金价急速上涨 (Gold prices rise rapidly)](https://s.weibo.com/weibo?q=%23%E9%87%91%E4%BB%B7%E6%80%A5%E9%80%9F%E4%B8%8A%E6%B6%A8%23) `127.4K 🔥` `+27%`
1. [优思益 (Yousiyi)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `109.4K 🔥` `+78%`
1. [公安发声支持张雪机车新手禁令](https://s.weibo.com/weibo?q=%23%E5%85%AC%E5%AE%89%E5%8F%91%E5%A3%B0%E6%94%AF%E6%8C%81%E5%BC%A0%E9%9B%AA%E6%9C%BA%E8%BD%A6%E6%96%B0%E6%89%8B%E7%A6%81%E4%BB%A4%23) `97.9K 🔥` `+33%`
1. [与辉同行卖优思益销售额超千万 (Selling Yousiyi with Hui Peer, sales exceeding 10 million)](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E8%BE%89%E5%90%8C%E8%A1%8C%E5%8D%96%E4%BC%98%E6%80%9D%E7%9B%8A%E9%94%80%E5%94%AE%E9%A2%9D%E8%B6%85%E5%8D%83%E4%B8%87%23) `872.1K 🔥`
1. [严屹宽鼓励张凌赫接受质疑](https://s.weibo.com/weibo?q=%23%E4%B8%A5%E5%B1%B9%E5%AE%BD%E9%BC%93%E5%8A%B1%E5%BC%A0%E5%87%8C%E8%B5%AB%E6%8E%A5%E5%8F%97%E8%B4%A8%E7%96%91%23) `183.7K 🔥`
1. [黄子韬自曝不拍戏原因 (Huang Zitao reveals why he doesn’t film movies)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E5%AD%90%E9%9F%AC%E8%87%AA%E6%9B%9D%E4%B8%8D%E6%8B%8D%E6%88%8F%E5%8E%9F%E5%9B%A0%23) `170.9K 🔥`
1. [女子瞒重病订婚向男友索600万治病 (Woman conceals serious illness, gets engaged, asks boyfriend for 6 million for medical treatment)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%9E%92%E9%87%8D%E7%97%85%E8%AE%A2%E5%A9%9A%E5%90%91%E7%94%B7%E5%8F%8B%E7%B4%A2600%E4%B8%87%E6%B2%BB%E7%97%85%23) `152.2K 🔥`
1. [孙俪演的生理厌恶太真实了](https://s.weibo.com/weibo?q=%23%E5%AD%99%E4%BF%AA%E6%BC%94%E7%9A%84%E7%94%9F%E7%90%86%E5%8E%8C%E6%81%B6%E5%A4%AA%E7%9C%9F%E5%AE%9E%E4%BA%86%23) `129.9K 🔥`
1. [被易烊千玺骗到了 (Deceived by Yi Yang Qianxi)](https://s.weibo.com/weibo?q=%23%E8%A2%AB%E6%98%93%E7%83%8A%E5%8D%83%E7%8E%BA%E9%AA%97%E5%88%B0%E4%BA%86%23) `108.4K 🔥`
1. [陈都灵工作室连夜招人整改 (Chen Duling's studio hired people overnight for rectification)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%83%BD%E7%81%B5%E5%B7%A5%E4%BD%9C%E5%AE%A4%E8%BF%9E%E5%A4%9C%E6%8B%9B%E4%BA%BA%E6%95%B4%E6%94%B9%23) `95.4K 🔥`
1. [在美出生即公民或彻底终结](https://s.weibo.com/weibo?q=%23%E5%9C%A8%E7%BE%8E%E5%87%BA%E7%94%9F%E5%8D%B3%E5%85%AC%E6%B0%91%E6%88%96%E5%BD%BB%E5%BA%95%E7%BB%88%E7%BB%93%23) `270.9K 🔥` `-45%`
1. [以色列遭开战以来最大规模导弹袭击 (Israel suffers largest missile attack since war began)](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E9%81%AD%E5%BC%80%E6%88%98%E4%BB%A5%E6%9D%A5%E6%9C%80%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%23) `254.1K 🔥` `-54%`
1. [国乒男线对德国3连败 (National table tennis men's line lost 3 games in a row against Germany)](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%B9%92%E7%94%B7%E7%BA%BF%E5%AF%B9%E5%BE%B7%E5%9B%BD3%E8%BF%9E%E8%B4%A5%23) `206.1K 🔥` `-71%`
1. [檀健次谢却山将军造型 (Tan Jianci's appearance as General Xie Queshan)](https://s.weibo.com/weibo?q=%23%E6%AA%80%E5%81%A5%E6%AC%A1%E8%B0%A2%E5%8D%B4%E5%B1%B1%E5%B0%86%E5%86%9B%E9%80%A0%E5%9E%8B%23) `116.5K 🔥` `-50%`
1. [优思益声明 (Unisei Statement)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E5%A3%B0%E6%98%8E%23) `101.1K 🔥` `-40%`
1. [十五五我们躬身加油干 (On the 15th, let’s work hard)](https://s.weibo.com/weibo?q=%23%E5%8D%81%E4%BA%94%E4%BA%94%E6%88%91%E4%BB%AC%E8%BA%AC%E8%BA%AB%E5%8A%A0%E6%B2%B9%E5%B9%B2%23) `98.0K 🔥` `-83%`

Updated at 2026-04-02 09:02:12

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
