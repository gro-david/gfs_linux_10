---
marp: true
class: invert
---

---
<!-- paginate: false -->
![bg](https://ucarecdn.com/38ae1b9c-5544-4ab1-8f4e-25c5705bb15d/)
<!-- 
macOs?
-->


---
![bg](https://libre2news.files.wordpress.com/2021/04/screenshotfrom2021-03-3123-29-06.png?w=1024)
<!-- 
Windows?
-->
---
# Linux <!--fit-->

---

![bg](https://upload.wikimedia.org/wikipedia/commons/thumb/9/97/GNOME_Shell.png/1200px-GNOME_Shell.png)
<!-- 
GNOME
-->

---
![bg](https://kde.org/announcements/plasma/5/5.27.0/fullscreen_with_apps.png)
<!-- 
KDE Plasma
-->

---
# Themen
- Was ist Linux?
- Geschichte
- Aufbau
- Distros
- Befehle
- Vor- und Nachteile

---
## Was ist Linux?

- OS <!--Genauer: ein kernel-->
- Bekannt für Stabilität, Sicherheit und Flexibilität

<!--frage: relevant für die nächste folie: wie viele haben android-->

---
## Aber niemand benutzt Linux!!
- 96,3 % der Webserver <!--top eine Million-->
- 100% der Top 500 Supercomputer
- 83,1% der Smartphones
 

---
![bg right:35% h:100%](https://cdn.britannica.com/99/124299-050-4B4D509F/Linus-Torvalds-2012.jpg)
## Geschichte von Linux

- 1991 von Linus Torvalds entwickelt <!--Motivation: keine unterstützung für sein CPU-->
<!--Name: Linus+Unix = Linux-->
- Große Gemeinschaft von Entwicklern und Benutzern

---
![bg vertical right:35% w:45%](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/142px-Tux.svg.png)
![bg vertical right:35% w:45%](https://upload.wikimedia.org/wikipedia/en/thumb/2/22/Heckert_GNU_white.svg/172px-Heckert_GNU_white.svg.png)
## Linux oder GNU/Linux?

- Namenskonflikt in der Community <!--GNU/Linux vs Linux-->
- wichtige Komponente von GNU 
<!--GNU ist ein Betriebssystem, Kernel schlecht-->
<!--GNU komponente auch von Win und Mac benutzt-->
<!--GNU/Linux: korrekt, Linux: Einfacher-->
---

## Aufbau von Linux
- Modular <!--Manche Module vom distro: Pacman, manche serlber: Desktop, Displaymanager, Windowmanager-->
- Hierarchisches Dateisystem <!--Keine Drives, später mehr-->
- Desktop-Umgebung zur Interaktion mit dem Betriebssystem
<!--Desktop-Env = GUI. Bsp: Gnome, xfce, und der Beste: Plasma-->
- Paketmanager = App Store  <!--die ersten App stores-->

---
## Dateisystem

    root
      ├── bin         # essentielle Binärdateien 
      ├── boot        # essentielle Dateien für den Bootvorgang
      ├── dev  
      ├── etc         # "Editable Text Config"
      ├── home
          ├── user1   # Benutzerdaten
          ├── user2
      ├── lib
      ├── media
      ├── mnt
      ├── opt         # optionale Software
      ├── proc
      ├── root
      ├── run
      ├── sbin        # Binärdateien für Administratoren
      ├── srv
      ├── sys
      ├── tmp
      ├── usr
          ├── bin     # installierte Applikationen
      ├── var


---
## Wichtigste Befehle

- Command-Line-Interface (CLI) zur interaktion
- Wichtige Befehle:
  - `ls`: Listet alle Dateien
  - `cd`: Wechselt das Verzeichnis
  - `sudo`: Führt Befehl als Administrator aus
<!--sehr wichting: cmd muss nicht unbedingt angefasst werden (GUI für fast alles), aber schneller und einfacher-->
---
![ bg right:25% vertical w:200px](https://avatars.githubusercontent.com/u/4673648?s=280&v=4)
![bg w:200px](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/UbuntuCoF.svg/512px-UbuntuCoF.svg.png?20120210072525)
![bg w:200px](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Fedora-logo.svg/2048px-Fedora-logo.svg.png)
## Distros

- Viele verschiedene Linux-Distributionen
- Beliebte Distros:
  - Ubuntu <!--Anfänger Distro, apt PM-->
  - Arch Linux <!--Distro für fortgeschrittene: nur ein shell. GUI muss seperat installiert werden, Pacman PM, ich benutze arch-->
  - Manjaro <!--basiert auf arch, einfachere installation, für alle-->
- Unterschiedliche Funktionen und Zielgruppen

---
# Vor- und Nachteile von Linux
### Vorteile

- Frei und open-source
- Sicher und stabil <!--Sicherer: viren entwickeln lohnt sich weniger. Mehr entwickler suchen nach bugs-->
- Flexibel
- Große Gemeinschaft von Entwicklern und Benutzern <!--nette community hilft gerne-->
- Ressourceneffizient
<!--Software installation sicherer, scheller, nicht auf random websiten nach .exes suchen, offizielle repos-->
<!--Live-testing vor installation-->
<!--installation auf usb möglich **usb zeigen**-->
<!--display nicht unbedingt benötigt, alles kann remote aus cmd gemacht werden-->

### Nachteile
<!--Desktops gehen mit multi-monitor setups schlechter um-->

- Umstieg 
- Software wechsel nötig <!--zb von MS Office auf OnlyOffice-->

---

# Für wen eignet sich Linux?

- Alle, die etwas Neues ausprobieren wollen
- Jeder, der Freiheit und Anpassbarkeit schätzt
<!--besonders für Entwickler und Programmierer-->
<!--Alternativen kennenlernen wollen-->
<!--für wen nicht?: Gamer oder MS Office, 
wenn bei alter routine bleiben, 
nichts nachschauen-->

# Welches Distro?
- Manjaro:
  - pacman
  - einfache Installation
  <!-- KDE-Desktop am besten anpassbar, selber nachschauen, eigene Meinung-->


---
## Anfänger Fehler

- Distro nach aussehen
- Die Annahme dass die Wechsel nur kosmetisch sind
- Angst vor der Konsole
<!--
- egal welches distro, kann angepasst werden
  Desktops seperat installiert
- Viele unterscchiede wie zb Filesystem
- Einfach commands abschreiben

-->
---
# Persönliche Erfahrungen

- Viel schneller
- Manche Bugs <!--Selber schuld-->
<!--interessante erfahrung, sieht besser aus-->


---
![bg w:175%](https://preview.redd.it/bbvwgctz82191.png?auto=webp&s=e82c294ff4a8f7ab0558c8e80ac5ba4165c45e91)

<!--Quellen:
https://wiki.archlinux.org/
https://en.wikipedia.org/wiki/GNU/Linux_naming_controversy
https://en.wikipedia.org/wiki/Linux
https://en.wikipedia.org/wiki/GNU
https://en.wikipedia.org/wiki/Linux_distribution
-->