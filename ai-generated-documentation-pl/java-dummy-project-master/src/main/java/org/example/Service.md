![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---
 1. Overview
Kod Java definiuje klasę `Service`, która zawiera dwie metody: `isEven(int input)` i `highComplexityMethod(int a, int b, int c)`. Metoda `isEven` sprawdza, czy liczba całkowita jest parzysta poprzez określenie, czy ma resztę zera podczas dzielenia przez 2. Metoda `highComplexityMethod` drukuje znaki trzech liczb (a, b i c) aby wskazać ich relację z zerem.

2. Nazwa pakietu/modułu
Kod należy do pakietu `org.example`.

3. Szczegółowe Dokumentacja
- Klasa/plik: Service.java

   - Funkcja/Metoda 1 (isEven)
     - Opis: Sprawdza, czy liczba całkowita jest parzysta poprzez określenie, czy ma resztę zera podczas dzielenia przez 2.
     - Parametry:
       - input (int): Liczba całkowita do sprawdzenia na parzystość.
     - Wartości powrotne: Wartość logiczna określająca, czy liczba całkowita jest parzysta lub nieparzysta.
     - Logika ważna: Używa operatora modulo (%).
   - Funkcja/Metoda 2 (highComplexityMethod)
     - Opis: Drukuje znaki trzech liczb (a, b i c) aby wskazać ich relację z zerem.
     - Parametry:
       - a (int): Pierwsza liczba do sprawdzenia na swój znak.
       - b (int): Druga liczba do sprawdzenia na swój znak.
       - c (int): Trzecia liczba do sprawdzenia na swój znak.
     - Wartości powrotne: Brak.
     - Logika ważna: Sprawdza znaki a, b i c za pomocą warunków logicznych.
   - Kluczowe zmienne: Brak.
   - Założenia lub zależności zewnętrzne: Nie są założone żadne zależności zewnętrzne ani założenia.

4. Pseudo Kod
```
// Klasa: Service

// Funkcja: isEven(int input)
  1. Inicjuje zmienne
  2. Sprawdza, czy input jest poprawny
    - Jeśli nie, rzuca wyjątek
  3. Określa, czy input jest parzysty za pomocą operatora modulo
  4. Zwraca wynik

// Funkcja: highComplexityMethod(int a, int b, int c)
  1. Inicjuje zmienne
  2. Sprawdza, czy a jest poprawny
    - Jeśli nie, rzuca wyjątek
  3. Określa znak a
  4. Sprawdza, czy b jest poprawny
    - Jeśli nie, rzuca wyjątek
  5. Określa znak b
  6. Sprawdza, czy c jest poprawny
    - Jeśli nie, rzuca wyjątek
  7. Określa znak c
  8. Drukuje znaki a, b i c
```