# 技能索引（Skills Index）

## 38 个法律推理技能完整清单

### 第一类：信息检索（5 个技能）

| 编号 | 技能名称 | 英文名 | 描述 |
|------|----------|---------|-------|
| 09 | 案例检索 | case-retrieval | 查找与法律问题相关的类似案例和判决 |
| 11 | 法条检索 | legal-article-retrieval | 检索现行有效的法律规范和司法解释 |
| 10 | 法律规范效力检查 | legal-norm-validity-check | 验证法条的现行有效性和层级 |
| 05 | 其他法律信息检索 | other-legal-retrieval | 检索立法背景、监管案例、地方规定等辅助信息 |
| 14 | 法律术语解析 | legal-terminology | 查阅和解析法律专业术语 |

### 第二类：事实与要素处理（4 个技能）

| 编号 | 技能名称 | 英文名 | 描述 |
|------|----------|---------|-------|
| 13 | 法律核心要素提取 | legal-element-extraction | 从非结构化叙述中提取法律相关事实 |
| 07 | 结构化要素清单 | structured-element-extraction | 将法律问题分解为完整的要素清单 |
| 02 | 争议焦点识别 | dispute-issue-identification | 识别案件中的事实争议和法律争议 |
| 12 | 证��效力评估 | evidence-evaluation | 评估证据的真实性、合法性、关联性 |

### 第三类：法律解释（4 个技能）

| 编号 | 技能名称 | 英文名 | 描述 |
|------|----------|---------|-------|
| 15 | 法律解释与论证 | legal-interpretation-argument | 运用解释方法对法条进行论证 |
| 16 | 体系解释 | systematic-interpretation | 从法律体系关系进行解释 |
| 17 | 目的解释 | teleological-interpretation | 从规范目的进行解释 |
| 18 | 规范含义论证 | normative-meaning-argumentation | 对法律规范含义进行深入论证 |

### 第四类：法律推理（7 个技能）

| 编号 | 技能名称 | 英文名 | 描述 |
|------|----------|---------|-------|
| 19 | 演绎推理 | deductive-reasoning | 运用三段论进行法律推理 |
| 20 | 归纳推理 | inductive-reasoning | 从个案推导一般法律规则 |
| 21 | 类比推理 | analogical-reasoning | 运用案例类比进行推理 |
| 22 | 反事实推理 | counterfactual-reasoning | 进行反事实分析 |
| 23 | 法律绎论推理 | legal-abductive-reasoning | 进行法律假设推理 |
| 24 | 演绎法律推理系统 | deductive-reasoning | [复合能力] 综合演绎多步推理 |
| 25 | 形式法律后果 | formal-legal-consequence | 推导法律规范的形式后果 |

### 第五类：论证组织与评估（4 个技能）

| 编号 | 技能名称 | 英文名 | 描述 |
|------|----------|---------|-------|
| 26 | 论证链条构建 | argument-chain-construction | 组织多层级的法律论证链条 |
| 27 | 论证强度评估 | argument-strength-evaluation | 评估法律论证的说服力 |
| 28 | 证据论证链 | evidence-argument-chain | 将证据组织为完整的论证链 |
| 03 | 冲突解决与协调 | conflict-resolution | 协调相互矛盾的法律规范或论点 |

### 第六类：风险评估与价值判断（6 个技能）

| 编号 | 技能名称 | 英文名 | 描述 |
|------|----------|---------|-------|
| 29 | 纠纷与履行风险 | dispute-and-performance-risk | 识别合同中的风险因素 |
| 30 | 内部合规风险识别 | internal-compliance-risk-identification | 识别企业内部合规风险 |
| 31 | 法律风险评估 | legal-risk-assessment | 系统性评估法律风险 |
| 32 | 战略风险优先级 | strategic-risk-prioritization | 对风险进行优先级排序 |
| 33 | 司法价值判断 | judicial-value-judgment | 从司法角度进行价值评估 |
| 34 | 行政价值判断 | administrative-value-judgment | 从行政角度进行价值评估 |
| ◆ | 法律判决预测 | legal-judgment-prediction | [复合能力] 预测诉讼结果 |

### 第七类：文书与事务管理（8 个技能）

| 编号 | 技能名称 | 英文名 | 描述 |
|------|----------|---------|-------|
| 35 | 法律文档格式化 | legal-document-formatting | 按标准格式制作法律文书 |
| 36 | 法律文档总结 | legal-document-summarization | 总结和萃取法律文档要点 |
| 37 | 多文档总结 | multi-document-summarization | 综合多份文档进行总结 |
| ◆ | 判决书生成 | judgment-document-generation | [复合能力] 生成结构化判决书 |
| 38 | 案件生命周期规划 | case-lifecycle-planning | 规划案件全程管理 |
| 39 | 诉讼时间表与期限监督 | trial-scheduling-and-deadline-monitoring | 管理诉讼期限和时间节点 |
| 40 | 账单与诉讼预算 | billing-and-litigation-budget | 估算法律成本和诉讼预算 |
| 08 | 法律概念理解 | legal-concept-comprehension | 精准理解法律概念的含义 |

---

**图例**：
- 编号为数字：原子能力
- ◆ 标记：复合能力（调度多个原子能力）
- 所有技能都包含完整的 SKILL.md 文档

## 技能依赖关系

```
信息检索类技能 ──→ 事实与要素处理类技能 ──→ 法律解释类技能
                                    ↓
                             法律推理类技能 ──→ 论证组织类技能
                                    ↓
                             风险评估类技能 ──→ 复合能力
                                              ↓
                                     文书与事务类技能
```

## 快速导航

- **法律研究者**：从信息检索 → 法律解释 → 法律推理
- **律师代理人**：从事实提取 → 论证链构建 → 法律风险评估
- **法官/仲裁员**：从争议焦点识别 → 法律推理 → 判决书生成
- **企业合规**：从内部风险识别 → 战略风险评估 → 文档管理
