## 📊 Supplementary Visualizations

The supplementary visualizations in this repository are divided into **two figure sets** per observation day:

- **Interpolated Data Figures**
- **Raw/Non-Interpolated Data Figures**

Each set includes three synchronized plots representing:
1. **Electrodermal Activity (EDA)** – Measures emotional arousal and sympathetic activation.
2. **Pulse Rate Variability (PRV)** – Reflects autonomic nervous system balance, aligned with HRV metrics.
3. **Respiratory Rate (RR)** – Indicates breathing rate in breaths per minute (brpm).

### 🔹 Interpolated Figures

Interpolated plots offer smooth, continuous curves using signal processing techniques applied to noisy or sparse wearable data. These figures help in visualizing trends and transitions across the day. They are particularly useful for identifying stress events, baseline periods, and recovery patterns.

### 🔸 Non-Interpolated (Raw) Figures

Raw signal plots retain original sampling patterns and gaps in the data, providing an unprocessed view of signal integrity and sensor behavior. These plots highlight areas with missing data, motion artifacts, or brief signal losses, which can affect interpretation or model reliability.

---

### 📁 Figures in This Repository

| File Name       | Description                                |
|-----------------|--------------------------------------------|
| `march01_interpolated.png` | High stress event (March 1) – smoothed curves for clear transition detection |
| `march01_raw.png`          | Same event – raw data shows signal sparsity during peak stress |
| `march02_interpolated.png` | Stress spike with delayed recovery – smooth visualization |
| `march02_raw.png`          | Raw version shows sampling gaps and subtle dips |
| `march03_interpolated.png` | Baseline restful day – steady signals across EDA, PRV, RR |
| `march03_raw.png`          | Confirms signal consistency and minimal noise |
| `march05_interpolated.png` | Prolonged late-evening stress detected via EDA and PRV |
| `march05_raw.png`          | Exposes fragmented data during stress episode |
| `march08_interpolated.png` | Multiple peaks – high EDA with disrupted PRV |
| `march08_raw.png`          | Signal dropouts aligned with movement or low contact |

> ⚠️ Note: Only selected representative figures (March 1 and 3) are included in the main paper. All other figures and extended observations are hosted here for reproducibility and transparency.

---

## 📄 Extended Observations

Detailed text summaries for March 2, 5, and 8 can be found in [`extended_observations.md`](./extended_observations.md), where insights into physiological patterns and stress transitions are provided.
