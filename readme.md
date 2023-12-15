# Git verziókezelés
## helyi repository létrehozása

- a helyi repo inicializálása:
    > git init
- ellenőrzés:
    > git status
- előkészítjük a commitolásra (beindexelődésre - stage)
    > git add .
- létrehozzuk a legújabb verziót, eltároljuk a helyi repoba:
    > git commit -m "first commit"
- ellenőrzés:
    > git status

## öszekapcsolás a távoli repoval

- új GitHub repo létrehozása (publikus)
- összekapcsolási parancs:
    > git remote add origin https://token@github.com/mdavidstefan/**repoName**.git
- az első alkalommal meg kell adni az ágat, hogy hová kerüljön:
    > git push -u origin master
- kérni fogja a tokenedet, amit a privát repoban eltároltál