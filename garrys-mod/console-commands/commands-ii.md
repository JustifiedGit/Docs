# Commands II

```lua
ai_use_frame_think_limits "1"
ai_use_readiness "1"
ai_use_think_optimizations "1"
ai_use_visibility_cache "1"
ai_vehicle_avoidance "1"
alias // Alias a command.
anim_3wayblend "1" // Toggle the 3-way animation blending code.
anim_showmainactivity "0" // and/or sprint activities.
anim_showstate "-1" // Show the (client) animation state for the specified entity (-1 for none).
anim_showstatelog "0" // 1 to output anim_showstate to Msg(). 2 to store in AnimState.log. 3 for both.
antlion_easycrush "1"
askconnect_accept // Accept a redirect request by the server.
async_allow_held_files "1" // Allow AsyncBegin/EndRead()
async_mode "0" // 1 = synchronous)
async_resume
async_serialize "0" // Force async reads to serialize for profiling
async_simulate_delay "0" // Simulate a delay of up to a set msec per file operation
async_suspend
audit_save_in_memory // Audit the memory usage and files in the save-to-memory system
autoaim_max_deflect "0"
autoaim_max_dist "2160"
autoaim_unlock_target "0"
autosave // Autosave
autosavedangerous // AutoSaveDangerous
autosavedangerousissafe
banid // Add a user ID to the ban list.
banip // Add an IP address to the ban list.
benchframe // Takes a snapshot of a particular frame in a time demo.
bench_end // Ends gathering of info.
bench_showstatsdialog // Shows a dialog displaying the most recent benchmark results.
bench_start // Starts gathering of info. Arguments: filename to write results into
bench_upload // Uploads most recent benchmark stats to the Valve servers.
bind // Bind a key.
binds_per_command "1"
BindToggle // Performs a bind <key> increment var <cvar> 0 1 1
bind_mac // not win32
birds_debug "0"
blink_duration "0" // How many seconds an eye blink will last.
bloodspray // blood
bot // Add a bot.
bot_attack "0" // Shoot!
bot_changeclass "0" // Force all bots to change to the specified class.
bot_crouch "0" // Bot crouches
bot_defend "0" // and that team will all keep their combat shields raised.
bot_flipout "0" // all bots fire their guns.
bot_forceattack2 "0" // use attack2.
bot_forceattackon "0" // hold it down.
bot_forcefireweapon "0" // Force bots with the specified weapon to fire.
bot_mimic "0" // Bot uses usercmd of player by index.
bot_mimic_yaw_offset "0" // Offsets the bot yaw.
bot_sendcmd "0" // Forces bots to send the specified command.
bot_zombie "0" // Brraaaaaiiiins.
box // Draw a debug box.
breakable_disable_gib_limit "0"
breakable_multiplayer "1"
buddha // Toggle. Player takes damage but wont die. (Shows red cross when health is zero)
budget_averages_window "30" // number of frames to look at when figuring out average frametimes
budget_background_alpha "128" // how translucent the budget panel is
budget_bargraph_background_alpha "128" // how translucent the budget panel is
budget_bargraph_range_ms "16" // budget bargraph range in milliseconds
budget_history_numsamplesvisible "100" // number of samples to draw in the budget history window. The lower the better as far as rendering overhead of the budget panel
budget_history_range_ms "66" // budget history range in milliseconds
budget_panel_bottom_of_history_fraction "0" // number between 0 and 1
budget_panel_height "384" // height in pixels of the budget panel
budget_panel_width "512" // width in pixels of the budget panel
budget_panel_x "0" // number of pixels from the left side of the game screen to draw the budget panel
budget_panel_y "50" // number of pixels from the top side of the game screen to draw the budget panel
budget_peaks_window "30" // number of frames to look at when figuring out peak frametimes
budget_show_averages "0" // enable/disable averages in the budget panel
budget_show_history "1" // turn history graph off and on. . good to turn off on low end
budget_show_peaks "1" // enable/disable peaks in the budget panel
budget_toggle_group // Turn a budget group on/off
bug // Show/hide the bug reporting UI.
bugbait_distract_time "5"
bugbait_grenade_radius "150"
bugbait_hear_radius "2500"
bugbait_radius "512"
bugreporter_includebsp "1" // Include .bsp for internal bug submissions.
bugreporter_uploadasync "0" // Upload attachments asynchronously
bug_swap // Automatically swaps the current weapon for the bug bait and back again.
buildcubemaps // Rebuild cubemaps.
building_cubemaps "0"
bulletspeed "6000"
cache_print // cache_print [section] Print out contents of cache memory.
cache_print_lru // cache_print_lru [section] Print out contents of cache memory.
cache_print_summary // cache_print_summary [section] Print out a summary contents of cache memory.
callvote // Start a vote on an issue.
camortho // Switch to orthographic camera.
cam_collision "1" // an attempt is made to keep the camera from passing though walls.
cam_command "0"
cam_idealdelta "4" // Controls the speed when matching offset to ideal angles in thirdperson view
cam_idealdist "150"
cam_idealdistright "0"
cam_idealdistup "0"
cam_ideallag "4" // Amount of lag used when matching offset to ideal angles in thirdperson view
cam_idealpitch "0"
cam_idealyaw "0"
cam_showangles "0" // print viewangles/idealangles/cameraoffsets to the console.
cam_snapto "0"
cancelselect
cast_hull // Tests hull collision detection
cast_ray // Tests collision detection
cc_captiontrace "1" // 2 = show in hud)
cc_linger_time "1" // Close caption linger time.
cc_predisplay_time "0" // Close caption delay before showing caption.
cc_smallfontlength "300" // force usage of small font size.
cc_subtitles "0" // wont help hearing impaired players).
centerview
changegamemode // <map> <gamemode> - Start a map with named gamemode instead of the default
changelevel // Change server to the specified map
changelevel2 // Transition to the specified map in single player
ch_createairboat // Spawn airboat in front of the player.
ch_createjalopy // Spawn jalopy in front of the player.
ch_createjeep // Spawn jeep in front of the player.
clear // Clear all console output.
clear_debug_overlays // clears debug overlays
clientport "27005" // Host game client port
closecaption "0" // Enable close captioning.
cl_allowdownload "1" // Client downloads customization files
cl_allowupload "1" // Client uploads customization files
cl_anglespeedkey "0"
cl_animationinfo // Hud element to examine.
cl_autowepswitch "1" // Automatically switch to picked up weapons (if more powerful)
cl_backspeed "450"
cl_bob "0"
cl_bobcycle "0"
cl_bobup "0"
cl_burninggibs "0" // A burning player that gibs has burning gibs.
cl_chatfilters "63" // Stores the chat filter settings
cl_class "0" // Default class when joining a game
cl_clearhinthistory // Clear memory of client side hints displayed to the player.
cl_clockdrift_max_ms "150" // Maximum number of milliseconds the clock is allowed to drift before the client snaps its clock to the servers.
cl_clockdrift_max_ms_threadmode "0" // Maximum number of milliseconds the clock is allowed to drift before the client snaps its clock to the servers.
cl_clock_correction "1" // Enable/disable clock correction on the client.
cl_clock_correction_adjustment_max_amount "200" // Sets the maximum number of milliseconds per second it is allowed to correct the client clock. It will only correct this amount
cl_clock_correction_adjustment_max_offset "90" // it moves towards apply
cl_clock_correction_adjustment_min_offset "10" // then no clock correction is applied.
cl_clock_correction_force_server_tick "999" // Force clock correction to match the server tick + this offset (-999 disables it).
cl_clock_showdebuginfo "0" // Show debugging info about the clock drift.
cl_cmdrate "30" // Max number of command packets sent to server per second
cl_customsounds "0" // Enable customized player sound playback
cl_debugrumble "0" // Turn on rumble debugging spew
cl_debug_player_perf "0"
cl_defaultweapon "0" // Default Spawn Weapon
cl_demoviewoverride "0" // Override view during demo playback
cl_detaildist "1200" // Distance at which detail props are no longer visible
cl_detailfade "400" // Distance across which detail props fade in 
```
