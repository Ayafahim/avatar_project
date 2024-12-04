# Avatar: The Last Airbender Social Network Analysis

## Project Overview

This project delves into the intricate social network of characters from Nickelodeon's acclaimed animated series, **Avatar: The Last Airbender**. By analyzing character interactions, emotional dynamics, and their evolution across the series' three seasons, we aim to uncover the narrative elements that contribute to the show's enduring appeal.

### Central Idea

Our primary objectives include:

- **Mapping Connections**: Identifying and visualizing relationships between characters.
- **Analyzing Dynamics**: Examining shifts in dialogues, sentiments, and themes over time.
- **Assessing Narrative Impact**: Understanding how character roles and emotional states influence the plot and story arcs.

By integrating **network analysis** with a deep exploration of character development and narrative progression, we seek to provide insights into the storytelling techniques that make the series exceptional.

### Motivation

As avid fans of Avatar: The Last Airbender, we are fascinated by its depth, complexity, and timeless storytelling. This project allows us to explore questions such as:

- How do character relationships evolve throughout the series?
- What emotional trends are present in dialogues and story arcs?
- How do these patterns contribute to the show's lasting impact?

## Data Overview

Our analysis utilizes the following datasets:

### Primary Datasets

1. **Avatar: The Last Airbender Episode Scrape - IMDb**
   - **Source**: Kaggle
   - **Size**: 26.59 kB
   - **Description**: Contains IMDb ratings and metadata for each episode.
   - **Dataset Link**: [Avatar: The Last Airbender Episode Scrape - IMDb](https://www.kaggle.com/datasets/amiryusoff/avatar-the-last-airbender-episode-scrape-imdb)

   **Columns**:
   - `Season`: The season number (1, 2, or 3).
   - `Episode`: The episode number within the season.
   - `Title`: The title of the episode.
   - `Rating`: The IMDb rating of the episode.
   - `AirDate`: The original air date of the episode.
   - `TotalVotes`: The total number of votes the episode received on IMDb.

2. **Avatar: The Last Airbender**
   - **Source**: Kaggle
   - **Size**: 4.36 MB
   - **Description**: Provides transcripts of the show, metadata, and visualizations.
   - **Dataset Link**: [Avatar: The Last Airbender](https://www.kaggle.com/code/ekrembayar/avatar-the-last-airbender-data-visualization)

   **Columns**:
   - `id`: Unique identifier for each line of dialogue or scene description.
   - `book`: The season of the series (Water, Earth, or Fire).
   - `book_num`: Numerical representation of the season (1, 2, or 3).
   - `chapter`: The title of the episode.
   - `chapter_num`: The episode number within the season.
   - `character`: The character speaking the line; 'Scene Description' if it's a narrative description.
   - `full_text`: The complete text of the dialogue or scene description.
   - `character_words`: The words spoken by the character, excluding scene descriptions.
   - `scene_description`: Descriptive text of the scene's action or setting.
   - `writer`: The writer(s) of the episode.
   - `director`: The director of the episode.
   - `imdb_rating`: The IMDb rating of the episode.

### Supplementary Dataset

- **NRC Emotion Lexicon**
  - **Source**: NRC
  - **Description**: A lexicon that maps words to associated emotions, facilitating sentiment and thematic analysis.

### Data Focus

The primary text analyzed comprises the **transcripts of each episode**, enabling in-depth study of dialogues, sentiments, and thematic elements.

## Goals and Methods

### Key Objectives

1. Construct a **social network graph** to visualize character interactions.
2. Perform **sentiment analysis** on dialogues to identify emotional trends.
3. Examine the **evolution of relationships and emotions** throughout the series.
4. Investigate **narrative patterns** and thematic developments.

### Tools and Techniques

- **Network Analysis**: Utilizing tools like NetworkX to map and analyze character connections.
- **Sentiment Analysis**: Applying the NRC Emotion Lexicon to assess emotional trends in dialogues.
- **Visualization**: Creating interactive graphs and charts to illustrate relationships and trends.
- **Python Libraries**: Employing pandas, NetworkX, matplotlib, and other relevant libraries.

## Significance

This project bridges the realms of storytelling and data analytics, offering a novel perspective on one of the most celebrated animated series. By combining **data science** with **narrative analysis**, we aim to uncover the character dynamics, relationships, and themes that contribute to Avatar: The Last Airbender's timeless resonance.

---

## How to Use This Repository

1. **Explore the Data**: Familiarize yourself with the structure and content of the datasets.
2. **Run the Analysis**: Utilize the provided scripts to generate social network graphs and sentiment visualizations.
3. **Interpret the Insights**: Delve into the results to explore character dynamics and narrative evolution.

---

### Authors

This project is developed by a team of Avatar enthusiasts with a passion for data analysis and storytelling.

### License

This project is open-source under the [MIT License](LICENSE).

---
