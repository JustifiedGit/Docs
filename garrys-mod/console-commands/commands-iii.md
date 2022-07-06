# Commands III

```lua
cl_detail_avoid_force "0" // percentage of the width of the detail sprite )
cl_detail_avoid_radius "30" // radius around detail sprite to avoid players
cl_detail_avoid_recover_speed "1" // how fast to recover position after avoiding players
cl_detail_max_sway "10" // Amplitude of the detail prop sway
cl_detail_multiplier "1" // extra details to create
cl_disablehtmlmotd "0" // Disable HTML motds.
cl_downloadfilter "0" // nosounds)
cl_drawhud "1" // Enable the rendering of the hud
cl_drawleaf "-1"
cl_drawmaterial "0" // Draw a particular material over the frame
cl_drawmonitors "1"
cl_drawownshadow "0" // Draw own shadow in first person mode
cl_drawshadowtexture "0"
cl_draw_airboat_wake "1"
cl_dump_particle_stats // dump particle profiling info to particle_profile.csv
cl_ejectbrass "1"
cl_entityreport "0" // draw entity states to console
cl_entityreport_sorted "0" // 3 = peak
cl_ent_absbox // Displays the clients absbox for the entity under the crosshair.
cl_ent_bbox // Displays the clients bounding box for the entity under the crosshair.
cl_ent_rbox // Displays the clients render box for the entity under the crosshair.
cl_extrapolate "1" // Enable/disable extrapolation if interpolation history runs out.
cl_extrapolate_amount "0" // Set how many seconds the client will extrapolate entities for.
cl_fastdetailsprites "1" // whether to use new detail sprite system
cl_fasttempentcollision "5"
cl_find_ent // Find and list all client entities with classnames that contain the specified substring. Format: cl_find_ent <substring>
cl_find_ent_index // Display data for clientside entity matching specified index. Format: cl_find_ent_index <index>
cl_flushentitypacket "0" // For debugging. Force the engine to flush an entity packet.
cl_forcepreload "0" // Whether we should force preloading.
cl_forwardspeed "450"
cl_fullupdate // Forces the server to send a full update packet
cl_hudhint_sound "1" // Disable hudhint sounds.
cl_idealpitchscale "0"
cl_ignorepackets "0" // Force client to ignore packets (for debugging).
cl_interp "0" // Sets the interpolation amount (bounded on low side by server interp ratio settings).
cl_interp_all "0" // Disable interpolation list optimizations.
cl_interp_npcs "0" // if greater)
cl_interp_ratio "2" // Sets the interpolation amount (final amount is cl_interp_ratio / cl_updaterate).
cl_jiggle_bone_debug "0" // Display physics-based jiggle bone debugging information
cl_jiggle_bone_debug_pitch_constraints "0" // Display physics-based jiggle bone debugging information
cl_jiggle_bone_debug_yaw_constraints "0" // Display physics-based jiggle bone debugging information
cl_jiggle_bone_framerate_cutoff "45" // Skip jiggle bone simulation if framerate drops below this value (frames/second)
cl_lagcompensation "1" // Perform server side lag compensation of weapon firing events.
cl_language "0" // Language (from HKCUSoftwareValveSteamLanguage)
cl_leveloverview "0"
cl_leveloverviewmarker "0"
cl_localnetworkbackdoor "1" // Enable network optimizations for single player games.
cl_logofile "0" // Spraypoint logo decal.
cl_maxrenderable_dist "3000" // Max distance from the camera at which things will be rendered
cl_mouseenable "1"
cl_mouselook "1" // 0 for keyboard look. Cannot be set while connected to a server.
cl_new_impact_effects "0"
cl_npc_speedmod_intime "0"
cl_npc_speedmod_outtime "1"
cl_observercrosshair "1"
cl_overdraw_test "0"
cl_panelanimation // Shows panel animation variables: <panelname | blank for all panels>.
cl_particleeffect_aabb_buffer "2" // it wont have to be reinserted as oft
cl_particles_dump_effects
cl_particles_show_bbox "0"
cl_particle_batch_mode "1"
cl_particle_max_count "0"
cl_particle_retire_cost "0"
cl_pclass "0" // Dump entity by prediction classname.
cl_pdump "-1" // Dump info about this entity to screen.
cl_phys_props_enable "1" // Disable clientside physics props (must be set before loading a level).
cl_phys_props_max "300" // Maximum clientside physic props
cl_phys_props_respawndist "1500" // Minimum distance from the player that a clientside prop must be before its allowed to respawn.
cl_phys_props_respawnrate "60" // between clientside prop respawns.
cl_phys_timescale "1" // Sets the scale of time for client-side physics (ragdolls)
cl_pitchdown "89"
cl_pitchspeed "225" // Client pitch speed.
cl_pitchup "89"
cl_playback_screenshots "0" // Allows the client to playback screenshot and jpeg commands in demos.
cl_playermodel "0" // Default Player Model
cl_playerspraydisable "0" // Disable player sprays.
cl_precacheinfo // Show precache info (client).
cl_predict "1" // Perform client side prediction.
cl_predictionlist "0" // Show which entities are predicting
cl_predictweapons "1" // Perform client side prediction of weapon effects.
cl_pred_optimize "2" // and also for not repredicting if there were no errors (2)
cl_pred_track // for field fieldname.
cl_ragdoll_collide "0"
cl_removedecals // Remove the decals from the entity under the crosshair.
cl_resend "6" // Delay in seconds before the client will resend the connect attempt
cl_rumblescale "1" // Scale sensitivity of rumble effects (0 to 1.0)
cl_screenshotname "0" // Custom Screenshot name
cl_SetupAllBones "0"
cl_shadowtextureoverlaysize "256"
cl_showbattery "0" // Draw current battery level at top of screen when on battery power
cl_ShowBoneSetupEnts "0" // Show which entities are having their bones setup each frame.
cl_showdemooverlay "0" // -1 - show always)
cl_showents // Dump entity list to console.
cl_showerror "0" // 2 for above plus detailed field deltas.
cl_showevents "0" // Print event firing info in the console
cl_showfps "0" // 2 = smooth fps)
cl_showhelp "1" // Set to 0 to not show on-screen help
cl_showpausedimage "1" // Show the Paused image when game is paused.
cl_showpluginmessages "1" // Allow plugins to display messages to you
cl_showpos "0" // Draw current position at top of screen
cl_ShowSunVectors "0"
cl_showtextmsg "1" // Enable/disable text messages printing on the screen.
cl_show_num_particle_systems "0" // Display the number of active particle systems.
cl_show_splashes "1"
cl_sidespeed "450"
cl_smooth "1" // Smooth view/eye origin after prediction errors
cl_smoothtime "0" // Smooth clients view after prediction error over this many seconds
cl_soundemitter_flush // Flushes the sounds.txt system (client only)
cl_soundfile "0" // Jingle sound file.
cl_soundscape_flush // Flushes the client side soundscapes
cl_soundscape_printdebuginfo // print soundscapes
cl_spewscriptintro "0"
cl_spewuserinfoconvars // Re-send your myinfo variables to the server
cl_sporeclipdistance "512"
cl_starfield_diameter "128"
cl_starfield_distance "256"
cl_sun_decay_rate "0"
cl_team "0" // Default team when joining a game
cl_threaded_bone_setup "0" // Enable parallel processing of C_BaseAnimating::SetupBones()
cl_threaded_client_leaf_system "0"
cl_timeout "45" // the client will disconnect itself
cl_updaterate "30" // Number of packets per second of updates you are requesting from the server
cl_upspeed "320"
cl_view // Set the view entity index.
cl_voice_filter "0" // Filter voice by name substring
cl_vote_ui_active_after_voting "0"
cl_vote_ui_show_notification "0"
cl_winddir "0" // Weather effects wind direction angle
cl_windspeed "0" // Weather effects wind speed scalar
cl_wpn_sway_interp "0"
cl_wpn_sway_scale "1"
cl_yawspeed "210" // Client yaw speed.
cmd // Forward command to server.
cnc // Context Click
collision_shake_amp "0"
collision_shake_freq "0"
collision_shake_time "0"
collision_test // Tests collision system
colorcorrectionui // Show/hide the color correction tools UI.
combine_guard_spawn_health "1"
combine_spawn_health "1"
commentary "0" // Desired commentary mode state.
commentary_available "0" // Automatically set by the game when a commentary file is available for the current map.
commentary_cvarsnotchanging
commentary_finishnode
commentary_firstrun "0" 
```
