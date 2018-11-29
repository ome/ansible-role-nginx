Nginx
=====

Install upstream Nginx.

TODO: Add configuration options.


Role Variables
--------------

- `nginx_keep_default_configs`: If `true` keep the default site configuration files in `nginx/conf.d`, default `false` (disable them)

Log rotation:

- `nginx_logrotate_interval`: Rotate log files at this interval, default `daily`
- `nginx_logrotate_backlog_size`: Number of backlog files to keep, default `366`
- `nginx_stable_repo`: If `false` use the mainline instead of stable repo, default `true`


Author Information
------------------

ome-devel@lists.openmicroscopy.org.uk
