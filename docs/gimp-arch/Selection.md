## Table of Contents
- [Class: Selection](#class-selection)
  - [🔹 Public Methods](#-public-methods)
  - [🔒 Private Methods](#-private-methods)
  - [⚙️ Dunder Methods](#️-dunder-methods)
  - [🏷️ Properties](#-properties)
  - [📣 Signals](#-signals)

### Class: Selection
**Module**: gi.repository.Gimp  
**Base Class**: Channel<br><br>
**Inheritance Tree**:
- `gi.repository.Gimp.Selection` *(GI-wrapped ,GObject.Object)*
  - `gi.repository.Gimp.Channel` *(GI-wrapped ,GObject.Object)*
    - `gi.repository.Gimp.Drawable` *(GI-wrapped ,GObject.Object)*
      - `gi.repository.Gimp.Item` *(GI-wrapped ,GObject.Object)*
        - `gi.overrides.GObject.Object` *(GI-wrapped ,GObject.Object)*
          - `gi.repository.GObject.Object` *(GI-wrapped)*
            - `gi._gi.GObject`
              - `builtins.object` *(Builtin)*
<br>
#### 🔹 Public Methods
**all**  
`(image: BOXED)`<br>
**append_filter**  
`(filter: BOXED)`<br>
**attach_parasite**  
`(parasite: BOXED)`<br>
⚠️ **bind_property**
_Unable to extract signature — no signature found for builtin <method 'bind_property' of 'gi._gi.GObject' objects>_<br>
**bind_property_full**  
`(self, *args, **kargs)`<br>
**border**  
`(image: BOXED, radius: INT32)`<br>
**bounds**  
`(image: BOXED, non_empty: BOOLEAN, x1: INT32, y1: INT32, x2: INT32, y2: INT32)`<br>
**brightness_contrast**  
`(brightness: DOUBLE, contrast: DOUBLE)`<br>
⚠️ **chain**
_Unable to extract signature — no signature found for builtin <method 'chain' of 'gi._gi.GObject' objects>_<br>
**color_balance**  
`(transfer_mode: BOXED, preserve_lum: BOOLEAN, cyan_red: DOUBLE, magenta_green: DOUBLE, yellow_blue: DOUBLE)`<br>
**colorize_hsl**  
`(hue: DOUBLE, saturation: DOUBLE, lightness: DOUBLE)`<br>
**combine_masks**  
`(channel2: BOXED, operation: BOXED, offx: INT32, offy: INT32)`<br>
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
**copy**  
`()`<br>
**curves_explicit**  
`(channel: BOXED, num_values: UINT64, values: FLAGS)`<br>
**curves_spline**  
`(channel: BOXED, num_points: UINT64, points: FLAGS)`<br>
**delete**  
`()`<br>
**desaturate**  
`(desaturate_mode: BOXED)`<br>
**detach_parasite**  
`(name: STRING)`<br>
⚠️ **disconnect**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_disconnect) is not supported by signature_<br>
⚠️ **disconnect_by_func**
_Unable to extract signature — no signature found for builtin <method 'disconnect_by_func' of 'gi._gi.GObject' objects>_<br>
##### 🔧 edit_* Methods
**edit_bucket_fill**  
`(fill_type: BOXED, x: DOUBLE, y: DOUBLE)`<br>
**edit_clear**  
`()`<br>
**edit_fill**  
`(fill_type: BOXED)`<br>
**edit_gradient_fill**  
`(gradient_type: BOXED, offset: DOUBLE, supersample: BOOLEAN, supersample_max_depth: INT32, supersample_threshold: DOUBLE, dither: BOOLEAN, x1: DOUBLE, y1: DOUBLE, x2: DOUBLE, y2: DOUBLE)`<br>
**edit_stroke_item**  
`(item: BOXED)`<br>
**edit_stroke_selection**  
`()`<br>
⚠️ **emit**
_Unable to extract signature — no signature found for builtin <method 'emit' of 'gi._gi.GObject' objects>_<br>
**emit_stop_by_name**  
`(self, detailed_signal)`<br>
**equalize**  
`(mask_only: BOOLEAN)`<br>
**extract_component**  
`(component: INT32, invert: BOOLEAN, linear: BOOLEAN)`<br>
**feather**  
`(image: BOXED, radius: DOUBLE)`<br>
**fill**  
`(fill_type: BOXED)`<br>
**find_property**  
`(property_name: STRING)`<br>
**float**  
`(image: BOXED, drawables: FLAGS, offx: INT32, offy: INT32)`<br>
**flood**  
`(image: BOXED)`<br>
**force_floating**  
`(self, *args, **kargs)`<br>
**foreground_extract**  
`(mode: BOXED, mask: BOXED)`<br>
**free_shadow**  
`()`<br>
**freeze_notify**  
`(self)`<br>
##### 🔧 get_* Methods
**get_bpp**  
`()`<br>
**get_buffer**  
`()`<br>
**get_by_id**  
`(selection_id: INT32)`<br>
**get_children**  
`()`<br>
**get_color**  
`()`<br>
**get_color_tag**  
`()`<br>
**get_data**  
`(self, *args, **kargs)`<br>
**get_expanded**  
`()`<br>
**get_filters**  
`()`<br>
**get_format**  
`()`<br>
**get_height**  
`()`<br>
**get_id**  
`()`<br>
**get_image**  
`()`<br>
**get_lock_content**  
`()`<br>
**get_lock_position**  
`()`<br>
**get_lock_visibility**  
`()`<br>
**get_name**  
`()`<br>
**get_offsets**  
`(offset_x: INT32, offset_y: INT32)`<br>
**get_opacity**  
`()`<br>
**get_parasite**  
`(name: STRING)`<br>
**get_parasite_list**  
`()`<br>
**get_parent**  
`()`<br>
**get_pixel**  
`(x_coord: INT32, y_coord: INT32)`<br>
⚠️ **get_properties**
_Unable to extract signature — no signature found for builtin <method 'get_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **get_property**
_Unable to extract signature — no signature found for builtin <method 'get_property' of 'gi._gi.GObject' objects>_<br>
**get_qdata**  
`(self, *args, **kargs)`<br>
**get_shadow_buffer**  
`()`<br>
**get_show_masked**  
`()`<br>
**get_sub_thumbnail**  
`(src_x: INT32, src_y: INT32, src_width: INT32, src_height: INT32, dest_width: INT32, dest_height: INT32, alpha: BOXED)`<br>
**get_sub_thumbnail_data**  
`(src_x: INT32, src_y: INT32, src_width: INT32, src_height: INT32, dest_width: INT32, dest_height: INT32, actual_width: INT32, actual_height: INT32, bpp: INT32)`<br>
**get_tattoo**  
`()`<br>
**get_thumbnail**  
`(width: INT32, height: INT32, alpha: BOXED)`<br>
**get_thumbnail_data**  
`(width: INT32, height: INT32, actual_width: INT32, actual_height: INT32, bpp: INT32)`<br>
**get_thumbnail_format**  
`()`<br>
**get_visible**  
`()`<br>
**get_width**  
`()`<br>
**getv**  
`(n_properties: UINT32, names: FLAGS, values: FLAGS)`<br>
**grow**  
`(image: BOXED, steps: INT32)`<br>
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
**has_alpha**  
`()`<br>
**histogram**  
`(channel: BOXED, start_range: DOUBLE, end_range: DOUBLE, mean: DOUBLE, std_dev: DOUBLE, median: DOUBLE, pixels: DOUBLE, count: DOUBLE, percentile: DOUBLE)`<br>
**hue_saturation**  
`(hue_range: BOXED, hue_offset: DOUBLE, lightness: DOUBLE, saturation: DOUBLE, overlap: DOUBLE)`<br>
##### 🔧 id_* Methods
**id_is_channel**  
`(item_id: INT32)`<br>
**id_is_drawable**  
`(item_id: INT32)`<br>
**id_is_group_layer**  
`(item_id: INT32)`<br>
**id_is_layer**  
`(item_id: INT32)`<br>
**id_is_layer_mask**  
`(item_id: INT32)`<br>
**id_is_path**  
`(item_id: INT32)`<br>
**id_is_selection**  
`(item_id: INT32)`<br>
**id_is_text_layer**  
`(item_id: INT32)`<br>
**id_is_valid**  
`(item_id: INT32)`<br>
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
**invert**  
`(image: BOXED)`<br>
##### 🔧 is_* Methods
**is_channel**  
`()`<br>
**is_drawable**  
`()`<br>
**is_empty**  
`(image: BOXED)`<br>
**is_floating**  
`()`<br>
**is_gray**  
`()`<br>
**is_group**  
`()`<br>
**is_group_layer**  
`()`<br>
**is_indexed**  
`()`<br>
**is_layer**  
`()`<br>
**is_layer_mask**  
`()`<br>
**is_path**  
`()`<br>
**is_rgb**  
`()`<br>
**is_selection**  
`()`<br>
**is_text_layer**  
`()`<br>
**is_valid**  
`()`<br>
**levels**  
`(channel: BOXED, low_input: DOUBLE, high_input: DOUBLE, clamp_input: BOOLEAN, gamma: DOUBLE, low_output: DOUBLE, high_output: DOUBLE, clamp_output: BOOLEAN)`<br>
**levels_stretch**  
`()`<br>
**list_properties**  
`(n_properties: UINT32)`<br>
**mask_bounds**  
`(x1: INT32, y1: INT32, x2: INT32, y2: INT32)`<br>
**mask_intersect**  
`(x: INT32, y: INT32, width: INT32, height: INT32)`<br>
##### 🔧 merge_* Methods
**merge_filter**  
`(filter: BOXED)`<br>
**merge_filters**  
`()`<br>
**merge_shadow**  
`(undo: BOOLEAN)`<br>
**new**  
`(image: BOXED, name: STRING, width: INT32, height: INT32, opacity: DOUBLE, color: BOXED)`<br>
**new_from_component**  
`(image: BOXED, component: BOXED, name: STRING)`<br>
**newv**  
`(object_type: GTYPE, n_parameters: UINT32, parameters: FLAGS)`<br>
**none**  
`(image: BOXED)`<br>
**notify**  
`(property_name: STRING)`<br>
**notify_by_pspec**  
`(self, *args, **kargs)`<br>
**offset**  
`(wrap_around: BOOLEAN, fill_type: BOXED, color: BOXED, offset_x: INT32, offset_y: INT32)`<br>
**override_property**  
`(property_id: UINT32, name: STRING)`<br>
**posterize**  
`(levels: INT32)`<br>
**ref**  
`(self, *args, **kargs)`<br>
**ref_sink**  
`(self, *args, **kargs)`<br>
**replace_data**  
`(self, *args, **kargs)`<br>
**replace_qdata**  
`(self, *args, **kargs)`<br>
**run_dispose**  
`()`<br>
**save**  
`(image: BOXED)`<br>
##### 🔧 set_* Methods
**set_color**  
`(color: BOXED)`<br>
**set_color_tag**  
`(color_tag: BOXED)`<br>
**set_data**  
`(self, *args, **kargs)`<br>
**set_expanded**  
`(expanded: BOOLEAN)`<br>
**set_lock_content**  
`(lock_content: BOOLEAN)`<br>
**set_lock_position**  
`(lock_position: BOOLEAN)`<br>
**set_lock_visibility**  
`(lock_visibility: BOOLEAN)`<br>
**set_name**  
`(name: STRING)`<br>
**set_opacity**  
`(opacity: DOUBLE)`<br>
**set_pixel**  
`(x_coord: INT32, y_coord: INT32, color: BOXED)`<br>
⚠️ **set_properties**
_Unable to extract signature — no signature found for builtin <method 'set_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **set_property**
_Unable to extract signature — no signature found for builtin <method 'set_property' of 'gi._gi.GObject' objects>_<br>
**set_show_masked**  
`(show_masked: BOOLEAN)`<br>
**set_tattoo**  
`(tattoo: UINT32)`<br>
**set_visible**  
`(visible: BOOLEAN)`<br>
**shadows_highlights**  
`(shadows: DOUBLE, highlights: DOUBLE, whitepoint: DOUBLE, radius: DOUBLE, compress: DOUBLE, shadows_ccorrect: DOUBLE, highlights_ccorrect: DOUBLE)`<br>
**sharpen**  
`(image: BOXED)`<br>
**shrink**  
`(image: BOXED, steps: INT32)`<br>
**steal_data**  
`(self, *args, **kargs)`<br>
**steal_qdata**  
`(self, *args, **kargs)`<br>
**stop_emission**  
`(self, detailed_signal)`<br>
⚠️ **stop_emission_by_name**
_Unable to extract signature — callable gi.FunctionInfo(signal_stop_emission_by_name) is not supported by signature_<br>
**thaw_notify**  
`()`<br>
**threshold**  
`(channel: BOXED, low_threshold: DOUBLE, high_threshold: DOUBLE)`<br>
##### 🔧 transform_* Methods
**transform_2d**  
`(source_x: DOUBLE, source_y: DOUBLE, scale_x: DOUBLE, scale_y: DOUBLE, angle: DOUBLE, dest_x: DOUBLE, dest_y: DOUBLE)`<br>
**transform_flip**  
`(x0: DOUBLE, y0: DOUBLE, x1: DOUBLE, y1: DOUBLE)`<br>
**transform_flip_simple**  
`(flip_type: BOXED, auto_center: BOOLEAN, axis: DOUBLE)`<br>
**transform_matrix**  
`(coeff_0_0: DOUBLE, coeff_0_1: DOUBLE, coeff_0_2: DOUBLE, coeff_1_0: DOUBLE, coeff_1_1: DOUBLE, coeff_1_2: DOUBLE, coeff_2_0: DOUBLE, coeff_2_1: DOUBLE, coeff_2_2: DOUBLE)`<br>
**transform_perspective**  
`(x0: DOUBLE, y0: DOUBLE, x1: DOUBLE, y1: DOUBLE, x2: DOUBLE, y2: DOUBLE, x3: DOUBLE, y3: DOUBLE)`<br>
**transform_rotate**  
`(angle: DOUBLE, auto_center: BOOLEAN, center_x: DOUBLE, center_y: DOUBLE)`<br>
**transform_rotate_simple**  
`(rotate_type: BOXED, auto_center: BOOLEAN, center_x: DOUBLE, center_y: DOUBLE)`<br>
**transform_scale**  
`(x0: DOUBLE, y0: DOUBLE, x1: DOUBLE, y1: DOUBLE)`<br>
**transform_shear**  
`(shear_type: BOXED, magnitude: DOUBLE)`<br>
**transform_translate**  
`(off_x: DOUBLE, off_y: DOUBLE)`<br>
**translate**  
`(image: BOXED, offx: INT32, offy: INT32)`<br>
**type**  
`()`<br>
**type_with_alpha**  
`()`<br>
**unref**  
`(self, *args, **kargs)`<br>
**update**  
`(x: INT32, y: INT32, width: INT32, height: INT32)`<br>
**value**  
`(image: BOXED, x: INT32, y: INT32)`<br>
**watch_closure**  
`(self, *args, **kargs)`<br>
⚠️ **weak_ref**
_Unable to extract signature — no signature found for builtin <method 'weak_ref' of 'gi._gi.GObject' objects>_<br>
<br>
#### 🏷️ Properties
- **id**: `gint` (read/write)
<br>
#### 📣 Signals
<br>