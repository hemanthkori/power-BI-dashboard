# Power BI Dashboard for Job Market Analysis

This repository contains an interactive Power BI dashboard that explores patterns in the job market. The dashboard helps recruiters and job seekers understand demand trends, salary ranges, in-demand skills and other important metrics.

## Objectives

- Build a visually appealing, interactive dashboard to analyse job postings data.
- Identify key patterns in the job market: top roles, companies, locations, and salary ranges.
- Provide actionable insights for recruiters and job seekers using data-driven storytelling.

## Data & Methodology

The dataset for this project was sourced from open job listings platforms and includes fields such as job title, company, location, salary range, industry and required skills. Data cleaning and transformation were performed using Power Query and Python before importing into Power BI. DAX measures were created for metrics such as average salary, job count by category, and top skills.

## Dashboard Features & Key Insights

The Power BI report (`data_jobs_dashboard.pbix`) includes multiple pages with interactive visuals:
- **Overview** – headline metrics (total jobs, average salary) and interactive filters.
- **Role & Company Analysis** – bar charts showing top job titles, top hiring companies, and distribution across industries.
- **Location & Salary Trends** – maps and box plots of job counts and salary ranges by region.
- **Skills Demand** – word clouds and bar charts highlighting the most in-demand skills.

From the analysis we discovered:
- Certain tech roles (e.g., Data Analyst, Data Scientist) and industries (e.g., IT, Finance) are consistently high in demand.
- Top locations have higher average salaries but also greater competition.
- Skills like Python, SQL and machine learning dominate job descriptions.

## Deliverables

- `data_jobs_dashboard.pbix`: The Power BI report with all visuals and DAX calculations.
- `images/`: Exported PNGs of report pages for quick preview.
- `README.md` (this file): Summary of objectives, methodology, insights and usage guidelines.

## Skills Demonstrated

- Data wrangling with Power Query and Python.
- Data modeling and DAX for dynamic metrics.
- Visual design in Power BI (charts, maps, slicers, tooltips).
- Analytical storytelling tailored for recruiters and job seekers.

## Usage

To explore the full interactive dashboard, download the `.pbix` file and open it with [Power BI Desktop](https://powerbi.microsoft.com/desktop/). Alternatively, view the static images in the `images/` folder. Feel free to fork this repository and adapt the report for your own analysis.

## Contact

For questions or collaboration opportunities, please reach out via LinkedIn or open an issue in this repository.
