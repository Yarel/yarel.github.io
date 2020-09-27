---
title: Escaneo y Enumeracion
author: Yarel Balcazar
date: 2020-09-27 14:00
categories: [Blogging, post]
tags: [Footprinting]
math: true
image: https://www.google.com/url?sa=i&url=http%3A%2F%2Fwww.lscvsystems.com%2Findex.php%2Fservicios%2Fseguridad-de-la-informacion%2Fhacking-etico&psig=AOvVaw32Vto5ziGedIxXolCzalIn&ust=1601297060516000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPD6sdGuiewCFQAAAAAdAAAAABAE
---

Este post hablamos un poco del footprinting, junto al footprinting el escaneo y la enumeracion donde son las fases de obtencion de informacion previas a un ataque

### **Escaneo**
  Proceso de localizacion de sistemas que esten en la red. Un Ethical hacker/Pentester utiliza este proceso para encontrar las IP de objetivos.
  Los siguientes datos ayudan al atacante a poder decidirse por el tipo de exploit a utilizar:

* Direccion de IP
* Sistema Operativo
* Servicios disponibles
* Aplicaciones instaladas

Segun la metodologia de un CEH existen tres tipos de escaneo:

- Escaneo de puertos: determina los puertos TCP/IP abiertos y disponibles
- Escaneo de Red: determina los host que se encuentren activos
- Escaneo de Vulnerabilidades: determina la existencia de vulnerabilidad conocidas en los host.
### **Enumeracion**
  Comienza apenas finalizado el escaneo y su objetivo es el de enumerar e identificar los nombres de los equipos,usuarios, y recursos compartidos entre otra informacion.

Metodologia CEH :

1. verificacion de sistemas vivos
2. comprobacion de puertos abiertos
3. servicios , identificaicon
4. Banner Grabbing / OS fingerprinting
5. Escaneo de vulnerabilidades
6. dibujar diagramas de red de host vulnerables
7. preparacion de Proxys
8. Ataque

Esta metodologia utilizado a la hora de conduir el proceso de escaneo de una red. Su principal objetvo, es el de asegurar que ningun sistema o vulnerabilidad es pasada por alto. 

---


