# ✈️ Flight Delay Analysis – Verspätungen & Annullierungen bei Airlines (2009-2023)

Dieses Projekt untersucht die **Verspätungen und Annullierungen von Flügen** im Zeitraum **2009-2023**.  
Der Fokus liegt auf **Zusammenhängen zwischen Abflugverspätung, Ankunftsverspätung und Flugdauer**.

---

## 🚀 Ziel des Projekts
- **Welche Airlines sind am häufigsten verspätet?** (Optional für Erweiterung)
- **Wie hängen Abflugverspätung und Ankunftsverspätung zusammen?**
- **Beeinflusst die Flugdauer die Verspätung?**

---

## 📂 Projektstruktur
- `data/` – Rohdaten (Flugverspätungen 2009-2023)
- `notebooks/` – Explorative Datenanalyse (`flight_delay_analysis.ipynb`)
- `visuals/` – Diagramme & Plots
- `scripts/` – Python-Skripte

---

## 📊 Ergebnisse

### 🔸 Korrelationen (Heatmap)
- **Abflugverspätung ↔️ Ankunftsverspätung: 0.96** → **Sehr starker Zusammenhang**  
  ➡️ **"Einmal verspätet → bleibt verspätet."**
- **Flugdauer ↔️ Verspätung: Kein Zusammenhang (0.03 - 0.05)**  
  ➡️ **"Länge des Flugs hat keinen Einfluss auf die Verspätung."**

📊 **Visualisierung:**  
![Heatmap Korrelationen](visuals/korrelationen_heatmap.png)

---

### 🔸 Scatterplot – Abflugverspätung vs. Ankunftsverspätung
- **Klarer linearer Zusammenhang** → **Je später der Abflug, desto später die Ankunft.**

📊 **Visualisierung:**  
![Scatterplot Abflug/Ankunft](visuals/scatter_abflug_ankunft.png)

---

### 🔸 Scatterplot – Flugdauer vs. Ankunftsverspätung
- **Keine klare Struktur** → **Flugdauer spielt kaum eine Rolle für Verspätungen.**

📊 **Visualisierung:**  
![Scatterplot Flugdauer/Verspätung](visuals/scatter_flugdauer_ankunft.png)

