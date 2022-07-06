# Commands XIII

```lua
r_flashlightlockposition "0"
r_flashlightmodels "1"
r_flashlightnear "4"
r_flashlightnodraw "0"
r_flashlightoffsetx "10"
r_flashlightoffsety "-20"
r_flashlightoffsetz "24"
r_flashlightquadratic "0"
r_flashlightrender "1"
r_flashlightrendermodels "1"
r_flashlightrenderworld "1"
r_flashlightscissor "0"
r_flashlightshadowatten "0"
r_flashlightupdatedepth "1"
r_flashlightvisualizetrace "0"
r_flex "1"
r_flushlod // Flush and reload LODs.
r_ForceWaterLeaf "1" // Enable for optimization to water - considers view in leaf under water for purposes of culling
r_frustumcullworld "1"
r_glint_alwaysdraw "0"
r_glint_procedural "0"
r_hunkalloclightmaps "0"
r_hwmorph "1"
r_itemblinkmax "0"
r_itemblinkrate "4"
r_JeepFOV "90"
r_JeepViewBlendTo "0"
r_JeepViewBlendToScale "0"
r_JeepViewBlendToTime "1"
r_lightaverage "1" // Activates/deactivate light averaging
r_lightcachecenter "1"
r_lightcachemodel "-1"
r_lightcache_numambientsamples "162" // number of random directions to fire rays when computing ambient lighting
r_lightcache_zbuffercache "0"
r_lightinterp "5" // 0 turns off interpolation
r_lightmap "-1"
r_lightstyle "-1"
r_lightwarpidentity "0"
r_lockpvs "0" // Lock the PVS so you can fly around and inspect what is being drawn.
r_lod "-1"
r_mapextents "16384" // Set the max dimension for the map. This determines the far clipping plane
r_maxdlights "32"
r_maxmodeldecal "50"
r_maxnewsamples "6"
r_maxsampledist "128"
r_minnewsamples "3"
r_modelwireframedecal "0"
r_newflashlight "1"
r_nohw "0"
r_norefresh "0"
r_nosw "0"
r_novis "0" // Turn off the PVS.
r_occludeemaxarea "0" // Prevents occlusion testing for entities that take up more than X% of the screen. 0 means use whatever the level said to use.
r_occluderminarea "0" // Prevents this occluder from being used if it takes up less than X% of the screen. 0 means use whatever the level said to use.
r_occludermincount "0" // no matter how big they are.
r_occlusion "1" // Activate/deactivate the occlusion system.
r_occlusionspew "0" // Activate/deactivates spew about what the occlusion system is doing.
r_oldlightselection "0" // Set this to revert to HL2s method of selecting lights
r_overlayfadeenable "0"
r_overlayfademax "2000"
r_overlayfademin "1750"
r_overlaywireframe "0"
r_particle_sim_spike_threshold_ms "5"
r_partition_level "-1" // Displays a particular level of the spatial partition system. Use -1 to disable it.
r_PhysPropStaticLighting "1"
r_pixelfog "1"
r_pixelvisibility_partial "1"
r_pixelvisibility_spew "0"
r_pix_recordframes "0"
r_pix_start "0"
r_portalsopenall "0" // Open all portals
r_PortalTestEnts "1" // Clip entities against portal frustums.
r_printdecalinfo
r_projectedtexture_filter "1"
r_proplightingfromdisk "1" // 2=Show Errors
r_proplightingpooling "-1" // 1 - static prop color meshes are allocated from a single shared vertex buffer (on hardware that supports stream offset
r_propsmaxdist "1200" // Maximum visible distance
r_queued_decals "0" // Offloads a bit of decal rendering setup work to the material system queue when enabled.
r_queued_post_processing "0"
r_queued_ropes "1"
r_radiosity "4" // 0: no radiosity 1: radiosity with ambient cube (6 samples) 2: radiosity with 162 samples 3: 162 samples for static props, 6 sam
r_rainalpha "0"
r_rainalphapow "0"
r_raindensity "0"
r_RainHack "0"
r_rainlength "0"
r_RainProfile "0" // Enable/disable rain profiling.
r_RainRadius "1500"
r_RainSideVel "130" // How much sideways velocity rain gets.
r_RainSimulate "1" // Enable/disable rain simulation.
r_rainspeed "600"
r_RainSplashPercentage "20"
r_rainwidth "0"
r_randomflex "0"
r_renderoverlayfragment "1"
r_rimlight "1"
r_rootlod "0" // Root LOD
r_ropetranslucent "1"
r_screenfademaxsize "0"
r_screenfademinsize "0"
r_screenoverlay // Draw specified material as an overlay
r_sequence_debug "0"
r_shader_srgb "0" // -1 = use hardware caps. 0 = use hardware srgb. 1 = use shader srgb(software lookup)
r_shadowangles // Set shadow angles
r_shadowblobbycutoff // some shadow stuff
r_shadowcolor // Set shadow color
r_shadowdir // Set shadow direction
r_shadowdist // Set shadow distance
r_shadowids "0"
r_shadowmaxrendered "32"
r_shadowrendertotexture "1"
r_shadows "1"
r_shadows_gamecontrol "-1"
r_shadowwireframe "0"
r_showenvcubemap "0"
r_ShowViewerArea "0"
r_showz_power "1"
r_skin "0"
r_skybox "1" // Enable the rendering of sky boxes
r_snapportal "-1"
r_SnowColorBlue "200" // Snow.
r_SnowColorGreen "175" // Snow.
r_SnowColorRed "150" // Snow.
r_SnowDebugBox "0" // Snow Debug Boxes.
r_SnowEnable "1" // Snow Enable
r_SnowEndAlpha "255" // Snow.
r_SnowEndSize "0" // Snow.
r_SnowFallSpeed "1" // Snow fall speed scale.
r_SnowInsideRadius "256" // Snow.
r_SnowOutsideRadius "1024" // Snow.
r_SnowParticles "500" // Snow.
r_SnowPosScale "1" // Snow.
r_SnowRayEnable "1" // Snow.
r_SnowRayLength "8192" // Snow.
r_SnowRayRadius "256" // Snow.
r_SnowSpeedScale "1" // Snow.
r_SnowStartAlpha "25" // Snow.
r_SnowStartSize "1" // Snow.
r_SnowWindScale "0" // Snow.
r_SnowZoomOffset "384" // Snow.
r_SnowZoomRadius "512" // Snow.
r_spray_lifetime "2" // Number of rounds player sprays are visible
r_sse2 // Enable/disable SSE2 code
r_sse_s "1" // sse ins for particle sphere create
r_staticpropinfo "0"
r_staticprop_lod "-1"
r_studio_stats "0"
r_studio_stats_lock "0" // Lock the current studio stats entity selection
r_studio_stats_mode "0" // Sets a mode for r_studio_stats. Modes are as follows: 0 = Entity under your crosshair 1 = Weapon held by player under your cr
r_swingflashlight "1"
r_teeth "1"
r_threaded_client_shadow_manager "0"
r_threaded_particles "1"
r_threaded_renderables "0"
r_unloadlightmaps "0"
r_updaterefracttexture "1"
r_vehicleBrakeRate "1"
r_VehicleViewClamp "1"
r_VehicleViewDampen "0"
r_visambient "0" // Draw leaf ambient lighting samples. Needs mat_leafvis 1 to work
r_visocclusion "0" // Activate/deactivate wireframe rendering of what the occlusion system is doing.
r_visualizelighttraces "0"
r_visualizelighttracesshowfulltrace "0"
r_visualizeproplightcaching "0"
r_visualizetraces "0"
r_WaterDrawReflection "1" // Enable water reflection
r_WaterDrawRefraction "1" // Enable water refraction
r_waterforceexpensive "1"
r_waterforcereflectentities "0"
r_worldlightmin "0"
r_worldlights "4" // number of world lights to use per vertex
r_worldlistcache "1"
save // Saves current game.
save_async "1"
save_asyncdelay "0" // adds this many milliseconds of delay to the save operation.
save_console "0" // Autosave on the PC behaves like it does on the consoles.
save_disable "0"
save_finish_async
save_history_count "1" // Keep this many old copies in history of autosaves and quicksaves.
save_huddelayframes "1" // Number of frames to defer for drawing the Saving message.
save_in_memory "0" // Set to 1 to save to memory instead of disk (Xbox 360)
save_noxsave "0"
save_screenshot "1" // 2 = always
save_spew "0"
say // Display player message
say_team // Display player message to team
sbox_godmode "1"
sbox_maxballoons "20"
sbox_maxbuttons "50"
sbox_maxdynamite "10"
sbox_maxeffects "50"
sbox_maxemitters "20"
sbox_maxhoverballs "50"
sbox_maxlamps "5"
sbox_maxlights "5"
sbox_maxnpcs "0"
sbox_maxprops "100"
sbox_maxragdolls "2"
sbox_maxsents "512"
sbox_maxspawners "2"
sbox_maxthrusters "50"
sbox_maxturrets "4"
sbox_maxvehicles "3"
sbox_maxwheels "50"
sbox_noclip "1"
sbox_plpldamage "1"
sbox_weapons "1"
sb_mod_suggested_maxplayers "0"
sb_quick_list_bit_field "-1"
sb_showblacklists "0" // blacklist rules will be printed to the console as theyre applied.
scene_async_prefetch_spew "0" // Display async .ani file loading info.
scene_clamplookat "1" // Clamp head turns to a max of 20 degrees per think.
scene_clientflex "1" // Do client side flex animation.
scene_flatturn "1"
scene_flush // Flush all .vcds from the cache and reload from disk.
scene_forcecombined "0" // force use of combined .wav files even in english.
scene_maxcaptionradius "1200" // Only show closed captions if recipient is within this many units of speaking actor (0==disabled). 
```
