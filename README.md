This is a telegram bot for removing all messages in group/chat.

# Prerequisite
For group, `Chat History For New Members` setting must configure to `Visible` **at the begining of group conversation starts**. Otherwise the bot cannot obtain chat history and there is no way to delete them. If the setting switch to `Visible` at the middle of conversation, the bot can only remove messages after this setting switched.

**Please test before use, if you are having sensitive conversation :)**

# Bot Setup
1. Register a bot in telegram https://core.telegram.org/bots#6-botfather
2. Obtain `token` from Bot Father
3. `npm install`
4. `BOT_TOKEN=XXXXX node bot.js`

# Clear all messages
1. Invite your bot to group/chat
2. Add the bot as admin with all permissions
3. Type and send `/deleteAll` in your group/chat


### Deploy To Heroku 📡</h4>

<p align="left">
  <a href="https://heroku.com/deploy?template=https://github.com/TG-Musics/Telegram_Vc_Bot">
     <img height="30px" src="https://img.shields.io/badge/Deploy%20To%20Heroku-blueviolet?style=for-the-badge&logo=heroku">
  </a>
