**Algorytm** -  jednoznaczny przepis obliczenia w skończonym czasie pewnych danych *wejściowych* do pewnych danych *wynikowych/wyjściowych* 

### 5 warunków algorytmu:
* skończoność
* skuteczność
* określoność
* posiada dane wejściowe i wyjściowe
* posiada ściśle określony sposób danych wejściowych w dane wyjściowe

### Sposoby reprezentacji:
* opis słowny
* lista kroków
* schemat blokowy
* pseudokod
* program komputerowy

### Przykłady wybranych algorytmów
#### Sortowanie Bąbelkowe

```
l - ciąg wejściowy (nieposortowany)
n = len(l) - długość ciągu l

for i:=0, 1, 2, …, n - 1
	for j:= 1, 2,…, n - i
		if l[j - 1] > l[j]:
			swap l[j - 1], l[j]

l - posortowany ciąg 
```

#### Algorytm Euklidesa - NWD (ang. *greatest common divisor*)
```
Ecuklides(a: integer, b: integer)
	while(b!=0)
		r := a % b
		a := b
		b := r
	return a
```
