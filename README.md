# My minimal Firefox config

## Installation / Configuration

1. Install [Firefox](https://www.mozilla.org/en-US/firefox/new).
2. Install [Sidebery](https://addons.mozilla.org/en-US/firefox/addon/sidebery).
3. Download the "sidebery-data-###.json" and "userChrome.css" files.
4. Open SideBery's settings and navigate to the "Help" section, click the "Import addon data" button and select the "sidebery-data-###.json" file.
5. In Firefox's address bar, type "about:config". Search for "stylesheets" and double-click the "toolkit.legacyUserProfileCustomizations.stylesheets" field to toggle it to "true".
6. In Firefox's address bar, type "about:profiles". For the profile currently in use, click "Open Folder" on the "Root Directory". Create a new folder named "chrome" inside the folder that opens, then paste the "userChrome.css" file into the "chrome" folder.
7. Restart Firefox and everything should work!
