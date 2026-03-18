---
title: 连接 MiniMax（M2.7）
subtitle: 教程站专享 9 折优惠
course: OpenCode 中文实战课
stage: 第一阶段
lesson: "1.4d"
duration: 15 分钟
practice: 5 分钟
level: 新手
description: 获取 MiniMax API Key，并在 OpenCode 中连接使用 M2.7 旗舰模型。
tags:
  - 模型
  - MiniMax
  - API Key
prerequisite:
  - 1.2 安装
---

# 连接 MiniMax（M2.7）

> 预计时间：10-15 分钟

**MiniMax M2.7** 是国产模型第一梯队，专为代码和 Agent 任务优化，支持模型自我进化。

::: tip 推荐购买 Token Plan
教程站用户专享 **9 折优惠**，推荐购买 **Max** 或 **Pro** 套餐，性价比最高。
:::

如果你还没看过“API Key 是什么”，建议先回到 [1.4 总览](./04-connect)。

---

## 学完你能做什么

- 获取 MiniMax API Key
- 在 OpenCode 里连接 MiniMax
- 选择模型并完成第一次对话

---

## 🎒 开始前的准备

- [ ] 完成了 [1.2 安装](./02-install)，能运行 `opencode`
- [ ] 已能访问 MiniMax 控制台并拿到 API Key

---

## 跟我做

### 第 1 步：注册并获取 API Key

访问 MiniMax 平台（教程站用户专享链接，9折优惠）：

https://platform.minimaxi.com/subscribe/token-plan?code=2OOzWR9jAE&source=link

::: tip 推荐套餐
推荐购买 **Token Plan** 的 **Max** 或 **Pro** 套餐：
- **Max**：重度用户首选，量大优惠
- **Pro**：日常开发够用，性价比高

订阅后在「套餐管理」页面复制专属 API Key：

<img src="/images/1-start/minimax-token-plan.png" alt="MiniMax Token Plan 页面 - 复制 API Key" style="border: 1px solid #e1e4e8; border-radius: 6px; margin: 16px 0;" />

> 💡 截图显示了 Token Plan 页面，左侧导航选择「Token Plan」，在 API Key 区域点击「复制」按钮获取密钥。
:::

**为什么推荐 MiniMax M2.7？**

- 🏆 **国产模型第一梯队**：Artificial Analysis 全球排名前五，开源第一
- 🚀 **自我进化能力**：能构建复杂 Agent Harness，参与模型自身迭代
- 💻 **软件工程专长**：SWE-Pro 56.22%，接近 Opus 水平
- 📦 **端到端交付**：VIBE-Pro 55.6%，支持完整项目开发
- 🤝 **Agent Teams**：原生支持多智能体协作
- 💰 **高性价比**：保持一贯价格优势

---

### 第 2 步：在 OpenCode 中连接 MiniMax

方式 A（推荐优先尝试）：

1. 启动 OpenCode：
   ```bash
   opencode
   ```
2. 输入：
   ```
   /connect
   ```
3. 搜索 `MiniMax`，选择 **MiniMax Coding Plan (minimaxi.com)**，粘贴 API Key

> 💡 国内用户推荐选择带有 `(minimaxi.com)` 后缀的选项。


### 第 3 步：选择模型并验证

输入：

```
/models
```

选择 `MiniMax-M2.7` 或 `MiniMax-M2.7-highspeed`（或你配置/列表中的其他模型），然后发送一句话验证：

```
你好，请介绍一下你自己
```

---

## 检查点 ✅

- [ ] `/models` 里能看到并选择 MiniMax 模型
- [ ] 发送消息能收到 AI 回复

---

## 踩坑提醒

| 现象 | 原因 | 解决 |
|-----|------|------|
| `Cannot read properties of undefined` | 配置不完整或 Key 错误 | 检查 baseURL 和 apiKey 配置 |
| 没有响应 | 环境变量冲突 | 清除 `ANTHROPIC_AUTH_TOKEN` 等环境变量 |

---

## 下一步

- 回到 [1.4 总览](./04-connect) 选择下一条路线，或进入 [2.1 界面与基础操作](../2-daily/01-interface)