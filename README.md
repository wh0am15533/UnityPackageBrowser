# Unity Package Browser (LITE) and Extractor

This is the LITE version. Your can browse a package file and extract it like it should be extracted. The assets are left untouched. You get the real thing, preserving script and asset hierarchy references. No more missing scripts on prefabs and shit.

The full version is forthcoming, it includes viewing assets directly within the app. You can view 3D models and interact with them, you can view any type of media asset, textures, etc, without extraction, and you can export models to a different format. It's great for previewing Unity Assets before importing into your project or mod. We all know that sometime's they fuck up your project somehow.

[UPDATE] I've posted a PREVIEW version of the FULL version on the release page along with some Demo unitypackages filled with assets. Be aware you WILL encounter errors as it is only a pre-release for preview purposes.

NOTE: There is no dependency on having Unity Editor installed. This is totally self-contained.

Extract the entire package or just checked items. You can use file streams (In-Memory extraction) or file based access which extracts to a Temp folder then deletes. Usings streams is alot faster, especially for large UnityPackage files.

## Why?

Because there isn't an existing reliable tool already. The closest you come is some Python script that's a bit outdated and SLOW.

## What about Resource files and AssetBundles?

Not yet. I'm currently implementing uTinyRipper into the app, so probably in the next update.

![preview](https://github.com/wh0am15533/UnityPackageBrowser/blob/master/Screens/Screenshot.png)
![preview](https://github.com/wh0am15533/UnityPackageBrowser/blob/master/Screens/Screenshot2.png)
![preview](https://github.com/wh0am15533/UnityPackageBrowser/blob/master/Screens/Screenshot3.png)
![preview](https://github.com/wh0am15533/UnityPackageBrowser/blob/master/Screens/Screenshot6.png)
![preview](https://github.com/wh0am15533/UnityPackageBrowser/blob/master/Screens/Screenshot4.png)
![preview](https://github.com/wh0am15533/UnityPackageBrowser/blob/master/Screens/Screenshot5.png)

## Credits:
VLC Media Player: https://github.com/videolan/vlc

Helix 3D Toolkit: https://github.com/helix-toolkit/helix-toolkit
