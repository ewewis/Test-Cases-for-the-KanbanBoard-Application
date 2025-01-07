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
2. W aplikacji widoczny jest przycisk `ADD NEW COLUMN`.

### Kroki testowe i oczekiwane rezultaty:
1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.
2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.
3. **Krok:** Wpisz nazwę kolumny.
   **Oczekiwany rezultat:** W polu pojawia się wpisana nazwa.
4. **Krok:** Kliknij `Anuluj`.
    **Oczekiwany rezultat:** Kolumna nie zostaje dodana jako ostatnia po prawej stronie.

  
[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Rezygnacja_z_dodania_nowej_kolumny.png)



## TC02: Dodanie nowej kolumny

### Cel testu:
Sprawdzenie możliwości utworzenia nowej kolumny.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: `ADD NEW COLUMN`.


### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.

3. **Krok:** W polu nazwa wpisz `wakacje`.  
   **Oczekiwany rezultat:** W polu pojawia się wpisana nazwa `wakacje`.

4. **Krok:** Naciśnij `OK`.  
   **Oczekiwany rezultat:** Kolumna o nazwie `wakacje` zostaje dodana jako ostatnia po prawej stronie.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_nowej_kolumny.png)



## TC03: Dodanie kolumny bez nazwy

### Cel testu:
Sprawdzenie możliwości dodania kolumny bez nazwy.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: `ADD NEW COLUMN`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.

3. **Krok:** Pozostaw pole nazwy puste.  
   **Oczekiwany rezultat:** Pole nazwy pozostaje puste.

4. **Krok:** Naciśnij `OK`.  
   **Oczekiwany rezultat:** Kolumna dodaje się jako ostatnia na stronie z domyślną nazwą `Kolumna`.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_bez_nazwy.png)



## TC04: Dodanie kolumny ze znakami specjalnymi w nazwie

### Cel testu:
Sprawdzenie, czy można dodać kolumnę ze znakami specjalnymi w nazwie.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: `ADD NEW COLUMN`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.

3. **Krok:** W polu nazwa wpisz `@_!`.  
   **Oczekiwany rezultat:** W polu pojawia się wpisana nazwa `@_!`.

5. **Krok:** Naciśnij `OK`.  
   **Oczekiwany rezultat:** Kolumna o nazwie `@_!` pojawia się jako ostatnia po prawej stronie.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_ze_znakami_specjalnymi_w_nazwie.png)



## TC05: Dodanie dwóch kolumn o tej samej nazwie

### Cel testu:
Sprawdzenie, czy możliwe jest dodanie dwóch kolumn o tej samej nazwie.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: `ADD NEW COLUMN`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN` i w polu nazwa wpisz `A`.  
   **Oczekiwany rezultat:** W aplikacji pojawia się nowa kolumna o nazwie `A`.

3. **Krok:** Kliknij ponownie `ADD NEW COLUMN` i w polu nazwa wpisz `A`.  
   **Oczekiwany rezultat:** W aplikacji widoczne są dwie kolumny o tej samej nazwie `A`.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_dw%C3%B3ch_kolumn_o_tej_samej_nazwie.png)



## TC06: Dodanie kolumny ze znakami diakrytycznymi w nazwie

### Cel testu:
Sprawdzenie, czy możliwe jest dodanie kolumny, której nazwa zawiera znaki diakrytyczne.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji widoczny jest przycisk dodania nowej kolumny: `ADD NEW COLUMN`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy kolumny.

3. **Krok:** W polu nazwa wpisz `ńść`.  
   **Oczekiwany rezultat:** Kolumna o nazwie `ńść` zostaje dodana do listy jako ostatnia po prawej stronie.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_ze_znakami_diakrytycznymi_w_nazwie.png)



## TC07: Dodanie 15 kolumn w aplikacji

### Cel testu:
Sprawdzenie, czy można dodać 15 nowych kolumn.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji widoczny jest przycisk dodania nowej kolumny: `ADD NEW COLUMN`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy kolumny.

3. **Krok:** W polu nazwa wpisz `1`.  
   **Oczekiwany rezultat:** Kolumna o nazwie `1` zostaje dodana do listy jako ostatnia po prawej stronie.

4. **Krok:** Powtórz kroki 2–3, wpisując kolejno nazwy `2`, `3`, ..., `15`.  
   **Oczekiwany rezultat:** Po dodaniu ostatniej kolumny w aplikacji, oprócz trzech domyślnych kolumn: `to do`, `doing`, `done` widocznych jest 15 nowych kolumn — łącznie 18 kolumn.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_15_nowych_kolumn.png)



## TC08: Dodanie kolumny z nazwą zawierającą 40 znaków

### Cel testu:
Sprawdzenie, czy można dodać kolumnę, której nazwa zawiera 40 znaków.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD NEW COLUMN`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy kolumny.

