our-test-repo
=============

testing

juppheidie!
YOU CANT PUSH  


## ein Repository clonen

    git clone git@github.com:motrton/our-test-repo.git  

## Dann änderungen vornehmen
##README.md ändern

## eine Änderung der Versionskontrolle hinzufügen  

    git commit -a -m "This is a change"

## eine neue datei erzuegen

    touch test.txt  

## eine neue Datei unter versionskontrolle legen  

    git add test.txt  

## Die neue Datei commiten  

    git commit -a -m "this is a new file"  

## Zum online Repo pushen  

    git push origin master  

## wenn bereits änderungen da sind  gibt es einen Fehler  
## Also erst Änderungen ziehen  

    git pull origin master  

## Wenn die automatisch gemergt werden kann toll
## wenn nicht musst du in die Dateien und <<<<<<<<<<<<<Head usw finden  
## dann wieder commiten

    git commit -a -m "merged changes"  

## dann pushen  

    git push origin master  



