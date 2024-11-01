# To-Do-App

## Jak uruchomić aplikację:
1. Pobrać i rozpakowac Wolsztyniak_ToDo_App.zip z wydania (release) v1.0 z prawej strony tej strony
2. Lokalnie stworzyć bazę danych w postgresql o nazwie "tododb" (ja uzylem pgAdmin 4)
3. W folderze `todo_api\src\main\resources` w pliku `application.properties` zmienic username i password na takie umożliwiające zalogowanie do lokalnego serwera bazy danych (w moim przypadku username=postgres, password=admin)
4. Otworzyc w srodowisku programowania (w moim przypadku Intellij Idea) projekt z folderu todo_api i go uruchomic (powinien sie poprawnie polaczyc z baza danych `tododb` i utworzyc tabele "zadanie")
5. Otworzyc w srodowisku programowania (w moim przypadku Visual Studio Code) projekt z folderu TodoFront i go uruchomic (w przypadku visual studio code, otworzyc nowy terminal i wpisac `ng serve`)
6. Wejsc w przegladarce na `http://localhost:4200/`
