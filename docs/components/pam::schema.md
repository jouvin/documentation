
### Types

 - `/software/pam/component_pam_options`
 - `/software/pam/component_listfile_acl`
    - `/software/pam/component_listfile_acl/filename`
        - Optional
        - Type: string
    - `/software/pam/component_listfile_acl/items`
        - Optional
        - Type: string
 - `/software/pam/component_pam_module_stack`
    - `/software/pam/component_pam_module_stack/control`
        - Optional
        - Type: string
    - `/software/pam/component_pam_module_stack/module`
        - Optional
        - Type: string
    - `/software/pam/component_pam_module_stack/options`
        - Optional
        - Type: component_pam_options
    - `/software/pam/component_pam_module_stack/options_list`
        - Optional
        - Type: string
    - `/software/pam/component_pam_module_stack/allow`
        - Optional
        - Type: component_listfile_acl
    - `/software/pam/component_pam_module_stack/deny`
        - Optional
        - Type: component_listfile_acl
 - `/software/pam/component_pam_service_type`
    - `/software/pam/component_pam_service_type/auth`
        - Optional
        - Type: component_pam_module_stack
    - `/software/pam/component_pam_service_type/account`
        - Optional
        - Type: component_pam_module_stack
    - `/software/pam/component_pam_service_type/password`
        - Optional
        - Type: component_pam_module_stack
    - `/software/pam/component_pam_service_type/session`
        - Optional
        - Type: component_pam_module_stack
    - `/software/pam/component_pam_service_type/mode`
        - Optional
        - Type: string
 - `/software/pam/component_pam_module`
    - `/software/pam/component_pam_module/path`
        - Optional
        - Type: string
 - `/software/pam/component_pam_access_entry`
    - `/software/pam/component_pam_access_entry/permission`
        - Optional
        - Type: string
    - `/software/pam/component_pam_access_entry/users`
        - Optional
        - Type: string
    - `/software/pam/component_pam_access_entry/origins`
        - Optional
        - Type: string
 - `/software/pam/component_pam_access`
    - `/software/pam/component_pam_access/filename`
        - Optional
        - Type: string
    - `/software/pam/component_pam_access/acl`
        - Optional
        - Type: component_pam_access_entry
    - `/software/pam/component_pam_access/lastacl`
        - Optional
        - Type: component_pam_access_entry
    - `/software/pam/component_pam_access/allowpos`
        - Optional
        - Type: boolean
    - `/software/pam/component_pam_access/allowneg`
        - Optional
        - Type: boolean
 - `/software/pam/component_pam_entry`
    - `/software/pam/component_pam_entry/modules`
        - Optional
        - Type: component_pam_module
    - `/software/pam/component_pam_entry/services`
        - Optional
        - Type: component_pam_service_type
    - `/software/pam/component_pam_entry/directory`
        - Optional
        - Type: string
    - `/software/pam/component_pam_entry/acldir`
        - Optional
        - Type: string
    - `/software/pam/component_pam_entry/access`
        - Optional
        - Type: component_pam_access
