# scuesplit
Simple Cue Splitter. Split audio files via CUE sheet without re-encoding. Written in POSIX shell.

## Supported Audio formats
As far as I am aware, this should work with any audio formats that ffmpeg can split. I have confirmed it works with: `wav` `flac` `m4a` `mp3` `aac` `opus`

## Use
```
scuesplit audio.ext cuefile.cue
```
The output will be in the format:
```
TRACKNUM - PERFORMER - TITLE.ext
```
Example output:
```
01 - Bodyguard - HUM2ER.ext
02 - Bodyguard - E-CIG.ext
...
```
## Dependencies
`ffmpeg`

