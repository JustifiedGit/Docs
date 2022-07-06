# Commands XVI

```lua
sv_alternateticks "0" // server only simulates entities on even numbered ticks.
sv_autojump "0"
sv_autoladderdismount "1" // Automatically dismount from ladders when you reach the end (dont have to +USE).
sv_autosave "0" // Set to 1 to autosave game on level transition. Does not affect autosave triggers.
sv_benchmark_autovprofrecord "0" // it will record a vprof file over the duration of the benchmark with filename benchmark.
sv_benchmark_numticks "3300" // then it only runs the benchmark for this # of ticks.
sv_bonus_challenge "0" // Set to values other than 0 to select a bonus map challenge type.
sv_bonus_map_challenge_update // Updates a bonus map challenge score.
sv_bonus_map_complete // Completes a bonus map.
sv_bonus_map_unlock // Locks a bonus map.
sv_cacheencodedents "1" // does an optimization to prevent extra SendTable_Encode calls.
sv_cheats "1" // Allow cheats on server
sv_clearhinthistory // Clear memory of server side hints displayed to the player.
sv_client_cmdrate_difference "20" // cl_cmdrate is moved to within sv_client_cmdrate_difference units of cl_updaterate before it is clamped between sv_mincmdrate an
sv_client_max_interp_ratio "5" // This can be used to limit the value of cl_interp_ratio for connected clients (only while they are connected). If sv_client_min_
sv_client_min_interp_ratio "1" // This can be used to limit the value of cl_interp_ratio for connected clients (only while they are connected). -1
sv_client_predict "1" // This can be used to force the value of cl_predict for connected clients (only while they are connected). -1 = let clients se
sv_clockcorrection_msecs "60" // The server tries to keep each players m_nTickBase withing this many msecs of the server absolute tickcount
sv_consistency "1" // Whether the server enforces file consistency for critical files
sv_contact "0" // Contact email for server sysop
sv_debugmanualmode "0" // Make sure entities correctly report whether or not their network data has changed.
sv_debugtempentities "0" // Show temp entity bandwidth usage.
sv_debug_player_use "0" // Green box=radius success
sv_defaultdeployspeed "4"
sv_defaultgamemode "0" // The default gamemode
sv_deltaprint "0" // Print accumulated CalcDelta profiling data (only if sv_deltatime is on)
sv_deltatime "0" // Enable profiling of CalcDelta calls
sv_disable_querycache "0" // debug - disable trace query cache
sv_downloadurl "0" // Location from which clients can download missing files
sv_dumpstringtables "0"
sv_enableoldqueries "0" // Enable support for old style (HL1) server queries
sv_filterban "1" // Set packet filtering by IP mode
sv_footsteps "1" // Play footstep sound for players
sv_forcepreload "0" // Force server side preloading.
sv_friction "8" // World friction.
sv_gamemode "0" // The current gamemode name
sv_gamemodeoverride "0" // Gamemode to override.
sv_gravity "600" // World gravity.
sv_hudhint_sound "1"
sv_infinite_aux_power "0"
sv_ladderautomountdot "0" // this is the tolerance for looking now directly along the ladder axis.
sv_ladder_useonly "0" // ladders can only be mounted by pressing +USE
sv_lan "0" // no non-class C addresses )
sv_loadingurl "0" // URL to show to clients while joining the server
sv_logbans "0" // Log server bans in the server logs.
sv_logblocks "0" // If true when log when a query is blocked (can cause very large log files)
sv_logdownloadlist "1"
sv_logecho "1" // Echo log information to the console.
sv_logfile "1" // Log server information in the log file.
sv_logflush "0" // Flush the log file to disk on each write (slow).
sv_logsdir "0" // Folder in the game directory where server logs will be stored.
sv_logsecret "0" // not usual 0x52)
sv_log_onefile "0" // Log server information to only one file.
sv_lowedict_action "0" // 4 - go to the next ma
sv_lowedict_threshold "8" // take the action specified by sv_lowedict_action.
sv_massreport "0"
sv_master_share_game_socket "1" // then it will create a socket on -steamport + 1 to comm
sv_maxcmdrate "66" // this sets the maximum value for cl_cmdrate.
sv_maxplayers "8" // This is a hack around the fact that maxplayers isnt a real convar.
sv_maxrate "0" // 0 == unlimited
sv_maxreplay "0" // Maximum replay time in seconds
sv_maxroutable "1260" // Server upper bound on net_maxroutable that a client can use.
sv_maxupdaterate "66" // Maximum updates per second that the server will allow
sv_maxvelocity "3500" // Maximum speed any ballistically moving object is allowed to attain per axis.
sv_max_connects_sec "2" // Maximum connections per second to respond to from a single IP address.
sv_max_connects_sec_global "0" // Maximum connections per second to respond to from anywhere.
sv_max_connects_window "4" // Window over which to average connections per second averages.
sv_max_queries_sec "3" // Maximum queries per second to respond to from a single IP address.
sv_max_queries_sec_global "3000" // Maximum queries per second to respond to from anywhere.
sv_max_queries_window "30" // Window over which to average queries per second averages.
sv_max_usercmd_future_ticks "12" // Prevents clients from running usercmds too far in the future. Prevents speed hacks.
sv_memlimit "0" // the server wi
sv_mincmdrate "10" // This sets the minimum value for cl_cmdrate. 0 == unlimited.
sv_minrate "3500" // 0 == unlimited
sv_minupdaterate "10" // Minimum updates per second that the server will allow
sv_namechange_cooldown_seconds "20" // wait N seconds allowing another name change
sv_netspike_on_reliable_snapshot_overflow "0" // the server will dump a netspike trace if a client is dropped due to reliable snapshot overflow
sv_noclipaccelerate "5"
sv_noclipduringpause "0" // etc.).
sv_noclipspeed "5"
sv_npc_talker_maxdist "1024" // NPCs over this distance from the player wont attempt to speak.
sv_parallel_packentities "1"
sv_parallel_sendsnapshot "1"
sv_passengersalwaysvisible "1"
sv_password "0" // Server password for entry into multiplayer games
sv_pausable "0" // Is the server pausable.
sv_playerforcedupdate "10"
sv_playerperfhistorycount "60" // Number of samples to maintain in player perf history
sv_playerpickupallowed "1" // Allow the player to pick things up using the USE key
sv_precacheinfo // Show precache info.
sv_pure // Show user data.
sv_pure_kick_clients "1" // it will issue a warning to the client.
sv_pure_trace "0" // the server will print a message whenever a client is verifying a CRC for a file.
sv_pvsskipanimation "1" // Skips SetupBones when npcs are outside the PVS
sv_querycache_stats // Display status of the query cache (client only)
sv_rcon_banpenalty "0" // Number of minutes to ban users who fail rcon authentication
sv_rcon_log "1" // Enable/disable rcon logging.
sv_rcon_maxfailures "10" // Max number of times a user can fail rcon authentication before being banned
sv_rcon_maxpacketbans "1" // Ban IPs for sending RCON packets exceeding the value specified in sv_rcon_maxpacketsize
sv_rcon_maxpacketsize "1024" // The maximum number of bytes to allow in a command packet
sv_rcon_minfailures "5" // Number of times a user can fail rcon authentication in sv_rcon_minfailuretime before being banned
sv_rcon_minfailuretime "30" // Number of seconds to track failed rcon authentications
sv_region "-1" // The region of the world to report this server in.
sv_restrict_aspect_ratio_fov "1" // This can be used to limit the effective FOV of users using wide-screen resolutions with aspect ratios wider than 1.85:1 (slight
sv_robust_explosions "1"
sv_rollangle "0" // Max view roll angle
sv_rollspeed "200"
sv_scriptenforcer "0" // Enforce script consistency
sv_scriptenforcer_initialkick "0" // Kick for initial SE check failure
sv_showladders "0" // Show bbox and dismount points for all ladders (must be set before level load.)
sv_showlagcompensation "0" // Show lag compensated hitboxes whenever a player is lag compensated.
sv_show_crosshair_target "0"
sv_shutdown // Sets the server to shutdown next time its empty 
```
