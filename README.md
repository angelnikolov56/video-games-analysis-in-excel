# Video Games Sales Analysis and Visualization

## Introduction

The aim of this project is to build an interactive dashboard in Excel that can be used to analyze data about a topic that I'm passionate about - video games. The [dataset](https://www.kaggle.com/datasets/thedevastator/discovering-hidden-trends-in-global-video-games) is downloaded from Kaggle. It contains sales data for video games from all around the world, across different platforms, genres, and regions from 1983 to 2012. I've cleaned the data, transformed it into long format, made pivot tables to group and aggregate the data, created charts from the pivot tables, and organized them into a dashboard with slices for interactability.

## Data cleaning and transformation

-   Multiple cells in the sales columns (North America, Europe, Japan, Rest of World, Global) had numbers stored as text. I used the VALUE function to convert them to numbers.

-   There was some missing data in the Year column. I manually added them by looking up the release year for each game with missing values.

-   I reshaped the sales columns in order to be able to break down the sales by region. I used Power Query's Unpivot Columns functionality.

After the cleaning and transformation, I proceeded with building the pivot tables and visualizations that can be explored in the file.

## Insights

### Sales Distribution by Market

The sales distribution by market for video games, based on the data from the "Video Games Sales - LONG" sheet, shows the following:

-   **North America**: 2,400.51 million units

-   **Europe**: 1,347.63 million units

-   **Japan**: 605.46 million units

-   **Rest of World**: 393.74 million units

This distribution indicates that North America is the largest market for video game sales, followed by Europe, Japan, and then the Rest of the World. The significant lead of North America in video game sales highlights the region's strong influence on the global video game market.

If we look into the distribution over time we can see a shift in the video game market over the years, with North America maintaining a strong lead, Europe's market share growing, Japan's market share shrinking after an early peak, and the Rest of World market share slowly increasing.

If we look at the dynamic of the global sales over time there appears to be a significant growth period starting in the late 1990s through the mid-2000s, where we see a sharp increase in total sales. This growth period likely corresponds to the rise of home gaming consoles and the increasing popularity of video games across a broader audience. There is a noticeable decline after 2008, most likely due to the economic crisis.

### **Top-Performing Games Globally**

The analysis of the top-performing video games globally, based on total sales across all markets, reveals the following titles as the top sellers:

1.  **Wii Sports**: 81.13 million units

2.  **Super Mario Bros.**: 40.24 million units

3.  **Tetris**: 35.84 million units

4.  **Mario Kart Wii**: 33.56 million units

5.  **Wii Sports Resort**: 31.52 million units

6.  **New Super Mario Bros.**: 29.08 million units

7.  **Wii Play**: 28.71 million units

8.  **Call of Duty: Black Ops**: 28.50 million units

9.  **Duck Hunt**: 28.31 million units

10. **Call of Duty: Modern Warfare 3**: 27.52 million units

### **Top-Performing Genres Globally**

When it comes to genres, the total sales figures highlight the following as the most popular:

1.  **Sports**: 703.24 million units

2.  **Action**: 637.32 million units

3.  **Platform**: 595.16 million units

4.  **Shooter**: 557.35 million units

5.  **Role-Playing**: 496.29 million units

### Top-Rated Video Games

1.  **Metroid Prime**: 96.35

2.  **Tekken 3**: 96.30

3.  **Halo: Combat Evolved**: 95.54

4.  **Half-Life 2**: 95.48

5.  **Metal Gear Solid 2: Sons of Liberty**: 95.04

6.  **Uncharted 2: Among Thieves**: 95.00

7.  **The Legend of Zelda: Ocarina of Time**: 95.00

8.  **Batman: Arkham Asylum**: 94.99

9.  **BioShock**: 94.85

10. **The Legend of Zelda: Twilight Princess**: 94.79

Uncover more insights through the dashboard!
