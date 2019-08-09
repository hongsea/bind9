## hongsea/bind9:1.0
Bind 
```
$ sudo docker pull hongsea/bind9:1.0
$ sudo mkdir -p /srv/docker/bind
$ sudo docker run --name bind -d --volume /srv/docker/bind:/data hongsea/bind9:1.0
$ sudo docker inspect bind |grep IPAddress	
  https://172.17.0.2:10000
```

