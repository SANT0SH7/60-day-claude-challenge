# Vehicle Cost Analysis Dashboard

A data-driven HTML dashboard for analyzing vehicle costs, fuel efficiency, and economic comparisons using Claude AI.

## What This Dashboard Does
- Analyzes vehicle datasets (CSV format) without coding
- Calculates comprehensive business metrics & KPIs
- Compares fuel types (petrol, diesel, E85) with cost breakdowns
- Visualizes maintenance costs and fuel consumption trends
- Generates E85 economics & break-even analysis
- Interactive SVG charts and gauges for real-time insights

## Tech Stack
- Claude AI (CSV analysis & prompt-based generation)
- HTML5 + CSS3 (responsive design)
- SVG Graphics (interactive charts & gauges)
- Business Intelligence metrics

## Key Features
✅ No-code data analysis pipeline  
✅ Complete HTML dashboard with KPI cards  
✅ Fuel cost comparison engine  
✅ Maintenance & environmental impact analysis  
✅ E85 break-even economics calculator  
✅ Browser-ready (open & use instantly)

## Learning Outcomes
- CSV data analysis without Python/SQL
- Dashboard design & data visualization
- Business metrics calculation & interpretation
- Real-world analytics use case

**Part of 60 Day AI Challenge - Building one AI tool daily**

## the prompt : 

## Details
- Vehicle : [YOUR VEHICLE MODEL]
- Fuel    : [Petrol/Diesel/CNG/E85/EV]
- Usage   : [City/Highway/Mixed/Fleet]
- KM/month: [e.g. 1000]
- Car Age : [e.g. 3 yrs]

## Role
Data analyst. Read attached CSV → compute metrics → output one HTML dashboard. HTML only, no explanation.

## Compute (group by Fuel_Type)
1. Avg Cost/km        = Fuel_Cost_INR ÷ Distance_km
2. Avg CO₂/km         = CO2_emitted_kg ÷ Distance_km
3. Avg Maintenance/km = Maintenance_Cost_INR ÷ Distance_km
4. Avg Refuel time    = Refuel_Recharge_time_min
5. Age buckets: New(0-2y) Mid-life(3-5y) Aged(6-9y) Old(10+y)
   → show Cost/km and Maint/km per bucket. Mark [CAR AGE] yrs.
6. E85 Paradox:
   - Pump saving    = ((Petrol_price−E85_price)/Petrol_price)×100
   - Running penalty= ((E85_cpkm−Petrol_cpkm)/Petrol_cpkm)×100
   - Break-even     = (E85_mileage÷Petrol_mileage)×Petrol_price
7. E85 Score/10: cost=4pt CO₂=3pt refuel=2pt maint=1pt

## Dashboard (no CDN, pure SVG charts, CSS in <style>, JS in <script>)
Dark navy #0a0f1e, glassmorphism. Colours: E85=amber Petrol=blue Diesel=grey CNG=green EV=purple.

1. Header — '[YOUR VEHICLE] · [FUEL] · Age:[CAR AGE]y · [KM/month]km/mo'
2. KPI Cards (5) — your fuel cost/km | E85 cost/km | E85 premium vs Petrol | break-even price | your monthly cost
3. SVG bar chart: Cost/km per fuel | SVG doughnut: CO₂/km per fuel (hover tooltips)
4. SVG line chart: Cost/km vs age (0-12y) per fuel. Vertical line at [CAR AGE].
5. SVG gauge: E85 score/10 (CSS animated). One verdict sentence.
6. Fuel cards: highlight [FUEL] with glow. Each: 2 pros ✅ 2 cons ❌ best-for 🚗

Output: <!DOCTYPE html> only. All numbers from CSV. Responsive 375px–1440px.
