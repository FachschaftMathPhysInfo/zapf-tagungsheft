# ZaPF Tagungsheft

Dieses Projekt erstellt das Tagungsheft für die [Zusammenkunft aller deutschsprachigen Physik Fachschaften im Sommersemester 2018 in Heidelberg](https://www.zapfinhd.de/), welche von der [Fachschaft MathPhysInfo](http://mathphys.info/) ausgerichtet wird.

## Mitarbeiten
Auf dem [Projektboard](https://github.com/FachschaftMathPhys/zapf-tagungsheft/projects/1) befinden sich diverse kleine Aufgaben, die noch erledigt werden müssen. Davon kann man sich einfach eines schnappen, ggf. daraus auch ein Issue erstellen und es dann einfach abarbeiten. Am liebsten auf einem eigenen Feature-Branch, der vom `develop` Branch auscheckt, damit am Ende ein schöner Pull-Request gestellt werden kann, dieser reviewed werden kann und wenn alle glücklich sind, das neue Feature in das Projekt eingebaut werden kann.

Bei neuen Dateien am besten in den ersten drei Zeilen
```latex
% !TEX TS-program = pdflatex
% !TEX encoding = UTF-8 Unicode
% !TEX ROOT = main.tex
```
einbinden, damit erkannt wird, das die ```main.tex``` die Hauptdatei ist. Die neuen Dateien am besten im `chapters` Odner und ggf. noch in einen entsprechenden Unterordner packen. In der Main Datei kann dann per `input{chapters/DATEINAME}` die neue Datei einbinden.

Falls du Hilfe brauchst, dann melde ich bei `trix@`.

Als Inspiration kann man sich das [Tagungsheft von Düsseldorf](http://zapf.wolfbyte.de/Tagungsheft.pdf) anschauen und selber Gedanken zu unserem [vorläufigen Inhaltsverzeichnis](https://github.com/FachschaftMathPhys/zapf-tagungsheft/blob/master/INHALT.md) machen.

## vorläufige Roadmap
* Deadline für externe Werbung: nächste ZaPFen, Unternehmen: 15. April 23:55 Uhr
* Redaktionsschluss intern: 15. April 23:55 Uhr
* anschließend Überarbeiten und Druck
* anschließend Überarbeiten und Druck

