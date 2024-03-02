Filtr Kalmana to [[algorytm]] służący do estymacji i predykcji stanu systemu w warunkach niepewności. Jest szeroko używany w nawigacjach, systemach śledzenia obiektu itp.
Stosuje się do obiektów danych równaniem różnicowym **liniowym**. Jego działanie można podzielić na dwa etapy: **predykcja** i **korekcja**.

Filtr Kalmana opiera się na dwóch podstawowych równaniach:
- równanie stanu
- równanie pomiaru
Oba te równania zawierają parametry, które mogą zawierać szumy i zakłócenia (zazwyczaj mają one rozkład normalny) 

**Przebieg**
- inicjalizacja (może to być pomiar)
- predykcja (następnego stanu systemu)
- korekcja (wzmocnienie Kalmana)


**Rozszerzony filtr Kalmana** (ang. *extended Kalmana filter* -  EKF) - to zaawansowana wersja algorytmu rozszerzająca jego działanie o układy nieliniowe. 