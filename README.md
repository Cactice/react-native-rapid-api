# react-native-rapid-api
This is an npm package for using Rapid API with react native.

# Get Your RapidAPI Credentials

1. Go to your RapidAPI Dashboard (https://dashboard.rapidapi.com)
2. Go to My Apps => (Your application) =>  Security

# How to Use

Run the following command to install the package:
```
npm install react-native-rapid-api --save
```

In your code, add the following code to import the RapidAPI SDK:
```
import RapidAPI from 'RapidAPI'
const rapid = new RapidAPI("Your RapidAPI Credentials Project", "Your RapidAPI Credentials Key");
```

(Example) Call the NASA API and check out the picture of the day:
```
rapid.call('NasaAPI', 'getPictureOfTheDay', {});
```
