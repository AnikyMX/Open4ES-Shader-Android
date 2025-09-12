# Open4ES Shader Android
Open4ES is a shader project for Minecraft: Java Edition on Android that uses the [GL4ES](https://github.com/PojavLauncherTeam/gl4es-114-extra) renderer or OpenGL ES 2.

- Compatible with **Adreno, Mali, and PowerVR GPUs**.
- Makes your Minecraft look a little better :)
- The shader can be downloaded from the [Releases](https://github.com/AnikyMX/Open4ES-Shader-Android/releases) tab.

# Supported Launchers
- [Fold Craft Launcher](https://github.com/FCL-Team/FoldCraftLauncher)
- [Amethyst Launcher](https://github.com/AngelAuraMC/Amethyst-Android)
- [Pojav Glow Worm](https://github.com/Vera-Firefly/Pojav-Glow-Worm)
- [Zalith Launcher](https://github.com/ZalithLauncher/ZalithLauncher)
- [Pojav Launcher](https://github.com/PojavLauncherTeam/PojavLauncher)
- [HMCL Launcher](https://github.com/HMCL-dev/HMCL-PE)
- [Mojo Launcher](https://github.com/MojoLauncher/MojoLauncher)
- Etc

# Known Issues
- On PowerVR and Mali GPUs, there are weird lines on the real-time shadows.
- On some devices that use a PowerVR GPU, performance can suddenly drop a lot.
- Some devices with PowerVR GPUs have a problem when using the GL4ES Renderer: they can't read 'texture2D'. The fix is to change '#version 120' to '#version 150'. This stops using 'texture2D' and replaces it with 'texture'.
- Please report if you find other bugs!

# More
This project was inspired by the work within this [repository](https://github.com/Open4Es/Open4Es-Shader-Android).
