



# Social Graphs Project: Taylor Swift Network and Analysis
## Project Overview
This project involves building and analyzing a Taylor Swift song network, focusing on the lyrical and thematic relationships between her songs. The network analysis allows us to explore Taylor Swift's songwriting patterns, thematic communities, and song popularity through advanced techniques in natural language processing, network analysis, and sentiment evaluation.

**Students:** 
- Raquel Chaves Martinez (s243297)
- Paula Gambus i Moreno (s233219)
- Alessia Saccardo (s212246)

**Dataset source:** https://www.kaggle.com/datasets/delfinaoliva/taylor-swift-discography (downloaded 6/11/2024)

## Project Structure

1. **Data Collection and Analysis**
   - **Taylor Swift Dataset Analysis:** Exploration of Taylor Swift's discography, including songs, albums, Spotify streams, and genres.
   - **Metacritic Web Scraping:** Collecting album reviews and scores from Metacritic for sentiment and popularity correlation.

2. **Network Construction**
   - **Song Similarity with TF-IDF:** Computing lyrical similarity between songs using TF-IDF and cosine similarity.
   - **Network Creation:** Constructing a directed graph where songs are nodes and edges represent chronological influence based on shared words.

3. **Network Analysis**
   - **Degree, In-Degree, and Out-Degree Distributions:** Analysis to identify influential songs.
   - **Community Detection:** Comparison between Louvain-based communities and album-based groupings.
   - **Centrality Analysis:** Evaluating node centrality measures to identify key songs within the network.

4. **Sentiment Analysis**
   - **LabMT Wordlist Sentiment Evaluation:** Sentiment analysis of each song.
   - **Sentiment Distribution Visualization:** Happy, neutral, and sad word distributions across popular songs were visualized to uncover emotional patterns.

5. **Popularity and Critical Reception**
   - **Spotify Streams vs. Sentiment Scores:** Examining the relationship between song sentiment and popularity as indicated by Spotify streams.
   - **Spotify Streams vs. Metacritic Scores:** Analyzing the correlation between critical acclaim and popularity.
   - **Original vs. "Taylor’s Version" Albums:** Comparison for critical reception and streaming performance.

