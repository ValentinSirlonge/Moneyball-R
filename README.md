# Moneyball – Baseball Player Value Analysis
This project analyzes Major League Baseball (MLB) player statistics through the lens of the *Moneyball* strategy, which gained fame through the Oakland A’s data-driven approach to assembling a competitive team on a budget.

<p align="center">
  <img src="https://img-s-msn-com.akamaized.net/tenant/amp/entityid/BB1lEoSr.img?w=768&h=384&m=6&x=459&y=177&s=477&d=190" 
       alt="Moneyball" 
       width="400"/>
</p>


## Project Overview
- **Goal**: Identify undervalued players using performance data to optimize team composition and salary efficiency.
- **Dataset**: Official MLB data containing player performance and salary information.
- **Tools**: Built entirely in R with a structured HTML dashboard generated via R Markdown.


## Key Features
### Data Cleaning & Preparation
- Loaded, cleaned, and formatted raw data from multiple MLB seasons.
- Standardized variable names, filtered relevant years, and handled missing values.


### Dashboard Tabs (based on the assignment brief)
- **Introduction**: Context of the Moneyball method and its impact.
- **Performance Metrics**: Batting average, OBP (On-Base Percentage), SLG (Slugging Percentage), and more.
- **Top Players**: Ranking of players by performance-to-salary ratio.
- **Salary Evolution**: Visual graphs tracking salary trends versus output.
- **Team Strategy**: Suggestions for building cost-effective, high-performance teams.

### Visualizations
- Interactive tables (via `DT`) and graphs (`ggplot2`) highlight standout performers.
- Strategic plots showing correlations between salary and key performance indicators.


## Technologies Used
- **Language**: R
- **Environment**: RStudio
- **Libraries**: `dplyr`, `tidyr`, `ggplot2`, `readr`, `kableExtra`, `DT`, `shiny`, etc.
- **Output**: HTML dashboard via R Markdown
