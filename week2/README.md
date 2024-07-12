"#MakeoverMonday week2 project" 
## Introduction

The goal of this project is to visualize the cumulative natural gas production across various countries over more than a century. This visualization helps to understand the global distribution and historical trends in natural gas production.

## Data

The data used in this project includes the cumulative natural gas production by country in exajoules (EJ) from 1900 to 2022. The dataset provides a comprehensive overview of the historical and current production levels. The dataset can be downloaded from the below shared link
https://data.world/makeovermonday/week-27-what-to-watch-in-2024-energy
suggested article: https://visualizingenergy.org/the-history-of-global-natural-gas-production/

## Visualization

The main visualization is an interactive choropleth map that highlights the cumulative natural gas production for each country. The map uses a custom color scale:
- **5 to 200 Exajoules**: Very Dark Blue to Dark Blue
- **200 to 500 Exajoules**: Dark Blue to Medium Blue
- **500 to 1000 Exajoules**: Very Light Blue to  Light Blue
- **Above 1000 Exajoules**: Light Blue to White

## Line Chart

In addition to the choropleth map, a line chart visualization is provided to show the cumulative production of natural gas for any five selected countries over the years.

## Installation

To run this project locally, you'll need to install the required dependencies listed in 'environments.yml' file.
The project requires the following Python libraries:
- `plotly`
- `pandas`

## Results

The interactive map allows users to hover over each country to see the cumulative natural gas production, with country boundaries highlighted in bold black. This visualization provides insights into the historical and regional distribution of natural gas production.

## License

This project is licensed under the MIT License - see the LICENSE file for details.