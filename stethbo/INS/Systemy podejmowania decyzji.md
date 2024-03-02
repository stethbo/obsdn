**Zagadnienie**
*Systemy podejmowania i wspomagania decyzji - definicje, metody i algorytmy wyznaczania decyzji, zastosowania.*

### Definicje
**Podejmowanie decyzji** - proces polegający na zbieraniu i przetwarzaniu informacji o przyszłym działaniu. Wyróżniamy przedmiot (obiekt decyzyjny/ **przedmiot decyzji**), którego decyzja dotyczy oraz podmiot podejmujący decyzję (**decydent**)

**![](https://lh7-eu.googleusercontent.com/Fq3PNv_X4QgTGLPsysGIdfGGtG6bYZQLbLOlCr0PHs5n8ECsq6yGalhSD6Bt05ytMQxvvvusElDvHmw7OvoX75hxdxMnTTNIOoYwkBI9XvYqef7rM2kANHeFyOy9eUagqXGhjslIqUEyEozJOwVde2U)**


Zamiast decydenta możemy mieć algorytm (DA)
**![](https://lh7-eu.googleusercontent.com/Cy0x27-61nnr992u3o1wPhxJ-EH-Mk5w2Z9e7ePZypJyv5AHulhwFg9RS4VzYXI2H6vEWFWnGanztpvJkV-xN31GOXhPhCDyoEpUYffgsbCJ3cNsRb505T7PSUjBxqrQmBWwb3SMdKHwHJ9U7OL7pLI)**


**System wspomagania decyzji**  - istnieje wtedy gdy decyzje generowane przez DS podlegają akceptacji przez użytkownika, systemy wspomagania decyzji możemy również spotkać jako systemy doradcze lub systemy rekomendacyjne.


**Formułowanie problemu podejmowania decyzji**
1. Dane - model obiektu podejmowania decyzji oraz wymaganie na wyjście
2. Funkcja celu - [[Model|model]] obiektu optymalizacji
3. Rozwiązanie - jaką decyzję ze zbioru decyzji dopuszczalnych, dla której wymagane wyjście jest spełnione

**Problem optymalizacji** - szukamy ekstremalnej wartości funkcji celu
**Problem decyzyjny** - udzielamy odpowiedzi "tak"/"nie" na zadane rozwiązanie

### **Metody**
**Symulowane wyżarzanie** (ang. *simulated annealing*) ^825a2c
- heurystyczna metoda optymalizacji, która polega na losowym przeszukiwaniu przestrzeni rozwiązań z uwzględnieniem temperatury, która stopniowo maleje.
- pozwala na znalezienie rozwiązania optymalnego lub bliskiego optymalnemu nawet w złożonej przestrzeni posiadającej wiele minimum lokalnych
**Tabu search**
* heurystyczna metoda optymalizacji, polega na przeszukiwaniu lokalnego sąsiedztwa aktualnego rozwiązania i wyborze najlepszego z nich, z wyjątkiem tych które są zakazane (tabu)
**Kryterium jednorodne (suma ważona/metakryterium)**
- klasyczna metoda wielokryterialnego podejmowania decyzji która polega na agregacji ocen poszczególnych kryteriów za pomocą wag, które odzwierciedlają ich znaczenie (zmienianie z wielu kryteriów na jedno)

### Zastosowania
Tego typu systemy można zastosować gdziekolwiek gdzie mamy do podjęcia jakąś decyzję.
* systemy rekomendacyjne na serwisach typu Spotify
* systemy rekomendacyjne postów i treści w serwisach społecznościowych
* diagnozowanie chorób na podstawie objawów
* systemu wspomagania decyzji inwestycyjnych
