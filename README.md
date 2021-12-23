# AEModManager by hazel
Developed by hazelify as part of the JET / AE project. Designed to help fellow singleplayer games manage their mods easily without having to press a single key.

# Info
AEM is an AE exclusive app that allows the user to micro-manage, remove and install mods to their singleplayer server easily.

**This app is a WIP, and things may break.**

# Usage
Please install [7-Zip](https://www.7-zip.org/download.html) for extracting zipped folders, as WinRAR sometimes doesn't work.
## Extracting
Unpack `AE-ModManager-main.zip` somewhere you remember.

Right click -> `7zip` -> `Extract here` -> Drag and drop `AE-ModManager.exe` and `Newtonsoft.Json.dll` into your Server folder (where Server.exe is)

## Customizing / using
Double-click AE-ModManager.exe to launch the app. If you get [this message](https://imgur.com/a/tDP6af1) when opening the app, you've installed it wrong. Follow the Extracting section again.

On first run, `config.txt` and `modmanager.log` will be created. These are meant for a preset server path, enabling download links and logging.

* `config.txt` -> 
```
   AE-ModManager by hazelify
   
   Server Path:
   None
   
   Enable Download:
   False
```
   *Server Path* lets you decide which server to manage.
   
   *Enable download* is currently not available.
* `modmanager.log` -> 
```
   AE-MODMANAGER BY HAZELIFY
   [01:25:28 am][APP] Opened by user
   
```
   Logging will be rewritten to be more sophisticated and detailed in a future version.

**Name, author, description and version of mods can not be changed currently.**

# To-do list
**Wanted in future updates**:
* Edit metadata and config info via the app

# Versions
This acts both as a changelog and as a history. Only the latest version will be available for download. I do not provide support for older versions of my app.

## 1.0.0
* Initial release


# Credits
* hazelify (`*you're#7036` on Discord)
