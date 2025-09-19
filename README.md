# Agoda Instagram Data Analysis  

This project explores **Instagram performance of Agoda** by analyzing scraped post and follower data. The workflow is done in **R** using data wrangling, language detection, and integration with **Google Sheets** for reporting.  

The repository contains:  
- 📂 **RMarkdown Code** → Data cleaning, transformation, and analysis.  
- 📊 **Presentation Deck** → Key findings and insights for storytelling.  
- 📑 **Datasets** → [Link to Drive/Cloud Storage] (since large data files are stored externally).  

---

## 🔍 Project Overview  
The goal of this project is to:  
1. Scrape Instagram **posts and follower data** for Agoda.  
2. Clean and transform the data (timezones, engagement metrics, language detection).  
3. Differentiate **Agoda Global** vs **Agoda Indonesia** posts.  
4. Track **follower growth** across accounts.  
5. Export the processed dataset into **Google Sheets** for easy sharing and dashboarding.  

---

## 🛠️ Tools & Libraries  
- **R**: `dplyr`, `tidyverse`, `lubridate`, `cld3`, `readxl`, `googlesheets4`  
- **Google Sheets API**: For exporting cleaned datasets  
- **Presentation Deck**: Summarizes insights and business implications  

---

## 📂 Repository Structure  

├── code/
│   └── agoda_instagram_analysis.Rmd   # Main RMarkdown file
├── deck/
│   └── agoda_instagram_analysis.pdf   # Presentation slides
├── data/ (not included here)
│   └── agoda - Instagram - Analysis
└── README.md


---

## 📊 Data Sources  
- **IG Follower Scraping.xlsx** → Daily follower count from multiple Agoda accounts  
- **IG Post Scraping.xlsx** → Post-level data including captions, likes, comments, and posting time  

---

## 🚀 How to Run  

1. Clone this repository
2. Open agoda_instagram_analysis.Rmd in RStudio.
3. Install the required packages: "dplyr", "tidyverse", "lubridate", "cld3", "readxl", "googlesheets4"
4. Authenticate your Google Sheets API
5. Knit the RMarkdown file to generate results.

## 📈 Key Features  

- Cleans **timezones** and creates new date features.  
- Detects **caption language** and re-labels posts correctly.  
- Splits posts into **Agoda Global vs Agoda Indonesia**.  
- Calculates **engagement** (`likes + comments`).  
- Exports cleaned datasets to **Google Sheets**.  

---

## 📑 Presentation Deck  

The deck highlights:  
- Language distribution of posts  
- Follower growth trends in 2022  
- Comparison of engagement between Agoda Global & Agoda Indonesia  

You can view the slides here:  
👉 [Deck Link](https://drive.google.com/file/d/1NwJ-sF_evclOUrO1wYWBl_x8qChNTmo1/view?usp=sharing)  
