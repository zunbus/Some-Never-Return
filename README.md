# Nie Każdy Wraca

**Nie Każdy Wraca (Some Never Return)** to pierwszoosobowy symulator służb ratowniczych tworzony przez zespół GLORPO TEAM z wykorzystaniem silnika Unreal Engine 5.

Akcja gry rozgrywa się we współczesnej Polsce, w fikcyjnym mieście Czarnowierch, położonym w Karpatach. Gracz wciela się w operatora numeru alarmowego 112, zarządza działaniami Zintegrowanego Centrum Ratowniczego (ZCR) oraz bierze bezpośredni udział w akcjach ratowniczych jako członek zespołów Państwowej Straży Pożarnej (PSP), Górskiego Ochotniczego Pogotowia Ratunkowego (GOPR) i Tatrzańskiego Ochotniczego Pogotowia Ratunkowego (TOPR).

Projekt łączy symulację działań ratowniczych, zarządzanie personelem, proceduralne generowanie misji, rozwój technologiczny oraz narrację środowiskową. Szczególny nacisk położono na odpowiedzialność za podejmowane decyzje, bezpieczeństwo ratowników i konsekwencje niepowodzeń.

---

## Informacje o projekcie

| Parametr | Wartość |
|---|---|
| Nazwa projektu | Nie Każdy Wraca |
| Tytuł angielski | Some Never Return |
| Zespół | GLORPO TEAM |
| Gatunek | Symulator służb ratowniczych |
| Perspektywa | Pierwszoosobowa (FPP) |
| Silnik gry | Unreal Engine 5 |
| Platforma docelowa | PC |
| System operacyjny | Windows 10/11 |
| Konkurs | Motorola Solutions Science Cup 2027 |
Struktura Folderów:
```
./
├── Game/            <- Projekt gry (Unreal Engine 5.8)
├── Docs/            <- Dokumenty
└── RawAssets/       <- Czyste Assety
    ├── Textures/    <- Assety 2d
    ├── 3dAssets/    <- Assety 3d
    └── Audio/       <- Muzyka/SFX
```
## Główne założenia rozgrywki

Podstawą rozgrywki jest zarządzanie Zintegrowanym Centrum Ratowniczym oraz bezpośredni udział w akcjach ratowniczych.

Gracz rozpoczyna służbę jako operator centrum ratowniczego. Przyjmuje zgłoszenia alarmowe, przygotowuje zespoły do interwencji, a następnie uczestniczy w działaniach ratowniczych.

### Dostępne służby ratownicze

**Państwowa Straż Pożarna (PSP)**

Interwencje PSP koncentrują się na gaszeniu pożarów, ratownictwie technicznym i reagowaniu na zagrożenia miejskie.

Przykładowe rodzaje zdarzeń:
- Pożary budynków.
- Zawalenia konstrukcji budowlanych.
- Pożary lasów.
- Wypadki drogowe i karambole.
- Podtopienia budynków.
- Zdarzenia związane z substancjami niebezpiecznymi.

**Górskie Ochotnicze Pogotowie Ratunkowe (GOPR)**

Interwencje GOPR obejmują poszukiwanie zaginionych turystów, docieranie do osób poszkodowanych i prowadzenie działań ratowniczych w wymagających warunkach górskich.

Przykładowe rodzaje zdarzeń:
- Zaginięcia turystów.
- Wypadki górskie.
- Wypadki narciarskie.
- Zagubieni narciarze.
- Wypadki wspinaczkowe.
- Interwencje w trudno dostępnym terenie.

**Tatrzańskie Ochotnicze Pogotowie Ratunkowe (TOPR)**

TOPR stanowi wyspecjalizowany element działań ratowniczych w górach. Interwencje obejmują bardziej wymagające scenariusze, w tym akcje wykorzystujące śmigłowiec ratowniczy.

### Główna pętla rozgrywki

