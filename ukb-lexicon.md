# UKB 队列论文高频术语、搭配与句式（用词来源基准）

本表收录 UK Biobank 队列研究（加速度计身体活动、dMRI 结构连接、抑郁症方向）已发表论文中反复出现的高频表达。写作/翻译时优先使用本表词汇与句式；表中未收录的表达，须检索已发表 UKB 论文核实后再使用，不杜撰。

## 1. 研究设计与人群（Study design and population）

| 中文 | 英文（UKB 文献用法） |
|---|---|
| 前瞻性队列研究 | a prospective cohort study |
| UK 生物样本库 | UK Biobank (UKB) |
| 符合条件的参与者 | eligible participants |
| 排除后 | after exclusions |
| 基线特征 | baseline characteristics |
| 随访 | follow-up / were followed up |
| 中位随访 | median follow-up of X years |
| 加速度计数据有效 | valid accelerometry data |
| 完成结构磁共振成像 | with structural MRI data available |
| 入组时 | at baseline / at recruitment |
| 排除标准 | exclusion criteria |

## 2. 暴露：加速度计身体活动（Accelerometer-derived physical activity）

| 中文 | 英文（UKB 文献用法） |
|---|---|
| 身体活动 | physical activity (PA) |
| 加速度计测量的身体活动 | accelerometer-derived physical activity |
| 佩戴时间 | wear time |
| 有效佩戴天数 | valid wear days |
| 非佩戴时间 | non-wear time |
| 平均加速度 | average acceleration |
| 总身体活动 | total physical activity |
| 中高强度身体活动 | moderate-to-vigorous physical activity (MVPA) |
| 低强度身体活动 | light physical activity (LPA) |
| 久坐行为 | sedentary behaviour (SB) |
| 活动强度梯度 | intensity gradient |
| 单位强度 | per 1-SD increase / per 1-SD |
| 每天/每周时长 | minutes per day / min/week |

## 3. 影像与结构连接（Neuroimaging and structural connectivity）

| 中文 | 英文（UKB 文献用法） |
|---|---|
| 结构连接 | structural connectivity (SC) |
| 弥散加权成像 | diffusion-weighted imaging (DWI) |
| 各向异性分数 | fractional anisotropy (FA) |
| 平均弥散率 | mean diffusivity (MD) |
| 概率性纤维追踪 | probabilistic tractography |
| 纤维追踪 | tractography |
| 脑区划分图谱 | parcellation / brain atlas |
| Brainnetome 图谱 | Brainnetome Atlas |
| 节点/边 | node / edge |
| 连接强度 | connectivity strength / streamline count |
| 全脑/全局效率 | global efficiency |
| 局部效率 | local efficiency |
| 网络属性 | network metrics / graph metrics |
| 白质纤维束 | white matter tracts |

## 4. 结局：抑郁症（Depression outcome）

| 中文 | 英文（UKB 文献用法） |
|---|---|
| 重度抑郁障碍 | major depressive disorder (MDD) |
| 抑郁症状 | depressive symptoms |
| 抑郁症状评分 | depressive symptom score |
| 新发/发病 | incident |
| 已患 | prevalent |
| 病例对照 | case-control |
| 诊断编码 | diagnostic codes (ICD-10) |
| 自报抑郁 | self-reported depression |

## 5. 统计（Statistics）

| 中文 | 英文（UKB 文献用法） |
|---|---|
| 限制性立方样条 | restricted cubic splines (RCS) |
| Cox 比例风险模型 | Cox proportional hazards model |
| 风险比 | hazard ratio (HR) |
| 比值比 | odds ratio (OR) |
| 回归系数 | beta coefficient (β) |
| 95% 置信区间 | 95% confidence interval (CI) |
| 错误发现率 | false discovery rate (FDR) |
| Benjamini-Hochberg 校正 | Benjamini–Hochberg (BH) correction |
| 多因素校正 | multivariable-adjusted / multivariable adjustment |
| 协变量 | covariates |
| 混杂因素 | confounders |
| 敏感性分析 | sensitivity analysis |
| 分层分析 | stratified analysis |
| 多重比较校正 | correction for multiple testing |
| 事后检验 | post hoc test |
| 标准差 | standard deviation (SD) |
| 标准误 | standard error of the mean (SEM) |

## 6. 高频句式模板（UKB 文献典型写法）

**人群描述**
- Of the N participants, X were included in the analysis.
- Participants with complete accelerometry data and available structural MRI were included.
- After excluding participants with X, N participants remained.
- The analytic sample comprised N participants (mean age, X years; X% female).

**随访与结局**
- Participants were followed up for a median of X years (interquartile range, X–X).
- During follow-up, X participants developed incident MDD.

**关联报告（结果段）**
- Higher total physical activity was associated with lower risk of MDD (HR per 1-SD increase, 0.XX; 95% CI, X.XX–X.XX).
- The association remained after adjustment for demographic and lifestyle covariates.
- No significant association was observed for X (HR per 1-SD increase, X.XX; 95% CI, X.XX–X.XX).
- A nonlinear association was indicated by restricted cubic spline analysis (P for nonlinearity = X.XXX).
- The association was attenuated but remained significant after adjustment for X.

**影像-行为关联**
- Higher X was associated with greater structural connectivity in the X network (β = X.XX; 95% CI, X.XX–X.XX; P_FDR = X.XX×10⁻³).
- The associations were specific to X, not Y.

**讨论措辞（克制不夸大）**
- These findings suggest that X may be associated with Y.
- The observational nature of this study precludes causal inference.
- Future studies are needed to clarify the underlying mechanisms.

## 7. 使用规则

- 数值与统计量的表达格式保持 UKB 文献惯例（如 "HR per 1-SD, 0.87; 95% CI, 0.82–0.93"），不改写。
- 缩写定义规则见 SKILL.md 第三节第 5 条：首现全称 + 括号缩写，之后只用缩写。
- 未收录表达先检索核实（如 PubMed 检索 "UK Biobank" + 主题词），确认出现在 UKB 队列论文后再用。
