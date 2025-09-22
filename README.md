# EPL PySpark RDD Analysis

## Overview
This project performs **analysis of English Premier League (EPL) match data** using **PySpark RDDs**.  
It reads match data from a CSV file, performs transformations, and computes:

- Total goals per season  
- Season with highest and lowest goals  
- Team with highest average goals per season  
- Probabilities of Manchester United **winning, drawing, or losing** matches  

The project demonstrates how to process large datasets efficiently using Spark RDDs.

---

## Dataset
- The dataset file is `EPL.csv`  
- Columns:
  - `home_team` – Name of the home team  
  - `away_team` – Name of the away team  
  - `home_goals` – Goals scored by home team  
  - `away_goals` – Goals scored by away team  
  - `result` – Match result from home team perspective (`H`=Home win, `D`=Draw, `A`=Away win)  
  - `season` – Season year (e.g., `2006-2007`)  

---

## Features
1. Compute **total goals per season**  
2. Identify **season with highest and lowest goals**  
3. Calculate **team with highest average goals per season**  
4. Compute **probabilities of wins, draws, and losses** for Manchester United  

---

## How to Run
1. Install PySpark:
```bash
pip install pyspark
