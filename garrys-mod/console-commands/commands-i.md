# Commands I

```lua
+alt1
+alt2
+attack
+attack2
+back
+break
+camdistance
+camin
+cammousemove
+camout
+campitchdown
+campitchup
+camyawleft
+camyawright
+commandermousemove
+demoui2 // Bring the advanced demo player UI (demoui2) to foreground.
+duck
+forward
+graph
+grenade1
+grenade2
+jlook
+jump
+klook
+left
+lookdown
+lookup
+mat_texture_list
+movedown
+moveleft
+moveright
+moveup
+posedebug // Turn on pose debugger or add ents to pose debugger UI
+reload
+right
+score
+showbudget
+showbudget_texture
+showbudget_texture_global
+showscores

+showvprof
+speed
+strafe
+use
+vgui_drawtree
+voicerecord
+walk
+zoom
-alt1
-alt2
-attack
-attack2
-back
-break
-camdistance
-camin
-cammousemove
-camout
-campitchdown
-campitchup
-camyawleft
-camyawright
-commandermousemove
-demoui2 // Send the advanced demo player UI (demoui2) to background.
-duck
-forward
-graph
-grenade1
-grenade2
-jlook
-jump
-klook
-left
-lookdown
-lookup
-mat_texture_list
-movedown
-moveleft
-moveright
-moveup
-posedebug // Turn off pose debugger or hide ents from pose debugger UI
-reload
-right
-score
-showbudget
-showbudget_texture
-showbudget_texture_global
-showscores
-showvprof
-speed
-strafe
-use
-vgui_drawtree
-voicerecord
-walk
-zoom
achievement_debug "0" // Turn on achievement debug msgs.
act
addip // Add an IP address to the ban list.
adsp_alley_min "122"
adsp_courtyard_min "126"
adsp_debug "0"
adsp_door_height "112"
adsp_duct_min "106"
adsp_hall_min "110"
adsp_low_ceiling "108"
adsp_opencourtyard_min "126"
adsp_openspace_min "130"
adsp_openstreet_min "118"
adsp_openwall_min "130"
adsp_room_min "102"
adsp_street_min "118"
adsp_tunnel_min "114"
adsp_wall_height "128"
advisor_use_impact_table "1" // advisor will use her custom impact damage table.
ainet_generate_report // Generate a report to the console.
ainet_generate_report_only // Generate a report to the console.
airboat_fatal_stress "5000" // Amount of stress in kg that would kill the airboat driver.
airboat_joy_response_move "1"
air_density // Changes the density of air for drag computations.
ai_actbusy_search_time "10"
ai_ally_manager_debug "0"
ai_auto_contact_solver "1"
ai_block_damage "0"
ai_citizen_debug_commander "1"
ai_clear_bad_links // Clears bits set on nav links indicating link is unusable
ai_debugscriptconditions "0"
ai_debug_actbusy "0" // Used to debug actbusy behavior. Usage: 1: Constantly draw lines from NPCs to the actbusy nodes theyve chosen to actbusy at. 2:
ai_debug_assault "0"
ai_debug_avoidancebounds "0"
ai_debug_directnavprobe "0"
ai_debug_doors "0"
ai_debug_dyninteractions "0" // Debug the NPC dynamic interaction system.
ai_debug_efficiency "0"
ai_debug_enemies "0"
ai_debug_enemyfinders "0"
ai_debug_expressions "0" // Show random expression decisions for NPCs.
ai_debug_follow "0"
ai_debug_loners "0"
ai_debug_looktargets "0"
ai_debug_los "0" // itl
ai_debug_nav "0"
ai_debug_node_connect // Debug the attempted connection between two nodes
ai_debug_ragdoll_magnets "0"
ai_debug_readiness "0"
ai_debug_shoot_positions "0"
ai_debug_speech "0"
ai_debug_squads "0"
ai_debug_think_ticks "0"
ai_default_efficient "0"
ai_disable // Bi-passes all AI logic routines and puts all NPCs into their idle animations. Can be used to get NPCs out of your way and to t
ai_disabled "0"
ai_drawbattlelines "0"
ai_drop_hint // Drop an ai_hint at the players current eye position.
ai_dump_hints
ai_efficiency_override "0"
ai_ef_hate_npc_duration "1"
ai_ef_hate_npc_frequency "5"
ai_enable_fear_behavior "1"
ai_expression_frametime "0" // Maximum frametime to still play background expressions.
ai_expression_optimization "0" // Disable npc background expressions when you cant see them.
ai_fear_player_dist "720"
ai_find_lateral_cover "1"
ai_find_lateral_los "1"
ai_follow_move_commands "1"
ai_follow_use_points "1"
ai_follow_use_points_when_moving "1"
ai_force_serverside_ragdoll "0"
ai_frametime_limit "50" // frametime limit for min efficiency AIE_NORMAL (in secs).
ai_hull // Controls which connections are shown when ai_show_hull or ai_show_connect commands are used Arguments: NPC name or classname,
ai_ignoreplayers "0"
ai_inhibit_spawners "0"
ai_keepragdolls "0"
ai_lead_time "0"
ai_LOS_mode "0"
ai_moveprobe_debug "0"
ai_moveprobe_jump_debug "0"
ai_moveprobe_usetracelist "0"
ai_navigator_generate_spikes "0"
ai_navigator_generate_spikes_strength "8"
ai_newgroundturret "0"
ai_new_aiming "1"
ai_next_hull // Cycles through the various hull sizes. Currently selected hull size is written to the screen. Controls which connections are
ai_nodes // Toggles node display. First call displays the nodes for the given network as green objects. Second call displays the nodes a
ai_norebuildgraph "0"
ai_no_local_paths "0"
ai_no_node_cache "0"
ai_no_select_box "0"
ai_no_steer "0"
ai_no_talk_delay "0"
ai_path_adjust_speed_on_immediate_turns "1"
ai_path_insert_pause_at_est_end "1"
ai_path_insert_pause_at_obstruction "1"
ai_post_frame_navigation "0"
ai_radial_max_link_dist "512"
ai_reaction_delay_alert "0"
ai_reaction_delay_idle "0"
ai_readiness_decay "120"
ai_rebalance_thinks "1"
ai_report_task_timings_on_limit "0"
ai_resume // If NPC is stepping through tasks (see ai_step ) will resume normal processing.
ai_sequence_debug "0"
ai_setupbones_debug "0" // Shows that bones that are setup every think
ai_set_move_height_epsilon // Set how high AI bumps up ground walkers when checking steps
ai_shot_bias "1"
ai_shot_bias_max "1"
ai_shot_bias_min "-1"
ai_shot_stats "0"
ai_shot_stats_term "1000"
ai_show_connect // Displays the allowed connections between each node for the currently selected hull type. Hulls are color code as follows: Gre
ai_show_connect_fly // Displays the allowed connections between each node for the currently selected hull type. Hulls are color code as follows: Gre
ai_show_connect_jump // Displays the allowed connections between each node for the currently selected hull type. Hulls are color code as follows: Gre
ai_show_graph_connect // Toggles graph connection display for the node that the player is looking at. Nodes that are connected to the selected node by
ai_show_grid // Draw a grid on the floor where looking.
ai_show_hints // Displays all hints as small boxes Blue - hint is available for use Red - hint is currently being used by an NPC Orange -
ai_show_hull // Displays the allowed hulls between each node for the currently selected hull type. Hulls are color code as follows: Green -
ai_show_hull_attacks "0"
ai_show_node // Highlight the specified node
ai_show_think_tolerance "0"
ai_show_visibility // Toggles visibility display for the node that the player is looking at. Nodes that are visible from the selected node will be d
ai_simulate_task_overtime "0"
ai_spread_cone_focus_time "0"
ai_spread_defocused_cone_multiplier "3"
ai_spread_pattern_focus_time "0"
ai_step // use ai_step again. To resume processing no
ai_strong_optimizations "0"
ai_strong_optimizations_no_checkstand "0"
ai_task_pre_script "0"
ai_test_los // Test AI LOS from the players POV
ai_test_moveprobe_ignoresmall "0"
ai_think_limit_label "0"
ai_use_clipped_paths "1"
ai_use_efficiency 
```
