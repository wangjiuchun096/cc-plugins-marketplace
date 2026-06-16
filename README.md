# CC Plugins Marketplace

我的 [Claude Code](https://claude.com/claude-code) 插件市场。

## 插件列表

| 插件 | 版本 | 用途 |
|---|---|---|
| [issue-report-builder](./plugins/issue-report-builder/) | 1.0.0 | 研发反馈单生成器，把随口描述的问题/需求整理成规范反馈单 |

## 安装插件

```bash
# 添加市场
/plugin marketplace add wangjiuchun/cc-plugins-marketplace

# 安装插件
/plugin install issue-report-builder
```

## 手动安装

```bash
cp -r plugins/issue-report-builder ~/.claude/skills/
```

## 索引

以下插件来自官方/第三方市场，日常常用，记录备查。

| 名称 | 来源 | 用途 |
|---|---|---|
| superpowers | 官方 | 开发流程方法论：brainstorming、systematic-debugging、TDD、code-review 等 |
| chrome-devtools-mcp | 官方 | 浏览器调试/自动化：chrome-devtools、a11y-debugging、memory-leak-debugging 等 |
| frontend-design | 官方 | 生成有设计感的前端界面代码 |
| skill-creator | 官方 | 创建、改进、评测 skill |
| claude-md-management | 官方 | 审计与改进 CLAUDE.md |
| drawio-skill | 365-skills | 生成 draw.io 图并导出 PNG/SVG/PDF |
| python-patterns | ECC | Pythonic 写法、PEP 8、类型注解 |
| python-testing | ECC | pytest / TDD / fixture / mock |
| search-first | ECC | 写代码前先搜现成工具/库/范式 |
| skill-stocktake | ECC | 批量审计 skill 质量 |
| strategic-compact | ECC | 任务交界处压缩上下文 |

---

*市场配置见 [.claude-plugin/marketplace.json](./.claude-plugin/marketplace.json)*
