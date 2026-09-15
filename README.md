# Raport Analityczny: Determinanty Otyłości i Zdrowia Publicznego w USA (2011-2024)

🌍 **Wersja interaktywna:** [Zobacz wyrenderowany raport HTML]([https://mkaczkowski07.github.io/EDA_Health/](https://mkaczkowski07.github.io/EDA_Lifestyle_Obesity/EDA_RMD.html))

Kompleksowa Analiza Eksploracyjna (EDA) badająca powiązania między czynnikami społeczno-ekonomicznymi, nawykami behawioralnymi a wskaźnikami zdrowotnymi w Stanach Zjednoczonych. 

## Cel projektu
Celem analizy jest identyfikacja i ocena siły czynników wpływających na rosnący wskaźnik otyłości. Projekt weryfikuje hipotezy dotyczące wpływu:
* **Statusu materialnego i edukacji** na świadomość prozdrowotną i ryzyko otyłości.
* **Nawyków żywieniowych** (częstotliwość spożycia owoców i warzyw).
* **Aktywności fizycznej** (weryfikacja realizacji standardów WHO w ujęciu regionalnym).

## Źródło danych
* **Baza:** Behavioral Risk Factor Surveillance System (BRFSS)
* **Zakres czasowy:** 2011–2024
* **Poziom agregacji:** 50 stanów USA + Dystrykt Kolumbii (z uwzględnieniem makroregionów)

## Wykorzystane technologie
* **Język:** R
* **Przetwarzanie danych:** `tidyverse` (`dplyr`, `tidyr`, `stringr`)
* **Wizualizacja:** `ggplot2`
* **Analiza braków danych:** `mice`
* **Raportowanie:** `R Markdown` 

## Uruchomienie lokalne
Aby samodzielnie wygenerować raport na własnym środowisku:
1. Sklonuj repozytorium.
2. Otwórz projekt w RStudio używając pliku `EDA_1.Rproj`.
3. Otwórz główny skrypt `EDA_RMD.Rmd`.
4. Użyj opcji **Knit to HTML** (wymagane zainstalowane pakiety wymienione w nagłówku pliku).

## Wyniki (Output)
Efektem końcowym jest dynamiczny raport HTML (`EDA_RMD.html`), który obejmuje:
* Proces czyszczenia, standaryzacji i profilowania danych w R.
* Weryfikację hipotez z wykorzystaniem aparatu statystycznego (m.in. test Kruskala-Wallisa, korelacje Spearmana).
* Wnioski analityczne dotyczące determinantów otyłości, poparte wizualizacjami.
