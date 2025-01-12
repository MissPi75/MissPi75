## Wymaganie funkcjonalne 5:
Próba logowania przy użyciu poprawnego loginu i hasła pozwala na zalogowanie się do systemu.

### Id: PT5-1

Tytuł: Test logowania do systemu przy użyciu poprawnego loginu i hasła.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies
- istnieje konto użytkownika

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, widoczny przycisk logowania. | 2. | Kliknięto przycisk logowania | N/A | Strona logowania otwiera się poprawnie. | 3. | Wpisano dane w pole login. | mojmail@jakisserwer.pl | Pole login uzupełnione. | 4. | Wpisano dane w pole hasło. | jakieshaslo | Pole hasło uzupełnione. | 5. | Naciśnięto przycisk *zaloguj się*. | N/A | Użytkownik zostaje zalogowany do systemu. |

Rezultat oczekiwany:
Po uzupełnieniu pól *login* i *hasło* poprawnymi danymi użytkownik zostaje zalogowany do systemu.

### Id: PT5-2

Tytuł: Test logowania do systemu przy użyciu niepoprawnego loginu.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies
- istnieje konto użytkownika

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, widoczny przycisk logowania. | 2. | Kliknięto przycisk logowania | N/A | Strona logowania otwiera się poprawnie. | 3. | Wpisano dane w pole login. | mojmail#jakisserwer.pl | Pole login uzupełnione, przy przejściu do pola *hasło* pojawia się komunikat *Wpisz prawidłowy login*. |

Rezultat oczekiwany:
Po uzupełnieniu pola login niepoprawnymi danymi użytkownikowi zostaje wyświetlony komunikat o konieczności wpisania prawidłowego loginu.

### Id: PT5-3

Tytuł: Test logowania do systemu przy użyciu niepoprawnego hasła.

Autor: Anna O-B

Środowisko: Ubuntu 20.04.6 LTS, Opera One (wersja: 107.0.5045.21)

Warunki wstępne:

- uruchomiona przeglądarka
- zaakceptowane cookies
- istnieje konto użytkownika

Kroki:

| Lp. | Krok/Akcja | Dane testowe | Rezultat oczekiwany |
| --- | ---------- | ------------ | ------------------- |
| 1.  | Otwarto stronę https://www.maxizoo.pl. | N/A | Strona główna wyświetla się poprawnie, widoczny przycisk logowania.| 2. | Kliknięto przycisk logowania | N/A | Strona logowania otwiera się poprawnie. | 3. | Wpisano dane w pole login. | mojmail@jakisserwer.pl | Pole login uzupełnione. | 4. | Wpisano dane w pole hasło. | blablabla | Pole hasło uzupełnione. | 5. | Naciśnięto przycisk *zaloguj się*. | N/A | Użytkownikowi zostaje wyświetlony komunikat *Hasło lub e-mail są nieprawidłowe*. |

Rezultat oczekiwany:
Po uzupełnieniu pola login poprawnymi danymi a pola hasło niepoprawnymi danymi użytkownikowi zostaje wyświetlony komunikat o tym że hasło lub e-mail są nieprawidłowe.
