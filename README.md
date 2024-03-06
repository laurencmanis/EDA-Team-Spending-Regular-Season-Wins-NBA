# EDA: Team Spending & Regular Season Wins in the NBA
Exploratory Data Analysis Around Team Spending &amp; Regular Season Wins in the NBA

Originally created for an Exploratory Data Analysis graduate course in November of 2023.

## Motivation
Exploring the relationship between historical team payrolls and records and wins, attempting to answer the question like:
- Do NBA teams with higher payrolls win more regular season games?
- Are teams justified in going over the salary cap?

## Data 
Salaries.csv: Salary information for every active player by season (obtained from data.world)
Salary-Cap.csv: NBA salary cap by season (obtained from basketball-reference)
Inflation.csv: Yearly inflation rates (from Investopedia)
Team-Records.csv: Team records and win percentages by season (obtained from Kaggle)

## Simplifying Assumptions 
- Looking at a 20-year, 21-season period, from the 1997-98 season through 2017-18 season
- A team’s payroll is defined as the sum of all of their players' salaries
- All dollar values have been converted to and are represented in 2022 USD, based on inflation rates from Investopedia
- Teams are represented by the names they went by in the given season
- Seasons with lockouts and other special cases are treated as normal seasons
- A team is considered over the cap or not cap compliant if their payroll exceeds the salary cap
- No consideration is given to teams with exceptions or luxury tax exemptions

## High-Level Takeaways & Potential Next Steps
Based on the data, it appears that teams with higher payrolls, specifically those above the salary cap, win more games in the regular season, on average. If this is indeed the case, teams hoping to make a championship run are justified in their action of spending more money on personnel and going above the salary cap.

More research and further analysis would be needed to confirm this hypothesis, including:
- Additional consideration for cap exceptions 
- Other factors in wins/performance (coaching, home court advantage, schedule, etc.)
- Playr Injury information
- 2-way player consideration
- Etc.
 

 

 
