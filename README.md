# data-portfolio-evangelina
Data analysis portfolio - R &amp; Python projects


01_morphometrics
Geometric Morphometric Analysis

This module performs a geometric morphometric analysis to quantify shape variation and evaluate the effects of biological and environmental factors.

Overview

Landmark-based morphometrics are used to:

quantify shape variation
test differences among groups (sex, nest)
evaluate allometric effects (shape ~ size)
Data
Landmark data: TPS format (SD.tps)
Metadata: Excel file (Datos_todos.xlsx)
Replicates: 3 digitizations per individual
Workflow
Data import and cleaning
Generalized Procrustes Analysis (GPA)
Averaging of landmark replicates
Principal Component Analysis (PCA)
Shape analysis using Procrustes ANOVA
Canonical Variate Analysis (CVA)
Visualization of morphospace
Outputs
PCA plot (shape variation)
CVA plot (group differentiation)
Statistical models:
Shape ~ Sex
Shape ~ Nest
Shape ~ Size (allometry)
Requirements

R packages:

geomorph
readxl
dplyr
ggplot2
MASS
viridis
Notes
Shape is analyzed independently of size, position, and orientation after GPA.
CVA is performed on principal components to reduce dimensionality and noise.
This workflow is suitable for high-replicability morphometric datasets.
