Description
===========

Installs and configures Logstash (http://logstash.net/) agent with the jar.

Attributes
==========

* `node["logstash"]["package_url"]` - URL to monolithic logstash jar. Defaults to logstash-1.1.0-monolithic.jar.
* `node["logstash"]["package_checksum"]` - sha256sum of the monolithic jar. Defaults to above checksum.
* `node['logstash']['install_path']` - location where Logstash jar is installed. Default `/usr/local/logstash`.
* `node['logstash']['config_path']` - location where Logstash config files are stored. Default `/etc/logstash`.
* `node['logstash']['log_path']` - location where Logstash log files are written. Default `/var/log/logstash`.