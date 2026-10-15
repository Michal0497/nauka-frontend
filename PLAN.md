# Plan nauki: frontend developer

## Cel i ścieżka

Cel: pierwsza praca w IT w 10–12 miesięcy jako **frontend developer z okiem do designu**, potem rozwój w full-stack i docelowo własni klienci lub firma.

- **Stos technologiczny:** HTML, CSS, JavaScript → TypeScript → React → Next.js, do tego Git, SQL i podstawy Figmy.
- **Dlaczego frontend:** lubię budowanie z klocków i widoczny efekt; React to dosłownie składanie aplikacji z komponentów.
- **Dlaczego full-stack na końcu:** sam zbuduję cały produkt dla klienta, co jest bazą pod freelance i własną firmę.
- **AI jako wyróżnik, nie fundament:** integracje z LLM-ami dobudowuję w etapie 4.
- **Priorytety:** jak najszybciej wejść do IT (także hybrydowo w Warszawie), potem awansować; docelowo praca zdalna.

Realia rynku: proste strony generuje dziś AI, więc szanse ma junior, który dowozi działające aplikacje z backendem, bazą i deployem, a nie sam HTML/CSS.

## Zasady nauki

Rytm: **2 godziny dziennie, 6 dni w tygodniu**, jeden dzień wolny lub na powtórkę. Dni po 3 godziny to bonus, który przyspiesza plan.

| Część sesji | Czas | Co robię |
| --- | --- | --- |
| Teoria | 20 min | Tylko to, czego wymaga bieżące zadanie |
| Kodowanie | 80 min | Piszę sam, bez gotowych rozwiązań |
| Review i commit | 20 min | Code review w Claude Code, poprawki, commit, jedna notatka z lekcją |

**Praca z Claude:**

- Projekt w Claude (aplikacja) służy do planowania, teorii, pytań rekrutacyjnych i mentoringu, także z telefonu.
- Claude Code służy do sesji kodowania w repozytorium. W każdym repo jest plik `CLAUDE.md` z trybem nauki: najpierw pytanie naprowadzające, potem podpowiedź, kod tylko na wyraźną prośbę.
- Zasada: nie commituję linijki, której nie umiem wytłumaczyć.

**Angielski (obecnie około B1, cel B2):** podcasty i kanały techniczne po angielsku w aucie, dokumentacja od pierwszego dnia bez tłumacza.

## Etapy planu

48 tygodni po 12 godzin (2 h × 6 dni), czyli około 11 miesięcy. Każdy etap kończy się projektem do portfolio, a od etapu 2 robię 2 zadania algorytmiczne tygodniowo (np. Codewars), bo o to pytają na rozmowach. CV wysyłam od tygodnia 36.

| Etap | Tygodnie | Temat | Projekt |
| --- | --- | --- | --- |
| 1 | 1–8 | HTML, CSS, Figma, podstawy JS | Projekt 1 |
| 2 | 9–17 | JavaScript, API, TypeScript | Projekt 2 |
| 3 | 18–30 | React, Next.js, Tailwind | Projekt 3 |
| 4 | 31–40 | Full-stack: SQL, logowanie, testy | Projekt 4 |
| 5 | 41–48 | Portfolio, CV, rekrutacje | Szlify projektów 1–4 |

### Etap 1: HTML, CSS, Figma, podstawy JS (tygodnie 1–8)

Na koniec etapu umiem zaprojektować i zakodować responsywną stronę oraz wrzucić ją do internetu.

| Tydzień | Temat | Rezultat |
| --- | --- | --- |
| 1 | Środowisko, terminal, Git, GitHub, podstawy HTML | Repo na GitHubie, strona „O mnie” (szczegóły w sekcji Tydzień 1) |
| 2 | HTML: semantyka, formularze, tabele, podstawy dostępności; CSS: selektory, box model, kolory, fonty | Ostylowana strona „O mnie” z formularzem kontaktowym |
| 3 | CSS: flexbox, jednostki (rem, %, vw), pozycjonowanie | 3 komponenty: nawigacja, karta, stopka |
| 4 | CSS: grid, responsywność, mobile-first, media queries | Landing page odtworzony z gotowego projektu (np. Frontend Mentor) |
| 5 | Figma i zasady designu: hierarchia, odstępy, kontrast, typografia | Projekt 1 zaprojektowany w Figmie: wersja mobilna i desktop |
| 6 | JavaScript: zmienne, typy, warunki, pętle, funkcje | 15 krótkich ćwiczeń, menu mobilne w JS |
| 7 | Projekt 1: kodowanie | Wszystkie podstrony zakodowane |
| 8 | Projekt 1: poprawki, deploy, Lighthouse, README | Projekt 1 online + **punkt kontrolny: design czy kod?** |

