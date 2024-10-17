### datadog account and agent revision 

<img src="rev1.png">

### datadog agent process and tags

<img src="tags.png">

### checking agent status on linux vm

```
 whoami
ec2-user
[ec2-user@ip-172-31-92-124 ~]$ sudo -i
[root@ip-172-31-92-124 ~]# systemctl status datadog-agent
● datadog-agent.service - Datadog Agent
     Loaded: loaded (/usr/lib/systemd/system/datadog-agent.service; enabled; preset: disabled)
     Active: active (running) since Thu 2024-10-17 07:37:41 UTC; 49s ago
   Main PID: 2080 (agent)
      Tasks: 8 (limit: 4658)
     Memory: 266.1M
        CPU: 1.377s
```

### Installing Docker on LInux machine 

```
yum install docker -y 

====>
 systemctl start docker 
[root@ip-172-31-92-124 ~]# systemctl status  docker 
● docker.service - Docker Application Container Engine
     Loaded: loaded (/usr/lib/systemd/system/docker.service; disabled; preset: disabled)
     Active: active (running) since Thu 2024-10-17 08:33:35 UTC; 7s ago
TriggeredBy: ● docker.socket

```
