KGLM - Kotlin OpenGL Mathematics Library
======================================

A *conceptual* port of the [OpenGL Mathematics](http://glm.g-truc.net/) C++ 
library (GLM). Inspired by [JGLM](https://github.com/jroyalty/jglm). I call this conceptual because a direct port of GLM to Kotlin wouldn't
make a ton of sense.  So, instead, I've taken the concept of providing some of
the functionality of [GLSL](http://www.opengl.org/documentation/glsl/) and
the missing matrix capabilities of modern OpenGL and move those to Kotlin.

The current version is **1.0.0**.


Using
-----

KGLM is available in Maven Central so just add this to your POM (or adapt to whatever build tool you use that supports Maven artifacts):

```
<dependency>
    <groupId>com.hackoeur</groupId>
    <artifactId>kglm</artifactId>
    <version>1.0.0</version>
</dependency>
```

Building
--------

JGLM does not require any external libraries!  The only things you'll need are

* Java 1.6 or greater and
* Maven 3.x

In order to build just clone the repository and run:

```
mvn clean install
```
