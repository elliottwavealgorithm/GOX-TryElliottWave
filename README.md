<p align="center">
  <img src="https://img.shields.io/badge/Status-Research%20MVP-blue?style=for-the-badge" alt="Status" />
  <img src="https://img.shields.io/badge/TradingView-Partner-131722?style=for-the-badge&logo=tradingview&logoColor=white" alt="TradingView Partner" />
  <img src="https://img.shields.io/badge/License-Research-green?style=for-the-badge" alt="License" />
</p>

<h1 align="center">
  <strong>GOX</strong>
  <br />
  <sub>Generative Object eXtraction for Elliott Wave Research</sub>
</h1>

<p align="center">
  <strong>TryElliottWave · Research MVP</strong>
</p>

---

GOX is an early-stage research MVP developed under the **TryElliottWave** initiative. The project explores how traders conceptualize, draw, and validate Elliott Wave structures on financial charts, and how those human-generated structures can be transformed into structured datasets suitable for computational analysis and machine learning research.

> At its core, GOX bridges **human technical analysis cognition** with **programmatic representation**, enabling the systematic study of subjective chart annotations at scale.

---

## 📌 Research Motivation

Elliott Wave Theory is widely used in discretionary trading, yet remains difficult to formalize due to its interpretive and subjective nature. Most existing tools focus on visualization or post-hoc labeling, but do not capture the **decision process** behind wave construction.

GOX approaches this gap by treating chart drawings as **first-class data objects**, allowing researchers to:

- 🔍 **Observe** how humans encode market structure visually
- 📊 **Measure** consistency, variance, and rule adherence across users
- 🤖 **Explore** whether subjective wave interpretations can be modeled, evaluated, or assisted algorithmically

---

## 🎯 Core Objectives

| Objective | Description |
|-----------|-------------|
| **Interactive Drawing** | Enable users to draw Elliott Wave and Fibonacci structures directly on interactive financial charts |
| **Structured Capture** | Programmatically capture each drawing as structured data: anchor points, geometry, wave hierarchy, labeling, timestamps, and chart context |
| **Real-time Validation** | Apply real-time structural validation against formal Elliott Wave principles |
| **Dataset Persistence** | Persist datasets for downstream research and ML/LLM experimentation |
| **Feedback Mechanisms** | Provide feedback that surfaces rule violations, ambiguities, or alternative interpretations |

---

## 🏗️ System Overview

```
┌─────────────────────────────────────────────────────────────────────────┐
│                              FRONTEND                                    │
│         TradingView Advanced Charts · Native Drawing Tools              │
└─────────────────────────────────┬───────────────────────────────────────┘
                                  │
                                  ▼
┌─────────────────────────────────────────────────────────────────────────┐
│                      EXTRACTION LAYER (GOX)                             │
│      Converts drawings → Normalized, machine-readable representations   │
└─────────────────────────────────┬───────────────────────────────────────┘
                                  │
                                  ▼
┌─────────────────────────────────────────────────────────────────────────┐
│                        VALIDATION ENGINE                                │
│   Deterministic rule checks: wave relationships, retracements, overlaps │
└─────────────────────────────────┬───────────────────────────────────────┘
                                  │
                                  ▼
┌─────────────────────────────────────────────────────────────────────────┐
│                   RESEARCH DATASET PIPELINE                             │
│            Pattern analysis · Label evaluation · ML/LLM training        │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 📈 Current Status

<table>
  <tr>
    <td><strong>🌐 Live MVP</strong></td>
    <td><a href="https://www.tryelliottwave.com">www.tryelliottwave.com</a></td>
  </tr>
</table>

### ✅ Demonstrates

- Advanced Charts integration
- Drawing capture and persistence
- Core validation logic and data workflow

### 🔬 Active Focus

- Data schema refinement
- Rule formalization
- Research-oriented instrumentation *(rather than trading signals)*

---

## 🔭 Research Scope

Potential research directions enabled by GOX include:

| Area | Description |
|------|-------------|
| **Human Variability** | Modeling human variability in Elliott Wave interpretation |
| **Validation Methods** | Rule-based vs probabilistic validation of technical structures |
| **AI Assistance** | Assisted technical analysis via AI feedback loops |
| **Feature Extraction** | Feature extraction from subjective chart annotations |
| **Hybrid Representations** | Symbolic + statistical representations of market structure |

---

## 🎓 Educational & Institutional Context

<table>
  <tr>
    <td>
      <p>The project is currently developed for <strong>educational and research purposes</strong>, in collaboration with the <strong>Instituto de Análisis Técnico Bursátil (IAT)</strong> in Mexico, an educational partner of TradingView.</p>
      <br />
      <p><em>There is no trading execution, brokerage connectivity, or automated decision-making in the current scope.</em></p>
    </td>
  </tr>
</table>

---

## 🚀 Future Directions

If validated successfully, GOX could evolve into:

1. **Public Research Platform** — For technical analysis cognition studies
2. **Dataset Foundation** — For AI-assisted market structure interpretation
3. **Educational Tool** — To improve analyst training through structured feedback

> Any future commercial deployment would pursue the appropriate licensing agreements and ethical research considerations.

---

## ⚠️ Disclaimer

<table>
  <tr>
    <td align="center">
      <strong>GOX is a research prototype.</strong>
      <br /><br />
      It does not provide financial advice, trading signals, or execution capabilities.
    </td>
  </tr>
</table>

---

<p align="center">
  <sub>Built with ❤️ for Elliott Wave Research</sub>
</p>
