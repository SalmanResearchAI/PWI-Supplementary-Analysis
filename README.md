# 📘 Online Annex: Supplementary Analysis for "Introducing a Physiological Wellness Index (PWI)"

This repository hosts the **Online Annex** for the conference paper titled  
**"Introducing a Physiological Wellness Index (PWI) for Health and Well-Being"**.  

It contains supplementary figures, extended observations, and data analysis supporting the paper’s findings. These materials were moved from the main manuscript due to space limitations and are provided here to enhance transparency and reproducibility.

---

## 📑 Contents of This Repository

### 1. 📄 Online Annex (Word Document)

The annex includes:
- Extended analysis of IoMT data (EDA, PRV, RR)
- Section 5: *Analysis of IoMT Data* (shifted from the main article)
- Figure interpretations from March 01 to March 08
- Physiological state transitions (rest, active, distressed)
- Real-world use-case interpretation using PWI scoring

---

### 2. 📊 Supplementary Visualizations

Each observation day includes **two sets of figures**:
- **Interpolated Data** – smoothed curves for trend analysis
- **Raw Data** – original signals for validation and artifact detection

Each figure shows synchronized trends for:
- **Electrodermal Activity (EDA)** – Emotional arousal/stress
- **Pulse Rate Variability (PRV)** – Autonomic nervous system response
- **Respiratory Rate (RR)** – Breathing dynamics

| File Name                | Description                                               |
|--------------------------|-----------------------------------------------------------|
| `march01_interpolated.png` | March 1: High stress event with EDA peak and PRV drop    |
| `march01_raw.png`          | Raw signal confirms early morning sympathetic activation |
| `march02_interpolated.png` | March 2: Multiple minor stress events with trend shifts  |
| `march02_raw.png`          | Raw EDA dips aligned with RR changes                     |
| `march03_interpolated.png` | March 3: Calm day with stable PRV and RR                 |
| `march03_raw.png`          | Raw data shows minimal fluctuations                      |
| `march05_interpolated.png` | March 5: Prolonged stress (night episode)                |
| `march05_raw.png`          | PRV consistently low; RR elevated                        |
| `march08_interpolated.png` | March 8: Episodic stress events across the day           |
| `march08_raw.png`          | Raw signal with movement-related dropouts                |

---

## 📘 Section 5 – IoMT Analysis

> Section 5 of the paper, which includes a detailed discussion of the physiological observations and PWI score interpretations, has been relocated to the [Online Annex](./Annex/PWI_Online_Annex_Final.docx). It includes:

- Detailed daily breakdowns (March 1, 2, 3, 5, 8)
- Correlation between EDA, PRV, RR during stress
- Use-case illustration of PWI detecting distressed states
- PWI score mapping with real-time physiological data

---

## 🔍 Extended Observations (Optional)

> Further in-depth notes for March 02, 05, and 08 are embedded in the annex file. You may also view raw analysis notes in [`extended_observations.md`](./extended_observations.md) *(if included in repo)*.

---

## 📢 Citation and Usage

If you use or refer to the materials here, please cite the paper:

E. Evangelista, A. Nazir, R. Sharma, S. Bukhari (2025). "Introducing a Physiological Wellness Index (PWI) for Health and Well-Being".
IADIS International Conference on e-Health, 2025.


---

