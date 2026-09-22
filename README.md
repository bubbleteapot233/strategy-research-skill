# strategy-research

战略研究材料写作规范 —— 覆盖两类交付场景的完整 skill。

## 这个 skill 解决什么问题

做研究材料时，最常见的两个坑：

1. **写研究报告时用了 PPT 思维** —— 全是 bullet point，没有论述展开，深度不够
2. **做汇报 PPT 时用了报告思维** —— 大段文字堆在幻灯片上，没人看得进去

这个 skill 把两种场景拆开，各自有独立的写作原则、流程和自检清单，不会混用。

## 两类场景

| 场景 | 交付物 | 写作风格 |
|---|---|---|
| **研究材料** | 调研报告、深度分析、行业研究 | 段落论述体：完整论证、引用丰富 |
| **汇报 PPT** | 演示文稿、演讲稿、汇报幻灯片 | Bullet point 体：≤7 条/页、精炼 |

## 仓库结构

```
├── SKILL.md                          # 主 skill 文件（完整规范）
├── README.md                         # 本文件
├── templates/                        # 4 类调研模板
│   ├── enterprise-research.md        # 企业调研（6 章节）
│   ├── regional-research.md          # 区域市场调研（8 章节）
│   ├── track-research.md             # 赛道调研（6 章节）
│   └── topic-research.md             # 议题调研（4 章节）
└── references/
    ├── quick-reference.md            # 快速参考卡（原则 + 铁律 + 自检）
    └── source-rating-guide.md        # 信源 A/B/C 评级指南
```

## 怎么用

### 作为 QoderWork skill 安装

把整个仓库下载后，将 `SKILL.md` 放到 `~/.qoderwork/skills/strategy-research/` 目录下即可。`templates/` 和 `references/` 作为配套参考材料，skill 执行时按需读取。

### 直接使用

不装 skill 也能用 —— `SKILL.md` 本身是完整的写作规范文档，`templates/` 可以直接拿来填空，`references/` 是速查工具。

## 触发词

| 关键词 | 走哪个流程 |
|---|---|
| 调研 / 分析 / 研究 / 写一份 / 做个分析 | 研究材料 SOP（段落论述体）|
| 帮我看看 XX 市场 / 帮我了解下 XX 公司 | 研究材料 SOP（段落论述体）|
| 汇报材料 / 汇报 PPT / 战略汇报 | 汇报 PPT 流程（bullet point 体）|
| 帮我做个 PPT / 汇报分享 | 汇报 PPT 流程（bullet point 体）|

## 核心设计

- **场景分流**：研究材料 vs 汇报 PPT，写作风格完全不同，不混用
- **6 阶段 22 步 SOP**：从调研启动到复盘，全流程覆盖
- **2 个铁律**：目标对齐（不可跳过阶段 1）+ 可视化必须有文字总结
- **4 类调研模板**：企业 / 区域市场 / 赛道 / 议题，拿来就能用
- **信源 A/B/C 三级**：明确什么来源能用、什么要交叉验证

## License

MIT


## 方法论 Skills

除主 `strategy-research` Skill 外，本仓库开始沉淀可复用的战略分析方法论 Skill：

| Skill | 用途 |
|---|---|
| [influence-factor-analysis](./skills/influence-factor-analysis/SKILL.md) | 影响因素筛选、评分模型、组合分析、弱因素淘汰、异常样本解释；适用于市场进入、区域选择、合作方筛选、产品组合、项目优先级与风险预警 |

后续新增方法论优先放在 `skills/<skill-name>/` 下，每个 Skill 独立维护 `SKILL.md`，并可附带 `templates/` 与 `references/`。
