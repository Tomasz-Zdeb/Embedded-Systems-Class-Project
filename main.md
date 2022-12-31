# Systemy Wbudowane - Projekt Grupy Laboratoryjnej 04

Realizacja projektu polega na zaprojektowaniu urządzenia embedded (systemu wbudowanego) do pomiaru temperatury. Projekt urządzenia w teorii mógłby stanowić podstawę do konstrukcji fizycznego prototypu urządzenia. Zakres projektu obejmuje dobór komponentów, mając na uwadzę:

- kompatybilność
- cenę
- rozmiary
- dostępność
- przystępność komponentu (tj. dostępność dokumentacji i schematów pozwalających na integrację komponentu)

W projekcie przedstawiono także schemat elektryczny potencjalnego urządzenia obrazujący połączenia komponentów przy zastosowaniu odpowiednich interfejsów. 

## Skład grupy

- Imię Nazwisko (ta sekcja zostanie uzupełniona przed wysyłką projektu aby nie przechowywać danych uczestników w publicznym repozytorium)

## Specyfikacja urządzenia

Projektowane urządzenie stanowi kompaktowe i przystępne cenowo rozwiązanie do monitorowania temperatory przy pomocy termopary, z odczytem w czasie rzeczywistym lokalnie i zdalnie oraz zapisem na zewnętrznym nośniku.

## Funkcjonalności

- Pomiar temperatury (przy pomocy termopary)
- Wyświetlanie warotści temperatury na alfanumerycznym wyświetlaczu **LCD** w czasie rzeczywistym
- Zapis pomiarów na karcie **micro SD**
- Możliwość odczytu aktualnej wartości i wartości zapisanych przez łączność **Bluetooth**
- Ustawienie alarmu, tj. wartości temperatury której przekroczenie (poniżej lub powyżej - w zależności od wybranego trybu) powoduje emisje sygnału dźwiękowego oraz powiadomienia w przypadku łączności **Bluetooth**

### Pomiar temperatury

[Issue 11](https://github.com/Tomasz-Zdeb/Embedded-Systems-Class-Project/issues/11)

### Monitoring pomiaru w czasie rzeczywistym na alfanumerycznym ekranie LCD

[Issue 15](https://github.com/Tomasz-Zdeb/Embedded-Systems-Class-Project/issues/15)

### Zapisywanie szeregu czasowego pomiarów na karcie Micro SD

[Issue 21](https://github.com/Tomasz-Zdeb/Embedded-Systems-Class-Project/issues/21)

### Komunikacja przy pomocy interfejsu bluetooth - odczyt danych w czasie rzeczywistym i zapisanych na karcie

[Issue 26](https://github.com/Tomasz-Zdeb/Embedded-Systems-Class-Project/issues/26)

### Emisja sygnałów dźwiękowych po przekroczeniu zadanej wartości progowej temperatury

[Issue 27](https://github.com/Tomasz-Zdeb/Embedded-Systems-Class-Project/issues/27)

## Potencjalna konfiguracja

Stworzyć Issue dotyczące uzupełnienia tego pliku danymi z [Issue 28](https://github.com/Tomasz-Zdeb/Embedded-Systems-Class-Project/issues/28)

## Schemat elektryczny

## Kosztorys

Ceny jednostkowe komponentów:
-moduł Bluetooth: 27,80 zł
-mikroprocesor: 39,20 zł
-buzzer: 5,90 zł
-tact Switch (niebieski): 3,40 zł
-tact Switch (czerwony): 3,40 zł
-tact Switch (czarny): 2,90 zł
-gniazdo karty pamięci SD z wyrzutnikiem: 2,60 zł
-karta pamieci: 293,70 zł
-wyświetlacz LCD + konwerter: 24,70 zł
-termopara typu K: 21,47 zł
-chip do interpretowania napięć: 49,98 zł
-obudowa: 10 zł
Razem: 485,05 zł

Potencjalna cena rynkowa urządzenia: 679,07 zł - przyjąłem 140% ceny komponentów aby pokryć koszty produkcji izapewnić marżę dla wytwórcy