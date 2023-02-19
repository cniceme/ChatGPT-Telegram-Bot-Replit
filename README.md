# ChatGPT Telegram Bot Replit 远程部署

首先，安装 python 依赖

```bash
pip install -r requirements.txt
```

在左边栏 Tools 里面选择 Secrets，添加机器人需要的环境变量，一共四个：

- BOT_TOKEN: 你需要在 [BotFather](https://t.me/BotFather) 创建一个 bot 以获取 BOT_TOKEN
- WEB_HOOK: 在 Replit 会自动分配一个域名给你，填入 `https://appname.username.repl.co`
- EMAIL，PASSWORD: openai 的账号密码.
- NICK: 可选，默认为空，NICK 是机器人的名字。当用户输入消息以 NICK 开头，机器人才会回答，否则机器人会回答任何消息。尤其在群聊里，没有 NICK，机器人会对所有消息进行回复。

点击屏幕上方的 run，即可运行机器人。