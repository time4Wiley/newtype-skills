<p align="right">
  <a href="./README.md">English</a> | <strong>简体中文</strong>
</p>

# newtype-skills

一套 AI 提示词技能集，涵盖分析、写作、事实核查、编辑和访谈。这些技能是基于方法论的提示词，可以与任何 AI 助手配合使用（ChatGPT、Claude、Gemini 等）。

---

## 作者：黄益贺

- **YouTube**: [https://www.youtube.com/@huanyihe777](https://www.youtube.com/@huanyihe777)
- **Twitter**: [https://x.com/huangyihe](https://x.com/huangyihe)
- **Substack**: [https://newtype.pro/](https://newtype.pro/)
- **知识星球**: [https://t.zsxq.com/19IaNz5wK](https://t.zsxq.com/19IaNz5wK)

---

## 技能概览

### 核心技能

| 技能 | 描述 | 适用场景 |
|------|------|----------|
| **[Super Analyst](./skills/super-analyst/SKILL.md)** | 12 个分析框架 + 系统化调研方法论 | 战略分析、竞争研究、投资决策、根因诊断 |
| **[Super Writer](./skills/super-writer/SKILL.md)** | 6 种写作方法论（W.R.I.T.E、AIDA、Storytelling 等） | 博客文章、营销文案、品牌故事、社媒内容 |
| **[Super Fact-Checker](./skills/super-fact-checker/SKILL.md)** | 系统化核查：声明提取、来源可信度、结果标注 | 内容审核、来源验证、准确性保障 |
| **[Super Editor](./skills/super-editor/SKILL.md)** | 四层编辑法：结构 → 段落 → 句子 → 词语 | 草稿润色、可读性提升、一致性检查 |
| **[Super Interviewer](./skills/super-interviewer/SKILL.md)** | 对话技巧：开放式提问、5 Whys、苏格拉底法 | 头脑风暴、需求挖掘、深度探索 |

### 专业技能

| 技能 | 描述 | 适用场景 |
|------|------|----------|
| **[双模型分析](./skills/dual-model-analyze/SKILL.md)** | 并行使用 GPT-5.2 + Gemini 3 Pro 进行交叉验证分析 | 数据分析、交叉验证、高风险决策 |
| **[会议消化](./skills/meeting-digest/SKILL.md)** | 会议记录处理器，带双模型洞察提取 | 会议笔记处理、决策追踪、全景更新 |
| **[项目同步包](./skills/project-sync-pack/SKILL.md)** | 从 Markdown 生成视觉交付物（PPTX + PNG） | 演示文稿生成、信息图创建、可视化报告 |

---

## 使用方法

### 方法一：直接复制粘贴

1. 打开技能文件（如 `skills/super-analyst/SKILL.md`）
2. 复制全部内容
3. 粘贴到与任意 AI 助手对话的开头
4. AI 会按照方法论进行回复

### 方法二：配合 OpenCode / Claude Code 使用

如果你使用 [OpenCode](https://opencode.ai) 或 Claude Code，可以将这些作为技能加载：

1. 将仓库克隆到 `~/.claude/skills/` 或 `.opencode/skill/`：
   ```bash
   git clone https://github.com/newtype-01/huangyihe-skills.git ~/.claude/skills/huangyihe-skills
   ```

2. 使用 `/skill` 命令加载：
   ```
   /skill super-analyst
   ```

### 方法三：Custom GPT / Claude Project

你也可以将这些提示词添加到：
- ChatGPT Custom GPT 的指令中
- Claude Project 的系统提示中
- 任何支持自定义指令的 AI 工具

---

## 技能详解

### Super Analyst（超级分析师）

**最适合**：战略决策、竞争分析、投资评估、问题诊断

**特点**：
- 三级复杂度识别（简单 → 单框架 → 组合框架）
- 12 个分析框架，每个都有步骤指南：
  - SWOT、波特五力、成本效益分析
  - 第一性原理、5 Whys、设计思维
  - 系统思维、情景规划、MECE
  - 帕累托、假设驱动、苏格拉底法
- 调研方法论：来源分层、可信度评估、三角验证

**示例提问**：
- "用 SWOT 分析特斯拉的竞争优势"
- "我们应该进入印度市场吗？用合适的框架分析"
- "我们转化率下降的根本原因是什么？"

---

### Super Writer（超级写手）

**最适合**：内容创作、文案写作、故事讲述

**特点**：
- 6 种写作方法论：
  - **W.R.I.T.E**：初稿 → 研究 → 构思 → 定位 → 优化
  - **AIDA**：吸引注意 → 引发兴趣 → 激发渴望 → 促成行动
  - **Storytelling**：设定 → 冲突 → 历程 → 高潮 → 结局
  - **Content Writing Process**：规划 → 研究 → 写作 → 编辑 → 发布
  - **Content Creation Techniques**：Hook-Story-Offer、Problem-Agitate-Solve 等
  - **High-Value Content Strategies**：深度长文、原创研究、专家访谈
- 风格提取，用于模仿参考内容

**示例提问**：
- "用 W.R.I.T.E 方法写一篇关于 AI 生产力的博客"
- "用 AIDA 为我们的新产品写一封销售邮件"
- "为一位创业者写品牌故事"

---

### Super Fact-Checker（超级事实核查员）

**最适合**：内容审核、来源验证、准确性保障

**特点**：
- 声明分类（可核查 vs 不可核查）
- 优先级矩阵（影响度 × 可疑度）
- 来源可信度层级（6 级）
- 数据、引用、事件的验证方法
- 标注体系：✅ 已验证、⚠️ 部分验证、❓ 无法验证、❌ 有误、🔍 需进一步核查

**示例提问**：
- "核查这篇文章，标注每条声明"
- "验证这份报告的数据来源"
- "审核这份新闻稿的准确性"

---

### Super Editor（超级编辑）

**最适合**：草稿润色、可读性提升、一致性检查

**特点**：
- 四层编辑法：
  1. **结构层**：整体架构、章节顺序、逻辑流程
  2. **段落层**：内聚性、过渡、信息密度
  3. **句子层**：清晰度、节奏、歧义
  4. **词语层**：精准、一致、冗余
- 每层都有检查清单和常见问题诊断
- 编辑报告格式，附修改理由

**示例提问**：
- "编辑这篇文章，重点关注结构和段落流畅度"
- "润色这份草稿，提高清晰度和简洁度"
- "检查这份文档的术语一致性"

---

### Super Interviewer（超级访谈者）

**最适合**：头脑风暴、需求挖掘、深度探索

**特点**：
- 提问类型：开放式/封闭式、澄清、追问、挑战、总结
- 对话四阶段：破冰 → 开放探索 → 深度挖掘 → 总结确认
- 苏格拉底技巧：概念澄清、假设质疑、后果探索
- 5 Whys 方法论，用于发现根本原因
- 需求挖掘三层：表面需求 → 深层需求 → 核心动机

**示例提问**：
- "用苏格拉底法帮我思考这个产品想法"
- "访谈我,了解我真正的需求"
- "挑战我对这个商业计划的假设"

---

### Dual-Model Analyze（双模型分析）

**最适合**：需要交叉验证的数据分析、高风险决策

**特点**：
- 并行运行 GPT-5.2（高推理）和 Gemini 3 Pro（高思考）
- 综合输出，突出一致性和差异性
- 使用 uv 内联脚本元数据实现零配置执行
- 需要 `OPENAI_API_KEY` 和 `GEMINI_API_KEY` 环境变量

**示例提问**：
- "分析 API 响应时间与错误率之间的相关性"
- "比较 2026 年 LLM API 提供商的竞争格局"
- "分析这个算法的时间复杂度和瓶颈"

---

### Meeting Digest（会议消化）

**最适合**：处理会议记录、追踪决策和待办事项

**特点**：
- 从会议记录中提取决策、待办、洞察、团队变更
- 支持 .docx、.txt 或粘贴的文本输入
- 可选双模型分析以进行更深入的洞察提取
- 与现有全景 markdown 进行对比
- 生成带变更追踪的注释更新

**示例提问**：
- "处理这份会议记录并更新全景"
- "从这些会议笔记中提取决策和待办"
- "用最新讨论更新主文档"

---

### Project Sync Pack（项目同步包）

**最适合**：从 markdown 生成演示文稿和信息图

**特点**：
- 读取主全景 markdown 并重新生成 PPTX + PNG
- PptxGenJS 配合深红/金色设计系统
- Pillow 双字体渲染器，适配移动端 PNG
- 生成前可选双模型质量审查
- 视觉质检，带截图验证

**示例提问**：
- "从全景 markdown 生成 PPTX 和 PNG"
- "刷新所有视觉交付物"
- "用最新内容更新演示文稿"

---

## 语言

所有技能都以**简体中文**为主要语言编写。方法论和框架是通用的，无论你用中文还是英文交流，效果都一样好。

---

## 许可证

MIT License - 可自由使用、修改和分发。

---

## 贡献

欢迎贡献！如果你有改进建议或新技能要添加，请提交 Pull Request。
