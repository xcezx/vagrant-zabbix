zabbix-agent [![Build Status](https://travis-ci.org/xcezx/ansible-zabbix-agent.svg?branch=master)](https://travis-ci.org/xcezx/ansible-zabbix-agent)
========

install and configutation zabbix-agent

Role Variables
--------------

- `zabbix_agent_install_packages`
- `zabbix_agent.settings.Alias`
- `zabbix_agent.settings.AllowRoot`
- `zabbix_agent.settings.BufferSend`
- `zabbix_agent.settings.BufferSize`
- `zabbix_agent.settings.DebugLevel`
- `zabbix_agent.settings.EnebleRemoteCommands`
- `zabbix_agent.settings.HostMetadata`
- `zabbix_agent.settings.HostMetadataItem`
- `zabbix_agent.settings.Hostname`
- `zabbix_agent.settings.HostnameItem`
- `zabbix_agent.settings.Include`
- `zabbix_agent.settings.ListenIP`
- `zabbix_agent.settings.ListenPort`
- `zabbix_agent.settings.LoadModule`
- `zabbix_agent.settings.LoadModulePath`
- `zabbix_agent.settings.LogFile`
- `zabbix_agent.settings.LogFileSize`
- `zabbix_agent.settings.LogRemoteCommands`
- `zabbix_agent.settings.MaxLinesPerSecond`
- `zabbix_agent.settings.PidFile`
- `zabbix_agent.settings.RefreshActiveChecks`
- `zabbix_agent.settings.Server`
- `zabbix_agent.settings.ServerActive`
- `zabbix_agent.settings.SourceIP`
- `zabbix_agent.settings.StartAgents`
- `zabbix_agent.settings.Timeout`
- `zabbix_agent.settings.UnsafeUserParameters`
- `zabbix_agent.settings.UserParameter`

Dependencies
------------

- `xcezx.zabbix-repository`

Example Playbook
-------------------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: xcezx.zabbix-agent }

License
-------

BSD
