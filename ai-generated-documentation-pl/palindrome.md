![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

### Uczyń to rzeczywistym.

---

## Przegląd
Cały kod to skrypt Python, który sprawdza, czy podany tekst jest palindromem. Palindrom to słowo, fraza, liczba lub inna sekwencja znaków, która czytana od przodu i od tyłu jest taka sama, ignorując spacje, interpunkcję i wielkość liter.

## Nazwa pakietu/modułu
Nazwa pakietu lub modułu nie jest podana w kodzie.

## Nazwa klasy/pliku
Nazwa pliku to "palindrome.py".

## Dokumentacja szczegółowa
### Funkcja 1: check_palindrome()
- **Opis:** Ta funkcja pobiera tekst od użytkownika, usuwa spacje, konwertuje wszystkie znaki na małe litery i sprawdza, czy zmodyfikowany tekst jest palindromem.
- **Parametry:** Brak (funkcja korzysta ze zmiennej globalnej "text", która jest ustawiana poza funkcją).
- **Wartości zwracane:** Wartość logiczna (True, jeśli tekst jest palindromem, False w przeciwnym razie).
- **Logika kluczowa:** Funkcja usuwa spacje z wprowadzonego tekstu i konwertuje wszystkie znaki na małe litery. Następnie sprawdza, czy zmodyfikowany tekst jest równy swojemu odwróceniu. Jeśli są równe, funkcja zwraca True; w przeciwnym razie zwraca False.

## Pseudokod
```python
// Funkcja: check_palindrome()
  1. Poproś użytkownika o wprowadzenie tekstu: "Wprowadź swój tekst:"
  2. Zapisz wprowadzone dane w zmiennej 'text'
  3. Usuń spacje ze zmiennej 'text' i przekonwertuj wszystkie znaki na małe litery
  4. Sprawdź, czy zmodyfikowana zmienna 'text' jest równa swojemu odwróceniu
     - Jeśli są równe, zwróć True
     - W przeciwnym razie zwróć False
```
Przypadki brzegowe i obsługa błędów:
- Kod obsługuje przypadek, gdy wprowadzony tekst zawiera spacje, usuwając je przed sprawdzeniem palindromu.
- Kod obsługuje również przypadek, gdy wprowadzony tekst ma różną wielkość liter, konwertując wszystkie znaki na małe litery przed sprawdzeniem palindromu.
- W kodzie nie ma jawnej obsługi błędów, ale naturalnie obsłuży on nieprawidłowe dane wejściowe (np. nieciągi znaków), ponieważ funkcja `input()` w Pythonie zgłosi wyjątek `ValueError`.

### Zależności i biblioteki
Kod nie korzysta z żadnych zewnętrznych bibliotek.