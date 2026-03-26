# 🏅 Exploratory Data Analysis (EDA): Olympic Medal History

This project presents an Exploratory Data Analysis (EDA) of the historical Olympic Games dataset, with the goal of studying the evolution of athlete participation and medal distribution from a historical and geopolitical perspective.

The analysis explores how economic power, population, global events, and political contexts have influenced Olympic performance across different countries and time periods.

---

## 📑 Table of Contents
---
- [Introduction](#description)
- [Research Questions](#-research-questions)
- [Methodology](#%EF%B8%8F-methodology)
- [Results](#-results)
- [Key Insights](#-key-insights)
- [Challenges](#%EF%B8%8F-challenges)
- [Repository Structure](#-repository-structure)
- [Tech Stack](#-tech-stack)
- [My Contributions](#-results)
- [Authors](#authors)

---

## 📊 Data Source

The dataset was obtained from [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results) and contains historical information on Olympic athletes, events, and medal results.

**Categorical variables**: Sex, Country / NOC, Sport, Event, Medal  
**Numerical variables**: Age, Height, Weight, Athlete ID  
**Temporal variables**: Year, Games  
**Binary variables**: Has_Medal, Team_Event, Single_Event 

## 🧹 Data Preprocessing
**Missing Values**  
Several preprocessing steps were applied to ensure data consistency:  

- *Medal values*: Missing medal values were interpreted as athletes who did not win a medal in the event. These values were replaced with “NoMedal” to preserve this information.  
- *Incomplete dates*: Partial date information was combined where possible to reduce missing values.  
- *Athlete characteristics*: Age, height, and weight contain many missing values. Since these variables were not the main focus of the analysis, missing values were replaced using the median value by gender.  

## 🎯 Objectives

The project aims to explore several key questions:

- How has Olympic participation evolved over time?
- Which countries have historically dominated the Olympic medal table?
- How do economic and demographic factors relate to Olympic success?
- How have historical events influenced Olympic performance?

---

## 🔎 Key Observations

1. **Olympic Powerhouses**
Historically, a small group of countries has dominated the Olympic medal table, including United States, China, Russia / Soviet Union and Germany.

2. **Sport Specialization**
Leading Olympic nations tend to specialize in specific sports disciplines, investing resources strategically in areas where they have competitive advantages.

3. **GDP and Population**
The analysis suggests several patterns:

- Countries with high GDP per capita tend to perform well in the Olympic medal rankings.
- Some countries achieve strong results despite lower economic resources, likely due to targeted sports investment.
- Conversely, some wealthy nations obtain relatively few medals, suggesting that economic resources alone do not determine success.
  
4. **Host Country Advantage**
A strong host country effect was observed. In most Olympic Games, the host nation significantly increases its medal count, likely due to factors such as:
- home advantage
- increased funding before the event
- larger athlete delegations

---

## 📈 Athlete Participation and Performance Over Time
Major historical events have significantly influenced Olympic participation and performance.
Political conflicts, wars, and geopolitical tensions have directly impacted both the number of participating athletes and the competitive balance between nations.

**Germany in the Olympic Games**  
Germany’s Olympic history reflects a transition from a highly politicized sports system to a more balanced and sustainable model in the modern era.

**USSR Performance**  
The Soviet Union achieved remarkably consistent Olympic results, typically winning between 90 and 125 medals per Olympic Games during the period 1952–1976.

**United States Performance**  
The United States shows a long-term upward trend in medal counts since the first modern Olympics in 1896, with notable peaks in 1904 and 1984, both hosted in the United States.

**USSR vs Russia**  
Following the dissolution of the Soviet Union, Russia experienced a significant decline in medal counts compared to the Soviet era.

**USSR vs USA Rivalry**  
During the Cold War, the Olympic Games became a stage for geopolitical rivalry between the United States and the Soviet Union.
The 1980 and 1984 Olympic boycotts significantly distorted the medal standings.
When both countries competed directly without boycotts, the rivalry was extremely close, with a slight advantage for the Soviet Union in several editions.

## 🧠 Main Conclusions
**Sports specialization**  
Olympic success is not determined solely by economic wealth. Countries that allocate resources strategically and invest in specific sports programs tend to perform better.

**Impact of world events**  
Major events such as the World Wars created structural disruptions in Olympic participation and medal distribution, followed by uneven recovery periods influenced by political sanctions, economic crises, and geopolitical changes.

**Geopolitical rivalries**  
During the Cold War, the Olympic Games served as a symbolic arena for geopolitical competition. Boycotts and political tensions significantly affected participation and medal outcomes.

---

## 🔮 Future Research Directions

Potential extensions of this analysis include:
- Investigating the relationship between GDP per capita and medal efficiency
- Analyzing population size vs medal performance
- Studying long-term specialization trends by country
- Applying predictive models to estimate medal counts

---

## ⚙️ Technologies Used

**Programming**  
- Python

**Main libraries**  
- Pandas
- Numpy
- Matplotlib
- Seaborn
  
**Tools**  
- Jupyter Notebook (data exploration and visualization)
- Canva (presentations)
- Word / PDF (project documentation)

---

## 👥 Credits

Pablo Baro
Nico Guitart
Sergi de la Cruz

**Bootcamp Data Science The Bridge**

2025/26
