# Test Cases for Kanban Board

This repository contains test cases for verifying the functionality of the Kanban Board application. Below is the structured list of test cases, organized by feature.

# Tool:
![TestLink](https://img.shields.io/badge/TestLink-yellow?style=flat?logo=TestLink)

---

# 1. Dodawanie kolumn

## TC01: Rezygnacja z dodania nowej kolumny

### Cel testu:
Sprawdzenie, czy użytkownik może anulować dodanie nowej kolumny.

### Warunki początkowe:  
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.  
2. W aplikacji widoczny jest przycisk „Add new column”.

### Kroki testowe i oczekiwane rezultaty:
1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.
2. **Krok:** Kliknij przycisk „Add new column”.
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.
3. **Krok:** Wpisz nazwę kolumny.
   **Oczekiwany rezultat:** W polu pojawia się wpisana nazwa.
4. **Krok:** Kliknij „Anuluj”.
    **Oczekiwany rezultat:** Kolumna nie zostaje dodana jako ostatnia po prawej stronie.
  
[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Rezygnacja_z_dodania_nowej_kolumny.png)

## TC02: Dodanie nowej kolumny

### Cel testu:
Sprawdzenie możliwości utworzenia nowej kolumny.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: „add new column”.


### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column”.  
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.

3. **Krok:** W polu nazwa wpisz „wakacje”.  
   **Oczekiwany rezultat:** W polu pojawia się wpisana nazwa „wakacje”.

4. **Krok:** Naciśnij „OK”.  
   **Oczekiwany rezultat:** Kolumna o nazwie „wakacje” zostaje dodana jako ostatnia po prawej stronie.

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_nowej_kolumny.png)


## TC03: Dodanie kolumny bez nazwy

### Cel testu:
Sprawdzenie możliwości dodania kolumny bez nazwy.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: „add new column”.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column”.  
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.

3. **Krok:** Pozostaw pole nazwy puste.  
   **Oczekiwany rezultat:** Pole nazwy pozostaje puste.

4. **Krok:** Naciśnij „OK”.  
   **Oczekiwany rezultat:** Kolumna dodaje się jako ostatnia na stronie z domyślną nazwą „Kolumna”.

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_bez_nazwy.png)

## TC04: Dodanie kolumny ze znakami specjalnymi w nazwie

### Cel testu:
Sprawdzenie, czy można dodać kolumnę ze znakami specjalnymi w nazwie.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: „add new column”.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column”.  
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.

3. **Krok:** W polu nazwa wpisz „@_!”.  
   **Oczekiwany rezultat:** W polu pojawia się wpisana nazwa „@_!”.

4. **Krok:** Naciśnij „OK”.  
   **Oczekiwany rezultat:** Kolumna o nazwie „@_!” pojawia się jako ostatnia po prawej stronie.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_ze_znakami_specjalnymi_w_nazwie.png)


## TC05: Dodanie dwóch kolumn o tej samej nazwie

### Cel testu:
Sprawdzenie, czy możliwe jest dodanie dwóch kolumn o tej samej nazwie.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: „add new column”.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column” i w polu nazwa wpisz „A”.  
   **Oczekiwany rezultat:** W aplikacji pojawia się nowa kolumna o nazwie „A”.

3. **Krok:** Kliknij ponownie „add new column” i w polu nazwa wpisz „A”.  
   **Oczekiwany rezultat:** W aplikacji widoczne są dwie kolumny o tej samej nazwie „A”.

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_dw%C3%B3ch_kolumn_o_tej_samej_nazwie.png)


## TC06: Dodanie kolumny ze znakami diakrytycznymi w nazwie

### Cel testu:
Sprawdzenie, czy możliwe jest dodanie kolumny, której nazwa zawiera znaki diakrytyczne.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji widoczny jest przycisk dodania nowej kolumny: „add new column”.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column”.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy kolumny.

3. **Krok:** W polu nazwa wpisz „ńść”.  
   **Oczekiwany rezultat:** Kolumna o nazwie „ńść” zostaje dodana do listy jako ostatnia po prawej stronie.

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_ze_znakami_diakrytycznymi_w_nazwie.png)

## TC07: Dodanie 15 kolumn w aplikacji

### Cel testu:
Sprawdzenie, czy można dodać 15 nowych kolumn.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji widoczny jest przycisk dodania nowej kolumny: „add new column”.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column”.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy kolumny.

3. **Krok:** W polu nazwa wpisz „1”.  
   **Oczekiwany rezultat:** Kolumna o nazwie „1” zostaje dodana do listy jako ostatnia po prawej stronie.

4. **Krok:** Powtórz kroki 2–3, wpisując kolejno nazwy „2”, „3”, ..., „15”.  
   **Oczekiwany rezultat:** Po dodaniu ostatniej kolumny w aplikacji, oprócz trzech domyślnych kolumn („to do”, „doing”, „done”), widocznych jest 15 nowych kolumn — łącznie 18 kolumn.

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_15_nowych_kolumn.png)


## TC08: Dodanie kolumny z nazwą zawierającą 40 znaków

### Cel testu:
Sprawdzenie, czy można dodać kolumnę, której nazwa zawiera 40 znaków.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk „add new column”.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column”.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy kolumny.

3. **Krok:** W polu nazwa wpisz dokładnie 40 znaków, np. `aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa`.  
   **Oczekiwany rezultat:** Kolumna o nazwie zawierającej 40 znaków zostaje dodana do listy jako ostatnia po prawej stronie.

4. **Krok:** Kliknij „ok”.  
   **Oczekiwany rezultat:** Kolumna z nazwą o długości 40 znaków jest poprawnie widoczna w interfejsie aplikacji.

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_o_nazwie_zawieraj%C4%85cej_40_znak%C3%B3w.png)

---

## 2. Dodawanie zadań w kolumnach



---

## Uwagi
- Każdy przypadek testowy zawiera cel, warunki wstępne, kroki oraz oczekiwane rezultaty.
- Szczegółowy projekt testów i ich wykonanie znajduje się w załączonych zrzutach ekranu lub dokumentacji.

