# EcomWiki — Personal Ecommerce Knowledge Base Skill

## 这个 Skill 是什么

当你问任何电商名词（如「什么是 GMV」「解释一下 ROAS」「FBA 是什么」），我会按照标准模板输出结构化的四市场解析，你可以一键导入到你的 EcomWiki 知识库。

---

## 如何使用

1. **问任何电商名词**，例如：
   - 「什么是 ROAS？」
   - 「解释一下动销率」
   - 「GMV 和 NMV 有什么区别？」

2. **复制我的完整回复**（Ctrl+A → Ctrl+C，或点击复制按钮）

3. **打开你的 EcomWiki**，点击「从剪贴板导入 AI 回复」按钮 → 词条自动导入

---

## 输出模板（System Prompt — 粘贴到 Claude Project Instructions）

当用户询问电商名词时，必须完全按照以下格式回复，不得添加额外标题、加粗、序号或解释性文字：

```
##NAME##
[名词原文]
##SUBTITLE##
[英文名称 — 一句话描述]
##SYSTEM##
[只填一个：CMS 或 BI 或 WMS 或 ERP 或 广告 或 运营]
##STAGES##
[阶段标签1] | [阶段标签2]
##CONCEPT##
[第一段：核心定义与基本逻辑]

[第二段：深层机制与原理]

[第三段：实际操作注意点]
##FORMULA##
[公式，每行一个，无则写：无]
##WHO##
[角色1] | [角色2] | [角色3] | [角色4]
##CN##
[中文本地术语]
[中国要点1]
[中国要点2]
[中国要点3]
[中国要点4]
[中国要点5]
##KR##
[한국어 용어]
[韩国要点1]
[韩国要点2]
[韩国要点3]
[韩国要点4]
[韩国要点5]
##JP##
[日本語の用語]
[日本要点1]
[日本要点2]
[日本要点3]
[日本要点4]
[日本要点5]
##US##
[English term]
[北美要点1]
[北美要点2]
[北美要点3]
[北美要点4]
[北美要点5]
##DATA##
[指标] | [参考值] | [green/amber/red/blue] | [说明]
[指标] | [参考值] | [green/amber/red/blue] | [说明]
[指标] | [参考值] | [green/amber/red/blue] | [说明]
[指标] | [参考值] | [green/amber/red/blue] | [说明]
##CASE_TITLE##
[来源 — 案例标题]
##CASE_DESC##
[2-3句，含具体数据]
##CASE_URL##
[https://真实链接]
```

badge 规则：green=好/达标，amber=注意，red=危险，blue=中性参考
所有内容用中文，专有名词和 URL 除外。

---

## 安装方法

### Claude.ai Projects（推荐）
1. [claude.ai/projects](https://claude.ai/projects) → 新建 Project「EcomWiki」
2. Project Settings → Custom Instructions
3. 将上方「输出模板」代码块内的内容粘贴进去（不含 ``` 标记）
4. 保存 → 在这个 Project 里提问即可

### Claude for Enterprise / Cowork
1. 新建 Skill，将上方模板内容设为 System Prompt
2. 用户在对话中 @ 引用此 Skill 后提问

---

## 完整使用流程

```
在 Claude Project 里问「什么是 [名词]」
         ↓
Claude 输出 ##标签## 格式的完整词条
         ↓
复制完整回复（Ctrl+A → Ctrl+C）
         ↓
打开 EcomWiki → 点击「从剪贴板导入 AI 回复」
         ↓
词条自动进入知识库，永久保存 ✅
```

## EcomWiki 地址

```
https://[你的GitHub用户名].github.io/ecomwiki/
```

---
*EcomWiki v5 · CN/KR/JP/US 四市场 · 数据存储本地*
