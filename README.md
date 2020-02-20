# ml4j-quickstart

Get up and running with ml4j quickly, with ml4j-quickstart.

There are many customisations possible with the configuration of the various
ml4j components and defaults.

This project autowires these components and factories with default settings, so
you can get starting working with the project with a single artifact import.

## Quick Start ##

Download the jar though Maven:

```xml
<repository>
  <id>ml4j-snapshots</id>
  <url>https://raw.githubusercontent.com/ml4j/mvn-repository/master/snapshots</url>	
  <snapshots>
    <enabled>true</enabled>
  </snapshots>
</repository>
```

```xml
<dependency>
  <groupId>org.ml4j</groupId>
  <artifactId>ml4j-quickstart</artifactId>
  <version>2.0.0-SNAPSHOT</version>
</dependency>
```

For simple demos of getting started with ml4j, please <a href="https://github.com/ml4j/ml4j-quickstart-demo">ml4j-quickstart-demo</a>.

For more complex examples (eg. Inception V4,  YOLOv2 ), please see the following projects:

https://github.com/ml4j/inception-v4-spring-demo

https://github.com/ml4j/yolo-v2-spring-demo

## Project Status ##

The ml4j-api-2.0.0.RC1 release candidate has now been released, and there are to be no planned changes to the API contract of any of the ml4j-api components before the ml4j-api-2.0.0 final release.   Most of the changes left to be made to the api are for Javadoc and unit tests.

The implementations in the various impl projects are still in snapshot status (eg. ml4j-impl,  ml4j-default-components ).  These projects are almost fully functional, with a couple of exceptions - for example, while batch norm is available for graph networks (eg. Inception networks), it has not yet been implemented for sequential layer networks - also ResidualBlocks have not yet been implemented). 

This remaining to-do functionality should be a matter of re-using the already written components from other parts of the project - however the recent focus has been on delivering a stable API contract in the ml4j-api-2.0.0.RC1 release.

The main technical debt with the impl projects is with unit testing and Javadoc, the coverage of which will need to be much higher before a stable impl release can be delivered.

The various demo projects have acted as integration tests throughout development - eg. the demos in following projects:

https://github.com/ml4j/inception-v4-spring-demo
https://github.com/ml4j/yolo-v2-spring-demo
https://github.com/ml4j/ml4j-neuralnets-demo

