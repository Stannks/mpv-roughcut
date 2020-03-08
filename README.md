# mpv-roughcut
My personal configuration of mpv plugins from [User-Scripts](https://github.com/mpv-player/mpv/wiki/User-Scripts) to expedite rough cutting of media.

*scipts/encode.lua* has been modified so that the ffmpeg call accomodates for just cutting audio.

## Bindings
| Keybind | Description |
| :---: | --- |
| Ctrl+t | Go to specific time |
| e | Starting point of rough cut with profile encode_va |
| E | Starting point of rough cut with profile encode_a |
| W | Activate webm maker |
| Alt+g | Set gif start |
| Alt+G | Set gif end |
| g | Toggle contact sheet |
| c | Toggle playlist view |

\* Hit *enter* for the end point and to start encoding for all *encode.lua* bindings.

*encode_va* roughcut with audio and video.
*encode_a* roughcut with only audio.