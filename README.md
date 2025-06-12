# 🎥 TMDB Movies Data Analysis

## Introduction

This project performs an in-depth data analysis of a dataset containing approximately **1 million movies** collected from **The Movie Database (TMDB)**. TMDB is a comprehensive online movie database that offers rich metadata for movies across the world, including details such as titles, genres, average ratings, vote counts, revenue, runtime, release dates, and more.

The main objective of this analysis is to uncover meaningful insights into global movie trends, genre popularity, audience ratings, and financial performance, and how these factors interplay across languages, decades, and genres.

## Objectives

- **Clean and prepare the raw data** to ensure high-quality analysis.
- **Visualize trends** across genres, languages, decades, and movie characteristics.
- **Identify relationships** between revenue, ratings, runtime, language, and genre.
- **Extract insights** that may reflect changes in the movie industry over time.

## Data Preparation

The raw dataset contained inconsistencies and missing data that required preprocessing:

- Dropped irrelevant columns (homepage, tagline, poster paths, etc.).
- Removed rows with missing critical fields (titles, genres).
- Filtered out movies with invalid or zero values for runtime, budget, or revenue.
- Normalized date formats and filtered movies released between 1900 and 2025.
- Cleaned and extracted genres from semi-structured strings.

## Exploratory Data Analysis (EDA)

### Genre Analysis

- Extracted genre lists and analyzed genre frequency.
- Identified the **Top 10 most common genres**.
- Tracked the **evolution of genre popularity across decades (1990–2025)**.

### Ratings and Revenue Insights

- Explored how ratings vary across genres.
- Analyzed **average rating trends by decade**.
- Compared revenue and ratings for:

  - **English vs Non-English movies**
  - **Single-genre vs Multi-genre movies**
  - **Hidden gems (high rating, low revenue) and Cult classics (low revenue, high fan base)**

- Investigated how **runtime** and **vote counts** correlate with revenue.

### Language Diversity

- Examined the growth of language diversity in global cinema over time.

## Key Findings

- **Genre Shifts**: While genres like Drama, Comedy, Action, and Thriller dominate overall, the relative popularity shifts over time.
- **Language Trends**: English-language films still dominate revenue, but non-English films show increasing diversity and respectable ratings.
- **Revenue Factors**: Revenue tends to correlate more strongly with **vote counts** (popularity) than with average ratings (critical reception).
- **Runtime & Revenue**: Longer runtimes may be loosely associated with higher revenue, though not universally.
- **Multi-genre films** often outperform single-genre films in both ratings and revenue.
- **Cult classics** often receive high critical acclaim without achieving massive box office success.

## Conclusion

The TMDB dataset provides a rich, multifaceted view of the global movie industry. Through detailed analysis, we observe:

- **Changing audience tastes** over decades.
- The importance of **genre blending** in commercial success.
- The nuanced relationship between **ratings, popularity, and revenue**.
- The growing **diversity of global cinema** in both language and content.

Such analysis offers valuable perspectives not only for movie enthusiasts but also for producers, distributors, and marketers seeking to better understand the evolving cinematic landscape.
