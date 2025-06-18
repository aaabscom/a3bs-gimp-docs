## Table of Contents
- [Class: GimpProcedureConfigRun-python-fu-pdb-scan](#class-gimpprocedureconfigrun-python-fu-pdb-scan)
  - [🔹 Public Methods](#-public-methods)
  - [🔒 Private Methods](#-private-methods)
  - [⚙️ Dunder Methods](#️-dunder-methods)
  - [🏷️ Properties](#-properties)
  - [📣 Signals](#-signals)

### Class: GimpProcedureConfigRun-python-fu-pdb-scan
**Module**: __gi__  
**Base Class**: ProcedureConfig, ConfigInterface<br><br>
**Inheritance Tree**:
- `__gi__.GimpProcedureConfigRun-python-fu-pdb-scan` *(Builtin ,GObject.Object)*
  - `gi.repository.Gimp.ProcedureConfig` *(GI-wrapped ,GObject.Object)*
    - `gi.overrides.GObject.Object` *(GI-wrapped ,GObject.Object)*
      - `gi.repository.GObject.Object` *(GI-wrapped)*
        - `gi._gi.GObject`
          - `gi.repository.Gimp.ConfigInterface` *(GI-wrapped)*
            - `gobject.GInterface` *(Builtin)*
              - `builtins.object` *(Builtin)*
<br>


<a name="public-methods"></a>
#### 🔹 Public Methods


⚠️ **bind_property**
_Unable to extract signature — no signature found for builtin <method 'bind_property' of 'gi._gi.GObject' objects>_<br>
**bind_property_full**  
`(self, *args, **kargs)`<br>
##### 🔧 build_* Methods
**build_data_path**  
`(name: STRING)`<br>
**build_plug_in_path**  
`(name: STRING)`<br>
**build_system_path**  
`(name: STRING)`<br>
**build_writable_path**  
`(name: STRING)`<br>
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
**deserialize_return**  
`(scanner: BOXED, expected_token: BOXED, nest_level: INT32)`<br>
**diff**  
`(a: BOXED, b: BOXED, flags: BOXED)`<br>
⚠️ **disconnect**
_Unable to extract signature — callable gi.FunctionInfo(signal_handler_disconnect) is not supported by signature_<br>
⚠️ **disconnect_by_func**
_Unable to extract signature — no signature found for builtin <method 'disconnect_by_func' of 'gi._gi.GObject' objects>_<br>
⚠️ **emit**
_Unable to extract signature — no signature found for builtin <method 'emit' of 'gi._gi.GObject' objects>_<br>
**emit_stop_by_name**  
`(self, detailed_signal)`<br>
**error_quark**  
`()`<br>
**find_property**  
`(property_name: STRING)`<br>
**force_floating**  
`(self, *args, **kargs)`<br>
**freeze_notify**  
`(self)`<br>
##### 🔧 get_* Methods
**get_choice_id**  
`(property_name: STRING)`<br>
**get_color_array**  
`(property_name: STRING)`<br>
**get_core_object_array**  
`(property_name: STRING)`<br>
**get_data**  
`(self, *args, **kargs)`<br>
**get_procedure**  
`()`<br>
⚠️ **get_properties**
_Unable to extract signature — no signature found for builtin <method 'get_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **get_property**
_Unable to extract signature — no signature found for builtin <method 'get_property' of 'gi._gi.GObject' objects>_<br>
**get_qdata**  
`(self, *args, **kargs)`<br>
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
**is_floating**  
`()`<br>
**list_properties**  
`(n_properties: UINT32)`<br>
**newv**  
`(object_type: GTYPE, n_parameters: UINT32, parameters: FLAGS)`<br>
**notify**  
`(property_name: STRING)`<br>
**notify_by_pspec**  
`(self, *args, **kargs)`<br>
**override_property**  
`(property_id: UINT32, name: STRING)`<br>
**param_spec_duplicate**  
`(pspec: BOXED)`<br>
**ref**  
`(self, *args, **kargs)`<br>
**ref_sink**  
`(self, *args, **kargs)`<br>
**replace_data**  
`(self, *args, **kargs)`<br>
**replace_qdata**  
`(self, *args, **kargs)`<br>
**reset_properties**  
`(object: BOXED)`<br>
**reset_property**  
`(object: BOXED, property_name: STRING)`<br>
**run_dispose**  
`()`<br>
**save_metadata**  
`(exported_image: BOXED, file: BOXED)`<br>
**serialize_value**  
`(value: BOXED, str: BOXED, escaped: BOOLEAN)`<br>
##### 🔧 set_* Methods
**set_color_array**  
`(property_name: STRING, colors: FLAGS, n_colors: UINT64)`<br>
**set_core_object_array**  
`(property_name: STRING, objects: FLAGS, n_objects: UINT64)`<br>
**set_data**  
`(self, *args, **kargs)`<br>
⚠️ **set_properties**
_Unable to extract signature — no signature found for builtin <method 'set_properties' of 'gi._gi.GObject' objects>_<br>
⚠️ **set_property**
_Unable to extract signature — no signature found for builtin <method 'set_property' of 'gi._gi.GObject' objects>_<br>
**steal_data**  
`(self, *args, **kargs)`<br>
**steal_qdata**  
`(self, *args, **kargs)`<br>
**stop_emission**  
`(self, detailed_signal)`<br>
⚠️ **stop_emission_by_name**
_Unable to extract signature — callable gi.FunctionInfo(signal_stop_emission_by_name) is not supported by signature_<br>
**string_append_escaped**  
`(string: BOXED, val: STRING)`<br>
**sync**  
`(src: BOXED, dest: BOXED, flags: BOXED)`<br>
**thaw_notify**  
`()`<br>
**type_register**  
`(parent_type: GTYPE, type_name: STRING, pspecs: FLAGS, n_pspecs: INT32)`<br>
**unref**  
`(self, *args, **kargs)`<br>
**watch_closure**  
`(self, *args, **kargs)`<br>
⚠️ **weak_ref**
_Unable to extract signature — no signature found for builtin <method 'weak_ref' of 'gi._gi.GObject' objects>_<br>
<br>


<a name="properties"></a>
#### 🏷️ Properties


- **procedure**: `GimpProcedure` (read/write)
<br>


<a name="signals"></a>
#### 📣 Signals


<br>