# Awesome Digital Employees · 中文数字员工资产库

> 面向中国小微企业与 **OPC（一人公司）** 的开源数字员工生态  
> 资产形态：**纯提示词客户端资产** —— 零 API Key、零部署、零运行时依赖，粘贴到任意 AI 工具即可使用

| 数字员工 | 原子技能 | 场景工作流 | 覆盖行业/客群 | 更新 |
|---|---|---|---|---|
| **30** | 160 | 140 | 4 大客群 | 2026-09-29 |

---

## 这是什么

每个数字员工是一个**独立可用的资产包**，交付「一个岗位的全套 AI 工作能力」：

```
DigitalEmployee 数字员工（资产包）
  └─ ScenarioWorkflow 场景工作流（DAG 编排）
        └─ BusinessSkill 原子技能（提示词四件套）
```

**为什么不用 API Key？** 数字员工不是程序，是**提示词资产**。你在自己已订阅的 AI 工具里运行它，
不需要为资产再付一次算力钱，资产方也不产生任何服务端成本。

| 特性 | 说明 |
|---|---|
| 无需 API Key | 一个 Key 都不需要 |
| 无需部署 | 没有服务端，没有脚本 |
| 平台无关 | Coze / WorkBuddy / Dify / Claude / ChatGPT 均可 |
| 用户自备算力 | 模型来自你自己的订阅 |

### 单个数字员工怎么用

```text
1. 打开某个技能目录，例如 skills/hot-topic-radar/prompt.txt
2. 全文复制
3. 粘贴到你常用的 AI 工具
4. 按 SKILL.md 的输入规格提供数据
```

---

## 交付状态

- ✅ **P0 首发 13 个数字员工已完整交付**（2,626 文件 / 73 技能 / 61 工作流 / 1,340 份资产级文档 / 1,675 项资产校验全通过）
- ⏳ P1 二期 12 个、P2 后期 5 个（交付标准与 P0 一致，生成器 `--stage` 一键切换）

### P0 首发（13 个） · 已交付

