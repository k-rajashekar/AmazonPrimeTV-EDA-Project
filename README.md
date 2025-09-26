# Amazon Prime Movies & Shows – Power BI Dashboard

## 📊 Project Overview

This project explores the **Amazon Prime Video catalog** using interactive Power BI dashboards.
It provides a complete view of how titles have evolved over the decades—covering genres, IMDb scores, release trends, and geographic distribution—so users can quickly identify patterns in global entertainment.

## 📂 Repository Contents

| File/Folder                  | Description                                                      |
| ---------------------------- | ---------------------------------------------------------------- |
| `Amazon_Prime_Analysis.pbix` | Main Power BI Desktop file containing all dashboards             |
| `datasets/`                  | Public datasets used for the analysis (included for easy access) |
| `M4_AmazonProject_PDF.pdf`   | Static PDF export of the dashboard for quick preview             |

The datasets include:

* **titles.csv** – Metadata for each title (id, title, type, description, release year, genres, IMDb/ TMDB scores, etc.).
* **credits.csv** – Cast and crew details (person id, role, character, etc.).

Both datasets are publicly available and bundled here so the report can be refreshed without external downloads.

## 🚀 Dashboard Walkthrough

The Power BI report is organized into several interactive pages:

1. **Genre Trends Over Decades**

   * Visualizes how different genres emerged or declined from the 1920s to 2020s.
   * Highlights the *number of titles* released per decade and the evolution of unique genres.

2. **Global Distribution**

   * Maps the count of titles produced by country.
   * Allows filtering by genre or decade to see regional production strengths.

3. **Ratings & Popularity**

   * Shows average IMDb ratings and votes by genre.
   * Compares the count of releases with their average IMDb score across decades.

4. **Key Influencers**

   * Identifies segments where IMDb scores are higher or lower than average.
   * Helps spot patterns such as genres or regions with higher audience approval.

Each page supports slicers and filters for deep exploration.

## 🔑 Key Insights

A few notable findings from the analysis:

* **Drama** consistently emerges as the most dominant genre across decades.
* Average IMDb ratings peaked during the **2000s** (~6.2) and have remained steady since.
* **Titanic** received the highest IMDb vote count, while **Couple of Mirrors** achieved the highest average rating in the dataset.
* The **United States** leads in total title production, followed by India, the United Kingdom, and Canada.

## 🔏 How to Use

1. Download or clone this repository.
2. Open `Amazon_Prime_Analysis.pbix` in **Power BI Desktop**.
3. Interact with slicers, hover over visuals, and drill through pages to explore the data.

   * The included `datasets/` folder is already connected; refresh is optional.

## ⚡ Quick Preview

For a snapshot of the visuals without opening Power BI, view **M4_AmazonProject_PDF.pdf** in this repo.
