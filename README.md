# Projekt zaliczeniowy

W ramach zaliczenia przedmiotu jesteśmy zobowiązani grupowo wykonać wspólny projekt, którego celem jest zaprojektowanie urządzenia elektronicznego opartego o mikroprocesor z rodziny **STM32**, służącego do rejestracji temperatury.

## Specyfikacja

* wykonanie projektu polega na zaprojektowaniu urządrzenia
* każdy komponent logiczny urządzenia powinien zostać dokładnie udokumentowany
* urządzenie powinno składać się z rzeczywistych komponentów elektronicznych dostępnych na rynku.
* wszelkie użyte komponenty elektroniczne powinny wnosić szacowaną wartość do kosztorysu
* projekt powinien zawierać schemat elektryczny całego urządzenia
* projekt ma formę dokumentu `.pdf`

## Cykl życia projektu

1. Ustalenie funkcjonalności, które urządzenie będzie realizować, na przykład:

* > pomiar temperatury za pomocą urządzenia pomiarowego np. **termorezystora**
* > przechowywanie szeregu czasowego wartości temperatur w pamięci trwałej
* > zapewnienie interfejsu do komunikacji z innymi urządzeniami, np. **Ethernet**
* > monitoring wartości temperatury w czasie rzeczywistym przy pomocy wyświetlacza alfanumerycznego **LCD**
  
2. Ustalenie jakie komponenty będą realizować zaplanowane funkcjonalności

* Należy mieć na uwadze ograniczenia interfejsów **I/O** mikrokontrolerów z rodziny **STM32** pod względem ilościowym i jakościowym . Do przeglądu dostępnych mikroprocesorów zaleca się użycie oprogramowania z [SDK](https://www.st.com/en/development-tools/stm32-software-development-tools.html#products) firmy **ST** używanego w ramach przedmiotu **Mikroprocesory i Mikrokontrolery**.

3. Opracowanie każdej z funkcjonalości w kontekście użytego komponentu

* opis charakterystyki komponentu i jego zastosowania w urządzeniu
* określelnie uproszczonego schematu podłączenia komponentu z danym interfejsem mikroprocesora
* uwzględnienie użytych komponentów w kosztorysie

4. Opracowanie całościowego schematu elektrycznego urządzenia

5. Opracowanie dokumentu stanowiącego podstawę do eksportu do `.pdf` / eksport bezpośredni `.md` => `.pdf`

* zawiera krótki opis urządzenia na wstępie
* (opcjonalnie) zawiera schemat logiczny urządzenia
* zawiera schemat elektryczny urządzenia
* zawiera opis każdej z funkcjonalności urządzenia w kontekście użytego komponentu
* zawiera kosztorys urządzenia
* zawiera uczestników projektu

6. Eksport dokumentu do `.pdf` i prezentacja prowadzącemu przedmiot: <mateusz.michalek@pk.edu.pl>

## Realizacja projektu

* Zaleca się korzystanie z edytora: [VS Code](https://code.visualstudio.com/)

  * sugestia dotycząca zalecanego rozszerzenia zawierającego pomoc w pisaniu dokumentów `.markdown` powinna pojawić się automatycznie. W przeciwnym wypadku ID: `DavidAnson.vscode-markdownlint`

* Treść projektu znajduje się w pliku [main](./main.md). Pracując nad projektem należy umieszczać tam owoce swojej pracy korzystając z formatowania języka [markdown](https://www.markdownguide.org/basic-syntax/).

* Obrazy znajdują się w katalogu `./images/`. Dodawanie obrazu do dokumentu polega na umieszczeniu obrazu w katalogu, a następnie stworzeniu odwołania w dokumencie [main](./main.md), np. `(alternatywny_tekst_dla_obrazu)[./images/]`

* Każdą jednostkową część pracy [commitujemy](https://git-scm.com/docs/git-commit) w lokalnym repozytorium na swojej maszynie na branchu dedykowanym danemu **issue**.

* W celu uaktualnienia centralnego repozytroium, należy wypushować brancha do centralnego repozytorium i otworzyć [pull request](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/working-with-your-remote-repository-on-github-or-github-enterprise/creating-an-issue-or-pull-request) danego brancha z branchem **master**

* Za pomocą funkcjonalości serwisu **GitHub** - [Issues](https://github.com/features/issues):

  * przypisujemy dane zadanie do swojej osoby
  * tworzymy nowe zadania

## Status projektu

- [x] Inicjalizacja repozytorium
- [x] Stworzenie struktury projektu
- [x] Stworzenie zasad współtworzenia projektu
- [x] Dodanie wszystkich uczestników jako współtwórców repozytorium na **GitHub-ie**
- [x] **Issue**: Ustalenie funkcjonalności projektu
- [x] Utworzenie **issues** odpowiadających wszystkim funkcjonalnościom
- [x] Utworzenie **issues** odpowiadających pozostałym elementom realizacji projektu jak: **stworzenie schematu elektrycznego**
- [X] Realizacja rzeczonych issues
- [X] Uzupełnienie składu grupy
- [X] Publikacja projektu w formacie `.pdf`
- [ ] Dostarczenie projektu do prowadzącego laboratorium

## Schemat elektryczny

Na podstawie researchu przeprowadzonego w [Issue: #4](https://github.com/Tomasz-Zdeb/Embedded-Systems-Class-Project/issues/4) schemat elektryczny urządzenia będzie tworzony przy pomocy oprogramowania: [KiCad](https://www.kicad.org/).

Schemat elektyczny znajduje się w katalogu: `/schematics/`

## Zadania których nie udało się zrealizować

- opis menu wraz z obsługą przy pomocy przycisków
- graficzny projekt gotowego urządzenia wraz z obudową
- opis modułu rozszerzeń
- przygotwanie kilku wariantów wyposażenia (wraz z cennikiem)

## Materiały

<p align="center">

<img src="./images/tablica.jpg" alt="zdjecie tablicu z sugestiami prowadzącego" width="400"/>

</p>

## Opiekun repozytorium

### [Tomasz Zdeb](https://github.com/Tomasz-Zdeb)
