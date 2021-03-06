
### Types

 - `/software/useraccess/useraccess_pointer`
 - `/software/useraccess/structure_kerberos`
    - `/software/useraccess/structure_kerberos/realm`
        - Optional
        - Type: type_hostname
    - `/software/useraccess/structure_kerberos/principal`
        - Optional
        - Type: string
    - `/software/useraccess/structure_kerberos/instance`
        - Optional
        - Type: string
    - `/software/useraccess/structure_kerberos/host`
        - Optional
        - Type: type_hostname
 - `/software/useraccess/credentialfilestring`
 - `/software/useraccess/structure_useraccess_auth`
    - `/software/useraccess/structure_useraccess_auth/ssh_keys_urls`
        - Optional
        - Type: type_absoluteURI
    - `/software/useraccess/structure_useraccess_auth/kerberos4`
        - Optional
        - Type: structure_kerberos
    - `/software/useraccess/structure_useraccess_auth/kerberos5`
        - Optional
        - Type: structure_kerberos
    - `/software/useraccess/structure_useraccess_auth/acls`
        - Optional
        - Type: string
    - `/software/useraccess/structure_useraccess_auth/roles`
        - Optional
        - Type: useraccess_pointer
    - `/software/useraccess/structure_useraccess_auth/ssh_keys`
        - Optional
        - Type: string
    - `/software/useraccess/structure_useraccess_auth/managed_credentials`
        - Optional
        - Type: credentialfilestring
 - `/software/useraccess/structure_component_useraccess`
    - `/software/useraccess/structure_component_useraccess/configSerial`
        - Optional
        - Type: string
    - `/software/useraccess/structure_component_useraccess/users`
        - Optional
        - Type: structure_useraccess_auth
    - `/software/useraccess/structure_component_useraccess/roles`
        - Optional
        - Type: structure_useraccess_auth
    - `/software/useraccess/structure_component_useraccess/acl_services`
        - Optional
        - Type: string