3. **Krok:** W polu nazwa wpisz dokładnie 40 znaków, np. `aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa`.  
   **Oczekiwany rezultat:** Kolumna o nazwie zawierającej 40 znaków zostaje dodana do listy jako ostatnia po prawej stronie.

4. **Krok:** Kliknij `OK`.  
   **Oczekiwany rezultat:** Kolumna z nazwą o długości 40 znaków jest poprawnie widoczna w interfejsie aplikacji.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_kolumny_o_nazwie_zawieraj%C4%85cej_40_znak%C3%B3w.png)


---

# 2. Dodawanie zadań w kolumnach

## TC01: Dodanie nowego zadania w kolumnie `to do`

### Cel testu:
Sprawdzenie możliwości dodania nowego zadania.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij `ADD TASK` w kolumnie `to do`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy zadania.

3. **Krok:** Wpisz nazwę zadania `niebo`.  
   **Oczekiwany rezultat:** W kolumnie `to do` pojawia się nowe zadanie o nazwie `niebo`.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_nowego_zadania.png)



## TC02: Rezygnacja z dodania nowego zadania w kolumnie `to do`

### Cel testu:
Sprawdzenie możliwości rezygnacji z dodania nowego zadania w kolumnie `to do`.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `to do` kliknij przycisk `ADD TASK`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy zadania.

3. **Krok:** Wpisz nazwę zadania.  
   **Oczekiwany rezultat:** Nazwa zostaje poprawnie wpisana w pole.

4. **Krok:** Kliknij `Anuluj`.  
   **Oczekiwany rezultat:** Zadanie nie pojawia się w kolumnie `to do`.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Rezygnacja_z_dodania_nowego_zadania.png)



## TC03: Dodanie nowego zadania bez nazwy w kolumnie `to do`

### Cel testu:
Sprawdzenie, czy istnieje możliwość dodania zadania bez nazwy.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij `ADD TASK` w kolumnie `to do`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy zadania.

3. **Krok:** Naciśnij `OK` bez wpisywania żadnej nazwy.  
   **Oczekiwany rezultat:** Zadanie pojawia się w kolumnie `to do` jako puste.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_zadania_bez_nazwy.png)



## TC04: Dodanie więcej niż 3 zadań w kolumnie `doing`

### Cel testu:
Sprawdzenie, czy można dodać więcej niż 3 zadania w kolumnie `doing`.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W kolumnie `doing` znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `doing` poprzez przycisk „add task” dodaj trzy zadania.  
   **Oczekiwany rezultat:** W kolumnie `doing` znajdują się trzy zadania.

3. **Krok:** W kolumnie `doing` naciśnij `ADD TASK`, aby dodać czwarte zadanie.  
   **Oczekiwany rezultat:** Nie można dodać czwartego zadania. W kolumnie `doing` widoczne są tylko trzy zadania.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_wi%C4%99cej_ni%C5%BC_trzech_zada%C5%84.png)



## TC05: Dodanie zadania w nowo utworzonej kolumnie

