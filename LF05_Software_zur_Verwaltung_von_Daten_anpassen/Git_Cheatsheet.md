* Git Cheatsheet

*** git config --global user.email "<mailadresse>"
*** git config --lgobal user.name  "username"

*** git init
Dieser Befehl erstellt ein Repository

*** git add
Fügt die Datei(en) der Staging Area hinzu

*** git commit -m "Commitbeschreibung"
Fügt die Datei(en) dem Repository hinzu und speichert die angegebene Nachricht an d em entsprechenden Commit

*** git branch <branchname>
Erstellt einen neuen Branch und wechselt dorthin

*** git checkout <branchname>
"switcht" zwischen Branches

Master-Branch sollte geradlinig und lange am Leben bleiben, deshalb immer die anderen Branches, soweit möglich, wieder in den Master-Branch mergen

*** git merge <branchname>

*** git branch -d <branchname>
Nicht mehr benötigte lokale Branches entfernen

*** git log --graph --decorate --oneline
Verschiedene Optionen für den git Log Befehl um die Branches und Commits anzuzeigen

** Neues Projekt mit neuem Repository auf GitHub erstellen

GitBash --> Remote setzen

*** git remote -v # Abfrage
*** git remote add <alias> <URL>
*** git remote add origina https://xxx
 
*** git push --set-upstream origin master # Verbindung zwischen Onlinebranch und Offlinebranch definieren

*** git pull # Tipp immer erst zu pullen bevor man etwas neues pusht

** Zu Projekt beitragen

*** git clone <URL>
URL findet man auf GitHub unter "Clone or Download"

*** git clone 
