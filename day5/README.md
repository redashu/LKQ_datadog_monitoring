### Revision 

<img src="ddv1.png">

### datadog agent host os vs container based agent 

<img src="ddv2.png">

## on linux agent 

### checking docker and container status 

```
ec2-user@ip-172-31-92-124 ~]$ sudo -i
[root@ip-172-31-92-124 ~]# systemctl status docker
● docker.service - Docker Application Container Engine
     Loaded: loaded (/usr/lib/systemd/system/docker.service; disabled; preset: disabled)
     Active: active (running) since Fri 2024-10-18 07:53:32 UTC; 2min 10s ago
TriggeredBy: ● docker.socket
       Docs: https://docs.docker.com
    Process: 2273 ExecStartPre=/bin/mkdir -p /run/docker (cod

=>> to start docker on vm start 

systemctl enable --now  docker


===> checking datadog agent status 

systemctl status datadog-agent
● datadog-agent.service - Datadog Agent
     Loaded: loaded (/usr/lib/systemd/system/datadog-agent.service; enabled; preset: disabled)
     Active: active (running) since Fri 2024-10-18 07:53:27 UTC; 4min 14s ago
   Main PID: 2064 (agent)
      Tasks: 8 (limit: 4658)
     Memory: 268.6M
```
