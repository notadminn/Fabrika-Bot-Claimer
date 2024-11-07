# Fabrika-Bot-Claimer
An automation bot for Fabrika Friends Factory that includes Auto Claim and Auto Farm functionalities. Simple setup for Windows users.
## Download the Latest Release

You can download the latest version of **Fabrika-Bot-Claimer** by clicking the button below:

<a href="https://github.com/notadminn/Fabrika-Bot-Claimer/releases/tag/v1.0.0" target="_blank">
  <img src="https://img.shields.io/badge/Download-v1.0.0-blue?style=for-the-badge" alt="Download Release">
</a>

## Features

- **Multi-account Support:** Automate actions across multiple accounts
- **Auto Complete Task** Automatically perform available quest
- **Configurable Settings:** Control various aspects of the script via a `config.json` file.
- **Static user agent**

## Configuration
Create a config.json file in the root directory with the following structure:
   ```json
{
    "account_delay": [5, 10],
    "cycle_delay": [1400, 2800]
}
   ```

`delay_account`: Delay between processing different accounts (in seconds) - the minimum and maximum values are taken randomly

`cycle_delay`: Delay between different cycles of operations (in seconds) - the minimum and maximum values are taken randomly

## How to get tgWebAppData (query_id / user_id)

1. Login telegram via portable or web version
2. Launch the bot
3. Press `F12` on the keyboard 
4. Open console
5. Сopy this code in Console for getting tgWebAppData (user= / query=):

```javascript
copy(Telegram.WebApp.initData)
```

6. you will get data that looks like this

```
query_id=AA....
user=%7B%22id%....
```
7. add it to `query.txt` file or create it if you dont have one

## Disclaimer

This bot is **private** and **for personal use only**. By using this bot, you acknowledge that you are doing so at your own risk. I am not responsible for any consequences, including but not limited to account bans, suspensions, or any other issues that may arise from using this bot.

Please be aware that the bot may be flagged by antivirus software due to the use of **PyInstaller** during the packaging process,  you may need to whitelist it in your antivirus software if it gets flagged.

Use the bot responsibly, and make sure you comply with the terms of service of any platform you interact with.


