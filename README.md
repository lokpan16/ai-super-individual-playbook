# AI超级个体方法论 Playbook

《AI超级个体：打造不可替代的个人品牌》（元宇宙公主、徐旦，机械工业出版社 2026）方法论知识库，提炼全书 14 章的框架、模型、原则、提示词与反模式。

符合 [Agent Skills 开放标准](https://agentskills.io/)，可安装到任何兼容的 AI Agent 宿主（Kimi、Claude Code、Codex、Copilot、Cursor 等），在工作对话中按需调用书中方法论。

## 覆盖主题

- **定位**：蓝海三步法、高变现三标准、差异化三维度（交叉 / 隐藏需求 / 新概念）、五个记忆点、品牌手册
- **内容**：八种变现路径、变现地图四层、GEO 写作三步 + 四结构、8 周冷启动、共鸣十按钮
- **转化**：AIDA（7 种开篇 / 3 种兴趣 / 4 种欲望 / 4 种行动）、被推荐五特征、销售漏斗四阶段、朋友圈三层叙事
- **分发**：平台算法人格表、30 分钟四人格改写、人格冲突与一致性检测
- **社群**：粉丝五层 KPI、价值金字塔、四级商业化、七种商业模型、运营四部曲、七日上线
- **变现**：三层产品（AI 体验官 / AI 私教 / AI 工作流设计师）、一周做课、会员制、人格资产化、AI 咨询三场景与三步验证
- **管理**：12 位 AI 同事四象限、外包三原则、三层时间（30/50/20）、三日循环
- **转型**：技能 IP 化四步飞轮、专业 × 情绪 × 立场定位、三道护城河（替代率 ≥50% 且 6 个月 / 拐点后 / 储蓄 ≥12 月）、过渡三期

## 目录结构

```
ai-super-individual-playbook/
├── SKILL.md              # 技能入口：何时使用、心智模型、工作流程、快速索引
└── references/
    └── notes.md          # 全书 14 章笔记：框架、案例、反模式清单、提示词模板、教学设计
```

## 安装方法

### Kimi Work / Kimi

把本仓库克隆（或下载）到本机 skills 目录即可被自动识别：

```bash
git clone https://github.com/lokpan16/ai-super-individual-playbook.git \
  ~/skills/ai-super-individual-playbook
```

也可以在 Kimi Work 中用 plugin-builder 技能把本仓库直接导入为个人插件。

### Claude Code / Codex / Copilot / Cursor 等

将本目录复制到宿主约定的 skills 位置：

```bash
# Claude Code 示例
git clone https://github.com/lokpan16/ai-super-individual-playbook.git \
  ~/.claude/skills/ai-super-individual-playbook
```

其他宿主放到对应的 `skills/` 目录下即可，结构无需改动。

## 使用方式

安装后直接在对话中描述需求即可触发，例如：

- 「帮我做个人 IP 定位」→ 套用蓝海三步法与差异化三维度
- 「写一篇能被 AI 引用的文章」→ 套用 GEO 写作三步 + 四结构
- 「设计一个社群的变现模型」→ 套用粉丝五层 KPI 与七种商业模型
- 「我的副业该不该转主业」→ 套用转型三道护城河决策模型

Agent 会按 `SKILL.md` 的工作流程，到 `references/notes.md` 取对应章节的框架，输出「框架 + 填空模板 + 一个反模式提醒」。

## 使用提示

- 书中量化数据多为作者引述，引用时建议标注「据书中引述」并二次核实。
- 本知识库为读书笔记性质的学习与教学素材，供个人学习、内训、社群带读使用。

## License

知识库结构与个人笔记部分以 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 发布；原书内容版权归机械工业出版社及作者所有，本仓库仅为方法论提炼与转述，不含原书正文。
