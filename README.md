# TiebaSign

## 使用说明

1. Fork 本仓库，然后点击仓库右上角的 'Settings'，找到 'Secrets' 这一项，添加一个库秘密变量。
其中 `BDUSS` 存放你的 BDUSS。支持同时添加多个帐户，BDUSS 之间用 `#` 隔开即可。

2. 点击仓库上方的 'Actions' 选项，第一次打开需要点击 `I understand ...` 按钮，确认启用 GitHub Actions。

3. 任意 commit 一次，例如修改本 README.md 文件。

4. 搭建完毕，可以点击 'Actions' 查看工作记录，如果有 `Baidu Tieba Auto Sign` 则说明 workflow 创建成功。
点击右侧记录可以查看详细签到情况。
