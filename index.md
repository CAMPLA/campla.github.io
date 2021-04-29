
 <p align="center">
  <img src="/assets/images/logo-trans-128x128.png" style="margin-right:150px;"/>
  <img src="/assets/images/lernstick.png" width="128"/>
</p>


CAMPLA wird an der Fachhochschule Nordwestschweiz in einem interdisziplinären Team entwickelt. Es steht für «Cloud Assessment Management Platform».  Zusammen mit dem Lernstick bildet CAMPLA ein ganzheitliches System zur Durchführung von digitalen Prüfungen. 

Das Ziel ist den Dozenten\*innen die Möglichkeit zu geben, Prüfungen auf den Notebooks der Studenten\*innen im Klassenraum oder einem Prüfungsraum durchzuführen. Dadurch entstehen neue Möglichkeiten zur Kompetenzüberprüfung und es kann mit neuen Prüfungsformen experimentiert werden. Zusätzlich wird dadurch sichergestellt, dass alle Studierenden unabhängig von ihrem eigenen Gerät dieselben Voraussetzungen für die Prüfung haben. 

In verschiedenen Lehrveranstaltungen an der Hochschule für Technik der FHNW finden Pilotversuche statt und es zeigen sich erste positive Resultate. Die Studenten*innen schätzen die digitale Prüfung, da diese Art der Prüfung näher an der Realität ist. Sprich bei Programmierprüfungen kann am Notebook programmiert werden und es besteht die Möglichkeit z.B. Simulationssoftware in Prüfungen nutzen. Die Dozenten\*innen haben die Möglichkeit Prüfungen online mit verschiedenen Vorlagen zu erstellen. Das Verteilen und Ausdrucken von Prüfungen fällt weg. Wenn die Prüfung abgeschlossen ist, können die Resultate vom Dozenten\*in heruntergeladen und direkt ausgewertet werden. 

Bei CAMPLA besteht die Möglichkeit Prüfungen mit oder ohne Unterlagen durchzuführen. Den Studenten\*innen wird die Möglichkeit geboten vor der Prüfung eigene Unterlagen in CAMPLA hochzuladen. Diese müssen von den Dozenten\*innen überprüft und akzeptiert werden. Anschliessend stehen die Unterlagen während der Prüfung zur Verfügung. 

In Abbildung 1 ist der Aufbau der CAMPLA Infrastruktur zu sehen. Bei einer Prüfung wird auf den Geräten der Studenten\*innen mit dem Lernstick ein Linux Betriebssystem gestartet. In dieser Umgebung loggen sich die Studenten\*innen über den Webbrowser bei CAMPLA ein. Nachdem sie den Code für ihre Prüfung eingegeben haben, wird die Verbindung mit einem virtuellen Computer in der Cloud hergestellt. Auf diesem Computer läuft Windows mit den benötigten Programmen für die Prüfung. Hier findet sich auch die Prüfung, die Prüfungsunterlagen der Dozenten\*innen und die Unterlagen der Studenten\*innen, falls diese im Vorfeld zugelassen und hochgeladen wurden. 

![Abbildung 1: Systemübersicht](/assets/images/studentExaminationSetup.png)

<span style="font-size: 8pt;color: gray">Abbildung 1: Systemübersicht</span>

Der Aufbau der CAMPLA Infrastruktur in Verbindung mit dem Lernstick dient der Vorbeugung von Betrugsversuchen. Die Verbindung zum Internet kann individuell konfiguriert oder ausgeschlossen werden. Dadurch wird die digitale Kommunikation zwischen den Studenten*innen erheblich erschwert. Durch die Signierung der Dateien nach dem Abschluss einer Prüfung wird die Rekurssicherheit der Prüfung sichergestellt.  

[Weitere Information zum Lernstick](https://www.digitale-nachhaltigkeit.unibe.ch/dienstleistungen/lernstick/index_ger.html)

**Projektverantwortliche**
- Niklaus Lang (niklaus.lang@fhnw.ch)
- Norbert Hofmann (norbert.hofmann@fhnw.ch)

**Entwicklung**
- Lernstick: Ronny Standtke (ronny.standtke@bfh.ch) 
- CAMPLA: Simon Kaspar (simon.kaspar@fhnw.ch)

**Beteiligte Hochschulen**
 <p align="center">
  <img src="/assets/images/logo-fhnw.jpg" style="margin-right:150px;" height="80" />
  <img src="/assets/images/logo-uni-kiel.png" height="80"/>
</p>
