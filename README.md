# Driver-fatigue-detection-Python-

Projekt inżynierski zrealizowany na kierunku Automatyka i Robotyka (specjalność: Technologie Informacyjne) na Wydziale Automatyki, Elektroniki i Informatyki Politechniki Śląskiej.

## Opis projektu
Głównym założeniem pracy było zaprojektowanie oraz wdrożenie aplikacji umożliwiającej detekcję zmęczenia kierowcy w czasie rzeczywistym. System opiera się na bezinwazyjnej analizie obrazu wideo, integrując moduły detekcji twarzy i rozpoznawania emocji w jeden spójny system decyzyjny.

### Kluczowe funkcjonalności
* **Analiza czasowa**: algorytmy opracowane do analizy danych w dziedzinie czasu pozwalają szacować ryzyko zaśnięcia na podstawie sekwencji zdarzeń, a nie tylko pojedynczych klatek.
* **Head Pose Estimation**: moduł estymacji pozycji głowy bazujący na geometrii 2D, pozwalający na skuteczne wykrywanie opadania głowy (mikrosnu) przy zachowaniu niskiej złożoności obliczeniowej.
* **Weryfikacja ziewania**: innowacyjny mechanizm wspierany analizą emocji, który odróżnia ziewanie od śmiechu czy rozmowy poprzez weryfikację, czy otwarciu ust towarzyszą mikroekspresje negatywne.
* **Fatigue Index**: końcowa ocena stanu kierowcy bazująca na fuzji zebranych danych oraz wyliczonym wskaźniku, który uwzględnia m.in. metrykę PERCLOS.

## Technologie i narzędzia
* **Język**: Python 3.10.
* **Przetwarzanie obrazu**: OpenCV 4.9.0 oraz Dlib 19.24.4 (model 68 punktów charakterystycznych).
* **Uczenie maszynowe**: TensorFlow i Keras (architektura EfficientNetB0 do klasyfikacji emocji).
* **Zbiór danych**: Baza wideo YawDD.

## Wyniki badań
Poprawność działania algorytmów została zweryfikowana na zbiorze danych YawDD. System wykazał wysoką skuteczność w identyfikacji stanów zagrożenia, zachowując odporność na czynniki zakłócające, takie jak obecność okularów korekcyjnych u kierowcy.

---
**Autor**: Jakub Kielar  
**Prowadzący**: dr hab. inż. Sebastian Budzan, prof. Pol. Śl.  
**Uczelnia**: Politechnika Śląska, Gliwice 2026
