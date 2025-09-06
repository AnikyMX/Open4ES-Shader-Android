# Open4ES Shader Android
Open4ES is a shader project for Minecraft: Java Edition on Android that uses the [GL4ES](https://github.com/PojavLauncherTeam/gl4es-114-extra) renderer.

- I provide shaders for **Adreno, Mali, and PowerVR GPUs**.
- Just a little bit to spruce up your Minecraft look :)
- To download the shader, you can check here [Release](https://github.com/ahmaf-gif/Open4ES-Shader-Android/releases).

# Supported Launchers
- Fold Craft Launcher
- Pojav Glow Worm
- Zalith Launcher
- Pojav Launcher
- Mojo Launcher
- Etc

# Known Issues
- On PowerVR and Mali GPUs, there are weird lines on the real-time shadows.
- On some devices that use a PowerVR GPU, performance can suddenly drop a lot.
- On some PowerVR devices, there's a bug: 'texture2D' doesn't work. The workaround is to switch from '#version 120' to '#version 150', which replaces 'texture2D' with just 'texture'.
- Please report if you find other bugs!

# More
This repository is inspired by [ENDERMANYK](https://github.com/Open4Es/Open4Es-Shader-Android).
