-- Block entity being ticked --
Details:
	Name: occultism:golden_sacrificial_bowl // com.github.klikli_dev.occultism.common.tile.GoldenSacrificialBowlTileEntity
	Block: Block{occultism:golden_sacrificial_bowl}
	Block location: World: (71,69,-183), Chunk: (at 7,4,9 in 4,-12; contains blocks 64,0,-192 to 79,255,-177), Region: (0,-1; contains chunks 0,-32 to 31,-1, blocks 0,0,-512 to 511,255,-1)
	Block: Block{occultism:golden_sacrificial_bowl}
	Block location: World: (71,69,-183), Chunk: (at 7,4,9 in 4,-12; contains blocks 64,0,-192 to 79,255,-177), Region: (0,-1; contains chunks 0,-32 to 31,-1, blocks 0,0,-512 to 511,255,-1)
Stacktrace:
	at net.minecraft.world.World.func_217391_K(World.java:491) ~[?:?] {re:mixin,pl:accesstransformer:B,xf:fml:observerlib:coremodmethod,xf:fml:astralsorcery:sun_brightness_server,xf:fml:twilightforest:hitbox,re:classloading,pl:accesstransformer:B,xf:fml:observerlib:coremodmethod,xf:fml:astralsorcery:sun_brightness_server,xf:fml:twilightforest:hitbox,pl:mixin:APP:mixins.common.json:LevelMixin,pl:mixin:APP:kubejs-common.mixins.json:LevelMixin,pl:mixin:APP:flywheel.mixins.json:TileWorldHookMixin,pl:mixin:A}
	at net.minecraft.world.server.ServerWorld.func_72835_b(ServerWorld.java:371) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:mixins.common.json:ServerLevelMixin,pl:mixin:APP:abnormals_core.mixins.json:ServerWorldMixin,pl:mixin:APP:endergetic.mixins.json:ServerWorldMixin,pl:mixin:APP:quark.mixins.json:ServerWorldMixin,pl:mixin:A}


-- Affected level --
Details:
	All players: 1 total; [ServerPlayerEntity['Anarchy63'/88251, l='ServerLevel[New World]', x=70.52, y=69.00, z=-189.01]]
	Chunk stats: ServerChunkCache: 2603
	Level dimension: minecraft:overworld
	Level spawn location: World: (-144,63,-144), Chunk: (at 0,3,0 in -9,-9; contains blocks -144,0,-144 to -129,255,-129), Region: (-1,-1; contains chunks -32,-32 to -1,-1, blocks -512,0,-512 to -1,255,-1)
	Level time: 773400 game time, 1113522 day time
	Level name: New World
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: true
	Level weather: Rain time: 114232 (now: false), thunder time: 57077 (now: false)
	Known server brands: forge
	Level was modded: true
	Level storage version: 0x04ABD - Anvil
