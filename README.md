# SDS192-project2

## Author

Maybell Murphy-Sylla, Abby Crotteau, Khadija Teffahi, Esther He

## Project Description

This project analyzes trends of U.S. food imports in the last 20 years, and how the rate of importation of different food groups has varied. The selected dataset is annually published by the U.S. Department of Agriculture, containing import values and the origin of food and drink shipments into U.S. ports from 1999 to 2024. Import values included are the monetary value of the product being imported, the physical volume of the imports, and the percentage change across each year, along with a ten-year average change. These are separated by year into different food groups, such as meat, fish, vegetables, and dairy. Among these broad categories, each food group contains sub-categories. For example, “vegetables” data is divided into the subcategories “fresh,” “frozen,” “dried,” and “prepared or preserved.” We specifically analyzed how the 2008 financial crisis has impacted import volumes of these food groups.

## Project Structure Overview

Here is how the repository is structured:

-   **Data folder**

    -   Contains the original data set: `FoodImports.xlsx`
      
    -   Contains tidied data sets used throughout analysis: `volume.csv`, `volumemeat.csv`, `volumedairy.csv`, `volumeperc.csv`, `totalpercchange0609.csv`

-   **R**

    -   Contains the file for data tidying: `tidying.qmd`

    -   Contains the file for our exploratory data analysis: `EDA.qmd`

    -   Contains the file for our overall analysis: `mainanalysis.qmd`

-   **README.md**

    -   Provides a description of the project and its structure.
