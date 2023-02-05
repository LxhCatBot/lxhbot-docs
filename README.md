# lxhbot-docs

小黑猫 Bot 的在线帮助文档,使用 `mkdocs` 构建。

# 本地开发

## 启动服务器

需要预装 `Python3` 以及 `pip`

    python -m pip install -r ./requirements.txt
    python -m mkdocs serve

## 构建

    python -m mkdocs build

构建完成的文件在 `dist` 目录下,上传到任意托管平台即可

# 在线开发

向 [本仓库](https://github.com/LxhCatBot/lxhbot-docs) push ,Github Action 会自动构建,输出在 `gh-pages` 分支
