# Numerical Inverse Kinematics in Cluttered Environments

Seminar report on numerical approaches to the Inverse Kinematics (IK) problem in cluttered environments.

## Author

**Emanuel André Medina Araujo**  
Technische Universität München  
Email: emanuel.medina@tum.de

## Overview

This report presents an overview of the most common numerical approaches to solving the Inverse Kinematics problem for robots operating in cluttered environments. The report analyzes three major classes of methods:

- **Jacobian Methods** - Including Jacobian Inverse, Jacobian Transpose, and (Selectively) Damped Least Squares
- **Heuristic Methods** - Including Cyclic Coordinate Descent (CCD) and FABRIK
- **Meta-Heuristic Methods** - Including Differential Evolutionary Algorithms and Particle Swarm Optimization

Each method is examined for its ability to handle the secondary task of obstacle avoidance.

## Compilation

To compile the LaTeX document:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

Or use your preferred LaTeX editor/IDE.

## Requirements

- LaTeX distribution (e.g., TeX Live, MiKTeX)
- IEEEtran document class (included)
- Standard LaTeX packages: amsmath, graphicx, cite, subfig, threeparttable

## Files

- `main.tex` - Main document source
- `coverpage.tex` - Cover page template
- `Bibliography/Report.bib` - Bibliography database
- `IEEEtran.cls` - IEEE conference paper class
- `images/` - Figures and diagrams
- `SeminarReport.pdf` - Compiled PDF output

## Seminar

**Course:** Cyber-Physical Systems  
**Term:** Summer Term 2023  
**Advisor:** Jonathan Külz  
**Supervisor:** Prof. Dr.-Ing. Matthias Althoff  
**Submission:** 31. July 2023

## License

This is an academic seminar report. Please contact the author for usage permissions.
