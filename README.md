# hello-omc606

`omc606` 账号的第一个仓库，用来验证整条 Git 链路是否真的通了。

## 这个仓库验证了什么

| 环节 | 结果 |
|---|---|
| SSH 认证（22 / 443） | `Hi omc606! You've successfully authenticated` |
| 提交身份 | `OMC606` + `357308607+omc606@users.noreply.github.com`（不含真实邮箱） |
| 远端分支 | `main` |
| 推送路径 | SSH，不走 HTTPS |

## 用途说明

这是一个**空壳验证仓库**，只有 README 和 .gitignore。真实项目请另开仓库，建议默认私有。

## 后续常用命令

```bash
git clone git@github.com:omc606/hello-omc606.git
git add .
git commit -m "说明这次改了什么"
git push
```
