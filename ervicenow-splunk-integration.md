# ServiceNow ↔ Splunk Integration (Lab Setup)

## 🔍 Overview
Completed end-to-end integration between ServiceNow and Splunk using the Splunk Add-on for ServiceNow in a standalone lab environment.

## ⚙️ Setup Details
- ServiceNow Developer Instance configured
- Dedicated integration account created (non-admin)
- Splunk Add-on for ServiceNow installed and configured
- Connection established between ServiceNow and Splunk

## 📥 Data Ingestion
- Incident data successfully ingested into Splunk
- Verified data indexing and field extraction

## 🧠 Key Learning
ServiceNow data ingestion in Splunk is **incremental** and driven by:

👉 `sys_updated_on` field

### This means:
- Historical incidents are **not ingested by default**
- Only newly created or updated incidents are pulled into Splunk

## 🔄 Validation
After updating an incident in ServiceNow:
- Data was immediately ingested into Splunk
- Confirmed that the integration and ingestion pipeline were working correctly

## 📚 Key Concepts Demonstrated
- Splunk Add-on configuration
- API-based data ingestion
- Authentication handling
- Incremental data ingestion logic
- ITSM workflow integration


## Splunk, ServiceNow, Integration, Add-on, ITSM, Data Ingestion, sys_updated_on
