# hello-world

我的第一个 GitHub 仓库。

- 账号：ZYRJYLF
- 创建时间：2026-10-22
- 用途：练手，验证 SSH 推送链路

## 已经跑通的链路

```
本地 Git  →  SSH (ed25519)  →  github.com:22  →  ZYRJYLF/hello-world
```

## 常用命令备忘

```bash
git status              # 看当前改了哪些文件
git add -A              # 把所有改动加入暂存区
git commit -m "说明"    # 提交
git push                # 推到 GitHub
git pull                # 拉取最新
git log --oneline       # 看提交历史
```

## 注意

GitHub 网页（443 端口）在国内线路上时通时断，但 `git push` 走的是 22 端口的 SSH，不受影响。
