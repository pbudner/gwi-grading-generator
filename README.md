# Case Study – Grundlagen Wirtschaftsinformatik
Dieses Repository dient als Grundlage für die praktische Case Study im Kurs 'Grundlagen der Wirtschaftsinformatik' an der Universität zu Köln.

Innerhalb dieses Repositories befindet sich im Ordner _data_ die Datei _students.txt_. In der pro Zeile ein zufällig erzeugter Studentenname abgelegt ist. Falls das Notebook dieses Repositorys in Google CoLab ausgecheckt wird, muss zudem der erste Code-Block ausgeführt werden, um die Daten (_students.txt_) zu erhalten.

## Problemstellung
Es soll nun ein Code entwickelt werden, der die Datei einliest und für jeden Student eine Schulnote zwischen 1 und 6 würfelt. Das Ergebnis soll schließlich in eine neue CSV-Datei (mit dem Komma (,) als Trennzeichen) mit dem Namen _noten.csv_ abgespeichert werden. Die Zieldatei sollte dann in etwa so aussehen:
```
name,note
Max Mustermann,1
Thomas Müller,4
...
```
Die CSV-Datei kann schließlich dann zur weiteren Verarbeitung (bspw. Import in das Benotungssystem der Universität) genutzt werden. 

## Lösung
Die Lösung gilt es nun zu erarbeiten. Ihr könnt dafür das Jupyter-Notebook _code.ipynb_ aufrufen und dort den entsprechenden Code einfügen und ausführen.

Viel Spaß!

## Tipp
Beim einlesen der Zeilen in Dateien liest Python zusätzlich den Zeilenumbruch (\n) mit ein, den ihr entfernen müsst, wenn ihr mit dem Studentennamen arbeitet.