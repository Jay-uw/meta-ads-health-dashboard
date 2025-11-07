# 🧭 Marketing Health Dashboard
![Version](https://img.shields.io/badge/version-v2.1.1-purple)
![Status](https://img.shields.io/badge/status-active-brightgreen)
![Platform](https://img.shields.io/badge/platform-web%20dashboard-yellow)
![Meta Ads](https://img.shields.io/badge/data-Meta%20Ads-blue)
![TikTok](https://img.shields.io/badge/data-TikTok-pink)
### ✅ Current Version: **v2.1.1**


The **Marketing Health Dashboard** is an all-in-one performance diagnostic web tool designed to evaluate and visualize the health of your **digital marketing performance** across multiple platforms, including **Meta Ads** (Facebook & Instagram) and **TikTok Posts**.

It provides a unified and data-driven overview of your campaigns and content health through interactive visual reports, smart summaries, and automatic health scoring systems tailored for each platform.

---

## 🚀 Key Features

### 🩺 Multi-Platform Performance Insights
Get detailed diagnostics for both:
- Meta Ads (Campaigns, Ad Sets, and Ads)
- TikTok Posts

Each platform has its own scoring logic, data parameters, and visual summaries to help you easily identify strengths and areas that need improvement.

---

### 📊 Dual Parameter Dashboard
The sidebar includes two distinct parameter panels:

**Meta Ads Parameters (Updated Universal Metrics)**
- Cost per Messaging Conversation  
- New Messaging Contacts  
- Impressions  
- Reach  

**TikTok Parameters**
- Engagement Rate  
- Watch Time %  
- Completion Rate  
- Retention Rate  

Each set of metrics contributes to its own independent and platform-specific health score system.

---

### 📈 Smart Health Scoring

The system automatically calculates and displays a **Health Score** for each platform based on optimized, goal-driven weighting systems.

**Meta Ads Health Score (Updated System):**
- 40 percent weight: New Messaging Contacts  
- 40 percent weight: Cost per Messaging Conversation  
- 10 percent weight: Impressions  
- 10 percent weight: Reach  

Includes **dynamic weight redistribution** if certain metrics are missing.  
Example: old Engagement campaigns without messaging data still score fairly out of 100.

**TikTok Health Score:**
Uses a **dynamic weighting engine** based on your custom parameter values.  
No fixed weights, completely adaptive to user priorities.

---

### 🎨 Color-Coded Performance
All key metrics now display **color indicators** from **green (Excellent)** to **red (Urgent)** for instant clarity.

---

### 📤 Easy Data Upload
Upload `.xlsx` files directly from:
- Meta Ads Manager  
- TikTok Analytics  

The system automatically detects the correct structure and processes the data.

---

### 💡 Actionable Insights
- Identify underperforming assets fast  
- View average performance and problem items  
- Status tags:
  - ✅ Excellent  
  - 🟢 Good  
  - 🟠 Review  
  - 🔴 Urgent  

---

### 🔗 Interactive Features
- Clickable TikTok video links  
- Flexible column detection regardless of formatting differences  

---

## 🎯 Who It Is For
Ideal for:
- Advertisers and social media managers  
- Data analysts and automation pros  
- Agencies handling Meta and TikTok performance  

---

## 🧩 Tech Overview
- JavaScript, HTML, CSS  
- `.xlsx` processing  
- Modular scoring logic for each platform  
- Fully browser-based and responsive  

---

<details>
  <summary><strong>🗓️ Updates Log</strong></summary>

### 🗓️ November 7, 2025 - Meta Ads Scoring System Upgrade
A major update has been implemented to unify scoring across **Engagement** and **Lead Generation** campaigns.

**New Universal Metrics Added:**
- Cost per Messaging Conversation  
- New Messaging Contacts  
- Impressions  
- Reach  

**New Weighting Structure:**
- 40 percent: Cost per Messaging Conversation  
- 40 percent: New Messaging Contacts  
- 10 percent: Reach  
- 10 percent: Impressions  

**Dynamic Intelligent Weighting:**  
If a metric is missing (for example older Engagement campaigns with no New Messaging Contacts), its weight is redistributed across the existing metrics so all campaigns still score fairly out of 100.

**Updated Tables:**  
Campaigns, Ad Sets, and Ads tables now include these universal metrics with color-coded results.

**Balanced Scoring Logic:**  
All scores now cap at 100, even if results exceed 200 percent, eliminating inflated performance and ensuring strict accuracy.

---

### 🗓️ November 1, 2025 — TikTok Integration & Dynamic Scoring Update
- Added full TikTok support alongside Meta Ads.  
- Now you can measure the health of each TikTok post with its own scoring system.  
- Introduced a unified sidebar separating Meta and TikTok parameters.  
- Added a new upload button for TikTok data files.  
- Created summary cards for total posts, average engagement, and posts requiring action.  
- Improved date and percentage formatting for TikTok data.  
- Made the “Video Link” column clickable for easy access to TikTok posts.  
- Fixed “Header not found” error. The system now detects headers regardless of case sensitivity or extra spaces.  
- Replaced fixed 25 percent TikTok metric weights with a dynamic weighting system that adapts to your custom parameter values.  
- Added color-coded cell highlighting for all major performance metrics, helping visualize strengths and weaknesses instantly.

</details>
