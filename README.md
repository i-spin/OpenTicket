# OpenTicket
Readme in progress.....  
Bot Development in heavy development.....

### To run the bot:
Create a config.json file, containing your token and desired prefix:
```json5
{
  "token": "",
  "prefix": "'",
  "disallowInThreads": true, // Bot does not respond commands in threads
  "disallowBotMessages": true // Bot does not respond commands sent by other bots
}
```
Then run:
```shell
yarn build
yarn start
```
