# highkey

Hacked together set of tools to replace lowkey.gg for my **specific** use case
of making and sharing very high quality game clips.

The video player is available in: `https://bd82.github.io/highkey/`

Note that a "vid" url parameter must be passed to this page, e.g:
- https://bd82.github.io/highkey/?vid=https://vjs.zencdn.net/v/oceans.mp4
- hotkeys are documented here: https://github.com/ctd1500/videojs-hotkeys#introduction

## The tools used

- Radeon replay / Nvidia ShadowPlay **for recording the clips**.

- [VidCutter](https://github.com/ozmartian/vidcutter) **for trimming/stitching clips**.
  - Note that VidCutter works faster / more stable when you disable `timeline thumbnails` and `frame accurate cutting`
    (options on the bottom left of its GUI),
  - 
- [DropBox](https://www.dropbox.com/) **to host the uncompressed videos**.
  - Note there are bandwidth limitations when using DropBox, which you can mitigate by upgrading your dropbox subscription:
    - https://help.dropbox.com/files-folders/share/banned-links
    - https://www.dropbox.com/individual/plans-comparison

- https://bd82.github.io/highkey/ for **video playback**
  - Because by default dropbox provides a low quality preview version for hosted video links.