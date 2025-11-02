# rock paper siccors game dashboard
###### display the remainding number of card by HTML and firebase
## Setup
1. Go to https://console.firebase.google.com and create a new project.
2. In the project, enable the Realtime Database (under Build > Realtime Database).
3. For security, set database rules to allow read/write (e.g., `{ "rules": { ".read": true, ".write": true } }` for testing; restrict later for production).
4. Get your Firebase config from Project Settings > General (under "Your apps" > Web app). It looks like:
```javascript
{
  "apiKey": "AIzaSy...",
  "authDomain": "your-project.firebaseapp.com",
  "databaseURL": "https://your-project-default-rtdb.firebaseio.com",
  "projectId": "your-project",
  "storageBucket": "your-project.appspot.com",
  "messagingSenderId": "...",
  "appId": "..."
}
```
1. Replace the placeholder `firebaseConfig` in the code below with yours.
2. Host the HTML files somewhere accessible (e.g., GitHub Pages, Vercel, or local server). Multiple users can open the same file on different devices, and edits will sync in real-time via Firebase.

## template
#### try it out on [rocks.m4s73r.org](http://rocks.m4s73r.org "rocks.m4s73r.org")

## screenshot

![](https://github.com/M4st3r-4ss/-rock-paper-siccors-game-dashboard/blob/main/screenshot.png?raw=true)
