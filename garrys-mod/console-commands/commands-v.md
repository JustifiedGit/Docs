# Commands V

```lua
ent_rbox // Displays the total bounding box for the given entity(s) in green. Some entites will also display entity specific overlays. Ar
ent_remove // Removes the given entity(s) Arguments: {entity_name} / {class_name} / no argument picks what player is looking at
ent_remove_all // Removes all entities of the specified type Arguments: {entity_name} / {class_name}
ent_rotate // Rotates an entity by a specified # of degrees
ent_setname // Sets the targetname of the given entity(s) Arguments: {new entity name} {entity_name} / {class_name} / no argument picks wh
ent_show_response_criteria // an entitys current criteria set used to select responses. Arguments: {entity_name} / {class_name} /
ent_step // When ent_pause is set this will step through one waiting input / output message at a time.
ent_teleport // Teleport the specified entity to where the player is looking. Format: ent_teleport <entity name>
ent_text // Displays text debugging information about the given entity(ies) on top of the entity (See Overlay Text) Arguments: {entity_
ent_viewoffset // Displays the eye position for the given entity(ies) in red. Arguments: {entity_name} / {class_name} / no argument picks wha
envmap
escape // Escape key pressed.
exec // Execute script file.
exit // Exit the engine.
explode // Kills the player with explosive damage
explodevector // Kills a player applying an explosive force. Usage: explodevector <player> <x value> <y value> <z value>
explosion_dlight "1"
fadein // fadein {time r g b}: Fades the screen in from black or from the specified color over the given number of seconds.
fadeout // fadeout {time r g b}: Fades the screen to black or to the specified color over the given number of seconds.
fast_fogvolume "0"
filesystem_buffer_size "0" // Size of per file buffers. 0 for none
find // Find concommands with the specified string in their name/help text.
findflags // Find concommands by flags.
find_ent // Find and list all entities with classnames or targetnames that contain the specified substring. Format: find_ent <substring>
find_ent_index // Display data for entity matching specified index. Format: find_ent_index <index>
firetarget
fire_absorbrate "3"
fire_dmgbase "1"
fire_dmginterval "1"
fire_dmgscale "0"
fire_extabsorb "5"
fire_extscale "12"
fire_growthrate "1"
fire_heatscale "1"
fire_incomingheatscale "0"
fire_maxabsorb "50"
firstperson // Switch to firstperson camera.
fish_debug "0" // Show debug info for fish
fish_dormant "0" // Turns off interactive fish behavior. Fish become immobile and unresponsive.
flex_expression "0"
flex_looktime "5"
flex_maxawaytime "1"
flex_maxplayertime "7"
flex_minawaytime "0"
flex_minplayertime "5"
flex_rules "1" // Allow flex animation rules to run.
flex_smooth "1" // Applies smoothing/decay curve to flex animation controller changes.
flex_talk "0"
flush // Flush unlocked cache memory.
flush_locked // Flush unlocked and locked cache memory.
fogui // Show/hide fog control UI.
fog_color "-1"
fog_colorskybox "-1"
fog_color_b "-1"
fog_color_g "-1"
fog_color_r "-1"
fog_enable "1"
fog_enableskybox "1"
fog_enable_water_fog "1"
fog_end "1"
fog_endskybox "1"
fog_maxdensity "-1"
fog_maxdensityskybox "-1"
fog_override "0"
fog_start "1"
fog_startskybox "1"
force_centerview
fov // Change players FOV
fov_desired "75" // Sets the base field-of-view.
fps_max "300" // cannot be set while connected to a server.
free_pass_peek_debug "0"
fstat
fstat_clear
fs_monitor_read_from_pack "0" // 2:Sync only
fs_printopenfiles // Show all files currently opened by the engine.
fs_report_sync_opens "0" // 2:Not during load
fs_translate_names "1"
fs_warning_level // Set the filesystem warning level.
fs_warning_mode "0" // 2:Warn other threads
func_breakdmg_bullet "0"
func_breakdmg_club "1"
func_breakdmg_explosive "1"
func_break_max_pieces "15"
func_break_reduction_factor "0"
fun_npcscale "1"
g15_dumpplayer // Spew player data.
g15_reload // Reloads the Logitech G-15 Keyboard configs.
g15_update_msec "250" // Logitech G-15 Keyboard update interval.
gamemenucommand // Issue game menu command.
gamemode // outputs information about the gamemode
gamemode_reload // Reloads the gamemode. This wont transfer new clientside files - so youll need to restart the map for connected clients to see
gamemode_reload_cl // Reloads the gamemode on the client
gameui_activate // Shows the game UI
gameui_allowescape // Escape key allowed to hide game UI
gameui_allowescapetoshow // Escape key allowed to show game UI
gameui_hide // Hides the game UI
gameui_hide_dialog // asdf
gameui_preventescape // Escape key doesnt hide game UI
gameui_preventescapetoshow // Escape key doesnt show game UI
gameui_show_dialog // Show an arbitrary Dialog.
gameui_xbox "0"
getpos // dump position and angles to the console
give // Give item to player. Arguments: <item_name>
givecurrentammo // Give a supply of ammo for current weapon..
global_set // 2 = DEAD).
gl_clear "0"
gl_clear_randomcolor "0" // Clear the back buffer to random colors every frame. Helps spot open seams in geometry.
gm_clearfonts // For development purposes. Clears the font list so itll be forced to re-create the font next time. (This means it leaks memory)
gm_gridsize "32"
gm_showhelp
gm_showspare1
gm_showspare2
gm_showteam
gm_snapdegrees "45"
gm_snaptogrid "0"
god // Toggle. Player becomes invulnerable.
groundlist // Display ground entity list <index>
g_ai_citizen_show_enemy "0"
g_antlionguard_hemorrhage "1" // guard will emit a bleeding particle effect when wounded.
g_antlion_cascade_push "1"
g_antlion_maxgibs "16"
g_debug_angularsensor "0"
g_debug_antlion "0"
g_debug_antlionguard "0"
g_debug_antlionmaker "0"
g_debug_antlion_worker "0"
g_debug_basehelicopter "0"
g_debug_basescanner "0"
g_debug_combine_camera "0"
g_debug_constraint_sounds "0" // Enable debug printing about constraint sounds.
g_debug_cscanner "0"
g_debug_doors "0"
g_debug_dropship "0"
g_debug_dynamicresupplies "0" // Debug item_dynamic_resupply spawning. Set to 1 to see text printouts of the spawning. Set to 2 to see lines drawn to other item
g_debug_gunship "0"
g_debug_headcrab "0"
g_debug_hunter_charge "0"
g_debug_npc_vehicle_roles "0"
g_debug_physcannon "0"
g_debug_ragdoll_removal "0"
g_debug_ragdoll_visualize "0"
g_debug_trackpather "0"
g_debug_transitions "0" // Set to 1 and restart the map to be warned if the map has no trigger_transition volumes. Set to 2 to see a dump of all entities
g_debug_turret "0"
g_debug_turret_ceiling "0"
g_debug_vehiclebase "0"
g_debug_vehicledriver "0"
g_debug_vehicleexit "0"
g_debug_vehiclesound "0"
g_debug_vortigaunt_aim "0"
g_helicopter_bomb_danger_radius "120"
g_helicopter_bullrush_bomb_enemy_distance "0"
g_helicopter_bullrush_bomb_speed "850" // The maximum distance the player can be from the chopper before it stops firing
g_helicopter_bullrush_bomb_time "10"
g_helicopter_bullrush_distance "5000"
g_helicopter_bullrush_mega_bomb_health "0" // Fraction of the health of the chopper before it mega-bombs
g_helicopter_bullrush_shoot_height "650" // The maximum distance the player can be from the chopper before it stops firing
g_helicopter_chargetime "2" // How much time we have to wait (on average) between the time we start hearing the charging sound + the chopper fires
g_helicopter_idletime "3" // How much time we have to wait (on average) after we fire before we can charge up again
g_helicopter_maxfiringdist "2500" // The maximum distance the player can be from the chopper before it stops firing
g_jeepexitspeed "100"
g_Language "0"
g_ragdoll_fadespeed "600"
g_ragdoll_important_maxcount "2"
g_ragdoll_lvfadespeed "100"
g_ragdoll_maxcount "32"
g_test_new_antlion_jump "1"
hap_airboat_gun_mag "3"
hap_damagescale_game "1"
hap_HasDevice "0" // falcon is connected
hap_jeep_cannon_mag "10"
hap_melee_scale "0"
hap_noclip_avatar_scale "0"
hap_turret_mag "5"
hap_ui_vehicles "1"
heartbeat // Force heartbeat of master servers
help // Find help about a convar/concommand.
hideconsole // Hide the console.
hidehud "0" 
```
