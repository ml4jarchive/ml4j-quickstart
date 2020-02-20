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


