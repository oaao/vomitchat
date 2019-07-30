# vomitchat

A Vue-based chat app which employs CometChat and its JavaScript SDK.

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Run your unit tests
```
npm run test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### obtaining a CometChat API key

* [register](https://app.cometchat.com/#/register "CometChat registration") a (free) CometChat Pro account]

* from the dashboard, add a new app

* in the app's `Explore` > `API keys`, generate a new key (`fullAccess`) or just use the one that was automatically made upon app creation

* in the app's `Groups`, either create and configure your own group or use the demo group that was automatically generated upon app creation

* to integrate CometChat with this project, you will need the `App ID` and `API key`, as well as the `GUID` of the `Group` you will be using.

* add the `App ID`, `API key`, and `GUID` values to the `.env` file found in the application root folder.
