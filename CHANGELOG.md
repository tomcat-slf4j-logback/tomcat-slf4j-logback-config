Notable Changes
---------------
Release 1.4.0

 - Drop collection of logback-access and logback-core as we will shade them now to avoid any other potential conflicts

Release 1.3.0

 - Require java 8

Release 1.2.0

 - Build updates / using parent with changes to dependency stack to optional

Release 1.1.0

 - Split up project into individual pieces.  The Config manages defaults across the project for team. See Individual tomcat modules for more details [tomcat-slf4j-logback](https://github.com/tomcat-slf4j-logback).