### Etap 2: JavaScript, API, TypeScript (tygodnie 9–17)

Na koniec etapu umiem zbudować interaktywną aplikację, która pobiera dane z API i obsługuje błędy.

| Tydzień | Temat | Rezultat |
| --- | --- | --- |
| 9 | Tablice i obiekty; metody map, filter, reduce, find | Ćwiczenia na danych z pliku JSON |
| 10 | DOM i zdarzenia: wybieranie elementów, tworzenie, obsługa kliknięć i formularzy | Lista zadań (dodawanie, usuwanie, filtrowanie) |
| 11 | Moduły ES, DevTools i debugowanie, localStorage | Lista zadań zapisuje dane po odświeżeniu |
| 12 | HTTP i JSON, Promise, async/await, fetch, obsługa błędów | Aplikacja pogodowa z obsługą błędów sieci |
| 13 | Praca z API: wyszukiwanie, paginacja, stany ładowania, pustego wyniku i błędu | Wyszukiwarka z paginacją na publicznym API |
| 14 | TypeScript: typy, interfejsy, unie, typowanie odpowiedzi z API | Aplikacja pogodowa przepisana na TypeScript |
| 15 | Projekt 2: plan, struktura plików, typy danych | Szkielet aplikacji, pierwszy widok |
| 16 | Projekt 2: główne funkcje | Wszystkie funkcje działają |
| 17 | Projekt 2: testy jednostkowe (Vitest), deploy, README | Projekt 2 online |

### Etap 3: React, Next.js, Tailwind (tygodnie 18–30)

Na koniec etapu umiem zbudować wielostronicową aplikację w React i Next.js, tak jak robi się to w firmach.

| Tydzień | Temat | Rezultat |
| --- | --- | --- |
| 18 | npm, Vite, React: JSX, komponenty, props | Lista zadań z etapu 2 przepisana na React |
| 19 | Stan (useState), zdarzenia, listy, renderowanie warunkowe | Quiz lub kalkulator w React |
| 20 | useEffect, pobieranie danych, własne hooki | Wyszukiwarka z etapu 2 w React |
| 21 | Formularze i walidacja (React Hook Form + Zod) | Formularz wieloetapowy z walidacją |
| 22 | Routing, Tailwind CSS | Mini-aplikacja z kilkoma podstronami |
| 23 | Context, architektura komponentów, struktura folderów | Refaktor mini-aplikacji |
| 24 | Next.js: App Router, layouty, komponenty serwerowe i klienckie | Pierwsza aplikacja w Next.js |
| 25 | Next.js: pobieranie danych, SEO i metadata, obrazy, deploy na Vercel | Aplikacja z tygodnia 24 online |
| 26 | Dostępność, wydajność (Lighthouse), testy komponentów (Testing Library) | Audyt i poprawki aplikacji z tygodnia 24 |
| 27 | Projekt 3: projekt w Figmie, architektura, typy | Makiety i szkielet aplikacji |
| 28 | Projekt 3: główne widoki | Główne widoki działają |
| 29 | Projekt 3: formularze, stany błędów, responsywność | Wszystkie funkcje działają |
| 30 | Projekt 3: testy, deploy, README | Projekt 3 online |

### Etap 4: full-stack (tygodnie 31–40)

Na koniec etapu umiem zbudować aplikację z bazą danych, kontami użytkowników i testami. Od tygodnia 36 wysyłam CV.

| Tydzień | Temat | Rezultat |
| --- | --- | --- |
| 31 | Backend w Next.js: REST, Route Handlers, Server Actions, walidacja danych na serwerze | API do listy zadań |
| 32 | SQL i PostgreSQL: SELECT, INSERT, UPDATE, JOIN, relacje | Schemat bazy dla Projektu 4 |
| 33 | ORM (Prisma lub Drizzle), migracje | Lista zadań zapisuje dane w bazie |
| 34 | Logowanie i sesje (np. Auth.js), podstawy bezpieczeństwa | Konta użytkowników w liście zadań |
| 35 | Testy E2E (Playwright), integracja z API LLM (opcjonalnie) | Testy przepływu logowania |
| 36 | Projekt 4: makiety, schemat bazy, architektura; **start wysyłania CV** | Plan i szkielet Projektu 4 |
| 37 | Projekt 4: baza, API, logowanie | Backend działa |
| 38 | Projekt 4: interfejs | Główne widoki działają |
| 39 | Projekt 4: obsługa błędów, testy, funkcja wyróżniająca (np. AI) | Wszystkie funkcje działają |
| 40 | Projekt 4: deploy, README z diagramem architektury | Projekt 4 online |

### Etap 5: rynek (tygodnie 41–48)

Na koniec etapu mam gotowe portfolio, regularnie aplikuję i ćwiczę rozmowy. Sesja dzieli się na 1 h nauki i 1 h szukania pracy.

