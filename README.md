### Enveu client library for JavaScript based frameworks

#### Example for Initializing the library　
```javascript
var config = new EnveuConfiguration();
config.setApiKey("<Blah>");
config.setDebug(true);
config.setDevice("mobile");
config.setPlatform("web");
config.setServiceUrl("<Blah Blah>");
config.setServiceEnvironment("qa");
var eClient = new EnveuClient(config);
EnveuLayoutManagerService.listAction(0).execute(eClient);
```

#### Usage 　
```javascript
EnveuLayoutManagerService.listAction(0).execute(eClient, <callback method>);
```
