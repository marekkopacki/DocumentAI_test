![Capgemini Logo](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Make it real.

---

Oto przetłumaczona dokumentacja w języku polskim, zgodnie z podanymi wytycznymi:

![Logo Capgemini](https://www.capgemini.com/wp-content/themes/capgemini2020/assets/images/logo.svg)

### Uczyń to rzeczywistym.

---

## Przegląd
Dostarczony `pom.xml` jest skryptem budowania Maven dla projektu Java o nazwie "dummy-java-project" z grupy "org.example". Skrypt konfiguruje zależności projektu, ustawienia kompilatora i framework testowy. Wykorzystuje JUnit 5 jako framework testowy wraz z bibliotekami Mockito i AssertJ.

## Narzędzie budowania
Maven (Apache Maven)

## Nazwa skryptu/pliku
`pom.xml` (Plik modelu projektu)

## Dokumentacja szczegółowa

### Zadanie 1: Konfiguracja projektu
- **Opis:** Definiuje podstawowe informacje o projekcie, takie jak identyfikator grupy, identyfikator artefaktu i wersję.
- **Parametry:**
  - `groupId` (String): Unikalny identyfikator projektu w repozytorium.
  - `artifactId` (String): Nazwa projektu.
  - `version` (String): Numer wersji projektu.
- **Ważna logika:** Ustanawia podstawę dla procesu budowania Maven.

### Zadanie 2: Konfiguracja właściwości
- **Opis:** Konfiguruje różne właściwości budowania, takie jak wersje źródłowe i docelowe kompilatora Java oraz kodowanie UTF-8.
- **Parametry:**
  - `maven.compiler.source` (Integer): Wersja źródłowa kompilatora Java.
  - `maven.compiler.target` (Integer): Wersja docelowa kompilatora Java.
  - `project.build.sourceEncoding` (String): Kodowanie znaków dla plików źródłowych.
- **Ważna logika:** Zapewnia, że projekt jest budowany z odpowiednią wersją Javy i kodowaniem.

### Zadanie 3: Zarządzanie zależnościami
- **Opis:** Deklaruje zależności wymagane przez projekt, w tym Mockito, AssertJ i JUnit 5.
- **Parametry:**
  - `groupId` (String): Unikalny identyfikator zależności w repozytorium.
  - `artifactId` (String): Nazwa zależności.
  - `version` (String): Numer wersji zależności.
  - `scope` (String): Zakres, w którym używana jest zależność (np. kompilacja, test).
- **Ważna logika:** Zarządza zależnościami niezbędnymi dla projektu do prawidłowego funkcjonowania.

### Zadanie 4: Konfiguracja budowania
- **Opis:** Konfiguruje proces budowania Maven, w tym plugin testowy (SureFire).
- **Parametry:**
  - `groupId` (String): Unikalny identyfikator pluginu w repozytorium.
  - `artifactId` (String): Nazwa pluginu.
  - `version` (String): Numer wersji pluginu.
- **Ważna logika:** Zapewnia, że projekt jest budowany i testowany prawidłowo.

## Wersja języka
Java 17 (określona przez `maven.compiler.source` i `maven.compiler.target`)

## Wersje zależności
- Mockito Core: 5.6.0
- AssertJ Core: 3.24.2
- JUnit Jupiter Engine: 5.10.0
- JUnit Jupiter API: 5.10.0
- Mockito JUnit Jupiter: 5.6.0

## Pseudokod
```plaintext
/* Skrypt budowania Maven dla "dummy-java-project" */

1. Zdefiniuj informacje o projekcie:
   - groupId: org.example
   - artifactId: dummy-java-project
   - version: 1.0-SNAPSHOT

2. Skonfiguruj właściwości budowania:
   - kompilator źródłowy i docelowy: Java 17
   - kodowanie znaków źródłowych: UTF-8

3. Zadeklaruj zależności projektu:
   - Mockito Core (5.6.0, test)
   - AssertJ Core (3.24.2, test)
   - JUnit Jupiter Engine (5.10.0, test)
   - JUnit Jupiter API (5.10.0, test)
   - Mockito JUnit Jupiter (5.6.0, test)

4. Skonfiguruj pluginy budowania:
   - SureFire Plugin (3.0.0) do testowania

5. Zbuduj projekt z określoną konfiguracją i zależnościami.
6. Uruchom testy przy użyciu skonfigurowanego pluginu SureFire.
```

## Równoważniki zależności i pluginów
- Maven SureFire Plugin: Gradle Testing Base Plugin (dla JUnit)
- Mockito: EasyMock (Gradle), jest-mock (npm)
- AssertJ: Chai (npm), Shoulda (Ruby)