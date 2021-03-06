# GLTFQuickLook
macOS QuickLook plugin for glTF files. (.gltf/.glb)

![ScreenShot](https://github.com/magicien/GLTFQuickLook/blob/master/screenshot.png)

![ScreenShot2](https://github.com/magicien/GLTFQuickLook/blob/master/screenshot2.gif)

## System Requirements

- macOS 10.13 (High Sierra) or later

## Install

### Using [Homebrew Cask](https://github.com/phinze/homebrew-cask)

- Run `brew cask install gltfquicklook`

### Manually

1. Download **GLTFQuickLook_vX.X.X.zip** from [Releases](https://github.com/magicien/GLTFQuickLook/releases/latest).
2. Put **GLTFQuickLook.qlgenerator** (in the zip file) into `/Library/QuickLook` (for all users) or `~/Library/QuickLook` (only for the logged-in user).
3. Run `qlmanage -r` command to reload QuickLook plugins.

### See also

- [GLTFSceneKit](https://github.com/magicien/GLTFSceneKit/)
