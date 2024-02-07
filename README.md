# dogFactsAPI_express

HOW TO USE API ENDPOINTS:

server is listed on port 3000, `localhost:3000`

/facts will get an error result in JSON format 

use `/facts?number=integer` with integer being any number between 1 and 435
to display a number of random dog facts based on the integer provided

example: `/facts?number=2` will display two random dog facts on page 

if 0 is entered, all facts will be displayed

if something less than 0 or greater than 435 is entered, an error is displayed in JSON format 

