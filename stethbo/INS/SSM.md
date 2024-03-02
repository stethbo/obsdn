*Modele w przestrzeni stanów. Ocena jakości i porównanie modeli.*
## SSM (ang. *state space model*)
**[[Model]] w przestrzeni stanu** (ang. *state space model*) (SSM) - jest to matematyczny model opisujący układ dynamiczny stosowany w analizie i modelowaniu [[systemów dynamicznych]], szczególnie w kontekście czasu rzeczywistego i [[systemów sterowania]].
Reprezentuje system przy pomocy zbioru wejść, wyjść oraz zmiennych stanów reprezentowanych przez układ równań różniczkowych ([[systemy ciągłe]]) lub [[Metody modelowania systemów dyskretnych#Równanie różnicowe|równań różnicowych]] ([[systemy dyskretne]]).
Stan zawiera skumulowaną informację z całej przeszłości układu, aż do danej chwili.
W przypadku większości układów wyjście układu $y$ w chwili $t_n$ nie tylko zależy od wejść układu $u_n$ ale również od stanu poprzedniego $x_{t-1}$ 

Przykładem takiego modelu jest [[Filtr Kalmana]]


stan - w jakiej pozycji znajduje się obiekt, np. odległość rakiety🚀 od ziemi

**Stan równowagi**
- układ znajduje się w stanie równowagi gdy po jego osiągnięciu w nim pozostaje



**Metody oceny jakości model**
1. Błąd średnio kwadratowy - [[MSE]]
2. Metoda estymacji Bayesa -  [[Metoda Bayesa]]
3. Metoda maksymalnej wiarygodności ([[MLE]]) -- maksymalizujemy funkcję poprzez dobieranie różnych rozkładów (mogą być zastosowane metody gradientowe), np. od doboru parametrów filtru Kalmana

