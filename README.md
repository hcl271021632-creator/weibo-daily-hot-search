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

1. [致冬奥会中国体育代表团的贺电 (A congratulatory message to the Chinese sports delegation at the Winter Olympics)](https://s.weibo.com/weibo?q=%23%E8%87%B4%E5%86%AC%E5%A5%A5%E4%BC%9A%E4%B8%AD%E5%9B%BD%E4%BD%93%E8%82%B2%E4%BB%A3%E8%A1%A8%E5%9B%A2%E7%9A%84%E8%B4%BA%E7%94%B5%23) `690.0K 🔥` `NEW`
1. [刘浩存我想象中扎丸子头的样子](https://s.weibo.com/weibo?q=%23%E5%88%98%E6%B5%A9%E5%AD%98%E6%88%91%E6%83%B3%E8%B1%A1%E4%B8%AD%E6%89%8E%E4%B8%B8%E5%AD%90%E5%A4%B4%E7%9A%84%E6%A0%B7%E5%AD%90%23) `250.2K 🔥` `NEW`
1. [墨西哥毒枭向家乡果农收保护费](https://s.weibo.com/weibo?q=%23%E5%A2%A8%E8%A5%BF%E5%93%A5%E6%AF%92%E6%9E%AD%E5%90%91%E5%AE%B6%E4%B9%A1%E6%9E%9C%E5%86%9C%E6%94%B6%E4%BF%9D%E6%8A%A4%E8%B4%B9%23) `205.9K 🔥` `NEW`
1. [王者血包可以共享了](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E8%80%85%E8%A1%80%E5%8C%85%E5%8F%AF%E4%BB%A5%E5%85%B1%E4%BA%AB%E4%BA%86%23) `180.2K 🔥` `NEW`
1. [台湾河道弃尸案](https://s.weibo.com/weibo?q=%23%E5%8F%B0%E6%B9%BE%E6%B2%B3%E9%81%93%E5%BC%83%E5%B0%B8%E6%A1%88%23) `141.1K 🔥` `NEW`
1. [飞驰3换轮胎不扔的原因](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E9%A9%B03%E6%8D%A2%E8%BD%AE%E8%83%8E%E4%B8%8D%E6%89%94%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `117.3K 🔥` `NEW`
1. [孙颖莎晋级32强](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8E%E6%99%8B%E7%BA%A732%E5%BC%BA%23) `117.1K 🔥` `NEW`
1. [夜王 尺度](https://s.weibo.com/weibo?q=%23%E5%A4%9C%E7%8E%8B%20%E5%B0%BA%E5%BA%A6%23) `116.7K 🔥` `NEW`
1. [上班](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E7%8F%AD%23) `112.1K 🔥` `NEW`
1. [高速堵车大聪明选择下国道绕行](https://s.weibo.com/weibo?q=%23%E9%AB%98%E9%80%9F%E5%A0%B5%E8%BD%A6%E5%A4%A7%E8%81%AA%E6%98%8E%E9%80%89%E6%8B%A9%E4%B8%8B%E5%9B%BD%E9%81%93%E7%BB%95%E8%A1%8C%23) `99.2K 🔥` `NEW`
1. [大众点评 分析相册 (Dianping Analysis Photo Album)](https://s.weibo.com/weibo?q=%23%E5%A4%A7%E4%BC%97%E7%82%B9%E8%AF%84%20%E5%88%86%E6%9E%90%E7%9B%B8%E5%86%8C%23) `98.4K 🔥` `NEW`
1. [李琰谈宁忠岩夺金](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%90%B0%E8%B0%88%E5%AE%81%E5%BF%A0%E5%B2%A9%E5%A4%BA%E9%87%91%23) `97.5K 🔥` `NEW`
1. [老外调侃终于体验了一把春节堵车](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%A4%96%E8%B0%83%E4%BE%83%E7%BB%88%E4%BA%8E%E4%BD%93%E9%AA%8C%E4%BA%86%E4%B8%80%E6%8A%8A%E6%98%A5%E8%8A%82%E5%A0%B5%E8%BD%A6%23) `97.4K 🔥` `NEW`
1. [湖北到苏州10小时车程开2天](https://s.weibo.com/weibo?q=%23%E6%B9%96%E5%8C%97%E5%88%B0%E8%8B%8F%E5%B7%9E10%E5%B0%8F%E6%97%B6%E8%BD%A6%E7%A8%8B%E5%BC%802%E5%A4%A9%23) `96.6K 🔥` `NEW`
1. [成何体统](https://s.weibo.com/weibo?q=%23%E6%88%90%E4%BD%95%E4%BD%93%E7%BB%9F%23) `95.0K 🔥` `NEW`
1. [郭晓婷王天辰 高干文](https://s.weibo.com/weibo?q=%23%E9%83%AD%E6%99%93%E5%A9%B7%E7%8E%8B%E5%A4%A9%E8%BE%B0%20%E9%AB%98%E5%B9%B2%E6%96%87%23) `91.5K 🔥` `NEW`
1. [永远不要说关于自己的消极的话](https://s.weibo.com/weibo?q=%23%E6%B0%B8%E8%BF%9C%E4%B8%8D%E8%A6%81%E8%AF%B4%E5%85%B3%E4%BA%8E%E8%87%AA%E5%B7%B1%E7%9A%84%E6%B6%88%E6%9E%81%E7%9A%84%E8%AF%9D%23) `78.1K 🔥` `NEW`
1. [谷爱凌去年收入超2300万美元](https://s.weibo.com/weibo?q=%23%E8%B0%B7%E7%88%B1%E5%87%8C%E5%8E%BB%E5%B9%B4%E6%94%B6%E5%85%A5%E8%B6%852300%E4%B8%87%E7%BE%8E%E5%85%83%23) `869.5K 🔥` `+533%`
1. [鸟中刘亦菲也扛不了后置镜头怼脸拍](https://s.weibo.com/weibo?q=%23%E9%B8%9F%E4%B8%AD%E5%88%98%E4%BA%A6%E8%8F%B2%E4%B9%9F%E6%89%9B%E4%B8%8D%E4%BA%86%E5%90%8E%E7%BD%AE%E9%95%9C%E5%A4%B4%E6%80%BC%E8%84%B8%E6%8B%8D%23) `369.1K 🔥` `+50%`
1. [原来全麻手术不是睡着了](https://s.weibo.com/weibo?q=%23%E5%8E%9F%E6%9D%A5%E5%85%A8%E9%BA%BB%E6%89%8B%E6%9C%AF%E4%B8%8D%E6%98%AF%E7%9D%A1%E7%9D%80%E4%BA%86%23) `365.7K 🔥` `+41%`
1. [西湖里捞起财物累计价值超600万 (The cumulative value of property found in West Lake exceeds 6 million)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E6%B9%96%E9%87%8C%E6%8D%9E%E8%B5%B7%E8%B4%A2%E7%89%A9%E7%B4%AF%E8%AE%A1%E4%BB%B7%E5%80%BC%E8%B6%85600%E4%B8%87%23) `353.9K 🔥` `+115%`
1. [瘦了后出片像呼吸一样简单 (After losing weight, making movies is as easy as breathing)](https://s.weibo.com/weibo?q=%23%E7%98%A6%E4%BA%86%E5%90%8E%E5%87%BA%E7%89%87%E5%83%8F%E5%91%BC%E5%90%B8%E4%B8%80%E6%A0%B7%E7%AE%80%E5%8D%95%23) `353.8K 🔥` `+39%`
1. [单依纯 蔻驰](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BE%9D%E7%BA%AF%20%E8%94%BB%E9%A9%B0%23) `273.2K 🔥` `+48%`
1. [史上最贵iPhone要来了 (The most expensive iPhone in history is coming)](https://s.weibo.com/weibo?q=%23%E5%8F%B2%E4%B8%8A%E6%9C%80%E8%B4%B5iPhone%E8%A6%81%E6%9D%A5%E4%BA%86%23) `265.4K 🔥` `+48%`
1. [三亚偶遇章子怡一家](https://s.weibo.com/weibo?q=%23%E4%B8%89%E4%BA%9A%E5%81%B6%E9%81%87%E7%AB%A0%E5%AD%90%E6%80%A1%E4%B8%80%E5%AE%B6%23) `262.6K 🔥` `+49%`
1. [王格格开了时代峰峻的高会 (Wang Gege held a high-level meeting of the times)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A0%BC%E6%A0%BC%E5%BC%80%E4%BA%86%E6%97%B6%E4%BB%A3%E5%B3%B0%E5%B3%BB%E7%9A%84%E9%AB%98%E4%BC%9A%23) `256.2K 🔥` `+49%`
1. [孩子把摔炮当糖果入口后爆炸](https://s.weibo.com/weibo?q=%23%E5%AD%A9%E5%AD%90%E6%8A%8A%E6%91%94%E7%82%AE%E5%BD%93%E7%B3%96%E6%9E%9C%E5%85%A5%E5%8F%A3%E5%90%8E%E7%88%86%E7%82%B8%23) `253.0K 🔥` `+48%`
1. [王鹤棣说祝大家永远不死](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E9%B9%A4%E6%A3%A3%E8%AF%B4%E7%A5%9D%E5%A4%A7%E5%AE%B6%E6%B0%B8%E8%BF%9C%E4%B8%8D%E6%AD%BB%23) `244.9K 🔥` `+83%`
1. [叶舒华瘦下来美成真人bjd了](https://s.weibo.com/weibo?q=%23%E5%8F%B6%E8%88%92%E5%8D%8E%E7%98%A6%E4%B8%8B%E6%9D%A5%E7%BE%8E%E6%88%90%E7%9C%9F%E4%BA%BAbjd%E4%BA%86%23) `177.9K 🔥` `+22%`
1. [金秋天solo曲Odd](https://s.weibo.com/weibo?q=%23%E9%87%91%E7%A7%8B%E5%A4%A9solo%E6%9B%B2Odd%23) `116.9K 🔥` `+21%`
1. [不让江山剧组声明](https://s.weibo.com/weibo?q=%23%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E5%89%A7%E7%BB%84%E5%A3%B0%E6%98%8E%23) `1.2M 🔥`
1. [蒙牛致敬要强中国队米兰冬奥收官](https://s.weibo.com/weibo?q=%23%E8%92%99%E7%89%9B%E8%87%B4%E6%95%AC%E8%A6%81%E5%BC%BA%E4%B8%AD%E5%9B%BD%E9%98%9F%E7%B1%B3%E5%85%B0%E5%86%AC%E5%A5%A5%E6%94%B6%E5%AE%98%23) `636.9K 🔥`
1. [杨洋工作室回应不让江山相关争议](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E6%B4%8B%E5%B7%A5%E4%BD%9C%E5%AE%A4%E5%9B%9E%E5%BA%94%E4%B8%8D%E8%AE%A9%E6%B1%9F%E5%B1%B1%E7%9B%B8%E5%85%B3%E4%BA%89%E8%AE%AE%23) `275.2K 🔥`
1. [董宇辉自曝不整容的原因 (Dong Yuhui reveals the reason why he doesn’t have plastic surgery)](https://s.weibo.com/weibo?q=%23%E8%91%A3%E5%AE%87%E8%BE%89%E8%87%AA%E6%9B%9D%E4%B8%8D%E6%95%B4%E5%AE%B9%E7%9A%84%E5%8E%9F%E5%9B%A0%23) `175.2K 🔥`
1. [能谈到结婚的伴侣是什么样的](https://s.weibo.com/weibo?q=%23%E8%83%BD%E8%B0%88%E5%88%B0%E7%BB%93%E5%A9%9A%E7%9A%84%E4%BC%B4%E4%BE%A3%E6%98%AF%E4%BB%80%E4%B9%88%E6%A0%B7%E7%9A%84%23) `172.2K 🔥`
1. [吴佳尼自曝订婚后才知马景涛年龄 (Wu Jiani revealed that she only found out about Ma Jingtao’s age after getting engaged)](https://s.weibo.com/weibo?q=%23%E5%90%B4%E4%BD%B3%E5%B0%BC%E8%87%AA%E6%9B%9D%E8%AE%A2%E5%A9%9A%E5%90%8E%E6%89%8D%E7%9F%A5%E9%A9%AC%E6%99%AF%E6%B6%9B%E5%B9%B4%E9%BE%84%23) `167.0K 🔥`
1. [白鹿曾舜晞梁永棋陈鹤一团建合照](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E6%9B%BE%E8%88%9C%E6%99%9E%E6%A2%81%E6%B0%B8%E6%A3%8B%E9%99%88%E9%B9%A4%E4%B8%80%E5%9B%A2%E5%BB%BA%E5%90%88%E7%85%A7%23) `166.9K 🔥`
1. [西安暴雪24小时内温差20度](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%AE%89%E6%9A%B4%E9%9B%AA24%E5%B0%8F%E6%97%B6%E5%86%85%E6%B8%A9%E5%B7%AE20%E5%BA%A6%23) `140.2K 🔥`
1. [尼格买提家宴8个菜没一个青菜 (There are 8 dishes in Nigmaiti’s family banquet, not a single green vegetable)](https://s.weibo.com/weibo?q=%23%E5%B0%BC%E6%A0%BC%E4%B9%B0%E6%8F%90%E5%AE%B6%E5%AE%B48%E4%B8%AA%E8%8F%9C%E6%B2%A1%E4%B8%80%E4%B8%AA%E9%9D%92%E8%8F%9C%23) `123.3K 🔥`
1. [免费时段即将结束仍在高速怎么办](https://s.weibo.com/weibo?q=%23%E5%85%8D%E8%B4%B9%E6%97%B6%E6%AE%B5%E5%8D%B3%E5%B0%86%E7%BB%93%E6%9D%9F%E4%BB%8D%E5%9C%A8%E9%AB%98%E9%80%9F%E6%80%8E%E4%B9%88%E5%8A%9E%23) `101.4K 🔥`
1. [运动员因庆祝动作不当被取消冠军](https://s.weibo.com/weibo?q=%23%E8%BF%90%E5%8A%A8%E5%91%98%E5%9B%A0%E5%BA%86%E7%A5%9D%E5%8A%A8%E4%BD%9C%E4%B8%8D%E5%BD%93%E8%A2%AB%E5%8F%96%E6%B6%88%E5%86%A0%E5%86%9B%23) `97.4K 🔥`
1. [柳智敏solo成绩](https://s.weibo.com/weibo?q=%23%E6%9F%B3%E6%99%BA%E6%95%8Fsolo%E6%88%90%E7%BB%A9%23) `96.5K 🔥`
1. [妈妈给远嫁女儿寄了120个单间饺子](https://s.weibo.com/weibo?q=%23%E5%A6%88%E5%A6%88%E7%BB%99%E8%BF%9C%E5%AB%81%E5%A5%B3%E5%84%BF%E5%AF%84%E4%BA%86120%E4%B8%AA%E5%8D%95%E9%97%B4%E9%A5%BA%E5%AD%90%23) `82.8K 🔥`
1. [商家称36斤羊烤完剩6.9斤是正常 (The merchant said that it is normal for 36 kilograms of lamb to be left with 6.9 kilograms after roasting.)](https://s.weibo.com/weibo?q=%23%E5%95%86%E5%AE%B6%E7%A7%B036%E6%96%A4%E7%BE%8A%E7%83%A4%E5%AE%8C%E5%89%A96.9%E6%96%A4%E6%98%AF%E6%AD%A3%E5%B8%B8%23) `377.7K 🔥` `-55%`
1. [镖人票房](https://s.weibo.com/weibo?q=%23%E9%95%96%E4%BA%BA%E7%A5%A8%E6%88%BF%23) `377.3K 🔥` `-39%`
1. [夫妻春节不回家送外卖1个月赚4万 (Couple makes 40,000 yuan in one month by delivering food without going home during Spring Festival)](https://s.weibo.com/weibo?q=%23%E5%A4%AB%E5%A6%BB%E6%98%A5%E8%8A%82%E4%B8%8D%E5%9B%9E%E5%AE%B6%E9%80%81%E5%A4%96%E5%8D%961%E4%B8%AA%E6%9C%88%E8%B5%9A4%E4%B8%87%23) `178.6K 🔥` `-32%`
1. [丞磊王楚然共创回忆录](https://s.weibo.com/weibo?q=%23%E4%B8%9E%E7%A3%8A%E7%8E%8B%E6%A5%9A%E7%84%B6%E5%85%B1%E5%88%9B%E5%9B%9E%E5%BF%86%E5%BD%95%23) `98.8K 🔥` `-32%`
1. [初八上班的我就这样 (I was like this when I went to work on the eighth day of the lunar month)](https://s.weibo.com/weibo?q=%23%E5%88%9D%E5%85%AB%E4%B8%8A%E7%8F%AD%E7%9A%84%E6%88%91%E5%B0%B1%E8%BF%99%E6%A0%B7%23) `97.7K 🔥` `-32%`
1. [小狗坐十几个小时长途面相都变了 (The puppy's face changed after sitting for more than ten hours.)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8B%97%E5%9D%90%E5%8D%81%E5%87%A0%E4%B8%AA%E5%B0%8F%E6%97%B6%E9%95%BF%E9%80%94%E9%9D%A2%E7%9B%B8%E9%83%BD%E5%8F%98%E4%BA%86%23) `97.4K 🔥` `-40%`
1. [孙颖莎vs帕拉南 (Sun Yingsha vs Paranam)](https://s.weibo.com/weibo?q=%23%E5%AD%99%E9%A2%96%E8%8E%8Evs%E5%B8%95%E6%8B%89%E5%8D%97%23) `92.6K 🔥` `-50%`
1. [周洁琼为了重组大半年没休息](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%B4%81%E7%90%BC%E4%B8%BA%E4%BA%86%E9%87%8D%E7%BB%84%E5%A4%A7%E5%8D%8A%E5%B9%B4%E6%B2%A1%E4%BC%91%E6%81%AF%23) `79.2K 🔥` `-43%`

Updated at 2026-02-23 22:32:31

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
