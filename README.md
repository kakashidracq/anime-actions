[![npm](https://img.shields.io/npm/v/anime-actions.svg)](https://www.npmjs.com/package/anime-actions)
[![install size](https://packagephobia.now.sh/badge?p=anime-actions)](https://packagephobia.now.sh/result?p=anime-actions)


[![NPM](https://nodei.co/npm/anime-actions.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/anime-actions/)

## New version detail
- Fixed api links error
- Removed uglyBastard and added zettaiRyouiki

## Installation
```
npm i anime-actions
```
A package for multiple anime actions for discord.
Now with SFW and NSFW

## ACTIONS

| Actions |
| --- | ---  | 
| `baka`     |
| `blush`    |
| `cuddle`   |
| `bite`     | 
| `dance`    |
| `slap`     |
| `bonk`     |
| `bully`    |
| `hug`      |
| `kiss`     |
| `pat`      |
| `wallpaper`|
| `happy`    |
| `wink`     |
| `kill`     |
| `highfive` |
| `wave` | 
| `cry` |
| `smile` |
| `punch` |
| `kick` |
| `poke` |
| `goodnight` |
| `confused` |
| `sad` |
| `thinking` |
| `yes` |
| `yeet` |
| `stare` |
| `bored` |
| `scream` |
| `nervous` |

## Examples

Discord.js Example
```js
const { Client, Intents } = require('discord.js');
const kakashi = require('anime-actions');
const intents = new Intents(32767);

const client = new Client({ intents });

client.once('ready', () => {
	console.log('Ready to hug');
});
client.on('messageCreate', async(message) => {
    if(message.content === 'hug') {
        message.channel.send(await kakashi.hug())
    }
})
client.login('your-token');
```


Await/Async example
```js
const kakashi = require('anime-actions');
async function hug() {
  console.log(await kakashi.hug());
}

hug();
```

## Support Server

<a href="https://discord.gg/mTxBX87Bdr"><img src="https://discord.c99.nl/widget/theme-2/614018799212953611.png"/></a>

<a href="https://discord.gg/mTxBX87Bdr"><img src="https://invidget.switchblade.xyz/mTxBX87Bdr"/></a>

## Bots using this api

<a href="https://top.gg/bot/760923630212874251">
    <img src="https://top.gg/api/widget/760923630212874251.svg" alt="KAKASHI Bot" />
</a>

