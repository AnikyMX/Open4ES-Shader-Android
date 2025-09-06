# Open4ES Shader Android
This is a shader project that runs on **Minecraft Java Edition for Android** using [GL4ES](https://github.com/PojavLauncherTeam/gl4es-114-extra).

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
- There may be some strange lines in the shadows on some GPUs, especially Mali and PowerVR.
- There may be a drastic performance drop on some PowerVR GPUs (Due to Driver limitations).
- On some devices that use PowerVR GPUs, sometimes they cannot read "texture2D" so you have to work around it by changing "#version 120" to "#version 150" so you can use "texture"
- Please report if you find any other bugs!

# More
This repository is inspired by [ENDERMANYK](https://github.com/Open4Es/Open4Es-Shader-Android).
