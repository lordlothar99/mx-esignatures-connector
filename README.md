# mx-signeasy-connector
Mendix integration with [SignEasy](https://signeasy.com/). SignEasy is a digital signature service similar to Docusign and Hellosign, but cheaper. You will need to create an account and set your API key + clientID.

## Local tests
Callbacks won't work locally, so default callback url is ``https://signeasy.requestcatcher.com/``, so you'll be able to see the API callbacks sent by SignEasy, and send the payloads using Postman to your local instance.
