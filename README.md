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

## License
MIT
