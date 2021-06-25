Stream youtube videos with VLC while keeping a local copy of the watched video without having to re-download. Also downloads the description and subtitles.

# Setup

First install vlc, ffmpeg and [youtube-dl](https://youtube-dl.org/).

Put `yw` and `yd` in your $PATH and make them executable.

Edit the path at the top of the scripts and ensure it exists.

You can also set some parameters like the desired resolution. Keep in mind that youtube sometimes offers higher resolutions only as separate video files with no audio and `youtube-dl` is not capable of combining separate video and audio files while streaming so you may end up with a lower resolution than expected.

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


