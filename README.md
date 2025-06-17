# Data-Governance-Project
# Dataset Description:
    
    Overview: 
The Netflix Titles dataset is a comprehensive compilation of movies and TV shows available on Netflix, covering various aspects such as the title type, director, cast, country of production, release year, rating, duration, genres (listed in), and a brief description. This dataset is instrumental for analyzing trends in Netflix content, understanding genre popularity, and examining the distribution of content across different regions and time periods.

    Features: 
1-show_id: A unique identifier for each title.
2-type: The category of the title, which is either 'Movie' or 'TV Show'.
3-title: The name of the movie or TV show.
4-director: The director(s) of the movie or TV show. (Contains null values for some entries, especially TV shows where this information might not be applicable.)
5-cast: The list of main actors/actresses in the title. (Some entries might not have this information.)
6-country: The country or countries where the movie or TV show was produced.
7-date_added: The date the title was added to Netflix.
8-release_year: The year the movie or TV show was originally released.
9-rating: The age rating of the title.
10-duration: The duration of the title, in minutes for movies and seasons for TV shows.
11-listed_in: The genres the title falls under.
12-description: A brief summary of the title.

    Insights & observations:
Netflix stands as a leading force in the realm of media and video streaming. With a staggering array of over 8,000 movies and TV shows accessible on their platform, as of mid-2021, their global subscriber count exceeds 200 million. This tabulated dataset comprehensively catalogs all offerings on Netflix, including vital details such as cast, directors, ratings, release year, duration, and more. This analysis will remove all the nulls, duplicates , and errors improving their data to achieve more accurate numbers.

    Problem Definition: 
The Main problem is that we have a dataset that has many issues like missing values, nulls, duplicates, and many other issues so we want to clean this data at the first step. We want to ensure the validation of this data and secure it by many techniques, such as Anonymization, and pseudonymization. 

    Methodology:
The methods I used for securing data are Anonymization such as Masking, suppression, synthetic,  nulling, and swapping,
 pseudonymization such as Hashing and Encryption.
Here are some screenshots from the code.
