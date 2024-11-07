# Fabrika-Bot-Claimer
An automation bot for Fabrika Friends Factory that includes Auto Claim and Auto Farm functionalities. Simple setup for Windows users.

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

