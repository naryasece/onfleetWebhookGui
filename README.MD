# Onfleet Webhook GUI
A simple web interface to make working with Onfleet's webhooks easier. I found interacting with their webhooks through curl commands to be tedious and frustrating, especially during development and using ngrok to forward them to my local env.

## How to use
The app is a single page web interface which can work from your local directory or hosted somewhere on the web. All the resources it needs are pulled from the web.

Instructions:

To view your existing webhooks:

1. Open the page in your browser
2. Enter one of your Onfleet API keys into the appropriate text box
3. Your current webhooks should appear below (you can use the refresh button to manually update the list.)

To add new webhooks:

1. You can add new webhooks by pasting the callback URL into the URL bar (assuming you have set up your project to respond to those webhooks)
2. select the trigger and click Add webhook. The list of current webhooks should automatically update

To Remove old webhooks:

3. Press the Delete button to the right of the webhook
