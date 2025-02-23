# Film Production Analysis for a New Movie Studio

Welcome to the repository for the Film Production Analysis project! This project uses exploratory data analysis (EDA) to generate actionable insights for a new movie studio. By combining film budget data with IMDb metadata, we help the studio decide which films to produce to maximize profitability and minimize financial risk.

---

## Project Overview

### Goal
The goal of this project is to explore the performance of films (released from 2000 onward) using data from multiple sources (Box Office Mojo, IMDb, Rotten Tomatoes, TheMovieDB, and The Numbers) and provide three concrete business recommendations for a new movie studio. Our analysis focuses on:
- **Global Gross Profit** – the difference between worldwide gross revenue and production budget.
- **Global Gross ROI** – an indicator of efficient budget utilization.
- **Trends and patterns** in film genres, runtime, and key personnel (directors and actors).

### Audience
The primary audience for this project is the head of the new movie studio and the company’s management team. They will use our insights to guide strategic decisions about which types of films to create.

### Datasets
This project makes use of:
- **Movie Budgets Data:** A compressed CSV file (`bom.movie_gross.csv.gz`) that includes production budgets, domestic and worldwide grosses, and release dates.
- **IMDb Data:** Extracted from a zipped SQLite database (`im.db.zip`), providing additional metadata (ratings, runtime, genres, and cast/crew details).

The provided data files are stored in the `./zippedData/` and `./Data/` folders. The code also generates several images (e.g., bar charts and pie charts) stored in the `./Images/` folder.

---

## Deliverables

This project includes the following deliverables:

1. **Non-Technical Presentation:**
   - A slide deck (in PDF format) summarizing the analysis and presenting three actionable business recommendations.
   - The presentation is designed for a business stakeholder audience and includes clear, simple visualizations (e.g., bar charts, line graphs, and pie charts).

2. **Jupyter Notebook:**
   - An integrated `.ipynb` file that includes both Python code and Markdown explanations.
   - The notebook is organized into sections: Business Understanding, Data Understanding, Data Preparation, Data Analysis, Visualization, and Conclusion.
   - It contains all code, detailed write-ups, and at least three visualizations supporting our recommendations.

---

- **Data Manipulation and Analysis with pandas:** Data is prepared and analyzed using idiomatic, performant pandas code.

---


