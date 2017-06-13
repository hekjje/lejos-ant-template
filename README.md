# lejos-ant-template

## How to build
**Resolve dependencies**

```$ ant resolve```

**Build jar file**

```$ ant```

**Run jar file**

```$ java -jar dist/App.jar```

*When running the jar file from the local machine you will get an exception do to the code can't find the EV3 brick*

```
Exception in thread "main" lejos.hardware.DeviceException: No brick found
	at lejos.hardware.BrickFinder.getDefault(BrickFinder.java:171)
	at app.Application.main(Unknown Source``` 