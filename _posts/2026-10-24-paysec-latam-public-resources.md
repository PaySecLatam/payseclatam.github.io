---
layout: post
title: "PaySec Latam | Public Resources"
author: PaySec Latam
date: 2026-10-24
tags: [recursos, nfc, bluetooth]
excerpt: "Siguiendo con las publicaciones de lo que hemos mostrado en la villa, esta vez compartimos tres herramientas: PAYGoat, el simulador de cobros con NFC para transporte público, y blestx para explorar comunicaciones BLE."
---

Siguiendo con las publicaciones de lo que hemos mostrado en la villa en los diferentes eventos, esta vez le toca a tres herramientas que ya han tenido su momento en vivo y que estaban listas para salir al mundo.

---

## PAYGoat

PAYGoat es una aplicación intencionalmente vulnerable para practicar seguridad en flujos de pago. La hemos llevado a varios eventos y siempre genera buen interés, así que tiene su propio repositorio donde la pueden clonar, romper y aprender del proceso. Si alguna vez has querido entender cómo se ven las fallas de lógica de negocio en aplicaciones financieras, este es un buen lugar para empezar.

🔗 [github.com/stuxctf/PAYGoat](https://github.com/stuxctf/PAYGoat)

---

## BusTerminal NFC Simulator

Este nació de una pregunta sencilla: ¿qué pasa exactamente cuando acercas una tarjeta a un lector de transporte público? El simulador replica ese flujo de cobro completo y permite ver la diferencia entre cómo responde una tarjeta RFID estándar, una DESFire y una tarjeta real de transporte. Lo mostramos en vivo en eventos y la gente siempre se sorprende de cuántas cosas pasan en ese intercambio que parece instantáneo.

Todavía estamos afinando algunos detalles antes del release oficial, pero el repositorio ya está disponible.

🔗 [github.com/PaySecLatam/BusTerminal-NFC-Simulator](https://github.com/PaySecLatam/BusTerminal-NFC-Simulator)

---

## blestx

Bluetooth Low Energy aparece cada vez más en terminales de pago, lectores y aplicaciones financieras, pero es una tecnología que se investiga mucho menos que NFC o EMV. blestx es una herramienta para explorar esas comunicaciones: qué se transmite, cómo está estructurado y dónde pueden existir riesgos. Todavía en desarrollo activo, pero ya está publicada para quien quiera echarle un ojo o contribuir.

🔗 [github.com/PaySecLatam/blestx](https://github.com/PaySecLatam/blestx)

---

Todo open-source, todo pensado para aprender en entornos controlados. Si tienes preguntas o encuentras algo interesante jugando con estas herramientas, escríbenos a [payseclatam@proton.me](mailto:payseclatam@proton.me) o búscanos en [LinkedIn](https://www.linkedin.com/in/stuxnet/).
