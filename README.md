# mcs-forestry-feasibility-map
Interactive megawatt charging station feasibility map for forestry fleet electrification in Sweden
This project analyzes the feasibility of using megawatt charging stations (MCS) to support the electrification of forestry truck operations in Sweden.

Instead of relying on abstract driving range assumptions, the analysis evaluates real forest-to-sawmill transport links based on routing via the nearest MCS and measuring the additional detour distance.

An interactive spatial map is provided to explore feasible transport connections for 37 sawmills.

---

## Methodology

For each forest harvesting location and sawmill pair:

- Direct road network route distance is computed  
- The nearest available megawatt charging station is assigned  
- Total route via MCS is calculated:
  - Forest → MCS  
  - MCS → Sawmill  
- Absolute and relative detour distance is measured  

OD pairs are classified as feasible if MCS access requires less than:

- 1 km detour  
- 5 km detour  
- 10 km detour  

To identify infrastructure gaps, a fallback mechanism expands the allowable route length from 150 km up to 350 km and selects the minimum-detour connection where no feasible OD exists.

---

## Key Contributions

- OD-level electrification feasibility (not fleet averages)  
- Detour-based operational realism  
- Explicit detection of charging infrastructure gaps  
- Spatially resolved sawmill-level results  

---

## Interactive Map

Open the live visualization:

👉 https://github.com/HamounPR/mcs-forestry-feasibility-map
Use the controls to:

- Select detour thresholds  
- Explore sawmill-specific transport links  

---

## Applications

- Megawatt charger placement planning  
- Forestry freight electrification strategies  
- Infrastructure gap analysis  
- Integration with fleet simulation models

---

## Author

Hamoun Pourroshanfekr Arabani  
PhD Researcher – Energy Systems & E-Mobility
