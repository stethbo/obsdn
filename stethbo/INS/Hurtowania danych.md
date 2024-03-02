*Proces i architektura hurtowni danych, wielowymiarowy model danych.*



**projektowanie wstępujące** - od ogółu do szczegółu, najpierw tworzone są projekty związane z poszczególnymi źródłami danych, działami przedsiębiorstwa, potrzebami użytkowników itp., a następnie projekty te scalane są w jeden projekt ogólny
**projektowanie zstępujące** - w ramach którego rozpoczynamy od stworzenia modelu przedsiębiorstwa na poziomie pojęciowym, by następnie stopniowo przejść do projektu integracji potrzebnych danych źródłowych.

Tworzenie:
1. Zbieranie danych
2. ETL
3. Przechowywanie danych
4. Zarządzanie i Utrzymanie

**źródła** -> **ETL** -> **hurtowania danych** -> **hurtownie oddziałowe** (ang. *data marts*)


![[Pasted image 20240115221150.png]]


### Wielowymiarowy model danych 
Jeden ze sposobów na przyspieszenie typowych operacji podsumowujących [[OLTP i OLAP#OLAP (ang. *online analytical processing*)|OLAP]], stosowany zwłaszcza w hurtowniach tematycznych (ang. *data marts*).

**Przykład modelu wielowymiarowego**
Baza danych zawiera zapisy transakcji sprzedaży odczytywane z kas supermarketu. Hurtownia danych gromadzi informację pochodzącą z baz źródłowych 300 sklepów sieci, rozmieszczonych w wielu miastach. Klienci są identyfikowani dzięki kartom rabatowym, z których korzystają podczas zakupów.
- Docelowa kostka jest 4-wymiarowa.
- Fakt to w tym przypadku pojedyncza sprzedaż jednego produktu jednemu klientowi (pozycja na paragonie).
- Fakty opisane są wymiarami: czas, klient, produkt, sklep.
- Miara to wartość sprzedaży i liczba sztuk.
- Poziom agregacji informacji w kostce to poziom szczegółowości opisu wymiarów, np. czas można dzielić na dni lub na kwartały, produkty można grupować w grupy produktów.
