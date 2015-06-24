# videotogif
A minimal bash script that converts a video to a gif.

This generates an optimized gif using ffmpeg and imagemagick, gifsicle.


## Usage
``` bash
videotogif source.mp4 > out.gif
```

Also you can use this as filter:

``` bash
cat source.mp4 | videotogif > out.gif
```

## Prerequisites
You need ffmpeg, imagemagick and gifsicle.

## Install
Put `videotogif` into your PATH.

``` bash
curl https://raw.githubusercontent.com/uiureo/videotogif/master/videotogif > ~/bin/videotogif
chmod a+x ~/bin/videotogif
```

## License
MIT
