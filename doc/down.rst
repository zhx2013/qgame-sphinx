Download and Use QGAME
======================

This section provides a brief instruction on downloading QGAME.

Download
--------

**QGAME-seesaw** downloads could be found in `our github repo`_.

We provide 4 jar files:

qgame-seesaw-<version>.jar
	This is a QGAME-seesaw jar file which is compiled against *IcedTea 7* in *Fedora Schrödinger's Cat*. This file doesn't contain any dependencies. Java 7 users who want to solve dependencies on their own could download this file.
qgame-seesaw-<version>-standalone.jar
	This is a uberjar which is compiled against *IcedTea 7* in *Fedora Schrödinger's Cat*. This jar contains all the dependencies and it runs under Java 7.
qgame-seesaw-<version>-openjdk6.jar
	This is a jar file which is compiled against *openJDK 6* in *Debian Wheezy*. It contains no dependencies. Java 6 users who want to solve dependencies by themselves should choose this file.
qgame-seesaw-<version>-openjdk6-standalone.jar
	This is a uberjar which is compiled against *openJDK 6* in *Debian Wheezy*. This jar contains all dependencies and it runs on JRE 6.

Decide your Java version
^^^^^^^^^^^^^^^^^^^^^^^^

A hard part of choosing the right jar file is to find out which version of JRE are you running. You can simply run::

	java -version

in your terminal.

If you see something like ``java version "1.6.x"``, you are using JRE 6. If it is ``java version "1.7.x"``, it means that the version on your computer is JRE 7.

.. These are links
.. _our github repo: https://github.com/zhx2013/qgame-seesaw/releases

Start the program
-----------------

.. NOTE::
	These instructions assume that you are using the uberjars.

There are two ways of starting ``qgame-seesaw``.

* start from terminal.
* start from you file manager.

Start ``qgame-seesaw`` from terminal
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

#. Use ``cd`` to change your working directory
#. Run ``java -jar qgame-seesaw-*.jar``

Start ``qgame-seesaw`` from file manager
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

It depends on your system. Mostly, there are two possibilities:

* You may start the program directly by clicking on the icon of the jar file.
* A compression software might start after you clicking the icon. Thus you need to right-click and choose to open it in java runtime.
