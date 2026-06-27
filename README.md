# 25Live → Coursedog Legacy Data Migration

## Historical Scheduling Data Preservation Through Python Automation

### Project Overview

During Mercy University's migration from **25Live** to **Coursedog**, several historical scheduling records were not available through standard system reports. To support the transition, I developed a **Python-based data extraction solution** that automated the retrieval of historical scheduling information directly from the legacy system, preserving critical institutional records and ensuring operational continuity throughout the migration.

---

## Project Highlights

- Supported the migration from **25Live** to **Coursedog**
- Preserved historical scheduling records unavailable through standard reports
- Automated historical data extraction using Python and Selenium
- Reduced manual data collection during system migration
- Improved data quality through automated validation
- Supported institutional data continuity

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Automation |
| Selenium | Browser Automation |
| Chrome WebDriver | Legacy System Navigation |
| CSV | Data Export |
| Jupyter Notebook | Development Environment |

---

## Business Problem

Standard reporting within the legacy **25Live** scheduling system did not provide access to all historical scheduling information required during the migration to **Coursedog**. Without an alternative extraction process, valuable institutional scheduling history would have been unavailable after the retirement of the legacy platform.

---

## Solution

Developed a Python automation workflow using Selenium to navigate the legacy scheduling system, extract historical scheduling records, validate the collected information, and export structured datasets to support the migration process.

---

## Automation Workflow

```text
25Live
   ↓
Python Automation
   ↓
Selenium Navigation
   ↓
Historical Data Extraction
   ↓
Data Validation
   ↓
CSV Export
   ↓
Coursedog Migration
```

---

## Code Overview

The automation performs the following tasks:

- Authenticates into the legacy scheduling platform
- Navigates scheduling pages automatically
- Extracts historical scheduling records
- Validates extracted information
- Handles loading delays and exceptions
- Exports structured datasets for migration

---

## Results

- Preserved historical scheduling records
- Supported a successful migration to Coursedog
- Reduced manual extraction effort
- Improved consistency and reliability of migrated data
- Created a reusable automation framework for future migration projects

---

## Business Impact

By automating historical data extraction, the project ensured that critical scheduling information remained accessible after the migration from **25Live** to **Coursedog**, reducing operational risk while improving the efficiency and reliability of the system transition.

---

## Skills Demonstrated

- Python Development
- Selenium Automation
- Data Extraction
- Legacy System Migration
- Data Validation
- Process Automation
- Higher Education Operations
- Process Improvement

---

## Future Enhancements

- Database integration
- Automated audit logging
- Incremental data extraction
- User interface for non-technical users
- Migration progress dashboard

---

## Conclusion

This project demonstrates how Python automation can support enterprise system modernization by preserving historical institutional data that is not accessible through standard reporting tools. The solution helped ensure a smooth transition from **25Live** to **Coursedog** while maintaining valuable scheduling history for future operational and reporting needs.
