# mpv-roughcut
My personal configuration of mpv plugins from [User-Scripts](https://github.com/mpv-player/mpv/wiki/User-Scripts) to expedite rough cutting of media.

*scripts/encode.lua* has been modified so that the `ffmpeg` call accomodates for just cutting audio.

## Bindings
| Keybind | Description |
| :---: | --- |
| Ctrl+t | Go to specific time |
| Ctrl+del | Mark video for deletion upon close |
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

## Use
Clip the video in mpv using either `e` or `E` at the beginning of the cut, then pressing `enter` once you have seeked to the end of the cut. Follow that up with `Ctrl+del` to mark the video for deletion. Move to the next video in the playlist.<br/>
Cut videos will have the same filename as the original with the addition of '_1' before the extension.<br/>
Closing mpv will delete all the videos marked for deletion in the playlist, obviously keeping the cut videos.
