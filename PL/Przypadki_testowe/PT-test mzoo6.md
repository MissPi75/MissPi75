## Wymaganie funkcjonalne 6:
Na stronie głównej u góry po środku belki górnej znajduje się pole *szukaj*. Pole przyjmuje litery, cyfry i znaki specjalne. Przyjmuje alfabet łaciński. Po wpisaniu frazy użytkownik przenoszony jest do strony z wynikami.

### Id: PT6-1

Tytuł: Test czy pole *szukaj* na stronie głównej przyjmuje litery alfabetu łacińskiego.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, u góry pośrodku belki górnej widoczne pole *szukaj*. |
| 2. | Wpisano dane w pole *szukaj*. | karma | Po wpisaniu słowa *karma* użytkownik jest przenoszony na stronę z wynikami wyszukiwania. |

Rezultat oczekiwany:
Po wpisaniu słowa *karma* użytkownikowi jest wyświetlana strona z wynikami wyszukiwania.

### Id: PT6-2

Tytuł: Test czy pole *szukaj* na stronie głównej przyjmuje litery inne niż alfabetu łacińskiego.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, u góry pośrodku belki górnej widoczne pole *szukaj*. |
| 2. | Wpisano dane w pole *szukaj*. | 餌 | Po wpisaniu słowa 餌użytkownik jest przenoszony na stronę z wynikami wyszukiwania gdzie wyświetlany jest rezultat: 0- brak wyników wyszukiwania. |

Rezultat oczekiwany:
Po wpisaniu znaku 餌 użytkownik jest przenoszony na stronę z wynikami wyszukiwania gdzie wyświetlany jest komunikat o braku wyników wyszukiwania.

### Id: PT6-3

Tytuł: Test czy pole szukaj na stronie głównej przyjmuje polskie znaki.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, u góry pośrodku belki górnej widoczne pole *szukaj*. |
| 2. | Wpisano dane w pole *szukaj*. | mięsny | Po wpisaniu słowa *mięsny* użytkownik jest przenoszony na stronę z wynikami wyszukiwania. |


Rezultat oczekiwany:
Po wpisaniu słowa *mięsny* użytkownikowi jest wyświetlana strona z wynikami wyszukiwania.

### Id: PT6-4

Tytuł: Test czy pole szukaj na stronie głównej przyjmuje cyfry.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, u góry pośrodku belki górnej widoczne pole *szukaj*. |
| 2. | Wpisano dane w pole *szukaj*. | 12 | Po wpisaniu *12* użytkownik jest przenoszony na stronę z wynikami wyszukiwania. |


Rezultat oczekiwany:
Rezultat oczekiwany: Po wpisaniu ciągu cyfr *12* użytkownikowi jest wyświetlana strona z wynikami wyszukiwania.

### Id: PT6-5

Tytuł: Test czy pole szukaj na stronie głównej przyjmuje znaki specjalne.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, u góry pośrodku belki górnej widoczne pole *szukaj*. |
| 2. | Wpisano dane w pole *szukaj*. | $ | Po wpisaniu *$* użytkownik jest przenoszony na stronę z wynikami wyszukiwania. |


Rezultat oczekiwany:
Po wpisaniu znaku specjalnego użytkownikowi jest wyświetlana strona z wynikami wyszukiwania.

