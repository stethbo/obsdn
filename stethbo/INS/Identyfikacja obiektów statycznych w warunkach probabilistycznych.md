Metody identyfikacji obiektów statycznych w warunkach probabilistycznych. Identyfikacja parametryczna i nieparametryczna

**Obiekt statyczny** to obiekt, którego stan nie zmienia się w czasie, w odróżnieniu od [[system dynamiczny| obiektów dynamicznych]], które wykazują zmienne zachowanie lub stan (pojazd w ruch, ilość mikroba). Obiekty statyczne pozostają niezmienne przynajmniej w ramach rozpatrywanego okresu czasu (np. budynki, struktury geologiczne niezmieniające się cechy środowiska).

**Warunki probabilistyczne** odnoszą się do sytuacji, w których wyniki lub obserwacje są niepewne i mogą być opisane za pomocą prawdopodobieństwa. Zamiast określać czy wystąpienie pewnego zdarzenia możemy określić jego prawdopodobieństwo. To podejście jest ważne dla systemów gdzie istnieje **niepewność** danych wejściowych lub **szum** w danych (typowe warunki rzeczywiste).

Identyfikacja obiektów statycznych w warunkach probabilistycznych polega na analizowaniu i przetwarzaniu danych w sposób, który uwzględnia niepewność i pozwala na dokonanie najbardziej prawdopodobnych wniosków na podstawie dostępnych informacji.

### Metody
**Statystyka Bayesowska**  - oparte na [[Metoda Bayesa|twierdzeniu Bayesa]] czyli na łączeniu prawdopodobieństwa różnych zdarzeń
**[[Filtr Kalmana]]** - rekurencyjny algorytm służący do estymacji stanu systemu dynamicznego wa warunkach niepewności.
**[[Metoda Monte Carlo]]** - polega na losowym próbkowaniu do estymacji nieznanych parametrów których obliczenie jest zbyt skomplikowane w analityczny sposób.
Sieci neuronowe i [[Metody maszynowego uczenia się|uczenie maszynowe]] - pozwalają na zbudowanie [[Model|modeli]] złożonych zależności wynikających z dużych zbiorów danych, może to być przewidywanie wartości (np. obecność znaku drogowego na zdjęciu w [[Widzenie komputerowe|systemach widzenia komputerowego]], predykcja poziomu szczęścia na podstawie zarobków)


## Identyfikacja parametryczna i nieparametryczna



### Identyfikacja parametryczna 

- jest proces optymalizacji
Identyfikacja parametryczna polega na założeniu, że dane mogą być opisane przy pomocy modelu statystycznego o określonej, z góry ustalonej formie. Model charakteryzuje się określoną liczbą parametrów, które są estymowane na podstawie dostępnych danych.

**metody**
- Regresja liniowa
- Analiza wariancji (ANOVA)
- Model Logistyczny (aka regresja logistyczna)
- Model ARIMA - analiza szeregów czasowych

### Identyfikacja nieparametryczna

- tylko z ilości danych
- każda pojedyncza próbka ma swój rozkład gęstości
Identyfikacja nieparametryczna nie zakłada żadnej konkretnej formy modelu statystycznego, metody te są bardziej elastyczne ponieważ nie wymagają założeń co do rozkładu danych i mogą dostosować się do dowolnej struktury danych.

**metody**
- drzewa decyzyjne
- k-NN
- metody kernelowe
- estymacja jądra gęstości
	- estymator jądrowy Parzena