*Niestacjonarność w strumieniach danych. [[Algorytm|Algorytmy]] detekcji zmian w strumieniach danych.*

**Strumień danych** sekwencja danych często powiązana relacjami, generowana i napływająca w czasie, w stałych lub zmiennych odstępach czasu.

## Algorytmy detekcji zmian w strumieniach danych

Algorytm detekcji zmian w strumieniach danych to narzędzie służące do identyfikowania punktów w czasie w których rozkład danych lub ich właściwości statystyczne ulegają zmianie.

1. ruchome okna (sliding windows)
	- Najprostszym sposobem na wykrycie danych jest sprawdzanie czy dane przychodzące znacząco różnią się od poprzednich, czyli na przykład jeśli odchylenie standardowe jakiejś cechy (parametru) przekroczy ustaloną wcześniej wartość. 
	- Chodzimy ruchomymi oknami “wzdłuż” strumienia danych i zbieramy kolejne - jeśli trafimy na wartość odstającą od reszty, informujemy o zmianie i zaczynamy tworzenie klasyfikatora od nowa.

3. metody komitetowe
	- tworzymy klasyfikatory które informują czy napływające dane są anomalią czy pochodzą z odpowiedniego rozkładu
	- klasyfikatory uczymy na bierząco tak aby wymieniać te stare

### Algorytmy
- **CUMSUM** (ang. *cumulative sum control chart*) - metoda statystyczna wykrywająca zmianę w średniej wartości sekwencji liczbowych

- **ADWIN** (ang. adaptive windowing) - algorytm który automatycznie dostosowuje wielkość okna w celu wykrycia zmiany

1. SEA
	- tworzymy zadaną liczbę klasyfikatorów i zakładamy, że powinna ona zostać stała
	- uczone są one na małych zbiorach danych
	- uczymy następne klasyfikatory i jeśli są lepsze (według wcześniej określonego kryterium) od najgorszego z naszego zbioru “roboczego”, to są one zamieniane tak, aby podnosić średnią wydajność zbioru
	- algorytm dostosowuje się do dryfu danych i niejako “podświadomie” go wykrywając, podnosi jakość klasyfikatora
    