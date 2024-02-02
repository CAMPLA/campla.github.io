---
title: CAMPLA / Lernstick
description: Ein ganzheitliches System zur Durchführung von digitalen Prüfungen
---
 <p align="center">
  <img src="/assets/images/logo-trans-128x128.png" style="margin-right:150px;"/>
  <img src="/assets/images/lernstick_logo.svg" width="128"/>
</p>

[English Version](/en.md)

CAMPLA wird an der Fachhochschule Nordwestschweiz in einem interdisziplinären Team entwickelt. Es steht für «Cloud Assessment Management Platform».  Zusammen mit dem Lernstick bildet CAMPLA ein ganzheitliches System zur Durchführung von digitalen Prüfungen. 

Das Ziel ist es den Lehrenden die Möglichkeit zu geben, auf den Notebooks der Studierenden (Bring Your Own Device) den E-Prüfungen vor Ort (E-Assessments) neue Möglichkeiten des kompetenzorientierten Prüfens zu geben. Die im Unterricht auf den eigenen Geräten der Studierenden erarbeiten Fertigkeiten sollen möglichst nahtlos mit einer Kompetenzüberprüfung validiert werden können.  Die Studierenden schätzen E-Assessments mit CAMPLA/Lernstick, da damit elektronische Prüfungsformate denkbar sind, die näher an der (Arbeits-)Realität liegen und papierlos sind. Zudem können durch den Einsatz der Plattform CAMPLA (ohne Lernstick) bereits während der Veranstaltung für alle Studierenden gleiche Bedingungen bezüglich Software (und Software-Lizenzen) geschaffen werden. Auch formatives Prüfen zu bestimmten Punkten während dem Semester ist über CAMPLA ohne die Benutzung des Lernsticks möglich. Die Dozent\*innen haben die Möglichkeit Prüfungen online mit verschiedenen Vorlagen zu erstellen. Das Verteilen und Ausdrucken von Prüfungen fällt weg. Wenn die Prüfung abgeschlossen ist, können die Resultate von Dozierenden heruntergeladen und direkt ausgewertet werden. 

Bei CAMPLA besteht die Möglichkeit Prüfungen mit oder ohne Unterlagen durchzuführen. Den Student\*innen wird die Möglichkeit geboten vor der Prüfung eigene Unterlagen in CAMPLA hochzuladen. Diese müssen von den Dozent\*innen überprüft und akzeptiert werden. Anschliessend stehen die Unterlagen während der Prüfung zur Verfügung. 

In Abbildung 1 ist der Aufbau der CAMPLA Infrastruktur zu sehen. Bei einer Prüfung wird auf den Geräten der Student\*innen mit dem Lernstick ein Linux Betriebssystem gestartet. In dieser Umgebung loggen sich die Student\*innen über den Webbrowser bei CAMPLA ein. Nachdem sie den Code für ihre Prüfung eingegeben haben, wird die Verbindung mit einem virtuellen Computer in der Cloud hergestellt. Auf diesem Computer läuft Windows mit den benötigten Programmen für die Prüfung. Hier findet sich auch die Prüfung, die Prüfungsunterlagen der Dozent\*innen und die Unterlagen der Student\*innen, falls diese im Vorfeld zugelassen und hochgeladen wurden. 

![Abbildung 1: CAMPLA Systemlandschaft](/assets/images/studentExaminationSetupDeutsch.png)

<span style="font-size: 8pt;color: gray">Abbildung 1: CAMPLA Systemlandschaft</span>

Der Aufbau der CAMPLA Infrastruktur in Verbindung mit dem Lernstick dient der Vorbeugung von Betrugsversuchen. Die Verbindung zum Internet kann individuell konfiguriert oder ausgeschlossen werden. Dadurch wird die digitale Kommunikation zwischen den Student\*innen erheblich erschwert. Durch die Signierung der Dateien nach dem Abschluss einer Prüfung wird die Rekurssicherheit der Prüfung sichergestellt. Darüber hinaus wird an der Möglichkeit gearbeitet, das verwendete Prüfungssystem durch den integrierten Sicherheitschip (TPM) abzusichern. Dieses Verfahren nennt sich Remote Attestation und stellt sicher, dass das gestartet Prüfungssystem nicht manipuliert wurde. Dies erschwert, das Betrügen, während einer Prüfung nochmals erheblich.

**Anwendungsbeispiele**

| Hochschule | Kompetenzen | Tools/LMS | Status |
| ---------- | ------------ | --------- | ----- |
| **Hochschule für Wirtschaft** |Studierende der Wirtschaft lernen den Umgang mit Daten, können diese mit für Geschäftsanalysen geeigneten Tools analysieren und datengetriebene Entscheidung unterstützen. | Power Bi, Excel | Bereits mit CAMPLA/Lernstick durchgeführt |
| **Hochschule für Life Sciences** | Studierende der Hochschule für Life Sciences können Aufnahmen der Mikroskopie sowie anderer bildgebenden Verfahren analysieren und beurteilen. | Matlab, Moodle | Bereits mit CAMPLA/Lernstick durchgeführt |
| **Pädagogische Hochschule** | Studierende der Pädagogischen Hochschule können eine Lese-, Hör- und Sprachverständnisprüfung in ihrem eigenen Tempo (d.h. asynchrone Start/Stop-Möglichkeiten von Audio- und Videosequenzen) lösen. | Moodle (Lesen, Sprechen, Hören) | Bereits mit CAMPLA/Lernstick durchgeführt |
| **Hochschule für Technik** | Studierende der Technik können reale elektronische Regelungen modellieren und simulieren. | Matlab, Scilab | Bereits mit CAMPLA/Lernstick durchgeführt |
| **Hochschule für Gestaltung und Kunst** | Studierende der Hochschule für Gestaltung und Kunst können gezielt Bildmaterial bearbeiten und weiterentwickeln. | Bildverarbeitungsprogramme | dee für Durchführung mit CAMPLA/Lernstick |
| **Hochschule für Musik** | Studierende der Hochschule für Musik können passend zu einem Thema ein Jingle entwerfen. | Aufnahme sowie Audioverarbeitungsprogramme | Idee für Durchführung mit CAMPLA/Lernstick |

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
- [Weitere Information zum Lernstick](https://www.lernstick.ch)
- [Blog-Gastbeitrag zu CAMPLA/Lernstick im Hochschulforum Digitalisierung](https://hochschulforumdigitalisierung.de/de/blog/campla-lernstick)
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

