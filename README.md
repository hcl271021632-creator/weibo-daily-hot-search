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

1. [领克07碳纤维尾翼版带感登场 (Lynk & Co 07 carbon fiber rear wing version debuts)](https://s.weibo.com/weibo?q=%23%E9%A2%86%E5%85%8B07%E7%A2%B3%E7%BA%A4%E7%BB%B4%E5%B0%BE%E7%BF%BC%E7%89%88%E5%B8%A6%E6%84%9F%E7%99%BB%E5%9C%BA%23) `406.3K 🔥` `NEW`
1. [霸王茶姬口令](https://s.weibo.com/weibo?q=%23%E9%9C%B8%E7%8E%8B%E8%8C%B6%E5%A7%AC%E5%8F%A3%E4%BB%A4%23) `389.8K 🔥` `NEW`
1. [月经弄脏卧铺当事人详述事件经过](https://s.weibo.com/weibo?q=%23%E6%9C%88%E7%BB%8F%E5%BC%84%E8%84%8F%E5%8D%A7%E9%93%BA%E5%BD%93%E4%BA%8B%E4%BA%BA%E8%AF%A6%E8%BF%B0%E4%BA%8B%E4%BB%B6%E7%BB%8F%E8%BF%87%23) `381.7K 🔥` `NEW`
1. [梅姨案有家庭认亲成功也未能团圆](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E6%A1%88%E6%9C%89%E5%AE%B6%E5%BA%AD%E8%AE%A4%E4%BA%B2%E6%88%90%E5%8A%9F%E4%B9%9F%E6%9C%AA%E8%83%BD%E5%9B%A2%E5%9C%86%23) `162.9K 🔥` `NEW`
1. [杨家鑫被梅姨拐走爸爸跳火车身亡](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E5%AE%B6%E9%91%AB%E8%A2%AB%E6%A2%85%E5%A7%A8%E6%8B%90%E8%B5%B0%E7%88%B8%E7%88%B8%E8%B7%B3%E7%81%AB%E8%BD%A6%E8%BA%AB%E4%BA%A1%23) `134.4K 🔥` `NEW`
1. [当女性大声说出我想要](https://s.weibo.com/weibo?q=%23%E5%BD%93%E5%A5%B3%E6%80%A7%E5%A4%A7%E5%A3%B0%E8%AF%B4%E5%87%BA%E6%88%91%E6%83%B3%E8%A6%81%23) `121.5K 🔥` `NEW`
1. [梅姨同居男友曾称警方画像不像](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E7%94%B7%E5%8F%8B%E6%9B%BE%E7%A7%B0%E8%AD%A6%E6%96%B9%E7%94%BB%E5%83%8F%E4%B8%8D%E5%83%8F%23) `106.9K 🔥` `NEW`
1. [梅姨曾与60多岁老人同居2年](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E6%9B%BE%E4%B8%8E60%E5%A4%9A%E5%B2%81%E8%80%81%E4%BA%BA%E5%90%8C%E5%B1%852%E5%B9%B4%23) `103.1K 🔥` `NEW`
1. [做饭2小时吃饭10分钟](https://s.weibo.com/weibo?q=%23%E5%81%9A%E9%A5%AD2%E5%B0%8F%E6%97%B6%E5%90%83%E9%A5%AD10%E5%88%86%E9%92%9F%23) `97.5K 🔥` `NEW`
1. [花10块都要经过深思熟虑](https://s.weibo.com/weibo?q=%23%E8%8A%B110%E5%9D%97%E9%83%BD%E8%A6%81%E7%BB%8F%E8%BF%87%E6%B7%B1%E6%80%9D%E7%86%9F%E8%99%91%23) `96.2K 🔥` `NEW`
1. [马嘉祺无框眼镜贵公子 (Ma Jiaqi rimless glasses noble man)](https://s.weibo.com/weibo?q=%23%E9%A9%AC%E5%98%89%E7%A5%BA%E6%97%A0%E6%A1%86%E7%9C%BC%E9%95%9C%E8%B4%B5%E5%85%AC%E5%AD%90%23) `96.1K 🔥` `NEW`
1. [下次给小朋友就这么切橙子](https://s.weibo.com/weibo?q=%23%E4%B8%8B%E6%AC%A1%E7%BB%99%E5%B0%8F%E6%9C%8B%E5%8F%8B%E5%B0%B1%E8%BF%99%E4%B9%88%E5%88%87%E6%A9%99%E5%AD%90%23) `93.6K 🔥` `NEW`
1. [男子借口卖烟去亲戚家踩点后抢劫](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E5%80%9F%E5%8F%A3%E5%8D%96%E7%83%9F%E5%8E%BB%E4%BA%B2%E6%88%9A%E5%AE%B6%E8%B8%A9%E7%82%B9%E5%90%8E%E6%8A%A2%E5%8A%AB%23) `86.3K 🔥` `NEW`
1. [老师为什么能发现家长签名是假的](https://s.weibo.com/weibo?q=%23%E8%80%81%E5%B8%88%E4%B8%BA%E4%BB%80%E4%B9%88%E8%83%BD%E5%8F%91%E7%8E%B0%E5%AE%B6%E9%95%BF%E7%AD%BE%E5%90%8D%E6%98%AF%E5%81%87%E7%9A%84%23) `80.2K 🔥` `NEW`
1. [梅姨画像耗时约4小时修改了四五次](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E7%94%BB%E5%83%8F%E8%80%97%E6%97%B6%E7%BA%A64%E5%B0%8F%E6%97%B6%E4%BF%AE%E6%94%B9%E4%BA%86%E5%9B%9B%E4%BA%94%E6%AC%A1%23) `70.1K 🔥` `NEW`
1. [睡眠不足带来的恶性影响](https://s.weibo.com/weibo?q=%23%E7%9D%A1%E7%9C%A0%E4%B8%8D%E8%B6%B3%E5%B8%A6%E6%9D%A5%E7%9A%84%E6%81%B6%E6%80%A7%E5%BD%B1%E5%93%8D%23) `66.0K 🔥` `NEW`
1. [多地中小银行集中清理沉睡账户](https://s.weibo.com/weibo?q=%23%E5%A4%9A%E5%9C%B0%E4%B8%AD%E5%B0%8F%E9%93%B6%E8%A1%8C%E9%9B%86%E4%B8%AD%E6%B8%85%E7%90%86%E6%B2%89%E7%9D%A1%E8%B4%A6%E6%88%B7%23) `59.0K 🔥` `NEW`
1. [五十公里桃花坞](https://s.weibo.com/weibo?q=%23%E4%BA%94%E5%8D%81%E5%85%AC%E9%87%8C%E6%A1%83%E8%8A%B1%E5%9D%9E%23) `57.9K 🔥` `NEW`
1. [梅姨同居男友都看不到她的身份证](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E7%94%B7%E5%8F%8B%E9%83%BD%E7%9C%8B%E4%B8%8D%E5%88%B0%E5%A5%B9%E7%9A%84%E8%BA%AB%E4%BB%BD%E8%AF%81%23) `1.2M 🔥` `+109%`
1. [梅姨同居男友说她不戴首饰](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E5%90%8C%E5%B1%85%E7%94%B7%E5%8F%8B%E8%AF%B4%E5%A5%B9%E4%B8%8D%E6%88%B4%E9%A6%96%E9%A5%B0%23) `422.6K 🔥` `+207%`
1. [女子熬夜3个月突然开始对墙讲课 (Woman stayed up late for 3 months and suddenly started lecturing against the wall)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E7%86%AC%E5%A4%9C3%E4%B8%AA%E6%9C%88%E7%AA%81%E7%84%B6%E5%BC%80%E5%A7%8B%E5%AF%B9%E5%A2%99%E8%AE%B2%E8%AF%BE%23) `419.0K 🔥` `+86%`
1. [软软的水 脆脆的水](https://s.weibo.com/weibo?q=%23%E8%BD%AF%E8%BD%AF%E7%9A%84%E6%B0%B4%20%E8%84%86%E8%84%86%E7%9A%84%E6%B0%B4%23) `412.8K 🔥` `+387%`
1. [90后男子为降血糖自制汤药身亡](https://s.weibo.com/weibo?q=%2390%E5%90%8E%E7%94%B7%E5%AD%90%E4%B8%BA%E9%99%8D%E8%A1%80%E7%B3%96%E8%87%AA%E5%88%B6%E6%B1%A4%E8%8D%AF%E8%BA%AB%E4%BA%A1%23) `402.9K 🔥` `+192%`
1. [美军核坟墓辐射量已超切尔诺贝利 (The amount of radiation in the US military's nuclear grave has exceeded that of Chernobyl)](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E6%A0%B8%E5%9D%9F%E5%A2%93%E8%BE%90%E5%B0%84%E9%87%8F%E5%B7%B2%E8%B6%85%E5%88%87%E5%B0%94%E8%AF%BA%E8%B4%9D%E5%88%A9%23) `398.6K 🔥` `+189%`
1. [谢征白吃醋了](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E7%99%BD%E5%90%83%E9%86%8B%E4%BA%86%23) `385.8K 🔥` `+212%`
1. [伊朗有意日本船只通行霍尔木兹海峡](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%89%E6%84%8F%E6%97%A5%E6%9C%AC%E8%88%B9%E5%8F%AA%E9%80%9A%E8%A1%8C%E9%9C%8D%E5%B0%94%E6%9C%A8%E5%85%B9%E6%B5%B7%E5%B3%A1%23) `185.9K 🔥` `+35%`
1. [以色列刚放完狠话防空警报就响了](https://s.weibo.com/weibo?q=%23%E4%BB%A5%E8%89%B2%E5%88%97%E5%88%9A%E6%94%BE%E5%AE%8C%E7%8B%A0%E8%AF%9D%E9%98%B2%E7%A9%BA%E8%AD%A6%E6%8A%A5%E5%B0%B1%E5%93%8D%E4%BA%86%23) `100.2K 🔥` `+48%`
1. [业内曝男演员比女演员修图难](https://s.weibo.com/weibo?q=%23%E4%B8%9A%E5%86%85%E6%9B%9D%E7%94%B7%E6%BC%94%E5%91%98%E6%AF%94%E5%A5%B3%E6%BC%94%E5%91%98%E4%BF%AE%E5%9B%BE%E9%9A%BE%23) `95.0K 🔥` `+29%`
1. [周杰伦拍了华语乐坛最贵mv](https://s.weibo.com/weibo?q=%23%E5%91%A8%E6%9D%B0%E4%BC%A6%E6%8B%8D%E4%BA%86%E5%8D%8E%E8%AF%AD%E4%B9%90%E5%9D%9B%E6%9C%80%E8%B4%B5mv%23) `76.6K 🔥` `+38%`
1. [梅姨被逮捕 (Aunt May was arrested)](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E8%A2%AB%E9%80%AE%E6%8D%95%23) `1.8M 🔥`
1. [总会被一棵树的张力震撼到 (I will always be shocked by the tension of a tree)](https://s.weibo.com/weibo?q=%23%E6%80%BB%E4%BC%9A%E8%A2%AB%E4%B8%80%E6%A3%B5%E6%A0%91%E7%9A%84%E5%BC%A0%E5%8A%9B%E9%9C%87%E6%92%BC%E5%88%B0%23) `750.8K 🔥`
1. [金饰价格已下跌超300元](https://s.weibo.com/weibo?q=%23%E9%87%91%E9%A5%B0%E4%BB%B7%E6%A0%BC%E5%B7%B2%E4%B8%8B%E8%B7%8C%E8%B6%85300%E5%85%83%23) `135.2K 🔥`
1. [谢某某就是梅姨](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E6%9F%90%E6%9F%90%E5%B0%B1%E6%98%AF%E6%A2%85%E5%A7%A8%23) `129.5K 🔥`
1. [谢征俞宝儿是连襟 (Xie Zheng and Yu Baoer are brothers-in-law)](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E4%BF%9E%E5%AE%9D%E5%84%BF%E6%98%AF%E8%BF%9E%E8%A5%9F%23) `122.5K 🔥`
1. [鹿晗 关晓彤 (Lu Han Guan Xiaotong)](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%20%E5%85%B3%E6%99%93%E5%BD%A4%23) `119.4K 🔥`
1. [白象 土豆泥火鸡面 (White Elephant Mashed Potato Turkey Noodles)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E8%B1%A1%20%E5%9C%9F%E8%B1%86%E6%B3%A5%E7%81%AB%E9%B8%A1%E9%9D%A2%23) `117.2K 🔥`
1. [曝迪丽热巴新经纪人入职嘉行](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E6%96%B0%E7%BB%8F%E7%BA%AA%E4%BA%BA%E5%85%A5%E8%81%8C%E5%98%89%E8%A1%8C%23) `114.4K 🔥`
1. [痞幼因网红身份被邻居排挤](https://s.weibo.com/weibo?q=%23%E7%97%9E%E5%B9%BC%E5%9B%A0%E7%BD%91%E7%BA%A2%E8%BA%AB%E4%BB%BD%E8%A2%AB%E9%82%BB%E5%B1%85%E6%8E%92%E6%8C%A4%23) `113.0K 🔥`
1. [梅姨与画像相似度不到30%](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E4%B8%8E%E7%94%BB%E5%83%8F%E7%9B%B8%E4%BC%BC%E5%BA%A6%E4%B8%8D%E5%88%B030%25%23) `111.0K 🔥`
1. [濮院重新定义古镇非标模式](https://s.weibo.com/weibo?q=%23%E6%BF%AE%E9%99%A2%E9%87%8D%E6%96%B0%E5%AE%9A%E4%B9%89%E5%8F%A4%E9%95%87%E9%9D%9E%E6%A0%87%E6%A8%A1%E5%BC%8F%23) `81.6K 🔥`
1. [粉丝误把五月天门票送给韩雨彤 (Fan mistakenly gave Mayday tickets to Han Yutong)](https://s.weibo.com/weibo?q=%23%E7%B2%89%E4%B8%9D%E8%AF%AF%E6%8A%8A%E4%BA%94%E6%9C%88%E5%A4%A9%E9%97%A8%E7%A5%A8%E9%80%81%E7%BB%99%E9%9F%A9%E9%9B%A8%E5%BD%A4%23) `79.7K 🔥`
1. [猫咪意识到抚摸它的不是妈妈](https://s.weibo.com/weibo?q=%23%E7%8C%AB%E5%92%AA%E6%84%8F%E8%AF%86%E5%88%B0%E6%8A%9A%E6%91%B8%E5%AE%83%E7%9A%84%E4%B8%8D%E6%98%AF%E5%A6%88%E5%A6%88%23) `73.3K 🔥`
1. [为什么猫咪塌鼻梁还那么可爱](https://s.weibo.com/weibo?q=%23%E4%B8%BA%E4%BB%80%E4%B9%88%E7%8C%AB%E5%92%AA%E5%A1%8C%E9%BC%BB%E6%A2%81%E8%BF%98%E9%82%A3%E4%B9%88%E5%8F%AF%E7%88%B1%23) `64.7K 🔥`
1. [什么是减压深睡裤 (What are pressure relief pajamas?)](https://s.weibo.com/weibo?q=%23%E4%BB%80%E4%B9%88%E6%98%AF%E5%87%8F%E5%8E%8B%E6%B7%B1%E7%9D%A1%E8%A3%A4%23) `530.9K 🔥` `-39%`
1. [梅姨长相与公布画像相似度不高](https://s.weibo.com/weibo?q=%23%E6%A2%85%E5%A7%A8%E9%95%BF%E7%9B%B8%E4%B8%8E%E5%85%AC%E5%B8%83%E7%94%BB%E5%83%8F%E7%9B%B8%E4%BC%BC%E5%BA%A6%E4%B8%8D%E9%AB%98%23) `279.4K 🔥` `-71%`
1. [别来工作的地方找我 (Don't come to me at work)](https://s.weibo.com/weibo?q=%23%E5%88%AB%E6%9D%A5%E5%B7%A5%E4%BD%9C%E7%9A%84%E5%9C%B0%E6%96%B9%E6%89%BE%E6%88%91%23) `138.6K 🔥` `-31%`
1. [张凌赫男大自拍](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B7%E5%A4%A7%E8%87%AA%E6%8B%8D%23) `105.3K 🔥` `-23%`
1. [曝梁小龙去世两个月没下葬将停棺10年](https://s.weibo.com/weibo?q=%23%E6%9B%9D%E6%A2%81%E5%B0%8F%E9%BE%99%E5%8E%BB%E4%B8%96%E4%B8%A4%E4%B8%AA%E6%9C%88%E6%B2%A1%E4%B8%8B%E8%91%AC%E5%B0%86%E5%81%9C%E6%A3%BA10%E5%B9%B4%23) `105.1K 🔥` `-24%`
1. [迪丽热巴再被叫胖迪很惊讶 (Dilireba was surprised to be called Fatty again)](https://s.weibo.com/weibo?q=%23%E8%BF%AA%E4%B8%BD%E7%83%AD%E5%B7%B4%E5%86%8D%E8%A2%AB%E5%8F%AB%E8%83%96%E8%BF%AA%E5%BE%88%E6%83%8A%E8%AE%B6%23) `99.6K 🔥` `-28%`
1. [张凌赫田曦薇 所有人都在觊觎我妻子](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%20%E6%89%80%E6%9C%89%E4%BA%BA%E9%83%BD%E5%9C%A8%E8%A7%8A%E8%A7%8E%E6%88%91%E5%A6%BB%E5%AD%90%23) `97.4K 🔥` `-29%`
1. [网友通过倪妮悄悄话分析出汤唯怀孕了 (Netizens analyzed that Tang Wei was pregnant through Ni Ni’s whispers)](https://s.weibo.com/weibo?q=%23%E7%BD%91%E5%8F%8B%E9%80%9A%E8%BF%87%E5%80%AA%E5%A6%AE%E6%82%84%E6%82%84%E8%AF%9D%E5%88%86%E6%9E%90%E5%87%BA%E6%B1%A4%E5%94%AF%E6%80%80%E5%AD%95%E4%BA%86%23) `97.0K 🔥` `-29%`
1. [AG锁定季后赛胜者组](https://s.weibo.com/weibo?q=%23AG%E9%94%81%E5%AE%9A%E5%AD%A3%E5%90%8E%E8%B5%9B%E8%83%9C%E8%80%85%E7%BB%84%23) `58.8K 🔥` `-32%`

Updated at 2026-03-21 17:44:15

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
