DIAZI-App
=========

### About

This node-red App is created for HAW-Landshut's Project (DIAZI)
The app depends on axios which is added to the `package.json` file

the following needs to be added to the `setting.js` file of __Node-red__

```js
functionGlobalContext: {
    axios: require('axios')
}
```

