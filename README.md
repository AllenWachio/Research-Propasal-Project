# Autonomous Geofence-Triggered Implantable Sedative-Delivery Device

## Project Overview
This project focuses on the design, development, and validation of an autonomous implantable device for human-wildlife conflict (HWC) management. The device is engineered to provide immediate immobilization of habitual wildlife trespassers (e.g., big cats, elephants, hippopotami) when they cross a pre-defined virtual geofence boundary [cite: 10, 11]. This technology aims to shift HWC management from reactive to proactive, reducing casualties and property damage [cite: 13, 55].

## Repository Structure
- `Research_Propasal.tex`: The main LaTeX source file for the research proposal.
- `references.bib`: BibTeX database managed via JabRef containing all cited literature.
- `.gitignore`: Configuration to exclude LaTeX auxiliary files (e.g., `.aux`, `.log`, `.pdf`) from version control.

## Technical Foundations
The research integrates several technological domains:
- **GPS/GSM Telemetry:** Real-time tracking and geofence boundary detection [cite: 42, 44].
- **BioMEMS:** Biocompatible implantable architectures for drug delivery [cite: 45, 48].
- **Autonomous Control:** Closed-loop systems for sensor-triggered drug release [cite: 47, 56].
- **Refillable Systems:** Robotic drug reservoirs that can be refilled non-invasively [cite: 46, 177].

## How to Compile
To generate the proposal PDF, use a LaTeX compiler with BibTeX support:
1. `pdflatex Research_Propasal.tex`
2. `bibtex Research_Propasal.aux`
3. `pdflatex Research_Propasal.tex`
4. `pdflatex Research_Propasal.tex`

## References
All citations are managed in `references.bib` and use the `unsrtnat` style in the final document. Key literature includes studies on HWC in Kenya [cite: 21, 231], satellite telemetry in India [cite: 109, 228], and autonomous medical implants [cite: 191, 244].
