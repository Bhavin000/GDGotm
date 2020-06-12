<p align="center"><a href="https://gotm.io"><img src="https://imgur.com/mc8HAgS.png" alt="gotm.io" ></a></p>
<p align="center">Access Gotm's API with GDScript</p>
<p align="center"><a href="https://gotm.io/about/plugin>Learn more</a></p>

# Install

_Supports versions 3.1.0 and newer._

## 1. Download

Download the plugin from the [AssetLib](https://docs.godotengine.org/en/stable/tutorials/assetlib/using_assetlib.html#in-the-editor) in the Godot Editor and follow its instructions.

You can also download it directly [here](https://github.com/PlayGotM/GDGotm/archive/master.zip). Extract the contents into your project's directory.

## 2. Setup

Add Gotm.gd to your autoloads at "Project Settings -> AutoLoad". Make sure the global autoload is named "Gotm". It must be named "Gotm" for it to work.

# Notes

This plugin serves as a polyfill when developing against the API locally.
The "real" API calls are only available when running the game live on gotm.io.