### Cel testu:
Sprawdzenie, czy jest możliwość dodawania zadań do kolumn utworzonych przez użytkownika.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD NEW COLUMN`.
3. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy kolumny.

3. **Krok:** Wpisz nazwę kolumny `A` i naciśnij `OK`.  
   **Oczekiwany rezultat:** Dodana zostaje nowa kolumna o nazwie `A`.

4. **Krok:** W nowo utworzonej kolumnie `A` kliknij `ADD TASK`.  
   **Oczekiwany rezultat:** Otwiera się pole do wpisania nazwy zadania.

5. **Krok:** Wpisz nazwę zadania i naciśnij `OK`.  
   **Oczekiwany rezultat:** W nowej kolumnie `A` widoczne jest zadanie.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_zadania_w_nowo_utworzonej_kolumnie.png)



## TC06: Dodanie dwóch zadań o tej samej nazwie

### Cel testu:
Sprawdzenie, czy w kolumnie można dodać dwa zadania o tej samej nazwie.

### Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `to do` kliknij `ADD TASK`, wpisz nazwę `b` i naciśnij `OK`.  
   **Oczekiwany rezultat:** W kolumnie `to do` widoczne jest zadanie o nazwie `b`.

3. **Krok:** Wykonaj to samo co w kroku 2: kliknij `ADD TASK`, wpisz nazwę `b` i naciśnij `OK`.  
   **Oczekiwany rezultat:** W kolumnie `to do` widoczne są dwa zadania o tej samej nazwie `b`.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_dw%C3%B3ch_zada%C5%84_o_tej_samej_nazwie.png)



## TC07: Dodanie zadania ze znakami specjalnymi w nazwie

### Cel testu
Sprawdzenie, czy można utworzyć zadanie z nazwą zawierającą znaki specjalne.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji widoczny jest przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij `ADD TASK` w dowolnej kolumnie.  
   **Oczekiwany rezultat:** Otwiera się pole do wprowadzenia nazwy zadania.

3. **Krok:** W polu nazwa wpisz `#$@` i naciśnij `OK`.  
   **Oczekiwany rezultat:** W kolumnie widoczne jest zadanie o nazwie `#$@`.
   

[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_zadania_ze_znakami_specjalnymi_w_nazwie.png)



## TC08: Dodanie zadania ze znakami diakrytycznymi w nazwie

### Cel testu
Sprawdzenie, czy istnieje możliwość dodania zadania z nazwą zawierającą znaki diakrytyczne.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `doing` kliknij `ADD TASK`.  
   **Oczekiwany rezultat:** Otwiera się pole do wprowadzenia nazwy zadania.

3. **Krok:** W polu nazwa wpisz `ąćę` i naciśnij `OK`.  
   **Oczekiwany rezultat:** W kolumnie `doing` widoczne jest zadanie o nazwie `ąćę`.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_zadania_ze_znakami_diakrytycznymi_w_nazwie.png)



## TC09: Dodanie 30 zadań w kolumnie `to do`

### Cel testu
Sprawdzenie, czy istnieje możliwość dodania 30 zadań w kolumnie `to do`.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `to do` kliknij `ADD TASK`.  
   **Oczekiwany rezultat:** Otwiera się pole do wprowadzenia nazwy zadania.

3. **Krok:** W polu nazwa wpisz `1` i kliknij `OK`.  
   **Oczekiwany rezultat:** W kolumnie `to do` widoczne jest zadanie o nazwie `1`.

4. **Krok:** Analogicznie wykonaj następne kroki jak w punktach 2 i 3, dodaj kolejnych 29 zadań, wpisując nazwę w kolejności: `2`, `3`, ..., `29`, `30`.  
   **Oczekiwany rezultat:** W kolumnie "To Do" oprócz zadania o domyślnej nazwie "new task" widocznych jest 30 nowo utworzonych zadań o nazwach `1`, `2`, ..., `30`. Razem 31 zadań.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_30_zada%C5%84.png)



## TC10: Dodanie zadania w kolumnie `to do` z nazwą zawierającą 50 znaków

### Cel testu
Sprawdzenie, czy w kolumnie `to do` można dodać zadanie o nazwie zawierającej 50 znaków.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `to do` kliknij `ADD TASK`.  
   **Oczekiwany rezultat:** Otwiera się pole do wprowadzenia nazwy zadania.

3. **Krok:** W polu nazwa wpisz 50 znaków, np. `xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx`.  
   **Oczekiwany rezultat:** Pole akceptuje nazwę o długości 50 znaków.

4. **Krok:** Kliknij `OK`.  
   **Oczekiwany rezultat:** W kolumnie `to do` widoczne jest zadanie, którego nazwa zawiera 50 znaków.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Dodanie_zadania_z_50_znakami_w_nazwie.png)



# 3. Usuwanie kolumn


## TC01: Usunięcie kolumny `to do`

