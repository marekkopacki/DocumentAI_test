![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

Oto przetłumaczone dokumentacja zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

## Dokumentacja ogólna dla pakietu example
Dokumentacja wygenerowana na podstawie dostarczonych plików Markdown. Pakiet `example` składa się z dwóch głównych klas, `Client` i `Service`, które współpracują ze sobą w celu zapewnienia spersonalizowanych powitań na podstawie długości wprowadzonych imion. Klasa `Client` oddziałuje z obiektem `Service`, aby określić, czy długość nazwy jest parzysta lub nieparzysta i zwraca odpowiednie powitanie. Klasa `Service` zawiera metody do sprawdzania, czy liczba całkowita jest parzysta oraz drukowania stwierdzeń na podstawie znaków trzech wprowadzonych liczb całkowitych.

## Spis treści
- [Client.md](Client.md)
  - **Opis:** Klasa `Client` oddziałuje z obiektem `Service`, aby generować spersonalizowane powitania na podstawie długości wprowadzonego imienia. Sprawdza, czy nazwa nie jest pusta lub null i określa, czy jej długość jest parzysta czy nieparzysta, zwracając powitanie wielkimi literami lub oryginalnym przypadku odpowiednio.
- [Service.md](Service.md)
  - **Opis:** Klasa `Service` dostarcza dwie metody: `isEven`, która sprawdza, czy wprowadzona liczba całkowita jest parzysta oraz `highComplexityMethod`, która drukuje stwierdzenia na podstawie znaków trzech wprowadzonych liczb całkowitych. Pomaga klasie `Client` w określeniu odpowiedniego formatu powitania.