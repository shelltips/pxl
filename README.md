# pxl

pxl is a little hack to display images in the terminal.

### Installation

You will need to have [Go](https://golang.org) installed and configured in your path. Your terminal must have xterm-256color mode enabled.

`go get github.com/ichinaski/pxl`

### Usage

`pxl [-r whratio] filename`

where the optional flag `-r` sets the cursor's width/height ratio. This flag has a default value of 2.35, make sure you update it to match your terminal environment.

Close the image with `<ESC>`.

### Disclaimer

You may want to squint your eyes or take a few steps backwards when looking at the output.

### Examples


|  image  | pxl   |
|:--:|:--:|
|<img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/gh.png" height="250"> | <img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/gh.pxl.png" height="250"> |
|
|<img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/batman.jpg" height="250"> | <img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/batman.pxl.png" height="250"> |
|
|<img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/elvis.jpg" height="250"> | <img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/elvis.pxl.png" height="250"> |
|
|<img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/gd.jpg" height="250"> | <img src="https://raw.githubusercontent.com/ichinaski/pxl/master/img/gd.pxl.png" height="250"> |
