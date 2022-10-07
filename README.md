# Signeasy connector
Mendix integration with [SignEasy](https://signeasy.com/). SignEasy is a digital signature service similar to Docusign and Hellosign, but cheaper. 

## Setup
You need to create an account on [SignEasy](https://signeasy.com/), and set the API key (access token) + clientID in the ``Config`` entity.

## Local tests
Callbacks won't work locally, so default callback url is ``https://signeasy.requestcatcher.com/``, so you'll be able to see the API callbacks sent by SignEasy, and send the payloads using Postman to your local instance.

## SignEasy documentation
You can find the documentation [here](https://docs.signeasy.com/docs)
