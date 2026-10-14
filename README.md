<div align="center">

# 🎬 astra-prompt-optimizer

## 提示词救不了运行配置错，先分清再改
## Prompt rewrites can't fix a wrong run config — split them first

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这是一个提示词优化技能：动手改写之前，先识别用户到底要做什么任务，并按任务筛选相关上下文，避免把无关信息一起塞进提示词。它会先复述并确认用户要求的那一个操作，再据此优化，同时严格区分「提示词文本」和「运行配置」两类东西，防止把配置项当成措辞问题去改。它设有明确的路由边界——不介入普通的 Design 创作，只在需要优化提示词的任务上出手。技能内含 DESIGN 运行假设，用它来判断哪些设定属于运行前提、哪些才是可以优化的表达。

### ✨ 能做什么

- 先识别任务类型，再按相关性筛选上下文，无关内容不进提示词
- 复述并确认用户指定的那一个操作，只做用户真正要求的那一步
- 区分提示词与运行配置：配置问题不当作措辞问题处理
- 内置 DESIGN 运行假设，判定哪些设定是运行前提、哪些可优化
- 明确路由边界：普通 Design 创作不介入，只在优化任务上触发
- 输出可用的优化后提示词，而不是泛泛的改写建议

### 📦 包含的技能

- `astra-prompt-optimizer` —— 见 [`astra-prompt-optimizer/SKILL.md`](astra-prompt-optimizer/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/astra-prompt-optimizer.git
cp -r astra-prompt-optimizer/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A prompt-optimization skill that identifies the task first and filters in only the context that matters before touching any wording. It confirms the single operation the user actually asked for, then optimizes against that, instead of rewriting everything in reach. It draws a hard line between prompt text and runtime configuration, so config mistakes never get "fixed" as phrasing problems. Routing boundaries are explicit: it does not step into ordinary Design creation, and only runs where prompt optimization is genuinely the job. Built-in DESIGN runtime assumptions separate the premises that must hold from the wording that is free to change.

### ✨ What it does

- Identifies the task first, then filters context so irrelevant material stays out
- Restates and confirms the one operation requested, and only performs that step
- Separates prompt text from runtime config so config issues aren't rewritten as wording
- Ships DESIGN runtime assumptions that separate fixed premises from optimizable phrasing
- Enforces routing boundaries: no intervention in ordinary Design creation
- Returns an optimized prompt ready to use, not generic rewriting advice

### 📦 Skills included

- `astra-prompt-optimizer` — [`astra-prompt-optimizer/SKILL.md`](astra-prompt-optimizer/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/astra-prompt-optimizer.git
cp -r astra-prompt-optimizer/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
