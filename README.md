# 📘 Analiza szeregów czasowych – bezrobocie i turystyka w Polsce (2011–2025)

## 📄 Opis projektu  
Celem projektu jest przeprowadzenie kompleksowej analizy dwóch szeregów czasowych opisujących kluczowe aspekty życia społeczno-gospodarczego w Polsce w latach **2011–2025**.  
Analiza koncentruje się na:  
- identyfikacji struktury i komponentów badanych szeregów,  
- weryfikacji stacjonarności,  
- dopasowaniu optymalnych modeli prognostycznych,  
- interpretacji uzyskanych wyników w kontekście zjawisk ekonomicznych (np. wpływu pandemii COVID-19).  

---

## 📊 Analizowane szeregi czasowe  

### 1. Bezrobocie rejestrowane (niesezonowe)  
- **Zakres:** styczeń 2011 – kwiecień 2025  
- **Cel:** identyfikacja trendów i wpływu czynników gospodarczych na rynek pracy  
- **Zastosowany model:** ARIMA(2,1,4)  
- **Wynik:** model skutecznie odwzorowuje dynamikę bezrobocia i zapewnia wiarygodne prognozy  

### 2. Turystyka – baza noclegowa (sezonowy)  
- **Zakres:** 2011–2025  
- **Charakterystyka:** wyraźna sezonowość, trend wzrostowy, zaburzenie w okresie pandemii COVID-19  
- **Zastosowane metody:** metoda Holta-Wintersa oraz modele sezonowe ARIMA  
- **Wynik:** metoda Holta-Wintersa zapewniła najlepsze odwzorowanie dynamiki i prognoz sezonowych  

---

## 🧮 Zastosowane metody i techniki  

- Dekompozycja szeregów czasowych (trend, sezonowość, reszty)  
- Testy stacjonarności: **ADF** (Augmented Dickey–Fuller), **KPSS**  
- Analiza autokorelacji: **ACF** i **PACF**  
- Modelowanie: **ARIMA**, **SARIMA**, **Holt-Winters**  
- Ocena jakości modeli: **MSE**, **AIC**, **BIC**  

---

## 🎯 Cele projektu  

- Zbudowanie modeli umożliwiających **wiarygodne prognozowanie** przyszłych wartości szeregów  
- **Identyfikacja fundamentalnych właściwości** procesów gospodarczych  
- Dostarczenie wniosków wspierających **strategiczne decyzje** w zakresie polityki rynku pracy i turystyki  

---

## 🧠 Wnioski  

- Model **ARIMA(2,1,4)** najlepiej opisuje dynamikę bezrobocia w Polsce  
- W przypadku danych turystycznych kluczowe znaczenie ma **modelowanie sezonowości** – tu najlepiej sprawdziła się **metoda Holta-Wintersa**  
- Uzyskane wyniki umożliwiają **lepsze zrozumienie zjawisk makroekonomicznych** oraz wspierają **planowanie strategiczne** w badanych sektorach  

---

## 🛠️ Wykorzystane narzędzia  

- **Python** (pandas, statsmodels, matplotlib, numpy)  
- **Jupyter Notebook / Visual Studio Code**  
- **Dane źródłowe:** GUS – Bank Danych Lokalnych  
