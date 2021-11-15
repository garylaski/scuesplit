# m4asplit
Split m4a files with a CUE sheet without re-encoding. Written in POSIX shell.

## Use
```
m4asplit audio.m4a cuefile.cue
```
The output will be in the format:
```
TRACKNUM - PERFORMER - TITLE.m4a
```
Example output:
```
01 - Bodyguard - HUM2ER.m4a
02 - Bodyguard - E-CIG.m4a
...
```
## Dependency
`ffmpeg`
