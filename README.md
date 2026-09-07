# Pillar Respiratory Assessment — Prototype

An interactive, self-contained prototype simulating a cross-sectional respiratory assessment protocol for post-heart-transplant recipients. Built to visualize and pressure-test a research design before real data collection begins.

## Live demo

[live prototype](https://Taniya-Tariq.github.io/-respiratory-assessment-prototype/respiratory-assessment-prototype.html)

## What it does

Enter a hypothetical patient profile — demographics, months since transplant, immunosuppressant regimen, and clinical characteristics — and the tool generates simulated scores across four pillars of respiratory capacity:

- **Function** — lung capacity and volume (FVC, FEV1)
- **Strength** — inspiratory/expiratory muscle power (MIP/MEP, handgrip)
- **Endurance** — cardiopulmonary exertion capacity (6MWT)
- **Mobility** — chest wall and shoulder range of motion

Results are plotted on a radar chart against a healthy-individual reference line, alongside per-pillar metric cards and a short "personalized insight" summarizing the weakest pillar for that profile.

## Why

The underlying research protocol proposes that post-heart-transplant recipients show impaired capacity across all four pillars compared to healthy individuals, driven by demographic, clinical, and transplant-related factors. This prototype makes that framework tangible — a way to see how inputs might map to outputs before the actual cross-sectional study runs.

## Running it

No build step, no dependencies. Just open `respiratory-assessment-prototype.html` in any modern browser.

## Tech

Plain HTML, CSS, and vanilla JavaScript. The radar chart is hand-drawn inline SVG — no external libraries or CDN calls, so it works fully offline.

## Important disclaimer

This is a **prototype for demonstrating protocol design**, not a diagnostic or predictive tool. The scoring model is a simplified simulation for illustration only and has not been validated against real patient data. Score thresholds (Normal / Mild impairment / Significant impairment) are illustrative, not clinically established cut-offs. Nothing here should inform real care decisions.

## Context

Part of research work in  cardiopulmonary rehabilitation.
