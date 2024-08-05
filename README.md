# Atliq Hardware Power BI Project [here] ([https://your-live-report-link.com](https://app.powerbi.com/view?r=eyJrIjoiNGI4N2JhNDQtZDY3Ny00ZTBhLWJiMWQtMGRjMGJlMWZhZmY2IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)).

This repository contains the Power BI project developed for Atliq Hardware, focusing on creating dashboards for finance, sales, marketing, and supply chain analytics.

## Project Overview

Atliq Hardware has experienced rapid growth in recent years and decided to implement data analytics using Power BI to surpass competitors and facilitate data-driven decision-making. This project aims to provide answers to stakeholders' questions across various aspects, including finance, sales, marketing, and supply chain management.


## Tech Stack

- **SQL**
- **Power BI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for optimizing the report)

## Project Charter & Key Techniques

### Power BI Techniques Learned

#### Initial Planning
- Identifying critical questions to ask before starting the project.
- Understanding project objectives and stakeholder expectations.

#### Data Preparation & Modeling
- Creating calculated columns and measures using DAX.
- Developing robust data models.
- Using the divide function to prevent zero division errors.
- Creating date tables using M language.

#### Visual Design & Interactivity
- Using bookmarks to switch between visuals.
- Implementing page navigation with buttons.
- Dynamic titles based on applied filters.
- Applying conditional formatting with icons or background colors.
- Utilizing KPI indicators for key metrics.

#### Data Validation & Optimization
- Employing data validation techniques to ensure accuracy.
- Optimizing reports using DAX Studio.

#### Deployment & Collaboration
- Publishing reports to Power BI Services.
- Setting up a personal gateway for auto-refreshing data.
- Creating Power BI Apps for end-users.
- Managing collaboration, workspaces, and access permissions in Power BI Services.

## GitHub Best Practices

- **Uploading Large Files:** Using GitHub LFS (Large File Storage) for large datasets.
- **File Tracking:** Monitoring specific file extensions for efficient version control.

## Business-Related Terms

- **Financial Metrics:** Gross Price, Net Sales, Gross Margin, Net Profit, COGS (Cost of Goods Sold)
- **Time-based Metrics:** YTD (Year to Date), YTG (Year to Go)
- **Channels:** Direct, Retailer, Distributor, Consumer

## Company Background

Atliq Hardware is a globally expanding company selling computer hardware and accessories through various channels, including retailers, direct sales, and distributors. The company faced a recent setback from opening a store in the USA, which was driven by intuition and basic Excel analysis. Competitors' use of data analytics prompted Atliq Hardware to build their own analytics team to make informed, data-driven decisions.

## Project Kick-off & Questions

Before beginning the project, several key questions were addressed:

1. What is the objective of building this Power BI dashboard?
2. How will the project's success be measured?
3. What is the project timeline?
4. Are stakeholders expecting a preview before the full release?
5. What are the stakeholders' hopes and fears regarding this project?
6. Who will be using the dashboard and for what purpose?
7. What are the specific expectations from the project?
8. What potential issues could arise during development?
9. What data and resources are required to build the dashboard?
10. Are there specific design or view preferences from stakeholders?

## Data Understanding

A thorough understanding of the available data was crucial for analysis:

### Dimension Tables

Contain static data such as customer and product details.

### Fact Tables

Contain transaction data.

### Key Tables

- **dim_customer:** Details of 75 distinct customers across 27 markets.
- **dim_market:** Information on 27 markets, 7 sub-zones, and 4 regions (APAC, EU, LATAM, etc.).
- **dim_product:** Product details across multiple categories and variants.
- **fact_forecast_monthly:** Forecast data for customer needs, aiding in cost reduction and satisfaction.
- **fact_sales_monthly:** Sales data, structured similarly to forecast data.
- **freight_cost:** Travel and other costs per market.
- **gross_price, manufacturing_cost:** Pricing and manufacturing cost details.
- **Pre_invoice_deductions, Post_invoice_deductions:** Details of deductions applicable to transactions.

## Importing Data into Power BI

Data was imported from a MySQL database into Power BI, using database credentials provided by the data engineering team.

## Data Model

A well-structured data model is essential for report performance. The project adhered to best practices, utilizing a snowflake schema where appropriate.

## Dashboard Design

Dashboards were designed based on received mock-ups, with measures and visuals developed as needed. Key views include:

- **Home View:** Navigation buttons for quick access to specific reports.
- **Info, Finance, Sales, Marketing, Supply Chain, Executive Views:** Detailed insights tailored to each area.
- **Products & Support:** Additional information and support resources.

### Visual Examples

- **Overall Report:** Comprehensive overview of business metrics. 
- **Finance, Sales, Marketing, Supply Chain Reports:** Specific dashboards for each business area.

## Project Outcome

The Power BI reports provide valuable insights for data-driven decision-making, enabling stakeholders to answer numerous "why" questions based on real-time data.

You can find the full report file [here](#).
