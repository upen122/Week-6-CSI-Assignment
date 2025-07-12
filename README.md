# Azure Data Factory Integration Projects

This repository contains various advanced Azure Data Factory (ADF) pipelines demonstrating real-world integration use cases, automation, and data engineering best practices.

## 📌 Completed Tasks

### ✅ 1. Extract from Local Server using Self-hosted Integration Runtime (SHIR)
- Setup SHIR on-premises
- Connected to local SQL Server
- Loaded data into Azure SQL Database

### ✅ 2. Incremental Load Pipeline with Daily Trigger
- Implemented ID-based watermarking
- Pipeline runs daily using schedule trigger
- Only loads new/modified rows

### ✅ 3. Monthly Trigger on Last Saturday
- Custom pipeline trigger configured
- Automatically triggers on the last Saturday of each month

### ✅ 4. Retry Logic for Transient Errors
- Configured pipeline with wait and retry logic
- Improves resilience of data extraction

---

## ❌ Skipped Task (SFTP Extraction)
Due to environment limitations, the SFTP pipeline was skipped.

---

## 🧠 How to Use
- Navigate to each folder for JSON pipeline exports, screenshots, and step-by-step setup guide.
- Import pipelines into ADF using the "Manage hub" → "ARM Template" if required.

## 📷 Sample Screenshots
> See `screenshots/` folders in each task for detailed configuration and run output.

## 📅 Author
**Upen Singh**  
M.Tech Aspirant | Data Engineering Enthusiast | Jaipur, India
