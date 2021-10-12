# Travel Tool Build

1. Need an drop down box to pull the orign airport code
2. Need an drop-down box to select destination airport code
3. Need calender to select onward date and return date
4. should show available flight options on the requested query
5. client to select the flight options which will contain flight itinerary details
6. after selecting, we should provide an option to enter traveler first name and last name
7. traveller now should able to print full flight itinerary along with his name and flight information with requested travel dates genarating the pdf


# Suggested changes or elaborations to the project

1. User visits our home page, selects origin airport and then destination airport
2. Selects date ot travels onward and return date
3. This displays a list of flights 
4. User selects the flights to match their plan
5. If user is signed in we allow user to print full flight itenary along with his name and flight information with requested travel dates genarating the pdf
6. If user is not logged in we request user to login or register
7. We provide user with login popup, registration popup

We need to create following APIs using nodejs and express
1. Register user API
2. Login user API
3. Save itenary as draft API
4. Save final itenary API
5. Get itenary PDF API
6. API to show list of available airports(You can also use(or modify) this library created by me [airlines-iata-codes](https://www.npmjs.com/package/airlines-iata-codes))
7. API to get you list of flights, we can do this directly from frontend react but let us create a wrapper API around the API providing us schedule of flights we can look into providers such as [openskynetwork](https://openskynetwork.github.io/opensky-api/rest.html#), please feel free to look into other options as well