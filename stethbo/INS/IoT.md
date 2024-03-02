*Sieci usług, sieci sensorowe, systemy Internetu Rzeczy, analiza wydajności, zarządzanie, bezpieczeństwo i zastosowania*

### System internetu rzeczy

**Definicja**
Jest to system urządzeń elektronicznych, które mogą wymieniać informację między za pomocą sieci Internet bez pomocy człowieka. IoT oznacza sieć obiektów fizycznych które są wyposażone w czujniki, oprogramowanie i inne technologie w celu łączenia się i wymiany danych. Korzystają z [[Architektura rozproszona|architektury rozproszonej]].

**Analiza wydajności**
Systemy te wymagają wydajnej sieci internetowej, która umożliwia na szybkie przekazywanie informacji. Wdrażanie sieci 5G od 2020 roku umożliwia rozwój tej technologii.

**Zarządzanie**
- PODSTAWA - ważne jest zdolność do zdalnej komunikacji wielu urządzeń
- protokół MQTT - służy do komunikacji między urządzeniami a serwerem, serwer zarządza rozproszonym czujnikami / sensorami poprzez wysyłanie poleceń tym protokołem, podejmuje decyzje na podstawie danych napływających z czujników (również droga IoT)
- platformy zarządzania takie jak *AWS IoT* czy *MS Azure IoT* ([[Metody chmur i mgieł obliczeniowych|systemy chmurowe]])
- ważną kwestią jest zarządzanie zasobami energetycznymi gdyż urządzenia IoT często znajdują się w miejscach z ograniczonym dostępem do pasma energetycznego 

**Bezpieczeństwo**
Ze względu na rozproszony charakter system IoT jest podatny na wiele ataków a przekazywane dane płynące z wielu źródeł mogą być przechwycone przez niechcianych użytkowników.

dlatego stosuje się 
- szyfrowanie
- uwierzytelnianie
- regularne aktualizacje oprogramowania
- zabezpieczenia na poziomie sprzętu jak i oprogramowania
- zagrożenia związane z adopcją (ktoś uwierzy asystentowi Alexa lub pozostawi dziecko pod opieką lodówki)

**Zastosowania**
- inteligentny dom
- inteligentne miasta
	- monitoring wolnych miejsc na parkingu
	- system rozpoznawania tablic rejestracyjnych na parkingu
- rolnictwo
	- monitorowanie warunków gleby, nawadnianie, dawkowanie nawozów, zbieranie
	- śledzenie zdrowia zwierząt hodowlanych
- zarządzanie energią
- Przemysł 4.0  - internet rzeczy jest wykorzystywany do monitorowania i optymalizacji procesów produkcyjnych


## Sieci sensorowe

Sieci sensorowe (ang. *wireless sensor networks*) czyli inaczej sieci czujników bezprzewodowych, to systemy złożone z wielu urządzeń sensorowych, które współpracują ze sobą w celu zbierania i przesyłania informacji o środowisku. Urządzenia nazywane są węzłami sensorowymi, są małe, energooszczędne i mogą być rozmieszczone w trudno dostępnych miejscach.

**Zarządzanie**
- konfiguracja i rozmieszczenie czujników
- monitorowanie stanu sieci
- aktualizacje i konserwacja

## Różnice między IoT i WSN

![[Pasted image 20240114222424.png]]


## Sieci usług (ang. *service networks*)

Sieci usług (ang. service networks) to sieci telekomunikacyjne, które umożliwiają dostarczanie usług telekomunikacyjnych, takich jak połączenia głosowe, transmisja danych, przesyłanie obrazów i wideo, itp. do klientów. Sieci usług obsługują różnorodne rodzaje usług, takie jak transmisja danych, dostęp do Internetu, usługi VoIP (Voice over IP), streaming wideo, usługi chmurowe, aplikacje internetowe, a także nowoczesne usługi oparte na Internet of Things (IoT).
