# anishot
![PyPI](https://img.shields.io/pypi/v/anishot.svg)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/anishot.svg)
![PyPI - License](https://img.shields.io/pypi/l/anishot.svg)
![PyPI - Wheel](https://img.shields.io/pypi/wheel/anishot.svg)

Animates a long screenshot into a GIF. Use it to show off long screenshots in your GitHub README.

![clean look](https://user-images.githubusercontent.com/20287615/42131345-5e13bb52-7cb5-11e8-93d3-d448684dc1c5.gif)

## Install

```
$ pip install anishot
```

## Usage
```
$ anishot
Usage: 
anishot.__main__:
  --h: Window height
    (default: '0')
    (an integer)
  --inp: Input screenshot image
  --maxspeed: Max speed on scroll px/frame
    (default: '200')
    (an integer)
  --out: Output antimated GIF
  --pad: Padding on sides
    (default: '0')
    (an integer)
  --rgb_bg: Background color
    (default: '#ffffff')
  --rgb_outline: Screenshot outline color
    (default: '#e1e4e8')
  --rgb_shadow: Screenshot shadow color
    (default: '#999999')
  --rgb_window: Window outline color
    (default: '#e1e4e8')
  --shadow_size: Shadow size
    (default: '0')
    (an integer)
  --start_scale: Start scale
    (default: '0.5')
    (a number)
  --stops: List of stops for scrolling
    (default: '')
    (a comma separated list)
  --zoom_steps: Number of steps on initial zoom in
    (default: '7')
    (an integer)
  --zoom_to: Point to zoom to
    (default: '0')
    (an integer)
```

The anishot at the top of this README was generated by:
``anishot --inp=anishot.png --out=anishot.gif --h=450 --stops=290,640,940 --zoom_to=150 --start_scale=.7``

You can also experiment with styles. For example, you can go for a retro look:

``anishot --inp=anishot.png --out=anishot.gif --h=450 --stops=290,640,940 --zoom_to=150 --start_scale=.7 --pad=50 --shadow_size=5 --rgb_bg=#cccccc --rgb_window=#666666`` 

![retro look](https://user-images.githubusercontent.com/20287615/42131349-64488250-7cb5-11e8-863f-b3156e709ddc.gif)

## Contributing
Contributions are welcome!

[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/0)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/0)
[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/1)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/1)
[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/2)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/2)
[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/3)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/3)
[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/4)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/4)
[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/5)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/5)
[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/6)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/6)
[![](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/images/7)](https://sourcerer.io/fame/sergey48k/sourcerer-io/anishot/links/7)
