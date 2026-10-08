# Nordic Delights Oy — Business Intelligence Dashboard

A fictional Finnish food and beverage distribution company's business intelligence website, built as a course project. The site introduces Nordic Delights Oy and presents four interactive Power BI reports through an ASP.NET Core MVC dashboard.

## Features

- Responsive company website with a home page and dashboard
- ASP.NET Core MVC structure with Bootstrap and custom CSS
- Four Power BI reports embedded in the dashboard
- Interactive charts, filters, drill-down analysis, and a map visual
- Deployment to Azure App Service (Free F1 tier during the course project)

## Reports and data sources

| Report | Source | What it shows |
| --- | --- | --- |
| **Sales Performance** | Northwind sample database via Microsoft SQL Server | Sales KPIs, sales over time, categories, customers, and countries |
| **Market Overview** | Microsoft Power BI Financial Sample (Excel) | Sales, profit, products, and a country map |
| **European Market Potential** | Wikipedia, *List of European countries by population* (Web/HTML) | European population comparisons and potential markets |
| **Customer & Product Sales** | Locally generated fictional Nordic Delights dataset (CSV) | Sales, orders, category performance, and drill-down by customer type and product |

The fourth dataset is synthetic and was created specifically for this project. The other reports use sample or publicly accessible reference data; the reports are demonstrations rather than real Nordic Delights business results.


### Examples of Reports and Drill-down Functionality

<img width="1000" height="500" alt="Sales overview" src="https://github.com/user-attachments/assets/ebebdf00-0073-48e6-bb9e-be18e025fffe" />

#### Interactive Data Exploration

<img width="600" height="300" alt="Interactive data exploration" src="https://github.com/user-attachments/assets/f79798d9-f59c-40f2-b70f-a55d5fe6abb8" />

<img width="1000" height="500" alt="Report overview" src="https://github.com/user-attachments/assets/dd7096c0-f18c-4232-aeda-8420b98b4401" />

<img width="1293" height="713" alt="Report overview" src="https://github.com/user-attachments/assets/ea058db6-77f5-400c-b0ab-5141364a5381" />

<img width="900" height="600" alt="Sales by category" src="https://github.com/user-attachments/assets/ceaea362-0c57-46e9-bd64-652184ecadc8" />

#### Sales by Category – Drill-down by Customer Type

<img width="600" height="400" alt="Sales by customer type drill-down" src="https://github.com/user-attachments/assets/65210250-86bb-4a14-89cb-7eba86ca484f" />



## Technologies

- **C# / ASP.NET Core MVC** — web application
- **Bootstrap and CSS** — responsive layout and styling
- **Microsoft Power BI** — reports and interactive visualizations
- **Microsoft SQL Server / Northwind** — relational data source
- **Excel, Web/HTML, CSV** — additional data sources
- **Azure App Service** — web hosting

## Running locally

1. Install Visual Studio with the ASP.NET and web development workload, or use the compatible .NET SDK.
2. Clone the repository and open the solution or project in Visual Studio.
3. Restore dependencies and run the application using HTTPS.
4. Open the **Dashboard** page to view the report sections.

**Important:** The Power BI reports are hosted separately in the Power BI service. The **Website or portal** embedding method requires sign-in and appropriate permissions and licensing. Cloning this repository does not automatically grant access to the reports. If the embedded reports are no longer available, the MVC website can still be used to demonstrate the site structure and design.

## Deployment

The project was deployed to **Azure App Service** as part of a student assignment, using the **F1 (Free)** hosting tier. Availability of the original deployment depends on the Azure subscription and the separately hosted Power BI reports.

## Data and privacy

- Nordic Delights Oy and its CSV sales figures are fictional.
- The Northwind database is a training dataset; this project does not represent actual company transactions.

## Purpose

This project was created to practice integrating multiple data sources into Power BI, presenting business information visually, building an MVC website, and publishing a web application to Azure.
