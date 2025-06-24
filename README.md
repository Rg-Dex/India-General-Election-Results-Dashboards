#India General Election Results 2024 Analysis

**📊 Power BI Project | Data Modeling | DAX | Drill-through | Data Storytelling**

A comprehensive Power BI project visualizing and analyzing the 2024 Lok Sabha election results across 543 constituencies. The project features **6 interactive dashboards**, built on a well-structured **star/hybrid schema**, leveraging advanced **Power BI functionality** including DAX, Power Query, drill-throughs, bookmarks, and dynamic filtering.

---

## 📁 Project Highlights

* 🔗 **Data Source**: Public dataset based on 2024 Indian General Election results
* 🧠 **Tools Used**: Power BI, DAX, Power Query (M), SQL
* 🏗 **Data Model**: Star/Hybrid schema with fact and dimension tables
* ⚙️ **Features**: Drill-throughs, tooltips, bookmarks, dynamic slicers, interactive maps, exportable tables

---

## 📌 Dashboards Overview

### 1. 🧭 Overview Analysis

* Displays total seats won by major alliances (NDA, INDIA, Others) across all 543 constituencies
* Includes drill-through ("ℹ️ button") to a detailed candidate-level table showing:

  * Constituency, winning candidate, party, alliance, total votes, and margin
* Allows filtering and drill-down based on selected alliance or party

---

### 2. 🗺 State Demographic Analysis

* Features 3 interactive map visuals:

  * **State-wise map** with tooltips showing total seats, NDA/INDIA seat share
  * **Constituency map** with winning candidate & party
  * **Bubble map** color-coded by alliance:

    * 🟧 NDA (Saffron)
    * 🔵 INDIA (Blue)
    * ⚫ Others (Black)
* All maps support drill-through to the candidate grid and respond dynamically to user interaction

---

### 3. 🧩 Political Landscape by State

* A state slicer allows users to view detailed analytics for any selected state
* Visuals include:

  * Party-wise results table
  * Donut chart showing % seat share
  * Highlighted state map
  * Total seats and breakdown by NDA, INDIA, and Others

---

### 4. 🏛 Constituency Analysis

* Fully dynamic dashboard driven by a constituency slicer
* Displays for the selected constituency:

  * Total votes cast
  * EVM votes, Postal votes
  * Total candidates
  * Winning, runner-up, and second runner-up candidates with:

    * Name, state, party, vote count, vote share %
* Built using **advanced DAX** & **Power Query** logic (IF statements, calculated columns, conditional logic)

---

### 5. 📋 Details Grid Dashboard

* Master data table showing all 543 constituencies
* Includes fields like:

  * Winning candidate, runner-up, margin, party, alliance, vote counts
* Supports both "show entire data" view and filtered drill-throughs from other dashboards
* Seamlessly integrates with other dashboards via bookmarks & filters

---

### 6. 🏠 Landing Page

* Serves as the homepage and navigation hub for the entire report
* Provides buttons linking to each dashboard
* Enables users to return from any dashboard to the landing page via a **Home button**
* Built using Power BI **bookmarks** for a smooth UX flow

---

## 🎯 Key Features

* ✅ Advanced Data Modeling using Star/Hybrid Schema
* ✅ Drill-through functionality from every dashboard
* ✅ Dynamic filters, slicers, tooltips, and buttons
* ✅ Responsive and exportable visuals
* ✅ End-to-end storytelling through data

---

## 📌 Skills Demonstrated

* Data Modeling
* DAX & Power Query (M)
* Interactive Visualizations
* KPI & Insight Generation
* Dashboard Design & UX
* Stakeholder-ready Reporting
