# Ansible Loki install Role

An Ansible Role that installs [Grafana Loki](https://github.com/grafana/loki) on Linux.

##### Role Variables
Available variables with their default values are defined in defaults/main.yml.

##### Role Templates
1. **config-loki.yml.j2** - Loki config  
2. **loki.service.j2** - file for configure Loki as a service so that we can keep it running in the background  

##### LogCli install

An Ansible Tasks that installs [Grafana LogCLI](https://github.com/grafana/loki/blob/master/docs/getting-started/logcli.md) on Linux.

Set the value of the variable **install_logcli: 1** to install LogCLI

_defaults/main.yml:_
```
install_logcli: 1

```