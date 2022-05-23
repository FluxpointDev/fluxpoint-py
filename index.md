# Index
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
