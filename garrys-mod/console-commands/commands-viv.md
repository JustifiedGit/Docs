# Commands VIV

```lua
nav_area_bgcolor "0" // RGBA color to draw as the background color for nav areas while editing.
nav_area_max_size "50" // Max area size created in nav generation
nav_avoid // Toggles the avoid this area when possible flag used by the AI system.
nav_begin_area // drag the opposite corner to the desired location and
nav_begin_deselecting // Start continuously removing from the selected set.
nav_begin_drag_deselecting // Start dragging a selection area.
nav_begin_drag_selecting // Start dragging a selection area.
nav_begin_selecting // Start continuously adding to the selected set.
nav_begin_shift_xy // Begin shifting the Selected Set.
nav_build_ladder // Attempts to build a nav ladder on the climbable surface under the cursor.
nav_check_file_consistency // Scans the maps directory and reports any missing/out-of-date navigation files.
nav_check_floor // Updates the blocked/unblocked status for every nav area.
nav_check_stairs // Update the nav mesh STAIRS attribute
nav_chop_selected // Chops all selected areas into their component 1x1 areas
nav_clear_attribute // Remove given nav attribute from all areas in the selected set.
nav_clear_selected_set // Clear the selected set.
nav_clear_walkable_marks // Erase any previously placed walkable positions.
nav_compress_id // Re-orders area and ladder IDs so they are continuous.
nav_connect // then invoke the connect command. Note that this creates a
nav_coplanar_slope_limit "0"
nav_coplanar_slope_limit_displacement "0"
nav_corner_adjust_adjacent "18" // radius used to raise/lower corners in nearby areas when raising/lowering corners.
nav_corner_lower // Lower the selected corner of the currently marked Area.
nav_corner_place_on_ground // Places the selected corner of the currently marked Area on the ground.
nav_corner_raise // Raise the selected corner of the currently marked Area.
nav_corner_select // Select a corner of the currently marked Area. Use multiple times to access all four corners.
nav_create_area_at_feet "0" // Anchor nav_begin_area Z to editing players feet
nav_create_place_on_ground "0" // nav areas will be placed flush with the ground when created by hand.
nav_crouch // Toggles the must crouch in this area flag used by the AI system.
nav_debug_blocked "0"
nav_delete // Deletes the currently highlighted Area.
nav_delete_marked // Deletes the currently marked Area (if any).
nav_disconnect // then invoke the disconnect command. This will remove all connec
nav_disconnect_outgoing_oneways // disconnect all outgoing one-way connections.
nav_displacement_test "10000" // Checks for nodes embedded in displacements (useful for in-development maps)
nav_dont_hide // Toggles the area is not suitable for hiding spots flag used by the AI system.
nav_drag_selection_volume_zmax_offset "32" // The offset of the nav drag volume top from center
nav_drag_selection_volume_zmin_offset "32" // The offset of the nav drag volume bottom from center
nav_draw_limit "500" // The maximum number of areas to draw in edit mode
nav_dump_selected_set_positions // z) coordinates of the centers of all selected nav areas to a file.
nav_edit "0" // Set to one to interactively edit the Navigation Mesh. Set to zero to leave edit mode.
nav_end_area // Defines the second corner of a new Area or Ladder and creates it.
nav_end_deselecting // Stop continuously removing from the selected set.
nav_end_drag_deselecting // Stop dragging a selection area.
nav_end_drag_selecting // Stop dragging a selection area.
nav_end_selecting // Stop continuously adding to the selected set.
nav_end_shift_xy // Finish shifting the Selected Set.
nav_flood_select // use this command again.
nav_generate // Generate a Navigation Mesh for the current map and save it to disk.
nav_generate_fencetops "1" // Autogenerate nav areas on fence and obstacle tops
nav_generate_fixup_jump_areas "1" // Convert obsolete jump areas into 2-way connections
nav_generate_incremental // Generate a Navigation Mesh for the current map and save it to disk.
nav_generate_incremental_range "2000"
nav_generate_incremental_tolerance "0" // Z tolerance for adding new nav areas.
nav_gen_cliffs_approx // post-processing approximation
nav_jump // Toggles the traverse this area by jumping flag used by the AI system.
nav_ladder_flip // Flips the selected ladders direction.
nav_load // Loads the Navigation Mesh for the current map.
nav_lower_drag_volume_max // Lower the top of the drag select volume.
nav_lower_drag_volume_min // Lower the bottom of the drag select volume.
nav_make_sniper_spots // Chops the marked area into disconnected sub-areas suitable for sniper spots.
nav_mark // Marks the Area or Ladder under the cursor for manipulation by subsequent editing commands.
nav_mark_attribute // Set nav attribute for all areas in the selected set.
nav_mark_unnamed // Mark an Area with no Place name. Useful for finding stray areas missed when Place Painting.
nav_mark_walkable // Mark the current location as a walkable position. These positions are used as seed locations when sampling the map to generate
nav_max_view_distance "6000" // Maximum range for precomputed nav mesh visibility (0 = default 1500 units)
nav_max_vis_delta_list_length "64"
nav_merge // and invoke the merge comm
nav_merge_mesh // Merges a saved selected set into the current mesh.
nav_no_hostages // Toggles the hostages cannot use this area flag used by the AI system.
nav_no_jump // Toggles the dont jump in this area flag used by the AI system.
nav_place_floodfill // and flood-fills the Place to all adjacent Areas. Flood-filli
nav_place_list // Lists all place names used in the map.
nav_place_pick // Sets the current Place to the Place of the Area under the cursor.
nav_place_replace // Replaces all instances of the first place with the second place.
nav_place_set // Sets the Place of all selected areas to the current Place.
nav_potentially_visible_dot_tolerance "0"
nav_precise // Toggles the dont avoid obstacles flag used by the AI system.
nav_quicksave "1" // Set to one to skip the time consuming phases of the analysis. Useful for data collection and testing.
nav_raise_drag_volume_max // Raise the top of the drag select volume.
nav_raise_drag_volume_min // Raise the bottom of the drag select volume.
nav_recall_selected_set // Re-selects the stored selected set.
nav_remove_from_selected_set // Remove current area from the selected set.
nav_remove_jump_areas // replacing them with connections.
nav_run // Toggles the traverse this area by running flag used by the AI system.
nav_save // Saves the current Navigation Mesh to disk.
nav_save_selected // Writes the selected set to disk for merging into another mesh via nav_merge_mesh.
nav_selected_set_border_color "100" // Color used to draw the selected set borders while editing.
nav_selected_set_color "255" // Color used to draw the selected set background while editing.
nav_select_blocked_areas // Adds all blocked areas to the selected set
nav_select_damaging_areas // Adds all damaging areas to the selected set
nav_select_half_space // Selects any areas that intersect the given half-space.
nav_select_invalid_areas // Adds all invalid areas to the Selected Set.
nav_select_larger_than // Select nav areas where both dimensions are larger than the given size.
nav_select_obstructed_areas // Adds all obstructed areas to the selected set
nav_select_orphans // Adds all orphan areas to the selected set (highlight a valid area first).
nav_select_overlapping // Selects nav areas that are overlapping others.
nav_select_radius // Adds all areas in a radius to the selection set
nav_select_stairs // Adds all stairway areas to the selected set
nav_set_place_mode // Sets the editor into or out of Place mode. Place mode allows labelling of Area with Place names.
nav_shift // Shifts the selected areas by the specified amount
nav_show_approach_points "0" // Show Approach Points in the Navigation Mesh.
nav_show_area_info "0" // Duration in seconds to show nav area ID and attributes while editing
```
