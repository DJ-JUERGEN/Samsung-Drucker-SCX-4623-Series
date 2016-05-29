 Samsung-Drucker-SCX-4623-Series
 Problem mit der Treiber-Installation

 Dies ist die Installationsdatei (install.sh) der Treiber aus der Datei "uld_v1.00.36_00.91.tar.gz" (Original von Samsung)
 Diese Datei lief auf meinem System (Ubuntu 16.04 LTS) zuerst nicht.
 Irgendwann nach Installation von "cups" (Netzwerkdrucker) und "xsane" (Scanner), liessen sich die Installationsdateien anstandslos starten.

 Fehlte ein Befehl/Kommando in meinem System ? Terminal meldete "Befehl nicht gefunden", das war's.
 
 Die kompletten Treiber und install-/uninstall-Dateien befinden sich im File "uld_v1.00.36_00.91.tar.gz"
 
 Auf einem zweiten Rechner mit Ubuntu 14.04 LTS läuft es (immernoch) genauso ab. Deshalb kann ich auf dem zweiten Rechner zwar inzwischen drucken, weil dies anscheinend mit "cups" genauso funktioniert, ohne die Treiber kann ich jedoch nicht scannen !
 
 Terminal meldet immer "command not found". Ich weiss aber nicht, welches Commando er nicht findet, oder kennt.
 
 LÖSUNG DES PROBLEMS:
 Achtet bitte darauf, allen ausführbaren Dateien (z.B. install.sh) im Ordner "uld" Ausführungsrecht zuzuweisen
 >> sudo chmod +x install.sh << 
 
 Ich hab das im Eifer des Gefechts übersehen, deswegen konnte ich auf dem zweiten Rechner die Installation nicht durchführen.
 Nach der Änderung funktionierte alles wunderbar !!
 
 
 
