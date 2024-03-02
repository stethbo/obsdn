## Fuzja danych
Pod pojęciem fuzji danych rozumie się wszelkie metody umożliwiające łączenie i przetwarzanie wiedzy o badanym obiekcie lub zjawisku, pochodzącej z wielu źródeł danych (np. urządzenia [[IoT]]) w celu uzyskania stabilniejszej, dokładniejszej i użyteczniejszej informacji. Fuzja danych jest sposobem działania, za pomocą którego duża liczba danych, pochodzących z różnych źródeł może być połączona w spójną całość.
Przykłady zastosowania:
* monitorowanie stanu mostów
* optymalizacja trasy dostaw w logistyce
* wczesne wykrywanie pożarów lasów


## Metody fuzji danych
- łączenie danych z wielu źródeł lub o różnych charakterystykach
- sposoby łączenia
	- komplementarne
	- redundantne
	- kooperatywne
- poziomy łączenia
	- poziom czujników
	- poziom cech
	- poziom decyzji
	- na poziomie przestrzeni i czasu
Kluczowym elementem jest określenie momentu akwizycji.

## Metody asymilacji danych
Asymilacja danych to procesu łączenia danych zaobserwowanych z danymi modelowanymi z celu poprawy jakości obrony

Podział na typy:
- asymilacja zmiennej stanu - [[SSM]]
	- Aktualizacja wewnętrznego stanu modelu na podstawie dostępnych danych obserwacyjnych.
	- Popularne w meteorologii i oceanografii.
- asymilacja [[Filtr Kalmana|Kalmana]]
	- wykorzystuje filtr Kalmana do prognozy modelu na podstawie obserwacji
- asymilacja danych wielkoskalowych 
	- integracja danych o różnej skali przestrzennej i czasowej