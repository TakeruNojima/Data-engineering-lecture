# Analisis Pengaruh Jam Kerja (Work-Life Balance) terhadap Indeks Kebahagiaan di Eropa
**Created By:** Team 9  
**Date:** February 12, 2025  
**Version:** 1.0  

---

# Executive Summary

## Project Overview
**Tujuan Project:**  
Menganalisis apakah terdapat korelasi langsung antara rata-rata jam kerja mingguan penduduk suatu negara dengan skor indeks kebahagiaan (*World Happiness Report*) di kawasan Eropa.

**Scope Project:**  
Mengintegrasikan data jam kerja dari Eurostat, metrik kebahagiaan dari Kaggle, dan data kesehatan mental dari WHO untuk sekitar **45 negara Eropa pada tahun 2024**.

**Expected Outcomes:**
- Laporan analitik sosial-kesehatan  
- Pemetaan klaster negara Eropa berdasarkan gaya hidup  
- Model regresi untuk memprediksi tingkat kebahagiaan  

**Timeline:**  
3 Bulan

---

# Stakeholders

**Project Owner:**  
Kementerian Ketenagakerjaan

**Team Members:**
- **Data Engineer:** Dzakwan Daris  
- **Data Analyst:** Takeru Putra  
- **Project Manager:** Dea Riftya  

**End Users:**
- Pembuat kebijakan publik  
- Peneliti SDM (HR)  
- Jurnalis sosial  

---

# Data Source Analysis

## 2.1 Dataset WHR (World Happiness Report)

### Source Details
- **Dataset Name:** WHR  
- **URL / Access Point:**  
  https://www.worldhappiness.report/data-sharing/  
- **Data Owner:** WHR  
- **Update Frequency:** Annually  

### Data Analysis
- **Format Data:** CSV / Excel (XLSX)  
- **Volume Data:**  
  Full: 100–300MB  
  Data yang digunakan: sekitar **1–3MB**  
- **Time Coverage:** 2015 – 2019  

### Data Quality
**Completeness**
- Germany: 100%  
- France: 100%  
- Denmark: 100%  

**Accuracy:** High (verified by WHR)  
**Consistency:** Moderate  
**Timeliness:** Good timeliness  
**Authentication Method:** None (Public Access / Open Access)

### Data
**Live Evaluation**

Denmark:

![Denmark data](images/Screenshot%202026-03-05%20132139.png)

France:

![France data](images/Screenshot%202026-03-05%20132156.png)


Denmark:

![German Data](images/Screenshot%202026-03-05%20132210.png)

---

## 2.2 Dataset WHR (World Happiness Report)

### Source Details
- **Dataset Name:** WHR  
- **URL / Access Point:**  
  https://www.kaggle.com/datasets/unsdsn/world-happiness  
- **Data Owner:** Not specified  
- **Update Frequency:** Not specified  

### Data Analysis
- **Format Data:** CSV  
- **Volume Data:** Full: 80.86 KB  
- **Time Coverage:** 2015 – 2019  

### Data Quality
**Completeness**
- Germany: 100%  
- France: 100%  
- Denmark: 100%  

**Accuracy:** High (verified by OECD)  
**Consistency:** Moderate  
**Timeliness:** Good timeliness  
**Authentication Method:** None (Public Access / Open Access)

---

## 2.3 OECD Data Explorer (Organisation for Economic Co-operation and Development)

### Source Details
- **Dataset Name:** WHR  
- **URL / Access Point:**  
  https://www.kaggle.com/datasets/unsdsn/world-happiness  
- **Data Owner:** OECD  
- **Update Frequency:** Not specified  

### Data Analysis
- **Format Data:** CSV  
- **Volume Data:**  
  Full: 510MB  
  Filtered: ~1.5MB  
- **Time Coverage:** 2015 – 2019  

### Data Quality
**Completeness**
- Germany: 100%  
- France: 100%  
- Denmark: 100%  

**Accuracy:** High (verified by OECD)  
**Consistency:** Moderate  
**Timeliness:** Good timeliness  
**Authentication Method:** None (Public Access / Open Access)