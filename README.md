# 24/7 online Giveaways Bot

🎁Giveways Bot using the [discord-giveaways](https://npmjs.com/discord-giveaways) package!

This is a Moded Version of This code : https://github.com/Androz2091/giveaways-bot

## Features
Ready to Deploy to repl.it

## Commands

` g!start-giveaway <channel> <time> <winners> <prize> `
` g!reroll <message.id>  `
` g!end <message.id>  `


![enter image description here](https://cdn.discordapp.com/attachments/790688869665996820/790688956491890718/Screenshot_138.png)

## Install

* Clone repository:
```sh
git clone https://github.com/Nitr0Dev/GiveawayBot
```

* Fill configuration (config.json):

```json
  
{
    "token": "Your BOT Token",
    "prefix": "g!",
    "everyoneMention": true,
    "hostedBy": true
}

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
pm2 start index.js
```
