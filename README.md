# 📊 Analýza mateřských škol v Brně

Tento projekt představuje interaktivní dashboard vytvořený v **Power BI**, který umožňuje analyzovat rozmístění mateřských škol v Brně, jejich spádové oblasti a porovnávat velikost spádových oblastí mezi jednotlivými městskými částmi.

---

## 🎯 Cíl projektu

Cílem projektu je vytvořit přehlednou a interaktivní vizualizaci, která umožní:

- porovnávat počet mateřských škol v jednotlivých městských částech,
- analyzovat velikost spádových oblastí jednotlivých mateřských škol,
- identifikovat školy s největší a nejmenší spádovou oblastí,
- zobrazit prostorové rozmístění spádových adres.

Velikost spádové oblasti je v této analýze vyjádřena **počtem spádových adres** přiřazených jednotlivým mateřským školám.

---

## 🗂️ Použitá data

Projekt využívá otevřená data města Brna dostupná na portálu:

https://data.brno.cz/

Použity byly zejména dva datové soubory:

- data o spádových adresách přiřazených k mateřským školám,
- seznam mateřských škol včetně jejich adres a geografické polohy.

Každý záznam představuje jednu adresu zařazenou do spádové oblasti konkrétní mateřské školy.

---

## 📈 Použité nástroje

- Power BI Desktop
- Microsoft Excel

---

## 📊 Obsah dashboardu

Dashboard obsahuje **tři interaktivní stránky**:

### 1. Přehled podle městských částí

- mapa mateřských škol ve vybrané městské části,
- počet mateřských škol ve vybrané městské části,
- seznam spádových oblastí,
- graf počtu mateřských škol,
- interaktivní filtrování podle městské části.

### 2. Analýza spádových oblastí

- kombinovaný graf počtu spádových adres a mateřských škol,
- mapa spádových adres,
- počet spádových adres na jednu mateřskou školu,
- počet mateřských škol ve vybrané spádové oblasti,
- interaktivní filtrování podle městské části a spádové oblasti.

### 3. Přehled vytíženosti mateřských škol

- TOP 5 mateřských škol s největší spádovou oblastí,
- TOP 5 mateřských škol s nejmenší spádovou oblastí,
- souhrnné informace o vybrané městské části,
- identifikace škol s největší a nejmenší spádovou oblastí.

---

## 🔍 Hlavní zjištění

- velikost spádových oblastí se mezi mateřskými školami výrazně liší,
- i v rámci jedné městské části existují značné rozdíly ve velikosti spádových oblastí,
- některé mateřské školy obsluhují výrazně rozsáhlejší území než jiné,
- dashboard umožňuje interaktivně porovnávat jednotlivé městské části i konkrétní spádové oblasti.

---

## ⚠️ Omezení

Velikost spádové oblasti je v projektu vyjádřena **počtem spádových adres**. Tento ukazatel nepředstavuje skutečný počet dětí ani skutečnou obsazenost mateřských škol. Jedna adresa může zahrnovat více domácností (např. bytové domy) nebo naopak žádné děti předškolního věku.

Některé záznamy ve zdrojových datech obsahovaly prázdná pole s adresami. Tyto hodnoty nebyly v rámci projektu doplňovány ani upravovány a odpovídají původním otevřeným datům města Brna.

Projekt pracuje s aktuálně dostupnými otevřenými daty města Brna a výsledky odpovídají jejich rozsahu a kvalitě.

---
