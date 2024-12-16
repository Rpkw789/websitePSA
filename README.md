# Automatic Rerouting of SeaRoute - Backend
This is the frontend for our website that automatically reroutes when a relevant news that may impact sea trade is published online.

This website is connected to our backend which listens to the published news using NewsAPI(https://newsapi.ai/#). It will feed relevant news to OpenAI to read and determine it's severity level. Such news will be flagged up to admins to view. Upon confirmation of the severity of the news, the user will confirm the news on our website which will then reroute affected ships.

This website is made using React, with a boiler template from ubaimutl.

# Set Up
Get the code - Clone this repo
 
Install required dependencies

<pre>yarn install</pre>


Start the server

<pre>yarn start</pre>
