## Systemy chmurowe
Chmura obliczeniowa to model dostarczania usług komputerowych, takich jak przechowywanie danych, przetwarzanie, analiza danych, a także dostęp do zasobów sieciowych, bez konieczności posiadania własnej infrastruktury. Usługi chmury obliczeniowej mogą być udostępniane na żądanie, elastyczne i skalowalne.

### Infrastruktury
#### Infrastructure as a Service (IaaS):
IaaS dostarcza wirtualną infrastrukturę, umożliwiającą użytkownikom korzystanie z maszyn wirtualnych, pamięci masowej i sieci.
Przykłady: Amazon EC2, Microsoft Azure Virtual Machines, Google Compute Engine.

#### Platform as a Service (PaaS):
PaaS dostarcza platformę programową, umożliwiającą programistom tworzenie, testowanie i wdrażanie aplikacji bez konieczności zarządzania infrastrukturą.
Przykłady: Heroku, Google App Engine, Microsoft Azure App Service.

#### Software as a Service (SaaS):
SaaS dostarcza gotowe do użycia aplikacje przez internet, bez konieczności instalowania, aktualizowania ani utrzymywania lokalnie.
Przykłady: Salesforce, Google Workspace, Microsoft 365.

#### Function as a Service (FaaS) / Serverless Computing:
FaaS umożliwia uruchamianie funkcji bez konieczności zarządzania serwerami. Opłacasz tylko za rzeczywisty czas pracy funkcji.
Przykłady: AWS Lambda, Azure Functions, Google Cloud Functions.


![[Pasted image 20240118154426.png]]


## Mgła obliczeniowa
Mgła obliczeniowa (ang. *fog computing*) to model, w którym obliczenia są rozproszone pomiędzy urządzeniami końcowymi a chmurą, znajdującą się bliżej tych urządzeń. Mgła pozwala na przetwarzanie danych bliżej źródła, co może skutkować niższym opóźnieniem i lepszą wydajnością w porównaniu do tradycyjnych chmur.
Systemy mgłowe są często [[Architektura rozproszona|systemami rozproszonymi]].


### Zastosowania
- [[IoT]]
- analiza danych w czasie rzeczywistym
- lokalne przetwarzanie danych


## Rozwiązania hybrydowe 
- połączenie chmury publicznej (i.e AWS) z chmurą prywatną (i.e. zasoby które posiada pewne przedsiębiorstwo)