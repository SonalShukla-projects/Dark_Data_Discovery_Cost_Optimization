# Dark_Data_Discovery_Cost_Optimization

# Power BI Report & Data Model Architecture

## Overview
This repository contains the layout specifications, data models, static resources, and report theme settings for the Power BI Business Intelligence dashboard. The underlying layout structure utilizes custom XML configurations (`Report/Layout`, `[Content_Types].xml`), custom theme definitions (`CY24SU10.json`), and security binding models to provide business insights.

## Project Structure
* `Report/Layout`: Defines visual placement, page layouts, formatting, and canvas dimensions.
* `Report/StaticResources/SharedResources/BaseThemes/`: Stores color palettes, typography, and default style rules (e.g., `CY24SU10.json`).
* `DataModel`: Logical data schema containing tables, relationships, DAX measures, and data transformations.
* `Settings` & `SecurityBindings`: Configuration files managing connection strings, RLS (Row-Level Security), and file permissions.

## Features
- **Custom Power BI Theme Integration**: Embedded JSON theme styling for standardized corporate branding.
- **Data Modeling & Analytics**: Includes complex DAX calculations, structured relationship hierarchies, and optimized data schemas.
- **Dynamic Security**: Configured with explicit security bindings and data access controls.

## Usage
1. Open the `.pbix` file using **Power BI Desktop**.
2. Refresh the dataset or configure the data source settings under `Transform Data` -> `Data Source Settings`.
3. Publish to the **Power BI Service** for distribution and workspace sharing.
