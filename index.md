# Library
> `fluxpoint-py` is a library built in Python-3 by [kunosyn](https://github.com/kunosyn) made for easier interacting with the [Fluxpoint API](https://bluedocs.page/fluxpoint-api/).

Using this library you can get a variety of images and gifs, SFW and NSFW.

```python
from fluxpoint import FluxpointClient;
import asyncio;

client = FluxpointClient("token");

async def main():
    res = client.sfw.getNekoImage();
    print(res.file);
asyncio.run(main());
```

---

# NSFW
> Documentation over NSFW library methods.

---

# SFW
> Documentation over SFW library methods.


## SFW Image Methods


* `client.sfw.getNekoImage();`      ->     Method to get SFW neko image from the API. 
* `client.sfw.getKitsuneImage();`   ->     Method to get SFW kitsune image from the API. 
* `client.sfw.getHoloImage();`      ->     Method to get SFW holo image from the API. 
* `client.sfw.getChristmasImage();` ->     Method to get SFW christmas image from the API. 
* `client.sfw.getMaidImage();`      ->     Method to get SFW maid image from the API. 
* `client.sfw.getNekoparaImage();`  ->     Method to get SFW Nekopara image from the API. 
* `client.sfw.getAzurlaneImage();`  ->     Method to get SFW Azurlane image from the API. 
* `client.sfw.getSenkoImage();`     ->     Method to get SFW Senko image from the API. 
* `client.sfw.getDDLCImage();`      ->     Method to get SFW Doki Doki Literature Club image from the API. 
* `client.sfw.getWallpaperImage();` ->     Method to get SFW wallpaper image from the API. 
* `client.sfw.getAnimeImage();`     ->     Method to get SFW anime image from the API. 
* `client.sfw.getMemeImage();`      ->     Method to get SFW meme image from the API. 
* `client.sfw.getNoUImage();`       ->     Method to get No U image from the API. 
* `client.sfw.getPogImage();`       ->     Method to get pog image from the API. 
* `client.sfw.getCatImage();`       ->     Method to get random cat image from the API. 
* `client.sfw.getDogImage();`       ->     Method to get random dog image from the API. 
* `client.sfw.getLizardImage();`    ->     Method to get a random lizard image from the API. 


## SFW GIF Methods


---

# ImageGen
> Documentation over ImageGen library methods.
