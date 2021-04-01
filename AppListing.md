# Listing of apps compiled and available for arm64

Not all builds provided here are official. 

# Web Browsers

### Chrome

Chrome is not available yet. The code is complete, however a disagreement between megacorps is preventing it from release.

**Workaround: ** Chromium has however been released. It is the engine Chrome is built on, is compatible with all Chrome extensions and such, and has the same UI.

Download available here: 
https://chromium.woolyss.com/#windows-on-arm


### Firefox

Released arm support as a beta, download it here:

https://www.mozilla.org/en-US/firefox/channel/desktop/#beta




# Electron Apps

## Web App Workaround

Many Electron apps haven't been updated. Here is an incredibly convenient workaround for this:
https://www.groovypost.com/howto/using-web-apps-new-chromium-edge-windows-10/

### Spotify

Spotify hasn't been updated. You can use the Edge Web App functionality as a workaround for native performance. 

### Discord

Discord hasn't been updated. You can use the Edge web app workaround mentioned above as a workaround.

# Development IDEs

### VS Code

https://code.visualstudio.com/docs/?dv=win32arm64user

# Development languages

### Python 

Python has been "unofficially" compiled for arm64. This build is automatically updated as the official one is. There is not much different about it from the official one, if anything.

Download it here

https://github.com/jay0lee/CPython-Windows-ARM64/releases

### OpenJDK

Two ways to go about this. 

#### Actual native windows JDK

https://github.com/microsoft/openjdk-aarch64/releases

#### Using WSL + JDK for arm linux

I consider this a hack. But if it works, it works. I haven't been able to get WSL to run myself. 

This is a guide on how to do it for IntelliJ IDEs: https://www.mdoninger.de/2020/06/06/use-intellij-on-surfacexpro.html



### Go

Unofficial. Version 1.16 was compiled here, download from Releases tab. 

I don't know Go, and as such can't speak to the quality of this fork. Someone who does is free to PR their opinion on it here.

https://github.com/thongtech/go-windows-arm

### Node (node.js)

Only reason this build isn't listed with the rest is lack of a reliable machine to produce arm builds with every update.

https://unofficial-builds.nodejs.org/download/release/v15.8.0/

### PHP

I was able to find next to nothing about a native php build for WoA. 

TODO: test PHP running in WSL



# Tools

### 7zip

7zip has released an official alpha build here:
https://7-zip.org/a/7z2100-arm64.exe

### Filezilla

Filezilla ported to WOA by driver1998

https://github.com/driver1998/filezilla-woa/releases/download/v3.48.0/filezilla-aarch64-v3.48.0.exe

### TightVNC

https://github.com/driver1998/tightvnc-gpl-woa/releases/download/v2.8.11/tightvnc-2.8.11-gpl-win-arm64.zip