# Cybrancee Hosting Guide (extremely cheap alterative to self hosting on your own device)

🔹 Head over to https://cybrancee.com/discord-bot-hosting and select **Starter.**
It's more than enough to host any of the bots. 

🔹 Select a server location and Discord bot language. Continue to place your order.

**Bot languages**
```
Pi Tracker and Cryptocurrency Tracker: NodeJS
Member of the Week, Question of the Day, and Voyager: Python
```

🔹 Once you've placed your order you will get a confirmation email and be asked to create a panel account. Download the GitHub repository if you haven't already and unzip the folder. You can head to https://cybrancee.com/client/getting-started/how-to-host-a-discord-bot.php and come back to this guide once you've reached step 8. 

🔹 Your Docker image shouldn't need to be changed, as the most previous version is usually the default.

**Minimun version requirements**
```
Node.JS 16+ 
Python 3.12+
```


🔹 Enter the corresponding bot startup file

**Bot startup files**
```
Pi Tracker & Cryptocurrency Tracker: index.js

Member of the Week: index.py

Question of the Day: main.py

Voyager: bot.py
```

🔹 Add dependencies. 

**Only copy and paste the text following the colon ":" For example, "discord.js dotenv axios" for Pi Tracker.**
```
Pi Tracker & Cryptocurrency Tracker: discord.js dotenv axios

Member of the Week: discord.py python-dotenv apscheduler

Question of the Day: discord.py python-dotenv

Voyager: discord.py python-dotenv aiosqlite yfinance
```

🔹 Make sure you've configured `.env-example` and renamed it to `.env` then you can go to the Console page and start your bot.