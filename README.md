# convert-doc

Da das Importieren von doc bzw docx Dokumenten in Libreoffice manchmal Probleme im Layout verursacht,
muss man die proprietären Microsoft Office Dateien erst in das offene odt Format umwandeln.
Dies geschieht mit diesem Skript über den online-converter http://docspal.com, der intern Microsoft Office verwendet.

Folgende Umwandlungen werden unterstützt: 

  * odt  --> docx
  * doc  --> odt
  * doc  --> pdf
  * docx --> pdf

Das Debian Paket convert-doc.deb sollte wegen minimaler Abhängigkeiten
auf allen Debian-basierten Distributionen installierbar sein.
(Debian, Ubuntu , LinuxMint...)
Nach Installation des Pakets mit `sudo dpkg -i convert-doc.deb`
kann ein Dokument mit öffnen mit ausgewählt und umgewandelt werden.