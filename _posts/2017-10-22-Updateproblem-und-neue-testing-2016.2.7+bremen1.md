---
layout: post
title:  "Updateproblem und neue Testing-Firmware 2016.2.7+bremen1"
author: SimJoSt
date:   2017-10-23 22:29:21 +0200
---
Es gibt eine neue testing-Firmware für die Knoten des Bremer Freifunks: 2016.2.7+bremen1  
Diese behebt ein Updateproblem, welches in der aktuellen Firmware existiert. Knoten mit wenig Arbeitspeicher sind am ehesten betroffen und hängen beim Updaten einfach fest. Der WLAN-, VPN- und Freifunk-Betrieb ist in diesem Zustand nicht mehr aktiv, aber nichts geht dauerhaft kaputt. Nach einmal vom Strom trennen nimmt der Knoten wieder den regulären Betrieb auf.  
Wird das Update zeitnah nach einem Neustart durchgeführt, so sollte dies Erfolgswahrscheinlichkeit verbessern.

Unabhängig davon wurde auch eine Änderung am IPv6-Netz vorgenommen. Im Changelog gibt es mehr Details zu den [Änderungen durch das Update auf 2016.2.7+bremen1](https://wiki.bremen.freifunk.net/Firmware/Changelog#freifunk-bremen-versionen_2016-2-7-bremen1).

Dieses Update wird in etwa zwei Wochen für die Testing-Knoten freigeschaltet. Wir wollten diese Stillhaltefrist für Knoten-Betreiber festlegen, die ihre Knoten manuell und kontrolliert updaten wollen, um dem Problem aus dem Weg zu gehen.  
Wenn für zwei weitere Wochen keine Probleme auftreten, werden wir das Update auch für die stable-Knoten verfügbar machen.

Dieses Update für den 2016.2.x-Zweig von Gluon ist eine Ausnahme, da die Autoupdater-Funktion recht essentiell ist. Sobald dieses Updateproblem im kompletten Netz von Freifunk Bremen gelöst ist, wollen wir die erste 2017.x-Version auf Basis von LEDE in Betrieb nehmen.

Frohes Freifunken!

*Für detaillierte Änderungen und Fehlerbehebungen lohnt sich wie immer ein Blick in unser [Firmware-Changelog](https://wiki.bremen.freifunk.net/Firmware/Changelog).*