### Cel testu
Sprawdzenie, czy można usunąć kolumnę `to do`.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji widoczny jest przycisk `x`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W nazwie kolumny `to do` kliknij `x`.  
   **Oczekiwany rezultat:** W aplikacji kolumna `to do` nie jest widoczna.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Usuni%C4%99cie_kolumny_to_do.png)


## TC02: Usunięcie wszystkich trzech domyślnych kolumn

### Cel testu
Sprawdzenie, czy można usunąć wszystkie trzy domyślne kolumny w aplikacji.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `x`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij `x` w kolumnie `to do`.  
   **Oczekiwany rezultat:** Kolumna `to do` została usunięta.

3. **Krok:** Kliknij `x` w kolumnie `doing`.  
   **Oczekiwany rezultat:** Kolumna `doing` została usunięta.

4. **Krok:** Kliknij `x` w kolumnie `done`.  
   **Oczekiwany rezultat:** Wszystkie kolumny domyślne zostały usunięte — w aplikacji nie jest widoczna żadna kolumna.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Usuni%C4%99cie_trzech_domy%C5%9Blnych_kolumn.png)



# 4. Usuwanie zadań


## TC01: Usunięcie zadania `new task` w kolumnie `to do`

### Cel testu
Sprawdzenie, czy można usunąć domyślne zadanie `new task`.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.  
2. W aplikacji znajduje się domyślne zadanie o nazwie `new task`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij `x` w `new task` w kolumnie `to do`.  
   **Oczekiwany rezultat:** Domyślne zadanie `new task` zostało usunięte z kolumny `to do`.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Usuni%C4%99cie_domy%C5%9Blnego_zadania_'newtask'.png)



## TC02: Usunięcie nowo utworzonego zadania 

### Cel testu
Sprawdzenie, czy można usunąć zadanie wcześniej utworzone przez użytkownika.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.
3. W aplikacji znajduje się przycisk `x`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `doing` kliknij `ADD TASK`.  
   **Oczekiwany rezultat:** Wyświetla się pole umożliwiające dodanie zadania.

3. **Krok:** Wpisz nazwę zadania `c` i kliknij `OK`.  
   **Oczekiwany rezultat:** W kolumnie `doing` pojawia się nowe zadanie o nazwie `c`.

4. **Krok:** W nowo dodanym zadaniu `c` kliknij `x`.  
   **Oczekiwany rezultat:** W kolumnie `doing` nie jest widoczne zadanie o nazwie `c`.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Usuni%C4%99cie_nowo_utworzonego_zadania.png)



## TC03: Usunięcie wszystkich zadań z 3 kolumn

### Cel testu
Sprawdzenie, czy istnieje możliwość, aby w trzech domyślnych kolumnach `to do`, `doing`, `done` nie było widoczne żadne zadanie.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.
3. W kolumnie "To Do" znajduje się zadanie o domyślnej nazwie `new task`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `doing`, `done` kliknij `ADD TASK`, tak aby w trzech kolumnach znajdowało się po jednym zadaniu.  
   **Oczekiwany rezultat:** Każda kolumna zawiera po jednym zadaniu.

3. **Krok:** Wpisz nazwę i kliknij `OK`.  
   **Oczekiwany rezultat:** Zadanie zostaje dodane do kolumny.

4. **Krok:** W każdej kolumnie, przy każdym z trzech zadań kliknij `x`.  
   **Oczekiwany rezultat:** We wszystkich trzech kolumnach nie ma żadnego zadania.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Usuni%C4%99cie_wszystkich_zada%C5%84_z_trzech_kolumn.png)



# 5. Przenoszenie zadań


## TC01: Przeniesienie zadania `new task` z kolumny `to do` do kolumny `doing`

### Cel testu
Sprawdzenie, czy można przenieść zadanie `new task` z kolumny `to do` do kolumny `doing`.

### Warunki początkowe
1. Aplikacja działa poprawnie.
2. W kolumnie `to do` znajduje się zadanie z domyślną nazwą `new task`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij w miejscu, gdzie znajduje się zadanie `new task`.  
   **Oczekiwany rezultat:** Zadanie `new task` zostaje zaznaczone.

3. **Krok:** Gdy w lewym górnym rogu zobaczysz małą czarną kropkę, przeciągnij zadanie do kolumny `doing`.  
   **Oczekiwany rezultat:** Zadanie jest przenoszone do kolumny `doing`.

