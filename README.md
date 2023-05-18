# NBA-Player-Analysis-Package


Our team has developed an NBA Player Analysis Package that allows users to collect and evaluate NBA player information from a given dataset, compute player statistics, and visualize individual performance using graphs and charts. While developing the Python package, the pandas, NumPy, and matplotlib packages will be used to manipulate and visualize data. For our analysis package, we have employed a customized dataset of NBA players, which will be hosted on platforms such as GitHub. This compilation of player statistics from the 1950s to the present includes information such as the player's name, height, weight, position, college, and performance statistics.

The dataset used for the analysis package data is collected, cleaned, and prepared for analysis using pandas and NumPy.

The functions in the code are as follows:

• calculate_career_stats: In the following function, it accepts a player name as an input and returns a dictionary including the player's active years, height in feet and inches, and average weight throughout the players career.

• calculate_player_stats: We have implemented the following function called calculater_player_stats. The function takes the player name as an argument and returns a dictionary containing that player's total points, rebounds, and assists.

• visualize_player_performance: This method takes a player’s name as an argument. It then calculates the players total point, assist, and total rebounds. It then uses the matplot library to generate a bar plot showing the player's points, rebounds, and assists.

• calculate_performance: In this method we have made the use of weights to calculate the player’s performance. Point has a weight of 0.5, assists has a weight of 0.2 and total rebounds has a weight of 0.3. The function then calculates a performance score for each player based on their assists, rebounds, and points.

• top_players: In this function we calculate the top 10 players in the dataset. The function takes input data and returns the top 10 players to a data frame. We have set n=10 to show the top 10 players.

• plot_player_graph: This function takes two arguments. This function accepts a Data Frame containing player names and performance and generates a bar chart to visualize the performance of the top ten players. It shows the total performance, points, assists and rebounds.

• compare_players: This method is used to visualize the top 10 players in the data set and a random player in the data set. Using this function, the user can compare how a random player compares to the top 10 players in the data set. It displays the players performance, points, assists, and total rebounds.

• compare_players_single: This function provides an in-depth analysis; it visualizes a random player and any one random player from the top 10 players in the dataset. This visualization is similar to the above functions but gives a comprehensive insights into the players statistics.

Error Handling: The function, calculate_career_stats, calculate_player_stats, and visualize_player_performance have a try and except block to catch errors. All of the three functions have similar error handling done to catch any errors getting generated. The following error messages will be generated if:

• player_name is None or an empty string, the message "Error: Player name cannot be null or empty" is displayed.

• player_name is not a string, the message "Player name must be string" is displayed.

• player_name includes only spaces or is empty: "Player name cannot be empty or
contain only spaces."

• player_name is not found in the data set , the message "Error: Player not found in data"
is displayed.
