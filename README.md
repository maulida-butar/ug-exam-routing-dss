# UG-Routing DSS: Examination Document Distribution Optimizer

An optimization framework for the distribution of examination papers and administrative documents using **Capacitated Vehicle Routing Problem with Time Windows (CVRPTW)**.

## Case Study
**Universitas Gunadarma**, Indonesia. 
This system optimizes routes from Campus E (Depot) to various campus locations (D, G, F4-F8) under strict delivery deadlines.

## Key Features
- **Optimization Engine:** Google OR-Tools (Guided Local Search metaheuristic).
- **Road Network Data:** Open Source Routing Machine (OSRM) API for real-road distance & duration.
- **Interactive Dashboard:** Built with Streamlit for dynamic scenario analysis.
- **Spatial Visualization:** Interactive maps using Folium.

## Installation
1. Ensure you have **Python 3.13+** installed.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