1. Przyjęcie zgłoszenia alarmowego w ZCR.
2. Wybór odpowiedniej interwencji i służby ratowniczej.
3. Przygotowanie zespołu oraz wyposażenia.
4. Dotarcie na miejsce zdarzenia.
5. Rozpoznanie sytuacji i przeprowadzenie działań ratowniczych.
6. Uratowanie poszkodowanych i zabezpieczenie miejsca zdarzenia.
7. Powrót do ZCR.
8. Analiza wyników i rozwój infrastruktury centrum.

---

## Systemy rozgrywki

### Proceduralne generowanie misji

Z wyjątkiem dwóch pierwszych interwencji, pełniących funkcję samouczków, kolejne misje są generowane proceduralnie.

Ich charakterystyka zależy od kilku czynników:
- Rodzaju zdarzenia.
- Lokalizacji interwencji.
- Warunków atmosferycznych i środowiskowych.
- Charakterystyki zagrożeń.

System ma zapewniać różnorodność kolejnych interwencji poprzez zmienność ich przebiegu i warunków realizacji.

### Rozwój personelu i permanentna utrata postaci

Dowódcy zespołów ratowniczych zdobywają doświadczenie podczas kolejnych interwencji. Rozwijają swoje kompetencje i możliwości operacyjne.

Jednocześnie każda akcja wiąże się z ryzykiem utraty członków zespołu.

Śmierć dowódcy podczas interwencji jest permanentna. Utracona postać zostaje usunięta z aktywnego personelu, a jej historia zostaje upamiętniona w specjalnej sekcji **In Memoriam** w Zintegrowanym Centrum Ratowniczym.

Nowy dowódca przejmuje stanowisko poprzednika i część jego zdobytego doświadczenia.

System podkreśla znaczenie odpowiedzialnego zarządzania personelem oraz konsekwencje podejmowanych decyzji.

### System oceny interwencji

Każda misja podlega ocenie punktowej, której maksymalna wartość bazowa wynosi 1000 punktów.

Na końcowy wynik wpływają między innymi:
- Liczba uratowanych osób.
- Stan zdrowia uratowanych poszkodowanych.
- Bezpieczeństwo członków zespołu.
- Straty w personelu.
- Straty materialne.
- Realizacja celów misji.

Wynik może przyjmować również wartości ujemne, które są odejmowane od łącznej sumy punktów gracza.

Zdobywane punkty stanowią podstawę systemu progresji technologicznej.

### Rozwój technologiczny ZCR

Za osiągnięcia podczas interwencji gracz zdobywa żetony misji, wykorzystywane do odblokowywania nowych technologii.

System rozwoju technologicznego został podzielony na dwie niezależne ścieżki:

- Komunikacja i obsługa dyspozytorska.
- Rozpoznanie i świadomość sytuacyjna.

W projekcie wykorzystano wybrane rozwiązania technologiczne Motorola Solutions, które zostały odwzorowane jako mechaniki rozgrywki.

Przykładowe technologie:
- PremierOne CAD.
- CommandCentral Aware.
- Avigilon Unity Video.
- APX NEXT.
- CAPE Drone Software.
- Spillman Flex CAD.

Odblokowywane rozwiązania zapewniają dostęp do dodatkowych informacji o zdarzeniach, usprawniają komunikację i zwiększają możliwości operacyjne centrum.

### Zintegrowane Centrum Ratownicze

ZCR jest główną przestrzenią eksploracji oraz centrum zarządzania rozgrywką.

W jego skład wchodzą:
- Dyspozytornie PSP i GOPR.
- Garaże pojazdów ratowniczych.
- Pomieszczenia operacyjne.
- Zaplecze techniczne.
- Pomieszczenia personelu.
- Infrastruktura komunikacyjna.
- Lądowisko dla śmigłowca ratowniczego.

Wraz z postępami w rozgrywce kolejne pomieszczenia i obszary centrum stają się dostępne.

ZCR pełni również funkcję przestrzeni narracyjnej, w której gracz poznaje historię placówki, jej personelu i wcześniejszych interwencji.

---

## Świat gry i narracja

Akcja gry toczy się w fikcyjnym mieście Czarnowierch, położonym w dolinie rzeki Czarna Woda, u podnóża Pasma Czarnowierskiego.

