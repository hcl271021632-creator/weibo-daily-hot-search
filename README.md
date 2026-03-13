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

1. [F1](https://s.weibo.com/weibo?q=%23F1%23) `1.1M 🔥` `NEW`
1. [微信新功能被称为社恐福音](https://s.weibo.com/weibo?q=%23%E5%BE%AE%E4%BF%A1%E6%96%B0%E5%8A%9F%E8%83%BD%E8%A2%AB%E7%A7%B0%E4%B8%BA%E7%A4%BE%E6%81%90%E7%A6%8F%E9%9F%B3%23) `787.5K 🔥` `NEW`
1. [冻干草莓测出二十几种农药](https://s.weibo.com/weibo?q=%23%E5%86%BB%E5%B9%B2%E8%8D%89%E8%8E%93%E6%B5%8B%E5%87%BA%E4%BA%8C%E5%8D%81%E5%87%A0%E7%A7%8D%E5%86%9C%E8%8D%AF%23) `294.8K 🔥` `NEW`
1. [沈月张晚意开机路透](https://s.weibo.com/weibo?q=%23%E6%B2%88%E6%9C%88%E5%BC%A0%E6%99%9A%E6%84%8F%E5%BC%80%E6%9C%BA%E8%B7%AF%E9%80%8F%23) `237.7K 🔥` `NEW`
1. [以色列总理威胁刺杀伊朗新最高领袖](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E6%80%BB%E7%90%86%E5%A8%81%E8%83%81%E5%88%BA%E6%9D%80%E4%BC%8A%E6%9C%97%E6%96%B0%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%23) `200.9K 🔥` `NEW`
1. [苍南一民房煤气燃烧致1死系AI生成](https://s.weibo.com/weibo?q=%23%E8%8B%8D%E5%8D%97%E4%B8%80%E6%B0%91%E6%88%BF%E7%85%A4%E6%B0%94%E7%87%83%E7%83%A7%E8%87%B41%E6%AD%BB%E7%B3%BBAI%E7%94%9F%E6%88%90%23) `184.1K 🔥` `NEW`
1. [此人的懒商还是太超前了](https://s.weibo.com/weibo?q=%23%E6%AD%A4%E4%BA%BA%E7%9A%84%E6%87%92%E5%95%86%E8%BF%98%E6%98%AF%E5%A4%AA%E8%B6%85%E5%89%8D%E4%BA%86%23) `161.4K 🔥` `NEW`
1. [但愿人长久](https://s.weibo.com/weibo?q=%23%E4%BD%86%E6%84%BF%E4%BA%BA%E9%95%BF%E4%B9%85%23) `160.1K 🔥` `NEW`
1. [3个新人跑两会是啥体验](https://s.weibo.com/weibo?q=%233%E4%B8%AA%E6%96%B0%E4%BA%BA%E8%B7%91%E4%B8%A4%E4%BC%9A%E6%98%AF%E5%95%A5%E4%BD%93%E9%AA%8C%23) `160.0K 🔥` `NEW`
1. [保洁员发现男子被遗忘核磁共振机](https://s.weibo.com/weibo?q=%23%E4%BF%9D%E6%B4%81%E5%91%98%E5%8F%91%E7%8E%B0%E7%94%B7%E5%AD%90%E8%A2%AB%E9%81%97%E5%BF%98%E6%A0%B8%E7%A3%81%E5%85%B1%E6%8C%AF%E6%9C%BA%23) `159.6K 🔥` `NEW`
1. [张踩铃 不要脸的人先享受甜茶 (The shameless person Zhang Tie Ling enjoys the sweet tea first)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E8%B8%A9%E9%93%83%20%E4%B8%8D%E8%A6%81%E8%84%B8%E7%9A%84%E4%BA%BA%E5%85%88%E4%BA%AB%E5%8F%97%E7%94%9C%E8%8C%B6%23) `159.2K 🔥` `NEW`
1. [澳洲遇难2名中国人深夜自驾赶工作](https://s.weibo.com/weibo?q=%23%E6%BE%B3%E6%B4%B2%E9%81%87%E9%9A%BE2%E5%90%8D%E4%B8%AD%E5%9B%BD%E4%BA%BA%E6%B7%B1%E5%A4%9C%E8%87%AA%E9%A9%BE%E8%B5%B6%E5%B7%A5%E4%BD%9C%23) `158.9K 🔥` `NEW`
1. [苹果税下调](https://s.weibo.com/weibo?q=%23%E8%8B%B9%E6%9E%9C%E7%A8%8E%E4%B8%8B%E8%B0%83%23) `158.7K 🔥` `NEW`
1. [豆包 消极怠工](https://s.weibo.com/weibo?q=%23%E8%B1%86%E5%8C%85%20%E6%B6%88%E6%9E%81%E6%80%A0%E5%B7%A5%23) `158.3K 🔥` `NEW`
1. [杨紫罗马看秀G社生图](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E7%BD%97%E9%A9%AC%E7%9C%8B%E7%A7%80G%E7%A4%BE%E7%94%9F%E5%9B%BE%23) `158.2K 🔥` `NEW`
1. [孔雪儿回复田曦薇](https://s.weibo.com/weibo?q=%23%E5%AD%94%E9%9B%AA%E5%84%BF%E5%9B%9E%E5%A4%8D%E7%94%B0%E6%9B%A6%E8%96%87%23) `157.9K 🔥` `NEW`
1. [俄向伊朗提供人道主义援助](https://s.weibo.com/weibo?q=%23%E4%BF%84%E5%90%91%E4%BC%8A%E6%9C%97%E6%8F%90%E4%BE%9B%E4%BA%BA%E9%81%93%E4%B8%BB%E4%B9%89%E6%8F%B4%E5%8A%A9%23) `156.1K 🔥` `NEW`
1. [多地学校取消家长护学岗](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E5%AD%A6%E6%A0%A1%E5%8F%96%E6%B6%88%E5%AE%B6%E9%95%BF%E6%8A%A4%E5%AD%A6%E5%B2%97%23) `155.9K 🔥` `NEW`
1. [拼多多试行免费送货进村](https://s.weibo.com/weibo?q=%23%E6%8B%BC%E5%A4%9A%E5%A4%9A%E8%AF%95%E8%A1%8C%E5%85%8D%E8%B4%B9%E9%80%81%E8%B4%A7%E8%BF%9B%E6%9D%91%23) `155.1K 🔥` `NEW`
1. [杨紫不染发是因为大家喜欢黑色](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E4%B8%8D%E6%9F%93%E5%8F%91%E6%98%AF%E5%9B%A0%E4%B8%BA%E5%A4%A7%E5%AE%B6%E5%96%9C%E6%AC%A2%E9%BB%91%E8%89%B2%23) `154.8K 🔥` `NEW`
1. [陈浚铭 闹鬼了 (Chen Junming is haunted)](https://s.weibo.com/weibo?q=%23%E9%99%88%E6%B5%9A%E9%93%AD%20%E9%97%B9%E9%AC%BC%E4%BA%86%23) `154.1K 🔥` `NEW`
1. [医院通报患者被遗忘6小时处理结果](https://s.weibo.com/weibo?q=%23%E5%8C%BB%E9%99%A2%E9%80%9A%E6%8A%A5%E6%82%A3%E8%80%85%E8%A2%AB%E9%81%97%E5%BF%986%E5%B0%8F%E6%97%B6%E5%A4%84%E7%90%86%E7%BB%93%E6%9E%9C%23) `153.8K 🔥` `NEW`
1. [白鹿丁禹兮 恰逢雨连天](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E4%B8%81%E7%A6%B9%E5%85%AE%20%E6%81%B0%E9%80%A2%E9%9B%A8%E8%BF%9E%E5%A4%A9%23) `152.8K 🔥` `NEW`
1. [12岁男孩很少生病突然查出肾衰竭](https://s.weibo.com/weibo?q=%2312%E5%B2%81%E7%94%B7%E5%AD%A9%E5%BE%88%E5%B0%91%E7%94%9F%E7%97%85%E7%AA%81%E7%84%B6%E6%9F%A5%E5%87%BA%E8%82%BE%E8%A1%B0%E7%AB%AD%23) `138.0K 🔥` `NEW`
1. [代露娃唐诗逸开机路透](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E9%9C%B2%E5%A8%83%E5%94%90%E8%AF%97%E9%80%B8%E5%BC%80%E6%9C%BA%E8%B7%AF%E9%80%8F%23) `134.9K 🔥` `NEW`
1. [张柏芝一把夺过粉丝手机合拍](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E6%9F%8F%E8%8A%9D%E4%B8%80%E6%8A%8A%E5%A4%BA%E8%BF%87%E7%B2%89%E4%B8%9D%E6%89%8B%E6%9C%BA%E5%90%88%E6%8B%8D%23) `126.5K 🔥` `NEW`
1. [霍华德宣布退役](https://s.weibo.com/weibo?q=%23%E9%9C%8D%E5%8D%8E%E5%BE%B7%E5%AE%A3%E5%B8%83%E9%80%80%E5%BD%B9%23) `108.6K 🔥` `NEW`
1. [天津一摊主削凤梨火了](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E6%B4%A5%E4%B8%80%E6%91%8A%E4%B8%BB%E5%89%8A%E5%87%A4%E6%A2%A8%E7%81%AB%E4%BA%86%23) `108.0K 🔥` `NEW`
1. [新一代SU7靛石绿](https://s.weibo.com/weibo?q=%23%E6%96%B0%E4%B8%80%E4%BB%A3SU7%E9%9D%9B%E7%9F%B3%E7%BB%BF%23) `106.2K 🔥` `NEW`
1. [沧元图](https://s.weibo.com/weibo?q=%23%E6%B2%A7%E5%85%83%E5%9B%BE%23) `97.9K 🔥` `NEW`
1. [教育局回应学校取消家长护学岗 (The Education Bureau responded to the school’s cancellation of parent nursing posts)](https://s.weibo.com/weibo?q=%23%E6%95%99%E8%82%B2%E5%B1%80%E5%9B%9E%E5%BA%94%E5%AD%A6%E6%A0%A1%E5%8F%96%E6%B6%88%E5%AE%B6%E9%95%BF%E6%8A%A4%E5%AD%A6%E5%B2%97%23) `97.2K 🔥` `NEW`
1. [伊朗公布袭击美军基地卫星图像](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%85%AC%E5%B8%83%E8%A2%AD%E5%87%BB%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%E5%8D%AB%E6%98%9F%E5%9B%BE%E5%83%8F%23) `95.4K 🔥` `NEW`
1. [女总裁人设带货不知名美妆月销破亿](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E6%80%BB%E8%A3%81%E4%BA%BA%E8%AE%BE%E5%B8%A6%E8%B4%A7%E4%B8%8D%E7%9F%A5%E5%90%8D%E7%BE%8E%E5%A6%86%E6%9C%88%E9%94%80%E7%A0%B4%E4%BA%BF%23) `86.8K 🔥` `NEW`
1. [公司AI监控](https://s.weibo.com/weibo?q=%23%E5%85%AC%E5%8F%B8AI%E7%9B%91%E6%8E%A7%23) `82.3K 🔥` `NEW`
1. [爷爷跨越2200公里找孙女看哭网友](https://s.weibo.com/weibo?q=%23%E7%88%B7%E7%88%B7%E8%B7%A8%E8%B6%8A2200%E5%85%AC%E9%87%8C%E6%89%BE%E5%AD%99%E5%A5%B3%E7%9C%8B%E5%93%AD%E7%BD%91%E5%8F%8B%23) `81.0K 🔥` `NEW`
1. [但愿人长久全阵容官宣](https://s.weibo.com/weibo?q=%23%E4%BD%86%E6%84%BF%E4%BA%BA%E9%95%BF%E4%B9%85%E5%85%A8%E9%98%B5%E5%AE%B9%E5%AE%98%E5%AE%A3%23) `75.7K 🔥` `NEW`
1. [新一代小米SU7本月发布](https://s.weibo.com/weibo?q=%23%E6%96%B0%E4%B8%80%E4%BB%A3%E5%B0%8F%E7%B1%B3SU7%E6%9C%AC%E6%9C%88%E5%8F%91%E5%B8%83%23) `75.4K 🔥` `NEW`
1. [黑白真的能抑制食欲](https://s.weibo.com/weibo?q=%23%E9%BB%91%E7%99%BD%E7%9C%9F%E7%9A%84%E8%83%BD%E6%8A%91%E5%88%B6%E9%A3%9F%E6%AC%B2%23) `71.7K 🔥` `NEW`
1. [业内称草莓存农残和重金属两大顽疾](https://s.weibo.com/weibo?q=%23%E4%B8%9A%E5%86%85%E7%A7%B0%E8%8D%89%E8%8E%93%E5%AD%98%E5%86%9C%E6%AE%8B%E5%92%8C%E9%87%8D%E9%87%91%E5%B1%9E%E4%B8%A4%E5%A4%A7%E9%A1%BD%E7%96%BE%23) `70.1K 🔥` `NEW`
1. [从一只大公鸡身上看到了安全感](https://s.weibo.com/weibo?q=%23%E4%BB%8E%E4%B8%80%E5%8F%AA%E5%A4%A7%E5%85%AC%E9%B8%A1%E8%BA%AB%E4%B8%8A%E7%9C%8B%E5%88%B0%E4%BA%86%E5%AE%89%E5%85%A8%E6%84%9F%23) `68.5K 🔥` `NEW`
1. [法院拍卖布加迪跑车强调无法上牌 (Court auction of Bugatti sports car emphasizes that it cannot be registered)](https://s.weibo.com/weibo?q=%23%E6%B3%95%E9%99%A2%E6%8B%8D%E5%8D%96%E5%B8%83%E5%8A%A0%E8%BF%AA%E8%B7%91%E8%BD%A6%E5%BC%BA%E8%B0%83%E6%97%A0%E6%B3%95%E4%B8%8A%E7%89%8C%23) `93.5K 🔥` `+61%`
1. [鹿晗专辑预告](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E4%B8%93%E8%BE%91%E9%A2%84%E5%91%8A%23) `89.5K 🔥` `+31%`
1. [春天里的中国向新而行 (China in spring moves towards newness)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%A4%A9%E9%87%8C%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%90%91%E6%96%B0%E8%80%8C%E8%A1%8C%23) `644.3K 🔥`
1. [女子腰臀部疼了8年终于找到元凶 (A woman has been suffering from waist and hip pain for 8 years and finally found the culprit)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%85%B0%E8%87%80%E9%83%A8%E7%96%BC%E4%BA%868%E5%B9%B4%E7%BB%88%E4%BA%8E%E6%89%BE%E5%88%B0%E5%85%83%E5%87%B6%23) `114.3K 🔥`
1. [樊长玉取关言正 (Fan Changyu takes Guan Yanzheng)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E5%8F%96%E5%85%B3%E8%A8%80%E6%AD%A3%23) `96.9K 🔥`
1. [女子不爱喝水长巨型肾结石](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B8%8D%E7%88%B1%E5%96%9D%E6%B0%B4%E9%95%BF%E5%B7%A8%E5%9E%8B%E8%82%BE%E7%BB%93%E7%9F%B3%23) `86.2K 🔥`
1. [京东采销比价直播发1斤黄金 (JD.com sells 1 catty of gold via live streaming of purchasing, selling and price comparison)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E9%87%87%E9%94%80%E6%AF%94%E4%BB%B7%E7%9B%B4%E6%92%AD%E5%8F%911%E6%96%A4%E9%BB%84%E9%87%91%23) `438.1K 🔥` `-24%`
1. [今年加快研究人工智能立法 (Accelerate research on artificial intelligence legislation this year)](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E5%8A%A0%E5%BF%AB%E7%A0%94%E7%A9%B6%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%AB%8B%E6%B3%95%23) `161.9K 🔥` `-65%`
1. [张凌赫田曦薇醉酒吻是现挂 (Zhang Linghe and Tian Xiwei’s drunken kiss is now hanging)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E9%86%89%E9%85%92%E5%90%BB%E6%98%AF%E7%8E%B0%E6%8C%82%23) `153.4K 🔥` `-26%`
1. [伊朗称若电力遭袭整个地区将陷黑暗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E8%8B%A5%E7%94%B5%E5%8A%9B%E9%81%AD%E8%A2%AD%E6%95%B4%E4%B8%AA%E5%9C%B0%E5%8C%BA%E5%B0%86%E9%99%B7%E9%BB%91%E6%9A%97%23) `99.6K 🔥` `-80%`
1. [美军福特号航母发生火灾](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E7%A6%8F%E7%89%B9%E5%8F%B7%E8%88%AA%E6%AF%8D%E5%8F%91%E7%94%9F%E7%81%AB%E7%81%BE%23) `70.2K 🔥` `-30%`
1. [建议允许公积金直接抵首付还房贷 (It is recommended that provident funds be allowed to be used directly as down payments to repay mortgages)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%85%81%E8%AE%B8%E5%85%AC%E7%A7%AF%E9%87%91%E7%9B%B4%E6%8E%A5%E6%8A%B5%E9%A6%96%E4%BB%98%E8%BF%98%E6%88%BF%E8%B4%B7%23) `68.1K 🔥` `-93%`

Updated at 2026-03-13 10:49:09

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
