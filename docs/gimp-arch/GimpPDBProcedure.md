---
title: "Gimp PDB Procedure"
date: 2025-06-17
layout: default
---

## Table of Contents
- [Class: GimpPDBProcedure](#class-gimppdbprocedure)
  - [🔹 Public Methods](#public-methods)
  - [🔒 Private Methods](#private-methods)
  - [⚙️ Dunder Methods](#dunder-methods)
  - [🏷️ Properties](#properties)
  - [📣 Signals](#signals)

### Class: GimpPDBProcedure
**Module**: __gi__  
**Base Class**: Procedure<br><br>
**Inheritance Tree**:
- `__gi__.GimpPDBProcedure` *(Builtin ,GObject.Object)*
  - `gi.repository.Gimp.Procedure` *(GI-wrapped ,GObject.Object)*
    - `gi.overrides.GObject.Object` *(GI-wrapped ,GObject.Object)*
      - `gi.repository.GObject.Object` *(GI-wrapped)*
        - `gi._gi.GObject`
          - `builtins.object` *(Builtin)*
<br>
#### 🔧 Public Methods
##### add_* Methods

**add_boolean_argument**  
`(name: STRING, nick: STRING, blurb: STRING, value: BOOLEAN, flags: BOXED)`<br>
**add_boolean_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, value: BOOLEAN, flags: BOXED)`<br>
**add_boolean_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, value: BOOLEAN, flags: BOXED)`<br>
**add_brush_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_brush_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_brush_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_bytes_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_bytes_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_bytes_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_channel_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_channel_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_channel_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_choice_argument**  
`(name: STRING, nick: STRING, blurb: STRING, choice: BOXED, value: STRING, flags: BOXED)`<br>
**add_choice_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, choice: BOXED, value: STRING, flags: BOXED)`<br>
**add_choice_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, choice: BOXED, value: STRING, flags: BOXED)`<br>
**add_color_argument**  
`(name: STRING, nick: STRING, blurb: STRING, has_alpha: BOOLEAN, value: BOXED, flags: BOXED)`<br>
**add_color_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, has_alpha: BOOLEAN, value: BOXED, flags: BOXED)`<br>
**add_color_from_string_argument**  
`(name: STRING, nick: STRING, blurb: STRING, has_alpha: BOOLEAN, value: STRING, flags: BOXED)`<br>
**add_color_from_string_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, has_alpha: BOOLEAN, value: STRING, flags: BOXED)`<br>
**add_color_from_string_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, has_alpha: BOOLEAN, value: STRING, flags: BOXED)`<br>
**add_color_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, has_alpha: BOOLEAN, value: BOXED, flags: BOXED)`<br>
**add_core_object_array_argument**  
`(name: STRING, nick: STRING, blurb: STRING, object_type: GTYPE, flags: BOXED)`<br>
**add_core_object_array_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, object_type: GTYPE, flags: BOXED)`<br>
**add_core_object_array_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, object_type: GTYPE, flags: BOXED)`<br>
**add_display_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_display_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_display_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_double_argument**  
`(name: STRING, nick: STRING, blurb: STRING, min: DOUBLE, max: DOUBLE, value: DOUBLE, flags: BOXED)`<br>
**add_double_array_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_double_array_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_double_array_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_double_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, min: DOUBLE, max: DOUBLE, value: DOUBLE, flags: BOXED)`<br>
**add_double_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, min: DOUBLE, max: DOUBLE, value: DOUBLE, flags: BOXED)`<br>
**add_drawable_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_drawable_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_drawable_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_enum_argument**  
`(name: STRING, nick: STRING, blurb: STRING, enum_type: GTYPE, value: INT32, flags: BOXED)`<br>
**add_enum_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, enum_type: GTYPE, value: INT32, flags: BOXED)`<br>
**add_enum_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, enum_type: GTYPE, value: INT32, flags: BOXED)`<br>
**add_file_argument**  
`(name: STRING, nick: STRING, blurb: STRING, action: BOXED, none_ok: BOOLEAN, default_file: BOXED, flags: BOXED)`<br>
**add_file_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, action: BOXED, none_ok: BOOLEAN, default_file: BOXED, flags: BOXED)`<br>
**add_file_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_font_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_font_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_font_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_gradient_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_gradient_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_gradient_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_group_layer_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_group_layer_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_group_layer_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_image_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_image_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_image_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_int32_array_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_int32_array_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_int32_array_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_int_argument**  
`(name: STRING, nick: STRING, blurb: STRING, min: INT32, max: INT32, value: INT32, flags: BOXED)`<br>
**add_int_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, min: INT32, max: INT32, value: INT32, flags: BOXED)`<br>
**add_int_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, min: INT32, max: INT32, value: INT32, flags: BOXED)`<br>
**add_item_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_item_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_item_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_layer_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_layer_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_layer_mask_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_layer_mask_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_layer_mask_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_layer_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_menu_path**  
`(menu_path: STRING)`<br>
**add_palette_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_palette_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_palette_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_param_argument**  
`(name: STRING, nick: STRING, blurb: STRING, param_type: GTYPE, flags: BOXED)`<br>
**add_param_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, param_type: GTYPE, flags: BOXED)`<br>
**add_param_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, param_type: GTYPE, flags: BOXED)`<br>
**add_parasite_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_parasite_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_parasite_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_path_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_path_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_path_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_pattern_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_pattern_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, default_value: BOXED, default_to_context: BOOLEAN, flags: BOXED)`<br>
**add_pattern_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_resource_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, default_value: BOXED, flags: BOXED)`<br>
**add_resource_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, default_value: BOXED, flags: BOXED)`<br>
**add_resource_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_selection_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_selection_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_selection_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_string_argument**  
`(name: STRING, nick: STRING, blurb: STRING, value: STRING, flags: BOXED)`<br>
**add_string_array_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_string_array_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_string_array_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, flags: BOXED)`<br>
**add_string_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, value: STRING, flags: BOXED)`<br>
**add_string_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, value: STRING, flags: BOXED)`<br>
**add_text_layer_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_text_layer_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_text_layer_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, none_ok: BOOLEAN, flags: BOXED)`<br>
**add_uint_argument**  
`(name: STRING, nick: STRING, blurb: STRING, min: UINT32, max: UINT32, value: UINT32, flags: BOXED)`<br>
**add_uint_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, min: UINT32, max: UINT32, value: UINT32, flags: BOXED)`<br>
**add_uint_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, min: UINT32, max: UINT32, value: UINT32, flags: BOXED)`<br>
**add_unit_argument**  
`(name: STRING, nick: STRING, blurb: STRING, show_pixels: BOOLEAN, show_percent: BOOLEAN, value: BOXED, flags: BOXED)`<br>
**add_unit_aux_argument**  
`(name: STRING, nick: STRING, blurb: STRING, show_pixels: BOOLEAN, show_percent: BOOLEAN, value: BOXED, flags: BOXED)`<br>
**add_unit_return_value**  
`(name: STRING, nick: STRING, blurb: STRING, show_pixels: BOOLEAN, show_percent: BOOLEAN, value: BOXED, flags: BOXED)`<br>
⚠️ **bind_property**
_Unable to extract signature — no signature found for builtin <method 'bind_property' of 'gi._gi.GObject' objects>_<br>
**bind_property_full**  
`(self, *args, **kargs)`<br>
⚠️ **chain**
_Unable to extract signature — no signature found for builtin <method 'chain' of 'gi._gi.GObject' objects>_<br>
**compat_control**  
`(self, *args, **kargs)`<br>
##### connect_* Methods

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
**create_config**  
`()`<br>
⚠️ **disconnect**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_disconnect) is not supported by signature_<br>
⚠️ **disconnect_by_func**
_Unable to extract signature — no signature found for builtin <method 'disconnect_by_func' of 'gi._gi.GObject' objects>_<br>
##### do_* Methods

