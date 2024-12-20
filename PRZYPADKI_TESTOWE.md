# Test Cases for Kanban Board

This repository contains test cases for verifying the functionality of the Kanban Board application. Below is the structured list of test cases, organized by feature.

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
  
  ![Test Case Screenshot]()


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

