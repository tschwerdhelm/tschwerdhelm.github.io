### Documentation zur Website 

## lokales Testen
Die Website nutzt github-pages mit jekyll zum rendern der .md-Dateien zu .html-Dateien.
Da jekyll auf Ruby basiert kann über einen lokalen ruby-server getestet werden. 
Es ist notwendig Ruby lokal zu installieren: "https://rubyinstaller.org/downloads/"

Die Abhängigkeiten des Servers sind in der "gemfile"-Datei gespeichert.

Über "bundle install" können die Abhängigkeiten installiert werden.
Der lokale Server lässt sich über "bundle exec jekyll serve --watch" starten.
Der Server läuft standardmäßg unter "http://127.0.0.1:4000/".