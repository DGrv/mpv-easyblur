## easycrop

A simple mpv script for manually blurring an aera of a video.

Based on [mpv-easycrop](https://github.com/aidanholm/mpv-easycrop).
Based on [mpv-easycrop](https://github.com/aidanholm/mpv-easycrop).
Based on [mpv-easycrop](https://github.com/aidanholm/mpv-easycrop).

- will create a new file 

### Installation

Place `easyblur.lua` in your `~/.mpv/scripts` or `~/.config/mpv/scripts` directory.

Install ffmpeg:

- via their website
- with chocolatey

```sh
choco install ffmpeg
```

### Usage

Press `c` to begin blurring. Click at one corner of the desired cropping
rectangle, and click a second time at the opposite corner.

ffmepg will then rename the original video with "_old" suffix and create a new video with the blur with the original name

If you wish to use a key other than `c` to blur, the keybind `easyblur` can be
changed in the lua script:

```sh
mp.add_key_binding("c", "easyblur", easyblur_activate)
```

### Example 

**Input:**

![](/assets/Input_easyblur_example..gif)

**Output:**

![](/assets/Output_easyblur_example..gif)

### License

GPLv3
