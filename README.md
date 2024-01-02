# Football API Project - Odds for Premier League Matches

This project involves making an API request to the [Football API](https://www.api-football.com/) to gather information about odds offered by various bookmakers, for the Premier League matches that were played on December 30. The main goal is to rank the bookmakers based on their offering of odds for a particular betting market.

## Getting Started

1. **API Key:**
   Get your API key from [Football API](https://www.api-football.com/) to access the data.

2. **Project Details:**
   - The initial step is to retrieve information of bets for the Premier League fixtures that were played on December 30 using the 'https://v3.football.api-sports.io/odds' endpoint.

   - The script makes an API request to the "odds" endpoint and saves the received JSON response to a file for future reference and data manipulation.

   - After retrieving the JSON data, the script parses it, and additional processing is performed. This includes deleting and renaming columns to refine the dataset and for clarity.

   - Visualizations are created to facilitate both comprehension and analysis of the data.
   
   - Filtering and grouping data based on betting markets and outcomes to create matrices for a better interpretation of odds. The purpose is to facilitate a more insightful analysis and ranking of bookmakers using simple statistical methods.

   - Creating a function that builds on the logic of the previous steps.

## API Documentation

Please check out the [Football API Documentation](https://www.api-football.com/documentation-v3) for detailed information about available endpoints, parameters, and responses. 

## Contributing

Feel free to contribute to the project.