| 仓库 | 数字员工 | 客群 | 技能 | 工作流 | 旧名存档 |
|------|----------|------|-----:|-------:|----------|
| [`coldstart-growth-zh`](https://github.com/bangwozuo/coldstart-growth-zh) | 出海增长官 | OPC | 7 | 5 | 出海冷启动获客官（Build-in-Public 内容引擎） |
| [`launch-commander-zh`](https://github.com/bangwozuo/launch-commander-zh) | 发布指挥官 | OPC | 9 | 5 | 发布日冲刺指挥官（PH Launch Commander） |
| [`topic-planner-zh`](https://github.com/bangwozuo/topic-planner-zh) | 选题策划师 | 自媒体创作者 | 6 | 4 | 爆款选题策划师 |
| [`script-writer-zh`](https://github.com/bangwozuo/script-writer-zh) | 脚本创作师 | 自媒体创作者 | 6 | 4 | 短视频脚本创作师 |
| [`engagement-ops-zh`](https://github.com/bangwozuo/engagement-ops-zh) | 评论运营官 | 自媒体创作者 | 6 | 4 | 评论区运营官 |
| [`product-visual-zh`](https://github.com/bangwozuo/product-visual-zh) | 商品视觉师 | 电商小卖家 | 6 | 5 | 视觉设计师·小图 |
| [`shop-support-zh`](https://github.com/bangwozuo/shop-support-zh) | 店铺客服官 | 电商小卖家 | 6 | 5 | 客服专员·小服 |
| [`review-manager-zh`](https://github.com/bangwozuo/review-manager-zh) | 评价运营官 | 电商小卖家 | 5 | 5 | 评价运营专员·小评 |
| [`listing-copy-zh`](https://github.com/bangwozuo/listing-copy-zh) | Listing 文案师 | 电商小卖家 | 5 | 5 | 上架文案专员·小文 |
| [`local-content-zh`](https://github.com/bangwozuo/local-content-zh) | 探店编导 | 本地生活商家 | 5 | 5 | 探店短视频编导 |
| [`review-firefighter-zh`](https://github.com/bangwozuo/review-firefighter-zh) | 口碑捍卫者 | 本地生活商家 | 4 | 5 | 差评灭火官 |
| [`local-retention-zh`](https://github.com/bangwozuo/local-retention-zh) | 复购管家 | 本地生活商家 | 5 | 5 | 私域复购管家 |
| [`daily-report-zh`](https://github.com/bangwozuo/daily-report-zh) | 经营日报员 | 本地生活商家 | 3 | 4 | 门店经营日报分析师 |

### P1 二期（12 个） · 规划中

| 仓库 | 数字员工 | 客群 | 技能 | 工作流 | 旧名存档 |
|------|----------|------|-----:|-------:|----------|
| [`seo-matrix-zh`](https://github.com/bangwozuo/seo-matrix-zh) | SEO 架构师 | OPC | 7 | 6 | SEO 内容矩阵助理（独立站增长助理） |
| [`feedback-hub-zh`](https://github.com/bangwozuo/feedback-hub-zh) | 反馈分析师 | OPC | 6 | 5 | 用户反馈聚合分析师 |
| [`multi-publish-zh`](https://github.com/bangwozuo/multi-publish-zh) | 分发中控 | OPC | 6 | 5 | 多平台发布与数据回捞助理 |
| [`funnel-builder-zh`](https://github.com/bangwozuo/funnel-builder-zh) | 引流转化师 | 自媒体创作者 | 6 | 4 | 私域引流转化师 |
| [`cross-post-zh`](https://github.com/bangwozuo/cross-post-zh) | 分发改写师 | 自媒体创作者 | 6 | 4 | 多平台分发改写师 |
| [`data-recap-zh`](https://github.com/bangwozuo/data-recap-zh) | 数据复盘师 | 自媒体创作者 | 6 | 4 | 跨平台数据复盘师 |
| [`multi-shop-ops-zh`](https://github.com/bangwozuo/multi-shop-ops-zh) | 多店运营官 | 电商小卖家 | 5 | 5 | 多平台运营助理·小铺 |
| [`shop-video-zh`](https://github.com/bangwozuo/shop-video-zh) | 店铺编导 | 电商小卖家 | 5 | 5 | 内容编导·小导 |
| [`product-research-zh`](https://github.com/bangwozuo/product-research-zh) | 选品分析师 | 电商小卖家 | 5 | 5 | 选品分析师·小察 |
| [`groupbuy-designer-zh`](https://github.com/bangwozuo/groupbuy-designer-zh) | 团购设计师 | 本地生活商家 | 4 | 5 | 团购引流设计师 |
| [`appointment-scheduler-zh`](https://github.com/bangwozuo/appointment-scheduler-zh) | 排班调度师 | 本地生活商家 | 4 | 5 | 预约排班调度员 |
| [`member-reactivation-zh`](https://github.com/bangwozuo/member-reactivation-zh) | 会员唤醒师 | 本地生活商家 | 4 | 5 | 会员唤醒师 |

### P2 后期（5 个） · 规划中

| 仓库 | 数字员工 | 客群 | 技能 | 工作流 | 旧名存档 |
|------|----------|------|-----:|-------:|----------|
| [`lite-support-zh`](https://github.com/bangwozuo/lite-support-zh) | 客服值守员 | OPC | 5 | 4 | 轻量客服与 FAQ 数字员工 |
| [`tax-guard-zh`](https://github.com/bangwozuo/tax-guard-zh) | 合规哨兵 | OPC | 6 | 4 | 财税合规助理 |
| [`brand-deal-zh`](https://github.com/bangwozuo/brand-deal-zh) | 商单管家 | 自媒体创作者 | 4 | 4 | 商单对接管家 |
| [`shop-retention-zh`](https://github.com/bangwozuo/shop-retention-zh) | 复购运营官 | 电商小卖家 | 5 | 5 | 私域运营专员·小复 |
| [`local-ops-hub-zh`](https://github.com/bangwozuo/local-ops-hub-zh) | 本地运营中台 | 本地生活商家 | 3 | 4 | 多平台运营中台 |

---

## 按客群索引

### OPC（7 个）

| 数字员工 | 阶段 | 技能 | 工作流 |
|----------|------|-----:|-------:|
| 发布指挥官 | P0 | 9 | 5 |
| 出海增长官 | P0 | 7 | 5 |
| SEO 架构师 | P1 | 7 | 6 |
| 反馈分析师 | P1 | 6 | 5 |
| 分发中控 | P1 | 6 | 5 |
| 合规哨兵 | P2 | 6 | 4 |
| 客服值守员 | P2 | 5 | 4 |

### 自媒体创作者（7 个）

| 数字员工 | 阶段 | 技能 | 工作流 |
|----------|------|-----:|-------:|
| 选题策划师 | P0 | 6 | 4 |
| 脚本创作师 | P0 | 6 | 4 |
| 评论运营官 | P0 | 6 | 4 |
| 引流转化师 | P1 | 6 | 4 |
| 分发改写师 | P1 | 6 | 4 |
| 数据复盘师 | P1 | 6 | 4 |
| 商单管家 | P2 | 4 | 4 |

### 电商小卖家（8 个）

| 数字员工 | 阶段 | 技能 | 工作流 |
|----------|------|-----:|-------:|
| 商品视觉师 | P0 | 6 | 5 |
| 店铺客服官 | P0 | 6 | 5 |
| 评价运营官 | P0 | 5 | 5 |
| Listing 文案师 | P0 | 5 | 5 |
| 多店运营官 | P1 | 5 | 5 |
| 店铺编导 | P1 | 5 | 5 |
| 选品分析师 | P1 | 5 | 5 |
| 复购运营官 | P2 | 5 | 5 |

### 本地生活商家（8 个）

| 数字员工 | 阶段 | 技能 | 工作流 |
|----------|------|-----:|-------:|
| 探店编导 | P0 | 5 | 5 |
| 复购管家 | P0 | 5 | 5 |
| 口碑捍卫者 | P0 | 4 | 5 |
| 经营日报员 | P0 | 3 | 4 |
| 团购设计师 | P1 | 4 | 5 |
| 排班调度师 | P1 | 4 | 5 |
| 会员唤醒师 | P1 | 4 | 5 |
| 本地运营中台 | P2 | 3 | 4 |

---

## 资产结构与规范

每个数字员工仓遵循统一结构：

```text
{repo}/
  README.md employee.md package.yaml    # 入口与定义卡
  docs/01~07                            # 员工级文档（架构/流程/场景/手册/示例/录像/测试）
  skills/<slug>/                        # ① 原子技能（type: atomic）
    README.md SKILL.md prompt.txt schema.json examples/
    docs/01~09 + assets/overview.svg     #  该技能自己的 10 项文档 + 配图
  workflows/<slug>/                     # ② 工作流（复合技能，type: composite）
    README.md SKILL.md prompt.txt schema.json examples/
    docs/01~09 + assets/overview.svg     #  该工作流自己的 10 项文档 + 配图
  knowledge/                            # RAG wiki（index + template + entries + 接入指南）
  connectors/                           # 索引 + 逐连接器说明 + COMPLIANCE.md 合规红线
  quality/                              # 效果基线与追踪日志
  tests/ pytest.ini                     # 资产校验测试
  .github/workflows/validate.yml        # CI 门禁
```

> **工作流 = 复合技能**：规范与原子技能完全一致（同一套四件套 + 同一套文档），
> 物理上原子技能放 `skills/`、工作流放 `workflows/`，靠 `type: atomic | composite` 区分。

---

## 合规

- 连接器只走两条合规路径：**官方 API**、**用户自行导出的数据**
- 禁止爬取私密数据 / 刷量 / 协议机器人
- 每个技能提示词内置「合规」区块；输出为 AI 辅助内容，**交付前必须人工审核**

---

## 许可

Apache-2.0。

*本索引由 `library/` 数据自动同步；更新请改章节稿后重跑构建器。*