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

`client.sfw.getNekoImage();`      ->     Method to get SFW neko image from the API. \
`client.sfw.getKitsuneImage();`   ->     Method to get SFW kitsune image from the API. \
`client.sfw.getHoloImage();`      ->     Method to get SFW holo image from the API. \
`client.sfw.getChristmasImage();` ->     Method to get SFW christmas image from the API. \
`client.sfw.getMaidImage();`      ->     Method to get SFW maid image from the API. \
`client.sfw.getNekoparaImage();`  ->     Method to get SFW Nekopara image from the API. \

---

# ImageGen
> Documentation over ImageGen library methods.
