# Real Time Monitoring Report: Contact Centre on Microsoft Fabric

**Moving towards unmanned reporting: ask a Copilot Studio agent for insights or to change planned numbers in MS Fabric**

A contact-centre reporting solution covering data, insights and reporting, built on Microsoft Fabric, a Fabric Data Agent and Copilot Studio.

## Demo

https://github.com/YOUR-USERNAME/YOUR-REPO/raw/main/media/Forecast_Agent_Demo.mp4

> Tip: to get an inline player, edit this README on github.com and drag `media/Forecast_Agent_Demo.mp4` into the editor, then replace the link above with the URL GitHub generates.

![Service level performance](media/sl-performance.png)
![Interval table](media/interval-table.png)

## What I built

→ Created a Lakehouse and Warehouse
→ Uploaded the CSV files into a Fabric Lakehouse
→ Created Warehouse tables using SQL
→ Created Copy Jobs to move the data into the Warehouse
→ Built the Power BI semantic model
→ Created additional Date and Interval tables using DAX
→ Created relationships between the tables
→ Created DAX measures
→ Built the Power BI report/dashboard
→ Created a Fabric Data Agent (optimised the tables to feed only relevant data)
→ Created a Copilot Studio agent
→ Created stored procedures for writeback queries from the Copilot Studio agent
→ Synced the stored procedure changes to Warehouse tables
→ Created pipelines to refresh the SQL endpoints

## AI agents

- **Fabric Data Agent:** read-only, on top of the Warehouse tables and semantic model, answering questions by querying the data
- **Copilot Studio agent:** can edit planned numbers in the Warehouse tables

Tested end to end for data, insights and reporting. It can be scaled to update weekly and monthly numbers.

## Stack

Microsoft Fabric (Lakehouse, Warehouse, Pipelines) · T-SQL · Power BI (DAX) · Fabric Data Agent · Copilot Studio

*Built with synthetic data.*

## Portfolio site

`index.html` is my portfolio page (projects, skills, experience and an AI assistant). Hosted with GitHub Pages.
