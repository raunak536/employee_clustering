# Problem Statement : 
Cluster incoming students into different groups based on their employment details like CTC, designation, year of joining etc.
    
# Insights : 
- Backend/Fullstack/Frontend Engineers are the most common job positions
- nvnv wgzohrnvzwj otqcxwto is the most common company ~ 4%
- Engineering Leadership is the highest paid job ~ 26Lakh median salary
- bxwqgogen is the company which has highest median salary ~ 26Lakh
- There is very linear relationship between number of years spent at an organization vs their salary
- Median salary for employees who joined in
    - 2000 -> 26 Lakh
    - 2021 -> 6 Lakh
- We got a Hopkins score ~ 0 meaning there is strong clustering tendency in the data
- Kmeans, DBSCAN and Hierarichal clustering techniques all showed presence of 2 clusters in our dataset
- There is a 80-20 split between these two clusters
- Minority class are mostly backend/fullstack engineers or have unidentified (other/nan/misc) job positions
- The minority cluster are the employees who work at the top companies with lower experience and lower ctc
- The majority cluster are the employees who dont work at the top companies but have higher experience and ctc


# Recommendations : 
- We can create two pitches for these 2 clusters : 
    - The majority cluster needs to be shown how we can help them get into the top companies of their fields
    - The minority cluster needs to be shown how we can help them get into higher positions in their existing companies.
- We can also promote interactions between these two clusters so that they can impart each other with their own learnings
    - Minority cluster can share their experience of working in a big company
    - Majority cluster can share their experience and skills required to grow up in an organization