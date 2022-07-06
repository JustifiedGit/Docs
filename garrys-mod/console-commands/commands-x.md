# Commands X

```lua
nav_show_compass "0"
nav_show_continguous "0" // Highlight non-contiguous connections
nav_show_danger "0" // Show current danger levels.
nav_show_dumped_positions // z) coordinate positions of the given dump file.
nav_show_func_nav_avoid "0" // Show areas of designer-placed bot avoidance due to func_nav_avoid entities
nav_show_func_nav_prefer "0" // Show areas of designer-placed bot preference due to func_nav_prefer entities
nav_show_light_intensity "0"
nav_show_nodes "0"
nav_show_node_grid "0"
nav_show_node_id "0"
nav_show_player_counts "0" // Show current player counts in each area.
nav_show_potentially_visible "0" // Show areas that are potentially visible from the current nav area
nav_simplify_selected // Chops all selected areas into their component 1x1 areas and re-merges them together into larger areas
nav_slope_limit "0" // The ground unit normals Z component must be greater than this for nav areas to be generated.
nav_slope_tolerance "0" // The ground unit normals Z component must be this close to the nav areas Z component to be generated.
nav_snap_to_grid "0" // Snap to the nav generation grid when creating new nav areas
nav_solid_props "0" // Make props solid to nav generation/editing
nav_splice // connected area between them.
nav_split // align the split line using your cursor and invoke the split command.
nav_split_place_on_ground "0" // nav areas will be placed flush with the ground when split.
nav_stand // Toggles the stand while hiding flag used by the AI system.
nav_stop // Toggles the must stop when entering this area flag used by the AI system.
nav_store_selected_set // Stores the current selected set for later retrieval.
nav_strip // and Encounter Spots from the current Area.
nav_subdivide // Subdivides all selected areas.
nav_test_node "0"
nav_test_node_crouch "0"
nav_test_node_crouch_dir "4"
nav_test_stairs // Test the selected set for being on stairs
nav_toggle_deselecting // Start or stop continuously removing from the selected set.
nav_toggle_in_selected_set // Remove current area from the selected set.
nav_toggle_place_mode // Toggle the editor into and out of Place mode. Place mode allows labelling of Area with Place names.
nav_toggle_place_painting // pointing at an Area will paint it with the current Place.
nav_toggle_selected_set // Toggles all areas into/out of the selected set.
nav_toggle_selecting // Start or stop continuously adding to the selected set.
nav_transient // Toggles the area is transient and may become blocked flag used by the AI system.
nav_unmark // Clears the marked Area or Ladder.
nav_update_blocked // Updates the blocked/unblocked status for every nav area.
nav_update_lighting // Recomputes lighting values
nav_update_visibility_on_edit "0" // If nonzero editing the mesh will incrementally recompue visibility
nav_use_place // the current Place is set.
nav_walk // Toggles the traverse this area by walking flag used by the AI system.
nav_warp_to_mark // Warps the player to the marked area.
nav_world_center // Centers the nav mesh in the world
nb_allow_avoiding "1"
nb_allow_climbing "1"
nb_allow_gap_jumping "1"
nb_blind "0" // Disable vision
nb_command // Sends a command string to all bots
nb_debug // ERRORS.
nb_debug_climbing "0"
nb_debug_filter // Add items to the NextBot debug filter. Items can be entindexes or part of the indentifier of one or more bots.
nb_debug_history "1" // each bot keeps a history of debug output in memory
nb_debug_known_entities "0" // Show the known entities for the bot that is the current spectator target
nb_delete_all // Delete all non-player NextBot entities.
nb_force_look_at // Force selected bot to look at the local players position
nb_goal_look_ahead_range "50"
nb_head_aim_resettle_angle "100" // the bot pauses to recenter its virtual mouse on its virtual mousepad
nb_head_aim_resettle_time "0" // How long the bot pauses to recenter its virtual mouse on its virtual mousepad
nb_head_aim_settle_duration "0"
nb_head_aim_steady_max_rate "100"
nb_ladder_align_range "50"
nb_last_area_update_tolerance "4" // Distance a character needs to travel in order to invalidate cached area
nb_move_to_cursor // Tell all NextBots to move to the cursor position
nb_path_draw_inc "100"
nb_path_draw_segment_count "100"
nb_path_segment_influence_radius "100"
nb_player_crouch "0" // Force bots to crouch
nb_player_move "1" // Prevents bots from moving
nb_player_move_direct "0"
nb_player_stop "0" // Stop all NextBotPlayers from updating
nb_player_walk "0" // Force bots to walk
nb_saccade_speed "1000"
nb_saccade_time "0"
nb_select // Select the bot you are aiming at for further debug operations.
nb_shadow_dist "400"
nb_speed_look_ahead_range "150"
nb_stop "0" // Stop all NextBots
nb_update_debug "0"
nb_update_framelimit "15"
nb_update_frequency "0"
nb_update_maxslide "2"
nb_warp_selected_here // Teleport the selected bot to your cursor position
net_blockmsg "0" // Discards incoming message: <0|1|name>
net_channels // Shows net channel info
net_chokeloop "0" // Apply bandwidth choke to loopback packets
net_compresspackets "1" // Use lz compression on game packets.
net_compresspackets_minsize "128" // Dont bother compressing packets below this size.
net_compressvoice "0" // Attempt to compress out of band voice payloads (360 only).
net_drawslider "0" // Draw completion slider during signon
net_droppackets "0" // Drops next n packets on client
net_fakejitter "0" // Jitter fakelag packet time
net_fakelag "0" // Lag all incoming network data (including loopback) by this many milliseconds.
net_fakeloss "0" // Simulate packet loss as a percentage (negative means drop 1/n packets)
net_graph "0" // = 3 draws payload legend.
net_graphheight "64" // Height of netgraph panel
net_graphmsecs "400" // The latency graph represents this many milliseconds.
net_graphpos "1"
net_graphproportionalfont "1" // Determines whether netgraph font is proportional or not
net_graphshowinterp "1" // Draw the interpolation graph.
net_graphshowlatency "1" // Draw the ping/packet loss graph.
net_graphsolid "1"
net_graphtext "1" // Draw text fields
net_maxcleartime "4" // Max # of seconds we can wait for next packets to be sent based on rate setting (0 == no limit).
net_maxfilesize "16" // Maximum allowed file size for uploading in MB
net_maxfragments "1260" // Max fragment bytes per packet
net_maxpacketdrop "5000" // Ignore any packets with the sequence number more than this ahead (0 == no limit)
net_maxroutable "1260" // Requested max packet size before packets are split.
net_queued_packet_thread "1" // Use a high priority thread to send queued packets out instead of sending them each frame.
net_queue_trace "0"
net_scale "5"
net_showdrop "0" // Show dropped packets in console
net_showevents "0" // 2=all).
net_showfragments "0" // Show netchannel fragments
net_showmsg "0" // Show incoming message: <0|1|name>
net_showpeaks "0" // Show messages for large packets only: <size>
net_showsplits "0" // Show info about packet splits
net_showtcp "0" // Dump TCP stream summary to console
net_showudp "0" // Dump UDP packets summary to console
net_showudp_wire "0" // Show incoming packet information
net_splitpacket_maxrate "15000" // Max bytes per second when queueing splitpacket chunks
net_splitrate "1" // Number of fragments for a splitpacket that can be sent per frame
net_start // Inits multiplayer network sockets
net_status // Shows current network status
net_udp_rcvbuf "131072" // Default UDP receive buffer size
net_usesocketsforloopback "0" // Use network sockets layer even for listen server local players packets (multiplayer only).
next "0" // Set to 1 to advance to next frame ( when singlestep == 1 )
nextdemo // Play next demo in sequence.
nextlevel "0" // will change to this map during the next changelevel
noclip
notarget // Toggle. Player becomes hidden to NPCs.
npc_ally_deathmessage "1"
npc_ammo_deplete // Subtracts half of the targets ammo
npc_barnacle_swallow "0" // Use prototype swallow code.
npc_bipass // s 
```
