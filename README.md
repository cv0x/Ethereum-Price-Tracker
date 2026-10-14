# Ethereum Price Tracker for Wallpaper Engine
A dynamic wallpaper for Wallpaper Engine that displays the current price of Ethereum (USD) and a 7-day price chart. The appearance can be customized directly in the Wallpaper Engine properties panel.
- [Project on Steam](https://steamcommunity.com/sharedfiles/filedetails/?id=3252688975)
- [Project example](https://cv0x.github.io/Ethereum-Price-Tracker/)

![ETH price wallpaper](https://steamuserimages-a.akamaihd.net/ugc/2491132166132214784/BCEB7841154472E9408964DEFB8655AB375AB660/?)

## Description

This project creates a customizable wallpaper for the [Wallpaper Engine](https://store.steampowered.com/app/431960/Wallpaper_Engine/) program, displaying the real-time Ethereum (ETH) price in USD and a 7-day price chart. Data is loaded from the [CoinGecko API](https://www.coingecko.com/en/api) every 60 seconds and the chart is drawn from its 7-day sparkline data.

## Usage

1. Log in to Steam in your browser.
2. Subscribe to this [ETHEREUM WALLPAPER](https://steamcommunity.com/sharedfiles/filedetails/?id=3252688975).
3. Open Wallpaper Engine and select the wallpaper in the Installed tab.
4. Customize it in the properties panel on the right side of Wallpaper Engine (changes apply instantly).

## Customization Options

All options are defined in [project.json](project.json) as Wallpaper Engine user properties and are received in [app.js](app.js) via `window.wallpaperPropertyListener`.

| Property | Options | Default |
|---|---|---|
| Font | Poppins, Roboto, Playfair, Poetsen, Cursive, Sans-serif, Monospace | Poppins |
| Price color | Custom color, Interactive (7d trend), Ethereum color presets | Custom color (black) |
| Logo & card shadow | Off, Custom color, Interactive (7d trend), Ethereum color presets | Interactive |
| Logo color | Any color | Ethereum blue |
| Card color | Any color | Light brown |
| Background | Gradient presets, Custom colors | Ocean Teal |
| Background color 1 / 2 | Any color (only with Custom colors) | Blue / teal |
| Show 7-day chart | On / Off | On |
| Size | 50 – 250 % | 100 % |
| Horizontal / vertical position | -45 – 45 % of the screen | 0 (center) |

### Ethereum color presets
Ethereum Blue, Ether Indigo, Merge Purple, Diamond Silver, Gwei Gold, Gas Fee Red, Staking Green, Smart Contract Cyan, Ultrasound Orange, Whitepaper White, Cold Wallet Black.

### Background gradient presets
Ocean Teal, Ethereum Night, Merge Purple, Cosmic Fusion, Sunset, Aurora, Royal Blue, Crimson Night, Gwei Gold, Mint Forest, Deep Space.

### Interactive color
Price color and shadow can follow the 7-day trend. They use the same color as the chart line: green when the price is higher than 7 days ago, red when it is lower.

## Support the creator
Hover over the small heart in the top left corner to show the ETH QR code.
