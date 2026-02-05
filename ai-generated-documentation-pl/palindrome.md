![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---


Oto przetłumaczona dokumentacja w języku polskim, zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

## Przegląd
Cały kod to skrypt Python, który sprawdza, czy podany tekst jest palindromem. Palindrom to słowo, fraza, liczba lub inna sekwencja znaków, która czytana od przodu i od tyłu jest taka sama, ignorując spacje, interpunkcję i wielkość liter.

## Nazwa pakietu/modułu
Kod nie należy do żadnego konkretnego pakietu ani modułu; jest to samodzielny skrypt.

## Nazwa klasy/pliku
Nazwa pliku to `palindrome.py`, a w skrypcie nie zdefiniowano żadnych klas.

## Szczegółowa dokumentacja

### Funkcja 1: check_palindrome()
- **Opis:** Ta funkcja pobiera od użytkownika tekst, usuwa spacje, konwertuje tekst do małych liter i sprawdza, czy zmodyfikowany tekst jest palindromem.
- **Parametry:** Brak (funkcja nie przyjmuje żadnych parametrów).
- **Wartości zwracane:** Zwraca `True`, jeśli tekst jest palindromem; w przeciwnym razie zwraca `False`.
- **Ważna logika:** Funkcja wykorzystuje techniki manipulacji ciągami znaków do usuwania spacji i konwersji tekstu na małe litery przed porównaniem go z odwróconą wersją. Jeśli oryginalny tekst i jego odwrócenie są takie same, funkcja zwraca `True`, wskazując, że tekst jest palindromem.

## Pseudokod
```python
// Funkcja: check_palindrome()
  1. Poproś użytkownika o wprowadzenie tekstu
  2. Zapisz input użytkownika w zmiennej o nazwie "text"
  3. Usuń spacje z "text" i przekonwertuj na małe litery
  4. Utwórz odwróconą wersję zmodyfikowanego "text"
  5. Porównaj zmodyfikowany "text" z jego odwróceniem
     - Jeśli są takie same, zwróć True (Tekst jest palindromem)
     - W przeciwnym razie zwróć False (Tekst nie jest palindromem)
```

Przypadki brzegowe i obsługa błędów:
- Kod obsługuje przypadki brzegowe, w których input zawiera spacje i różne wielkości liter, usuwając spacje i konwertując tekst na małe litery.
- Nie ma jawnej obsługi błędów w kodzie, ale jeśli użytkownik wprowadzi nieprawidłowe dane (np. wartości niebędące stringiem), skrypt zgłosi wyjątek `ValueError`.

Zależności i biblioteki:
Kod nie korzysta z żadnych zewnętrznych bibliotek. Wykorzystuje podstawowe funkcjonalności Pythona do manipulacji ciągami znaków i pobierania danych od użytkownika.