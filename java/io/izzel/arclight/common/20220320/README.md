[Look out the issue thread](https://github.com/IzzelAliz/Arclight/issues/524)

This is a copy of the markdown of the issue, with some more demonstration.

----

Latest Update:

- **timi137137** added [bug] [plugin] [1.18] and removed [Triage] labels: 20220323

----

### I have confirmed that ...

- [X] Arclight is up to date
> Using the latest release of 1.18.1 that is the latest build
- [X] all dependencies are installed
> WorldEdit with ArclightPatcher, which one is required more?
- [X] all plugins and mods are up to date
> Using latest release from GitHub
- [X] unable to reproduce in Spigot
> WorldEdit is released under testing with Spigot and Paper
- [X] unable to reproduce in Forge
> No additional Forge mods installed

### Additional requirements I've made:

- [x] I've read the FAQ
> In FAQ they say you **should** install ArclightPatcher, and **I DID**

### Arclight version

arclight-1.18.1-1.0.1-e2655bb

### OS & Java versions

 openjdk version "17" 2021-09-14 LTS<br>
 OpenJDK Runtime Environment Zulu17.28+13-CA (build 17+35-LTS)<br>
 OpenJDK 64-Bit Server VM Zulu17.28+13-CA (build 17+35-LTS, mixed mode, sharing)

### Plugins and Mods

```raw
> plugins
[19:46:26 INFO] [Console]: Plugins (2): ArclightPatcher, WorldEdit
> forge mods
[19:46:28 INFO]: Mod List:
• minecraft server-1.18.1-20211210.034407-srg.jar : minecraft (1.18.1) - 1
• minecraft forge-1.18.1-39.1.2-universal.jar : forge (39.1.2) - 1
• arclight arclight-1.18.1-1.0.1-e2655bb.jar : arclight (1.18.1-1.0.1-e2655bb) - 1
>
```


### Description

On FAQ, IF ArclightPatcher(Plugin) is installed WorldEdit should work, but it doesn't work entirely on Arc 1.18 with latest WE.

On bootup:
![image](https://user-images.githubusercontent.com/34373595/159158689-a4fe01e6-ad13-4834-96fd-c3d08ac350e7.png)

On editing:
![image](https://user-images.githubusercontent.com/34373595/159158598-db192d62-2dcf-48a2-b035-e112b8a7881d.png)


### Step to reproduce

1. Install Arclight.
> Hint: If not installing correctly, please download Forge Installer 39.1.2 in the same directory.
2. Put the latest WorldEdit-Bukkit and ArclightPatcher Loader plugins into `plugins` directory.
3. Boot the server. WE will stop operating when the server starts. (They don't be shown as RED ![image](https://user-images.githubusercontent.com/34373595/159158671-146f24d5-8fae-4d54-b661-da5aa0b51823.png) but they still throws an error)

### Logs

[forge-1.18.1-39.1.2-installer.jar.log](https://github.com/IzzelAliz/Arclight/files/8311039/forge-1.18.1-39.1.2-installer.jar.log) for the Forge Installer Log

[latest.log](https://github.com/IzzelAliz/Arclight/files/8311053/latest.log) for the Arclight Fallback Log

[mclo.gs PasteBin](https://mclo.gs/my7D1gr) for the Arclight Fallback Log with analizer(published).

### Server pack link (Optional)

_No response_
