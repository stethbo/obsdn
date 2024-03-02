*Specyfika przetwarzania operacyjnego (OLTP) oraz strategicznego (OLAP), proces eksploracji oraz prezentacji danych w systemach Business Intelligence.*

## OLTP (ang. *online transactional processing*)
- relacyjne bazy danych z normalizacją danych (minimalizacja redundancji)
- transakcje 
- bankowość (frajerzy), handel, linie lotnicze
- wysoki wolumen małych transakcji
- Normalizacja danych to proces projektowania struktury bazy danych tak aby zminimalizować redundancję (powtarzanie) oraz uniknąć niepożądanych problemów takich jak anomalię w dodawaniu, aktualizacji czy usuwaniu danych.
1NF - 
## OLAP (ang. *online analytical processing*)
- złożone zapytania w dużych zbiorach danych
- SNOWFLAKE❄️ I GWIAZDA⭐️
- wielowymiarowe KOSTKI
- analiza
- magazyny danych, skomplikowane systemy raportowania, [[Hurtowania danych|hurtownie danych]]
- wysoce **zdenormalizowane** dane - przetworzone w taki sposób aby zmniejszyć liczbę tabeli
- szybki dostęp do danych (sumy, średnie) 
- analiza trendów, prognozowanie

## Proces eksploracji danych w systemach BI (ETL - *extract, transform, load*)
1. Zbieranie i integracja
2. Przetwarzanie i czyszczenie
3. Analiza i eksploracji



