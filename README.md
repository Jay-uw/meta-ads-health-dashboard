# 🧭 Marketing Health Dashboard

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

**Meta Ads Parameters**
- Cost per Result  
- Results  

**TikTok Parameters**
- Engagement Rate  
- Watch Time %  
- Completion Rate  
- Retention Rate  

Each set of metrics contributes to its own independent health score system.

---

### 📈 Smart Health Scoring
The system automatically calculates and displays a **Health Score** for each platform:

**Meta Ads Health Score:**  
Based on Cost per Result (60%) and Results (40%).

**TikTok Health Score:**  
Uses a new **dynamic weighting system**.  
Instead of fixed weights, each metric’s importance is determined by the parameter values you set.

**How it works:**  
1. The system adds the values of your four TikTok parameters (for example: 8 + 60 + 40 + 70 = 178).  
2. Each metric’s weight = (Parameter Value) ÷ (Sum of All Parameters).  
3. Example with the defaults:  
   - Retention @ 3s (70): ~39% of total weight (most important)  
   - Avg. Watch Time (60): ~34%  
   - Completion Rate (40): ~22%  
   - Engagement Rate (8): ~5%  

This makes the TikTok Health Score far more accurate, automatically prioritizing the metrics that matter most to your goals.

---

### 🎨 Color-Coded Performance
All key metrics (Cost/Result, Results, Engagement Rate, Watch Time %, etc.) now display **color indicators**.  
Values change from **green (Excellent)** to **red (Urgent)** based on how well they perform compared to your defined parameters.  
This gives you an instant visual understanding of what’s working and what needs optimization.

---

### 📤 Easy Data Upload
Upload `.xlsx` files directly from:
- Meta Ads Manager for ad data  
- TikTok Analytics for post data  

The system automatically detects the file type and processes the correct metrics and visualizations.

---

### 💡 Actionable Insights
- Identify underperforming ads or posts at a glance.  
- Review total posts, average engagement, and elements requiring immediate action.  
- Use visual tags to quickly assess status:
  - ✅ Excellent  
  - 🟢 Good  
  - 🟠 Review  
  - 🔴 Urgent  

---

### 🔗 Interactive Features
- The “Video Link” column in the TikTok section is now clickable and opens in a new tab.  
- Headers such as “Ad Name” or “Results” are now detected regardless of uppercase, lowercase, or spacing differences. The dashboard automatically finds the correct columns even if the file has variations in naming.

---

## 🎯 Who It’s For
This dashboard is ideal for:
- Digital advertisers and social media managers  
- Marketing analysts and automation teams  
- Agencies managing both Meta and TikTok campaigns  

Whether auditing past performance or optimizing live campaigns, the **Marketing Health Dashboard** helps you make faster and smarter data-driven decisions.

---

## 🧩 Tech Overview
- Built using JavaScript, HTML, and CSS.  
- Reads Excel data via `.xlsx` upload.  
- Includes separate logic for Meta and TikTok analysis.  
- Fully responsive and browser-based.  

---

<details>
  <summary><strong>🗓️ Updates Log</strong></summary>

### 🗓️ November 1, 2025 — TikTok Integration & Dynamic Scoring Update
- Added full TikTok support alongside Meta Ads.  
- Now you can measure the health of each TikTok post with its own scoring system.  
- Introduced a unified sidebar separating Meta and TikTok parameters.  
- Added a new upload button for TikTok data files.  
- Created summary cards for total posts, average engagement, and posts requiring action.  
- Improved date and percentage formatting for TikTok data.  
- Made the “Video Link” column clickable for easy access to TikTok posts.  
- Fixed “Header not found” error. The system now detects headers regardless of case sensitivity or extra spaces.  
- Replaced fixed 25% TikTok metric weights with a dynamic weighting system that adapts to your custom parameter values.  
- Added color-coded cell highlighting for all major performance metrics, helping visualize strengths and weaknesses instantly.

</details>
