Project Title:
Demand Forecasting and Inventory Optimization for Milk Supply Chain

Overview:
This project analyzes 24 months of monthly milk demand data (litres) to build a forecasting and inventory optimization system. It combines demand analysis, statistical forecasting, EOQ-based ordering, safety stock calculation, and inventory simulation to support cost-efficient supply chain decisions.

Dataset
•	Time period: 2024-01 to 2025-12 (24 months)
•	Demand unit: litres
•	Total demand: 1579.5 litres
•	Average monthly demand: 131.63 litres
•	Demand variability (std dev): 20.50 litres

Methodology
1. Demand Analysis & Forecasting
•	Historical demand trends analyzed over 24 months
•	Forecasting compared against actual demand to evaluate variability and pattern stability
2. Inventory Optimization
•	Economic Order Quantity (EOQ): 281 litres
•	Annual demand: 1579.5 litres
•	Ordering cost assumption: Tk 500 per order
•	Holding cost assumption: Tk 20 per litre per year
3. Reorder Policy
•	Daily demand: 4.39 litres
•	Safety stock: 2.52 litres
•	Reorder point (final): 24.46 litres

Inventory Simulation
A time-based simulation was implemented to evaluate stock behavior under real demand fluctuations. The model triggers replenishment when inventory drops below the reorder point and tracks stockout occurrences.

Cost Optimization Results
•	Total annual cost (before EOQ): 7316
•	Total annual cost (after EOQ): 5810
•	Cost savings: 1506 (~20.6% reduction)

Key Output
•	Reduced total inventory cost by optimizing order size
•	Defined a data-driven reorder policy
•	Simulated inventory behavior under demand variability
•	Identified cost-service tradeoff in milk supply chain management

Tools Used
•	Python (Pandas, NumPy, Matplotlib)
•	Google Colab
•	Excel (data preprocessing)

Key Insight
The EOQ-based policy reduces ordering frequency while balancing holding cost, resulting in a lower total supply chain cost while maintaining controlled inventory levels under fluctuating milk demand (litres).

