# project-spotify
#  Spotify Dataset Analysis

This project analyzes a Spotify music dataset using Python and pandas. The goal was to simulate a real-world data analysis scenario and present business-relevant insights using music data.

---

##  Project Overview

We selected a dataset containing thousands of Spotify tracks along with details like:

- Artist name
- Song title
- Genre
- Popularity
- Emotion
- Loudness
- Explicit content
- and more...

Our goal was to extract meaningful insights that could help businesses in the music industry better understand trends, consumer preferences, and artist behaviors.

---

## Questions We Answered

1. **How many songs does each artist have?**  
   → Helps identify prolific artists or large catalogs.

2. **What are the complete details of a specific song?**  
   → Useful for targeted search and recommendation systems.

3. **What is the most popular genre in the dataset?**  
   → Key for understanding music trends and planning promotions.

4. **Who is consistently the loudest artist in the dataset?**  
   → Interesting for sound engineering and listener engagement.

5. **What are the top 10 artists consistently releasing explicit music?**  
   → Can influence marketing decisions and platform filters.

---

##  Key Findings

- **Pop music** was the most dominant genre (excluding unknown values).
- **Lil Wayne** had the most songs among all individual artists.
- **1 800 PAIN** was the loudest artist based on average decibel levels.
- **Lil Wayne**, **Juice WRLD**, and **Gucci Mane** topped the list for most explicit songs.
- The dataset also contained many tracks labeled as `Unknown`, which suggests the need for better data curation.

---

##  How to Run This Project

1. Clone the GitHub repo.
2. Make sure you have Python installed.
3. Install the required library:

```bash
pip install pandas
