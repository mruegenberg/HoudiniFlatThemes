# Houdini Flat Themes

Flat themes for Houdini, to be easier on the eye.

## Screenshots

Dark:
![Dark](./screenshots/dark.png)

Light:
![Light](./screenshots/light.png)

Modo Style, inspired by the Modini theme posted on the SideFX forums. To get the viewport in the right style, use the `3DSceneColors.bw` file taken from the [Modini theme](https://www.sidefx.com/forum/topic/82081/) and set your viewport background color to grey.

![ModoStyle](./screenshots/modostyle.png)

## Installation

Copy the `*.inc` and `*.hcs` files to the `config` subfolder (you can just create it if it's not there yet) in your Houdini user folder (typically `$HOME/houdini19.5` or similar). 

To get a modo-style (darker) grey background, add the `*.bw` file as well. This can then be used by going to the display options in the Viewport and chosing the Grey background.

## Usage

Copy the files to install, then go to Edit > Color Settings and choose the new theme from the dropdown.

## Status

These themes are very usable, but probably an ongoing work in progress.

Some cleanup would be needed, as the themes probably contain a lot of uneeded lines. Also, additional comments to aid in identifying which UI element corresponds to what are needed.
