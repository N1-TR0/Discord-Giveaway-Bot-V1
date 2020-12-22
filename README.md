# Giveaways Bot

🎁Giveways Bot using the [discord-giveaways](https://npmjs.com/discord-giveaways) package!

## Features

Note: It Works only on => { "discord-giveaways": "^2.4.4"}
If the number of votes is less than 3 votes, it will appear that there is no winner

$gcreate <time> <winners> <prize>
$greroll <message.id> 
$gedit <message.id>  
$gend <message.id>  


![enter image description here](https://cdn.discordapp.com/attachments/790688869665996820/790688956491890718/Screenshot_138.png)

## Install

* Clone repository:
```sh
git clone https://github.com/Nitr0Dev/GiveawayBot
```

* Fill configuration (index.js):
**go to Line 26**
```json
const giveaways = require("discord-giveaways"),
settings = {
    prefix: "!g", // Your Prefix You Want
    token: ""
```
**go to line 161**
```json
go to line 161
client.login("Your BOT Token");

```

* Install dependencies:
```sh
npm install
```

* Start:
```sh
node index.js
```
* Start For VPS:
```sh
P2M start index.js
```
