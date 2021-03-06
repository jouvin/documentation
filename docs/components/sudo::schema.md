
### Types

 - `/software/sudo/type_host_sudo`
 - `/software/sudo/type_user_alias`
 - `/software/sudo/type_cmd_alias`
 - `/software/sudo/type_host_alias`
 - `/software/sudo/structure_privilege_line`
    - `/software/sudo/structure_privilege_line/user`
        - Optional
        - Type: string
    - `/software/sudo/structure_privilege_line/run_as`
        - Optional
        - Type: string
    - `/software/sudo/structure_privilege_line/host`
        - Optional
        - Type: string
    - `/software/sudo/structure_privilege_line/options`
        - Optional
        - Type: string
    - `/software/sudo/structure_privilege_line/cmd`
        - Optional
        - Type: string
 - `/software/sudo/structure_sudo_default_options`
    - `/software/sudo/structure_sudo_default_options/long_otp_prompt`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/ignore_dot`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/mail_always`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/mail_badpass`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/mail_no_user`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/mail_no_host`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/mail_no_perms`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/tty_tickets`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/lecture`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/authenticate`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/root_sudo`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/log_host`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/log_year`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/shell_noargs`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/set_home`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/always_set_home`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/path_info`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/preserve_groups`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/fqdn`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/insults`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/requiretty`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/env_editor`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/rootpw`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/runaspw`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/targetpw`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/set_logname`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/stay_setuid`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/env_reset`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/use_loginclass`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/visiblepw`
        - Optional
        - Type: boolean
    - `/software/sudo/structure_sudo_default_options/passwd_tries`
        - Optional
        - Type: long
    - `/software/sudo/structure_sudo_default_options/loglinelen`
        - Optional
        - Type: long
    - `/software/sudo/structure_sudo_default_options/timestamp_timeout`
        - Optional
        - Type: long
    - `/software/sudo/structure_sudo_default_options/passwd_timeout`
        - Optional
        - Type: long
    - `/software/sudo/structure_sudo_default_options/umask`
        - Optional
        - Type: long
    - `/software/sudo/structure_sudo_default_options/mailsub`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/env_keep`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/env_delete`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/badpass_message`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/timestampdir`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/timestampowner`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/passprompt`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/runas_default`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/syslog_goodpri`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/syslog_badpri`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/editor`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/logfile`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/syslog`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/mailerpath`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/mailerflags`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/mailto`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/exempt_group`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/verifypw`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/listpw`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_default_options/secure_path`
        - Optional
        - Type: string
 - `/software/sudo/structure_sudo_defaults`
    - `/software/sudo/structure_sudo_defaults/user`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_defaults/run_as`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_defaults/host`
        - Optional
        - Type: type_host_sudo
    - `/software/sudo/structure_sudo_defaults/cmd`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_defaults/options`
        - Optional
        - Type: structure_sudo_default_options
 - `/software/sudo/structure_sudo_ldap`
    - `/software/sudo/structure_sudo_ldap/dn`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_ldap/objectClass`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_ldap/sudoOption`
        - Optional
        - Type: structure_sudo_default_options
    - `/software/sudo/structure_sudo_ldap/description`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_ldap/sudoUser`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_ldap/sudoRunAsUser`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_ldap/sudoHost`
        - Optional
        - Type: string
    - `/software/sudo/structure_sudo_ldap/sudoCommand`
        - Optional
        - Type: string
 - `/software/sudo/structure_component_sudo`
    - `/software/sudo/structure_component_sudo/general_options`
        - Optional
        - Type: structure_sudo_defaults
    - `/software/sudo/structure_component_sudo/user_aliases`
        - Optional
        - Type: type_user_alias
    - `/software/sudo/structure_component_sudo/run_as_aliases`
        - Optional
        - Type: type_user_alias
    - `/software/sudo/structure_component_sudo/host_aliases`
        - Optional
        - Type: type_host_alias
    - `/software/sudo/structure_component_sudo/cmd_aliases`
        - Optional
        - Type: type_cmd_alias
    - `/software/sudo/structure_component_sudo/privilege_lines`
        - Optional
        - Type: structure_privilege_line
    - `/software/sudo/structure_component_sudo/includes`
        - Optional
        - Type: string
    - `/software/sudo/structure_component_sudo/includes_dirs`
        - Optional
        - Type: string
    - `/software/sudo/structure_component_sudo/ldap`
        - Optional
        - Type: structure_sudo_ldap

### Functions

 - is_host_sudo
