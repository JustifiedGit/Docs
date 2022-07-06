# Commands VI

```lua
hidepanel // Hides a viewport panel <name>
hl1_debug_sentence_volume "0"
hl1_fixup_sentence_sndlevel "1"
hl2_darkness_flashlight_factor "1"
hl2_episodic "0"
hostip "0" // Host game server ip
hostname "0" // Hostname for server.
hostport "27015" // Host game server port
host_flush_threshold "20" // Memory threshold below which the host should flush caches between server instances
host_framerate "0" // Set to lock per-frame time elapse.
host_limitlocal "0" // Apply cl_cmdrate and cl_updaterate to loopback connection
host_map "0" // Current map name.
host_profile "0"
host_runofftime // Run off some time without rendering/updating sounds
host_showcachemiss "0" // Print a debug message when the client or server cache is missed.
host_ShowIPCCallCount "0" // the # of IPC calls is shown every frame.
host_sleep "0" // Force the host to sleep a certain number of milliseconds each frame.
host_speeds "0" // Show general system running times.
host_thread_mode "0" // 2 == force)
host_timer_report // Spew CPU timer jitter for the last 128 frames in microseconds (dedicated only)
host_timer_spin_ms "0" // Use CPU busy-loop for improved timer precision (dedicated only)
host_timescale "1" // Prescale the clock by this amount.
host_writeconfig // Store current settings to config.cfg (or specified .cfg file).
hud_airboathint_numentries "10"
hud_autoaim_method "1"
hud_autoaim_scale_icon "0"
hud_autoreloadscript "0" // Automatically reloads the animation script each time one is ran
hud_centerid "1"
hud_deathnotice_time "6"
hud_drawhistory_time "5"
hud_draw_active_reticle "0"
hud_draw_fixed_reticle "0"
hud_fastswitch "0"
hud_freezecamhide "0" // Hide the HUD during freeze-cam
hud_jeephint_numentries "10"
hud_magnetism "0"
hud_quickinfo "1"
hud_reloadscheme // Reloads hud layout and animation scripts.
hud_reticle_alpha_speed "700"
hud_reticle_maxalpha "255"
hud_reticle_minalpha "125"
hud_reticle_scale "1"
hud_saytext_time "12"
hud_showtargetid "1"
hud_takesshots "0" // Auto-save a scoreboard screenshot at the end of a map.
hunter_allow_dissolve "1"
hunter_allow_nav_jump "0"
hunter_charge "1"
hunter_charge_min_delay "10"
hunter_charge_pct "25"
hunter_charge_test "0"
hunter_cheap_explosions "1"
hunter_clamp_shots "1"
hunter_disable_patrol "0"
hunter_dodge_debug "0"
hunter_dodge_warning "1"
hunter_dodge_warning_cone "0"
hunter_dodge_warning_width "180"
hunter_first_flechette_delay "0"
hunter_flechette_delay "0"
hunter_flechette_explode_delay "2"
hunter_flechette_max_concurrent_volleys "2"
hunter_flechette_max_range "1200"
hunter_flechette_min_range "100"
hunter_flechette_speed "2000"
hunter_flechette_test "0"
hunter_flechette_volley_end_max_delay "2"
hunter_flechette_volley_end_min_delay "1"
hunter_flechette_volley_size "8"
hunter_flechette_volley_start_max_delay "0"
hunter_flechette_volley_start_min_delay "0"
hunter_free_knowledge "10"
hunter_hate_attached_striderbusters "1"
hunter_hate_held_striderbusters "1"
hunter_hate_held_striderbusters_delay "0"
hunter_hate_held_striderbusters_tolerance "2000"
hunter_hate_thrown_striderbusters "1"
hunter_hate_thrown_striderbusters_tolerance "300"
hunter_jostle_car_max_speed "600"
hunter_jostle_car_min_speed "100"
hunter_melee_delay "2"
hunter_plant_adjust_z "12"
hunter_random_expressions "0"
hunter_retreat_striderbusters "1" // the hunter will retreat when a buster is glued to him.
hunter_seek_thrown_striderbusters_tolerance "400"
hunter_shoot_flechette // Fires a hunter flechette where the player is looking.
hunter_show_weapon_los_condition "0"
hunter_show_weapon_los_z "0"
hunter_siege_frequency "12"
hunter_stand_still "0"
hurtme // Hurts the player. Arguments: <health to lose>
impulse
incrementvar // Increment specified convar value.
invnext
invprev
in_usekeyboardsampletime "1" // Use keyboard sample time smoothing.
ip "0" // Overrides IP for multihomed hosts
jalopy_blocked_exit_max_speed "50"
jalopy_cargo_anim_time "1"
jalopy_radar_test_ent "0"
joyadvancedupdate
joystick "0"
joy_accelmax "1"
joy_accelscale "0"
joy_accel_filter "0"
joy_advanced "0"
joy_advaxisr "0"
joy_advaxisu "0"
joy_advaxisv "0"
joy_advaxisx "0"
joy_advaxisy "0"
joy_advaxisz "0"
joy_autoaimdampen "0" // How much to scale user stick input when the gun is pointing at a valid target.
joy_autoaimdampenrange "0" // The stick range where autoaim dampening is applied. 0 = off
joy_autosprint "0" // Automatically sprint when moving with an analog joystick
joy_axisbutton_threshold "0" // Analog axis range before a button press is registered.
joy_diagonalpov "0" // too.
joy_display_input "0"
joy_forwardsensitivity "-1"
joy_forwardthreshold "0"
joy_inverty "0" // Whether to invert the Y axis of the joystick for looking.
joy_inverty_default "0"
joy_lowend "1"
joy_lowmap "1"
joy_movement_stick "0" // Which stick controls movement (0 is left stick)
joy_movement_stick_default "0"
joy_name "0"
joy_pegged "0"
joy_pitchsensitivity "1"
joy_pitchsensitivity_default "-1"
joy_pitchthreshold "0"
joy_response_look "0" // 1=Acceleration Promotion
joy_response_move "1" // 1/sensitivity
joy_response_move_vehicle "6"
joy_sidesensitivity "1"
joy_sidethreshold "0"
joy_vehicle_turn_lowend "0"
joy_vehicle_turn_lowmap "0"
joy_virtual_peg "0"
joy_wingmanwarrior_centerhack "0" // Wingman warrior centering hack.
joy_wingmanwarrior_turnhack "0" // Wingman warrior hack related to turn axes.
joy_xcontroller_cfg_loaded "0" // the 360controller.cfg file will be executed on startup & option changes.
joy_xcontroller_found "0" // Automatically set to 1 if an xcontroller has been detected.
joy_yawsensitivity "-1"
joy_yawsensitivity_default "-1"
joy_yawthreshold "0"
jpeg // Take a jpeg screenshot: jpeg <filename> <quality 1-100>.
jpeg_quality "90" // jpeg screenshot quality.
kdtree_test // Tests spatial partition for entities queries.
key_findbinding // Find key bound to specified command string.
key_listboundkeys // List bound keys with bindings.
key_updatelayout // Updates game keyboard layout to current windows keyboard setting.
kick // Kick a player by name.
kickall // Kicks everybody connected with a message.
kickid // with a message.
kill // Kills the player with generic damage
killserver // Shutdown the server.
killvector // Kills a player applying force. Usage: killvector <player> <x value> <y value> <z value>
language_reload // Reloads the language files
lastinv
lightcache_maxmiss "2"
lightprobe // Samples the lighting environment. Creates a cubemap and a file indicating the local lighting in a subdirectory called material
light_crosshair // Show texture color at crosshair
linefile // Parses map leak data from .lin file
listdemo // List demo file contents.
listid // Lists banned users.
listip // List IP addresses on the ban list.
listissues // List all the issues that can be voted on.
listmodels // List loaded models.
listRecentNPCSpeech // Displays a list of the last 5 lines of speech from NPCs.
load // Load a saved game.
loadcommentary
loader_dump_table
loader_spew_info "0" // -1:All
loader_spew_info_ex "0" // (internal)
lod_TransitionDist "800"
log // and udp < on | off >.
logaddress_add // Set address and port for remote host <ip:port>.
logaddress_del // Remove address and port for remote host <ip:port>.
logaddress_delall // Remove all udp addresses being logged to
logaddress_list // List all addresses currently being used by logaddress.
log_verbose_enable "0" // Set to 1 to enable verbose server log on the server.
log_verbose_interval "3" // Determines the interval (in seconds) for the verbose server log.
lookspring "0"
lookstrafe "0"
lservercfgfile "0"
LuaParticle_SettleSpeed "100"
lua_cookieclear
lua_cookiespew
lua_filestats // Lua File Stats
lua_log_cl "0"
lua_log_sv "0"
lua_md5
lua_networkvar_bytespertick "256"
lua_networkvar_refreshtime "60"
lua_openscript // Open a Lua script
lua_openscript_cl // Open a Lua script
lua_reloadents // Reload all scripted entities
lua_run // Run a Lua command
lua_run_cl // Run a Lua command
map // Start playing on specified map. 
```
