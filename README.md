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

1. [唐艺昕上浪姐用张若昀的助理 (Tang Yixin went to Sister Lang and used Zhang Ruoyun's assistant)](https://s.weibo.com/weibo?q=%23%E5%94%90%E8%89%BA%E6%98%95%E4%B8%8A%E6%B5%AA%E5%A7%90%E7%94%A8%E5%BC%A0%E8%8B%A5%E6%98%80%E7%9A%84%E5%8A%A9%E7%90%86%23) `564.3K 🔥` `NEW`
1. [国乒女队伦敦世乒赛名单已确定](https://s.weibo.com/weibo?q=%23%E5%9B%BD%E4%B9%92%E5%A5%B3%E9%98%9F%E4%BC%A6%E6%95%A6%E4%B8%96%E4%B9%92%E8%B5%9B%E5%90%8D%E5%8D%95%E5%B7%B2%E7%A1%AE%E5%AE%9A%23) `171.9K 🔥` `NEW`
1. [伊朗再袭巴林的亚马逊云计算中心](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%86%8D%E8%A2%AD%E5%B7%B4%E6%9E%97%E7%9A%84%E4%BA%9A%E9%A9%AC%E9%80%8A%E4%BA%91%E8%AE%A1%E7%AE%97%E4%B8%AD%E5%BF%83%23) `156.1K 🔥` `NEW`
1. [伊朗真正意义上的核武器](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%9C%9F%E6%AD%A3%E6%84%8F%E4%B9%89%E4%B8%8A%E7%9A%84%E6%A0%B8%E6%AD%A6%E5%99%A8%23) `146.9K 🔥` `NEW`
1. [张天爱发文回应变样](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%A4%A9%E7%88%B1%E5%8F%91%E6%96%87%E5%9B%9E%E5%BA%94%E5%8F%98%E6%A0%B7%23) `146.4K 🔥` `NEW`
1. [谢娜回应乘风直播节奏慢](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%A8%9C%E5%9B%9E%E5%BA%94%E4%B9%98%E9%A3%8E%E7%9B%B4%E6%92%AD%E8%8A%82%E5%A5%8F%E6%85%A2%23) `145.6K 🔥` `NEW`
1. [这种天然青霉素就在你家餐桌上](https://s.weibo.com/weibo?q=%23%E8%BF%99%E7%A7%8D%E5%A4%A9%E7%84%B6%E9%9D%92%E9%9C%89%E7%B4%A0%E5%B0%B1%E5%9C%A8%E4%BD%A0%E5%AE%B6%E9%A4%90%E6%A1%8C%E4%B8%8A%23) `144.8K 🔥` `NEW`
1. [马天宇不然别人又说我耍大牌了](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%A4%A9%E5%AE%87%E4%B8%8D%E7%84%B6%E5%88%AB%E4%BA%BA%E5%8F%88%E8%AF%B4%E6%88%91%E8%80%8D%E5%A4%A7%E7%89%8C%E4%BA%86%23) `110.2K 🔥` `NEW`
1. [第一次见买家秀和卖家秀反着来的](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%A7%81%E4%B9%B0%E5%AE%B6%E7%A7%80%E5%92%8C%E5%8D%96%E5%AE%B6%E7%A7%80%E5%8F%8D%E7%9D%80%E6%9D%A5%E7%9A%84%23) `78.4K 🔥` `NEW`
1. [美撤换陆军参谋长](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E6%92%A4%E6%8D%A2%E9%99%86%E5%86%9B%E5%8F%82%E8%B0%8B%E9%95%BF%23) `78.4K 🔥` `NEW`
1. [黄金白银全部下跌 (Gold and silver all fell)](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E7%99%BD%E9%93%B6%E5%85%A8%E9%83%A8%E4%B8%8B%E8%B7%8C%23) `70.6K 🔥` `NEW`
1. [男子出轨染病给女友同意赔50万又后悔](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%87%BA%E8%BD%A8%E6%9F%93%E7%97%85%E7%BB%99%E5%A5%B3%E5%8F%8B%E5%90%8C%E6%84%8F%E8%B5%9450%E4%B8%87%E5%8F%88%E5%90%8E%E6%82%94%23) `70.2K 🔥` `NEW`
1. [人鱼](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E9%B1%BC%23) `69.9K 🔥` `NEW`
1. [北京一老人翻窗从27楼爬到21楼](https://s.weibo.com/weibo?q=%23%E5%8C%97%E4%BA%AC%E4%B8%80%E8%80%81%E4%BA%BA%E7%BF%BB%E7%AA%97%E4%BB%8E27%E6%A5%BC%E7%88%AC%E5%88%B021%E6%A5%BC%23) `65.0K 🔥` `NEW`
1. [特朗普讲话遭到美国舆论花式吐槽](https://s.weibo.com/weibo?q=%23%E7%89%B9%E6%9C%97%E6%99%AE%E8%AE%B2%E8%AF%9D%E9%81%AD%E5%88%B0%E7%BE%8E%E5%9B%BD%E8%88%86%E8%AE%BA%E8%8A%B1%E5%BC%8F%E5%90%90%E6%A7%BD%23) `58.1K 🔥` `NEW`
1. [郑强说张雪这一跑不亚于10块奥运金牌](https://s.weibo.com/weibo?q=%23%E9%83%91%E5%BC%BA%E8%AF%B4%E5%BC%A0%E9%9B%AA%E8%BF%99%E4%B8%80%E8%B7%91%E4%B8%8D%E4%BA%9A%E4%BA%8E10%E5%9D%97%E5%A5%A5%E8%BF%90%E9%87%91%E7%89%8C%23) `57.9K 🔥` `NEW`
1. [鞠婧祎角色热度破一亿](https://s.weibo.com/weibo?q=%23%E9%9E%A0%E5%A9%A7%E7%A5%8E%E8%A7%92%E8%89%B2%E7%83%AD%E5%BA%A6%E7%A0%B4%E4%B8%80%E4%BA%BF%23) `56.3K 🔥` `NEW`
1. [小警犬刚到警局就被全体同事的围观了](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E8%AD%A6%E7%8A%AC%E5%88%9A%E5%88%B0%E8%AD%A6%E5%B1%80%E5%B0%B1%E8%A2%AB%E5%85%A8%E4%BD%93%E5%90%8C%E4%BA%8B%E7%9A%84%E5%9B%B4%E8%A7%82%E4%BA%86%23) `50.1K 🔥` `NEW`
1. [宝妈投诉蛋糕店未果反助店家爆单 (Bao's mother complained to the cake shop but failed to help the store to increase orders)](https://s.weibo.com/weibo?q=%23%E5%AE%9D%E5%A6%88%E6%8A%95%E8%AF%89%E8%9B%8B%E7%B3%95%E5%BA%97%E6%9C%AA%E6%9E%9C%E5%8F%8D%E5%8A%A9%E5%BA%97%E5%AE%B6%E7%88%86%E5%8D%95%23) `1.0M 🔥` `+36%`
1. [嘴唇发紫博主称一直以为身体正常 (Blogger with purple lips says he always thought his body was normal)](https://s.weibo.com/weibo?q=%23%E5%98%B4%E5%94%87%E5%8F%91%E7%B4%AB%E5%8D%9A%E4%B8%BB%E7%A7%B0%E4%B8%80%E7%9B%B4%E4%BB%A5%E4%B8%BA%E8%BA%AB%E4%BD%93%E6%AD%A3%E5%B8%B8%23) `715.3K 🔥` `+30%`
1. [多城实施住房公积金新政](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9F%8E%E5%AE%9E%E6%96%BD%E4%BD%8F%E6%88%BF%E5%85%AC%E7%A7%AF%E9%87%91%E6%96%B0%E6%94%BF%23) `575.4K 🔥` `+35%`
1. [伊朗标志性大桥遭袭 (Iran's iconic bridge attacked)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%A0%87%E5%BF%97%E6%80%A7%E5%A4%A7%E6%A1%A5%E9%81%AD%E8%A2%AD%23) `271.1K 🔥` `+25%`
1. [孙怡马天宇镜头被切](https://s.weibo.com/weibo?q=%23%E5%AD%99%E6%80%A1%E9%A9%AC%E5%A4%A9%E5%AE%87%E9%95%9C%E5%A4%B4%E8%A2%AB%E5%88%87%23) `257.9K 🔥` `+76%`
1. [我的妈耶又笑又哭的 (My mom laughs and cries at the same time)](https://s.weibo.com/weibo?q=%23%E6%88%91%E7%9A%84%E5%A6%88%E8%80%B6%E5%8F%88%E7%AC%91%E5%8F%88%E5%93%AD%E7%9A%84%23) `222.5K 🔥` `+54%`
1. [美国头大了 (America's head is getting bigger)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%A4%B4%E5%A4%A7%E4%BA%86%23) `222.2K 🔥` `+26%`
1. [优思益 (Yousiyi)](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%23) `78.6K 🔥` `+21%`
1. [张杰在鸟巢喊歌迷上车 (Zhang Jie called fans to get on the bus at the Bird's Nest)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9D%B0%E5%9C%A8%E9%B8%9F%E5%B7%A2%E5%96%8A%E6%AD%8C%E8%BF%B7%E4%B8%8A%E8%BD%A6%23) `64.3K 🔥` `+30%`
1. [王濛 浪姐直播太磨叽了 (Wang Meng Sister Lang’s live broadcast is too boring)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%20%E6%B5%AA%E5%A7%90%E7%9B%B4%E6%92%AD%E5%A4%AA%E7%A3%A8%E5%8F%BD%E4%BA%86%23) `187.5K 🔥`
1. [张雪称卖陈光标劳斯莱斯捐款天使嫣然 (Zhang Xue said that she sold Chen Guangbiao’s Rolls-Royce and donated money to Angel Yanran.)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E7%A7%B0%E5%8D%96%E9%99%88%E5%85%89%E6%A0%87%E5%8A%B3%E6%96%AF%E8%8E%B1%E6%96%AF%E6%8D%90%E6%AC%BE%E5%A4%A9%E4%BD%BF%E5%AB%A3%E7%84%B6%23) `173.0K 🔥`
1. [王濛 安崎没满30不能淘汰 (Wang Meng and An Qi cannot be eliminated if they are under 30)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%BF%9B%20%E5%AE%89%E5%B4%8E%E6%B2%A1%E6%BB%A130%E4%B8%8D%E8%83%BD%E6%B7%98%E6%B1%B0%23) `168.1K 🔥`
1. [伊朗称250年历史无法威胁6000年文明 (Iran says 250 years of history cannot threaten 6,000 years of civilization)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0250%E5%B9%B4%E5%8E%86%E5%8F%B2%E6%97%A0%E6%B3%95%E5%A8%81%E8%83%816000%E5%B9%B4%E6%96%87%E6%98%8E%23) `164.8K 🔥`
1. [张天爱变样了 (Zhang Tianai has changed)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%A4%A9%E7%88%B1%E5%8F%98%E6%A0%B7%E4%BA%86%23) `163.6K 🔥`
1. [优思益代言人](https://s.weibo.com/weibo?q=%23%E4%BC%98%E6%80%9D%E7%9B%8A%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `162.1K 🔥`
1. [伊朗强硬回应特朗普](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%BC%BA%E7%A1%AC%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%23) `159.6K 🔥`
1. [唐艺昕陶昕然 宝娟我的嗓子 (Tang Yixin Tao Xinran Baojuan My Throat)](https://s.weibo.com/weibo?q=%23%E5%94%90%E8%89%BA%E6%98%95%E9%99%B6%E6%98%95%E7%84%B6%20%E5%AE%9D%E5%A8%9F%E6%88%91%E7%9A%84%E5%97%93%E5%AD%90%23) `156.6K 🔥`
1. [女子离婚多年名字被刻上前婆婆墓碑 (A woman’s name is engraved on her ex-mother-in-law’s tombstone after being divorced for many years)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%A6%BB%E5%A9%9A%E5%A4%9A%E5%B9%B4%E5%90%8D%E5%AD%97%E8%A2%AB%E5%88%BB%E4%B8%8A%E5%89%8D%E5%A9%86%E5%A9%86%E5%A2%93%E7%A2%91%23) `149.7K 🔥`
1. [阚清子出场 (Kan Qingzi appears)](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E5%87%BA%E5%9C%BA%23) `143.8K 🔥`
1. [老式水果为什么消失了 (Why Old-Fashioned Fruit Disappeared)](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%BC%8F%E6%B0%B4%E6%9E%9C%E4%B8%BA%E4%BB%80%E4%B9%88%E6%B6%88%E5%A4%B1%E4%BA%86%23) `117.4K 🔥`
1. [以色列遭到开战以来最大规模导弹袭击](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E9%81%AD%E5%88%B0%E5%BC%80%E6%88%98%E4%BB%A5%E6%9D%A5%E6%9C%80%E5%A4%A7%E8%A7%84%E6%A8%A1%E5%AF%BC%E5%BC%B9%E8%A2%AD%E5%87%BB%23) `116.8K 🔥`
1. [张凌赫后面还有两部待播将军剧](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%90%8E%E9%9D%A2%E8%BF%98%E6%9C%89%E4%B8%A4%E9%83%A8%E5%BE%85%E6%92%AD%E5%B0%86%E5%86%9B%E5%89%A7%23) `93.6K 🔥`
1. [迪丽热巴 古偶 (Dilraba ancient puppet)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%20%E5%8F%A4%E5%81%B6%23) `77.6K 🔥`
1. [白鹿素颜做饭自拍 (Bai Lu takes a selfie while cooking without makeup)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E7%B4%A0%E9%A2%9C%E5%81%9A%E9%A5%AD%E8%87%AA%E6%8B%8D%23) `75.3K 🔥`
1. [女子20万买170g金条藏豆瓣酱里 (Woman buys 170g gold bars for RMB 200,000 and hides them in Doubanjiang)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%9020%E4%B8%87%E4%B9%B0170g%E9%87%91%E6%9D%A1%E8%97%8F%E8%B1%86%E7%93%A3%E9%85%B1%E9%87%8C%23) `68.6K 🔥`
1. [李现逛街偶遇粉丝](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%8E%B0%E9%80%9B%E8%A1%97%E5%81%B6%E9%81%87%E7%B2%89%E4%B8%9D%23) `66.9K 🔥`
1. [与辉同行致歉](https://s.weibo.com/weibo?q=%23%E4%B8%8E%E8%BE%89%E5%90%8C%E8%A1%8C%E8%87%B4%E6%AD%89%23) `65.4K 🔥`
1. [白日提灯待遇 (Daytime lantern treatment)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%E5%BE%85%E9%81%87%23) `56.1K 🔥`
1. [邓凯要还车贷交社保把自己说生气了 (Deng Kai said he was angry because he wanted to pay back the car loan and pay social security.)](https://s.weibo.com/weibo?q=%23%E9%82%93%E5%87%AF%E8%A6%81%E8%BF%98%E8%BD%A6%E8%B4%B7%E4%BA%A4%E7%A4%BE%E4%BF%9D%E6%8A%8A%E8%87%AA%E5%B7%B1%E8%AF%B4%E7%94%9F%E6%B0%94%E4%BA%86%23) `50.0K 🔥`
1. [迪丽热巴陈飞宇共创 (Co-created by Dilraba and Chen Feiyu)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%99%88%E9%A3%9E%E5%AE%87%E5%85%B1%E5%88%9B%23) `49.5K 🔥`
1. [孙怡说我看那玩意儿干啥啊 (Sun Yi said, what am I doing looking at that thing?)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E6%80%A1%E8%AF%B4%E6%88%91%E7%9C%8B%E9%82%A3%E7%8E%A9%E6%84%8F%E5%84%BF%E5%B9%B2%E5%95%A5%E5%95%8A%23) `169.2K 🔥` `-52%`
1. [孙颖莎2比7落后完成逆转 (Sun Yingsha completed the comeback after falling behind 2-7.)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E2%E6%AF%947%E8%90%BD%E5%90%8E%E5%AE%8C%E6%88%90%E9%80%86%E8%BD%AC%23) `68.8K 🔥` `-58%`

Updated at 2026-04-03 07:53:47

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
