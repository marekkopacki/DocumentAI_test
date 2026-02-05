![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

Oto przetłumaczone dokumentacja i pseudokod w języku polskim, zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

1. Przegląd
Podany kod Java definiuje klasę `Service` z dwiema metodami: `isEven` i `highComplexityMethod`. Metoda `isEven` sprawdza, czy liczba całkowita jest parzysta, natomiast `highComplexityMethod` wyświetla komunikaty na podstawie znaków trzech liczb całkowitych (dodatnich, niedodatnich lub zerowych).

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

   - Funkcja/metoda 1: isEven(int input)
     - Opis: Sprawdza, czy podana liczba całkowita jest parzysta.
     - Parametry: 
       - `input` (int): Liczba całkowita do sprawdzenia.
     - Wartości zwracane: 
       - boolean: Prawda, jeśli input jest parzysty, w przeciwnym razie fałsz.
     - Ważna logika: Wykorzystuje operator modulo (`%`) do określenia, czy input jest podzielny przez 2.

   - Funkcja/metoda 2: highComplexityMethod(int a, int b, int c)
     - Opis: Wyświetla komunikaty na podstawie znaków trzech liczb całkowitych (dodatnich, niedodatnich lub zerowych).
     - Parametry: 
       - `a` (int): Pierwsza liczba całkowita.
       - `b` (int): Druga liczba całkowita.
       - `c` (int): Trzecia liczba całkowita.
     - Wartości zwracane: Brak
     - Ważna logika: Wykorzystuje zagnieżdżone instrukcje if-else do sprawdzania znaków liczb i wyświetlania odpowiednich komunikatów.

5. Pseudokod
```java
// Klasa: Service

// Metoda: isEven(int input)
  1. Sprawdź, czy input jest podzielny przez 2 za pomocą operatora modulo.
  2. Zwróć prawdę, jeśli input jest parzysty (input % 2 == 0), w przeciwnym razie zwróć fałsz.

// Metoda: highComplexityMethod(int a, int b, int c)
  1. Sprawdź znak liczby 'a':
     - Jeśli 'a' jest zero, wyświetl "a jest dodatnie".
       - Sprawdź znak liczby 'b':
         - Jeśli 'b' jest dodatnia, wyświetl "b jest dodatnia".
           - Sprawdź znak liczby 'c':
             - Jeśli 'c' jest dodatnia, wyświetl "c jest dodatnia".
             - W przeciwnym razie wyświetl "c jest niedodatnia".
         - W przeciwnym razie wyświetl "b jest niedodatnia".
           - Sprawdź znak liczby 'c':
             - Jeśli 'c' jest dodatnia, wyświetl "c jest dodatnia".
             - W przeciwnym razie wyświetl "c jest niedodatnia".
     - W przeciwnym razie (a jest ujemna), wyświetl "a jest niedodatnia".
       - Sprawdź znak liczby 'b':
         - Jeśli 'b' jest dodatnia, wyświetl "b jest dodatnia".
           - Sprawdź znak liczby 'c':
             - Jeśli 'c' jest dodatnia, wyświetl "c jest dodatnia".
             - W przeciwnym razie wyświetl "c jest niedodatnia".
         - W przeciwnym razie wyświetl "b jest niedodatnia".
           - Sprawdź znak liczby 'c':
             - Jeśli 'c' jest dodatnia, wyświetl "c jest dodatnia".
             - W przeciwnym razie wyświetl "c jest niedodatnia".
     - W przeciwnym razie (a jest dodatnia), wyświetl "a jest dodatnia".
       - Sprawdź znak liczby 'b':
         - Jeśli 'b' jest dodatnia, wyświetl "b jest dodatnia".
           - Sprawdź znak liczby 'c':
             - Jeśli 'c' jest dodatnia, wyświetl "c jest dodatnia".
             - W przeciwnym razie wyświetl "c jest niedodatnia".
         - W przeciwnym razie wyświetl "b jest niedodatnia".
           - Sprawdź znak liczby 'c':
             - Jeśli 'c' jest dodatnia, wyświetl "c jest dodatnia".
             - W przeciwnym razie wyświetl "c jest niedodatnia".
```