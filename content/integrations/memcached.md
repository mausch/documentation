---
title: Datadog-Memcached Integration
integration_title: Memcached
git_integration_title: memcached
kind: integration
---
### Overview

Connect Memcached to Datadog in order to:

  * Visualize its performance
  * Correlate the performance of Memcached with the rest of your applications

<%= insert_example_links(conf:"mcache", check:"mcache")%>

## Metrics

<%= get_metrics_from_git() %>
The following metrics are collected by default with the Memcache integration:

    memcache.bytes
    memcache.bytes_read
    memcache.bytes_written
    memcache.cmd_get
    memcache.cmd_set
    memcache.connection_structures
    memcache.curr_connections
    memcache.curr_items
    memcache.evictions
    memcache.get_hits
    memcache.get_misses
    memcache.limit_maxbytes
    memcache.pointer_size
    memcache.rusage_system
    memcache.rusage_user
    memcache.threads
    memcache.total_connections
    memcache.total_items

[1]: https://github.com/DataDog/dd-agent/blob/master/conf.d/mcache.yaml.example
[2]: https://github.com/DataDog/dd-agent/blob/master/checks.d/mcache.py


