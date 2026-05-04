# NorthStar Urban Mobility & Logistics Analytics Project

## Overview
This project analyses operational inefficiencies within **NorthStar Urban Mobility and Logistics**, a multi-service transport and delivery provider.  
The company operates across shuttle transport, last-mile delivery, EV charging, warehouse dispatch, and a mobile platform.

Despite growing demand, NorthStar faces increasing:
- Delivery failures and delays  
- Customer complaints  
- Operational costs exceeding revenue growth  

The core issue lies in **fragmented data systems**, where structured relational data and semi-structured platform data are not integrated.

---

## Project Objective
The goal of this project is to design an **integrated analytics solution** that:
- Identifies key operational inefficiencies  
- Analyses failure patterns across hubs and zones  
- Evaluates customer complaints and financial impact  
- Explores relationships between operational factors (drivers, routes, incidents)  
- Designs a NoSQL database for complex, event-driven data  

---

## Key Research Questions
1. What are the highest failure rates and what drives them across hubs and zones?  
2. Does driver behaviour (manual route overrides) affect service quality?  
3. Which customers generate repeated failures and compensation costs?  
4. Can operational indicators predict delivery failures and incident severity?  

---

## Technologies Used
- **R** (sqldf, dplyr, ggplot2) → SQL queries, statistical analysis, visualisation  
- **Python** → Data processing and transformation  
- **MongoDB Atlas** → NoSQL database design for complex data  
- **Google Colab** → Development environment  
- **GitHub** → Version control and project structure  

---

## Workflow

### 1. SQL Analysis (R)
- SQL queries executed using `sqldf`  
- Identifies failure rates, delays, and operational bottlenecks  

### 2. Statistical Analysis (R)
- Data manipulation using `dplyr`  
- Visualisation using `ggplot2`  
- Identifies trends and performance gaps  

### 3. Data Processing (Python)
- Data cleaning and transformation  
- Additional analysis and charting  

### 4. NoSQL Database Design (MongoDB)
- Document-based modelling for:
  - Complaints  
  - Deliveries & incidents  
  - App event sessions  
- Optimised for flexible, nested, and event-driven data  

---

## Key Insights (Summary)
- Central zone hubs show significantly higher failure rates  
- Operational inefficiencies vary by hub and zone  
- Customer complaints are strongly linked to delivery delays  
- Platform issues create direct financial impact  
- Data fragmentation limits visibility and decision-making  

---

## Solution Approach
The project combines:
- **Relational analysis (SQL)** for structured data  
- **Statistical modelling (R)** for deeper insights  
- **Python processing** for flexibility and scalability  
- **NoSQL (MongoDB)** for handling complex data  

This hybrid approach enables a **complete view of operations** and supports data-driven decisions.

---

## Notes
- Data is loaded via Google Drive or the `/data` folder  
- Each notebook can run independently  
- MongoDB Atlas is used for cloud-based NoSQL implementation  


---

## Conclusion
This project demonstrates how combining SQL, R, Python, and NoSQL technologies can solve real-world data challenges by integrating fragmented systems, uncovering hidden inefficiencies, and improving operational performance.




