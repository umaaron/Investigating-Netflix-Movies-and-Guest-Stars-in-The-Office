# Investigating-Netflix-Movies-and-Guest-Stars-in-The-Office

Data visualization is often a great way to start exploring your data and uncovering insights. In this notebook, you will initiate this process by creating an informative plot of the episode data provided to you. In doing so, you're going to work on several different variables, including the episode number, the viewership, the fan rating, and guest appearances. Here are the requirements needed to pass this project:

Create a matplotlib scatter plot of the data that contains the following attributes:

Each episode's episode number plotted along the x-axis
Each episode's viewership (in millions) plotted along the y-axis
A color scheme reflecting the scaled ratings (not the regular ratings) of each episode, such that:
Ratings < 0.25 are colored "red"
Ratings >= 0.25 and < 0.50 are colored "orange"
Ratings >= 0.50 and < 0.75 are colored "lightgreen"
Ratings >= 0.75 are colored "darkgreen"
A sizing system, such that episodes with guest appearances have a marker size of 250 and episodes without are sized 25
A title, reading "Popularity, Quality, and Guest Appearances on the Office"
An x-axis label reading "Episode Number"
A y-axis label reading "Viewership (Millions)"
Provide the name of one of the guest stars (hint, there were multiple!) who was in the most watched Office episode. Save it as a string in the variable top_star (e.g. top_star = "Will Ferrell").