**do_install**  
`()`<br>
**do_run**  
`(args: BOXED)`<br>
**do_set_sensitivity**  
`(sensitivity_mask: INT32)`<br>
**do_uninstall**  
`()`<br>
⚠️ **emit**
_Unable to extract signature — no signature found for builtin <method 'emit' of 'gi._gi.GObject' objects>_<br>
**emit_stop_by_name**  
`(self, detailed_signal)`<br>
##### find_* Methods

**find_argument**  
`(name: STRING)`<br>
**find_aux_argument**  
`(name: STRING)`<br>
**find_property**  
`(property_name: STRING)`<br>
**find_return_value**  
`(name: STRING)`<br>
**force_floating**  
`(self, *args, **kargs)`<br>
**freeze_notify**  
`(self)`<br>
##### get_* Methods

**get_argument_sync**  
`(arg_name: STRING)`<br>
**get_arguments**  
`(n_arguments: INT32)`<br>
**get_authors**  
`()`<br>
**get_aux_arguments**  
`(n_arguments: INT32)`<br>
**get_blurb**  
`()`<br>
**get_copyright**  
`()`<br>
**get_data**  
`(self, *args, **kargs)`<br>
**get_date**  
`()`<br>
**get_help**  
`()`<br>
**get_help_id**  
`()`<br>
**get_icon_file**  
`()`<br>
**get_icon_name**  
`()`<br>
**get_icon_pixbuf**  
`()`<br>
**get_icon_type**  
`()`<br>
**get_image_types**  
`()`<br>
**get_menu_label**  
`()`<br>
**get_menu_paths**  
`()`<br>
**get_name**  
`()`<br>
**get_plug_in**  
`()`<br>
**get_proc_type**  
`()`<br>
⚠️ **get_properties**
_Unable to extract signature — no signature found for builtin <method 'get_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **get_property**
_Unable to extract signature — no signature found for builtin <method 'get_property' of 'gi._gi.GObject' objects>_<br>
**get_qdata**  
`(self, *args, **kargs)`<br>
**get_return_values**  
`(n_return_values: INT32)`<br>
**get_sensitivity_mask**  
`()`<br>
**getv**  
`(n_properties: UINT32, names: FLAGS, values: FLAGS)`<br>
##### handler_* Methods

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
**install_properties**  
`(n_pspecs: UINT32, pspecs: FLAGS)`<br>
**install_property**  
`(property_id: UINT32, pspec: BOXED)`<br>
##### interface_* Methods