Miasto łączy infrastrukturę przemysłową, gęstą zabudowę mieszkaniową oraz obszary górskie. Zróżnicowanie geograficzne stanowi podstawę dla proceduralnego generowania interwencji.

Narracja opiera się przede wszystkim na opowiadaniu historii poprzez otoczenie.

Informacje o świecie i jego mieszkańcach przekazywane są za pomocą:
- Dokumentów i raportów.
- Fotografii i przedmiotów osobistych.
- Komunikatów radiowych.
- Zmian zachodzących w otoczeniu.
- Interakcji z elementami ZCR.
- Sekcji In Memoriam.

Główny bohater, operator centrum ratowniczego, nie posiada narzuconego imienia ani rozbudowanych kwestii dialogowych. Jego tożsamość budowana jest poprzez elementy otoczenia i decyzje gracza.

---

## Technologie i narzędzia

| Technologia | Zastosowanie |
|---|---|
| Unreal Engine 5 | Główny silnik gry |
| Blender | Modelowanie i tworzenie zasobów 3D |
| Affinity Photo | Tworzenie i edycja zasobów graficznych |
| Visual Studio Code | Środowisko programistyczne |

**Platforma docelowa:** komputery osobiste z systemem Windows 10/11.

## Zakres projektu

Wersja konkursowa projektu zakłada realizację następujących elementów:

- Interwencje PSP, GOPR i TOPR.
- Kompletny budynek Zintegrowanego Centrum Ratowniczego.
- Interaktywne obiekty i eksploracja otoczenia.
- System rozwoju technologicznego.
- Podstawowe mechaniki ratownicze.
- Główna pętla rozgrywki.
- Podstawowa warstwa fabularna.
- Integracja wybranych technologii Motorola Solutions.

### Priorytety produkcyjne

Najważniejsze obszary rozwoju projektu:

1. System poruszania się i interakcji z otoczeniem.
2. System rozwoju technologicznego ZCR.
3. Mechaniki interwencji PSP, GOPR i TOPR.
4. Budynek ZCR wraz z odblokowywanymi obszarami.
5. Główna pętla fabularna.

Dodatkowe funkcjonalności, takie jak wybrane interakcje z obiektami oraz końcowa interwencja Firestorm, mają charakter opcjonalny.

---

## Zespół projektowy

Projekt jest rozwijany przez pięcioosobowy zespół GLORPO TEAM.

| Członek zespołu | Rola |
|---|---|
| Hubert Filas | Kierownik projektu / Główny programista |
| Adam Bartosz | Programista pomocniczy |
| Michał Goraj | Projektant narracji |
| Eryk Kaputa | Projektant graficzny |
| Adam Dzik | Projektant graficzny |

Ogólna koncepcja gry oraz rozgrywki została opracowana wspólnie przez wszystkich członków zespołu w ramach pierwszej fazy konkursu Motorola Solutions Science Cup.

---

## Dokumentacja

Podstawowym dokumentem projektowym jest **Game Design Document (GDD)**, zawierający szczegółowy opis założeń i struktury gry.

Dokumentacja obejmuje:
- Koncepcję gry i główne mechaniki.
- Systemy rozgrywki i progresji.
- Strukturę interwencji ratowniczych.
- Projekt świata i warstwę narracyjną.
- Interfejs użytkownika i sterowanie.
- Kierunek artystyczny i oprawę audiowizualną.
- Założenia techniczne.
- Zakres projektu i priorytety produkcyjne.

---

## Informacja o własności intelektualnej

Wszystkie znaki towarowe, nazwy handlowe, logotypy, produkty i technologie należące do Motorola Solutions oraz innych podmiotów trzecich pozostają własnością ich prawowitych właścicieli.

Ich wykorzystanie w projekcie ma charakter informacyjny i projektowy. Nie oznacza uzyskania licencji, przeniesienia praw własności intelektualnej ani oficjalnego powiązania projektu z wymienionymi podmiotami.

---

**GLORPO TEAM**

*Nie Każdy Wraca / Some Never Return*
