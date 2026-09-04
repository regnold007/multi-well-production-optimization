# Multi-Well Production Optimization & Artificial Lift Design

Advanced Production Engineering term project: nodal analysis and PIPESIM multiphase-flow simulation across six oil wells to select optimum tubing/pipeline sizes, design artificial lift systems, and evaluate project economics over field life.

## Abstract

This project investigates six oil wells (Wells A–F) for production performance, flow assurance, artificial lift needs, and overall economic feasibility, using an integrated nodal analysis and multiphase flow simulation approach. Steady-state models were run for Year 0 base-case conditions to identify optimal tubing diameters that maintain stable flow, keep fluid velocities within acceptable limits, and support long-term operation. All wells were equipped with chokes to mitigate backflow and restrain excessively high production rates, following conventional production system design guidelines.

Artificial lift was introduced at different points in the wells' production life as reservoir pressure declined and the risk of liquid loading increased: gas lift on Wells A and B, electric submersible pumps (ESPs) on Wells C and E, and rod pumps on Wells D and F. Sensitivity studies refined gas injection rates, pump staging, operating frequencies, and stroke speeds to balance efficient energy use against stable operation.

Multiphase flow behavior was modeled in PIPESIM using standard correlations to examine pressure, temperature, and velocity profiles, with particular attention to liquid loading tendencies and erosion thresholds. An economic analysis incorporating oil price, water disposal expense, and artificial lift power costs was used to calculate annual cash flows and net profits.

## Methodology

1. **Nodal analysis for pipe sizing** — inflow performance relationships (IPR) from multipoint well test data compared against tubing outflow curves for multiple diameters, for each of the six wells, to select the optimum tubing size.
2. **Pressure, temperature, and superficial gas velocity profiling** — PIPESIM multiphase-flow simulation for each well at Year 0 conditions.
3. **Production decline analysis** — forecasting well performance as reservoir pressure depletes over field life.
4. **Artificial lift sensitivity analysis and optimization** — gas lift injection rate studies, ESP pump-stage/frequency sensitivity, and rod pump stroke-speed sizing per well.
5. **Uncertainty analysis** — evaluating the effect of multiphase flow correlation selection on tubing/pipeline sizing decisions.
6. **Economic evaluation** — annual cash flow analysis incorporating oil price, water disposal costs, and lift power costs.

## Repository Contents

- `Production_Term_Project_Report.pdf` — full project report (abstract, methodology, well-by-well results, economics, and conclusions).
- `Well_A.pips`, `Well_network_Year_0.pips`, `Well_network_RIGHT_NOW.pips`, `Well_network_Year_5.pips` — PIPESIM well and network models at different points in field life.
- `Production_Project_Workbook.xlsx` — supporting production and economic calculations.

## Team

Tafadzwa Guzha & Regnold Chinowaita
*PE 5523 — Advanced Production Engineering, University of Oklahoma*
*Instructors: Dr. H. Karami & Dr. X. Wu*
