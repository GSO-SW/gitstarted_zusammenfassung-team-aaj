# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
- In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.
- Mit diesen [Generator](https://www.tablesgenerator.com/markdown_tables) können Sie Tabellen für Markdown erzeugen

:dart: Ziele:
1. Die Arbeit soll nicht im Browser stattfinden. Clonen Sie das Repo und arbeiten Sie lokal.
1. Hier gehts um Teamwork: Ich erwarte häufige Commits (+ häufiges pushen/pullen )

## TODO
- Begriffe definieren und erklären (z.B. repository, branch etc.)
- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)
  + git init: erstellen von Repositorie und Staging Area in einem Ordner.
  + git log: Änderungsverlauf der Repositorie
  + git status: zeigt Inhalte, die nicht commitet sind.
  + git branch 'name': erstellt ein loakler Arbeisbereich. (gut für Testzwecke)
  + git add (Datei Name)/*: fügt die Dateien zum Satging Area.
  + git commit: erstellt ein Commit mit dem Inhalt in der Satging Area
  
- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)
  + git clone: Inhale der lokalen Repositories entsprechend der entfernten Repositories aktualisieren
  + git merge: lokal bearbeitete Commits mit dem entfernten Repositories Stand zusammenfügen.
  + git pull: git clone + git merge. Da meistens die beide Befähle zusammengehören
  + git push: lokale commits zum entfernten Repositories pushen.

## TODO2
- Fachbegriffe OOP erklären (mit Beispielen)
  - abstract (Klassen)
  - abstract (Methoden)
  - virtual
  - override
  - Polymorphie
- Wie überschreibt man die Methode `virtual string ToString()`?
