#CarbonTrack - Personal Carbon Footprint Calculator

## Website Link: https://noeljosephkurian-ux.github.io/CarbonTrack-Noel-Joseph-Kurian-/

## Project Overview

CarbonTrack is a web-based personal carbon footprint calculator designed to help users understand how their everyday activities contribute to carbon emissions.

The calculator allows users to enter information across five major categories:

- Food
- Transportation
- Electricity
- Waste
- General Consumption

Based on the entered information, the website provides an estimated carbon footprint, identifies the category contributing the most emissions, and provides suggestions to help users make more environmentally responsible choices.

The project is developed as an educational sustainability project using basic web technologies and simplified emission factors.

---

## Main Features

### 1. Personal Carbon Footprint Calculator

Users can enter lifestyle and consumption information across different environmental categories.

The calculator processes the entered data and estimates the user's carbon emissions in terms of **kg COâ‚‚e**.

### 2. Five Environmental Categories

The calculator covers:

- **Food** â€” Estimates emissions associated with different food consumption habits.
- **Transportation** â€” Considers travel-related activities and modes of transport.
- **Electricity** â€” Estimates emissions based on electricity usage.
- **Waste** â€” Considers general waste generation and disposal.
- **Consumption** â€” Represents emissions associated with general purchasing and consumption habits.

### 3. Category-wise Results

After completing the calculator, users can view their estimated emissions for each category.

This makes it easier to understand which areas of their lifestyle contribute most to their overall carbon footprint.

### 4. Biggest Contributor Identification

CarbonTrack identifies the category with the highest estimated emissions and highlights it to the user.

This helps users focus their efforts on the area where changes could have the greatest potential impact.

### 5. Suggestions and Recommendations

The results page provides practical suggestions based on the calculated footprint.

These suggestions are intended to encourage more sustainable everyday choices.

### 6. "What If?" Scenarios

Users can explore possible changes to their lifestyle and see how those changes could affect their estimated carbon footprint.

This helps demonstrate the potential environmental impact of individual choices.

### 7. Responsive Design

The website is designed to work across different screen sizes, including:

- Desktop computers
- Laptops
- Tablets
- Mobile devices

### 8. Light and Dark Mode

The website includes both light and dark display modes to improve usability and provide users with a choice of interface appearance.

---

## Technologies Used

- **HTML5** â€” Used to create the structure and content of the website.
- **CSS3** â€” Used for styling, layout, responsive design and visual appearance.
- **JavaScript** â€” Used for calculator logic, user interaction, calculations, results and dynamic content.

No external backend or database is required.

---

## Project Structure

```text
CarbonTrack/
â”‚
â”œâ”€â”€ index.html
â”œâ”€â”€ css/
| â””â”€â”€ style.css
â”œâ”€â”€ js/
| â””â”€â”€ app.js
| â””â”€â”€ emissions.css
â”œâ”€â”€ Documents/
â”‚ â””â”€â”€ CarbonTrack PPT.pptx
â”‚ â””â”€â”€ CarbonTrack_Final.pdf
â”‚
â””â”€â”€ README.md
```
## How to Run

### Method 1 â€” Open Directly
1. Download or clone the repository.
2. Extract the project files if downloaded as a ZIP.
3. Open index.html in a web browser.
4. The website can be used directly without installing any additional software.

### Method 2 â€” Using GitHub
1. Open the project repository.
2. Download the repository using Code â†’ Download ZIP.
3. Extract the ZIP file.
4. Open index.html in a browser.

No Node.js, database, or server installation is required.

---

## How the Calculator Works
The calculator follows a simple process:
```text
User Input
â†“
Activity Data
â†“
Emission Factor
â†“
Carbon Emission Calculation
â†“
Category-wise Results
â†“
Total Carbon Footprint
â†“
Biggest Contributor
â†“
Suggestions / What-If Scenarios
```
The basic calculation principle used by the project is:
```text
Carbon Emissions = Activity Data Ã— Emission Factor
```
The calculated values from the different categories are combined to produce an estimated overall carbon footprint.

---

