# Power BI Dashboard: Supply Chain & Order Analysis

Ein datengetriebenes Projekt zur Analyse von Lieferperformance, Produkten, Regionen und Logistik basierend auf einem realistischen Supply-Chain-Datensatz.

---

## Projektübersicht

Dieses Power BI Dashboard analysiert einen realistischen Supply-Chain-Datensatz und bietet strategische Einblicke für datenbasierte Entscheidungen im Bereich Operations, Logistik und Customer Intelligence.

### Business-Ziele:

- Identifikation ineffizienter Versandarten und Regionen
- Analyse von Wachstums- und Gewinnmustern
- Performance-Tracking von Produktkategorien
- Verständnis für die Auswirkungen von Rabatten und Margen

---

## Dashboardstruktur

Das Projekt umfasst **5 interaktive Seiten**, die jeweils unterschiedliche Geschäftsperspektiven beleuchten:

---

### Lieferketten- und Auftragsübersicht  
> *Operative KPI-Übersicht und Entwicklung auf Makroebene*

Diese Seite zeigt zentrale Leistungskennzahlen wie Bestellvolumen, Lieferzeiten, Verspätungsquote und Gewinnentwicklung im Zeitverlauf.  
Mit Hilfe interaktiver Filter (Land, Versandart, Produktkategorie, Monat) lassen sich verschiedene Dimensionen explorieren.

**Kennzahlen-Highlights:**

- Gesamtanzahl der Bestellungen: **65 752**
- Ø Lieferzeit (tatsächlich): **3,50 Tage**
- Ø Lieferzeit (geplant): **2,93 Tage**
- Anteil verspäteter Lieferungen: **54,8 %**
- Monatlicher Höchstwert: **2 124 Bestellungen (Dez 2017)**

 ![](Page%201.png)

---

### Periodenanalyse: Vor und nach September 2017  
> *Strategische Vergleichsanalyse mit Fokus auf Rabattpolitik und Gewinn*

Diese Seite analysiert zwei Zeiträume — **vor** und **nach** dem Wendepunkt im September 2017, als das Bestellvolumen deutlich anstieg.

**Wesentliche Kennzahlenvergleiche:**

| Zeitraum             | Bestellungen | Gesamtgewinn (€) | Ø Rabatt (€) | Ø Bestellwert (€) |
|----------------------|--------------|------------------|--------------|-------------------|
| Bis August 2017      | 55 626       | € 3 563 523       | € 20,13      | € 178,37          |
| Ab September 2017    | 10 126       | € 403 380         | € 27,13      | € 240,60          |

**Interpretation:**  
Trotz höherem durchschnittlichen Bestellwert stürzte der Gesamtgewinn um **89 %** ab. Der Grund liegt u. a. in aggressiveren Rabatten und einem veränderten Produktmix. 

![](Page%202.png)

---

### Produktanalyse  
> *Identifikation margenträchtiger Kategorien und Top-Produkte*

Diese Seite fokussiert sich auf die Umsatz- und Gewinnleistung einzelner Produktkategorien und -namen.

**Top-Performing Kategorien:**

| Kategorie           | Umsatz (€)     | Gewinn (€)     |
|---------------------|----------------|----------------|
| Fishing             | 6,23 Mio       | € 756 221       |
| Cleats              | 3,98 Mio       | € 494 637       |
| Camping & Hiking    | 3,70 Mio       | € 427 456       |
| Cardio Equipment    | 3,32 Mio       | € 383 011       |

Die Top-Kategorien stammen überwiegend aus dem Outdoor- und Sportbereich.  
Gleichzeitig zeigen einige Produktgruppen mit hohem Volumen eine unterdurchschnittliche Gewinnspanne — Potenzial für Optimierung im Sortimentsmanagement.

![](Page%203.png)

---

### Regionale Analyse  
> *Geografische Unterschiede in Lieferleistung & Gewinn*

- Regionale Verspätungsquoten > **40 %**
- Analyse von Bestellvolumen, Ø Lieferzeit und Gewinn nach Region & Versandart

![](Page%204.png)

---

### Logistikanalyse  
> *Geografische Auswertung von Performance und Effizienz*

Hier werden Unterschiede in der Lieferperformance je nach Land und Region untersucht.

**Analysedimensionen:**

- Ø Lieferzeit pro Region
- Verspätungsquote nach Land und Region
- Gewinnverteilung nach Region
- Matrix Region × Versandart

**Erkenntnisse:**  
In bestimmten Regionen treten überdurchschnittlich viele Lieferverzögerungen auf (teilweise > 40 %). Besonders Regionen mit hohem Bestellvolumen bieten Potenzial für gezielte logistische Optimierung.

 ![](Page%205.png)

---

## Datenquelle

- **DataCo Supply Chain Dataset**  
- Ursprünglich von [Kaggle](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)

---

## Verwendete Technologien

- Power BI Desktop
- Power Query (ETL)
- DAX (KPI-Berechnung)

---

## Key Insights (Executive Summary)

- **Gewinn ist nicht gleich Volumen:** Trotz Wachstum ging der Gesamtgewinn zurück — Rabatte & Sortimentsmischung sind entscheidend.
- **Produktdivergenzen:** Outdoor-Artikel haben starke Performance; andere Produkte binden Umsatz ohne entsprechende Marge.
- **Regionale Unterschiede:** Verspätungen sind geografisch konzentriert; Logistik kann gezielt optimiert werden.
- **Versandstrategie beeinflusst Pünktlichkeit & Gewinn:** „First Class“ liefert Profit, aber wenig Pünktlichkeit – hier sind Trade-offs zu managen.

---

## Autorin

Erstellt von **Ekaterina Podolskaya**  
Zielrolle: **Data Analyst / Business Intelligence Analyst / Data Scientist**  
Kontakt: https://www.linkedin.com/in/ekaterina-podolskaya

---
