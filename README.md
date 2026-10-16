# Project Northstar – Business Analysis Portfolio Project

A self-directed portfolio project simulating the Business Analyst role on a council
system replacement: a legacy Access database and spreadsheets replaced by a cloud-based
asset and work order management system, integrated with finance and GIS.

The council, stakeholders and workshop are fictional. The data analysis uses a real
open dataset: City of Melbourne "Street lights with emitted lux level" (106,037 records, CC BY).

## What I did
- Documented requirements, decisions, actions and a RAID log from a simulated stakeholder workshop
- Mapped current and future state processes (swimlane diagrams) and completed a gap analysis
- Wrote 23 user stories with acceptance criteria and MoSCoW priorities, managed in Jira across 6 epics
- Profiled 106,037 legacy records and built a source-to-target data mapping
- Specified a finance integration with error handling, and reporting requirements
- Wrote UAT scenarios, a defect log and a requirements traceability matrix

## Key finding
The legacy data had no suburb field, so a planned "work orders by suburb" report could not be
delivered without GIS data. This was raised in the RAID log and traced through to a blocked test.

## Tools
Jira, Confluence, Confluence Whiteboards, Microsoft Excel

📄 **[View the full portfolio (PDF)](Keerthi_Kuchipudi_Project_Northstar_BA_Portfolio.pdf)**
