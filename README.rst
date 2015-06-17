example.java.helloworld
=======================

"Hello World" Example for Java based a articule.

The structure ``HelloWorld`` package is like this: ::

  example.java.helloworld/
  |-- HelloWorld
  |   `-- Main.java
  |-- LICENSE
  |-- Manifest.txt
  `-- README.md

For compile the main class for package, execute the follow command: ::

  javac HelloWorld/Main.java

This generate the ``Main.class`` file into ``HelloWorld`` directory.

For run the main class for package, execute the follow command: ::

  java -cp . HelloWorld.Main

This show the ``Hello world`` message.

For pack the main class for package as a JAR file, execute the follow command: ::

  jar cfme Main.jar Manifest.txt HelloWorld.Main HelloWorld/Main.class

For run the JAR file packed, execute the follow command: ::

  java -jar Main.jar

This show the ``Hello world`` message.

Reference
=========

- `java - How to run a JAR file - Stack Overflow <http://stackoverflow.com/questions/1238145/how-to-run-a-jar-file>`_.

- `Setting an Application's Entry Point (The Java™ Tutorials > Deployment > Packaging Programs in JAR Files) <http://docs.oracle.com/javase/tutorial/deployment/jar/appman.html>`_.
