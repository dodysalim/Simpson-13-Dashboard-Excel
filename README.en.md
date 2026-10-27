<p align="center"><img src="https://dodysalim.github.io/assets/project-covers/simpson.webp" alt="Simpson 1/3" width="100%"></p>

<h1 align="center">Simpson 1/3</h1>

<p align="center"><b>Numerical integration in Excel with an interactive dashboard and documented VBA code.</b></p>

<p align="center"><img src="https://img.shields.io/badge/Personal_project-75E6CE?style=for-the-badge&labelColor=0b1222" alt="Personal project"></p>

<p align="center">
<img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logoColor=white" alt="Excel"> <img src="https://img.shields.io/badge/VBA-5C2D91?style=flat-square&logoColor=white" alt="VBA">
</p>

<p align="center"><a href="https://dodysalim.github.io/"><b>🌐 Portfolio</b></a> · <a href="README.md"><b>🇪🇸 Versión en español</b></a></p>

---

## 📌 At a glance

| | |
| --- | --- |
| **🎯 Problem** | Compute definite integrals and visualize the even/odd weights of Simpson's 1/3 rule. |
| **🛠️ Solution** | Excel workbook with VBA macros, input validation and error handling. |
| **📈 Deliverables** | Excel dashboard with point table and method chart. |

## 🏗️ Architecture

```mermaid
flowchart LR
    IN[Función f·x, límites a-b, n par] --> VBA[Macro VBA<br/>Simpson_Dashboard_Pro]
    VBA --> VAL{n par y<br/>2 ≤ n ≤ 100.000}
    VAL -->|sí| CALC[Pesos 1-4-2-4…-1<br/>h/3 · Σ]
    VAL -->|no| ERR[Mensaje de error]
    CALC --> TAB[Tabla de puntos]
    CALC --> RES[Resultado]
    TAB --> GR[Gráfica del área]
```

## 🚀 How to run

```text
Open Simpson_Pro.xlsm in desktop Excel with macros enabled.
To use the reviewed source, import Simpson_VBA.txt into a VBA module and run Simpson_Dashboard_Pro.
```

## ⚖️ Scope

n must be even, between 2 and 100,000. Accuracy depends on the function and step size.

---

<p align="center">
<b>Dody Dueñas Remache</b> · Data Analyst / Data Scientist · Guayaquil, Ecuador (remote LATAM)<br>
<a href="https://dodysalim.github.io/">Portfolio</a> · <a href="https://github.com/dodysalim">GitHub</a> · <a href="https://www.linkedin.com/in/dody-duenas/">LinkedIn</a> · <a href="mailto:dodydurema67@gmail.com">dodydurema67@gmail.com</a>
</p>
