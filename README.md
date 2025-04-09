
# Zadania SQL – Klauzula WHERE (Baza: Chinook)

📦 **Baza danych Chinook**  
Zadania w tym repozytorium oparte są na przykładowej bazie danych **Chinook**, która symuluje środowisko sklepu muzycznego online. Baza zawiera dane o klientach, pracownikach, utworach, albumach, fakturach oraz wykonawcach. Jest to popularny zbiór danych wykorzystywany do nauki SQL i relacyjnych baz danych.

Więcej informacji o projekcie Chinook można znaleźć tutaj: [https://github.com/lerocha/chinook-database](https://github.com/lerocha/chinook-database)


### Data Model
<img width="836" alt="image" src="https://github.com/lerocha/chinook-database/assets/135025/cea7a05a-5c36-40cd-84c7-488307a123f4">
---

## 🟢 Poziom 1 – Proste

### Zadanie 1
Wyświetl wszystkich klientów z miasta `Prague`.


### Zadanie 2
Wyświetl wszystkie utwory (`Track`), których czas trwania (czas w milisekundach) jest mniejszy niż 60 000.


---

## 🟡 Poziom 2 – Średnie

### Zadanie 3
Wyświetl wszystkie faktury (`Invoice`) wystawione w Kanadzie (`Canada`), których całkowita wartość przekracza 10.


### Zadanie 4
Wyświetl wszystkich pracowników (`Employee`), którzy mają stanowisko inne niż `Sales Support Agent`.


---

## 🔴 Poziom 3 – Zaawansowane

### Zadanie 5
Wyświetl wszystkie utwory (`Track`) z gatunku `Rock`, których rozmiar pliku przekracza 5 MB (5242880 bajtów).


### Zadanie 6
Wyświetl wszystkich klientów, którzy mają `Company` ustawione na NULL i mieszkają w USA (`USA`).


---




# Zadania SQL – GROUP BY + HAVING (Baza: Chinook)


---

## 🟢 Poziom 1 – Proste

### Zadanie 1
Wyświetl liczbę klientów w każdym kraju.


### Zadanie 2
Wyświetl liczbę utworów w każdej kategorii (`Genre`).


---

## 🟡 Poziom 2 – Średnie

### Zadanie 3
Wyświetl kraje, w których liczba klientów przekracza 5.


### Zadanie 4
Wyświetl identyfikatory albumów, które zawierają więcej niż 10 utworów.


---

## 🔴 Poziom 3 – Zaawansowane

### Zadanie 5
Wyświetl identyfikatory faktur oraz sumaryczną wartość pozycji (`InvoiceLine`) dla każdej faktury, ale tylko dla tych, których suma przekracza 15.


### Zadanie 6
Wyświetl gatunki muzyczne (`GenreId`), dla których średni rozmiar pliku (`Bytes`) przekracza 5 MB (5242880 bajtów).


---



# Zadania SQL – JOIN + ORDER BY + LIMIT (Baza: Chinook)

Poniżej znajduje się zestaw 6 zadań SQL do wykonania na bazie danych **Chinook**. Wszystkie zadania zawierają zapytania z użyciem `JOIN`, `ORDER BY` oraz `LIMIT`. Zadania są podzielone według poziomu trudności.

---

## 🟢 Poziom 1 – Proste

### Zadanie 1
Wyświetl nazwy utworów wraz z nazwą albumu, do którego należą. Posortuj rosnąco po nazwie albumu i ogranicz wynik do 10 wierszy.


### Zadanie 2
Wyświetl imię i nazwisko klienta wraz z nazwą kraju, posortowane malejąco po nazwisku. Pokaż tylko 5 rekordów.


---

## 🟡 Poziom 2 – Średnie

### Zadanie 3
Wyświetl nazwiska pracowników wraz z nazwą klienta, który jest im przypisany (poprzez `SupportRepId`). Posortuj według nazwiska pracownika i ogranicz wynik do 10 wierszy.


### Zadanie 4
Wyświetl listę utworów wraz z nazwą wykonawcy (artist). Posortuj według długości utworu malejąco i pokaż tylko 7 najdłuższych utworów.


---

## 🔴 Poziom 3 – Zaawansowane

### Zadanie 5
Wyświetl imię i nazwisko klienta oraz datę i wartość jego faktury. Posortuj malejąco po wartości faktury i ogranicz wynik do 10 najwyższych faktur.


### Zadanie 6
Wyświetl listę albumów i wykonawców, którzy mają więcej niż jeden album. Posortuj rosnąco po nazwie wykonawcy i pokaż pierwszych 10 wyników.


---




📝 **Uwaga:** Przed wykonaniem zapytań upewnij się, że masz zaimportowaną bazę danych **Chinook** i jesteś połączony z odpowiednim serwerem MySQL/ MariaDb.

