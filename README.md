**Global Video Games: Regional Sales & Critic Trends  **
This project is an interactive Executive Dashboard designed to analyze the global gaming landscape, focusing on regional sales performance, platform popularity, and the correlation between critic scores and market success.

**Data Source Information ** 
Dataset: https://mavenanalytics.io/data-playground/video-game-sales/VG_Chartz24 (Video Game Sales & Ratings).  
Volume: Comprehensive transactional records covering games from 1980 to 2015+.  
Scope: Global data including Region (NA, EU, JP, Others), Genre, Console/Platform, and Critic Scores.

**Project Overview  
Key Business Insights  **

- **Regional Insights:** Identified North America (NA Sales) as a primary revenue driver for top-tier titles like *Grand Theft Auto V*.  
- **Genre Popularity:** Visualized how "Action" and "Shooter" genres dominate the modern console eras (PS4, XOne).  
- **Historical Peaks:** Detected the 2010s as a peak decade for software sales before the shift in market dynamics.  

**Recommended Analysis (Answering Key Questions):**  
1. **Top-Selling Titles Worldwide:**  
   - Best-selling games globally identified via `Global_Sales`.  
   - Top performers include *Grand Theft Auto V*, *Wii Sports*, and *Minecraft*.  
   - Visualized with a bar chart of top 10 global titles.  

2. **Yearly Sales & Industry Growth:**  
   - Aggregated sales by `Year_of_Release` to identify trends.  
   - Peak sales occurred in the **2010s**, showing steady growth prior to market shifts.  

3. **Console Genre Specialization:**  
   - Analyzed sales by `Platform` and `Genre`.  
   - Observed patterns:  
     - **Nintendo (Wii, Switch):** Family & Platformer games  
     - **PlayStation:** Action & RPG  
     - **Xbox:** Shooter & Sports  

4. **Regional Popularity Discrepancies:**  
   - Compared regional sales (`NA_Sales`, `EU_Sales`, `JP_Sales`, etc.) per title.  
   - Titles with high regional disparity include:  
     - *Monster Hunter* → Strong in Japan, modest elsewhere  
     - *FIFA* series → Dominant in Europe, lower in Japan  

**🛠️ Technical Process (The Workflow)  **

**Data Preparation & ETL: ** 
- Cleaned and structured the VG_Chartz24 table to ensure consistency in regional naming.  
- Validated sales figures (e.g., NA Sales vs. Global Total) using Power Query.  

**Data Analysis Expressions (DAX):  **
- Developed measures for Total Sales, Regional Totals, and Average Metascore.  
- Created a Decade grouping for better long-term trend analysis.  

**Effective Visualization & UI/UX: ** 
- **Interactivity:** Configured Edit Interactions to allow Cards to filter the entire dashboard.  
- **Advanced Navigation:** Implemented a Pop-out Slicer Menu using Bookmarks and Selection Pane to maintain a clean, "Puno Na" yet organized layout.  
- **Hierarchy Slicers:** Combined Decade, Genre, and Console into a single drill-down slicer for deep-dive analysis.  

 **Design & Branding ** 
- **Color Palette:** Professional Slate Gray and White theme with high-contrast accents for Metascores.  
- **Finesse:** Optimized visual layering (Bring to Front/Back) to ensure interaction icons are accessible without cluttering the UI.

---

### 📸 Dashboard Screenshot

<img width="431" height="242" alt="Videogames Dashboard" src="https://github.com/user-attachments/assets/d9fbc518-f510-4ec9-a064-93cb8a86995f" />

---

### 📬 Contact Me
* **LinkedIn:** [Jemico Dalangin](https://www.linkedin.com/in/jemico-dalangin-955b60288)
* **Email:** jemico.dalangin@gmail.com
* **GitHub Portfolio:** [JCoquillaD](https://github.com/JCoquillaD)
