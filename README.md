# 上海外服 · 业务需求发现报告（合成演练）

案例：**招聘需求澄清与面试协同**——基于 fde-simulation 的 workflow-decomposition / outcome-risk-matrix / 4-source-convergence 三框架归纳，需求为待验证假设。

> ⚠️ 公开来源仅支持企业名称与业务方向，访谈事实（顾明岚 / 林亦舟 / 唐映秋 / 秦芮 / 傅景 / 叶书 等角色）为合成创作，**不代表任何企业真实经营数据**。

## 仓库内容

| 文件 | 说明 |
|---|---|
| `discovery-requirements.csv` | 需求假设表（表头：需求假设 / 优先级 / 负责人 / 状态 / 验收与约束 / 证据编号 / 事实内容） |
| `discovery-report.md` | 业务需求发现报告（人读版，83 行） |
| `discovery-report.json` | 同份报告的 JSON 结构（程序读版） |

## 当前覆盖

- 角色 × 维度：6 × 6 = 36 条应采集事实
- 已覆盖：0 / 36（0%）—— `discovery-report.json` 的 `coverage.found = 0`
- 报告内容：初始诉求、建议追问、按角色的证据缺口清单、公开业务来源、方法来源

## 方法来源

[fde-simulation](https://github.com/kalyvask/fde-simulation) · 三个框架：
- **workflow-decomposition**（流程分解）
- **outcome-risk-matrix**（收益风险矩阵）
- **4-source-convergence**（四源验证：Buyer / Brief / Industry / Operator）

## 公开来源（仅支撑企业方向）

- [上海外服 · 公司概况与五类主营业务](https://www.fsg.com.cn/AboutUs_Profile.html)
- [上海外服 · 数字化服务介绍](https://www.fsg.com.cn/AboutUs_Profile_Digitization.html)
- [上海外服 · 业务外包服务](https://www.fsg.com.cn/Product_BPO.html)
- [上海外服 · 零售终端外包服务](https://www.fsg.com.cn/Product_BPO_Retail.html)

## 用途

作为业务发现与最小集方法论的样例素材，配合 [`brief-query-demo`](https://github.com/LEO-CNS/brief-query-demo) 看实测效果。
