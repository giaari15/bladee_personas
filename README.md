## Out In Tech Spring 2025 Cohort Project: Archetypal Analysis on Bladee Lyrics

## About the Project

Many fans characterize Bladee, swedish rapper, into a few archetypes qualitatively, so I wanted to explore if these archetypes could be found through his lyrics. I used the LyricsGenius API to collect all Bladee song lyrics, cleaned and preprocessed the data, 
vectorized each line of lyric with SBERT, and then approximated archetypal analysis with non-negative matrix formation and with an autoencoder and compared the two methods' results with basic data visualizations. 

## Tools/Libraries Used

- LyricsGenius API
- SBERT (SentenceTransformers)
- Sci-Kit Learn (NMF)
- PyTorch
- Matplotlib/Seaborn
