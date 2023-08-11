# Starwars API

**Task:** To write a script that prints all characters of a Star Wars movie using the Star Wars API and the request module:

To achieve this task, you can follow these steps:

*Import Necessary Modules*: Begin by importing the request module to make HTTP requests to the Star Wars API.

*Parse Command Line Arguments:* Use a command-line argument parser to retrieve the Movie ID provided as the first positional argument when the script is executed.

*Make API Request:* Construct the URL for the Star Wars API's /films/ endpoint to retrieve details about the specified movie. Make an HTTP GET request using the request module to fetch the movie data.

*Extract Characters List:* Parse the API response to extract the "characters" list associated with the specified movie.

*Print Characters:* Loop through the characters list and print each character's name, displaying one character name per line.
