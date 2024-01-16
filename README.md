
<body style="background-color: #011123;
background-image: linear-gradient(221deg, #011123 50%, #141506 69%);
">


# Comprehensive Analysis of the TMDb Movie Dataset By <span style="color:green">Natnael Tadesse(1316/12)</span>

## Overview

This project conducts an in-depth analysis of the extensively-used TMDb movie dataset, containing over 10,000 movies spanning decades of cinema history. Through meticulous data exploration and insightful visualization, key trends and relationships are uncovered to reveal the factors contributing to a film's success.

**Core Objectives:**

- Identify key metrics like budget, revenue, release timing, cast, crew, and genres that correlate with a movie's popularity and financial performance.

- Analyze annual trends in budgets, revenues, and profits to understand the movie industry's evolution.

- Investigate the shifting dynamics of genre prevalence from 1960 - 2015.

- Explore the most prominent cinematic personalities in front of and behind the camera. 

- Discover pairs of features with the strongest correlations to gain a nuanced view of interconnections.


**Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, BeautifulSoup, requests, prettytable

## Contents

- [Data Overview](#data-overview)
- [Exploratory Data Analysis](#exploratory-data-analysis)
  - [Preprocessing](#preprocessing)
  - [Visualizations](#visualizations)
    - [Revenue and Budget Analysis](#revenue-and-budget-analysis)
    - [Temporal Trends](#temporal-trends)
    - [Genre Dynamics](#genre-dynamics)
    - [Prominent Personalities](#prominent-personalities)
    - [Feature Correlations](#feature-correlations)
- [Key Findings and Insights (1960-2015)](#key-findings-and-insights-1960-to-2015)  
- [Key Findings and Insights (2023)](#key-findings-and-insights-2023)  
- [Conclusions](#conclusions)

## Data Overview

- **Source:** [The Movie Database](https://www.kaggle.com/datasets/juzershakir/tmdb-movies-dataset) (TMDb)
- **Timespan:** 1960 - 2015
- **Rows:** 10,866
- **Columns:** 21 features including:
  - Budget, revenue
  - Cast, crew
  - Release date
  - Genres
  - Popularity
  
## Exploratory Data Analysis

### Preprocessing

- Handling missing values
- Data formatting and standardization 
- Feature engineering as needed

### Visualizations 

Powerful visuals provide intuitive insights into the data. Key analyses include:

#### Revenue and Budget Analysis

- Scatterplots relating budget to revenue and profit  
- Highest/lowest profit movies
- Profitability over time

#### Temporal Trends

- Annual analysis of:
  - Highest budget vs. profit
  - Total budget over years
    ![4](https://github.com/SomeonePro72/Big-Data-TMDB_Movies/assets/83784402/cd16bbfd-b005-4def-a677-d1b848c1a620)
  - Top grossing films

#### Genre Dynamics

- Prevalence of genres from 1960 - 2015
  ![7](https://github.com/SomeonePro72/Big-Data-TMDB_Movies/assets/83784402/e35fe16f-3462-40fb-a262-3648e0498aec)

#### Prominent Personalities

- Most featured cast members
  ![6](https://github.com/SomeonePro72/Big-Data-TMDB_Movies/assets/83784402/212ec58c-75fa-4251-928b-efdb9bc2da2e)

- Most prolific directors
  ![0](https://github.com/SomeonePro72/Big-Data-TMDB_Movies/assets/83784402/4a53effe-628d-4e97-8886-0533e7981730)

- Production companies involved
  ![9](https://github.com/SomeonePro72/Big-Data-TMDB_Movies/assets/83784402/052d8084-c7f7-43f8-b50f-f80b864205b5)

  
#### Feature Correlations 

- Heatmaps relating all features
  ![10](https://github.com/SomeonePro72/Big-Data-TMDB_Movies/assets/83784402/42c27ebd-bfd5-4e1c-81a6-f7d680c9f9cb)
  
- Strongest correlations

## Key Findings and Insights 1960 to 2015

### Financial Landscape:

- **Highest Profit Movie (1960-2015):** "Avatar" holds the record for the highest profit of all time, demonstrating the potential for substantial returns in the film industry.
  
- **Lowest Profit Movie (1960-2015):** "The Warrior's Way" serves as a reminder of the variability in financial success, highlighting the importance of strategic decision-making.

- **Annual Profitability (1960-2015):** The analysis of annual trends reveals 2015 as a standout year, indicating potential shifts in audience preferences, marketing strategies, or economic conditions.

### Budget Dynamics:

- **Top Budget Movies (1960-2015):** The bar chart showcasing the top 10 movies with the highest budget provides insights into the industry's willingness to invest in ambitious projects.

- **Annual Budget Trends (1960-2015):** Understanding the highest budget movie each year and the total budget for every year unveils the financial evolution of the film industry over the decades.

### Genre Exploration:

- **Most Employed Genre (1960-2015):** Drama emerges as the most employed genre, reflecting its enduring popularity and its ability to resonate with diverse audiences.

### Cinematic Personalities:

- **Most Filmed Cast (1960-2015):** Robert De Niro stands out as the most featured actor, contributing to the richness and variety of films across genres.

- **Prolific Directors (1960-2015):** Steven Spielberg takes the lead as the most frequently filmed director, leaving an indelible mark on the cinematic landscape.

### Correlation Insights:

- **Strongest Feature Correlations (1960-2015):** Exploring feature correlations through heatmaps from 1960 to 2015 reveals nuanced connections between different aspects of movies, contributing to a holistic understanding of the dataset.
  

## Key Findings and Insights 2023

### Film Production Companies:
#### Most Movie Count:
- Universal emerged as the leading film production company with the highest number of movie releases in 2023.
- Warner Bros. secured the second position, closely followed by Sony Pictures.

#### Top Revenue Earners:

- Universal, Walt Disney, and Warner Bros. stand out as the top three companies in terms of revenue generation in 2023.

### Movie Genres:
#### Highest Movie Count by Genre:

- Drama claimed the top spot as the most frequently employed genre in 2023.
- Documentary and Comedy followed closely, showcasing diverse preferences in filmmaking.

#### Top Revenue-Generating Genres:

- Action, Adventure, and Comedy emerged as the top three genres contributing the most to revenue in 2023.

These key findings provide a snapshot of the vibrant and diverse landscape of the 2023 movie industry. From the prolific output of film production companies to the preferred genres capturing audience attention, the data reveals intriguing patterns and insights that shape the cinematic experience of the year.
## Conclusions
The movie industry stands as a dynamic and fast-growing force, evolving over decades to become a global cultural phenomenon. Each film within this vast landscape is a unique creation, blending creative expression, technological innovation, and financial investment. As we navigate through the dataset spanning from 1960 to 2015 and delve into the intricacies of the cinematic landscape in 2023, it becomes evident that the movie industry is more than a mere entertainment sector; it's a reflection of societal trends, artistic visions, and economic dynamics.

The diversity of genres, the prolific contributions of actors and directors, and the strategic moves of production companies collectively shape the narrative of this industry. Financial success, while a significant aspect, intertwines with creativity, storytelling, and audience preferences. The dataset serves as a window into this multifaceted world, allowing us to glimpse the trends, correlations, and patterns that define the cinematic experience.

As the movie industry continues to burgeon, it presents not only challenges but also opportunities. Technological advancements, changing viewer habits, and global influences contribute to the industry's constant evolution. The data exploration undertaken provides a snapshot of a vast and ever-changing landscape, inviting further inquiry and analysis.
### Limitation and Future Directions:
While the analysis has offered valuable insights, it is essential to acknowledge the limitation of correlation not implying causation. Additionally, future research could explore external factors influencing movie trends, such as cultural shifts, technological advancements, or global events.

The comprehensive nature of this exploration sets the stage for further in-depth studies, and the project serves as a valuable foundation for understanding the intricate dynamics of the film industry.

</body>
