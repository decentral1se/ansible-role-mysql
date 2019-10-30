# ansible-role-mysql

## Table Of Contents

* [About](#about)
* [Role Defaults](#role-defaults)
* [Example Playbooks](#example-playbooks)
* [License](#license)
* [Author](#author)

## About

> MySQL server for RHEL/CentOS and Debian/Ubuntu.

[Back to table of contents](#table-of-contents)

## Role Defaults

**Quicklist**: [mysql_bind_address](#mysql_bind_address),
[mysql_binlog_format](#mysql_binlog_format),
[mysql_config_include_files](#mysql_config_include_files),
[mysql_databases](#mysql_databases), [mysql_datadir](#mysql_datadir),
[mysql_enabled_on_startup](#mysql_enabled_on_startup),
[mysql_enablerepo](#mysql_enablerepo),
[mysql_event_scheduler_state](#mysql_event_scheduler_state),
[mysql_expire_logs_days](#mysql_expire_logs_days),
[mysql_group_concat_max_len](#mysql_group_concat_max_len),
[mysql_innodb_buffer_pool_size](#mysql_innodb_buffer_pool_size),
[mysql_innodb_file_format](#mysql_innodb_file_format),
[mysql_innodb_file_per_table](#mysql_innodb_file_per_table),
[mysql_innodb_flush_log_at_trx_commit](#mysql_innodb_flush_log_at_trx_commit),
[mysql_innodb_large_prefix](#mysql_innodb_large_prefix),
[mysql_innodb_lock_wait_timeout](#mysql_innodb_lock_wait_timeout),
[mysql_innodb_log_buffer_size](#mysql_innodb_log_buffer_size),
[mysql_innodb_log_file_size](#mysql_innodb_log_file_size),
[mysql_join_buffer_size](#mysql_join_buffer_size),
[mysql_key_buffer_size](#mysql_key_buffer_size), [mysql_log](#mysql_log),
[mysql_log_file_group](#mysql_log_file_group),
[mysql_lower_case_table_names](#mysql_lower_case_table_names),
[mysql_max_allowed_packet](#mysql_max_allowed_packet),
[mysql_max_binlog_size](#mysql_max_binlog_size),
[mysql_max_connections](#mysql_max_connections),
[mysql_max_heap_table_size](#mysql_max_heap_table_size),
[mysql_myisam_sort_buffer_size](#mysql_myisam_sort_buffer_size),
[mysql_mysqldump_max_allowed_packet](#mysql_mysqldump_max_allowed_packet),
[mysql_port](#mysql_port), [mysql_query_cache_limit](#mysql_query_cache_limit),
[mysql_query_cache_size](#mysql_query_cache_size),
[mysql_query_cache_type](#mysql_query_cache_type),
[mysql_read_buffer_size](#mysql_read_buffer_size),
[mysql_read_rnd_buffer_size](#mysql_read_rnd_buffer_size),
[mysql_replication_master](#mysql_replication_master),
[mysql_replication_role](#mysql_replication_role),
[mysql_replication_user](#mysql_replication_user),
[mysql_root_home](#mysql_root_home),
[mysql_root_password](#mysql_root_password),
[mysql_root_password_update](#mysql_root_password_update),
[mysql_root_username](#mysql_root_username),
[mysql_server_id](#mysql_server_id),
[mysql_skip_name_resolve](#mysql_skip_name_resolve),
[mysql_slow_query_log_enabled](#mysql_slow_query_log_enabled),
[mysql_slow_query_time](#mysql_slow_query_time),
[mysql_sort_buffer_size](#mysql_sort_buffer_size),
[mysql_sql_mode](#mysql_sql_mode),
[mysql_table_open_cache](#mysql_table_open_cache),
[mysql_thread_cache_size](#mysql_thread_cache_size),
[mysql_tmp_table_size](#mysql_tmp_table_size),
[mysql_user_home](#mysql_user_home), [mysql_user_name](#mysql_user_name),
[mysql_user_password](#mysql_user_password),
[mysql_user_password_update](#mysql_user_password_update),
[mysql_users](#mysql_users), [mysql_wait_timeout](#mysql_wait_timeout),
[overwrite_global_mycnf](#overwrite_global_mycnf)

### mysql_bind_address 

* *help*: TODO.
* *default*: ``0.0.0.0``

[Back to table of contents](#table-of-contents)

### mysql_binlog_format 

* *help*: TODO.
* *default*: ``ROW``

[Back to table of contents](#table-of-contents)

### mysql_config_include_files 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_databases 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_datadir 

* *help*: TODO.
* *default*: ``/var/lib/mysql``

[Back to table of contents](#table-of-contents)

### mysql_enabled_on_startup 

* *help*: TODO.
* *default*: ``True``

[Back to table of contents](#table-of-contents)

### mysql_enablerepo 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_event_scheduler_state 

* *help*: TODO.
* *default*: ``OFF``

[Back to table of contents](#table-of-contents)

### mysql_expire_logs_days 

* *help*: TODO.
* *default*: ``10``

[Back to table of contents](#table-of-contents)

### mysql_group_concat_max_len 

* *help*: TODO.
* *default*: ``1024``

[Back to table of contents](#table-of-contents)

### mysql_innodb_buffer_pool_size 

* *help*: TODO.
* *default*: ``256M``

[Back to table of contents](#table-of-contents)

### mysql_innodb_file_format 

* *help*: TODO.
* *default*: ``barracuda``

[Back to table of contents](#table-of-contents)

### mysql_innodb_file_per_table 

* *help*: TODO.
* *default*: ``1``

[Back to table of contents](#table-of-contents)

### mysql_innodb_flush_log_at_trx_commit 

* *help*: TODO.
* *default*: ``1``

[Back to table of contents](#table-of-contents)

### mysql_innodb_large_prefix 

* *help*: TODO.
* *default*: ``1``

[Back to table of contents](#table-of-contents)

### mysql_innodb_lock_wait_timeout 

* *help*: TODO.
* *default*: ``50``

[Back to table of contents](#table-of-contents)

### mysql_innodb_log_buffer_size 

* *help*: TODO.
* *default*: ``8M``

[Back to table of contents](#table-of-contents)

### mysql_innodb_log_file_size 

* *help*: TODO.
* *default*: ``64M``

[Back to table of contents](#table-of-contents)

### mysql_join_buffer_size 

* *help*: TODO.
* *default*: ``262144``

[Back to table of contents](#table-of-contents)

### mysql_key_buffer_size 

* *help*: TODO.
* *default*: ``256M``

[Back to table of contents](#table-of-contents)

### mysql_log 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_log_file_group 

* *help*: TODO.
* *default*: ``mysql``

[Back to table of contents](#table-of-contents)

### mysql_lower_case_table_names 

* *help*: TODO.
* *default*: ``0``

[Back to table of contents](#table-of-contents)

### mysql_max_allowed_packet 

* *help*: TODO.
* *default*: ``64M``

[Back to table of contents](#table-of-contents)

### mysql_max_binlog_size 

* *help*: TODO.
* *default*: ``100M``

[Back to table of contents](#table-of-contents)

### mysql_max_connections 

* *help*: TODO.
* *default*: ``151``

[Back to table of contents](#table-of-contents)

### mysql_max_heap_table_size 

* *help*: TODO.
* *default*: ``16M``

[Back to table of contents](#table-of-contents)

### mysql_myisam_sort_buffer_size 

* *help*: TODO.
* *default*: ``64M``

[Back to table of contents](#table-of-contents)

### mysql_mysqldump_max_allowed_packet 

* *help*: TODO.
* *default*: ``64M``

[Back to table of contents](#table-of-contents)

### mysql_port 

* *help*: TODO.
* *default*: ``3306``

[Back to table of contents](#table-of-contents)

### mysql_query_cache_limit 

* *help*: TODO.
* *default*: ``1M``

[Back to table of contents](#table-of-contents)

### mysql_query_cache_size 

* *help*: TODO.
* *default*: ``16M``

[Back to table of contents](#table-of-contents)

### mysql_query_cache_type 

* *help*: TODO.
* *default*: ``0``

[Back to table of contents](#table-of-contents)

### mysql_read_buffer_size 

* *help*: TODO.
* *default*: ``1M``

[Back to table of contents](#table-of-contents)

### mysql_read_rnd_buffer_size 

* *help*: TODO.
* *default*: ``4M``

[Back to table of contents](#table-of-contents)

### mysql_replication_master 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_replication_role 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_replication_user 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_root_home 

* *help*: TODO.
* *default*: ``/root``

[Back to table of contents](#table-of-contents)

### mysql_root_password 

* *help*: TODO.
* *default*: ``root``

[Back to table of contents](#table-of-contents)

### mysql_root_password_update 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_root_username 

* *help*: TODO.
* *default*: ``root``

[Back to table of contents](#table-of-contents)

### mysql_server_id 

* *help*: TODO.
* *default*: ``1``

[Back to table of contents](#table-of-contents)

### mysql_skip_name_resolve 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_slow_query_log_enabled 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_slow_query_time 

* *help*: TODO.
* *default*: ``2``

[Back to table of contents](#table-of-contents)

### mysql_sort_buffer_size 

* *help*: TODO.
* *default*: ``1M``

[Back to table of contents](#table-of-contents)

### mysql_sql_mode 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_table_open_cache 

* *help*: TODO.
* *default*: ``256``

[Back to table of contents](#table-of-contents)

### mysql_thread_cache_size 

* *help*: TODO.
* *default*: ``8``

[Back to table of contents](#table-of-contents)

### mysql_tmp_table_size 

* *help*: TODO.
* *default*: ``16M``

[Back to table of contents](#table-of-contents)

### mysql_user_home 

* *help*: TODO.
* *default*: ``/root``

[Back to table of contents](#table-of-contents)

### mysql_user_name 

* *help*: TODO.
* *default*: ``root``

[Back to table of contents](#table-of-contents)

### mysql_user_password 

* *help*: TODO.
* *default*: ``root``

[Back to table of contents](#table-of-contents)

### mysql_user_password_update 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_users 

* *help*: TODO.

[Back to table of contents](#table-of-contents)

### mysql_wait_timeout 

* *help*: TODO.
* *default*: ``28800``

[Back to table of contents](#table-of-contents)

### overwrite_global_mycnf 

* *help*: TODO.
* *default*: ``True``

[Back to table of contents](#table-of-contents)

## Example Playbooks

### Basic Usage

```yaml
- hosts: db-servers
  roles:
    - role: geerlingguy.mysql
      mysql_root_password: super-secure-password
      mysql_databases:
        - name: example_db
          encoding: latin1
          collation: latin1_general_ci
      mysql_users:
        - name: example_user
          host: "%"
          password: similarly-secure-password
          priv: "example_db.*:ALL"
```


[Back to table of contents](#table-of-contents)

## License

license (BSD, MIT)

[Back to table of contents](#table-of-contents)

## Author

geerlingguy

[Back to table of contents](#table-of-contents)
