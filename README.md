# Review API Documentation
## Main Features
1. Titles Data
 - Fetch single/multiple titles
 - Search by keywords, title name, or aka
 - Get ratings, episodes, seasons, upcoming releases  
2. Actors Data
 - Actor details, known works, profession, etc.  
3. Lists & Rankings
 - Most popular, top rated, box office, etc. 
4. Utility Data
 - Title types, genres, available list names 
5. Flexible Querying
 - Filters by year, genre, title type
 - Sort options (year ascending/descending)
 - Selective data fields using the info parameter
## API overview
1. Massive movie & TV database
 - Covers over 9 million titles (movies, series, episodes) and 11 million people (actors, directors, crew).
 - Includes rich details like plots, genres, trailers, ratings, awards, box office, and more.  
2. Flexible search & filtering
 - Search by keyword, exact/partial title, or alternate title (aka).
 - Filter by year, genre, or title type.
 - Sort results (e.g., by year ascending/descending).
3. Sort results (e.g., by year ascending/descending).Detailed title & episode info
 - Get complete or minimal data for any title using the info parameter.
 - Fetch ratings, seasons, episodes, and upcoming releases.
 - Retrieve multiple titles at once or by a list of IMDb IDs.
## Available Endpoints
1. Titles
 - /titles – Multiple titles (with filters/sorting)
2. Search
 - /titles/search/keyword/{keyword} – Titles by keyword  
3. Actors
 - /actors – Multiple actors (with filters)  
4. Utils
 - /title/utils/titleType – List of title types
## Error Handling
## Usage Limits and Best Practices
