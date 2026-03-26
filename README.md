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

1. [情侣间转账6万因多音字闹上法庭 (Couple who transferred RMB 60,000 to each other went to court over polyphonic characters)](https://s.weibo.com/weibo?q=%23%E6%83%85%E4%BE%A3%E9%97%B4%E8%BD%AC%E8%B4%A66%E4%B8%87%E5%9B%A0%E5%A4%9A%E9%9F%B3%E5%AD%97%E9%97%B9%E4%B8%8A%E6%B3%95%E5%BA%AD%23) `845.8K 🔥` `NEW`
1. [顺德文旅给8天吃胖8斤女子道歉](https://s.weibo.com/weibo?q=%23%E9%A1%BA%E5%BE%B7%E6%96%87%E6%97%85%E7%BB%998%E5%A4%A9%E5%90%83%E8%83%968%E6%96%A4%E5%A5%B3%E5%AD%90%E9%81%93%E6%AD%89%23) `213.6K 🔥` `NEW`
1. [体检正常不等于运动安全](https://s.weibo.com/weibo?q=%23%E4%BD%93%E6%A3%80%E6%AD%A3%E5%B8%B8%E4%B8%8D%E7%AD%89%E4%BA%8E%E8%BF%90%E5%8A%A8%E5%AE%89%E5%85%A8%23) `210.5K 🔥` `NEW`
1. [阚清子和老公一同现身机场](https://s.weibo.com/weibo?q=%23%E9%98%9A%E6%B8%85%E5%AD%90%E5%92%8C%E8%80%81%E5%85%AC%E4%B8%80%E5%90%8C%E7%8E%B0%E8%BA%AB%E6%9C%BA%E5%9C%BA%23) `210.3K 🔥` `NEW`
1. [心内科专家解读心源性猝死](https://s.weibo.com/weibo?q=%23%E5%BF%83%E5%86%85%E7%A7%91%E4%B8%93%E5%AE%B6%E8%A7%A3%E8%AF%BB%E5%BF%83%E6%BA%90%E6%80%A7%E7%8C%9D%E6%AD%BB%23) `210.1K 🔥` `NEW`
1. [张凌赫 张家玮](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E5%BC%A0%E5%AE%B6%E7%8E%AE%23) `210.1K 🔥` `NEW`
1. [颜如晶曾连续喝了7天特色冰浆](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%A6%82%E6%99%B6%E6%9B%BE%E8%BF%9E%E7%BB%AD%E5%96%9D%E4%BA%867%E5%A4%A9%E7%89%B9%E8%89%B2%E5%86%B0%E6%B5%86%23) `209.6K 🔥` `NEW`
1. [张雪峰早场7点开播晚场24点下播](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E6%97%A9%E5%9C%BA7%E7%82%B9%E5%BC%80%E6%92%AD%E6%99%9A%E5%9C%BA24%E7%82%B9%E4%B8%8B%E6%92%AD%23) `209.4K 🔥` `NEW`
1. [孟子义腰比名牌细](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E8%85%B0%E6%AF%94%E5%90%8D%E7%89%8C%E7%BB%86%23) `209.3K 🔥` `NEW`
1. [陈哲远关注白鹿](https://s.weibo.com/weibo?q=%23%E9%99%88%E5%93%B2%E8%BF%9C%E5%85%B3%E6%B3%A8%E7%99%BD%E9%B9%BF%23) `175.4K 🔥` `NEW`
1. [白鹿宣传你是迟来的欢喜 (Bailu publicizes that you are a belated joy)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E5%AE%A3%E4%BC%A0%E4%BD%A0%E6%98%AF%E8%BF%9F%E6%9D%A5%E7%9A%84%E6%AC%A2%E5%96%9C%23) `117.9K 🔥` `NEW`
1. [章泽天深V黑裙](https://s.weibo.com/weibo?q=%23%E7%AB%A0%E6%B3%BD%E5%A4%A9%E6%B7%B1V%E9%BB%91%E8%A3%99%23) `114.2K 🔥` `NEW`
1. [香蕉放超市与放家里的区别](https://s.weibo.com/weibo?q=%23%E9%A6%99%E8%95%89%E6%94%BE%E8%B6%85%E5%B8%82%E4%B8%8E%E6%94%BE%E5%AE%B6%E9%87%8C%E7%9A%84%E5%8C%BA%E5%88%AB%23) `113.1K 🔥` `NEW`
1. [白银黄金集体大涨](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%93%B6%E9%BB%84%E9%87%91%E9%9B%86%E4%BD%93%E5%A4%A7%E6%B6%A8%23) `111.5K 🔥` `NEW`
1. [A股](https://s.weibo.com/weibo?q=%23A%E8%82%A1%23) `111.3K 🔥` `NEW`
1. [法国女孩梦中生下三胞胎](https://s.weibo.com/weibo?q=%23%E6%B3%95%E5%9B%BD%E5%A5%B3%E5%AD%A9%E6%A2%A6%E4%B8%AD%E7%94%9F%E4%B8%8B%E4%B8%89%E8%83%9E%E8%83%8E%23) `110.5K 🔥` `NEW`
1. [内塔尼亚胡妻子为成年儿子诉苦遭批](https://s.weibo.com/weibo?q=%23%E5%86%85%E5%A1%94%E5%B0%BC%E4%BA%9A%E8%83%A1%E5%A6%BB%E5%AD%90%E4%B8%BA%E6%88%90%E5%B9%B4%E5%84%BF%E5%AD%90%E8%AF%89%E8%8B%A6%E9%81%AD%E6%89%B9%23) `110.2K 🔥` `NEW`
1. [张雪峰公司婚假最多有3星期](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%85%AC%E5%8F%B8%E5%A9%9A%E5%81%87%E6%9C%80%E5%A4%9A%E6%9C%893%E6%98%9F%E6%9C%9F%23) `104.0K 🔥` `NEW`
1. [黄晓明林志玲握手](https://s.weibo.com/weibo?q=%23%E9%BB%84%E6%99%93%E6%98%8E%E6%9E%97%E5%BF%97%E7%8E%B2%E6%8F%A1%E6%89%8B%23) `104.0K 🔥` `NEW`
1. [伊朗议长外长暂被移出清除名单](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%AE%AE%E9%95%BF%E5%A4%96%E9%95%BF%E6%9A%82%E8%A2%AB%E7%A7%BB%E5%87%BA%E6%B8%85%E9%99%A4%E5%90%8D%E5%8D%95%23) `102.8K 🔥` `NEW`
1. [EWC电竞世界杯 (EWC Esports World Cup)](https://s.weibo.com/weibo?q=%23EWC%E7%94%B5%E7%AB%9E%E4%B8%96%E7%95%8C%E6%9D%AF%23) `101.3K 🔥` `NEW`
1. [女子肢体麻木开颅抓出3厘米活虫](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%82%A2%E4%BD%93%E9%BA%BB%E6%9C%A8%E5%BC%80%E9%A2%85%E6%8A%93%E5%87%BA3%E5%8E%98%E7%B1%B3%E6%B4%BB%E8%99%AB%23) `95.4K 🔥` `NEW`
1. [逐玉](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `92.5K 🔥` `NEW`
1. [张雪峰1年直播时长达600个小时](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B01%E5%B9%B4%E7%9B%B4%E6%92%AD%E6%97%B6%E9%95%BF%E8%BE%BE600%E4%B8%AA%E5%B0%8F%E6%97%B6%23) `86.4K 🔥` `NEW`
1. [镜头霸凌](https://s.weibo.com/weibo?q=%23%E9%95%9C%E5%A4%B4%E9%9C%B8%E5%87%8C%23) `84.0K 🔥` `NEW`
1. [佘诗曼说着说着嘴里掉出一颗糖](https://s.weibo.com/weibo?q=%23%E4%BD%98%E8%AF%97%E6%9B%BC%E8%AF%B4%E7%9D%80%E8%AF%B4%E7%9D%80%E5%98%B4%E9%87%8C%E6%8E%89%E5%87%BA%E4%B8%80%E9%A2%97%E7%B3%96%23) `83.9K 🔥` `NEW`
1. [张凌赫大一的时候给人很好追的感觉](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E5%A4%A7%E4%B8%80%E7%9A%84%E6%97%B6%E5%80%99%E7%BB%99%E4%BA%BA%E5%BE%88%E5%A5%BD%E8%BF%BD%E7%9A%84%E6%84%9F%E8%A7%89%23) `80.4K 🔥` `NEW`
1. [张雪峰对于家长们的意义](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E5%AF%B9%E4%BA%8E%E5%AE%B6%E9%95%BF%E4%BB%AC%E7%9A%84%E6%84%8F%E4%B9%89%23) `79.5K 🔥` `NEW`
1. [俄乌战场惊现持枪人形机器人](https://s.weibo.com/weibo?q=%23%E4%BF%84%E4%B9%8C%E6%88%98%E5%9C%BA%E6%83%8A%E7%8E%B0%E6%8C%81%E6%9E%AA%E4%BA%BA%E5%BD%A2%E6%9C%BA%E5%99%A8%E4%BA%BA%23) `1.1M 🔥` `+349%`
1. [张凌赫伊利低温鲜奶代言人 (Zhang Linghe Yili low-temperature fresh milk spokesperson)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%BC%8A%E5%88%A9%E4%BD%8E%E6%B8%A9%E9%B2%9C%E5%A5%B6%E4%BB%A3%E8%A8%80%E4%BA%BA%23) `526.4K 🔥` `+39%`
1. [刘晓庆外甥方否认造谣](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%99%93%E5%BA%86%E5%A4%96%E7%94%A5%E6%96%B9%E5%90%A6%E8%AE%A4%E9%80%A0%E8%B0%A3%23) `209.2K 🔥` `+51%`
1. [我国成功发射四维高景二号0506星 (my country successfully launched the 4D Gaojing-2 0506 satellite)](https://s.weibo.com/weibo?q=%23%E6%88%91%E5%9B%BD%E6%88%90%E5%8A%9F%E5%8F%91%E5%B0%84%E5%9B%9B%E7%BB%B4%E9%AB%98%E6%99%AF%E4%BA%8C%E5%8F%B70506%E6%98%9F%23) `643.8K 🔥`
1. [乐华建议向王一博授出股份奖励 (Leroy recommends granting share awards to Wang Yibo)](https://s.weibo.com/weibo?q=%23%E4%B9%90%E5%8D%8E%E5%BB%BA%E8%AE%AE%E5%90%91%E7%8E%8B%E4%B8%80%E5%8D%9A%E6%8E%88%E5%87%BA%E8%82%A1%E4%BB%BD%E5%A5%96%E5%8A%B1%23) `168.4K 🔥`
1. [微信聊天为什么会出现对方正在输入](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E8%81%8A%E5%A4%A9%E4%B8%BA%E4%BB%80%E4%B9%88%E4%BC%9A%E5%87%BA%E7%8E%B0%E5%AF%B9%E6%96%B9%E6%AD%A3%E5%9C%A8%E8%BE%93%E5%85%A5%23) `166.0K 🔥`
1. [家长违停孩子开门杀撞人后逃逸](https://s.weibo.com/weibo?q=%23%E5%AE%B6%E9%95%BF%E8%BF%9D%E5%81%9C%E5%AD%A9%E5%AD%90%E5%BC%80%E9%97%A8%E6%9D%80%E6%92%9E%E4%BA%BA%E5%90%8E%E9%80%83%E9%80%B8%23) `399.3K 🔥` `-48%`
1. [原来骑手知道你在看配送进度](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E9%AA%91%E6%89%8B%E7%9F%A5%E9%81%93%E4%BD%A0%E5%9C%A8%E7%9C%8B%E9%85%8D%E9%80%81%E8%BF%9B%E5%BA%A6%23) `213.4K 🔥` `-72%`
1. [康平路线下追光plog](https://s.weibo.com/weibo?q=%23%E5%BA%B7%E5%B9%B3%E8%B7%AF%E7%BA%BF%E4%B8%8B%E8%BF%BD%E5%85%89plog%23) `213.1K 🔥` `-72%`
1. [一笑随歌爱奇艺双榜超逐玉](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%AC%91%E9%9A%8F%E6%AD%8C%E7%88%B1%E5%A5%87%E8%89%BA%E5%8F%8C%E6%A6%9C%E8%B6%85%E9%80%90%E7%8E%89%23) `213.0K 🔥` `-72%`
1. [小哥爬7楼送外卖看到牌匾瞬间愣住](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%93%A5%E7%88%AC7%E6%A5%BC%E9%80%81%E5%A4%96%E5%8D%96%E7%9C%8B%E5%88%B0%E7%89%8C%E5%8C%BE%E7%9E%AC%E9%97%B4%E6%84%A3%E4%BD%8F%23) `210.7K 🔥` `-81%`
1. [睡眠不足当心运动变成无效消耗](https://s.weibo.com/weibo?q=%23%E7%9D%A1%E7%9C%A0%E4%B8%8D%E8%B6%B3%E5%BD%93%E5%BF%83%E8%BF%90%E5%8A%A8%E5%8F%98%E6%88%90%E6%97%A0%E6%95%88%E6%B6%88%E8%80%97%23) `210.6K 🔥` `-72%`
1. [林志玲51岁体态](https://s.weibo.com/weibo?q=%23%E6%9E%97%E5%BF%97%E7%8E%B251%E5%B2%81%E4%BD%93%E6%80%81%23) `209.9K 🔥` `-72%`
1. [能做夫妻是有点玄学在身上的](https://s.weibo.com/weibo?q=%23%E8%83%BD%E5%81%9A%E5%A4%AB%E5%A6%BB%E6%98%AF%E6%9C%89%E7%82%B9%E7%8E%84%E5%AD%A6%E5%9C%A8%E8%BA%AB%E4%B8%8A%E7%9A%84%23) `209.6K 🔥` `-72%`
1. [张雪峰追悼会将于周六举行 (Zhang Xuefeng's memorial service will be held on Saturday)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E8%BF%BD%E6%82%BC%E4%BC%9A%E5%B0%86%E4%BA%8E%E5%91%A8%E5%85%AD%E4%B8%BE%E8%A1%8C%23) `200.0K 🔥` `-28%`
1. [每天3分钟平板撑一个月后的效果](https://s.weibo.com/weibo?q=%23%E6%AF%8F%E5%A4%A93%E5%88%86%E9%92%9F%E5%B9%B3%E6%9D%BF%E6%92%91%E4%B8%80%E4%B8%AA%E6%9C%88%E5%90%8E%E7%9A%84%E6%95%88%E6%9E%9C%23) `122.8K 🔥` `-39%`
1. [女子被骗50万元民警追回100万元](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%A2%AB%E9%AA%9750%E4%B8%87%E5%85%83%E6%B0%91%E8%AD%A6%E8%BF%BD%E5%9B%9E100%E4%B8%87%E5%85%83%23) `118.9K 🔥` `-33%`
1. [强闯我驻日使馆不法之徒长相公开 (The faces of the criminals who forced their way into our embassy in Japan are revealed)](https://s.weibo.com/weibo?q=%23%E5%BC%BA%E9%97%AF%E6%88%91%E9%A9%BB%E6%97%A5%E4%BD%BF%E9%A6%86%E4%B8%8D%E6%B3%95%E4%B9%8B%E5%BE%92%E9%95%BF%E7%9B%B8%E5%85%AC%E5%BC%80%23) `108.4K 🔥` `-87%`
1. [张雪峰丧事不设追思会](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E9%9B%AA%E5%B3%B0%E4%B8%A7%E4%BA%8B%E4%B8%8D%E8%AE%BE%E8%BF%BD%E6%80%9D%E4%BC%9A%23) `107.7K 🔥` `-48%`
1. [晋江副总裁称开发票是魔法攻击](https://s.weibo.com/weibo?q=%23%E6%99%8B%E6%B1%9F%E5%89%AF%E6%80%BB%E8%A3%81%E7%A7%B0%E5%BC%80%E5%8F%91%E7%A5%A8%E6%98%AF%E9%AD%94%E6%B3%95%E6%94%BB%E5%87%BB%23) `104.8K 🔥` `-64%`
1. [王俊凯新歌上线](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E6%96%B0%E6%AD%8C%E4%B8%8A%E7%BA%BF%23) `99.9K 🔥` `-33%`
1. [继母见女孩学习就虐待殴打撕书](https://s.weibo.com/weibo?q=%23%E7%BB%A7%E6%AF%8D%E8%A7%81%E5%A5%B3%E5%AD%A9%E5%AD%A6%E4%B9%A0%E5%B0%B1%E8%99%90%E5%BE%85%E6%AE%B4%E6%89%93%E6%92%95%E4%B9%A6%23) `96.0K 🔥` `-53%`
1. [月鳞绮纪](https://s.weibo.com/weibo?q=%23%E6%9C%88%E9%B3%9E%E7%BB%AE%E7%BA%AA%23) `92.4K 🔥` `-24%`
1. [日本自卫队将登陆菲律宾](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E8%87%AA%E5%8D%AB%E9%98%9F%E5%B0%86%E7%99%BB%E9%99%86%E8%8F%B2%E5%BE%8B%E5%AE%BE%23) `88.0K 🔥` `-26%`

Updated at 2026-03-26 14:45:13

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
