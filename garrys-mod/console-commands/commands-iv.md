# Commands IV

```lua
commentary_showmodelviewer // Display the commentary model viewer. Usage: commentary_showmodelviewer <model name> <optional attached model name>
commentary_testfirstrun
condump // dump the text currently in the console to condumpXX.log
connect // Connect to specified server.
contimes "8" // Number of console lines to overlay for debugging.
con_drawnotify "1" // Disables drawing of notification area (for taking screenshots).
con_enable "0" // Allows the console to be activated.
con_filter_enable "0" // 2 displays filtered text brighter than ot
con_filter_text "0" // Text with which to filter console spew. Set con_filter_enable 1 or 2 to activate.
con_filter_text_out "0" // Text with which to filter OUT of console spew. Set con_filter_enable 1 or 2 to activate.
con_notifytime "8" // How long to display recent console text to the upper part of the game window
con_nprint_bgalpha "50" // Con_NPrint background alpha.
con_nprint_bgborder "5" // Con_NPrint border size.
con_timestamp "0" // Prefix console.log entries with timestamps
con_trace "0" // Print console text to low level printout.
coop "0" // Cooperative play.
CreateHairball
create_flashlight
creditsdone
crosshair "1"
cursor_active "0"
cursor_x "0"
cursor_y "0"
cursor_z "0"
curve_bias "0"
cvarlist // Show the list of convars/concommands.
c_maxdistance "200"
c_maxpitch "90"
c_maxyaw "135"
c_mindistance "30"
c_minpitch "0"
c_minyaw "-135"
c_orthoheight "100"
c_orthowidth "100"
datacachesize "32" // Size in MB.
dbghist_addline // Add a line to the debug history. Format: <category id> <line>
dbghist_dump // Dump the debug history to the console. Format: <category id> Categories: 0: Entity I/O 1: AI Decisions 2: Sc
deathmatch "0" // Running a deathmatch server.
debugsystemui // Show/hide the debug system UI.
debug_materialmodifycontrol "0"
debug_materialmodifycontrol_client "0"
debug_physimpact "0"
debug_touchlinks "0" // Spew touch link activity
decalfrequency "10"
default_fov "75"
demolist // Print demo sequence list.
demos // Demo demo file sequence.
demoui // Show/hide the demo player UI.
demoui2 // Show/hide the advanced demo player UI (demoui2).
demo_avellimit "2000" // Angular velocity limit before eyes considered snapped for demo playback.
demo_debug "0" // Demo debug info.
demo_fastforwardfinalspeed "20" // Go this fast when starting to hold FF button.
demo_fastforwardramptime "5" // How many seconds it takes to get to full FF speed.
demo_fastforwardstartspeed "2" // Go this fast when starting to hold FF button.
demo_fov_override "0" // this value will be used to override FOV during demo playback.
demo_gototick // Skips to a tick in demo.
demo_interplimit "4000" // How much origin velocity before its considered to have teleported causing interpolation to reset.
demo_interpolateview "1" // Do view interpolation during dem playback.
demo_legacy_rollback "1" // Use legacy view interpolation rollback amount in demo playback.
demo_pause // Pauses demo playback.
demo_pauseatservertick "0" // Pauses demo playback at server tick
demo_quitafterplayback "0" // Quits game after demo playback.
demo_recordcommands "1" // Record commands typed at console into .dem files.
demo_resume // Resumes demo playback.
demo_setendtick // Sets end demo playback tick. Set to 0 to disable.
demo_timescale // Sets demo replay speed.
demo_togglepause // Toggles demo playback.
derma_controls
developer "0" // Set developer message level
devshots_nextmap // Used by the devshots system to go to the next map in the devshots maplist.
devshots_screenshot // use the screenshot command instead.
differences // Show all convars which are not at their default values.
disconnect // Disconnect game from server.
dispcoll_drawplane "0"
displaysoundlist "0"
disp_dynamic "0"
dlight_debug // Creates a dlight in front of the player
dog_debug "0"
dog_max_wait_time "7"
download_debug "0"
drawcross // Draws a cross at the given location Arguments: x y z
drawline // Draws line between two 3D Points. Green if no collision Red is collides with something Arguments: x1 y1 z1 x2 y2 z2
dropprimary // dropprimary: Drops the primary weapon of the player.
dsp_automatic "0"
dsp_db_min "80"
dsp_db_mixdrop "0"
dsp_dist_max "1440"
dsp_dist_min "0"
dsp_enhance_stereo "0"
dsp_facingaway "0"
dsp_mix_max "0"
dsp_mix_min "0"
dsp_off "0"
dsp_player "0"
dsp_reload
dsp_room "0"
dsp_slow_cpu "0"
dsp_spatial "40"
dsp_speaker "50"
dsp_volume "1"
dsp_vol_2ch "1"
dsp_vol_4ch "0"
dsp_vol_5ch "0"
dsp_water "14"
dti_flush // Write out the datatable instrumentation files (you must run with -dti for this to work).
dtwarning "0" // Print data table warnings?
dtwatchclass "0" // Watch all fields encoded with this table.
dtwatchent "-1" // Watch this entities data table encoding.
dtwatchvar "0" // Watch the named variable.
dt_ShowPartialChangeEnts "0" // (SP only) - show entities that were copied using small optimized lists (FL_EDICT_PARTIAL_CHANGE).
dt_UsePartialChangeEnts "1" // (SP only) - enable FL_EDICT_PARTIAL_CHANGE optimization.
dumpentityfactories // Lists all entity factory names.
dumpeventqueue // Dump the contents of the Entity I/O event queue to the console.
dumpgamestringtable // Dump the contents of the game string table to the console.
dumplongticks // Enables generating minidumps on long ticks.
dumpsavedir // List the contents of the save directory in memory
dumpstringtables // Print string tables to console.
dumpstringtables_new // or list them if none
dumpstringtables_new // or list them if none
dump_entity_sizes // Print sizeof(entclass)
dump_globals // Dump all global entities/states
dump_luafiles
dump_luafiles
dump_luafiles_bootstrap
dump_luafiles_nosend
dump_panels // Dump Panel Tree
dump_pooledstrings // Dumps a list of Lua pooled strings
dump_x360_cfg // Dump X360 config files to disk
dump_x360_saves // Dump X360 save games to disk
echo // Echo text to console.
editdemo // Edit a recorded demo file (.dem ).
editor_toggle // Disables the simulation and returns focus to the editor
effects_list // engine effects.
effects_reload // Reloads the effect scripts (For development purposes)
enable_debug_overlays "1" // Enable rendering of debug overlays
endmovie // Stop recording movie frames.
english "1" // running the english language set of assets.
ent_absbox // Displays the total bounding box for the given entity(s) in green. Some entites will also display entity specific overlays. Ar
ent_attachments // Displays the attachment points on an entity. Arguments: {entity_name} / {class_name} / no argument picks what player is loo
ent_autoaim // Displays the entitys autoaim radius. Arguments: {entity_name} / {class_name} / no argument picks what player is looking at
ent_bbox // Displays the movement bounding box for the given entity(ies) in orange. Some entites will also display entity specific overlay
ent_cancelpendingentfires // Cancels all ent_fire created outputs that are currently waiting for their delay to expire.
ent_create // Creates an entity of the given type where the player is looking. Additional parameters can be passed in in the form: ent_creat
ent_debugkeys "0"
ent_dump // Usage: ent_dump <entity name>
ent_fire // Usage: ent_fire <target> [action] [value] [delay]
ent_info // Usage: ent_info <class name>
ent_keyvalue // Applies the comma delimited key=value pairs to the entity with the given Hammer ID. Format: ent_keyvalue <entity id> <key1>=<v
ent_messages // Toggles input/output message display for the selected entity(ies). The name of the entity will be displayed as well as any mes
ent_messages_draw "0" // Visualizes all entity input/output activity.
ent_name
ent_orient // only orients target entitys YAW. Use the allangles opt
ent_pause // Toggles pausing of input/output message processing for entities. When turned on processing of all message will stop. Any mess
ent_pivot // Displays the pivot for the given entity(ies). (y=up=green, z=forward=blue, x=left=red). Arguments: {entity_name} / {class
```
