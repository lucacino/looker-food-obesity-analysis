# Looker Studio — Food Consumption & Global Obesity

> Studio sulla correlazione tra consumi alimentari (animali vs vegetali) e tassi di obesità in 170+ paesi, con dashboard interattiva su Looker Studio.

**IT** | Progetto di Data Visualization realizzato nell'ambito del Master in Data Science, Analytics e AI @ Start2Impact University.

---

## Obiettivo / Objective

**IT:** Analizzare la distribuzione globale dei consumi alimentari e verificare se esiste una correlazione con i tassi di obesità nazionali. L'analisi include distribuzione geografica, ranking per paese e case study specifici, consegnata tramite dashboard interattiva Looker Studio.

**EN:** Explore whether global dietary patterns (animal vs plant-based products, sugar, alcohol) correlate with national obesity rates. The analysis covers geographic distribution, country rankings, and targeted case studies, delivered via an interactive Looker Studio dashboard.

---

## Dataset

Source: dati pubblici su consumi alimentari per paese e tassi di obesità (WHO / FAO)

Variabili principali:
- `Derivati Animali` — quota percentuale di prodotti animali nella dieta
- `Derivati Vegetali` — quota percentuale di prodotti vegetali nella dieta
- `Zucchero e Dolci`, `Alcol` — variabili aggravanti
- `Obesità` — percentuale di popolazione obesa per paese

Scope: 170+ paesi

---

## Struttura dell'Analisi / Analysis Structure

### 1. Distribuzione Geografica dei Consumi
Mappe di calore che mostrano la distribuzione mondiale del consumo di derivati animali e vegetali, evidenziando cluster regionali influenzati da economia e tradizioni culturali.

### 2. I Due Estremi della Dieta Mondiale

Top 10 — Derivati Animali:
| Paese | Valore |
|---|---|
| Finlandia | 0.26 |
| Mongolia | 0.24 |
| Paesi Bassi | 0.24 |

Top 10 — Derivati Vegetali:
| Paese | Valore |
|---|---|
| Niger | 0.39 |
| Corea del Nord | 0.38 |
| Afghanistan | 0.37 |

### 3. La Mappa dell'Obesità nel Mondo
Kiribati, Giordania e Libano tra i tassi più elevati. Corea del Nord, Ciad e Nepal tra i più bassi.

### 4. Case Study — Il Modello della Corea del Nord
La Corea del Nord si posiziona al 2° posto mondiale per consumo di derivati vegetali (0.38) e all'estremo basso per tasso di obesità — confermando la correlazione analizzata.

### 5. Grafico Combinato — Dieta + Obesità per Paese
Visualizzazione sovrapposta di derivati animali, vegetali, zuccheri, alcol e obesità: emerge che l'obesità è amplificata dal consumo combinato di zuccheri e alcol nei paesi occidentali, indipendentemente dal solo consumo di carne.

---

## Risultati e Conclusioni / Key Results

- **Correlazione Vegetali-Salute:** i paesi con il più alto consumo di derivati vegetali mostrano i tassi di obesità più bassi
- **Impatto dei Derivati Animali:** Finlandia e Paesi Bassi hanno tassi di obesità significativamente più alti rispetto ai paesi a dieta prevalentemente vegetale
- **Fattori Aggravanti:** zuccheri e alcol amplificano l'obesità nei paesi occidentali
- **Sintesi:** la distribuzione alimentare è un indicatore predittivo affidabile dello stato di salute di una nazione

---

## Dashboard Looker Studio

🔗 **[Visualizza la Dashboard]([INSERISCI_LINK](https://datastudio.google.com/u/0/reporting/5e5fd869-bc1f-4070-aeb1-3dfe2543e2ea/page/bi2nF))**

La dashboard include:
- Mappe di calore geografiche (consumo animale / vegetale)
- Ranking Top 10 per categoria
- Grafico popolazione obesa per paese
- Grafico combinato: dieta + obesità per paese

---

## Tech Stack

- Tool: Google Looker Studio
- Connessione dati: Google Sheets / CSV import
- Tipo di chart: Mappe, Bar chart, Line chart, Stacked bar

---

## Struttura del Repository

```
looker-food-obesity-analysis/
├── README.md
└── presentation/
    └── Progetto_Looker_Studio_di_Luca_Cino.pdf
```

---

## Autore / Author

**Luca Cino** — [LinkedIn](https://www.linkedin.com/in/lucacino) | [GitHub](https://github.com/lucacino)

Master Professionale in Data Science, Analytics e AI @ Start2Impact University
