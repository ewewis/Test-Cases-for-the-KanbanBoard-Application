# Test Cases for Kanban Board

This repository contains test cases for verifying the functionality of the Kanban Board application. Below is the structured list of test cases, organized by feature.

# Tool:
![TestLink](https://img.shields.io/badge/TestLink-yellow?style=flat?logo=TestLink)

---

# 1. Dodawanie Kolumn

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


---

## 2. Usuwanie Zadań

### Przypadek Testowy: Usunięcie Nowo Utworzonego Zadania
- **Cel**: Sprawdzenie, czy użytkownik może usunąć nowo utworzone zadanie.
- **Warunki wstępne**:  
  1. Na tablicy istnieje nowo utworzone zadanie.  
  2. Opcja „Delete” jest dostępna dla zadań.
- **Kroki**:
  1. Otwórz menu zadania.
  2. Kliknij „Delete”.
  3. Potwierdź usunięcie.
- **Oczekiwany rezultat**:  
  Zadanie zostaje poprawnie usunięte z tablicy.

---

## 3. Przenoszenie Zadań

### Przypadek Testowy: Przeniesienie Zadania do Kolumny „Done”
- **Cel**: Sprawdzenie, czy użytkownik może przenieść zadanie do kolumny „Done”.
- **Warunki wstępne**:  
  1. Na tablicy istnieje co najmniej jedno zadanie oraz kolumna „Done”.
- **Kroki**:
  1. Przeciągnij i upuść zadanie do kolumny „Done”.
- **Oczekiwany rezultat**:  
  Zadanie pojawia się w kolumnie „Done”.

---

## Uwagi
- Każdy przypadek testowy zawiera cel, warunki wstępne, kroki oraz oczekiwane rezultaty.
- Szczegółowy projekt testów i ich wykonanie znajduje się w załączonych zrzutach ekranu lub dokumentacji.

