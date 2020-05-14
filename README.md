# dev-tracker

## Firebase
* I have added a deploy script to the scripts folder
```
npm install firebase-tools --no-save # I have purposefully not installed globally
./node_modules/.bin/firebase login 
./node_modules/.bin/firebase init # only do this once
./node_modules/.bin/firebase deploy # uses firestore.rules
```

## Hosting
* https://dev-tracker.tripattern.com
* https://dev-tracker-c1ae9.web.app/
### References
* https://www.pawangaria.com/post/map-custom-domain-with-godaddy-firebase/
* Note that I did not put the whole domain in the A record only the subdomain part (dev-tracker)

## Cloudstore

## Authentication
* https://github.com/firebase/firebaseui-web-react
* https://developer.github.com/apps/building-oauth-apps/creating-an-oauth-app/
