# Experiment 06 — Measurement of Mechanical Properties

### ME5381 — Basic Manufacturing Lab
### Department of Mechanical Engineering, IIT Madras

---

## 📌 Overview

This experiment was conducted to study the mechanical response of an
unknown material specimen under tensile loading using a Micro Universal
Testing Machine (Micro-UTM).

The experiment involved both hands-on machine operation and post-processing
of experimentally obtained load-extension data.

The complete workflow was:

Theory → Micro-UTM Familiarization → Tensile Test → Raw CSV Data
→ Excel Data Processing → Mechanical Property Calculation
→ Stress-Strain Analysis → Interpretation

---

## 🎯 Objective

To perform a tensile test on an unknown specimen using a Micro-UTM and
evaluate important mechanical properties from the experimentally obtained
load-extension data.

---

## 📚 1. Background and Theory

Mechanical properties describe how a material responds to applied forces
and deformation.

Tensile testing is commonly used to determine properties such as:

- Yield Stress
- Ultimate Tensile Stress
- Fracture Stress
- Young's Modulus
- Resilience
- Toughness
- Ductility
- Strain-Hardening Coefficient

### Engineering Stress

Engineering stress is calculated using the original cross-sectional area:

σₑ = P / A₀

where:

- P = Applied load
- A₀ = Original cross-sectional area

### Engineering Strain

e = Δl / l₀

where:

- Δl = Change in gauge length
- l₀ = Original gauge length

### True Stress

True stress is calculated using the instantaneous load and actual
cross-sectional area:

σₜ = Pᵢ / Aᵢ

### True Strain

True strain is obtained from the incremental deformation:

ε = ln(1 + e)

### Engineering–True Stress Relationship

σₜ = σₑ(1 + e)

These relationships were used for processing the experimental data.

---

## 🔬 2. Micro-UTM Familiarization

Before performing the experiment, the professor introduced the theoretical
concepts of stress-strain behavior and mechanical properties.

The laboratory technician then provided hands-on guidance regarding:

- Major components of the Micro-UTM
- Function of individual components
- Working principle of the machine
- Specimen mounting
- Machine operation
- Test setup
- Data acquisition
- Tensile-test procedure

This provided practical understanding of how the theoretical stress-strain
concepts are connected to an actual materials-testing system.

---

## 🧪 3. Experimental Procedure

1. The theoretical concepts and required calculations were reviewed.
2. The Micro-UTM and its components were introduced.
3. The operating procedure of the machine was demonstrated by the technician.
4. An unknown specimen was mounted in the testing machine.
5. A tensile test was performed by progressively applying tensile loading.
6. Load and extension data were recorded during the test.
7. The resulting experimental data were provided in CSV format.
8. The CSV data were converted into Excel for further processing.
9. Engineering stress and strain were calculated.
10. True stress and true strain were calculated.
11. Mechanical properties were evaluated.
12. Stress-strain and load-extension graphs were generated.
13. Strain-hardening behavior was analyzed.

---

## 📊 4. Specimen and Experimental Data

The specimen dimensions used for the calculations were:

| Parameter | Value |
|---|---:|
| Gauge Length | 3.00 mm |
| Gauge Width | 1.15 mm |
| Gauge Thickness | 1.02 mm |
| Original Cross-sectional Area | 1.173 mm² |

The raw experimental data were originally obtained in CSV format and
subsequently converted into Excel for calculations and analysis.

The Excel workbook contains the experimental load-extension data along
with calculated engineering and true stress-strain values.

---

## 💻 5. Data Processing

The experimental data were processed in Excel using formulas for:

- Engineering Stress
- Engineering Strain
- True Stress
- True Strain
- Natural logarithm of True Stress
- Natural logarithm of True Strain
- 0.2% Offset Yield Stress
- Mechanical-property evaluation
- Strain-hardening analysis

The processed dataset contains the experimental measurements together
with the calculated quantities used for generating the final graphs.

---

## 📈 6. Results

The main calculated mechanical properties were:

| Property | Result |
|---|---:|
| Ultimate Tensile Stress | 90.41 MPa |
| 0.2% Yield Stress | 69.99 MPa |
| Young's Modulus | 12.30 GPa |
| Modulus of Resilience | 0.199 MJ/m³ |
| Modulus of Toughness | 2.054 MJ/m³ |
| Ductility | 7.17 % |
| Strength Coefficient (K) | 597.47 MPa |
| Strain-Hardening Exponent (n) | 0.436 |

The fracture-stress value was not included in the final Excel summary,
so no value has been assumed here.

---

## 📉 7. Graphical Analysis

The experimental data were used to generate the following graphs:

### 7.1 Load vs Extension

The load initially increases with extension and reaches a maximum load
of approximately 106 N before decreasing as deformation progresses.

### 7.2 Engineering Stress-Strain Curve

The engineering stress-strain curve was used to identify the 0.2% offset
yield stress and ultimate tensile stress.

### 7.3 True Stress-Strain Curve

The true stress-strain curve represents the material response using
instantaneous stress and true strain.

### 7.4 Yield–Necking / Strain-Hardening Analysis

The plastic region was further analyzed using logarithmic true
stress-strain values.

The fitted relationship obtained from the analysis was:

y = 0.4355x + 6.3927

with:

R² = 0.9906

The slope of the log-log relationship corresponds to the strain-hardening
exponent:

n ≈ 0.436

---

## 📁 Repository Contents

```text
06-mechanical-properties/
│
├── README.md
│
├── data/
│   └── Experimental_Data.xlsx
│
├── graphs/
│   └── Stress_Strain_Analysis.pdf
│
├── images/
│   ├── 01_micro_utm_control_panel.png
│   ├── 02_micro_utm_tensile_testing_setup.png
│   ├── 03_micro_utm_controller_unit.png
│   ├── 04_micro_utm_data_acquisition.png
│   └── 05_micro_utm_display_unit.png
│
└── report/
    └── Lab_Report.pdf
