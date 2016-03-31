The aim of this project is to create a plugin for (or instantiation of) [Logback](http://logback.qos.ch/) that supports the _literate_ style of structured logging where format arguments are preserved as named properties in the (usually JSON) log event.

```java
String name = "world";

logger.debug("Hello {name}.", name);

// Produces an event where name == "world"
```

Currently planning the approach, all input welcome. For an idea of where this is headed check out [Serilog](http://serilog.net).
