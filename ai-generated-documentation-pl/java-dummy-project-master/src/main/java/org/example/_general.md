![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

### Uczyńmy to realnym.

---

## Dokumentacja ogólna dla pakietu przykładowego
Opis: Pakiet przykładowy składa się z dwóch głównych klas, `Client` i `Service`, które współpracują ze sobą w celu generowania spersonalizowanych powitań na podstawie długości wprowadzonego imienia. Klasa `Client` współdziała z obiektem `Service`, aby określić, czy długość imienia jest parzysta czy nieparzysta, i zwraca powitanie wielkimi literami lub w oryginalnej formie odpowiednio. Klasa `Service` udostępnia dwie metody: `isEven` do sprawdzania, czy liczba całkowita jest parzysta, oraz `highComplexityMethod` do wyświetlania stwierdzeń na podstawie znaków trzech wprowadzonych liczb całkowitych.

## Spis treści
- [Client.md](Client.md)
  - **Opis:** Klasa `Client` współdziała z obiektem `Service` w celu generowania spersonalizowanych powitań na podstawie długości wprowadzonego imienia. Sprawdza, czy imię nie jest puste lub null, i określa, czy długość imienia jest parzysta czy nieparzysta, aby zwrócić powitanie wielkimi literami lub w oryginalnej formie.
- [Service.md](Service.md)
  - **Opis:** Klasa `Service` udostępnia dwie metody: `isEven` do sprawdzania, czy liczba całkowita jest parzysta, oraz `highComplexityMethod` do wyświetlania stwierdzeń na podstawie znaków trzech wprowadzonych liczb całkowitych. Pomaga klasie `Client` w określeniu formatu powitania na podstawie długości imienia.