# simple-api-bungie-destiny
Youtube Simple API series example for Bungie's Destiny

## Steps
1. Create an account with one of the platforms necessary to create a bungie account.
    * XBOX
    * Playstation
    * Steam
    * Stadia
    * Twitch
1. Create/Register your app: https://www.bungie.net/en/Application
    * OAuth Client Type: Confidential
1. Copy App Credentials and Endpoints from app details page
    * API key
    * Client Id
    * Client Secret
    * Authorization url
1. Clone git repo: [https://github.com/tekksparrow-programs/simple-api-bungie-destiny]
1. Fill out `.env` file with data copied from the app details page
1. Set up working environment
    * `python3 -m venv venv`
    * `source venv/bin/activate`
    * `pip3 install requests requests-oauthlib python-dotenv`
1. Run the program
    * `python3 simple-api-bungie-destiny`
