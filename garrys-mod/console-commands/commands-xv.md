# Commands XV

```lua
sk_pathfollower_grenade_radius "0"
sk_player_arm "1"
sk_player_chest "1"
sk_player_head "2"
sk_player_leg "1"
sk_player_stomach "1"
sk_plr_dmg_357 "0"
sk_plr_dmg_airboat "0"
sk_plr_dmg_alyxgun "0"
sk_plr_dmg_ar2 "0"
sk_plr_dmg_buckshot "0"
sk_plr_dmg_crossbow "0"
sk_plr_dmg_crowbar "0"
sk_plr_dmg_fraggrenade "0"
sk_plr_dmg_grenade "0"
sk_plr_dmg_pistol "0"
sk_plr_dmg_rpg_round "0"
sk_plr_dmg_satchel "0"
sk_plr_dmg_smg1 "0"
sk_plr_dmg_smg1_grenade "0"
sk_plr_dmg_sniper_round "0"
sk_plr_dmg_stunstick "0"
sk_plr_dmg_tripmine "0"
sk_plr_grenade_drop_time "30"
sk_plr_health_drop_time "30"
sk_plr_num_shotgun_pellets "7"
sk_rollermine_shock "0"
sk_rollermine_stun_delay "1"
sk_rollermine_vehicle_intercept "1"
sk_satchel_radius "0"
sk_scanner_dmg_dive "0"
sk_scanner_health "0"
sk_smg1_grenade_radius "0"
sk_stalker_health "0"
sk_stalker_melee_dmg "0"
sk_striderbuster_magnet_multiplier "2"
sk_strider_health "350"
sk_strider_num_missiles1 "5"
sk_strider_num_missiles2 "7"
sk_strider_num_missiles3 "7"
sk_suitcharger "0"
sk_suitcharger_citadel "0"
sk_suitcharger_citadel_maxarmor "0"
sk_tripmine_radius "0"
sk_vortigaunt_armor_charge "30"
sk_vortigaunt_armor_charge_per_token "5"
sk_vortigaunt_dmg_claw "0"
sk_vortigaunt_dmg_rake "0"
sk_vortigaunt_dmg_zap "0"
sk_vortigaunt_health "0"
sk_vortigaunt_vital_antlion_worker_dmg "0" // Vital-ally vortigaunts scale damage taken from antlion workers by this amount.
sk_vortigaunt_zap_range "100" // Range of vortigaunts ranged attack (feet)
sk_weapon_ar2_alt_fire_duration "4"
sk_weapon_ar2_alt_fire_mass "150"
sk_weapon_ar2_alt_fire_radius "10"
sk_zombie_dmg_both_slash "0"
sk_zombie_dmg_one_slash "0"
sk_zombie_health "0"
sk_zombie_poison_dmg_spit "0"
sk_zombie_poison_health "0"
sk_zombie_soldier_health "0"
slot0
slot1
slot10
slot2
slot3
slot4
slot5
slot6
slot7
slot8
slot9
smoke_trail "1"
smoothstairs "1" // Smooth player eye z coordinate when traversing stairs.
snapto
sndplaydelay // Usage: sndplaydelay delay_in_sec (negative to skip ahead) soundname
snd_async_flush // Flush all unlocked async audio data
snd_async_fullyasync "0" // All playback is fully async (sound doesnt play until data arrives).
snd_async_minsize "262144"
snd_async_showmem // Show async memory stats
snd_async_spew_blocking "0" // Spew message to console any time async sound loading blocks on file i/o.
snd_async_stream_spew "0" // 2=buffers
snd_cull_duplicates "0" // aggressively cull duplicate sounds during mixing. The number specifies the number of duplicates allowed to be playe
snd_defer_trace "1"
snd_delay_sound_shift "0"
snd_disable_mixer_duck "0"
snd_duckerattacktime "0"
snd_duckerreleasetime "2"
snd_duckerthreshold "0"
snd_ducktovolume "0"
snd_dumpclientsounds // Dump sounds to VXConsole
snd_foliage_db_loss "4"
snd_gain "1"
snd_gain_max "1"
snd_gain_min "0"
snd_legacy_surround "0"
snd_lockpartial "1"
snd_mixahead "0"
snd_mix_async "0"
snd_musicvolume "1" // Music volume
snd_mute_losefocus "1"
snd_noextraupdate "0"
snd_obscured_gain_dB "0"
snd_pitchquality "1"
snd_profile "0"
snd_rebuildaudiocache // level caches) from reslists
snd_refdb "60"
snd_refdist "36"
snd_restart // Restart sound system.
snd_show "0" // Show sounds info
snd_showclassname "0"
snd_showmixer "0"
snd_showstart "0"
snd_ShowThreadFrameTime "0"
snd_soundmixer "0"
snd_spatialize_roundrobin "0" // spatialize only a fraction of sound channels each frame. 1/2^x of channels will be spatialized
snd_surround_speakers "2"
snd_visualize "0" // Show sounds location in world
snd_vox_captiontrace "0" // Shows sentence name for sentences which are set not to show captions.
snd_vox_globaltimeout "300"
snd_vox_sectimetout "300"
snd_vox_seqtimetout "300"
snd_writemanifest // outputs the precache manifest for the current level
sniperspeak "0"
sniperviewdist "35"
sniper_xbox_delay "1"
soundfade // Fade client volume.
soundinfo // Describe the current sound device.
soundlist // List all known sounds.
soundpatch_captionlength "2" // How long looping soundpatch captions should display for.
soundscape_debug "0" // red lines show soundscapes that ar
soundscape_dumpclient // Dumps the clients soundscape data.
soundscape_fadetime "3" // Time to crossfade sound effects between soundscapes
soundscape_flush // Flushes the server & client side soundscapes
spawnicon_disablepreload "0" // Set to 1 to disable preloading
speak // Play a constructed sentence.
spec_autodirector "1" // Auto-director chooses best view modes while spectating
spec_freeze_distance_max "200" // Maximum random distance from the target to stop when framing them in observer freeze cam.
spec_freeze_distance_min "96" // Minimum random distance from the target to stop when framing them in observer freeze cam.
spec_freeze_time "4" // Time spend frozen in observer freeze cam.
spec_freeze_traveltime "0" // Time taken to zoom in to frame a target in observer freeze cam.
spec_pos // dump position and angles to the console
spec_scoreboard "0"
spec_track "0" // Tracks an entity in spec mode
spike // generates a fake spike
startdemos // Play demos in demo sequence.
startmovie // Start recording movie frames.
startupmenu // and were not in developer
star_memory // Dump memory stats
stats // Prints server performance variables
status // Display map and connection status.
step_spline "0"
stop // Finish recording demo.
stopdemo // Stop playing back a demo.
stopsound
stopsounds // Stops all sounds..
stopsoundscape // Stops all soundscape processing and fades current looping sounds
striderbuster_allow_all_damage "0" // If set to 1 the bomb will detonate on any damage taken. Otherwise only the player may trigger it.
striderbuster_autoaim_radius "64"
striderbuster_debugseek "0"
striderbuster_die_detach "1"
striderbuster_dive_force "-200"
striderbuster_falloff_power "4" // Order of the distance falloff. 1 = linear 2 = quadratic
striderbuster_health "14"
striderbuster_leg_stick_dist "80" // the max distance from the head at which it sticks anyway.
striderbuster_magnetic_force_hunter "1750000" // Intensity of magnades attraction to a hunter.
striderbuster_magnetic_force_strider "750000" // Intensity of magnades attraction to a strider.
striderbuster_shot_velocity "2500" // Speed at which launch the bomb from the physcannon
striderbuster_use_particle_flare "1"
strider_always_use_procedural_height "0"
strider_ar2_altfire_dmg "25"
strider_distributed_fire "1"
strider_eyepositions "0"
strider_free_knowledge "0"
strider_free_pass_after_escorts_dead "2"
strider_free_pass_cover_dist "120"
strider_free_pass_duration "2"
strider_free_pass_move_tolerance "320"
strider_free_pass_refill_rate "0"
strider_free_pass_start_time "3"
strider_free_pass_tolerance_after_escorts_dead "600"
strider_idle_test "0"
strider_immolate "0"
strider_missile_suppress_dist "240"
strider_missile_suppress_time "3"
strider_pct_height_no_crouch_move "90"
strider_peek_eye_dist "1"
strider_peek_eye_dist_z "4"
strider_peek_time "0"
strider_peek_time_after_damage "4"
strider_show_cannonlos "0"
strider_show_focus "0"
strider_show_weapon_los_condition "0"
strider_show_weapon_los_z "0"
strider_test_height "0"
stringtabletotals // Size of all string tables
stringtabletotals // Size of all string tables
studio_queue_mode "1"
stuffcmds // Parses and stuffs command line + commands to command buffer.
suitvolume "0"
surfaceprop // Reports the surface properties at the cursor
sv_accelerate "10"
sv_airaccelerate "10"
sv_allowdownload "1" // Allow clients to download files
sv_allowupload "1" // Allow clients to upload customizations files
sv_allow_color_correction "1" // Allow or disallow clients to use color correction on this server.
sv_allow_voice_from_file "0" // Allow or disallow clients from using voice_inputfromfile on this server.
sv_allow_votes "1" // Allow voting?
sv_alltalk "0" // no team restrictions
```