Stacktrace:
	at net.minecraft.server.MinecraftServer.func_71190_q(MinecraftServer.java:851) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:resourcefulbees.mixins.json:MixinMinecraftServer,pl:mixin:APP:elementalcraft.mixins.json:MixinMinecraftServer,pl:mixin:APP:kubejs-common.mixins.json:MinecraftServerMixin,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_71217_p(MinecraftServer.java:787) ~[?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:resourcefulbees.mixins.json:MixinMinecraftServer,pl:mixin:APP:elementalcraft.mixins.json:MixinMinecraftServer,pl:mixin:APP:kubejs-common.mixins.json:MinecraftServerMixin,pl:mixin:A}
	at net.minecraft.server.integrated.IntegratedServer.func_71217_p(IntegratedServer.java:78) ~[?:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.server.MinecraftServer.func_240802_v_(MinecraftServer.java:642) [?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:resourcefulbees.mixins.json:MixinMinecraftServer,pl:mixin:APP:elementalcraft.mixins.json:MixinMinecraftServer,pl:mixin:APP:kubejs-common.mixins.json:MinecraftServerMixin,pl:mixin:A}
	at net.minecraft.server.MinecraftServer.func_240783_a_(MinecraftServer.java:232) [?:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:mixin:APP:betterendforge.mixins.json:MinecraftServerMixin,pl:mixin:APP:structure_gel.mixins.json:MinecraftServerMixin,pl:mixin:APP:byg.mixins.json:server.MixinMinecraftServer,pl:mixin:APP:resourcefulbees.mixins.json:MixinMinecraftServer,pl:mixin:APP:elementalcraft.mixins.json:MixinMinecraftServer,pl:mixin:APP:kubejs-common.mixins.json:MinecraftServerMixin,pl:mixin:A}
	at net.minecraft.server.MinecraftServer$$Lambda$31030/0x0000000000000000.run(Unknown Source) [?:?] {}
	at java.lang.Thread.run(Thread.java:826) [?:1.8.0_302] {}


-- System Details --
Details:
	Minecraft Version: 1.16.5
	Minecraft Version ID: 1.16.5
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 1.8.0_302, International Business Machines Corporation
	Java VM Version: Eclipse OpenJ9 VM (JRE 1.8.0 Windows 10 amd64-64-Bit Compressed References 20210730_192 (JIT enabled, AOT enabled)
OpenJ9   - 1851b0074
OMR      - 9db1c870d
JCL      - de702c3174 based on jdk8u302-b08), Eclipse OpenJ9
	Memory: 1185333528 bytes (1130 MB) / 5180424192 bytes (4940 MB) up to 7818182656 bytes (7456 MB)
	CPUs: 24
	JVM Flags: 8 total; -Xoptionsfile=C:\Program Files\Semeru\jdk-8.0.302.8-openj9\jre\bin\default\options.default -Xlockword:mode=default,noLockword=java/lang/String,noLockword=java/util/MapEntry,noLockword=java/util/HashMap$Entry,noLockword=org/apache/harmony/luni/util/ModifiedMap$Entry,noLockword=java/util/Hashtable$Entry,noLockword=java/lang/invoke/MethodType,noLockword=java/lang/invoke/MethodHandle,noLockword=java/lang/invoke/CollectHandle,noLockword=java/lang/invoke/ConstructorHandle,noLockword=java/lang/invoke/ConvertHandle,noLockword=java/lang/invoke/ArgumentConversionHandle,noLockword=java/lang/invoke/AsTypeHandle,noLockword=java/lang/invoke/ExplicitCastHandle,noLockword=java/lang/invoke/FilterReturnHandle,noLockword=java/lang/invoke/DirectHandle,noLockword=java/lang/invoke/ReceiverBoundHandle,noLockword=java/lang/invoke/DynamicInvokerHandle,noLockword=java/lang/invoke/FieldHandle,noLockword=java/lang/invoke/FieldGetterHandle,noLockword=java/lang/invoke/FieldSetterHandle,noLockword=java/lang/invoke/StaticFieldGetterHandle,noLockword=java/lang/invoke/StaticFieldSetterHandle,noLockword=java/lang/invoke/IndirectHandle,noLockword=java/lang/invoke/InterfaceHandle,noLockword=java/lang/invoke/VirtualHandle,noLockword=java/lang/invoke/PrimitiveHandle,noLockword=java/lang/invoke/InvokeExactHandle,noLockword=java/lang/invoke/InvokeGenericHandle,noLockword=java/lang/invoke/VarargsCollectorHandle,noLockword=java/lang/invoke/ThunkTuple -Xjcl:jclse29 -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx7456m -Xms256m -XX:PermSize=256m
	ModLauncher: 8.0.9+86+master.3cf110c
	ModLauncher launch target: fmlclient
	ModLauncher naming: srg
	ModLauncher services: 
		/mixin-0.8.4.jar mixin PLUGINSERVICE 
		/eventbus-4.0.0.jar eventbus PLUGINSERVICE 
		/forge-1.16.5-36.2.9.jar object_holder_definalize PLUGINSERVICE 
		/forge-1.16.5-36.2.9.jar runtime_enum_extender PLUGINSERVICE 
		/accesstransformers-3.0.1.jar accesstransformer PLUGINSERVICE 
		/forge-1.16.5-36.2.9.jar capability_inject_definalize PLUGINSERVICE 
		/forge-1.16.5-36.2.9.jar runtimedistcleaner PLUGINSERVICE 
		/mixin-0.8.4.jar mixin TRANSFORMATIONSERVICE 
		/forge-1.16.5-36.2.9.jar fml TRANSFORMATIONSERVICE 
	FML: 36.2
	Forge: net.minecraftforge:36.2.9
	FML Language Providers: 
		javafml@36.2
		minecraft@1
		kotlinforforge@1.15.1
	Mod List: 
		ftb-essentials-1605.1.5-build.32.jar              |FTB Essentials                |ftbessentials                 |1605.1.5-build.32   |DONE      |Manifest: NOSIGNATURE
		supermartijn642configlib-1.0.9-mc1.16.jar         |SuperMartijn642's Config Lib  |supermartijn642configlib      |1.0.9               |DONE      |Manifest: NOSIGNATURE
		ProjectE-1.16.5-PE1.0.1B.jar                      |ProjectE                      |projecte                      |PE1.0.1B            |DONE      |Manifest: NOSIGNATURE
		mcw-windows-2.0.0-mc1.16.5.jar                    |Macaw's Windows               |mcwwindows                    |2.0.0               |DONE      |Manifest: NOSIGNATURE
		modnametooltip_1.16.2-1.15.0.jar                  |Mod Name Tooltip              |modnametooltip                |1.15.0              |DONE      |Manifest: NOSIGNATURE
		BetterCaves-Forge-1.16.4-1.1.2.jar                |YUNG's Better Caves           |bettercaves                   |1.16.4-1.1.2        |DONE      |Manifest: NOSIGNATURE
		CTM-MC1.16.1-1.1.2.6.jar                          |ConnectedTexturesMod          |ctm                           |MC1.16.1-1.1.2.6    |DONE      |Manifest: NOSIGNATURE
		farmersdelightintegrations-1.16.5-1.2.jar         |Farmer's Delight Compats      |farmersdelightintegrations    |1.16.5-1.2          |DONE      |Manifest: NOSIGNATURE
		EvilCraft-1.16.5-1.1.9.jar                        |EvilCraft                     |evilcraft                     |1.1.9               |DONE      |Manifest: NOSIGNATURE
		YungsApi-1.16.4-Forge-13.jar                      |YUNG's API                    |yungsapi                      |1.16.4-Forge-13     |DONE      |Manifest: NOSIGNATURE
		reliquary-1.16.5-1.3.5.1100.jar                   |Reliquary                     |xreliquary                    |1.16.5-1.3.5.1100   |DONE      |Manifest: NOSIGNATURE
		randompatches-2.4.4-forge.jar                     |RandomPatches                 |randompatches                 |2.4.4-forge         |DONE      |Manifest: 92:f6:29:d4:09:89:f5:f5:98:5e:20:34:31:d0:7b:58:22:06:bd:a5:d1:6a:92:6e:ac:3d:8d:18:c5:b2:5b:d7
		Apotheosis-1.16.5-4.8.2.jar                       |Apotheosis                    |apotheosis                    |4.8.2               |DONE      |Manifest: NOSIGNATURE
		Morpheus-1.16.5-4.2.70.jar                        |Morpheus                      |morpheus                      |4.2.70              |DONE      |Manifest: NOSIGNATURE
		dynviewdist-2.0.jar                               |Dynamic view distance         |dynview                       |1.8                 |DONE      |Manifest: NOSIGNATURE
		shetiphiancore-1.16-3.8.6.jar                     |ShetiPhian-Core               |shetiphiancore                |3.8.6               |DONE      |Manifest: NOSIGNATURE
		supplementaries-1.16.5-0.17.9.jar                 |Supplementaries               |supplementaries               |1.16.5-0.17.9       |DONE      |Manifest: NOSIGNATURE
		betterendforge-1.16.5-1.6.3.jar                   |BetterEnd Forge               |betterendforge                |1.16.5-1.6.3        |DONE      |Manifest: NOSIGNATURE
		structure_gel-1.16.5-1.7.8.jar                    |Structure Gel API             |structure_gel                 |1.7.8               |DONE      |Manifest: NOSIGNATURE
		PackMenu-1.16.5-2.5.0.jar                         |PackMenu                      |packmenu                      |2.5.0               |DONE      |Manifest: NOSIGNATURE
		alltheores-1.3.6-1.16.5-36.1.0.jar                |AllTheOres                    |alltheores                    |1.3.6-1.16.5-36.1.0 |DONE      |Manifest: NOSIGNATURE
		torchmaster-2.3.8.jar                             |Torchmaster                   |torchmaster                   |2.3.8               |DONE      |Manifest: NOSIGNATURE
		repurposed_structures_forge-3.4.2+1.16.5.jar      |Repurposed Structures         |repurposed_structures         |3.4.2+1.16.5        |DONE      |Manifest: NOSIGNATURE
		ironfurnaces-1.16.5-2.7.7.jar                     |Iron Furnaces                 |ironfurnaces                  |2.7.7               |DONE      |Manifest: NOSIGNATURE
		astral-1.9.18.jar                                 |Astral                        |astral                        |1.9.18              |DONE      |Manifest: NOSIGNATURE
		supermartijn642corelib-1.0.14-mc1.16.5.jar        |SuperMartijn642's Core Lib    |supermartijn642corelib        |1.0.14              |DONE      |Manifest: NOSIGNATURE
		Botania-1.16.5-420.jar                            |Botania                       |botania                       |1.16.5-420          |DONE      |Manifest: NOSIGNATURE
		fairylights-4.0.5-1.16.5.jar                      |Fairy Lights                  |fairylights                   |4.0.5               |DONE      |Manifest: NOSIGNATURE
		SpawnerFix-1.16.2-1.0.0.2.jar                     |Spawner Fix                   |sf                            |1.0.0.2             |DONE      |Manifest: NOSIGNATURE
		spark-forge.jar                                   |spark                         |spark                         |1.6.0               |DONE      |Manifest: NOSIGNATURE
		curios-forge-1.16.5-4.0.5.3.jar                   |Curios API                    |curios                        |1.16.5-4.0.5.3      |DONE      |Manifest: NOSIGNATURE
		FramedBlocks-2.11.1.jar                           |FramedBlocks                  |framedblocks                  |2.11.1              |DONE      |Manifest: NOSIGNATURE
		angelring-1.16.5-1.3.4.1.jar                      |Angel Ring                    |angelring                     |1.3.4.1             |DONE      |Manifest: NOSIGNATURE
		tombstone-6.6.0-1.16.5.jar                        |Corail Tombstone              |tombstone                     |6.6.0               |DONE      |Manifest: NOSIGNATURE
		TheAbyss2 1.9.7 1.16.5.jar                        |TheAbyss                      |theabyss                      |1.9.7               |DONE      |Manifest: NOSIGNATURE
		NaturesAura-34.3.jar                              |Nature's Aura                 |naturesaura                   |34.3                |DONE      |Manifest: NOSIGNATURE
		constructionwand-1.16.5-2.4.jar                   |Construction Wand             |constructionwand              |1.16.5-2.4          |DONE      |Manifest: NOSIGNATURE
		mcw-roofs-2.0.1-mc1.16.5-4.jar                    |Macaw's Roofs                 |mcwroofs                      |2.0.1               |DONE      |Manifest: NOSIGNATURE
		cfm-7.0.0-pre22-mc1.16.3.jar                      |MrCrayfish's Furniture Mod    |cfm                           |7.0.0-pre22         |DONE      |Manifest: NOSIGNATURE
		observerlib-1.16.5-1.5.3.jar                      |ObserverLib                   |observerlib                   |1.16.5-1.5.3        |DONE      |Manifest: NOSIGNATURE
		cloth-config-4.12.41-forge.jar                    |Cloth Config v4 API           |cloth-config                  |4.12.41             |DONE      |Manifest: NOSIGNATURE
		FastLeafDecay-v25.jar                             |FastLeafDecay                 |fastleafdecay                 |v25                 |DONE      |Manifest: NOSIGNATURE
		geckolib-forge-1.16.5-3.0.54.jar                  |GeckoLib                      |geckolib3                     |3.0.54              |DONE      |Manifest: NOSIGNATURE
		dwarfcoal-1.16.4-1.0.1.jar                        |Dwarf Coal                    |dwarfcoal                     |1.16.4-1.0.0        |DONE      |Manifest: NOSIGNATURE
		mowziesmobs-1.5.19.jar                            |Mowzie's Mobs                 |mowziesmobs                   |1.5.19              |DONE      |Manifest: NOSIGNATURE
		Floocraft 1.16.3-1.16.1.jar                       |Floocraft                     |floocraftft                   |1.16.1              |DONE      |Manifest: NOSIGNATURE
		bagofyurting-1.16.4-1.2.0.1.jar                   |Bag of Yurting                |bagofyurting                  |1.2.0.1             |DONE      |Manifest: NOSIGNATURE
		jei-1.16.5-7.7.1.134.jar                          |Just Enough Items             |jei                           |7.7.1.134           |DONE      |Manifest: NOSIGNATURE
		AttributeFix-1.16.5-10.1.3.jar                    |AttributeFix                  |attributefix                  |10.1.3              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		invtweaks-1.16.4-1.0.1.jar                        |Inventory Tweaks Renewed      |invtweaks                     |1.16.4-1.0.1        |DONE      |Manifest: NOSIGNATURE
		NaturesCompass-1.16.5-1.9.1-forge.jar             |Nature's Compass              |naturescompass                |1.16.5-1.9.1-forge  |DONE      |Manifest: NOSIGNATURE
		LibX-1.16.3-1.0.76.jar                            |LibX                          |libx                          |1.16.3-1.0.76       |DONE      |Manifest: NOSIGNATURE
		champions-forge-1.16.5-2.0.1.8.jar                |Champions                     |champions                     |1.16.5-2.0.1.8      |DONE      |Manifest: NOSIGNATURE
		sulfuric-1.1 (2).jar                              |Sulfuric                      |sulfuric                      |1.0                 |DONE      |Manifest: NOSIGNATURE
		mysticalworld-1.16.5-0.3.5.24.jar                 |Mystical World                |mysticalworld                 |0.3.5.23            |DONE      |Manifest: NOSIGNATURE
		forge-1.16.5-36.2.9-universal.jar                 |Forge                         |forge                         |36.2.9              |DONE      |Manifest: 22:af:21:d8:19:82:7f:93:94:fe:2b:ac:b7:e4:41:57:68:39:87:b1:a7:5c:c6:44:f9:25:74:21:14:f5:0d:90
		ironchest-1.16.5-11.2.13.jar                      |Iron Chests                   |ironchest                     |1.16.5-11.2.13      |DONE      |Manifest: NOSIGNATURE
		MythicBotany-1.16.5-1.4.14.jar                    |MythicBotany                  |mythicbotany                  |1.16.5-1.4.14       |DONE      |Manifest: NOSIGNATURE
		DungeonsArise-1.16.5-2.1.47-release.jar           |When Dungeons Arise           |dungeons_arise                |2.1.47              |DONE      |Manifest: NOSIGNATURE
		forge-1.16.5-36.2.9-client.jar                    |Minecraft                     |minecraft                     |1.16.5              |DONE      |Manifest: NOSIGNATURE
		cofh_core-1.16.5-1.3.1.jar                        |CoFH Core                     |cofh_core                     |1.3.1               |DONE      |Manifest: NOSIGNATURE
		theoneprobe-1.16-3.1.4.jar                        |The One Probe                 |theoneprobe                   |1.16-3.1.4          |DONE      |Manifest: NOSIGNATURE
		MouseTweaks-2.14-mc1.16.2.jar                     |Mouse Tweaks                  |mousetweaks                   |2.14                |DONE      |Manifest: NOSIGNATURE
		Psi 1.16-97.jar                                   |Psi                           |psi                           |1.16-96             |DONE      |Manifest: NOSIGNATURE
		pamhc2crops-1.16.3-1.0.2.jar                      |Pam's HarvestCraft 2 Crops    |pamhc2crops                   |version             |DONE      |Manifest: NOSIGNATURE
		turtlemancy-1.16.5-1.6.3.jar                      |Turtlemancy                   |turtlemancy                   |1.6.3               |DONE      |Manifest: NOSIGNATURE
		jeiintegration_1.16.5-7.0.1.15.jar                |JEI Integration               |jeiintegration                |7.0.1.15            |DONE      |Manifest: NOSIGNATURE
		flywheel-1.16-0.2.4.jar                           |Flywheel                      |flywheel                      |1.16-0.2.4          |DONE      |Manifest: NOSIGNATURE
		Mantle-1.16.5-1.6.127.jar                         |Mantle                        |mantle                        |1.6.127             |DONE      |Manifest: NOSIGNATURE
		pamhc2foodcore-1.16.3-1.0.2.jar                   |Pam's HarvestCraft 2 Food Core|pamhc2foodcore                |version             |DONE      |Manifest: NOSIGNATURE
		ftb-backups-2.1.2.2.jar                           |FTB Backups                   |ftbbackups                    |2.1.2.2             |DONE      |Manifest: NOSIGNATURE
		baubleyheartcanisters-1.16.5-1.1.11.jar           |Baubley Heart Canisters       |bhc                           |1.16.5-1.1.11       |DONE      |Manifest: NOSIGNATURE
		oauth-1.07-1.16.jar                               |OAuth                         |oauth                         |1.0                 |DONE      |Manifest: NOSIGNATURE
		polymorph-forge-1.16.5-0.30.jar                   |Polymorph                     |polymorph                     |1.16.5-0.30         |DONE      |Manifest: NOSIGNATURE
		AutoRegLib-1.6-49.jar                             |AutoRegLib                    |autoreglib                    |1.6-49              |DONE      |Manifest: NOSIGNATURE
		entityculling-1.3.0.jar                           |EntityCulling                 |entityculling                 |1.3.0               |DONE      |Manifest: NOSIGNATURE
		mysticalmachinery-1.16.5-0.0.3.10.jar             |Mystical Machinery            |mysticalmachinery             |0.0.2.9             |DONE      |Manifest: NOSIGNATURE
		FastFurnace-1.16.4-4.4.0.jar                      |FastFurnace                   |fastfurnace                   |4.4.0               |DONE      |Manifest: NOSIGNATURE
		appleskin-forge-mc1.16.x-2.2.0.jar                |AppleSkin                     |appleskin                     |mc1.16.4-2.2.0      |DONE      |Manifest: NOSIGNATURE
		lootr-1.16.5-0.0.8.24.jar                         |Lootr                         |lootr                         |0.0.8.23            |DONE      |Manifest: NOSIGNATURE
		occultism-1.16.5-1.19.3.jar                       |Occultism                     |occultism                     |1.16.5-1.19.3       |DONE      |Manifest: NOSIGNATURE
		allthetweaks-1.4.2-1.16.5-36.1.13.jar             |All The Tweaks                |allthetweaks                  |1.4.2-1.16.5-36.1.13|DONE      |Manifest: NOSIGNATURE
		byg-1.3.5.jar                                     |Oh The Biomes You'll Go       |byg                           |1.3.4               |DONE      |Manifest: NOSIGNATURE
		extremeSoundMuffler-3.17_1.16.5.jar               |Extreme Sound Muffler         |extremesoundmuffler           |3.17_forge-1.16.5   |DONE      |Manifest: NOSIGNATURE
		CosmeticArmorReworked-1.16.5-v4.jar               |CosmeticArmorReworked         |cosmeticarmorreworked         |1.16.5-v4           |DONE      |Manifest: 5e:ed:25:99:e4:44:14:c0:dd:89:c1:a9:4c:10:b5:0d:e4:b1:52:50:45:82:13:d8:d0:32:89:67:56:57:01:53
		magipsi-1.16.5-2.0.0.1.jar                        |Magical Psi                   |magipsi                       |1.16.5-2.0.0.1      |DONE      |Manifest: NOSIGNATURE
		tetra-1.16.5-3.19.0.jar                           |Tetra                         |tetra                         |3.19.0              |DONE      |Manifest: NOSIGNATURE
		tetranomicon-1.3.jar                              |Tetranomicon                  |tetranomicon                  |1.3                 |DONE      |Manifest: NOSIGNATURE
		CyclopsCore-1.16.5-1.12.1.jar                     |Cyclops Core                  |cyclopscore                   |1.12.1              |DONE      |Manifest: NOSIGNATURE
		blue_skies-1.16.5-1.1.3.jar                       |Blue Skies                    |blue_skies                    |1.1.3               |DONE      |Manifest: NOSIGNATURE
		astralsorcery-1.16-1.16.5-1.13.12.jar             |Astral Sorcery                |astralsorcery                 |1.16.5-1.13.12      |DONE      |Manifest: 45:2b:0a:49:6b:65:3b:39:a9:dd:d2:5b:55:7f:82:47:a5:1d:7a:cc:7f:a8:69:73:72:53:6f:57:4d:b2:1a:b7
		NaturesStarlight-1.1.jar                          |Nature's Starlight            |naturesstarlight              |1.1                 |DONE      |Manifest: NOSIGNATURE
		aiotbotania-1.16.5-1.8.4.jar                      |AIOT Botania                  |aiotbotania                   |1.8.4               |DONE      |Manifest: NOSIGNATURE
		Wyrmroost-1.16.3-1.2.11.jar                       |Wyrmroost                     |wyrmroost                     |1.16.3-1.2.11       |DONE      |Manifest: NOSIGNATURE
		eidolon-0.2.7.jar                                 |Eidolon                       |eidolon                       |0.2.7               |DONE      |Manifest: NOSIGNATURE
		incontrol-1.16-5.2.2.jar                          |InControl                     |incontrol                     |1.16-5.2.2          |DONE      |Manifest: NOSIGNATURE
		findme-1.16.3-2.2.0.0.jar                         |Find Me                       |findme                        |2.2.0               |DONE      |Manifest: NOSIGNATURE
		glassential-forge-1.16.5-1.1.7.jar                |Glassential                   |glassential                   |1.1.7               |DONE      |Manifest: NOSIGNATURE
		Controlling-7.0.0.27.jar                          |Controlling                   |controlling                   |7.0.0.27            |DONE      |Manifest: NOSIGNATURE
		Placebo-1.16.5-4.6.0.jar                          |Placebo                       |placebo                       |4.6.0               |DONE      |Manifest: NOSIGNATURE
		citadel-1.8.1-1.16.5.jar                          |Citadel                       |citadel                       |1.8.1               |DONE      |Manifest: NOSIGNATURE
		iceandfire-2.1.9-1.16.5.jar                       |Ice and Fire                  |iceandfire                    |2.1.9-1.16.5        |DONE      |Manifest: NOSIGNATURE
		potionsmaster-0.2.2-1.16.5-36.1.0.jar             |Potions Master                |potionsmaster                 |0.2.2-1.16.5-36.1.0 |DONE      |Manifest: NOSIGNATURE
		Bookshelf-Forge-1.16.5-10.3.29.jar                |Bookshelf                     |bookshelf                     |10.3.29             |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		DarkUtilities-1.16.5-8.0.11.jar                   |Dark Utilities                |darkutils                     |8.0.11              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		sophisticatedbackpacks-1.16.5-3.11.1.390.jar      |Sophisticated Backpacks       |sophisticatedbackpacks        |1.16.5-3.11.1.390   |DONE      |Manifest: NOSIGNATURE
		ironshulkerboxes-1.16.4-5.1.11.jar                |Iron Shulker Boxes            |ironshulkerbox                |1.16.4-5.1.11       |DONE      |Manifest: NOSIGNATURE
		twilightforest-1.16.5-4.0.546-universal.jar       |The Twilight Forest           |twilightforest                |NONE                |DONE      |Manifest: NOSIGNATURE
		chipped-1.1.2.jar                                 |Chipped                       |chipped                       |1.1.2               |DONE      |Manifest: NOSIGNATURE
		chocolate-1.3.0-1.16.4.jar                        |Chocolate                     |chocolate                     |1.3.0-1.16.4        |DONE      |Manifest: NOSIGNATURE
		mcw-bridges-2.0.0-mc1.16.5.jar                    |Macaw's Bridges               |mcwbridges                    |2.0.0               |DONE      |Manifest: NOSIGNATURE
		FarmersDelight-1.16.5-0.5.1.jar                   |Farmer's Delight              |farmersdelight                |1.16.5-0.5.1        |DONE      |Manifest: NOSIGNATURE
		farmersdelightintegration-1.16.5-1.0.3.jar        |Farmer's Delight Integration  |farmersdelightintegration     |1.16.5-1.0.3        |DONE      |Manifest: NOSIGNATURE
		ResourcefulBees-1.16.5-0.9.9.8.jar                |Resourceful Bees              |resourcefulbees               |1.16.5-0.9.9.8      |DONE      |Manifest: NOSIGNATURE
		entangled-1.3.9-mc1.16.jar                        |Entangled                     |entangled                     |1.3.9               |DONE      |Manifest: NOSIGNATURE
		endertanks-1.16-1.9.6.jar                         |EnderTanks                    |endertanks                    |1.9.6               |DONE      |Manifest: NOSIGNATURE
		CommonCapabilities-1.16.5-2.8.0.jar               |CommonCapabilities            |commoncapabilities            |2.8.0               |DONE      |Manifest: NOSIGNATURE
		crashutilities-3.12.jar                           |Crash Utilities               |crashutilities                |3.12                |DONE      |Manifest: NOSIGNATURE
		pamhc2foodextended-1.16.3-1.0.4.jar               |Pam's HarvestCraft 2 Food Exte|pamhc2foodextended            |version             |DONE      |Manifest: NOSIGNATURE
		dpanvil-1.16.5-1.2.3.jar                          |DataPack Anvil                |dpanvil                       |1.16.5-1.2.3        |DONE      |Manifest: NOSIGNATURE
		Patchouli-1.16.4-53.2.jar                         |Patchouli                     |patchouli                     |1.16.4-53.2         |DONE      |Manifest: NOSIGNATURE
		Feywild-1.16.5-2.0.5.jar                          |Feywild                       |feywild                       |1.16.5-2.0.5        |DONE      |Manifest: NOSIGNATURE
		ars_nouveau-1.16.5-1.23.11.jar                    |Ars Nouveau                   |ars_nouveau                   |1.23.11             |DONE      |Manifest: NOSIGNATURE
		witchery_rewitched-0.3.2.jar                      |Witchery: Rewitched           |witchery_rewitched            |0.3.2               |DONE      |Manifest: NOSIGNATURE
		time-in-a-bottle-1.1.0.jar                        |Time In A Bottle              |tiab                          |1.1.0               |DONE      |Manifest: NOSIGNATURE
		eidolonrecipes-1.16.5-1.0.jar                     |Raccpack Eidolon              |raccpack-eidolon              |1.0-SNAPSHOT        |DONE      |Manifest: NOSIGNATURE
		MysticalCustomization-1.16.5-2.1.6.jar            |Mystical Customization        |mysticalcustomization         |2.1.6               |DONE      |Manifest: NOSIGNATURE
		elevatorid-1.16.5-1.7.13.jar                      |Elevator Mod                  |elevatorid                    |1.16.5-1.7.13       |DONE      |Manifest: NOSIGNATURE
		ftb-ultimine-forge-1605.3.1-build.45.jar          |FTB Ultimine                  |ftbultimine                   |1605.3.1-build.45   |DONE      |Manifest: NOSIGNATURE
		EnigmaticLegacy-2.11.6.jar                        |Enigmatic Legacy              |enigmaticlegacy               |2.11.6              |DONE      |Manifest: NOSIGNATURE
		buildersaddition-1.16.5-20210807a.jar             |Builders Crafts & Addition    |buildersaddition              |1.16.5-20210807a    |DONE      |Manifest: NOSIGNATURE
		Runelic-1.16.5-7.0.2.jar                          |Runelic                       |runelic                       |7.0.2               |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		architectury-1.24.35-forge.jar                    |Architectury                  |architectury                  |1.24.35             |DONE      |Manifest: NOSIGNATURE
		ftb-library-forge-1605.3.4-build.83.jar           |FTB Library                   |ftblibrary                    |1605.3.4-build.83   |DONE      |Manifest: NOSIGNATURE
		ftb-teams-forge-1605.2.3-build.38.jar             |FTB Teams                     |ftbteams                      |1605.2.3-build.38   |DONE      |Manifest: NOSIGNATURE
		ftb-ranks-1605.1.4-build.12-forge.jar             |FTB Ranks                     |ftbranks                      |1605.1.4-build.12   |DONE      |Manifest: NOSIGNATURE
		AI-Improvements-1.16.2-0.3.0.jar                  |AI-Improvements               |aiimprovements                |0.3.0               |DONE      |Manifest: NOSIGNATURE
		light-overlay-5.8.1.jar                           |Light Overlay                 |lightoverlay                  |5.8.1               |DONE      |Manifest: NOSIGNATURE
		trashcans-1.0.10-mc1.16.5.jar                     |Trash Cans                    |trashcans                     |1.0.10              |DONE      |Manifest: NOSIGNATURE
		bwncr-1.16.5-3.10.16.jar                          |Bad Wither No Cookie Reloaded |bwncr                         |1.16.5-3.10.16      |DONE      |Manifest: NOSIGNATURE
		observable-0.1.3-forge.jar                        |Observable                    |observable                    |0.1.3               |DONE      |Manifest: NOSIGNATURE
		BetterAdvancements-1.16.5-0.1.1.115.jar           |Better Advancements           |betteradvancements            |0.1.1.115           |DONE      |Manifest: NOSIGNATURE
		rhino-forge-1605.1.5-build.73.jar                 |Rhino                         |rhino                         |1605.1.5-build.73   |DONE      |Manifest: NOSIGNATURE
		Cucumber-1.16.5-4.1.12.jar                        |Cucumber Library              |cucumber                      |4.1.12              |DONE      |Manifest: NOSIGNATURE
		TrashSlot_1.16.3-12.2.1.jar                       |TrashSlot                     |trashslot                     |12.2.1              |DONE      |Manifest: NOSIGNATURE
		craftingstation-4.1.1.jar                         |Crafting Station              |craftingstation               |4.1.1               |DONE      |Manifest: NOSIGNATURE
		redstonepen-1.16.5-1.0.6.jar                      |Redstone Pen                  |redstonepen                   |1.0.6               |DONE      |Manifest: bf:30:76:97:e4:58:41:61:2a:f4:30:d3:8f:4c:e3:71:1d:14:c4:a1:4e:85:36:e3:1d:aa:2f:cb:22:b0:04:9b
		item-filters-forge-1605.2.5-build.9.jar           |Item Filters                  |itemfilters                   |1605.2.5-build.9    |DONE      |Manifest: NOSIGNATURE
		elementalcraft-1.16.5-2.7.13.jar                  |ElementalCraft                |elementalcraft                |1.16.5-2.7.13       |DONE      |Manifest: NOSIGNATURE
		metalbarrels-1.16.2-3.3b.jar                      |Metal Barrels                 |metalbarrels                  |1.16.2-3.3b         |DONE      |Manifest: NOSIGNATURE
		abnormals_core-1.16.5-3.3.0.jar                   |Abnormals Core                |abnormals_core                |3.3.0               |DONE      |Manifest: NOSIGNATURE
		upgrade_aquatic-1.16.5-3.1.1.jar                  |Upgrade Aquatic               |upgrade_aquatic               |3.1.1               |DONE      |Manifest: NOSIGNATURE
		endergetic-1.16.4-3.0.0.jar                       |The Endergetic Expansion      |endergetic                    |3.0.0               |DONE      |Manifest: NOSIGNATURE
		savageandravage-1.16.5-3.1.0.jar                  |Savage & Ravage               |savageandravage               |3.1.0               |DONE      |Manifest: NOSIGNATURE
		nethers_delight-2.1.jar                           |Nethers Delight               |nethers_delight               |2.1                 |DONE      |Manifest: NOSIGNATURE
		allthemodium-1.5.17-1.16.5-36.1.23.jar            |Allthemodium                  |allthemodium                  |1.5.17-1.16.5-36.1.2|DONE      |Manifest: NOSIGNATURE
		ensorcellation-1.16.5-1.3.1.jar                   |Ensorcellation                |ensorcellation                |1.3.1               |DONE      |Manifest: 75:0b:cc:9b:64:2e:9b:c4:41:d1:95:00:71:ee:87:1a:b3:5e:4b:da:8e:e8:39:00:fd:5d:e5:9c:40:42:33:09
		create-mc1.16.5_v0.3.2f.jar                       |Create                        |create                        |v0.3.2f             |DONE      |Manifest: NOSIGNATURE
		Waystones_1.16.5-7.6.4.jar                        |Waystones                     |waystones                     |7.6.4               |DONE      |Manifest: NOSIGNATURE
		Clumps-6.0.0.27.jar                               |Clumps                        |clumps                        |6.0.0.27            |DONE      |Manifest: NOSIGNATURE
		mgui-1.16.5-3.3.0.jar                             |mgui                          |mgui                          |3.3.0               |DONE      |Manifest: NOSIGNATURE
		comforts-forge-1.16.5-4.0.1.3.jar                 |Comforts                      |comforts                      |1.16.5-4.0.1.3      |DONE      |Manifest: NOSIGNATURE
		Artifacts-1.16.5-2.10.3.jar                       |Artifacts                     |artifacts                     |1.16.5-2.10.3       |DONE      |Manifest: NOSIGNATURE
		configured-1.3.0-1.16.5.jar                       |Configured                    |configured                    |1.3.0               |DONE      |Manifest: NOSIGNATURE
		decorative_blocks-1.16.4-1.7.2.jar                |Decorative Blocks             |decorative_blocks             |1.7.2               |DONE      |Manifest: NOSIGNATURE
		decorative_blocks_abnormals-1.2.jar               |Decorative Blocks Abnormals   |decorative_blocks_abnormals   |1.2                 |DONE      |Manifest: NOSIGNATURE
		DungeonCrawl-1.16.5-2.3.3.jar                     |Dungeon Crawl                 |dungeoncrawl                  |2.3.3               |DONE      |Manifest: NOSIGNATURE
		AkashicTome-1.4-16.jar                            |Akashic Tome                  |akashictome                   |1.4-16              |DONE      |Manifest: NOSIGNATURE
		ftb-chunks-forge-1605.3.2-build.81.jar            |FTB Chunks                    |ftbchunks                     |1605.3.2-build.81   |DONE      |Manifest: NOSIGNATURE
		kubejs-forge-1605.3.18-build.159.jar              |KubeJS                        |kubejs                        |1605.3.18-build.159 |DONE      |Manifest: NOSIGNATURE
		ftb-quests-forge-1605.3.5-build.72.jar            |FTB Quests                    |ftbquests                     |1605.3.5-build.72   |DONE      |Manifest: NOSIGNATURE
		kubejs-create-1605.1.2-build.7.jar                |KubeJS Create                 |kubejs_create                 |1605.1.2-build.7    |DONE      |Manifest: NOSIGNATURE
		BloodMagic-1.16.4-3.1.5-25.jar                    |Blood Magic                   |bloodmagic                    |1.16.4-3.1.5-25     |DONE      |Manifest: NOSIGNATURE
		tomeofblood-1.16.5-1.2.2.jar                      |Tome of Blood                 |tomeofblood                   |1.16.5-1.2.2        |DONE      |Manifest: NOSIGNATURE
		kubejs-blood-magic-1605.1.1-build.3.jar           |KubeJS Blood Magic            |kubejs_blood_magic            |1605.1.1-build.3    |DONE      |Manifest: NOSIGNATURE
		selene-1.16.5-1.9.0.jar                           |Selene                        |selene                        |1.16.5-1.0          |DONE      |Manifest: NOSIGNATURE
		MysticalAgriculture-1.16.5-4.2.5.jar              |Mystical Agriculture          |mysticalagriculture           |4.2.5               |DONE      |Manifest: NOSIGNATURE
		MysticalAgradditions-1.16.5-4.2.2.jar             |Mystical Agradditions         |mysticalagradditions          |4.2.2               |DONE      |Manifest: NOSIGNATURE
		CraftingTweaks_1.16.5-12.2.1.jar                  |Crafting Tweaks               |craftingtweaks                |12.2.1              |DONE      |Manifest: NOSIGNATURE
		EnchantmentDescriptions-1.16.5-7.0.17.jar         |EnchantmentDescriptions       |enchdesc                      |7.0.17              |DONE      |Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		swingthroughgrass-1.16.4-1.5.3.jar                |SwingThroughGrass             |swingthroughgrass             |1.16.4-1.5.3        |DONE      |Manifest: NOSIGNATURE
		mana-and-artifice-1.5.0.10.jar                    |Mana and Artifice             |mana-and-artifice             |1.5.0.10            |DONE      |Manifest: NOSIGNATURE
		archers_paradox-1.16.5-1.3.1.jar                  |Archer's Paradox              |archers_paradox               |1.3.1               |DONE      |Manifest: 75:0b:cc:9b:64:2e:9b:c4:41:d1:95:00:71:ee:87:1a:b3:5e:4b:da:8e:e8:39:00:fd:5d:e5:9c:40:42:33:09
		smoothboot-forge-1.16.4-1.2.2.jar                 |Smooth Boot                   |smoothboot                    |1.16.4-1.2.2        |DONE      |Manifest: NOSIGNATURE
		Quark-r2.4-319.jar                                |Quark                         |quark                         |r2.4-319            |DONE      |Manifest: NOSIGNATURE
		cookiecore-1.16.5-3.3.0-12106d2.jar               |CookieCore                    |cookiecore                    |3.3.0               |DONE      |Manifest: NOSIGNATURE
		magicfeather-1.16.2-3.2.0.jar                     |Magic Feather                 |magicfeather                  |1.16.2-3.2.0        |DONE      |Manifest: NOSIGNATURE
		malum-1.16.5-0.3.0.jar                            |Malum                         |malum                         |1.16.5-0.3.0        |DONE      |Manifest: NOSIGNATURE
		FastWorkbench-1.16.4-4.5.1.jar                    |FastWorkbench                 |fastbench                     |4.5.1               |DONE      |Manifest: NOSIGNATURE
		StorageDrawers-1.16.3-8.3.0.jar                   |Storage Drawers               |storagedrawers                |8.3.0               |DONE      |Manifest: NOSIGNATURE
		topaddons-1.16.5-2.1.5-beta.jar                   |TOP Addons                    |topaddons                     |1.16.5-2.1.5-beta   |DONE      |Manifest: NOSIGNATURE
		enderchests-1.16-1.7.8.jar                        |EnderChests                   |enderchests                   |1.7.8               |DONE      |Manifest: NOSIGNATURE
		ferritecore-2.1.0-forge.jar                       |Ferrite Core                  |ferritecore                   |2.1.0               |DONE      |Manifest: 41:ce:50:66:d1:a0:05:ce:a1:0e:02:85:9b:46:64:e0:bf:2e:cf:60:30:9a:fe:0c:27:e0:63:66:9a:84:ce:8a
		Chisel-MC1.16.5-2.0.1-alpha.4.jar                 |Chisel                        |chisel                        |MC1.16.5-2.0.1-alpha|DONE      |Manifest: NOSIGNATURE
		SoL-Carrot-1.16.5-1.10.1.jar                      |Spice of Life: Carrot Edition |solcarrot                     |1.16.5-1.10.1       |DONE      |Manifest: NOSIGNATURE
		TA2 beginning 1.0.9 1.16.5.jar                    |[Add-on] The Abyss: The Beginn|thebeginning                  |1.0.9               |DONE      |Manifest: NOSIGNATURE
		expandability-2.0.1-forge.jar                     |ExpandAbility                 |expandability                 |2.0.1               |DONE      |Manifest: NOSIGNATURE
		valhelsia_core-16.0.13a.jar                       |Valhelsia Core                |valhelsia_core                |16.0.13a            |DONE      |Manifest: NOSIGNATURE
		forbidden_arcanus-16.2.0-beta-4.jar               |Forbidden & Arcanus           |forbidden_arcanus             |16.2.0-beta-4       |DONE      |Manifest: NOSIGNATURE
	Crash Report UUID: ef0329bf-3d2f-4992-9000-5b1b55af87d1
	[Psi] Active spell: None
	Patchouli open book context: n/a
	Player Count: 1 / 8; [ServerPlayerEntity['Anarchy63'/88251, l='ServerLevel[New World]', x=70.52, y=69.00, z=-189.01]]
	Data Packs: vanilla, mod:ftbessentials, mod:supermartijn642configlib, mod:projecte, mod:mcwwindows, mod:modnametooltip, mod:bettercaves (incompatible), mod:ctm (incompatible), mod:farmersdelightintegrations, mod:evilcraft, mod:yungsapi, mod:xreliquary, mod:randompatches, mod:apotheosis (incompatible), mod:morpheus (incompatible), mod:dynview (incompatible), mod:shetiphiancore, mod:supplementaries, mod:betterendforge, mod:structure_gel, mod:packmenu (incompatible), mod:alltheores, mod:torchmaster (incompatible), mod:repurposed_structures, mod:ironfurnaces, mod:astral, mod:supermartijn642corelib, mod:botania, mod:fairylights, mod:sf, mod:spark, mod:curios, mod:framedblocks (incompatible), mod:angelring (incompatible), mod:tombstone, mod:theabyss, mod:naturesaura (incompatible), mod:constructionwand (incompatible), mod:mcwroofs, mod:observerlib, mod:cloth-config (incompatible), mod:fastleafdecay (incompatible), mod:geckolib3 (incompatible), mod:dwarfcoal (incompatible), mod:mowziesmobs (incompatible), mod:floocraftft (incompatible), mod:bagofyurting (incompatible), mod:jei, mod:attributefix, mod:invtweaks (incompatible), mod:naturescompass (incompatible), mod:libx, mod:champions (incompatible), mod:sulfuric, mod:mysticalworld, mod:forge, mod:ironchest, mod:mythicbotany, mod:dungeons_arise, mod:cofh_core (incompatible), mod:theoneprobe, mod:mousetweaks, mod:psi (incompatible), mod:turtlemancy, mod:jeiintegration, mod:flywheel, mod:mantle (incompatible), mod:ftbbackups (incompatible), mod:bhc (incompatible), mod:oauth, mod:polymorph, mod:autoreglib (incompatible), mod:entityculling, mod:mysticalmachinery (incompatible), mod:fastfurnace (incompatible), mod:appleskin, mod:lootr (incompatible), mod:occultism, mod:allthetweaks, mod:byg, mod:extremesoundmuffler, mod:cosmeticarmorreworked (incompatible), mod:magipsi, mod:tetra, mod:tetranomicon, mod:cyclopscore, mod:blue_skies (incompatible), mod:astralsorcery, mod:naturesstarlight (incompatible), mod:aiotbotania (incompatible), mod:wyrmroost (incompatible), mod:eidolon, mod:incontrol (incompatible), mod:findme (incompatible), mod:glassential (incompatible), mod:controlling, mod:placebo (incompatible), mod:citadel (incompatible), mod:iceandfire (incompatible), mod:potionsmaster, mod:bookshelf, mod:darkutils (incompatible), mod:sophisticatedbackpacks, mod:ironshulkerbox (incompatible), mod:twilightforest, mod:chipped, mod:chocolate, mod:mcwbridges (incompatible), mod:farmersdelight, mod:farmersdelightintegration, mod:resourcefulbees (incompatible), mod:entangled, mod:endertanks, mod:commoncapabilities, mod:crashutilities (incompatible), mod:dpanvil, mod:patchouli (incompatible), mod:feywild, mod:ars_nouveau, mod:witchery_rewitched, mod:tiab, mod:raccpack-eidolon, mod:mysticalcustomization (incompatible), mod:elevatorid, mod:ftbultimine (incompatible), mod:enigmaticlegacy, mod:buildersaddition (incompatible), mod:runelic, mod:architectury, mod:ftblibrary, mod:ftbteams, mod:ftbranks, mod:aiimprovements, mod:lightoverlay (incompatible), mod:trashcans, mod:bwncr, mod:observable, mod:betteradvancements, mod:rhino, mod:cucumber, mod:trashslot (incompatible), mod:craftingstation (incompatible), mod:redstonepen, mod:itemfilters, mod:elementalcraft, mod:metalbarrels (incompatible), mod:abnormals_core, mod:upgrade_aquatic, mod:endergetic, mod:savageandravage, mod:nethers_delight, mod:allthemodium, mod:ensorcellation (incompatible), mod:create, mod:waystones (incompatible), mod:clumps, mod:mgui (incompatible), mod:comforts, mod:artifacts, mod:configured, mod:decorative_blocks, mod:decorative_blocks_abnormals, mod:dungeoncrawl, mod:akashictome, mod:ftbchunks, mod:kubejs, mod:ftbquests, mod:kubejs_create, mod:bloodmagic, mod:tomeofblood, mod:kubejs_blood_magic, mod:selene, mod:mysticalagriculture, mod:mysticalagradditions, mod:craftingtweaks (incompatible), mod:enchdesc, mod:swingthroughgrass (incompatible), mod:mana-and-artifice, mod:archers_paradox (incompatible), mod:smoothboot, mod:quark (incompatible), mod:cookiecore, mod:magicfeather, mod:malum (incompatible), mod:fastbench (incompatible), mod:storagedrawers (incompatible), mod:topaddons (incompatible), mod:enderchests, mod:ferritecore (incompatible), mod:chisel (incompatible), mod:solcarrot, mod:thebeginning, mod:expandability, mod:valhelsia_core, mod:forbidden_arcanus (incompatible), resourcefulbees:internals (incompatible), mod:cfm (incompatible), mod:pamhc2crops (incompatible), mod:pamhc2foodcore (incompatible), mod:pamhc2foodextended (incompatible)
	Type: Integrated Server (map_client.txt)
	Is Modded: Definitely; Client brand changed to 'forge'
