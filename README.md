# 

## Overview

stocksTUI is designed for anyone who prefers to keep an eye on the stock market from the comfort of their terminal. It provides a quick overview of your favorite stocks, indices, and cryptocurrencies, along with detailed historical data and the latest news.

## Features

-   **Real-time* Price Data:** Monitor stock prices, daily change, and ranges. (* Fetched via API, may have delays)
-   **Customizable Watchlists:** Organize your symbols into different lists (e.g., tech stocks, crypto, indices).
-   **Historical Data:** View historical performance with charts and data tables.
-   **Ticker News:** Stay updated with the latest news for any symbol.
-   **Theming:** Customize the look and feel with multiple built-in themes.
-   **Configurable:** Adjust refresh rates, default tabs, and more.


## Keybindings

| Key             | Action                        | Context      |
| --------------- | ----------------------------- | ------------ |
| `q`             | Quit the application          | Global       |
| `r`             | Refresh current view          | Global       |
| `R` (`Shift+r`) | Refresh all lists in background | Global       |
| `s`             | Enter Sort Mode               | Price/History |
| `?`             | Toggle Help Screen            | Global       |
| `/`             | Search in current table       | Tables       |
| `1-0`           | Switch to corresponding tab   | Global       |
| `h, j, k, l`    | Navigate / Scroll             | All          |
| `Up, Down`      | Navigate / Scroll             | All          |
| `Left, Right`   | Navigate                      | All          |
| `Tab, Shift+Tab`| Focus next/previous widget    | Global       |
| `Enter`         | Select / Action               | All          |
| `Esc`           | Close dialog/search, exit sort mode, or focus tabs | Global |

In Sort Mode (after pressing `s`):

| Key | Action               | Context       |
| --- | -------------------- | ------------- |
| `d` | Sort by Description/Date | Price/History |
| `p` | Sort by Price        | Price         |
| `c` | Sort by Change/Close | Price/History |
| `e` | Sort by % Change     | Price         |
| `t` | Sort by Ticker       | Price         |
| `u` | Undo Sort            | Price         |
| `H` | Sort by High         | History       |
| `L` | Sort by Low          | History       |
| `v` | Sort by Volume       | History       |

## Configuration

User-specific configuration files are stored in `~/.config/stockstui/`. You can edit `lists.json` to manage your watchlists or `settings.json` for application settings. The application must be restarted for changes to `lists.json` to take effect.

