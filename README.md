Overview
-----------------

A single-page Node.js webapp hosted on Heroku at [www.micropayments.tech](http://www.micropayments.tech/).  

Note that the app runs on a free dyno, so it may take a few seconds to load.


Setup
-----------------

To set up your own monetized webpage, follow these steps:
- Sign up for a [Heroku](https://www.heroku.com/) account and create a free app
- Clone the source for this webapp (`git clone https://github.com/SamvitJ/micropayments-webpage`)
- Replace the hardcoded server IP address in [micropayments.js](https://github.com/SamvitJ/micropayments-webpage/blob/master/js/micropayments.js#L6) with the IP address of your running [payments server](https://github.com/SamvitJ/21BC-server) instance
- Commit the change and push the modified repo to your Heroku remote
- Visit the URL associated with your Heroku app in your browser


More information
-----------------
- See the [parent repository](https://github.com/SamvitJ/Bitcoin-micropayments) of this project.
