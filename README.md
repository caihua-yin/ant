Hello world for Ant
===================

#### Project structure
```
${project home directory}: 
    |- build.xml: Ant build file
    |- src/: source code of the project
    |- lib/: libraries required by the project
    |- classes/: class file during build
    |- jar/: jar file after build
```

Take this helloworld project for example:
```
$ tree
.
|-- build.xml
|-- class
|   `-- com
|       `-- caihua
|           `-- helloworld
|               `-- Helloworld.class
|-- jar
|   `-- Helloworld.jar
|-- lib
`-- src
    `-- Helloworld.java
```

#### Install Ant
http://ant.apache.org/manual/install.html

#### Build
- `ant build`: compile java to class file
- `ant jar`: build jar file

#### Run
- `ant run`: run with -classpath
- `ant run-jar`: run with jar file

#### Clean
ant clean

#### Reference
https://ant.apache.org/manual/tutorial-HelloWorldWithAnt.html
