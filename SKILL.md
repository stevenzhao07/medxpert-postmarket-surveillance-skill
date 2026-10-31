---
name: medxpert-postmarket-surveillance-skill
description: 医疗器械上市后监督（PMS）与不良事件上报指导。输入产品类型+目标市场，输出PMS计划框架+不良事件上报时限+MDR PMS要求。Use for：上市后监督计划、不良事件上报、MDR PMS、PSUR报告、警戒系统。Do NOT use for：注册申报（用medxpert-reg-path-skill）、风险管理（用medxpert-risk-management-skill）。触发词：PMS、上市后监督、不良事件、AE上报、MDR警戒、PSUR、PMCF。
---

# MedXpert Postmarket Surveillance Skill · 上市后监督

> 拿证不是结束，是开始——MDR下PMS是强制要求，做不好会被吊销证书。

## 这个 Skill 做什么

产品上市之后，不是就完事了。法规要求：
- 持续收集上市后数据
- 不良事件按时限上报
- 定期做PMS报告（PSUR）
- 必要时做PMCF（上市后临床随访）

这个Skill帮你：
- 搭PMS计划框架
- 不良事件上报时限和流程
- 各市场PMS要求差异

---

## 何时使用

### ✅ 合适的场景

- 新产品上市前，搭PMS体系
- 发生不良事件，不知道要不要报、多久内报
- MDR下PSUR/PMCF怎么写

### ❌ 不合适的场景

- 注册申报阶段（用注册Skill）
- 风险管理报告（用风险管理Skill）

---

## 工作流

### Step 1 · 确认市场

- 哪个市场的PMS要求？（中美欧完全不一样）
- 产品分类几级？

### Step 2 · PMS计划框架

按对应市场要求，列出PMS计划应该包含什么：
- 数据收集方法（投诉、文献、监管数据库）
- 数据分析方法
- 报告频率
- 触发再评价的阈值

### Step 3 · 不良事件上报

列出各市场的上报时限：
- 美国FDA：MDR 21 CFR 803，死亡/严重伤害10个工作日
- 欧盟MDR：严重事件15天，死亡/健康恶化10天
- 中国NMPA：死亡7天，严重伤害20天

### Step 4 · 常见踩坑点

提醒用户：PMS最容易踩的坑是什么。

---

## 硬规则

### 🚫 P0级禁令

1. **不许瞒报不良事件**——这是违法的，严重的吊销注册证
2. **上报时限不能错**——不同市场时限不一样，别搞混了
3. **PMS不是写个计划就完事**——要真的做，要留记录
4. **MDR下PMCF是强制的**——Class IIa以上必须做PMCF计划

---

> 🛡️ MedXpert LGD体系：有籍有证有门禁。
