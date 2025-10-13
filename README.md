<div align="center">

# 📊 Amazon Prime Video | Content Strategy Dashboard

**A comprehensive Power BI dashboard analyzing over 12,000 titles to uncover trends in content production, genre evolution, and global distribution.**

</div>

---

### 🎯 **Business Objective**

In the competitive streaming market, understanding the landscape of content is crucial for making strategic acquisition and production decisions. This project aims to answer key business questions for Amazon Prime Video's content strategy team:
- Which countries are the dominant players in content production?
- How have genre preferences evolved over the last century?
- Is there a relationship between the volume of content produced and its average user rating over time?

---

### 🛠️ **Tech Stack & Tools**

| Technology | Purpose |
| :--- | :--- |
| **Power BI** | The core tool for data modeling, analysis, and creating the interactive dashboard. |
| **DAX** | Used for creating custom calculations, measures, and KPIs within Power BI. |
| **Power Query** | For data extraction, transformation, and loading (ETL) processes to clean and shape the raw data. |

---

### 📂 **Dataset Overview**

The analysis is built on two primary datasets, providing a comprehensive view of the Amazon Prime Video catalog:
- **`titles.csv`**: Contains metadata for over 12,000 unique movies and TV shows, including release year, genre, and IMDb scores.
- **`credits.csv`**: Includes detailed cast and crew information for each title.

These datasets were merged and modeled in Power BI to create a unified source for the dashboard.

---

### 🎨 **Dashboard Showcase & Key Insights**

The interactive dashboard provides a multi-faceted view of the Prime Video catalog. The following snapshots highlight the most critical insights derived from the analysis.

#### **Insight 1: The United States Dominates Global Content Production**
The data clearly shows that the United States is the largest producer of content available on the platform, followed by India and the United Kingdom. This highlights the importance of the US market for both production and acquisition.
<br>
<div align="center">

<img width="604" height="358" alt="line_Countries_Titles" src="https://github.com/user-attachments/assets/45048554-b92f-47f8-93df-fa9413af304e" />

<br>
A line chart showing the total count of titles produced by the top 7 countries.
</div>
<br>

#### **Insight 2: "Drama" Has Been the Most Consistent and Popular Genre for a Century**
While other genres have risen and fallen in popularity, Drama has consistently remained a dominant category since the 1920s. This suggests it is a cornerstone of any content library.
<br>
<div align="center">

<img width="898" height="498" alt="stacked_Decades_Titles" src="https://github.com/user-attachments/assets/30a5af6f-c737-4060-a35f-b5903a4b5432" />

<br>
A 100% stacked area chart showing the proportional popularity of major genres over time.
</div>
<br>

#### **Insight 3: The Peak of Average Content Quality Occurred in the 2000s**
An interesting trend emerges when comparing the volume of content with its average IMDb rating. The average rating peaked at **6.20 in the 2000s**, even as the number of titles released per decade has continued to explode. This suggests that a higher quantity of content does not necessarily correlate with higher average quality.
<br>
<div align="center">

<img width="643" height="428" alt="combo_Titles_Rating" src="https://github.com/user-attachments/assets/35afb89c-7311-4dba-8d7d-c19674d6bd46" />

<br>
A combo chart comparing the count of titles released with the average IMDb score by decade.
</div>
<br>

---

### 🚀 **Business Impact & Conclusion**

This Power BI dashboard transforms a complex dataset into a strategic decision-making tool. The key takeaways for Amazon's content strategy team are:
- **Focus on Core Markets:** The US, India, and the UK are the primary sources of content and should be the focus of acquisition efforts.
- **Invest in Evergreen Genres:** Drama is a perennially popular genre that should form a core part of the content library.
- **Balance Quantity with Quality:** As content production accelerates, it is crucial to monitor quality metrics (like IMDb scores) to ensure the catalog remains compelling for subscribers.

---

### 🔧 **How to View This Project**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/k-rajashekar/AmazonPrimeTV-EDA-Project.git
   cd AmazonPrimeTV-EDA-Project
   ```
2. **Open the Power BI file:**
   - The main interactive dashboard can be explored by opening the `Amazon_Prime_Analysis.pbix` file in Power BI Desktop.
3. **View a Static Version:**
   - For a quick preview without Power BI, you can view the `M4_AmazonProject_PDF.pdf` file included in the repository.

