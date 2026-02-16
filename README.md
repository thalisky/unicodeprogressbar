
# Unicode Progress-Bar

A unicode progress-bar generator


## Features

- Strictly typed
- Customizable
- Lightweight


## Installation

Install unicodeprogressbar using Wally

```sh
wally add thalisky/unicodeprogressbar
```

Install unicodeprogressbar using Pesde

```sh
pesde add thalisky/unicodeprogressbar
```
    
## Usage

```luau
local uniprogressbar = require(path.to.unicodeprogressbar)

uniprogressbar.generateBar(71, 0, 100, 32, "MINIMAL")
--[[ RETURNS:
    █████████████████████▊░░░░░░░░░░░
]]
```
## License

[Unicode Progress-Bar Generator](https://github.com/thalisky/unicodeprogressbar)© 2024 by [thalisky](https://github.com/thalisky/) is licensed under [CC BY-SA 4.0 ![|20x20](upload://qFxLsmeYlZmZPDkUZy6ZBItKmmg.svg)![|20x20](upload://zRUvWIXkFRjiUcdQ7zsLxaNTXgW.svg)![|20x20](upload://ix5eihYREmVZjZmGBtYTnaLqFSr.svg)](https://creativecommons.org/licenses/by-sa/4.0/?ref=chooser-v1)
## API Reference

#### Generate a progress-bar
```luau
uniprogressbar.generateBar(
        value: number,
        minRangeValue: number,
        maxRangeValue: number,
        length: number,
        background_blocks: ("NONE" | "TRANSPARENT" | "MINIMAL" | "MEDIUM" | "MEDIUM_REVERSED" | "FULL")
    ): string
```
