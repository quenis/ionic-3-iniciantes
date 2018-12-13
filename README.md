## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

* [Node.js](https://nodejs.org)

* Ionic and Cordova:
```
$ npm install -g cordova ionic
```

### Installing

```
$ git clone https://github.com/fortDev/ionic3-angular4-basic-app-login.git 
$ cd ionic3-angular4-basic-app-login
$ ionic serve --lab
```

### Deployment

If the error saying that you are missing the ionic-scripts dependencies occurs, execute these commands:

```
npm cache clean --force
npm install @ionic/app-scripts@latest
```

Android:
```
$ ionic cordova build android
```

iOS:
```
$ ionic cordova build ios
```