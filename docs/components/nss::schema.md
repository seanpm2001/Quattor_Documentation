### Types

- `/software/nss/component_nss_build`
    - `/software/nss/component_nss_build/script`
        - required
        - type: string
    - `/software/nss/component_nss_build/depends`
        - optional
        - type: string
    - `/software/nss/component_nss_build/active`
        - optional
        - type: boolean
- `/software/nss/component_nss_build_dbs`
    - `/software/nss/component_nss_build_dbs/db`
        - optional
        - type: component_nss_build
    - `/software/nss/component_nss_build_dbs/nis`
        - optional
        - type: component_nss_build
    - `/software/nss/component_nss_build_dbs/compat`
        - optional
        - type: component_nss_build
    - `/software/nss/component_nss_build_dbs/dns`
        - optional
        - type: component_nss_build
    - `/software/nss/component_nss_build_dbs/files`
        - optional
        - type: component_nss_build
    - `/software/nss/component_nss_build_dbs/ldap`
        - optional
        - type: component_nss_build
- `/software/nss/component_nss_db`
- `/software/nss/component_nss_type`
    - `/software/nss/component_nss_type/build`
        - optional
        - type: component_nss_build_dbs
    - `/software/nss/component_nss_type/databases`
        - required
        - type: component_nss_db