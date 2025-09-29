# Syracuse Men’s Soccer 2024 — Ethical Decision Report

## Overview
This repository documents a stakeholder-facing decision report based on the Syracuse Men’s Soccer 2024 season data. It includes actionable recommendations generated through validated statistical analysis and supported by LLM-generated narratives. Each recommendation is tiered by risk level and includes ethical considerations.

## Purpose
To inform data-driven decisions for the upcoming 2025 season across coaching strategy, player conditioning, and recruiting — while ensuring transparency, fairness, and reproducibility.

---

## Recommendations & Visualizations

### 1. For Head Coach & Athletic Director — Operational (Low Risk)
**Recommendation**: Implement structured defensive drills to improve win probability.  
**Rationale**: Strong correlation between defensive stats and win rates.  
**Visualization**: Not shown; supported via historical bootstrap CI: [26%, 34%].

**Recommendation**: Introduce late-game HIIT conditioning.  
**Rationale**: Shot accuracy drops post-60th minute among top-minute players.  
**Visualization**:  
Fatigue Indicator: Minutes Played vs Shots Taken  


---

### 2. For Head Coach & Athletic Director — Investigatory (Medium Risk)
**Recommendation**: Adjust substitution patterns post-60 minutes.  
**Rationale**: Offensive efficiency drops significantly after 60th minute.

**Recommendation**: Monitor shot accuracy decline in top-minute players.  
**Rationale**: Cutler-DeJesus, Layton, Threadgold show late-game dips.  


---

### 3. For Head Coach & Athletic Director — Strategic (High Risk)
**Recommendation**: Reassess senior player roles (e.g., Kaloukian, Scott).  
**Rationale**: High playing time but low conversion (Kaloukian: 6.2%).  
**Visualization**:  
Shot Conversion Rate Comparison  


---

### 4. For Strength & Conditioning Coach — Operational (Low Risk)
**Recommendation**: Deploy recovery-focused training post-60 minutes.  
**Rationale**: Team-wide dip in performance late in matches.  
**Visualization**: See fatigue chart.

---

### 5. For Director of Recruiting — Investigatory (Medium Risk)
**Recommendation**: Prioritize players with high goals/90 over total shots.  
**Rationale**: Fortier outperforms Kaloukian on efficiency despite fewer minutes.  
**Visualization**:  
Recruitment Efficiency: Goals per 90 Minutes  
![Goals per 90](visualization_2.png)

---

## Ethical Considerations
- All LLM content is clearly labeled and human-validated.
- Role changes and recruitment recommendations reviewed for fairness.
- Reproducible code, prompts, and datasets archived.

## Repository Contents
- `notebooks/` – Jupyter analysis and bootstrapping code
- `visuals/` – Exported visualizations for inclusion
- `prompts/` – LLM-generated interview prompts and transcripts
- `report/` – Final docx/pdf submission
- `README.md` – This file

---

## Reproducibility
All findings are derived using open-source tools (Python, Polars, Matplotlib). Confidence intervals and effect sizes are calculated via bootstrapping techniques. Full audit trail is preserved.

## Author
Bhaarat Kotak – M.S. IS Grad, Syracuse University  
Research Task 07 