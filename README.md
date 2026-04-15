<div align="center">

# 🏳️‍🌈 出柜模拟器.Skill

**基于 Claude Code 的出柜顾问与对话演练工具**

帮助 LGBTQ+ 用户摸清家庭底牌、获取有温度的策略建议，<br>并在安全环境里演练出柜对话，积累真实的心理经验。

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)
![AgentSkills](https://img.shields.io/badge/AgentSkills-Standard-green)
![Language: 中文](https://img.shields.io/badge/语言-中文-red)

</div>

---

## 这个 Skill 能做什么

| 阶段 | 内容 |
|------|------|
| 🔍 **摸清底牌** | 逐步了解家庭成员、地区、氛围、教育程度——一次问一个，不像填表格 |
| 🎯 **出柜策略** | 生成危险系数评估（1-5星）+ 个性化打法，幽默有料，不说废话 |
| 🎭 **对话演练** | 扮演真实家庭成员，按地区性格原型还原反应，附实时旁白 + 复盘 |

**覆盖范围：**
- 身份：gay / lesbian / 泛性恋等
- 中国各省份：一线城市、东北、广东珠三角、潮汕、山东、四川、西北……
- 海外地区：北美、欧洲、日韩、东南亚

---

## 安装

```bash
# 全局安装（所有项目都能用，推荐）
git clone https://github.com/YOUR_USERNAME/coming-out-skill ~/.claude/skills/coming-out

# 项目内安装（在 git 仓库根目录执行）
mkdir -p .claude/skills
git clone https://github.com/YOUR_USERNAME/coming-out-skill .claude/skills/coming-out
```

---

## 使用

在 Claude Code 中输入以下任意关键词即可触发：

```
出柜   coming out   我想出柜   怎么出柜
出柜模拟   出柜演练   告诉家人我是gay   告诉家人我是拉拉
```

触发后 Skill 会一步一步引导，不会一次问一堆问题。

---

## 项目结构

```
coming-out/
├── SKILL.md                          # Skill 主逻辑（三阶段流程）
├── references/
│   ├── regional-profiles.md          # 中国各省 + 海外地区家庭文化画像
│   ├── strategy-engine.md            # 出柜策略库（危险系数评级 + 幽默定性）
│   └── family-archetypes.md          # 家庭成员性格原型 + 模拟台词库
└── README.md
```

---

## 免责声明

本 Skill 为情感支持与演练工具，不构成任何心理咨询或医疗建议。出柜是个人决定，Skill 不会评价你"应该"还是"不应该"出柜。如有需要，请寻求专业心理咨询支持。
