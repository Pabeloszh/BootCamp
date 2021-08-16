1. git jest systemem kontroli wersji który umożliwia nam śledzenie, zapisywanie i bezpieczne dodawanie zmian do aplikacji
2. git - jest to oprogramowanie, jest narzędziem wiersza poleceń
github - jest to serwis internetowy, jest stroną internetową
3. wykorzystuje się go do tego aby zignorować niektóre pliki/foldery żeby przez to nie dodać do repo np. node_modules (które za dużo ważą) lub plików zawierających hasła lub jakieś poufne informacje
4. repozytorium lokalne - jest dostępne tylko lokalnie na komputerze użytkownika i tylko on ma do niego dostęp, służy do: dodawania, komitowania lub cofania zmian
repozytorium zdalne - jest dostępne publicznie lub dla wybranych użytkowników przez wybrany serwis, służy do monitorowania zmian, pullowania, fetchowania, pushowania 
5. git remote rm <remote-name> albo przez githuba usunąć przez settings>delete this repository
6. wykorzystuje się aby zachować estetykę pracy i zminimalizować ryzyko "zepsucia" projektu przez przykładowo wypushowanie zmian bezpośrednio na mastera bez code review lub sprawdzenia czy są jakieś konflikty w zmianach
7. git status - pokazuje zmodyfikowane, usunięte lub dodane pliki w obecnym przygotowaniu do kommita
git log - pokazuje zmiany w historii
8. git init
9. fetch - pobiera danego brancha na lokalne repozytorium
pull - tak jak fetch pobiera ale automatycznie merguje z bieżącym branchem
10. kiedy dokonamy pusha zmian do repozytorium zdalnego używając komendy "git push origin (nazwa brancha)"