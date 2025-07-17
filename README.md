## 🧪 Fischer Cutter RCA & Process Intelligence Dashboard

### 🛠 Project Type: Industrial Analytics | Root Cause Analysis | Power BI | Process Optimization

---

## 📘 Project Summary
We studied downtime and process instability in a high-speed tire manufacturing line (RH Calender → Fischer Cutter), analyzing multiple fault types using real secondary data collected from the field — including shift engineer reports, PLC logs, and RCA documentation.

Using Power BI, we built a decision-support dashboard for engineers and plant managers to identify bottlenecks and visualize fault trends across machines, shifts, and compounds.

As a result, we diagnosed critical machine-level issues and implemented corrective actions — including design and control recommendations formally communicated to the OEM, resulting in upgrades to subsequent machine deliveries.

The insights also revealed a strong correlation between compound properties, calender roll temperature drift, and cutter behavior, enabling data-driven process parameter changes across multiple plant locations.

---

## 🎯 Business Problem
The Fischer Cutter was experiencing frequent unplanned stoppages and product rejections — leading to significant downtime and quality issues.

**Key pain points included:**
- Unexplained sequence missing faults disrupting the cut–park–splice cycle
- Change Over Plate jams, particularly with certain compound types — closely linked to Gum Edge issues originating from the RH Calender
- Splice sensor failures caused by dust, timing mismatches, or calibration drift
- Roll temperature fluctuations in the RH Calender (especially the bottom roll)
- Feeding method inconsistencies causing material uncoat and gripper jams
- HMI and PLC logic delays, especially during manual override attempts

**Goals:**
- Understand recurring fault root causes
- Link breakdowns to shifts, machine conditions, and materials
- Implement engineering and control-based solutions
- Build a Power BI dashboard to support decision-making

---

## 📊 Data Description
All data used in this analysis was collected from real field operations and cross-verified through engineering review. The data sources included:

- Shift engineer logs
- PLC/HMI tag logs
- Root Cause Analysis reports
- RH Calender roll temperature logs
- Compound test reports (T5, T35, Mooney viscosity, reclaim %, batch origin)

**Each record includes:**
- Date & Shift
- Machine ID
- Fault Type & Duration
- Compound properties
- Operator or engineering notes

The hybrid dataset enabled both trend-based and engineering-logic-based insights.

---

## 📈 Power BI Dashboard Structure

The dashboard is organized into eight interactive pages, each designed to reflect the RCA thought process, cross-machine dependencies, and engineering observations:

### 🔹 Page 1: Shift-Level Fault Distribution
- Histogram, density plot, Pareto
- Shift vs faults vs delay breakdown
- KPI Cards

### 🔹 Page 2: Root Cause Classification (4M+P)
- Man, Machine, Material, Method, Production classification
- Filters and stacked visuals by fault impact

### 🔹 Page 3: Issue-Specific Deep Dives
- Study of top recurring faults (Change Over Plate, Gum Edge, etc.)
- RCA trees and filters

### 🔹 Page 4: RH Calender Study (Upstream Machine)
- Roll temperature vs fault trends
- Crossroll cooling, RH3 bottom roll behavior

### 🔹 Page 5: Compound Behavior Study
- T5, T35, Mooney, Reclaim % impact on faults
- Compound vs jam or stretch issues

### 🔹 Page 6: Cross-Plant Observations
- Learnings from other plant sites
- Field notes, changes made, image documentation

### 🔹 Page 7: Post-Intervention Performance Review
- Before vs After trendline
- Fault reduction KPIs

### 🔹 Page 8: New Machine Modifications & OEM Feedback
- Design changes recommended
- What OEM implemented in the next-gen machines

---

## 💡 Key Insights & Impact
(Will be added after dashboard is built)

---

## 🧰 Tools & Skills Used

This project demonstrates the intersection of real-world engineering, data-driven analysis, and RCA implementation across a high-speed tire manufacturing process.

**Tools & Technologies:**
- Power BI (DAX, KPIs, custom visuals)
- MS Excel (data cleaning, log structuring)
- PLC programming and tag monitoring
- Sensor integration and signal tracing
- Markdown for documentation

**Analytical & Operational Skills:**
- Root Cause Analysis (RCA), Fishbone, Pareto
- Signal logic diagnosis (sequence errors, sensor faults)
- Operator training and SOP creation
- Mechanical and control-based corrective action planning
- End-to-end process improvement from data to intervention

**Domain Knowledge:**
- Electrical & Process Engineering
- Tire Manufacturing (RH Calender → Fischer Cutter)
- Compound material behavior
- Multi-plant commissioning and field trials

---

## 👤 About Me

**Asif Noushad Sharafudeen**  
Process Engineer | Data Scientist | Industrial Problem Solver  
Electrical Engineering graduate with strong industrial automation experience and a passion for data-driven process improvement.

- Delivered multiple machine and process optimizations using field data and engineering insight  
- Experienced in programming and modifying PLC/HMI logic to reduce downtime  
- Led machine erection and commissioning in new plants  
- Collaborated with OEMs to improve machine design via structured RCA  
- Currently transitioning into advanced analytics and industrial data science to drive smarter, scalable improvements

🔗 [LinkedIn](https://www.linkedin.com/in/asifnoushad/)  
🔗 [GitHub](https://github.com/asifnoushadsharafudeen)

---

## 📂 Folder Structure

fischer-cutter-rca-powerbi/
│
├── data/ # Fault logs, compound test sheets (anonymized)
├── dashboards/ # Power BI .pbix files or screenshots
├── docs/ # Supporting PDFs, diagrams, RCA notes
├── README.md # Project overview and documentation

---
