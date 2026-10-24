# 备份记录

## 来源

| 项目 | 记录 |
| --- | --- |
| 原始短链 | `https://d.dedao.cn/1juJAwh` |
| 跳转地址 | `https://drive.weixin.qq.com/s?k=ADQABgdrAAkEC4pwXL` |
| 企业微信文件名 | `help-me-understand.zip` |
| 文件大小 | 17,897 字节 |
| 分享者 | `AI圈苏苏（工作日10:00-19:00陆续回）` |
| 所属企业 | `得到APP` |
| 直接下载 | 需要企业微信登录，备份时未能直接取得压缩包 |
| 内容来源 | [`littlejcai/skill-registry`](https://github.com/littlejcai/skill-registry/tree/main/skills/help-me-understand) 中的同名技能；其 `SKILL.md` 标注 `source: 得到AI学习圈` |
| 上游文件提交 | `81bb809c0965e311c1f68c8173f32ac0f54b7374`（2026-10-16） |
| 备份日期 | 2026-10-25 |

> 说明：企业微信分享页需要登录，无法直接读取压缩包。本备份取自公开镜像中标注来源为「得到AI学习圈」的同名技能。文件清单与当前镜像一致；如果原压缩包含有额外的 README 或预览图，本仓库未包含。

## 文件清单

| 文件 | 字节 | SHA-256 |
| --- | ---: | --- |
| `SKILL.md` | 7,042 | `e7545092e876716e6fc1f8534683c04726f5f0ed4833d79975d83e82ad825bdd` |
| `references/ste-and-chinese.md` | 4,096 | `420bb4b63ba2ee4c2872f98a1d87ef1c5d4268d216ad5a248f324471455a30f6` |
| `references/sources.md` | 3,127 | `4c2572c68101f57e38582054ec1d7bc02ba8b9680a67f3dcb060d761c34077d3` |
| `references/acceptance-cases.md` | 3,055 | `51062ae8a021f45cbb07f6d521c274b4f082b1b52fa479c5f7d90c090aba6218` |
| `examples/flow.svg` | 3,606 | `e2ea08b682a1708b94e8f710aba38384704fe5d4d3ac1b720fb7113b4f5167b4` |
| `examples/parallel-demo.html` | 7,348 | `59ababe03aa3e67342a68da5202d6e29373483df8a93c14d210a78a12940aecf` |
| `examples/source.md` | 1,745 | `7d68389587c7b448195d36d7e12be015e2a3314e51cfcb74c3f9592790434599` |
| `examples/walkthrough.md` | 2,424 | `ec748b5f15502c4494a07ba52a1c78e994137a370a0bcbf0cd444be191f275e2` |

## 校验方式

```powershell
Get-FileHash SKILL.md -Algorithm SHA256
Get-ChildItem references,examples -Recurse -File | Get-FileHash -Algorithm SHA256
```
