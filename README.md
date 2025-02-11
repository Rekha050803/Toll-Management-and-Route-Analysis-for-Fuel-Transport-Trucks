# 🚛 Toll Management and Route Analysis for Fuel Transport Trucks

## 📌 Introduction  
Efficient toll management is critical in the logistics sector, especially for fuel transport companies. Manual toll claims are often error-prone and susceptible to fraud, leading to increased costs and reduced transparency. This project automates toll cost calculations, ensuring accuracy and integrity in route and toll compliance.

---

## 🚀 Features  
✅ **Automated Toll Cost Calculation** – Identifies toll plazas crossed and calculates accurate toll expenses.  
✅ **Fraud Prevention** – Ensures only legitimate toll claims are reimbursed.  
✅ **GPS-Based Route Tracking** – Monitors real-time vehicle movement and logs route details.  
✅ **Interactive Map Visualization** – Displays vehicle journeys, toll plazas crossed, and halt locations.  
✅ **Data-Driven Insights** – Generates reports for trip analysis and financial reconciliation.  

---

## 🛠️ Tech Stack  
- **Frontend:** HTML, CSS, JavaScript  
- **Backend:** Python (for data processing and mapping)  
- **Libraries Used:**  
  - 📍 **Folium** – For interactive map generation  
  - 🌍 **Geopy** – For distance calculations  
  - 📊 **Pandas** – For data handling and analysis  
  - 🔢 **NumPy** – For numerical computations  

---

## 📊 Dataset  
📌 **Toll Data** – Includes toll plaza locations, latitude/longitude, and charges.  
📌 **Vehicle Tracking Data** – Contains trip IDs, vehicle numbers, GPS coordinates, and timestamps.  

---

## 🔧 Implementation  
The system follows a structured process to automate toll management and route analysis:  

1️⃣ **Data Collection & Preprocessing**  
   - Collects vehicle GPS tracking data and toll plaza locations.  
   - Cleans and structures data using **Pandas**.  
   - Stores the data in **CSV files** for easy access.  

2️⃣ **Route Mapping & Toll Detection**  
   - Uses the **Great Circle Distance algorithm** to find nearby toll plazas.  
   - If a vehicle is within **1 km** of a toll plaza, it is marked as a valid toll crossing.  

3️⃣ **Toll Cost Calculation**  
   - Determines **single or round trips** based on toll crossings.  
   - Computes total toll charges by summing up toll fees.  

4️⃣ **Interactive Map Visualization**  
   - Uses **Folium** to create an interactive map showing:  
     - **Vehicle journey** (start and end points).  
     - **Toll plazas crossed** (marked locations).  
     - **Halts** detected along the route.  

5️⃣ **Report Generation & Data Export**  
   - Generates **CSV reports** summarizing:  
     - Toll crossings for each trip.  
     - Total toll charges.  
     - Route compliance status.  
   - Saves **interactive maps as HTML files** for visualization.  

---

## 🎯 Outcome  
✅ Accurate toll cost calculation  
✅ Fraud prevention in toll claims    
✅ Interactive visualization of routes and tolls  


