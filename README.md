# Amazon Logistics Optimization – SQL Project

## Project Overview

This project focuses on analyzing Amazon’s logistics operations using SQL to identify delivery delays, route inefficiencies, warehouse bottlenecks, and delivery agent performance issues. The analysis aims to improve shipment efficiency, reduce delays, and enhance overall customer satisfaction through data-driven insights.

---

## Tools & Technologies

* MySQL
* MySQL Workbench
* SQL (Joins, CTEs, Window Functions, Subqueries)

---

## Database Used

**Amazon_Logistics**

### Tables:

* `orders`
* `routes`
* `warehouses`
* `deliveryagents`
* `shipment_tracking`

---

## Project Objectives

* Analyze delivery delays and shipment performance
* Identify inefficient routes and traffic bottlenecks
* Evaluate warehouse processing efficiency
* Measure delivery agent performance
* Provide actionable optimization recommendations

---

## Task 1: Data Cleaning & Preparation

* Removed duplicate `Order_ID` records
* Handled NULL traffic delays using route-level averages
* Standardized all date columns
* Validated delivery timelines

---

## Task 2: Delivery Delay Analysis

* Calculated delivery delay (in days) for each order
* Identified top delayed routes
* Ranked delayed orders within each warehouse

---

## Task 3: Route Optimization Insights

* Calculated average delivery time per route
* Analyzed traffic delays and efficiency ratios
* Identified routes with more than 20% delayed shipments

---

## Task 4: Warehouse Performance

* Ranked warehouses by average processing time
* Identified bottleneck warehouses using CTEs
* Calculated on-time delivery percentage per warehouse

---

## Task 5: Delivery Agent Performance

* Ranked agents by on-time delivery percentage
* Identified underperforming agents (<80% on-time)
* Compared speed of top vs bottom performing agents

---

## Task 6: Shipment Tracking Analytics

* Identified last delivery checkpoint per order
* Analyzed most common delay reasons
* Flagged orders with repeated delivery delays

---

## Task 7: Advanced KPI Reporting

* Average delivery delay by region
* Overall on-time delivery percentage
* Average traffic delay per route

---

## Key Insights

* Routes R012, R017, and R020 show the highest delays
* Warehouses W010 and W001 are major bottlenecks
* Sorting and traffic delays are the most frequent causes
* Faster delivery agents have significantly higher on-time rates

---

## Business Recommendations

* Optimize high-delay routes using dynamic rerouting
* Improve warehouse processing efficiency
* Retrain and monitor low-performing delivery agents
* Schedule deliveries during off-peak traffic hours

---

## Project Files

* `amazon_logistics_optimization.sql` – All SQL queries
* `Presentation 2.pdf` – Project presentation
* Video walkthrough (Google Drive link)

