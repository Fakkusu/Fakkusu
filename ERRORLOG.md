---- Crash Report ----
// Who set us up the TNT?

Time: 2023-11-20 16:48:39
Description: Mod loading error has occurred

java.lang.Exception: Mod Loading has failed
	at net.minecraftforge.logging.CrashReportExtender.dumpModLoadingCrashReport(CrashReportExtender.java:55) ~[forge-1.19.2-43.3.5-universal.jar%23808!/:?] {re:classloading,pl:rei_plugin_compatibilities:B}
	at net.minecraftforge.client.loading.ClientModLoader.completeModLoading(ClientModLoader.java:167) ~[forge-1.19.2-43.3.5-universal.jar%23808!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:rei_plugin_compatibilities:B,pl:mixin:APP:memorysettings.mixins.json:ClienModLoaderMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.lambda$new$2(Minecraft.java:585) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:rei_plugin_compatibilities:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:hud_batching.MixinMinecraftClient,pl:mixin:APP:kubejs-common.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:immersive_armors.mixins.json:MixinMinecraftClient,pl:mixin:APP:rubidium.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:mixins.blur.json:MixinMinecraftClient,pl:mixin:APP:mixins.oculus.json:MixinMinecraft_PipelineManagement,pl:mixin:APP:mutantmore.mixins.json:MinecraftMixin,pl:mixin:APP:dungeons_libraries.mixins.json:MinecraftMixin,pl:mixin:APP:tslatentitystatus.mixins.json:client.MinecraftMixin,pl:mixin:APP:fastload.mixins.json:client.MinecraftMixin,pl:mixin:APP:cgm.mixins.json:client.MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin,pl:mixin:APP:embeddiumplus.mixin.json:FrameCounter.FpsAccessorMixin,pl:mixin:APP:mixins.satin.client.json:event.MinecraftClientMixin,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:dynmus-common.mixins.json:MinecraftClientMixin,pl:mixin:APP:konkrete.mixin.json:MixinMinecraft,pl:mixin:APP:entity_model_features-common.mixins.json:MixinResourceReload,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.MinecraftClientAccessor,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinMinecraftClient,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinResourceReload,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:anchor-common.client.mixins.json:MinecraftMixin,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:travelerstitles.mixins.json:MinecraftClientTickMixin,pl:mixin:APP:citresewn.mixins.json:citenchantment.MinecraftClientMixin,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.Mixin_RunEssentialTasks,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:compatibility.vanilla.Mixin_WorkaroundBrokenFramebufferBlitBlending,pl:mixin:APP:mixins.essential.json:events.Mixin_RenderTickEvent,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.Util.m_137521_(Util.java:438) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:mixin,pl:accesstransformer:B,re:classloading,pl:accesstransformer:B,pl:rei_plugin_compatibilities:B,pl:mixin:APP:kubejs-common.mixins.json:UtilMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.thread_priorities.UtilMixin,pl:mixin:APP:bettermineshafts.mixins.json:SuppressLogMixin,pl:mixin:APP:blue_skies.mixins.json:UtilMixin,pl:mixin:A}
	at net.minecraft.client.Minecraft.lambda$new$3(Minecraft.java:579) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:rei_plugin_compatibilities:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:hud_batching.MixinMinecraftClient,pl:mixin:APP:kubejs-common.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:immersive_armors.mixins.json:MixinMinecraftClient,pl:mixin:APP:rubidium.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:mixins.blur.json:MixinMinecraftClient,pl:mixin:APP:mixins.oculus.json:MixinMinecraft_PipelineManagement,pl:mixin:APP:mutantmore.mixins.json:MinecraftMixin,pl:mixin:APP:dungeons_libraries.mixins.json:MinecraftMixin,pl:mixin:APP:tslatentitystatus.mixins.json:client.MinecraftMixin,pl:mixin:APP:fastload.mixins.json:client.MinecraftMixin,pl:mixin:APP:cgm.mixins.json:client.MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin,pl:mixin:APP:embeddiumplus.mixin.json:FrameCounter.FpsAccessorMixin,pl:mixin:APP:mixins.satin.client.json:event.MinecraftClientMixin,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:dynmus-common.mixins.json:MinecraftClientMixin,pl:mixin:APP:konkrete.mixin.json:MixinMinecraft,pl:mixin:APP:entity_model_features-common.mixins.json:MixinResourceReload,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.MinecraftClientAccessor,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinMinecraftClient,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinResourceReload,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:anchor-common.client.mixins.json:MinecraftMixin,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:travelerstitles.mixins.json:MinecraftClientTickMixin,pl:mixin:APP:citresewn.mixins.json:citenchantment.MinecraftClientMixin,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.Mixin_RunEssentialTasks,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:compatibility.vanilla.Mixin_WorkaroundBrokenFramebufferBlitBlending,pl:mixin:APP:mixins.essential.json:events.Mixin_RenderTickEvent,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.LoadingOverlay.m_6305_(LoadingOverlay.java:135) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:mixin,pl:runtimedistcleaner:A,re:classloading,pl:rei_plugin_compatibilities:B,pl:mixin:APP:kubejs-common.mixins.json:LoadingOverlayMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:885) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:mixin,pl:accesstransformer:B,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:rei_plugin_compatibilities:B,pl:mixin:APP:pehkui.mixins.json:client.compat115plus.compat1192minus.GameRendererMixin,pl:mixin:APP:supplementaries-common.mixins.json:GameRendererMixin,pl:mixin:APP:mixins.oculus.json:GameRendererAccessor,pl:mixin:APP:mixins.oculus.json:MixinGameRenderer,pl:mixin:APP:mixins.oculus.json:MixinModelViewBobbing,pl:mixin:APP:mixins.oculus.json:MixinTweakFarPlane,pl:mixin:APP:tslatentitystatus.mixins.json:client.GameRendererMixin,pl:mixin:APP:fastload.mixins.json:client.GameRendererMixin,pl:mixin:APP:cgm.mixins.json:client.GameRendererMixin,pl:mixin:APP:pehkui.mixins.json:client.compat115plus.GameRendererMixin,pl:mixin:APP:shouldersurfing.mixins.json:MixinGameRenderer,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:core.compat.MixinGameRenderer,pl:mixin:APP:embeddiumplus.mixin.json:TotalDarkness.MixinGameRenderer,pl:mixin:APP:mixins.satin.client.json:event.GameRendererMixin,pl:mixin:APP:sanitydim.mixins.json:MixinGameRenderer,pl:mixin:APP:justzoom.mixin.json:MixinGameRenderer,pl:mixin:APP:mixins.essential.json:client.renderer.MixinEntityRenderer,pl:mixin:APP:mixins.essential.json:client.renderer.MixinEntityRenderer_Zoom,pl:mixin:APP:create.mixins.json:accessor.GameRendererAccessor,pl:mixin:APP:create.mixins.json:client.GameRendererMixin,pl:mixin:APP:mixins.oculus.json:MixinGameRenderer_NightVisionCompat,pl:mixin:APP:mixins.essential.json:events.Mixin_GuiDrawScreenEvent_Priority,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1115) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:rei_plugin_compatibilities:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:hud_batching.MixinMinecraftClient,pl:mixin:APP:kubejs-common.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:immersive_armors.mixins.json:MixinMinecraftClient,pl:mixin:APP:rubidium.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:mixins.blur.json:MixinMinecraftClient,pl:mixin:APP:mixins.oculus.json:MixinMinecraft_PipelineManagement,pl:mixin:APP:mutantmore.mixins.json:MinecraftMixin,pl:mixin:APP:dungeons_libraries.mixins.json:MinecraftMixin,pl:mixin:APP:tslatentitystatus.mixins.json:client.MinecraftMixin,pl:mixin:APP:fastload.mixins.json:client.MinecraftMixin,pl:mixin:APP:cgm.mixins.json:client.MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin,pl:mixin:APP:embeddiumplus.mixin.json:FrameCounter.FpsAccessorMixin,pl:mixin:APP:mixins.satin.client.json:event.MinecraftClientMixin,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:dynmus-common.mixins.json:MinecraftClientMixin,pl:mixin:APP:konkrete.mixin.json:MixinMinecraft,pl:mixin:APP:entity_model_features-common.mixins.json:MixinResourceReload,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.MinecraftClientAccessor,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinMinecraftClient,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinResourceReload,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:anchor-common.client.mixins.json:MinecraftMixin,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:travelerstitles.mixins.json:MinecraftClientTickMixin,pl:mixin:APP:citresewn.mixins.json:citenchantment.MinecraftClientMixin,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.Mixin_RunEssentialTasks,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:compatibility.vanilla.Mixin_WorkaroundBrokenFramebufferBlitBlending,pl:mixin:APP:mixins.essential.json:events.Mixin_RenderTickEvent,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:700) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:mixin,pl:accesstransformer:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:runtimedistcleaner:A,re:classloading,pl:accesstransformer:B,pl:rei_plugin_compatibilities:B,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick,xf:fml:xaeroworldmap:xaero_wm_minecraft_runtick_render_call,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:hud_batching.MixinMinecraftClient,pl:mixin:APP:kubejs-common.mixins.json:MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.dedicated_reload_executor.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:perf.blast_search_trees.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:feature.measure_time.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.world_leaks.MinecraftMixin,pl:mixin:APP:modernfix-common.mixins.json:bugfix.concurrency.MinecraftMixin,pl:mixin:APP:modernfix-forge.mixins.json:feature.measure_time.MinecraftMixin_Forge,pl:mixin:APP:balm.mixins.json:MinecraftMixin,pl:mixin:APP:immersive_armors.mixins.json:MixinMinecraftClient,pl:mixin:APP:rubidium.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:mixins.blur.json:MixinMinecraftClient,pl:mixin:APP:mixins.oculus.json:MixinMinecraft_PipelineManagement,pl:mixin:APP:mutantmore.mixins.json:MinecraftMixin,pl:mixin:APP:dungeons_libraries.mixins.json:MinecraftMixin,pl:mixin:APP:tslatentitystatus.mixins.json:client.MinecraftMixin,pl:mixin:APP:fastload.mixins.json:client.MinecraftMixin,pl:mixin:APP:cgm.mixins.json:client.MinecraftMixin,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientAccessor,pl:mixin:APP:bettercombat.mixins.json:client.MinecraftClientInject,pl:mixin:APP:flywheel.mixins.json:PausedPartialTickAccessor,pl:mixin:APP:forge-immediatelyfast-common.mixins.json:core.MixinMinecraftClient,pl:mixin:APP:biomemusic.mixins.json:ClientMusicChoiceMixin,pl:mixin:APP:embeddiumplus.mixin.json:FrameCounter.FpsAccessorMixin,pl:mixin:APP:mixins.satin.client.json:event.MinecraftClientMixin,pl:mixin:APP:bookshelf.common.mixins.json:client.AccessorMinecraft,pl:mixin:APP:dynmus-common.mixins.json:MinecraftClientMixin,pl:mixin:APP:konkrete.mixin.json:MixinMinecraft,pl:mixin:APP:entity_model_features-common.mixins.json:MixinResourceReload,pl:mixin:APP:entity_model_features-common.mixins.json:accessor.MinecraftClientAccessor,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinMinecraftClient,pl:mixin:APP:entity_texture_features-common.mixins.json:reloading.MixinResourceReload,pl:mixin:APP:architectury.mixins.json:MixinMinecraft,pl:mixin:APP:anchor-common.client.mixins.json:MinecraftMixin,pl:mixin:APP:blueprint.mixins.json:client.MinecraftMixin,pl:mixin:APP:travelerstitles.mixins.json:MinecraftClientTickMixin,pl:mixin:APP:citresewn.mixins.json:citenchantment.MinecraftClientMixin,pl:mixin:APP:iceberg.mixins.json:MinecraftMixin,pl:mixin:APP:quark.mixins.json:client.MinecraftMixin,pl:mixin:APP:mixins.essential.json:client.Mixin_RunEssentialTasks,pl:mixin:APP:mixins.essential.json:client.MixinMinecraft,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_FixKeybindUnpressedInEmoteWheel,pl:mixin:APP:mixins.essential.json:client.gui.Mixin_RecalculateMenuScale,pl:mixin:APP:mixins.essential.json:compatibility.vanilla.Mixin_WorkaroundBrokenFramebufferBlitBlending,pl:mixin:APP:mixins.essential.json:events.Mixin_RenderTickEvent,pl:mixin:APP:mixins.essential.json:feature.skin_overwrites.Mixin_InstallTrustingServicesKeyInfo,pl:mixin:APP:create.mixins.json:client.WindowResizeMixin,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.m_239872_(Main.java:212) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:classloading,re:mixin,pl:runtimedistcleaner:A,pl:mixin:A,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:51) ~[client-1.19.2-20220805.130853-srg.jar%23803!/:?] {re:classloading,re:mixin,pl:runtimedistcleaner:A,pl:mixin:A,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {re:mixin}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:27) ~[fmlloader-1.19.2-43.3.5.jar%23101!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:30) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-10.0.8.jar%2388!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:141) [bootstraplauncher-1.1.2.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Suspected Mods: NONE
Stacktrace:
	at java.util.ArrayList.add(ArrayList.java:455) ~[?:?] {re:mixin}
-- MOD irons_spellbooks --
Details:
	Mod File: /C:/Users/User/curseforge/minecraft/Instances/Prey/mods/irons_spellbooks-1.19.2-2.0.3.jar
	Failure message: Iron's Spells 'n Spellbooks (irons_spellbooks) encountered an error during the sided_setup event phase
		java.lang.ArrayIndexOutOfBoundsException: Index 87 out of bounds for length 86
	Mod Version: 1.19.2-2.0.3
	Mod Issue URL: https://github.com/iron431/Irons-Spells-n-Spellbooks/issues
	Exception message: java.lang.ArrayIndexOutOfBoundsException: Index 87 out of bounds for length 86
Stacktrace:
	at java.util.ArrayList.add(ArrayList.java:455) ~[?:?] {re:mixin}
	at java.util.ArrayList.add(ArrayList.java:467) ~[?:?] {re:mixin}
	at se.mickelus.tetra.items.modular.impl.holo.gui.craft.HoloStatsGui.addBar(HoloStatsGui.java:124) ~[tetra-1.19.2-5.5.1.jar%23760!/:5.5.1] {re:classloading,pl:rei_plugin_compatibilities:B}
	at io.redspace.ironsspellbooks.compat.tetra.effects.FreezeTetraEffect.addGuiBars(FreezeTetraEffect.java:33) ~[irons_spellbooks-1.19.2-2.0.3.jar%23644!/:1.19.2-2.0.3] {re:classloading,pl:rei_plugin_compatibilities:B}
	at io.redspace.ironsspellbooks.compat.tetra.TetraActualImpl.initClient(TetraActualImpl.java:25) ~[irons_spellbooks-1.19.2-2.0.3.jar%23644!/:1.19.2-2.0.3] {re:classloading,pl:rei_plugin_compatibilities:B}
	at io.redspace.ironsspellbooks.setup.ClientSetup.clientSetup(ClientSetup.java:301) ~[irons_spellbooks-1.19.2-2.0.3.jar%23644!/:1.19.2-2.0.3] {re:classloading,pl:rei_plugin_compatibilities:B}
	at io.redspace.ironsspellbooks.setup.__ClientSetup_clientSetup_FMLClientSetupEvent.invoke(.dynamic) ~[irons_spellbooks-1.19.2-2.0.3.jar%23644!/:1.19.2-2.0.3] {re:classloading,pl:eventbus:B}
	at net.minecraftforge.eventbus.ASMEventHandler.invoke(ASMEventHandler.java:73) ~[eventbus-6.0.3.jar%2385!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:315) ~[eventbus-6.0.3.jar%2385!/:?] {}
	at net.minecraftforge.eventbus.EventBus.post(EventBus.java:296) ~[eventbus-6.0.3.jar%2385!/:?] {}
	at net.minecraftforge.fml.javafmlmod.FMLModContainer.acceptEvent(FMLModContainer.java:114) ~[javafmllanguage-1.19.2-43.3.5.jar%23805!/:?] {}
	at net.minecraftforge.fml.ModContainer.lambda$buildTransitionHandler$10(ModContainer.java:122) ~[fmlcore-1.19.2-43.3.5.jar%23804!/:?] {re:mixin}
	at java.util.concurrent.CompletableFuture$AsyncRun.run(CompletableFuture.java:1804) ~[?:?] {}
	at java.util.concurrent.CompletableFuture$AsyncRun.exec(CompletableFuture.java:1796) ~[?:?] {}
	at java.util.concurrent.ForkJoinTask.doExec(ForkJoinTask.java:373) ~[?:?] {}
	at java.util.concurrent.ForkJoinPool$WorkQueue.topLevelExec(ForkJoinPool.java:1182) ~[?:?] {}
	at java.util.concurrent.ForkJoinPool.scan(ForkJoinPool.java:1655) ~[?:?] {re:mixin,re:computing_frames,pl:rei_plugin_compatibilities:B}
	at java.util.concurrent.ForkJoinPool.runWorker(ForkJoinPool.java:1622) ~[?:?] {re:mixin,re:computing_frames,pl:rei_plugin_compatibilities:B}
	at java.util.concurrent.ForkJoinWorkerThread.run(ForkJoinWorkerThread.java:165) ~[?:?] {re:mixin}


-- System Details --
Details:
	Minecraft Version: 1.19.2
	Minecraft Version ID: 1.19.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.8, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 1538722152 bytes (1467 MiB) / 5385486336 bytes (5136 MiB) up to 8925478912 bytes (8512 MiB)
	CPUs: 20
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i9-10900K CPU @ 3.70GHz
	Identifier: Intel64 Family 6 Model 165 Stepping 5
	Microarchitecture: unknown
	Frequency (GHz): 3.70
	Number of physical packages: 1
	Number of physical CPUs: 10
	Number of logical CPUs: 20
	Graphics card #0 name: NVIDIA GeForce RTX 3080
	Graphics card #0 vendor: NVIDIA (0x10de)
	Graphics card #0 VRAM (MB): 4095.00
	Graphics card #0 deviceId: 0x2206
	Graphics card #0 versionInfo: DriverVersion=31.0.15.4617
	Memory slot #0 capacity (MB): 16384.00
	Memory slot #0 clockSpeed (GHz): 2.13
	Memory slot #0 type: DDR4
	Memory slot #1 capacity (MB): 16384.00
	Memory slot #1 clockSpeed (GHz): 2.13
	Memory slot #1 type: DDR4
	Virtual memory max (MB): 34668.16
	Virtual memory used (MB): 22304.97
	Swap memory total (MB): 2048.00
	Swap memory used (MB): 64.93
	JVM Flags: 4 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx8512m -Xms256m
	Loaded Shaderpack: ComplementaryUnbound_r5.0.1.zip
		Profile: HIGH (+0 options changed by user)
	ModLauncher: 10.0.8+10.0.8+main.0ef7e830
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services:
		mixin-0.8.5.jar mixin PLUGINSERVICE
		eventbus-6.0.3.jar eventbus PLUGINSERVICE
		fmlloader-1.19.2-43.3.5.jar slf4jfixer PLUGINSERVICE
		fmlloader-1.19.2-43.3.5.jar object_holder_definalize PLUGINSERVICE
		fmlloader-1.19.2-43.3.5.jar runtime_enum_extender PLUGINSERVICE
		fmlloader-1.19.2-43.3.5.jar capability_token_subclass PLUGINSERVICE
		accesstransformers-8.0.4.jar accesstransformer PLUGINSERVICE
		fmlloader-1.19.2-43.3.5.jar runtimedistcleaner PLUGINSERVICE
		modlauncher-10.0.8.jar mixin TRANSFORMATIONSERVICE
		modlauncher-10.0.8.jar essential-loader TRANSFORMATIONSERVICE
		modlauncher-10.0.8.jar fml TRANSFORMATIONSERVICE
	FML Language Providers:
		minecraft@1.0
		lowcodefml@null
		javafml@null
		kotlinforforge@3.6.0
	Mod List:
		YungsBetterDungeons-1.19.2-Forge-3.2.2.jar        |YUNG's Better Dungeons        |betterdungeons                |1.19.2-Forge-3.2.2  |ENQUEUE_IM|Manifest: NOSIGNATURE
		MEED-1.19.2-2.4.jar                               |Moderately Enough Effect Descr|meed                          |1.0.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		ftb-essentials-forge-1902.3.4-build.109.jar       |FTB Essentials                |ftbessentials                 |1902.3.4-build.109  |ENQUEUE_IM|Manifest: NOSIGNATURE
		EasyAnvils-v4.0.11-1.19.2-Forge.jar               |Easy Anvils                   |easyanvils                    |4.0.11              |ENQUEUE_IM|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		riverredux-0.3.0+forge.jar                        |RiverRedux                    |riverredux                    |0.3.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		prefab-1.9.2.5.jar                                |Prefab                        |prefab                        |1.9.2.5             |ENQUEUE_IM|Manifest: NOSIGNATURE
		nerb-1.19.2-0.3-FORGE.jar                         |Not Enough Recipe Book        |nerb                          |0.3                 |ENQUEUE_IM|Manifest: NOSIGNATURE
		Entity_Collision_FPS_Fix-forge-1.19-2.0.0.0.jar   |Entity Collision FPS Fix      |entitycollisionfpsfix         |2.0.0.0             |ENQUEUE_IM|Manifest: NOSIGNATURE
		stalwart-dungeons-1.19.2-1.2.8.jar                |Stalwart Dungeons             |stalwart_dungeons             |1.2.8               |ENQUEUE_IM|Manifest: NOSIGNATURE
		modnametooltip-1.20.1-1.20.0.jar                  |Mod Name Tooltip              |modnametooltip                |1.20.0              |ENQUEUE_IM|Manifest: NOSIGNATURE
		hourglass-1.19.1-1.2.1.1.jar                      |Hourglass                     |hourglass                     |1.19.1-1.2.1.1      |ENQUEUE_IM|Manifest: NOSIGNATURE
		ForgeEndertech-1.19.2-10.0.6.1-build.0897.jar     |ForgeEndertech                |forgeendertech                |10.0.6.1            |ENQUEUE_IM|Manifest: NOSIGNATURE
		modernfix-forge-5.9.3+mc1.19.2.jar                |ModernFix                     |modernfix                     |5.9.3+mc1.19.2      |ENQUEUE_IM|Manifest: NOSIGNATURE
		YungsApi-1.19.2-Forge-3.8.10.jar                  |YUNG's API                    |yungsapi                      |1.19.2-Forge-3.8.10 |ENQUEUE_IM|Manifest: NOSIGNATURE
		MaxHealthFix-Forge-1.19.2-8.0.2.jar               |MaxHealthFix                  |maxhealthfix                  |8.0.2               |ENQUEUE_IM|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		lootbeams-1.19.2-1.0.jar                          |LootBeams                     |lootbeams                     |1.0                 |ENQUEUE_IM|Manifest: NOSIGNATURE
		BlockySiege-5.3.0-1.19.2.jar                      |Blocky Siege                  |blocky_siege                  |4.0.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		secretrooms-1.19.2-1.2.0.jar                      |Secret Rooms 6                |secretroomsmod                |1.19.2-1.2.0        |ENQUEUE_IM|Manifest: NOSIGNATURE
		Customized-Dungeon-Loot-1.19-(v.2.1.2).jar        |Customized Dungeon Loot       |cdl                           |2.1.2               |ENQUEUE_IM|Manifest: NOSIGNATURE
		clickadv-1.19.2-3.5.jar                           |clickadv mod                  |clickadv                      |1.19.2-3.5          |ENQUEUE_IM|Manifest: NOSIGNATURE
		balm-forge-1.19.2-4.6.0.jar                       |Balm                          |balm                          |4.6.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		immersive_armors-1.5.6+1.19.2-forge.jar           |Immersive Armors              |immersive_armors              |1.5.6+1.19.2        |ENQUEUE_IM|Manifest: NOSIGNATURE
		projectile_damage-forge-3.2.1+1.19.jar            |Projectile Damage Attribute   |projectile_damage             |3.2.1+1.19          |ENQUEUE_IM|Manifest: NOSIGNATURE
		YungsBetterNetherFortresses-1.19.2-Forge-1.0.6.jar|YUNG's Better Nether Fortresse|betterfortresses              |1.19.2-Forge-1.0.6  |ENQUEUE_IM|Manifest: NOSIGNATURE
		cloth-config-8.3.103-forge.jar                    |Cloth Config v8 API           |cloth_config                  |8.3.103             |ENQUEUE_IM|Manifest: NOSIGNATURE
		ctov-3.2.6c.jar                                   |ChoiceTheorem's Overhauled Vil|ctov                          |3.2.6c              |ENQUEUE_IM|Manifest: NOSIGNATURE
		embeddium-0.2.9+mc1.19.2.jar                      |Embeddium                     |embeddium                     |0.2.9+mc1.19.2      |ENQUEUE_IM|Manifest: NOSIGNATURE
		structure_gel-1.19.2-2.7.3.jar                    |Structure Gel API             |structure_gel                 |2.7.3               |ENQUEUE_IM|Manifest: NOSIGNATURE
		corpse-1.19.2-1.0.0.jar                           |Corpse                        |corpse                        |1.19.2-1.0.0        |ENQUEUE_IM|Manifest: NOSIGNATURE
		Amplified_Nether_1.19.3_v1.2.1.jar                |Amplified Nether              |amplifiednether               |1.2.1               |ENQUEUE_IM|Manifest: NOSIGNATURE
		loot_journal-2.1.jar                              |Loot Journal                  |loot_journal                  |2.1                 |ENQUEUE_IM|Manifest: NOSIGNATURE
		explorify-forge-1.19-1.3.0.jar                    |Explorify                     |explorify                     |1.19-1.3.0          |ENQUEUE_IM|Manifest: NOSIGNATURE
		blur-forge-3.0.1.jar                              |Blur (Forge)                  |blur                          |3.0.1               |ENQUEUE_IM|Manifest: NOSIGNATURE
		StructureCompass-1.19.2-1.4.6.jar                 |Structure Compass Mod         |structurecompass              |1.4.6               |ENQUEUE_IM|Manifest: NOSIGNATURE
		dungeons_plus-1.19.2-1.3.1.jar                    |Dungeons Plus                 |dungeons_plus                 |1.3.1               |ENQUEUE_IM|Manifest: NOSIGNATURE
		volcanic_caverns-1.19.2-1.2.2.jar                 |Volcanic Caverns              |volcanic_caverns              |1.19.2-1.2.2        |ENQUEUE_IM|Manifest: NOSIGNATURE
		resourcefulconfig-forge-1.19.2-1.0.20.jar         |Resourcefulconfig             |resourcefulconfig             |1.0.20              |ENQUEUE_IM|Manifest: NOSIGNATURE
		Highlighter-1.19.1-1.1.4.jar                      |Highlighter                   |highlighter                   |1.1.4               |ENQUEUE_IM|Manifest: NOSIGNATURE
		Philips-Ruins1.19.2-7.8.jar                       |Philip's Ruins                |philipsruins                  |7.8                 |ENQUEUE_IM|Manifest: NOSIGNATURE
		DimensionAccessManager-1.19.2-3.1.0.jar           |Dimension Access Manager      |dimension_access_manager      |3.1.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		assortedtools-1.19.2-6.1.4.jar                    |Assorted Tools                |assortedtools                 |1.19.2-6.1.4        |ENQUEUE_IM|Manifest: NOSIGNATURE
		lightspeed-1.19.2-1.0.5.jar                       |Lightspeed                    |lightspeed                    |1.19.2-1.1.0        |ENQUEUE_IM|Manifest: NOSIGNATURE
		curios-forge-1.19.2-5.1.4.2.jar                   |Curios API                    |curios                        |1.19.2-5.1.4.2      |ENQUEUE_IM|Manifest: NOSIGNATURE
		armorpointspp-forge-1.19.2-3.1.0.jar              |ArmorPoints++                 |armorpointspp                 |1.19.2-3.1.0        |ENQUEUE_IM|Manifest: NOSIGNATURE
		oculus-mc1.19.2-1.6.9.jar                         |Oculus                        |oculus                        |1.6.9               |ENQUEUE_IM|Manifest: NOSIGNATURE
		reforgium-1.0.12a.jar                             |Reforgium                     |reforgium                     |1.0.12a             |ENQUEUE_IM|Manifest: NOSIGNATURE
		Hostile_Delight_0.2.1_1.19.2.jar                  |Hostile_Delight               |hostiledelight                |1.0.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		pluto-mc1.19.2-0.0.9.jar                          |Pluto                         |pluto                         |0.0.9               |ENQUEUE_IM|Manifest: NOSIGNATURE
		brrp-618156-4422602.jar                           |Better Runtime Resource Pack  |better_runtime_resource_pack  |0.9.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		mutantmore-1.19.2-early-access-1.0.7.jar          |Mutant More                   |mutantmore                    |1.0                 |ENQUEUE_IM|Manifest: NOSIGNATURE
		lategamegolems-1.19.2-1.3.0.2.jar                 |Late Game Golems              |lategamegolems                |1.19.2-1.3.0.2      |ENQUEUE_IM|Manifest: NOSIGNATURE
		YungsBetterEndIsland-1.19.2-Forge-1.0.jar         |YUNG's Better End Island      |betterendisland               |1.19.2-Forge-1.0    |ENQUEUE_IM|Manifest: NOSIGNATURE
		EnhancedAI-1.8.4-mc1.19.2.jar                     |Enhanced AI                   |enhancedai                    |1.8.4               |ENQUEUE_IM|Manifest: NOSIGNATURE
		JadeAddons-1.19.2-forge-3.6.0.jar                 |Jade Addons                   |jadeaddons                    |3.6.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		windswept-1.19.2-2.2.3.jar                        |Windswept                     |windswept                     |2.2.3               |ENQUEUE_IM|Manifest: NOSIGNATURE
		toms_storage-1.19-1.5.9.jar                       |Tom's Simple Storage Mod      |toms_storage                  |1.5.9               |ENQUEUE_IM|Manifest: NOSIGNATURE
		EasyShulkerBoxes-v4.4.1-1.19.2-Forge.jar          |Easy Shulker Boxes            |easyshulkerboxes              |4.4.1               |ENQUEUE_IM|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		FastLeafDecay-30.jar                              |FastLeafDecay                 |fastleafdecay                 |30                  |ENQUEUE_IM|Manifest: NOSIGNATURE
		CodeChickenLib-1.19.2-4.3.1.481-universal.jar     |CodeChicken Lib               |codechickenlib                |4.3.1.481           |ENQUEUE_IM|Manifest: 31:e6:db:63:47:4a:6e:e0:0a:2c:11:d1:76:db:4e:82:ff:56:2d:29:93:d2:e5:02:bd:d3:bd:9d:27:47:a5:71
		CleanView-1.19.2-v1.jar                           |CleanView                     |cleanview                     |1.19.2-v1           |ENQUEUE_IM|Manifest: 5e:ed:25:99:e4:44:14:c0:dd:89:c1:a9:4c:10:b5:0d:e4:b1:52:50:45:82:13:d8:d0:32:89:67:56:57:01:53
		YungsBetterMineshafts-1.19.2-Forge-3.2.1.jar      |YUNG's Better Mineshafts      |bettermineshafts              |1.19.2-Forge-3.2.1  |ENQUEUE_IM|Manifest: NOSIGNATURE
		NekosEnchantedBooks-1.19-1.8.0.jar                |Neko's Enchanted Books        |nebs                          |1.8.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		dungeons_libraries-1.19.2-3.0.10-beta.jar         |Dungeons Libraries            |dungeons_libraries            |1.19.2-3.0.10-beta  |ENQUEUE_IM|Manifest: NOSIGNATURE
		dungeons_gear-1.19.2-5.0.5-beta.jar               |Dungeons Gear                 |dungeons_gear                 |1.19.2-5.0.5-beta   |ENQUEUE_IM|Manifest: NOSIGNATURE
		crafting-on-a-stick-1.19.2-1.0.5.jar              |Crafting On A Stick           |crafting_on_a_stick           |1.0.5               |ENQUEUE_IM|Manifest: NOSIGNATURE
		Essential (forge_1.19.2).jar                      |Essential                     |essential                     |1.2.3.1+g169bd9af6a |ENQUEUE_IM|Manifest: NOSIGNATURE
		YungsBetterJungleTemples-1.19.2-Forge-1.0.1.jar   |YUNG's Better Jungle Temples  |betterjungletemples           |1.19.2-Forge-1.0.1  |ENQUEUE_IM|Manifest: NOSIGNATURE
		THT-1.19.2-4.3.1.jar                              |Tan's Huge Trees              |tht                           |4.3.1               |ENQUEUE_IM|Manifest: NOSIGNATURE
		TES-forge-1.19.2-1.2.1.jar                        |TES                           |tslatentitystatus             |1.2.1               |ENQUEUE_IM|Manifest: NOSIGNATURE
		elytraslot-forge-6.1.1+1.19.2.jar                 |Elytra Slot                   |elytraslot                    |6.1.1+1.19.2        |ENQUEUE_IM|Manifest: NOSIGNATURE
		StylishEffects-v4.3.4-1.19.2-Forge.jar            |Stylish Effects               |stylisheffects                |4.3.4               |ENQUEUE_IM|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		puffish_skills-0.4.0-1.19.2-forge.jar             |Pufferfish's Skills           |puffish_skills                |0.4.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		Fastload-Reforged-mc1.19.2-3.4.0.jar              |Fastload-Reforged             |fastload                      |3.4.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		projectileimmunityfix_1.0.0_1.19.2backport.jar    |ProjectileImmunityFix         |projectileimmunityfix         |1.0.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		MutantMonsters-v4.0.6-1.19.2-Forge.jar            |Mutant Monsters               |mutantmonsters                |4.0.6               |ENQUEUE_IM|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		endertrigon-1.0.jar                               |Ender Trigon                  |endertrigon                   |1.0                 |ENQUEUE_IM|Manifest: NOSIGNATURE
		coralreef-forge-1.19-1.0.2.jar                    |Coral Reef                    |coralreef                     |1.19-1.0.2          |ENQUEUE_IM|Manifest: NOSIGNATURE
		cgm-forge-1.19.2-1.3.7.jar                        |MrCrayfish's Gun Mod          |cgm                           |1.3.7               |ENQUEUE_IM|Manifest: NOSIGNATURE
		Mutagenesis 1.19.2.jar                            |Mutagenesis                   |mutagenesis                   |1.0.1               |ENQUEUE_IM|Manifest: NOSIGNATURE
		VisualWorkbench-v4.2.4-1.19.2-Forge.jar           |Visual Workbench              |visualworkbench               |4.2.4               |ENQUEUE_IM|Manifest: 9a:09:85:98:65:c4:8c:11:c5:49:f6:d6:33:23:39:df:8d:b4:ff:92:84:b8:bd:a5:83:9f:ac:7f:2a:d1:4b:6a
		AttributeFix-Forge-1.19.2-17.2.7.jar              |AttributeFix                  |attributefix                  |17.2.7              |ENQUEUE_IM|Manifest: eb:c4:b1:67:8b:f9:0c:db:dc:4f:01:b1:8e:61:64:39:4c:10:85:0b:a6:c4:c7:48:f0:fa:95:f2:cb:08:3a:e5
		Pehkui-3.7.11+1.19.2-forge.jar                    |Pehkui                        |pehkui                        |3.7.11+1.19.2-forge |ENQUEUE_IM|Manifest: NOSIGNATURE
		libraryferret-forge-1.19.2-4.0.0.jar              |Library ferret                |libraryferret                 |4.0.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		epicsamurai-0.0.16-1.19.2-forge.jar               |Epic Samurai                  |epicsamurai                   |0.0.16-1.19.2-forge |ENQUEUE_IM|Manifest: NOSIGNATURE
		caelus-forge-1.19.2-3.0.0.6.jar                   |Caelus API                    |caelus                        |1.19.2-3.0.0.6      |ENQUEUE_IM|Manifest: NOSIGNATURE
		Paxi-1.19.2-Forge-3.0.1.jar                       |Paxi                          |paxi                          |1.19.2-Forge-3.0.1  |ENQUEUE_IM|Manifest: NOSIGNATURE
		colytra-forge-6.0.2+1.19.2.jar                    |Colytra                       |colytra                       |6.0.2+1.19.2        |ENQUEUE_IM|Manifest: NOSIGNATURE
		immersive_weathering-1.19.2-1.2.10-forge.jar      |Immersive Weathering          |immersive_weathering          |1.19.2-1.2.10       |ENQUEUE_IM|Manifest: NOSIGNATURE
		realmrpg_fallen_adventurers_1.0.2_forge_1.19.2.jar|Realm RPG: Fallen Adventurers |realmrpg_skeletons            |1.0.2               |ENQUEUE_IM|Manifest: NOSIGNATURE
		integrated_api_forge-1.2.7+1.19.2.jar             |Integrated API                |integrated_api                |1.2.7+1.19.2        |ENQUEUE_IM|Manifest: NOSIGNATURE
		NaturesCompass-1.19.2-1.10.0-forge.jar            |Nature's Compass              |naturescompass                |1.19.2-1.10.0-forge |ENQUEUE_IM|Manifest: NOSIGNATURE
		burninthesun-forge-1.19.2-1.4.3.jar               |Burn in the Sun               |burninthesun                  |1.4.3               |ENQUEUE_IM|Manifest: NOSIGNATURE
		starlight-1.1.1+forge.cf5b10b.jar                 |Starlight                     |starlight                     |1.1.1+forge.a3aea74 |ENQUEUE_IM|Manifest: NOSIGNATURE
		davespotioneering-1.19.2-2.jar                    |Dave's Potioneering           |davespotioneering             |1.19.2-2            |ENQUEUE_IM|Manifest: NOSIGNATURE
		questsadditions-1.19.2-1.4.2.jar                  |Quests Additions              |questsadditions               |1.4.2               |ENQUEUE_IM|Manifest: NOSIGNATURE
		catalogue-1.7.0-1.19.2.jar                        |Catalogue                     |catalogue                     |1.7.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		tetratic-combat-1.19-2.6.3.jar                    |Tetratic Combat               |tetraticcombat                |2.6.3               |ENQUEUE_IM|Manifest: NOSIGNATURE
		forge-1.19.2-43.3.5-universal.jar                 |Forge                         |forge                         |43.3.5              |ENQUEUE_IM|Manifest: 84:ce:76:e8:45:35:e4:0e:63:86:df:47:59:80:0f:67:6c:c1:5f:6e:5f:4d:b3:54:47:1a:9f:7f:ed:5e:f2:90
		THEUNDEADREVAMPED_0.8c_1.19.2.jar                 |Undead_revamp2                |undead_revamp2                |1.0.0               |ENQUEUE_IM|Manifest: NOSIGNATURE
		Log-Begone-Forge-1.19-1.0.6.jar                   |Log Begone                    |logbegone                     |1.0.6               |ENQUEUE_IM|Manifest: NOSIGNATURE
