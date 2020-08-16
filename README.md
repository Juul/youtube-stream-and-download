# Setup

First install mplayer, [youtube-dl](https://youtube-dl.org/) and ffmpeg.

Put `yw` and `yd` in your PATH and make them executable.

Edit the path at the top of the scripts and ensure it exists.

# Usage

To begin downloading and watching a video:

```
yw https://www.youtube.com/watch?v=uZkGudvjNzw
```

The description of all watched videos will be in `<download_dir>/watched`.

To delete the most recently watched video (e.g. because you canceled the download before it completed):

```
yd
```

# Notes

Tested with version `2020.07.28` of youtube-dl.

Subtitle display during streaming is not working in 1.3.0 but may work in later versions.


