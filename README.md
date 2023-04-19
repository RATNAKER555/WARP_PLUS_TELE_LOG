# WARP_PLUS_TELE_LOG
This repository is for generating free GB's of data for WARP PLUS without any mod and posting the logs on telegram


If the input is via a file ensure the file is either .txt or .csv and it is in the following format:

.txt
WARP_CLIENT_ID =<your_id>
bot_token =<bot_token_value>
bot_chatID =<chat_ID>



.csv
WARP_CLIENT_ID,<your_id>
bot_token,<bot_token_value>
bot_chatID,<chat_ID>


To obtain your WARP_CLIENT_ID download the app on your mobile, go to the 3 sandwich icon on the top-right, then go to Advanced then Diagnostics. It will be right next to the public license key, long press on it and save it somewhere. Also ensure that the licence keys for both your pc and the mobile is same, if not go to preferences on WARP on your pc, then Account and tap on use a different key, now enter the same key as on your mobile device.


Follow this tutorial to create a custom bot using @BotFather on telegram:
https://medium.com/shibinco/create-a-telegram-bot-using-botfather-and-get-the-api-token-900ba00e0f39

To obtain the bot_chatID, follow the following URL on your browser:

https://api.telegram.org/bot<your-bot-token>/getUpdates (replace <your-bot-token> with your actual bot token)
