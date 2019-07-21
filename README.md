var config = new EnveuConfiguration();

config.setApiKey("<Blah>");

config.setDebug(true);

config.setDevice("mobile");

config.setPlatform("web");

config.setServiceUrl("<Blah Blah>");

config.setServiceEnvironment("qa");

var eClient = new EnveuClient(config);
EnveuLayoutManagerService.listAction(0).execute(eClient);