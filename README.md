# QSAR – predykcja aktywności biologicznej ligandów receptora serotoniny 5-HT2A

Projekt skupiony na budowie modeli predykcyjnych określających aktywność biologiczną cząsteczek względem receptora serotoniny 5-HT2A na podstawie wektora cech numerycznych (deskryptorów molekularnych).

Projekt został zrealizowany w języku Python z wykorzystaniem narzędzi analizy danych i uczenia maszynowego.

Repozytorium zawiera praktyczną część projektu zrealizowanego w ramach pracy inżynierskiej, obejmującą pełny workflow analizy danych i modelowania predykcyjnego.

---

## Cel projektu

Celem było zbadanie zależności struktura–aktywność (QSAR) oraz budowa modeli klasyfikacyjnych przewidujących aktywność biologiczną związków chemicznych na podstawie deskryptorów molekularnych zapisanych jako cechy numeryczne.

---

## Workflow

Projekt obejmował następujące etapy:

1. Eksploracyjna analiza danych (EDA) na pełnym zbiorze.
2. Wstępne filtrowanie cech oraz redukcja korelacji.
3. Wykrywanie obserwacji odstających z użyciem Isolation Forest.
4. Redukcja wymiarowości (PCA) oraz analiza skupień.
5. Selekcja cech (mutual information, testy statystyczne).
6. Podział danych na zbiory treningowe i testowe.
7. Budowa i porównanie modeli klasyfikacyjnych.
8. Ewaluacja modeli z użyciem metryk precision–recall.

---

## Zawartość repozytorium

- `exploration.ipynb` – eksploracyjna analiza danych i przygotowanie cech
- `classification.ipynb` – pipeline modelowania i ewaluacji modeli
- `RDKit_2D_dataset.csv` – zbiór danych wykorzystany w analizie
