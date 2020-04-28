# color_names_list
[![Gem Version](https://badge.fury.io/rb/color_names_list.svg)](https://badge.fury.io/rb/color_names_list)

Ruby wrapper for Massive color dictionary 🌈 [https://meodai.github.io/color-names/](https://meodai.github.io/color-names/)

Current release based on csv file from 'color-names' v5.17.0
[https://github.com/meodai/color-names/blob/master/src/colornames.csv](https://github.com/meodai/color-names/blob/master/src/colornames.csv)

## Install

```
gem install color_names_list
```
## Usage

```
require 'color_names_list'

# You can use 3 and six digits hex code with or without #

ColorNamesList.show_color_name("#ff0000")
=> "Red"

ColorNamesList.show_color_name("ff0000")
=> "Red"

ColorNamesList.show_color_name("#f00")
=> "Red"

ColorNamesList.show_color_name("f00")
=> "Red"

# You can get random color name

ColorNamesList.show_random
=> "Yanagicha"

```
## License

Create homepage with demo

## License

MIT
