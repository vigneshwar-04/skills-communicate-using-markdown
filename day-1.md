# Daily Learning

## Morning Planning

<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="200" align="right">

## Review

Convert an image or video from dark mode to light mode using ffmpeg.

```bash
ffmpeg -i input.mp4 -vf "negate,hue=s=0,eq=contrast=1.2:saturation=1.1" output.mp4
