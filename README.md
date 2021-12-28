# Get-Location
Hey friends, today I Created Get Loction ,
 We See how to Get User Location in HTML CSS & JavaScript.
 now it’s time to get user location in JavaScript using Geolocation API.

The Geolocation API of JavaScript is used to get the geographical position or location of a user.
  Using this API, you will get the current latitude and longitude coordinates of the user if they allow it.
  In this project (Get User Location in JavaScript), on the webpage,
  there is a button labeled as “Detect your location”.
  
  When you clicked on this button, there will open a location prompt with allow and block options.
  If you block the request then the button text will change into “You denied the request”.
  If you allow the request then there will show “detecting your location”. After few seconds,
  there is shown your current location including city, postal code, and country.

In the console of a browser, you’ll get many other location details including road, municipality, continent, etc.
 
 let’s understand the main JavaScirpt codes behind creating this project.
 In JavaScript codes, on the button click, first, I got the current latitude and longitude coordinates of the user device using the geolocation API.

Then using fetch API,
 I sent a get request to the opencagedata server with passing those coordinates and got all the location details of it means I used opencagedata API to get all location details of those coordinates.
 Remember, you should never store your API key in the JavaScript file because it’s a client-side language. So users can easily get your key and misuse it.