**interface_find_property**  
`(self, *args, **kargs)`<br>
**interface_install_property**  
`(self, *args, **kargs)`<br>
**interface_list_properties**  
`(self, *args, **kargs)`<br>
**is_floating**  
`()`<br>
**is_internal**  
`()`<br>
**list_properties**  
`(n_properties: UINT32)`<br>
**new**  
`(plug_in: BOXED, name: STRING, proc_type: BOXED, run_func: BOXED, run_data: VOID, run_data_destroy: BOXED)`<br>
**new_return_values**  
`(status: BOXED, error: VARIANT)`<br>
**newv**  
`(object_type: GTYPE, n_parameters: UINT32, parameters: FLAGS)`<br>
**notify**  
`(property_name: STRING)`<br>
**notify_by_pspec**  
`(self, *args, **kargs)`<br>
**override_property**  
`(property_id: UINT32, name: STRING)`<br>
**persistent_ready**  
`()`<br>
**ref**  
`(self, *args, **kargs)`<br>
**ref_sink**  
`(self, *args, **kargs)`<br>
**replace_data**  
`(self, *args, **kargs)`<br>
**replace_qdata**  
`(self, *args, **kargs)`<br>
**run**  
`(config: BOXED)`<br>
**run_dispose**  
`()`<br>
##### set_* Methods

**set_argument_sync**  
`(arg_name: STRING, sync: BOXED)`<br>
**set_attribution**  
`(authors: STRING, copyright: STRING, date: STRING)`<br>
**set_data**  
`(self, *args, **kargs)`<br>
**set_documentation**  
`(blurb: STRING, help: STRING, help_id: STRING)`<br>
**set_icon_file**  
`(file: BOXED)`<br>
**set_icon_name**  
`(icon_name: STRING)`<br>
**set_icon_pixbuf**  
`(pixbuf: BOXED)`<br>
**set_image_types**  
`(image_types: STRING)`<br>
**set_menu_label**  
`(menu_label: STRING)`<br>
⚠️ **set_properties**
_Unable to extract signature — no signature found for builtin <method 'set_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **set_property**
_Unable to extract signature — no signature found for builtin <method 'set_property' of 'gi._gi.GObject' objects>_<br>
**set_sensitivity_mask**  
`(sensitivity_mask: INT32)`<br>
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
**unref**  
`(self, *args, **kargs)`<br>
**watch_closure**  
`(self, *args, **kargs)`<br>
⚠️ **weak_ref**
_Unable to extract signature — no signature found for builtin <method 'weak_ref' of 'gi._gi.GObject' objects>_<br>
<br>
#### Properties

- **plug-in**: `GimpPlugIn` (read/write)
- **name**: `gchararray` (read/write)
- **procedure-type**: `GimpPDBProcType` (read/write)
- **pdb**: `GimpPDB` (read/write)
<br>
#### Signals

<br>