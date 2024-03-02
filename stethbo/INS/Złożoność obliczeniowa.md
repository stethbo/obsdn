*Złożoność obliczeniowa. Algorytmy dokładne, aproksymacyjne i heurystyczne.*

**Złożoność obliczeniowa [[Algorytm|algorytmu]]** - ilość zasobów komputerowych potrzebnych do jego wykonania.
- złożoność czasowa
- złożoność pamięciowa 

**Złożoność czasowa** powinna być własnością samego algorytmu jako metody rozwiązania problemu, więc powinna być niezależna od komputera, języka programowania czy sposobu jego kodowania.

**![](https://lh7-eu.googleusercontent.com/Ct7GBzYITAjwu6B4J8kZ1SrDJZC67vGpBq8W9TLHtUTMg38loKWaxEXtsseVW3zPBxblRnNCz4o-nLvGtd0NCFNJAjWIsf_1zpY2l7mpS2hhr9d1WhYqCswOi1brz1jpUOjhGDasl7cyMZR3bxEBGjo)**



## P, NP, NP-complete, NP-hard
- P (ang. *polynomial* time) - czas wielomianowy
- NP (ang. *nondeterministic polynomial*) - weryfikowalne w P rozwiązywalne (w NP lub P)
- **NP-zupełne** (ang. *NP-complete*)
	- należy do klasy NP
	- dowolny problem w klasie NP może być do niego zredukowany w czasie wielomianowym
	- przykłady
		- problem cyklu Hamiltona - każdy wierzchołek w [[Grafy|grafie]] odwiedzany jest dokładnie raz
		- decyzyjna wersja problemu **Plecakowego**
		- decyzyjna wersja problemu **Komiwojażera**
- **NP-trudne** (ang. *NP-hard*) ^a9bd88
	- rozwiązanie jest conajmniej tak trudne jak każdego problemu NP
	- przykłady:
		- problem **Komiwojażera**
		- problem **Plecakowy**

![[Pasted image 20240117160950.png]]


## Klasyfikacja algorytmów
- **Algorytmy dokładne** - dla danej instancji problemu obliczają jego dokładne rozwiązanie


- **Algorytmy aproksymacyjne** - dla jednej instancji problemu obliczają jego przybliżone rozwiązanie z zadaną dokładnością
	- matematyczny stosunek do rozwiązania optymalnego
	- oparte na solidnych teorytycnzych fundamentach
	- często stosuje się je do problemów NP-trudnych


- **Algorytmy heurystyczne** - heurystyką nazywamy algorytm (metodę) zwracający rozwiązanie przybliżone. Zazwyczaj oczekuje się, że algorytm taki ma złożoność wielomianową i działa szybko w praktyce. Heurystyki wykorzystujemy gdy wyliczenie dokładnego wyniku jest niemożliwe/ trwa zbyt długo. Metoda heurystyczna dla problemów optymalizacyjnych nie gwarantuje znalezienia optymalnego rozwiązania. Powinna dążyć do wygenerowania rozwiązania dopuszczalnego o wartości funkcji celu jak najbliższej optymalnej.
	- [[Metody optymalizacji#^57d92b|symulowane wyżarzanie]]
	- tabu search
	- Algorytm genetyczny
	- Algorytmy zachłanne (Greedy Algorithm)
