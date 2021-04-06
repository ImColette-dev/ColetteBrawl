# OldBrawl
Open source Python 3.8 Brawl Stars Server for version 12!
![ScreenShot](https://cdn.discordapp.com/attachments/728556050285985823/810416686771470336/Screenshot_20210214-094555_Brawl_Stars.jpg) 

## Setup
First you must install TweetNaCl. To do it use this command: ```python setup.py install```.
Now you can run server. If your OS is Windows just run main.py. If Linux type ```python3 main.py``` to terminal.

## Client
To connect to your server, you need a custom client. Here the only solution is to use a [pre-made client](https://drive.google.com/file/d/17P7LdvUn8yIjem_xaTHn-wB92RY6iGol/view?usp=sharing).
Just edit the IP in the frida-gadget config (```/lib/armeabi-v7a/libmrvitalik.config.so```)
```{"interaction":{"interaction":{"type":"script","path":"libmrvitalik.script.so","on_change":"reload","parameters":{"redirectHost":"YOUR_IP"}}}```


