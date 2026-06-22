# Risk and Logistics Optimisation

Two optimisation projects addressing uncertain facility location and charging
infrastructure design.

## Overview

This repository contains two group projects completed for the University of
Edinburgh Risk and Logistics course.

### Project 1: Facility Location Under Uncertain Demand

The first project considers a multi-period warehouse-location problem with
uncertain customer demand. The objective is to make robust infrastructure and
allocation decisions while controlling operating and transportation costs.

My contribution was clustering customer demand using measures of economic
similarity, reducing the problem to a more tractable representation.

### Project 2: Drone Charging Infrastructure

The second project determines where charging stations should be constructed and
how many chargers should be installed so that a fleet of drones can complete
its required operations.

My contribution included:

- a continuous mixed-integer programming model;
- a discrete mixed-integer programming model;
- continuous and discrete construction heuristics;
- neighbourhood-search procedures for improving heuristic solutions;
- comparison of exact and heuristic approaches.

## Methodology

- Mixed-integer programming
- Facility-location and capacity decisions
- Demand aggregation and clustering
- Construction heuristics
- Local neighbourhood search
- Cost and feasibility comparison across modelling assumptions

## Repository Contents

- `Project_1_Report.pdf` and `Project_2_Report.pdf` - complete reports.
- `Project_1_Assignment.pdf` and `Project_2_Assignment.pdf` - original problem
  specifications.
- `aggregation.ipynb` - demand aggregation for Project 1.
- `1a_a.ipynb` to `2.ipynb` - exact and heuristic models for Project 2.
- `Project_1_Data.zip` and `Project_2_Data.zip` - project data.

## Running the Models

Extract the relevant data archive, open the associated notebook, and update any
local file paths before running the cells in order. Required packages are listed
in the notebook imports.

## Key Skills Demonstrated

Operations research, mixed-integer programming, facility location, optimisation
under uncertainty, heuristic design, local search, clustering, and Python.

## Academic Context

Group projects completed at the University of Edinburgh. Individual
contributions are identified above.
