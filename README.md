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

This bot is **for personal use only** and is intended solely for the creator. By using this bot, you acknowledge that you are solely responsible for any consequences that may arise, including but not limited to account bans, restrictions, or any other issues resulting from its use.

I am **not responsible** for any damage, loss of access, or violations that may occur while using this bot. By running the bot, you accept the risks and understand that you are using it at your own discretion. It is recommended to use this bot only on accounts that are not critical and that you are willing to risk.

Use at your own risk.

