Modification of https://github.com/arcada-uas/TechLabs-Expressions-GUI
fork of https://github.com/arcada-uas/TechLabs-Expressions-API

# Api_Expressions
An Api what has more expressions than my thesis one (slutarbete_api).
This is Flask based code and has a SVG data for different expressions.

## Code
- This Api has a Docker container, what will automatically download Flask when opening the code in a container.
- To run the code, one simply can write: flask run. 

## URL
- The plain localhost URL will serve the face gui in the browser, to show that the applicaion is working.
- When writing "your_URL"/face/all then one gets all the data that is stored in this API.
- To get a secifict expression one has to write "your_URL"/face?name=smile. Instead of smile one could use  other expression name that the API data has and one wants to use.

