# Test Cases for Kanban Board

This repository contains test cases for verifying the functionality of the Kanban Board application. Below is the structured list of test cases, organized by feature.

# Tool:
![TestLink](https://img.shields.io/badge/TestLink-yellow?style=flat?logo=TestLink)

---

## 1. Dodawanie Kolumn

### Przypadek Testowy: Rezygnacja z dodania nowej kolumny
- **Cel**: Sprawdzenie, czy użytkownik może anulować dodanie nowej kolumny.
- **Warunki wstępne**:  
  1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.  
  2. W aplikacji widoczny jest przycisk „Add new column”.
- **Kroki**:
  1. Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).
  2. Kliknij przycisk „Add new column”.
  3. Wpisz nazwę kolumny.
  4. Kliknij „Anuluj”.
- **Oczekiwany rezultat**:  
  Kolumna nie zostaje dodana jako ostatnia po prawej stronie.
  
  [Test Case Screenshot](https://github.com/ewewis/Test-Cases-for-the-KanbanBoard-Application/blob/main/Rezygnacja_z_dodania_nowej_kolumny.png)

### Przypadek testowy: Dodanie nowej kolumny w aplikacji [http://kanbanboard.pl/]

## Cel testu:
Sprawdzenie możliwości utworzenia nowej kolumny.

## Warunki początkowe:
1. Aplikacja [http://kanbanboard.pl/](http://kanbanboard.pl/) działa poprawnie.
2. W aplikacji znajduje się przycisk dodania nowej kolumny: „add new column”.


## Kroki testowe i oczekiwane rezultaty:

1. **Krok:** Wejdź na stronę [http://kanbanboard.pl/](http://kanbanboard.pl/).  
   **Oczekiwany rezultat:** Strona otwiera się poprawnie.

2. **Krok:** Kliknij przycisk „add new column”.  
   **Oczekiwany rezultat:** Wyświetla się okno dialogowe umożliwiające dodanie kolumny.

3. **Krok:** W polu nazwa wpisz „wakacje”.  
   **Oczekiwany rezultat:** W polu pojawia się wpisana nazwa „wakacje”.

4. **Krok:** Naciśnij „OK”.  
   **Oczekiwany rezultat:** Kolumna o nazwie „wakacje” zostaje dodana jako ostatnia po prawej stronie.





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

