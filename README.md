# GMCP AI background images

## Install

```
lua installPackage("https://github.com/vadi2/GMCP-AI-background-images/raw/main/GMCP%20AI%20background%20images.mpackage")
```

## Use

Draws background images using StableHorde AI network as you walk around in a GMCP-enabled game. Requires room descriptions to be available in `gmcp.Room.Info.desc` to work.

To make image generation go quicker, register an account at https://stablehorde.net, obtain an API key, and create a new script in Mudlet with the following code:

```
STABLEHORDE_APIKEY = "<key here>"
```

Doing so will give your images a bit more priority. To increase it further, read about the kudos system on https://stablehorde.net.
