## Wartość oczekiwana
- **Rozkład dyskretny**
$$E[X] = \sum_{x \in X}x\ \cdot p(x)$$
- **Rozkład ciągły**
$$E[X]=\int_{x\in X}x \cdot p(x)$$

## Wariancja

$$Var[X]=E[X^2] - E[X]^2 $$
## Kowariancja
$$cov[X, Y]=E[XY]-E[X]E[Y]$$
$$cov[X, Y] \in [0, \infty) $$
## Korelacja
$$corr[X, Y]=\frac{cov[X, Y]}{\sqrt{Var[X]Var[Y]}}$$
$$corr[X, Y] \in [-1, 1]$$

## Niezależność zmiennych
* dla rozkładu dyskretnego
$$P(X=x, Y=y) = P(X=x) \cdot P(Y=y) \; \text{ for all } x, y$$
* rozkład ciągły
	$$P(X \leq a, Y \leq b)=P(X\leq a) \cdot P(Y \leq b) \text{ for all } a, b$$
	more generally:
	$$f_{X,Y}(a, b) = F_x(a) \cdot F_y(b)\text{  for all }a, b$$

### Funkcji gęstości spełnia reguły
* brzegową
$$p(x)=\int p(x, y) dy$$
* łańcuchową
	$$p(x, y)=p(x | y)p(y)$$