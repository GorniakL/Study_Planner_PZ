# Wymagania

Wymagania (Requirements) określają, co system powinien robić oraz jakie właściwości i ograniczenia powinien spełniać.

## Oznaczenia

- **FR** (Functional Requirement) — wymaganie funkcjonalne, określające, co system powinien robić.

- **NFR** (Non-Functional Requirement) — wymaganie niefunkcjonalne, określające, jakie właściwości lub ograniczenia powinien spełniać system.

Każde wymaganie posiada unikalny identyfikator, np. `FR-01` lub `NFR-01`.

## Wymagania funkcjonalne

| ID | Wymaganie |
|---|---|
| FR-01 | System umożliwia studentowi utworzenie talii fiszek. |
| FR-02 | System umożliwia studentowi dodanie do talii fiszki składającej się z pytania i odpowiedzi. |
| FR-03 | System umożliwia studentowi edycję i usunięcie talii oraz fiszek. |
| FR-04 | System umożliwia studentowi rozpoczęcie sesji nauki z wybranej talii. |
| FR-05 | Podczas sesji nauki system wyświetla pytanie fiszki i umożliwia studentowi odkrycie odpowiedzi. |
| FR-06 | System umożliwia studentowi ocenę swojej odpowiedzi jako „Źle”, „Trudno” lub „Łatwo”. |
| FR-07 | System wyznacza termin powtórki fiszki na podstawie oceny odpowiedzi. |
| FR-08 | System umożliwia studentowi podanie okresu nauki oraz dziennego limitu fiszek. |
| FR-09 | System tworzy plan nauki dla wybranej talii, uwzględniając okres nauki, dzienny limit fiszek oraz zaplanowane powtórki. |
| FR-10 | System wyświetla studentowi fiszki zaplanowane do nauki i powtórzenia w danym dniu. |
| FR-11 | System wskazuje studentowi zaległe powtórki. |
| FR-12 | System informuje studenta, gdy nie można rozplanować wszystkich fiszek w wybranym okresie nauki przy podanym dziennym limicie. |
| FR-13 | System prezentuje studentowi liczbę opanowanych fiszek, liczbę zaległych powtórek oraz skuteczność odpowiedzi. |
| FR-14 | System prezentuje studentowi wykres postępów w czasie. |

## Wymagania niefunkcjonalne

| ID | Wymaganie |
|---|---|
| NFR-01 | Aplikacja jest dostępna i poprawnie wyświetla się w przeglądarce internetowej. |
| NFR-02 | System zapisuje ocenę odpowiedzi i wyświetla kolejną fiszkę w czasie nieprzekraczającym 2 sekund dla 90% powtórek. |
| NFR-03 | System zachowuje talie, fiszki i historię ocen studenta po zamknięciu aplikacji i ponownym jej uruchomieniu. |
| NFR-04 | System wymaga potwierdzenia przed trwałym usunięciem talii wraz z jej fiszkami. |

## Pytania otwarte

- Co oznacza, że fiszka jest opanowana?
- W jaki sposób system powinien wyznaczać termin kolejnej powtórki dla ocen „Źle”, „Trudno” i „Łatwo”?
- Czy dzienny limit fiszek obejmuje zarówno nowe fiszki, jak i powtórki?
- Czy plan nauki obejmuje jedną talię, czy kilka talii jednocześnie?
- Co powinien zrobić system, jeżeli liczba zaległych powtórek przekroczy dzienny limit fiszek?
- Co powinien zrobić system, jeśli student nie zrealizuje zaplanowanej sesji nauki?
- Czy student może zmienić okres nauki lub dzienny limit fiszek po utworzeniu planu?
- Jak dokładnie system powinien obliczać skuteczność odpowiedzi i postęp nauki?
- Czy student musi mieć konto, aby korzystać z aplikacji, i czy jego dane mają być dostępne na więcej niż jednym urządzeniu?
