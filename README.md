# How to render PivotGrid by using Date Range Filter

## Project Overview

This project showcases the integration of Syncfusion's EssentialJS2 PivotGrid control within an ASP.NET MVC application. The primary focus is on demonstrating how to apply date range filters to pivot grid data, enabling users to view summarized and aggregated data within specific time periods. This is particularly useful for business intelligence, reporting, and data analysis scenarios.

## Features

* **PivotGrid Rendering** - Dynamic rendering of pivot grid with customizable rows, columns, and values
* **Date Range Filtering** - Interactive date range picker for filtering pivot grid data
* **Data Aggregation** - Automatic aggregation and summarization of data based on applied filters
* **Responsive Design** - Bootstrap-based responsive UI that adapts to different screen sizes
* **EssentialJS2 Integration** - Leverage of Syncfusion's EssentialJS2 components for rich UI elements

## Prerequisites

* Visual Studio 2022
* .NET Framework (compatible with the project configuration)
* NuGet Package Manager for dependency management

## Installation

1. **Checkout this project** to a location on your disk
2. **Open the solution file** using Visual Studio 2022
3. **Restore NuGet packages** by rebuilding the solution - this will download all required dependencies
4. **Ensure database connectivity** - The project includes a SQL Server Compact database (ReportsTable.sdf) in the App_Data folder

## How to Run the Project

1. Build the solution to restore all NuGet packages
2. Set the startup project to EssentialJS2MvcApplication1
3. Press F5 or click Run to start the development server
4. Navigate to the PivotGrid view through the application menu

## Usage

The application provides a user-friendly interface for working with pivot grid data:

* Access the PivotGrid features through the application's navigation menu
* Use the date range filter controls to select your desired time period
* The pivot grid automatically updates to display filtered data
* Pivot grid data is organized by rows, columns, and value fields for comprehensive analysis

## Project Structure

* **Controllers** - Application controllers including PivotGridController for handling pivot grid operations
* **Views** - Razor views for rendering the user interface, including PivotGridFeatures.cshtml
* **Models** - Data models and view models for application structure
* **Scripts** - JavaScript libraries and references for client-side functionality
* **Content** - CSS stylesheets and styling resources

## Technologies Used

* ASP.NET MVC
* EssentialJS2 (Syncfusion components)
* Bootstrap CSS Framework
* jQuery for DOM manipulation
* SQL Server Compact Database

## Support

For questions or issues regarding this project, please refer to the Syncfusion documentation or the project structure for implementation details.