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

1. [上海迪士尼70元1个包子网友怒了 (Netizens are angry at Shanghai Disney’s 70 yuan buns)](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E6%B5%B7%E8%BF%AA%E5%A3%AB%E5%B0%BC70%E5%85%831%E4%B8%AA%E5%8C%85%E5%AD%90%E7%BD%91%E5%8F%8B%E6%80%92%E4%BA%86%23) `1.1M 🔥` `NEW`
1. [开始推理吧直播](https://s.weibo.com/weibo?q=%23%E5%BC%80%E5%A7%8B%E6%8E%A8%E7%90%86%E5%90%A7%E7%9B%B4%E6%92%AD%23) `827.0K 🔥` `NEW`
1. [稳定发展是中国人民的坚实底气](https://s.weibo.com/weibo?q=%23%E7%A8%B3%E5%AE%9A%E5%8F%91%E5%B1%95%E6%98%AF%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B0%91%E7%9A%84%E5%9D%9A%E5%AE%9E%E5%BA%95%E6%B0%94%23) `666.1K 🔥` `NEW`
1. [美国得州炼油厂发生爆炸](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E5%BE%97%E5%B7%9E%E7%82%BC%E6%B2%B9%E5%8E%82%E5%8F%91%E7%94%9F%E7%88%86%E7%82%B8%23) `368.6K 🔥` `NEW`
1. [浅浅为俞宝儿改名齐煜](https://s.weibo.com/weibo?q=%23%E6%B5%85%E6%B5%85%E4%B8%BA%E4%BF%9E%E5%AE%9D%E5%84%BF%E6%94%B9%E5%90%8D%E9%BD%90%E7%85%9C%23) `310.4K 🔥` `NEW`
1. [张楚寒邓凯吻戏](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%A5%9A%E5%AF%92%E9%82%93%E5%87%AF%E5%90%BB%E6%88%8F%23) `268.8K 🔥` `NEW`
1. [iPhone史上最大规模产品革新来了](https://s.weibo.com/weibo?q=%23iPhone%E5%8F%B2%E4%B8%8A%E6%9C%80%E5%A4%A7%E8%A7%84%E6%A8%A1%E4%BA%A7%E5%93%81%E9%9D%A9%E6%96%B0%E6%9D%A5%E4%BA%86%23) `183.6K 🔥` `NEW`
1. [刘亦菲安妮海瑟薇互相搂腰](https://s.weibo.com/weibo?q=%23%E5%88%98%E4%BA%A6%E8%8F%B2%E5%AE%89%E5%A6%AE%E6%B5%B7%E7%91%9F%E8%96%87%E4%BA%92%E7%9B%B8%E6%90%82%E8%85%B0%23) `180.2K 🔥` `NEW`
1. [热巴给开推团准备了新疆特产](https://s.weibo.com/weibo?q=%23%E7%83%AD%E5%B7%B4%E7%BB%99%E5%BC%80%E6%8E%A8%E5%9B%A2%E5%87%86%E5%A4%87%E4%BA%86%E6%96%B0%E7%96%86%E7%89%B9%E4%BA%A7%23) `178.6K 🔥` `NEW`
1. [刘宇宁都不知道丁程鑫要来开推](https://s.weibo.com/weibo?q=%23%E5%88%98%E5%AE%87%E5%AE%81%E9%83%BD%E4%B8%8D%E7%9F%A5%E9%81%93%E4%B8%81%E7%A8%8B%E9%91%AB%E8%A6%81%E6%9D%A5%E5%BC%80%E6%8E%A8%23) `177.1K 🔥` `NEW`
1. [有人趁金价大跌买了2公斤黄金 (Someone took advantage of the sharp drop in gold prices and bought 2 kilograms of gold)](https://s.weibo.com/weibo?q=%23%E6%9C%89%E4%BA%BA%E8%B6%81%E9%87%91%E4%BB%B7%E5%A4%A7%E8%B7%8C%E4%B9%B0%E4%BA%862%E5%85%AC%E6%96%A4%E9%BB%84%E9%87%91%23) `154.5K 🔥` `NEW`
1. [生命树集均1381万](https://s.weibo.com/weibo?q=%23%E7%94%9F%E5%91%BD%E6%A0%91%E9%9B%86%E5%9D%871381%E4%B8%87%23) `148.6K 🔥` `NEW`
1. [开推4女生只剩金靖了](https://s.weibo.com/weibo?q=%23%E5%BC%80%E6%8E%A84%E5%A5%B3%E7%94%9F%E5%8F%AA%E5%89%A9%E9%87%91%E9%9D%96%E4%BA%86%23) `148.5K 🔥` `NEW`
1. [第一批金价下跌受害者发声](https://s.weibo.com/weibo?q=%23%E7%AC%AC%E4%B8%80%E6%89%B9%E9%87%91%E4%BB%B7%E4%B8%8B%E8%B7%8C%E5%8F%97%E5%AE%B3%E8%80%85%E5%8F%91%E5%A3%B0%23) `148.2K 🔥` `NEW`
1. [金银继续下跌](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%93%B6%E7%BB%A7%E7%BB%AD%E4%B8%8B%E8%B7%8C%23) `147.8K 🔥` `NEW`
1. [王俊凯要唱新歌无人乐园](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%BF%8A%E5%87%AF%E8%A6%81%E5%94%B1%E6%96%B0%E6%AD%8C%E6%97%A0%E4%BA%BA%E4%B9%90%E5%9B%AD%23) `147.6K 🔥` `NEW`
1. [中东已经够乱了](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E4%B8%9C%E5%B7%B2%E7%BB%8F%E5%A4%9F%E4%B9%B1%E4%BA%86%23) `133.5K 🔥` `NEW`
1. [白日提灯](https://s.weibo.com/weibo?q=%23%E7%99%BD%E6%97%A5%E6%8F%90%E7%81%AF%23) `132.0K 🔥` `NEW`
1. [官方通报秦岭乱扔垃圾起冲突事件](https://s.weibo.com/weibo?q=%23%E5%AE%98%E6%96%B9%E9%80%9A%E6%8A%A5%E7%A7%A6%E5%B2%AD%E4%B9%B1%E6%89%94%E5%9E%83%E5%9C%BE%E8%B5%B7%E5%86%B2%E7%AA%81%E4%BA%8B%E4%BB%B6%23) `128.1K 🔥` `NEW`
1. [境外间谍能使用激光设备隔空窃听](https://s.weibo.com/weibo?q=%23%E5%A2%83%E5%A4%96%E9%97%B4%E8%B0%8D%E8%83%BD%E4%BD%BF%E7%94%A8%E6%BF%80%E5%85%89%E8%AE%BE%E5%A4%87%E9%9A%94%E7%A9%BA%E7%AA%83%E5%90%AC%23) `128.0K 🔥` `NEW`
1. [A股集体高开 (A shares collectively opened higher)](https://s.weibo.com/weibo?q=%23A%E8%82%A1%E9%9B%86%E4%BD%93%E9%AB%98%E5%BC%80%23) `128.0K 🔥` `NEW`
1. [金靖包场迪丽热巴白宇新剧](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%9D%96%E5%8C%85%E5%9C%BA%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E7%99%BD%E5%AE%87%E6%96%B0%E5%89%A7%23) `124.3K 🔥` `NEW`
1. [赖清德宣布将重启核电厂](https://s.weibo.com/weibo?q=%23%E8%B5%96%E6%B8%85%E5%BE%B7%E5%AE%A3%E5%B8%83%E5%B0%86%E9%87%8D%E5%90%AF%E6%A0%B8%E7%94%B5%E5%8E%82%23) `123.9K 🔥` `NEW`
1. [金正恩称朝鲜将继续巩固拥核国家地位](https://s.weibo.com/weibo?q=%23%E9%87%91%E6%AD%A3%E6%81%A9%E7%A7%B0%E6%9C%9D%E9%B2%9C%E5%B0%86%E7%BB%A7%E7%BB%AD%E5%B7%A9%E5%9B%BA%E6%8B%A5%E6%A0%B8%E5%9B%BD%E5%AE%B6%E5%9C%B0%E4%BD%8D%23) `119.2K 🔥` `NEW`
1. [缓解上班焦虑情绪的方法](https://s.weibo.com/weibo?q=%23%E7%BC%93%E8%A7%A3%E4%B8%8A%E7%8F%AD%E7%84%A6%E8%99%91%E6%83%85%E7%BB%AA%E7%9A%84%E6%96%B9%E6%B3%95%23) `98.4K 🔥` `NEW`
1. [无法共情小时候的自己](https://s.weibo.com/weibo?q=%23%E6%97%A0%E6%B3%95%E5%85%B1%E6%83%85%E5%B0%8F%E6%97%B6%E5%80%99%E7%9A%84%E8%87%AA%E5%B7%B1%23) `96.3K 🔥` `NEW`
1. [QQ音乐超级巅峰之夜曲目](https://s.weibo.com/weibo?q=%23QQ%E9%9F%B3%E4%B9%90%E8%B6%85%E7%BA%A7%E5%B7%85%E5%B3%B0%E4%B9%8B%E5%A4%9C%E6%9B%B2%E7%9B%AE%23) `95.5K 🔥` `NEW`
1. [谢征樊长玉圆房吻来了](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E6%A8%8A%E9%95%BF%E7%8E%89%E5%9C%86%E6%88%BF%E5%90%BB%E6%9D%A5%E4%BA%86%23) `94.6K 🔥` `NEW`
1. [金店店员称金价降幅有限](https://s.weibo.com/weibo?q=%23%E9%87%91%E5%BA%97%E5%BA%97%E5%91%98%E7%A7%B0%E9%87%91%E4%BB%B7%E9%99%8D%E5%B9%85%E6%9C%89%E9%99%90%23) `91.7K 🔥` `NEW`
1. [睡不好是身体在给你发信号](https://s.weibo.com/weibo?q=%23%E7%9D%A1%E4%B8%8D%E5%A5%BD%E6%98%AF%E8%BA%AB%E4%BD%93%E5%9C%A8%E7%BB%99%E4%BD%A0%E5%8F%91%E4%BF%A1%E5%8F%B7%23) `87.8K 🔥` `NEW`
1. [姿态谈Bin信誉分 (Posture talks about Bin’s reputation points)](https://s.weibo.com/weibo?q=%23%E5%A7%BF%E6%80%81%E8%B0%88Bin%E4%BF%A1%E8%AA%89%E5%88%86%23) `82.0K 🔥` `NEW`
1. [日本考虑派兵去霍尔木兹海峡扫雷](https://s.weibo.com/weibo?q=%23%E6%97%A5%E6%9C%AC%E8%80%83%E8%99%91%E6%B4%BE%E5%85%B5%E5%8E%BB%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%E6%89%AB%E9%9B%B7%23) `81.4K 🔥` `NEW`
1. [虞书欣名誉权案被告登报致歉](https://s.weibo.com/weibo?q=%23%E8%99%9E%E4%B9%A6%E6%AC%A3%E5%90%8D%E8%AA%89%E6%9D%83%E6%A1%88%E8%A2%AB%E5%91%8A%E7%99%BB%E6%8A%A5%E8%87%B4%E6%AD%89%23) `75.1K 🔥` `NEW`
1. [独行侠vs勇士](https://s.weibo.com/weibo?q=%23%E7%8B%AC%E8%A1%8C%E4%BE%A0vs%E5%8B%87%E5%A3%AB%23) `73.4K 🔥` `NEW`
1. [小猫起床的第一件事就是吸狗](https://s.weibo.com/weibo?q=%23%E5%B0%8F%E7%8C%AB%E8%B5%B7%E5%BA%8A%E7%9A%84%E7%AC%AC%E4%B8%80%E4%BB%B6%E4%BA%8B%E5%B0%B1%E6%98%AF%E5%90%B8%E7%8B%97%23) `70.2K 🔥` `NEW`
1. [逐玉配角 上桌](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%E9%85%8D%E8%A7%92%20%E4%B8%8A%E6%A1%8C%23) `69.6K 🔥` `NEW`
1. [单休一天出了一趟国](https://s.weibo.com/weibo?q=%23%E5%8D%95%E4%BC%91%E4%B8%80%E5%A4%A9%E5%87%BA%E4%BA%86%E4%B8%80%E8%B6%9F%E5%9B%BD%23) `296.2K 🔥` `+120%`
1. [伊朗公布袭击美军基地前后对比照](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%85%AC%E5%B8%83%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%E5%89%8D%E5%90%8E%E5%AF%B9%E6%AF%94%E7%85%A7%23) `185.0K 🔥` `+33%`
1. [地铁吐血女孩因重病拒绝男友求婚](https://s.weibo.com/weibo?q=%23%E5%9C%B0%E9%93%81%E5%90%90%E8%A1%80%E5%A5%B3%E5%AD%A9%E5%9B%A0%E9%87%8D%E7%97%85%E6%8B%92%E7%BB%9D%E7%94%B7%E5%8F%8B%E6%B1%82%E5%A9%9A%23) `182.1K 🔥` `+36%`
1. [女教师称要是班主任把你们折磨到死](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E6%95%99%E5%B8%88%E7%A7%B0%E8%A6%81%E6%98%AF%E7%8F%AD%E4%B8%BB%E4%BB%BB%E6%8A%8A%E4%BD%A0%E4%BB%AC%E6%8A%98%E7%A3%A8%E5%88%B0%E6%AD%BB%23) `177.3K 🔥` `+58%`
1. [真正的麻辣香锅已经非常罕见了 (Real spicy hotpot is very rare)](https://s.weibo.com/weibo?q=%23%E7%9C%9F%E6%AD%A3%E7%9A%84%E9%BA%BB%E8%BE%A3%E9%A6%99%E9%94%85%E5%B7%B2%E7%BB%8F%E9%9D%9E%E5%B8%B8%E7%BD%95%E8%A7%81%E4%BA%86%23) `319.1K 🔥`
1. [一个预防胃癌最简单的方法](https://s.weibo.com/weibo?q=%23%E4%B8%80%E4%B8%AA%E9%A2%84%E9%98%B2%E8%83%83%E7%99%8C%E6%9C%80%E7%AE%80%E5%8D%95%E7%9A%84%E6%96%B9%E6%B3%95%23) `128.3K 🔥`
1. [上京东买王濛的大魔王一加15T](https://s.weibo.com/weibo?q=%23%E4%B8%8A%E4%BA%AC%E4%B8%9C%E4%B9%B0%E7%8E%8B%E6%BF%9B%E7%9A%84%E5%A4%A7%E9%AD%94%E7%8E%8B%E4%B8%80%E5%8A%A015T%23) `300.0K 🔥` `-27%`
1. [海马体为出片要求穿长裙致孕妇摔倒 (Hippocampus required a pregnant woman to wear a long skirt for a film, causing her to fall)](https://s.weibo.com/weibo?q=%23%E6%B5%B7%E9%A9%AC%E4%BD%93%E4%B8%BA%E5%87%BA%E7%89%87%E8%A6%81%E6%B1%82%E7%A9%BF%E9%95%BF%E8%A3%99%E8%87%B4%E5%AD%95%E5%A6%87%E6%91%94%E5%80%92%23) `231.4K 🔥` `-42%`
1. [美团删照片](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%A2%E5%88%A0%E7%85%A7%E7%89%87%23) `184.0K 🔥` `-24%`
1. [张凌赫为什么被称为粉底液将军](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E4%B8%BA%E4%BB%80%E4%B9%88%E8%A2%AB%E7%A7%B0%E4%B8%BA%E7%B2%89%E5%BA%95%E6%B6%B2%E5%B0%86%E5%86%9B%23) `148.1K 🔥` `-40%`
1. [开推4迪丽热巴退出丁程鑫加入](https://s.weibo.com/weibo?q=%23%E5%BC%80%E6%8E%A84%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E9%80%80%E5%87%BA%E4%B8%81%E7%A8%8B%E9%91%AB%E5%8A%A0%E5%85%A5%23) `145.3K 🔥` `-21%`
1. [情侣住酒店正亲密时被员工开窗 (Couple staying in hotel was having sex when employee opened window)](https://s.weibo.com/weibo?q=%23%E6%83%85%E4%BE%A3%E4%BD%8F%E9%85%92%E5%BA%97%E6%AD%A3%E4%BA%B2%E5%AF%86%E6%97%B6%E8%A2%AB%E5%91%98%E5%B7%A5%E5%BC%80%E7%AA%97%23) `111.6K 🔥` `-39%`
1. [伊朗称美为操纵市场散布假新闻](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E7%BE%8E%E4%B8%BA%E6%93%8D%E7%BA%B5%E5%B8%82%E5%9C%BA%E6%95%A3%E5%B8%83%E5%81%87%E6%96%B0%E9%97%BB%23) `110.4K 🔥` `-61%`
1. [当代年轻人的潮流三件套](https://s.weibo.com/weibo?q=%23%E5%BD%93%E4%BB%A3%E5%B9%B4%E8%BD%BB%E4%BA%BA%E7%9A%84%E6%BD%AE%E6%B5%81%E4%B8%89%E4%BB%B6%E5%A5%97%23) `89.8K 🔥` `-66%`
1. [美第31海军陆战队远征队27日抵中东](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E7%AC%AC31%E6%B5%B7%E5%86%9B%E9%99%86%E6%88%98%E9%98%9F%E8%BF%9C%E5%BE%81%E9%98%9F27%E6%97%A5%E6%8A%B5%E4%B8%AD%E4%B8%9C%23) `74.9K 🔥` `-36%`

Updated at 2026-03-24 11:42:56

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
