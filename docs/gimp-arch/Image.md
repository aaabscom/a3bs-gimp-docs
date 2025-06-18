---
title: "Image Class Documentation"
date: 2025-06-17
layout: default
---

## Table of Contents
- [Class: Image](#class-image)
  - [🔹 Public Methods](#-public-methods)
    - [🔧 add_* Methods](#add_-methods)
  - [🔒 Private Methods](#-private-methods)
  - [⚙️ Dunder Methods](#️-dunder-methods)
  - [🏷️ Properties](#-properties)
  - [📣 Signals](#-signals)

## Class: Image
- **Module**: gi.repository.Gimp  
- **Base Class**: Object<br><br>
- **Inheritance Tree**:
  - `gi.repository.Gimp.Image` *(GI-wrapped ,GObject.Object)*
    - `gi.overrides.GObject.Object` *(GI-wrapped ,GObject.Object)*
      - `gi.repository.GObject.Object` *(GI-wrapped)*
        - `gi._gi.GObject`
          - `builtins.object` *(Builtin)*

<a name="public-methods"></a>
### 🔧 Public Methods

<a name="add_-methods"></a>
#### 🔧 add_* Methods
*add_hguide* `(yposition: INT32)`<br>
*add_sample_point* `(position_x: INT32, position_y: INT32)`<br>

**add_vguide**  
`(xposition: INT32)`<br>
**attach_parasite**  
`(parasite: BOXED)`<br>
**autocrop**  
`(drawable: BOXED)`<br>
**autocrop_selected_layers**  
`(drawable: BOXED)`<br>
⚠️ **bind_property**
_Unable to extract signature — no signature found for builtin <method 'bind_property' of 'gi._gi.GObject' objects>_<br>
**bind_property_full**  
`(self, *args, **kargs)`<br>
⚠️ **chain**
_Unable to extract signature — no signature found for builtin <method 'chain' of 'gi._gi.GObject' objects>_<br>
**clean_all**  
`()`<br>
**compat_control**  
`(self, *args, **kargs)`<br>

##### 🔧 connect_* Methods
⚠️ **connect**
_Unable to extract signature — no signature found for builtin <method 'connect' of 'gi._gi.GObject' objects>_<br>
⚠️ **connect_after**
_Unable to extract signature — no signature found for builtin <method 'connect_after' of 'gi._gi.GObject' objects>_<br>
**connect_data**  
`(self, detailed_signal, handler, *data, **kwargs)`<br>
⚠️ **connect_object**
_Unable to extract signature — no signature found for builtin <method 'connect_object' of 'gi._gi.GObject' objects>_<br>
⚠️ **connect_object_after**
_Unable to extract signature — no signature found for builtin <method 'connect_object_after' of 'gi._gi.GObject' objects>_<br>

##### 🔧 convert_* Methods
**convert_color_profile**  
`(profile: BOXED, intent: BOXED, bpc: BOOLEAN)`<br>
**convert_color_profile_from_file**  
`(file: BOXED, intent: BOXED, bpc: BOOLEAN)`<br>
**convert_grayscale**  
`()`<br>
**convert_indexed**  
`(dither_type: BOXED, palette_type: BOXED, num_cols: INT32, alpha_dither: BOOLEAN, remove_unused: BOOLEAN, palette: STRING)`<br>
**convert_precision**  
`(precision: BOXED)`<br>
**convert_rgb**  
`()`<br>
**convert_set_dither_matrix**  
`(width: INT32, height: INT32, matrix: BOXED)`<br>
**crop**  
`(new_width: INT32, new_height: INT32, offx: INT32, offy: INT32)`<br>

##### 🔧 delete_* Methods
**delete**  
`()`<br>
**delete_guide**  
`(guide: UINT32)`<br>
**delete_sample_point**  
`(sample_point: UINT32)`<br>
**detach_parasite**  
`(name: STRING)`<br>
⚠️ **disconnect**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_disconnect) is not supported by signature_<br>
⚠️ **disconnect_by_func**
_Unable to extract signature — no signature found for builtin <method 'disconnect_by_func' of 'gi._gi.GObject' objects>_<br>
**duplicate**  
`()`<br>
⚠️ **emit**
_Unable to extract signature — no signature found for builtin <method 'emit' of 'gi._gi.GObject' objects>_<br>
**emit_stop_by_name**  
`(self, detailed_signal)`<br>
**export_path_to_file**  
`(file: BOXED, path: BOXED)`<br>
**export_path_to_string**  
`(path: BOXED)`<br>

##### 🔧 find_* Methods
**find_next_guide**  
`(guide: INT32)`<br>
**find_next_sample_point**  
`(sample_point: UINT32)`<br>
**find_property**  
`(property_name: STRING)`<br>
**flatten**  
`()`<br>
**flip**  
`(flip_type: BOXED)`<br>
**floating_sel_attached_to**  
`()`<br>
**force_floating**  
`(self, *args, **kargs)`<br>

##### 🔧 freeze_* Methods
**freeze_channels**  
`()`<br>
**freeze_layers**  
`()`<br>
**freeze_notify**  
`(self)`<br>
**freeze_paths**  
`()`<br>

##### 🔧 get_* Methods
**get_base_type**  
`()`<br>
**get_by_id**  
`(image_id: INT32)`<br>
**get_channel_by_name**  
`(name: STRING)`<br>
**get_channel_by_tattoo**  
`(tattoo: UINT32)`<br>
**get_channels**  
`()`<br>
**get_color_profile**  
`()`<br>
**get_component_active**  
`(component: BOXED)`<br>
**get_component_visible**  
`(component: BOXED)`<br>
**get_data**  
`(self, *args, **kargs)`<br>
**get_default_new_layer_mode**  
`()`<br>
**get_effective_color_profile**  
`()`<br>
**get_exported_file**  
`()`<br>
**get_file**  
`()`<br>
**get_floating_sel**  
`()`<br>
**get_guide_orientation**  
`(guide: UINT32)`<br>
**get_guide_position**  
`(guide: UINT32)`<br>
**get_height**  
`()`<br>
**get_id**  
`()`<br>
**get_imported_file**  
`()`<br>
**get_item_position**  
`(item: BOXED)`<br>
**get_layer_by_name**  
`(name: STRING)`<br>
**get_layer_by_tattoo**  
`(tattoo: UINT32)`<br>
**get_layers**  
`()`<br>
**get_metadata**  
`()`<br>
**get_name**  
`()`<br>
**get_palette**  
`()`<br>
**get_parasite**  
`(name: STRING)`<br>
**get_parasite_list**  
`()`<br>
**get_path_by_name**  
`(name: STRING)`<br>
**get_path_by_tattoo**  
`(tattoo: UINT32)`<br>
**get_paths**  
`()`<br>
**get_precision**  
`()`<br>
⚠️ **get_properties**
_Unable to extract signature — no signature found for builtin <method 'get_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **get_property**
_Unable to extract signature — no signature found for builtin <method 'get_property' of 'gi._gi.GObject' objects>_<br>
**get_qdata**  
`(self, *args, **kargs)`<br>
**get_resolution**  
`(xresolution: DOUBLE, yresolution: DOUBLE)`<br>
**get_sample_point_position**  
`(sample_point: UINT32, position_y: INT32)`<br>
**get_selected_channels**  
`()`<br>
**get_selected_drawables**  
`()`<br>
**get_selected_layers**  
`()`<br>
**get_selected_paths**  
`()`<br>
**get_selection**  
`()`<br>
**get_simulation_bpc**  
`()`<br>
**get_simulation_intent**  
`()`<br>
**get_simulation_profile**  
`()`<br>
**get_tattoo_state**  
`()`<br>
**get_thumbnail**  
`(width: INT32, height: INT32, alpha: BOXED)`<br>
**get_thumbnail_data**  
`(width: INT32, height: INT32, bpp: INT32)`<br>
**get_unit**  
`()`<br>
**get_width**  
`()`<br>
**get_xcf_file**  
`()`<br>
**getv**  
`(n_properties: UINT32, names: FLAGS, values: FLAGS)`<br>

##### 🔧 grid_* Methods
**grid_get_background_color**  
`()`<br>
**grid_get_foreground_color**  
`()`<br>
**grid_get_offset**  
`(xoffset: DOUBLE, yoffset: DOUBLE)`<br>
**grid_get_spacing**  
`(xspacing: DOUBLE, yspacing: DOUBLE)`<br>
**grid_get_style**  
`()`<br>
**grid_set_background_color**  
`(bgcolor: BOXED)`<br>
**grid_set_foreground_color**  
`(fgcolor: BOXED)`<br>
**grid_set_offset**  
`(xoffset: DOUBLE, yoffset: DOUBLE)`<br>
**grid_set_spacing**  
`(xspacing: DOUBLE, yspacing: DOUBLE)`<br>
**grid_set_style**  
`(style: BOXED)`<br>

##### 🔧 handler_* Methods
**handler_block**  
`(obj, handler_id)`<br>
⚠️ **handler_block_by_func**
_Unable to extract signature — no signature found for builtin <method 'handler_block_by_func' of 'gi._gi.GObject' objects>_<br>
⚠️ **handler_disconnect**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_disconnect) is not supported by signature_<br>
⚠️ **handler_is_connected**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_is_connected) is not supported by signature_<br>
⚠️ **handler_unblock**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_unblock) is not supported by signature_<br>
⚠️ **handler_unblock_by_func**
_Unable to extract signature — no signature found for builtin <method 'handler_unblock_by_func' of 'gi._gi.GObject' objects>_<br>
**id_is_valid**  
`(image_id: INT32)`<br>
**import_paths_from_file**  
`(file: BOXED, merge: BOOLEAN, scale: BOOLEAN, paths: FLAGS)`<br>
**import_paths_from_string**  
`(string: STRING, length: INT32, merge: BOOLEAN, scale: BOOLEAN, paths: FLAGS)`<br>

##### 🔧 insert_* Methods
**insert_channel**  
`(channel: BOXED, parent: BOXED, position: INT32)`<br>
**insert_layer**  
`(layer: BOXED, parent: BOXED, position: INT32)`<br>
**insert_path**  
`(path: BOXED, parent: BOXED, position: INT32)`<br>
**install_properties**  
`(n_pspecs: UINT32, pspecs: FLAGS)`<br>
**install_property**  
`(property_id: UINT32, pspec: BOXED)`<br>

##### 🔧 interface_* Methods
**interface_find_property**  
`(self, *args, **kargs)`<br>
**interface_install_property**  
`(self, *args, **kargs)`<br>
**interface_list_properties**  
`(self, *args, **kargs)`<br>

##### 🔧 is_* Methods
**is_dirty**  
`()`<br>
**is_floating**  
`()`<br>
**is_valid**  
`()`<br>
**list_properties**  
`(n_properties: UINT32)`<br>
**lower_item**  
`(item: BOXED)`<br>
**lower_item_to_bottom**  
`(item: BOXED)`<br>
**merge_down**  
`(merge_layer: BOXED, merge_type: BOXED)`<br>
**merge_visible_layers**  
`(merge_type: BOXED)`<br>

##### 🔧 metadata_* Methods
**metadata_load_thumbnail**  
`(file: BOXED)`<br>
**metadata_save_filter**  
`(mime_type: STRING, metadata: BOXED, flags: BOXED, file: BOXED)`<br>
**metadata_save_prepare**  
`(mime_type: STRING, suggested_flags: BOXED)`<br>
**new**  
`(width: INT32, height: INT32, type: BOXED)`<br>
**new_with_precision**  
`(width: INT32, height: INT32, type: BOXED, precision: BOXED)`<br>
**newv**  
`(object_type: GTYPE, n_parameters: UINT32, parameters: FLAGS)`<br>
**notify**  
`(property_name: STRING)`<br>
**notify_by_pspec**  
`(self, *args, **kargs)`<br>
**override_property**  
`(property_id: UINT32, name: STRING)`<br>
**pick_color**  
`(drawables: FLAGS, x: DOUBLE, y: DOUBLE, sample_merged: BOOLEAN, sample_average: BOOLEAN, average_radius: DOUBLE, color: BOXED)`<br>
**pick_correlate_layer**  
`(x: INT32, y: INT32)`<br>
**policy_color_profile**  
`(interactive: BOOLEAN)`<br>
**policy_rotate**  
`(interactive: BOOLEAN)`<br>
**raise_item**  
`(item: BOXED)`<br>
**raise_item_to_top**  
`(item: BOXED)`<br>
**ref**  
`(self, *args, **kargs)`<br>
**ref_sink**  
`(self, *args, **kargs)`<br>

##### 🔧 remove_* Methods
**remove_channel**  
`(channel: BOXED)`<br>
**remove_layer**  
`(layer: BOXED)`<br>
**remove_path**  
`(path: BOXED)`<br>
**reorder_item**  
`(item: BOXED, parent: BOXED, position: INT32)`<br>
**replace_data**  
`(self, *args, **kargs)`<br>
**replace_qdata**  
`(self, *args, **kargs)`<br>
**resize**  
`(new_width: INT32, new_height: INT32, offx: INT32, offy: INT32)`<br>
**resize_to_layers**  
`()`<br>
**rotate**  
`(rotate_type: BOXED)`<br>
**run_dispose**  
`()`<br>
**scale**  
`(new_width: INT32, new_height: INT32)`<br>

##### 🔧 select_* Methods
**select_color**  
`(operation: BOXED, drawable: BOXED, color: BOXED)`<br>
**select_contiguous_color**  
`(operation: BOXED, drawable: BOXED, x: DOUBLE, y: DOUBLE)`<br>
**select_ellipse**  
`(operation: BOXED, x: DOUBLE, y: DOUBLE, width: DOUBLE, height: DOUBLE)`<br>
**select_item**  
`(operation: BOXED, item: BOXED)`<br>
**select_polygon**  
`(operation: BOXED, num_segs: UINT64, segs: FLAGS)`<br>
**select_rectangle**  
`(operation: BOXED, x: DOUBLE, y: DOUBLE, width: DOUBLE, height: DOUBLE)`<br>
**select_round_rectangle**  
`(operation: BOXED, x: DOUBLE, y: DOUBLE, width: DOUBLE, height: DOUBLE, corner_radius_x: DOUBLE, corner_radius_y: DOUBLE)`<br>

##### 🔧 set_* Methods
**set_color_profile**  
`(profile: BOXED)`<br>
**set_color_profile_from_file**  
`(file: BOXED)`<br>
**set_component_active**  
`(component: BOXED, active: BOOLEAN)`<br>
**set_component_visible**  
`(component: BOXED, visible: BOOLEAN)`<br>
**set_data**  
`(self, *args, **kargs)`<br>
**set_file**  
`(file: BOXED)`<br>
**set_metadata**  
`(metadata: BOXED)`<br>
**set_palette**  
`(new_palette: BOXED)`<br>
⚠️ **set_properties**
_Unable to extract signature — no signature found for builtin <method 'set_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **set_property**
_Unable to extract signature — no signature found for builtin <method 'set_property' of 'gi._gi.GObject' objects>_<br>
**set_resolution**  
`(xresolution: DOUBLE, yresolution: DOUBLE)`<br>
**set_selected_channels**  
`(channels: FLAGS)`<br>
**set_selected_layers**  
`(layers: FLAGS)`<br>
**set_selected_paths**  
`(paths: FLAGS)`<br>
**set_simulation_bpc**  
`(bpc: BOOLEAN)`<br>
**set_simulation_intent**  
`(intent: BOXED)`<br>
**set_simulation_profile**  
`(profile: BOXED)`<br>
**set_simulation_profile_from_file**  
`(file: BOXED)`<br>
**set_tattoo_state**  
`(tattoo_state: UINT32)`<br>
**set_unit**  
`(unit: BOXED)`<br>
**steal_data**  
`(self, *args, **kargs)`<br>
**steal_qdata**  
`(self, *args, **kargs)`<br>
**stop_emission**  
`(self, detailed_signal)`<br>
⚠️ **stop_emission_by_name**
_Unable to extract signature — callable gi.FunctionInfo(signal_stop_emission_by_name) is not supported by signature_<br>

##### 🔧 take_* Methods
**take_selected_channels**  
`(channels: PARAM)`<br>
**take_selected_layers**  
`(layers: PARAM)`<br>
**take_selected_paths**  
`(paths: PARAM)`<br>

##### 🔧 thaw_* Methods
**thaw_channels**  
`()`<br>
**thaw_layers**  
`()`<br>
**thaw_notify**  
`()`<br>
**thaw_paths**  
`()`<br>

##### 🔧 undo_* Methods
**undo_disable**  
`()`<br>
**undo_enable**  
`()`<br>
**undo_freeze**  
`()`<br>
**undo_group_end**  
`()`<br>
**undo_group_start**  
`()`<br>
**undo_is_enabled**  
`()`<br>
**undo_thaw**  
`()`<br>
**unref**  
`(self, *args, **kargs)`<br>
**unset_active_channel**  
`()`<br>
**watch_closure**  
`(self, *args, **kargs)`<br>
⚠️ **weak_ref**
_Unable to extract signature — no signature found for builtin <method 'weak_ref' of 'gi._gi.GObject' objects>_<br>
<br>

<a name="properties"></a>
### ⚙️ Properties

<span style="font-size:0.9em;">🏷️ Class properties</span>
- **id**: `gint` (read/write)
<br>

#### Signals
<span style="font-size:0.9em;">📣 Signal events</span>
<br>
