## Datadog Revision 

<img src="rev1.png">

### datadog agent more info 

<img src="rev2.png">

## datadog agent -- Golang vs Python understanding 

<img src="lang.png">

### datadog Login URL 


```
https://app.datadoghq.com/
```

[click_here](https://app.datadoghq.com/)

### datadog account with their official data centre region 

<img src="reg.png">

## Intro metrics in datadog 

<img src="met.png">

## Metrics components in datadog 

<img src="met1.png">

### by default CPU metrics collected by datadog agent collector 

<img src="cpu1.png">

### system vs user cpu metrics 

<img src="cpu2.png">

## Grouping and filtering concept in datadog 

<img src="ddf.png">

## tags info 

<img src="tag1.png">

### tag limits 

<img src="tag2.png">

### Tags changing places 

<img src="tag3.png">

### Reserver tags key

[click_here](https://docs.datadoghq.com/getting_started/tagging/)

<img src="tag4.png">

### sample tag changing data in yaml file 

```
tags:
  - "system:local_windows"
  - "microsoft:w10"
  - "ashu:mylaptop_2"
```

### login to linux machine with root user 

```
[ec2-user@ip-172-31-92-124 ~]$ whoami
ec2-user
[ec2-user@ip-172-31-92-124 ~]$ sudo -i
[root@ip-172-31-92-124 ~]# whoami
root
[root@ip-172-31-92-124 ~]# 

```

### open file 

```
nano  /etc/datadog-agent/datadog.yaml 

===>
datadog-agent configcheck 
===>

systemctl restart datadog-agent
```

### to verify tags 

```
datadog-agent status

```