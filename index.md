## [Sports Science/Analytics Projects](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects) 

---
### [Master's Project](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Master's%20Project)
***Receiving a top-five pick in the NBA lottery leads to success***

**Duration**: 5 months  
**Program**: R

**Description**: This project was my final Master's project in the program. I spent 5 months researching NBA draft data to see if a top-five pick's effect in the NBA correlated with success. My goal was to find a clear correlation between winning and being a high draft pick, and when to expect this winning to happen.

I utilized OLS regressions, negative binomial regressions, and event studies as the statistical frameworks for this analysis. These models predicted that just by having a top-five pick, the team is expected to increase in winning in years 3-6. Playoff and regular season wins become statistically different from the rookie season wins in most of these years.

- **[Presentation](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Master's%20Project/Final%20Project%20NBA%20Presentation.pdf)**
- **[Project Paper](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Master's%20Project/Master's%20Project%20Paper.pdf)**

<img src="/images/Event Study NBA.png"/> 
<img src="/images/Comparison of Top Five to Non Lottery Picks.png"/>

---
### [Volleyball Project](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/Volleyball%20Project)
**Duration**: 4 months  
**Program**: R

**Description**: This project focused on finding the statistics and movements essential to winning volleyball games. The data used was two seasons of historical catapult data and matching game data from those two seasons. By collecting and analyzing this data, the goal was to provide answers to the questions about what movements within a game and practice drove wins for the volleyball team.

Two types of Bayesian models were run in this analysis using STAN: General Linear Regression Models and Logistic Models. These models were run using the stan package in R, allowing for a deep Bayesian analysis of how movements influenced match outcomes and statistics. This project deepened my experience with advanced statistical modeling and reinforced the value of data analysis in optimizing athlete performance.

- **[Presentation](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Volleyball%20Project/Volleyball%20Presentation.pdf)**
- **[Project Paper](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Volleyball%20Project/Volleyball%20Project%20Paper.pdf)**
- **[Data Manipulation Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Volleyball%20Project/Volleyball%20Portfolio%20File.Rmd)**
- **[Stan Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Volleyball%20Project/Volleyball%20Stan.R)**

<img src="/images/kill_diff_Logistic_curve.png"/> 
<img src="/images/predictive values.png"/>

---

### [Football Metrics Dashboard](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/Football%20Projects)
**Duration**: 2 months  
**Program**: Power BI

**Description**: This project aimed to provide a dashboard of testing metrics that is easily accessible to coaches. The goal was to combine all of the metrics that Football values and showcase them in a one-stop shop. 

The dashboard's capabilities allow coaches to select different players and dates to review individual metrics easily. The metrics covered in this dashboard come from Catapult, Vald ForceDecks, Body Weight, and Hydration. These metrics are all shown as z-scores to compare players to their prior 30-day averages for practice and load preparations. 

<img src="/images/Football Metrics Dashboard.png"/> 

---

### [ForceDecks API](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/ForceDecks%20API)
**Duration**: 3 months  
**Program**: R

**Description**: This project aimed to build a consistent API that runs every five minutes to automatically update ForceDeck data files utilized by an entire athletics department. The API was implemented in R-Studio and was designed to check for new data and then update the sports-specific data frames to keep all data current. 

This project was completed using the Vald API documentation and resource files. A substantial portion of time was spent on researching how to code an API and how to validate API credentials within R. The other portion of time was spent formatting and specifying the incoming data so the formatting was consistent with the existing data formats.

- **[Main](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/ForceDecks%20API/FD%20main.R)**
- **[Utils](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/ForceDecks%20API/utils)**

---

### [Injury Project](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/Injury%20Project)
**Duration**: 7 months  
**Program**: R

**Description**: This project aimed to explore the relationship between ForceDecks data and injury report data to identify connections or correlations that could help predict or flag injuries. This project was completed over two semesters with a small break between the two periods. 

The first stage focused on exploratory and descriptive statistics, mainly utilizing z-score and data summarization techniques. The project's second stage continued this exploratory analysis and focused on sports with higher observation counts to slim down the data set and ensure robust results. Statistical methods such as a Cox proportional hazards model were introduced to look for predictive results.

Multiple angles of analysis were attempted in both stages, and while results were not fully conclusive, information valuable to the department was still gained. 

- **[Poster Presentation](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Injury%20Project/Second%20Stage/Symposium%20Poster%20Presentation.pdf)**
- **[1st Stage Presentation](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Injury%20Project/First%20Stage/Injury%20Exploration%20Presentation.pdf)**
- **[1st Stage Exploratory Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Injury%20Project/First%20Stage/Data%20Exploration%20Code.R)**
- **[1st Stage Analysis Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Injury%20Project/First%20Stage/Beginning%20Data%20Analysis.R)**
- **[2nd Stage Presentation](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Injury%20Project/Second%20Stage/Injury%20Exploration%20Presentation.pdf)**
- **[2nd Stage Analysis Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Injury%20Project/Second%20Stage/Injury%20Code.Rmd)**

<img src="/images/Injury Horizontal Bars.png"/> 

---

### [Baseball Dashboard Project](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/Baseball%20Dashboard)
**Duration**: 2 months  
**Program**: Power BI

**Description**: This project aimed to provide a printable dashboard of pitching statistics for coaches to use easily. This dashboard was my first experience using Power BI in a professional setting.

The dashboard's capabilities allow coaches to easily select different pitchers and specific game dates to review individual performance metrics. The second tab of the dashboard has a slider that allows for the ability to specify a time frame for summarizing pitching statistics. Coaches can print this dashboard to show players at practice about their performance in the previous games or their overall season-long performances.

<img src="/images/Baseball Dashboard.png"/> 

---

### [Track & XC Project](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/Track%20%26%20XC%20Project)
**Duration**: 3 months  
**Program**: R

**Description**: The project investigated the differences between the Track and Cross Country (XC) teams, who do not train together but will compete in similar or even the same events. This analysis focused on ForceDeck data and race times to see which metrics predicted performance for each team's best runners and how those differed.

To answer this question, I implemented a hierarchical statistical model to better understand team differences.  The project included exploratory analysis, distance comparisons, and team comparisons to uncover key insights into performance metrics. This project showcases my visualization skills using the ggplot2 package in R.

- **[Presentation](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Track%20%26%20XC%20Project/Track%20%26%20XC%20Presentation.pdf)**
- **[Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Track%20%26%20XC%20Project/Track%20%26%20XC%20Code.Rmd)**

<img src="/images/Radar Chart XC Track.png"/> 

---

### [Basketball End-of-Season Project](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/Basketball%20Project)
**Duration**: 1 month  
**Program**: R

**Description**: This project aimed to provide an end-of-season analysis of the basketball team. This analysis used Strive in-season data. The main goals of this project were to provide meaningful visualizations that could be aggregated and report on season-long trends. Trends were analyzed by position and individually by player. 

- **[Charting Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Basketball%20Project/End%20of%20Season%20Report%20Code.Rmd)**

---

### [Football Height Project](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Sports%20Science%20Projects/Football%20Projects)
**Duration**: 1 week  
**Program**: R

**Description**: This project was an impromptu question from the Head Coach of the football team. The main question was how much athletes in the football program have grown over the years. This included growth in height, wingspan, and hand size. This project was a quick look at a small data set showcasing my dplyr manipulation skills and an understanding of R programming. A quick turnaround gave the coach an insightful answer to his question.

- **[Football Height Code](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/blob/main/Sports%20Science%20Projects/Football%20Projects/Football%20Height%20Code.Rmd)**

---

## [Economics Projects](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Economics%20Studies) 

### [Creativity Study](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Economics%20Studies/Creativity%20Study)

### [Mountain West Housing Prices](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Economics%20Studies/Mountain%20West%20Housing%20Prices%20Study)

### [Smoking Excise Tax](https://github.com/ParkerBooth/Sports-Analyst-Portfolio/tree/main/Economics%20Studies/Smoking%20Excise%20Tax%20Project)

---

## Education
**University of Utah:**
Master of Science - MS, Statistics, Econometrics Specialization
Jan 2024 - May 2025

**University of Utah:**
Bachelor's degree, Quantitative Analysis of Markets & Organizations, Finance Emphasis
Aug 2021 - Dec 2023

---

## Contacts
- [LinkedIn](https://www.linkedin.com/in/parker-booth-26b81b237/)
- Email: parkerbooth7@gmail.com
- Phone: (435) 776-6640

---

