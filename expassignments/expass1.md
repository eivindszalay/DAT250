Set up a public GitHub (link) for experiment assignments.

I am a Mac user.

Installed maven with command "brew install maven"

Signed up at Heroku with a free account.

Followed the guide "Getting Started on Heroku with Java"
	- Downloaded and installed heroku.
	- Cloned the example app.
	- Created a Heroku project using the cloned repo with "heroku create".
	- Deployed the app with "git push heroku main".
	- Opened the app with "heroku open".
	- Viewed the logs with "heroku logs --tail".
	- Scaled the app up and down with "heroku ps:scale web=0/1".
	- Started a local version of the app with "mvn clean install" and heroku local".
	- Made some changes to the app.
	- Ran the changes locally.
	- Deployed the changes.
	- Made changes to the config vars, deployed them.
	- Created a one-off dyno.
	- Tried to provision add-ons, but I were asked for billing information to verify. i skipped this step. i played around with pre created postgresql add-on instead.
	- Didn't manage to set up the database so that I could display the database at the app's /db route.