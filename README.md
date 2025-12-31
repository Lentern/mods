# The Best Performance (and Quality-of-Life) Mods for Minecraft 1.21

This is the most up-to-date list of the mods that I personally use while playing Minecraft. From tripling performance to revamping menus, these mods improve your gameplay experience without changing vanilla gameplay.

Want my mod configs? [Here you go](https://drive.google.com/file/d/1amMFKcRSWMBUf3ZmyKpcby5JMFJUhL8b/view).

## You must install [Fabric](https://fabricmc.net) to run these mods

Don't know how? Watch [my tutorial](https://youtu.be/eF_uPVLCG-E?t=45).

# FAQ

### My game is crashing, what's going on?

- If you get a crash any time you load a world or join a server, remove the Chat Patches mod. If that fixes it, add the mod back and then delete the file "chatlog.json" file in _.minecraft\logs_. This will reset your chat history and fix the crash. If this doesn't fix it, start removing mods, half of them at a time, until you find the culprit, and then get googling or leave a comment on my video about which mod it is.

### Will these mods affect/break my builds/redstone/farms/gameplay?

- In theory, no. I made this list with the goal of staying true to vanilla while also improving the experience. If you notice an issue with your world, start removing mods, half of them at a time, until you figure out which mod is causing an issue, and report the issue to the mod developers (or check if it has already been reported or fixed in a newer version ). It could also be a setting within the mod that should have been toggled, and was unintentionally impeding your experience. To avoid this, use my mod configs, linked above.

# Mods

## Performance Mods
- [AsyncParticles](https://modrinth.com/mod/asyncparticles) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ **(not needed in 1.21.11+)**
  - Makes improvements to asynchronous rendering using multiple threads
  - **New addition to the mod list since the most recent video**
- [BadOptimizations](https://modrinth.com/mod/badoptimizations) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds improvements to lighting and color calculations
  - **New addition to the mod list since the most recent video**
- [Client Crafting](https://www.curseforge.com/minecraft/mc-mods/client-crafting) - 1.21.1 ✔ 1.21.4 ❌ 1.21.10 ❌ 1.21.11 ❌
  - Moves crafting to the client so that crafting is more responsive on laggy servers
  - **New addition to the mod list since the most recent video**
- [Concurrent Chunk Management Engine (C2ME)](https://modrinth.com/mod/c2me-fabric) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Improves the efficiency of chunk generation
- [Connectivity](https://www.curseforge.com/minecraft/mc-mods/connectivity) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Fixes server connectivity issues to make multiplayer better
  - **Requires Cupboard**
  - **New addition to the mod list since the most recent video**
- [Debugify](https://modrinth.com/mod/debugify) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ❌
  - Patches a bunch of unpatched bugs in vanilla Minecraft
  - **Requires Fabric API**
- [Dynamic FPS](https://modrinth.com/mod/dynamic-fps) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Reduces your game's frame rate while you aren't focused on the window to save power and increase the performance of the rest of your computer
  - **Requires Fabric API**
- [Enhanced Block Entities](https://modrinth.com/mod/ebe) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔ (use [Better Block Entities](https://modrinth.com/mod/better-block-entities) for 1.21.6+)
  - Changes blocks like chests and beds to use block models instead of entity models, which increases performance, but also allows for better custom textures and allows them to have smooth lighting
  - **Requires Fabric API**
- [Entity Culling](https://modrinth.com/mod/entityculling) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Makes the game not render entites you can't see to improve FPS
  - **Requires Fabric API**
- [Fast IP Ping](https://modrinth.com/mod/fast-ip-ping) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Makes servers on your server list that have literal IP addresses ping much faster
  - **New addition to the mod list since the most recent video**
- [FerriteCore](https://modrinth.com/mod/ferrite-core) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Reduces the game's memory usage
- [fix GPU memory leak](https://www.curseforge.com/minecraft/mc-mods/fix-gpu-memory-leak) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ❌
  - self explanatory
  - **New addition to the mod list since the most recent video**
- [Flerovium](https://modrinth.com/mod/flerovium) - 1.21.1 ✔ 1.21.4 ❌ 1.21.10 ❌ 1.21.11 ❌
  - Improves rendering of items, particles, and entities
  - **Requires Sodium**
  - **New addition to the mod list since the most recent video**
- [ImmediatelyFast](https://modrinth.com/mod/immediatelyfast) - 1.21.1 ✔ 1.21.4 ✔  1.21.10 ✔ 1.21.11 ✔
  - Makes the game's FPS higher
- [kennytvs-epic-force-close-loading-screen-mod-for-fabric](https://modrinth.com/mod/forcecloseworldloadingscreen) - 1.21.1 ✔ 1.21.4 ✔ 1.21.8 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Closes the "Loading terrain" and resource pack switching screens faster
- [Krypton](https://modrinth.com/mod/krypton) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ❌
  - Improves performance in the networking stack and reduces CPU usage
- [Lithium](https://modrinth.com/mod/lithium) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Improves performance of features like mob AI, game physics, and more internal stuff without changing vanilla gameplay
- [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix) - **(not needed in 1.21+ anymore)**
  - Fixes memory leaks that can cause the game to lag/crash
- [ModernFix](https://modrinth.com/mod/modernfix) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔ ([1.21.5+ downloads here](https://modrinth.com/mod/modernfix-mvus))
  - Fixes bugs and improves the resource usage and frame rate of the game in many ways
- [More Culling](https://modrinth.com/mod/moreculling) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds more things to cull for the Entity Culling mod
- [Noisium](https://modrinth.com/mod/noisium) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔ ([1.21.7+ versions available here](https://modrinth.com/mod/noisiumforked))
  - Makes small optimizations to world generation
  - **New addition to the mod list since the most recent video**
- [Nvidum](https://modrinth.com/mod/nvidium) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ❌ ([unofficial 1.21.5+ version here](https://github.com/drouarb/nvidium/releases)]
  - Uses NVIDIA OpenGL extensions to drastically increase the performance of the game. **Only works on NVIDIA 16 series and higher GPUs, the mod will not do anything on other GPUs**
  - **Requires Sodium**
- [Particle Core](https://modrinth.com/mod/particle-core) - 1.21.1 ✔ 1.21.4 ✔ **(not needed in 1.21.9+)**
  - Adds optimizations to particle rendering
  - **Requires Fabric API, Fzzy Config, & Fabric Language Kotlin**
  - **New addition to the mod list since the most recent video**
- [ResourcePackCached](https://modrinth.com/mod/resourcepackcached) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Keeps server resource packs loaded in the background so you don't need to reload them every time you leave and join a server
  - **New addition to the mod list since the most recent video**
- [ScalableLux](https://modrinth.com/mod/scalablelux) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Improves the lighting system for faster chunk generation
  - **New addition to the mod list since the most recent video**
- [Server Pinger Fixer](https://modrinth.com/mod/serverpingerfixer) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Uses more threads to ping servers making them ping much faster
  - **New addition to the mod list since the most recent video**
- [Sodium](https://modrinth.com/mod/sodium) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Improves your game's FPS by an order of magnitude
- [Tekst](https://modrinth.com/mod/tekst) - 1.21.1 ✔ 1.21.4 ❌ 1.21.10 ❌ 1.21.11 ❌
  - Makes formatted text rendering faster
  - **New addition to the mod list since the most recent video**
- [Very Many Players](https://modrinth.com/mod/vmp-fabric) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Improves server performance at high player counts. Not super impactful on the client but does make small improvements
  - **New addition to the mod list since the most recent video**
 
## Quality-of-Life Mods
- [3D Skin Layers](https://modrinth.com/mod/3dskinlayers) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Makes the second layer of a skin render in 3D
- [Auth Me](https://modrinth.com/mod/auth-me) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Allows for in-game account authentication to fix the dreaded "Invalid session" issue
  - **New addition to the mod list since the most recent video**
- [Better Mount HUD](https://modrinth.com/mod/better-mount-hud) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Prevents your HUD information from being hidden when riding a horse
  - **New addition to the mod list since the most recent video**
- [Better Ping Display](https://modrinth.com/mod/better-ping-display-fabric) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔ ([1.21.6+ download here](https://github.com/user-attachments/files/21384157/BetterPingDisplay-Fabric-1.21.6-1.1.2-SNAPSHOT.jar.zip))
  - Changes player list (tab list) to show ping numbers instead of ping bars
- [Better Statistics Screen](https://modrinth.com/mod/better-stats) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Makes the in-game statistics screen [beautiful](https://www.youtube.com/watch?v=AaC8J0G238c)
  - **Requires Architectury API, Fabric API, & TCDCommons API**
- [Capes](https://modrinth.com/mod/capes) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Lets you see capes from OptiFine, LabyMod, and MinecraftCapes without installing those mods
  - **Requires Fabric API & Fabric Language Kotlin**
- [Chat Patches](https://modrinth.com/mod/chatpatches) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Allows you to view your cape from mods like OptiFine
  - **Requires Fabric API & YetAnotherConfigLib**
- [Concentration](https://modrinth.com/mod/concentration) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ❌ (alternative mod for 1.21.9+: [Cubes Without Borders](https://modrinth.com/mod/cubes-without-borders))
  - Makes your fullscreen window borderless
  - **Requires Fabric API**
- [Controlling](https://modrinth.com/mod/controlling) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds a search bar to the controls menu
  - **Requires Fabric API & Searchables**
  - **New addition to the mod list since the most recent video**
- [Continuity](https://modrinth.com/mod/continuity) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds support for [connected textures](https://external-preview.redd.it/do0Hmo_W7FIGVul6Fu9t9XoAC1345cghxoeqHzw5ffU.png?width=1080&crop=smart&auto=webp&v=enabled&p=e&s=eb504037c91a7fc94e56254a90e1145d6e4ae560) (like OptiFine)
  - **Requires Fabric API**
- [e4mc](https://modrinth.com/mod/e4mc) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Allows opening of a world from your computer instantly to let friends join
  - **Requires Fabric API**
  - **New addition to the mod list since the most recent video**
- [Gamma Utils](https://modrinth.com/mod/gamma-utils) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds in-game options to increase your game brightness above the normal limit, a.k.a fullbright
  - **Requires Cloth Config API & Fabric API**
- [Highlight](https://modrinth.com/mod/highlight) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Improves the look of block selection boxes for unusually shaped blocks
  - **Requires Fabric API**
  - **New addition to the mod list since the most recent video**
- [In-Game Account Switcher](https://modrinth.com/mod/in-game-account-switcher) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Allows you to switch between Minecraft account without restarting the game
  - **Requires Fabric API**
- [Iris Shaders](https://modrinth.com/mod/iris) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds support for shader packs, just like OptiFine
  - **Requires Sodium**
- [Language Reload](https://modrinth.com/mod/language-reload) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ❌
  - Adds a great-looking GUI for switching languages and makes switching them instantaneous
  - **Requires Fabric API**
- [MiniHUD](https://modrinth.com/mod/minihud) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds a mini F3 menu that you can add your own information to
  - **Requires MaLiLib**
- [Mod Menu](https://modrinth.com/mod/modmenu) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds an in-game list of every loaded mod and allows you to configure the settings of mods
- [Model Gap Fix](https://modrinth.com/mod/modelfix) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ **(not needed in 1.21.11+)**
  - Fixes [the little pixel-wide gaps](https://bugs.mojang.com/browse/MC-73186) in items and blocks in the game
  - **Requires Fabric API**
- [No Chat Reports](https://modrinth.com/mod/no-chat-reports) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Removes signatures from your chat messages to make them unreportable and disables in-game telemetry (data collection)
- [Reese's Sodium Options](https://modrinth.com/mod/reeses-sodium-options) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Reorganizes the Sodium mod's video settings menu
  - **Requires Sodium**
- [Replay Mod](https://www.replaymod.com) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Allows for viewing of past in-game Minecraft sessions from a spectator POV and rendering of videos from this POV (very simplified explanation)
- [Screenshot to Clipboard](https://modrinth.com/mod/screenshot-to-clipboard) - 1.21.1 ✔ 1.21.4 ✔ ❌ 1.21.10 ❌ 1.21.11 ❌
  - Copies screenshots you take to your computer's clipboard so you don't have to dig through your computer to find them every time
- [Scribble](https://modrinth.com/mod/scribble) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds formatting controls to book writing
  - **New addition to the mod list since the most recent video**
- [Server Pack Unlocker](https://modrinth.com/mod/server-pack-unlocker) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Allows you to disable and move server resource packs around like any other resource pack
  - **New addition to the mod list since the most recent video**
- [Status Effect Bars](https://modrinth.com/mod/status-effect-bars) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Shows how long your potion effects have left in the icons at the top of the screen
  - **New addition to the mod list since the most recent video**
- [ViaFabricPlus](https://modrinth.com/mod/viafabricplus) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Allows you to join servers running on any older version of Minecraft (including Bedrock) without having to change versions
  - **New addition to the mod list since the most recent video**
- [WorldEdit](https://modrinth.com/plugin/worldedit) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Edit massive areas of terrain and make massive structures
- [Zoomify](https://modrinth.com/mod/zoomify) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds a customizable zoom key with versatile options
  - **Requires Fabric API, Fabric Language Kotlin & YetAnotherConfigLib**

## Dependency Mods (you need these too)

- [Architectury API](https://modrinth.com/mod/architectury-api) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Assists in multiplatform mod usage
- [Cloth Config API](https://modrinth.com/mod/cloth-config) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Required for a lot of mods to be configured
- [Cupboard](https://www.curseforge.com/minecraft/mc-mods/cupboard) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds frameworks for other mods
  - **New addition to the mod list since the most recent video**
- [Fabric API](https://modrinth.com/mod/fabric-api) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Necessary for almost all Fabric mods to work
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin) (works on any game version)
  - Adds support for the Kotlin programming language for mods to use
- [Indium](https://modrinth.com/mod/indium) - 1.21.1 ✔ **(not necessary with Sodium 0.6 and above)**
  - Makes Sodium compatible with the Fabric Rendering API, allowing a lot of previously incompatible mods to work with it
  - **Requires Fabric API & Sodium**
- [MaLiLib](https://modrinth.com/mod/malilib) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Makes other mods by [the author of this mod](https://github.com/maruohon) work
- [Searchables](https://modrinth.com/mod/searchables) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Adds backend searching and autocomplete functionality
  - **Requires Fabric API**
  - **New addition to the mod list since the most recent video**
- [TCDCommons API](https://modrinth.com/mod/tcdcommons) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - An API for custom GUIs
  - **Requires Fabric API & Architectury API**
- [YetAnotherConfigLib](https://modrinth.com/mod/yacl) - 1.21.1 ✔ 1.21.4 ✔ 1.21.10 ✔ 1.21.11 ✔
  - Similar to Cloth Config API, but for certain other mods
  - **Requires Fabric API**

### Bonus mod

- [Technopig](https://modrinth.com/mod/technomodel)
  - Makes pigs named Technoblade wear a crown. Fly high
