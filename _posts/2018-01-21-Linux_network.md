---
layout: post
title: Настройка сети linux
date: '2018-01-21 18:00:00'tags:
- linux
- network
---

## Вывести все сетевые интерфейсы:
```code 
$ ifconfig -a
$ sudo nano /etc/network/interfaces

## Configuración de dirección IP dinámica para el interfaz eth0

auto eth0
iface eth0 inet dhcp
```
$ sudo /etc/init.d/networking restart

$ sudo ifconfig eth0 down
$ sudo ifconfig eth0 up

ethtool eth0


#настройка сети
ifconfig up
ethtool <iface>
ifconfig <iface> dhcp
exampel /etc/network/interface