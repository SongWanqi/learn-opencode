---
title: "Connect MiniMax (M2.7)"
subtitle: "10% Off for Tutorial Users"
course: "OpenCode Chinese Practical Course"
stage: "Phase 1"
lesson: "1.4d"
duration: "15 minutes"
practice: "5 minutes"
level: "Beginner"
description: "Get MiniMax API Key and connect M2.7 flagship model in OpenCode."
tags:
  - "Model"
  - "MiniMax"
  - "API Key"
prerequisite:
  - "1.2 Installation"
---

# Connect MiniMax (M2.7)

> Estimated time: 10-15 minutes

**MiniMax M2.7** is a top-tier domestic model, optimized for code and Agent tasks, supporting model self-evolution.

::: tip Recommended: Token Plan
Tutorial users get **10% off**. We recommend the **Max** or **Pro** plan for best value.
:::

If you haven't read "What is an API Key", we recommend going back to [1.4 Overview](./04-connect).

---

## What You'll Be Able to Do

- Get MiniMax API Key
- Connect MiniMax in OpenCode
- Select a model and complete your first conversation

---

## 🎒 Before You Start

- [ ] Completed [1.2 Installation](./02-install) and can run `opencode`
- [ ] Have access to MiniMax console and obtained API Key

---

## Follow Along

### Step 1: Register and Get API Key

Visit MiniMax platform (10% off for tutorial users):

https://platform.minimaxi.com/subscribe/token-plan?code=2OOzWR9jAE&source=link

::: tip Recommended Plans
We recommend **Token Plan** **Max** or **Pro** plans:
- **Max**: Best for heavy users, great value for high volume
- **Pro**: Suitable for daily development, cost-effective

After subscribing, copy your exclusive API Key from the "Plan Management" page:

<img src="/images/1-start/minimax-token-plan.png" alt="MiniMax Token Plan - Copy API Key" style="border: 1px solid #e1e4e8; border-radius: 6px; margin: 16px 0;" />

> 💡 The screenshot shows the Token Plan page. Select "Token Plan" in the left navigation, then click the "Copy" button in the API Key section to get your key.
:::

**Why recommend MiniMax M2.7?**

- 🏆 **Top-tier domestic model**: Ranked top 5 globally on Artificial Analysis, #1 in open source
- 🚀 **Self-evolution capability**: Can build complex Agent Harness, participate in model iteration
- 💻 **Software engineering expertise**: SWE-Pro 56.22%, close to Opus level
- 📦 **End-to-end delivery**: VIBE-Pro 55.6%, supports complete project development
- 🤝 **Agent Teams**: Native multi-agent collaboration support
- 💰 **High cost-effectiveness**: Maintains consistent price advantages

---

### Step 2: Connect MiniMax in OpenCode

Method A (Recommended to try first):

1. Start OpenCode:
   ```bash
   opencode
   ```
2. Enter:
   ```
   /connect
   ```
3. Search `MiniMax`, select **MiniMax Coding Plan (minimaxi.com)**, then paste your API Key

> 💡 China users should select the option with `(minimaxi.com)` suffix.


### Step 3: Select Model and Verify

Enter:

```
/models
```

Select `MiniMax-M2.7` or `MiniMax-M2.7-highspeed` (or other models in your configuration/list), then send a test message:

```
Hello, please introduce yourself
```

---

## Checklist ✅

- [ ] Can see and select MiniMax models in `/models`
- [ ] Can receive AI responses after sending messages

---

## Common Issues

| Symptom | Cause | Solution |
|---------|-------|----------|
| `Cannot read properties of undefined` | Incomplete configuration or wrong Key | Check baseURL and apiKey configuration |
| No response | Environment variable conflict | Clear `ANTHROPIC_AUTH_TOKEN` and other environment variables |

---

## Next Steps

- Return to [1.4 Overview](./04-connect) to choose another route, or proceed to [2.1 Interface and Basic Operations](../2-daily/01-interface)
