# PT Toyota Boshoku Indonesia – Power BI Data Warehouse Project (Dual Role - DE & PM)

## Project Overview
This project was developed for **PT Toyota Boshoku Indonesia** to build a centralized **Power BI reporting system** supported by a structured **SQL Server Data Warehouse**.

The source data originated from **SAP**, where business requirements were translated into custom **ABAP programs** that generated `.txt` output files. These files were placed in a shared folder (**AL11**) and processed through **SSIS (SQL Server Integration Services)** into SQL Server for reporting and analytics.

I served in a dual role as **Data Engineer** and **Project Manager**, handling both the technical ETL delivery and overall project management from initiation to completion.

![Workflow](https://github.com/rinoyaohari/Data-Engineer---SSIS---Project-at-Toyota-Boshoku-Indonesia/blob/aa5c81cf9536d1cd38490d00fd1aaf4ffb3c6f2f/Workflow.jpg)

---

# Responsibilities

## Data Engineering Role

### Requirement Translation & Data Integration
- Gathered business reporting requirements from stakeholders
- Coordinated with ABAP Developers to build SAP extraction programs
- Ensured output `.txt` files matched reporting needs

### Source File Processing
- Retrieved generated files from SAP shared folder (**AL11**)
- Built SSIS packages to automate file ingestion
- Managed structured file-to-database loading process

### ETL Development (SSIS)
- Created ETL workflow including:
  - Process log start / end
  - TXT file ingestion
  - Data type conversion
  - Row count validation
  - Data load into SQL Server Data Warehouse

### Data Warehouse Development
- Loaded processed data into SQL Server reporting tables
- Structured data for Power BI dashboards and analytics
- Ensured data readiness for visualization layer

### Scheduling & Maintenance
- Configured daily automated jobs for SSIS execution
- Maintained shared folder operations and file availability
- Monitored recurring ETL process performance

---

## Project Manager Role

### Project Governance
- Managed project lifecycle from kickoff to go-live
- Maintained project timeline, milestones, and deliverables
- Coordinated communication between customer, developer team, and internal resources

### Reporting & Monitoring
- Delivered weekly project progress reports to customer and team
- Monitored risks, blockers, and delivery status
- Ensured successful completion aligned with schedule

---

# Technology Stack

| Technology | Purpose |
|---|---|
| SAP | Source ERP System |
| ABAP | Custom Data Extraction Program |
| AL11 Shared Folder | File Output Repository |
| SSIS | ETL Development |
| SQL Server | Data Warehouse |
| Power BI | Reporting & Dashboard |
| SQL | Data Processing |

---

# Project Workflow

---
