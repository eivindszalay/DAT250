**Report**

Short report on the first experiment assignement.

**What I did:**
* Set up this GitHub for experiment assignments and other work related to DAT250.
* Installed maven with command "brew install maven"
* Signed up at Heroku with a free account.
* Followed the guide "Getting Started on Heroku with Java":
	- Downloaded and installed heroku.
	- Cloned the example app.
	- Created a Heroku project using the cloned repo with "heroku create".
	- Deployed the app with a git push to https://warm-refuge-71098.herokuapp.com/.
	- Opened the app with "heroku open".
	- Viewed the logs with "heroku logs --tail".
	- Scaled the app up and down with "heroku ps:scale web=0/1".
	- Started a local version of the app with "mvn clean install" and heroku local".
	- Made some changes to the app.
	- Ran the changes locally.
	- Deployed the changes.
	- Made changes to the config vars, deployed them.
	- Created a one-off dyno.
	- Tried to provision add-ons, but I were asked for billing information to verify. Skipped this step and played around with pre created postgresql add-on instead.
	- Didn't manage to set up the database so that I could display the database at the app's /db route.

**Conclusion**

The tutorial was easy to follow, with only minor problems except from the last parts concerning the database. 