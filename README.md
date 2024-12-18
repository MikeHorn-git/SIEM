# Description

A SIEM (Security Information and Event Management) playground of ELK Stack (Elasticsearch, Logstash, Kibana) and Wazuh. With Agent VMs and Wazuh rulesets.

# VMs

* Arch (Agent): 192.168.56.30
* Debian (Agent) : 192.168.56.40
* ELK (Server): 192.168.56.25
* Wazuh (Manager) : 192.168.56.10

# Requirements

* Vagrant
* VirtualBox

# Installation

```bash
git clone https://your-repo-url.git
cd SIEM/Vagrantfiles
```

## Example

```bash
cd ELK
vagrant up
```

# Rulesets

Wazuh samples rules.

* 0010-rules_config.xml
* 0040-auditd_decoders.xml

# Known Issues

```bash
echo 3 | sudo tee /proc/sys/vm/drop_caches
```
