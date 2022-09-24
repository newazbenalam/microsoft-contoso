# Windows
set FLASK_ENV=development

# Linux/macOS
export FLASK_ENV=development

# Start the server
flask run


===================================================================

Create .env file to store the key
Return to Visual Studio Code and create a new file in the root of the application by selecting New file and naming it .env

The . at the beginning of the file is required.

Paste the following text into .env

KEY=your_key
ENDPOINT=your_endpoint
LOCATION=your_location
Replace the placeholders

your_key with the key you copied above
your_endpoint with the endpoint from Azure
your_location with the location from Azure

Your .env file should look like the following (with your values):

KEY=00d09299d68548d646c097488f7d9be9
ENDPOINT=https://api.cognitive.microsofttranslator.com/
LOCATION=westus2