Route Optimization Manila 🚚
A Python-based logistics tool that calculates the most efficient delivery route across Metro Manila using real-world road data.

Project Scope
Depot: Intramuros, Manila.

Stops: Quezon City, BGC, Makati, and Roxas Blvd.

Goal: Minimize total travel time using the Clarke-Wright Savings Algorithm.

How to Run
Install Libraries:
pip install osmnx networkx requests pandas numpy folium geopy

Execute: Run all cells in route_optimization_osrm_networkx.ipynb.

View Map: Open routes_map.html in any web browser to see the interactive result.

Configuration
The project uses the OSRM Public Demo Server by default. To change this to a self-hosted server, update the OSRM_BASE variable in the notebook:

Python
# Change this URL to switch servers
OSRM_BASE = "http://router.project-osrm.org" 
