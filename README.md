# pm-doc-template-kit

WorkBuddy PM 文档模板工具包。这个仓库同时维护：

1. `SKILL.md`：根据任务选择 PM 文档模板、补全文档并按项目目录归档的技能说明。
2. `templates/`：产品经理文档 `.docx` 原始模板库。

## 模板清单

| 模板 | 用途 |
|---|---|
| `01-需求报告模板.docx` | 需求简报、需求报告、立项前说明 |
| `02-需求评审记录模板.docx` | 需求评审、评审意见、评审结论 |
| `03-PRD文档模板.docx` | PRD、功能规格、页面与规则说明 |
| `04-遗留问题记录模板.docx` | 待确认问题、遗留问题 |
| `05-技术风险记录模板.docx` | 技术风险、三方依赖、上线风险 |
| `06-工期节点计划模板.docx` | 里程碑、排期、交付计划 |
| `07-UI评审记录模板.docx` | UI 走查、设计评审、截图验收 |
| `08-延期记录模板.docx` | 延期说明、延期影响、调整方案 |
| `09-测试用例模板.docx` | 测试用例、冒烟用例、回归用例 |
| `10-项目产出物清单模板.docx` | 交付清单、验收材料清单 |

## 使用规则

- 不直接修改原始模板；生成项目文档时先复制或转写模板，再按项目目录归档。
- 项目阶段、目录规则、验收口径以项目根 `AGENTS.md` 为准。
- 在 WorkBuddy 工作区内，`/Users/macos/Downloads/WorkBuddy/agents.md` 是主规范。

## 换机恢复

```bash
cd ~/Downloads/WorkBuddy/skills
git clone git@github.com:genapohub/pm-doc-template-kit.git
```

不再在工作区根目录维护重复模板展示目录。需要生成项目文档时，从本仓库 `templates/` 复制或转写到目标项目目录，例如：

```bash
cp ~/Downloads/genapoWork/skills/pm-doc-template-kit/templates/03-PRD文档模板.docx ~/Downloads/genapoWork/<项目名>/02-产品文档/<项目名>_PRD_v1.0.docx
```
