# Weather-App

Project Goal - Create an app that outputs the average temperature of a given time period in a given location.

MVP Scope - A barebones terminal IO system that takes in a location and time period, and outputs the average temperature over that time period.

Future Plans - Have the app also output a recommended clothing level given the temperature. Add humidity into the equation. Output if rain is forecasted. 
               Take in user feedback of the recommended clothing to tweak the algorithm for the specific user. Have the user be able to set a default location.

Tech Stack - 
              Language: Java
              External Tools: Open-Meteo (Weather API), HttpClient (Library), Gson (JSON parser)
              Data will be outputted as plain text.
              To get the data, I will use Open-Meteo to get a json file, and then use Gson to parse it. I will use HttpClient to actually send the API call to Open-Meteo.