## Example Workflow
1. Open the CarbonTrack website.
2. Enter the requested information about daily or monthly activities.
3. Complete the sections for food, transportation, electricity, waste and consumption.
4. Submit the information to calculate the footprint.
5. View the total estimated carbon footprint.
6. Check the category-wise breakdown.
7. Identify the category with the highest contribution.
8. Review the suggested sustainable actions.
9. Use the "What If?" section to explore possible changes.

---

## Sustainability Focus
CarbonTrack is intended to support awareness of sustainable consumption and climate action.

The project is related to the following Sustainable Development Goals:

- SDG 2 â€” Zero Hunger: The food category provides a connection to sustainable food consumption and the environmental impact associated with food systems.
- SDG 12 â€” Responsible Consumption and Production: The calculator encourages users to understand the environmental consequences of consumption and waste.
- SDG 13 â€” Climate Action: The primary purpose of the calculator is to increase awareness of personal carbon emissions and encourage actions that may reduce them.

The project also relates conceptually to ISO 14001, particularly the ideas of identifying environmental impacts, measuring environmental performance and supporting continuous improvement.

---

## Validation
The website was tested by entering different combinations of user inputs to check whether:

- Input controls respond correctly.
- Calculations are performed correctly.
- Results are displayed properly.
- Category contributions are calculated and displayed.
- The biggest contributor is identified.
- Suggestions are displayed after calculation.
- "What If?" scenarios respond to changes.
- Light and dark modes function correctly.
- The website remains usable on different screen sizes.

---

## Methodology
CarbonTrack is an **educational prototype**.

The emission factors and calculations used by the website are simplified estimates intended for demonstration, learning and environmental awareness. They should not be treated as a scientifically validated or professionally certified carbon footprint assessment.

The purpose of the project is to demonstrate how a simple web-based application can help users understand the relationship between everyday activities and carbon emissions.

---

## Future Enhancements
The project can be further improved by adding:

- Region-specific emission factors.
- More detailed transportation and energy calculations.
- User accounts and saved results.
- Historical carbon-footprint tracking.
- More detailed charts and visualizations.
- Comparison of footprints over time.
- Integration with verified environmental datasets.
- More personalized recommendations.
- Support for additional languages.

---

## Disclaimer
CarbonTrack is developed as a student sustainability project for educational purposes.

The results provided by the calculator are estimates based on simplified assumptions and should not be used as an official measurement of an individual's actual carbon footprint.

---

## Project Purpose
The main objective of CarbonTrack is to make carbon-footprint awareness simple and accessible.

By allowing users to measure, understand and explore the environmental impact of everyday activities, the project demonstrates how a basic web application can be used as a tool for sustainability education and awareness.

# CarbonTrack-Parvana-Mohan
# CarbonTrack — Student Carbon Footprint Calculator

## Run the website
1. Extract the ZIP.
2. Open `index.html` in Chrome, Edge or Opera.
3. No JavaScript, Node.js or server installation is required.

## Included
- Responsive desktop/mobile layout
- Five-step calculator: food, transport, electricity, waste and consumption
- Working radio-button options and sliders
- Category breakdown chart
- Biggest-contributor identification
- Suggestions and “What if?” scenarios
- Light/dark mode

## Methodology warning
This is a working educational prototype. The original interface collects broad lifestyle categories, so not every category is based on a physically measured activity unit.

- Transport and electricity use activity-based calculations.
- Food, waste and consumption currently use simplified screening proxies.
- The electricity value is provisional and should be replaced with the official India-specific factor chosen by the project team.
- For a formally validated calculator, collect food mass/servings, waste kilograms and purchase spending, then use published factors with units.

## Sources consulted
- UK Department for Energy Security and Net Zero, *Greenhouse gas reporting: conversion factors 2026*:
  https://www.gov.uk/government/publications/greenhouse-gas-reporting-conversion-factors-2026
- Our World in Data, *Environmental Impacts of Food*:
  https://ourworldindata.org/environmental-impacts-of-food
- Our World in Data, *Greenhouse gas emissions per kilogram of food product*:
  https://ourworldindata.org/grapher/ghg-per-kg-poore

Before submitting academically, cite the exact factor table and reporting year used by your team, especially for India's electricity grid and local transport.
