## Wymaganie funkcjonalne 4:
Pole *City Name* na zakładce *hotels* może przyjmować tylko litery i tylko alfabetu łacińskiego. Nie można używać innych alfabetów. Pole rozpoczyna wyświetlanie podpowiedzi po wpisaniu 3 liter.

### Id: PT4a

Tytuł: Zakładka *hotels* –  test pola wyboru *City Name*: czy przyjmuje tylko litery, wyświetla podpowiedzi po wpisaniu 3 liter

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 106.0.4998.70)

Warunki wstępne:

- uruchomiona przeglądarka
- otwarta strona https://phptravels.net/
- zaakceptowane pliki cookies
- użytkownik musi znajdować się na zakładce *hotels*

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  |  Wpisano dane w pole *City Name* | Poz| Pole wyświetla podpowiedź nazw miast zawierających ciąg liter *Poz* |

### Id: PT4b

Tytuł: Zakładka *hotels* –  test pola wyboru *City Name*: czy przyjmuje tylko litery, wyświetla podpowiedzi po wpisaniu 3 liter

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 106.0.4998.70)

Warunki wstępne:

- uruchomiona przeglądarka
- otwarta strona https://phptravels.net/
- zaakceptowane pliki cookies
- użytkownik musi znajdować się na zakładce *hotels*

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  |  Wpisano dane w pole *City Name* | 東京 | Pole wyświetla komunikat o wpisaniu błędnych danych. |

### Id: PT4c

Tytuł: Zakładka *hotels* –  test pola wyboru *City Name*: czy przyjmuje tylko litery alfabetu łacińskiego

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 106.0.4998.70)

Warunki wstępne:

- uruchomiona przeglądarka
- otwarta strona https://phptravels.net/
- zaakceptowane pliki cookies
- użytkownik musi znajdować się na zakładce *hotels*

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  |  Wpisano dane w pole *City Name* | $5@!, 名古屋, جلال‌آباد | Pole wyświetla komunikat o braku (0) wyników wyszukiwania. |