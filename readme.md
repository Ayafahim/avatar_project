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

Additionally, we have used **thread discussions** from Reddit to supplement our analysis with fan perspectives:

- [Appa's Lost Days Will Always Be the Saddest](https://www.reddit.com/r/TheLastAirbender/comments/8ezr6b/appas_lost_days_will_always_be_the_saddest/)
- [ATLA Rewatch Season 2 Episode 7: Zuko Alone](https://www.reddit.com/r/TheLastAirbender/comments/gy843t/atla_rewatch_season_2_episode_7_zuko_alone/)
- [I Liked Zuko Alone, but Screw That Village](https://www.reddit.com/r/CharacterRant/comments/n16qvd/i_liked_zuko_alone_but_screw_that_village/)
- [The Painted Lady Is Actually a Good Episode](https://www.reddit.com/r/TheLastAirbender/comments/1b56kmr/the_painted_lady_is_actually_a_good_episode_it_is/)
- [ATLA: What's Wrong with The Great Divide?](https://www.reddit.com/r/TheLastAirbender/comments/44yb5v/atla_whats_wrong_with_the_great_divide/)
- [Is The Episode "The Great Divide" the Worst Episode?](https://www.reddit.com/r/TheLastAirbender/comments/ociiu2/is_the_episode_the_great_divide_the_worst_episode/)
- [The Headband](https://avatar.fandom.com/wiki/The_Headband)
- [ATLA Rewatch S3E2: The Headband](https://www.reddit.com/r/TheLastAirbender/comments/ohxf2c/atla_rewatch_s3e2_the_headband/)
- [Sokka's Master Is One of My Favorite Episodes](https://www.reddit.com/r/TheLastAirbender/comments/kjjguo/sokkas_master_is_one_of_my_favorite_episodes_what/)
- [In Sokka's Master, Master Piandao Knew That Aang...](https://www.reddit.com/r/TheLastAirbender/comments/nsxe9n/in_sokkas_master_master_piandao_knew_that_aang/)

## Data Overview

Our analysis utilizes the following datasets:

### Primary Datasets

1. **Avatar: The Last Airbender**
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
