# Commands XVII

```lua
sv_skyname "0" // Current name of the skybox texture
sv_soundemitter_trace "0" // Show all EmitSound calls including their symbolic name and the actual wave file they resolved to
sv_specaccelerate "5"
sv_specnoclip "1"
sv_specspeed "3"
sv_stats "1" // Collect CPU usage stats
sv_steamblockingcheck "0" // 3 >= dr
sv_steamgroup "0" // The ID of the steam group that this server belongs to. You can find your groups ID on the admin profile page in the steam comm
sv_stickysprint "0"
sv_stickysprint_default "0"
sv_stopspeed "50" // Minimum stopping speed when on ground.
sv_strict_notarget "0" // notarget will cause entities to never think they are in the pvs
sv_tags "0" // Server tags. Used to provide extra information to clients when theyre browsing for servers. Separate tags with a comma.
sv_teststepsimulation "1"
sv_test_scripted_sequences "0" // Tests for scripted sequences that are embedded in the world. Run through your map with this set to check for NPCs falling throu
sv_thinktimecheck "0" // Check for thinktimes all on same timestamp.
sv_timeout "180" // the client is dropped
sv_turbophysics "0" // Turns on turbo physics
sv_unlockedchapters "19" // Highest unlocked game chapter.
sv_usermessage_maxsize "1024" // The max number of bytes to output per tick
sv_use_steam_voice "1" // voice_inputfromfile will no longer function).
sv_vehicle_autoaim_scale "8"
sv_visiblemaxplayers "-1" // Overrides the max players reported to prospective clients
sv_voicecodec "0" // Specifies which voice codec DLL to use in a game. Set to the name of the DLL without the extension.
sv_voiceenable "1"
sv_vote_allow_spectators "0" // Allow spectators to vote?
sv_vote_failure_timer "300" // A vote that fails cannot be re-submitted for this long
sv_vote_ui_hide_disabled_issues "1" // Suppress listing of disabled issues in the vote setup screen.
sv_wateraccelerate "10"
sv_waterfriction "1"
systemlinkport "27030" // System Link port
sys_minidumpexpandedspew "1"
sys_minidumpspewlines "500" // Lines of crash dump console spew to keep.
template_debug "0"
testhudanim // Test a hud element animation. Arguments: <anim name>
testscript_debug "0" // Debug test scripts.
Test_CreateEntity
test_dispatcheffect // Test a clientside dispatch effect. Usage: test_dispatcheffect <effect name> <distance away> <flags> <magnitude> <scale> Defau
Test_EHandle
test_entity_blocker // Test command that drops an entity blocker out in front of the player.
test_freezeframe // Test the freeze frame code.
Test_InitRandomEntitySpawner
test_massive_dmg "30"
test_massive_dmg_clip "0"
Test_ProxyToggle_EnableProxy
Test_ProxyToggle_EnsureValue // Test_ProxyToggle_EnsureValue
Test_ProxyToggle_SetValue
Test_RandomizeInPVS
Test_RandomPlayerPosition
Test_RemoveAllRandomEntities
Test_SpawnRandomEntities
texture_budget_background_alpha "128" // how translucent the budget panel is
texture_budget_panel_bottom_of_history_fraction "0" // number between 0 and 1
texture_budget_panel_global "0" // Show global times in the texture budget panel.
texture_budget_panel_height "284" // height in pixels of the budget panel
texture_budget_panel_width "512" // width in pixels of the budget panel
texture_budget_panel_x "0" // number of pixels from the left side of the game screen to draw the budget panel
texture_budget_panel_y "450" // number of pixels from the top side of the game screen to draw the budget panel
tf_arena_max_streak "3" // Teams will be scrambled if one team reaches this streak
tf_arena_preround_time "10" // Length of the Pre-Round time
tf_arena_round_time "0"
tf_arena_use_queue "1" // Enables the spectator queue system for Arena.
tf_escort_recede_time "30"
tf_escort_recede_time_overtime "5"
tf_escort_score_rate "1" // in points per second
tf_matprox_BurnLevel "0"
tf_matprox_InvulnLevel "0"
tf_matprox_spy_invis "0"
tf_matprox_YellowLevel "1"
tf_show_train_path "0"
think_limit "10" // warning is printed if this is exceeded.
thirdperson // Switch to thirdperson camera.
thirdperson_mayamode // Switch to thirdperson Maya-like camera controls.
thirdperson_platformer "0" // Player will aim in the direction they are moving.
thirdperson_screenspace "0" // eg: left means screen-left
threadpool_affinity "1" // Enable setting affinity
thumper_show_radius "0" // advisor will use her custom impact damage table.
timedemo // Play a demo and report performance info.
timedemoquit // and then exit
timerefresh // Profile the renderer.
toggle // or cycles through a set of values.
toggleconsole // Show/hide the console.
toggle_duck // Toggles duck
toggle_zoom // Toggles zoom display
toybox_entity // Spawn a test entity from a local file
toybox_save // Save a game onto the cloud
toybox_weapon // Spawn a test weapon from a local file
tracer_extra "1"
trace_report "0"
tv_allow_camera_man "1" // Auto director allows spectators to become camera man
tv_allow_static_shots "1" // Auto director uses fixed level cameras for shots
tv_autorecord "0" // Automatically records all games as SourceTV demos.
tv_autoretry "1" // Relay proxies retry connection after network timeout
tv_chatgroupsize "0" // Set the default chat group size
tv_chattimelimit "8" // Limits spectators to chat only every n seconds
tv_clients // Shows list of connected SourceTV clients.
tv_debug "0" // SourceTV debug info.
tv_delay "30" // SourceTV broadcast delay in seconds
tv_delaymapchange "0" // Delays map change until broadcast is complete
tv_deltacache "2" // Enable delta entity bit stream cache
tv_dispatchmode "1" // 2=always
tv_enable "0" // Activates SourceTV on server.
tv_maxclients "128" // Maximum client number on SourceTV server.
tv_maxrate "8000" // 0 == unlimited
tv_msg // Send a screen message to all clients.
tv_name "0" // SourceTV host name
tv_nochat "0" // Dont receive chat messages from other SourceTV spectators
tv_overridemaster "0" // Overrides the SourceTV master root address.
tv_password "0" // SourceTV password for all clients
tv_port "27020" // Host SourceTV port
tv_relay // Connect to SourceTV server and relay broadcast.
tv_relaypassword "0" // SourceTV password for relay proxies
tv_relayvoice "1" // 1=on
tv_retry // Reconnects the SourceTV relay proxy.
tv_snapshotrate "16" // Snapshots broadcasted per second
tv_status // Show SourceTV server status.
tv_stop // Stops the SourceTV broadcast.
tv_stoprecord // Stops SourceTV demo recording.
tv_timeout "30" // SourceTV connection timeout in seconds.
tv_title "0" // Set title for SourceTV spectator UI
tv_transmitall "0" // Transmit all entities (not only director view)
ui_posedebug_fade_in_time "0" // Time during which a new pose activity layer is shown in green in +posedebug UI
ui_posedebug_fade_out_time "0" // Time to keep a no longer active pose activity layer in red until removing it from +posedebug UI
unbind // Unbind a key.
unbindall // Unbind all keys.
unbind_mac // Unbind a key on the Mac only.
unpause // Unpause the game.
updatemyinfo // Re-send your myinfo variables to the server
use // Use a particular weapon Arguments: <weapon_name>
user // Show user data.
users // Show user info for players on server.
user_context // Set a Rich Presence Context: user_context <context id> <context value>
user_property // Set a Rich Presence Property: user_property <property id>
vcollide_wireframe "0" // Render physics collision models in wireframe
vcr_verbose "0" // Write extra information into .vcr file.
vehicle_flushscript // Flush and reload all vehicle scripts
version // Print version info string.
vgui_allowhtml "1"
vgui_drawfocus "0" // Report which panel is under the mouse.
vgui_drawtree "0" // Draws the vgui panel hiearchy to the specified depth level.
vgui_drawtree_bounds "0" // Show panel bounds.
vgui_drawtree_clear
vgui_drawtree_draw_selected "0" // Highlight the selected panel
vgui_drawtree_freeze "0" // Set to 1 to stop updating the vgui_drawtree view.
vgui_drawtree_hidden "0" // Draw the hidden panels.
vgui_drawtree_panelalpha "0" // Show the panel alpha values in the vgui_drawtree view. 
```
