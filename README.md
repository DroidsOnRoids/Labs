# Oddawanie zadań
Po skończonych warsztatach można wysłać swoje projekty w następujący sposób:

## Za pomocą SourceTree
1. Otwieramy **SourceTree** i klikamy `+ New Repository` -> `Clone from URL`.
2. W `Source URL` wklejamy: `git@github.com:IB2016/Labs.git`
3. W `Destination Path` i `Name` wpisujemy ścieżkę i nazwę nowego folderu w którym umieścimy zadanie.
4. Powinniśmy mieć nowe repozytorium na liście w **SourceTree**, wchodzimy w nie.
5. Klikamy na `Branch+` w menu i tworzymy nowy branch o nazwie składającej się z imienia i nazwiska (bez polskich znaków i z dolnym podkreślnikiem zamiast spacji, np. `jan_kowalski`). Zaznaczamy checkout new branch.
6. Teraz kopiujemy folder z zadaniem do nowo-stworzonego folderu.
7. **(Opcjonalnie)** Gdziekolwiek w projekcie w komentarzu na samej górze podać e-mail na feedback zwrotny.
8. Wchodzimy jeszcze raz do **SourceTree**, zaznaczamy checkbox obok `Unstaged files`, na samym dole w Commit message wpisujemy "[IB2016] Snapchat]", zaznaczamy `Push changes immediately to origin/master` i naciskamy `Commit`.

## Za pomocą terminala
1. Otwieramy terminal i przechodzimy do miejsca w którym chcemy utworzyć nowy folder z wklejonym zadaniem, np. `cd ~/Desktop`
2. Ściągamy folder w którym wkleimy nasze zadanie poleceniem `git clone git@github.com:IB2016/Labs.git`.
3. Przechodzimy do nowo-stworzonego folderu poleceniem `cd Labs`.
4. Tworzymy nowy branch poleceniem `git checkout -b NAZWA_BRANCHA`, gdzie nazwa brancha musi składać się z imienia i nazwiska (bez polskich znaków i z dolnym podkreślnikiem zamiast spacji, np. `jan_kowalski`), na przykład `git checkout -b jan_kowalski`.
5. Kopiujemy folder z naszym zadaniem do folderu `Labs`, który został właśnie utworzony. Może to być komendą `cp SCIEZKA_DO_PROJEKTU .`, np `cp ~/Desktop/Projekt .`.
6. Wysyłamy nasze zmiany poleceniami (jeden po drugim):
`git add.`
`git commit -m "[IB2016] Snapchat]"`
`git push`
