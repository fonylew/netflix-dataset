# 📊 Netflix Data Challenges

### Challenge 1: The Fresh Starts
**Goal:** List the titles and release dates of the first 10 movies released after January 1st, 2023. Sort them from oldest to newest.

<details><summary>Hint</summary>There is limit.</details>

### Challenge 2: Search for Love
**Goal:** Identify all TV shows that have the word "Love" in their title and were originally produced in English (`locale = 'en'`).

<details><summary>Hint</summary>`like` Love but with wildcards. There are 5 of them</details>

### Challenge 3: Show Longevity
**Goal:** Count how many seasons each TV show has. Display the TV show title and the total count, sorted by the most seasons first.

<details><summary>Hint</summary>Join first, then group by.</details>

### Challenge 4: Binge-Watch Calculator
**Goal:** Calculate the total runtime (in hours) for every TV show by summing up all its seasons' runtimes. Display this as `total_hours`.

<details><summary>Hint</summary>Don't forget to convert the runtime to hours. There are `round`, `sum`.</details>

### Challenge 5: The Heavy Hitters
**Goal:** Filter your previous list to only show TV shows that have more than 5 seasons.

<details><summary>Hint</summary>Similar to Challenge 4, but with `having`.</details>

### Challenge 6: Hall of Fame
**Goal:** Find the top 10 movies that have spent the most cumulative weeks in the Netflix Top 10 list.

<details><summary>Hint</summary> Group by movie title, `cumulative_weeks_in_top10` is the column you need and it should not be null. `max()` and `limit` are also useful. Do you like KPop Demon Hunters?</details>

### Challenge 7: Holiday Vibe Check
**Goal:** Find all movies and TV shows released in the month of December (any year). Label them as 'Movie' or 'TV Show'.

<details><summary>Hint</summary>Extract month and `union` them all! You might find there is no TV Show.</details>

### Challenge 8: Movie Length Labels
**Goal:** Categorize movies by their length: 
- **'Short'**: Under 90 min
- **'Standard'**: 90-120 min
- **'Epic'**: Over 120 min

<details><summary>Hint</summary>`case ... when ... then ... else ... end`</details>

### Challenge 9: Beating the Average
**Goal:** Find all movies that have more views than the average number of views across the entire dataset.

<details><summary>Hint</summary>subquery could be useful to find what is `avg`.</details>
