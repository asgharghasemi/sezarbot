# [@sezarinfo](https://telegram.me/sezarinfo)


* * *


# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/asgharghasemi/sezarbot
cd sezarbot
chmod +x sezar.sh
./sezar.sh install
./sezar.sh 
# Enter a phone number & confirmation code.
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/asgharghasemi/sezarbot.git && cd sezarbot && chmod +x sezar.sh && ./sezar.sh install && ./sezar.sh
```

* * *

### launch Bot

```
killall -9 bash
cd ezarbot && killall screen && screen ./sezar.sh
```

* * *


### auto launch 
```
bi pv :)
@sezarinfo
```

* * *


### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    377450049,
    0,
    YourID
  }
