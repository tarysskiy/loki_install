# Ansible Loki install Role

An Ansible Role that installs [Grafana Loki](https://github.com/grafana/loki) on Linux.

##### Role Variables
Available variables with their default values are defined in defaults/main.yml.

##### Role Templates
1. **config-loki.yml.j2** - Loki config  
2. **loki.service.j2** - file for configure Loki as a service so that we can keep it running in the background  
