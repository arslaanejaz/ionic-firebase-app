# ionic5-Chat
This is ionic based messenger with firebase.

# Install Method
  1. npm install
  2. ionic serve

# Cordova installation & steps
  1. npm install -g cordova@7
  2. cordova platform add android@7.1.4
  3. cordova build android 

# Create account with firebase 
  1. google-service.json file and upload at root directory of the app
  2. Go to the root directory of the app run following command to install firebase package in your ionic app
      - npm install firebase
  
# Go to src/environment.ts and add 
    const config = {
      apiKey: "your_api_key",
      authDomain: "project_id.firebaseapp.com",
      databaseURL: "https://project_id.firebaseio.com",
      projectId: "project_id",
      storageBucket: "project_id.appspot.com",
      messagingSenderId: "sender_id"
    }; 
