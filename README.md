



# Social Graphs Project: Taylor Swift Network and Analysis
## Project Overview
This project involves building and analyzing a Taylor Swift song network, focusing on the lyrical and thematic relationships between her songs. The network analysis allows us to explore Taylor Swift's songwriting patterns, thematic communities, and song popularity through advanced techniques in natural language processing, network analysis, and sentiment evaluation.

**Students:** 
- Raquel Chaves Martinez (s243297)
- Paula Gambus i Moreno (s233219)
- Alessia Saccardo (s212246)

**Dataset source:** https://www.kaggle.com/datasets/delfinaoliva/taylor-swift-discography (downloaded 6/11/2024)

## Project Structure
The project is divided into the following sections:

**1. Data Collection and Analysis**
    - Taylor Swift Dataset Analysis: Exploration of Taylor Swift's discography, including songs, albums, Spotify streams, and genres.
    - Metacritic Web Scraping: Collecting album reviews and scores from Metacritic for sentiment and popularity correlation.
**2. Network Construction**
    - Song Similarity with TF-IDF: Computing lyrical similarity between songs using TF-IDF and cosine similarity.
    - Network Creation: Constructing a directed graph where songs are nodes and edges represent chronological influence based on shared words.
**3. Network Analysis**
    - Degree, in-degree, and out-degree distributions were analyzed to identify influential songs.
    - Comparison between Louvain-based communities and album-based communities.
**4. Sentiment Analysis**
    - Using the LabMT wordlist, the sentiment of each song was evaluated.
    - Happy, neutral, and sad word distributions across popular songs were visualized to uncover emotional patterns.
**5. Popularity and Critical Reception**
    - Correlation between Spotify streams and Metacritic scores was analyzed.
    - Original albums and "Taylor’s Version" re-releases were compared for critical reception and popularity.
