# Auth with React Router and Firebase
authentication and protected routes with React Router and Firebase.

*Using React 15.3.X, React Router 2.6.X and Firebase 3.3.X*

#### Features:
* Protected Routes with React Router
* Register new users with Firebase
* Add new users to ```/users``` in your Firebase
* Login/Logout Functionality
* Simple Boostrap UI

#### Instructions:
* `git clone this_repo && cd this_repo`
* `npm install`
* [Create a new firebase app](https://console.firebase.google.com/)
* Navigate to the Authentication tab, SIGN-IN-METHOD, and enable Email/Password
* Put your Firebase app configurations to `firebase.config.js` file.
* Run `npm start` an open http://127.0.0.1:8080/public in your browser


##### Notes:
Dashboard page is a secure route that can only be viewed by logged in users, it’s here where we will place the individual user scorecard(s) along with whatever information that user can view.
