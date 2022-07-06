# Commands VII

```lua
map2 // <map> <gamemode> - Start a map with named gamemode instead of the default
mapcyclefile "0" // Name of the .txt file used to cycle the maps on multiplayer servers
maps // Displays list of maps.
map_background // Runs a map as the background to the main menu.
map_commentary // on a specified map.
map_edit
map_noareas "0" // Disable area to area connection testing.
matchmakingport "27025" // Host Matchmaking port
mat_aaquality "0"
mat_accelerate_adjust_exposure_down "3"
mat_alphacoverage "1"
mat_antialias "0"
mat_autoexposure_max "2"
mat_autoexposure_min "0"
mat_bloomamount_rate "0"
mat_bloomscale "1"
mat_bloom_scalefactor_scalar "1"
mat_bufferprimitives "1"
mat_bumpbasis "0"
mat_bumpmap "1"
mat_camerarendertargetoverlaysize "128"
mat_clipz "1"
mat_colcorrection_disableentities "0" // Disable map color-correction entities
mat_colorcorrection "1"
mat_color_projection "0"
mat_compressedtextures "1"
mat_configcurrent // show the current video control panel config for the material system
mat_crosshair // Display the name of the material under the crosshair
mat_crosshair_edit // open the material under the crosshair in the editor defined by mat_crosshair_edit_editor
mat_crosshair_explorer // open the material under the crosshair in explorer and highlight the vmt file
mat_crosshair_printmaterial // print the material under the crosshair
mat_crosshair_reloadmaterial // reload the material under the crosshair
mat_debugalttab "0"
mat_debugdepth "0"
mat_debugdepthmode "0"
mat_debugdepthval "128"
mat_debugdepthvalmax "256"
mat_debug_autoexposure "0"
mat_debug_bloom "0"
mat_debug_postprocessing_effects "0" // 2 = only apply post-processing to the centre of the screen
mat_debug_process_halfscreen "0"
mat_depthbias_decal "-262144"
mat_depthbias_normal "0"
mat_depthbias_shadowmap "0"
mat_diffuse "1"
mat_disablehwmorph "0" // Disables HW morphing for particular mods
mat_disable_bloom "0"
mat_disable_d3d9ex "0" // Disables Windows Aero DirectX extensions (may positively or negatively affect performance depending on video drivers)
mat_disable_fancy_blending "0"
mat_disable_lightwarp "0"
mat_disable_ps_patch "0"
mat_drawflat "0"
mat_drawTexture "0" // Enable debug view texture
mat_drawTextureScale "1" // Debug view texture scale
mat_drawTitleSafe "0" // Enable title safe overlay
mat_drawwater "1"
mat_dump_rts "0"
mat_dxlevel "95"
mat_dynamic_tonemapping "1"
mat_edit // Bring up the material under the crosshair in the editor
mat_envmapsize "128"
mat_envmaptgasize "32"
mat_excludetextures "0"
mat_exposure_center_region_x "0"
mat_exposure_center_region_x_flashlight "0"
mat_exposure_center_region_y "0"
mat_exposure_center_region_y_flashlight "0"
mat_fastclip "0"
mat_fastnobump "0"
mat_fastspecular "1" // Enable/Disable specularity for visual testing. Will not reload materials and will not affect perf.
mat_fillrate "0"
mat_filterlightmaps "1"
mat_filtertextures "1"
mat_forceaniso "1"
mat_forcedynamic "0"
mat_forcehardwaresync "1"
mat_forcemanagedtextureintohardware "0"
mat_force_bloom "0"
mat_force_ps_patch "0"
mat_force_tonemap_scale "0"
mat_framebuffercopyoverlaysize "128"
mat_frame_sync_enable "1"
mat_frame_sync_force_texture "0" // Force frame syncing to lock a managed texture.
mat_fullbright "0"
mat_hdr_enabled // Report if HDR is enabled for debugging
mat_hdr_level "2" // and 2 for full HDR on HDR maps.
mat_hdr_manual_tonemap_rate "1"
mat_hdr_tonemapscale "1" // 16 = eyes wide open.
mat_hdr_uncapexposure "0"
mat_hsv "0"
mat_info // Shows material system info
mat_leafvis "0" // Draw wireframe of current leaf
mat_levelflush "1"
mat_lightmap_pfms "0" // Outputs .pfm files containing lightmap data for each lightmap page when a level exits.
mat_loadtextures "1"
mat_luxels "0"
mat_managedtextures "1" // allows Direct3D to manage texture uploading at the cost of extra system memory
mat_maxframelatency "1"
mat_max_worldmesh_vertices "65536"
mat_measurefillrate "0"
mat_mipmaptextures "1"
mat_monitorgamma "2" // monitor gamma (typically 2.2 for CRT and 1.7 for LCD)
mat_monitorgamma_tv_enabled "0"
mat_monitorgamma_tv_exp "2"
mat_monitorgamma_tv_range_max "255"
mat_monitorgamma_tv_range_min "16"
mat_morphstats "0"
mat_motion_blur_enabled "0"
mat_motion_blur_falling_intensity "1"
mat_motion_blur_falling_max "20"
mat_motion_blur_falling_min "10"
mat_motion_blur_forward_enabled "0"
mat_motion_blur_percent_of_screen_max "4"
mat_motion_blur_rotation_intensity "1"
mat_motion_blur_strength "1"
mat_non_hdr_bloom_scalefactor "0"
mat_norendering "0"
mat_normalmaps "0"
mat_normals "0"
mat_parallaxmap "0"
mat_picmip "0"
mat_postprocessing_combine "1" // software anti-aliasing and color correction into one post-processing pass
mat_postprocess_x "4"
mat_postprocess_y "1"
mat_powersavingsmode "0" // Power Savings Mode
mat_proxy "0"
mat_queue_mode "-2" // 1=queued sing
mat_reducefillrate "0"
mat_reduceparticles "0"
mat_reloadallmaterials // Reloads all materials
mat_reloadmaterial // Reloads a single material
mat_reloadtextures // Reloads all textures
mat_remoteshadercompile "0"
mat_reporthwmorphmemory // Reports the amount of size in bytes taken up by hardware morph textures.
mat_report_queue_status "0"
mat_reversedepth "0"
mat_savechanges // saves current video configuration to the registry
mat_setvideomode // windowed state of the material system
mat_shadowstate "1"
mat_showcamerarendertarget "0"
mat_showenvmapmask "0"
mat_showframebuffertexture "0"
mat_showlightmappage "-1"
mat_showlowresimage "0"
mat_showmaterials // Show materials.
mat_showmaterialsverbose // Show materials (verbose version).
mat_showmiplevels "0" // 1: everything else
mat_showtextures // Show used textures.
mat_showwatertextures "0"
mat_show_ab_hdr "0"
mat_show_ab_hdr_hudelement "0" // HDR Demo HUD Element toggle.
mat_show_histogram "0"
mat_show_texture_memory_usage "0" // Display the texture memory usage on the HUD.
mat_slopescaledepthbias_decal "0"
mat_slopescaledepthbias_normal "0"
mat_slopescaledepthbias_shadowmap "5"
mat_softwarelighting "0"
mat_softwareskin "0"
mat_software_aa_blur_one_pixel_lines "0" // (1.0 - lots)
mat_software_aa_debug "0" // (2 - show anti-a
mat_software_aa_edge_threshold "1" // Software AA - adjusts the sensitivity of the software AA shaders edge detection (default 1.0 - a lower value will soften more
mat_software_aa_quality "0" // (1 - 9-tap filter)
mat_software_aa_strength "-1" // Software AA - perform a software anti-aliasing post-process (an alternative/supplement to MSAA). This value sets the strength o
mat_software_aa_strength_vgui "-1" // but forced to this value when called by the post vgui AA pass.
mat_software_aa_tap_offset "1" // Software AA - adjusts the displacement of the taps used by the software AA shader (default 1.0 - a lower value will make the im
mat_specular "1" // Enable/Disable specularity for perf testing. Will cause a material reload upon change.
mat_spewvertexandpixelshaders // Print all vertex and pixel shaders currently loaded to the console
mat_stub "0"
mat_supportflashlight "1" // 1 - flashlight is supported
mat_surfaceid "0"
mat_surfacemat "0"
mat_texture_limit "-1" // the material system will limit the amount of texture memory it uses in a frame. Useful for identifying
mat_texture_list "0" // show a list of used textures per frame
mat_texture_list_all "0" // then the texture list panel will show all currently-loaded textures.
mat_texture_list_content_path "0" // itll assume your content directory is next to the currently runn
mat_texture_list_txlod // -1 to dec resolution
mat_texture_list_txlod_sync // save - saves all changes to material content files
mat_texture_list_view "1" // then the texture list panel will render thumbnails of currently-loaded textures.
mat_tonemapping_occlusion_use_stencil "0"
mat_tonemap_algorithm "1" // 0 = Original Algorithm 1 = New Algorithm
mat_tonemap_min_avglum "3"
mat_tonemap_percent_bright_pixels "2"
mat_tonemap_percent_target "60"
mat_trilinear "1"
mat_use_compressed_hdr_textures "1"
```
