# Valheim-Plus-Config

Plugins on the Server and Client.

Plugins for the client are installed manually, not through Vortex client.\
Client plugins are installed in: `{DRIVE:}\Program Files (x86)\Steam\steamapps\common\Valheim\BepInEx\plugins`\
Client plugins:
- ValheimPlus Grantapher Temporary: https://thunderstore.io/c/valheim/p/Grantapher/ValheimPlus_Grantapher_Temporary
- ImFRIENDLY DAMMIT: https://thunderstore.io/c/valheim/p/Azumatt/ImFRIENDLY_DAMMIT
- Seafloor Walking Boots: https://www.nexusmods.com/valheim/mods/1580
- OCDheim: https://thunderstore.io/c/valheim/p/Vapok/OCDheim
- Jotunn: https://www.nexusmods.com/valheim/mods/1138
- Gungnir: https://www.nexusmods.com/valheim/mods/1921


Server plugins:\
There should be no need to copy `ValheimPlus.dll` as it will be download and installed onto the server by specifying it\
in the environment variables, and it will automatically be put into the correct locations:\
VALHEIM_PLUS=true\
VALHEIM_PLUS_REPO=Grantapher/ValheimPlus\
VALHEIM_PLUS_RELEASE=tags/0.9.13.0 <-- version for Ashlands update.\

`valheim_plus.cfg` will be put in `path/to/data/valheim/config/valheimplus`\
The rest of the plugins should go into `path/to/data/valheim/data/plus/BepInEx/plugins`
- XPortal: https://www.nexusmods.com/valheim/mods/2239
- Gungnir: https://www.nexusmods.com/valheim/mods/1921
- Jotunn: https://www.nexusmods.com/valheim/mods/1138
- OCDheim: https://thunderstore.io/c/valheim/p/Vapok/OCDheim
