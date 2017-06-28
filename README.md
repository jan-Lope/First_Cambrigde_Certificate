# First Cambrigde Certificate
My Exercises for the First Cambrigde Certificate (in German)

## Generierte PDF- HTML- und TXT-Dateien


[FCE-lessons.pdf](https://github.com/jan-Lope/First_Cambrigde_Certificate/blob/gh-pages/FCE-lessons.pdf)  
Generiertes Buch (A4)  

[FCE-lessons-booklet.pdf](https://github.com/jan-Lope/First_Cambrigde_Certificate/blob/gh-pages/FCE-lessons-booklet.pdf)  
Generieretes Booklet (A5). 
Bei der Booklet-Version werden jeweils zwei Seiten auf eine A4-Seite abgebildet, so dass ein daraus ein Booklet (A5) erstellt werden kann. Dazu werden erst alle ungeraden Seiten ausgedruckt. Dann legt man die Blätter wieder ins Papierfach zurück und druckt alle geraden Seiten in absteigender Reihenfolge aus. 

[HTML-Version](https://htmlpreview.github.io/?https://raw.githubusercontent.com/jan-Lope/First_Cambrigde_Certificate/gh-pages/FCE-lessons/index.html)  



### Source Codes

Die PDF- und HTML- Dateien werden automatisch aus den Latex-Dateien per [travis-ci.org](https://travis-ci.org/jan-Lope/First_Cambrigde_Certificate) generiert.

Die Latex-Datei und die anderen Dateien sind in [Github](https://github.com/jan-Lope/First_Cambrigde_Certificate) veröffentlicht.  


### Manuelles Generieren

Das manuelle Generieren der PDF- und HTML- und TXT-Dateien kann unter Ubuntu erfolgen. Dazu sind folgende Pakete zu installieren:


    sudo apt-get install texlive texlive-base texlive-latex-base texlive-extra-utils texlive-binaries texlive-extra-utils texlive-font-utils texlive-pictures texlive-pstricks texlive-latex-extra 
    sudo apt-get install latex2html latex-xcolor


Lade alle Dateien in ein Verzeichnis und wechsle in diese Verzeichis. Unter Linux (Ubuntu) starte folgendes Script:


    ./make_booklet.sh




[jan Lope](https://jan-lope.github.io)
