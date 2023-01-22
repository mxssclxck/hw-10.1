# 10.1 «Keepalived/vrrp» - НиконоровДА FOPS-6

## Задание 1

*Разверните топологию из лекции и выполните установку и настройку сервиса Keepalived.*

```
vrrp_instance test {
state "name_mode"
interface "name_interface"
virtual_router_id "number id"
priority "number priority"
advert_int "number advert"
authentication {
auth_type "auth type"
auth_pass "password"
}
unicast_peer {
"ip address host"
}
virtual_ipaddress {
"ip address host" dev "interface" label "interface":vip
}
}
```

![alt text](https://github.com/mxssclxck/hw-10.1/blob/main/img/1.png)

![alt text](https://github.com/mxssclxck/hw-10.1/blob/main/img/2.png)

![alt text](https://github.com/mxssclxck/hw-10.1/blob/main/img/3.png)

![alt text](https://github.com/mxssclxck/hw-10.1/blob/main/img/4.png)



