## Table of Contents
- [Class: Path](#class-path)
  - [🔹 Public Methods](#-public-methods)
  - [🔒 Private Methods](#-private-methods)
  - [⚙️ Dunder Methods](#️-dunder-methods)
  - [🏷️ Properties](#-properties)
  - [📣 Signals](#-signals)

### Class: Path
**Module**: gi.repository.Gimp  
**Base Class**: Item<br><br>
**Inheritance Tree**:
- `gi.repository.Gimp.Path` *(GI-wrapped ,GObject.Object)*
  - `gi.repository.Gimp.Item` *(GI-wrapped ,GObject.Object)*
    - `gi.overrides.GObject.Object` *(GI-wrapped ,GObject.Object)*
      - `gi.repository.GObject.Object` *(GI-wrapped)*
        - `gi._gi.GObject`
          - `builtins.object` *(Builtin)*
<br>


<a name="public-methods"></a>
#### 🔹 Public Methods


**attach_parasite**  
`(parasite: BOXED)`<br>
##### 🔧 bezier_* Methods
**bezier_stroke_conicto**  
`(stroke_id: INT32, x0: DOUBLE, y0: DOUBLE, x1: DOUBLE, y1: DOUBLE)`<br>
**bezier_stroke_cubicto**  
`(stroke_id: INT32, x0: DOUBLE, y0: DOUBLE, x1: DOUBLE, y1: DOUBLE, x2: DOUBLE, y2: DOUBLE)`<br>
**bezier_stroke_lineto**  
`(stroke_id: INT32, x0: DOUBLE, y0: DOUBLE)`<br>
**bezier_stroke_new_ellipse**  
`(x0: DOUBLE, y0: DOUBLE, radius_x: DOUBLE, radius_y: DOUBLE, angle: DOUBLE)`<br>
**bezier_stroke_new_moveto**  
`(x0: DOUBLE, y0: DOUBLE)`<br>
⚠️ **bind_property**
_Unable to extract signature — no signature found for builtin <method 'bind_property' of 'gi._gi.GObject' objects>_<br>
**bind_property_full**  
`(self, *args, **kargs)`<br>
⚠️ **chain**
_Unable to extract signature — no signature found for builtin <method 'chain' of 'gi._gi.GObject' objects>_<br>
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
**delete**  
`()`<br>
**detach_parasite**  
`(name: STRING)`<br>
⚠️ **disconnect**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_disconnect) is not supported by signature_<br>
⚠️ **disconnect_by_func**
_Unable to extract signature — no signature found for builtin <method 'disconnect_by_func' of 'gi._gi.GObject' objects>_<br>
⚠️ **emit**
_Unable to extract signature — no signature found for builtin <method 'emit' of 'gi._gi.GObject' objects>_<br>
**emit_stop_by_name**  
`(self, detailed_signal)`<br>
**find_property**  
`(property_name: STRING)`<br>
**force_floating**  
`(self, *args, **kargs)`<br>
**free**  
`(path: PARAM)`<br>
**freeze_notify**  
`(self)`<br>
##### 🔧 get_* Methods
**get_by_id**  
`(path_id: INT32)`<br>
**get_children**  
`()`<br>
**get_color_tag**  
`()`<br>
**get_data**  
`(self, *args, **kargs)`<br>
**get_expanded**  
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
**get_parasite**  
`(name: STRING)`<br>
**get_parasite_list**  
`()`<br>
**get_parent**  
`()`<br>
⚠️ **get_properties**
_Unable to extract signature — no signature found for builtin <method 'get_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **get_property**
_Unable to extract signature — no signature found for builtin <method 'get_property' of 'gi._gi.GObject' objects>_<br>
**get_qdata**  
`(self, *args, **kargs)`<br>
**get_strokes**  
`(num_strokes: UINT64)`<br>
**get_tattoo**  
`()`<br>
**get_user_writable_dir**  
`(path: PARAM)`<br>
**get_visible**  
`()`<br>
**getv**  
`(n_properties: UINT32, names: FLAGS, values: FLAGS)`<br>
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
##### 🔧 is_* Methods
**is_channel**  
`()`<br>
**is_drawable**  
`()`<br>
**is_floating**  
`()`<br>
**is_group**  
`()`<br>
**is_group_layer**  
`()`<br>
**is_layer**  
`()`<br>
**is_layer_mask**  
`()`<br>
**is_path**  
`()`<br>
**is_selection**  
`()`<br>
**is_text_layer**  
`()`<br>
**is_valid**  
`()`<br>
**list_properties**  
`(n_properties: UINT32)`<br>
**new**  
`(image: BOXED, name: STRING)`<br>
**new_from_text_layer**  
`(image: BOXED, layer: BOXED)`<br>
**newv**  
`(object_type: GTYPE, n_parameters: UINT32, parameters: FLAGS)`<br>
**notify**  
`(property_name: STRING)`<br>
**notify_by_pspec**  
`(self, *args, **kargs)`<br>
**override_property**  
`(property_id: UINT32, name: STRING)`<br>
**parse**  
`(path: STRING, max_paths: INT32, check: BOOLEAN, check_failed: PARAM)`<br>
**ref**  
`(self, *args, **kargs)`<br>
**ref_sink**  
`(self, *args, **kargs)`<br>
**remove_stroke**  
`(stroke_id: INT32)`<br>
**replace_data**  
`(self, *args, **kargs)`<br>
**replace_qdata**  
`(self, *args, **kargs)`<br>
**run_dispose**  
`()`<br>
##### 🔧 set_* Methods
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
⚠️ **set_properties**
_Unable to extract signature — no signature found for builtin <method 'set_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **set_property**
_Unable to extract signature — no signature found for builtin <method 'set_property' of 'gi._gi.GObject' objects>_<br>
**set_tattoo**  
`(tattoo: UINT32)`<br>
**set_visible**  
`(visible: BOOLEAN)`<br>
**steal_data**  
`(self, *args, **kargs)`<br>
**steal_qdata**  
`(self, *args, **kargs)`<br>
**stop_emission**  
`(self, detailed_signal)`<br>
⚠️ **stop_emission_by_name**
_Unable to extract signature — callable gi.FunctionInfo(signal_stop_emission_by_name) is not supported by signature_<br>
##### 🔧 stroke_* Methods
**stroke_close**  
`(stroke_id: INT32)`<br>
**stroke_flip**  
`(stroke_id: INT32, flip_type: BOXED, axis: DOUBLE)`<br>
**stroke_flip_free**  
`(stroke_id: INT32, x1: DOUBLE, y1: DOUBLE, x2: DOUBLE, y2: DOUBLE)`<br>
**stroke_get_length**  
`(stroke_id: INT32, precision: DOUBLE)`<br>
**stroke_get_point_at_dist**  
`(stroke_id: INT32, dist: DOUBLE, precision: DOUBLE, x_point: DOUBLE, y_point: DOUBLE, slope: DOUBLE, valid: BOOLEAN)`<br>
**stroke_get_points**  
`(stroke_id: INT32, num_points: UINT64, controlpoints: FLAGS, closed: BOOLEAN)`<br>
**stroke_interpolate**  
`(stroke_id: INT32, precision: DOUBLE, num_coords: UINT64, closed: BOOLEAN)`<br>
**stroke_new_from_points**  
`(type: BOXED, num_points: UINT64, controlpoints: FLAGS, closed: BOOLEAN)`<br>
**stroke_reverse**  
`(stroke_id: INT32)`<br>
**stroke_rotate**  
`(stroke_id: INT32, center_x: DOUBLE, center_y: DOUBLE, angle: DOUBLE)`<br>
**stroke_scale**  
`(stroke_id: INT32, scale_x: DOUBLE, scale_y: DOUBLE)`<br>
**stroke_translate**  
`(stroke_id: INT32, off_x: DOUBLE, off_y: DOUBLE)`<br>
**thaw_notify**  
`()`<br>
**to_str**  
`(path: PARAM)`<br>
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
**unref**  
`(self, *args, **kargs)`<br>
**watch_closure**  
`(self, *args, **kargs)`<br>
⚠️ **weak_ref**
_Unable to extract signature — no signature found for builtin <method 'weak_ref' of 'gi._gi.GObject' objects>_<br>
<br>


<a name="properties"></a>
#### 🏷️ Properties


- **id**: `gint` (read/write)
<br>


<a name="signals"></a>
#### 📣 Signals


<br>