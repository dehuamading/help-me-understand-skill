# 帮我看懂（help-me-understand）

让 AI 把你真正看不懂的东西讲清楚：先判断卡在哪里，再选择文字、图示或交互 HTML，并保留数字、证据和适用边界。

这是我在 GitHub 上的个人备份。内容来自「得到 AI 学习圈」分享的 `help-me-understand.zip`；公开镜像中的 `SKILL.md` 标注了 `source: 得到AI学习圈`。这不是得到官方仓库。

## 适合什么场景

- 论文、报告、复杂方案或长文，看完仍说不出它怎么运作
- AI 的回答术语太多，看不出概念之间的关系
- 想知道「改变这个条件会怎样」
- 已经说了「还是没懂」，希望换个讲法而不是继续加长

## 仓库内容

| 路径 | 作用 |
| --- | --- |
| `SKILL.md` | 技能主文件：工作流程、输出形式、交付前检查 |
| `references/ste-and-chinese.md` | STE 表达原则与中文适配 |
| `references/sources.md` | 来源说明与核验规则 |
| `references/acceptance-cases.md` | 验收案例 |
| `examples/` | 图示、交互 HTML、示例材料 |

## 怎么用

### Codex

```powershell
git clone https://github.com/dehuamading/help-me-understand-skill.git (Join-Path $env:USERPROFILE '.codex\skills\help-me-understand')
```

重启 Codex 后，用「帮我看懂……」或「这个过程画出来」触发。

### Claude Code

```shell
git clone https://github.com/dehuamading/help-me-understand-skill.git ~/.claude/skills/help-me-understand
```

### 其他支持 SKILL.md 的工具

把整个目录放进该工具的 skills 目录，或直接把 `SKILL.md` 作为提示词加载。技能本身不依赖特定产品或安装路径。

## 备份来源

- 原始分享：<https://d.dedao.cn/1juJAwh>（跳转至企业微信文件 `help-me-understand.zip`，17,897 字节，需登录）
- 公开镜像：[`littlejcai/skill-registry`](https://github.com/littlejcai/skill-registry/tree/main/skills/help-me-understand)
- 镜像中的来源标注：`得到AI学习圈`
- 备份日期：2026-10-25
- 文件校验：见 [BACKUP.md](BACKUP.md)

## 版权

技能内容版权归「得到 AI 学习圈」及原作者所有。上游镜像未声明开源许可证；本仓库仅作个人备份与学习使用，不构成任何授权。详见 [NOTICE.md](NOTICE.md)。
