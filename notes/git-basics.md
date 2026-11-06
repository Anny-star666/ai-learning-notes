# Git 常用命令速查

## 日常四步

| 命令 | 作用 | 什么时候用 |
| --- | --- | --- |
| `git status` | 查看当前状态 | 每次改完文件先敲 |
| `git add .` | 把改动加入暂存区 | 确认改动没问题后 |
| `git commit -m "说明"` | 保存一次快照 | add 之后 |
| `git push` | 推送到 GitHub | commit 之后 |

## 同步相关

| 命令 | 作用 |
| --- | --- |
| `git pull` | 把 GitHub 上的改动拉到本地 |
| `git clone 地址` | 把远程仓库完整下载到本地 |

## 查看历史

| 命令 | 作用 |
| --- | --- |
| `git log --oneline` | 一行一条看提交历史 |
| `git diff` | 看具体改了哪些行 |

## 我踩过的坑

- `git push` 报 `Recv failure: Connection was reset`：国内网络抖动，重敲一次通常就好
- `git config --global user.name "值"`：name 和引号之间必须有空格
