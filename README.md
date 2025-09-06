<img src="https://github.com/PojavLauncherTeam/PojavLauncher/blob/v3_openjdk/app_pojavlauncher/src/main/assets/pojavlauncher.png" align="left" width="60" height="80" alt="PojavLauncher logo">

# Open4ES Shader Android
Open4ES is a shader project for Minecraft: Java Edition on Android that uses the [GL4ES](https://github.com/PojavLauncherTeam/gl4es-114-extra) renderer.

- Compatible with **Adreno, Mali, and PowerVR GPUs**.
- Makes your Minecraft look a little better :)
- The shader can be downloaded from the [Releases](https://github.com/AnikyMX/Open4ES-Shader-Android/releases) tab.

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
This project was inspired by the work within this [repository](https://github.com/Open4Es/Open4Es-Shader-Android).
