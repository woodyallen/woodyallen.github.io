---
layout: post
title: Raspberry Pi Zero W
---

He adquirido recientemente la nueva Raspberry Pi Zero, esta nueva versión W, tiene Wifi y Bluetooth y todo por 10€, aquí las características.

[https://www.raspberrypi.org/blog/raspberry-pi-zero-w-joins-family/]

En casa tengo una Raspberry Pi model 3, que es un modelo más potente y lo uso junto al Apple TV mediante Plex como centro multimedia, lo que no tengo en mis canales de streaming Netflix y HBO que religiosamente pago, lo tengo en mi Raspberry 3.

Al igual que su hermana mayor la Raspberry Zero la he configurado sin teclado ni monitor, y accedo mediante SSH y FTP para el uso diario.

En concreto la Zero es para trastear y aún no tiene un uso concreto pero estoy alucinando que es todo un ordenador por 10€.

Los pasos que he seguido para configurarlos son bastante sencillos, me he bajado la última imagen de Raspbian, la de marzo de 2017, ya que la anterior no viene preparada con WIFI ni BT para la Zero.

El siguiente paso que hice lo tomé de este blog que me fue super útil para arrancar desde un portátil la Zero mediante USB

http://blog.gbaman.info/?p=791

Ademas en la tarjeta SD hay que crear en la carpeta BOOT un archivo con nombre ssh vacío para poder habilitar el acceso SSH ya que viene capado por defecto.

Dos enlaces mas para la configuración de la WIFI en la ZERO

http://raspberrypi.stackexchange.com/questions/37920/how-do-i-set-up-networking-wifi-static-ip-address/37921#37921

http://caffinc.github.io/2016/12/raspberry-pi-3-headless/

