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

1. [今年加快研究人工智能立法 (Accelerate research on artificial intelligence legislation this year)](https://s.weibo.com/weibo?q=%23%E4%BB%8A%E5%B9%B4%E5%8A%A0%E5%BF%AB%E7%A0%94%E7%A9%B6%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%AB%8B%E6%B3%95%23) `466.6K 🔥` `NEW`
1. [人大代表支招小单方治大病](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E6%94%AF%E6%8B%9B%E5%B0%8F%E5%8D%95%E6%96%B9%E6%B2%BB%E5%A4%A7%E7%97%85%23) `406.2K 🔥` `NEW`
1. [代表关于物业的建议被采纳](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E5%85%B3%E4%BA%8E%E7%89%A9%E4%B8%9A%E7%9A%84%E5%BB%BA%E8%AE%AE%E8%A2%AB%E9%87%87%E7%BA%B3%23) `274.2K 🔥` `NEW`
1. [法院拍卖布加迪跑车强调无法上牌](https://s.weibo.com/weibo?q=%23%E6%B3%95%E9%99%A2%E6%8B%8D%E5%8D%96%E5%B8%83%E5%8A%A0%E8%BF%AA%E8%B7%91%E8%BD%A6%E5%BC%BA%E8%B0%83%E6%97%A0%E6%B3%95%E4%B8%8A%E7%89%8C%23) `58.2K 🔥` `NEW`
1. [春天里的中国向新而行 (China in spring moves towards newness)](https://s.weibo.com/weibo?q=%23%E6%98%A5%E5%A4%A9%E9%87%8C%E7%9A%84%E4%B8%AD%E5%9B%BD%E5%90%91%E6%96%B0%E8%80%8C%E8%A1%8C%23) `608.4K 🔥` `+23%`
1. [京东采销比价直播发1斤黄金 (JD.com sells 1 catty of gold via live streaming of purchasing, selling and price comparison)](https://s.weibo.com/weibo?q=%23%E4%BA%AC%E4%B8%9C%E9%87%87%E9%94%80%E6%AF%94%E4%BB%B7%E7%9B%B4%E6%92%AD%E5%8F%911%E6%96%A4%E9%BB%84%E9%87%91%23) `572.9K 🔥` `+43%`
1. [法拉利来中国也得进货 (Ferrari has to buy goods when it comes to China)](https://s.weibo.com/weibo?q=%23%E6%B3%95%E6%8B%89%E5%88%A9%E6%9D%A5%E4%B8%AD%E5%9B%BD%E4%B9%9F%E5%BE%97%E8%BF%9B%E8%B4%A7%23) `548.2K 🔥` `+74%`
1. [代表推进小班化教学建议被采纳 (Representatives’ suggestions for promoting small class teaching were adopted)](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E6%8E%A8%E8%BF%9B%E5%B0%8F%E7%8F%AD%E5%8C%96%E6%95%99%E5%AD%A6%E5%BB%BA%E8%AE%AE%E8%A2%AB%E9%87%87%E7%BA%B3%23) `504.0K 🔥` `+141%`
1. [伊朗称若电力遭袭整个地区将陷黑暗](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%A7%B0%E8%8B%A5%E7%94%B5%E5%8A%9B%E9%81%AD%E8%A2%AD%E6%95%B4%E4%B8%AA%E5%9C%B0%E5%8C%BA%E5%B0%86%E9%99%B7%E9%BB%91%E6%9A%97%23) `492.4K 🔥` `+586%`
1. [世界从中国两会看到新机遇 (The world sees new opportunities from China’s Two Sessions)](https://s.weibo.com/weibo?q=%23%E4%B8%96%E7%95%8C%E4%BB%8E%E4%B8%AD%E5%9B%BD%E4%B8%A4%E4%BC%9A%E7%9C%8B%E5%88%B0%E6%96%B0%E6%9C%BA%E9%81%87%23) `327.1K 🔥` `+102%`
1. [伊朗最高领袖公开声明](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E5%85%AC%E5%BC%80%E5%A3%B0%E6%98%8E%23) `217.8K 🔥` `+45%`
1. [张凌赫田曦薇醉酒吻是现挂 (Zhang Linghe and Tian Xiwei’s drunken kiss is now hanging)](https://s.weibo.com/weibo?q=%23%E5%BC%A0%E5%87%8C%E8%B5%AB%E7%94%B0%E6%9B%A6%E8%96%87%E9%86%89%E9%85%92%E5%90%BB%E6%98%AF%E7%8E%B0%E6%8C%82%23) `207.4K 🔥` `+60%`
1. [飞机上到处求摸摸的社交悍匪小狗](https://s.weibo.com/weibo?q=%23%E9%A3%9E%E6%9C%BA%E4%B8%8A%E5%88%B0%E5%A4%84%E6%B1%82%E6%91%B8%E6%91%B8%E7%9A%84%E7%A4%BE%E4%BA%A4%E6%82%8D%E5%8C%AA%E5%B0%8F%E7%8B%97%23) `139.4K 🔥` `+49%`
1. [谢征带兵救下宁娘](https://s.weibo.com/weibo?q=%23%E8%B0%A2%E5%BE%81%E5%B8%A6%E5%85%B5%E6%95%91%E4%B8%8B%E5%AE%81%E5%A8%98%23) `138.4K 🔥` `+162%`
1. [杨紫说没接综艺](https://s.weibo.com/weibo?q=%23%E6%9D%A8%E7%B4%AB%E8%AF%B4%E6%B2%A1%E6%8E%A5%E7%BB%BC%E8%89%BA%23) `100.9K 🔥` `+52%`
1. [美军一加油机坠毁据称非被击落](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E4%B8%80%E5%8A%A0%E6%B2%B9%E6%9C%BA%E5%9D%A0%E6%AF%81%E6%8D%AE%E7%A7%B0%E9%9D%9E%E8%A2%AB%E5%87%BB%E8%90%BD%23) `92.8K 🔥` `+49%`
1. [科学家发现30亿年前月球仍生机勃勃 (Scientists discover that the moon was still full of life 3 billion years ago)](https://s.weibo.com/weibo?q=%23%E7%A7%91%E5%AD%A6%E5%AE%B6%E5%8F%91%E7%8E%B030%E4%BA%BF%E5%B9%B4%E5%89%8D%E6%9C%88%E7%90%83%E4%BB%8D%E7%94%9F%E6%9C%BA%E5%8B%83%E5%8B%83%23) `69.6K 🔥` `+27%`
1. [建议允许公积金直接抵首付还房贷 (It is recommended that provident funds be allowed to be used directly as down payments to repay mortgages)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E5%85%81%E8%AE%B8%E5%85%AC%E7%A7%AF%E9%87%91%E7%9B%B4%E6%8E%A5%E6%8A%B5%E9%A6%96%E4%BB%98%E8%BF%98%E6%88%BF%E8%B4%B7%23) `1.0M 🔥`
1. [中方回应特朗普计划访华 (China responds to Trump's planned visit to China)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E7%89%B9%E6%9C%97%E6%99%AE%E8%AE%A1%E5%88%92%E8%AE%BF%E5%8D%8E%23) `739.1K 🔥`
1. [建议给新就业形态人员缴纳社保 (It is recommended to pay social security for people with new employment forms)](https://s.weibo.com/weibo?q=%23%E5%BB%BA%E8%AE%AE%E7%BB%99%E6%96%B0%E5%B0%B1%E4%B8%9A%E5%BD%A2%E6%80%81%E4%BA%BA%E5%91%98%E7%BC%B4%E7%BA%B3%E7%A4%BE%E4%BF%9D%23) `178.5K 🔥`
1. [呼吁老人大额转账设24小时冷静期](https://s.weibo.com/weibo?q=%23%E5%91%BC%E5%90%81%E8%80%81%E4%BA%BA%E5%A4%A7%E9%A2%9D%E8%BD%AC%E8%B4%A6%E8%AE%BE24%E5%B0%8F%E6%97%B6%E5%86%B7%E9%9D%99%E6%9C%9F%23) `173.5K 🔥`
1. [美国防部被曝龙虾门](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%9B%BD%E9%98%B2%E9%83%A8%E8%A2%AB%E6%9B%9D%E9%BE%99%E8%99%BE%E9%97%A8%23) `172.7K 🔥`
1. [人大代表说一切都离不开创新](https://s.weibo.com/weibo?q=%23%E4%BA%BA%E5%A4%A7%E4%BB%A3%E8%A1%A8%E8%AF%B4%E4%B8%80%E5%88%87%E9%83%BD%E7%A6%BB%E4%B8%8D%E5%BC%80%E5%88%9B%E6%96%B0%23) `154.5K 🔥`
1. [西安不倒翁小姐姐宣布离职 (The roly-poly girl from Xi'an announced her resignation)](https://s.weibo.com/weibo?q=%23%E8%A5%BF%E5%AE%89%E4%B8%8D%E5%80%92%E7%BF%81%E5%B0%8F%E5%A7%90%E5%A7%90%E5%AE%A3%E5%B8%83%E7%A6%BB%E8%81%8C%23) `152.8K 🔥`
1. [男子被遗忘核磁共振机涉事医生发声 (Doctor involved in man's forgotten MRI machine speaks out)](https://s.weibo.com/weibo?q=%23%E7%94%B7%E5%AD%90%E8%A2%AB%E9%81%97%E5%BF%98%E6%A0%B8%E7%A3%81%E5%85%B1%E6%8C%AF%E6%9C%BA%E6%B6%89%E4%BA%8B%E5%8C%BB%E7%94%9F%E5%8F%91%E5%A3%B0%23) `100.5K 🔥`
1. [李维嘉或将你好星期六常驻 (Li Weijia may make Hello Saturday permanent)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E7%BB%B4%E5%98%89%E6%88%96%E5%B0%86%E4%BD%A0%E5%A5%BD%E6%98%9F%E6%9C%9F%E5%85%AD%E5%B8%B8%E9%A9%BB%23) `95.5K 🔥`
1. [衣服洗不干净的原因找到了](https://s.weibo.com/weibo?q=%23%E8%A1%A3%E6%9C%8D%E6%B4%97%E4%B8%8D%E5%B9%B2%E5%87%80%E7%9A%84%E5%8E%9F%E5%9B%A0%E6%89%BE%E5%88%B0%E4%BA%86%23) `95.3K 🔥`
1. [女子腰臀部疼了8年终于找到元凶 (A woman has been suffering from waist and hip pain for 8 years and finally found the culprit)](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E8%85%B0%E8%87%80%E9%83%A8%E7%96%BC%E4%BA%868%E5%B9%B4%E7%BB%88%E4%BA%8E%E6%89%BE%E5%88%B0%E5%85%83%E5%87%B6%23) `95.0K 🔥`
1. [韩网热议韩国掀起中国热 (Korean nets are hotly discussing South Korea’s rise in China fever)](https://s.weibo.com/weibo?q=%23%E9%9F%A9%E7%BD%91%E7%83%AD%E8%AE%AE%E9%9F%A9%E5%9B%BD%E6%8E%80%E8%B5%B7%E4%B8%AD%E5%9B%BD%E7%83%AD%23) `94.7K 🔥`
1. [女子寺庙求姻缘遇心动男生](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E5%AF%BA%E5%BA%99%E6%B1%82%E5%A7%BB%E7%BC%98%E9%81%87%E5%BF%83%E5%8A%A8%E7%94%B7%E7%94%9F%23) `93.5K 🔥`
1. [女子不爱喝水长巨型肾结石](https://s.weibo.com/weibo?q=%23%E5%A5%B3%E5%AD%90%E4%B8%8D%E7%88%B1%E5%96%9D%E6%B0%B4%E9%95%BF%E5%B7%A8%E5%9E%8B%E8%82%BE%E7%BB%93%E7%9F%B3%23) `91.3K 🔥`
1. [樊长玉取关言正 (Fan Changyu takes Guan Yanzheng)](https://s.weibo.com/weibo?q=%23%E6%A8%8A%E9%95%BF%E7%8E%89%E5%8F%96%E5%85%B3%E8%A8%80%E6%AD%A3%23) `90.0K 🔥`
1. [肾病恶化身体会发3次信号 (When kidney disease worsens, the body will send signals three times)](https://s.weibo.com/weibo?q=%23%E8%82%BE%E7%97%85%E6%81%B6%E5%8C%96%E8%BA%AB%E4%BD%93%E4%BC%9A%E5%8F%913%E6%AC%A1%E4%BF%A1%E5%8F%B7%23) `89.4K 🔥`
1. [伊朗的策略越来越清晰 (Iran's strategy becomes increasingly clear)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E7%9A%84%E7%AD%96%E7%95%A5%E8%B6%8A%E6%9D%A5%E8%B6%8A%E6%B8%85%E6%99%B0%23) `88.1K 🔥`
1. [20岁小伙泡沫尿1年多不重视致透析 (A 20-year-old boy had foamy urine and neglected it for more than a year, causing dialysis)](https://s.weibo.com/weibo?q=%2320%E5%B2%81%E5%B0%8F%E4%BC%99%E6%B3%A1%E6%B2%AB%E5%B0%BF1%E5%B9%B4%E5%A4%9A%E4%B8%8D%E9%87%8D%E8%A7%86%E8%87%B4%E9%80%8F%E6%9E%90%23) `81.6K 🔥`
1. [强吻亦是吻 (A forced kiss is also a kiss)](https://s.weibo.com/weibo?q=%23%E5%BC%BA%E5%90%BB%E4%BA%A6%E6%98%AF%E5%90%BB%23) `78.3K 🔥`
1. [李雪琴的网恋对象是师兄 (Li Xueqin’s online dating partner is her senior brother)](https://s.weibo.com/weibo?q=%23%E6%9D%8E%E9%9B%AA%E7%90%B4%E7%9A%84%E7%BD%91%E6%81%8B%E5%AF%B9%E8%B1%A1%E6%98%AF%E5%B8%88%E5%85%84%23) `76.5K 🔥`
1. [伊朗向以发射多型号导弹](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E5%90%91%E4%BB%A5%E5%8F%91%E5%B0%84%E5%A4%9A%E5%9E%8B%E5%8F%B7%E5%AF%BC%E5%BC%B9%23) `74.4K 🔥`
1. [鹿晗专辑预告](https://s.weibo.com/weibo?q=%23%E9%B9%BF%E6%99%97%E4%B8%93%E8%BE%91%E9%A2%84%E5%91%8A%23) `68.3K 🔥`
1. [白鹿把孩子塞到王鹤棣怀里 (Bai Lu stuffed the child into Wang Hedi's arms)](https://s.weibo.com/weibo?q=%23%E7%99%BD%E9%B9%BF%E6%8A%8A%E5%AD%A9%E5%AD%90%E5%A1%9E%E5%88%B0%E7%8E%8B%E9%B9%A4%E6%A3%A3%E6%80%80%E9%87%8C%23) `65.4K 🔥`
1. [中方回应是否有中国民用商船遭袭 (China responds to whether any Chinese civilian merchant ships were attacked)](https://s.weibo.com/weibo?q=%23%E4%B8%AD%E6%96%B9%E5%9B%9E%E5%BA%94%E6%98%AF%E5%90%A6%E6%9C%89%E4%B8%AD%E5%9B%BD%E6%B0%91%E7%94%A8%E5%95%86%E8%88%B9%E9%81%AD%E8%A2%AD%23) `60.4K 🔥`
1. [伊朗最高领袖要求地区美军基地关闭 (Iran's supreme leader calls for regional US military bases to close)](https://s.weibo.com/weibo?q=%23%E4%BC%8A%E6%9C%97%E6%9C%80%E9%AB%98%E9%A2%86%E8%A2%96%E8%A6%81%E6%B1%82%E5%9C%B0%E5%8C%BA%E7%BE%8E%E5%86%9B%E5%9F%BA%E5%9C%B0%E5%85%B3%E9%97%AD%23) `57.1K 🔥`
1. [王楚钦回应出现失误](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E6%A5%9A%E9%92%A6%E5%9B%9E%E5%BA%94%E5%87%BA%E7%8E%B0%E5%A4%B1%E8%AF%AF%23) `54.5K 🔥`
1. [乃万演唱会取消 (Naiwan concert canceled)](https://s.weibo.com/weibo?q=%23%E4%B9%83%E4%B8%87%E6%BC%94%E5%94%B1%E4%BC%9A%E5%8F%96%E6%B6%88%23) `52.2K 🔥`
1. [天塌了山姆的三文鱼原来不能生吃 (The sky is falling. It turns out Sam’s salmon can’t be eaten raw.)](https://s.weibo.com/weibo?q=%23%E5%A4%A9%E5%A1%8C%E4%BA%86%E5%B1%B1%E5%A7%86%E7%9A%84%E4%B8%89%E6%96%87%E9%B1%BC%E5%8E%9F%E6%9D%A5%E4%B8%8D%E8%83%BD%E7%94%9F%E5%90%83%23) `52.2K 🔥`
1. [病人被困核磁机一夜被保洁救下 (Patient trapped in MRI machine overnight was rescued by cleaning staff)](https://s.weibo.com/weibo?q=%23%E7%97%85%E4%BA%BA%E8%A2%AB%E5%9B%B0%E6%A0%B8%E7%A3%81%E6%9C%BA%E4%B8%80%E5%A4%9C%E8%A2%AB%E4%BF%9D%E6%B4%81%E6%95%91%E4%B8%8B%23) `52.1K 🔥`
1. [王一博入围巴黎时装周名人声量 (Wang Yibo is shortlisted for Paris Fashion Week celebrity status)](https://s.weibo.com/weibo?q=%23%E7%8E%8B%E4%B8%80%E5%8D%9A%E5%85%A5%E5%9B%B4%E5%B7%B4%E9%BB%8E%E6%97%B6%E8%A3%85%E5%91%A8%E5%90%8D%E4%BA%BA%E5%A3%B0%E9%87%8F%23) `52.1K 🔥`
1. [逐玉 (Zhuyu)](https://s.weibo.com/weibo?q=%23%E9%80%90%E7%8E%89%23) `52.1K 🔥`
1. [美军福特号航母发生火灾](https://s.weibo.com/weibo?q=%23%E7%BE%8E%E5%86%9B%E7%A6%8F%E7%89%B9%E5%8F%B7%E8%88%AA%E6%AF%8D%E5%8F%91%E7%94%9F%E7%81%AB%E7%81%BE%23) `100.2K 🔥` `-25%`
1. [陈赫录综艺全身紫外线过敏](https://s.weibo.com/weibo?q=%23%E9%99%88%E8%B5%AB%E5%BD%95%E7%BB%BC%E8%89%BA%E5%85%A8%E8%BA%AB%E7%B4%AB%E5%A4%96%E7%BA%BF%E8%BF%87%E6%95%8F%23) `52.2K 🔥` `-82%`
1. [代表教你用生姜白糖绿茶治肠胃病](https://s.weibo.com/weibo?q=%23%E4%BB%A3%E8%A1%A8%E6%95%99%E4%BD%A0%E7%94%A8%E7%94%9F%E5%A7%9C%E7%99%BD%E7%B3%96%E7%BB%BF%E8%8C%B6%E6%B2%BB%E8%82%A0%E8%83%83%E7%97%85%23) `52.2K 🔥` `-22%`

Updated at 2026-03-13 08:01:27

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
