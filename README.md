# 🎓 University Project Activity Tracker (UPAT) Database System

## 🌟 Project Overview

This repository documents the complete lifecycle of designing and developing the **University Project Activity Tracker (UPAT)**, a robust database application. UPAT is designed to assist a university administration in efficiently tracking and managing project activities, associated funding, and faculty involvement across various academic departments.

This project encompassed the full spectrum of database development, from initial business analysis and conceptual modeling to physical implementation and **advanced data visualization**.

> **🏆 Final Project for Data Visualization Course: Scored 10/10**

## 📊 Data Visualization & Analysis

The capstone of this project involved turning complex relational data into insightful, actionable visualizations. We used a powerful combination of tools and libraries to create both static and interactive dashboards.

| Feature | Tools Used | Description |
| :--- | :--- | :--- |
| **Business Intelligence** | **Tableau** | Developed interactive dashboards to visualize project funding distribution, departmental participation rates, activity timelines, and faculty workload. |
| **Statistical Visualizations** | **Python (Seaborn)** | Created detailed, aesthetically pleasing statistical plots (e.g., heatmaps, box plots, time-series analysis) for deep-dive analysis into project and fund balance trends. |
| **Interactive Grammar of Graphics** | **Python (Altair)** | Built highly interactive, declarative visualizations that allow users to explore relationships between entities (e.g., Sponsor-to-Fund relationships, Faculty-to-Project contribution). |

## 💡 Key Database Design Highlights

The database was meticulously designed to handle the complex relationships inherent in academic project management. The core entities and their relationships are captured in the provided Entity-Relationship (E-R) Diagram.

### Entity-Relationship (E-R) Model

The conceptual model defines the key entities and their strong, weak, and associative relationships:

  * **DEPARTMENT:** Tracks departmental information and location details.
  * **FACULTY:** Stores faculty personnel details (employs relationship with DEPARTMENT).
  * **PROJECT:** The core entity representing research or institutional projects.
  * **ACTIVITY:** Details specific, date-bound tasks or phases within a PROJECT.
  * **FUND:** Manages financial allocations and balances, linked to PROJECTs (fund relationship).
  * **SPONSOR:** Tracks external and internal sponsors who contribute funds.

### Relational Schema & Implementation

The E-R model was translated into a normalized relational schema, ensuring data integrity and minimal redundancy. This involved:

1.  **Normalization:** Achieving at least **3rd Normal Form (3NF)** to ensure structural integrity.
2.  **Schema Definition:** Creating the tables, defining primary and foreign keys, and implementing referential integrity constraints.
3.  **Physical Implementation:** Executing the Data Definition Language (DDL) and populating the system with sample data for testing and visualization.

## 🛠️ Technology Stack

| Component | Technology | Role |
| :--- | :--- | :--- |
| **Modeling** | Lucidchart / MySQL Workbench | E-R Diagram, Relational Schema Design |
| **Data Analysis** | **Python** (Pandas, NumPy) | Data cleaning, transformation, and preparation for visualization |
| **Visualization** | **Tableau** | Professional BI Dashboarding |
| **Visualization** | **Python (Seaborn, Altair)** | Advanced statistical and interactive plotting |
| **Database** | SQL / Relational Database System (e.g., MySQL, PostgreSQL) | Database implementation and querying |

## 🚀 Getting Started

To explore the project:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/thesjhu/university-project-activities-database-application
    ```
2.  **Database:** Review the `university-project-activities-database.accdb` file to see the schema definition.
3.  **Visualization:** Explore the Jupyter Notebooks in the `visualization` folder for the Seaborn and Altair code, and the `tableau` folder for the Tableau workbook files.
