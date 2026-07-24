# Vibe Coding Sandbox 🎨

> 国金证券 Spec/Vibe Coding 培训 — **0 → 1 从零演练**沙盒。
> 这里没有脚手架、没有现成代码，只有你和 AI，从一个空仓库开始把一个想法变成能跑的东西。

## 这是什么

供学员练习 **Vibe Coding**（用自然语言驱动 AI 写代码）的空仓库。适合用来：
- 体验"描述需求 → AI 生成 → 你审查/调整"的循环
- 在没有既有架构约束的情况下，快速搭一个原型
- 对照 [`we-erp-training`](https://github.com/renzhichao/we-erp-training) 里"有 Spec 的 Spec Coding"，感受两种工作流的差异

## 怎么用

1. **认领一个主题**（见下方，或自拟）
2. 用 AI 编码助手（Claude Code / Cursor 等）从零开始实现
3. 把过程当成交付物 —— commit message 写清楚你让 AI 做了什么、你为什么改

> 💡 建议每位学员 fork 本仓库或新建自己的分支练习，避免互相覆盖。

## 推荐主题（从易到难）

| 难度 | 主题 | 一句话描述 |
|------|------|-----------|
| ⭐ | 待办清单 | 一个能增删改查、本地持久化的 TODO CLI 或网页 |
| ⭐⭐ | 报销计算器 | 输入一堆发票，按税率/类别汇总输出报表 |
| ⭐⭐ | 股票监控 | 抓取某只股票行情，价格突破阈值时提醒 |
| ⭐⭐⭐ | 迷你 ERP | 实现一个最小闭环：商品 + 订单 + 库存扣减 |

## 规则

- 🚫 **不要提交任何真实数据**：真实客户、真实凭证、内部主机/IP 一律禁止
- ✅ 每个 commit 写清意图，不要 `update`、`fix` 这类无信息消息
- ✅ 至少写一个能跑的测试或手动验证步骤
- 🤝 鼓励把遇到的好 prompt / 坑记录到 `NOTES.md`

## 相关

- Spec Coding（有规格先行的训练）：[`we-erp-training`](https://github.com/renzhichao/we-erp-training)
