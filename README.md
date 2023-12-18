# 2023 MLB Batting Data Visualization Dashboard
## Project Proposal

## Overview
The goal of this project is to develop a comprehensive data visualization dashboard for MLB hitters from the 2023 season with a minimum of 100 plate appearances, incorporating their standard statistical splits, advanced analytics, and performance against specific pitches. The end result should be a dashboard that offers simple visualizations that display a team's performance against specific pitches, and visualizations that offer lists of players who perform well against specific pitches. Implentation could inform roster decisions, targeted offseason training programs, and potential targets for offseason acquisitions.

## Objectives
1. **Data Aggregation**: Gather 2023 regular season MLB batting data with a minimum of 100 plate appearances.
2. **Dashboard Development**: Build an interactive and dynamic dashboard with hover text of the player's batting statistics
3. **Advanced Analytics Integration**: Produce visualizations of the top hitters for a chosen statistic.
4. **Team Aggregation**: Generate visualizations that aggregate a chosen team's statistical performance.
5. **Accessibility and Usability**: Ensure ease of use and accessibility.

## Data Sources and Collection
This project will source data that was posted to www.kaggle.com and was collected from www.fangraphs.com by Shane Simon. Additionally, I am investigating the potential for incorporating information from the Python library pybaseball (MIT License, Copyright (c) 2017 James LeDoux) to potentially supplement the data.

**Fangraphs.com attributes their data sources as follows:**
- Major League Baseball data provided by Major League Baseball.
- All major league baseball data including pitch type, velocity, batted ball location, and play-by-play data provided by Sports Info Solutions.
- All UZR (ultimate zone rating) calculations are provided courtesy of Mitchel Lichtman.
- All Win Expectancy, Leverage Index, Run Expectancy, and Fans Scouting Report data licenced from TangoTiger.com

## Key Features
1. **Traditional Batting Statistics**: Traditional metrics like batting average, home runs, RBIs, plate appearances, etc.
2. **Specific Pitch Splits**: Statistical splits that track performance against various pitches, such as fastballs, changeups, and sliders
3. **Advanced Analytics**: Metrics like WAR, LA, EV, and Contact%
4. **Interactive Charts and Graphs**: Visual tools for data representation

## Technology Stack and Implementation
- **Frontend**: JavaScript, CSS, HTML
- **Backend**:
- **Database**: postgresQL or MongoDB
- **Data Processing**: Python, Pandas, numpy, Jupyter, and pybaseball
- **Hosting**: Github

