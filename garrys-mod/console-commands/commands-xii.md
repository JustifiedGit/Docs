# Commands XII

```lua
print_colorcorrection // Display the color correction layer information.
progress_enable
props_break_max_pieces "-1" // Maximum prop breakable piece count (-1 = model default)
props_break_max_pieces_perframe "-1" // Maximum prop breakable piece count per frame (-1 = model default)
prop_active_gib_limit "999999"
prop_active_gib_max_fade_time "999999"
prop_crosshair // Shows name for prop looking at
prop_debug // props will show colorcoded bounding boxes. Red means ignore all damage. White means respond phys
prop_dynamic_create // Creates a dynamic prop with a specific .mdl aimed away from where the player is looking. Arguments: {.mdl name}
prop_physics_create // Creates a physics prop with a specific .mdl aimed away from where the player is looking. Arguments: {.mdl name}
pwatchent "-1" // Entity to watch for prediction system changes.
pwatchvar "0" // Entity variable to watch in prediction system for changes.
pyro_max_intensity "0"
pyro_max_rate "0"
pyro_max_side_length "0"
pyro_max_side_width "0"
pyro_min_intensity "0"
pyro_min_rate "0"
pyro_min_side_length "0"
pyro_min_side_width "0"
pyro_vignette "2"
pyro_vignette_distortion "1"
quit // Exit the engine.
ragdoll_sleepaftertime "5" // the ragdoll will go to sleep.
rate "30000" // Max bytes/sec the host can receive data
rcon // Issue an rcon command.
rcon_address "0" // Address of remote server if sending unconnected rcon commands (format x.x.x.x:p)
rcon_password "0" // remote console password.
recompute_speed // Recomputes clock speed (for debugging purposes).
record // Record a demo.
refresh_options_dialog // Refresh the options dialog.
reload // Reload the most recent saved game (add setpos to jump to current view position on reload).
reload_materials "0"
reload_postprocess // Reload the post process scripts
removeid // Remove a user ID from the ban list.
removeip // Remove an IP address from the ban list.
replay_debug "0"
replay_ignorereplayticks "0"
report_entities // Lists all entities
report_simthinklist // Lists all simulating/thinking entities
report_soundpatch // reports sound patch count
report_soundpatch // reports sound patch count
report_touchlinks // Lists all touchlinks
respawn_entities // Respawn all the entities in the map.
restart // Restart the game on the same level (add setpos to jump to current view position on restart).
retry // Retry connection to last server.
room_type "0"
rope_averagelight "1" // Makes ropes use average of cubemap lighting instead of max intensity.
rope_collide "1" // Collide rope with the world
rope_rendersolid "1"
rope_shake "0"
rope_smooth "1" // Do an antialiasing effect on ropes
rope_smooth_enlarge "1" // How much to enlarge ropes in screen space for antialiasing effect
rope_smooth_maxalpha "0" // Alpha for rope antialiasing effect
rope_smooth_maxalphawidth "1"
rope_smooth_minalpha "0" // Alpha for rope antialiasing effect
rope_smooth_minwidth "0" // this is the min screenspace width it lets a rope shrink to
rope_solid_maxalpha "1"
rope_solid_maxwidth "1"
rope_solid_minalpha "0"
rope_solid_minwidth "0"
rope_subdiv "2" // Rope subdivision amount
rope_wind_dist "1000" // Dont use CPU applying small wind gusts to ropes when theyre past this distance.
rr_debugresponses "0" // it will only show response success/failure for np
rr_debugrule "0" // that rules score will be shown whenever a concept is passed into the response rules system.
rr_debug_qa "0" // Set to 1 to see debug related to the Question & Answer system used to create conversations between allied NPCs.
rr_dumpresponses "0" // Dump all response_rules.txt and rules (requires restart)
rr_reloadresponsesystems // Reload all response system scripts.
r_3dnow // Enable/disable 3DNow code
r_3dsky "1" // Enable the rendering of 3d sky boxes
r_AirboatPitchCurveLinear "60"
r_AirboatPitchCurveZero "25"
r_AirboatRollCurveLinear "120"
r_AirboatRollCurveZero "90"
r_AirboatViewBlendTo "1"
r_AirboatViewBlendToScale "0"
r_AirboatViewBlendToTime "1"
r_ambientboost "1" // Set to boost ambient term if it is totally swamped by local lights
r_ambientfactor "5" // Boost ambient cube by no more than this factor
r_ambientfraction "0" // Fraction of direct lighting that ambient cube must be below to trigger boosting
r_ambientlightingonly "0" // Set this to 1 to light models with only ambient lighting (and no static lighting).
r_ambientmin "0" // Threshold above which ambient cube will not boost (i.e. its already sufficiently bright
r_aspectratio "0"
r_avglight "1"
r_avglightmap "0"
r_bloomtintb "0"
r_bloomtintexponent "2"
r_bloomtintg "0"
r_bloomtintr "0"
r_cheapwaterend
r_cheapwaterstart
r_cleardecals // Usage r_cleardecals <permanent>.
r_ClipAreaPortals "1"
r_colorstaticprops "0"
r_debugcheapwater "0"
r_debugrandomstaticlighting "0" // Set to 1 to randomize static lighting for debugging. Must restart for change to take affect.
r_decals "2048"
r_decalstaticprops "1" // Decal static props test
r_decal_cover_count "4"
r_decal_cullsize "5"
r_decal_overlap_area "0"
r_decal_overlap_count "3"
r_depthoverlay "0" // Replaces opaque objects with their grayscaled depth values. r_showz_power scales the output.
r_DispBuildable "0"
r_DispDrawAxes "0"
r_DispWalkable "0"
r_dopixelvisibility "1"
r_drawbatchdecals "1" // Render decals batched.
r_DrawBeams "1" // 2=Wireframe
r_drawbrushmodels "1" // 2=Wireframe
r_drawclipbrushes "0" // purple=NPC)
r_drawdecals "1" // Render decals.
r_drawdetailprops "1" // 2=Wireframe
r_DrawDisp "1" // Toggles rendering of displacment maps
r_drawentities "1"
r_drawflecks "1"
r_drawfuncdetail "1" // Render func_detail
r_drawleaf "-1" // Draw the specified leaf.
r_drawlightcache "0" // 0: off 1: draw light cache entries 2: draw rays
r_drawlightinfo "0"
r_drawlights "0"
r_drawmodeldecals "1"
r_DrawModelLightOrigin "0"
r_drawmodelstatsoverlay "0"
r_drawmodelstatsoverlaydistance "500"
r_drawmodelstatsoverlaymax "1" // time in milliseconds beyond which a model overlay is fully red in r_drawmodelstatsoverlay 2
r_drawmodelstatsoverlaymin "0" // time in milliseconds that a model must take to render before showing an overlay in r_drawmodelstatsoverlay 2
r_drawopaquerenderables "1"
r_drawopaquestaticpropslast "0" // Whether opaque static props are rendered after non-npcs
r_drawopaqueworld "1"
r_drawothermodels "1" // 2=Wireframe
r_drawparticles "1" // Enable/disable particle rendering
r_drawpixelvisibility "0" // Show the occlusion proxies
r_DrawPortals "0"
r_DrawRain "1" // Enable/disable rain rendering.
r_drawrenderboxes "0"
r_drawropes "1"
r_drawskybox "1"
r_DrawSpecificStaticProp "-1"
r_drawsprites "1"
r_drawstaticprops "1" // 2=Wireframe
r_drawtranslucentrenderables "1"
r_drawtranslucentworld "1"
r_drawvgui "1" // Enable the rendering of vgui panels
r_drawviewmodel "1"
r_drawworld "1" // Render the world.
r_dscale_basefov "90"
r_dscale_fardist "2000"
r_dscale_farscale "4"
r_dscale_neardist "100"
r_dscale_nearscale "1"
r_dynamic "1"
r_dynamiclighting "1"
r_emulategl "0"
r_entityclips "1"
r_eyeglintlodpixels "20" // The number of pixels wide an eyeball has to be before rendering an eyeglint. Is a floating point value.
r_eyemove "1"
r_eyes "1"
r_eyeshift_x "0"
r_eyeshift_y "0"
r_eyeshift_z "0"
r_eyesize "0"
r_eyewaterepsilon "10"
r_farz "30000" // Override the far clipping plane. -1 means to use the value in env_fog_controller.
r_fastzreject "0" // Activate/deactivates a fast z-setting algorithm to take advantage of hardware with fast z reject. Use -1 to default to hardware
r_fastzrejectdisp "0" // Activates/deactivates fast z rejection on displacements (360 only). Only active when r_fastzreject is on.
r_flashlightambient "0"
r_flashlightclip "0"
r_flashlightconstant "0"
r_flashlightculldepth "1"
r_flashlightdepthres "1024"
r_flashlightdepthtexture "1"
r_flashlightdrawclip "0"
r_flashlightdrawdepth "0"
r_flashlightdrawfrustum "0"
r_flashlightdrawfrustumbbox "0"
r_flashlightdrawsweptbbox "0"
r_flashlightfar "750"
r_flashlightfov "45"
r_flashlightladderdist "40"
r_flashlightlinear "100" 
```
