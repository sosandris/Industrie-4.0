# OPTO22 PAC REST API tester
To find out if a SNAP PAC responds to AJAX calls directly from the browser:
1. serve `index.html` from a web server (Apache, IIS, Express, etc).
1. Then, browse to the site, e.g. `http://localhost/`.
1. Hit F12 to open the Dev Tools
1. Press the `GET w/jQuery` button
1. Watch what happens in the Dev Tools Console and Network tab.

If the browser tells you anything wrong about `OPTIONS` or `Pre-flight` not successful, then the PAC does not support your scenario.

Currently (April 2018), it is not supported. See the png files for details.