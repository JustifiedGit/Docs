# Commands XI

```lua
npc_citizen_auto_player_squad "1"
npc_citizen_auto_player_squad_allow_use "0"
npc_citizen_dont_precache_all "1"
npc_citizen_explosive_resist "0"
npc_citizen_insignia "0"
npc_citizen_medic_emit_sound "1"
npc_citizen_squad_marker "0"
npc_combat // Displays text debugging information about the squad and enemy of the selected NPC (See Overlay Text) Arguments: {npc_name}
npc_conditions // Displays all the current AI conditions that an NPC has in the overlay text. Arguments: {npc_name} / {npc class_name} / no a
npc_create // Creates an NPC of the given type where the player is looking (if the given NPC can actually stand at that location). Note that
npc_create_aimed // Creates an NPC aimed away from the player of the given type where the player is looking (if the given NPC can actually stand at
npc_create_equipment "0"
npc_destroy // Removes the given NPC(s) from the universe Arguments: {npc_name} / {npc_class_name} / no argument picks what player is looki
npc_destroy_unselected // Removes all NPCs from the universe that arent currently selected
npc_enemies // Shows memory of NPC. Draws an X on top of each memory. Eluded entities drawn in blue (dont know where it went) Unreachable
npc_focus // Displays red line to NPCs enemy (if has one) and blue line to NPCs target entity (if has one) Arguments: {npc_name} / {np
npc_freeze // uses the NPC under the crosshair. Arguments
npc_freeze_unselected // Freeze all NPCs not selected
npc_go // Selected NPC(s) will go to the location that the player is looking (shown with a purple box) Arguments: -none-
npc_go_do_run "1" // Set whether should run on NPC go
npc_go_random // Sends all selected NPC(s) to a random node. Arguments: -none-
npc_heal // Heals the target back to full health
npc_height_adjust "1" // Enable test mode for ik height adjustment
npc_kill // Kills the given NPC(s) Arguments: {npc_name} / {npc_class_name} / no argument picks what player is looking at
npc_nearest // Draws a while box around the NPC(s) nearest node Arguments: {entity_name} / {class_name} / no argument picks what player i
npc_relationships // Displays the relationships between this NPC and all others. Arguments: {entity_name} / {class_name} / no argument picks wha
npc_reset // Reloads schedules for all NPCs from their script files Arguments: -none-
npc_route // Displays the current route of the given NPC as a line on the screen. Waypoints along the route are drawn as small cyan rectang
npc_select // Select or deselects the given NPC(s) for later manipulation. Selected NPCs are shown surrounded by a red translucent box Arg
npc_sentences "0"
npc_squads // Obsolete. Replaced by npc_combat
npc_steering // Displays the steering obstructions of the NPC (used to perform local avoidance) Arguments: {entity_name} / {class_name} / n
npc_steering_all // Displays the steering obstructions of all NPCs (used to perform local avoidance)
npc_strider_height_adj "0"
npc_strider_shake_ropes_magnitude "150"
npc_strider_shake_ropes_radius "1200"
npc_tasks // Displays detailed text debugging information about the all the tasks of the selected NPC current schedule (See Overlay Text) A
npc_task_text // Outputs text debugging information to the console about the all the tasks + break conditions of the selected NPC current schedu
npc_teleport // Selected NPC will teleport to the location that the player is looking (shown with a purple box) Arguments: -none-
npc_thinknow // Trigger NPC to think
npc_viewcone // Displays the viewcone of the NPC (where they are currently looking and what the extents of there vision is) Arguments: {ent
npc_vphysics "0"
old_radiusdamage "0"
option_duck_method "1"
option_duck_method_default "1"
opt_EnumerateLeavesFastAlgorithm "1" // Use the new SIMD version of CEngineBSPTree::EnumerateLeavesInBox.
overview_alpha "1" // Overview map translucency.
overview_health "1" // Show players health in map overview.
overview_locked "1" // doesnt follow view angle.
overview_mode // large: <0|1|2>
overview_names "1" // Show players names in map overview.
overview_tracks "1" // Show players tracks in map overview.
overview_zoom // Sets overview map zoom: <zoom> [<time>] [rel]
particle_simulateoverflow "0" // Used for stress-testing particle systems. Randomly denies creation of particles.
particle_sim_alt_cores "2"
particle_test_attach_attachment "0" // Attachment index for attachment mode
particle_test_attach_mode "0" // follow_origin
particle_test_file "0" // Name of the particle system to dynamically spawn
particle_test_start // particle_test_attach_mode and particl
particle_test_stop // Stops all particle systems on the selected entities. Arguments: {entity_name} / {class_name} / no argument picks what playe
password "0" // Current server access password
path // Show the engine filesystem path.
pause // Toggle the server pause state.
perfui // Show/hide the level performance tools UI.
perfvisualbenchmark
perfvisualbenchmark_abort
phonemedelay "0" // Phoneme delay to account for sound system latency.
phonemefilter "0" // Time duration of box filter to pass over phonemes.
phonemesnap "2" // regardless of duration.
physcannon_ball_cone "0"
physcannon_chargetime "2"
physcannon_cone "0"
physcannon_maxforce "1500"
physcannon_maxmass "250"
physcannon_mega_enabled "0"
physcannon_minforce "700"
physcannon_pullforce "4000"
physcannon_tracelength "250"
physgun_DampingFactor "0"
physgun_drawbeams "1"
physgun_limited "0"
physgun_maxAngular "5000"
physgun_maxAngularDamping "10000"
physgun_maxSpeed "5000"
physgun_maxSpeedDamping "10000"
physgun_rotation_sensitivity "0" // The sensitivity of rotation.
physgun_teleportDistance "0"
physgun_timeToArrive "0"
physgun_timeToArriveRagdoll "0"
physicsshadowupdate_render "0"
physics_budget // Times the cost of each active object
physics_constraints // Highlights constraint system graph for an entity
physics_debug_entity // Dumps debug info for an entity
physics_highlight_active // Turns on the absbox for all active physics objects
physics_report_active // Lists all active physics objects
physics_select // Dumps debug info for an entity
phys_impactforcescale "1"
phys_penetration_error_time "10" // Controls the duration of vphysics penetration error boxes.
phys_pushscale "1"
phys_speeds "0"
phys_spinspeed "200"
phys_stressbodyweights "5"
phys_swap // Automatically swaps the current weapon for the physcannon and back again.
phys_timescale "1" // Scale time for physics
phys_upimpactforcescale "0"
picker // pivot and debugging text is displayed for whatever entity the play
ping // Display ping to server.
pipeline_static_props "1"
pistol_use_new_accuracy "1"
pixelvis_debug // Dump debug info
play // Play a sound.
playdemo // Play a recorded demo file (.dem ).
player_debug_print_damage "0" // print amount and type of all damage received by player to console.
player_limit_jump_speed "1"
player_old_armor "0"
player_showpredictedposition "0"
player_showpredictedposition_timestep "1"
player_squad_autosummon_debug "0"
player_squad_autosummon_move_tolerance "20"
player_squad_autosummon_player_tolerance "10"
player_squad_autosummon_time "5"
player_squad_autosummon_time_after_combat "8"
player_squad_double_tap_time "0"
player_squad_transient_commands "1"
player_throwforce "1000"
playflush // reloading from disk in case of changes.
playgamesound // Play a sound from the game sounds txt file
playsoundscape // Forces a soundscape to play
playvideo // Plays a video: <filename> [width height]
playvideo_exitcommand // Plays a video and fires and exit command when it is stopped or finishes: <filename> <exit command>
playvol // Play a sound at a specified volume.
plugin_pause // plugin_pause <index> : pauses a loaded plugin
plugin_pause_all // pauses all loaded plugins
plugin_print // Prints details about loaded plugins
plugin_unload // plugin_unload <index> : unloads a plugin
plugin_unpause // plugin_unpause <index> : unpauses a disabled plugin
plugin_unpause_all // unpauses all disabled plugins
```
