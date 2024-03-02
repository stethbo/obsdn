### Definicje
**Reprezentacja wiedzy** - sposób przedstawiania informacji, który umożliwia jego przetwarzanie i wykorzystywanie przez np. algorytmy. Reprezentować można np.  za pomocą logiki, grafów, drzew, reguł.

przedstawienie informacji -> przetwarzanie i wykorzystywanie


**Logiczna reprezentacja wiedzy** - sposób przedstawiania informacji w postaci formuł logicznych o różnych rzędach logiki.

rzędy logiki - poziom skomplikowania logiki, dobór rzędu zależy od złożoności problemu i dostępnych danych
dzielą się na logiki:
- zerowego 
	- reprezentacja faktów za pomocą zdań **T/F**
- pierwszego rzędu
	- pozwala na reprezentację faktów i relacji między nimi
- drugiego rzędu
	- reprezentacja relacji między klasami obiektów  - to co w pierwszym rzędzie ale dodając kwantyfikatory po zmiennych
- wyższych rzędów
	- bardziej skomplikowane relacje i pojęcia

**Formuła logiczna** - służy do reprezentacji zdania logicznego, Występują formuły proste (atomowe) - zdania oraz formuł złożone to zdania połączone koniunkcją.
Przykład dla logiki pierwszego rzędu:
- p - "okno jest otwarte"
- q - "drzwi są zamknięte"
- r - "pokój jest zamknięty"
- $w(p)=1, w(q)=1, w(r)=0$ - wartości logiczne reprezentujące aktualny stan okien, drzwi i pokoju
- formuła złożona:    $\neg \; p\; \land q \implies r$

**Zdanie logiczne** - stwierdzenie, któremu można przypisać wartość logiczną

Są 3 rodzaje zadań związanych z LRW
1. Zadanie analizy **(ZA)** - kaki może być skutek określonego działania
2. Zadanie diagnostyki **(ZD)** - jaka jest możliwa przyczyna obserwowanych skutków
3. Zadanie podejmowania decyzji **(ZPD)** - jakie działanie zapewni pożądany skutek


### **Wnioskowanie w warunkach niepewności** 

**Wnioskowanie** - to proces osiągania konkluzji na podstawie dostępnych informacji.
**Warunki niepewności** - sytuacje, w których informacje wejściowe są niepełne, zawierają błędy, są niejasne lub mogą się zmieniać w czasie.

*Wnioskowanie w warunkach niepewności* - proces dedukcji lub indukcji, w którym dostępne informacje są niekompletne, niejednoznaczne, niepewne, posiadają błędy lub ulegają zmiany w czasie.

**Metody**
1. Logika rozmyta (ang. *fuzzy logic*)
2. Sieci Bayesowskie  - oparte na [[Metoda Bayesa|twierdzeniu Bayesa]]
3. Teoria gier
4. Algorytmy heurystyczne
5. Systemy ekspertowe

**Zastosowania**
1. [[Sztuczna Inteligencja]]
2. [[Systemy podejmowania decyzji|Systemy wspomagania decyzji]]
3. Robotyka
4. Analiza ryzyka