---
layout: post
title: Jmeter, лучшие практики
date: '2017-10-20 18:00:00'
tags:
- linux
- network
---



$ ifconfig -a
$ sudo nano /etc/network/interfaces

# Configuración de dirección IP dinámica para el interfaz eth0
auto eth0
iface eth0 inet dhcp

$ sudo /etc/init.d/networking restart

$ sudo ifconfig eth0 down
$ sudo ifconfig eth0 up

ethtool eth0