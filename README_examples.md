# Example vars settings for CentOS and Ubuntu
This file shows the same config for CentOS and Ubuntu when using Elasticsearch version 1, 5 and 6.

## Ubuntu and Elasticsearch version 1

```
# elasticsearch role

elasticsearch_version: "1.7.6"
elasticsearch_apt_java_package: "openjdk-8-jre-headless"
elasticsearch_java_home: "/usr/lib/jvm/java-1.8.0-openjdk-amd64"
elasticsearch_heap_size: "1g"
elasticsearch_max_open_files: "65535"
elasticsearch_timezone: "UTC"
elasticsearch_node_max_local_storage_nodes: "1"
elasticsearch_index_mapper_dynamic: "true"
elasticsearch_memory_bootstrap_mlockall: "true"
elasticsearch_install_java: "true"
elasticsearch_thread_pools:
  - "threadpool.bulk.type: fixed"
  - "threadpool.bulk.size: 50"
  - "threadpool.bulk.queue_size: 1000"
elasticsearch_network_http_max_content_lengtht: 1024mb
elasticsearch_plugins:
  - { name: 'mobz/elasticsearch-head' }
elasticsearch_discovery_zen_ping_multicast_enabled: "false"
elasticsearch_max_locked_memory: "unlimited"
elasticsearch_network_host: "127.0.0.1"
```

## Ubuntu and Elasticsearch version 5

```
# elasticsearch role

elasticsearch_version: "5.6.10"
elasticsearch_apt_java_package: "openjdk-8-jre-headless"
elasticsearch_java_home: "/usr/lib/jvm/java-1.8.0-openjdk-amd64"
elasticsearch_heap_size: "1g"
elasticsearch_max_open_files: "65535"
elasticsearch_timezone: "UTC"
elasticsearch_node_max_local_storage_nodes: "1"
elasticsearch_index_mapper_dynamic: "true"
elasticsearch_memory_bootstrap_mlockall: "true"
elasticsearch_install_java: "true"
elasticsearch_thread_pools:
  - "thread_pool.bulk.size: 2"
  - "thread_pool.bulk.queue_size: 1000"
elasticsearch_network_http_max_content_lengtht: 1024mb
elasticsearch_plugins:
  - { name: 'mobz/elasticsearch-head' }
elasticsearch_discovery_zen_ping_multicast_enabled: "false"
elasticsearch_max_locked_memory: "unlimited"
elasticsearch_network_host: "127.0.0.1"
```

## Ubuntu and Elasticsearch version 6

```
# elasticsearch role

elasticsearch_version: "6.5.4"
elasticsearch_apt_java_package: "openjdk-8-jre-headless"
elasticsearch_java_home: "/usr/lib/jvm/java-1.8.0-openjdk-amd64"
elasticsearch_heap_size: "1g"
elasticsearch_max_open_files: "65535"
elasticsearch_timezone: "UTC"
elasticsearch_node_max_local_storage_nodes: "1"
elasticsearch_index_mapper_dynamic: "true"
elasticsearch_memory_bootstrap_mlockall: "true"
elasticsearch_install_java: "true"
elasticsearch_thread_pools:
  - "thread_pool.write.size: 2"
  - "thread_pool.write.queue_size: 1000"
elasticsearch_network_http_max_content_lengtht: 1024mb
elasticsearch_plugins:
  - { name: 'mobz/elasticsearch-head' }
elasticsearch_discovery_zen_ping_multicast_enabled: "false"
elasticsearch_max_locked_memory: "unlimited"
elasticsearch_network_host: "127.0.0.1"
```

## CentOS and Elastisearch version 1

```
# elasticsearch role

elasticsearch_version: "1.7.5"
elasticsearch_java_home: "/usr/lib/jvm/jre-1.8.0"
elasticsearch_heap_size: "1g"
elasticsearch_max_open_files: "65535"
elasticsearch_timezone: "UTC"
elasticsearch_node_max_local_storage_nodes: "1"
elasticsearch_index_mapper_dynamic: "true"
elasticsearch_memory_bootstrap_mlockall: "true"
elasticsearch_install_java: "true"
elasticsearch_thread_pools:
  - "threadpool.bulk.type: fixed"
  - "threadpool.bulk.size: 50"
  - "threadpool.bulk.queue_size: 1000"
elasticsearch_network_http_max_content_lengtht: 1024mb
elasticsearch_plugins:
  - { name: 'mobz/elasticsearch-head' }
elasticsearch_discovery_zen_ping_multicast_enabled: "false"
elasticsearch_max_locked_memory: "unlimited"
elasticsearch_network_host: "127.0.0.1"
```

## CentOS and Elastisearch version 5

```
# elasticsearch role

elasticsearch_version: "5.6.10'"
elasticsearch_java_home: "/usr/lib/jvm/jre-1.8.0"
elasticsearch_heap_size: "1g"
elasticsearch_max_open_files: "65535"
elasticsearch_timezone: "UTC"
elasticsearch_node_max_local_storage_nodes: "1"
elasticsearch_index_mapper_dynamic: "true"
elasticsearch_memory_bootstrap_mlockall: "true"
elasticsearch_install_java: "true"
elasticsearch_thread_pools:
  - "thread_pool.bulk.size: 2"
  - "thread_pool.bulk.queue_size: 1000"
elasticsearch_network_http_max_content_lengtht: 1024mb
elasticsearch_plugins:
  - { name: 'mobz/elasticsearch-head' }
elasticsearch_discovery_zen_ping_multicast_enabled: "false"
elasticsearch_max_locked_memory: "unlimited"
elasticsearch_network_host: "127.0.0.1"
```

## CentOS and Elastisearch version 6

```
# elasticsearch role

elasticsearch_version: "6.5.4'"
elasticsearch_java_home: "/usr/lib/jvm/jre-1.8.0"
elasticsearch_heap_size: "1g"
elasticsearch_max_open_files: "65535"
elasticsearch_timezone: "UTC"
elasticsearch_node_max_local_storage_nodes: "1"
elasticsearch_index_mapper_dynamic: "true"
elasticsearch_memory_bootstrap_mlockall: "true"
elasticsearch_install_java: "true"
elasticsearch_thread_pools:
  - "thread_pool.bulk.size: 2"
  - "thread_pool.bulk.queue_size: 1000"
elasticsearch_network_http_max_content_lengtht: 1024mb
elasticsearch_plugins:
  - { name: 'mobz/elasticsearch-head' }
elasticsearch_discovery_zen_ping_multicast_enabled: "false"
elasticsearch_max_locked_memory: "unlimited"
elasticsearch_network_host: "127.0.0.1"
```
