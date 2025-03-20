[英语](./README-en.md) | 简体中文

#电报记账机器人

这是一个电报（Telegram）记账机器人，可以帮助你记录支出和收入。

## 部署

1. 安装Docker（Docker）和Docker（Docker）组合
2. 克隆本仓库到本地
3. 将env目录中的.example文件都重命名为.env文件，并按需修改数据库名称、密码等配置
4. 在重命名后的 `bot.env` 文件中修改 `远程BOT_TOKEN` 为你自己的电报机器人令牌
5. 在终端中进入项目目录，运行 `docker-compose up -d` 启动容器，如果你不需要OpenAPI功能，则执行`docker-compose up -d bot` 即可
6. 打开电报，搜索你的机器人，开始使用

## 使用

以下是目前可用的命令：

    /start - 开始使用

    /day - 查看当日账单

    /month - 查看当月账单

    /set_keyboard - 设置快捷键盘

    /cancel - 取消当前操作

    /set_balance - 设置余额

    /balance - 查询余额

    /create_令牌创建用于OpenAPI的令牌

    /disable_all_tokens 废弃所有 token

## TODO
- [x]自动更新Bot命令
- [x]开放应用程序界面
- [ ]使用多种语言的
- [ ]自然语言界面
