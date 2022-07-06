# Commands VIII

```lua
mat_viewportscale "1" // Scale down the main viewport (to reduce GPU impact on CPU profiling)
mat_visualize_dof "0"
mat_vsync "0" // Force sync to vertical retrace
mat_wateroverlaysize "128"
mat_wireframe "0"
mat_yuv "0"
maxplayers // Change the maximum number of players allowed on this server.
memory // Print memory stats.
memory_diff // show memory stats relative to snapshot
memory_list // dump memory list (linux only)
memory_mark // snapshot current allocation status
memory_status // show memory stats (linux only)
mem_compact
mem_dump // Dump memory stats to text file.
mem_dumpstats "0" // Dump current and max heap usage info to console at end of frame ( set to 2 for continuous output )
mem_dumpvballocs // Dump VB memory allocation stats.
mem_eat
mem_force_flush "0" // Force cache flush of unlocked resources on every alloc
mem_max_heapsize "256" // Maximum amount of memory to dedicate to engine hunk and datacache (in mb)
mem_max_heapsize_dedicated "64" // for dedicated server (in mb)
mem_min_heapsize "48" // Minimum amount of memory to dedicate to engine hunk and datacache (in mb)
mem_periodicdumps "0" // Write periodic memstats dumps every n seconds.
mem_test
mem_test_each_frame "0" // Run heap check at end of every frame
mem_test_every_n_seconds "0" // Run heap check at a specified interval
mem_vcollide // Dumps the memory used by vcollides
menu_achievements
menu_clearfonts // For development purposes. Clears the font list so itll be forced to re-create the font next time. (This means it leaks memory)
menu_extensions
menu_reload // Forces a total reload of the Lua base menu
menu_startgame
metropolice_charge "1"
metropolice_chase_use_follow "0"
metropolice_move_and_melee "1"
minisave // Saves game (for current level only!)
mission_list // List all available tactical missions
mission_show // Show the given mission
mm_add_item // Add a stats item
mm_add_player // Add a player
mm_max_spectators "4" // Max players allowed on the spectator team
mm_message // Send a message to all remote clients
mm_minplayers "2" // Number of players required to start an unranked game
mm_select_session // Select a session
mm_session_info // Dump session information
mm_stats
model_list // Dump model list to file
mod_forcedata "1" // Forces all model file data into cache on model load.
mod_forcetouchdata "1" // Forces all model file data into cache on model load.
mod_load_anims_async "0"
mod_load_fakestall "0" // Forces all ANI file loading to stall for specified ms
mod_load_mesh_async "0"
mod_load_showstall "0" // 2 - show stalls
mod_load_vcollide_async "0"
mod_lock_mdls_on_load "0"
mod_test_mesh_not_available "0"
mod_test_not_available "0"
mod_test_verts_not_available "0"
mod_touchalldata "1" // Touch model data during level startup
mod_trace_load "0"
monk_headshot_freq "2"
mortar_visualize "0"
motdfile "0" // The MOTD file to load.
motdfile_text "0" // The text-only MOTD file to use for clients that have disabled HTML MOTDs.
movie_fixwave // etc.
mp_allowNPCs "1"
mp_allowspectators "1" // toggles whether the server allows spectator mode or not
mp_autocrosshair "1"
mp_autoteambalance "1"
mp_bonusroundtime "15" // Time after round win until round restarts
mp_chattime "10" // amount of time players can chat after the game is over
mp_clan_readyrestart "0" // game will restart once someone from each team gives the ready signal
mp_clan_ready_signal "0" // Text that team leader from each team must speak for the match to begin
mp_decals "5000"
mp_defaultteam "0"
mp_disable_autokick // Prevents a userid from being auto-kicked
mp_disable_respawn_times "0"
mp_enableroundwaittime "1" // Enable timers to wait between rounds.
mp_fadetoblack "0" // fade a players screen to black when he dies
mp_falldamage "0"
mp_flashlight "0"
mp_footsteps "1"
mp_forceautoteam "0" // Automatically assign players to teams when joining.
mp_forcecamera "0" // Restricts spectator modes for dead players
mp_forcerespawn "1"
mp_forcerespawnplayers // Force all players to respawn.
mp_forcewin // Forces team to win
mp_fraglimit "0" // The number of kills at which the map ends
mp_friendlyfire "0" // Allows team members to injure other members of their team
mp_holiday_nogifts "0" // Set to 1 to prevent holiday gifts from spawning when players are killed.
mp_match_end_at_timelimit "0" // Allow the match to end when mp_timelimit hits instead of waiting for the end of the current round.
mp_maxrounds "0" // max number of rounds to play before server changes maps
mp_readyrestart "0" // game will restart once each player gives the ready signal
mp_ready_signal "0" // Text that each player must speak for the match to begin
mp_respawnwavetime "10" // Time between respawn waves.
mp_restartgame "0" // game will restart in the specified number of seconds
mp_restartgame_immediate "0" // game will restart immediately
mp_restartround "0" // the current round will restart in the specified number of seconds
mp_scrambleteams // Scramble the teams and restart the game
mp_scrambleteams_auto "1" // Server will automatically scramble the teams if criteria met. Only works on dedicated servers.
mp_scrambleteams_auto_windifference "2" // Number of round wins a team must lead by in order to trigger an auto scramble.
mp_showgestureslots "-1" // Show multiplayer client/server gesture slot information for the specified player index (-1 for no one).
mp_show_voice_icons "1" // Show overhead player voice icons when players are speaking.
mp_simulatemultiplecappers "1"
mp_stalemate_enable "0" // Enable/Disable stalemate mode.
mp_stalemate_meleeonly "0" // Restrict everyone to melee weapons only while in Sudden Death.
mp_stalemate_timelimit "240" // Timelimit (in seconds) of the stalemate round.
mp_switchteams // Switch teams and restart the game
mp_teamlist "0"
mp_teamoverride "1"
mp_teamplay "0"
mp_teams_unbalance_limit "1" // Teams are unbalanced when one team has this many more players than the other team. (0 disables check)
mp_timelimit "0" // game time per map in minutes
mp_time_between_capscoring "30" // Delay between scoring of owned capture points.
mp_tournament "0"
mp_tournament_allow_non_admin_restart "1" // Allow mp_tournament_restart command to be issued by players other than admin.
mp_tournament_restart // Restart Tournament Mode on the current level.
mp_usehwmmodels "0" // 0 = based upon GPU)
mp_usehwmvcds "0" // 0 = based upon GPU)
mp_waitingforplayers_cancel "0" // Set to 1 to end the WaitingForPlayers period.
mp_waitingforplayers_restart "0" // Set to 1 to start or restart the WaitingForPlayers period.
mp_waitingforplayers_time "0" // WaitingForPlayers time length in seconds
mp_weaponstay "0"
mp_winlimit "0" // Max score one team can reach before server changes maps
multvar // Multiply specified convar value.
muzzleflash_light "1"
myinfo // myinfo..
myinfo_bytes "128"
myinfo_debug "0"
m_customaccel "0" // Custom mouse acceleration: 0: custom accelaration disabled 1: mouse_acceleration = min(m_customaccel_max, pow(raw_mouse_delta,
m_customaccel_exponent "1" // Mouse move is raised to this power before being scaled by scale factor.
m_customaccel_max "0" // 0 for no limit
m_customaccel_scale "0" // Custom mouse acceleration value.
m_filter "0" // Mouse filtering (set this to 1 to average the mouse over 2 frames).
m_forward "1" // Mouse forward factor.
m_mouseaccel1 "0" // Windows mouse acceleration initial threshold (2x movement).
m_mouseaccel2 "0" // Windows mouse acceleration secondary threshold (4x movement).
m_mousespeed "1" // 2 to enable secondary threshold
m_pitch "0" // Mouse pitch factor.
m_rawinput "0" // Use Raw Input for mouse input.
m_side "0" // Mouse side factor.
m_yaw "0" // Mouse yaw factor.
name "0" // Current user name
nav_add_to_selected_set // Add current area to the selected set.
nav_add_to_selected_set_by_id // Add specified area id to the selected set.
nav_analyze // Re-analyze the current Navigation Mesh and save it to disk. 
```
