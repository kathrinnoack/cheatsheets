# Shell commands 

## Navigation
Hier sind fünf wichtige Befehle für das Arbeiten (navigieren)mit der *Command Line*

* die *command line* ist text-basiert. Um sie zu benutzen, wird das *iTerm* verwendet.

* Mit der Command Line kann man sich durch Dateien und Ordner navigieren:

    * `pwd` = print working directory = zeigt den Pfad in den Ordner in dem man sich befindet.
    * `ls` = list = zeigt alle Dateien in dem aktuellen Ordner und Unterordner  an.
        * `la -a` = Liste mit Details, auch mit versteckten Dateien
        * `la -l`= Liste mit Details (`l`= long)
        * `la -t`= orders files and directories by the time they were last modified

    * `cd [Ordnername]` = change directory = ist eine Anweisung mit der man in den genannten Ordner springt    
        * `cd` bringt mich in mein Verzeichnis
        * `cd..` bringt mich einen Ordner hoch

    * `..` Weiterleitung in übergeordnete Ordner
    * `tree` Verzeichnisbaum anzeigen
    * `curl` lädt Objekt über eine URL
    * `cat` zeigt den Inhalt einer Datei

          
    * `mkdir` = make directory = legt neuen Ordner an 
    * `mkdir [Ordner/Unterordner]` Unterordner erstellen
    * `touch` = legt eine neue Datei in demn aktuellen Ordner an

* Von der *command line* aus, kann man Ordner und Dateien auch kopieren, verschieben und löschen:
    * `cp` kopiert Dateien
    * `cp -R [src-directory] [target-directory]` kopiert alles aus dem Quellverzeichnis in das Zielverzeichnis
    * `mv` bewegt Dateien und nennt sie auch um
        * `mv [alter Name] [neuer Name]` Ordner/Datei umbenennen
        * `mv [alter Pfad] [neuer Pfad]` Ordner/Datei verschieben
        * `mv [Ordner] *` verschieben des Ordners in den aktuellen Ordner
    * `rm` remove (geht nur bei Dateien)
    * `rm -rf` löschen aller Ordner und Dateien im aktuellen Ordner
    * **rm -r** löscht Ordner
* Wildcards are useful for selecting groups of files and directories

- `pbcopy` speichert Eingabe in die Zwischenablage (Bsp.: `cat ~/.ssh/id_rsa.pub | pbcopy`)

* `code .` aktueller Ordner wird bei VS Code aufgerufen
* `open [Datei]` öffnet Datei mit dem Standardprogramm eines Betriebssystems
* `open .` öffnet Ordner im Finder/Explorer