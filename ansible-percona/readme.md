### Extra vars
    percona:
    cluster_name: percona-01
    mysql_options: |
        log_output=file
        slow_query_log=ON
        long_query_time=0
        max_connections=500
        skip-name-resolve
    wsrep:
        binlog_format: ROW
        default_storage_engine: InnoDB
        innodb_autoinc_lock_mode: 2
        pxc_strict_mode: DISABLED
        sst:
        password: kucinglucu
        username: sstuser
        wsrep_auto_increment_control: false
        wsrep_slave_threads: 8
    xtradb_datadir: /var/lib/mysql
    xtradb_partition: /dev/sda1
    xtradb_preflight_lock:
        bootstraped: _bootstraped
        configured: _configured
        installed: _installed
        password_changed: _password_changed
        secured: _secured
    xtradb_root:
        password: ""
        username: root
    xtradb_service: mysql
    xtradb_version: '57'
    proxy:
    http_proxy: ''
    https_proxy: ''
    no_proxy: ''
    xinetd:
        auth:
            password: buayakecil
            user: lakilakibermain
        resource_threshold: 75