4. **Krok:** Upuść zadanie w kolumnie `doing`.  
   **Oczekiwany rezultat:** W kolumnie `doing` pojawia się zadanie o nazwie `new task`.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Przeniesienie_zadania.png)



## TC02: Przeniesienie czterech zadań z kolumny `to do` do kolumny `doing`

### Cel testu  
Sprawdzenie, czy można przenieść cztery zadania z kolumny `to do` do kolumny `doing`.

### Warunki początkowe  
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.  
2. W aplikacji znajduje się przycisk `ADD TASK`.  
3. W kolumnie `to do` znajduje się zadanie o domyślnej nazwie `new task`.

### Kroki testowe i oczekiwane rezultaty  

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `to do` kliknij przycisk `ADD TASK` i dodaj trzy nowe zadania.  
   **Oczekiwany rezultat:** W kolumnie `to do` znajdują się cztery zadania.

3. **Krok:** Przenieś każde z trzech zadań przeciągając je i upuszczając do kolumny `doing`.  
   **Oczekiwany rezultat:** Trzy zadania zostają pomyślnie przeniesione do kolumny `doing`.

4. **Krok:** Przeciągnij czwarte zadanie z kolumny `to do` i spróbuj upuścić je w kolumnie `doing`.  
   **Oczekiwany rezultat:** Nie można przenieść czwartego zadania do kolumny `doing`. W kolumnie `doing` widoczne są wyłącznie trzy zadania.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Przeniesienie_czterech_zadan.png)



## TC03: Przeniesienie zadań w kolumnie `doing`

### Cel testu
Sprawdzenie, czy istnieje możliwość zmiany kolejności zadań w kolumnie `doing` poprzez zastosowanie metody drag & drop.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk `ADD TASK`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W kolumnie `doing` kliknij `ADD TASK` i dodaj zadanie o nazwie `1`, zatwierdź `OK`.  
   **Oczekiwany rezultat:** W kolumnie `doing` pojawia się zadanie o nazwie `1`.

3. **Krok:** Analogicznie jak w punkcie drugim, kliknij `ADD TASK`, wpisz nazwę `2` i zatwierdź `OK`.  
   **Oczekiwany rezultat:** W kolumnie `doing` pojawiają się dwa zadania: `1` oraz `2` (w tej kolejności).

4. **Krok:** Chwyć zadanie o nazwie `2` i upuść je przed zadaniem o nazwie `1`.  
   **Oczekiwany rezultat:** W kolumnie `doing` znajdują się dwa zadania z nazwą odpowiednio `2`, `1`. Zadanie o nazwie `2` zostało przeniesione przed zadanie o nazwie `1`.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Przenoszenie_zada%C5%84_w_kolumnie.png)



# 6. Przenoszenie kolumn


## TC01: Przeniesienie kolumny `to do` za kolumnę `done`

### Cel testu
Sprawdzenie, czy istnieje możliwość przeniesienia kolumny `to do` za kolumnę `done`, tak aby znajdowała się jako ostatnia z prawej strony.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajdują się trzy kolumny odpowiednio od lewej strony: `to do`, `doing`, `done`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Chwyć za kolumnę `to do`.  
   **Oczekiwany rezultat:** Kolumna `to do` zostaje wybrana do przeniesienia.

3. **Krok:** Przenieś kolumnę `to do` i upuść tak, aby znajdowała się za kolumną `done`.  
   **Oczekiwany rezultat:** W aplikacji widoczne są trzy kolumny w kolejności: `doing`, `done`, `to do`. Kolumna `to do` została pomyślnie przeniesiona na koniec.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Przeniesienie_kolumny_'to%20do'_za_kolumn%C4%99_'done'.png)



## TC02: Przeniesienie kolumny `done` przed kolumnę `to do`

### Cel testu
Sprawdzenie, czy istnieje możliwość przeniesienia kolumny `done` tak, aby znajdowała się jako pierwsza, przed kolumną `to do`.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajdują się trzy kolumny w kolejności: `to do`, `doing`, `done`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Chwyć za kolumnę `done`.  
   **Oczekiwany rezultat:** Kolumna `done` zostaje wybrana do przeniesienia.

