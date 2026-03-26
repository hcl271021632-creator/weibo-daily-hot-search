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

1. [8岁被领养至加拿大又遭遗弃 (Adopted to Canada at the age of 8 and then abandoned)](https://s.weibo.com/weibo?q=%238%E5%B2%81%E8%A2%AB%E9%A2%86%E5%85%BB%E8%87%B3%E5%8A%A0%E6%8B%BF%E5%A4%A7%E5%8F%88%E9%81%AD%E9%81%97%E5%BC%83%23) `331.0K 🔥` `NEW`
1. [女子因停车争吵身亡家属索赔122万](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%9B%A0%E5%81%9C%E8%BD%A6%E4%BA%89%E5%90%B5%E8%BA%AB%E4%BA%A1%E5%AE%B6%E5%B1%9E%E7%B4%A2%E8%B5%94122%E4%B8%87%23) `212.0K 🔥` `NEW`
1. [Crisp怒喷Kanavi](https://s.weibo.com/weibo?q=%23Crisp%E6%80%92%E5%96%B7Kanavi%23) `195.7K 🔥` `NEW`
1. [没认出来这是王子异](https://s.weibo.com/weibo?q=%23%E6%B2%A1%E8%AE%A4%E5%87%BA%E6%9D%A5%E8%BF%99%E6%98%AF%E7%8E%8B%E5%AD%90%E5%BC%82%23) `194.0K 🔥` `NEW`
1. [逐玉谢征吸长玉锁骨](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E8%B0%A2%E5%BE%81%E5%90%B8%E9%95%BF%E7%8E%89%E9%94%81%E9%AA%A8%23) `189.9K 🔥` `NEW`
1. [医生谈硝酸甘油能否救心源性猝死](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E7%94%9F%E8%B0%88%E7%A1%9D%E9%85%B8%E7%94%98%E6%B2%B9%E8%83%BD%E5%90%A6%E6%95%91%E5%BF%83%E6%BA%90%E6%80%A7%E7%8C%9D%E6%AD%BB%23) `187.3K 🔥` `NEW`
1. [伊朗正式回应美国15点停火协议](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%AD%A3%E5%BC%8F%E5%9B%9E%E5%BA%94%E7%BE%8E%E5%9B%BD15%E7%82%B9%E5%81%9C%E7%81%AB%E5%8D%8F%E8%AE%AE%23) `187.1K 🔥` `NEW`
1. [杨笠的脑子转得太快了](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%AC%A0%E7%9A%84%E8%84%91%E5%AD%90%E8%BD%AC%E5%BE%97%E5%A4%AA%E5%BF%AB%E4%BA%86%23) `126.9K 🔥` `NEW`
1. [全国猪价已跌破5元](https://s.weibo.com/weibo?q=%23%E5%85%A8%E5%9B%BD%E7%8C%AA%E4%BB%B7%E5%B7%B2%E8%B7%8C%E7%A0%B45%E5%85%83%23) `124.3K 🔥` `NEW`
1. [日本6.4级地震](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC6.4%E7%BA%A7%E5%9C%B0%E9%9C%87%23) `85.7K 🔥` `NEW`
1. [小孩哥淘到疑似日军细菌战账单 (Brother Kid found a suspected Japanese military germ warfare bill)](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E5%AD%A9%E5%93%A5%E6%B7%98%E5%88%B0%E7%96%91%E4%BC%BC%E6%97%A5%E5%86%9B%E7%BB%86%E8%8F%8C%E6%88%98%E8%B4%A6%E5%8D%95%23) `85.2K 🔥` `NEW`
1. [现货黄金](https://s.weibo.com/weibo?q=%23%E7%8E%B0%E8%B4%A7%E9%BB%84%E9%87%91%23) `82.4K 🔥` `NEW`
1. [颜如晶曾找过25个教练减重均失败](https://s.weibo.com/weibo?q=%23%E9%A2%9C%E5%A6%82%E6%99%B6%E6%9B%BE%E6%89%BE%E8%BF%8725%E4%B8%AA%E6%95%99%E7%BB%83%E5%87%8F%E9%87%8D%E5%9D%87%E5%A4%B1%E8%B4%A5%23) `64.5K 🔥` `NEW`
1. [这样的脱发留意心血管问题](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%A0%B7%E7%9A%84%E8%84%B1%E5%8F%91%E7%95%99%E6%84%8F%E5%BF%83%E8%A1%80%E7%AE%A1%E9%97%AE%E9%A2%98%23) `64.4K 🔥` `NEW`
1. [熬夜到哪种程度可能会猝死](https://s.weibo.com/weibo?q=%23%E7%86%AC%E5%A4%9C%E5%88%B0%E5%93%AA%E7%A7%8D%E7%A8%8B%E5%BA%A6%E5%8F%AF%E8%83%BD%E4%BC%9A%E7%8C%9D%E6%AD%BB%23) `62.1K 🔥` `NEW`
1. [伊朗击落美军F18战机画面](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%87%BB%E8%90%BD%E7%BE%8E%E5%86%9BF18%E6%88%98%E6%9C%BA%E7%94%BB%E9%9D%A2%23) `54.7K 🔥` `NEW`
1. [意大利2比0北爱尔兰](https://s.weibo.com/weibo?q=%23%E6%84%8F%E5%A4%A7%E5%88%A92%E6%AF%940%E5%8C%97%E7%88%B1%E5%B0%94%E5%85%B0%23) `52.4K 🔥` `NEW`
1. [中芯国际发布2025年业绩](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E8%8A%AF%E5%9B%BD%E9%99%85%E5%8F%91%E5%B8%832025%E5%B9%B4%E4%B8%9A%E7%BB%A9%23) `52.0K 🔥` `NEW`
1. [KPL春季赛](https://s.weibo.com/weibo?q=%23KPL%E6%98%A5%E5%AD%A3%E8%B5%9B%23) `51.3K 🔥` `NEW`
1. [黄金下破4450美元](https://s.weibo.com/weibo?q=%23%E9%BB%84%E9%87%91%E4%B8%8B%E7%A0%B44450%E7%BE%8E%E5%85%83%23) `48.7K 🔥` `NEW`
1. [游客因拍照设备太专业被景区驱赶 (Tourists were driven away from scenic spots because their photography equipment was too professional)](https://s.weibo.com/weibo?q=%23%E6%B8%B8%E5%AE%A2%E5%9B%A0%E6%8B%8D%E7%85%A7%E8%AE%BE%E5%A4%87%E5%A4%AA%E4%B8%93%E4%B8%9A%E8%A2%AB%E6%99%AF%E5%8C%BA%E9%A9%B1%E8%B5%B6%23) `982.7K 🔥` `+52%`
1. [这样的民族败类必将被钉在历史耻辱柱上 (Such national scum will surely be nailed to the pillar of historical shame.)](https://s.weibo.com/weibo?q=%23%E8%BF%99%E6%A0%B7%E7%9A%84%E6%B0%91%E6%97%8F%E8%B4%A5%E7%B1%BB%E5%BF%85%E5%B0%86%E8%A2%AB%E9%92%89%E5%9C%A8%E5%8E%86%E5%8F%B2%E8%80%BB%E8%BE%B1%E6%9F%B1%E4%B8%8A%23) `689.0K 🔥` `+52%`
1. [2026中国网络媒体论坛 (2026 China Online Media Forum)](https://s.weibo.com/weibo?q=%232026%E4%B8%AD%E5%9B%BD%E7%BD%91%E7%BB%9C%E5%AA%92%E4%BD%93%E8%AE%BA%E5%9D%9B%23) `575.0K 🔥` `+48%`
1. [央视新闻夸了张凌赫雉鸡翎造型 (CCTV News praised Zhang Linghe’s pheasant feather appearance)](https://s.weibo.com/weibo?q=%23%E5%A4%AE%E8%A7%86%E6%96%B0%E9%97%BB%E5%A4%B8%E4%BA%86%E5%BC%A0%E5%87%8C%E8%B5%AB%E9%9B%89%E9%B8%A1%E7%BF%8E%E9%80%A0%E5%9E%8B%23) `284.0K 🔥` `+95%`
1. [专家辟谣怀儿子孕妈皮肤会变差 (Experts refute rumors that pregnant mothers’ skin will get worse during pregnancy)](https://s.weibo.com/weibo?q=%23%E4%B8%93%E5%AE%B6%E8%BE%9F%E8%B0%A3%E6%80%80%E5%84%BF%E5%AD%90%E5%AD%95%E5%A6%88%E7%9A%AE%E8%82%A4%E4%BC%9A%E5%8F%98%E5%B7%AE%23) `267.0K 🔥` `+773%`
1. [38岁教培创始人突发心梗后怕不已 (The 38-year-old education and training founder was frightened after suffering a heart attack)](https://s.weibo.com/weibo?q=%2338%E5%B2%81%E6%95%99%E5%9F%B9%E5%88%9B%E5%A7%8B%E4%BA%BA%E7%AA%81%E5%8F%91%E5%BF%83%E6%A2%97%E5%90%8E%E6%80%95%E4%B8%8D%E5%B7%B2%23) `213.2K 🔥` `+72%`
1. [伊朗导弹2小时内4次密集砸向以本土 (Iranian missiles hit the Israeli mainland 4 times in 2 hours)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%AF%BC%E5%BC%B92%E5%B0%8F%E6%97%B6%E5%86%854%E6%AC%A1%E5%AF%86%E9%9B%86%E7%A0%B8%E5%90%91%E4%BB%A5%E6%9C%AC%E5%9C%9F%23) `196.9K 🔥` `+35%`
1. [罗技回应发布侮辱性广告 (Logitech responds to release of insulting ad)](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%8A%80%E5%9B%9E%E5%BA%94%E5%8F%91%E5%B8%83%E4%BE%AE%E8%BE%B1%E6%80%A7%E5%B9%BF%E5%91%8A%23) `191.8K 🔥` `+62%`
1. [罗技侮辱消费者 (Logitech insults consumers)](https://s.weibo.com/weibo?q=%23%E7%BD%97%E6%8A%80%E4%BE%AE%E8%BE%B1%E6%B6%88%E8%B4%B9%E8%80%85%23) `146.1K 🔥` `+50%`
1. [林俊杰称自己生命的沙漏加速了 (JJ Lin said the hourglass of his life has accelerated)](https://s.weibo.com/weibo?q=%23%E6%9E%97%E4%BF%8A%E6%9D%B0%E7%A7%B0%E8%87%AA%E5%B7%B1%E7%94%9F%E5%91%BD%E7%9A%84%E6%B2%99%E6%BC%8F%E5%8A%A0%E9%80%9F%E4%BA%86%23) `134.7K 🔥` `+75%`
1. [谢征樊长玉被窝戏删掉了](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E8%A2%AB%E7%AA%9D%E6%88%8F%E5%88%A0%E6%8E%89%E4%BA%86%23) `133.4K 🔥` `+78%`
1. [医院回应女婴刚出生一天没有肛门 (The hospital responded that the baby girl had no anus just one day after birth)](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E9%99%A2%E5%9B%9E%E5%BA%94%E5%A5%B3%E5%A9%B4%E5%88%9A%E5%87%BA%E7%94%9F%E4%B8%80%E5%A4%A9%E6%B2%A1%E6%9C%89%E8%82%9B%E9%97%A8%23) `133.1K 🔥` `+81%`
1. [孟子义李昀锐装不熟](https://s.weibo.com/weibo?q=%23%E5%AD%9F%E5%AD%90%E4%B9%89%E6%9D%8E%E6%98%80%E9%94%90%E8%A3%85%E4%B8%8D%E7%86%9F%23) `116.8K 🔥` `+61%`
1. [姐姐在弟弟平板微信疯狂发力 (My sister goes crazy on her brother’s tablet WeChat)](https://s.weibo.com/weibo?q=%23%E5%A7%90%E5%A7%90%E5%9C%A8%E5%BC%9F%E5%BC%9F%E5%B9%B3%E6%9D%BF%E5%BE%AE%E4%BF%A1%E7%96%AF%E7%8B%82%E5%8F%91%E5%8A%9B%23) `96.7K 🔥` `+34%`
1. [田曦薇张凌赫 二搭 (Tian Xiwei Zhang Linghe second partner)](https://s.weibo.com/weibo?q=%23%E7%94%B0%E6%9B%A6%E8%96%87%E5%BC%A0%E5%87%8C%E8%B5%AB%20%E4%BA%8C%E6%90%AD%23) `96.7K 🔥` `+32%`
1. [马杜罗夫妇关押地如同人间炼狱 (The place where Maduro and his wife are being held is like hell on earth)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E6%9D%9C%E7%BD%97%E5%A4%AB%E5%A6%87%E5%85%B3%E6%8A%BC%E5%9C%B0%E5%A6%82%E5%90%8C%E4%BA%BA%E9%97%B4%E7%82%BC%E7%8B%B1%23) `409.6K 🔥`
1. [隐身的名字 (invisible name)](https://s.weibo.com/weibo?q=%23%E9%9A%90%E8%BA%AB%E7%9A%84%E5%90%8D%E5%AD%97%23) `172.7K 🔥`
1. [韩国垃圾袋一袋难求](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E5%9B%BD%E5%9E%83%E5%9C%BE%E8%A2%8B%E4%B8%80%E8%A2%8B%E9%9A%BE%E6%B1%82%23) `140.0K 🔥`
1. [你其实从未触摸过任何东西](https://s.weibo.com/weibo?q=%23%E4%BD%A0%E5%85%B6%E5%AE%9E%E4%BB%8E%E6%9C%AA%E8%A7%A6%E6%91%B8%E8%BF%87%E4%BB%BB%E4%BD%95%E4%B8%9C%E8%A5%BF%23) `134.8K 🔥`
1. [陈飞宇迪丽热巴两集短剧 (Chen Feiyu and Dilireba two-episode short drama)](https://s.weibo.com/weibo?q=%23%E9%99%88%E9%A3%9E%E5%AE%87%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E4%B8%A4%E9%9B%86%E7%9F%AD%E5%89%A7%23) `127.7K 🔥`
1. [千金不换 撤档](https://s.weibo.com/weibo?q=%23%E5%8D%83%E9%87%91%E4%B8%8D%E6%8D%A2%20%E6%92%A4%E6%A1%A3%23) `96.5K 🔥`
1. [留几手发文暗讽被全网炮轰 (I posted a satirical post and was bombarded by the entire Internet.)](https://s.weibo.com/weibo?q=%23%E7%95%99%E5%87%A0%E6%89%8B%E5%8F%91%E6%96%87%E6%9A%97%E8%AE%BD%E8%A2%AB%E5%85%A8%E7%BD%91%E7%82%AE%E8%BD%B0%23) `83.5K 🔥`
1. [LPL进入大回归时代](https://s.weibo.com/weibo?q=%23LPL%E8%BF%9B%E5%85%A5%E5%A4%A7%E5%9B%9E%E5%BD%92%E6%97%B6%E4%BB%A3%23) `74.9K 🔥`
1. [美方被曝正酝酿对伊朗最后一击 (The US is revealed to be preparing a final blow against Iran)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E6%96%B9%E8%A2%AB%E6%9B%9D%E6%AD%A3%E9%85%9D%E9%85%BF%E5%AF%B9%E4%BC%8A%E6%9C%97%E6%9C%80%E5%90%8E%E4%B8%80%E5%87%BB%23) `71.2K 🔥`
1. [白敬亭郑合惠子互动](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%95%AC%E4%BA%AD%E9%83%91%E5%90%88%E6%83%A0%E5%AD%90%E4%BA%92%E5%8A%A8%23) `70.2K 🔥`
1. [43岁不健身和61岁健身的区别 (The difference between not exercising at the age of 43 and exercising at the age of 61)](https://s.weibo.com/weibo?q=%2343%E5%B2%81%E4%B8%8D%E5%81%A5%E8%BA%AB%E5%92%8C61%E5%B2%81%E5%81%A5%E8%BA%AB%E7%9A%84%E5%8C%BA%E5%88%AB%23) `68.4K 🔥`
1. [逐玉 he](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%20he%23) `58.8K 🔥`
1. [樊振东若不参赛机会或给温瑞博](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E6%8C%AF%E4%B8%9C%E8%8B%A5%E4%B8%8D%E5%8F%82%E8%B5%9B%E6%9C%BA%E4%BC%9A%E6%88%96%E7%BB%99%E6%B8%A9%E7%91%9E%E5%8D%9A%23) `80.0K 🔥` `-33%`
1. [伊朗议长称地区某国支持敌人夺岛 (Iran's Speaker Says A Country in the Region Supports Enemies to Seize Islands)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E8%AE%AE%E9%95%BF%E7%A7%B0%E5%9C%B0%E5%8C%BA%E6%9F%90%E5%9B%BD%E6%94%AF%E6%8C%81%E6%95%8C%E4%BA%BA%E5%A4%BA%E5%B2%9B%23) `60.5K 🔥` `-27%`
1. [货拉拉司机运10箱茅台失联后续 (Follow-up after Lalamove driver disappeared while transporting 10 boxes of Moutai)](https://s.weibo.com/weibo?q=%23%E8%B4%A7%E6%8B%89%E6%8B%89%E5%8F%B8%E6%9C%BA%E8%BF%9010%E7%AE%B1%E8%8C%85%E5%8F%B0%E5%A4%B1%E8%81%94%E5%90%8E%E7%BB%AD%23) `56.1K 🔥` `-22%`
1. [一笑随歌 (Smile and sing)](https://s.weibo.com/weibo?q=%23%E4%B8%80%E7%AC%91%E9%9A%8F%E6%AD%8C%23) `50.1K 🔥` `-31%`

Updated at 2026-03-27 07:44:14

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
