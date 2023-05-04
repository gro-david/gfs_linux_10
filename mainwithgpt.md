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
- 
---
## Was ist Linux?

- OS
- Bekannt für Stabilität, Sicherheit und Flexibilität
<!--Wenn man von Linux redet redet man von GNU/Linux. Linux = Kernel. mehr später-->

<!--frage: relevant für die nächste folie: wie viele haben android-->

---
## Aber niemand benutzt Linux!!
- 96,3 % der Webserver <!--top eine Million-->
- 100% der Top 500 Supercomputer
- 83,1% der Smartphones

---
# Themen


---
## Was ist Linux?


---
![bg right:35% h:100%](https://cdn.britannica.com/99/124299-050-4B4D509F/Linus-Torvalds-2012.jpg)
## Geschichte von Linux

- 1991 von Linus Torvalds entwickelt <!--Motivation: keine unterstützung für sein CPU-->
<!--Name: Linus+Unix = Linux-->
- Gewann schnell an Popularität
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

---
![ bg right:25% vertical w:200px](https://avatars.githubusercontent.com/u/4673648?s=280&v=4)
![bg w:200px](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/UbuntuCoF.svg/512px-UbuntuCoF.svg.png?20120210072525)
![bg w:200px](https://upload.wikimedia.org/wikipedia/commons/thumb/b/bd/Fedora-logo.svg/2048px-Fedora-logo.svg.png)
## Distros

- Viele verschiedene Linux-Distributionen
- Beliebte Distros:
  - Ubuntu <!--Anfänger Distro, apt PM-->
  - Arch Linux <!--Distro für fortgeschrittene: nur ein shell. GUI muss seperat installiert werden, Pacman PM-->
  - Fedora <!--DNF PM, für fortgeschrittene-->
- Unterschiedliche Funktionen und Zielgruppen

---
# Vor- und Nachteile von Linux
### Vorteile

- Frei und open-source
- Sicher und stabil <!--Sicherer: viren entwickeln lohnt sich weniger. Mehr entwickler suchen nach bugs-->
- Flexibel
- Große Gemeinschaft von Entwicklern und Benutzern
- Ressourceneffizient
<!--Software installation sicherer, nicht auf random websiten nach .exes suchen, offizielle repos-->
<!--Live-testing vor installation-->

### Nachteile
<!--Desktops gehen mit multi-monitor setups schlechter um-->

- Umstieg 
- Software wechsel nötig

---

# Für wen eignet sich Linux?

- Alle, die etwas Neues ausprobieren wollen
- Jeder, der Freiheit und Anpassbarkeit schätzt
<!--esonders für Entwickler und Programmierer-->


---
## Anfänger Fehler

- Distro nach aussehen
- Denken dass es wie Windows ist
- Angst vor der Konsole
<!--
- egal welches distro, kann angepasst werden
  Desktops seperat installiert
- Einfach commands abschreiben
-->
---
# Persönliche Erfahrungen

- Viel schneller
- Manche Bugs <!--Selber schuld-->

---
<!--header: '' -->
![bg](https://repository-images.githubusercontent.com/458803330/fd027c0e-dcbb-4127-8670-7dd92566b808)

---
![bg w:175%](https://preview.redd.it/bbvwgctz82191.png?auto=webp&s=e82c294ff4a8f7ab0558c8e80ac5ba4165c45e91)