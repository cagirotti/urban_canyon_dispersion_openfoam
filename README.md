# Urban Canyon Dispersion – OpenFOAM

This repository contains an OpenFOAM case for simulating airflow and pollutant dispersion in a generic urban canyon configuration.

## Academic Context

This simulation setup is part of the PhD research of Carolina Girotti:

"Análise da morfologia urbana e da vegetação nos Eixos de Estruturação e Transformação Urbana do município de São Paulo: Aspectos da concentração e dispersão de poluentes atmosféricos"

Faculty of Architecture and Urbanism and Design (FAU-USP)
University of São Paulo (USP)

Part of this work was presented at:

Girotti, C. et al. (2024)
*Analysis of Air Velocity, Pressure Coefficient and Pollutant Dispersion in Generic Models of Urban Canyons with Computational Fluid Dynamics*
Conference: PLEA 2024 WROCŁAW (Re)thinking Resilience

## Description

The case represents a generic urban canyon used to investigate:

* Airflow patterns
* Pressure distribution
* Pollutant dispersion behavior

## How to run

```bash
chmod +x Allrun
./Allrun
```

## Mesh

The mesh is not included in this repository to keep the project lightweight.

Users must generate the mesh before running the simulation:

```bash
blockMesh
snappyHexMesh
```

## Requirements

* OpenFOAM v9 (or compatible)

## Notes

* This repository contains only the simulation setup
* No simulation results are included
* Users can adapt geometry, boundary conditions, and parameters for their own studies



