# client

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Lints and fixes files
```
yarn lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


This profile provides a client/server multi-project build structure. The server Grails app is using the rest-api profile with CORS enabled. It can be started using 'grails run-app' or using the Gradle wrapper:

./gradlew server:bootRun

The Vue client app has been built via the Vue CLI (https://cli.vuejs.org/). It can be started via npm/yarn (`npm run serve`/`yarn serve`), or by using the Gradle wrapper (which will install npm dependencies automatically if needed):

./gradlew client:serve

For support, please use the Grails Community Slack (https://grails-slack.cfapps.io) or open an issue on Github: https://github.com/grails-profiles/vue/issues

