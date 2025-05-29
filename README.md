# RE-DISTRIBUTION-VEHICLE-OPTIMIZATION-WITH-MULTI-DEPOTS-PROBLEM

## Description
This Jupyter Notebook contains a comprehensive fleet management and route optimization system designed to efficiently assign delivery outlets to multi depots and optimize truck routes. The system processes geographical data, calculates distances, balances depot assignments, clusters routes, and visualizes results.

## Key Features
- **Data Processing**: Loads and preprocesses fleet, outlet, and depot data from Excel files
- **Distance Calculations**: Computes geodesic distances between outlets and depots
- **Depot Assignment**: Balances outlet assignments to depots based on capacity and regional demand
- **Route Optimization**: Uses K-means clustering and nearest neighbor heuristics to create efficient truck routes
- **Utilization Analysis**: Calculates truck loads and monthly mileage metrics
- **Visualization**: Generates histograms and other plots to analyze truck utilization

## Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- scikit-learn (K-means clustering)
- geopy (distance calculations)
- folium (geographical visualization)

## Usage
The code processes input data from Excel files (`fleet.xlsx`, `outlets.xlsx`, `depots.xlsx`) and outputs optimized route assignments, utilization metrics, and visualizations. The system is designed for delivery networks with multiple depots and truck fleets of varying capacities.

## Results
The notebook includes visualizations showing the distribution of monthly truck utilization, with targets marked at 80-100% utilization for optimal fleet efficiency.
