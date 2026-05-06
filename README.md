# 🎬 Prime Video Analytics Dashboard (Power BI)

> Turning raw streaming data into actionable insights 📊

---

## 🚀 Overview

This project is an **interactive Power BI dashboard** built to analyze and visualize content trends from a Prime Video dataset.  
It focuses on extracting meaningful insights about:

- 📺 Content distribution (Movies vs TV Shows)
- 🌍 Geographic availability
- 🎭 Genre dominance
- 📅 Release trends over time
- ⭐ Rating patterns across content types

The goal was simple:  
👉 Transform static data into **decision-ready intelligence**

---

## 🧠 Problem Statement

Streaming platforms host massive libraries of content, but:

- It's difficult to identify **content trends**
- Hard to compare **genres, ratings, and growth**
- No quick way to visualize **global distribution**

This dashboard solves that by providing a **centralized, visual analysis system**.

---

## 🛠️ Tools & Technologies

| Tool        | Purpose |
|------------|--------|
| **Power BI** | Data visualization & dashboard creation |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Calculated measures & KPIs |
| **Dataset** | Prime Video titles dataset |

---

## 📊 Key Features

### 🔹 1. KPI Cards (Top Section)
- Total Titles
- Total Countries
- Average Duration
- Top Genre

➡️ Gives **instant snapshot insights**

---

### 🔹 2. Global Content Distribution 🌍
- Map visualization of shows by country
- Helps identify:
  - Content-heavy regions
  - Market focus areas

---

### 🔹 3. Content Type Breakdown 🎥
- Donut chart comparing:
  - Movies vs TV Shows

➡️ Insight: Movies dominate (~60%)

---

### 🔹 4. Genre Exploration 🎭
- Interactive genre panel
- Shows:
  - Action
  - Comedy
  - Crime
  - Animation, etc.

➡️ Helps understand **audience preference trends**

---

### 🔹 5. Release Year Trends 📅
- Line/area chart of content over time
- Shows growth pattern

➡️ Key Observation:
- Peak around recent years → platform expansion

---

### 🔹 6. Rating Distribution ⭐
- Compares ratings like:
  - 13+
  - 16+
  - PG
  - R

➡️ Insight:
- Most content falls under **teen & general audience categories**

---

### 🔹 7. Genre vs Content Type 📊
- Bar chart comparing:
  - Movies vs TV shows across genres

➡️ Helps identify:
- Which genres dominate each format

---

## 📈 Data Processing Workflow

```text
Raw Dataset
   ↓
Data Cleaning (Power Query)
   ↓
Feature Engineering
   ↓
DAX Measures Creation
   ↓
Visualization Design
   ↓
Final Dashboard
