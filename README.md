# 休食商家经营 Showcase

## 项目说明

小红书电商 · 店播标杆案例对外宣传页，面向商家展示「月上新」打法的实战复盘。

所有数据已脱敏处理（量级区间 + 分档表达），可直接用于对外传播。

## 在线访问

| 案例 | GitHub Pages | CDN |
|------|-------------|-----|
| 札x旗舰店 · 7月中场 | [onepage-case1.html](https://devilfivoy.github.io/xiushi-merchant-showcase/onepage-case1.html) | [CDN](https://picasso-private-1251524319.cos.ap-shanghai.myqcloud.com/formula-static/dibp/w54izo2v/onepage-case1.html) |
| 内蒙xx的店 · 8月大场 | [onepage-case2.html](https://devilfivoy.github.io/xiushi-merchant-showcase/onepage-case2.html) | [CDN](https://picasso-private-1251524319.cos.ap-shanghai.myqcloud.com/formula-static/dibp/o3fysvkn/onepage-case2.html) |

## 案例概要

### 案例一：札x旗舰店 · 7月中场
- **主题：** 用新品做预约钩子，单品聚焦打出 10 倍日播的中场爆发力
- **核心数据：** 单场 DGMV 40万+（10x 日播）、转化率超 30%、新品占 GMV 近 60%
- **三个关键动作：**
  1. 用新品做「预约钩子」，把月上新变成一次小蓄水
  2. 货盘做减法，用「单品击穿」替代「多品类铺货」
  3. 老粉池做底盘，预约是最高效的筛子
- **优化建议：** 非粉「买了没关注」是最大隐性漏损，建议话术中加入关注引导

### 案例二：内蒙xx的店 · 8月大场
- **主题：** 「猪爆脆」驱动的店播「上新日」打法，单场 GMV 40万+，日播的 20 倍
- **核心数据：** 单场 DGMV 40万+（20x 日播）、自然流量超 99%、成交客单 140元+
- **三个关键动作：**
  1. 新品就是整场的理由，整场直播定义成一次产品发布
  2. 全家桶把单品爆款翻译成组合客单
  3. 13 天 70+ 篇长周期蓄水，换来 99%+ 自然流量

## 设计特点

- **风格：** PPT slide 风格（白底 + 小红书红 `#E60033` 主色）
- **自适应：** 桌面（1280px）/ 平板（≤960px）/ 手机（≤520px）三档
- **数据可视化：** KPI 数据条 + 渐变进度条
- **结构：** 顶部标识栏 → 主标题 → 商家信息 → KPI → 亮点优势 → 关键动作 → 优化建议/公式总结 → 行业可复制 → 底部

## 脱敏口径

| 维度 | 处理方式 | 示例 |
|------|---------|------|
| GMV 金额 | 量级区间 | 46.93万 → 40万+ |
| 转化率/占比 | 分档表达 | 34.1% → 超30% |
| 商家名称 | 部分脱敏 | 札萨 → 札x旗舰店 |
| 绝对值（人数） | 不展示，仅保留占比/倍数 | 2,877预约 → 不展示 |

## 技术栈

- 纯 HTML + CSS，无外部依赖
- 响应式 media query（960px / 520px 断点）
- 托管：GitHub Pages + 腾讯云 COS CDN

## 制作流程

详见 [SKILL.md](./SKILL.md)

## 文件结构

```
case-onepage-shop-broadcast/
├── SKILL.md              # Skill 使用说明（供 AI 复用）
├── README.md             # 本文件（项目介绍）
├── onepage-case1.html    # 案例一：札x旗舰店
├── onepage-case2.html    # 案例二：内蒙xx的店
├── case_data.json        # 原始数据配置（已弃用，数据直接写入 HTML）
├── onepage.html          # 早期版本（已弃用）
└── poster.html           # 早期海报版本（已弃用）
```

## 更新记录

| 日期 | 变更 |
|------|------|
| 2026-08-03 | 首次创建，两个案例 onepage |
| 2026-08-03 | 加入三档自适应（桌面/平板/手机） |
| 2026-08-03 | 加顶部标识栏「小红书电商 · 店播标杆案例」 |
| 2026-08-04 | 整理 SKILL.md + README.md，上传 GitHub |
