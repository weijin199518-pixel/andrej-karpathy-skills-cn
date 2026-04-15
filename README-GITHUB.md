# Karpathy Skills 中文版 - 让 AI 写出更好代码的 4 大原则

> 基于 Andrej Karpathy 对 LLM 编程缺陷的观察，提炼出的实战指南

[![GitHub stars](https://img.shields.io/github/stars/yourusername/karpathy-skills-zh-cn?style=social)](https://github.com/yourusername/karpathy-skills-zh-cn)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 核心问题

AI 写代码时常见的 3 大问题：

1. **盲目假设** - 不确认需求就开始写，方向错了还继续
2. **过度复杂** - 1000 行能做的事，非要写成 10000 行
3. **乱改代码** - 改 A 功能时顺手"优化"了 B、C、D

## ✅ 4 大原则

### 1. 先想后写
- 不确定就问，不要猜
- 有多种方案就列出来，不要自己选
- 发现更简单的方法就说出来

### 2. 简单至上
- 只写需要的功能，不写"可能用到"的
- 单次使用的代码不要抽象
- 200 行能搞定就别写 1000 行

### 3. 精准修改
- 只改需要改的，不要"顺手优化"
- 不要重构没问题的代码
- 你的改动创造的垃圾代码，你负责清理

### 4. 目标驱动
- 把任务变成可验证的目标
- "修复 bug" → "写个测试复现它，然后让测试通过"
- "添加验证" → "写测试覆盖非法输入，然后让测试通过"

## 📦 使用方法

### 方式 1: 直接使用中文版规则

下载 [CLAUDE.zh-CN.md](./CLAUDE.zh-CN.md) 并放到你的项目根目录。

### 方式 2: Claude Code 插件

```bash
# 原版英文
/plugin marketplace add forrestchang/andrej-karpathy-skills
/plugin install andrej-karpathy-skills@karpathy-skills
```

## 🎁 中文增强版

我们提供了针对中国开发者的增强版本：

- ✅ 完整中文翻译
- ✅ 本土化案例
- ✅ 常见问题解答
- ✅ 实战避坑指南

## 💡 为什么需要这个

如果你遇到过这些问题：

- ❌ AI 写的代码总是过度复杂
- ❌ 改一个功能，结果改坏了三个
- ❌ AI 不问需求就开始写，方向错了还继续
- ❌ 代码能跑，但维护成本极高

那这个指南就是为你准备的。

## 📊 效果对比

| 维度 | 使用前 | 使用后 |
|------|--------|--------|
| 代码复杂度 | ⭐⭐⭐⭐⭐ | ⭐⭐ |
| 维护成本 | ⭐⭐⭐⭐⭐ | ⭐⭐ |
| Bug 率 | ⭐⭐⭐⭐ | ⭐ |

## 🤝 适合谁

- 使用 Claude Code / Cursor / GitHub Copilot 的开发者
- 团队中引入 AI 编程的技术负责人
- 想提升 AI 编程效率的个人开发者

## 📚 相关资源

- [原版 GitHub](https://github.com/forrestchang/andrej-karpathy-skills)
- [Andrej Karpathy 原推文](https://x.com/karpathy/status/2015883857489522876)
- [中文版规则文件](./CLAUDE.zh-CN.md)

## 📄 License

MIT License - 详见 [LICENSE](./LICENSE) 文件

---

**Star 这个项目，让更多开发者写出更好的代码！** ⭐

如果这个项目对你有帮助，欢迎：
- 给个 Star ⭐
- 分享给朋友
- 提交 Issue 或 PR
