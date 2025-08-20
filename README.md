# AUTO-INTELLIX - Smart Car Maintenance Analytics System 🚗📊

This repository contains all deliverables from my **Data Engineering Internship** project at *Data Sparks*.  
The project is focused on building a **Smart Car Maintenance Analytics System** for AUTO-INTELLIX, enabling better insights into service center performance, customer behavior, and operational efficiency.

---

## 📂 Repository Structure

- **/docs** → Contains project documentation (e.g., BRD).
- **/erd** → Entity Relationship Diagram of the system database.
- **/process flow** → End-to-End Car Service Process Flow diagrams.

---

## 🎯 My Contributions

During this project, I contributed to:
- Collaborating with the team to design the **ERD**.
- Implementing the **KPI calculations** for the first dashboard in Power BI.
- Reviewing the **Business Requirements Document (BRD)**.
- Presenting the BRD to our instructor on behalf of the team.

---

## 📊 Key KPIs I Implemented

Here are the KPIs/metrics I worked on for the **first dashboard**:

1. **Maintenance Type Distribution (CM vs PM)**  
   - Shows proportion of corrective vs. preventive maintenance.  
   - Formula:  
     ```
     (Bookings by Maintenance Type / Total Bookings) * 100
     ```

2. **Recurring Issues Rate**  
   - Identifies % of repeated issues for the same vehicle within 30 days.  
   - Formula:  
     ```
     (Repeated Service Codes per Vehicle / Total Service Codes) * 100
     ```

3. **First-Time Fix Rate**  
   - Measures how often an issue is resolved on the first attempt.  
   - Formula:  
     ```
     (Unique Service Entries without Repeat / Total Service Entries) * 100
     ```

4. **Maintenance Backlog Volume**  
   - Tracks number of pending or unfinished requests.  
   - Formula:  
     ```
     Count of requests with Status = 'Pending' or 'Finished'
     ```

5. **Top Service Bundles**  
   - Identifies the most common sets of services performed together.  
   - Formula:  
     ```
     Group services by BookingID → Count frequency → Top N bundles
     ```

6. **Capacity Utilization Rate**  
   - Measures how much of the service center capacity is used.  
   - Formula:  
     ```
     (Actual Bookings / Total Capacity) * 100
     ```

7. **Top 5 Requested Services**  
   - Shows the most frequently booked services.  
   - Formula:  
     ```
     Count of ServiceCode across bookings → Top 5
     ```

---

## 🚀 Tools & Skills Used

- **Data Modeling** (ERD design)
- **Business Requirements Review** (BRD)
- **Power BI** (KPI definitions & dashboard design)
- **Team collaboration & presentations**

---

## 📌 Notes

This repo will be updated gradually as the project progresses.  
Final deliverables will include the **full process flow, ERD, dashboards, and documentation**.
