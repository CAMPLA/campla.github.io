---
title: CAMPLA / Lernstick
description: Ein ganzheitliches System zur Durchführung von digitalen Prüfungen
---
 <p align="center">
  <img src="/assets/images/logo-trans-128x128.png" style="margin-right:150px;"/>
  <img src="/assets/images/lernstick.png" width="128"/>
</p>

[English Version](/en.md)

CAMPLA wird an der Fachhochschule Nordwestschweiz in einem interdisziplinären Team entwickelt. Es steht für «Cloud Assessment Management Platform».  Zusammen mit dem Lernstick bildet CAMPLA ein ganzheitliches System zur Durchführung von digitalen Prüfungen. 

Das Ziel ist es den Lehrenden die Möglichkeit zu geben, auf den Notebooks der Studierenden (Bring Your Own Device) den E-Prüfungen vor Ort (E-Assessments) neue Möglichkeiten des kompetenzorientierten Prüfens zu geben. Die im Unterricht auf den eigenen Geräten der Studierenden erarbeiten Fertigkeiten sollen möglichst nahtlos mit einer Kompetenzüberprüfung validiert werden können.  Die Studierenden schätzen E-Assessments mit CAMPLA/Lernstick, da damit elektronische Prüfungsformate denkbar sind, die näher an der (Arbeits-)Realität liegen und papierlos sind. Zudem können durch den Einsatz der Plattform CAMPLA (ohne Lernstick) bereits während der Veranstaltung für alle Studierenden gleiche Bedingungen bezüglich Software (und Software-Lizenzen) geschaffen werden. Auch formatives Prüfen zu bestimmten Punkten während dem Semester ist über CAMPLA ohne die Benutzung des Lernsticks möglich. Die Dozenten\*innen haben die Möglichkeit Prüfungen online mit verschiedenen Vorlagen zu erstellen. Das Verteilen und Ausdrucken von Prüfungen fällt weg. Wenn die Prüfung abgeschlossen ist, können die Resultate vom Dozenten\*in heruntergeladen und direkt ausgewertet werden. 

Bei CAMPLA besteht die Möglichkeit Prüfungen mit oder ohne Unterlagen durchzuführen. Den Studenten\*innen wird die Möglichkeit geboten vor der Prüfung eigene Unterlagen in CAMPLA hochzuladen. Diese müssen von den Dozenten\*innen überprüft und akzeptiert werden. Anschliessend stehen die Unterlagen während der Prüfung zur Verfügung. 

In Abbildung 1 ist der Aufbau der CAMPLA Infrastruktur zu sehen. Bei einer Prüfung wird auf den Geräten der Studenten\*innen mit dem Lernstick ein Linux Betriebssystem gestartet. In dieser Umgebung loggen sich die Studenten\*innen über den Webbrowser bei CAMPLA ein. Nachdem sie den Code für ihre Prüfung eingegeben haben, wird die Verbindung mit einem virtuellen Computer in der Cloud hergestellt. Auf diesem Computer läuft Windows mit den benötigten Programmen für die Prüfung. Hier findet sich auch die Prüfung, die Prüfungsunterlagen der Dozenten\*innen und die Unterlagen der Studenten\*innen, falls diese im Vorfeld zugelassen und hochgeladen wurden. 

![Abbildung 1: Systemlandschaft](/assets/images/studentExaminationSetupDeutsch.png)

<span style="font-size: 8pt;color: gray">Abbildung 1: Systemlandschaft</span>

Der Aufbau der CAMPLA Infrastruktur in Verbindung mit dem Lernstick dient der Vorbeugung von Betrugsversuchen. Die Verbindung zum Internet kann individuell konfiguriert oder ausgeschlossen werden. Dadurch wird die digitale Kommunikation zwischen den Studenten*innen erheblich erschwert. Durch die Signierung der Dateien nach dem Abschluss einer Prüfung wird die Rekurssicherheit der Prüfung sichergestellt. Darüber hinaus wird an der Möglichkeit gearbeitet, das verwendete Prüfungssystem durch den integrierten Sicherheitschip (TPM) abzusichern. Dieses Verfahren nennt sich Remote Attestation und stellt sicher, dass das gestartet Prüfungssystem nicht manipuliert wurde. Dies erschwert, das Betrügen, während einer Prüfung nochmals erheblich.

**Anwendungsbeispiele**

![Use Cases FHNW](/assets/images/use-cases-fhnw.png)

**Projektverantwortliche**
- Niklaus Lang (niklaus.lang@fhnw.ch)
- Norbert Hofmann (norbert.hofmann@fhnw.ch)
- Marcel Steiner (marcel.steiner@fhnw.ch)

**Entwicklung**
- **Lernstick:** Ronny Standtke (ronny.standtke@bfh.ch), Thore Sommer (thore.sommer@fhnw.ch)
- **CAMPLA:** Simon Kaspar (simon.kaspar@fhnw.ch)
- **Remote Attestation / Keylime:** Thore Sommer (thore.sommer@fhnw.ch)

**Prozesse & Didaktik**
- Merima Hotic (merima.hotic@fhnw.ch)
- Stefan Walter (stefan.walter@fhnw.ch)
- Cinzia Garcia (cinzia.garcia@fhnw.ch)

**Weiterführende Links**
- [Weitere Information zum Lernstick](https://www.digitale-nachhaltigkeit.unibe.ch/dienstleistungen/lernstick/index_ger.html)
- [CAMPLA SWITCHtube Kanal](https://tube.switch.ch/channels/65fa27a6)

**Anfragen**

Bitte senden Sie Anfragen zu CAMPLA/Lernstick an die folgende E-Mail Adresse:

[campla.services@fhnw.ch](mailto:campla.services@fhnw.ch)

**Beteiligte Hochschulen**

 <p align="center">
  <img src="/assets/images/logo-fhnw.jpg" style="margin-right:150px;" height="60" />
  <img src="/assets/images/logo-bfh.png" style="margin-right:150px;" height="95"/>
  <img src="/assets/images/logo-uni-kiel.png" height="60"/>
</p>