3. **Krok:** Przeciągnij kolumnę `done` i upuść tak, aby znajdowała się przed kolumną `to do`.  
   **Oczekiwany rezultat:** W aplikacji widoczne są trzy kolumny w kolejności: `done`, `to do`, `doing`. Kolumna `done` została pomyślnie przeniesiona na pierwsze miejsce.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Przeniesienie_kolumny_'done'_przed_kolumn%C4%99_'to%20do'.png)



## TC03: Przeniesienie nowo utworzonej kolumny o nazwie `A`

### Cel testu
Sprawdzenie, czy można przenieść kolumnę o nazwie `A`, utworzoną przez użytkownika.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajdują się trzy kolumny w kolejności: `to do`, `doing`, `done`.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk `ADD NEW COLUMN`.  
   **Oczekiwany rezultat:** Pojawia się pole do wprowadzenia nazwy nowej kolumny.

3. **Krok:** W polu nazwa wpisz `A` i zatwierdź przyciskiem `OK`.  
   **Oczekiwany rezultat:** W aplikacji widoczne są cztery kolumny w kolejności: `to do`, `doing`, `done`, `A`.

4. **Krok:** Chwyć za kolumnę `A`, przeciągnij i upuść tak, aby znajdowała się przed kolumną `to do`.  
   **Oczekiwany rezultat:** Kolumna o nazwie `A` zostaje przeniesiona przed kolumnę `to do` i widoczna jest jako pierwsza po lewej stronie.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Przeniesienie_nowo_utworzonej_kolumny.png)



# 7. Użytkowanie aplikacji


## TC01: Odświeżenie strony aplikacji

### Cel testu
Sprawdzenie, co się stanie po odświeżeniu strony oraz czy zachowana jest praca użytkownika w aplikacji.

### Warunki początkowe
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. Użytkownik posiada dodane przez siebie zadania w poszczególnych kolumnach i pracuje nad nimi.

### Kroki testowe i oczekiwane rezultaty

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** W przeglądarce kliknij "Odśwież bieżącą stronę" lub użyj skrótu klawiszowego Ctrl+R.  
   **Oczekiwany rezultat:** Po odświeżeniu strony dotychczasowa praca nie została utracona. Użytkownik nadal może pracować nad dodanymi przez siebie zadaniami.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Od%C5%9Bwie%C5%BCenie_strony_aplikacji.png)



## TC02: Ponowne otworzenie aplikacji

### Cel testu  
Sprawdzenie, co się stanie, jeśli użytkownik ponownie otworzy aplikację po jej zamknięciu.

### Warunki początkowe  
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.  
2. Aplikacja działa na zasadzie plików cookies – brak konieczności rejestracji i logowania.  
3. Użytkownik w przeglądarce zaakceptował cookies i posiada swoje zadania w poszczególnych kolumnach.

### Kroki testowe i oczekiwane rezultaty  

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.  

2. **Krok:** W przeglądarce zamknij aplikację, klikając `x`.  
   **Oczekiwany rezultat:** Aplikacja zostaje zamknięta.  

3. **Krok:** Ponownie wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** W aplikacji widoczna jest dotychczasowa praca wykonana przez użytkownika.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Ponowne_otworzenie_aplikacji.png)



## TC03: Sprawdzenie, czy użytkownik B widzi pracę użytkownika A

### Cel testu  
Sprawdzenie, czy każdy z użytkowników posiada tylko swoją indywidualną tablicę.

### Warunki początkowe  
1. Aplikacja działa poprawnie.  
2. Użytkownik A posiada swoją tablicę w przeglądarce.

### Kroki testowe i oczekiwane rezultaty  

1. **Krok:** Jako użytkownik B wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Drugi użytkownik B po wejściu na stronę aplikacji widzi wyłącznie swoją indywidualną tablicę. Nie można wyświetlić tablicy użytkownika A.


[Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Sprawdzenie_czy_u%C5%BCytkownik_widzi_swoj%C4%85_tablic%C4%99.png)


---

## Uwagi
- Każdy przypadek testowy zawiera cel, warunki wstępne, kroki oraz oczekiwane rezultaty.
- Szczegółowy projekt testów i ich wykonanie znajduje się w załączonych zrzutach ekranu.

