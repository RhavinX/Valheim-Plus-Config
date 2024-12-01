# Valheim-Plus-Config

The docker container being used is:\
Github page: https://github.com/lloesche/valheim-server-docker \
Docker Hub: https://hub.docker.com/r/lloesche/valheim-server

Plugins on the Server and Client.\
Plugins for the client are installed manually, not through Vortex client.

Client plugins are installed in:\
Windows - `{DRIVE:}\Program Files (x86)\Steam\steamapps\common\Valheim\BepInEx\plugins`\
Linux - `/path/to/SteamLibrary/steamapps/common/Valheim/`
- Grantapher's Valheim Plus bundled with BepInEx: https://www.nexusmods.com/valheim/mods/2323?tab=description  
Or you can download the following 2 items if you want to install Grantapher's Valheim Plus and BepInEx seperately.
- BepInExPack Valheim: https://thunderstore.io/c/valheim/p/denikson/BepInExPack_Valheim
- ValheimPlus Grantapher Temporary: https://thunderstore.io/c/valheim/p/Grantapher/ValheimPlus_Grantapher_Temporary
- ImFRIENDLY DAMMIT: https://thunderstore.io/c/valheim/p/Azumatt/ImFRIENDLY_DAMMIT
- XPortal: https://www.nexusmods.com/valheim/mods/2239
- Gungnir: https://www.nexusmods.com/valheim/mods/1921
- Jotunn: https://www.nexusmods.com/valheim/mods/1138
- Seafloor Walking Boots: https://www.nexusmods.com/valheim/mods/1580
- OCDheim: https://thunderstore.io/c/valheim/p/Vapok/OCDheim - Currently broken with latest Valehim

Server plugins:\
There should be no need to copy `ValheimPlus.dll` to the server as it will be downloaded and installed onto the server by specifying it\
in the environment variables, and it will automatically be put into the correct location:\
`VALHEIM_PLUS=true`\
`VALHEIM_PLUS_REPO=Grantapher/ValheimPlus`\
`VALHEIM_PLUS_RELEASE=tags/0.9.15.0`

`valheim_plus.cfg` will be put in `path/to/data/valheim/config/valheimplus`\
Edit `valheim_plus.cfg` if you want to customize it to your preference.\
The rest of the plugins should go into `path/to/data/valheim/data/plus/BepInEx/plugins`
- XPortal: https://www.nexusmods.com/valheim/mods/2239
- Gungnir: https://www.nexusmods.com/valheim/mods/1921
- Jotunn: https://www.nexusmods.com/valheim/mods/1138
- Seafloor Walking Boots: https://www.nexusmods.com/valheim/mods/1580
- OCDheim: https://thunderstore.io/c/valheim/p/Vapok/OCDheim  - Currently broken with latest Valehim
