![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

Oto przetłumaczone dokumentacja zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

1. Przegląd
Podany kod Java definiuje klasę `Service` z dwiema metodami: `isEven` i `highComplexityMethod`. Metoda `isEven` sprawdza, czy podana liczba całkowita jest parzysta, natomiast metoda `highComplexityMethod` wypisuje stwierdzenia na podstawie znaków trzech podanych liczb całkowitych.

2. Nazwa pakietu/modułu
```java
package org.example;
```
Kod należy do pakietu `org.example`.

3. Nazwa klasy/pliku
```java
public class Service {
    // ...
}
```
Klasa nazywa się `Service` i jest zdefiniowana w pliku `Service.java`.

4. Szczegółowa dokumentacja
### Funkcja/metoda 1: isEven
- Opis: Sprawdza, czy podana liczba całkowita jest parzysta.
- Parametry:
  - `input` (int): Liczba całkowita do sprawdzenia.
- Wartości zwracane:
  - boolean: Prawda, jeśli liczba wejściowa jest parzysta, w przeciwnym razie fałsz.
- Ważna logika: Metoda używa operatora modulo (`%`) do sprawdzenia, czy reszta z dzielenia liczby wejściowej przez 2 jest równa 0.

### Funkcja/metoda 2: highComplexityMethod
- Opis: Wypisuje stwierdzenia na podstawie znaków trzech podanych liczb całkowitych.
- Parametry:
  - `a` (int): Pierwsza liczba.
  - `b` (int): Druga liczba.
  - `c` (int): Trzecia liczba.
- Wartości zwracane: Brak
- Ważna logika: Metoda używa zagnieżdżonych instrukcji if-else do określenia znaków podanych liczb i wypisania odpowiednich komunikatów.

5. Pseudokod
```java
// Klasa: Service

// Metoda: isEven(int input)
  1. Sprawdź, czy wejściowa liczba jest parzysta, używając operatora modulo (input % 2 == 0)
  2. Zwróć prawdę, jeśli liczba jest parzysta; w przeciwnym razie zwróć fałsz

// Metoda: highComplexityMethod(int a, int b, int c)
  1. Sprawdź znak 'a'
    - Jeśli 'a' jest dodatnie, wypisz "a jest dodatnie"
    - W przeciwnym razie wypisz "a jest niedodatnie"
  2. Sprawdź znak 'b'
    - Jeśli 'b' jest dodatnie, wypisz "b jest dodatnie"
    - W przeciwnym razie wypisz "b jest niedodatnie"
  3. Sprawdź znak 'c'
    - Jeśli 'c' jest dodatnie, wypisz "c jest dodatnie"
    - W przeciwnym razie wypisz "c jest niedodatnie"
```