| Tydzień | Temat | Rezultat |
| --- | --- | --- |
| 41 | Strona portfolio, README i nagrania demo projektów 1–4 | Portfolio online |
| 42 | CV, LinkedIn, profil GitHub | CV gotowe do wysyłki |
| 43 | Pytania z JavaScript i HTML/CSS, zadania algorytmiczne | Lista odpowiedzi w Playbooku |
| 44 | Pytania z React i Next.js, live coding | 3 próbne zadania na czas |
| 45 | Rozmowa behawioralna: moja historia zmiany zawodu, praca w zespole | Gotowa historia na 2 minuty |
| 46 | Poprawki projektów po feedbacku z rekrutacji | Lista i wdrożenie poprawek |
| 47–48 | Rekrutacje, meetupy w Warszawie, kontakty na LinkedIn | Minimum 10 aplikacji tygodniowo |

## Tydzień 1

Cel tygodnia: działające środowisko na Windowsie, pierwsze repo na GitHubie i pierwsza strona w HTML.

- [x] Dzień 1: instalacja Git for Windows, VS Code, Node.js LTS i Claude Code; konfiguracja `git config` (imię, e-mail, gałąź `main`)
- [x] Dzień 2: terminal (`pwd`, `ls`, `cd`, `mkdir`) i cykl Gita (`init`, `status`, `add`, `commit`, `log`); repo `nauka-frontend` z plikiem `CLAUDE.md`
- [x] Dzień 3: konto na GitHubie, podłączenie repo, `git push`, `README.md`
- [x dzień 4] Dni 4–6: podstawy HTML i semantyka; strona „O mnie”; pierwsze code review w Claude Code

Sprawdzian na koniec tygodnia:

- Czym różni się `git add` od `git commit`?
- Po co jest GitHub, skoro Git działa lokalnie?
- Dlaczego `<button>` jest lepszy niż `<div>` z obsługą kliknięcia?

## Projekty portfolio

Cztery projekty, każdy trudniejszy od poprzedniego; tematy ustalamy później. Najlepiej, żeby rozwiązywały realny problem biznesowy, a nie były kolejną aplikacją z tutoriala.

| Projekt | Kiedy | Technologie | Wymagania minimalne | Co pokazuje rekruterowi | Temat |
| --- | --- | --- | --- | --- | --- |
| Projekt 1 | Tygodnie 5–8 | HTML, CSS, trochę JS, Figma | Min. 3 podstrony, wersja mobilna i desktop, projekt w Figmie, Lighthouse powyżej 90, deploy | Design, porządny HTML/CSS, responsywność | Do ustalenia |
| Projekt 2 | Tygodnie 15–17 | JavaScript, TypeScript, publiczne API | Wyszukiwanie lub filtrowanie, stany ładowania i błędu, zapis w localStorage, testy jednostkowe | Logika, praca z API, obsługa błędów | Do ustalenia |
| Projekt 3 | Tygodnie 27–30 | React, Next.js, Tailwind | Kilka widoków, formularze z walidacją, routing, dostępność, testy komponentów | Nowoczesny frontend jak w firmie | Do ustalenia |
| Projekt 4 | Tygodnie 36–40 | Next.js, PostgreSQL, logowanie | Konta użytkowników, baza danych, operacje CRUD, testy E2E, diagram architektury, opcjonalnie AI | Pełny produkt od A do Z | Do ustalenia |

Każdy projekt ma README: problem, zrzuty ekranu, link do wersji online, technologie, decyzje techniczne i co bym poprawił. Projekt 1 lub 3 może być dla prawdziwego klienta, jeśli taki się pojawi.

## Postępy i decyzje

**Kamienie milowe:**

- [ ] Etap 1 ukończony: Projekt 1 online
- [ ] Punkt kontrolny: design czy kod (decyzja zapisana niżej)
- [ ] Etap 2 ukończony: Projekt 2 online
- [ ] Etap 3 ukończony: Projekt 3 online
- [ ] Etap 4 ukończony: Projekt 4 online
- [ ] Pierwsze CV wysłane
- [ ] Pierwsza oferta pracy lub pierwsze płatne zlecenie

**Dziennik decyzji** (najnowsze na górze):

| Data | Decyzja | Dlaczego |
| --- | --- | --- |
| 2026-10-13 | Ścieżka: frontend z okiem do designu, docelowo full-stack | Lubię widoczny efekt i budowanie z klocków; szybkie wejście + baza pod własnych klientów |
| 2026-10-13 | Rytm 2 h dziennie, 6 dni w tygodniu | Realne do utrzymania obok pracy przez 10–12 miesięcy |
| 2026-10-13 | JavaScript zamiast Pythona jako pierwszy język | Jeden język na froncie i backendzie, znam już podstawy JS |
