# 第 2 周复盘（2026-11-03 ~ 11-09）

## 这周学了什么

- Git 四步流程：status → add → commit → push
- pull 的作用：把 GitHub 上的改动拉到本地
- Markdown 语法：标题、列表、表格、代码块、链接
- 怎么读一个开源项目的 README

## 踩过的坑

1. `git push` 报 `Recv failure: Connection was reset`
   → 国内网络抖动，重敲一次通常就好
2. `git push` 报 `Failed to connect to github.com:443`
   → 网络完全不通，隔一段时间再试，或者换网络
3. `git pull` 弹出 vim 界面
   → 按 Esc，输入 :wq 回车退出
4. 网页改过文件后本地 push 失败
   → 先 git pull 合并，再 git push

## 数字记录

- hello-github 提交数：[11]
- 笔记仓库文件数：[2]
- Star 项目数：[7]

## 下周要做什么

第 3 周开始写 Python 代码，做第一个 AI 问答机器人：
1. 搭环境（虚拟环境 + Streamlit + OpenAI SDK）
2. 调用 DeepSeek API
3. 做网页界面
4. 多轮对话 + 流式输出
5. 写 README 发布
