A discord bot that sends specific messages if certain commands are typed

The bot uses the [discord.io](https://izy521.gitbooks.io/discord-io/content/) api for discord bots. It requires [node.js](https://github.com/nodejs) 0.10.x or a higher version.

### Api Installation
Stable version ```npm install discord.io```

Latest version ```npm install izy521/discord.io```

### Node.js Installation
https://nodejs.org/en/download/

### Commands
```!ip``` will trigger
```
            case 'ip':
                bot.sendMessage({
                    to: channelID,
                    message: '[map link]'                    
```
```!store``` will trigger
```
            case 'store':
                bot.sendMessage({
                    to: channelID,
                    message: '[map link]'                    
```
```!map``` will trigger
```
            case 'map':
                bot.sendMessage({
                    to: channelID,
                    message: '[map link]'                    
```
