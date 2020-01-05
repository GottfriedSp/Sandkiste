# Verwendung von git

## Benutzername und E-Mail ändern
- git config --global user.name "John Doe"
- git config --global user.email "john@doe.org"

## von externem repos
#### Frisch holen und Austschecken
- git clone <repi>
#### Bestehendes von extern holen und auschecken
- git pull
#### hochladen
- git push

## Lokal ändern
#### log ansehen
- git log
- git log  --oneline
### Adden
- git add <datei>
### Eintschecken
- git commit
- git commit -a

## Big troubles beheben!
### Änderungen rückgängig machen
- git reset --hard <key>
- git reset --hard HEAD

