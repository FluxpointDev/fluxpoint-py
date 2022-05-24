<link rel="shortcut icon" type="image/x-icon" href="https://fluxpoint.dev/img/icons/fluxpoint.png">
# Library
> `fluxpoint-py` is a library built in Python-3 by [kunosyn](https://github.com/kunosyn) made for easier interacting with the [Fluxpoint API](https://bluedocs.page/fluxpoint-api/).

Using this library you can get a variety of images and gifs, SFW and NSFW.

```python
from fluxpoint import FluxpointClient;
import asyncio;

client = FluxpointClient("token");

async def main():
    res = client.sfw.getNekoImage();
    
    if res.success:
        print(res.file);
asyncio.run(main());
```

---

# NSFW
> Documentation over NSFW library methods. \
*Not documented yet...*

---

# SFW
> Documentation over SFW library methods.


### SFW Image Methods


* `client.sfw.getNekoImage(self);` -> Method to get SFW neko image from the API. 
* `client.sfw.getKitsuneImage(self);` -> Method to get SFW kitsune image from the API. 
* `client.sfw.getHoloImage(self);` -> Method to get SFW holo image from the API. 
* `client.sfw.getChristmasImage(self);` -> Method to get SFW christmas image from the API. 
* `client.sfw.getMaidImage(self);` -> Method to get SFW maid image from the API. 
* `client.sfw.getNekoparaImage(self);` -> Method to get SFW Nekopara image from the API. 
* `client.sfw.getAzurlaneImage(self);` -> Method to get SFW Azurlane image from the API. 
* `client.sfw.getSenkoImage(self);` -> Method to get SFW Senko image from the API. 
* `client.sfw.getDDLCImage(self);` -> Method to get SFW Doki Doki Literature Club image from the API. 
* `client.sfw.getWallpaperImage(self);` -> Method to get SFW wallpaper image from the API. 
* `client.sfw.getAnimeImage(self);` -> Method to get SFW anime image from the API. 
* `client.sfw.getMemeImage(self);` -> Method to get SFW meme image from the API. 
* `client.sfw.getNoUImage(self);` -> Method to get No U image from the API. 
* `client.sfw.getPogImage(self);` -> Method to get pog image from the API. 
* `client.sfw.getCatImage(self);` -> Method to get random cat image from the API. 
* `client.sfw.getDogImage(self);` -> Method to get random dog image from the API. 
* `client.sfw.getLizardImage(self);` -> Method to get a random lizard image from the API. 


### SFW GIF Methods


* `client.sfw.getBakaGif(self);` -> Method to get a baka gif from the API.
* `client.sfw.getBiteGif(self);` -> Method to get a bite gif from the API.
* `client.sfw.getBlushGif(self);` -> Method to get a blush gif from the API.
* `client.sfw.getCryGif(self);` -> Method to get a blush gif from the API.
* `client.sfw.getDanceGif(self);` -> Method to get a dance gif from the API.
* `client.sfw.getFeedGif(self);` -> Method to get a feed gif from the API.
* `client.sfw.getFluffGif(self);` -> Method to get a fluff gif from the API.
* `client.sfw.getGrabGif(self);` -> Method to get a grab gif from the API.
* `client.sfw.getHandholdGif(self);` -> Method to get a hand holding gif from the API.
* `client.sfw.getHighfiveGif(self);` -> Method to get a highfive gif from the API.
* `client.sfw.getKissGif(self);` -> Method to get a kiss gif from the API.
* `client.sfw.getLickGif(self);` -> Method to get a lick gif from the API.
* `client.sfw.getNekoGif(self);` -> Method to get a neko gif from the API.
* `client.sfw.getPatGif(self);` -> Method to get a pat gif from the API.
* `client.sfw.getPokeGif(self);` -> Method to get a poke gif from the API.
* `client.sfw.getPunchGif(self);` -> Method to get a punch gif from the API.
* `client.sfw.getShrugGif(self);` -> Method to get a shrug gif from the API.
* `client.sfw.getSlapGif(self);` -> Method to get a slap gif from the API.
* `client.sfw.getSmugGif(self);` -> Method to get a smug gif from the API.
* `client.sfw.getStareGif(self);` -> Method to get a stare gif from the API.
* `client.sfw.getTickleGif(self);` -> Method to get a tickle gif from the API.
* `client.sfw.getWagGif(self);` -> Method to get a wag gif from the API.
* `client.sfw.getWastedGif(self)`; -> Method to get a wasted gif from the API.
* `client.sfw.getWaveGif(self);` -> Method to get a wave gif from the API.
* `client.sfw.getWinkGif(self);` -> Method to get a wink gif from the API.

---

# ImageGen
> Documentation over ImageGen library methods. \
*Not documented yet...*
