![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---


Oto przetłumaczona dokumentacja zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

## Przegląd
Cały kod to skrypt Python, który sprawdza, czy podany tekst jest palindromem. Palindrom to słowo, fraza, liczba lub inna sekwencja znaków, która czytana od przodu i od tyłu jest taka sama, ignorując spacje, interpunkcję i wielkość liter.

## Nazwa pakietu/modułu
Kod nie należy do żadnego konkretnego pakietu ani modułu; jest to samodzielny skrypt.

## Nazwa klasy/pliku
Nazwa pliku to "palindrome.py", a w skrypcie nie zdefiniowano żadnych klas.

## Szczegółowa dokumentacja

### Funkcja 1: check_palindrome()
- **Opis:** Ta funkcja pobiera od użytkownika tekst, usuwa spacje i konwertuje tekst do małych liter, a następnie sprawdza, czy zmodyfikowany tekst jest palindromem.
- **Parametry:** Brak (funkcja korzysta ze zmiennej globalnej "text" do przechowywania danych wejściowych użytkownika)
- **Wartości zwracane:** Wartość logiczna (True, jeśli tekst jest palindromem; False w przeciwnym razie)
- **Logika kluczowa:** Funkcja usuwa spacje z tekstu i konwertuje go do małych liter przed porównaniem z jego odwróceniem. Jeśli oryginalny i odwrócony tekst są równe, funkcja zwraca True; w przeciwnym razie zwraca False.

## Pseudokod
```
// Funkcja: check_palindrome()
  1. Poproś użytkownika o wprowadzenie tekstu
  2. Zapisz dane wejściowe użytkownika w zmiennej globalnej "text"
  3. Usuń spacje z "text" i przekonwertuj na małe litery
  4. Sprawdź, czy zmodyfikowany "text" jest równy swojemu odwróceniu
     - Jeśli tak, zwróć True
     - W przeciwnym razie zwróć False
```

Przypadki brzegowe i obsługa błędów:
- Kod obsługuje przypadek, gdy wejście zawiera spacje, usuwając je przed sprawdzeniem palindromu.
- Kod również obsługuje przypadek, gdy wejście jest w różnych przypadkach (wielkie lub małe litery), konwertując cały tekst na małe litery.
- Nie ma jawnej obsługi błędów w kodzie, ale zwróci False, jeśli użytkownik wprowadzi pusty ciąg lub wartości niebędące łańcuchem (ze względu na sposób działania funkcji "input" w Pythonie).

Zależności i biblioteki:
Kod nie ma żadnych konkretnych zależności ani bibliotek poza standardowymi funkcjonalnościami wejścia/wyjścia Pythona i manipulacją ciągami znaków. Równoważną funkcjonalność można osiągnąć w innych językach programowania, korzystając z ich odpowiednich standardowych bibliotek do obsługi wejścia/wyjścia i manipulacji ciągami znaków.