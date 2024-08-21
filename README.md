<h1><ins>**Project reopen**</ins></h1>

```
 ______                   __         __              __
|   __ \.___.-.._____..__|  |.___.-.|  |__.._____. _|  |_
|    __/|  _  ||     ||  _  ||  _  ||  _  ||  _  ||_    _|
|___|   |___._||__|__||_____||___._||_____||_____|  |__|
Telegram UserBot - next generation link trading     
```
### Telegram UserBot - next generation link trading

100% Opensource.

Developer: Propapanda \
Testguru : Thomas 

Telegram Channel: https://t.me/PandaBot007

Pandabot use MadelineProto as Telegram Client Library: \
Telegram Channel: https://t.me/MadelineProto \
Documentation: https://docs.madelineproto.xyz/ \
Download: https://github.com/danog/MadelineProto \
Prereqiured: https://docs.madelineproto.xyz/docs/REQUIREMENTS.html 

Additonal needed: PHP Postgres Module, PHP Yaml Module, PostgreSQL Server, apache webserver, php-fpm proxy

> [!WARNING]
> Telegram allow only 2000 requests per hour! Config ur channels.conf be carefully! \
> Flood wait change the behavior of ur normal TG-Client(s), u can't send messages, view pictures, videos, and forwards are not allowed!
> or simple: u can do nothing... :-/ 

> [!WARNING]
> If a phone number is brand new, it will be closely monitored by Telegram for abuse, and it can even already be considered a bad user due to bad behavior from the previous owner of that phone number (which may happen often with VoIP or other easy-to-buy-online numbers, so expect fast ban)

> You may want to use your new phone number account with an official Telegram client and act like a normal user for some time (some weeks/months), before using it the bot.

Configuration: \
edit conf/pandabot.conf - database settings, recover forward queue, botcommand, webserver \
edit conf/channels.conf:

simple section conf: 
```
'uniqueName123':
 from: channelid1
 to:
  - channelid2
```

Start/ Stop: \
 ./bot.sh

