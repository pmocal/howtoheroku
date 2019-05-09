## for my own reference:

Head to root directory of the repo that contains `index.html` which dictates the main HTML page.

Run `touch composer.json` to create a file called `composer.json`.

Add the following line: `{}` inside.

Run `touch index.php` to create a file called index.php.

Add the line: `<?php include_once("index.html"); ?>` inside (or whatever the name of the HTML page is).

Now update the repo on Github if it’s connected to your account or Heroku command `git push heroku master`.

Wait for the automatic deploy to work its magic and tada!
