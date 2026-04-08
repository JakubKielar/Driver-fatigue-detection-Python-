# Driver-fatigue-detection-Python-

[cite_start]Projekt inżynierski zrealizowany na kierunku Automatyka i Robotyka (specjalność: Technologie Informacyjne) na Wydziale Automatyki, Elektroniki i Informatyki Politechniki Śląskiej[cite: 1, 6].

## Opis projektu
[cite_start]Głównym założeniem pracy było zaprojektowanie oraz wdrożenie aplikacji umożliwiającej detekcję zmęczenia kierowcy w czasie rzeczywistym[cite: 13]. [cite_start]System opiera się na bezinwazyjnej analizie obrazu wideo, integrując moduły detekcji twarzy i rozpoznawania emocji w jeden spójny system decyzyjny[cite: 14].

### Kluczowe funkcjonalności:
* [cite_start]**Analiza czasowa**: Algorytmy opracowane do analizy danych w dziedzinie czasu pozwalają szacować ryzyko zaśnięcia na podstawie sekwencji zdarzeń[cite: 15, 16].
* [cite_start]**Head Pose Estimation**: Moduł estymacji pozycji głowy bazujący na geometrii 2D, wykrywający opadanie głowy przy niskiej złożoności obliczeniowej[cite: 17, 18].
* [cite_start]**Weryfikacja ziewania**: Mechanizm wspierany analizą emocji, który odróżnia ziewanie od śmiechu czy rozmowy poprzez detekcję mikroekspresji negatywnych[cite: 19, 20].
* [cite_start]**Fatigue Index**: Końcowa ocena stanu kierowcy bazująca na fuzji danych, uwzględniająca m.in. metrykę PERCLOS[cite: 21, 34].

## Technologie i narzędzia
* [cite_start]**Język**: Python 3.10[cite: 214].
* [cite_start]**Przetwarzanie obrazu**: OpenCV 4.9.0 oraz Dlib 19.24.4 (model 68 punktów charakterystycznych)[cite: 221, 227, 228].
* [cite_start]**Uczenie maszynowe**: TensorFlow i Keras (architektura EfficientNetB0 do klasyfikacji emocji)[cite: 233, 234].
* [cite_start]**Zbiór danych**: Baza wideo YawDD[cite: 241].

## Wyniki
[cite_start]Poprawność działania algorytmów została zweryfikowana na zbiorze YawDD, ze szczególnym uwzględnieniem przypadków trudnych, takich jak obecność okularów korekcyjnych u kierowcy[cite: 22, 35].

---
[cite_start]**Autor**: Jakub Kielar [cite: 4]  
**Prowadzący**: dr hab. inż. Sebastian Budzan, prof. Pol. [cite_start]Śl. [cite: 8]  
[cite_start]**Uczelnia**: Politechnika Śląska, Gliwice 2026 [cite: 1, 9]
