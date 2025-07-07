# # 🔮ChatGPT Telegram Bot (by nodejs)

<img src="https://www.helloimg.com/images/2023/02/02/oZLhl9.jpg" width = "400"/>

### 💍演示成品机器人:[@sisChatBot](https://t.me/sisChatBot)
## 事前准备🛡️
- 申请Telegram bot api token : https://t.me/BotFather
- 获取[OpenAi apiKey](https://platform.openai.com/account/api-keys)
- Node.js版本 18+

## 部署⚔️

1. 克隆项目，安装依赖

   ```bash
   git clone https://github.com/hobk/chatgpt-telebot.git
   cd chatgpt-telebot
   npm install
   ```
   
2. 把之前准备的 Telegram bot token 和 openAi apiKey 对应写入 .env 文件

   ```bash
   # 1.复制文件
   cp .env.example .env
   
   # 2.编辑 .env
     #token='your TelegramBot token'
     #apiKey='your openAi apiKey'
     #group_name = '群消息中需要回复的消息必须以该名称开头，如设置为'gpt'，那么群消息中必须以/gpt开头才会触发回复'
   ```

3. 启动

   ```bash
    node index.js
    # 或者使用 pm2 （安装：npm i pm2 -g）
    pm2 start index.js
   ```

> 本项目 CDN 加速及安全防护由 Tencent EdgeOne 赞助
   [![EdgeOne](https://edgeone.ai/media/34fe3a45-492d-4ea4-ae5d-ea1087ca7b4b.png)](https://edgeone.ai/zh?from=github)
